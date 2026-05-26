# 自进化 Wiki 知识库设计方案

> Self-Evolving Wiki Knowledge Base — A Portable Design
>
> 版本 1.0 · 2026-05-24
>
> 本文档是**领域无关**的。它最初为神经科学每日知识库设计，但其架构、循环和协议可直接移植到任何持续学习的知识库（法律、某个代码库、个人研究、某个行业追踪等）。第 10 节专门讲如何移植。

---

## 0. 设计目标

一个真正"会生长、会自我进化"的知识库，必须同时满足三件事：

1. **积累**：新知识不是简单堆叠新文件，而是让既有主题页变得更深、更准。
2. **不腐烂**：旧页面不会因为新内容而被静默覆盖或自相矛盾；矛盾被显式记录和处理。
3. **可导航、可问询**：任何时刻都能回答"我现在对 X 的理解是什么""我还不知道什么""下一步该学什么"。

大多数"每日生成"系统只做到了第 0 件事的反面——它们产出**孤立的、带时间戳的文章流**，三个月后你拥有 90 篇互不连接的文章，而不是一个知识体系。本方案修复这一点。

---

## 1. 核心理念：情景—语义双层架构

借用人脑记忆系统作为设计隐喻（也是工程原则）：

| 人脑 | 知识库 | 性质 |
|------|--------|------|
| 情景记忆（海马） | `articles/` 每日文章 | 时间戳、append-only、**永不改写** |
| 语义记忆（新皮层） | `wiki/` 主题页 | 活的、**持续修订**、永远代表当前理解 |
| 记忆固结（睡眠） | **每日固结步骤** | 把文章中的知识整合进 wiki |
| 联想网络 | `wiki/_graph.json` | 概念之间的有类型连接 |

**关键洞察**：文章和 wiki 不是冗余的。文章是"证据日志"（我在 2026-05-24 读了这些论文、得出这些理解），wiki 是"当前信念"（我现在认为动作电位是这样工作的）。两者分工明确：文章保证可追溯性和诚实，wiki 保证可用性和生长。

---

## 2. 三条不可违反的不变量

任何一次运行都不得破坏这三条：

1. **情景层 append-only**：永不修改或删除任何已发布的 `articles/`、`notes/`、`sources/`、`logs/` 文件。历史就是历史。
2. **语义层永远当前**：每个 wiki 页面顶部的"当前理解"必须反映**截至今天**的最佳认识。过时的认识移入页内"修订历史"，不留在正文误导。
3. **来源可追溯**：wiki 页面中的**每一条事实主张**都必须能回溯到 (a) 一篇源文章 和 (b) 一个一手引用（PMID/DOI/官方 URL）。没有来源的句子不允许进入 wiki 正文。
4. **单一真相分支（连续性的命脉）**：知识库的全部累积状态必须长期沉淀在**同一个持久分支**（默认即 `main`）。每次运行都**从最新的该分支出发，并把当天产出写回该分支**。绝不让架构或历史"搁浅"在某个一次性分支上——那会让下一次运行从空白起步，知识库就此断裂。若流程中必须用临时分支，当天结束**必须合并回主分支**。同时确认调度触发器的 base branch 指向该主分支。

---

## 3. 目录结构

```
<repo>/
  KNOWLEDGE-BASE-DESIGN.md      # 本文档（移植到新库时一并复制）
  ROUTINE.md                    # 每日运行指令（操作手册）

  neuro-daily/                  # 一个知识库实例（换领域时改这个名）
    # ───── 情景层（append-only）─────
    articles/   YYYY-MM-DD-slug.md
    notes/      YYYY-MM-DD-reading-notes.md
    sources/    YYYY-MM-DD-sources.json
    logs/       YYYY-MM-DD-run.log

    # ───── 语义层（活页，持续修订）─────
    wiki/
      _TEMPLATE.md              # 新页模板
      index.md                  # 全库地图（人读）
      _graph.json               # 知识图谱：节点 + 有类型的边（机读）
      CHANGELOG.md              # 每日 wiki 变更日志
      <domain-1>/<topic>.md     # 主题页，按领域分目录
      <domain-2>/<topic>.md
      ...

    # ───── 治理层（元状态）─────
    state/
      topic_ledger.json         # 每日产出台账（防重复、记录选题）
      maturity_index.json       # 每个 wiki 页的成熟度/置信度
      contested_claims.json     # 矛盾登记册 ← 自进化的核心
      unresolved_questions.md   # 未解问题队列（驱动选题）
      source_registry.json      # 用过的来源（防无说明重复）
      monthly_synthesis.md      # 月度大图景
```

要点：
- `wiki/` 下按**领域**分子目录（neurons / circuits / concepts / methods / theories / diseases…），保持文件名 = `slug`，便于 `[[wikilink]]` 引用。
- 下划线开头的文件（`_TEMPLATE`、`_graph`）是基础设施，与内容页区分。

---

## 4. Wiki 页面规范

### 4.1 YAML Frontmatter（机读元数据）

每个 wiki 页**必须**以这段 frontmatter 开头。这是让知识库可问询、可生成图谱的关键。

```yaml
---
title: 动作电位
slug: action-potential
domain: neurons
type: mechanism          # concept|mechanism|structure|region|method|disease|theory|entity
status: established       # speculative|emerging|mainstream|established|contested
confidence: high         # high|medium|low
created: 2026-05-24
updated: 2026-05-24
revision_count: 1
dimensions: [molecular, cellular]   # 领域自定义的"层级/维度"标签
related: [axon-initial-segment, voltage-gated-sodium-channel]
prerequisites: [membrane-potential, ion-channels]
opens_questions: [Q-ap-threshold-modulation]
source_articles: [2026-05-24-axon-initial-segment]
key_sources: ["PMID:23055474", "PMID:41930336"]
---
```

### 4.2 正文结构

```markdown
# 动作电位 (Action Potential)

> **一句话定义**（永远保持当前、准确）

## 当前理解
[活的综合段落。这是会被反复修订的核心。写"我们现在认为……"。]

## 关键机制
[分层解释：分子 → 细胞 → 回路 → 行为，按需。]

## 关键证据
| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| AIS 钠通道密度约为胞体 50 倍 | 超分辨成像+膜片钳 | PMID:41930336 | 高 |

## 连接
- [[轴突始段]] — 动作电位的发起位点
- [[电压门控钠通道]] — 实现动作电位的分子基础

## 未解问题
- 见 state/unresolved_questions.md 中的 Q-xxx

## 修订历史
- 2026-05-24 · 创建 · 基于《决策的解剖学》一文 · 初始置信度：高

## 来源文章
- [[2026-05-24-axon-initial-segment]]
```

**修订历史**是自进化的可见证据：任何人翻开一页，都能看到这个概念的理解是如何随时间被一次次修正、加深的。

---

## 5. 知识成熟度模型

每个页面（乃至每条主张）都带一个 `status`，它会**随证据积累而流动**：

```
speculative ──→ emerging ──→ mainstream ──→ established
      ↑                                          │
      └──────────── contested ←──────────────────┘
                  (出现可信的反向证据时)
```

- **speculative**：单篇预印本/单一来源/作者推测。
- **emerging**：若干独立来源，但尚未形成共识。
- **mainstream**：综述承认的主流模型。
- **established**：教科书级、多重独立验证。
- **contested**：曾经稳固，但出现可信反例——**降级而非删除**。

晋级规则：当一个页面被 N 篇独立、可信、开放来源支持，且无未解决的反例时，可上调一级。`maturity_index.json` 记录每页的当前等级和上次变动原因。

这套模型让知识库"诚实地生长"——它不假装确定性，并能区分"已知事实"和"今天的猜测"。

---

## 6. 矛盾处理协议（自进化的核心）

> 一个会"覆盖"的系统是健忘的；一个会"记录矛盾"的系统才是会学习的。

当今天的来源与某个既有 wiki 页冲突时，**严禁静默覆盖**。执行：

1. **不删旧主张**。把新证据并列写入"关键证据"表，标注冲突。
2. **降低该页 `confidence`**，必要时把 `status` 降为 `contested`。
3. **在 `state/contested_claims.json` 登记**一条：
   ```json
   {
     "id": "C-2026-05-24-01",
     "page": "wiki/neurons/xxx.md",
     "claim_A": "旧理解 + 来源",
     "claim_B": "新证据 + 来源",
     "nature": "方法差异 / 物种差异 / 样本量 / 真实分歧",
     "status": "open",
     "opened": "2026-05-24"
   }
   ```
4. **在页面"当前理解"里如实写出张力**："关于 X 存在两种证据……差异可能源于……"
5. 当后续证据能化解矛盾时，更新该登记条目为 `resolved` 并记录裁决依据。

这一步是整套设计中最重要的。它把"知识库会不会自我矛盾/腐烂"这个最大风险，转化成"知识库会显式追踪自己的不确定性"这个最大优点。

---

## 7. 知识图谱

`wiki/_graph.json` 是机读的概念网络，使知识库可被结构化问询、可暴露盲区。

```json
{
  "version": "1.0",
  "updated": "2026-05-24",
  "nodes": [
    {"id": "action-potential", "title": "动作电位", "domain": "neurons",
     "type": "mechanism", "status": "established", "confidence": "high",
     "page": "wiki/neurons/action-potential.md"}
  ],
  "edges": [
    {"from": "axon-initial-segment", "to": "action-potential", "type": "initiation-site-of"},
    {"from": "voltage-gated-sodium-channel", "to": "action-potential", "type": "mechanism-of"}
  ]
}
```

**边的类型**（领域无关的一套）：`is-a`、`part-of`、`mechanism-of`、`prerequisite-for`、`regulates`、`supports`、`contradicts`、`related`。

图谱的两大用途：
- **暴露缺口**：被 `related`/`prerequisites` 引用、但还没有对应节点的 slug = "悬空引用" = 该写的下一篇。
- **找前沿**：高连接度（很多边指向它）但低置信度的节点 = 值得深挖的重点。

---

## 8. 每日固结循环（算法）

这是把"每日文章生成器"升级为"自进化知识库"的核心改动。每天运行：

```
A. 读取状态
   - topic_ledger（防重复）、unresolved_questions（待办）、
     contested_claims（待裁决）、_graph.json（缺口与前沿）

B. 选题（见第 9 节：缺口驱动 + 课程脊柱 + 突破追踪）

C. 检索 → 阅读 → 写每日文章（情景层，append-only）
   —— 与旧流程相同，产出 articles/ notes/ sources/

D. ★ 固结步骤（新增，核心）★
   对今天文章触及的每一个概念：
   1. 该 slug 是否已有 wiki 页？
      - 有 → 修订：把新理解整合进"当前理解"，向"证据表"加行，
              更新 frontmatter（updated, revision_count, key_sources, related），
              在"修订历史"追加一行。
      - 无 → 用 _TEMPLATE 创建新页，填全 frontmatter 与正文。
   2. 运行矛盾检查（第 6 节）：新证据是否冲突既有主张？
      若冲突 → 走矛盾处理协议，登记 contested_claims。
   3. 重新评估成熟度（第 5 节），更新 maturity_index。

E. ★ 更新图谱与导航 ★
   - 在 _graph.json 增/改节点与边。
   - 在 index.md 反映新页/状态变化。
   - 在 wiki/CHANGELOG.md 写一行：今天创建了哪些页、修订了哪些页、
     登记了哪些矛盾。

F. 更新治理层
   - topic_ledger、unresolved_questions、source_registry、
     monthly_synthesis 照旧。

G. 提交 + 推送（文章 + wiki + 状态，一次 commit）。

H. 自检（第 11 节）后才算完成。
```

固结步骤 D 和图谱步骤 E 是与旧流程的全部区别，但它们正是"会生长"的来源。

---

## 9. 缺口驱动的主题选择

旧流程靠固定课程表选题。自进化库应让**知识库自己说出它缺什么**。优先级：

1. **突破追踪**：过去 7 天有重大新发现 → 优先写，并固结进相关 wiki 页。
2. **裁决矛盾**：`contested_claims` 里有 `open` 的重要矛盾 → 找新证据去裁决。
3. **填补悬空引用**：图谱里被引用但无节点的 slug → 补上。
4. **加深前沿节点**：高连接度、低置信度的节点 → 深挖。
5. **回收未解问题**：`unresolved_questions` 里的高优先级问题。
6. **课程脊柱**：以上都不紧迫时，按预设课程推进，保证系统性。

约束（防失衡）：避免连续三天同一"维度/层级"；每 7 篇做一次周综合；每 30 篇做一次月度大图景。

---

## 10. 如何移植到新领域

整套架构中，**只有四样东西是领域相关的**，其余（双层架构、固结循环、矛盾协议、成熟度模型、图谱）原样复用。移植时只需定义：

### (1) 领域分类法
- `type` 枚举：概念有哪些种类？
  - 神经科学：`concept|mechanism|structure|region|method|disease|theory`
  - 法律：`statute|case|doctrine|principle|institution|procedure`
  - 某代码库：`module|function|data-model|api|pattern|gotcha|decision`
- `dimensions` 枚举：知识沿哪些轴展开？
  - 神经科学：分子/细胞/回路/系统/行为/认知
  - 法律：宪法/部门法/程序/判例层级
  - 代码库：前端/后端/数据/基础设施/构建

### (2) 来源权威政策
定义"什么算可信一手来源"，以及禁用什么：
- 神经科学：PubMed/PMC/Europe PMC + 官方机构；禁 Sci-Hub/盗版。
- 法律：官方法规库、法院公开判决；禁二手博客作为唯一来源。
- 代码库：源码本身、官方文档、commit/PR 历史；禁过时的 Stack Overflow 作为定论。

### (3) 课程脊柱（可选）
该领域"从入门到精通"的系统化路线。没有也行（纯缺口驱动），但有它能保证覆盖完整。

### (4) 选题模式
是"追踪新进展"为主，还是"系统建图"为主，还是两者混合（推荐）。

> **移植清单**：复制 `KNOWLEDGE-BASE-DESIGN.md` + `ROUTINE.md` → 改上述四项 → 改实例目录名 → 跑第一天（会自动初始化所有状态文件）。其余照搬。

### 三个移植示例

- **本地代码库知识库**：`type=module/function/gotcha`，来源=源码与 PR，固结步骤把"今天读懂的某模块"写成会随重构更新的 wiki 页，矛盾协议处理"文档说 A、代码做 B"。
- **个人投资/行业追踪库**：`type=company/thesis/metric/event`，来源=财报与官方披露，矛盾协议处理"旧论点 vs 新数据"，成熟度模型区分"假设 vs 已验证"。
- **法律研究库**：`type=statute/case/doctrine`，`dimensions`=法律部门，矛盾协议天然处理判例冲突与法律修订。

---

## 11. 质量与防腐机制

每次运行结束前自检（任一不过则修正后再提交）：

**真实性**
- [ ] wiki 每条新主张都有来源（PMID/DOI/URL）？
- [ ] 区分了事实 / 主流模型 / 推测 / 争议？
- [ ] 没有把单篇/小样本/动物研究写成定论？

**一致性（防腐核心）**
- [ ] 新内容是否与既有 wiki 页冲突？冲突是否走了矛盾协议？
- [ ] 被修订页的 `updated`/`revision_count`/修订历史是否同步更新？
- [ ] `_graph.json` 有无悬空边（指向不存在节点）？记入待办。

**可导航**
- [ ] `index.md` 与 `CHANGELOG.md` 反映了今天的变化？
- [ ] 新页的 `related`/`prerequisites` 至少各填了一个？

**情景层完整**
- [ ] 文章/笔记/来源/日志齐全且 append-only（没改旧文件）？

---

## 附：与旧"每日文章"流程的差异一览

| 维度 | 旧流程 | 自进化库 |
|------|--------|----------|
| 产物 | 孤立文章流 | 文章流 + 活的 wiki + 图谱 |
| 旧知识 | 不再触碰 | 每天被修订加深 |
| 矛盾 | 无机制（易腐烂） | 显式登记与裁决 |
| 选题 | 固定课程表 | 缺口/矛盾/前沿驱动 |
| 可问询性 | 无 | frontmatter + 图谱 |
| 确定性表达 | 模糊 | 成熟度模型分级 |

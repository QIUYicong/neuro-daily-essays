---
title: PKMζ（蛋白激酶M-ζ）
slug: pkm-zeta
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-21
updated: 2026-09-21
revision_count: 1
dimensions: [molecular, synaptic, cellular, cognition]
related: [ltp, synaptic-tagging-capture, ampa-receptor, camkii, bdnf, arc-arg31, memory-consolidation, hebbian-learning]
prerequisites: [ltp, ampa-receptor, synaptic-tagging-capture]
opens_questions: [Q-pkm-zeta-in-vivo-oligomer, Q-pkm-zeta-region-specificity, Q-pkm-zeta-memory-modification]
source_articles: [2026-09-21-pkm-zeta-late-ltp-persistence]
key_sources: ["PMID:16463388", "PMID:15958741", "PMID:21119699", "PMID:20383136", "PMID:23283171", "PMID:23283174", "PMID:27187150", "PMID:33540466", "PMID:39814881", "PMID:41814337", "PMID:41889799"]
---

# PKMζ（蛋白激酶M-ζ，Protein Kinase M-zeta）

> **一句话定义**：非典型PKC（aPKC）的ζ亚型的无调节域剪接形式，天生持续激活，通过阻止含GluA2 AMPA受体内吞来维持突触强度；与PKCι/λ共同构成晚期LTP（L-LTP）必需的aPKC功能层；通过KIBRA寡聚体形成的"感染性磷酸化"传递机制，实现激活状态对蛋白周转的超越。

## 当前理解

我们现在认为，PKMζ是目前已知的**最直接回应"克里克问题"**（蛋白质寿命数周 vs. 记忆持续数十年）的分子机制，但这一答案经历了发现—颠覆—重建三个阶段：

| 阶段 | 时间 | 关键事件 | 认知状态 |
|------|------|---------|---------|
| 发现期 | 1993–2012 | 发现持续激活特性；ZIP抹去记忆；鉴定为第一个L-LTP特异性PRP | PKMζ = 记忆的单一分子维持者 |
| 危机期 | 2013 | 两篇Nature KO论文：Prkcz敲除小鼠记忆正常；ZIP在KO小鼠中仍有效 | 假说面临根本质疑 |
| 重建期 | 2016–2026 | PKCι/λ代偿上调（Tsokas 2016）；双KO消除L-LTP（Tsokas 2026）；ZIP阳离子机制（Stokes 2025）；KIBRA-PKMζ寡聚体（Hsieh 2026） | 功能层不可或缺；分子机制有了真正解答 |

**当前共识**：
1. 单独缺失PKMζ不足以损害记忆——PKCι/λ发育性代偿
2. 同时缺失PKMζ和PKCι/λ → L-LTP完全消失（双KO关键证据）
3. KIBRA-PKMζ寡聚体通过"感染性磷酸化"将激活状态代代传递，解答分子周转悖论
4. ZIP的记忆破坏作用非PKMζ特异性，而是阳离子电荷介导的巨胞饮效应

## 关键机制

### 一、PKMζ的分子结构：无调节域的持续激活激酶

```
PKCζ基因（完整）：
  ┌─调节结构域─┐ ┌──催化结构域──┐
  │PS-C1-PB1    │ │ kinase core   │
  └─────────────┘ └───────────────┘
         ↕（内部独立启动子转录）
PKMζ（特殊剪接产物）：
  ┌──────催化结构域──────┐
  │ kinase core (only)   │
  └──────────────────────┘
  → 无调节域 → 天生持续激活（不需要Ca²⁺、DAG等第二信使）
```

**关键特性**：
- **组成性激活**：合成即激活，不需要受体偶联或第二信使
- **树突mRNA定位**：PKMζ mRNA大量分布于树突，可在突触局部翻译
- **活动依赖性合成**：L-LTP诱导后30–60分钟，PKMζ蛋白水平在突触局部升高
- **脑特异性**：在脑外组织中极低表达

### 二、PKMζ维持LTP的机制：阻止GluA2-AMPAR内吞

```
PKMζ激活（持续）
  ↓
抑制 NSF-GluA2 通路（GluA2亚基参与的内吞机制）
  ↓
含GluA2亚基的AMPA受体（GluA1/A2异聚体）驻留在突触后膜
  ↓
突触传递效率维持在LTP水平
  ↓
记忆的突触基础持续存在
```

PKMζ单独过表达可将突触AMPA受体数量增加近2倍（Ling 2006, PMID:16463388），无需任何突触刺激。这是**主动维持**（持续阻止减弱），而非静态编码。

### 三、PKMζ在STC中的角色：第一个明确的L-LTP PRP

PKMζ是**突触标记与捕获（STC）**框架中第一个被明确鉴定的晚期LTP特异性可塑性相关蛋白（PRP）：

```
弱Hebbian刺激 → E-LTP + 突触标签（~1-2h有效）
                      ↓（在标签有效期内）
             强刺激/DA爆发 → PKMζ合成（~30-60 min延迟）
                      ↓
             新合成PKMζ被标签突触捕获
                      ↓
             E-LTP → L-LTP（蛋白质合成依赖）
```

（Sajikumar et al. 2005, PMID:15958741）

### 四、aPKC功能层：PKMζ + PKCι/λ的冗余设计

**为什么PKMζ单独KO不破坏记忆**（Tsokas 2016, PMID:27187150）：

- 从出生起PKMζ缺失 → PKCι/λ在发育中**代偿性上调**
- PKCι/λ与PKMζ共享相似的催化结构域
- PKCι/λ可执行类似的GluA2-AMPAR维持功能

**双KO的关键证据**（Tsokas 2026, PMID:41889799）：

| 基因型 | L-LTP | 空间记忆 |
|--------|-------|---------|
| 野生型 | 正常 | 正常 |
| PKMζ KO | 正常（PKCι/λ代偿） | 正常 |
| PKCι/λ KO | 正常（PKMζ维持） | 正常 |
| **双KO** | **完全消失** | **严重受损** |

E-LTP仍可诱导，但3小时后完全衰退至基线。

### 五、KIBRA-PKMζ寡聚体：分子周转悖论的解答

**2026年关键发现**（Hsieh et al. 2026, PMID:41814337）：

```
KIBRA（支架蛋白）+ 磷酸化PKMζ → 稳定寡聚体复合物（AlphaFold3验证）
                                            ↓
                                  新合成的未磷酸化PKMζ加入复合物
                                            ↓
                                  "感染性磷酸化"：新PKMζ被已磷酸化的PKMζ激活
                                            ↓
                                  老PKMζ降解，新PKMζ继承激活状态
                                            ↓
                              激活状态在蛋白更新中代代传递（克里克问题的答案）
```

**类比**：类似于朊病毒的构象传播机制，但不涉及病理性聚集——是生理性的功能状态传递。

**工具**：
- **K-ZAP**（KIBRA拮抗肽）：阻断KIBRA-PKMζ相互作用，测试寡聚体在记忆中的作用
- **ζ-stat**：新型PKMζ状态探针，区分"新加入"与"已激活"的PKMζ

### 六、ZIP机制重写：阳离子电荷非PKMζ特异性

**2025年重大重新解读**（Stokes et al. 2025, PMID:39814881）：

ZIP（zeta-inhibitory peptide）的记忆破坏作用**不是**通过抑制PKMζ实现的，而是：

```
ZIP（阳离子肽）
  ↓ 细胞内吞
  → 激活 endophilin-A2 依赖的巨胞饮（macropinocytosis）
  → AMPA受体大规模非特异性内吞
  → 突触传递效率下降
  → 记忆破坏
```

验证：移除ZIP的阳离子电荷（中性化）→ ZIP失去记忆破坏能力，即使保留PKMζ伪底物序列。

**含义**：2006–2024年的ZIP实验需要全面重新解读。ZIP是有效的记忆操控工具，但不是PKMζ特异性探针。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| PKMζ过表达→突触AMPA受体数量翻倍 | 海马CA1神经元过表达+电生理 | PMID:16463388 | 高 |
| PKMζ是第一个L-LTP特异性PRP（STC框架内） | STC双通路实验+PKMζ合成阻断 | PMID:15958741 (PMC6724879) | 高 |
| PKMζ通过阻止GluA2-AMPAR内吞维持LTP | NSF-GluA2通路+PKMζ抑制剂实验 | PMID:20383136 | 高 |
| PKMζ KO小鼠LTP和记忆正常 | 条件性Prkcz KO+电生理+行为 | PMID:23283171 (PMC3548047) | 高 |
| 独立重复：PKMζ KO不影响LTP | 独立实验室+独立KO策略 | PMID:23283174 (PMC3830948) | 高 |
| PKCι/λ在PKMζ KO中代偿上调 | Western blot + 功能实验 | PMID:27187150 (PMC4869915) | 高 |
| 双KO（PKMζ + PKCι/λ）→ L-LTP完全消失 | 双KO小鼠切片电生理 | PMID:41889799 (PMC13014159) | 高（预印本） |
| 记忆神经元中PKMζ在1个月后仍升高 | c-Fos-DREADD标记+免疫染色 | PMID:33540466 (PMC8333175) | 高 |
| ZIP通过阳离子电荷/巨胞饮破坏记忆，非PKMζ特异 | ZIP变体（中性化/序列改变）系统比较 | PMID:39814881 (PMC12413077) | 高 |
| KIBRA-PKMζ寡聚体：感染性磷酸化传递激活状态 | AlphaFold3+体外结合+功能实验 | PMID:41814337 (PMC12997682) | 中-高（部分体外） |

## 连接

- [[ltp]] — PKMζ（+PKCι/λ）是L-LTP必需的aPKC功能层；KIBRA-PKMζ机制解答Q-ltp-lifetime-mechanism
- [[synaptic-tagging-capture]] — PKMζ是STC框架中第一个明确的L-LTP特异性PRP；新合成PKMζ被突触标签捕获
- [[ampa-receptor]] — PKMζ通过阻止含GluA2 AMPAR内吞来维持突触AMPA受体密度
- [[camkii]] — CaMKII是LTP诱导的快速信号（秒内），PKMζ是L-LTP的慢速持久信号（小时-天）；二者在时间尺度上互补
- [[bdnf]] — BDNF是L-LTP的催化分子，驱动PRPs合成（包括PKMζ的合成信号通路）
- [[arc-arg31]] — Arc和PKMζ是STC框架中两个最重要的L-LTP PRPs；Arc负责结构稳定，PKMζ负责功能维持
- [[memory-consolidation]] — PKMζ持久性和KIBRA寡聚体机制是突触层面记忆巩固的分子基础
- [[hebbian-learning]] — PKMζ是Hebbian学习的晚期分子执行者（E-LTP→L-LTP转化的关键）

## 未解问题

- Q-pkm-zeta-in-vivo-oligomer：KIBRA-PKMζ寡聚体的结构稳定性在体内神经元中如何维持？AlphaFold3预测的相互作用是否在整体动物行为实验中得到验证（K-ZAP体内应用）？
- Q-pkm-zeta-region-specificity：PKMζ在海马CA1的功能是否适用于其他脑区（皮层、杏仁核、纹状体）？各脑区的PKCι/λ代偿比例是否不同，是否存在真正的PKMζ专属需求脑区？
- Q-pkm-zeta-memory-modification：K-ZAP/ζ-stat工具是否可以实现"选择性单条记忆修改"（而非全脑AMPAR破坏）？这对创伤后应激障碍（PTSD）的干预有何潜力？

## 修订历史

- 2026-09-21 · 创建（rev1）· 基于《记忆的分子守夜人》一文（#151）· 覆盖PKMζ发现→2013危机→重建全貌；关键证据：双KO（Tsokas 2026）、ZIP机制（Stokes 2025）、KIBRA寡聚体（Hsieh 2026）；初始置信度：高（核心机制）/中-高（KIBRA寡聚体，部分体外证据）

## 来源文章

- [[2026-09-21-pkm-zeta-late-ltp-persistence]]

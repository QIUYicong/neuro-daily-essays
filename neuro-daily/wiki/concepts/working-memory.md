---
title: 工作记忆
slug: working-memory
domain: concepts
type: concept
status: established
confidence: high
created: 2026-06-05
updated: 2026-06-10
revision_count: 3
dimensions: [cognition, brain-region, microcircuit, behavior]
related: [persistent-activity, gamma-oscillations, prefrontal-cortex, pv-interneurons, nmda-receptor, theta-oscillations, sharp-wave-ripples, memory-consolidation, competition-selection-principle, short-term-synaptic-plasticity, norepinephrine-locus-coeruleus, acetylcholine-cortex, dorsal-language-stream, language-network]
prerequisites: [nmda-receptor, pv-interneurons, synaptic-transmission]
opens_questions: [Q-wm-active-vs-silent, Q-wm-capacity-mechanism, Q-wm-pfc-content-vs-control, Q-wm-human-specificity]
source_articles: [2026-06-05-prefrontal-working-memory, 2026-06-10-stp-short-term-plasticity, 2026-06-12-neuromodulators-ach-ne]
key_sources: ["PMID:4998337", "PMID:7695894", "PMID:26996084", "PMID:18339943", "PMID:21345366", "PMID:16254995", "PMID:23818597"]
updated: 2026-06-20
revision_count: 5
---

# 工作记忆 (Working Memory)

> **一句话定义**：在数秒内主动维持少量信息（容量约 4 项）并对其进行操作的认知能力，神经基础为 dlPFC 循环回路的 γ 爆发（间歇性主动编码）与突触 STP 易化（活动无声储存）的协同机制。

## 当前理解

工作记忆是认知控制的核心基础设施。心理学实验（Baddeley & Hitch 1974）将其定义为容量有限（~4 项）、时间有限（约 15–30 秒）、需主动维持的信息暂存-操作系统。

其神经基础集中在背外侧前额叶皮层（dlPFC），尤其是第 2/3/5 层锥体细胞的循环连接网络。当前最佳理解（2020 年代）认为工作记忆由多层机制共同实现：

1. **活动性编码**（active coding）：γ 爆发（45–100 Hz，~67 ms/次）期间，神经元高精度编码记忆内容（Lundqvist et al. 2016）
2. **突触静默储存**（activity-silent storage）：突触 STP 易化（Ca²⁺ 残留 + 囊泡就绪）在爆发间隔期无声保持信息（Mongillo et al. 2008）
3. **主动抑制**（active suppression）：β 振荡（20–35 Hz）压制竞争信息
4. **层级特化**：浅层（L2/3）负责内容编码，深层（L5/6）负责时序控制

经典持续放电模型（Goldman-Rakic 1995）仍然有效，但需修订：延迟期放电是**间歇性 γ 爆发**而非连续高频，且并非所有信息都需要主动放电维持。

## 关键机制

### 回路机制：吸引子网络
dlPFC 第 2/3 层锥体细胞通过水平侧支形成循环兴奋回路。一个刺激激活的神经集群通过循环连接形成**吸引子状态（attractor state）**，在外部输入消失后自持活动（Wang 2001）。NMDA 受体的慢衰减（τ ~100–300 ms）赋予回路所需的时间积分能力。

### γ 爆发机制
PV+ 篮状细胞的兴奋-抑制循环（锥体细胞兴奋 → PV 反馈抑制 → 10-15 ms 后再激活）产生 30–80 Hz γ 振荡。工作记忆维持期间，γ 以短暂爆发形式出现（非持续），间歇性"刷新"信息表征。

### 多巴胺调节
多巴胺 D1 受体对 dlPFC 工作记忆呈倒 U 型调节（Arnsten 2011）：适中水平通过 α-2A 受体抑制 cAMP，强化循环回路；过高（急性压力）或过低（衰老）均损害工作记忆。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| PFC 神经元在延迟期持续放电 | 猕猴单单元记录 + 延迟任务 | Fuster & Alexander 1971 (PMID:4998337) | 高 |
| 持续活动呈内容选择性 | 猕猴 PFC 空间延迟任务 | Goldman-Rakic 1995 (PMID:7695894) | 高 |
| 延迟期为 γ 爆发非持续放电 | 猕猴 PFC 时频分析 | Lundqvist et al. 2016 (PMID:26996084, PMC:PMC5220584) | 中-高 |
| STP 可实现活动无声 WM | 计算模型 | Mongillo et al. 2008 (PMID:18339943) | 中 |
| D1 受体倒 U 型调节 | 猕猴 PFC 微量注射 | Arnsten 2011 (PMID:21345366, PMC:PMC3115784) | 高 |
| PV 损伤导致 γ 下降和 WM 缺陷 | 人类 dlPFC 尸检 | Hughes et al. 2024 (PMID:39381500, PMC:PMC11458443) | 高 |

## 连接

- [[persistent-activity]] — 工作记忆维持的活动性机制（γ 爆发的神经相关物）
- [[gamma-oscillations]] — PV+中间神经元生成的 30–80 Hz 节律，工作记忆的时序框架
- [[prefrontal-cortex]] — 工作记忆的关键脑区，dlPFC 第 2/3/5 层
- [[pv-interneurons]] — γ 生成者，控制工作记忆的时序精度
- [[nmda-receptor]] — PFC 循环回路的时间积分器
- [[theta-oscillations]] — θ 周期内可嵌套 5–7 个 γ 爆发，可能与工作记忆容量相关
- [[memory-consolidation]] — 工作记忆的长期化需要海马参与
- [[short-term-synaptic-plasticity]] — STP易化机制是"活动无声"工作记忆的物理基础（Mongillo 2008）；Syt7驱动的易化状态储存记忆，无需持续高频放电
- [[dorsal-language-stream]] — Baddeley语音回路（phonological loop）对应背侧流Spt↔BA44环路：颞顶界面区（Spt）是音韵短期缓冲，弓状束传递信息到BA44进行内部"默读"，是语言工作记忆的神经底层
- [[language-network]] — 双流语言网络中的背侧流Spt↔BA44子回路 = 语音工作记忆的解剖基础

## 未解问题

- Q-wm-active-vs-silent：在真实任务中，活动性编码与突触静默储存各贡献多少？
- Q-wm-capacity-mechanism：约 4 项的容量限制是来自吸引子间的相互干扰还是 θ/γ 嵌套约束？
- Q-wm-pfc-content-vs-control：PFC 究竟是"内容存储器"还是"调度控制中心"？
- Q-wm-human-specificity：人类 dlPFC 是否有特有的工作记忆机制？

## 工作记忆容量的吸引子竞争机制

（2026-06-06 新增：竞争-遴选框架整合）

约 4 项的工作记忆容量限制不是偶然数字，而是 dlPFC 吸引子网络竞争动态的物理结果：

- **竞争者**：同时进入 dlPFC 的多个信息项目（每个对应一个潜在吸引子状态）
- **竞争机制**：PV+ 中间神经元介导的相互抑制——激活吸引子 A 的神经元集群通过 PV+ 细胞抑制吸引子 B 的集群
- **容量限制来源**（两种假说，尚争议）：
  - 假说1：θ/γ 嵌套约束——每个 θ 周期（~125 ms）可承载 4–7 个 γ 爆发（~25 ms/个），每个 γ 表征一个项目
  - 假说2：吸引子间竞争干扰——超过约 4 个活跃吸引子时，相互抑制压力使所有吸引子不稳定
- **"软竞争"特性**：被淘汰的吸引子并非消失，而是以突触 STP 易化的活动无声形式静默保存（Mongillo et al. 2008）；当主动吸引子被清空时，静默项目可重新激活——这是 WM 更新（swap）的机制

**与竞争-遴选架构的关系**：工作记忆是"嵌套竞争-遴选架构"（[[competition-selection-principle]]）在认知层次上的典型实例，容量限制即竞争机制的物理上限。

## 修订历史

- 2026-06-05 · 创建 · 基于《γ爆发、静默突触与持续放电》一文 · 初始置信度：高
- 2026-06-06 · 修订 · 基于《第二周综合：竞争法则》一文 · 新增"工作记忆容量的吸引子竞争机制"小节；明确 θ/γ 嵌套约束与吸引子竞争两种容量限制假说；added [[competition-selection-principle]] to related
- 2026-06-10 · 修订 · 基于《瞬息之变：短时程突触可塑性》一文 · 将 [[short-term-synaptic-plasticity]] 加入 related；明确Mongillo（2008）的STP机制作为"活动无声"储存的分子基础；为Q-wm-active-vs-silent提供新的STP侧证据（Syt7慢解离动力学与储存时间窗的对应）
- 2026-06-12 · 修订 · 基于《注意的化学语言》一文 · 新增 NE/ACh 对工作记忆的调制条目：α2A 受体（高亲和力 NE 受体）抑制 HCN 通道、稳定 PFC 工作记忆表征（Arnsten）；M1 ACh 受体促进持续放电（Hasselmo & Sarter 2011）；α7-nAChR 增强 dlPFC NMDA 信号稳定性（Yang 2013）；related 新增 norepinephrine-locus-coeruleus, acetylcholine-cortex
- 2026-06-20 · 修订 · 基于《语言的解剖》一文 · 新增语音工作记忆（phonological loop）与背侧语言流的解剖对应：Spt（音韵短期缓冲）↔BA44（内部发声）即Baddeley语音回路的神经底层；related 新增 dorsal-language-stream, language-network

## NE 和 ACh 对工作记忆的调制

（2026-06-12 新增）

工作记忆不仅依赖局部 PFC 回路，还受两套调质系统的增益调控：

**去甲肾上腺素（NE，α2A 受体）**：
- 低-中等 NE 水平时，α2A 受体（高亲和力，Gi 偶联）在 PFC 锥体细胞树突上激活
- 抑制 HCN（Ih）通道 → 减少树突泄漏 → 工作记忆表征更稳定、更不易被噪声打断
- α2A 激动剂（胍法辛）在灵长类中显著改善工作记忆任务表现
- **高 NE（极度压力）时**：α1 受体主导 → 增加背景噪声 → WM 受损（应激性认知崩溃）
- 临床相关：胍法辛是 ADHD 治疗药物之一（正是通过 α2A 稳定 PFC 信号）

**乙酰胆碱（ACh，M1 和 α7 受体）**：
- M1 受体激活（Hasselmo & Sarter 2011, PMID:20668433）→ 减少 K⁺ 漏电流 → 促进持续放电 → 支持工作记忆主动维持
- α7-nAChR 在 dlPFC 谷氨酸突触（Yang et al. 2013, PMID:23818597）→ 促进 NMDA 受体参与 → 增强 PFC 信号稳定性
- 皮层 ACh 去同步化 → 支持 WM 任务所需的高频编码状态

## 来源文章

- [[2026-06-05-prefrontal-working-memory]]
- [[2026-06-10-stp-short-term-plasticity]]
- [[2026-06-12-neuromodulators-ach-ne]]
- [[2026-06-20-language-dual-stream]]

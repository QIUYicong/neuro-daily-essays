---
title: 持续活动（延迟期放电）
slug: persistent-activity
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-05
updated: 2026-08-03
revision_count: 2
dimensions: [cellular, microcircuit, cognition]
related: [working-memory, nmda-receptor, prefrontal-cortex, gamma-oscillations, pv-interneurons, short-term-synaptic-plasticity]
prerequisites: [nmda-receptor, synaptic-transmission, action-potential]
opens_questions: [Q-wm-active-vs-silent, Q-pa-gamma-burst-causality]
source_articles: [2026-06-05-prefrontal-working-memory, 2026-08-03-working-memory-neural-code-debate]
key_sources: ["PMID:4998337", "PMID:7695894", "PMID:11476885", "PMID:26996084", "PMID:34654556"]
---

# 持续活动（延迟期放电）(Persistent Activity / Delay-Period Activity)

> **一句话定义**：神经元在外部刺激消失后继续维持高于基线的放电频率的现象；在 PFC 工作记忆回路中，现已证明主要以间歇性 γ 爆发的形式出现，而非经典模型中的连续高频放电。

## 当前理解

持续活动最初由 Fuster & Alexander（1971, PMID:4998337）在猕猴 PFC 中发现：延迟期（无外部输入的等待期）神经元持续放电，被认为是工作记忆的神经相关物。Goldman-Rakic（1995, PMID:7695894）系统建立了"持续放电 = 工作记忆维持"的框架。

**当前修订**（Lundqvist et al. 2016, PMID:26996084）：延迟期放电**不是持续连续的**，而是以短暂 γ 爆发（~67 ms/次，45–100 Hz）的间歇形式出现。信息编码在爆发期清晰；爆发间隔期神经元接近静默，信息由突触 STP 状态（活动无声机制）隐性保持。

## 关键机制

### 循环兴奋 + NMDA 吸引子（Wang 2001, PMID:11476885）
PFC 第 2/3 层锥体细胞的水平侧支循环连接形成局部吸引子网络。NMDA 受体的慢衰减（τ ~100–300 ms）使循环信号不会在快速衰减后消失，而是持续自激振荡，形成稳定的活动态（吸引子状态）。

### γ 爆发形式（Lundqvist 2016）
PV+ 篮状细胞参与的快速兴奋-抑制回路将持续活动"打碎"为 γ 爆发：锥体细胞放电 → PV 激活 → 强力抑制 → 抑制解除后再激活。每次爆发约 67 ms，携带信息内容；β 振荡（20–35 Hz）在爆发间出现，代表"等待态"。

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| PFC 延迟期出现高于基线放电 | 猕猴单单元记录 | Fuster & Alexander 1971 (PMID:4998337) | 高 |
| 持续活动依赖 NMDA 受体慢动力学 | 计算模型 + 药理学 | Wang 2001 (PMID:11476885) | 高 |
| 延迟期为 γ 爆发而非连续放电 | 猕猴 PFC 时频分析 | Lundqvist et al. 2016 (PMID:26996084) | 中-高 |
| 吸引子框架与 γ 爆发兼容；活动沉默在主动 WM 操纵中有局限；多吸引子网络提供容量约束 | 50年文献综合 + 计算模型 | Wang XJ 2021 (PMID:34654556, PMC:PMC9087306) | 高 |
| 延迟期 On 态（~192ms γ 爆发）与 Off 态（~146ms 静默）交替；On 态对应持续活动机制 | Neuropixels 8225 神经元同步记录，猕猴空间 WM | Panichello et al. 2024 (PMID:39506106, PMC:PMC11634780) | 高 |

## Wang 2021 修订版吸引子框架

（2026-08-03 新增）

Wang XJ 在 2021 年的 50 年回顾（PMID:34654556，PMC:PMC9087306）中提出了吸引子网络的修订版本，回应活动沉默和 γ 爆发模型的挑战：

1. **吸引子网络自然产生 γ 爆发**：含 PV+ 中间神经元的吸引子网络在合理参数下，稳定态表现为稀疏同步振荡（sparse synchronous oscillation），即间歇性 γ 爆发。持续活动不要求每个神经元连续高频放电，而是集群层面的间歇性集体动态。

2. **活动沉默的功能局限**：STP 储存状态在**过滤干扰项**（distractor filtering）和**主动更新**（active updating）等需要认知控制的场景中缺乏足够的鲁棒性——只有吸引子维持的持续活动（通过 β 振荡提供主动抑制）才能可靠地执行这类操作。

3. **On/Off 态框架的整合**：Panichello 2024 的 On 态（~192ms 群体爆发）对应吸引子的"激活态"，Off 态（~146ms）对应低活动中间态——两态交替本身是含抑制性中间神经元的吸引子网络的自然涌现行为。

## 连接

- [[working-memory]] — 持续活动是工作记忆维持的活动性机制
- [[nmda-receptor]] — 时间积分器，使吸引子网络的持续活动成为可能
- [[gamma-oscillations]] — 持续活动的实际形式（间歇 γ 爆发）
- [[prefrontal-cortex]] — 持续活动的主要发生部位（dlPFC L2/3）
- [[short-term-synaptic-plasticity]] — 活动沉默机制（STP）是持续活动的互补模型；两者在 On/Off 态中协作

## 修订历史

- 2026-06-05 · 创建 · 基于《γ爆发、静默突触与持续放电》一文
- 2026-08-03 · 修订 · 基于《工作记忆神经代码之争》一文（#102）· 新增 Wang XJ (2021) 50年综述（γ爆发与吸引子框架兼容；活动沉默局限于被动WM）和 Panichello (2024) On/Off态证据（On态=持续活动的实验验证形式）；key_sources 新增 PMID:34654556, PMID:39506106

## 来源文章

- [[2026-06-05-prefrontal-working-memory]]
- [[2026-08-03-working-memory-neural-code-debate]]

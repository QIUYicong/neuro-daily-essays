---
title: 持续活动（延迟期放电）
slug: persistent-activity
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-05
updated: 2026-08-18
revision_count: 2
dimensions: [cellular, microcircuit, cognition]
related: [working-memory, nmda-receptor, prefrontal-cortex, gamma-oscillations, pv-interneurons, activity-silent-wm, attractor-network]
prerequisites: [nmda-receptor, synaptic-transmission, action-potential]
opens_questions: [Q-wm-active-vs-silent, Q-pa-gamma-burst-causality]
source_articles: [2026-06-05-prefrontal-working-memory, 2026-08-18-working-memory-persistent-activity-silent]
key_sources: ["PMID:4998337", "PMID:7695894", "PMID:11476885", "PMID:26996084", "PMID:34654556", "PMID:39506106", "PMID:37910532", "PMID:40634665"]
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
| NR2B-NMDA受体拮抗剂几乎完全消除选择性延迟放电 | 猕猴PFC局部iontophoresis | Wang XJ 2021 综述引用 (PMID:34654556, PMC:PMC9087306) | 高 |
| 持续放电神经元携带更多WM解码信息（vs非持续神经元） | SVM解码，猕猴，多任务 | Thrower et al. 2023 (PMID:37910532, PMC:PMC11068397) | 高 |
| 延迟期群体状态在"开"（可解码）和"关"（基线）间切换 | Neuropixels，猕猴，480神经元/节次 | Panichello et al. 2024 (PMID:39506106) | 极高 |
| 人类MTL神经元以持续放电维持未关注记忆项目 | 人类颅内记录 | Paluch et al. 2025 (PMID:40634665) | 高 |

## 连接

- [[working-memory]] — 持续活动是工作记忆维持的活动性机制
- [[nmda-receptor]] — 时间积分器，使吸引子网络的持续活动成为可能
- [[gamma-oscillations]] — 持续活动的实际形式（间歇 γ 爆发）
- [[prefrontal-cortex]] — 持续活动的主要发生部位（dlPFC L2/3）

## 修订历史

- 2026-06-05 · 创建 · 基于《γ爆发、静默突触与持续放电》一文
- 2026-08-18 · 修订 · 基于《工作记忆的两种面孔》（#104）· 新增NMDA受体药理证据（Wang 2021）、Panichello 2024开-关切换证据、Thrower 2023信息优势证据、Paluch 2025人类MTL证据；关键证据表新增4行；related新增activity-silent-wm、attractor-network；key_sources新增4条

## 来源文章

- [[2026-06-05-prefrontal-working-memory]]
- [[2026-08-18-working-memory-persistent-activity-silent]]

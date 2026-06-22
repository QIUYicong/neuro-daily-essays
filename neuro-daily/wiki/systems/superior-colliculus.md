---
title: 上丘
slug: superior-colliculus
domain: systems
type: structure
status: established
confidence: high
created: 2026-07-30
updated: 2026-09-01
revision_count: 2
dimensions: [cellular, microcircuit, brain-region, cognition]
related: [multisensory-integration, inverse-effectiveness, thalamus, somatosensory-cortex, auditory-cortex, lip-area, perceptual-decision-making]
prerequisites: [multisensory-integration]
opens_questions: [Q-msi-02, Q-pdm-02]
source_articles: [2026-07-30-multisensory-integration-bayesian-brain, 2026-09-01-perceptual-decision-making-lip-drift-diffusion]
key_sources: ["PMID:32113921", "PMCID:PMC9680976", "PMID:19616425", "PMID:37352857"]
---

# 上丘 (Superior Colliculus, SC)

> **一句话定义**：脊椎动物中脑的层状结构，是多感觉整合的主要皮层下节点，通过三条经典规则（空间、时间、逆效应性）实现视听触觉的跨模态增强，并向丘脑和运动回路输出整合后的信号。

## 当前理解

上丘（SC）在鱼类、两栖类和鸟类中（称为视觉顶盖 optic tectum）是视觉处理的主要中枢；在哺乳类中，随着新皮层的扩张，SC 保留了视觉/多感觉的中脑处理功能，但皮层成为主要的感知中心。

SC 的层状结构：
- **浅层（Superficial layers, sSC）**：主要接收视网膜输入，处理初级视觉（运动、方向）
- **中/深层（Intermediate/Deep layers, iSC/dSC）**：多感觉神经元所在，接收视觉、听觉、触觉和前庭信号

SC 深层含有**多感觉神经元**，它们：
1. 对视觉刺激有感受野（Receptive Field, RF-V）
2. 对听觉刺激有感受野（RF-A）
3. 对触觉刺激有感受野（RF-T）
4. 当多种感觉刺激同时落在各自感受野内时，放电超过任何单一刺激的响应（超加性）

### Stein-Meredith 三条规则（1983-1993）

**1. 空间规则**：超加性响应仅在两刺激落在重叠感受野时发生。空间不匹配 → 多感觉抑制（低于单感觉响应）。

**2. 时间规则**：跨模态刺激必须在特定时间窗内近似同步，才产生整合增强。时间差超出窗口 → 无增强或抑制。

**3. 逆效应性**：单感觉刺激越弱，整合后的相对增益越大（详见 [[inverse-effectiveness]]）。细胞机制：NMDA 受体在膜电位接近阈值时的非线性激活（PMCID: PMC5375642）。

### 皮层依赖性

SC 的多感觉整合能力不是自主生成的，而是依赖来自联合皮层的下行投射：
- 猫的前外侧沟皮层（AES）和后外侧沟皮层（PLLS）在发育期提供关键输入
- 新生猫期阻断 AES 输入 → 成年后 SC 多感觉整合能力缺失
- 成年猫临时失活 AES → SC 整合能力可逆消失

这提示 SC 整合是皮层"使能"的皮层下计算，而非自主的皮层下独立处理。

### 临床转化：半盲恢复（Hemianopia Reversal）

基于 SC 三条规则的实验性治疗：对视野盲区（初级视觉皮层损伤区域）系统呈现时间同步、空间一致的视听刺激对，可逐步在动物模型中恢复盲区的多感觉检测能力（Stein & Rowland 2020）。这依赖：
- SC 的视觉处理通路（SC → 丘脑枕核 Pulvinar → 皮层联合区）绕过受损的 V1 通路
- 多感觉训练驱动 SC 多感觉神经元的突触可塑性

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| SC 深层含多感觉神经元（视听触） | 猫 SC 单细胞记录；系统感受野测绘 | Meredith & Stein 1983 (Science) | 高 |
| 三条规则（空间/时间/逆效应性）在猫/猫鼬中保守 | 多电极记录 + 行为测量 | Stein-Meredith 系列（1983-1993） | 高 |
| AES 皮层失活消除 SC 整合能力 | 药理失活（GABA 注射）+ 细胞外记录 | PMID:32113921 | 高 |
| 视听训练恢复半盲区多感觉检测 | 猫半盲模型 + 多感觉训练方案 | PMID:32113921 | 高（动物模型）|

## SC 作为决策终止器（Stine et al. 2023）

除多感觉整合外，SC 在**感知决策**中还承担决策终止的角色（Stine et al. 2023，Neuron，PMID:37352857）：

- **机制**：猴子在随机点运动任务中，LIP（外侧顶内区）神经元以漂移扩散动力学积累感觉证据；当 LIP 放电率越过决策边界时，SC 检测到该信号并爆发放电，触发眼跳
- **因果证据**：药理失活 SC（muscimol 注射）→ LIP 积累延长（无法终止）→ 反应时显著增加，且积累轨迹越过通常的 SC 爆发点仍继续上升
- **分工概念**：LIP 是**积累器**，SC 是**阈值传感器**；这是与 SC 多感觉功能完全不同的感知-运动接口功能

SC 的这一"决策终止"功能揭示了皮层-皮层下的计算分工：皮层（LIP）负责慢速随机证据整合，皮层下（SC）负责快速阈值检测和运动触发。

## 连接

- [[multisensory-integration]] — SC 是多感觉整合的皮层下节点
- [[inverse-effectiveness]] — SC 的第三条规则
- [[thalamus]] — SC → 丘脑枕核（Pulvinar）→ 皮层联合区 快速通路
- [[auditory-cortex]] — AES 皮层投射到 SC（使能整合）
- [[lip-area]] — LIP → SC 决策终止回路（Stine 2023）
- [[perceptual-decision-making]] — SC 是感知决策运动输出的触发节点

## 未解问题

- Q-msi-02：SC 整合和 STS 整合是串联（SC→Pulvinar→STS）还是并联（两条独立通路）？
- Q-pdm-02：决策边界（LIP 阈值放电率）在速度-精度权衡时如何变化？SC 的阈值检测机制与边界高度如何协调？

## 修订历史

- 2026-07-30 · 创建 · 基于《感官的裁判》文章 #98 · 初始置信度：高（Stein & Rowland 2020 开放全文）
- 2026-09-01 · 修订（rev2）· 新增 SC 决策终止功能（Stine et al. 2023，PMID:37352857）基于文章 #131

## 来源文章

- [[2026-07-30-multisensory-integration-bayesian-brain]]
- [[2026-09-01-perceptual-decision-making-lip-drift-diffusion]]

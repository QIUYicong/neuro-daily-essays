---
title: 纹状体拍频模型
slug: striatal-beat-frequency
domain: concepts
type: theory
status: mainstream
confidence: medium
created: 2026-07-31
updated: 2026-07-31
revision_count: 1
dimensions: [cellular, microcircuit, brain-region]
related: [interval-timing, medium-spiny-neuron, dopamine-reward-prediction-error, population-clock]
prerequisites: [medium-spiny-neuron, cortical-oscillations]
opens_questions: [Q-it-01]
source_articles: [2026-07-31-interval-timing-basal-ganglia-striatum]
key_sources: ["PMCID:PMC3178804"]
---

# 纹状体拍频模型 (Striatal Beat-Frequency Model, SBF)

> **一句话定义**：一种区间计时的机制模型——大量频率各异的皮层振荡子在区间开始时同步对齐，随时间相位逐渐拉开形成对每个时刻独一无二的"拍频图案"，纹状体中型多棘神经元（MSN）作为符合检测器读出该图案，从而测量已流逝的时间。

## 当前理解

我们现在认为，SBF 是解释**秒级区间计时**最有影响力的机制模型之一（Oprisan & Buhusi, 2011, PMC:PMC3178804）。它把"读时间"优雅地转化为"识别皮层振荡的拍频图案"，并能定量复现药物对时间知觉的标量改变。它属于专用计时框架的具体实现，可与 [[population-clock]]（内在计时）形成互补或竞争的描述层次。

## 关键机制

1. **皮层振荡子作为时基**：大量皮层神经元以略微不同的频率振荡（模型取 α 频段，约 8–13Hz）。区间开始时（由多巴胺脉冲触发重置/对齐）所有振荡子被同步到同一相位。
2. **相位漂移产生"拍"**：频率各异 → 相位随时间逐渐拉开 → 对每个时刻形成独一无二的相位组合模式。
3. **MSN 作为符合检测器（coincidence detector）**：纹状体 MSN 接收成千上万皮层输入；某个特定相位组合（对应某时刻）让众多输入恰好同时到达，激活该 MSN。经学习，MSN 被调谐到"目标时长对应那一刻的相位图案"。

**多巴胺的角色**：多巴胺激动剂产生"**即时、标量**的时间知觉改变"——在模型中，多巴胺调节**振荡子频率**（而非记忆存储），频率改变使"拍"的演化速度改变，导致系统性高估/低估时长。这是"多巴胺=时钟速度旋钮"假说的机制实现。

**噪声的必要性**：模型**需要生物学噪声**（真实神经的不精确性）才能维持**标量特性**（误差随时长成比例增长，即时间的韦伯定律）。神经系统的不完美在此是特性而非缺陷。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 皮层振荡子 × MSN 符合检测可计时 | SBF 模型仿真 | PMC:PMC3178804 | 中 |
| DA 调振荡频率→即时标量时间改变 | 模型对照药理时间知觉数据 | PMC:PMC3178804 | 中 |
| 标量特性需生物学噪声维持 | 模型仿真 | PMC:PMC3178804 | 中 |

## 连接

- [[interval-timing]] — SBF 是区间计时的核心机制模型之一
- [[medium-spiny-neuron]] — MSN 作为符合检测器
- [[dopamine-reward-prediction-error]] — 多巴胺通过调频率改变时钟速度
- [[population-clock]] — 另一类计时模型（轨迹/内在计时），与 SBF 互补或竞争

## 未解问题

- **Q-it-01**：SBF 假设的"许多频率各异的皮层振荡子 + MSN 相位符合检测"这一具体生理回路尚未被直接、完整地在体证实。皮层振荡的真实频率分布、相位重置的生理触发、MSN 是否真以此方式被调谐，均缺乏决定性因果实验。

## 修订历史

- 2026-07-31 · 创建 · 基于《大脑的秒表》文章 #99 · 初始置信度：中

## 来源文章

- [[2026-07-31-interval-timing-basal-ganglia-striatum]]

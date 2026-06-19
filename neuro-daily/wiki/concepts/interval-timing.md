---
title: 区间计时
slug: interval-timing
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-07-26
updated: 2026-07-26
revision_count: 1
dimensions: [molecular, cellular, microcircuit, brain-region, cognition, behavior]
related: [basal-ganglia, dopamine-reward-prediction-error, time-cells, hippocampal-circuit, circadian-clock]
prerequisites: [basal-ganglia, dopamine-reward-prediction-error]
opens_questions: [Q-timecell-longscale]
source_articles: [2026-07-26-hippocampal-time-cells-temporal-coding]
key_sources: ["PMID:16163383", "PMID:26455307", "PMID:29963985"]
---

# 区间计时 (Interval Timing)

> **一句话定义**：大脑对几百毫秒到几分钟时间间隔的精确测量与再现能力，依赖纹状体-皮层振荡巧合检测网络（SBF 模型）和多巴胺调制，与海马情节时间细胞互补，共同构成大脑的双时间系统。

## 当前理解

我们现在认为，大脑有两套互补的时间系统：
1. **海马情节时间**：时间细胞在延迟间隔中按序激活，编码"事件发生在什么时候"——事件定位功能
2. **纹状体区间计时**：精确测量和再现特定时间区间（秒到分钟）——时间计量功能

区间计时的核心机制是 Buhusi & Meck 2005 提出的**纹状体节拍频率（Striatal Beat Frequency, SBF）模型**：皮层多个神经元以不同频率振荡，纹状体中的棘状神经元（Medium Spiny Neurons, MSN）通过检测特定振荡频率组合同时激活的"巧合"来标记特定时间点。不同的时间点对应不同的频率组合，学习时通过多巴胺奖励信号强化"正确时刻"对应的突触连接。

多巴胺（DA）是区间计时的关键调制器：DA 信号在奖励发生时（Temporal Difference error）加强纹状体 MSN 的突触，从而"记住"特定时间区间。帕金森病（DA 耗竭）和 D2 受体拮抗剂（抗精神病药）都会显著损害区间计时精度——这是临床观察到的最直接证据。

大脑的区间计时还涉及小脑：Kunimatsu et al. 2018（猴子实验）区分了纹状体（尾状核）和小脑（齿状核）的不同角色：
- **纹状体**：在整个延迟期间跟踪时间流逝（"计时器"）
- **小脑**：仅在延迟末端激活，负责精细时间调整（"精调器"）

## 关键机制

### SBF 模型

```
皮层振荡子 (多种频率) → 纹状体 MSN (巧合检测) → 特定时刻信号
               ↑                        ↑
        DA 奖励调制             D1/D2 受体差异化突触强化
```

皮层振荡子以 f₁, f₂, ..., fₙ 多种频率振荡，每个特定时刻 T 对应一个特定的频率相位组合 (φ₁(T), φ₂(T), ..., φₙ(T))。纹状体 MSN 学会识别这个特定组合，即"报时"该时刻。

### 顶叶皮层斜坡信号

Jazayeri & Shadlen 2015（猴子）发现，顶叶皮层（DMFC）的神经活动在时间测量阶段产生一个**斜坡信号**，其斜率编码了被测量的时间区间长度；随后在时间再现阶段，斜坡信号斜率与样本时间区间成正比，实现时间的"测量-再现"耦合。这是顶叶皮层参与时间感知的直接神经元证据。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 纹状体是区间计时核心结构，DA 调制关键 | 综述：病变+影像+药理 | Buhusi & Meck 2005 (PMID:16163383) | 高（教科书级） |
| 帕金森病（DA 耗竭）区间计时受损 | 临床+神经影像 |综述数据 | 高 |
| 顶叶皮层斜坡信号斜率编码时间区间 | 猴子 DMFC 单元记录 | Jazayeri & Shadlen 2015 (PMID:26455307) | 高 |
| 尾状核跟踪时间流逝，齿状核精调末端 | 猴子单元记录 | Kunimatsu et al. 2018 (PMID:29963985) | 中（单物种） |

## 连接

- [[basal-ganglia]] — 纹状体（尾状核/壳核）是区间计时的核心结构
- [[dopamine-reward-prediction-error]] — DA 奖励信号强化"正确时刻"的纹状体突触
- [[time-cells]] — 区间计时的互补系统：纹状体计量 vs 海马定位
- [[circadian-clock]] — 更长时间尺度（24 小时）的另一种生物时钟机制

## 未解问题

- Q-timecell-longscale：分钟到小时的时间信息（超出典型区间计时范围）如何编码？

## 修订历史

- 2026-07-26 · 创建 · 基于《时间的神经地图：海马时间细胞如何让大脑记住"几时"》· 初始置信度：高

## 来源文章

- [[2026-07-26-hippocampal-time-cells-temporal-coding]]

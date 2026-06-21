---
title: 误差相关负波（Error-Related Negativity, ERN）
slug: error-related-negativity
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-23
updated: 2026-08-23
revision_count: 1
dimensions: [cognition, methods]
related: [anterior-cingulate-cortex, frontal-midline-theta, conflict-monitoring, dopamine-reward-prediction-error, response-inhibition]
prerequisites: [anterior-cingulate-cortex, dopamine-reward-prediction-error]
opens_questions: []
source_articles: [2026-08-23-dacc-error-monitoring-conflict-effort]
key_sources: ["PMID:10686361", "PMID:12374324"]
---

# 误差相关负波（Error-Related Negativity, ERN）

> **一句话定义**：错误反应发生后约 50–100ms 出现于前额叶中线（dACC/MCC）的负向 EEG 电位，是大脑内部错误监测机制的电气表达，早于主观意识对错误的觉察。

## 当前理解

ERN（又称 Ne，error negativity，由 Falkenstein 团队命名）是认知神经科学中最重要的电生理成分之一。它提供了大脑"自动检测自身错误"的直接神经证据：

- 在受试者按下错误键后约 **50–100ms** 内出现
- 幅值约 **3–10 μV**（负向，在 Fz/FCz 电极最大）
- 来源定位：dACC/MCC（多项研究一致，颅内记录直接证实）
- 出现于主观错误觉察之前（Pe 成分，200–400ms 后，才更多对应有意识觉察）

ERN 之后通常跟随一个**错误后正波（Pe，post-error positivity）**，反映更高阶的错误意识处理和行为调整准备。

## 关键机制

### Holroyd & Coles 强化学习框架（2002）

最有影响力的 ERN 解释将其纳入强化学习框架：

```
错误发生
  → 基底核输出：负向预测误差（RPE < 0）
  → VTA/SNc 多巴胺活动降低
  → DA 信号传递至 dACC
  → dACC 接收 DA 下降 → 产生 ERN
```

关键预测：
1. ERN 幅值随学习进展减小（随着预测更准，RPE 更小）
2. ERN 幅值与随后的行为调整量正相关
3. 药物/状态改变 DA 信号应影响 ERN

### θ 振荡基础

ERN 是 dACC 产生的前额叶中线 θ（FMθ，4–8Hz）在错误事件时刻的**相位重置**和**功率增强**的表现（Cavanagh & Frank 2014）。ERN 与 N2（冲突后）、FRN（负性反馈后）共享同一 θ 频谱基础，是 θ 振荡在不同触发事件下的时域表达。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| ERN 来源于 dACC/MCC | 偶极源分析 + 颅内记录 | Falkenstein 2000, PMID:10686361 | 高 |
| ERN 为多巴胺负向 RPE 在 ACC 的表达 | 计算模型 + 行为/ERP 整合 | Holroyd & Coles 2002, PMID:12374324 | 中（机制间接） |
| ERN 与 N2/FRN 共享 θ 频谱特征 | EEG 时频分析 + 综述 | Cavanagh & Frank 2014, PMID:24835663 | 高 |
| ERN 早于主观错误意识觉察 | ERP + 主观报告时间对比 | 多项研究 | 高 |

## 连接

- [[anterior-cingulate-cortex]] — dACC/MCC 是 ERN 的主要生成器
- [[frontal-midline-theta]] — ERN 是 FMθ 在错误时刻的时域表达
- [[conflict-monitoring]] — ERN 和 N2 共享 dACC 计算起源；错误是特殊的高冲突事件
- [[dopamine-reward-prediction-error]] — Holroyd & Coles 框架中，DA 下降是 ERN 的触发因子
- [[response-inhibition]] — 错误后增加的反应抑制部分通过 ERN→控制追加机制实现

## 修订历史

- 2026-08-23 · 创建 · 基于《背侧前扣带皮层的三重计算》文章（#121）· 初始置信度：高

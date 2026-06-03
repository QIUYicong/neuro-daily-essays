---
title: 星形胶质细胞钙信号
slug: astrocyte-calcium-signaling
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-02
updated: 2026-07-02
revision_count: 1
dimensions: [molecular, cellular, synaptic]
related: [astrocyte, tripartite-synapse, d-serine, gliotransmitter, ltp, nmda-receptor, neuromodulator-systems]
prerequisites: [astrocyte, synaptic-transmission]
opens_questions: [Q-astro-02]
source_articles: [2026-07-02-astrocyte-tripartite-synapse]
key_sources: ["PMID:1967852", "PMID:20075918", "PMID:10322493"]
---

# 星形胶质细胞钙信号 (Astrocyte Calcium Signaling)

> **一句话定义**：星形胶质细胞以胞质 Ca²⁺ 浓度的振荡性升高作为"非电兴奋性"信号载体，由突触谷氨酸激活 mGluR → IP₃-ER 通路触发，可在胶质网络中传播为钙波，并下游触发 D-丝氨酸等胶质递质的释放，是三方突触中星形胶质细胞"感知—响应"突触活动的核心机制。

## 当前理解

我们现在认为，星形胶质细胞虽不产生动作电位，但拥有以 Ca²⁺ 为信号载体的独特兴奋性系统。星形胶质细胞的钙信号与神经元的电信号形成一种**慢速/分散的并行信号通道**，负责感知和整合突触活动的时空模式。

**触发机制**：
- 突触前释放的谷氨酸溢出至 PAPs，激活代谢型谷氨酸受体（mGluR1/5）→ Gq → PLC → IP₃ 产生 → IP₃R（内质网上的 Ca²⁺ 释放通道）开放 → 胞质 Ca²⁺ 浓度振荡性升高约 10 倍
- 突触 ATP 激活 P2Y 受体（同一通路）
- 内源大麻素激活 CB1 受体（部分星形胶质细胞）

**传播**：单个星形胶质细胞的 Ca²⁺ 信号可通过 connexin43 缝隙连接向邻近细胞传播，形成以 15–27 μm/s 传播的**钙波**（Cornell-Bell et al. 1990）。钙波可在数百微米范围内协调多个星形胶质细胞的 D-丝氨酸释放。

**激活阈值**：体外研究表明，星形胶质细胞的钙信号存在激活阈值——需要足够强度的突触活动（谷氨酸溢出量）才能触发。这个阈值在不同脑状态下是否改变，以及神经调质（NE、ACh、DA）是否通过直接作用星形胶质细胞来调整此阈值，是重要的未解问题（Q-astro-02）。

## 关键机制

### IP₃-ER 信号链

```
突触谷氨酸溢出
       ↓ (mGluR1/5 激活)
    Gq → PLC
       ↓
    IP₃ 产生
       ↓ (IP₃R 开放，位于内质网)
    胞质 Ca²⁺ 振荡性升高 (~10×)
       ↓
    激活胶质递质释放（D-丝氨酸、ATP、谷氨酸）
```

### 钙波传播

Ca²⁺ 升高 → 触发 connexin43 缝隙连接中的 IP₃ 扩散（或直接 Ca²⁺ 扩散）→ 邻近星形胶质细胞 IP₃R 激活 → 形成行波（15–27 μm/s）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 谷氨酸诱导星形胶质细胞 Ca²⁺ 振荡和钙波 | Fluo-3 成像，培养海马星形胶质细胞 | PMID:1967852 | 高（Science；多次重复） |
| 星形胶质细胞 Ca²⁺ 钳制消除 LTP（间接证明 Ca²⁺ 控制 D-丝氨酸释放）| 单细胞 patch-clamp + EGTA | PMID:20075918 | 高（Nature） |
| mGluR 依赖的星形胶质细胞 Ca²⁺ 升高 | mGluR 特异性激动/拮抗剂实验 | 多项研究（见 PMID:10322493）| 高 |

## 连接

- [[astrocyte]] — 钙信号是星形胶质细胞功能的核心载体
- [[d-serine]] — Ca²⁺ 信号门控 D-丝氨酸释放
- [[gliotransmitter]] — Ca²⁺ 是触发多种胶质递质释放的共同上游信号
- [[tripartite-synapse]] — Ca²⁺ 信号是三方突触中星形胶质细胞响应神经元的机制
- [[ltp]] — Ca²⁺ → D-丝氨酸 → NMDA 激活 → LTP 诱导

## 未解问题

- Q-astro-02：体内星形胶质细胞钙信号的激活阈值及其在不同脑状态（清醒/睡眠/压力）下的变化

## 修订历史

- 2026-07-02 · 创建 · 基于《大脑的第三方》(#68) · 初始置信度：高（机制基本确立；体内激活条件有待深入）

## 来源文章

- [[2026-07-02-astrocyte-tripartite-synapse]]

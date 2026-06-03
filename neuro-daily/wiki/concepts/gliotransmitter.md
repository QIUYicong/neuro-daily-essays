---
title: 胶质递质
slug: gliotransmitter
domain: concepts
type: concept
status: mainstream
confidence: medium
created: 2026-07-02
updated: 2026-07-02
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [astrocyte, tripartite-synapse, d-serine, astrocyte-calcium-signaling, nmda-receptor, ltp, ltd, synaptic-transmission]
prerequisites: [astrocyte, synaptic-transmission]
opens_questions: [Q-astro-01]
source_articles: [2026-07-02-astrocyte-tripartite-synapse]
key_sources: ["PMID:10322493", "PMID:7911978", "PMID:16025096", "PMID:34334233"]
---

# 胶质递质 (Gliotransmitter)

> **一句话定义**：星形胶质细胞（以及其他胶质细胞）释放的、能够作用于神经元或其他细胞受体并调控突触传递和可塑性的活性分子，包括 D-丝氨酸、ATP/腺苷和谷氨酸。

## 当前理解

我们现在认为，星形胶质细胞能够主动释放多种活性分子，统称为胶质递质。这些分子通过作用于神经元的不同受体，对突触功能产生多样化的调控效果：

**主要胶质递质及功能**：

| 分子 | 主要靶受体 | 主要效果 |
|------|---------|--------|
| D-丝氨酸 | NMDA 受体 GluN1 协同位点 | 升高 NMDA 受体激活阈值；LTP 必要条件 |
| ATP → 腺苷 | A1R（抑制性）；P2X/P2YR | A1R 突触前抑制；LTD；睡眠稳态 |
| 谷氨酸 | 突触外 NMDA/mGluR | 慢内向电流（SIC）；增加神经元兴奋性 |

**争议状态**：胶质递质的释放机制存在重大争议（见下），整体概念的置信度为中等（框架被广泛接受，但部分分子的体内释放机制仍在论证中）。

## 关键机制

### 三种假定释放机制

**1. 钙依赖 SNARE 介导胞吐（争议中）**：
星形胶质细胞含有表达 VAMP-3 等 SNARE 蛋白的囊泡。Ca²⁺ 升高可能触发囊泡胞吐，释放 D-丝氨酸或谷氨酸。这是最初提出的机制，但体内证据的充分性受到质疑。

**2. 体积敏感阴离子通道（VRAC/LRRC8）**：
细胞肿胀或局部 Ca²⁺ 信号可能开放 VRAC，允许谷氨酸等阴离子分子外流。这是体积调节条件下谷氨酸释放的可能机制。

**3. 连接蛋白半通道（connexin hemichannels）**：
未配对的 connexin43 半通道可在特定条件下开放，允许 ATP 等分子外漏。

**溶酶体胞吐（ATP）**：ATP 的释放可能通过溶酶体胞吐而非突触小泡型囊泡，Ca²⁺ 依赖但机制与神经元突触前释放不同。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 星形胶质细胞可释放谷氨酸并激活神经元 | 体外实验：机械刺激/IP₃诱导 → 神经元 NMDAR EPSC 增加 | PMID:7911978 | 中（体外，生理条件有争议） |
| D-丝氨酸以 Ca²⁺ 依赖方式从星形胶质细胞释放 | Ca²⁺ 钳制实验；HOAsp 阻断；D-丝氨酸恢复 | PMID:20075918 | 高（间接但有力证据） |
| ATP 经溶酶体胞吐释放 | 溶酶体 VAMP-7 标记；破坏溶酶体阻断 ATP 释放 | 多项研究 | 中 |

## 矛盾记录

**C-2026-07-02-01（open）**：关于星形胶质细胞 Ca²⁺ 依赖性谷氨酸胞吐在生理条件下是否真实发生：
- Parpura 1994 及后续研究（体外）：Ca²⁺ 升高导致谷氨酸释放并激活神经元
- Fiacco et al. 2007 / Bhatt et al. 2009：选择性诱导星形胶质细胞 Ca²⁺ 升高未见神经元效应
- 现状 open：D-丝氨酸的 Ca²⁺ 依赖释放有更强证据；谷氨酸的 Ca²⁺ 依赖胞吐证据仍有争议

## 连接

- [[astrocyte]] — 主要产生和释放胶质递质的细胞
- [[d-serine]] — 最重要的胶质递质，对 LTP 有直接因果作用
- [[astrocyte-calcium-signaling]] — 触发胶质递质释放的上游信号
- [[tripartite-synapse]] — 胶质递质是三方突触中星形胶质细胞发出信号的媒介
- [[ltp]] — D-丝氨酸是 LTP 的必要胶质递质
- [[ltd]] — ATP/腺苷和 D-丝氨酸参与不同类型 LTD

## 未解问题

- Q-astro-01：D-丝氨酸的精确释放机制（囊泡胞吐 vs 转运体逆转 vs VRAC）

## 修订历史

- 2026-07-02 · 创建 · 基于《大脑的第三方》(#68) · 初始置信度：中（概念广泛接受，部分分子释放机制仍有争议；已登记矛盾 C-2026-07-02-01）

## 来源文章

- [[2026-07-02-astrocyte-tripartite-synapse]]

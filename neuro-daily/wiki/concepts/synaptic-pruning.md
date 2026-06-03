---
title: 突触修剪
slug: synaptic-pruning
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-04
updated: 2026-07-04
revision_count: 1
dimensions: [synaptic, cellular, microcircuit, cognition, development, disease]
related: [complement-synaptic-pruning, microglia, hebbian-learning, ltp, homeostatic-plasticity, adult-neurogenesis, alzheimers-disease]
prerequisites: [synaptic-transmission, hebbian-learning]
opens_questions: [Q-microglia-01, Q-microglia-02, Q-microglia-04]
source_articles: [2026-07-04-microglia-synaptic-pruning]
key_sources: ["PMID:18083105", "PMID:21778362", "PMID:22632727", "PMID:26814963"]
---

# 突触修剪 (Synaptic Pruning)

> **一句话定义**：大脑发育过程中将过剩的突触连接有选择性地消除的过程，主要在生命早期（人类约从胎儿晚期到青春期）执行，是神经回路从冗余到精确的必要转变。

## 当前理解

我们现在认为，突触修剪是神经回路发育的一个核心策略：大脑先生产大量冗余连接，再根据实际使用（神经活动）进行精修，保留强/活跃的突触，消除弱/不活跃的突触。

修剪并非随机——它具有**活动依赖性**：活跃使用的突触被保留，长期低活动的突触被消除。在分子机制上，目前最清楚的是**补体介导的微胶质修剪**（见 complement-synaptic-pruning 页），但也存在非补体机制（PS 外翻-TREM2 通路等）。

修剪的时间窗与**关键期（critical period）** 高度重叠：发育关键期内，神经活动不仅加强突触（LTP），也同时触发对弱突触的补体标记和微胶质清除。关键期结束后，修剪速率大幅降低，回路趋于稳定。

**人类突触密度的发育轨迹**：
- 胎儿晚期：突触快速形成（synaptogenesis 爆发）
- 出生至 2 岁：额叶突触密度达到成人的约 150%（Huttenlocher et al.）
- 儿童期至青春期：持续修剪，突触密度逐步降至成人水平
- 青春期额叶修剪速度加快（与 C4 表达峰值重叠，Sekar 2016）
- 成年：突触密度相对稳定（维持有限的结构可塑性）

## 关键机制

### 1. 补体-微胶质通路（主要机制）
详见 [[complement-synaptic-pruning]] 页面。
核心：C1q/C3 标记弱突触 → 小胶质 CR3/TREM2 识别 → 吞噬消化。

### 2. 磷脂酰丝氨酸（PS）通路
弱/异常突触的 PS 外翻作为独立 eat-me 信号。

### 3. 轴突前末梢的竞争性撤退
轴突间通过神经营养因子（如 BDNF）竞争突触后位点；弱输入轴突因无法维持靶细胞的营养支持而撤退（但这更多是轴突修剪而非突触消除）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 突触密度在发育早期过剩，青春期前降至成人水平 | 尸检脑组织定量（额叶突触密度）| Huttenlocher et al. 1979 | 高 |
| 微胶质吞噬突触物质，CX3CR1 KO 导致突触过剩 | CX3CR1-GFP 小鼠 PSD-95 追踪 | Paolicelli 2011, PMID:21778362 | 高 |
| C1q/C3 为突触精修必需分子 | KO 小鼠视网膜膝状体精修缺陷 | Stevens 2007, PMID:18083105 | 高 |
| C4A 高拷贝 → 青春期过度修剪假说 | 遗传学+小鼠数据 | Sekar 2016, PMID:26814963 | 中（机制为推断）|
| 精修具有活动依赖性 | 单眼阻断+CR3 KO，视网膜膝状体 | Schafer 2012, PMID:22632727 | 高 |

## 连接

- [[complement-synaptic-pruning]] — 突触修剪的主要分子机制
- [[microglia]] — 执行细胞
- [[hebbian-learning]] — 互补机制（修剪消除弱连接，Hebbian 强化强连接）
- [[homeostatic-plasticity]] — 功能性调整（突触稳态缩放）vs 结构性删除（修剪）
- [[alzheimers-disease]] — 发育修剪机制的病理重激活
- [[adult-neurogenesis]] — 另一种维持大脑结构可塑性的机制

## 未解问题

- Q-microglia-01：什么分子信号决定某一突触被 C1q 标记（活动→分子标记的具体转换）？
- Q-microglia-04：突触修剪（结构消除）与突触稳态缩放（功能减弱）如何协调？

## 修订历史

- 2026-07-04 · 创建 · 基于《大脑的免疫剪刀》(#70) · 初始置信度：高

## 来源文章

- [[2026-07-04-microglia-synaptic-pruning]]

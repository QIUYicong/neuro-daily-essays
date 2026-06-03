---
title: 小胶质细胞
slug: microglia
domain: concepts
type: entity
status: established
confidence: high
created: 2026-07-04
updated: 2026-07-04
revision_count: 1
dimensions: [cellular, molecular, synaptic, microcircuit, cognition, disease]
related: [complement-synaptic-pruning, synaptic-pruning, astrocyte, tripartite-synapse, homeostatic-plasticity, alzheimers-disease, sharp-wave-ripples]
prerequisites: [synaptic-transmission, ltp]
opens_questions: [Q-microglia-01, Q-microglia-02, Q-microglia-04]
source_articles: [2026-07-04-microglia-synaptic-pruning]
key_sources: ["PMID:18083105", "PMID:21778362", "PMID:22632727", "PMID:27033548", "PMID:32657463", "PMCID:PMC6252206"]
---

# 小胶质细胞 (Microglia)

> **一句话定义**：大脑的居民免疫细胞，占脑细胞总数 5–15%，在健康大脑中持续执行高度动态的突触监视与主动结构雕刻功能，而非仅在损伤时才激活的被动守卫。

## 当前理解

我们现在认为，小胶质细胞是大脑神经回路精修的**主动建筑师**，而非被动的"应急消防员"。在发育期（出生后数周至数月），小胶质细胞通过识别弱活动突触上的分子标记（主要是补体蛋白 C1q/C3/iC3b）并经由 CR3 受体将其定向吞噬，执行**活动依赖性突触修剪**——这是将冗余的过剩连接雕刻为精确功能回路的必要步骤。

在健康成年大脑中，小胶质细胞处于高度动态的"监视状态"（ramified morphology）：突起每小时完整扫描一遍全脑，持续与突触接触但不吞噬。这种监视可能参与突触稳态调节、免疫监控和局部细胞因子释放。

小胶质细胞的功能被严重低估了近半个世纪。Paolicelli et al. 2011 首次直接证明它在正常发育中吞噬突触材料（PSD-95 被检测到在微胶质内部），CX3CR1 缺失小鼠的多余突触和回路功能受损确认了这一功能的必要性。

## 关键机制

### 1. 发育期突触修剪
- **补体识别**：弱活动突触表面积累 C1q → 激活 C3 → iC3b 沉积 → 小胶质 CR3 识别 → 吞噬
- **CX3CR1 通路**：神经元分泌分形素（fractalkine/CX3CL1），小胶质 CX3CR1 受体接收，维持正常监视活动和突触互动
- **磷脂酰丝氨酸（PS）外翻**：弱突触 PS 翻转至膜外侧，被 TREM2 等受体识别为"eat-me"信号（Scott-Hewitt 2020）
- **活动依赖性**：神经活动强的突触受到保护（可能通过维持糖基化保护 C1q 结合位点）；弱活动突触优先被标记和清除

### 2. 双重角色：拆除与建设
小胶质细胞不只是拆除者，也可释放：
- **BDNF**：促进突触成熟和稳定
- **TSP-1（血小板反应素-1）**：促进突触发生
- **促炎细胞因子（TNFα、IL-1β）**：在激活状态下影响突触传递（见 tripartite-synapse 页面）

### 3. 成年期功能
在正常成年大脑中，持续的微胶质监视可能参与：
- 清除凋亡细胞碎片
- 维持局部免疫稳态
- 调节炎症反应阈值
- 有限的突触修整（成熟大脑中规模远小于发育期）

### 4. 病理激活
在阿尔茨海默病中，Aβ 寡聚体重激活 C1q/C3 通路，导致小胶质细胞在成熟突触上过度修剪（Hong 2016）。
在精神分裂症中，C4A 基因高拷贝数可能增强青春期额叶的补体标记，导致过度修剪（Sekar 2016，机制推断）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 小胶质细胞在正常发育中吞噬突触物质 | CX3CR1-GFP 小鼠中 PSD-95 在微胶质内 | Paolicelli et al. 2011, PMID:21778362 | 高 |
| CX3CR1 缺失→突触过剩→回路功能受损 | KO 小鼠 mEPSC 减小，CA1 突触密度增加 | Paolicelli et al. 2011, PMID:21778362 | 高 |
| 微胶质突触修剪依赖 CR3/C3 通路 | CR3 KO 小鼠精修缺陷；活动操控实验 | Schafer et al. 2012, PMID:22632727 | 高 |
| Aβ 重激活微胶质修剪导致 AD 突触丢失 | J20 小鼠，SIM 超分辨，抗 C1q 拯救 | Hong et al. 2016, PMID:27033548 | 高 |
| PS 外翻为微胶质吞噬的"eat-me"信号 | 荧光 PS 传感器；TREM2 相关实验 | Scott-Hewitt 2020, PMID:32657463 | 中 |

## 连接

- [[complement-synaptic-pruning]] — 微胶质执行修剪的分子机制
- [[synaptic-pruning]] — 修剪过程的广义框架
- [[astrocyte]] — 神经胶质家族；星形胶质细胞通过 TGF-β 调节 C1q 表达
- [[tripartite-synapse]] — 三方突触概念；微胶质与星形胶质共同构成"四方突触"环境
- [[homeostatic-plasticity]] — 微胶质修剪（结构）与突触稳态缩放（功能）的协调/竞争
- [[alzheimers-disease]] — Aβ 重激活微胶质修剪是 AD 早期突触丢失的关键机制

## 未解问题

- Q-microglia-01：活动依赖性 C1q 标记的精确分子机制（什么让弱突触 C1q 更容易沉积？）
- Q-microglia-02：发育修剪 vs AD 病理修剪的分子差异（为何后者无差别？）
- Q-microglia-04：微胶质修剪与突触稳态可塑性（缩放 vs 删除）的分子决定因素

## 修订历史

- 2026-07-04 · 创建 · 基于《大脑的免疫剪刀：小胶质细胞如何用补体蛋白雕刻神经回路》(#70) · 初始置信度：高（实体层面 established；具体机制细节 high-medium）

## 来源文章

- [[2026-07-04-microglia-synaptic-pruning]]

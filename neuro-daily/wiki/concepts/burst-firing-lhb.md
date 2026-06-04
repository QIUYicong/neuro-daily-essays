---
title: 外侧缰核爆发放电（抑郁机制）
slug: burst-firing-lhb
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-11
updated: 2026-07-11
revision_count: 1
dimensions: [molecular, cellular, synaptic, brain-region, disease]
related: [lateral-habenula, hpa-axis, neuroinflammation, glucocorticoid-hippocampus-plasticity, thalamic-firing-modes]
prerequisites: [lateral-habenula, action-potential, t-type-calcium-channels-thalamus]
opens_questions: [Q-lhb-01, Q-lhb-02, Q-lhb-03]
source_articles: [2026-07-11-lateral-habenula-depression-ketamine]
key_sources: ["PMID:29446379", "PMID:29446381", "PMID:37853123", "PMID:23990563"]
---

# 外侧缰核爆发放电（抑郁机制）(LHb Burst Firing in Depression)

> **一句话定义**：在抑郁状态下，LHb神经元从正常的4-6 Hz紧张性放电切换为爆发性（burst）放电模式（每束3-10个锋电位，theta频段4-8 Hz同步），这需要NMDA受体激活和T型Ca²⁺通道去失活协同产生，是三重分子改变（βCaMKII↑、Kir4.1星形胶质失调、突触前增益↑）的最终收敛点，也是氯胺酮NMDAR通道捕获的靶向作用位点。

## 当前理解

LHb爆发放电是将"慢性应激分子改变→单胺递质抑制→抑郁症状"因果链在电生理层面的关键中间步骤。它不是一种单纯的神经元固有属性，而是由多个分子层面的上游变化（突触增益、Kir4.1、βCaMKII）汇聚产生的网络动力学状态。

**爆发放电的产生机制**：
1. 慢性应激→Kir4.1星形胶质失调→突触外K⁺浓度改变→LHb神经元静息膜电位超极化
2. 超极化状态→T型Ca²⁺通道（CaV3）从"稳态失活"中恢复（去失活）→准备就绪
3. 兴奋性输入到来（βCaMKII→GluA1↑使LHb对输入更敏感）→轻度去极化→T型Ca²⁺激活→爆发
4. 爆发期间NMDA受体高频开放→氯胺酮进入通道孔被捕获→爆发终止（治疗机制）

**爆发放电的病理效应**：
- LHb爆发→持续激活RMTg（GABA）→DA神经元持续抑制
- LHb爆发→持续抑制DRN→5-HT减少
- 结果：快感缺失 + 动机缺乏 + 习得性无助（通过不同的并行下游回路）

**氯胺酮的靶向性**：
LHb爆发放电期间NMDA受体**高频、大量开放**，为氯胺酮的使用依赖性捕获（use-dependent trapping）创造了最优条件——爆发越剧烈，氯胺酮捕获率越高，这形成了"病理状态自我靶向治疗"的罕见机制（PMID:37853123）。

## 与视丘爆发放电的比较

LHb爆发放电与视丘T型Ca²⁺通道爆发放电（见[[thalamic-firing-modes]]）共享相同的**T型Ca²⁺通道依赖性超极化触发机制**，但功能意义截然不同：
- **视丘爆发**：在清醒状态下可增强时序精度（Borden 2022），睡眠期间产生纺锤波
- **LHb爆发**（病理性）：持续压制单胺能系统，产生抑郁症状

这是同一离子通道机制在不同回路语境中产生完全不同功能结果的典型案例。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 抑郁大鼠LHb爆发↑+theta同步↑，氯胺酮逆转 | 体内电生理+CMS模型 | PMID:29446381 | 高 |
| 爆发需NMDAR+T型Ca²⁺（两者均必要） | 药理学阻断实验 | PMID:29446381 | 高 |
| 光遗传诱导LHb爆发→因果驱动快感缺失和绝望 | 因果实验 | PMID:29446381 | 高 |
| Kir4.1→超极化→爆发（星形胶质来源）| 双向操控电生理 | PMID:29446379 | 高 |
| βCaMKII→GluA1→内在兴奋性↑→爆发倾向↑ | 质谱+过表达+行为 | PMID:23990563 | 高 |
| 氯胺酮NMDAR捕获：半衰期13分钟→效果24小时 | 切片电生理+动力学建模 | PMID:37853123（PMC10600008）| 高 |

## 争议

NMDA受体是否对LHb爆发**必要**？Yang et al. 2018认为是。但2026年Frontiers新论文报告"NMDA受体对LHb神经元爆发放电并非必要"（在小鼠中）。两个结论可能反映：物种差异（大鼠vs小鼠）、实验条件差异（体内vs体外）、或LHb亚群差异。此矛盾已登记为待裁决争议，见contested_claims。

## 连接

- [[lateral-habenula]] — LHb爆发放电的解剖载体
- [[thalamic-firing-modes]] — 同类T型Ca²⁺通道机制，不同功能背景
- [[glucocorticoid-hippocampus-plasticity]] — 皮质醇通过增强LHA→LHb投射增加爆发倾向
- [[neuroinflammation]] — 炎症细胞因子可能增强LHb突触输入，增加爆发频率

## 修订历史

- 2026-07-11 · 创建 · 基于《大脑的"惩罚计算器"》一文（#79）· 初始置信度：高

## 来源文章

- [[2026-07-11-lateral-habenula-depression-ketamine]]

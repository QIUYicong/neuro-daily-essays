---
title: 突触修剪
slug: synaptic-pruning
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-31
updated: 2026-05-31
revision_count: 1
dimensions: [molecular, cellular, synaptic, brain-region]
related: [critical-period, complement-cns, perineuronal-net, microglia, ltp, hebbian-learning, orientation-selectivity, v1-primary-visual-cortex]
prerequisites: [synaptic-transmission, action-potential]
opens_questions: [Q-cp-02]
source_articles: [2026-05-31-synaptic-pruning-critical-period]
key_sources: ["PMID:22632727", "PMID:18083105", "PMID:21778362", "PMID:27033548"]
---

# 突触修剪 (Synaptic Pruning)

> **一句话定义**：发育期大脑通过补体蛋白（C1q/C3b）标记弱势突触、小胶质细胞（CR3 受体介导）活动依赖地将其吞噬消除的过程，是将初始冗余神经回路精确雕刻为功能性成熟图谱的必要机制。

## 当前理解

我们现在认为，成熟神经回路的精密性不是基因"写死"的，而是通过先过量生产（overproduction）再选择性消除（selective elimination）演化而来的。突触修剪是后一步骤的核心机制。

发育期突触修剪依赖**经典补体级联与小胶质细胞的协作**：
1. 未成熟星形胶质细胞信号诱导神经元表达 **C1q**（补体启动蛋白）
2. C1q 精确沉积于**弱势突触**（活动水平低的突触）
3. C1q 激活补体级联 → **C3b** 共价沉积于突触膜（"调理化"）
4. 小胶质细胞的 **CR3（CD11b-CD18）** 受体识别 C3b → 吞噬清除

修剪具有**活动依赖的选择性**：活动强的突触受到保护，活动弱的突触 C3b 沉积更多，优先被吞噬（Schafer et al. 2012）。这是 Hebbian 学习原则在发育修剪中的分子体现——"同步发放的突触共同存活"。

小胶质细胞-补体修剪机制首先在**视网膜-外侧膝状体回路**中被精确描述，之后在海马和其他脑区独立验证，表明这是大脑发育的通用机制。

## 关键机制

**分子层**：
- C1q：神经元表达，响应未成熟星形胶质细胞信号；分子结构类似免疫系统的"感染标签"，被征用为"弱突触标签"
- C3 裂解产物 C3b：共价沉积于突触膜，稳定的 opsonin
- CR3（=Mac-1，CD11b-CD18）：β₂ 整合素家族；小胶质细胞溶酶体通路末端

**细胞层**：
- 小胶质细胞（microglia）是执行者：利用 CR3 识别 C3b 标记突触 → 主动吞噬进入 CD68+ 溶酶体 → 降解
- 修剪在时间上高度精确：Retinogeniculate 修剪高峰 P5，P9 以后显著下降

**活动依赖选择**：
- TTX 阻断神经活动 → 不活跃眼轴突优先被吞噬
- Forskolin 增强活动 → 保护该侧轴突
- 机制假说：高活动神经元可能通过钙信号或分泌因子（如 fractalkine/CX3CL1）主动抑制 C1q/C3b 在自身突触上的沉积

**回路层**：
- 视觉系统示范：出生后视网膜 RGC 轴突大量冗余分支在 LGN 重叠 → 修剪后分离为眼优势投射区带（关键期内）
- 海马：过多兴奋性突触被修剪 → 信噪比和回路精度提升

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| C1q 沉积于发育期突触，启动修剪 | 免疫染色 + C1q null 小鼠修剪失败 | PMID:18083105 (Stevens 2007) | 高 |
| 小胶质细胞通过 CR3 活动依赖地吞噬弱突触 | Retinogeniculate 模型；CR3 KO 1.3× 突触增加；TTX/Forskolin 操控 | PMID:22632727 (Schafer 2012) | 高 |
| 小胶质细胞修剪对脑发育必要 | CX3CR1 KO：突触修剪失败 + 孤独症样行为 | PMID:21778362 (Paolicelli 2011) | 高 |
| 发育修剪机制在 AD 中被重激活 | AD 模型早期 C1q 上调 + C1q KO 减轻突触损失 | PMID:27033548 (Hong 2016) | 高 |

## 连接

- [[critical-period]] — 突触修剪在视觉皮层关键期内高度活跃，活动依赖修剪驱动眼优势柱形成
- [[complement-cns]] — C1q/C3 是突触修剪的标记分子
- [[microglia]] — 突触修剪的细胞执行者
- [[hebbian-learning]] — 活动依赖的修剪规则（弱者淘汰）在逻辑上与 Hebb 规则对称
- [[ltp]] — 突触强化（LTP）与突触修剪是神经可塑性的两个方向
- [[v1-primary-visual-cortex]] — 眼优势柱是突触修剪经典研究系统
- [[alzheimers-disease]] — 补体修剪机制在 AD 中被病理性重激活

## 未解问题

- **Q-cp-02**：C1q 在人类成年大脑在什么条件下重新激活？是否有可靠的生物标志物能在 AD 突触损失前预警？
- 活动依赖选择的精确"选择函数"是什么？仅仅是总活动水平，还是时序同步性、突触位置等多维信息？
- 不同脑区的修剪选择规则是否统一？

## 修订历史

- 2026-05-31 · 创建 · 基于《发育之剪：视觉皮层关键期、突触竞争与大脑如何将粗糙线路雕刻成精密图谱》· 初始置信度：高（教科书级机制，多个系统独立验证）

## 来源文章

- [[2026-05-31-synaptic-pruning-critical-period]]

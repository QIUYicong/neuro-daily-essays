---
title: 平行纤维
slug: parallel-fiber
domain: concepts
type: structure
status: established
confidence: high
created: 2026-10-11
updated: 2026-10-11
revision_count: 1
dimensions: [cellular, microcircuit, synaptic]
related: [granule-cell, purkinje-cell, cerebellar-ltd, golgi-cell, basket-cell, stellate-cell, expansion-coding]
prerequisites: [granule-cell, cerebellum, synaptic-transmission]
opens_questions: [Q-pf-01]
source_articles: [2026-10-11-granule-cell-parallel-fiber-expansion-coding]
key_sources: ["PMID:37671785", "PMID:31787879", "PMID:17669443"]
---

# 平行纤维（Parallel Fiber）

> **一句话定义**：小脑颗粒细胞轴突在分子层沿冠状面伸展的 T 形分支，全长 3-7mm，顺序接触约 300-500 个浦肯野细胞并在其树突棘上形成弱突触——这种"稀疏接触+大数量"的几何结构，是颗粒细胞展开编码到达浦肯野细胞的物理通道，也是 PF-PC LTD（小脑运动学习）发生的突触位点。

## 当前理解

平行纤维（parallel fiber, PF）是颗粒细胞（granule cell）轴突的上升段在小脑皮层分子层分叉后的两支延伸。它们沿**冠状面**（coronal plane，垂直于小脑叶片长轴）延伸，与浦肯野细胞（Purkinje cell）的树突扇面（在矢状面伸展）形成正交关系。

每根平行纤维：
- 每侧长度约 **3-6mm**（小鼠）至 **5-7mm**（人类），是大脑中最长的局部轴突之一
- 在穿越分子层的路径上，顺序接触约 **300-500 个浦肯野细胞**
- 与每个浦肯野细胞形成 **1-2 个突触**（位于浦肯野细胞远端树突棘上）
- 单个突触强度较弱（低 AMPAR 数量），需要大量平行纤维协同才能驱动浦肯野细胞放电

每个浦肯野细胞接受约 **150,000-175,000 根**不同颗粒细胞的平行纤维输入，是大脑中扇入最高的突触汇聚之一。

平行纤维是**Marr-Albus-Ito 小脑学习理论**的关键中间层：它将颗粒细胞的高维展开编码信号传递给浦肯野细胞，攀爬纤维（climbing fiber）的误差信号则通过 LTD 选择性地减弱与错误相关的 PF-PC 突触。

## 关键几何特征

| 参数 | 数值（小鼠） | 数值（人类）|
|------|------------|-----------|
| 平行纤维单侧长度 | 3-6 mm | 5-7 mm |
| 每根 PF 接触的 PC 数 | ~300-500 | ~300-500 |
| 每个 PC 接受的 PF 数 | ~150,000 | ~150,000-175,000 |
| PF 在分子层的走向 | 冠状面 | 冠状面 |
| PC 树突扇面走向 | 矢状面（正交于 PF） | 矢状面 |

## 关键机制

### 兴奋-抑制的空间结构

平行纤维与分子层抑制性中间神经元（篮状细胞、星形细胞）的相互作用产生了精确的空间信号处理（Prestori et al. 2019）：

- **On-beam（沿束兴奋）**：平行纤维路径上的浦肯野细胞依次被激活，形成一条"兴奋带"
- **Off-beam（离束抑制）**：平行纤维兴奋的篮状细胞和星形细胞，侧向抑制 on-beam 外的浦肯野细胞

这种"中心兴奋-侧向抑制"机制在空间上锐化浦肯野细胞的响应模式，类似视网膜的侧抑制。

### PF-PC LTD：平行纤维的学习位点

当平行纤维活动**先于**攀爬纤维约 50-150ms（峰值 80ms）时，该 PF-PC 突触发生 LTD：
- PF 谷氨酸 → mGluR1 → DAG / IP₃ / 2-AG（内源性大麻素）
- CF → 复杂放电 → 大量 Ca²⁺ 内流
- 两路信号同时激活 → PKCα → GluA2 磷酸化 → AMPAR 内吞 → LTD
- 内源性大麻素 2-AG 是 LTD 的必要中间信号（CB1R 激活，阻断 CB1R 则 LTD 消失）（Safo & Regehr 2008）

LTD 的生物学结果：减弱"造成错误的那组平行纤维"对浦肯野细胞的兴奋驱动，使浦肯野细胞在下次遇到相同运动上下文时响应减弱，从而减少对深部小脑核（DCN）的 GABA 抑制，改善运动输出。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| PF 走向冠状面、与 PC 树突正交 | 解剖学（Cajal 及后续 EM 研究） | 经典 | 高 |
| 每个 PC 约接受 150,000 PF 输入 | 细胞计数 + 突触计数 | 多来源 | 高 |
| LTD 需要 PF 先于 CF 50-150ms | 精确时序刺激实验（离体切片） | PMID:17669443 | 高 |
| CB1R 阻断完全阻止 LTD | AM251 药理实验 | PMID:17669443 | 高 |
| On-beam 兴奋 + off-beam 抑制 | 电生理 + 双光子成像 | PMID:31787879 | 高 |

## 连接

- [[granule-cell]] — 平行纤维的细胞来源
- [[purkinje-cell]] — 平行纤维的主要投射目标
- [[cerebellar-ltd]] — PF-PC 突触的 LTD 机制
- [[climbing-fiber-error-signal]] — 与平行纤维时序协同触发 LTD 的误差信号
- [[golgi-cell]] — 接受平行纤维兴奋（前馈反馈高尔基细胞抑制颗粒细胞）
- [[basket-cell]] — 接受平行纤维兴奋并侧向抑制浦肯野细胞
- [[expansion-coding]] — 平行纤维是展开编码的"输出线"

## 未解问题

- Q-pf-01：平行纤维的精确走向（冠状面）在演化上是否最优，还是仅仅是发育约束的结果？能否通过基因操控改变 PF 走向并观察运动学习的影响？

## 修订历史

- 2026-10-11 · 创建 · 基于《宇宙中最大的展开器》(#173) · 来源：Safo & Regehr 2008、Prestori et al. 2019、Xie et al. 2023 · 初始置信度：高

## 来源文章

- [[2026-10-11-granule-cell-parallel-fiber-expansion-coding]]

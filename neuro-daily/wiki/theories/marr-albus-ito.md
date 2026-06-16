---
title: 马尔-阿尔布斯-伊藤模型
slug: marr-albus-ito
domain: theories
type: theory
status: mainstream
confidence: high
created: 2026-10-12
updated: 2026-10-12
revision_count: 1
dimensions: [synaptic, microcircuit, brain-region, behavior]
related: [cerebellar-ltd, climbing-fiber-error-signal, purkinje-cell, granule-cell, parallel-fiber, inferior-olive, forward-model, deep-cerebellar-nuclei, molecular-layer-interneurons]
prerequisites: [purkinje-cell, granule-cell, parallel-fiber, cerebellar-ltd, climbing-fiber-error-signal]
opens_questions: [Q-mai-01, Q-mai-02, Q-mai-03]
source_articles: [2026-10-12-marr-albus-ito-cerebellar-learning-model]
key_sources: ["PMID:23440175", "PMID:21482355", "PMID:24814344", "PMID:26330521", "PMID:22895474", "PMID:32599123"]
---

# 马尔-阿尔布斯-伊藤模型 (Marr-Albus-Ito Model, MAI)

> **一句话定义**：小脑通过下橄榄核攀爬纤维的误差信号，在平行纤维-浦肯野细胞突触处诱导长时程抑制（LTD），从而将运动误差转化为突触权重更新，实现监督式运动精细化学习的经典计算框架。

## 当前理解

我们现在认为，MAI模型是目前神经科学中**将计算目标、算法规则、神经实现三层次完整连接**起来的少数理论之一，尽管其经典版本（LTD是必要且唯一机制）已被后续实验所修正。

**MAI框架的核心逻辑仍然成立**：
- 平行纤维携带运动情景上下文信号
- 攀爬纤维携带来自下橄榄核的误差/教学信号
- 两者在浦肯野细胞处的联合激活触发突触可塑性（主要是LTD，但不限于LTD）
- 多次学习后，浦肯野细胞在"即将出错"的情景下自动压制响应，深部小脑核去抑制，运动输出精细化

**修正内容**（2011年后）：
1. PF-PC LTD对许多运动学习范式**不是唯一必要条件**——三种LTD阻断小鼠在VOR适应、眼皮条件学习和跑梯运动学习中均表现正常（Schonewille et al. 2011, PMID:21482355）
2. **分布式协同可塑性**（distributed synergistic plasticity）：小脑学习涉及至少8种突触位点的可塑性，包括PF-PC LTD、MLI突触LTP、PC-DCN突触、颗粒层MF-GC LTP等
3. 攀爬纤维不是二进制"误差信号器"：**复杂放电时长**梯度编码误差幅度（-0.70 sp/s per ms CS时长；Yang & Lisberger 2014, PMID:24814344）
4. 不同小脑模块（Zebrin阳性/阴性分区）用不同可塑性策略完成不同类型学习

**监督学习框架的核心仍然成立**：攀爬纤维作为教学信号，误差驱动突触权重更新，小脑实现类似delta规则的计算——与人工神经网络中的监督学习在算法层次同构。

## 关键机制

### 计算级：解决延迟反馈下的运动精细化问题

感觉反馈有50-200ms延迟，快速运动无法依赖实时反馈纠错。小脑作为**前向内部模型**载体，通过预测运动感觉后果并提前补偿，解决延迟反馈问题（Wolpert et al. 1998, PMID:21227230）。

### 算法级：delta规则的生物学实现

学习规则可简化为：
`Δw(PF→PC) = -η × [CF活动] × [PF活动]`

即：当攀爬纤维（教师）在场且某平行纤维活跃时，该PF→PC连接权重按学习率η减弱。等价于有监督学习的delta（δ）规则。

### 实现级：LTD分子级联

1. PF释放谷氨酸 → 激活mGluR1 + AMPA受体
2. CF触发强烈去极化 → 大量Ca²⁺内流
3. 高Ca²⁺ + mGluR1激活 → PKC磷酸化GluA2 S880位点
4. PICK1介导AMPA受体内化 → 突触传递效率持续下降（LTD）
5. **时序窗**：PF必须领先CF约50-500ms才能有效诱导LTD

### Zebrin分区：两种可塑性策略

- **Zebrin阳性（绒球/副叶）**：基础放电60 Hz；VOR适应中PC简单放电增多（LTP主导）
- **Zebrin阴性（前叶C2区）**：基础放电90 Hz；眼皮条件学习中PC简单放电减少（LTD主导）→ DCN细胞反跳激活 → 运动输出

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 攀爬纤维编码感觉误差（VOR中的视觉滑动）| VOR适应+CF电生理记录 | PMID:23440175 | 高 |
| PF-PC LTD存在（联合刺激诱导）| 体外小脑切片电生理 | PMID:24916287 | 高 |
| LTD对多种运动学习非必要条件 | 三种LTD阻断小鼠VOR/眼皮/跑梯学习正常 | PMID:21482355 PMC3104468 | 高 |
| 复杂放电时长梯度编码误差幅度 | 灵长类单细胞记录；-0.70 sp/s per ms | PMID:24814344 PMC4132823 | 高 |
| Zebrin阳/阴性分区差异化可塑性策略 | 免疫组化+电生理+遗传工具整合 | PMID:26330521 PMC4563713 | 高 |
| 分布式协同可塑性框架 | 综合遗传学+电生理+计算建模 | PMID:22895474 | 高（未读取全文）|

## 连接

- [[cerebellar-ltd]] — MAI模型的核心突触可塑性机制（被修正：LTD是冗余系统之一）
- [[climbing-fiber-error-signal]] — MAI模型的教学信号来源；IO是误差检测最终共同通路
- [[purkinje-cell]] — MAI模型的学习单元；Zebrin分区决定可塑性策略
- [[granule-cell]] — 展开编码提供上下文信号（PF输入的起源）
- [[parallel-fiber]] — 携带运动情景上下文信号
- [[forward-model]] — MAI学习的计算目标（前向内部模型）
- [[deep-cerebellar-nuclei]] — MAI学习的输出门（PC抑制↓→DCN去抑制→运动调整）
- [[molecular-layer-interneurons]] — 分布式可塑性中的协同位点（MLI-LTP）
- [[inferior-olive]] — 攀爬纤维的起源；误差信号整合

## 未解问题

- Q-mai-01：攀爬纤维的复杂放电时长由什么决定？IO如何将误差幅度编码为放电时长？
- Q-mai-02：不同小脑模块（Zebrin阳/阴性）在同一运动学习任务中如何协调？
- Q-mai-03：深部小脑核细胞的突触可塑性与小脑皮层LTD时序如何配合？哪个是"初级存储"？
- 见 state/unresolved_questions.md

## 修订历史

- 2026-10-12 · 创建 · 基于《马尔-阿尔布斯-伊藤模型：小脑如何用攀爬纤维的教学信号学会精确运动》· 初始置信度：高；status=mainstream（经典框架成立但LTD非唯一必要条件）

## 来源文章

- [[2026-10-12-marr-albus-ito-cerebellar-learning-model]]

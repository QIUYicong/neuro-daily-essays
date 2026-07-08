---
title: 小脑颗粒细胞
slug: granule-cell-cerebellar
domain: neurons
type: structure
status: established
confidence: high
created: 2026-09-03
updated: 2026-07-09
revision_count: 3
dimensions: [cellular, synaptic, microcircuit, brain-region]
related: [cerebellum, purkinje-cell, parallel-fiber, climbing-fiber, mossy-fiber]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: [Q-gc-01]
source_articles: [2026-09-03-purkinje-cell-cerebellar-motor-learning, 2026-10-19-parallel-fiber-cerebellar-cortex-computation, 2026-07-09-mossy-fiber-synaptic-diversity-coding]
key_sources: ["PMID:40523942", "PMID:37141091", "PMID:37671785", "PMID:25821914"]
---

# 小脑颗粒细胞 (Cerebellar Granule Cell)

> **一句话定义**：小脑皮层颗粒层的微型兴奋性神经元，人脑约 690 亿个（占全脑神经元约 50–80%），接受苔藓纤维输入后生成平行纤维，对感觉运动情景进行高维重编码，为浦肯野细胞的联想学习提供特征基底。

## 当前理解

小脑颗粒细胞（granule cell，GC）是脑中数量最多的神经元类型。每个 GC 体积极小，轴突上行至分子层后形成"T"字形分叉，构成**平行纤维（parallel fiber，PF）**，水平穿越数百个浦肯野细胞（PC）的树突扇面。

GC 的功能是实现对感觉运动情景的**高维展开（expansion recoding）**：约 7,000 条苔藓纤维输入被展开为约 20 万条平行纤维，形成极高维度的特征表征，使 PC 能以简单线性权重分离各种运动情景。

**稀疏 vs 密集编码争议（2023 更新）**：
- 经典 Marr-Albus 理论预测 GC 应极度稀疏激活（任意时刻仅少数 GC 活跃），形成正交表征，便于 PC 分类
- Xie 等 2023 年计算模型表明，对连续感觉运动变换任务，较密集的 GC 激活反而更优——最优编码密度是**任务依赖**的
- 体内记录有时见到高于预测的 GC 活动密度，与新理论一致

Lee 等 2023 年通过遗传方法特异性阻断 GC 的突触传递（CaV2 敲除），证明 GC 信号对正常运动功能因果必要——运动相关的 PC 调制消失，导致严重运动障碍，尽管 PC 基线放电正常。

GC 还编码**时序信息**：通过级联激活模式，不同 GC 在运动后不同时间点达到激活峰值，形成"时序基底集合"（temporal basis set），使小脑能学习以精确延迟触发预测性运动纠正（Nguyen & Person 2025）。

**输入层的多模态时间编码（2026-07-09 新增）**：GC 的高维展开重编码并非从"性质均一"的输入开始——上游 [[mossy-fiber]] 本身在突触层面就携带"生物物理签名"：来自不同模态（前庭初级/前庭次级/视觉相关）的苔藓纤维终扣，在同一 GC 上表现出可区分的突触强度与短时程动态（Chabrol et al. 2015，PMID:25821914）。当多模态信号同时抵达时，GC 通过放电频率提升和首个动作电位潜伏期的变化实现"跨模态巧合"的时间编码。这意味着 GC 的展开重编码从一开始就不是对同质信号的简单扩维，而是叠加在一个本身已经携带通路身份信息的输入层之上——GC 层的计算，至少部分始于苔藓纤维突触本身的物理特性。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| GC 信号对正常运动功能必要 | CaV2 KO GC → 严重运动障碍，PC 基线正常但运动调制消失 | PMID:37141091 | 高 |
| 最优 GC 编码密度是任务依赖的 | 计算模型优化分析 | PMID:37671785 | 中（理论，待体内验证） |
| GC 生成时序基底集合 | 体内多电极记录 + 计算分析 | PMID:40523942 | 中-高 |
| 同一GC上不同模态苔藓纤维终扣具可区分突触动态，支持多模态巧合时间编码 | 通路特异性刺激+脑片膜片钳 | PMID:25821914 | 高 |

## 连接

- [[cerebellum]] — GC 所在系统
- [[purkinje-cell]] — GC 通过 PF 投射至 PC
- [[parallel-fiber]] — GC 的输出轴突
- [[climbing-fiber]] — 与 PF 同时激活时诱导 PC 的 LTD
- [[mossy-fiber]] — GC 的主要突触前输入；不同模态来源的MF终扣携带可区分的生物物理签名，是GC多模态时间编码的上游基础

## 未解问题

- **Q-gc-01**（中优先级）：不同运动任务下体内 GC 激活密度的实际范围？不同小脑分区（蚓部 vs 半球）是否不同？

## 修订历史

- 2026-09-03 · 创建（简版）· 基于《小脑里的误差教师》一文 · 重点：稀疏 vs 密集编码争议更新（Xie 2023）
- 2026-07-09 · 修订 rev2→rev3 · 基于《颗粒细胞的输入密码：苔藓纤维如何用突触多样性给感觉信号打上"身份标签"》一文（#192）· 新增"输入层的多模态时间编码"段落，整合MF突触多样性作为GC编码的上游基础；关键证据表新增Chabrol 2015；连接新增mossy-fiber；dimensions新增synaptic；key_sources新增PMID:25821914

## 来源文章

- [[2026-09-03-purkinje-cell-cerebellar-motor-learning]]
- [[2026-07-09-mossy-fiber-synaptic-diversity-coding]]

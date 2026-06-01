---
title: 普肯野细胞
slug: purkinje-cell
domain: neurons
type: structure
status: established
confidence: high
created: 2026-06-23
updated: 2026-06-23
revision_count: 1
dimensions: [cellular, microcircuit, brain-region]
related: [climbing-fiber, cerebellar-cortex, cerebellar-ltd, deep-cerebellar-nuclei, complex-spike, parallel-fiber, granule-cell, mglur1]
prerequisites: [action-potential, inhibitory-interneurons, voltage-gated-calcium-channels, ampa-receptor]
opens_questions: [Q-cbm-01, Q-cbm-02]
source_articles: [2026-06-23-cerebellar-learning-purkinje-climbing-fiber]
key_sources: ["PMID:31572132", "PMID:32352914", "PMCID:PMC12546079", "PMID:36632066"]
---

# 普肯野细胞 (Purkinje Cell)

> **一句话定义**：小脑皮层的唯一输出神经元，GABA 能，具有高度展开的平面树突（小鼠约 3.5 万棘，人类约 36 万棘），接受约 1 根攀爬纤维和数万根平行纤维输入，通过两种放电模式（简单棘波/复杂棘波）整合误差教学与运动信息，其突触可塑性（LTD）是小脑运动学习的分子基础。

## 当前理解

普肯野细胞（PC）是小脑皮层信息汇聚的焦点，也是整个小脑对外输出的唯一渠道。它体积巨大，是中枢神经系统中树突形态最复杂的细胞之一——其树突在单一平面内展开成扇形，垂直于平行纤维走行方向，最大化与平行纤维的相遇面积。

**两种放电模式**：
1. **简单棘波（simple spikes，SS）**：约 50–100 Hz，由平行纤维驱动（经颗粒细胞中继），编码当前运动状态和前馈预测信号
2. **复杂棘波（complex spikes，CS）**：约 1 Hz，由唯一的攀爬纤维驱动，产生 2–4 个子棘波的簇发放和整个树突的 Ca²⁺ 风暴，传统上视为误差信号的载体

**关键解剖约束**：每个普肯野细胞只接受来自对侧下橄榄核的**一根**攀爬纤维，这是自然界中最严格的"一对一教师"连接之一。这根攀爬纤维决定了该普肯野细胞的"学习方向"。

**最新修正（Masoli et al. 2025）**：传统估计普肯野细胞有约 100,000 个树突棘，但电镜+AI 分割显示小鼠约 35,000 棘，人类约 360,000 棘。92.7% 的棘有突触（非传统的"90% 静默"）；约 15% 为双头棘，对同时激活两根平行纤维更敏感（PMCID: PMC12546079）。

## 关键机制

### LTD 诱导的分子级联（当 CF + PF 几乎同时激活时）
1. 平行纤维激活 **mGluR1a**（突触后 Gq 蛋白偶联）→ PLCβ → IP₃ → IP₃R → 内质网 Ca²⁺ 释放（局部）
2. 攀爬纤维触发复杂棘波，开放 **P/Q 型 VGCC** → 大量 Ca²⁺ 从胞外内流（广泛树突）
3. 两路 Ca²⁺ 汇聚激活 **PKCα**（需要 Ca²⁺ + DAG）
4. PKCα 磷酸化 AMPA 受体 **GluA2 Ser880** → 破坏 GRIP1/2 锚定 → PICK1 介导 AMPA 受体内吞
5. 该平行纤维-普肯野细胞突触权重持久降低（LTD）

关键证据：mGluR1a（而非 mGluR1b）是充分条件——光遗传激活 mGluR1a + PF 共刺激即可诱导 LTD（Surdin et al. 2023，PMCID: PMC9826949）。

### 复杂棘波的梯度化信号（Zang & De Schutter 2019）
传统认为 CS 是二值信号（有/无），但实际上：
- CS 子棘波数量（2–4 个）、背景突触状态、膜电位状态共同调制 Ca²⁺ 内流幅度
- Ca²⁺ 幅度大 → LTD 幅度大 → 该次误差被"记住"更深
- 这使小脑具备比二值教学信号更高的学习精度

### 简单棘波与误差的双重关系
传统认为 SS 只编码运动信息，CS 编码误差。但 Popa et al.（2016，PMCID: PMC4691440）发现 SS 也随运动误差调整，且调整早于 CS 出现——提示 PC 通过两种放电模式的整合维护连续的预测误差表征。

## 关键证据
| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| mGluR1a 是 LTD 充分条件 | 光遗传体外/体内 | PMCID:PMC9826949（Surdin 2023）| 高 |
| CS 是梯度化误差信号 | 膜片钳+钙成像+计算建模 | PMCID:PMC6749063（Zang 2019）| 中高 |
| SS 也携带连续误差信号 | 体内电生理 | PMCID:PMC4691440（Popa 2016）| 中 |
| 树突棘数量修正（小鼠 3.5 万） | 电镜+AI | PMCID:PMC12546079（Masoli 2025）| 中高 |

## 连接
- [[攀爬纤维]] — 唯一"教师"，触发复杂棘波
- [[小脑 LTD]] — 普肯野细胞学习的分子机制
- [[小脑皮层]] — 所在环境
- [[深部小脑核]] — 被持续抑制的输出靶标

## 未解问题
- 见 Q-cbm-01, Q-cbm-02

## 修订历史
- 2026-06-23 · 创建 · 基于《错误的教育》文章 · 置信度：高

## 来源文章
- [[2026-06-23-cerebellar-learning-purkinje-climbing-fiber]]

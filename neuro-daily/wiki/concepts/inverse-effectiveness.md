---
title: 逆效应性原则
slug: inverse-effectiveness
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-30
updated: 2026-07-30
revision_count: 1
dimensions: [cellular, synaptic, microcircuit]
related: [multisensory-integration, superior-colliculus, nmda-receptor]
prerequisites: [multisensory-integration, nmda-receptor]
opens_questions: []
source_articles: [2026-07-30-multisensory-integration-bayesian-brain]
key_sources: ["PMCID:PMC5375642", "PMID:32113921"]
---

# 逆效应性原则 (Principle of Inverse Effectiveness)

> **一句话定义**：多感觉整合的相对增益（跨模态增强）与单感觉刺激的有效性成反比——弱刺激整合另一感觉后获得最大相对增益，强刺激整合后增益趋近于零。

## 当前理解

逆效应性（Inverse Effectiveness）是 Stein 与 Meredith 在上丘多感觉神经元研究中总结的三条规则之一（另两条为空间规则和时间规则）。

**核心观察**：
- 当单感觉刺激接近阈值（非常弱）时，加入另一感觉模态可以产生高达数倍的放电增益（超加性，superadditivity）
- 当单感觉刺激已接近神经元的饱和（非常强）时，加入另一感觉模态几乎不产生额外增益

**功能意义**：在检测最困难的条件下（弱信号、高噪声、远距离、夜间）提供最大的多感觉补偿——这在生态上高度有意义：在环境允许的情况下，增加感觉冗余最能改善困难情境下的感知和行为。

## 关键机制

### NMDA 受体介导的非线性（细胞级别）

细胞层面的逆效应性由 NMDA 型谷氨酸受体（NMDARs）的非线性特性实现（Bhatt et al. PMCID: PMC5375642）：

1. **弱单感觉输入**：使膜电位抬高但未达充分去极化，NMDA 受体的镁离子阻断未完全解除
2. **第二感觉模态加入**：额外的去极化推过 NMDA 激活阈值，引发 NMDA 通道开放 → 大量 Ca²⁺ 内流 → 放电爆发式增加（非线性超加性）
3. **强单感觉输入**：膜电位已充分去极化，NMDA 阻断已解除，追加信号产生的相对增量小（接近线性叠加，相对增益小）

这是一个精巧的自然设计：单个分子机制（NMDA 受体的镁离子阻断-去除动力学）自动实现了"弱则互补、强则冗余"的整合逻辑。

### 行为学的对应
行为逆效应性：弱视觉闪光 + 弱音 → 检测率提升显著；强视觉 + 强音 → 提升接近零。这在心理物理实验中与神经元层面一致（Stein 组跨越细胞和行为两个层次的验证）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 上丘多感觉神经元的逆效应性（细胞记录） | 猫 SC 多电极记录；系统变化刺激强度 | Meredith & Stein 1993 系列 | 高 |
| NMDA 受体阻断消除超加性（细胞机制） | 上丘神经元膜片钳 + 药理阻断（APV） | PMCID:PMC5375642 | 高 |
| 弱光+弱音行为检测率的逆效应性增强 | 猫多感觉行为测量 | Stein 组系列实验 | 高 |

## 连接

- [[multisensory-integration]] — 上丘整合的三条规则之一
- [[superior-colliculus]] — 逆效应性的主要实验来源
- [[nmda-receptor]] — 逆效应性的细胞分子机制（Mg²⁺ 阻断-去除）

## 修订历史

- 2026-07-30 · 创建 · 基于《感官的裁判》文章 #98 · 初始置信度：高

## 来源文章

- [[2026-07-30-multisensory-integration-bayesian-brain]]

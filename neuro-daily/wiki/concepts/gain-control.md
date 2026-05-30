---
title: 皮层增益控制
slug: gain-control
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-12
updated: 2026-06-12
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, cognition]
related: [acetylcholine-cortex, norepinephrine-locus-coeruleus, neuromodulator-systems, orientation-selectivity, working-memory, v1-primary-visual-cortex]
prerequisites: [synaptic-transmission, action-potential]
opens_questions: []
source_articles: [2026-06-12-neuromodulators-ach-ne]
key_sources: ["PMID:18633352", "PMID:16254995", "PMID:22866031"]
---

# 皮层增益控制 (Cortical Gain Control)

> **一句话定义**：皮层神经元对输入的响应幅度可以被独立于输入本身的机制调节——这种对"输入-输出函数"的乘法性或加法性缩放称为增益控制，是注意、唤醒和感觉适应的核心机制。

## 当前理解

我们现在认为，皮层的增益控制是神经调质系统（特别是 ACh 和 NE）的核心功能，也存在于局部皮层网络的规范化机制中。

**增益控制的两种形式**：
- **响应增益（Response gain）**：输入-输出曲线的斜率改变；在高对比度时效果最大。ACh 在 V1 中主要以此方式工作（Herrero et al., 2017, PMID:29311843）
- **对比度增益（Contrast gain）**：输入-输出曲线水平移动（等效于改变对输入的"敏感性"）；注意效应有时表现为对比度增益

**增益控制的实现层次**：
1. **分子层**：神经调质（ACh via M1，NE via α2A/α1）改变单个神经元的输入-输出关系
2. **突触层**：突触前调节（nAChR 增强 TC 输入）改变突触权重
3. **回路层**：规范化抑制（E/I 平衡，PV+ 中间神经元的快速前馈抑制）实现除法归一化
4. **系统层**：调质系统的紧张性基线决定整个皮层区域的"工作点"

**注意效应与增益控制**：
- 将注意引向某位置 → 该位置感受野神经元增益增大
- 机制：自上而下注意信号（PFC/顶叶）→ 激活基底前脑 ACh 系统→ 皮层 M1 受体激活→ 响应增益提升
- Herrero 2008 直接证明：阻断 V1 中肌碱受体 → 注意诱导的增益增大消失

## 关键机制

**乘法性增益（Multiplicative gain）**：
- 神经元对所有输入的响应乘以一个大于 1 的系数
- 数学表示：R_attended = gain × R_unattended
- 实现机制：M1 受体减少 K⁺ 漏电流 → 细胞膜更接近阈值 → 所有输入产生更多输出

**信噪比改善（SNR enhancement）**：
- "信号"（任务相关输入）增益提升更多
- "噪声"（自发放电）不成比例增加或甚至降低
- 净效果：神经元对任务相关信息的"敏感性"提升

**除法归一化（Divisive normalization）**：
- 每个神经元的响应除以邻域神经元的集体活动（实现相互竞争）
- 由 PV+ 中间神经元（GABA 前馈抑制）实现
- 保持神经元的动态范围，防止饱和

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| ACh 通过响应增益模型改善 V1 对比度灵敏度 | 受体阻断 + 对比度曲线 | Herrero 2017, PMID:29311843 | 高 |
| 肌碱受体阻断消除 V1 注意诱导的增益提升 | 电泳注射 scopolamine + 注意任务 | Herrero 2008, PMID:18633352 | 高 |
| NE 和 ACh 均增强多感觉皮层信噪比 | 综述 | Edeline 2012, PMID:22866031 | 高 |

## 连接

- [[acetylcholine-cortex]] — ACh 通过 M1 受体实现皮层增益提升
- [[norepinephrine-locus-coeruleus]] — NE 通过 α2A/α1 受体实现皮层增益控制（倒U曲线）
- [[neuromodulator-systems]] — 增益控制是调质系统的核心输出
- [[orientation-selectivity]] — V1 方向选择性的增益调制（Herrero 2008 实验背景）
- [[working-memory]] — α2A 受体稳定 PFC WM 表征（认知层面的增益控制）
- [[v1-primary-visual-cortex]] — 增益控制在 V1 感觉编码中的作用

## 修订历史

- 2026-06-12 · 创建 · 基于《注意的化学语言》一文 · 初始置信度：高

## 来源文章

- [[2026-06-12-neuromodulators-ach-ne]]

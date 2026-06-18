---
title: 皮层增益控制
slug: gain-control
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-12
updated: 2026-07-15
revision_count: 4
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, cognition]
related: [acetylcholine-cortex, norepinephrine-locus-coeruleus, neuromodulator-systems, orientation-selectivity, working-memory, v1-primary-visual-cortex, multi-timescale-plasticity, short-term-synaptic-plasticity, dopamine-reward-prediction-error, serotonin-raphe-system, 5-ht-autoreceptor]
prerequisites: [synaptic-transmission, action-potential]
opens_questions: [Q-gain-timescale-interaction]
source_articles: [2026-06-12-neuromodulators-ach-ne, 2026-05-30-week3-synthesis, 2026-06-13-serotonin-autoreceptor-ssri-delay, 2026-07-15-brain-attention-transformer-qkv]
key_sources: ["PMID:18633352", "PMID:16254995", "PMID:22866031", "PMID:23040802", "PMID:29470969", "PMID:19186161"]
---

# 皮层增益控制 (Cortical Gain Control)

> **一句话定义**：皮层神经元对输入的响应幅度可以被独立于输入本身的机制调节——这种对"输入-输出函数"的乘法性或加法性缩放称为增益控制，是注意、唤醒和感觉适应的核心机制。

## 当前理解

我们现在认为，皮层的增益控制是神经调质系统（特别是 ACh 和 NE）的核心功能，也存在于局部皮层网络的规范化机制中。

**第三周综合（2026-05-30 更新）**：增益控制不是单一机制，而是**多层嵌套架构**的一部分。皮层增益控制（ACh/NE，秒–分钟时间尺度）是三层架构中的**第二层**，由更快的短时程突触可塑性（STP，毫秒–秒，第一层）和更慢的多巴胺奖励信号（分钟–小时，第三层）共同包裹。理解皮层增益控制需要同时理解它在多时间尺度架构中的位置。Eve Marder（2012，PMID:23040802）的核心原则概括了这一整体视角：解剖连接体只提供骨架，神经调质环境决定在该骨架上运行的功能回路。详见 [[multi-timescale-plasticity]]。

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

**5-HT系统的超慢负反馈增益控制（2026-06-13新增）**：
5-HT的自受体脱敏机制代表了增益控制的一种独特形式——不是像ACh/NE那样通过受体激活立即调整增益，而是通过**负反馈的慢速脱敏**在2-4周时间尺度上实现情绪调节系统的增益稳态。这是三层多时间尺度增益控制架构之外的第四层（情绪/可塑性时间尺度，天-周级）。

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

**Reynolds & Heeger（2009）规范化注意力模型（PMID:19186161, PMCID:PMC2752446，开放全文）**：
将除法归一化与注意力场（attention field）整合为统一公式：

$$R = \frac{(A \cdot S)^n}{\sigma^n + \left(\sum_i w_i A_i S_i\right)^n}$$

其中 $A$ 为注意力场，$S$ 为刺激驱动，$\sigma$ 为半饱和常数，$\sum w_i A_i S_i$ 为归一化池（含竞争刺激的加权响应）。

关键预测（均获实验支持）：
- 注意场**窄于**刺激 → 对比度增益（Contrast gain）：曲线水平左移，等效于提高对比度敏感性
- 注意场**宽于**刺激 → 响应增益（Response gain）：曲线幅度整体放大，等效于乘法增益
- 该模型统一了 Treue 的特征相似度增益原理与 Reynolds 的对比度增益控制

**与 Transformer softmax 的区别**：
除法归一化与 softmax 归一化有本质差异：softmax 使所有权重之和恒为 1（全局指数归一化），而除法归一化的分母是邻域响应的加权和（局部竞争池），不要求权重之和为常数，因此可根据注意场宽度产生对比度增益或响应增益两种不同模式——这是生物注意力比 Transformer softmax 更丰富的动力学表现之一。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| ACh 通过响应增益模型改善 V1 对比度灵敏度 | 受体阻断 + 对比度曲线 | Herrero 2017, PMID:29311843 | 高 |
| 肌碱受体阻断消除 V1 注意诱导的增益提升 | 电泳注射 scopolamine + 注意任务 | Herrero 2008, PMID:18633352 | 高 |
| NE 和 ACh 均增强多感觉皮层信噪比 | 综述 | Edeline 2012, PMID:22866031 | 高 |
| 注意场宽度决定产生对比度增益还是响应增益 | 规范化模型数学推导 + 电生理数据拟合 | Reynolds & Heeger 2009, PMID:19186161 | 高（模型预测与数据一致）|

## 连接

- [[acetylcholine-cortex]] — ACh 通过 M1 受体实现皮层增益提升
- [[norepinephrine-locus-coeruleus]] — NE 通过 α2A/α1 受体实现皮层增益控制（倒U曲线）
- [[neuromodulator-systems]] — 增益控制是调质系统的核心输出
- [[orientation-selectivity]] — V1 方向选择性的增益调制（Herrero 2008 实验背景）
- [[working-memory]] — α2A 受体稳定 PFC WM 表征（认知层面的增益控制）
- [[v1-primary-visual-cortex]] — 增益控制在 V1 感觉编码中的作用
- [[multi-timescale-plasticity]] — 皮层增益控制作为三层增益架构的第二层
- [[short-term-synaptic-plasticity]] — 第一层增益控制（毫秒级），与皮层增益控制互补
- [[dopamine-reward-prediction-error]] — 第三层增益控制（价值驱动学习），与皮层增益控制协同
- [[serotonin-raphe-system]] — 5-HT系统的超慢负反馈增益控制（天-周级，情绪基调）
- [[5-ht-autoreceptor]] — 自受体脱敏机制：5-HT增益的慢速稳态调节

## 修订历史

- 2026-06-12 · 创建 · 基于《注意的化学语言》一文 · 初始置信度：高
- 2026-05-30 · 修订 · 基于《第三周综合》 · 将皮层增益控制定位为多层增益控制架构（[[multi-timescale-plasticity]]）的第二层；新增 Marder 原则（PMID:23040802）和 Thiele & Bellgrove 2018（PMID:29470969）作为理论支撑；更新 related 和 key_sources
- 2026-06-13 · 修订 · 基于《血清素的慢时钟》 · 新增5-HT自受体脱敏机制作为增益控制的第四个时间尺度（天-周，情绪/可塑性）；补全[[serotonin-raphe-system]]和[[5-ht-autoreceptor]]连接
- 2026-07-15 · 修订 · 基于《同一个算法，两种实现》一文 · 新增 Reynolds & Heeger 2009 规范化注意力模型（PMID:19186161，开放全文）；说明除法归一化与 Transformer softmax 的关键差异（注意场宽度 → 对比度增益 vs 响应增益 vs softmax 无此区分）；key_sources 新增 PMID:19186161

## 来源文章

- [[2026-06-12-neuromodulators-ach-ne]]
- [[2026-05-30-week3-synthesis]]
- [[2026-06-13-serotonin-autoreceptor-ssri-delay]]

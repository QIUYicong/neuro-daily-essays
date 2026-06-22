---
title: 除法规范化
slug: divisive-normalization
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-02
updated: 2026-09-02
revision_count: 1
dimensions: [synaptic, cellular, microcircuit, brain-region, cognition]
related: [gain-control, v1-primary-visual-cortex, orientation-selectivity, precision-weighting, competition-selection-principle, biased-competition, attention-normalization, ltp, pv-interneurons, sst-interneurons, transformer-self-attention, thalamus, global-workspace-theory]
prerequisites: [synaptic-transmission, action-potential, gain-control]
opens_questions: [Q-dn-01, Q-dn-02, Q-dn-03]
source_articles: [2026-09-02-divisive-normalization-canonical-computation]
key_sources: ["PMID:22108672", "PMC3273486", "PMID:19186161", "PMC2752446", "PMID:28835531", "PMC5814712", "PMID:1504027", "PMID:36161961", "PMID:38754373"]
---

# 除法规范化 (Divisive Normalization)

> **一句话定义**：除法规范化是一种神经计算原则——神经元的响应幅度被其邻域神经元集体活动的加权和除，从而实现对比度归一化、赢者聚焦竞争和动态范围最大化；它作为"规范计算"在 V1、注意系统、决策回路乃至丘脑中普遍存在，是大脑皮层非线性信息处理的统一框架。

## 当前理解

除法规范化（Divisive Normalization，DN）最初由 Heeger（1992）提出，用于解释猫纹状皮层神经元的对比度响应饱和现象。Carandini & Heeger（2012，Nature Reviews Neuroscience）的系统综述将其上升为"规范计算"——一种在不同脑区、不同物种、不同感觉模态中反复出现的统一计算原型。

**标准规范化方程**：

$$R_j = \frac{\gamma D_j^n}{\sigma^n + \sum_k D_k^n}$$

其中：
- $R_j$：目标神经元 j 的响应幅度
- $D_j$：驱动 j 的输入强度（对比度、刺激强度等）
- $\sum_k D_k^n$：抑制性池（suppressive pool）中所有竞争神经元活动的加权和
- $\sigma$：半饱和常数（semi-saturation constant），越大则神经元对低强度输入越线性
- $n$：幂次系数，通常约为 2
- $\gamma$：最大增益系数

**规范化的四个计算功能**（Carandini & Heeger 2012）：
1. **最大化动态范围**：将输入编码范围扩展到感觉输入的整个强度谱
2. **对比度不变性**：神经元调谐（方向、频率）宽度不随对比度变化
3. **赢者聚焦竞争**：高强度刺激主导分母，压制低强度竞争刺激
4. **降低统计冗余**：当自然图像服从多变量 Pareto 分布时，规范化是信息论最优编码（Bucher & Brandenburger 2022）

## 关键机制

### V1 中的三种经典非线性现象

除法规范化统一解释了初级视觉皮层（V1）中三种原本被视为独立现象的非线性响应：

**1. 对比度饱和（Contrast Saturation）**
- 现象：V1 神经元对增加的对比度响应从线性增长转为饱和的 S 型曲线
- 规范化解释：当分子 $D_j^n$ 增大时，分母 $\sigma^n + \sum_k D_k^n$ 也随之增大（含自身贡献），导致比值趋近平台
- 半饱和常数 $\sigma$ 决定饱和转折点的对比度阈值

**2. 交叉朝向抑制（Cross-Orientation Suppression）**
- 现象：与目标方向正交的"掩蔽刺激"可显著降低目标神经元的响应，即使目标神经元对该掩蔽方向不调谐
- 规范化解释：掩蔽刺激驱动的神经元贡献到抑制性池 $\sum_k D_k^n$，增加分母而不改变分子，净效果是响应下降
- 这是规范化模型对"不调谐的刺激也能产生抑制"的核心预测，与经典侧抑制模型（仅调谐方向之间相互抑制）的关键区别

**3. 环绕抑制（Surround Suppression）**
- 现象：感受野外的刺激抑制中心区域神经元的响应（对应自然图像中均匀背景被"解释掉"的现象）
- 规范化解释：经典感受野外的神经元也加入抑制性池，实现空间尺度的规范化
- 与预测编码视角互补：均匀背景被高级区域预测覆盖 → 误差较小；孤立边缘违反预测 → 误差较大（两种框架不互斥）

### 注意力与规范化：Reynolds & Heeger 2009

Reynolds & Heeger（2009，Neuron）将注意力形式化为规范化框架的扩展：

$$R = \frac{(A \cdot E)^n}{\sigma^n + \left(\sum_i w_i A_i E_i\right)^n}$$

其中 $A$ 为注意力场（attention field），$E$ 为刺激驱动。**关键洞察**：注意力场的空间宽度与刺激大小的相对关系，决定产生哪种注意效果：

| 注意力场（A）与刺激关系 | 预测效应 | 实验条件 |
|------------------------|---------|---------|
| 注意场**窄于**刺激 | 对比度增益（曲线左移，敏感性↑） | 单个小刺激+宽注意场 |
| 注意场**宽于**刺激 | 响应增益（曲线整体放大，幅度↑） | 大刺激+窄注意场 |

这统一了 McAdams & Maunsell（1999）和 Williford & Maunsell（2006）的矛盾结果——两者对增益效果的不同观察，实际上反映了相同机制在不同实验参数下的不同表现。

### 决策与价值规范化

在顶叶内沟（LIP）的决策神经元中，类似规范化机制调节多选项竞争的价值信号：

$$R_{选项A} = \frac{V_A^n}{\sigma^n + V_A^n + V_B^n + \ldots}$$

这一机制实现了"相对价值比较"而非绝对价值编码，是大脑高效决策的神经计算基础。当选项 B 的价值升高，即使选项 A 的绝对价值不变，选项 A 的神经响应也会下降——与行为经济学中的"语境效应"（preference reversal）直接对应。

### 丘脑网状核的全脑规范化路由

Whyte 等（2024，Neuron）提出丘脑网状核（TRN）通过对多个丘脑中继核的**侧向抑制**，实现类似除法规范化的全脑信息路由：TRN 对各丘脑核的抑制竞争，功能上等价于在全脑尺度选择哪些感觉通道获得皮层接入。这一机制支持意识整合（多模感觉汇聚）、分离（注意聚焦时抑制竞争通道）和连续性三个功能。

## 回路实现

目前尚无统一的"规范化专用回路"，不同脑区的实现机制有所不同：

**三种候选回路机制**：

1. **分流性抑制（Shunting Inhibition）**
   - 由 PV+ 篮状细胞介导的氯离子电导（GABA-A）
   - 增大树突膜电导（"短路"），等效于除法操作而非减法
   - 果蝇嗅觉球：GABA 能局部神经元（LN）提供最强的因果实验证据（Nagel & Wilson 2011）
   - 但在哺乳动物 V1 中，GABA-A 阻断**并不消除**规范化（反证！），提示 V1 存在其他机制

2. **递归抑制（Recurrent Inhibition）**
   - 局部兴奋性神经元激活抑制性中间神经元，再反馈抑制兴奋性神经元
   - 形成闭环竞争动态，在高强度刺激时自动放大抑制力度
   - 对应数学上的非线性除法效果

3. **突触抑制（Synaptic Depression）**
   - 突触前神经递质耗竭导致的高频适应（短时程抑制）
   - 为实现规范化提供了不依赖抑制性中间神经元的替代机制

**V1 中 GABA-A 阻断的反证**提示：哺乳动物 V1 的规范化可能主要依赖递归抑制或突触抑制，而非简单的分流性抑制——这是领域内最重要的开放机制问题之一。

## 规范化的规范性依据

Bucher & Brandenburger（2022，PNAS）从信息论角度证明：当自然环境的多变量输入服从**Pareto 分布**（重尾，幂律）时，除法规范化是最大化互信息（最优编码）的唯一策略。

Pareto 分布的关键性质：信息论最优的编码对每个通道的响应概率进行均匀化（histogram equalization），而 Pareto 分布下的最优均匀化变换恰好具有规范化的数学形式。

这为规范化的"为什么"（进化压力/功能意义）提供了严格的数学依据，但前提是自然环境输入确实服从 Pareto 分布。

## 与人工智能的比较

| 神经规范化 | AI 等价操作 | 主要差异 |
|-----------|-----------|---------|
| 除法规范化（分母=邻域池加权和） | BatchNorm、LayerNorm | AI 版本使用统计矩（均值/方差），而非竞争神经元活动 |
| Reynolds & Heeger 注意场规范化 | Transformer Softmax 注意力 | Softmax 权重之和恒为 1；规范化的注意场宽度产生两种不同增益模式，Softmax 不支持此分化 |
| 赢者聚焦效应（高强度压制低强度） | Winner-Take-All / Softmax 极限 | 生物规范化是"软性"的，结果可调；WTA 是极端情形 |

神经规范化与 Softmax 的**根本差异**：Softmax 将所有注意力权重归一为概率分布，缺失"注意场宽度 × 刺激大小"的相互作用；而规范化框架中，这一相互作用决定产生对比度增益还是响应增益，反映了生物注意系统对实验条件更丰富的适应性。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 规范化方程统一解释 V1 对比度饱和/交叉朝向抑制/环绕抑制 | 系统性与 30+ 数据集对比拟合（Sawada & Petrov 2017） | PMID:28835531 | 高 |
| 注意场宽度决定对比度增益 vs 响应增益 | 数学推导 + 与已有电生理数据拟合 | PMID:19186161 | 高（理论+拟合，缺新体内验证） |
| 果蝇嗅觉球 GABA-LN 介导规范化 | LN 激活/抑制光遗传操控 | Nagel & Wilson 2011 | 高（直接因果证据） |
| GABA-A 阻断不消除哺乳动物 V1 规范化 | V1 GABA-A 受体拮抗剂（局部注射）+ 电生理 | 多项研究综述（PMID:22108672） | 高（直接反证） |
| Pareto 分布下规范化是信息论最优编码 | 数学定理（Shannon 互信息最大化推导） | PMID:36161961 | 高（数学证明），依赖 Pareto 假设 |

## 连接

- [[gain-control]] — 皮层增益控制的回路层面实现（PV+ 前馈抑制实现除法归一化）；本页是 gain-control 中"除法归一化"子节的专属深化页面
- [[v1-primary-visual-cortex]] — V1 是规范化实验验证最充分的脑区；三种经典非线性现象的证据来源
- [[orientation-selectivity]] — V1 方向选择性的背景——规范化保持方向调谐宽度随对比度不变
- [[precision-weighting]] — 精度加权在计算层面与规范化对应：注意力场乘以感觉精度在规范化之前（Reynolds & Heeger 公式的精度编码解读）
- [[competition-selection-principle]] — 嵌套竞争遴选架构：规范化是回路级竞争的精确数学定量化
- [[biased-competition]] — 偏置竞争模型的计算实现：注意信号通过修改注意力场 A 实现对规范化竞争的偏置
- [[pv-interneurons]] — PV+ 篮状细胞提供快速 GABA-A 前馈抑制，是分流性抑制候选
- [[sst-interneurons]] — SST+ 细胞通过树突区室抑制为规范化提供树突级实现
- [[transformer-self-attention]] — Transformer Softmax 注意力与规范化的数学对比（差异大于相似）
- [[thalamus]] — TRN 侧向抑制为全脑信息路由提供规范化类机制
- [[global-workspace-theory]] — GWT 的点燃机制可能依赖 TRN 水平规范化竞争决定哪个工作区获胜

## 未解问题

- **Q-dn-01（高优先级）**：哺乳动物 V1 的规范化主要由哪种机制实现？为何 GABA-A 阻断不消除规范化？是递归抑制还是突触抑制主导？在体光遗传学解离实验能否直接区分？
- **Q-dn-02（中优先级）**：规范化的抑制性池（suppressive pool）的确切范围是什么？是所有对同一感受野有响应的神经元，还是存在特定的池选择规则（方向、空间频率的特异性）？不同脑区中池的组成是否有统一规律？
- **Q-dn-03（中优先级）**：Reynolds & Heeger 注意力规范化模型缺乏新的独立体内验证。具体预测（注意场宽度调节下的双相增益效应）能否用高密度皮层电极或双光子成像直接测量注意场宽度并验证？

## 修订历史

- 2026-09-02 · 创建 rev1 · 基于《除法规范化：大脑皮层的规范计算》（#132） · 初始置信度：高（Carandini & Heeger 系统综述 + Sawada & Petrov 系统验证 + Bucher & Brandenburger 数学证明）

## 来源文章

- [[2026-09-02-divisive-normalization-canonical-computation]]

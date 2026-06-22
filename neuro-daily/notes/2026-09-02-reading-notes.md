# 2026-09-02 阅读笔记：除法规范化

**主题**：除法规范化（Divisive Normalization）作为典范神经计算
**对应文章**：2026-09-02-divisive-normalization-canonical-computation.md（#132）

---

## 来源 1：Carandini & Heeger 2011（主要综述）
**PMID**：22108672，PMC：PMC3273486（开放全文）
**题目**：Normalization as a canonical neural computation
**期刊**：Nature Reviews Neuroscience

**要解决的问题**：V1 中的多种非线性现象（对比度饱和、交叉朝向抑制、环绕抑制）是否有统一机制？这一机制是否在其他脑区也存在？

**方法**：综述 + 数学分析，整合多个脑区和物种的数据

**关键发现**：
- 规范化方程 R_j = γD_j^n / (σ^n + ΣD_k^n) 可统一解释 V1 多种非线性
- 规范化在感觉皮层（视觉/听觉/嗅觉）、决策（LIP）和多感觉整合（MST）中都有证据
- 果蝇嗅觉球中 GABA 能中间神经元是因果证据最强的实现机制，但哺乳动物 V1 中 GABA-A 阻断不消除规范化
- 规范化解决的计算问题：最大化动态范围、提供不变性、实现赢者全得竞争、降低统计冗余

**改变了什么理解**：从"多个独立现象"到"单一规范计算"的框架转变

**证据强度**：高（系统综述，多物种多脑区），但因果机制部分仍为推测

**局限**：规范化方程参数灵活，可能存在过度拟合风险；不同脑区机制差异大

---

## 来源 2：Heeger 1992（原始论文）
**PMID**：1504027（非开放全文，仅摘要）
**题目**：Normalization of cell responses in cat striate cortex
**期刊**：Vis Neurosci

**关键发现**：
- 提出规范化模型作为 V1 神经元非线性响应的统一解释
- 神经元相互抑制，有效归一化对比度响应
- 对对比度饱和和交叉朝向抑制有良好预测

**证据强度**：高（原始实验数据），但机制部分基于旁路抑制假说（后来部分被质疑）

---

## 来源 3：Reynolds & Heeger 2009（注意力规范化）
**PMID**：19186161，PMC：PMC2752446（开放全文）
**题目**：The normalization model of attention
**期刊**：Neuron

**要解决的问题**：注意力产生对比度增益还是响应增益？实验室间的矛盾如何解决？

**方法**：扩展规范化方程，加入注意力场 A(x,θ)；数学推导不同实验条件下的预测；与已有实验数据对比

**关键发现**：
- 注意力场乘以刺激驱动在规范化之前（ A·E/（σ + A·S） ）
- 小刺激+宽注意力场 → 对比度增益（曲线左移）
- 大刺激+窄注意力场 → 响应增益（曲线上移）
- 统一解释了 McAdams 1999 和 Williford & Maunsell 2006 的矛盾结果

**改变了什么理解**：注意力"对比度增益 vs 响应增益"的争论不是理论错误，而是不同实验参数条件下同一机制的不同表现

**证据强度**：中-高（理论推导 + 与已有数据拟合），缺乏新的独立体内验证

---

## 来源 4：Sawada & Petrov 2017（系统验证）
**PMID**：28835531，PMC：PMC5814712（开放全文）
**题目**：The divisive normalization model of V1 neurons: a comprehensive comparison of physiological data and model predictions
**期刊**：J Neurophysiol

**关键发现**：
- 系统测试规范化模型对 30 余个 V1 实验数据集的预测能力
- 以统一参数集成功复现多种 V1 响应特性
- 模型参数具有一定的个体神经元依赖性，但跨刺激条件下可设定约束

**证据强度**：高（系统性验证）

---

## 来源 5：Whyte et al. 2024（丘脑与意识）
**PMID**：38754373，PMC：PMC11537458（开放全文）
**题目**：Thalamic contributions to the state and contents of consciousness
**期刊**：Neuron

**关键发现**：
- 丘脑网状核（TRN）通过对多个丘脑中继核的侧向抑制，实现类似除法规范化的全脑信息路由
- TRN 机制支持意识整合、分离和连续性三个功能

**证据强度**：低-中（综述性推断为主，TRN 的规范化功能有部分实验支持，但意识联系是理论推断）

**注意**：这部分内容只读了摘要，核心论点是综述性假说而非新实验数据

---

## 来源 6：Bucher & Brandenburger 2022
**PMID**：36161961（开放全文）
**题目**：Divisive normalization is an efficient code for multivariate Pareto-distributed environments
**期刊**：PNAS

**关键发现**：
- 从信息论角度证明，当环境输入服从多变量 Pareto 分布时，除法规范化是最优编码策略
- 为规范化的"为什么"提供了规范性（normative）解释

**证据强度**：高（数学定理），但需要"自然环境服从 Pareto 分布"这一假设

---

## 来源 7：Noel & Angelaki 2023
**PMID**：37183143（开放全文）
**题目**：A theory of autism bridging across levels of description
**期刊**：Trends Cog Sci

**关键发现**：
- 提出 ASD 可能是情境适应性规范化精度（meta-precision）失调，而非简单的"超精确先验"
- 主动推断模型参数拟合显示 ASD 在动态不确定性条件下学习率适应不足

**证据强度**：中（初步数据，样本量限制，需跨实验室复现）

**注意**：该来源仅读取摘要

---

## 术语解释

- **抑制性池（suppressive pool）**：规范化方程分母中包含的神经元群体，这些神经元的活动会降低目标神经元的响应
- **半饱和常数（semi-saturation constant, σ）**：规范化方程中使响应进入饱和的对比度阈值；σ 越大，神经元对低对比度越线性，高对比度才饱和
- **对比度增益（contrast gain）**：注意力效果体现为响应曲线向左移，等效于提高对比度敏感性
- **响应增益（response gain）**：注意力效果体现为响应曲线整体上移，等效于乘法放大
- **赢者全得效应（winner-take-all）**：当一个高强度刺激主导分母时，低强度竞争刺激的响应被压缩至接近零

---

## 矛盾检查

今日文章无新增矛盾（与既有 wiki 一致，GABA-A 阻断反证在 gain-control 页面已有引用，未引入新冲突）。

需注意：`gain-control.md`（rev4）中已有 Reynolds & Heeger 2009 的相关内容，今日文章对规范化的深度阐述与该页面一致，但未冲突。

---
title: 平衡传播
slug: equilibrium-propagation
domain: concepts
type: mechanism
status: emerging
confidence: medium
created: 2026-09-04
updated: 2026-09-04
revision_count: 1
dimensions: [synaptic, cellular, theory, methods]
related: [hopfield-network, contrastive-hebbian-learning, pc-learning, credit-assignment, cortical-slow-oscillation, stdp, hebbian-learning, free-energy-principle, three-factor-learning-rule]
prerequisites: [hopfield-network, hebbian-learning, ltp, energy-based-models]
opens_questions: [Q-ep-01, Q-ep-02]
source_articles: [2026-09-04-equilibrium-propagation-cortical-two-phase-learning]
key_sources: ["PMID:28522969", "PMID:40038254", "PMID:30704969"]
---

# 平衡传播 (Equilibrium Propagation, EP)

> **一句话定义**：由 Scellier & Bengio (2017) 提出的学习框架：在能量极小化神经网络中，代价函数梯度等于"自由弛豫极小值"与"弱锁定弛豫极小值"两个稳态活动乘积之差除以锁定强度的极限——这使局部突触活动差能精确计算全局梯度，而无需任何全局误差信号。

## 当前理解

我们现在认为，平衡传播（EP）是继预测编码学习（PC-Learning）之后，另一种理论上严谨的"无全局误差信号梯度近似"学习框架，其根植于物理能量景观语言，而非层级误差传播。

**核心结构**：

网络能量函数为：$\Phi(\mathbf{s}; \beta) = \Phi_0(\mathbf{s}) + \beta C(\mathbf{s}_{\text{out}}, y)$

- **自由相**（$\beta = 0$）：输入 $x$ 固定，网络自由弛豫到能量极小值 $\mathbf{s}^0$；
- **弱锁定相**（$\beta > 0$）：代价项轻推输出单元，网络弛豫到新极小值 $\mathbf{s}^\beta$；
- **权重更新**：$\Delta W_{ij} \propto \frac{1}{\beta}(s_i^\beta s_j^\beta - s_i^0 s_j^0)$

**核心定理（Scellier & Bengio 2017，定理 1）**：

$$\frac{\partial C}{\partial W_{ij}} = \lim_{\beta \to 0} \frac{1}{\beta}\left(\frac{\partial \Phi}{\partial W_{ij}}\bigg|_{\mathbf{s}^\beta} - \frac{\partial \Phi}{\partial W_{ij}}\bigg|_{\mathbf{s}^0}\right)$$

**结论**：局部两相活动差 → 精确全局梯度。这是一个数学定理，不是近似。

**与 PC-Learning 的关键区别**：

| 维度 | PC-Learning | 平衡传播 (EP) |
|------|-------------|--------------|
| 信息结构 | 层级预测误差前向传播 | 能量相变两稳态比较 |
| 神经元特化 | 误差单元 vs 表征单元 | 无特化（所有单元参与推断）|
| 时间相位 | 无需相位切换 | 自由相 + 弱锁定相 |
| 与 STDP 的关系 | 通过局部 Hebbian 规则实现 | 积分后直接等价 STDP |
| 生物底层候选 | 皮层 L2/3 误差流 + L5 表征流 | 皮层慢振荡 UP/DOWN 态（假说）|

**STDP 等价性**（EP 最重要的生物学性质）：

将权重更新写为时间连续形式：

$$\frac{d W_{ij}}{dt} \propto \rho(u_i) \cdot \frac{d\rho(u_j)}{dt}$$

这与 STDP 形式高度一致——突触强化取决于突触前当前活动乘以突触后活动的变化率。Scellier & Bengio（2017）证明，对此式沿弛豫路径时间积分，得到 EP 的权重更新规则。

## 关键机制

### 能量极小化作为推断

EP 的推断过程是物理上的能量最小化——与弹簧弛豫、温度平衡等完全类似。神经元"滚入"能量谷底，代表对当前输入的最佳解释。这是贝叶斯推断的物理实现：能量极小值 = 后验分布的最高概率点。

### 两相结构的逻辑

自由相告诉突触"网络现在认为答案是什么"，锁定相告诉突触"正确答案下应该是什么"。两者之差是误差方向——但这个差**不需要额外的误差计算电路**，直接体现在活动乘积的差值中。

### 解决两相协调问题：隐式非平衡记忆（2025）

Altun et al.（2025，PMID:40038254，PMC11880436）证明，当每个突触学习自由度包含**积分反馈**时，显式全局相位信号不再必需：
- 记忆核对快速状态变化（相切换时）强烈响应
- 对慢速稳态变化抑制响应
- 突触自动计算相变前后状态差

这种"隐式非平衡记忆"机制类似于 CaMKII 磷酸化动力学、突触标记与捕获（STC）的时间积分特性。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| EP 权重更新 = 精确代价梯度（$\beta \to 0$ 极限） | 数学推导（定理 1）+ MNIST 验证（训练误差 0.00%）| PMID:28522969 / PMC5415673 🔓 | 高（数学定理）|
| EP 权重规则积分后 = STDP | 时间连续版本推导 | PMID:28522969 / PMC5415673 🔓 | 高（理论推导）|
| 积分反馈可绕过显式两相信号 | 理论推导 + 多物理底物仿真 | PMID:40038254 / PMC11880436 🔓 | 中（理论严谨；神经实现待验证）|
| CHL 近似等价于反向传播梯度 | 数学分析（综述）| PMID:30704969 / PMC6382460 🔓 | 高（多方验证的理论结论）|
| 皮层 UP/DOWN 态可能对应 EP 两相 | 类比推断；UP 态 ~500 ms（推断），DOWN 态+SWR（软目标锁定）| PMID:29213231 / PMC5703076 🔓 | 低（假说；无直接实验验证）|

## 连接

- [[hopfield-network]] — EP 扩展了连续 Hopfield 网络，用代价函数补充其能量
- [[contrastive-hebbian-learning]] — EP 是 CHL 的理论精确化；CHL 是 EP 的离散/早期版本
- [[credit-assignment]] — EP 是空间信用分配的能量极小化路径（与 PC-Learning 并列）
- [[pc-learning]] — 同为无全局误差信号的梯度近似；EP 用能量语言，PCL 用误差语言
- [[cortical-slow-oscillation]] — UP/DOWN 态切换是 EP 两相结构的生物候选（假说）
- [[stdp]] — EP 权重规则积分后等价 STDP；生物可行性的关键支撑
- [[free-energy-principle]] — EP 的变分版本（无监督）与 FEP 框架数学上同源
- [[three-factor-learning-rule]] — 三因素规则是时间维度信用分配；EP 是空间维度的能量路径

## 未解问题

- **Q-ep-01**：皮层 UP 态约 500 ms 的时长是否足以让 EP 类弛豫在两相内完成收敛？EP 的收敛速度取决于网络规模和能量景观的凸性——目前缺乏针对皮层规模网络的定量研究。
- **Q-ep-02**：EP 的"锁定目标"在无监督皮层学习中由谁提供？海马 SWR 重播是否构成足够的"弱目标锁定"，或者说皮层的预测误差本身是否可以充当内生目标？

## 修订历史

- 2026-09-04 · 创建 · 基于《大脑的"能量景观学习"》(#135) · 初始置信度：中（算法理论严谨；皮层 UP/DOWN 态实现是假说）

## 来源文章

- [[2026-09-04-equilibrium-propagation-cortical-two-phase-learning]]

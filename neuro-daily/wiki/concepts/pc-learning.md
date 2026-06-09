---
title: 预测编码学习
slug: pc-learning
domain: concepts
type: mechanism
status: emerging
confidence: medium
created: 2026-09-03
updated: 2026-09-03
revision_count: 1
dimensions: [synaptic, cellular, microcircuit, cognition, methods]
related: [predictive-coding, hebbian-learning, three-factor-learning-rule, backpropagating-action-potential, canonical-microcircuit, active-inference, free-energy-principle, credit-assignment, eligibility-trace, cortical-layers]
prerequisites: [predictive-coding, hebbian-learning, ltp, nmda-receptor]
opens_questions: [Q-fep-02]
source_articles: [2026-09-03-pc-learning-biological-backpropagation]
key_sources: ["PMID:28333583", "PMID:41996333", "PMID:37818157"]
---

# 预测编码学习 (PC-Learning)

> **一句话定义**：在预测编码框架内，用简单局部 Hebbian 突触可塑性实现的学习算法——在推断收敛极限，其权重更新数学上等价于反向传播（backpropagation）的梯度，从而在不需要全局误差广播的条件下实现了与梯度下降等价的学习效果。

## 当前理解

我们现在认为，PC-Learning 是目前最有望弥合"生物学习规则（局部 Hebbian）"与"深度学习的优化能力（梯度下降）"之间鸿沟的计算框架。

核心证明（Whittington & Bogacz 2017，PMID:28333583）：在以下条件下，预测编码网络的权重更新等价于精确的反向传播梯度：
- 网络通过迭代推断达到"推断平衡"（inference equilibrium）
- 精度参数 Σ → ∞（系统对感觉输入具有极高确信度）

在此极限，每个突触的权重更新仅依赖于其突触前表征神经元的活动和突触后侧误差神经元的活动——这是纯局部规则，不需要全局误差信号。但功能上，通过层级预测误差的前馈传播，全局信用以局部误差的形式自然涌现。

皮层实现（Max et al. 2026，PMID:41996333）：
- **误差神经元**（L2/3 锥体细胞）→ 误差流（前馈，γ 频段）
- **表征神经元**（L5 锥体细胞）→ 表征流（反馈，α/β 频段）
- 两流对向传播，无需时间相位切换

## 关键机制

### 网络架构

```
高级区域表征单元（L5）
        │  
        ├─── [反馈预测] ──→ 低级区域 L1/L6（接触误差单元顶树突）
        │
        ↑
高级区域误差单元（L2/3）
        ↑
[误差 = 实际输入 - 预测] 在低级区域 L2/3 局部计算
        ↑
低级区域感觉输入（来自 L4 + 高级区域反馈）
```

### 权重更新规则

$$\Delta w_{ij}^{(l)} \propto \varepsilon_i^{(l-1)} \cdot f(x_j^{(l)})$$

- $\varepsilon_i^{(l-1)}$：第 l-1 层（当前层的下一层）误差神经元的活动
- $f(x_j^{(l)})$：当前层表征神经元的激活

这是局部规则：突触 ij 只需知道自己的突触前活动（表征单元输出）和突触后侧的局部误差信号。

**等价性条件**：当推断完全收敛（ε → 0），上述局部更新 = 精确的反向传播梯度（数学证明见 Whittington & Bogacz 2017）。

### 与反向传播的关系

| 特性 | 反向传播 | PC-Learning |
|------|---------|------------|
| 误差传播方向 | 反向（输出→输入） | 前向（下→上，随前馈流）|
| 是否需要时间相位 | 需要（前向+后向） | 不需要（phase-free，Max 2026）|
| 权重对称性 | 需要前后向权重对称 | 不需要（各层局部规则）|
| 误差精确性 | 精确全局梯度 | 近似（收敛时精确）|
| Dale 定律兼容 | 否 | 近似（需种群编码绕过）|

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| PC-Learning 权重更新在推断收敛极限等价于反向传播梯度 | 严格数学推导 | PMID:28333583 (PMC5467749) 🔓 | 高（数学证明）|
| L2/3 误差单元 + L5 表征单元模型在 5 个任务达到 ANN 性能 | 基于灵长类解剖约束的计算模型 + 多任务测试 | PMID:41996333 (PMC13089762) 🔓 | 中（计算模型，待体内验证）|
| 局部 Hebbian PC 网络自发涌现不变性表征和时间层级 | 4 层 PC 网络 + 视觉序列数据；与皮层时间尺度数据对比 | PMID:37818157 (PMC10561268) 🔓 | 中（计算实验，与部分生物数据一致）|
| L2/3 神经元对感觉运动失配（预测误差）有强烈选择性响应 | 清醒小鼠 V1 + VR + 双光子钙成像 | PMID:22681686（预测编码页已记录）| 高（体内，多物种验证）|

## 生物可行性的未解约束

1. **推断收敛条件**：数学等价需要推断完全收敛（ε → 0），真实皮层是连续动态的
2. **Dale 定律**：有效负权重需要种群编码实现（用兴奋性神经元激活抑制性中间神经元来产生净负效应）
3. **有符号误差编码**：生物神经元只能产生非负放电率，编码有符号误差需要差分种群
4. **误差的来源模糊性**：Rao-Ballard 经典模型（每层局部差值）vs Max 等人（显式误差投射跨区域）——两种架构的体内区分仍缺乏直接实验

## 与 FEP 的关系

PC-Learning 是自由能原理（FEP，[[free-energy-principle]]）在突触可塑性层面的具体实现路径：
- FEP 框架下，感知 = 最小化变分自由能（感知路径）
- 学习 = 调整生成模型参数以进一步降低长期预期自由能
- PC-Learning 提供了"学习"路径的局部实现机制
- 数学上，FEP ≈ VAE-ELBO 优化；PC-Learning 提供了 ELBO 优化的局部近似

## 连接

- [[predictive-coding]] — 理论框架，PC-Learning 是其学习算法层面的实现
- [[credit-assignment]] — PC-Learning 解决空间信用分配问题的具体机制
- [[hebbian-learning]] — PC-Learning 使用的基础规则，但赋予了梯度语义
- [[canonical-microcircuit]] — PC-Learning 的解剖底层：L2/3（误差）/L5（表征）分工
- [[cortical-layers]] — 六层架构为前馈误差流（L2/3，γ）和反馈表征流（L5/6，α/β）提供物理分离
- [[active-inference]] — 主动推断是 PC-Learning 在行动维度的扩展
- [[free-energy-principle]] — FEP 是 PC-Learning 的数学精确化框架
- [[backpropagating-action-potential]] — bAP 为表征神经元提供树突-胞体间的信号传递，参与 PC-Learning 的误差计算

## 未解问题

- Q-fep-02（部分回答）：PC-Learning 回答了"权重如何局部更新以等价梯度下降"；但 FEP/VAE 等价框架中的时间依赖性（非 IID 感觉流）和多目标优化（感知精度 + 模型压缩）仍需额外机制

## 修订历史

- 2026-09-03 · 创建 · 基于《大脑的反向传播幻觉》(#134) · 初始置信度：中（理论证明扎实，皮层实现仍需体内验证）

## 来源文章

- [[2026-09-03-pc-learning-biological-backpropagation]]

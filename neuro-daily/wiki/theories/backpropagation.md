---
title: 反向传播算法
slug: backpropagation
domain: theories
type: theory
status: established
confidence: high
created: 2026-06-24
updated: 2026-06-24
revision_count: 1
dimensions: [cognition, methods]
related: [credit-assignment-problem, feedback-alignment, predictive-coding, three-factor-learning-rule, cerebellar-ltd, dendritic-computation, hebbian-learning, ltp]
prerequisites: [hebbian-learning, ltp, dendritic-computation]
opens_questions: [Q-bp-01, Q-bp-02, Q-bp-03]
source_articles: [2026-06-24-credit-assignment-backprop]
key_sources: ["PMID:32303713", "PMID:27824044", "PMID:31659335"]
---

# 反向传播算法 (Backpropagation Algorithm / BP)

> **一句话定义**：通过链式法则将输出误差梯度从最后一层反向逐层传播，精确计算每个参数对误差的贡献并进行梯度下降更新的监督学习算法；是深度学习的核心基础，但在生物学上几乎不可能直接实现。

## 当前理解

我们现在认为，反向传播（BP）是人工神经网络（ANN）领域解决**信用分配问题**（credit assignment problem）的标准算法，由 Rumelhart、Hinton 和 Williams 于 1986 年系统提出。它的成功是现代 AI 的技术基础。然而，尽管大脑显然也能解决信用分配问题（人类可以学习极其复杂的技能），BP 在神经生物学上面临根本性障碍，导致大脑不可能直接使用这个算法。

BP 的运作分为四步：
1. **前向传播**：输入从第一层流向最后一层，产生输出。
2. **误差计算**：输出与期望目标比对，计算损失函数 L。
3. **反向传播**：用链式法则逐层计算 ∂L/∂w（每个参数的梯度）。
4. **参数更新**：对每个权重做梯度下降：w ← w − η·∂L/∂w。

BP 的精妙在于：梯度的计算是解析性的（无需数值近似），且可在任意深度网络上精确执行。

## 关键机制

### BP 的数学核心：链式法则

若网络有 L 层，第 l 层输出为 h^l = f(W^l · h^(l-1) + b^l)，则第 l 层的误差信号（δ^l）由下式递推：
```
δ^L = ∂L/∂h^L  (输出层误差，直接由损失函数计算)
δ^l = (W^(l+1))^T · δ^(l+1) ⊙ f'(h^l)  (反向传播)
```
第 l 层权重的梯度：∂L/∂W^l = δ^l · (h^(l-1))^T

关键：反向传播时，误差信号乘以**转置权重矩阵** (W^(l+1))^T，这正是"权重对称问题"的根源。

### BP 的四个生物学困境

| 困境 | 要求 | 生物学现实 |
|------|------|-----------|
| **权重对称问题** | 反向连接权重 = 前向权重转置 | 前向/反向突触是独立物理对象，无法保持精确对称 |
| **局部性问题** | 突触更新依赖远端误差信号 | Hebb 规则要求更新仅依赖突触前后局部活动 |
| **更新锁定问题** | 前向传播必须完成后才能更新权重 | 大脑持续运转，无全局"冻结"机制 |
| **信号类型问题** | 误差是实数（可负），通过相同连接双向流动 | 动作电位非负，前向与反向信号无法在同一纤维上区分 |

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| BP 在深度 ANN 中精确实现信用分配 | 数学证明 + ImageNet/NLP 等大规模验证 | 经典深度学习文献 | 高 |
| BP 的权重对称问题在生物中不可实现 | 神经解剖学：前后向突触独立；无精确权重复制机制 | 文献共识 | 高 |
| 随机反馈权重（feedback alignment）近似 BP | 计算模型 + MNIST/CIFAR 基准 | PMID:27824044 (PMC5105169) | 高（建模） |
| BP ≈ 预测编码（局部 Hebb 规则下） | 数学等价性证明 | PMID:28333583 (PMC5467749) | 中（建模，特定条件） |

## 连接

- [[credit-assignment-problem]] — BP 是解决信用分配问题的 AI 方法
- [[feedback-alignment]] — 放宽权重对称要求的 BP 近似
- [[predictive-coding]] — 在特定条件下与 BP 数学等价的生物学机制
- [[three-factor-learning-rule]] — 提供全局低维信用信号（DA × Hebb），功能互补
- [[cerebellar-ltd]] — 生物学上最接近精确误差学习的小脑机制
- [[dendritic-computation]] — 树突分离学习的物理基础（顶端 vs 基底）
- [[hebbian-learning]] — BP 是 Hebb 规则的"全局监督"版本

## 未解问题

- Q-bp-01: 皮层真正使用的信用分配机制与 BP 的差距有多大？
- Q-bp-02: 不同皮层区域是否使用不同的信用分配近似？
- Q-bp-03: 发育关键期是否是"粗糙深度学习"发生的特殊时间窗口？

## 修订历史

- 2026-06-24 · 创建 · 基于《信用分配的困境》一文 · 初始置信度：高（算法本身）；中（生物对应性）

## 来源文章

- [[2026-06-24-credit-assignment-backprop]]

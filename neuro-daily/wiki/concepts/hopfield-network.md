---
title: 霍普菲尔德网络
slug: hopfield-network
domain: concepts
type: theory
status: established
confidence: high
created: 2026-09-04
updated: 2026-09-04
revision_count: 1
dimensions: [molecular, cellular, microcircuit, cognition, theory]
related: [equilibrium-propagation, contrastive-hebbian-learning, associative-memory, pattern-completion, hippocampal-circuit, attractor-dynamics, hebbian-learning, synaptic-tagging-capture]
prerequisites: [hebbian-learning, synaptic-transmission, energy-based-models]
opens_questions: []
source_articles: [2026-09-04-equilibrium-propagation-cortical-two-phase-learning]
key_sources: ["PMID:6953413", "PMID:28522969"]
---

# 霍普菲尔德网络 (Hopfield Network)

> **一句话定义**：约翰·霍普菲尔德 1982 年提出的联想记忆模型：神经网络动力学等价于物理能量最小化，存储的记忆是能量函数的局部极小值；给定残缺输入，网络沿能量梯度弛豫到最近记忆——这是"吸引子记忆"和"模式补全"的经典形式化。

## 当前理解

我们现在认为，霍普菲尔德网络是神经科学和 AI 历史上最重要的概念桥梁之一——它证明了物理系统（自旋玻璃）、联想记忆（脑）和计算（AI）三个领域共享同一套数学框架。约翰·霍普菲尔德于 2024 年因此获得诺贝尔物理学奖。

**核心公式**：

网络能量函数（$N$ 个神经元 $s_i \in \{-1, +1\}$）：

$$E = -\frac{1}{2} \sum_{i \neq j} W_{ij} s_i s_j$$

动力学规则（顺序异步更新）：

$$s_i \leftarrow \text{sign}\left(\sum_j W_{ij} s_j\right)$$

性质：每次更新能量单调不增（$\Delta E \leq 0$）→ 系统最终收敛到极小值。

**存储规则（Hebbian）**：

$$W_{ij} = \frac{1}{N} \sum_{\mu=1}^{P} \xi_i^\mu \xi_j^\mu$$

其中 $\xi^\mu \in \{-1,+1\}^N$ 是第 $\mu$ 个存储模式。

**存储容量**：约 $0.14N$（Hopfield 1982）。超过容量出现伪记忆（spurious attractors）——对应真实记忆干扰和混淆现象。

## 关键机制

### 联想记忆检索

给定一个带噪声的输入（残缺记忆片段），网络沿能量梯度弛豫到最近的存储极小值——这实现了**模式补全**：
- 海马 CA3 区的循环连接可能实现类似功能
- 模式补全是情节记忆的核心——"闻到某种气味想起整个场景"

### 现代大霍普菲尔德网络（2020）

Ramsauer et al.（2020）将霍普菲尔德网络扩展到连续版本，存储容量从 $O(N)$ 提升到指数级。关键发现：**Transformer 的注意力机制等价于连续霍普菲尔德网络的一步检索更新**。这将生物联想记忆与 AI 大模型的核心操作统一在同一框架下。

### 能量极小化与推断

霍普菲尔德网络的弛豫过程是变分贝叶斯推断的物理实现：能量极小值对应条件分布的最大后验估计（MAP）。这是平衡传播（EP）框架的基础——EP 直接利用这一弛豫过程来计算梯度。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 网络动力学能量单调递减（Lyapunov 函数证明）| 数学证明 | PMID:6953413（1982 PNAS）| 高（数学定理）|
| 存储容量约 0.14N（随机模式）| 统计物理分析（复本法）| Amit et al. 1985（未在 PubMed）| 高（多方验证）|
| Transformer attention = 连续 Hopfield 单步更新 | 数学等价性证明 | Ramsauer et al. 2020（arXiv:2008.02217）| 高（数学推导）|

## 连接

- [[equilibrium-propagation]] — EP 在霍普菲尔德网络的能量框架上添加代价项实现梯度学习
- [[hippocampal-circuit]] — CA3 循环连接被认为实现霍普菲尔德式联想记忆与模式补全
- [[pattern-completion]] — 霍普菲尔德网络的核心功能；CA3 的核心生物功能
- [[hebbian-learning]] — 霍普菲尔德存储规则是 Hebb 规则的精确形式化
- [[associative-memory]] — 霍普菲尔德网络是联想记忆的数学模型

## 修订历史

- 2026-09-04 · 创建 · 基于《大脑的"能量景观学习"》(#135) · 补充 EP 的前置基础知识节点；初始置信度：高（1982 年经典，数学定理级别，诺贝尔物理学奖 2024）

## 来源文章

- [[2026-09-04-equilibrium-propagation-cortical-two-phase-learning]]

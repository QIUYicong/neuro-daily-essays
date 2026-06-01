---
title: 吸引子网络
slug: attractor-network
domain: concepts
type: theory
status: mainstream
confidence: medium
created: 2026-06-24
updated: 2026-06-24
revision_count: 1
dimensions: [microcircuit, cellular, cognition]
related: [pattern-completion, hippocampal-circuit, working-memory, complementary-learning-systems]
prerequisites: [ltp, nmda-receptor, action-potential]
opens_questions: [Q-pc-01]
source_articles: [2026-06-24-hippocampal-ca3-pattern-completion]
key_sources: ["PMID:1308182", "PMID:12040087", "PMID:15272123"]
---

# 吸引子网络 (Attractor Network)

> **一句话定义**：一类递归连接的神经网络，具有多个稳定平衡态（吸引子），输入会在网络动力学作用下收敛到最近的稳定态，是大脑内容可寻址联想记忆的计算原型。

## 当前理解

我们现在认为，吸引子网络是解释大脑如何存储和检索联想记忆的最有影响力的计算框架之一。它的核心思想是：记忆不存储在特定的"地址"上，而是编码在**突触权重矩阵**中，当局部激活时能自发演化到对应的稳定状态。

吸引子网络框架的强点在于：
1. 对噪声鲁棒：输入有误差时，网络"自修正"（即模式补全）
2. 联想检索：部分线索能触发完整记忆
3. 容量分析：Hopfield 网络的理论存储容量约为 0.14N（N=神经元数），超过容量出现错误

吸引子网络的主要生物对应物是海马 CA3（模式补全）和前额叶（工作记忆维持），两者都依赖强烈的循环兴奋性连接。

## 关键机制

### 1. Hopfield 网络（1982）：吸引子的数学基础

Hopfield（1982）定义了一类全连接对称神经网络（每对神经元双向等权连接），该网络：
- 具有 Lyapunov 能量函数（Energy function），每次状态更新单调降低
- 收敛到**局部能量最小值**（吸引子）
- 存储记忆的方式：用 Hebb 规则（"一起激活，一起连接"）设置权重矩阵

**检索**：给定部分损坏的输入模式，网络同步（异步）更新，直到状态稳定——此时输出就是最近的存储模式。

### 2. 存储容量与伪吸引子

标准 Hopfield 网络：
- 最大有效存储：约 0.14N 个无干扰模式
- 超过容量：出现"伪吸引子"——两个存储模式的叠加也成为局部最小值，导致检索错误

对于 CA3（大鼠，约 3×10⁵ 神经元），Treves & Rolls（PMID:1308182）估计实际容量约为 0.04N（考虑稀疏激活和空间限制），即约 12,000 个独立模式——这与大鼠的环境数量级相匹配。

### 3. 现代 Hopfield 网络与 Transformer

Ramsauer et al. (2021, arXiv:2008.02217) 将能量函数从二次型推广到指数型，使容量提升到指数级（O(e^N)），且其更新规则数学等价于 Transformer 的 softmax 注意力机制。

这表明**大脑 CA3 的吸引子记忆机制和人工 Transformer 共享同一个计算原理**，尽管实现方式不同（生物局部稀疏连接 vs 全连接矩阵运算）。

### 4. 连续吸引子与工作记忆

除了离散吸引子（Hopfield 型，用于长期记忆），神经系统中还存在**连续吸引子**（continuous attractor），其能量景观是连续流形而非离散盆地，可以稳定维持连续变量的表征。

空间导航（头向细胞、网格细胞）和工作记忆（前额叶对某个值的持续维持）被认为依赖连续吸引子动力学。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| CA3 循环连接产生离散吸引子状态 | 部分线索下 CA3 表征崩塌（NMDAR KO） | PMID:12040087 | 高（因果）|
| CA3 体内表现出非线性离散状态切换 | 相似环境中 CA3 激活全局重映射 | PMID:15272123 | 高 |
| Hopfield 网络更新 = Transformer 注意力 | 数学证明 | arXiv:2008.02217 | 高（数学严格）|

## 连接

- [[pattern-completion]] — 吸引子检索在 CA3 中实现模式补全
- [[hippocampal-circuit]] — CA3 是主要的生物吸引子网络实现
- [[working-memory]] — 前额叶的持续激活被认为依赖连续吸引子动力学
- [[complementary-learning-systems]] — 吸引子网络的模式补全是 CLS 理论中海马功能的计算核心

## 未解问题

- Q-pc-01：CA3 的实际容量是 Treves & Rolls 预测的 ~12,000，还是更大或更小？老化和 AD 中容量的下降是否解释了记忆干扰的增加？

## 修订历史

- 2026-06-24 · 创建 · 基于"记忆不混淆的秘密"第 60 篇文章 · 涵盖 Hopfield 网络基础、CA3 生物对应物和现代 Transformer 联系 · 初始置信度：中（理论框架有大量支持，但 CA3 容量估算和细节机制仍有不确定性）

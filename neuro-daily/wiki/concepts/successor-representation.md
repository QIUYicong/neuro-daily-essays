---
title: 后继者表征
slug: successor-representation
domain: concepts
type: mechanism
status: emerging
confidence: medium
created: 2026-09-18
updated: 2026-09-18
revision_count: 1
dimensions: [cellular, brain-region, cognition, behavior]
related: [cognitive-map, world-model, place-cells, grid-cells, hippocampal-circuit, sharp-wave-ripples, model-based-learning, reinforcement-learning-brain]
prerequisites: [cognitive-map, place-cells, hippocampal-circuit]
opens_questions: [Q-hsr-01, Q-hsr-02, Q-hsr-03]
source_articles: [2026-09-18-hippocampal-successor-representation-simulation]
key_sources: ["PMID:28967910", "PMID:38849521", "PMID:34799416", "PMID:30871859"]
---

# 后继者表征 (Successor Representation)

> **一句话定义**：一种关于"从当前状态出发、未来折扣状态分布"的预测表征，最初源自强化学习理论，现被认为是海马场所细胞编码的计算形式——使地图不只记录"在哪里"，还记录"从这里出发，世界将如何展开"。

## 当前理解

我们现在认为，海马场所细胞编码的可能不是纯粹的几何坐标，而是**后继者表征（SR）**——一种对未来可能状态的预测分布（Stachenfeld et al. 2017，PMID:28967910）。

**经典认知地图 vs 后继者表征**：

经典认知地图理论（O'Keefe & Nadel 1978）认为场所细胞编码了环境的几何坐标。这可以解释动物的空间导航，但无法直接解释：
- 场所细胞的感应野在奖励位置附近**不对称地向奖励方向扩展**
- 场所细胞的激活模式是**政策依赖**的（动物习惯走不同路线时，地图不同）
- 海马在**模型规划**（model-based planning）中的关键作用（Vikbladh et al. 2019，PMID:30871859）

SR框架可自然解释所有这些现象：如果场所细胞编码的是"从x出发，将来会到达哪些状态（折扣求和）"，那么：
- 奖励位置的感应野扩展 = SR随奖励方向的拉伸（因为动物将来会频繁到达奖励位置）
- 政策依赖 = 不同政策导致不同状态转移序列，SR随之改变
- 规划 = 在SR矩阵上执行前向展开（rollout）

### 数学形式

设状态空间为S，折扣因子为γ∈(0,1)，后继者表征M(s, s')定义为：

**M(s, s') = E[∑_{t=0}^∞ γ^t 𝟙[s_t = s'] | s_0 = s]**

即：从状态s出发，未来所有时刻到达状态s'的折扣期望次数。

关键性质：
- **价值函数可分解**：V(s) = ∑_{s'} M(s, s') · R(s')，其中R是奖励函数。当奖励变化时，只需更新R，无需重新建立M，这使得SR比纯model-free学习更具适应性。
- **M矩阵的特征向量分解**：Stachenfeld等人证明，内嗅皮层网格细胞可以解释为M的特征向量（basis functions），提供一个多尺度的预测分解系统。

### 与海马重放的关联

Jensen等人（2024，PMID:38849521）通过计算模型证明：海马重放（replay）在统计特征上与"在SR地图上执行策略展开（policy rollout）"完全一致：
1. 重放序列避开物理障碍（墙壁）
2. 重放序列聚焦于目标/奖励区域
3. 连续重放序列的成功率（到达目标）递增

这提示：SWR期间的重放不只是记忆的录像回放，而是大脑利用SR地图生成的**主动规划仿真**。

### 与规划层级的关联

Brunec & Momennejad（2022，PMID:34799416）的fMRI研究表明，不同脑区维护不同时间尺度的SR：
- 后部海马：γ值小（预测视野短），编码近端步骤的SR
- 前部海马：中等视野
- 眶额叶→前前额叶：γ值大（预测视野长），编码跨越多个子目标的SR

这构成了一个从后到前的**时间梯度层级**，为多尺度规划提供神经基础。

## 关键机制

### 学习SR

SR矩阵M可以通过TD（时差）学习在经验中逐步更新：
- 每当动物从状态s转移到状态s'，M(s, ·)就以预测误差更新
- 学习率和折扣因子γ由调质系统（NE/ACh/DA）动态调控
- SWR重放可能起到快速批量更新SR的作用（不依赖实时经验）

### SR与奖励解耦

SR的计算优势在于**结构与价值解耦**：
- M矩阵编码环境转移结构（与奖励无关）
- V = M · R将结构（M）与当前奖励（R）分开
- 当奖励位置改变时，只需重新计算R部分，M不变——这比重新遍历环境要快得多

实验验证：当奖励位置改变后，海马场所细胞的激活模式（M）比价值表示（vmPFC）更稳定，且动物能快速适应新奖励位置——符合SR预测。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 场所细胞感应野在奖励方向不对称扩展 | 大鼠电生理；奖励位置操控 | PMID:28967910（模型拟合） | 中 |
| 网格细胞可解释为SR的特征向量分解 | 理论模型 | PMID:28967910 | 中（计算层面；神经层面待验证）|
| 重放序列统计特征与策略展开相同 | 大鼠重放重分析+AI模型 | PMID:38849521 | 中（新兴，需独立重复）|
| 海马损伤损害model-based规划 | 遗忘症患者空间推断任务 | PMID:30871859 | 高（多实验室重复）|
| 前前额叶维护最长预测视野 | 人类fMRI + 多尺度SR建模 | PMID:34799416 | 中 |

## 连接

- [[cognitive-map]] — 认知地图是SR的神经实现形式；SR是认知地图的计算形式化
- [[place-cells]] — 场所细胞可能编码SR矩阵的行向量
- [[grid-cells]] — 网格细胞可能是SR的特征向量（低维基函数）
- [[world-model]] — SR是大脑世界模型在空间/结构层的计算核心
- [[sharp-wave-ripples]] — SWR期间的重放可能是SR空间上的策略展开
- [[hippocampal-circuit]] — 海马是SR的神经底物；CA3循环回路可能计算多步展开

## 未解问题

- Q-hsr-01（高）：能否在单细胞分辨率上直接测量SR矩阵，而不只是推断？
- Q-hsr-02（高）：PFC如何控制"何时"以及"以多少γ"触发海马SR展开？
- Q-hsr-03（中）：SR框架是否延伸至社会/概念性仿真场景（非空间）？

## 修订历史

- 2026-09-18 · 创建 · 基于《大脑的时间机器：海马后继者表征如何让神经元预演从未发生的未来》(#148) · 初始置信度：中（计算框架成熟，神经实现直接证据仍有限）

## 来源文章

- [[2026-09-18-hippocampal-successor-representation-simulation]]

---
title: 时序差分学习
slug: td-learning
domain: theories
type: theory
status: established
confidence: high
created: 2026-07-12
updated: 2026-07-12
revision_count: 1
dimensions: [cognition, behavior, methods]
related: [dopamine-reward-prediction-error, actor-critic-brain, complementary-learning-systems, reinforcement-learning, predictive-coding]
prerequisites: [dopamine-reward-prediction-error, hebbian-learning]
opens_questions: [Q-td-biological-discount-factor, Q-td-credit-assignment-long-horizon]
source_articles: [2026-07-12-dopamine-td-learning-brain-ai]
key_sources: ["PMID:9054347", "PMID:8774460", "PMID:33186815", "PMID:31003893"]
---

# 时序差分学习 (Temporal Difference Learning, TD Learning)

> **一句话定义**：时序差分学习是一类强化学习算法，通过比较相邻时间步的价值预测来生成学习误差信号（δ = r(t) + γV(t+1) − V(t)），使智能体无需等待最终结果便可从即时经验中学习；这一算法在神经科学中找到了精确的生物对应——中脑多巴胺神经元的相位性放电模式。

## 当前理解

我们现在认为，时序差分学习（Temporal Difference Learning）是强化学习领域中最具生物合理性的算法家族，也是理解大脑奖励学习的关键计算框架。

**核心方程**：
> **δ(t) = r(t) + γ · V(t+1) − V(t)**

- r(t)：当前时间步的即时奖励
- V(t)：当前状态的预期价值（折扣未来奖励之和）
- V(t+1)：下一状态的预期价值
- γ：折扣因子（0 < γ < 1，未来奖励打折）
- δ：TD 误差，驱动学习的核心信号

**TD 学习的革命性特点**：它允许学习从**当前预测的差异**中进行，不必等到最终结果——就像一个棋手在每一步棋后立即更新判断，而不是等到游戏结束才学习。这被称为"自举（bootstrapping）"。

1996–1997 年，Montague-Dayan-Sejnowski 框架（PMID:8774460）预言、Schultz-Dayan-Montague 实验（PMID:9054347）证实：**大脑的多巴胺神经元精确编码 TD 误差 δ**，在神经科学与计算机科学之间建立了跨领域的桥梁。

## 关键机制

### TD 误差作为学习驱动力

当 δ > 0（超出预期）：增强当前状态的价值估计，并向导致此状态的行动方向强化
当 δ = 0（符合预期）：无需更新，预测已准确
当 δ < 0（低于预期）：降低当前状态的价值估计，抑制导致此状态的行动

### 响应迁移：TD 的时间逆传播

随着学习进行，TD 误差从实际奖励时刻**逐步向前迁移**到最早的预测线索——这是信息"向前传播价值"的过程：
- 训练初期：奖励出现时 δ > 0；线索出现时 δ ≈ 0
- 训练后期：线索出现时 δ > 0；奖励出现时 δ ≈ 0（因为奖励已被完全预期）

这一预测完全对应多巴胺实验中 CS 阶段爆发、US 阶段响应消失的现象。

### 从简单 TD 到信念态 TD

传统 TD 假设完全可观测状态（马尔可夫假设）。在真实的部分可观测环境中（POMDP），大脑需要维护**信念态**（对当前状态的概率分布估计）：

> V^(t) = Σᵢ wᵢ · bₜ(i)

其中 bₜ(i) 是时刻 t 处于状态 i 的概率，wᵢ 是对应价值估计。这需要 mPFC（提供状态信念更新）和海马（提供时序状态表征）参与（Starkweather & Uchida 2021, PMID:33186815）。

### 分布式 TD

经典 TD 计算单一均值 δ；分布式强化学习（Dabney et al. 2020, PMID:31942076）表明，不同多巴胺神经元分别编码奖励分布的不同分位数——整体群体追踪奖励的**完整概率分布**，而非仅单一均值。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 猴 VTA/SNc DA 神经元编码三态 RPE（超/符合/低预期）| 清醒猴单神经元电生理 + 巴甫洛夫任务 | PMID:9054347 | 高 |
| DA 响应随学习从 US 迁移到 CS | 同上，训练进程分析 | PMID:9054347 | 高 |
| 人工激活 DA 可解除"阻断效应"（causal）| 光遗传激活 VTA DA | Starkweather 2021 综述 | 高 |
| 信念态对 DA 响应的调制需要 mPFC | 小鼠 mPFC 失活 + 不确定性任务 | PMID:33186815 | 中-高 |
| DQN 结合 TD 学习 + 深度网络达到人类水平 Atari | 49 款 Atari 游戏测试 | PMID:25719670 | 高（AI 技术验证）|

## 连接

- [[dopamine-reward-prediction-error]] — DA 神经元是 TD 误差 δ 的生物实现
- [[actor-critic-brain]] — Actor-Critic 架构是 TD 学习在基底节的实现形式
- [[complementary-learning-systems]] — CLS 的海马快速 + 皮层慢速对应两种时间尺度的 TD 学习
- [[predictive-coding]] — 预测编码与 TD 在数学结构上同源（都是"预测 − 实际"误差），但作用于感觉 vs 奖励不同层面
- [[hebbian-learning]] — TD 三因素规则（pre × post × DA）是将 Hebb 规则与 TD 信号的结合

## 未解问题

- Q-td-biological-discount-factor：大脑的折扣因子 γ 在行为层面是多少？有多动态？不同脑区（前额叶 vs 纹状体）的折扣偏好是否不同？
- Q-td-credit-assignment-long-horizon：数小时跨度的延迟奖励（如"今天的锻炼改善了明天的睡眠"）如何被 TD 系统正确分配信用？SWR 重放是否承担长时信用分配？

## 修订历史

- 2026-07-12 · 创建 · 基于《奖励信号的双重发现》第 80 篇文章 · 建立 TD 学习理论页，连接神经科学（DA-RPE）与 AI（深度 RL），整合标准 TD → 信念态 TD → 分布式 TD 的演进 · 初始置信度：高

## 来源文章

- [[2026-07-12-dopamine-td-learning-brain-ai]]

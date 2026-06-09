---
title: 主动推断
slug: active-inference
domain: theories
type: theory
status: emerging
confidence: medium
created: 2026-09-01
updated: 2026-09-01
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, whole-brain-network, behavior, cognition]
related: [free-energy-principle, predictive-coding, forward-model, cerebellum, motor-learning, precision-weighting, world-model, dopamine-reward-prediction-error]
prerequisites: [predictive-coding, free-energy-principle, forward-model]
opens_questions: [Q-fep-01]
source_articles: [2026-09-01-free-energy-principle-active-inference]
key_sources: ["PMID:20068583", "PMID:23663408", "PMID:19528002"]
---

# 主动推断（Active Inference）

> **一句话定义**：在自由能原理框架中，行动被理解为"实现本体感觉预测"而非"响应外部刺激的输出命令"——运动系统通过使真实感觉输入匹配内部预测来最小化自由能，感知与行动由此统一在同一优化目标下。

## 当前理解

经典感知-行动模型将大脑划分为两个阶段：感知阶段（接收并理解感觉输入）→ 行动阶段（根据感知结果输出运动命令）。

主动推断（Active Inference，Friston 2010, PMID:20068583；Clark 2013, PMID:23663408）颠覆这一图式：

**行动不是感知之后的输出，而是最小化预测误差的另一种方式。**

具体机制：
1. 运动皮层（和高级皮层）生成关于本体感觉/感觉后果的**预测**（"手应在位置 X，以速度 Y 运动"）
2. 脊髓 α 运动神经元上的牵张反射（stretch reflex）接收这一预测，执行**使实际本体感觉匹配预测的肌肉命令**
3. 从运动皮层视角看，它发出的是"本体感觉预测"而非"肌肉力量命令"

这一模型有几个重要含义：
- **感知和行动统一**：两者都在最小化同一目标函数（自由能）
- **行动是一种自我实现的预言**：大脑预测将会看到的感觉，然后通过行动使预测成真
- **目标导向行为**：可以用"期望自由能最小化"来描述（最小化预期惊喜，而非当前惊喜）

## 关键机制

### 经典运动控制 vs 主动推断

| 维度 | 经典运动控制 | 主动推断 |
|------|------------|---------|
| 行动的出发点 | 感觉误差 → 运动命令 | 本体感觉预测 → 牵张反射执行 |
| 控制层级 | 前馈指令 + 反馈修正 | 仅预测，反射弧完成执行 |
| 行动角色 | 消除外部干扰 | 实现内部预测 |
| 主动性来源 | 奖励信号 / 指令 | 预测误差本身驱动 |

### 期望自由能与目标导向行为

在主动推断的扩展框架（Sophisticated Inference）中，大脑可以**预演未来**——在内部生成模型中模拟可能的行动序列，选择使期望自由能（未来预测误差的总和）最小的那条路径。

这等价于（但不需要显式计算）最大化期望效用（奖励）——正因如此，FEP 框架可以把奖励最大化（强化学习）作为其特例处理，只要把"奖励状态"定义为"预期的低惊喜状态"即可。

### 与小脑的关系

小脑前向模型是主动推断的关键组成部分（见 [[forward-model]] 和 [[cerebellum]]）：
- 小脑提供精准的本体感觉前向预测（给定运动命令，预测感觉后果）
- 这些预测是主动推断所依赖的"先验"的主要来源之一
- 尚未解决的问题（Q-fep-01）：主动推断框架如何完整整合小脑的前向模型？

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 脊髓牵张反射可实现本体感觉预测的"执行层" | 神经生理学经典结果（Ia 传入 + γ 运动神经元） | 教科书级 | 高（机制明确）|
| 感觉运动失配 = 预测误差激活 V1 L2/3 | 小鼠 VR 实验 | PMID:30359606 | 高（体内，行为） |
| 目标导向行为可在 FEP 框架下推导出（无需显式奖励函数） | 数学推导 | PMID:20068583 | 中（理论框架，实验验证有限） |

## 连接

- [[free-energy-principle]] — 主动推断是 FEP 的核心延伸：行动 = 自由能最小化的感觉输入路径
- [[predictive-coding]] — 预测编码是感知侧的 FEP 实现；主动推断是行动侧的对称实现
- [[forward-model]] — 前向模型（小脑）提供行动后感觉后果的精准预测，是主动推断的关键先验来源
- [[cerebellum]] — 小脑是主动推断中本体感觉预测精度的主要校准者
- [[motor-learning]] — 运动学习 = 前向模型精度的提升 = 本体感觉预测误差的减少
- [[world-model]] — 主动推断中的"行动规划"依赖世界模型的内部模拟（期望自由能最小化）

## 未解问题

- Q-fep-01：主动推断如何与小脑前向模型完整整合？两者对本体感觉预测的贡献如何分工？

## 修订历史

- 2026-09-01 · 创建 · 基于《变分自由能与主动推断》(#132) · 初始置信度：中（概念框架 emerging，脊髓执行层机制 established，目标导向行为的完整 FEP 导出仍为 emerging）

## 来源文章

- [[2026-09-01-free-energy-principle-active-inference]]

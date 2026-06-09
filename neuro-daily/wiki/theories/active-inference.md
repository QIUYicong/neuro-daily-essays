---
title: 主动推断
slug: active-inference
domain: theories
type: theory
status: emerging
confidence: medium
created: 2026-09-01
updated: 2026-09-02
revision_count: 2
dimensions: [cellular, microcircuit, brain-region, whole-brain-network, behavior, cognition]
related: [free-energy-principle, predictive-coding, forward-model, cerebellum, motor-learning, precision-weighting, world-model, dopamine-reward-prediction-error, proprioceptive-prediction, deep-cerebellar-nuclei]
prerequisites: [predictive-coding, free-energy-principle, forward-model]
opens_questions: [Q-fep-01, Q-fep-02]
source_articles: [2026-09-01-free-energy-principle-active-inference, 2026-09-02-cerebellum-active-inference-proprioceptive-prior]
key_sources: ["PMID:20068583", "PMID:23663408", "PMID:19528002", "PMID:41451122", "PMID:27391681"]
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

### 与小脑的关系（2026-09-02 深化）

小脑在主动推断层次结构中承担**本体感觉先验的精度校准**角色（Parr et al. 2025，PMID:41451122）：

**本体感觉预测**不仅包含均值（期望状态），还包含**协方差**（预测确信度），分解为两个分量：
1. **空间精度分量**：调节脊髓反射弧的响应增益（γ 运动神经元）
   → 高尔基细胞通过对颗粒细胞的抑制门控来实现（Palacios et al. 2021，PMID:33757352）
2. **时间精度分量**：基于信号自相关结构，决定预测轨迹的时间平滑度
   → 深部小脑核（DCN）调节时间精度估计；DCN 损坏 → 时间精度失调 → 意向性震颤

**关键区别**：在主动推断中，只需要**一个前向模型**（小脑），逆向模型的计算被脊髓反射代替——这解决了 Wolpert-Kawato 框架中"逆向模型在哪里"的悬而未决问题。

**Friston & Herreros（2016，PMID:27391681）**：将眼睑条件化建模为变分自由能最小化，提供小脑主动推断的最早计算实现，再现了时间/轨迹条件化的损伤模式。

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
- 2026-09-02 · 修订（rev1→rev2）· 基于《小脑作为主动推断引擎》(#133，Q-fep-01 追踪）· 深化：小脑精度先验角色（DCN 时间精度 + 高尔基细胞空间精度）；主动推断只需前向模型（逆向模型被脊髓代替）；Friston & Herreros 2016 眼睑条件化模型；key_sources、related、opens_questions 更新

## 来源文章

- [[2026-09-01-free-energy-principle-active-inference]]
- [[2026-09-02-cerebellum-active-inference-proprioceptive-prior]]

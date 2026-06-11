---
title: 自由能原理
slug: free-energy-principle
domain: theories
type: theory
status: mainstream
confidence: medium
created: 2026-09-01
updated: 2026-09-01
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, whole-brain-network, behavior, cognition]
related: [predictive-coding, active-inference, precision-weighting, variational-bayes, dopamine-reward-prediction-error, canonical-microcircuit, cortical-layers, bayesian-sensory-integration, world-model, global-workspace-theory]
prerequisites: [predictive-coding, bayesian-sensory-integration, dopamine-reward-prediction-error]
opens_questions: [Q-fep-01, Q-fep-02, Q-pc-02]
source_articles: [2026-09-01-free-energy-principle-active-inference]
key_sources: ["PMID:19528002", "PMID:20068583", "PMID:23663408", "PMID:10195184", "PMID:30359606"]
---

# 自由能原理（Free Energy Principle）

> **一句话定义**：弗里斯顿提出的统计物理-变分贝叶斯框架：所有自适应生物系统都通过最小化变分自由能（感觉数据相对于内部生成模型的"惊喜"上界）来维持自身存在；感知（更新内部模型）和行动（改变感觉输入）是最小化同一目标函数的两条平行路径。

## 当前理解

我们现在认为，自由能原理（Free Energy Principle, FEP）是预测编码框架的数学精确化版本，由 Karl Friston 在 2005–2010 年间系统发展（代表作：Friston 2010, Nat Rev Neurosci, PMID:20068583）。

**核心逻辑链：**

1. 生物系统若要在热力学上维持"活着"的状态（即维持低熵、远离平衡的内部状态），必须避开感觉上令其"惊讶"的状态（数学上，即最小化感觉数据的负对数概率：−log P(s)）。

2. 直接最小化"惊喜"（-log P(s)）在计算上不可行——它需要对所有可能的世界状态积分。

3. 因此，大脑最小化一个**可计算的上界**：变分自由能 F：
   > F = KL[Q(v) || P(v|s)] + (−log P(s))
   > 其中 Q(v) 是大脑对世界隐变量 v 的近似后验，P(v|s) 是真实后验。

4. 由于 KL 散度 ≥ 0，所以 F ≥ −log P(s)，即 F 是惊喜的上界。

5. 最小化 F 有两条路径：
   - **感知推断**：更新 Q（内部信念），使其更接近真实后验
   - **主动推断**：改变 s（感觉输入），使其符合 Q 的预测（即通过行动实现本体感觉预测）

这是 FEP 的核心：**感知和行动不是两个系统，而是同一优化目标的两种实现**。

## 关键机制

### 层级生成模型

Friston & Kiebel（2009, PMC2666703）给出了层级实现：

- 生成模型 P(s, v) 分解为层级动态：高层 v₂ 缓慢变化，调控低层 v₁ 的动态；v₁ 的动态驱动感觉 s 的轨迹
- 使用广义运动坐标（位置、速度、加速度…）捕捉时间结构
- 每个层级维护两类神经元：
  - **表征单元**（近似后验期望 μ）：深层锥体细胞
  - **误差单元**（精度加权预测误差 ξ）：浅层锥体细胞

### 精度加权

预测误差的影响取决于精度（可信度的倒数）：

> 有效误差 = 精度 π × 预测误差 ξ

注意力 = 选择性提升任务相关感觉通道的 π。多巴胺可能调控奖励域的 π，乙酰胆碱调控感觉域的 π。

### 学习

长时间尺度的自由能最小化等价于更新生成模型的参数（连接权重），使得内部模型对感觉环境的建模越来越准确。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 层级生成模型可产生类 MMN 的省略响应 | 合成鸟鸣识别模型；省略音调产生预期激活 | PMID:19528002 | 中（计算模型，定性一致） |
| 感觉运动失配触发 V1 L2/3 预测误差响应 | 小鼠 VR + 双光子钙成像 | PMID:30359606 | 高（体内行为实验） |
| 多巴胺拮抗剂破坏精度加权（奖励域） | 药理 fMRI（舒必利）+ 首发精神病患者 | PMID:32576965 | 高（药理因果 + 临床）|
| FEP 框架与变分自编码器（VAE）数学等价 | 数学证明 | — | 高（数学同构） |

## 连接

- [[predictive-coding]] — 预测编码是 FEP 在神经回路层面的具体实现假说
- [[active-inference]] — 行动作为自由能最小化：主动推断是 FEP 的核心延伸
- [[precision-weighting]] — 精度加权是 FEP 中注意力和神经调质的计算角色
- [[canonical-microcircuit]] — 规范微回路提供了 FEP 误差/预测单元的解剖底层
- [[dopamine-reward-prediction-error]] — DA RPE 是奖励域中精度加权的神经实现
- [[bayesian-sensory-integration]] — 多感觉整合的贝叶斯模型是 FEP 在多模态输入层面的子案例
- [[world-model]] — 生成模型 = 大脑的世界模型；FEP 给出世界模型如何更新的数学原则
- [[global-workspace-theory]] — 大到无法被层级局部解消的预测误差可能触发全局工作空间点燃

## 未解问题

- Q-fep-01：主动推断如何与小脑前向模型整合，生成精准的本体感觉先验？
- Q-fep-02：VAE 的数学等价是否暗示大脑使用了类似反向传播的信号？"生物学可行的反向传播"（三因素规则等）在 FEP 框架中如何定位？
- Q-pc-02：FEP 作为原理是否足够可证伪？其核心实验预测是什么？（与 predictive-coding 页面共享）

## 修订历史

- 2026-09-01 · 创建 · 基于《变分自由能与主动推断》(#132) · 初始置信度：中（框架为 mainstream，但可证伪性批评有效；具体实现假说置信度各异）

## 来源文章

- [[2026-09-01-free-energy-principle-active-inference]]

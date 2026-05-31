---
title: 主动推断与自由能原理
slug: active-inference
domain: theories
type: theory
status: emerging
confidence: medium
created: 2026-05-31
updated: 2026-05-31
revision_count: 1
dimensions: [molecular, synaptic, microcircuit, brain-region, whole-brain-network, behavior, cognition]
related: [predictive-coding, precision-weighting, global-workspace-theory, world-model, hebbian-learning, dopamine-reward-prediction-error, default-mode-network, working-memory]
prerequisites: [predictive-coding, ltp, nmda-receptor, dopamine-reward-prediction-error, hebbian-learning]
opens_questions: [Q-pc-02, Q-gwt-04, Q-fep-01, Q-fep-02]
source_articles: [2026-05-31-active-inference-free-energy-principle]
key_sources: ["PMID:20068583", "PMID:28298703", "PMID:37550277", "PMID:34957844", "PMID:19528002", "PMID:38689714"]
---

# 主动推断与自由能原理 (Active Inference & Free Energy Principle)

> **一句话定义**：生物有机体通过最小化"变分自由能"（感觉惊奇的近似上界）来维持存在——感知是更新内部生成模型的信念，行动是让感觉输入符合预测，学习是精炼模型参数，三者统一于同一变分贝叶斯原则。

## 当前理解

我们现在认为，弗里斯顿（Karl Friston）的自由能原理（Free Energy Principle, FEP）是神经科学中最具统一野心的框架：它从单一数学原则推导出感知（预测编码）、学习（Hebbian 可塑性）和行动（主动推断）的具体神经机制。

**核心数学关系**：

变分自由能 F = −log P(感觉数据 | 模型) + KL[q(隐状态) || p(隐状态|感觉)]

= 真实惊奇 + 非负的 KL 散度 ≥ 真实惊奇

最小化 F 就是在近似约束下尽可能最小化对世界的惊奇，等价于最大化内部生成模型对感觉数据的解释。

**三层操作**：
1. **感知**：最小化 F 对内部表征（神经活动）的偏导数 → 更新信念
2. **学习**：最小化 F 对参数（突触权重）的偏导数 → 更新生成模型
3. **行动**：最小化 F 对行动变量的偏导数 → 改变感觉输入，使之符合预测

**主动推断的核心洞见**：大脑不只被动等待世界提供感觉数据（感知），而是主动采取行动使世界状态符合内部预测（行动）。运动控制不是"发出肌肉命令"，而是"生成本体感觉预测，让反射弧自动实现"。

**预期自由能（G）**：FEP 扩展至未来时，行动策略的选择基于 G（未来预期惊奇 + 预期认识论价值）。这自然产生探索行为（减少不确定性）而不需要外部探索奖励。

**2023 年直接实验证据**：Isomura 等人（Nature Communications，PMID: 37550277）将大鼠皮层神经元培养于微电极阵列，在 100 次训练 session 中观察到：突触权重轨迹**沿理论自由能曲面的下坡方向移动**，盲源分离自发涌现，药理预测精确（<4% 误差）。这是迄今最直接的神经网络级别 FEP 验证。

**理论地位**：FEP 本身作为元原理可能较难直接证伪，但其"过程理论"版本（层级预测编码、精度加权、本体感觉预测运动控制）产生具体可检验的预测，且 Isomura 2023 等研究已开始给出定量检验。

## 关键机制

### 变分贝叶斯推断的神经实现（Bogacz 2017）

两级层级网络：
- **表征单元**（深层 L5/6）：维护对世界状态的当前估计 μ
- **误差单元**（浅层 L2/3）：计算精度加权的预测误差 ε = (实际 − 预测) × √精度

更新规则：μ_新 = μ_旧 + 学习率 × (ε_低级 − ε_高级)

此规则完全局域——符合神经生物学约束。

### 学习作为参数更新

突触权重变化 ∝ 突触前后神经元活动的乘积 → Hebbian 学习

FEP 从第一原理推导出 Hebbian 规则，不需要额外假设。

### 主动推断中的运动控制

1. 运动皮层生成本体感觉预测（期望的关节角度/肌张力）
2. 预测传递至脊髓运动神经元
3. α 运动神经元对本体感觉预测误差做出反应，激活肌肉，直到误差消除

行动 = 预测的自我实现，而非命令的执行

### 精度加权与注意

精度（π）= 1/不确定性，加权每条误差信号对信念更新的影响

注意 = 选择性提升任务相关通道的精度 → 放大该通道的误差信号

乙酰胆碱（ACh）、去甲肾上腺素（NE）可能是实现精度调节的神经调质机制

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 变分自由能原理统一感知-行动-学习 | 数学推导 + 计算模型综合 | PMID:20068583 | 理论 |
| 体外神经网络实现 FEP 预测的自由能最小化 | 大鼠皮层 MEA 培养，100 次 session，突触轨迹追踪 | PMID:37550277 | 高（单一实验室，需重复） |
| Hebbian 可塑性是 FEP 参数学习的实现 | 数学推导 + 教程分析 | PMID:28298703 | 中 |
| 预测编码层级具有前馈γ/反馈α-β分离 | 灵长类视觉皮层 LFP 分析 | PMID:23177956 | 中 |
| 预测处理从稳态调节进化而来 | 跨物种比较 + 斑马鱼行为研究 | PMID:34957844 | 中 |
| 精度加权 = 注意的计算实现 | fMRI/EEG 研究 + VIP 去抑制回路 | PMID:27917138 | 中（机制证据间接） |

## 连接

- [[predictive-coding]] — FEP 的感知层实现；Rao-Ballard 预测编码模型是 FEP 的特例
- [[precision-weighting]] — FEP 对注意的定量解释；精度加权机制的详细描述
- [[hebbian-learning]] — FEP 从第一原理推导出 Hebbian 学习规则
- [[global-workspace-theory]] — 整合假说：大预测误差的全局传播 = GWT 点燃的候选触发机制
- [[world-model]] — FEP 的生成模型是大脑"世界模型"的正式版本
- [[dopamine-reward-prediction-error]] — 多巴胺 RPE 可被解读为 FEP 中关于奖励的精度加权误差信号
- [[default-mode-network]] — DMN 可能实现 FEP 中的深时间生成模型（自我参照预测）

## 未解问题

- Q-pc-02：FEP 元原理本身是否可证伪？其过程理论版本的最强检验是什么？
- Q-gwt-04：GWT 与 FEP/PC 的神经机制整合点在哪里？大预测误差 → 点燃假说待实验验证
- Q-fep-01：主动推断在高阶认知（语言、数学推理）中的具体神经机制是什么？
- Q-fep-02：体外实验（Isomura 2023）的 FEP 验证能否在有层级结构和反馈投射的体内网络中重复？

## 修订历史

- 2026-05-31 · 创建 · 基于《感知即推断，行动即预言自我实现》(第 37 篇) · 初始置信度：中（有直接实验证据但理论可证伪性仍有争议）

## 来源文章

- [[2026-05-31-active-inference-free-energy-principle]]

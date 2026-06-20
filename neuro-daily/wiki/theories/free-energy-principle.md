---
title: 自由能原理
slug: free-energy-principle
domain: theories
type: theory
status: emerging
confidence: medium
created: 2026-07-13
updated: 2026-08-11
revision_count: 2
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, whole-brain-network, behavior, cognition, disease]
related: [predictive-coding, active-inference, variational-autoencoder, dopamine-reward-prediction-error, basal-ganglia, working-memory, default-mode-network, precision-weighting, norepinephrine-locus-coeruleus, ascending-arousal-system, neuromodulator-systems, disorders-of-consciousness]
prerequisites: [predictive-coding, synaptic-transmission, action-potential]
opens_questions: [Q-fep-01, Q-fep-02]
source_articles: [2026-07-13-predictive-coding-free-energy-vae, 2026-08-11-active-inference-precision-neuromodulation-consciousness]
key_sources: ["PMID:20068583", "PMID:19528002", "PMID:28298703", "PMID:25689102", "PMID:39330123", "PMID:38241174", "PMID:38316333", "PMID:37695796", "PMID:27450778"]
---

# 自由能原理 (Free Energy Principle)

> **一句话定义**：弗里斯顿提出的统一大脑理论，认为大脑（乃至任何能够在变化环境中维持自身的生物系统）必须最小化一个叫做"变分自由能"的量——这等价于通过感知（更新内部模型）和行动（改变感觉输入）来减少"惊奇"（意外感觉事件的概率）。

## 当前理解

我们现在认为，自由能原理（Friston 2010, PMID:20068583）是预测编码理论的数学推广，把感知和行动统一在同一个最优化目标下。其核心主张是：大脑通过最小化"变分自由能"（variational free energy）来维持内稳态和生存。

**数学形式**：

变分自由能 F 被定义为：

$$F = -\ln p(\tilde{s}) + D_{KL}[q(\vartheta) \| p(\vartheta|\tilde{s})]$$

其中 $\tilde{s}$ 是感觉输入，$q(\vartheta)$ 是大脑对世界状态的近似后验分布（内部模型）。F 是真实负对数证据（即"惊奇度"）的上界。

最小化 F 有两个路径：
1. **感知**：通过更新 $q(\vartheta)$（内部模型）来使 $D_{KL}$ 趋近于零，使大脑的信念匹配真实世界。
2. **行动**（主动推断, active inference）：通过改变感觉输入 $\tilde{s}$ 使其符合大脑的预测——选择可以减少惊奇的行动。

**与预测编码的关系**：自由能原理是预测编码的数学基础。预测编码网络中的误差最小化等价于变分自由能的最小化。

**与 VAE 的数学对应**：自由能 F 的数学结构与变分自编码器的 ELBO（Evidence Lower BOund）损失函数高度对应——两者都通过最小化重建误差和 KL 散度来学习数据的生成模型（见 [[variational-autoencoder]]）。

## 关键机制

### 变分推断

大脑无法直接计算感觉数据在所有可能世界状态下的精确后验概率（计算上不可处理）。自由能原理提出，大脑使用**变分推断**——用一个容易处理的近似分布 $q(\vartheta)$ 来替代精确后验 $p(\vartheta|\tilde{s})$，通过最小化两者的 KL 散度来优化近似。

### 主动推断（Active Inference）

在主动推断框架中，行动不是"执行指令"，而是"实现本体感觉预测"。运动皮层生成"手应在位置 X"的预测，脊髓反射弧执行使实际感觉匹配预测的肌肉命令。这将感知和行动统一为同一个自由能最小化过程的两个面向。

### 精度（Precision）

不同感觉通道和不同预测的误差信号有不同的"精度"（precision，信念的可信度）。精度高的误差信号对内部模型的更新影响大；精度低（如噪声通道）的误差信号影响小。注意力在此框架中被定义为选择性地提升任务相关通道的精度。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 自由能原理作为统一框架，涵盖感知、行动、学习 | 理论综述；数学推导 | PMID:20068583 | 中（理论框架，难直接证伪）|
| 感知即变分推断的神经计算实现 | 理论综述；与已知皮层生理的一致性 | PMID:19528002 | 中（间接证据为主）|
| 数学教程：精确的微分方程实现与神经网络对应 | 教程论文；可再现的计算仿真 | PMID:28298703 | 高（数学可验证）|

## 精度：层级推断的权重系统（2026-08-11 新增）

自由能原理的一个关键延伸是**精度加权**（[[precision-weighting]]）：预测误差信号不均等重要，其影响内部模型更新的强度取决于精度（= 信念可信度 = 1/方差）。

在完整的主动推断框架中，精度在三个层面运作（Limanowski et al. 2024，PMID:39330123）：

| 精度层级 | 含义 | 神经调质 |
|---------|------|---------|
| 感觉精度 | 底层感觉数据的可信度 | 乙酰胆碱（ACh） |
| 转换精度 | 状态转变预测的可信度 | 去甲肾上腺素（NE）|
| 策略精度 | 行动计划的置信度 | 多巴胺（DA）|

这将 AAS（[[ascending-arousal-system]]）的五大神经调质系统重新定位为**全脑精度分配硬件**，而非简单的觉醒/注意调节器。直接实验证据（Pérez-González et al. 2024，PMID:38241174；Basu et al. 2024，PMID:38316333）见 [[active-inference]] 和 [[precision-weighting]]。

## 连接

- [[predictive-coding]] — 预测编码是自由能原理在皮层层级中的具体实现
- [[active-inference]] — 主动推断：行动作为自由能最小化的完整框架（已有页面）
- [[precision-weighting]] — 精度加权是自由能原理的关键机制：决定预测误差对信念更新的影响强度
- [[variational-autoencoder]] — VAE 的 ELBO 最大化与自由能最小化数学等价
- [[dopamine-reward-prediction-error]] — DA RPE 是自由能原理在奖励域中策略精度的特例
- [[default-mode-network]] — DMN 可能是自由能框架中最高层的先验生成器
- [[ascending-arousal-system]] — AAS 五核团 = 精度控制硬件：ACh/NE/DA/5-HT 分别对应不同精度层级
- [[neuromodulator-systems]] — 神经调质系统通过精度调制实现全脑状态管理
- [[disorders-of-consciousness]] — DoC 可理解为精度路由失败：VS/MCS/CMD 对应不同拓扑断联

## 未解问题

- Q-fep-01（高优先级）：自由能原理给出的哪些具体实验预测（可被数据证伪）？是否有任何已知神经现象在该框架下无法被解释，构成真正的反例？截至2024年，实证研究数量仍不足双位数（Badcock & Davey 2024，PMID:39451909）。
- Q-fep-02（中优先级）：三层精度（感觉/转换/策略）的神经基底是否真的分离？ACh/NE/DA 的实际投射重叠大，精度专一化程度存疑。

## 修订历史

- 2026-07-13 · 创建 · 基于《大脑的预言机》（#81）一文 · 初始置信度：中（框架 emerging/contested 之间；理论优雅但可证伪性有争议）
- 2026-08-11 · 修订 rev2 · 基于《大脑永远在押注》（#110）一文 · 新增"精度层级与神经调质分工"段落（三层精度表格；AAS重新定位为精度硬件；直接证据引用）；related 新增 precision-weighting/ascending-arousal-system/neuromodulator-systems/disorders-of-consciousness；key_sources 新增 7 条 2015-2024 文献；active-inference 页面从悬空引用恢复为已建立

## 来源文章

- [[2026-07-13-predictive-coding-free-energy-vae]]
- [[2026-08-11-active-inference-precision-neuromodulation-consciousness]]

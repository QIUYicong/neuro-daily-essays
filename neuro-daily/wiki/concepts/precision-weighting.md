---
title: 精度加权
slug: precision-weighting
domain: concepts
type: mechanism
status: emerging
confidence: medium
created: 2026-06-15
updated: 2026-08-11
revision_count: 2
dimensions: [molecular, cellular, microcircuit, brain-region, whole-brain-network, cognition, disease]
related: [predictive-coding, gain-control, acetylcholine-cortex, norepinephrine-locus-coeruleus, vip-interneurons, dopamine-reward-prediction-error, working-memory, active-inference, free-energy-principle, ascending-arousal-system, disorders-of-consciousness]
prerequisites: [predictive-coding, gain-control]
opens_questions: [Q-pc-01, Q-prec-01, Q-fep-02]
source_articles: [2026-06-15-predictive-coding, 2026-08-11-active-inference-precision-neuromodulation-consciousness]
key_sources: ["PMID:23663408", "PMID:27917138", "PMID:38259953", "PMID:30359606", "PMID:39330123", "PMID:38241174", "PMID:38316333", "PMID:37695796", "PMID:27450778"]
---

# 精度加权 (Precision Weighting)

> **一句话定义**：在预测编码框架中，每个预测误差信号都携带一个精度权重（可信度的倒数方差），高精度误差对内部模型更新的影响更大；注意力被形式化为选择性提升任务相关误差信号精度的过程，神经调质（ACh、NE）是实现这一精度动态调制的分子机器。

## 当前理解

我们现在认为，大脑不只是最小化预测误差，而是**最小化精度加权的预测误差**。两个预测误差信号可能数值相同，但如果精度不同，它们对大脑内部模型的影响截然不同。

精度加权在计算上正式化注意力：注意一个刺激 = 提升该感觉通道预测误差信号的精度 → 该通道的误差对信念更新产生更大影响 → 感知更清晰、更精确。

在神经回路层面，精度加权等效于**增益控制**：选择性地放大特定突触连接的响应。这将抽象的贝叶斯计算与具体的神经元动力学联系起来。

## 关键机制

### 数学定义

在预测编码框架中，预测误差 ε 对信念更新的贡献为：

**∆belief ∝ π × ε**

其中 π（精度）= 1/σ²（方差的倒数）。精度越高（误差越可信），对信念更新的推力越大。

### 神经回路实现的候选（Shipp 2016, 2023）

**VIP 中间神经元通路（去抑制）**：
- VIP（血管活性肠肽）神经元 → 抑制 SST（生长抑素）神经元 → 解除对锥体细胞的抑制 → 锥体细胞增益↑ → 精度↑
- 这一去抑制回路已在多个皮层区域发现，是注意效应的一个候选实现（见 [[vip-interneurons]]）

**NMDA 受体介导的增益调制**：
- NMDA 受体开放状态提高突触传递效率 → 增加对特定输入的响应增益
- 可能是精度加权的另一候选分子底物

### 神经调质作为精度调节器

| 调质 | 精度层级（Limanowski 2024） | 具体效果 | 实验证据 |
|-----|--------------------------|---------|---------|
| **ACh** | 感觉精度（likelihood） | 选择性锐化预测误差分布，改善信号-噪声分离 | Pérez-González et al. 2024 eLife（iPE 0.29→-0.05，iRS不变）PMID:38241174 |
| **NE** | 转换精度（transition） | 编码全局不确定性/模型失效；时间精度更新 | Basu et al. 2024 Biol Psych（RW拟合 R²=0.69）PMID:38316333；Sales et al. 2019 PLoS CB PMID:30608922 |
| **DA** | 策略精度（policy） | 行动计划置信度；EFE 中的 softmax 参数 β | Friston et al. 2015 Cog Neurosci（计算仿真）PMID:25689102 |
| **5-HT** | 内感觉精度（待定） | 可能调控内脏/情绪信号可信度；时间深度 | 缺乏直接证据（2026年仍高度不确定）|

### 精度失调作为疾病模型（2026-08-11 精确化）

**精神分裂症**（Friston et al. 2016，PMID:27450778）：
NMDA 受体功能减退 → 突触增益（精度调制）失常 → 感觉精度异常升高（幻觉：底层误差过度影响高层）+ 先验精度代偿升高（妄想：顽固信念抵抗感觉更新）

**孤独症谱系障碍**（Arthur et al. 2023，PMID:37695796）：
挑战简单"超精确先验"假说。实验发现：静态任务无精度差异；动态波动环境中学习率适应不足（d=0.73）。更精确诊断：**情境适应性精度（meta-precision）失调**，而非长期精度升高。

**帕金森病**（策略精度下降，DA损失）：行动起始困难 = 对任何行动计划的置信度不足

**上运动神经元病变**（感觉精度升高，皮层下行精度调制丧失）：腱反射亢进 = 脊髓精度失控

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 注意 ↔ 精度加权（计算等价性） | 理论分析 + 贝叶斯模型与注意数据拟合 | PMID:23663408 | 中（理论层面高，直接神经元标记证据不足）|
| ACh M1 受体实现 V1 注意性增益 | 猕猴 V1 + M1 阻断 + 注意任务（Herrero et al. 2008, PMID:18651663） | PMID:27917138 | 高（体内药理+电生理）|
| VIP-SST-锥体细胞去抑制回路实现局部增益 | 小鼠皮层光遗传 + 电生理（Pfeffer et al. 2013, Pi et al. 2013） | PMID:27917138; PMID:38259953 | 高（直接光遗传操控）|
| ACh 选择性调制听觉皮层预测误差精度（非重复抑制） | 麻醉大鼠听觉皮层微离子导入 ACh；113 神经元；iPE 0.29→-0.05（p<0.001），iRS p=0.121 不变 | PMID:38241174 | 高（直接体内测量，选择性精确）|
| NE 编码时间精度更新（非简单唤醒信号） | 小鼠前额叶 GRABNE2h 传感器；RW拟合 R²=0.69；时间不确定性效应显著（F₂,₂₈=11.42，p=0.0002）；LC光遗传因果验证 | PMID:38316333 | 高（因果+相关证据）|
| ASD 情境适应性精度失调（而非超精确先验） | 两感觉运动任务主动推断参数拟合；拦截任务波动性条件 d=0.73，p=.01；抓握任务无差异 | PMID:37695796 | 中（需跨实验室重复）|

## 连接

- [[predictive-coding]] — 精度加权是预测编码框架中注意的核心计算定义
- [[active-inference]] — 精度加权是主动推断框架的中心机制；三层精度（感觉/转换/策略）
- [[free-energy-principle]] — 精度加权是自由能最小化中确定误差影响权重的关键组件
- [[gain-control]] — 精度加权在回路层面的等效表述
- [[acetylcholine-cortex]] — ACh 是皮层感觉处理中最直接的精度调节器（感觉精度层）
- [[norepinephrine-locus-coeruleus]] — NE 编码全局不确定性/时间精度更新（转换精度层）
- [[vip-interneurons]] — VIP→SST 去抑制是精度加权的皮层回路实现候选
- [[dopamine-reward-prediction-error]] — DA 在策略选择域实现精度加权（策略精度层）
- [[ascending-arousal-system]] — AAS 五核团是全脑精度分配的完整硬件体系
- [[disorders-of-consciousness]] — DoC 可被理解为精度路由拓扑失败：不同状态对应不同断联模式

## 未解问题

- Q-pc-01：精度单元是否可以被在体内直接鉴定和操控（独立于增益控制）？
- Q-prec-01：不同神经调质（ACh/NE/DA）对精度调节的分工是否有清晰的空间-时间结构？它们的精度调节是否真的是在最小化预测误差，还是只是一般性的信噪比调节？
- Q-fep-02（新增）：三层精度（感觉/转换/策略）的神经基底是否真的分离？投射重叠大，精度专一化程度存疑。

## 修订历史

- 2026-06-15 · 创建 · 基于《当大脑主动预测而非被动接收》一文 · 初始置信度：中（计算理论清晰，但神经回路级别的直接验证有限）
- 2026-08-11 · 修订 rev2 · 基于《大脑永远在押注》（#110）一文 · 神经调质精度分工表格精确化（加入2024实验证据）；新增精度失调疾病模型（精神分裂症/ASD/PD/MND，含量化证据）；新增关键证据3条（ACh eLife 2024、NE Biol Psych 2024、ASD PLoS CB 2023）；connected 新增 active-inference/free-energy-principle/ascending-arousal-system/disorders-of-consciousness；key_sources 新增5条；opens_questions 新增 Q-fep-02

## 来源文章

- [[2026-06-15-predictive-coding]]
- [[2026-08-11-active-inference-precision-neuromodulation-consciousness]]

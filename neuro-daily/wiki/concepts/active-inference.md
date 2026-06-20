---
title: 主动推断
slug: active-inference
domain: concepts
type: mechanism
status: established
confidence: medium
created: 2026-08-11
updated: 2026-06-21
revision_count: 2
dimensions: [molecular, cellular, microcircuit, brain-region, whole-brain-network, behavior, cognition, disease]
related: [free-energy-principle, predictive-coding, precision-weighting, norepinephrine-locus-coeruleus, ascending-arousal-system, neuromodulator-systems, dopamine-reward-prediction-error, disorders-of-consciousness, working-memory, interoception, insula]
prerequisites: [predictive-coding, free-energy-principle, synaptic-transmission]
opens_questions: [Q-fep-01, Q-fep-02, Q-ai-01, Q-int-01, Q-int-03]
source_articles: [2026-08-11-active-inference-precision-neuromodulation-consciousness, 2026-06-21-interoception-insular-cortex]
key_sources: ["PMID:20068583", "PMID:25689102", "PMID:30608922", "PMID:39330123", "PMID:38241174", "PMID:38316333", "PMID:37695796", "PMID:27450778", "PMID:26016744", "PMID:28080966"]
---

# 主动推断 (Active Inference)

> **一句话定义**：行动和感知被统一为最小化变分自由能的两个方向——感知通过更新内部生成模型来匹配世界，行动通过改变感觉输入来符合模型预测；选择行动时还最小化"期望自由能"，该量分解为外在价值（目标满足）和认知价值（信息增益/探索）。

## 当前理解

主动推断（Friston 2010，PMID:20068583）是[[free-energy-principle|自由能原理]]在运动控制和决策层面的核心推论。它挑战了经典神经科学的"运动命令"视角：

**经典视角**：运动皮层生成命令 → 脊髓执行 → 肌肉运动

**主动推断视角**：运动皮层生成本体感觉预测（"手应当在位置 X"）→ 脊髓反射弧执行使实际本体感觉匹配预测的肌肉收缩

在此框架中，感知和行动共享同一个优化目标：**最小化变分自由能 F**。感知通过内部模型的贝叶斯更新实现（减少 KL 散度），行动通过改变感觉输入使之符合预测实现（减少预测误差）。

### 期望自由能（EFE）与策略选择

行动选择不只依赖当前感觉状态，还涉及对未来的预期评估。期望自由能（Expected Free Energy，EFE）是在选择行动策略之前对未来自由能的预期：

$$G(\pi) = \underbrace{-\mathbb{E}[\ln p(o|\pi)]}_{\text{外在价值（利用）}} - \underbrace{\mathbb{E}[D_{KL}[q(s|\pi)\|p(s)]]}_{\text{认知价值（探索）}}$$

- **外在价值**（extrinsic value）：策略能多大程度实现偏好结果
- **认知价值**（epistemic value）：策略能多大程度减少对世界状态的不确定性

这个分解优雅地解决了探索-利用困境：认知价值耗尽前，探索具有内在驱动力；不确定性消除后，利用自然涌现（Friston et al. 2015，PMID:25689102）。

## 关键机制

### 精度在主动推断中的核心角色

预测误差信号并非均等重要——其影响内部模型更新的程度取决于精度（precision，即信念可信度 = 1/方差）。见[[precision-weighting]]详细讨论。

在主动推断框架中，**神经调质系统正是全脑精度分配的硬件**（Limanowski et al. 2024，PMID:39330123）：

| 精度层级 | 含义 | 神经调质 | 核团来源 |
|---------|------|---------|---------|
| 感觉精度（likelihood） | 底层感觉数据的可信度 | ACh | 基底前脑（BF）|
| 转换精度（transition） | 世界状态转变预测的可信度 | NE | 蓝斑（LC）|
| 策略精度（policy） | 行动计划的置信度 | DA | VTA/SNc |
| 内感觉精度（interoceptive） | 内脏/身体状态的可信度 | 5-HT（待定）| 背侧缝核（DRN）|

### 主动推断中的运动控制

运动失调在精度框架下获得了统一解释（Limanowski et al. 2024）：
- 策略精度下降（DA 减少）→ 帕金森样动力学减退（akinesia）
- 感觉精度升高（脊髓层精度失控）→ 腱反射亢进（上运动神经元病变）
- 层级精度断联（额叶离断）→ 持续运动（perseveration）

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| ACh 选择性调制听觉皮层预测误差精度（而非简单增益） | 大鼠听觉皮层微离子导入 ACh + 奇异音范式（n=113 神经元）；iPE 0.29→-0.05（p<0.001），iRS 不变（p=0.121） | PMID:38241174 | 高（体内直接测量）|
| LC-NE 编码时间精度更新信号 | 小鼠前额叶 NE GRABNE2h 传感器；RW模型拟合 R²=0.69；时间不确定性效应 F₂,₂₈=11.42 p=0.0002；光遗传因果验证 | PMID:38316333 | 高（因果+相关）|
| LC-NE phasic/tonic 模式是信念更新的涌现属性 | 计算模型与 LC 生理数据比较；状态-行动预测误差动态调整学习率 | PMID:30608922 | 中（计算模型）|
| ASD 精度失调 = 情境适应而非超精确先验 | 两感觉运动任务主动推断参数拟合；d=0.73，p=.01（拦截波动性条件）；抓握任务无差异 | PMID:37695796 | 中（n 较小，需重复）|
| DA 策略精度计算仿真复现帕金森运动特征 | 混合层级主动推断模型；策略精度参数降低→akinesia-like dynamics | PMID:39330123 | 中（计算模拟）|

## 精度失调作为统一计算病理学

主动推断框架的核心临床贡献是将多种神经精神疾病统一为**不同层级精度的异常**：

### 精神分裂症
NMDA 受体功能减退 → 突触增益（精度调制）失常 → 感觉精度升高（幻觉）+ 先验精度代偿（妄想）。Friston 断联假说预测：患者在需要抑制先验信念的任务上系统性受损（PMID:27450778）。

### 孤独症谱系障碍
非"超精确先验"，而是**情境适应性精度（meta-precision）失调**：在静态任务中精度正常，但在动态波动环境中学习率调整不足（Arthur et al. 2023，PMID:37695796）。

### 意识障碍（DoC）
精度路由视角：VS/UWS = 精度路由拓扑断联（无法形成层级组织模型）；MCS = 部分精度路由恢复；CMD = 运动输出精度分配失败但内隐推断保留（连接 [[disorders-of-consciousness]]）。

## 争议

- **可证伪性**：FEP/主动推断的灵活性允许事后解释任何数据。实证研究到 2024 年数量仍少于双位数，多停留计算仿真（Badcock & Davey 2024，PMID:39451909）
- **精度专一化假说**：ACh/NE/DA 的三分法建立在理论映射上，实际投射重叠大，精度专一化程度存疑
- **5-HT 角色**：仍高度不确定，缺乏直接实验证据

## 连接

- [[free-energy-principle]] — 数学基础：变分自由能最小化
- [[predictive-coding]] — 皮层层级实现：误差单元/表征单元/反馈/前馈
- [[precision-weighting]] — 精度的具体机制：增益控制、注意力的计算角色
- [[norepinephrine-locus-coeruleus]] — NE 作为转换精度控制器：LC 主动推断模型
- [[ascending-arousal-system]] — AAS 五核团 = 全脑精度控制硬件
- [[neuromodulator-systems]] — 神经调质系统作为精度网络
- [[dopamine-reward-prediction-error]] — DA 策略精度 vs RPE 的统一
- [[disorders-of-consciousness]] — 精度路由视角的意识障碍分类
- [[interoception]] — 主动内感受推断是主动推断框架在内脏/情绪域的核心应用
- [[insula]] — 岛叶皮层作为主动内感受推断的实施位点（前岛叶发出预测，后岛叶计算误差）

## 未解问题

- Q-fep-01（高优先级）：主动推断给出哪些可被数据证伪的具体实验预测？
- Q-fep-02（中优先级）：三层精度的神经基底真的分离还是高度重叠？
- Q-ai-01（中优先级）：5-HT 在精度框架中的具体角色——内感觉精度还是时间深度？如何实验检验？

## 修订历史

- 2026-08-11 · 创建 · 基于《大脑永远在押注》（#110）一文 · 填补 [[free-energy-principle]] 的悬空引用；初始置信度：中（框架成熟，但关键实验预测实证检验不足）
- 2026-06-21 · 修订 · 基于《内感受：大脑如何从心跳中构建情绪与自我》（#113）· 增加内感受推断（interoceptive inference）作为主动推断的核心应用域；新增 [[interoception]] 和 [[insula]] 连接；增加 Q-int-01/Q-int-03 至 opens_questions；新增 EPIC 模型（PMID:26016744）和 Seth&Friston 2016（PMID:28080966）来源

## 来源文章

- [[2026-08-11-active-inference-precision-neuromodulation-consciousness]]
- [[2026-06-21-interoception-insular-cortex]]

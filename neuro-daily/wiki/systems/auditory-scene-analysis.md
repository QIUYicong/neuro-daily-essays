---
title: 听觉景观分析
slug: auditory-scene-analysis
domain: systems
type: mechanism
status: established
confidence: high
created: 2026-08-19
updated: 2026-08-19
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, systems, cognition]
related: [auditory-cortex, auditory-dual-stream, temporal-coherence, tonotopy, tpj-temporoparietal-junction, selective-attention, auditory-streaming]
prerequisites: [auditory-cortex, tonotopy]
opens_questions: [Q-asa-01, Q-asa-02, Q-asa-03]
source_articles: [2026-08-19-auditory-scene-analysis-cocktail-party]
key_sources: ["PMID:28821680", "PMID:22522927", "PMID:21196054", "PMID:32273487", "PMID:28954867", "PMID:36049112", "PMID:29061698"]
---

# 听觉景观分析 (Auditory Scene Analysis, ASA)

> **一句话定义**：大脑将混合声学输入（来自多个同时发声的声源）分解并重组为感知上内聚的独立"听觉流"的过程，是所有高层听觉认知（语言理解、声音识别、音乐感知）的前提条件。

## 当前理解

我们现在认为，听觉景观分析（ASA）是一个**层级双向**的计算过程：底层声学线索驱动的"原始分割"（primitive segregation）与顶层注意和知识驱动的"图式分割"（schema-based segregation）协同工作，在从耳蜗到高阶颞叶皮层的完整听觉层级上逐级实现声音流的组织与分离。

**初级听觉皮层（A1）是整个声景的忠实代表**：无论被关注还是被忽略的声音流，在A1中均以相近的保真度被表征（Puvvada & Simon 2017，PMID:28821680）。声景分割的选择性不在A1实现。

**高阶颞叶皮层（STG及以上）是注意驱动的选择性放大器**：在多说话人场景中，颞上回（STG）选择性地以高保真度表征被关注的说话人，同时有效抑制被忽略说话人的表征（Mesgarani & Chang 2012，PMID:22522927）。这一选择性重组在注意切换后数百毫秒内完成。

**流分割信号沿层级渐进放大**：从A1到次级皮层（Belt/PEG），前景流的神经增益相对于背景流逐步增大，说明分割是一个连续强化过程，而非皮层高层的突变切换（Saderi et al. 2020，PMID:32273487）。

**时间相干性是跨特征绑定的统一原则**（Shamma et al. 2011，PMID:21196054）：同一声源的多个声学特征（音调、音色、空间位置）在时间上同步波动，这种时间相干性是将它们绑定为同一流的神经计算标准（详见 [[temporal-coherence]]）。

## 关键机制

**一、耳蜗频率分析（物理基础）**
基底膜沿对数频率轴分解混合信号；不同频率成分激活不同位置的内毛细胞；外毛细胞的橄榄耳蜗束传出允许顶层对外周增益进行调控。

**二、A1的适应性增益调节**
A1神经元对持续不变的背景声发生多时间尺度的适应性抑制（Willmore & King 2023，PMID:36049112），相对增强前景声（新颖/变化的声音）的响应，类似于视觉的对比度适应。这是"听觉图形-背景"分离的关键底层机制。

**三、音调拓扑种群分离**
A1的音调拓扑结构（tonotopy）为不同频率声源的神经响应提供空间分离基础：频率差越大，激活的A1种群空间距离越大，分割越容易。种群分离程度与感知上的流分割概率正相关（Fishman et al. 2017，PMID:28954867）。

**四、A1→Belt→Parabelt层级放大**
次级皮层（Belt/Parabelt/STG）对前景流相对于背景流的神经增益逐步放大，形成连续层级放大流水线。

**五、注意的选择性提取（STG/STS）**
高阶颞叶皮层（STG，STSp）在前额叶/顶叶注意网络（经由TPJ）的驱动下，选择性放大被关注流，将被忽略的多个声音流折叠为单一"背景对象"。

**六、双稳态动力学（感知竞争）**
ABA音调序列（频率不同的A和B交替）是听觉双稳态的经典范式：同一不变输入可以被感知为"一条流"或"两条流"，两种感知之间自发切换。这反映了A和B频率对应的A1神经种群之间的竞争抑制动力学，也揭示了流分割的不稳定基础（而非固定输出）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| A1代表整个声景（不区分关注/忽略） | MEG+皮层神经反应重建 | PMID:28821680 | 高 |
| STG选择性高保真表征被关注说话人 | 颅内ECoG（神经外科患者） | PMID:22522927 | 高（小样本） |
| 注意切换后数百毫秒内神经表征重组 | ECoG，注意切换范式 | PMID:22522927 | 高 |
| 流分割信号在A1→PEG层级中放大 | 铁鼬多电极同步记录 | PMID:32273487 | 中-高 |
| 音调拓扑种群分离与感知分割相关 | 猕猴颞横回多通道记录 | PMID:28954867 | 中-高 |
| 适应机制增强听觉图形-背景分离 | 综述，多物种多层次 | PMID:36049112 | 高 |
| 右TPJ激活与成功听觉注意追踪相关 | 并发EEG-fMRI | PMID:29061698 | 中 |

## 连接

- [[auditory-cortex]] — A1是声景分析的初级底层：全景代表+适应性增益调节
- [[auditory-dual-stream]] — 腹侧/背侧流是ASA的下游：处理声景分析后的听觉对象
- [[temporal-coherence]] — 跨特征流绑定的统一计算原则
- [[tonotopy]] — A1的频率地图是种群分离机制的物理基础
- [[tpj-temporoparietal-junction]] — 注意控制→听觉皮层流选择的关键接口
- [[language-network]] — ASA是语言感知（腹侧流输入）的前序处理

## 未解问题

- Q-asa-01：时间相干性的突触实现机制？（伽马振荡、循环连接、侧抑制？）
- Q-asa-02：ABA双稳态切换时A1是否随之变化，还是切换只发生在高阶皮层？
- Q-asa-03：老年性ASA能力下降的主要瓶颈（外周/A1适应/前额叶注意）各贡献多少？

## 修订历史

- 2026-08-19 · 创建 · 基于《鸡尾酒会问题》第101篇文章 · 初始置信度：高

## 来源文章

- [[2026-08-19-auditory-scene-analysis-cocktail-party]]

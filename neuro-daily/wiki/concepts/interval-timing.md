---
title: 区间计时
slug: interval-timing
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-07-31
updated: 2026-07-31
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, cognition]
related: [striatal-beat-frequency, population-clock, cerebellum, basal-ganglia, dopamine-reward-prediction-error, temporal-binding-window, scalar-property-timing]
prerequisites: [medium-spiny-neuron, dopamine-reward-prediction-error, cerebellum]
opens_questions: [Q-it-01, Q-it-02]
source_articles: [2026-07-31-interval-timing-basal-ganglia-striatum]
key_sources: ["PMID:15217335", "PMID:21389235", "PMID:38918348", "PMID:35446093"]
---

# 区间计时 (Interval Timing)

> **一句话定义**：大脑测量数百毫秒到数十秒时间间隔的能力与机制——它不依赖单一中央时钟，而由小脑（事件/毫秒）、纹状体与皮层-纹状体-丘脑环路（秒级）等多套分布式机制按时间尺度和任务类型分工实现。

## 当前理解

我们现在认为，时间处理是**分布式**的，而非由某个集中的"中央时钟"读出（Mauk & Buonomano, 2004, PMID:15217335）。不同的时间尺度（毫秒 / 秒 / 昼夜）和不同的任务类型（单一区间 vs 节拍、感知 vs 运动）调用**物理上不同**的回路与机制。

一个延续至今的核心二分：

- **专用计时（dedicated timing）**：存在专门负责计时的回路（小脑、基底节），像配备"硬件计时器"。
- **内在计时（intrinsic timing）**：时间从一般神经网络的固有动力学中涌现——网络状态本身随时间演化，读出状态即读出时间（[[population-clock]] 是其现代形式）。

区间计时特指**数百毫秒到数十秒**的尺度（区别于昼夜节律的分子时钟，见 [[circadian-clock]]）。它是更高级认知的隐形脚手架：运动时序、经典条件反射、奖励时机预测、决策与等待，以及多感觉整合的时间绑定窗（[[temporal-binding-window]]）。

## 关键机制

### 小脑：毫秒级事件计时

小脑负责**事件计时（event-based）**——单一、离散的时间间隔（如眼睑条件反射、绝对时长），靠橄榄-小脑系统（下橄榄核→攀爬纤维→浦肯野细胞 LTD）。**不**做节拍计时、**不**做连续计时（Breska & Ivry, 2016, PMID:27088121）。猴电生理：准备活动运动前~500ms 启动，主要调节**亚秒级变异性**（Tanaka et al., 2024, PMID:38918348）。详见 [[cerebellum]]。

### 纹状体：秒级区间计时核心

- **拍频符合检测**：皮层振荡子的相位漂移形成对每个时刻独特的图案，纹状体 MSN 作为符合检测器读出时间（[[striatal-beat-frequency]]）。
- **斜坡放电（ramping）**：约 1/3 的纹状体 MSN 在区间内单调升或降；涌现于"混沌边缘"；独立于皮层斜坡（Ponzi & Wickens, 2022, PMID:35978564）。
- **D1/D2 对立协同**：6s 区间内 D2-MSN 升、D1-MSN 降，共同累积时间证据（Bruce et al., 2025）。详见 [[basal-ganglia]]、[[medium-spiny-neuron]]。
- 准备活动可贯穿延迟期最长 ~2 秒（Tanaka et al., 2024）。

### 皮层与种群时钟

时间编码在群体活动于高维状态空间的轨迹中（[[population-clock]]）；纹状体的"序列性"高于运动皮层（Zhou & Buonomano, 2022, PMID:35446093）。皮层-纹状体-丘脑环路（含 SMA、前运动皮层、DLPFC）支持节拍/相对计时（Teki et al., 2011, PMID:21389235）。

### 多巴胺的调制

经典起搏器-累加器模型中多巴胺控制时钟速度（Buhusi & Meck, 2005）；SBF 中多巴胺调振荡频率产生**即时、标量**的时间改变（Oprisan & Buhusi, 2011, PMC:PMC3178804）。但帕金森病的复杂时间扭曲（短时过度产生、长时产生不足、DA 结合与计时无关）否定了单一"慢时钟"模型（Terao et al., 2021, PMID:33815049）。

### 标量特性

计时误差随被测时长成比例增长（韦伯定律的时间版本）；log-power 形式的放电率可解释（Shouval et al., 2014, PMC:PMC4063330）。SBF 模型需生物学噪声维持标量性。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 时长计时与节拍计时由分离网络实现 | fMRI 18 人；橄榄-小脑 vs 纹状-丘脑-皮层 | PMID:21389235 | 高 |
| 小脑=事件计时（非节拍/非连续） | 病变双重分离 + 眼睑条件反射 | PMID:27088121 | 高 |
| 小脑调变异性、基底节测时长 | 猴电生理（~500ms vs ~2s） | PMID:38918348 | 中高 |
| 纹状体斜坡是局部独立机制 | 计算建模；~1/3 MSN；混沌边缘 | PMID:35978564 | 中 |
| D1 降/D2 升协同累积、有因果作用 | 光遗传+药理；R²=0.95；抑制延迟计时 | DOI:10.7554/eLife.96287.4 | 中高 |
| DA 调频率→标量时间改变 | SBF 模型仿真 | PMC:PMC3178804 | 中 |
| PD 时间扭曲非简单慢时钟 | 患者行为+影像；DA 结合与计时无关 | PMID:33815049 | 中高 |
| 时间编码在群体轨迹中 | 理论/群体记录综述 | PMID:35446093 | 中 |

## 连接

- [[cerebellum]] — 毫秒级事件计时器
- [[basal-ganglia]] — 秒级区间计时核心
- [[striatal-beat-frequency]] — 拍频符合检测机制
- [[population-clock]] — 内在计时的现代形式（高维轨迹）
- [[medium-spiny-neuron]] — D1/D2 对立协同的细胞基础
- [[dopamine-reward-prediction-error]] — 多巴胺调制计时；奖励时机的时间维度
- [[temporal-binding-window]] — TBW 依赖毫秒级时间测量，是区间计时的下游
- [[scalar-property-timing]] — 计时的韦伯定律
- [[circadian-clock]] — 对照：分子时钟 vs 神经动力学时钟

## 未解问题

- **Q-it-01**：SBF 的皮层振荡子—MSN 符合检测回路是否真实存在？SBF、斜坡、种群时钟是互斥、互补还是同一现象的不同描述层次？
- **Q-it-02**：种群时钟与专用计时器是什么关系？纹状体序列性为何高于运动皮层？读出轨迹位置的下游译码器是谁？

## 修订历史

- 2026-07-31 · 创建 · 基于《大脑的秒表》文章 #99 · 初始置信度：高

## 来源文章

- [[2026-07-31-interval-timing-basal-ganglia-striatum]]

---
title: 基底节
slug: basal-ganglia
domain: systems
type: structure
status: established
confidence: high
created: 2026-07-31
updated: 2026-09-26
revision_count: 4
dimensions: [cellular, microcircuit, brain-region, behavior, cognition, disease]
related: [dopamine-reward-prediction-error, interval-timing, striatal-beat-frequency, td-learning, parkinson-disease, prefrontal-cortex, thalamus, foxp2, vocal-learning, childhood-apraxia-of-speech, medium-spiny-neuron, striatal-direct-indirect-pathway, striatal-plasticity, habitual-behavior, goal-directed-behavior]
prerequisites: [medium-spiny-neuron, dopamine-reward-prediction-error]
opens_questions: [Q-bg-01, Q-foxp2-01]
source_articles: [2026-07-31-interval-timing-basal-ganglia-striatum, 2026-08-12-foxp2-language-genetics-development, 2026-09-01-medium-spiny-neurons-striatum, 2026-09-26-habit-goal-directed-dorsal-striatum]
key_sources: ["PMID:21389235", "PMID:38918348", "PMID:35978564", "PMID:34260143", "PMID:25225386", "PMID:21469956", "PMID:31171839", "PMID:27373834", "PMID:14750976", "PMID:16045504", "PMID:19776734", "PMID:21435563"]
---

# 基底节 (Basal Ganglia)

> **一句话定义**：皮层下核团群（纹状体、苍白球、丘脑底核、黑质），通过相互拮抗的直接/间接通路在多巴胺信号调控下实现动作选择、强化学习与时间认知；既是运动控制的中枢，也是奖励学习和秒级区间计时的核心。

> **注**：本页是 systems 域的首版概览，强调基底节在区间计时中的角色，将在后续文章中深化。回路级别的更详细解剖与直接/间接通路机制另见 [[circuits/basal-ganglia]]（疾病/帕金森视角的姊妹页）。

## 当前理解

我们现在认为，基底节是一个**动态竞争与遴选**系统：在多种候选行为或认知状态中，通过直接/间接通路的相对强弱选择最适当的方案并抑制竞争方案。它的功能远不止运动——还包括强化学习、习惯形成、认知控制，以及本页重点关注的**秒级区间计时**（[[interval-timing]]）。

人类 fMRI 显示，**节拍/相对计时**调用的正是**纹状-丘脑-皮层（striato-thalamo-cortical）**网络（壳核 + 尾状核 + 丘脑 + SMA + 前运动皮层 + DLPFC），与小脑负责的绝对时长计时形成分工（Teki et al., 2011, PMID:21389235）。

## 解剖

### 核团组成

| 结构 | 英文 | 角色 | 主要递质 |
|------|------|------|---------|
| 纹状体（尾状核 + 壳核） | Striatum (caudate + putamen) | 皮层/丘脑输入整合，两条通路起点 | GABA（MSN） |
| 伏隔核 | Nucleus accumbens | 腹侧纹状体，奖励动机 | GABA |
| 苍白球内节 | Globus Pallidus internal (GPi) | 主要输出，抑制丘脑 | GABA |
| 苍白球外节 | Globus Pallidus external (GPe) | 间接通路中继 | GABA |
| 丘脑底核 | Subthalamic Nucleus (STN) | 唯一兴奋性核团 | 谷氨酸 |
| 黑质致密部 | Substantia Nigra pars compacta (SNc) | 多巴胺来源 | 多巴胺 |
| 黑质网状部 | Substantia Nigra pars reticulata (SNr) | 输出门 | GABA |

纹状体 = 尾状核 + 壳核 + 伏隔核（腹侧）。中型多棘神经元（MSN）占纹状体神经元绝大多数，分 D1 型（直接通路）与 D2 型（间接通路），见 [[medium-spiny-neuron]]。

### 直接/间接通路模型

- **直接通路（促进运动）**：皮层 → D1-MSN → 抑制 GPi/SNr → 丘脑去抑制 → 皮层激活 → 运动。多巴胺经 D1 增强此通路。
- **间接通路（抑制运动）**：皮层 → D2-MSN → 抑制 GPe → STN 去抑制（激活）→ 激活 GPi/SNr → 丘脑抑制 → 运动受阻。多巴胺经 D2 减弱此通路。
- 现代修正：两通路并非严格分离，存在广泛交织，功能更接近"软竞争"。

## 在运动、奖励、计时、认知中的角色

- **运动**：动作选择与发起的门控；直接/间接通路平衡决定运动是否被允许。
- **奖励学习**：SNc 多巴胺神经元编码奖励预测误差（RPE），作为三因素学习的"第三因子"（[[dopamine-reward-prediction-error]]）。
- **区间计时**（本页重点，[[interval-timing]]）：
  - 准备活动可贯穿延迟期最长 ~2 秒，负责数百毫秒到秒级的**时长测量**（Tanaka et al., 2024, PMID:38918348）。
  - 约 1/3 纹状体 MSN 显示单调**斜坡放电**，涌现于"混沌边缘"，独立于皮层斜坡（Ponzi & Wickens, 2022, PMID:35978564）。
  - **D1/D2 对立协同**：6s 区间内 D2-MSN 升、D1-MSN 降，共同累积时间证据（漂移扩散 R²=0.95），抑制任一者都延迟计时（Bruce et al., 2025）。
  - **拍频符合检测**（[[striatal-beat-frequency]]）：MSN 读出皮层振荡相位图案以测量时长。
- **认知**：前额叶-纹状体环路参与工作记忆与认知控制。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 节拍计时调用纹状-丘脑-皮层网络 | fMRI 18 人 | PMID:21389235 | 高 |
| 基底节负责秒级时长测量 | 猴电生理，延迟期~2s 准备活动 | PMID:38918348 | 中高 |
| 纹状体斜坡为局部独立机制 | 计算建模；~1/3 MSN；混沌边缘 | PMID:35978564 | 中 |
| D1/D2 对立协同累积时间证据 | 光遗传+药理；R²=0.95 | DOI:10.7554/eLife.96287.4 | 中高 |

## FOXP2与纹状体发育（2026-08-12新增）

纹状体不仅是计时和运动选择的核心，也是**言语运动程序化回路的关键节点**，这一功能依赖FOXP2在发育期的调控：

**FOXP2在纹状体表达**：优先在纹状体小室（striosome）隔室表达，发育期（胚胎至出生后早期）最高，成体降低但保留；调控中型棘神经元（MSN）的树突形态复杂度（Vernes et al. 2011；PMID:21765815）

**FOXP2敲减→MSN树突简化**：原代纹状体MSN实验显示，FoxP2敲减导致树突总长度和分支复杂度显著减少——直接减少了纹状体整合皮层输入的容量

**语言习得层面**：人源化Foxp2小鼠纹状体表现出：
- 背内侧纹状体（DMS，陈述性学习）多巴胺降低~30%
- 背外侧纹状体（DLS，程序性学习）LTD增强
- 净效果：加速从陈述性（有意识学习音素）到程序性（自动化流利言语）的转换（Schreiweis et al. 2014；PMID:25225386）

**FOXP2突变的纹状体后果**：KE家族R553H突变导致纹状体MSN中dynactin1过表达→dynein-dynactin蛋白马达破坏→TrkB/BDNF信号受损→树突发育不全→言语运动程序化失败（儿童语言失用症CAS）（Walker et al. 2023；PMID:37137515）

**跨物种视角**：鸣禽纹状体（Area X）是发声学习的前馈可塑性回路核心节点，Area X中FoxP2动态调控（鸣唱时下调）控制发声变异性窗口——与哺乳动物纹状体在程序性学习中的角色高度平行

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 节拍计时调用纹状-丘脑-皮层网络 | fMRI 18 人 | PMID:21389235 | 高 |
| 基底节负责秒级时长测量 | 猴电生理，延迟期~2s 准备活动 | PMID:38918348 | 中高 |
| 纹状体斜坡为局部独立机制 | 计算建模；~1/3 MSN；混沌边缘 | PMID:35978564 | 中 |
| D1/D2 对立协同累积时间证据 | 光遗传+药理；R²=0.95 | DOI:10.7554/eLife.96287.4 | 中高 |
| FoxP2敲减→MSN树突简化 | 原代纹状体神经元培养 | PMID:21765815 | 高 |
| 人源化Foxp2→纹状体多巴胺-30%+DLS LTD增强 | Foxp2^hum knockin小鼠 | PMID:25225386 | 中 |
| D1 MSN激活→丘脑/运动皮层兴奋；D2 MSN激活→丘脑/运动皮层抑制 | ofMRI+AAV-ChR2（小鼠DMS）| PMID:27373834 (PMC5528162) | 高 |
| DMS损伤→目标导向退化为习惯；DLS损伤→无法形成习惯 | 靶向损伤+行为测试（啮齿类）| PMID:31171839 (PMC7231228) | 高 |

## 背内侧/背外侧纹状体的双系统功能分化（2026-09-26新增）

纹状体在背侧轴上分为两个功能上互补、神经上独立的子系统，分别支撑**目标导向行为**和**习惯行为**：

**背内侧纹状体（DMS，尾状核内侧）→ 目标导向行为**
- DMS 接受前额叶联合皮层（prelimbic, PL）和眶额叶的大量投射，经 DA 依赖性可塑性建立**动作-结果（A-O）联结**
- DMS 损毁→即使少量训练后行为也变为习惯性（Yin et al. 2005, PMID:16045504）
- 前边缘皮层（PL）对 A-O 联结的**获得**必要（但不影响已建立联结的表达）
- 计算等价：**有模型（model-based）强化学习**，维护世界模型 + 前向规划，对结果贬值敏感

**背外侧纹状体（DLS，壳核后外侧）→ 习惯行为**
- DLS 接受初级运动皮层/感觉运动皮层投射，经**黑质-纹状体多巴胺**建立**刺激-反应（S-R）联结**
- DLS 损毁→即使大量训练也无法形成习惯（Yin et al. 2004, PMID:14750976）
- 6-OHDA 耗竭黑质-纹状体 DA 通路 → 无法习惯化（Faure et al. 2005, PMID:15772337）
- 计算等价：**无模型（model-free）强化学习**，缓存 Q 值 + TD 误差更新，对结果贬值不敏感

**下边缘皮层（IL）的竞争仲裁角色**
- IL 通过腹侧纹状体主动抑制 PL-DMS 目标导向回路，使习惯系统主导
- Muscimol 暂时性灭活 IL → 习惯化大鼠恢复结果贬值敏感性（Coutureau & Killcross 2003, PMID:14643469）
- 核心推论：**习惯是"压制"目标导向，而非"消除"目标导向能力**

**人类神经影像学证据**
- Daw 等（2011）两步任务 fMRI：人类行为同时受 model-based 和 model-free 影响；腹侧纹状体 BOLD 编码两种预测误差（PMID:21435563）
- 人类壳核后外侧随习惯化训练激活增强（Tricomi 2009）；人类前尾状核编码动作-结果权变（Tanaka 2008）

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| DMS 对目标导向行为获得和表达必要 | 前/后训练 DMS 损毁均导致少量训练后习惯化 | Yin et al. 2005, PMID:16045504 | 高 |
| DLS 对习惯形成必要 | DLS 损毁→过度训练后仍对结果贬值敏感 | Yin et al. 2004, PMID:14750976 | 高 |
| 黑质-纹状体 DA 对习惯形成必要 | 6-OHDA 耗竭→无法习惯化 | Faure et al. 2005, PMID:15772337 | 高 |
| IL 主动压制目标导向系统 | IL Muscimol → 习惯化大鼠恢复目标导向 | Coutureau & Killcross 2003, PMID:14643469 | 高（大鼠） |
| 人类行为同时受 MB/MF 双系统影响 | 两步任务 fMRI + 腹侧纹状体 BOLD | Daw et al. 2011, PMID:21435563 | 中-高 |

## 连接

- [[medium-spiny-neuron]] — D1/D2 通路的细胞基础
- [[dopamine-reward-prediction-error]] — RPE 是基底节学习的第三因子
- [[interval-timing]] — 基底节是秒级计时核心
- [[striatal-beat-frequency]] — 纹状体计时的机制模型
- [[td-learning]] — 时序差分学习与基底节
- [[parkinson-disease]] — 多巴胺退化导致回路失衡与时间扭曲
- [[prefrontal-cortex]] / [[thalamus]] — 皮层-纹状体-丘脑环路
- [[foxp2]] — FOXP2在发育期调控纹状体MSN树突形态，支持言语运动程序化
- [[vocal-learning]] — 鸣禽纹状体（Area X）是发声学习前馈通路的关键节点
- [[childhood-apraxia-of-speech]] — FOXP2纹状体功能失调的主要临床后果
- [[circuits/basal-ganglia]] — 姊妹页：回路/疾病视角的更详细解剖
- [[striatal-direct-indirect-pathway]] — 两条通路的回路机制（今日新增详细页面）
- [[striatal-plasticity]] — 皮质-纹状体LTP/LTD的分子机制（今日新增页面）
- [[habitual-behavior]] — DLS 是习惯行为的解剖基底；IL 主动抑制目标导向以支持习惯控制
- [[goal-directed-behavior]] — DMS 是目标导向行为的解剖基底；PL/prelimbic 皮层对获得必要

## 未解问题

- **Q-bg-01**：D1 与 D2 通路在计时中的精确分工是什么？为何放电方向相反却协同累积时间证据——冗余、互补还是拮抗平衡？
- **Q-foxp2-01**（来自#111）：成体鸣禽Area X中FoxP2下调的上游触发机制是什么？多巴胺/BDNF/钙信号中哪个是触发器？

## 修订历史

- 2026-07-31 · 创建（systems 域首版，计时视角） · 基于《大脑的秒表》文章 #99 · 初始置信度：高
- 2026-08-12 · 修订 rev2 · 新增FOXP2与纹状体发育小节（MSN树突调控、人源化Foxp2效果、CAS机制、鸣禽Area X平行）· 来源：PMID:21765815, PMID:25225386, PMID:37137515 · related新增foxp2、vocal-learning、childhood-apraxia-of-speech；dimensions扩展至disease
- 2026-09-01 · 修订 rev3 · 新增证据表条目（ofMRI D1/D2激活脑网络效应PMID:27373834；DMS/DLS功能分离损伤实验PMID:31171839）；related新增medium-spiny-neuron、striatal-direct-indirect-pathway、striatal-plasticity；连接节新增姊妹页链接 · 来源：《纹状体的决策细胞》文章#131
- 2026-09-26 · 修订 rev4 · 新增DMS/DLS双系统功能分化小节（目标导向/习惯各自解剖、DA必要性、IL竞争仲裁、人类fMRI证据）及配套证据表；related新增habitual-behavior、goal-directed-behavior；key_sources新增PMID:14750976/16045504/19776734/21435563 · 来源：《自动驾驶的大脑》文章#156

## 来源文章

- [[2026-07-31-interval-timing-basal-ganglia-striatum]]
- [[2026-08-12-foxp2-language-genetics-development]]
- [[2026-09-01-medium-spiny-neurons-striatum]]

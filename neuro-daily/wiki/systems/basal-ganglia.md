---
title: 基底节
slug: basal-ganglia
domain: systems
type: structure
status: established
confidence: high
created: 2026-07-31
updated: 2026-07-31
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, behavior, cognition]
related: [dopamine-reward-prediction-error, interval-timing, striatal-beat-frequency, td-learning, parkinson-disease, prefrontal-cortex, thalamus]
prerequisites: [medium-spiny-neuron, dopamine-reward-prediction-error]
opens_questions: [Q-bg-01]
source_articles: [2026-07-31-interval-timing-basal-ganglia-striatum]
key_sources: ["PMID:21389235", "PMID:38918348", "PMID:35978564"]
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

## 连接

- [[medium-spiny-neuron]] — D1/D2 通路的细胞基础
- [[dopamine-reward-prediction-error]] — RPE 是基底节学习的第三因子
- [[interval-timing]] — 基底节是秒级计时核心
- [[striatal-beat-frequency]] — 纹状体计时的机制模型
- [[td-learning]] — 时序差分学习与基底节
- [[parkinson-disease]] — 多巴胺退化导致回路失衡与时间扭曲
- [[prefrontal-cortex]] / [[thalamus]] — 皮层-纹状体-丘脑环路
- [[circuits/basal-ganglia]] — 姊妹页：回路/疾病视角的更详细解剖

## 未解问题

- **Q-bg-01**：D1 与 D2 通路在计时中的精确分工是什么？为何放电方向相反却协同累积时间证据——冗余、互补还是拮抗平衡？

## 修订历史

- 2026-07-31 · 创建（systems 域首版，计时视角） · 基于《大脑的秒表》文章 #99 · 初始置信度：高

## 来源文章

- [[2026-07-31-interval-timing-basal-ganglia-striatum]]

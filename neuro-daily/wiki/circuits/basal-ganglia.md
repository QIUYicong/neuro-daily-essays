---
title: 基底节
slug: basal-ganglia
domain: circuits
type: structure
status: established
confidence: high
created: 2026-06-14
updated: 2026-06-14
revision_count: 1
dimensions: [microcircuit, brain-region, behavior, cognition]
related: [parkinsons-disease, dopamine-reward-prediction-error, three-factor-learning-rule, working-memory, engram-cells, pv-interneurons, disinhibitory-circuit]
prerequisites: [dopamine-reward-prediction-error, synaptic-transmission, ltp]
opens_questions: [Q-pd-beta-causality, Q-bg-habit-goal-split]
source_articles: [2026-06-14-parkinson-basal-ganglia-circuit]
key_sources: ["PMID:21469956", "PMID:2479133", "PMID:1695404", "PMID:2402638", "PMID:25065439"]
---

# 基底节 (Basal Ganglia)

> **一句话定义**：皮层下核团群（纹状体、苍白球、丘脑底核、黑质），通过直接通路（D1/dSPNs → GPi抑制 → 丘脑去抑制）和间接通路（D2/iSPNs → GPe → STN → GPi激活 → 丘脑抑制）相互拮抗地调控丘脑-皮层的运动输出，并在多巴胺奖励预测误差信号下实现动作选择学习。

## 当前理解

我们现在认为，基底节是一个**动态竞争与遴选**系统，其核心功能不只是运动控制，而是在多种候选行为（或认知状态）中通过直接/间接通路的相对强弱，选择最适当的行为方案并抑制竞争方案。

**经典框架（Albin-DeLong模型，1989-1990）**：
- 直接通路激活 → 运动"油门"
- 间接通路激活 → 运动"刹车"
- 两条通路的相对平衡决定"运动是否被允许"

**现代修正（Calabresi等，2014）**：
- 两条通路并非完全分离，有广泛的纹状体内侧支连接
- 多巴胺耗竭改变的不只是兴奋性状态，而是突触可塑性的全局格局
- 实际功能更接近"软竞争"而非严格的"油门/刹车"二元论

**振荡状态依赖性**：
- 正常多巴胺存在时：γ振荡主导，允许灵活运动规划
- 多巴胺缺失（PD）：β振荡主导，主动阻断运动发起
- 治疗（DA补充或DBS）：β→θ切换，恢复运动意图的实施

## 关键机制

### 核团解剖

| 核团 | 英文名 | 功能角色 | 主要递质 |
|------|-------|---------|---------|
| 纹状体（壳核+尾状核）| Striatum | 皮层/丘脑输入整合，两条通路的起点 | GABA（SPNs）|
| 伏隔核 | Nucleus accumbens | 腹侧纹状体，奖励动机 | GABA |
| 苍白球内节 | GPi | 主要输出，抑制丘脑 | GABA |
| 黑质网状部 | SNr | 另一输出门，抑制上丘/丘脑 | GABA |
| 苍白球外节 | GPe | 间接通路中继 | GABA |
| 丘脑底核 | STN | 唯一兴奋性核团，驱动GPi | 谷氨酸 |
| 黑质致密部 | SNc | 多巴胺来源，调节D1/D2平衡 | 多巴胺 |

### 直接通路（促进运动）

皮层→纹状体（dSPNs, D1受体, 物质P/强啡肽）→ **抑制** GPi/SNr → 丘脑去抑制 → 皮层激活 → 运动

多巴胺通过D1受体兴奋dSPNs（cAMP↑→PKA→L型Ca²⁺通道↑），增强直接通路。

### 间接通路（抑制运动）

皮层→纹状体（iSPNs, D2受体, 脑啡肽）→ **抑制** GPe → STN去抑制（**激活**）→ **激活** GPi/SNr → 丘脑抑制 → 皮层输入减少 → 运动受阻

多巴胺通过D2受体抑制iSPNs（cAMP↓→PKA↓），减弱间接通路。

### 超直接通路（快速制动）

皮层→STN（直接谷氨酸）→ GPi活化 → 丘脑全面抑制

功能：快速"取消"运动指令，参与stop-signal任务。

### 多巴胺的双重调节

SNc DA神经元的放电率编码奖励预测误差（RPE）。高RPE时（超出预期奖励）：
- D1激活 → 促进刚发生运动相关dSPNs的LTP → 巩固动作选择
- D2抑制 → 促进竞争性iSPNs的LTD → 减弱对应动作的"刹车"

低RPE时（低于预期）：反向。这是基底节作为三因素学习规则执行系统的基础（← 文章#15）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| D1/D2受体的dSPN/iSPN精确分离 | BAC转基因小鼠eGFP标记+膜片钳 | PMID:21469956 | 高 |
| STN过度活跃驱动PD运动减少症状 | MPTP猴STN损毁后症状逆转 | PMID:2402638 | 高 |
| 双通路失衡解释运动减少与运动过多 | 人类/灵长类病理和生理研究综合 | PMID:2479133, PMID:1695404 | 高 |
| 两通路实际上结构/功能相互交织 | 光遗传学同时激活实验；突触可塑性数据 | PMID:25065439 | 中 |

## 连接

- [[parkinsons-disease]] — DA神经元死亡导致基底节回路的范本性失衡
- [[dopamine-reward-prediction-error]] — SNc的RPE信号是基底节学习的"第三因子"
- [[three-factor-learning-rule]] — DA × dSPN/iSPN活动 = 基底节的三因素可塑性
- [[beta-oscillations]] — PD状态的病理振荡；正常基底节中被γ替代
- [[disinhibitory-circuit]] — 基底节-丘脑-皮层本质上是一个去抑制回路
- [[working-memory]] — 前额叶纹状体回路参与工作记忆和认知控制

## 未解问题

- Q-pd-beta-causality：β振荡是PD中回路失衡的直接原因还是伴生物？
- Q-bg-habit-goal-split：背外侧纹状体（习惯性学习）vs 背内侧纹状体（目标导向学习）的分工机制

## 修订历史

- 2026-06-14 · 创建 · 基于《多巴胺的沉默与节律的失控》一文 · 初始置信度：高

## 来源文章

- [[2026-06-14-parkinson-basal-ganglia-circuit]]

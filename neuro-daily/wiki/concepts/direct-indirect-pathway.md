---
title: 基底神经节直接/间接通路
slug: direct-indirect-pathway
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-06
updated: 2026-06-06
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, behavior]
related: [d1-d2-receptor-signaling, basal-ganglia, dopamine-reward-prediction-error, vta, substantia-nigra, habit-formation, parkinsons-disease, dopamine-systems-anatomy]
prerequisites: [synaptic-transmission, d1-d2-receptor-signaling, basal-ganglia]
opens_questions: [Q-direct-indirect-dynamic-balance, Q-direct-indirect-learning]
source_articles: [2026-06-06-dopamine-systems-anatomy]
key_sources: ["PMID:30716356", "PMID:24130517"]
---

# 基底神经节直接/间接通路 (Basal Ganglia Direct/Indirect Pathway)

> **一句话定义**：纹状体中型棘神经元（MSN）按多巴胺受体类型分为两类：D1-MSN 构成直接通路（纹状体→SNr/GPi→丘脑→皮层，净效果：促进运动），D2-MSN 构成间接通路（纹状体→GPe→STN→SNr/GPi→丘脑→皮层，净效果：抑制运动）；多巴胺通过同时激活 D1-MSN 和抑制 D2-MSN 来协调这两条通路、促进特定动作的选择与执行。

## 当前理解

我们现在认为，基底神经节通过直接/间接通路对立机制，在运动选择和学习中实现"Go/No-Go"的平衡竞争，而多巴胺信号通过 D1/D2 受体的对立效应来调节这一平衡。

**直接通路（Direct Pathway，"Go" 通路）**：
```
皮层（谷氨酸）→ 纹状体 D1-MSN（GABA，表达 dynorphin/substance P）
→ 黑质网状部（SNr）/苍白球内侧（GPi）→ 丘脑（去抑制）→ 皮层
```
- D1-MSN 激活 → SNr/GPi 被抑制（GABA）→ 丘脑去抑制 → 皮层兴奋 → **运动促进**
- 多巴胺（via D1R→Gs→cAMP↑）增强 D1-MSN 对皮层谷氨酸输入的响应 → **强化已选动作**

**间接通路（Indirect Pathway，"No-Go" 通路）**：
```
皮层（谷氨酸）→ 纹状体 D2-MSN（GABA，表达 enkephalin）
→ 苍白球外侧（GPe，GABA）→ 丘脑底核（STN，谷氨酸）
→ SNr/GPi（兴奋）→ 丘脑（抑制）→ 皮层
```
- D2-MSN 激活 → GPe 被抑制 → STN 去抑制（兴奋 SNr/GPi）→ 丘脑抑制 → **运动抑制**
- 多巴胺（via D2R→Gi→cAMP↓）抑制 D2-MSN 活性 → **解除 "No-Go" 制动**

**多巴胺的协同效应**：
当多巴胺释放增加时：
- D1-MSN（Go）被激活 → 直接通路增强
- D2-MSN（No-Go）被抑制 → 间接通路压制
- 净效果：选定动作获得"双重绿灯"——促进执行 + 压制竞争性抑制

这一机制解释了为什么多巴胺对运动既不是简单的"促进"也不是简单的"允许"，而是**选择性地放大已被皮层选定的动作，同时压制其他竞争动作**。

### 帕金森病：多巴胺耗竭后的通路失衡

SNc 神经元死亡 → 纹状体多巴胺严重耗竭 → ：
1. D1-MSN 失去激活 → 直接通路（Go）功能减弱
2. D2-MSN 失去抑制（D2R 持续处于"待激活"状态，但无多巴胺）→ 间接通路（No-Go）过度激活
3. 丘脑底核（STN）过度兴奋 → SNr/GPi 过度激活 → 丘脑被强烈抑制
4. 皮层运动输出减少 → 运动迟缓、强直、启动困难

β 振荡（13-30 Hz）在基底神经节（尤其是 STN 和 GPi）的异常同步是帕金森病的电生理标志，也是深部脑刺激（DBS）靶向 STN 的理论基础。

### 学习中的通路可塑性

直接/间接通路不是固定的"解剖硬件"，而是通过多巴胺依赖的三因素学习规则（pre × post × DA）动态调整各 MSN 的突触权重：
- 正奖励（DA 爆发）→ D1-MSN 与皮层输入的突触增强（LTP）→ 强化该选择
- 负奖励/惩罚（DA 抑制）→ D2-MSN 通路相对增强 → 压制该选择

这是基底神经节"演员（Actor）"功能的突触级实现（见 [[habit-formation]], [[actor-critic-model]]）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| D1-MSN 构成直接通路（dynorphin+），D2-MSN 构成间接通路（enkephalin+）| 免疫组化 + 在位杂交 + D1/D2 遗传标记 | PMID:24130517 | 确立 |
| 光遗传激活 D1-MSN 增加运动；激活 D2-MSN 抑制运动 | 光遗传 D1-Cre/D2-Cre 小鼠 + 行为测试 | 多实验室（Kravitz 2010, Natsuoka 2016 等）| 高 |
| DA 耗竭导致 STN 过度放电和 β 振荡 | 帕金森动物模型 + 电生理 | 多项研究 | 确立 |

## 连接

- [[d1-d2-receptor-signaling]] — 多巴胺通过 D1/D2 相反信号调控直接/间接通路的 MSN 活性
- [[basal-ganglia]] — 直接/间接通路是基底神经节信息流的核心计算逻辑
- [[dopamine-reward-prediction-error]] — RPE 信号通过 D1/D2 调控这两条通路的可塑性
- [[habit-formation]] — 习惯学习中多巴胺依赖的直接通路突触权重增加
- [[parkinsons-disease]] — 多巴胺耗竭 → 间接通路过度激活的直接临床后果

## 未解问题

- Q-direct-indirect-dynamic-balance：直接/间接通路的相对激活比例如何在实时行为中动态调整？是否存在 D1/D2-MSN 以外的第三类 MSN（表达 D1+D2 异聚体）？
- Q-direct-indirect-learning：直接通路 LTP 和间接通路 LTD 在同一行为学习中是否同步进行，还是有时间差分工？

## 修订历史

- 2026-06-06 · 创建 · 基于《奖励、运动与认知的统一信使》(#15) · 初始置信度：高

## 来源文章

- [[2026-06-06-dopamine-systems-anatomy]]

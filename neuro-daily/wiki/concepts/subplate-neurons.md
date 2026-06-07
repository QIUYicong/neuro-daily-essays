---
title: 下板神经元
slug: subplate-neurons
domain: concepts
type: structure
status: established
confidence: high
created: 2026-08-14
updated: 2026-08-14
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, cognition, disease]
related: [thalamocortical-axons, cortical-neurogenesis, cortical-layers, cortical-arealization, critical-period, synaptogenesis, cortical-interneuron-development]
prerequisites: [cortical-neurogenesis, cortical-layers, thalamocortical-axons]
opens_questions: [Q-tca-01, Q-subplate-01]
source_articles: [2026-08-14-thalamocortical-axons-guidance-sensory-maps]
key_sources: ["PMID:40745219", "PMID:38167425", "PMID:32659318"]
---

# 下板神经元 (Subplate Neurons)

> **一句话定义**：下板神经元是皮层发育中最早出生的神经元群（小鼠 E11-E13），位于皮层板下方的一过性结构（人类胎儿期下板尤为发达），通过与丘脑皮层轴突（TCA）形成皮层最早的谷氨酸能突触来主动调控 TCA 的等待时序、进皮层的分层选择与关键期的开启，最终在出生后数周内大量消亡。

## 当前理解

我们现在认为，下板神经元是皮层发育程序中一个"一次性的核心建筑工人"——它们完成了丘脑皮层布线的关键中转与时序调控任务后，大多数在出生后数周内凋亡，但其功能影响持久写入了已成形的皮层回路。

下板有三个关键功能：

1. **握手协同**：下板神经元在丘脑轴突到达之前就已发出皮层丘脑轴突（CTA）到达 PSPB；当 TCA 从对面赶来时，两者互用对方为脚手架，协同越过皮质-皮质下边界（握手假说）。

2. **等待区管理**：TCA 在 E15 前后进入下板，在那里建立早期突触并接受下板的调控，等待"放行"信号后才进入皮层板。下板神经元消融导致 TCA 无序过早侵入皮层。

3. **关键期触发**：下板与 TCA 之间的早期突触活动，通过激活皮层内的 L5b SST 中间神经元，形成一个瞬时的"脚手架回路"（scaffold circuit），帮助建立 L4 的正式连接架构，是关键期开启的上游事件之一。

在**人类胎儿大脑**中，下板尤为发达（妊娠 15-34 周峰值），其体积在高峰期甚至超过皮层板本身——反映了人类大脑长时程发育需要更复杂的中转机制。下板的异常与早产儿脑损伤（白质损伤）以及神经发育疾病（ASD、精神分裂症）有关联。

## 关键机制

### 下板的三亚层组织（Kostović 2020）

| 亚层 | 位置 | 功能 |
|------|------|------|
| 深下板（入侵区）| 最深，靠近白质 | TCA 入侵区，轴突进入皮层的入口 |
| 中下板（导航区）| 中间 | TCA 路径整合与分拣中心 |
| 浅下板（等待区）| 靠近皮层板 | TCA 等待并建立早期突触的区域 |

### 时序调控逻辑

```
E11-E13（小鼠）: 下板神经元出生（皮层最早）
E12: TCA 从丘脑出发
E15: TCA 抵达皮层，进入下板等待区
E15-P0: 下板-TCA 早期突触形成（皮层最早的谷氨酸能突触）
P0前后: 停止信号解除 → TCA 开始侵入皮层板
P4-P7: 下板-L5b SST 中间神经元暂时性回路激活
P10-P15: L4 正式连接完成，下板大量凋亡
```

### 握手假说中的作用

下板神经元→CTA（皮质-丘脑轴突）先于TCA到达PSPB；TCA到达PSPB时借用CTA作为引导轨道；CTA同时借用TCA轨道延伸回丘脑。

**遗传证据**（Molnár & Kwan 2024）：
- *Arid1a*（Emx1-Cre）敲除：下板神经元发育缺陷 → TCA 无法越过 PSPB
- *Arid1a*（hGFAP-Cre）敲除：下板已形成后才失去 Arid1a → PSPB 越过正常
- → 下板神经元的 Arid1a 表达是 TCA 越界的充要条件

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 下板神经元是皮层最早出生的 | 出生日期标记（BrdU）+ 单细胞测序 | PMID:40745219（综述） | 高 |
| 下板神经元消融→TCA 无序侵入皮层 | 免疫毒素选择性消融 | 经典实验（多篇综述引用） | 高 |
| 握手假说的遗传证据 | Arid1a Emx1-Cre vs hGFAP-Cre 对比 | PMID:38167425 | 高 |
| 人类下板在 GW13-15 出现双层化，到 GW30-34 峰值 | 人类胎儿大脑尸检组织化学 | PMID:32659318（Kostović 2020） | 高 |
| 下板异常与白质损伤/ASD/精神分裂相关 | 临床病理和影像学研究 | PMID:32659318 | 中（相关性，非因果） |

## 连接

- [[thalamocortical-axons]] — 下板是 TCA 的等待宿主；两者建立皮层最早的谷氨酸能突触
- [[cortical-neurogenesis]] — 下板神经元是 Inside-Out 规则的最底层：最早出生，位置最深（下板），不进入皮层板
- [[cortical-layers]] — 下板在出生后消亡，其空间被成熟的 Layer 6 下方白质取代
- [[cortical-arealization]] — 下板发出的 CTA 携带皮层区域身份信息，与 TCA 在 PSPB 握手时传递区域导向
- [[critical-period]] — 下板瞬时回路的激活是关键期开启的上游事件
- [[synaptogenesis]] — 下板-TCA 突触是皮层中时序上最早的突触形成场所

## 未解问题

- **Q-tca-01**（高）：TCA 等待期的"停止-放行"分子信号身份？（与此条 Q 共享）
- **Q-subplate-01**（中）：人类早产儿（GW25-30 出生）脑损伤优先累及下板，与 ASD/CP 风险的因果关系是什么？下板特异性保护策略是否可行？

## 修订历史

- 2026-08-14 · 创建 · 基于《感觉世界的有线传输》（文章 #113）· 初始置信度：高

## 来源文章

- [[2026-08-14-thalamocortical-axons-guidance-sensory-maps]]

---
title: 跨胼抑制
slug: transcallosal-inhibition
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-26
updated: 2026-09-26
revision_count: 1
dimensions: [cellular, synaptic, microcircuit, brain-region]
related: [corpus-callosum, interhemispheric-competition, motor-cortex, dorsal-attention-network, myelination]
prerequisites: [corpus-callosum, inhibitory-interneurons, myelination]
opens_questions: [Q-cc-02]
source_articles: [2026-09-26-corpus-callosum-anatomy-splitbrain]
key_sources: ["PMID:28381485/PMC5494372", "PMID:23800346/PMC3695846", "PMID:25550994/PMC4278150"]
---

# 跨胼抑制 (Transcallosal Inhibition)

> **一句话定义**：胼胝体轴突终止于对侧皮层的抑制性中间神经元，减少对侧皮层兴奋性输出，维持单侧运动/注意的精确性并实现半球间竞争。

## 当前理解

跨胼抑制（transcallosal inhibition, TCI）是胼胝体功能的重要组成部分，约 30–40% 的胼胝体轴突终止于对侧皮层的抑制性中间神经元（而非兴奋性锥体细胞），通过这些中间神经元减少对侧皮层的净兴奋性输出。这意味着胼胝体不只是"传递信息"，而是主动**抑制对侧**以维持功能特化与偏侧化。

在运动控制中，跨胼抑制确保单侧肢体运动时对侧运动皮层的兴奋性被抑制，防止"镜像运动"（不需要的对侧肢体运动）。在注意系统中，它是半球间竞争的物理基础——活跃半球的 DAN 通过胼胝体抑制对侧半球，实现空间注意偏侧化。

其成熟程度可通过 TMS-iSP（同侧静默期）范式精确量化，且具有发育轨迹和老化变化。

## 关键机制

### TMS-iSP 范式

**同侧静默期（ipsilateral silent period, iSP）**：
1. 受试者主动收缩目标手（如右手握拳）
2. TMS 刺激**同侧**运动皮层（右侧 M1）
3. 信号通过胼胝体→对侧抑制性中间神经元→对侧 M1 被抑制
4. EMG 记录到左手肌肉短暂的活动中断（iSP）

**参数**：
- iSP 潜伏期：~35–40 ms（反映胼胝体传导速度）
- iSP 持续时长：~14–16 ms（左右半球相近）
- iSP 面积：抑制深度的综合指标

### 发育轨迹

随胼胝体髓鞘化成熟（Ciechanski et al., 2017, PMC5494372）：
- iSP 潜伏期随年龄缩短（10–18岁，r=−0.631，p=0.005）
- iSP 抑制强度随年龄增加（r=0.488，p=0.040）
- 女孩比男孩成熟约快 5 ms（p=0.002）
- iSP 与手部精细运动成绩（Purdue Pegboard）正相关

### 老化衰减

（Davidson & Tremblay, 2013, PMC3695846）：
- 老年人（~73岁）iSP 面积减少 **57%**（vs 年轻人）
- 胼胝体传导时间延长
- 与手部精细运动下降直接相关
- 遵循"后进先出"规律（最晚髓鞘化的前部连接最先退化）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| iSP 潜伏期随年龄缩短（r=−0.631） | TMS-iSP，n=19，10–18岁 | PMID:28381485 (PMC5494372) | 中（小样本横断面） |
| 老年人 iSP 面积减少 57% | TMS-iSP，老年vs年轻 | PMID:23800346 (PMC3695846) | 中（横断面） |
| 女孩 iSP 潜伏期比男孩短 5 ms（p=0.002） | TMS-iSP | PMID:28381485 (PMC5494372) | 中（小样本） |
| iSP 与精细运动成绩相关 | TMS + Pegboard | PMID:28381485 (PMC5494372) | 中 |
| 跨胼抑制衰减与老年运动能力下降相关 | TMS + 运动测试 | PMID:23800346 (PMC3695846) | 中 |

## 连接

- [[corpus-callosum]] — 跨胼抑制的解剖基础（胼胝体纤维终止于抑制性中间神经元）
- [[interhemispheric-competition]] — 跨胼抑制是半球间竞争的物理机制
- [[motor-cortex]] — 运动控制中的跨胼抑制（单侧运动精确性）
- [[inhibitory-interneurons]] — 信号终止的细胞类型
- [[myelination]] — 决定传导速度和发育时序

## 未解问题

- Q-cc-02：胼胝体发育可塑性关键期何时关闭？
- 跨胼抑制是否在空间注意（DAN-VAN 竞争）中也能被 TMS-iSP 直接测量？
- 老龄跨胼抑制减弱是否可以通过训练或 tDCS 干预减缓？

## 修订历史

- 2026-09-26 · 创建 · 基于《连接两个大脑》一文 · PMC5494372、PMC3695846 开放全文 · 初始置信度：高

## 来源文章

- [[2026-09-26-corpus-callosum-anatomy-splitbrain]]

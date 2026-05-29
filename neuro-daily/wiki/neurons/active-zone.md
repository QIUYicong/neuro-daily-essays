---
title: 活动区
slug: active-zone
domain: neurons
type: structure
status: established
confidence: high
created: 2026-05-25
updated: 2026-06-01
revision_count: 2
dimensions: [molecular, cellular, synaptic]
related: [synaptic-transmission, SNARE-complex, synaptotagmin, voltage-gated-calcium-channels, RIM-protein]
prerequisites: [synaptic-transmission]
opens_questions: [Q-active-zone-plasticity, Q-active-zone-heterogeneity]
source_articles: [2026-05-25-synaptic-vesicle-exocytosis, 2026-06-01-voltage-gated-calcium-channels]
key_sources: ["PMID:22026965", "PMID:27537483", "PMID:36544543", "PMID:22183436", "PMID:25674049"]
---

# 活动区（Active Zone）

> **一句话定义**：活动区是突触前终末中一块电子密度极高的特化膜区域，由多种骨架蛋白构建的纳米级脚手架将电压门控钙通道与就绪态突触囊泡精确定位于同一位置，是突触囊泡融合的唯一发生地点。

## 当前理解

活动区是突触效率的物理基础。其核心设计原则是**纳米级空间预组织**：在动作电位到达之前，钙通道和就绪囊泡已经就位于最优距离，使钙进入后能在局部迅速达到触发Synaptotagmin的浓度（微摩尔至百微摩尔级）。

**核心骨架蛋白（PMID:22026965）：**
- **RIM蛋白（Rab3-interacting molecules）**：活动区的核心组织者
  - α-RIM含：Rab3结合域（与囊泡GTP酶相互作用）、锌指域（与Munc13 C2A域结合，激活Munc13）、PDZ域（直接结合N/P/Q型钙通道C末端；结合ELKS蛋白）、两个C端C2域
  - RIM蛋白是将"钙通道""囊泡""启动机器"连接于同一纳米位置的枢纽
- **CAST/ELKS**：与RIM的PDZ域结合，维持活动区物理完整性
- **Bassoon和Piccolo**：大型骨架蛋白，维持活动区在高频重复刺激下的稳定
- **RIM-BP（RIM结合蛋白）**：连接RIM与钙通道的额外桥梁

**功能：**
1. 将钙通道锚定于活动区（RIM直接结合钙通道C末端）
2. 通过RIM-Munc13互动激活启动蛋白，促进囊泡进入RRP
3. 连接囊泡（via Rab3-RIM）与释放机器

**活动区丧失的后果（PMID:27537483）：**
RIM+ELKS双敲除后：
- 突触囊泡停泊（docking）几乎消失
- 活动区钙通道减少44%
- 单动作电位触发的释放概率急剧降低
- 但：高渗蔗糖仍能触发释放（说明存在游离的"融合能力囊泡"）

结论：活动区不是囊泡获得融合能力的必要条件，但**对于动作电位诱发的高效快速释放至关重要**。

## 关键机制

### 纳米域耦合
不同突触的钙通道-囊泡距离高度异质性：
- **纳米域耦合**（<100 nm，通常10-30 nm）：钙通道（CaV2.1/P/Q型或CaV2.2/N型）与Synaptotagmin极近，单通道开放即可触发释放，释放概率高，对快速钙螯合剂BAPTA敏感但对慢速螯合剂EGTA不敏感
- **微域耦合**（>100 nm）：需多个通道协同钙流，释放概率较低，BAPTA和EGTA均可影响

**量化数据（来自实验测量和模拟）**：
- 海马篮状细胞突触：~10–20 nm（纳米域）（PMID:22183436，PMC3617475）
- 成熟颈静脉复合体（P16-18）：~23 nm，约9个通道/活动区，纯P/Q型（PMID:25674049，PMC4306312）
- 未成熟颈静脉复合体（P8-12）：~61 nm，需N型+P/Q型共同参与（微域）

**发育性转变**：突触成熟时从微域（~60 nm，N+P/Q型）转变为纳米域（~20 nm，纯P/Q型），由Septin-5调控。这一转变使触发时间提前约410 μs，赋予成熟突触更高的时间精度。

这种异质性由RIM/RIM-BP/CAST/ELKS和neurexin的精确组织决定（PMID:36544543），并直接影响短时程突触可塑性特征。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| RIM直接结合钙通道C末端，锚定通道于活动区 | PDZ域-通道C末端共沉淀；RIM敲除→通道丢失 | PMID:22026965 | 高 |
| 活动区脚手架丧失→停泊消失但融合能力保留 | RIM+ELKS双敲除小鼠电生理+形态学 | PMID:27537483 | 高 |
| 通道-囊泡距离决定释放概率 | 超分辨成像 + 钙螯合剂实验 | PMID:36544543 | 高 |

## 连接

- [[synaptic-transmission]] — 活动区是突触传递的物理平台
- [[voltage-gated-calcium-channels]] — CaV2.1（P/Q型）和CaV2.2（N型）通道在活动区内以纳米域精度与囊泡融合位点耦合
- [[SNARE-complex]] — SNARE在活动区组装执行融合
- [[synaptotagmin]] — Syt在活动区处感应局部Ca²⁺信号

## 未解问题

- Q-active-zone-plasticity：活动区大小和分子组成是否可在活动依赖方式下重塑？如何影响突触可塑性？
- Q-active-zone-heterogeneity：同一神经元的不同突触之间，活动区结构的异质性有多大？其功能意义是什么？

## 修订历史

- 2026-05-25 · 创建 · 基于《神经信号的化学渡口》一文 · 初始置信度：高
- 2026-06-01 · 修订 · 基于《神经元的三重钙门》一文 · 补充纳米域耦合量化数值（10-20 nm至23 nm）、P/Q型vs N型在不同成熟阶段的分布、发育性转变（septin-5调控）；更新连接指向正确的voltage-gated-calcium-channels节点

## 来源文章

- [[2026-05-25-synaptic-vesicle-exocytosis]]
- [[2026-06-01-voltage-gated-calcium-channels]]

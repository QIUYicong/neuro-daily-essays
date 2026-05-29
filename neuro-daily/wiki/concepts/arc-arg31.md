---
title: Arc/Arg3.1（活动调控的细胞骨架相关蛋白）
slug: arc-arg31
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-04
updated: 2026-06-04
revision_count: 1
dimensions: [molecular, synaptic, cellular, cognition]
related: [ltd, ltp, ampa-receptor, memory-consolidation, engram-cells, mglur-ltd]
prerequisites: [synaptic-transmission, ampa-receptor, ltp, ltd]
opens_questions: [Q-arc-ltp-ltd-switch, Q-arc-dendritic-targeting]
source_articles: [2026-06-04-ltd-long-term-depression]
key_sources: ["PMID:19690847", "PMID:25429259", "PMID:24183021"]
---

# Arc/Arg3.1（活动调控的细胞骨架相关蛋白）

> **一句话定义**：神经活动即早表达的树突蛋白，作为突触活动的"量规"，在 LTD 中通过与 dynamin/endophilin 结合促进 AMPA 受体内吞，在 LTP 中参与肌动蛋白稳定和记忆巩固，双向调节突触强度。

## 当前理解

我们现在认为，Arc/Arg3.1 是一个突触活动的多功能调节器，而非单向效应蛋白。Arc 的 mRNA 在神经元激活后数分钟内从核运输出去，沿树突分布，在**活动的突触棘局部翻译**——这一特性使 Arc 成为"突触标记"分子，在正确的地点、正确的时间产生，响应局部突触活动。

Arc 的功能因其产生背景（活动强度、时间窗口）而异：
- **mGluR 激活/中等活动（LTD 情境）**：Arc 与 dynamin 和 endophilin 结合 → 促进网格蛋白介导的 AMPAR 内吞 → 突触减弱
- **强烈活动（LTP 巩固情境）**：Arc 激活 PAK → 磷酸化 LIMK → 抑制 cofilin → 稳定棘内肌动蛋白 → 支持 L-LTP 的树突棘结构维持
- **持续高活动（稳态情境）**：Arc 积累驱动 AMPAR 内吞，防止突触过度增强，实现突触稳态下调（synaptic scaling down）

Arc 的"双向"功能使它成为大脑活动感知系统的一部分：它感知活动的量，并将感知结果转化为对应的突触强度调整。这与 LTP 和 LTD 的 BCM 双向框架紧密契合。

## 关键机制

### 基因与蛋白结构

- **基因**：*Arc*（小鼠）= *Arg3.1*（大鼠），即早基因（IEG），依赖活动诱导表达
- **蛋白结构**：含 N 端 NHD 结构域（与 dynamin 结合）和 C 端 CCD 结构域（参与多聚化）
- **mRNA 的特殊性**：Arc mRNA 含去稳定元件（ARE），半衰期短（~30 min）；同时含特殊的 3'UTR，驱动树突靶向运输

### Arc 在 LTD 中的作用

mGluR5 激活 → ERK 磷酸化激活 → FMRP 翻译抑制解除 → Arc mRNA 局部翻译 → Arc 蛋白在激活的树突棘出现
→ Arc 与 **dynamin**（GTPase，驱动囊泡颈部断裂）结合
→ Arc 与 **endophilin**（弯曲膜脂质，形成网格蛋白囊泡管状结构）结合
→ 两者共同加速网格蛋白包被小泡的形成和分裂
→ AMPAR 内吞效率提高 → 突触表面 AMPAR 减少 → LTD

### Arc 在 LTP 巩固中的作用

高频刺激/高 Ca²⁺ → BDNF-TrkB 信号 → Arc 表达升高 → Arc 激活 PAK1（p21 激活激酶）→ PAK1 磷酸化 LIMK1/2 → LIMK 磷酸化抑制 cofilin（actin 切割蛋白）→ 棘内肌动蛋白稳定聚合 → 树突棘结构持久放大 → L-LTP 维持

### Arc 与突触稳态

慢性过高活动 → Arc 积累 → 广泛 AMPAR 内吞 → 突触稳态性降低（synaptic scaling down）→ 防止网络过度激活/饱和

这一机制可能与睡眠期间突触权重整体下调相关（SHY 假说）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| Arc mRNA 快速运输到激活树突并局部翻译 | 荧光原位杂交（FISH）+ 多聚核糖体分析 | PMID:19690847 (PMC2803749) | 高 |
| Arc 敲除小鼠 LTP 可诱导但不能巩固（L-LTP 缺损） | Arc -/- 小鼠海马切片电生理；Morris 水迷宫学习正常但记忆保留受损 | PMID:19690847 (PMC2803749) | 高 |
| Arc 与 dynamin/endophilin 结合驱动 AMPAR 内吞 | Arc 截断突变体（NHD 缺失）无法促进内吞；共免疫沉淀证实直接结合 | PMID:25429259 (PMC4150421) | 中-高 |
| Arc 过表达导致 AMPAR 内吞增加、突触传递减弱 | 转染过表达 Arc 的神经元基础 EPSC 降低 | PMID:19690847 (PMC2803749) | 高 |

## 连接

- [[ltd]] — Arc 是 mGluR-LTD 的核心执行蛋白；与 dynamin/endophilin 形成内吞复合体
- [[ltp]] — Arc 参与 L-LTP 巩固（肌动蛋白稳定）；与 LTD 功能形成活动量依赖的双向关系
- [[ampa-receptor]] — Arc 直接驱动 AMPAR 网格蛋白内吞，是受体从突触移除的关键连接者
- [[memory-consolidation]] — Arc 敲除的记忆巩固缺损说明 Arc 是将 LTP 转化为持久记忆的关键分子
- [[engram-cells]] — Arc 标记活跃神经元（用于 ArcCreERT2 等印迹捕获工具）；Arc 表达量可能区分印迹细胞与非印迹细胞

## 未解问题

- Q-arc-ltp-ltd-switch：同一细胞中，Arc 如何"决定"促进 LTP（肌动蛋白稳定）还是促进 LTD（AMPAR 内吞）？活动量？局部 Ca²⁺ 的精确水平？时间窗口？
- Q-arc-dendritic-targeting：Arc mRNA 被运输到特定的激活树突棘的分子机制是什么？参与运输的 RNA 结合蛋白和运动蛋白是哪些？

## 修订历史

- 2026-06-04 · 创建 · 基于《遗忘的精准：LTD 文章》· 初始置信度：高

## 来源文章

- [[2026-06-04-ltd-long-term-depression]]

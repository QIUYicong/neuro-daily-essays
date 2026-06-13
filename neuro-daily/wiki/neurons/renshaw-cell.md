---
title: Renshaw 细胞
slug: renshaw-cell
domain: neurons
type: structure
status: established
confidence: high
created: 2026-06-13
updated: 2026-06-13
revision_count: 1
dimensions: [cellular, microcircuit]
related: [stretch-reflex, alpha-motor-neuron, ia-inhibitory-interneuron, spinal-cord-cpg]
prerequisites: [synaptic-transmission, alpha-motor-neuron]
opens_questions: []
source_articles: [2026-06-13-stretch-reflex-arc]
key_sources: ["PMID:26446220", "PMID:16716488", "PMID:11351007"]
---

# Renshaw 细胞 (Renshaw Cell)

> **一句话定义**：脊髓腹角的特殊甘氨酸能抑制性中间神经元，接收 α 运动神经元轴突侧支的兴奋（胆碱能），并反馈性地抑制同名及协同肌的 α-MN（**复现抑制**）和 Ia 抑制性中间神经元，构成运动神经元输出的自我限制负反馈回路。

## 当前理解

我们现在认为，Renshaw 细胞是脊髓运动回路中最独特的结构之一：它是已知唯一受 α-MN 轴突侧支直接驱动的中间神经元，其功能是实现运动系统的"输出-依赖性制动"——运动神经元放电越多，Renshaw 细胞被激活越强，对该运动神经元的抑制也越强。

Renshaw 细胞的功能意义有两种有些对立的解释：

1. **输出规范化假说**：Renshaw 细胞限制单个运动神经元的最高放电率，防止振荡或不稳定放电；同时可能对运动神经元池的输出进行归一化（使大的运动神经元不会持续压制小的）

2. **共收缩解除器假说**：Renshaw 细胞通过抑制 Ia-INs，间接减弱互反抑制，允许主动肌和拮抗肌同时收缩（关节刚性化），这在需要精细稳定性的任务中很重要

Moore 等（2015，PMC4464588）用光遗传学方法确认了 Renshaw 细胞的突触连接组织：单个 Renshaw 细胞接受来自多个运动神经元的 axon collateral 输入，并将甘氨酸能抑制广播给多个运动神经元，具有明显的"汇聚-发散"结构。

## 关键机制

- **位置**：脊髓腹角最腹侧区（Rexed IX 层内或邻近区域）
- **输入**：α-MN 轴突侧支（兴奋性，乙酰胆碱 nAChR）
- **输出**：
  - 同名肌 α-MN → 甘氨酸能 IPSP（复现抑制）
  - Ia-INs → 甘氨酸能 IPSP（减弱互反抑制 → 允许共收缩）
- **化学特征**：甘氨酸（主要）+ GABA（部分），Calbindin 阳性（标志物）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Renshaw 细胞实现复现抑制 | 原始描述：电生理+解剖 | Renshaw 1941; Eccles 1954 | 极高（历史） |
| 突触连接的汇聚-发散结构 | 光遗传学激活+全细胞记录 | Moore et al. 2015, PMC4464588 | 高 |
| Renshaw 细胞抑制 Ia-INs | 细胞内记录 | Hultborn 2001, PMC2278613 | 高 |

## 连接

- [[stretch-reflex]] — Renshaw 细胞提供复现抑制，是牵张反射回路的增益制动
- [[alpha-motor-neuron]] — 双向关系：α-MN 驱动 Renshaw，Renshaw 抑制 α-MN
- [[ia-inhibitory-interneuron]] — Renshaw 细胞抑制 Ia-INs，可解除互反抑制以允许共收缩
- [[spinal-cord-cpg]] — 步态 CPG 通过调控 Renshaw 细胞来切换互反抑制/共收缩模式

## 修订历史

- 2026-06-13 · 创建（rev1）· 基于文章 #179《脊髓最短捷径》· 初始置信度：高

## 来源文章

- [[2026-06-13-stretch-reflex-arc]]

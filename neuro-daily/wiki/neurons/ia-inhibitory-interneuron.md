---
title: Ia 抑制性中间神经元
slug: ia-inhibitory-interneuron
domain: neurons
type: structure
status: established
confidence: high
created: 2026-06-13
updated: 2026-06-13
revision_count: 1
dimensions: [cellular, microcircuit]
related: [stretch-reflex, alpha-motor-neuron, renshaw-cell, spinal-cord-cpg, spinal-interneurons-locomotion, corticospinal-tract]
prerequisites: [synaptic-transmission, alpha-motor-neuron, muscle-spindle]
opens_questions: [Q-stretch-01]
source_articles: [2026-06-13-stretch-reflex-arc]
key_sources: ["PMID:13396937", "PMID:11351007", "PMID:16716488"]
---

# Ia 抑制性中间神经元 (Ia Inhibitory Interneuron, Ia-IN)

> **一句话定义**：脊髓腹角的甘氨酸能中间神经元，接收 Ia 传入纤维的单突触兴奋性输入，并向**拮抗肌** α 运动神经元传递 IPSP，实现互反抑制（reciprocal inhibition）——确保主动肌收缩时拮抗肌自动放松。

## 当前理解

我们现在认为，Ia-INs 是牵张反射回路中互反抑制的专用中介，其发现（Eccles, Eccles & Lundberg 1956，PMID:13396937）是揭示脊髓抑制性回路细胞机制的里程碑。

Ia-INs 本身接受多种输入的汇聚：不仅来自 Ia 纤维，还接收来自 Renshaw 细胞的抑制（从而允许共收缩时解除互反抑制）、来自 α-MN 的间接激活（通过 Renshaw 细胞的去抑制），以及来自皮质脊髓束、网状脊髓束的下行调控。这种多输入汇聚使 Ia-INs 成为 Hultborn（2001）所说的"功能单元"的一部分，其激活状态决定了互反抑制的强度是增强还是削弱。

特别重要的是：Ia-INs 的活跃程度在不同运动状态下差异巨大：
- **站立/姿势维持**：Ia-INs 活跃，互反抑制强 → 主动肌和拮抗肌清晰分工
- **共收缩（关节刚性化）**：Renshaw 细胞通过抑制 Ia-INs 来削弱互反抑制，允许主动肌和拮抗肌同时收缩

## 关键机制

- **位置**：脊髓腹角，Rexed VII 层（中间带区域）
- **神经递质**：甘氨酸（glycine）→ GlyR 介导 IPSP
- **输入**：Ia 传入（兴奋性，谷氨酸/AMPA）；Renshaw 细胞（抑制性，甘氨酸）；下行通路（兴奋性或抑制性）
- **输出**：拮抗肌 α-MN（抑制性）；可能也投射到协同肌的 α-MN

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Ia-IN 介导互反抑制 | 细胞内记录+反向刺激去除 Ia-IN 输入 | Eccles et al. 1956, PMID:13396937 | 极高 |
| Renshaw 细胞抑制 Ia-IN | 细胞内记录；薄切片 | Hultborn 2001, PMC2278613 | 高 |
| 下行通路调控 Ia-IN 的互反抑制强度 | H反射双脉冲测试 | Knikou 2008, PMID:18394711 | 中-高 |

## 连接

- [[stretch-reflex]] — Ia-IN 是互反抑制通路的核心中介
- [[alpha-motor-neuron]] — 输入来源（Ia 纤维分支）及抑制目标（拮抗肌α-MN）
- [[renshaw-cell]] — Renshaw 细胞抑制 Ia-IN，允许共收缩
- [[spinal-cord-cpg]] — 步态 CPG 通过调控 Ia-IN 实现状态依赖性互反抑制模式切换
- [[corticospinal-tract]] — 皮质脊髓束通过 Ia-INs 调节随意运动时的互反抑制模式

## 未解问题

- Q-stretch-01：人类 Ia-INs 的功能特性与猫是否完全一致？（无直接人类细胞内记录）

## 修订历史

- 2026-06-13 · 创建（rev1）· 基于文章 #179《脊髓最短捷径》· 初始置信度：高

## 来源文章

- [[2026-06-13-stretch-reflex-arc]]

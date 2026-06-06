---
title: 运动学习
slug: motor-learning
domain: concepts
type: concept
status: established
confidence: high
created: 2026-08-08
updated: 2026-08-08
revision_count: 1
dimensions: [behavior, cognition, microcircuit, brain-region, synaptic, cellular]
related: [cerebellum, deep-cerebellar-nuclei, inferior-olive, cerebellar-ltd, climbing-fiber-error-signal, purkinje-cell, motor-cortex, basal-ganglia, ltp, ltd, memory-consolidation, predictive-coding]
prerequisites: [cerebellum, ltp, ltd, cerebellar-ltd]
opens_questions: [Q-dcn-01, Q-dcn-03]
source_articles: [2026-08-08-deep-cerebellar-nuclei-motor-learning-circuit]
key_sources: ["PMID:9378587", "PMID:23440175", "PMID:19684593", "PMID:21482355", "PMID:29643480"]
---

# 运动学习（Motor Learning）

> **一句话定义**：通过重复练习和误差反馈改善运动技能表现的过程，在神经科学层面由小脑（皮层 LTD + 深部核团 LTP）和基底神经节（多巴胺奖励强化）共同实现，前者负责误差驱动的精度适应，后者负责奖励驱动的习惯固化。

## 当前理解

运动学习是神经科学中理解最深入的学习类型之一，因为它有两大优势：可精确量化（运动误差的大小、方向、时序），且有直接因果可操作的动物模型（眼跳适应、VOR 适应、眼眨条件反射）。

我们现在认为，运动学习在神经回路层面由**两个相对独立的系统**实现：

**1. 小脑误差驱动学习**：对"运动结果与预期的差异"（误差）进行监督式纠正，使运动精度提高。依赖 IO-CF 误差信号驱动 PC 的 LTD，随后在 DCN 完成记忆巩固（两相模型）。适用于：运动适应（如新工具、扰动适应）、定时精度学习（条件反射）、眼动适应。

**2. 基底神经节奖励强化学习**：对"运动结果的奖励/惩罚"进行强化，逐渐固化为习惯。依赖多巴胺奖励预测误差信号驱动纹状体的 D1/D2 通路权重变化。适用于：技能学习的初始阶段（获取）、习惯固化、运动序列自动化。

这两个系统并非完全独立——小脑与基底神经节之间存在皮层下直接连接（Bostan & Strick 2018，PMID:29643480），提示两者在整合运动控制与评价信号方面有直接交流。

## 关键机制

### 小脑运动学习的两相模型（Ito 2013，PMID:23440175）

**第一相（分钟到数小时）**：小脑皮层快速适应
- IO 在运动误差出现后放电 → CF 激活 PC 复杂放电
- CF（稀疏 ~1 Hz）与先前 PF（CS 通道）的时序重叠 → PF-PC LTD
- PC 在特定情境下放电减少 → DCN 去抑制 → 运动输出产生

**第二相（数小时到数天）**：DCN 记忆巩固
- PC 持续对 DCN 的抑制减少
- MF-DCN 突触因 NMDA 受体激活增加而发生 LTP
- 记忆固化在 DCN：即使 IO 被灭活，已巩固 CR 仍表达

### 运动学习经典实验范式

| 范式 | 物种 | CS | US | CR | 关键 DCN 核团 |
|------|------|----|----|----|----|
| 眼眨条件反射 | 兔/鼠 | 纯音 | 角膜气流 | 预期性眨眼 | 间位核（前部）|
| VOR 适应 | 鼠/猴 | 头动 | 视觉错位 | 调整 VOR 增益 | 绒球/前庭核 |
| 眼跳适应 | 猴/人 | 眼跳目标 | 视网膜滑移 | 改变眼跳幅度 | 绒球/小叶 |

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 前间位核损毁选择性消除 CR（不影响 UR）| 利多卡因灭活；多物种 | PMID:9378587 | 极高 |
| 充分巩固后 IO 灭活不影响 CR 表达 | 训练后 IO muscimol 注射 | PMID:19684593 | 高 |
| 阻断小脑皮层 LTD 不影响多种运动学习任务 | 三种 AMPAR 内吞阻断突变小鼠 | PMID:21482355 | 高 |
| 小脑-基底神经节有直接皮层下连接 | 灵长类逆向追踪 | PMID:29643480 | 高 |

## 连接

- [[cerebellum]] — 小脑皮层（PC LTD）是运动学习的快速适应阶段
- [[deep-cerebellar-nuclei]] — DCN 是运动记忆的长期存储与输出门控
- [[inferior-olive]] — IO 提供误差驱动学习所需的教师信号（CF）
- [[cerebellar-ltd]] — 小脑皮层运动学习的核心突触机制
- [[climbing-fiber-error-signal]] — CF 是 Marr-Albus-Ito 监督学习的误差通道
- [[memory-consolidation]] — 小脑皮层→DCN 的两相记忆转移，类比海马→新皮层系统巩固
- [[habit-formation]] — 习惯形成是运动学习的另一极（奖励驱动，基底神经节依赖）
- [[ltp]] — DCN 的苔藓纤维 LTP 是运动记忆巩固的细胞机制

## 未解问题

- **Q-dcn-01**：人类技能学习（如演奏乐器）中，小脑皮层 LTD 与 DCN LTP 的时间进程各多长？能否通过 cerebellar fMRI 分辨？
- **Q-dcn-03**：小脑认知功能（CCAS）的学习是否也走两相模型（皮层 → 核团巩固）？

## 修订历史

- 2026-08-08 · 创建 · 基于《深部核团的门与教师》（文章#107）· 初始置信度：高（小脑机制 established；两相模型 high；基底神经节运动学习在此页为概述，详见 habit-formation）

## 来源文章

- [[2026-08-08-deep-cerebellar-nuclei-motor-learning-circuit]]

---
title: 运动学习
slug: motor-learning
domain: concepts
type: concept
status: established
confidence: high
created: 2026-08-08
updated: 2026-06-14
revision_count: 2
dimensions: [behavior, cognition, microcircuit, brain-region, synaptic, cellular]
related: [cerebellum, deep-cerebellar-nuclei, inferior-olive, cerebellar-ltd, climbing-fiber-error-signal, purkinje-cell, motor-cortex, basal-ganglia, ltp, ltd, memory-consolidation, predictive-coding, bg-cerebellum-interaction, striatal-chunking]
prerequisites: [cerebellum, ltp, ltd, cerebellar-ltd]
opens_questions: [Q-dcn-01, Q-dcn-03]
source_articles: [2026-08-08-deep-cerebellar-nuclei-motor-learning-circuit, 2026-06-14-skill-learning-three-systems-bg-cerebellum-cortex]
key_sources: ["PMID:9378587", "PMID:23440175", "PMID:19684593", "PMID:21482355", "PMID:29643480", "PMID:22004979", "PMID:39087986", "PMID:42017796", "PMID:16107540", "PMID:9242612"]
---

# 运动学习（Motor Learning）

> **一句话定义**：通过重复练习和误差反馈改善运动技能表现的过程，在神经科学层面由小脑（误差驱动+内部模型）、基底神经节（强化学习+动作分块）、运动皮层（长期表征存储）三个系统并行协作实现，且 BG 与小脑之间存在直接的双突触皮层下互联（Bostan & Strick 2018）。

## 当前理解

运动学习是神经科学中理解最深入的学习类型之一，因为它有两大优势：可精确量化（运动误差的大小、方向、时序），且有直接因果可操作的动物模型（眼跳适应、VOR 适应、眼眨条件反射、旋转棒技能任务）。

我们现在认为，运动学习（特别是**运动技能习得**）在神经回路层面由**三个并行系统**实现（Penhune & Steele 2012，PMID:22004979；Doyon & Benali 2005，PMID:15831397）：

**1. 小脑误差驱动学习**：对"运动结果与预期的差异"（误差）进行监督式纠正，使运动精度提高。依赖 IO-CF 误差信号驱动 PC 的 LTD，随后在 DCN 完成记忆巩固（两相模型）。小脑还建立**内部前向模型**（forward model），使运动可以在感觉反馈到达前就进行前馈补偿。在技能学习中，小脑主要负责**早期适应和内部模型的精炼**。Varani et al. 2026（PMID:42017796）进一步揭示小脑的两条输出通路具有时间分工：CN→CL 支持在线学习，CN→VAL 支持离线巩固。

**2. 基底神经节奖励强化学习**：对"运动结果的奖励/惩罚"进行强化，逐渐固化为习惯。依赖多巴胺奖励预测误差信号驱动纹状体的 D1/D2 通路权重变化。在技能学习中，BG 负责**动作分块（motor chunking）**和**运动序列的自动化**。关键动态：纹状体内部存在沿前后轴的功能迁移（联合型→感觉运动型，Lehéricy et al. 2005，PMID:16107540），对应从认知参与到自动化的转变。

**3. 运动皮层（M1）表征存储**：M1 在技能学习中主要承担**已习得运动程序的长期表征存储**。M1 损伤主要影响保留（retention），而非在线误差修正。M1 的运动地图随学习发生重塑。

**三个系统并非独立**：BG 和小脑通过双向双突触通路直接互联（Bostan & Strick 2018，PMID:29643480；详见 wiki/concepts/bg-cerebellum-interaction）；误差驱动学习（小脑）和强化学习（BG）的算法在解剖层面存在直接交叉调制。

### 三系统的时间轴动态（两阶段模型，Doyon & Benali 2005）

**快速习得阶段**（单次练习课内）：BG（联合型纹状体）和小脑均高度活跃；前额叶参与维持序列信息；误差大，学习率高。

**缓慢巩固/自动化阶段**（数小时到数周）：BG 激活重心向感觉运动壳核迁移；小脑对已标准化动作的活跃度降低；M1 成为长期表征归宿；前额叶参与减少——动作不再需要工作记忆辅助。

神经系统级别的"幕后重组"（Shadmehr & Holcomb 1997，PMID:9242612）：仅仅6小时内，无行为变化的情况下，激活就从前额叶→前运动皮层+顶叶+小脑皮层转移，证明巩固是主动的神经重组过程。

### 3R 框架（Tsay et al. 2024，PMID:39087986）

最新的整合框架提出感觉运动学习包含三个并行过程：**推理（Reasoning，PFC+MTL，显式）**、**精炼（Refinement，隐式，可能小脑）**、**检索（Retrieval，自动化，皮层下）**。三者并行而非序列，且可相互竞争同一套误差信号。

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
| 纹状体内部联合→感觉运动型功能迁移（fMRI） | 纵向 fMRI，一个月 | PMID:16107540 | 中-高 |
| 巩固期神经重组（6小时内激活模式转移） | fMRI，力场适应后测 | PMID:9242612 | 中-高 |
| 三系统并行分工（纹状体分块/小脑内部模型/M1存储）| 综合神经生理学+神经成像 | PMID:22004979 | 中-高 |
| CN→CL vs CN→VAL 通路时间分工 | DREADD 化学遗传学，旋转棒，小鼠 | PMID:42017796 | 中（鼠类，新发表） |

## 连接

- [[cerebellum]] — 小脑皮层（PC LTD）是运动学习的快速适应阶段；内部模型的建立场所
- [[deep-cerebellar-nuclei]] — DCN 是运动记忆的长期存储与输出门控；两条输出通路时间分工
- [[inferior-olive]] — IO 提供误差驱动学习所需的教师信号（CF）
- [[cerebellar-ltd]] — 小脑皮层运动学习的核心突触机制
- [[climbing-fiber-error-signal]] — CF 是 Marr-Albus-Ito 监督学习的误差通道
- [[memory-consolidation]] — 小脑皮层→DCN 的两相记忆转移；离线巩固与 CN→VAL 通路
- [[habit-formation]] — 习惯形成是运动技能自动化的 BG 依赖端点
- [[ltp]] — DCN 的苔藓纤维 LTP 是运动记忆巩固的细胞机制
- [[bg-cerebellum-interaction]] — BG-小脑双突触互联，打破两系统孤立并行图景
- [[striatal-chunking]] — 纹状体动作分块是技能自动化的 BG 端机制
- [[motor-cortex]] — M1 是已习得运动程序的长期表征存储场所

## 未解问题

- **Q-dcn-01**：人类技能学习（如演奏乐器）中，小脑皮层 LTD 与 DCN LTP 的时间进程各多长？能否通过 cerebellar fMRI 分辨？
- **Q-dcn-03**：小脑认知功能（CCAS）的学习是否也走两相模型（皮层 → 核团巩固）？

## 修订历史

- 2026-08-08 · 创建 · 基于《深部核团的门与教师》（文章#107）· 初始置信度：高（小脑机制 established；两相模型 high；基底神经节运动学习在此页为概述，详见 habit-formation）
- 2026-06-14 · 修订（rev2）· 基于《三系统动态协奏》（文章#187）· 修订内容：①将"两系统"扩展为"三系统并行"框架（增加 M1 角色）；②加入 Lehéricy 2005 纹状体内部轴向迁移证据；③加入 Shadmehr 1997 离线巩固神经重组证据；④加入 Varani 2026 小脑两条输出通路时间分工证据；⑤加入 Tsay 2024 3R 框架；⑥新增连接至 bg-cerebellum-interaction、striatal-chunking、motor-cortex；关键来源扩充至10条

## 来源文章

- [[2026-08-08-deep-cerebellar-nuclei-motor-learning-circuit]]
- [[2026-06-14-skill-learning-three-systems-bg-cerebellum-cortex]]

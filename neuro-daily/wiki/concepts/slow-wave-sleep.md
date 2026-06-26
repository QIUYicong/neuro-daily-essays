---
title: 慢波睡眠（非快速眼动深睡眠）
slug: slow-wave-sleep
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-10-11
updated: 2026-10-13
revision_count: 2
dimensions: [molecular, cellular, microcircuit, brain-region, whole-brain-network, behavior, cognition]
related: [sharp-wave-ripples, sleep-spindles, cortical-slow-oscillation, so-spindle-swr-coupling, memory-consolidation, thalamocortical-circuit, thalamic-reticular-nucleus, flip-flop-switch-sleep-wake, rem-sleep, hippocampal-circuit, ascending-arousal-system, glymphatic-system, adenosine, two-process-model]
prerequisites: [cortical-slow-oscillation, sleep-spindles, sharp-wave-ripples, thalamocortical-circuit]
opens_questions: [Q-sws-substate-nr-01, Q-sws-substate-human-01]
source_articles: [2026-10-11-swr-duration-sleep-microstructure-memory]
key_sources: ["PMID:39743590", "PMID:34001599", "PMID:26135716", "PMID:27182818", "PMID:34709916", "PMID:32248788", "PMID:31197012"]
---

# 慢波睡眠（非快速眼动深睡眠）(Slow-Wave Sleep, SWS / NREM Deep Sleep)

> **一句话定义**：慢波睡眠（SWS）是非快速眼动睡眠（NREM）第3期（N3期），以皮层慢振荡（~0.75 Hz）、丘脑纺锤波（10–16 Hz）和海马尖波涟漪（SWR，80–120 Hz）的三重时间嵌套为特征，是目前已知最主要的记忆系统巩固窗口，同时也是大脑"物理清洁"（类淋巴系统冲洗）的核心时段。

## 当前理解

我们现在认为，SWS 不是大脑简单"关机"的阶段，而是一套**主动的神经程序**，执行两项核心任务：

**任务1：记忆的系统巩固**
海马（快速单次编码器）与新皮层（慢速分布式存储器）在 SWS 期间通过三重振荡耦合反复"对话"，逐步将当日经历刻入皮层突触。主要机制见 [[so-spindle-swr-coupling]]。

**任务2：内环境维护**
类淋巴系统（[[glymphatic-system]]）在 SWS 期间最活跃——神经元体积收缩，脑脊液流速增加，清除代谢废物（包括 β-淀粉样蛋白和 tau 蛋白）。

**新认知：SWS 内部存在精细微结构**

Chang et al.（2025, PMID:39743590）发现 SWS/NREM 睡眠内部并非均匀——瞳孔振荡揭示出两种亚状态，以不同方式处理新旧记忆（见"关键机制"）。

## 关键机制

### 1. 皮层慢振荡（Cortical Slow Oscillations, SO）

- 频率：~0.75 Hz（每1.3秒一个循环）
- 波形：DOWN state（皮层沉默，~400 ms）→ UP state（皮层活跃，~700 ms）
- 起源：皮层内在节律（不依赖丘脑）
- 功能：作为"主时钟"，协调下游纺锤波和 SWR 的时机

### 2. 丘脑纺锤波（Sleep Spindles）

- 频率：10–16 Hz，持续 0.5–3 秒
- 起源：丘脑网状核（TRN）的节律性 GABA 能振荡（见 [[thalamic-reticular-nucleus]]）
- 时机：嵌套在 SO 的 UP state 内部
- 功能：通过 L 型钙通道向皮层树突注入 Ca²⁺，创造"突触可塑性窗口"（Peyrache & Seibt 2020, PMID:32248788）

### 3. 海马 SWR

- 频率：80–120 Hz（啮齿类），持续 50–150 ms
- 时机：嵌套在纺锤波波谷（"SO→纺锤波→SWR"序列）
- 功能：将海马编码的神经序列以~20倍速向新皮层传输
- 见 [[sharp-wave-ripples]] 专页

### 4. NREM 睡眠亚状态（2025 新发现）

Chang et al.（2025）发现，NREM 睡眠中瞳孔大小以 ~10–20 秒周期振荡，与蓝斑（LC）去甲肾上腺素能活动波动同步：

| 亚状态 | 瞳孔 | 推测 NE 水平 | SWR 内容 |
|--------|------|-------------|---------|
| **收缩期**（Contracted）| 缩小 | 低 | 优先重放**近期**（当日）经历 |
| **扩张期**（Dilated）| 扩大 | 较高 | 优先重放**陈旧**（数日前）经历 |

选择性干扰收缩期 SWR → 近期记忆损害（不影响陈旧记忆）——因果证据。

**意义**：这种分时机制使大脑能在同一夜睡眠中同时巩固新旧两类记忆，防止相互覆盖（记忆干扰问题的最直接神经生理答案）。

### 5. 人类颅内证据

Skelin et al.（2021, PMID:34001599）在人类癫痫患者颅内记录中发现：
- SWR 与皮层慢波活动（SWA）的相位耦合预测该皮层位点是否被激活
- 61.4% 同侧皮层位点在 SWR+SWA 条件下显示高频活动增加（局部神经元激活）
- 对照（非 SWR 时段）仅 16.2% 激活
- 这为 SWR 在人类 SWS 期间驱动分布式记忆激活提供了直接证据

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| SWR 因果参与记忆巩固 | 闭环干扰 SWR → 空间记忆受损（大鼠） | PMID:19749750 | 高 |
| SO-纺锤波-SWR 三重耦合是巩固机制 | 闭环增强三重耦合 → 隔天记忆改善（大鼠） | PMID:27182818 | 高 |
| NREM 睡眠存在分时亚状态（近期/陈旧记忆分离） | 瞳孔追踪 + CA1 记录 + 闭环 SWR 抑制（小鼠） | PMID:39743590 | 高（新发现，2025） |
| 长时程 SWR 改善学习 | 光遗传延长 SWR → 迷宫学习加快（大鼠） | PMID:31197012 | 高（因果） |
| SWR-慢波耦合预测人类皮层激活 | 颅内多区域记录（人类癫痫患者） | PMID:34001599 | 中-高（未读取全文）|
| 纺锤波促进皮层突触可塑性 | Ca²⁺ 成像 + 电生理（树突 Ca²⁺ 升高） | PMID:32248788 | 中（综述/多研究综合） |

## 连接

- [[sharp-wave-ripples]] — SWR 是 SWS 记忆巩固的核心机制，嵌套在纺锤波波谷
- [[sleep-spindles]] — 由 TRN 产生，在 SWS 期间为皮层提供可塑性窗口
- [[cortical-slow-oscillation]] — SWS 主时钟；协调纺锤波和 SWR
- [[so-spindle-swr-coupling]] — 三重耦合的完整机制
- [[memory-consolidation]] — SWS 是系统巩固的核心时段
- [[thalamic-reticular-nucleus]] — 纺锤波的生成来源；SWS 期间 TRN 的 Spp1+/Ecel1+ 亚网络控制纺锤波密度
- [[glymphatic-system]] — SWS 期间物理清洁大脑
- [[flip-flop-switch-sleep-wake]] — 控制 SWS 进入/退出的互抑回路

## 未解问题

- **Q-sws-substate-nr-01（新增，高优先级）**：NREM 睡眠亚状态切换的分子机制——LC 的 NE 波动如何直接影响 CA3/CA1 的 SWR 内容？α₂ 受体调制？还是通过对 CA3 循环兴奋阈值的直接调制？
- **Q-sws-substate-human-01（新增，高优先级）**：Chang 2025 的瞳孔振荡分时机制是否在人类中存在等效现象？人类 NREM 睡眠中是否存在可识别的近期/陈旧记忆分时重播模式？

## 修订历史

- 2026-10-11 · 创建 · 基于《时长与时机》文章 (#171) · 整合 Chang 2025（NREM 亚状态）、Skelin 2021（人类颅内）、Fernández-Ruiz 2019（长 SWR）证据；填补 _graph.json 中的 `slow-wave-sleep` 悬空引用 · 初始置信度：高
- 2026-10-13 · rev2 · 添加 related 链接：[[adenosine]] 和 [[two-process-model]]——腺苷（Process S）是 SWA 反弹的内稳态驱动信号；A₁R 激活是 SWA 深度调控的分子必要条件（Bjorness 2009） · 来源：#173

## 来源文章

- [[2026-10-11-swr-duration-sleep-microstructure-memory]]
- [[2026-10-13-adenosine-sleep-homeostasis-process-s]]

---
title: 尖波涟漪（Sharp-Wave Ripple）
slug: sharp-wave-ripple
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-05-29
updated: 2026-05-29
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, behavior, cognition]
related: [memory-consolidation, hippocampal-circuit, place-cell, ltp, theta-oscillations, sleep-oscillations]
prerequisites: [hippocampal-circuit, action-potential, synaptic-transmission, ltp]
opens_questions: [Q-swr-noreplay, Q-swr-selection]
source_articles: [2026-05-29-memory-consolidation-swr]
key_sources: ["PMID:26135716", "PMID:30356103", "PMID:34262446"]
---

# 尖波涟漪（Sharp-Wave Ripple, SWR）

> **一句话定义**：尖波涟漪是海马 CA1 区短暂（40–100 ms）的高频振荡事件（150–250 Hz），由 CA3 循环回路自发爆发触发，在 NREM 睡眠和安静休息期以 2–4 次/秒的频率发生，是序列记忆重放和系统巩固的电生理执行者。

## 当前理解

我们现在认为，SWR 是哺乳类大脑**两阶段记忆策略的核心执行机制**（PMID:26135716）：

**在时间结构上**，SWR 是一种"自发释放"而非"主动诱导"的事件——它是 CA3 循环兴奋网络在 ACh 等调制性抑制减弱时的**默认状态**。清醒探索期，θ 振荡和高 ACh 压制 SWR；睡眠和安静时，抑制解除，SWR 自然涌现。

**在功能上**，SWR 具有**双重角色**（PMID:30356103）：
1. **即时使用（immediate use）**：清醒状态下的 SWR 携带"本地轨迹"重放，服务于导航决策和规划
2. **系统巩固（consolidation）**：睡眠期 SWR 携带压缩的时序序列，通过三重振荡耦合向皮层广播

不是所有 SWR 都相同：大型 SWR 比小型 SWR 招募更多神经元，更有效地驱动海马-皮层共激活，且学习后大型 SWR 优先增加（PMID:41205608）。

## 关键机制

### 1. CA3 起源：循环网络的雪崩

SWR 起源于 CA2-CA3 区（PMID:34262446）：
- CA3 约 25 万锥体细胞通过 **60–100 公里**的轴突侧支形成密集循环网络（~50–100 亿突触）
- 当调制性抑制（ACh）下降，CA3 循环网络自发爆发同步激活
- 爆发通过 **Schaffer 侧支**传播到 CA1 辐状层，产生大型兴奋性 EPSP（"尖波"）

### 2. CA1 涟漪：兴奋-抑制振荡

CA1 的涟漪（150–250 Hz）由以下回路产生：
1. CA3 大量兴奋性输入 → CA1 锥体细胞去极化并激活
2. CA1 **PV+ 篮细胞（parvalbumin basket cell）**被招募，产生强烈 GABA 抑制
3. 锥体细胞抑制 → 解除 → 再激活 → 再抑制……形成高频振荡
4. 轴突-轴突细胞（chandelier cell）在 SWR 期间**减少**放电（可能提供去抑制）

**神经元参与统计**（PMID:26135716）：
- 1.5% 的 CA1 锥体细胞参与了 50% 的 SWR 事件（"超级参与者"，对数正态分布）
- ~50% 的细胞在 <10% 的 SWR 中激活
- 整体 SWR 每次招募约 10–50% 的锥体细胞（大型 SWR > 小型）

### 3. 序列压缩重放

SWR 期间，白天 θ 振荡中按空间/时间序列激活的细胞群以约 **20:1** 的压缩比重放：
- θ 期序列持续：数百 ms ~数秒
- SWR 重放持续：40–100 ms
- 重放类型：
  - **正向（forward）**：原始方向，服务于空间预测
  - **反向（reverse）**：逆向，服务于奖励相关强化
  - **前瞻（prospective）**：未曾经历的路径，可能服务于规划

只有 **10–40%** 的 SWR 有统计上可检测的序列重放；其余 SWR 的功能尚不完全清楚。

### 4. 睡眠中的三重振荡耦合

在 NREM 睡眠中，SWR 嵌套于皮层振荡的精密时序中：
- 皮层慢振荡（SO）上行状态 → 纺锤波（10–15 Hz）出现
- 纺锤波的特定相位 → SWR 爆发
- 皮层处于"接收窗口"时，SWR 传递记忆信号效率最高

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| CA3 是 SWR 起源 | CA3 损伤消除 CA1 的 SWR；CA3 体外自发产生 SWR | PMID:26135716 | 高 |
| PV+ 篮细胞产生涟漪 | 光遗传特异性激活/抑制 PV 细胞改变涟漪频率 | PMID:34262446 | 高 |
| SWR 中断损害记忆 | 电刺激中断 SWR → 空间学习减慢；光遗传中断 → 任务表现下降 | PMID:30356103 | 高 |
| SWR 序列重放 | 多细胞记录 + 解码分析，重放顺序保留 | PMID:26135716 | 高 |
| 大型 SWR 优先驱动皮层记忆激活 | 海马-PFC 同步记录 + SWR 大小分类 | PMID:41205608 | 中-高（读摘要）|
| SWR 密度与次日记忆正相关 | 大鼠迷宫 + 睡眠记录；r=−.68 | PMID:19693273 | 中-高 |

## 连接

- [[memory-consolidation]] — SWR 是系统记忆巩固的核心执行机制
- [[hippocampal-circuit]] — CA3 产生 SWR，CA1 表达涟漪；SWR 是海马回路的"广播模式"
- [[place-cell]] — 场所细胞序列是 SWR 重放的主要内容
- [[ltp]] — SWR 可在 CA3→CA1 突触诱导 LTP，是巩固的突触机制之一
- [[theta-oscillations]] — θ 振荡（编码期）与 SWR（巩固期）是互斥的海马工作模式
- [[sleep-oscillations]] — SWR 嵌套于皮层 SO-纺锤波层级中

## 未解问题

- Q-swr-noreplay：没有可检测序列重放的 SWR 事件（占所有 SWR 的 60–90%）在做什么？
- Q-swr-selection：SWR 基于什么原则选择优先重放某些经历（奖励相关的、新奇的）？

## 修订历史

- 2026-05-29 · 创建 · 基于《海马的夜间档案馆》文章 · 综合 Buzsáki 2015、Joo&Frank 2018、Zhen 2021 三篇综述 · 初始置信度：高

## 来源文章

- [[2026-05-29-memory-consolidation-swr]]

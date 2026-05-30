---
title: 短时程突触可塑性（STP）
slug: short-term-synaptic-plasticity
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-10
updated: 2026-06-10
revision_count: 1
dimensions: [molecular, synaptic, microcircuit, cognition]
related: [synaptotagmin, readily-releasable-pool, synaptic-transmission, active-zone, voltage-gated-calcium-channels, working-memory, pv-interneurons, ltp, ltd]
prerequisites: [synaptic-transmission, active-zone, synaptotagmin, voltage-gated-calcium-channels]
opens_questions: [Q-stp-activity-silent-wm, Q-stp-cognitive-disease, Q-syt7-facilitation-mechanism, Q-stp-syt7-human]
source_articles: [2026-06-10-stp-short-term-plasticity]
key_sources: ["PMID:11826273", "PMID:22751149", "PMID:28472650", "PMID:29088700", "PMID:9012851", "PMID:18339943"]
---

# 短时程突触可塑性（Short-Term Synaptic Plasticity, STP）

> **一句话定义**：突触传递效率在毫秒至分钟时间尺度内的使用依赖性动态变化，包括增强（易化/augmentation/PTP）和减弱（抑制）两类方向，由突触前钙动力学、囊泡就绪状态和特定蛋白（Syt7、PKC）共同决定，是突触执行频率选择性计算和储存工作记忆的物理基础。

## 当前理解

我们现在认为，突触不是固定增益的信号继电器，而是具有"一秒内记忆"的动态计算元件。在毫秒至分钟的时间尺度上，突触根据其输入历史动态调整传递效率——这种使用依赖的可塑性称为短时程突触可塑性（STP）。

STP分为四种主要形式（Zucker & Regehr 2002, PMID:11826273）：

| 形式 | 时间尺度 | 方向 | 主要机制 |
|------|---------|------|---------|
| 易化（Facilitation, F） | 数十–数百毫秒 | 增强 | 残余钙 + Syt7膜结合 |
| 抑制（Depression, D） | 数百毫秒–数秒 | 减弱 | RRP耗竭 |
| 增强（Augmentation, A） | 数秒–数十秒 | 增强 | 残余钙持续升高 + PKC |
| 强直后增强（PTP） | 数十秒–数分钟 | 增强 | 线粒体钙 + PKC磷酸化Munc18-1 |

关键认识是，这四种形式同时存在于大多数突触，净效应取决于突触特定的分子组成（p值、RRP大小、Syt7表达量、钙缓冲蛋白浓度）。具有不同p值的突触实现不同的计算功能（Tsodyks & Markram 1997, PMID:9012851）。

## 关键机制

### 易化（Facilitation）

**主要机制：Synaptotagmin-7（Syt7）**

Jackman & Regehr (2017, PMID:28472650) 证明，在海马沙费尔侧支、苔藓纤维等4种主要突触中，Syt7敲除几乎完全消除配对脉冲易化（PPF），而不影响快速同步释放。

Syt7的分子特性：
- 高钙亲和力（Kd ~1.5 μM），可被残余钙激活
- 慢解离（比Syt1慢约60倍），激活后在膜上驻留数十毫秒
- 不独立触发释放，而是增强Syt1介导融合的概率（等效降低能垒2–5 kT）

**辅助机制：缓冲区饱和**

在苔藓纤维等含高浓度calbindin的突触：第一次刺激使钙缓冲蛋白饱和，第二次局部钙峰更高（Regehr 2012, PMID:22751149）。

### 抑制（Depression）

**主要机制：就绪释放池（RRP）耗竭**

- 每个动作电位释放 p × RRP 个囊泡
- 释放后位点暂时空出，等待储备池囊泡补充（数百毫秒–数秒）
- 高频刺激下，耗竭速率超过补充速率 → 抑制

**定量预测**：配对脉冲比 PPR ≈ (1 - p)，与实验数据在同一量级

**钙加速补充**：高频刺激的胞内残余钙通过钙/钙调蛋白依赖机制加速RRP补充，最高达**10倍**（Regehr 2012）

**其他机制**：释放位点失活（融合后不可用期1–2秒）、钙通道失活（低频时更重要）

### 频率不变传输（Frequency-Invariant Transmission）

在某些抑制性突触（小脑PC→DCN，前庭突触），Syt7提供的隐藏易化精确抵消depression，产生跨5–150 Hz的频率不变传输（Turecek et al. 2017, PMID:29088700）。

这是进化通过匹配两个对立机制实现线性编码的极致案例，对感觉-运动系统（前庭-眼反射）的线性信号传递至关重要。

### 强直后增强（PTP）

PKC磷酸化Munc18-1介导约80% PTP（calyx of Held）；线粒体是持续数分钟的残余钙来源（Regehr 2012）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Syt7是脑内多突触易化的主要传感器 | Syt7 KO消除4种突触的PPF | PMID:28472650 (PMC5865607) | 高 |
| RRP耗竭是突触抑制的主要机制 | 统计分析 + 数学模型 + 多突触体系 | PMID:11826273 | 高 |
| 钙加速RRP补充达10倍 | calyx of Held荧光钙成像 + 电生理 | PMID:22751149 (PMC3385958) | 高 |
| Syt7赋予特殊抑制性突触频率不变性 | Syt7 KO消除PC→DCN频率不变性；救援实验恢复 | PMID:29088700 (PMC5892411) | 高 |
| 高p突触=低通，低p突触=高通滤波 | 新皮层配对记录 + 数学模型 | PMID:9012851 (PMC19580) | 高 |
| STP易化可实现活动无声WM | 计算模型 + PFC生理部分验证 | PMID:18339943 | 中（模型） |

## 连接

- [[synaptotagmin]] — Syt7是易化的专属分子传感器；Syt1是快速同步释放传感器
- [[readily-releasable-pool]] — RRP耗竭是抑制的主要机制；RRP大小和补充速率决定抑制深度
- [[synaptic-transmission]] — STP是突触传递的时序扩展：将固定增益的传递变为历史依赖的计算
- [[active-zone]] — RRP囊泡位于活动区；释放位点的物理结构决定STP参数
- [[voltage-gated-calcium-channels]] — 残余钙（激活Syt7）来自钙通道关闭后的胞质清除不完全
- [[working-memory]] — Mongillo模型：STP易化状态储存"活动无声"工作记忆
- [[pv-interneurons]] — PV+快速发放的抑制性突触有特殊STP设计（Syt7频率不变）
- [[ltp]] — LTP（分钟-终身）vs STP（毫秒-分钟）：时间尺度连续谱的不同区段

## 计算逻辑

STP的核心计算功能（Abbott & Regehr 2004, PMID:15483601）：

1. **频率路由**：高p突触（低通）→ 传递持续低频；低p突触（高通）→ 传递突发高频burst
2. **增益控制**：depression使突触对相对频率变化（而非绝对变化）敏感（Abbott et al. 1997）
3. **线性编码**：Syt7精确抵消depression → 频率不变传输（Turecek et al. 2017）
4. **工作记忆**：STP易化状态储存短期信息，无需持续放电（Mongillo et al. 2008）

## 未解问题

- Q-stp-activity-silent-wm：活动无声WM的STP状态是否已被体内直接测量？不同WM任务中贡献比例？
- Q-stp-cognitive-disease：STP障碍在精神分裂症/自闭症/AD中是否有因果作用？
- Q-syt7-facilitation-mechanism：Syt7通过直接调控SNARE还是纯通过膜结合构象影响融合概率？（已更新，仍open）
- Q-stp-syt7-human：人类皮层STP参数（p分布、RRP大小、Syt7表达）与啮齿类的系统性差异？

## 修订历史

- 2026-06-10 · 创建 · 基于《瞬息之变：短时程突触可塑性的分子机制与计算逻辑》一文 · 初始置信度：高

## 来源文章

- [[2026-06-10-stp-short-term-plasticity]]

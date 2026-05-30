---
title: 短时程突触可塑性
slug: short-term-synaptic-plasticity
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-10
updated: 2026-06-10
revision_count: 1
dimensions: [synaptic, molecular, cellular, cognition]
related: [synaptotagmin, synaptic-transmission, ltp, ltd, active-zone, working-memory, nmda-receptor, ampa-receptor]
prerequisites: [synaptic-transmission, active-zone, synaptotagmin, voltage-gated-calcium-channels]
opens_questions: [Q-syt7-facilitation-mechanism, Q-wm-active-vs-silent, Q-stp-ltp-interaction]
source_articles: [2026-06-10-short-term-synaptic-plasticity]
key_sources: ["PMID:11826273", "PMID:22751149 (PMC3385958)", "PMID:26738595 (PMC4729191)", "PMID:29088700 (PMC5892411)", "PMID:18339943", "PMID:41665484 (PMC12890252)"]
---

# 短时程突触可塑性 (Short-term Synaptic Plasticity, STP)

> **一句话定义**：突触后响应幅度随突触前活动历史在毫秒到分钟尺度上的一过性可逆变化，分为短时程易化（STF）和短时程抑制（STD），无需新蛋白合成，完全由残余钙动力学（Syt7 介导）和囊泡池耗竭竞争决定方向。

## 当前理解

我们现在认为，突触不是静态的权重旋钮，而是具有历史感知能力的动态滤波器。同一个突触在一次 AP 之后，其传递效率可能在接下来的几百毫秒内显著升高（STF）或降低（STD），具体方向由**初始释放概率（$P_r$）**决定（PMC3385958）：

- **高 $P_r$ 突触（$P_r > 0.4$）**：倾向于 STD——因为每次 AP 消耗较大比例的 RRP，后续 AP 时可用囊泡减少
- **低 $P_r$ 突触（$P_r < 0.2$）**：倾向于 STF——囊泡耗竭少，但残余钙积累显著，驱动 Syt7 激活

**Syt7 是 STF 的分子传感器**（Jackman 2016，PMC4729191）：AP 后残余 Ca²⁺（~0.5–2 μM）激活高亲和力 Syt7（K_D ~μM），而 Syt1 需要峰值 Ca²⁺ (~50–100 μM) 才能激活——这解释了为何残余钙虽然仅为峰值的 ~1%，却能驱动 100–200% 的释放增强。

Syt7 在高 $P_r$（抑制型）突触中也有"隐性"功能：它提供的易化恰好补偿了囊泡耗竭，使这些突触实现**频率不变性**——响应幅度在生理放电频率范围（10–150 Hz）内保持稳定（Turecek 2017，PMC5892411）。

**认知层面**：STF 可将信息以"静默突触增益状态"存储，不需要持续神经元放电——即所谓**活动静默工作记忆**（Mongillo 2008，PMID:18339943）。

## 关键机制

### 短时程抑制（STD）——囊泡池耗竭

- **主要机制**：每次 AP 释放 RRP 中比例 $F$ 的囊泡；连续 AP 后 RRP 耗竭，响应幅度下降
  - 定量模型：$A_n / A_1 = (1 - F)^{n-1}$（指数衰减）
- **恢复**：RRP 补充速率 ~1–10 秒；Ca²⁺ 依赖性加速（calmodulin 介导）
- **次要机制**：突触后 AMPA 受体去敏化（特别是在视网膜-LGN 等高速突触）
- **效应**：高 $P_r$ 突触成为低通滤波器（只有低频输入才能充分传递）

### 短时程易化（STF）——Syt7 + 残余钙

- **传感器**：Syt7（高亲和力，K_D ~μM；慢激活 ~10–100 ms）
- **机制链**：AP → Ca²⁺ 峰值（→ Syt1 激活→同步释放）→ Ca²⁺ 弥散 → 残余 ~1 μM → Syt7 激活 → 下一 AP 时 Syt7 协同 Syt1 → 释放概率升高
- **时间常数**：PPF 约 50–500 ms 内衰减（随残余 Ca²⁺ 清除）
- **PFC 特殊机制**（Shin 2026，PMC12890252）：当 $P_v \approx 1$ 时，STF 不增加 $P_v$，而是通过"囊泡过载"（occupancy 从 30% → 60%）增加可用发射点位数量；Syt7 将囊泡补充加速 50 倍（5s → 100ms）

### 其他形式（较慢）

- **增效（Augmentation）**：~5–30 秒；依赖线粒体 Ca²⁺ 释放；部分通过 PKC/Munc13
- **强直后增强（PTP）**：~1–10 分钟；高频爆发后；Na/Ca 交换体饱和 → 持续高残余 Ca²⁺
- **计算功能（Grover 2026，PMC12908934）**：Augmentation 可在 WM 中编码"时序"信息（不只是身份）

### Syt7 的频率不变性（隐性易化）

在高 $P_r$ 突触（如浦肯野→深部小脑核）：
- 低频：STD 和 STF 都较弱，响应正常
- 高频：STD 增强（耗竭），但 STF 也增强（Syt7 被连续激活）
- 净效应：两者相消 → 频率不变 → 线性信号传递

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| RRP 耗竭是 STD 的主要机制 | 方差-均值分析；RRP 直接耗竭实验（calyx of Held）| PMC3385958 | 高 |
| 高 $P_r$ → 抑制型；低 $P_r$ → 易化型 | 胞外 Ca²⁺ 浓度改变可切换 STP 方向 | PMC3385958 | 高 |
| Syt7 KO → PPF 完全消失（4 种突触）| Syt7 KO 小鼠全细胞膜片钳 + 救援实验 | PMC4729191 | 高 |
| Syt7 C2A Ca²⁺ 不敏感突变 → 不能救援 PPF | 点突变 + 病毒重表达 | PMC4729191 | 高 |
| Syt7 在高 $P_r$ 突触提供频率不变性 | Syt7 KO：高频时频率依赖抑制出现 | PMC5892411 | 高 |
| PFC L2/3 STF 通过囊泡过载（$P_v \approx 1$）| 方差-均值分析；Syt7 KD 减慢补充（5s vs 100ms）| PMC12890252 | 中 |
| PFC Syt7 KD → 追踪恐惧记忆受损 | 行为测试（AA vs 对照） | PMC12890252 | 中（需复制）|
| STD → 低通滤波；STF → 高通滤波 | 计算建模 + 体外电生理多系统验证 | PMC6171349 | 高 |
| 活动静默 WM 的突触理论 | 理论建模 + 间接行为支持 | PMID:18339943 | 中（缺体内直接证据）|

## 连接

- [[synaptotagmin]] — Syt7（STF 传感器）和 Syt1（同步释放传感器）在同一突触上协同工作
- [[synaptic-transmission]] — STP 调制突触传递效率的即时状态
- [[active-zone]] — RRP 存在于活动区，其大小和补充速率决定 STD 深度与恢复时间
- [[ltp]] — LTP 是小时尺度的突触增强；STP 是毫秒-分钟尺度的动态调制，两者可能协同诱导
- [[ltd]] — LTD 是小时尺度的突触减弱；STD 是其分钟内的快速表亲
- [[working-memory]] — 活动静默 WM（Mongillo 2008）以 STF 作为 WM 的物质基础
- [[ampa-receptor]] — AMPA 受体去敏化是 STD 的突触后机制
- [[voltage-gated-calcium-channels]] — VGCCs（CaV2.1/2.2）控制残余 Ca²⁺ 的幅度和清除速率，决定 STF 时间常数

## 未解问题

- Q-syt7-facilitation-mechanism：Syt7 如何与 Syt1 协同增加释放概率？通过共同结合 SNARE 还是膜弯曲效应？（Jackman 2016 提供了"是什么"的答案，但"怎么做"的分子细节尚不完全清楚）
- Q-wm-active-vs-silent：活动静默 WM（STF 机制）与 γ 爆发（持续放电机制）在真实任务中各贡献多少比例？（见 working-memory.md）
- Q-stp-ltp-interaction（新增）：STF 处于激活窗口时，是否更容易同时诱导 LTP（因为释放概率升高 → 更多 Ca²⁺ → 更容易激活 NMDA 受体）？STD 是否阻碍 LTP 诱导？

## 修订历史

- 2026-06-10 · 创建 · 基于《突触的历史感：Syt7、囊泡耗竭与大脑如何在每一次传递中存储"刚才发生了什么"》· 初始置信度：高（STF/STD 机制）；中（活动静默 WM 体内证据）

## 来源文章

- [[2026-06-10-short-term-synaptic-plasticity]]

---
title: 短时程突触可塑性
slug: short-term-synaptic-plasticity
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-07
updated: 2026-06-07
revision_count: 1
dimensions: [synaptic, molecular, microcircuit, cognition]
related: [synaptotagmin, synaptic-transmission, active-zone, ltp, ltd, working-memory, voltage-gated-calcium-channels, SNARE-complex]
prerequisites: [synaptic-transmission, active-zone, voltage-gated-calcium-channels]
opens_questions: [Q-syt7-facilitation-mechanism, Q-stp-ltp-interaction, Q-activity-silent-wm-in-vivo, Q-stp-human-wm]
source_articles: [2026-06-07-short-term-synaptic-plasticity]
key_sources: ["PMID:11826273", "PMID:22751149", "PMID:26738595", "PMID:9012851", "PMID:18339943"]
---

# 短时程突触可塑性 (Short-Term Synaptic Plasticity, STP)

> **一句话定义**：突触连续激活时，因残余钙积累（→易化）或就绪囊泡耗竭（→抑制），在毫秒到秒时间尺度上动态改变释放概率（Pr）的现象；Syt7 是易化的分子传感器，Tsodyks-Markram 模型（A × u(t) × x(t)）是其数学描述，STP 是突触实时状态机的核心机制。

## 当前理解

我们现在认为，突触不是固定权重的静态乘法器，而是在毫秒到秒时间尺度上持续更新状态的动态系统。每个动作电位过后，突触前终末的两个相反过程同时进行：

1. **残余钙积累**：每次 AP 引入的钙未被完全清除（数十毫秒才能泵出），如果下一个 AP 很快到来，残余钙叠加使 Pr 短暂升高 → **突触易化（facilitation）**。Jackman et al. 2016 确认，Syt7（高亲和力，慢速钙传感器，位于突触前质膜）是感知这一残余钙信号的必要分子（PMID:26738595）。

2. **就绪囊泡耗竭**：每个 AP 消耗 RRP 的一部分（具体比例 = 释放概率 Pr）；如果 Pr 高或者激活频率高，RRP 在数十至数百 ms 内耗尽 → **突触抑制（depression）**，恢复时间常数约数百 ms 至几秒（钙加速补充）。

**四种 STP 形式**（时间谱从短到长）：

| 形式 | 时间尺度 | 方向 | 主要机制 |
|------|---------|------|---------|
| 易化（Facilitation） | 10–300 ms | 增强 | 残余钙 + Syt7 |
| 抑制（Depression） | 50 ms–秒 | 减弱 | 囊泡耗竭（RRP） |
| 增强（Augmentation） | ~4–5 s | 增强 | 残余钙积累 + 囊泡补充 |
| 突触后强化效应（PTP） | 10–180 s | 增强 | 线粒体钙释放 + PKC + RRP 扩大 |

**Tsodyks-Markram 定量模型**（PMID:9012851）：
```
EPSP(t) = A × u(t) × x(t)
```
- A：长期突触权重（LTP/LTD 决定）
- u(t)：当前释放概率（AP 后升高 → 易化，时间常数 τ_u ≈ 数百 ms）
- x(t)：囊泡可用比例（AP 后下降 → 抑制，时间常数 τ_x ≈ 数秒）

## 关键机制

### 突触抑制的分子机制

**主要**：囊泡耗竭
- RRP 约为总囊泡的几个百分点，每次 AP 消耗其中 Pr 比例
- 循环利用池约占总囊泡 10–20%，恢复时间常数 ~数百 ms
- 高频刺激 → 供不应求 → 后续 EPSP 急剧缩小

**次要**：突触前钙通道失活（calmodulin 介导，高频刺激减少钙流入）、突触后受体脱敏（AMPA 受体短暂脱敏）

### 突触易化的分子机制

**Syt7 的关键角色**（PMID:26738595，PMC:PMC4729191）：
- Syt7 位于突触前质膜，C2A 结构域对 Ca²⁺ 亲和力高（约 1–5 μM，对应残余钙水平），动力学慢（数十 ms）
- Syt1 位于囊泡膜，对 Ca²⁺ 亲和力低（约 20–100 μM，对应纳米域峰值），动力学快（<1 ms）
- 第一个 AP 后，Syt7 被部分激活但尚未触发额外融合；残余钙维持 Syt7 激活状态
- 第二个 AP 到来：Syt7 对残余钙的响应叠加在 Syt1 的峰值钙响应上 → 多更多囊泡融合

**"钙缓冲蛋白饱和"机制**（补充作用）：
- 快速高亲和力缓冲蛋白（calbindin）在第一个 AP 后被 Ca²⁺ 占满
- 第二个 AP 时缓冲能力降低 → 局部 Ca²⁺ 更多到达 Syt1 → 额外的释放增强

### 突触后强化效应（PTP）的机制

- **线粒体钙储库**：高频刺激时线粒体大量吸收钙，刺激停止后缓慢释放，维持数十秒低水平升高
- **PKC 激活**：钙激活蛋白激酶 C，磷酸化 Munc18-1 等 SNARE 调控蛋白，增加有效 RRP
- **RRP 扩大**：高频刺激后 RRP 净增约 30%（calyx of Held 测量）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Syt7 KO 消除多类突触的 PPF | 小鼠 KO + 多类突触 PPR 测量 | PMID:26738595（Nature，开放全文） | 极高 |
| 囊泡耗竭是抑制主要机制 | 高渗蔗糖探测 RRP；耗竭与 PPD 幅度相关 | PMID:22751149（开放全文）；PMID:11826273 | 高 |
| 残余钙定量不能单独解释易化幅度 | Cares ≈ Calocal 的 1%；Ca⁴依赖仅预测 4% 增强 | PMID:22751149 | 高 |
| Ca²⁺ 结合突变体 Syt7 不能恢复易化 | 点突变 Syt7 C2A + KO 背景下恢复实验 | PMID:26738595 | 高 |
| STP 易化是活动无声 WM 的可能基础 | 循环网络计算模型（Tsodyks-Markram） | PMID:18339943（计算模型）；PMID:35471537 | 中（模型预测） |
| Syt7 还介导异步释放 | 小脑颗粒细胞 KO 实验 | PMID:29593071 | 中-高 |

## 连接

- [[synaptotagmin]] — Syt1 触发同步释放；Syt7 介导易化（同一终末内的双钙传感器体系）
- [[synaptic-transmission]] — STP 是突触传递有效强度的动态修饰因子
- [[active-zone]] — RRP 储量（在活动区 scaffold 上预备的囊泡）直接决定抑制的幅度
- [[voltage-gated-calcium-channels]] — CaV2.1/2.2 产生局部 Ca²⁺ 触发 Syt1；L 型产生较慢钙信号，可能与 Syt7 更相关
- [[working-memory]] — STP 易化是活动无声工作记忆的突触基础（Mongillo et al. 2008）
- [[ltp]] — LTP/LTD 设定长期权重 A；STP 在更短时间尺度上动态调制 u(t) × x(t)；两者叠加决定实时有效突触强度
- [[ltd]] — 与 LTD 共同构成突触可塑性的完整时间谱（从毫秒到终身）

## 未解问题

- **Q-syt7-facilitation-mechanism**：Syt7 感应残余钙后的下游信号是什么？它如何与 SNARE 相互作用来提高释放概率？（分子机制细节仍不完整）
- **Q-stp-ltp-interaction**：PTP 与 LTP 的诱导门限如何相互影响？同一突触在高频刺激时的 LTP vs PTP 分配规则是什么？
- **Q-activity-silent-wm-in-vivo**：Mongillo 2008 的活动无声 WM 模型是否有直接体内证据（同时测量单突触 STP 状态与行为记忆）？
- **Q-stp-human-wm**：人类前额叶皮层突触的 STP 属性与啮齿类的异同？STP 是否是人类长延迟工作记忆能力的关键因素？

## 修订历史

- 2026-06-07 · 创建 · 基于《突触的短时记忆：易化与抑制如何让每个突触成为计算单元》一文 · 初始置信度：高

## 来源文章

- [[2026-06-07-short-term-synaptic-plasticity]]

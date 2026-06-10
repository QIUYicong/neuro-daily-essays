---
title: 关键期可塑性
slug: critical-period-plasticity
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-05
updated: 2026-09-05
revision_count: 1
dimensions: [molecular, synaptic, cellular, microcircuit, brain-region, systems]
related: [critical-period, ocular-dominance-columns, silent-synapse, ltp, ltd, homeostatic-plasticity, synaptic-scaling, pv-interneurons, perineuronal-nets, bdnf, metaplasticity]
prerequisites: [critical-period, ltp, ltd, silent-synapse, synaptic-transmission]
opens_questions: [Q-cp-01, Q-odc-03]
source_articles: [2026-09-05-odp-stage2-hebbian-vs-homeostatic]
key_sources: ["PMID:18549780", "PMID:22232689", "PMID:26015564", "PMID:32765222", "PMID:22841309", "PMID:28093561"]
---

# 关键期可塑性 (Critical Period Plasticity)

> **一句话定义**：在发育关键期内，感觉经验对神经回路进行大规模、快速且持久重塑的突触可塑性现象的总称；在初级视觉皮层中表现为眼优势可塑性（ODP）的两阶段过程：稳态缩放（TNFα 介导）提供允许条件，Hebbian LTP（PSD-95/沉默突触）执行输入特异性精修，两者时序协同。

## 当前理解

**关键期可塑性不是单一机制，而是时序协调的机制集合**。以 ODP 为最佳研究模型，关键期可塑性体现为：

**开启条件**：PV+ 中间神经元 GABA 能成熟达到阈值（Hensch 1998/2000）；BDNF-TrkB 加速成熟时钟；OTX2 经 PNN 传递到 PV+ 细胞。详见 [[critical-period]]。

**关键期内的 ODP 两阶段机制**：

**第一阶段（受剥夺眼减弱，MD 第 1–4 天）**：
- 低活动 → NMDAR 低激活 → PP2B/PP1 → GluA2-AMPAR 内吞 → LTD
- 分子工具：Arc（AMPAR 内吞媒介）、circHomer1（调控效率）
- 不依赖蛋白质合成；不需要开放眼竞争活动

**第二阶段（开放眼增强，MD 第 3–7+ 天）**——两个机制时序协同：

*稳态缩放（Claim B，Kaneko et al. 2008, Stryker 实验室）*：
1. 整体活动下降 → 星形胶质细胞释放 TNFα → TNFR1 → PI3K/PKA → GluA1-AMPAR 乘法性插入
2. 全局兴奋性抬升（不区分输入来源）
3. 提供 NMDAR 充分激活的前提条件（兴奋性许可信号）
4. 时间尺度：数小时至数天

*Hebbian LTP / 沉默突触开锁（Claim A，Schlüter/Löwel 实验室）*：
1. 开放眼视觉活动 + TNFα 抬升的兴奋性背景 → NMDAR 充分激活 → Ca²⁺ 大量流入
2. CaMKII 激活 → GluA1（S831）磷酸化 → AMPAR 插入沉默突触 → PSD-95 锚定
3. 开放眼路径特异性增强（Hebbian 特异性）
4. 随沉默突触耗竭，关键期走向关闭
5. 时间尺度：数天

**关键期关闭**：(a) 底物耗竭（沉默突触池耗竭）；(b) 主动结构封印（PNN 沉积 + Lynx1 上调）。详见 [[critical-period]]。

## 关键机制

### 与元可塑性的关系

BCM 元可塑性（滑动修改阈值）在关键期第二阶段发挥协同作用：
- 持续活动剥夺 → NR2B/NR2A 比值升高（NMDAR 动力学减慢）→ LTP 阈值降低
- 这使开放眼更容易诱导 LTP，解释了为什么第二阶段在第一阶段后开始（当总活动已下降后）

### 成年期 ODP 的机制转变

幼年 ODP 第二阶段需要 TNFα（稳态许可）；成年 ODP 第二阶段不需要 TNFα，但需要 CaMKII（直接 Hebbian LTP，Ranson 2012）。这意味着：
- 幼年：稳态→Hebbian 的时序依赖
- 成年：Hebbian 可独立运作（TNFα 替代由丘脑 CaV3.1 爆发放电提供，Echavarri-Leet 2025）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 第一阶段 LTD：NMDAR-PP2B-GluA2 AMPAR 内吞 | APV/肽阻断 + 电生理 | PMID:22841309 | 高 |
| 第二阶段需要 TNFα（幼年）| TNFα KO + VEP/单细胞 | PMID:18549780 | 高 |
| 幼年需要稳态机制；成年不需要（CaMKII instead）| 年龄对比 + KO | PMID:22232689 | 高 |
| PSD-95 KO 无限延长关键期（底物耗竭机制）| PSD-95 KO + ODP | PMID:26015564 | 高 |
| TNFα 也是视皮层 LTP 的许可因子（桥接 A+B）| TNFα KO + LTP 诱导 | PMID:25701075 | 中 |

## 连接

- [[critical-period]] — 关键期的时间结构、开启/关闭门控机制（更上层的概念页）
- [[ocular-dominance-columns]] — ODP 是关键期可塑性在视皮层的功能输出
- [[silent-synapse]] — ODP 第二阶段 Hebbian LTP 的底物
- [[homeostatic-plasticity]] — TNFα 稳态缩放是 ODP 第二阶段的许可机制
- [[synaptic-scaling]] — TNFα→AMPAR 上调是突触缩放的分子机制
- [[ltp]] — ODP 第二阶段的 Hebbian 组件
- [[ltd]] — ODP 第一阶段的分子机制
- [[pv-interneurons]] — PV+ 去抑制触发关键期进入可塑状态
- [[perineuronal-nets]] — 关键期关闭的结构性刹车
- [[metaplasticity]] — BCM 元可塑性（滑动阈值）与关键期 Stage 2 LTP 协同
- [[bdnf]] — BDNF-TrkB 是 Stage 2 增强的信号驱动之一

## 未解问题

- Q-odc-03（高优先级）：ODP 第二阶段中稳态缩放（TNFα）和 Hebbian LTP（PSD-95/沉默突触）的时间窗口分工？同一动物同一时间点的直接双重测量实验仍缺失。
- Q-cp-01：人类视觉关键期沉默突触池的大小和耗竭时序（大鼠 ~P28 关闭；人类对应年龄不明）。

## 修订历史

- 2026-09-05 · 创建 rev1 · 基于《开放眼的胜利》(#119) · 填补悬空引用（被 [[metaplasticity]] 中的 edge: metaplasticity→critical-period-plasticity 引用但无对应页）；综合 ODP 两阶段分子机制，与 [[critical-period]] 区分：本页聚焦突触分子机制，[[critical-period]] 聚焦时间结构和门控机制 · 初始置信度：高

## 来源文章

- [[2026-09-05-odp-stage2-hebbian-vs-homeostatic]]

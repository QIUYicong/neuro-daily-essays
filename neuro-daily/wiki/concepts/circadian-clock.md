---
title: 昼夜节律分子振荡器（TTFL）
slug: circadian-clock
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-08
updated: 2026-07-08
revision_count: 1
dimensions: [molecular, cellular, brain-region, whole-brain-network, cognition, disease]
related: [scn-circadian-pacemaker, memory-consolidation, glymphatic-system, rem-sleep, cortical-slow-oscillation, ltp, homeostatic-plasticity, pv-interneurons, critical-period, alzheimers-disease, bdnf, norepinephrine-locus-coeruleus, neuromodulator-systems]
prerequisites: [synaptic-transmission, action-potential]
opens_questions: [Q-circ-01, Q-circ-02, Q-circ-03]
source_articles: [2026-07-08-circadian-clock-scn-brain-rhythm]
key_sources: ["PMID:12198538", "PMID:1546306", "PMID:32503914", "PMID:20664079", "PMID:30862123", "PMID:36741032", "PMID:11805301", "PMID:7185792"]
---

# 昼夜节律分子振荡器（TTFL）(Circadian Clock — Transcription-Translation Feedback Loop)

> **一句话定义**：哺乳动物细胞内部的约 24 小时自主分子振荡器——由 CLOCK/BMAL1 转录激活子驱动、经 PER/CRY 蛋白复合物反馈抑制、通过 CKIδ/ε 磷酸化延迟形成稳定的~24h 周期，并由 REV-ERB/ROR 辅助回路稳定振幅；在 SCN 神经元中以细胞间 VIP 耦合同步为主时钟，再将时间信号广播全脑全身。

## 当前理解

我们现在认为，昼夜节律分子振荡器（TTFL）是生物计时的普遍原理之一，从真菌到哺乳动物均有功能同源的实现（Hall、Rosbash、Young，2017 年诺贝尔生理学或医学奖，PMID:31236512）。哺乳动物的 TTFL 有几个关键特性使其区别于简单化学振荡：

1. **温度补偿**：在 34–39°C 范围内，振荡周期稳定到±3 分钟/天，比等效化学系统精确数量级。
2. **细胞自主性**：即使将 SCN 分离为单个神经元，每个细胞仍能独立维持约 24 小时的 PER2::LUC 荧光素酶报告基因振荡。
3. **全身分布性**：肝、肺、肌肉、皮肤细胞均有功能性 TTFL；外周时钟以 SCN 为主时钟同步，但在离体培养中可自主振荡（Schibler & Sassone-Corsi 2002, PMID:12507418）。
4. **直接认知功能**：BMAL1 敲除小鼠（全局时钟缺失）表现出显著的学习和记忆损伤，独立于睡眠缺乏本身，提示时钟分子直接参与突触可塑性。
5. **关键期调控**：时钟基因 CLOCK/BMAL1 通过代谢-氧化应激路径调控 PV+ 中间神经元成熟速度，从而决定视觉关键期的开启时间（Reh et al. 2020, PMID:32503914）。

## 关键机制

### 正向臂：CLOCK/BMAL1 激活器复合物

CLOCK 和 BMAL1 均含 bHLH-PAS 结构域，在细胞核内形成异源二聚体：
- 结合靶基因启动子的 **E-box 元件**（CACGTG 共识序列）
- 驱动 *Per1*、*Per2*、*Cry1*、*Cry2*（负反馈组分）以及数百个**时钟控制基因（CCGs）**的转录
- CCGs 覆盖代谢、细胞周期、免疫等广泛生理功能（约占哺乳动物基因组的 10–40%，取决于组织类型）

### 负向臂：PER/CRY 抑制器

PER1/PER2 与 CRY1/CRY2 蛋白在细胞质积累：
- **CKIδ/CKIε 磷酸化 PER**：①促进 β-TrCP E3 泛素连接酶识别 → 蛋白酶体降解（缩短周期）；②在 CRY 存在下，磷酸化状态的 PER/CRY 复合物核转位
- 足够量 PER/CRY 进核后**直接与 CLOCK/BMAL1 结合，抑制其转录活性** → PER/CRY 自身转录停止
- 随着核内 PER/CRY 被逐步降解，抑制解除，新一轮 CLOCK/BMAL1 激活开始
- **回路时间常数**：mRNA 转录→蛋白翻译→磷酸化延迟→核转位 → 完成一个约 24 小时的完整振荡

**FASPS（家族性睡眠相位提前综合征）**：*CKIδ T44A* 突变使 PER 磷酸化加速 → 周期缩短至约 20 小时 → 患者每天比正常人早 4 小时入睡和醒来，是人类 CKI-PER 轴的直接遗传证据。

### 辅助稳定回路：REV-ERB/ROR

CLOCK/BMAL1 还驱动核受体 **REV-ERBα/β**（抑制子）和 **RORα/β/γ**（激活子）的表达：
- REV-ERBα 与 ROR 竞争性结合 *Bmal1* 启动子的 RRE 元件，使 BMAL1 表达平滑振荡
- 增强主回路的鲁棒性；同时，REV-ERBα 抑制 NF-κB 炎症通路，将分子钟与免疫/代谢状态联结
- REV-ERBα 是慢性炎症与昼夜节律紊乱关联的分子基础

### 非 TTFL 时钟（新兴补充机制）

最近发现，某些组织（红细胞、无核细胞）中存在不依赖转录的**过氧化还原蛋白（peroxiredoxin）振荡**（Millius & Bhargava 2019, PMID:31031966），提示进化上更古老的氧化还原振荡可能是 TTFL 的原始前体。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| SCN 移植后节律周期跟随供体（非受体） | 啮齿类 SCN 移植 + 行为节律记录 | PMID:1546306 | 高 |
| BMAL1 KO 小鼠完全失去行为节律 | Bmal1 KO + 行为监测 | PMID:12198538（综述引用） | 高 |
| CKIδ T44A 突变使人类周期缩短→FASPS | 家族遗传分析 + 表达酶活性测定 | Xu et al. 2005（综述） | 高 |
| PER/CRY 直接与 CLOCK/BMAL1 结合抑制转录 | 体外转录实验 + CoIP | PMID:12198538 | 高 |
| 单个 SCN 神经元离体维持约 24h 振荡 | PER2::LUC 小鼠 + 单细胞成像 | PMID:30862123 | 高 |
| CLOCK/BMAL1 调控 PV+ 成熟 → 关键期时序 | Bmal1 神经元特异 KO + 关键期测定 | PMID:32503914 | 中-高 |
| 光照激活 CREB → Per 基因诱导（相位重置） | 体内 RHT 刺激 + 原位杂交 | PMID:20664079 | 高 |

## 连接

- [[scn-circadian-pacemaker]] — SCN 是 TTFL 驱动的主时钟；通过 VIP 耦合使数万细胞同步
- [[pv-interneurons]] — CLOCK/BMAL1 调控 PV+ 中间神经元成熟速度（Reh 2020）
- [[critical-period]] — PV+ 成熟速度决定关键期开启时间；时钟基因 → 关键期时序的直接分子桥梁
- [[rem-sleep]] — 昼夜节律通过 SCN 信号决定 REM 睡眠集中在后半夜的时序分布
- [[cortical-slow-oscillation]] — 昼夜节律决定 NREM 深慢波睡眠（SO 主导）集中在前半夜
- [[memory-consolidation]] — 分子钟直接调控 GluA1 AMPA 受体的日周期表达；LTP 阈值随活跃期/休息期振荡
- [[glymphatic-system]] — 昼夜节律通过 LC-NE 的 NREM 振荡节律性驱动胶质淋巴 CSF 泵送
- [[ltp]] — 海马 LTP 幅度随昼夜节律波动，活跃期显著高于休息期
- [[homeostatic-plasticity]] — 突触稳态缩放的时间窗口受昼夜节律调控
- [[alzheimers-disease]] — SCN 神经元在 AD 早期萎缩；昼夜节律紊乱破坏 Aβ 清除节律
- [[bdnf]] — BDNF 表达受昼夜节律调控，影响 PV+ 成熟的时间轴
- [[norepinephrine-locus-coeruleus]] — LC-NE 系统是昼夜节律输出到睡眠和胶质淋巴系统的关键中间体
- [[neuromodulator-systems]] — 四大调质系统（NE/ACh/DA/5-HT）均受昼夜节律调控，构成时间依赖的认知状态切换

## 未解问题

- Q-circ-01：局部脑区时钟（海马、PFC）与 SCN 主时钟的相对贡献——SCN 萎缩（如衰老或 AD）后局部时钟能否部分代偿？
- Q-circ-02：定时光照 + 褪黑素干预能否稳定昼夜节律进而延缓 AD Aβ 积累？III 期 RCT 证据目前缺失。
- Q-circ-03：SCN 星形胶质细胞的独立功能时钟（Brancaccio et al. 2019）在 AD 中的功能改变：反应性胶质增生是否破坏 SCN 内部的星形胶质-神经元节律耦合？

## 修订历史

- 2026-07-08 · 创建 · 基于《大脑的 24 小时时钟》(#76) · 初始置信度：高 · 综合 13 篇来源（3 篇开放全文）

## 来源文章

- [[2026-07-08-circadian-clock-scn-brain-rhythm]]

---
title: 外侧缰核
slug: lateral-habenula
domain: systems
type: region
status: established
confidence: high
created: 2026-07-11
updated: 2026-07-11
revision_count: 1
dimensions: [molecular, cellular, microcircuit, brain-region, whole-brain-network, behavior, cognition, disease]
related: [dopamine-reward-prediction-error, serotonin-raphe-system, hpa-axis, rmtg, burst-firing-lhb, neuroinflammation, glucocorticoid-hippocampus-plasticity, amygdala, prefrontal-cortex, neuromodulator-systems]
prerequisites: [dopamine-reward-prediction-error, synaptic-transmission, action-potential]
opens_questions: [Q-lhb-01, Q-lhb-02, Q-lhb-03, Q-lhb-04]
source_articles: [2026-07-11-lateral-habenula-depression-ketamine]
key_sources: ["PMID:17522629", "PMID:21832176", "PMID:21350486", "PMID:23990563", "PMID:29446379", "PMID:29446381", "PMID:37853123", "PMID:38863324"]
---

# 外侧缰核 (Lateral Habenula, LHb)

> **一句话定义**：外侧缰核是上丘脑的一对高度进化保守的核团，编码负向奖励预测误差（"事情比预期更糟"），通过谷氨酸能→RMTg→GABA→DA抑制和直接→DRN→5-HT抑制两条并行路径，在厌恶、惩罚和奖励缺失时压制单胺能系统；在抑郁症中，慢性应激诱导的三重分子改变（βCaMKII↑、Kir4.1星形胶质失调、突触前增益↑）将LHb锁定在病理性爆发放电状态，是重度抑郁和快感缺失的主要回路机制。

## 当前理解

外侧缰核（LHb）是大脑"计算坏消息"的核心节点。其功能身份在2007年被确立：LHb神经元的反应模式与多巴胺神经元**完全镜像**——当预期奖励被省略（负向预测误差δ<0）时，DA神经元被抑制而LHb爆发；当超预期奖励出现时，DA爆发而LHb被抑制（PMID:17522629）。

LHb传递这一"坏消息"的机制是**间接的**：LHb谷氨酸能轴突→喙内侧被盖核（RMTg）→GABA能抑制→VTA/SNc多巴胺神经元（PMID:21832176）。同时，LHb也直接向背侧中缝核（DRN）投射，抑制5-HT神经元。这两条并行路径分别负责：快感缺失（DRN→5-HT↓）和动机下降（RMTg→DA↓）。

**在抑郁症中**，LHb发生三重分子改变，从"生理性的惩罚计算器"变为"病理性的持续抑制信号"：

1. **突触前增益增加**：来自脚桥核（EP）、外侧下丘脑（LHA）、内侧前额叶（mPFC）的兴奋性输入在慢性应激后显著增强（mEPSC频率2.3→4.0 Hz，高频比例2%→20%，Li et al. 2011）
2. **βCaMKII驱动的内在兴奋性增加**：βCaMKII上调→GluA1-AMPAR表面表达增至222%→LHb神经元自发放电频率3倍（Li et al. 2013）
3. **星形胶质细胞Kir4.1失调**：Kir4.1上调+位置向神经元胞体迁移→K⁺缓冲异常→LHb神经元静息膜电位超极化→T型Ca²⁺通道去失活→爆发放电锁定（Cui et al. 2018）

**氯胺酮**（ketamine）通过NMDAR使用依赖性**通道捕获**（use-dependent trapping）特异性打破这一锁定：在LHb爆发放电期间，NMDA受体通道高频开放，氯胺酮进入通道孔并被捕获——血药浓度消失（半衰期~13分钟）后，捕获的氯胺酮仍维持通道封锁，持续抑制爆发放电长达24小时（Ma et al. 2023，PMID:37853123）。

**回路特异性**（Wang et al. 2024）：LHb不同输出神经元驱动不同症状——LHb→DRN爆发↑特异性驱动快感缺失和焦虑；同时抑制LHb→DRN/VTA/MnR三路才能缓解绝望感。光疗通过视网膜→vLGN/IGL→LHb的GABA能抑制通路减少爆发，产生抗抑郁效果。

## 关键机制

### 输入来源（信息汇聚）

| 来源 | 信号类型 | 携带信息 |
|------|---------|---------|
| 内侧前额叶（mPFC） | 谷氨酸能 | 认知层面的惩罚评估、被动应对策略 |
| 外侧下丘脑（LHA） | 谷氨酸/GABA混合 | 生存相关厌恶信号（饥饿、疼痛）|
| 室旁核（PVN） | 含CRH的谷氨酸能 | 应激激素，HPA轴激活信号 |
| 脚桥核（EP/腹侧苍白球） | 谷氨酸/GABA混合 | 基底节强化学习结果反馈 |
| 基底外侧杏仁核（BLA） | 谷氨酸能 | 情感性厌恶和恐惧预测 |

### 输出路径（功能分工）

| 靶点 | 递质 | 效果 | 相关症状 |
|------|------|------|---------|
| RMTg → VTA/SNc（DA） | Glu→GABA | 多巴胺抑制 | 动机下降、奖励无感 |
| DRN（5-HT） | 谷氨酸（经GABA中间神经元） | 血清素抑制 | 快感缺失、焦虑 |
| MnR（中缝正中核） | 谷氨酸能 | 5-HT抑制 | 绝望感（与VTA联合）|
| 蓝斑（LC，NE） | 谷氨酸能 | NE调节（机制不完全清楚）| 认知和唤醒影响 |

### 爆发放电的电生理机制

LHb神经元正常以紧张性模式（~4-6 Hz）放电。抑郁状态转变为**爆发性（burst）**：每束3-10个锋电位（>100 Hz），随后沉默，theta频段（4-8 Hz）同步化。

爆发需要两个条件**同时满足**（Yang et al. 2018）：
- NMDA受体激活（Mg²⁺通道开放）
- T型Ca²⁺通道（CaV3）去失活→瞬间Ca²⁺内流

Kir4.1失调通过使静息膜电位超极化，使T型Ca²⁺通道处于"准备就绪"的去失活状态，只需少量兴奋性输入即可触发爆发。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| LHb编码负向奖励预测误差（与DA镜像） | 清醒猕猴单神经元记录+巴甫洛夫奖惩任务 | PMID:17522629 | 高 |
| LHb通过RMTg（GABA）抑制DA神经元（94%受抑制） | 猕猴三区同步记录+电刺激 | PMID:21832176（PMC3315151）| 高 |
| 抑郁大鼠LHb突触前增益增加（mEPSC 2.3→4.0 Hz） | 习得性无助离体膜片钳 | PMID:21350486（PMC3285101）| 高 |
| βCaMKII↑→GluA1↑→LHb超活跃→快感缺失/绝望 | 质谱组学+病毒过表达/敲低+行为 | PMID:23990563（PMC3932364）| 高 |
| Kir4.1星形胶质失调→LHb爆发→抑郁 | 双向操控+电生理+行为 | PMID:29446379 | 高 |
| LHb爆发需NMDAR+T型Ca²⁺；氯胺酮逆转爆发+行为 | 体内电生理+光遗传+药理学 | PMID:29446381 | 高 |
| 氯胺酮NMDAR通道捕获维持24h抑制（半衰期~13min）| 切片电生理+动力学建模+活体 | PMID:37853123（PMC10600008）| 高 |
| LHb→DRN爆发特异驱动快感缺失；三路并抑制→解绝望 | 回路特异性光遗传+化学遗传+多维度行为 | PMID:38863324（PMC11321664）| 中-高 |

## 连接

- [[dopamine-reward-prediction-error]] — LHb通过RMTg提供DA神经元的负预测误差输入（LHb是DA-RPE系统的"上游来源"）
- [[serotonin-raphe-system]] — LHb直接投射至DRN，通过GABA中间神经元抑制5-HT神经元（快感缺失的5-HT机制）
- [[hpa-axis]] — PVN（CRH）→LHb兴奋性输入，双向调节：LHb活动↑也会激活HPA轴
- [[rmtg]] — LHb的关键中继站，将谷氨酸能信号转化为对DA的GABA抑制
- [[neuroinflammation]] — 促炎细胞因子（IL-1β、TNF-α）可增强LHb的输入突触，连接神经炎症与抑郁回路
- [[glucocorticoid-hippocampus-plasticity]] — 皮质醇通过增强LHA→LHb投射，连接HPA失调与LHb过激活
- [[amygdala]] — BLA→LHb投射（厌恶/恐惧预测）；LHb活动也影响杏仁核的恐惧记忆编码
- [[neuromodulator-systems]] — LHb是DA（RMTg路径）和5-HT（DRN路径）两大调质系统的共同上游负调节器

## 未解问题

- Q-lhb-01（高优先级）：LHb是否是氯胺酮起效的唯一关键位点？代谢产物在海马/PFC的AMPAR激活作用有多大？（PMID:34038579指出多靶点可能性；PMID:34097706显示LHb损毁不影响氯胺酮持续效果）
- Q-lhb-02（高优先级）：NMDA受体是否是LHb爆发放电的**必要**条件？（2026年Frontiers新论文存疑）
- Q-lhb-03（中优先级）：Kir4.1失调的上游触发器——慢性应激如何改变星形胶质细胞Kir4.1的表达和分布？是否通过皮质醇GR受体→星形胶质细胞的基因组通路？
- Q-lhb-04（中优先级）：不同抑郁亚型（难治性抑郁、产后抑郁、双相抑郁相）中LHb的活动特征是否相同？人类直接证据（有创iEEG或术中记录）何时能验证？

## 修订历史

- 2026-07-11 · 创建 · 基于《大脑的"惩罚计算器"》一文（#79）· 初始置信度：高

## 来源文章

- [[2026-07-11-lateral-habenula-depression-ketamine]]

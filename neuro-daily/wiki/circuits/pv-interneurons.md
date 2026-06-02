---
title: PV+ 中间神经元（小清蛋白阳性中间神经元）
slug: pv-interneurons
domain: circuits
type: entity
status: established
confidence: high
created: 2026-06-03
updated: 2026-06-28
revision_count: 3
dimensions: [cellular, synaptic, microcircuit, cognition]
related: [chandelier-cell, sst-interneurons, vip-interneurons, disinhibitory-circuit, theta-oscillations, dendritic-computation, hippocampal-circuit, working-memory, gamma-oscillations, prefrontal-cortex, critical-period]
prerequisites: [action-potential, synaptic-transmission, axon-initial-segment]
opens_questions: [Q-pv-schizophrenia-causal, Q-pv-gamma-necessary]
source_articles: [2026-06-03-inhibitory-interneuron-diversity, 2026-06-28-critical-period-visual-cortex]
key_sources: ["PMID:27477017", "PMID:18599766", "PMID:24429630", "PMID:22219337", "PMID:25863358", "PMID:26996084", "PMID:39381500", "PMID:41478518"]
---

# PV+ 中间神经元（Parvalbumin-expressing Interneurons）

> **一句话定义**：以小清蛋白（PV）为分子标记的快速放电 GABA 能中间神经元，靶向锥体细胞的胞体和近端树突，通过毫秒级精确抑制实现皮层时序控制和 γ 振荡的产生。

## 当前理解

我们现在认为，PV+ 中间神经元构成新皮层 GABA 能神经元中最大的一类（约占 40%），并在皮层局部回路的时序控制中发挥核心作用。它们主要分化为**篮状细胞（basket cells）**（靶向胞体和近端树突）和**吊灯细胞（chandelier cells）**（靶向轴突始段，详见 [[chandelier-cell]]），两者均发育自内侧神经节隆起（MGE），受 Nkx2.1 基因调控。

PV+ 细胞的核心特征是"快速放电"（fast-spiking）：动作电位极短（峰宽约 300 μs），高频刺激下几乎不适应，大而快的后超极化（AHP）使其能快速复极并再放电。在突触传递层面，PV+ 篮状细胞到锥体细胞的突触延迟平均仅 **0.7 ms**，抖动（jitter）仅 **0.19 ms**（Tremblay et al., 2016, PMID:27477017），是已知皮层突触中时间精度最高的类型之一。

PV+ 细胞通过围胞体的强力、精确抑制实现两项关键计算：（1）将锥体细胞的放电限定在窄时间窗口（时序精度）；（2）通过 PV↔PV 和 PV→锥体细胞的 PING 回路产生和维持皮层 **γ 振荡（30–80 Hz）**。

在精神分裂症中，前额叶 PV+ 细胞的 GAD67 下调导致 γ 振荡受损，与工作记忆缺陷直接相关，为 PV+ 细胞在认知控制中的必要性提供了临床证据。

## 关键机制

**分子层面**：
- PV（小清蛋白）是钙缓冲蛋白，本身可能调节细胞内 Ca²⁺ 动力学
- 表达 Kv3 型电压门控钾通道，驱动快速复极，是 fast-spiking 表型的分子基础
- 表达 α1 亚型 GABA-A 受体（突触后），介导快速 Cl⁻ 内流

**细胞层面**：
- 篮状细胞：多极形态，轴突末梢形成密集的"篮"包绕目标锥体细胞胞体
- 吊灯细胞：轴突终止于 AIS，形成"吊灯"状末端（详见 [[chandelier-cell]]）

**回路层面**：
- PV+ 细胞接受来自锥体细胞的兴奋性突触（反馈抑制）和丘脑的直接兴奋输入
- PV+ 细胞之间通过缝隙连接（电突触）相互耦合，增强同步性
- VIP+ 中间神经元可抑制 PV+ 细胞（去抑制回路，见 [[disinhibitory-circuit]]）

**系统层面（2026-06-05 更新）**：
- γ 振荡产生：PING（锥体细胞-中间神经元-γ）回路中，锥体细胞激活 PV+ 细胞，PV+ 细胞反馈抑制锥体细胞，形成 30–80 Hz 振荡；在 PFC 中表现为间歇性 γ 爆发（~67 ms/次）而非持续振荡（Lundqvist et al. 2016, PMID:26996084, PMC:PMC5220584）
- 工作记忆：dlPFC PV 篮状细胞通过 γ 爆发为工作记忆的间歇性信息编码提供时序框架；β 振荡（20–35 Hz）出现于 γ 爆发间隔，代表默认静息态
- 精神分裂症病理（Hughes et al. 2024, PMID:39381500, PMC:PMC11458443）：dlPFC 中 PV mRNA 和 GAD67 减少 → γ 功率降低 → 工作记忆缺陷，三者高度相关

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| PV+ 篮状细胞突触延迟 0.7 ms，jitter 0.19 ms | 双细胞膜片钳（30°C 条件）| PMID:27477017 | 高 |
| PV+ 占皮层 GABA 能神经元约 40% | 分子标记 + 细胞计数 | PMID:21154909 | 高 |
| 光遗传学激活/抑制 PV+ 细胞可驱动/消除皮层 γ 振荡 | ChR2/ArchT 光遗传学 | PMID:24429630 (review) | 高 |
| 精神分裂症前额叶 PV+ 细胞 GAD67 mRNA 下调 | 原位杂交（死后脑组织）| PMID:22219337 | 高 |
| 精神分裂症患者工作记忆任务期间前额叶 γ 功率下降 | MEG/EEG | PMID:25863358 | 高 |
| 篮状细胞在 SWR 期间强烈放电，相位锁定到涟漪周期 | 清醒大鼠 CA1 体内记录 | PMID:18599766 | 高 |

## 连接

- [[chandelier-cell]] — PV+ 亚类，专门靶向轴突始段
- [[sst-interneurons]] — 并列的 MGE 来源抑制性家族，靶向树突
- [[vip-interneurons]] — VIP+ 细胞可抑制 PV+，形成去抑制回路
- [[disinhibitory-circuit]] — VIP→PV/SST→锥体细胞的门控机制
- [[theta-oscillations]] — PV+ 篮状细胞在海马 θ 相位特定时刻放电
- [[hippocampal-circuit]] — CA1 篮状细胞 + 吊灯细胞是海马主要 PV+ 类型
- [[action-potential]] — PV+ 细胞对锥体细胞动作电位的产生实施时序控制
- [[axon-initial-segment]] — 吊灯细胞（PV+ 亚类）靶向 AIS

## 未解问题

- Q-pv-schizophrenia-causal：精神分裂症中 PV+ 细胞 GAD67 下调是病因、代偿还是继发改变？
- Q-pv-gamma-necessary：PV+ 细胞是 γ 振荡的必要产生者，还是只是与 γ 相关的贡献者之一？

## 修订历史

- 2026-06-03 · 创建 · 基于《回路中的少数精锐》一文 · 初始置信度：高
- 2026-06-05 · 修订 · 基于《γ爆发、静默突触与持续放电》一文 · 系统层面新增：PFC γ爆发WM应用、精神分裂症病理证据（PMID:26996084, PMC5220584; PMID:39381500, PMC11458443; PMID:41478518）；related 新增 working-memory, gamma-oscillations, prefrontal-cortex；dimensions 新增 cognition
- 2026-06-28 · 修订 · 基于《发育的窗口：大脑关键期如何开启、关闭与重启》(#64) · 新增发育维度：PV 细胞成熟是关键期启动的核心机制（Hensch 1998, PMID:9822384）；related 新增 critical-period；source_articles 新增 2026-06-28-critical-period-visual-cortex

## 来源文章

- [[2026-06-03-inhibitory-interneuron-diversity]]
- [[2026-06-05-prefrontal-working-memory]]
- [[2026-06-28-critical-period-visual-cortex]]

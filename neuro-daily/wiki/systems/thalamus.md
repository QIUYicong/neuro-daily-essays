---
title: 视丘
slug: thalamus
domain: systems
type: region
status: established
confidence: high
created: 2026-06-03
updated: 2026-08-02
revision_count: 6
dimensions: [molecular, cellular, microcircuit, brain-region, whole-brain-network, cognition]
related: [thalamocortical-circuit, thalamic-firing-modes, sleep-spindles, working-memory, prefrontal-cortex, v1-primary-visual-cortex, neural-correlates-of-consciousness, gain-control, dorsal-attention-network, alpha-oscillations, auditory-cortex, pain-matrix, nociceptor]
prerequisites: [action-potential, synaptic-transmission, voltage-gated-calcium-channels]
opens_questions: [Q-thalamus-burst-awake, Q-thalamus-consciousness-causal, Q-matrix-vs-core-function, Q-thalamus-gating-mechanism, Q-dan-01]
source_articles: [2026-06-03-thalamus-gatekeeper-cognition, 2026-07-01-dorsal-attention-network-FEF-IPS, 2026-07-22-alpha-oscillations-attention-wm, 2026-07-28-auditory-cortex-tonotopy, 2026-08-02-pain-nociception-spinal-dorsal-horn-acc]
key_sources: ["PMID:35803270", "PMID:29275841", "PMID:29184210", "PMID:22561455", "PMID:40642212", "PMID:26776512", "PMID:11164943", "PMID:11994752", "PMID:31972202", "PMID:19837031"]
---

# 视丘 (Thalamus)

> **一句话定义**：视丘是位于大脑深部的一对卵圆形核团，通过三重功能——感觉信号门控（TRN）、皮层间信号中转（高次核）与皮层认知状态放大（MD-PFC 轴）——主动参与感知、注意、工作记忆和意识状态的调控。

## 当前理解

我们现在认为，视丘不是一个被动的"感觉中继站"，而是一台**主动的认知路由器**。它解决了大型皮层网络的核心架构问题：在数百个皮层功能区域之间，如何高效、动态地调配信息流的带宽和优先级。

视丘通过三个层次的机制实现这一目标：

1. **门控层（TRN）**：视丘网状核（TRN）作为纯 GABAergic 薄层，接受所有上行/下行视丘-皮层轴突的侧支，从而感知和控制通过视丘的一切信号。前额叶通过大型驱动型突触端钮指令 TRN，感觉皮层只能以小型调制型端钮请求 TRN——这种解剖学权力不对称，是注意自上而下控制的回路基础（Zikopoulos & Barbas 2006, PMID: 16837581）。

2. **中转层（高次核）**：高次视丘核（枕核、MD、LP 等）接受皮层第 V 层的驱动输入，并投射到其他皮层区域——形成"皮层 A → 高次视丘 → 皮层 B"的经视丘通路，与直接皮层内连接并行（Sherman 2024, J Neurosci）。

3. **放大层（MD-PFC 轴）**：背内侧核（MD）接受 PFC 第 V 层输入并广泛反馈至 PFC。工作记忆任务中，MD 维持**延迟期晚期**的 PFC 活动，充当"认知放大器"；MD 抑制损害认知灵活性（反转学习）（Parnaudeau et al. 2018, PMID: 29275841）。

## 关键结构

### 1. 视丘中继核（TC Neurons）
- 谷氨酸能；投射到皮层第 IV 层（感觉核）或第 I/V/VI 层（非感觉核）
- 具有两种放电模式（见 [[thalamic-firing-modes]]）：强直（tonic）与爆发（burst）
- 爆发依赖 T 型 Ca²⁺ 通道（CaV3.1/CaV3.3）的去失活

### 2. 视丘网状核（TRN）
- 纯 GABAergic，包裹视丘表面；高度表达 CaV3.3
- 功能三重：（1）注意门控；（2）NREM 睡眠纺锤波起搏器；（3）感觉状态切换
- PFC→TRN 大型端钮（驱动型），感觉皮层→TRN 小型端钮（调制型）

### 3. 一次视丘核（First-Order Nuclei）
- LGN（外侧膝状体，视觉）；VPM（腹后内核，触觉/本体）；MGN（内侧膝状体，听觉）
- 驱动输入来自外周感觉通路末梢
- **MGBv（内侧膝状体腹侧核）**：听觉通路的最终中继站，接受下丘（IC）的精确音调拓扑投射，保真地将耳蜗 cochleotopic map 传递至初级听觉皮层 A1；MGBd（背侧核）和 MGBm（内侧核）投射至听觉旁带状区和边缘结构，参与情绪-听觉整合

### 4. 高次视丘核（Higher-Order Nuclei）
- 枕核（Pulvinar）：视觉系统，连接全视觉皮层层级；灭活→V1 反应几乎消失（Purushothaman 2012, PMID: 22561455）
- 背内侧核（MD）：PFC 的主要视丘搭档；认知灵活性与工作记忆放大
- 外侧后核（LP）：顶叶关联区

### 5. 痛觉丘脑核团（Pain-Specific Thalamic Nuclei）

痛觉上行通路（脊髓丘脑束，STT）在丘脑层面分两路：

| 核团 | 接收输入 | 投射目标 | 功能 |
|------|---------|---------|------|
| **VPL（腹后外侧核）** | STT 板层Ⅰ/Ⅴ投射神经元（新脊丘束） | S1/S2 皮层 | 精确痛觉定位、强度编码（感觉-分辨维度） |
| **VMpo（腹后内侧核后部）** | STT 板层Ⅰ NK1R+ 投射神经元（旁脊丘束） | 岛叶后部、ACC | 情感性疼痛（不愉快度）、温度感知 |
| **MDvc（背内侧核腹侧小细胞部）** | 脊髓板层Ⅰ输入 | ACC | 疼痛-情感整合 |

这一分叉解释了为何 VPL 病变→定位精确度丧失，而 cingulotomy 仅消除"痛苦感"而保留定位能力——两条通路在丘脑即分道扬镳（Basbaum et al. 2009, PMID:19837031）。

### 5. 髓板内核群（Intralaminar Nuclei）
- CM-Pf（中央核-束旁核）：兼具 core/matrix 投射；与意识状态关联最强（Cacciatore et al. 2025, PMID: 40642212）
- 中央核（CL）：广泛皮层投射；DBS 靶点（意识障碍治疗）

## 关键机制

### 双模放电（修订于 2026-06-30）
见 [[thalamic-firing-modes]] 专页详细讲解。

**修订前理解**（旧模型）：高 ACh 清醒状态 → 强直模式；低 ACh/NREM 睡眠 → 爆发模式。爆发被认为仅与睡眠/麻醉相关，与感觉信息传递无关。

**修订后理解**（Borden et al. 2022, PMID:35803270, 清醒小鼠因果实验）：清醒 VPm 核中约 15% 的感觉诱发响应为爆发放电。光遗传增强爆发比率至 ~30% 后，皮层响应幅度不变，但**时序精度显著提升**，皮层快速棘波单元（FSU，抑制性中间神经元）成对同步性增强，形成约 10 ms 的感知"机会窗"。爆发放电实现的是**基于时序的感知门控**，而非信号放大。

感觉适应连续调控爆发-强直比率（Whitmire et al. 2016, PMID:26776512）：爆发端利于检测（是否有刺激），强直端利于辨别（刺激细节）。

### 驱动/调制框架（Sherman & Guillery 1998, PMID: 9618549）
- **驱动型输入**（RL/driver）：携带感受野信息；大突触端钮；高概率释放；AMPA+NMDA
- **调制型输入**（RS/modulator）：改变传递效率；小突触端钮；低概率释放；含 mGluR

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 枕核是 V1 运转的主动维持者 | 灵长类枕核灭活 → 95% V1 反应消失 | PMID:22561455（PMC3430824）| 高（因果） |
| MD 维持工作记忆晚期延迟活动 | 光遗传 MD 抑制 + 延迟任务 | 综述 PMID:29275841（PMC5862748）| 高 |
| PFC→TRN 大型驱动型端钮 | 猕猴 EM + 3D 重建 | PMID:16837581（PMC6674204）| 高（解剖学）|
| CM-Pf 与意识相关性最强 | 系统综述 167 篇文章 | PMID:40642212（PMC12241866）| 中-高 |
| 清醒视丘爆发有独立功能 | 清醒小鼠光遗传 + 电记录 | PMID:35803270（PMC9464711）| 高（因果） |

## 连接

- [[thalamocortical-circuit]] — TC⟷TRN 振荡回路；核心/矩阵通路；详细回路结构
- [[thalamic-firing-modes]] — tonic vs burst 双模切换的离子通道机制
- [[sleep-spindles]] — TRN CaV3.3 爆发驱动的 TRN⟷TC 振荡=纺锤波起搏器
- [[alpha-oscillations]] — 枕核（Pulvinar）/LP通过TRN-TC回路产生清醒α振荡，同步调制多个皮层区域α功率（广播式α门控）
- [[working-memory]] — MD 维持 PFC 工作记忆晚期延迟活动
- [[prefrontal-cortex]] — MD 是 PFC 的主要视丘搭档（双向驱动连接）
- [[v1-primary-visual-cortex]] — Pulvinar 灭活→V1 反应消失；视觉注意空间门控
- [[neural-correlates-of-consciousness]] — CM-Pf 与意识状态；DBS 临床证据
- [[gain-control]] — TRN 介导皮层-视丘增益调控
- [[auditory-cortex]] — MGBv 精确拓扑投射至 A1，保真传递耳蜗 cochleotopic 频率地图
- [[pain-matrix]] — VPL/VMpo/MDvc 是痛觉矩阵的丘脑接入点，分别对接感觉-分辨和情感两条通路
- [[nociceptor]] — 伤害感受器信号经脊髓背角→STT→VPL/VMpo 上传

## 未解问题

- Q-thalamus-burst-awake：清醒爆发已确认有功能（时序精度提升），但触发机制仍开放：TRN 注意转移超极化 vs 适应性 KATP 超极化？两者比例如何？（部分回答：见 2026-06-30 文章）
- Q-thalamus-consciousness-causal：视丘损伤本身导致意识丧失，还是只是皮层网络崩溃的先导？DBS 恢复意识的机制？
- Q-matrix-vs-core-function：矩阵通路（弥散性 intralaminar→全皮层 L1）的功能与核心通路有何本质区别？
- Q-thalamus-gating-mechanism：PFC→TRN→视丘核如何实现感觉注意的精确空间门控？

## 修订历史

- 2026-06-03 · 创建 · 基于《视丘的三张面孔》文章 #66 · 整合 TC/TRN 解剖学、双模放电机制、MD-PFC 认知放大、Pulvinar 视觉门控和 CM-Pf 与意识的多层证据 · 初始置信度：高
- 2026-06-30 · 修订（rev2） · 基于文章 #66《视丘的双面人格》· 更新"双模放电"小节：加入 Borden 2022 清醒因果实验结果（爆发→时序精度↑非幅度↑）和 Whitmire 2016 爆发-强直连续谱；更新 Q-thalamus-burst-awake 状态为"部分回答"；新增 key_sources 2 条

- 2026-07-01 · 修订（rev3） · 基于文章 #67《空间注意的神经回路》· 新增 DAN（FEF/IPS）→TRN 通路作为皮层注意信号向下传递的接口；回答了 Q-thalamus-gating-mechanism 中关于 FEF→TRN 感觉门控的部分机制；related 新增 dorsal-attention-network；新增 Q-dan-01 交叉引用
- 2026-07-22 · 修订（rev4） · 基于文章 #90《α振荡》· 新增枕核/LP作为清醒α振荡的广播来源（TRN-TC回路→α同步多皮层区域）；related新增alpha-oscillations；key_sources新增PMID:31972202
- 2026-07-28 · 修订（rev5） · 基于文章 #96《从蜗旋到皮层音图》· 新增 MGBv/MGBd/MGBm 三区功能分化（腹侧核→精确音调拓扑投射至 A1；背侧核/内侧核→旁带状区/边缘系统）；连接节新增 auditory-cortex；related 新增 auditory-cortex；source_articles 新增 2026-07-28-auditory-cortex-tonotopy
- 2026-08-02 · 修订（rev6） · 基于文章 #101《痛觉的守门人》· 新增"痛觉丘脑核团"小节（VPL→S1感觉分辨通路；VMpo→岛叶/ACC情感通路；MDvc→ACC）；related 新增 pain-matrix, nociceptor；source_articles 新增 2026-08-02-pain-nociception-spinal-dorsal-horn-acc；key_sources 新增 PMID:19837031

## 来源文章

- [[2026-06-03-thalamus-gatekeeper-cognition]]
- [[2026-06-30-thalamic-burst-t-type-calcium-timing-gate]]
- [[2026-07-01-dorsal-attention-network-FEF-IPS]]
- [[2026-07-22-alpha-oscillations-attention-wm]]
- [[2026-07-28-auditory-cortex-tonotopy]]
- [[2026-08-02-pain-nociception-spinal-dorsal-horn-acc]]

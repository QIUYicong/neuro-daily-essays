---
title: 视交叉上核（SCN 主时钟）
slug: scn-circadian-pacemaker
domain: systems
type: region
status: established
confidence: high
created: 2026-07-08
updated: 2026-07-08
revision_count: 1
dimensions: [molecular, cellular, brain-region, whole-brain-network, cognition, disease]
related: [circadian-clock, memory-consolidation, glymphatic-system, rem-sleep, cortical-slow-oscillation, alzheimers-disease, neuromodulator-systems, norepinephrine-locus-coeruleus, thalamus]
prerequisites: [circadian-clock, synaptic-transmission]
opens_questions: [Q-circ-01, Q-circ-02, Q-circ-03]
source_articles: [2026-07-08-circadian-clock-scn-brain-rhythm]
key_sources: ["PMID:1546306", "PMID:11805301", "PMID:12198538", "PMID:19798445", "PMID:30630934", "PMID:20664079", "PMID:38590628"]
---

# 视交叉上核（SCN 主时钟）(Suprachiasmatic Nucleus — Master Circadian Pacemaker)

> **一句话定义**：位于下丘脑前部视交叉正上方的成对微小核团（人类约双侧共 50,000 个神经元），通过细胞间 VIP/VPAC2 和缝隙连接将数万个各自振荡的 TTFL 神经元同步为单一精确主时钟，再经三条输出路径（自主神经→褪黑素、直接神经投射、体液肽信号）将约 24 小时节律广播全脑全身。

## 当前理解

我们现在认为，SCN 是哺乳动物昼夜节律的**必要且充分的主时钟**：双侧 SCN 切除使所有行为和激素节律消失，而胚胎 SCN 组织的移植可以将节律恢复——且恢复的节律周期完全由**供体 SCN**决定（Ralph et al. 1990, PMID:1546306，Science 经典实验）。

SCN 的独特性在于其**精度来自耦合而非单细胞**：离体单个 SCN 神经元可独立振荡，但细胞间相位会逐渐漂移；完整 SCN 中，VIP 神经元（核心区）通过 VPAC2 受体耦合实现全群体同步，使集体振荡精度比单细胞高出约 20 倍。

**SCN 的功能分区**：
- **腹侧核心（Ventral Core）**：富含 VIP 神经元；直接接受视网膜下丘脑束（RHT）的光输入；对光最先响应；通过 VIP 向背侧壳区传递相位信息
- **背侧壳区（Dorsal Shell）**：富含 AVP（精氨酸加压素）神经元；整合来自核心区的相位信号；是 SCN 的主要输出站，投射至下丘脑室旁核（PVN）、背内侧下丘脑（DMH）等

**SCN 在衰老和 AD 中的早期受损**：神经病理研究表明，SCN VIP 神经元密度在 AD 患者中显著降低，且与 tau 病理扩散的 Braak 分期早期相关——提示 SCN 萎缩是 AD 病程中节律紊乱和胶质淋巴清除减退的早期驱动因素之一。

## 关键机制

### 1. 光输入：视网膜下丘脑束（RHT）

光线通过**内在光敏视网膜神经节细胞（ipRGC）** 中的黑视素（melanopsin）感知（对~480 nm 蓝绿光最敏感，Berson et al. 2002, PMID:11805301）。ipRGC 通过 RHT 将信号直接传递至 SCN 核心区：
- 谷氨酸 + PACAP → NMDA 受体 → Ca²⁺ → CaMKII → CREB 磷酸化 → *Per1/Per2* 快速诱导
- **相位响应曲线（PRC）**：主观夜晚早期光照 → Per 基因诱导 → 时钟相位延后；主观夜晚后期光照 → 时钟相位提前；白天光照几乎无效（时钟已处于活跃期）

### 2. 细胞间耦合同步

- **VIP/VPAC2 轴**：核心区 VIP 神经元释放 VIP，激活壳区神经元 VPAC2 受体 → cAMP → PKA → CREB → *Per1* 诱导，将各神经元的振荡相位拉向统一
- **缝隙连接（Gap junctions）**：Cx36 缝隙连接提供电学耦合，加速邻近神经元间的相位同步
- **星形胶质细胞反馈**：SCN 内星形胶质细胞有功能性 TTFL，通过谷氨酸/ATP 释放向神经元反馈，影响整体节律振幅（Brancaccio et al. 2019, PMID:30630934）

### 3. 三条输出路径

#### 路径一：自主神经系统 → 松果体 → 褪黑素

SCN（壳区）→ PVN → 脊髓 IML → 颈上交感神经节 → 松果体：
- 夜间 SCN 去激活 → NE 释放 → β1-AR → cAMP → AANAT↑ → 血清素 → 褪黑素合成分泌
- 褪黑素经 MT1/MT2 受体向全脑传递"现在是夜晚"的时间信号
- **重要限制**：褪黑素本身不产生睡意，只传递时间信号；真实睡眠驱动来自腺苷积累（稳态过程 S）

#### 路径二：直接神经投射（SCN→DMH→脑干）

- SCN → DMH → LC（蓝斑核）：调控 NE 系统的昼夜节律振荡（日间高 NE，夜间 NREM 时~0.05 Hz 慢振荡）
- SCN → DMH → VLPO（腹外侧视前区）：通过中间神经元调控 VLPO 抑制觉醒中枢（LC/Raphe/TMN）的时机
- SCN → 海马/杏仁核（多突触）：通过内侧前脑束调控边缘系统兴奋性状态的昼夜相位

#### 路径三：体液肽信号

- **AVP（壳区）**：白天高分泌 → 整脑 V1b 受体 → 促觉醒效果
- **PROK2（Prokineticin 2）**：作用于边缘前脑 PROKR2 → 直接促进清醒；PROK2 受体缺失小鼠昼夜节律减弱

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| SCN 切除消除节律；移植恢复并由供体决定周期 | SCN 损毁 + 胎鼠 SCN 移植 + tau 突变移植 | PMID:1546306 | 高 |
| ipRGC/黑视素是昼夜节律光输入通路 | 视杆/视锥完全缺失小鼠仍保持光同步 + Opn4 KO | PMID:11805301 | 高 |
| SCN 星形胶质细胞有独立功能时钟 | SCN 特异 TTFL 破坏（仅限胶质细胞） | PMID:30630934 | 中-高 |
| 人脑 CSF Aβ 昼夜节律波动；睡眠剥夺使 Aβ 升高 | 人类 CSF 时间序列采集 + 睡眠剥夺 | PMID:19798445 | 高 |
| SCN VIP 神经元密度在 AD 早期降低 | 神经病理定量 + Braak 分期相关 | 综述（PMID:38590628）| 中 |

## 连接

- [[circadian-clock]] — TTFL 是 SCN 每个神经元产生节律的分子机制；SCN 是 TTFL 的系统整合层
- [[glymphatic-system]] — SCN→LC-NE 路径产生 NREM 期 ~0.05 Hz NE 振荡，驱动胶质淋巴 CSF 泵送
- [[rem-sleep]] — SCN 通过 NE/ACh 节律决定 REM 睡眠集中在后半夜的时序
- [[cortical-slow-oscillation]] — SCN 决定 NREM 深慢波睡眠（SO 主导）的昼夜时序，前半夜最多
- [[memory-consolidation]] — SCN 编排记忆固结的最优时间窗口（NREM 深睡→陈述性；REM→情绪记忆）
- [[alzheimers-disease]] — SCN 萎缩是 AD 昼夜节律紊乱和胶质淋巴清除减退的上游病理节点
- [[norepinephrine-locus-coeruleus]] — LC-NE 是 SCN 输出到睡眠调控和胶质淋巴系统的核心中间节点
- [[neuromodulator-systems]] — SCN 通过 LC/Raphe/VTA 的节律性调控，协调四大调质系统的昼夜工作模式
- [[thalamus]] — SCN→丘脑室旁核（PVT）通路是昼夜节律信号传递到前脑的重要中间站

## 未解问题

- Q-circ-01：局部脑区时钟（海马、PFC）与 SCN 的相对贡献——SCN 萎缩后局部时钟能否部分代偿？
- Q-circ-02：定时光照和褪黑素干预能否稳定昼夜节律、延缓 AD Aβ 积累？III 期 RCT 证据缺失。
- Q-circ-03：SCN 星形胶质细胞时钟在 AD 中的功能改变——反应性胶质增生是否破坏 SCN 节律耦合？

## 修订历史

- 2026-07-08 · 创建 · 基于《大脑的 24 小时时钟》(#76) · 初始置信度：高 · 综合 8 篇来源

## 来源文章

- [[2026-07-08-circadian-clock-scn-brain-rhythm]]

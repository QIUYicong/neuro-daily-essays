---
title: 缝隙连接与神经元电突触（Connexin-36）
slug: gap-junction-electrical-synapse
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-10-06
updated: 2026-10-07
revision_count: 2
dimensions: [molecular, cellular, synaptic, microcircuit]
related: [pv-interneurons, gamma-oscillations, sharp-wave-ripple, place-cell, voltage-gated-sodium-channel, action-potential, synaptic-transmission, inferior-olive, climbing-fiber]
prerequisites: [action-potential, synaptic-transmission, pv-interneurons]
opens_questions: [Q-gap-01, Q-gap-02, Q-gap-03, Q-gap-04, Q-io-01]
source_articles: [2026-10-06-gap-junction-electrical-synapse, 2026-10-07-inferior-olive-cx36-motor-learning]
key_sources: ["PMID:11516403", "PMID:11516404", "PMID:12574431", "PMID:15217338", "PMID:21525295", "PMID:22659675", "PMID:28245529", "PMID:38616956", "PMID:42129559", "PMID:18498740", "PMID:21151372", "PMID:29311830"]
---

# 缝隙连接与神经元电突触 (Gap Junction / Electrical Synapse, Connexin-36)

> **一句话定义**：由 Connexin-36（Cx36）蛋白组成、成年哺乳动物大脑中神经元间电突触的主要类型，以亚毫秒延迟双向传导离子电流，是 PV+ 快速放电中间神经元伽马振荡同步的物质基础。

## 当前理解

我们现在认为，成年哺乳动物大脑皮层和海马中存在功能性神经元电突触，主要由 **Connexin-36（Cx36）**蛋白构成，选择性表达于**PV+ 快速放电（FS）中间神经元**（及部分其他类型神经元）。Cx36 缝隙连接允许离子电流以约 0.1–0.5 ms 的延迟在两个神经元之间双向传导，比化学突触（0.5–2.0 ms）快 5–10 倍。

Cx36 电突触的核心功能是为 PV+ 中间神经元网络提供**初始同步模板**：在 ING 和 PING 伽马振荡机制中，电偶联在化学 GABA 突触的抑制周期之前完成快速同步，使整个 PV+ 网络能以精确的时序同步放电，产生 30–80 Hz 伽马振荡。

遗传学实验证明，Cx36 缺失**选择性消除伽马振荡**（30–80 Hz），而不影响更高频的尖波纹波（140–200 Hz），揭示了不同频段振荡依赖不同同步机制的基本原理。

Cx36 并非固定"硬线"——其通道导电性受 PKA（Ser110/293 磷酸化）、CaMKII 以及多巴胺、去甲肾上腺素等神经调质动态调节，使伽马振荡强度可随大脑状态变化。

最新突破（LinCx, 2025）展示了工程化电突触的可能性：设计正交连接蛋白对，在指定细胞对之间精确重建电偶联，并改善小鼠行为。

## 关键机制

**分子层面**：
- Cx36 是神经元特异性连接蛋白，由 6 个 Cx36 单体组成一个半通道（connexon），两相邻细胞各贡献一个半通道对接成完整通道
- 通道孔径约 1.2 nm，允许离子和 <1 kDa 小分子（cAMP、IP₃）双向通过
- Cx36 C 末端含 Ser110、Ser293（PKA 位点）和 CaMKII 结合域
- **低通滤波特性**：慢膜电位变化传导效率高，高频尖峰被部分衰减（典型偶联系数 0.05–0.15）

**细胞层面**：
- 电偶联仅占动作电位幅度的 5–15%，不足以单独触发靶细胞放电
- **双相耦合电位**：A 细胞放电 → B 细胞先短暂去极化（Cx36 电流，~0–3 ms）→ 再超极化（化学 GABA，~3–10 ms）
- 偶联效率受目标细胞输入阻抗影响（小细胞被更强去极化）

**突触/回路层面**：
- PV+ FS 中间神经元之间形成"电偶联子网络"，可在化学突触参与之前实现初始时序对齐
- 电突触与化学 GABA 突触**协同**而非竞争：电偶联提供同步模板，GABA 衰减时间常数（τ_decay）决定振荡频率
- 下橄榄核（IO）中 Cx36 支持 4–10 Hz 亚阈值振荡（STO），将相邻 IO 神经元相位锁定，形成同步误差广播——详见 IO 专属功能节

**IO Cx36 的专属功能：同步运动误差时钟**（2026-10-07 新增）

下橄榄核（inferior olive）是 Cx36 大脑中密度最高的脑区之一，其 Cx36 功能与皮层 PV+ 回路截然不同：

- **频率更低**：IO STO 为 4–10 Hz（vs 皮层 gamma 30–80 Hz）；Cx36 在此处同步的是慢振荡，而非高频振荡
- **功能不同**：皮层 Cx36 同步兴奋性传导时序→驱动 gamma 振荡；IO Cx36 同步误差信号时间戳→驱动运动学习时序精度
- **调控回路不同**：IO Cx36 受小脑深核（DCN）GABAergic 反馈门控（Lefler et al. 2014），而皮层 Cx36 主要受 PKA/多巴胺调控
- **行为学证据更直接**：甲氟喹（mefloquine）阻断 IO Cx36 → 人类运动学习速度和容量受损，基础运动保留（van Essen et al. 2010）；Cx36 KO 小鼠 CS 时序变异增大、运动学习时机受损（Van Der Giessen et al. 2008）

这表明 Cx36 是一种**功能多样的同步硬件**，通过部署在不同回路中（皮层 PV+ 网络 vs IO 树突小球）实现截然不同的计算目标——同一分子，不同语境，不同计算。

**可塑性**：
- PKA（多巴胺 D1R→cAMP→PKA）磷酸化 → 偶联**降低**
- CaMKII（活动/NMDA/Ca²⁺ 依赖）→ 偶联**增强或降低**（双向，取决于磷酸化位点）
- 多巴胺、去甲肾上腺素、组胺、内源性大麻素均可在分钟—小时尺度动态调节

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| Cx36 是皮层 PV+ FS 细胞电偶联的主要载体（>90% 偶联消失于 KO） | 双细胞 patch-clamp in vitro，Cx36 KO vs WT | PMID:11516403 | 高 |
| Cx36 KO 选择性消除伽马振荡，保留高频（~150 Hz） | 海马脑片 LFP，carbachol 诱发，KO vs WT | PMID:11516404 | 高 |
| 体内自由活动小鼠：Cx36 KO 降低跑步期伽马，不影响尖波纹波 | 体内 CA1 LFP，Cx36 KO vs WT | PMID:12574431 / PMC6741916 | 高 |
| Cx36 KO 损害地点细胞空间选择性和短期空间记忆 | 体内 CA1 记录 + 行为测试，Cx36 KO vs WT | PMID:21525295 / PMC3160467 | 高 |
| Cx36 受 PKA（Ser110/293）和 CaMKII 磷酸化调节偶联强度 | 生化 + 电生理 + 成像（综述） | PMID:22659675 / PMC3437247 | 中 |
| 工程化 LinCx 可选择性重建特定细胞对偶联，改善小鼠行为 | 分子工程 + 体内行为，小鼠 | PMID:42129559 / PMC11974911 | 新兴 |
| IO Cx36 KO：CS 时序变异增大，运动学习时机受损；运动执行保留 | Cx36 KO 小鼠；多电极体内记录+条件性眨眼 | PMID:18498740 | 高 |
| 甲氟喹（IO Cx36 阻断剂）损害人类运动学习速度和容量，不影响基础运动 | 随机对照，健康志愿者 | PMID:21151372 | 高 |
| PKA → IO Cx36 开放概率降低；βCaMKII KO → IO Cx36 数量 87→1/mm² | 基因 KO + 免疫组化，小鼠 IO | PMID:29311830 | 高 |

## 连接

- [[pv-interneurons]] — 皮层 Cx36 电突触的主要宿主神经元类型
- [[inferior-olive]] — IO 树突小球中 Cx36 的另一关键部署：同步运动误差时钟（4–10 Hz）
- [[climbing-fiber]] — IO Cx36 同步的直接下游：CF 时序精度和 CS 同步性
- [[gamma-oscillations]] — Cx36 是 ING 机制中初始同步的物质基础；伽马频段对 Cx36 有选择性依赖
- [[sharp-wave-ripple]] — 尖波纹波（140–200 Hz）不依赖 Cx36，揭示频率特异性同步机制分离
- [[place-cell]] — Cx36 KO 损害地点细胞空间选择性和 theta 相位进动
- [[action-potential]] — 动作电位通过低通滤波的电偶联传递去极化（但尖峰被衰减）
- [[synaptic-transmission]] — 电突触与化学突触为互补并行通路

## 未解问题

- Q-gap-01：尖波纹波（140–200 Hz）不依赖 Cx36——其同步机制是什么？（纯化学循环？其他 connexin？）
- Q-gap-02：Cx36 可塑性是否支持任何形式的经验依赖学习？
- Q-gap-03：胚胎期广泛缝隙连接→成年期局限于 PV 细胞的转变机制？
- Q-gap-04：精神分裂症中 Cx36 是否功能受损，是否可作为治疗靶点？

## 修订历史

- 2026-10-06 · 创建 · 基于《缝隙连接与神经元电突触：被遗忘了半个世纪的大脑"硬线"同步装置》（#166）· 初始置信度：高
- 2026-10-07 · 修订 rev1→rev2 · 基于《下橄榄核：大脑最奇特的节律师》（#167）· 新增 IO Cx36 专属功能节（同步误差时钟 vs 皮层 gamma 的功能对比）；新增 IO 相关证据行（PMID:18498740、PMID:21151372、PMID:29311830）；新增连接：inferior-olive、climbing-fiber

## 来源文章

- [[2026-10-06-gap-junction-electrical-synapse]]
- [[2026-10-07-inferior-olive-cx36-motor-learning]]

---
title: 突触生成
slug: synaptogenesis
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-06
updated: 2026-08-06
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [axon-guidance, neuroligin-neurexin, postsynaptic-density, gephyrin-scaffold, ltp, synaptic-pruning, growth-cone]
prerequisites: [action-potential, axon-guidance, synaptic-transmission]
opens_questions: [Q-synaptogenesis-01, Q-synaptogenesis-02, Q-synaptogenesis-03]
source_articles: [2026-08-06-synaptogenesis-molecular-assembly]
key_sources: ["PMID:10892652", "PMID:30359597", "PMID:41614918", "PMID:41824561"]
---

# 突触生成 (Synaptogenesis)

> **一句话定义**：轴突接触目标树突后，通过 Neuroligin-Neurexin 跨膜"握手"双向触发突触前主动带和突触后密度体（PSD）的协同装配，产生功能性突触的发育过程。

## 当前理解

我们现在认为，突触生成不是简单的细胞"粘合"，而是一套高度编程化的双向分子装配工程。两张陌生细胞膜相遇后，突触后膜上的 Neuroligin（NLGN）与突触前膜上的 Neurexin（NRXN）形成跨间隙粘附对，产生**双向信号**：NL 向后激活突触后密度体（PSD）的组装，NRXN 向前招募主动带蛋白。兴奋性（谷氨酸能）和抑制性（GABA/甘氨酸能）突触分别使用不同的 NL 亚型（NL1 vs. NL2）和不同的后端骨架系统（PSD-95/Shank/Homer vs. Gephyrin/Collybistin），从装配起点就建立了兴奋-抑制分子区分。

近年证据（Kim et al. 2026, PMC13094498）进一步表明，轴突导向分子（Latrophilin、Neurexin、NMDAR 等）在到达靶点后并不"退休"，而是通过重新偶联不同 G 蛋白或切换信号模式，从导向角色无缝转变为突触组织角色——这个"分子连续性"模型重新定义了发育阶段的边界。

初期突触生成大体活动非依赖；随后突触的保留或修剪则高度依赖神经活动（突触竞争模型）。

## 关键机制

### 分子层：识别与启动

1. **NL-NRXN 握手**：NLGN 的类胆碱酯酶折叠域与 NRXN 的 LNS（Laminin-Neurexin-Sex hormone binding globulin）域结合；不同 NLGN 亚型（NL1–4）和不同 NRXN 异构体（α/β，多个可变外显子）组合构成突触识别"密码"
2. **平行系统**：LRRTM 家族（LRRTM1–4）也与 NRXN 结合（部分通过硫酸乙酰肝素修饰）诱导突触前分化，与 NL 系统形成冗余保障（PMID:31995730）
3. **弱结合 × 聚集**：NL2-NRXβ1 的弱亲和力（Kd ~10 μM）通过多对协同聚集实现高效膜牵引和 Gephyrin 招募（PMID:41824561）

### 细胞层：双侧组装

**突触前侧**：NRXN 接合信号促使 Bassoon/Piccolo 支架蛋白在接触点聚集，形成主动带原基（protocytomatrix）；突触小泡经 SNARE 依赖机制向主动带靶向

**突触后侧兴奋性**：NL1 → PSD-95（MAGUK）聚集 → GKAP 桥接 → Shank/Homer 自组装 → AMPA/NMDA 受体锚定。整体形成三层结构（见 [[postsynaptic-density]]）

**突触后侧抑制性**：NL2 + Collybistin 激活 Cdc42 → Gephyrin 格栅在抑制性接触点定向铺开 → GABA-A 受体通过 α/β3 胞内环被捕获（见 [[gephyrin-scaffold]]）

### 系统层：活动依赖的稳定与修剪

过度生成的突触中，活动频繁者被稳定，活动稀少者被小胶质细胞通过补体系统（C1q/C3）介导的突触修剪去除（见 [[synaptic-pruning]]）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| NL-1/2 足以诱导突触前分化 | HEK293 异位表达 NL + 神经元共培养 → 接触点 SV 聚集 | PMID:10892652（Scheiffele 2000） | 高 |
| NL1→兴奋性，NL2→抑制性突触 | 免疫荧光共定位 + 亚型特异性敲除动物 | PMID:26209464（Bemben 2015）综述 | 高 |
| NL2-NRXβ1 弱结合通过聚集效应锚定 Gephyrin | 数学建模 + 荧光成像 + 受体密度定量 | PMID:41824561（Boyd 2026, PMC12985673） | 高 |
| 导向分子（LPHN/NRXN）双重功能 | 条件敲除：层状投射+突触密度双重受损 | PMID:41895449（Kim 2026, PMC13094498） | 中 |
| LRRTM 通过硫酸乙酰肝素诱导突触 | HS 去除抑制 LRRTM3/4 的突触前效应 | PMID:31995730（Roppongi 2020） | 高 |

## 连接

- [[axon-guidance]] — 轴突导向的续集；分子连续性（导向分子双重功能）
- [[neuroligin-neurexin]] — 突触生成的核心识别系统
- [[postsynaptic-density]] — 兴奋性突触后的三层骨架
- [[gephyrin-scaffold]] — 抑制性突触后的格栅系统
- [[ltp]] — 突触生成后的强化机制（活动依赖可塑性）
- [[synaptic-pruning]] — 过剩突触的选择性去除
- [[growth-cone]] — 导向阶段的终末结构
- [[autism-spectrum-disorder]] — NLGN3/NLGN4/SHANK3 突变与突触生成缺陷

## 未解问题

- Q-synaptogenesis-01：从接触到第一个功能性 AMPA 电流的体内时间进程
- Q-synaptogenesis-02：Nrxn 异构体密码在体内是否真正实现突触亚类特异性
- Q-synaptogenesis-03：突触初始装配与稳定化（抗修剪）的分子机制是否独立

## 修订历史

- 2026-08-06 · 创建 · 基于《轴突找到伙伴之后：突触如何从分子装配线上诞生》(#105) · 初始置信度：高

## 来源文章

- [[2026-08-06-synaptogenesis-molecular-assembly]]

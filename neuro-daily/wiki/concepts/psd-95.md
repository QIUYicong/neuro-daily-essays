---
title: PSD-95（突触后密度-95）
slug: psd-95
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-06
updated: 2026-09-07
revision_count: 2
dimensions: [molecular, synaptic, cellular, microcircuit]
related: [silent-synapse, ltp, ltd, nmda-receptor, ampa-receptor, camkii, synaptogenesis, postsynaptic-density, critical-period, critical-period-plasticity, gephyrin-scaffold, tarp-auxiliary-subunit, syngap1, syngap1-related-disorder, dlg4-syndrome, working-memory]
prerequisites: [synaptic-transmission, nmda-receptor, ampa-receptor, postsynaptic-density]
opens_questions: [Q-psd95-01, Q-psd95-02]
source_articles: [2026-09-06-psd95-synaptic-scaffold, 2026-09-05-odp-stage2-hebbian-vs-homeostatic]
key_sources: ["PMID:7569905", "PMID:11082065", "PMID:12359873/PMC129795", "PMID:14749436/PMC6729816", "PMID:16061821/PMC1182136", "PMID:21525273/PMC3099547", "PMID:27623146/PMC5040590", "PMID:27565345/PMC5564291", "PMID:23926273/PMC6619720", "PMID:26015564/PMC4475980"]
---

# PSD-95（突触后密度-95）(Postsynaptic Density-95 / DLG4)

> **一句话定义**：兴奋性突触后致密体（PSD）最丰富的支架蛋白（每个突触约 300 个分子），通过 PDZ1/2 锚定 NMDA 受体、经 TARP（Stargazin）间接稳定 AMPA 受体，形成"突触槽位（synaptic slot）"的分子基础，控制突触权重的写入与擦除，并与 PSD-93 的竞争共同设定视觉关键期的时间轴。

## 当前理解

我们现在认为，PSD-95（基因：*DLG4*）不只是突触的结构骨架，而是突触权重的动态调控者。它的核心功能是通过五域结构（PDZ1/2/3 + SH3 + GK）同时执行三项任务：① 通过 PDZ1/2 锚定 NMDA 受体 GluN2B 亚基（-ESDV 基序结合），将 LTP 诱导的钙信号与 PSD 重构物理上绑定；② 通过 TARP（如 Stargazin/γ-2）间接稳定 AMPA 受体，提供"槽位"供 AMPAR 落脚，每个 PSD-95 分子创建一个（或多个）AMPAR 槽位；③ 通过 GK 域→GKAP→Shank/Homer 的三层级联，将 NMDAR/AMPAR 层与 mGluR/代谢信号层整合为统一的计算单元。

**LTP 中的角色**：CaMKII 激活后磷酸化 SynGAP（使其从 PDZ 槽位上解离，释放空间给 TARP-AMPAR），并磷酸化 GluA1-S831（驱动 AMPAR 向突触扩散）。两个效应协同，使突触 AMPAR 数量增加、突触权重增大。

**关键期中的角色**：PSD-95/PSD-93 的比值控制沉默突触开锁速率——PSD-95 KO 使 AMPAR 无法稳定插入（关键期永不关闭），PSD-93 KO 使 PSD-95 槽位提前充满（关键期提前关闭）。

**液液相变**：SynGAP 三聚体与多个 PSD-95 形成多价复合物，驱动液-液相分离，使 PSD 成为动态凝聚体（而非固态晶体）；活动通过 CaMKII 磷酸化改变相变状态。

**量化基准（Kennedy 实验室，2005）**：每个平均 PSD（直径 360 nm，质量 1.1 GDa）约含 300 个 PSD-95 分子（占 PSD 质量 2.3%）和 80 个 α-CaMKII 全酶。

## 关键机制

### 1. 分子结构（五域）

| 域 | 结合伙伴 | 功能 |
|----|---------|------|
| PDZ1/2 | NMDAR GluN2B C 末端 -ESDV；TARP（Stargazin）C 末端 | NMDAR 锚定；AMPAR 间接槽位 |
| PDZ3 | NL1/NL2 C 末端；Kv1.4 | 突触粘附整合；钾通道锚定 |
| SH3 | 富含脯氨酸的内部合作伙伴；与 PDZ3 内部偶联 | 构象门控；蛋白质复合物等级化组装 |
| GK | GKAP（SAPAP/DLGAP）家族 | 连接 Shank/Homer 深部骨架层 |
| N 末端（C3/C5） | 棕榈酰化（ZDHHC2 等） | 突触后膜锚定；活动依赖性循环 |

### 2. TARP-PSD95 轴（AMPAR 槽位的物理实现）

AMPA 受体不直接结合 PSD-95；中介是 **TARP（跨膜 AMPAR 调控蛋白）**，最重要的是 Stargazin（γ-2）：
- AMPAR 亚基与 Stargazin 组成稳定复合物
- Stargazin C 末端（PDZ 结合基序）与 PSD-95 PDZ1/2 直接结合（Schnell 2002, PMID:12359873, PNAS，PMC129795，开放）
- Stargazin 突变（不能结合 PSD-95 PDZ）：表面 AMPAR 量正常，但**无法在突触聚集**
- 这说明 TARP-PSD-95 链是 AMPAR 突触锚定的必要条件，而非调节性信号

**超分辨证据**：PSD-95 敲低后，突触内 AMPAR 的 70-100 nm 纳米域消失，AMPAR 扩散增加（Nair 2013, PMID:23926273, J Neurosci，PMC6619720，开放）。

### 3. SynGAP 竞争与 LTP

SynGAP-α1 也与 PDZ 槽位结合，静息时约占 15% 槽位（与 TARP-AMPAR 竞争）：
- LTP 时：CaMKII 磷酸化 SynGAP-α1 → 亲和力降低 ~10 倍 → 槽位释放给 TARP-AMPAR
- SynGAP 杂合 KO 小鼠：TARP（+12%）、LRRTM2（+14%）在突触处增加，与预测吻合
- 这将 SynGAP 相关 ID/ASD（2-9% 散发病例）与"槽位竞争"机制直接连接

### 4. 棕榈酰化（膜锚定与动态循环）

PSD-95 N 末端 C3/C5 的棕榈酰化（S-palmitoylation）是突触聚集的必要条件：
- 7 种 ZDHHC 酶可棕榈酰化 PSD-95（ZDHHC2/3/5/7/8/15/17）
- **ZDHHC2 负责活动依赖性动态循环**：活动 → 去棕榈酰化 → PSD-95 分散；静默 → 复棕榈酰化 → 重新聚集
- 棕榈酰化状态把神经元活动史"写入" PSD-95 的突触含量（PMID:36766729, PMC9913408，开放）

### 5. 液液相变与凝聚体动力学

SynGAP/PSD-95 多价复合物驱动液-液相分离（Zeng 2016, PMID:27565345, Cell, PMC5564291，开放）：
- PSD 不是固态晶体，而是动态凝聚体
- CaMKII 磷酸化 SynGAP → 相变解体（活动时凝聚体松散化 → AMPAR 插入空间增大）
- 这为"LTP 时 PSD 迅速重构"提供了物理机制

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| PSD-95 PDZ1/2 直接结合 NMDAR GluN2B -ESDV | 酵母双杂交；体外 pull-down | PMID:7569905，Science 1995 | 高 |
| PSD-95 过表达→突触 AMPAR 增加，驱动突触成熟 | 海马神经元过表达 + 电生理 | PMID:11082065，Science 2000 | 高 |
| Stargazin 直接结合 PSD-95 PDZ，控制突触 AMPAR 数量 | Stargazin 突变体 + 电生理 | PMID:12359873 / PMC129795，PNAS 2002 | 高 |
| PSD-95 PDZ1/2 是 LTP 中 AMPAR 插入的必要结构 | PDZ 截断突变 + 显性阴性 + 经验依赖性可塑性 | PMID:14749436 / PMC6729816，J Neurosci 2004 | 高 |
| 每个 PSD 约 300 个 PSD-95 分子 | STEM 质量测量 + 定量凝胶电泳 | PMID:16061821 / PMC1182136，PNAS 2005 | 高 |
| PSD-95 形成垂直纤维阵列；敲低→AMPAR 相关结构消失 | 电子断层扫描 + RNAi | PMID:21525273 / PMC3099547，J Neurosci 2011 | 高 |
| SynGAP 竞争 PDZ 槽位；CaMKII 磷酸化释放槽位给 AMPAR | 结合动力学 + SynGAP 杂合 KO 蛋白质组 | PMID:27623146 / PMC5040590，eLife 2016 | 高 |
| PSD 液液相分离由 SynGAP/PSD-95 驱动；CaMKII 调控 | 体外相分离 + 荧光 + 冷冻电镜 | PMID:27565345 / PMC5564291，Cell 2016 | 中（体外系统，体内状态有争议） |
| AMPAR 纳米域（70-100 nm）由 PSD-95 维持 | 单分子追踪（uPAINT+sptPALM） | PMID:23926273 / PMC6619720，J Neurosci 2013 | 高 |
| PSD-95 KO→关键期无限延长（沉默突触无法开锁） | PSD-95 KO 小鼠 + 单眼遮蔽 + 电生理 | PMID:26015564 / PMC4475980，PNAS 2015 | 高 |
| PSD-93 KO→关键期提前关闭 | PSD-93 KO 小鼠 + ODP 测量 | PMID:30586380 / PMC6324823，PLoS Biol 2018 | 高 |

## 连接

- [[silent-synapse]] — PSD-95 是沉默突触"开锁"（AMPAR 稳定插入）的关键执行蛋白；PSD-95 KO 使沉默突触无法被激活
- [[ltp]] — PSD-95 的"槽位"是 LTP 中 AMPAR 插入的物理基础；CaMKII 通过 SynGAP 解离释放槽位
- [[ltd]] — Ser-295 去磷酸化或 Ser-561 磷酸化导致 PSD-95 分散，AMPAR 槽位减少，促进 LTD
- [[nmda-receptor]] — PSD-95 PDZ1/2 直接锚定 GluN2B C 末端；双方是 PSD 的核心双锚点系统
- [[ampa-receptor]] — PSD-95 经 TARP（Stargazin）间接稳定突触 AMPAR；PSD-95 数量决定 AMPAR 容量
- [[camkii]] — CaMKII 磷酸化 SynGAP（释放 PDZ 槽位）并磷酸化 GluA1-S831（驱动 AMPAR 插入），与 PSD-95 槽位系统协同完成 LTP
- [[postsynaptic-density]] — PSD-95 是 PSD 三层结构的第一层（膜近端）的主骨架
- [[synaptogenesis]] — 突触形成初期，NL1 通过 PDZ3 招募 PSD-95，触发 PSD 组装级联
- [[critical-period-plasticity]] — PSD-95/PSD-93 竞争比值设定关键期时间轴
- [[gephyrin-scaffold]] — 抑制性突触的平行支架系统，与 PSD-95 在兴奋性突触中的角色对比

## 未解问题

- **Q-psd95-01**：LTP 时 PSD-95 分子绝对数量是否真的增加？还是只是槽位占用率（SynGAP 解离 + AMPAR 捕获）变化？体内定量 LTP 前后 PSD-95 分子数的实验尚缺乏。
- **Q-psd95-02**：PSD-95 的棕榈酰化-去棕榈酰化周期（ZDHHC2 介导）是否在睡眠期间参与突触强度的全局下调（SHY 假说）？ZDHHC2 的活动依赖性抑制（睡眠时神经元活动减少）是否对应 PSD-95 重新聚集和突触稳定？

## 修订历史

- 2026-09-07 · 修订 rev2 · 基于《突触的"制动蛋白"》(#137) · SynGAP1-PDZ2 相互作用的分子细节明确（CaMKII磷酸化→亲和力降低→SynGAP1弥散）；related 新增 syngap1、syngap1-related-disorder；syngap→syngap1 slug 更新；source_articles 新增
- 2026-09-06 · 创建 · 基于《PSD-95：兴奋性突触的主控分子》(#136) · 初始置信度：高 · 填补 2026-09-05 沉默突触文章创建的悬空引用

## 来源文章

- [[2026-09-07-syngap1-synaptic-brake-intellectual-disability]]
- [[2026-09-06-psd95-synaptic-scaffold]]
- [[2026-09-05-odp-stage2-hebbian-vs-homeostatic]]

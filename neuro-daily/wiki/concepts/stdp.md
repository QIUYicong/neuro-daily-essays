---
title: 脉冲时序依赖可塑性（STDP）
slug: stdp
domain: concepts
type: mechanism
status: mainstream
confidence: medium
created: 2026-08-25
updated: 2026-08-25
revision_count: 1
dimensions: [molecular, synaptic, cellular, microcircuit]
related: [ltp, ltd, hebbian-learning, nmda-receptor, ampa-receptor, camkii, backpropagating-action-potential, three-factor-learning-rule, theta-oscillations, btsp, barrel-cortex, place-cell]
prerequisites: [nmda-receptor, synaptic-transmission, action-potential, ltp]
opens_questions: [Q-stdp-01, Q-stdp-02, Q-stdp-03]
source_articles: [2026-08-25-stdp-spike-timing-dependent-plasticity]
key_sources: ["PMID:8985014", "PMID:9852584", "PMID:15450157", "PMID:22920249", "PMID:34616278", "PMID:35203089", "PMID:20798031", "PMID:30018546", "PMCID:PMC10188658"]
---

# 脉冲时序依赖可塑性 (STDP, Spike-Timing Dependent Plasticity)

> **一句话定义**：突触前神经元在突触后神经元放电前约 5–40 毫秒内放电则该突触增强（LTP），反之则减弱（LTD）——这一时序规则是赫布学习规则的毫秒级精化，通过 NMDA 受体符合探测和回传动作电位（bAP）在树突棘内的超线性钙信号实现，但其在生理条件下的确切表达仍有重要争议。

## 当前理解

我们现在认为，STDP 是赫布原理（"一起激发的神经元连在一起"）的时序分辨率升级版：它不只要求两个神经元共激活，还要求**突触前先于突触后**激发。这一方向性使突触能够在某种程度上编码时间因果关系——"A 导致 B"而非仅仅"A 与 B 相关"。

经典 STDP 学习窗口（由 Markram et al. 1997 Science 和 Bi & Poo 1998 J Neurosci 奠定）的要点是：
- **前先后随**（pre before post，Δt ≈ +5 到 +40 ms）→ 突触增强（t-LTP）
- **后先前随**（post before pre，Δt ≈ −5 到 −70 ms）→ 突触减弱（t-LTD）
- 窗口不对称：LTP 窗口窄于 LTD 窗口
- 时间窗外（|Δt| > 100 ms）→ 无可塑性

但以下两点需要重要标注：

**1. 生理钙浓度的挑战（Inglebert & Debanne 2021）**：几乎所有经典 STDP 实验使用细胞外 Ca²⁺ 2–3 mM，而生理浓度约 1.3–1.8 mM。在生理 Ca²⁺ 下，标准低频配对方案（0.3 Hz, 1:1）无法可靠诱导 LTP，只有 LTD 或无可塑性。这意味着教科书 STDP 曲线可能不直接适用于体内条件。

**2. 短期因果性 vs 长期同步性（Anisimova et al. 2022）**：使用光遗传 3 天追踪发现，短期（20 min）依赖因果顺序；但 3 天后，无论前先后随还是后先前随，只要 |Δt| < 50 ms（同步），均产生长期 LTP。长期记忆可能更依赖同步性，经典因果 STDP 曲线反映的是短期动态（status: contested, 见 C-2026-08-25-01）。

## 关键机制

### 分子层：NMDA 受体符合探测器

NMDA 受体要求同时满足：
1. 谷氨酸结合（突触前信号）
2. 膜电位去极化（突触后信号，解除 Mg²⁺ 阻断）

这是一个 AND 逻辑门，执行 Hebb 规则的分子形式。

### 细胞层：回传动作电位（bAP）的时序信号

突触后动作电位不只前向传播，还沿树突**逆向回传**（back-propagating AP, bAP），将突触后激活的时序信息传递到所有激活的树突突触处。

- **前先后随时序**：突触前谷氨酸先到（轻微去极化）→ bAP 随后到来（强去极化）→ NMDA 两个门同时开放 → 大量 Ca²⁺ 内流 → CaMKII 激活 → LTP
- **后先前随时序**：bAP 先到（Mg²⁺ 暂时解阻）→ 谷氨酸后到（bAP 已消散，Mg²⁺ 复位）→ 少量 Ca²⁺ 内流 → 磷酸酶（PP2B/calcineurin）激活 → AMPA 受体内吞 → LTD

### 突触层：AMPA 受体门控时间精度（Holbro et al. 2010）

AMPA 受体不只是被动响应谷氨酸，它还调控 STDP 时间精度：
- AMPA 激活产生的轻微去极化使 NMDA Mg²⁺ 阻断不稳定
- bAP 到来时产生超线性 Ca²⁺ 叠加（实际 Ca²⁺ > EPSP 单独 + bAP 单独之和）
- 阻断 AMPA → 消除 STDP 时间精度

### 第三因素调制（Foncelle et al. 2018）

STDP 是基础 Hebbian 项，神经调质作为"第三因素"调制：
- 多巴胺（D1/D5）：将 LTD 转为 LTP，扩大 LTP 窗口
- 乙酰胆碱：增强 LTD
- 去甲肾上腺素：趋向对称 LTP

这使 STDP 能被奖励（DA）和注意力（ACh）信号选择性调控，与三因素学习规则整合。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 新皮质突触可塑性依赖精确时序 | 双全细胞膜片钳，大鼠S1，双向配对 | PMID:8985014（Markram 1997） | 高 |
| 培养海马神经元经典 STDP 窗口（+5~+40ms LTP；-5~-70ms LTD） | 系统时序扫描 + 药理控制（AP5 阻断）| PMID:9852584（Bi & Poo 1998） | 高（体外） |
| NMDA 受体是 STDP 诱导的必要条件 | AP5 阻断消除 LTP 和 LTD | PMID:9852584 | 高 |
| AMPA 受体调控 STDP 时间精度，超线性 Ca²⁺ 叠加 | 双光子棘钙成像，AMPA 阻断实验 | PMID:20798031（Holbro 2010） | 高 |
| 生理 Ca²⁺（1.3-1.8 mM）下标准配对无法诱导 LTP | CA3-CA1 系统比较不同 Ca²⁺ 浓度 | PMID:34616278（Inglebert 2021）| 中（需独立重复） |
| 长期（3天）记忆依赖同步性而非因果顺序 | 光遗传CA3-CA1，20min vs 3day测量 | PMID:35203089（Anisimova 2022）| 中（单一来源，重要但待重复）|
| 人类运动皮质存在 STDP-like 规则（毫秒精度） | 双线圈 TMS ccPAS，跨胼胝体延迟 | PMCID:PMC10188658（Hernandez-Pavon 2022）| 中-高（人类非侵入性证据）|

## 连接

- [[ltp]] — STDP 的前先后随情形产生 LTP；STDP 是时序敏感形式的 Hebb LTP
- [[ltd]] — STDP 的后先前随情形产生 LTD；STDP 与 LTD 共享 calcineurin/AMPA 内吞通路
- [[hebbian-learning]] — STDP 是赫布规则的时序精化版本，将 "fire together" 升级为 "fire in sequence"
- [[nmda-receptor]] — NMDA 受体是 STDP 的分子符合探测器，双重门控（谷氨酸 + 去极化）执行时序 AND 逻辑
- [[ampa-receptor]] — AMPA 受体调控 STDP 的时间精度，产生超线性 Ca²⁺ 叠加
- [[camkii]] — Ca²⁺ 内流的主要下游效应器，诱导并维持 LTP（STDP 正向分支）
- [[three-factor-learning-rule]] — STDP 是三因素规则的 Hebbian 项（pre × post）；神经调质是第三因素
- [[theta-oscillations]] — θ 振荡组织海马神经元的放电时序，使行为时序落入 STDP LTP 窗口（theta phase precession）
- [[btsp]] — BTSP 是 Hebb 规则的秒级实例（~1–3s），与 STDP（毫秒级）互补；BTSP 由树突 Ca²⁺ 平台电位触发，不依赖 bAP 时序精度
- [[barrel-cortex]] — 桶状皮质地图重塑（配对胡须刺激实验）是体内 STDP 功能最强的直接证据之一
- [[place-cell]] — 场所细胞的 θ 序列时序通过 STDP 强化轨迹方向突触连接

## 未解问题

- Q-stdp-01（高优先级）：体内生理 Ca²⁺ 浓度下，STDP 规则的真正形态是什么？是否需要 θ-burst 才能可靠诱导 LTP？ → 关联 Inglebert & Debanne 2021 的挑战，需要在体内单突触分辨率实验验证
- Q-stdp-02（高优先级）：因果 STDP（经典 Bi & Poo 曲线）vs 同步性 STDP（Anisimova 2022）——哪个描述了长期记忆？两者如何整合？ → 登记为矛盾 C-2026-08-25-01
- Q-stdp-03（中优先级）：不同脑区和突触类型的 STDP 规则差异（皮质 vs 海马 vs 小脑）由什么分子特征（GluN2A/B 比例、树突 bAP 传播速率、棘几何）决定？

## 修订历史

- 2026-08-25 · 创建 · 基于《突触的时间守门人》(#123) · 初始置信度：中（核心机制 established，但体内规则形态 contested）

## 来源文章

- [[2026-08-25-stdp-spike-timing-dependent-plasticity]]

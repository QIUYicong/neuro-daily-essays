---
title: DISC1（精神分裂症中断基因 1）
slug: disc1
domain: concepts
type: entity
status: emerging
confidence: medium
created: 2026-09-16
updated: 2026-09-16
revision_count: 1
dimensions: [molecular, cellular, brain-region, disease]
related: [pv-interneurons, schizophrenia, cortical-interneuron-development, medial-ganglionic-eminence, nrg1-erbb4, nmda-receptor, gaba]
prerequisites: [pv-interneurons, cortical-interneuron-development, medial-ganglionic-eminence]
opens_questions: [Q-scz-gen-01, Q-disc1-gwas-status]
source_articles: [2026-09-16-schizophrenia-genetics-circuits]
key_sources: ["PMID:32029441", "PMID:23912123", "PMID:29156684", "PMID:37004850"]
---

# DISC1（Disrupted in Schizophrenia 1）

> **一句话定义**：DISC1 是一种多功能支架蛋白，通过调控微管稳定性（NUDEL/LIS1）、GSK3β-Wnt 信号和 MGE 祖细胞命运决定来影响 PV+ 中间神经元的发育和形态，其功能丧失导致 PV 细胞 GABA 输出减少和前额叶回路的前馈抑制损伤。

## 当前理解

我们现在认为，DISC1 的主要神经科学价值在于其作为 PV 细胞发育脆弱性的分子探针——它揭示了当细胞骨架信号和 MGE 发育程序被干扰时，PV 细胞如何选择性地出现 GAD67 下调和 GABA 输出减少，而其他类型中间神经元（SST、VIP）相对不受影响（Delevich et al. 2020，PMID:32029441）。

**重要警告**：DISC1 在精神分裂症遗传学中的地位存在严重争议（见"争议"节）。大规模 GWAS（Trubetskoy 2022，PMID:35396580）的 287 个 SCZ 风险位点中**不包含 DISC1**，其与 SCZ 的关联主要来自苏格兰大家系的罕见染色体易位（t(1;11)(q42.1;q14.3)）。DISC1 的细胞生物学机制研究有重要价值，但不应将其普遍化为 SCZ 人群的主要遗传驱动因素。

## 关键机制

### 分子层

DISC1 蛋白的功能域及其结合伙伴：
- **微管相关**：与 NUDEL（NDEL1）和 LIS1 相互作用，调控微管稳定性和神经元迁移（神经元迁移中微管的组织，LIS1 见 lissencephaly 页）
- **线粒体分裂**：通过与 Mitofilin 相互作用调控线粒体形态
- **信号转导**：调制 GSK3β 活性，进而影响 Wnt 信号
- **Dlx2 交叉**：通过 GSK3β 影响 MGE 命运转录因子 Dlx2 的活性（见 medial-ganglionic-eminence 页）
- **DBZ 结合**：DISC1-binding zinc finger protein（DBZ/Zmynd8），负责篮状细胞形态维护

### 细胞层

DISC1 功能受损对 PV 细胞的影响：

1. **MGE 发育阶段**（产前）：DISC1 干扰 → GSK3β/Dlx2 信号异常 → MGE 祖细胞增殖减少 → PV 细胞前体产生量减少（Deng et al. 2017，PMID:29156684）

2. **篮状细胞形态阶段**（产后）：DBZ（DISC1 结合伙伴）KO → PV 篮状细胞轴突分支减少、突起缩短、GAD67 mRNA 下调（Koyama et al. 2013，PMID:23912123）

3. **丘脑-PFC 回路阶段（成年）**：Disc1 LI 小鼠 → mPFC 第 2/3 层锥体细胞受到的抑制显著减少 → 专门来自 PV 细胞的 GABA 释放减少（SST 细胞不受影响）→ 内侧背核→mPFC 前馈抑制损伤（Delevich et al. 2020，PMID:32029441）

### 汇聚层（与 NRG1-ErbB4 和 NMDAR 的关系）

Gawande et al. 2023（PMID:37004850）发现 PV 细胞特异性 GluN2D 敲除会导致 *Disc1* 转录表达下调，说明 DISC1 在 PV 细胞内是 NMDA 受体激活状态的下游靶基因之一——NMDAR 低激活可能导致 DISC1 表达减少，进而恶化细胞骨架稳定性和篮状细胞形态维护。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Disc1 LI 小鼠 mPFC 第 2/3 层锥体细胞受抑制减少，专门来自 PV（非 SST）细胞 GABA 释放减少 | Disc1 LI 小鼠脑片电生理 | PMID:32029441 | 中（单实验室） |
| Disc1 LI 小鼠内侧背核→mPFC 前馈抑制损伤 | 丘脑激光刺激 + mPFC 脑片记录 | PMID:32029441 | 中（单实验室） |
| DBZ（DISC1 结合蛋白）KO→PV 篮状细胞轴突分支减少，GAD67 mRNA 下调 | DBZ KO 小鼠免疫组化 + ISH | PMID:23912123 | 中（单实验室） |
| 产前 DN-DISC1 表达抑制 MGE 祖细胞增殖（GSK3β-Dlx2 机制） | 逆转录病毒载体 + 脑片分析 | PMID:29156684 | 中 |
| GluN2D KO in PV 细胞 → *Disc1* 转录下调（汇聚点） | PV-cKO 小鼠转录组 | PMID:37004850 | 中（单实验室 2023） |

## 遗传学争议

**苏格兰家系证据（高外显率，罕见变异）**：DISC1 最初被发现于一个苏格兰大家系，其染色体 t(1;11)(q42.1;q14.3) 易位断点恰好穿过 DISC1 基因，多名家族成员患有精神分裂症和其他精神障碍（Blackwood et al. 2001）。这是高质量的罕见变异遗传证据。

**普通 GWAS 中的缺失**：大规模 SCZ GWAS（Trubetskoy 2022，PMID:35396580，76,755 例）的 287 个风险位点**不包含 DISC1 区域**。这意味着 DISC1 的常见变异不是普通人群 SCZ 多基因风险的主要驱动力。其 SCZ 相关性可能主要来自高外显率的罕见变异（易位、点突变），而不是在人群中广泛分布的 SNP。

**含义**：DISC1 研究揭示的 PV 细胞发育脆弱性机制具有普遍神经生物学价值，但不应将 DISC1 解读为一个重要的 SCZ 多基因风险基因。其角色更接近于"机制探针"而非"人群风险基因"。

## 连接

- [[pv-interneurons]] — DISC1 功能减弱选择性损伤 PV 细胞（而非 SST 或 VIP 细胞）的 GABA 输出
- [[schizophrenia]] — DISC1 最初的历史遗传关联（苏格兰家系），现在被定位为机制而非 GWAS 信号
- [[cortical-interneuron-development]] — DISC1 通过 MGE 祖细胞增殖和 Dlx2 信号影响 PV 细胞发育
- [[medial-ganglionic-eminence]] — DISC1 干扰 MGE 发育（GSK3β-Dlx2-Wnt 轴）
- [[nrg1-erbb4]] — DISC1 和 NRG1-ErbB4 在 PV 细胞内部形成相互调控的分子网络

## 未解问题

- Q-disc1-gwas-status（高优先）：DISC1 是否真正缺席普通 SCZ 遗传风险结构，还是其效应被 GWAS 设计所低估（稀有变异 + 家族特异性）？能否用外显子组测序在大样本中评估 DISC1 稀有变异的 SCZ 贡献？
- Q-scz-gen-01（高优先）：DISC1、NRG1、GRIN2A 路径是否有先后顺序？哪条是原发，哪条是继发？

## 修订历史

- 2026-09-16 · 创建 · 基于《当遗传学汇聚于同一个回路》(#146) · 初始置信度：中（小鼠机制证据扎实；人类遗传学有争议——GWAS 未确认 DISC1 常见变异风险）

## 来源文章

- [[2026-09-16-schizophrenia-genetics-circuits]]

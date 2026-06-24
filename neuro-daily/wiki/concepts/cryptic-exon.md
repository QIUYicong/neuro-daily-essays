---
title: 隐蔽外显子
slug: cryptic-exon
domain: concepts
type: mechanism
status: emerging
confidence: high
created: 2026-09-11
updated: 2026-09-11
revision_count: 1
dimensions: [molecular, cellular, disease]
related: [tdp-43-pathology, als-amyotrophic-lateral-sclerosis, rna-splicing, synaptic-vesicle-exocytosis]
prerequisites: [rna-splicing, pre-mrna-processing]
opens_questions: []
source_articles: [2026-09-11-als-tdp43-motor-neuron-selective-vulnerability]
key_sources: ["PMID:35197626", "PMC8891019", "PMID:35197628", "PMC8891020", "PMID:35767949", "PMC9327139"]
---

# 隐蔽外显子 (Cryptic Exon)

> **一句话定义**：正常情况下被 TDP-43 等 RNA 结合蛋白抑制、不被剪接体识别的内含子内序列；当抑制因子核功能丧失（如 TDP-43 核清除）时暴露，被纳入 mRNA 并通常导致移码、提前终止密码子或非稳定性 mRNA，是 TDP-43 蛋白病（ALS/FTLD）的功能性生物标志物。

## 当前理解

我们现在认为，隐蔽外显子代表了 RNA 剪接的一种"备用模式"——通常被序列特异性 RNA 结合蛋白主动抑制。TDP-43 通过结合内含子中的 UG 富集序列来阻止剪接体识别相邻的隐蔽剪接位点。

**关键发现（2022 年）**：TDP-43 功能丧失在 ALS/FTD 中的最重要后果之一，是 **UNC13A**（突触囊泡对接与释放的核心调控蛋白）基因内隐蔽外显子的暴露（PMID:35197626 / PMC8891019；PMID:35197628 / PMC8891020）。更重要的是，与 ALS 和 FTD 最强关联的两个常见 SNP（人群频率 ~25%）恰好覆盖 UNC13A 内的 TDP-43 结合位点——携带这两个 SNP 的个体在 TDP-43 功能下降时更容易暴露隐蔽外显子，疾病更快进展。这是遗传风险因素通过功能性 RNA 剪接变化发挥作用的直接机制证明。

另一个关键靶标是 **STMN2**（司坦敏蛋白-2），TDP-43 LOF 导致 STMN2 第 1 内含子中的隐蔽多腺苷酸化位点暴露，STMN2 mRNA 在提前终止，产生无功能截短蛋白。STMN2 减少损害轴突微管动力学和 NMJ 维持（PMID:35767949 / PMC9327139）。

## 关键机制

1. **TDP-43 正常作用**：结合靶基因内含子中的 UG 富集序列，招募辅助因子，物理阻断剪接体对隐蔽 5'/3' 剪接位点的识别
2. **暴露条件**：TDP-43 核清除（ALS/FTLD），或 TDP-43 突变降低 RNA 结合能力，或 TDP-43 结合位点附近的 SNP 弱化结合
3. **后果**：含隐蔽外显子的 mRNA 通常导致框内移码 → 提前终止密码子 → mRNA 降解（NMD）或截短蛋白

## 关键证据

| 主张 | 方法 | 来源 | 置信度 |
|------|------|------|--------|
| TDP-43 核清除→UNC13A 隐蔽外显子暴露 | RNA-seq, iPSC, 患者脑组织 | PMID:35197626/35197628 | 高 |
| ALS 风险 SNP 覆盖 TDP-43 结合位点，增强隐蔽外显子暴露 | 遗传 + 功能验证 | PMID:35197628 | 高 |
| STMN2 隐蔽 PolyA → mRNA 截短 → 轴突功能丧失 | iPSC-MN + KO 小鼠 | PMID:35767949 | 高 |

## 连接

- [[tdp-43-pathology]] — 隐蔽外显子暴露是 TDP-43 核 LOF 的直接读出
- [[als-amyotrophic-lateral-sclerosis]] — UNC13A/STMN2 隐蔽外显子在 ALS 病理中的关键作用
- [[synaptic-vesicle-exocytosis]] — UNC13A（Munc13-1）是突触囊泡释放的核心调控蛋白

## 修订历史

- 2026-09-11 · 创建 · 基于《ALS TDP-43 文章》(#141) · 初始置信度：高（隐蔽外显子包含 ALS 生物标志物证据很强）

## 来源文章

- [[2026-09-11-als-tdp43-motor-neuron-selective-vulnerability]]

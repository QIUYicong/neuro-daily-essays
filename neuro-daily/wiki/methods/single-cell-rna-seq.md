---
title: 单细胞RNA测序（scRNA-seq）
slug: single-cell-rna-seq
domain: methods
type: method
status: established
confidence: high
created: 2026-07-25
updated: 2026-09-12
revision_count: 2
dimensions: [molecular, cellular, methods]
related: [transcriptomic-cell-types, optogenetics, spatial-transcriptomics, patch-seq]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: [Q-scrna-state-vs-type, Q-scrna-resolution-functional]
source_articles: [2026-07-25-scrna-seq-neural-cell-type-diversity]
key_sources: ["PMID:30382198", "PMID:30586455", "PMID:38092916", "PMID:38123823"]
---

# 单细胞RNA测序 (Single-Cell RNA Sequencing, scRNA-seq)

> **一句话定义**：通过液滴微流控+条形码技术，对单个细胞的全基因组mRNA表达量进行定量测序，从而识别细胞类型、推断细胞状态的高通量分子分析方法。

## 当前理解

我们现在认为，scRNA-seq（及其脑组织优化版本snRNA-seq，单核RNA测序）是神经科学中鉴定细胞类型最系统化的技术。它将每个细胞的基因表达谱视为一个高维向量，通过降维和聚类在"基因表达空间"中识别细胞群体。应用于大脑时，scRNA-seq已将已知细胞类型数从几十种扩展到数千种（小鼠全脑5322个聚类，人脑461个major cluster；Yao et al. 2023，Siletti et al. 2023），彻底重塑了我们对神经元多样性的认知。

**snRNA-seq**是大脑研究中的关键变体：大脑难以解离为活细胞悬液，且解离过程本身会诱导即早基因（FOS, ARC等）异常表达（"解离伪影"）。单核测序直接提取完整细胞核，对核内mRNA（包含部分内含子，Bakken et al. 2018）进行测序，虽然检测基因数量略低，但能有效区分相关亚型，并避免解离诱导的转录变化。

## 关键机制

**技术流程（以10x Genomics Chromium为例）**：

1. **组织制备**：急性脑切片 → 酶解/机械解离 → 得到单细胞或单核悬液
2. **液滴封装（GEM生成）**：微流控芯片将每个细胞/核与含有唯一条形码（Cell Barcode, CB）和聚T引物的凝胶微珠（GEM）封装在油滴中，每个油滴约5–20 µm
3. **逆转录**：在油滴内，poly-A mRNA被捕获到引物上，逆转录为cDNA；每个cDNA分子获得细胞条形码（识别来源细胞）和UMI（Unique Molecular Identifier，消除PCR扩增偏差）
4. **扩增与建库**：裂解油滴 → PCR扩增 → 片段化/接头 → Illumina测序
5. **数据分析**：
   - **对齐（Alignment）**：将reads比对到基因组/转录组
   - **计数（Count matrix）**：生成细胞×基因UMI计数矩阵
   - **降维（PCA→UMAP/tSNE）**：将高维数据投影到可视化空间
   - **聚类（Leiden/Louvain）**：在kNN图上进行图聚类，识别细胞群
   - **差异基因分析**：每个聚类的标记基因（marker genes）

**通量与深度**：
- 10x Genomics：每个实验捕获~5,000–10,000细胞；每细胞~1,000–3,000个检测基因（较浅）
- SMARTseq2：~200–500细胞/实验；每细胞~6,000–8,000基因（深覆盖，适合亚型精细分析）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 小鼠VISp+ALM有133种转录组细胞类型 | SMARTseq2，~14K细胞 | Tasic et al. 2018，PMID:30382198 | 高 |
| 全小鼠神经系统265种细胞类型 | 液滴法，~500K细胞 | Zeisel et al. 2018，PMID:30096314 | 高 |
| 全小鼠脑5322个聚类（+MERFISH空间验证） | 700万细胞+MERFISH | Yao et al. 2023，PMID:38092916 | 高 |
| snRNA-seq足以区分皮层相关亚型 | snRNA vs scRNA对比实验 | Bakken et al. 2018，PMID:30586455 | 高 |

## 连接

- [[transcriptomic-cell-types]] — scRNA-seq的主要认知产出：转录组细胞类型分类体系
- [[optogenetics]] — 细胞类型知识驱动Cre驱动线选择，是光遗传学实验设计的前提
- [[pv-interneurons]] — 转录组分析揭示了PV细胞内部的多种亚类
- [[sst-interneurons]] — SST细胞的多样性由scRNA-seq进一步细化
- [[pyramidal-neuron]] — 锥体神经元的区域特异性亚类由scRNA-seq系统刻画

## 未解问题

- Q-scrna-state-vs-type：scRNA-seq如何区分细胞的"类型"（稳定分子身份）与"状态"（对活动/刺激的短暂响应）？
- Q-scrna-resolution-functional：哪个聚类分辨率对应功能上真实的细胞类型？5322个聚类与功能回路的对应关系如何？

## 修订历史

- 2026-07-25 · 创建 · 基于《神经元类型的分子宇宙》文章 #93 · 初始置信度：高
- 2026-09-12 · 修订 · 基于《大脑细胞类型的坐标系》文章 #142 · 增加：空间转录组学作为scRNA-seq的空间扩展；Allen Brain Cell Atlas 2023将5,322个聚类和空间位置对应的重要意义；scRNA-seq的根本局限（空间信息丢失）在MERFISH中如何被克服

## 来源文章

- [[2026-07-25-scrna-seq-neural-cell-type-diversity]]
- [[2026-09-12-spatial-transcriptomics-brain-cell-atlas]]

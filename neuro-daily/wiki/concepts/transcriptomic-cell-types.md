---
title: 转录组细胞类型
slug: transcriptomic-cell-types
domain: concepts
type: concept
status: established
confidence: high
created: 2026-07-25
updated: 2026-07-25
revision_count: 1
dimensions: [molecular, cellular, microcircuit, methods]
related: [single-cell-rna-seq, pv-interneurons, sst-interneurons, vip-interneurons, pyramidal-neuron, cortical-canonical-microcircuit, critical-period]
prerequisites: [single-cell-rna-seq, action-potential, synaptic-transmission]
opens_questions: [Q-scrna-state-vs-type, Q-scrna-resolution-functional, Q-cell-type-human-cognitive]
source_articles: [2026-07-25-scrna-seq-neural-cell-type-diversity]
key_sources: ["PMID:30382198", "PMID:30096314", "PMID:31435019", "PMID:34616075", "PMID:37824663", "PMID:38092916", "PMID:37824669"]
---

# 转录组细胞类型 (Transcriptomic Cell Types)

> **一句话定义**：在高维基因表达空间中形成可重复、稳定聚类的细胞群体，代表共享分子身份（标记基因组合+调控程序）和功能特性的神经元集合——是当前最系统化的大脑细胞分类体系。

## 当前理解

我们现在认为，转录组细胞类型（或"转录组聚类"）是迄今最系统的神经元分类体系。在此框架下，细胞类型被定义为在基因表达空间中能与邻近群体稳定分离的细胞集合，而非仅凭单一标记基因或单一形态特征的分组。

**核心数字**（截至2023年）：
- 小鼠视觉+运动皮层：133种（Tasic et al. 2018，PMID:30382198）
- 小鼠全神经系统：265种（Zeisel et al. 2018，PMID:30096314）
- 小鼠全脑（最高分辨率）：5,322种聚类（Yao et al. 2023，PMID:38092916）
- 人类颞中回：~100+种（Hodge et al. 2019，PMID:31435019）
- 全人脑：461个聚类/3313个亚聚类（Siletti et al. 2023，PMID:37824663，仅摘要）

**两个关键模式**：
1. **GABAergic（抑制性）细胞类型跨皮层区高度保守**（小鼠视觉/运动皮层约70%共享），而**谷氨酸能（兴奋性）细胞类型有强烈的区域特异性**——提示皮层功能特化主要来自兴奋性神经元的差异化，而抑制性回路模块在各区通用（Tasic 2018）
2. **转录因子组合编码（Combinatorial TF Code）**：每种细胞类型由一组独特的转录因子组合定义，这套"分子地址"决定细胞的命运、连接偏好和功能特性（Yao 2023）

**多模态验证**：BICCN 2021（PMID:34616075）通过转录组+染色质可及性+DNA甲基化+空间转录组+Patch-seq多重技术独立验证，证明转录组聚类对应真实的细胞实体（有独立的表观基因组特征、调控程序和解剖位置）——转录组类型不是分析产物，而是"自然界的真实切割"。

## 关键机制

**层级分类体系**（类比生物分类）：
```
神经元 vs 非神经元（最高层）
  ├── 兴奋性（谷氨酸能）
  │     ├── 皮层层次特异亚型（L2/3, L4, L5 IT/ET/NP, L6...）
  │     │     └── 区域特异亚型（VISp vs ALM vs 前额叶...）
  └── 抑制性（GABAergic）
        ├── PV（快速放电，体/轴突靶向）→ 多种PV亚类
        ├── SST（树突靶向，Martinotti细胞...）→ 多种SST亚类
        ├── VIP（双极/disinhibitory）→ 多种VIP亚类
        └── 其他（LAMP5, PVALB-, HCN1+等）
```

**从基因表达到功能的连接**（Patch-seq验证，Lee et al. 2023，PMID:37824669）：
- 转录组亚类预测**形态电生理特征**（轴突靶点偏好、放电模式、树突形态）
- 但同一转录组亚类内仍有**电生理变异**——基因表达决定"大类行为"而非精确放电参数
- PVALB-SST之间存在连续谱上的中间类型

**物种保守性与差异**（Hodge 2019, Siletti 2023）：
- 哺乳动物皮层有**同源细胞类型**（共同进化起源），支持跨物种比较研究的合理性
- 人类有小鼠没有的**物种特有亚型**（尤其是深层兴奋性神经元），可能与高级认知相关
- 同源类型的基因表达模式仍有系统性差异，提示**直接从小鼠外推人类需要谨慎**

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 皮层GABAergic类型跨区保守，兴奋性类型区域特异 | scRNA-seq，视觉/运动皮层对比 | Tasic 2018，PMID:30382198 | 高 |
| 转录组类型对应独立的表观基因组和调控程序 | 多模态整合（转录组+ATAC+甲基化） | BICCN 2021，PMID:34616075 | 高 |
| 全鼠脑5322个聚类，转录因子组合编码细胞身份 | scRNA-seq 700万细胞+MERFISH | Yao 2023，PMID:38092916 | 高 |
| 转录组亚类预测人类GABAergic形态电生理 | Patch-seq，人类外科样本 | Lee 2023，PMID:37824669 | 中-高 |
| 人类和小鼠有同源但差异显著的细胞类型 | snRNA-seq跨物种比较 | Hodge 2019，PMID:31435019 | 高 |

## 连接

- [[single-cell-rna-seq]] — 生成转录组细胞类型图谱的核心技术
- [[pv-interneurons]] — 转录组分析揭示PV细胞内多个功能亚类
- [[sst-interneurons]] — SST细胞的多样性（Martinotti vs non-Martinotti等）由转录组进一步细化
- [[cortical-canonical-microcircuit]] — 转录组细胞类型是理解正则微回路的分子基础
- [[critical-period]] — 关键期调控可能依赖于特定细胞类型的成熟时间线
- [[pyramidal-neuron]] — 锥体神经元的区域特异性亚类（特别是L5 ET vs IT差异）由转录组定义

## 未解问题

- Q-scrna-state-vs-type：细胞"类型"（稳定身份）与"状态"（对活动的短暂响应）的边界如何在测序数据中区分？
- Q-scrna-resolution-functional：哪个层次的转录组分类对应功能上真实的"回路单元"？5322个聚类vs133个聚类，哪个是电路设计的基础？
- Q-cell-type-human-cognitive：人类特有的细胞类型（Hodge 2019报告的深层兴奋性亚型）具体负责什么功能？这与人类高级认知有什么关系？

## 修订历史

- 2026-07-25 · 创建 · 基于《神经元类型的分子宇宙》文章 #93 · 初始置信度：高

## 来源文章

- [[2026-07-25-scrna-seq-neural-cell-type-diversity]]

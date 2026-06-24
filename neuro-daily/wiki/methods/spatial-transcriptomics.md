---
title: 空间转录组学
slug: spatial-transcriptomics
domain: methods
type: method
status: emerging
confidence: high
created: 2026-09-14
updated: 2026-09-14
revision_count: 1
dimensions: [molecular, cellular, methods]
related: [single-cell-rna-seq, connectomics, transcriptomic-cell-types, inhibitory-compartmental-targeting, like-to-like-connectivity, cortical-layers]
prerequisites: [single-cell-rna-seq]
opens_questions: [Q-st-01, Q-st-02, Q-st-03, Q-st-04]
source_articles: [2026-09-14-spatial-transcriptomics-brain-cell-atlas]
key_sources:
  - "PMID:38092916"
  - "PMCID:PMC10719114"
  - "PMID:34616063"
  - "PMCID:PMC8494645"
  - "PMID:39095595"
  - "PMCID:PMC11405287"
---

# 空间转录组学 (Spatial Transcriptomics)

> **一句话定义**：在保留细胞原位空间坐标的同时测量每个细胞的基因表达谱，将分子身份（细胞类型）与解剖位置整合为同一张地图的技术族群。

## 当前理解

我们现在认为，空间转录组学是"第三代"神经元分类方法（第一代：形态学；第二代：电生理+免疫化学；第三代：单细胞转录组）的关键补全。scRNA-seq（单细胞 RNA 测序）将细胞类型数量从数十扩展到数千，但代价是丢失了空间信息；空间转录组学通过在完整组织切片上直接测量 RNA 分子，把这一信息找回来。

2023 年的里程碑：BICCN 用 MERFISH（430 万细胞，1122 基因）完成了小鼠全脑的第一张高分辨率空间细胞类型地图，将全脑 5322 个转录组聚类精确定位到三维解剖坐标中（Yao et al. 2023，PMID:38092916）。这标志着神经科学从"细胞类型普查"升级到"细胞类型空间地图集"。

核心原则：分子身份是空间位置的可靠预测器——不同转录组聚类在空间上高度特异，反映了发育历史、功能约束和解剖区域化的共同塑造。

## 关键机制

### 两大方法家族

**家族一：成像型（Imaging-based ISH/ISS）**

在完整组织切片上直接对 RNA 分子成像，保持单分子分辨率。

| 方法 | 原理 | 基因数 | 分辨率 | 代表实验 |
|------|------|--------|--------|---------|
| MERFISH | 二进制条形码+汉明误差校正+顺序荧光成像 | 100–1100+ | 亚细胞 | Yao 2023 全脑（1122基因，430M细胞）|
| seqFISH+ | 迭代杂交+成像循环 | 10,000+ | 亚细胞 | Zhuang/Shah 2019（皮层切片）|
| STARmap PLUS | 原位测序（滚环扩增+ISS）| 1000+ | 亚细胞，3D兼容 | Wang 2023（1022基因，1.09M细胞，全CNS）|

MERFISH 的误差校正原理：每种 RNA 被分配一个 16 位二进制码，汉明距离≥4（可校正 2 个成像错误）。这将假阳性/假阴性率压低到统计上可接受的范围，对于大规模、多轮成像实验至关重要。

**家族二：测序型（Sequencing-based）**

在空间解析的底物上捕获 RNA 后进行 NGS 测序，可接近全转录组覆盖，但分辨率较低。

| 方法 | 原理 | 分辨率 | 基因覆盖 | 典型规模 |
|------|------|--------|---------|---------|
| Slide-seqV2 | DNA条形码微珠底物 | 10 μm | 全转录组 | ~170万细胞，101切片（Broad BICCN）|
| Visium（10x） | poly-dT探针捕获底物，55μm spot | 55 μm（多细胞）| 全转录组 | 最广泛商业化 |
| Stereo-seq | 亚微米 DNA 纳米球阵列 | 0.22 μm | 全转录组 | 高分辨率全转录组前沿 |

### BICCN 全脑图谱的整合策略

Yao et al. 2023 的关键技术贡献是建立了 scRNA-seq 和 MERFISH 的**层级映射（hierarchical mapping）**框架：

1. 用 scRNA-seq（700万细胞）建立全脑参考分类系统（5322聚类）
2. 用 MERFISH（1122基因探针）在 59 张连续切片上成像，捕获 430 万个空间定位细胞
3. 将 MERFISH 细胞映射到 scRNA-seq 分类体系（中位相关系数 0.91）
4. 计算推断：用 k-NN 方法将 scRNA-seq 的全基因组表达"投影"到 MERFISH 的空间坐标中

这一策略的优势：用有限基因（MERFISH）实现高通量空间成像，再通过统计映射获得全基因组的空间分辨率预测。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 小鼠全脑存在 5322 个有空间定位的转录组聚类 | scRNA-seq（7M cells）+ MERFISH（4.3M cells）双数据集整合 | Yao et al. 2023，PMID:38092916 | 高（双数据集验证）|
| 大多数皮层抑制性神经元聚类也呈层级空间组织 | MERFISH 258基因，小鼠 MOp，~30万细胞 | Zhang et al. 2021，PMID:34616063 | 高（原位成像）|
| STARmap PLUS 识别全 CNS 230种分子细胞类型+106分子区域 | 3D ISS，1022基因，109万细胞 | Wang et al. 2023，Nature 622 | 高（摘要为准，全文未读）|
| 小鼠脑背腹二元性：背侧=少量高度分化类型，腹侧=多量近缘类型 | MERFISH空间分布+系统发育树分析 | Yao et al. 2023，PMID:38092916 | 高 |
| 人类大脑3313个转录组子聚类；区域差异主要是比例变化 | 11.3M cells，70项研究，14脑区 | Cross et al. 2024，PMID:39095595 | 高（多数据集整合）|

## 连接

- [[single-cell-rna-seq]] — 空间转录组学的前驱技术，提供分子细胞类型定义（但无空间信息）
- [[transcriptomic-cell-types]] — 空间转录组学的主要认知产出：将转录组聚类与解剖位置绑定
- [[connectomics]] — 空间转录组学提供连接组研究的"细胞类型图例"：知道75,000个神经元各是什么类型
- [[cortical-layers]] — 皮层层级组织在空间转录组学中得到精确的分子分辨率确认
- [[inhibitory-compartmental-targeting]] — MICrONS的20个运动组（功能类型）与转录组分类的比较，待系统对应
- [[like-to-like-connectivity]] — "同类相连"规则可通过空间转录组学来定义"类"的边界

## 未解问题

- Q-st-01（高）：5322个聚类是否都有生物学实在性，还是算法过分切分了连续分布的细胞状态变异？
- Q-st-02（高）：MICrONS的20个抑制性运动组（功能维度）如何系统对应BICCN的转录组子类（分子维度）？
- Q-st-03（中）：人类大脑是否存在灵长类特有的细胞亚型，其与人类特有认知功能的因果关系是什么？
- Q-st-04（中）：如何在体内区分"细胞类型"（稳定的发育约束）和"细胞状态"（学习/激活诱导的可逆变化）？

## 修订历史

- 2026-09-14 · 创建 · 基于《大脑的分子护照》一文（#144）· 初始置信度：高（BICCN多数据集验证）

## 来源文章

- [[2026-09-14-spatial-transcriptomics-brain-cell-atlas]]

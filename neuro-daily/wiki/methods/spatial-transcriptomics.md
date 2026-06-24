---
title: 空间转录组学
slug: spatial-transcriptomics
domain: methods
type: method
status: established
confidence: high
created: 2026-09-16
updated: 2026-09-16
revision_count: 1
dimensions: [molecular, cellular, brain-region, methods]
related: [single-cell-rna-seq, transcriptomic-cell-types, connectomics, merfish, allen-brain-cell-atlas]
prerequisites: [single-cell-rna-seq, transcriptomic-cell-types]
opens_questions: [Q-spatial-cell-type-boundary, Q-spatial-human-brain, Q-spatial-functional-correspondence]
source_articles: [2026-09-16-spatial-transcriptomics-brain-cell-atlas]
key_sources: ["PMID:25858977", "PMID:34616063", "PMID:38092916", "PMID:38092912", "PMID:36580914"]
---

# 空间转录组学 (Spatial Transcriptomics)

> **一句话定义**：空间转录组学是在保留细胞原位空间位置的同时测量基因表达的技术总称，其中 MERFISH 通过多轮序贯荧光成像与纠错编码实现在全脑尺度同时检测 1000+ 基因，从而揭示细胞的分子身份与解剖位置的统一图谱。

## 当前理解

我们现在认为，空间转录组学（spatial transcriptomics）代表了神经科学方法论的一次范式转变：它打破了"精确分子分类（scRNA-seq）"与"精确空间定位（传统组织学）"长期以来只能二选一的困境。

在最成熟的实现形式——MERFISH（Multiplexed Error-Robust Fluorescence In Situ Hybridization）——中，技术突破来自一个看似简单的洞见：将信息论中的**纠错编码（error-correcting code）**应用于荧光成像。为每种 RNA 分配一个最小汉明距离≥4 的二进制条形码，通过 14–16 轮序贯成像读出该条形码的各位，即使某轮成像发生单位读取错误，算法依然能正确识别 RNA 种类（Chen et al. 2015，PMID:25858977）。

这套方案从 2015 年原始的 140 个 RNA（人成纤维细胞），演进到 2021 年的 258 个基因（初级运动皮层，Zhang et al.），再到 2023 年的 1100+ 基因、1000 万个细胞的全脑覆盖（Zhang et al. 2023，PMID:38092912）。

以 MERFISH 为核心技术构建的 **Allen Brain Cell Atlas 2023**（Yao et al.，PMID:38092916）整合了约 700 万个 scRNA-seq 单细胞与约 430 万个 MERFISH 空间细胞，产生小鼠全脑 4 级层级分类体系：**34 类（class）/ 338 亚类（subclass）/ 1201 超类型（supertype）/ 5322 簇（cluster）**，这是迄今对哺乳动物大脑细胞多样性最完整的描述。

## 关键机制

### 技术层：MERFISH 如何工作

1. **编码设计**：为每种目标 RNA 分配一条独特二进制序列（条形码），采用最小汉明距离≥4 的 MHD4 编码（可纠正单位错误）或 MHD2 编码（可检测但不纠正错误）。
2. **探针标记**：每个目标 RNA 被约 192 条编码探针标记，每条探针含 RNA 靶向序列和用于读出成像的序列。
3. **序贯成像**：14–16 轮荧光杂交成像，每轮读出条形码的若干位，每轮之间光漂白清除荧光，同一组织切片反复使用。
4. **解码与定位**：多轮成像叠加后，通过纠错算法解码每个单分子荧光点的 RNA 身份，同时保留其在切片中的 XY 坐标（精度约 20 nm）。
5. **细胞分割与注释**：将检测到的 RNA 点分配给单个细胞（基于 DAPI 核染色等细胞分割算法），计算每个细胞的基因表达向量，通过最近邻映射注释到 scRNA-seq 细胞类型体系。

### 分析层：空间模块与细胞类型梯度

- **空间模块**（Zhang et al. 2023）：不依据解剖坐标，而是按局部细胞类型组成的相似性聚类，定义分子层面的"功能同质区域"。一级模块 16 个，二级模块 130 个，大致（但不精确）对应传统解剖区域。
- **连续细胞类型梯度**：IT 神经元随皮层深度渐变，纹状体 D1/D2 MSN 沿背外侧-腹内侧轴渐变，下丘脑/中脑/后脑神经元多样性极高且沿多轴连续变化——挑战"细胞类型等于离散类别"的简化观念。
- **背腹侧分化原则**（Yao et al. 2023）：背侧（皮层/海马来源）——细胞类型数量少但高度分化；腹侧（基底神经节/杏仁核来源）——细胞类型多但彼此相近。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| MERFISH 可在原位检测 1000+ RNA，准确性高 | scRNA-seq 验证（Pearson r=0.94）；多独立实验室重现 | PMID:25858977（PMC4662681）| 高 |
| 初级运动皮层中大多数 GABAergic 亚簇有层级特异性分布 | 258 基因 MERFISH + 逆行示踪；约 30 万细胞 | PMID:34616063（PMC8494645）| 高 |
| IT 神经元形成连续分子梯度（随皮层深度变化基因表达渐变） | MERFISH 空间定位 + 基因表达向量分析 | PMID:34616063 | 高 |
| 小鼠全脑存在 5322 个转录组细胞簇，分属 34 类/338 亚类 | 700 万 scRNA-seq + 430 万 MERFISH 整合 | PMID:38092916（PMC10719114）| 高 |
| 背侧脑区细胞类型少而分化，腹侧多而相近 | 全脑 MERFISH 空间分布分析 | PMID:38092916 | 高 |
| 转录因子是细胞类型分类的最强预测因子（优于其他基因类别）| 全脑 TF 基因集单独分类与全转录组比较 | PMID:38092916 | 高 |
| 老化驱动的非神经元炎症变化在白质高度富集（空间特异性）| 416 基因 MERFISH；3 个年龄组；额叶皮层+纹状体 | PMID:36580914（PMC10024607）| 中（小鼠，需人类验证）|
| 空间模块（分子定义）部分跨越传统解剖边界 | 1100+ 基因 MERFISH；局部细胞类型组成聚类 | PMID:38092912（PMC10719103）| 高 |

## 连接

- [[single-cell-rna-seq]] — 互补方法：scRNA-seq 提供全转录组分辨率，空间转录组学提供位置信息
- [[transcriptomic-cell-types]] — 空间维度：同一转录组细胞类型在不同位置可有系统性分子差异
- [[connectomics]] — 整合方向：空间转录组学提供连接组节点的分子身份注释
- [[cortical-canonical-microcircuit]] — 皮层层级空间组织的分子验证
- [[critical-period]] — 发育应用：追踪细胞类型的空间迁移与基因程序变化
- [[als-amyotrophic-lateral-sclerosis]] — 疾病应用：脆弱细胞类型的空间分布
- [[parkinsons-disease]] — 疾病应用：多巴胺能神经元亚型的空间分布与选择性死亡

## 未解问题

- Q-spatial-cell-type-boundary（高）：5322 个簇的边界依赖聚类参数——什么分辨率的分类对应真实的功能差异？
- Q-spatial-human-brain（高）：人类全脑 MERFISH 面临技术障碍（组织质量/计算规模/样本可及性），小鼠发现在多大程度上适用于人类？
- Q-spatial-functional-correspondence（高）：转录组细胞类型与功能细胞类型（感受野/放电模式）的对应关系？MICrONS 与 Allen Brain Cell Atlas 整合是关键

## 修订历史

- 2026-09-16 · 创建 · 基于《给细胞贴上地址标签》（#146）· 来源：Chen 2015 / Zhang 2021 / Yao 2023 / Zhang 2023 / Allen 2023 · 初始置信度：高（方法论 established，小鼠全脑图谱 established，人类推广 emerging）

## 来源文章

- [[2026-09-16-spatial-transcriptomics-brain-cell-atlas]]

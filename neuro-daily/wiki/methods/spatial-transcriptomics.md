---
title: 空间转录组学
slug: spatial-transcriptomics
domain: methods
type: method
status: mainstream
confidence: high
created: 2026-09-14
updated: 2026-09-14
revision_count: 1
dimensions: [molecular, cellular, methods]
related: [single-cell-rna-seq, connectomics, merfish, cortical-layers, cell-type-diversity]
prerequisites: [single-cell-rna-seq, cortical-layers]
opens_questions: [Q-spatial-tx-01, Q-spatial-tx-02, Q-spatial-tx-03]
source_articles: [2026-09-14-spatial-transcriptomics-brain-cell-atlas]
key_sources: ["PMID:38092916", "PMID:36945367", "PMID:40369074", "PMID:37779145"]
---

# 空间转录组学 (Spatial Transcriptomics)

> **一句话定义**：在保留组织三维空间结构的同时，对每个细胞进行基因表达量测量的技术集合，同时回答"这个细胞表达什么基因"和"它在组织的哪里"两个问题。

## 当前理解

我们现在认为，空间转录组学是后单细胞测序时代神经科学的关键方法突破，它解决了单细胞RNA测序（scRNA-seq）的根本性信息缺失——空间坐标。神经元的功能深度依赖其所处的解剖位置：海马CA1和CA3的锥体神经元分子标记相似，但功能截然不同（CA3：模式补全；CA1：整合输出）；皮层各层的锥体神经元有共同的excitatory identity，但L2/3、L5a、L5b的投射靶点、功能计算和疾病脆弱性差异巨大。

**主要技术类别**：
- **基于成像的原位杂交**（MERFISH、seqFISH+、STARmap）：高分辨率（单细胞至亚细胞），但基因数有限（数百至数千）
- **基于测序的空间捕获**（10x Visium、Slide-seq、Stereo-seq）：全转录组无偏，但分辨率较粗（55 μm多细胞至单细胞）

**关键应用成就**（截至2025年）：
- 小鼠全脑5322个细胞聚类的精确空间图谱（Yao et al. 2023，BICCN）
- 人类胎儿皮层六层结构在形态出现前三个月就已分子确立（Qian et al. 2025）
- 假设下丘脑中特定神经元组合驱动社会行为（MERFISH行为研究）
- 疾病病理区的细胞类型特异性基因模块（AD、ALS等）

## 关键机制

### MERFISH（代表性成像方法）

MERFISH的核心是**组合荧光条码**：给每个目标mRNA分子分配唯一的二进制条码（每一"位"代表一轮成像的有/无荧光）。对N个目标基因，设计最小码字长度（如100基因用7轮成像，2⁷=128>100）。使用**Hamming距离≥2**的编码方案，使单位错误（荧光检测失误）可被检测和纠正（"Error-Robust"的含义）。多轮成像后，每个mRNA点的完整条码被读出，识别其基因身份并记录其像素坐标。

**整合流程**（BICCN标准）：
1. 脑组织冷冻切片（20–50 μm厚）
2. 样本固定、探针杂交
3. 多轮荧光成像（每轮用不同颜色组合）
4. 单分子RNA检测与坐标记录
5. 细胞分割（DAPI核染色+深度学习）
6. 生成细胞×基因计数矩阵（含x/y/z坐标）
7. 与scRNA-seq参考整合，精细化细胞类型分配
8. 注册到标准坐标系（如Allen CCF）

### 与scRNA-seq的互补整合

两者优势互补：scRNA-seq检测效率高、全转录组覆盖、已有大量参考数据；MERFISH提供精确空间坐标。标准流程是：用scRNA-seq建立高分辨率细胞类型参考，用MERFISH的空间数据（基因子集）对组织内每个细胞进行类型分配，从而同时获得分子身份和空间位置。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 小鼠全脑有5322个转录组学定义的细胞聚类 | scRNA-seq（400万细胞）+ MERFISH（430万细胞），4层分类体系 | PMID:38092916（Yao 2023）| 高 |
| 背侧大脑细胞类型少但多样性高，腹侧多但亲缘关系近 | MERFISH全脑空间分布分析 | PMID:38092916（Yao 2023）| 高 |
| 人类皮层六层分子模式在GW22确立，比形态出现（GW34）早3个月 | MERFISH，1800万细胞，8个皮层区域，7个发育时间点 | PMID:40369074（Qian 2025）| 高 |
| V1专属神经元亚型在GW20就已存在，早于视觉输入 | MERFISH，V1 vs V2神经元亚型互斥分布 | PMID:40369074（Qian 2025）| 高 |
| 细胞类型沿解剖轴呈梯度分布，而非完全离散边界 | MERFISH全脑空间图谱 | PMID:36945367（Zhang 2023）| 高 |
| 皮层区域化大多数呈渐变，V1-V2边界是锐利例外 | 四对互斥神经元亚型在V1/V2边界的分布 | PMID:40369074（Qian 2025）| 高 |

## 连接

- [[single-cell-rna-seq]] — scRNA-seq是空间转录组学的参考和互补；MERFISH通常需要scRNA-seq参考数据进行细胞类型分配
- [[connectomics]] — 结构连接组学提供"谁连着谁"，空间转录组学提供"谁是谁、在哪里"；两者整合是理解回路的下一步
- [[cortical-layers]] — 空间转录组学是理解皮层六层分子分化最直接的工具；Qian 2025证明六层分子预编程
- [[cell-type-diversity]] — 空间转录组学是揭示大脑细胞类型真实多样性的主要方法
- [[critical-period]] — Qian 2025的发现（V1专属亚型在功能输入前已存在）与关键期"内在vs外在"的争论直接相关

## 未解问题

- **Q-spatial-tx-01（高优先级）**：转录组身份是否完全预测功能特性？电生理特性、突触连接和行为相关反应是否与转录组聚类一一对应，还是存在相同转录组但不同功能状态的细胞？
- **Q-spatial-tx-02（高优先级）**：5322个聚类的"真实性"——不同分辨率参数下的分类数变化多大？细胞类型之间是离散边界还是连续谱系？
- **Q-spatial-tx-03（中优先级）**：如何实现实时空间转录组（dynamic spatial transcriptomics）——捕获神经元活动诱导的即时转录组变化而非仅有静态快照？

## 修订历史

- 2026-09-14 · 创建 · 基于《空间转录组学：当分子地图遇上大脑地理》（文章#144）· 初始置信度：高

## 来源文章

- [[2026-09-14-spatial-transcriptomics-brain-cell-atlas]]

---
title: MERFISH（多重误差稳健荧光原位杂交）
slug: merfish
domain: methods
type: method
status: mainstream
confidence: high
created: 2026-09-14
updated: 2026-09-14
revision_count: 1
dimensions: [molecular, cellular, methods]
related: [spatial-transcriptomics, single-cell-rna-seq, connectomics]
prerequisites: [single-cell-rna-seq]
opens_questions: []
source_articles: [2026-09-14-spatial-transcriptomics-brain-cell-atlas]
key_sources: ["PMID:38092916", "PMID:36945367", "PMID:37779145"]
---

# MERFISH（多重误差稳健荧光原位杂交, Multiplexed Error-Robust Fluorescence In Situ Hybridization）

> **一句话定义**：通过给每个目标mRNA分子分配唯一的荧光二进制条码，在完整组织切片中以单细胞分辨率同时检测数百至数千个基因的空间表达模式的成像技术。

## 当前理解

MERFISH是目前在全脑神经科学研究中应用最广的高分辨率空间转录组学技术，由哈佛大学庄小威（Xiaowei Zhuang）实验室开发。它解决了传统FISH（荧光原位杂交）只能同时检测1–2个基因的根本限制，通过组合荧光条码实现了高度多路复用（>1000基因同时检测）。

核心创新点：**误差稳健编码**。传统多色荧光标记检测时，单次成像噪声会导致假阳/假阴。MERFISH的解决方案是对条码使用Hamming距离≥2的设计，使任何单位错误都可被检测和纠正，大幅提升了大规模多路复用的可靠性。

**主要应用成就**：
- 小鼠全脑5322细胞聚类图谱（Yao et al. 2023，BICCN，PMID:38092916）
- 人类胎儿皮层六层分子预编程发现（Qian et al. 2025，PMID:40369074）
- 庄小威课题组在下丘脑中发现特定神经元组合调控社会行为

## 关键机制

**条码分配**：
- 为每个目标mRNA设计一个唯一的n位二进制条码（如100个基因用7位码，因为2⁷=128>100）
- 每一"位"对应一轮成像：成像该轮中mRNA点有荧光 = 1，无荧光 = 0
- n轮成像后读取完整条码，识别mRNA身份

**误差稳健设计**：
- 选用Hamming距离≥2的编码方案（任意两个有效条码至少有2位不同）
- 当观察到一个单位错误的条码时，可将其纠正到最近的有效条码
- 使假阳性和假阴性率从~10%降至<1%

**实验流程**：
1. 组织切片（冷冻，20–50μm）
2. 目标mRNA的荧光编码探针杂交
3. 多轮（n轮）荧光成像，每轮不同荧光通道
4. 单分子荧光点检测（亚衍射分辨率，~200nm）
5. 细胞分割（DAPI核+深度学习）
6. 条码读取和误差纠正
7. 单细胞坐标-基因表达矩阵生成
8. 注册到参考坐标系（Allen CCF等）

**最新发展**：MERFISH 2.0（2026预印本）改善了固定组织中RNA降解样本的检测灵敏度，扩展了对人类档案组织的适用性。

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| MERFISH在全脑水平实现单细胞分辨率 | 430万个细胞，59个冠状切片，>1100基因面板 | PMID:38092916 | 高 |
| 误差稳健编码将假阳性率降至<1% | 原始MERFISH论文中的编码理论验证（Chen et al. 2015）| 原始技术论文 | 高 |

## 连接

- [[spatial-transcriptomics]] — MERFISH是空间转录组学的代表性成像方法
- [[single-cell-rna-seq]] — MERFISH通常以scRNA-seq为参考进行细胞类型分配，两者互补
- [[connectomics]] — MERFISH提供分子身份坐标，连接组学提供突触连接；整合是未来方向

## 修订历史

- 2026-09-14 · 创建 · 基于《空间转录组学：当分子地图遇上大脑地理》（文章#144）· 初始置信度：高

## 来源文章

- [[2026-09-14-spatial-transcriptomics-brain-cell-atlas]]

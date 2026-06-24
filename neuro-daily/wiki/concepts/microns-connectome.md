---
title: MICrONS 皮层连接组项目
slug: microns-connectome
domain: concepts
type: entity
status: established
confidence: high
created: 2026-09-13
updated: 2026-09-13
revision_count: 1
dimensions: [methods, microcircuit, brain-region, whole-brain-network]
related: [connectomics, like-to-like-connectivity, inhibitory-specificity, binary-analog-synapse, v1-primary-visual-cortex, cortical-canonical-microcircuit, cnn-visual-cortex-analogy]
prerequisites: [connectomics, v1-primary-visual-cortex]
opens_questions: [Q-conn-02, Q-conn-03, Q-mc-01, Q-mc-02]
source_articles: [2026-08-06-connectomics-flywire-wiring-diagram, 2026-09-13-microns-inhibitory-binary-synapse]
key_sources:
  - "PMID:40205214"
  - "PMCID:PMC11981939"
  - "DOI:10.1038/s41586-025-08790-w"
  - "PMID:36993398"
  - "PMCID:PMC10054929"
  - "PMID:36747710"
  - "PMCID:PMC9900837"
  - "PMID:36382887"
  - "PMCID:PMC9704804"
---

# MICrONS 皮层连接组项目 (MICrONS Cortical Connectome Project)

> **一句话定义**：BRAIN Initiative 旗舰数据集——将小鼠视觉皮层 1.3×0.87×0.82 mm³ 体积内约 20 万神经元的活体钙成像功能记录（~75,000 个视觉响应神经元）与 4nm 分辨率电子显微镜重建（5.24 亿突触）在单细胞精度上配准，形成迄今最大规模的哺乳动物**功能连接组**开放数据集，已衍生出多篇揭示皮层连接语法的里程碑论文。

---

## 当前理解

MICrONS（Machine Intelligence from Cortical Networks）项目是美国 BRAIN Initiative 的核心成果之一，由普林斯顿大学、贝勒医学院、艾伦脑科学研究所、卡内基梅隆大学等多机构联合完成，于 2025 年发表数据集主论文（MICrONS Consortium, *Nature* 640:435-447, PMID: 40205214, **PMCID: PMC11981939**，全文开放）。

### 技术规格

| 维度 | 数值 |
|------|------|
| EM 体积 | 1.3 × 0.87 × 0.82 mm³ |
| EM 分辨率 | ~4 nm（切片厚度约 40 nm） |
| 切片数量 | 26,652 张 |
| 总细胞数 | >200,000 |
| 总突触数 | ~524,000,000（5.24 亿） |
| 精校神经元（含轴突） | 1,433 个 |
| 精校神经元（仅树突） | 1,188 个 |
| 功能记录神经元 | ~75,000（双光子钙成像） |
| 功能记录区域 | VISp（初级视觉）+ VISrl、VISal、VISlm（高级视觉） |

### 独特性：功能-结构配准

MICrONS 与之前连接组项目（C. elegans, FlyWire）的最根本区别是：**同一批神经元既有活体功能记录，又有完整结构重建，且两者在单细胞精度上配准**。

这使以下研究问题变得可回答（而此前只能推测）：
- 功能相似的神经元（相同视觉偏好）是否优先相互连接？→ **是（like-to-like，Ding et al. 2024）**
- 兴奋性突触的大小是否反映神经元对的协同激活历史？→ **是（二进制成分，Dorkenwald et al. 2022）**
- 抑制性接线是否遵循细胞类型特异性的精确规则？→ **是（18 种模体，Schneider-Mizell et al. 2023）**

### 主要衍生论文

| 论文 | 核心发现 | PMID / PMCID |
|------|---------|-------------|
| MICrONS Consortium (2025) | 数据集发布；功能-结构联合分析框架；like-to-like 概述 | PMID:40205214, PMC11981939 |
| Ding et al. (2024) | Like-to-like 布线规则；跨层跨区域普遍性；AI 验证 | PMID:36993398, PMC10054929 |
| Schneider-Mizell et al. (2023/2024) | 18 种抑制模体群；去抑制专家；亚层精度 | PMID:36747710, PMC9900837 |
| Dorkenwald et al. (2022) | 突触大小二进制-模拟双变量；双稳态突触支持 | PMID:36382887, PMC9704804 |

### 开放数据

数据集完全开放，可通过 microns-explorer.org 交互式访问，亦提供 Python API（CAVE, CloudVolume）进行程序化查询，是全球神经科学社区的公共资源。

---

## 关键机制

### 数据获取流程

1. **活体功能记录**：对清醒、固定头部小鼠，用双光子显微镜（通过颅骨窗口）记录初级和高级视觉皮层的 Ca²⁺ 荧光信号，对应神经元的视觉响应
2. **后续 EM 重建**：同一动物灌注固定 → 连续超薄切片 → 透射电镜（4nm/pixel）扫描 → 深度学习自动分割（初始神经元轮廓提取）→ 专家和众包精校
3. **配准**：功能记录的神经元通过三维坐标（基于细胞核位置）与 EM 重建数据配准，实现功能数据（视觉响应向量）与结构数据（突触连接）的单细胞对应

### 规模挑战与突破

- **数据量**：5.24 亿突触的完整存储与检索需要约数百 TB 数据
- **自动分割准确性**：深度学习分割在密集区域仍有约 0.5-2% 的错误率（merge/split errors）；1,433 个精校神经元代表了人工校正后可信度最高的子集
- **配准误差**：功能数据（活体，含形变）与 EM 数据（固定，有收缩）之间的配准引入系统误差，影响细胞对匹配的准确性，估计约 5-15% 的细胞对可能存在配准误差

---

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| MICrONS 是目前规模最大的哺乳动物功能连接组 | 数据规模比较（>200k 细胞，5.24 亿突触，单细胞功能配准） | PMID:40205214, PMC11981939 | 高 |
| 功能-结构配准在单细胞精度上可行（小鼠皮层） | 三维坐标配准，细胞核位置对齐，~75,000 功能配准神经元 | PMID:40205214 | 高（尽管有约 5-15% 估计配准误差） |
| 数据集开放，可重分析 | microns-explorer.org 公开访问，CAVE/CloudVolume API | MICrONS Consortium | 高 |

---

## 连接

- [[connectomics]] — MICrONS 是连接组学发展阶梯中哺乳动物皮层级别的里程碑
- [[like-to-like-connectivity]] — 从 MICrONS 数据直接发现的布线规则
- [[inhibitory-specificity]] — 从 MICrONS 数据揭示的抑制回路精确性
- [[binary-analog-synapse]] — 从 MICrONS 数据发现的突触强度双变量结构
- [[v1-primary-visual-cortex]] — MICrONS 的主要研究区域（VISp 及相邻高级视觉区）
- [[cortical-canonical-microcircuit]] — MICrONS 提供了标准皮层回路模型的高分辨率检验与修正
- [[cnn-visual-cortex-analogy]] — MICrONS 的 like-to-like 发现强化了生物视觉皮层与 CNN 之间的计算类比

---

## 未解问题

- **Q-conn-02**：能否从突触超微结构（活动区面积等）估计突触功能权重，从而建立"加权接线图"？
- **Q-conn-03**：MICrONS 规模的功能连接组能否扩展到非感觉皮层（前额叶、颞叶联合区）？
- **Q-mc-01**：MICrONS 揭示的 18 种抑制模体在发育中如何建立？
- **Q-mc-02**：MICrONS 的发现（like-to-like、抑制特异性）是否适用于前额叶等联合皮层？

---

## 修订历史

- 2026-09-13 · 创建 · 基于《皮层连接的完整语法》文章 #143 · 来源：MICrONS Consortium 2025 (PMID:40205214) 及四篇衍生论文 · 初始状态：established（数据集本身存在且开放，已被多篇独立分析论文引用和使用）

---

## 来源文章

- [[2026-08-06-connectomics-flywire-wiring-diagram]]
- [[2026-09-13-microns-inhibitory-binary-synapse]]

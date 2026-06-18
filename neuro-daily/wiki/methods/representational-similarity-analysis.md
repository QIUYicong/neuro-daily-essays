---
title: 表征相似性分析（RSA）
slug: representational-similarity-analysis
domain: methods
type: method
status: established
confidence: high
created: 2026-06-18
updated: 2026-06-18
revision_count: 1
dimensions: [methods, cognition, whole-brain-network]
related: [dnn-ventral-stream, task-optimized-model, v1-orientation-selectivity, fmri]
prerequisites: [neural-coding]
opens_questions: []
source_articles: [2026-06-18-dnn-ventral-stream-comparison]
key_sources: ["PMID:25375136", "PMID:24812127", "PMID:26906502"]
---

# 表征相似性分析（Representational Similarity Analysis, RSA）

> **一句话定义**：RSA 通过比较两个系统（如神经网络层与脑区）对同一刺激集的"相互区分结构"来评估它们的表征相似性，无需直接对应各系统的单元，也不依赖维度数量相同。

## 当前理解

RSA 的核心思想是：与其比较两个系统（一个脑区和一个计算模型）的具体单元，不如比较它们如何**区分**一组刺激。如果系统 A 认为刺激 P 和 Q 很相似、刺激 R 和 S 截然不同，系统 B 也有同样的判断，那么它们就有相似的表征结构——即使它们有完全不同的神经元数量、维度和内部编码。

**操作步骤**：
1. 选择 N 个刺激（如 N=96 幅图像）
2. 对每个系统，获取每个刺激的响应向量（神经元放电率 or 网络激活值）
3. 计算两两刺激之间的**表征距离**（1-相关系数，欧式距离，等），构成 N×N 的**表征差异矩阵（RDM, Representational Dissimilarity Matrix）**
4. 比较两个系统的 RDM 是否相似（用 Spearman r 或 Kendall τ_A 等秩相关）

RDM 的关键优势：它是**维度无关**的。一个有 200 个神经元的脑区和一个有 10 万个单元的 CNN 层，可以在同一个 N×N 矩阵空间中比较。

## 关键机制

### RDM 的构建
对于一个系统（脑区或网络层），N 个刺激各产生一个响应向量（维度 = 神经元数 or 单元数）。RDM[i,j] = 1 - Pearson_r(响应_i, 响应_j)，或用欧式距离、马哈拉诺比斯距离等。这个矩阵是对称的，对角线为 0。

### 系统间的比较
两个 RDM 的相关系数反映两个系统的表征几何有多相似。通常用 **Kendall τ_A** 而非 Pearson r，因为 τ_A 对噪声更鲁棒，且适用于非正态分布。

### 噪声上界（Noise Ceiling）
由于测量本身有噪声，完美的 RDM 相关系数上限不是 1.0 而是**噪声上界**（从同一脑区的不同测量中估算，代表"你能达到的最高可能相关系数"）。触及噪声上界意味着模型已经解释了数据中的全部可解释信息。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 深度监督 CNN 的 IT-RDM 相关性达到噪声上界（τ_A=0.38） | 比较 37 个模型的 RDM vs 人类 fMRI/猴 MEG IT 数据 | PMID:25375136 | 高 |
| 对比学习无监督模型的 RDM 相关性等同于监督 CNN | SimCLR/MoCo vs AlexNet，猕猴电生理 RDM | PMID:33431673 | 中-高 |
| 线性可预测性（另一种测量方式）与 RSA 给出一致结论 | 两种方法在 Yamins 2014 中并行使用并比较 | PMID:24812127 | 高 |

## 连接

- [[dnn-ventral-stream]] — RSA 是比较 CNN 与腹侧视觉流的核心工具
- [[task-optimized-model]] — RSA 是测试任务优化模型的主要评估方法
- [[v1-orientation-selectivity]] — V1 的 RDM 与 CNN 低层 RDM 高度相关

## 未解问题

- RSA 对噪声水平、刺激集选择的敏感性有多强？
- 触及"噪声上界"是否等同于"完全解释大脑"？上界本身是否被低估？

## 修订历史

- 2026-06-18 · 创建 · 基于《当人工神经网络照镜子大脑》一文 · 初始置信度：高（RSA 为成熟方法论）

## 来源文章

- [[2026-06-18-dnn-ventral-stream-comparison]]

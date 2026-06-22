---
title: 颞下皮层（IT 皮层）
slug: inferior-temporal-cortex
domain: neurons
type: region
status: established
confidence: high
created: 2026-08-29
updated: 2026-08-29
revision_count: 1
dimensions: [brain-region, systems, cellular, cognition]
related: [ventral-visual-stream, object-recognition, v1-primary-visual-cortex, entorhinal-cortex, hippocampal-circuit, cnn-visual-cortex-analogy, place-cell, grid-cell]
prerequisites: [ventral-visual-stream, v1-primary-visual-cortex]
opens_questions: [Q-it-01, Q-it-02]
source_articles: [2026-08-29-ventral-visual-stream-object-recognition]
key_sources: ["PMID:8833438", "PMID:17631409", "PMID:20869601", "PMCID:PMC2946943", "PMID:22836252", "PMCID:PMC3307055", "PMID:32494012", "PMID:40200940", "PMCID:PMC11975662"]
---

# 颞下皮层（IT 皮层）(Inferotemporal Cortex)

> **一句话定义**：颞下皮层（IT，包括前颞下皮层 TE 和后颞下皮层 TEO）是腹侧视觉流的终点，负责物体身份的不变性表征——神经元种群以线性可分的高维格式编码物体类别，对物体的位置、大小、旋转等视觉变换具有高度容忍度。

## 当前理解

IT 皮层位于颞叶腹侧（灵长类），分为后部（TEO/v4 延伸区）和前部（TE）两个主要亚区，前者接收来自 V4 的输入，后者接收来自 TEO 的输入并投射到内嗅皮层、杏仁核、海马及前额叶。

IT 皮层的核心功能是解决视觉物体识别的"不变性-选择性悖论"：同一物体在不同位置、大小、视角下仍被识别为同一物体，而不同物体即使在相似视觉条件下也被区分。IT 不是通过让单个神经元在所有条件下均匀响应来实现不变性，而是通过**种群活动的几何结构**——在高维神经状态空间中，同一物体在各种条件下的活动向量仍聚集成线性可分的簇。

IT 皮层的功能特性（Tanaka 1996, PMID:8833438）：
1. 大感受野（10–20°+，常跨越中央凹）
2. 对中等复杂度特征（物体部件及其组合）选择
3. 对视觉变换（平移、缩放）的高度容忍
4. 稀疏但高对比度的响应（少数图像/物体驱动强烈响应）

## 关键机制

### 1. 物体流形的线性可分性

在 IT 种群活动的高维状态空间中，代表不同物体的神经活动形成**线性可分的流形**（linearly separable manifolds）。用线性分类器对 IT 种群活动解码：8 类物体在多样化位置/大小/背景条件下达到 90%+ 准确率（Hung et al. 2005）。相比之下，V1 种群活动在相同条件下仅约 40–50%——这一差距量化了腹侧流"解缠"计算的效果（DiCarlo & Cox 2007, PMID:17631409）。

### 2. IT 神经元选择性的来源

IT 神经元的选择性并非简单的"感受野大+容忍"，而是对**特定复杂特征组合**的精确偏好：
- Tanaka 等人的系统性降维（reducing complexity）实验显示，IT 神经元最优刺激通常是"中等复杂度特征"——既不是简单线段，也不是完整物体；
- 有些神经元对面孔、手或特定几何图案有选择性；
- TE 比 TEO 具有更强的类别学习信号（Shimizu et al. 2024，引自 PMC11975662），表明 TE 是类别选择性最终形成的主要场所。

### 3. 物体空间地图组织

Bao et al.（2020，PMID:32494012）在猕猴中发现 IT 皮层按**低维"物体空间"坐标轴**组织：
- 4 个解剖聚集网络，各自对应 DNN 分析提取的主要物体维度
- 著名的**面孔区**（face patches，Tsao & Livingstone 系列）是物体空间"动物面孔"维度的极化极端，而非独立功能模块
- 在 IT 的三个层级（TEO → 中 TE → 前 TE），该地图重复出现，视角不变性随层级提升

### 4. 不变性的无监督学习

IT 皮层的不变性并非硬编码，而是通过视觉经验动态维持：
- Li & DiCarlo 2008/2010（PMID:18787171, 20869601）通过操控视觉时间统计（打乱时间连续性），在几小时内改变了 IT 的位置和大小不变性
- 这支持**无监督时间连续性学习（UTL）**：自然视觉中物体在变换间保持身份→Hebbian 学习加强相同物体在不同变换下的活动相关性
- 时序不对称（滞后强于超前）暗示 STDP 型机制

### 5. IT 与认知/记忆的接口

IT 皮层通过以下两条主要通路将视觉物体表征接入认知和记忆系统：
1. **IT→内嗅皮层→海马**（"what"通路）：物体身份信息通过周围嗅皮层（perirhinal cortex）和内嗅皮层传入海马，与"where"（来自背侧流→海马体旁）和"when"（时间上下文）整合形成情节记忆
2. **IT→前额叶**（物体工作记忆）：在延迟任务中，IT 活动静默保持（activity-silent working memory）可能维持物体表征，前额叶的目标/任务状态则通过反馈调制 IT 活动

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| IT 种群活动对物体线性可分（90%+准确率）| 猕猴 IT 多电极 + 线性分类器，多变换条件 | Hung et al. 2005（经综述引用）| 高 |
| IT 神经元对中等复杂度特征选择 | 猕猴单细胞记录，系统降维刺激集 | Tanaka 1996 (PMID:8833438) | 高 |
| IT 不变性靠视觉经验动态维持 | 时间统计操控 + IT 记录，几小时可逆 | Li & DiCarlo 2010 (PMC2946943) | 高 |
| V4→IT 稀疏度恒定（选择性↑，不变性↑，两者抵消）| 猕猴 V4/IT 多电极，自然图像 | Rust & DiCarlo 2012 (PMC3307055) | 高 |
| IT 组织为物体空间低维坐标地图 | 猕猴大规模成像+电生理 | Bao et al. 2020 (PMID:32494012) | 高（猕猴）；中（人类类比）|
| TE（前IT）比 TEO（后IT）类别学习信号更强 | 猕猴单细胞记录，类别判断训练 | Shimizu 2024（引自 PMC11975662）| 中 |

## 连接

- [[ventral-visual-stream]] — IT 是腹侧流的终点和计算成就体现
- [[object-recognition]] — IT 是核心物体识别的神经基底
- [[v1-primary-visual-cortex]] — 腹侧流起点，与 IT 形成层级对
- [[entorhinal-cortex]] — 接收 IT 的物体表征，传递给海马
- [[hippocampal-circuit]] — IT 提供"what"，海马整合情节记忆
- [[cnn-visual-cortex-analogy]] — CNN 顶层预测 IT 响应约 48.5% 方差
- [[place-cell]] — 海马地点细胞的活动受 IT 物体身份信息的调节
- [[grid-cell]] — 内嗅皮层网格细胞接收来自 IT 的物体输入，可能参与物体空间的泛化

## 未解问题

- **Q-it-01（高优先级）**：人类 IT 皮层（梭状回/颞枕皮层）是否与猕猴 IT 具有相同的物体空间 4 轴组织？文化习得的类别（如汉字/字母）如何改变人类 IT 的组织（VWFA 字形区是物体空间中"文字"维度的特化，还是独立机制）？
- **Q-it-02（中优先级）**：IT 皮层的重复抑制（repetition suppression）机制是什么？它是物体识别的"确认信号"，还是注意资源的释放，还是预测编码的预测满足？

## 修订历史

- 2026-08-29 · 创建 · 基于《腹侧视觉流的"解缠"之旅》(#127) · 初始置信度：高

## 来源文章

- [[2026-08-29-ventral-visual-stream-object-recognition]]

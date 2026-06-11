---
title: 认知地图
slug: cognitive-map
domain: concepts
type: theory
status: mainstream
confidence: high
created: 2026-06-22
updated: 2026-09-18
revision_count: 3
dimensions: [brain-region, whole-brain-network, behavior, cognition]
related: [place-cells, grid-cells, path-integration, entorhinal-cortex, hippocampal-circuit, memory-consolidation, sharp-wave-ripples, theta-oscillations, world-model, semantic-memory-hub, conceptual-space-geometry, successor-representation]
prerequisites: [place-cells, grid-cells, hippocampal-circuit]
opens_questions: [Q-gc-01, Q-cogmap-01, Q-cogmap-02]
source_articles: [2026-06-22-grid-cells-place-cells, 2026-07-16-semantic-hub-atl-conceptual-space, 2026-09-18-hippocampal-successor-representation-simulation]
key_sources: ["PMID:5124915", "PMID:15965463", "PMID:23354386", "PMID:27572056", "PMID:38065931", "PMID:41887217", "PMID:40063809", "PMID:33603654", "PMID:28967910", "PMID:38849521"]
---

# 认知地图 (Cognitive Map)

> **一句话定义**：海马-内嗅皮层系统构建的空间（及更广义的关系）结构内部模型；不只表征物理位置，还将同样的坐标框架扩展至时间序列、情节记忆和概念空间，是大脑组织和检索结构性知识的通用计算格式。

## 当前理解

我们现在认为，认知地图不只是"大脑里的地图"，而是一个更广义的**结构化关系表征系统**。原始意义上（Tolman 1948），认知地图指动物对空间布局的内部模型，使其能走最短路而非重复强化的特定路径。现在的理解大大扩展了这一概念：

1. **物理空间层**：场所细胞 + 网格细胞 + 头朝向细胞 + 边界细胞共同构建物理空间的多层表征
2. **时间/情节层**：同样的海马-EC回路组织时间序列（情节记忆），路径整合对应时序整合（Buzsáki & Moser 2013）
3. **抽象概念层**：最新证据表明，EC在心理模拟（Bellmund 2016）、视觉空间（Nau 2018）、概念关系（Viganò 2023）中均出现六边形对称编码，暗示网格-场所系统是大脑处理**任何连续、结构化信息空间**的通用格式

从这个视角，阿尔茨海默病早期的EC损伤不只是"迷路"，而是**整个结构化世界模型的基础设施损坏**——这解释了为什么AD患者的情节记忆、空间导航和结构性知识同步衰退。

## 关键机制

### 1. 空间导航层：场所-网格双系统

- **场所细胞**（海马CA1/CA3）：环境特异的索引地图，提供"我现在在哪个熟悉位置"的当前坐标
- **网格细胞**（MEC）：环境无关的度量坐标系，提供连续空间度量；通过路径整合实时更新
- **边界细胞**：在靠近环境边界时激活，为网格/场所系统提供环境边界锚定
- **头朝向细胞**：编码当前朝向，为路径整合提供方向参数

### 2. 记忆层：时间序列的海马编码

导航和情节记忆的共同点（Buzsáki & Moser 2013）：
- 两者都需要对自身轨迹（空间路径/时间序列）进行连续整合
- 两者都需要维护一个"当前状态"（当前位置/当前情节帧）
- 两者都需要能快速切换到不同的上下文（重映射/情境依赖记忆）
- θ序列在两者中都提供时间压缩的前向预测

### 3. 抽象空间层：认知地图的泛化

近年证据表明，网格样的六边形对称编码不只出现于物理空间：
- **心理模拟**：Bellmund等2016（PMC5005038）——人类想象方位时EC出现六边形信号，无需实际运动
- **视觉空间**：Nau等2018——追踪视觉目标方向时EC出现六边形调制
- **概念空间**：Viganò等2023（PMID:38065931）——在概念空间中搜索时EC和PFC出现网格样激活重构
- **发育与智力**：Qu等2026（PMID:41887217）——非空间网格码强度预测青少年流体智力

这些证据支持"认知地图作为通用知识格式"假说（Bellmund 2019 Science综述），但仍有争议（见下）。

### 4. DSI统一计算框架

Haga, Oseki, Fukai（2025，PNAS，PMID:40063809）的**DSI（Disentangled Successor Information）模型**从数学上将空间导航和语义认知统一：
- 空间认知的后继者表征（successor representation，SR）与NLP的逐点互信息（PMI）在数学上**完全等价**
- DSI-decorr变体自发产生六角网格表征（类网格细胞），DSI-sparse变体产生稀疏选择性单元（类场所细胞/概念细胞）
- **词语类比推理**（"国王−男人+女人=女王"）与空间三角推断（向量叠加路径整合）是完全相同的算术运算

这意味着：认知地图的计算核心（预测"从当前状态出发，最可能遭遇哪些相邻状态"）是大脑处理任何结构化信息空间（物理路径、概念关系、词语共现）的通用算法，网格细胞和概念细胞只是这一通用算法在不同领域的表达形式。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 动物能走捷径（最短路），不只循强化路径 | Tolman 1948大鼠迷宫 | Tolman 1948 | 高（经典，多次重复） |
| 场所细胞构建环境特异的内部地图 | 多环境记录 + 重映射 | PMID:5124915等 | 高 |
| 记忆与导航共用θ-EC-海马框架 | 综述+计算模型 | PMID:23354386 | 高 |
| 心理模拟中EC出现六边形信号 | 人类fMRI+MVPA | PMID:27572056（PMC5005038） | 中-高 |
| 概念空间搜索时EC和PFC出现网格样编码 | 人类fMRI | PMID:38065931 | 中（新兴） |
| 非空间网格码强度预测流体智力（发育研究） | 203名青少年fMRI，Cell 2026 | PMID:41887217 | 中（新发现） |
| 内嗅皮层六重对称信号编码二维概念类别空间方向 | fMRI-RSA，类别学习范式 | PMID:33603654 | 中 |
| SR与PMI数学等价；DSI统一网格细胞与概念细胞计算 | 理论模型+NLP模拟 | PMID:40063809 | 中（理论框架，待实验验证）|

## 连接

- [[place-cells]] — 认知地图的基本位置编码单元；环境特异索引
- [[grid-cells]] — 认知地图的通用度量坐标系基础设施
- [[path-integration]] — 认知地图在无地标时的自主更新机制
- [[hippocampal-circuit]] — 认知地图的主要神经底物
- [[memory-consolidation]] — 认知地图（场所序列）通过SWR重播转写为新皮层长期记忆
- [[world-model]] — 认知地图是"世界模型"在空间/结构层面的神经实现
- [[semantic-memory-hub]] — ATL枢纽组织的语义知识可能是认知地图在概念领域的实现
- [[conceptual-space-geometry]] — 概念空间几何是认知地图理论向语义域的直接延伸；DSI模型提供统一计算基础
- [[successor-representation]] — SR是认知地图的计算形式化：场所细胞可能编码SR矩阵行，网格细胞可能是SR特征向量分解

## 未解问题

- Q-gc-01：认知地图的"泛化"是真实的计算泛化，还是fMRI六边形分析的方法论artifact？需要单细胞分辨率验证
- Q-cogmap-01：概念空间中的"网格码"是否也由MEC的网格细胞实现，还是由与导航无关的皮层区域产生类似几何结构？
- Q-cogmap-02：认知地图是如何从儿童期逐步建立的？网格码的发育轨迹（Qu 2026）是先天程序还是需要空间探索经验驱动？

## 修订历史

- 2026-06-22 · 创建 · 基于《六边形的秘密》文章 · 初始置信度：高
- 2026-07-16 · 修订 · 基于文章#84《意义的诞生地：前颞叶如何将感官碎片组装成概念》· 新增DSI统一计算框架节（Haga 2025，SR≡PMI等价），新增概念空间fMRI证据行（Bokeria 2021），新增连接至semantic-memory-hub和conceptual-space-geometry
- 2026-09-18 · 修订 rev3 · 基于《大脑的时间机器》文章 (#148) · related 新增 successor-representation；connections 新增SR作为认知地图计算形式化的关系说明；key_sources 新增 PMID:28967910、PMID:38849521；source_articles 新增 2026-09-18

## 来源文章

- [[2026-06-22-grid-cells-place-cells]]
- [[2026-07-16-semantic-hub-atl-conceptual-space]]

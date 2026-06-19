---
title: 头向细胞
slug: head-direction-cells
domain: neurons
type: entity
status: established
confidence: high
created: 2026-07-27
updated: 2026-07-27
revision_count: 1
dimensions: [cellular, brain-region, microcircuit, behavior]
related: [grid-cell, place-cell, hippocampal-circuit, entorhinal-cortex, path-integration, border-cells]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: [Q-hd-ring-attractor-location]
source_articles: [2026-07-27-grid-cells-head-direction-spatial-coordinate-system]
key_sources: ["PMID:2303852", "PMID:7823153", "PMID:15965463"]
---

# 头向细胞 (Head Direction Cells)

> **一句话定义**：对动物头部朝向具有选择性放电的神经元，每个细胞只在头部指向特定方向时才高频激活，共同构成大脑内置的"方向罗盘"，为网格细胞和场所细胞提供角度参考框架。

## 当前理解

我们现在认为，头向细胞是空间导航系统中的**方位基准层**。1990 年，Taube、Muller 和 Ranck 在大鼠后下托（postsubiculum）首次记录到它们（PMID: 2303852）。每个头向细胞有一个**首选方向**（preferred direction），当动物头部朝向该方向时放电率最高，偏离后按高斯曲线下降，调谐宽度约 60–120°。

头向细胞的几个关键特性使其成为可靠的角度参考：
- **黑暗中维持**：移除所有视觉地标后，首选方向仍能短期维持（依赖路径积分）
- **地标锚定**：显著视觉地标移动时，首选方向随之旋转——外部信息定期"校准"内部罗盘
- **全局一致性**：同一时刻，整个头向系统中所有细胞的首选方向一致指向同一方向；这在场所细胞中不成立（场所细胞会在不同环境重映射）
- **与速度整合**：头向细胞也接受角速度信号（来自前庭系统），使其能在转头时实时更新

头向细胞分布在多个脑区，形成层次网络，包括后下托（PoS）、丘脑前背侧核（ADN）、外侧乳头体核（LMN）、背侧顶前核（DTN）和后压区（RSC）。

## 关键机制

### 1. 环形吸引子网络（Ring Attractor）

头向系统的生成机制目前被认为是**环形吸引子网络**：想象神经元排列在一个环上，每个神经元代表一个方向（0°–360°）。连接规则是：相近方向的细胞相互兴奋，远方向的细胞相互抑制。

这种连接拓扑使"活跃泡（activity bump）"只能稳定在环上的某个位置，不会随机漂移。当动物头部转动时，前庭/视流输入的**角速度信号**驱动活跃泡沿环旋转，精确追踪头部方向。

### 2. 解剖层次

不同脑区在头向系统中承担不同角色：
- **背侧顶前核（DTN）** / **外侧乳头体核（LMN）**：接收前庭角速度信号，可能是头向信号的原始生成器
- **丘脑前背侧核（ADN）**：ADN 头向细胞可在 PoS 损毁后保持（说明 ADN 是主要节点之一）（PMID: 7823153）
- **后下托（PoS）**：最早发现的头向细胞区域，接受地标视觉信息并锚定首选方向
- **后压区（RSC）**：高层整合，可能将自我中心（egocentric）和环境中心（allocentric）方向参考相互转换

### 3. 与网格细胞的接口

头向细胞为网格细胞的路径积分提供**方位坐标**：网格细胞需要知道"动物在向哪个方向移动"才能正确更新其活跃泡的位置。在 MEC 中，"联合细胞（conjunctive cells）"同时对位置（网格）和方向（头向）敏感，可能是两类系统的整合节点。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 后下托神经元对头部方向选择性放电 | 大鼠自由探索，胞外记录+追踪头部方向 | PMID: 2303852 | 高 |
| ADN 头向细胞在 PoS 损毁后仍维持 | 选择性损伤实验 | PMID: 7823153 | 高 |
| 头向系统在黑暗中维持方向（短期） | 黑暗条件下记录，比较地标移除前后 | PMID: 2303852 | 高 |
| MEC 联合细胞同时编码方向和网格位置 | MEC 多通道记录 | PMID: 15965463 相关 | 高 |

## 连接

- [[grid-cell]] — 头向细胞为网格细胞的路径积分提供角度输入
- [[place-cell]] — 头向系统锚定整个空间坐标系，影响场所场的稳定性
- [[border-cells]] — 边界细胞和头向细胞共同为网格坐标系提供锚点
- [[entorhinal-cortex]] — MEC 含头向细胞和联合细胞，是头向-网格整合的关键节点
- [[path-integration]] — 头向细胞提供路径积分所需的角度维度
- [[hippocampal-circuit]] — 头向信号经 MEC 传入海马，影响情节记忆的空间框架

## 未解问题

- Q-hd-ring-attractor-location：环形吸引子的物理基底在哪里？DTN、LMN、ADN 哪个是主要的"生成器"，哪些是"中继/维持"节点？最新研究（2025）提示脑干两类头向细胞共同生成信号，但层次细节仍不清楚。
- Q-hd-landmark-mechanism：地标如何被编码并锚定头向系统？PoS 和 RSC 各自对此贡献什么？

## 修订历史

- 2026-07-27 · 创建 · 基于《大脑内置的坐标系》文章 #95 · 整合 Taube 1990/1995 和 Moser 2008 综述 · 初始置信度：高

## 来源文章

- [[2026-07-27-grid-cells-head-direction-spatial-coordinate-system]]

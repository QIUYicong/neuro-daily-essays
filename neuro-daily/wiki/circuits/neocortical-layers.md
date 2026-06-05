---
title: 新皮质六层结构
slug: neocortical-layers
domain: circuits
type: structure
status: established
confidence: high
created: 2026-07-23
updated: 2026-07-23
revision_count: 1
dimensions: [cellular, synaptic, microcircuit, brain-region]
related: [cortical-column, canonical-microcircuit, layer-5-pyramidal-cell, thalamocortical-circuit, barrel-cortex, predictive-coding, v1-primary-visual-cortex]
prerequisites: [action-potential, synaptic-transmission, thalamocortical-circuit]
opens_questions: [Q-layers-01, Q-layers-02]
source_articles: [2026-07-23-neocortical-layers-columns-canonical-circuit]
key_sources: ["PMID:31367018", "PMCID:PMC3394394", "PMID:25622573", "PMID:23177956", "PMID:1666655"]
---

# 新皮质六层结构 (Neocortical Laminar Organization)

> **一句话定义**：新皮质（哺乳动物大脑皮层的演化新部分）在所有区域（感觉、运动、关联皮层）都呈现高度保守的六层层状结构，各层由特异性细胞类型、连接模式和输入/输出目标定义，共同构成信息从丘脑输入到皮层下输出的"规范算法"。

## 当前理解

我们现在认为，新皮质的六层不只是发育历史的留存，而是一套精妙的**计算分离架构**：不同层承担前馈编码、本地整合和反馈预测等不同功能角色，并以层特异性的振荡频段（γ vs α/β）来区分前馈误差信号和反馈预测信号（Bastos et al. 2012）。整个哺乳动物新皮质的多样功能，源于对同一份六层蓝图的"量化变奏"而非"质的不同电路逻辑"（Harris & Shepherd 2015）。

关键洞见（Douglas & Martin 1991）：皮层的持续活动**主要由皮层内循环兴奋维持**，而非持续的丘脑输入——丘脑提供约 10–20% 的 L4 突触，其余来自皮层内部。这使皮层成为时刻维持内部动态状态的主动系统，外界感觉信号是对这个系统的更新，而非从零驱动。

## 关键机制

### 六层的细胞-功能身份

| 层 | 主要细胞类型 | 主要输入 | 主要输出 | 功能角色 |
|----|------------|---------|---------|---------|
| L1 | 极少神经元；主要是顶端树突簇和反馈轴突 | 高级皮层反馈 + 皮质调制输入 | — | 反馈/调制接收区 |
| L2/3 | IT 型锥体细胞（约 80% 的皮层兴奋性）| L4 上行 + 跨柱/跨区水平 | 同侧皮层（IT）、对侧（胼胝体）、L5 | 皮层内整合；预测误差前馈（γ）|
| L4 | 棘星形细胞（主要感觉皮层）+ IT 锥体 | 特异性丘脑核团（lemniscal）| L2/3（主）、L5、L6 | 主要感觉输入集散；丘脑信号放大 |
| L5A | IT 型细胞（细簇型锥体）| L2/3、非特异性丘脑（paralemniscal）| 纹状体、对侧皮层（IT）| 皮层-纹状体；皮层-皮层整合 |
| L5B | PT 型细胞（厚簇型锥体）| L2/3、非特异性丘脑（POm 等）| 脑干、脊髓、上丘、基底节 | 皮质下输出"发令" |
| L6 | CT 型细胞（皮层-丘脑）| L5、特异性 + 非特异性丘脑 | 丘脑（TRN + 中继核 CT 反馈）| 丘脑门控调节（功能尚未完全明确）|

### 层间信号流动（规范前馈通道）
```
丘脑（lemniscal pathway）
  ↓
L4（棘星形细胞，初始放大）
  ↓  [单向，EPSP 0.6–1.0 mV，连接率 10–15%]
L2/3（IT 锥体细胞，整合与水平传播）
  ↓  [需多单元时间汇聚，短时易化，EPSP ~0.1 mV]
L5B（PT 锥体细胞，皮质下输出）
  ↓
皮层下靶标（脑干/脊髓/上丘/纹状体）
```

同时：
- L5B 锥体细胞的顶端树突在 L1 接收高级皮层反馈（预测信号）
- L6 CT 细胞向丘脑发出反馈（corticothalamic loop）

### 循环兴奋的核心作用

L4 内：L4-L4 连接率 25–36%，EPSP 约 1.6 mV（最强），形成高度互联的放大网络；丘脑触发 → 皮层内循环维持响应

深浅层之间也有丰富的循环连接（L5→L2/3 的反馈，L6→L4 的反馈），使皮层在没有持续外部输入的情况下也能维持活动状态。

### 预测编码的层分离（Bastos et al. 2012）

| 功能 | 解剖层 | 投射方向 | 主导振荡 |
|------|--------|---------|---------|
| 预测误差（错误信号，前馈）| L2/3 | → 高级区域 L4 | γ（30–80 Hz）|
| 预测（期望信号，反馈）| L5/6 | → 低级区域 L1/L6 | α/β（8–20 Hz）|

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| VPM 只提供 L4 突触的 10–20% | 配对膜片钳定量 | PMCID:PMC3394394 | 高 |
| L4→L2/3 单向，EPSP 0.6–1.0 mV | 配对膜片钳，in vitro | PMCID:PMC3394394 | 高 |
| 皮层持续激活主要由皮层内循环兴奋维持 | 胞内记录 + 刺激对比 | PMID:1666655 | 高 |
| 浅层 γ 高于深层，深层 β 高于浅层 | 灵长类层分辨 LFP | PMID:23177956 | 中（间接测量）|
| 六层结构在哺乳类所有皮层区域保守 | 比较解剖学 + 基因表达 | PMID:25622573 | 高 |

## 连接

- [[cortical-column]] — 六层结构垂直方向形成的功能柱单元
- [[canonical-microcircuit]] — 六层结构中的 L4→L2/3→L5 规范算法实例
- [[layer-5-pyramidal-cell]] — L5 PT 细胞是六层结构中跨层级整合的关键细胞类型
- [[thalamocortical-circuit]] — 丘脑是 L4 的主要（但非主导）外部输入来源
- [[barrel-cortex]] — 桶状皮层是六层结构最精确研究的具体实例
- [[predictive-coding]] — 六层分离是预测编码的解剖实现基础
- [[v1-primary-visual-cortex]] — V1 是六层结构在视觉皮层中的具体实例

## 未解问题

- Q-layers-01（高优先级）：L6 CT 神经元的真实功能是什么？切断它们为何不产生明显的感知缺陷？是否参与"精度加权"（precision weighting）的精细调控？
- Q-layers-02（中优先级）：不同皮层区域（前额叶 vs 感觉皮层）的六层结构在分子水平有哪些系统性差异？这些差异如何对应功能的量化变奏？

## 修订历史

- 2026-07-23 · 创建 · 基于《新皮质六层算法》(#91) · 初始置信度：高

## 来源文章

- [[2026-07-23-neocortical-layers-columns-canonical-circuit]]

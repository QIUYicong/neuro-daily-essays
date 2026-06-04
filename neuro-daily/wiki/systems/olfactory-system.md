---
title: 嗅觉系统
slug: olfactory-system
domain: systems
type: structure
status: established
confidence: high
created: 2026-07-17
updated: 2026-07-17
revision_count: 1
dimensions: [molecular, cellular, microcircuit, brain-region, cognition]
related: [olfactory-receptor-neuron, olfactory-glomerulus, amygdala, hippocampal-circuit, adult-neurogenesis, predictive-coding, memory-consolidation]
prerequisites: [action-potential, synaptic-transmission, ampa-receptor]
opens_questions: [Q-olfact-01, Q-olfact-02, Q-olfact-03]
source_articles: [2026-07-17-olfactory-system-molecular-to-memory]
key_sources: ["PMID:19804753", "PMID:1840504", "PMID:32982699", "PMID:31220213"]
---

# 嗅觉系统 (Olfactory System)

> **一句话定义**：哺乳动物唯一不经过丘脑中转、将化学分子直接转化为边缘系统可访问感知表征的感觉系统，通过"一神经元—一受体"分子专一性、嗅小球轴突汇聚图谱和梨状皮层稀疏符合编码，实现从分子结构到情绪记忆的三层计算。

## 当前理解

我们现在认为，嗅觉系统代表了感觉神经科学中一种独特的架构范式：与视觉、听觉、触觉等所有其他主要感觉不同，嗅觉信号从嗅球出发**不经过丘脑中继**，直接投射到梨状皮层（古皮层）、皮层杏仁核和内嗅皮层，随后进入海马。这一"快捷方式"是理解为什么气味能触发强烈情感和自传性记忆（"Proustian 效应"）的解剖学基础。

系统由三个功能层组成：
- **受体层**：嗅上皮中约 600-1000 万个 ORN，各自表达约 1000 种 OR 中的一种（单受体表达规则）；气味通过"组合编码"激活特定的 OR 子集
- **嗅球层**：同类 OR 的 ORN 轴突汇聚至固定嗅小球（约 5000 ORN/嗅小球，小鼠）；僧帽/簇状细胞整合并放大信号；颗粒细胞侧抑制实现对比增强和增益控制
- **皮层层**：梨状皮层通过"符合探测"（仅当特定多个嗅小球同时激活时才响应）实现稀疏、去相关的气味表征；丰富的联合纤维支持联想记忆

## 关键机制

### 分子转导级联
OR（GPCR）→ Gαolf → 腺苷酸环化酶 III → cAMP↑ → CNG 通道（CNGA2₂/CNGA4/CNGB1b，2:1:1）→ Na⁺/Ca²⁺ 内流 → Ca²⁺ 激活 Anoctamin2（Cl⁻ 外流放大）→ 动作电位；Ca²⁺ 升高→CaM→CNG 通道快速适应

### 嗅小球图谱
同类 OR→固定嗅小球位置（跨个体保守）→小鼠约 2000 个嗅小球/嗅球→"OR 图谱"

### 梨状皮层计算
稀疏编码 + 符合探测 + 联合纤维联想存储 → 气味识别和学习

### 无丘脑中转路径
嗅球→梨状皮层（AP/PP）/ 杏仁核 / 内嗅皮层（→海马）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 哺乳动物 ~250-1200 个功能 OR 基因 | 基因测序 | PMID:1840504 (1991) | 高 |
| 一 ORN 只表达一种 OR | 单细胞原位杂交 | PMID:19804753 | 高 |
| 同类 OR 轴突汇聚至固定嗅小球 | 基因示踪 | PMID:19804753 | 高 |
| 梨状皮层稀疏编码+符合探测 | 体内钙成像+膜片钳 | PMID:19804753 | 中-高 |
| 嗅觉不经丘脑 | 解剖示踪 | 教科书共识 | 高 |
| 梨状皮层可驱动海马齿状回 LTP | 体内电刺激大鼠 | PMID:31220213 | 中 |

## 连接

- [[olfactory-receptor-neuron]] — ORN 分子机制和细胞层
- [[olfactory-glomerulus]] — 嗅球中枢节点
- [[amygdala]] — 气味→皮层杏仁核→情绪记忆直接路径
- [[hippocampal-circuit]] — 通过内嗅皮层间接连接；梨状皮层可直接驱动 DG LTP
- [[adult-neurogenesis]] — ORN 持续再生（嗅上皮）+ OB 颗粒细胞再生（SVZ→OB）
- [[predictive-coding]] — 无丘脑通路与感觉皮层预测编码框架的关系：嗅觉皮层独立实现预测，不依赖 LGN 型丘脑门控
- [[memory-consolidation]] — 气味提示在记忆提取中的特殊作用（Proustian effect）

## 未解问题

- **Q-olfact-01**（高优先级）：OR 排他性表达的表观遗传机制是什么？
- **Q-olfact-02**（中优先级）：梨状皮层是否存在气味的语义/情感拓扑图？
- **Q-olfact-03**（中优先级）：COVID-19 相关嗅觉丧失的神经修复机制？

## 修订历史

- 2026-07-17 · 创建 · 基于《一缕香气的旅行》文章 #85 · 初始置信度：高（基础回路架构教科书级，多项 Nobel-Prize 验证）；梨状皮层-海马直接连接：中（单实验室）

## 来源文章

- [[2026-07-17-olfactory-system-molecular-to-memory]]

---
title: 记忆再巩固
slug: memory-reconsolidation
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-28
updated: 2026-07-28
revision_count: 1
dimensions: [molecular, synaptic, cellular, brain-region, behavior, cognition]
related: [memory-consolidation, engram-cells, ltp, ltd, ampa-receptor, nmda-receptor, fear-conditioning, fear-extinction, dopamine-reward-prediction-error, incubation-of-craving]
prerequisites: [memory-consolidation, ltp, ltd, ampa-receptor, nmda-receptor, engram-cells]
opens_questions: [Q-recon-01, Q-recon-02, Q-recon-03, Q-recon-04]
source_articles: [2026-07-28-memory-reconsolidation]
key_sources: ["PMID:10963596", "PMID:30914678 (PMC6435726)", "PMID:25475090 (PMC4292167)", "PMID:22341662 (PMC3348400)", "PMID:23413355", "PMID:27885549", "PMID:29474957", "PMID:32097575", "PMID:15501585"]
---

# 记忆再巩固 (Memory Reconsolidation)

> **一句话定义**：已经巩固的长期记忆，在被提取后会短暂回到蛋白质合成依赖的不稳定状态（去稳定化），需要重新合成蛋白质才能再次固化（再稳定化）——这一过程仅在出现预测误差时发生，揭示了记忆是动态重构而非静态档案的本质。

## 当前理解

我们现在认为，记忆巩固不是一个"一次性事件"，而是**每次记忆被提取时都可能重新发生**的过程。这一理解来自 Nader、Schafe 和 LeDoux 2000年在 Nature 上发表的里程碑实验（PMID:10963596）：向已巩固的恐惧记忆（1–14天前形成）的外侧杏仁核，在提取后立即注射蛋白质合成抑制剂茴香霉素，记忆几乎完全消失——但在不提取记忆的情况下注射，记忆不受影响。

这意味着已经稳定的记忆，在被激活后会暂时回到与初次巩固类似的脆弱状态，并且需要新的蛋白质合成才能重新固化。这个过程被称为**再巩固**（reconsolidation）。

再巩固的发生有一个关键的计算条件：**预测误差**（prediction error）。Sevenster 等人（2013, PMID:23413355）在人类实验中直接证明，只有当记忆提取时出现与预期不符的信息（预测误差），记忆才会变得不稳定；完全一致的提取不触发再巩固。这与强化学习中用预测误差驱动权重更新的原理高度对应。

再巩固的生物学功能是**在维持记忆稳定性的同时允许记忆根据新信息更新**——这是一种高度精巧的"编辑功能"，使大脑既能保持旧知识又能整合新经验。

## 关键机制

### 去稳定化：记忆的"解锁"过程

去稳定化（destabilization）是指记忆在被提取后主动回到可塑状态的分子过程：

1. **NMDA受体激活**：记忆提取时，谷氨酸释放激活突触后NMDA受体。这是去稳定化的必要条件——NMDA受体拮抗剂阻断提取时，记忆不变得不稳定（Haubrich & Nader, 2018, PMID:27885549）。

2. **GluA2亚基内吞（逆向LTP）**：核心分子事件——含GluA2亚基的AMPA受体从突触膜被内吞（endocytosis），相当于对初始LTP过程的部分逆转。Ferrara等人（2019, PMC6435726）直接测量了提取后15分钟杏仁核GluA2表面表达的下降，并证明阻断GluA2内吞可完全阻止记忆更新。

3. **泛素-蛋白酶体系统（UPS）激活**：突触支架蛋白（Shank、Homer、PSD-95）被泛素标记并降解，"拆除"了维持突触改变的分子脚手架，使突触物理上回到可塑状态。

### 再稳定化：记忆的"重写"过程

再稳定化（restabilization）需要新的蛋白质合成——与初始巩固共享分子逻辑，但不完全相同（Alberini & Kandel, 2015, PMC4292167）：

- **转录激活**：CREB、C/EBPδ（Arguello et al. 2013, PMID:23426691）在提取后被激活
- **Zif268 (EGR-1)**：在再巩固中尤为突出的即刻早期基因转录因子，比在初始巩固中更具标志性
- **IGF-2**：注射可在再巩固窗口期增强记忆持久性（Alberini & Chen, 2012, PMC3348400）

再稳定化的时间窗口约为**6小时**，与初始巩固窗口相似。

### 边界条件：不会触发再巩固的情形

Zhang、Haubrich等人（2018, PMID:29474957）系统整理了边界条件：

| 边界条件 | 可能机制 |
|----------|----------|
| 记忆年龄过久（>30天，小鼠） | GluN2A/GluN2B比值升高（元可塑性，更"保守"的突触） |
| 记忆被多次强化（强记忆） | AMPAR池过大，GluA2内吞难以主导去稳定化 |
| 提取无预测误差 | NMDA受体激活不足，未达去稳定化阈值 |
| 提取时间极短 | 去稳定化级联未达阈值 |

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 提取后蛋白合成抑制→记忆消失（不提取则无效） | 杏仁核茴香霉素注射，提取 vs 不提取对照 | PMID:10963596（Nader 2000 Nature） | 极高 |
| GluA2内吞是去稳定化的分子触发器 | 合成肽段阻断GluA2内吞→阻止记忆更新；GluA2表面表达15min后下降 | PMID:30914678（PMC6435726） | 高 |
| 预测误差是人类再巩固的必要条件 | 普萘洛尔+提取：有预测误差→记忆削弱；无预测误差→无效 | PMID:23413355（Science 2013） | 极高 |
| NE阻断选择性削弱再巩固（不影响初始巩固） | 杏仁核内直接注射普萘洛尔，提取后给药 vs 不提取后给药 | PMID:15501585（Debiec & LeDoux 2004） | 高 |
| IGF-2在再巩固窗口增强记忆 | 海马注射IGF-2后，3周后记忆显著优于对照 | PMID:22341662（PMC3348400） | 高 |
| 再巩固干扰导致真实记忆消除（非提取障碍） | 脑机制长时程记忆（BM-LTM）测量→神经活动降至未训练水平 | PMID:32097575（Haubrich 2020） | 中-高 |
| 普萘洛尔减轻PTSD梦魇（初步临床证据） | 创伤激活+普萘洛尔口服→梦魇严重度评分降低 | PMID:35404227（Mallet 2022） | 中（小样本初步研究） |

## 连接

- [[memory-consolidation]] — 再巩固证明巩固是可以被重复触发的过程，而非一次性事件；再巩固与初始巩固共享分子机制
- [[engram-cells]] — 印迹细胞被再激活时，GluA2内吞和UPS激活使印迹细胞的突触权重暂时回到可修改状态；再巩固是印迹修改的分子窗口
- [[ltp]] — 初始巩固通过LTP机制增强突触；去稳定化本质上是LTP的部分逆转（GluA2内吞）
- [[ltd]] — 去稳定化的GluA2内吞机制与NMDA-LTD和mGluR-LTD中的AMPAR移除机制高度相似
- [[ampa-receptor]] — GluA2亚基内吞是去稳定化的核心分子事件；再稳定化后AMPAR重新插入
- [[nmda-receptor]] — NMDA受体激活是去稳定化的必要起始信号；GluN2A/GluN2B比值决定元可塑性边界
- [[fear-conditioning]] — 恐惧记忆是最常用的再巩固研究范式；杏仁核外侧核是恐惧记忆再巩固的关键脑区
- [[fear-extinction]] — 消退与再巩固是记忆提取后两条不同通路：再巩固修改原始记忆；消退建立新的抑制记忆
- [[dopamine-reward-prediction-error]] — 预测误差在再巩固中的驱动角色，与DA-RPE在强化学习中的权重更新角色计算上高度平行
- [[incubation-of-craving]] — 成瘾相关的NAc AMPAR动态（CP-AMPA插入）与再巩固的GluA2内吞机制相关联；再巩固干预是潜在的戒断辅助治疗靶点

## 未解问题

- Q-recon-01（高优先级）：能否开发出特异性靶向单一记忆的再巩固干预手段？现有临床方法不可避免地激活相关记忆网络。
- Q-recon-02（高优先级）：再巩固与消退是否共享底层分子机制（Bonin & De Koninck 2015提出的统一假说）？在哪个分子节点分叉？
- Q-recon-03（中优先级）：强记忆/老记忆的边界条件中，元可塑性（GluN2A/B比值）是否是唯一决定因素，还是存在其他平行机制？
- Q-recon-04（中优先级）：人类成年大脑的再巩固分子机制（特别是GluA2内吞和UPS激活）是否与啮齿类完全相同？缺乏直接人类突触层面证据。

## 修订历史

- 2026-07-28 · 创建 · 基于《记忆的活书稿》文章（#96）· 初始置信度：高

## 来源文章

- [[2026-07-28-memory-reconsolidation]]

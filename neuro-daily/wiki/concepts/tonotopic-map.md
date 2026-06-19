---
title: 音调拓扑图（Tonotopy）
slug: tonotopic-map
domain: concepts
type: concept
status: established
confidence: high
created: 2026-07-28
updated: 2026-07-28
revision_count: 1
dimensions: [cellular, brain-region, whole-brain-network]
related: [cochlea, auditory-cortex, orientation-selectivity, grid-cell, place-cell]
prerequisites: [cochlea]
opens_questions: [Q-ac-01, Q-ac-03]
source_articles: [2026-07-28-auditory-cortex-tonotopy]
key_sources: ["PMID:19471271", "PMID:27145914", "PMID:23916753", "PMID:11427697"]
---

# 音调拓扑图 (Tonotopic Map)

> **一句话定义**：音调拓扑图是听觉皮层（以及脑干、丘脑各听觉中继站）中声音频率按有序空间梯度排列的功能地图——低频神经元和高频神经元在皮层上系统性地相邻排列，保真地复现了耳蜗基底膜的频率-位置对应关系（地点编码）。

## 当前理解

音调拓扑图（tonotopy，来自希腊语 tono- = 音调，-topy = 位置）是听觉神经系统中"频率→空间"信息保真传递的组织原则，贯穿从耳蜗到皮层的全部听觉中继站。

**物理起点（cochleotopy）**：耳蜗基底膜的弹性渐变产生行波，使每个声音频率在 BM 上有精确的最大振幅位置——这是地点编码（place coding）的物理实现（Robles & Ruggero 2001，PMID:11427697）。

**沿升序通路的保真传递**：
1. 耳蜗（CF-位置地图）→ 听觉神经束（CF-纤维束排列）
2. → 蜗神经核（CN）→ 上橄榄复合体（SOC）→ 下丘（IC）→ 内侧膝状体腹侧（MGBv）
3. → 初级听觉皮层 A1（高频后部，低频前部）+ 吻侧核心区 R（镜像排列）

**人类听觉皮层的 11 张场图**（Brewer & Barton 2016，PMID:27145914）：
- 音调梯度（tonotopy）× 周期性梯度（periodotopy，对时间调制速率的偏好）两个正交轴，共同组织 11 张独立的听觉场图
- A1 和 R 在 Heschl 回上呈 V 形镜像排列（Saenz & Langers 2014，PMID:23916753），对应耳蜗的基部（高频）和顶部（低频）

**拓扑地图作为皮层计算的通用策略**：
- 视觉皮层：视网膜拓扑图（retinotopy），V1 精确复现视网膜位置信息
- 听觉皮层：音调拓扑图（tonotopy），A1 精确复现耳蜗频率信息
- 体感皮层：躯体拓扑图（somatotopy），S1 精确复现身体表面位置
- 海马内嗅皮层：空间地图（网格细胞/场所细胞），编码环境的空间结构

这些地图的共同之处：**空间保持**——输入空间中相似的信息在皮层上空间相邻，使短程侧向抑制可以实现精确的特征对比分离（类比视觉 V1 方向柱之间的水平抑制增强方向选择性）。

## 关键机制

**皮层柱状组织**：沿音调梯度方向相邻的皮层柱偏好相邻频率；同一位置的皮层柱沿深度方向偏好相同频率（如视觉皮层方向柱）

**侧向抑制**：相邻频率的皮层柱之间存在 SST+/PV+ 抑制性中间神经元介导的侧向抑制，增强频率对比度——这与视觉皮层中侧向抑制增强方向和空间频率对比的机制类似

**学习可塑性**：成年动物的音调图在重复训练特定频率后可重组（Merzenich 组，1980–90 年代）——揭示拓扑图不只是固定感觉接收器，而是随经验动态维护的"工作地图"

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 猫A1音调图（高频后/低频前） | 多电极记录 | Merzenich & Brugge 1973 | 高 |
| 人类A1 fMRI音调梯度（V形排列） | 7T fMRI | PMID:23916753 | 中-高 |
| 人类听觉皮层11张场图 | 高分辨率fMRI系统综述 | PMID:27145914 | 中（精确数量有争议） |
| 训练后A1频率调谐可塑性重组 | 经典条件反射+多电极记录（猫、大鼠） | Merzenich组多篇（1983-1993） | 高 |

## 连接

- [[cochlea]] — 耳蜗 cochleotopic map 是 tonotopic-map 的物理起点（prerequisite-for）
- [[auditory-cortex]] — A1/R 是 tonotopic-map 在皮层的主要实现位置（part-of）
- [[orientation-selectivity]] — V1 方向选择性地图（orientation map）是感觉皮层拓扑组织的另一个实例（related，同类原则）
- [[grid-cell]] — 网格细胞认知地图是海马-内嗅系统对环境空间的拓扑编码（related，同类原则，不同实现）
- [[place-cell]] — 场所细胞的"场所场"可视为单个位置的"拓扑基元"（related）

## 未解问题

- Q-ac-01：成人 A1 拓扑图是固定感觉分析器还是随学习经验重组的动态地图？
- Q-ac-03：11 张场图的精确数量和边界是否受个体语言/音乐经历影响？

## 修订历史

- 2026-07-28 · 创建 · 基于《从蜗旋到皮层音图》（#96）· 初始置信度：高

## 来源文章

- [[2026-07-28-auditory-cortex-tonotopy]]

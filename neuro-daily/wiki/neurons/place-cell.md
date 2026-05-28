---
title: 场所细胞
slug: place-cell
domain: neurons
type: entity
status: established
confidence: high
created: 2026-05-28
updated: 2026-05-29
revision_count: 2
dimensions: [cellular, brain-region, cognition, behavior]
related: [hippocampal-circuit, btsp, grid-cell, dendritic-computation, ltp, hebbian-learning, engram-cells, theta-oscillations, memory-consolidation, sharp-wave-ripple]
prerequisites: [dendritic-computation, ltp, hippocampal-circuit]
opens_questions: [Q-place-field-content, Q-place-field-btsp-universality, Q-remapping-trigger]
source_articles: [2026-05-28-place-cells-btsp, 2026-05-29-memory-consolidation-swr]
key_sources: ["PMID:26167906", "PMID:28883072", "PMID:18284371", "PMID:32042144", "PMID:26135716"]
---

# 场所细胞 (Place Cell)

> **一句话定义**：海马（主要是 CA1 和 CA3）中的锥体神经元子集，当动物处于环境中特定空间位置时才高频放电，其集体活动构成动物当前位置的内部表征——即认知地图。

## 当前理解

我们现在认为，场所细胞是大脑空间导航和空间记忆的核心神经基础。每个场所细胞都有自己的**场所场**（place field）：一个椭圆形的空间区域（通常占环境面积的 10–30%），动物进入该区域时细胞放电，离开则沉寂。

场所细胞最重要的特性之一是**单次写入**：通过**行为时间尺度突触可塑性（BTSP）**，一次树突钙平台电位就能建立稳定的场所场，无需反复访问。这使空间记忆的形成速度远超经典 STDP 理论的预测。

多个场所细胞的集体活动模式（而非单个细胞）编码空间位置——这是一种**群体码**。同一位置由数十个不同细胞"投票"确认，既赋予了编码稳健性，也使重映射成为可能：在不同环境中，同一细胞群重新组合，产生全新的地图表征。

## 关键机制

### 1. 场所场形成的 BTSP 机制

场所场形成由**树突钙平台电位**触发（Bittner et al., 2015, PMID:26167906）：

1. 动物到达新位置时，内嗅皮层（EC3）和 CA3 联合输入共同驱动 CA1 锥体神经元的树突
2. 两路输入在恰当时序下（θ 振荡特定相位）触发**钙平台电位**（L 型 Cav1.2/1.3 通道介导，持续 100–500 ms）
3. 平台电位触发**BTSP**：向前后各约 3–4 秒窗口内的突触输入被增强
4. 增强的突触对应动物在该位置前后数秒内收到的空间输入组合
5. 结果：该细胞在"刚才所在的地方"到"刚才所在地方"之间的一段空间形成稳定场所场

**关键数字**：
- 膜电位斜坡向后延伸约 3.8 秒（Bittner 2017, PMID:28883072）
- 场所场在单次平台电位后稳定维持平均 39 圈（约 19 分钟）（Bittner 2015）
- BTSP 诱导需要 NMDA 受体（~84% 依赖）和 L 型钙通道（~73% 依赖）

### 2. 群体编码与地图特性

- **位置分辨率**：通过群体解码可达数厘米精度
- **稳定性**：熟悉环境中场所场可稳定数周至数月
- **重映射（remapping）**：进入不同环境后，大多数场所细胞重新选择场所场位置（全局重映射）；有时仅改变放电频率而不改变位置（速率重映射）
- **序列编码**：场所细胞在动物移动时按顺序激活（place cell sequence），可能是事件序列的时间编码基础

### 3. 输入来源

CA1 场所细胞整合两路主要输入：
- **CA3 Schaffer collaterals**：提供模式完整的空间表征（pattern completion）
- **EC3 直接输入（穿孔通路远端支）**：提供内嗅皮层的空间编码信息（包括网格细胞输入）

两路输入在树突的不同区域整合（CA3 → 近端树突；EC3 → 远端树突），BTSP 由两路联合触发产生。

### 4. 睡眠期的序列重放（Replay via SWR）

场所细胞在睡眠中会**重放**白天的空间序列——这一重放发生在**尖波涟漪（SWR）**期间，速度约为行为时的 **~20 倍**（PMID:26135716）。

**重放的细节**（PMID:30356103）：
- 正向重放：保留原始方向，与导航预测和规划相关
- 反向重放：逆向，与奖励强化相关（频率随奖励大小增加）
- 前瞻重放：重放从未经过的路径，可能服务于未来规划

**场所细胞序列是 SWR 的"内容"**：SWR 之所以能携带有意义的记忆信号，正是因为场所细胞在 θ 振荡中建立了时序关联——SWR 在睡眠中以压缩形式回放这些关联，向皮层"广播"记忆。

这一重放是**海马→皮层系统巩固的关键步骤**（见 [[memory-consolidation]]）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| CA1 神经元有位置特异性放电（场所场） | 大鼠自由探索，单单元胞外记录 | O'Keefe & Dostrovsky 1971（引用于 PMID:18284371） | 高 |
| 钙平台电位单次触发场所场 | 清醒小鼠 CA1 胞内记录，人工诱导平台电位 | PMID:26167906 (PMC4888374) | 高 |
| BTSP 时间窗口约 ±3–4 秒 | 脑片 + 在体胞内记录，药理学验证 | PMID:28883072 (PMC7289271) | 高 |
| CA3 BTSP 发生在循环突触，时间窗口对称 | 清醒小鼠 CA3 胞内记录 + 光遗传 | PMID:39454575 | 高（读摘要）|
| 场所场的多样性钙动态（部分不符合 BTSP） | 大群体 CA1 钙成像 | PMID:41025505 | 中（提示多路径）|

## 连接

- [[hippocampal-circuit]] — 场所细胞位于 CA1，是三突触回路的输出节点
- [[btsp]] — 场所场形成的核心突触机制
- [[grid-cell]] — 内嗅皮层网格细胞为场所细胞提供类坐标输入框架
- [[dendritic-computation]] — 树突钙平台电位是场所场写入的细胞机制
- [[ltp]] — BTSP 与 LTP 并列为两种独立的突触增强机制；场所场由 BTSP 主导
- [[engram-cells]] — 场所细胞是空间情景记忆的印迹细胞候选
- [[theta-oscillations]] — θ 振荡调控平台电位的触发时机（θ 相位依赖性）
- [[memory-consolidation]] — 场所细胞序列通过 SWR 重放完成系统巩固
- [[sharp-wave-ripple]] — SWR 是场所细胞序列重放的电生理执行者

## 未解问题

- Q-place-field-content：场所细胞编码的是纯粹的欧几里得空间坐标，还是包含了情境、情绪、任务状态的联合编码？
- Q-place-field-btsp-universality：BTSP 是所有场所场形成的机制，还是只是其中一条路径（Sumegi 2025 提示多路径）？
- Q-remapping-trigger：什么触发了全局重映射（新环境）vs. 速率重映射（相似环境）的不同类型？

## 修订历史

- 2026-05-28 · 创建 · 填补悬空引用（由 [[树突计算]] 页引用）· 基于《场所细胞》文章 · 初始置信度：高
- 2026-05-29 · 修订 · 基于《海马的夜间档案馆》文章 · 展开睡眠重放一节（SWR 重放的详细机制）· 新增 memory-consolidation 和 sharp-wave-ripple 的连接

## 来源文章

- [[2026-05-28-place-cells-btsp]]
- [[2026-05-29-memory-consolidation-swr]]

---
title: 海马回路
slug: hippocampal-circuit
domain: neurons
type: structure
status: established
confidence: high
created: 2026-05-28
updated: 2026-06-01
revision_count: 4
dimensions: [brain-region, microcircuit, cognition]
related: [place-cell, grid-cell, dendritic-computation, ltp, hebbian-learning, btsp, engram-cells, theta-oscillations, memory-consolidation]
prerequisites: [synaptic-transmission, ltp, action-potential]
opens_questions: [Q-ca2-function, Q-hippocampal-consolidation-mechanism]
source_articles: [2026-05-28-place-cells-btsp, 2026-05-31-engram-cells-optogenetic-proof]
key_sources: ["PMID:32042144", "PMID:18007020", "PMID:18284371", "PMID:39454575", "PMID:26135716", "PMID:23354386", "PMID:40047245", "PMID:19749750"]
---

# 海马回路 (Hippocampal Circuit)

> **一句话定义**：海马由齿状回（DG）、CA3、CA1（及下托）四个亚区串行连接构成三突触回路，并行接受内嗅皮层（EC）输入，共同实现空间记忆的编码、模式分离、模式补全和输出。

## 当前理解

我们现在认为，海马回路并非简单的串行管道，而是一个**多路并行、功能分工**的网络。经典的"三突触回路"（EC→DG→CA3→CA1）是主要路径之一，但内嗅皮层还通过穿孔通路直接与 CA1 和 CA3 相连（bypass path），使不同类型的记忆可以通过不同路径编码。

各亚区的核心计算功能：
- **DG（齿状回）**：模式分离——将相似输入变成不相似表征，防止记忆混淆
- **CA3**：模式补全——通过循环连接，用部分线索激活完整表征
- **CA1**：整合与输出——综合 CA3 和 EC3 两路信息，是场所细胞密度最高的区域

海马是情景记忆（episodic memory）的核心结构，损伤（如 H.M. 案例）导致无法形成新的情景记忆，但远期记忆和技能记忆相对保留。

## 关键机制

### 1. 信息流入：内嗅皮层的两路输入

**内嗅皮层（EC）**是皮层与海马之间的枢纽，提供两类输入：
- **内侧内嗅皮层（MEC）**：空间信息（网格细胞、头向细胞、边界细胞）→ 空间坐标框架
- **外侧内嗅皮层（LEC）**：物体和非空间信息 → 事件"内容"

输入路径：
- **穿孔通路（perforant path, PP）**：EC→DG（主要）、EC→CA3（侧支）、EC3→CA1（远端树突）

### 2. 齿状回（DG）：模式分离

**粒细胞（granule cells）**：
- 活动极稀疏：每次环境探索中仅 <5% 的细胞激活
- 每个细胞有单一、长期稳定的场所场
- 通过**苔状纤维（mossy fiber）**投射到 CA3

**模式分离机制**：
- 大量颗粒细胞（啮齿类约 100 万）接受少量内嗅皮层神经元输入 → 投影展开（expansion recoding）
- 颗粒细胞间强抑制（篮细胞、苔状细胞介导）→ 竞争稀疏化
- 结果：相似输入 → 不相似 DG 输出 → 防止 CA3 中记忆干扰

### 3. CA3：模式补全与联想记忆

CA3 的独特结构是大量的**循环连接（recurrent collaterals）**：CA3 锥体细胞约有 12,000 个同类细胞的兴奋性突触输入（来自其他 CA3 细胞），与来自 DG 的约 50 个苔状纤维突触相比数量悬殊。

**模式补全**：当部分线索激活 CA3 的一小部分，循环连接可逐步激活代表完整记忆的整个 CA3 集群（类似 Hopfield 网络的吸引子动力学）。

**CA3 的 BTSP**（Li et al., 2024, PMID:39454575）：
- 发生在循环突触（而非苔状纤维）
- 时间窗口对称（vs CA1 的不对称）
- 依赖内嗅皮层更新；DG 输入不是必须的

### 4. CA1：整合与输出

**CA1 是三突触回路的终点**，整合两路主要输入：
- **近端树突**：CA3 Schaffer collaterals（模式完整的联想信息）
- **远端树突**：EC3 直接输入（穿孔通路远端支，空间坐标信息）

CA1 的场所细胞通过 BTSP 在单次穿越中建立场所场，时间窗口不对称（向后偏移），产生预测性斜坡电位（ramp membrane potential）。

CA1 输出到**下托（Subiculum）**，再到内嗅皮层（EC）、前额叶和杏仁核等皮层结构。

### 5. 海马的两种工作模式：θ态与SWR态

海马在不同行为状态下运行截然不同的工作模式，两者在时间上几乎互斥：

**θ态（在线/编码模式）**：
- 出现于主动探索、运动和REM睡眠时
- 局部场电位呈4–12 Hz θ振荡
- 场所细胞以相位前进（phase precession）方式放电，实现空间位置的双重编码（速率+相位）
- 每个θ周期内，多个场所细胞形成时间序列（θ sequences），将行为尺度路径压缩约20倍
- BTSP等突触可塑性依赖于θ振荡协调的时机，实现快速记忆写入

**SWR态（离线/固化模式）**：
- 出现于静止、非REM睡眠和进食/梳洗等消耗性行为时
- CA3循环兴奋自发爆发，通过Schaffer侧支驱动CA1产生110–200 Hz涟漪
- 白天的场所细胞序列以~20倍速度高速重播
- 重播内容包括前向、反向，甚至新颖路径（规划/想象？）
- 选择性SWR中断损害次日空间记忆（因果证据）
- 被认为是海马→新皮层记忆巩固的物理载体

**两种模式的切换机制**：
- 胆碱能（ACh）张力是关键开关：ACh高→θ态；ACh低→SWR自发爆发
- MS-DBB驱动θ时，同时抑制CA3的循环兴奋；θ消失时，循环兴奋解放

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| DG 粒细胞活动稀疏（<5%）| 钙成像，体内探索实验 | PMID:32042144 综述 | 高 |
| CA3 循环回路支持模式补全 | 选择性 CA3 损伤损害线索完整记忆提取 | PMID:18007020 | 中-高 |
| CA1 整合 CA3 + EC3 两路输入 | 分层记录 + 光遗传阻断 | PMID:32042144 综述 | 高 |
| 海马损伤导致顺行性遗忘 | H.M. 案例等神经心理学经典 | 引用于 PMID:18284371 | 高 |
| CA3 BTSP 在循环突触上，依赖内嗅皮层 | 清醒小鼠胞内 + 光遗传 | PMID:39454575 | 高（读摘要）|

## 连接

- [[place-cell]] — CA1 场所细胞是海马回路的主要输出表征
- [[btsp]] — BTSP 是 CA1（和 CA3）场所场写入的突触机制
- [[grid-cell]] — 内嗅皮层网格细胞通过穿孔通路输入到 DG/CA3/CA1
- [[ltp]] — CA3 循环突触和 CA1 Schaffer 突触的 LTP 是长期记忆的突触基础
- [[dendritic-computation]] — CA1 锥体细胞的树突计算（平台电位）是 BTSP 的物理基础
- [[memory-consolidation]] — 海马 SWR 重放是海马→皮层记忆巩固的机制
- [[theta-oscillations]] — θ 振荡（4–12 Hz）协调海马回路的编码节律，调控 BTSP 触发时机
- [[engram-cells]] — DG 是印迹细胞的主要居所；DG→CA3→CA1→BLA 的印迹间优先连接链利用三突触回路结构

## 未解问题

- Q-ca2-function：CA2 亚区（在 CA3 和 CA1 之间）在记忆编码中的具体角色？与社会记忆相关？
- Q-hippocampal-consolidation-mechanism：海马→皮层的记忆巩固是如何精确调控的？SWR 重放选择哪些序列？
- Q-shr-content-selection：决定哪些 SWR 重播内容被"选中"的完整机制（多巴胺标记之外）？
- Q-human-swr-consolidation：人类 SWR 因果证据如何在伦理约束下获得？

## 修订历史

- 2026-05-28 · 创建 · 基于《场所细胞》文章 · 整合 Hainmueller & Bartos 2020 和 Li 2024 的信息 · 初始置信度：高
- 2026-05-29 · 修订 · 基于《θ振荡与相位编码》文章 · 新增"海马两种工作模式"（θ态/SWR态）章节；新增 SWR 生成和重播机制；新增 key_sources
- 2026-05-31 · 修订 · 基于《印迹细胞》文章 · 新增：DG 是印迹细胞分配竞争的主要场所（2–4% 稀疏活动→高正交性）；DG→CA3→CA1→BLA 印迹间优先连接链的描述；连接增加 [[engram-cells]]
- 2026-06-01 · 修订 · 基于《记忆固化的夜间工厂》文章 · 新增未解问题（Q-shr-content-selection、Q-human-swr-consolidation）；补充 key_sources（Basha 2025 丘脑汇聚核、Girardeau 2009 SWR 因果）；海马巩固机制现有独立 memory-consolidation 页面详细展开

## 来源文章

- [[2026-05-28-place-cells-btsp]]
- [[2026-05-29-theta-oscillations-phase-coding]]
- [[2026-05-31-engram-cells-optogenetic-proof]]

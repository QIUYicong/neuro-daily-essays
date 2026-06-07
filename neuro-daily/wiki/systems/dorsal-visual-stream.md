---
title: 背侧视觉流
slug: dorsal-visual-stream
domain: systems
type: mechanism
status: established
confidence: high
created: 2026-08-17
updated: 2026-08-17
revision_count: 1
dimensions: [brain-region, whole-brain-network, systems, cognition, behavior]
related: [v1-primary-visual-cortex, area-MT-V5, mst-medial-superior-temporal, lip-lateral-intraparietal, inferior-temporal-cortex, v4-visual-area, ocular-dominance-columns, thalamocortical-axons, invariant-object-recognition]
prerequisites: [v1-primary-visual-cortex, action-potential]
opens_questions: [Q-dorsal-01, Q-dorsal-02, Q-dorsal-03]
source_articles: [2026-08-17-dorsal-visual-stream-MT-V5-motion-space]
key_sources: ["PMID:1374953", "PMID:1607944", "PMID:3385495", "PMID:11600651", "PMID:17600525", "PMID:28196647"]
---

# 背侧视觉流 (Dorsal Visual Stream)

> **一句话定义**：背侧视觉流（V1→MT/V5→MST→LIP/顶叶）是视觉皮层两条主要计算通路中专门处理运动、空间与行动导向信息的通路，依次完成运动方向提取（MT）、光流/自身运动感知（MST）、证据积累与决策（LIP），支撑"如何行动"而非"这是什么"的功能。

## 当前理解

我们现在认为，背侧视觉流不是一条单一的"where pathway"（Mishkin & Ungerleider 1982 的早期描述），而是一个**专门支持在线视觉引导动作（online visuomotor control）**的神经计算系统（Goodale & Milner 1992，PMID: 1374953）。

其核心特点：
1. **分工"how"而非"where"**：背侧流不主要建立物体的意识化空间地图，而是实时计算"如何运动身体来与物体交互"。
2. **三级计算层级**：从 MT 提取局部运动方向 → MST 整合光流提取自身运动 → LIP 积累感觉证据触发决策。
3. **双子通路结构**：背外侧子流（MT→MST→VIP，运动分析）+ 背内侧子流（V6→V6A→MIP，空间位置持续监控）（Galletti & Fattori 2018，PMID: 28196647）。
4. **动态网络而非固定层级**：两条子通路的相对贡献随任务上下文动态变化，与腹侧流之间也有广泛的交互连接。

## 关键机制

### 层级架构

| 区域 | 核心计算 | 输入 | 输出 |
|------|---------|------|------|
| V1（方向选择） | 局部边缘方向 | LGN | V2, MT, V4 |
| MT/V5 | 运动方向+速度提取，解决光圈问题 | V1/V2/V3 + LGN 旁路 | MST, LIP, 丘脑 |
| MST（背侧亚区 MSTd） | 光流解析，自身运动/航向 | MT | VIP, LIP, 前庭皮层 |
| LIP | 证据时间积累，决策触发 | MT, MST, FEF, PFC | SC, FEF（眼跳） |

### 腹侧流 vs 背侧流对比

| 维度 | 腹侧流 | 背侧流 |
|------|--------|--------|
| 终点 | IT 皮层 | 顶叶（LIP/VIP/MIP） |
| 核心问题 | "这是什么？" | "如何行动？" |
| 时间尺度 | 较慢（意识识别） | 较快（实时动作控制） |
| 意识接入 | 高（支持有意识识别） | 低（多为无意识控制） |
| 关键病变 | 视觉失认症（IT） | 运动失认症（MT）、空间忽视（顶叶） |

### 临床双分离证据

- **患者 D.F.**（腹侧损伤）：无法识别物体形状，但能准确完成视觉引导抓握（背侧完整）→ 支持 Goodale-Milner 框架。
- **患者 L.M.**（MT/V5 损伤）：无法感知运动，世界如连续静止帧 → 支持 MT 对运动感知的必要性（Zihl et al. 1983）。
- **空间忽视**（顶叶/右侧 LIP 区域损伤）：忽视对侧空间，不能响应对侧空间的视觉-运动信号 → 支持顶叶在空间行动中的作用。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 背侧流专门化为行动导向（非纯粹"where"） | D.F. 患者双分离：视觉失认 + 完整抓握 | PMID: 1374953 | 高 |
| MT 因果参与运动感知（病变） | 猕猴 MT 化学损毁→方向判别阈值升高 | PMID: 3385495 | 高 |
| MT 因果参与运动感知（微电刺激） | 微刺激 MT 方向柱 → 感知偏移 | PMID: 1607944 | 高 |
| LIP 实现证据积累式决策 | LIP 斜坡活动与漂移扩散模型一致 | PMID: 11600651 | 中-高 |
| 背侧流包含两条子通路 | 解剖+功能研究综述 | PMID: 28196647 | 中-高 |

## 连接

- [[v1-primary-visual-cortex]] — V1 方向选择性为 MT 提供运动输入
- [[area-MT-V5]] — 背侧流的第一个专业化运动节点
- [[mst-medial-superior-temporal]] — 光流解析，自身运动感知
- [[lip-lateral-intraparietal]] — 证据积累与感知决策
- [[inferior-temporal-cortex]] — 腹侧流的对应终点（"what" vs "how"）
- [[v4-visual-area]] — 腹侧流中 V1→V4 的颜色/形状处理（对比）
- [[ocular-dominance-columns]] — V1 竞争性组织 → 为 MT 提供输入基础

## 未解问题

- Q-dorsal-01：MSTd 的前庭-视觉整合具体机制？信号冲突时如何权重裁决？
- Q-dorsal-02：LIP 斜坡活动是细胞内积分还是循环回路积分？
- Q-dorsal-03：两条背侧子通路（背外侧 vs 背内侧）如何协调工作？

## 修订历史

- 2026-08-17 · 创建 · 基于《大脑的运动侦探：背侧视觉流如何从光影变化中提取运动方向、空间坐标与行动决策》· 初始置信度：高

## 来源文章

- [[2026-08-17-dorsal-visual-stream-MT-V5-motion-space]]

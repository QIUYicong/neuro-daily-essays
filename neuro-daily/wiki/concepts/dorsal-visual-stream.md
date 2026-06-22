---
title: 背侧视觉流
slug: dorsal-visual-stream
domain: concepts
type: concept
status: established
confidence: high
created: 2026-08-30
updated: 2026-08-30
revision_count: 1
dimensions: [brain-region, systems, behavior]
related: [ventral-visual-stream, posterior-parietal-cortex, mt-v5-motion-area, v1-primary-visual-cortex, motor-cortex, dorsal-attention-network]
prerequisites: [v1-primary-visual-cortex, action-potential]
opens_questions: [Q-dorsal-01]
source_articles: [2026-08-30-dorsal-visual-stream-parietal-action]
key_sources: ["PMID:1374953", "PMID:12955383", "PMID:38820554", "PMCID:PMC11602008"]
---

# 背侧视觉流 (Dorsal Visual Stream)

> **一句话定义**：背侧视觉流（"how pathway"）从 V1 出发，经 MT/V5 提取运动信息，汇入后顶叶皮层（IPS 各区），再通过顶叶-前运动皮层投射驱动视觉引导的行动；其核心是以自我为中心的坐标系处理，为行动而非感知服务。

## 当前理解

我们现在认为背侧视觉流的核心功能是**行动视觉**（vision-for-action）——它把视觉信息转化为在以自我为中心的坐标系中可被运动系统调用的空间参数。这一理解是对 Ungerleider-Mishkin（1982）最初"where pathway"框架的重要修正：背侧流的关键不只是定位物体，而是实时计算"如何行动于此物体"。

经典的双流框架（Goodale & Milner 1992，PMID: 1374953）提出：
- **腹侧流（ventral / what pathway）**：物体识别，用异我中心表征，服务于感知
- **背侧流（dorsal / how pathway）**：行动引导，用自我中心表征，服务于行动

两流的分离在神经心理学案例中得到双离解证据：视觉失认症患者 D.F. 腹侧流损伤但抓握完整；光学性共济失调患者顶叶损伤但物体识别正常。

最新综述（Ritchie et al. 2024，PMC11602008）将"视觉流"提升为分类学概念，指出流内有多条并行的功能性通路，两流之间有广泛的跨流连接，实际视觉皮层是 branching heterarchy 而非封闭平行管道——双流框架在功能分类层面仍然有效，但不应被过度简化为物理隔离的两条管道。

## 关键机制

### 解剖路径

```
V1 (M 细胞输入)
 → V2 厚条纹 / V3
 → MT/V5 (运动方向和深度)
 → MST (光流/自我运动)
 → 后顶叶皮层 IPS (LIP / AIP / VIP / MIP)
     ↓背背侧: SPL → PMd (背侧前运动皮层) → M1 (到达)
     ↓腹背侧: IPL → PMv (腹侧前运动皮层) → M1 (抓握/工具)
```

### 坐标转换（核心计算）

大脑需要把视网膜坐标（retinal）→ 头部坐标（head-centered）→ 身体坐标（body-centered）→ 手部坐标（hand-centered），这一系列变换在后顶叶皮层的不同分区中分步完成，是背侧流最基本的计算工作。

### 双路细分（Rizzolatti & Matelli 2003，PMID: 12955383）
- **背背侧流**（dorsodorsal）：SPL → PMd → M1，控制到达（reaching）
- **腹背侧流**（ventrodorsal）：IPL → PMv → M1，控制抓握与工具使用

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 感知与行动的双离解 | D.F. 案例（视觉失认但抓握正常）+ 光学性共济失调（感知正常但抓握偏差） | PMID: 1374953 | 高 |
| 背侧流用自我中心坐标 | fMRI + 行为 + 损伤研究 | PMID: 24634664 | 高 |
| 双流有广泛跨流连接 | 解剖示踪 + 功能 fMRI 相关性分析 | PMC11602008 | 中-高 |

## 连接

- [[ventral-visual-stream]] — 互补的两条视觉流，腹侧处理身份/感知，背侧处理位置/行动
- [[posterior-parietal-cortex]] — 背侧流的核心处理节点
- [[mt-v5-motion-area]] — 背侧流的关键中间站，专职运动信息提取
- [[v1-primary-visual-cortex]] — 背侧流起点，接收 M 细胞（magnocellular）快速输入
- [[motor-cortex]] — 背侧流的最终输出接受端
- [[dorsal-attention-network]] — 共享 IPS 节点，自上而下调控注意-行动的连接

## 未解问题

- Q-dorsal-01（中优先级）：背侧流的计算是否完全无意识？光学性共济失调表明行动视觉不依赖意识感知，但 LIP 携带显著性/注意信号暗示存在意识调节通道。行动视觉与意识感知的精确接口在哪里？

## 修订历史

- 2026-08-30 · 创建 · 基于《视觉的另一半：背侧流如何把世界变成动作》· 初始置信度：高

## 来源文章

- [[2026-08-30-dorsal-visual-stream-parietal-action]]

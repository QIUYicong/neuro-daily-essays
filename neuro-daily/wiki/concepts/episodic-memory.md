---
title: 情节记忆
slug: episodic-memory
domain: concepts
type: concept
status: established
confidence: high
created: 2026-07-26
updated: 2026-07-26
revision_count: 1
dimensions: [cellular, brain-region, whole-brain-network, cognition, behavior]
related: [time-cells, place-cells, hippocampal-circuit, memory-consolidation, sharp-wave-ripples, cognitive-map, engram-cells, default-mode-network, rem-sleep, pattern-completion]
prerequisites: [hippocampal-circuit, memory-consolidation, place-cells]
opens_questions: [Q-timecell-human-task]
source_articles: [2026-07-26-hippocampal-time-cells-temporal-coding]
key_sources: ["PMID:25269553", "PMID:21867888", "PMID:39322671", "PMID:23318095"]
---

# 情节记忆 (Episodic Memory)

> **一句话定义**：由"谁/什么 + 哪里 + 几时"三维时空坐标整合而成的自传式事件记忆，依赖海马-内嗅皮层回路的时空支架（spatiotemporal scaffold），是能被有意识"心理时间旅行"访问的个人经历记录。

## 当前理解

我们现在认为，情节记忆是三个维度的整合：

1. **内容维度（What）**：事件本身的感觉、语义内容——由颞叶联合区（IT 皮层）、嗅周皮层编码
2. **空间维度（Where）**：事件发生的场景——由场所细胞、网格细胞构建的空间认知地图提供
3. **时间维度（When）**：事件在时间流中的位置——由**时间细胞**（time cells）和时间漂变上下文信号提供

海马的核心角色不是"储存"这三个维度的内容，而是作为**时空绑定器（spatiotemporal binder）**：DG（模式分离）+ CA3（模式补全/吸引子）+ CA1（输出整合）的三突触回路将空间、时间和内容信息绑定为一个完整的"情节帧"（episodic frame），并通过内嗅皮层（mEC 提供网格/时间坐标，LEC 提供物体/内容）接收来自两条信息流的输入。

情节记忆的典型特征是"心理时间旅行"（mental time travel）：能有意识地"重新经历"过去的事件（向后）或"预演"未来的场景（向前）——两者都依赖同一套海马时空模拟系统。海马损伤（如 H.M. 案例中的双侧海马切除）不只造成新情节记忆的缺失，也损伤了想象未来事件的能力，印证了这一假说。

## 关键机制

### 时空支架理论

```
时间细胞（几时）→ ─┐
场所细胞（哪里）→ ─├→ 海马 CA1 整合 → 情节帧
内容信息（什么）→ ─┘         ↓
                        SWR 重播 → 系统巩固 → 新皮层长时存储
```

海马-EC 系统的三层组织：
- **内嗅皮层 mEC**：提供网格/时间坐标（空间度量 + 时间序列）
- **内嗅皮层 LEC**：提供物体/内容信息（"什么"）
- **海马 CA1/CA3**：将两条流整合，形成内容-时空绑定的情节编码

### 巩固路径

**快速初始编码**：BTSP（行为时间尺度突触可塑性）和 Hebbian LTP 在体验时快速在 CA1/CA3 形成编码；时间细胞序列和场所场同时被写入海马回路。

**离线巩固**：SWR（尖波涟漪）期间，时空序列以 20 倍速重播，通过 SO-spindle-SWR 三重耦合逐步将情节记忆转移到新皮层分布式存储，最终形成语义化的长期记忆。

### 情节记忆 vs 语义记忆

| | 情节记忆 | 语义记忆 |
|---|---|---|
| 内容 | 具体时空事件 | 一般知识/概念 |
| 海马依赖 | 强（急性期） | 最终独立 |
| 时间维度 | 核心要素 | 非必需 |
| "心理时间旅行" | 是 | 否 |

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 海马损伤导致情节记忆缺失（H.M. 案例） | 双侧海马切除 + 记忆测试 | Scoville & Milner 1957 | 高（经典） |
| 情节记忆需要"什么+哪里+几时"三维整合 | 综述 + 认知神经科学 | Eichenbaum 2013 (PMID:23318095) | 高 |
| 时间细胞为"几时"维度提供神经底物 | 大鼠 TPOT 任务 CA1 记录 | MacDonald et al. 2011 (PMID:21867888) | 高 |
| 人类 MTL 神经元编码序列时间结构 | 颅内 SEEG 单神经元记录 | Tacikowski et al. 2024 (PMID:39322671) | 高 |
| 海马损伤也损害想象未来事件 | 失忆症患者行为 + fMRI | Hassabis et al. 2007 | 高 |
| DMN（MTL 子系统）支持场景构建 | 静息态 fMRI + 任务 fMRI | Andrews-Hanna et al. 2014 | 高 |

## 连接

- [[time-cells]] — 提供情节记忆的"几时"维度
- [[place-cells]] — 提供情节记忆的"哪里"维度
- [[hippocampal-circuit]] — 三突触回路是情节帧的绑定基础设施
- [[memory-consolidation]] — 情节记忆经 SWR 重播逐渐转移到新皮层
- [[sharp-wave-ripples]] — 离线期间对情节记忆时空序列的快速重播
- [[engram-cells]] — 情节记忆的细胞集成体：特定神经元集合编码特定情节
- [[default-mode-network]] — DMN MTL 子系统支持场景构建和自传式回忆
- [[cognitive-map]] — 情节记忆依赖认知地图的时空支架

## 未解问题

- Q-timecell-human-task：主动的情节时间推断（"这发生在几时？"）是否激活与被动观察相同的时间细胞？

## 修订历史

- 2026-07-26 · 创建 · 基于《时间的神经地图：海马时间细胞如何让大脑记住"几时"》· 初始置信度：高

## 来源文章

- [[2026-07-26-hippocampal-time-cells-temporal-coding]]

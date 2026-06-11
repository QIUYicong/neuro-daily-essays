---
title: 中颞区（MT/V5）
slug: area-MT-V5
domain: systems
type: region
status: established
confidence: high
created: 2026-08-17
updated: 2026-08-17
revision_count: 1
dimensions: [brain-region, systems, cellular, microcircuit]
related: [dorsal-visual-stream, v1-primary-visual-cortex, mst-medial-superior-temporal, lip-lateral-intraparietal, ocular-dominance-columns, v4-visual-area]
prerequisites: [v1-primary-visual-cortex, action-potential, synaptic-transmission]
opens_questions: [Q-dorsal-01]
source_articles: [2026-08-17-dorsal-visual-stream-MT-V5-motion-space]
key_sources: ["PMID:1607944", "PMID:3385495", "PMID:31293393", "PMID:15702885", "PMID:22159104"]
---

# 中颞区（MT/V5）

> **一句话定义**：MT（Middle Temporal area，猕猴）/ V5（人类），是背侧视觉流中第一个高度专业化的运动处理区域，超过 90% 的神经元对视觉运动的方向和速度有精确调谐，通过整合多个 V1 输入解决光圈问题，因果性地支撑运动方向感知。

## 当前理解

我们现在认为，MT/V5 是大脑从局部边缘运动中提取真实物体运动方向的关键节点。它接受来自 V1、V2、V3 的前馈视觉输入，以及来自外侧膝状体（LGN）大细胞层的旁路输入——这条旁路使 MT 能在 V1 受损后仍维持部分功能。

MT 神经元的核心特性：
- **方向选择性**：>90% 的神经元对运动方向有强调谐，半波宽约 60–90°
- **速度调谐**：每个神经元有偏好速度，整体覆盖 0.5–500°/s 的宽速度范围
- **双眼视差敏感**：许多神经元对立体深度有调谐，可从运动视差提取深度（PMID: 22159104）
- **大感受野**：比 V1 大约 10 倍，允许整合更大范围的运动信息
- **方向柱组织**：类似 V1 方向柱，MT 神经元按方向偏好有序排列（方向柱）

最重要的计算成就：通过存在"模式细胞"（pattern cells，约 25-30%）解决**光圈问题**——整合多个 V1 局部输入（尤其是线端终止处的端停止细胞信号），提取物体真实的运动方向，而非仅报告局部边缘的分量运动。

MT 是运动感知的**因果性节点**，有三条相互独立的证据支持：
1. 选择性病变（化学损毁）→ 方向判别阈值升高，亮度感知不受影响（PMID: 3385495）
2. 选择性微电刺激特定方向柱 → 感知判断系统性偏移（PMID: 1607944）
3. 人类 MT 同源区域（V5）损伤 → 运动失认症（患者 L.M.，Zihl 1983）

## 关键机制

### 方向选择性的来源

MT 的方向选择性来自多路 V1 输入的整合：
- V1 简单细胞的方向选择性为 MT 提供基本的方向"票"
- MT 模式细胞特别依赖 V1 端停止细胞（end-stopped cells）在线段终点处的无歧义运动信号

### 光圈问题的解决

| 细胞类型 | 比例 | 响应特性 |
|---------|------|---------|
| 分量细胞（Component cells） | ~40% | 响应各自垂直于边缘方向的分量运动 |
| 模式细胞（Pattern cells） | ~25-30% | 响应物体真实运动方向（PMID: 31293393） |
| 中间型 | ~30-35% | 介于两者之间 |

模式细胞的出现代表 MT 将多个局部、歧义的运动信号整合为单一、无歧义的方向估计——视觉运动感知的核心计算成就。

### MT 损伤（运动失认症）

患者 L.M.（Zihl et al. 1983，Brain 106:313）：双侧后部皮层损伤，表现为：
- 无法感知物体运动（"冻结帧"体验）
- 无法判断来往车辆方向，倒茶时看不到茶流
- 形状识别、颜色辨别完全正常
- 是"选择性缺失 = 功能模块化"的经典证据

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| MT >90% 神经元方向选择 | 猕猴单神经元电生理 | PMID:15702885 (综述) | 高（教科书级） |
| MT 因果参与运动感知（病变） | ibotenic acid 损毁 + 随机点方向判别 | PMID:3385495 | 高 |
| MT 因果参与运动感知（刺激） | 微电刺激方向柱 + 感知报告偏移 | PMID:1607944 | 高 |
| MT 存在模式细胞解决光圈问题 | V1→MT 输入模型 + 实验验证 | PMID:31293393 | 中-高 |
| MT 神经元对双眼视差有调谐 | 立体刺激 + 单神经元记录 | PMID:22159104 | 高 |

## 连接

- [[dorsal-visual-stream]] — MT 是背侧流的核心运动处理站
- [[v1-primary-visual-cortex]] — V1 提供方向选择性输入，MT 整合并提取运动方向
- [[mst-medial-superior-temporal]] — MT 输出到 MST，进行光流整合
- [[lip-lateral-intraparietal]] — MT 运动信号作为 LIP 决策积分的证据来源

## 未解问题

- Q-dorsal-01：MT 旁路输入（直接来自 LGN）的功能意义？盲视（blindsight）中的 MT 残留功能从何而来？

## 修订历史

- 2026-08-17 · 创建 · 基于《大脑的运动侦探》(#116) · 初始置信度：高

## 来源文章

- [[2026-08-17-dorsal-visual-stream-MT-V5-motion-space]]

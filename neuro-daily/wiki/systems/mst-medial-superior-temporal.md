---
title: 内上颞区（MST）
slug: mst-medial-superior-temporal
domain: systems
type: region
status: established
confidence: high
created: 2026-08-17
updated: 2026-08-17
revision_count: 1
dimensions: [brain-region, systems, cellular]
related: [dorsal-visual-stream, area-MT-V5, lip-lateral-intraparietal, v1-primary-visual-cortex]
prerequisites: [area-MT-V5, action-potential]
opens_questions: [Q-dorsal-01]
source_articles: [2026-08-17-dorsal-visual-stream-MT-V5-motion-space]
key_sources: ["PMID:1875243", "PMID:1875244", "PMID:17600525"]
---

# 内上颞区（MST / Medial Superior Temporal Area）

> **一句话定义**：MST（内上颞区）是背侧视觉流中接收 MT 输入的光流解析节点，其背侧亚区（MSTd）神经元对大感受野的扩张、旋转和平动光流有精确调谐，整合视觉光流与前庭信号，提取自身在空间中的运动方向（航向），是自我运动感知的核心皮层基底。

## 当前理解

我们现在认为，MST 是背侧视觉流从"物体运动"到"自身运动"计算的过渡节点。它从 MT 接收方向和速度信号，通过大感受野整合将局部运动场转化为全局运动模式的表征。

MST 分为两个功能亚区：
- **MSTd（背侧）**：大感受野（可达 50°），对光流的整体成分（扩张/收缩/旋转/平动）有调谐，响应自身运动的视觉信号，是导航的核心节点。
- **MSTl（外侧）**：较小感受野，更侧重于物体运动追踪（而非自身运动）。

MSTd 的多模态整合：约 64% 的 MSTd 神经元不仅对光流定义的航向调谐，也对前庭惯性运动（otolith 信号）有调谐（约 98% 对光流有调谐）。当两种信号一致时，神经元通常响应最强，说明 MST 实现了视觉-前庭的最优整合（贝叶斯意义上的权重整合）。

## 关键机制

### 光流成分与航向提取

当自身向前运动时，视野产生从中心向外的"扩张"光流，这是航向的经典视觉信号。MSTd 神经元：
- 对扩张、收缩、旋转、平动各有调谐
- 通过这些基本成分的组合估计三维航向方向
- 在虚拟现实任务中，三维航向调谐可精确到约 10° 的分辨率

### 光流感受野的构建

MSTd 神经元的大感受野（含中央凹表征区）来自 MT 多个感受野位置的汇聚输入（Duffy & Wurtz 1991，PMID: 1875243）。这种汇聚使 MSTd 能整合视野中多个位置同时发生的运动，而非孤立地响应局部运动。

### 视觉-前庭整合

在猕猴导航实验中，MSTd 神经元在光流单独呈现、前庭信号单独呈现、以及两者同时呈现时都表现出对航向的调谐，且多模态刺激通常产生更强/更准确的调谐，符合最优整合（maximum likelihood estimation）的预测。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| MSTd 神经元对光流成分（扩张/旋转/平动）调谐 | 大视野运动刺激 + 单神经元记录 | PMID:1875243 | 高 |
| MSTd 神经元对三维航向有调谐 | 虚拟现实光流 + 电生理 | 综合研究 | 高 |
| MSTd 整合视觉光流与前庭信号 | 双模态刺激 + 单神经元记录（约64% 前庭-视觉双调谐） | 综述 PMID:17600525 | 中-高 |

## 连接

- [[dorsal-visual-stream]] — MST 是背侧流光流整合的专用节点
- [[area-MT-V5]] — MT 提供方向和速度信号到 MST
- [[lip-lateral-intraparietal]] — MST 输出自身运动信息到 LIP，参与空间决策

## 未解问题

- Q-dorsal-01：MSTd 的前庭-视觉整合具体机制？信号冲突（如虚拟现实晕动症）时如何权重？

## 修订历史

- 2026-08-17 · 创建 · 基于《大脑的运动侦探》(#116) · 初始置信度：高

## 来源文章

- [[2026-08-17-dorsal-visual-stream-MT-V5-motion-space]]

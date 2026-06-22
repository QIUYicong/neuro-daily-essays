---
title: MT/V5 运动区
slug: mt-v5-motion-area
domain: neurons
type: region
status: established
confidence: high
created: 2026-08-30
updated: 2026-08-30
revision_count: 1
dimensions: [cellular, brain-region, systems]
related: [dorsal-visual-stream, posterior-parietal-cortex, v1-primary-visual-cortex]
prerequisites: [v1-primary-visual-cortex, action-potential]
opens_questions: [Q-mt-01]
source_articles: [2026-08-30-dorsal-visual-stream-parietal-action]
key_sources: ["PMID:3385495", "PMID:16022593"]
---

# MT/V5 运动区 (Middle Temporal Area / V5)

> **一句话定义**：MT（猴）/ V5（人类）是背侧视觉流的关键中间站，大多数神经元具有方向选择性，能整合局部运动信息为整体运动方向感知，并接受双目视差输入，是大脑提取三维运动信号的专用处理器。

## 当前理解

我们现在认为 MT/V5 是背侧视觉流中第一个主要的专门化处理节点，也是大脑中对视觉运动响应最特异化的皮层区域。它并非简单地"转发"运动信息，而是通过神经元集群的方向柱（direction columns）对运动进行结构化编码，并将局部运动（local motion）整合为整体运动模式（pattern motion），实现对"整个物体在运动"的感知，而非仅仅"边缘在移动"。

MT 损毁直接损害运动感知（Newsome & Paré 1988，PMID: 3385495），人类 V5 损伤导致运动盲（akinetopsia），证明 MT/V5 对运动感知是必要的——尽管其他并行通路存在，损伤效应通常部分可恢复。

## 关键机制

### 方向选择性
- MT 神经元对特定运动方向（如向左）反应强烈，对相反方向反应弱
- 方向柱（direction columns）按方向偏好系统排列，类似 V1 的朝向柱
- 大多数神经元对静止刺激无响应

### Pattern Motion 整合
- MT 能整合跨接受野的运动方向，感知整体运动模式
- 这使得大脑能分辨"整个物体向左运动"而不只是"某条边缘向左倾斜"

### 双目视差与三维运动
- MT 有大量对双目视差（binocular disparity）敏感的神经元
- 结合运动方向和深度信息，MT 参与三维运动感知

### 在背侧流中的位置
- 输入：V1 M 细胞层（快速、低分辨率）→ V2 厚条纹 → MT
- 输出：→ MST（自我运动/光流）→ 后顶叶 LIP/VIP

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| MT 损毁→运动感知阈值升高 | 猕猴 MT 化学损毁 + 随机点运动辨别任务 | PMID: 3385495 (Newsome & Paré 1988) | 高 |
| MT 有方向柱 | 单细胞电生理 + 光学成像 | PMID: 16022593 (Born & Bradley 2005) | 高 |
| 人类 V5 损伤→运动盲 | 临床神经病学案例 | 教科书级证据 | 高 |

## 连接

- [[dorsal-visual-stream]] — MT/V5 是背侧流的核心中间站
- [[v1-primary-visual-cortex]] — MT/V5 的主要输入来源（M 细胞通路）
- [[posterior-parietal-cortex]] — MT/V5 向 LIP/VIP 提供运动输入

## 未解问题

- Q-mt-01（中优先级）：MT 对运动感知的必要性程度——单 MT 损毁效应短暂，提示并行通路存在。并行通路的精确解剖和功能分工是什么？

## 修订历史

- 2026-08-30 · 创建 · 基于《视觉的另一半：背侧流如何把世界变成动作》· 初始置信度：高

## 来源文章

- [[2026-08-30-dorsal-visual-stream-parietal-action]]

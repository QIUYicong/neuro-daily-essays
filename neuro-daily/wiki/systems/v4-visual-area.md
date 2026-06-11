---
title: V4 视觉区
slug: v4-visual-area
domain: systems
type: region
status: established
confidence: medium
created: 2026-08-16
updated: 2026-08-16
revision_count: 1
dimensions: [brain-region, cellular]
related: [v1-primary-visual-cortex, inferior-temporal-cortex, invariant-object-recognition]
prerequisites: [v1-primary-visual-cortex, action-potential]
opens_questions: [Q-it-01]
source_articles: [2026-08-16-inferotemporal-cortex-ventral-stream-object-recognition]
key_sources: ["PMID:32580663"]
---

# V4 视觉区 (Primate Visual Area V4)

> **一句话定义**：V4 是腹侧视觉流的中间节点，在"物体中心"坐标系中对边界形状（曲率×角度组合）、颜色、纹理、深度进行联合高维编码，是从 V1 低级边缘到 IT 高级物体表征的关键转折点。

## 当前理解

我们现在认为，V4 代表腹侧流从"图像坐标"到"物体中心坐标"的关键转变。与 V1 神经元编码感受野内局部方向边缘不同，V4 神经元对物体边界的曲率和物体中心相对角度的组合有选择性（Pasupathy et al. 2020, PMID:32580663），这种偏好在感受野内不同绝对位置保持稳定，说明位置不变性已经开始涌现。

V4 不是简单的"颜色区"（旧有的 V4=color area 标签过于简化）。它是一个高维特征空间，对形状、纹理、颜色、深度同时调谐（联合调谐），使 V4 能够进行面向物体分割和识别的多维特征提取。

V4 在人类脑中的精确范围仍有争议（猕猴 V4 与人类 V4 的对应关系不完全确定），这是该条目 confidence 为 medium 而非 high 的主要原因。

## 关键机制

### 形状选择性：物体中心坐标的曲率-角度空间

V4 神经元的形状偏好可以用两个参数描述：
1. **曲率（curvature）**：偏好某种弯曲程度的边界（尖锐凸起 vs. 缓和弧线 vs. 平直 vs. 凹入）
2. **物体中心角度（object-centered angular position）**：偏好该特征在物体轮廓的哪个方位出现（右上方 / 左下方等）

例如，一个 V4 神经元可能特别响应"物体右上方出现的锐凸起"。这种表征与 V1 的"图像中某位置有某方向的边"完全不同——V4 开始以物体为参考系来描述形状特征。

### 真实边界 vs. 遮挡边界的区分

V4 神经元能区分：
- **真实物体边界**（由物体本身的轮廓产生）：响应强
- **偶然边界**（由一物体遮挡另一物体产生的边界）：响应弱

这暗示 V4 已经利用了场景的三维结构信息（哪条边"属于"前景物体？），而不仅仅响应视网膜上的局部边缘。

### 响应潜伏期

V4 神经元的响应潜伏期宽泛：平均 **76.6 ms**（范围 25–200 ms）。快速响应（~25–50 ms）与运动皮层 MT 和额叶眼动区 FEF 相当，说明 V4 不是一个"慢速、深度分析"的区域，其早期响应成分对后续的快速行为决策有贡献。

### 多维联合调谐

V4 神经元对形状 × 纹理 × 颜色 × 深度的高维特征组合进行联合调谐（joint, independent tuning）。这与 V1 的单维度（方向/空间频率）或 V2 的低阶组合（纹理二阶统计）不同，标志着真正的多维"物体部件特征空间"的涌现。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| V4 在物体中心坐标下调谐曲率×角度组合 | 清醒猕猴单神经元记录 + 形状空间系统刺激 | PMID:32580663 | 高 |
| V4 区分真实 vs. 偶然轮廓 | 猕猴单神经元 + 操控遮挡条件刺激设计 | PMID:32580663 | 高 |
| 平均响应潜伏期 76.6 ms | 276 个 V4 神经元的系统测量 | PMID:32580663 | 高 |
| V4 稀疏度 ~11%（自然图像）| 自然图像库单元记录，与 IT 定量比较 | PMID:22836252 | 高 |
| 人类 V4 的边界在 fMRI 中存在争议 | 多组 fMRI 研究，不同结论 | 多来源 | 低-中 |

## 连接

- [[v1-primary-visual-cortex]] — V4 的主要（间接）输入来源；V1→V2→V4 层级传递
- [[inferior-temporal-cortex]] — V4 的主要输出目标；V4 为 IT 提供中级形状特征
- [[invariant-object-recognition]] — V4 是不变量识别的关键中间阶段（位置不变性开始涌现）

## 未解问题

- Q-it-01：V4 计算的究竟是形状特征还是纹理统计？（涉及 Ayzenberg & Behrmann 2022 争论）

## 修订历史

- 2026-08-16 · 创建 · 基于《从线条到身份：腹侧视觉流如何解决不变量物体识别的核心难题》 · 初始置信度：中（V4 功能性质 established，但人类对应区域边界争议，故整体 medium）

## 来源文章

- [[2026-08-16-inferotemporal-cortex-ventral-stream-object-recognition]]

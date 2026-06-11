---
title: 顶内沟外侧区（LIP）
slug: lip-lateral-intraparietal
domain: systems
type: region
status: mainstream
confidence: medium
created: 2026-08-17
updated: 2026-08-17
revision_count: 1
dimensions: [brain-region, systems, cognition, behavior]
related: [dorsal-visual-stream, area-MT-V5, mst-medial-superior-temporal, prefrontal-cortex, working-memory, dorsal-attention-network]
prerequisites: [area-MT-V5, action-potential, synaptic-transmission]
opens_questions: [Q-dorsal-02]
source_articles: [2026-08-17-dorsal-visual-stream-MT-V5-motion-space]
key_sources: ["PMID:11600651", "PMID:17600525", "PMID:28772104"]
---

# 顶内沟外侧区（LIP / Lateral Intraparietal Area）

> **一句话定义**：LIP 是背侧视觉流中接收 MT/MST 运动证据并通过斜坡式积累（ramping activity）实现感知决策的顶叶节点，其放电率在决策期间持续上升，达到阈值时触发眼跳，被认为是漂移扩散模型（drift-diffusion model）的神经实现。

## 当前理解

我们现在认为，LIP 是联结感觉（MT 运动信号）与动作（眼跳）的决策计算节点。在随机点运动方向判别任务中，LIP 神经元的放电率在刺激呈现后缓慢积累，以斜坡形式持续上升约 1–2 秒，直至越过某一阈值触发反应眼跳（Shadlen & Newsome 2001，PMID: 11600651）。

斜坡活动的关键特性：
- **与刺激一致性成正比**：运动点越一致（越清晰），斜坡上升越陡，决策越快
- **预测最终选择**：对偏好目标对应的 LIP 神经元放电率上升，对非偏好目标对应的神经元放电率下降
- **阈值恒定**：无论刺激清晰度如何，放电率在越过相似阈值后触发眼跳
- **与漂移扩散模型匹配**：积累速度（drift rate）对应感觉证据强度，阈值对应决策边界

这一发现的深刻意义在于：它把"下决心"这一哲学上难以把握的主观时刻，翻译成了神经回路中可直接测量的物理阈值过程。

**争议**：LIP 是通用决策节点，还是"眼跳准备区"？LIP 本是一个准备眼跳的区域，其斜坡也许只是运动计划，而非真正的感知证据积累（PMID: 28772104 综述了这一争论）。当动物用手而非眼跳反应时，LIP 斜坡是否仍然存在？部分实验表明存在与效应器无关的成分，但争议未止。

## 关键机制

### 斜坡活动的产生

LIP 的斜坡活动来源可能包括：
1. **持续的 MT 差分输入**：MT 中偏好左运动 vs 右运动的神经元放电差异（"差分证据流"）持续输入 LIP，被 LIP 积分
2. **循环回路积分**：LIP 内部的循环连接（或 LIP-前额叶环路）实现时间积分，将瞬时输入转化为累积表征
3. **决策阈值的神经实现**：可能由 LIP 到上丘/FEF（眼球运动控制区）的下行投射阈值实现

### 速度-准确性权衡

漂移扩散框架自然实现了速度-准确性权衡（speed-accuracy tradeoff）：
- 低阈值 → 快速反应，但更多错误
- 高阈值 → 慢速反应，但更高准确率
- LIP 的决策阈值可能受前额叶调控（奖励期望、紧迫程度）动态调整

### 与漂移扩散模型的对应

| 数学模型概念 | LIP 神经活动 |
|------------|------------|
| 决策变量 x(t) | LIP 放电率斜坡 |
| 漂移率（drift rate） | MT 差分证据强度（∝ coherence） |
| 决策边界（bound） | 触发眼跳的阈值放电率 |
| 决策时刻 | 放电率越过阈值的时刻 |

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| LIP 神经元放电率在决策期间呈斜坡 | 随机点运动方向判别 + LIP 单神经元记录 | PMID:11600651 | 高 |
| 斜坡速率与刺激一致性（证据强度）成正比 | 同上，不同 coherence 条件 | PMID:11600651 | 高 |
| 斜坡活动与漂移扩散模型预测定量吻合 | 综述+计算建模 | PMID:17600525 | 中-高 |
| LIP 是眼跳计划区，斜坡可能是运动准备 | 手动任务中 LIP 斜坡部分消失 | PMID:28772104 | 中（争议） |

## 连接

- [[dorsal-visual-stream]] — LIP 是背侧流决策整合的最高节点
- [[area-MT-V5]] — MT 差分运动信号是 LIP 决策积分的证据来源
- [[mst-medial-superior-temporal]] — MST 自身运动信号也输入 LIP
- [[prefrontal-cortex]] — 前额叶调节 LIP 的决策阈值和规则
- [[dorsal-attention-network]] — LIP 是背侧注意网络（FEF-IPS/LIP）的重要节点

## 未解问题

- Q-dorsal-02：LIP 斜坡活动的细胞机制？是 LIP 内部循环积分，还是来自上游的持续输入？
- 当动物使用手动反应（而非眼跳）时，LIP 的斜坡是否仍存在且依然对应决策变量？（争议未止）

## 修订历史

- 2026-08-17 · 创建 · 基于《大脑的运动侦探》(#116) · status=mainstream（因 LIP-as-decision-integrator 存在争议）· 置信度：中

## 来源文章

- [[2026-08-17-dorsal-visual-stream-MT-V5-motion-space]]

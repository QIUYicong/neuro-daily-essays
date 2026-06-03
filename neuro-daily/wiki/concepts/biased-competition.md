---
title: 偏置竞争模型
slug: biased-competition
domain: concepts
type: theory
status: mainstream
confidence: high
created: 2026-07-01
updated: 2026-07-01
revision_count: 1
dimensions: [cognition, whole-brain-network, brain-region, microcircuit]
related: [dorsal-attention-network, working-memory, v1-primary-visual-cortex, attentional-blink, global-workspace-theory]
prerequisites: [dorsal-attention-network, v1-primary-visual-cortex]
opens_questions: []
source_articles: [2026-07-01-dorsal-attention-network-FEF-IPS]
key_sources: ["PMID:7605061", "PMID:11994752", "PMID:10376597"]
---

# 偏置竞争模型 (Biased Competition Model)

> **一句话定义**：多个视觉刺激在感觉皮层中竞争有限的神经表征资源；注意通过自上而下的偏置信号（来自 FEF/IPS）倾斜这场竞争，使目标刺激获得更强的皮层表征和处理优先权。

## 当前理解

偏置竞争模型由 Desimone 和 Duncan（1995, PMID:7605061）提出，是目前解释选择性视觉注意神经机制最有影响力的理论框架之一。

核心主张：
1. **竞争**：同时呈现在神经元感受野内的多个刺激会**相互抑制**对方的表征——当两个刺激同时出现时，神经元的响应低于单独呈现任一刺激时的响应
2. **偏置**：注意通过自上而下的偏置信号（来自前额叶、FEF、IPS）改变竞争的"起点"——被注意的刺激获得额外增益，从而在竞争中胜出
3. **分布式**：竞争在感觉处理的每一层级都发生（从 V1 到 IT），不局限于高级皮层

核心预测（均获实验支持）：
- 当两个刺激同时出现在同一感受野时，神经元响应 < 单独呈现任一刺激（相互抑制）
- 注意于其中一个刺激 → 该刺激"主导"感受野，响应接近单独呈现水平（偏置后的竞争胜出）
- 感受野越小、刺激间距越近，竞争越激烈

## 关键机制

偏置竞争中的"偏置信号"来自 FEF 和 IPS 构成的背侧注意网络（DAN），通过以下方式施加：

1. **皮层反馈增益调制**：FEF → V4 → V1 的反馈路径产生乘法增益，使被注意位置的所有神经元响应整体放大
2. **视丘门控**：FEF/IPS → TRN → 视丘核，调节感觉信号的丘脑传递效率
3. **局部抑制竞争**：在 V4、IT 等区域，被注意目标的活动通过侧抑制压制竞争者的表征

乘法增益（Treue & Martínez Trujillo 1999, PMID:10376597）是偏置竞争的核心调制形式：不改变神经元的偏好特性（调谐宽度不变），只整体放大响应强度。

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| 多刺激相互抑制（竞争存在） | 猕猴 V4/IT 双刺激 vs 单刺激比较 | 多个 Desimone 实验室研究 | 高 |
| 注意恢复竞争（偏置有效） | 猕猴单单元记录 + 注意任务 | Reynolds et al. 系列 | 高 |
| 偏置信号来自前额叶-顶叶 DAN | fMRI + 微电刺激（FEF） | Corbetta & Shulman 2002 | 高 |
| 乘法增益是偏置的计算形式 | 猕猴 MT 方向调谐曲线 | Treue & Trujillo 1999, PMID:10376597 | 高 |

## 连接

- [[dorsal-attention-network]] — DAN（FEF+IPS）是产生偏置信号的解剖实体
- [[working-memory]] — 工作记忆维持目标信息，提供持续的偏置信号来源
- [[v1-primary-visual-cortex]] — V1 是竞争发生的早期感觉皮层层级
- [[attentional-blink]] — 注意瞬盲是竞争资源（Stage 2 工作记忆巩固）被占用的表现
- [[global-workspace-theory]] — GWT 的"广播"可以理解为赢得偏置竞争后进入全局工作空间

## 未解问题

（偏置竞争模型本身争议较少，主要开放问题见 [[dorsal-attention-network]] 页面）

## 修订历史

- 2026-07-01 · 创建 · 基于《空间注意的神经回路》一文 · 来源：Desimone & Duncan 1995, Corbetta & Shulman 2002, Treue & Trujillo 1999 · 初始置信度：高

## 来源文章

- [[2026-07-01-dorsal-attention-network-FEF-IPS]]

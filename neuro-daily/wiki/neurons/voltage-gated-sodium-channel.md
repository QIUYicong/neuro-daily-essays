---
title: 电压门控钠通道
slug: voltage-gated-sodium-channel
domain: neurons
type: structure
status: established
confidence: high
created: 2026-05-24
updated: 2026-05-24
revision_count: 1
dimensions: [molecular]
related: [action-potential, axon-initial-segment, hodgkin-huxley-model]
prerequisites: []
opens_questions: [Q-nav-developmental-switch]
source_articles: [2026-05-24-axon-initial-segment]
key_sources: ["PMID:23055474", "PMID:28536506"]
---

# 电压门控钠通道 (Voltage-Gated Sodium Channel, Nav)

> **一句话定义**：电压门控钠通道是一类感知膜电压、在去极化时快速开放允许 Na⁺ 内流的膜蛋白，是动作电位上升相的分子引擎。

## 当前理解

我们现在认为，电压门控钠通道是把"电压变化"翻译成"离子流"的分子机器。它由大型 α 亚基（约 260 kDa，约 2000 个氨基酸，四个同源结构域，每域 6 个跨膜片段 S1–S6）和较小的 β 亚基（30–40 kDa）构成。其工作的两个核心动作是**激活**（S4 片段感知电压、外移开门）与**快速失活**（胞内 IFMT 序列折入孔道封闭）。不同亚型（NaV1.1–1.9）有不同的激活阈值与分布，决定了神经元各区段的兴奋性差异。

## 关键机制

**电压感知**：S4 片段含等间距排列的带正电氨基酸（门控电荷），膜去极化时整体向外移动，以"虹膜样运动"打开孔道。

**离子选择**：孔道含宽外前庭与窄胞内激活门；选择性滤器用酸性侧链实现对 Na⁺ 的特异性传导（细菌祖先 NaVAb 晶体结构揭示）。

**快速失活**：胞内 IFMT（Ile-Phe-Met-Thr）环作为"铰链盖"折入孔道阻断电流，造成不应期。

**亚型与定位**：NaV1.6 阈值最低，主导成熟 [[轴突始段]]；NaV1.2 主导发育早期 AIS；定位受 AnkyrinG 经 II-III 连接子结合调控，并受 CK2 磷酸化微调。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| α 亚基为四同源结构域 × 6 跨膜片段 | 纯化（神经毒素探针）+ 克隆测序 | PMID:23055474 | 高 |
| S4 门控电荷外移驱动激活 | 晶体结构 + 门控电流测量 | PMID:23055474 | 高 |
| IFMT 序列介导快速失活 | 定点突变 + 电生理 | PMID:23055474 | 高 |
| AnkyrinG 经 II-III 连接子招募 Nav | 分子结合实验 | PMID:28536506 | 高 |

## 连接

- [[动作电位]] — 本通道是其上升相的分子基础
- [[轴突始段]] — Nav 在此超高密度聚集（NaV1.6/NaV1.2）
- [[Hodgkin-Huxley 模型]] — 用数学描述了 Nav 的激活/失活动力学

## 未解问题

- **Q-nav-developmental-switch**：NaV1.2→NaV1.6 的发育转变受何信号触发，人类与啮齿类是否一致？

## 修订历史

- 2026-05-24 · 创建 · 基于《决策的解剖学：神经元如何在混沌的输入中找到它唯一的声音》· 初始置信度：高

## 来源文章

- [[2026-05-24-axon-initial-segment]]

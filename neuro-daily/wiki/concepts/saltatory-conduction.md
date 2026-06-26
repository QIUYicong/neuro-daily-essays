---
title: 跳跃式传导
slug: saltatory-conduction
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-10-05
updated: 2026-10-05
revision_count: 1
dimensions: [molecular, cellular]
related: [oligodendrocyte, adaptive-myelination, action-potential, axon-initial-segment, voltage-gated-sodium-channel]
prerequisites: [action-potential, voltage-gated-sodium-channel]
opens_questions: []
source_articles: [2026-10-05-oligodendrocyte-adaptive-myelination]
key_sources: ["PMID:40761314", "PMID:28817797"]
---

# 跳跃式传导 (Saltatory Conduction)

> **一句话定义**：跳跃式传导是有髓鞘轴突中动作电位以"跳跃"方式从一个郎飞结（node of Ranvier）传至下一个的机制，使传导速度达到未髓鞘化轴突的 50–100 倍（约 70–120 m/s），同时大幅降低能量消耗。

## 当前理解

我们现在认为，跳跃式传导的核心价值不仅在于速度提升，更在于**传导时序的精确性**——这直接影响远距离神经元之间能否满足 STDP（棘波时序依赖可塑性）所要求的 ±20ms 共激活窗口。

髓鞘通过两种方式实现跳跃式传导：
1. **绝缘**：髓鞘的高电阻脂质双层防止离子沿轴突侧面泄漏，使局部电流只能沿轴内流动到下一个郎飞结
2. **集中**：高密度电压门控钠通道集中在郎飞结（密度约为无髓区域的 100–1000 倍），保证动作电位在每个结处忠实再生

能量效率：跳跃式传导中只有郎飞结处的少量膜面积需要重极化，离子泵（Na⁺/K⁺-ATPase）的消耗大幅降低——有髓鞘轴突的能量效率估计比无髓鞘提高约 10 倍。

**经验依赖的维度**：髓鞘厚度（g 比值）和节间长度不是固定的，而是通过适应性髓鞘化响应神经活动调整，从而改变轴突的传导速度，进而影响远距离回路的时序匹配质量。

## 关键机制

- **郎飞结构成**：AnkyrinG 锚定 Nav1.2/Nav1.6，形成高密度钠通道簇
- **髓鞘节段**：由少突胶质细胞延伸的膜翅缠绕轴突形成（约 70% 脂质，30% 蛋白质）
- **主要髓鞘蛋白**：MBP（髓鞘碱性蛋白）压缩细胞膜，PLP（蛋白脂质蛋白）维持结构
- **传导速度决定因素**：节间长度（长 → 快）、髓鞘厚度（最优 g 比值约 0.6）、轴突直径

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 有髓鞘传导速度 70–120 m/s vs 无髓约 1 m/s | 神经传导速度测量（经典电生理） | 教科书级 | 极高 |
| 髓鞘厚度改变影响传导速度（且有最优 g 比值） | 理论建模 + 实验验证 | 多来源 | 高 |
| 跳跃式传导降低能量消耗约 10 倍 | 离子通量计算 | 估算 | 中 |

## 连接

- [[oligodendrocyte]] — 产生髓鞘的细胞
- [[adaptive-myelination]] — 经验依赖地调整髓鞘参数，影响传导时序
- [[action-potential]] — 被跳跃式传导加速的信号
- [[axon-initial-segment]] — 动作电位起始处，处于髓鞘化轴突的近端
- [[voltage-gated-sodium-channel]] — 郎飞结的核心分子

## 修订历史

- 2026-10-05 · 创建 · 基于《髓鞘的秘密》(#165) · 支撑概念 · 初始置信度：高

## 来源文章

- [[2026-10-05-oligodendrocyte-adaptive-myelination]]

---
title: VIP+ 中间神经元（血管活性肠肽阳性中间神经元）
slug: vip-interneurons
domain: circuits
type: entity
status: established
confidence: high
created: 2026-06-03
updated: 2026-06-03
revision_count: 1
dimensions: [cellular, microcircuit, behavior, cognition]
related: [pv-interneurons, sst-interneurons, disinhibitory-circuit, theta-oscillations, hebbian-learning, memory-consolidation, engram-cells]
prerequisites: [synaptic-transmission, sst-interneurons, pv-interneurons]
opens_questions: [Q-vip-behavioral-universality, Q-vip-sst-pv-ratio]
source_articles: [2026-06-03-inhibitory-interneuron-diversity]
key_sources: ["PMID:24097352", "PMID:22158104", "PMID:27477017", "PMID:24429630"]
---

# VIP+ 中间神经元（VIP-expressing Interneurons）

> **一句话定义**：以 VIP 为标记的 GABA 能中间神经元，主要靶向其他抑制性中间神经元（尤其是 SST+），通过"去抑制"将行为驱动的调制信号（奖励、注意、恐惧）转化为皮层特定计算通道的选择性放大。

## 当前理解

我们现在认为，VIP+ 中间神经元是皮层中专门化的**去抑制专家**，约占 5HT3aR 阳性 GABA 能细胞的 40%，在 L2/3 中富集（约 60% 的 VIP 细胞位于 L2/3）。它们发育自尾侧神经节隆起（CGE），与 PV+/SST+ 的 MGE 来源不同。

VIP+ 细胞的形态通常为"双极型（bipolar）"：垂直细长的树突，轴突跨越多个皮层层级。其核心功能不是直接抑制锥体细胞，而是**抑制其他抑制性细胞**——主要是 SST+ 细胞，也部分靶向 PV+ 细胞，从而实现对锥体细胞的净兴奋效果（去抑制）。

VIP+ 细胞的激活主要由以下信号驱动：
1. **神经调质**：5-HT₃ 受体激动（血清素）、胆碱能输入（乙酰胆碱）——这使 VIP 细胞成为大脑"唤醒状态"和神经调制状态的感受器；
2. **top-down 输入**：来自高层皮层区域和前额叶的注意力信号；
3. **行为反馈**：奖励和惩罚信号（Pi et al., 2013, PMID:24097352）。

Pi 等（2013）在听觉皮层显示，奖励和惩罚信号**强烈且一致地激活 VIP 细胞**，随后主要压制 SST+ 细胞，最终使锥体细胞增益上调。Letzkus 等（2011，PMID:22158104）展示了恐惧学习中的去抑制链路：胆碱能→L1 中间神经元→抑制 L2/3 PV+→锥体细胞从胞体抑制中解脱→更好地整合声音-电击关联。阻断这条链路，条件恐惧无法形成。

## 关键机制

**去抑制回路（核心机制）**：
```
行为信号（奖励/惩罚/注意）→ VIP+ 激活 → SST+ 和/或 PV+ 被抑制 → 锥体细胞净兴奋
```

**细胞特性**：
- 输入阻抗高：对小的兴奋性输入即有明显响应（low activation threshold）
- 对 5-HT₃ 受体激动剂强烈去极化（化学感受器特性）
- 对胆碱能输入（mAChR）敏感

**靶标选择性**：
- 主要靶标：SST+ 中间神经元（→ 解除树突抑制）
- 次要靶标：部分 PV+ 细胞（→ 解除胞体抑制）
- 极少直接靶向锥体细胞

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| VIP 细胞被奖励/惩罚信号强烈激活 | 两光子钙成像 + 听觉辨别任务 | PMID:24097352 | 高 |
| VIP 激活主要压制 SST+（部分 PV+）| 细胞类型特异光遗传 + 电生理 | PMID:24097352 | 高 |
| VIP 介导的去抑制路径（胆碱能→L1 IN→抑制 PV→解放锥体细胞）对恐惧学习必要 | 光遗传学因果实验 | PMID:22158104 | 高 |
| VIP+ 占 L2/3 GABA 能神经元约 60% 比例 | 转基因小鼠 + IHC | PMID:27477017 | 高 |
| VIP+ 细胞发育自 CGE | 谱系追踪实验 | PMID:24429630 | 高 |

## 连接

- [[sst-interneurons]] — VIP+ 主要抑制靶标；去抑制的主要通路
- [[pv-interneurons]] — VIP+ 部分抑制 PV+；去抑制的次要通路
- [[disinhibitory-circuit]] — VIP+ 是去抑制回路的"上游门控"节点
- [[hebbian-learning]] — 去抑制在学习期间提供"学习许可信号"，可能是三因素学习规则（Hebb + 奖励）的回路基础
- [[memory-consolidation]] — 去抑制可能调控 SWR 期间特定印迹细胞的重播优先级
- [[engram-cells]] — 去抑制选择性放大特定锥体细胞群活动，可能在印迹分配（CREB 竞争）中发挥作用

## 未解问题

- Q-vip-behavioral-universality：Pi 2013 在听觉皮层、Letzkus 2011 在听觉皮层，VIP 去抑制在不同皮层区域（PFC、海马、运动皮层）是否有统一机制？
- Q-vip-sst-pv-ratio：不同皮层区域中，VIP+ 对 SST+ vs PV+ 的抑制比例是否有系统性差异？功能含义是什么？

## 修订历史

- 2026-06-03 · 创建 · 基于《回路中的少数精锐》一文 · 初始置信度：高

## 来源文章

- [[2026-06-03-inhibitory-interneuron-diversity]]

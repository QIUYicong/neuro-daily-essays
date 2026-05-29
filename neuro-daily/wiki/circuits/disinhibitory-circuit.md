---
title: 去抑制回路
slug: disinhibitory-circuit
domain: circuits
type: mechanism
status: established
confidence: high
created: 2026-06-03
updated: 2026-06-03
revision_count: 1
dimensions: [microcircuit, cellular, behavior, cognition]
related: [vip-interneurons, sst-interneurons, pv-interneurons, hebbian-learning, engram-cells, memory-consolidation, theta-oscillations]
prerequisites: [synaptic-transmission, vip-interneurons, sst-interneurons, pv-interneurons]
opens_questions: [Q-disinhibition-timing-precision, Q-disinhibition-cortex-universal]
source_articles: [2026-06-03-inhibitory-interneuron-diversity]
key_sources: ["PMID:24097352", "PMID:22158104", "PMID:24429630"]
---

# 去抑制回路（Disinhibitory Circuit）

> **一句话定义**：VIP+ 中间神经元通过抑制 SST+ 和/或 PV+ 中间神经元，实现对锥体细胞的净兴奋效果，将行为信号（奖励、惩罚、注意、恐惧）转化为皮层特定计算通道的选择性增益。

## 当前理解

我们现在认为，皮层中普遍存在一个三级去抑制回路：

**[行为信号] → VIP+ 激活 → SST+/PV+ 被抑制 → 锥体细胞从抑制中解放 → 特定输入整合效率上升**

这是一个"双重取反变正"的逻辑，其计算意义类似于电路中的"与门+非门"组合：只有当特定行为信号存在时，特定的感觉或认知输入才能被充分处理。去抑制回路将**行为状态（what matters now）**的信息注入到感觉/认知皮层的局部计算中。

Pi 等（2013，PMID:24097352）的核心实验在听觉皮层证明这一机制在行为中真实起作用：奖励和惩罚信号激活 VIP 细胞，压制 SST+，使主细胞增益上调。Letzkus 等（2011，PMID:22158104）则证明：在恐惧条件化中，胆碱能→L1 中间神经元→抑制 L2/3 PV+→主细胞去抑制，这条链路是恐惧记忆形成的必要条件，而非可选机制。

Kepecs & Fishell（2014，PMID:24429630）将去抑制回路概括为"跨皮层区域保守的微回路"：VIP→SST→锥体细胞的结构在不同皮层区域均已被发现，暗示这是一个基本的皮层计算模块。

## 关键机制

**三级架构**：
- 第一级：行为/调制信号激活 VIP+ 细胞（通过 5-HT₃R、mAChR、top-down 投射等）
- 第二级：VIP+ 细胞抑制 SST+（主要）和/或 PV+（次要）中间神经元
- 第三级：SST+/PV+ 对锥体细胞的抑制被解除

**功能含义**：
1. **学习门控**：去抑制提供"学习许可"窗口，允许特定时刻的突触可塑性发生（三因素学习规则的回路实现）；
2. **注意力放大**：top-down 注意力信号通过激活 VIP 细胞，选择性增强目标皮层区域的响应增益；
3. **感觉选通**：在感觉处理中，去抑制允许特定感觉通路在行为相关时刻得到增强处理；
4. **情绪记忆编码**：恐惧条件化、奖励学习等情绪记忆依赖去抑制机制来增强关键时刻的突触可塑性。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| VIP 激活主要压制 SST+（少量 PV+），净效果使锥体细胞增益上升 | 细胞类型特异光遗传 + 两光子钙成像 | PMID:24097352 | 高 |
| 去抑制链路对恐惧条件化形成必要（阻断则恐惧学习失败）| ChR2 激活 L1 IN + 行为实验 | PMID:22158104 | 高 |
| VIP→SST→锥体细胞架构在多个皮层区域保守 | 多区域连接组学 + 光遗传 | PMID:24429630 (review) | 中-高 |

## 连接

- [[vip-interneurons]] — 去抑制回路的门控节点（第一级）
- [[sst-interneurons]] — 去抑制的主要目标（第二级）
- [[pv-interneurons]] — 去抑制的次要目标（第二级）
- [[hebbian-learning]] — 去抑制为 Hebb 学习规则提供行为驱动的"允许信号"（三因素规则的基础）
- [[engram-cells]] — 去抑制可能在印迹竞争性分配中偏向特定神经元集合
- [[memory-consolidation]] — 去抑制可能调控 SWR 期间的印迹重播选择性
- [[theta-oscillations]] — θ 期间的选择性去抑制可能创造特定学习窗口

## 未解问题

- Q-disinhibition-timing-precision：去抑制的时间窗口有多窄？与 Hebbian STDP 的毫秒级精度相比，VIP 介导的去抑制是否有足够的时间分辨率来门控特定突触对的可塑性？
- Q-disinhibition-cortex-universal：去抑制回路在皮层下结构（杏仁核、海马、基底神经节）中是否有对应机制？

## 修订历史

- 2026-06-03 · 创建 · 基于《回路中的少数精锐》一文 · 初始置信度：高

## 来源文章

- [[2026-06-03-inhibitory-interneuron-diversity]]

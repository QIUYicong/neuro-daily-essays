---
title: 突触稳态假说（SHY）
slug: synaptic-homeostasis
domain: concepts
type: theory
status: mainstream
confidence: medium
created: 2026-05-29
updated: 2026-05-29
revision_count: 1
dimensions: [synaptic, cellular, behavior, cognition]
related: [memory-consolidation, ltp, sharp-wave-ripple, sleep-oscillations, ampa-receptor]
prerequisites: [ltp, ampa-receptor, synaptic-transmission]
opens_questions: [Q-shy-selective-downscaling]
source_articles: [2026-05-29-memory-consolidation-swr]
key_sources: ["PMID:40962324"]
---

# 突触稳态假说（Synaptic Homeostasis Hypothesis, SHY）

> **一句话定义**：突触稳态假说（SHY）认为清醒学习使皮层突触整体增强（上调），而 NREM 睡眠通过全局下调恢复突触到可持续水平，同时选择性保护被反复重激活（SWR驱动）的记忆相关突触，从而在代谢效率和记忆保留之间取得平衡。

## 当前理解

我们现在认为，SHY 是关于睡眠功能的主流假说之一，但仍有若干方面有争议（PMID:40962324）。

**核心逻辑**：
1. 清醒期间，每次学习和感知经历都在皮层建立新的 LTP（突触增强）
2. 如果不加限制，突触权重会趋向饱和：记忆容量耗尽，代谢负担过重，新学习被抑制
3. NREM 睡眠期间，皮层突触整体被下调（downscaling）：AMPA 受体密度下降，突触重量减小
4. 但 SWR 在下调过程中选择性激活记忆相关的突触群，这些突触被"保护"甚至增强
5. 最终结果：噪声突触缩小，信号突触凸出——记忆信噪比提高

**证据支持点**（PMID:40962324）：
- 睡眠后皮层神经元的突触接触面积（通过电镜测量）整体减小
- 两光子成像显示：学习后 NREM 睡眠中，训练相关区域某些树突棘增大，周围棘缩小
- 睡眠剥夺使 AMPA 受体基线水平异常升高，新学习的 LTP 空间缩小

**争议与局限**：
- 全局下调与选择性保护之间的边界如何界定？机制尚未完全阐明
- 部分研究发现睡眠中**某些类型的突触在 REM 期间增大**，不完全符合"整体下调"
- SHY 主要描述皮层；海马内部的突触平衡规则可能不同

**与 SWR 的关系**：SHY 和 SWR 不是竞争假说，而是互补的——SWR 提供"选择性激活"信号，SHY 描述"整体调节背景"。两者共同解释了为什么睡眠既清理信息又保留记忆。

## 关键机制

### 清醒期上调

- LTP 通过 CaMKII→AMPA 受体插入使突触增强
- 重复经历、强烈情绪、奖励信号使相关突触权重累积增加
- 到睡前，皮层突触平均权重高于基线

### NREM 睡眠下调

- 皮层慢振荡（SO）和纺锤波驱动全局突触下调
- 机制可能涉及：LTD 相关通路激活、AMPA 受体内吞增加、突触前递质释放减少
- 全局下调幅度取决于当天的学习量（"睡多少取决于学了多少"）

### SWR 驱动的选择性保护

- 睡眠期 SWR 反复激活代表特定经历的神经元集群
- 这些集群的突触在反复激活中维持或增强（抵抗全局下调）
- 非相关突触被下调，从而凸显记忆相关回路

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 睡眠后皮层突触整体缩小 | 电镜突触形态学 | 综述于 PMID:40962324 | 中-高 |
| 训练区域特定树突棘在睡眠后增大 | 双光子成像（两光子） | 综述于 PMID:40962324 | 中 |
| SWR 选择性激活记忆相关集群 | 多细胞记录 + 解码分析 | PMID:30356103 | 高 |

## 连接

- [[memory-consolidation]] — SHY 是系统巩固的突触层面机制
- [[ltp]] — SHY 以 LTP 的下调对等物（LTD）和受体内吞为基础
- [[sharp-wave-ripple]] — SWR 提供选择性保护信号，在全局下调中挑出"要保留"的突触
- [[ampa-receptor]] — AMPA 受体的插入和内吞是 SHY 的分子执行者

## 未解问题

- Q-shy-selective-downscaling：SHY 的"全局下调"和"选择性保护"之间的分界在分子层面如何实现？是什么信号标记了"该保留的"突触？

## 修订历史

- 2026-05-29 · 创建 · 基于《海马的夜间档案馆》文章 · 置信度设为 medium（mainstream 假说但机制细节仍有争议）

## 来源文章

- [[2026-05-29-memory-consolidation-swr]]

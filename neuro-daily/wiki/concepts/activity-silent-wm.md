---
title: 活动无声工作记忆
slug: activity-silent-wm
domain: concepts
type: mechanism
status: emerging
confidence: medium
created: 2026-08-18
updated: 2026-08-18
revision_count: 1
dimensions: [synaptic, microcircuit, cognition]
related: [working-memory, persistent-activity, short-term-synaptic-plasticity, prefrontal-cortex, attractor-network, gamma-oscillations]
prerequisites: [short-term-synaptic-plasticity, working-memory, synaptic-transmission]
opens_questions: [Q-wm-active-vs-silent, Q-wm-silent-vs-episodic, Q-wm-manipulation-mechanism]
source_articles: [2026-08-18-working-memory-persistent-activity-silent]
key_sources: ["PMID:26051384", "PMID:18339943", "PMID:32516337", "PMID:33551266", "PMID:39506106"]
---

# 活动无声工作记忆 (Activity-Silent Working Memory)

> **一句话定义**：一种工作记忆维持机制：信息在神经元不放电（"活动无声"）的状态下由突触的短期可塑性权重变化保存，可被外部探测刺激重新激活读出。

## 当前理解

我们现在认为，工作记忆的维持并非只能依赖神经元的持续放电（[[persistent-activity]]）。Stokes（2015，PMID:26051384）系统提出"活动无声"框架：在某些时间窗口内，工作记忆信息隐藏在**突触传递效率的短暂变化**（即短期突触可塑性，[[short-term-synaptic-plasticity]]）中，神经元本身几乎不放电，从外部看似乎"什么都没记"，但当给予探测刺激（冲激）时，记忆内容会被"读出"——表明信息从未真正消失。

**与持续放电的关系**：活动无声机制不是持续放电的替代，而是其补充。2024年最大规模的神经元群体记录（Panichello et al. 2024，PMID:39506106）直接证明：在同一工作记忆任务的延迟期，神经元群体**周期性在"开"（持续/选择性放电，信息可解码）和"关"（接近基线，活动无声）状态之间切换**。"开"状态对应[[gamma-oscillations]]的爆发，"关"状态对应突触权重的短暂储存。两种机制轮流工作，相互备份。

**状态评估**：这一机制已有良好的计算模型支持和行为/电生理证据，但机制的精确分子底物（哪类STSP？需要Syt7吗？）和其独立于情节记忆的边界条件仍有争议（Beukers et al. 2021，PMID:33551266）。

## 关键机制

### 短期突触易化作为储存介质

刺激激活突触前末梢时，钙离子内流触发递质释放。激活停止后，突触前末梢的**残余钙离子**（residual calcium）和Synaptotagmin-7（Syt7）的膜结合状态可在数百毫秒至约2秒内维持突触传递效率的增强（易化状态）。这个窗口恰好覆盖工作记忆的典型维持时间（~1-3秒）。

当外部探测刺激（或内源性Gamma爆发）到来时，处于易化状态的突触比未易化突触传递更多电流→激活下游神经元，从而"读出"存储的内容。

### 冲激再激活范式

Stokes（2015）提出的关键实验逻辑：
1. 呈现刺激（编码）→ 神经元高频放电
2. 延迟期：不呈现任何刺激，神经元接近基线放电（看似"无记忆"）
3. 呈现任务无关的探测刺激（冲激）
4. 观察被冲激触发的群体响应：若响应模式能区分记忆了不同内容，则证明信息以"活动无声"的方式保存

这个范式在猴子行为（双任务抑制）和人类EEG（MVPA解码）中均得到支持。

### 与持续放电的动态分工（Panichello 2024）

在"开-关"切换模型中：
- **"关"期（活动无声）**：信息储存在突触STSP易化状态；下游神经元无法自发"读出"
- **"开"期（Gamma爆发）**：神经元集体激活，对应记忆内容的模式可被解码；可能同时"刷新"STSP状态
- 切换频率与任务需求相关，高WM负荷或接近提取期时"开"状态比例增加

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 双任务抑制后WM表现不降，说明信息在放电消失期保留 | 猴行为实验 + 双任务范式 | Stokes 2015 (PMID:26051384, PMC:PMC4509720) | 中 |
| 计算模型：STSP易化可在~2秒内无声保存信息 | 计算模型（Mongillo 2008） | PMID:18339943 | 中 |
| 基于钙STSP的尖峰神经元模型重现人类EEG和行为WM数据 | 计算模型+EEG拟合 | Pals et al. 2020 (PMID:32516337) | 中 |
| 延迟期群体在"开-关"状态间切换，两机制共存 | Neuropixels，猕猴，~480神经元/节次 | Panichello et al. 2024 (PMID:39506106) | 极高 |

## 连接

- [[working-memory]] — 活动无声机制是工作记忆维持的两种机制之一（另一种为持续放电）
- [[persistent-activity]] — 在同一延迟期内交替出现，相互补充而非互斥
- [[short-term-synaptic-plasticity]] — STSP易化是活动无声WM的物理底物
- [[gamma-oscillations]] — Gamma爆发标记"开"状态，爆发间隔即活动无声窗口
- [[attractor-network]] — 活动无声机制在吸引子网络模型中对应"活动状态之外的权重储存"

## 未解问题

- Q-wm-active-vs-silent：在真实任务中，活动性编码与突触静默储存的相对权重如何？是否随任务类型变化？
- Q-wm-silent-vs-episodic：活动无声WM和海马情节记忆的快速激活是否共用机制？需要海马失活对照实验（Beukers 2021挑战）
- Q-wm-manipulation-mechanism：涉及信息主动操纵（非仅保持）时，活动无声机制是否仍然足够？Wang（2021）认为不够。

## 修订历史

- 2026-08-18 · 创建 · 基于《工作记忆的两种面孔》（#104）· 初始置信度：中；整合Stokes 2015框架、Pals 2020计算模型、Panichello 2024开-关状态证据

## 来源文章

- [[2026-08-18-working-memory-persistent-activity-silent]]

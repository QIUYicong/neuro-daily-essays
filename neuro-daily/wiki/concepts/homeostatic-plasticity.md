---
title: 稳态可塑性
slug: homeostatic-plasticity
domain: concepts
type: concept
status: established
confidence: high
created: 2026-07-03
updated: 2026-07-04
revision_count: 2
dimensions: [synaptic, cellular, molecular, behavior, cognition, disease]
related: [synaptic-scaling, ltp, ltd, hebbian-learning, ampa-receptor, intrinsic-excitability, sharp-wave-ripples, adult-neurogenesis, tripartite-synapse, ei-balance]
prerequisites: [ltp, ltd, synaptic-transmission, action-potential]
opens_questions: [Q-scale-01, Q-scale-02, Q-sca-sleep-shy]
source_articles: [2026-07-03-synaptic-scaling-homeostatic-plasticity]
key_sources: ["PMID:14735113", "PMID:22086977", "PMID:9495341"]
---

# 稳态可塑性 (Homeostatic Plasticity)

> **一句话定义**：神经元检测自身活动历史，通过多种机制（突触缩放、内在兴奋性调节、突触前稳态等）将放电率和突触权重维持在功能工作区间内的一类负反馈可塑性的总称。

## 当前理解

我们现在认为，稳态可塑性是与 Hebbian 可塑性（LTP/LTD）并列的神经可塑性的第二大支柱。若没有稳态调节，赫布型正反馈将导致突触饱和或沉默，神经网络失去动态范围。稳态可塑性通过负反馈机制（检测放电率偏差 → 反向调节突触强度或内在兴奋性）维持网络功能的稳定性。

**稳态可塑性的三大类型**（按空间尺度分）：

1. **突触稳态缩放（synaptic scaling）**：最核心类型。神经元检测总体活动水平，乘法性等比调节所有 AMPA 受体数量。保留突触间相对权重（记忆信息）。慢速（小时到天）。→ 详见 [[synaptic-scaling]]

2. **内在兴奋性稳态（intrinsic homeostasis）**：神经元通过改变离子通道表达（Na⁺ 通道、K⁺ 通道）来调节放电阈值和放电模式，独立于突触强度变化。

3. **突触前稳态（presynaptic homeostatic plasticity，PHP）**：当突触后受体受损时，突触前释放增强以补偿。通过跨突触逆行信号（Sema3a 等）实现。→ 部分详见 [[synaptic-scaling]]

**与 Hebbian 可塑性的时间隔离**：Hebbian LTP（毫秒-分钟）和稳态缩放（小时-天）的时间尺度差异使两者可以共时运行而不相互干扰——快速学习型变化不会被慢速稳态归零，稳态调节也不会截断快速学习。

## 关键机制

（主要机制详见 [[synaptic-scaling]]）

**活动传感器层级**：
- 细胞层级：总体放电率 → Ca²⁺ → CaMKIV（小时到天）
- 树突层级：局部突触传递阻断 → 视黄酸（RA）合成 → GluA1 局部翻译
- 突触层级：突触后受体受损 → Sema3a 逆行信号 → 突触前释放增强

**功能意义**：
- 维护网络的动态工作范围
- 防止兴奋性/抑制性失衡
- 主动雕刻记忆特异性（Wu et al. 2021）
- 支持发育关键期可塑性（TNFα/Arc依赖的眼优势可塑性）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 突触稳态缩放具有乘法性，保留突触相对权重 | 新皮层培养 + TTX/bicuculline + 膜片钳 | PMID:9495341 | 极高 |
| 稳态调节操作时间尺度（小时-天）与 LTP（秒-分）不同 | 多实验室，多物种，一致结果 | PMID:14735113 综述 | 高 |
| 稳态缩放主动参与记忆精调（不只是维稳） | 大鼠味觉学习 + GluA2 阻断 → 泛化期延长 | PMID:33798429 | 中-高 |

## 连接

- [[synaptic-scaling]] — 稳态可塑性的核心突触形式，详细机制在此页
- [[ltp]] — 稳态可塑性的互补机制，两者共同维护突触功能稳定
- [[hebbian-learning]] — 稳态可塑性解决了 Hebbian 规则的正反馈不稳定性
- [[ei-balance]] — 稳态可塑性是 E/I 平衡的慢速（小时-天）补偿机制；与 PV+ 中间神经元的毫秒级快速反馈抑制互补，共同维护回路工作区间

## 未解问题

- Q-scale-02：突触稳态如何与 SWR 介导的记忆巩固（选择性增强）共存？（睡眠稳态假说 SHY vs 记忆巩固假说的矛盾）

## 修订历史

- 2026-07-03 · 创建 · 基于《突触稳态：当赫布规则失控时，大脑如何给自己"归零"》 · 初始置信度：高
- 2026-07-04 · 修订 · 基于《信号与噪声之间：皮层 E/I 平衡》一文 · 新增：与 E/I 平衡的互补关系（慢速 vs 快速机制）；related 新增 ei-balance

## 来源文章

- [[2026-07-03-synaptic-scaling-homeostatic-plasticity]]

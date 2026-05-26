---
title: 动作电位
slug: action-potential
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-05-24
updated: 2026-05-26
revision_count: 3
dimensions: [molecular, cellular, synaptic, cognition]
related: [axon-initial-segment, voltage-gated-sodium-channel, hodgkin-huxley-model, synaptic-transmission, active-zone, nmda-receptor, ltp, hebbian-learning]
prerequisites: [voltage-gated-sodium-channel]
opens_questions: []
source_articles: [2026-05-24-axon-initial-segment, 2026-05-25-synaptic-vesicle-exocytosis, 2026-05-26-nmda-receptor-ltp]
key_sources: ["PMID:23055474", "PMID:22068972", "PMID:22510460"]
---

# 动作电位 (Action Potential)

> **一句话定义**：动作电位是神经元膜电位的一次快速、全或无的去极化—复极化脉冲，是神经系统将连续模拟信号转换为离散数字信号的基本单位。

## 当前理解

我们现在认为，动作电位是神经元传递信息的基本"字符"。它由电压门控离子通道的精密时序产生：膜去极化触发钠通道开放（Na⁺ 内流，正反馈式放大），随后钠通道快速失活、钾通道开放（K⁺ 外流，复极化），整个事件持续约 1–3 毫秒。其最关键的性质是**全或无**——刺激低于阈值则毫无动作电位，达到阈值则产生幅度固定的完整脉冲，与刺激强度无关。信息因此被编码在动作电位的**发放时序与频率**中，而非幅度中。

动作电位并非神经元整体的均匀属性：它有一个明确的**诞生地**（见 [[轴突始段]]），并从那里向轴突末梢（顺向）和树突（逆向，即反向传播动作电位）传播。

## 关键机制

**分子层**：电压门控钠通道（见 [[电压门控钠通道]]）的 S4 片段感知电压，去极化时向外移动打开孔道；胞内 IFMT 序列充当"铰链盖"实现快速失活。钾通道较慢开放，负责复极化。

**细胞层**：[[Hodgkin-Huxley 模型]]用四个微分方程定量描述了上述钠/钾电导的时间演化，准确预测了动作电位波形、不应期和阈值行为。该模型还区分了 Class 1（频率-强度连续）与 Class 2（不连续、有次阈振荡）两类神经元的发放动力学。

**传播**：在有髓轴突中，动作电位以跳跃式传导在 Ranvier 结节间"跳跃"，大幅提速并省能。逆向传入树突的**反向传播动作电位（bAP）**参与 Hebb 型突触可塑性的时序判定：bAP 沿树突逆向传播时，在树突棘产生去极化，解除 NMDA 受体的 Mg²⁺ 阻断；若此时该棘的突触前终末也正在释放谷氨酸，则 NMDA 受体被激活，Ca²⁺ 内流触发 LTP——这就是**突触时间依赖性可塑性（STDP）**的生物物理基础。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 钠/钾电导的电压依赖动力学可用四方程精确描述 | 鱿鱼巨轴突电压钳实验 + 数学建模 | PMID:23055474 (Hodgkin & Huxley 1952 综述) | 高 |
| 钠通道 S4 含门控电荷，去极化时外移开门 | 晶体结构（NaVAb）+ 电生理 | PMID:23055474 | 高 |
| 动作电位在轴突始段最先产生（早于胞体约 0.1 ms） | 双位点膜片钳记录 | PMID:41930336 | 高 |

## 连接

- [[轴突始段]] — 动作电位的发起位点
- [[电压门控钠通道]] — 实现动作电位上升相的分子基础
- [[Hodgkin-Huxley 模型]] — 动作电位的定量数学框架
- [[吊灯细胞]] — 通过抑制 AIS 直接控制动作电位的产生
- [[突触传递]] — 动作电位到达突触前终末后触发的下一步：化学信号转化（→[[活动区]]→[[SNARE复合体]]）
- [[nmda-receptor]] — 反向传播动作电位（bAP）提供的去极化解除 NMDA 受体的 Mg²⁺ 阻断，触发 LTP
- [[ltp]] — bAP + 突触前释放的时间巧合通过 NMDA 受体触发 LTP（STDP 机制）

## 未解问题

- 暂无本页专属未解问题（相关问题见 [[轴突始段]]）。

## 修订历史

- 2026-05-24 · 创建 · 基于《决策的解剖学：神经元如何在混沌的输入中找到它唯一的声音》· 初始置信度：高
- 2026-05-25 · 修订 · 新增"突触传递"为动作电位的下游功能连接；补充相关节点（活动区、SNARE复合体）；dimensions扩展为synaptic层 · 来源：《神经信号的化学渡口》
- 2026-05-26 · 修订 · 补充反向传播动作电位（bAP）在 Hebbian 可塑性（STDP/LTP）中的作用；related 新增 nmda-receptor、ltp、hebbian-learning；dimensions 新增 cognition · 来源：《NMDA 受体：突触的巧合检测器》

## 来源文章

- [[2026-05-24-axon-initial-segment]]
- [[2026-05-25-synaptic-vesicle-exocytosis]]

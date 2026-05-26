---
title: Hebbian 学习
slug: hebbian-learning
domain: concepts
type: theory
status: established
confidence: high
created: 2026-05-26
updated: 2026-05-26
revision_count: 1
dimensions: [synaptic, cognition]
related: [nmda-receptor, ltp, ampa-receptor, camkii, three-factor-learning-rule, stdp]
prerequisites: [synaptic-transmission, action-potential, nmda-receptor]
opens_questions: [Q-hebbian-global-error, Q-hebbian-stability]
source_articles: [2026-05-26-nmda-receptor-ltp]
key_sources: ["PMID:22510460", "PMID:30037851", "PMID:26834568"]
---

# Hebbian 学习 (Hebbian Learning)

> **一句话定义**："共同激发的神经元连接在一起"——突触前和突触后活动的时间巧合增强该突触权重，NMDA 受体在分子层面精确实现了这一原理。

## 当前理解

我们现在认为，Hebb 规则（Donald Hebb 于 1949 年提出）不只是一个直觉性的学习隐喻，而是有其分子实现：NMDA 受体的双重门控机制（需要谷氨酸结合 + 突触后去极化同时发生）在每个突触处精确执行逻辑与（AND）运算。满足条件时 Ca²⁺ 内流，激活 CaMKII，最终导致 LTP——突触权重的持久增强。

Hebb 规则解释了**联合编码**的基础（巴甫洛夫的铃声与食物之所以建立联系，是因为激活它们的神经元在时间上重合，通过 Hebbian LTP 建立了突触连接）。它也解释了**关键期**（敏感期）的机制：在大量沉默突触存在、GluN2B 比例高（更长时间整合窗口）时，Hebbian 可塑性最易被触发。

**Hebb 规则的局限**：纯 Hebb 规则没有误差信号，不能学习任意目标。现代神经科学提出**三因素学习规则**：在 Hebbian 项之外，加入**调制信号**（多巴胺奖励预测误差、乙酰胆碱注意力信号），使突触学习能够被全局目标所导向。

## 关键机制

### 经典 Hebb 规则（突触/认知层面）

- 条件：突触前活动（神经递质释放）同时发生于突触后活动（膜电位去极化）
- 结果：该突触权重增加（即 LTP）
- 分子实现：NMDA 受体双重门控 → Ca²⁺ → CaMKII → AMPA 受体插入

### STDP 扩展（突触/分子层面）

- 精确的时间顺序决定可塑性方向：
  - 突触前先于突触后激发（pre → post，间隔 <30 ms）：LTP（正向 Hebb）
  - 突触后先于突触前激发（post → pre）：LTD（反向 Hebb）
- 时间窗口宽度由 NMDA 受体的 GluN2 亚型衰减动力学决定

### 三因素学习规则（认知/系统层面）

- 权重更新 ∝ (突触前活动) × (突触后活动) × (调制信号，如多巴胺)
- 多巴胺信号（奖励预测误差）可在 Hebbian 结合后数百毫秒内调制突触可塑性
- 这使 Hebb 规则能够被全局的奖励结果所"评分"

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| NMDA 受体双重门控实现 Hebb 规则 | Mg²⁺ 阻断的电压依赖性 + 配对刺激实验 | PMID:30037851 (PMC6080888) | 高 |
| STDP 时间窗与 NMDA 受体衰减动力学相关 | 配对刺激 + NMDA 受体阻断实验 | PMID:22510460 (PMC3367554) | 高 |
| 多巴胺调制 STDP（三因素规则） | 多巴胺受体拮抗 + 遗传操控实验 | PMID:26834568 (PMC4717313) | 中 |

## 连接

- [[nmda-receptor]] — NMDA 受体是 Hebb 规则的分子实现装置
- [[ltp]] — LTP 是 Hebb 规则的突触结果
- [[three-factor-learning-rule]] — 将 Hebb 规则扩展为包含全局调制信号的学习算法（待建页面）
- [[stdp]] — STDP 是 Hebb 规则的时间分辨精化版本（待建页面）

## 未解问题

- Q-hebbian-global-error：纯 Hebb 规则没有全局误差信号；大脑如何通过多巴胺等调制器将 Hebbian 可塑性与全局目标对齐？三因素规则是否足以解释有监督学习？
- Q-hebbian-stability：纯 Hebb 规则是正反馈的（强的突触变得更强），缺乏稳定机制——大脑如何通过稳态可塑性（homeostatic plasticity）防止突触无限增强或减弱到零？

## 修订历史

- 2026-05-26 · 创建 · 基于《NMDA 受体：突触的巧合检测器》一文 · 初始置信度：高

## 来源文章

- [[2026-05-26-nmda-receptor-ltp]]

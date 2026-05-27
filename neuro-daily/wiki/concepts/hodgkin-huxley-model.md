---
title: Hodgkin-Huxley 模型
slug: hodgkin-huxley-model
domain: concepts
type: theory
status: established
confidence: high
created: 2026-05-24
updated: 2026-05-27
revision_count: 2
dimensions: [molecular, cellular, microcircuit, methods]
related: [action-potential, voltage-gated-sodium-channel, dendritic-computation]
prerequisites: [action-potential]
opens_questions: []
source_articles: [2026-05-24-axon-initial-segment, 2026-05-27-dendritic-computation]
key_sources: ["PMID:23055474", "PMID:36218068", "PMID:25856629"]
---

# Hodgkin-Huxley 模型 (Hodgkin-Huxley Model)

> **一句话定义**：Hodgkin-Huxley 模型是 1952 年提出的一组四个微分方程，定量描述动作电位期间钠/钾电导随电压和时间的演化，是计算神经科学至今的主干框架。

## 当前理解

我们现在认为，Hodgkin-Huxley（H-H）模型不仅准确，更重要的是它是一个可**无限延伸**的数学框架。它最初基于鱿鱼巨轴突的电压钳数据（Hodgkin & Huxley 因此获 1963 年诺奖），用电压依赖的激活/失活变量描述钠与钾电导，从而再现动作电位波形。七十余年后，该形式主义已从单腔室胞体扩展到树突（见 [[树突计算]]）、轴突、乃至大规模回路仿真，贯穿分子—细胞—回路三个层级。

它的局限也清晰：原始单腔室模型忽略了树突与轴突的空间复杂性；"最现实的单腔室 spike-initiation 模型是哪个"至今仍是计算神经科学的开放讨论（需在"经验内容"与"经验准确性"之间权衡）。

## 关键机制

**四方程体系**：膜电位方程 + 三个门控变量（钠激活 m、钠失活 h、钾激活 n）的动力学方程。钠电导 ∝ m³h，钾电导 ∝ n⁴。

**预测力**：准确预测动作电位形态、不应期时长、阈值行为；并通过进化压力分析预言"更快的钾激活应与更快的钠失活匹配"以优化代谢成本。

**动力学分类**：揭示 Class 1（频率-强度连续）与 Class 2（不连续、有次阈振荡）神经元，用相平面分析刻画其编码与同步特性。

**扩展**：经 Wilfrid Rall 等扩展到树突，可生成钠棘波、NMDA 棘波等树突再生事件的模型（见 [[树突计算]]）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 四方程可精确再现动作电位 | 鱿鱼巨轴突电压钳 + 建模 | PMID:23055474 | 高 |
| 框架可扩展至树突再生事件 | H-H 形式主义 + 树突建模/实验 | PMID:36218068 | 高 |
| 单腔室模型的"现实性"需内容/准确性权衡 | 计算分析 | PMID:25856629 | 中 |

## 连接

- [[动作电位]] — 本模型定量描述的对象
- [[电压门控钠通道]] — 模型中钠电导动力学的分子对应
- [[树突计算]] — H-H 框架向树突的关键扩展

## 未解问题

- "最现实的单腔室 spike-initiation 模型"仍无定论（见来源 PMID:25856629）。

## 修订历史

- 2026-05-24 · 创建 · 基于《决策的解剖学：神经元如何在混沌的输入中找到它唯一的声音》· 初始置信度：高
- 2026-05-27 · 修订 · [[树突计算]] 页面已建立，填补此前悬空引用；source_articles 无变化，仅元数据更新

## 来源文章

- [[2026-05-24-axon-initial-segment]]

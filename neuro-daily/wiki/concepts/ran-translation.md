---
title: RAN 翻译
slug: ran-translation
domain: concepts
type: mechanism
status: emerging
confidence: medium
created: 2026-09-11
updated: 2026-09-11
revision_count: 1
dimensions: [molecular, cellular, disease]
related: [dipeptide-repeat-proteins, als-amyotrophic-lateral-sclerosis, c9orf72-repeat-expansion, integrated-stress-response]
prerequisites: [translation-initiation, mrna-processing]
opens_questions: [Q-als-03]
source_articles: [2026-09-11-als-tdp43-motor-neuron-selective-vulnerability]
key_sources: ["PMID:30120348", "PMC6417666"]
---

# RAN 翻译 (Repeat-Associated Non-ATG Translation)

> **一句话定义**：一种非经典翻译起始机制，允许重复序列 DNA/RNA 在无 ATG 起始密码子的情况下被翻译；在 C9orf72 ALS/FTD 中，将非编码 GGGGCC 重复扩增 RNA 翻译成五种二肽重复蛋白（DPR），且整合应激反应（ISR）悖论性地增强 RAN 翻译效率，创造压力→更多毒性 DPR 的恶性循环。

## 当前理解

我们现在认为，RAN 翻译是由重复核苷酸序列诱导的非经典翻译，独立于 ATG 起始密码子存在。这一机制最初在肌强直性营养不良（CTG 重复）和脆性 X 相关震颤/共济失调综合征（CGG 重复）中被发现，后来在 C9orf72 ALS/FTD 中得到充分研究（PMID:30120348 / PMC6417666）。

在 C9orf72 中，RAN 翻译在六个不同阅读框中进行（正义链 3 帧 + 反义链 3 帧），产生五种 DPR 蛋白（poly-GA、GP、GR、PA、PR）。RAN 翻译效率受多种因素调控，最关键的发现是**整合应激反应（ISR）的悖论性放大**：

细胞应激（包括 ALS 病理本身引起的蛋白质稳态崩溃）激活 eIF2α 磷酸化（ISR 核心步骤），在抑制整体帽依赖性翻译的同时，选择性**上调** RAN 翻译效率——这意味着应激越严重，生产的毒性 DPR 越多，形成自我放大的恶性循环。

## 关键机制

1. **无 ATG 翻译起始**：上游 CUG 密码子可作为替代起始位点；也有证据支持帽非依赖性机制
2. **正义链 + 反义链均被翻译**：GGGGCC 重复同时以两个方向产生 RNA，6 个阅读框产生 5 种 DPR（GP 在正反义链均可产生）
3. **ISR 上调 RAN 翻译**：eIF2α 磷酸化→整体 cap 依赖翻译下降→RAN 翻译相对比例上升（可能通过 IRES 样机制）

## 关键证据

| 主张 | 方法 | 来源 | 置信度 |
|------|------|------|--------|
| C9orf72 GGGGCC 重复经 RAN 翻译产生 5 种 DPR | 细胞系 + 患者尸检 | PMID:30120348 / PMC6417666 | 高 |
| ISR（eIF2α 磷酸化）悖论性上调 RAN 翻译 | 体外翻译系统 + 细胞系 | PMID:30120348 / PMC6417666 | 中-高 |

## 连接

- [[dipeptide-repeat-proteins]] — RAN 翻译的直接产物
- [[als-amyotrophic-lateral-sclerosis]] — RAN 翻译在 C9-ALS 中的核心病理作用
- [[tdp-43-pathology]] — DPR（poly-GR/PR）诱导 TDP-43 固态化

## 未解问题

- Q-als-03（中）：RAN 翻译产生的 DPR 对脊髓运动神经元是直接损伤还是经上运动神经元间接作用？

## 修订历史

- 2026-09-11 · 创建 · 基于《ALS TDP-43 文章》(#141) · 初始置信度：中（机制在模型中明确，但体内量化仍有争议）

## 来源文章

- [[2026-09-11-als-tdp43-motor-neuron-selective-vulnerability]]

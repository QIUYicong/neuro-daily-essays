---
title: 内源性阿片系统
slug: endogenous-opioids
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-14
updated: 2026-06-14
revision_count: 1
dimensions: [molecular, cellular, synaptic, brain-region, whole-brain-network, behavior, cognition]
related:
  - mu-opioid-receptor
  - kappa-opioid-receptor
  - descending-pain-modulation
  - nociception
  - placebo-analgesia
  - vta
  - nucleus-accumbens
  - dopamine-reward-prediction-error
  - anterior-cingulate-cortex
  - anterior-insula
prerequisites:
  - synaptic-transmission
  - gaba
  - action-potential
  - ion-channels
opens_questions:
  - Q-opioid-01
  - Q-opioid-02
  - Q-opioid-03
  - Q-opioid-04
source_articles:
  - "articles/2026-06-14-endogenous-opioid-system-analgesia-reward.md"
  - "articles/2026-06-14-nociception-pain-pathways.md"
key_sources:
  - "PMID:29852083 (Corder et al. 2018, Annu Rev Neurosci) - PMC6428583"
  - "PMC6224460 (Valentino & Volkow 2018, Neuropsychopharmacology)"
  - "PMID:31971607 (Lau et al. 2020, Br J Pharmacol) - PMC7174888"
  - "PMID:16120776 (Zubieta et al. 2005, J Neurosci) - PMC6725254"
---

# 内源性阿片系统 (Endogenous Opioid System)

> **一句话定义**：由四类 Gi/Go 偶联 GPCR（μ/δ/κ/NOP）及其内源性配体（β-内啡肽/脑啡肽/强啡肽/孤啡肽）构成的跨神经轴信号系统，通过抑制神经活动同时实现镇痛（PAG-RVM 回路）、奖励/社会联结（VTA-NAc 回路）和认知驱动镇痛（安慰剂效应）等多重功能。

## 当前理解

我们现在认为，内源性阿片系统是大脑中最重要的"痛苦-欢愉"双向调控网络，其核心逻辑是**通过抑制抑制性中间神经元（去抑制）来激活功能**：

1. **PAG 镇痛**：μ 受体激活 vlPAG GABAergic 中间神经元上的突触前 MOR → GABA 释放减少 → 去抑制下行投射神经元 → RVM OFF 细胞激活 → 脊髓背角抑制
2. **VTA 奖励**：μ 受体激活 VTA GABAergic 中间神经元 → 去抑制多巴胺神经元 → NAc 多巴胺上升 + NAc 壳 MOR 激活 → "喜欢"(liking)
3. **认知驱动镇痛**：期待/信念 → 内源性 β-内啡肽释放（ACC/dlPFC/NAc）→ MOR 激活 → 镇痛（PET 直接证据）
4. **社会联结**：欢笑/抚摸/音乐 → β-内啡肽释放 → MOR 奖励回路 → 社会联结维持

共同分子机制：Gi/Go 蛋白解离 → (a) Gα 抑制 AC → cAMP↓；(b) Gβγ 激活 GIRK → K⁺外流超极化；(c) Gβγ 抑制 Cav → Ca²⁺↓ → 递质释放减少

## 四类受体与四族肽

| 受体 | 基因 | 主要内源配体 | 主要功能 | 主要脑区 |
|------|------|-------------|---------|---------|
| μ（MOR/MOPR） | *Oprm1* | β-内啡肽、脑啡肽 | 镇痛、欢愉、呼吸抑制 | PAG, VTA, NAc, ACC |
| δ（DOR/DOPR） | *Oprd1* | 脑啡肽（met/leu-ENK） | 镇痛、抗焦虑、抗抑郁 | 纹状体, 皮层 |
| κ（KOR/KOPR） | *Oprk1* | 强啡肽 | 镇痛、**烦躁不快**、应激 | 纹状体, 下丘脑 |
| NOP | *Oprl1* | 孤啡肽/孤儿素 FQ | 双向调制（位置依赖） | PAG（拮抗），脊髓（镇痛） |

**前体蛋白**：
- POMC → β-内啡肽（弓状核/NTS）
- PENK → met-ENK / leu-ENK（广泛分布）
- PDYN → 强啡肽 A[1-17]（纹状体/下丘脑）
- PNOC → 孤啡肽/OFQ

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| μ 受体在 PAG 通过突触前去抑制激活镇痛 | 脑片电生理（miniEPSC/IPSC） | PMID:31971607 | 高 |
| 安慰剂激活 μ-阿片系统（ACC/dlPFC/NAc） | PET ¹¹C-卡芬太尼，n=14 | PMID:16120776 | 高 |
| MOR(-/-) 小鼠社交互动缺陷 | 基因敲除行为表型 | PMC6016638 | 高（动物） |
| Gi/Go 是三类受体的共同偶联 | 多实验室药理学共识 | PMID:29852083 | 高 |
| 慢性疼痛使 VTA MOR 脱敏 | 受体结合 + 行为学 | PMID:29852083 | 中 |

## 连接

- [[mu-opioid-receptor]] — μ受体详细机制
- [[kappa-opioid-receptor]] — κ受体与应激/负性情感
- [[descending-pain-modulation]] — PAG-RVM 镇痛回路（opioid 是核心执行者）
- [[nociception]] — 伤害感受与内源性阿片调制
- [[placebo-analgesia]] — 认知驱动的内源性阿片激活
- [[vta]] — VTA 中的 MOR 去抑制机制
- [[nucleus-accumbens]] — NAc 壳区阿片"喜欢"热点
- [[dopamine-reward-prediction-error]] — 多巴胺"想要"与阿片"喜欢"的分离

## 未解问题

- Q-opioid-01（高）：自然行为中不同脑区内源性阿片肽的**实时释放动态**（GRAB opioid sensors 的应用）
- Q-opioid-02（高）：μ/δ/κ 在情绪调节中的独立功能分工（需受体亚型选择性工具）
- Q-opioid-03（中）：跑步者愉悦感（runner's high）中阿片 vs 内源性大麻素的贡献比例
- Q-opioid-04（中）：社会联结中内啡肽与催产素激活的时序关系

## 修订历史

- 2026-06-14 · 创建 · 基于《同一把钥匙，三扇门》(#192) · 填补 descending-pain-modulation.md 中的悬空引用 · 初始置信度：高

## 来源文章

- [[2026-06-14-endogenous-opioid-system-analgesia-reward]] (#192)
- [[2026-06-14-nociception-pain-pathways]] (#190，涉及 PAG 下行镇痛的阿片机制）

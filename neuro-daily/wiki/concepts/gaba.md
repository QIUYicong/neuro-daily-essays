---
title: GABA（γ-氨基丁酸）
slug: gaba
domain: concepts
type: concept
status: established
confidence: high
created: 2026-08-10
updated: 2026-08-10
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, cognition, disease]
related: [pv-interneurons, sst-interneurons, vip-interneurons, ei-balance, cortical-interneuron-development, synaptic-transmission, action-potential, critical-period, ltp, nmda-receptor]
prerequisites: [synaptic-transmission, action-potential, membrane-potential]
opens_questions: []
source_articles: [2026-08-10-cortical-interneuron-tangential-migration]
key_sources: ["PMID:21154909", "PMID:18494250", "DOI:10.3389/fnins.2022.929469"]
---

# GABA（γ-氨基丁酸）(Gamma-Aminobutyric Acid)

> **一句话定义**：大脑中最主要的抑制性神经递质，由 GAD65/GAD67 酶从谷氨酸合成，通过 GABA-A（快速 Cl⁻ 通道）和 GABA-B（慢速 G 蛋白偶联）受体介导突触抑制，是皮层 E/I 平衡的分子基础。

## 当前理解

GABA 是中枢神经系统的主要抑制性神经递质，约占大脑突触的 20-30%。在成熟大脑中，GABA 通过使突触后细胞超极化来降低其放电概率：

**GABA 的方向性（发育依赖）**：
- **出生前/新生儿期**：GABA 是**去极化的**（兴奋性），因为细胞内 Cl⁻ 浓度高（KCC2 未成熟），GABA-A 通道开放 → Cl⁻ 外流 → 膜去极化
- **发育后期/成年期**：GABA 变为**超极化的**（抑制性），因为 BDNF/TrkB 信号上调 KCC2（Cl⁻/K⁺ 共转运体），降低细胞内 Cl⁻ → GABA-A 通道开放 → Cl⁻ 内流 → 膜超极化

这一方向翻转对于 PV 细胞功能成熟和关键期开放至关重要（[[critical-period]]）。

**GABAergic 中间神经元的多样性**：约占皮层神经元 20-25% 的 GABA 能神经元分为三大类，由不同发育起源决定（[[cortical-interneuron-development]]）：
- PV 型（MGE 来源）：快速放电，胞体/轴突始段抑制
- SST 型（MGE 来源）：树突抑制，Martinotti 形态
- 5HT3aR/VIP 型（CGE 来源）：脱抑制回路

## 关键机制

### 合成与分解
```
谷氨酸 → (GAD65/GAD67) → GABA → (GABA 转氨酶) → 琥珀酸半醛 → TCA 循环
```

### 受体分类

| 受体类型 | 机制 | 时间常数 | 功能 |
|----------|------|----------|------|
| GABA-A | 配体门控 Cl⁻ 通道 | 快（ms 级）| 快速抑制，决定放电窗口 |
| GABA-B | G 蛋白偶联，K⁺ 通道/腺苷酸环化酶 | 慢（100ms+）| 持续性超极化，突触前抑制 |

### 发育方向翻转

```
新生儿期：NKCC1 高表达 → [Cl⁻]ᵢ 高 → GABA-A 开放 → Cl⁻ 外流 → 去极化（兴奋！）
成年期：KCC2 高表达（BDNF 驱动）→ [Cl⁻]ᵢ 低 → GABA-A 开放 → Cl⁻ 内流 → 超极化（抑制）
```

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| PV/SST/5HT3aR 涵盖~100% GABA 能皮层神经元 | Cre 系统谱系追踪 | PMID:21154909 | 高 |
| GAD67 mRNA 减少于精神分裂症 DLPFC | 尸检 qPCR+原位杂交 | PMID:27336026 | 高 |
| BDNF/TrkB 驱动 KCC2 上调（GABA 方向翻转）| TrkB 敲除 + KCC2 表达分析 | DOI:10.3389/fnins.2022.929469 | 高 |

## 连接

- [[pv-interneurons]] — 皮层 PV+ GABAergic 细胞（MGE 来源）
- [[sst-interneurons]] — 皮层 SST+ GABAergic 细胞（MGE 来源）
- [[vip-interneurons]] — 皮层 VIP+ GABAergic 细胞（CGE 来源）
- [[ei-balance]] — GABA 是 E/I 平衡的"减法"端
- [[cortical-interneuron-development]] — GABA 能中间神经元的发育起源
- [[synaptic-transmission]] — GABA 突触传递的分子机制
- [[critical-period]] — GABA 方向翻转是关键期开放的先决条件
- [[ltp]] — GABA 能抑制调节 LTP 的诱导窗口

## 未解问题

（暂无独立条目；相关问题见 [[cortical-interneuron-development]] 和 [[ei-balance]]）

## 修订历史

- 2026-08-10 · 创建 · 填补图谱中"gaba"悬空引用 · 基于《皮层的第二种建筑学》(#109) + 整合 E/I 平衡等已有知识 · 初始置信度：高

## 来源文章

- [[2026-08-10-cortical-interneuron-tangential-migration]]

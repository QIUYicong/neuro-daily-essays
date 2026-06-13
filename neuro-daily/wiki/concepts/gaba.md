---
title: GABA（γ-氨基丁酸）
slug: gaba
domain: concepts
type: concept
status: established
confidence: high
created: 2026-08-10
updated: 2026-06-13
revision_count: 2
dimensions: [molecular, cellular, synaptic, microcircuit, cognition, disease]
related: [pv-interneurons, sst-interneurons, vip-interneurons, ei-balance, cortical-interneuron-development, synaptic-transmission, action-potential, critical-period, ltp, nmda-receptor, kcc2, gaba-polarity-switch, nkcc1, temporal-lobe-epilepsy]
prerequisites: [synaptic-transmission, action-potential, membrane-potential]
opens_questions: []
source_articles: [2026-08-10-cortical-interneuron-tangential-migration, 2026-06-13-kcc2-gaba-polarity-switch]
key_sources: ["PMID:21154909", "PMID:18494250", "DOI:10.3389/fnins.2022.929469", "PMID:9930699", "PMID:25234263", "PMID:31615901"]
---

# GABA（γ-氨基丁酸）(Gamma-Aminobutyric Acid)

> **一句话定义**：大脑中最主要的抑制性神经递质，由 GAD65/GAD67 酶从谷氨酸合成，通过 GABA-A（快速 Cl⁻ 通道）和 GABA-B（慢速 G 蛋白偶联）受体介导突触抑制，是皮层 E/I 平衡的分子基础。

## 当前理解

GABA 是中枢神经系统的主要抑制性神经递质，约占大脑突触的 20-30%。在成熟大脑中，GABA 通过使突触后细胞超极化来降低其放电概率：

**GABA 的方向性（发育依赖）**：
- **出生前/新生儿期**：GABA 是**去极化的**（兴奋性），因为 NKCC1（Na-K-2Cl 进口商）高表达使细胞内 Cl⁻ 浓度高（[Cl⁻]ᵢ ≈ 25-35 mM），KCC2 虽表达但因 Thr906/Thr1007 高磷酸化而几乎无活性；GABA-A 通道开放 → Cl⁻ 外流 → 膜去极化→ Ca²⁺ 内流 → 神经元成熟、早期同步（GDPs）
- **发育后期/成年期**：WNK-SPAK/OSR1 激酶级联活性下降 → KCC2 Thr906/T1007 脱磷酸化（>95%减少）→ KCC2 转运效率提升 >10 倍 → [Cl⁻]ᵢ 降至 5-10 mM → GABA-A 通道开放 → Cl⁻ 内流 → 膜超极化（抑制）
- **切换时间线**：遵循脊髓→延髓→丘脑→海马→新皮层的头尾梯度；大鼠新皮层约 P10-P15 完成；人类约妊娠晚期至生后数月（Rivera 1999, PMID:9930699；Watanabe 2019, PMID:31615901）

这一方向翻转对于 PV 细胞功能成熟和关键期开放至关重要（[[critical-period]]）。详细机制见 [[gaba-polarity-switch]] 和 [[kcc2]]。

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
| KCC2 直接因果决定 GABA 极性 | 海马锥体细胞 KCC2 反义抑制 → 恢复去极化 GABA | PMID:9930699 | 高 |
| T906/T1007 脱磷酸化激活 KCC2（>10x）| T906E/T1007E 敲入小鼠出生后 4-12h 死亡 | PMID:31615901 | 高 |

## 连接

- [[pv-interneurons]] — 皮层 PV+ GABAergic 细胞（MGE 来源）
- [[sst-interneurons]] — 皮层 SST+ GABAergic 细胞（MGE 来源）
- [[vip-interneurons]] — 皮层 VIP+ GABAergic 细胞（CGE 来源）
- [[ei-balance]] — GABA 是 E/I 平衡的"减法"端
- [[cortical-interneuron-development]] — GABA 能中间神经元的发育起源
- [[synaptic-transmission]] — GABA 突触传递的分子机制
- [[critical-period]] — GABA 方向翻转是关键期开放的先决条件
- [[ltp]] — GABA 能抑制调节 LTP 的诱导窗口
- [[kcc2]] — 决定 GABA 方向性的分子执行者
- [[gaba-polarity-switch]] — 兴奋→抑制转变的发育机制详细页
- [[temporal-lobe-epilepsy]] — TLE 中 KCC2 失效导致 GABA 部分兴奋化

## 未解问题

（暂无独立条目；相关问题见 [[cortical-interneuron-development]] 和 [[ei-balance]]）

## 修订历史

- 2026-08-10 · 创建 · 填补图谱中"gaba"悬空引用 · 基于《皮层的第二种建筑学》(#109) + 整合 E/I 平衡等已有知识 · 初始置信度：高
- 2026-06-13 · 修订 rev2 · 基于《大脑如何学会说"不"》(#189) · 大幅扩展 GABA 极性切换机制（加入 NKCC1/KCC2 比例、WNK-SPAK 磷酸化轴、区域时间线、GDPs）；新增连接 kcc2/gaba-polarity-switch/temporal-lobe-epilepsy；新增 3 条证据；来源 PMID:9930699, 31615901

## 来源文章

- [[2026-08-10-cortical-interneuron-tangential-migration]]
- [[2026-06-13-kcc2-gaba-polarity-switch]]

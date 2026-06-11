---
title: Reelin 信号通路
slug: reelin-signaling
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-11
updated: 2026-08-11
revision_count: 1
dimensions: [molecular, cellular, brain-region, cognition, disease]
related: [lissencephaly, cortical-neurogenesis, cortical-layers, ltp, alzheimers-disease, ei-balance, pv-interneurons, sst-interneurons, cortical-interneuron-development]
prerequisites: [cortical-neurogenesis, nmda-receptor, ltp]
opens_questions: [Q-lis-02]
source_articles: [2026-08-11-lissencephaly-cortical-migration-failure]
key_sources: ["PMID:23495356", "PMID:18255163", "PMID:31022460", "PMID:9321693"]
---

# Reelin 信号通路（Reelin Signaling）

> **一句话定义**：Reelin 是由胚胎期 Cajal-Retzius 细胞（成年期由中间神经元）分泌的大型糖蛋白，通过 VLDLR/ApoER2→Dab1 磷酸化→PI3K/LIMK1 双路径，在皮层 Inside-Out 建造中充当"到达并停止"的终止信号，同时在成年大脑中调节突触可塑性。

## 当前理解

Reelin（RELN 基因，7q22，~400 kDa 糖蛋白）是理解皮层 Inside-Out 层叠形成的关键分子之一：它不是"驱动"神经元迁移的分子，而是在神经元到达皮层板最外层时发出"脱离并就位"的信号。Reelin 缺失不妨碍神经元迁移，而是导致神经元无法正确停止，层序完全倒转（outside-in），这正是 reeler 小鼠突变的本质。

**双阶段功能**：
1. **发育期**：Cajal-Retzius 细胞分泌 Reelin 到边缘带，作为 Inside-Out 层叠的终止信号
2. **成年期**：中间神经元（可能是 SST+/VIP+ 亚型）继续分泌 Reelin，调节海马突触可塑性（AMPA 受体表面运输，LTP 阈值）

## 关键机制

### 受体复合体
Reelin 与两种脂蛋白受体形成三元复合体：
- **VLDLR**（Very Low Density Lipoprotein Receptor）
- **ApoER2（LRP8）**（Apolipoprotein E Receptor 2）
- 两种受体功能有部分重叠但不完全等价：ApoER2 在成年突触中尤为重要

受体激活后招募胞内接头蛋白 **Dab1（Disabled homolog 1）**至受体胞质尾部

### Dab1 磷酸化级联
Dab1 被 Src 家族激酶（Src、Fyn）在酪氨酸残基（Y198、Y220）磷酸化 → p-Dab1

**p-Dab1 下游双路径**：

**路径 A（微管稳定）**：
p-Dab1 → PI3K → AKT → 抑制 GSK3β → 减少 MAPT（tau）和 MAP1B 磷酸化 → **微管稳定** → 神经元前导突起维持结构

**路径 B（肌动蛋白调控）**：
p-Dab1 → LIMK1 激活 → 磷酸化 Cofilin（CFL1） → p-CFL1 抑制 actin 解聚 → **F-actin 稳定** → 前导突起动力学调控

**路径 C（与 LIS1 交叉）**：
p-Dab1 直接结合 LIS1 → 连通 Reelin 信号与 LIS1/dynein 微管牵引系统 → 协同驱动终止性跃迁

### "脱离并跃迁"（Detach and Go）模型
Cooper（2008，PMID:18255163）提出：

1. 迁移神经元前导突起到达边缘带
2. 前导突起探测到 Reelin 浓度峰值
3. Reelin 激活 Dab1 → p-Dab1 → 双路径
4. 神经元从放射状胶质纤维**脱离**
5. 胞体快速**跃迁**至皮层板顶部（somal translocation）
6. 神经元就位于当前最浅层，成为该出生时间段的该层"最新住户"

Reelin 缺失 → 步骤 3–5 不能发生 → 前导突起不脱离胶质 → 晚出生的神经元被迫越过早出生的神经元 → 层序倒置

### RELN 突变的表型
- **纯合 RELN 突变（人类）**：I 型无脑回伴小脑发育不全（LCH）
- **reeler 小鼠（纯合）**：皮层+海马+小脑三区域层叠倒置
- **scrambler 小鼠**（Dab1 突变，RELN 正常）：与 reeler 完全相同的皮层表型——证明 Dab1 是 Reelin 的下游必要效应器

## 成年 Reelin 的突触功能

成年海马中的中间神经元（可能主要是 SST+ 和 VIP+ 亚型，而非 PV+）继续分泌 Reelin。成年 Reelin：

- 调节 AMPA 受体（GluA1）的表面运输和突触侧向扩散
- 通过 ApoER2 在突触后密度中介导信号，影响 LTP 诱导阈值
- 可能通过 GSK3β 抑制路径，减少 tau 蛋白过度磷酸化

**精神分裂症中的 Reelin 降低**：前额叶皮层和海马 Reelin mRNA/蛋白水平降低 30–50%，可能与 GAD67（GABA 合成酶）同时降低，提示中间神经元功能损伤。但降低的细胞来源（哪种亚型？）和时序（发育期 vs 成年期？）仍不确定（PMID:31022460）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Reelin 作为 inside-out 终止信号 | reeler 小鼠出生日期标记实验（outside-in 表型） | PMID:9321693（Frotscher 1997） | 高 |
| Dab1 是 Reelin 下游效应器 | scrambler 小鼠（Dab1 突变，Reelin 正常）表型≡reeler | PMID:9364067 | 高 |
| VLDLR/ApoER2 是 Reelin 受体 | 双受体敲除小鼠重现 reeler 表型 | PMID:9619503 | 高 |
| p-Dab1 直接结合 LIS1 | 免疫共沉淀；Dab1/Lis1 双突变协同加重 | PMC3593794（PMID:23495356） | 高 |
| 成年 Reelin 调节 LTP | 体外 Reelin 处理海马切片增强 LTP | PMID:31022460（摘要） | 中 |
| 精神分裂症 Reelin 降低 | 尸检研究，多个实验室重复 | PMID:31022460（摘要） | 高（现象）；机制推断（低） |

## 连接

- [[lissencephaly]] — Reelin/RELN 突变直接导致 I 型无脑回伴小脑发育不全
- [[cortical-neurogenesis]] — Reelin 是 Inside-Out 规则的分子执行者
- [[ltp]] — 成年 Reelin 通过 ApoER2 调节 AMPA 受体运输，影响突触可塑性
- [[alzheimers-disease]] — Reelin→AKT→GSK3β↓路径可能对抗 tau 过度磷酸化（神经保护假说）
- [[ei-balance]] — Reelin 成年表达降低（精神分裂症）可能加剧 E/I 失衡
- [[pv-interneurons]] — Reelin 分泌来源（成年期可能非 PV+ 细胞，待确认）
- [[sst-interneurons]] — 成年 Reelin 产生细胞的主要候选亚型

## 未解问题

- Q-lis-02：成年 Reelin 的主要分泌细胞类型（SST+ vs VIP+ vs PV+？）及精神分裂症中的降低来源
- 关键期后 Reelin 通路激活是否可以逆转部分 lissencephaly 表型？

## 修订历史

- 2026-08-11 · 创建 · 基于文章"皮层建造的故障报告"(#110) · 初始置信度：高（发育机制高度确立）；成年突触功能中等置信度

## 来源文章

- [[2026-08-11-lissencephaly-cortical-migration-failure]]

---
title: Aβ寡聚体
slug: amyloid-beta-oligomers
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-08
updated: 2026-06-08
revision_count: 1
dimensions: [molecular, synaptic, cellular, disease]
related: [alzheimers-disease, nmda-receptor, ltp, calcineurin, camkii, ampa-receptor, hebbian-learning]
prerequisites: [nmda-receptor, ltp, synaptic-transmission]
opens_questions: [Q-abeta-oligomer-subtypes, Q-abeta-prpc-mechanism, Q-nmda-alzheimer]
source_articles: [2026-06-08-alzheimers-amyloid-synaptic-mechanism]
key_sources: ["PMID:11932745", "PMID:17360908", "PMID:21543591", "PMID:41929946"]
---

# Aβ寡聚体 (Amyloid-β Oligomers)

> **一句话定义**：由2-12个Aβ单体聚合形成的可溶性小聚合体，是阿尔茨海默病中LTP损伤和突触丢失的主要毒性物种，通过多条并行分子通路将海马突触的可塑性能力单向瓦解。

## 当前理解

我们现在认为，阿尔茨海默病的核心突触毒性来自可溶性Aβ寡聚体，而非不溶性淀粉样斑块（纤维/斑块）或Aβ单体。这一认识来自Walsh et al. 2002的关键实验：天然分泌（非人工合成）的Aβ寡聚体在注射到大鼠海马后显著抑制LTP，而单体和纤维无此效果。

寡聚体通过至少五条并行机制攻击突触可塑性：
1. PrPC/mGluR5/Fyn/NR2B轴 → NR2B异常激活 → Ca²⁺过载
2. 突触外NR2B激活 → p38 MAPK → CREB失活 → LTP基因表达阻断
3. Ca²⁺过载 → calcineurin/PP1过激活 → GluA1 AMPA受体大量内吞（CaMKII活性降低约60%）
4. BDNF/TrkB双重打击 + proBDNF/p75NTR激活 → 蛋白合成阻断 + 棘主动收缩
5. tau过磷酸化错位至突触后 → PSD-95/AMPA受体失稳 + GluA1运输受阻

这五条通路的共同效果是：把突触的可塑性双向调节（LTP⇌LTD）强制推向单向削弱，形成"LTP不可逆阻断"状态。

关键浓度：100-300 pM（Shankar et al. 2007）的天然分泌Aβ二聚体/三聚体，与AD患者脑脊液中Aβ的可测量浓度范围相近，在15天内引发约75%的树突棘密度丢失（早期可逆）。

## 关键机制

### 寡聚体的形成谱系

Aβ来自APP（淀粉样前体蛋白）通过β-分泌酶（BACE1）+γ-分泌酶的顺序切割。聚合谱系：
- **单体**（毒性低）
- **二聚体、三聚体**（毒性高，可溶性）← 主要毒性物种
- **四聚体至十二聚体**（ADDLs，amyloid-derived diffusible ligands，高毒性）
- **原纤维**（protofibril，介于寡聚体与纤维之间）
- **淀粉样纤维**（成熟斑块前体）
- **老年斑**（不溶性，低直接突触毒性）

寡聚体处于动态平衡中：寡聚体可以解聚为单体，也可以进一步聚合为纤维。病理条件下平衡向寡聚化方向偏移。

### 突触攻击通路的解剖学分离

突触内vs突触外NR2B的功能差异是Aβ毒性机制的核心逻辑节点：

| 位置 | 触发条件 | 下游信号 | 效果 |
|------|---------|---------|------|
| 突触内NR2B | 正常突触前释放 | CaMKII→ERK→CREB | LTP / 突触增强 |
| 突触外NR2B | Aβ寡聚体激活/谷氨酸溢出 | p38 MAPK→CREB磷酸酶 | LTP阻断 / 突触削弱 |

Aβ寡聚体优先激活突触外NR2B（Li et al. 2011），将信号天平推向"LTP阻断"侧。

### 关键数据点

- 毒性物种确认：Walsh et al. 2002——天然分泌寡聚体（非单体/纤维）抑制体内LTP (PMID:11932745)
- 浓度阈值：100-300 pM Aβ二/三聚体 → 75%棘密度丢失（15天）；可逆（Shankar et al. 2007, PMID:17360908）
- CaMKII：活性降低约60%（Behroozi et al. 2026, PMC:13039067）
- NR2B：通道开放概率升高约40%（PMC:13039067，4-HNE介导）
- 临床：靶向寡聚体抗体减缓早期AD认知衰退；斑块清除量与临床获益不相关（"斑块清除悖论"，PMC:8231952）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 天然分泌寡聚体（非单体/纤维）抑制体内LTP | 大鼠海马内注射+在体电生理 | Walsh et al. 2002, PMID:11932745 | 高 |
| 生理浓度Aβ二/三聚体引发75%棘丢失，可逆 | 活体细胞成像，15天暴露+撤药恢复 | Shankar et al. 2007, PMID:17360908; PMC:6672572 | 高 |
| 突触外NR2B激活是LTP阻断的分子机制 | NR2B阻断剂救援LTP；脑片电生理+生化 | Li et al. 2011, PMID:21543591 | 高 |
| CaMKII活性降低60%，NR2B通道开放概率升高40% | 定量生化+电生理 | Behroozi et al. 2026, PMC:13039067 | 中（综述引用，需原始文献确认） |

## 连接

- [[alzheimers-disease]] — Aβ寡聚体是AD的核心毒性物种，驱动AD突触病理
- [[nmda-receptor]] — 突触外NR2B-NMDA受体是Aβ寡聚体攻击LTP的核心分子靶点
- [[ltp]] — LTP的多条诱导/维持通路均被Aβ寡聚体干扰或阻断
- [[calcineurin]] — Aβ诱导的Ca²⁺过载过激活calcineurin，驱动AMPA受体内吞（LTP的主要表达机制被逆转）
- [[camkii]] — CaMKII活性被Aβ抑制，LTP诱导的关键激酶失效
- [[ampa-receptor]] — AMPA受体内吞是calcineurin过激活的直接后果，也是突触强度崩解的执行步骤

## 未解问题

- Q-abeta-oligomer-subtypes：不同大小（二聚体/三聚体/十二聚体）和不同构象的Aβ寡聚体的毒性机制是否不同？哪种亚型是临床干预的最优靶点？
- Q-abeta-prpc-mechanism：PrPC-mGluR5复合物如何选择性结合Aβ寡聚体而非单体？结合的分子结构基础是什么？
- Q-nmda-alzheimer：在AD进程中，突触内vs突触外NR2B受体的比例是否发生重分布？是否可以通过选择性药物恢复其平衡？

## 修订历史

- 2026-06-08 · 创建 · 基于《记忆的分子遗忘》一文 · 建立Aβ寡聚体条目 · 初始置信度：高

## 来源文章

- [[2026-06-08-alzheimers-amyloid-synaptic-mechanism]]

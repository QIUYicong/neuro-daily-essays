---
title: 钙调磷酸酶（Calcineurin / PP2B）
slug: calcineurin
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-04
updated: 2026-06-04
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [ltd, ltp, nmda-receptor, ampa-receptor, camkii]
prerequisites: [action-potential, synaptic-transmission, nmda-receptor]
opens_questions: [Q-ltd-nmda-metabotropic]
source_articles: [2026-06-04-ltd-long-term-depression]
key_sources: ["PMID:24183021", "PMID:19169250"]
---

# 钙调磷酸酶（Calcineurin / PP2B）

> **一句话定义**：钙/钙调素激活的丝氨酸-苏氨酸磷酸酶，在低至中等 Ca²⁺ 浓度下优先被激活，通过激活 PP1 去磷酸化 AMPA 受体相关底物，是 NMDA 受体依赖型 LTD 的关键分子开关。

## 当前理解

我们现在认为，钙调磷酸酶（Protein Phosphatase 2B，PP2B）是突触可塑性方向性决定的核心分子之一。在同一个突触处，Ca²⁺ 进入的**量**决定激活哪条下游通路：
- **高 Ca²⁺ 脉冲**（LTP 诱导协议）→ 优先激活低亲和力、高活性的 CaMKII → LTP
- **中低 Ca²⁺**（LTD 诱导协议）→ 优先激活高亲和力的钙调磷酸酶/PP2B → LTD

钙调磷酸酶对 Ca²⁺-钙调素（CaM）的亲和力高于 CaMKII，因此在 Ca²⁺ 浓度较低时就被激活，扮演"Ca²⁺ 量规"中的低阈值感受器角色。激活后，PP2B 激活 PP1（蛋白磷酸酶 1），后者对 GluA1 亚基的 Ser831 和 Ser845 位点去磷酸化，启动 AMPA 受体内吞。

关键洞察：钙调磷酸酶的**空间定位**与其功能同等重要。AKAP150（A 激酶锚定蛋白 150）通过与 PSD-95 结合，将钙调磷酸酶精确定位于 NMDA 受体旁——这使它在 Ca²⁺ 进入后能迅速感知局部高浓度，选择性激活（Bhattacharyya et al., 2009）。

## 关键机制

### Ca²⁺ 浓度感受与亲和力差异

| 酶 | Ca²⁺ 亲和力 | LTP vs LTD 倾向 |
|----|-----------|----------------|
| 钙调磷酸酶（PP2B） | 高（Kd ~ 数十 nM） | 低 Ca²⁺ 时激活 → LTD |
| CaMKII | 低（Kd ~ 数百 nM） | 高 Ca²⁺ 时激活 → LTP |

注：两种酶之间存在竞争性激活关系；实际阈值受钙调素（CaM）总量、空间微域等多因素影响，体内边界比上表更模糊。

### 磷酸酶级联

```
Ca²⁺（低-中等）
  ↓
PP2B（钙调磷酸酶）激活（Ca²⁺-CaM 结合）
  ↓
PP1 激活（PP2B 使 PP1 抑制因子 DARPP-32/Inhibitor-1 去磷酸化）
  ↓
GluA1 Ser831 去磷酸化（原 CaMKII 磷酸化位点）
GluA1 Ser845 去磷酸化（原 PKA 磷酸化位点）
  ↓
AMPA 受体从 PSD 横向扩散 → 网格蛋白介导内吞 → LTD
```

### AKAP150 空间定位机制

PSD-95 的 SH3-GK 结构域与 AKAP150 结合，AKAP150 同时结合钙调磷酸酶（PP2B）和 PKA。这一复合体将两种相互拮抗的酶都定位在突触后致密区（PSD），使它们都能感知突触处的 Ca²⁺ 变化并产生对抗性效应：
- PKA：磷酸化 GluA1 Ser845，倾向于维持/增强受体在突触（LTP 有利）
- PP2B：去磷酸化 GluA1 Ser845，倾向于减弱受体在突触（LTD 有利）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| PP2B 抑制阻断 NMDA-LTD | FK506、cyclosporin A 等磷酸酶抑制剂在海马切片中阻断低频刺激诱导的 LTD | PMID:24183021 (PMC4195488) | 高 |
| AKAP150/PP2B 定位是 NMDA-LTD 所需 | AKAP150 缺失 PP2B 结合域的突变体（ΔAKAP-PP2B）阻断 LTD | PMID:19169250 (PMC2694745) | 高 |
| PP2B 激活 PP1（通过 I1/DARPP-32 去磷酸化） | DARPP-32 磷酸化状态在 LTD 诱导时降低 | PMID:24183021 (PMC4195488) | 中-高 |

## 连接

- [[ltd]] — PP2B 是 NMDA-LTD 磷酸酶级联的第一个效应器
- [[ltp]] — PP2B（LTD 磷酸酶）与 CaMKII（LTP 激酶）构成突触双向调控的核心对立对
- [[camkii]] — 与 PP2B 竞争 Ca²⁺-CaM，亲和力更低但活性更强；高 Ca²⁺ 时 CaMKII"赢"
- [[nmda-receptor]] — NMDA 受体的 Ca²⁺ 内流是 PP2B 激活的上游触发
- [[ampa-receptor]] — PP2B 通过 PP1 使 GluA1 去磷酸化，驱动 AMPAR 内吞

## 未解问题

- Q-ltd-nmda-metabotropic：若 NMDA 受体无需开放离子通道即可触发 LTD（"代谢型 NMDA 受体"假说），PP2B 的激活来源是什么？是内质网 Ca²⁺？还是与离子流无关的构象变化信号？

## 修订历史

- 2026-06-04 · 创建 · 基于《遗忘的精准：LTD 文章》· 初始置信度：高

## 来源文章

- [[2026-06-04-ltd-long-term-depression]]

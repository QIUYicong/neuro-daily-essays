---
title: AMPA 受体
slug: ampa-receptor
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-26
updated: 2026-06-04
revision_count: 2
dimensions: [molecular, synaptic]
related: [nmda-receptor, ltp, ltd, camkii, calcineurin, arc-arg31, synaptic-transmission, hebbian-learning, tarp-auxiliary-subunit]
prerequisites: [synaptic-transmission, action-potential]
opens_questions: [Q-ampa-receptor-silent-synapse, Q-ampa-glua1-atd-partners]
source_articles: [2026-05-26-nmda-receptor-ltp, 2026-06-04-ltd-long-term-depression]
key_sources: ["PMID:30359599", "PMID:34271016", "PMID:22510460", "PMID:24183021", "PMID:19169250"]
---

# AMPA 受体 (AMPA Receptor / AMPAR)

> **一句话定义**：突触快速兴奋传递的主要执行者，无 Mg²⁺ 阻断、衰减极快（~2–5 ms）；其在突触后膜上的数量是 LTP 期间突触权重增强的主要决定因素。

## 当前理解

我们现在认为，AMPA 受体是突触快速 EPSP 的核心来源。与 NMDA 受体不同，AMPA 受体不需要突触后去极化即可开放——谷氨酸结合后在几毫秒内即完成激活和失活循环，产生快速的突触电流。AMPA 受体在突触后膜上的数量并非固定，而是随活动状态动态调节：LTP 时大量插入（突触权重增强），LTD 时从突触移除（突触权重减弱）。这一动态性使 AMPA 受体成为突触可塑性的"物理实现"——突触权重在生化上等价于突触后膜 AMPA 受体的数量和电导。

## 关键机制

### 亚基组成与分工（分子层面）

AMPA 受体是由 GluA1–4 亚基组成的四聚体（通常为二聚体的二聚体）。成熟海马 CA1 区：
- ~80% 为 **GluA1/GluA2 异聚体**（高表达）
- ~20% 为 **GluA2/GluA3 异聚体**（较少）

**GluA1 vs GluA2 的差异**：
- GluA1（长尾 C 末端）：负责**活动依赖性**突触运输；LTP 诱导时主要被插入
- GluA2/GluA3（短尾 C 末端）：负责**组成性循环**（constitutive cycling），维持基础突触传递
- GluA2 含有 Arg（R）于 Q/R 编辑位点，使受体对 Ca²⁺ 不通透（Ca²⁺-impermeable AMPARs）
- GluA2 缺失的受体（GluA1 同聚体）对 Ca²⁺ 通透——这类受体可能在某些可塑性状态下增加以提高 Ca²⁺ 流入

### LTP 期间 AMPA 受体插入（突触层面）

1. CaMKII 磷酸化 **GluA1 S831** → 提高单通道电导，促进 GluA1 靶向 PSD
2. AMPA 受体从**再循环内体**（recycling endosome）通过**胞吐**到达树突干非突触区
3. 受体通过**横向扩散（lateral diffusion）**从胞外膜迁移进入突触后致密区（PSD）
4. **TARP（如 Stargazin, TARP γ-2）**与 PSD-95 的 PDZ 结构域相互作用，将受体**锚定**于突触"槽位"（synaptic slot）

### 沉默突触与 AMPA 受体（突触层面）

沉默突触（silent synapse）只含 NMDA 受体，无 AMPA 受体 → 静息电位下功能沉默。LTP 诱导后，AMPA 受体插入这类突触 → 突触觉醒。这可能是早期学习和发育期突触精炼的关键机制。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| LTP 主要通过 AMPA 受体插入（非释放增加）表达 | MK-801 法、PPF 不变、星形胶质细胞转运体电流不变 | PMID:22510460 (PMC3367554) | 高 |
| CaMKII 磷酸化 GluA1 S831 并驱动其突触插入 | CaMKII 突变 + 磷酸化特异性抗体 | PMID:30359599 (PMC6214363) | 高 |
| LTP 需要 GluA1，但不需要 GluA2 | GluA1/GluA2 条件性敲除实验 | PMID:34271016 (PMC9122021) | 高 |
| TARP-PSD95 相互作用锚定 AMPA 受体于突触 | Stargazin 突变 + 电生理 | PMID:34271016 (PMC9122021) | 高 |

### LTD 期间 AMPA 受体内吞（突触层面）

LTD 时，AMPA 受体从突触后膜内吞，是突触权重降低的物理实现（Huganir & Nicoll, 2013，PMC4195488）：

1. **GluA1 Ser831/Ser845 去磷酸化**（PP2B→PP1 级联）→ 受体稳定性降低，开始横向扩散离开 PSD
2. **GluA2 Ser880 磷酸化**（PKC）→ 破坏 GluA2-GRIP1/2 结合（突触锚点丧失）→ 转为 PICK1 结合 → 内吞
3. **Arc 蛋白**（mGluR-LTD 路径）→ Arc 与 dynamin/endophilin 结合 → 加速网格蛋白包被小泡形成 → AMPAR 内化

**重要争议**：GluA2/GluA3 双敲除小鼠海马 LTD 仍然正常，表明 GluA2 Ser880 路径不是唯一的 LTD 表达机制，存在 GluA2 非依赖的备用内吞路径（分子身份未明，→ Q-ltd-glua2-redundancy）。

内化后受体进入早期内体：可被再循环回突触（LTP 时优先）或被溶酶体降解（LTD 维持时可能）。

## 连接

- [[nmda-receptor]] — NMDA 受体 Ca²⁺ 内流激活 CaMKII，后者驱动 AMPA 受体插入；低 Ca²⁺ 时激活 PP2B，驱动内吞
- [[ltp]] — AMPA 受体插入（exocytosis → lateral diffusion → PSD 锚定）是 LTP 在突触后的主要表达机制
- [[ltd]] — AMPA 受体内吞（endocytosis）是 LTD 在突触后的主要表达机制；GluA1 去磷酸化 + GluA2 Ser880 磷酸化是关键开关
- [[camkii]] — CaMKII 磷酸化 GluA1 S831（LTP），与 PP2B-PP1 去磷酸化相对立（LTD）
- [[calcineurin]] — PP2B/PP1 级联在 LTD 时去磷酸化 GluA1 Ser831/845，驱动内吞
- [[arc-arg31]] — Arc 是 mGluR-LTD 路径中促进 AMPAR 内吞的执行蛋白
- [[synaptic-transmission]] — AMPA 受体是快速 EPSP 的主要产生者
- [[tarp-auxiliary-subunit]] — TARP 是 AMPA 受体靶向突触的关键辅助亚基（待建页面）

## 未解问题

- Q-ampa-receptor-silent-synapse：沉默突触觉醒中，AMPA 受体的首个分子被插入的精确分子触发事件是什么？
- Q-ampa-glua1-atd-partners：GluA1 氨基末端结构域（ATD）通过哪些跨突触配体（neuronal pentraxins？细胞黏附分子？）建立突触外的相互作用？

## 修订历史

- 2026-05-26 · 创建 · 基于《NMDA 受体：突触的巧合检测器》一文 · 初始置信度：高
- 2026-06-04 · 修订 · 基于《LTD 文章》· 新增"LTD 期间 AMPA 受体内吞"机制段落；GluA2 Ser880 磷酸化→PICK1 路径；Arc 在 mGluR-LTD 中的内吞执行角色；GluA2 双敲除后 LTD 正常的争议（备用内吞路径）；related 增加 ltd、calcineurin、arc-arg31；key_sources 新增 PMC4195488, PMC2694745

## 来源文章

- [[2026-05-26-nmda-receptor-ltp]]
- [[2026-06-04-ltd-long-term-depression]]

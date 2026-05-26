---
title: CaMKII（钙/钙调素依赖性蛋白激酶 II）
slug: camkii
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-05-26
updated: 2026-05-26
revision_count: 1
dimensions: [molecular, synaptic]
related: [nmda-receptor, ltp, ampa-receptor, synaptic-transmission]
prerequisites: [nmda-receptor, synaptic-transmission]
opens_questions: [Q-camkii-subunit-exchange, Q-camkii-maintenance-lifetime]
source_articles: [2026-05-26-nmda-receptor-ltp]
key_sources: ["PMID:34908526", "PMID:22510460", "PMID:30359599"]
---

# CaMKII（钙/钙调素依赖性蛋白激酶 II）

> **一句话定义**：突触后致密区（PSD）中浓度极高的丝氨酸/苏氨酸蛋白激酶，Ca²⁺ 内流时被激活，通过 T286 自磷酸化形成持续活化状态，是 LTP 诱导和维持的关键效应器。

## 当前理解

我们现在认为，CaMKII 是突触可塑性的"分子记忆开关"。Ca²⁺/CaM 激活 CaMKII 后，其 T286 位点的自磷酸化使激酶在 Ca²⁺ 消失后仍保持自主活化——这一特性使短暂的 Ca²⁺ 脉冲被"编码"为持续性的激酶活化。CaMKII 磷酸化 GluA1 S831，提高 AMPA 受体电导并驱动其突触插入，是 LTP 早期表达的核心机制。

**关键修正（2021）**：CaMKII 不只参与 LTP 诱导，也是已建立 LTP 的**维持**所必需的。在已完成 LTP 的突触上持续抑制 CaMKII，LTP 会完全逆转。这意味着 CaMKII 的持续活化是 E-LTP 存储机制的核心组成部分，而不仅仅是一个启动信号。

## 关键机制

### 激活级联（分子层面）

1. NMDA 受体开放 → Ca²⁺ 内流进入突触后棘
2. Ca²⁺ 结合**钙调素（calmodulin）**，形成 Ca²⁺/CaM 复合物
3. Ca²⁺/CaM 结合并激活 CaMKII（构象变化，解除自抑制结构域）
4. **CaMKII T286 自磷酸化**（催化亚基之间互相磷酸化）→ 形成**自主激活状态**（即使 Ca²⁺ 撤除后仍维持活性）

### 构型（分子层面）

CaMKII 是由 12 个亚基组成的环形全酶（六聚体或十二聚体）。激活后，亚基间自磷酸化可能使磷酸化状态在蛋白质更新中传递（**亚基交换假说**，subunit exchange），这是"持久记忆"机制的一种可能解释。

### 下游效应（突触层面）

- 磷酸化 **GluA1 S831**：提高 AMPA 受体单通道电导；促进 GluA1 靶向突触
- 磷酸化其他 PSD 蛋白（如 SynGAP），重塑突触蛋白质组
- 招募更多 AMPA 受体至 PSD 中的"槽位"

### CaMKII 在 LTP 维持中的必要性

- 使用特异性 CaMKII 抑制剂（myr-CN27）在 LTP 建立后处理切片：LTP 完全逆转
- AMPAR 电流减少 ~50%，但 NMDAR 电流不变（选择性的突触后效应）
- 此效应依赖 NMDA 受体的存在（GluN1 敲除神经元不受影响）
（Tao et al., 2021, PMC8798046）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| CaMKII T286 自磷酸化形成自主活化态 | T286A 突变消除 LTP，生化自磷酸化实验 | PMID:22510460 (PMC3367554) | 高 |
| CaMKII 对 LTP 维持必需（非仅诱导） | myr-CN27 处理后完全逆转已建立 LTP | PMID:34908526 (PMC8798046) | 高 |
| CaMKII 磷酸化 GluA1 S831 | 磷酸化特异性抗体 + 点突变实验 | PMID:30359599 (PMC6214363) | 高 |
| CaMKII 占 PSD 总蛋白的 ~8.5% | 定量质谱 | PMID:34271016 (PMC9122021) | 高 |

## 连接

- [[nmda-receptor]] — Ca²⁺ 内流激活 CaMKII，CaMKII 是 NMDA 受体下游的第一个主要效应器
- [[ltp]] — CaMKII 是 LTP 诱导和维持的必要分子机器
- [[ampa-receptor]] — CaMKII 磷酸化 GluA1 S831，驱动 AMPA 受体插入突触

## 未解问题

- Q-camkii-subunit-exchange：CaMKII 的亚基交换假说（磷酸化状态在蛋白质更新中通过亚基替换传递）是否在体内得到验证？这能否解释 E-LTP 在蛋白降解情况下的持久性？
- Q-camkii-maintenance-lifetime：CaMKII 的自主活化状态在体内能持续多久？与记忆的实际时间跨度相比有多大差距？

## 修订历史

- 2026-05-26 · 创建 · 基于《NMDA 受体：突触的巧合检测器》一文 · 初始置信度：高

## 来源文章

- [[2026-05-26-nmda-receptor-ltp]]

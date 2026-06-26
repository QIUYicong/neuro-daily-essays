---
title: 反弹增强
slug: rebound-potentiation
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-10-09
updated: 2026-10-09
revision_count: 1
dimensions: [molecular, synaptic, cellular, microcircuit]
related: [molecular-layer-interneuron, purkinje-cell, cerebellar-ltd, camkii, motor-learning, cerebellum]
prerequisites: [inhibitory-synapse, camkii, cerebellar-ltd, purkinje-cell]
opens_questions: [Q-rp-01, Q-rp-02]
source_articles: [2026-10-09-mli-cerebellar-interneuron-plasticity]
key_sources: ["PMID:24600347", "PMID:26930485", "PMID:12019316", "PMID:26179122"]
---

# 反弹增强 (Rebound Potentiation, RP)

> **一句话定义**：浦肯野细胞（PC）在被攀爬纤维驱动去极化之后，对后续 GABA 输入（来自分子层中间神经元）的响应持久增强的现象，机制为 Ca²⁺ → β-CaMKII → GABARAP 磷酸化 → GABA_A 受体数量增加；因果证据表明 RP 对小脑运动学习（VOR 适应）是必要的。

## 当前理解

我们现在认为，反弹增强（Rebound Potentiation，RP）是小脑皮层平行纤维-浦肯野细胞 LTD（PF-PC LTD）之外的**第二条长时程可塑性机制**，两者以互补的方式共同利用攀爬纤维（CF）误差信号，实现运动学习所需的持续 PC 输出抑制。

RP 与 PF-PC LTD 的关键区别：
- **LTD**：减弱兴奋性 PF→PC 突触权重（AMPA 受体内吞）
- **RP**：增强抑制性 MLI→PC 突触效能（GABA_A 受体数量增加）

两种机制都依赖 CF 激活，都最终减少 PC 在特定运动情景下的输出，都属于活动依赖性（activity-dependent）的长时程可塑性。当 LTD 被遗传性阻断时，RP 仍可独立运作，提供部分代偿（转基因阻断 RP 会损伤 VOR 适应，说明 RP 自身的因果贡献不可被 LTD 完全取代）。

## 关键机制

### 诱导条件

PC 需要经历**去极化**（通常来自攀爬纤维复杂放电），随后的 GABA 输入（来自 MLI）对 PC 的抑制效果才会被持久增强。单纯 PC 去极化（无后续 GABA）或单纯 GABA 输入（无去极化）均不能诱导 RP。这使 RP 具有**时序依赖性**：去极化必须先于 GABA 刺激。

### 分子级联

```
CF 激活 PC
   ↓ 复杂放电
大量 Ca²⁺ 内流（P/Q 型 VGCC 为主）
   ↓ 结合钙调蛋白（CaM）
β-CaMKII 激活（Ca²⁺-CaM 亲和力：β >> α）
   ↓ 磷酸化
GABARAP（GABA_A 受体关联蛋白）
   ↓ 构象改变
GABA_A 受体向突触膜定向招募（胞吐/插入）
   ↓
突触 GABA_A 受体数量 ↑
   ↓
同等 GABA 输入 → 更大抑制电流（RP）
```

（综述：Hirano 2014，PMID:24600347，PMC3927423）

### 量子机制（Ono et al. 2016）

非稳态涨落分析（NSFA）揭示：
- RP 增加**受体数量**，单通道电导不变
- 与 ATP 诱导的 LTP 形成对照：后者增加**单通道电导**，数量不变
- 两种机制独立，可叠加

### 调控开关：α/β-CaMKII 比值

| 状态 | 结果 |
|------|------|
| β-CaMKII 占优 | RP 容易诱导（β 对 Ca²⁺-CaM 亲和力高） |
| α-CaMKII 过量 | RP 受抑制（α 竞争性占用激酶活性但对 GABARAP 效果不同） |

这提示细胞可通过调节 CaMKII 亚型比值，设定自身的 RP 增益阈值——一种内在的"可塑性门控"。

### 空间特异性（He et al. 2015）

RP 在 MLI→PC 突触上不是均匀分布：
- **篮状细胞（basket cell）→PC 胞体/AIS 突触**：可发生，依赖 β2-GABA_A + CaMKII
- **星状细胞（stellate cell）→PC 树突突触**：不发生同类 RP

这意味着 RP 主要增强 PC 近胞体/AIS 处的抑制门控，对动作电位发放阈值的影响比树突整合更直接。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| RP 依赖 CaMKII 激活 | CaMKII 抑制剂阻断 RP | PMID:12019316 | 高 |
| RP 依赖 β-CaMKII → GABARAP 磷酸化 | β-CaMKII 过表达增强 RP；GABARAP 结合位点突变消除 RP | PMID:24600347 | 高 |
| 阻断 RP（γ2 肽链转基因）→ VOR 适应受损 | 转基因小鼠行为学（因果证据）| PMID:24600347 | 高 |
| RP 增加 GABA_A 受体数量（而非电导）| NSFA 分析 | PMID:26930485（PMC4773004）| 高 |
| BC 特异性 RP：β2-GABA_A + CaMKII 依赖 | 脑片膜片钳 + 选择性药理学 | PMID:26179122 | 高 |

## 连接

- [[molecular-layer-interneuron]] — MLI 是 RP 的前突触来源（提供 GABA）；RP 发生在 MLI→PC 突触的后突触侧
- [[cerebellar-ltd]] — 与 PF-PC LTD 互补：两者共同利用 CF 信号减少 PC 输出
- [[camkii]] — β-CaMKII 是 RP 诱导的关键激酶
- [[purkinje-cell]] — RP 发生在 PC 上；PC 去极化是诱导条件
- [[climbing-fiber]] — CF 激活提供 RP 诱导所需的去极化和 Ca²⁺ 信号
- [[cerebellum]] — RP 是小脑皮层多层可塑性系统的抑制性 LTP 组成部分

## 未解问题

- **Q-rp-01**（高优先级）：当 PF-PC LTD 和 RP 同时被特异性阻断时，运动学习缺陷是否叠加？这将直接检验两者是否真正代偿。
- **Q-rp-02**（中优先级）：RP 的时间尺度（数十分钟至数小时）与运动学习的快速早期阶段（数分钟内）是否匹配？RP 是否主要负责运动技能的晚期巩固而非早期快速适应？

## 修订历史

- 2026-10-09 · 创建 · 基于《误差的双重利用：分子层中间神经元如何在浦肯野细胞的阴影里构建第二条学习通道》（文章 #169）· 初始置信度：高（转基因因果证据；机制有多篇独立来源支持）

## 来源文章

- [[2026-10-09-mli-cerebellar-interneuron-plasticity]]

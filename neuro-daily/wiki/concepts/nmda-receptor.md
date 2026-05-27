---
title: NMDA 受体
slug: nmda-receptor
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-26
updated: 2026-05-27
revision_count: 2
dimensions: [molecular, synaptic, cellular, cognition]
related: [ampa-receptor, ltp, hebbian-learning, synaptic-transmission, voltage-gated-sodium-channel, calcium-channel, camkii, dendritic-computation, pyramidal-neuron]
prerequisites: [synaptic-transmission, action-potential, membrane-potential]
opens_questions: [Q-nmda-coincidence-window, Q-glun2-switch-development, Q-nmda-alzheimer]
source_articles: [2026-05-26-nmda-receptor-ltp, 2026-05-27-dendritic-computation]
key_sources: ["PMID:22510460", "PMID:30037851", "PMID:6306230"]
---

# NMDA 受体 (NMDA Receptor / N-Methyl-D-Aspartate Receptor)

> **一句话定义**：同时需要谷氨酸结合（突触前活动）和突触后膜去极化（Mg²⁺ 阻断的解除）才能开放的离子通道；通过双重门控实现 Hebb 型巧合检测，是 LTP 诱导的必要条件。

## 当前理解

我们现在认为，NMDA 受体是突触后膜上的一类离子型谷氨酸受体，其核心特殊性在于**双重门控机制**：它不仅需要配体（谷氨酸 + 甘氨酸）结合，还需要突触后膜**去极化**来解除通道内的 Mg²⁺ 阻断，才能允许 Ca²⁺ 内流。这两个条件缺一不可，使 NMDA 受体成为一个分子级别的"逻辑与"（AND）门，即**巧合检测器**——只有当突触前和突触后活动在毫秒级时间窗内同时发生，它才被激活。Ca²⁺ 内流激活下游级联（CaMKII 等），最终导致 AMPA 受体大量插入突触膜，突触传递效率持久增强，即长时程增强（LTP）。这一机制在分子层面精确实现了 Hebb 学习规则。

## 关键机制

### 亚基组成

NMDA 受体是四聚体，标准构型为两个 GluN1 + 两个 GluN2，按 1-2-1-2 交替排列：
- **GluN1**：结合共激动剂**甘氨酸**（或 D-丝氨酸）；脑中甘氨酸浓度相对稳定，使谷氨酸成为主要时间控制因子
- **GluN2**（A/B/C/D 四种亚型）：结合**谷氨酸**；决定通道的动力学特性

**GluN2 亚型的关键差异**（分子层面）：

| 亚型 | 衰减时间常数 | 开放概率 | 主要表达阶段 |
|------|------------|---------|------------|
| GluN2A | ~40–50 ms | ~0.5 | 成年 |
| GluN2B | ~300–400 ms | ~0.1 | 幼年→成年均有 |
| GluN2D | ~4 s | <0.02 | 丘脑、脑干 |

GluN2B 在幼年期高表达，其更长的衰减时间常数意味着更宽的时间整合窗口，可能是关键期可塑性的分子基础之一。

### Mg²⁺ 阻断——电压感应锁（突触/分子层面）

静息状态（~–70 mV）下，Mg²⁺ 嵌入通道孔（M2 loop 顶端的 Q/R/N 位点），物理阻断 Ca²⁺ 通过。GluN1/2A 和 GluN1/2B 受体的 IC₅₀ ≈ 2 µM（–100 mV），几乎完全被阻断。去极化时 Mg²⁺ 被推出，通道解除阻断，Ca²⁺ 才能内流。

**双重门控逻辑**：
1. 化学锁：谷氨酸 + 甘氨酸同时结合
2. 电压锁：突触后膜去极化（如 bAP 传回树突）解除 Mg²⁺ 阻断
→ 两者同时满足 = Ca²⁺ 内流 = 可塑性触发

### Ca²⁺ 内流的下游效应（突触→认知层面）

- 高 Ca²⁺ → 优先激活 **CaMKII**（需要高 Ca²⁺/CaM 浓度）→ LTP（突触增强）
- 低 Ca²⁺ → 优先激活**磷酸酶**（calcineurin，对 Ca²⁺/CaM 亲和力更高）→ LTD（突触减弱）
- Ca²⁺ 浓度编码了两种相反的指令，同一通道，不同含量，不同结果。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| NMDA 受体是 LTP 诱导的必要条件 | AP5 阻断 NMDA 受体后 LTP 消失，但基础传递正常 | PMID:6306230 | 高 |
| 双重门控：需谷氨酸 + 去极化 | Mg²⁺ 阻断的电压依赖性 + 配体结合实验 | PMID:30037851 (PMC6080888) | 高 |
| GluN2 亚型决定衰减动力学（多达 100 倍差异） | 单通道电生理 + 遗传操控 | PMID:30037851 (PMC6080888) | 高 |
| Ca²⁺ 浓度区分 LTP vs LTD | 低频→磷酸酶 LTD；高频→CaMKII LTP 通路 | PMID:22510460 (PMC3367554) | 高 |
| NMDA 受体 GluN1/2A IC₅₀ ≈ 2 µM at –100 mV | 电生理 Mg²⁺ 剂量-反应曲线 | PMID:30037851 (PMC6080888) | 高 |
| 体内视觉皮层：NMDA 受体阻断使朝向选择性指数从 0.82 降至 0.45 | 小鼠 V1 in vivo patch-clamp + 细胞内 MK-801 | PMID:24162850 (PMC6319606) | 高 |
| 细薄树突 NMDA 棘波：NMDA 受体贡献 ≥80% 离子电荷，胞体响应超线性 226% | 大鼠皮层脑片，焦点刺激 + 膜片钳 | PMID:10749211 | 高 |

## NMDA 受体的双重身份

今日修订（2026-05-27）新增重要概念：NMDA 受体在细胞层面有**两种截然不同的功能角色**，服务于不同的时空尺度：

1. **突触层面巧合检测器（单突触 LTP）**：在单个树突棘的突触水平，作为前文（2026-05-26）描述的 Hebb 型学习门卫——同时需要谷氨酸（突触前）和去极化（突触后）。
2. **树突分支层面计算单元（NMDA 棘波）**：当一个树突分支上的多个 NMDA 受体同时激活时，形成再生性正反馈，产生持续 50–200 ms 的"NMDA 棘波"——这是高出单突触贡献许多倍的、全分支层面的非线性整合事件，使该分支成为独立的 sigmoid 计算单元。

这两个功能使用同一分子，但在空间尺度（单突触 vs 整分支）和时间尺度（毫秒 vs 数百毫秒）上都不同。它们分别对应"突触强度调整"和"分支计算"两个层次的信息处理。

## 连接

- [[ltp]] — NMDA 受体是 LTP 诱导的必要门卫（单突触层面）
- [[ampa-receptor]] — Ca²⁺ 内流后 AMPA 受体大量插入突触是 LTP 的主要表达机制
- [[camkii]] — Ca²⁺ 内流激活 CaMKII 是 LTP 诱导的第一步下游信号
- [[hebbian-learning]] — NMDA 受体双重门控在分子层面实现 Hebb 规则
- [[synaptic-transmission]] — NMDA 受体是突触传递中谷氨酸信号的重要接受者
- [[calcium-channel]] — 与电压门控 Ca²⁺ 通道同为突触 Ca²⁺ 内流的重要来源（但机制不同）
- [[dendritic-computation]] — NMDA 受体是树突 NMDA 棘波的核心机器，使单根树突分支成为独立计算单元

## 未解问题

- Q-nmda-coincidence-window：NMDA 受体的时间整合窗口（由 GluN2 亚型决定）如何在发育和学习中动态变化？
- Q-glun2-switch-development：幼年期 GluN2B 到成年期 GluN2A 的亚型切换的精确分子触发机制是什么？
- Q-nmda-alzheimer：Aβ 寡聚体如何选择性损害 NMDA 受体依赖的 LTP？是通过直接结合受体，还是间接改变其下游信号？

## 修订历史

- 2026-05-26 · 创建 · 基于《NMDA 受体：突触的巧合检测器》一文 · 初始置信度：高
- 2026-05-27 · 修订 · 基于《树突：神经元内部的神经网络》一文 · 新增"NMDA 受体的双重身份"概念（突触层面巧合检测器 vs 分支层面 NMDA 棘波计算单元）；关键证据表新增 Smith 2013 体内视觉皮层证据 + Schiller 2000 NMDA 棘波证据；连接新增 dendritic-computation；dimensions 新增 cellular

## 来源文章

- [[2026-05-26-nmda-receptor-ltp]]
- [[2026-05-27-dendritic-computation]]

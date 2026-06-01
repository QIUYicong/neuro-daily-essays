---
title: 长时程抑制（LTD）
slug: ltd
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-04
updated: 2026-06-23
revision_count: 2
dimensions: [molecular, synaptic, cellular, cognition]
related: [ltp, nmda-receptor, ampa-receptor, camkii, calcineurin, arc-arg31, hebbian-learning, mglur-ltd, memory-consolidation, engram-cells, cerebellar-ltd, cerebellum]
prerequisites: [synaptic-transmission, nmda-receptor, ampa-receptor, ltp]
opens_questions: [Q-ltd-nmda-metabotropic, Q-ltd-long-term-maintenance, Q-ltd-behavior-extinction, Q-ltd-glua2-redundancy]
source_articles: [2026-06-04-ltd-long-term-depression]
key_sources: ["PMID:24183021", "PMID:19169250", "PMID:25429259", "PMID:19690847", "PMID:15450156", "PMID:15219735"]
---

# 长时程抑制 (Long-Term Depression, LTD)

> **一句话定义**：突触传递效率的持久性减弱，通过 AMPA 受体从突触后膜内吞来实现，由两条主要路径（NMDA 受体依赖型和 mGluR 依赖型）触发，是与 LTP 共同构成突触双向可塑性、维持大脑信息容量的主动遗忘机制。

## 当前理解

我们现在认为，LTD 是大脑主动塑造遗忘的分子机制，而非被动的突触衰减。LTD 的本质是突触后膜 AMPA 受体数量的持久减少——受体被内吞进入内体系统，突触电流降低，突触权重持久减弱。这一过程需要精确的分子机器运作（磷酸酶激活、支架蛋白重组、网格蛋白内吞），是与 LTP 对称的主动生化事件。

LTD 和 LTP 由同一个信使（Ca²⁺）的**数量**决定方向：高 Ca²⁺（高频刺激） → CaMKII → LTP；低 Ca²⁺（低频刺激）→ 钙调磷酸酶（PP2B）→ LTD。这是 BCM 可塑性理论的分子实现。

LTD 不只是单一机制——不同脑区、不同突触类型使用不同的触发机器，但最终效应相同（AMPA 受体内吞）：
1. **NMDA-LTD**（海马 CA1）：低 Ca²⁺ → PP2B/PP1 → GluA1 去磷酸化 + GluA2 Ser880 磷酸化 → AMPAR 内吞
2. **mGluR-LTD**（海马 CA1）：I 组 mGluR（mGluR5）激活 → 局部蛋白合成（Arc）→ AMPAR 内吞
3. **小脑 LTD**（PF-Purkinje）：mGluR1 + P/Q 通道 Ca²⁺ → PKC → GluA2 Ser880 磷酸化 → AMPAR 内吞

## 关键机制

### NMDA-LTD（海马 CA1，最充分研究的形式）

**诱导条件**：低频刺激（1 Hz, 900 次），使突触后 Ca²⁺ 达中等水平（而非 LTP 时的高峰值）

**磷酸酶级联**：
1. Ca²⁺ 激活 **PP2B（钙调磷酸酶）**（高亲和力，低 Ca²⁺ 即可激活）
2. PP2B 激活 **PP1**（蛋白磷酸酶 1）
3. PP1 使 **GluA1 Ser831**（CaMKII 位点）和 **Ser845**（PKA 位点）去磷酸化

**GluA2 命运切换**：
- PKC 磷酸化 **GluA2 Ser880** → 破坏 GRIP1/2 结合（突触锚点丧失）→ PICK1 结合 → 内吞

**空间定位机制**（Bhattacharyya et al., 2009，PMC2694745）：
- PSD-95 通过 SH3-GK 结构域与 AKAP150 结合
- AKAP150 将 PP2B（以及 PKA）精确定位于 NMDA 受体旁
- 钙调磷酸酶被定位激活 → AMPAR 去磷酸化 → 内吞

**两条 LTD 路径的分子特异性**：PSD-95 敲减仅阻断 NMDA-LTD，不影响 mGluR-LTD，证明两条路径使用不同的分子机器。

### mGluR-LTD

**触发受体**：mGluR5（I 组 mGluR，突触后膜上与 NMDA 受体相邻）

**关键特征**：不依赖 NMDA 受体；必须依赖**局部蛋白质合成**（翻译抑制剂可完全阻断）

**核心效应蛋白**：Arc/Arg3.1（活动调控的细胞骨架相关蛋白）
- mGluR 激活 → 解除 FMRP 对 Arc mRNA 的翻译抑制 → Arc 局部合成
- Arc 与 dynamin 和 endophilin 结合 → 促进网格蛋白介导的 AMPAR 内吞

**脆性 X 综合征联系**：FMRP 缺失 → Arc 等 LTD 相关蛋白持续过度翻译 → mGluR-LTD 失控激活 → 突触权重弥漫性减弱（Bear, Huber & Warren 2004 mGluR 理论）

### 小脑 LTD（PF-PC LTD）的独特性
小脑 LTD 与海马 LTD 使用相同的**最终效应器**（GluA2 Ser880 磷酸化 → AMPAR 内吞），但**触发机制根本不同**：
- 不依赖 NMDA 受体，依赖 **mGluR1**（代谢型）
- Ca²⁺ 来自 VGCCs 和 IP₃R（而非 NMDA）
- 关键激酶是 **PKCα/γ**（而非 LTP 对立的 PP2B）
- 诱导条件：平行纤维 + 攀爬纤维同时激活（Aiba et al. 1994, PMID:7954803）
- 功能意义：运动误差纠正（而非突触稳态）

详见 [[cerebellar-ltd]]。

### AMPAR 内吞后的命运

内化的 AMPAR 进入早期内体（early endosome），命运分叉：
- 通过**再循环内体**回到突触膜（LTP 时优先发生）
- 通过**溶酶体降解**（LTD 长期维持时可能的路径，尚不明确）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 低频刺激（1 Hz）诱导 NMDA-LTD，需要 NMDA 受体 | AP5 阻断消除 LTD；高频刺激后 LTD 缩小 | PMID:15450156 | 高 |
| PP2B/PP1 级联是 NMDA-LTD 所必需的 | 磷酸酶抑制剂（okadaic acid）阻断 LTD | PMID:24183021 (PMC4195488) | 高 |
| PSD-95/AKAP150 复合体定位钙调磷酸酶于突触是 NMDA-LTD 必要条件 | PSD-95 敲减/AKAP150 突变体 | PMID:19169250 (PMC2694745) | 高 |
| GluA1 Ser831/Ser845 去磷酸化参与 LTD 表达 | 敲入去磷酸化突变体小鼠；磷酸化特异抗体 | PMID:24183021 (PMC4195488) | 中-高 |
| mGluR-LTD 需要局部蛋白合成（Arc） | 翻译抑制剂阻断 mGluR-LTD；Arc 敲除阻断 mGluR-LTD | PMID:19690847 (PMC2803749) | 高 |
| Arc 与 dynamin/endophilin 结合促进 AMPAR 内吞 | 共免疫沉淀；Arc 截断突变体功能丧失 | PMID:25429259 (PMC4150421) | 中-高 |
| GluA2/GluA3 双敲除小鼠海马 LTD 仍然正常 | GluA2/GluA3 条件性双敲除 | PMID:24183021 (PMC4195488) | 高（对 GluA2 必需性的反证） |

## 连接

- [[ltp]] — LTD 与 LTP 构成突触双向可塑性；同一 NMDA 受体和 Ca²⁺，数量决定方向
- [[nmda-receptor]] — NMDA-LTD 的触发受体；Ca²⁺ 的量和速率决定 LTD vs. LTP
- [[ampa-receptor]] — LTD 的最终效应器：AMPAR 从突触膜内吞导致权重降低
- [[camkii]] — CaMKII（LTP 的激酶）与 PP2B（LTD 的磷酸酶）是对立调控对
- [[calcineurin]] — PP2B，NMDA-LTD 的关键磷酸酶，由中等 Ca²⁺ 优先激活
- [[arc-arg31]] — Arc/Arg3.1，mGluR-LTD 的执行分子，连接化学信号与内吞机器
- [[hebbian-learning]] — LTD 是 BCM 反-Hebb 规则在突触层面的分子实现；防止突触饱和
- [[memory-consolidation]] — 睡眠期间的突触稳态下调（SHY 假说）可能涉及 LTD 类机制
- [[cerebellar-ltd]] — 使用相同 AMPAR 内吞最终效应器的平行机制（但触发完全不同：mGluR1/PKC，无需 NMDA）
- [[cerebellum]] — 小脑 LTD 发生的回路背景（PF→PC突触）

## 未解问题

- Q-ltd-nmda-metabotropic：NMDA 受体是否可通过构象信号（非离子流）触发 LTD？"代谢型 NMDA 受体"假说的分子身份是什么？
- Q-ltd-long-term-maintenance：LTD 诱导后，降低的突触权重如何在数天至数周内稳定维持？
- Q-ltd-behavior-extinction：恐惧消退学习中的突触 LTD，是对原有恐惧记忆 LTP 的直接逆转，还是在独立突触上建立竞争性抑制？
- Q-ltd-glua2-redundancy：GluA2/GluA3 双敲除后 LTD 仍然正常，说明存在未知的备用内吞路径——其分子身份是什么？

## 修订历史

- 2026-06-04 · 创建 · 基于《遗忘的精准：LTD 文章》· 初始置信度：高（经典已建立机制）
- 2026-06-23 · 修订 · 基于《小脑的秘密》· 加入小脑 LTD 独特性说明（mGluR1/PKC 路径，与 NMDA-LTD 并列）；新增 related: cerebellar-ltd, cerebellum；新增连接段落

## 来源文章

- [[2026-06-04-ltd-long-term-depression]]

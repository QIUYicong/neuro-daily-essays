---
title: 社会记忆
slug: social-memory
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-08-14
updated: 2026-08-16
revision_count: 2
dimensions: [cellular, microcircuit, brain-region, cognition, behavior]
related: [hippocampal-circuit, ca2-hippocampus, vasopressin, oxytocin, supramammillary-nucleus, ltp, mgluR-ltd]
prerequisites: [hippocampal-circuit, synaptic-transmission]
opens_questions: [Q-ca2-function, Q-ca2-pnn-plasticity-window, Q-oxt-01]
source_articles: [2026-08-14-ca2-hippocampus-social-memory-temporal-context, 2026-08-16-oxytocin-circuit-social-memory-bonding]
key_sources: ["PMID:24572357", "PMID:24863146", "PMID:29705549", "PMID:36971428", "PMID:10888874", "PMID:38052983"]
---

# 社会记忆 (Social Memory)

> **一句话定义**：识别和记住曾见过的同类个体的能力；依赖海马 CA2 亚区作为专用神经底物，通过加压素/催产素激素门控的突触可塑性（mGluR-LTD 而非 LTP）实现信息存储——这使得社会记忆既依赖情节记忆系统，又拥有独立于一般记忆的分子门控机制。

## 当前理解

我们现在认为，社会记忆在神经回路层面与空间记忆、情境恐惧记忆等一般情节记忆**并行但分离**。其关键证据来自 Hitti & Siegelbaum 2014（PMID:24572357）的遗传解剖：选择性灭活海马 CA2 区的突触输出导致社会记忆**完全丧失**，而空间记忆、恐惧记忆和物体识别均完全正常。

社会记忆不是"记录谁"的单一维度编码，而是"**在激素门控下绑定谁-何时**"的双维信息：
- **"谁"**：由 CA2 从 EC 接收的感官/身份信息
- **"门控"**：由下丘脑 PVN 通过加压素（AVP）/催产素（OT）纤维决定"现在是否写入"

## 关键机制

### 1. CA2 是社会记忆的专用基底

**核心实验（Hitti & Siegelbaum 2014, PMID:24572357）**：
- 方法：Amigo2-Cre 转基因小鼠 + 双侧 CA2 注射 AAV-DIO-TeNT（破伤风毒素重链）
- 结果：五试次社会认知测试中，CA2-TeNT 小鼠对熟悉同类的探索时间与陌生者无差别（社会记忆完全丧失）
- 关键对照：社交性（与陌生者互动意愿）完全正常——动机保留，记忆消失
- 所有其他记忆测试（空间、恐惧、物体识别、嗅觉辨别）均正常

**意义**：CA2 是社会记忆的**必要专用底物**，不是一般记忆系统的非特异性组件。

### 2. 激素门控：加压素/催产素的 CA2 特异性作用

CA2 密集表达**加压素 1b 受体（Avpr1b）**，这是 CA1/CA3 所不具备的：
- Avpr1b 选择性激动剂在 CA2 诱发 NMDA 受体+Ca²⁺ 依赖的突触增强（同等处理 CA1 无效）（Pagani et al. 2015, PMID:24863146）
- 下丘脑 PVN→CA2 加压素通路增强社会记忆表现（Piskorowski & Chevaleyre 2018, PMID:29705549）
- 社会接触触发垂体肽释放 → Avpr1b/催产素受体激活 → Ca²⁺ 信号解除 RGS14 的部分抑制 → CA2 突触短暂进入可塑性窗口

### 3. mGluR-LTD：社会记忆的突触可塑性形式

尽管 CA2 对标准 Hebbian LTP 有 RGS14 介导的抵抗，**社会记忆并非依赖 LTP，而是依赖 mGluR 长时程抑制（mGluR-LTD）**（Samadi et al. 2023, PMID:36971428）：
- CA2 的 mGluR-LTD 依赖蛋白质合成和 STEP 磷酸酶
- 需要 RGS14（而非 RGS4）参与
- RGS14 KO 小鼠的 mGluR-LTD 受损，社会识别记忆也同步受损

**反直觉结论**：RGS14（LTP 抑制蛋白）通过驱动 mGluR-LTD 正向调节社会记忆——LTP 抗性 ≠ 记忆不可塑性。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| CA2 灭活选择性消除社会记忆，其他记忆正常 | Amigo2-Cre+TeNT 小鼠；5试次社会认知测试 | PMID:24572357 (PMC4000264) | 高 |
| Avpr1b 在 CA2（而非 CA1）诱发 NMDA 依赖突触增强 | CA2/CA1 切片电生理；选择性 Avpr1b 激动剂 | PMID:24863146 | 高 |
| CA2 mGluR-LTD 需要 RGS14，且 RGS14 KO 损害社会识别记忆 | RGS14 KO 小鼠；mGluR 激动剂；社会识别测试 | PMID:36971428 | 高 |

## 连接

- [[ca2-hippocampus]] — CA2 是社会记忆的神经底物；社会记忆是 CA2 三大功能之一
- [[hippocampal-circuit]] — CA2 插于 CA3 和 CA1 之间；社会记忆依赖 CA2→CA1 路径
- [[vasopressin]] — Avpr1b 在 CA2 门控社会情境可塑性（直接通路，激素-记忆接口）
- [[oxytocin]] — 通过PVH→SuM→CA2间接通路参与社会识别记忆写入；Ferguson 2000确立OXT因果作用
- [[supramammillary-nucleus]] — OXT到CA2的中继站，同时也是θ节律起搏源

## 未解问题

- Q-ca2-function：CA2 的社会记忆功能与时间记忆功能是否共享细胞机制，或由不同亚型神经元承担？
- Q-ca2-pnn-plasticity-window：CA2 围神经元网（PNNs）在青春期成熟后是否关闭了社会记忆的关键期？PNN 异常与 ASD 社交记忆缺陷的关系？

## 修订历史

- 2026-08-14 · 创建 · 基于《CA2：海马遗忘的第三元件》文章 #113 · 整合 Hitti & Siegelbaum 2014、Pagani 2015、Piskorowski & Chevaleyre 2018、Samadi 2023 四项研究；初始置信度：高（强遗传解剖证据）
- 2026-08-16 · rev2 · 基于《催产素回路》文章 #115 · 新增：(1) Ferguson 2000 Oxt⁻/⁻社会失忆作为催产素因果性的奠基证据；(2) PVH→SuM→CA2间接路径的补充（PMID:38052983）；(3) 与oxytocin、supramammillary-nucleus的新连接；(4) Q-oxt-01未解问题（Avpr1b与OTR双通路协调）

## 来源文章

- [[2026-08-14-ca2-hippocampus-social-memory-temporal-context]]
- [[2026-08-16-oxytocin-circuit-social-memory-bonding]]

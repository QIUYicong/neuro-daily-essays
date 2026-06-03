---
title: 记忆再巩固
slug: memory-reconsolidation
domain: concepts
type: mechanism
status: mainstream
confidence: medium
created: 2026-07-01
updated: 2026-07-01
revision_count: 1
dimensions: [molecular, cellular, synaptic, brain-region, behavior, cognition, disease]
related: [memory-consolidation, fear-conditioning, fear-extinction, engram-cells, ltp, ltd, amygdala, hippocampal-circuit, bdnf, zif268, prediction-error]
prerequisites: [memory-consolidation, fear-conditioning, ltp, engram-cells]
opens_questions: [Q-reconsolidation-all-memories, Q-reconsolidation-human-clinical, Q-reconsolidation-pe-mechanism]
source_articles: [2026-07-01-memory-reconsolidation-update-window]
key_sources: ["PMID:10963596", "PMID:21120142", "PMID:28495311", "PMID:32563517", "PMID:30659275"]
---

# 记忆再巩固 (Memory Reconsolidation)

> **一句话定义**：已固化的记忆在被提取后短暂重新进入蛋白质合成依赖的脆弱状态（再巩固窗口，约 1–6 小时），期间可被干扰、增强或以新信息更新，完成后通过 Zif268 依赖通路（不同于初始巩固的 BDNF 通路）重新稳固。

## 当前理解

我们现在认为，记忆再巩固是一种**主动的记忆更新机制**（Lee, Nader, Schiller 2017, PMID:28495311）：当已固化的记忆被提取时，其突触权重模式短暂变为可塑状态，允许将新信息整合进旧记忆痕迹，而非总是创建独立的新痕迹。这在认知上具有适应性——当世界改变而同一线索产生不同结果时，大脑需要更新旧痕迹而非不断叠加冗余表征。

**核心区分**：再巩固≠消退。消退是新抑制学习（IL皮层→腹侧ITC→CeM回路建立），原始记忆保留；再巩固是原始记忆痕迹本身被更新——两者可被区分的最关键证据是它们使用不同的分子机制（BDNF vs Zif268），以及提取时长对它们的不同影响。

**动物层面证据扎实，人类行为操控层面有争议**：动物（鼠）实验中再巩固已被数百个独立研究重复，分子机制较清晰。人类中通过行为（提取+消退）操控再巩固窗口的最引人注目的研究（Schiller 2010）被验证报告（Krediet 2020, PMID:32563517）发现存在严重方法论问题，降低了对人类行为操控可靠性的信心。

## 关键机制

### 阶段一：不稳定化（Destabilization，提取后 0–30 min）

- 提取激活 NR2B 亚基 NMDA 受体 → Ca²⁺ 内流
- 钙调磷酸酶（calcineurin）激活 → AMPA 受体从突触撤出（GluR2 内化）
- 泛素-蛋白酶体通路激活 → 突触蛋白降解
- 结果：突触重新变为"可写"状态（"编辑模式"）

### 阶段二：整合窗口（提取后 30 min – 约 6 h）

- 如有新信息（来自新的学习事件或注射记忆增强剂），可被整合进正在不稳定的痕迹
- 如有干扰因素（蛋白质合成抑制剂、β阻断剂），可损伤再巩固
- 蛋白酶抑制剂（如放线菌酮/anisomycin）在此窗口内有效，6 h 后无效

### 阶段三：重新稳固化（Restabilization，依赖 Zif268）

**与初始巩固的分子解离**（Lee 2010, PMID:21120142）：
| 过程 | 关键 IEG | 其他分子 |
|------|---------|---------|
| 初始巩固 | BDNF | mTOR/MAPK, CaMKII, AMPAR 插入 |
| 再巩固更新 | Zif268（Egr1/NGFI-A） | CB1 受体, CaMKII/NO, 新蛋白合成 |

### 决定再巩固 vs 消退的因素

| 因素 | 再巩固 | 消退 |
|------|--------|------|
| 提取时长 | 短（1–3 次 CS） | 长（>10–20 次 CS） |
| 预测误差 | 中等不匹配 | 高不匹配 |
| 记忆年龄 | 较新记忆 | 不影响 |
| 记忆强度 | 较弱记忆 | 不影响 |

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 提取后 anisomycin 致遗忘，不提取则无效 | 大鼠BLA微注射 + 条件性恐惧 | PMID:10963596（仅摘要） | 高（被大量重复） |
| 初始巩固需 BDNF，更新需 Zif268 | CPFE 范式 + 海马 antisense | PMID:21120142（全文） | 中（单一实验室，特定范式） |
| 人类提取-消退 10 min 内预防恐惧回归 | 皮肤电反应 + 1年随访 | PMID:20010606（仅摘要） | 低（验证报告发现方法问题） |
| 中等不匹配触发再巩固，高不匹配触发消退 | 吸引子网络计算模型 | PMC3149635（全文） | 中（理论预测，有部分实验支持） |
| 提取-消退不需要 DA D1 或 GluN2B | BLA 内药理 + 行为 | PMID:30659275（全文） | 中（单一实验室，大鼠） |

## 连接

- [[memory-consolidation]] — 初始巩固是再巩固的前提；两者分子通路不同（BDNF vs Zif268）
- [[fear-conditioning]] — 条件性恐惧是最广泛研究的再巩固模型
- [[fear-extinction]] — 消退与再巩固共享提取触发器但走向不同机制
- [[engram-cells]] — 再巩固窗口是印迹细胞突触被选择性修改的时机
- [[ltp]] — 再巩固的稳固化相依赖 LTP 类的蛋白合成，但 IEG 不同
- [[amygdala]] — BLA（外侧杏仁核）是恐惧记忆再巩固的关键位点
- [[hippocampal-circuit]] — 陈述性/情景记忆再巩固的关键结构
- [[bdnf]] — 初始巩固中 BDNF 的角色；与 Zif268 形成解离

## 未解问题

- Q-reconsolidation-all-memories：所有记忆类型（程序性、语义性）都能再巩固吗？
- Q-reconsolidation-human-clinical：人类行为操控再巩固的可靠性如何提高？
- Q-reconsolidation-pe-mechanism：预测误差如何分子层面触发不稳定化？如果不是 DA D1/GluN2B，是什么？

## 修订历史

- 2026-07-01 · 创建 · 基于《提取的代价：记忆再巩固如何在稳固与可塑之间走钢丝》 · 初始置信度：中（动物层面 mainstream，人类临床 emerging）

## 来源文章

- [[2026-07-01-memory-reconsolidation-update-window]]

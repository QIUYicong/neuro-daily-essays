---
title: 小脑
slug: cerebellum
domain: systems
type: region
status: established
confidence: high
created: 2026-06-23
updated: 2026-06-23
revision_count: 1
dimensions: [molecular, cellular, microcircuit, brain-region, whole-brain-network, behavior, cognition]
related: [cerebellar-motor-learning, purkinje-cell, motor-cortex, default-mode-network, basal-ganglia]
prerequisites: [synaptic-transmission, action-potential, long-term-depression]
opens_questions: [Q-cb-01, Q-cb-02, Q-cb-03]
source_articles: [2026-06-23-cerebellum-motor-learning]
key_sources: ["PMID:35803588", "PMID:32866603", "PMID:33897382", "PMID:31636540"]
---

# 小脑 (Cerebellum)

> **一句话定义**：后脑背侧的运动和认知预测中枢，含约 600 亿颗粒细胞（占全脑神经元约 69%），通过攀爬纤维误差信号驱动的突触可塑性（LTD）精调运动，并通过外侧新皮质小脑参与语言、执行控制等认知功能。

## 当前理解

我们现在认为，小脑是大脑中最精良的"局域监督学习机器"。它的核心逻辑是：苔藓纤维提供来自多脑区的"状态信号"，攀爬纤维（来自下橄榄核）携带"预测误差"，两者在浦肯野细胞树突上的偶然同步触发 LTD，使下次同样情境下的运动输出更加精准。

小脑的功能远超运动控制。外侧小脑（Crus I/II 等）在人类进化中与前额叶皮层平行扩张，功能磁共振显示其参与默认模式网络、中央执行网络、语言网络、注意网络等所有主要认知网络。小脑可能是大脑中一个通用的"预测计算和时序精调模块"——无论被预测的是运动结果还是语言序列，其底层计算逻辑相似。

## 关键解剖

**细胞类型**（按功能层级）：
- **颗粒细胞（Granule cells）**：约 600 亿个，占全脑约 69%；接收苔藓纤维，发出并行纤维；实现高维稀疏扩展
- **浦肯野细胞（Purkinje cells）**：小脑皮层唯一输出；巨大树突接收 15-20 万条并行纤维 + 1 条攀爬纤维；输出 GABA 抑制深部核团
- **攀爬纤维（Climbing fibers）**：来自下橄榄核；1:1 接触浦肯野细胞；携带误差信号；触发 LTD
- **苔藓纤维（Mossy fibers）**：来自脑桥核、脊髓、前庭等；携带多模态感觉运动状态
- **分子层中间神经元（MLIs）**：篮状细胞 + 星形细胞；抑制浦肯野细胞；构成学习门控机制
- **Golgi 细胞**：抑制颗粒细胞；调节稀疏性

**主要分区**：
- 绒球（flocculus）：VOR/OKR 适应的核心
- 蚓部（vermis）：躯干和眼动控制
- 外侧半球 / Crus I & II：认知和语言相关功能（人类特化）

**深部核团（Deep Cerebellar Nuclei, DCN）**：
- 齿状核（dentate）、球状核（globose）、栓状核（emboliform）、顶核（fastigial）
- 浦肯野细胞抑制 DCN；DCN 是小脑的主要输出，经丘脑到达运动皮层和前额叶

## 关键机制

→ 详见 [[cerebellar-motor-learning]]（回路可塑性机制）

**核心回路**：
```
苔藓纤维 → 颗粒细胞 → 并行纤维
                            ↓
下橄榄核 → 攀爬纤维 → 浦肯野细胞 → 深部核团 → 丘脑 → 皮层/脑干
                               ↑
                      分子层中间神经元 (MLI) [门控]
```

**认知小脑回路**：
- 外侧小脑 ↔ 前额叶（经丘脑的小脑-丘脑-皮层回路）
- 参与语言加工、执行控制、工作记忆等

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 小脑皮层 LTD 是运动学习的核心机制 | VOR 适应（多实验室，多物种）+ 遗传学 | PMID:32866603 | 高 |
| 外侧小脑参与认知网络 | 静息态 fMRI 功能连接 + 病人损伤数据 | PMID:33897382 | 中 |
| Purkinje 细胞减少与 ASD 相关 | 尸检 + 基因模型鼠 | PMID:31636540 | 中 |
| 小脑颗粒细胞约占全脑神经元 69% | 立体定量计数 | PMID:35803588 | 高 |
| 人类外侧小脑与 PFC 平行演化扩张 | 比较神经解剖 + 比较基因组学 | PMID:33897382 | 中 |

## 连接

- [[cerebellar-motor-learning]] — 小脑运动学习的分子与回路机制（核心子页）
- [[purkinje-cell]] — 小脑皮层的唯一输出细胞
- [[motor-cortex]] — 小脑→丘脑→运动皮层的输出回路
- [[default-mode-network]] — 外侧小脑参与 DMN
- [[basal-ganglia]] — 基底节与小脑并行参与运动控制，但机制不同（强化学习 vs. 监督学习）
- [[long-term-depression]] — 小脑 LTD 与 CA1-LTD 的分子机制异同
- [[predictive-coding]] — 小脑是"预测-误差-更新"回路的最早实现

## 未解问题

- Q-cb-01：认知小脑是否也使用攀爬纤维/LTD 机制？还是不同的可塑性？
- Q-cb-02：ASD 中 Purkinje 细胞减少是因还是果？
- Q-cb-03：多个运动技能的并行学习如何避免"回路干涉"？

## 修订历史

- 2026-06-23 · 创建 · 基于《静默的预测机器》(#59) · 综合 Hull & Regehr 2022, Lisberger 2020, Habas 2021 · 初始置信度：高

## 来源文章

- [[2026-06-23-cerebellum-motor-learning]]

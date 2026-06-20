---
title: FOXP2转录因子
slug: foxp2
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-12
updated: 2026-08-15
revision_count: 2
dimensions: [molecular, cellular, disease, behavior]
related: [language-network, broca-area, language-evolution, basal-ganglia, childhood-apraxia-of-speech, vocal-learning, corticostriatal-circuit, cntnap2]
prerequisites: [action-potential, synaptic-transmission, language-network]
opens_questions: [Q-foxp2-01, Q-foxp2-02, Q-foxp2-03]
source_articles: [2026-08-12-foxp2-language-genetics-development, 2026-08-15-cntnap2-language-social-autism-circuit]
key_sources: ["PMID:11586359", "PMID:34260143", "PMID:25225386", "PMID:37137515", "PMID:39868047", "PMID:38366112"]
---

# FOXP2转录因子 (FOXP2 Transcription Factor)

> **一句话定义**：FOXP2是一个叉头框家族转录因子，通过在发育期调控264个以上靶基因来构建皮层-纹状体-丘脑-小脑言语运动回路；其人类特异性的两个氨基酸替换（相比黑猩猩）优化了陈述性→程序性学习的转换效率，为自动化流利言语提供神经底物；杂合突变导致儿童语言失用症（CAS）。

## 当前理解

我们现在认为FOXP2不是直接编码语言能力的"语言基因"，而是在胚胎和早期发育阶段**构建言语运动回路的发育基因**。

**蛋白结构**（den Hoed et al., 2021；PMID:34260143）：
- 叉头域（forkhead domain）：~80-100个氨基酸，DNA结合；KE家族p.R553H突变破坏此域
- 锌指基序（zinc finger）：FOXP亚家族特有，蛋白-蛋白互作
- 亮氨酸拉链（leucine zipper）：使FOXP蛋白形成同源/异源二聚体，对DNA结合至关重要
- N端谷氨酰胺富集区（polyQ）：功能尚不明确

**表达模式**：
- 皮层：第IV-VI层（~70%在第VI层，均为皮层-丘脑CT投射神经元，Qi et al. 2024；PMID:39868047）
- 纹状体：纹状体小室（striosome）优先表达，发育期高，成体水平降低
- 丘脑：后侧和外侧核群
- 小脑：普肯野细胞（Purkinje cells）
- 下橄榄核

**人类特异性**：相比黑猩猩有T303N和N325S两个氨基酸替换。尼安德特人也携带这两个替换（Krause et al. 2007；PMID:17949978），提示替换事件早于30万年前。原始正向选择信号被证明是小样本量统计伪迹（2018年重新分析）。

**功能**：主要作为转录抑制子，通过招募CTBP1/2共抑制子和NuRD染色质重塑复合物发挥作用；也能激活特定靶基因（如VLDLR）。

## 关键机制

### 分子层：靶基因网络（Vernes et al. 2011；PMID:21765815）

E16小鼠脑ChIP-chip鉴定264个高置信直接靶基因，富集于：
- 轴突导向（KEGG p=4.73×10⁻⁸）：SEMA3A, SEMA4F, SEMA6D, EFNB2
- 神经突发育：NRN1（神经营养素）、NELL2
- 突触传递和细胞迁移

| 靶基因 | 调控方向 | 功能 | 疾病关联 |
|--------|---------|------|---------|
| CNTNAP2 | 抑制（内含子调控区直接结合） | 神经元细胞粘附（neurexin家族） | 语言障碍、孤独症 |
| SRPX2 | 抑制 | 突触形成、超声发声 | 人类语言缺陷 |
| MET | 抑制 | 皮层发育 | 孤独症 |
| DISC1 | 抑制 | 树突生长、海马发育 | 精神分裂症 |
| VLDLR | 激活（直接结合） | 小脑颗粒细胞迁移 | 小脑发育不全 |

### 细胞层：2023年新机制——蛋白质马达（Walker et al. 2023；PMID:37137515）

KE家族R553H突变导致纹状体神经元dynactin1过表达：
```
R553H突变 → dynactin1过表达 → dynein-dynactin蛋白马达复合物破坏
→ TrkB内体运输障碍（BDNF信号受损）
→ 微管动力学改变 + 树突生长减少 + 电活动改变
→ 言语失用症表型
降低dynactin1 → 救援上述异常（小鼠实验）
```

### 回路层：皮层-纹状体-丘脑三角

**皮层侧**（Qi et al. 2024）：第VI层FOXP2+ CT神经元形成促进型突触（低p₀，强短期促进），受乙酰胆碱（M1/α4β2α5 nAChR）和多巴胺（D1，仅L6b）精确调制

**纹状体侧**：FOXP2影响中型棘神经元（MSN）树突发育复杂度，从而影响皮层-纹状体信息整合能力

**进化功能**（Schreiweis et al. 2014；PMID:25225386）：人源化Foxp2小鼠在陈述性→程序性学习转换中表现更快；DMS多巴胺降低30%，DLS LTD增强

### 动物模型：发声学习（White lab；PMC2683917）

斑马雀Area X（纹状体）中：
- 独自练习时FoxP2 mRNA下降（促进变异性探索）
- 定向鸣叫时下降幅度更小（社会情境依赖）
- 敲减→异常发声变异性+额叶皮质类似区过度爆发（Hilliard et al. 2014；PMID:24360538）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| p.R553H突变→CAS | KE家族三代遗传 + 独立个体CS | PMID:11586359 | 高 |
| L6 FOXP2+细胞=CT神经元 | 逆行示踪+膜片钳 | PMID:39868047 | 高 |
| 264个直接靶基因（发育期） | E16 ChIP-chip + 原代神经元验证 | PMID:21765815 | 高 |
| 人源化Foxp2加速程序性学习转换 | Foxp2^hum knockin小鼠行为 | PMID:25225386 | 中 |
| R553H→dynactin1过表达→rescue | iPSC + knockin小鼠 + dynactin1 KD | PMID:37137515 | 中-高 |
| Area X FoxP2在鸣唱时下调 | ISH | PMC2683917 | 中-高 |
| CAS>30个致病基因（非仅FOXP2） | 全外显子测序，3队列 | PMID:38366112 | 高 |

## 连接

- [[language-network]] — FOXP2构建语言网络的运动侧（皮层-纹状体回路）
- [[language-evolution]] — 人类特异性氨基酸替换是语言进化中的分子事件之一
- [[broca-area]] — BA44/BA45所在皮层的第VI层CT神经元高表达FOXP2
- [[basal-ganglia]] — 纹状体MSN树突发育受FOXP2调控
- [[childhood-apraxia-of-speech]] — FOXP2杂合突变的主要临床表现
- [[vocal-learning]] — FoxP2在鸣禽Area X动态调控发声学习
- [[cntnap2]] — FOXP2最重要的下游直接抑制靶点；CNTNAP2缺失→PV+中间神经元减少→CDFE综合征/ASD/语言障碍三角共病（现已有独立wiki页）

## 未解问题

- Q-foxp2-01（高优先级）：成体鸣禽Area X中FoxP2下调的上游触发机制是什么（什么信号让FoxP2在鸣唱时降低）？是否涉及多巴胺信号？
- Q-foxp2-02（高优先级）：FOXP2 L6 CT神经元在言语产生时的实时电生理活动是什么？在言语规划vs执行阶段如何变化？
- Q-foxp2-03（中优先级）：FOXP2靶基因网络中哪些是言语特异的（对应CAS），哪些是通用运动学习的？区分这两类基因的实验策略？

## 修订历史

- 2026-08-12 · 创建 · 基于《一个改变了语言研究的基因：FOXP2如何在神经回路层面为人类发声学习奠定遗传基础》(#111) · 综合EMBO Reports 2021综述（PMID:34260143）、PLoS Genet 2011靶基因研究（PMID:21765815）、PNAS 2014人源化小鼠（PMID:25225386）、Brain 2023新机制（PMID:37137515）、iScience 2024 CT神经元（PMID:39868047）和Mol Psychiatry 2024 CAS遗传架构（PMID:38366112） · 初始置信度：高
- 2026-08-15 · rev2 · 来自《CNTNAP2：语言、社会与癫痫三角共病》(#114) · 补充cntnap2连接说明（PV+中间神经元减少→CDFE/ASD/语言障碍三角共病）；CNTNAP2已有独立wiki页，source_articles补充 2026-08-15

## 来源文章

- [[2026-08-12-foxp2-language-genetics-development]]
- [[2026-08-15-cntnap2-language-social-autism-circuit]]

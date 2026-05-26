---
title: 突触传递
slug: synaptic-transmission
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-05-25
updated: 2026-05-26
revision_count: 2
dimensions: [synaptic, cellular, molecular, cognition]
related: [action-potential, SNARE-complex, synaptotagmin, active-zone, neurotransmitter-receptor, axon-initial-segment, nmda-receptor, ampa-receptor, ltp]
prerequisites: [action-potential, voltage-gated-calcium-channel]
opens_questions: [Q-snare-partial-zipper, Q-kiss-and-run-prevalence, Q-vesicle-recycling-kinetics]
source_articles: [2026-05-25-synaptic-vesicle-exocytosis, 2026-05-26-nmda-receptor-ltp]
key_sources: ["PMID:22068972", "PMID:22026965", "PMID:23060190", "PMID:22510460", "PMID:30037851"]
---

# 突触传递 (Synaptic Transmission)

> **一句话定义**：突触传递是一个神经元（突触前）通过释放化学信号分子（神经递质）将电信号转化为化学信号，进而在另一个神经元（突触后）重新产生电信号的过程，其速度可达毫秒级。

## 当前理解

突触传递是大脑神经元之间信息交流的主要方式（电突触为少数例外）。在化学突触处，突触前终末通过精密的分子机器实现信号的"电→化学→电"转化：

1. **动作电位**传入突触前终末，使**电压门控钙通道（VGCCs）**开放。
2. Ca²⁺内流，局部浓度在活动区迅速升高（纳米域内可能超过数十至数百微摩尔）。
3. Ca²⁺结合**Synaptotagmin**（钙传感器），触发突触囊泡与突触前膜的**SNARE蛋白介导的融合**。
4. 神经递质被释放到突触间隙（宽约20纳米），扩散并结合突触后膜上的受体。
5. 受体激活引发突触后细胞的电化学反应（EPSP或IPSP）。

从Ca²⁺内流到融合孔打开，全过程约**100-200微秒**，是已知最快的生物力学反应之一（PMID:22068972）。

这一速度得益于：
- 活动区的**纳米级空间预组织**（钙通道与准备好的囊泡紧邻）
- 囊泡预先进入**就绪态（Ready Releasable Pool, RRP）**
- SNARE蛋白已处于**部分拉合**的高能态，只等钙信号触发

## 关键机制

### 分子层（活动区与SNARE机器）
- 活动区：由RIM、CAST/ELKS、Bassoon、Piccolo等蛋白构成的纳米级脚手架，将钙通道和囊泡组织在最优距离
- SNARE复合体（[[SNARE-complex]]）：Synaptobrevin（囊泡）+ Syntaxin-1 + SNAP-25（靶膜）形成四螺旋束，从N端向C端"拉链式"组装产生机械力驱动融合
- Munc13（启动蛋白）：使Syntaxin从闭合→开放，是囊泡进入RRP的必要步骤
- Munc18-1（SM蛋白）：与Syntaxin结合，调控SNARE复合体组装，缺失则融合完全阻断

### 细胞层（囊泡循环）
- **停泊（Docking）**：囊泡附着于活动区，需活动区脚手架
- **启动（Priming）**：ATP依赖过程，需Munc13，囊泡进入RRP
- **融合（Fusion）**：Ca²⁺→Syt1激活→SNARE完成拉合→半融合→融合孔打开
- **回收（Recycling）**：网格蛋白介导内吞（慢）或超快内吞（快），维持囊泡供应

### 突触层（信号传递特性）
- **同步释放**：Ca²⁺触发，Syt1/2/9介导，毫秒级
- **异步释放**：Syt1缺失后显现，低亲和力传感器，百毫秒级
- **自发微小释放（miniature events）**：不依赖动作电位，偶发，频率因突触类型而异

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 融合时间约100-200微秒 | 光解Ca²⁺螯合 + 高分辨膜片钳（calyx of Held） | PMID:22068972 | 高 |
| Ca²⁺触发释放速率提高>100,000倍 | 体外SNARE重建 + 遗传学 | PMID:23060190 | 高 |
| SNARE三蛋白是必要融合机器 | 三组分遗传缺失/重建实验 | PMID:22026965 | 极高 |
| 活动区脚手架决定释放效率而非融合能力 | RIM+ELKS双敲除鼠 | PMID:27537483 | 高 |
| 约3个SNARE复合体足以触发单次融合 | 计算模型 + 单分子实验 | PMID:23060190; PMID:37891212 | 中 |

### 突触后层（受体接收与可塑性，2026-05-26 新增）

突触后侧主要有两类谷氨酸受体共同参与快速兴奋突触传递：

- **AMPA 受体（[[ampa-receptor]]）**：快速、无电压依赖性阻断，产生 EPSP 的主要贡献者；衰减时间约 2–5 ms；数量决定突触传递强度，LTP 期间大量插入。
- **NMDA 受体（[[nmda-receptor]]）**：需要谷氨酸 + 甘氨酸 + 突触后去极化（解除 Mg²⁺ 阻断），Ca²⁺ 高度通透，是突触可塑性（LTP/LTD）的触发器。衰减时间约 40–400 ms（取决于 GluN2 亚型）。

这两类受体共同构成了突触传递的接收端：AMPA 受体负责"当下"的快速传递，NMDA 受体负责"可塑性"的时间判断。突触传递效率（"突触权重"）在 LTP/LTD 中由突触后 AMPA 受体的数量动态调节。

## 连接

- [[action-potential]] — 触发突触传递的电信号
- [[SNARE-complex]] — 突触融合的核心分子机器
- [[synaptotagmin]] — 钙传感器，触发融合的分子开关
- [[active-zone]] — 突触前终末的纳米级发射平台
- [[axon-initial-segment]] — 产生动作电位的位点，突触传递的上游
- [[nmda-receptor]] — 突触后谷氨酸受体，巧合检测器，触发 LTP/LTD
- [[ampa-receptor]] — 突触后谷氨酸受体，快速 EPSP 产生者，突触权重的物理实现
- [[ltp]] — 突触传递的可塑性形态，通过 AMPA 受体动态调节实现

## 未解问题

- Q-snare-partial-zipper：就绪态囊泡的SNARE蛋白是部分拉合还是完全分开？（见 contested_claims.json）
- Q-kiss-and-run-prevalence：kiss-and-run模式在生理条件下的普遍程度
- Q-vesicle-recycling-kinetics：超快内吞的分子机制与速率

## 修订历史

- 2026-05-25 · 创建 · 基于《神经信号的化学渡口》一文 · 初始置信度：高（多篇诺贝尔奖相关研究支持）
- 2026-05-26 · 修订 · 新增突触后受体层（AMPA/NMDA 受体）及其在 LTP 中的角色；related 字段扩展；dimensions 新增 cognition · 来源：《NMDA 受体：突触的巧合检测器》

## 来源文章

- [[2026-05-25-synaptic-vesicle-exocytosis]]

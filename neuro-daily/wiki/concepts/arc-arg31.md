---
title: Arc/Arg3.1（活动调控的细胞骨架相关蛋白）
slug: arc-arg31
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-04
updated: 2026-10-16
revision_count: 3
dimensions: [molecular, synaptic, cellular, cognition, behavior]
related: [ltd, ltp, ampa-receptor, memory-consolidation, engram-cells, mglur-ltd, pkm-zeta, synaptic-tagging-capture, homer1a, slow-wave-sleep, homeostatic-plasticity]
prerequisites: [synaptic-transmission, ampa-receptor, ltp, ltd]
opens_questions: [Q-arc-ltp-ltd-switch, Q-arc-dendritic-targeting, Q-arc-capsid-function, Q-homer1a-01]
source_articles: [2026-06-04-ltd-long-term-depression, 2026-09-21-pkm-zeta-late-ltp-persistence, 2026-10-16-homer1a-arc-sleep-ampa-downscaling]
key_sources: ["PMID:19690847", "PMID:25429259", "PMID:24183021", "PMID:29466744", "PMID:29466743", "PMID:32350140", "PMC:7229651", "PMID:36632309", "PMC:9826981"]
---

# Arc/Arg3.1（活动调控的细胞骨架相关蛋白）

> **一句话定义**：神经活动即早表达的树突蛋白，作为突触活动的"量规"，在 LTD 中通过与 dynamin/endophilin 结合促进 AMPA 受体内吞，在 LTP 中参与肌动蛋白稳定和记忆巩固，双向调节突触强度。

## 当前理解

我们现在认为，Arc/Arg3.1 是一个突触活动的多功能调节器，而非单向效应蛋白。Arc 的 mRNA 在神经元激活后数分钟内从核运输出去，沿树突分布，在**活动的突触棘局部翻译**——这一特性使 Arc 成为"突触标记"分子，在正确的地点、正确的时间产生，响应局部突触活动。

Arc 的功能因其产生背景（活动强度、时间窗口）而异：
- **mGluR 激活/中等活动（LTD 情境）**：Arc 与 dynamin 和 endophilin 结合 → 促进网格蛋白介导的 AMPAR 内吞 → 突触减弱
- **强烈活动（LTP 巩固情境）**：Arc 激活 PAK → 磷酸化 LIMK → 抑制 cofilin → 稳定棘内肌动蛋白 → 支持 L-LTP 的树突棘结构维持
- **持续高活动（稳态情境）**：Arc 积累驱动 AMPAR 内吞，防止突触过度增强，实现突触稳态下调（synaptic scaling down）

Arc 的"双向"功能使它成为大脑活动感知系统的一部分：它感知活动的量，并将感知结果转化为对应的突触强度调整。这与 LTP 和 LTD 的 BCM 双向框架紧密契合。

## 关键机制

### 基因与蛋白结构

- **基因**：*Arc*（小鼠）= *Arg3.1*（大鼠），即早基因（IEG），依赖活动诱导表达
- **蛋白结构**：含 N 端 NHD 结构域（与 dynamin 结合）和 C 端 CCD 结构域（参与多聚化）
- **mRNA 的特殊性**：Arc mRNA 含去稳定元件（ARE），半衰期短（~30 min）；同时含特殊的 3'UTR，驱动树突靶向运输

**2026-09-21 新增：病毒样衣壳结构（Arc capsid）**：
Arc 蛋白在体外和体内可自发组装成**病毒样衣壳颗粒**（virus-like capsid），能够包裹Arc mRNA并通过胞外囊泡（extracellular vesicles）在神经元间转运（Ashley et al. 2018, PMID:29466744；Pastuzyn et al. 2018, PMID:29466743）。Arc 的 N 端 GAG 样结构域（类似逆转录病毒 capsid）和 C 端 linker 结构域分别驱动寡聚化和RNA结合。这表明 Arc 不只是胞内信号蛋白，还具有细胞间通讯功能（突触→核？神经元→神经元？），可能通过传递mRNA影响突触可塑性的协同，但体内功能意义仍不清楚（Q-arc-capsid-function）。

### Arc 在 LTD 中的作用

mGluR5 激活 → ERK 磷酸化激活 → FMRP 翻译抑制解除 → Arc mRNA 局部翻译 → Arc 蛋白在激活的树突棘出现
→ Arc 与 **dynamin**（GTPase，驱动囊泡颈部断裂）结合
→ Arc 与 **endophilin**（弯曲膜脂质，形成网格蛋白囊泡管状结构）结合
→ 两者共同加速网格蛋白包被小泡的形成和分裂
→ AMPAR 内吞效率提高 → 突触表面 AMPAR 减少 → LTD

### Arc 在 LTP 巩固中的作用

高频刺激/高 Ca²⁺ → BDNF-TrkB 信号 → Arc 表达升高 → Arc 激活 PAK1（p21 激活激酶）→ PAK1 磷酸化 LIMK1/2 → LIMK 磷酸化抑制 cofilin（actin 切割蛋白）→ 棘内肌动蛋白稳定聚合 → 树突棘结构持久放大 → L-LTP 维持

### Arc 与突触稳态（睡眠期选择性削减）

慢性过高活动 → Arc 积累 → 广泛 AMPAR 内吞 → 突触稳态性降低（synaptic scaling down）→ 防止网络过度激活/饱和

**2026-10-16 新增：睡眠期逆向突触标记（Inverse Synaptic Tagging）**

Diering（2022，PMID:36632309，PMC9826981）和 Suzuki 等（2020，PMID:32350140，PMC7229651）揭示了 Arc 在睡眠中的更精细功能：

**逆向标记原理**：
- Arc 与**去磷酸化 CaMKIIβ**（未被近期 LTP 激活的安静突触）亲和力**高** → 优先聚集于安静突触 → 调用 dynamin/endophilin 内吞 AMPA 受体
- Arc 与**磷酸化 CaMKIIβ**（刚经历 LTP 的印迹突触）亲和力**低** → 被排斥 → 印迹突触幸存

这使 Arc 的睡眠期功能成为一种**负向选择**：不标记重要突触，而是标记所有非重要突触并将其批量削减。净效果：噪音降低，印迹突触相对突出，记忆信噪比提升。

**遗传证据（Suzuki 2020）**：
- Arc KO 小鼠：睡眠剥夺后恢复睡眠（rebound）显著减弱（行为），GluA1 上调和磷酸化变化大幅减弱（分子）
- 核 Arc：睡眠剥夺后增加约 2.5 倍 → 在 PML 核体中抑制 GluA1 mRNA 转录（双重削减机制）
- 胞质 Arc：睡眠剥夺后同样增加约 2.5 倍 → 内吞执行

Arc 在睡眠中与 [[homer1a]] 协同：Homer1a 负责瓦解 mGluR1/5-IP3R 支架（GluA1/GluA2 松动），Arc 负责执行网格蛋白介导的内吞。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| Arc mRNA 快速运输到激活树突并局部翻译 | 荧光原位杂交（FISH）+ 多聚核糖体分析 | PMID:19690847 (PMC2803749) | 高 |
| Arc 敲除小鼠 LTP 可诱导但不能巩固（L-LTP 缺损） | Arc -/- 小鼠海马切片电生理；Morris 水迷宫学习正常但记忆保留受损 | PMID:19690847 (PMC2803749) | 高 |
| Arc 与 dynamin/endophilin 结合驱动 AMPAR 内吞 | Arc 截断突变体（NHD 缺失）无法促进内吞；共免疫沉淀证实直接结合 | PMID:25429259 (PMC4150421) | 中-高 |
| Arc 过表达导致 AMPAR 内吞增加、突触传递减弱 | 转染过表达 Arc 的神经元基础 EPSC 降低 | PMID:19690847 (PMC2803749) | 高 |
| Arc KO 小鼠睡眠剥夺后恢复睡眠减弱，GluA1 变化消失 | Arc -/- 小鼠睡眠行为记录 + Western blot 皮层 GluA1/p-GluA1 | PMID:32350140 (PMC7229651) | 高 |
| 核 Arc 在睡眠剥夺后增加约 2.5 倍，参与 GluA1 mRNA 抑制 | 核/胞质 Arc 分级分离 + PML 核体共定位 | PMID:32350140 (PMC7229651) | 中-高 |
| Arc 逆向突触标记（绕开 pCaMKIIβ 印迹突触） | 磷酸化特异性 Arc 结合实验（Diering 2022 综述整合） | PMID:36632309 (PMC9826981) | 中（直接体内验证不足） |

## 连接

- [[ltd]] — Arc 是 mGluR-LTD 的核心执行蛋白；与 dynamin/endophilin 形成内吞复合体
- [[ltp]] — Arc 参与 L-LTP 巩固（肌动蛋白稳定）；与 LTD 功能形成活动量依赖的双向关系
- [[ampa-receptor]] — Arc 直接驱动 AMPAR 网格蛋白内吞，是受体从突触移除的关键连接者
- [[memory-consolidation]] — Arc 敲除的记忆巩固缺损说明 Arc 是将 LTP 转化为持久记忆的关键分子
- [[engram-cells]] — Arc 标记活跃神经元（用于 ArcCreERT2 等印迹捕获工具）；Arc 表达量可能区分印迹细胞与非印迹细胞
- [[pkm-zeta]] — Arc 和 PKMζ 是 STC 框架中两个最重要的 L-LTP PRPs；Arc 负责结构稳定，PKMζ 负责功能维持
- [[synaptic-tagging-capture]] — Arc 是 STC 的重要 PRP（结构稳定成分）；与 PKMζ 共同构成 L-LTP 的分子执行层
- [[homer1a]] — 睡眠期协同执行突触削减：Homer1a 瓦解 mGluR5 支架，Arc 负责 AMPAR 内吞
- [[slow-wave-sleep]] — Arc 在 NREM 睡眠期执行逆向突触标记和 AMPAR 内吞，是 SHY 的分子实现
- [[homeostatic-plasticity]] — Arc 是睡眠依赖的突触稳态下调的必要执行蛋白

## 未解问题

- Q-arc-ltp-ltd-switch：同一细胞中，Arc 如何"决定"促进 LTP（肌动蛋白稳定）还是促进 LTD（AMPAR 内吞）？活动量？局部 Ca²⁺ 的精确水平？时间窗口？
- Q-arc-dendritic-targeting：Arc mRNA 被运输到特定的激活树突棘的分子机制是什么？参与运输的 RNA 结合蛋白和运动蛋白是哪些？
- Q-arc-capsid-function：Arc 病毒样衣壳在神经元间转运 mRNA 的体内功能意义是什么？这是否是突触可塑性在细胞群体水平协同的一种机制？与 STC 中 PRPs 的捕获有何关联？

## 修订历史

- 2026-10-16 · 修订 rev3 · 基于《睡眠如何修剪突触：Homer1a 与 Arc 的分子协奏》(#176) · 新增"睡眠期逆向突触标记"机制段落（Diering 2022/Suzuki 2020）；Arc KO 睡眠数据（PMID:32350140）；related 新增 homer1a、slow-wave-sleep、homeostatic-plasticity；连接段落新增 3 条；证据表新增 3 行；key_sources 新增 4 个
- 2026-09-21 · 修订 rev2 · 基于《记忆的分子守夜人》(#151) · 新增"病毒样衣壳结构"（Ashley/Pastuzyn 2018, PMID:29466744/29466743）；related新增pkm-zeta、synaptic-tagging-capture；连接新增pkm-zeta和synaptic-tagging-capture；opens_questions新增Q-arc-capsid-function；key_sources新增2个PMID；source_articles新增#151
- 2026-06-04 · 创建 · 基于《遗忘的精准：LTD 文章》· 初始置信度：高

## 来源文章

- [[2026-06-04-ltd-long-term-depression]]

---
title: NMDA 受体
slug: nmda-receptor
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-26
updated: 2026-10-21
revision_count: 8
dimensions: [molecular, synaptic, cellular, cognition, brain-region, disease]
related: [ampa-receptor, ltp, hebbian-learning, synaptic-transmission, voltage-gated-sodium-channel, calcium-channel, camkii, dendritic-computation, pyramidal-neuron, persistent-activity, working-memory, prefrontal-cortex, alzheimers-disease, amyloid-beta-oligomers, calcineurin, central-sensitization, gate-control-theory, excitotoxicity, major-depressive-disorder, bdnf, eef2k]
prerequisites: [synaptic-transmission, action-potential, membrane-potential]
opens_questions: [Q-nmda-coincidence-window, Q-glun2-switch-development, Q-abeta-oligomer-subtypes]
source_articles: [2026-05-26-nmda-receptor-ltp, 2026-05-27-dendritic-computation, 2026-06-05-prefrontal-working-memory, 2026-06-08-alzheimers-amyloid-synaptic-mechanism, 2026-07-17-stdp-spike-timing-dependent-plasticity, 2026-08-02-pain-nociception-spinal-dorsal-horn-acc, 2026-09-08-excitotoxicity-synaptic-extrasynaptic-calcium-death, 2026-10-21-depression-ketamine-rapid-antidepressant]
key_sources: ["PMID:22510460", "PMID:30037851", "PMID:6306230", "PMID:21543591", "PMID:17360908", "PMID:9852584", "PMC6793365", "PMC8488271", "PMID:19837031", "PMID:20842175", "PMID:2880938", "PMID:35078537", "PMID:21677641", "PMID:20724638"]
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

## NMDA 受体的第四重角色：突触外NR2B——LTP的"解毒剂"（AD相关）

**2026-06-08 新增（来自《记忆的分子遗忘》一文，解答 Q-nmda-alzheimer）**

NMDA受体存在**解剖学功能分工**：突触后致密区（PSD）内的**突触内NR2B**与PSD之外的**突触外NR2B**激活相同的钙离子内流，但下游信号截然相反：

| 位置 | 典型激活条件 | 下游信号级联 | 功能效果 |
|------|------------|------------|--------|
| **突触内NR2B**（PSD内） | 正常突触谷氨酸释放 | CaMKII → ERK → **CREB磷酸化** | LTP / 突触增强 |
| **突触外NR2B**（PSD外） | 谷氨酸溢出/Aβ激活 | p38 MAPK → **CREB去磷酸化** | LTP阻断 / 突触削弱 |

Aβ寡聚体**优先激活突触外NR2B**（Li et al. 2011, PMID:21543591），将NMDA受体总体信号流从"LTP促进"推向"LTP阻断"。NR2B选择性拮抗剂（Ro 25-6981）完全阻止了Aβ寡聚体对LTP的抑制，确认了突触外NR2B是关键靶点。

这回答了长期存在的疑问（Q-nmda-alzheimer）：Aβ不直接破坏NMDA受体，而是**改变了NR2B激活的解剖定位**——从"突触内（LTP信号）"转向"突触外（LTP反向信号）"，相当于把同一台机器从正向转档接到了反向传动链。

## NMDA 受体的双重身份

今日修订（2026-05-27）新增重要概念：NMDA 受体在细胞层面有**两种截然不同的功能角色**，服务于不同的时空尺度：

1. **突触层面巧合检测器（单突触 LTP）**：在单个树突棘的突触水平，作为前文（2026-05-26）描述的 Hebb 型学习门卫——同时需要谷氨酸（突触前）和去极化（突触后）。
2. **树突分支层面计算单元（NMDA 棘波）**：当一个树突分支上的多个 NMDA 受体同时激活时，形成再生性正反馈，产生持续 50–200 ms 的"NMDA 棘波"——这是高出单突触贡献许多倍的、全分支层面的非线性整合事件，使该分支成为独立的 sigmoid 计算单元。

这两个功能使用同一分子，但在空间尺度（单突触 vs 整分支）和时间尺度（毫秒 vs 数百毫秒）上都不同。它们分别对应"突触强度调整"和"分支计算"两个层次的信息处理。

## 连接

- [[major-depressive-disorder]] — 静息态 NMDA 活动通过 eEF2K 主动抑制 BDNF 翻译；氯胺酮阻断此静息态活动是 30 分钟快速抗抑郁的分子基础
- [[alzheimers-disease]] — NMDA受体（特别是突触外NR2B）是AD中LTP失效的核心分子靶点
- [[amyloid-beta-oligomers]] — Aβ寡聚体通过将NMDA激活从突触内偏转至突触外来阻断LTP
- [[ltp]] — NMDA 受体是 LTP 诱导的必要门卫（单突触层面）
- [[ampa-receptor]] — Ca²⁺ 内流后 AMPA 受体大量插入突触是 LTP 的主要表达机制
- [[camkii]] — Ca²⁺ 内流激活 CaMKII 是 LTP 诱导的第一步下游信号
- [[hebbian-learning]] — NMDA 受体双重门控在分子层面实现 Hebb 规则
- [[synaptic-transmission]] — NMDA 受体是突触传递中谷氨酸信号的重要接受者
- [[calcium-channel]] — 与电压门控 Ca²⁺ 通道同为突触 Ca²⁺ 内流的重要来源（但机制不同）
- [[dendritic-computation]] — NMDA 受体是树突 NMDA 棘波的核心机器，使单根树突分支成为独立计算单元

## NMDA 受体的第八重角色：静息态翻译阻断器与快速抗抑郁靶点（2026-10-21 新增）

**来源**：《氯胺酮与快速抗抑郁机制》文章 #189（Autry AE et al. 2011, PMID:21677641；Li N et al. 2010, PMID:20724638）

NMDA 受体在 MDD 研究中揭示了一个此前未认识到的功能——**静息态下作为 BDNF mRNA 翻译的主动抑制器**。

**核心发现**（Autry et al. 2011）：
- 突触的**自发活动**（自发微小 EPSP/IPSP）持续激活低水平 NMDA 受体
- 这种静息态 NMDA 激活维持 eEF2K（真核延伸因子 2 激酶）处于激活状态
- eEF2K 磷酸化 eEF2 → 抑制 BDNF mRNA 的翻译延伸
- 这不是"默认关闭"，而是 NMDA 受体**主动施加的翻译刹车**

**药理学验证**：
```
eEF2K 抑制剂（NH125）单独给药
    → 直接降低 p-eEF2
    → 海马 BDNF 蛋白↑
    → 产生与氯胺酮相同的快速抗抑郁行为效果
    → 无需阻断 NMDA 受体

氯胺酮在静息态阻断 NMDA
    → eEF2K 活性↓ → BDNF↑
    → 30 分钟行为抗抑郁效果
    → rapamycin（mTOR 抑制剂）不能阻断此 30 分钟效果
    （说明此路径不需要 mTOR，独立于 2-24 小时的突触生成路径）
```

与既有机制的关系：

| 时间窗口 | 机制 | NMDA 受体角色 | rapamycin 敏感？ |
|---------|------|-------------|----------------|
| 30 min | eEF2K→BDNF 脱抑制 | 静息态阻断解除翻译刹车 | 否 |
| 2-24 h | mTOR→突触蛋白合成 | SST 中间神经元去抑制→谷氨酸爆发→AMPA→mTOR | 是 |

这是 NMDA 受体的**第八重功能**（补充既有七种：Hebb 检测器、NMDA 棘波、工作记忆积分器、AD 中突触外 LTP 阻断、STDP 时序仲裁器、脊髓中枢敏化触发器、兴奋毒性主要 Ca²⁺ 入口）。

## NMDA 受体的第六重角色：脊髓中枢敏化的触发器（2026-08-02 新增）

**来源**：《痛觉的守门人》文章 #101（Basbaum et al. 2009, PMID:19837031）

脊髓背角发生的**中枢敏化**（chronic pain 的核心机制）与海马 LTP 共享分子机器，但发生在脊髓而非海马：

| 特征 | 海马 LTP | 脊髓 LTP（中枢敏化） |
|------|---------|------------------|
| 触发 | 高频突触刺激 | 持续 C 纤维伤害性输入 |
| NMDA 受体角色 | 巧合检测→Ca²⁺ 内流→CaMKII | 同上；另激活 PKC、Src、MAPK |
| 关键附加效应 | CaMKII→AMPA 受体增加 | PKC→AMPA 受体增加 + 前列腺素合成（COX-2 上调） |
| 功能 | 适应性学习 | 病理性慢性痛（wind-up 现象） |

**"Wind-up" 现象**：重复低频 C 纤维刺激下，脊髓投射神经元放电频率逐步递增——这是 NMDA 受体依赖的时间总和效应在疼痛中的类比。AP-5（NMDA 受体拮抗剂）可阻断 wind-up，证明 NMDA 受体的必要性。

**临床意义**：氯胺酮（ketamine，NMDA 受体阻断剂）在术前/术中使用可减少术后慢性痛的发生率——这是脊髓 NMDA 受体介导中枢敏化的临床验证。

见 [[central-sensitization]] 专页的完整回路描述。

## NMDA 受体在 STDP 中的时序仲裁角色

**2026-06-19 新增（来自《突触时序依赖可塑性》一文）**

NMDA 受体双重门控在 STDP 中的具体运作：

| 时序场景 | 分子事件 | Ca²⁺ 信号 | 结果 |
|---------|---------|---------|------|
| **突触前先（+5 to +20 ms）** | 谷氨酸先到→部分解锁；bAP 随后→Mg²⁺ 完全去除；两者重叠→充分开放 | 高峰 Ca²⁺ | LTP（CaMKII 激活） |
| **突触后先（-5 to -20 ms）** | bAP 先到→Mg²⁺ 临时去除；谷氨酸随后→膜已复极，Mg²⁺ 重新封堵 | 低幅持续 Ca²⁺ | LTD（钙调磷酸酶激活） |

**关键发现**（Bi & Poo 1998，PMID:9852584，PMC6793365）：施用 AP-5（NMDA 受体拮抗剂）后，无论时序如何，STDP 完全消失——证实 NMDA 受体是 STDP 的必要条件，不是充分条件。

**生理约束**：在 1.3 mM 生理 Ca²⁺ 浓度下，单次精确毫秒配对无法诱导 STDP（Inglebert & Debanne 2021，PMC8488271）——提示 NMDA 受体需要 θ 振荡（5–12 Hz）背景提供足够的 Ca²⁺ 积累才能可靠运作。

这是 NMDA 受体的**第五重功能角色**（补充既有四种：单突触 Hebb 检测器、NMDA 棘波、工作记忆持续活动积分器、AD 中 LTP 失效靶点）。

## 未解问题

- Q-nmda-coincidence-window：NMDA 受体的时间整合窗口（由 GluN2 亚型决定）如何在发育和学习中动态变化？
- Q-glun2-switch-development：幼年期 GluN2B 到成年期 GluN2A 的亚型切换的精确分子触发机制是什么？
- Q-nmda-alzheimer：**已部分解答（2026-06-08）**——Aβ寡聚体通过PrPC/mGluR5/Fyn激酶通路磷酸化NR2B，并优先激活突触外NR2B（p38/CREB失活）。未解部分：突触内vs突触外NR2B比例是否在AD中发生漂移？能否通过选择性增强突触内、抑制突触外NR2B来治疗AD？

## 修订历史

- 2026-05-26 · 创建 · 基于《NMDA 受体：突触的巧合检测器》一文 · 初始置信度：高
- 2026-05-27 · 修订 · 基于《树突：神经元内部的神经网络》一文 · 新增"NMDA 受体的双重身份"概念（突触层面巧合检测器 vs 分支层面 NMDA 棘波计算单元）；关键证据表新增 Smith 2013 体内视觉皮层证据 + Schiller 2000 NMDA 棘波证据；连接新增 dendritic-computation；dimensions 新增 cellular
- 2026-06-05 · 修订 · 基于《γ爆发、静默突触与持续放电》一文 · 新增第三重角色：PFC 工作记忆回路中作为时间积分器（慢衰减 τ ~100–300 ms 支撑循环激活的吸引子状态）；related 新增 persistent-activity, working-memory, prefrontal-cortex；dimensions 新增 brain-region（PMID:11476885；Wang 2001 吸引子模型）
- 2026-06-19 · 修订 · 基于《突触时序依赖可塑性》(#85) · 新增第五重角色：STDP 时序仲裁器（精确毫秒级时序 → Ca²⁺ 幅度 → LTP/LTD）；补充 Bi & Poo 1998 NMDA 受体对 STDP 的必要性证据（AP-5 消除 STDP）；新增生理钙浓度约束（1.3 mM 无效，需 θ 振荡）；key_sources 新增 PMID:9852584、PMC6793365、PMC8488271
- 2026-06-08 · 修订 · 基于《记忆的分子遗忘》一文 · 新增第四重角色：突触外NR2B-LTP反向信号路径；解答 Q-nmda-alzheimer（Aβ通过优先激活突触外NR2B/p38 MAPK阻断LTP，非直接破坏受体）；related 新增 alzheimers-disease、amyloid-beta-oligomers、calcineurin；dimensions 新增 disease；连接新增 alzheimers-disease、amyloid-beta-oligomers；key_sources 新增 PMID:21543591、PMID:17360908
- 2026-08-02 · 修订（rev6）· 基于《痛觉的守门人》文章（#101）· 新增第六重角色：脊髓背角中枢敏化触发器（wind-up 现象；与海马 LTP 同源机制；氯胺酮临床验证）；related 新增 central-sensitization、gate-control-theory；source_articles 新增 2026-08-02-pain-nociception；key_sources 新增 PMID:19837031
- 2026-09-08 · 修订（rev7）· 基于《兴奋毒性》文章（#138）· 新增第七重角色：兴奋毒性的主要Ca²⁺入口（突触外激活→Jacob/DAPK1/Calpain死亡级联 vs 突触内激活→CREB/AID存活屏障）；related 新增 excitotoxicity；source_articles 新增 2026-09-08-excitotoxicity；key_sources 新增 PMID:20842175, PMID:2880938, PMID:35078537
- 2026-10-21 · 修订（rev8）· 基于《氯胺酮与快速抗抑郁机制》(#189) · 新增第八重角色：静息态翻译阻断器（eEF2K-BDNF路径；30分钟机制；rapamycin非敏感路径与2-24h mTOR路径的时序区分）；related 新增 major-depressive-disorder, bdnf, eef2k；连接新增 major-depressive-disorder；source_articles 新增 #189；key_sources 新增 PMID:21677641, PMID:20724638

## 来源文章

- [[2026-05-26-nmda-receptor-ltp]]
- [[2026-05-27-dendritic-computation]]
- [[2026-06-05-prefrontal-working-memory]]
- [[2026-08-02-pain-nociception-spinal-dorsal-horn-acc]]
- [[2026-09-08-excitotoxicity-synaptic-extrasynaptic-calcium-death]]
- [[2026-10-21-depression-ketamine-rapid-antidepressant]]

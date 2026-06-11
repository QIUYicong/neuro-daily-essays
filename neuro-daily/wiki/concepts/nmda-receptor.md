---
title: NMDA 受体
slug: nmda-receptor
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-26
updated: 2026-09-15
revision_count: 5
dimensions: [molecular, synaptic, cellular, cognition, brain-region, disease]
related: [ampa-receptor, ltp, hebbian-learning, synaptic-transmission, voltage-gated-sodium-channel, calcium-channel, camkii, dendritic-computation, pyramidal-neuron, persistent-activity, working-memory, prefrontal-cortex, alzheimers-disease, amyloid-beta-oligomers, calcineurin, glun2-developmental-switch, bcm-rule, critical-period-plasticity]
prerequisites: [synaptic-transmission, action-potential, membrane-potential]
opens_questions: [Q-nmda-coincidence-window, Q-glun2-switch-development, Q-abeta-oligomer-subtypes, Q-glun2-triheteromeric-region-ratio]
source_articles: [2026-05-26-nmda-receptor-ltp, 2026-05-27-dendritic-computation, 2026-06-05-prefrontal-working-memory, 2026-06-08-alzheimers-amyloid-synaptic-mechanism, 2026-09-15-nmda-receptor-subunit-developmental-switch]
key_sources: ["PMID:22510460", "PMID:30037851", "PMID:6306230", "PMID:21543591", "PMID:17360908", "PMID:22960932", "PMID:28554889", "PMID:37290118", "PMID:35484243"]
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

GluN2B 在幼年期高表达，其更长的衰减时间常数意味着更宽的时间整合窗口，是关键期可塑性的分子基础之一。随发育进行，GluN2A:2B 比值逐渐向 GluN2A 偏移；在人类视觉皮层，这一比值在约 **36 岁**才达到峰值，老年期（>55 岁）GluN2A 骤降约 75%，比值回归婴儿水平（详见 [[glun2-developmental-switch]]）。成年期突触主要由**三异四聚体**（GluN1/GluN2A/GluN2B）组成，保留 GluN2B 以维持 CaMKII 锚定。

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

## NMDA 受体的第五重角色：GluN2 亚单位切换——可塑性阈值的终身调节（2026-09-15 新增）

**核心新增（来自《NMDA 受体的两张脸》一文 #145，解答 Q-glun2-switch-development）**

NMDA 受体的 GluN2B→GluN2A 发育切换不仅是一个成熟标志，它是大脑在整个生命周期动态调节突触可塑性阈值的核心分子机制：

- **切换驱动力**：REST 转录因子表观遗传沉默 *Grin2b* + GluN2A 蛋白浓度独立上升（非 CTD 机制）；经验/感觉活动参与调速
- **功能效果**：GluN2A 取代 GluN2B → 衰减时间常数从 ~300–400 ms 收窄至 ~40–50 ms → LTP 阈值升高（需更强、更同步的输入）→ BCM 修改阈值 θ 右移
- **CaMKII 连接**：GluN2B CTD 是 CaMKII 的直接锚定位点；此结合是 LTP 的充要条件之一（I205K 突变 → LTP 消失，PMID:37290118）；成年三异四聚体保留 GluN2B 以维持此锚定
- **平衡的重要性**：GluN2A 过量表达（K879R）同时损害 LTP 和 LTD + 认知（PMID:35484243）；大脑追求的是 GluN2A:2B 的动态平衡，而非单纯 GluN2A 最大化
- **人类独特性**：峰值约 36 岁（远超关键期闭合时间）；老年期 GluN2A 骤降 75%（PMID:28554889）

详见专门页面 [[glun2-developmental-switch]]。

## 连接

- [[glun2-developmental-switch]] — NMDA 受体亚单位切换的专门页面（GluN2B→GluN2A 的分子机制、时间线、可塑性效果）
- [[bcm-rule]] — GluN2A:2B 比值漂移在分子层面实现 BCM 滑动修改阈值 θ
- [[critical-period-plasticity]] — GluN2B 主导期与关键期高度重叠；REST 是共同调控因子
- [[alzheimers-disease]] — NMDA受体（特别是突触外NR2B）是AD中LTP失效的核心分子靶点
- [[amyloid-beta-oligomers]] — Aβ寡聚体通过将NMDA激活从突触内偏转至突触外来阻断LTP
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
- Q-nmda-alzheimer：**已部分解答（2026-06-08）**——Aβ寡聚体通过PrPC/mGluR5/Fyn激酶通路磷酸化NR2B，并优先激活突触外NR2B（p38/CREB失活）。未解部分：突触内vs突触外NR2B比例是否在AD中发生漂移？能否通过选择性增强突触内、抑制突触外NR2B来治疗AD？

## 修订历史

- 2026-05-26 · 创建 · 基于《NMDA 受体：突触的巧合检测器》一文 · 初始置信度：高
- 2026-05-27 · 修订 · 基于《树突：神经元内部的神经网络》一文 · 新增"NMDA 受体的双重身份"概念（突触层面巧合检测器 vs 分支层面 NMDA 棘波计算单元）；关键证据表新增 Smith 2013 体内视觉皮层证据 + Schiller 2000 NMDA 棘波证据；连接新增 dendritic-computation；dimensions 新增 cellular
- 2026-06-05 · 修订 · 基于《γ爆发、静默突触与持续放电》一文 · 新增第三重角色：PFC 工作记忆回路中作为时间积分器（慢衰减 τ ~100–300 ms 支撑循环激活的吸引子状态）；related 新增 persistent-activity, working-memory, prefrontal-cortex；dimensions 新增 brain-region（PMID:11476885；Wang 2001 吸引子模型）
- 2026-06-08 · 修订 · 基于《记忆的分子遗忘》一文 · 新增第四重角色：突触外NR2B-LTP反向信号路径；解答 Q-nmda-alzheimer（Aβ通过优先激活突触外NR2B/p38 MAPK阻断LTP，非直接破坏受体）；related 新增 alzheimers-disease、amyloid-beta-oligomers、calcineurin；dimensions 新增 disease；连接新增 alzheimers-disease、amyloid-beta-oligomers；key_sources 新增 PMID:21543591、PMID:17360908
- 2026-09-15 · 修订 · 基于《NMDA 受体的两张脸》一文（#145）· 新增第五重角色：GluN2 亚单位切换与突触可塑性阈值的终身调节；GluN2B 衰减时间 ~300–400ms vs GluN2A ~40–50ms 对比详述；人类皮层 GluN2A:2B 峰值约36岁 + 老年期骤降75%（PMID:28554889）；CaMKII-GluN2B 物理结合是 LTP 充要条件（PMID:37290118）；"平衡优于最大化"：GluN2A 过量损害 LTP+LTD（PMID:35484243）；部分解答 Q-glun2-switch-development；新建专门 wiki 页 glun2-developmental-switch；related 新增 glun2-developmental-switch, bcm-rule, critical-period-plasticity；key_sources 新增 PMID:22960932, 28554889, 37290118, 35484243

## 来源文章

- [[2026-05-26-nmda-receptor-ltp]]
- [[2026-05-27-dendritic-computation]]
- [[2026-06-05-prefrontal-working-memory]]

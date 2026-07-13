---
title: 复合素
slug: complexin
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-07-12
updated: 2026-07-14
revision_count: 2
dimensions: [molecular, synaptic]
related: [SNARE-complex, synaptotagmin, active-zone, synaptic-transmission, munc13, munc18]
prerequisites: [SNARE-complex, synaptic-transmission]
opens_questions: [Q-cpx-tripartite-generality, Q-cpx-retinal-dynamics, Q-cpx-primordial-evidence, Q-cpx-disease-causality]
source_articles: [2026-07-12-complexin-dual-function-vesicle-fusion]
key_sources: ["PMID:19164751", "PMID:22068972", "PMID:23238737", "PMID:28813412", "PMID:39627811", "PMID:42364981"]
---

# 复合素 (Complexin)

> **一句话定义**：Complexin 是一种约 130 个氨基酸的可溶性突触前调控蛋白，通过四个功能不同的结构域同时对 SNARE 复合体施加相反的两种效应——钳制自发融合、催化钙触发的诱发融合——2026 年新证据提示这一双重能力可能起源于一个比 synaptotagmin、甚至比钙触发释放机制本身都更古老的通用胞吐调控机制。

## 当前理解

Complexin 结合在几乎完全组装的 SNARE 复合体（[[SNARE-complex]]）上，是连接 SNARE 拉链组装与 [[synaptotagmin]] 钙感知这两个环节之间的关键调控枢纽。它并不是一个简单的"开/关"开关，而是通过四个结构域的协同/拮抗作用，在同一个分子复合体上同时执行两种表面矛盾的功能：

- 平时（无 Ca²⁺）：辅助螺旋（AH）钳制 SNARE 复合体，阻止其在钙信号到来前完全拉链、触发自发融合。
- Ca²⁺ 到来后：synaptotagmin 感知钙信号，解除 complexin 的钳制，同时 complexin 的 N 端结构域（NTD）和 C 端结构域（CTD）转为促进角色，加速 SNARE 完全拉链和融合孔形成。

2017 年的晶体结构（Zhou et al., *Nature*，PMID:28813412）首次在原子分辨率上解释了这把"锁"如何工作：两个 synaptotagmin-1 C2B 结构域分别通过"主要界面"和新发现的"三方界面"接触同一个 SNARE 复合体，其中三方界面同时涉及 SNARE、synaptotagmin-1 的 HA 螺旋和 complexin 的中央螺旋，三者拼接成一个六螺旋束，界面接触面积达 990 Å²。这一"预融合锁定"结构不涉及 Ca²⁺ 结合位点本身，只有当 Ca²⁺ 结合到 synaptotagmin-1 上才会被解开。

2026 年 6 月的一项新研究（Chen et al., *Nat Commun*，PMID:42364981）把这一图景推向更深的演化维度：作者在天然缺少 synaptotagmin 的脂肪细胞 GLUT4 囊泡胞吐通路中，发现 complexin 仍然发挥作用——但这里它完全独立于 synaptotagmin，只保留"催化"这一半功能（加速激素触发的胞吐速率），"钳制"功能完全缺席。基于 complexin 在演化上早于 synaptotagmin 出现这一事实，作者提出：complexin 最原始的功能可能是不依赖 Ca²⁺、独立加速胞吐；直到 synaptotagmin 后续出现，complexin 才被"招募"去执行与钙触发释放协调的钳制角色。换言之，我们在突触里研究得最透彻的"钳制+解锁"精密机制，很可能是历史上后加上去的特化层。**这一演化时间顺序论证目前依据的详细跨物种分子系统发生学证据尚未被本知识库核实**，列为待深入的开放问题（见 Q-cpx-primordial-evidence）。

## 关键机制

### 分子层：四个结构域的分工

- **中央 α 螺旋（CH）**：高度保守，紧密结合 synaptobrevin 与 syntaxin-1，是 complexin 附着到 SNARE 复合体的主接口；脂肪细胞中不依赖 synaptotagmin 的催化功能同样依赖这一结构域。
- **辅助 α 螺旋（AH）**：插入 synaptobrevin C 端区域，增强囊泡膜与突触前膜间的静电排斥，是"钳制"效应的直接执行者。
- **N 端结构域（NTD）**：与 AH 相反，稳定 SNARE 复合体 C 端、部分抵消 AH 的钳制效应，是"催化/激活"效应的来源。
- **C 端结构域（CTD）**：感知膜曲率、稳定新形成的融合孔、加速融合孔形成速率；在脂肪细胞胞吐中，这一结构域通过重塑脂双层促成 synaptotagmin 非依赖性的加速功能。

（综述来源：PMID:39627811）

### 细胞/突触层：功能证据

Maximov 等（2009，PMID:19164751，PMC全文）用 RNAi 敲低+拯救实验及 synaptobrevin 点突变交叉验证，量化了 complexin 缺失的"双向脱靶"表型：自发微小突触电流频率上升 3–4 倍，诱发释放幅度下降 3–4 倍且失同步。果蝇神经肌肉接头的独立证据（Jorquera et al., 2012，PMID:23238737，PMC全文）表明，complexin 通过调节 synaptotagmin 激活的时机与性质，同时塑形自发释放和诱发释放两条独立通路，而非简单的二元开关。

### 特化层：亚型分化（CPX1-4）

哺乳动物有四个旁系同源基因。CPX1/CPX2 广泛分布于中枢神经系统，不含 CAAX 基序，与 SNARE 亲和力高，负责常规突触的快速同步释放。CPX3/CPX4 是脊椎动物特有、仅表达于视网膜带状突触（ribbon synapse）的旁系同源物，含 CAAX 基序（可法尼基化），与 SNARE 亲和力更低（尤其 CPX4），但能支持带状突触持续、高频、宽动态范围的谷氨酸释放。CPX3/4 过表达可有效代偿 CPX1/2 双敲除神经元中的释放缺失，说明四者共享同一套底层分子逻辑，只是被各自所在突触类型"调了参数"。（综述来源：PMID:39627811）

### 疾病相关性

人类 CPLX1（CPX1 编码基因）功能丧失突变与常染色体隐性遗传性癫痫性脑病 63（DEE63，MIM:617976）相关，最早由大规模罕见变异外显子测序研究发现（Karaca et al., 2015, *Neuron*，PMID:26539891，摘要级）。UniProt 官方注释（O14810）同时记录 CPX1 在帕金森病患者黑质中表达上调（较早的组织学观察，PMID:9853440，本文未精读）。综述（PMID:39627811）另提及 CPX1 与阿尔茨海默病、CPX2 与精神分裂症的关联性证据，但本知识库尚未核实具体因果机制的原始文献，暂列为相关性观察，不做因果或诊疗层面的推论。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Complexin 缺失导致自发释放上升、诱发释放下降且失同步（双向脱靶） | RNAi敲低+拯救、knock-in小鼠电生理 | PMID:19164751（PMC全文） | 高 |
| 四结构域（CH/AH/NTD/CTD）分别执行SNARE结合/钳制/激活/融合孔调控 | 结构-功能综述 | PMID:39627811（PMC全文） | 高 |
| 晶体结构揭示Syt1-SNARE-Cpx三方界面，Ca²⁺结合前锁定、结合后解锁 | X射线晶体学(1.85-2.5Å)+突变功能验证 | PMID:28813412（PMC全文） | 高 |
| Complexin通过调节Syt激活时机同时塑形自发与诱发释放 | 果蝇NMJ电生理+分子遗传学 | PMID:23238737（PMC全文） | 高 |
| Complexin在脂肪细胞GLUT4胞吐中独立于Syt发挥纯正向调控作用，提示更古老祖先功能 | 细胞生物学+结构-功能突变分析 | PMID:42364981（开放获取） | 中—高（单篇最新研究，演化推论待更多证据） |
| CPX1功能丧失突变导致DEE63 | 外显子测序发现+官方数据库注释 | UniProt O14810；PMID:26539891（摘要级） | 中 |

## 连接

- [[SNARE-complex]] — complexin 结合并调控 SNARE 复合体的拉链组装状态
- [[synaptotagmin]] — 二者在突触中协同工作：Ca²⁺触发 Syt1 解除 complexin 的钳制；晶体结构显示三方界面直接连接二者
- [[active-zone]] — complexin 的调控作用发生在活动区囊泡对接/预融合位点
- [[synaptic-transmission]] — complexin 是决定突触传递时间精度的关键调控蛋白之一
- [[munc13]] — 与 complexin 分属不同调控层（囊泡启动 vs 融合钳制/催化），共同构成活动区"同分子不同配比造出不同突触性格"这一更大原则下的实例
- [[munc18]] — 作用于组装链路的更上游阶段：Munc18-1 在 Syntaxin 闭合构象下充当模板、预先对齐 SNARE 基序；complexin 则在组装接近完成后介入，钳制并催化最后的拉链/融合步骤

## 未解问题

- Q-cpx-tripartite-generality：三方界面结构是否对 Syt2、Syt9（快速诱发释放）及 Syt7（异步释放）同样成立？
- Q-cpx-retinal-dynamics：CPX3/4 更低的SNARE亲和力如何仍支持带状突触持续高频释放的具体动力学补偿机制？
- Q-cpx-primordial-evidence：complexin 早于 synaptotagmin 演化出现的具体跨物种分子系统发生学证据是什么？
- Q-cpx-disease-causality：CPX1/CPX2 与阿尔茨海默病/精神分裂症的关联是相关性还是已验证的因果链条？

## 修订历史

- 2026-07-12 · 创建 · 基于《刹车还是油门？Complexin 如何用同一段螺旋同时钳制与催化囊泡融合》一文 · 初始置信度：高
- 2026-07-14 · 修订 · 基于《一把先关上的锁：Munc18-1 如何在"堵住"SNARE的同时，充当组装它的模板》一文 · 新增munc18交叉链接，说明二者在囊泡融合链路中的分工（组装启动模板 vs 拉链后期钳制/催化）

## 来源文章

- [[2026-07-12-complexin-dual-function-vesicle-fusion]]

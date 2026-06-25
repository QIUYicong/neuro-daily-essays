---
title: "记忆的分子守夜人：PKMζ的发现、颠覆与新生"
slug: pkm-zeta-late-ltp-persistence
number: 151
date: 2026-09-21
tags: [ltp, memory, pkm-zeta, synaptic-plasticity, ampa-receptor, kibra, zip]
related_wiki: [pkm-zeta, ltp, synaptic-tagging-capture, arc-arg31, camkii]
open_questions_addressed: [Q-ltp-lifetime-mechanism]
key_sources: ["PMID:16463388", "PMID:15958741", "PMID:21119699", "PMID:20383136", "PMID:23283171", "PMID:23283174", "PMID:23283170", "PMID:27187150", "PMID:33540466", "PMID:39814881", "PMID:41814337", "PMID:41889799"]
---

# 记忆的分子守夜人：PKMζ的发现、颠覆与新生

## 一个令弗朗西斯·克里克寝食难安的问题

1984年，DNA双螺旋的发现者弗朗西斯·克里克在《自然》杂志发表了一篇不长的论文，提出了神经科学史上最深刻的问题之一：

"突触的分子基础必然不断更新。在蛋白质不断降解和替换的过程中，信息是如何被保存的？"

这个问题的锋芒在于它的精确性。我们知道，大多数蛋白质在神经元中的半衰期约为24小时至几周。突触后密度（PSD）的支架蛋白寿命略长一些，但仍以天计。然而人类可以记住几十年前的一张脸、一段旋律、一种味道。

这两个时间尺度之间，横亘着40年来神经科学家最想填平的沟壑。

PKMζ——蛋白激酶M-ζ——是目前最接近这个答案的分子。它的故事，跌宕起伏得像一部侦探小说：发现、膜拜、颠覆、重建。而最终的结局，比最初设想的更加深刻。

---

## PKMζ是什么：一个先天"开机"的激酶

PKMζ（Protein Kinase M-zeta）是非典型蛋白激酶C家族（aPKC）中的ζ亚型的特殊剪接形式。理解它为什么特殊，需要先了解蛋白激酶的一般工作方式。

大多数蛋白激酶都有两个结构域：**调节结构域**（regulatory domain）负责"关机"——在静息状态下折叠住催化活性位点；**催化结构域**（catalytic domain）负责执行磷酸化。激酶被激活，需要第二信使（如Ca²⁺、DAG）或磷酸化信号解除调节结构域的抑制。

PKMζ打破了这个规律。它的mRNA从PKCζ基因内部的独立启动子转录，**不包含调节结构域**——它天生只有催化结构域，没有可以"关机"的开关。一旦合成，它就持续处于激活状态（Sacktor 2011, PMID:21119699）。

更重要的是，这种mRNA在神经元中有独特的分布：它大量存在于树突中，在活动依赖性条件下可以被快速翻译。这意味着，当突触发生强烈的Hebbian活动时，PKMζ蛋白可以在局部快速合成，无需等待细胞体。

这一分子特性使研究者从一开始就对PKMζ抱有极大期望：一个在突触活动后本地合成、一旦合成便持续激活的激酶——这不就是克里克问题的答案吗？

---

## PKMζ如何维持LTP：增加突触的AMPA受体数量

2006年，Ling等人用最直接的方式证明了PKMζ的突触功能（PMID:16463388）：在海马CA1锥体细胞中，单独过表达PKMζ就能将突触处的AMPA受体数量提高至近两倍。这种效应不需要任何突触刺激，是PKMζ催化活性的直接后果。

机制在随后几年被厘清（Migues et al. 2010, PMID:20383136）：

```
PKMζ激活
  → 抑制含GluA2亚基的AMPA受体内吞
  → 更多AMPA受体保留在突触后膜
  → 突触传递效率增强（LTP的表达）
```

这里的关键是**GluA2**（也称GluR2）亚基。含GluA2的AMPA受体（GluA1/A2异聚体）是成人海马最主要的AMPA受体类型，通常经由GRIP1/ABP→NSF通路进行内吞循环。PKMζ通过磷酸化调控这一通路，将"内吞倾向"转变为"驻留在突触"。

换言之，PKMζ是一个**持续阻止突触减弱**的分子。只要它存在且有活性，它就不断地将AMPA受体"钉"在突触上。这是一种动态维持，而非静态储存——与克里克问题的逻辑完全吻合：不需要蛋白质永生，只需要功能状态的持续再生。

---

## PKMζ是突触标记与捕获的第一个明确PRP

2005年，Sajikumar等人完成了一个关键实验（PMID:15958741），将PKMζ放进了突触标记与捕获（STC）框架中。

STC的经典问题是：弱刺激诱导的早期LTP（E-LTP）如何在有"强刺激"或"奖励信号"提供时升级为晚期LTP（L-LTP）？答案依赖于"可塑性相关蛋白"（PRPs）的合成和捕获，但PRPs的分子身份长期不明。

Sajikumar的实验表明，PKMζ是**第一个被明确鉴定的L-LTP特异性PRP**：
- E-LTP诱导后，在标签有效期内提供蛋白质合成依赖的PKMζ → E-LTP升级为L-LTP
- 反之，若阻断PKMζ的合成，强刺激仍能诱导E-LTP，但无法形成L-LTP
- PKMζ蛋白合成在强刺激后30–60分钟内发生，符合"PRP"的时间动力学

这一发现将PKMζ提升为突触持久性记忆的中心分子，也为ZIP实验铺垫了理论基础。

---

## ZIP实验：注射进大脑，抹去记忆

2006–2010年间，Sacktor实验室和其他团队用ZIP（zeta-inhibitory peptide，PKMζ伪底物抑制肽）做了一系列令人震惊的实验：

- **空间记忆**：大鼠学会莫里斯水迷宫后，海马内注射ZIP → 1天后记忆消失，且不可恢复（Serrano et al. 2008）
- **厌恶条件反射**：岛叶皮层注射ZIP → 诱导后1个月的味道厌恶记忆被完全抹去
- **鸟类鸣唱记忆**：纹状体注射ZIP → 破坏已稳定的鸣唱记忆

这些结果在神经科学界引起轰动。"ZIP可以抹去已经巩固的记忆"——这是首次有工具能在行为层面直接干预已形成的长期记忆。PKMζ被定位为**记忆维持的必要分子机器**。

然而，这个故事在2013年遭遇了最大的挑战。

---

## 2013年的双重炸弹：基因敲除小鼠记忆正常

2013年1月，《自然》杂志同期发表了两篇论文，颠覆了"PKMζ是L-LTP必要分子"的信念。

**Lee et al. 2013（PMID:23283171）**：构建了Prkcz（PKMζ基因）条件性敲除小鼠。结果令人困惑：这些小鼠表现出**完全正常的LTP和空间记忆**。他们的莫里斯水迷宫成绩与对照组没有差异，长期记忆同样正常保留。

**Volk et al. 2013（PMID:23283174）**：用独立的敲除策略得到同样结论——没有PKMζ的小鼠，海马依然可以诱导和维持LTP，行为记忆完好。

同期的评论文章（Frankland & Josselyn 2013, PMID:23283170）给出了贴切的标题：《记忆与单一分子》（"Memory and the single molecule"）——指出单一分子不可能独自支撑如此复杂的功能。

更尖锐的是ZIP悖论：**即便在PKMζ敲除小鼠中，ZIP注射依然能够破坏记忆**（Bhatt & Bhatt et al.发现）。如果ZIP的效应是通过抑制PKMζ实现的，那在没有PKMζ的小鼠上怎么还能起效？

研究者开始怀疑：ZIP的作用可能根本不是通过PKMζ。

---

## 拯救：补偿性激酶与双敲除的终局

2013年的危机促使Sacktor团队和其他实验室深挖PKMζ敲除小鼠的代偿机制。答案来自2016年。

**Tsokas et al. 2016（PMID:27187150）**发现，在PKMζ从出生起就缺失的小鼠中，另一个非典型PKC——**PKCι/λ**（atypical PKC iota/lambda）发生了**代偿性上调**。PKCι/λ与PKMζ有着相似的催化结构域，在PKMζ缺失时，它能执行类似的AMPA受体维持功能。

这解释了为什么敲除小鼠记忆正常：**发育性补偿掩盖了PKMζ的必要性**。

这一发现导向了最终的实验设计：同时敲除PKMζ和PKCι/λ。

**Tsokas et al. 2026（PMID:41889799，bioRxiv预印本）**报告了双敲除的结果：
- 同时删除PKMζ和PKCι/λ后，海马CA1区的**晚期LTP（L-LTP）完全消失**
- 电生理记录显示，HFS（高频刺激）仍能诱导短暂的E-LTP，但3小时后衰退至基线
- 行为测试中，双敲除小鼠的长期空间记忆严重受损
- 单独敲除任何一个基因，L-LTP均正常

这是对原始假说最强的支持：**PKMζ和PKCι/λ共同构成了L-LTP维持所需的非典型aPKC功能层**。单一分子并非不可或缺，但这类分子的功能本身不可或缺。

---

## ZIP的真实作用：阳离子电荷与内吞途径

与此同时，关于ZIP的机制也有了新答案。

**Stokes et al. 2025（PMID:39814881，Nature）**系统性地研究了ZIP的作用机制。他们构建了一系列ZIP变体，包括：
- 保留阳离子电荷但改变氨基酸序列的肽段（不再是PKMζ伪底物）
- 中性化肽段（移除正电荷）

结论十分清晰：**ZIP的记忆破坏作用来自其阳离子电荷，而非PKMζ伪底物序列**。具体机制涉及**endophilin-A2**（内源蛋白）介导的**巨胞饮作用（macropinocytosis）**：阳离子肽被细胞内吞时，触发了一种非特异性的突触后膜AMPA受体大规模内吞。

这一发现完全重新诠释了过去20年的ZIP实验：ZIP确实能破坏记忆，但它的效应是非特异的急性干扰，而非PKMζ功能的精准缺失。这并不否定PKMζ的重要性，但意味着用ZIP作为PKMζ功能探针的所有研究结论都需要重新评估。

---

## 最新框架：KIBRA-PKMζ寡聚体与分子更新悖论

2026年，Hsieh等人发表了直接回答克里克问题的机制（PMID:41814337）。

**KIBRA**是一种支架蛋白，已知与记忆相关遗传多态性有关（KIBRA T基因型携带者表现出更好的情节记忆）。但它与PKMζ的关系直到2024-2026年才被厘清。

关键发现：
1. **PKMζ与KIBRA在突触后密度形成稳定的多聚体复合物**（AlphaFold3模型预测，体外实验验证）
2. 新合成的未磷酸化PKMζ（"新PKMζ"）与活化状态的KIBRA-PKMζ复合物结合后，被"感染性地"磷酸化激活（类似朊病毒机制）
3. 通过亚基交换，磷酸化状态可以在蛋白更新中**代代传递**：老蛋白降解，新蛋白加入后继承激活状态

这正是克里克所设想的解决方案类型——不需要每个分子永生，而是**激活状态通过分子间相互作用传递，使集体功能状态超越个体分子寿命**。

研究者还开发了K-ZAP（KIBRA-拮抗肽）和ζ-stat两种工具，能够精确干预KIBRA-PKMζ复合物，区分"新合成PKMζ并入"与"已有PKMζ维持"，为未来机制研究提供了更精准的手术刀。

---

## 体内证据：记忆神经元中PKMζ持续存在1个月

以上机制研究的可信度，最终需要体内证据支撑。

**Hsieh et al. 2021（PMID:33540466）**使用了一种精巧的策略：通过c-Fos启动子驱动的DREADD系统（化学遗传学），标记出情境恐惧记忆编码时被激活的海马CA1细胞（"记忆神经元"），然后在**记忆形成后1个月**检测这些特定细胞中的PKMζ水平。

结果：与非记忆神经元相比，被标记的记忆神经元中PKMζ持续维持在**更高水平**，且这种差异在1个月后仍然显著。

这是目前最直接的证据，表明PKMζ在自然记忆巩固后，在相关神经元中长期保持升高，与分子周转背景下的记忆持久性直接关联。

---

## 认知地图的更新：这场争论教会我们什么

PKMζ的故事是神经科学方法论的一次重要教育。

**发现阶段（1993-2012）**的过度解读源于工具的特异性假设未经严格验证——ZIP被默认为PKMζ特异性工具，而实际上它的效应机制完全不同。这提醒我们：药理学工具的特异性必须与遗传学工具互相校验，不能孤立使用。

**2013年危机**揭示的是**神经回路的冗余原则**：记忆系统通过多个分子机制实现功能冗余，单一分子的缺失可以被部分补偿。这不是PKMζ的失败，而是大脑稳健性的体现——如果一个如此关键的功能只由一个分子支撑，将面临太大的灾难性失效风险。

**2016-2026年的重建**揭示了更深的真相：PKMζ（和PKCι/λ）共同维持的**非典型aPKC功能层**才是L-LTP必需的，单一分子不够但功能本身不可或缺。而KIBRA-PKMζ寡聚体机制直接回答了克里克1984年的问题：分子通过**功能状态的传染性传播**（而非分子本体的永生）实现记忆的持久。

---

## 与今天之前理解的对比

在写下这篇文章之前，ltp.md中存在一个未解问题Q-ltp-lifetime-mechanism：**"LTP如何在蛋白周转的情况下持续数年？"**

现在我们有了一个完整（虽然仍在持续完善中）的回答框架：

| 问题维度 | 答案 |
|---------|------|
| 哪个分子负责维持LTP？ | 非典型aPKC功能层（PKMζ + PKCι/λ），具有功能冗余 |
| 如何对抗蛋白周转？ | KIBRA-PKMζ寡聚体：新蛋白被"感染性磷酸化"，继承激活状态 |
| 在哪里维持？ | 突触后密度（PKMζ持续阻止GluA2-AMPAR内吞） |
| 体内证据？ | 记忆神经元中PKMζ在1个月后仍升高（Hsieh 2021） |
| ZIP抹去记忆的机制？ | 阳离子电荷→endophilin-A2→巨胞饮→AMPAR非特异性内吞（非PKMζ特异性） |
| 单一分子足够吗？ | 不够；但aPKC功能本身（PKMζ+PKCι/λ双层）是L-LTP必需的 |

这不是一个让人失望的结论——恰恰相反，它比"只需要PKMζ"的简单版本更加迷人。大脑用**功能层而非分子层**来构建记忆，用**感染性传播而非分子永生**来对抗时间。

克里克的问题在40年后有了答案。但新的问题随之而来：KIBRA-PKMζ寡聚体的结构稳定性在体内如何维持？在不同脑区、不同类型记忆中，功能冗余的比例如何？用K-ZAP/ζ-stat精准干预后能否在行为层面实现选择性记忆修改？

这场守夜仍在继续。

---

## 参考文献

- Ling DSF, et al. (2006). *Protein kinase Mzeta is necessary and sufficient for LTP maintenance.* Nat Neurosci. PMID:16463388
- Sajikumar S, et al. (2005). *Late-associativity, synaptic tagging, and the role of dopamine during LTP and LTD.* J Neurosci. PMID:15958741, PMC6724879
- Sacktor TC. (2011). *How does PKMζ maintain long-term memory?* Nat Rev Neurosci. PMID:21119699
- Migues PV, et al. (2010). *PKMζ maintains spatial, instrumental, and Pavlovian conditioned fear memories.* Nat Neurosci. PMID:20383136
- Lee AM, et al. (2013). *Prkcz null mice show normal learning and memory.* Nature. PMID:23283171, PMC3548047
- Volk LJ, et al. (2013). *PKM-ζ is not required for hippocampal synaptic plasticity, learning and memory.* Nature. PMID:23283174, PMC3830948
- Frankland PW, Josselyn SA. (2013). *Memory and the single molecule.* Nature. PMID:23283170
- Tsokas P, et al. (2016). *Compensation for PKMζ in long-term potentiation and spatial long-term memory.* eLife. PMID:27187150, PMC4869915
- Hsieh C, et al. (2021). *Persistent increased PKMζ in memory-activated neurons.* Eur J Neurosci. PMID:33540466, PMC8333175
- Stokes J, et al. (2025). *ZIP is a cationic amphiphile that disrupts synaptic plasticity via macropinocytosis.* Nature. PMID:39814881, PMC12413077
- Hsieh C, et al. (2026). *KIBRA-PKMζ oligomers maintain long-term memory.* Mol Brain. PMID:41814337, PMC12997682
- Tsokas P, et al. (2026). *Double knockout of PKMζ and PKCι/λ eliminates late long-term potentiation.* bioRxiv. PMID:41889799, PMC13014159

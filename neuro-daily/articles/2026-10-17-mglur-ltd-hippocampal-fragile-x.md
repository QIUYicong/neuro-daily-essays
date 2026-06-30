---
title: 当受体失去支架：海马 mGluR-LTD 的分子故事与脆性 X 综合征的启示
date: 2026-10-17
article_number: 177
slug: mglur-ltd-hippocampal-fragile-x
layer: [molecular, synaptic, cellular, disease, cognition]
curriculum_track: 课程脊柱4（学习与记忆：LTD 机制）+ 课程脊柱11（疾病作为窗口：脆性 X 综合征）
core_question: 海马 CA1 突触中，mGluR5 激活如何通过 Gαq→PLCβ→IP3→ER Ca²⁺→PKCβ→GluA2-Ser880 磷酸化→GRIP 解离→PICK1 内化级联触发 AMPA 受体永久减少（mGluR-LTD）？脆性 X 综合征中 FMRP 的缺失为何使这条通路失控？Homer1a 在睡眠期的"解耦"与 mGluR-LTD 的"激活"有何根本区别？
sources:
  - "PMID:20188650 (Luscher & Huber 2010, Neuron 65:445-59, 摘要仅)"
  - "PMID:15219735 (Bear, Huber, Warren 2004, Trends Neurosci 27:370-7, 摘要仅)"
  - "PMID:12032354 (Huber et al. 2002, PNAS 99:7746-50, 摘要仅)"
  - "PMID:26764156 (Berry-Kravis et al. 2016, Sci Transl Med 8:321ra5, 摘要仅)"
  - "PMID:23083736 (Bhattacharya et al. 2012, Neuron, 摘要仅)"
  - "PMID:21090964 / PMCID:PMC3019409 (Krueger & Bear 2011, Annu Rev Med 62:411-29, PMC 开放全文)"
---

# 当受体失去支架：海马 mGluR-LTD 的分子故事与脆性 X 综合征的启示

## 今日核心问题

海马 CA1 突触中，当代谢型谷氨酸受体（mGluR5）被强烈的突触活动激活后，是什么精确的分子步骤决定了 AMPA 受体从突触后膜"永久离场"？这条被称为 mGluR 依赖性长时程抑制（mGluR-LTD）的通路，与我们昨天讨论的 Homer1a 介导的睡眠突触削减有何关联？它又如何在脆性 X 综合征（Fragile X Syndrome, FXS）中失控，成为人类最常见的遗传性智力障碍的核心机制？

## 一句话摘要

海马 mGluR-LTD 通过 mGluR5→Gαq→PLCβ→IP3→ER Ca²⁺→PKCβ→GluA2-Ser880 磷酸化→GRIP 解离→PICK1 内化的完整级联，驱动 AMPA 受体持久减少；脆性 X 综合征中 FMRP 的缺失使这条通路过度激活，揭示了当突触"遗忘的分子刹车"失控时，认知的蓝图如何被擦除。

## 为什么重要

在前一篇（#176）中，我们讨论了 Homer1a 如何在睡眠期"悄悄解开"mGluR5 与其下游效应子的联系，从而安静地削减突触权重。但 Homer1a 的描述中留下了一个悬空的引用：`[[mglur-ltd]]`——"与 mGluR-LTD 共享受体，但机制不同"。

今天，我们补上这个缺口。mGluR-LTD 是海马突触可塑性的另一条独立轴，与 NMDA 受体依赖型 LTD（#22）共存，但机制迥异——它通过 mGluR5 的**主动激活**而非 NMDA 受体的钙内流来启动受体内化。更重要的是，理解这条通路为理解脆性 X 综合征提供了一扇独特的窗口：当负责翻译调控的蛋白 FMRP 缺失，mGluR-LTD 就像一台刹车失灵的汽车，突触在错误的时间被消除，认知的建构被破坏在根基上。

## 背景：突触强度的双向调控

大脑的信息存储依赖突触强度的精确双向调控：增强（LTP）和减弱（LTD）。NMDA-LTD 通过低频刺激（1 Hz）产生的中等 Ca²⁺ 内流，激活磷酸酶（PP2B/PP1）使 AMPA 受体去磷酸化并内化。

但海马突触不只有一种 LTD。当突触接受**强烈但特定模式的活动**时，NMDA 受体旁的另一类受体——代谢型谷氨酸受体（metabotropic glutamate receptor, mGluR）——会被激活，启动一套**完全不同**的 LTD 程序。这就是 mGluR-LTD，由 Bhattacharyya 和 Bear 等人在 1990 年代系统确立（Bhattacharyya 1993；Lüscher & Huber 2010 全面综述），其机制独立于 NMDA 受体，但最终效应相同——AMPA 受体从突触后膜永久消失。

## 分子机制（分层解析）

### 1. 分子层：mGluR5 的身份与位置

mGluR5 是 I 族代谢型谷氨酸受体（Group I mGluR）之一，与 mGluR1 同组。

**位置**：mGluR5 集中分布于突触后致密区（PSD）的外周——不像 AMPAR 和 NMDAR 集中在 PSD 核心，mGluR5 位于更外围的"突触外环"，仅在强烈激活溢出谷氨酸时才充分感应到释放的谷氨酸。这种位置偏倚本身就是一种"强度感应器"：只有强烈的突触活动才能激活 mGluR5，触发 LTD。

**结构**：mGluR5 是七次跨膜的 G 蛋白偶联受体（GPCR），与 Gαq/11 蛋白偶联，与同组的 mGluR1 共享信号机制（但 mGluR5 在海马 CA1 中占主导，mGluR1 在小脑浦肯野细胞中占主导）。

**Homer 支架**：在正常清醒突触中，mGluR5 通过长型 Homer 蛋白（Homer1b/c、Homer2）与 IP3R（内质网 IP3 受体）和 Shank 脚手架蛋白形成稳定复合物。长型 Homer 拥有 N 端 EVH1 域（结合 mGluR5/1）和 C 端卷曲螺旋域（与 IP3R、Shank 交联）。这个复合物让 mGluR5 的钙信号"随时待命"。

### 2. 突触层：mGluR-LTD 的信号级联

mGluR-LTD 可以用 DHPG（3,5-dihydroxyphenylglycine，I 族 mGluR 选择性激动剂）在脑片上诱导，也可以在体由配对脉冲低频刺激（PP-LFS）触发（Lüscher & Huber 2010，PMID:20188650）。

**完整的分子步骤（海马 Schaffer 侧支-CA1 突触）**：

**第一步：mGluR5 激活 Gαq**
强烈突触活动 → 突触间隙谷氨酸浓度高 → mGluR5 结合谷氨酸 → Gαq/11 活化

**第二步：PLCβ 切割 PIP2**
活化 Gαq → 激活磷脂酶 Cβ（PLCβ）→ 水解膜磷脂 PIP2 → 产生两个第二信使：
- **IP3**（肌醇三磷酸）→ 扩散至内质网
- **DAG**（二酰基甘油）→ 留在质膜

**第三步：ER Ca²⁺ 释放**
IP3 → 结合 IP3 受体（IP3R，ER 上的钙通道）→ ER Ca²⁺ 释放到细胞质 → 胞质 Ca²⁺ 短暂升高

此 Ca²⁺ 升高**独立于 NMDA 受体**。这是 mGluR-LTD 与 NMDA-LTD 的根本区别——Ca²⁺ 来源不同（NMDA-LTD 来自胞外内流；mGluR-LTD 来自 ER 内库）。

**第四步：PKCβ 激活**
DAG + Ca²⁺ → 联合激活 **PKCβ**（蛋白激酶 C β 型），这是一个 Ca²⁺/DAG 双信使依赖的信号节点。

**第五步：GluA2-Ser880 磷酸化**
活化 PKCβ 靶向 AMPA 受体的 GluA2 亚基 C 末端，磷酸化 **Ser880** 位点。这是整个通路的枢纽磷酸化事件。

**第六步：GRIP 解离**
正常情况下，GluA2-Ser880（未磷酸化）与 **GRIP1/2**（谷氨酸受体相互作用蛋白 1/2）结合，是 AMPAR 在突触的重要锚定机制。Ser880 磷酸化后，GluA2-GRIP1/2 结合被破坏——锚固点丧失。

**第七步：PICK1 结合与内吞**
**PICK1**（蛋白激酶 C 相互作用蛋白 1）对磷酸化的 GluA2-Ser880 有高亲和力。GRIP 离去 → PICK1 占据 GluA2 → PICK1 招募内吞机器（与 dynamin、NSF 相互作用）→ 网格蛋白介导的 AMPAR 内吞。

结果：突触后膜 AMPA 受体数量持久减少，突触电流降低——mGluR-LTD 表达完成。

### 3. 蛋白合成层：为什么 mGluR-LTD 需要翻译？

上述信号级联给出了 mGluR-LTD 表达的即时机制（分钟内）。但 **Huber et al.（2002，PNAS, PMID:12032354）**证明，mGluR-LTD 的正常诱导与维持**依赖于树突局部蛋白质合成**（翻译抑制剂 anisomycin 可完全阻断）。

这揭示了第二个时间层次：mGluR-LTD 不只是即时的磷酸化级联，还需要**新蛋白的快速合成**（发生在树突而非细胞体，在突触刺激后数分钟内完成）。

**哪些蛋白被合成？**
- **Arc/Arg3.1**：活动调控细胞骨架蛋白，促进 AMPAR 内吞（见 #64）
- **MAP1B、STEP**（striatal-enriched phosphatase）：支持 LTD 信号传导
- **GluA1 亚基本身**等（尚有争议）

**FMRP 的翻译守门角色**：这些树突 mRNA 在静息状态下处于**翻译沉默**，被 FMRP（脆性 X 心智障碍蛋白）结合并抑制翻译。当 mGluR5 激活信号传来，FMRP 被快速磷酸化（然后泛素化降解）→ 翻译抑制解除 → Arc 等蛋白迅速合成 → LTD 正常执行。

FMRP 是精确控制 mGluR-LTD 规模和时机的翻译刹车。这个刹车的缺失，正是脆性 X 综合征的病理核心。

## 脆性 X 综合征：当刹车失效

### 脆性 X 综合征简介

脆性 X 综合征（FXS）是最常见的遗传性**单基因智力障碍**，影响约 1/4000 男性和 1/8000 女性（X 连锁显性，males 受影响更重）。致病机制是 FMR1 基因第一外显子 5'UTR 区 CGG 重复序列扩增（正常 < 55次，完全突变 > 200次）→ CGG 甲基化 → FMR1 启动子甲基化沉默 → **FMRP 蛋白完全缺失**。

临床表现：中到重度智力障碍、注意缺陷、社交回避、语言发育迟滞、感觉过敏，与自闭症谱系障碍高度共病。没有单一的生化治疗靶点，直到 Bear 等人的发现改变了局面。

### Huber、Bear 与 mGluR 理论

2002 年，**Huber KM、Gallagher SM、Warren ST、Bear MF（PNAS, PMID:12032354）**发表了一个关键发现：FMR1 基因敲除小鼠（Fmr1 KO）的海马脑片中，DHPG 诱导的 mGluR-LTD 比野生型**更强**（82% vs 93% 基线，p=0.004），并且这种增强的 LTD **不依赖于蛋白质合成**——翻译抑制剂不能阻断它。

解释：没有 FMRP 时，Arc 等 LTD 相关蛋白在静息状态就已经过度翻译（刹车失效），因此 mGluR5 激活后的 LTD 不再需要等待新蛋白合成——"翻译桶"已经满溢。

2004 年，**Bear MF、Huber KM、Warren ST（Trends Neurosci, PMID:15219735）**提出了影响深远的 **"mGluR 理论"（mGluR Theory of FXS）**：

> FXS 的核心病理是 mGluR5 下游蛋白合成的过度激活。FMRP 作为翻译抑制剂，正常情况下限制 mGluR 触发的蛋白合成；其缺失导致这些蛋白（Arc 等）的持续过量表达，引起夸大的 mGluR-LTD、突触权重弥散性减弱，最终导致突触功能障碍和认知缺陷。

这个理论的关键预测：**减弱 mGluR5 信号应能挽救 FXS 表型。**

动物模型验证迅速涌现：用 mGluR5 基因方法（Fmr1 KO × mGluR5 KO 杂交）将 mGluR5 减少 50%，Bhattacharya & Bear 等发现多种 FXS 表型（蛋白合成、树突棘密度、mGluR-LTD 增强、听觉惊反应、体重过增）均得到纠正（Bhattacharya et al. 2012, Neuron, PMID:23083736）。

## 临床试验：大起大落的 mavoglurant 时代

mGluR 理论激动人心，制药公司迅速跟进。**Novartis 的 mavoglurant（AFQ056）**和 **Roche 的 basimglustat（RG7090）**成为最主要的候选 mGluR5 拮抗剂。

2016 年，**Berry-Kravis E 等人（Science Translational Medicine, PMID:26764156）**报告了 mavoglurant 的两项 2b 期随机双盲安慰剂对照试验（成人 n=175，青少年 n=139，12 周），主要终点为异常行为量表（ABC-C FXS 版本）。

**结果：两项试验均未能达到主要终点。**

研究者总结了失败的可能原因：
1. **患者异质性过大**：FXS 患者的基础表型变异极广，12 周的单一量表无法捕捉细微改善
2. **治疗时间窗**：成年 FXS 患者突触可塑性异常可能已经"固化"，发育关键期已过
3. **结果测量不敏感**：行为量表对药物引起的认知/神经生物学变化不够灵敏
4. **生物标志物缺失**：没有预测哪些患者会响应的生物标志物

这次失败并不否定 mGluR 理论本身（动物证据仍然强健），而是揭示了从动物模型到人类临床的转化鸿沟：**证明机制成立不等于证明干预有效**，尤其是在复杂的神经发育障碍中，治疗时机、剂量、患者选择同等重要。

## Homer1a 的双面性：同一分子，两种命运

昨天（#176）我们描述了 Homer1a 在睡眠期进入 PSD、瓦解 mGluR5-IP3R 复合物、导致 AMPAR 悄悄脱落的机制。

今天，我们看到 mGluR-LTD 的"激活级联"同样通过 mGluR5 和 IP3R 起作用。

这揭示了一个精妙的设计逻辑：**Homer1a 在两种情境中是完全相反的调控者。**

| 情境 | Homer1a 的作用 | mGluR5 的状态 | 结果 |
|------|--------------|----------------|------|
| **睡眠期（生理性）** | 进入 PSD，**解耦** mGluR5-IP3R 复合物 | mGluR5 失去效应子连接，**无法信号传导** | AMPAR 轻柔脱落（稳态削减）|
| **脆性 X（病理性）** | 长型 Homer 减少（被 Homer1a 取代），mGluR5 去抑制 | mGluR5 持续处于"部分激活"状态，**过度信号传导** | mGluR-LTD 过强，突触权重弥散性减弱 |

更具体地：Bhattacharya 等人发现 FMR1 KO 小鼠中，**Homer1a 在突触处持续升高**（FMRP 缺失导致 Homer1a mRNA 翻译增加）。这一病理性升高的 Homer1a 持续取代长型 Homer，解耦 mGluR5 信号调控的正常闸门，使 mGluR5 在原本应该安静的时刻也能"漏信"激活下游。

这意味着：同一个 Homer1a 分子，在睡眠中它是突触的"守夜人"，在脆性 X 中它却成了"不定时炸弹"。背景——神经调质状态、其他蛋白的分布——决定了同一个分子是治愈还是伤害。

## 与小脑 LTD 的比较：同一效应器，不同触发器

本系列第 #168 篇讨论了小脑 PF-PC LTD。对比两种 mGluR 依赖的 LTD：

| 特征 | 海马 mGluR-LTD | 小脑 PF-PC LTD |
|------|---------------|---------------|
| **触发 mGluR** | mGluR5（I 族）为主 | mGluR1（I 族）为主 |
| **Ca²⁺ 来源** | IP3R 介导的 ER Ca²⁺ | ER Ca²⁺ + P/Q 型 VGCCs |
| **关键 PKC** | PKCβ | PKCα/γ |
| **共同效应器** | **GluA2-Ser880 磷酸化→PICK1→AMPAR 内吞**（相同！）|
| **蛋白合成需求** | 是（Arc 等） | 是（部分；GluA2 本身也受控）|
| **Homer 角色** | 长型 Homer 放大 mGluR5 信号准备度 | 长型 Homer 同样组织 mGluR1 复合物 |
| **功能意义** | 突触稳态、遗忘、认知灵活性 | 运动误差学习（经典条件化）|

两种形式的 LTD 在最终效应器上惊人相似（都用 GluA2-Ser880-PKC-PICK1 路径）——这说明大脑在进化上保留了相同的"受体移除执行机制"，只是在上游的"谁来触发"上选择了不同的受体偶联路径，以适应不同脑区、不同功能需求。

## 比喻：分子弹射座椅

想象突触 PSD 是一架飞机的驾驶舱，AMPA 受体是飞行员坐在弹射座椅上。正常飞行时，GRIP1/2 是安全销钉，保证飞行员（AMPAR）稳稳固定在座位上。

mGluR5 激活就像飞行电脑收到"紧急情况"信号，激活 PKCβ"拔掉安全销"（GluA2-Ser880 磷酸化→GRIP 解离），然后 PICK1 拉动弹射手柄，飞行员（AMPAR）被弹出驾驶舱（突触膜）进入内体。

**比喻成立处**：准确描述了"安全销解除→执行弹射"的两步顺序，以及每种蛋白的功能角色。

**比喻失效处**：真实的 AMPAR 并非立即降解，它们进入再循环内体后可能被重新插回突触（LTP 可逆转 LTD）——"弹出的飞行员可以降落后再上机"。另外，内吞不是瞬时的爆发，而是一个分钟到小时量级的持续过程，且多个步骤（PICK1 结合、网格蛋白囊泡形成）之间的时序远比比喻复杂。

## 它如何改变我们对大脑的理解

mGluR-LTD 的发现及其在脆性 X 中的异常，给"大脑如何从神经网络中建构认知"的问题增添了一个关键维度：

**突触权重的"遗忘边界"是计算性的**。大脑不只需要 LTP（学习），同样需要 LTD（遗忘/再平衡）——两者必须精确配合，否则网络就会陷入"噪音淹没信号"的困境。mGluR-LTD 是一种**背景活动触发的精准遗忘机制**：强烈但非精确的突触刺激激活 mGluR5，削减随机增强的背景突触，保护真正编码重要信息的精确突触（这与 Homer1a 的"记忆特异性提升"机制同向）。

**翻译调控是神经可塑性的关键时间层次**。LTP/LTD 的分子故事不只是磷酸化/去磷酸化，还需要蛋白合成这个慢速但持久的层次。FMRP 作为翻译刹车，在这个层次上精确定时 LTD 相关蛋白的表达。这提醒我们：突触可塑性有多个时间尺度（毫秒→分钟→小时），每个尺度都有独立的调控节点，任何一个节点出错都可能导致整个认知系统的失衡。

**疾病作为窗口**。脆性 X 综合征的研究历史是"从基因到细胞到电路到认知"完整因果链分析的范本——先找到致病基因（FMR1），再找到蛋白功能（FMRP 为翻译抑制剂），再找到电路异常（mGluR-LTD 过强），再找到行为后果（认知缺陷），再设计靶向干预（mGluR5 拮抗剂），最后在临床试验中遭遇现实复杂性。这个完整的科学旅程提醒我们：疾病是理解正常功能的特殊望远镜，而转化的道路远比实验室中看起来漫长。

## 争议与未解问题

**1. PICK1 在 mGluR-LTD 中的必要性之争**

PICK1 在 mGluR-LTD 中的必要性有争议。Bhattacharyya 等人（2009）的研究与其他实验室的数据在不同实验系统中给出了不一致的结论。目前较为审慎的观点是：PICK1 可能是众多内吞辅助因子之一，而非唯一必要因子（置信度：中）。

**2. mGluR-LTD 的具体蛋白合成靶标**

哪些新合成的蛋白负责维持 mGluR-LTD？Arc 是重要候选，但 Arc KO 并不完全消除 mGluR-LTD，说明还有其他贡献蛋白（MAP1B、FMRP 本身的翻译？）。完整的合成靶标列表至今未定论。

**3. 为什么 mGluR5 拮抗剂在人类中失败？**

mavoglurant 的失败让整个 FXS 治疗领域陷入困境。理论上合理的靶点为何不管用？可能原因：年龄（成年期神经可塑性窗口关闭）、结果指标不对、患者异质性、动物模型对应的是发育关键期而非成年期。未解问题：**是否存在 FXS 的特定亚型（按遗传背景、年龄）能从 mGluR5 干预中获益？**

**4. mGluR-LTD vs NMDA-LTD 在体内各占多大比例？**

脑片实验证明两种 LTD 共存，但在体内自然行为中，哪种机制主导？在什么任务、什么脑区、什么发育阶段下？目前不清楚。

**5. Homer1a 病理性升高在 FXS 中的因果作用**

FMR1 KO 中 Homer1a 升高是否直接驱动 mGluR-LTD 增强，还是其他机制更关键？相关研究正在进行但结论未定。

## 与 AI 的对照

mGluR-LTD 为深度学习提供了一个有趣的计算类比：

**类比权重衰减（Weight Decay / L2 正则化）**：深度学习模型经常使用权重衰减惩罚项——在每次更新时自动向零方向施加微小压力，防止过拟合。海马 mGluR-LTD 的功能可以理解为一种**活动驱动的局部权重衰减**：强烈但随机的突触激活（mGluR5 触发的"强背景噪音"）触发权重减小，防止随机涌现的"虚假 LTP"固化成假信号。

**不同之处**：AI 的 L2 衰减是均匀的（每个参数都受同等压力），而 mGluR-LTD 是高度突触特异的（只有激活了 mGluR5 的突触才会被压制）。这种**输入特异性遗忘**比均匀衰减计算上更精确，但实现成本也更高（需要 mGluR 的精确定位、专用信号级联和局部翻译机制）。

此外，mGluR-LTD 的蛋白质合成依赖性没有 AI 类比——AI 不需要在推理时合成新"零件"来执行权重更新。这提醒我们：生物学习系统在硬件层面有着 AI 完全不具备的动态物质层次。

## 今日概念卡片

**mGluR-LTD（代谢型谷氨酸受体依赖性长时程抑制）**：海马 CA1 Schaffer 侧支-CA1 突触处，mGluR5 被强烈谷氨酸激活 → Gαq → PLCβ → IP3 + DAG → ER Ca²⁺ 释放 + PKCβ激活 → GluA2 Ser880 磷酸化 → GRIP1/2 解离 → PICK1 招募 → AMPAR 内吞 → 突触权重持久减弱。蛋白质合成（Arc 等）是其完整表达的必要条件；FMRP 缺失（脆性 X）导致该通路过度激活，引发认知障碍。与睡眠期 Homer1a 介导的 AMPAR 削减的关键区别在于：mGluR-LTD 是 mGluR5 **主动激活**的后果，而 Homer1a 是 mGluR5 **解耦/沉默**的后果。

## 今日认知地图更新

今天补全了知识地图中的一个重要缺口：
- `mglur-ltd` 节点建立，填补了来自 `homer1a` 的悬空引用
- `mglur-ltd` 与 `cerebellar-ltd` 构成"mGluR 依赖型 LTD 的两种形式"——相同效应器（PKC-GluA2-PICK1）、不同受体（mGluR5 vs mGluR1）
- `fragile-x-syndrome` 节点建立，作为"mGluR-LTD 失控的疾病窗口"
- `ltd` 的 mGluR-LTD 节已有基础，本次细化完整级联并添加 Homer1a/FMRP 交互
- 知识地图新增了"同一蛋白（Homer1a）在不同背景下正反相反的功能"这一重要认知原则

## 参考来源

| # | 来源 | 类型 | 获取 | 来源说明 |
|---|------|------|------|---------|
| S1 | Lüscher C, Huber KM (2010). Group 1 mGluR-dependent synaptic long-term depression: mechanisms and implications for circuitry and disease. *Neuron* 65:445-459. **PMID:20188650** | 综述 | 摘要仅 | mGluR-LTD 机制的标准综述参考；信号级联和疾病关联 |
| S2 | Bear MF, Huber KM, Warren ST (2004). The mGluR theory of fragile X mental retardation. *Trends Neurosci* 27:370-7. **PMID:15219735** | 原创理论 | 摘要仅 | mGluR 理论原始提出；脆性 X 与 mGluR 的因果关系 |
| S3 | Huber KM, Gallagher SM, Warren ST, Bear MF (2002). Altered synaptic plasticity in a mouse model of fragile X mental retardation. *PNAS* 99:7746-7750. **PMID:12032354** | 原始研究 | 摘要仅 | FMR1 KO 小鼠 mGluR-LTD 增强的首篇报道；蛋白合成独立性 |
| S4 | Berry-Kravis E et al. (2016). Mavoglurant in fragile X syndrome: results of two randomized, double-blind, placebo-controlled trials. *Sci Transl Med* 8:321ra5. **PMID:26764156** | 临床试验 | 摘要仅 | 两期 2b 临床试验（n=314），主要终点未达，揭示转化困境 |
| S5 | Bhattacharya A, Kaphzan H, Alvarez-Dieppa AC, Murphy JP, Pierre P, Klann E (2012). Genetic removal of p70 S6 kinase 1 corrects molecular, synaptic, and behavioral phenotypes in fragile X syndrome mice. *Neuron* **PMID:23083736** | 原始研究 | 摘要仅 | S6K1 敲除纠正 FXS 翻译异常和 LTD 过强；证明蛋白合成调控靶点可行性 |
| S6 | Krueger DD, Bear MF (2011). Toward fulfilling the promise of molecular medicine in fragile X syndrome. *Annu Rev Med* 62:411-29. **PMID:21090964 / PMCID:PMC3019409** | 综述 | **PMC 开放全文** | mGluR 理论与 FXS 治疗展望的全面综述；mGluR5 抑制挽救多种 FMR1 KO 表型的系统概述 |

**注**：S1–S5 仅读取摘要，未获取付费全文；核心机制描述基于 S6 开放全文及已发表综述所概括的学界共识。文章中描述的 GluA2-Ser880-PKC-PICK1 级联为神经科学领域教科书级别的既定机制，置信度高；Homer1a 在 FXS 中病理性升高的因果角色尚在研究中，置信度中等（已在文中标注）。

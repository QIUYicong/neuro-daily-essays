# mGluR5 依赖的长时程抑制：突触削减的精密设计与脆性X综合征的分子悲剧

**文章编号**：#177  
**日期**：2026-10-17  
**字数**：约 5400 字  
**课程轨迹**：突触可塑性深度系列（接续#176 Homer1a/Arc 睡眠削减机制；填补 mglur-ltd 悬空引用）

---

## 今日核心问题

**代谢型谷氨酸受体5（mGluR5）激活后，突触是如何在不借助 NMDA 受体的情况下发生长时程抑制的？FMRP 蛋白在其中扮演了怎样的"制动器"角色——而当这个制动器因基因突变缺失时，为什么脆性X综合征的突触会走向失控的过度削减？**

---

## 一句话摘要

mGluR5 激活 Homer 长型支架 → 通过 PI3K-mTOR 与 ERK-MAPK 双通道启动局部蛋白翻译（弧形蛋白 Arc、MAP1b、STEP 等）→ 驱动 AMPA 受体内吞；FMRP 正常情况下作为翻译制动器压制这批蛋白的过度产生；当 FMR1 基因沉默（脆性X综合征）时，FMRP 消失、这批蛋白基底水平持续偏高、mGluR-LTD 失控增强、突触权重弥漫性下调——而 2019–2024 年临床试验显示，简单阻断 mGluR5 在人类中并不足以逆转这场复杂的发育失调。

---

## 为什么重要

上一篇（#176）我们追踪了 Homer1a 如何在睡眠期瓦解 mGluR5 的长型支架复合物，让 AMPA 受体悄悄从突触后膜脱落。那篇文章结尾留下了一个谜：Homer1a 的"攻击对象"——由长型 Homer（Homer1b/c）搭建、与 mGluR5 牢固锚定的信号平台——到底在正常清醒状态下负责什么样的功能？

答案是 mGluR-LTD（代谢型谷氨酸受体依赖的长时程突触抑制）。这是大脑在清醒学习时用来主动削减特定突触权重的机制之一。它的发现史，与人类遗传学中最令人心碎的疾病之一紧密交织——脆性X综合征（Fragile X Syndrome, FXS），迄今已知的最常见遗传性智力障碍。

理解 mGluR5-LTD 的意义不止在于一条信号通路：它揭示了大脑如何精确控制"哪些突触需要被削减"的分子逻辑；而脆性X综合征的案例，则告诉我们当这个逻辑的"限速阀"被拆除，后果有多严重——以及为什么以为只要堵住 mGluR5 就能救人的临床直觉，在真实的人类神经发育中遭遇了意想不到的挫败。

---

## 背景：两条 LTD，两套机器

我们在#96（LTD 文章）已经知道，长时程抑制（LTD）不是单一机制，而是一个结果（AMPA 受体从突触后膜上减少）可以由多条路径实现：

1. **NMDA 受体依赖的 LTD（NMDAR-LTD）**：低频刺激 → 中等 Ca²⁺ → 钙调磷酸酶（PP2B）→ PP1 → GluA1/GluA2 去磷酸化 → AMPAR 内吞  
2. **代谢型谷氨酸受体依赖的 LTD（mGluR-LTD）**：强突触活动或特定药物 → mGluR1/5 激活 → 局部蛋白翻译 → AMPAR 内吞  
3. **小脑 LTD**（详见#103）：mGluR1 + 攀爬纤维 Ca²⁺ → PKC → GluA2 Ser880 磷酸化 → AMPAR 内吞

三者最终效应相同，但触发器、信使和分子机器截然不同。mGluR-LTD 有两个最与众不同之处：

**第一：它不需要 NMDA 受体**。经典 NMDAR 是突触可塑性的"看门人"，因为它同时感受预突触谷氨酸和后突触去极化（"符合学习律"）。mGluR-LTD 绕开了这一逻辑。Lüscher & Huber 的综述（2010, Neuron, PMID:20188650）明确指出，在海马 CA1，mGluR-LTD 的发生"独立于后突触 Ca²⁺ 升高、IP3 敏感 Ca²⁺ 储库、PLC 或 PKC 活性"——这与 mGluR5 的教科书 Gq 耦联路径（→PLC→IP3→Ca²⁺ 释放）看似相悖，实际上揭示的是 mGluR5 在突触可塑性中激活的是不同的下游分支。

**第二：它依赖快速局部蛋白翻译**。NMDAR-LTD 主要靠磷酸酶的即时活化；mGluR-LTD 则需要在突触附近**即时合成**一批特定蛋白。翻译抑制剂（放线菌酮等）可以完全阻断 mGluR-LTD，但对 NMDAR-LTD 影响小得多。这个"蛋白合成依赖性"是 mGluR-LTD 最独特的标志，也是理解脆性X综合征的核心线索。

---

## 机制：mGluR5 如何指挥突触附近的蛋白合成流水线

### 1. 触发器：强突触活动或 DHPG

mGluR-LTD 在体内的自然触发条件是**强突触活动**（高频、持续的谷氨酸释放），使突触间隙谷氨酸浓度足以充分激活位于突触外围的 mGluR5（和 mGluR1）。

在实验室，研究者常用药物 **DHPG**（(RS)-3,5-dihydroxyphenylglycine，一种 I 组 mGluR 激动剂）短暂（5–15 分钟）灌流脑切片，即可可靠诱导 CA1 的 mGluR-LTD（Huber et al. 2001, J Neurophysiol, PMID:11431513）。这使 mGluR-LTD 成为一个可在体外定量研究的模型系统。

### 2. Homer 长型蛋白：平台搭建者

mGluR5 单独存在时，其胞内 C 端尾部连接着 **Homer 长型蛋白**（Homer1b/c、Homer2、Homer3）的 EVH1 结构域。Homer 的关键在于另一端：C 端卷曲螺旋结构域可与 IP3 受体、PIKE（PI3K 增强子）、Shank 以及 PSD-95 等多种支架蛋白交联。

**这个平台的功能不是传递钙信号，而是将 mGluR5 的激活与 PI3K-mTOR 通路相连**（Ronesi & Huber 2008, J Neurosci, PMID:18184796）。Homer 将 mGluR5 锚定于 PIKE，PIKE 激活 PI3K，PI3K 进而活化 mTOR——这是蛋白翻译最核心的调控枢纽。

这个细节将昨天（#176）的 Homer1a 故事与今天连接起来：  
- **Homer1a（短型，睡眠期）**：缺乏 C 端卷曲螺旋 → 进入 PSD 后取代长型 Homer → **瓦解** mGluR5-PIKE-PI3K 平台 → 信号解耦 → AMPAR 被动脱落（不经典 LTD 途径）  
- **Homer1b/c（长型，清醒期）**：完整平台 → mGluR5 激活 → 经典 mGluR-LTD 启动

两者共享 mGluR5 受体，但利用相反的支架状态，产生**完全不同的信号结果**。睡眠中的 Homer1a 机制不是"mGluR-LTD 在睡眠中发生"，而是 Homer1a 主动断路，绕过 mGluR-LTD 的蛋白合成需求，直接触发 AMPAR 脱落。

### 3. 双通道翻译激活：mTOR 与 ERK-MAPK

mGluR5 激活后，通过 Homer-PIKE 激活 **PI3K-mTOR** 通路，并同时通过 Gq 偶联激活 **ERK/MAPK** 通路。两条通路殊途同归，共同调控翻译机器：

- **mTOR** 磷酸化 4EBP1 → 释放 eIF4E → 翻译启动因子可用性增加
- **ERK/MAPK** 激活 MNK1/2 → 磷酸化 eIF4E → 进一步促进翻译启动
- **EF2K（延伸因子激酶）** 轻度抑制翻译延伸 → 使翻译资源集中于"5'端结构复杂、需要高启动因子水平"的难翻译 mRNA（如 Arc、MAP1b）

结果：Arc 蛋白在 mGluR5 激活后 **约 5 分钟内**即在树突局部被翻译（Lüscher & Huber 2010）。

### 4. 执行 AMPAR 内吞的三位演员

三种蛋白协作完成 AMPAR 的移除：

**Arc（Activity-Regulated Cytoskeleton-associated protein）**  
Arc 与 dynamin 和 endophilin 结合，促进网格蛋白介导的内吞，将 AMPA 受体从突触膜拉入胞内。（我们在#176 详细讨论了 Arc 如何在睡眠期靶向静默突触并执行内吞。）

**MAP1b（Microtubule-Associated Protein 1b）**  
MAP1b 通过与 GluA2 亚基结合，负调控 AMPAR 的表面表达，是 mGluR5 触发 AMPAR 数量减少所必需的（Lüscher & Huber 2010）。

**STEP（Striatal-Enriched Tyrosine Phosphatase）**  
STEP 通过酪氨酸去磷酸化使 GluA2 亚基从 PSD 锚点脱离，创造 AMPAR 向突触外侧向扩散的条件——这是内吞的前提。

三者相互配合：MAP1b 降低 AMPAR 表面数量，STEP 为 GluA2 脱锚，Arc 召唤内吞机器。抑制任意一个均损害 mGluR-LTD 的表达。

### 5. mGluR-LTD 的靶点偏好：大突触，有内质网的脊

Thomazeau et al. 2021（Mol Psychiatry, PMID:32606374）用双光子显微镜同时记录电生理和树突棘形态，发现了一个引人深思的事实：**mGluR 激活引起 AMPAR 内吞和 LTD，但不引起树突棘收缩**（spine shrinkage）。这与 NMDAR-LTD 截然不同——NMDAR-LTD 同时造成 AMPAR 内吞和棘的物理缩小。

Lüscher & Huber 的综述进一步指出，mGluR-LTD 优先发生在"含有内质网（ER）的棘"上——即那些较大、较成熟的突触（ER 是内质网 Ca²⁺ 储库，也是局部蛋白合成的物质基础）。这意味着 mGluR-LTD 并非无差别的削减，而是偏好削减已经建立起翻译平台的、成熟度较高的突触。

---

## FMRP：翻译制动器与 mGluR-LTD 的速率限制

理解 mGluR-LTD 的蛋白合成依赖性，就是为理解 FMRP（脆性X智力低下蛋白，Fragile X Mental Retardation Protein）在其中的关键作用做铺垫。

### FMRP 的分子身份

FMRP 由 FMR1 基因编码，含 632 个氨基酸，具有两个 KH（hnRNP K 同源）结构域和一个 RGG 盒，赋予它识别并结合特定 mRNA 编码区的能力（Richter 2021, Nat Rev Neurosci, PMID:33608673/PMC8094212）。HITS-CLIP 实验在幼鼠前脑中鉴定了 **842 个高置信度 FMRP 靶 mRNA**，其中约三分之一编码突触后蛋白——包括 mGluR 和 NMDA 受体亚基本身。

FMRP 主要通过**停滞核糖体**（stalling ribosomes on polysomes）来抑制翻译延伸——不是阻止翻译启动，而是让核糖体走走停停、降低合成速率。

### FMRP 如何压制 mGluR-LTD

在正常突触中，Arc、MAP1b、STEP 这些 mGluR-LTD 执行者的 mRNA **恰好都在 FMRP 的靶标列表上**。平静状态下，FMRP 将这些 mRNA 的翻译维持在低速；当 mGluR5 被激活，信号级联触发 FMRP **去磷酸化和/或泛素化降解**，释放对这批 mRNA 的翻译抑制 → 翻译加速 → LTD 执行蛋白快速积累 → AMPAR 内吞。

因此，FMRP 是 mGluR-LTD 的**速率限制器（rate-limiting brake）**：它确保 mGluR-LTD 只在真正被充分激活时发生，而不是持续低水平地侵蚀突触权重。

---

## 脆性X综合征：当制动器消失

### FMR1 沉默机制

脆性X综合征（FXS）是迄今已知最常见的遗传性智力障碍（大约 1/4000 男性），由 X 染色体上 FMR1 基因 5' 非翻译区的 CGG 重复扩增（超过 200 次）导致。扩增使该区域发生 **DNA 甲基化**，基因启动子被沉默，FMRP 几乎完全缺失。

结果是翻译制动器消失。那批 mGluR-LTD 执行蛋白（Arc、MAP1b、STEP 等）的 mRNA 持续以较高速率翻译，在树突中保持异常高的基底水平。

### 过度 mGluR-LTD：不需要强激活

Lüscher & Huber 的综述（2010）描述了关键的实验观察：**在 Fmr1 敲除小鼠（FX 模型），DHPG 诱导的 mGluR-LTD 在海马 CA1 和小脑均显著增强**，且这种增强的 LTD 不再依赖急性蛋白合成（翻译抑制剂不再能阻断 LTD，因为蛋白已经预先充足）。

这是一个精妙的悖论：正常情况下，mGluR-LTD 需要"先激活 mGluR5 → 才能解除 FMRP 抑制 → 才能翻译蛋白 → 才能 LTD"；但在 FMRP 缺失的 FX 小鼠中，蛋白合成不再需要 mGluR 激活来启动，LTD 的启动门槛大大降低。

### Bear 的 mGluR 理论（2004）

这一系列发现促使 Mark Bear 与同事 Kimberly Huber 和 Stephen Warren 在 2004 年提出"**mGluR 理论的脆性X综合征**"（Bear, Huber & Warren, 2004, Trends in Neurosciences, PMID:15219735）：

> FXS 的众多神经和精神症状，均可能源自 mGluR5 依赖的、蛋白合成相关功能的**整体过度激活**——不只是 mGluR-LTD，还包括 mGluR5 在突触发育、突触形态、兴奋性调节中所有需要局部翻译的功能。

这是一个大胆而统一的假说：FXS 不是某单一突触或脑区的局部缺陷，而是对**所有 mGluR5→蛋白合成依赖性可塑性**的系统性过激。

Bear 理论的实验支撑在 2007 年由 Dölen 等人（PMID:18093519）提供：在 Fmr1 KO 小鼠中**将 mGluR5 表达量遗传性地减少 50%**，多项 FXS 表型（包括听源性发作、AMPAR 表达异常、视皮层可塑性缺陷等）得到显著纠正，证明 mGluR5 的过度激活确实是 FXS 病理的重要驱动因素。

---

## 临床悲剧：从小鼠到人类的跌落

Bear 理论发表后，制药公司迅速行动，开发 mGluR5 拮抗剂作为 FXS 的治疗药物。两个主要候选药物是：
- **Mavoglurant**（AFQ056，罗氏）
- **Basimglurant**（RG7090，罗氏）

在啮齿类和斑马鱼模型中，这些药物展示了令人鼓舞的结果（Zerbi et al. 2019, NeuroImage, PMID:30807820）。但在人类临床试验中，结果令人沮丧：

Protic 等人 2024 年报告（PMID:39483619）描述了 FXLEARN 试验——在 3–6 岁 FXS 儿童中使用 AFQ056。**主要终点（语言发育改善）未达到统计显著性**，血液生物标志物亦未见显著变化。Witkin 等人（2022, Pharmacology Biochemistry and Behavior, PMID:35987339）的综述也指出，这些 mGluR5 靶向药物"在帕金森和脆性X综合征患者中的表现远不如预期"。

这次临床失败提出了若干深刻的问题：

1. **动物模型的局限**：Fmr1 KO 小鼠的全身性 FMRP 缺失，与人类 FXS 在发育时机、回路复杂性上有根本差异。
2. **治疗窗口问题**：FMRP 在胎儿和婴儿期神经回路发育中发挥重要作用；出生后才开始药物干预，可能已错过关键期（斑马鱼研究暗示 0–3 天的发育窗口最关键，Medishetti 2019）。
3. **测量方式问题**：临床试验中用于评估认知和行为改善的量表，可能对 mGluR5 拮抗剂产生的微小突触变化不够灵敏。
4. **补偿机制问题**：数年的 FXS 发育异常已经在多个层面建立了补偿性适应，单一靶点的急性阻断可能不足以逆转整个回路的重组。

临床失败并不意味着 mGluR 理论是错的——它更可能意味着 FXS 是一种需要**多靶点、发育早期、个性化**干预策略的复杂神经发育疾病。

---

## 比喻：一个工厂的生产限速与失控

mGluR5-LTD 可以理解为一个**按需生产系统**：正常情况下，工厂里有批量的原材料（mRNA），但生产线（核糖体）被一个品质控制员（FMRP）限速，使生产不过度。接到强订单（mGluR5 激活）时，品控员暂时离岗，生产线全速运转，产品（Arc、MAP1b、STEP）快速堆积，执行突触削减任务，然后恢复平衡。

脆性X综合征相当于品控员（FMRP）永久缺席：工厂始终在全速运转，产品永久过剩，突触削减的门槛消失，大量不该被削减的突触也被波及。这解释了为什么 FXS 患者的树突棘数量增多但形态细长不成熟（过度突触形成 + 过度削减 + 成熟不足的三角矛盾），以及智力障碍、自闭症样社交障碍、癫痫敏感性增高等多样化临床表现。

比喻的局限：工厂隐喻把 FMRP 的作用过度简单化为"开关"。实际上，FMRP 的去磷酸化/降解本身就受精细调控（包括 PP2A、泛素-蛋白酶体系统），而它调控的不只是翻译延伸速率，还涉及 mRNA 定位、核糖体进入位点选择等多个层面。此外，工厂比喻忽略了脑区特异性——海马 CA1 的 mGluR-LTD 与小脑 mGluR-LTD 使用同一终端执行者但来自不同回路需求。

---

## 它如何改变我们对大脑的理解

mGluR5-LTD 的发现和脆性X综合征的教训，在几个层面深化了我们对大脑的理解：

### 突触可塑性的多样性

同一结果（突触权重下降）可以由多条机制实现，每条机制有其特定的触发条件、时间尺度和功能语境：NMDAR-LTD 对弱、低频输入敏感；mGluR-LTD 对强活动后的"回归稳态"敏感；小脑 LTD 专门响应运动误差信号。大脑不是用单一机制解决所有问题，而是配备了多套工具，各司其职。

### 翻译控制是突触可塑性的核心调控层

经典的突触可塑性框架强调磷酸化/去磷酸化（激酶与磷酸酶的对抗）。mGluR-LTD 告诉我们，**局部蛋白合成是一个独立且不可缺少的调控层**。突触不只是信号转导的场所，还是一个微型的翻译工厂，可以在数分钟内"按需生产"特定蛋白来改变自己的权重。

### 支架蛋白决定信号方向

Homer 长型/短型的差异，改变的不是受体本身，而是受体下游信号的路由——同一个 mGluR5，连接到长型 Homer 时产生 mGluR-LTD，被短型 Homer1a 替代后产生睡眠期 AMPAR 脱落（但机制不同）。支架蛋白是大脑使用"信号路由器"而非"信号开关"来精调可塑性的典型体现。

### 疾病作为揭示机制的自然实验

FXS 是一个惨痛的自然实验：它让我们看到了当 FMRP 这个翻译制动器消失后，mGluR5 蛋白合成依赖性功能全面失控的后果。临床试验的失败则反过来提醒：即使理解了分子机制，治疗神经发育疾病需要的不只是靶点拮抗，还需要对发育时间窗口、代偿机制和系统复杂性的深刻理解。

---

## 争议与未解问题

### mGluR-LTD 在海马 CA1 的触发机制争议

Lüscher & Huber（2010）指出 CA1 的 mGluR-LTD 独立于 IP3 和 PLC——但这与 mGluR5 作为 Gq 耦联受体（理论上应激活 PLC）的教科书描述相悖。一个可能的解释：mGluR5 在不同情境下可以偶联不同 G 蛋白（Gq vs Gi/o）或激活非 G 蛋白依赖的 β-arrestin 通路；另一个解释是 CA1 mGluR-LTD 的蛋白合成主要依赖 PI3K/mTOR（通过 Homer-PIKE），不需要经典 PLC 路径。这一争议至今未完全厘清。

### 脊形态与 LTD 的分离

Thomazeau 等人（2021）发现 mGluR-LTD 不引起树突棘收缩，而 NMDAR-LTD 会。这说明功能性（AMPAR 数量减少）和结构性（棘体积改变）可塑性可以分离。这引发了一个重要问题：没有结构变化的 mGluR-LTD，持久性如何保证？AMPAR 内吞后进入内体，是被降解还是再循环？

### FXS 治疗失败后的新方向

mGluR5 拮抗剂临床失败后，研究者转向：
- **GABA_B 受体激动剂**（提高抑制性张力）
- **mTORC1 通路抑制剂**（rapamycin 类化合物，直接作用于翻译启动）
- **ISRIB（整合应激反应抑制剂）**：2024 年 Barnes 等人（PMID:39983718）报告 NMDAR 的非离子型信号通路（GluN2B 胞内尾端介导的构象信号）可以逆转 FXS 树突棘缺陷，为非 mGluR5 靶向策略提供了新方向
- **基因治疗**：直接恢复 FMRP 表达（AAV 载体）
- **表观遗传去甲基化**：逆转 FMR1 基因的甲基化沉默

---

## 与 AI 的对照

mGluR-LTD 与 FMRP 的故事，在 AI 的权重学习框架中有一个有意思的类比：

**mGluR-LTD = 局部规则驱动的权重下调**，不需要全局误差信号（对比 NMDAR-LTD 更接近"赫布反规则"），而是由局部活动水平超阈值后的翻译过程决定要削减哪个突触。

**FMRP = L1/L2 正则化中的权重惩罚系数**：它限制权重（翻译速率）的增长，防止过拟合（突触过削减）。在 FXS 中，缺乏正则化的网络趋向于过度削减，泛化能力受损（FXS 患者常表现出对新刺激过度泛化的恐惧和感觉超敏）。

但类比在这里遇到边界：神经网络的正则化是全局的（对所有权重施以相同惩罚），而 FMRP 的调控是**高度特异的**（842 个靶标，各有不同的结合亲和力和调控强度）。生物系统的"正则化"更像是一张细粒度的个性化规则表，而不是一个全局超参数。

---

## 今日概念卡片

**mGluR-LTD**  
由 I 组 mGluR（主要为 mGluR5，海马；mGluR1，小脑）激活驱动、需要局部蛋白快速翻译（Arc、MAP1b、STEP 等）的突触长时程抑制。独立于 NMDA 受体；通过 Homer-PI3K-mTOR 和 ERK-MAPK 双通道启动翻译；最终效果为 AMPA 受体内吞、突触权重降低。FMRP 是其翻译速率的关键制动器；FMRP 缺失（脆性X综合征）导致 mGluR-LTD 过度增强。

**FMRP（FMR1 蛋白）**  
含 KH 结构域和 RGG 盒的 RNA 结合蛋白，通过停滞核糖体抑制 842 个靶标 mRNA 的翻译延伸。mGluR5 激活后经去磷酸化/降解释放抑制，允许 Arc、MAP1b 等快速合成，执行 mGluR-LTD。FMR1 CGG 扩增 → 甲基化沉默 → FMRP 消失 → 脆性X综合征。

---

## 今日认知地图更新

本文在知识库中新建了 **mGluR-LTD** 的独立概念页，填补了 homer1a.md（#176）、ltd.md 和 cerebellar-ltd.md 中已引用但缺少节点的悬空引用。

新建或重要修订的连接：
- homer1a ↔ mglur-ltd（机制对比：Homer1a 解耦 vs 长型 Homer 激活 mGluR-LTD）
- fmrp ↔ mglur-ltd（翻译制动器关系）
- mglur-ltd ↔ arc-arg31（蛋白合成执行者）
- mglur-ltd ↔ fragile-x-syndrome（核心分子机制）
- mglur-ltd ↔ ltd（is-a 关系，同时区别 NMDAR-LTD）

---

## 参考来源

| # | PMID / PMC | 标题（缩略） | 来源类型 | 全文 |
|---|-----------|-------------|---------|------|
| S1 | PMID:20188650 / PMC:2841961 | Lüscher & Huber 2010, Neuron · Group 1 mGluR-LTD 综述 | PMC 开放全文 | ✓ |
| S2 | PMID:15219735 | Bear, Huber & Warren 2004, Trends Neurosci · mGluR 脆性X理论 | 摘要仅 | ✗ |
| S3 | PMID:18093519 / PMC:2199268 | Dölen et al. 2007, Neuron · mGluR5 减少 50% 纠正 FXS 表型 | PMC 开放全文 | ✓ |
| S4 | PMID:32606374 | Thomazeau et al. 2021, Mol Psychiatry · mGluR-LTD vs NMDAR-LTD 结构/功能分离 | 已验证 PMID | △（摘要+部分） |
| S5 | PMID:33608673 / PMC:8094212 | Richter 2021, Nat Rev Neurosci · FMRP 分子生物学综述 | PMC 开放全文 | ✓ |
| S6 | PMID:18184796 | Ronesi & Huber 2008, J Neurosci · Homer 互作对 mGluR-LTD 必要性 | 摘要仅（未读全文） | ✗ |
| S7 | PMID:11431513 | Huber et al. 2001, J Neurophysiol · DHPG 化学诱导 mGluR5-LTD | 摘要仅（未读全文） | ✗ |
| S8 | PMID:39483619 | Protic et al. 2024, SAGE Open Med · FXLEARN 试验 mavoglurant 儿童 FXS | 摘要已验证 | △ |
| S9 | PMID:35987339 | Witkin 2022, Pharmacol Biochem Behav · mGluR 靶向药物临床综述 | 摘要已验证 | △ |
| S10 | PMID:39983718 | Barnes et al. 2025, Cell Reports · GluN2B 非离子型信号逆转 FXS 树突棘 | 摘要已验证 | △ |

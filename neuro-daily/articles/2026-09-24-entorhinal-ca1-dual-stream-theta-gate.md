# 时序之门：内嗅皮层的两条输入流如何在 theta 节律中锻造 CA1 的精准空间地图

**知识库连续日期**：2026-09-24 | **文章编号**：#154  
**系统时钟日期**：2026-06-25 UTC+8  
**课程轨道**：课程脊柱 3（大脑如何编码世界：空间表征）+ 课程脊柱 4（学习和记忆：位置细胞、BTSP）  
**层级**：microcircuit / brain-region / synaptic / cognition

---

## 今日核心问题

CA1 锥体细胞如何在 theta 振荡的时序框架内，将来自内嗅皮层第三层（EC-III）的直接穿通径路（temporoammonic path，TA path）与来自 CA3 的 Schaffer 侧支输入整合成精准的位置细胞活动——同时，内侧内嗅皮层（MEC）与外侧内嗅皮层（LEC）这两个平行亚区在这一过程中各自传递什么样的信息？

---

## 一句话摘要

内嗅皮层通过两条解剖上分离的输入流——EC-III 的直接穿通径路（终止于 CA1 远端树突）和 EC-II 经齿状回、CA3 中继的三突触通路（终止于 CA1 近端树突）——在 theta 振荡的时序门控下向 CA1 输送互补信息；CA1 锥体神经元充当"时序 AND 门"，仅当 Schaffer 侧支先于直接皮层输入约半个 theta 周期到达时才允许后者穿透至胞体，而 MEC 与 LEC 在这两条通路的上游分别传递环境语境地图与目标奖励地图。

---

## 为什么重要

如果你已经读过这个系列中关于 BTSP 的文章（#150）以及树突棘结构可塑性（#153），你可能会有一个悬而未决的问题：**那个触发 BTSP 的高钙平台电位究竟从哪里来？是谁告诉 CA1 神经元"现在，把这里写入地图"？**

这正是今天要回答的问题的核心。CA1 是海马回路中最终生成空间表征的地方，但它本身并不独立工作——它站在两条皮层输入流的交汇处，同时还要处理来自 CA3 的联想信号。这三路输入在解剖上、在时间上、在功能上都有精妙的分工，而 theta 振荡正是协调这一切的时钟。

理解这个回路的重要性还在于它挑战了一个流行了将近 20 年的简单二分法：**"MEC 负责空间，LEC 负责非空间内容。"** 2023 年的直接体内成像数据告诉我们，这个图景太过简化了——真实情况更微妙，也更令人着迷。

---

## 背景：两条通路的解剖分工

### 内嗅皮层：大脑皮层进入海马的主要门户

在颞叶内侧，有一块不显眼却至关重要的皮层区域——内嗅皮层（entorhinal cortex，EC）。它是感觉联合皮层与海马之间的主要接口，整合来自视觉、听觉、嗅觉、躯体感觉和前额叶的信息，再经过预处理后传递给海马。

EC 在功能和解剖上分为两个亚区：
- **内侧内嗅皮层（MEC）**：富含网格细胞（grid cells）、头朝向细胞、速度细胞、边界细胞，提供环境的度量式空间坐标
- **外侧内嗅皮层（LEC）**：整合物体、气味、社会情境等非空间内容，编码"这里有什么"

Hafting 等人 2005 年在《自然》杂志上发表的里程碑论文（PMID:15965463，未读取全文）揭示了 MEC 第二层星状细胞中的网格细胞以三角形晶格的节点周期性放电，为海马提供路径积分的度量基础。这是地球上迄今发现的最规整的神经编码结构之一——Edvard Moser 和 May-Britt Moser 也因此获得了 2014 年诺贝尔生理学或医学奖。

### 从 EC 到 CA1：两条平行的高速公路

EC 通过两条解剖路径将信息传递给海马 CA1（图 1）：

**通路一：三突触通路（Trisynaptic Pathway）**
EC 第二层（主要是 MEC-II 和 LEC-II）→ 穿通纤维（perforant path）→ 齿状回（DG）→ 苔状纤维（mossy fiber）→ CA3 → Schaffer 侧支 → CA1

这条通路经过三次中间突触，信息被逐步加工：DG 完成模式分离，CA3 通过循环连接完成模式补全，最终 CA3 的 Schaffer 侧支终止于 CA1 的**近端顶端树突（stratum radiatum，SR）**——距胞体约 100–200 μm。

**通路二：直接穿通径路（Temporoammonic Pathway，TA path）**
EC 第三层（主要是 MEC-III 和 LEC-III）→ 颞氨通路（temporoammonic path）→ 直接投射到 CA1

这条通路跳过了齿状回和 CA3，直接终止于 CA1 的**远端顶端树突（stratum lacunosum-moleculare，SLM）**——距胞体约 300–400 μm。

**这一解剖差异的意义极其深刻。**

SLM 在电气上极远离胞体，一个单独的 TA path 突触电位在到达胞体时已经被大幅衰减——远端树突的电阻和电容滤波效应使高频信号几乎无法到达。这意味着 TA path 在大多数情况下是"沉默"的——它的信号被困锁在树突末梢，无法独立驱动 CA1 神经元放电。

那么，TA path 有什么用？这正是这个回路最精妙的地方。

---

## 机制一：位置细胞究竟依赖哪条通路？

在回答"时序 AND 门"之前，我们需要先确立两条通路对位置细胞各自的贡献。两组里程碑性实验给出了清晰的回答。

### 实验 1：切除 CA3 后，CA1 依然能形成场所场

Brun 等人 2002 年在《科学》杂志上报告了一个令人惊讶的结果（PMID:12077421，未读取全文）：他们通过手术选择性切断 CA3 到 CA1 的 Schaffer 侧支（同时保留直接穿通径路完整），发现 CA1 锥体细胞**仍然能够形成清晰稳定的场所场**。

这意味着：**直接来自 EC 的穿通径路本身就足以在 CA1 中建立基本的空间表征。**

但是，当这些被切断 CA3 输入的大鼠被放入水迷宫测试记忆回忆能力时，它们出现了明显的**回忆障碍**——虽然能认出熟悉的地点（识别记忆完好），却无法主动利用空间记忆找到目标（回忆记忆受损）。

这个实验揭示了一个精妙的双回路分工：
- **直接 EC→CA1 通路**：支持基本的空间编码和识别
- **CA3 Schaffer 侧支通路**：支持联想回忆（associative retrieval）——从部分线索重建完整记忆

### 实验 2：选择性破坏直接 EC-III 输入，CA1 场所场变大变散

Brun 等人 2008 年在《神经元》杂志上报告了另一个实验（PMID:18215625，未读取全文）：他们选择性破坏了内侧 EC 第三层（MEC-III）神经元（使用 γ-乙炔基 GABA，一种 GABA 转氨酶抑制剂，在 MEC-III 选择性积累），从而特异性切断 TA path，同时保留 CA3 输入完整。

结果是：CA1 的**场所场变大了，变得更分散**——细胞仍然有位置偏好，但不够精准，像是被模糊了一层。相比之下，CA3 的场所场（接收的是来自 EC-II 的间接输入，未受损）仍然清晰锐利。

**结论：EC-III 直接输入是维持 CA1 场所场空间精准度的关键。**

两个实验合起来揭示的图景是：
- 来自 MEC-II/LEC-II 通过 CA3 的间接通路 → 提供联想回忆能力（内容重建）
- 来自 MEC-III/LEC-III 的直接穿通径路 → 提供当前感觉情境的精准空间锚定（精准度）

---

## 机制二：时序 AND 门——theta 节律如何协调两路输入

CA1 锥体神经元面临一个工程挑战：它需要整合来自两个时间上不同步、空间上解剖分离的输入，但又不能让两者相互干扰。theta 振荡（约 8 Hz）提供了解决方案。

### Ang 等人 2005 年的发现：CA1 是"时序特异性 AND 门"

Ang、Carlson 和 Coulter 在 2005 年发表于《神经科学杂志》的工作（PMID:16237162，PMC:2048747，开放全文）揭示了 CA1 锥体神经元是如何通过一种精妙的门控机制整合两路输入的。

**关键发现：TA path 的信号只有在 Schaffer 侧支先于其约半个 theta 周期（~40–60 ms）激活之后，才能穿透到 CA1 的胞体。**

这是如何实现的？机制有两个关键步骤：

**步骤 1：Schaffer 侧支预激活**
Schaffer 侧支终止于 stratum radiatum（SR），在这里激活 NMDA 受体。NMDA 受体的激活导致 Ca²⁺ 内流，使 SR 内的树突局部去极化。这个局部去极化扩散到更远端的树突，包括 SLM 区域。

**步骤 2：GABA_B 介导的预突触去抑制**
在正常情况下，SLM 区域的 OA 型（oriens/alveus）抑制性中间神经元持续向 TA path 的突触前末梢释放 GABA_B 信号，抑制 TA path 的谷氨酸释放——这是一种预突触抑制，将 TA path 的信号锁死在远端树突。

然而，当 Schaffer 侧支先期激活之后，回路中产生的 NMDA 受体激活触发了对 OA 中间神经元的**GABA_B 介导的去抑制**（disinhibition）——简单说，先期的 Schaffer 激活"关掉了"那个抑制 TA path 的闸门。

于是，在这个短暂的去抑制窗口内（约 40–60 ms 后），到达的 TA path 信号不再被预突触抑制，能够在已经部分去极化的树突上产生更强的局部 EPSP，从而穿透到胞体，使 CA1 神经元放电。

这就是"**时序 AND 门**"的本质：
- 仅 Schaffer 激活（无 TA path）→ CA1 可以放电，但缺少当前感觉情境的精准空间锚定
- 仅 TA path 激活（无 Schaffer 激活）→ TA 信号被 GABA_B 预突触抑制，无法到达胞体，CA1 不响应
- Schaffer 先于 TA path 约半 theta 周期 → AND 门开启，CA1 以整合两路信息的方式精准放电

### theta 振荡如何组织这一时序？

在大鼠自由探索时，theta 振荡（~8 Hz，周期约 125 ms）在全海马中精确地组织了不同输入的激活顺序：

- **theta 波谷**（~10–60 Hz gamma 主导，Schaffer 侧支输入期）：CA3 放电主要集中在这个相位，驱动 Schaffer 侧支输入 CA1 的 SR
- **theta 波峰**（~60–120 Hz gamma 主导，EC 直接输入期）：EC 第三层主要在这个相位向 CA1 的 SLM 输入

两个输入刚好相差约半个 theta 周期，完美匹配"时序 AND 门"的时序要求。López-Madrona 和 Canals 2021 年的工作（PMID:34439925，PMC:8389192，开放全文）进一步揭示，在新颖环境探索时，EC-II 对 EC-III 的方向性影响增强，同时 Schaffer 侧支的影响减弱——theta 振荡本身携带着"学习模式还是回忆模式"的动态切换信息。

---

## 机制三：MEC vs LEC——空间之外还有奖励

传统神经科学教科书告诉我们一个清晰的二分法：**MEC 编码空间，LEC 编码非空间内容**（物体、气味、颜色）。

这个框架来自对两个亚区选择性损伤实验的经典解读：MEC 损伤损害空间导航，LEC 损伤损害物体识别。但 Hales 等人 2014 年（PMID:25437546，PMC:4294707，开放全文）发现 MEC 大面积损伤后，CA1 场所场只是"部分降级"而非完全消失——这暗示 LEC 也能传递某种空间相关信息。

2023 年，Bowler 和 Losonczy 的研究（PMID:37816349，PMC:11490304，开放全文）用更直接的方法彻底重写了这个图景。他们直接在虚拟现实导航任务中，用双光子钙成像**在 CA1 的 SLM 内直接记录 MEC 和 LEC 到 CA1 的轴突活动**——这是第一次在行为动物体内直接观察这两条轴突通路。

**关键发现：**

**MEC 传递的是：环境 / 语境地图**
- MEC 轴突表现出**高度位置特异性和环境特异性**
- 同一位置、不同视觉环境（不同的墙纸图案）→ MEC 重映射（不同细胞激活）
- 奖励位置改变（保持环境视觉不变）→ MEC **不重映射**，保持稳定

**LEC 传递的是：目标 / 奖励地图**
- LEC 轴突也表现出位置特异性（！——打破了"LEC 不编码空间"的假设）
- 同一位置、环境视觉切换 →  LEC 保持稳定
- 奖励位置改变（保持环境视觉不变）→ LEC **重映射**，跟踪新的奖励位置
- 约 11.7% 的 LEC 轴突是"奖励追踪"细胞（相比 MEC 只有 3.5%）

最关键的功能测试：选择性化学遗传学抑制 LEC→CA1 投射 → **特异性损害新奖励位置学习**（空间回忆完好，仅目标更新受损）。抑制 MEC→CA1 则无此效应。

**这个发现的认知图谱意义是巨大的：**

CA1 通过 SLM 接收的直接皮层输入不是单一的"空间坐标"，而是两张叠加的地图：
1. **MEC 的环境地图**：这是"你在哪里"（当前环境结构的坐标）
2. **LEC 的目标地图**：这是"你在追求什么"（当前目标位置的信息）

两张地图在同一条神经通路（TA path）内混合传输，在 CA1 的远端树突上汇聚，通过时序 AND 门的条件化整合到位置细胞的活动中。

---

## 机制四：BTSP 的两个 EC 来源

将上述理解延伸到 BTSP（行为时间尺度突触可塑性），2024 年 Dorian 等人的研究（PMID:39253411，PMC:11383060，bioRxiv 预印本，开放全文）提供了一个清晰的解答：当 CA1 通过 BTSP 将一个新的场所场"写入"时，MEC 和 LEC 扮演了分工明确的两个角色。

**实验设计**：在气味线索工作记忆任务中，用双光子钙成像记录 CA1 神经元，同时化学遗传学抑制 MEC 或 LEC 到 CA1 的投射。研究者关注的关键事件是"高钙平台事件"（large somatic calcium events，> 10 标准差振幅）——这正是触发 BTSP 的关键教学信号。

**结果：**
- 抑制 MEC→CA1 → 平台钙事件的**发生频率**从约 1.91 次/神经元/天降至 1.60 次 → BTSP 写入机会减少
- 抑制 LEC→CA1 → 平台钙事件虽然还在发生，但**触发新气味表征的成功率**从 7.20% 降至 3.18%，且生成的气味选择性减弱

**解读：**
- **MEC 提供写入频率**：MEC 的输入是触发 CA1 高钙平台事件的关键驱动力之一，增大 BTSP 的发生机会
- **LEC 提供信息内容**：LEC 的输入携带气味特异性信息（"写入什么"），决定哪些突触被选择性强化，因此决定了 BTSP 能否成功生成一个有意义的表征

这个结果与 Bowler & Losonczy 2023 的图景完美吻合：MEC 提供"当前位置/环境结构"——这是触发 BTSP 的背景条件；LEC 提供"当前目标/内容"——这决定了写入哪个记忆内容。

---

## 记忆巩固中的 TA path：不只是瞬时输入

到目前为止，我们讨论的都是 TA path 在**编码**阶段的作用。但 Remondes 和 Schuman 2004 年的工作（PMID:15470431，未读取全文）揭示了另一个令人惊讶的功能：**TA path 参与长期记忆的系统巩固。**

实验设计：选择性电解毁损 TA path（保留 CA3 Schaffer 侧支完整）。发现：
- 毁损后 24 小时测试的空间记忆：**完好**
- 毁损后 4 周测试的空间记忆：**受损**
- 学习后立即毁损：长期记忆受损
- 学习后 3 周再毁损：长期记忆**不受损**

这意味着：TA path 在学习后的一段时间窗口内持续向 CA1 传递"复习信号"——可能是在每次睡眠的 SWR（sharp-wave ripple）或慢波睡眠期间，EC 持续向 CA1 重放相关的皮层活动，促进记忆从海马依赖阶段向皮层长期存储的转移。一旦转移完成（3 周后），TA path 的损伤就不再影响已经固化的记忆。

这为"系统巩固"理论提供了一个具体的回路机制：TA path 是皮层→海马的"持续教师信号"，在巩固窗口内不断强化海马的记忆痕迹，直到它被彻底迁移到新皮层。

---

## 抑制性中间神经元的协调作用

值得一提的是，这一复杂整合不仅仅依靠兴奋性突触实现，抑制性中间神经元也扮演着关键的协调角色。

Udakis 等人 2020 年（PMID:32879322，PMC:7467931，开放全文）发现，CA1 的两类抑制性中间神经元对 EC 和 CA3 输入的权重进行动态调节：
- **小清蛋白（PV）中间神经元突触发生 LTD**（长时程抑制）→ 解除对 EC 直接输入的抑制
- **生长抑素（SST）中间神经元突触发生 LTP**（长时程增强）→ 强化对 CA3 输入的侧向抑制

这两种互补的可塑性共同作用，**动态重新排列 EC 和 CA3 对 CA1 的相对影响权重**——在新环境中，EC 输入权重上调，帮助 CA1 形成新的场所场；在熟悉环境中，CA3 的联想回忆能力增强，帮助 CA1 稳定已有的场所场。

这是一个精妙的元可塑性（metaplasticity）机制：兴奋性突触的可塑性（BTSP）决定哪些细胞成为场所细胞，而抑制性突触的可塑性决定来自哪个输入通道的信号更有影响力。

---

## 一个比喻：GPS 导航与当地向导

想象你在一个陌生城市开车。你的 GPS（MEC）提供基于地图的精确坐标，告诉你"你现在在北纬 39.9°，东经 116.3°"；与此同时，你的当地向导（LEC）坐在副驾驶，告诉你"前方 200 米有你预定的餐厅"。

你的前额叶（CA1）需要整合两组信息：**你在哪里**（GPS）+ **目标在哪里**（向导）。但整合不是简单相加——你只在先确认了当前位置（GPS 锁定），再接收到向导的目标信息时，才会执行转弯动作。这就是"时序 AND 门"：先有空间背景，再有目标信息，才产生行动。

**比喻的有效范围**：这个比喻很好地传达了"两路信息互补且有时序依赖"的核心概念。

**比喻失效的地方**：真实情况比比喻复杂得多。MEC 和 LEC 不是截然分离的——它们都传递位置信息，区别在于偏向。而且 theta 节律创造的时序门控是一个动态过程，不是静态的先后顺序。此外，CA1 作为"AND 门"需要 NMDA 受体和 GABA_B 信号的精妙交互，而不是 GPS 和向导简单地先后发言。

---

## 它如何改变我们对大脑的理解

这个回路的全图告诉我们几件深刻的事：

**1. 位置细胞不是"感觉转发器"，而是多维整合器**

CA1 的场所场不是简单地反映"我在哪里"，而是整合了"当前环境坐标"（MEC）、"当前目标位置"（LEC）、"联想记忆内容"（CA3）三路信息后的综合表征。这是一个真正意义上的**情境综合子**。

**2. 时序是信息的一部分**

theta 振荡不只是大脑的"背景节拍"，它将不同功能的信息流分配到不同相位，使 CA1 神经元能够按照"先看到 CA3 的联想预测，再确认 EC 的当前感觉"的顺序处理信息。这与 Tolman 的"认知地图"理论的现代神经回路解释直接对应：大脑不只是记录当前感觉，而是在每个 theta 周期内都在"预测—验证—更新"。

**3. 两条通路失衡对应两种不同的记忆障碍**

- EC-III 直接通路损伤 → 空间精准度下降（感觉锚定失效）
- CA3 Schaffer 侧支通路损伤 → 联想回忆能力下降（记忆检索失效）
- TA path 巩固窗口损伤 → 长期记忆无法系统化（皮层转移失败）

这对理解不同类型的记忆障碍（如阿尔茨海默病的 EC 早期损伤为什么先出现空间迷失而非语言障碍）有直接的理论意义。

---

## 争议与未解问题

**1. 网格细胞如何转变为位置细胞？**

MEC-II 的网格细胞提供六边形坐标系，MEC-III 的联合细胞提供速度和方向整合。但从"多个周期性网格的叠加"到"单一紧凑的场所场"的转变机制，至今没有在单细胞水平上被完全证实。竞争性抑制假说、向量叠加假说都存在，但都缺乏直接的体内 causal 验证。

**2. LEC 空间编码的起源**

Bowler & Losonczy 2023 发现 LEC 也传递位置信息，这与经典的"LEC=非空间"框架矛盾。LEC 的位置信号来自何处？它是接收来自旁海马回（parahippocampal cortex）的视觉空间信息？还是通过 CA1→EC 的反馈回路学习到的？还是源于物体在空间位置上的关联记忆？目前尚不清楚。

**3. TA path 的"复习信号"机制**

长期记忆巩固窗口内，TA path 传递的究竟是什么信号？是睡眠期间 EC 自发产生的"离线重播"（offline replay）？还是清醒状态下的某种持续监督？这条通路与 SWR 之间的时序关系（SWR 期间 TA path 是激活还是被抑制？）仍有争议。

**4. 人类的 theta AND 门**

在大鼠体内，theta 振荡（8 Hz）的时序组织相当规律。人类的 theta 振荡频率和相位精度是否足以维持这种精密的时序 AND 门机制？人类颞叶内侧 EC-CA1 回路是否有相似的解剖分层？目前仅有有限的手术中电生理数据，无法得出确定性结论。

---

## 与 AI 的对照

这个回路惊人地像是现代 Transformer 中的**交叉注意力机制（cross-attention）**：

- **Schaffer 侧支（CA3 → CA1）** 类似于"记忆 Query"——从已学习的联想记忆中生成一个"预测状态"
- **TA path（EC-III → CA1）** 类似于"当前感觉 Key-Value"——提供当前时刻的精确感觉输入
- **theta AND 门** 类似于"注意力掩码"——只有当 Query 和 Key 在时序上对齐时，Value 才被整合进输出

更深刻的类比是：
- **MEC 输入** ≈ **位置编码（positional encoding）**——提供 token 的绝对空间位置
- **LEC 输入** ≈ **语义嵌入（semantic embedding）**——提供 token 的内容语义

然而，AI 的注意力机制是固定权重矩阵与输入的乘积，而生物 CA1 的整合是**动态的**：权重由 theta 相位、BTSP 历史、抑制性中间神经元的当前状态共同决定，每一个 theta 周期都是一次独立的动态计算。这种时序动态性是目前的 AI 架构尚未完全复现的。

---

## 今日概念卡片

| 概念 | 定义 |
|------|------|
| 穿通径路（TA path） | EC-III → CA1 直接投射，终止于 SLM，在 theta 振荡的特定相位传递当前感觉情境 |
| 三突触通路 | EC-II → DG → CA3 → CA1，提供联想回忆能力；CA3 Schaffer 侧支终止于 SR |
| 时序 AND 门 | CA1 锥体神经元仅在 Schaffer 先于 TA path 约半 theta 周期激活后，才允许 TA 信号穿透到胞体 |
| MEC vs LEC 分工（新认识） | MEC=环境/语境地图（语境切换时重映射）；LEC=奖励/目标地图（奖励位置切换时重映射）；两者都传递位置信息，但偏向不同 |
| BTSP 的 EC 来源 | MEC 提供触发平台事件的频率（写入机会）；LEC 提供表征的信息内容（写入什么） |

---

## 今日认知地图更新

本文在知识库中新增了以下节点和连接：

**新建 wiki 页**：
- `wiki/circuits/entorhinal-ca1-circuit.md`（内嗅皮层→CA1 双流回路，新建 rev1）
- `wiki/circuits/temporoammonic-path.md`（穿通径路，新建 rev1）

**修订 wiki 页**：
- `wiki/systems/entorhinal-cortex.md`（rev4→rev5）：补充 theta AND 门机制、Bowler 2023 新发现（MEC=语境 vs LEC=目标的修正二分法）
- `wiki/concepts/btsp.md`（rev3→rev4）：新增 MEC/LEC 分工在 BTSP 中的差异化作用（Dorian 2024）
- `wiki/concepts/place-cells.md`（rev2→rev3）：补充 Brun 2002 和 Brun 2008 关于 EC-III 直接通路 vs CA3 间接通路对位置细胞贡献的证据

**新增图谱边**：
- `entorhinal-ca1-circuit` → `btsp`（mechanism-of）
- `entorhinal-ca1-circuit` → `place-cells`（mechanism-of）
- `temporoammonic-path` → `entorhinal-ca1-circuit`（part-of）
- `theta-oscillations` → `entorhinal-ca1-circuit`（regulates）
- `entorhinal-ca1-circuit` → `memory-consolidation`（supports）
- `lateral-entorhinal-cortex` → `entorhinal-ca1-circuit`（part-of）

---

## 参考来源

| # | 来源 | 类型 | 开放全文 |
|---|------|------|----------|
| 1 | Hafting T et al. (2005). Microstructure of a spatial map in the entorhinal cortex. *Nature* 436:801–806. **PMID:15965463** | 研究论文 | 否（仅摘要） |
| 2 | Brun VH et al. (2002). Place cells and place recognition maintained by direct entorhinal-hippocampal circuitry. *Science* 296:2243–2246. **PMID:12077421** | 研究论文 | 否（仅摘要） |
| 3 | Remondes M, Schuman EM (2002). Direct cortical input modulates plasticity and spiking in CA1 pyramidal neurons. *Nature* 416:736–740. **PMID:11961555** | 研究论文 | 否（仅摘要） |
| 4 | Ang CW, Carlson GC, Coulter DA (2005). Hippocampal CA1 circuitry dynamically gates direct cortical inputs preferentially at theta frequencies. *J Neurosci* 25:9567–9580. **PMID:16237162**，**PMC:2048747** | 研究论文 | **是（PMC 全文）** |
| 5 | Remondes M, Schuman EM (2004). Role for a cortical input to hippocampal area CA1 in the consolidation of a long-term memory. *Nature* 431:699–703. **PMID:15470431** | 研究论文 | 否（仅摘要） |
| 6 | Brun VH et al. (2008). Impaired spatial representation in CA1 after lesion of direct input from entorhinal cortex. *Neuron* 57:290–302. **PMID:18215625** | 研究论文 | 否（仅摘要） |
| 7 | Hales JB et al. (2014). Medial entorhinal cortex lesions only partially disrupt hippocampal place cells and hippocampus-dependent place memory. *Cell Rep* 9:893–901. **PMID:25437546**，**PMC:4294707** | 研究论文 | **是（PMC 全文）** |
| 8 | Udakis M et al. (2020). Interneuron-specific plasticity at parvalbumin and somatostatin inhibitory synapses onto CA1 pyramidal neurons shapes hippocampal output. *Nat Commun* 11:4395. **PMID:32879322**，**PMC:7467931** | 研究论文 | **是（PMC 全文）** |
| 9 | López-Madrona VJ, Canals S (2021). Functional interactions between entorhinal cortical pathways modulate theta activity in the hippocampus. *Biology (Basel)* 10:780. **PMID:34439925**，**PMC:8389192** | 研究论文 | **是（PMC 全文）** |
| 10 | Bowler JC, Losonczy A (2023). Direct cortical inputs to hippocampal area CA1 transmit complementary signals for goal-directed navigation. *Neuron* 111:4071–4085. **PMID:37816349**，**PMC:11490304** | 研究论文 | **是（PMC 全文）** |
| 11 | Dorian CC et al. (2024). Behavioral timescale synaptic plasticity in the hippocampus creates non-spatial representations during learning and is modulated by entorhinal inputs. *bioRxiv* preprint. **PMID:39253411**，**PMC:11383060** | 预印本 | **是（PMC 全文）** |

**来源说明**：
- 来源 1–3、5–6：均为经典历史文献，仅读取了摘要；结论有后续研究广泛引用验证，置信度高。
- 来源 11：预印本（bioRxiv 2024），尚未经过同行评审，但来自 Golshani 实验室，方法严谨，机制与已有理解高度一致；本文引用时已明确标注"预印本"，并在相关表述中保持保守语气。

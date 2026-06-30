# 目标导向还是习惯？纹状体双系统的分子开关机制

> **今日核心问题**：当行为从"有意识的选择"过渡到"无须思考的自动执行"，大脑究竟在哪里、用什么分子手段完成了这次交接？背内侧纹状体（DMS）和背外侧纹状体（DLS）的双系统框架在 2021–2026 年间收到了一系列颠覆性的细节修正——习惯的形成不只是 DLS 的"胜利"，还需要 DMS 直接通路的主动"退场"，眶额叶—纹状体内大麻素路径则是扳动这个开关的分子手柄。

**一句话摘要**：目标导向行为（DMS 依赖，model-based）与习惯行为（DLS 依赖，model-free）是两套从第一天起就并行运行的回路，习惯的获得需要同时完成"DLS 长时程增强"和"DMS 直接通路突触压制"两步操作，眶额叶→DLS 的 CB1 内大麻素信号是触发习惯转换的关键分子门控，而成瘾药物恰好通过损毁 DMS D1 神经元的目标导向功能来破坏这两套系统的平衡。

**日期**：2026-10-20 | **文章编号**：#188 | **层级**：行为 / 回路 / 细胞 / 分子

---

## 为什么重要

每天早上，你走向咖啡机，不需要查看说明书，不需要列举这动作的理由，手已经先一步完成了。这就是习惯——一种"被动执行"的、无需当前目标驱动的行为。与之对立的是目标导向行为：你知道这个行动会产生什么结果，你也知道那个结果现在值多少，所以你选择行动。

这两种行为策略对应大脑的两套平行系统，而它们之间的平衡决定了你在日常生活中有多大程度上活在"自动驾驶"模式里。更重要的是，这个平衡的失调与一系列神经精神疾病直接相关：
- **成瘾**（addiction）：奖励信号劫持习惯回路，使觅药行为在后果极端负面时依然持续
- **强迫症**（OCD）：习惯回路异常增强，目标导向系统无法压制不必要的重复行为
- **帕金森病**（PD）：多巴胺系统受损导致两套系统同时失能
- **老龄化**：D1/D2 通路逐渐失去年轻态的弹性，越来越容易落入习惯模式

理解这个开关如何被扳动，就是理解大脑如何在灵活性和效率之间做出权衡的核心问题。

---

## 背景：Balleine 和 Dickinson 的双系统框架

行为神经科学中区分"目标导向"与"习惯"的金标准测试，是由 Bernard Balleine 和 Anthony Dickinson 在 1990 年代建立的**结果贬值范式**（outcome devaluation）：让动物学会"按杆→获得食物奖励"后，通过让动物吃饱（饱食贬值）或对食物本身产生厌恶（味觉厌恶贬值）来降低该结果的当前价值，然后测试动物是否继续按杆。

- **目标导向**的动物：立即降低按杆频率——它们知道食物价值降低了，因此调整行动
- **习惯化**的动物：继续按杆，对结果贬值不敏感——动作与结果的因果联结已断裂

这个范式确定了：
- 背内侧纹状体（DMS，在人类同源于尾状核内侧/前部）损毁：即使在早期训练阶段也导致习惯化（Yin et al. 2005, PMID:16045504）
- 背外侧纹状体（DLS，在人类同源于壳核后外侧）损毁：即使过度训练也无法形成习惯（Yin et al. 2004, PMID:14750976）

经典框架因此认为：DMS = 目标导向，DLS = 习惯，二者相互拮抗，通过下边缘皮层（IL）的竞争性抑制协调（Coutureau & Killcross 2003, PMID:14643469）。

---

## 机制：分层解析习惯形成

### 第一层：多巴胺三因素规则的纹状体实现

纹状体可塑性的分子基础是**多巴胺依赖性三因素学习规则**：

$$\Delta w \propto (\text{突触前活动}) \times (\text{突触后去极化}) \times (\text{多巴胺})$$

Shen et al.（2008, PMID:18687967）在 D1/D2-EGFP 荧光报告小鼠脑切片中，用精确的 STDP 协议直接证明了这一规则在两类细胞中的**不对称实现**：

| | D1-MSN（直接通路） | D2-MSN（间接通路） |
|--|--|--|
| 正时序 STDP + 高 DA | **LTP**（D1→PKA→AMPAR 磷酸化） | **LTD**（D2→CB1→内大麻素） |
| 负时序 STDP + 低 DA | 无效（D1 阻断 mGluR5-CB1 路径） | **LTP**（A2a→腺苷酸环化酶） |

这不是简单的"DA 高→LTP 更强"，而是 DA 从根本上改写了 STDP 的**方向规则**。D1-MSN 在奖励（高 DA）时几乎只能 LTP；D2-MSN 在奖励时几乎只能 LTD。奖励时，两条通路同时被"写入"，实现"正确行为强化 + 竞争行为清除"的对称学习。

### 第二层：直接与间接通路的对立调控（Bakhurin et al. 2020）

经典模型认为直接通路"促进行动"、间接通路"抑制行动"，两者像开关一样互斥。但 Bakhurin et al.（2020, eLife, PMID:32324535，开放全文）发现，两条通路在动作执行过程中**都被激活**，只是功能不同：

- **直接通路（D1-MSN/纹状体黑质通路）**：启动行动并**重置内部时序计时器**
- **间接通路（D2-MSN/纹状体苍白球通路）**：**暂停时序计时器**并在竞争行动间进行选择

这将两条通路的功能从"行动/停止"的二分模型，升级为"行动时序的双向调控器"。

### 第三层：DMS D1-MSN 的主动"退场"——Yu et al. 2021 的关键发现

经典框架假设习惯化过程中，DMS 保持中立或逐渐"被忽视"，主控权自然转移给 DLS。但 Yu et al.（2021, Cerebral Cortex, PMID:33774666）揭示了一个关键事实：**习惯形成过程中，DMS 直接通路 D1-MSN 的兴奋性突触发生了突触后压制（synaptic depression）。**

具体发现：
1. 过度训练（生成习惯）后，DMS D1-MSN 的皮层→纹状体兴奋性突触 EPSC 幅度显著降低
2. 这种压制是 DMS 特异性的（DLS 无此变化）
3. 化学遗传学（DREADD）**拯救**这种压制（使 D1-MSN 恢复正常兴奋性），会**损害习惯的获得**，但不影响已形成习惯的**表达**

这个发现重新定义了习惯的形成逻辑：

**旧框架**：习惯 = DLS 突触增强 + DMS 失活（被动）
**新框架**：习惯 = DLS 突触增强 + **DMS 直接通路的主动突触压制**（主动退场）

换言之，习惯不只是 DLS "接管了控制权"，而是 DMS 的 D1-MSN 首先放弃了竞争——大脑在 DMS 侧主动降低目标导向系统的敏感性，为 DLS 接管创造条件。

### 第四层：眶额叶 CB1 内大麻素门控——分子开关（Gremel et al. 2016）

习惯的形成需要一个"触发器"来启动 DMS→DLS 的权力转移。Gremel et al.（2016, Neuron, PMID:27238866，开放全文 PMCID:PMC4911264）发现，这个分子触发器是**眶额叶（OFC）→纹状体投射末梢的 CB1 大麻素受体**：

实验设计：选择性敲除 OFC 皮层锥体神经元（而非其他来源）的 CB1 受体

核心发现：
- **CB1 缺失小鼠**：经过相同的过度训练后，动作控制**始终保持目标导向**，无法完成到习惯的转换——它们对结果贬值始终敏感
- **机制推断**：正常情况下，OFC 神经元活动触发树突末梢的内大麻素释放（retrograde），CB1 受体被激活后抑制 OFC→DLS 的兴奋性传递。这种抑制削弱了 OFC 对 DLS 的目标导向输入，使 DLS 的习惯性 S-R 联结逐渐主导

这一发现有重要的临床意义：OFC 在强迫症和成瘾中高度异常，CB1 激活（如大麻素使用）可能影响目标导向/习惯的平衡，而 OFC-DLS 电路可能是干预目标。

### 第五层：D1+ 与 A2A+ 神经元的不对称命运——Malvaez et al. 2025

Malvaez et al.（2025, bioRxiv, PMID:39896502, PMCID:PMC11785256，开放全文）通过**单细胞钙成像**，追踪了小鼠在学习目标导向行动、然后经过过度训练形成习惯的整个过程中，DMS D1+ 和 A2A+（D2 型）神经元的活动轨迹：

| 细胞类型 | 目标导向学习阶段 | 习惯化后 | 功能意义 |
|---------|----------------|---------|---------|
| D1+ 直接通路 | **稳定编码行动 + 发展出结果编码** | 继续稳定编码 | 始终追踪行动-结果关系 |
| A2A+（D2）间接通路 | 初期编码行动 | **活动重新组织**，从行动编码转为刻板模式 | 从学习阶段转入习惯执行程序 |

最关键的化学遗传学发现：
- 抑制 D1+ 神经元 → 损害目标导向决策，但习惯保留
- 抑制 A2A+ 神经元 → 损害初期动作-结果学习，但一旦建立，目标导向决策可正常执行
- **只有 D1+ 神经元的活动能够实现基于结果价值的目标导向决策**

这揭示了一个精妙的劳动分工：D1+ 神经元是目标导向决策的"持续看门人"，A2A+ 神经元在学习初期是必要的，但最终"迁移"到支持习惯的执行模式。

---

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| DLS 损毁→过度训练后依然目标导向（不能形成习惯） | DLS 双侧损毁 + 结果贬值范式 | PMID:14750976 | 高 |
| DMS 损毁→早期训练后即习惯化 | DMS 双侧损毁 + 结果贬值 | PMID:16045504 | 高 |
| IL 沉默→习惯化大鼠恢复目标导向敏感性 | Muscimol 抑制 IL + 结果贬值 | PMID:14643469 | 高（大鼠） |
| DMS D1-MSN 突触压制是习惯获得的必要条件 | DMS D1 DREADD 增强→习惯获得受损；体外 EPSC 记录 | PMID:33774666 | 中-高（单实验室，需独立复制）|
| OFC→DLS CB1 敲除→无法习惯化 | 皮层特异性 CB1 KO + 工具性学习 + 结果贬值 | PMID:27238866 | 高（开放全文，独立实验室）|
| D1-MSN vs D2-MSN STDP 规则不对称（多巴胺反转方向） | D1/D2 EGFP 小鼠脑切片 + 精控 STDP + 药理 | PMID:18687967 | 高（复制性强）|
| D1+ 神经元支持目标导向决策；A2A+ 重组为习惯模式 | DMS 钙成像 + DREADD + 过度训练范式 | PMID:39896502 | 中（预印本，2025）|
| DLS 刺激（DREADD）消除目标导向控制（对侧和同侧） | DLS DREADD 激活 + 结果贬值 + 奖励驱动复原 | PMID:40771101 | 中-高（2025）|
| 目标导向 vs 习惯回避行为同样依赖 DMS vs DLS | 大鼠主动回避 + 结果贬值（安全信号贬值） + 化学遗传学 | PMID:41663373 | 中-高（2026，已出版）|
| METH 环境暴露损伤 DMS D1 神经元活动，A2a 拮抗恢复目标导向 | c-Fos 染色 + DMS ZM241385 注射 + 负反馈敏感性 | PMID:26515740 | 高（开放全文）|

---

## 一个比喻，以及它在哪里失效

**比喻**：想象大脑的决策是一个导航 APP（目标导向）和一个老驾驶员的肌肉记忆（习惯）并行运行。在新路上，你用 APP；在每天上班的路上，你关掉 APP 靠肌肉记忆。

**比喻有效的地方**：这个类比抓住了"并行系统竞争控制"的本质——APP 和肌肉记忆都一直存在，只是控制权在不同情境下切换。

**比喻失效的地方**：
1. 生物学上，"关掉 APP"不是被动的——DMS D1-MSN 需要主动被压制（突触压制）。没有这个主动退场，习惯无法稳固建立。
2. "肌肉记忆"暗示纯粹的末梢执行，但 DLS 实际上仍然接受皮层调控，只是换成了来自感觉运动皮层的输入，而不是眶额叶/前边缘皮层的决策输入。
3. 习惯不是"遗忘了有 APP"——暂时性抑制 IL，目标导向立即恢复。这更像是"主动关机"而非"忘记密码"。

---

## 它如何改变我们对大脑的理解

**经典图景**（约 2010 年）：  
习惯形成 = DLS 被动积累 S-R 联结；DMS 系统随训练重复逐渐"退后"。习惯是 DLS 的"增益"，目标导向是 DMS 的"增益"，转换只是两者相对权重的此消彼长。

**修正图景**（2021-2026 年后）：  
习惯形成是一个**多步骤、主动构建**的过程：

1. **OFC→DLS CB1 内大麻素门控**首先被开启（Gremel 2016）——这是习惯形成的分子许可
2. **DMS D1-MSN 的突触压制**发展出来（Yu 2021）——这是目标导向系统的主动退场
3. **D1+ 神经元继续监控行动-结果关系**，而 **A2A+ 神经元重组为习惯执行模式**（Malvaez 2025）——两种细胞类型有不同命运
4. 最终，**DLS 刺激本身就能主动消除目标导向控制**（Hart 2025）——习惯不只是 DMS 退场的结果，DLS 主动抑制 DMS 的目标导向评估

这幅图景更接近于：习惯不是"无为的自动化"，而是大脑**主动建设的一条捷径**，它既需要 DLS 的增强，也需要 DMS 的主动降权。

---

## 成瘾：习惯回路被药物劫持

成瘾提供了最清晰的"病理性习惯"窗口。Furlong et al.（2017, Addiction Biology, PMID:26515740，开放全文）在甲基苯丙胺（METH）处理大鼠中发现：

- 将大鼠放入 METH 配对的情境中（不需要给药），其**选择行动**对负反馈不再敏感——行为已经习惯化
- c-Fos 染色显示：DMS 中**非脑啡肽（非 D2）的神经元**（即 D1 直接通路神经元）活动显著降低，DLS 无此变化
- 向 DMS 局部注射腺苷 A2a 受体拮抗剂（ZM241385），使 D2 信号相对降低/D1 相对升高，**完全恢复**了对负反馈的敏感性

这提示成瘾的机制之一是：药物配对的情境通过降低 DMS D1 神经元活动，复制了"习惯化"时 DMS 的状态——但这次的驱动力不是学习积累，而是药物的神经毒性效应。

这与 Yu et al.（2021）的发现形成了精彩的对应：正常习惯化需要 DMS D1-MSN 突触压制；成瘾的习惯化也正是通过破坏同一条通路来实现的。

---

## 争议与未解问题

**1. DMS D1-MSN 突触压制的具体机制是什么？**  
Yu et al.（2021）只描述了现象（EPSC 降低），但压制的分子机制未明确。是 AMPAR 内化（类似海马 LTD）？还是突触前谷氨酸释放减少？还是涉及内大麻素？目前不知道。

**2. DLS 的"主动抑制"是抑制 DMS 的哪个环节？**  
Hart et al.（2025）发现 DLS 刺激消除目标导向，但具体的抑制路径是什么？DLS→GPe→STN→GPi 的间接通路是否反馈抑制了 DMS 相关的丘脑-皮层环路？

**3. 两条通路的"共同激活"范式能与 go/no-go 框架调和吗？**  
Bakhurin et al.（2020）发现两条通路都在运动中激活，这与经典 go/no-go 模型矛盾。具体解释仍有争议：是竞争行动的抑制、时序调控、还是完全不同的功能？

**4. 成瘾治疗的目标在哪里？**  
如果成瘾是通过损伤 DMS D1 通路来习惯化的，那么**增强 DMS D1-MSN 的目标导向功能**是否能恢复控制？Furlong 2017 的 A2a 拮抗剂实验提示这可能，但持续时间、副作用和人类转化尚不清楚。

**5. 性别差异被严重低估**  
Sears et al.（2026, Nature Communications, PMID:41663373）发现：雄性大鼠在过度训练后对安全信号贬值不敏感（习惯化），但**雌性大鼠始终对情境依赖性反结果条件化（counterconditioning）高度敏感**——即在目标导向/习惯的平衡上存在显著性别差异。这与焦虑症和 PTSD 的性别差异是否存在关联？完全未知。

---

## 与 AI 的对照

目标导向 vs 习惯行为在计算神经科学中有精准的对应：

| 生物系统 | AI 对应 | 差异 |
|---------|---------|------|
| DMS（目标导向） | Model-based 强化学习（规划树搜索） | 大脑的 MB-RL 使用真实的因果世界模型，而不仅仅是值函数 |
| DLS（习惯） | Model-free 强化学习（Q-learning/TD 学习） | 生物 Q 值通过 D1/D2 STDP 存储在突触权重中 |
| DMS D1-MSN 压制 | "遗忘"先验、降低 MB 通道的学习率 | AI 系统的 MB/MF 切换通常通过置信度阈值实现，生物机制是主动突触压制 |
| OFC→DLS CB1 门 | 自适应 Meta-learning（何时使用 MB 何时切换 MF） | CB1 内大麻素提供了一种化学信号层面的切换门控，AI 中无类似机制 |

生物系统的一个深刻优越性：它的 MB/MF 切换有**电化学时间常数**——CB1 内大麻素的信号整合发生在数分钟到数小时的时间尺度上，天然实现了"足够训练次数后再切换"的防过早切换机制。AI 的 MB/MF 混合架构（如 Dyna、Dreamer）通常缺乏这种时间常数，难以防止随机扰动导致过早切换。

---

## 今日概念卡片

**结果贬值范式（Outcome Devaluation）**  
行为神经科学的金标准工具，用于区分目标导向行为和习惯行为。核心逻辑：如果动物的行为受当前结果价值控制（目标导向），那么降低结果价值（通过饱食或味觉厌恶）应立即减少行为；如果行为已变成习惯（S-R 联结），则对结果贬值不敏感。

关键特点：
- **饱食贬值**（specific devaluation）：让动物在测试前自由采食该奖励食物，降低其当前驱动价值
- **味觉厌恶贬值**（lithium chloride pairing）：让动物对某种食物产生条件性厌恶
- 经过适当训练次数（中等）：多数动物表现出目标导向（对贬值敏感）
- 经过过度训练（大量重复）：向习惯转变（对贬值不敏感）

---

## 今日认知地图更新

今天的文章触及了以下概念节点，将对知识库进行如下更新：

**新建 wiki 页**：
- `wiki/concepts/habit-vs-goal-directed.md`（填补 striatal-direct-indirect-pathway 页的悬空引用）

**修订 wiki 页**：
- `wiki/concepts/goal-directed-behavior.md`（rev1→rev2）：整合 Malvaez 2025 D1+ 稳定性、Sears 2026 回避行为证据、Hart 2025 DLS 主动抑制发现
- `wiki/concepts/habitual-behavior.md`（rev2→rev3）：整合 Gremel 2016 CB1 门控、Yu 2021 DMS D1 压制、Bakhurin 2020 时序对立
- `wiki/circuits/striatal-direct-indirect-pathway.md`（rev2→rev3）：整合 Malvaez 2025 D1+/A2A+ 命运分叉

**矛盾检查**：Malvaez 2025 发现 A2A+ 神经元也支持早期 A-O 学习，与现有 habitual-behavior.md 中"D2 间接通路主导习惯"的表述需要细化（D2 初期必要，但最终特化为习惯执行）——不矛盾，但需要明确分阶段描述。

---

## 参考来源

1. **Yin HH et al. (2004)** - "Lesions of dorsolateral striatum preserve outcome expectancy but disrupt habit formation in instrumental learning" - European Journal of Neuroscience - **PMID:14750976** - （习惯必须 DLS）
2. **Yin HH et al. (2005)** - "The role of the dorsomedial striatum in instrumental conditioning" - European Journal of Neuroscience - **PMID:16045504** - （目标导向必须 DMS）
3. **Coutureau E & Killcross S (2003)** - "Inactivation of the infralimbic prefrontal cortex reinstates goal-directed responding in overtrained rats" - Behavioral Brain Research - **PMID:14643469** - （IL 压制目标导向）
4. **Shen W et al. (2008)** - "Dichotomous dopaminergic control of striatal synaptic plasticity" - Science - **PMID:18687967** - PMCID:PMC2833421（开放全文）- （D1/D2 不对称 STDP）
5. **Gremel CM et al. (2016)** - "Endocannabinoid Modulation of Orbitostriatal Circuits Gates Habit Formation" - Neuron - **PMID:27238866** - PMCID:PMC4911264（开放全文）- （OFC CB1 门控习惯）
6. **Furlong TM et al. (2017)** - "Pulling habits out of rats: adenosine 2A receptor antagonism in dorsomedial striatum rescues meth-amphetamine-induced deficits in goal-directed action" - Addiction Biology - **PMID:26515740** - PMCID:PMC4851927（开放全文）- （A2a 拮抗剂恢复目标导向）
7. **Bakhurin KI et al. (2020)** - "Opponent regulation of action performance and timing by striatonigral and striatopallidal pathways" - eLife - **PMID:32324535** - DOI:10.7554/eLife.54831（开放全文）- （两通路对立调控时序）
8. **Yu X, Chen S, Shan Q (2021)** - "Depression in the Direct Pathway of the Dorsomedial Striatum Permits the Formation of Habitual Action" - Cerebral Cortex - **PMID:33774666** - （DMS D1-MSN 突触压制，关键新发现）
9. **Malvaez M et al. (2025)** - "Striatal cell-type specific stability and reorganization underlying agency and habit" - bioRxiv - **PMID:39896502** - PMCID:PMC11785256（开放全文）- 预印本，待同行评审 - （D1+ 稳定，A2A+ 重组）
10. **Hart G et al. (2025)** - "Unilateral Stimulation of the Dorsolateral Striatum Attenuates Goal-Directed Action" - European Journal of Neuroscience - **PMID:40771101** - （DLS 主动消除目标导向）
11. **Sears RM et al. (2026)** - "Devaluation of response-produced safety signals reveals circuits for goal-directed versus habitual avoidance in dorsal striatum" - Nature Communications - **PMID:41663373** - PMCID:PMC13000197（开放全文）- （扩展到主动回避行为，性别差异）

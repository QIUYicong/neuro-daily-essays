# 睡眠如何修剪突触：Homer1a 与 Arc 的分子协奏

**文章编号**：#176  
**日期**：2026-10-16  
**字数**：约 5200 字  
**课程轨迹**：睡眠系列第 7 篇（#170 TRN→#171 SWR→#172 翻转开关→#173 腺苷/Process S→#174 SHY/ON-OFF→#175 NT1 疾病→#176 分子机制）

---

## 今日核心问题

**在 NREM 睡眠期间，突触是如何在分子层面被"削减"的？是哪些蛋白质触发了 AMPA 受体从突触后膜上的移除，而它们又是如何只削减"普通"突触、精准跳过新鲜记忆印迹？**

---

## 一句话摘要

睡眠期间，随着去甲肾上腺素（NA）水平下降，长期被阻止进入突触后致密区（PSD）的 Homer1a 蛋白终于得以进入并瓦解 mGluR5-IP3R 信号复合物，同时 Arc 蛋白也借助"逆向突触标记"机制优先靶向静默突触并调用 dynamin/endophilin 内吞机器，共同驱动 GluA1 含量 AMPA 受体从突触脱落；而刚经历过 LTP 的"印迹突触"则因磷酸化的 CaMKIIβ 排斥 Arc，成功躲过这场删减。

---

## 为什么重要

几周前，我们在#174 中确认了突触稳态假说（SHY）的一个核心主张：皮层神经元在清醒期间进入 ON 态（高放电），使突触总体权重攀升；在 NREM 睡眠期间，周期性的 OFF 态被 Driessen 等人（2026）的体内记录证实为突触权重确实下调的窗口。但那篇文章留下了一个问题没有回答——**是哪些分子在执行这场删减？**

这个问题有三层难度。第一，突触重量的物理实现是 AMPA 受体：突触后致密区（PSD）里受体越多，权重越高；要削减突触，就必须移除受体。第二，"全局移除"在概念上是简单的，但大脑需要的是"选择性移除"——刚刚学到的记忆不能随睡眠灰飞烟灭。第三，这场删减必须在睡眠期间自动发生，受神经调质的门控，而非依赖意识指令。

2017 年到 2024 年间的一批实验，为上述三层难题提供了令人信服的分子答案。这些答案不仅解释了 SHY 的机制，也揭示了一种令人惊讶的生物工程学之美：大脑用来编写记忆的同一套分子，也被用来决定哪些记忆可以在睡眠中幸存。

---

## 背景：AMPA 受体是突触权重的货币

在正式进入睡眠之前，我们需要先理解突触"货币"。大脑中大多数快速兴奋性突触传递由 AMPA 受体完成：谷氨酸与受体结合后数毫秒内打开阳离子通道，产生突触后兴奋电流（EPSC）。突触后 AMPA 受体的数量，几乎直接决定了这个突触的权重。

AMPA 受体是由 GluA1–4 亚基组成的四聚体。在成人海马 CA1 区，最常见的是 GluA1/GluA2 异聚体。两种亚基的胞内 C 末端截然不同，承担着不同角色：

- **GluA1**：C 末端较长，含 **Ser845**（PKA 磷酸化位点）和 **Ser831**（CaMKII 磷酸化位点）。LTP 期间 Ser831 磷酸化后，受体被优先插入突触。Ser845 的磷酸化状态与表面 GluA1 的数量紧密相关：磷酸化→表面增加；去磷酸化→易于内吞。
- **GluA2**：C 末端较短，负责 AMPA 受体的组成性循环（constitutive cycling），维持基础突触传递；其 Ser880 的磷酸化影响与 GRIP1/2 的锚定及随后的内吞。

睡眠研究者注意到一件事：在睡眠期与剥夺睡眠后的对比实验中，最敏感地变化的受体亚基是 **GluA1**，尤其是 **磷酸化 Ser845 的 GluA1**。这意味着睡眠依赖的突触削减，很可能通过一条 GluA1 特异性的路径而非经典的突触稳态缩放（经典缩放使用 GluA2 通路）执行。

---

## 新证据：睡眠剥夺使 GluA1 飙升，恢复睡眠将其拉回

**Squarcio、Tononi 与 Cirelli（2024，PMID:38973508）**在小鼠皮层突触体（synaptosome）中直接测量了 GluA1 和 磷酸-GluA1(Ser845) 在不同觉醒/睡眠状态下的表达水平（开放全文，PMC11895523）。

实验设计清晰：成年小鼠被分为三组——自然睡眠 5 小时（Sleep）、睡眠剥夺 5 小时（SD）、睡眠剥夺后恢复睡眠 5 小时（RS）。从各组小鼠皮层制备突触体后，用 Western blot 定量 GluA1 总量和磷酸-GluA1(845)。

结果令人印象深刻：

- 剥夺睡眠组的皮层突触体 GluA1 水平比正常睡眠组高出 **43.8%**（±6.8%，p=0.025）
- 恢复 5 小时睡眠后，GluA1 从剥夺水平下降了 **31.7%**（±3.5%，p=0.02），基本归位
- 磷酸-GluA1(Ser845) 在睡眠剥夺后比正常睡眠高出 **78.9%**（±18.8%，p=0.015）
- 老年小鼠显示出类似的模式（p-GluA1(845) 剥夺后高出 **87.9%**）

同样重要的是他们对 **REM 睡眠特异性**的排查：选择性去除 REM 睡眠（保留 NREM）的小鼠，GluA1 仍然正常下降（降低 30.5%）。这说明 GluA1 的削减**需要 NREM 睡眠，不需要 REM**。

与此同时，**Liu 等人（2024，PMID:39163472）**在下丘脑中重复了类似的发现（开放全文，PMC11364421）：总睡眠剥夺后下丘脑突触 GluA1 升至正常睡眠水平的 **142.7%**，慢波睡眠（SWS）是将其拉回的关键。

---

## Homer1a：被 NA 囚禁于胞质的分子开关

仅仅知道 GluA1 在 NREM 睡眠中下降，还不等于知道机制。**Diering 等人（2017，PMID:28154077，Science）**的研究揭示了一个既优雅又意想不到的分子开关：**Homer1a**（开放全文，PMC5382711）。

Homer 蛋白家族是突触后支架蛋白，通过 EVH1 结构域结合 mGluR1/5 受体，同时通过 C 端卷曲螺旋（coiled-coil）域与 IP3 受体（IP3R）以及 Shank 等骨架蛋白交联，把代谢型谷氨酸受体信号与下游 PLC-IP3-Ca²⁺ 通路连接在一起。这个完整的 Homer 蛋白（长型 Homer）是清醒状态突触的标配组件。

**Homer1a** 是 Homer1 基因在强烈神经活动后诱导产生的**即早基因（IEG）短型转录本**。它包含 EVH1 结构域（可与 mGluR1/5 结合），但**缺少 C 端卷曲螺旋**——这使它成为天然的"显性负效应蛋白"（dominant negative）：它能与 mGluR1/5 竞争结合，却无法与 IP3R 和 Shank 交联，从而瓦解整个信号复合物。

**关键问题**：如果 Homer1a 在神经活动期间（清醒时）大量表达，为什么它不会在清醒时就开始破坏突触？

答案来自神经调质。

Diering 2017 的实验表明：
1. **去甲肾上腺素（NA）在清醒时高水平持续存在，将 Homer1a 排斥在 PSD 之外**。清醒小鼠若阻断 α/β 肾上腺素受体，PSD 中 Homer1a 水平即显著升高。
2. **腺苷是睡眠方向的门控信号**。阻断腺苷 A1 受体（A1R）能**完全阻止**睡眠压力状态下 PSD-Homer1a 的升高；给予 A1R 激动剂则可在清醒时模拟 Homer1a 的突触靶向。

这与我们在#173 中建立的腺苷框架完美咬合：清醒期 → 腺苷积累 → A1R 激活 → Homer1a 得以进入 PSD；与此同时，入睡时 NA 水平骤降 → Homer1a 进入 PSD 的另一道门也同时打开。两个信号叠加，共同在睡眠初期将 Homer1a 定向输入突触。

**Homer1a 进入 PSD 后做什么？** 它与 mGluR1/5 结合，把长型 Homer 顶出（争夺结合位点），瓦解 mGluR1/5-IP3R-PKCγ 信号复合体。失去完整架构后，GluA1 和 GluA2 亚基开始脱离 PSD，受体数量减少，突触权重下降。

Martin、Monroe 与 Diering（2019，PMID:30923476，PMC6430175）进一步证明，Homer1a 驱动 mGluR1/5 信号模式从"清醒模式"（IP3R→Ca²⁺振荡→激活）切换到"睡眠模式"（解耦→低 Ca²⁺），这一切换本身就是突触由强变弱的分子时刻。

---

## Arc：逆向突触标记与 AMPA 受体内吞

与 Homer1a 并行运作的是**Arc/Arg3.1**（活动调控的细胞骨架相关蛋白）。Arc 在我们的知识库里有自己的页面（#arc-arg31），在 LTD 中已有充分记录：它通过与 **endophilin** 和 **dynamin** 结合，加速 AMPA 受体的网格蛋白介导的内吞。

在睡眠背景下，Arc 承担了额外的、更精妙的功能——**逆向突触标记（inverse synaptic tagging）**，由 Diering（2022，PMID:36632309，PMC9826981）系统阐述。

原理如下：

- **活跃的、刚经历 LTP 的突触**：CaMKII 处于磷酸化激活态（pCaMKIIβ）。Arc 与磷酸化 CaMKIIβ 结合的亲和力**低**——Arc 被这类突触排斥。
- **安静的、未被近期增强的突触**：CaMKII 处于去磷酸化态。Arc 与去磷酸化 CaMKIIβ 的亲和力**高**——Arc 优先聚集于此，召唤 endophilin/dynamin 内吞 AMPAR。

这就是"逆向标记"的含义：Arc 不标记活跃突触，而是**标记所有非活跃突触**，将它们批量内化 AMPAR。结果是：普通背景突触被削减，而刚刚被学习"选中"的突触（pCaMKIIβ 高，Arc 进不来）得以幸存，甚至相对而言变得更突出。

这套机制回答了 SHY 一直以来最难解释的问题：**睡眠削减突触，为什么不会同时删除刚学会的记忆？** 因为分子层面有一道自动"豁免"机制——记忆印迹的突触携带着磷酸化印章，Arc 认不出它们，跳了过去。

**Suzuki、Yanagisawa 与 Greene（2020，PMID:32350140，PMC7229651）**提供了遗传证据：Arc 敲除小鼠在睡眠剥夺后的恢复睡眠（rebound）显著减弱（行为层面），且脑内与睡眠剥夺相关的 GluA1 上调和磷酸化变化均大幅减弱。这说明 Arc 不仅在体外、而且在体内，都是睡眠相关突触稳态的必要分子。同时，他们发现睡眠剥夺使核内 Arc 增加约 **2.5 倍**——这部分核 Arc 在 PML 核体中抑制 GluA1 mRNA 转录，从另一角度减少 GluA1 的供应，与胞质 Arc 促进内吞形成双向削减。

---

## 两个机制如何协同

现在我们可以把 Homer1a 和 Arc 的角色整合起来：

**入睡时的分子事件时间线**：

1. 去甲肾上腺素下降（蓝斑放电减弱）→ Homer1a 进入 PSD 的 NA 屏障解除
2. 腺苷积累激活 A1R → 主动促进 Homer1a 靶向 PSD
3. **Homer1a 进入 PSD**，与 mGluR1/5 结合 → 信号复合物瓦解 → GluA1/GluA2 开始松动
4. 同时，**Arc 与去磷酸化 CaMKIIβ 结合**，在安静突触的内吞机器旁边就位
5. GluA1 Ser845 去磷酸化（PKA 活性下降，因为 NA 降低了 cAMP） → GluA1 从突触横向扩散到突触外区域
6. Arc/dynamin/endophilin 网格蛋白小泡形成 → GluA1 内吞
7. 净效果：突触 GluA1 减少、突触权重下降；但 pCaMKIIβ 标记的"印迹突触"逃过了 Arc 的靶向，在相对噪音降低后显得更为突出

这场协同发生在 NREM 睡眠的慢波 ON-OFF 期间，与#174 中建立的 OFF 期突触权重下调机制在时间上吻合。OFF 期的静默（膜下超极化）可能为 GluA1 的横向扩散提供了时间窗口：在无谷氨酸激活时，受体更容易从 PSD 的"槽位"逸出。

---

## 睡眠纺锤波：削减中的例外，记忆的保护层

然而事情并非如此简单。**Liu 等人（2024，PMC11364421）**发现，下丘脑中睡眠纺锤波（sleep spindle）的密度与 GluA1 水平之间存在**正相关**——纺锤波密度越高，局部 GluA1 反而更高，而非更低。

这一乍看矛盾的发现，实际上揭示了睡眠突触动力学的双轨并行：

- **慢波（SWS/NREM 整体）**：驱动 Homer1a/Arc 介导的全局 AMPA 受体削减
- **睡眠纺锤波**：Ca²⁺ 内流触发局部可塑性，在某些突触选择性地**增加** GluA1 表达

纺锤波是大脑在睡眠中"重放"新记忆时产生的高频振荡（12–15 Hz），起源于丘脑，在整个皮层传播。每一次纺锤波都引发短暂的局部去极化和 Ca²⁺ 内流，足以磷酸化 CaMKII，推动 AMPA 受体从内体重新插入对应突触。于是，那些在清醒期被学习经历"标注"过的突触，在睡眠纺锤波的照耀下得到了进一步强化，而全局背景权重正在 Homer1a/Arc 的作用下被削减。

这一双轨机制——全局削减 + 局部增强——正是 SHY 理论所需要的：不是把所有突触一刀切地压缩，而是**降低噪音底板，同时提升信噪比**，让有用的记忆在对比度增强后更为醒目。

---

## 另一个角度：脑干 GABA 神经元的 AMPA 受体上调

**Ba 等人（2026，PMID:42161267）**刚刚在 Current Biology 上报告了一个角度不同但同样重要的发现。他们在小鼠脑干口部脑桥网状核（oral pontine reticular nucleus）发现了一群清醒期活跃的 GABAergic 神经元，这些神经元在睡眠剥夺后开始**上调 GluA1 含量 AMPA 受体**和突触蛋白，随后在恢复睡眠的前一个小时内表现出短暂的活动增强。

这是与皮层/海马方向相反的现象：皮层突触在睡眠中 GluA1 下降，而这些脑干 GABA 神经元的 GluA1 却升高，并在此后驱动更多的恢复性 NREM 睡眠产生。这提示 AMPA 受体的上调，在这个回路里不是"睡眠的产物"，而是"产生睡眠的动力"——脑干的睡眠压力计通过 AMPA 受体上调来编码积累的清醒时长，并将其转化为驱动恢复睡眠的电信号。

这一发现说明，AMPA 受体在睡眠调控中的角色远比"被削减的突触权重"复杂——它们同时参与感知睡眠需求（脑干层面）和执行睡眠效果（皮层层面），方向相反但互为补充。

---

## 比喻：图书馆的夜班编辑

想象一座巨型图书馆，白天读者在成千上万本书上贴了黄色便利贴（清醒期增强的突触），到了夜晚，图书馆关闭，夜班编辑上岗。

编辑手持的第一个工具是 **Homer1a**——一把万能键，可以解锁任何便利贴持有装置。只要值班主任（去甲肾上腺素）不在场、疲劳积累的信号（腺苷）足够强，Homer1a 就开始走动，把书架上的便利贴容纳槽逐一解锁，让便利贴自然脱落。

第二个工具是 **Arc**——一个有辨识力的助理。Arc 只走向书页空白干净（突触安静）的地方，将脱落的便利贴收进废纸篓（内吞）。但凡是被醒目红笔（pCaMKIIβ）圈注过的书页，Arc 视而不见，默默绕开。

与此同时，纺锤波就像图书馆里安装的**聚光灯**，每隔几秒扫过一次，打亮那些已有红圈批注的重要页面，并在上面再贴一张金色便利贴（选择性 GluA1 上调），使它在众多减少的黄贴中愈发醒目。

**这个比喻的有效之处**：准确描述了 Homer1a/Arc 的协同机制（全局削减）、Arc 的逆向标记（保护已印迹突触）和睡眠纺锤波（对重要突触的选择性增强）的分工。

**这个比喻的失效之处**：图书馆编辑可以阅读内容，知道哪本书更重要。而 Arc 是纯粹机械地识别 pCaMKIIβ 的磷酸化状态——它对"重要性"本身完全无感，只感知最近的分子印记。这种"盲目的"分子机制能否真正分辨学习价值与随机激活，仍是开放问题。

---

## 它如何改变我们对大脑的理解

这些发现从两个方向重新定义了我们对睡眠和记忆的理解。

**第一，睡眠不是记忆的敌人，而是记忆的精炼师**。Homer1a 和 Arc 的选择性机制，在技术层面解释了一个长期难以直觉理解的现象：睡眠越充分，记忆越清晰。机制是：充分的睡眠让 Homer1a/Arc 有足够时间削减背景突触，同时纺锤波强化了印迹突触。净效果是更高的信噪比。睡眠不足（如 SD 组 GluA1 高 43.8%）意味着背景没有被削减，印迹在噪音中相对模糊。

**第二，觉醒-睡眠循环实际上是一个分子"写-整合"循环**。清醒期，NA 高企，Homer1a 被排斥在 PSD 之外，突触可以自由响应体验并通过 LTP 增强（GluA1 Ser831 磷酸化、受体插入）。入睡后，NA 撤退，腺苷上位，Homer1a 进场，Arc 赶到，突触进行整合性删减，为明天的新体验腾出空间。这是一个精妙的两相设计：如果没有"写"相，大脑无法学习；如果没有"整合"相，突触会饱和（SHY 所预测的），学习效率崩溃。

**第三，这个机制与经典的突触稳态缩放（synaptic scaling）是不同的路径**。经典突触缩放（Turrigiano 1998）使用 GluA2 通路，在数小时到数天的时间尺度上以乘法性方式调节所有突触。睡眠依赖的突触削减则通过 GluA1 和 Homer1a/Arc，在数小时内完成，且具有突触特异性（Arc 的逆向标记机制）。两者是两套独立的稳态机制，在不同时间尺度和不同精度上共同维护突触权重的可用区间。

---

## 争议与未解问题

**争议一：选择性能否真正保护记忆印迹？**

Arc 的逆向标记机制在概念上很美，但仍主要来自体外和急性实验。pCaMKIIβ 的印记在 LTP 后维持多久？如果标记在睡眠数小时内消退，"印迹保护"窗口会变得非常有限（**Q-homer1a-01**）。

**争议二：CDK5 通路**

Liu 2024 提到，AMPA 受体内吞的另一候选通路是 **CDK5**（cyclin-dependent kinase 5）和 **Homer1a** 协同，以及 CDK5 对 GluA1 Ser845 的间接去磷酸化。CDK5 如何与 Homer1a/Arc 协调尚不清楚（**Q-homer1a-02**）。

**争议三：脑区特异性**

Squarcio 2024 在皮层，Liu 2024 在下丘脑。这两个区域的削减时序和分子节律是否完全同步？海马（记忆最关键的区域）是否有相同的时间曲线？海马 CA1 的睡眠相关 GluA1 变化数据目前仍不完整（**Q-homer1a-03**）。

**争议四：老年大脑中的失调**

老年小鼠的 p-GluA1(845) 在睡眠剥夺后反应更强烈（87.9% vs 78.9%），且恢复效率可能降低。结合 SCN 在衰老中的萎缩（NA 节律降低），老年大脑中 Homer1a 削减机制是否失调，可能是理解衰老相关记忆障碍的新切入点（**Q-homer1a-04**）。

---

## 与 AI 的对照

这让我想到了神经网络中的**权重正则化**（weight regularization）。L2 正则化在训练中向所有权重施加一个朝向零的力，防止任何权重过度增长——这类似于 Homer1a/Arc 的全局削减。Dropout 随机屏蔽部分神经元，间接使某些权重在训练中被"遗忘"——这有某种影子似的类比。

然而，生物睡眠的 AMPA 受体机制远比这些正则化手段精妙：

1. **L2 正则化是全局等比的**，无法识别"印迹权重"并绕开它们。弧的逆向标记做到了。
2. **Dropout 是随机的**，没有与学习历史相关的结构性偏好。Arc 对 pCaMKIIβ 的敏感是确定性的分子识别。
3. **AI 的权重正则化发生在前向/反向传播中（"清醒"时）**，不存在专门的"睡眠"整合阶段。AI 没有两相设计。

有意思的是，研究人员正在探索能否给深度网络引入"睡眠阶段"——定期停止学习、运行权重重整——来改善灾难性遗忘（catastrophic forgetting）。这与 SHY 在概念上高度类似，尽管分子机制完全不同。这也许是大脑启发 AI 的下一个真实贡献。

---

## 今日概念卡片

**Homer1a**
- 类型：即早基因产物（短型 Homer1 变体），突触后致密区支架蛋白的显性负效应物
- 功能：清醒时（高 NA）被排斥在 PSD 之外；睡眠时（低 NA + 高腺苷）进入 PSD，瓦解 mGluR1/5-IP3R 复合物，导致 AMPA 受体脱落
- 关键调控：腺苷 A1R（促进）/ 去甲肾上腺素 α/β-AR（抑制）

**Arc 的逆向突触标记**
- 类型：基于磷酸化状态的分子识别机制
- 功能：Arc 优先结合去磷酸化 CaMKIIβ（安静突触），招募 dynamin/endophilin 内吞 AMPA 受体；自动跳过 pCaMKIIβ（印迹突触）
- 意义：解释了睡眠削减突触为何不删除新鲜记忆

**GluA1 Ser845 磷酸化**
- 类型：分子状态标记
- 功能：PKA 磷酸化→增加表面 GluA1（清醒态）；去磷酸化（NA 降低→cAMP 降低）→受体横向扩散→内吞候选
- 量化：睡眠剥夺使 p-GluA1(845) 升高 78.9%；恢复睡眠使其归位（Squarcio 2024）

---

## 今日认知地图更新

今天的内容在知识库的"突触可塑性 ↔ 睡眠"区域建立了一个重要的分子级别桥梁：

- `homer1a` → 新页面，连接 `arc-arg31`、`ampa-receptor`、`adenosine`、`norepinephrine-locus-coeruleus`、`synaptic-scaling`
- `arc-arg31` → 修订，新增睡眠功能（逆向标记 + Suzuki 2020）
- `ampa-receptor` → 修订，新增睡眠依赖的 GluA1 Ser845 通路
- 今日新发现的张力：睡眠削减使用 **GluA1** 通路，而经典突触缩放使用 **GluA2** 通路——这两者是否真正独立，尚待进一步明确

---

## 参考来源

| # | 来源 | PMID / PMC | 状态 | 用途 |
|---|------|-----------|------|------|
| 1 | Squarcio F, Tononi G, Cirelli C. "Effects of non-rapid eye movement sleep on the cortical synaptic expression of GluA1-containing AMPA receptors." *Eur J Neurosci.* 2024 | PMID:38973508 / PMC11895523 | **开放全文** | 皮层 GluA1 量化；Ser845 数据；REM vs NREM 分解 |
| 2 | Liu J et al. "Slow-wave sleep drives sleep-dependent renormalization of synaptic AMPA receptor levels in the hypothalamus." *PLoS Biol.* 2024 | PMID:39163472 / PMC11364421 | **开放全文** | 下丘脑 GluA1；睡眠纺锤波的保护性正相关 |
| 3 | Diering GH, Nirujogi RS, Roth RH, Worley PF, Pandey A, Huganir RL. "Homer1a drives homeostatic scaling-down of excitatory synapses during sleep." *Science.* 2017 | PMID:28154077 / PMC5382711 | **开放全文** | Homer1a 机制核心；NA/腺苷门控；mGluR5-IP3R |
| 4 | Diering GH. "Remembering and forgetting in sleep: Selective synaptic plasticity during sleep driven by scaling factors Homer1a and Arc." *Neurobiol Stress.* 2022 | PMID:36632309 / PMC9826981 | **开放全文** | Arc 逆向标记机制；pCaMKIIβ 选择性；与 Homer1a 协同 |
| 5 | Suzuki A, Yanagisawa M, Greene RW. "Loss of Arc attenuates the behavioral and molecular responses for sleep homeostasis in mice." *PNAS.* 2020 | PMID:32350140 / PMC7229651 | **开放全文** | Arc KO 睡眠反弹减弱；Arc 2.5x 上调；核 Arc GluA1 mRNA 抑制 |
| 6 | Ba W, Harding EC, Nollet M, Tossell K et al. "Wake-active brainstem GABA neurons signal sleep pressure by upregulating AMPA receptors to drive recovery sleep." *Curr Biol.* 2026 | PMID:42161267 | 摘要（全文未确认） | 脑干 GABA 神经元 GluA1 上调驱动恢复睡眠 |
| 7 | Tononi G, Cirelli C. "Sleep and the price of plasticity: from synaptic and cellular homeostasis to memory consolidation and integration." *Neuron.* 2014 | PMID:24411729 / PMC3921176 | **开放全文** | SHY 框架综述；突触权重归一化功能 |
| 8 | Tononi G, Cirelli C. "Sleep function and synaptic homeostasis." *Sleep Med Rev.* 2006 | PMID:16376591 | 摘要 | SHY 原始假说 |
| 9 | Martin SC, Monroe SK, Diering GH. "Homer1a and mGluR1/5 Signaling in Homeostatic Sleep Drive and Output." *Yale J Biol Med.* 2019 | PMID:30923476 / PMC6430175 | **开放全文** | Homer1a-mGluR 信号切换机制 |
| 10 | Lee SH et al. "Clathrin adaptor AP2 and NSF interact with overlapping sites of GluR2 and play distinct roles in AMPA receptor trafficking and hippocampal LTD." *Neuron.* 2002 | PMID:12441055 | 摘要 | AMPA 受体内吞基础：GluR2-AP2 互作是网格蛋白内吞的经典机制 |

**开放全文数**：7/10（≥2 要求满足；≥1 官方来源通过 PMC 满足）

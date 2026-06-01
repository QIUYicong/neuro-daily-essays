# 神经科学 Wiki 知识库 · 总地图

> 这是语义层的人读地图。每个条目链接到一个**活的**主题页（会随时间被修订加深）。
> 机读版见 `_graph.json`；每日变更见 `CHANGELOG.md`；设计原理见仓库根 `KNOWLEDGE-BASE-DESIGN.md`。
>
> 成熟度图例：🟢 established · 🔵 mainstream · 🟡 emerging · ⚪ speculative · 🔴 contested
>
> 最后更新：2026-06-23（第59篇·小脑的秘密·运动预测与多层可塑性）· 主题页总数：103（新建3页：cerebellum, cerebellar-ltd, forward-model；修订3页：ltd rev2, predictive-coding rev5, motor-cortex rev2）

---

## neurons（神经元）

- 🟢 [动作电位](neurons/action-potential.md) — 神经系统的基本信息单位，全或无脉冲（修订3次）
- 🟢 [轴突始段 (AIS)](neurons/axon-initial-segment.md) — 动作电位的诞生地与神经元决策中枢
- 🟢 [电压门控钠通道](neurons/voltage-gated-sodium-channel.md) — 动作电位上升相的分子引擎
- 🟢 [突触传递](neurons/synaptic-transmission.md) — 神经元间化学信号转化的核心机制，含突触后受体（修订2次）
- 🟢 [突触结合蛋白 Synaptotagmin](neurons/synaptotagmin.md) — 突触囊泡上的钙传感器，触发融合的分子开关（修订3次）
- 🟢 [就绪释放池（RRP）](neurons/readily-releasable-pool.md) — 突触活动区中处于停靠就绪状态的囊泡子集；RRP耗竭是短时程抑制的主要机制 **[NEW 2026-06-10]**
- 🟢 [活动区（Active Zone）](neurons/active-zone.md) — 突触前终末的纳米级分子发射台
- 🟢 [CaMKII（钙/钙调素依赖性蛋白激酶 II）](neurons/camkii.md) — LTP 诱导和维持的核心激酶，"分子记忆开关"
- 🟢 [树突计算](neurons/dendritic-computation.md) — NMDA 棘波与 Ca²⁺ 棘波使单根树突成为独立计算单元，单神经元等价两层神经网络；Wilson 2016证明V1突触聚类增强方向选择性（修订4次）
- 🟢 [锥体神经元](neurons/pyramidal-neuron.md) — 皮层主体兴奋性神经元，双树突系统是树突计算和前馈/反馈整合的物理基础
- 🟢 [场所细胞](neurons/place-cell.md) — 海马 CA1/CA3 的空间位置编码器，通过 BTSP 单次写入场所场，构成大脑认知地图 **[NEW]**
- 🟢 [海马回路](neurons/hippocampal-circuit.md) — DG（模式分离）→ CA3（模式补全）→ CA1（整合输出）的三突触回路与并行穿孔通路；AD最早受损的回路（修订6次）
- 🟢 [网格细胞](neurons/grid-cell.md) — 内侧内嗅皮层的六角网格空间编码器，为场所细胞提供坐标框架 **[NEW]**
- 🟢 [电压门控钙通道（VGCCs）](neurons/voltage-gated-calcium-channels.md) — P/Q型在突触前纳米域触发递质释放；L型在树突驱动BTSP平台电位，在核激活基因表达；三亚家族、三地点、三时间尺度 **[NEW 2026-06-01]**

## circuits（回路）

- 🔵 [吊灯细胞](circuits/chandelier-cell.md) — 特异靶向 AIS 的抑制性中间神经元（修订2次）
- 🟢 [基底节](circuits/basal-ganglia.md) — 纹状体/GPi/GPe/STN/SNc构成的运动选择回路；直接通路（D1/促进运动）与间接通路（D2/抑制运动）由多巴胺精确平衡；振荡状态决定运动是否被"允许" **[NEW 2026-06-14]**
- 🟢 [丘脑-皮层回路](circuits/thalamocortical-circuit.md) — TRN（CaV3.3 T型）↔TC（CaV3.1）振荡环路是睡眠纺锤波起搏器；Core/Matrix双通路；CT反馈在清醒/睡眠切换中起关键作用 **[NEW 2026-06-19]**
- 🟢 [PV+ 中间神经元](circuits/pv-interneurons.md) — 快速放电篮状/吊灯细胞，控制 gamma 振荡与精确输出时序 **[NEW 2026-06-03]**
- 🟢 [SST+ 中间神经元](circuits/sst-interneurons.md) — Martinotti 细胞靶向远端树突，O-LM 细胞 theta 期门控 EC 输入 **[NEW 2026-06-03]**
- 🟢 [VIP+ 中间神经元](circuits/vip-interneurons.md) — CGE 来源的去抑制专家，被行为显著信号激活 **[NEW 2026-06-03]**
- 🟢 [去抑制回路](circuits/disinhibitory-circuit.md) — VIP→SST/PV→锥体细胞的三级去抑制架构，学习与注意调制的皮层通用模块 **[NEW 2026-06-03]**

## concepts（概念/框架）

- 🟢 [Hodgkin-Huxley 模型](concepts/hodgkin-huxley-model.md) — 动作电位的定量数学框架
- 🟢 [SNARE复合体](concepts/SNARE-complex.md) — 突触囊泡融合的核心分子机器（四螺旋束拉链）
- 🟢 [NMDA 受体](concepts/nmda-receptor.md) — 突触巧合检测器 + 树突 NMDA 棘波 + PFC 吸引子时间积分器 + AD中突触外NR2B逆转LTP（修订4次）
- 🟢 [长时程增强（LTP）](concepts/ltp.md) — 突触可塑性与学习记忆的分子基础；Aβ寡聚体通过五条通路单向阻断LTP（修订6次）
- 🟢 [Hebbian 学习](concepts/hebbian-learning.md) — "共同激发的神经元连接在一起"，NMDA 受体实现其分子逻辑
- 🟢 [AMPA 受体](concepts/ampa-receptor.md) — 快速突触传递的执行者，LTP 权重变化的物理载体
- 🟢 [行为时间尺度突触可塑性（BTSP）](concepts/btsp.md) — 秒级时间窗口的突触增强规则，单次写入场所场，与 LTP 并列的独立学习法则
- 🟢 [θ振荡](concepts/theta-oscillations.md) — 海马4–12 Hz探索节律；提供相位编码时间框架；θ序列压缩路径；θ/γ嵌套承载5-9项目序列；REM期LA-VH θ同步驱动情绪记忆巩固（Boyce 2016, Totty 2017）**[修订 2026-06-22]**
- 🟢 [尖波涟漪（SWR）](concepts/sharp-wave-ripples.md) — CA3→CA1高频群体事件；20倍速序列重播；记忆固化的离线物理载体；大振幅亚集专门驱动海马-PFC同步再激活（Robinson 2026）；清醒SWR是记忆标记机制（Yang 2024）；SWR嵌套在纺锤波内（SO-spindle-SWR三重奏）**[修订 2026-06-22]**
- 🟢 [场所细胞](concepts/place-cells.md) — 海马CA1/CA3位置特异放电神经元；稀疏编码（1–5%激活）；重映射（不同环境正交表征）；θ相位前移实现双重位置编码；SWR期间序列以20倍速重播；是认知地图基本编码单元 **[NEW 2026-06-22]**（填补长期悬空引用）
- 🟢 [网格细胞](concepts/grid-cells.md) — 内侧内嗅皮层MEC以六边形格点激活的神经元；三参数（间距/方向/相位）完全描述；4–7离散模块比√2；背腹向间距梯度（20cm–1.5m）；路径整合的坐标输出；活跃于心理模拟和概念空间（Qu 2026 Cell：发育成熟预测流体智力）**[NEW 2026-06-22]**（填补长期悬空引用）
- 🟢 [路径整合](concepts/path-integration.md) — 通过持续积累速度矢量估计当前位置；不依赖外部地标；联合细胞（位置+方向+速度）实现；随时间漂移需地标锚定；是黑暗导航的神经机制 **[NEW 2026-06-22]**
- 🟢 [θ相位前移](concepts/theta-phase-precession.md) — 场所细胞放电相位随穿越场所场系统性提前约100–355°；产生θ序列（125ms内压缩数秒路径）；为STDP提供时间压缩框架；O'Keefe & Recce 1993经典发现；CAN vs OI两机制模型仍未决 **[NEW 2026-06-22]**（填补theta-oscillations页面的phase-precession悬空引用）
- 🔵 [认知地图](concepts/cognitive-map.md) — 海马-EC构建的空间（及概念）关系内部模型；从Tolman 1948捷径行为到场所/网格双系统；扩展至时间序列（情节记忆）、心理模拟（Bellmund 2016）、概念空间（Viganò 2023）；发育研究证据（Qu 2026）**[NEW 2026-06-22]**
- 🟢 [睡眠纺锤波](concepts/sleep-spindles.md) — TRN CaV3.3→TRN↔TC振荡→12–15 Hz梭形波；皮层树突L型Ca²⁺预热窗口；SO-spindle-SWR三重奏中间层；CACNA1I变异→精神分裂症纺锤波缺陷；三重耦合因果实验（Latchoumane 2017）**[NEW 2026-06-19]**
- 🟢 [皮层慢振荡（SO）](concepts/cortical-slow-oscillation.md) — NREM 深睡眠~0.75 Hz UP/DOWN态交替；起源PFC向后传播；SO上行相是纺锤波和SWR的最高时间框架；三重奏顶层 **[NEW 2026-06-19]**
- 🟢 [相位前进](concepts/phase-precession.md) — 场所细胞在θ周期中放电相位随位置移动；速率+相位双重编码；O'Keefe & Recce 1993经典发现
- 🟡 [嵌套时间编码层级](concepts/temporal-coding-hierarchy.md) — 大脑记忆系统在 μs 到年的时间谱上，以嵌套方式在每层通过巧合检测修改突触权重；Hebb 原理的多时间尺度实例化（第一周综合分析框架）
- 🟢 [印迹细胞](concepts/engram-cells.md) — 学习时被激活并持久改变的神经元集合；光遗传学证明激活印迹细胞足以重现记忆；沉默印迹证明遗忘可以是提取障碍而非信息消失（修订2次）
- 🟢 [记忆巩固（系统层面）](concepts/memory-consolidation.md) — SWR驱动的海马→皮层记忆转移；SO-spindle-SWR三重奏；SCT vs MTT理论争论；互补学习系统模型；NREM/SWR负责信息内容，REM/θ负责情感维度（SFSR假说，Q-rem-sleep-role部分解答）**[修订 2026-05-31]**
- 🟢 [长时程抑制（LTD）](concepts/ltd.md) — NMDA-LTD（PP2B/PP1/GluA1去磷酸化）与 mGluR-LTD（Arc/AMPAR内吞）构成双向突触可塑性；LTD 是主动的精准遗忘机制；**小脑 LTD（mGluR1/PKC路径，与 NMDA-LTD 并列，修订2026-06-23）** **[修订rev2]**
- 🟢 [小脑 LTD（PF-PC LTD）](concepts/cerebellar-ltd.md) — mGluR1→IP₃→PKC→AMPAR内吞；与海马 NMDA-LTD 共用最终效应器但触发机制根本不同；Schonewille 2011 证明无 LTD 也能运动学习；Hansel 2026 预印本 400ms 时间窗口 **[NEW 2026-06-23]**
- 🟢 [钙调磷酸酶（Calcineurin / PP2B）](concepts/calcineurin.md) — 高亲和力 Ca²⁺ 磷酸酶，中低 Ca²⁺ 时激活，是 NMDA-LTD 磷酸酶级联的第一步；与 CaMKII 构成 LTP/LTD 方向性的分子开关 **[NEW 2026-06-04]**
- 🟢 [Arc/Arg3.1（活动调控的细胞骨架相关蛋白）](concepts/arc-arg31.md) — 突触活动量规器：mGluR-LTD 的执行蛋白（dynamin/endophilin 内吞）；同时参与 L-LTP 巩固（肌动蛋白稳定）；突触稳态的分子感受器 **[NEW 2026-06-04]**
- 🟢 [工作记忆](concepts/working-memory.md) — 容量~4项的临时信息维持系统；γ爆发（活动性编码）+ STP突触易化（静默储存）双机制；依赖dlPFC吸引子回路、PV-γ轴和多巴胺D1调节 **[NEW 2026-06-05]**
- 🟢 [持续活动（延迟期放电）](concepts/persistent-activity.md) — PFC 延迟期的神经活动模式；实为间歇性 γ 爆发而非连续高频放电；依赖 NMDA 慢衰减和循环兴奋吸引子网络 **[NEW 2026-06-05]**
- 🟢 [γ振荡（30–80 Hz）](concepts/gamma-oscillations.md) — PV+篮状细胞兴奋-抑制循环产生；工作记忆中以~67ms爆发形式间歇出现；精神分裂症中功率减弱与PV损伤相关 **[NEW 2026-06-05]**
- 🔵 [意识点燃](concepts/consciousness-ignition.md) — 全有全无的非线性临界翻转；~270-300ms 前额顶叶激活；注意双要求机制；P3b EEG标志（地位存疑）；GWT核心机制节点 **[修订 2026-05-31]**
- 🔵 [注意瞬盲](concepts/attentional-blink.md) — GWT 最直接的有/无意识分叉检验；RSVP T1 后 200–500ms 内 T2 感知抑制；感觉处理相同条件下 ~270ms 前额顶叶神经分叉（Sergent 2005）；填补 COGITATE 遗留的方法论缺口 **[NEW 2026-05-31]**
- 🟡 [世界模型](concepts/world-model.md) — 大脑对外部世界和自身状态维护的当前最佳贝叶斯估计；八层分层贝叶斯预测机器架构；五月月报整合后修订 **[修订 2026-05-31]**
- 🔵 [时间层级编码](concepts/temporal-hierarchy.md) — 大脑在从纳秒到终身的12个数量级时间尺度上并行运行的计算机制全谱；从SNARE融合到威胁记忆的多层架构 **[NEW 2026-05-31]**
- 🟡 [嵌套竞争-遴选架构](concepts/competition-selection-principle.md) — 大脑在突触→细胞→回路→系统→认知五个层次通过竞争决定"什么值得记住"；与嵌套时间编码层级互补；第二周综合分析框架 **[NEW 2026-06-06]**
- 🟢 [多巴胺奖励预测误差（DA-RPE）](concepts/dopamine-reward-prediction-error.md) — VTA/SNc DA 神经元编码"实际 − 预期"奖励误差；TD学习的神经底物；D1/D2分化；三因素规则的广播信号 **[NEW 2026-06-07]**
- 🔵 [三因素学习规则](concepts/three-factor-learning-rule.md) — Δw = (pre × post) × M；多巴胺/ACh/NE 作为第三因素；填补 hebbian-learning 悬空引用；纹状体直接实验验证 **[NEW 2026-06-07]**
- 🔵 [突触标记与捕获（STC）](concepts/synaptic-tagging-capture.md) — Hebbian 标签（~1-2h）+ DA-PRP 捕获 → E-LTP 升级为 L-LTP；解决三因素规则的时间延迟难题 **[NEW 2026-06-07]**

- 🟢 [Aβ寡聚体](concepts/amyloid-beta-oligomers.md) — AD的核心毒性物种；通过PrPC/NR2B/calcineurin/BDNF/tau五路并行瓦解海马LTP机器 **[NEW 2026-06-08]**
- 🟢 [短时程突触可塑性（STP）](concepts/short-term-synaptic-plasticity.md) — 毫秒至分钟尺度内突触效率的使用依赖性动态变化；Syt7驱动易化（高p→低通）、RRP耗竭驱动抑制（低p→高通）；是工作记忆活动无声储存的分子基础 **[NEW 2026-06-10]**
- 🟢 [方向选择性](concepts/orientation-selectivity.md) — V1将LGN非定向圆对称输入转化为精确方向响应的核心计算；前馈LGN排列+E/I平衡+树突NMDA棘波三层机制；有/无方向柱物种均可达同等锐利选择性 **[NEW 2026-06-11]**
- 🟡 [突触聚类](concepts/synaptic-clustering.md) — 功能相似突触在同一树突分支聚集→NMDA棘波超线性整合→局部"与门"计算；Wilson 2016在雪貂V1提供首个体内直接证据；普遍性待验证 **[NEW 2026-06-11]**（填补 dendritic-computation 悬空引用）
- 🟢 [乙酰胆碱皮层调质](concepts/acetylcholine-cortex.md) — 基底前脑胆碱能系统通过M1/M2/nAChR受体增大皮层信噪比；肌碱受体介导V1注意调制（Herrero 2008）；相位性/紧张性双时间尺度；支持皮层去同步和工作记忆持续放电 **[NEW 2026-06-12]**
- 🟢 [皮层增益控制](concepts/gain-control.md) — 神经调质系统的核心输出：乘法性缩放皮层神经元输入-输出曲线；ACh通过M1、NE通过α2A/α1实现；注意调制的分子机制（修订2次）**[NEW 2026-06-12]**
- 🟡 [多层增益控制架构](concepts/multi-timescale-plasticity.md) — STP（毫秒–秒层一）+ ACh/NE增益控制（秒–分钟层二）+ DA-RPE（分钟–小时层三）三层嵌套；Marder原则：调质环境决定功能回路；第三周综合框架 **[NEW 2026-05-30]**
- 🟢 [去甲肾上腺素与蓝斑系统](concepts/norepinephrine-locus-coeruleus.md) — 蓝斑LC通过相位性/紧张性双模式和倒U形NE浓度曲线优化皮层认知增益；α2A稳定PFC工作记忆；β受体促进情绪记忆LTP；Aston-Jones & Cohen 2005适应性增益理论 **[NEW 2026-06-12]**
- 🔵 [5-HT自受体与SSRI延迟起效](concepts/5-ht-autoreceptor.md) — 5-HT1A树突自受体负反馈在急性期抵消SSRI效果；14天后自受体脱敏解除制动；皮质5-HT1A/2A功能拮抗；pindolol加速起效的临床证据 **[NEW 2026-06-13]**
- 🔴 [海马神经发生](concepts/hippocampal-neurogenesis.md) — 啮齿类SGZ持续神经发生（证据充分）；阻断神经发生消除SSRI行为效果；人类成人神经发生规模和存在性争议（Sorrells vs Boldrini 2018对立数据）**[NEW 2026-06-13 · 争议]**
- 🔵 [β振荡（基底节-皮层）](concepts/beta-oscillations.md) — 13-30 Hz同步振荡；PD中病理性增强构成"抗运动"回路状态；DA和DBS均通过β→θ切换改善运动（Köhler 2024 n=25）；与γ振荡（促运动执行）功能对立 **[NEW 2026-06-14]**
- 🟢 [恐惧条件反射](concepts/fear-conditioning.md) — 外侧杏仁核（LA）CS+US汇聚→NMDA巧合检测→CaMKII→AMPA插入→LA-LTP；与海马LTP分子机器完全同构；约20%LA神经元形成稀疏恐惧印迹；光遗传双向因果证明（Nabavi 2014）**[NEW 2026-05-30]**
- 🟢 [恐惧消退](concepts/fear-extinction.md) — 消退≠遗忘，而是IL皮层→腹侧ITC→CeM新抑制回路；与原始恐惧记忆竞争性共存；vmPFC激活预测消退回忆质量；PTSD=消退记忆提取失败；LA-VH θ相位差（~180°）预测消退记忆质量（Totty 2017，R=0.954）**[修订 2026-05-31]**
- 🟢 [REM睡眠](concepts/rem-sleep.md) — 去甲肾上腺素真空（LC沉默）+θ振荡+杏仁核-海马θ同步；情绪记忆去饱和化（SFSR假说）；Boyce 2016光遗传因果证明REM θ是情境记忆必需条件；van der Helm 2011人类fMRI证实REM降低杏仁核情绪反应 **[NEW 2026-05-31]**
- 🟡 [情绪记忆去饱和化](concepts/emotional-memory-depotentiation.md) — REM睡眠NE真空→θ相位驱动LA突触选择性LTD→情绪色彩弱化、事实内容保留；Walker SFSR假说的机制底层；PTSD可能是去饱和化失败 **[NEW 2026-05-31]**
- 🔴 [Φ（整合信息度量）](concepts/phi-measure.md) — IIT 核心量；衡量系统最优分割时损失的因果信息量；NP-hard 计算；IIT 声称 Φ = 意识的量；COGITATE 2025 对相关机制预测构成挑战 **[NEW 2026-05-31]**
- 🔵 [后方皮层热区](concepts/posterior-cortical-hot-zone.md) — IIT 的解剖核心预测；V1/V4/MT/下颞叶等视觉-感觉联合皮层通过高整合连接产生意识内容；COGITATE 2025 对后方皮层内部同步（机制核心）构成挑战 **[NEW 2026-05-31]**
- 🔵 [回路主题](concepts/circuit-motifs.md) — 神经回路中反复出现的小型拓扑模式（前馈回路、反馈循环、富人俱乐部），可能反映神经计算的基本功能需求；Drosophila连接组（Lin 2024）提供最大规模系统验证；蘑菇体15个学习隔室是典型实例 **[NEW 2026-06-18]**

## motor（运动系统）

- 🟢 [运动皮层](systems/motor-cortex.md) — M1/PMC/SMA分层组织；Betz细胞→皮质脊髓束；均质小人（手/嘴比例扭曲）；群体向量编码（Georgopoulos 1986）；旋转动力学（Churchland 2012）；输出零空间（Kaufman 2014）；**小脑-运动皮层闭环（修订2026-06-23）**
- 🟢 [小脑](systems/cerebellum.md) — 多样化预测处理器；三层皮层（颗粒/浦肯野/分子）+ DCN；PF-LTD多层可塑性；前向/逆向内部模型（Wolpert 1998）；双向微区（De Zeeuw 2021）；CCAS（认知情感综合征，Schmahmann 1998）**[NEW 2026-06-23]**
- 🔵 [前向模型](concepts/forward-model.md) — 利用传出拷贝预测运动感觉后果，使大脑超越反馈延迟；小脑的主要计算角色；逆向模型对称结构 **[NEW 2026-06-23]**
- 🟡 [群体向量编码](concepts/population-vector-coding.md) — M1方向编码的分布式机制；余弦调谐→群体向量精确预测；心理旋转时群体向量以732°/s旋转（Georgopoulos 1989）**[NEW 2026-06-21]**
- 🟡 [旋转动力学（运动皮层）](concepts/rotational-dynamics-motor.md) — 执行期神经群体以2–2.8 Hz在状态空间旋转；动力学引擎而非参数地图；RNN训练后自发出现相同结构 **[NEW 2026-06-21]**
- 🟡 [输出零空间](concepts/output-null-space.md) — 准备活动集中在对肌肉无效的零空间子空间（调谐比4.5×）；几何机制解释准备不触发运动 **[NEW 2026-06-21]**
- 🟡 [镜像神经元](circuits/mirror-neurons.md) — F5区17%神经元在执行+观察同一有目标动作时均激活（Gallese/Rizzolatti 1996）；F5/BA44同源；语言演化的动作理解假说 **[NEW 2026-06-21]**

## language（语言）

- 🟢 [语言网络（双流模型）](systems/language-network.md) — 腹侧流（声音→意义，双侧）+ 背侧流（声音→动作/句法，左侧主导）；超模态（手语激活同一Broca区）；主动预测性；镜像神经元补充 **[修订 2026-06-21]**
- 🟢 [Broca区（额叶下回）](systems/broca-area.md) — BA44（层级句法Merge，背侧流）vs BA45（语义工作记忆，腹侧流）内部分工；不是统一的"语言产出区" **[NEW 2026-06-20]**
- 🟢 [弓状束](concepts/arcuate-fasciculus.md) — 背侧流主干白质通路；左侧优势；出生时低髓鞘化→随句法习得成熟；损伤→传导性失语 **[NEW 2026-06-20]**
- 🟢 [背侧语言流](circuits/dorsal-language-stream.md) — A1→颞平面→Spt→弓状束→BA44；音韵缓冲+句法层级运算；左侧主导 **[NEW 2026-06-20]**
- 🟢 [腹侧语言流](circuits/ventral-language-stream.md) — A1→MTG/STS→角回→BA45；声音→词义；双侧；具身语义（工具→运动皮层，动物→视觉皮层） **[NEW 2026-06-20]**

## systems（系统）

- 🟢 [内嗅皮层（EC）](systems/entorhinal-cortex.md) — MEC（网格细胞/联合细胞）+ LEC（情境感觉）构成海马主要输入门户；MEC Layer II是路径整合坐标输出层；Braak分期：EC Layer II是AD最早受损皮层区域；空间记忆障碍先于语言退化的神经解剖基础 **[NEW 2026-06-22]**
- 🟢 [杏仁核](systems/amygdala.md) — 外侧核（LA）通过LTP写入恐惧记忆；ITC细胞是恐惧/消退的分子闸门；基底核（BA）中恐惧神经元与消退神经元双群竞争；中央核（CeA）驱动防御行为输出；与PFC（IL/PL）和海马形成情绪调控三角回路 **[NEW 2026-05-30]**
- 🟢 [前额叶皮层（PFC）](systems/prefrontal-cortex.md) — dlPFC 第2/3/5层循环回路是工作记忆的关键脑区；PV-γ轴是认知控制的时序基础 **[NEW 2026-06-05]**
- 🟢 [初级视觉皮层（V1）](systems/v1-primary-visual-cortex.md) — 视觉信息皮层第一站；方向选择性从LGN非定向输入的从头计算；猫/猴方向柱 vs 小鼠盐-胡椒型组织均可达精确方向选择性；树突突触聚类增益层（Wilson 2016）；ACh通过肌碱受体放大V1注意调制（Herrero 2008）（修订2次）
- 🟢 [神经调质系统](systems/neuromodulator-systems.md) — 基底前脑ACh、蓝斑NE、中脑DA、中缝核5-HT四套弥散调质系统的总概述；编码"用什么模式处理信息"而非信息本身；Marder原则定位（修订3次）**[NEW 2026-06-12]**
- 🟢 [血清素-缝际核系统](systems/serotonin-raphe-system.md) — 约20-30万DRN/MRN 5-HT神经元向全脑广播；体积传输为主；14种5-HT受体；5-HT1A自受体的双重负反馈机制是SSRI延迟起效的核心 **[NEW 2026-06-13]**
- 🟢 [默认模式网络（DMN）](systems/default-mode-network.md) — 大脑内部模拟基础设施；Raichle 2001 发现"默认模式"；Fox 2005 DMN-TPN反相关；Andrews-Hanna 2011 双子系统（MTL子系统=情节记忆/场景构建；dMPFC子系统=心智化）；aMPFC+PCC枢纽节点；Buckner 2009 Aβ优先沉积枢纽节点；课程路线8（意识与自我）首篇 **[NEW 2026-06-16]**

## methods（方法）

- 🟢 [光遗传学](methods/optogenetics.md) — ChR2（蓝光激活）+ NpHR/Arch（黄光沉默）+ Cre-lox/c-fos-tTA 遗传特异性递送，提供毫秒精度因果回路解析；印迹细胞/假记忆/效价翻转实验的核心工具 **[NEW 2026-06-09]**
- 🟢 [扰动复杂性指数（PCI）](methods/perturbational-complexity-index.md) — IIT 的临床代理工具；TMS 扰动 + EEG 记录 + Lempel-Ziv 复杂度算法；区分清醒/NREM/麻醉/植物状态/最小意识状态；Casali 2013 奠基，多中心验证 **[NEW 2026-05-31]**
- 🟢 [连接组学](methods/connectomics.md) — 用串行电子显微镜重建生命体所有神经元与突触连接的完整结构图谱；C. elegans（302神经元，White 1986）→ 果蝇（139,255神经元，FlyWire 2024）；揭示网络拓扑（小世界、富人俱乐部、前馈回路）；结构约束功能但不充分描述动力学（结构-功能鸿沟）**[NEW 2026-06-18]**
- 🟡 [对抗性协作](methods/adversarial-collaboration.md) — 让对立理论家预注册具体预测与通过/失败标准，再按标准裁判；COGITATE 2025 是神经科学最大规模实践（256人，fMRI/MEG/iEEG，IIT vs GNWT）；同时挑战两理论核心机制预测 **[NEW 2026-05-31]**

## theories（理论）

- 🔵 [全局工作空间理论（GWT）](theories/global-workspace-theory.md) — 意识点燃机制；Dehaene-Changeux 神经工作空间；有意识知觉的全有全无广播事件；GWT vs IIT 2025 年对抗性合作 **[NEW 2026-05-30]**
- 🟡 [预测编码](theories/predictive-coding.md) — 皮层层级通过自上而下的预测反馈 + 自下而上的预测误差前馈实现贝叶斯推断；Rao & Ballard 1999 奠基模型；Bastos 2012 皮层分层映射（γ=误差前馈，α/β=预测反馈）；Keller 2012 V1感觉运动失配实验；注意=精度加权；与DA-RPE同一计算结构 **[NEW 2026-06-15]**
- 🔴 [整合信息理论（IIT）](theories/integrated-information-theory.md) — 意识 = Φ（整合信息量）；五公理推导物理约束；意识基质在后方皮层热区（而非前额叶）；小脑/视网膜低 Φ 预测与临床一致；COGITATE 2025 挑战核心机制预测（后方皮层同步缺失）；泛心论蕴含；前馈网络 Φ ≈ 0 **[NEW 2026-05-31 · 争议]**
- 🟡 [精度加权](concepts/precision-weighting.md) — 预测误差信号携带精度权重，注意力形式化为选择性提升误差精度；ACh/NE/DA是分子层面的精度调节器；VIP-SST去抑制回路是回路层面的实现候选 **[NEW 2026-06-15]**

## diseases（疾病）

- 🟢 [阿尔茨海默病](diseases/alzheimers-disease.md) — Aβ寡聚体通过5条并行通路瓦解海马突触LTP；突触密度（非斑块）与认知衰退相关r=0.96；早期突触沉默可逆 **[NEW 2026-06-08]**
- 🟢 [帕金森病](diseases/parkinsons-disease.md) — α-突触核蛋白聚集/路易小体/Braak分期；基底节直接/间接通路失衡（GPi过度活跃→丘脑抑制→运动减少）；β振荡病理状态；DA和DBS共享β→θ振荡切换治疗机制（Köhler 2024）**[NEW 2026-06-14]**

---

## 当前知识路线进度

| 课程主题 | 状态 |
|---------|------|
| 1. 神经元如何工作 | 🔵 进行中（已覆盖：AIS, 动作电位, 突触传递, NMDA/AMPA 受体, CaMKII, 树突计算, 锥体神经元, 电压门控钙通道, PV+/SST+/VIP+ 中间神经元, 去抑制回路, **LTD（长时程抑制）**, **短时程突触可塑性（STP）**, **神经调质 ACh/NE（2026-06-12）**, **血清素系统/5-HT1A自受体（2026-06-13）**, **小脑 LTD（2026-06-23）**；待覆盖：多巴胺系统深度） |
| 2. 神经网络微回路设计 | 🔵 进行中（已覆盖：PV+/SST+/VIP+ 中间神经元, 去抑制回路；待覆盖：皮层柱结构, 前馈/反馈抑制, 神经调质调节） |
| 3. 大脑如何编码世界 | 🔵 进行中（已覆盖：**场所细胞（2026-06-22 wiki建立）**, **网格细胞（2026-06-22 wiki建立）**, θ振荡/相位编码, **V1方向选择性（2026-06-11）**, **路径整合（2026-06-22）**, **运动编码-旋转动力学（2026-06-21）**, **小脑前向模型（2026-06-23）**；待覆盖：听觉/体感, 头向细胞, 时间表征）|
| 4. 学习和记忆 | 🔵 进行中（已覆盖：LTP, Hebb 规则, BTSP, 海马回路, 场所场形成, SWR 重播, 印迹细胞, 记忆巩固（系统层面）, **LTD**, **短时程突触可塑性（STP）**, **认知地图（2026-06-22）**；待覆盖：记忆提取机制、网格-场所转化精确机制）|
| 5. 认知控制 | 🔵 进行中（已覆盖：**工作记忆**、**奖励学习/三因素规则（2026-06-07）**、**注意/增益控制（ACh/NE，2026-06-12）**；待覆盖：执行控制、决策）|
| 6. 情绪与动机 | 🔵 进行中（已覆盖：多巴胺奖励系统、VTA/NAc/PFC 投射路线、**杏仁核恐惧记忆回路（2026-05-30）**、**恐惧条件反射/消退机制**；待覆盖：动机回路深度、恐惧情景结合（海马-杏仁核）、PTSD深度、下丘脑情绪调控）|
| 11. 疾病作为窗口 | 🔵 进行中（已覆盖：阿尔茨海默病（AD突触机制）、**帕金森病（基底节回路失衡/β振荡/DBS机制，2026-06-14）**；待覆盖：ASD、精神分裂症、癫痫）|
| 8. 意识与自我 | 🔵 进行中（已覆盖：**默认模式网络（DMN）**（2026-06-16）、**全局工作空间理论 GWT + 意识点燃**（2026-05-30）、**整合信息理论 IIT + Φ + 后方皮层热区 + PCI**（2026-05-31）、**COGITATE预注册对决（2026-05-31）**、**注意瞬盲（2026-05-31，填补 COGITATE 方法论缺口）**；待覆盖：主动推断/自由能原理、自我参照处理、意识的神经相关物精细解析）|
| 10. 方法革命 | 🔵 开始（已覆盖：**光遗传学**；待覆盖：电生理、fMRI、钙成像、单细胞测序、空间转录组）|
| 9. Connectomics | 🔵 开始（已覆盖：**连接组学基础（C. elegans + Drosophila）**；待覆盖：小鼠皮层连接组、人脑功能连接组、Connectomics×AI集成）|
| 2, 7, 12 | ⚪ 待开始 |

**第7篇（2026-05-30）**：**第一周综合**——归纳嵌套时间编码层级（Nested Temporal Coding Hierarchy）框架，连接前 6 篇文章的核心机制，指向第二周方向（印迹细胞、记忆巩固系统、钙通道）。

**第8篇（2026-05-31）**：**印迹细胞**——光遗传学实验证明记忆宿于特定细胞集合；沉默印迹证明遗忘可以是提取障碍；AD 早期记忆缺损可能可逆；填补 4 个页面的高优先级悬空引用。

**第9篇（2026-06-01）**：**电压门控钙通道**——三亚家族（CaV1/CaV2/CaV3）通过亚细胞定位实现三种时间尺度功能；纳米域耦合（10-30 nm）赋予突触前毫秒精度；L型通道驱动BTSP平台电位（73%贡献）和晚期LTP核钙信号；填补6个页面引用的最高优先悬空引用 calcium-channel。

**第11篇（2026-06-03）**：**抑制性中间神经元多样性**——PV+（快速放电，gamma/SWR）/ SST+（Martinotti+O-LM，树突门控）/ VIP+（去抑制专家，行为信号激活）三类分工；VIP→SST/PV→锥体细胞的三级去抑制架构；海马≥21种中间神经元的时空分工；PV+ GAD67下调与精神分裂症连接。新建4个 circuits 页面，修订3个现有页面（chandelier-cell, dendritic-computation, hippocampal-circuit）。

**第12篇（2026-06-04）**：**长时程抑制（LTD）**——NMDA-LTD（低 Ca²⁺→PP2B/PP1→GluA1 去磷酸化→AMPAR 内吞）与 mGluR-LTD（mGluR5→Arc 翻译→dynamin 内吞）的双路径完整机制；PSD-95/AKAP150/calcineurin 复合体的空间定位；脆性 X 综合征（FMRP 缺失→mGluR-LTD 过度激活）；恐惧消退、AD 突触损害、睡眠突触稳态。新建3个 concepts 页面（ltd, calcineurin, arc-arg31），修订 ltp 和 ampa-receptor 两个页面，填补 ltp-ltd 悬空引用。

**第13篇（2026-06-05）**：**前额叶皮层与工作记忆**——工作记忆经典吸引子模型（Goldman-Rakic 1995）vs γ爆发动态代码（Lundqvist 2016）vs 活动无声突触储存（Mongillo 2008）三模型整合；NMDA受体时间积分、多巴胺D1倒U型调节、PV-γ-WM轴；精神分裂症中PV/GAD67下降与γ减弱的因果链；首次进入 systems 层和认知控制主题。新建4个页面（working-memory, persistent-activity, gamma-oscillations, prefrontal-cortex），修订 pv-interneurons 和 nmda-receptor 两个页面。

**第14篇（2026-06-06）**：**第二周综合——竞争法则**——归纳嵌套竞争-遴选架构（Nested Competition-Selection Architecture）框架，整合第二周六篇文章（印迹细胞、VGCC、记忆巩固、抑制性中间神经元、LTD、工作记忆）的统一计算逻辑：大脑在突触/细胞/回路/系统/认知五个层次均以竞争实现稀疏遴选。新建1个页面（competition-selection-principle），修订 engram-cells、memory-consolidation、working-memory 三个页面。

**第15篇（2026-06-07）**：**多巴胺与奖励预测误差——三因素学习规则**——揭示 VTA/SNc 多巴胺神经元如何编码 RPE（实际 − 预期奖励），实现 TD 学习的神经底物；三因素规则（Δw = (pre × post) × DA）如何将 Hebb 规则与行为意义相耦合；突触标记与捕获（STC）如何解决时间延迟；填补 hebbian-learning 的 [[three-factor-learning-rule]] 悬空引用。新建3个页面（dopamine-reward-prediction-error, three-factor-learning-rule, synaptic-tagging-capture），修订 hebbian-learning 和 ltp 两页。

**第16篇（2026-06-08）**：**阿尔茨海默病的突触机制——记忆的分子遗忘**——首次进入 disease 层。揭示AD核心毒性物种是可溶性Aβ寡聚体（非斑块），通过5条并行通路（PrPC/Fyn/NR2B过激活、突触外NR2B/p38/CREB失活、calcineurin/AMPA内吞、BDNF/TrkB截断、tau错位）系统性瓦解海马LTP；突触密度（r=0.96）是认知衰退最强预测因子；早期损伤（棘丢失）在人工实验中可逆；theta振荡-突触可塑性三角联动。新建2个页面（alzheimers-disease, amyloid-beta-oligomers），修订 ltp、nmda-receptor、hippocampal-circuit 三页；解答 Q-nmda-alzheimer 未解问题。

**第17篇（2026-06-09）**：**光遗传学：用一束光解开神经回路的因果之谜**——首次覆盖 methods 层。从莱茵衣藻ChR2奠基论文（Boyden 2005）出发，阐明ChR2（蓝光激活，7TM结构，视黄醛门控）和NpHR（黄光沉默，Cl⁻泵）的分子机制；Cre-lox/c-fos-tTA遗传特异性递送；假记忆实验（Ramirez 2013）和记忆效价翻转（Redondo 2014）作为因果证明的最高标准；方法论意义（从相关性到因果性的认识论革命）；与AI可解释性的深层类比。新建1个wiki页面（methods/optogenetics），修订 engram-cells 页面（补充c-fos-tTA技术细节，~2-6% DG细胞稀疏性），添加14条新边。

**第18篇（2026-06-10）**：**瞬息之变：短时程突触可塑性的分子机制与计算逻辑**——揭示突触如何在毫秒至分钟尺度内动态调整传递效率。四种形式（易化/抑制/增强/PTP）的分子机制：Syt7高亲和力慢解离作为配对脉冲易化的主要传感器（4种突触类型KO实验，Jackman & Regehr 2017）；RRP耗竭驱动抑制（Zucker & Regehr 2002）；Syt7-depression精确平衡实现频率不变传输（Turecek 2017）；Mongillo活动无声工作记忆模型。高p突触=低通滤波、低p突触=高通滤波（Tsodyks-Markram 1997）。新建2个wiki页面（short-term-synaptic-plasticity, readily-releasable-pool），修订 synaptotagmin 和 working-memory 两页，添加10条新边，解决 readily-releasable-pool 悬空引用。

**第19篇（2026-06-11）**：**V1初级视觉皮层的方向选择性：从随机输入到精确编码**——首次进入"大脑如何编码世界——视觉皮层"主题。复现Hubel & Wiesel 1962的发现（简单/复杂细胞，前馈模型），阐明三层机制（LGN前馈排列+E/I平衡+LGN非线性跨方向抑制），呈现猫/猴方向柱 vs 小鼠盐-胡椒型组织的物种悖论（Hansel & van Vreeswijk 2012理论解释），解析树突突触聚类对方向选择性的增益贡献（Wilson 2016），并比较CNN Gabor滤波器与V1简单细胞感受野的收敛性（Kindel 2019）。新建3个wiki页面（v1-primary-visual-cortex, orientation-selectivity, synaptic-clustering），修订 dendritic-computation（revision_count 3→4），添加13条新边，解决 synaptic-clustering 悬空引用（被 dendritic-computation 引用的最长悬挂引用之一）。

**第20篇（2026-06-12）**：**注意的化学语言：乙酰胆碱与去甲肾上腺素如何向大脑发出行动指令**——揭示皮层增益控制的双系统机制。基底前脑ACh（M1肌碱受体→减少K⁺漏电→乘法性响应增益提升）与蓝斑NE（α2A→抑制HCN→稳定PFC工作记忆表征；α1→噪声增加；β→促进LTP）各自的受体、解剖和信号逻辑；Aston-Jones & Cohen（2005）的相位-紧张模式理论（任务驱动→相位；漫游→紧张；睡眠→静默）；Herrero et al.（2008, Nature, PMID:18633352）在猕猴V1直接证明东莨菪碱（M1拮抗剂）消除注意诱导增益提升（P<0.001），而美加明（nAChR拮抗剂）无效（P=0.465）。新建4个wiki页面（acetylcholine-cortex, norepinephrine-locus-coeruleus, neuromodulator-systems, gain-control），修订 v1-primary-visual-cortex（revision 2）和 working-memory（revision 4），添加22条新边；知识图谱总计54节点、278条边。

---

## 待补的悬空引用（缺口，下一步可写）

- ~~`place-cell`（场所细胞）~~ ✅ **2026-05-28 已建立**
- ~~`theta-oscillations`（θ振荡）~~ ✅ **2026-05-29 已建立**
- ~~`engram-cells`（印迹细胞）~~ ✅ **2026-05-31 已建立**
- ~~`calcium-channel`（电压门控钙通道）~~ ✅ **2026-06-01 已建立**（slug为`voltage-gated-calcium-channels`，填补6个页面的悬空引用）
- ~~`pv-interneurons`（PV+ 中间神经元）~~ ✅ **2026-06-03 已建立**（填补 chandelier-cell, dendritic-computation, hippocampal-circuit 的悬空引用）
- ~~`sst-interneurons`（SST+ 中间神经元）~~ ✅ **2026-06-03 已建立**（填补 dendritic-computation, hippocampal-circuit 的悬空引用）
- ~~`vip-interneurons`（VIP+ 中间神经元）~~ ✅ **2026-06-03 已建立**
- ~~`disinhibitory-circuit`（去抑制回路）~~ ✅ **2026-06-03 已建立**
- `memory-consolidation`（记忆巩固）— 被多个页面引用；SWR 已有详细覆盖（sharp-wave-ripples），但**系统巩固专页**尚缺（皮层侧机制、睡眠阶段分工、标准巩固 vs 多重痕迹理论），**最高优先级（第二周首要主题）**
- ~~`path-integration`（路径整合）~~ ✅ **2026-06-22 已建立**
- ~~`place-cells`（场所细胞）~~ ✅ **2026-06-22 已建立**（旧悬空slug：place-cell，已修正）
- ~~`grid-cells`（网格细胞）~~ ✅ **2026-06-22 已建立**（旧悬空slug：grid-cell，已修正）
- ~~`theta-phase-precession`（θ相位前移）~~ ✅ **2026-06-22 已建立**（旧悬空slug：phase-precession，已修正）
- ~~`entorhinal-cortex`（内嗅皮层）~~ ✅ **2026-06-22 已建立**
- ~~`cognitive-map`（认知地图）~~ ✅ **2026-06-22 已建立**
- ~~`synaptic-clustering`（突触聚类假说）~~ ✅ **2026-06-11 已建立**（Wilson 2016体内证据；V1雪貂，聚类程度与OSI正相关；普遍性待验证）
- `apical-tuft`（顶端簇）— 被 [[树突计算]]、[[锥体神经元]] 引用，Ca²⁺ 棘波的主要发生地
- ~~`three-factor-learning-rule`（三因素学习规则）~~ ✅ **2026-06-07 已建立**（同时建立 dopamine-reward-prediction-error 和 synaptic-tagging-capture，填补 hebbian-learning 悬空引用）
- `tarp-auxiliary-subunit`（TARP 辅助亚基）— 被 [[ampa-receptor]] 引用，AMPA 受体突触锚定关键
- ~~`readily-releasable-pool`（可释放池/RRP）~~ ✅ **2026-06-10 已建立**（填补突触传递页引用，新建 neurons/readily-releasable-pool 专页）
- `complexin`（复合素）— 被 SNARE-complex 等引用

---

## 当前知识前沿（高连接、待深挖）

- **嵌套时间编码层级**（今日新建，综合性框架节点）：连接 ltp/btsp/theta-oscillations/sharp-wave-ripples/phase-precession/nmda-receptor/dendritic-computation/place-cell/hebbian-learning 共 9 个节点；是第一周知识的整合枢纽。**第二周方向的参照系**。
- **θ振荡**（整合节点）：连接 place-cell、grid-cell、hippocampal-circuit、ltp、btsp、sharp-wave-ripples、phase-precession 等 7+ 节点；是"全脑网络层"的关键节点。
- **NMDA 受体**（最高连接数）：连接突触 LTP、树突计算、BTSP（间接）、嵌套时间编码层级；仍是最密集枢纽节点。
- ~~**印迹细胞（engram-cells）**~~ ✅ **2026-05-31 已建立**（填补了 ltp/hebbian-learning/dendritic-computation/place-cell 共 4 个页面的悬空引用）
- **记忆巩固（memory-consolidation）**（新优先悬空引用）：被 hippocampal-circuit、place-cell、sharp-wave-ripples 引用；系统巩固理论、皮层侧 LTP、睡眠阶段分工；**第二周次优先主题**。
- ~~**电压门控钙通道（calcium-channel）**~~ ✅ **2026-06-01 已建立**（新建 voltage-gated-calcium-channels 节点，添加12条新边，连接9个既有节点）
- **记忆巩固（memory-consolidation）**（现在最高优先级）：被 hippocampal-circuit、place-cell、sharp-wave-ripples、engram-cells 引用；系统巩固、睡眠阶段分工、皮层侧 LTP；**第二周首要主题**。

**第26篇（2026-06-16）**：**默认模式网络（DMN）——当大脑"休息"时，它在做什么？**——课程路线8（意识与自我）开篇。Raichle 2001 PET元分析发现跨任务一致性去激活区域；Fox 2005 静息态fMRI证实DMN-TPN反相关（r≈-0.15至-0.20）；Andrews-Hanna 2011/2014 揭示双子系统架构（MTL子系统=情节记忆/场景构建；dMPFC子系统=心智化）；aMPFC+PCC作为个人相关信息超加性整合枢纽；Buckner 2009 Aβ优先沉积DMN枢纽节点的功能解剖解释；GSR方法论争议；DMN作为预测编码高层先验生成器。新建1个wiki页面（systems/default-mode-network），修订 predictive-coding、hippocampal-circuit、alzheimers-disease 三页；图谱67节点385条边；新建Q-dmn-01到Q-dmn-04。

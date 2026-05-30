# 神经科学 Wiki 知识库 · 总地图

> 这是语义层的人读地图。每个条目链接到一个**活的**主题页（会随时间被修订加深）。
> 机读版见 `_graph.json`；每日变更见 `CHANGELOG.md`；设计原理见仓库根 `KNOWLEDGE-BASE-DESIGN.md`。
>
> 成熟度图例：🟢 established · 🔵 mainstream · 🟡 emerging · ⚪ speculative · 🔴 contested
>
> 最后更新：2026-06-15 · 主题页总数：63

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
- 🟢 [θ振荡](concepts/theta-oscillations.md) — 海马4–12 Hz探索节律；提供相位编码时间框架；θ序列压缩路径；θ/γ嵌套承载5-9项目序列
- 🟢 [尖波涟漪（SWR）](concepts/sharp-wave-ripples.md) — CA3→CA1高频群体事件；20倍速序列重播；记忆固化的离线物理载体
- 🟢 [相位前进](concepts/phase-precession.md) — 场所细胞在θ周期中放电相位随位置移动；速率+相位双重编码；O'Keefe & Recce 1993经典发现
- 🟡 [嵌套时间编码层级](concepts/temporal-coding-hierarchy.md) — 大脑记忆系统在 μs 到年的时间谱上，以嵌套方式在每层通过巧合检测修改突触权重；Hebb 原理的多时间尺度实例化（第一周综合分析框架）
- 🟢 [印迹细胞](concepts/engram-cells.md) — 学习时被激活并持久改变的神经元集合；光遗传学证明激活印迹细胞足以重现记忆；沉默印迹证明遗忘可以是提取障碍而非信息消失（修订2次）
- 🟢 [记忆巩固（系统层面）](concepts/memory-consolidation.md) — SWR驱动的海马→皮层记忆转移；SO-spindle-SWR三重奏；SCT vs MTT理论争论；互补学习系统模型 **[NEW 2026-06-02]**
- 🟢 [长时程抑制（LTD）](concepts/ltd.md) — NMDA-LTD（PP2B/PP1/GluA1去磷酸化）与 mGluR-LTD（Arc/AMPAR内吞）构成双向突触可塑性；LTD 是主动的精准遗忘机制 **[NEW 2026-06-04]**
- 🟢 [钙调磷酸酶（Calcineurin / PP2B）](concepts/calcineurin.md) — 高亲和力 Ca²⁺ 磷酸酶，中低 Ca²⁺ 时激活，是 NMDA-LTD 磷酸酶级联的第一步；与 CaMKII 构成 LTP/LTD 方向性的分子开关 **[NEW 2026-06-04]**
- 🟢 [Arc/Arg3.1（活动调控的细胞骨架相关蛋白）](concepts/arc-arg31.md) — 突触活动量规器：mGluR-LTD 的执行蛋白（dynamin/endophilin 内吞）；同时参与 L-LTP 巩固（肌动蛋白稳定）；突触稳态的分子感受器 **[NEW 2026-06-04]**
- 🟢 [工作记忆](concepts/working-memory.md) — 容量~4项的临时信息维持系统；γ爆发（活动性编码）+ STP突触易化（静默储存）双机制；依赖dlPFC吸引子回路、PV-γ轴和多巴胺D1调节 **[NEW 2026-06-05]**
- 🟢 [持续活动（延迟期放电）](concepts/persistent-activity.md) — PFC 延迟期的神经活动模式；实为间歇性 γ 爆发而非连续高频放电；依赖 NMDA 慢衰减和循环兴奋吸引子网络 **[NEW 2026-06-05]**
- 🟢 [γ振荡（30–80 Hz）](concepts/gamma-oscillations.md) — PV+篮状细胞兴奋-抑制循环产生；工作记忆中以~67ms爆发形式间歇出现；精神分裂症中功率减弱与PV损伤相关 **[NEW 2026-06-05]**
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

## systems（系统）

- 🟢 [前额叶皮层（PFC）](systems/prefrontal-cortex.md) — dlPFC 第2/3/5层循环回路是工作记忆的关键脑区；PV-γ轴是认知控制的时序基础 **[NEW 2026-06-05]**
- 🟢 [初级视觉皮层（V1）](systems/v1-primary-visual-cortex.md) — 视觉信息皮层第一站；方向选择性从LGN非定向输入的从头计算；猫/猴方向柱 vs 小鼠盐-胡椒型组织均可达精确方向选择性；树突突触聚类增益层（Wilson 2016）；ACh通过肌碱受体放大V1注意调制（Herrero 2008）（修订2次）
- 🟢 [神经调质系统](systems/neuromodulator-systems.md) — 基底前脑ACh、蓝斑NE、中脑DA、中缝核5-HT四套弥散调质系统的总概述；编码"用什么模式处理信息"而非信息本身；Marder原则定位（修订3次）**[NEW 2026-06-12]**
- 🟢 [血清素-缝际核系统](systems/serotonin-raphe-system.md) — 约20-30万DRN/MRN 5-HT神经元向全脑广播；体积传输为主；14种5-HT受体；5-HT1A自受体的双重负反馈机制是SSRI延迟起效的核心 **[NEW 2026-06-13]**

## methods（方法）

- 🟢 [光遗传学](methods/optogenetics.md) — ChR2（蓝光激活）+ NpHR/Arch（黄光沉默）+ Cre-lox/c-fos-tTA 遗传特异性递送，提供毫秒精度因果回路解析；印迹细胞/假记忆/效价翻转实验的核心工具（修订2次）
- 🟢 [双光子钙成像](methods/two-photon-calcium-imaging.md) — 飞秒近红外激光的 I² 非线性激发实现活体组织深层单细胞分辨率成像；结合 GCaMP 同时记录数千神经元活动；方法层第二个已建立节点（扰动-观测框架的"观测"支柱）**[NEW 2026-06-15]**
- 🟢 [GCaMP 钙指示剂](methods/gcaMP-indicators.md) — 遗传编码钙指示剂（GECI）；CaM+M13+cpGFP 融合蛋白；GCaMP6（99%单棘波检测）→ jGCaMP8f（2ms 半上升时间，PV+快速放电分辨）；细胞类型特异性 AAV 递送 **[NEW 2026-06-15]**

## theories（理论） — *待建*

## diseases（疾病）

- 🟢 [阿尔茨海默病](diseases/alzheimers-disease.md) — Aβ寡聚体通过5条并行通路瓦解海马突触LTP；突触密度（非斑块）与认知衰退相关r=0.96；早期突触沉默可逆 **[NEW 2026-06-08]**
- 🟢 [帕金森病](diseases/parkinsons-disease.md) — α-突触核蛋白聚集/路易小体/Braak分期；基底节直接/间接通路失衡（GPi过度活跃→丘脑抑制→运动减少）；β振荡病理状态；DA和DBS共享β→θ振荡切换治疗机制（Köhler 2024）**[NEW 2026-06-14]**

---

## 当前知识路线进度

| 课程主题 | 状态 |
|---------|------|
| 1. 神经元如何工作 | 🔵 进行中（已覆盖：AIS, 动作电位, 突触传递, NMDA/AMPA 受体, CaMKII, 树突计算, 锥体神经元, 电压门控钙通道, PV+/SST+/VIP+ 中间神经元, 去抑制回路, **LTD（长时程抑制）**, **短时程突触可塑性（STP）**, **神经调质 ACh/NE（2026-06-12）**, **血清素系统/5-HT1A自受体（2026-06-13）**；待覆盖：多巴胺系统深度） |
| 2. 神经网络微回路设计 | 🔵 进行中（已覆盖：PV+/SST+/VIP+ 中间神经元, 去抑制回路；待覆盖：皮层柱结构, 前馈/反馈抑制, 神经调质调节） |
| 3. 大脑如何编码世界 | 🔵 进行中（已覆盖：场所细胞, 网格细胞, θ振荡/相位编码, **V1方向选择性（2026-06-11）**；待覆盖：听觉/体感, 头向细胞, 时间表征）|
| 4. 学习和记忆 | 🔵 进行中（已覆盖：LTP, Hebb 规则, BTSP, 海马回路, 场所场形成, SWR 重播, 印迹细胞, 记忆巩固（系统层面）, **LTD**, **短时程突触可塑性（STP）**；待覆盖：记忆提取机制）|
| 5. 认知控制 | 🔵 进行中（已覆盖：**工作记忆**、**奖励学习/三因素规则（2026-06-07）**、**注意/增益控制（ACh/NE，2026-06-12）**；待覆盖：执行控制、决策）|
| 6. 情绪与动机 | 🔵 进入中（已覆盖：多巴胺奖励系统、VTA/NAc/PFC 投射路线；待覆盖：杏仁核、恐惧、动机回路）|
| 11. 疾病作为窗口 | 🔵 进行中（已覆盖：阿尔茨海默病（AD突触机制）、**帕金森病（基底节回路失衡/β振荡/DBS机制，2026-06-14）**；待覆盖：ASD、精神分裂症、癫痫）|
| 10. 方法革命 | 🔵 进行中（已覆盖：**光遗传学**、**双光子钙成像 + GCaMP（2026-06-15）**；待覆盖：电生理（Neuropixels）、fMRI、单细胞测序、空间转录组）|
| 2, 7–9, 12 | ⚪ 待开始 |

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
- `path-integration`（路径整合）— 被 [[网格细胞]] 引用，网格细胞无地标时维持空间表征的内源机制
- `memory-consolidation`（记忆巩固）— 被 [[海马回路]]、[[场所细胞]] 引用，SWR重放→皮层巩固
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

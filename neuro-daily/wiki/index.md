# 神经科学 Wiki 知识库 · 总地图

> 这是语义层的人读地图。每个条目链接到一个**活的**主题页（会随时间被修订加深）。
> 机读版见 `_graph.json`；每日变更见 `CHANGELOG.md`；设计原理见仓库根 `KNOWLEDGE-BASE-DESIGN.md`。
>
> 成熟度图例：🟢 established · 🔵 mainstream · 🟡 emerging · ⚪ speculative · 🔴 contested
>
> 最后更新：2026-09-14（第144篇·V1各层如何区分预测与预测误差·Thomas 2024 7T fMRI层级解码·Bastos 2012典范微回路·Keller 2012感觉运动错配）· 主题页总数：**284**（新建0页；修订2页：theories/predictive-coding rev9→rev10, systems/v1-primary-visual-cortex rev7→rev8；新增Q-pc-08/Q-pc-09；图谱285节点/1653边）

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
- 🟢 [场所细胞](neurons/place-cell.md) — 海马 CA1/CA3 的空间位置编码器，通过 BTSP 单次写入场所场，构成大脑认知地图（修订4次）
- 🟢 [海马回路](neurons/hippocampal-circuit.md) — DG（模式分离）→ CA3（模式补全）→ CA1（整合输出）的三突触回路与并行穿孔通路；AD最早受损的回路（修订6次）
- 🔵 [苔藓细胞（齿状回）](neurons/mossy-cells-dentate.md) — 门区大型兴奋性细胞，净效果为通过招募篮状细胞间接抑制颗粒细胞（苔藓细胞悖论）；Jinde 2012 消融实验：缺失→颗粒细胞过兴奋→模式分离失败；GoodSmith 2017：多位置场/高放电率（对比颗粒细胞单场极低频）；Vargish 2025 预印本：VGluT3+ 元抑制回路 **[NEW 2026-08-28]**
- 🟢 [颞下皮层（IT 皮层）](neurons/inferior-temporal-cortex.md) — 腹侧视觉流终点；物体身份的不变性表征；IT 种群活动线性可分（90%+准确率）；无监督时间连续性学习维持不变性；物体空间低维坐标地图（Bao 2020）**[NEW 2026-08-29]**
- 🟢 [MT/V5 运动区](neurons/mt-v5-motion-area.md) — 背侧流关键中间站；方向选择性；pattern motion 整合；双目视差细胞；MT损毁→运动感知阈值升高（Newsome 1988）；运动盲（akinetopsia）**[NEW 2026-08-30]**
- 🟢 [中型多棘神经元（MSN）](neurons/medium-spiny-neuron.md) — 纹状体主导细胞（95%+）；D1型→直接通路→D1-cAMP-PKA-DARPP-32-LTP；D2型→间接通路→eCB-CB1-LTD；上行/下行双稳态；灵长类≥9种转录学亚型；**rev2新增**：HD选择性脆弱性四重机制（BDNF依赖性单点失效/NR2B兴奋毒性/转录失调靶向性/体细胞CAG不稳定） **[NEW 2026-09-01 · 修订 rev2 2026-09-07]**
- 🟢 [浦肯野细胞](neurons/purkinje-cell.md) — 小脑皮层唯一输出神经元；接受 ~20 万 PF（运动情景）+ 1 CF（误差/奖励预测违反信号）；LTD（mGluR1→PKC→AMPAR 内吞）；多层可塑性（Schonewille 2011）；复杂放电梯度；奖励 CF 信号（Jin 2025，emerging） **[NEW 2026-09-03]**
- 🟢 [攀爬纤维](neurons/climbing-fiber.md) — 来自下橄榄核；每根与单一 PC 形成 400–500 个强突触；触发复杂放电（1–4 个去极化波峰，3–30 ms）；梯度误差信号（Zang 2019）；外侧小脑携带奖励预测误差（Jin & Hull 2025，emerging） **[NEW 2026-09-03]**
- 🟢 [小脑颗粒细胞](neurons/granule-cell-cerebellar.md) — 约 690 亿个（全脑 50–80%）；MF→GC→PF 感觉运动情景高维重编码；稀疏 vs 密集编码争议（Xie 2023：任务依赖最优）；Lee 2023 因果证明对运动功能不可或缺 **[NEW 2026-09-03]**
- 🟢 [网格细胞](neurons/grid-cell.md) — 内侧内嗅皮层的六角网格空间编码器，模块化组织（1.4:1间距比），为场所细胞提供坐标框架；人类fMRI六边形信号证实（修订2次）
- 🟢 [头向细胞](neurons/head-direction-cells.md) — 对头部方向选择性放电的神经元，构成大脑方位罗盘；环形吸引子网络生成；PoS/ADN/LMN/RSC回路 **[NEW 2026-07-27]**
- 🟢 [边界细胞](neurons/border-cells.md) — MEC/下托中对环境边界距离/方向编码的神经元，为路径积分提供空间锚点防止误差累积 **[NEW 2026-07-27]**
- 🟢 [电压门控钙通道（VGCCs）](neurons/voltage-gated-calcium-channels.md) — P/Q型在突触前纳米域触发递质释放；L型在树突驱动BTSP平台电位，在核激活基因表达；三亚家族、三地点、三时间尺度 **[NEW 2026-06-01]**
- 🟢 [T 型钙通道（低电压激活钙通道）](neurons/t-type-calcium-channels.md) — CaV3.1（TC）/CaV3.3（TRN）是视丘爆发放电的分子开关；需超极化去失活后触发LTS；失神癫痫/脆性X综合征的分子通路 **[NEW 2026-06-30]**
- 🟢 [视丘放电模式（爆发/强直双模式）](neurons/thalamic-firing-modes.md) — 清醒VPm约15%感觉响应为爆发；爆发提高时序精度（非幅度）；爆发-强直连续谱：检测vs辨别；基于时序的感知门控 **[NEW 2026-06-30]**
- 🟢 [小胶质细胞](neurons/microglia.md) — CNS 常驻免疫细胞，发育期突触剪枝执行者：CR3（C3b识别）+ TREM2（PS识别）双通路；活动依赖性（TTX→优先吞噬沉默突触）；AD中C1q重激活；精神分裂症C4A→过度剪枝 **[NEW 2026-06-03]**
- 🟢 [低阈值机械感受器（LTMR）](neurons/mechanoreceptor-ltmr.md) — 皮肤中专职编码轻触/振动/压力的四类感受器（SA1 Merkel/SA2 Ruffini/RA1 Meissner/RA2 Pacini）；PIEZO2通道介导机械转导；脊髓背角机械感觉柱整合信号 **[NEW 2026-07-29]**
- 🟢 [CB1 大麻素受体](neurons/cb1-receptor.md) — 脑内最丰富的 GPCR，主要突触前定位；富集于 CCK⁺ GABA 能中间神经元（皮层/海马）；Gi/o 偶联：Gβγ→Cav2.2 抑制（DSI 短时程），Gαi→cAMP/PKA↓→RIM1α（eCB-LTD 长时程），GIRK 激活（SSI）；BLA CB1R 激活对恐惧消退因果必要 **[NEW 2026-08-05]**

## circuits（回路）

- 🔵 [吊灯细胞](circuits/chandelier-cell.md) — 特异靶向 AIS 的抑制性中间神经元（修订2次）
- 🟢 [基底节](circuits/basal-ganglia.md) — 纹状体/GPi/GPe/STN/SNc构成的运动选择回路；直接通路（D1/促进运动）与间接通路（D2/抑制运动）由多巴胺精确平衡；振荡状态决定运动是否被"允许"；**新增**：超直接通路IFG-STN单突触（2.2 ms）与停止信号全局抑制证据 **[修订 rev2→rev3 2026-08-19]**
- 🔵 [纹状体直接/间接通路](circuits/striatal-direct-indirect-pathway.md) — dMSN→GPi/SNr（直接，促进行动）；iMSN→GPe→STN→GPi/SNr（间接，抑制行动）；DMS/DLS功能分化；行为证据：DMS损伤→习惯化，DLS损伤→无法习惯化 **[NEW 2026-09-01]**
- 🟢 [丘脑-皮层回路](circuits/thalamocortical-circuit.md) — TRN（CaV3.3 T型）↔TC（CaV3.1）振荡环路是睡眠纺锤波起搏器；Core/Matrix双通路；CT反馈在清醒/睡眠切换中起关键作用；**新增**：一次/高次视丘核（Sherman框架）、驱动/调制型突触、PFC→TRN大型端钮（2026-06-03更新）
- 🟢 [PV+ 中间神经元](circuits/pv-interneurons.md) — 快速放电篮状/吊灯细胞，控制 gamma 振荡与精确输出时序；Sohal 2009 光遗传学因果证明 PV→γ；GAD67 下调→PING 崩溃→WM 缺陷（精神分裂症核心机制）**[NEW 2026-06-03 · 修订 rev5 2026-07-20]**
- 🟢 [SST+ 中间神经元](circuits/sst-interneurons.md) — Martinotti 细胞靶向远端树突，O-LM 细胞 theta 期门控 EC 输入 **[NEW 2026-06-03]**
- 🟢 [VIP+ 中间神经元](circuits/vip-interneurons.md) — CGE 来源的去抑制专家，被行为显著信号激活 **[NEW 2026-06-03]**
- 🟢 [去抑制回路](circuits/disinhibitory-circuit.md) — VIP→SST/PV→锥体细胞的三级去抑制架构，学习与注意调制的皮层通用模块 **[NEW 2026-06-03]**
- 🟢 [规范微回路（新皮层）](circuits/cortical-canonical-microcircuit.md) — 六层保守回路模板：L2/3（误差单元，γ前馈）→L5/6（预测单元，β反馈）→L6（丘脑门控）；L5顶端钙爆发 AND 门；VIP+去抑制注意调控；Douglas & Martin 2004循环兴奋4-7×，Harris & Shepherd 2015串联同源性 **[NEW 2026-07-18]**

## concepts（概念/框架）

- 🟢 [发育关键期](concepts/critical-period.md) — GABA 阈值触发开启；三道刹车（PNN/OTX2/Lynx1）主动关闭；ChABC/氟西汀/催产素可重开；MeCP2 KO 使 Rett 综合征关键期错位；弱视与语言习得的发育窗口 **[NEW 2026-06-03]**
- 🟢 [突触剪枝](concepts/synaptic-pruning.md) — 先多建再精删策略；C1q/C3b"吃我"+CD47"别吃我"双向博弈；活动依赖（TTX实验）；dLGN/海马/前额叶分窗口；精神分裂症（C4A过度剪枝）与AD（C1q重激活）疾病连接 **[NEW 2026-06-03]**
- 🟢 [补体级联（CNS突触功能）](concepts/complement-cascade-cns.md) — C1q→C4→C3b经典通路；TGF-β（星形胶质细胞）诱导神经元C1q；CR3识别C3b触发吞噬；发育期/病理期的表达差异 **[NEW 2026-06-03]**
- 🟢 [Hodgkin-Huxley 模型](concepts/hodgkin-huxley-model.md) — 动作电位的定量数学框架
- 🟢 [SNARE复合体](concepts/SNARE-complex.md) — 突触囊泡融合的核心分子机器（四螺旋束拉链）
- 🟢 [NMDA 受体](concepts/nmda-receptor.md) — 突触巧合检测器 + 树突 NMDA 棘波 + PFC 吸引子时间积分器 + AD中突触外NR2B逆转LTP + 脊髓中枢敏化触发器 + **兴奋毒性的主要Ca²⁺入口（突触内/外位置决定存活或死亡，修订rev7 2026-09-08）**（修订7次）
- 🔵 [兴奋毒性](concepts/excitotoxicity.md) — 谷氨酸过激活引发的神经元死亡机制；位置决定命运（突触内=CREB存活 vs 突触外=Jacob/DAPK1/Calpain死亡）；钙-线粒体-ROS三联体；GLT-1防线；ALS/AD/HD/缺血中的疾病窗口 **[NEW 2026-09-08 · 修订2026-09-09: mPTP汇聚机制补充]**
- 🔵 [PINK1/Parkin 线粒体自噬](concepts/pink1-parkin-mitophagy.md) — ΔΨm消失→PINK1 OMM积累→二聚化+自磷酸化→pUb（Ser65）生成→Parkin招募+激活（正反馈放大）→NDP52/OPTN/TBK1→LC3/自噬体→溶酶体；PD早发性遗传最主要原因（PINK1/PARK6、Parkin/PARK2）；Pink1 KO猕猴vs小鼠物种差异 **[NEW 2026-09-09]**
- 🟢 [长时程增强（LTP）](concepts/ltp.md) — 突触可塑性与学习记忆的分子基础；Aβ寡聚体通过五条通路单向阻断LTP；CA3循环突触NMDAR-LTP是模式补全的分子基础（修订8次）
- 🟢 [模式补全](concepts/pattern-completion.md) — CA3吸引子动力学从部分线索恢复完整记忆；Nakazawa 2002 CA3-NR1 KO因果证据 **[NEW 2026-06-24]**
- 🟢 [模式分离](concepts/pattern-separation.md) — DG扩张重编码+稀疏激活把相似输入变成不相似表征；苔藓细胞悖论：兴奋性苔藓细胞净效果为抑制颗粒细胞（Jinde 2012）；维度框架（Cayco-Gajic 2019）；Sahay 2011神经发生因果证据 **[修订 rev2→rev3 2026-08-28]**
- 🔵 [吸引子网络](concepts/attractor-network.md) — Hopfield网络数学基础；CA3生物实现；现代Hopfield网络=Transformer注意力的数学等价 **[NEW 2026-06-24]**
- 🔵 [互补学习系统（CLS）](concepts/complementary-learning-systems.md) — 海马快/稀疏学习+新皮层慢/分布式学习；SWR重放是知识转移机制；深度学习经验回放缓冲区的神经科学先驱 **[NEW 2026-06-24]**
- 🟢 [Hebbian 学习](concepts/hebbian-learning.md) — "共同激发的神经元连接在一起"，NMDA 受体实现其分子逻辑；皮层拓扑地图的经验依赖重组（Merzenich 1983–1993）是其在全脑图谱尺度的直接证明 **[修订 rev6 2026-07-29]**
- 🟢 [皮层可塑性](concepts/cortical-plasticity.md) — 成年初级感觉皮层（S1/A1/V1）的经验依赖拓扑重组；Merzenich系列实验；需行为相关性（注意门控）；感觉剥夺重启关键期状态；多时间尺度机制（GABA解除/LTP/轴突出芽）**[NEW 2026-07-29]**
- 🟢 [感觉小人](concepts/homunculus.md) — Penfield（1950）S1拓扑体图；比例失真正比于感受器密度（指尖140 SA1/cm² vs 背部1/cm²）；21世纪SEEG/fMRI揭示精细内部梯度；动态可塑小人 **[NEW 2026-07-29]**
- 🔵 [突触时序依赖可塑性（STDP）](concepts/stdp.md) — Hebb 规则的时间分辨精化版：前先后→LTP，后先前→LTD；NMDA 受体±20ms 仲裁；θ 前进体内桥接；三因素扩展 **[NEW 2026-06-19]**（填补 hebbian-learning 悬空引用）
- 🟢 [皮层分层结构（六层）](concepts/cortical-layers.md) — L1–L6 各层细胞类型、输入/输出投射和振荡特征；前馈（L2/3→高级L4，γ驱动型）vs 反馈（L5/6→低级L1/2/3，β调制型绕过L4）的层级不对称；L4棘突星形细胞、L5厚毛绒锥体细胞两极整合、L6 CT丘脑门控 **[NEW 2026-07-18]**
- 🟢 [AMPA 受体](concepts/ampa-receptor.md) — 快速突触传递的执行者，LTP 权重变化的物理载体
- 🟢 [行为时间尺度突触可塑性（BTSP）](concepts/btsp.md) — 秒级时间窗口的突触增强规则，单次写入场所场，与 LTP 并列的独立学习法则
- 🟢 [θ振荡](concepts/theta-oscillations.md) — 海马4–12 Hz探索节律；提供相位编码时间框架；θ序列压缩路径；θ/γ嵌套承载5-9项目序列；REM期LA-VH θ同步驱动情绪记忆巩固（Boyce 2016, Totty 2017）**[修订 2026-07-21 rev4]**
- 🔵 [θ-γ跨频率耦合](concepts/theta-gamma-coupling.md) — Lisman-Idiart 1995容量分格模型：每个θ周期嵌套约4–6个γ爆发，每个γ爆发承载一项工作记忆（对应4±1容量上限）；Colgin 2009慢γ（θ波峰，CA3）/快γ（θ波谷，MEC）双通道时分路由；Axmacher 2010人类颅内PAC证据；Huang 2026序列规划扩展 **[NEW 2026-07-21]**
- 🟢 [α振荡（8–12 Hz）](concepts/alpha-oscillations.md) — 视丘-皮层回路（TRN-TC）与皮层L5协同生成的最强神经振荡；抑制-时序假说：ERS=主动压制无关感觉输入；Worden 2000/Foxe 2011确立差异化α拓扑门控；枕核/LP复合体为α广播器（Bourgeois 2020）；α-γ PAC在工作记忆三阶段（编码/维持/提取）的分格机制（Roux 2014双代码模型×Wianda 2019三阶段证据）；Q-theta-primate的α-γ替代假说 **[NEW 2026-07-22]**
- 🟢 [尖波涟漪（SWR）](concepts/sharp-wave-ripples.md) — CA3→CA1高频群体事件；20倍速序列重播；记忆固化的离线物理载体；大振幅亚集专门驱动海马-PFC同步再激活（Robinson 2026）；清醒SWR是记忆标记机制（Yang 2024）；SWR嵌套在纺锤波内（SO-spindle-SWR三重耦合）；Maingret 2016 闭环因果证据**[修订 2026-07-07]**
- 🟢 [场所细胞](concepts/place-cells.md) — 海马CA1/CA3位置特异放电神经元；稀疏编码（1–5%激活）；重映射（不同环境正交表征）；θ相位前移实现双重位置编码；SWR期间序列以20倍速重播；是认知地图基本编码单元 **[NEW 2026-06-22]**（填补长期悬空引用）
- 🟢 [网格细胞](concepts/grid-cells.md) — 内侧内嗅皮层MEC以六边形格点激活的神经元；三参数（间距/方向/相位）完全描述；4–7离散模块比√2；背腹向间距梯度（20cm–1.5m）；路径整合的坐标输出；活跃于心理模拟和概念空间（Qu 2026 Cell：发育成熟预测流体智力）**[NEW 2026-06-22]**（填补长期悬空引用）
- 🟢 [路径整合](concepts/path-integration.md) — 通过持续积累速度矢量估计当前位置；不依赖外部地标；联合细胞（位置+方向+速度）实现；随时间漂移需地标锚定；是黑暗导航的神经机制 **[NEW 2026-06-22]**
- 🟢 [θ相位前移](concepts/theta-phase-precession.md) — 场所细胞放电相位随穿越场所场系统性提前约100–355°；产生θ序列（125ms内压缩数秒路径）；为STDP提供时间压缩框架；O'Keefe & Recce 1993经典发现；CAN vs OI两机制模型仍未决 **[NEW 2026-06-22]**（填补theta-oscillations页面的phase-precession悬空引用）
- 🔵 [认知地图](concepts/cognitive-map.md) — 海马-EC构建的空间（及概念）关系内部模型；从Tolman 1948捷径行为到场所/网格双系统；扩展至时间序列（情节记忆）、心理模拟（Bellmund 2016）、概念空间（Viganò 2023）；发育研究证据（Qu 2026）**[NEW 2026-06-22]**
- 🟢 [睡眠纺锤波](concepts/sleep-spindles.md) — TRN CaV3.3→TRN↔TC振荡→12–15 Hz梭形波；皮层树突L型Ca²⁺预热窗口；SO-spindle-SWR三重奏中间层；CACNA1I变异→精神分裂症纺锤波缺陷；三重耦合因果实验（Latchoumane 2017）；老龄化相位偏移 46.3°→记忆损害（Helfrich 2018）**[修订 2026-07-07]**
- 🟢 [皮层慢振荡（SO）](concepts/cortical-slow-oscillation.md) — NREM 深睡眠~0.75 Hz UP/DOWN态交替；起源PFC向后传播；SO上行相是纺锤波和SWR的最高时间框架；三重奏顶层 **[NEW 2026-06-19]**
- 🟢 [SO-纺锤波-SWR 三重耦合](concepts/so-spindle-swr-coupling.md) — NREM 睡眠中 SO（主时钟）→纺锤波（皮层预热）→SWR（记忆写入）精确时间嵌套；Maingret 2016 闭环刺激因果证明；老龄化耦合精度下降（d=1.19，mPFC 萎缩机制）；DA/NE/ACh 神经调质调节 **[NEW 2026-07-07]**
- 🔵 [突触稳态假说（SHY）](concepts/shy-hypothesis.md) — Tononi & Cirelli：清醒期 LTP 积累→睡眠期 SO 驱动 ~18% 突触下调（de Vivo 2017 超微结构证据）；down-selection：被 SWR 重播激活的突触受保护，多数突触弱化；与主动记忆巩固统一 **[NEW 2026-07-07]**
- 🟢 [皮层 UP/DOWN 态机制](concepts/up-down-state-mechanism.md) — Layer 5 循环兴奋（AMPA+NMDA 侧支）自主启动 UP 态（~−65 mV，0.8–1.5 s）；KNa 通道 Na⁺ 积累（主要机制）+ 短时程突触抑郁 + SST+ 延迟抑制三机制终止 UP 态；孤立皮层切片自发 SO 证明回路内在充分性（Sanchez-Vives 2000）；为 SO-spindle-SWR 三重协奏提供细胞层级时间骨架 **[NEW 2026-07-23]**
- 🟢 [相位前进](concepts/phase-precession.md) — 场所细胞在θ周期中放电相位随位置移动；速率+相位双重编码；O'Keefe & Recce 1993经典发现
- 🔵 [嵌套时间编码层级](concepts/temporal-coding-hierarchy.md) — 大脑记忆系统在 μs 到年的时间谱上，以嵌套方式在每层通过巧合检测修改突触权重；Hebb 原理的多时间尺度实例化（第一周综合分析框架）**[修订rev2 2026-08-13：新增皮层INT/TRW层级维度]**
- 🔵 [内禀神经时间尺度（INT）](concepts/intrinsic-neural-timescale.md) — 皮层区域自发放电自相关时间常数τ（MT~50ms→ACC~350ms）；由突触兴奋梯度+E/I平衡+NMDA亚基组成决定；跨物种/模态一致；颞叶癫痫/AD/脑卒中中失调 **[NEW 2026-08-13]**
- 🔵 [时间感受野（TRW）](concepts/temporal-receptive-window.md) — 皮层各区域的外部信息时间整合窗口（A1:毫秒→DMN:数十秒）；叙事打乱实验测量；叙事理解时信息流沿层级有序传播；与INT高度相关但测量角度不同 **[NEW 2026-08-13]**
- 🟢 [印迹细胞](concepts/engram-cells.md) — 学习时被激活并持久改变的神经元集合；光遗传学证明激活印迹细胞足以重现记忆；沉默印迹证明遗忘可以是提取障碍而非信息消失（修订5次）
- 🔵 [神经元分配（记忆分配）](concepts/memory-allocation.md) — CREB/内在兴奋性竞争决定哪些神经元进入印迹；零和竞争；PV+侧向抑制赢家通吃；表观遗传前置层（H3K27ac）；训练后5min巩固窗口 **[NEW 2026-07-05]**
- 🟡 [记忆联结](concepts/memory-linking.md) — 时间接近（~6h）的两段学习因共享高兴奋性印迹神经元而实现联结；Cai 2016 CA1钙成像直接证据；老年小鼠联结缺陷→DREADD救援；scFLARE2精确时间边界（3h vs 27h）**[NEW 2026-07-05]**
- 🟢 [记忆巩固（系统层面）](concepts/memory-consolidation.md) — SWR驱动的海马→皮层记忆转移；SO-spindle-SWR三重耦合（Maingret 2016因果证据）；SHY down-selection 统一主动巩固与稳态下调；老龄化耦合解锁机制（mPFC萎缩）；SCT vs MTT理论争论；**新增**：再巩固是"巩固即密封"的动态例外（修订 2026-07-10）**[修订 2026-07-10]**
- 🔵 [记忆再巩固](concepts/memory-reconsolidation.md) — 已巩固记忆在提取后重新进入蛋白合成依赖态（Nader 2000）；去稳定化分子链（GluN2B-NMDA→CaMKII→UPS→Shank/GKAP降解+GluA2内吞）；再巩固窗口消退永久消除恐惧（Monfils 2009, Agren 2012 fMRI）；普萘洛尔消除人类情绪恐惧（Kindt 2009）；米非司酮 Phase 2a RCT 未达主要终点 **[NEW 2026-07-10]**
- 🟢 [长时程抑制（LTD）](concepts/ltd.md) — NMDA-LTD（PP2B/PP1/GluA1去磷酸化）与 mGluR-LTD（Arc/AMPAR内吞）构成双向突触可塑性；LTD 是主动的精准遗忘机制；**小脑 LTD（mGluR1/PKC路径，与 NMDA-LTD 并列，修订2026-06-23）** **[修订rev2]**
- 🟢 [小脑 LTD（PF-PC LTD）](concepts/cerebellar-ltd.md) — mGluR1→IP₃→PKC→AMPAR内吞；与海马 NMDA-LTD 共用最终效应器但触发机制根本不同；Schonewille 2011 证明无 LTD 也能运动学习；Hansel 2026 预印本 400ms 时间窗口 **[NEW 2026-06-23]**
- 🔵 [纹状体突触可塑性](concepts/striatal-plasticity.md) — 皮质-纹状体谷氨酸突触的LTP（D1-Gs-cAMP-PKA-DARPP-32-AMPA插入）和eCB-LTD（D2-mGluR-2-AG-CB1-突触前释放↓）；奖励时双向刻写；多巴胺1秒时间窗解决信用分配；NMDA受体对LTP必需 **[NEW 2026-09-01]**
- 🟢 [钙调磷酸酶（Calcineurin / PP2B）](concepts/calcineurin.md) — 高亲和力 Ca²⁺ 磷酸酶，中低 Ca²⁺ 时激活，是 NMDA-LTD 磷酸酶级联的第一步；与 CaMKII 构成 LTP/LTD 方向性的分子开关 **[NEW 2026-06-04]**
- 🟢 [Arc/Arg3.1（活动调控的细胞骨架相关蛋白）](concepts/arc-arg31.md) — 突触活动量规器：mGluR-LTD 的执行蛋白（dynamin/endophilin 内吞）；同时参与 L-LTP 巩固（肌动蛋白稳定）；突触稳态的分子感受器 **[NEW 2026-06-04]**
- 🟢 [工作记忆](concepts/working-memory.md) — 容量~4项的临时信息维持系统；γ爆发（活动性编码）+ STP突触易化（静默储存）双机制；依赖dlPFC吸引子回路、PV-γ轴和多巴胺D1调节 **[NEW 2026-06-05]**
- 🔵 [混合选择性](concepts/mixed-selectivity.md) — dlPFC 神经元对多变量交叉项的非线性响应；高维化表征支持任意规则组合的线性可读出；Rigotti 2013 证明维度降低预测行为错误；认知弹性的编码基础 **[NEW 2026-08-24]**
- 🔵 [认知稳定性—弹性权衡](concepts/stability-flexibility-tradeoff.md) — 工作记忆系统的基本计算约束；BG-PFC-dACC 网络的三角解决方案；OCD/ADHD/精神分裂症/PD 的四种失调模式 **[NEW 2026-08-24]**
- 🟢 [任务切换代价](concepts/task-switching-cost.md) — 混合代价（维持多套规则）+ 残余切换代价（旧规则正向干扰）；额顶网络与切换预测误差（Sali 2024 fMRI+RL）；OCD 超大切换代价 **[NEW 2026-08-24]**
- 🟢 [持续活动（延迟期放电）](concepts/persistent-activity.md) — PFC 延迟期的神经活动模式；实为间歇性 γ 爆发而非连续高频放电；依赖 NMDA 慢衰减和循环兴奋吸引子网络；2023/2024最新证据：持续放电神经元携带更多WM信息；Panichello 2024开-关状态 **[修订 rev2 2026-08-18]**
- 🟡 [活动无声工作记忆](concepts/activity-silent-wm.md) — 工作记忆信息在突触STSP易化状态中无声储存；Stokes 2015框架；Panichello 2024证明与持续放电机制共存 **[NEW 2026-08-18]**
- 🟢 [反应抑制](concepts/response-inhibition.md) — 叫停已启动运动/认知程序的能力；rIFG→STN超直接通路（2.2 ms单突触）实现快速全局刹车；SSRT量化刹车速度；反应性/主动性/选择性三模式 **[NEW 2026-08-19]**
- 🟢 [误差相关负波 (ERN)](concepts/error-related-negativity.md) — 错误后~80ms、dACC/MCC 生成（iEEG证实）；Holroyd & Coles RL 框架（DA 负向 RPE → ERN）；是 FMθ 在错误时刻的相位重置表达；早于主观错误意识觉察 **[NEW 2026-08-23]**
- 🔵 [冲突监控假说](concepts/conflict-monitoring.md) — Botvinick 2001 框架；Hopfield 能量形式化冲突量；Gratton 效应行为预测；van Veen fMRI 响应冲突特异激活；被 EVC 框架扩展包含 **[NEW 2026-08-23]**
- 🟢 [dACC 冲突监控](concepts/dacc-conflict-monitoring.md) — dACC 通过检测并行响应通道冲突向 dlPFC 发出认知控制增强信号；ERN/N2 成分；导航页指向 anterior-cingulate-cortex 和 conflict-monitoring 主页 **[NEW 2026-09-03（填补悬空引用）]**
- 🔵 [控制期望价值 (EVC)](concepts/expected-value-of-control.md) — Shenhav 2013 规范框架；EVC = Σ(收益×概率) − 努力成本；dACC 统一处理错误/冲突/努力/奖励信号；vs dlPFC 执行分工；额外预测奖励效果 **[NEW 2026-08-23]**
- 🔵 [前额叶中线θ振荡 (FMθ)](concepts/frontal-midline-theta.md) — 4–8Hz，来源 dACC/MCC+preSMA；ERN/N2/FRN 共享θ谱特征；11项跨区同步复制；FMθ→STN同步=冲突驱动反应抑制；θ功率预测 Gratton 效应 **[NEW 2026-08-23]**
- 🟢 [停止信号任务](concepts/stop-signal-task.md) — 量化反应抑制的标准实验范式；独立赛马模型（Go vs Stop过程竞赛）；SSRT = 中位RT(Go) - 平均SSD；正常值约200-250 ms **[NEW 2026-08-19]**
- 🟢 [超直接通路](concepts/hyperdirect-pathway.md) — rIFG/preSMA→STN单突触直接制动回路（2.2 ms，~25 m/s）；跳过纹状体；STN→GPi发散投射产生全局运动抑制；与间接通路形成速度vs精度互补 **[NEW 2026-08-19]**
- 🟢 [γ振荡（30–80 Hz）](concepts/gamma-oscillations.md) — ING（纯抑制网络）与 PING（兴奋-抑制反馈）双机制；GABA-A τ_decay 是振荡频率的分子时钟（τ≈5ms→快γ，τ≈15ms→慢γ）；Sohal/Cardin 2009 光遗传学因果证明；PV/SST 双贡献；精神分裂症 GAD67 级联 **[NEW 2026-06-05 · 修订 rev4 2026-07-20]**
- 🔵 [意识点燃](concepts/consciousness-ignition.md) — 全有全无的非线性临界翻转；~270-300ms 前额顶叶激活；注意双要求机制；P3b EEG标志（地位存疑）；GWT核心机制节点 **[修订 2026-05-31]**
- 🔵 [注意瞬盲](concepts/attentional-blink.md) — GWT 最直接的有/无意识分叉检验；RSVP T1 后 200–500ms 内 T2 感知抑制；感觉处理相同条件下 ~270ms 前额顶叶神经分叉（Sergent 2005）；填补 COGITATE 遗留的方法论缺口 **[NEW 2026-05-31]**
- 🟡 [世界模型](concepts/world-model.md) — 大脑对外部世界和自身状态维护的当前最佳贝叶斯估计；八层分层贝叶斯预测机器架构；五月月报整合后修订 **[修订 2026-05-31]**
- 🟢 [变分自编码器](concepts/variational-autoencoder.md) — Kingma & Welling 2014的深度生成模型；ELBO（重建误差 + KL散度）目标与弗里斯顿变分自由能数学等价；编码器≈识别模型 $q(z|x)$，解码器≈生成模型 $p(x|z)$；两者都在解同一个贝叶斯推理问题 **[NEW 2026-07-13]**
- 🟢 [腹侧视觉流](concepts/ventral-visual-stream.md) — V1→V2→V4→IT层级；"解开纠缠"核心计算任务；前馈核心+循环调制；IT线性可分性；困难图像需要额外~30ms循环处理（Kar 2019）**[修订 2026-08-30 rev2→rev3]**
- 🟢 [背侧视觉流](concepts/dorsal-visual-stream.md) — vision-for-action；V1→MT/V5→PPC→前运动皮层；自我中心坐标；D.F.双离解案例；背背侧（reaching）/腹背侧（grasping）双路；Ritchie 2024 branching heterarchy 更新**[NEW 2026-08-30]**
- 🟢 [视觉物体识别](concepts/object-recognition.md) — 解缠假说的核心计算目标；种群线性可分性（vs 祖母细胞）；无监督时间连续性学习；IT线性可读性（90%+准确率）；目标驱动CNN r=0.78**[NEW 2026-08-29]**
- 🔵 [CNN–视觉皮层类比](concepts/cnn-visual-cortex-analogy.md) — 目标驱动CNN与视觉皮层层级的系统性类比；性能-IT预测力相关（r=0.78，Yamins 2014）；三个崩溃裂缝：循环连接/形状偏见/对抗样本；课程脊柱12第三篇 **[NEW 2026-07-14]**
- 🟢 [Transformer 自注意力（Q/K/V 机制）](concepts/transformer-self-attention.md) — Attention(Q,K,V)=softmax(QK^T/√d_k)V；现代Hopfield网络更新规则=单头注意力（Ramsauer 2020）；FEF/IPS→Query，V4/IT→Key/Value；softmax vs 除法归一化的根本差异（Reynolds & Heeger 2009）；6大断裂点（时间动力学/局部赫布/眼动耦合/多头生物对应/归一化形式/循环连接）；课程脊柱12第四篇 **[NEW 2026-07-15]**
- 🔵 [时间层级编码](concepts/temporal-hierarchy.md) — 大脑在从纳秒到终身的12个数量级时间尺度上并行运行的计算机制全谱；从SNARE融合到威胁记忆的多层架构 **[NEW 2026-05-31]**
- 🟡 [嵌套竞争-遴选架构](concepts/competition-selection-principle.md) — 大脑在突触→细胞→回路→系统→认知五个层次通过竞争决定"什么值得记住"；与嵌套时间编码层级互补；第二周综合分析框架 **[NEW 2026-06-06]**
- 🟢 [多巴胺奖励预测误差（DA-RPE）](concepts/dopamine-reward-prediction-error.md) — VTA/SNc DA 神经元编码"实际 − 预期"奖励误差；TD学习的神经底物；D1/D2分化；三因素规则的广播信号 **[NEW 2026-06-07]**
- 🔵 [三因素学习规则](concepts/three-factor-learning-rule.md) — Δw = (pre × post) × M；多巴胺/ACh/NE 作为第三因素；填补 hebbian-learning 悬空引用；纹状体直接实验验证 **[NEW 2026-06-07]**
- 🔵 [突触标记与捕获（STC）](concepts/synaptic-tagging-capture.md) — Hebbian 标签（~1-2h）+ DA-PRP 捕获 → E-LTP 升级为 L-LTP；解决三因素规则的时间延迟难题；LC-DA（非VTA）是行为标记 PRPs 合成的主要触发者（Takeuchi 2016, Moncada 2007）**[修订 rev2 2026-07-11]**
- 🟡 [蓝斑-海马多巴胺系统（LC-DA）](concepts/lc-hippocampus-dopamine.md) — LC TH⁺ 末梢（非VTA）是海马dCA1 DA的主要来源；D1/D5调控记忆持续性（非编码）；行为标记（新颖→LC-DA→PRPs→STC）；记忆联结（~6h时间窗，LC→dCA1 D1/D5依赖）；与GC-NE应激记忆系统互补 **[NEW 2026-07-11]**
- 🔵 [Actor-Critic架构（基底节）](concepts/actor-critic-brain.md) — VTA/SNc=TD误差δ广播；NAc/腹侧纹状体=Critic价值估计；背侧纹状体D1-MSN=Actor Go / D2-MSN=Actor No-Go；DA双向读出设计（D1兴奋/D2抑制）**[NEW 2026-07-12]**
- 🟡 [分布式强化学习与多巴胺编码](concepts/distributional-rl-dopamine.md) — 不同VTA DA神经元以不对称RPE缩放编码奖励分布分位数；大脑早于AI独立实现分布式RL计算；Dabney 2020 小鼠VTA单细胞记录 **[NEW 2026-07-12]**
- 🔵 [模型-基与模型-无强化学习（双系统）](concepts/model-based-model-free.md) — DMS支持MB（目标导向/灵活）；DLS支持MF（习惯性/快速）；结果贬值测试区分双系统；应激→从MB切换到MF；OCD/成瘾/抑郁的计算框架 **[NEW 2026-07-12]**

- 🔵 [三方突触](concepts/tripartite-synapse.md) — Araque 1999 框架；突触前+突触后+星形胶质细胞 PAPs 三元功能单元；双向神经元-胶质细胞信号；LTP/LTD 的三方必要性因果证明（Henneberger 2010）**[NEW 2026-07-02]**
- 🔵 [D-丝氨酸](concepts/d-serine.md) — NMDA 受体 GluN1 协同激动剂（而非甘氨酸）；星形胶质细胞丝氨酸消旋酶合成；Ca²⁺ 依赖释放；切断 D-丝氨酸 → LTP 完全消失（Henneberger 2010）**[NEW 2026-07-02]**
- 🔵 [胶质递质](concepts/gliotransmitter.md) — 星形胶质细胞释放的 D-丝氨酸/ATP/谷氨酸；三种释放机制（囊泡胞吐/VRAC/connexin）；争议：谷氨酸胞吐在生理条件下的真实性（C-2026-07-02-01 open）**[NEW 2026-07-02·medium confidence]**
- 🟢 [星形胶质细胞钙信号](concepts/astrocyte-calcium-signaling.md) — mGluR→Gq→PLC→IP₃→ER Ca²⁺ 路径；钙波（connexin43 缝隙连接传播，15–27 μm/s）；门控 D-丝氨酸；Cornell-Bell 1990 奠基发现 **[NEW 2026-07-02]**
- 🟢 [谷氨酸-谷氨酰胺循环](concepts/glutamate-glutamine-cycle.md) — 星形胶质细胞 EAAT2 清除→GS 转化→SNAT 输出→神经元谷氨酰胺酶水解→递质再生；GLT-1 KO → 癫痫/神经元死亡；防兴奋毒性的代谢基础 **[NEW 2026-07-02]**

- 🟢 [突触稳态缩放](concepts/synaptic-scaling.md) — Hebbian 可塑性的负反馈稳定器；乘法性等比调节所有 AMPA 受体（GluA2 通路，不同于 LTP 的 GluA1）；TNFα（星形胶质细胞）许可；视黄酸树突局部信号；Wu 2021 证明稳态缩放主动雕刻记忆特异性 **[NEW 2026-07-03]**
- 🟢 [AQP4（水通道蛋白4）](concepts/aqp4.md) — 脑内表达量最高的水通道；高度极化富集于星形胶质细胞终足（密度约10倍于其他胶质膜区）；CSF-ISF 对流的分子水门；AQP4 KO→70% 清除效率下降；AQP4 去极化是衰老脑胶质淋巴功能下降的分子基础；SNTA1/M23亚型维持极化分布 **[NEW 2026-07-06]**
- 🟢 [稳态可塑性](concepts/homeostatic-plasticity.md) — 突触缩放+内在兴奋性+突触前稳态三大类型；时间尺度隔离（小时/天 vs 秒/分）；为 Hebbian 规则提供运行前提；是 E/I 平衡的慢速补偿机制 **[NEW 2026-07-03 · 修订 2026-07-04]**
- 🔵 [兴奋-抑制平衡（E/I 平衡）](concepts/ei-balance.md) — 皮层回路信噪比控制机制；PV+/SST+/VIP+ 三类中间神经元分工维持；失衡是 ASD/精神分裂症/癫痫的共同汇流点；多维度（不同细胞类型→不同靶点），非单一数字 **[NEW 2026-07-04]**
- 🟢 [围神经元网（PNNs）](concepts/perineuronal-nets.md) — 包裹 PV+ 细胞的细胞外基质网络（aggrecan+透明质酸+连接蛋白）；OTX2 正反馈驱动 PV 成熟；固化 AMPA 受体、关闭发育关键期；ChABC 处理可逆转（动物） **[NEW 2026-07-04]**

- 🟢 [背侧注意网络（DAN）](concepts/dorsal-attention-network.md) — FEF+IPS 构成目标驱动注意控制系统；LIP 优先级地图整合视觉/扫视/认知信号；FEF 微电刺激因果增强对应视野区感知（Moore & Fallah 2004）；V4→V1 反馈是注意调制必要通道（Debes & Dragoi 2023）；乘法性增益调制（Treue & Trujillo 1999）；与 VAN（TPJ/VFC）构成双网络架构（Corbetta & Shulman 2002）**[NEW 2026-07-01]**
- 🟢 [偏置竞争模型](concepts/biased-competition.md) — 多刺激竞争有限皮层表征资源；注意通过 DAN 提供自上而下偏置信号倾斜竞争；乘法增益是偏置的计算形式；Desimone & Duncan 1995 经典理论框架 **[NEW 2026-07-01]**
- 🟢 [脑源性神经营养因子（BDNF）](concepts/bdnf.md) — 神经活动诱导释放的关键成长信号；TrkB三通路（PLCγ/ERK/Akt）；proBDNF→p75NTR与成熟BDNF→TrkB的双向开关；L-LTP的催化分子；SGZ神经发生的存活驱动力；AD早期受损靶点；Val66Met多态性；**rev3新增**：HD中BDNF-REST轴断裂（mHTT→REST入核→BDNF转录↓→MSN营养饥饿；Zuccato 2001/2005） **[NEW 2026-06-28 · 修订 rev3 2026-09-07]**（填补多页悬空引用）
- 🟡 [SGK3 介导的神经干细胞自噬性死亡](concepts/sgk3-autophagic-nsc-death.md) — 慢性应激/CORT→GR→SGK3→LC3→TRP53 降解→NSC 自噬性死亡（非凋亡）；TRP53 是 NSC 的存活守护蛋白；Atg7 KO 对应激诱导的 AHN 下降具有抗性；单实验室证据（Jung et al.），需独立复现 **[NEW 2026-08-27]**
- 🔵 [FKBP51（糖皮质激素受体伴侣蛋白）](concepts/fkbp51.md) — FKBP51 降低 GR 对 CORT 的亲和力并阻碍核转位；GR→FKBP5 转录→FKBP51 增加的超短负反馈环；*FKBP5* rs1360780 T 等位基因×童年创伤×成年 PTSD 三重交互（人类遗传最强证据之一）；SAFit2 体外促 NPC 增殖（>BDNF），体内应激弹性但体内神经发生效应不显著 **[NEW 2026-08-27]**
- 🟢 [糖皮质激素与应激记忆](concepts/glucocorticoid-stress-memory.md) — MR（高亲和力/快速评估）/GR（低亲和力/慢速巩固）双时相模型；BLA是全脑GC记忆增强的必要枢纽；GC+NE协同门控（β-AR阻断消除GC效应）；慢性GC→CA3选择性萎缩；急性应激→记忆系统切换至背侧纹状体；**新增**：慢性 GC 对 DG 神经发生的第四条损伤机制（BDNF↓+SGK3自噬+Wnt↓）+AHN-HPA双向反馈+FKBP51遗传调制（2026-08-27 rev2） **[NEW 2026-07-09 · 修订 rev2 2026-08-27]**
- 🟢 [Aβ寡聚体](concepts/amyloid-beta-oligomers.md) — AD的核心毒性物种；通过PrPC/NR2B/calcineurin/BDNF/tau五路并行瓦解海马LTP机器 **[NEW 2026-06-08]**
- 🟢 [polyglutamine毒性机制](concepts/polyglutamine-toxicity.md) — polyQ束超阈（HD CAG≥40）→β-折叠链间聚集→N端截短片段入核→包涵体毒性vs保护性争议；同时wtHtt功能丧失（REST隔离/BDNF运输/轴突运输）；包涵体毒性vs可溶性寡聚体毒性的核心争议；9种polyQ疾病共享机制骨架（SCA/SBMA/DRPLA） **[NEW 2026-09-07]**
- 🟢 [TDP-43 病理](concepts/tdp-43-pathology.md) — TDP-43 核清除（>97% ALS）是神经退行性病变统一病理标志；LCD/PLD 驱动从可逆液态小滴到不可逆固态聚集的相变；LOF 通过 UNC13A/STMN2 隐蔽外显子削弱突触囊泡释放和轴突再生；GOF 通过 RBP 测序、UPS 负担和朊蛋白样传播放大毒性 **[NEW 2026-09-11]**
- 🟡 [隐蔽外显子（Cryptic Exon）](concepts/cryptic-exon.md) — 正常被 TDP-43 抑制的内含子隐蔽序列；TDP-43 核清除→UNC13A（突触囊泡释放）和 STMN2（轴突再生）提前多腺苷酸化；2022 年 Nature 双文证明 UNC13A 隐蔽外显子是 TDP-43 LOF 的直接下游靶点；ALS 风险 SNP（~25% 人群频率）恰好位于 TDP-43 结合位点 **[NEW 2026-09-11]**
- 🟡 [RAN 翻译](concepts/ran-translation.md) — 非经典 ATG 非依赖性翻译起始；C9orf72 GGGGCC 重复在 6 个阅读框产生 5 种 DPR 蛋白；整合应激反应（ISR/eIF2α 磷酸化）悖论性上调 RAN 翻译效率——应激越重，毒性 DPR 越多 **[NEW 2026-09-11]**
- 🟡 [二肽重复蛋白（DPR）](concepts/dipeptide-repeat-proteins.md) — C9orf72 RAN 翻译的 5 种产物（poly-GA/GP/GR/PA/PR）；poly-GR/PR 毒性最强（精氨酸阳离子-LCD π 系统相互作用）；破坏核质运输、应激颗粒动力学和 TDP-43 稳态；尸检中 poly-GR 与神经退化区域及 TDP-43 特异共定位；DPR 分布（小脑/海马）与 ALS 损伤（脊髓）的空间解耦悖论 **[NEW 2026-09-11]**
- 🟢 [短时程突触可塑性（STP）](concepts/short-term-synaptic-plasticity.md) — 毫秒至分钟尺度内突触效率的使用依赖性动态变化；Syt7驱动易化（高p→低通）、RRP耗竭驱动抑制（低p→高通）；是工作记忆活动无声储存的分子基础 **[NEW 2026-06-10]**
- 🟢 [方向选择性](concepts/orientation-selectivity.md) — V1将LGN非定向圆对称输入转化为精确方向响应的核心计算；前馈LGN排列+E/I平衡+树突NMDA棘波三层机制；有/无方向柱物种均可达同等锐利选择性 **[NEW 2026-06-11]**
- 🟡 [突触聚类](concepts/synaptic-clustering.md) — 功能相似突触在同一树突分支聚集→NMDA棘波超线性整合→局部"与门"计算；Wilson 2016在雪貂V1提供首个体内直接证据；普遍性待验证 **[NEW 2026-06-11]**（填补 dendritic-computation 悬空引用）
- 🟢 [乙酰胆碱皮层调质](concepts/acetylcholine-cortex.md) — 基底前脑胆碱能系统通过M1/M2/nAChR受体增大皮层信噪比；肌碱受体介导V1注意调制（Herrero 2008）；相位性/紧张性双时间尺度；支持皮层去同步和工作记忆持续放电 **[NEW 2026-06-12]**
- 🟢 [皮层增益控制](concepts/gain-control.md) — 神经调质系统的核心输出：乘法性缩放皮层神经元输入-输出曲线；ACh通过M1、NE通过α2A/α1实现；注意调制的分子机制（修订5次）**[NEW 2026-06-12]**
- 🟢 [除法规范化](concepts/divisive-normalization.md) — 皮层规范计算：$R_j = \gamma D_j^n/(\sigma^n + \sum_k D_k^n)$；统一解释V1对比度饱和/交叉朝向抑制/环绕抑制；Reynolds & Heeger注意场规范化（注意场宽度决定对比度增益vs响应增益）；LIP价值规范化；Pareto分布下信息论最优编码；与Transformer Softmax的根本差异 **[NEW 2026-09-02]**
- 🟡 [多层增益控制架构](concepts/multi-timescale-plasticity.md) — STP（毫秒–秒层一）+ ACh/NE增益控制（秒–分钟层二）+ DA-RPE（分钟–小时层三）三层嵌套；Marder原则：调质环境决定功能回路；第三周综合框架 **[NEW 2026-05-30]**
- 🟢 [去甲肾上腺素与蓝斑系统](concepts/norepinephrine-locus-coeruleus.md) — 蓝斑LC通过相位性/紧张性双模式和倒U形NE浓度曲线优化皮层认知增益；α2A稳定PFC工作记忆；β受体促进情绪记忆LTP；选择性集合体拓扑组织；AD/PD早期LC退变（55%神经元丢失）**[NEW 2026-06-12 · 修订 rev4 2026-08-10]**
- 🔵 [5-HT自受体与SSRI延迟起效](concepts/5-ht-autoreceptor.md) — 5-HT1A树突自受体负反馈在急性期抵消SSRI效果；14天后自受体脱敏解除制动；皮质5-HT1A/2A功能拮抗；pindolol加速起效的临床证据 **[NEW 2026-06-13]**
- 🔴 [海马神经发生](concepts/hippocampal-neurogenesis.md) — 啮齿类SGZ持续神经发生（证据充分）；阻断神经发生消除SSRI行为效果；人类成人神经发生规模和存在性争议（Sorrells vs Boldrini 2018对立数据）**[NEW 2026-06-13 · 争议]**
- 🔵 [β振荡（13–30 Hz）](concepts/beta-oscillations.md) — "当前内部状态有效，无需更新"的振荡表达；三副面孔：运动ERD/PMBR（状态维持vs运动解锁）、感觉皮层γ前馈/β后向（28对灵长类视觉区域）、WM延迟期β爆发（130ms，背景态）+γ爆发（67ms，内容编码）；深层L5/6 β相位调控浅层L2/3 γ许可窗口（Bastos 2018）；PD中病理性β卡死；**[修订 rev2 2026-07-19]**
- 🟢 [恐惧条件反射](concepts/fear-conditioning.md) — 外侧杏仁核（LA）CS+US汇聚→NMDA巧合检测→CaMKII→AMPA插入→LA-LTP；与海马LTP分子机器完全同构；约20%LA神经元形成稀疏恐惧印迹；光遗传双向因果证明（Nabavi 2014）；**新增**：已巩固恐惧记忆在 CS 再激活后进入再巩固窗口，可被选择性修改**[修订 2026-07-10]**
- 🟢 [恐惧消退](concepts/fear-extinction.md) — 消退≠遗忘，而是IL皮层→腹侧ITC→CeM新抑制回路；与原始恐惧记忆竞争性共存；vmPFC激活预测消退回忆质量；PTSD=消退记忆提取失败；LA-VH θ相位差（~180°）预测消退记忆质量（Totty 2017，R=0.954）；再巩固窗口消退永久消除恐惧（Monfils 2009）；**rev7新增**：Milad 2009 fMRI 直接证据（PTSD消退回忆时vmPFC+海马激活↓）；Yi 2026 整合多靶点治疗框架**[修订 rev6→rev7 2026-08-26]**
- 🟡 [恐惧泛化](concepts/fear-generalization.md) — 条件性恐惧从原始 CS/情景扩散到相似或安全刺激的机制；核心通路：LC-NE→海马苔藓细胞抑制→颗粒细胞去抑制→情景集合重叠→BLA 共享激活（Jeong 2024，啮齿类，新兴证据）；5-HT 递质身份切换（谷氨酸→GABA）独立驱动泛化；PTSD 的核心症状之一 **[NEW 2026-08-26]**
- 🟢 [情绪调节](concepts/emotion-regulation.md) — 五类策略（认知重评/注意部署/情绪压制/习惯化消退/内感觉重估）；vmPFC 为情绪调节枢纽的前额叶-杏仁核-脑干多层级控制回路；主动推断视角（精度权重调整）；认知重评 vs 情绪压制长期代价对比 **[NEW 2026-08-25]**
- 🟢 [认知重评](concepts/cognitive-reappraisal.md) — 通过重解释事件含义改变情绪影响；vlPFC（语义重构）→vmPFC（情绪整合）→杏仁核（抑制）三层级回路；Steward 2021 DCM 量化 vmPFC→杏仁核负向有效连接；He 2023 TMS-fMRI 因果证明；重评 vs 压制（长期代价低）；有效性边界（感官驱动情绪效果有限） **[NEW 2026-08-25]**
- 🟢 [REM睡眠](concepts/rem-sleep.md) — 去甲肾上腺素真空（LC沉默）+θ振荡+杏仁核-海马θ同步；情绪记忆去饱和化（SFSR假说）；Boyce 2016光遗传因果证明REM θ是情境记忆必需条件；van der Helm 2011人类fMRI证实REM降低杏仁核情绪反应 **[NEW 2026-05-31]**
- 🟢 [睡眠-清醒翻转开关](concepts/flip-flop-switch-sleep-wake.md) — VLPO（GABA+甘丙肽）与AAS核团（LC/DRN/TMN/食欲素）的双稳互抑回路；解释睡眠-清醒为何是两个稳定极端态而非连续渐变；腺苷/PGD₂→VLPO激活→睡眠翻转；食欲素稳定清醒侧 **[NEW 2026-08-10]**
- 🟢 [食欲素（下丘脑泌素）与发作性睡病](concepts/orexin-hypocretin.md) — 外侧下丘脑8万神经元的"AAS总指挥"；缺失导致NT1（95%神经元丢失，HLA-DQB1*06:02）；OX2R激动剂danavorexton MWT改善11.1分（2024）；干细胞/基因治疗前景 **[NEW 2026-08-10]**
- 🟡 [情绪记忆去饱和化](concepts/emotional-memory-depotentiation.md) — REM睡眠NE真空→θ相位驱动LA突触选择性LTD→情绪色彩弱化、事实内容保留；Walker SFSR假说的机制底层；PTSD可能是去饱和化失败 **[NEW 2026-05-31]**
- 🔴 [Φ（整合信息度量）](concepts/phi-measure.md) — IIT 核心量；衡量系统最优分割时损失的因果信息量；NP-hard 计算；IIT 声称 Φ = 意识的量；COGITATE 2025 对相关机制预测构成挑战 **[NEW 2026-05-31]**
- 🔵 [后方皮层热区](concepts/posterior-cortical-hot-zone.md) — IIT 的解剖核心预测；V1/V4/MT/下颞叶等视觉-感觉联合皮层通过高整合连接产生意识内容；COGITATE 2025 对后方皮层内部同步（机制核心）构成挑战；Boly 2017 临床证据（完全额叶切除不影响意识）**[修订 2026-06-27]**
- 🟢 [意识的神经相关物（NCC）](concepts/neural-correlates-of-consciousness.md) — Crick & Koch 纲领；最小性+充分性约束；Koch 等（2016）三分法（内容特异 NCC/完整 NCC/使能 NCC）；COGITATE 2025 裁决摘要；无报告范式方法学意义 **[NEW 2026-06-27]**
- 🔵 [回路主题](concepts/circuit-motifs.md) — 神经回路中反复出现的小型拓扑模式（前馈回路、反馈循环、富人俱乐部），可能反映神经计算的基本功能需求；Drosophila连接组（Lin 2024）提供最大规模系统验证；蘑菇体15个学习隔室是典型实例 **[NEW 2026-06-18]**
- 🟢 [小世界网络](concepts/small-world-network.md) — 高聚类（局部模块化）+短路径（全局快速整合）的网络拓扑；果蝇全脑 σ=141；大脑跨尺度普遍存在；进化最优权衡假说；开放问题：微观vs宏观 σ 差距两个数量级的原因 **[NEW 2026-08-06]**
- 🔵 [同类相连](concepts/like-to-like-connectivity.md) — 小鼠视觉皮层布线规则：功能相似神经元优先互连（控制距离后仍显著）；MICrONS 2025系统验证（6,608连接对，四种投影类型含反馈连接）；AI验证（RNN自发涌现）；升级 emerging→mainstream（2026-09-13） **[NEW 2026-08-06 · 修订2026-09-13]**
- 🔵 [抑制性神经元隔室靶向特异性](concepts/inhibitory-compartmental-targeting.md) — MICrONS普查：163个抑制性神经元、427,294突触输出；四类靶向组（PeriTC近体/DistTC远端/SparTC稀疏/InhTC抑制性）；去抑制专家（InhTC-dist专靶DistTC, InhTC-peri专靶PeriTC，突触大69%）；20个运动组与PV/SST/VIP分类互补 **[NEW 2026-09-13]**
- 🟢 [转录组细胞类型](concepts/transcriptomic-cell-types.md) — 高维基因表达空间中可重复聚类的细胞群体；GABAergic跨区保守（~70%），谷氨酸能区域特异；转录因子组合编码细胞身份；BICCN多模态验证（转录组+ATAC+甲基化+空间）；全鼠脑5322聚类×全人脑461聚类的神经元分子宇宙 **[NEW 2026-07-25]**
- 🟢 [嗅觉受体（OR）基因家族](concepts/olfactory-receptor.md) — 哺乳动物最大GPCR基因家族；人类~400功能性成员；一细胞一受体/一受体一小球/组合编码三规则；cAMP→CNG通道→Cl⁻放大五步转导；Buck & Axel 1991诺贝尔奖基础 **[NEW 2026-07-26]**
- 🟢 [梨状皮层（初级嗅觉皮层）](concepts/piriform-cortex.md) — 三层古皮层；~10%稀疏激活；无拓扑图；CA3型递归联想网络（模式补全能力）；早期信号门控+全局抑制实现浓度不变性；感知层级（梨状→杏仁核→OFC）；直接接收嗅球经LOT的投射 **[NEW 2026-07-26]**
- 🟢 [音调拓扑图（Tonotopy）](concepts/tonotopic-map.md) — 频率→空间信息保真传递原则（耳蜗→CN→SOC→IC→MGB→A1）；A1/R Heschl回V形镜像；11场图双轴组织（音调×周期性梯度）；侧向抑制增强频率对比；成人可塑性重组（Merzenich组）；与方向选择性/网格细胞/场所细胞类比为皮层拓扑计算通用策略 **[NEW 2026-07-28]**
- 🟢 [多感觉整合](concepts/multisensory-integration.md) — 大脑跨视听触觉的两阶段感知推断：先因果推断（是否共享来源），再贝叶斯最优权重合并；上丘三条规则（空间/时间/逆效应性）；人类核心网络（STG/STS/丘脑枕核/脑岛）；麦格克效应；Ernst & Banks MLE验证 **[NEW 2026-07-30]**
- 🟡 [贝叶斯因果推断](concepts/bayesian-causal-inference.md) — 多感觉整合的核心计算框架：P(C=1)加权决定整合vs分离；"负偏移"独特预测（R²=0.97，Körding 2007）；与 MLE 的包含关系 **[NEW 2026-07-30]**
- 🟢 [逆效应性原则](concepts/inverse-effectiveness.md) — 上丘整合第三规则：弱刺激整合获益最大；NMDA 受体 Mg²⁺ 阻断-去除非线性机制（Bhatt 2016）；在最困难感知条件下提供最大跨模态补偿 **[NEW 2026-07-30]**
- 🔵 [时间绑定窗（TBW）](concepts/temporal-binding-window.md) — 多感觉整合的时间约束（视听±100-200ms）；ASD中TBW扩宽；候选机制（皮层振荡相位/STS时间调谐）；与麦格克效应易感性相关 **[NEW 2026-07-30]**
- 🔵 [区间计时](concepts/interval-timing.md) — 神经系统测量毫秒至数十秒时间的机制：小脑橄榄小脑系统负责事件驱动精确计时，纹状体-丘脑-皮层回路负责节拍驱动的秒级区间计时，种群时钟从网络内在动力学涌现；多巴胺通过调节振荡频率改变"时钟速度"（标量特性）**[NEW 2026-07-31]**
- 🔵 [纹状体拍频模型（SBF）](concepts/striatal-beat-frequency.md) — 区间计时最有影响力的机制模型之一：大量皮层振荡子在区间开始时同步，随时间相位拉开形成唯一的"拍频图案"，纹状体 MSN 作为符合检测器读出该图案；多巴胺调节振荡频率→时钟速度；生物学噪声是标量特性的必要条件 **[NEW 2026-07-31]**
- 🟡 [种群时钟](concepts/population-clock.md) — 内在计时的现代形式：时间由神经群体活动在高维状态空间走过的轨迹编码（无需专用时钟元件）；神经序列（稀疏接力放电）比斜坡放电更灵活；纹状体序列性高于运动皮层；RNN 自发涌现相同结构 **[NEW 2026-07-31]**
- 🟡 [时间细胞](concepts/time-cells.md) — CA1海马神经元在延迟期特定时刻依次激发，形成"时间地图"；距离-时间解耦（Kraus 2013）；可缩放表征（Shimbo 2021缩放因子1.81）；MEC斜坡细胞+CA2→CA1回路提供时间输入；人类单细胞验证（Umbach 2020）；与空间地点细胞功能对称 **[NEW 2026-08-04]**
- 🟡 [时间情境模型（TCM）](concepts/temporal-context-model.md) — Howard & Eichenbaum 2013提出：海马维持缓慢漂移的内部时间情境向量（t(τ)），自然解释近因效应和时间相邻效应；时间细胞是其物理实现候选；Q-tc-01：CA2/MEC是否是TCM内部"时钟"的神经底物？ **[NEW 2026-08-04]**
- 🔵 [CA2 区（海马第二角）](concepts/ca2-hippocampus.md) — 海马最小亚区（RGS14/PCP4/Avpr1b 分子标记）；三功能枢纽：社会记忆专用基底（Hitti 2014）/ CA1 时间序列组织者（MacDonald & Tonegawa 2021，~48% 时间细胞依赖）/ SWR 主要触发者（Oliva 2016，SWR 前 20–30ms 先行放电）；LTP 抗性由 RGS14 维持，mGluR-LTD 实现社会情境专用可塑性；新增：Avpr1b直接通路+OTR经SuM间接通路双重门控（2026-08-16 rev2）**[NEW 2026-08-14]**
- 🔵 [社会记忆](concepts/social-memory.md) — 识别并记住曾见过的同类；CA2 亚区作为专用神经底物（TeNT 灭活 CA2 选择性消除社会记忆，空间/恐惧记忆正常）；Avpr1b/催产素门控的 CA2 特异性突触增强；mGluR-LTD（而非 LTP）是信息存储机制（Samadi 2023）；新增：OXT五条专化路径的系统视角（2026-08-16 rev2）**[NEW 2026-08-14]**
- 🟢 [加压素（精氨酸加压素，AVP）](concepts/vasopressin.md) — 与催产素仅差2 aa的九肽；V1aR（VP配对联结·Gq/11）/V1bR（CA2攻击触发·CA2→LS→VMH）/V2R（肾水重吸收）三受体系统；AVPR1A RS3微卫星决定物种配对策略；Lim 2004单基因草甸田鼠实验；Gobrogge 2009 AH-V1aR选择性攻击；Leroy 2018 CA2-V1bR→LS→VMH攻击回路；"受体密度地图"而非"分子浓度"决定社会命运 **[NEW 2026-08-17]**
- 🟢 [催产素](concepts/oxytocin.md) — 下丘脑PVN/SON合成的九肽神经肽；OTR/Gq/11 GPCR；五条专化投射：①PVH→SuM→CA2（社会识别记忆）、②PVN→NAc（社会奖赏/配对联结）、③PVN→CeA（恐惧抑制/情绪辨别）、④SON→LS（哺乳期社会恐惧）、⑤aPVN→BNST（应激社交调制）；"社会凸显假说"解释双面性；非"爱的激素"而是多路社会调制器 **[NEW 2026-08-16]**
- 🟡 [乳头丘脑上核（SuM）](concepts/supramammillary-nucleus.md) — 下丘脑后部核团；双重功能：θ节律起搏器 + 催产素中继站（OTR⁺谷氨酸能神经元→CA2）；PVH→SuM→CA2路径是2024年新发现的社会识别记忆间接通路（Thirtamara Rajamani 2024）**[NEW 2026-08-16]**

- 🟢 [伤害感受器（Nociceptor）](concepts/nociceptor.md) — 专职感知有害刺激（高温/强机械力/有害化学物）的感觉神经元亚群；TRP家族通道（TRPV1热/辣 43°C、TRPA1化学/寒冷 <15°C、TRPM8凉感）；Nav1.7/1.8/1.9动作电位触发；Aδ（快速尖痛）vs C纤维（慢速弥散痛）双时程系统；外周致敏机制（PGE2/缓激肽/NGF→TRPV1阈值降低）**[NEW 2026-08-02]**
- 🔵 [闸门控制理论](concepts/gate-control-theory.md) — Melzack & Wall 1965提出的脊髓痛觉调控框架；Koch 2018在分子细胞层面验证：DYN+抑制性神经元（接收Aβ→压制PKCγ+）/PKCγ+兴奋性神经元（allodynia节点）/SOM+兴奋性神经元；KCC2下调→GABA兴奋→闸门失控；PAG-RVM下行控制 **[NEW 2026-08-02]**
- 🟢 [中枢敏化（Central Sensitization）](concepts/central-sensitization.md) — 慢性疼痛的核心神经可塑性机制；NMDA受体→Ca²⁺→多激酶级联（MAPK/PKC/Src）→突触效能持久增强（wind-up/脊髓LTP-like）；小胶质细胞-BDNF→KCC2下调→GABA兴奋化正反馈；与海马LTP同源机制发生在"错误的地方" **[NEW 2026-08-02]**
- 🟢 [安慰剂镇痛（Placebo Analgesia）](concepts/placebo-analgesia.md) — PFC→rACC→PAG→RVM→脊髓下行阿片回路将心理期望转化为真实止痛信号；纳洛酮逆转证明内源性阿片依赖（Levine 1978）；Zubieta 2005 PET直接测量rACC μ-OR激活（r=-0.87）；Eippert 2009 fMRI rACC-PAG耦合纳洛酮消除；双过程模型（期望+条件反射）；Nocebo效应通过CCK路径形成镜像促痛 **[NEW 2026-08-03]**
- 🟢 [内源性阿片系统（Endogenous Opioid System）](concepts/endogenous-opioid-system.md) — μ/κ/δ三类受体（Gi/o→AC↓→cAMP↓→K⁺开放→超极化）；β-内啡肽（弓形核）/脑啡肽/强啡肽三类阿片肽；PAG-RVM-脊髓三级下行镇痛通路；[¹¹C]卡芬太尼PET活体直接测量；吗啡模拟内源性SIA（应激诱导镇痛）的分子底物 **[NEW 2026-08-03]**
- 🟢 [Nocebo效应](concepts/nocebo-effect.md) — 负向期望→主观疼痛增强；CCK-A/B拮抗剂（丙谷胺）可阻断——与安慰剂阿片路径形成双路径分离；医源性nocebo（负面预期语言即增加术后疼痛）；开放标签安慰剂显示知情者仍可触发条件性镇痛 **[NEW 2026-08-03]**
- 🟢 [内源性大麻素系统（Endocannabinoid System）](concepts/endocannabinoid-system.md) — 脑内最主要逆行突触调制系统；2-AG（DGLα合成/MAGL降解，全激动剂）和 AEA（NAPE-PLD合成/FAAH降解，TRPV1全激动剂）；CB1R Gβγ→Cav2.2（DSI短时程）+ Gαi→RIM1α（eCB-LTD长时程）双通路；CCK⁺ GABA 能中间神经元为主要靶点；杏仁核 AEA-FAAH 轴调控恐惧消退（FAAH 抑制剂 PTSD 靶点）；THC 弥散激活 CB1R 导致逆行调控失真；**rev2新增**：NAc壳区享乐热点AEA→CB1R→liking增强（依赖阿片信号耦合），社会互动→NAc内eCB升高，CB1R拮抗阻断社会CPP **[修订rev2 2026-08-20]**
- 🟢 [激励显著性（Incentive Salience）](concepts/incentive-salience.md) — Berridge-Robinson 1993提出的"wanting vs liking"框架：多巴胺系统赋予刺激趋近动机（wanting），而非享乐快感（liking）；多巴胺耗竭消除食物seeking但保留liking（orofacial reactions）；激励敏化理论解释成瘾者"停不下来却不快乐"；aberrant salience解释精神分裂症幻觉/妄想形成；anhedonia区分（wanting vs liking损害的不同临床含义）**[NEW 2026-08-20]**
- 🟢 [内感觉（Interoception）](concepts/interoception.md) — 大脑对身体内部生理状态的感知系统；专属解剖通路（脊髓 lamina I → VMpo → 后岛，独立于外感觉 VPM→S1 路径）；后→前梯度处理（原始生理参数→预测误差→主观感受）；EPIC 预测编码模型（Barrett 2015：感受=预测+实际信号约束）；内感觉精确度个体差异（AIC 激活预测 BDT 心跳/呼吸准确性）；主动推断维度（通过自主神经调节身体以符合预测）**[NEW 2026-08-22]**
- 🟢 [价值决策（Value-Based Decision Making）](concepts/value-based-decision-making.md) — 大脑通过OFC的三类价值神经元（offer value/chosen value/taste cells）显式表征并比较选项主观效用；BLA-OFC双向回路是结果特异性价值记忆的读写系统（lOFC→BLA写入/mOFC→BLA读取）；OFC→DMS通路将价值信号转化为目标导向行动；dlPFC调制vmPFC价值权重实现自控（Hare 2009, PMID:19407204）；与习惯行为（外侧纹状体）形成目标导向vs习惯双系统分离 **[NEW 2026-08-21]**
- 🔵 [享乐热点（Hedonic Hotspot）](concepts/hedonic-hotspot.md) — NAc壳区前背侧内侧象限约1mm³的"快乐发生器"（大鼠，推算人脑约1cm³）；µ/δ/κ阿片受体激动剂均使sucrose liking反应翻倍；AEA在此位置增强liking但依赖内源性阿片信号同时激活（纳洛酮共注射完全阻断，Mitchell 2018）；多巴胺在热点内注射不增强liking（wanting-liking解剖分离的直接证据）；"情感键盘"（前appetitive/后aversive）可被应激重调 **[NEW 2026-08-20]**
- 🟡 [认知运动解离（CMD）](concepts/cognitive-motor-dissociation.md) — 行为检查显示无命令跟随，但任务型fMRI/EEG显示命令跟随神经信号的状态；约25%"无反应"DoC患者有CMD（Bodien NEJM 2024，n=353）；识别方法（"打网球"想象范式/P300 EEG/PCI≥0.31）；从根本上改变意识障碍的医疗决策伦理 **[NEW 2026-08-09]**
- 🟡 [前脑中间回路假说](concepts/mesocircuit-hypothesis.md) — Schiff（2009/2022）提出的VS/UWS自我维持机制：皮层损伤→纹状体失驱动→GPi脱抑制→中央丘脑过度抑制→皮层进一步去传入；关键：GPi脱抑制是可逆的；唑吡坦/金达胺素/中央丘脑DBS均通过打破该回路起效 **[NEW 2026-08-09]**

## motor（运动系统）

- 🟢 [后顶叶皮层（PPC）](systems/posterior-parietal-cortex.md) — 背侧流核心枢纽；LIP（空间显著性图谱，非眼动指令）；AIP（抓握手型预编码，optic ataxia）；VIP（近身空间防御）；MIP（到达计算）；背背侧→PMd/腹背侧→PMv 双路输出**[NEW 2026-08-30]**
- 🟢 [运动皮层](systems/motor-cortex.md) — M1/PMC/SMA分层组织；Betz细胞→皮质脊髓束；均质小人（手/嘴比例扭曲）；群体向量编码（Georgopoulos 1986）；旋转动力学（Churchland 2012）；输出零空间（Kaufman 2014）；**小脑-运动皮层闭环（修订2026-06-23）**
- 🟢 [小脑](systems/cerebellum.md) — 多样化预测处理器；三层皮层（颗粒/浦肯野/分子）+ DCN；PF-LTD多层可塑性；前向/逆向内部模型（Wolpert 1998）；双向微区（De Zeeuw 2021）；CCAS（认知情感综合征，Schmahmann 1998）**[修订rev4 2026-09-04]**
- 🟢 [深部小脑核（DCN）](systems/deep-cerebellar-nuclei.md) — 小脑唯一输出门控；三核团（顶核平衡/间位核时序/齿状核认知）+ 三细胞类型（谷氨酸能主力/GABA能短环路/甘氨酸能前庭）；去抑制为主要输出机制（Ishikawa 2014灵长类证据）；三层可塑性（突触LTP+内在兴奋性+PNN门控，CR率↑42%）；aDCN→VTA→纹状体饱腹感回路；齿状核→VM丘脑→前额叶认知路径**[NEW 2026-09-04]**
- 🔵 [前向模型](concepts/forward-model.md) — 利用传出拷贝预测运动感觉后果，使大脑超越反馈延迟；小脑的主要计算角色；逆向模型对称结构 **[NEW 2026-06-23]**
- 🟡 [群体向量编码](concepts/population-vector-coding.md) — M1方向编码的分布式机制；余弦调谐→群体向量精确预测；心理旋转时群体向量以732°/s旋转（Georgopoulos 1989）**[NEW 2026-06-21]**
- 🟡 [旋转动力学（运动皮层）](concepts/rotational-dynamics-motor.md) — 执行期神经群体以2–2.8 Hz在状态空间旋转；动力学引擎而非参数地图；RNN训练后自发出现相同结构 **[NEW 2026-06-21]**
- 🟡 [输出零空间](concepts/output-null-space.md) — 准备活动集中在对肌肉无效的零空间子空间（调谐比4.5×）；几何机制解释准备不触发运动 **[NEW 2026-06-21]**
- 🟡 [镜像神经元](circuits/mirror-neurons.md) — F5区17%神经元在执行+观察同一有目标动作时均激活（Gallese/Rizzolatti 1996）；F5/BA44同源；语言演化的动作理解假说 **[NEW 2026-06-21]**

## language（语言）

- 🟢 [语言网络（双流模型）](systems/language-network.md) — 腹侧流（声音→意义，双侧）+ 背侧流（声音→动作/句法，左侧主导）；"自然种"地位（Fedorenko 2024 NRN）；产出-理解共享同一套表征（Hu 2022）；1亿词LLM达最大对齐度（Hosseini 2024）；3–9岁儿童已与MD网络功能分离（Hiersche 2024）；腹侧流语义核心节点=双侧ATL（Pobric 2010，修订rev6 2026-09-05）**[修订rev6 2026-09-05]**
- 🔵 [颞叶前部（语义枢纽）](systems/anterior-temporal-lobe.md) — 双侧ATL是跨模态语义枢纽；感觉皮层连接质心（Bajada 2019）；rTMS因果证据（Pobric 2010）；SD→类别无关语义崩溃（Patterson 2007）；聚焦超声→GABA↓Glx↑灰质↑（Jung 2026）；双侧共享社会/非社会语义（Rouse 2024）**[NEW 2026-09-05]**
- 🟢 [Broca区（额叶下回）](systems/broca-area.md) — BA44（层级句法Merge，背侧流）vs BA45（语义工作记忆，腹侧流）；人类左BA44前部进化扩张1.64倍（Gallardo 2023）；3→4岁发育神经重组pSTS→BA44（Klein 2022）；MVPA分类图谱（Schell 2022）**[修订rev3 2026-08-07]**
- 🟢 [弓状束](concepts/arcuate-fasciculus.md) — 背侧流主干白质通路；三段解剖（额叶-顶叶-颞叶）；左侧优势；完整功能谱（右半球AF：社会认知/空间注意/音乐）；出生时低髓鞘化→随句法习得成熟；损伤→传导性失语；手术顶叶段风险最高（Vavassori 2023）**[修订rev2 2026-08-07]**
- 🟢 [背侧语言流](circuits/dorsal-language-stream.md) — A1→颞平面→Spt→弓状束→BA44；音韵缓冲+句法层级运算；左侧主导 **[NEW 2026-06-20]**
- 🟢 [腹侧语言流](circuits/ventral-language-stream.md) — A1→MTG/STS→角回→BA45；声音→词义；双侧；具身语义（工具→运动皮层，动物→视觉皮层） **[NEW 2026-06-20]**
- 🔴 [具身语义](concepts/embodied-semantics.md) — 词义神经基底是感觉运动皮层再激活（Hauk 2004 somatotopy；Pulvermüller 2005 TMS类别特异性因果效应）；面临复制危机（de Zubicaray 2026）；分级具身论+Hub-and-Spoke整合模型取代强具身论；ATL枢纽整合感觉运动辐条（Pobric 2010，修订rev2 2026-09-05）**[修订rev2 2026-09-05]**
- 🟢 [语义记忆](concepts/semantic-memory.md) — 枢纽-辐条模型：ATL跨模态枢纽+感觉运动辐条；与情景记忆双解离（SD vs 遗忘症）；Hebbian建立辐条；语义控制层（LIFG+pMTG）；CLS理论中与海马互补**[NEW 2026-09-05]**
- 🟢 [心智理论（ToM）](concepts/theory-of-mind.md) — 大脑推断他人信念/意图/情感的能力；核心三节点（pTPJ+mPFC+DMN dMPFC子系统）；假信念任务（Sally-Anne，4岁发展里程碑）；ASD 中 DMN 功能连接降低与 ToM 缺陷关联；GPT-4 ToM 测试的局限 **[NEW 2026-08-01]**
- 🔴 [镜像神经元系统](concepts/mirror-neuron-system.md) — Rizzolatti 1992 猕猴 F5 区 ~17% MNS 神经元；直接匹配假说（动作观察=运动共鸣）；Hickok "破碎镜子"批评（Broca 失语不损动作理解）；模拟理论 vs. 理论理论；MNS-ToM 因果关系争议（C-mirror-01 开放）**[NEW 2026-08-01 · 争议]**
- 🔵 [短语结构组装（Merge操作）](concepts/phrase-structure-building.md) — Chomsky Merge递归操作的神经基础（左BA44）；AⁿBⁿ层级规则选择性激活BA44（vs线性序列）；Schell 2022 MVPA：BA44分类grammatical词组/BA45分类semantic词组；Hu 2022精准fMRI：产出和理解共享Merge机制 **[NEW 2026-08-07]**
- 🟡 [语言的神经进化](concepts/language-evolution.md) — 人类左侧BA44前部额外扩张约1.64倍（Gallardo 2023，相对黑猩猩）；进化双重结构（后部BA44动作/前部BA44句法）；否定强版本镜像神经元语言假说；前向扩张模型；FOXP2分子层（T303N+N325S替换→程序性学习加速，Schreiweis 2014）**[修订 2026-08-12]**
- 🟢 [FOXP2](concepts/foxp2.md) — 人类语言关键转录因子；KE家族R553H突变→言语失用+语法障碍；forkhead域+锌指+亮氨酸拉链三模块；264+靶基因网络（CNTNAP2等）；R553H→dynactin1过表达→dynein-dynactin破坏→TrkB/BDNF受损→MSN树突不全→CAS；L6皮层丘脑（CT）神经元回路；人源化小鼠（T303N+N325S）加速程序性学习（修订2次）**[NEW 2026-08-12]**
- 🟢 [CNTNAP2 / CASPR2](concepts/cntnap2.md) — 神经素超家族跨膜粘附蛋白；人类最大基因之一（2.3 Mb，7q35）；FOXP2直接转录抑制CNTNAP2；成熟功能（旁节区Kv1锚定）+发育功能（PV+/CR+中间神经元迁移导引）；缺失→E/I失衡+振荡协调崩溃+OXT系统萎缩+PNN异常→语言-孤独症-癫痫三角共病 **[NEW 2026-08-15]**
- 🟢 [发声学习](concepts/vocal-learning.md) — 脊椎动物中独立进化多次的罕见能力；斑马雀Area X→DLM→LMAN→RA前馈可塑性回路；FoxP2在鸣唱时社会情境依赖性下调（练习↓稳定性→探索，表演↑稳定性）；FoxP2敲减→歌曲变异性过高无法稳定；与人类言语程序化的深度并行 **[NEW 2026-08-12]**
- 🟡 [大型语言模型与大脑的对齐](concepts/llm-brain-alignment.md) — GPT-2等LLM可预测语言网络fMRI响应；1亿词训练量达近最大对齐度（Hosseini 2024）；单向注意更接近大脑在线处理；表征相似性≠机制等同；Pasquiou 2023：左半球句法/语义空间分离高于右半球 **[NEW 2026-08-07]**

## systems（系统）

- 🟢 [视丘](systems/thalamus.md) — 感觉门控（TRN 注意探照灯）+ 皮层间中转（高次核：Pulvinar-V1、MD-PFC）+ 意识状态维持（CM-Pf）；双模放电（tonic/burst）是状态切换的分子基础；PFC→TRN 大型端钮：自上而下注意优先权 **[NEW 2026-06-03]**
- 🟢 [星形胶质细胞](systems/astrocyte.md) — 三方突触的第三方成员；PAPs 覆盖约 57% 海马兴奋性突触；EAAT2 清除 ~80% 突触谷氨酸；Ca²⁺ 信号（mGluR-IP₃-ER）门控 D-丝氨酸释放；LTP/LTD 不可或缺的第三方（Henneberger 2010）；人类星形胶质细胞覆盖约 200 万个突触 **[NEW 2026-07-02·知识库首次胶质细胞条目]**
- 🟢 [内嗅皮层（EC）](systems/entorhinal-cortex.md) — MEC（网格细胞/联合细胞）+ LEC（情境感觉）构成海马主要输入门户；MEC Layer II是路径整合坐标输出层；Braak分期：EC Layer II是AD最早受损皮层区域；空间记忆障碍先于语言退化的神经解剖基础；**rev2新增**：嗅球→LEC→海马通路及梨状皮层→EC→海马三突触回路（修订2次）
- 🟢 [齿状回](systems/dentate-gyrus.md) — 海马三突触回路第一站；EC → DG 5–10倍扩张（~20–30万→~100–200万颗粒细胞）；约 2–5% 颗粒细胞同时激活（极端稀疏编码）；多层 GABA 能抑制网络（篮状/HIPP/MOPP）主动雕刻稀疏性；苔藓细胞反馈抑制机制；成体神经发生场所；模式分离的主要神经基底 **[NEW 2026-08-28]**
- 🟢 [嗅球（主嗅觉球）](systems/olfactory-bulb.md) — 一受体一小球规则将OR激活映射为拓扑图；僧帽/簇状细胞经LOT直接投射至梨状皮层、杏仁核、内嗅皮层（无视丘中继，所有感觉系统唯一）；颗粒细胞树突-树突双向突触实现侧向抑制和对比度增强；β/γ振荡与梨状皮层同步 **[NEW 2026-07-26]**
- 🟢 [听觉皮层](systems/auditory-cortex.md) — 核心（A1+R，Heschl回V形镜像）-带状-旁带状三级层级；11张音调拓扑场图；腹侧"What"流（声音身份）+ 背侧"Where/How"流（空间/运动）；STG群体响应编码被注意者谱时特征（鸡尾酒会效应）；pSTG STRF重建语音（词语精确率0.89） **[NEW 2026-07-28]**
- 🟢 [耳蜗](systems/cochlea.md) — 基底膜行波实现频率-位置地点编码（cochleotopic map）；外毛细胞 Prestin 耳蜗放大器（+40–50 dB，Q因子×100）；内毛细胞 tip links / TMC1-TMC2 / Ca_v1.3 / ribbon synapse 机械-电换能级联；是听觉通路所有拓扑图的物理起点 **[NEW 2026-07-28]**
- 🟢 [初级躯体感觉皮层（S1）](systems/somatosensory-cortex.md) — 四亚区（3a/3b/1/2）×感觉小人（homunculus）×皮层放大因子；Merzenich系列实验确立经验依赖皮层地图可塑性（截指后邻指侵占/训练后表征扩张）；可塑性需要行为相关性（注意门控）；感觉剥夺重启成年皮层至关键期状态；**rev2新增：S1在痛觉中的感觉-分辨维度（脊髓丘脑束→VPL→S1）** **[修订rev2 2026-08-02]**
- 🔵 [痛觉矩阵（Pain Matrix）](systems/pain-matrix.md) — 脊髓丘脑束信号在脑内形成的多节点网络：S1/S2（感觉-分辨）+岛叶（内感受整合）+ACC（情感成分）+PFC（认知调控）；VPL→S1（新脊丘束）vs VMpo→岛叶/ACC（旁脊丘束）双路分叉；cingulotomy"知痛不感苦"经典分离；Wager NPS 多变量模式分析；慢性化中中脑边缘系统替代感觉网络 **[NEW 2026-08-02]**
- 🟢 [前扣带回（ACC）](systems/anterior-cingulate-cortex.md) — 疼痛情感成分的核心编码区（cingulotomy证明）；ACC→PAG下行镇痛通路；dACC/MCC认知控制（错误监测/冲突监控/努力决策/FMθ）；**rev5新增**：sgACC（BA25）作为"内脏运动皮层"（Price & Drevets 2010）——调节自主神经+神经调质基线；抑郁中sgACC持续过度激活；BA25白质纤维DBS治疗TRD（Mayberg 2005）**[修订 rev4→rev5 2026-08-25]**
- 🟢 [导水管周围灰质（PAG）](systems/periaqueductal-gray.md) — 内源性阿片镇痛系统核心枢纽；PAG电刺激→全身镇痛→纳洛酮阻断（内源性阿片因果证据）；vlPAG GABA能→去抑制机制；RVM ON/OFF-cells分工（镇痛/促痛）；ACC/下丘脑/杏仁核→PAG整合；急性疼痛OFF-cells主导→慢性疼痛ON-cells过度激活 **[NEW 2026-08-02]**
- 🟢 [上丘（SC）](systems/superior-colliculus.md) — 脊椎动物中脑多感觉整合的皮层下主节点；浅层（视网膜输入）vs 深层（视听触多感觉神经元）层状结构；Stein-Meredith 三条规则（空间/时间/逆效应性）；皮层（AES）依赖性使能；半盲恢复临床转化 **[NEW 2026-07-30]**
- 🟢 [基底节（区间计时视角）](systems/basal-ganglia.md) — 以区间计时为核心的系统层级视角：MSN ~1/3 显示斜坡放电；D1-MSN 递减/D2-MSN 递增的对立动力学（Bruce 2025 eLife 光遗传因果证据，R²=0.95 漂移扩散模型）；纹状体-丘脑-皮层节拍计时回路；帕金森病计时障碍机制 **[NEW 2026-07-31]**（另见 [[circuits/basal-ganglia]] 运动选择视角）
- 🟢 [颞顶联合区（TPJ）](systems/temporoparietal-junction.md) — 前-后轴分工：pTPJ（信念推断/视角转换，右侧化）vs aTPJ（注意定向，VAN 节点）；与 DAN（FEF/IPS）动态拮抗；进化：灵长类 TPJ 体积与社会群体大小正相关；临床：右 TPJ 损伤→偏侧空间忽视+社会认知障碍；TPJ 功能是否专一于 ToM 仍有争议（Q-tom-01）**[NEW 2026-08-01]**
- 🟢 [杏仁核](systems/amygdala.md) — 外侧核（LA）通过LTP写入恐惧记忆；ITC细胞是恐惧/消退的分子闸门；基底核（BA）中恐惧神经元与消退神经元双群竞争；中央核（CeA）驱动防御行为输出；与PFC（IL/PL）和海马形成情绪调控三角回路；GC+NE协同增强BLA恐惧记忆巩固（β-AR必要门控）；CRH在CeA独立于HPA轴的中枢效应；BLA-LA 再巩固去稳定化分子链；皮质内侧核Proust效应解剖基础；**rev7新增**：vmPFC→杏仁核负向有效连接（认知重评+恐惧消退双机制）；Steward 2021 DCM量化**[修订 rev6→rev7 2026-08-25]**
- 🟢 [HPA 轴（下丘脑-垂体-肾上腺轴）](systems/hpa-axis.md) — PVN-CRH→垂体-ACTH→肾上腺皮质-皮质醇级联；MR/GR双受体时间分离（MR快速评估/GR慢速巩固）；海马GR负反馈制动；**新增**：DG 新生神经元主动参与 HPA 负反馈（Snyder 2011）+FKBP51 遗传门控+AHN-HPA 双向恶性循环（2026-08-27 rev2）；慢性应激→CA3萎缩→负反馈减弱→HPA恶性循环；CRH在CeA的中枢独立效应 **[NEW 2026-07-09 · 修订 rev2 2026-08-27]**
- 🟢 [伏隔核（Nucleus Accumbens, NAc）](systems/nucleus-accumbens.md) — 腹侧纹状体的动机计算枢纽；D1/D2 MSN时程效应（短暂激活均→奖赏，持续激活均→厌恶，Soares-Cunha 2020打破经典D1=奖赏/D2=厌恶二分法）；享乐热点（壳区前内侧~1mm³，阿片→liking翻倍，eCB→liking需阿片协同，多巴胺在此不增强liking）；社会奖赏专用接口（OTR+MOR正向/KOR负向/eCB正向的NAc壳区四系统整合）；多路输入：VTA-DA（wanting）/PFC-Glu（认知控制）/杏仁核BLA（情感价值）/海马（情境）/PVN-OXT（社会特异性门控）；NAc DBS用于难治性抑郁（~40%反应率）**[NEW 2026-08-20]**
- 🟢 [眶额皮层（OFC）](systems/orbitofrontal-cortex.md) — 额叶最腹侧的新皮层区域；三类功能神经元（提案/选定/效用价值细胞）构成决策流水线；BLA-OFC双向回路是目标导向价值学习的神经基础（lOFC→BLA写入/mOFC→BLA读取）；OFC→DMS投射将价值信号转化为行动（Gore 2023光遗传学因果）；lOFC驱动感觉皮层重映射支持逆向学习；价值代码纵向稳定（Zhang 2024双光子）**[NEW 2026-08-21]**
- 🟢 [岛叶皮层（Insular Cortex）](systems/insular-cortex.md) — 藏于外侧裂深处的多层级内感觉处理中枢；四区功能分化（后颗粒岛体感拓扑/中岛预测误差/前岛主观感受生成/前岛极沉默性顶端控制）；VMpo→后岛专属内感觉通路（区别于 VPM→S1）；前岛含 VENs（体积4.6×，快速远程同步，与 alexithymia 关联）；EPIC 预测编码模型（Barrett 2015）与 IMAC 三层计算模型（Fermin 2022）；显著性网络（岛叶-ACC）；躯体标记（岛叶→OFC/vmPFC）；精神疾病共同病理节点（抑郁/精分/成瘾）**[NEW 2026-08-22]**
- 🟢 [前额叶皮层（PFC）](systems/prefrontal-cortex.md) — dlPFC 第2/3/5层循环回路是工作记忆的关键脑区；PV-γ轴是认知控制的时序基础；rIFG/preSMA反应抑制（超直接通路）；vmPFC/OFC价值决策腹侧亚区；dlPFC认知弹性三重机制（混合选择性/群体动力学/振荡选通）；**rev7新增**：vmPFC作为情绪调节腹侧亚区（认知重评三层级+IL消退同源+sgACC轴+抑郁回路）**[修订 rev6→rev7 2026-08-25]**
- 🟢 [腹内侧前额叶皮层（vmPFC）](systems/vmPFC.md) — PFC情绪调节枢纽（BA10/11/12/25/32腹侧）；vlPFC→vmPFC→杏仁核三层级认知重评回路；IL/vmPFC→腹侧ITC→CeM恐惧消退回路；sgACC（BA25）"内脏运动皮层"自主神经调节轴；抑郁症vmPFC灰质减少+sgACC超激活；Mayberg 2005 BA25 DBS治疗TRD **[NEW 2026-08-25]**
- 🔵 [背外侧前额叶认知弹性](systems/dlpfc-cognitive-flexibility.md) — dlPFC 三重认知弹性机制：混合选择性（Rigotti 2013）高维编码支持任意规则组合；群体动力学（Mante 2013）正交子空间分离不同背景下的决策轨迹；振荡选通（Buschman 2012）beta激活/alpha抑制动态路由规则集群；BG门控（O'Reilly 2006）控制WM更新时机；前额叶前后轴层级（Badre 2009）；OCD认知僵化的系统级网络失调机制 **[NEW 2026-08-24]**
- 🟢 [初级视觉皮层（V1）](systems/v1-primary-visual-cortex.md) — 视觉信息皮层第一站；方向选择性从LGN非定向输入的从头计算；猫/猴方向柱 vs 小鼠盐-胡椒型组织均可达精确方向选择性；树突突触聚类增益层（Wilson 2016）；ACh通过肌碱受体放大V1注意调制（Herrero 2008）（修订2次）
- 🟢 [神经调质系统](systems/neuromodulator-systems.md) — 基底前脑ACh、蓝斑NE、中脑DA、中缝核5-HT四套弥散调质系统的总概述；编码"用什么模式处理信息"而非信息本身；Marder原则定位；AAS两通道架构与VTA枢纽（修订5次）**[NEW 2026-06-12]**
- 🟢 [上行激活系统（AAS）](systems/ascending-arousal-system.md) — 脑干五核团（LC/DRN/PPT-LDT/TMN/Orexin）经腹侧基底前脑路（主要）+背侧丘脑路（次要）激活皮层；PB/PC谷氨酸通路是关键必要节点（Fuller 2011）；VTA=dAAN枢纽；翻转开关架构 **[NEW 2026-08-10]**
- 🟢 [血清素-缝际核系统](systems/serotonin-raphe-system.md) — 约20-30万DRN/MRN 5-HT神经元向全脑广播；体积传输为主；14种5-HT受体；5-HT1A自受体的双重负反馈机制是SSRI延迟起效的核心 **[NEW 2026-06-13]**
- 🟢 [默认模式网络（DMN）](systems/default-mode-network.md) — 大脑内部模拟基础设施；Raichle 2001 发现"默认模式"；Fox 2005 DMN-TPN反相关；Andrews-Hanna 2011 双子系统（MTL子系统=情节记忆/场景构建；dMPFC子系统=心智化）；aMPFC+PCC枢纽节点；Buckner 2009 Aβ优先沉积枢纽节点；课程路线8（意识与自我）首篇 **[NEW 2026-06-16]**
- 🔵 [胶质淋巴系统](systems/glymphatic-system.md) — 大脑废物清洗网络：CSF 沿动脉旁间隙入流→星形胶质细胞终足 AQP4 穿越脑实质→静脉旁出流；蓝斑核 NE 振荡（~0.05 Hz）驱动血管慢性搏动为物理泵；NREM 深度睡眠期高效清除 Aβ 和 tau；AQP4 KO→70% 清除效率下降；衰老→三重削弱→AD 恶性循环；人类随机交叉试验直接验证（Dagum 2026）**[NEW 2026-07-06]**

## methods（方法）

- 🟢 [光遗传学](methods/optogenetics.md) — ChR2（蓝光激活）+ NpHR/Arch（黄光沉默）+ Cre-lox/c-fos-tTA 遗传特异性递送，提供毫秒精度因果回路解析；印迹细胞/假记忆/效价翻转实验的核心工具 **[NEW 2026-06-09]**
- 🟢 [扰动复杂性指数（PCI）](methods/perturbational-complexity-index.md) — IIT 的临床代理工具；TMS 扰动 + EEG 记录 + Lempel-Ziv 复杂度算法；区分清醒/NREM/麻醉/植物状态/最小意识状态；Casali 2013 奠基，多中心验证 **[NEW 2026-05-31]**
- 🟢 [连接组学](methods/connectomics.md) — 用串行电子显微镜重建生命体所有神经元与突触连接的完整结构图谱；C. elegans（302神经元）→ 果蝇（139,255神经元，FlyWire 2024）→ 小鼠视觉皮层（MiCrONS 2025）；揭示小世界拓扑、富人俱乐部、同类相连布线规则；结构-功能鸿沟三大来源 **[修订 rev1→rev2 2026-08-06]**
- 🟡 [对抗性协作](methods/adversarial-collaboration.md) — 让对立理论家预注册具体预测与通过/失败标准，再按标准裁判；COGITATE 2025 是神经科学最大规模实践（256人，fMRI/MEG/iEEG，IIT vs GNWT）；同时挑战两理论核心机制预测 **[NEW 2026-05-31]**
- 🟢 [单细胞RNA测序（scRNA-seq）](methods/single-cell-rna-seq.md) — 液滴微流控+条形码+UMI单细胞基因组测序；snRNA-seq解决脑组织分离难题；UMAP降维+Leiden聚类揭示神经元转录组多样性；神经元分类学革命的核心技术平台 **[NEW 2026-07-25]**

## theories（理论）

- 🔵 [全局工作空间理论（GWT）](theories/global-workspace-theory.md) — 意识点燃机制；Dehaene-Changeux 神经工作空间；有意识知觉的全有全无广播事件；GWT vs IIT 2025 年对抗性合作 **[NEW 2026-05-30]**
- 🟡 [预测编码](theories/predictive-coding.md) — 皮层层级通过自上而下的预测反馈 + 自下而上的预测误差前馈实现贝叶斯推断；Rao & Ballard 1999 奠基模型；Bastos 2012 皮层分层映射（γ=误差前馈，α/β=预测反馈）；Keller 2012 V1感觉运动失配实验；注意=精度加权；与DA-RPE同一计算结构 **[修订 rev6 2026-07-13]**
- 🟡 [自由能原理](theories/free-energy-principle.md) — 弗里斯顿提出的统一大脑理论：大脑通过最小化变分自由能（感知+行动双路径）来减少惊奇；数学上等价于VAE的ELBO；新增：三层精度框架+AAS神经调质=精度硬件+DoC=精度路由失败 **[修订 rev2 2026-08-11]**
- 🟢 [时序差分学习（TD学习）](theories/td-learning.md) — Sutton & Barto 1988经典算法；δ(t)=r(t)+γV(t+1)−V(t)；从标准TD到信念状态TD（mPFC+海马处理状态不确定性）再到分布式TD（不同分位数学习器）的三级发展；深度强化学习（DQN）的理论基础 **[NEW 2026-07-12]**
- 🔴 [整合信息理论（IIT）](theories/integrated-information-theory.md) — 意识 = Φ（整合信息量）；五公理推导物理约束；意识基质在后方皮层热区（而非前额叶）；小脑/视网膜低 Φ 预测与临床一致；COGITATE 2025 挑战核心机制预测（后方皮层同步缺失）；泛心论蕴含；前馈网络 Φ ≈ 0；与多重发生器假说的关系 **[修订 rev4 2026-08-08 · 争议]**
- ⚪ [多重发生器假说（MGH）](theories/multiple-generator-hypothesis.md) — 意识可能由多个并行发生器（后方整合+前额广播+再入反馈）共同产生；原则 vs 发生器的核心区分；IIT/GWT/RPT/HOT 可能各自描述了真实存在的不同发生器；为"所有理论都被部分支持部分否定"格局提供相容框架；目前属于理论推断，尚无专门检验实验 **[NEW 2026-08-08 · 推测性]**
- 🟢 [主动推断](concepts/active-inference.md) — 感知（更新内部模型）和行动（改变感觉输入）统一为最小化变分自由能；期望自由能分解为外在价值（利用）+认知价值（探索）；精度三层框架：ACh感觉精度/NE转换精度/DA策略精度；精度失调统一解释精神分裂/ASD/PD/MND **[NEW 2026-08-11]**
- 🟡 [精度加权](concepts/precision-weighting.md) — 预测误差信号携带精度权重，注意力形式化为选择性提升误差精度；ACh/NE/DA分别实现三层精度（感觉/转换/策略）；2024直接实验证据（eLife ACh，Biol Psych NE）；精度失调疾病模型精确化（精神分裂/ASD/PD）**[修订 rev2 2026-08-11]**

## diseases（疾病）

- 🟢 [阿尔茨海默病](diseases/alzheimers-disease.md) — Aβ寡聚体通过5条并行通路瓦解海马突触LTP；突触密度（非斑块）与认知衰退相关r=0.96；早期突触沉默可逆；tau病理（NFT）比斑块更预测认知衰退（修订4次）**[NEW 2026-06-08 · 修订2026-06-29]**
- 🟢 [帕金森病](diseases/parkinsons-disease.md) — α-突触核蛋白聚集/路易小体/Braak分期；基底节直接/间接通路失衡（GPi过度活跃→丘脑抑制→运动减少）；β振荡病理状态；DA和DBS共享β→θ振荡切换治疗机制（Köhler 2024）**[NEW 2026-06-14]**
- 🟢 [亨廷顿病](diseases/huntingtons-disease.md) — HTT基因CAG重复≥40→polyQ展开→四重MSN选择性打击（BDNF-REST断裂/转录失调CBP/PGC-1α/NR2B兴奋毒性）；纹状体MSN >90%晚期退化；丁苯那嗪/氘丁苯那嗪症状控制；tominersen悖论；WVE-003等位基因选择性策略 **[NEW 2026-09-07 · 修订2026-09-09]**
- 🟢 [线粒体功能障碍](diseases/mitochondrial-dysfunction.md) — PD/AD/HD分别攻击Complex I/IV/II；ROS-mtDNA正反馈；Ca²⁺超载→MCU→mPTP→Cyt c→凋亡；DRP1病理性分裂；PINK1/Parkin线粒体自噬；神经元~4.7×10⁹ ATP/秒的高能耗决定结构性脆弱性 **[NEW 2026-09-09 · 填补图谱唯一悬空引用]**
- 🔵 [精神分裂症](diseases/schizophrenia.md) — PV-GAD67-γ 轴：NMDA 低活→PV 细胞（NR2A 高密度）损伤→GAD67 mRNA 下调→GABA 合成↓→PING 时序崩溃→γ 振荡减弱→WM 缺陷；多巴胺 D2 过度激活（阳性症状）与 D1 不足（阴性/认知症状）并存；高度多基因遗传（C4A 突触过度剪枝） **[NEW 2026-07-20]**
- 🔵 [意识障碍（DoC）](diseases/disorders-of-consciousness.md) — 严重脑损伤后觉醒和/或意识内容持续损害的临床综合征；昏迷→VS/UWS→MCS→CMD连续谱；前脑中间回路（GPi脱抑制→中央丘脑过度抑制→皮层去传入）；25%"无反应"患者有隐蔽意识（Bodien NEJM 2024）；多模态神经评估（任务型fMRI/EEG/PCI）正在重塑临床诊断标准和伦理框架 **[NEW 2026-08-09]**
- 🟢 [儿童言语失用症（CAS）](diseases/childhood-apraxia-of-speech.md) — 言语运动程序化选择性障碍（非肌力或发音器官问题）；遗传异质性：30+致病基因（Morgan 2024）；FOXP2经典病因链：R553H→dynactin1过表达→dynein-dynactin破坏→TrkB/BDNF受损→MSN树突不全→程序化失败；多基因CAS汇聚于共同转录调控通路 **[NEW 2026-08-12]**
- 🟢 [CNTNAP2 缺乏症 / CDFE 综合征](diseases/cntnap2-deficiency-cdfe.md) — 双等位CNTNAP2功能缺失→皮层发育不良-局灶性癫痫-语言退行-ASD-智力障碍五联征；Strauss 2006 Amish家系；动物模型（Peñagarikano 2011 Cell）复制核心表型；FOXP2→CNTNAP2轴将CAS与CDFE连接至共同遗传级联 **[NEW 2026-08-15]**
- 🟢 [创伤后应激障碍（PTSD）](diseases/ptsd.md) — 三角失调模型：杏仁核（过度激活）/vmPFC（沉默/消退刹车失效）/海马（萎缩+苔藓细胞受损→模式分离失败）；恐惧泛化是核心症状；两条治疗靶点（消退增强 vs 再巩固干预）；5-HT 递质身份切换新发现 **[NEW 2026-08-26]**
- 🟢 [肌萎缩侧索硬化症（ALS）](diseases/als-amyotrophic-lateral-sclerosis.md) — TDP-43 核清除是 ALS 统一病理标志（>97%）；C9orf72 三叉毒矛（LOF/RNA foci/DPR）；poly-GR/PR 毒性最强且与 TDP-43 特异共定位；UNC13A/STMN2 隐蔽外显子是 TDP-43 LOF 的关键下游；运动神经元四重脆弱性（超长轴突/低钙缓冲/高Ca²⁺通透AMPA/持续皮质驱动）；tofersen-SOD1-ALS 临床里程碑 **[NEW 2026-09-11]**

- 🟢 [tau 蛋白病理](concepts/tau-pathology.md) — Aβ诱发CDK5/p25+GSK-3β激酶风暴→tau过磷酸化（约25倍）→树突棘错位（TTLL6-spastin微管破坏）→突触毒性；PHF/SF cryo-EM结构（R3+R4核心，3.4Å）；Braak I-VI分期与朊蛋白样跨突触传播；FTD-MAPT证明tau独立神经毒性 **[NEW 2026-06-29]**

---

## 当前知识路线进度

| 课程主题 | 状态 |
|---------|------|
| 1. 神经元如何工作 | 🔵 进行中（已覆盖：AIS, 动作电位, 突触传递, NMDA/AMPA 受体, CaMKII, 树突计算, 锥体神经元, 电压门控钙通道, PV+/SST+/VIP+ 中间神经元, 去抑制回路, **LTD（长时程抑制）**, **短时程突触可塑性（STP）**, **神经调质 ACh/NE（2026-06-12）**, **血清素系统/5-HT1A自受体（2026-06-13）**, **小脑 LTD（2026-06-23）**；待覆盖：多巴胺系统深度） |
| 2. 神经网络微回路设计 | 🔵 进行中（已覆盖：PV+/SST+/VIP+ 中间神经元, 去抑制回路；待覆盖：皮层柱结构, 前馈/反馈抑制, 神经调质调节） |
| 3. 大脑如何编码世界 | 🔵 进行中（已覆盖：**场所细胞（2026-06-22 wiki建立）**, **网格细胞（2026-06-22 wiki建立）**, θ振荡/相位编码, **V1方向选择性（2026-06-11）**, **路径整合（2026-06-22）**, **运动编码-旋转动力学（2026-06-21）**, **小脑前向模型（2026-06-23）**, **耳蜗音调拓扑图×听觉皮层（2026-07-28）**；待覆盖：体感皮层, 时间表征）|
| 4. 学习和记忆 | 🔵 进行中（已覆盖：LTP, Hebb 规则, BTSP, 海马回路, 场所场形成, SWR 重播, 印迹细胞, 记忆巩固（系统层面）, **LTD**, **短时程突触可塑性（STP）**, **认知地图（2026-06-22）**；待覆盖：记忆提取机制、网格-场所转化精确机制）|
| 5. 认知控制 | 🔵 进行中（已覆盖：**工作记忆**、**奖励学习/三因素规则（2026-06-07）**、**注意/增益控制（ACh/NE，2026-06-12）**、**反应抑制/超直接通路（2026-08-19）**；待覆盖：执行控制、决策）|
| 6. 情绪与动机 | 🔵 进行中（已覆盖：多巴胺奖励系统、VTA/NAc/PFC 投射路线、**杏仁核恐惧记忆回路（2026-05-30）**、**恐惧条件反射/消退机制**；待覆盖：动机回路深度、恐惧情景结合（海马-杏仁核）、PTSD深度、下丘脑情绪调控）|
| 11. 疾病作为窗口 | 🔵 进行中（已覆盖：阿尔茨海默病（AD突触机制）、**帕金森病（基底节回路失衡/β振荡/DBS机制，2026-06-14）**、**精神分裂症（PV-GAD67-γ轴×NMDA低活×多巴胺双轴，2026-07-20）**；待覆盖：ASD、癫痫）|
| 8. 意识与自我 | 🔵 进行中（已覆盖：**默认模式网络（DMN）**（2026-06-16）、**全局工作空间理论 GWT + 意识点燃**（2026-05-30）、**整合信息理论 IIT + Φ + 后方皮层热区 + PCI**（2026-05-31）、**COGITATE预注册对决（2026-05-31）**、**注意瞬盲（2026-05-31，填补 COGITATE 方法论缺口）**；待覆盖：主动推断/自由能原理、自我参照处理、意识的神经相关物精细解析）|
| 10. 方法革命 | 🔵 开始（已覆盖：**光遗传学**；待覆盖：电生理、fMRI、钙成像、单细胞测序、空间转录组）|
| 9. Connectomics | 🔵 开始（已覆盖：**连接组学基础（C. elegans + Drosophila）**；待覆盖：小鼠皮层连接组、人脑功能连接组、Connectomics×AI集成）|
| 2, 7 | ⚪ 待开始 |
| 12. 人脑与AI比较 | 🔵 进行中（已覆盖：**多巴胺TD学习与深度RL的平行演化（2026-07-12）**；Actor-Critic基底节架构；分布式RL与DA群体编码；MB-MF双系统；**预测编码×自由能×VAE（2026-07-13）**：ELBO=变分自由能数学等价，局部赫布规则≈反向传播；待覆盖：Transformer注意力与大脑注意回路、大型语言模型与语言网络）|

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

**第89篇（2026-07-21）**：**海马的节律钟表：θ-γ跨频率耦合如何量化工作记忆容量**——揭示工作记忆 4±1 项容量上限的节律物理机制。核心贡献：(1) Lisman-Idiart 1995 容量分格模型：每个 θ 周期（约 125 ms）内嵌套约 4–6 个 γ 爆发（修订后），每个 γ 分格通过 ADP 维持一项记忆，θ/γ 比率即容量上限；(2) Axmacher 2010 人类颅内 EEG 直接证据：θ-γ PAC 随工作记忆负荷（1→3→5 项）系统性增强，个体 PAC 精度预测容量；(3) Colgin 2009 双通道路由：CA1 慢 γ（θ 波峰，CA3 自联想）/ 快 γ（θ 波谷，MEC 感觉）时分多路复用；(4) Wolinski 2018 定量预测：个体 θ 频率负相关工作记忆容量（慢 θ→更多 γ 循环→更大容量）；(5) Huang 2026 MEG 扩展：γ 爆发在连续 θ 相位编码导航序列，将 θ-γ 从"静态并行维持"扩展到"动态前向规划"。新建1个wiki页面（concepts/theta-gamma-coupling），修订3个wiki页面（theta-oscillations rev3→rev4、gamma-oscillations rev4→rev5、working-memory rev7→rev8），知识图谱161节点、989边，新增未解问题 Q-tgc-01/02/03，部分解答 Q-gamma-capacity 和 Q-wm-capacity-mechanism。

**第88篇（2026-07-20）**：**篮状细胞打出节拍：γ 振荡的双重生成机制与精神分裂症的细胞之谜**——从神经元网络的自发振荡到精神疾病的分子级联。核心贡献：(1) ING（Interneuron Network Gamma）完整机制——Whittington 1995体外实验奠基，GABA-A τ_decay 是振荡周期的分子时钟，纯 I-I 网络可自主产生 50-80 Hz 振荡；(2) PING（Pyramidal-Interneuron Network Gamma）的 E-I 反馈循环——锥体细胞→PV 细胞→回抑制，频率受 τ_decay + E→I 延迟共同决定；(3) Sohal 2009 和 Cardin 2009 的光遗传学因果证明——抑制 PV 细胞 → γ 功率减少+信噪比下降；40 Hz 驱动 FS 细胞 → 选择性 γ + 感觉相位门控；(4) SST+ 细胞的独立 γ 贡献（Antonoudiou 2020）——打破"γ 只依赖 PV+"的简化观点；(5) 精神分裂症完整分子级联——NMDA 低活（NR2A 偏好 PV 细胞）→ GAD67 mRNA 下调 → GABA 合成↓ → IPSP 幅度↓ → PING 时序精度崩溃 → γ 振荡减弱 → 工作记忆缺陷，是当前精神疾病-振荡机制研究中最清晰的多层次因果链。新建1个wiki页面（diseases/schizophrenia），修订2个wiki页面（concepts/gamma-oscillations rev3→rev4、circuits/pv-interneurons rev4→rev5），知识图谱160节点、977边，新增3个未解问题（Q-gamma-ping-ling-01、Q-gamma-sst-pv、Q-sz-dopamine-gaba-interface）。

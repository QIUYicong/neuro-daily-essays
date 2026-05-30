# Wiki 变更日志

> 每日固结步骤产生的 wiki 变更记录。新条目置于顶部。

---

## 2026-06-11（第三周·第 5 篇，文章 #19）

**源文章**：[[2026-06-11-v1-orientation-selectivity]] —《V1初级视觉皮层的方向选择性：从随机输入到精确编码》

**新建页面（3）**：
- `systems/v1-primary-visual-cortex.md`（初级视觉皮层V1）🟢 established / 置信度高 — 首个 systems 层视觉脑区页面；视觉信息皮层第一站；简单/复杂细胞区分（F1/F0）；方向柱/超柱/pinwheel（猫/猴，Ohki 2005 PMID:15660108）；盐-胡椒型组织（小鼠，Niell 2010 PMID:20810772）；三层方向选择性机制（前馈/E-I平衡/NMDA棘波）；树突突触聚类与OSI正相关（Wilson 2016 PMC5240628）；连接8个既有节点（dendritic-computation、nmda-receptor、pv-interneurons、sst-interneurons、prefrontal-cortex等）
- `concepts/orientation-selectivity.md`（方向选择性）🟢 established / 置信度高 — V1核心计算特性；OSI定量定义（HWHM约25-30°）；对比度不变性由E/I维持；三层机制（前馈LGN排列、E/I平衡网络、树突NMDA棘波聚类）；物种比较（猫/猴有方向柱 vs 小鼠盐-胡椒，OSI分布相似）；CNN Gabor滤波器收敛（Kindel 2019）；连接6个既有节点
- `concepts/synaptic-clustering.md`（突触聚类）🟡 emerging / 置信度中 — **填补 dendritic-computation 页面的长期悬空引用**；功能相似突触在同一树突分支聚集→NMDA棘波超线性整合；Wilson 2016（雪貂V1，双光子GCaMP6s）首次体内直接证据：聚类程度与OSI正相关，偏好方向热点2倍于非偏好方向；Smith 2013（PMID:24162850）独立验证；体外原理验证established，体内普遍性为emerging；开放问题：小鼠V1/海马/PFC中的聚类是否同样存在；连接5个既有节点

**修订页面（1）**：
- `neurons/dendritic-computation.md`（revision_count 3→4）：新增 V1 突触聚类体内证据节（Wilson 2016，雪貂V1双光子成像，OSI与聚类程度正相关，偏好方向NMDA棘波热点2倍）；部分解答 Q-synaptic-clustering-prevalence（体内存在，但物种/脑区普遍性仍open）；related 新增 synaptic-clustering, orientation-selectivity, v1-primary-visual-cortex；key_sources 新增 PMID:27383898；source_articles 新增 2026-06-11

**悬空引用新增（0）**：今日无新悬空引用（V1文章涉及概念均已在新建页面或既有页面中处理）。

**悬空引用解决（1）**：
- ~~`synaptic-clustering`~~ ✅ 已建立（concepts/synaptic-clustering.md）——自 2026-05-27 dendritic-computation 创建时起的悬空引用，历时14逻辑日

**矛盾登记（0）**：今日无新矛盾。两个现有开放矛盾（C-2026-05-24-01, C-2026-05-25-01）今日文献未直接涉及，状态不变。

**图谱更新**：
- 新节点：v1-primary-visual-cortex, orientation-selectivity, synaptic-clustering（47→50 总节点）
- 新边：13条（orientation-selectivity↔v1-primary-visual-cortex、orientation-selectivity→dendritic-computation、orientation-selectivity→nmda-receptor、orientation-selectivity→pv-interneurons、synaptic-clustering→dendritic-computation、synaptic-clustering→nmda-receptor、synaptic-clustering→orientation-selectivity、dendritic-computation→synaptic-clustering、v1-primary-visual-cortex→dendritic-computation、v1-primary-visual-cortex→pv-interneurons、v1-primary-visual-cortex→sst-interneurons、v1-primary-visual-cortex→prefrontal-cortex；243→256 总边数）
- 解决悬空：synaptic-clustering

---

## 2026-06-10（第三周·第 4 篇，文章 #18）

**源文章**：[[2026-06-10-stp-short-term-plasticity]] —《瞬息之变：短时程突触可塑性的分子机制与计算逻辑》

**新建页面（2）**：
- `concepts/short-term-synaptic-plasticity.md`（短时程突触可塑性）🟢 established / 置信度高 — 四种形式（易化/抑制/增强/PTP）的分子机制全覆盖；Syt7为脑内多突触易化的主要传感器（Jackman & Regehr 2017，PMID:28472650）；RRP耗竭驱动抑制（Zucker & Regehr 2002，PMID:11826273）；频率不变传输（Turecek 2017，PMID:29088700）；Mongillo活动无声工作记忆模型（PMID:18339943）；高p=低通/低p=高通计算逻辑（Tsodyks-Markram 1997，PMID:9012851）；连接9个既有节点
- `neurons/readily-releasable-pool.md`（就绪释放池/RRP）🟢 established / 置信度高 — 填补 synaptic-transmission 等多页引用的悬空引用；RRP停靠/就绪机制（Rab3-RIM/Munc13/Munc18-1）；RRP耗竭数学模型（PPR ≈ 1-p）；钙加速补充（10倍加速，PMID:22751149）；连接6个既有节点

**修订页面（2）**：
- `neurons/synaptotagmin.md`（revision_count 2→3）：大幅扩展Syt7作为易化传感器的机制（4种突触PPF KO实验；高钙亲和力 Kd ~1.5 μM；慢解离约60倍；频率不变传输PC→DCN）；related 新增 short-term-synaptic-plasticity；key_sources 新增 PMID:28472650, PMID:29088700；source_articles 新增 2026-06-10；更新 Q-syt7-facilitation-mechanism（主体机制已确立）；新增 Q-stp-syt7-human
- `concepts/working-memory.md`（revision_count 2→3）：related 新增 short-term-synaptic-plasticity；source_articles 新增 2026-06-10；连接段落新增 [[short-term-synaptic-plasticity]]；STP易化作为活动无声WM储存机制明确化

**悬空引用新增（0）**：今日无新悬空引用。

**悬空引用解决（1）**：
- ~~`readily-releasable-pool`~~ ✅ 已建立（neurons/readily-releasable-pool.md）

**矛盾登记（0）**：今日无新矛盾。两个现有开放矛盾（C-2026-05-24-01, C-2026-05-25-01）今日文献未直接涉及，状态不变。

**图谱更新**：
- 新节点：short-term-synaptic-plasticity, readily-releasable-pool（45→47 总节点）
- 新边：10条（STP↔synaptotagmin、STP↔readily-releasable-pool、STP↔synaptic-transmission、STP↔active-zone、STP↔voltage-gated-calcium-channels、STP↔working-memory、STP↔pv-interneurons、synaptotagmin↔short-term-synaptic-plasticity、readily-releasable-pool↔synaptic-transmission、readily-releasable-pool↔active-zone；233→243 总边数）
- 解决悬空：readily-releasable-pool

---

## 2026-06-09（第三周·第 3 篇，文章 #17）

**源文章**：[[2026-06-09-optogenetics-causal-neuroscience]] —《光遗传学：用一束光解开神经回路的因果之谜》

**新建页面（1）**：
- `methods/optogenetics.md`（光遗传学）🟢 established / 置信度高 — **methods 层第一个页面，填补完全空白的方法层**；ChR2（蓝光~470nm激活，7TM视黄醛门控阳离子通道，开放τ~1-2ms）+ NpHR（黄光~560nm沉默，Cl⁻泵，超极化~33mV，全文验证 PMID:17375185）分子机制；晶体结构（Kato 2012，2.3Å，C1C2嵌合体）；遗传特异性递送三策略（细胞特异性启动子/Cre-lox/c-fos-tTA）；假记忆实验（Ramirez 2013 Science）和效价翻转（Redondo 2014 Nature）因果实验；从相关性到因果性的方法论革命；与AI可解释性/mechanistic interpretability的类比；连接10个既有节点，新增14条边

**修订页面（1）**：
- `concepts/engram-cells.md`（revision_count 3→4）：补充 c-fos-tTA 标记系统技术细节（TetTag 小鼠、doxycycline 控制窗口、2-6% DG 稀疏性；全文来源 PMC3894458）；新增 [[optogenetics]] 到 related 字段；来源新增 PMID:24478647；来源文章新增 2026-06-09

**悬空引用新增（1）**：
- `channelrhodopsin`：被 optogenetics 引用，通道视紫质分子生物学专页（ChR1/ChR2 结构、光谱、工程变体）；待建页面

**矛盾登记（0）**：今日无新矛盾。C-2026-05-24-01（GABA 极性）和 C-2026-05-25-01（SNARE 就绪态）仍为 open，今日文献未直接涉及，未更新。

**图谱更新**：
- 新节点：optogenetics（45 个总节点）
- 新边：14条（optogenetics↔engram-cells、hippocampal-circuit、place-cell、pv-interneurons、ltp、dopamine-reward-prediction-error、disinhibitory-circuit、memory-consolidation、action-potential、synaptic-transmission、voltage-gated-sodium-channel；engram-cells↔optogenetics；hippocampal-circuit↔optogenetics）
- 新悬空：channelrhodopsin

---

## 2026-06-08（第三周·第 2 篇，文章 #16）

**源文章**：[[2026-06-08-alzheimers-amyloid-synaptic-mechanism]] —《记忆的分子遗忘：淀粉样寡聚体如何精准瓦解海马突触可塑性》

**新建页面（2）**：
- `diseases/alzheimers-disease.md`（阿尔茨海默病）🟢 established / 置信度高 — 首次建立疾病页（disease层空缺填补）；Aβ寡聚体5条并行通路；突触密度与认知衰退r=0.96（Terry 1991）；早期棘丢失可逆性（Shankar 2007）；斑块清除悖论（临床反向验证）；AD易损性分析（CA3-CA1高NR2B+内嗅皮层传播路径）；连接8个既有节点；新增未解问题Q-ad-vulnerable-synapses、Q-ad-tau-cascade、Q-ad-intervention-window
- `concepts/amyloid-beta-oligomers.md`（Aβ寡聚体）🟢 established / 置信度高 — Aβ寡聚体毒性物种认定（Walsh 2002：天然分泌寡聚体vs单体/纤维）；浓度数据（100-300 pM → 75%棘丢失）；PrPC/mGluR5/Fyn通路；突触外NR2B→p38/CREB通路；CaMKII降低60%、NR2B开放概率升高40%；连接6个既有节点

**修订页面（3）**：
- `concepts/ltp.md`（revision_count 5→6）：扩展"LTP病理镜像"段落（5条并行Aβ攻击通路；突触沉默可逆性早期干预意义）；related 新增 alzheimers-disease、amyloid-beta-oligomers；dimensions 新增 disease；key_sources 新增 PMID:11932745、17360908、21543591；连接 2 个新节点
- `concepts/nmda-receptor.md`（revision_count 3→4）：新增"第四重角色：突触外NR2B-LTP反向信号"小节；**解答 Q-nmda-alzheimer**（Aβ通过优先激活突触外而非突触内NR2B阻断LTP，而非直接破坏受体）；related 新增 alzheimers-disease、amyloid-beta-oligomers、calcineurin；dimensions 新增 disease；Q-nmda-alzheimer 更新为"已部分解答"
- `neurons/hippocampal-circuit.md`（revision_count 5→6）：新增AD易损性分析（CA3-CA1高NR2B密度+内嗅皮层Braak I期传播路径）；related 新增 alzheimers-disease、amyloid-beta-oligomers；dimensions 新增 disease；opens_questions 新增 Q-ad-vulnerable-synapses

**悬空引用新增（2）**：
- `bdnf-trkb`：被 alzheimers-disease 引用，BDNF/TrkB信号轴是L-LTP蛋白合成的关键上游；待建页面
- `prc-prion-protein`：被 amyloid-beta-oligomers、alzheimers-disease 引用，Aβ寡聚体的高亲和力细胞表面受体；待建页面

**矛盾登记（0）**：今日无新矛盾。theta-gamma耦合早于Aβ产生（Goutagny 2013）与Aβ→振荡失调（Mucke 2012）看似矛盾，但实为不同时间点的观察（振荡损伤先于Aβ大量积累，并非晚于），记录为未解问题Q-ad-vulnerable-synapses而非矛盾。

**解答的未解问题（1）**：
- Q-nmda-alzheimer（创建于 2026-05-26）："Aβ寡聚体如何选择性损害NMDA受体依赖的LTP？" → 已部分解答：Aβ通过PrPC/mGluR5/Fyn磷酸化NR2B，并优先激活突触外（而非突触内）NR2B/p38 MAPK/CREB失活通路；突触内vs突触外NR2B比例的AD中变化仍待研究

**图谱更新**：
- 新节点：alzheimers-disease、amyloid-beta-oligomers（44个总节点）
- 新增约12条边：alzheimers-disease→ltp/nmda-receptor/hippocampal-circuit/memory-consolidation/engram-cells/theta-oscillations；amyloid-beta-oligomers→ltp/nmda-receptor/calcineurin/camkii/ampa-receptor；等

---

## 2026-06-07（第三周·第 1 篇，文章 #15）

**源文章**：[[2026-06-07-dopamine-reward-prediction-error]] —《多巴胺奖励预测误差：大脑如何用一个信号重写所有预期》

**新建页面（3）**：
- `concepts/dopamine-reward-prediction-error.md`（多巴胺奖励预测误差）🟢 established / 置信度高 — VTA/SNc DA 神经元编码 δ = 实际奖励 − 预期奖励；Schultz 三种响应模式（正/零/负 RPE）；TD 学习的神经基底（Montague-Dayan-Sejnowski 1996）；三因素规则 Δw = (pre×post)×DA；D1/D2 双通路对称学习；DA 三大投射路径；连接 8 个已有节点；新增未解问题 Q-da-heterogeneity、Q-da-hippocampus-source
- `concepts/three-factor-learning-rule.md`（三因素学习规则）🟡 mainstream / 置信度高 — **填补 hebbian-learning 页面的悬空引用** — Δw = η·(pre×post)×M 统一框架；M = DA（奖励）/ ACh（注意）/ NE（显著性）三种调制因子；D1→cAMP→PKA 分子实现路径；Reynolds & Wickens 2002 在纹状体中的电生理验证；与 STC 解决 DA-Hebb 时间延迟问题的关系
- `concepts/synaptic-tagging-capture.md`（突触标记与捕获）🟡 mainstream / 置信度中 — 标记（~1-2 h 短暂 CaMKII 磷酸化）+ PRP 捕获（DA→D1→PKA→CREB→Arc/Homer/BDNF）将 E-LTP 转化为 L-LTP；解决 DA 来迟几秒~数十分钟的时间窗口问题；候选分子标签尚未完全确定（见 Q-stc-molecular-tag）

**修订页面（2）**：
- `concepts/hebbian-learning.md`（revision_count 2→3）：三因素规则小节从简述升级为完整分子机制（DA 作为 M 因子，D1→cAMP→PKA 链，Reynolds & Wickens 2002 验证，STC 解决时间延迟）；related 新增 dopamine-reward-prediction-error、synaptic-tagging-capture；三因素规则悬空引用标记为已建立
- `concepts/ltp.md`（revision_count 4→5）：新增"多巴胺调制的 LTP（DA-LTP）与突触标记-捕获"小节，详述 D1/D5→Gs→cAMP→PKA→GluA1 Ser845→CREB→PRP 分子链；related 新增 dopamine-reward-prediction-error、synaptic-tagging-capture、three-factor-learning-rule；key_sources 新增 PMID:7708662、PMID:9020359

**悬空引用解决（1）**：
- `three-factor-learning-rule`：首次出现于 hebbian-learning 页面，标记为"待建页面"；今日创建正式页面，hebbian-learning 已更新为"已建立"状态

**矛盾登记（0）**：今日无新矛盾。注：VTA DA 神经元功能异质性（奖励 vs 厌恶细胞）是活跃争议领域，记录为未解问题 Q-da-heterogeneity 而非矛盾，因两类细胞均有独立证据支持且互补而非互斥。

**图谱更新**：
- 新节点：dopamine-reward-prediction-error、three-factor-learning-rule、synaptic-tagging-capture（42 个总节点）
- 新增 14 条边（总计 207 条边）：含三因素规则→Hebb/LTP/竞争-遴选；DA-RPE→工作记忆/印迹细胞/记忆巩固；STC→CaMKII/Hebb；等

---

## 2026-06-06（第二周综合，文章 #14）

**源文章**：[[2026-06-06-week2-synthesis]] —《第二周综合：竞争法则——大脑如何在五个层次上通过竞争与遴选构建精简的世界模型》

**新建页面（1）**：
- `concepts/competition-selection-principle.md`（嵌套竞争-遴选架构）🟡 emerging / 置信度 medium — 大脑在突触（LTP/LTD Ca²⁺博弈）、细胞（CREB印迹竞争）、回路（PV+/SST+/VIP+时序门控）、系统（SWR选择性重播）、认知（PFC吸引子博弈）五个层次通过竞争决定记忆遴选；与嵌套时间编码层级互补（后者决定何时，前者决定选什么）；连接 10 个既有节点；第二周综合分析框架（分析性抽象，非命名理论）

**修订页面（3）**：
- `concepts/engram-cells.md`（revision_count 2→3）：新增"印迹细胞分配的竞争机制"小节，将 CREB 竞争纳入嵌套竞争-遴选架构的细胞层次；related 新增 competition-selection-principle
- `concepts/memory-consolidation.md`（revision_count 1→2）：新增"系统巩固中的竞争遴选"小节，明确 SWR 选择性（非全量）重播和 SHY 假说作为竞争-遴选的极端形式；related 新增 competition-selection-principle
- `concepts/working-memory.md`（revision_count 1→2）：新增"工作记忆容量的吸引子竞争机制"小节，从竞争角度解释约4项上限（θ/γ嵌套约束 + 吸引子干扰两种假说）；related 新增 competition-selection-principle

**矛盾登记（0）**：今日无新矛盾。综合框架（竞争-遴选）与既有知识无冲突——它是分析性抽象而非独立的实证主张。

**图谱更新**：
- 新节点：competition-selection-principle（39 个总节点）
- 新增 15 条边（总计 193 条边）：competition-selection-principle 与 ltp/ltd/engram-cells/memory-consolidation/pv-interneurons/sst-interneurons/vip-interneurons/working-memory/sharp-wave-ripples/temporal-coding-hierarchy 的双向/单向连接

**本周知识库增长（第8-14篇）**：节点 23→39（+16），边 86→193（+107）；覆盖层级首次扩展至 systems/prefrontal-cortex；disease 和 methods 层仍空缺

---

## 2026-06-05（第二周·第 6 篇，文章 #13）

**源文章**：[[2026-06-05-prefrontal-working-memory]] —《γ 爆发、静默突触与持续放电：前额叶皮层如何在数秒内维持工作记忆》

**新建页面（4）**：
- `concepts/working-memory.md`（工作记忆）🟢 established / 置信度高 — 容量~4项临时信息系统；γ爆发（活动性编码）+ STP突触易化（静默储存）双机制；dlPFC吸引子回路 + PV-γ轴 + D1倒U型调节三支柱；工作记忆容量与θ/γ嵌套的可能关系；4个未解问题
- `concepts/persistent-activity.md`（持续活动/延迟期放电）🟢 established / 置信度高 — PFC延迟期高于基线的神经活动；现已证明为间歇性γ爆发而非连续高频放电；依赖NMDA慢衰减和循环兴奋吸引子网络（Wang 2001）
- `concepts/gamma-oscillations.md`（γ振荡 30–80 Hz）🟢 established / 置信度高 — PV+篮状细胞PING机制产生；工作记忆中以~67ms爆发出现；精神分裂症中功率减弱与PV/GAD67损伤相关；θ/γ嵌套编码层级
- `systems/prefrontal-cortex.md`（前额叶皮层）🟢 established / 置信度高 — dlPFC L2/3 循环回路是WM关键脑区；多巴胺D1倒U型调节；深层L3d对压力/疾病的选择性脆弱性；跨物种比较（啮齿类→猕猴→人类）

**修订页面（2）**：
- `circuits/pv-interneurons.md`：系统层面新增PFC γ爆发WM应用（Lundqvist 2016）和精神分裂症病理证据（Hughes 2024）；related新增 working-memory, gamma-oscillations, prefrontal-cortex；dimensions新增 cognition；revision_count 1→2
- `concepts/nmda-receptor.md`：新增第三重角色——PFC吸引子回路时间积分器（慢衰减τ~100-300ms支撑循环激活；Wang 2001）；related新增 persistent-activity, working-memory, prefrontal-cortex；dimensions新增 brain-region；revision_count 2→3

**系统新增**：首次建立 `wiki/systems/` 子目录，知识库从分子/细胞/回路扩展到脑区/系统层级

**矛盾登记（0）**：今日无新矛盾。注意：活动性 WM vs 活动无声 WM 两种模型的相对贡献尚无定论，但两者并非互斥，记录为未解问题 Q-wm-active-vs-silent 而非矛盾（两种机制均有证据支持，互补而非冲突）。

**悬空引用新增**：dopamine-d1（dlPFC 倒 U 型调节中频繁引用，待建页面）；activity-silent-wm（Mongillo 2008 模型的独立概念页，可建）

---

## 2026-06-04（第二周·第 5 篇，文章 #12）

**源文章**：[[2026-06-04-ltd-long-term-depression]] —《遗忘的精准：突触如何弱化自身，以及这为何是大脑最聪明的设计》

**新建页面（3）**：
- `concepts/ltd.md`（长时程抑制 LTD）🟢 established / 置信度高 — NMDA-LTD（PP2B/PP1/GluA1去磷酸化/GluA2-Ser880-PICK1内吞）+ mGluR-LTD（Arc/dynamin内吞）+ 小脑 LTD（PKC/GluA2-Ser880）；AKAP150 机制；脆性 X 综合征连接；LTD 在 AD、恐惧消退、睡眠稳态中的角色；4 个未解问题
- `concepts/calcineurin.md`（钙调磷酸酶 PP2B）🟢 established / 置信度高 — 高亲和力 Ca²⁺ 磷酸酶；中低 Ca²⁺ 时优先激活；PP2B→PP1→GluA1去磷酸化；AKAP150 空间定位机制；与 CaMKII 构成 LTP/LTD 方向性的分子开关
- `concepts/arc-arg31.md`（Arc/Arg3.1）🟢 established / 置信度高 — 即早基因活动量规器；树突局部翻译；LTD 中与 dynamin/endophilin 结合→AMPAR 内吞；LTP 巩固中稳定肌动蛋白；Arc 敲除 L-LTP 受损；突触稳态下调的分子感受器

**修订页面（2）**：
- `concepts/ltp.md`：新增 LTD 作为双向对称的完整图景；related 从 ltp-ltd（悬空）改为 ltd（已建立）；新增 calcineurin 进 related；source_articles 新增 2026-06-04；revision_count 3→4
- `concepts/ampa-receptor.md`：新增"LTD 期间 AMPA 受体内吞"机制段落（GluA2 Ser880 磷酸化→PICK1路径；Arc/dynamin；GluA2 双敲除争议）；related 新增 ltd, calcineurin, arc-arg31；key_sources 新增 PMC4195488, PMC2694745；revision_count 1→2

**矛盾登记（0）**：今日无新矛盾。发现一个既有争议：GluA2/GluA3 双敲除后 LTD 仍然正常（Huganir & Nicoll 2013），与 GluA2 Ser880/PICK1 路径为必需机制的描述存在张力——但这不与 wiki 现有主张冲突（现有 AMPA-receptor 页原本未声明 GluA2 必需），记录为 Q-ltd-glua2-redundancy 未解问题。

**悬空引用解决**：
- `ltp-ltd`（ltp 页 related 字段悬空引用）✅ 改为已建立的 `ltd` 页面，悬空消除

**新增悬空引用**：
- `mglur-ltd`：被 ltd.md 和 arc-arg31.md 引用；目前内容已合并于 ltd 页面，可在未来单独展开

**已登记开放矛盾状态**（无变化）：
- `C-2026-05-24-01`（AIS GABA 极性）：仍 open
- `C-2026-05-25-01`（SNARE 就绪态装配状态）：仍 open

---

## 2026-06-03（第二周·第 4 篇，文章 #11）

**源文章**：[[2026-06-03-inhibitory-interneuron-diversity]] —《回路中的少数精锐：三类抑制性中间神经元如何统治大脑的计算时序》

**新建页面（4）**：
- `circuits/pv-interneurons.md`（PV+ 中间神经元）🟢 established / 置信度高 — 篮状细胞+吊灯细胞全貌；快速放电、围胞体抑制、γ振荡、0.7 ms 突触延迟；精神分裂症连接
- `circuits/sst-interneurons.md`（SST+ 中间神经元）🟢 established / 置信度高 — Martinotti 细胞、树突远端靶向、易化性输入特性；O-LM 细胞θ期功能；树突计算调控
- `circuits/vip-interneurons.md`（VIP+ 中间神经元）🟢 established / 置信度高 — 去抑制专家；被行为奖惩激活；主要抑制 SST+；Pi 2013 + Letzkus 2011
- `circuits/disinhibitory-circuit.md`（去抑制回路）🟢 established / 置信度高 — VIP→SST/PV→锥体细胞三级架构；学习门控；注意放大；跨皮层保守模块

**修订页面（3）**：
- `circuits/chandelier-cell.md`：新增 [[pv-interneurons]] 连接，纳入 PV+ 家族背景；revision_count 1→2
- `neurons/dendritic-computation.md`：新增 [[sst-interneurons]] 和 [[pv-interneurons]] 连接，填补 Q-inhibition-dendritic-spike-control 机制说明；revision_count 2→3
- `neurons/hippocampal-circuit.md`：新增 CA1 PV+ 篮状细胞（SWR 期涟漪产生者）和 SST+ O-LM 细胞（θ期 EC 输入门控）的角色描述；connected 到 pv-interneurons、sst-interneurons；revision_count 4→5

**矛盾登记（0）**：无新增矛盾。VIP 去抑制是否抑制 PV 部分的量化（主要抑制 SST 还是两者各半）在不同皮层区域有差异，但尚未引发与既有 wiki 内容的直接矛盾，记录为 Q-vip-sst-pv-ratio 未解问题。

**已登记开放矛盾状态**（无变化）：
- `C-2026-05-24-01`（AIS GABA 极性）：仍 open
- `C-2026-05-25-01`（SNARE 就绪态装配状态）：仍 open

**悬空引用解决**：
- `chandelier-cell → pv-interneurons` ✅ 新建 pv-interneurons 页面，吊灯细胞的 PV+ 家族归属现有完整背景页
- `dendritic-computation → sst-interneurons` ✅ 新建 sst-interneurons 页面，填补 Q-inhibition-dendritic-spike-control 机制说明

**新增悬空引用候选**：
- `three-factor-learning-rule`（三因素学习规则，VIP 去抑制的认知意义）→ 低优先级
- `e-i-balance`（兴奋-抑制平衡，精神疾病连接）→ 中优先级

**图谱**：节点 27→31（+4 新节点），边 136→约152（+~16 新边）

---

## 2026-06-02（第二周·第 3 篇，文章 #10）

**源文章**：[[2026-06-02-memory-consolidation-systems]] —《记忆的夜间旅行：大脑如何在睡眠中把海马的故事刻进皮层的石头》

**新建页面（1）**：
- `concepts/memory-consolidation.md`（记忆巩固·系统层面）🟢 established / 置信度高 — **填补了 hippocampal-circuit、sharp-wave-ripples、place-cell、engram-cells 共4个页面的最高优先级悬空引用**；整合系统巩固全貌（两阶段模型、SO-spindle-SWR三重奏、SCT vs MTT、CLS模型、SHY对立视角）；opens 4 个新未解问题

**修订页面（3）**：
- `concepts/sharp-wave-ripples.md`：填补 memory-consolidation 悬空引用解析完成；补充 SO-spindle-SWR 嵌套机制与因果破坏证据（PMID:26238360, 23589831）；key_sources +2；revision_count 1→2
- `neurons/hippocampal-circuit.md`：Q-hippocampal-consolidation-mechanism 内容通过 memory-consolidation 页面得到回答；来源文章增加 2026-06-02；revision_count 3→4
- `concepts/engram-cells.md`：补充系统巩固框架下沉默印迹的解读（被阻断的系统巩固）；来源文章增加 2026-06-02；revision_count 1→2

**矛盾登记（0）**：SHY（突触稳态假说）与主动系统巩固的张力已记录为 Q-shy-vs-active-consolidation 未解问题，但证据方向不完全对立（两者可能并行），未达到 contested_claims 登记门槛。

**已登记开放矛盾状态**（无变化）：
- `C-2026-05-24-01`（AIS GABA 极性）：仍 open
- `C-2026-05-25-01`（SNARE 就绪态装配状态）：仍 open

**悬空引用解决（1）**：
- `memory-consolidation` ✅ 已填补（被 hippocampal-circuit/sharp-wave-ripples/place-cell/engram-cells 共4个页面引用；最高优先级悬空引用之一）

**新增悬空引用**：memory-consolidation 页面的 related 字段中 `CLS-model`（互补学习系统）和 `slow-oscillation`（皮层慢振荡）可考虑在未来建立独立页面，已添加为低优先级悬空引用候选。

**图谱**：节点 26→27，边 120→136，新增 16 条边（memory-consolidation 出发 8 条 + 其他节点指向 memory-consolidation 8 条）。

---

## 2026-06-01（第二周·第 2 篇，文章 #9）

**源文章**：[[2026-06-01-voltage-gated-calcium-channels]] —《神经元的三重钙门：电压门控钙通道如何在不同地点执行截然不同的命令》

**新建页面（1）**：
- `neurons/voltage-gated-calcium-channels.md`（电压门控钙通道）🟢 established / 置信度高 — 填补了 synaptotagmin、active-zone、synaptic-transmission、nmda-receptor、dendritic-computation、btsp 共 6 个页面的最高优先级悬空引用（calcium-channel）；整合三亚家族（CaV1/CaV2/CaV3）的分类、结构（α1亚基四域架构）和三地点功能（突触前纳米域耦合、树突L型BTSP、核钙信号LTP）；opens 3 个新未解问题

**修订页面（3）**：
- `neurons/active-zone.md`：补充纳米域耦合量化数值（10-20 nm，23 nm，61 nm），P/Q型vs N型发育分布（P8→P16 转变），septin-5调控机制；更新 voltage-gated-sodium-channel→voltage-gated-calcium-channels 连接；key_sources 增 PMID:22183436, 25674049；revision_count 1→2
- `concepts/btsp.md`：明确L型通道（CaV1.2/1.3）作为平台电位的必要Ca²⁺来源（73% BTSP降低）；新增与 voltage-gated-calcium-channels 的连接；新增 Q-btsp-ltype-vs-nmda 未解问题；revision_count 1→2
- `neurons/synaptotagmin.md`：将悬空引用 calcium-channel 解析为 voltage-gated-calcium-channels；补充synprint位点与Syt1 C2B域的预结合机制（20 μM Ca²⁺时最强）；revision_count 1→2

**矛盾登记（0）**：今日新内容与既有wiki主张无直接冲突。CaV1.2在LTP中同时参与早期（mTOR局部蛋白合成，Sridharan 2020）和晚期（转录，CREB，既有综述）LTP的发现，是对既有"L型通道参与晚期LTP"主张的**扩展**而非矛盾——在ltp.md中添加注记即可，无需登记矛盾。

**已登记开放矛盾状态**（无变化）：
- `C-2026-05-24-01`（AIS GABA 极性）：仍 open
- `C-2026-05-25-01`（SNARE 就绪态装配状态）：仍 open

**悬空引用解决（1）**：
- `calcium-channel` ✅ 已填补（以 voltage-gated-calcium-channels 为新slug，被 synaptotagmin/active-zone/synaptic-transmission/nmda-receptor/dendritic-computation/btsp 共 6 个页面引用）

**新增悬空引用（0）**：voltage-gated-calcium-channels 页面的所有 related 节点均已有对应页面；Q-vgcc-nanodomain-universal、Q-cav1-cav13-functional-split、Q-btsp-ltype-vs-nmda 已加入 unresolved_questions。

**图谱**：节点 25→26，边 108→120，新增 12 条边（voltage-gated-calcium-channels 出发 10 条 + 其他节点指向 VGCCs 2 条）。

---

## 2026-05-31（第二周·第 1 篇，文章 #8）

**源文章**：[[2026-05-31-engram-cells-optogenetic-proof]] —《印迹细胞的光子证明：记忆真的宿于特定神经元集合吗？》

**新建页面（1）**：
- `concepts/engram-cells.md`（印迹细胞）🟢 established / 置信度高 — 填补了 ltp、hebbian-learning、dendritic-computation、place-cell 共 4 个页面的高优先级悬空引用；记录 Liu 2012、Ryan 2015、Roy 2016、Ramirez 2013 四个里程碑实验；定义三条认定标准、竞争性分配机制、沉默印迹；opens 4 个新未解问题

**修订页面（3）**：
- `concepts/ltp.md`：新增印迹细胞作为 LTP 细胞层面体现（AMPA/NMDA 比值）；补充沉默印迹中 LTP 缺失的证据；光学 LTP 恢复 AD 印迹；related 加 engram-cells；key_sources 增 PMID:26023136, 26982728；revision_count 2→3
- `neurons/place-cell.md`：明确场所细胞作为空间情景记忆印迹细胞候选的实验证据；更新 [[engram-cells]] 连接描述；revision_count 2→3
- `neurons/hippocampal-circuit.md`：新增 DG 作为印迹分配竞争主要场所的描述（2–4% 稀疏性→正交性）；DG→CA3→CA1→BLA 印迹间连接链；连接加 engram-cells；revision_count 2→3

**矛盾登记（0）**：新证据（沉默印迹）与既有 wiki 内容无直接冲突；沉默印迹丰富了 LTP 与遗忘关系的理解，补充而非推翻既有主张。

**已登记开放矛盾状态**（无变化）：
- `C-2026-05-24-01`（AIS GABA 极性）：仍 open
- `C-2026-05-25-01`（SNARE 就绪态装配状态）：仍 open

**悬空引用解决（1）**：
- `engram-cells` ✅ 已填补（被 ltp/hebbian-learning/dendritic-computation/place-cell 共 4 个页面引用）

**新增悬空引用（0）**：engram-cells 页的所有 related 节点均已有对应页面；memory-consolidation 原已在悬空列表中。

**图谱**：节点 24→25，边 95→108，新增 13 条边（engram-cells 出发 9 条 + 其他节点指向 engram-cells 4 条）。

---

## 2026-05-30（第一周综合，文章 #7）

**源文章**：[[2026-05-30-week1-synthesis]] —《第一周综合：时间的阶梯——大脑如何在七个数量级的尺度上编码记忆》

**本次运行说明**：今日（UTC+8）为 2026-05-28，但前序会话已生成 2026-05-28 和 2026-05-29 的日常文章。本次运行按 ROUTINE.md"每 7 篇写周综合"规则写第 7 篇（周综合），逻辑日期顺延至 2026-05-30，维护序列完整性。情景层 append-only 规则已遵守。

**新建页面（1）**：
- `concepts/temporal-coding-hierarchy.md`（嵌套时间编码层级）🟡 emerging / 置信度中 — 综合分析框架；从亚毫秒（钙纳米域）到年（记忆持久），大脑在每个时间尺度通过"精确巧合检测"修改突触权重；7 层嵌套结构；连接 ltp/btsp/theta-oscillations/sharp-wave-ripples/phase-precession/nmda-receptor/dendritic-computation/place-cell/hebbian-learning 共 9 个节点；status=emerging（各层单独证据强，整合框架待系统验证）

**修订页面（1）**：
- `concepts/hebbian-learning.md`：新增"多尺度 Hebb 规则"一节——将 LTP（ms）、BTSP（s）、θ 序列（120ms 压缩 s 级）和 SWR（离线批量）统一在 Hebb 原理的多时间尺度实现框架下；related 新增 btsp/theta-oscillations/sharp-wave-ripples/temporal-coding-hierarchy；dimensions 扩展为 behavior/whole-brain-network；revision_count 1→2

**矛盾登记（0）**：本周综合未发现新的概念间冲突。嵌套时间编码层级中各层机制的证据相互支持，而非冲突。

**已登记开放矛盾状态**（无变化）：
- `C-2026-05-24-01`（AIS GABA 极性）：仍 open
- `C-2026-05-25-01`（SNARE 就绪态装配状态）：仍 open

**悬空引用解决（0）**：本次未填补新悬空引用（temporal-coding-hierarchy 是新建节点，非悬空引用填补）。

**新增悬空引用（0）**：无新增（temporal-coding-hierarchy 页的 prerequisites 都已有节点）。

**图谱**：节点 23→24，边 86→95，新增 9 条边（temporal-coding-hierarchy 出发的 8 条 + hebbian-learning→temporal-coding-hierarchy 1 条）。

**知识意义**：第一周（文章 1–7）完整记录了从单神经元分子机制（AIS, 突触释放, LTP）到海马空间记忆系统（场所细胞, θ振荡, SWR）的完整故事链。今日周综合提取出这一链条的统一原理：嵌套时间编码层级，为第二周（印迹细胞、记忆巩固、抑制性回路）提供了系统性参照框架。

---

## 2026-05-29

**源文章**：[[2026-05-29-theta-oscillations-phase-coding]] —《θ振荡与相位编码：大脑如何用节律将空间压缩成时间》

**新建页面（3）**：
- `concepts/theta-oscillations.md`（θ振荡）🟢 established — **填补高优先级悬空引用**（此前被 place-cell、ltp、hippocampal-circuit、grid-cell 共4个页面引用）；4–12 Hz 探索节律，由 MS-DBB 驱动；相位编码框架；θ序列（20:1压缩）；θ/γ嵌套（5-9个γ/θ）；θ与BTSP协调的新假说
- `concepts/sharp-wave-ripples.md`（尖波涟漪 SWR）🟢 established — CA3循环兴奋→CA1涟漪（110-200 Hz）；~20倍速序列重播；前向/反向/新颖路径重播；记忆固化机制；选择性SWR中断→记忆受损（因果证据）；两阶段记忆理论的离线阶段
- `concepts/phase-precession.md`（相位前进）🟢 established — O'Keefe & Recce 1993经典发现；放电相位随位置移动100–355°；θ序列的基础；振荡干涉 vs 双路径输入两种机制争议

**修订页面（2）**：
- `neurons/hippocampal-circuit.md`：新增"海马两种工作模式"（θ态/SWR态双模切换）章节；新增胆碱能张力作为切换开关的机制；key_sources 增加 PMID:26135716、PMID:23354386；revision_count 1→2
- `neurons/place-cell.md`：新增"相位前进"（第4节）：场所细胞的速率+相位双重编码，θ序列的20:1压缩；key_sources 增加 PMID:8353611、PMID:23354386；连接新增 [[phase-precession]]、[[sharp-wave-ripples]]；revision_count 1→2

**矛盾登记（0）**：今日证据与既有 wiki 主张无冲突。相位前进的振荡干涉 vs 双路径输入两种机制争议已在新建 phase-precession 页面中如实并列（不足以登记为contested_claim，因两者可能互补而非真实冲突）。

**悬空引用解决（1）**：
- `theta-oscillations`（θ振荡）— 已建页面（此前被 4 个页面引用，高优先级）

**新增悬空引用（1）**：
- `medial-septum`（内侧隔核/MS-DBB）— θ振荡主要起搏器，待建页面

**层级跨越**：今日进入**全脑网络（whole-brain-network）层**——θ振荡是全海马同步的网络现象；SWR是海马→新皮层的跨区信息传递机制。同时覆盖 behavior 层（序列编码、空间导航中的时间结构）。

**图谱**：节点 20→23，边 68→86，悬空引用：`theta-oscillations` 已填补，新增 `medial-septum`。

---

## 2026-05-28

**源文章**：[[2026-05-28-place-cells-btsp]] —《场所细胞：海马如何在单次穿越中一次性写入空间记忆》

**新建页面（4）**：
- `neurons/place-cell.md`（场所细胞）🟢 established — **填补高优先级悬空引用**；CA1 场所细胞通过 BTSP 单次写入场所场；O'Keefe 1971 认知地图假说；群体编码+重映射+序列编码
- `concepts/btsp.md`（行为时间尺度突触可塑性 BTSP）🟢 established — 独立于 LTP/STDP 的第三种突触可塑性规则；秒级时间窗口（±3–4 s）；不对称性（CA1）vs 对称性（CA3）；单次写入；NMDA 84% + L-型 Ca 通道 73% 依赖
- `neurons/hippocampal-circuit.md`（海马回路）🟢 established — DG/CA3/CA1 三突触回路；模式分离（DG）+ 模式补全（CA3）+ 整合输出（CA1）；并行穿孔通路；记忆巩固与重放
- `neurons/grid-cell.md`（网格细胞）🟢 established — MEC 六角网格放电；背侧→腹侧间距梯度；路径整合能力；振荡干涉 vs 连续吸引子两种机制假说

**修订页面（2）**：
- `neurons/dendritic-computation.md`：新增钙平台电位→BTSP 连接段；related 增加 place-cell/btsp/hippocampal-circuit；dimensions 增加 brain-region；key_sources 增加 PMID:28883072；revision_count 1→2
- `concepts/ltp.md`：新增 BTSP 作为平行可塑性规则段落；related 增加 btsp/place-cell/hippocampal-circuit；dimensions 增加 brain-region；key_sources 增加 PMID:28883072；revision_count 1→2

**矛盾登记（0）**：今日证据与既有 wiki 主张无冲突。BTSP 是 LTP 的**补充而非替代**；关于 BTSP 的单一路径 vs 多路径（Sumegi 2025）尚不足以登记矛盾（证据水平差异过大：胞内记录 vs 群体钙成像）。

**悬空引用解决（1）**：
- `place-cell`（场所细胞）— 已建页面（此前被 [[树突计算]] 引用，高优先级）

**新增悬空引用（4）**：
- `engram-cells`（印迹细胞）— 场所细胞 × 记忆行为证据，今日 place-cell 页新引用
- `path-integration`（路径整合）— 网格细胞无地标时维持放电的内源机制
- `memory-consolidation`（记忆巩固）— 海马 SWR 重放→皮层巩固机制
- `theta-oscillations`（θ振荡）— 调控 BTSP 触发时机和场所场形成节律（已在旧悬空引用列表中，今日新证据加强了其重要性）

**层级跨越**：今日从细胞/微回路层（昨日）跨入**脑区层（brain-region）**——从单神经元的树突计算，到海马亚区的回路分工，到内嗅-海马系统的空间地图构建。

**图谱**：节点 16→20，边 50→68，悬空引用：`place-cell` 已填补，新增 path-integration / memory-consolidation；engram-cells 和 theta-oscillations 已在旧列表中。

---

## 2026-05-27

**源文章**：[[2026-05-27-dendritic-computation]] —《树突：神经元内部的神经网络——NMDA 棘波与 Ca²⁺ 棘波如何使一根树突变成一台计算机》

**新建页面（2）**：
- `neurons/dendritic-computation.md`（树突计算）🟢 established — 填补 Hodgkin-Huxley 模型页的长期悬空引用；NMDA 棘波（50–200 ms，全或无）+ Ca²⁺ 棘波 + 两层神经网络等价；体内证据：视觉皮层朝向选择性 + 海马场所场快速形成
- `neurons/pyramidal-neuron.md`（锥体神经元）🟢 established — 树突计算的物理载体；双树突系统（顶端 tuft top-down + 基底 bottom-up）是前馈/反馈整合的结构基础；连接 AIS、chandelier-cell、dendritic-computation

**修订页面（2）**：
- `concepts/nmda-receptor.md`：新增"NMDA 受体的双重身份"概念（突触层面巧合检测器 vs 树突分支层面 NMDA 棘波计算单元）；关键证据表新增 Smith 2013（体内 OSI 0.82→0.45）和 Schiller 2000（首次 NMDA 棘波）；连接新增 dendritic-computation；dimensions 新增 cellular；revision_count 1→2
- `concepts/hodgkin-huxley-model.md`：[[树突计算]] 悬空引用已填补，source_articles 补充今日文章；revision_count 1→2

**矛盾登记（0）**：今日新证据与既有 wiki 主张无冲突。NMDA 受体的"树突棘波"维度是对已有突触LTP功能的扩展，而非冲突。

**悬空引用解决（1）**：
- `dendritic-computation`（树突计算）— 已建页面（此前在 hodgkin-huxley-model 中为悬空引用）

**新增悬空引用（3）**：
- `place-cell`（场所细胞）— 海马 CA1/CA3，体内树突平台电位证据来源，高优先级
- `synaptic-clustering`（突触聚类假说）— NMDA 棘波发生的关键前提，有争议
- `apical-tuft`（顶端簇）— L5锥体细胞 Ca²⁺ 棘波的发生地

**层级转换**：今日从分子/突触层（连续4天）跨入**细胞/微回路层**——NMDA 棘波是从"分子 NMDA 受体"到"细胞计算单元"的层级跨越。

**图谱**：节点 14→16，边 36→50，悬空引用 8→9（net，减1填补，加3新增）。

---

## 2026-05-26

**源文章**：[[2026-05-26-nmda-receptor-ltp]] —《NMDA 受体：突触的"巧合检测器"，以及大脑如何在神经元间刻写记忆》

**新建页面（5）**：
- `concepts/nmda-receptor.md`（NMDA 受体）🟢 established — 双重门控巧合检测器（谷氨酸 + 去极化解除 Mg²⁺），LTP 诱导的必要门卫，GluN2 亚型多样性决定时间整合窗口
- `concepts/ltp.md`（长时程增强）🟢 established — 突触可塑性核心机制：NMDA→CaMKII→AMPA 受体插入→突触增强；填补此前悬空引用
- `concepts/hebbian-learning.md`（Hebbian 学习）🟢 established — Hebb 规则的分子实现；三因素学习规则扩展；填补此前悬空引用
- `concepts/ampa-receptor.md`（AMPA 受体）🟢 established — 快速 EPSP 执行者，GluA1 S831 磷酸化，LTP 期间大量插入，"突触权重"的物理载体
- `neurons/camkii.md`（CaMKII）🟢 established — T286 自磷酸化实现"分子记忆翻转"；LTP 诱导和维持均必需（2021 关键实验）

**修订页面（2）**：
- `neurons/synaptic-transmission.md`：新增突触后受体层（AMPA/NMDA 的功能分工及其在 LTP 中的角色）；related/dimensions/key_sources 扩展；revision_count 1→2
- `neurons/action-potential.md`：补充反向传播动作电位（bAP）在 STDP/LTP 中的作用；related 新增 nmda-receptor、ltp、hebbian-learning；revision_count 2→3

**矛盾登记（0）**：今日新证据与既有主张无冲突。

**悬空引用解决（2）**：
- `ltp`（长时程增强）— 已建页面
- `hebbian-learning`（Hebb 规则）— 已建页面

**新增悬空引用（4）**：
- `theta-oscillations`（θ振荡）— LTP 体内诱导节律
- `engram-cells`（印迹细胞）— 记忆存储的细胞群体
- `three-factor-learning-rule`（三因素学习规则）— Hebb × 多巴胺
- `tarp-auxiliary-subunit`（TARP 辅助亚基）— AMPA 受体突触锚定关键

**层级跨越**：今日首次从分子/突触层（前两天主题）跨入**认知层**——NMDA 受体巧合检测 → LTP → Hebb 学习 → 记忆的分子基础。

**图谱**：节点 9→14，边 20→36。

---

## 2026-05-25

**源文章**：[[2026-05-25-synaptic-vesicle-exocytosis]] —《神经信号的化学渡口：钙离子如何在不到一毫秒内触发突触囊泡融合》

**新建页面（4）**：
- `neurons/synaptic-transmission.md`（突触传递）🟢 established — 填补此前悬空引用；突触前→突触后化学信号转化全流程，约100-200微秒
- `concepts/SNARE-complex.md`（SNARE复合体）🟢 established — Synaptobrevin+Syntaxin-1+SNAP-25四螺旋束拉链，融合驱动机器
- `neurons/synaptotagmin.md`（突触结合蛋白）🟢 established — C2A/C2B双域钙传感器，触发SNARE最终拉合
- `neurons/active-zone.md`（活动区）🟢 established — RIM/CAST/ELKS/Bassoon脚手架，纳米级精度定位钙通道与就绪囊泡

**修订页面（1）**：
- `neurons/action-potential.md`：新增下游连接节点（突触传递、活动区），扩展dimensions为synaptic层，revision_count 1→2

**矛盾登记（1）**：
- `C-2026-05-25-01`：SNARE就绪态模型争议——"部分拉合"（N端预组装，Complexin锁C端）vs "完全游离"（Ca²⁺到来后从头组装）；两种模型均有体外/体内证据，尚无定论（PMID:23060190；见 contested_claims.json）

**悬空引用解决（1）**：
- `synaptic-transmission` — 已建页面（此前为悬空引用）

**新增悬空引用（4）**：
- `calcium-channel`（电压门控钙通道）
- `complexin`（复合素）
- `readily-releasable-pool`（RRP）
- `munc18`（SM蛋白，次要）

**图谱**：节点 5→9，边 9→20。

---

## 2026-05-24

**源文章**：[[2026-05-24-axon-initial-segment]] —《决策的解剖学：神经元如何在混沌的输入中找到它唯一的声音》

**Wiki 初始化 + 首次固结**：本日建立语义层（`wiki/`）并从首篇文章固结出 5 个主题页。

**新建页面（5）**：
- `neurons/action-potential.md`（动作电位）🟢 established — 全或无脉冲，神经系统基本信息单位
- `neurons/axon-initial-segment.md`（轴突始段）🟢 established — 动作电位诞生地，本日核心节点（5 条边、5 个未解问题）
- `neurons/voltage-gated-sodium-channel.md`（电压门控钠通道）🟢 established — 动作电位上升相分子引擎
- `concepts/hodgkin-huxley-model.md`（Hodgkin-Huxley 模型）🟢 established — 动作电位的数学框架
- `circuits/chandelier-cell.md`（吊灯细胞）🔵 mainstream / 置信度中 — 特异抑制 AIS（机制有争议）

**修订页面（0）**：无（首日，全部为新建）

**矛盾登记（0）**：无新矛盾。

**新增悬空引用（待补缺口）**：
- `dendritic-computation`（树突计算）— 被 Hodgkin-Huxley 模型页引用
- `synaptic-transmission`（突触传递）— 课程脊柱下一站

**图谱**：节点 5，边 9。

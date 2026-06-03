# Wiki 变更日志

> 每日固结步骤产生的 wiki 变更记录。新条目置于顶部。

---

## 2026-07-03（文章 #69·突触稳态·赫布规则的稳定器）

**源文章**：[[2026-07-03-synaptic-scaling-homeostatic-plasticity]] —《突触稳态：当赫布规则失控时，大脑如何给自己"归零"》

**新建页面（2 页）**：
- `concepts/synaptic-scaling.md`：突触稳态缩放——乘法性负反馈；GluA2 通路（不同于 LTP 的 GluA1）；钙/CaMKIV 全细胞传感；树突局部视黄酸非基因组信号；星形胶质细胞 TNFα 许可因子；突触前 PHP（Sema3a）；记忆特异性雕刻（Wu 2021）（established）
- `concepts/homeostatic-plasticity.md`：稳态可塑性总概念页——三大类型（突触缩放/内在兴奋性/突触前稳态）；时间尺度隔离（小时/天 vs 秒/分）；功能：维护网络动态范围；与 Hebbian 规则形成互补稳定系统（established）

**修订页面（4 页）**：
- `concepts/ltp.md`（rev10→rev11）：在连接段新增 synaptic-scaling 和 homeostatic-plasticity；明确 GluA1（LTP）vs GluA2（稳态缩放）分子路径分叉；related 新增两条
- `concepts/hebbian-learning.md`（rev3→rev4）：在连接段新增 synaptic-scaling 和 homeostatic-plasticity；Q-hebbian-stability 更新为"部分有答案"状态；related 新增两条
- `concepts/ampa-receptor.md`（rev2→rev3）：在连接段新增 synaptic-scaling；明确 GluA2 通路为稳态缩放特异通路（Gainey 2009 证据）；related 新增两条
- `wiki/systems/astrocyte.md`（rev1→rev2）：在连接段新增 synaptic-scaling；揭示星形胶质细胞 TNFα 在稳态中的许可角色（双时间尺度分工：D-丝氨酸→LTP；TNFα→稳态）；related 新增两条

**新登记矛盾**：无（今日证据无与既有主张冲突）

**新增悬空引用**：`homeostatic-plasticity`（已立即建页）；`synaptic-scaling`（已立即建页）

**图谱更新**：新增节点 2（synaptic-scaling, homeostatic-plasticity）；新增边约 12；总计 **127 节点、~721 条边**

---

## 2026-07-02（文章 #68·大脑的第三方·星形胶质细胞与三方突触）

**源文章**：[[2026-07-02-astrocyte-tripartite-synapse]] —《大脑的第三方：星形胶质细胞如何改写突触的游戏规则》

**新建页面（6 页）**：
- `systems/astrocyte.md`：星形胶质细胞——三方突触第三方成员；PAPs 覆盖 57% 突触；EAAT2 清除 80% 谷氨酸；D-丝氨酸供给；Ca²⁺ 信号；LTP/LTD 必要参与者（established）
- `concepts/tripartite-synapse.md`：三方突触——Araque 1999 框架；双向神经元-星形胶质细胞信号；Ca²⁺-D-丝氨酸-NMDA 轴；LTP/LTD 的三方必要性（mainstream）
- `concepts/d-serine.md`：D-丝氨酸——NMDA 受体 GluN1 协同激动剂；星形胶质细胞来源；Ca²⁺ 依赖释放；LTP 的隐性必要条件（Henneberger 2010）（mainstream）
- `concepts/gliotransmitter.md`：胶质递质——D-丝氨酸/ATP/谷氨酸；三种释放机制；争议（medium confidence；C-2026-07-02-01）
- `concepts/astrocyte-calcium-signaling.md`：星形胶质细胞钙信号——mGluR-IP₃-ER 路径；钙波传播；门控 D-丝氨酸（established）
- `concepts/glutamate-glutamine-cycle.md`：谷氨酸-谷氨酰胺循环——EAAT2 清除；GS 转化；递质再生；防兴奋毒性（established）

**修订页面（2 页）**：
- `concepts/ltp.md`（rev9→rev10）：新增"三方突触条件"段落——星形胶质细胞 D-丝氨酸是 LTP 的隐性必要条件（Henneberger 2010 因果证据）；related 新增 astrocyte、tripartite-synapse、d-serine、astrocyte-calcium-signaling；连接段落新增四条
- `concepts/ltd.md`（rev2→rev3）：新增星形胶质细胞参与 LTD 的三条路径（D-丝氨酸/ATP-腺苷/eCB-CB1R）；related 新增 astrocyte、tripartite-synapse、gliotransmitter、d-serine；连接段落新增四条

**新登记矛盾（1 条）**：
- `C-2026-07-02-01（open）`：星形胶质细胞 Ca²⁺ 依赖性谷氨酸胞吐在生理条件下是否真实发生（Parpura 1994 vs Fiacco/Bhatt 2007-2009）

**新增悬空引用**：无（所有引用的 slug 均已建页）

**图谱更新**：新增节点 6（astrocyte, tripartite-synapse, d-serine, gliotransmitter, astrocyte-calcium-signaling, glutamate-glutamine-cycle）；新增边约 20；总计 **125 节点、~709 条边**

---

## 2026-07-01（文章 #67·空间注意的神经回路·背侧注意网络 DAN）

**源文章**：[[2026-07-01-dorsal-attention-network-FEF-IPS]] —《空间注意的神经回路：前额叶眼区与顶内沟如何驾驭大脑的聚光灯》

**新建页面（2 页）**：
- `concepts/dorsal-attention-network.md`：背侧注意网络（DAN）——FEF+IPS 构成目标驱动注意控制系统；LIP 优先级地图；FEF 微电刺激因果证据；V4→V1 反馈必要通道；乘法性增益调制；FEF→TRN 门控接口（established）
- `concepts/biased-competition.md`：偏置竞争模型——Desimone & Duncan 1995；多刺激竞争感觉表征资源；DAN 提供偏置信号；乘法增益是偏置计算形式（mainstream）

**修订页面（3 页）**：
- `systems/prefrontal-cortex.md`（rev2→rev3）：新增 FEF（BA8）作为 PFC 注意控制子区域；related 新增 dorsal-attention-network 和 thalamus；key_sources 新增 PMID:13679398 和 PMID:11994752；opens_questions 新增 Q-dan-02
- `systems/v1-primary-visual-cortex.md`（rev3→rev4）：新增 V4→V1 反馈是注意调制必要通道（Debes & Dragoi 2023）；related 新增 dorsal-attention-network 和 biased-competition；key_sources 新增 PMID:36730414
- `systems/thalamus.md`（rev2→rev3）：新增 DAN（FEF/IPS）→TRN 通路作为皮层注意信号向下传递接口；related 新增 dorsal-attention-network；Q-dan-01 交叉引用；Q-thalamus-gating-mechanism 部分回答

**新登记矛盾**：无新矛盾
**新增悬空引用**：无
**图谱更新**：新增节点 2（dorsal-attention-network, biased-competition）；新增边 13；总计 119 节点、689 条边

---

## 2026-06-30（文章 #66·视丘的双面人格·T 型钙通道与感知时序门控）

**源文章**：[[2026-06-30-thalamic-burst-t-type-calcium-timing-gate]] —《视丘的双面人格：T 型钙通道如何在爆发与强直之间切换，让清醒大脑实现精确感知》

**新建页面（2）**：
- `neurons/thalamic-firing-modes.md`（视丘放电模式/爆发强直双模式）🟢 established — 清醒VPm约15%感觉响应为爆发；爆发提高时序精度非幅度；爆发-强直连续谱（Whitmire 2016）；前馈FSU同步创造10ms时窗（Borden 2022）；CaV3.1去失活机制；填补thalamus.md的悬空引用
- `neurons/t-type-calcium-channels.md`（T型钙通道/CaV3/低电压激活钙通道）🟢 established — CaV3.1（TC）/CaV3.3（TRN）分布；失活-去失活动力学；LTS产生机制；疾病连接（失神癫痫/脆性X/PLCβ4通路）

**修订页面（1）**：
- `systems/thalamus.md`（rev2）— 更新"双模放电"小节：加入 Borden 2022 清醒因果实验（爆发→时序精度↑非幅度↑）和 Whitmire 2016 爆发-强直连续谱；更新 Q-thalamus-burst-awake 为"部分回答"；补充 key_sources

**矛盾登记（0）**：新证据与既有主张一致，无新矛盾。

**未解问题状态更新**：
- Q-thalamus-burst-awake：部分回答（时序门控机制确认）；剩余开放：触发机制（TRN vs 适应性KATP）

**新增边（9）**：thalamic-firing-modes↔thalamus、t-type-calcium-channels→thalamic-firing-modes、thalamic-firing-modes→pv-interneurons 等

**图谱**：节点 117，边 676。

---

## 2026-06-03（第 66 篇·视丘的三张面孔·感觉门控、认知放大器与意识开关）

**源文章**：[[2026-06-03-thalamus-gatekeeper-cognition]] —《视丘的三张面孔：感觉门控、认知放大器与意识开关》

**核心任务**：从近期分子/疾病系列（tau, BDNF, NCC）转回系统/回路层级；填补 Q-thalamus-gating-mechanism（睡眠纺锤波文章遗留）；整合视觉注意（Pulvinar-V1）、工作记忆（MD-PFC）和意识（CM-Pf）的视丘视角；建立 thalamus 专页作为系统层核心节点。

**新建页面（2）**：
- `systems/thalamus.md`（视丘）🟢 established / 置信度高 — TRN/TC解剖学、双模放电调控、一次/高次核区分（Sherman框架）、Pulvinar-V1因果证据（Purushothaman 2012）、MD-PFC工作记忆放大（Parnaudeau 2018）、CM-Pf与意识（Cacciatore 2025）
- `concepts/thalamic-firing-modes.md`（视丘双模放电）🟢 established / 置信度高 — T型Ca²⁺通道机制、tonic/burst信息论差异（Zeldenrust 2018）、清醒爆发功能（Borden 2022 因果）、timing-based gating模型

**修订页面（2）**：
- `circuits/thalamocortical-circuit.md`（修订 #2）— 新增：一次/高次视丘核区分、驱动/调制型突触对比表、PFC→TRN大型端钮解剖证据（Zikopoulos&Barbas 2006）；related 新增 thalamus/thalamic-firing-modes/working-memory/prefrontal-cortex/neural-correlates-of-consciousness；Q-thalamus-burst-awake 新增为未解问题
- `concepts/working-memory.md`（修订 #6）— 新增MD视丘放大器角色小节：MD维持延迟期晚期活动、MD-PFC θ/β同步、认知灵活性MD-OFC依赖、精神分裂症临床证据；related 新增 thalamus, thalamocortical-circuit

**矛盾处理**：无新矛盾登记。清醒爆发功能（Q-thalamus-burst-awake）登记为新开放问题而非矛盾。

**新增悬空引用待补**：`[[prefrontal-cortex]]`（需要单独系统页）、`[[v1-primary-visual-cortex]]`（已有但需更新Pulvinar联系）

---

## 2026-06-29（第 65 篇·tau 蛋白病理·磷酸化级联、树突棘错位与朊蛋白样传播）

**源文章**：[[2026-06-29-tau-pathology-alzheimer]] —《形状即命运：tau 蛋白从微管守护者到神经原纤维缠结的分子蜕变》

**核心任务**：填补 alzheimers-disease.md 长期悬空引用 `[[tau-pathology]]`；建立 tau 病理独立 wiki 页面；回答 Q-ad-tau-cascade（高优先级开放问题）；完善 AD 分子损伤双刃剑模型（Aβ + tau）。

**新建页面（1）**：
- `concepts/tau-pathology.md`（tau 蛋白病理）🟢 established / 置信度高 — Braak 分期、CDK5/GSK-3β 激酶级联、Zempel 2015 树突棘错位（TTLL6-spastin 微管破坏）、Fitzpatrick 2017 cryo-EM 结构、de Calignon 2012 跨突触传播、FTD-MAPT 独立神经毒性证据

**修订页面（1）**：
- `diseases/alzheimers-disease.md`（修订 #4）— related 新增 tau-pathology；"连接"段落新增 tau-pathology 节点；key_sources 新增 PMID:1759558、PMID:26691836、PMID:22365544；已填补悬空引用

**矛盾处理**：无新矛盾登记（tau 低聚物 vs NFT 毒性争议记录为 Q-tau-01，待后续实验裁决；内部争议已在 tau-pathology.md 页内并列记录）

**图谱更新**：新增节点 1（tau-pathology）；新增边 12 条（tau-pathology ↔ alzheimers-disease、ltp、nmda-receptor、amyloid-beta-oligomers、engram-cells、hippocampal-circuit、bdnf、pattern-completion、memory-consolidation）；总计 110 节点，637 条边

**新增未解问题**：Q-tau-01（低聚物 vs NFT 相对毒性的活体分离实验）、Q-tau-02（EC-II 神经元优先受累的细胞选择性机制）

**下一步建议（来自 topic_ledger）**：
1. MAPT 突变与 FTD-MAPT 专篇（连接 tau-pathology 页面的 FTD 内容；独立 tauopathy 类群展开）
2. AD 整合综合（Aβ + tau + BDNF + 神经发生四线整合，完成 AD 系列）
3. 无报告范式的意识研究（Q-ncc-01）——从 AD 系列切换至意识系列

---

## 2026-06-02（第 65 篇·具身语义·行动词义的感觉运动神经基底与复制危机）

**源文章**：[[2026-06-02-embodied-semantics]] —《当大脑读到"踢"，脚步已先响——具身语义的神经科学》

**核心任务**：填补唯一悬空引用 `embodied-semantics`（被 motor-cortex 页面引用）；建立具身语义的独立 wiki 页面；整合2004-2026年的支持与反驳证据链；更新 motor-cortex 和 language-network 页面。

**新建页面（1）**：
- `concepts/embodied-semantics.md`（具身语义）🟡 contested / 置信度中 — Hauk等2004 somatotopic fMRI证据；Pulvermüller TMS类别特异性因果效应；Watson 2013 ALE元分析挑战；de Zubicaray 2026 复制危机；分级具身论与Hub-and-Spoke整合模型

**修订页面（2）**：
- `systems/motor-cortex.md`（修订 #3）— related 新增 embodied-semantics；新增连接"运动皮层作为词义的感觉运动辐条"；key_sources 新增 PMID:14741110, PMID:15733097
- `systems/language-network.md`（修订 #3）— related 新增 embodied-semantics；source_articles 新增 2026-06-02-embodied-semantics

**矛盾处理**：无新矛盾登记（具身语义本身状态设为 contested，内部争议已在页内并列记录）

**图谱更新**：新增节点 1（embodied-semantics）；新增/更新边 7 条；悬空引用从 1 减少至 0；总计 112 节点，644 条边

**新增未解问题**：Q-emb-01（运动激活的因果必要性）、Q-emb-02（复制危机系统检验）、Q-emb-03（任务依赖的具体机制）、Q-emb-04（先天无肢者的行动词语义）、Q-emb-05（Hub辐条的表征vs存储区分）

**下一步建议**：语言网络深化（语音知觉：颞上沟/颞平面/音素处理）；Wernicke区功能专篇；主动推断/自由能原理（FEP，填补 Q-pc-02）

---

## 2026-06-28（第 64 篇·BDNF·TrkB信号级联、LTP后期维持与AD分子接点）

**源文章**：[[2026-06-28-bdnf-trk-b-plasticity-memory]] —《BDNF：大脑给自己的成长信号》

**核心任务**：填补多页悬空引用 `[[bdnf]]`（被 adult-neurogenesis、hippocampal-neurogenesis、ltp 等页面引用）；建立 BDNF/TrkB 信号机制的独立 wiki 页面；补充 L-LTP 中 BDNF→Arc→突触固结的完整机制链。

**新建页面（1）**：
- `concepts/bdnf.md`（脑源性神经营养因子 BDNF）🟢 established / 置信度高 — proBDNF/成熟 BDNF 双向开关（p75NTR vs TrkB）；TrkB 三条信号通路（PLCγ/ERK/Akt）；L-LTP 的必要催化分子（Bramham 2005）；SGZ 神经发生 PI3K/Akt 存活机制；有氧运动→血清 BDNF↑→海马体积+2%（Erickson 2011 RCT）；Val66Met 多态性；AD 早期 BDNF/TrkB-CREB 受损；BDNF+AHN 协同改善认知（Choi 2018 Science）

**修订页面（4）**：
- `concepts/ltp.md`（修订 #9）— 新增 BDNF→Arc mRNA 局部翻译→E-LTP→L-LTP 转化段落（突触固结机制）；补充 BDNF 与 DA/STC 路径的汇聚；related 新增 bdnf、arc-arg31；key_sources 新增 PMID:16099088、PMID:17942328
- `concepts/adult-neurogenesis.md`（修订 #2）— 悬空引用 [[bdnf]] 已建页；补充 PI3K/Akt+MAPK/ERK 双通路机制描述
- `concepts/hippocampal-neurogenesis.md`（修订 #3）— 悬空引用 [[bdnf]] 已建页；补充 TrkB 信号机制说明
- `diseases/alzheimers-disease.md`（修订 #3）— 修正 related 中错误 slug `bdnf-trkb`→`bdnf`（已建页）；新增 adult-neurogenesis 连接；补充 Choi 2018 BDNF+AHN 协同干预证据；key_sources 新增 PMID:30190379

**矛盾处理**：无新矛盾登记

**图谱更新**：新增节点 1（bdnf）；新增边 12 条（bdnf→ltp/ltd/adult-neurogenesis/hippocampal-neurogenesis/alzheimers-disease/nmda-receptor/camkii/arc-arg31/synaptic-tagging-capture/memory-consolidation + 反向边 2 条）；总计 111 节点，638 条边

**新增未解问题**：Q-bdnf-01（血脑屏障/TrkB 激动剂临床）、Q-bdnf-02（Val66Met 风险权重）、Q-bdnf-03（AD 中 BDNF 因果方向）

**下一步建议**：阿尔茨海默病分子机制完整文章（tau/淀粉样蛋白/神经发生三线整合）；预测编码与 NCC 的整合；无报告范式意识研究（Q-ncc-01）

---

## 2026-06-27（第 63 篇·意识在哪里·NCC 框架与 COGITATE 2025 综合）

**源文章**：[[2026-06-27-ncc-consciousness-where]] —《意识在哪里？——神经相关物（NCC）框架与 2025 年大脑意识科学的真实地平线》

**核心任务**：推进裁决 C-2026-05-31-01（IIT 后方皮层同步预测 vs COGITATE）和 C-2026-05-31-02（GWT 偏移点燃预测 vs COGITATE）；引入 NCC 三分法框架作为意识理论讨论的基础架构。

**新建页面（1）**：
- `concepts/neural-correlates-of-consciousness.md`（意识的神经相关物 NCC）🟢 mainstream / 置信度高 — Crick & Koch 纲领；最小性+充分性约束；Koch 等（2016）三分法（内容特异 NCC / 完整 NCC / 使能 NCC）；COGITATE 2025 实验裁决摘要；无报告范式的方法学意义；两个竞争框架（GWT/IIT）对 NCC 预测的比较表

**修订页面（4）**：
- `theories/global-workspace-theory.md`（修订 #6）— 新增 NCC 三分法定位（GWT 主要描述使能+完整 NCC）；补充 GNW 回应论文（PMC12510449）四个论点；强调阈限刺激范式是 GWT 真正检验场景；新增 neural-correlates-of-consciousness 到 related
- `theories/integrated-information-theory.md`（修订 #3）— 新增 NCC 三分法定位（IIT 主要描述内容特异 NCC）；补充可证伪性讨论（Lakatos 框架：gamma 同步是辅助假说带而非硬核）；新增 neural-correlates-of-consciousness 到 related
- `concepts/consciousness-ignition.md`（修订 #5）— 补充 GNW 回应论点（offset ignition 从未是核心预测）；NCC 三分法视角（点燃是使能 NCC 的时间动力学描述）；新增 neural-correlates-of-consciousness 到 related
- `concepts/posterior-cortical-hot-zone.md`（修订 #2）— 补充 NCC 三分法视角（PCHZ = 内容特异 NCC 定位假说）；补充 Boly et al. 2017 临床证据（完全额叶切除不影响意识；214 倍植物状态风险）；新增 neural-correlates-of-consciousness 到 related

**矛盾处理**：
- C-2026-05-31-01（IIT 后方同步 vs COGITATE）：evidence_update 补充——GNW 回应论文（PMC12510449）提供额外视角；claim_B 证据进一步积累；裁决仍 open，需要直接测量 Φ 的实验；
- C-2026-05-31-02（GWT 偏移点燃 vs COGITATE）：evidence_update 补充——GNW 回应明确指出偏移点燃从未是核心预测，脑范围广播被确认；裁决仍 open，但 GWT 防线得到明确；新增可证伪性作为核心未解问题

**图谱更新**：新增节点 1（neural-correlates-of-consciousness）；新增边 11 条（NCC→GWT/IIT/posterior-hot-zone/consciousness-ignition/phi-measure/predictive-coding/prefrontal-cortex/v1 + 反向边 2 条）

**新增未解问题**：Q-ncc-01（无报告范式完整 NCC，高优先）、Q-ncc-02（相关性到因果性，高优先）、Q-ncc-03（三类 NCC 边界，中优先）

**下一步建议**：BDNF（仍是悬空引用，被多页引用）；预测编码与 NCC 的整合框架（Q-gwt-04）；阿尔茨海默病分子机制（连接神经发生-AD 线）

---

## 2026-06-26（第 62 篇·大脑的自我更新·成年齿状回神经发生与模式分离）

**源文章**：[[2026-06-26-adult-neurogenesis-dentate-gyrus]] —《大脑的自我更新：成年齿状回如何生产新神经元，以及一场三十年未决的科学之争》

**新建页面（1）**：
- `concepts/adult-neurogenesis.md`（成年神经发生）🟡 emerging / 置信度中 — 五阶段分化程序（qNSC→成熟颗粒细胞）；GABA 开关两阶段功能（协作期→竞争期）；关键期可塑性（NR2B、低 LTP 阈值）；前馈抑制机制支持模式分离；人类争议：Sorrells 2018 vs Boldrini 2018 → Moreno-Jiménez 2019 方法论破局（固定时间）→ snRNA-seq 独立确认；碳-14 定年（~700/天）；AD 中神经发生衰退

**修订页面（2）**：
- `concepts/hippocampal-neurogenesis.md`（修订 #2）— 新增 GABA 开关机制详解；更新人类神经发生评估（从"争议尚未解决"升级为"多维证据支持"）；方法论破局分析（固定时间）；snRNA-seq 证据（Zhou 2022）；AD 连接；证据表更新 3 行；连接新增 adult-neurogenesis、pattern-separation、alzheimers-disease；key_sources 新增 4 篇
- `concepts/pattern-separation.md`（修订 #2）— 神经发生机制部分深化：GABA 开关两阶段程序、关键期分子特性（NR2B）、前馈抑制机制、Clelland 2009 必要性证据；证据表新增 2 行；连接新增 adult-neurogenesis

**矛盾登记**：无新矛盾（Q-adult-neurogenesis-human-controversy 状态更新：从"有争议"升级为"多维证据汇聚支持存在，但规模不确定"，不需要新矛盾条目，因为不是新旧证据对立而是方法论统一）

**图谱更新**：新增节点 1（adult-neurogenesis）；新增边 9 条；修复 _graph.json JSON 格式错误（2026-06-25 遗留的缺少逗号和尾随逗号）；hippocampal-neurogenesis 节点 status→emerging

**新增悬空引用（待填补）**：
- `bdnf`（BDNF/TrkB 信号，被 adult-neurogenesis 和 hippocampal-neurogenesis 引用）

**新增未解问题**：Q-neurogenesis-AD（高优先级）、Q-gaba-switch-timing（中优先级）

---

## 2026-06-25（第 61 篇·当大脑把碎片缝合在一起·伽马振荡与神经绑定）

**源文章**：[[2026-06-25-gamma-oscillations-neural-binding]] —《当大脑把碎片缝合在一起：伽马振荡与神经绑定之谜》

**新建页面（1）**：
- `concepts/binding-by-synchrony.md`（绑定假说）🟡 contested / 置信度中 — Gray & Singer 1989 提出的神经绑定假说；PING/ING 机制作为伽马振荡基础；CTC 框架（Fries 2015）的通信窗口解释；支持证据（Garrett & Halgren 2024：语言绑定时 co-ripples）与反对证据（Costa & Castelo-Branco 2024：视觉整合时伽马反而降低）；未解因果问题（Q-gamma-bind-01/02/03）

**修订页面（1）**：
- `concepts/gamma-oscillations.md`（修订 #2）— 新增绑定假说维度（Gray & Singer 1989 证据）；ING 机制补充；CTC 框架；Costa 2024 反例（γ 在分离时升高）；Williams 2026 ING-PING 转换；精神分裂症 Sklar 2024；新增 related 节点 3 个；新增 key_sources 5 篇；opens_questions 新增 3 条

**矛盾登记**：无新矛盾（C-2026-05-31-01 更新状态说明：新证据进一步支持"IIT 伽马同步预测过于具体"，但矛盾仍 open；C-2026-06-22-01 无更新）。

**新增悬空引用（待填补）**：
- `binding-problem`（绑定问题背景，被 binding-by-synchrony 引用）
- `co-ripples`（高频共振波机制，被 binding-by-synchrony 引用）
- `visual-cortex-v4`（V4 区域页，被 binding-by-synchrony 和 gamma-oscillations 引用）

**新增未解问题**：Q-gamma-bind-01（高）、Q-gamma-bind-02（中）、Q-gamma-bind-03（高）

---

## 2026-06-24（第 60 篇·记忆不混淆的秘密·CA3 吸引子与 DG-CA1 模式分离）

**源文章**：[[2026-06-24-hippocampal-ca3-pattern-completion]] —《记忆不混淆的秘密：CA3 的吸引子动力学与海马如何在「自动补全」与「精准分离」之间走钢丝》

**新建页面（4）**：
- `concepts/pattern-completion.md`（模式补全）🟢 established / 置信度高 — CA3 循环连接 + Hopfield 吸引子动力学；苔状纤维"强制激活"编码 vs 穿孔通路检索的双输入系统；Nakazawa 2002 CA3-NR1 KO 因果证据（PMID:12040087）；吸引子收敛是"记忆提取"的计算本质
- `concepts/pattern-separation.md`（模式分离）🟢 established / 置信度高 — DG 扩张重编码（5×）+ 稀疏激活（<5%）→ 相似输入的神经表征正交化；Leutgeb 2007 DG 全局重映射证据（PMID:17303747）；Sahay 2011 成人神经发生因果改善分离（PMID:21460835）；CA3 的速率重映射（小差异）vs 全局重映射（大差异）梯度机制
- `concepts/attractor-network.md`（吸引子网络）🔵 mainstream / 置信度中 — Hopfield 网络（1982）数学基础；存储容量约 0.14N；现代 Hopfield 网络 = Transformer softmax attention 的数学等价（Ramsauer 2021, arXiv:2008.02217）；连续吸引子（工作记忆/头向细胞）；CA3 生物实现
- `concepts/complementary-learning-systems.md`（互补学习系统）🔵 mainstream / 置信度中 — O'Reilly & McClelland 1994 框架（PMID:7704110）；稳定性-可塑性困境；海马（快/稀疏）+ 新皮层（慢/分布式）；SWR 睡眠重放是知识转移机制；深度强化学习经验回放缓冲区（DQN）是 CLS 理论的直接工程应用

**修订页面（3）**：
- `neurons/hippocampal-circuit.md`（修订#9）— 新增 CA3 模式补全的因果证据（Nakazawa 2002, PMID:12040087）和 CA3 vs CA1 不同计算个性（Leutgeb 2004, PMID:15272123）；related 新增 4 项；key_sources 新增 4 篇
- `concepts/ltp.md`（修订#8）— 新增 CA3 循环突触 NMDAR-LTP 与模式补全因果链的连接；related 新增 pattern-completion、complementary-learning-systems
- `concepts/place-cells.md`（修订#2）— 加入模式分离视角（重映射 = 空间记忆中模式分离的具体表现）；related 新增 pattern-separation、pattern-completion

**矛盾登记**：无新矛盾。

**悬空引用（新增，待填补）**：
- `adult-neurogenesis`（成人神经发生，被 pattern-separation 引用）
- `dentate-gyrus`（齿状回，被 pattern-separation, pattern-completion 引用，目前合并在 hippocampal-circuit）
- `ca3-recurrent-collaterals`（CA3 循环侧支，被 pattern-completion 引用，目前合并在 hippocampal-circuit）

---

## 2026-06-23（第 59 篇·小脑的秘密·运动预测与多层可塑性）

**源文章**：[[2026-06-23-cerebellum-motor-prediction]] —《小脑的秘密：浦肯野细胞如何让大脑成为一台预测机器》

**新建页面（3）**：
- `systems/cerebellum.md`（小脑）🟢 established / 置信度高 — 小脑解剖（三层皮层/DCN）；PF-LTD → 多层可塑性；前向/逆向模型（Wolpert 1998）；CCAS（认知情感综合征，Schmahmann 1998）；De Zeeuw 2021 双向微区综合框架
- `concepts/cerebellar-ltd.md`（小脑 LTD）🟢 established / 置信度高 — mGluR1/IP₃/PKC/AMPAR 内吞五步级联；与海马 NMDA-LTD 的根本差异；Schonewille 2011 "无 LTD 照样学习"挑战；Hansel 2026 预印本 400ms 时间窗口
- `concepts/forward-model.md`（前向模型）🔵 mainstream / 置信度中 — 给定传出拷贝预测运动感觉后果；逆向模型（计算运动指令）；小脑的内部模型功能；MOSAIC 多模块扩展；认知领域扩展可能性

**修订页面（3）**：
- `concepts/ltd.md`（修订#2）— 新增小脑 LTD 独特性段落（mGluR1/PKC，与 NMDA-LTD 并列）；related 新增 cerebellar-ltd, cerebellum；连接段新增两项
- `theories/predictive-coding.md`（修订#5）— 新增"小脑专用预测误差学习系统"段落（前向模型→攀爬纤维误差→LTD更新）；related 新增 cerebellum, forward-model
- `systems/motor-cortex.md`（修订#2）— 新增"小脑-运动皮层闭环"段落（皮质-脑桥-小脑→DCN→VL丘脑→M1回路）；related 新增 cerebellum, forward-model；连接段新增两项

**矛盾登记**：无新矛盾（Schonewille 2011 挑战 LTD 中心论已是已知历史争议，不新登记为 open 矛盾，但在文章和 wiki 中如实呈现两方证据）

**悬空引用（新增，待填补）**：
- `climbing-fiber`（攀爬纤维，被 cerebellum, cerebellar-ltd 引用）
- `parallel-fiber`（平行纤维，被 cerebellum, cerebellar-ltd 引用）
- `deep-cerebellar-nuclei`（深部小脑核，被 cerebellum 引用）
- `spinocerebellar-ataxia`（脊髓小脑性共济失调，被 cerebellum 引用）

---

## 2026-06-22（第 58 篇·网格细胞与场所细胞·填补6个长期悬空引用）

**源文章**：[[2026-06-22-grid-cells-place-cells]] —《六边形的秘密：内嗅皮层网格细胞如何为大脑装备空间坐标系》

**新建页面（6）**：
- `concepts/place-cells.md`（场所细胞）🟢 established / 置信度高 — O'Keefe & Dostrovsky 1971；稀疏编码；重映射（不同环境正交）；θ相位前移；SWR重播；认知地图基本单元
- `concepts/grid-cells.md`（网格细胞）🟢 established / 置信度高 — Hafting等2005 Nature；六边形格点；三参数描述；4–7离散模块（√2比，Stensola 2012）；路径整合坐标输出；发育研究（Qu 2026 Cell）
- `concepts/path-integration.md`（路径整合）🟢 established / 置信度高 — McNaughton等2006；连续吸引子网络；联合细胞整合速度×方向；漂移需地标校准
- `concepts/cognitive-map.md`（认知地图）🔵 mainstream / 置信度高 — Tolman 1948到场所/网格双系统；泛化到情节记忆、心理模拟（Bellmund 2016）、概念空间（Viganò 2023）
- `concepts/theta-phase-precession.md`（θ相位前移）🟢 established / 置信度高 — O'Keefe & Recce 1993；100–355°相位位移；θ序列时间压缩（20:1）；STDP时间窗口框架
- `systems/entorhinal-cortex.md`（内嗅皮层）🟢 established / 置信度高 — MEC（网格/联合细胞）vs LEC（情境感觉）；Layer II-VI功能层级；AD最早受损皮层（Braak分期）

**修订页面（2）**：
- `concepts/theta-oscillations.md`（修订#3）— 修正悬空引用：place-cell→place-cells、grid-cell→grid-cells、phase-precession→theta-phase-precession；related新增 path-integration、entorhinal-cortex
- `concepts/sharp-wave-ripples.md`（修订#5）— 修正悬空引用：place-cell→place-cells；source_articles新增2026-06-22

**矛盾登记**：
- C-2026-06-22-01（OPEN）：人类网格信号稳定性争议。Bellmund 2016 / Nau 2018 等多项fMRI研究发现六边形对称信号 vs Kransberg 2026（PMID:41958631）预注册被动导航研究未检测到信号。性质：方法论差异（主动 vs 被动导航）。登记于 state/contested_claims.json。

**悬空引用**（新增，待填补）：
- `head-direction-cells`（头朝向细胞，被 grid-cells、path-integration 引用）
- `border-cells`（边界细胞，被 cognitive-map、entorhinal-cortex 引用）
- `remapping`（重映射机制，被 place-cells、cognitive-map 引用）

**图谱更新**：新增节点6（place-cells, grid-cells, path-integration, cognitive-map, theta-phase-precession, entorhinal-cortex）；修订节点2（theta-oscillations, sharp-wave-ripples）；新增有向边26条（总计：100节点/559边）

---

## 2026-06-21（第 57 篇·运动皮层·课程路线3 运动系统缺口填补）

**源文章**：[[2026-06-21-motor-cortex-voluntary-movement]] —《从意图到动作——运动皮层如何用旋转的神经交响乐指挥肌肉》

**新建页面（5）**：
- `systems/motor-cortex.md`（运动皮层）🟢 established / 置信度高 — M1/PMC/SMA分层组织；Betz细胞；均质小人；群体向量编码、旋转动力学、输出零空间三框架综合
- `concepts/population-vector-coding.md`（群体向量编码）🟢 established / 置信度高 — Georgopoulos 1986 Science；单神经元宽泛调谐→群体向量精确预测方向；心理旋转732°/s
- `concepts/rotational-dynamics-motor.md`（旋转动力学）🟡 mainstream / 置信度高 — Churchland 2012 Nature；执行期2–2.8 Hz旋转；动力学引擎而非参数地图；RNN可复现
- `concepts/output-null-space.md`（输出零空间）🟡 mainstream / 置信度高 — Kaufman 2014 NatNeuro；准备期活动集中于零空间（调谐比4.5×）；几何机制解释准备不触发运动
- `circuits/mirror-neurons.md`（镜像神经元）🟡 mainstream / 置信度中等 — Gallese/Rizzolatti 1996 Brain；F5区17%双重激活（执行+观察）；F5/BA44同源；语言演化假说

**修订页面（1）**：
- `systems/language-network.md`（修订#2）— 新增镜像神经元（F5/BA44同源）与运动皮层的连接；related 新增 mirror-neurons, motor-cortex；语言演化的动作理解背景

**矛盾登记**：无新矛盾

**悬空引用**：新增 `corticospinal-tract`（皮质脊髓束，motor-cortex 和 dorsal-language-stream 均引用）

**图谱更新**：新增节点5（motor-cortex, population-vector-coding, rotational-dynamics-motor, output-null-space, mirror-neurons）；修订节点1（language-network）；新增有向边12条（总计：88节点/505边）

---

## 2026-06-20（第 56 篇·双流语言网络·课程路线7 语言与抽象思维 首篇）

**源文章**：[[2026-06-20-language-dual-stream]] —《语言的解剖：双流网络如何将声波解码为思想》

**新建页面（5）**：
- `systems/language-network.md`（语言网络）🟢 established / 置信度高 — Hickok & Poeppel 2007 双流模型；腹侧流（声音→意义，双侧）+ 背侧流（声音→动作/句法，左侧主导）；超模态证据（手语研究）；主动预测性
- `systems/broca-area.md`（Broca区）🟢 established / 置信度高 — BA44（pars opercularis，层级句法Merge运算，背侧流）vs BA45（pars triangularis，语义工作记忆，腹侧流）内部分工；Friederici 2020 发育证据
- `concepts/arcuate-fasciculus.md`（弓状束）🟢 established / 置信度高 — 背侧流主干白质通路；左侧优势；出生时低髓鞘化随句法习得成熟；损伤→传导性失语
- `circuits/dorsal-language-stream.md`（背侧语言流）🟢 established / 置信度高 — A1→颞平面→Spt→弓状束→BA44→运动皮层；音韵短期记忆+句法层级运算；左侧主导
- `circuits/ventral-language-stream.md`（腹侧语言流）🟢 established / 置信度高 — A1→MTG/STS→ITG→角回→BA45；声音→词义映射；双侧分布；具身语义（工具词→运动皮层，动物词→视觉皮层）

**修订页面（3）**：
- `concepts/working-memory.md`（修订#5）— 新增语音回路（phonological loop）对应背侧流Spt↔BA44环路的描述；related 新增 dorsal-language-stream, language-network
- `theories/predictive-coding.md`（修订#5）— 新增语言预测编码实例（词前200ms语义-感觉运动预测，Grisoni 2024）；related 新增 language-network, ventral-language-stream
- `systems/default-mode-network.md`（修订#4）— 新增角回（BA39）作为DMN-语言网络共享节点；related 新增 language-network, ventral-language-stream

**矛盾登记**：无新矛盾（语言网络的双流分工已被多来源独立支持，证据一致）

**悬空引用**：新增潜在悬空引用待补：
- `wernicke-area`（颞上回语音区，与 language-network 密切相关）
- `embodied-semantics`（具身语义，ventral-language-stream 中的核心机制）
- `planum-temporale`（颞平面，语音时序分析节点）

**图谱更新**：新增节点5（language-network, broca-area, arcuate-fasciculus, dorsal-language-stream, ventral-language-stream）；修订节点3（working-memory, predictive-coding, default-mode-network）；新增有向边约20条

---

## 2026-05-31（第 36 篇·注意瞬盲·填补 Q-gwt-02 + Q-cogitate-02·课程路线8 意识与自我 第五篇）

**源文章**：[[2026-05-31-attentional-blink]] —《注意瞬盲：当意识成为稀缺资源，大脑如何在时间中撞墙》

**新建页面（1）**：
- `concepts/attentional-blink.md`（注意瞬盲）🔵 mainstream / 置信度高 — 填补 consciousness-ignition 和 global-workspace-theory 的悬空引用；RSVP 范式中 T1 后 200–500ms 内 T2 感知抑制；Chun & Potter 双阶段模型 + GWT 工作空间占据机制；270ms MEG 神经分叉是 GWT 有/无意识分叉最直接证据；全有全无 vs 梯度标记为 contested

**修订页面（2）**：
- `theories/global-workspace-theory.md`（修订#5）— 新增 attentional-blink 相关链接；新增注意瞬盲三行证据（270ms 分叉、双峰分布、掩蔽 vs 瞬盲分离）；更新 source_articles 和 key_sources；标注注意瞬盲是 COGITATE 未能检验的核心场景的直接补充
- `concepts/consciousness-ignition.md`（修订#4）— 填充 attentional-blink 悬空引用（添加说明文字）；更新 source_articles；新增修订历史行

**矛盾登记**：无新矛盾（现有矛盾状态未变化：C-2026-05-31-01 和 C-2026-05-31-02 仍 open）

**悬空引用解决**：
- `attentional-blink`（已解决）：consciousness-ignition.md（related 字段）和 global-workspace-theory.md（related 字段）均引用此 slug，今日新建页面，悬空消除

**图谱更新**：新增节点 1（attentional-blink）；新增有向边 7；总计 83 节点 493 条边

---

## 2026-05-31（第 35 篇·COGITATE预注册对决意识理论·裁决矛盾 C-2026-05-31-01 & C-2026-05-31-02·课程路线8·意识与自我 + 方法论）

**源文章**：[[2026-05-31-cogitate-adversarial-test-consciousness]] —《当意识理论遭遇实验法庭：COGITATE预注册对决如何同时挑战IIT与全局工作空间理论》

**新建页面（1）**：
- `methods/adversarial-collaboration.md`（对抗性协作）🟡 emerging / 置信度高 — 理论家共同预注册预测+通过/失败标准；COGITATE 2025 是最大规模实践（256人，3模态，IIT vs GNWT）；操作化争议是核心局限

**修订页面（3）**：
- `theories/integrated-information-theory.md`（修订#2）— 补充 COGITATE 全文精确数字（3.8% 电极持续激活，BF₀₁=1.15–4.9，<0.75s 同步，方向信息 0.5s 后衰减）；新增 adversarial-collaboration 相关链接；key_sources 补充 PMID:32135090
- `theories/global-workspace-theory.md`（修订#4）— 补充 COGITATE 精确数字（0/655 offset ignition，PFC 70% 0.2-0.4s，BF₀₁=1.94×10⁴）；更新证据表（拆分 PFC 解码条目+新增 offset ignition 失败行）；新增 adversarial-collaboration 相关链接
- `concepts/consciousness-ignition.md`（修订#3）— 证据表新增 offset ignition 完全缺失行（0/655）+ onset 时序偏差行；新增 Q-cogitate-02 于未解问题；source_articles 补充 COGITATE 文章

**矛盾裁决进展**：
- C-2026-05-31-01（IIT 后方皮层同步 vs COGITATE 否定）：**未裁决，但已深化**。COGITATE 全文数字（3.8% 电极，BF₀₁=1.15–4.9）进一步支持 claim_B（IIT 同步预测失败），但 IIT 理论家认为操作化不完全代表理论核心。状态维持 open，confidence 降级记录在 wiki。
- C-2026-05-31-02（GNWT offset ignition vs COGITATE 否定）：**未裁决，但已深化**。0/655 电极的 offset ignition 极强地支持 claim_B（GNWT 预测失败），但 GNWT 阵营争辩操作化版本非核心预测。状态维持 open。

**新增悬空引用**：无（图谱 83 节点 492 条边，无悬空边）

---

## 2026-05-31（第 34 篇·REM睡眠与情绪记忆·深化课程路线4·学习与记忆 + 课程路线6·情绪与动机）

**源文章**：[[2026-05-31-rem-sleep-emotional-memory]] —《情绪炼金炉：REM睡眠如何重写记忆的情感底色》

**新建页面（2）**：
- `concepts/rem-sleep.md`（REM睡眠）🟢 established / 置信度高 — NE真空（蓝斑沉默）+ θ振荡 + 杏仁核-海马θ同步三机制；情绪记忆去饱和化的离线窗口；Boyce 2016光遗传因果（仅REM期沉默MS GABA→θ消失→情境记忆损害）；van der Helm 2011人类fMRI（REM睡眠降低杏仁核情绪反应）；Walker SFSR假说
- `concepts/emotional-memory-depotentiation.md`（情绪记忆去饱和化）🟡 emerging / 置信度中 — REM期NE≈0 → θ谷值驱动LA突触类LTD → 情绪色彩选择性弱化、事实内容保留；Poe θ相位反转假说（峰值→谷值）；Totty 2017 LA-VH 180°反相 (R=0.954)；PTSD可能是去饱和化失败

**修订页面（3）**：
- `concepts/fear-extinction.md`（修订#2）— 当前理解节新增REM睡眠巩固段落（Totty 2017 LA-VH θ相位差，Walker SFSR）；frontmatter新增rem-sleep/theta-oscillations/emotional-memory-depotentiation至related，Q-rem-01/Q-rem-02至opens_questions，PMID:28729826/PMID:19702380至key_sources
- `concepts/theta-oscillations.md`（修订#2）— 新增「REM睡眠θ：情绪记忆巩固的相位窗口」机制节（清醒/REM θ功能对比表，LA-VH θ相位差机制，Boyce 2016因果链）；当前理解节补充REM θ段落；关键证据表新增2行；连接新增rem-sleep/fear-extinction/emotional-memory-depotentiation；opens_questions新增Q-rem-01/Q-rem-03/Q-rem-05
- `concepts/memory-consolidation.md`（修订#5）— 当前理解节新增REM睡眠角色段落（Boyce 2016因果链、van der Helm 2011、Walker SFSR假说）；关键证据表新增2行；Q-rem-sleep-role标记为部分解答；related新增rem-sleep/emotional-memory-depotentiation

**矛盾登记（0）**：θ相位反转假说（Poe）机制细节仍待验证，已登记为Q-rem-03；SFSR假说在人类层面证据仍弱，已在文章和wiki中标注置信度差异

**新增未解问题（5）**：Q-rem-01（LA-VH θ同步细胞机制）、Q-rem-02（θ相位反转是否区分不同强度情绪记忆）、Q-rem-03（θ峰值→谷值转变的充分/必要性）、Q-rem-04（人类REM去饱和化的个体差异来源）、Q-rem-05（增强REM θ是否改善情绪调节或治疗PTSD）

**图谱变化**：82节点（+2），486边（+18）

---

## 2026-06-19（第 33 篇·睡眠纺锤波·深化课程路线4·学习与记忆）

**源文章**：[[2026-06-19-sleep-spindles-nrem]] —《当大脑钟声响起：睡眠纺锤波的丘脑起源与记忆巩固的时间建筑学》

**新建页面（3）**：
- `concepts/sleep-spindles.md`（睡眠纺锤波）🟢 established / 置信度高 — TRN CaV3.3 T型钙通道驱动TRN↔TC振荡环路生成12–15 Hz纺锤波；皮层树突L型Ca²⁺预热窗口；CACNA1I精神分裂症风险基因；SO-spindle-SWR三重嵌套中间层；Latchoumane 2017因果实验（三重耦合必要）
- `circuits/thalamocortical-circuit.md`（丘脑-皮层回路）🟢 established / 置信度高 — TRN（CaV3.3）↔TC（CaV3.1）振荡回路是纺锤波起搏器；核心/矩阵双通路；皮层-丘脑反馈（CT第六层）调制纺锤波振幅；清醒（强直）vs睡眠（爆发）模式切换
- `concepts/cortical-slow-oscillation.md`（皮层慢振荡）🟢 established / 置信度高 — NREM深睡眠0.5–1 Hz UP/DOWN态交替；起源PFC向后传播；SO上行相触发纺锤波（CT→TRN）；三重奏顶层时间框架

**修订页面（2）**：
- `concepts/memory-consolidation.md`（修订#4）— NREM三重奏小节深化：纺锤波主动触发机制（CT→TRN→钙预热）；Latchoumane 2017因果实验；related/prerequisites新增sleep-spindles、cortical-slow-oscillation、thalamocortical-circuit
- `concepts/sharp-wave-ripples.md`（修订#4）— related新增sleep-spindles和cortical-slow-oscillation；key_sources扩充3个（三重耦合文献）；source_articles新增2026-06-19

**矛盾登记（0）**：今日文章核心机制（TRN纺锤波生成、三重耦合）在领域内无重大争议；CaV3.1 vs CaV3.3 分工已登记为"快/慢纺锤波待厘清"的开放问题，但不属于矛盾协议范围

**新增未解问题（3）**：Q-spindle-fast-vs-slow、Q-spindle-augmentation-clinical、Q-spindle-rem-division

**图谱变化**：80节点（+3），468边（+16）

---

## 2026-06-18（第 32 篇·连接组学：接线图之上·首次覆盖课程路线9·Connectomics）

**源文章**：[[2026-06-18-connectomics-wiring-diagram]] —《接线图之上：当我们拥有了完整神经地图，理解大脑的征途才刚刚开始》

**新建页面（2）**：
- `methods/connectomics.md`（连接组学）🟢 established / 置信度高 — 用串行电子显微镜重建神经元全突触接线图的方法；C. elegans（302神经元，White 1986）→果蝇FlyWire（139,255神经元，Dorkenwald 2024）；揭示小世界、富人俱乐部、前馈回路主题等网络拓扑原理；斑马鱼脑干连接组成功预测眼动吸引子动力学（Vishwanathan 2024）；核心局限：突触权重/动力学状态/个体差异均超出静态连接图的描述能力
- `concepts/circuit-motifs.md`（回路主题）🔵 mainstream / 置信度高 — 神经回路中反复出现的小型拓扑模式（前馈回路FFL、反馈循环、富人俱乐部rich-club）；可能反映神经计算基本需求；Drosophila全脑连接组（Lin 2024，30%枢纽神经元，前馈回路过表达）提供最大规模系统验证；蘑菇体15个学习隔室为典型应用

**修订页面（0）**：无修订现有页面

**矛盾登记（0）**：无新矛盾（连接组学主要发现在该领域内无重大争议，结构-功能鸿沟为领域共识）

**新增悬空引用待补**：
- `c-elegans-nervous-system` — 专用的 C. elegans 神经系统页面（可从 connectomics 主页分拆）
- `mushroom-body` — 果蝇蘑菇体专页（connectomics 文章中有详细内容但缺独立wiki页）
- `stomatogastric-ganglion` — 螃蟹/龙虾胃神经节作为神经调质改变回路功能的经典案例；connectomics 局限论点的关键实验系统

**图谱**：节点 75→77，边 438→452（新增14条边，围绕 connectomics 和 circuit-motifs 两个新节点建立连接）

---

## 2026-05-31（第 31 篇·五月月报·大图景·三十篇文章的跨月整合）

**源文章**：[[2026-05-31-may-monthly-synthesis]] —《五月月报·大图景：从一个动作电位到世界模型——三十篇文章如何拼出大脑构建认知的完整弧线》

**新建页面（1）**：
- `concepts/temporal-hierarchy.md`（时间层级编码）🔵 mainstream / 置信度高 — 从纳秒到终身的多时间尺度并行计算框架；从SNARE融合（100μs）到威胁记忆（终身）的完整时间谱；是世界模型架构的时间维度

**修订页面（1）**：
- `concepts/world-model.md`（世界模型）— revision_count 1→2；将六层架构扩展为八层分层贝叶斯预测机器；related 新增 temporal-hierarchy、sharp-wave-ripples、integrated-information-theory；补充 COGITATE 2025 对顶层意识理论的挑战

**矛盾登记（0）**：无新矛盾（月度综合不引入新实验数据）

**新增悬空引用待补**：
- `hebbian-learning` — world-model prerequisites 引用但独立页面不足（已有内容在 ltp.md 中）
- `active-inference` — 月度大图景提及但缺独立页面（高优先级：下月优先补充）
- `bayesian-brain` — 整合框架缺独立页面

**图谱**：节点 74→75，边 428→438（新增10条边，连接 temporal-hierarchy 到各时间尺度机制）

---

## 2026-06-17（第 30 篇·海马锐波涟漪与记忆重放·多项2024-2026新发现整合）

**源文章**：[[2026-06-17-sharp-wave-ripples-memory-replay]] —《夜晚，大脑重写自己的神经地图——海马锐波涟漪、记忆选择与睡眠期巩固的新机制》

**新建页面（0）**：今日无新建页面（相关 wiki 页面均已存在）

**修订页面（3）**：

- `concepts/sharp-wave-ripples.md`（revision 2→3）：新增4个关键2024-2026新发现：(1) Robinson 2026 — 只有大振幅SWR亚集与海马-PFC同步再激活相关，光遗传增强SWR改善记忆（因果充分性证据）；(2) Yang 2024 — 清醒SWR作为记忆标记机制，标记经历供睡眠优先重放；(3) Giri 2024 — 睡眠剥夺SWR振幅降低、重放效率下降（SWR发生率≠有效性的分离证据）；(4) Chang 2025 — NREM睡眠微结构（NE/瞳孔状态）将新旧记忆重放分时段组织防止干扰；另新增 Ecker 2022 CA3模型（学习突触结构同时决定SWR生成与重放内容）；证据表从5行扩展到11行；未解问题从2增到5；related新增norepinephrine-locus-coeruleus和dopamine-reward-prediction-error

- `concepts/memory-consolidation.md`（revision 2→3）：证据表新增3行（Robinson 2026因果充分性、Chang 2025微结构分时、Yang 2024清醒标记）；key_sources扩充3项；related新增norepinephrine-locus-coeruleus；source_articles新增今日文章

- `neurons/hippocampal-circuit.md`（revision 7→8）：新增Ecker 2022关键发现：CA3学习依赖突触权重结构同时决定SWR生成与重放内容；key_sources新增PMID:35040779；source_articles新增今日文章

**矛盾登记（0）**：今日新证据与既有wiki页面主张一致；Robinson 2026、Yang 2024、Chang 2025均为既有框架的深化而非推翻

**新增悬空引用（0）**：所有新增related字段的节点均已有wiki页面

**图谱变化**：节点 74→74（无变化，无新页面），边 424→428（+4：SWR↔NE双向调控边 ×2、DA→SWR调控边、SWR→DA关联边）

---

## 2026-05-31（第 29 篇·整合信息理论 IIT·COGITATE 双重挑战）

**源文章**：[[2026-05-31-integrated-information-theory]] —《意识等于整合信息：一个方程式的野心与困境》

**新建页面（4）**：
- `theories/integrated-information-theory.md`（整合信息理论）🔴 contested / 置信度中 — 意识 = Φ（整合信息量）；五公理推导物理约束；后方皮层热区解剖预测；小脑/视网膜低 Φ 预测与临床一致；COGITATE 2025（Nature，256被试，3种成像）挑战核心机制预测（后方皮层同步缺失）；泛心论蕴含；前馈网络 Φ ≈ 0
- `concepts/phi-measure.md`（Φ 整合信息度量）🔴 contested / 置信度中 — IIT 核心量；最优分割时的因果信息损失；NP-hard 精确计算；IIT 2.0→3.0 演化；前馈/并行/循环网络对比；PCI 作为实用代理
- `concepts/posterior-cortical-hot-zone.md`（后方皮层热区）🔵 mainstream / 置信度中 — V1/V4/MT/下颞叶的高整合连接拓扑；内容特异 NCC vs 完整 NCC vs 使能 NCC 三分法；COGITATE 2025 对后方皮层同步预测（机制核心）的挑战
- `methods/perturbational-complexity-index.md`（扰动复杂性指数 PCI）🟢 established / 置信度高 — Casali 2013 奠基；TMS+EEG+Lempel-Ziv 压缩；区分清醒/NREM/麻醉/MCS/VS；Sarasso 2015 跨麻醉药对比；临床意识评估客观工具

**修订页面（2）**：
- `theories/global-workspace-theory.md`（revision 2→3）：新增 IIT vs GWT 核心分歧对比表（前额叶 vs 后方皮层；瞬态点燃 vs 持续激活）；COGITATE 2025 偏移点燃缺失和前额叶内容解码有限的详细记录；related 新增 integrated-information-theory 和 posterior-cortical-hot-zone
- `concepts/consciousness-ignition.md`（revision 1→2）：新增 COGITATE 2025 对点燃预测的挑战（刺激偏移时前额叶点燃缺失）；新增 IIT 对比框架（持续激活 vs 瞬态点燃）；related 新增 integrated-information-theory 和 posterior-cortical-hot-zone；source_articles 新增今日文章

**矛盾登记（2）**：
- C-2026-05-31-01（新）：IIT 预测后方皮层内部持续同步 vs COGITATE 2025 否定此预测 — open
- C-2026-05-31-02（新）：GWT 预测刺激偏移时前额叶点燃 vs COGITATE 2025 否定偏移点燃 — open（更新 consciousness-ignition 页面 confidence 降为中）

**新增悬空引用（待建页面）**：
- `panpsychism`（被 integrated-information-theory 引用）
- `adversarial-collaboration`（方法论概念，被 cogitate 讨论引用）

**图谱变化**：节点 70→74（+4），边 410→424（+14）

---

## 2026-05-31（第 28 篇·第四周综合·世界模型六层架构）

**源文章**：[[2026-05-31-week4-synthesis]] —《第四周综合：当大脑成为自己的宇宙——世界模型的六层建构架构》

**新建页面（1）**：
- `concepts/world-model.md`（世界模型）🟡 emerging / 置信度中 — 大脑对外部世界和自身状态持续维护的贝叶斯最优内部模型；六层架构（化学调控层→运动预测层→情感标注层→误差加权层→离线仿真层→意识广播层）整合第四周六篇文章；Friston 2010 自由能原理为数学框架；整合框架，非单一实验结论，置信度设为中；**第四周综合框架节点**

**修订页面（3）**：
- `theories/global-workspace-theory.md`（revision 1→2）：添加"GWT 作为世界模型意识广播层"的整合框架定位；related 新增 world-model；世界模型广播更新机制描述；DMN 先验生成器 vs GWT 广播基础设施的互补关系再次强调
- `theories/predictive-coding.md`（revision 3→4）：将预测编码定位为"世界模型误差加权更新层"；related 新增 world-model；明确更新方程 Δmodel ∝ precision_weighted_prediction_error
- `systems/default-mode-network.md`（revision 2→3）：将 DMN 定位为"世界模型离线仿真层"；related 新增 world-model；AD/DMN 连接补充世界模型视角

**矛盾登记（0）**：无新矛盾。六层世界模型框架为今日新提出的整合性概念工具，尚无与既有 wiki 主张的冲突（该框架有意标注为 emerging 和 medium confidence）。

**图谱更新**：70 节点（+1 world-model），410 条边（+10 edges）

---

## 2026-05-30（第 27 篇·意识·全局工作空间理论，课程路线8第二篇）

**源文章**：[[2026-05-30-global-workspace-theory]] —《当意识在大脑中"点燃"：全局工作空间理论与感知的临界翻转》

**新建页面（2）**：
- `theories/global-workspace-theory.md`（全局工作空间理论）🔵 mainstream / 置信度中 — Baars（1988）认知GWT → Dehaene-Changeux（1998–2011）神经GWT；点燃机制；三个意识神经标志；GWT vs IIT 2025年COGITATE对抗性合作结果（两者均受挑战）；课程路线8第二篇
- `concepts/consciousness-ignition.md`（意识点燃）🔵 mainstream / 置信度中 — 全有或全无的非线性临界翻转；~270-300ms 前额顶叶激活；双触发条件（感觉超阈 + 注意可用）；注意瞬盲范式的黄金证据（Sergent et al. 2005）；P3b EEG标志（Cohen et al. 2024 无报告范式挑战其地位）

**修订页面（3）**：
- `systems/default-mode-network.md`（revision 1→2）：部分回应 Q-dmn-04；添加 DMN（先验生成器）vs GWT工作空间（广播基础设施）的互补架构描述；related 新增 global-workspace-theory
- `theories/predictive-coding.md`（revision 2→3）：添加 GWT-预测编码整合：足够大的预测误差可能触发工作空间点燃；related 新增 global-workspace-theory
- `systems/prefrontal-cortex.md`（revision 1→2）：添加 dlPFC 在 GWT 点燃中的角色；related 新增 global-workspace-theory 和 consciousness-ignition；新增 van Vugt 2018 猕猴证据

**矛盾登记（0）**：无新矛盾（GWT vs IIT 的争议已作为已知理论分歧记录在文章中，不需要在矛盾登记册中作为新条目，因为这是理论间分歧而非同一事实的相互矛盾证据）

**新增悬空引用（待补缺口）**：
- `attentional-blink`（注意瞬盲）— 被 GWT 和 consciousness-ignition 页引用
- `p3-wave`（P3波）— 被 consciousness-ignition 页引用

**图谱更新**：69 节点，400 条边（+2 节点，+15 边）

---

## 2026-06-16（第 26 篇·全脑网络·默认模式网络，课程路线8开篇）

**源文章**：[[2026-06-16-default-mode-network]] —《当大脑"休息"时，它在做什么？——默认模式网络与大脑内部宇宙的构建逻辑》

**新建页面（1）**：
- `systems/default-mode-network.md`（默认模式网络）🟢 mainstream / 置信度高 — 大脑内部模拟基础设施；Raichle 2001 发现；Fox 2005 反相关（GSR 方法论争议）；Buckner 2008 综述；Andrews-Hanna 2011 双子系统（MTL子系统=情节记忆/场景构建；dMPFC子系统=心智化）；aMPFC+PCC枢纽节点；Buckner 2009 Aβ优先沉积枢纽节点；**课程路线8（意识与自我）首次进入**

**修订页面（3）**：
- `theories/predictive-coding.md`（revision 1→2）：related 新增 default-mode-network；修订历史追加"DMN 作为预测编码层级高层先验生成器"
- `neurons/hippocampal-circuit.md`（revision 6→7）：related 新增 default-mode-network；确认海马（MTL）是 DMN 核心节点；修订历史追加
- `diseases/alzheimers-disease.md`（revision 1→2）：related 新增 default-mode-network；dimensions 新增 whole-brain-network；新增 Aβ 优先沉积 DMN 枢纽节点（Buckner 2009）；修订历史追加

**登记矛盾（0）**：Fox 2005 的反相关发现存在 GSR 方法论争议，已在文章和 wiki 页面中标注，但不构成知识库既有主张的直接矛盾（既有页面未声称特定反相关强度值）。

**新增悬空引用 / 待补缺口（3）**：
- `salience-network` — DMN 切换的中介（突显网络），尚无独立页；被 default-mode-network 的描述中提及
- `task-positive-network` — DMN 的反相关对象，尚无独立页
- `self-referential-processing` — DMN 枢纽的核心计算（自我参照），尚无独立页

**图谱变动**：新增节点1（default-mode-network）；新增边14条；总计：67节点，385边

---

## 2026-06-15（第 25 篇·理论框架·预测编码）

**源文章**：[[2026-06-15-predictive-coding]] —《当大脑主动预测而非被动接收：预测编码理论如何重新定义视觉皮层的计算逻辑》

**新建页面（2）**：
- `theories/predictive-coding.md`（预测编码）🟡 mainstream / 置信度中 — 皮层层级反馈传预测/前馈传误差；Rao & Ballard 1999 奠基；Bastos 2012 分层映射（γ/α-β振荡分工）；Keller 2012 V1感觉运动失配实验；主动推断：行动也是预测误差最小化；注意=精度加权；DA-RPE 同一计算结构；**首个理论域页面，开创 theories/ 子目录**
- `concepts/precision-weighting.md`（精度加权）🟡 emerging / 置信度中 — 预测误差精度权重 π；注意=提升关键误差精度；ACh/NE/DA 是分子层面精度调节器；VIP-SST 去抑制是回路层面实现候选；精度失调=精神分裂症/孤独症理论框架

**修订页面（2）**：
- `systems/v1-primary-visual-cortex.md`（revision_count 2→3）：新增"预测编码视角下的V1"小节；纳入 Keller 2012 感觉运动失配实验（V1 L2/3 误差响应）、环绕抑制预测编码解释、分层振荡分工；related 新增 predictive-coding, precision-weighting；opens_questions 新增 Q-pc-04；key_sources 新增 PMID:22681686, PMID:10195184, PMID:23177956
- `concepts/dopamine-reward-prediction-error.md`（revision_count 2→3）：新增"DA-RPE 作为预测编码框架中奖励域预测误差"小节；纳入 Diederen & Fletcher 2021 (PMID:32338128) 整合框架；新增精神分裂症 aberrant salience 的精度失调解释；related 新增 predictive-coding, precision-weighting；key_sources 新增 PMID:32338128, PMID:20068583

**登记矛盾（0）**：无新矛盾。预测编码与现有 wiki 主张（V1、DA、ACh、增益控制）的关系是扩展和深化，而非冲突。

**新增悬空引用 / 待补缺口（3）**：
- `active-inference` — 在 predictive-coding 的 related 中引用，尚无独立页
- `free-energy-principle` — 预测编码理论的数学基础（Friston 2010），尚无独立页
- `aberrant-salience` — 精神分裂症的精度失调假说，尚无独立页（在精度加权页中提及）

**图谱**：节点 64→66，边 353→371。新增2节点（predictive-coding, precision-weighting），新增18条有类型边（predictive-coding↔v1/orientation/gain-control/DA-RPE/precision-weighting/working-memory/theta/ltp/nmda/temporal-coding-hierarchy/competition-selection-principle；precision-weighting↔predictive-coding/gain-control/ACh/NE/VIP/DA-RPE）。

---

## 2026-05-30（第 24 篇·情绪与动机首篇）

**源文章**：[[2026-05-30-amygdala-fear-memory]] —《当杏仁核学会恐惧——突触可塑性如何将一次经历铸成防御记忆，以及大脑为何难以遗忘》

**新建页面（3）**：
- `systems/amygdala.md`（杏仁核）🟢 established / 置信度高 — LA/BA/ITC/CeA四层架构；恐惧印迹~20%稀疏LA编码；ITC背侧/腹侧分工闸门；前额叶PL/IL双向控制；课程主题6（情绪与动机）首个系统页
- `concepts/fear-conditioning.md`（恐惧条件反射）🟢 established / 置信度高 — CS+US在LA汇聚→NMDA巧合检测→CaMKII→GluA1插入→LA-LTP；与海马LTP分子机器同构；Nabavi 2014光遗传双向因果证明
- `concepts/fear-extinction.md`（恐惧消退）🟢 established / 置信度高 — 消退≠遗忘（LTD去增强+新IL→ITC→CeM回路）；BA双群竞争（恐惧/消退神经元）；vmPFC激活预测消退质量；PTSD=消退记忆提取失败

**修订页面（2）**：
- `concepts/ltp.md`（revision_count 6→7）：新增LA-LTP是恐惧记忆因果底物（Nabavi 2014 PMID:24896183）；"LTP是通用跨区域联想学习算法"洞见明确化；related新增fear-conditioning、amygdala；key_sources新增PMID:24896183、PMID:11584069
- `concepts/norepinephrine-locus-coeruleus.md`（revision_count 1→2）：新增LC-杏仁核轴恐惧记忆机制（β受体→BLA-LTP→闪光灯记忆）；新增应激-NE-消退损害机制（Plas 2024）；related新增amygdala、fear-conditioning、fear-extinction；key_sources新增PMID:38370858

**登记矛盾（0）**：无新矛盾，新内容与已有wiki一致（LTP机器、印迹细胞稀疏编码、海马情景信息）

**解决悬空引用（0）**：今日新建节点amygdala/fear-conditioning/fear-extinction均为首次创建，填补了"情绪与动机"方向的重要空白

**新增悬空引用（待填）**：
- `reconsolidation`（记忆再巩固）— 被fear-extinction页引用
- `vmPFC`（腹内侧前额叶）— 被fear-extinction和amygdala页引用（与已有prefrontal-cortex页不同，vmPFC特指IL/infralimbic皮层）

**图谱**：节点 61→64，边 326→353（新增 27 条边）

---

## 2026-06-14（第四周第二篇·第 23 篇）

**源文章**：[[2026-06-14-parkinson-basal-ganglia-circuit]] —《多巴胺的沉默与节律的失控：帕金森病如何揭示大脑运动控制的回路逻辑》

**新建页面（3）**：
- `diseases/parkinsons-disease.md`（帕金森病）🟢 established / 置信度高 — α-突触核蛋白病理（Braak分期/路易小体）、Albin-DeLong回路失衡模型（直接/间接通路）、β振荡病理状态、DBS机制（β→θ振荡切换，Köhler 2024）
- `circuits/basal-ganglia.md`（基底节）🟢 established / 置信度高 — 完整回路解剖（纹状体/GPi/GPe/STN/SNc）、直接/间接/超直接通路、D1/D2受体的双向调节、振荡状态依赖性
- `concepts/beta-oscillations.md`（β振荡）🔵 mainstream / 置信度中 — 13-30 Hz抗运动振荡、PAC耦合证据（López-Azcárate 2010 n=15）、β→θ治疗机制（Köhler 2024 n=25）、与γ/θ振荡的功能对立

**修订页面（1）**：
- `concepts/dopamine-reward-prediction-error.md`（revision_count 1→2）：补充DA的双重功能（RPE教学信号 vs 基底节回路调节器）；新增PD作为DA-RPE系统崩溃极端案例的讨论；新增[[parkinsons-disease]]、[[basal-ganglia]]连接

**登记矛盾（0）**：无新矛盾（β振荡因果性争议为该领域已知开放问题，未触发与现有wiki页面的直接矛盾）

**新增悬空引用（1）**：
- `alpha-synuclein`：被 parkinsons-disease.md 的 related 字段引用，需单独文章覆盖（路易小体/错误折叠机制专页）

**图谱更新**：新增3个节点（parkinsons-disease, basal-ganglia, beta-oscillations），新增18条边；图谱总计61节点、326条边

---

## 2026-06-13（第四周第一篇·第 22 篇）

**源文章**：[[2026-06-13-serotonin-autoreceptor-ssri-delay]] —《血清素的慢时钟：为什么抗抑郁药需要等待两周？》

**新建页面（3）**：
- `systems/serotonin-raphe-system.md`（血清素-缝际核系统）🟢 established / 置信度高 — DRN/MRN解剖、体积传输机制、14种5-HT受体分类、与DA/ACh/NE系统的比较
- `concepts/5-ht-autoreceptor.md`（5-HT自受体与SSRI延迟起效）🔵 mainstream / 置信度高 — 5-HT1A树突自受体负反馈机制；自受体脱敏的分子机制（GRK/β-arrestin）；pindolol加速起效的临床RCT证据（Celada 2004 PMC446220）；5-HT1A/2A在PFC的功能拮抗
- `concepts/hippocampal-neurogenesis.md`（海马神经发生）🔴 contested / 置信度中 — 啮齿类SGZ神经发生证据充分；阻断神经发生→SSRI行为效果消失（Santarelli 2003）；人类成人神经发生存在与规模存在 Sorrells 2018 vs Boldrini 2018 的真实矛盾（已登记 status=contested）

**修订页面（2）**：
- `systems/neuromodulator-systems.md`（revision_count 2→3）：补全5-HT系统（第四个调质系统）；新增5-HT系统对比其他三种调质最严格自受体负反馈机制的说明；新增[[serotonin-raphe-system]]和[[5-ht-autoreceptor]]连接；key_sources新增 PMID:15309042、PMID:10462127
- `concepts/gain-control.md`（revision_count 2→3）：新增5-HT自受体脱敏作为"第四个时间尺度"（天-周，情绪/可塑性层）的增益控制形式；新增[[serotonin-raphe-system]]和[[5-ht-autoreceptor]]连接

**登记矛盾（0）**：无新矛盾（海马神经发生争议已作为 status=contested 处理，未触发与现有 wiki 页面的直接矛盾）

**新增悬空引用（1）**：
- `major-depressive-disorder`：被 serotonin-raphe-system.md 引用，需单独文章覆盖

**图谱更新**：新增3个节点（serotonin-raphe-system, 5-ht-autoreceptor, hippocampal-neurogenesis），新增21条边；图谱总计58节点、308条边

---

## 2026-05-30（第三周综合·第 21 篇）

**源文章**：[[2026-05-30-week3-synthesis]] —《第三周综合：大脑的增益控制架构——神经调质如何在多重时间尺度上重配神经回路》

**新建页面（1）**：
- `concepts/multi-timescale-plasticity.md`（多层增益控制架构）🟡 emerging / 置信度中 — 第三周综合框架；三层嵌套（STP层一/ACh-NE层二/DA-RPE层三）；Marder原则（PMID:23040802）：解剖连接体只提供骨架，调质状态决定功能回路；来自 Thiele & Bellgrove 2018（PMID:29470969）的注意调质综述支撑；状态设为 emerging 因三层整合框架尚未被单一实验直接验证

**修订页面（3）**：
- `concepts/gain-control.md`（revision_count 1→2）：新增"第三周综合更新"段落，将皮层增益控制（层二，ACh/NE）定位为多层架构的第二层；新增与 [[multi-timescale-plasticity]]、[[short-term-synaptic-plasticity]]、[[dopamine-reward-prediction-error]] 的连接；opens_questions 新增 Q-gain-timescale-interaction；key_sources 新增 PMID:23040802、PMID:29470969
- `systems/neuromodulator-systems.md`（revision_count 1→2）：新增 Marder 原则（PMID:23040802）作为调质系统理论框架；新增多层架构定位；related 新增 [[multi-timescale-plasticity]]、[[short-term-synaptic-plasticity]]；opens_questions 新增 Q-gain-timescale-interaction、Q-marder-principle-cortex
- `concepts/short-term-synaptic-plasticity.md`（revision_count 1→2）：新增 [[multi-timescale-plasticity]] 和 [[gain-control]] 连接；定位 STP 为多层架构层一；opens_questions 新增 Q-gain-timescale-interaction

**悬空引用新增（1）**：
- 无新增悬空引用；`multi-timescale-plasticity` 页面的 prerequisites 均已有对应节点

**悬空引用解决（0）**：今日综合文章未针对现有悬空引用，专注整合框架

**矛盾登记（0）**：今日无新矛盾。多层框架（STP/ACh-NE/DA-RPE）各层独立证据充分，整合框架本身是理论综合（emerging 状态）而非具体机制争议

**图谱更新**：
- 新节点：multi-timescale-plasticity（54→55 总节点）
- 新边（9）：STP→multi（part-of）, gain-control→multi（part-of）, DA-RPE→multi（part-of）, ACh→multi（supports）, NE→multi（supports）, multi→neuromodulator-systems（related）, multi→working-memory（mechanism-of）, multi→orientation-selectivity（mechanism-of）, multi→alzheimers-disease（related）

**新增未解问题（3）**：
- Q-gain-timescale-interaction（高优先级）：三层增益控制之间的相互作用是否可预测？
- Q-marder-principle-cortex（中优先级）：Marder原则在哺乳类皮层的直接验证？
- Q-gain-architecture-ai（低优先级）：AI系统中的多层增益控制等效物设计？

---

## 2026-06-12（第三周·第 6 篇，文章 #20）

**源文章**：[[2026-06-12-neuromodulators-ach-ne]] —《注意的化学语言：乙酰胆碱与去甲肾上腺素如何向大脑发出行动指令》

**新建页面（4）**：
- `concepts/acetylcholine-cortex.md`（皮层乙酰胆碱）🟢 established / 置信度高 — 皮层ACh系统首个专页；基底前脑（Meynert核Ch4）解剖；M1受体（Gq→减少K⁺漏电流→促进持续放电）/M2受体（Gi→突触前自受体→负反馈）/α4β2+α7 nAChR功能分工；双时间尺度（紧张背景+相位爆发）；皮层去同步化；核心来源：Herrero 2008（PMC2666819）
- `concepts/norepinephrine-locus-coeruleus.md`（去甲肾上腺素/蓝斑系统）🟢 established / 置信度高 — NE系统首个专页；蓝斑（LC）解剖（约5万个神经元，投射全皮层）；α2A（高亲和力Gi→HCN抑制→PFC WM稳定）/α1（低亲和力Gq→噪声增加）/β（Gs→LTP促进）三受体分工；倒U型调节曲线；相位-紧张模式（Aston-Jones & Cohen 2005）；PFC→LC自上而下控制
- `systems/neuromodulator-systems.md`（神经调质系统总览）🟢 established / 置信度高 — 四大调质系统（ACh/NE/DA/5-HT）首个综合页；紧张 vs 相位释放区分；受体亲和力梯度；核心区别：调制"如何处理"而非"处理什么"；连接8个既有节点
- `concepts/gain-control.md`（皮层增益控制）🟢 established / 置信度高 — 增益控制首个专页；响应增益（斜率变化）vs 对比度增益（阈值移动）；乘法性增益实现机制（M1→K⁺漏电；NE/α2A→HCN抑制）；除法归一化（PV+中间神经元）；信噪比改善；核心来源：Herrero 2008/2017、Edeline 2012

**修订页面（2）**：
- `systems/v1-primary-visual-cortex.md`（revision_count 1→2）：新增"神经调质对 V1 的调制"小节（ACh/肌碱受体介导注意调制，Herrero 2008，东莨菪碱P<0.001，美加明P=0.465，注意效应~20-50%响应增益）；related 新增 acetylcholine-cortex, gain-control；opens_questions 新增 Q-ach-ne-02；key_sources 新增 PMID:18633352；source_articles 新增 2026-06-12
- `concepts/working-memory.md`（revision_count 3→4）：新增"NE 和 ACh 对工作记忆的调制"小节（α2A→HCN抑制→WM表征稳定；α1→噪声→应激性认知崩溃；胍法辛ADHD临床；M1→持续放电；α7-nAChR→NMDA稳定性）；related 新增 norepinephrine-locus-coeruleus, acetylcholine-cortex；key_sources 新增 PMID:16254995, PMID:23818597；source_articles 新增 2026-06-12

**悬空引用新增（2）**：
- `basal-forebrain`（被 acetylcholine-cortex/norepinephrine-locus-coeruleus 引用）— 基底前脑解剖待专页
- `locus-coeruleus-anatomy`（被 norepinephrine-locus-coeruleus 引用）— LC详细解剖专页待建立

**悬空引用解决（0）**：今日无旧悬空引用被填补。

**矛盾登记（0）**：今日无新矛盾。两个现有开放矛盾（C-2026-05-24-01, C-2026-05-25-01）今日文献未直接涉及，状态不变。

**图谱更新**：
- 新节点：acetylcholine-cortex, norepinephrine-locus-coeruleus, neuromodulator-systems, gain-control（50→54 总节点）
- 新边：22条（含 acetylcholine-cortex→v1-primary-visual-cortex(regulates)、acetylcholine-cortex→working-memory(regulates)、norepinephrine-locus-coeruleus→working-memory(regulates)、norepinephrine-locus-coeruleus→ltp(regulates)、gain-control→v1-primary-visual-cortex(mechanism-of)、neuromodulator-systems→acetylcholine-cortex(contains)等；256→278 总边数）
- 新增悬空引用：basal-forebrain, locus-coeruleus-anatomy

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

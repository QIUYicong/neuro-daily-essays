# Wiki 变更日志

> 每日固结步骤产生的 wiki 变更记录。新条目置于顶部。

---

## 2026-08-30 · 文章 #128 · 视觉的另一半：背侧流如何把世界变成动作

**核心主题**：背侧视觉流（V1→MT/V5→PPC→前运动皮层）的行动视觉计算——Goodale-Milner 感知vs行动双流框架、MT/V5 方向选择性与 pattern motion 整合、后顶叶皮层（LIP/AIP/VIP/MIP）的意图地图、LIP 非运动指令区的新证据（Brunamonti 2023）、Rizzolatti 背背侧/腹背侧双路细分。图谱从 255 节点/1494 边增至 258 节点/1507 边（+13 条有向边）。

### 新建 Wiki 页面（3 个）

- `systems/posterior-parietal-cortex.md`（后顶叶皮层/PPC）🟢 established · 高置信度 — LIP 空间显著性图谱（非眼动指令区）；AIP 抓握手型预编码；VIP 近身空间防御；MIP 到达计算；背背侧/腹背侧双路输出；关键证据表 5 条；Q-ppc-01/Q-ppc-02 两个开放问题
- `concepts/dorsal-visual-stream.md`（背侧视觉流）🟢 established · 高置信度 — 行动视觉（vision-for-action）vs 感知视觉；自我中心坐标核心；D.F.案例双离解；Rizzolatti双路细分；Ritchie 2024 branching heterarchy 框架更新；key_sources 4 篇
- `neurons/mt-v5-motion-area.md`（MT/V5 运动区）🟢 established · 高置信度 — 方向选择性；pattern motion 整合；双目视差细胞；MT 损毁→运动感知阈值升高（Newsome 1988）；运动盲（akinetopsia）；key_sources 2 篇

### 修订 Wiki 页面（1 个）

- `concepts/ventral-visual-stream.md` rev2→rev3 — related 新增 dorsal-visual-stream（完成双流完整图谱连接）；source_articles 追加 2026-08-30；修订历史追加

### 图谱与导航

- _graph.json：255→258 节点（+3），1494→1507 边（+13），悬空引用减少（dorsal-visual-stream、posterior-parietal-cortex 已建页面）
- index.md：主题页数更新，新增 systems/posterior-parietal-cortex、concepts/dorsal-visual-stream、neurons/mt-v5-motion-area 条目

### 矛盾登记

- 无新矛盾（LIP 的"注意图谱 vs 运动指令"分歧已在 PPC 页面并列呈现，待后续证据裁决；未降置信度，记入 Q-ppc-01）

---

## 2026-08-29 · 文章 #127 · 腹侧视觉流的"解缠"之旅：大脑如何在 150 毫秒内把像素变成物体身份

**核心主题**：腹侧视觉流（V1→V2→V4→TEO→IT）的层级物体识别计算——解缠假说（DiCarlo & Cox 2007）、无监督时间连续性学习（Li & DiCarlo 2008/2010）、性能优化 CNN 预测 IT 响应（Yamins et al. 2014）、IT 皮层物体空间地图（Bao et al. 2020）。今日填补知识库中 `inferior-temporal-cortex` 和 `object-recognition` 两个长期悬空引用。图谱从 253 节点/1479 边增至 255 节点/1494 边（+15 条有向边）。

### 新建 Wiki 页面（2 个）

- `neurons/inferior-temporal-cortex.md`（颞下皮层/IT皮层）🟢 established · 高置信度 — 物体身份的不变性种群表征；IT 种群线性可分性（Hung 2005, ~90%准确率）；无监督时间连续性学习（Li 2008/2010）；物体空间低维坐标地图（Bao 2020）；IT→内嗅→海马"what"通路；TE 比 TEO 类别学习信号更强（Shimizu 2024）；关键证据表 6 条；Q-it-01/Q-it-02 两个开放问题；key_sources 9 篇
- `concepts/object-recognition.md`（视觉物体识别）🟢 established · 高置信度 — 不变性-选择性悖论；解缠假说核心计算目标；核心物体识别系统（150ms前馈）；种群几何线性可分性（vs 祖母细胞假说）；时间连续性学习机制；目标驱动框架（r=0.78）；关键证据表 4 条；Q-vvs-01/Q-vvs-02/Q-it-01 指向的开放问题；key_sources 5 篇

### 修订 Wiki 页面（3 个）

- `concepts/ventral-visual-stream.md` rev1→rev2 — 此前悬空的 inferior-temporal-cortex 和 object-recognition related 链接已解决（新页面创建）；新增 key_sources 5 篇（Li & DiCarlo 2010, Yamins & DiCarlo 2016, Bao 2020 等）；related 新增 entorhinal-cortex, hippocampal-circuit, biased-competition；source_articles 更新
- `systems/v1-primary-visual-cortex.md` rev5→rev6 — ventral-visual-stream 的完整 wiki 页面已创建，V1 在腹侧流层级中的定位（第一站）得到进一步明确；source_articles 追加 2026-08-29
- `concepts/cnn-visual-cortex-analogy.md` rev1→rev2 — 此前悬空的 ventral-visual-stream related 链接解决（wiki页面已有）；新增 inferior-temporal-cortex 和 object-recognition 的连接；source_articles 追加 2026-08-29

### 图谱与导航

- _graph.json：253→255 节点（+2），1479→1494 边（+15），悬空引用 31→29（移除 inferior-temporal-cortex、object-recognition）
- index.md：主题页数 249→252，新增 neurons/inferior-temporal-cortex 和 concepts/object-recognition 条目；修订 ventral-visual-stream 条目状态

### 矛盾登记

- 无新矛盾登记（今日文章处理的是层级架构证据，各核心主张来自独立实验室重复验证，无明显冲突）

### 残余悬空引用（需未来填补）

- `inferior-temporal-cortex` ✅ 已填补
- `object-recognition` ✅ 已填补
- `medium-spiny-neuron`（被 basal-ganglia, actor-critic-brain, striatal-beat-frequency 引用）
- `neural-population-coding`（被 population-clock 引用）
- `recurrent-network`（被 population-clock, attractor-network 引用）
- `binding-problem`（被 binding-by-synchrony, gamma-oscillations 引用）

---

## 2026-08-28 · 文章 #126 · 稀疏奇迹：齿状回如何以 5% 的激活率撑起大脑的记忆分辨

**核心主题**：齿状回（DG）的稀疏编码机制与模式分离的细胞/回路实现。三大机制板块：(1) 颗粒细胞内在"沉默偏好"（静息膜电位约 −85 mV、高动作电位阈值、高密度 Kir2.x 通道），加之 5–10 倍解剖学扩张（EC→DG），使 DG 在高维空间中正交化相似输入；(2) 多层 GABA 能中间神经元（篮状细胞前馈/反馈快速抑制、HIPP 细胞树突层"分母滤波"、MOPP 细胞侧向抑制竞争）主动雕刻激活稀疏性；(3) 苔藓细胞悖论：门区大型兴奋性苔藓细胞通过净激励篮状细胞对颗粒细胞产生净抑制效果（Jinde 2012, PMID:23259953），苔藓细胞缺失导致颗粒细胞过兴奋和模式分离失败。维度框架（Cayco-Gajic & Silver 2019, PMID:30790539）：模式分离的关键是表征空间的有效维度，而非单纯稀疏性。GoodSmith 2017（PMID:28132828）纠正了历史错误——颗粒细胞（单场低频）与苔藓细胞（多场高频）的体内放电特性截然不同，文献中长期存在的误识别导致颗粒细胞活动被高估。Vargish 2025（PMID:40672329，预印本）报告 VGluT3+ 中间神经元专门靶向苔藓细胞的"元抑制"回路，进化保守至灵长类。

### 新建 Wiki 页面（2 个）

- `systems/dentate-gyrus.md`（齿状回）🟢 established · 高置信度 — EC→DG 5–10倍扩张解剖基础；颗粒细胞内在静息偏好（Kir2.x）；多层 GABA 能抑制网络；苔藓细胞双轨策略；维度视角；关键证据表 5 条；Q-dg-sparse-01/Q-dg-mc-net-effect/Q-dg-human-imaging 三个开放问题；key_sources 7 篇
- `neurons/mossy-cells-dentate.md`（苔藓细胞，齿状回）🔵 mainstream · 中置信度 — 回路解剖（兴奋性输入+双输出通路）；苔藓细胞悖论（净效果为抑制）；Jinde 2012 决定性消融实验；沉默篮状细胞假说（Jinde 2013）；Galloni 2022 计算模型；GoodSmith 2017 放电特性对比；Vargish 2025 VGluT3+ 元抑制（预印本）；关键证据表 5 条；Q-dg-mc-net-effect/Q-mc-state-dependent/Q-mc-vglut3-circuit 三个开放问题；key_sources 5 篇

### 修订 Wiki 页面（1 个）

- `concepts/pattern-separation.md`：rev2→rev3，当前理解节新增苔藓细胞悖论内容（Jinde 2012/2013，Galloni 2022）和维度框架（Cayco-Gajic & Silver 2019）；关键证据表新增 4 行（Diamantaki 2016、GoodSmith 2017、Jinde 2012、Cayco-Gajic 2019）；连接节新增 dentate-gyrus/mossy-cells-dentate/fear-generalization；related/key_sources/source_articles 字段对应更新

### 图谱更新

- 节点：251 → 253（+2）
- 边：1465 → 1479（+14）
- 新节点：dentate-gyrus（systems/region/established/high）、mossy-cells-dentate（neurons/structure/mainstream/medium）
- 主要新边：dentate-gyrus ↔ hippocampal-circuit/pattern-separation/pattern-completion/entorhinal-cortex/adult-neurogenesis/fear-generalization/mossy-cells-dentate；mossy-cells-dentate ↔ dentate-gyrus/pattern-separation/pv-interneurons/fear-generalization/hippocampal-circuit/adult-neurogenesis

### 新增开放问题（5 个）

- Q-dg-sparse-01（中优先级）：颗粒细胞激活率在不同任务难度和行为状态（探索/奔跑/睡眠）下如何动态变化？2–5% 是固定值吗？
- Q-dg-mc-net-effect（高优先级）：苔藓细胞对颗粒细胞的净效果（抑制 vs 兴奋）是否在不同神经调质状态（ACh/NE/DA）下动态反转？
- Q-dg-human-imaging（中优先级）：7T fMRI 能否可靠区分人类 DG 和 CA3 的激活（两者极薄且紧邻）？
- Q-mc-state-dependent（中优先级）：不同行为状态（探索/静止/NREM/REM）下苔藓细胞放电模式如何变化？
- Q-mc-vglut3-circuit（中优先级）：Vargish 2025 预印本 VGluT3+ 元抑制回路能否在独立实验室和人类组织中复现？其认知功能意义是什么？

### 无矛盾登记

- 苔藓细胞净效果为抑制的证据强度为中-高（啮齿类消融实验），但状态依赖性尚不清楚（Q-dg-mc-net-effect），记录于 mossy-cells-dentate 页面置信度：中 字段
- Vargish 2025 为预印本，记录于 mossy-cells-dentate 证据表置信度：新兴（待验证）

---

## 2026-08-26 · 文章 #124 · PTSD 中的记忆囚笼：当杏仁核、海马与 vmPFC 的三角联盟失守

**核心主题**：PTSD 的神经生物学。三节点三角失调模型：(1) 杏仁核（BLA/CeA）过度激活——创伤后 NE+GC 协同增强 BLA-LTP，杏仁核持续过度响应，与症状严重程度正相关（Shin 2006, PMID:16891563）；(2) vmPFC 沉默——消退刹车失效，消退记忆本身存储于 IL/vmPFC，无法提取"此处安全"（Milad 2009 fMRI 直接证据, PMID:19748076）；(3) 海马萎缩+情景化失败——苔藓细胞（mossy cells）受损→颗粒细胞去抑制→情景集合重叠→模式分离失败→恐惧泛化（Jeong 2024，Xu 2025 综述）。新兴发现：外侧背侧缝核（LDRn）5-HT 神经元在急性应激后从共释放谷氨酸切换为共释放 GABA，同一改变在 PTSD 死后人脑中观察到（Li et al. 2024）。治疗靶点：消退稳定化（PE/暴露+DCS/睡眠巩固）vs 再巩固编辑（普萘洛尔/再巩固窗口消退/MDMA）。Yi 2026（PMID:41663712）提出多靶点整合框架。

### 新建 Wiki 页面（2 个）

- `diseases/ptsd.md`（创伤后应激障碍）🟢 established · 高置信度 — 三角失调模型完整机制（5个机制板块）；10条证据记录；Q-ptsd-01~04四个开放问题；key_sources 10 篇
- `concepts/fear-generalization.md`（恐惧泛化）🟡 emerging · 中高置信度 — 苔藓细胞→颗粒细胞去抑制→情景集合重叠机制图；5-HT 递质切换独立驱动；ACC 整合角色；Q-fear-gen-01~02 两个开放问题

### 修订 Wiki 页面（4 个）

- `concepts/fear-extinction.md`：rev6→rev7，新增 Milad 2009 PTSD fMRI 直接证据（vmPFC+海马↓，dACC↑）；Yi 2026 整合多靶点框架（消退稳定化+再巩固编辑+睡眠）；添加 ptsd/fear-generalization 到 related；添加 PMID:19748076/41663712 到 key_sources
- `systems/amygdala.md`：rev7→rev8，连接节新增 ptsd（BLA/CeA过度激活与症状正相关；CRH₁R过激活候选机制）、fear-generalization（BLA是泛化恐惧的共同输出节点；苔藓细胞受损导致情景输入失去精确性）；related/key_sources/source_articles相应更新
- `concepts/memory-reconsolidation.md`：rev1→rev2，连接节新增 ptsd（再巩固干预是 PTSD 新靶点；Yi 2026 整合框架；Xu 2025 时空动态）；related/key_sources/source_articles相应更新
- `systems/vmPFC.md`：rev1→rev2，连接节新增 ptsd（Milad 2009 fMRI 直接证据：PTSD消退回忆时vmPFC激活↓；Yi 2026 整合多靶点治疗框架）；related/key_sources/source_articles相应更新

### 图谱更新

- 节点：247 → 249（+2）
- 边：1425 → 1444（+19）
- 新节点：ptsd / fear-generalization
- 主要新边：ptsd ↔ amygdala/vmPFC/fear-extinction/fear-conditioning/hippocampal-circuit/fear-generalization/memory-reconsolidation/norepinephrine-locus-coeruleus/glucocorticoid-stress-memory/adult-neurogenesis/engram-cells；fear-generalization ↔ amygdala/hippocampal-circuit/pattern-separation/fear-conditioning/fear-extinction/ptsd/norepinephrine-locus-coeruleus/adult-neurogenesis

### 新增开放问题（6 个）

- Q-ptsd-01（高）：海马体积缩小是 PTSD 的原因（易感性）还是结果（应激损伤）？双胞胎研究提示两者都有，相对权重不清楚
- Q-ptsd-02（高）：相同创伤暴露，只有约 25% 发展 PTSD——遗传（FKBP5/BDNF/SLC6A4）、童年创伤、社会支持、急性期应激反应各自的预测力和交互效应
- Q-ptsd-03（高）：如何在临床上可靠地打开再巩固窗口？久远 PTSD 创伤记忆（数十年）能否被干预？普萘洛尔 Phase 2a 给药时机问题如何改进设计？
- Q-ptsd-04（中）：PTSD 亚型（恐惧/高唤醒型 vs 解离/情感麻木型）是否有不同回路基础，需要相反方向的干预？
- Q-fear-gen-01（高）：苔藓细胞受损是恐惧泛化的必要机制还是多条并行通路之一？LC-NE 对苔藓细胞的抑制是直接还是间接的？人类如何验证？
- Q-fear-gen-02（中）：恐惧泛化是否存在可量化的活体生物标志物（如高分辨率 fMRI DG 集合重叠度）？5-HT 递质切换是否可逆？

### 无矛盾登记（苔藓细胞机制为新兴证据，记录于各页置信度字段和 key_sources 的证据强度标注）

---

## 2026-08-25 · 文章 #123 · 驯化杏仁核：vmPFC 与 sgACC 如何编织情绪控制的神经语言，以及抑郁症如何让这根丝线断裂

**核心主题**：vmPFC（BA10/11/12/25/32 腹侧）与 sgACC（BA25）如何作为前额叶-杏仁核情绪调节回路的枢纽。三个机制板块：(1) 认知重评——vlPFC 语义重构 → vmPFC 情绪整合 → 杏仁核负向有效连接（Steward 2021 DCM + He 2023 TMS-fMRI 因果证明）；(2) 恐惧消退——IL/vmPFC → 腹侧 ITC → CeM 抑制（Giustino & Maren 2015 系统综述 + Sierra-Mercado 2011 因果证据）；(3) sgACC 作为"内脏运动皮层"（Price & Drevets 2010）——正常情况下精准调节自主神经和神经调质基线，抑郁时持续过度激活形成自我维持的负性情绪循环（Drevets 1999 PET + Mayberg 2005 BA25 DBS）。

### 新建 Wiki 页面（3 个）

- `systems/vmPFC.md`（腹内侧前额叶皮层）🟢 established · 高置信度 — 四大功能回路（认知重评/恐惧消退/sgACC轴/抑郁崩溃）；9 条证据记录；Q-vmPFC-01/02/03 三个开放问题
- `concepts/emotion-regulation.md`（情绪调节）🟢 established · 高置信度 — 五类策略（认知重评/注意部署/情绪压制/习惯化消退/内感觉重估）；vmPFC 枢纽回路图；主动推断精度权重视角
- `concepts/cognitive-reappraisal.md`（认知重评）🟢 established · 高置信度 — 三层级回路（vlPFC语义重构→vmPFC整合→杏仁核抑制）；重评 vs 压制代价对比；Buhle 2014 元分析 + He 2023 TMS-fMRI 证据

### 修订 Wiki 页面（4 个）

- `concepts/fear-extinction.md`：rev5→rev6，新增 Giustino & Maren 2015 系统综述（BLA→IL/PL分区投射）+ Sierra-Mercado 2011 双侧因果实验；添加 vmPFC/emotion-regulation 到 related；添加 Q-vmPFC-03 到 opens_questions
- `systems/amygdala.md`：rev6→rev7，新增 vmPFC→杏仁核负向通路（认知重评 + 恐惧消退双视角）；添加 vmPFC/emotion-regulation/cognitive-reappraisal 到 related；添加 Q-vmPFC-03
- `systems/anterior-cingulate-cortex.md`：rev4→rev5，新增 sgACC（BA25）作为"内脏运动皮层"的完整机制（DBS治疗TRD + Drevets 1999 + Price & Drevets 2010）；添加 vmPFC/emotion-regulation/hpa-axis 到 related；添加 Q-vmPFC-02
- `systems/prefrontal-cortex.md`：rev6→rev7，新增 vmPFC 作为 PFC 情绪调节腹侧亚区（认知重评三层级 + IL消退 + sgACC轴 + 抑郁回路崩溃）；添加 vmPFC/emotion-regulation/cognitive-reappraisal/amygdala/fear-extinction 到 related；添加 Q-vmPFC-01；添加 dimensions: disease

### 图谱更新

- 节点：244 → 247（+3）
- 边：1402 → 1425（+23）
- 新节点：vmPFC / emotion-regulation / cognitive-reappraisal
- 主要新边：vmPFC ↔ amygdala/anterior-cingulate-cortex/prefrontal-cortex/fear-extinction/emotion-regulation/cognitive-reappraisal/orbitofrontal-cortex/nucleus-accumbens/hpa-axis；emotion-regulation ↔ vmPFC/amygdala/cognitive-reappraisal/fear-extinction/insular-cortex/interoception/active-inference；cognitive-reappraisal ↔ vmPFC/amygdala/prefrontal-cortex/working-memory/fear-extinction

### 新增开放问题（3 个）

- Q-vmPFC-01（高）：vmPFC 在认知重评元分析中未呈现稳定激活的原因——策略依赖/时间分辨率/个体差异稀释？
- Q-vmPFC-02（高）：sgACC 过度激活在抑郁中是起因还是结果？DBS 如何中断恶性循环？
- Q-vmPFC-03（高）：PTSD 中 vmPFC 消退记忆提取障碍的精确机制——编码失败还是提取阻断？

### 无矛盾登记（vmPFC 在元分析中的不稳定激活被标记为 Q-vmPFC-01，非实证矛盾）

---

## 2026-08-24 · 文章 #122 · 背外侧前额叶的认知弹性：规则维护、任务切换与工作记忆门控机制

**核心主题**：dlPFC（BA9/46）认知弹性三重机制——(1) 混合选择性（mixed selectivity，Rigotti 2013）：非线性多变量响应使神经表征高维化，支持任意规则组合的线性可读出；(2) 群体动力学（Mante 2013）：不同任务背景下群体活动轨迹沿正交子空间展开，选择与整合是同一动力学过程两个面；(3) 振荡选通（Buschman 2012）：beta 同步激活当前规则集群，alpha 同步抑制无关集群。BG-PFC 门控（O'Reilly & Frank 2006）解释稳定性—弹性权衡的回路机制，与 dACC（#121）直接串联。额叶层级（Badre 2009）描述前后轴抽象度递增的认知控制组织。OCD（Liu 2023）和 Sali 2024 的强化学习视角作为疾病与现代机制补充。

### 新建 Wiki 页面（4 个）

- `systems/dlpfc-cognitive-flexibility.md`（背外侧前额叶认知弹性）🔵 mainstream · 高置信度 — 三重机制：混合选择性/群体动力学/振荡选通；BG 门控；前额叶层级（Badre 2009）；OCD/精神分裂症疾病联系；Q-dlpfc-01~04
- `concepts/mixed-selectivity.md`（混合选择性）🔵 mainstream · 高置信度 — 非线性多变量响应；高维表征扩充任务组合；Rigotti 2013 理论+实验双重验证；与群体动力学关系
- `concepts/stability-flexibility-tradeoff.md`（认知稳定性—弹性权衡）🔵 mainstream · 高置信度 — 计算约束本质；BG-PFC-dACC 网络解决方案；OCD/ADHD/精神分裂症/PD 的四种失调模式
- `concepts/task-switching-cost.md`（任务切换代价）🟢 established · 高置信度 — 混合代价/残余切换代价两成分；额顶网络与切换预测误差（Sali 2024）；振荡动态底物（Buschman 2012）

### 修订 Wiki 页面（1 个）

- `systems/prefrontal-cortex.md`：rev5→rev6，新增 dlPFC 认知弹性机制（混合选择性/群体动力学/振荡选通/BG门控/额叶层级）；添加 dlpfc-cognitive-flexibility/mixed-selectivity/stability-flexibility-tradeoff/task-switching-cost 到 related；新增 Q-dlpfc-01~04；新增 key_sources 8项（Mante/Buschman/Rigotti/Badre/Sali等）

### 图谱更新

- 节点：240 → 244（+4）
- 边：1384 → 1402（+18）
- 新节点：dlpfc-cognitive-flexibility / mixed-selectivity / stability-flexibility-tradeoff / task-switching-cost
- 主要新边：dlpfc-cognitive-flexibility ↔ prefrontal-cortex/working-memory/basal-ganglia/dacc-conflict-monitoring/beta-oscillations/alpha-oscillations/mixed-selectivity/task-switching-cost

### 新增开放问题（4 个）

- Q-dlpfc-01（高）：持续激活 vs. 活动-沉默工作记忆的精确分工
- Q-dlpfc-02（高）：dACC→BG→dlPFC 规则更新信号链的时间分辨率
- Q-dlpfc-03（中）：人类 dlPFC 混合选择性是否超越猕猴
- Q-dlpfc-04（中）：旧规则的主动抑制 vs. 竞争压制机制

### 无矛盾登记

---

## 2026-08-23 · 文章 #121 · 背侧前扣带皮层的三重计算：错误监测、冲突信号与努力代价的统一语言

**核心主题**：dACC/MCC 的认知控制功能三角——(1) 错误监测：ERN（误差相关负波）作为多巴胺负向 RPE 在 ACC 的表达（Holroyd & Coles 2002）；(2) 冲突监控：Botvinick 假说、Hopfield 能量量化、Gratton 效应、van Veen 2001 fMRI 验证；(3) 努力-代价决策：Walton/Kennerley 2006 大鼠 T 型迷宫损伤实验 + Croxson & Rushworth 2009 人类 fMRI；整合：Cavanagh & Frank 2014 的 FMθ 振荡统一机制 + Shenhav 2013 EVC 规范理论。

### 新建 Wiki 页面（4 个）

- `concepts/error-related-negativity.md`（误差相关负波 ERN）🟢 established · 高置信度 — 错误后~80ms、dACC/MCC 生成器（iEEG 证实）；Holroyd & Coles RL 框架（多巴胺 RPE → ERN）；与 FMθ 的相位重置关系；Pe 成分（有意识觉察）
- `concepts/conflict-monitoring.md`（冲突监控假说）🔵 mainstream · 高置信度 — Botvinick 2001 框架；Hopfield 能量形式化；Gratton 效应行为预测；van Veen fMRI 响应冲突特异激活；与 EVC 的继承关系
- `concepts/expected-value-of-control.md`（EVC 理论）🔵 mainstream · 中置信度 — Shenhav 2013 规范框架；EVC = Σ收益−成本；统一三类信号（错误/冲突/努力）；dACC 监控+规范双功能 vs dlPFC 执行；EVC 额外预测奖励效果（冲突监控无法预测）
- `concepts/frontal-midline-theta.md`（FMθ 前额叶中线θ振荡）🔵 mainstream · 高置信度 — 4–8Hz；来源 dACC/MCC+preSMA；ERN/N2/FRN 共享θ谱；11项跨区同步复制；θ相位锁定机制；FMθ→STN 同步=冲突驱动反应抑制；θ功率预测 Gratton 效应

### 修订 Wiki 页面（1 个）

- `systems/anterior-cingulate-cortex.md`：rev3→rev4，**重大修订**，新增完整的 dACC/MCC 认知控制功能板块（错误监测/冲突监控/努力决策/FMθ/EVC五节），更新解剖分区表含现代 MCC 术语，新增 related 8 项（error-related-negativity/conflict-monitoring/expected-value-of-control/frontal-midline-theta/response-inhibition/hyperdirect-pathway/working-memory/nucleus-accumbens），opens_questions 增加 4 项，key_sources 增加 5 项

### 修复悬空引用（1 个）

- `orbitofrontal-cortex`（已有 wiki 页 systems/orbitofrontal-cortex.md）→ 新增图谱节点，悬空引用完全消除

### 无矛盾登记（EVC vs 冲突监控假说为知识库演化中的理论包含关系，非实证矛盾）

### 新增开放问题（4 个）

- Q-dacc-01（高）：dACC 与 MCC 的精确解剖边界及功能分工——是否真正是一个功能区域？
- Q-dacc-02（中）：EVC 中努力成本的具体神经实现（热力学/机会成本/主观厌恶感？）
- Q-dacc-03（中）：dACC 内部突触学习规则是否存在、形式为何？
- Q-dacc-04（低-中）：FMθ 与局部 γ 振荡的协作机制（θ-γ 耦合在 dACC 中是否存在？）

### 图谱更新

- 新增节点 5 个（error-related-negativity、conflict-monitoring、expected-value-of-control、frontal-midline-theta、orbitofrontal-cortex）
- 新增边 13 条（见 _graph.json，总计 240 节点 / 1384 边）
- 悬空引用从 1 个降至 0 个

---

## 2026-08-22 · 文章 #120 · 岛叶皮层：身体的感知地图如何生成主观感受并导航决策

**核心主题**：岛叶皮层（Insular Cortex）与内感觉（Interoception）——后→中→前的梯度层级处理轴，从初级内感觉皮层（后岛接收 VMpo 传入）到主观感受生成（前岛整合 VENs 快速同步），再到显著性网络与 PFC 决策回路的身体状态嵌入；EPIC 预测编码模型（Barrett & Simmons 2015）与 Craig 经典映射框架的比较；躯体标记与 Damasio 决策理论的神经基底；精神疾病中的岛叶系统性异常。

### 新建 Wiki 页面（2 个）

- `systems/insular-cortex.md`（岛叶皮层）🟢 established · 高置信度 — 四区功能分化（后颗粒岛体感拓扑/中岛预测误差/前岛主观感受/前岛极沉默性顶端控制）；VENs 解剖（4.6× 体积，Layer V 特异）与 alexithymia 关联；EPIC 预测编码梯度；IMAC 三层计算分工；显著性网络（岛叶-ACC）；9 条连接（ACC/OFC/amygdala/PFC/NAc/thalamus 等）；8 篇来源（6 篇开放全文）
- `concepts/interoception.md`（内感觉）🟢 established · 高置信度 — 专属解剖通路（lamina I → VMpo → 后岛，区别于 VPM→S1 体感路径）；后→前梯度处理；内感觉精确度个体差异（AIC 激活预测 BDT 准确性）；主动推断维度；4 篇核心来源

### 修订 Wiki 页面（2 个）

- `systems/anterior-cingulate-cortex.md`：rev2→rev3，更新 related 字段（insula→insular-cortex，新增 interoception）；连接节新增岛叶-ACC 显著性网络说明（ACC 认知控制 + 岛叶内脏状态信号的协作关系）；source_articles 新增 #120
- `systems/orbitofrontal-cortex.md`：rev1→rev2，更新 related 字段（新增 insular-cortex、interoception）；连接节新增躯体标记向 OFC 提供身体状态输入说明；修订历史新增一行

### 无矛盾登记（Craig vs Barrett 的预测编码框架争议为文献中已记载的持续理论争论，不构成本知识库新发现的矛盾）

### 新增开放问题（4 个）

- Q-ins-01（高）：Craig 映射框架 vs. Barrett 预测框架——内感觉信号时序先后可否用 ECoG 解码验证？
- Q-ins-02（高）：前岛极电刺激沉默机制——网络状态依赖性还是频率不匹配？
- Q-ins-03（中）：VENs 因果功能——灵长类选择性光遗传操控是否可行？
- Q-ins-04（中）：不同决策类型（风险/道德/社会）的岛叶子区域分工是否统一？

### 图谱更新

- 新增节点：`insular-cortex`（systems）、`interoception`（concepts）
- 新增边（9条）：insular-cortex → interoception/anterior-cingulate-cortex/orbitofrontal-cortex/amygdala/prefrontal-cortex/nucleus-accumbens/thalamus；interoception → active-inference/precision-weighting
- **当前图谱状态**：235 节点，1371 边（+2 节点，+9 边）

---

## 2026-08-21 · 文章 #119 · 价值的解剖：眶额皮层如何为选项定价

### 新建 Wiki 页面（2 个）
- `systems/orbitofrontal-cortex.md`：眶额皮层系统级综合页面（region，established），覆盖三类功能神经元（offer value/chosen value/taste cells）、内侧vs外侧vs腹外侧亚区功能分工、BLA-OFC四条双向投射（lOFC→BLA写入/mOFC→BLA读取/BLA→lOFC更新权变/BLA→mOFC调适奖赏期望）、OFC→DMS行动转换（Gore 2023光遗传学因果）、lOFC→感觉皮层重映射（Banerjee 2020）、价值代码纵向稳定性（Zhang 2024）、状态编码新框架（Moneta 2024）；来源 PMID:16633341, 29144973, 37592039, 32884146, 40068869, DOI:10.7554/eLife.80926, 27112314, 39331504, 39547861
- `concepts/value-based-decision-making.md`：价值决策框架（concept，established），OFC三类神经元的决策流水线、BLA-OFC双向价值记忆学习循环、OFC→DMS行动转换、dlPFC→vmPFC自控调制（Hare 2009）、目标导向vs习惯行为双系统对比

### 修订 Wiki 页面（3 个）
- `systems/prefrontal-cortex.md`：rev4→rev5，新增 vmPFC/OFC 作为 PFC 价值决策腹侧亚区的说明（dlPFC→vmPFC自控调制，Hare et al. 2009 PMID:19407204）；related 新增 orbitofrontal-cortex、value-based-decision-making；key_sources 新增 PMID:19407204, 29144973；未解问题新增 Q-ofc-02；来源文章新增 #119
- `systems/amygdala.md`：rev5→rev6，连接节新增 orbitofrontal-cortex（BLA↔OFC 双向价值学习回路，Wassum 2022 & Jenni 2025）和 value-based-decision-making；related/key_sources/source_articles 相应更新

### 新增未解问题（3 个）
- Q-ofc-01（高优先级）：lOFC vs mOFC 的功能边界是解剖梯度还是离散边界？部分研究显示功能重叠
- Q-ofc-02（中优先级）：OFC 的 chosen value cells 是决策的生成者还是报告者（生成 vs 读出的因果方向性）？
- Q-ofc-03（中优先级）：社会价值（信任、利他）是否共用 OFC 同一套价值代码，还是有专化社会价值维度？

### 无矛盾登记（今日来源与既有 wiki 无直接冲突；OFC-BLA 回路为新增内容，无旧主张需比较）

---

## 2026-08-20 · 文章 #118 · 伏隔核的奖赏解剖

### 新建 Wiki 页面（3 个）
- `systems/nucleus-accumbens.md`：伏隔核系统级综合页面（region，established），覆盖NAc核心/壳解剖分区、D1/D2 MSN时程效应、享乐热点阿片-eCB耦合机制、多路输入整合表、社会奖赏OXT/MOR/KOR/eCB四系统、7行关键证据表、11条连接、3个未解问题（Q-nac-01/02/03）；来源 PMID:25950633, 31462765, 30069500, 39892577, 42038339
- `concepts/incentive-salience.md`：激励显著性框架（mechanism，established），Berridge-Robinson 1993激励敏化理论、wanting-liking解耦实验证据、成瘾的敏化模型、aberrant salience精神病理框架、anhedonia的wanting/liking区分
- `concepts/hedonic-hotspot.md`：享乐热点（mechanism，mainstream/medium），NAc壳区前内侧~1mm³区域、阿片-eCB功能耦合（eCB增强liking依赖内源性阿片激活，Mitchell 2018）、affective keyboard情境重调

### 修订 Wiki 页面（2 个）
- `concepts/endocannabinoid-system.md`：rev1→rev2，新增连接 nucleus-accumbens（享乐热点AEA-CB1R→liking增强、社会奖赏eCB信号）和 hedonic-hotspot；endogenous-opioid-system 连接注释补充 NAc 热点 eCB-阿片功能耦合（Mitchell 2018）
- `concepts/oxytocin.md`：rev2→rev3，新增连接 nucleus-accumbens（OXT→NAc社会奖赏接口，与MOR/eCB耦合）；key_sources新增PMID:39892577；来源文章新增 #118

### 新增未解问题（3 个）
- Q-nac-01（高优先级）：NAc壳区"affective keyboard"应激重调的分子机制（GR/CRF候选）
- Q-nac-02（高优先级）：社会孤立如何影响NAc的催产素-阿片-eCB三系统整合
- Q-nac-03（中优先级）：MOR效应的Prairie田鼠雌性特异性能否推广至人类社交差异

### 新增悬空引用（0）
无新增悬空引用（所有新页面related指向的节点均已存在）

### 知识图谱更新
- 节点：230→233（+3：nucleus-accumbens, incentive-salience, hedonic-hotspot）
- 边：1337→1362（+25条：含新节点间连接和向现有节点的反向连接）

---

## 2026-08-19

### 新建 Wiki 页面（3 个）
- `concepts/response-inhibition.md`：反应抑制机制，综合超直接和间接通路，established，来源 PMID:32155442, 16510720, 28103476
- `concepts/stop-signal-task.md`：停止信号任务范式，independent horse-race model，SSRT计算，established
- `concepts/hyperdirect-pathway.md`：超直接通路（rIFG→STN），2.2ms单突触证据，established

### 修订 Wiki 页面（2 个）
- `circuits/basal-ganglia.md`：新增超直接通路与停止信号相关证据行（第3次修订）
- `systems/prefrontal-cortex.md`：新增 rIFG/preSMA 在反应抑制中的因果作用证据（第4次修订）

### 新增未解问题（3 个）
- Q-ri-01：全局 vs 选择性抑制的解剖基础
- Q-ri-02：β振荡在停止中的因果角色
- Q-ri-03：主动性 vs 反应性抑制的共享/分离回路

### 新增悬空引用
- `anterior-cingulate-cortex`（preSMA 近邻功能差异尚未独立成页）
- `subthalamic-nucleus`（STN 尚无独立页面，多次被引用）

---

## 2026-08-18 · 文章 #104 · 工作记忆的两种面孔：持续放电与活动无声机制之争

**核心主题**：工作记忆维持机制争论全景；Goldman-Rakic持续放电经典图景；Wang XJ吸引子网络+NMDA受体证据；Stokes 2015活动无声框架+STSP机制；Lundqvist 2016 Gamma/Beta爆发间歇编码；Panichello 2024 Neuropixels开-关状态大综合；Thrower 2023持续放电神经元信息优势；Lara/Wallis PFC执行控制视角；Paluch 2025人类MTL持续放电；Beukers 2021活动无声vs情节记忆挑战；AI Transformer对照。

**新建页面（1）**：
- `wiki/concepts/activity-silent-wm.md`（rev1，status: emerging，confidence: medium）— 活动无声WM定义；STSP钙动力学机制；冲激再激活范式；Panichello 2024开-关切换证据整合；三个未解问题（Q-wm-active-vs-silent、Q-wm-silent-vs-episodic、Q-wm-manipulation-mechanism）

**修订页面（2）**：
- `wiki/concepts/working-memory.md`（rev9→rev10）— 整合Panichello 2024（间歇开-关状态）、Thrower 2023（持续放电信息优势）、Wang XJ 2021（NMDA拮抗剂证据）、Paluch 2025（人类MTL）、Stokes 2015；关键证据表新增6行；opens_questions新增Q-wm-manipulation-mechanism和Q-wm-silent-vs-episodic；related新增activity-silent-wm、attractor-network；key_sources新增7条
- `wiki/concepts/persistent-activity.md`（rev1→rev2）— 新增NMDA拮抗剂证据、Panichello 2024开-关切换、Thrower 2023信息优势、Paluch 2025人类证据；关键证据表新增4行；related新增activity-silent-wm、attractor-network

**登记矛盾（0）**：持续放电 vs 活动无声之争被Panichello 2024部分调和（两者在同一任务中共存），不构成新的contested_claim；但Q-wm-silent-vs-episodic（活动无声WM vs情节记忆区分）作为open question登记于unresolved_questions.md。

**新增未解问题（2）**：
- Q-wm-manipulation-mechanism（中优先级）：信息主动操纵是否必须依赖持续放电吸引子激活？活动无声机制无法支持动态计算（Wang 2021理论主张，缺乏直接实验）
- Q-wm-silent-vs-episodic（中优先级）：活动无声WM与海马情节记忆快速激活是否能被区分？需海马失活对照实验（Beukers 2021挑战）

**知识图谱更新**：新增节点 `activity-silent-wm`；新增边6条（activity-silent-wm→working-memory, activity-silent-wm→short-term-synaptic-plasticity, activity-silent-wm→persistent-activity, activity-silent-wm→gamma-oscillations, working-memory→activity-silent-wm, working-memory→attractor-network）

---

## 2026-08-17 · 文章 #116 · 同一肽，不同故事：加压素如何用受体分布的地理差异重写社会命运

**核心主题**：AVP九肽结构（与OXT仅差2 aa）；三受体系统（V1aR/V1bR/V2R）；草原田鼠 vs. 山地田鼠VP-V1aR密度差异；Lim 2004单基因草甸田鼠实验（单基因过表达V1aR逆转物种配对策略）；AVPR1A RS3微卫星机制（~500bp单配制 vs. ~50bp乱交，Hammock 2006, PMID:17118932/PMC1764849）；Gobrogge 2009 AH-V1aR选择性攻击及配对后受体可塑性（PMID:19858480/PMC2776424）；Leroy 2018 CA2→LS→VMH攻击回路（PMID:30518859）；V1bR vs. OTR CA2双路径对比（记忆写入 vs. 攻击触发）；BNST/mAMY性二态加压素投射（de Vries 2008）；人类AVPR1A RS3 334bp与男性配对行为关联（Walum 2008，可重复性存疑）；鹿鼠反例（Turner 2010）。

**新建页面（1）**：
- `wiki/concepts/vasopressin.md`（rev1，status: established，confidence: high）— AVP九肽结构；三受体亚型完整机制表；腹侧苍白球V1aR配对联结（奖赏回路劫持假说）；AVPR1A微卫星遗传基础；AH-V1aR选择性攻击（双向因果证明）；CA2-V1bR→LS→VMH攻击回路；BNST/mAMY性二态性；人类遗传学；三个未解问题（Q-avp-01/02/03）

**修订页面（3）**：
- `wiki/concepts/ca2-hippocampus.md`（rev2→rev3）— 新增第4b节：CA2-V1bR→LS→VMH攻击回路（Leroy 2018，PMID:30518859）；OTR vs. V1bR功能对比；related增加vasopressin、aggression、lateral-septum；opens_questions增加Q-avp-01；key_sources新增PMID:30518859
- `wiki/concepts/oxytocin.md`（rev1→rev2）— 新增Q-avp-01（CA2 OTR/V1bR协调问题，与vasopressin页共享）；来源文章新增 #116
- `wiki/concepts/social-memory.md`（rev2→rev3）— 新增V1bR vs. OTR在CA2的双路径分工（Leroy 2018）；vasopressin连接内容扩充；Q-avp-01加入未解问题；来源文章新增 #116

**登记矛盾（0）**：今日无新矛盾。注意：鹿鼠研究（Turner 2010）挑战AVPR1A微卫星机制的普遍性，但不与vole类数据直接矛盾（属于物种特化 vs. 普遍机制之争），记为Q-avp-03相关背景而非contested_claims条目。

**新增未解问题（3）**：
- Q-avp-01（高优先级）：CA2 的 OTR（社会记忆）和 V1bR（攻击触发）如何在同一动物同一时刻协调？时序分离还是亚群分工？
- Q-avp-02（高优先级）：人类VP/纹状体V1aR密度能否用高特异性PET放射配体直接测量并与配对行为关联？（技术节点：缺乏高特异性人类V1aR-PET配体）
- Q-avp-03（中优先级）：加压素系统在AVPR1A罕见突变相关ASD中的精确受损机制是什么？

**悬空引用解决（1）**：
- `vasopressin` — 已建立 wiki/concepts/vasopressin.md（此前为 ca2-hippocampus.md、oxytocin.md、social-memory.md related字段中的悬空引用）

**新增悬空引用（2）**：
- `aggression` — 在ca2-hippocampus.md、vasopressin.md中引用，尚无独立wiki页面
- `lateral-septum` — 在ca2-hippocampus.md、vasopressin.md中引用，尚无独立wiki页面

**图谱**：225节点→226节点，1313边→1323边（+1节点：vasopressin；+10边）

---

## 2026-08-16 · 文章 #115 · 催产素回路：五条专化投射如何将同一神经肽解码为社会记忆、奖赏与联结

**核心主题**：催产素（OXT）九肽结构与OTR（GPCR/Gq/11）；PVN/SON的magnocellular vs parvocellular分化；PVN内前/后亚群功能分化（Chrisman 2026, PMID:41548026）；五条专化投射路径：①PVH→SuM→CA2（社会识别记忆，Thirtamara Rajamani 2024, PMID:38052983）、②PVN→NAc（社会奖赏/配对联结，Borland 2025, PMID:39892577）、③PVN→CeA（恐惧抑制，Knobloch 2012, PMID:22325206；Rickenbacher 2017 eLife, PMC5469614；Wahis 2021 NatNeurosci星形胶质细胞机制）、④SON→LS（哺乳期社会恐惧预防，Menon 2018, PMID:29551417）、⑤aPVN→BNST（应激依赖社交调制）；社会凸显假说（Shamay-Tsoory & Abu-Akel 2016, PMID:26321019）；Ferguson 2000（PMID:10888874）奠基性遗传证明。

**新建页面（2）**：
- `wiki/concepts/oxytocin.md`（rev1，status: established，confidence: high）— 九肽结构；OTR信号通路；PVN/SON来源与亚群；五条专化投射路径完整描述；社会凸显假说；关键证据表
- `wiki/concepts/supramammillary-nucleus.md`（rev1，status: emerging，confidence: medium）— SuM双重功能（θ起搏器 + 催产素中继站）；OTR⁺谷氨酸能SuM神经元→CA2；关键证据；新建Q-sum-01

**修订页面（2）**：
- `wiki/concepts/ca2-hippocampus.md`（rev1→rev2）— 新增PVH→SuM→CA2间接催产素通路（PMID:38052983）；related增加oxytocin和supramammillary-nucleus；opens_questions增加Q-oxt-01；key_sources新增PMID:38052983
- `wiki/concepts/social-memory.md`（rev1→rev2）— 新增Ferguson 2000奠基证据；新增oxytocin、supramammillary-nucleus连接；opens_questions增加Q-oxt-01

**登记矛盾（0）**：今日无新矛盾。注意：CA2接受的Avpr1b（直接加压素通路）和OTR（经SuM的催产素间接通路）双重输入的时序协调问题已记入Q-oxt-01，性质为"机制未知"而非"矛盾"。

**新增未解问题（3）**：
- Q-oxt-01（高优先级）：PVH→SuM→CA2催产素通路和PVN→CA2直接Avpr1b通路的时序协调机制
- Q-oxt-02（中优先级）：人类鼻腔给药催产素是否真的提高脑内催产素浓度（药代动力学争议）
- Q-sum-01（高优先级）：SuM的θ起搏功能和催产素中继功能是否由不同神经元亚群承担

**图谱**：223节点→225节点，1298边→1316边（+2节点：oxytocin、supramammillary-nucleus；+18边）

---

## 2026-08-15 · 文章 #114 · CNTNAP2：语言、社会与癫痫三角共病的分子桥梁

**核心主题**：CNTNAP2/CASPR2 双重身份（成熟轴突旁节区 Kv1 锚定 vs 发育期中间神经元迁移导引）；FOXP2→CNTNAP2 调控轴联结罕见 CAS 与常见 SLI/ASD（Vernes 2008, PMID:18987363）；CDFE综合征（Strauss 2006, PMID:16571880）；KO小鼠：PV+/CR+/NPY+ 减少+CUX1+迁移异常+三核心域行为缺陷+癫痫（Peñagarikano 2011, PMID:21962519, PMC3390029开放全文）；mPFC E/I突触输入双降低+振荡协调崩溃（Lazaro 2019, PMID:31141683）；PVN OXT减少+NAc关键节点+早期OXT给药救援（Peñagarikano 2015, Choe 2022）；mPFC PNN过度沉积+ChABC部分救援社交（Gandhi 2023, PMID:36998537, 开放全文）；常见变异大样本无稳健关联（Toma 2018, PMID:30586385, 开放全文）；CR+减少的性别差异（Sáfár 2026, PMID:42249747）。

**新建页面（2）**：
- `wiki/concepts/cntnap2.md`（rev1，status: established，confidence: high）— CASPR2蛋白双重功能（旁节区Kv1锚定/发育期中间神经元迁移）；FOXP2调控轴；三角共病机制（E/I失衡/OXT系统/PNN）；完整证据表
- `wiki/diseases/cntnap2-deficiency-cdfe.md`（rev1，status: established，confidence: high）— CDFE综合征临床表型；双等位功能缺失→五联征；小鼠模型对应；疾病谱连续性

**修订页面（2）**：
- `wiki/concepts/foxp2.md`（rev1→rev2）— 补充cntnap2连接说明（PV+中间神经元减少→CDFE/ASD三角共病）；CNTNAP2已建独立页；source_articles新增
- `wiki/circuits/pv-interneurons.md`（rev6→rev7）— 新增CNTNAP2缺失→PV+减少（Peñagarikano 2011）；mPFC E/I双降低+振荡协调崩溃（Lazaro 2019）；CR+特异减少（Sáfár 2026）；母体抗CASPR2抗体（Bagnall-Moreau 2026）；related新增cntnap2；key_sources新增2条

**登记矛盾（0）**：今日无新矛盾。CNTNAP2常见变异的风险效应争议（Alarcon 2008 vs Toma 2018）已在 cntnap2.md "关键证据"表中并列记录为"中等置信度"与"高置信度（否定）"，遵循知识库规范明确标注不同置信度，不需登记为 contested_claims（属于证据强度不同而非直接冲突）。

**新增未解问题（3）**：
- Q-cntnap2-01（高优先级）：CNTNAP2在人类胚胎皮层发育的精确时空单细胞分辨率图谱
- Q-cntnap2-02（中优先级）：CA2区CNTNAP2高富集是否导致特异性社会记忆编码缺陷
- Q-cntnap2-03（中优先级）：早期催产素给药最佳时间窗口及性别差异

**图谱**：221节点→223节点，1288边→1298边（+2节点：cntnap2、cntnap2-deficiency-cdfe；+10边）

---

## 2026-08-14 · 文章 #113 · CA2：海马遗忘的第三元件——拒绝 LTP、守护社会记忆、触发记忆回放的神经元集群

**核心主题**：CA2 海马亚区三功能枢纽——Hitti & Siegelbaum 2014（PMID:24572357, Nature）Amigo2-Cre+TeNT 选择性灭活 CA2 → 社会记忆完全丧失，空间/恐惧/物体识别正常（CA2 是社会记忆专用基底，不是一般记忆节点）；MacDonald & Tonegawa 2021（PMID:33431691, PNAS）光遗传沉默 CA2→CA1 → 48% 时间细胞降解（P=1.37×10⁻³¹），仅 15% 场所细胞受影响（χ²=19.89，P=8.19×10⁻⁶），工作记忆错误增加（F(1,20)=21.67，P=0.002）；Oliva 2016（PMID:27593179, Neuron）高密度探针记录：CA2 ramping cells 在 SWR 前 20-30ms 斜升激发 → 随后 CA3→CA1；光遗传激活 CA2 诱导人工 SWR；约 20% SWR 绕过 CA3 直接 CA2→CA1 传播；分子机制：RGS14 五通路压制标准 Hebbian LTP，但支持 Avpr1b/催产素门控的社会情境专用 mGluR-LTD（Samadi 2023 PMID:36971428）；Middleton & McHugh 2020 综述（PMID:31874067）CA2 解剖-分子-功能全谱及临床关联（TLE 弹性、双相障碍 pyramidal cell 减少）。

**新建页面（2）**：
- `wiki/concepts/ca2-hippocampus.md`（rev1，status: mainstream，confidence: high）— CA2 三功能枢纽全机制（社会记忆专用基底/时间序列必要输入/SWR触发者）；RGS14 五通路 LTP 抑制；mGluR-LTD；Avpr1b/催产素通路；CA2 连接结构；疾病关联；完整证据表
- `wiki/concepts/social-memory.md`（rev1，status: mainstream，confidence: high）— 社会记忆 CA2 专用底物的神经机制；Hitti 2014 遗传解剖；Avpr1b 特异性；mGluR-LTD 存储形式；与 LTP 的对比

**修订页面（3）**：
- `wiki/neurons/hippocampal-circuit.md`（rev11→rev12）— CA2 亚区节从单一时间编码扩展为三功能枢纽（社会记忆/时间序列/SWR触发）；连接新增[[ca2-hippocampus]]、[[sharp-wave-ripples]]；related/opens_questions/key_sources 更新
- `wiki/concepts/sharp-wave-ripples.md`（rev8→rev9）— SWR 生成节增加 CA2 主动触发路径（CA2+CA3 双路径模型）；Oliva 2016 光遗传因果证据；连接新增[[ca2-hippocampus]]；证据表新增1行
- `wiki/concepts/time-cells.md`（rev1→rev2）— CA2 区输入节补充精确统计；增补 CA2 三维功能说明；related新增ca2-hippocampus

**登记矛盾（0）**：今日无新矛盾。CA2 LTP 抗性（RGS14 机制）与 CA2 支持社会记忆可塑性（mGluR-LTD）的表面张力已在 ca2-hippocampus.md 中阐明为非矛盾的功能分工（不同机制，不同可塑性类型）。

**新增未解问题（3）**：
- Q-ca2-function（中优先）：CA2 社会记忆功能与时间记忆功能是否由不同神经元亚型承担？
- Q-ca2-pnn-plasticity-window（中优先）：CA2 PNN 青春期成熟是否关闭社会记忆关键期？与 ASD 的关系？
- Q-ca2-disease-mechanism（中优先）：双相障碍中 CA2 pyramidal cell 减少的具体回路后果

**图谱**：219节点→221节点，1280边→1288边（+2节点，+8边；ca2-hippocampus/social-memory 新增）

---

## 2026-08-13 · 文章 #112 · 皮层时间层级：内禀神经时间尺度（INT）与时间感受野（TRW）

**核心主题**：皮层时间层级——Murray et al. 2014（PMID:25383900）发现猕猴7皮层区域INT梯度（MT~50ms→ACC~350ms，rs=0.89）；Hasson et al. 2008/Lerner et al. 2011（PMID:18322098/21414912）建立TRW框架（A1:毫秒→DMN:数十秒）；Ding et al. 2016（PMID:26642090）ECoG证明大脑同时在4Hz/2Hz/1Hz追踪词/短语/句子；Caucheteux et al. 2023（PMID:36864133）证明预测编码层级与时间层级对应；Li & Wang 2022（PMID:35110401）三机制（突触兴奋梯度+E/I属性+精细平衡）的数学模型；Cusinato et al. 2023（PMID:37045604）颅内EEG揭示新皮层→内嗅→海马→杏仁核的延伸梯度；疾病窗口（TLE/AD/卒中INT失调）。

**新建页面（2）**：
- `wiki/concepts/intrinsic-neural-timescale.md` — 内禀神经时间尺度（INT），rev1；猕猴区域τ值、三机制、跨物种证据、与TRW关系、疾病标志物
- `wiki/concepts/temporal-receptive-window.md` — 时间感受野（TRW），rev1；叙事打乱实验、A1→DMN梯度、与预测编码连接、Blank&Fedorenko 2020争议

**修订页面（3）**：
- `wiki/concepts/temporal-coding-hierarchy.md`（rev1→rev2）— 新增皮层INT/TRW维度，status升为mainstream；related新增intrinsic-neural-timescale/temporal-receptive-window/language-network/predictive-coding
- `wiki/theories/predictive-coding.md`（rev8→rev9）— 证据表新增Caucheteux 2023（额顶叶预测长上下文/颞叶预测短上下文）；related新增INT/TRW页面
- `wiki/concepts/temporal-hierarchy.md`（未单独修订，但关联更新）— INT/TRW的连接已通过graph更新体现

**登记矛盾（0）**：今日无新矛盾。Blank & Fedorenko 2020（语言网络内TRW无梯度）与Lerner 2011（TRW梯度存在）之间的张力已在TRW页面"未解问题"中记录，未构成严格矛盾（两者测量的区域集合不同）。

**新增未解问题（3）**：Q-temp-hier-01（高：GluN2B/GluN2A比率梯度的单体水平因果证据）、Q-temp-hier-02（中：TMS操控INT→叙事理解）、Q-temp-hier-03（低：INT发育轨迹分子机制）

**新增悬空引用（2）**：
- `cortical-canonical-microcircuit`：INT机制的解剖实现（被intrinsic-neural-timescale隐含）
- `auditory-cortex`：TRW最短端的代表区域（被temporal-receptive-window引用，系统区已有auditory-cortex页面）

**图谱**：217节点→219节点，1262边→1280边（+2节点，+18边）

---

## 2026-08-12 · 文章 #111 · FOXP2与语言发育神经遗传学：从KE家族突变到皮层-纹状体回路的分子编程

**核心主题**：FOXP2是人类语言最著名的"单基因"入口——KE家族R553H突变导致严重的言语失用和语法障碍；蛋白质层面含forkhead域+锌指+亮氨酸拉链三功能模块，直接调控264+靶基因（CNTNAP2、VLDLR等）；Walker 2023（PMID:37137515）揭示R553H通过dynactin1过表达→dynein-dynactin马达破坏→TrkB/BDNF信号受损→MSN树突发育不全的分子链；Qi 2024（PMID:39868047）发现FOXP2+ L6皮层丘脑神经元是言语习得的不可或缺节点；人源化Foxp2小鼠（Schreiweis 2014）展示T303N+N325S替换加速陈述性→程序性学习转换；斑马雀Area X FoxP2在鸣唱时社会情境依赖性下调（PMC2683917）；CAS遗传异质性（Morgan 2024）：30+致病基因汇聚于转录调控共同通路。

**新建页面（3）**：
- `wiki/concepts/foxp2.md`（rev1，status: established，confidence: high）— 蛋白结构、表达谱、264靶基因网络、dynein机制、CT神经元回路、人源化小鼠、鸣禽模型；Q-foxp2-01/02/03
- `wiki/diseases/childhood-apraxia-of-speech.md`（rev1，status: established，confidence: high）— CAS定义/临床特征、遗传异质性（30+基因）、FOXP2-dynactin1机制链、收敛转录调控通路
- `wiki/concepts/vocal-learning.md`（rev1，status: established，confidence: high）— 斑马雀HVC→Area X→DLM→LMAN→RA回路、FoxP2社会情境依赖动态调控、FoxP2敲减→异常变异性、跨物种平行

**修订页面（2）**：
- `wiki/concepts/language-evolution.md`（rev1→rev2）— 新增"FOXP2分子层面的语言进化"小节（T303N+N325S替换、人源化小鼠功能后果、正向选择争议：Enard 2002→Krause 2007尼安德特人→Henn 2018统计伪迹）；Q-lang-06部分更新；related新增foxp2/vocal-learning；dimensions扩展至molecular/behavior
- `wiki/systems/basal-ganglia.md`（rev1→rev2）— 新增"FOXP2与纹状体发育"小节（striosome优先表达、MSN树突调控、人源化Foxp2效果DMS-DA -30%+DLS LTD增强、CAS纹状体病理、鸣禽Area X平行）；related新增foxp2/vocal-learning/childhood-apraxia-of-speech；dimensions扩展至disease

**矛盾检查**：无新矛盾。Q-lang-06部分解决：FOXP2影响纹状体（已有直接证据），但FOXP2→BA44前部扩张的直接因果链仍缺乏证据（保持开放）。

**图谱更新**：214节点/1246边 → 217节点/1262边（+3节点，+16边）

**新增未解问题**：
- Q-foxp2-01（高优先级）：成体鸣禽Area X中FoxP2下调的上游触发机制（多巴胺/BDNF/钙信号？）
- Q-foxp2-02（高优先级）：FOXP2+ L6皮层丘脑神经元在言语产生时的电生理特征
- Q-foxp2-03（中优先级）：264靶基因中哪些是言语运动特异性的vs一般运动学习共享的

---

## 2026-08-11 · 文章 #110 · 大脑永远在押注：主动推断、精度控制与神经调质的统一框架

**核心主题**：主动推断（active inference）作为感知-行动统一框架；期望自由能（EFE）分解为外在价值+认知价值，解决探索-利用困境；三层精度框架（感觉精度/转换精度/策略精度）对应ACh/NE/DA三大调质系统；直接实验证据（Pérez-González 2024 eLife：ACh选择性锐化听觉皮层预测误差分布 iPE 0.29→-0.05；Basu 2024 Biol Psych：前额叶NE拟合RW模型 R²=0.69，时间精度更新因果验证）；精度失调作为统一计算病理学（精神分裂/ASD/PD/MND）；断联假说（Friston 2016：NMDA功能减退→感觉精度升高→幻觉/妄想）；ASD情境适应性精度失调（Arthur 2023，非超精确先验）；DoC精度路由视角（VS=路由断联/MCS=部分恢复/CMD=运动输出精度失败）；主动推断 vs Transformer注意力机制比较（精度由内在状态分配 vs 由输入内容决定）。

**新建页面（1）**：
- `wiki/concepts/active-inference.md`（rev1，status: established，confidence: medium）— 填补 free-energy-principle 悬空引用；EFE分解；精度三层框架；AAS硬件连接；精度失调疾病模型；争议（可证伪性）

**修订页面（3）**：
- `wiki/theories/free-energy-principle.md`（rev1→rev2）— 新增"精度层级与神经调质分工"段落（三层精度表格；AAS=精度硬件；active-inference悬空引用填补）；related新增7个；key_sources新增7条2015-2024文献
- `wiki/concepts/precision-weighting.md`（rev1→rev2）— 神经调质精度分工表格精确化（加入2024实验证据）；新增精度失调疾病模型（精神分裂/ASD/PD/MND含量化证据）；新增关键证据3条；related新增4个；opens_questions新增Q-fep-02
- `wiki/concepts/norepinephrine-locus-coeruleus.md`（rev4→rev5）— 新增"LC在主动推断框架中的计算角色"段落（Sales 2019模型/Basu 2024时间精度更新 R²=0.69/三层精度框架定位NE=转换精度层/颠倒U型计算学解释）；关键证据表新增2行；related/connected新增3个；key_sources新增PMID:30608922/38316333

**图谱更新**：213节点/1226边 → 214节点/1246边（+1节点，+20边）

**新增未解问题**：
- Q-ai-01（中优先级）：5-HT在精度框架中的具体角色——内感觉精度还是时间深度？如何实验检验？

---

## 2026-08-10 · 文章 #109 · 脑干如何"点亮"大脑：上行激活系统的多源神经化学解剖与意识调控

**核心主题**：上行激活系统（AAS）的五核团架构（LC-NE / DRN-5HT / PPT-LDT-ACh / TMN-His / LH-Orexin）；Fuller 2011双通道模型（丘脑路次要 / 基底前脑路主要；PB/PC谷氨酸通路毁损→昏迷样状态）；Edlow 2024 VTA作为dAAN枢纽（人类超高分辨率MRI）；LC倒U型增益曲线与选择性集合体拓扑；AD/PD早期LC退变（55%神经元丢失早于Aβ斑块）；DRN→VTA血清素通路的清醒促进（Wang 2024，光遗传/化学遗传）；VLPO-AAS翻转开关模型（Arrigoni & Fuller 2022）；腺苷/PGD₂的睡眠驱动信号；食欲素作为系统稳定器；NT1中95%食欲素神经元丢失（Rauf 2025）；OX2R激动剂danavorexton（MWT+11.1分）。

**新建页面（3）**：
- `wiki/systems/ascending-arousal-system.md`（rev1，status: established，confidence: high）— 五核团架构、两通道模型、VTA枢纽、翻转开关
- `wiki/concepts/orexin-hypocretin.md`（rev1，status: established，confidence: high）— 食欲素生理、NT1病理、OX2R治疗
- `wiki/concepts/flip-flop-switch-sleep-wake.md`（rev1，status: established，confidence: high）— VLPO双稳互抑、腺苷信号、食欲素稳定化

**修订页面（2）**：
- `wiki/concepts/norepinephrine-locus-coeruleus.md`（rev3→rev4）— 新增LC在AAS中的解剖位置（腹侧通路）、选择性集合体拓扑组织、AD/PD早期LC退变机制；related新增ascending-arousal-system、disorders-of-consciousness
- `wiki/systems/neuromodulator-systems.md`（rev4→rev5）— 新增"AAS框架"小节（两通道架构、PB/PC谷氨酸通路、VTA枢纽、翻转开关）；related新增ascending-arousal-system、orexin-hypocretin、flip-flop-switch-sleep-wake

**图谱更新**：210节点/1206边 → 213节点/1226边（+3节点，+20边）

**新增未解问题**：
- Q-aas-01（高优先级）：AAS五系统的冗余度与关键节点
- Q-aas-02（中优先级）：人类AAS活体功能图谱（7T MRI技术挑战）
- Q-aas-03（低优先级）：翻转开关之外的睡眠-清醒调控（皮层自上而下路径）

---

## 2026-08-09 · 文章 #108 · 意识的边界：意识障碍的神经回路机制与前脑中间回路

**核心主题**：意识障碍（DoC）的连续谱分类（昏迷→VS/UWS→MCS→CMD）；前脑中间回路（Mesocircuit Hypothesis，Schiff 2009/2022）——皮层损伤→纹状体失驱动→GPi脱抑制→中央丘脑过度抑制→VS/UWS自我维持的可逆回路阻断；认知运动解离（CMD）——25%"无反应"患者有隐蔽意识（Bodien NEJM 2024，n=353）；PCI阈值（0.31）区分MCS/VS，rTMS响应生物标志物；唑吡坦悖论的GPi机制；上行激活系统受损与DMN/FPN网络破碎化。

**新建页面（3）**：
- `wiki/diseases/disorders-of-consciousness.md`（意识障碍）🔵 mainstream · 高置信度 — DoC 4级分类（昏迷/VS-UWS/MCS/CMD）；上行激活系统、前脑中间回路、功能网络破碎化三层机制；25% CMD发现；治疗窗口（金达胺素RCT/唑吡坦/rTMS/DBS）；left额顶有效连接是最强意识预测因子
- `wiki/concepts/cognitive-motor-dissociation.md`（认知运动解离，CMD）🟡 emerging · 高置信度 — 行为缺失但神经信号显示意识的状态；4条机制路径（传出通路损伤/丘脑皮层整合不稳定/DMN受损/药物遮蔽）；任务型fMRI（"打网球"想象）+EEG（P300/SSVEP）+PCI检测方法；伦理含义（撤除生命支持时患者可能有意识地"在场"）
- `wiki/concepts/mesocircuit-hypothesis.md`（前脑中间回路假说）🟡 emerging · 中置信度 — Schiff提出的GPi脱抑制→中央丘脑抑制→VS/UWS自我维持机制；ASCII回路图解；唑吡坦悖论机制（GPi优先结合GABAA ω-1受体）；金达胺素（多巴胺能→纹状体→GPi）；四项局限性（机制异质性/间接证据/缺乏大规模验证/DBS缺乏RCT）

**修订页面（2）**：
- `wiki/systems/thalamus.md` rev6→rev7 — 新增disease维度；related新增disorders-of-consciousness/mesocircuit-hypothesis；髓板内核群节扩展CL/CM-PF在DoC中的角色（GPi抑制、DAI、DBS目标）；新增Q-doc-03；key_sources新增PMID:36563999/PMID:33318675
- `wiki/concepts/neural-correlates-of-consciousness.md` rev2→rev3 — 新增disease维度；related新增disorders-of-consciousness/cognitive-motor-dissociation/mesocircuit-hypothesis；新增"临床窗口：DoC对NCC框架的压力测试"节（CMD挑战报告范式/GPi机制给Enabling NCC提供可逆干预/PCI临床化/左额顶有效连接）；key_sources新增PMID:39141852/PMID:38217619

**图谱更新**：`wiki/_graph.json` 210节点/1206条边（+3节点/+17条边）；新节点：disorders-of-consciousness、cognitive-motor-dissociation、mesocircuit-hypothesis；新边连接：← thalamus/basal-ganglia/neural-correlates-of-consciousness/global-workspace-theory/perturbational-complexity-index/dopamine-reward-prediction-error等

**新增未解问题（3）**：Q-doc-01（CMD在急性ICU期的检出率与早期预后价值）、Q-doc-02（TBI vs 缺氧性损伤中前脑中间回路差异）、Q-doc-03（中央外侧丘脑DBS大规模RCT时间线）

---

## 2026-08-08 · 文章 #107 · 意识的分水岭在何处：后方皮层、前额叶与多重发生器

**核心主题**：神经意识关联（NCC）的三分框架（内容特异/完整/使能）；COGITATE 2025 最终结果（IIT后方同步缺失+GNWT偏移点燃缺失，但内容在后方解码+脑范围广播确认）；GNW回应论文（PMID:41080705，Naccache/Dehaene/Changeux）的四点防守及其暴露的可证伪性问题；多重发生器假说（MGH，Kirkeby-Hinrup 2025）提出所有理论可能各描述真实的不同发生器；无报告范式的方法论局限（认知监控混淆）；PFC的局部意识处理（sEEG 200–300ms证据）；扰动复杂度指数（PCI）的理论基础与临床应用；意识与AI的对比。

**新建页面（1）**：
- `wiki/theories/multiple-generator-hypothesis.md`（多重发生器假说）⚪ speculative · 低置信度 — 意识可能由多个并行发生器共同产生；原则（principle）vs 发生器（generator）核心区分；现有理论各自描述了不同发生器；对物种意识和AI意识评估的影响；目前纯理论提案（PMID:41000147）

**修订页面（3）**：
- `wiki/concepts/neural-correlates-of-consciousness.md` rev1→rev2 — 整合GNW回应论文（PMID:41080705）的四点防守；PFC局部意识处理sEEG证据（PMID:38265851）；无报告范式的认知监控混淆批评（PMID:35634201）；MGH框架（PMID:41000147）；新增Q-ncc-04/05/06；related新增multiple-generator-hypothesis；key_sources新增4项
- `wiki/theories/global-workspace-theory.md` rev6→rev7 — 新增MGH视角（GWT广播机制可能是多重发生器之一）；C-2026-05-31-02矛盾焦点转移到GWT可证伪标准问题注记；related新增multiple-generator-hypothesis
- `wiki/theories/integrated-information-theory.md` rev3→rev4 — 新增MGH提供的理论逃脱路径（整合信息原则可能通过其他发生器实现）；related新增multiple-generator-hypothesis

**矛盾更新（2）**：
- C-2026-05-31-01（IIT后方同步 vs COGITATE）：evidence_update更新——GNW回应未为IIT辩护；MGH提供理论逃脱路径但不改变claim_B对特定机制的否定；状态 open，claim_B证据基础更厚实
- C-2026-05-31-02（GWT偏移点燃 vs COGITATE）：evidence_update更新——GNW回应提供系统性防守；矛盾焦点转移到GWT可证伪标准；状态 open，新矛盾：什么结果能证伪GWT

**新增未解问题（3）**：Q-ncc-04（多重发生器如何实验检验）、Q-ncc-05（深麻醉-意识分离实验）、Q-ncc-06（PCI测量的发生器成分）

---

## 2026-08-07 · 文章 #106 · 组装句子的机器：Broca区如何将词汇序列升维为层级结构

**核心主题**：BA44的Merge操作（短语结构组装）；BA44/BA45功能分工（grammatical vs semantic）；弓状束精细结构（Vavassori 2023三段解剖）；人类BA44进化双重结构（Gallardo 2023，左侧前部扩张1.64倍）；儿童句法神经重组（Klein 2022，3岁pSTS→4岁BA44）；语言网络的"自然种"地位（Fedorenko 2024）；LLM-大脑对齐的含义与限制（Hosseini 2024：1亿词达最大预测力）。

**新建页面（3）**：
- `wiki/concepts/phrase-structure-building.md`（短语结构组装/Merge）🟡 mainstream · 高置信度 — Chomsky Merge操作的神经基础；左侧BA44（pars opercularis）；AⁿBⁿ型层级规则选择性激活BA44；Schell 2022 MVPA分类图谱；产出和理解共享同一套Merge机制（Hu 2022）
- `wiki/concepts/language-evolution.md`（语言的神经进化）🟡 emerging · 中置信度 — 人类左侧BA44前部扩张约1.64倍（相对黑猩猩，Gallardo 2023）；进化双重结构（后部动作/前部句法）；否定强版本镜像神经元语言假说；前向扩张模型
- `wiki/concepts/llm-brain-alignment.md`（LLM-大脑对齐）🟡 emerging · 中置信度 — GPT-2等LLM可预测语言网络fMRI响应；1亿词训练量已达近最大对齐度（Hosseini 2024）；单向注意（GPT-2）比双向注意（BERT）更接近大脑；表征相似性≠机制等同

**修订页面（3）**：
- `wiki/systems/broca-area.md` rev1→rev3 — 新增进化双重结构（Gallardo 2023）、发育神经重组（Klein 2022，3→4岁）、MVPA分类图谱（Schell 2022）、精准fMRI产出证据（Hu 2022）；新增Q-lang-06；related新增phrase-structure-building/language-evolution
- `wiki/systems/language-network.md` rev3→rev5 — 新增"自然种"框架（Fedorenko 2024）、精准fMRI产出-理解统一（Hu 2022）、信息分布（Pasquiou 2023）、LLM对齐（Hosseini 2024）、儿童发育分离（Hiersche 2024）；related新增phrase-structure-building/llm-brain-alignment
- `wiki/concepts/arcuate-fasciculus.md` rev1→rev2 — 新增Vavassori 2023三段解剖+完整功能谱（右半球AF：社会认知/空间注意/音乐）+手术风险；新增Klein 2022发育AF髓鞘化证据

**矛盾登记（0）**：无新矛盾；Q-lang-03（语法/语义神经解离）维持open状态

**新增未解问题（1）**：Q-lang-06（BA44前部扩张与FOXP2人类特异突变的关联机制）

---

## 2026-08-06 · 文章 #105 · 连接组学深化篇：功能连接组学与同类相连布线规则

**核心主题**：功能连接组学——MiCrONS 2025（小鼠视觉皮层：75,000神经元钙成像 + 200,000+细胞 EM重建 + 5亿突触）；"同类相连"布线规则（Ding 2025）：功能相似神经元优先互连，控制距离后仍成立，跨层跨区域普遍有效；果蝇全脑网络统计（Lin 2024）：小世界系数141、平均路径4.42跳、富人俱乐部40,218神经元；结构-功能鸿沟的三个根本来源（静态快照/强度不可见/调质缺失）。

**新建页面（2）**：
- `wiki/concepts/small-world-network.md`（小世界网络）🟢 established · 高置信度 — 同时具有高聚类（局部模块）和短路径（全局整合）的网络组织；果蝇全脑 σ=141；跨尺度（微观神经元到宏观脑区）普遍存在；进化最优权衡假说
- `wiki/concepts/like-to-like-connectivity.md`（同类相连）🟡 emerging · 中置信度 — 功能相似的视觉神经元优先互连；控制物理距离后仍成立；跨层跨区域（V1→V2/AL，含反馈）；高阶规律（突触后细胞群相似度 > 一对一预测）；RNN 自发产生类似规律；因果机制未知（Hebbian vs 分子亲和 vs 突触修剪）

**修订页面（1）**：
- `wiki/methods/connectomics.md` rev1→rev2 — 增加"功能连接组学"新节（MiCrONS 2025）；增加"同类相连"规律（Ding 2025）；增加完整网络统计数据（Lin 2024）；related 新增 small-world-network、like-to-like-connectivity、rich-club-organization；key_sources 新增 PMID:40205214、PMCID:PMC11981947、PMID:37547019

**矛盾登记（0）**：无新矛盾

**新增未解问题（3）**：Q-swn-01（小世界系数跨尺度比较）、Q-ltl-01（like-to-like是否适用联合皮层）、Q-ltl-02（like-to-like因果机制）

---

## 2026-08-05 · 文章 #104 · 逆行的信使：内源性大麻素如何让突触后神经元掌控自身的输入

**核心主题**：内源性大麻素系统（ECS）——突触后神经元合成 2-AG/AEA 作为逆行信使，激活突触前 CB1R（Gi/o），通过 Gβγ 抑制 Cav2.2（DSI/DSE，秒级）和 Gαi→cAMP↓→RIM1α（eCB-LTD，长时程）两套下游机器；CB1R 富集于 CCK⁺ 中间神经元；BLA 中 AEA/FAAH 轴调控恐惧消退；非逆行模式（AEA→TRPV1、星形胶质细胞 CB1R、SSI）。

**新建页面（2）**：
- `wiki/concepts/endocannabinoid-system.md`（内源性大麻素系统）🟢 established · 高置信度 — 核心机制：2-AG（DGLα 合成，MAGL 降解，全激动剂）vs AEA（NAPE-PLD 合成，FAAH 降解，部分激动剂/TRPV1 全激动剂）；DSI/DSE 完整步骤；eCB-LTD 通过 RIM1α；CCK⁺ 靶细胞；非逆行模式；FAAH 抑制增强恐惧消退（PTSD 靶点）
- `wiki/neurons/cb1-receptor.md`（CB1 大麻素受体）🟢 established · 高置信度 — Gi/o 偶联；Gβγ→Cav2.2（短时程）；Gαi→RIM1α（长时程 LTD）；GIRK 激活（SSI）；CCK⁺ 富集；各脑区分布与功能；配体效能对比（2-AG、AEA、THC）

**修订页面（2）**：
- `wiki/concepts/ltd.md` rev3→rev4 — 深化 eCB-LTD 的前突触机制（Gαi→cAMP/PKA→RIM1α 与 NMDA-LTD 的并列）；新增 iLTD/eLTD 分类；related 新增 endocannabinoid-system、cb1-receptor、stdp；opens_questions 新增 Q-ecb-01；key_sources 新增 PMID:23040807、PMID:16776579
- `wiki/concepts/fear-extinction.md` rev4→rev5 — 新增 BLA 中 AEA/CB1R 的消退分子机制；FAAH 抑制增强消退；FAAH 抑制剂 PTSD 2a 期数据；related 新增 endocannabinoid-system、cb1-receptor；key_sources 新增 PMID:34598785

**矛盾登记（0）**：无新矛盾

**悬空引用解决（0）**：无（两新页的 related 均指向已有节点）

**新增开放问题（4个）**：
- Q-ecb-01（高优先级）：eCB-LTD 与 NMDA-LTD 在同一突触如何共存/竞争
- Q-ecb-02（高优先级）：FAAH 抑制剂人类 PTSD 3 期临床结果
- Q-ecb-03（中优先级）：SSI（慢自我抑制）在体内生理条件下的实际发生
- Q-ecb-04（中优先级）：CB2R 神经炎症通路的治疗靶点价值

**图谱**：199节点→201节点，1145边→1159边（+2节点，+14边）

---

## 2026-08-04 · 文章 #103 · 时间细胞：海马如何为情节记忆打上时间戳

**核心主题**：海马时间细胞（time cells）——在空白延迟期中依次激发的CA1神经元集群；时间vs路径积分的解耦；时间细胞的可缩放性与多尺度编码（秒/分/天）；驱动回路（MEC光遗传学因果证据+CA2专门组织者）；人类单细胞记录验证（Umbach 2020 PNAS、Reddy 2021 JNeurosci）；与AI序列建模的比较（LSTM细胞状态、Transformer位置编码）。

**新建页面（2）**：
- `concepts/time-cells.md`（时间细胞）🟡 emerging · 高置信度 — 整合MacDonald 2011原始发现、Eichenbaum 2014综述、Kraus 2013时间vs距离解耦（92%神经元时间调制）、Mau 2018多尺度（秒/分/天）、Shimbo 2021可缩放性（缩放因子1.81）、Robinson 2017 MEC光遗传学因果（MEC沉默→时间细胞降解，地点细胞保留）、MacDonald&Tonegawa 2021 CA2因果（CA2→CA1投射专门组织时间序列）、Umbach 2020 PNAS人类证据（激发精度预测时间聚类性，首次人类theta相位进动）、Reddy 2021 JNeurosci（30%人类海马神经元时间依赖激发，88.4%解码准确率）；登记Q-tc-01~Q-tc-04
- `concepts/temporal-context-model.md`（时间情境模型TCM）🟡 emerging · 中置信度 — Howard & Eichenbaum 2013理论框架：海马维持缓慢漂移的时间情境状态；自然解释recency effect和contiguity effect；精神时间旅行的神经机制候选；时间细胞是TCM神经实现候选

**修订页面（3）**：
- `neurons/hippocampal-circuit.md` rev10→rev11 — 新增"CA2亚区：时间序列专门组织者"机制节（CA2→CA1专门通路、50%CA1细胞有时间特性、空间-时间双分离）；更新"当前理解"为三流输入（LEC内容+MEC时间+CA3空间）；CA1升格为三路整合终点；related新增time-cells、temporal-context-model；opens_questions新增Q-tc-01/02/04；key_sources新增3项
- `systems/entorhinal-cortex.md` rev2→rev3 — 更新MEC功能："空间+时间"双重编码；新增斜坡细胞（ramping cells）描述；增加MEC时间特异性光遗传因果证据（Robinson 2017）和人类斜坡细胞证据（Umbach 2020）；连接新增time-cells
- `concepts/interval-timing.md` rev1→rev2 — 新增"海马时间细胞：秒-天尺度的情境时间编码"小节，含区间计时（纹状体/小脑/皮层）vs海马时间细胞的功能对比表；连接新增time-cells、hippocampal-circuit；开放问题Q-tc-03

**新增开放问题（4）**：
- Q-tc-01（高）：时间细胞是内在计时器还是内隐认知序列的神经表征？两种解释框架能否实验区分？
- Q-tc-02（高）：时间细胞对情节记忆提取的**因果**贡献是什么？（相关已知，直接因果操控人类时间细胞的研究尚不存在）
- Q-tc-03（中）：海马时间细胞与纹状体/小脑区间计时机制的功能分工？分层架构还是并行独立系统？
- Q-tc-04（中）：情节记忆固化时，时间细胞序列如何在SWR中被回放？精确重现还是压缩/重排？

**未登记矛盾**：本次无新增矛盾登记。（Q-tc-01的两种框架虽有张力，但非直接证据冲突，暂作开放问题而非矛盾登记。）

---

## 2026-08-02 · 文章 #101 · 痛觉的守门人：TRPV1、脊髓背角与慢性疼痛的神经机制

**核心主题**：痛觉的完整神经科学图谱——外周伤害感受器（TRPV1/TRPA1/Nav1.7-1.9）；Aδ vs C纤维双时程痛觉；脊髓背角闸门控制（DYN+/PKCγ+/SOM+分子定义回路）；中枢敏化（NMDA-LTP机制+小胶质细胞-BDNF-KCC2恶性循环）；脊髓丘脑束→痛觉矩阵；cingulotomy情感-感觉分离；PAG-RVM下行阿片镇痛回路；慢性疼痛作为中脑边缘系统劫持。

**知识库首次覆盖痛觉系统**：此前 wiki 完全无痛觉相关页面；本文新建6个核心页面并修订3个现有页面，填补感觉系统最后一块重大空白。

**新建页面（6）**：
- `concepts/nociceptor.md`（伤害感受器）🟢 established · 高置信度 — TRP通道（TRPV1/TRPA1/TRPM8/TRPV2）；Nav1.7/1.8/1.9（Nav1.7人类遗传金标准验证）；P2X3 ATP传感器；Aδ vs C纤维双时程；外周致敏分子机制（PGE2/缓激肽/NGF）；Q-pain-01/Q-pain-02
- `concepts/gate-control-theory.md`（闸门控制理论）🔵 mainstream · 高置信度 — Melzack-Wall 1965历史；Koch 2018分子验证：DYN+/Ret+（抑制）/PKCγ+/SOM+（兴奋）；闸门开/关回路图；KCC2下调-GABA翻转；小胶质细胞-BDNF正反馈；PAG-RVM下行控制；历史模型 vs 现代分子修订对比表；Q-pain-03
- `concepts/central-sensitization.md`（中枢敏化）🟢 established · 高置信度 — NMDA-Ca²⁺-多激酶级联（MAPK/PKC/Src/PKA/PI3K）；wind-up现象；KCC2下调机制（小胶质细胞-BDNF-TrkB→KCC2↓→GABA去极化）；与海马LTP同源对比表；临床相关性（纤维肌痛/氯胺酮预防慢性痛）；Q-pain-04
- `systems/pain-matrix.md`（痛觉矩阵）🔵 mainstream · 中置信度 — S1/S2/岛叶/ACC/PFC三维度分工；新脊丘束/旁脊丘束双路分叉（VPL vs VMpo→ACC）；cingulotomy经典分离；Tracey & Mantyh 2007框架；Wager NPS模式分析；Baliki & Apkarian慢性化中脑边缘系统重组
- `systems/anterior-cingulate-cortex.md`（前扣带回）🟢 established · 高置信度 — dACC/sgACC/rACC三亚区分工；cingulotomy"知痛不感苦"分离证据；ACC→PAG下行镇痛；社会排斥-身体疼痛共享dACC（Eisenberger 2003）；共情性疼痛；慢性化NAc-ACC功能连接预测因子
- `systems/periaqueductal-gray.md`（导水管周围灰质）🟢 established · 高置信度 — PAG刺激镇痛+纳洛酮阻断内源性阿片因果证据；vlPAG细胞多样性（McPherson & Ingram 2022）；μ-OR双重位置（细胞体+突触前GABA末梢）；RVM ON/OFF-cells分工；急性vs慢性疼痛PAG状态转换；应激诱导镇痛（SIA）机制

**修订页面（3）**：
- `systems/somatosensory-cortex.md` rev1→rev2 — 新增"S1在痛觉中的角色"小节（脊髓丘脑束→VPL→S1感觉分辨通路；cingulotomy后S1保留；Q-s1-02直接解答）；related新增pain-matrix, nociceptor
- `systems/thalamus.md` rev5→rev6 — 新增"痛觉丘脑核团"小节（VPL→S1 vs VMpo/MDvc→ACC/岛叶双路分叉表）；related新增pain-matrix, nociceptor
- `concepts/nmda-receptor.md` rev5→rev6 — 新增第六重角色：脊髓背角中枢敏化触发器（wind-up/氯胺酮临床验证）；related新增central-sensitization, gate-control-theory

**新增开放问题（4）**：
- Q-pain-01（高）：Nav1.7遗传验证vs临床试验失望——为何遗传靶点无法直接转化为药物？代偿机制？
- Q-pain-02（中）：沉默伤害感受器（mechanically insensitive C fibers）炎症后获得机械敏感性的分子切换机制？
- Q-pain-03（中）：Melzack-Wall"T细胞"对应哪些分子亚型？NK1R+投射神经元是否是现代版本？
- Q-pain-04（高）：中枢敏化建立后是否有干预可完全逆转？KCC2下调/抑制性神经元丧失有多少是可逆的？

**图谱**：188节点→194节点（+6：nociceptor, gate-control-theory, central-sensitization, pain-matrix, anterior-cingulate-cortex, periaqueductal-gray），1100边→~1118边（+~18新边）

---

## 2026-08-01 · 文章 #100（里程碑）· 读懂另一个心灵：心智理论×TPJ×镜像神经元×社会脑

**核心主题**：心智理论（ToM）的神经网络——pTPJ（信念推断/视角转换）、mPFC（腹侧特质推断/背侧抽象心理状态推断）、DMN dMPFC 子系统（社会叙事整合）三节点分工；镜像神经元系统（MNS，Rizzolatti 1992猕猴 F5→BA44 同源）与 ToM 的关系争议（Hickok "broken mirror" 批评）；ASD 中 DMN 功能连接降低与 ToM 缺陷的关联；GPT-4 ToM 测试的双重解读。

**第100篇里程碑**：知识库迈入三位数文章，覆盖社会认知神经科学这一此前空白的重要课程领域（课程脊柱8社会认知）。

**新建页面（3）**：
- `concepts/theory-of-mind.md`（心智理论）🟢 established · 高置信度 — 核心三节点神经网络（TPJ/mPFC/DMN）；假信念任务；发育轨迹；ASD 连接；AI 类比；Q-tom-01至Q-tom-03
- `systems/temporoparietal-junction.md`（颞顶联合区）🟢 established · 高置信度 — 前-后轴分工（pTPJ信念推断/aTPJ注意定向）；VAN-DAN双网络架构；进化与发育轨迹；临床关联（ASD/精神分裂症/空间忽视）
- `concepts/mirror-neuron-system.md`（镜像神经元系统）🔴 contested · 中置信度 — Rizzolatti 1992猕猴 F5 区 ~17% MNS神经元；直接匹配假说；Hickok 2009/2014 破碎镜子批评；模拟理论 vs. 理论理论；C-mirror-01争议登记

**修订页面（1）**：
- `systems/default-mode-network.md` rev3→rev4 — 新增 DMN dMPFC 子系统在 ToM 中的核心角色；Spreng 2021 DMN-TPJ 功能耦合随心智化任务需求增加的元分析证据；ASD DMN 连接降低与 ToM 缺陷关联；related 新增 theory-of-mind, temporoparietal-junction

**矛盾登记（1）**：
- `C-mirror-01`（MNS-ToM 因果关系争议）：Rizzolatti/Gallese 模拟理论 vs. Hickok 理论理论；当前证据等级：MNS 对 ToM 因果必要性——低（无直接因果实验）

**新增开放问题（3）**：
- Q-tom-01（高）：TPJ 是否真正专一于 ToM？前-后轴分工是否足够？"脱耦合"功能能否统一解释？
- Q-tom-02（中）：MNS 在 ToM 中的精确因果贡献？TMS BA44 对假信念任务的效应？
- Q-tom-03（中）：ASD 中 DMN 功能连接降低是 ToM 缺陷的原因还是结果？纵向发育数据？

**悬空引用**：新页面引用 [[social-brain-network]]（未建页面）、[[ventral-attention-network]]（未建页面）——暂标为待建

**图谱**：185节点→188节点（+3：theory-of-mind, temporoparietal-junction, mirror-neuron-system），1085边→1100边（+15新边）

---

## 2026-07-31 · 文章 #99 · 大脑的秒表：区间计时的分布式神经机制

**核心主题**：区间计时（interval timing）——小脑如何以橄榄-小脑系统实现毫秒级事件计时；纹状体拍频模型（SBF）如何以皮层振荡子+MSN符合检测实现秒级计时；种群时钟（population clock）如何从循环网络高维轨迹中涌现时间；D1-MSN（降）与D2-MSN（升）如何对立协同累积时间证据；多巴胺"调速时钟"假说在帕金森病证据面前为何不够。

**新建页面（3）**：
- `concepts/interval-timing.md`（区间计时）🔵 mainstream · 高置信度 — 整合小脑事件计时、纹状体秒级计时、种群时钟三套机制；韦伯定律的时间版；多巴胺的复杂调制；从TBW（上游）到认知脚手架
- `concepts/striatal-beat-frequency.md`（纹状体拍频模型）🔵 mainstream · 中置信度 — SBF核心三要素（振荡子/符合检测/多巴胺重置）；为何需要生物学噪声维持标量性；与斜坡/种群时钟的关系待定
- `concepts/population-clock.md`（种群时钟）🟡 emerging · 中置信度 — 内在计时：时间从网络高维轨迹涌现；神经序列vs复杂种群时钟；纹状体序列性高于运动皮层；RNN同构

**修订页面（4）**：
- `circuits/basal-ganglia.md` rev2 — 新增"基底节与区间计时"节：纹状体-丘脑-皮层的节拍计时网络；MSN斜坡（~1/3）；D1/D2对立协同；与小脑事件计时的解离
- `systems/cerebellum.md` rev2 — 新增"小脑作为区间计时器"节：事件计时（非节拍/非连续）；橄榄-小脑系统（下橄榄→攀爬纤维→浦肯野细胞LTD）；双重分离证据
- `concepts/temporal-binding-window.md` rev2 — 连接节新增[[interval-timing]]和[[striatal-beat-frequency]]；TBW作为区间计时的下游应用
- （basal-ganglia已在circuits/中，未在systems/重复创建）

**矛盾登记（0）**：无新矛盾；帕金森病时间扭曲vs"慢时钟"假说已记录为Q-it-01/Q-it-02的组成问题，证据等级分析已在文章中明确，不属于新矛盾登记

**新增开放问题**：
- Q-it-01（高）：SBF生理回路是否真实存在？SBF/斜坡/种群时钟互斥还是互补？
- Q-it-02（中）：种群时钟与专用计时器的关系？纹状体序列性差异的决定因素？下游译码器？

**悬空引用**：新页面引用 [[medium-spiny-neuron]]、[[neural-population-coding]]、[[recurrent-network]]、[[scalar-property-timing]] — 前两者检查是否已有页面；后两者暂标为待建

**图谱**：182节点→185节点（+3：interval-timing, striatal-beat-frequency, population-clock），1066边→~1085边（+~19新边）

---

## 2026-07-30（文章 #98·多感觉整合×贝叶斯因果推断×上丘三规则×麦格克效应）

**源文章**：[[2026-07-30-multisensory-integration-bayesian-brain]] —《感官的裁判：大脑如何决定"你听到的"和"你看到的"属于同一件事》

**新建页面（4）**：
- `wiki/concepts/multisensory-integration.md`（新建）— 多感觉整合的两阶段推断（因果推断→权重整合）；上丘三条 Stein-Meredith 规则；人类 fMRI 核心网络（STG/STS、丘脑枕核、脑岛/额下回、顶内沟）；贝叶斯因果推断模型统一解释；麦格克效应机制；revision_count=1；置信度：高
- `wiki/concepts/bayesian-causal-inference.md`（新建）— P(C=1) 后验因果推断；整合/分离的加权平均；"负偏移"独特预测；与 MLE 的关系（MLE 是 BCI 的特例）；实验验证（R²=0.97，Körding 2007）；revision_count=1；置信度：高
- `wiki/systems/superior-colliculus.md`（新建）— SC 浅层（视网膜输入）vs 深层（多感觉神经元）层状结构；Stein-Meredith 三条规则（空间/时间/逆效应性）；皮层依赖性（AES 失活消除整合）；半盲恢复临床转化（Stein & Rowland 2020）；SC→丘脑枕核→皮层联合区快速通路；revision_count=1；置信度：高
- `wiki/concepts/inverse-effectiveness.md`（新建）— 逆效应性：弱刺激整合获益最大；NMDA 受体 Mg²⁺ 阻断-去除非线性机制（Bhatt 2016）；行为层面验证；生态适应意义；revision_count=1；置信度：高
- `wiki/concepts/temporal-binding-window.md`（新建）— 时间绑定窗宽度（视听 ±100-200ms）；个体差异（ASD 扩宽）；候选神经机制（皮层振荡相位、STS 时间调谐、贝叶斯先验）；与麦格克效应易感性相关；revision_count=1；置信度：高

**修订页面（0）**：今日无现有页面修订（新建页面已覆盖今日核心概念）

**矛盾登记（0）**：无新矛盾。多感觉整合"最优性"（MLE 完全最优 vs. 近似最优/次优整合）的争议已在文章和 wiki 中如实并列（Angelaki 2009 的次加性批评 vs. Ernst & Banks 2002 的最优证明），但不与已有 wiki 页面中的具体主张冲突，不触发矛盾协议。

**新增开放问题（3）**：
- Q-msi-01（高优先级）：时间绑定窗（TBW）的神经振荡基础（θ/α 相位？STS 时间调谐？）
- Q-msi-02（中优先级）：SC 皮层下整合和 STS 皮层整合的串/并联关系
- Q-msi-03（低优先级）：多模态 AI 是否可以实现真正的不确定性加权整合

**悬空引用解决（0）**：今日未解决已有悬空引用

**新增悬空引用**：`nmda-receptor` 已有页面（确认已存在于 graph）；`predictive-coding` 已有页面；无新悬空引用

**图谱**：177→182 节点（+5：multisensory-integration、bayesian-causal-inference、superior-colliculus、inverse-effectiveness、temporal-binding-window），1055→1066 边（+11 条新边）

---

## 2026-07-29（文章 #97·S1初级躯体感觉皮层×LTMR机械感受器×Merzenich可塑性革命）

**源文章**：[[2026-07-29-s1-somatosensory-cortex-body-map-plasticity]] —《触觉的神经地图：S1 初级躯体感觉皮层如何将皮肤信号变为身体意象，以及为什么这张地图是活的》

**新建页面（4）**：
- `wiki/systems/somatosensory-cortex.md`（新建）— 四亚区（3a/3b/1/2）及其输入偏好；感觉小人与皮层放大因子；Merzenich 系列实验（截指后皮层重组/行为训练后表征扩张/被动刺激无可塑性对照）；多时间尺度可塑性机制（GABA解除/LTP/LTD/轴突出芽）；感觉剥夺重启成年关键期状态（PMID:28658619）；幻肢痛与皮层侵占；revision_count=1；置信度：高
- `wiki/neurons/mechanoreceptor-ltmr.md`（新建）— 四类 LTMR 特性对比表（SA1 Merkel/SA2 Ruffini/RA1 Meissner/RA2 Pacini）；PIEZO2 机械转导；脊髓背角机械感觉柱整合（Abraira & Ginty 2013）；感受野密度与皮层放大因子的数量关系；revision_count=1；置信度：高
- `wiki/concepts/cortical-plasticity.md`（新建）— 经验依赖皮层拓扑重组是新皮层普遍属性；Merzenich 1992 频率辨别训练实验（行为相关性必要性/阴性被动对照）；三时间尺度机制（GABA解除-Hebbian LTP/LTD-结构重塑）；行为相关性门控（胆碱能增益）；感觉剥夺类关键期重启；病理面（幻肢痛/焦肌张力障碍）；revision_count=1；置信度：高
- `wiki/concepts/homunculus.md`（新建）— Penfield 感觉小人（1950术中电刺激）；比例失真原理（感受器密度正比）；现代修正（Roux 2018 指节梯度 PMID:29285773；Saadon-Grosman 2020 高级皮层躯干权重差异 PMID:32954277）；动态可塑性；revision_count=1；置信度：高

**修订页面（1）**：
- `wiki/concepts/hebbian-learning.md` rev5→rev6 — updated=2026-07-29；related 新增 cortical-plasticity 和 somatosensory-cortex；连接段新增"皮层可塑性是 Hebb 原理在皮层地图尺度的体现"和"Merzenich 系列实验（1983–1993）是 Hebb 原理在皮层地图层面的直接体内证据"；source_articles 新增当日文章

**矛盾登记（0）**：无新矛盾。幻肢痛与皮层重组的因果关系（Makin & Flor 2020批评"重组→疼痛"简单因果链）已在文章和 somatosensory-cortex.md 中标注为"Q-s1-幻肢因果争议"，但因不与既有已登记主张直接冲突，不触发矛盾协议。

**新增开放问题（3）**：
- Q-s1-01（中优先级）：大规模 S1 皮层重组中，轴突出芽 vs. 潜伏连接揭露的相对贡献和时间分工
- Q-s1-02（中优先级）：S1 在疼痛处理中的角色——"触觉/疼痛"功能分工是否干净？
- Q-s1-03（中优先级）：SA2（Ruffini 终末）在人类本体感觉中的确切贡献（人类电生理证据稀少）

**图谱**：177 节点（+4：somatosensory-cortex、mechanoreceptor-ltmr、cortical-plasticity、homunculus），1056 边（+15 条新边，见 _graph.json）

---

## 2026-07-28（文章 #96·耳蜗音调拓扑图×听觉皮层层级→鸡尾酒会问题的皮层解答）

**源文章**：[[2026-07-28-auditory-cortex-tonotopy]] —《从蜗旋到皮层音图：耳蜗如何将声音的物理频率映射为大脑的功能地图，听觉皮层如何通过注意力解决"鸡尾酒会问题"》

**新建页面（3）**：
- `wiki/systems/auditory-cortex.md`（新建）— 核心-带状-旁带状三级层级（Rauschecker & Scott 2009，PMID:19471271）；11张听觉场图（Brewer & Barton 2016，PMID:27145914）；腹侧"What"流 + 背侧"Where/How"流；STG鸡尾酒会注意性选择编码（Mesgarani & Chang 2012，PMID:22522927）；pSTG STRF语音重建（Pasley et al. 2012，PMID:22303281）；revision_count=1；置信度：高
- `wiki/systems/cochlea.md`（新建）— 基底膜地点编码（Robles & Ruggero 2001，PMID:11427697）；外毛细胞 Prestin 耳蜗放大器（+40–50 dB，Q因子×100）；内毛细胞机械-电换能（tip links/TMC1-TMC2/Ca_v1.3/ribbon synapse）；听耳声发射（OAEs）；revision_count=1；置信度：高
- `wiki/concepts/tonotopic-map.md`（新建）— 频率-位置有序排列原则（cochlea → CN → SOC → IC → MGB → A1）；11张场图两轴组织（音调梯度×周期性梯度）；侧向抑制增强频率对比；成人可塑性重组（Merzenich组）；与方向选择性/网格细胞/场所细胞类比为皮层拓扑计算通用策略；revision_count=1；置信度：高

**修订页面（1）**：
- `wiki/systems/thalamus.md` rev5 — updated=2026-07-28；revision_count 4→5；MGBv（腹侧核，精确音调拓扑投射至 A1）+ MGBd（背侧核）+ MGBm（内侧核）三区功能分化；related 新增 auditory-cortex；连接节新增 auditory-cortex；source_articles 新增 2026-07-28-auditory-cortex-tonotopy

**矛盾登记（0）**：无新矛盾。Jeffress 延迟线模型（哺乳类 MSO 双侧 ITD 机制）的哺乳类证据争议已在文章中明确标注为"Q-ac-04 开放问题"，不触发矛盾协议（同一领域的不同模型竞争，而非已核查数据的直接矛盾）。

**新增开放问题（4）**：
- Q-ac-01（中优先级）：A1 拓扑图在成人行为中是否被学习历史重组（固定感觉分析器 vs 可塑经验图）？
- Q-ac-02（高优先级）：注意过滤是否也发生在皮层下（MGB 甚至 IC），或仅限皮层？其解剖通路？
- Q-ac-03（中优先级）：11 张场图是否在所有成人中普遍存在，还是受个体语言/音乐经历影响？
- Q-ac-04（低优先级）：ITD 在哺乳类 MSO 的神经机制是否真的是 Jeffress 延迟线？

**图谱**：173 节点（+3：auditory-cortex、cochlea、tonotopic-map），1042 边（+8：cochlea→tonotopic-map/mechanism-of、tonotopic-map→auditory-cortex/part-of、auditory-cortex→thalamus/prerequisite-for、cochlea→auditory-cortex/prerequisite-for、tonotopic-map→orientation-selectivity/related、tonotopic-map→grid-cell/related、tonotopic-map→place-cell/related、cochlea→voltage-gated-calcium-channels/prerequisite-for）

---

## 2026-07-27（文章 #95·网格细胞×头向细胞×边界细胞→大脑内置坐标系×认知地图拼贴图批评）

**源文章**：[[2026-07-27-grid-cells-head-direction-spatial-coordinate-system]] —《大脑内置的坐标系：网格细胞、头向细胞与边界细胞如何共同搭建空间认知地图》

**新建页面（2）**：
- `wiki/neurons/head-direction-cells.md`（新建）— 对头部方向选择性放电；Taube 1990/1995；首选方向+高斯调谐（~90°宽）；地标锚定+黑暗中短期维持；环形吸引子（ring attractor）生成机制；PoS/ADN/LMN/DTN/RSC分布层次；联合细胞整合头向×网格；revision_count=1；置信度：高
- `wiki/neurons/border-cells.md`（新建）— 对环境边界的特定距离/方向编码；Solstad 2008；完全跟随边界缩放（vs场所场50%跟随）；为路径积分提供重置锚点；Jeffery 2024 拼贴图批评：边界是空间坐标系分段点；revision_count=1；置信度：高

**修订页面（2）**：
- `wiki/neurons/grid-cell.md` rev2 — updated=2026-07-27；revision_count 1→2；related 新增 head-direction-cells、border-cells、entorhinal-cortex；key_sources 新增 PMID:20090680、PMID:29073650、PMID:38231426；source_articles 新增 2026-07-27-grid-cells-head-direction-spatial-coordinate-system；**新增第5节"模块结构与多尺度精度"**（1.4:1间距比、残差数系统原理）；**新增第6节"头向细胞接口"**（联合细胞）；更新第7节（Behrens 2018非空间应用）；**新增关键证据**：人类fMRI六边形信号（PMID:20090680）、网格模式扭曲（PMID:38231426）；**新增Q-grid-human-single-unit**；更新连接（head-direction-cells、border-cells、entorhinal-cortex）
- `wiki/neurons/place-cell.md` rev4 — updated=2026-07-27；revision_count 3→4；related 新增 border-cells、head-direction-cells；key_sources 新增 PMID:38231426；source_articles 新增 2026-07-27；连接新增 [[border-cells]]（场所场跨边界断裂）和 [[head-direction-cells]]（角度参考框架）

**矛盾登记（0）**：无新矛盾。Jeffery 2024 的"拼贴图"批评与传统"认知地图=全局坐标系"不构成数据矛盾，而是对同一实验的**理论层面不同解读**，已在文章中并列呈现，不触发矛盾协议（新实验数据无冲突）。

**新增开放问题（3）**：
- Q-hd-ring-attractor-location（中优先级）：头向环形吸引子的物理基底：DTN、LMN、ADN 哪个是生成器？
- Q-border-cells-mechanism（中优先级）：边界细胞由感觉驱动还是从网格/场所回路推算？
- Q-grid-human-single-unit（中优先级）：人类内嗅皮层单神经元网格证据（Jacobs 2013 是开始）是否能被大样本研究扩展？

**图谱**：170 节点（+2：head-direction-cells、border-cells），1034 边（+8：新增头向→网格supports、边界→网格supports、边界→场所supports、头向→场所supports、头向→内嗅part-of、边界→内嗅part-of、头向→路径积分mechanism-of、边界→路径积分supports）

---

## 2026-07-26（文章 #94·嗅觉编码×气味分子→情绪记忆四级变换×Proust效应解剖基础）

**源文章**：[[2026-07-26-olfactory-coding-smell-memory-limbic]] —《气味的神经密码：从一个分子到一段记忆的四级变换》

**新建页面（3）**：
- `wiki/concepts/olfactory-receptor.md`（新建）— OR基因家族（人类约400功能性成员）；一细胞一受体/一受体一小球/组合编码三条规则；cAMP信号转导五步级联（OR→Gs→ACIII→cAMP→CNG→Cl⁻通道）；单等位基因表达机制；revision_count=1；置信度：高
- `wiki/systems/olfactory-bulb.md`（新建）— 小球层（一受体一小球）；僧帽/簇状细胞（主要输出）；颗粒细胞（树突-树突双向突触→侧向抑制）；周小球细胞（自上而下调制）；β/γ振荡；直接边缘系统投射（无视丘中继）；revision_count=1；置信度：高
- `wiki/concepts/piriform-cortex.md`（新建）— 稀疏编码（~10%激活，~2 Hz增量）；无拓扑图；CA3型递归联想网络（模式补全）；早期信号门控+全局抑制实现浓度不变性；感知层级（梨状低维类别→杏仁核中等→OFC高维个体化）；revision_count=1；置信度：高

**修订页面（2）**：
- `wiki/systems/amygdala.md` rev5 — updated=2026-07-26；revision_count 4→5；related 新增 olfactory-bulb、piriform-cortex；key_sources 新增 PMID:37620443、PMID:32278646；source_articles 新增 2026-07-26-olfactory-coding-smell-memory-limbic；连接节新增 olfactory-bulb（皮质内侧核直接接收嗅球输出，无视丘中继）和 piriform-cortex（梨状皮层→杏仁核投射，气味感知层级）；修订历史新增 rev5 条目
- `wiki/systems/entorhinal-cortex.md` rev2 — updated=2026-07-26；revision_count 1→2；related 新增 olfactory-bulb、piriform-cortex；key_sources 新增 PMID:32278646；source_articles 新增 2026-07-26-olfactory-coding-smell-memory-limbic；连接节新增 olfactory-bulb（嗅球→LEC→海马通路）和 piriform-cortex（梨状皮层→EC→海马三突触回路）；修订历史新增 rev2 条目

**矛盾登记（0）**：无新矛盾。OR假基因化率（~60%）与三色视觉获得的因果关系是相关而非矛盾，作为开放问题Q-or-pseudogene-loss登记。

**新增开放问题（7）**：
- Q-or-pseudogene-loss（中优先级）：人类约60% OR假基因化与三色视觉获得的因果关系？还是随机基因漂变？
- Q-or-human-odor-space（低优先级）：400种功能性人类OR能否真的编码"万亿种"气味，还是这一估计有重大方法论问题？
- Q-ob-human-organization（低优先级）：人类嗅球的不规则小球分布是否改变了"一受体一小球"规则的严格性？
- Q-ob-topography-logic（中优先级）：嗅球小球的拓扑图（化学感觉的几何邻近性）对应什么编码原则？是否有"化学空间-物理空间"映射的规律性？
- Q-piriform-topography（中优先级）：梨状皮层是否完全没有任何功能组织？还是有超出当前分辨率的微尺度拓扑结构？
- Q-piriform-human-subdivision（中优先级）：人类aPCX/pPCX的功能分工与啮齿类ANT/POST是否有可比性？
- Q-piriform-td-control（中优先级）：OFC和PFC对梨状皮层的自上而下控制如何通过学习和期望改变气味感知？

**图谱**：168 节点（+3：olfactory-receptor、olfactory-bulb、piriform-cortex），1026 边（+9：OR→OB机制性，OB→PCX机制性，OB→杏仁核supports，OB→内嗅皮层supports，PCX→杏仁核related，PCX→模式补全related，PCX→内嗅皮层supports，OR→转录组细胞类型related）

---

## 2026-07-25（文章 #93·单细胞RNA测序×神经元类型分子宇宙×转录组分类体系）

**源文章**：[[2026-07-25-scrna-seq-neural-cell-type-diversity]] —《神经元类型的分子宇宙：单细胞测序如何重绘大脑细胞地图》

**新建页面（2）**：
- `wiki/methods/single-cell-rna-seq.md`（新建）— scRNA-seq/snRNA-seq技术原理、10x液滴流程、全脑图谱主要发现；revision_count=1；置信度：高；相关：transcriptomic-cell-types、optogenetics、pv-interneurons
- `wiki/concepts/transcriptomic-cell-types.md`（新建）— 转录组细胞类型分类体系；133种→5322种聚类的核心发现；GABAergic保守/Glutamatergic区域特异性；转录因子组合编码；Patch-seq验证；revision_count=1；置信度：高

**修订页面（2）**：
- `wiki/neurons/pyramidal-neuron.md` rev2 — updated=2026-07-25；revision_count 1→2；新增"转录组亚型分类"节（兴奋性细胞区域特异性、L5 ET vs IT划分、人类特有亚型、物种同源性）；related/key_sources 更新
- `wiki/circuits/pv-interneurons.md` rev6 — updated=2026-07-25；revision_count 5→6；新增"转录组亚型注记"节（篮状/吊灯细胞分子标记差异；PV亚类跨区保守；人类PV特异性变化）；related 更新添加transcriptomic-cell-types、single-cell-rna-seq

**矛盾登记（0）**：无新矛盾。转录组类型数量（133 vs 5322）的差异是分辨率差异，非真实冲突；细胞"状态 vs 类型"问题作为开放问题Q-scrna-state-vs-type登记

**新增开放问题（2）**：
- Q-scrna-state-vs-type（中优先级）：scRNA-seq如何区分细胞的稳定类型身份和短暂活动状态？即早基因（FOS、ARC）表达如何影响类型分类？
- Q-scrna-resolution-functional（高优先级）：哪个层次的转录组分类（133种 vs 5322种）对应功能上真实的"回路计算单元"？
- Q-cell-type-human-cognitive（中优先级）：人类皮层特有的兴奋性神经元亚型（Hodge 2019）具体负责什么功能？与高级认知的关系？

**图谱**：165 节点（+2），1017 边（+8）。新增节点：single-cell-rna-seq、transcriptomic-cell-types。新增边：单细胞测序→转录组类型（supports），转录组类型→PV/SST/VIP中间神经元（related），转录组类型→锥体神经元（related），转录组类型→皮层正则微回路（supports），单细胞测序→光遗传学（prerequisite-for），转录组类型→关键期（related）

---

## 2026-07-24（文章 #92·杏仁核恐惧印迹×突触可塑性竞争写入×消退记忆=奖励神经元）

**源文章**：[[2026-07-24-amygdala-fear-engram-extinction-reward-neurons]] —《恐惧的印迹与奖励的入侵：杏仁核如何竞争选择恐惧记忆，又如何将消退交给奖励系统》

**新建页面（0）**：本次无新建页面，均为现有页面修订。

**修订页面（4）**：
- `wiki/concepts/fear-conditioning.md` rev3 — updated=2026-07-24；revision_count 2→3；related/source_articles 新增今日文章；key_sources 新增 PMID:34168140, PMID:22036561；当前理解节新增"突触可塑性竞争规则"段落（Jeong 2021, Nat Commun）：高 CREB→高兴奋性→低 LTP 阈值→优先入选印迹；证据表新增1行（PMID:34168140）；修订历史新增 rev3 条目
- `wiki/concepts/fear-extinction.md` rev4 — updated=2026-07-24；revision_count 3→4；related 新增 engram-cells, dopamine-reward-prediction-error；opens_questions 新增 Q-extinction-reward-overlap；key_sources 新增 PMID:31952856, PMID:38396226, PMID:25162525, PMID:29507292；当前理解节新增三段：①消退印迹=BLA奖励神经元（Zhang 2020），②恐惧/消退印迹是不同细胞群（Luft 2024），③情感价值可逆转（Redondo 2014）；证据表新增4行；连接节新增 engram-cells, dopamine-reward-prediction-error；修订历史新增 rev4 条目
- `wiki/systems/amygdala.md` rev4 — updated=2026-07-24；revision_count 3→4；key_sources 新增 PMID:34168140, PMID:31952856, PMID:38396226, PMID:25162525；LA描述更新（Jeong 2021竞争规则）；BA描述更新（消退=奖励神经元 Zhang 2020；独立印迹细胞群 Luft 2024）；证据表新增4行；engram-cells 连接注释更新；未解问题新增 Q-extinction-reward-overlap；修订历史新增 rev4 条目
- `wiki/concepts/engram-cells.md` rev6 — updated=2026-07-24；revision_count 5→6；related 新增 amygdala, fear-conditioning, fear-extinction；opens_questions 新增 Q-extinction-reward-overlap；key_sources 新增 PMID:34168140, PMID:31952856, PMID:25162525；竞争机制节新增3段（Jeong 2021 LA突触权重竞争规则、Zhang 2020 消退印迹=BLA奖励神经元、Redondo 2014 情感价值可逆转）；修订历史新增 rev6 条目

**矛盾登记（0）**：无新矛盾（消退印迹=奖励神经元结论仅有一组 Tonegawa 实验室数据，置信度标注为"需独立重复"；情感价值逆转与恐惧条件反射的原始痕迹保留之间的张力作为开放问题 Q-extinction-reward-overlap 处理）

**新增开放问题（1）**：
- Q-extinction-reward-overlap（高优先级）：BLA消退印迹细胞与奖励响应细胞的重叠率精确值及因果关系——阻断BLA奖励通路是否导致消退失败？奖励系统功能低下（如抑郁症中多巴胺系统损伤）是否导致消退能力下降，进而维持 PTSD 症状？

**图谱**：163 节点，1009 边（+3 边：fear-extinction→engram-cells supports，fear-extinction→dopamine-reward-prediction-error related，engram-cells→fear-extinction supports）

---

## 2026-07-23（文章 #91·UP/DOWN态机制·Layer 5循环兴奋×KNa终止×PFC选择性守门）

**源文章**：[[2026-07-23-cortical-up-down-state-pfc-gating-memory]] —《皮层的沉默与苏醒：UP/DOWN 态如何从细胞机制到系统层面编排睡眠中的记忆选择》

**新建页面（1）**：
- `wiki/concepts/up-down-state-mechanism.md`（UP/DOWN态机制·rev1）🟢 established·high confidence — Layer 5 锥体细胞侧支循环兴奋（AMPA+NMDA）是 UP 态启动引擎；UP 态特征（~−65 mV，0.8–1.5 s，密集放电）；UP 态终止三机制：①KNa 通道（KCNT1/KCNT2，[Na⁺] ~10→15–20 mM）为主要自动计时器，②短时程突触抑郁（RRP 耗竭），③SST+ Martinotti 细胞延迟 GABA_A 树突抑制；DOWN 态深度（~−90 mV）由 GABA_B + KNa 持续激活 + TASK 漏电通道维持；离体皮层切片（无视丘）自发 SO 证明皮层回路内在充分性（Sanchez-Vives 2000，PMID:11017176）；视丘损毁后体内 SO 存在证明自主性（Steriade 1993，PMID:8340807）；关键证据表 6 条；连接 cortical-slow-oscillation, sleep-spindles, so-spindle-swr-coupling, action-potential, synaptic-transmission, pv-interneurons, shy-hypothesis；开放问题 Q-updown-termination-weight（中优先级）/Q-updown-human-mechanism（低优先级）；key_sources: PMID:8340806（PMC6576541）, PMID:8340807（PMC6576520）, PMID:11017176, PMID:26834569（PMC4625581）

**修订页面（2）**：
- `wiki/concepts/cortical-slow-oscillation.md` rev4 — updated=2026-07-23；revision_count 3→4；related 新增 up-down-state-mechanism；source_articles 新增 2026-07-23-cortical-up-down-state-pfc-gating-memory；key_sources 新增 PMID:8340806, PMID:8340807, PMID:26834569；UP态机制章节扩展（Layer 5 循环兴奋机制、睡眠 ACh 下降使静息电位趋近阈值）；DOWN态机制章节扩展（KNa 主机制 + 突触抑郁 + SST+ 延迟抑制三机制详细描述）；关键证据表新增4行（UP/DOWN参数、视丘损毁、离体切片、KNa/STP/SST综述）；连接节新增 up-down-state-mechanism
- `wiki/concepts/so-spindle-swr-coupling.md` rev2 — updated=2026-07-23；revision_count 1→2；related 新增 up-down-state-mechanism；opens_questions 新增 Q-pfc-veto-mechanism, Q-pfc-veto-human；source_articles 新增 2026-07-23-cortical-up-down-state-pfc-gating-memory；key_sources 新增 PMID:26389842, PMID:37429914, PMID:38834064；正文新增 Staresina 2015 人类颅内验证段落、Staresina 2023 MUA 阶梯递增段落、Shin & Jadhav 2024 PFC 选择性守门段落（重要新发现）；关键证据表新增3行；连接节新增 up-down-state-mechanism；未解问题新增 Q-pfc-veto-mechanism/Q-pfc-veto-human 详细描述

**矛盾登记（0）**：无新矛盾（PFC 守门机制的物种差异、UP 态终止权重的不确定性均作为开放问题处理）

**新增开放问题（4）**：
- Q-updown-termination-weight（中优先级）：KNa 积累、突触抑郁和 SST 延迟抑制在 UP 态终止中的相对权重是否在不同皮层区域（前额 vs 初级感觉皮层）和不同物种中显著不同？能否通过双光子 Na⁺ 成像直接测量？
- Q-updown-human-mechanism（低优先级）：人类皮层（厚达 2.5–5 mm，更长层内回路）的 UP 态终止机制是否与大鼠/猫有定量差异？目前缺乏人类体内单细胞记录。
- Q-pfc-veto-mechanism（高优先级）：PFC 独立涟漣如何"选择"哪些海马细胞集成体需要抑制？上游选择信号（PFC 记忆印记？强化学习输出？）是什么？
- Q-pfc-veto-human（中优先级）：Shin & Jadhav 2024 的 PFC 守门机制在人类颅内记录中是否可复现？PFC 涟漣的抑制功能是否在 PTSD/AD 等记忆障碍中受损？

**图谱**：163 节点，1006 边（+1 节点 up-down-state-mechanism，+8 边 up-down-state-mechanism→各关联节点）

---

## 2026-07-22（文章 #90·α振荡·视丘节拍器·感知闸门·α-γ PAC工作记忆机制）

**源文章**：[[2026-07-22-alpha-oscillations-attention-wm]] —《α振荡：视丘节拍器、感知闸门与人类工作记忆的抑制性容量机制》

**新建页面（1）**：
- `wiki/concepts/alpha-oscillations.md`（α振荡·rev1）🟢 established·high confidence — α振荡（8–12 Hz）的视丘-皮层双源生成机制（TRN→TC→皮层→TRN闭合环路，T型Ca²⁺通道驱动；枕核/LP复合体"α广播器"）；皮层L5层流证据（Bollimunta 2008 清醒猕猴Granger因果，L5主导低级视觉区α；高级联合区L2/3方向相反）；抑制-时序假说（Klimesch 2007：ERS=主动压制，非闲置）；脉冲式门控（Mathewson 2011：α创造交替开/关微态）；差异化α拓扑图（Worden 2000/Foxe 2011：被忽略位置α升高，跨感觉系统一致）；α影响感知决策标准c非灵敏度d'（Samaha 2020）；Clayton 2018五功能框架（抑制器/促进者/时序绑定/预测者/γ协调者）；α-γ PAC三阶段WM机制（Roux 2014双代码+Wianda 2019编码/维持/提取相转换）；rTMS因果初步证据（Yuan 2025，低-中置信度）；关键证据表8条；12个关联；开放问题Q-theta-primate（继承）、Q-alpha-thalamic-vs-cortical（新）、Q-alpha-c-vs-dprime（新）

**修订页面（3）**：
- `wiki/concepts/theta-gamma-coupling.md` rev2 — updated=2026-07-22，revision_count 1→2；frontmatter related 新增 alpha-oscillations；key_sources 新增 PMID:24268290（Roux 2014）、PMID:30887701（Wianda 2019）；Q-theta-primate 更新为"α-γ证据积累中：Roux 2014双代码模型+Wianda 2019三阶段变化，但因果性tACS/rTMS证据仍弱，问题仍open"；source_articles 新增 2026-07-22；修订历史追加一行
- `wiki/concepts/working-memory.md` rev9 — updated=2026-07-22，revision_count 8→9；frontmatter related 新增 alpha-oscillations；opens_questions 新增 Q-theta-primate；source_articles 新增 2026-07-22；key_sources 新增 PMID:24268290、PMID:30887701；正文新增"α振荡在工作记忆中的角色：α-γ双代码补充"节（三阶段WM α-γ PAC变化+α-γ vs θ-γ分工假说）；修订历史追加一行
- `wiki/systems/thalamus.md` rev4 — updated=2026-07-22，revision_count 3→4；frontmatter related 新增 alpha-oscillations；source_articles 新增 2026-07-22；key_sources 新增 PMID:31972202（Bourgeois 2020）；连接节新增 [[alpha-oscillations]] — 枕核/LP通过TRN-TC回路产生清醒α振荡，同步调制多个皮层区域α功率（广播式α门控）；修订历史追加一行

**矛盾登记（0）**：无新矛盾（α-γ PAC vs θ-γ CFC争议作为开放问题Q-theta-primate处理；α影响决策标准c vs d'的方法论张力登记为Q-alpha-c-vs-dprime）

**新增开放问题（2）**：
- Q-alpha-thalamic-vs-cortical（中优先级）：清醒状态下，枕核/TRN来源的α与皮层L5产生的α是同一机制的不同层级还是两个独立振荡器？二者如何相互影响？
- Q-alpha-c-vs-dprime（中优先级）：α振荡究竟影响感知决策标准（c）还是真实感觉灵敏度（d'）？两种研究结论的矛盾来自方法学差异还是真实分歧？

**Q-theta-primate 证据更新（2026-07-22）**：
- 新增α-γ PAC证据：Roux & Uhlhaas 2014（PMID:24268290）提出α-γ vs θ-γ双代码模型；Wianda & Ross 2019（PMID:30887701）报告WM三阶段中额颞α-γ PAC系统变化；Yuan 2025（PMID:40500659）rTMS增强α-γ PAC改善MCI工作记忆初步因果证据
- 状态更新：问题仍open，但α-γ证据在积累；θ-γ vs α-γ双代码竞争假说进入关注列表

**图谱**：162 节点，998 边（+1 节点 alpha-oscillations，+9 边 alpha-oscillations→各wiki节点，+1边 theta-gamma-coupling→alpha-oscillations）

---

## 2026-07-21（文章 #89·海马的节律钟表·θ-γ跨频率耦合·容量分格模型·Colgin双通道路由）

**源文章**：[[2026-07-21-theta-gamma-coupling-working-memory]] —《海马的节律钟表：θ-γ跨频率耦合如何量化工作记忆容量》

**新建页面（1）**：
- `wiki/concepts/theta-gamma-coupling.md`（θ-γ跨频率耦合·rev1）🔵 mainstream·medium confidence — Lisman-Idiart 1995 容量分格模型（θ/γ 比率 ≈ 4–6 ≈ WM 容量）；活动依赖 ADP 维持记忆分格；Colgin 2009 双通道路由（慢γ-CA3/快γ-MEC 时分多路复用）；Axmacher 2010 人类颅内 PAC×WM 负荷证据；Wolinski 2018 θ 频率→容量定量预测；Huang 2026 导航序列规划扩展；关键证据表 6 条；连接 theta-oscillations, gamma-oscillations, working-memory, place-cells, theta-phase-precession, sharp-wave-ripples, hippocampal-circuit, temporal-coding-hierarchy, pv-interneurons；开放问题 Q-tgc-01/02/03

**修订页面（3）**：
- `wiki/concepts/theta-oscillations.md` rev4 — 扩展 θ/γ 嵌套章节：Lisman-Idiart 1995 + Lisman-Jensen 2013 容量修订（4-6→4±1）、Colgin 2009 双通道路由（慢γ-CA3/快γ-MEC）、Axmacher 2010 人类 PAC 证据；related 新增 theta-gamma-coupling, working-memory, gamma-oscillations；source_articles 新增 2026-07-21-theta-gamma-coupling-working-memory；key_sources 新增 PMID:7878473, PMID:23522038, PMID:19924214
- `wiki/concepts/gamma-oscillations.md` rev5 — Q-gamma-capacity 从 opens_questions 移入 partially_resolved_questions（三层证据：Lisman-Idiart 1995 + Axmacher 2010 + Wolinski 2018；剩余争议：因果弱/灵长类θ不规则）；Q-gamma-capacity 正文标注部分解答；source_articles 新增 2026-07-21-theta-gamma-coupling-working-memory
- `wiki/concepts/working-memory.md` rev8 — Q-wm-capacity-mechanism 从 opens_questions 移入 partially_resolved_questions；θ-γ嵌套为4±1容量节律机制；连接新增 theta-gamma-coupling；related 新增 theta-gamma-coupling；key_sources 新增 PMID:7878473, PMID:23522038, PMID:20133762；source_articles 新增 2026-07-21-theta-gamma-coupling-working-memory

**矛盾登记（1）**：
- 啮齿类 vs 灵长类 θ 节律性张力：Colgin 2009 慢/快 γ 路由在大鼠中建立，但人类 θ 节律性显著弱于大鼠，人类直接颅内验证缺失。登记为 Q-tgc-02，页面 confidence 设为 medium。

**新增开放问题（3）**：
- Q-tgc-01（高优先级）：tACS 调制 θ 频率的 WM 行为效果是否与模型预测方向一致且效应量显著？因果性操控能否改变工作记忆容量？
- Q-tgc-02（中优先级）：Colgin 2009 慢γ/快γ 双通道路由在人类海马和前额叶中是否成立？人类颅内数据是否能重复相位分离？
- Q-tgc-03（低优先级）：Köster 2024 θ 早相位=内部预期、晚相位=预测误差的预测编码 θ-γ 框架是否有直接实验证据？

**部分解答问题（2）**：
- Q-gamma-capacity（来自 gamma-oscillations）：三层证据（Lisman-Idiart 1995 + Axmacher 2010 + Wolinski 2018）支持 θ-γ 嵌套作为 WM ~4 项容量的节律基础；剩余争议：tACS 因果证据弱，灵长类 θ 不规则
- Q-wm-capacity-mechanism（来自 working-memory）：θ-γ 嵌套约束与吸引子竞争同时起作用；三层证据支持 θ-γ 贡献；因果性仍弱

**图谱**：161 节点，989 边（+1 节点 theta-gamma-coupling，+12 边）

---

## 2026-07-20（文章 #88·篮状细胞打出节拍·ING/PING 双重机制·精神分裂症 PV-GAD67-γ 级联）

**源文章**：[[2026-07-20-gamma-oscillations-ping-ing-mechanism]] —《篮状细胞打出节拍：γ 振荡的双重生成机制与精神分裂症的细胞之谜》

**新建页面（1）**：
- `wiki/diseases/schizophrenia.md`（精神分裂症·rev1）🔵 mainstream — PV-GAD67-γ 轴完整分子-回路-认知因果链（NMDA低活→GAD67↓→GABA↓→PING崩溃→γ↓→WM缺陷）；多巴胺双轴（D2过度激活阳性症状/D1不足阴性认知症状）；高度多基因遗传（C4A突触过度剪枝假说）；连接 pv-interneurons, gamma-oscillations, working-memory, nmda-receptor, dopamine-reward-prediction-error, ei-balance；关键证据：GAD67 mRNA多实验室复现（PMID:22218597）、MEG/EEG γ功率缺失（PMID:25863358）、PV-NR2A优先损伤机制（PMID:22355184）

**修订页面（2）**：
- `wiki/concepts/gamma-oscillations.md` rev4 — **重大扩展**：新增"生成机制（ING vs PING）——分子到回路"完整章节；GABA-A τ_decay 作为频率时钟（Keeley 2017 计算模型：τ≈5ms→70-80 Hz，τ≈15ms→30-40 Hz）；Sohal 2009/Cardin 2009 光遗传学因果证据入证据表；Ainsworth 2011 双层 γ 生成器（L2/3 ING 慢γ/L4 PING 快γ）；Viriyopase 2016 ING-PING 竞争（高频者主导）；Antonoudiou 2020 SST+ 贡献（PV+→慢γ，SST+激活→快γ~80Hz）；精神分裂症级联 Gonzalez-Burgos 2012 细节；related 新增 schizophrenia, sst-interneurons, cortical-layers；key_sources 新增 8 个 PMID；新开放问题 Q-gamma-ping-ling-01、Q-gamma-sst-pv
- `wiki/circuits/pv-interneurons.md` rev5 — 新增"γ 生成机制的深化（2026-07-20 更新）"节：Sohal 2009 ChR2/eNpHR 因果证明（光激活→γ↑；光抑制→γ↓+信噪比↓）；Cardin 2009 40 Hz FS 驱动→选择性 γ+感觉相位门控；GABA-A τ_decay 频率机制；Gonzalez-Burgos & Lewis 2012 NMDA↓→GAD67↓→GABA↓→IPSP↓→PING崩溃完整级联；证据表新增 3 行（Sohal 2009, Cardin 2009, Gonzalez-Burgos 2012）；key_sources 新增 4 个 PMID；new opens_questions 细化

**矛盾登记（0）**：无新矛盾

**新增开放问题（3）**：
- Q-gamma-ping-ling-01（高优先级）：PING 中的 E→I 兴奋延迟如何与 GABA-A τ_decay 精确配合以锁定 γ 频率？计算模型预测与体内测量的差距？
- Q-gamma-sst-pv（中优先级）：SST+ 细胞与 PV+ 细胞在同一皮层回路中如何分工生成慢γ 和快γ？两者之间是否存在相互调控？
- Q-sz-dopamine-gaba-interface（高优先级）：精神分裂症中多巴胺异常（D2 过度激活）如何与 PV-GABA 损伤界面互动？是并行病理还是存在上下游因果关系？

**图谱**：160 节点，977 边（+1 节点 schizophrenia，+10 边）

---

## 2026-07-19（文章 #87·β振荡的三副面孔·统一框架·课程脊柱 2 × 课程脊柱 5）

**源文章**：[[2026-07-19-beta-oscillations-cortical-prediction]] —《β振荡的三副面孔：运动刹车、感知反馈与记忆守护》

**新建页面（0）**：无新建页面（主题已有 rev1 骨架）

**修订页面（3）**：
- `wiki/concepts/beta-oscillations.md` rev2 — **重大修订**：confidence medium→high；扩展统一框架（运动/感觉皮层层级/工作记忆/帕金森四系统）；Bastos 2015 ×2（28对视觉区域γ前向/β后向 + DCM V1-V4层级）、Lundqvist 2016 γ/β爆发双轨、Spitzer 2017 内容特异性β、Bastos 2018 L5/6许可窗口；related 新增 cortical-canonical-microcircuit, predictive-coding, cortical-layers, pv-interneurons, persistent-activity；key_sources 新增 6 个 PMID；opens_questions 新增 Q-beta-01至Q-beta-04
- `wiki/concepts/working-memory.md` rev7 — 扩展"主动抑制"为β爆发默认背景态+L5/6→L2/3许可窗口+内容特异性β再激活；关键证据表新增2行（Bastos 2018、Spitzer 2017）；连接新增 beta-oscillations；key_sources 新增 PMID:29339471, PMID:28785729
- `wiki/theories/predictive-coding.md` rev8 — 关键证据表新增2行（Bastos 2015 28对区域、Bastos 2018前额叶层流）；连接新增 beta-oscillations；related/key_sources 更新

**矛盾登记（0）**：无新矛盾

**新增开放问题（4）**：Q-beta-01（高）至Q-beta-04（低）

**已解答**：Q-ccm-03 → **部分解答**（Bastos 2018 将β/γ频率层级规律扩展至前额叶）

**图谱**：159 节点，940 边（+0 节点，+7 边）

---

## 2026-07-18（文章 #86·皮层规范微回路·预测编码解剖实现·课程脊柱 2）

**源文章**：[[2026-07-18-cortical-canonical-microcircuit]] —《大脑皮层的规范微回路：六层结构如何让感知成为主动推断》

**新建页面（2）**：
- `circuits/cortical-canonical-microcircuit.md`（规范微回路·新皮层）🟢 established — Douglas & Martin 2004 循环兴奋 4-7×丘脑输入；Harris & Shepherd 2015 串联同源性（serial homology）；Bastos 2012 预测编码层级对应（L2/3=误差单元γ，L5/6=预测单元β）；Larkum 2013 L5 顶端钙爆发 AND 门逻辑；Bastos 2015 28 对视觉区域 γ/β 频率验证；VIP+→SST+去抑制注意门控；连接 cortical-layers, predictive-coding, thalamocortical-circuit, pv-interneurons, sst-interneurons, vip-interneurons, gamma-oscillations, beta-oscillations, attractor-network
- `concepts/cortical-layers.md`（皮层分层结构·六层）🟢 established — L1–L6 各层细胞类型、输入/输出投射、振荡特征；前馈/反馈层级不对称（前馈→L4驱动型，反馈→L1/2/3调制型绕过L4）；L4棘突星形细胞、L5厚毛绒锥体细胞两极整合、L6 CT细胞丘脑门控；连接 cortical-canonical-microcircuit, thalamocortical-circuit, pv/sst/vip-interneurons, gamma/beta-oscillations, predictive-coding

**修订页面（2）**：
- `theories/predictive-coding.md` rev7 — related 新增 cortical-canonical-microcircuit、cortical-layers；connections 段新增规范微回路作为预测编码解剖实现的两条链接；修订历史新增一行
- `circuits/thalamocortical-circuit.md` rev3 — 新增"前馈/反馈的层级解剖特异性"节（丘脑→L4驱动型、L6 CT→丘脑调制型、高级L5/6→低级L1/2/3反馈绕过L4的层级对应表）；related 新增 cortical-canonical-microcircuit、cortical-layers；connections 段新增两条链接；修订历史新增一行

**矛盾登记（0）**：无新矛盾

**新增开放问题（4）**：
- Q-ccm-01（高优先级）：L2/3 误差单元和 L5/6 预测单元能否在同一体内实验中被直接、同时区分？（预测编码最核心的实验空白）
- Q-ccm-02（高优先级）：L5 顶端钙爆发在行为动物注意任务中的触发频率和触发条件是什么？VIP+去抑制的细胞级注意证据？
- Q-ccm-03（中优先级）：β/γ 频率规律是否普遍适用于非视觉皮层（前额叶、海马、运动皮层）？
- Q-ccm-04（中优先级）：无颗粒皮层（前额叶）的规范微回路是什么样的"变体"——L2/3 是否兼并了 L4 功能？

**新增悬空引用（需补）**：
- `disinhibitory-circuit`（VIP→SST→锥体细胞的去抑制回路，需建独立页面）
- `pv-interneurons`（PV+ 快速放电细胞专页，需建独立页面）
- `sst-interneurons`（SST+ 马氏细胞专页，需建独立页面）
- `vip-interneurons`（VIP+ 双极细胞专页，需建独立页面）

**图谱**：159 节点，933 边（+2 节点 cortical-canonical-microcircuit/cortical-layers，+21 边）

---

## 2026-07-16（文章 #84·海马回放·经验回放·课程脊柱 12 第五篇）

**源文章**：[[2026-07-16-hippocampal-replay-experience-replay]] —《记忆的时光机：海马回放如何重演昨天以学习明天》

**新建页面（1）**：
- `concepts/hippocampal-replay.md`（海马回放）🟢 established — Yang 2024 三阶段结构（θ 编码→清醒 SWR 选择→睡眠 SWR 固化）；Mattar-Daw 2018 Need×Gain 规范化理论；Foster 2006/Diba 2007 前向/反向回放；Igata 2021 未经历路径的回放；连接 sharp-wave-ripples, place-cells, complementary-learning-systems, td-learning, experience-replay-buffer

**修订页面（2）**：
- `concepts/complementary-learning-systems.md` rev3 — 新增三阶段回放结构（Yang 2024）；新增 Mattar-Daw Need×Gain 理论；新增 van de Ven 2020 生成回放；新增 hippocampal-replay / experience-replay-buffer 关联；key_sources +4
- `concepts/sharp-wave-ripples.md` rev8 — 新增 Mattar-Daw Need×Gain 规范化理论（前向/反向方向由 Need×Gain 决定）；source_articles + 2026-07-16；修订历史新增一行

**矛盾登记（0）**：无新矛盾

**新增开放问题**：
- `Q-cls-generative-replay-oneshotlearning`：人工海马（VAE）如何支持 one-shot 学习同时避免自身灾难性遗忘？
- `Q-replay-planning-mechanism`：海马"从未经历过的路径"的内部生成机制——CA3 循环动力学泛化还是需要前额叶输入？

**新增悬空引用（需补）**：
- `experience-replay-buffer`（AI 侧经验回放缓冲区，需建独立页面）
- `temporal-credit-assignment`（时间信用分配，需建独立页面）
- `knowledge-distillation`（知识蒸馏，可能并入 complementary-learning-systems 或建独立页面）

**图谱**：156 节点，924 边（+2 节点，+12 边）

---

## 2026-07-15（文章 #83·Transformer 自注意力·大脑注意回路类比·课程脊柱 12 第四篇）

**源文章**：[[2026-07-15-brain-attention-transformer-qkv]] —《同一个算法，两种实现：大脑注意回路与 Transformer 自注意力的深层对话》

**新建页面（1 页）**：
- `concepts/transformer-self-attention.md`：Transformer Q/K/V机制完整公式（Vaswani 2017）；现代Hopfield网络等价（Ramsauer 2020，arXiv:2008.02217）；Q/K/V↔FEF-Query/感觉皮层-Key-Value类比表（Knudsen 2007组件框架）；6大断裂点（连续时间动力学、局部赫布vs全局反向传播、眼动-注意耦合、多头生物对应、softmax vs除法归一化、循环连接）；Ellwood 2024局部赫布实现（NMDA Ca⁴抑制、可逆短期增强）；皮质-丘脑多头假说（arXiv:2504.06354，⚠️待同行评审）；established/high

**修订页面（5 页）**：
- `concepts/gain-control.md`（rev3→rev4）：新增 Reynolds & Heeger 2009 规范化注意力模型完整公式（R=(AS)^n/(σ^n+Σw_iA_iS_i^n)）；说明除法归一化 vs Transformer softmax 关键差异（注意场宽度→对比度增益/响应增益）；key_sources 新增 PMID:19186161；source_articles 新增 2026-07-15 文章
- `concepts/dorsal-attention-network.md`（rev1→rev2）：新增 "DAN 与 Transformer Q/K/V 的类比" 一节（Knudsen 2007 四组件框架）；related 新增 transformer-self-attention, attractor-network；key_sources 新增 PMID:17417935, arXiv:2008.02217, DOI:10.1371/journal.pcbi.1011843；source_articles 新增 2026-07-15 文章
- `concepts/biased-competition.md`（rev1→rev2）：新增 "与 Transformer softmax 竞争的类比" 一节；softmax 指数归一化 vs 除法归一化差异；related 新增 transformer-self-attention, attractor-network, gain-control；key_sources 新增 PMID:4023713, PMID:19186161
- `concepts/attractor-network.md`（rev1→rev2）：扩展现代 Hopfield 网络更新规则（β参数与温度关系）；新增 Ellwood 2024 局部赫布实现；related 新增 transformer-self-attention, biased-competition；key_sources 新增 arXiv:2008.02217, DOI:10.1371/journal.pcbi.1011843

**图谱更新**：新增 1 节点（transformer-self-attention）、14 条边；总计 **154 节点，912 边**
> 注：节点数从 151 跃至 154（含本日 +1），因先前两个 run 已各自新增节点（free-energy-principle, variational-autoencoder, ventral-visual-stream 等），CHANGELOG 记录的图谱数字已追上实际

**新增悬空引用**：无

**新登记矛盾**：无

**新增未解问题（2 个）**：
- Q-attn-bio-01（高优先级）：Ellwood 2024 "匹配-控制"原理是否有体内电生理直接验证？NMDA 短期增强时间常数是否支持注意力动力学？
- Q-attn-bio-02（中优先级）：大脑中"多头注意力"的生物对应是什么——不同皮层区域（空间并行）、不同振荡频率（时间序列），还是不同细胞类型？

---

## 2026-07-14（文章 #82·CNN–视觉皮层类比·课程脊柱 3 × 课程脊柱 12 第三篇）

**源文章**：[[2026-07-14-cnn-visual-cortex-hierarchy]] —《镜中影像：卷积神经网络与灵长类视觉皮层的层级对应，以及这面镜子在哪里碎裂》

**新建页面（2 页）**：
- `concepts/ventral-visual-stream.md`：腹侧视觉流（V1→V2→V4→IT）；"解开纠缠"计算任务；前馈核心+循环调制；IT线性可分性；established/high
- `concepts/cnn-visual-cortex-analogy.md`：目标驱动CNN与视觉皮层类比；性能-预测力相关（r=0.78）；~50%可解释方差；三个崩溃裂缝（循环/形状偏见/对抗样本）；mainstream/high

**修订页面（1 页）**：
- `systems/v1-primary-visual-cortex.md`（rev4→rev5）：新增"CNN第一层的V1类比"小节（Gabor型卷积核=V1简单细胞感受野；层级对应V4→IT由Yamins 2014证明）；related 新增 ventral-visual-stream, cnn-visual-cortex-analogy；key_sources 新增 PMID:24812127, PMCID:PMC4060707；source_articles 新增 2026-07-14 文章

**图谱更新**：新增 2 节点（ventral-visual-stream, cnn-visual-cortex-analogy）、7 条边；总计 **151 节点，892 边**

**新增悬空引用（2 个）**：
- `inferior-temporal-cortex`（IT 皮层专页，被 ventral-visual-stream 和 cnn-visual-cortex-analogy 引用）
- `object-recognition`（物体识别专页，被 ventral-visual-stream 引用）

**新登记矛盾**：无

**新增未解问题（3 个）**：
- Q-cnn-vc-01（高优先级）：循环连接在困难视觉任务中具体计算了什么？
- Q-cnn-vc-02（高优先级）：大脑的"监督信号"是什么？（解释为何监督CNN更接近IT）
- Q-cnn-vc-03（中优先级）：IT 形状偏见的皮层起源是V4还是IT才完成的？

---

## 2026-07-13（文章 #81·预测编码·自由能原理·VAE·课程脊柱 12 第二篇）

**源文章**：[[2026-07-13-predictive-coding-free-energy-vae]] —《大脑的预言机：从 Rao-Ballard 预测编码到自由能原理与变分自编码器》

**新建页面（2 页）**：
- `theories/free-energy-principle.md`：弗里斯顿自由能原理；变分推断统一感知-行动-学习；ELBO 等价；主动推断；emerging/medium
- `concepts/variational-autoencoder.md`：VAE（编码器+解码器+ELBO）；与预测编码的数学等价；ELBO 最大化=自由能最小化；工程实践广泛验证；与 TD 学习/CLS 的关联；established/high

**修订页面（1 页）**：
- `theories/predictive-coding.md`（rev5→rev6）：关键证据表新增 Whittington & Bogacz 2017（PC≈反向传播）、Richter 2018（腹侧流期望抑制）、Solomon 2021（批评性证据）、VAE 数学等价；dimensions 新增 AI；related 新增 free-energy-principle、variational-autoencoder；未解问题新增 Q-pc-06（Solomon 质疑）、Q-pc-07（VAE 等价性）；key_sources 新增 3 个；source_articles 新增 2026-07-13 文章

**图谱更新**：新增 2 节点（free-energy-principle, variational-autoencoder）、7 条边；总计 **151 节点，892 边**

**新增悬空引用**：active-inference（主动推断，尚无独立 wiki 页）

**新登记矛盾**：无（Solomon 2021 对预测编码证据质量的批评已记录在 predictive-coding.md 证据表中，整体降低置信度但不构成新 contested_claim——原 medium 置信度已反映不确定性）

**新增未解问题（4 个）**：
- Q-pc-06（高优先级）：在严格排除神经适应后，视觉皮层是否存在真正的预期依赖性预测误差信号？（来自 Solomon 2021 批评）
- Q-pc-07（中优先级）：VAE 编码器与皮层前馈通路的对应是否超出数学类比，存在真实计算等价性？
- Q-fep-01（高优先级）：自由能原理给出哪些具体可证伪的实验预测？
- Q-fep-02（中优先级）：自由能最小化在微观/介观/宏观三个尺度的分子基础各是什么？

---

## 2026-07-12（文章 #80·多巴胺 TD 学习与深度 RL 比较·人脑 vs AI 强化学习·课程脊柱 12 首篇）

**源文章**：[[2026-07-12-dopamine-td-learning-brain-ai]] —《奖励信号的双重发现：多巴胺时序差分学习与深度强化学习的平行演化与根本分歧》

**新建页面（4 页）**：
- `theories/td-learning.md`：时序差分学习理论；δ(t) = r(t) + γV(t+1) − V(t)；DA 神经元的生物实现（Schultz 1997）；信念态 TD（Starkweather 2021）；分布式 TD（Dabney 2020）；与预测编码同构；established/high
- `concepts/actor-critic-brain.md`：演员-评论家架构在基底节的实现；VTA/SNc=δ信号、NAc=Critic、背侧纹状体 D1-MSN=Go/D2-MSN=No-Go；DA 双读数设计；mainstream/medium
- `concepts/distributional-rl-dopamine.md`：分布式 DA 编码；不同 VTA DA 神经元的不对称 RPE 缩放（Dabney 2020）；群体追踪奖励概率分布；与 AI 分布式 RL（C51/QR-DQN）对应；emerging/medium
- `concepts/model-based-model-free.md`：MB-MF 双系统；DMS（目标导向/MB）vs DLS（习惯/MF）；结果贬值测试；应激→MB→MF 切换；OCD/成瘾/抑郁的计算解释；mainstream/medium

**修订页面（3 页）**：
- `concepts/dopamine-reward-prediction-error.md`（rev4→rev5）：新增"分布式 DA 编码"（Dabney 2020）和"Actor-Critic 架构"（Joel 2002）两小节；related 新增 td-learning/actor-critic-brain/distributional-rl-dopamine/model-based-model-free/complementary-learning-systems；key_sources 新增3个
- `concepts/complementary-learning-systems.md`（rev1→rev2）：新增 Kumaran-Hassabis-McClelland 2016 更新（情景记忆→行动选择接口）和 Botvinick 2019 Meta-RL 假说（DA-TD 训练 PFC-RNN→快速推断系统）；related 新增 td-learning/dopamine-reward-prediction-error/model-based-model-free

**图谱更新**：新增 4 节点（td-learning, actor-critic-brain, distributional-rl-dopamine, model-based-model-free）、12 条边；总计 **149 节点，885 边**

**新登记矛盾**：无（Active Inference vs RL 框架的潜在分歧以"开放问题"处理，证据不足以登记为 contested_claim）

**新增未解问题（4 个）**：
- Q-td-biological-discount-factor（中优先级）：大脑的折扣因子 γ 有多动态？不同脑区折扣偏好是否不同？
- Q-td-credit-assignment-long-horizon（高优先级）：数小时跨度延迟奖励如何被 TD 系统正确分配信用？SWR 重放是否承担长时信用分配？
- Q-distributional-da-behavior（高优先级）：分布式 DA 编码在行为层面有何可观测功能后果？乐观/悲观 DA 亚群与风险偏好的关系？
- Q-mb-mf-competition（中优先级）：DMS 和 DLS 如何在网络层面竞争控制行为输出？"仲裁者"是什么？

---

## 2026-07-11（文章 #79·LC多巴胺·海马记忆标记·LC-TH⁺为dCA1 DA主要来源；行为标记；记忆联结；VTA-SWR互补）

**源文章**：[[2026-07-11-dopamine-lc-hippocampus-memory-tagging]] —《当蓝斑充当"新奇探测器"：LC多巴胺如何把值得记住的瞬间标记进长期记忆》

**新建页面（1 页）**：
- `concepts/lc-hippocampus-dopamine.md`：蓝斑-海马多巴胺系统；LC TH⁺ 末梢（非VTA）是海马 dCA1 DA 的主要来源（Takeuchi 2016）；D1/D5 依赖"记忆持续性"（非编码）——D1 阻断致 24h LTM 缺陷但不影响 STM（Bethus 2010）；行为标记（Moncada & Viola 2007）：新颖性→LC 相位爆发→dCA1 DA→D1/D5→PRPs→突触标记捕获→STM→LTM；记忆联结（Matos 2022）：~6h 时间窗，LC→dCA1 D1/D5 依赖，CA1 ensemble 重叠；VTA 互补角色：GRAB-DA 验证（Kang 2024），VTA 调制 SWR 空间重播（Igata 2024）；与 GC-NE 应激记忆系统互补（emerging, confidence:medium）

**修订页面（5 页）**：
- `concepts/synaptic-tagging-capture.md`（rev1→rev2）：关键证据表新增3行（Moncada 2007 行为标记、Bethus 2010 D1/D5 持续性、Takeuchi 2016 LC 主要来源）；连接节新增 lc-hippocampus-dopamine；key_sources 新增 PMID:17626208、PMID:27602521、PMID:20130171、PMID:21170088；source_articles 新增 2026-07-11
- `concepts/dopamine-reward-prediction-error.md`（rev3→rev4）：新增"海马多巴胺来源争议：LC 主导，VTA 辅助"段落（LC vs VTA 解剖证据、GRAB-DA 直接测量、D1/D5 与 β-AR 功能分离）；Q-da-hippocampus-source 标记为"部分解答（2026-07-11）"；连接节新增 lc-hippocampus-dopamine；key_sources 新增3个；source_articles 新增
- `concepts/norepinephrine-locus-coeruleus.md`（rev2→rev3）：新增"LC 多巴胺共释放与海马记忆标记"段落（DA/NE 平行通道独立功能、新奇检测、行为标记、记忆联结）；关键证据表新增4行；连接节新增 lc-hippocampus-dopamine、synaptic-tagging-capture；未解问题新增 Q-lc-da-subtype；key_sources 新增 PMID:27602521、PMID:38592773、PMID:36041433；source_articles 新增
- `concepts/sharp-wave-ripples.md`（rev6→rev7）：关键证据表新增1行（Igata 2024 VTA 调制 SWR 空间重播）；Q-swr-tagging-mechanism 部分进展注释；key_sources 新增 PMID:38895442；source_articles 新增
- `concepts/memory-consolidation.md`（rev8→rev9）：连接节新增 lc-hippocampus-dopamine 和 synaptic-tagging-capture；related/source_articles 相应更新

**图谱更新**：新增 1 节点（lc-hippocampus-dopamine）、12 条边；总计 145 节点，873 边

**新登记矛盾**：无

**新增未解问题（2 个）**：
- Q-lc-da-subtype（高优先级）：LC 神经元中哪些亚型共释放多巴胺？分子标记（TH 高表达但 DBH 低？）？单细胞测序候选亚群？
- Q-lc-da-physiological-quantity（高优先级）：生理条件下 LC 激活（单次新颖事件）释放到 dCA1 的 DA 量是否足以有效激活 D1/D5 受体？GRAB-DA 峰值与 D1 Kd 比较？

**Q-da-hippocampus-source 部分解答（2026-07-11）**：Takeuchi 2016（PMID:27602521）解剖追踪+VTA 化学失活表明 LC TH⁺ 末梢是 dCA1 DA 主要来源（非 VTA）；Kang 2024（PMID:38592773）GRAB-DA 直接测量确认痕迹恐惧条件化中 LC 激活引发海马 DA 升高；但 VTA→腹侧 CA1/vSub 的 DA 投射仍对奖励相关记忆发挥互补作用（Lisman & Grace 2005 框架部分保留）

---

## 2026-07-10（文章 #78·记忆再巩固·GluN2B-NMDA-CaMKII-UPS 去稳定化分子链）

**源文章**：[[2026-07-10-memory-reconsolidation-ptsd]] —《记忆再巩固：分子机制与创伤记忆干预》

**新建页面（1 页）**：
- `concepts/memory-reconsolidation.md`：已巩固记忆在提取后的蛋白合成依赖再稳定化过程；去稳定化分子链（预测误差→GluN2B-NMDA→Ca²⁺→CaMKII→20S蛋白酶体激活→Shank/GKAP选择性降解+GluA2内吞→CP-AMPAR出现）；再稳定化路径（PKA/ERK/CaMKIV→CREB→即早基因→新蛋白合成）；边界条件（短暴露/小预测误差→再巩固；长暴露/大预测误差→消退；极强记忆难去稳定化）；行为干预（单次CS+10min内消退=永久消除恐惧，Monfils 2009）；药物干预（普萘洛尔：人类情绪记忆消除保留陈述性，Kindt 2009；米非司酮 Phase 2a RCT 未达主要终点，PMID:37159200）（mainstream, confidence:medium-high）

**修订页面（4 页）**：
- `concepts/memory-consolidation.md`（rev7→rev8）：当前理解节新增"第三维：再巩固"段落（再巩固打破"巩固即密封"教条；提取诱发的动态去稳定化→再稳定化循环）；连接节新增 memory-reconsolidation；related/source_articles 相应更新
- `concepts/fear-conditioning.md`（rev1→rev2）：当前理解节新增"记忆修改的窗口"段落（再巩固窗口、药物/行为干预靶点）；连接节新增 memory-reconsolidation、NE-β-AR 普萘洛尔注释；source_articles 新增
- `concepts/fear-extinction.md`（rev2→rev3）：当前理解节新增"消退 vs 再巩固窗口消退"段落（Monfils 2009 行为干预策略对比、Agren 2012 fMRI BLA 信号消除证据、临床含义）；连接节新增 memory-reconsolidation；Q-fear-reconsolidation-boundary 标记为部分解答；source_articles 新增
- `systems/amygdala.md`（rev2→rev3）：新增"BLA 中的记忆再巩固去稳定化分子链"机制节（GluN2B-NMDA→CaMKII→UPS→Shank/GKAP降解+GluA2内吞完整级联；再稳定化路径；窗口内干预靶点：普萘洛尔/米非司酮/行为干预）；连接节新增 memory-reconsolidation；source_articles 新增

**图谱更新**：新增 1 节点（memory-reconsolidation）、15 条边；总计 144 节点，861 边

**新登记矛盾**：无

**新增未解问题（2 个）**：
- Q-reconsolidation-01（高优先级）：极强/极旧记忆（多年 PTSD 创伤）能否在临床实践中可靠地诱导进入再巩固窗口？
- Q-reconsolidation-02（中优先级）：再巩固干预对不同记忆类型（空间、语义、运动）的分子机制是否相同？

**Q-gc-01 更新（部分解答）**：米非司酮 Phase 2a RCT（PMID:37159200）已明确：当前固定给药方案（600mg/d×7天，未锚定记忆激活时机）不支持 Phase 3；TBI 阴性亚组信号（22.7%）提示更精准设计（高剂量+CS暴露后1-2h内给药）仍有价值；问题仍 open，但有了关键失败参照

---

## 2026-07-09（文章 #77·记忆为什么最牢记住恐惧·糖皮质激素与应激记忆）

**源文章**：[[2026-07-09-glucocorticoids-stress-memory-amygdala]] —《记忆为什么最牢记住恐惧：糖皮质激素如何通过杏仁核把应激烙进长期记忆》

**新建页面（2 页）**：
- `concepts/glucocorticoid-stress-memory.md`：MR/GR 双时相模型（MR 高亲和力快速评估 vs GR 低亲和力慢速基因组巩固）；BLA 作为全脑 GC 记忆增强必要枢纽（Barsegyan 2019 PMC6452745）；GC+NE 协同门控（Roozendaal 2006 β-AR 阻断实验）；HPA-SAM 轴协同模型；慢性应激→CA3 选择性萎缩（McEwen 1997, Uno 1994）；急性应激→记忆系统切换（HC→背侧纹状体，Schwabe 2012 fMRI）（established, confidence:high）
- `systems/hpa-axis.md`：PVN-CRH→垂体-ACTH→肾上腺皮质-皮质醇三级级联；MR/GR 亲和力分工；负反馈三层次（快速非基因组/中速基因组/慢速 CRH 下调）；海马 GR 负反馈制动及慢性应激恶性循环；CRH 在 CeA 的中枢独立效应（肾上腺切除动物仍存在）；SCN 昼夜节律对 HPA 皮质醇晨峰的门控（established, confidence:high）

**修订页面（2 页）**：
- `systems/amygdala.md`（rev1→rev2）：新增"GC与NE协同增强应激记忆"机制节（BLA必要枢纽、GC-NE协同门控、两次激活模型、Barsegyan 2019 多节点网络证据）；新增"CRH在CeA的中枢独立效应"节；related新增glucocorticoid-stress-memory、hpa-axis、memory-consolidation；key_sources新增PMID:30877244、PMID:16310958、PMID:23968228；opens_questions新增Q-fear-itc-bidirectionality；source_articles新增2026-07-09
- `neurons/hippocampal-circuit.md`（rev9→rev10）：新增"CA3的慢性应激脆弱性"机制节（树突萎缩约20%、灵长类海马萎缩约30%、GR高密度机制、NMDAR拮抗剂防萎缩因果证据、HPA负反馈恶性循环）；关键证据表增加2行（PMID:9405958、PMID:7729802）；连接新增glucocorticoid-stress-memory、hpa-axis；未解问题新增Q-gc-02；related/key_sources/source_articles相应更新

**图谱更新**：新增 2 节点（glucocorticoid-stress-memory, hpa-axis）、27 条边；总计 143 节点，846 边

**新登记矛盾**：无

**新增未解问题（3 个）**：
- Q-gc-01（高优先）：GR 拮抗剂（米非司酮）在创伤记忆再巩固窗口的临床有效性——当前 RCT 结果不一致；理想给药时机、剂量、患者亚型未明
- Q-gc-02（高优先）：慢性应激→CA3 萎缩→AD 风险升高的因果链强度——纵向研究（PTSD 后跟踪 10 年）的 AD 发病率数据能否确立因果？
- Q-gc-03（中优先）：GR 快速非基因组效应（膜型 GR 和 eCB 系统）在 BLA 记忆增强的前 30 分钟的精确时间贡献

**新增悬空引用（待补）**：无（所有连接指向已有节点或新建节点）

---

## 2026-07-08（文章 #76·大脑的 24 小时时钟·昼夜节律与 SCN 主时钟）

**源文章**：[[2026-07-08-circadian-clock-scn-brain-rhythm]] —《大脑的 24 小时时钟：视交叉上核如何用分子振荡设定时间，协调睡眠、记忆与衰老》

**新建页面（2 页）**：
- `concepts/circadian-clock.md`：昼夜节律分子振荡器（TTFL）——CLOCK/BMAL1 E-box 激活→PER/CRY 负反馈→CKIδ/ε 磷酸化延迟产生约 24h 振荡；REV-ERB/ROR 辅助稳定回路；温度补偿；FASPS 遗传证据（CKIδ T44A）；全身细胞自主振荡；CLOCK/BMAL1 调控 PV+ 成熟和关键期时序（Reh 2020）（established, confidence:high）
- `systems/scn-circadian-pacemaker.md`：视交叉上核（SCN 主时钟）——ipRGC/黑视素→RHT→VIP 核心区→AVP 壳区；VIP/VPAC2 细胞间耦合同步；三条输出路径（自主神经→褪黑素、神经投射→LC/VLPO/DMH、体液 AVP/PROK2）；SCN 移植实验（Ralph 1990）；星形胶质细胞时钟（Brancaccio 2019）；AD 中 SCN VIP 神经元早期萎缩（established, confidence:high）

**修订页面（6 页）**：
- `concepts/rem-sleep.md`（rev1→rev2）：新增"昼夜节律对 REM 睡眠的时序门控"小节（后半夜 REM 优势的 SCN 门控、两过程模型、PTSD 脆弱性含义）；related 新增 circadian-clock、scn-circadian-pacemaker；key_sources 新增 PMID:12198538、PMID:7185792
- `concepts/memory-consolidation.md`（rev6→rev7）：新增"昼夜节律对记忆巩固的时间门控"小节（LTP 昼夜波动、BMAL1 KO 学习损伤、AD SCN 萎缩→记忆功能下降双重恶化）；related 新增 circadian-clock、scn-circadian-pacemaker；key_sources 新增 PMID:12198538
- `systems/glymphatic-system.md`（rev1→rev2）：连接节新增 circadian-clock、scn-circadian-pacemaker、norepinephrine-locus-coeruleus 三条路径说明（胶质淋巴清洗的昼夜节律门控机制经 SCN→LC→NE 振荡路径）；key_sources 新增 PMID:19798445
- `concepts/cortical-slow-oscillation.md`（rev2→rev3）：连接节新增 circadian-clock、scn-circadian-pacemaker（两过程模型将 SO 丰富的慢波睡眠定时于前半夜）；key_sources 新增 PMID:7185792
- `systems/neuromodulator-systems.md`（rev3→rev4）：新增"昼夜节律对神经调质系统的协调"小节（四大调质系统昼夜节律模式 × SCN 调控路径一览表；大脑时间依赖工作模式切换架构）；related 新增 circadian-clock、scn-circadian-pacemaker、glymphatic-system
- `concepts/critical-period.md`（rev1→rev2）：连接节新增 circadian-clock（Reh 2020：CLOCK/BMAL1→PV+ 成熟速率→关键期时间轴）；related 新增 circadian-clock；key_sources 新增 PMID:32503914

**图谱更新**：新增 2 节点（circadian-clock, scn-circadian-pacemaker）、22 条边；总计 138 节点，794 边

**新登记矛盾**：无（昼夜节律局部时钟 vs SCN 主时钟的相对贡献争议已记录为 Q-circ-01）

**新增未解问题（3 个）**：
- Q-circ-01（高优先）：局部脑区时钟（海马、PFC）与 SCN 主时钟的相对贡献——SCN 萎缩后局部时钟能否部分代偿？
- Q-circ-02（高优先）：定时光照 + 褪黑素干预能否稳定昼夜节律进而延缓 AD Aβ 积累？III 期 RCT 证据缺失。
- Q-circ-03（中优先）：SCN 星形胶质细胞独立功能时钟（Brancaccio 2019）在 AD 反应性胶质增生中的功能改变？

**新增悬空引用（待补）**：无（所有连接指向已有节点或新建节点）

---

## 2026-07-07（文章 #75·三重协奏·SO-纺锤波-SWR 与 SHY 假说）

**源文章**：[[2026-07-07-sleep-memory-consolidation-so-spindle-swr]] —《三重协奏：皮层慢振荡如何指挥纺锤波与海马涟漪，把白天的经历刻入长期记忆》

**新建页面（2 页）**：
- `concepts/so-spindle-swr-coupling.md`：SO-纺锤波-SWR 三重耦合——SO（主时钟）→纺锤波（皮层预热，L型Ca²⁺窗口）→SWR（记忆写入，纺锤波波谷）的时间嵌套机制；Maingret 2016 闭环刺激因果证明；Helfrich 2018 老龄化耦合精度下降（d=1.19）；神经调质（NE/DA/ACh）调节（established, confidence:high）
- `concepts/shy-hypothesis.md`：突触稳态假说（SHY）——清醒 LTP 积累→睡眠期 SO 驱动整体突触下调（de Vivo 2017：ASI 缩小~18%）；down-selection 框架：被 SWR 重播激活的突触受保护；与 Turrigiano 突触稳态缩放的区别；Q-shy-molecular-mechanism 未解问题（mainstream, confidence:medium）

**修订页面（3 页）**：
- `concepts/memory-consolidation.md`（rev5→rev6）：新增 so-spindle-swr-coupling、shy-hypothesis 两个 related 节点；新增 Helfrich 2018 和 de Vivo 2017 证据行；Q-shy-vs-active-consolidation 部分解决（通过 down-selection 框架）；source_articles 新增 2026-07-07 文章
- `concepts/sleep-spindles.md`（rev1→rev2）：新增 Helfrich 2018 SO-纺锤波相位精度证据行（d=1.19；老年相位偏移 46.3°）；related 新增 so-spindle-swr-coupling；source_articles 新增 2026-07-07 文章
- `concepts/sharp-wave-ripples.md`（rev5→rev6）：新增 Maingret 2016 闭环刺激因果证据行（PMID:27182818）；related 新增 so-spindle-swr-coupling；source_articles 新增 2026-07-07 文章

**图谱更新**：新增 2 节点（so-spindle-swr-coupling, shy-hypothesis）、18 条边；总计 136 节点，772 边

**新登记矛盾**：无（SHY vs 主动巩固的对立通过 down-selection 框架部分调和；已记录为 Q-shy-vs-active-consolidation 部分解答）

**新增/更新未解问题（3 个）**：
- Q-replay-human-translation（高优先）：人类直接因果实验（闭环增强三重耦合）能否复现大鼠结果？
- Q-shy-molecular-mechanism（高优先）：SO UP state 驱动突触 LTD 的分子触发器是 NMDAR 阈下 Ca²⁺、mGluR 还是内源性大麻素系统？
- Q-shy-vs-active-consolidation（已部分解答）：down-selection 框架调和了两者，但单突触层面直接追踪"被保护 vs 被下调"突触的实验仍缺失

**新增悬空引用（待补）**：
- `locus-coeruleus`：蓝斑核独立条目（so-spindle-swr-coupling 和 shy-hypothesis 均提及 NE 调节，目前无独立页面）

---

## 2026-07-06（文章 #74·大脑的夜间清洗工程·胶质淋巴系统与睡眠废物清洗）

**源文章**：[[2026-07-06-glymphatic-system-sleep-clearance]] —《大脑的夜间清洗工程：胶质淋巴系统如何在睡眠中清除阿尔茨海默病的始动毒素》

**新建页面（2 页）**：
- `systems/glymphatic-system.md`：胶质淋巴系统——CSF 沿动脉旁间隙入流、经星形胶质细胞终足 AQP4 穿越脑实质、沿静脉旁出流；蓝斑核 NE 振荡驱动慢性血管运动为主要驱动力；深度 NREM 睡眠期高效运转；AQP4 KO→70% 清除效率下降（mainstream, confidence:medium）
- `concepts/aqp4.md`：AQP4 水通道蛋白 4——高度极化富集于星形胶质细胞终足；CSF-ISF 对流的分子水门；AQP4 去极化是衰老导致胶质淋巴衰退的分子基础（established, confidence:high）

**修订页面（3 页）**：
- `systems/astrocyte.md`（rev2→rev3）：新增第六大功能（胶质淋巴功能）：终足 AQP4 极化驱动 CSF-ISF 对流交换；dimensions 新增 whole-brain-network；related 新增 glymphatic-system、aqp4；key_sources 新增 PMID:22896675
- `diseases/alzheimers-disease.md`（rev5→rev6）：新增关键机制节"胶质淋巴清除失效：AD 的上游功能原因"（衰老三重削弱 + 蓝斑核双重角色 + 人类直接证据）；related 新增 glymphatic-system、aqp4；opens_questions 新增 Q-glyph-01/02；key_sources 新增 PMID:22896675/30679382/19779148/41593094
- `concepts/cortical-slow-oscillation.md`（rev1→rev2）：新增 NREM 慢波睡眠同时驱动记忆巩固和胶质淋巴清洗的双重功能连接；related 新增 glymphatic-system、alzheimers-disease；key_sources 新增 PMID:39788123

**图谱更新**：新增 2 节点（glymphatic-system, aqp4）、10 条边；总计 134 节点，754 边

**新登记矛盾**：无（对流 vs 扩散增强之争是已知争议，但两派均同意睡眠增强清洗这一核心事实，不构成全面对立的 contested_claim；保留为未解问题）

**新增未解问题（4 个）**：
- Q-glyph-01（高优先级）：蓝斑核 NE 振荡的最优频率是什么？~0.05 Hz 是最优还是副产物？
- Q-glyph-02（高优先级）：AQP4 去极化在衰老中的分子触发器？M23/M1 比例是否可药物干预？
- Q-glyph-03（中优先级）：胶质淋巴系统对 α-突触核蛋白、TDP-43 等其他聚集蛋白的选择性
- Q-glyph-04（中优先级）：唑吡坦等安眠药长期使用对胶质淋巴清洗的量化影响

**新增悬空引用（待补）**：
- `locus-coeruleus`：蓝斑核独立条目（glymphatic-system 和 tau-pathology 均引用，目前只有 locus-coeruleus-anatomy 待建记录）

---

## 2026-07-05（文章 #73·记忆的竞争法庭·神经元分配与记忆联结机制）

**源文章**：[[2026-07-05-engram-allocation-memory-competition]] —《记忆的竞争法庭：大脑如何选定那些承载记忆的神经元》

**新建页面（2 页）**：
- `concepts/memory-allocation.md`：神经元分配——CREB/内在兴奋性竞争决定哪些神经元进入印迹；零和竞争；PV+侧向抑制赢家通吃；表观遗传前置层（H3K27ac）；训练后5min巩固窗口（mainstream, confidence:high）
- `concepts/memory-linking.md`：记忆联结——时间接近（~6h）的两段学习因共享高兴奋性印迹神经元而实现联结；Cai 2016 CA1钙成像直接证据；老年小鼠CA1兴奋性下降→联结缺陷→DREADD救援；scFLARE2精确时间边界（3h vs 27h）（emerging, confidence:medium）

**修订页面（1 页）**：
- `concepts/engram-cells.md`（rev4→rev5）：related新增 memory-allocation、memory-linking、pv-interneurons；key_sources新增 PMID:29709212、27251287、41470040；修订历史追加2026-07-05条目；source_articles新增2026-07-05文章

**图谱更新**：新增 2 节点（memory-allocation, memory-linking）、16 条边；总计 135 节点，770 边

**新登记矛盾**：无（CREB内源性波动是否足以影响自然分配——Q-alloc-01尚不构成正式矛盾，标记为未解问题）

**新增未解问题（3 个）**：
- Q-alloc-01（高优先级）：内源性CREB活性波动是否足以在自然学习中真实影响分配？
- Q-alloc-02（高优先级）：记忆联结时间窗（~6h）的分子决定因素和跨物种差异
- Q-alloc-03（中优先级）：H3K27ac等表观遗传标记是否可作为记忆增强干预靶点？

**新增悬空引用（待补）**：
- `creb`：CREB 蛋白（被 memory-allocation 多次引用，尚无独立 wiki 节点）
- `intrinsic-excitability`：内在兴奋性稳态（被 memory-allocation、memory-linking 引用，尚无独立页面）

---

## 2026-07-04（文章 #54·信号与噪声之间·皮层 E/I 平衡与 PV 中间神经元守门机制）

**源文章**：[[2026-07-04-ei-balance-pv-interneuron]] —《信号与噪声之间：皮层 E/I 平衡的回路逻辑、PV 中间神经元的守门机制与大脑"刹车"的分子基础》

**新建页面（2 页）**：
- `concepts/ei-balance.md`：兴奋-抑制平衡——皮层回路信噪比控制机制；PV+/SST+/VIP+ 三类中间神经元分工维持；多维度（非单一数字）；ASD/精神分裂症/癫痫的共同汇流点；关键证据：Sohal & Rubenstein 2019（mainstream, confidence:medium）
- `concepts/perineuronal-nets.md`：围神经元网——包裹 PV+ 细胞的细胞外基质网络；aggrecan+透明质酸+连接蛋白；OTX2 正反馈驱动 PV 成熟；固化 AMPA 受体；ChABC 可逆转关键期（动物）（established, confidence:high）

**修订页面（3 页）**：
- `circuits/pv-interneurons.md`（rev2→rev3）：新增 E/I 平衡执行者角色、关键期初始靶点（Quast & Hensch 2023）、PNN 固化机制、神经炎症脆弱性（Allami 2025）；related 新增 ei-balance/perineuronal-nets；key_sources 新增 3 个
- `concepts/gamma-oscillations.md`（rev2→rev3）：新增伽马振荡作为 E/I 平衡动态读出的维度；关键期 γ 瞬态爆发（Quast & Hensch 2023）；related 新增 ei-balance/perineuronal-nets；来源文章新增
- `concepts/homeostatic-plasticity.md`（rev1→rev2）：新增与 E/I 平衡的互补关系（慢速 vs 快速机制）；related 新增 ei-balance

**新登记矛盾**：无（E/I 失衡方向在 ASD 中存在争议，已在文章和 wiki 中标注为待解问题，暂不登记矛盾）

**新增未解问题（3 个）**：
- Q-ei-balance-01（高优先级）：如何精准非侵入性测量人类特定皮层 E/I 状态？
- Q-ei-balance-02（高优先级）：ASD 中 E/I 失衡方向的异质性——不同基因突变的回路变化方向一致吗？
- Q-ei-balance-03（中优先级）：VIP+ 去抑制回路调制 E/I 平衡的精确时序和幅度

**新增悬空引用（待补）**：
- `critical-period`：关键期（从 perineuronal-nets、ei-balance 页面引用，尚未独立成页）
- `intrinsic-excitability`：内在兴奋性稳态（homeostatic-plasticity 页面的第二大类型，尚未独立页面）

**图谱更新**：新增节点 2（ei-balance, perineuronal-nets）；新增边 14；总计 **132 节点、744 条边**

---

## 2026-06-03（文章 #70·大脑的"质检员"·小胶质细胞与补体介导的突触剪枝）

**源文章**：[[2026-06-03-microglia-synaptic-pruning]] —《大脑的"质检员"：小胶质细胞如何用补体分子标签精雕突触回路》

**新建页面（3 页）**：
- `neurons/microglia.md`：小胶质细胞——CNS 常驻免疫细胞，发育期突触剪枝执行者；CR3（C3b识别）+ TREM2（PS识别）双通路；活动依赖性（TTX实验）；疾病连接（AD C1q重激活、精神分裂症 C4A 过度表达）（established）
- `concepts/synaptic-pruning.md`：突触剪枝——先多建再精删策略；"吃我"（C3b/PS）+"别吃我"（CD47）双向信号博弈；视网膜膝状核模型（C1QA/C3 KO 眼特异性分离失败）；发育窗口：dLGN P2-P10、海马 P15、前额叶青春期（established）
- `concepts/complement-cascade-cns.md`：补体级联（CNS突触功能版）——C1q→C4→C3b的步骤；TGF-β（星形胶质细胞）→C1q（神经元）的跨细胞诱导轴；发育期/成年期的活性差异；AD和精神分裂症中的病理失调（established）

**修订页面（1 页）**：
- `diseases/alzheimers-disease.md`（rev4→rev5）：新增 C1q 补体介导的早期突触丢失机制（Hong et al. 2016，PMID:27033548）：Aβ低聚体触发C1q早期突触沉积（早于斑块）；related 新增 microglia/complement-cascade-cns/synaptic-pruning；key_sources 新增 PMID:27033548

**新登记矛盾**：无

**新增悬空引用（待补）**：
- `critical-period`：关键期（发育期 E/I 平衡与突触剪枝直接关联）
- `cx3cr1`：fractalkine 受体——趋化因子-微胶质轴（影响海马剪枝，Soteros 2022）
- `megf10` / `mertk`：星形胶质细胞自身的突触吞噬受体（非微胶质依赖的并行剪枝通路）

**图谱更新**：新增节点 3（microglia, synaptic-pruning, complement-cascade-cns）；新增边 10；总计 **130 节点、~730 条边**

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

---

## 2026-06-03 · 文章 #72 · 时间刻入神经回路：大脑发育关键期的开关机制与可塑性窗口的重启

**核心主题**：视觉皮层关键期（Critical Period）的分子开关机制——GABA 阈值触发开启，PNN/OTX2/Lynx1 三道刹车主动关闭，ChABC/氟西汀/催产素重开关键期。

**新建页面（1）**：
- `concepts/critical-period.md`（发育关键期）🟢 established — PV+成熟/PNN/OTX2/BDNF/Lynx1机制；19篇来源（13篇开放全文）；连接 pv-interneurons, perineuronal-nets, ei-balance, bdnf, microglia, synaptic-pruning, ltp, ltd

**修订页面（3）**：
- `concepts/perineuronal-nets.md` rev2 — 新增机制3（PTPσ-TRKB轴统一ChABC/氟西汀机制，Lesnikova 2021，PMC7880295）；新增成年PNN动态调节证据（Devienne 2021，PMC8265812）；related新增 critical-period, microglia
- `circuits/pv-interneurons.md` rev4 — 新增关键期角色：PV+去激活是ODP首要微回路事件（Kuhlman 2013，PMC3962838），OTX2经PNN驱动PV成熟（Sugiyama 2008/Beurdeley 2012），BDNF设定PV成熟时间轴（Huang 1999），Rett综合征MeCP2 KO使关键期错位（Krishnan 2015，PMC4553776），小胶质细胞上游调控（Wang 2025，PMC12013681）；related新增 critical-period, bdnf, microglia
- `concepts/bdnf.md` rev2 — 新增关键期相关角色：BDNF驱动GABAergic成熟时间轴，PNN-aggrecan-PTPσ轴抑制BDNF信号进入PV+细胞；related新增 critical-period, pv-interneurons, perineuronal-nets

**矛盾登记（0）**：无新矛盾；Q-pnn-human-therapy（已有，关键期视角下新增 Q-cp-01至Q-cp-04）

**新增开放问题**：Q-cp-01（人类视觉CP时序）、Q-cp-02（语言CP分子机制）、Q-cp-03（SSRI临床转化可塑性重开安全性）、Q-cp-04（不同脑区CP时间窗口的分子决定因素）

**新增悬空引用（需补）**：无新悬空引用（critical-period所需关联节点均已存在）

**图谱**：133节点，754边（+1节点，+10边）

---

## 2026-06-19 · 文章 #85 · 突触时序依赖可塑性：用毫秒级时间窗口书写神经因果律

**核心主题**：STDP（Spike-Timing Dependent Plasticity）——NMDA 受体如何在毫秒级时序中充当因果仲裁者，Ca²⁺ 幅度如何决定 LTP/LTD，θ 振荡如何将行为时间尺度桥接至 STDP 窗口，三因素规则如何为 STDP 添加行为目标导向。

**新建页面（1）**：
- `concepts/stdp.md`（突触时序依赖可塑性）🔵 mainstream · 高置信度 — 填补了 hebbian-learning.md 中长期悬空的 [[stdp]] 引用；STDP 时序窗口（±20ms），两种形式（NMDAR-LTD vs CB1-LTD），频率/树突位置依赖，生理钙浓度约束，θ前进体内机制（R²=0.87），三因素扩展；10 篇来源（5 篇开放全文）

**修订页面（2）**：
- `concepts/hebbian-learning.md` rev5 — 将 [[stdp]] 标注从"待建页面"更新为"已建立"；source_articles 新增今日文章
- `concepts/nmda-receptor.md` rev5 — 新增 NMDA 受体第五重功能角色：STDP 时序仲裁器；新增 Bi & Poo 1998 NMDA 必要性证据表（AP-5 消除 STDP）；补充生理钙浓度约束；key_sources 新增三条

**矛盾登记（0）**：无新矛盾

**新增开放问题**：
- Q-stdp-physiological-ca：生理钙浓度下 STDP 的实际触发条件
- Q-stdp-inhibitory-synapses：抑制性突触 STDP 规则与功能
- Q-stdp-human-evidence：人类 STDP 的直接电生理证据

**悬空引用解决（1）**：
- `stdp` — 已建立 wiki/concepts/stdp.md（此前为 hebbian-learning.md 中的悬空引用）

**新增悬空引用（0）**：无新悬空引用（stdp.md 的 related 指向的页面均已存在）

**图谱**：156节点→157节点，924边→939边（+1节点，+15边）

---

## 2026-08-03 · 文章 #102 · 期望的神经化学：安慰剂镇痛的大脑回路与内源性阿片系统

**核心主题**：安慰剂镇痛（Placebo Analgesia）——PFC→rACC→PAG→RVM→脊髓下行阿片回路如何将心理期望转化为真实的内源性阿片止痛信号；纳洛酮逆转实验、PET μ-OR成像、fMRI rACC-PAG功能连接直接测量；双过程模型（期望+条件反射）；nocebo效应的CCK路径。

**新建页面（3）**：
- `concepts/placebo-analgesia.md`（安慰剂镇痛）🟢 established / 置信度高 — PFC→rACC→PAG阿片下行回路；Wager 2004（PFC↑+丘脑/ACC↓）；Zubieta 2005（rACC μ-OR激活r=-0.87）；Eippert 2009（rACC-PAG耦合，纳洛酮消除）；Petrovic 2002（安慰剂与阿片共享rACC）；双过程模型；开放标签安慰剂
- `concepts/endogenous-opioid-system.md`（内源性阿片系统）🟢 established / 置信度高 — μ/κ/δ受体分子机制；β-内啡肽/脑啡肽/强啡肽三类阿片肽；PAG核心枢纽；纳洛酮选择性逆转；PET [11C]卡芬太尼直接测量；填补periaqueductal-gray.md的悬空引用
- `concepts/nocebo-effect.md`（Nocebo效应）🟢 established / 置信度中 — 负向期望→促痛；CCK-A/B机制（Benedetti组）；与安慰剂阿片路径的双路径分离；开放标签安慰剂vs隐蔽安慰剂的行为证据

**修订页面（2）**：
- `systems/anterior-cingulate-cortex.md` rev1→rev2 — 新增rACC在安慰剂镇痛中的深化证据节：rACC-PAG功能连接（Eippert 2009，纳洛酮完全消除耦合）；μ阿片受体直接激活（Zubieta 2005，r=-0.87）；共享激活（Petrovic 2002）；related新增placebo-analgesia、endogenous-opioid-system；key_sources新增19709634、16120776、11834781
- `systems/periaqueductal-gray.md` rev1→rev2 — 新增Eippert 2009到关键证据表（fMRI+纳洛酮双盲，rACC-PAG耦合，脊髓安慰剂效应逆转）；临床相关性节更新；related新增placebo-analgesia；key_sources新增19709634、14976306

**矛盾登记（0）**：无新矛盾

**悬空引用解决（1）**：
- `endogenous-opioid-system` — 已建立 wiki/concepts/endogenous-opioid-system.md（此前为 periaqueductal-gray.md related字段中的悬空引用）

**新增悬空引用（0）**：无新悬空引用（所有新页面的related指向的节点均已存在）

**新增开放问题**：
- Q-placebo-01（高优先级：安慰剂镇痛的非阿片成分——CB1/5-HT/DA候选路径）
- Q-placebo-02（中优先级：开放标签安慰剂的神经机制——fMRI对比研究空白）

**图谱**：194节点→197节点，1118边→1134边（+3节点，+16边）

---

## 2026-08-27 · 文章 #125 · 应激如何重塑海马新生神经元：从 HPA 轴到 SGK3/TRP53 自噬路径的多层分子机制

**核心主题**：慢性应激/糖皮质激素对成体海马神经发生（AHN）的多层分子抑制机制——BDNF/TrkB 抑制、SGK3/TRP53 自噬性 NSC 死亡、Wnt/β-catenin 抑制、CRF₁R 独立抑制四条并行路径；以及 AHN-HPA 轴双向负反馈环（Snyder 2011 Nature）和 FKBP51（*FKBP5*）遗传门控。

**新建页面（2）**：
- `concepts/sgk3-autophagic-nsc-death.md`（SGK3 介导的神经干细胞自噬性死亡）🟡 emerging · 置信度中 — CORT→GR→SGK3→LC3→TRP53 降解→自噬性 NSC 死亡；Atg7 KO 保护 NSC；TRP53 存活守护功能；RITA 体外保护；单实验室（Jung et al.），需独立复现；2个未解问题（Q-sgk3-01/02）
- `concepts/fkbp51.md`（FKBP51/FK506 结合蛋白51）🔵 mainstream · 置信度中 — FKBP51 降低 GR 亲和力阻碍核转位；GR→FKBP5 负反馈超短环；*FKBP5* rs1360780 T 等位基因×童年创伤×PTSD 三重交互；SAFit2 体外促 NPC 增殖（>BDNF）、体内应激弹性；体外/体内不一致（BrdU 无显著差异）；2个未解问题（Q-fkbp51-01/02）

**修订页面（3）**：
- `concepts/adult-neurogenesis.md` rev2→rev3 — 新增零节（§0）：HPA/GC 对 AHN 的四条抑制路径全览 + AHN-HPA 双向反馈环 + FKBP51 遗传门控 + 恢复路径（运动/SSRI/GSK-3β 抑制剂/FKBP51 抑制剂）；更新连接（hpa-axis, glucocorticoid-stress-memory, sgk3-autophagic-nsc-death, fkbp51, ptsd）
- `concepts/glucocorticoid-stress-memory.md` rev1→rev2 — 新增第六节：慢性 GC 对 DG 神经发生的抑制（三条并行路径详解 + HPA-AHN 正反馈恶性循环 + FKBP51 遗传调制）；更新连接（adult-neurogenesis, sgk3-autophagic-nsc-death, fkbp51, bdnf）；新增3行证据表
- `systems/hpa-axis.md` rev1→rev2 — 扩展"海马负反馈制动器"段：新增 AHN 主动参与 HPA 负反馈（Snyder 2011）、FKBP51 遗传门控、AHN-HPA 正反馈恶性循环第二路径；更新连接（adult-neurogenesis, fkbp51, sgk3-autophagic-nsc-death）

**矛盾登记**：
- 人类成体海马神经发生存在与否：Sorrells 2018（Nature，自然衰退）vs Boldrini 2018（Cell Stem Cell，持续存在至老年），文章使用"存在且有功能"立场，标注高争议
- SAFit2 体外/体内不一致：体外 BrdU/TuJ1 显著↑；体内 BrdU 差异无统计显著性——机制未明

**新增悬空引用（0）**：无新悬空引用

**新增开放问题（5）**：Q-neurogenesis-stress-ptsd-01、Q-sgk3-01、Q-sgk3-02、Q-fkbp51-01、Q-fkbp51-02

**图谱**：249节点/1444边 → **251节点/1465边**（+2节点，+20边）

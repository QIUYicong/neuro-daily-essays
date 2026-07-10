# 阅读笔记 2026-07-11

**文章**：#194《光如何拧开一扇离子通道：通道视紫质的分子机制，从藻类眼点到神经科学的"开关"》

> **命名说明**：真实日期 2026-07-11 已被本知识库此前"日期漂移"事件产生的虚拟时间线文章占用（`2026-07-11-dopamine-lc-hippocampus-memory-tagging.md`，第79篇），依据 2026-07-07 修复事件确立的"日期+slug"消歧命名惯例，本篇 notes/sources/log 均采用带 slug 后缀的文件名，不覆盖、不修改、不引用该历史遗留文件。

---

## 开放全文阅读（精读）

### Nagel G, Ollig D, Fuhrmann M, Kateriya S, Musti AM, Bamberg E, Hegemann P. 2003, *PNAS*（PMID:14615590 / PMCID:PMC283525）
*Channelrhodopsin-2, a directly light-gated cation-selective membrane channel*
- **要解决的问题**：莱茵衣藻基因组中发现的两个视蛋白同源序列（channelopsin-1/2）功能未知，是否真的是"直接"光门控的离子通道（而非需要第二信使的间接机制）
- **方法**：异源表达系统（爪蟾卵母细胞、HEK293、BHK细胞）全细胞电压钳记录；巨膜片钳（excised patch）排除可扩散胞内因子参与；动作光谱测定
- **关键发现**：光激活电流上升时间约200μs、无可见延迟；巨膜片实验证明失活为蛋白内在属性；吸收峰约460nm（蓝光）；传导多种一价二价阳离子（区别于ChR1的高质子选择性，光谱蓝移40nm）
- **证据强度**：高（原始发现，直接电生理证据，多表达系统交叉验证）
- **对知识库的意义**：确立ChR2作为单组件直接光门控通道这一核心事实，是整个光遗传学工具箱的分子起点；论文本身已预见工具化应用价值

### Kato HE, Zhang F, Yizhar O, et al. 2012, *Nature*（PMID:22266941 / PMCID:PMC4160518）
*Crystal structure of the channelrhodopsin light-gated cation channel*
- **要解决的问题**：ChR孔道的具体结构组成是什么，为何它能作为通道被动传导离子而非像同源的细菌视紫红质那样主动泵送
- **方法**：C1C2嵌合体晶体结构解析，2.3Å分辨率；结构比对（与细菌视紫红质BR比较）；定点突变（Q95A、K132A、E136A、E140A等）验证孔道残基功能
- **关键发现**：七跨膜二聚体，视黄醛经希夫碱共价连接Lys296；孔道由TM1/2/3/7构成，12个极性残基（Glu129/136/140/162、Asp292等）形成带负电通路；C1C2的TM1/TM2胞外端比BR外倾3.0/4.1Å，扩大空腔允许水化阳离子通路；黑暗态两处胞质侧收缩点（Ser102/Glu129/Asn297；Tyr109）封闭孔道；门控路径为推测模型（Asp292质子化→排斥Lys132→TM1运动），作者明确承认"无法排除"其他机制
- **证据强度**：高（结构直接证据）；门控动态机制部分为合理化推测，非直接观测
- **对知识库的意义**：首次在原子层面回答"孔道长什么样"，为后续几乎所有定点突变工程变体提供了结构基础；同时暴露了一个真实的、尚未解决的机制缺口（门控路径未被直接观测）

### Klapoetke NC, Murata Y, Kim SS, et al. 2014, *Nature Methods*（PMID:24509633 / PMCID:PMC3943671）
*Independent optical excitation of distinct neural populations*
- **要解决的问题**：能否找到一对光谱充分分离、动力学足够快的通道视紫质，实现对两群不同神经元的独立双色控制
- **方法**：大规模筛选新型通道视紫质基因，电生理+光谱学表征动力学参数（开启/关闭时间常数、光敏感性、光谱峰值）
- **关键发现**：Chronos（蓝绿光，开启2.3ms/关闭3.6ms，支持60Hz跟随，"比此前任何ChR都快"）；Chrimson（红光，峰值~590nm，"比此前任何ChR红移45nm"），工程变体ChrimsonR改善动力学支持~20Hz
- **证据强度**：高（直接功能表征，多参数交叉验证）
- **对知识库的意义**：确立"双色独立控制"这一实验范式的分子基础，是研究"两条通路如何相互作用"的关键工具起点

### Kishi KE, Yun HS, Nakamura R, et al. 2022, *Cell*（PMID:35114111 / PMCID:PMC7612760）
*Structural basis for channel conduction in the pump-like channelrhodopsin ChRmine*
- **要解决的问题**：ChRmine具有远超经典ChR2的光电流、光敏感性和红移光谱，其结构基础是什么；为何功能上是通道却被发现结构上更接近离子泵
- **方法**：结构解析（冷冻电镜/晶体学）；结构比对（与经典二聚体ChR及泵型视蛋白比较）；rsChRmine工程变体的全光学单神经元操控实验
- **关键发现**：ChRmine形成三聚体（而非典型ChR的二聚体）、TM3螺旋缩短、保留质子泵特征性DTD基序残基，但功能上仍是被动阳离子通道；红移光谱支持对上百个单独指定神经元的全光学操控；rsChRmine实现非侵入式深脑快速环路控制的概念验证
- **证据强度**：高（结构+功能双重证据）
- **对知识库的意义**：揭示"泵样折叠、通道功能"的结构错位现象，为分子层面回应[[optogenetics]]已登记的Q-opto-depth-limit（组织光散射限制）提供直接证据；同时暴露一个新的未解演化问题（这种结构错位如何产生）

---

## 摘要级阅读（未获取全文）

### Boyden ES, Zhang F, Bamberg E, Nagel G, Deisseroth K. 2005, *Nat Neurosci*（PMID:16116447）
*Millisecond-timescale, genetically targeted optical control of neural activity*
- 首次将ChR2应用于哺乳动物神经元，实现毫秒级动作电位光控；已在[[optogenetics]]页面（created 2026-06-09）固结，本次仅作背景引用，未重复精读全文

---

## 官方机构来源

### The Jackson Laboratory — Ai32 品系目录（Strain #012569）
- URL: https://www.jax.org/strain/012569
- **内容**：官方转基因小鼠品系页面，确认 Ai32（B6;129S-Gt(ROSA)26Sor^tm32(CAG-COP4*H134R/EYFP)Hze^/J）品系将 ChR2(H134R)/EYFP 构建整合于 ROSA26 位点，为 Cre 依赖表达设计
- **局限**：本次工具未能提取"How it's Used"完整正文段落（页面结构复杂），仅确认基础遗传构建信息与品系目录条目存在
- **角色**：作为"分子机制→工具箱标准化产品"链条的官方基础设施证据，呼应 #193 中使用 Allen Institute 基因数据库的先例

---

## 本次会话对图谱的核查发现

在为 channelrhodopsin 选题做背景核查时，发现 `wiki/_graph.json` 的 `dangling_references` 列表中标记为悬空引用的 `path-integration`（被 grid-cell 引用）实际上早在 2026-06-22 就已建立独立页面（`wiki/concepts/path-integration.md`，wiki/index.md 中有 "✅ 2026-06-22 已建立" 记录），图谱记录未同步更新。经进一步排查，`tarp-auxiliary-subunit`、`mglur-ltd`、`embodied-semantics`、`dentate-gyrus`、`excitotoxicity`、`mitochondrial-dysfunction`、`neuroinflammation` 等条目也存在同样的"页面已建但图谱未标注resolved"情况。本次仅订正了直接影响今日选题判断的 `path-integration` 一条（避免选中一个已被填补的"假空缺"），其余条目的批量核查与订正留待未来会话处理，已记入 `state/unresolved_questions.md`。

## 真正确认仍然开放的悬空引用（本次核查，供未来选题参考）

`complexin`、`munc18`、`bdnf-trkb`、`prc-prion-protein`、`basal-forebrain`、`locus-coeruleus-anatomy`、`wernicke-area`、`planum-temporale`、`binding-problem`、`co-ripples`、`neural-population-coding`、`recurrent-network`、`protein-aggregation`、`ubiquitin-proteasome`、`autophagy`、`nuclear-inclusions` —— 经逐一核查磁盘文件，确认均无对应 wiki 页面，是真实的悬空引用。`channelrhodopsin` 已在本次选题中处理。

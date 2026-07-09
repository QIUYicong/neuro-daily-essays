# 阅读笔记 2026-07-10

**文章**：#193《苔藓纤维的分子笔迹：活动区蛋白的配比，能否写出终扣的"生物物理签名"？》

> **命名说明**：真实日期 2026-07-10 已被本知识库此前"日期漂移"事件产生的虚拟时间线文章占用（`2026-07-10-memory-reconsolidation-ptsd.md`，第78篇，实际写作/提交于2026-07-02，标注日期为2026-07-10），依据 2026-07-07 修复事件确立的"日期+slug"消歧命名惯例，本篇 notes/sources/log 均采用带 slug 后缀的文件名，不覆盖、不修改、不引用该历史遗留文件。

---

## 开放全文阅读（精读）

### Augustin I, Korte S, Rickmann M, Kretzschmar HA, Südhof TC, Herms JW, Brose N. 2001, *J Neurosci*（PMID:11150314 / PMCID:PMC6762458）
*The cerebellum-specific Munc13 isoform Munc13-3 regulates cerebellar synaptic transmission and motor learning in mice*
- **要解决的问题**：Munc13 家族三个主要旁系同源基因（Munc13-1/2/3）中，Munc13-3 的组织分布和功能未知
- **方法**：原位杂交+免疫组化确定表达模式；同源重组生成 Munc13-3 缺失突变小鼠；平行纤维刺激下浦肯野细胞全细胞记录（配对脉冲比 50-400ms 间隔）；转棒运动学习行为学（重复测试+ANOVA）
- **关键发现**：Munc13-3 几乎只在小脑表达（颗粒细胞+浦肯野细胞胞体，不在胶质细胞），蛋白定位于分子层突触神经毡（PF-PC突触前膜）；敲除后 PF-PC 突触配对脉冲易化显著增强（最高200ms间隔仍显著），提示释放概率降低；自发运动正常，但复杂运动学习（第11次试验后开始）受损，基因型×测试轮次交互显著（F=15.12, p<0.0001）
- **证据强度**：高（原文全文可读，基因操控+电生理+行为学三重证据）
- **对知识库的意义**：确立小脑拥有专属的活动区/启动蛋白亚型这一核心事实，是今天论证链条的起点

### Ishiyama S, Schmidt H, Cooper BH, Brose N, Eilers J. 2014, *J Neurosci*（PMID:25355221 / PMCID:PMC6608426）
*Munc13-3 superprimes synaptic vesicles at granule cell-to-basket cell synapses in the mouse cerebellum*
- **要解决的问题**：Munc13-3 缺失导致释放概率下降的具体机制是什么（分子性 vs 位置性超预激活）
- **方法**：颗粒细胞-篮状细胞配对全细胞膜片钳记录；多概率涨落分析（不同细胞外钙浓度下的方差-均值分析）；EGTA（慢速钙螯合剂）缓冲实验区分纳米域/微域耦合
- **关键发现**：释放概率 WT 0.38 → KO 0.24（接近减半）；10ms间隔配对脉冲比 2.7→3.5；失败率 0.48→0.66；钙内流本身和 RRP 补充速率不受影响；EGTA 实验提示主要为位置性机制（钙通道-囊泡耦合距离缩短约10-15nm）
- **证据强度**：高（定量电生理+药理学分离机制，但研究对象是颗粒细胞输出突触，非苔藓纤维输入突触）
- **对知识库的意义**：为"超预激活"提供了目前最精确的量化机制描述，是本文核心概念卡片的直接来源

### Netrakanti PR, Cooper BH, Dere E, Poggi G, Winkler D, Brose N, Ehrenreich H. 2015, *Cerebellum*（PMID:25617111 / PMCID:PMC4441738）
*Fast cerebellar reflex circuitry requires synaptic vesicle priming by munc13-3*
- **要解决的问题**：Munc13-3 缺失在体内行为层面的功能后果是选择性的还是广泛的
- **方法**：Munc13-3 缺失小鼠全套行为学测试（Morris水迷宫、旷场焦虑、前脉冲抑制、社交互动、听觉惊跳反射）
- **关键发现**：海马依赖行为（空间学习、焦虑、社交、感觉门控）完全正常；唯独听觉惊跳反射（依赖快速小脑反射回路）显著减弱；Munc13-3 mRNA虽也见于齿状回但功能上似乎被其他亚型代偿
- **证据强度**：高（在体行为学，多范式交叉验证选择性效应）
- **对知识库的意义**：提供体内证据支持"Munc13-3 是快速小脑回路的非冗余组件"，但仍未直接测量苔藓纤维突触本身

### Fulterer A, Andlauer TFM, Ender A, et al. 2018, *Cell Reports*（PMID:29719243 / PMCID:PMC6436828）
*Active Zone Scaffold Protein Ratios Tune Functional Diversity across Brain Synapses*
- **要解决的问题**：活动区蛋白如何在同一神经元的不同突触间产生功能多样性
- **方法**：果蝇NMJ超分辨成像（STED）+电生理，定量BRP、Syd-1、Unc13A、Unc13B的相对比例与纳米级空间分布
- **关键发现**：BRP/Unc13A组合使Unc13A更靠近钙通道（高释放概率），Syd-1/Unc13B组合使Unc13B更远（低释放概率、更强易化）；不同突触的蛋白比例构成"纳米级分子指纹"，直接预测释放特性
- **证据强度**：高（果蝇模式系统，机制原理证据扎实，但非哺乳动物/非小脑）
- **对知识库的意义**：为"同分子不同配比→不同突触性格"提供了目前最直接的定量机制范例，是今天文章的核心理论支架

### Piao C, Sigrist SJ. 2021, *Front Synaptic Neurosci*（PMID:35046788 / PMCID:PMC8762327）
*(M)Unc13s in Active Zone Diversity: A Drosophila Perspective*（综述）
- **阅读范围**：摘要+机制框架部分
- **关键内容**：系统综述Unc13家族亚型在果蝇活动区中的纳米级定位差异如何驱动整体活动区多样性
- **对知识库的意义**：作为综述来源与Fulterer 2018形成互证，用于框定"活动区多样性"这一 wiki 页面既有开放问题（Q-active-zone-heterogeneity）的推进证据

---

## 摘要阅读（浏览，未获取全文）

### Nusser Z. 2018, *Curr Opin Neurobiol*（PMID:29353084，综述，未开放全文）
- 提出本文核心理论框架："功能多样的突触可以由相同分子构建，仅通过不同的数量、密度与纳米级排布实现"
- 未获取全文，仅依据摘要转述这一框架性论断，未引用其综述中可能存在的具体数据细节

### Han X, Meral ES, Lichtman J. 2025, bioRxiv 预印本（DOI:10.1101/2025.10.02.679866，未经同行评审，未获取全文，仅Europe PMC索引摘要）
*Structured Sampling of Molecularly Classified Mossy Fiber Inputs by Cerebellar Granule Cells*
- 体积相关光镜-电镜技术，按VGluT1阳性/阴性状态对苔藓纤维终扣分子分类；颗粒细胞对不同类型终扣的采样呈结构化非随机模式
- 未获取全文导致无法评估具体统计量与样本量，仅作为"苔藓纤维终扣本身可被分子分类"这一新兴方向的标志性证据引入，且明确标注其预印本、未同行评审的性质

### Beierlein M, Fioravante D, Regehr WG. 2007, *Neuron*（PMID:17582334，仅摘要）
- 同一颗粒细胞轴突对不同突触后靶点（浦肯野细胞 vs 中间神经元）表现出不同的突触后效应短时程可塑性和逆行信号
- 用作背景类比，说明"同一突触前细胞→不同靶点→不同突触性格"这一现象在小脑输出层已有先例

### Bao J, Reim K, Sakaba T. 2010, *J Neurosci*（PMID:20554867 / PMCID:PMC6634587，本次仅读摘要）
- 平行纤维突触对篮状细胞表现出压抑（此前认为该突触普遍易化），对不同细胞类型的短时程可塑性方向不同，驱动前馈抑制的靶细胞特异性时间模式
- 用作背景补充证据，未展开引用其定量细节

---

## 官方机构来源

### Allen Institute for Brain Science, Allen Mouse Brain Atlas（Gene Database API）
- 通过官方API（`api.brain-map.org`）确认 Unc13c（Munc13-3 编码基因）在其小鼠/大鼠全脑基因数据库中有条目记录（Gene ID 84031，小鼠；94978，大鼠）
- 该数据库理论上可用于查询苔藓纤维前体核团（脑桥核、前庭核、脊髓）中 Unc13c、Cacna1a 等基因的区域性表达定量数据
- **重要限制**：该机构官网的具体基因表达可视化页面（`mouse.brain-map.org/gene/show/*`）为JS动态渲染的单页应用，本次工具（WebFetch）无法提取实际ISH图像或表达量化数值，仅确认了API层面的基因条目存在性。这是一处诚实的检索限制，留待未来会话用专门的Allen API表达查询端点（如`/api/v2/data/StructureUnionize`）补充。

---

## 检索策略记录

- NCBI E-utilities esearch：`mossy fiber terminal Munc13 isoform cerebellum`（0条）→ 转 `Munc13 isoform short-term plasticity synapse`（11条）→ `Munc13-3 cerebellum granule cell`（4条）→ `mossy fiber bouton Munc13`（13条，多为海马MF-CA3，需甄别区分小脑MF）→ `P/Q-type calcium channel mossy fiber granule cell release`（2条）→ `active zone molecular diversity synapse specific release probability review`（0条）→ `Munc13 priming synaptic vesicle review`（26条）→ `synapse diversity molecular heterogeneity review bouton`（4条，命中Nusser 2018关键综述）
- Europe PMC REST API：逐一核实开放全文状态（isOpenAccess字段+PMCID），对声称开放的条目实际尝试PMC全文拉取以验证
- WebSearch辅助定位：Allen Institute相关背景、Munc13-3综述性描述交叉验证
- **重要甄别**：检索中发现大量"mossy fiber"文献实际指向海马齿状回-CA3的mossy fiber（不同于本文讨论的小脑苔藓纤维），包括PMID:41719128、39556620、36812326、34153028、31535974等——这些均为海马MF-CA3研究，本文未采用，仅在此记录以避免未来会话误用同名术语造成混淆

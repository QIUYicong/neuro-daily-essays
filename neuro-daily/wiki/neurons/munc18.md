---
title: Munc18-1 (STXBP1)
slug: munc18
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-07-14
updated: 2026-07-14
revision_count: 1
dimensions: [molecular, synaptic, cellular, disease]
related: [SNARE-complex, synaptotagmin, complexin, munc13, active-zone, synaptic-transmission]
prerequisites: [SNARE-complex, synaptic-transmission]
opens_questions: [Q-munc18-doc2-contribution, Q-munc18-template-in-vivo, Q-stxbp1-genotype-phenotype-gap]
source_articles: [2026-07-14-munc18-stxbp1-template-mechanism]
key_sources: ["PMID:10746715", "PMID:10657302", "PMID:21499244", "PMID:26030875", "PMID:32643828", "PMID:30540253", "PMID:38242640", "PMID:32073399", "GeneReviews:NBK396561"]
---

# Munc18-1 (STXBP1)

> **一句话定义**：SM（Sec1/Munc18）家族的胞质蛋白，与闭合构象的 Syntaxin-1 紧密结合；并非"堵住"SNARE 组装的阻碍者，而是用自身结构域充当模板，预先对齐 Syntaxin-1 与 Synaptobrevin-2 的 SNARE 基序 N 端，是神经递质释放绝对必需的组装催化核心。

## 当前理解

我们现在认为，Munc18-1 的闭合构象结合不是 SNARE 组装的"刹车"，而是一种**受控的预组装平台**。2000 年的晶体结构（Misura et al., PMID:10746715）曾造成一个持续多年的悖论：Munc18-1 把 Syntaxin-1 的 SNARE 基序物理包裹、藏在闭合构象内部，看起来应当阻碍组装；但同年的敲除小鼠实验（Verhage et al., PMID:10657302）显示，缺失 Munc18-1 会让神经递质分泌**完全消失**，而不是增强。2011-2020 年间的一系列生化与结构研究逐步解开了这个悖论：Munc18-1 的第 3a 结构域螺旋发夹在 Syntaxin 仍处闭合状态时，就已经把 Syntaxin 与 Synaptobrevin-2 的 SNARE 基序 N 端精确对齐、卡拢成一个"模板态"中间体（Jiao et al. 2018, PMID:30540253，单分子光镊观测，命名为"态7"，平衡力约5.1 pN）；随后 Munc13 的 MUN 结构域介入，加速这一模板态向允许 SNAP-25 加入的开放态转化（Ma et al. 2011, PMID:21499244；Yang et al. 2015, PMID:26030875；Wang et al. 2020, PMID:32643828）。2024 年的新证据（Guiberson et al., PMID:38242640）进一步提示 Munc18-1 还具有超出模板功能之外的分子伴侣式稳定器角色，能以浓度依赖方式稳定其他结合搭档（如 Doc2A/B）的蛋白水平。人类 STXBP1 基因的新发杂合突变（单倍剂量不足）是已知最常见的婴儿期发育性癫痫性脑病病因之一，机制上选择性损害抑制性中间神经元的突触强度（Chen & Cai 2020, PMID:32073399）。

## 关键机制

### 分子层：模板机制的核心步骤
1. Munc18-1 以"弓形夹子"结构整体包裹处于**闭合构象**的 Syntaxin-1（Habc 结构域折叠回SNARE基序上，自我抑制）
2. Munc18-1 第 3a 结构域的螺旋发夹，在 Syntaxin 仍闭合的情况下，将其 SNARE 基序的 N 端与 Synaptobrevin-2 的 SNARE 基序 N 端预先卡拢、并列（"模板态"，Jiao et al. 2018 称为"态7"），C 端此时仍保持分离
3. Munc13 的 MUN 结构域以弱亲和力（K_D 35-46 μM）同时接触多个组分，协同加速模板态向 Syntaxin 开放构象转化（25-240倍加速）
4. Syntaxin 完全开放后，SNAP-25 得以加入，完成四螺旋束的完整"拉链"组装（详见 [[SNARE-complex]]）
5. Munc13 同时也直接激活 Munc18-1 本身的催化活性（Wang et al. 2020），是双靶点作用机制

### 细胞层：稳定器功能（2024年新证据）
致病性 Munc18-1 突变除直接损害模板功能外，还会继发性耗竭 Doc2A/B（一种双C2结构域的自发释放钙传感器，与 Syntaxin-1 竞争性结合 Munc18-1），降低其溶解度和突触定位。提示 Munc18-1 以浓度依赖方式稳定多个结合搭档，是一种"一因多果"的分子枢纽（Guiberson et al. 2024）。

### 疾病层：单倍剂量不足如何选择性伤害抑制性突触
人类 STXBP1 基因新发杂合突变（多为 de novo）导致约 40-50% 蛋白剂量丢失（单倍剂量不足，而非显性负效应，据 GeneReviews NBK396561）。小鼠模型证明该剂量减半**选择性**损害抑制性突触：PV 阳性中间神经元突触强度下降约45%，SST阳性中间神经元下降约26%，而这些神经元接收的兴奋性输入不受影响，导致皮层过度兴奋（棘慢波放电增加约40倍）与癫痫样表型（Chen & Cai 2020, PMID:32073399）。这一"E/I失衡"框架与本知识库另一疾病主线（见 [[autism-synaptopathy-ei-balance]]）形成呼应。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| Munc18-1包裹Syntaxin-1闭合构象，SNARE基序被物理藏起 | X射线晶体学（2.6Å） | PMID:10746715（仅摘要） | 高 |
| Munc18-1敲除完全消除神经递质分泌，但突触形态学连接正常建立 | 基因敲除小鼠，形态学+电生理 | PMID:10657302（仅摘要） | 高 |
| Munc13 MUN结构域协同加速闭合复合物向组装能力状态转化25-240倍 | NMR、FRET、突变验证 | PMID:21499244（PMC全文） | 高 |
| MUN结构域独立足以撬开Syntaxin闭合构象 | 重构生化体系 | PMID:26030875（PMC全文） | 高 |
| Munc13直接激活Munc18-1本身的组装催化能力 | 重构体系 | PMID:32643828（PMC全文） | 高 |
| 识别"态7"模板中间体：Munc18-1将SNARE基序N端预先对齐，C端仍分离；平衡力约5.1pN；组装加速约25倍 | 单分子光镊+突变验证 | PMID:30540253（全文开放） | 高 |
| 致病突变继发性耗竭Doc2A/B，降低其溶解度与突触定位 | 生化+突触定位成像 | PMID:38242640（PMC全文） | 中高（新发现，未系统覆盖所有突变） |
| Stxbp1单倍剂量不足选择性损害PV/SST中间神经元突触强度（45%/26%），兴奋性输入不受影响，棘慢波放电增40倍 | 两种独立杂合敲除小鼠系，电生理+EEG+行为学 | PMID:32073399（PMC全文） | 高 |
| STXBP1脑病绝大多数为新发杂合突变，机制为单倍剂量不足；突变类型与表型无清晰对应关系 | 临床遗传学综述 | GeneReviews NBK396561（官方机构来源，全文开放） | 高 |

## 连接

- [[SNARE-complex]] — Munc18-1模板化组装的靶标复合体；本页填补该页长期标注的悬空引用
- [[synaptotagmin]] — 同为SNARE调控蛋白，但作用于组装完成后的钙触发解锁阶段（Munc18-1作用于组装启动阶段）
- [[complexin]] — 同为SNARE调控蛋白，作用于组装完成后的预融合锁定阶段
- [[munc13]] — 直接催化Munc18-1介导的模板态向开放态转化，双靶点机制（打开Syntaxin+激活Munc18-1）
- [[active-zone]] — Munc18-1介导的组装反应发生的特化位点

## 未解问题

- Q-munc18-doc2-contribution：Doc2耗竭与模板功能损伤，哪个是STXBP1脑病表型异质性的主因？
- Q-munc18-template-in-vivo：单分子光镊观测到的"态7"模板中间体，在活细胞拥挤环境中是否同样稳定存在？
- Q-stxbp1-genotype-phenotype-gap：STXBP1突变类型与临床表型为何缺乏清晰对应关系？

## 修订历史

- 2026-07-14 · 创建 · 基于《一把先关上的锁：Munc18-1 如何在"堵住"SNARE的同时，充当组装它的模板》· 初始置信度：高

## 来源文章

- [[2026-07-14-munc18-stxbp1-template-mechanism]]

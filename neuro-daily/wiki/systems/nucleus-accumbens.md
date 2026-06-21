---
title: 伏隔核
slug: nucleus-accumbens
domain: systems
type: region
status: established
confidence: high
created: 2026-08-20
updated: 2026-08-20
revision_count: 1
dimensions: [molecular, cellular, microcircuit, brain-region, behavior, cognition, disease]
related: [dopamine-reward-prediction-error, incentive-salience, hedonic-hotspot, endocannabinoid-system, endogenous-opioid-system, oxytocin, vasopressin, basal-ganglia, ventral-tegmental-area, prefrontal-cortex, amygdala, hippocampal-circuit, actor-critic-brain, social-memory]
prerequisites: [dopamine-reward-prediction-error, synaptic-transmission, basal-ganglia]
opens_questions: [Q-nac-01, Q-nac-02, Q-nac-03]
source_articles: [2026-08-20-nucleus-accumbens-wanting-liking-reward-circuit]
key_sources: ["PMID:25950633", "PMID:31462765", "PMID:30069500", "PMID:39892577", "PMID:42038339", "PMID:8401595", "PMID:17072591"]
---

# 伏隔核 (Nucleus Accumbens, NAc)

> **一句话定义**：腹侧纹状体的核心节点，大脑边缘系统（情感评估）与运动系统（行动执行）的解剖接口；通过D1/D2型中型棘状神经元整合多巴胺（激励显著性）、阿片肽（享乐快感）、内大麻素和催产素等多路信号，计算驱动趋近或回避行为的"值得一试"信号。

## 当前理解

我们现在认为，伏隔核（NAc）不是一个均质的"快乐中枢"，而是一台精密的**动机计算机**：它将来自VTA的多巴胺信号（编码"激励显著性/wanting"）、来自阿片热点和eCB系统的享乐信号（编码"liking/喜欢"）、来自PVN的催产素信号（编码社会奖赏特异性）以及来自PFC/杏仁核/海马/丘脑的认知和情境信息整合起来，通过GABAergic中型棘状神经元（MSN）的输出决定行为驱力。

**最重要的概念分叉**：多巴胺在NAc中产生"wanting"（激励显著性）而非"liking"（享乐快感）。这两个维度在解剖上分离：wanting由VTA→NAc的多巴胺系统驱动，liking由NAc壳区约1mm³的阿片-内大麻素"享乐热点"局域产生（Berridge & Kringelbach 2015, PMID:25950633）。

**D1/D2 MSN功能的修订**：经典模型将D1-MSNs视为奖赏通路，D2-MSNs视为厌恶通路。但2020年光遗传学研究（Soares-Cunha 2020, PMID:31462765）表明，**激活的时程（而非细胞类型）决定行为方向**：两种MSN在短暂激活时都产生奖赏，在持续激活时都产生厌恶（通过共释放不同阿片肽介导）。

## 关键机制

### 解剖分区：核心区 vs 壳区

**NAc核心区（Core）**：位置偏背侧；主要投射到腹侧苍白球和丘脑底核；处理奖赏的运动执行（将"值得一试"转化为行动）；与背侧纹状体的功能连续性更强。

**NAc壳区（Shell）**：包绕核心区；直接投射到下丘脑和脑干；处理情感和动机的计算（"值不值得去追求"）；含有阿片-内大麻素"享乐热点"；接受催产素、奥曲肽等神经肽输入。

**核心细胞类型**：约95%为GABAergic**中型棘状神经元（MSNs）**；约5%为胆碱能中间神经元（CINs，调节MSN的上/下态转换）和其他GABAergic中间神经元。

### D1-MSN vs D2-MSN：时程依赖的行为方向

| 条件 | D1-MSN | D2-MSN | 行为输出 | 机制 |
|------|--------|--------|----------|------|
| 短暂激活（~1秒） | 奖赏 | 奖赏 | 趋近/CPP | MSN→VP(GABA)抑制→VTA DA神经元去抑制 |
| 持续激活（~60秒） | 厌恶 | 厌恶 | 回避 | D1→强啡肽(κ-OR in VTA)；D2→脑啡肽(δ-OR in VP) |

这解释了先前文献矛盾的原因：不同实验范式的激活时程不同，导致表面上相互矛盾的结果（Soares-Cunha 2020）。

### 享乐热点：阿片-内大麻素的耦合

NAc壳区前背侧内侧象限的约1mm³区域是享乐快感的生成位点（大鼠，比例推算人脑约1cm³）：
- µ/δ/κ阿片受体激动剂在此注射→sucrose的"liking"反应翻倍
- CB1R激动剂（包括内大麻素AEA）在此注射→同样增强liking
- **eCB的liking增强依赖内源性阿片信号**：纳洛酮（阿片拮抗剂）共注射完全阻断AEA的liking增强（Mitchell et al. 2018, PMID:30069500）
- 在NAc其他位置，同样的药物效果消失或反转→**解剖位置是享乐门控的关键**

### 多路输入的汇聚

| 输入来源 | 递质/肽 | 功能 |
|---------|---------|------|
| VTA | 多巴胺 | 激励显著性（wanting），RPE信号 |
| PFC（内侧前额叶） | 谷氨酸 | 认知控制，规则更新 |
| 海马 | 谷氨酸 | 情境信息（"此情境通常有奖赏"） |
| 杏仁核BLA | 谷氨酸 | 情感价值（恐惧/奖赏历史） |
| 丘脑旁室核PVT | 谷氨酸 | 线索-奖赏关联，显著性预测 |
| 下丘脑PVN | 催产素 | 社会奖赏特异性门控 |
| 背侧中缝核DRN | 5-羟色胺 | 社会价值调节（方向尚有争议） |
| 蓝斑LC | 去甲肾上腺素 | 新颖性/唤醒调制 |

### 社会奖赏的专用神经化学接口

在NAc（特别是壳区），催产素（OXT）、µ-阿片受体（MOR）和内大麻素（eCB）共同构成社会奖赏的专用计算层：

**µ-阿片受体（MOR）**：正向调节亲社会行为（社会偏好、配对联结维持）；NAc壳区背内侧MOR激活是雌性Prairie田鼠配偶偏好的必要条件；MOR拮抗剂减弱社会新颖性偏好。

**κ-阿片受体（KOR）**：负向调节社会奖赏；激活强啡肽/KOR系统增加社会攻击性、减弱配对联结；社会失败后NAc强啡肽/KOR表达上调（与社会应激后社会回避相关联）。

**内大麻素（eCB）**：社会互动→NAc内AEA和2-AG水平上升；CB1R拮抗阻断社会CPP；配对联结的维持需要CB1R信号（拮抗后增加配偶拒绝）。

**催产素（OXT）**：PVN→NAc投射，OTR激活增强社会互动的奖赏价值；社会失败减少NAc的OTR结合。

**跨系统耦合**：OXT信号可能通过CB1R依赖性机制改变NAc突触可塑性；KOR激活直接减少NAc的多巴胺释放（Borland 2025, PMID:39892577）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| 多巴胺耗竭消除食物seeking但保留liking | NAc 6-OHDA损毁大鼠，orofacial liking reactions | Berridge 系列，综述于PMID:25950633 | 高 |
| NAc壳区享乐热点（µ-opioid→liking翻倍） | 定点微注射+orofacial liking测量，大鼠 | PMID:25950633 (PMC4425246) | 高 |
| eCB liking增强依赖内源性阿片信号 | AEA+纳洛酮联合注射NAc热点，大鼠 | PMID:30069500 (PMC6069591) | 中-高 |
| D1/D2-MSN短暂激活均→奖赏，持续激活均→厌恶 | 光遗传激活+CPP+RTPP，D1/D2-cre小鼠 | PMID:31462765 (PMC7714688) | 高（单实验室，需重复） |
| D1-MSN持续激活厌恶由VTA κ-OR介导 | VTA区域特异性κ-OR拮抗剂逆转厌恶 | PMID:31462765 | 中-高 |
| MOR激活增强而KOR减弱NAc社会奖赏 | Prairie田鼠配对联结模型，受体激动/拮抗 | PMID:39892577 及其综述文献 | 中（主要来自一种动物模型，性别特异性） |
| NAc DBS改善难治性抑郁症（~40%反应率） | 临床DBS研究系统综述 | PMID:37928918 | 中（小样本，开放试验多） |

## 连接

- [[dopamine-reward-prediction-error]] — VTA→NAc多巴胺是incentive salience（wanting）的来源；D1/D2受体是RPE信号的直接靶点；NAc D1-MSN直接通路和D2-MSN间接通路是actor-critic回路的执行臂
- [[incentive-salience]] — NAc是Berridge wanting系统的主要执行位点；多巴胺在此赋予刺激"吸引磁力"
- [[hedonic-hotspot]] — NAc壳区前背侧内侧象限的阿片-eCB热点是liking信号的局域生成位点
- [[endocannabinoid-system]] — CB1R在NAc热点内与µ-OR功能耦合，eCB retrograde信号调节MSN接受的谷氨酸能输入
- [[endogenous-opioid-system]] — µ/κ/δ受体在NAc分别介导社会奖赏增强（MOR）、厌恶信号（KOR/强啡肽）和时程依赖的厌恶（δ-OR in VP，D2-MSN通路）
- [[oxytocin]] — PVN→NAc催产素投射是社会奖赏特异性门控；OTR在NAc壳区激活是配偶偏好的必要条件
- [[basal-ganglia]] — NAc是腹侧纹状体，与背侧纹状体（背侧NAc以前）在解剖和功能上连续；共享D1直接/D2间接通路架构
- [[actor-critic-brain]] — NAc作为Critic（价值估计）和Actor（直接通路D1-MSN执行Go）的关键位点
- [[amygdala]] — BLA→NAc谷氨酸投射传递情感价值；BLA恐惧/奖赏印迹的内容通过此通路影响NAc的动机计算
- [[social-memory]] — NAc计算的社会奖赏信号与CA2社会记忆共同构成"这个个体值得再见"的完整回路
- [[prefrontal-cortex]] — mPFC→NAc谷氨酸投射提供认知控制信号，调节goal-directed vs habitual reward pursuit

## 未解问题

- Q-nac-01（高优先级）：NAc壳区"affective keyboard"在应激环境下从appetitive转为aversive的分子机制？候选：皮质酮通过GR改变MSN的兴奋性阈值？CRF受体调制？
- Q-nac-02（高优先级）：社会孤立如何影响NAc的催产素-阿片-eCB三系统整合？社会孤立诱发的无快感感（anhedonia）中三个系统各自的贡献？
- Q-nac-03（中优先级）：MOR效应在Prairie田鼠中的雌性特异性是否可推广到人类社交差异？雄性NAc中介导配对联结的主要神经化学系统是什么（KOR的抑制还是另外的机制）？

## 修订历史

- 2026-08-20 · 创建 · 基于《伏隔核的奖赏解剖》一文 (#118) · 初始置信度：高

## 来源文章

- [[2026-08-20-nucleus-accumbens-wanting-liking-reward-circuit]]

---
title: 内源性阿片系统（Endogenous Opioid System）
slug: endogenous-opioid-system
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-03
updated: 2026-08-17
revision_count: 2
dimensions: [molecular, synaptic, brain-region, behavior, cognition]
related: [periaqueductal-gray, placebo-analgesia, gate-control-theory, pain-matrix, dopamine-reward-prediction-error, nucleus-accumbens, nac-hedonic-hotspot, incentive-salience]
prerequisites: [gate-control-theory, periaqueductal-gray]
opens_questions: []
source_articles: [2026-08-03-placebo-analgesia-pfc-opioid-circuit]
key_sources: ["PMID:16120776", "PMID:26087681"]
---

# 内源性阿片系统（Endogenous Opioid System）

> **一句话定义**：大脑自产的三类阿片肽（内啡肽、脑啡肽、强啡肽）通过激活μ/δ/κ三类阿片受体，在 PAG-RVM-脊髓回路中执行内源性镇痛，是机体应对急性伤害、应激以及安慰剂效应的核心分子机制。

---

## 当前理解

内源性阿片系统由三个相互关联的成分构成：阿片肽（配体）、阿片受体（信号转导）、以及分布于脑干-脊髓的镇痛回路（效应通路）。

外源性阿片药物（吗啡、可待因、芬太尼等）的作用机制正是模拟内源性阿片肽对这一系统的激活——这也是为什么人类大脑上有阿片受体：不是为了海洛因而进化，而是为了内源性镇痛和应激反应。

---

## 内源性阿片肽：三大家族

| 阿片肽 | 前体蛋白 | 主要合成区域 | 主要受体亲和力 |
|-------|---------|------------|--------------|
| **β-内啡肽（β-Endorphin）** | 前阿黑皮素原（POMC） | 弓形核（下丘脑）、垂体 | μ > δ |
| **脑啡肽（Enkephalins）** | 前脑啡肽原（Proenkephalin） | PAG、脊髓背角、纹状体、边缘系统 | δ ≥ μ |
| **强啡肽（Dynorphins）** | 前强啡肽原（Prodynorphin） | PAG、脊髓、下丘脑、海马 | κ >> μ |
| **内吗啡肽（Endomorphins）** | 未知前体（有争议） | 丘脑、纹状体、脊髓 | μ（高度选择性） |

**功能分化**：
- β-内啡肽：系统性镇痛，应激诱导镇痛（SIA），由弓形核轴突下行到 PAG
- 脑啡肽：局部回路调节，脊髓背角突触前抑制
- 强啡肽：κ受体激活有时**促痛**（产生烦躁、痛觉超敏），在慢性疼痛中可能不利

---

## 三类阿片受体

| 受体 | 基因 | 主要效应 | 外源阿片选择性配体 |
|------|------|---------|----------------|
| **μ（mu）受体** | OPRM1 | 镇痛、欣快感、呼吸抑制、成瘾 | 吗啡、芬太尼（优选） |
| **δ（delta）受体** | OPRD1 | 镇痛（脊髓水平为主）、情绪调节 | 较少临床应用 |
| **κ（kappa）受体** | OPRK1 | 脊髓镇痛、烦躁感、幻觉 | 布托啡诺（部分） |

**信号转导**：三类受体均为 G 蛋白偶联受体（Gi/o）。激活后：
1. 抑制腺苷酸环化酶（降低 cAMP）
2. 激活内向整流 K⁺ 通道（超极化，抑制神经元）
3. 抑制电压门控 Ca²⁺ 通道（减少神经递质释放）

净效果：**降低神经元兴奋性，减少突触传递**——在 PAG GABA 能神经元上激活 μ-OR 后，通过去抑制（disinhibition）机制增加下行镇痛输出。

---

## PAG/RVM 在内源性阿片镇痛中的角色

内源性阿片镇痛的核心解剖回路：

```
弓状核（下丘脑）
    ↓ β-内啡肽
PAG（μ-OR 密集，尤以 vlPAG）
    ↓
RVM（延髓）
OFF-cells 激活 / ON-cells 去抑制
    ↓
脊髓背角
C 纤维和 Aδ 纤维突触前 + 后抑制
    ↓
伤害性信号上行减少
```

**历史实验**（证明内源性阿片的存在）：
- Reynolds（1969）：PAG 电刺激产生类吗啡镇痛
- Yaksh & Rudy（1976）：PAG 内微量注射吗啡产生镇痛
- Hughes et al.（1975）：从猪脑中分离出内源性脑啡肽
- 纳洛酮注入 PAG 阻断刺激诱导镇痛：证明内源性阿片系统的存在

---

## 纳洛酮的药理学与诊断价值

**纳洛酮（Naloxone）**是μ、δ、κ受体的竞争性拮抗剂（对μ亲和力最强），可完全逆转外源阿片引起的呼吸抑制，也是临床阿片过量的急救药物。

在研究中，纳洛酮作为探针用于判断某镇痛效应是否为内源性阿片依赖：

| 镇痛类型 | 纳洛酮效果 |
|---------|-----------|
| 吗啡镇痛 | 完全逆转 |
| 应激诱导镇痛（SIA） | 部分逆转（约50%）|
| 安慰剂镇痛 | 部分逆转（30-50%）|
| 针灸镇痛 | 部分逆转（结论有争议）|
| Nocebo痛觉增强 | 无效（CCK介导，非阿片）|

**安慰剂的纳洛酮敏感性**（Zubieta 2005，Wager & Atlas 2015）：安慰剂镇痛被30-50%逆转，提示：阿片系统是主要介质，但同时存在非阿片成分（可能包括大麻素系统、GABA能抑制、条件学习的脊髓成分）。

---

## 在安慰剂镇痛中的角色

安慰剂镇痛的直接分子证据来自 Zubieta et al.（2005，PMID:16120776）的 PET [¹¹C]卡芬太尼研究：

- 安慰剂条件下，DLPFC、rACC、前岛叶、伏隔核的μ阿片受体结合位点显著减少
- 结合位点减少 = 内源性阿片肽竞争结合 = 内源性阿片释放的**直接测量**
- rACC 的μ-OR 激活量与主观疼痛减轻幅度 r = -0.87（强负相关）

这是迄今为止安慰剂激活内源性阿片系统最直接的神经化学证据，将"安慰剂利用内源性阿片"从推断推进到了实时分子成像层面。

---

## 连接

- [[periaqueductal-gray]] — PAG 是内源性阿片镇痛系统的核心枢纽，μ-OR 密度最高区域之一
- [[placebo-analgesia]] — 安慰剂镇痛通过激活内源性阿片系统实现，是其最有力的人类证据
- [[gate-control-theory]] — 内源性阿片是闸门控制"中枢控制"组件的分子实现
- [[pain-matrix]] — 内源性阿片在痛觉矩阵多个节点（rACC、前岛叶、丘脑）调制疼痛体验
- [[dopamine-reward-prediction-error]] — 伏隔核μ-OR激活连接奖励预期系统，参与安慰剂的学习强化
- [[nucleus-accumbens]] — NAc壳部阿片热点是µ-阿片介导"liking"的关键位点（独立于多巴胺"wanting"）
- [[nac-hedonic-hotspot]] — 内源性阿片系统在NAc的奖赏功能专化亚区
- [[incentive-salience]] — 阿片liking系统与多巴胺wanting系统双重解离的核心概念

---

## 【新增：奖赏功能——阿片热点与liking信号】（2026-08-17）

内源性阿片系统不只参与镇痛，还在NAc壳部前背侧约1mm³的"阿片热点"中产生**享乐性愉悦感（"liking"）**，与多巴胺驱动的激励显著性（"wanting"）截然不同：

- µ-阿片受体激动剂微注射至NAc热点→orofacial liking反应>2倍（大鼠对甜食）
- δ-阿片激动剂和内源性大麻素在同一热点也有liking增强效应
- κ-阿片受体激活（强啡肽，在D1-MSN持续激活时共释放）→产生厌恶感，是liking的对立信号
- 腹侧苍白球（VP）后内侧也含阿片热点，且VP损毁导致liking缺失（产生对甜食的主动厌恶）

这个发现揭示了"快乐"的神经化学比"疼痛"更精细：阿片系统在两个截然不同的情景中（镇痛 vs 享乐）使用相同的受体，但作用于不同的脑区和回路——PAG轴产生镇痛，NAc热点产生liking。

---

## 修订历史

- 2026-08-03 · 创建 · 基于《当大脑相信治愈》文章（#102），建立安慰剂镇痛的分子机制背景
- 2026-08-17 · 修订 rev2 · 基于《大脑的欲望引擎》（文章#116）· 新增奖赏功能小节：NAc阿片热点产生liking，独立于多巴胺wanting；κ-阿片（强啡肽）的厌恶效应；VP阿片热点；新增 related: nucleus-accumbens, nac-hedonic-hotspot, incentive-salience

---

## 来源文章

- [[2026-08-03-placebo-analgesia-pfc-opioid-circuit]]
- [[2026-08-17-nucleus-accumbens-wanting-liking-social-reward]]

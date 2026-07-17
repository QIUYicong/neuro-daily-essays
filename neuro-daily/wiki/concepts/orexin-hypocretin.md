---
title: 食欲素（下丘脑泌素）与发作性睡病
slug: orexin-hypocretin
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-10
updated: 2026-07-18
revision_count: 3
dimensions: [molecular, cellular, microcircuit, brain-region, whole-brain-network, disease]
related: [ascending-arousal-system, flip-flop-switch-sleep-wake, neuromodulator-systems, rem-sleep, disorders-of-consciousness, amygdala, oxytocin]
prerequisites: [neuromodulator-systems, synaptic-transmission]
opens_questions: [Q-orexin-gene-therapy-timeline, Q-orexin-NT2-conversion]
source_articles: [2026-08-10-ascending-arousal-system-brainstem-wakefulness, 2026-10-15-narcolepsy-type1-orexin-autoimmune-flipflop, 2026-07-18-oxytocin-amygdala-cataplexy]
key_sources: ["PMID:41076550", "PMID:35878679", "PMID:21280045", "PMID:37188663", "PMID:30232458", "PMID:26721620", "PMID:23739970", "PMID:42449131"]
---

# 食欲素（下丘脑泌素）与发作性睡病 (Orexin/Hypocretin & Narcolepsy)

> **一句话定义**：食欲素（Orexin-A/B，又称下丘脑泌素Hypocretin-1/2）由外侧下丘脑约8万个神经元产生，是上行激活系统的"总指挥"——不直接激活皮层，而是通过兴奋LC/DRN/TMN/PPT等所有激活核团来稳定清醒状态；食欲素神经元的免疫介导性选择性丢失导致1型发作性睡病。

## 当前理解

### 食欲素的生理功能

食欲素神经元位于外侧下丘脑（LH）及穹窿旁区，投射至所有主要AAS核团（LC/DRN/PPT-LDT/TMN）以及基底前脑和皮层。其特征放电模式：清醒时持续激活，NREM和REM睡眠均保持沉默。

**食欲素的核心功能是状态稳定，而非状态启动**：
- 清醒时激活→增强所有其他激活核团的放电→增加清醒状态的稳定性
- 缺失时→翻转开关失去稳定化力量→状态切换阈值降低→清醒突然坍塌为REM

两种受体：OX1R（对OxA高亲和力）和OX2R（对OxA和OxB均高亲和力），均为Gq偶联GPCR，产生兴奋性突触后效应。

### 1型发作性睡病（NT1）：食欲素缺失的自然实验

NT1是食欲素神经元被T细胞介导的自身免疫选择性摧毁的结果（详见 [[narcolepsy]]）：

**关键数据**：
- 尸检：约95%外侧下丘脑食欲素神经元丢失
- CSF食欲素-A（Hcrt-1）：>90%患者 ≤110 pg/mL（诊断阈值，正常 >200 pg/mL）
- 遗传易感性：82–99%患者携带HLA-DQB1*06:02等位基因（携带者风险升高251倍）

**直接免疫证据（Latorre et al. 2018, Nature）**：
- 19/19 NT1患者血液中检测到靶向食欲素神经元自身抗原的CD4+ T细胞
- 多克隆，靶向多表位，HLA-DR限制；特定克隆型跨患者复现
- 脑脊液中也检测到食欲素特异性CD8+ T细胞

**NT1遗传架构（Ollila et al. 2023, Nat Commun，6073例GWAS）**：
- 除HLA-DQB1*06:02外，发现13个新风险位点
- 核心位点：PRF1（穿孔素，CD8+细胞毒性执行者）、CD207（树突状细胞病毒识别）、IFNAR1（I型干扰素受体，H1N1感染后上调）
- TCR偏倚：TRAJ*24、TRAJ*28、TRBV*4-2 链用频率异常

**临床表现（与神经机制对应）**：
| 症状 | 神经机制 |
|------|---------|
| 日间过度嗜睡 | 翻转开关清醒谷谷壁坍塌，随机噪声触发意外入睡 |
| 猝倒（情绪触发肌无力） | 正面情绪/奖赏→中央杏仁核（CeA）催产素受体阳性GABA能神经元激活→抑制脑干抗猝倒区域（vlPAG/LPT/LC/DR）→SLD失抑制→REM肌张力弛缓回路被误激活（详见 [[amygdala]]、[[oxytocin]]，2026-07-18更新） |
| 入睡期幻觉 | REM的视觉梦境溢出至半清醒状态 |
| 睡眠瘫痪 | REM肌张力弛缓延迟恢复至清醒状态 |

**猝倒电路与食欲素的拮抗关系（2026-07-18新增）**：Burgess et al.（2013, PMID:23739970，开放全文）首次用因果损毁实验证明，中央杏仁核（CeA）中>90%投射至vlPAG/LPT的神经元为GABA能，双侧CeA损毁使食欲素敲除小鼠的跑轮诱发猝倒减少58%、跑轮+巧克力诱发猝倒减少42%，且不影响正常REM睡眠本身——这说明CeA的抑制性输出与食欲素的兴奋性输出，正常情况下在vlPAG/LPT等区域相互拮抗，食欲素丢失打破了这一平衡。Mahoney et al.（2026, PMID:42449131，摘要级，全文未读）进一步将CeA这一抑制性输出的分子信使精确到催产素：CeA中表达催产素受体的神经元亚群是被正性情绪/奖赏（不仅是社交，也包括如巧克力等非社交奖赏）招募的具体细胞群体。

### 治疗前景

**现有治疗**：莫达非尼（非特异性促觉醒）、羟丁酸钠（改善猝倒）

**针对食欲素受体的靶向治疗**：
- **Danavorexton (TAK-925)**：选择性OX2R激动剂，2024年多中心II/III期试验：维持清醒测试（MWT）改善11.1分（超过莫达非尼）
- **ALKS 2680**：口服OX2R激动剂，Phase 2试验进行中

**前沿策略**：
- AAV载体介导前体食欲素基因治疗（血脑屏障穿越+靶向LH表达）
- 干细胞来源食欲素神经元移植（动物模型效力约60%）

**对照**：双食欲素受体拮抗剂（DORAs，如lemborexant）用于治疗失眠——通过拮抗食欲素受体促进睡眠，与NT1治疗方向相反，体现了食欲素系统的双向干预潜力。

## 关键证据

| 研究 | 发现 | 强度 |
|------|------|------|
| Rauf et al. 2025, 综述 | NT1中95%食欲素神经元丢失；HLA-DQB1*06:02 | 高（基于多项研究） |
| Danavorexton 2024试验 | MWT改善11.1分 | 高（Phase 2/3 RCT） |
| 动物基因敲除模型 | 食欲素缺失→发作性睡病表型 | 非常高（因果确立） |
| CeA GABA能神经元→vlPAG/LPT/LC/DR；双侧CeA损毁减少猝倒58%/42%（Burgess 2013, PMID:23739970） | 顺/逆行示踪+损毁+EEG/EMG，食欲素KO小鼠 | 高（开放全文） |
| CeA催产素受体阳性神经元是猝倒的分子-细胞开关，被社交与非社交奖赏共同激活（Mahoney 2026, PMID:42449131） | 药理/化学遗传学/光遗传学，食欲素缺失小鼠 | 中（摘要级，全文未读，单一实验室新发现） |

## 修订历史

| 版本 | 日期 | 变化 | 来源文章 |
|------|------|------|---------|
| rev1 | 2026-08-10 | 初始页面；食欲素生理/NT1病理/治疗前景 | #109 |
| rev2 | 2026-10-15 | 补充NT1自身免疫直接证据（Latorre 2018: 19/19 CD4+ T细胞）；完整GWAS遗传架构（Ollila 2023, 13新位点, PRF1/CD207/IFNAR1/TCR偏倚）；猝倒回路机制细化（VMM路径）；CSF Hcrt-1诊断数据精确化；添加 [[narcolepsy]] 交叉引用 | #175 |
| rev3 | 2026-07-18 | 猝倒电路描述由笼统的"杏仁核→VMM"修正为具体解剖通路（CeA GABA能神经元→vlPAG/LPT/LC/DR，Burgess 2013）+ 2026年新确立分子信使（催产素/CeA催产素受体阳性神经元，Mahoney 2026，摘要级）；新增"猝倒电路与食欲素的拮抗关系"小节；关键证据表新增2行；related新增amygdala、oxytocin；dimensions新增microcircuit | #201 |

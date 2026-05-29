---
title: 电压门控钙通道
slug: voltage-gated-calcium-channels
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-06-01
updated: 2026-06-01
revision_count: 1
dimensions: [molecular, cellular, synaptic]
related: [synaptic-transmission, synaptotagmin, active-zone, SNARE-complex, ltp, btsp, dendritic-computation, nmda-receptor, action-potential, camkii]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: [Q-vgcc-nanodomain-universal, Q-cav1-cav13-functional-split, Q-btsp-ltype-vs-nmda]
source_articles: [2026-06-01-voltage-gated-calcium-channels]
key_sources: ["PMID:21746798", "PMID:31064106", "PMID:22183436", "PMID:25674049", "PMID:32799605", "PMID:29723500"]
---

# 电压门控钙通道（Voltage-Gated Calcium Channels, VGCCs）

> **一句话定义**：电压门控钙通道是一类能感应膜电位变化并允许Ca²⁺选择性内流的离子通道蛋白家族，由10个基因编码、分化为CaV1（L型）、CaV2（P/Q、N、R型）和CaV3（T型）三大亚家族，通过亚细胞定位的差异，分别在突触前终末实现毫秒级递质释放、在树突驱动秒级突触可塑性、在胞体与核触发小时至天级的基因调控。

## 当前理解

我们现在认为，电压门控钙通道不是单一的"钙进入通道"，而是一套**多地点、多时间尺度的钙信号分配系统**。同一种离子（Ca²⁺），通过亚型特化和精确的蛋白质相互作用网络，在三个不同的亚细胞区室中被分别利用，执行截然不同的功能：

1. **突触前终末**（CaV2.1/P/Q型，CaV2.2/N型）：纳米域耦合（<30 nm）使Ca²⁺内流立即触发SNARE拉合→囊泡融合→递质释放，时间精度在亚毫秒级（Catterall 2011；PMC3140680）
2. **树突**（CaV1.3/CaV1.2，L型）：持续开放驱动平台电位，联合NMDA受体提供BTSP所需的秒级Ca²⁺内流（Bittner 2017；PMC7289271）
3. **胞体/细胞核**（CaV1.2，L型）：核钙信号链（CaV1.2→CaM→CaMKIV→CREB磷酸化）激活基因转录，驱动晚期LTP；C末端蛋白水解片段可直接进入核作为转录调控因子（Catterall 2011；PMC3140680）

## 关键机制

### 1. 结构基础

所有VGCCs的核心是**α1亚基**（约2000 aa）：
- 4个同源重复域（I-IV），每域含6个TM段（S1-S6）
- **S4**（电压传感器）：正电荷残基（Arg/Lys）每3位一个，膜去极化时旋转/平移驱动通道开放
- **S5-S6孔道**：每个域各贡献1个Glu残基形成Ca²⁺选择性滤器
- **域II-III胞质环（synprint site）**：结合SNARE蛋白和Synaptotagmin，预招募释放机器
- **C末端**：CaM结合基序（IQ样基序介导易化，CBD介导失活）；可被蛋白酶切割产生核转位片段

**辅助亚基**：β（胞质，调控动力学/表达）、α2δ（胞外，促进运输）、γ（肌肉为主）

### 2. 三大亚家族

| 亚家族 | 成员 | 激活阈值 | 主要位置 | 核心功能 |
|--------|------|----------|----------|----------|
| CaV1（L型） | CaV1.1–1.4 | 高（约-30 mV，CaV1.3约-50 mV） | 树突、胞体 | LTP、BTSP平台电位、基因表达 |
| CaV2（P/Q、N、R型） | CaV2.1/2.2/2.3 | 高 | 突触前活动区 | 递质释放、短时程突触可塑性 |
| CaV3（T型） | CaV3.1–3.3 | 低（约-60 mV） | 广泛 | 节律性放电、振荡 |

### 3. 纳米域耦合：突触前释放的速度秘密

CaV2.1（P/Q型）和CaV2.2（N型）在突触前活动区通过以下机制实现精确快速释放（Eggermann et al. 2011；PMC3617475；Wang & Augustine 2015；PMC4306312）：

- **物理近距离**：通道-Synaptotagmin距离10–30 nm（vs 微域耦合的>100 nm）
- **证据**：BAPTA（快螯合剂）完全阻断释放，但EGTA（慢螯合剂，80 mM）不影响——表明Ca²⁺到达传感器的时间极短，EGTA来不及拦截
- **量化**（颈静脉复合体）：成熟突触~23 nm，约9通道；未成熟突触~61 nm，需N+P/Q型协同
- **Synprint-SNARE预组织**（Mochida 2019；PMC6539076）：通道II-III环与syntaxin-1A、SNAP-25、Synaptotagmin-1直接结合，Ca²⁺进入前已建立释放复合体

**发育性精确化**（Wang & Augustine 2015；PMC4306312）：
- P8-12（微域，N+P/Q型，61 nm，峰Ca²⁺~35 μM）→ P16-18（纳米域，纯P/Q型，23 nm，峰Ca²⁺~56 μM）
- 转变调控分子：Septin-5（septin-5 KO→提前纳米域化）
- 纳米域化使Ca²⁺触发传感器时间提前约410 μs

### 4. L型通道与LTP/BTSP（树突-胞体层）

**BTSP中的贡献**（Bittner et al. 2017；PMC7289271）：
- 平台电位依赖NMDA受体（APV→降低~84%的BTSP）和L型通道（尼莫地平→降低~73%的BTSP）协同
- CaV1.3（低阈值）可能在树突去极化早期开放，为平台电位提供正反馈

**TBS-LTP（早期，局部蛋白质合成依赖）**（Sridharan et al. 2020；PMC7515572）：
- CaV1.2条件敲除→TBS-LTP受损（128% vs 166%，60分钟后，p=0.003）
- 机制：CaV1.2→mTORC1激活→局部蛋白质合成（非转录依赖）

**晚期LTP（转录依赖）**（Kroker 2011；PMID:21640734，摘要）：
- 晚期LTP等量依赖NMDA受体和L型VDCC
- 机制：见下节核钙信号

### 5. 核钙信号：活动历史写入基因组

（Catterall 2011；PMC3140680；Bengtson & Bading 2012；PMID:22351065，摘要）

**信号链**：
突触活动→L型通道开放（CaV1.2）→Ca²⁺内流→胞质CaM激活→CaM易位进核→激活CaMKIV→磷酸化CREB（Ser133）→目标基因转录（BDNF、c-fos等）→新蛋白质合成→长期突触结构改变

**直接核调控**：CaV1通道C末端被蛋白酶（类钙蛋白酶）切割的片段可直接进入核，调控一组特定基因的转录

### 6. G蛋白调控：突触前抑制机制

（Mochida 2019；PMC6539076）

Gi/Go偶联受体激活→Gβγ亚基释放→结合CaV2通道N末端+I-II连接环+C末端→"电压依赖性抑制"（VDI）：
- 通道激活需更强去极化
- 强突发放电（burst）可通过强正电位"打开"这种抑制（prepulse relief）
- 覆盖受体：μ-阿片受体、多巴胺D2、GABA-B、腺苷A1等

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 纳米域耦合（<30 nm）：BAPTA阻断但EGTA不阻断快速同步释放 | 突触前微注射+电生理记录 | PMID:22183436 (PMC3617475) | 极高 |
| 颈静脉复合体成熟突触：23 nm，约9通道，只需P/Q型 | 超分辨成像+遗传操控+模拟 | PMID:25674049 (PMC4306312) | 高 |
| Septin-5调控微域→纳米域发育转变 | Septin-5 KO小鼠表型 | PMID:25674049 (PMC4306312) | 高 |
| CaV1.2缺失→TBS-LTP受损（128% vs 166%）；mTOR机制 | 条件敲除小鼠+脑片电生理 | PMID:32799605 (PMC7515572) | 高 |
| BTSP：尼莫地平（L型阻断）降低约73%的BTSP | 在体/离体药理 | PMID:28883072 (PMC7289271) | 高 |
| Synprint位点结合SNARE蛋白和Syt1 | 共沉淀、点突变、功能实验 | PMID:31064106 (PMC6539076) | 高 |
| CaV1 C末端片段进入核调控转录 | 细胞分级分离+报告基因实验 | PMID:21746798 (PMC3140680) | 中（综述）|

## 连接

- [[synaptic-transmission]] — CaV2.1/2.2是突触前递质释放的触发器
- [[synaptotagmin]] — Ca²⁺传感器Syt1通过C2B域与CaV2的synprint位点结合，实现预组织
- [[active-zone]] — 活动区是CaV2.1（P/Q型）纳米域耦合的物理平台
- [[SNARE-complex]] — CaV2通道synprint位点直接结合SNARE蛋白
- [[btsp]] — CaV1.3/1.2（L型）为BTSP触发所需的树突平台电位提供持续Ca²⁺内流
- [[ltp]] — CaV1.2参与早期LTP（mTOR途径）和晚期LTP（核CaM→CREB途径）
- [[dendritic-computation]] — L型通道参与树突Ca²⁺棘波（平台电位）的维持
- [[nmda-receptor]] — NMDA受体与L型通道在BTSP/LTP中协同：两种Ca²⁺来源的协作
- [[action-potential]] — 动作电位提供去极化触发CaV2通道开放

## 未解问题

- Q-vgcc-nanodomain-universal：纳米域耦合（<30 nm）是否在大脑所有中枢突触中普遍存在？大多数"普通"小型突触的实际耦合距离尚待直接测量
- Q-cav1-cav13-functional-split：CaV1.2 vs CaV1.3在树突中的精确功能分工是什么？低阈值的CaV1.3是否在亚阈值去极化时发挥独特作用？
- Q-btsp-ltype-vs-nmda：BTSP中L型通道（~73% BTSP降低）和NMDA受体（~84%）的贡献机制：两者是否相互依赖，各自的独立贡献是什么？

## 修订历史

- 2026-06-01 · 创建 · 基于《神经元的三重钙门》一文 · 三大亚家族与三地点功能首次系统整合 · 初始置信度：高

## 来源文章

- [[2026-06-01-voltage-gated-calcium-channels]]

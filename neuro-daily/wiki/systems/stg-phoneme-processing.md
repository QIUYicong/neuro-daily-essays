---
title: 颞上回音素计算
slug: stg-phoneme-processing
domain: systems
type: mechanism
status: mainstream
confidence: high
created: 2026-08-20
updated: 2026-08-23
revision_count: 2
dimensions: [brain-region, systems, cognition, whole-brain-network]
related: [auditory-cortex, auditory-dual-stream, cortical-speech-entrainment, phoneme-categorical-perception, language-network, speech-production-circuit, superior-temporal-sulcus, broca-area, speech-comprehension-prediction, wernicke-area]
prerequisites: [auditory-cortex, auditory-dual-stream, tonotopy]
opens_questions: [Q-stg-01, Q-stg-02, Q-stg-03]
source_articles: [2026-08-20-stg-phoneme-speech-perception]
key_sources: ["PMID:34672685", "PMCID:PMC9447996", "PMID:24482117", "PMID:22426255", "PMCID:PMC3364513", "PMID:38805278", "PMID:22723684", "PMID:29891730", "PMID:27846209"]
---

# 颞上回音素计算 (STG Phoneme Processing)

> **一句话定义**：颞上回（STG）通过非线性范畴化、说话者归一化、语境修复和时间标记提取四大核心计算，在局部（单位点）编码声学-音素特征、在群体（跨位点空间模式）编码音素身份，将连续可变的声学输入映射为离散稳定的音素表征。

## 当前理解

我们现在认为，颞上回（STG）是听觉皮层（HG/A1）与语言语义网络（MTG/ATL）之间的核心"声学-语言转换器"，执行的计算远比简单的声学特征检测复杂——它是一套**主动的、具有预测性的非线性解码机制**（Bhaya-Grossman & Chang 2022，PMID:34672685）。

STG 内部存在从后到前的功能梯度：
- **pSTG**（后部）：检测声音起始（onset）事件，标记词/短语边界
- **mSTG**（中部）：追踪包络变化率峰值（peakRate），对齐音节边界与元音起始
- **aSTG/STS**（前部/颞上沟）：对语音可理解性有最强响应，参与视听整合

这一梯度不是严格串行，而是并发处理网络中的功能倾向性分布。

## 关键机制

### 四大核心计算

**1. 非线性范畴化**
沿/ba/→/da/→/ga/声学连续谱，STG群体响应并非线性渐变，而是在范畴边界处发生非线性跳跃，镜像人类的范畴感知。局部（单电极）可能呈线性调谐，群体（多电极）呈现范畴化。

**2. 说话者归一化**
STG对元音的神经编码在不同说话者之间是归一化的——来自男/女/儿童说话者的同一元音在STG中激活高度相似的群体模式。这与初级听觉皮层（A1）不同，A1对声学绝对值敏感。

**3. 语境修复与预测编码**（预测性激活）
当噪声掩蔽某个音素时，对应音素的STG群体活动仍然出现，且发生在噪声窗口出现前约300ms——说明STG依靠词汇/语义上下文提前预测下一个音素，而非等待声学信号再处理。更根本地，STG/STS 是整个语音理解预测-误差回路的核心计算节点：IFG（额下回）从高层级向 STG 发送"预测下一个词/音素"的信号（时序上先于STG响应，Sohoglu & Davis 2012，PMID:22723684），STG 只上报**预测误差**。正确先验使 STG 信号**减弱**（误差减小），误感知时 STS 预测误差信号**更弱**（纠正不足，Blank et al. 2018，PMID:29891730）。（完整预测编码框架见 [[speech-comprehension-prediction]]）

**4. 时间标记提取**
mSTG对声学包络的"peakRate事件"（包络变化率最大时刻）选择性响应，这些时刻对应元音起始和音节边界，提供分割连续言语流的时间锚点。

### 双尺度表征

- **局部尺度**（单个ECoG电极，~2mm²）：选择性响应音素特征组（发音方式、发音部位、送气性等），而非单个音素
- **群体尺度**（多电极空间激活模式）：可准确解码音素身份（英语40+音素均可识别）

这种设计允许保留范畴内的声学灵敏度（局部），同时实现范畴间的区分（群体）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| STG局部编码音素特征，群体模式编码音素身份 | ECoG直接记录，英语40+音素解码 | PMID:24482117（Mesgarani 2014） | 高 |
| 四大核心计算（范畴化/归一化/修复/时间标记） | ECoG合成刺激+自然语音，综述整合 | PMID:34672685（Bhaya-Grossman 2022） | 中-高 |
| 语境修复的神经时间线（提前300ms） | ECoG，噪声掩蔽音素实验 | PMID:34672685 引用 Leonard et al. | 中-高 |
| pSTG起始检测/mSTG peakRate | ECoG功能梯度分析 | PMID:34672685综述 | 中-高 |
| STG振荡相位锁定音素频率统计 | fMRI+振荡分析，预注册研究 | PMID:38805278（Ten Oever 2024） | 中 |
| IFG 对先验知识的响应早于 STG（自上而下方向） | EEG/MEG 同步，毫秒级时序 | PMID:22723684（Sohoglu & Davis 2012） | 高 |
| 正确先验使 STG 响应减弱（预测误差最小化） | MEG/EEG + fMRI 两项独立实验 | PMID:22723684 + PMID:26957596 | 高 |
| STS 编码预测误差而非增强信号 | fMRI MVPA + 计算模型比较 | PMID:27846209（Blank & Davis 2016） | 中-高 |
| 误感知时 STS 预测误差信号更弱（非更强） | fMRI RSA，诱导误感知设计 | PMID:29891730（Blank et al. 2018） | 高 |

## 连接

- [[auditory-cortex]] — STG（非初级皮层）的上游：HG/A1 提供初步声学特征
- [[auditory-dual-stream]] — STG 的输出分叉为腹侧（词义）和背侧（发音运动）两流
- [[cortical-speech-entrainment]] — 实现STG时间窗口采样的振荡机制
- [[phoneme-categorical-perception]] — 范畴化计算的详细机制
- [[language-network]] — STG是听觉-语言双流的核心节点
- [[speech-production-circuit]] — 背侧流效应副本回路与STG的监控功能
- [[superior-temporal-sulcus]] — STS是STG腹侧面，负责语音可理解性和视听整合
- [[speech-comprehension-prediction]] — STG/STS 在预测编码框架中的核心角色（预测误差计算节点）
- [[wernicke-area]] — 韦尼克区（pSTG/BA22）是STG的后部区域；功能是音韵形式缓冲而非理解中枢

## 未解问题

- Q-stg-01：STG皮层振荡是主动预测（internal clocking）还是被动声学驱动（stimulus tracking）？（高优先级）
- Q-stg-02：范畴化主要来自STG内竞争抑制，还是词汇反馈的自上而下调控？（中优先级）
- Q-stg-03：四大计算在解剖上能否解离——分别损毁后分别失效？（中优先级）

## 修订历史

- 2026-08-20 · 创建 · 基于《声音之刀》文章#102 · 初始置信度：高 · 整合Bhaya-Grossman & Chang 2022综述和Mesgarani 2014 ECoG实验证据
- 2026-08-23 · 修订 · 基于文章#121《从声波到意义》· 新增"语境修复与预测编码"段落；新增5条预测编码证据行（Sohoglu & Davis 2012/2016；Blank & Davis 2016/2018）；related新增speech-comprehension-prediction、wernicke-area；连接新增2个节点；key_sources新增3个PMID

## 来源文章

- [[2026-08-20-stg-phoneme-speech-perception]]

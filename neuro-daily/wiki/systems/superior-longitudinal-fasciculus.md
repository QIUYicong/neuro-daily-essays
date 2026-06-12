---
title: 上纵束（SLF）系统
slug: superior-longitudinal-fasciculus
domain: systems
type: structure
status: established
confidence: high
created: 2026-06-13
updated: 2026-06-12
revision_count: 2
dimensions: [brain-region, whole-brain-network, cognition, behavior, molecular]
related: [arcuate-fasciculus, language-network, broca-area, wernicke-area, hemispatial-neglect, speech-production-circuit, dorsal-language-stream, stg-phoneme-processing, conduction-aphasia, corpus-callosum, inferior-fronto-occipital-fasciculus, foxp2-language-gene, cntnap2-language-circuit, language-lateralization]
prerequisites: [language-network, arcuate-fasciculus]
opens_questions: [Q-SLF-01, Q-SLF-02, Q-SLF-03, Q-SLF-04]
source_articles: [2026-06-13-superior-longitudinal-fasciculus-branches-attention-language, 2026-06-12-cntnap2-foxp2-language-wiring]
key_sources: ["PMID:17431404", "PMID:23107648", "PMID:37051488", "PMID:33792674", "PMID:22422148", "PMID:26377454", "PMID:24951631", "PMID:21937035", "PMID:34288240", "PMID:34218465", "PMID:18987363", "PMID:21765815"]
---

# 上纵束（SLF）系统 (Superior Longitudinal Fasciculus System)

> **一句话定义**：上纵束（SLF）是大脑最大的额叶-顶叶白质联合系统，由至少三条功能截然不同的平行亚束构成——SLF I（额上回-顶上小叶，运动程序化）、SLF II（背外侧前额叶-角回，空间注意，右侧化）、SLF III（额下回/运动前区-缘上回，语音-运动映射，左侧化）——与弓状束（AF，颞叶-额叶，音韵传输）共同构成背侧语言流与空间注意回路的白质骨架。

## 当前理解

我们现在认为，上纵束并非一条均匀的"额顶联络纤维"，而是一套**内部功能高度分化的并行白质亚束系统**，其功能多样性完全由各亚束的皮层靶点（终止区）决定，而非纤维本身的固有属性（Dick & Tremblay 2012，PMID:23107648）。

**四个组成部分**（按 Makris/Schmahmann 系统 + Martino 等 2013 解剖验证）：

**SLF I（额上回/SMA ↔ 顶上小叶 BA5/7）**：连接补充运动区与顶上小叶，参与上肢运动序列规划和姿势控制。在运动程序化和工具使用的神经网络中有重要地位。单独 SLF I 损伤的临床文献相对稀少。

**SLF II（背外侧前额叶 BA9/46 ↔ 角回/缘上回 / 顶下小叶）**：空间注意系统的核心皮层间通路，将前额叶的自上而下注意控制传至顶叶，并将顶叶的显著性信号反馈至额叶。在右半球明显粗于左半球（右侧化），遗传力 h²≈0.68（Budisavljevic 2015，PMID:26377454）。**右 SLF II 损伤 → 半侧空间忽略**，这是 SLF 功能分化最清晰的临床证据之一。

**SLF III（额下回 BA44/45 + PMv ↔ 缘上回 SMG BA40）**：语音-运动映射界面的传输通路。缘上回（SMG）是语音感知-输出界面节点（音韵表征→发音程序化），额下回 BA44 是 Merge/句法操作节点。SLF III 连接这两个节点，使语音音素序列可被程序化为发音动作。**左 SLF III 损伤 → 言语运动停滞（anarthria）/ 口面失用**。随年龄左侧化，h²≈0.55（Budisavljevic 2015）。

**弓状束（AF）**：从颞叶 pSTG/Spt 弧形延伸至额叶 BA44/前运动皮层。是 SLF 系统的"颞叶延伸"，专责音韵时序传输（phonological loop 传输段）。在一些命名系统中被列为 SLF IV，但因其进入颞叶的独特解剖走行和特定的功能分离（AF 损伤→音韵错语，SLF III 损伤→运动停滞），通常单独记载（见 `arcuate-fasciculus.md`）。

**命名现状**（Porto de Oliveira 2021，PMID:34218465）：文献中至少有 12 种不同的 SLF/AF 命名系统，仅有部分对应，是白质研究的主要障碍之一。本知识库采用 SLF I/II/III + AF 分开记录的方案。

## 关键机制

### 皮层靶点决定功能

```
SLF I：  [额上回/SMA]         ←→  [顶上小叶 BA7]
           运动序列规划               身体图式/姿势
         → 功能 = 上肢运动程序化

SLF II： [背外侧前额叶 BA9]   ←→  [角回 AG / 顶下小叶]
           自上而下注意控制           空间显著性标记
         → 功能 = 空间注意额顶调控（右侧化）

SLF III：[额下回 BA44 + PMv]  ←→  [缘上回 SMG BA40]
           句法/发音计划              语音感知-输出界面
         → 功能 = 语音-运动映射（左侧化）

AF：     [额下回 BA44 + PMC]  ←→  [pSTG/Spt]
           句法/发音计划              音韵短期记忆缓冲
         → 功能 = 音韵时序传输（左侧化）
```

### SLF III vs AF 的临床双解离（Lu et al. 2021）

直接电刺激（DCS）是最强的人类体内功能定位证据：
- 刺激 **SLF III/腹侧运动前白质** → **anarthria**（发声动作程序化彻底失败，无声）
- 刺激 **AF 白质** → **音韵性错语**（发声可进行，但音素序列出错）
- 这一双解离在英语/法语/普通话患者中均一致（PMID:33792674，PMC:PMC8453410）

### 右侧 SLF 与半侧忽略的代偿模型

右半球 SLF II 体积大于左侧，在右脑卒中后损失更严重，导致注意向右偏移（忽略左侧）。同时，右半球 SLF（包括 AF）体积在左脑卒中后预测失语恢复速度（Forkel 2014，PMID:24951631），提示右半球 SLF 可通过激活右侧镜像语言区参与语言代偿。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| SLF III DCS → anarthria；AF DCS → 音韵错语（功能双解离） | 多中心清醒开颅 DCS，70+ 病例，三种语言 | PMID:33792674（PMC8453410）| 高 |
| SLF II 右侧化，遗传力 h²≈0.68；SLF III 随年龄左侧化，h²≈0.55 | 双胞胎设计纵向 DTI | PMID:26377454（Budisavljevic 2015）| 中高 |
| 右 AF 体积预测左脑卒中失语恢复（28%→57%） | 16 例卒中患者纵向 DTI+失语评分 | PMID:24951631（Forkel 2014）| 中（n 小，待复现）|
| 左 AF/SLF III DKI 轴向峰度低 → 音韵记忆/外语学习效率高 | DKI 微结构+语言能力测试 | PMID:34288240（PMC8449104）| 中 |
| 双侧 AF/SLF 先天性缺失，语言接近正常；腹侧束代偿 | 单例 12 岁早产儿多种 DTI 分析 | PMID:21937035（PMC3259257）| 中（单例，极端损伤）|
| SLF II/III 在发育期侧化方向相反，提示不同发育遗传机制 | 纵向 DTI 跨年龄组 | PMID:26377454（Budisavljevic 2015）| 中高 |

## 连接

- [[arcuate-fasciculus]] — AF 是 SLF 系统的颞叶延伸，与 SLF III 共享 BA44 额叶端但有不同起点和功能
- [[language-network]] — SLF III 和 AF 是背侧语言流的白质骨架
- [[dorsal-language-stream]] — SLF III/AF 是背侧流的具体化；SLF II 是空间注意网络的具体化
- [[hemispatial-neglect]] — 右 SLF II 损伤是半侧空间忽略最重要的白质相关性之一
- [[broca-area]] — BA44 同时是 SLF III 和 AF 的额叶端，是两条束的"汇聚枢纽"
- [[stg-phoneme-processing]] — pSTG 是 AF 的颞叶起点（而非 SLF III 的起点）
- [[conduction-aphasia]] — AF 直接段断路的临床表现，区别于 SLF III 损伤的言语运动停滞
- [[speech-production-circuit]] — SLF III 传输语音-运动映射信号进入 DIVA 前馈回路
- [[corpus-callosum]] — 右半球 SLF 参与失语代偿，可能通过胼胝体与左侧增强通信

## SLF III 左侧化的分子候选机制（emerging）

基于 2026-06-12 的文章（#171），目前最合理的分子候选轴是：

**FOXP2 → CNTNAP2 → 左侧额叶皮层连接优势**

- FOXP2 在发育期人脑额叶皮层直接转录激活 CNTNAP2（Vernes 2008）
- CNTNAP2 mRNA 在人类（非黑猩猩）发育期额叶皮层呈左 > 右的不对称表达（Alarcón 2008）
- FOXP2 还直接调控 264+ 轴突导向相关基因，包括 SLIT/ROBO 通路成员（Vernes 2011）

**但直接因果链未经实验验证**：CNTNAP2 → SLF III 左侧化的条件性敲除实验尚未完成；这是 Q-SLF-03 仍然"开放"的原因。状态：emerging（有候选机制，待实验验证）。

详见 wiki 页面：[[foxp2-language-gene]] 和 [[cntnap2-language-circuit]]

## 未解问题

- Q-SLF-01：猕猴/黑猩猩中 SLF 亚束是否有功能对应的同源通路？侧化程度如何比较？
- Q-SLF-02：SLF II 和 SLF III 的物理毗邻是否有计算意义——是否存在跨束轴突侧支？
- Q-SLF-03：SLF III 左侧化发育的分子闸门是什么？最合理候选：FOXP2→CNTNAP2→左侧额叶轴突稳定性，但尚未直接验证（见"分子候选机制"小节）。
- Q-SLF-04：在第二语言习得中，SLF III vs AF 的可塑性贡献比例如何？

## 修订历史

- 2026-06-13 · 创建 · 基于《白质的三条平行弦》(#170) · 覆盖 SLF I/II/III/AF 四分系统、DCS 功能双解离、发育遗传数据、代偿模型 · 初始置信度：高
- 2026-06-12 · 修订（添加 SLF III 左侧化分子候选机制小节）· 基于《CNTNAP2：FOXP2 基因网络》(#171) · 加入 FOXP2→CNTNAP2→额叶左侧化表达的证据链（status: emerging，尚未因果验证）；更新 related 加入 foxp2-language-gene 和 cntnap2-language-circuit；Q-SLF-03 更新为"有候选机制"状态

## 来源文章

- [[2026-06-13-superior-longitudinal-fasciculus-branches-attention-language]]

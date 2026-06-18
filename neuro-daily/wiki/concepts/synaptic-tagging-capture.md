---
title: 突触标记与捕获
slug: synaptic-tagging-capture
domain: concepts
type: mechanism
status: mainstream
confidence: medium
created: 2026-06-07
updated: 2026-07-11
revision_count: 2
dimensions: [synaptic, cellular, molecular]
related: [ltp, three-factor-learning-rule, dopamine-reward-prediction-error, camkii, hebbian-learning, memory-consolidation]
prerequisites: [ltp, hebbian-learning, camkii]
opens_questions: [Q-stc-molecular-tag, Q-three-factor-time-window]
source_articles: [2026-06-07-dopamine-reward-prediction-error, 2026-07-11-dopamine-lc-hippocampus-memory-tagging]
key_sources: ["PMID:9020359", "PMID:7708662", "PMID:17626208", "PMID:27602521", "PMID:20130171", "PMID:21170088"]
---

# 突触标记与捕获 (Synaptic Tagging and Capture, STC)

> **一句话定义**：Hebbian 活动在突触处设置短暂的"标签"（tag，有效期约 1-2 小时），标签本身不足以诱导晚期 LTP；只有当蛋白质合成信号（来自强刺激或多巴胺奖励）在标签有效期内到达时，可塑性相关蛋白（PRPs）才被"捕获"到标签处，将早期 LTP 升级为持久的晚期 LTP——这为三因素学习规则的时间延迟提供了分子机制。

## 当前理解

我们现在认为，突触标记与捕获（STC）假说（Frey & Morris 1997）是理解晚期 LTP（L-LTP）如何被大脑选择性地诱导，以及三因素学习规则的时间延迟如何被"等待"的最有力框架。

**基本逻辑**：

```
弱 Hebbian 刺激 → 早期 LTP（E-LTP，数小时）+ 设置"突触标签"（~1-2h 有效）
                                             ↓
                        在标签有效期内，若蛋白质合成信号到来
                          ↓                              ↓
                   [同侧强刺激]               [DA 爆发（D1→PKA→CREB→PRPs）]
                   → PRPs 合成               → PRPs 合成（全细胞范围）
                                             ↓
                        PRPs 被标签"捕获"到激活过的突触
                                             ↓
                        早期 LTP → 晚期 LTP（L-LTP，数天至数周）
```

**关键性质**：
- **局部选择性**：PRPs 是在细胞体或近端树突合成的，但只被带有标签的突触捕获——标签提供了"地址"
- **时间窗口**：标签有效期约 1-2 小时，这解释了为什么延迟奖励学习仍然有效（分钟内），但数小时后的随机关联不能被强化
- **双向利用**：E-LTP 的标签可被跨突触的 PRP 合成捕获（"协同 LTP"）；E-LTD 的标签也可被 LTP 诱导的 PRPs 捕获而逆转（"标签竞争"）

**对三因素规则的意义**：多巴胺 RPE 信号（通过 D1→cAMP→PKA→CREB）触发全细胞范围的 PRP 合成，这些 PRPs 在标签有效期内被带有 Hebbian 标签的突触捕获，实现"延迟的多巴胺调制晚期 LTP"——解决了奖励信号时间延迟的根本问题。

## 关键机制

### 突触标签的性质（假说）

标签的分子身份尚未确定（这是当前最重要的未解问题之一），候选机制包括：
- **CaMKII 的特定磷酸化构象**：Hebbian 激活 → Ca²⁺ → CaMKII T286 自磷酸化 → 特定结构状态作为标签
- **局部蛋白质合成的启动**：弱刺激启动树突局部翻译机器（BDNF-TrkB→mTOR），形成合成准备状态
- **肌动蛋白骨架变化**：树突棘内 F-actin 重塑标记可塑性位点

无论分子身份如何，标签的功能特征是：局部的（特定突触）、时间限制的（~1-2h）、可被 PRPs 识别和结合。

### 可塑性相关蛋白（PRPs）

PRPs 包括：
- Arc/Arg3.1（见 arc-arg31 页面）：局部突触稳定（L-LTP 成分）和内吞（mGluR-LTD）
- Homer 1a：重塑突触后密度，稳定 AMPAR
- 新合成的 AMPA 受体亚基
- BDNF（突触营养因子，触发 TrkB → ERK → 转录）

PRPs 合成由 CREB 磷酸化（PKA 或 CaMKIV 介导）驱动，属于"转录激活 → 翻译"的慢速过程（数分钟至数小时）。

### DA 介导的 STC（三因素规则的时间整合）

1. 行为事件（A）→ Hebbian 激活 → 突触标签（T窗口 ~1-2h 开始计时）
2. 结果评估（A 的奖励）→ DA 爆发 → D1/D5 → cAMP → PKA → CREB → PRPs 合成（全细胞）
3. PRPs 扩散至带标签的突触 → 被标签捕获 → 事件 A 的突触被持久增强（L-LTP）
4. 若行为 B 也发生在 T 窗口内但没有奖励（DA 不爆发）→ B 对应突触的标签消失，PRPs 不合成 → B 的突触不被持久增强

这一机制使大脑能够：**先行动，后评估，选择性记住值得记住的**。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 弱刺激可设置标签，被强刺激诱导的 PRPs 捕获（E-LTP→L-LTP 升级）| 双通路刺激 + 蛋白质合成抑制剂时序操控 | PMID:9020359 | 高（概念建立） |
| DA D1/D5 通过 PKA-CREB 诱导 PRPs 合成，可升级 E-LTP | D1/D5 激动剂诱导 CA1 L-LTP；蛋白质合成依赖 | PMID:7708662（PMC42234） | 高 |
| 标签有效期约 1-2 小时 | 不同延迟的双通路实验；延迟>2h 无协同效应 | PMID:9020359 | 中-高（估计值，不同突触类型可能不同） |
| 标签可被跨突触 PRP 合成捕获（"协同 LTP"） | 同侧 E-LTP 和对侧 L-LTP 的时间排列 | PMID:9020359 | 中-高 |
| 新颖事件在 ±1h 内将弱训练的 STM→LTM（行为标记；D1/D5 + 蛋白合成依赖）| 大鼠 IA 模型 + 时间排列 + 药理 | PMID:17626208 | 中-高（行为层面的 STC 验证）|
| D1/D5 调控记忆持续性（而非编码）：编码后注射拮抗剂损害 24h LTM，不损害 30min STM | 时间点药理分离 + 两种记忆任务 | PMID:20130171 | 高 |
| LC-TH⁺ 末梢（非 VTA）是海马 dCA1 的主要 DA 来源；LC 激活可产生行为标记效应 | 光遗传 + 解剖追踪 + VTA 化学失活 | PMID:27602521 | 高（STC 捕获信号的来源澄清）|

## 连接

- [[ltp]] — STC 是晚期 LTP（L-LTP）选择性诱导的关键机制；E-LTP（标签）→ L-LTP（捕获）是两阶段实现
- [[three-factor-learning-rule]] — STC 解决了三因素规则的时间延迟问题：Hebbian 产生标签，DA-PRPs 提供捕获信号
- [[dopamine-reward-prediction-error]] — DA 爆发触发 PRP 合成，是"捕获"的触发因素
- [[lc-hippocampus-dopamine]] — LC-TH⁺ 末梢（非 VTA）是海马 dCA1 DA 的主要来源；LC 相位激活提供行为标记所需的 PRPs 合成信号；新颖性是主要触发条件
- [[camkii]] — CaMKII 是突触标签的候选分子（假说；尚未证实）
- [[hebbian-learning]] — Hebbian 激活产生标签，是 STC 的"写入"端
- [[memory-consolidation]] — STC 是突触层面的巩固机制（类比：SWR 是系统层面的巩固机制）

## 未解问题

- Q-stc-molecular-tag：突触标签的分子身份是什么？CaMKII T286 磷酸化构象？局部翻译机器的激活状态？能否用超分辨成像直接可视化"标签"？
- Q-three-factor-time-window：标签有效期（~1-2h）在不同脑区、不同突触类型中的变异范围？体内行为任务中的"奖励窗口"是否与此一致？

## 修订历史

- 2026-06-07 · 创建 · 基于《多巴胺的时间机器》一文 · 理解三因素规则的时间整合机制 · 初始置信度：中（机制框架强，分子细节未解）
- 2026-07-11 · 修订 rev2 · 基于《当蓝斑充当"新奇探测器"》一文（#79）· 证据表新增3行（Moncada 2007行为标记、Bethus 2010 D1/D5持续性、Takeuchi 2016 LC为主要DA来源）；连接节新增 lc-hippocampus-dopamine；key_sources 新增4个；DA 捕获信号的来源澄清（LC 主导，非 VTA）

## 来源文章

- [[2026-06-07-dopamine-reward-prediction-error]]
- [[2026-07-11-dopamine-lc-hippocampus-memory-tagging]]

---
title: N400 语义 ERP 成分
slug: n400-erp
domain: concepts
type: method
status: established
confidence: high
created: 2026-08-20
updated: 2026-08-20
revision_count: 1
dimensions: [cognition, whole-brain-network, methods]
related: [language-network, lexical-access, predictive-coding, auditory-dual-stream, anterior-temporal-lobe-hub, working-memory]
prerequisites: [language-network, auditory-cortex]
opens_questions: [Q-lang-comprehension-01, Q-lang-comprehension-03]
source_articles: [2026-08-20-speech-comprehension-n400-lexical-access]
key_sources: ["PMID:20809780", "PMCID:PMC4052444", "PMID:38428168"]
---

# N400 语义 ERP 成分 (N400 Semantic ERP Component)

> **一句话定义**：N400 是事件相关电位（ERP）中一个约 400ms 出现的负向成分，振幅反映词汇在语境中的语义预测误差——越出人意料，N400 越大；它是实时监测大脑语义处理过程的核心神经标记。

## 当前理解

我们现在认为，N400 是大脑在进行语义整合（将感知到的词汇与上下文语境中已激活的语义网络进行匹配）时产生的电生理信号，反映的是**词汇语义激活与预测之间的不一致程度**（Kutas & Federmeier 2011，PMID:20809780）。

**历史**：1980 年，Kutas & Hillyard 在 *Science* 发表发现：在语义异常句子末尾词（"我的咖啡加**狗**"）后约 400ms 出现大幅负向偏转，与预期的 P300 不同，命名为 N400。

**核心特征**：
- **时间窗**：约 200–600ms，峰值 400ms；**潜伏期稳定**，振幅随条件变化
- **振幅决定因素**：完形概率（cloze probability，r ≈ 0.9）——词语在上下文中越出人意料，N400 越大
- **头皮分布**：中央-顶叶区域，双侧（略偏左）
- **跨模态性**：对语音、文字、图片、手势均有响应，说明反映多模态语义系统

**神经发生器**（MEG 时空轨迹，Kutas & Federmeier 2011）：
1. ~250ms：左侧后颞上回（pSTG）激活启动
2. ~365ms：扩展至左侧颞叶腹侧（MTG/ATL）
3. 370–500ms：扩散至右侧前颞叶（rATL）和额叶

这一轨迹与腹侧语言流（pSTG→MTG→ATL→PFC）的解剖结构高度一致。

**预测编码框架**（Grisoni et al. 2024，PMID:38428168）：大脑通过前额叶-ATL 的自顶向下连接在词语到来之前预先激活预期的语义表征；N400 振幅对应**更新预测的代价**——更新越耗费资源，N400 越大。

## 关键机制

**一、语义预激活**：语境在词语到来前即激活预期词语的语义网络；高预测性语境几乎消除 N400

**二、预测误差信号**：N400 反映实际词语与预测词语之间的语义不一致程度，而非"对"/"错"的二元判断

**三、多模态激活**：语义处理激活分布在视觉/听觉/运动皮层的多模态语义网络；N400 是该网络激活的整体信号

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| N400 振幅与完形概率 r ≈ 0.9 | 400+ 篇跨语言实验 | PMID:20809780 | 极高 |
| N400 对非语言刺激（图片、手势）也有响应 | 跨模态 ERP 实验 | PMID:20809780 | 高 |
| MEG 时空轨迹：pSTG→ATL→额叶 | MEG 源分析 | PMID:20809780 | 中高 |
| 预测编码计算模型精确模拟 N400 效应 | 计算建模 | PMID:38428168 | 中高 |

## 连接

- [[language-network]] — N400 是语言网络腹侧流实时激活的信号
- [[lexical-access]] — N400 发生在词汇访问和语义整合阶段
- [[predictive-coding]] — N400 振幅 = 预测误差的神经标记
- [[anterior-temporal-lobe-hub]] — ATL 是 N400 的核心神经发生器之一
- [[auditory-dual-stream]] — N400 与腹侧流的声音-意义处理直接对应

## 未解问题

- Q-lang-comprehension-01：ATL 内部哪个亚区是 N400 的主要发生器？
- Q-lang-comprehension-03：双语者 L2 中 N400 的时空轨迹如何变化？

## 修订历史

- 2026-08-20 · 创建 · 基于《语义理解的毫秒奇迹》(#119) · 初始置信度：高

## 来源文章

- [[2026-08-20-speech-comprehension-n400-lexical-access]]

---
title: 词汇访问
slug: lexical-access
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-08-20
updated: 2026-08-20
revision_count: 1
dimensions: [cognition, whole-brain-network, brain-region]
related: [language-network, n400-erp, auditory-dual-stream, auditory-cortex, anterior-temporal-lobe-hub, superior-temporal-sulcus, predictive-coding]
prerequisites: [auditory-cortex, language-network]
opens_questions: [Q-lang-comprehension-01, Q-lang-comprehension-02]
source_articles: [2026-08-20-speech-comprehension-n400-lexical-access]
key_sources: ["PMID:31220442", "PMCID:PMC6602075", "PMID:22766458", "PMCID:PMC3468690", "PMID:27956600", "PMCID:PMC5206517"]
---

# 词汇访问 (Lexical Access)

> **一句话定义**：词汇访问是将感知到的音素序列（或视觉词形）映射到存储在记忆中的词汇条目，从而激活词义表征的过程；在听觉语音处理中发生于约 100–300ms 内，主要依赖颞上回（STG）和颞中回（MTG）。

## 当前理解

我们现在认为，词汇访问是语音理解流水线中从**音韵编码**到**语义整合**之间的关键中间步骤。它的完成速度极快（约 150–250ms），并行激活多个候选词汇，随后通过竞争机制锁定目标词（Hickok & Poeppel 2012，PMID:22766458）。

**处理层级**（从声学到意义的四阶段）：
1. **声学谱时分析**（0–50ms）：初级听觉皮层（HG/A1）——频率-时间编码，无语言学知识
2. **音韵编码**（50–150ms）：颞上回（STG）——谱时→音素，由谱时感受野（STRFs）实现，有上下文依赖性（Leonard et al. 2019，PMID:31220442）
3. **词汇访问**（100–250ms）：STG/STS→颞中回（MTG）——音素序列→词汇条目，并行候选激活，内聚点（cohort）模型
4. **语义整合**（200–400ms+）：MTG→前颞叶（ATL）——词汇→多模态语义网络激活

**内聚点（Cohort）模型**：听觉开始时，大脑并行激活所有匹配当前音韵输入的词汇候选集（如听到"苹—"，激活"苹果""苹婆"等所有以此开头的词），随着声学信息增加，候选集逐渐"内聚"（收窄），直至确定唯一目标词。

**预测性词汇激活**：上下文（句子语境、话语结构）通过自顶向下连接（前额叶→颞叶）**预先激活**预期词汇的表征，大幅加速词汇访问——高预测性语境中词汇识别时间可缩短数十毫秒。

**词汇访问的神经底层**（Fridriksson et al. 2016，PMID:27956600）：VLSM 研究（n=138）证明，pSTG/MTG 的病变与**词汇理解障碍**（不是单纯音韵辨别障碍）相关，支持 MTG 在词汇访问中的核心地位。

## 关键机制

**音韵→词汇的瓶颈**：语音流无词边界（连续性问题）。STG 的时间递归连接（Leonard et al. 2019）通过积累前后音素的上下文表征辅助切割，但完整的词边界检测还依赖词汇知识（top-down）。

**并行竞争激活**：多个候选词汇同时激活，通过侧向抑制竞争（类似注意选择）。频率高的词汇抑制阈值更低（词频效应）。

**N400 与词汇访问**：词汇访问完成后，N400 反映将该词的语义激活与当前语境整合的难度。N400 在词语呈现后约 200ms 开始上升，与词汇访问的时程重叠——提示 N400 可能部分反映词汇访问本身，而非仅仅词后整合。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| STG 实现音韵-词形映射（谱时感受野）| ECoG, STRFs | PMID:31220442 | 高 |
| MTG 损伤→词汇理解障碍 | VLSM n=138 | PMID:27956600 | 高 |
| 词汇访问约 150–250ms 完成 | MEG | PMID:20809780 | 中高 |
| 上下文预激活加速词汇访问（N400 缩小）| ERP cloze paradigm | PMID:20809780 | 高 |

## 连接

- [[n400-erp]] — N400 是词汇访问完成后语义整合难度的信号
- [[language-network]] — 词汇访问是腹侧语言流的核心功能节点
- [[auditory-dual-stream]] — 词汇访问位于腹侧流，与背侧流（音韵-运动）分工
- [[auditory-cortex]] — 提供词汇访问的音韵输入
- [[anterior-temporal-lobe-hub]] — 词汇访问输出进入 ATL 进行语义整合
- [[predictive-coding]] — 上下文预激活是预测编码在词汇访问中的体现

## 未解问题

- Q-lang-comprehension-01：ATL 亚区（TE/TG/TI/TF）在语义整合中的功能分工
- Q-lang-comprehension-02：候选词汇内聚竞争过程是否有单细胞/多单位水平的直接电生理证据？

## 修订历史

- 2026-08-20 · 创建 · 基于《语义理解的毫秒奇迹》(#119) · 初始置信度：高

## 来源文章

- [[2026-08-20-speech-comprehension-n400-lexical-access]]

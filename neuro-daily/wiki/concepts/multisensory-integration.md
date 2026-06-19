---
title: 多感觉整合
slug: multisensory-integration
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-30
updated: 2026-07-30
revision_count: 1
dimensions: [cellular, brain-region, whole-brain-network, cognition]
related: [bayesian-causal-inference, superior-colliculus, predictive-coding, temporal-binding-window, inverse-effectiveness, auditory-cortex, somatosensory-cortex]
prerequisites: [bayesian-causal-inference, predictive-coding]
opens_questions: [Q-msi-01, Q-msi-02, Q-msi-03]
source_articles: [2026-07-30-multisensory-integration-bayesian-brain]
key_sources: ["PMID:17895984", "PMCID:PMC1978520", "PMID:19616425", "PMID:32113921", "PMID:11807554"]
---

# 多感觉整合 (Multisensory Integration)

> **一句话定义**：大脑将来自不同感觉通道的信号先进行因果推断（判断是否共享来源），再依据贝叶斯最优权重合并，以构建比任何单一感觉更准确的世界感知。

## 当前理解

多感觉整合是大脑将视觉、听觉、触觉、嗅觉、前庭觉等多种感觉信号合并以产生统一感知的过程。其计算核心不是简单叠加，而是**两阶段推断**：

1. **因果推断**（是否整合）：大脑首先估计两个信号来自同一来源的概率 P(C=1)。当 P(C=1) 高时，倾向于融合；当 P(C=1) 低时，倾向于分离。这一过程被 Körding 等（2007）形式化为贝叶斯因果推断模型。

2. **最优权重整合**（如何整合）：给定整合决策后，各感觉信号的权重与其可靠性（信号-噪声比的倒数，即不确定性）成反比——更可靠的感觉通道获得更高权重。这与最大似然估计（MLE）的预测一致（Ernst & Banks 2002）。

多感觉整合发生在多个层级：
- **皮层下**：上丘（SC）是最早被详细研究的多感觉整合位点，遵循三条 Stein-Meredith 规则
- **皮层**：颞上沟（STS）是视听整合（尤其是语音感知）的关键节点；顶叶皮层负责空间多感觉整合；脑岛处理跨模态冲突

## 关键机制

### 上丘的三条规则（细胞/回路级别）
1. **空间规则**：整合仅在两信号落在各自感受野重叠区时发生；空间不匹配产生抑制
2. **时间规则**：只有在时间绑定窗（TBW）内近似同步的信号才发生整合增强
3. **逆效应性**：单感觉刺激越弱，整合后的相对增益越大（见 [[inverse-effectiveness]]）

### 贝叶斯因果推断（认知计算级别）
最终感知 = P(C=1) × 整合估计 + P(C=2) × 分离估计

当两信号空间/时间高度一致，P(C=1)→1，效果接近完全整合；当空间/时间不匹配严重，P(C=2)→1，接近完全分离，且预测"负偏移"（感知位置向远离另一信号方向漂移）。

### 皮层网络（全脑网络级别）
- **STS（颞上沟）**：视听整合（语音、情感面部表情+声音）；对视听同步性高度敏感
- **丘脑枕核（Pulvinar）**：上丘多感觉信号到皮层的快速通路
- **顶内沟（IPS）**：多感觉空间整合
- **脑岛 + 额下回**：跨模态冲突检测和仲裁

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 人类视触觉整合符合 MLE 最优预测 | 调节视觉噪声，测量触觉权重变化；与 MLE 预测精确匹配 | PMID:11807554 (Ernst & Banks 2002) | 高 |
| 贝叶斯因果推断模型预测整合/分离决策（R²=0.97） | 视听空间定位实验；19 名受试者；4 种竞争模型对比 | PMID:17895984 (Körding 2007) | 高 |
| 上丘三条规则在猫/猫鼬中保守 | 细胞外记录；系统操控刺激空间/时间关系 | Meredith & Stein 1983 (Science) | 高 |
| 人脑多感觉整合的核心网络：STG/STS、丘脑、脑岛 | 49 项 fMRI 研究的 ALE 元分析 | PMID:36084305 (Scheliga 2022) | 中 |
| 基于 SC 原则的视听训练可恢复半盲检测 | 动物模型视野盲区恢复实验 | PMID:32113921 (Stein & Rowland 2020) | 高 |
| 多感觉整合可能是"去中心化"并行网络而非层次汇聚 | 理论模型 + 电生理综述 | PMID:38270850 (Zhang 2024) | 低-中 |

## 连接

- [[bayesian-causal-inference]] — 多感觉整合的计算框架
- [[superior-colliculus]] — 皮层下多感觉整合位点
- [[temporal-binding-window]] — 时间整合约束
- [[inverse-effectiveness]] — SC 整合的第三规则
- [[predictive-coding]] — 贝叶斯推断的共同语言
- [[auditory-cortex]] — STS 视听整合的听觉输入节点
- [[somatosensory-cortex]] — 视触觉整合（Ernst & Banks 2002 的感觉对）

## 未解问题

- Q-msi-01：时间绑定窗（TBW）的神经振荡基础是什么？（见 state/unresolved_questions.md）
- Q-msi-02：皮层下（SC/丘脑）整合和皮层（STS）整合是串联还是并联关系？
- Q-msi-03：多模态 AI 是否可以实现真正的不确定性加权整合？

## 修订历史

- 2026-07-30 · 创建 · 基于《感官的裁判》文章 #98 · 初始置信度：高（基于多篇开放全文综述）

## 来源文章

- [[2026-07-30-multisensory-integration-bayesian-brain]]

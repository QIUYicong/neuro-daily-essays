---
title: 贝叶斯感觉整合
slug: bayesian-sensory-integration
domain: concepts
type: theory
status: mainstream
confidence: high
created: 2026-07-20
updated: 2026-07-20
revision_count: 1
dimensions: [cellular, brain-region, behavior, cognition]
related: [multisensory-integration, temporal-binding-window, predictive-coding, precision-weighting, world-model]
prerequisites: [predictive-coding, precision-weighting]
opens_questions: [Q-msi-01]
source_articles: [2026-07-20-multisensory-integration-temporal-binding-sts]
key_sources: ["PMID:11807554", "PMID:19616425", "PMID:24374382"]
---

# 贝叶斯感觉整合 (Bayesian Sensory Integration)

> **一句话定义**：大脑以最大后验估计的方式整合多路感觉信号——先通过贝叶斯因果推断判断信号是否同源，再以最大似然估计（MLE）按各通道信噪比为信号加权融合，使整合后的感知方差严格小于任何单路。

## 当前理解

我们现在认为，贝叶斯感觉整合理论是描述多感觉整合最成功的计算框架。核心主张是：大脑对感觉信号的整合方式近似最优贝叶斯估计。这一框架分两个层次：

**层次一（MLE）——Ernst & Banks 2002**：在已确认信号同源的前提下，最优整合是加权平均，权重与各通道方差成反比：
- w_i = (1/σ_i²) / Σ(1/σ_j²)
- 整合后方差：σ² = 1 / Σ(1/σ_i²)，严格 < 任何单路方差
- 预测：视觉噪声增大→触觉权重增加；直接被 Ernst & Banks 实验证实

**层次二（因果推断）——Körding et al. 2007**：MLE 假设信号已确认同源。现实中，大脑需先估计 P(common cause)：
- P(C=1|观测) ∝ P(观测|C=1) × P(C=1)
- 时间差小/空间接近/感觉内容相符 → P(C=1) 高 → 融合（MLE）
- 时间差大/空间分离/内容矛盾 → P(C=1) 低 → 分离处理
- 解释为何腹语效应不完全：空间差超过阈限时，P(C=1) 下降，捕获效应减弱

## 关键机制

### MLE 框架（两通道示例）
```
w_V = σ_H² / (σ_V² + σ_H²)
w_H = σ_V² / (σ_V² + σ_H²)
σ_VH² = (σ_V² × σ_H²) / (σ_V² + σ_H²)
```

### 因果推断（Causal Inference Model）
```
P(C=1) = P(V,H | C=1) × prior_common / P(V,H)
整合估计 = P(C=1) × MLE_estimate + P(C=0) × [w_V×S_V + w_H×S_H]
```

### 与逆效性法则的数学等价
上丘的"逆效性法则"——越弱的信号整合增益越大——是 MLE 框架的必然结果：
- 弱信号 → 高方差 → 另一路信号的权重相对更高 → 整合后精度改善的百分比更大

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 视觉-触觉整合接近 MLE 最优 | 调节视觉噪声+精度测量 | PMID:11807554 | 高 |
| 视觉-前庭整合接近 MLE | 视觉-前庭神经元线性加权 | PMID:19616425 | 高 |
| 腹语效应随空间差增大而减弱（因果推断预测） | 心理物理学+计算建模 | 多项研究 | 高 |

## 局限与未解

- MLE 框架假设高斯噪声，真实神经编码噪声更复杂
- "近似最优"而非完全最优：内部噪声引入额外次优性
- 贝叶斯因果推断在神经元层面的实现尚不清楚（Q-msi-01）

## 连接

- [[multisensory-integration]] — 贝叶斯框架的应用领域
- [[temporal-binding-window]] — 时间维度上的"因果推断先验"
- [[predictive-coding]] — 共享"感知=贝叶斯推断"认识论
- [[precision-weighting]] — 精度权重是 MLE 权重的一般化

## 修订历史

- 2026-07-20 · 创建 · 基于《感官交响曲》文章（#88）· 初始置信度：高

## 来源文章

- [[2026-07-20-multisensory-integration-temporal-binding-sts]]

---
title: 贝叶斯因果推断
slug: bayesian-causal-inference
domain: concepts
type: theory
status: emerging
confidence: high
created: 2026-07-30
updated: 2026-07-30
revision_count: 1
dimensions: [cognition, whole-brain-network]
related: [multisensory-integration, predictive-coding, temporal-binding-window, free-energy-principle]
prerequisites: [predictive-coding]
opens_questions: [Q-msi-01, Q-msi-02]
source_articles: [2026-07-30-multisensory-integration-bayesian-brain]
key_sources: ["PMID:17895984", "PMCID:PMC1978520", "PMID:14724638"]
---

# 贝叶斯因果推断 (Bayesian Causal Inference)

> **一句话定义**：大脑整合多感觉信号时，先估计多信号"是否来自同一来源"的概率（因果推断），再以此概率为权重，对"完全整合"和"完全分离"两种极端估计做加权平均，产生最终感知。

## 当前理解

贝叶斯因果推断（BCI）模型由 Körding 等（2007）提出，是迄今解释多感觉整合为何/何时发生的最成功计算框架。

**核心思想**：感知决策不仅涉及"感觉信号的值是什么"，还涉及更深层的结构问题——"这些信号来自几个来源"。大脑隐式地运行一个因果图谱推断：

- **假说 C=1**（共同来源）：两个信号来自同一个物体/事件
- **假说 C=2**（独立来源）：两个信号来自不同物体/事件

最终感知是两个假说下估计的加权平均：

```
感知估计 = P(C=1|数据) × 整合估计 + P(C=2|数据) × 分离估计
```

**模型参数**：
- σV（视觉不确定性）
- σA（听觉不确定性）
- σP（空间先验分布宽度）
- P_common（先验共同来源概率，个体间有差异）

**独特预测**——"负偏移"（negative bias）：当 P(C=2) 高时（大脑判断来自不同来源），每个感觉通道的感知位置会**向远离另一信号方向漂移**——这是线性整合模型无法预测的现象，但在 Körding 等（2007）的实验中被精确观察到。

**与 MLE 模型的关系**：Ernst & Banks（2002）的最大似然估计（MLE）模型是 BCI 的特例——假设 P_common=1（始终整合），在信号可信来自同一来源时是优秀近似，但不能解释整合/分离的决策层。BCI 包含了 MLE，并将其推广到完整的决策空间。

## 关键机制

### 贝叶斯推断的具体步骤
1. 接收感觉输入（两个信号的位置/内容/时间）
2. 计算 P(C=1|数据)：根据先验和感觉不确定性，更新共同来源假说的概率
3. 分别在 C=1 和 C=2 假说下计算各感觉位置的 MAP 估计
4. 加权平均产生最终感知输出
5. 若被问"是否来自同一来源"，报告 P(C=1)

### 实验验证方式
- 系统操控空间/时间一致性 → 观察整合效果如何降低（与 P(C=1) 降低一致）
- 操控视觉/听觉噪声 → 权重随不确定性动态调整（与 MLE 预测一致）
- 观察"负偏移"现象 → BCI 独特预测

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| BCI 模型拟合优度 R²=0.97，显著优于其他模型 | 19 名受试者，视听空间定位，4 种竞争模型对比 | PMID:17895984 (Körding 2007) | 高 |
| "负偏移"现象被实验观察到（分离条件下感知漂移） | 同上实验 | PMID:17895984 | 高 |
| P_common 解释 72% 的"统一感知判断"方差 | 模型参数 vs 受试者报告 | PMID:17895984 | 高 |
| 感知运动学习也遵循贝叶斯整合原则 | 感知运动适应实验（扰动学习） | PMID:14724638 (Körding & Wolpert 2004) | 中高 |

## 连接

- [[multisensory-integration]] — BCI 的首要应用领域
- [[predictive-coding]] — 贝叶斯推断的层次皮层实现（共同的数学基础）
- [[free-energy-principle]] — Friston 的自由能原理是 BCI 的一般化框架
- [[temporal-binding-window]] — 时间不一致性降低 P(C=1) 的机制

## 未解问题

- Q-msi-01：TBW 的神经振荡基础（与 P(C=1) 如何关联？）
- Q-msi-02：BCI 的神经实现是在 SC 层级、丘脑层级还是皮层层级完成的？

## 修订历史

- 2026-07-30 · 创建 · 基于《感官的裁判》文章 #98 · 初始置信度：高（直接引用开放全文 Körding 2007）

## 来源文章

- [[2026-07-30-multisensory-integration-bayesian-brain]]

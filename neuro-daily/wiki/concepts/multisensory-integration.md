---
title: 多感觉整合
slug: multisensory-integration
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-20
updated: 2026-07-20
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, whole-brain-network, behavior, cognition]
related: [temporal-binding-window, bayesian-sensory-integration, mcgurk-effect, superior-temporal-sulcus, predictive-coding, precision-weighting, auditory-cortex, somatosensory-cortex, olfactory-system, v1-primary-visual-cortex, anterior-temporal-lobe-hub]
prerequisites: [auditory-cortex, somatosensory-cortex, predictive-coding]
opens_questions: [Q-msi-01, Q-msi-02, Q-msi-03]
source_articles: [2026-07-20-multisensory-integration-temporal-binding-sts]
key_sources: ["PMID:1012311", "PMID:11130706", "PMID:11807554", "PMID:19793985", "PMID:25128432", "PMID:36084305"]
---

# 多感觉整合 (Multisensory Integration)

> **一句话定义**：大脑通过贝叶斯因果推断先估计多路感觉信号是否同源，再根据各通道当前可靠性按最大似然估计加权融合，在时间绑定窗口内构造比任何单一感官更准确的统一感知。

## 当前理解

我们现在认为，多感觉整合不是简单的感觉叠加或投票取平均，而是一套近似最优的概率推断机制。大脑面临两个级联问题：**（1）这些信号是否来自同一物理事件？**（因果推断）**（2）如果是，各信号应以什么权重融合？**（可靠性加权）。

因果推断（common cause inference）首先判断信号在空间和时间上是否足够对齐以构成"同一来源"的证据。如果是，则进入最大似然估计（MLE）整合；如果否，则分离处理。整合后的感知精度（方差）严格小于任何单路感知的精度，即整合带来实质性的感知改善。

这套机制在皮层下（上丘）和皮层（pSTS、ALS meta-analysis 确认的 STG/MTG-丘脑-岛叶-IFG 网络）均有实现。整合的时间窗口（TBW）随任务复杂度变化（简单闪光-哔声：~100-200ms；语音视听：~300-500ms），且具有可塑性——反馈训练可缩窄约 40-64%。

## 关键机制

### 1. 皮层下：上丘三原则（Rowland & Stein 2014, PMID:24374382）
- **空间对齐**：只有大致相同空间位置的多感觉信号才产生超加性增强
- **时间一致**：信号须在限定时间窗内同时到达
- **逆效性法则**：单路越弱的信号，多感觉增强越大（与 MLE 数学一致）

### 2. 皮层：贝叶斯最优整合（Ernst & Banks 2002, PMID:11807554）
- 权重 w_i = (1/σ_i²) / Σ(1/σ_j²)，与方差成反比
- 整合后方差：σ_combined² = 1 / Σ(1/σ_i²)
- 视觉主导是可靠性高的结果，非硬连线规律

### 3. 时间绑定窗口（Wallace & Stevenson 2014, PMID:25128432）
- 跨感觉时间容差窗口；随刺激复杂度和发育阶段变化
- 主观同时性点（PSS）通常偏移约 100ms（听觉需滞后视觉）
- 训练可缩窄 TBW（Powers et al. 2009, PMID:19793985）

### 4. 皮层枢纽：后颞上沟（pSTS）（Scheliga et al. 2022, PMID:36084305; Zhu & Beauchamp 2017, PMID:28179553）
- 位于听觉和视觉皮层之间，接受双侧双模态输入
- 嘴型偏好区域同时偏好人声（联合选择性 = 视听言语整合）
- 沿前后轴功能梯度：后段（感觉运动整合）→ 前段（语义整合）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 视听融合产生第三感知（麦格克效应） | 音视频叠加主观报告；闭眼幻觉消失 | PMID:1012311 | 极高 |
| 听觉主导视觉计数（声音诱导闪光幻觉） | 1闪光+2哔声→感知2次闪光 | PMID:11130706 | 高 |
| 视觉-触觉整合接近 MLE 最优 | 调节视觉噪声+精度测量 | PMID:11807554 | 高 |
| TBW 训练可缩小 40-64% | 5天反馈训练+1周随访 | PMID:19793985 | 高 |
| ASD 患者 TBW 显著扩宽 | 系统综述+荟萃分析 | PMID:29317216 | 高 |
| 多感觉整合共同神经网络 | ALE 荟萃分析（fMRI/PET） | PMID:36084305 | 高 |
| pSTS 嘴-声音联合选择性 | 人类 fMRI 功能定位 | PMID:28179553 | 中-高 |

## 连接

- [[temporal-binding-window]] — 时间整合的窗口机制
- [[bayesian-sensory-integration]] — 计算原理
- [[mcgurk-effect]] — 经典视听融合幻觉
- [[superior-temporal-sulcus]] — 皮层整合枢纽
- [[predictive-coding]] — 共享"感知=推断"认识论框架
- [[precision-weighting]] — 贝叶斯框架中的精度权重机制
- [[auditory-cortex]] — 听觉输入通路
- [[somatosensory-cortex]] — 触觉输入通路
- [[anterior-temporal-lobe-hub]] — 高层语义整合（pSTS的前端延伸）

## 未解问题

- Q-msi-01（高优先级）：贝叶斯因果推断的单细胞神经表示是否可追踪？
- Q-msi-02（中优先级）：婴儿期 MLE 整合能力如何发展？
- Q-msi-03（中优先级）：ASD 中 TBW 扩宽是原发还是继发于感觉过敏？

## 修订历史

- 2026-07-20 · 创建 · 基于《感官交响曲》文章（#88）· 初始置信度：高

## 来源文章

- [[2026-07-20-multisensory-integration-temporal-binding-sts]]

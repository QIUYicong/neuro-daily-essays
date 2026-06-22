---
title: 外侧顶内区（LIP）
slug: lip-area
domain: systems
type: region
status: established
confidence: high
created: 2026-09-01
updated: 2026-09-01
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, cognition]
related: [perceptual-decision-making, drift-diffusion-model, posterior-parietal-cortex, mt-v5-motion-area, superior-colliculus, dorsal-attention-network, neural-manifold]
prerequisites: [posterior-parietal-cortex, mt-v5-motion-area, perceptual-decision-making]
opens_questions: [Q-pdm-01, Q-pdm-02, Q-pdm-03, Q-pdm-04]
source_articles: [2026-09-01-perceptual-decision-making-lip-drift-diffusion]
key_sources: ["PMID:11600651", "PMID:12417672", "PMID:17600525", "PMID:20174574", "PMID:26160947", "PMID:35915096", "PMID:37352857", "PMID:39422555", "PMID:40208792"]
---

# 外侧顶内区（Lateral Intraparietal Area, LIP）

> **一句话定义**：猕猴后顶叶皮层顶内沟外侧壁的感知-运动联合皮层区域，以爬坡到阈值的放电动力学实现感觉证据的时间积分，是漂移扩散决策模型最有力的神经底物候选；其功能解释在"证据积累器"和"空间注意优先图"之间存在根本争议。

## 当前理解

我们现在认为 LIP（外侧顶内区）是灵长类感知决策研究中最核心的脑区之一。自 Shadlen & Newsome（2001）发现 LIP 神经元在随机点运动任务中呈现随方向相干度变化的斜坡放电（爬坡动力学）以来，LIP 被视为漂移扩散模型（DDM）的主要神经实现——累积来自 MT/V5 的方向信息，当放电率达到阈值时触发眼跳决策。

Steinemann et al.（2024，eLife）的 Neuropixels 群体记录（54-203 个神经元同步）将这一理解升级为群体层面的直接验证：LIP 群体活动在单次试验中沿一维流形漂移扩散（PC1 = 44% 方差，参与比率 = 4.4）。

然而，Seideman et al.（2022，Nature Communications）的强迫时限（compelled-response）任务揭示了一个关键矛盾：更强的运动相干度反而导致**更弱**的 LIP 方向分化——这在传统 DDM 框架中无法解释，暗示 LIP 可能主要是一个**空间注意优先图（spatial priority map）**，证据积累效应是注意时序转移（刺激→靶点）的副产品，而非真正的证据积分。

## 关键机制

### 爬坡-到-阈值动力学（Ramp-to-Threshold Dynamics）

**经典实验范式**：随机点运动（RDM）任务
- 猴子注视屏幕，一组随机点以特定相干度运动（0%–100%），判断整体方向并眼跳到对应靶点
- **LIP 反应**：与猴子最终选择靶点对应的 LIP 神经元，从运动刺激出现后约 200ms 开始放电率单调升高
- **相干度效应**：相干度越高 → 爬坡斜率越陡（漂移速率越快）→ 反应越快且越准确
- **阈值一致性**：无论相干度如何，眼跳总在 LIP 放电率达到固定阈值时触发（Roitman & Shadlen 2002）

### 细胞类型异质性（Steinemann 2024）

LIP 不是均质的积累器神经元群：
- **Tin 神经元**（~14.5%）：在随机点运动期间靶点持续在感受野内，这些神经元是关键积累亚群，携带最多决策相关信息
- **Min 神经元**（~10%）：编码瞬时运动证据但不积累
- **其他神经元**：功能异质，非直接积累参与者

### 多信号整合：奖励 vs 感知证据

Rorie et al.（2010，PLoS One）的关键解离：
- 奖励信息影响**起点**：在运动刺激出现前 ~100ms，高奖励靶点对应的 LIP 积累器从更高初始放电率出发
- 感知证据影响**漂移速率**：运动刺激出现后 ~200ms 才显现斜率差异
- 时间分离机制支持贝叶斯最优先验（奖励）×似然（感觉证据）乘积计算

### 决策终止：LIP → SC 阈值检测

Stine et al.（2023，Neuron）：
- LIP 爬坡到阈值时，上丘（SC）检测到信号越界并爆发放电，触发眼跳
- SC 失活 → LIP 积累延长（无法终止）→ 反应时显著增加
- LIP 与 SC 形成**专职双区域分工**：LIP 积累，SC 终止

### 决策信心编码

Zylberberg & Shadlen（2025，Cell Reports）：反应前 100-200ms 的 LIP **群体协方差结构**（非均值）携带选择准确率的元信息（信心），高相干度→群体状态更集中→更高信心。这意味着 LIP 不只传递"选哪个"，还传递"确定程度"。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| LIP 爬坡斜率与相干度正相关，预测选择和 RT | 猕猴 LIP 单细胞记录，延迟反应 RDM | PMID:11600651 | 高 |
| LIP 达到固定阈值时眼跳触发，阈值跨相干度一致 | RT 版 RDM | PMID:12417672 | 高 |
| 奖励移动起点，感知证据改变漂移速率 | 不平衡奖励条件，时域线性回归 | PMID:20174574（PMC2824817）| 高 |
| 75% LIP 神经元被踩步模型更好描述 | 统计模型比较 | PMID:26160947 | 中 |
| 强迫时限条件下强证据→弱 LIP 分化（逆转） | 强迫时限 RDM，猕猴 LIP 记录 | PMID:35915096（PMC9343639）| 高（但对"纯积累器"的挑战） |
| SC 爆发检测 LIP 越界，SC 失活延长积累 | LIP+SC 同时记录，SC 失活实验 | PMID:37352857 | 高 |
| 群体 PC1 符合无界扩散自相关，时间介导 p<10⁻³¹⁷ | Neuropixels 群体记录（54-203 神经元）| PMID:39422555（PMC11488853）| 高 |
| LIP 群体协方差结构编码决策信心 | 猕猴 RDM，信心解码分析 | PMID:40208792 | 中-高 |

## 连接

- [[posterior-parietal-cortex]] — LIP 是 PPC 顶内沟外侧壁的功能分区
- [[perceptual-decision-making]] — LIP 是感知决策神经机制的核心
- [[drift-diffusion-model]] — LIP 爬坡动力学是 DDM 的神经实现
- [[mt-v5-motion-area]] — MT/V5 向 LIP 提供运动方向感觉证据
- [[superior-colliculus]] — SC 作为阈值传感器终止 LIP 积累
- [[dorsal-attention-network]] — LIP 是 DAN 的关键组成部分（空间优先图功能）
- [[neural-manifold]] — LIP 群体活动在单次决策期间沿一维流形扩散

## 未解问题

- Q-pdm-01：LIP 是感知证据积累器还是空间注意优先图？两者在哪些实验条件下可以明确区分？
- Q-pdm-02：LIP 的决策边界（阈值放电率）在速度-精度权衡时如何变化？边界调节由何处指令？
- Q-pdm-03：踩步动力学（Latimer 2015 单神经元）与扩散动力学（Steinemann 2024 群体）如何在细胞亚型层面统一？Tin 细胞是否是踩步的来源？
- Q-pdm-04：人类 IPS 的 hIP3 子区（Wongtrakun 2025）与猴子 LIP 的功能同源是否存在物种特异性差异？

## 修订历史

- 2026-09-01 · 创建 · 基于《大脑如何投票：从随机点到决策信号》(#131) · 初始置信度：高

## 来源文章

- [[2026-09-01-perceptual-decision-making-lip-drift-diffusion]]

---
title: 漂移扩散模型
slug: drift-diffusion-model
domain: concepts
type: theory
status: established
confidence: high
created: 2026-09-01
updated: 2026-09-01
revision_count: 1
dimensions: [cognition, behavior, methods]
related: [perceptual-decision-making, lip-area, neural-manifold, value-based-decision-making, population-clock, actor-critic-brain]
prerequisites: [perceptual-decision-making]
opens_questions: [Q-pdm-01, Q-pdm-02, Q-pdm-03]
source_articles: [2026-09-01-perceptual-decision-making-lip-drift-diffusion]
key_sources: ["PMID:17600525", "PMID:11600651", "PMID:12417672", "PMID:39422555", "PMID:20174574"]
---

# 漂移扩散模型 (Drift-Diffusion Model, DDM)

> **一句话定义**：描述二选一感知决策的连续时间随机过程数学框架——决策变量从起点以恒定漂移速率在噪声中积累，率先到达两个边界之一即触发对应选择；五参数（μ、σ、B、z、t₀）完整决定速度-精度权衡曲线。

## 当前理解

我们现在认为漂移扩散模型（DDM）是感知决策最成熟的数学框架，它将行为（反应时分布 + 错误率曲线）与神经生理（LIP 爬坡斜率、阈值放电率、起点偏置）精确对应起来。Gold & Shadlen（2007，Annu Rev Neurosci，PMID:17600525）系统建立了 DDM 参数与 LIP 神经信号的一一映射关系。

DDM 的核心方程是带漂移的 Wiener 过程（Brown 运动）：

$$dX(t) = \mu \, dt + \sigma \, dW(t)$$

其中 $X(t)$ 是时刻 $t$ 的决策变量，$\mu$ 是漂移速率，$\sigma$ 是扩散（噪声）强度，$dW(t)$ 是标准 Wiener 微分。当 $X$ 首次到达 $+B$ 或 $-B$ 时，分别触发"选项 1"或"选项 2"的选择。

Steinemann et al.（2024，eLife，PMID:39422555）用 Neuropixels 群体记录验证了单次试验层面 LIP 群体活动满足无界扩散自相关结构（时间介导效应 $p < 10^{-317}$），将 DDM 从行为模型提升为具有直接神经测量支持的描述性框架。

## 关键机制

### 五参数系统

| 参数 | 符号 | 含义 | LIP 对应 | 调节因素 |
|------|------|------|---------|---------|
| 漂移速率 | μ | 平均证据强度 | 爬坡斜率 | 感觉相干度 |
| 扩散系数 | σ | 感觉+神经噪声 | 单次轨迹波动 | 内在神经噪声 |
| 决策边界 | B | 积累停止阈值 | 最大放电率 | 速度-精度权衡 |
| 起点偏置 | z | 先验/奖励偏好 | 初始放电率 | 奖励、先验概率 |
| 非决策时间 | t₀ | 感觉延迟+运动执行 | 刺激后~200ms前 | 任务要求 |

### 速度-精度权衡（SAT）

边界高度 B 是 DDM 中控制速度-精度权衡的关键参数：
- **低边界**（速度优先）：较快反应但错误率高；LIP 爬坡更快但阈值放电率更低
- **高边界**（精度优先）：更慢但更准；LIP 爬坡更慢但阈值放电率更高

研究者通过时间压力指令操纵 SAT，LIP 阈值放电率随之变化，验证了边界的神经实现。

### DDM 的扩展版本

1. **非对称起点**（z ≠ 0）：奖励或先验概率偏向一侧，LIP 初始放电率反映偏置（Rorie et al. 2010）
2. **时变漂移**（urgency signals）：决策时间越长，边界收缩；解释强制速度条件下的行为（紧迫信号假说）
3. **多选项推广**（race models）：多个独立积累器竞争，支持多路选择

### 踩步 vs 爬坡的争论

DDM 预测决策变量连续爬坡（在单次试验层面应为随机游走），但 Latimer et al.（2015，Science，PMID:26160947）统计比较显示 ~75% 的 LIP 神经元被**离散踩步**（discrete-step）模型更好描述。

Steinemann et al.（2024）在群体层面反驳了踩步解释：54-203 个神经元同时记录的 PC1 投影显示出与扩散精确吻合的自相关，且不同方法（PCA、回归、直接平均）得到余弦相似度 0.63-0.74 的决策轴。单神经元踩步可能是低信噪比环境下对群体扩散信号的单元级近似，而非真正的计算机制。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| DDM 五参数与行为完整拟合 | 反应时分布 + 错误率贝叶斯拟合 | PMID:17600525（综述） | 高 |
| 漂移速率↔LIP 爬坡斜率 | 猕猴 LIP 记录，斜率随相干度线性变化 | PMID:11600651 | 高 |
| 边界↔LIP 阈值放电率（跨相干度一致） | RT 版 RDM，阈值一致 | PMID:12417672 | 高 |
| 起点↔奖励调制的初始 LIP 放电率 | 平衡/不平衡奖励条件 | PMID:20174574 | 高 |
| 单次试验群体活动匹配无界扩散 | Neuropixels 记录，时间介导检验 | PMID:39422555 | 高 |
| 踩步模型更好描述 75% LIP 神经元 | 统计模型比较（单细胞） | PMID:26160947 | 中（群体层面已部分反驳）|

## 连接

- [[perceptual-decision-making]] — DDM 描述感知决策的数学过程
- [[lip-area]] — LIP 神经元群体是 DDM 的主要神经底物
- [[neural-manifold]] — 决策变量是 LIP 群体状态空间中的一维流形
- [[value-based-decision-making]] — 奖励影响 DDM 的起点参数（Rorie 2010）
- [[population-clock]] — 种群时钟也依赖神经轨迹编码，与 DDM 群体动力学类似
- [[actor-critic-brain]] — 强化学习框架与 DDM 在"行动选择"层面的概念连接

## 未解问题

- Q-pdm-01：LIP 的积累究竟是空间注意优先图的副产品还是真正的证据积累？Seideman 2022 的挑战尚未完全解决。
- Q-pdm-02：决策边界在神经层面是如何实现的？SC 是阈值传感器，但边界高度（速度-精度权衡）由何处调控？
- Q-pdm-03：踩步模型（Latimer 2015）和爬坡扩散模型（Steinemann 2024）的矛盾在细胞亚型层面如何调和？

## 修订历史

- 2026-09-01 · 创建 · 基于《大脑如何投票：从随机点到决策信号》(#131) · 初始置信度：高

## 来源文章

- [[2026-09-01-perceptual-decision-making-lip-drift-diffusion]]

---
title: 目标驱动模型框架
slug: task-optimized-model
domain: theories
type: theory
status: emerging
confidence: medium
created: 2026-06-18
updated: 2026-06-18
revision_count: 1
dimensions: [methods, cognition, whole-brain-network, behavior]
related: [dnn-ventral-stream, representational-similarity-analysis, predictive-coding, ltp, hebbian-learning]
prerequisites: [representational-similarity-analysis]
opens_questions: [Q-dnn-02]
source_articles: [2026-06-18-dnn-ventral-stream-comparison]
key_sources: ["PMID:26906502", "PMID:31659335", "PMID:24812127"]
---

# 目标驱动模型框架（Task-Optimized Model Framework）

> **一句话定义**：不手工设计神经元的偏好，而是让人工网络通过优化**行为任务目标函数**来发展表征，然后观察涌现的内部结构是否与生物神经数据对应——这一框架将神经科学问题转化为"大脑在优化什么目标"的问题。

## 当前理解

Richards 等人（2019, Nature Neuroscience）系统提出：理解神经系统应关注三个**设计组件**：
1. **目标函数（Objective Functions）**：系统在优化什么？（视觉识别？预测未来？行动选择？）
2. **学习规则（Learning Rules）**：如何更新连接权重？（类梯度下降？Hebbian？三因子规则？）
3. **架构（Architecture）**：网络拓扑、连接类型、层级数量、归纳偏向。

核心主张：**神经活动是目标函数 × 学习规则 × 架构的涌现结果**，而不是接线图直接决定的固有属性。

**预测**：如果我们正确识别了大脑的目标函数，并在合理的架构中优化它，就应该自然地产生与真实神经数据对应的表征。

**已验证的核心预测**：
- ImageNet 分类（≈ 视觉识别）作为目标函数，在合理的分层卷积架构中，自发产生 V4-like 和 IT-like 表征（Yamins 2014, PNAS）
- 对比嵌入目标函数（无监督）同样产生 IT-like 表征，提示任务目标而非标签监督是关键（Zhuang 2021, PNAS）

**框架的局限（当前理解的边界）**：
- 目标函数识别困难：大脑可能同时优化多个目标，难以用单一函数形式化
- MouseNet（2022）表明：相同任务在不同物种的神经预测性不同，说明目标函数需与物种的生态位匹配
- 学习规则问题：反向传播（BP）在生物上不合理（权重传输问题、时间非局部性），但大脑用什么规则近似 BP？目前未知

## 关键机制

### 目标函数 → 表征
给定目标函数 L（如 cross-entropy on ImageNet），梯度下降在参数空间中寻找最优 θ*。这个 θ* 对应某种内部表征结构。如果 L 与大脑的真实目标 L_brain 接近，则产生的表征结构也接近真实神经数据。

**推论**：神经科学实验不只是在测量神经元，也是在**逆推大脑的目标函数**——哪种目标函数产生的表征最像真实皮层，那种目标函数就最接近大脑的真实目标。

### Brain-Score 基准（Schrimpf 2020）
整合多个实验室的神经数据（V1、V2、V4、IT 电生理和 fMRI）以及行为错误模式数据，为不同 DNN 架构打分，形成统一排行榜。这是目标驱动框架的工程化实现：给定一套神经基准，可系统地搜索最佳目标函数 + 架构组合。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 目标驱动 CNN 预测 IT 神经活动 | 猕猴电生理，线性预测力 | PMID:24812127 | 高 |
| 任务目标函数，而非监督本身，塑造 IT 表征 | 对比学习 vs 监督学习在 V1/V4/IT 的比较 | PMID:33431673 | 中-高 |
| 三组件框架提供统一解释视角 | 跨多个感觉系统的综合论证 | PMID:31659335 | 中（综述，尚待更多实证检验） |

## 连接

- [[dnn-ventral-stream]] — 该框架在腹侧视觉流中的主要应用和验证
- [[representational-similarity-analysis]] — 验证框架预测的主要工具
- [[predictive-coding]] — 另一种目标驱动理论（预测输入 vs 识别类别）
- [[ltp]] — 反向传播近似在生物学中可能的实现
- [[hebbian-learning]] — 生物学学习规则候选

## 未解问题

- Q-dnn-02：大脑发育的目标函数是什么？对比学习、预测编码、还是多任务组合？
- 反向传播的生物近似问题：局部学习规则能否产生同样的表征结构？

## 修订历史

- 2026-06-18 · 创建 · 基于《当人工神经网络照镜子大脑》一文 · 初始置信度：中（框架有强支持证据，但仍在 "emerging" 阶段，因为对复杂皮层区域的推广尚待验证）

## 来源文章

- [[2026-06-18-dnn-ventral-stream-comparison]]

---
title: 互补学习系统
slug: complementary-learning-systems
domain: concepts
type: theory
status: mainstream
confidence: medium
created: 2026-06-24
updated: 2026-09-25
revision_count: 4
dimensions: [cognition, whole-brain-network, behavior]
related: [hippocampal-circuit, memory-consolidation, sharp-wave-ripples, pattern-separation, pattern-completion, attractor-network, default-mode-network, td-learning, dopamine-reward-prediction-error, model-based-model-free, hippocampal-replay, experience-replay-buffer]
prerequisites: [hippocampal-circuit, memory-consolidation, ltp]
opens_questions: [Q-cls-generative-replay-oneshotlearning]
source_articles: [2026-06-24-hippocampal-ca3-pattern-completion, 2026-07-12-dopamine-td-learning-brain-ai, 2026-07-16-hippocampal-replay-experience-replay, 2026-09-25-systems-consolidation-silent-pfc-engrams]
key_sources: ["PMID:7704110", "PMID:35368306", "PMID:27315762", "PMID:31003893", "PMID:7624455", "PMID:30349103", "PMID:38547293", "PMID:32792531", "PMID:35970912", "PMID:36532709"]
---

# 互补学习系统 (Complementary Learning Systems, CLS)

> **一句话定义**：大脑通过两套互补的学习系统解决"快速学习新信息"与"避免覆盖已有知识"之间的根本矛盾：海马（快速、稀疏、情景性）和新皮层（缓慢、分布式、语义性），两者通过睡眠中的记忆重放协作整合。

## 当前理解

我们现在认为，CLS 理论（O'Reilly & McClelland 1994，PMID:7704110；McClelland et al. 1995）是理解记忆系统为什么不是单一结构的最有说服力的框架之一。

**核心矛盾**（稳定性-可塑性困境）：
- 快速学习（高学习率）→ 新知识可以一次习得，但会覆盖旧知识（**灾难性遗忘**）
- 慢速学习（低学习率）→ 旧知识保护，但无法快速记住新事件

**大脑的解法**：让两套系统分别优化两个目标，然后通过睡眠重放进行知识转移：
- **海马**：高学习率 + 稀疏编码 → 快速记录新情景，正交表征防止干扰
- **新皮层**：低学习率 + 分布式编码 → 缓慢整合跨情景的一般性模式（语义知识）
- **睡眠中的 SWR 重放**：海马反复"回放"情景记忆 → 新皮层从反复接触中缓慢学习，最终情景记忆可以在没有海马参与的情况下被检索（远期记忆转移）

这解释了著名的 H.M. 案例：双侧海马损伤 → 新情景记忆（新事件学习）完全缺失，但远期情景记忆（受伤前数十年的记忆）和语义知识大部分保留。

## 关键机制

### 1. 海马快速学习：稀疏编码防干扰

CA3 + DG 的稀疏编码确保任意两个新事件的神经重叠极低（<5%），从而：
- 新记忆的学习几乎不影响旧记忆对应的突触权重
- 每次一步（one-shot）学习可以在 CA1 通过 BTSP（PMID:39454575）在单次穿越中完成

### 2. 新皮层慢速学习：从重放中提取统计模式

新皮层使用分布式表征（同一特征激活多个神经元，同一神经元参与多个特征）：
- 高表征效率（更多特征可以用更少神经元编码）
- 但也意味着学习新信息会修改旧信息使用的突触，产生干扰

新皮层的解决方案：使用**极低的学习率**，对海马反复重放的事件集进行"统计学习"，只有多次出现的规律性（语义知识）才会被整合进皮层权重。

### 3. 睡眠重放：两套系统的通信协议

NREM 睡眠中，SWR（尖波涟漪）事件驱动：
- CA3/CA1 重播当天的情景序列（以 ~20× 压缩速度）
- 皮层同步慢振荡（~0.75 Hz）+ 睡眠纺锤体接收并整合这些信号
- 反复重放 → 新皮层突触缓慢被相关模式强化 → 情景记忆逐渐在皮层"固化"

**关键预测（已验证）**：选择性阻断 SWR → 次日空间记忆显著受损（因果证据：Girardeau et al. 2009，PMID:19693040）。

### 4. CLS 与深度强化学习的关系

CLS 理论直接启发了 DeepMind DQN（2013-2015）中的**经验回放缓冲区**（experience replay buffer）：
- 每次行动后将经验存入缓冲区（类似"海马"）
- 从缓冲区随机抽取小批量训练神经网络（类似"新皮层从重放中学习"）
- 防止灾难性遗忘，解决了深度 Q 学习的稳定性问题

这是 CLS 理论在 AI 领域最直接的技术应用之一。

### 5. CLS 与强化学习的整合（Kumaran, Hassabis & McClelland 2016 更新）

Kumaran、Hassabis 和 McClelland（2016, PMID:27315762）在原始 CLS 框架基础上指出，智能体需要的不只是"快速学习新情景 + 慢速整合规律"，还需要：
- **情景记忆指导行动选择（Episodic Control）**：直接利用过去最相似情景的行动-结果记录指导当前决策（类比"我上次遇到类似情况是怎么做的"）；这使一次性（one-shot）的目标导向行为成为可能
- **强化学习 + 情景记忆的接口**：DA-RPE 信号（奖励信号）与海马情景记忆的整合，使高奖励情景被优先重放、优先转移到新皮层

**与 model-based / model-free 的关系**：
- 海马情景记忆系统 ≈ MB 系统（灵活，基于模型）
- 新皮层/纹状体慢速 RL ≈ MF 系统（缓存规律，习惯性）

Botvinick et al.（2019, PMID:31003893）进一步提出 **Meta-RL 假说**：多巴胺（慢速 TD 学习）训练前额叶皮层的循环神经网络（RNN），使 PFC-RNN 本身成为一个"快速认知推断系统"（Fast RL System）——类似于"学习如何更快地学习"的元学习能力。这在 AI 中称为元学习（Meta-Learning / Learning to Learn）。

### 6. 瀑布记忆系统模型（CMS）：DMN 作为重播传播的基础设施（2026-09-25 新增）

Kaefer et al. 2022（PMID:35970912，PMC 开放全文）的 CMS 模型将 CLS 理论的"皮层侧学习"从抽象延伸到具体网络架构：

**主连接梯度**：大脑皮层存在一条从感觉运动皮层（低端）到 DMN（高端）的连接梯度，海马位于梯度顶端，是最广泛联接的节点。

**重播传播路径**：SWR 驱动的重播信号从海马出发，通过 DMN 中间节点（mPFC、后扣带皮层等）逐级向感觉皮层传播——每次传播在各层级留下轻微的突触权重修改。

**近临界动力学**：大脑工作在混沌-有序临界点附近，使神经元雪崩（avalanche）能跨越稀疏连接传播到远处脑区。CLS 的"皮层慢速学习"不需要精确解剖回路，而是通过这种物理性质实现。

**记忆年龄与重播层级**：新记忆从高层级（靠近海马）启动重播；旧记忆在皮层侧已累积足够权重，从低层级启动（皮层自主检索）。

这将 CLS 的抽象"皮层学习"与 DMN 的具体网络架构连接起来。见 [[default-mode-network]]。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 海马损伤→新情景记忆缺失，语义/远期记忆保留 | H.M. 等神经心理学经典案例 | 综述 PMID:18284371 | 高（教科书级）|
| 选择性 SWR 阻断→次日空间记忆受损 | 大鼠在线 SWR 检测并实时阻断 | PMID:19693040 | 高（因果）|
| 睡眠后皮层记忆痕迹增强 | 人类 fMRI：睡眠后与海马竞争性激活减少，皮层激活增加 | 多篇综述 | 中-高 |
| DMN 主连接梯度：海马处顶端 | 弥散谱分析（功能连接梯度分解） | PMID:27791099；PMID:35970912 | 高 |
| CMS 瀑布模型（理论预测） | 综合 connectome + replay + near-critical dynamics | PMID:35970912（PMC 开放全文）| 中（理论）|

## 连接

- [[hippocampal-circuit]] — 海马是 CLS 中"快系统"的神经底物
- [[memory-consolidation]] — 两阶段记忆巩固是 CLS 理论的直接预测
- [[sharp-wave-ripples]] — SWR 是海马→皮层知识转移的物理机制
- [[pattern-separation]] — 海马稀疏编码是 CLS 中快速学习不产生干扰的机制
- [[default-mode-network]] — DMN（含海马）在离线期间的自发活动可能是 CLS 的皮层侧整合机制
- [[attractor-network]] — CLS 中海马的内容可寻址检索依赖吸引子网络
- [[td-learning]] — CLS 的皮层慢速学习系统实现了 TD 学习；Botvinick 2019 的 Meta-RL 假说把 DA-TD 和 PFC-RNN 统一在 CLS 框架内
- [[dopamine-reward-prediction-error]] — DA-RPE 信号偏置 SWR 重放内容，使高奖励情景被优先转移；Meta-RL 假说中 DA-TD 训练 PFC 快速学习能力
- [[model-based-model-free]] — 海马情景 ≈ MB 系统；皮层/纹状体慢速 ≈ MF 系统；CLS 是 MB-MF 并行的记忆底物

## 修订历史

- 2026-06-24 · 创建 · 基于"记忆不混淆的秘密"第 60 篇文章 · 建立 CLS 理论页面，连接海马快学习、新皮层慢学习、SWR 重放和深度学习经验回放的统一框架 · 初始置信度：中（框架获广泛支持但某些预测仍有争议，如记忆转移的精确机制）
- 2026-07-12 · 修订 rev2 · 基于《奖励信号的双重发现》第 80 篇文章 · 新增 Kumaran, Hassabis & McClelland 2016 更新（情景记忆指导行动 + 强化学习与情景记忆的接口）；新增 Botvinick 2019 Meta-RL 假说（DA-TD 训练 PFC-RNN 成为快速推断系统）；新增与 td-learning、dopamine-reward-prediction-error、model-based-model-free 的关联
- 2026-07-16 · 修订 rev3 · 基于《记忆的时光机》（#84）· 新增三阶段回放结构（Yang et al. 2024, PMID:38547293：清醒 SWR 选择 → 睡眠 SWR 固化）；新增 Mattar-Daw Need×Gain 规范化理论（PMID:30349103）作为 CLS 回放内容选择的定量框架；新增 van de Ven et al. 2020 生成回放（PMID:32792531）作为 CLS 在 AI 系统的最接近工程实现；新增 hippocampal-replay 和 experience-replay-buffer 关联；更新 opens_questions
- 2026-09-25 · 修订 rev4 · 基于《记忆的双重人生》(#155) · 新增"6. 瀑布记忆系统模型（CMS）"小节，说明 DMN 作为重播传播信息高速公路的角色及近临界动力学机制（Kaefer et al. 2022）；新增 TTT 与 CLS 的关系（多形式并存是 CLS 双系统分工的功能体现）；key_sources 新增 PMID:35970912 / PMID:36532709；source_articles 新增 2026-09-25

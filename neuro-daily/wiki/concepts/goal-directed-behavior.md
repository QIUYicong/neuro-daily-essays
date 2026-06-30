---
title: 目标导向行为
slug: goal-directed-behavior
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-26
updated: 2026-10-20
revision_count: 2
dimensions: [synaptic, microcircuit, brain-region, behavior, cognition]
related: [habitual-behavior, habit-vs-goal-directed, basal-ganglia, dopamine-reward-prediction-error, prefrontal-cortex, striatal-direct-indirect-pathway, actor-critic-brain, td-learning, addiction]
prerequisites: [basal-ganglia, dopamine-reward-prediction-error, prefrontal-cortex]
opens_questions: [Q-gd-01, Q-gd-02]
source_articles: [2026-09-26-habit-goal-directed-dorsal-striatum, 2026-10-20-habit-goal-directed-dms-dls-circuit-switch]
key_sources: ["PMID:16045504", "PMID:19776734", "PMID:21435563", "PMID:14643469", "PMID:33774666", "PMID:39896502", "PMID:40771101", "PMID:41663373"]
---

# 目标导向行为 (Goal-Directed Behavior)

> **一句话定义**：由动作-结果联结（R-O）驱动、对行为后果的当前价值实时敏感的行为，神经基底为背内侧纹状体（DMS）和前边缘皮层（PL）；对应有模型（model-based）强化学习，可随结果价值变化灵活调整行为。

## 当前理解

我们现在认为，目标导向行为是大脑两套并行行为控制系统中"灵活但计算昂贵"的那一套。它的核心特征是**动作-结果关系编码**：动物知道"做 A 会导致结果 B，B 现在值 V"，因此当 B 的价值 V 改变时（结果贬值），做 A 的频率也相应变化。

目标导向系统的神经基底是**背内侧纹状体（DMS）**和**前边缘皮层（prelimbic, PL）**：DMS 损毁即使在少量训练后也导致习惯化行为（Yin et al. 2005），PL 损毁阻止目标导向获得（但不影响已建立的目标导向的表达）。

从计算视角，目标导向行为对应**有模型（model-based）强化学习**：维护一个状态转移模型（"做 A 会导致状态 S' 以概率 P"）和一个结果价值函数（"S' 的价值是 V"），通过前向规划评估当前最优动作。这需要实时访问并整合结果的当前价值，因此计算代价高，但对环境变化极为灵活。

目标导向系统与习惯系统始终**并行运行并竞争控制权**，由下边缘皮层（IL）调节两者的相对权重。早期训练阶段目标导向占主导；随训练重复，习惯系统（DLS）积累优势，并通过 IL 抑制目标导向控制。

## 关键机制

### 1. 背内侧纹状体（DMS）：A-O 联结的存储地点

DMS 接受大量来自前额叶联合皮层（prelimbic, 眶额叶）的投射，以及来自腹侧被盖区（VTA）的多巴胺信号。DMS 的中型多棘神经元通过 DA 依赖性可塑性，建立和存储"动作→结果"的因果联结（A-O 联结）。当结果的价值信息（由眶额叶/岛叶皮层传入）改变时，DMS 网络可即时更新行为概率。

### 2. 前边缘皮层（PL）的调控角色

PL 投射到 DMS，对于**获得**目标导向行为至关重要：PL 损毁阻止了 A-O 联结的建立，但不影响已经建立好的 A-O 联结的表达。这提示 PL 更多地参与"学会什么导致什么"的学习过程，而非储存联结本身。

PL 的人类同源物——腹内侧前额叶（vmPFC）——在结果贬值范式的 fMRI 实验中随结果价值变化而变化（Valentin et al. 2007），支持 PL/vmPFC 在目标导向行为中的调控角色。

### 3. 两套系统的竞争机制

DMS 和 DLS 系统通过下边缘皮层（IL）竞争控制权：IL 活跃时，它主动抑制 PL-DMS 的目标导向回路，习惯系统主导；IL 沉默时（如暂时性损毁），目标导向系统解除抑制，重新主导行为（Coutureau & Killcross 2003, PMID:14643469）。

这种竞争有重要的行为意义：即使在习惯化后，目标导向能力仍然潜伏。**习惯是"压制"，而非"抹除"**。

### 4. 计算对应：Model-Based 强化学习

目标导向行为的计算等价是 model-based RL：
- 维护环境转移模型：T(s,a,s') = Pr(下一状态=s' | 当前状态=s, 动作=a)
- 维护奖励模型：R(s') = 当前在状态 s' 获得的价值
- 通过前向规划（如 Bellman 备份或树搜索）计算 V*(s) = maxₐ Σ T(s,a,s') · [R(s') + γ V*(s')]
- 当 R(s') 改变时（结果贬值），前向规划立即重算，行为调整不依赖新试错

### 5. DMS D1-MSN 是目标导向决策的"持续看门人"（Malvaez et al. 2025）

**2026-10-20 新增（第 188 篇）**：Malvaez et al.（2025, bioRxiv, PMID:39896502，PMC11785256 开放全文）通过单细胞钙成像，追踪了整个训练-习惯化过程中 DMS 内两种细胞类型的命运分叉：

- **D1+（直接通路）**：在目标导向学习阶段稳定编码行动，逐渐发展出结果编码；习惯化后**继续稳定编码**行动-结果关系
- **A2A+（D2 间接通路）**：初期编码行动；习惯化后活动**重组为刻板执行模式**

DREADD 因果验证：
- 抑制 D1+ → 损害目标导向决策，但习惯保留
- 抑制 A2A+ → 损害初期动作-结果学习，但建立后目标导向决策仍可正常执行

**含义**：D1+ 神经元是目标导向控制的持续必要条件，A2A+ 神经元在学习初期必要但最终迁移到习惯支持模式。目标导向能力的维持依赖 D1-MSN 通路的完整性。

### 6. 习惯获得需要 DMS D1-MSN 的主动突触压制（Yu et al. 2021）

**2026-10-20 新增**：Yu et al.（2021, Cerebral Cortex, PMID:33774666）揭示一个反直觉的关键发现：**习惯的获得不是 DMS 系统"被忽视"的结果，而是 DMS 直接通路 D1-MSN 的突触后压制主动发展的结果**。

- 过度训练后，DMS D1-MSN 的皮层→纹状体兴奋性突触 EPSC 幅度显著降低
- 此压制 DMS 特异性（DLS 无此变化）
- DREADD 拯救此压制（使 D1-MSN 恢复正常兴奋性）→ 损害习惯的**获得**，但不影响已形成习惯的**表达**

这说明目标导向系统的退场是主动的——DMS D1-MSN 的突触降权是习惯形成的必要步骤之一，而非训练积累的副产品。

### 7. 扩展到主动回避行为（Sears et al. 2026）

**2026-10-20 新增**：Sears et al.（2026, Nature Communications, PMID:41663373，PMC13000197 开放全文）将目标导向/习惯的双系统框架扩展到**主动回避行为**（active avoidance）：

- 大鼠学会产生安全信号（执行动作→避免伤害性结果）后，安全信号可以被贬值（通过对 CS 本身建立厌恶联结）
- 雄性大鼠过度训练后：对安全信号贬值不敏感（习惯化回避）
- **雌性大鼠：始终对情境依赖性反结果条件化高度敏感，不显示习惯化**
- DMS 和 DLS 的化学遗传学操纵均产生与奖励场景下一致的效应

这是目标导向/习惯框架在**负性强化**（避害）领域的首批直接证据，并揭示了被低估的性别差异。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| DMS 对目标导向获得和表达必要 | DMS 前/后训练损毁均导致少量训练后习惯化 | Yin et al. 2005, PMID:16045504 | 高 |
| IL 抑制目标导向系统 | IL Muscimol→习惯化大鼠恢复目标导向 | Coutureau & Killcross 2003, PMID:14643469 | 高（大鼠） |
| 人类 vmPFC（PL 同源物）编码结果价值 | fMRI 随结果贬值降低激活 | Valentin et al. 2007，综述引用 PMID:19776734 | 中（单一 fMRI） |
| 人类尾状核前部编码动作-结果权变 | Tanaka et al. 2008, fMRI 权变操控范式 | Balleine & O'Doherty 2010, PMID:19776734 | 中（单一 fMRI） |
| 人类行为受 model-based 和 model-free 共同影响 | 两步任务，行为模式+腹侧纹状体 BOLD | Daw et al. 2011, PMID:21435563, PMC:3077926 | 中-高 |
| DMS D1+ 神经元是目标导向决策的持续必要条件 | 单细胞钙成像 + DREADD；D1+ 抑制→目标导向受损，习惯保留 | Malvaez et al. 2025, PMID:39896502 | 中（预印本，2025）|
| 习惯获得需要 DMS D1-MSN 突触压制（主动退场） | DREADD 拯救 D1-MSN + EPSC 记录；拯救→习惯获得受损 | Yu et al. 2021, PMID:33774666 | 中-高（单实验室）|
| DLS 激活主动消除目标导向行为 | 单侧 DLS DREADD 激活 + 结果贬值 | Hart et al. 2025, PMID:40771101 | 中-高（2025 已出版）|
| 目标导向/习惯框架扩展到主动回避行为；雌性不习惯化 | 安全信号贬值 + 化学遗传学，大鼠性别差异 | Sears et al. 2026, PMID:41663373 | 中-高（2026 已出版）|

## 连接

- [[habitual-behavior]] — 竞争系统：两套系统并行运行，IL 调节竞争
- [[habit-vs-goal-directed]] — 两套系统竞争与转换的综合框架（含分子开关机制）
- [[basal-ganglia]] — DMS（尾状核内侧）是目标导向行为的解剖基底
- [[prefrontal-cortex]] — PL/prelimbic cortex 对目标导向获得必要；vmPFC 是人类同源物
- [[dopamine-reward-prediction-error]] — DMS 中的 DA 侧化信号编码动作-结果联结强度
- [[td-learning]] — 目标导向行为计算等价为 model-based RL，与 model-free（TD）形成对照
- [[actor-critic-brain]] — actor-critic 是 model-free 和 model-based 的混合框架，连接两套系统的计算理论
- [[addiction]] — 成瘾损伤 DMS D1 通路，复制习惯化状态；是目标导向功能的病理性失调

## 未解问题

- Q-gd-01：在高认知负荷（疲劳、焦虑）下，model-based 控制的"可用容量"如何下降？是 vmPFC 资源减少、IL 兴奋性升高，还是 DA 信号的质量变化？
- Q-gd-02：目标导向行为的性别差异（雌性大鼠对安全信号贬值更敏感，Sears 2026）——神经机制是什么？与雌性激素对 PL/DMS 可塑性的调控是否相关？

## 修订历史

- 2026-09-26 · 创建（rev1）· 基于《自动驾驶的大脑》（文章 #156）· 整合 Balleine 实验室损毁实验和计算框架 · 初始置信度：高
- 2026-10-20 · 修订（rev2）· 基于《目标导向还是习惯？纹状体双系统的分子开关机制》（文章 #188）· 新增 Malvaez 2025（D1+ 是目标导向持续看门人）、Yu 2021（DMS D1-MSN 突触压制是习惯获得必要条件）、Hart 2025（DLS 主动抑制目标导向）、Sears 2026（回避行为扩展 + 性别差异）；新增 [[habit-vs-goal-directed]] 连接；新增 Q-gd-02（性别差异机制）· dimensions 扩展至包含 synaptic

## 来源文章

- [[2026-09-26-habit-goal-directed-dorsal-striatum]]
- [[2026-10-20-habit-goal-directed-dms-dls-circuit-switch]]

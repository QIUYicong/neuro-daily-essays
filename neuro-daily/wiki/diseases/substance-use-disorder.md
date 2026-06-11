---
title: 物质使用障碍（成瘾）
slug: substance-use-disorder
domain: diseases
type: disease
status: established
confidence: high
created: 2026-07-14
updated: 2026-07-14
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, whole-brain-network, behavior, disease]
related: [dopamine-reward-prediction-error, habit-formation, actor-critic-model, basal-ganglia, deltaFosB, incentive-salience, incubation-of-craving, prefrontal-cortex, lateral-habenula, hpa-axis]
prerequisites: [dopamine-reward-prediction-error, basal-ganglia, habit-formation]
opens_questions: [Q-habit-01, Q-addiction-01, Q-addiction-02]
source_articles: [2026-07-14-addiction-dopamine-deltaFosB]
key_sources: ["PMID:27475769", "PMCID:PMC6135092", "PMID:11572966", "PMCID:PMC58680", "PMID:21338877", "PMCID:PMC4046255", "PMID:18640920", "PMCID:PMC2607325"]
---

# 物质使用障碍（成瘾）

> **一句话定义**：成瘾不是意志力失败，而是奖励学习机制的病理性征用——反复的超生理多巴胺冲击通过 ΔFosB 积累、突触结构重塑和激励显著性系统的选择性敏化，将大脑的"想要"系统与"喜欢"系统解耦，形成强迫性渴望记忆，即使快乐本身已经消失，对药物线索的神经反应仍被刻入突触结构。

## 当前理解

成瘾（物质使用障碍）由 Koob & Volkow（2016, PMID:27475769）描述为三阶段循环，分别对应三套不同的大脑回路：

**1. 陶醉/暴饮阶段（Binge/Intoxication）**：基底节（NAc、背侧纹状体）。所有成瘾药物均通过不同机制使 NAc 多巴胺浓度急剧升高（可卡因约 20 倍于基线，食物奖励约 3-5 倍），激活 D1-MSN，编码强烈的奖励信号。

**2. 戒断/负性情绪阶段（Withdrawal/Negative Affect）**：扩展杏仁核（central amygdala, BNST）。多巴胺基线下降，CRF（促肾上腺皮质激素释放因子）和 dynorphin 激活产生焦虑、烦躁——负性情绪成为继续用药的驱动力（**负性强化**）。

**3. 专注/渴望阶段（Preoccupation/Anticipation）**：前额叶皮层（PFC）→ NAc 谷氨酸能投射。对药物相关线索反应过度激活，同时 PFC 对非药物奖励和执行抑制功能下调。

这三个阶段形成恶性循环，每次循环都使大脑状态进一步偏离正常稳态（**allostatic shift**）。

**与习惯形成的关系**：成瘾是习惯化（DMS→DLS 行为控制权转移）的病理极端，但在 NAc 层面叠加了 ΔFosB 积累和 CP-AMPA 突触重塑，使其远超普通习惯：即使价值完全贬失（devaluation），觅药行为仍不可阻止。

## 关键机制

### 分子层：ΔFosB——持续分子开关
见 [[deltaFosB]] 页面。重复药物暴露在 NAc D1-MSN 中累积 ΔFosB（半衰期数周），调控下游基因（CDK5→树突棘↑，GluA2↑，dynorphin↓），在戒断后持续驱动行为敏化。

### 突触层：沉默突触的成熟与渴望孵化
见 [[incubation-of-craving]] 页面。NAc 在早期暴露后出现 AMPAR-silent 突触，戒断期间 CP-AMPA 插入使突触"成熟"，渴望在戒断 6-7 周时达到峰值。

### 系统层：激励显著性的选择性敏化
见 [[incentive-salience]] 页面。多巴胺系统编码 wanting（激励显著性），而非 liking（快感）；成瘾中 wanting 被敏化而 liking 下降，形成"强迫性追求已不再喜欢的东西"的临床悖论。

### 回路层：VTA-NAc-PFC 三角失衡
- VTA DA 神经元：药物后 LTP（CP-AMPA 插入），兴奋性升高，对线索更敏感
- NAc D2 受体下调：PET 成像一致显示 D2 结合力降低（无论可卡因、酒精、阿片、苯丙胺）→ 间接通路（NoGo/行为抑制）功能减弱
- PFC：对非药物奖励低激活，对药物线索过度激活；执行控制功能受损

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 所有成瘾药物均增加 NAc 多巴胺 | 微透析（大鼠，多种药物） | PMID:27475769 综述 | 高 |
| 成瘾者纹状体 D2 结合力下降 | PET（人类，跨物质一致） | PMID:27475769 综述 | 高 |
| ΔFosB 过表达增强药物奖励和动机 | 转基因小鼠行为实验（CPP, PR） | PMID:11572966 (PMC58680) | 高 |
| NAc CP-AMPA 插入介导渴望孵化 | 膜片钳+行为实验，AMPAR 阻断预防 | PMID:21338877 (PMC4046255) | 高 |
| 多巴胺增加 wanting 而非 liking | L-DOPA 人类实验；dopamine 损毁行为分离 | PMID:18640920 (PMC2607325) | 中-高 |

## 连接

- [[deltaFosB]] — 成瘾的分子开关，驱动 NAc 重编程
- [[incentive-salience]] — wanting/liking 分离，解释成瘾核心悖论
- [[incubation-of-craving]] — 戒断期渴望增强的突触机制
- [[habit-formation]] — 成瘾作为 DMS→DLS 转移的病理极端
- [[dopamine-reward-prediction-error]] — 超生理 DA 信号破坏正常 RPE 计算
- [[lateral-habenula]] — 负预测误差信号；LHb 在戒断期功能变化
- [[hpa-axis]] — 应激系统在戒断负性情绪阶段的激活
- [[prefrontal-cortex]] — 执行控制损害与渴望阶段
- [[basal-ganglia]] — 直接/间接通路失衡

## 未解问题

### Q-habit-01（高优先级）
习惯化的"不可逆点"及其与成瘾的连续谱——成瘾的 DLS 强化 + NAc CP-AMPA 共同构成物理层面的不可逆；但量化的"不可逆点"仍未确定

### Q-addiction-01（高优先级）
成瘾记忆能否被真正消除，还是只能被新的抑制性记忆覆盖？消退学习（extinction）产生的抑制，能否通过精准突触干预（类似 Ma & Dong 2016 的光遗传 LTD）转化为真正的突触重写？

### Q-addiction-02（中优先级）
ΔFosB 的适应性 vs 促成瘾作用的边界在哪里？GluA2↑（减少 CP-AMPA → 保护性）与 CDK5↑（树突棘↑ → 促成瘾）是同一转录因子的矛盾效应，二者的相对权重随成瘾阶段如何变化？

## 修订历史

- 2026-07-14 · 创建 · 基于《欲望的叛变》一文（文章 #82）· 初始置信度：高

## 来源文章

- [[2026-07-14-addiction-dopamine-deltaFosB]]

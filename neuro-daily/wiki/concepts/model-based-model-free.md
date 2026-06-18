---
title: 模型-基与模型-无强化学习（双系统）
slug: model-based-model-free
domain: concepts
type: mechanism
status: mainstream
confidence: medium
created: 2026-07-12
updated: 2026-07-12
revision_count: 1
dimensions: [brain-region, whole-brain-network, behavior, cognition, disease]
related: [actor-critic-brain, dopamine-reward-prediction-error, td-learning, basal-ganglia, prefrontal-cortex, complementary-learning-systems, fear-conditioning, glucocorticoid-stress-memory]
prerequisites: [actor-critic-brain, basal-ganglia, td-learning]
opens_questions: [Q-mb-mf-competition, Q-mb-mf-stress-switch]
source_articles: [2026-07-12-dopamine-td-learning-brain-ai]
key_sources: ["PMID:28599832", "PMID:9054347"]
---

# 模型-基与模型-无强化学习（双系统）(Model-Based vs Model-Free RL: Dual Systems)

> **一句话定义**：大脑并行运行两套强化学习系统——背内侧纹状体（DMS）支持的"模型-基"（目标导向）系统通过心理模拟评估行动结果、灵活但耗资源；背外侧纹状体（DLS）支持的"模型-无"（习惯）系统直接缓存行动-价值映射、快速但僵化——两者竞争行为控制权，其平衡随练习程度、认知负荷和情绪状态动态调整。

## 当前理解

我们现在认为，将强化学习的"模型-基（Model-Based, MB）"与"模型-无（Model-Free, MF）"框架映射到大脑是现代计算精神病学和行为神经科学的核心组织原则之一。

**两种系统的本质差异**：

| 属性 | 模型-无（MF） | 模型-基（MB）|
|------|------------|------------|
| 计算 | 缓存习得的 Q 值（行动-价值表）| 构建世界转移模型，通过心理模拟规划 |
| 速度 | 快（直接查表）| 慢（需要模拟）|
| 灵活性 | 低（结果贬值后仍会执行旧行为）| 高（结果改变立即调整行为）|
| 资源消耗 | 低 | 高（工作记忆、前额叶）|
| 大脑底物 | 背外侧纹状体（DLS）| 背内侧纹状体（DMS）+ 前额叶皮层 |
| 学习信号 | DA TD 误差 δ | 模型转移误差（世界预测误差）|
| 对应行为 | 习惯性行为（habitual）| 目标导向行为（goal-directed）|

**发展弧线**：学习早期以 MB 为主（目标导向，高灵活性），随着练习增加，MF 逐渐接管（形成习惯）。这是一种适应性分配：常见、重复的行为不需要每次都重新模拟评估。

## 关键机制

### 结果贬值测试：区分两系统的实验窗口

结果贬值（outcome devaluation）测试是区分 MB 和 MF 控制的经典范式：
1. 动物学会按杆 → 获得食物
2. 通过厌恶配对（或饱食）使食物价值降低
3. 测试按杆行为：
   - **目标导向（MB 控制）**：食物贬值 → 按杆立即减少（因为系统"知道"食物价值降了）
   - **习惯性（MF 控制）**：食物贬值 → 按杆不减少（系统缓存的是刺激-行动关联，不依赖结果价值）

背外侧纹状体损伤 → 目标导向（结果贬值有效）
背内侧纹状体损伤 → 习惯性（结果贬值无效）

### 应激对双系统平衡的影响

急性应激 → 背侧纹状体（尤其 DLS）的 DA 和去甲肾上腺素信号改变 → 从 MB（目标导向）切换到 MF（习惯性），见 glucocorticoid-stress-memory 页面的"记忆系统切换"描述（Schwabe & Wolf 2009）。

这解释了应激下的刻板行为和成瘾复发：在压力下，大脑倾向于执行习惯性行为而非目标导向的评估。

### 精神疾病中的 MB-MF 失衡

多种精神疾病可被理解为 MB-MF 比例的失衡（Voon et al. 2017, PMID:28599832）：
- **强迫症（OCD）**：MF 习惯性过度激活 → 明知无用仍重复行为
- **成瘾**：重复药物使用 → DLS 过度强化药物习惯，MF 主导 → 难以通过 MB 理性评估戒断
- **抑郁**：MB 系统功能受损 → 失去目标导向规划能力 → 回避行为和无望感

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| DLS 损伤→习惯性行为不受影响；DMS 损伤→目标导向行为受损 | 啮齿类脑区选择性损毁 + 结果贬值 | 多篇综述 | 高 |
| 人类压力 → 更多习惯性行为（MF 切换）| 急性压力 + 结果贬值测试 | PMID：多篇（包括 Schwabe & Wolf）| 中-高 |
| OCD 患者 MB 系统功能降低 | fMRI + 结果贬值任务 | PMID:28599832 综述 | 中 |

## 连接

- [[actor-critic-brain]] — Actor-Critic 中的 Actor 由 DLS（MF/习惯）和 DMS（MB/目标导向）共同构成
- [[basal-ganglia]] — DLS/DMS 的解剖细分是双系统的神经底物
- [[dopamine-reward-prediction-error]] — DA TD 误差驱动 MF 系统更新；MB 系统的世界模型更新受 DA 调制但机制不同
- [[complementary-learning-systems]] — MB 系统类比 CLS 中的海马（灵活记忆），MF 类比皮层/纹状体（慢速规律整合）
- [[glucocorticoid-stress-memory]] — 应激 GC→DA/NE 信号改变→从 MB（目标导向）切换到 MF（习惯）

## 未解问题

- Q-mb-mf-competition：DMS 和 DLS 如何在网络层面竞争控制行为输出？是否存在专门的"仲裁者"（丘脑？前扣带皮层？）在实时动态分配两系统的控制权？
- Q-mb-mf-stress-switch：应激诱导的 MB→MF 切换的精确神经化学机制是什么？糖皮质激素 vs 去甲肾上腺素 vs 多巴胺各自贡献多少？切换的时间窗口和可逆性如何？

## 修订历史

- 2026-07-12 · 创建 · 基于《奖励信号的双重发现》第 80 篇文章 · 建立 MB-MF 双系统页面；连接精神疾病计算框架（Voon 2017）和应激对系统切换的影响 · 初始置信度：中（框架广为接受，但竞争机制和精神疾病的因果方向仍有争议）

## 来源文章

- [[2026-07-12-dopamine-td-learning-brain-ai]]

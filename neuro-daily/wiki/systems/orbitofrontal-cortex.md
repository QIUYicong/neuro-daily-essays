---
title: 眶额叶皮层
slug: orbitofrontal-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-07-29
updated: 2026-07-30
revision_count: 2
dimensions: [brain-region, whole-brain-network, behavior, cognition]
related: [subjective-value-encoding, dopamine-reward-prediction-error, habit-formation, actor-critic-model, amygdala, prefrontal-cortex, basal-ganglia, vmPFC-valuation, anterior-temporal-lobe-hub, bla-valence-circuits]
prerequisites: [synaptic-transmission, dopamine-reward-prediction-error, basal-ganglia]
opens_questions: [Q-ofc-01, Q-ofc-02, Q-ofc-03]
source_articles: [2026-07-29-orbitofrontal-cortex-value-decision, 2026-07-30-bla-reward-fear-circuits]
key_sources: ["PMID:16633341", "PMID:18545266", "PMID:22145882", "PMID:29169086", "PMID:17417936", "PMID:37957318", "PMID:36062909"]
---

# 眶额叶皮层 (Orbitofrontal Cortex, OFC)

> **一句话定义**：前额叶腹侧区域（Walker's area 11/13），是大脑"价值地图"的核心节点——整合来自所有感觉模态、杏仁核和海马的信息，将多维奖励属性编码为与感觉和动作无关的抽象主观价值信号，支持灵活的目标导向决策；并与BLA形成四向协作回路，分工驱动奖励记忆的编码（lOFC）和检索用于决策（mOFC）。

## 当前理解

我们现在认为，眶额叶皮层（OFC）是大脑将多维感觉信息转化为可比较的主观价值信号的核心区域。该区域约三分之一的神经元在选择前延迟期精确编码选项的主观价值，且这种编码独立于视觉位置和运动方向（Padoa-Schioppa & Assad 2006）——这是"goods-based value space"（商品价值空间）假说的直接细胞证据。

OFC的价值编码不是静态的价格标签，而是一个动态的比较过程：OFC神经集群在决策前在两个选项的表征态之间快速交替，被选择选项的神经表征主导程度预测决策速度（Rich et al. 2018）。

此外，OFC同时运行两种时间尺度的学习：快速的RPE驱动的试错学习，以及依赖CaMKII突触可塑性的慢速元学习（cross-session meta-RL，Hattori et al. 2023）。

## 关键机制

### 解剖输入：多模态感觉汇聚
OFC是前额叶中唯一直接接受所有感觉模态投射的区域（Wallis 2007）：
- 嗅觉（来自嗅梨状皮层，不经丘脑）
- 味觉（来自脑岛前部/次级味觉皮层）
- 视觉（来自颞叶腹侧流高阶区TEO/TE）
- 体感/内脏（来自脑岛、前扣带回）
- 杏仁核（情绪价值评估）
- 海马（情景记忆上下文）

### 三个功能子区
- **内侧OFC（约等于vmPFC）**：奖励质量编码；与杏仁核强烈相连；情绪价值的初始分配
- **中央OFC（Walker area 13）**：价值**更新**核心；当奖励大小/概率/状态改变时最先反应
- **外侧OFC（Walker area 12）**：负性价值信号（惩罚、风险、厌恶）；外侧损伤→冲动性

### 三类价值神经元（Padoa-Schioppa 2006）
1. **Offer-value A neurons**：编码选项A的主观价值（与位置和动作无关）
2. **Offer-value B neurons**：编码选项B的主观价值
3. **Chosen-value neurons**：选择完成后编码被选选项的价值

### OFC在三系统框架中的角色
OFC为**目标导向系统**（goal-directed/model-based system）提供"结果的当前主观价值"。当生理状态改变（口渴→饱腹），OFC的食物价值信号实时下调，使目标导向系统立即调整策略。OFC损伤 → 动物/患者过度依赖习惯系统，无法根据结果贬值更新行为。

### vmPFC的dlPFC调制（人类特有扩展）
在人类中，dlPFC通过调制vmPFC的价值权重实现自我控制：dlPFC越活跃，vmPFC越倾向于整合认知目标（如健康考虑），而非仅响应即时感官偏好（Hare et al. 2009, PMID:19407204）。

### BLA-OFC双向协作

BLA与OFC之间存在四向精密分工的协作回路，共同支持状态依赖的、结果特异性奖励记忆的编码与决策使用（Wassum 2022，PMID:36062909）：

**编码轴**（奖励记忆写入BLA）
- **lOFC → BLA**：驱动状态依赖的结果特异性奖励记忆的**编码**。lOFC将当前内部状态（饥饿、口渴、当前偏好）与特定奖励的身份信息整合，指导BLA将这一组合写入长期记忆。
- **BLA → lOFC**：BLA向lOFC反馈**奖励身份（identity）**——是哪一种具体的奖励，而非泛化的奖励驱动状态。

**决策轴**（奖励记忆提取用于选择）
- **mOFC → BLA**：当面临决策时，mOFC驱动BLA**检索**相关的奖励记忆，使之可供决策使用。
- **BLA → mOFC**：BLA向mOFC传递**预测事件的当前价值（value）**——当下这个奖励对当前生理状态值多少，而非记忆中的历史价值。

**理论意义**：这个四向回路将BLA（结果特异性情绪记忆库）与OFC（主观价值计算器）整合为一个双向互塑系统，而非传统的单向"杏仁核情绪信号→OFC价值评估"模型。lOFC/mOFC的功能分工（编码 vs 决策）体现了奖励记忆的两个阶段在解剖上的分离。

**注意**：该回路证据主要来自大鼠实验（光遗传回路操控），lOFC与mOFC在人类脑区中的严格对应关系尚待明确。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| OFC神经元编码行为无关的商品价值 | 猕猴单单元记录，随机化空间位置 | Padoa-Schioppa & Assad 2006（PMID:16633341） | 高 |
| OFC价值信号因果性影响决策速度和准确度 | 猕猴药理学抑制OFC | Setogawa et al. 2019（PMID:30963114） | 高 |
| 人类vmPFC整合多维价值；dlPFC调制价值权重 | 人类fMRI，味道×健康性设计 | Hare et al. 2009（PMID:19407204）| 高（未读全文） |
| OFC神经集群动态在两选项间交替，主导程度预测决策速度 | 猕猴集群电生理 | Rich et al. 2018（PMID:29169086） | 中-高 |
| OFC运行双层学习（快速RPE + 慢速CaMKII元学习） | 小鼠钙成像+光遗传学+CaMKII干预 | Hattori et al. 2023（PMID:37957318） | 高（仅小鼠） |
| OFC损伤→贬值实验中行为不更新，冲动性决策 | 人类和动物损伤研究 | Wallis 2007综述（PMID:17417936） | 高 |
| lOFC→BLA驱动结果特异性奖励记忆编码；mOFC→BLA驱动记忆用于决策 | 大鼠回路特异性光遗传干预 | Wassum 2022（PMID:36062909） | 高（大鼠） |

## 连接

- [[subjective-value-encoding]] — OFC是主观价值编码的核心实现脑区
- [[dopamine-reward-prediction-error]] — DA-RPE（多巴胺奖励预测误差）是OFC快速学习的更新信号
- [[habit-formation]] — OFC损伤导致过度依赖习惯系统（目标导向 vs. 习惯的竞争）
- [[actor-critic-model]] — OFC提供"critic"所需的价值估计（结果的当前主观价值）
- [[amygdala]] — 杏仁核向OFC传递情绪价值信号；四向BLA-OFC回路共同支持奖励记忆编码与决策（Wassum 2022）
- [[prefrontal-cortex]] — dlPFC通过调制vmPFC/内侧OFC实现高阶目标对价值的调控
- [[basal-ganglia]] — OFC价值输出传递给腹侧纹状体（伏隔核）完成选择执行
- [[bla-valence-circuits]] — BLA双通道是OFC-BLA四向协作的BLA端基础；lOFC/mOFC分别对接BLA的记忆写入和检索功能

## 未解问题

- Q-ofc-01（高优先级）：OFC的元学习机制（CaMKII）是否在人类中存在直接证据？
- Q-ofc-02（中优先级）：OFC动态编码（Rich 2018，50-66%的神经元情境依赖）与Padoa-Schioppa的稳定编码是否真正矛盾？
- Q-ofc-03（中优先级）：人类vmPFC和猕猴OFC是否严格功能同构？额叶的人类特化如何影响价值计算？

## 修订历史

- 2026-07-29 · 创建 · 基于《价值的地图：眶额叶皮层如何计算什么值得追求》一文 · 初始置信度：高
- 2026-07-30 · 修订 rev2 · 基于《情绪的两条轨道》(#98) · 新增BLA-OFC双向协作小节（Wassum 2022）：lOFC→BLA（记忆编码）、mOFC→BLA（决策使用）、BLA→lOFC（奖励身份）、BLA→mOFC（价值表征）；related新增bla-valence-circuits；key_sources新增PMID:36062909；关键证据表添加1行；连接新增bla-valence-circuits条目；updated→2026-07-30

## 来源文章

- [[2026-07-29-orbitofrontal-cortex-value-decision]]
- [[2026-07-30-bla-reward-fear-circuits]]

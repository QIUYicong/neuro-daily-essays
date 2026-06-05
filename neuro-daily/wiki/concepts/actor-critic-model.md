---
title: 演员-批评家模型（基底节的强化学习架构）
slug: actor-critic-model
domain: concepts
type: theory
status: mainstream
confidence: medium
created: 2026-07-13
updated: 2026-07-29
revision_count: 2
dimensions: [microcircuit, brain-region, cognition, behavior]
related: [basal-ganglia, dopamine-reward-prediction-error, habit-formation, prefrontal-cortex, working-memory, predictive-coding, complementary-learning-systems, orbitofrontal-cortex, subjective-value-encoding]
prerequisites: [basal-ganglia, dopamine-reward-prediction-error, hebbian-learning]
opens_questions: [Q-actor-critic-01, Q-actor-critic-02]
source_articles: [2026-07-13-striatum-direct-indirect-pathway-habit, 2026-07-29-orbitofrontal-cortex-value-decision]
key_sources: ["PMID:27069376", "PMID:30413646", "PMID:26961942", "PMID:9054347", "PMID:18545266", "PMID:16633341", "PMID:37957318"]
---

# 演员-批评家模型（基底节的强化学习架构）(Actor-Critic Model)

> **一句话定义**：在基底节中，腹侧纹状体（伏隔核）作为"批评家"学习状态价值函数并计算时序差分误差（TD误差），背侧纹状体作为"演员"利用批评家的误差信号更新动作策略——这一架构将多巴胺奖励预测误差（DA-RPE）具体化为神经计算算法的角色分工。

## 当前理解

我们现在认为，基底节的功能分区（腹侧 vs 背侧纹状体）对应强化学习理论中的一个经典架构：

**批评家（Critic）= 腹侧纹状体（伏隔核，NAc）**：
- 功能：学习状态价值函数 V(s)——当前状态预期能获得多少未来总奖励
- 输出：**时序差分误差**（TD error）δ = r(t) + γV(s') − V(s)
- 这个 δ 正好对应中脑 DA 神经元的相位放电模式（Schultz 1997, PMID:9054347）
- 神经实现：NAc 接收来自 vmPFC/OFC/海马/杏仁核的"状态评估"输入；DA 神经元的爆发/抑制 = δ 的正/负

**演员（Actor）= 背侧纹状体（DMS + DLS）**：
- 功能：维护并更新动作-状态的选择策略 π(a|s)
- 学习：根据批评家提供的 TD 误差，通过三因素学习规则（突触前×突触后×DA）更新纹状体 D1/D2-MSN 的突触权重
- 更新规则：Δπ(a|s) ∝ δ × e(a,s)（其中 e 为资格迹，记录近期状态-动作对）

**层级化分工（Haber 2016，PMID:27069376）**：
- 腹侧纹状体（批评家）学习价值 → 通过螺旋连接影响背侧纹状体（演员）的学习进程
- 背内侧纹状体（演员/目标导向）：接近批评家，受 vmPFC/OFC 驱动，实现 model-based 策略
- 背外侧纹状体（演员/习惯）：更独立于批评家，依赖 S-R 权重，实现 model-free 策略

## 关键机制

### TD 误差的神经实现

中脑 DA 神经元的放电可被量化为 TD 误差（Schultz 1997, PMID:9054347）：
- δ > 0（超预期奖励）→ DA 爆发（>30 Hz，持续~200ms）→ 增强刚执行动作的突触权重
- δ = 0（符合预期）→ DA 基线 → 不更新（学习完成）
- δ < 0（低于预期）→ DA 抑制 → 削弱刚执行动作的权重

DA 通过D1/D2受体对直接/间接通路的差异性调节，实现"赢者更强，输者更弱"的竞争性动作选择更新。

### 演员内部的 model-based vs model-free 双轨

Groman et al. 2019（PMID:30413646，PMC6325257，开放全文）和 Piray et al. 2016（PMID:26961942，PMC6601762，开放全文）提供了人类/大鼠的双系统证据：

| 特征 | Model-based（目标导向） | Model-free（习惯） |
|------|----------------------|----------------|
| 神经底物 | DMS + vmPFC/OFC | DLS |
| 对结果价值的敏感性 | 高（实时评估） | 低（与价值脱钩）|
| 计算复杂性 | 高（需要内部世界模型）| 低（直接S-R联结）|
| 解剖连接强度 | vmPFC→内侧纹状体 FA 越高越依赖此轨道 | - |
| 奖励贬值 | 敏感（减少动作）| 不敏感 |

### 成熟度与更新

批评家功能（腹侧 DA-RPE）的成熟度高（Schultz 系列实验多物种复现）；演员内部的 model-based/model-free 解离证据在人类研究中持续积累，但解剖精确性仍有争议（DMS 与 DLS 的严格功能分界不如啮齿类清晰）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| DA 神经元放电 = TD 误差（批评家输出）| 清醒猕猴单神经元记录 + 巴甫洛夫/操作性任务 | PMID:9054347 | 高 |
| model-based（goal-directed）与皮层-纹状体DA张力相关 | 大鼠多步任务+神经化学 | PMID:30413646（PMC6325257）| 中（单实验室）|
| vmPFC→内侧纹状体 FA 预测 model-based 策略 | 人类 DTI + 决策任务 | PMID:26961942（PMC6601762）| 中（单实验室）|
| 腹侧→背侧纹状体螺旋连接作为架构基础 | 灵长类解剖示踪 + 人类 DWI | PMID:27069376（PMC4826773）| 高 |

## 连接

- [[basal-ganglia]] — 演员-批评家架构在基底节的解剖实现（腹侧=批评家，背侧=演员）
- [[dopamine-reward-prediction-error]] — DA-RPE 是批评家输出 TD 误差的神经实现
- [[habit-formation]] — model-free 演员 = DLS 习惯系统；model-based 演员 = DMS 目标导向系统
- [[prefrontal-cortex]] — PFC 提供演员系统的 model-based "世界模型"计算
- [[complementary-learning-systems]] — 演员-批评家 BG 框架与 CLS 理论（海马快学习+新皮层慢学习）并行，各解决不同的时间尺度学习问题
- [[predictive-coding]] — 批评家的 TD 误差等同于奖励域的预测误差（Diederen & Fletcher 2021）

## 未解问题

- **Q-actor-critic-01**（新建，高优先级）：批评家（NAc）和演员（背侧纹状体）的功能分工是否绝对，还是两者均可接近批评家功能（即背侧纹状体也能局部计算 TD 误差，只是精度较低）？Groman 2019 的数据指向背侧纹状体 DA 张力也相关，这与纯粹的批评家-腹侧定位矛盾。
- **Q-actor-critic-02**（新建，中优先级）：演员-批评家框架如何解释在新颖环境（完全未知状态空间）中的探索行为？标准 TD 框架在初始阶段缺乏先验 V(s)——大脑是否通过前额叶或海马提供"初始化的V(s)"，还是通过好奇心/新颖性驱动的 DA 信号完成初始探索？

## OFC 作为批评家的"价值输入源"

（2026-07-29 新增，来自文章 #97）

标准 actor-critic 框架中，批评家（NAc/腹侧纹状体）学习状态价值函数 V(s)。但 V(s) 的计算需要外部输入——当前状态"值多少"不是纹状体自主计算的，而是依赖来自 OFC 的**结果当前价值信号**：

- OFC（眶额叶皮层）的三类价值神经元（Padoa-Schioppa & Assad 2006, PMID:16633341）在延迟期编码选项主观价值，随生理状态实时更新
- 这个来自 OFC 的价值信号投射到腹侧纹状体（伏隔核 NAc），为批评家的 V(s) 提供"结果维度的当前价值"
- 没有 OFC 的实时价值更新，批评家只能依赖历史的 S-R 权重（即退化为纯 model-free）

Rangel 框架（2008, PMID:18545266）的三系统架构中，目标导向系统 = DMS（演员的 model-based 轨道）+ OFC（批评家的价值输入源）。OFC 损伤 → 批评家接收的结果价值信息过时 → 贬值不敏感 → 行为外表为"纯习惯"。

**OFC 的元学习扩展**（Hattori et al. 2023, PMID:37957318）：OFC 内部还通过 CaMKII 可塑性积累跨会话的"任务结构知识"，相当于在 actor-critic 框架上增加了一层元学习，使批评家的 V(s) 初始化更准确（而非从随机初始化开始）。

## 修订历史

- 2026-07-13 · 创建 · 基于《行动的仲裁者：纹状体如何决定你该动还是不动》(#81) · 初始置信度：中（批评家-腹侧 DA 关联证据强；演员分区和model-based/free 双轨的精确神经解剖尚有争议）
- 2026-07-29 · 修订 · 基于《价值的地图》文章 #97 · 新增"OFC 作为批评家的价值输入源"小节；补充 OFC → NAc 的价值信号投射；Rangel 2008 三系统框架与 actor-critic 的对应；Hattori 2023 元学习扩展；related 新增 orbitofrontal-cortex, subjective-value-encoding；key_sources 新增 PMID:18545266, 16633341, 37957318

## 来源文章

- [[2026-07-13-striatum-direct-indirect-pathway-habit]]
- [[2026-07-29-orbitofrontal-cortex-value-decision]]

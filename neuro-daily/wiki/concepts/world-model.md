---
title: 世界模型
slug: world-model
domain: concepts
type: theory
status: emerging
confidence: medium
created: 2026-05-31
updated: 2026-09-18
revision_count: 3
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, whole-brain-network, behavior, cognition]
related: [predictive-coding, default-mode-network, global-workspace-theory, fear-conditioning, dopamine-reward-prediction-error, serotonin-raphe-system, basal-ganglia, hippocampal-circuit, memory-consolidation, engram-cells, temporal-hierarchy, sharp-wave-ripples, integrated-information-theory, successor-representation, cognitive-map]
prerequisites: [predictive-coding, ltp, hebbian-learning, synaptic-transmission, temporal-hierarchy]
opens_questions: [Q-pc-02, Q-dmn-04, Q-gwt-04, Q-iit-02, Q-iit-03]
source_articles: [2026-05-31-week4-synthesis, 2026-05-31-may-monthly-synthesis, 2026-09-18-hippocampal-successor-representation-simulation]
key_sources: ["PMID:20068583", "PMID:10195184", "PMID:23177956", "PMID:21677128", "PMID:32135090", "PMID:40307561", "PMID:24206127", "PMID:28967910", "PMID:38849521", "PMID:17229836", "PMID:40065137"]
---

# 世界模型 (World Model / Internal Generative Model)

> **一句话定义**：大脑对外部世界和自身状态持续维护的当前最佳贝叶斯估计，是一套被感觉预测误差、调质信号和离线整合不断更新的分布式动态表征，而非静态数据结构。

## 当前理解

我们现在认为，大脑不是被动的输入-输出机器，而是主动的世界模型建构者。这一观点有三个核心来源：

1. **认知地图传统**（Tolman 1948）：动物不只学习刺激-反应链，而是内部维护对环境的结构性表征（认知地图），以支持灵活的目标导向行为。
2. **预测编码框架**（Rao & Ballard 1999, PMID:10195184；Friston 2010, PMID:20068583）：皮层层级系统不断生成对感觉输入的预测，只将预测误差向上传递；感知是推断世界状态的过程（Bayesian inference）。大脑维护的「生成模型」就是世界模型。
3. **多系统整合**：海马认知地图（场所细胞/网格细胞）、默认模式网络离线仿真、情感系统高权重标注、调质系统精度调控，共同构成了世界模型不同子层的神经实现。

**六层架构**（来自第四周综合，文章 #28，2026-05-31）：

| 层级 | 机制/系统 | 功能 | 时间尺度 |
|------|---------|------|---------|
| 化学调控层 | 5-HT/DA/NE/ACh | 情感权重与学习率 | 分钟→天 |
| 运动预测层 | 基底节/纹状体/SNc | 行动遴选与运动状态预测 | 毫秒→秒 |
| 情感标注层 | BLA/杏仁核 | 威胁事件高权重永久写入 | 秒→终身 |
| 误差加权层 | 皮层层级/预测编码 | 最小化加权预测误差来更新模型 | 毫秒→秒 |
| 离线仿真层 | DMN/海马/mPFC | 情节重构、社会仿真、先验维护 | 秒→分钟 |
| 意识广播层 | GWT/PFC-顶叶网络 | 重要模型更新的全脑广播 | 毫秒（点燃） |

**不确定性说明**：「六层架构」是本文提出的整合框架，不是来自单一实验或单一理论——它是对已有神经科学发现的概念组织工具。其具体的层级边界、层间交互机制和完备性，需要未来研究的明确验证。

## 关键机制

### 贝叶斯更新原理

世界模型的更新遵循贝叶斯推断原理：

```
新的后验估计 ∝ 先验（当前模型）× 似然（感觉数据）
```

在神经实现中（预测编码框架）：
- **先验**：由高层皮层的反馈信号（α/β 振荡，L5/6 深层）传递
- **预测误差**：由低层皮层浅层（L2/3，γ 振荡）计算并上传
- **精度加权**：调质系统（ACh/NE/DA）调节误差信号的影响权重

### 情感权重标注（边缘系统）

杏仁核（BLA）为特定事件赋予「紧急度」权重——威胁经历通过 LA-LTP 获得几乎不可逆的高权重标注，使这些模型内容在注意竞争中永远占有优先权。

### 离线维护（DMN + 海马）

世界模型在外部输入减少时（睡眠/静息）依然运行：
- SWR 重播（海马）：压缩并巩固近期经历为长期模型
- DMN 仿真：情节模拟、社会状态推断、自我叙事整合

### 意识广播（全局工作空间）

当某个模型更新被判定足够重要时，全局工作空间「点燃」将该更新广播至全脑，使其对所有处理模块全局可得——这被认为是有意识知觉的神经基础。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 大脑维护对环境的结构性表征 | 场所细胞/网格细胞；认知地图 | PMID:15965463 (O'Keefe & Dostrovsky) | 高 |
| 预测编码：皮层只传递误差 | V1 失配响应；振荡分层（γ/α-β） | PMID:22681686（全文）; PMID:23177956（摘要） | 中（振荡分工有挑战）|
| DMN 负责世界模型的离线维护 | 功能磁共振功能连接；情节记忆任务 | PMID:21677128（全文） | 中 |
| 意识广播世界模型重要更新 | GWT 点燃证据（P3 波、晚期放大） | PMID:32135090（全文）; PMID:40307561（全文） | 中 |
| 六层架构整合 | 今日综合框架（非直接实验结论） | 文章 #28（2026-05-31）| 低（概念框架） |

## 连接

- [[predictive-coding]] — 预测编码是世界模型更新机制的形式化描述
- [[default-mode-network]] — DMN 是世界模型的离线仿真和先验维护系统
- [[global-workspace-theory]] — GWT 描述世界模型重要更新如何进入意识
- [[fear-conditioning]] — 恐惧记忆是世界模型情感标注层的高权重写入
- [[dopamine-reward-prediction-error]] — DA-RPE 是世界模型奖励预测层的误差信号
- [[basal-ganglia]] — 基底节是世界模型运动预测层的核心门控结构
- [[hippocampal-circuit]] — 海马是世界模型空间/情节表征的关键实现结构
- [[memory-consolidation]] — 系统巩固是世界模型长期版本的写入过程
- [[engram-cells]] — 印迹细胞是世界模型中特定记忆的细胞基底

## 未解问题

- **Q-pc-02**：自由能原理是否足够可证伪？「世界模型」框架的最强实验预测是什么？
- **Q-dmn-04**：DMN 与全局工作空间（GWT）的精确关系——两者如何协同维护和广播世界模型内容？
- **Q-gwt-04**：GWT 与预测编码能否整合为统一框架？整合点在哪里？
- **世界模型的「自我」层**（新问题，无编号）：自我参照处理（mPFC 的自传体记忆功能）如何与上述六层整合？「主观体验者」如何在神经层面涌现？

## 世界模型的仿真引擎层（2026-09-18 更新）

第148篇文章《大脑的时间机器》提供了关于世界模型**仿真执行层**的关键新证据：

**海马作为仿真引擎**：Stachenfeld等（2017，PMID:28967910）提出的**后继者表征（SR）**框架表明，海马编码的不是几何坐标，而是"从当前状态出发，未来状态分布"的预测表征。这使海马认知地图天然成为仿真的底层引擎。

**重放=策略展开**：Jensen等（2024，PMID:38849521）证明，海马SWR重放在统计特征上与AI世界模型中的"政策展开（policy rollout）"完全一致。这将世界模型的"离线仿真层"从概念层面下沉到了具体的神经机制：**SWR期间的重放是世界模型执行前向仿真的物理载体**。

**想象与记忆共享引擎**：Hassabis等（2007，PMID:17229836）发现，海马损伤遗忘症患者不只是不能回忆过去，也不能想象从未经历的新场景——这将"世界模型的预测/仿真功能"直接定位到海马这一底层设施。

**人类颅内证据**：Seeber等（2025，PMID:40065137）首次在人类颅内记录中证明，想象导航时海马θ振荡与真实导航统计上完全一致，进一步支持"想象是世界模型在θ框架驱动下的主动仿真"这一机制。

**六层架构的修订**：在原六层框架中，"离线仿真层（DMN/海马/mPFC）"现可以细化为：
- **SR底层**：海马场所细胞编码SR矩阵；网格细胞提供SR的基函数分解
- **SWR执行层**：SWR驱动SR空间上的策略展开，生成具体仿真序列
- **mPFC调度层**：前额皮层作为元控制者，决定何时/多深地展开仿真
- **DMN整合层**：默认模式网络提供情节/社会背景的整合（Huang 2024，PMID:39169063）

## 修订历史

- 2026-05-31 · 创建 · 基于《第四周综合：当大脑成为自己的宇宙》(#28) · 初始置信度：中（整合框架，非单一实验结论）
- 2026-05-31 · 修订（月度综合）· 基于《五月月报·大图景》(#31) · 将六层架构升级为八层、补充时间层级维度（分子→终身）、新增 COGITATE 2025 对 GWT/IIT 两个顶层意识理论的挑战作为关键证据 · related 新增 temporal-hierarchy、sharp-wave-ripples、integrated-information-theory
- 2026-09-18 · 修订 rev3 · 基于《大脑的时间机器》文章 (#148) · 新增"世界模型仿真引擎层"小节（SR框架/SWR=策略展开/想象共享神经底物/θ框架的人类证据）；related 新增 successor-representation、cognitive-map；key_sources +4（SR/仿真核心论文）；六层架构离线仿真层细化

## 来源文章

- [[2026-05-31-week4-synthesis]]
- [[2026-05-31-may-monthly-synthesis]]

---
title: 主观价值编码
slug: subjective-value-encoding
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-29
updated: 2026-07-29
revision_count: 1
dimensions: [cellular, brain-region, whole-brain-network, cognition, behavior]
related: [orbitofrontal-cortex, dopamine-reward-prediction-error, habit-formation, actor-critic-model, working-memory, amygdala, interoception, anterior-insula]
prerequisites: [dopamine-reward-prediction-error, synaptic-transmission, action-potential]
opens_questions: [Q-sval-01, Q-sval-02]
source_articles: [2026-07-29-orbitofrontal-cortex-value-decision]
key_sources: ["PMID:16633341", "PMID:18545266", "PMID:22145882", "PMID:19407204"]
---

# 主观价值编码 (Subjective Value Encoding)

> **一句话定义**：大脑将不同选项的多维属性（大小、概率、延迟、感官偏好、认知目标）整合为单一可比较数值的过程，核心神经底物是眶额叶皮层（OFC）和腹内侧前额叶（vmPFC），这一过程支持了从Pavlovian学习到复杂目标导向决策的所有层次的选择行为。

## 当前理解

我们现在认为，主观价值编码是大脑决策系统的核心中间步骤：在感觉表征（"这是什么食物"）和行为执行（"我要按左键"）之间，大脑必须构建一个**与具体感觉和动作无关的价值表征层**（Rangel et al. 2008）。

这个价值层的核心特性：
1. **跨维度整合**：将大小、概率、时间延迟、主观偏好等异质维度压缩为单一数值
2. **状态依赖**：随当前生理状态（饥饿/饱腹、情绪）实时更新
3. **行为无关**：同一价值信号可支持多种不同的执行动作（手动、眼动、语音选择）

Padoa-Schioppa & Assad（2006）在猕猴OFC中发现的**三类价值神经元**（offer-value-A、offer-value-B、chosen-value）提供了主观价值编码的直接细胞级证据，确认了其"goods-based"（商品基础）而非"action-based"（行动基础）的编码格式。

## 关键机制

### 三个价值系统的竞争框架（Rangel et al. 2008）

| 系统 | 计算方式 | 神经底物 | 局限 |
|------|---------|---------|------|
| 巴甫洛夫系统 | 进化预设的刺激-价值关联 | 杏仁核+腹侧纹状体 | 仅限天生重要刺激 |
| 习惯系统（model-free） | 刺激-反应统计积累 | 背外侧纹状体 | 贬值后行为不立即更新 |
| 目标导向系统（model-based） | 行为→结果→OFC当前价值 | 背内侧纹状体+OFC+PFC | 计算昂贵 |

### 价值信号的时序（OFC层面）
在选择前延迟期：
1. **Offer-value信号**（双选项各自价值编码）出现
2. **动态比较过程**：神经集群在两选项表征态间交替切换
3. **Chosen-value信号**出现，确认最终选择

### vmPFC的多属性整合与dlPFC调制
vmPFC将OFC基本价值信号与认知目标（健康、道德、规则）结合；dlPFC通过调制vmPFC权重，将高阶目标"写入"价值计算：
- 高dlPFC活动 → vmPFC更多整合认知目标 → 自我控制行为
- 低dlPFC活动/损伤 → vmPFC主要响应即时感官偏好 → 冲动行为

### 价值更新的两个时间尺度
- **快速**（ms-s）：多巴胺RPE驱动的即时价值更新
- **慢速**（days-sessions）：CaMKII依赖的突触可塑性驱动的元学习（Hattori et al. 2023）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| OFC神经元编码行为无关的商品价值 | 猕猴单单元记录，空间控制 | PMID:16633341（Padoa-Schioppa 2006） | 高 |
| 价值编码是"goods-based"而非"action-based" | 双选项随机化位置和动作方向 | PMID:22145882（Padoa-Schioppa 2011综述） | 高 |
| 人类vmPFC整合多维价值，dlPFC调制其权重 | 人类fMRI，2×2味道×健康性设计 | PMID:19407204（Hare et al. 2009）| 高（未读全文）|
| 目标导向vs习惯系统的竞争决定行为灵活性 | 贬值实验（lesion+化学遗传学）| PMID:18545266（Rangel综述+原始文献）| 高 |

## 连接

- [[orbitofrontal-cortex]] — 主观价值编码的核心神经底物（OFC）
- [[dopamine-reward-prediction-error]] — 提供价值更新所需的误差信号（RPE）
- [[habit-formation]] — 习惯系统（model-free）与目标导向系统（model-based）的竞争框架
- [[actor-critic-model]] — 主观价值是actor-critic中critic模块的输出
- [[amygdala]] — 提供情绪性价值信号输入（恐惧、吸引力）
- [[interoception]] — 内感受状态（口渴、饱腹、情绪）决定价值信号的当前基础水平
- [[anterior-insula]] — 将内感受信号传递给价值计算系统

## 未解问题

- Q-sval-01（高优先级）：价值信号是单一标量还是多维向量？OFC是真正将多维属性"压缩"成一维，还是维持多维价值表征供下游整合？
- Q-sval-02（中优先级）：主观价值编码与自我意识的关系——没有自我意识的系统（如虫类神经回路）能否实现真正意义上的"主观价值"？

## 修订历史

- 2026-07-29 · 创建 · 基于《价值的地图：眶额叶皮层如何计算什么值得追求》一文 · 初始置信度：高

## 来源文章

- [[2026-07-29-orbitofrontal-cortex-value-decision]]

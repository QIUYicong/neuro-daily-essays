---
title: 三因素学习规则
slug: three-factor-learning-rule
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-06-07
updated: 2026-06-07
revision_count: 1
dimensions: [synaptic, cellular, cognition, behavior]
related: [hebbian-learning, dopamine-reward-prediction-error, ltp, synaptic-tagging-capture, ampa-receptor, camkii, engram-cells, competition-selection-principle]
prerequisites: [hebbian-learning, ltp, synaptic-transmission, nmda-receptor]
opens_questions: [Q-three-factor-time-window, Q-stc-molecular-tag]
source_articles: [2026-06-07-dopamine-reward-prediction-error]
key_sources: ["PMID:12371508", "PMID:9054347", "PMID:8774460", "PMID:9020359", "PMID:7708662"]
---

# 三因素学习规则 (Three-Factor Learning Rule)

> **一句话定义**：突触权重的改变不仅由局部 Hebbian 条件（突触前 × 突触后活动）决定，还需要全局调制信号（第三因素，如多巴胺）的"许可"：**Δw ∝ (pre × post) × M**，这使突触可塑性具有方向性和选择性，能够被全局目标（奖励、注意、显著性）所导向。

## 当前理解

我们现在认为，经典 Hebbian 规则（二因素：Δw = η × pre × post）描述了突触可塑性的必要条件，但不是充分条件——至少在行为意义的学习中，需要第三因素的"评估"。三因素学习规则写成：

**Δw = η · (pre × post) × M**

其中 M 是全局调制信号，对于不同学习类型有不同底物：
- **奖励学习**：M = 多巴胺（DA）浓度变化（来自 VTA/SNc）
- **注意调制**：M = 乙酰胆碱（ACh）（来自基底前脑胆碱能神经元）
- **显著性/应激**：M = 去甲肾上腺素（NE）（来自蓝斑）

三个关键含义：
1. **必要性**：M 和 Hebbian 激活都是必要条件，缺一不可（乘法，不是加法）
2. **方向性**：M > 0（DA 爆发）→ LTP；M < 0（DA 抑制）→ LTD；M = 0 → 无变化
3. **选择性**：M 作为全局广播，只强化"最近被 Hebbian 激活的突触"——选择性由 Hebbian 条件而非 M 本身实现

**最直接实验证据**（Reynolds & Wickens 2002）：在纹状体皮层-纹状体突触，高频皮层刺激（Hebbian）+ DA 脉冲 → LTP；单独 Hebbian 激活或单独 DA 均不诱导 LTP；三因素的乘法逻辑在纹状体得到直接验证。

## 关键机制

### 奖励学习（DA 作为第三因素）

```
突触前活动（谷氨酸释放）
    + 突触后去极化（AMPAR/NMDAR激活）
    = Hebbian 激活 → Ca²⁺ 内流 → CaMKII 激活 → 设置"突触标签"

                                    +

DA 爆发（RPE > 0）
    → D1/D5 激活 → cAMP↑ → PKA
    → ① GluA1 Ser845 磷酸化（E-LTP 增强）
    → ② CREB 磷酸化 → PRPs 合成（被突触标签捕获 → L-LTP）

= 三因素 LTP（比单独 Hebbian 激活更持久、更强）
```

DA 抑制（δ < 0）时，通过 D2 受体 → Gi → cAMP↓ → PP2B/PP1 级联 → AMPAR 去磷酸化 → 三因素 LTD。

### 注意调制（ACh 作为第三因素）

基底前脑胆碱能神经元（Ch1-Ch4）在注意任务中被激活，释放 ACh 到皮层。ACh 通过：
- M1 受体（突触后）：增强 NMDAR 的 Ca²⁺ 内流，放大 Hebbian 激活
- nAChR（突触前）：增加皮层谷氨酸释放，增强 pre 因素

使注意焦点内的刺激表征优先被 Hebbian 强化——注意力改变学习的选择性（而非方向性）。

### 纹状体 D1/D2 双通道实现

纹状体 D1-SPNs（直接通路）和 D2-SPNs（间接通路）是三因素规则的对称实现：

| | D1-SPNs（Go） | D2-SPNs（No-Go） |
|--|--------------|-----------------|
| DA 爆发（正 RPE） | LTP（强化正确行动） | LTD（削弱竞争行动） |
| DA 抑制（负 RPE） | LTD（削弱错误行动） | LTP（强化回避行动） |
| DA 基线 | 无变化 | 无变化 |

这一双通道设计使大脑**同时学习"做什么"和"不做什么"**，比单纯正向强化高效得多。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 纹状体三因素乘法规则（pre × post × DA = LTP）| 纹状体-皮层突触电生理 + 多巴胺精控 | PMID:12371508 | 高 |
| DA 是奖励学习必要条件（不只是充分） | 6-OHDA 损毁 DA 系统的学习缺陷 + 光遗传 DA 激活替代奖励 | 多篇；基于综述 | 高 |
| D1→cAMP→PKA→L-LTP（海马） | D1/D5 激动剂诱导 CA1 L-LTP；茴香霉素阻断 | PMID:7708662（PMC42234） | 高 |
| ACh 调制 NMDAR 增强 Hebbian 激活 | M1 受体阻断消除 ACh 的学习促进效果 | 多篇；基于综述 | 中-高 |

## 连接

- [[hebbian-learning]] — 三因素规则是 Hebb 规则的扩展：加入全局调制因子 M，使突触可塑性有了方向性和行为意义
- [[dopamine-reward-prediction-error]] — DA-RPE 是奖励学习中 M 因素的主要来源
- [[ltp]] — 三因素规则的正向（DA > 0）结果是 LTP；D1→PKA→CREB 是 DA 诱导 L-LTP 的分子链
- [[synaptic-tagging-capture]] — 突触标记（Hebbian 产物）+ 捕获（DA 驱动的 PRP 合成）是三因素规则的时间整合机制
- [[camkii]] — Hebbian 激活 → Ca²⁺ → CaMKII 激活可能是"突触标签"的分子身份（假说）
- [[ampa-receptor]] — 三因素 LTP 最终通过 AMPAR 插入/磷酸化表达
- [[engram-cells]] — CREB 竞争性分配（印迹细胞选择）可能受 DA 三因素规则调制
- [[competition-selection-principle]] — 三因素规则在细胞层面实现了竞争性突触遴选

## 未解问题

- Q-three-factor-time-window：三因素规则中 Hebbian 激活与 DA 信号之间的有效时间窗口（标签有效期）在不同脑区和突触类型中有多大差异？光遗传精控 DA 时序是否可以精确绘制这个窗口？
- Q-stc-molecular-tag：突触标签的分子身份——CaMKII 特定构象？PKM-ζ？F-actin 聚合？目前缺乏直接分子证据。

## 修订历史

- 2026-06-07 · 创建 · 基于《多巴胺的时间机器》一文 · 填补 [[hebbian-learning]] 页面的悬空引用 [[three-factor-learning-rule]] · 初始置信度：高

## 来源文章

- [[2026-06-07-dopamine-reward-prediction-error]]

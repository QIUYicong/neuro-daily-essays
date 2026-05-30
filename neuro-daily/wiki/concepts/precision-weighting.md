---
title: 精度加权
slug: precision-weighting
domain: concepts
type: mechanism
status: emerging
confidence: medium
created: 2026-06-15
updated: 2026-06-15
revision_count: 1
dimensions: [molecular, cellular, microcircuit, brain-region, cognition]
related: [predictive-coding, gain-control, acetylcholine-cortex, norepinephrine-locus-coeruleus, vip-interneurons, dopamine-reward-prediction-error, working-memory]
prerequisites: [predictive-coding, gain-control]
opens_questions: [Q-pc-01, Q-prec-01]
source_articles: [2026-06-15-predictive-coding]
key_sources: ["PMID:23663408", "PMID:27917138", "PMID:38259953", "PMID:30359606"]
---

# 精度加权 (Precision Weighting)

> **一句话定义**：在预测编码框架中，每个预测误差信号都携带一个精度权重（可信度的倒数方差），高精度误差对内部模型更新的影响更大；注意力被形式化为选择性提升任务相关误差信号精度的过程，神经调质（ACh、NE）是实现这一精度动态调制的分子机器。

## 当前理解

我们现在认为，大脑不只是最小化预测误差，而是**最小化精度加权的预测误差**。两个预测误差信号可能数值相同，但如果精度不同，它们对大脑内部模型的影响截然不同。

精度加权在计算上正式化注意力：注意一个刺激 = 提升该感觉通道预测误差信号的精度 → 该通道的误差对信念更新产生更大影响 → 感知更清晰、更精确。

在神经回路层面，精度加权等效于**增益控制**：选择性地放大特定突触连接的响应。这将抽象的贝叶斯计算与具体的神经元动力学联系起来。

## 关键机制

### 数学定义

在预测编码框架中，预测误差 ε 对信念更新的贡献为：

**∆belief ∝ π × ε**

其中 π（精度）= 1/σ²（方差的倒数）。精度越高（误差越可信），对信念更新的推力越大。

### 神经回路实现的候选（Shipp 2016, 2023）

**VIP 中间神经元通路（去抑制）**：
- VIP（血管活性肠肽）神经元 → 抑制 SST（生长抑素）神经元 → 解除对锥体细胞的抑制 → 锥体细胞增益↑ → 精度↑
- 这一去抑制回路已在多个皮层区域发现，是注意效应的一个候选实现（见 [[vip-interneurons]]）

**NMDA 受体介导的增益调制**：
- NMDA 受体开放状态提高突触传递效率 → 增加对特定输入的响应增益
- 可能是精度加权的另一候选分子底物

### 神经调质作为精度调节器

| 调质 | 精度调节效果 | 机制 | 时间尺度 |
|-----|------------|------|---------|
| **ACh** | 放大任务相关感觉通道精度（局部） | M1 受体→ K⁺漏电流↓ → 细胞增益↑ | 快（相位性）+ 慢（紧张性）|
| **NE** | 设定全局精度基线（倒 U 型） | α2A 受体→ HCN↓ → WM 稳定性↑（适中 NE）；高 NE → 噪声↑ | 慢（紧张性主导）|
| **DA** | 奖励相关精度信号（奖励域） | D1/D2 分化调制 → 纹状体选择压力 | 相位性（RPE 爆发）|

### 精度失调作为疾病模型

**精神分裂症**（Diederen & Fletcher 2021, PMID:32338128）：  
假设：先验精度过高（先验太强，难以被误差更新）→ 幻觉和妄想 = 未被感觉证据更新的强先验  
或：误差精度错误放大（aberrant salience）→ 无意义刺激被赋予"高精度误差" → 感知到不存在的意义

**孤独症谱系障碍**（理论，尚未收录于本知识库文章）：  
假设：感觉域精度过高（感觉先验弱，误差精度过高）→ 过度响应意外刺激 → 感觉过敏 → 需要可预测的环境

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 注意 ↔ 精度加权（计算等价性） | 理论分析 + 贝叶斯模型与注意数据拟合 | PMID:23663408 | 中（理论层面高，直接神经元标记证据不足）|
| ACh M1 受体实现 V1 注意性增益 | 猕猴 V1 + M1 阻断 + 注意任务（Herrero et al. 2008, PMID:18651663） | PMID:27917138 | 高（体内药理+电生理）|
| VIP-SST-锥体细胞去抑制回路实现局部增益 | 小鼠皮层光遗传 + 电生理（Pfeffer et al. 2013, Pi et al. 2013） | PMID:27917138; PMID:38259953 | 高（直接光遗传操控）|

## 连接

- [[predictive-coding]] — 精度加权是预测编码框架中注意的核心计算定义
- [[gain-control]] — 精度加权在回路层面的等效表述
- [[acetylcholine-cortex]] — ACh 是皮层感觉处理中最直接的精度调节器
- [[norepinephrine-locus-coeruleus]] — NE 设定全局精度/唤醒基线
- [[vip-interneurons]] — VIP→SST 去抑制是精度加权的皮层回路实现候选
- [[dopamine-reward-prediction-error]] — DA 在奖励域实现精度加权的类似功能

## 未解问题

- Q-pc-01：精度单元是否可以被在体内直接鉴定和操控（独立于增益控制）？
- Q-prec-01：不同神经调质（ACh/NE/DA）对精度调节的分工是否有清晰的空间-时间结构？它们的精度调节是否真的是在最小化预测误差，还是只是一般性的信噪比调节？

## 修订历史

- 2026-06-15 · 创建 · 基于《当大脑主动预测而非被动接收》一文 · 初始置信度：中（计算理论清晰，但神经回路级别的直接验证有限）

## 来源文章

- [[2026-06-15-predictive-coding]]

---
title: 预测编码
slug: predictive-coding
domain: theories
type: theory
status: mainstream
confidence: medium
created: 2026-06-15
updated: 2026-06-23
revision_count: 5
dimensions: [molecular, synaptic, microcircuit, brain-region, whole-brain-network, behavior, cognition]
related: [precision-weighting, v1-primary-visual-cortex, orientation-selectivity, dopamine-reward-prediction-error, gain-control, working-memory, theta-oscillations, active-inference, default-mode-network, global-workspace-theory, world-model, language-network, ventral-language-stream, cerebellum, forward-model]
prerequisites: [action-potential, synaptic-transmission, ltp, nmda-receptor, dopamine-reward-prediction-error]
opens_questions: [Q-pc-01, Q-pc-02, Q-pc-03, Q-pc-04, Q-pc-05]
source_articles: [2026-06-15-predictive-coding, 2026-06-16-default-mode-network, 2026-05-31-week4-synthesis]
key_sources: ["PMID:10195184", "PMID:23177956", "PMID:22681686", "PMID:30359606", "PMID:23663408", "PMID:27917138", "PMID:38259953", "PMID:20068583"]
---

# 预测编码 (Predictive Coding / Predictive Processing)

> **一句话定义**：皮层层级持续生成对感觉输入的自上而下预测，只将"实际输入 − 预测"的差值（预测误差）沿前馈方向向上传递；感知是推断世界状态的过程，而非被动复制感觉信号的过程。

## 当前理解

我们现在认为，视觉皮层的反馈连接（数量约是前馈连接 10 倍）不是修饰性的，而是计算的核心组成：它们携带高级区域对低级区域的**预测**，而前馈连接携带**预测误差**（实际输入与预测之差）。这与经典前馈感知模型正好相反。

Rao & Ballard（1999, PMID:10195184）的奠基性计算模型显示，在这样的层级网络中：
- 每级区域维护对输入的"当前最优估计"（表征单元，representation units）
- 预测误差（误差单元，error units）被向上传递，驱动更高层级更新其估计
- 仅传递误差（而非原始信号）是在统计结构化的自然图像上的高效编码策略

**主动推断（Active Inference）**：Clark（2013, PMID:23663408）和 Friston（2010, PMID:20068583）进一步提出，行动也是预测误差最小化的一种方式——运动不是"执行命令"，而是"实现本体感觉预测"。感知和行动共享一个计算原理：最小化预测误差（或其数学近似：自由能）。

**精度加权（Precision Weighting）**：预测误差信号不是均等重要的，其影响信念更新的程度取决于精度（可信度/1/方差）权重。注意力在计算上被定义为选择性地提升任务相关误差信号的精度，神经调质（ACh、NE）是在神经回路层面实现这一精度调节的分子机器。

## 关键机制

### 层级推断结构

在皮层层级中（以视觉为例：LGN → V1 → V2 → V4 → IT）：

```
高级区域 ←─误差信号（前馈）─── 低级区域
         ───预测信号（反馈）──→
```

每级区域做的是：
1. 接受来自高级区域的预测（反馈）
2. 与实际接收的输入（来自低级区域）比较
3. 计算预测误差，向上传递
4. 更新本层的当前估计

### 皮层层级的解剖学实现（Bastos et al. 2012, PMID:23177956）

| 皮层层 | 功能角色 | 投射方向 | 振荡频段 |
|--------|---------|---------|---------|
| L2/3（浅层） | 误差单元 | 前馈（到上级 L4） | **γ（30-80 Hz）** |
| L4 | 接受前馈输入 + 接受上级反馈预测 | — | — |
| L5/6（深层） | 表征/预测单元 | 反馈（到下级 L1/6） | **α/β（8-20 Hz）** |

振荡频段的功能分工：
- **γ 振荡**：前馈误差信号的载波；灵长类视觉皮层前馈方向以 γ 为主
- **α/β 振荡**：反馈预测信号的载波；灵长类视觉皮层反馈方向以 α/β 为主

### 精度加权与注意

每个误差信号 ε 被精度因子 π 加权：**有效误差 = π × ε**

精度 π 越高，该误差对更新的影响越大。注意力 = 提升特定感觉通道的 π，等效于选择性放大该通道对内部模型的更新能力。

**分子机制候选**（Shipp 2016, PMID:27917138; 2023, PMID:38259953）：
- VIP 中间神经元通过去抑制回路增加目标神经元的增益（精度↑）
- NMDA 受体的激活程度调节突触传递增益
- ACh（M1 受体）直接放大 V1 中注意相关刺激的响应增益（见 Herrero et al. 2008）

### 主动推断（Active Inference）

运动控制在主动推断框架中被理解为：
1. 运动皮层生成本体感觉的预测（"手应在位置 X"）
2. 脊髓反射弧执行使实际本体感觉匹配预测的肌肉命令
3. 感知与行动共享"最小化预测误差"的目标

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 预测编码框架复现 V1 非经典感受野效应（末端停止、环绕抑制） | 层级网络 + 自然图像训练；计算预测与已知神经数据对比 | PMID:10195184 | 高（计算模型）|
| 皮层前馈方向 γ 主导，反馈方向 α/β 主导 | 灵长类多脑区 MEG/LFP 记录；层级连接解剖与振荡记录对比 | PMID:23177956 | 高（多项独立研究）|
| 小鼠 V1 L2/3 在感觉运动失配时强烈激活（预测误差响应） | 清醒小鼠 + VR + 双光子钙成像；操控运动-视觉耦合状态 | PMID:22681686 | 高（体内行为实验）|
| 注意可被理解为精度加权（ACh 实现 V1 精度调制） | 猕猴 V1 + M1 受体阻断 + 注意任务（Herrero et al. 2008） | PMID:27917138；PMID:30359606 综述 | 高（体内药理+电生理）|
| 某些感觉皮层间交互不符合简单振荡-方向映射预测 | 灵长类视觉联合皮层新数据（仅读摘要） | PMID:41120233 | 待评估（限于摘要）|

### 小脑：专用预测误差学习系统

小脑是大脑中实现预测编码最具体、最古老的子系统（Wolpert et al. 1998, PMID:21227230）：
- **前向模型**：利用传出拷贝（efference copy）预测运动感觉后果 → 与实际感觉（攀爬纤维）对比 → 预测误差
- **可塑性更新**：误差驱动 PF-LTD/LTP，更新内部模型（浦肯野细胞突触权重）
- 预测编码原理在小脑的实现早于皮层预测编码理论的提出，是同一计算原则在进化上的较古老版本

小脑的预测编码是**局部的、运动-感觉专用的**；皮层的预测编码是**层级的、多模态的**。两者可能共享"预测 → 误差 → 更新"这一核心循环。

## 连接

- [[cerebellum]] — 专用预测误差学习系统（前向模型 + 攀爬纤维误差信号）
- [[forward-model]] — 小脑前向模型是预测编码的一个具身子系统
- [[precision-weighting]] — 预测编码框架中注意力和神经调质的计算角色
- [[v1-primary-visual-cortex]] — 预测编码在视觉系统中最被研究的具体实例
- [[orientation-selectivity]] — 方向选择性作为高效预测编码自然涌现的结果
- [[dopamine-reward-prediction-error]] — 多巴胺 RPE = 奖励域中预测误差信号的神经实现（同一计算原理）
- [[gain-control]] — 增益控制是精度加权的低层级实现机制
- [[working-memory]] — 工作记忆可被理解为主动维护预测模板（先验）
- [[theta-oscillations]] — θ 振荡可能是序列预测（时间上的预测编码）的载波
- [[ltp]] — LTP/LTD 是预测误差驱动的突触层面权重更新
- [[global-workspace-theory]] — GWT 与预测编码互补：足够大的预测误差（无法被局部层级消解）可能是触发全局工作空间点燃的候选机制；意识 = 大脑在无法预测时召唤全局计算资源
- [[language-network]] — 语言理解是预测编码在词汇层面的实例化：额叶（Broca区）在词出现前200ms生成语义-感觉运动预测，颞叶返回预测误差，构成词级预测-更新循环（Grisoni 2024, PMC10957213）
- [[ventral-language-stream]] — 腹侧语言流的具身语义预测（工具词→运动皮层预激活；动物词→视觉皮层预激活）是预测编码具身性的直接神经证据

## 未解问题

- Q-pc-01：误差单元和表征单元是否能被可靠地在体内直接区分？（高优先级）
- Q-pc-02：预测编码/自由能原理是否足够可证伪？其核心实验预测是什么？（高优先级）
- Q-pc-03：环绕抑制和末端停止究竟是预测误差还是侧抑制？如何在体内区分？（中优先级）
- Q-pc-04：V1 感觉运动失配响应的具体来源（运动皮层反馈 vs 高级视觉 vs 神经调质）？（高优先级）
- Q-pc-05：层级振荡映射（γ/α-β）的普适性如何？Westerberg 2026 的挑战范围有多大？（高优先级）

## 修订历史

- 2026-06-15 · 创建 · 基于《当大脑主动预测而非被动接收》一文 · 初始置信度：中（框架是 mainstream，但具体机制仍有争议）
- 2026-06-16 · 修订 · 基于《默认模式网络》一文 · 添加 DMN 作为预测编码层级高层先验生成器的关联；related 新增 default-mode-network
- 2026-05-30 · 修订 · 基于《当意识在大脑中"点燃"》一文 · 添加 GWT 与预测编码的互补关系：足够大的预测误差触发工作空间点燃；related 新增 global-workspace-theory
- 2026-05-31 · 修订 · 基于《第四周综合：当大脑成为自己的宇宙》(#28) · 将预测编码定位为「世界模型误差加权更新层」；新增 world-model 到 related；明确预测编码给出了世界模型的贝叶斯更新方程：Δmodel ∝ precision_weighted_prediction_error
- 2026-06-20 · 修订 · 基于《语言的解剖》一文 · 新增语言域的预测编码实例：词出现前200ms的语义-感觉运动预测（Grisoni 2024），腹侧流具身语义预测（工具词→运动皮层，动物词→视觉皮层）；related 新增 language-network, ventral-language-stream
- 2026-06-23 · 修订 · 基于《小脑的秘密》一文 · 新增"小脑专用预测误差学习系统"段落（前向模型→误差→LTD更新）；related 新增 cerebellum, forward-model

## 来源文章

- [[2026-06-15-predictive-coding]]
- [[2026-06-20-language-dual-stream]]

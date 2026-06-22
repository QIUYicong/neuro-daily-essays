---
title: 攀爬纤维
slug: climbing-fiber
domain: neurons
type: structure
status: established
confidence: high
created: 2026-09-03
updated: 2026-09-03
revision_count: 1
dimensions: [cellular, synaptic, microcircuit, brain-region]
related: [purkinje-cell, cerebellar-ltd, inferior-olive, cerebellum, granule-cell, parallel-fiber]
prerequisites: [synaptic-transmission, action-potential]
opens_questions: [Q-pc-01, Q-cb-02]
source_articles: [2026-09-03-purkinje-cell-cerebellar-motor-learning]
key_sources: ["PMID:40523942", "PMID:40848722", "PMID:31572132", "PMID:24814344"]
---

# 攀爬纤维 (Climbing Fiber)

> **一句话定义**：从下橄榄核发出的强突触纤维，每根与单一浦肯野细胞形成约 400–500 个突触，触发独特的"复杂放电"（complex spike），携带预测违反信号（包括运动误差和奖励预测误差），驱动 PF-PC LTD 等小脑可塑性。

## 当前理解

攀爬纤维（climbing fiber，CF）是小脑皮层中来自下橄榄核（inferior olivary nucleus）的轴突投射。其命名来自它沿浦肯野细胞（PC）树突"攀爬"的解剖特征——每根 CF 沿 PC 的主树突干和粗分支缠绕，形成约 400–500 个突触释放位点，是中枢神经系统中最强的单一突触联系之一。

**功能定性演化**：
- **经典（Marr-Albus-Ito）**：CF 携带运动误差信号——当运动产生非预期的感觉后果时，下橄榄核激活，CF 触发 PC 的复杂放电，驱动 PF-PC LTD
- **2019 年更新（Zang & De Schutter）**：CF 信号是梯度（analog）而非二元——复杂放电持续时间和内部去极化波峰数量变化，携带误差量级信息
- **2025 年更新（Jin & Hull）**：外侧小脑的 CF 还携带奖励预测误差信号，使小脑参与广义预测学习

**复杂放电（Complex Spike）**：CF 触发的 PC 特征性响应，包含1–4个去极化波峰，持续时间3–30 ms（vs 简单放电 < 1 ms）。复杂放电触发大量 Ca²⁺ 内流（通过 P/Q 型 VGCC），与 mGluR1 信号共同驱动 PF-PC LTD。

## 关键机制

### CF → PC 联系的解剖
- 起源：下橄榄核（对侧）
- 一对一原则：一根 CF 支配一个 PC（成年哺乳动物；发育期为多对一，后精炼为一对一）
- 沿 PC 主树突干攀爬，形成强突触联系
- 每个 PC 接受约 400–500 个 CF 突触（vs PF 约 200,000 个但每个仅 1–2 个突触）

### CF 信号的梯度本质（Zang & De Schutter 2019）
- 复杂放电持续时间受多因素调制：CF 爆发频率、PC 背景发放状态、并行突触输入
- 持续时间越长 → 树突 Ca²⁺ 峰值越高 → LTD 诱导越强
- 不同树突分支可接受不同幅度 Ca²⁺ 信号 → 分支特异性 LTD

### CF 奖励信号（Jin & Hull 2025）
- 外侧小脑（crus I/II）CF 在 Pavlovian 任务中表现奖励预测误差特征
- 响应从"奖励本身"转移至"预测奖励的 CS"
- 刺激阻断效应证实强化学习属性
- 下橄榄核接受来自边缘系统（多巴胺？奖励相关输入？）的调制

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| CF 触发 PC 复杂放电，驱动 LTD | 脑片电生理 + 下橄榄核激活 | 伊藤正男经典系列（1970s） | 高 |
| 复杂放电持续时间与 LTD 量正相关 | 电控 CF 爆发 vs 可塑性量测定 | PMID:24814344 | 中-高 |
| CF 信号是梯度非二元 | 综述，多模态证据 | PMID:31572132 | 中-高 |
| CF 携带奖励预测误差信号 | 钙成像 + 光遗传学 in vivo | PMID:40848722 | 中（单实验室，外侧小脑） |

## 连接

- [[purkinje-cell]] — CF 的突触靶点；驱动 LTD
- [[inferior-olive]] — CF 的起源核团（待建页面）
- [[cerebellar-ltd]] — CF 驱动的可塑性机制详情
- [[cerebellum]] — CF 在小脑回路中的位置
- [[parallel-fiber]] — CF 与 PF 的同时激活诱导 LTD

## 未解问题

- Q-cb-02：CF 究竟编码什么类型的"误差"——感觉预测误差、运动结果误差、时间违规还是奖励预测误差？不同小脑区域是否不同？
- Q-pc-01：外侧小脑奖励 CF 信号与蚓部运动误差 CF 信号如何在同一 PC 上整合？

## 修订历史

- 2026-09-03 · 创建 · 基于《小脑里的误差教师》一文 · 初始置信度：高（解剖与经典功能 established）；奖励 CF 信号：emerging

## 来源文章

- [[2026-09-03-purkinje-cell-cerebellar-motor-learning]]

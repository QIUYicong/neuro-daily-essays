---
title: 控制期望价值（Expected Value of Control, EVC）
slug: expected-value-of-control
domain: concepts
type: theory
status: mainstream
confidence: medium
created: 2026-08-23
updated: 2026-08-23
revision_count: 1
dimensions: [cognition, brain-region, behavior]
related: [anterior-cingulate-cortex, conflict-monitoring, error-related-negativity, frontal-midline-theta, prefrontal-cortex, nucleus-accumbens, response-inhibition]
prerequisites: [anterior-cingulate-cortex, conflict-monitoring]
opens_questions: [Q-dacc-02, Q-dacc-03]
source_articles: [2026-08-23-dacc-error-monitoring-conflict-effort]
key_sources: ["PMID:23889930"]
---

# 控制期望价值（Expected Value of Control, EVC）

> **一句话定义**：Shenhav、Botvinick 和 Cohen（2013）提出的规范性理论，主张 dACC 通过计算"追加认知控制的期望价值"（收益 × 概率 − 努力成本）来统一决定是否、向何处、投入多少控制——将错误监测、冲突监控和努力决策整合进同一框架。

## 当前理解

EVC 理论是迄今最全面的 dACC 功能统一框架（Shenhav, Botvinick & Cohen 2013，PMID:23889930，PMCID:PMC3767969）。它的核心洞察是：dACC 激活的多样性（错误后、冲突时、奖励时、努力决策时……）反映的是**同一个底层计算**：

> 在当前情境下，追加认知控制能带来的期望价值是多少？

形式化：
```
EVC(c) = Σₒ [P(o|c,S) × V(o)] − Cost(c)
```

其中：
- c = 控制信号（类型和强度）
- o = 可能的结果（outcomes）
- S = 当前任务状态
- P(o|c,S) = 控制 c 在状态 S 下产生结果 o 的概率
- V(o) = 结果 o 的价值
- Cost(c) = 施加控制 c 的努力代价

当 EVC > 0 时，dACC 激活 dlPFC 等控制区域；当 EVC ≤ 0 时，允许自动化/习惯性处理。

## 关键机制

### dACC 的双重功能

EVC 理论区分了 dACC 的两个功能：

1. **监控（Monitoring）**：追踪冲突、任务难度、结果信息、激励状态——这是 EVC 计算的输入
2. **规范（Specification）**：基于 EVC 计算，决定控制的**类型**（哪类控制）和**强度**（多少控制）——这是 EVC 计算的输出

与之对比，dlPFC 的功能是**执行（Implementation）**：实施 dACC 指定的具体控制策略（选择性注意、规则维护、任务切换等）。

### 三类信号的统一

| 信号类型 | 在 EVC 中的位置 | 效果 |
|---------|----------------|------|
| 错误（ERN） | 负向 EVC 更新（预测收益未实现） | 追加控制以纠正 |
| 冲突（N2） | 高不确定性 → 控制追加收益增大 | 追加控制以减少冲突 |
| 努力代价 | 直接进入 Cost(c) | 高代价时降低控制倾向 |
| 高奖励情境 | 增大 V(o) → EVC 提升 | 主动追加控制 |

### 与旧假说的关系

| 理论 | 预测 | EVC 的处理 |
|------|------|-----------|
| 冲突监控假说 | 冲突↑ → dACC↑ | 被包含：冲突是 EVC 输入之一 |
| ERN-RL 框架 | 错误后 ERN → 控制追加 | 被包含：错误 = 负EVC更新 |
| 努力决策理论 | 代价高时 dACC 抑制努力 | 被包含：代价 = Cost(c) |
| EVC 额外预测 | **奖励↑ → dACC↑** | 纯冲突监控无此预测；已得实验验证 |

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| dACC 随任务难度和任务奖励双向上调 | fMRI（Kouneiher 2009 等多项研究） | Shenhav 2013 综合引用 | 中-高 |
| 切扣带回术患者冲突适应效应消失 | 神经外科病例研究 | Shenhav 2013 引用 | 高（因果证据）|
| dACC 追踪价值选项（探索 vs 利用） | 恒河猴单细胞记录 | Shenhav 2013 引用 | 中-高 |
| FMθ 功率预测行为调整（EVC实施机制） | EEG | Cavanagh & Frank 2014, PMID:24835663 | 高 |

## 未解问题

- Q-dacc-02: EVC 中"努力成本"的具体神经实现（是热力学代价？机会成本？主观厌恶感？）
- Q-dacc-03: dACC 内部是否存在实现 EVC 更新的突触学习规则？

## 连接

- [[anterior-cingulate-cortex]] — dACC/MCC 是 EVC 计算的神经基底
- [[conflict-monitoring]] — 冲突监控假说被 EVC 包含和扩展
- [[error-related-negativity]] — ERN 是负向 EVC 更新的电气表达
- [[frontal-midline-theta]] — FMθ 是 EVC 驱动控制招募的振荡机制
- [[prefrontal-cortex]] — dlPFC 执行 dACC（EVC 计算）指定的控制策略
- [[nucleus-accumbens]] — dACC→NAc 通路传递"努力是否值得"的自顶向下信号

## 修订历史

- 2026-08-23 · 创建 · 基于《背侧前扣带皮层的三重计算》文章（#121）· 初始置信度：中（规范理论）

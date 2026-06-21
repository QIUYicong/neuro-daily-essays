---
title: 冲突监控假说（Conflict Monitoring Hypothesis）
slug: conflict-monitoring
domain: concepts
type: theory
status: mainstream
confidence: high
created: 2026-08-23
updated: 2026-08-23
revision_count: 1
dimensions: [cognition, brain-region]
related: [anterior-cingulate-cortex, frontal-midline-theta, error-related-negativity, expected-value-of-control, response-inhibition, hyperdirect-pathway, prefrontal-cortex]
prerequisites: [anterior-cingulate-cortex, prefrontal-cortex]
opens_questions: [Q-dacc-01]
source_articles: [2026-08-23-dacc-error-monitoring-conflict-effort]
key_sources: ["PMID:11488380", "PMID:11707086", "PMID:15486290"]
---

# 冲突监控假说（Conflict Monitoring Hypothesis）

> **一句话定义**：Botvinick 等（2001）提出，dACC 通过计算互斥反应的并发激活之积（Hopfield 能量）监测信息处理中的冲突程度，并在高冲突时向 dlPFC 发出"需要追加认知控制"的信号。

## 当前理解

冲突监控假说（Botvinick, Braver, Barch, Carter & Cohen 2001，PMID:11488380）是过去二十五年认知神经科学中最有影响力的框架之一。它给出了一个统一的计算解释，说明为什么 dACC 在 Stroop、Simon、N-back、错误等如此多样的任务中都被激活：**它们的共同点是信息处理过程中存在竞争性冲突**。

核心主张：
1. dACC 持续监测处理系统内部的"冲突"（Conflict）
2. "冲突"= 多个互斥响应选项被同时激活
3. 高冲突 → dACC 信号 → dlPFC 追加认知控制 → 行为调整
4. 这个过程是自动的（不需要主动监督）

## 关键机制

### Hopfield 能量量化冲突

冲突在计算上被形式化为**Hopfield 能量**：

```
冲突 = Σᵢ≠ⱼ (aᵢ × aⱼ)
```

其中 aᵢ、aⱼ 是不同候选反应的激活水平。当多个反应同时高度激活时，两两乘积之和（冲突量）最大化。

以 Stroop 任务为例：
- 你看到"红"字，字体颜色是绿色
- 自动读字过程激活"说红"响应
- 任务要求激活"说绿"响应
- 两个响应并发激活 → Hopfield 能量高 → 冲突量大 → dACC 激活

### 冲突-控制循环

```
任务情境
  → 多个竞争响应并发激活
  → dACC 计算 Hopfield 冲突能量
  → 高冲突: dACC → dlPFC 信号（"需要更多控制"）
  → dlPFC 追加选择性注意、规则维护、任务切换等控制机制
  → 下一试次冲突减少（Gratton 效应）
```

### Gratton 效应（行为核心预测）

冲突监控假说的核心行为预测：
- 高冲突试次之后，下一试次**反应时变慢、准确率提高**
- 因为上一次的高冲突触发了额外控制，这个控制在下一次仍然起效
- 这被称为 Gratton 效应（或冲突适应效应），已被大量实验验证

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| dACC 对"响应冲突"特异激活（非刺激冲突） | 事件相关 fMRI，Stroop + Simon | van Veen 2001, PMID:11707086 | 高 |
| 冲突监控预测 Gratton 效应 | 计算模型 + 行为实验 | Botvinick 2001, PMID:11488380 | 高 |
| 内侧额叶皮层激活在错误/冲突/不确定性中重叠 | 人类 fMRI 元分析 | Ridderinkhof 2004, PMID:15486290 | 高 |
| FMθ 功率预测 Gratton 效应 | EEG 时频分析 | Cavanagh & Frank 2014, PMID:24835663 | 高 |

## 与 EVC 理论的关系

冲突监控假说被 Shenhav 等（2013）的 **EVC（期望控制价值）理论**部分包含和扩展：
- 冲突监控假说只预测"困难/冲突程度"对 dACC 激活的正向影响
- EVC 理论额外预测"奖励/收益"也应正向影响 dACC 激活（实验证实）
- 冲突可被形式化为 EVC 模型中"处理不确定性"组分

## 连接

- [[anterior-cingulate-cortex]] — dACC 是冲突监控假说的神经基底
- [[frontal-midline-theta]] — FMθ 是冲突信号的振荡实现；N2 成分是其时域表达
- [[error-related-negativity]] — ERN 是特殊冲突（已犯错）的 EEG 标志；与 N2 共享 θ 基础
- [[expected-value-of-control]] — EVC 框架扩展和包含了冲突监控假说
- [[response-inhibition]] — 冲突触发 dACC → STN 激活，实施全局反应抑制
- [[hyperdirect-pathway]] — dACC θ → STN 超直接通路是冲突-抑制的神经回路
- [[prefrontal-cortex]] — dlPFC 是接收 dACC 冲突信号并实施控制的执行者

## 修订历史

- 2026-08-23 · 创建 · 基于《背侧前扣带皮层的三重计算》文章（#121）· 初始置信度：高

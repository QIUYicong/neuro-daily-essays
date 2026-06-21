---
title: 任务切换代价
slug: task-switching-cost
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-24
updated: 2026-08-24
revision_count: 1
dimensions: [cognition, behavior, methods]
related: [stability-flexibility-tradeoff, dlpfc-cognitive-flexibility, prefrontal-cortex, response-inhibition, dacc-conflict-monitoring]
prerequisites: [prefrontal-cortex, working-memory]
opens_questions: [Q-dlpfc-02]
source_articles: [2026-08-24-dlpfc-cognitive-flexibility-rule-switching]
key_sources: ["PMID:38010299", "PMC10902878", "PMID:37683103"]
---

# 任务切换代价 (Task-Switching Cost)

> **一句话定义**：在两个任务之间交替时，切换任务相比重复同一任务产生的反应时延长和错误率升高，反映了新旧规则切换的认知代价，包括"混合代价"（维持多任务集的负担）和"残余切换代价"（旧规则的正向干扰）。

## 当前理解

任务切换范式（task-switching paradigm，Rogers & Monsell 1995 奠基）揭示了认知弹性的实际代价：

**两个代价成分**：
1. **混合代价（mixing cost）**：即使重复同一任务的试次，在"混合块"（随时可能需要切换）中比"纯块"（只做一个任务）更慢——反映同时维持两套任务规则的认知负担。
2. **残余切换代价（residual switch cost）**：即便给予充足的准备时间（1-2 秒），切换试次仍比重复试次更慢——反映上一任务规则的正向干扰（proactive interference）未能完全消除，需要主动抑制。

**神经基底**（Sali et al. 2024，PMID:38010299）：
- 外侧额叶和顶叶（额顶网络）的 BOLD 信号与"切换预测误差"（unsigned switch prediction error）正相关
- 切换概率统计上更高时，行为切换代价降低，额顶激活相应调整
- 提示额顶网络在实时学习切换策略（强化学习机制），而非固定执行切换

## 关键机制

### 正向干扰的来源
旧规则的任务集（task set）在切换后不会立即消失，而是以降低的激活水平持续存在，与新任务规则竞争。残余切换代价反映了清除或抑制这种竞争所需的时间和认知资源。

### 规则切换中的振荡动态
Buschman 等 2012（PMID:23177967）：规则切换时，beta 频段同步从旧规则集群转向新规则集群，alpha 同步抑制旧集群——这是切换代价的神经层面底物。

## 关键证据
| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 额顶网络活动与切换预测误差正相关 | fMRI + 强化学习模型 | PMID:38010299 / PMC10902878 | 中 |
| OCD 患者切换代价增大 + 额顶超激活 | fMRI 任务切换范式 | PMID:37683103 | 中 |
| PFC 规则切换时 beta/alpha 振荡模式改变 | 猕猴 LFP 记录 | PMID:23177967 / PMC3907768 | 高 |

## 连接
- [[stability-flexibility-tradeoff]] — 任务切换代价是稳定性—弹性权衡的行为体现
- [[dlpfc-cognitive-flexibility]] — dlPFC 执行规则切换
- [[response-inhibition]] — 切换需要抑制旧反应
- [[dacc-conflict-monitoring]] — 切换时 dACC 监测新旧规则冲突

## 修订历史
- 2026-08-24 · 创建 · 基于《背外侧前额叶的认知弹性》文章 · 初始置信度：高

## 来源文章
- [[2026-08-24-dlpfc-cognitive-flexibility-rule-switching]]

---
title: 停止信号任务
slug: stop-signal-task
domain: concepts
type: method
status: established
confidence: high
created: 2026-08-19
updated: 2026-08-19
revision_count: 1
dimensions: [behavior, cognition, methods]
related: [response-inhibition, hyperdirect-pathway, basal-ganglia]
prerequisites: []
opens_questions: []
source_articles: [2026-08-19-response-inhibition-hyperdirect-pathway]
key_sources: ["PMID:18822313", "PMID:16510720", "PMID:32155442"]
---

# 停止信号任务 (Stop-Signal Task, SST)

> **一句话定义**：量化反应抑制能力的标准实验范式；受试者在大多数试次中对Go信号快速响应，但在少数试次中需在出现停止信号后叫停已启动的响应；核心指标SSRT由中位RT(Go)与平均SSD之差估算，正常值约200-250 ms。

## 当前理解

停止信号任务（SST）是研究反应抑制最广泛使用的行为范式，其理论基础是**独立赛马模型**（Independent Horse Race Model，Verbruggen & Logan 2009，PMID:18822313）：Go 过程和 Stop 过程独立并行，谁先完成则决定最终行为（执行 vs 抑制）。

**任务基本结构**：
- 约 75% 试次：Go 试次，受试者对箭头方向按键（快速响应）
- 约 25% 试次：Stop 试次，Go 信号后延迟 SSD 出现停止信号（通常是声音），受试者抑制按键
- 通过上下法（staircase）动态调整 SSD，使停止成功率约为 50%

**核心量化指标**：

SSRT = 中位 RT(Go) - 平均 SSD

- SSRT 越短 → 刹车系统越快
- 正常成人：约 200-250 ms
- ADHD 患者：SSRT 显著延长（约延长 30-50 ms）

**赛马模型的关键预测**：
- Go 过程必须通常比 Stop 过程快（否则大多数停止试次都会成功，任务过于容易）
- 在停止成功率 ~50% 时，Go 和 Stop 的"终点线"在统计意义上相当
- Stop 过程的潜伏期（即 SSRT 的来源）对受试者不可见，只能通过整体分布推算

## 关键机制

### 赛马模型的计算逻辑

独立赛马模型假设 Go 过程的反应时呈某一分布（可测量），Stop 过程（SSRT）对应固定潜伏期（不可直接测量）。通过计算在停止成功率约为 50% 时，SSRT 对应 Go RT 分布的哪个百分位点（约 50th 分位），可以反推 SSRT。

当代替代方法（如贝叶斯参数估计 BEESTS 模型）提供更精细的 SSRT 估算，但经典积分法（中位 Go RT - 平均 SSD）在多数研究中已经足够。

### 任务变体

- **Stop-Change 任务**：停止信号后需改变响应（而非仅抑制），可分离抑制和重定向
- **选择性停止任务**：只停止特定手（而非全身），用于研究选择性 vs 全局抑制
- **延迟停止任务**：变化 Go 信号与停止信号之间的时间关系

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| 独立赛马模型是SST数据的主要解释框架 | 理论+大量行为研究收敛 | PMID:18822313 [摘要] | 高 |
| SSRT与rIFG+STN激活程度相关 | fMRI + SST | PMID:16510720 [全文] | 高 |
| IFG-STN同步强度预测SSRT | 颅内记录 | PMID:32155442 [全文] | 高 |
| ADHD患者SSRT显著延长 | 多项SST研究 | 综合文献 | 高 |

## 连接

- [[response-inhibition]] — SST 是量化反应抑制的标准方法
- [[hyperdirect-pathway]] — SSRT 是衡量超直接通路功能效率的行为指标
- [[basal-ganglia]] — SST 中的神经激活集中在基底节（STN/纹状体）

## 未解问题

（无专属未解问题；参见 response-inhibition 页面的 Q-ri-01 至 Q-ri-03）

## 修订历史

- 2026-08-19 · 创建 · 基于《大脑的刹车系统》文章 #105 · 初始置信度：高（established，超过30年研究历史）

## 来源文章

- [[2026-08-19-response-inhibition-hyperdirect-pathway]]

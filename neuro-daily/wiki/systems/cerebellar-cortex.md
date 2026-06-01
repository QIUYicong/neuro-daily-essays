---
title: 小脑皮层
slug: cerebellar-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-06-23
updated: 2026-06-23
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, behavior]
related: [purkinje-cell, climbing-fiber, granule-cell, cerebellar-ltd, cerebellar-forward-model, deep-cerebellar-nuclei, motor-cortex, inferior-olive]
prerequisites: [action-potential, inhibitory-interneurons, synaptic-transmission]
opens_questions: [Q-cbm-01, Q-cbm-04]
source_articles: [2026-06-23-cerebellar-learning-purkinje-climbing-fiber]
key_sources: ["PMID:32352914", "PMID:30697149", "PMID:32710914", "PMCID:PMC12546079"]
---

# 小脑皮层 (Cerebellar Cortex)

> **一句话定义**：小脑皮层是高度规律化的三层神经结构，通过平行纤维（感觉-运动信息）和攀爬纤维（误差信号）在普肯野细胞上的汇聚，实现基于误差的运动学习和运动预测。

## 当前理解

小脑皮层是已知组织最规律的脑区之一，其微回路结构跨物种高度保守。它包含超过 80% 的全脑神经元（绝大多数是颗粒细胞），但体积仅占脑的约 10%。

**三层架构**：
- **颗粒层**（内层）：颗粒细胞（小、多），接受来自苔状纤维的感觉/运动信息，通过平行纤维上行至分子层
- **普肯野细胞层**（中层）：单层巨大神经元，小脑皮层的唯一输出
- **分子层**（外层）：平行纤维水平走行，与普肯野细胞树突交叉

**两套输入的功能分工**：
- **苔状纤维 → 颗粒细胞 → 平行纤维 → 普肯野细胞**：信息通道，携带感觉/运动上下文
- **攀爬纤维（下橄榄核）→ 普肯野细胞**：误差通道，每个普肯野细胞仅一根攀爬纤维，约 1 Hz 激活

**学习机制**：平行纤维与攀爬纤维的同时激活诱导平行纤维-普肯野细胞突触的长时程抑制（LTD），是小脑的核心有监督学习机制。

## 关键机制

### 颗粒层：信息展开（expansion recoding）
苔状纤维数量有限（约 2×10⁸根），但通过颗粒细胞（~5×10¹⁰个，人类）的随机混合采样（每个颗粒细胞约采样 4 根苔状纤维），创造了极高维度的稀疏表征，为后续 LTD 学习提供区分度。

### 平行纤维的解剖特殊性
平行纤维水平走行，与普肯野细胞树突垂直交叉（普肯野细胞树突展开在单一平面内）。这使平行纤维逐个"拨弦式"激活沿途每个普肯野细胞，实现时序化的感觉-运动上下文传递。

### 攀爬纤维的独特解剖
每个普肯野细胞只接受**一根**来自下橄榄核的攀爬纤维（但该攀爬纤维形成数百至千个突触），激活产生复杂棘波（complex spike），大量 Ca²⁺ 内流覆盖整个树突。

### 普肯野细胞的抑制输出
普肯野细胞通过 GABA 能轴突持续抑制深部小脑核（DCN），DCN 是小脑唯一输出门户。学习通过减少普肯野细胞放电（LTD 弱化 PF 突触）→ 脱抑制 DCN → 增强运动输出来实现。

## 关键证据
| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 皮层两阶段学习（快获取-弱保留） | 猕猴平滑追踪，同步记录普肯野细胞 + 绒球靶神经元 | PMID:32352914（Herzfeld 2020） | 高 |
| 普肯野细胞树突棘约 3.5 万（小鼠，非传统 10 万） | 电镜+AI 分割 | PMCID:PMC12546079（Masoli 2025） | 中高 |
| 前馈内部模型的双峰 SS 时序 | 大鼠追踪任务，SS 时序分析 | PMID:30697149（Popa 2019） | 中高 |

## 连接
- [[普肯野细胞]] — 唯一输出神经元
- [[攀爬纤维]] — 误差教师信号
- [[小脑 LTD]] — 核心学习机制
- [[小脑前馈内部模型]] — 系统功能
- [[深部小脑核]] — 最终输出门户
- [[运动皮层]] — 接受小脑输出的目标区域
- [[下橄榄核]] — 攀爬纤维起源

## 未解问题
- 见 state/unresolved_questions.md 中的 Q-cbm-01, Q-cbm-04

## 修订历史
- 2026-06-23 · 创建 · 基于《错误的教育：小脑如何学习》一文 · 初始置信度：高

## 来源文章
- [[2026-06-23-cerebellar-learning-purkinje-climbing-fiber]]

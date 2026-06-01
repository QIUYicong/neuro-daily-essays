---
title: 攀爬纤维
slug: climbing-fiber
domain: neurons
type: structure
status: established
confidence: high
created: 2026-06-23
updated: 2026-06-23
revision_count: 1
dimensions: [cellular, microcircuit, brain-region]
related: [purkinje-cell, cerebellar-cortex, cerebellar-ltd, inferior-olive, complex-spike, cerebellar-forward-model]
prerequisites: [action-potential, voltage-gated-calcium-channels, synaptic-transmission]
opens_questions: [Q-cbm-02, Q-cbm-03]
source_articles: [2026-06-23-cerebellar-learning-purkinje-climbing-fiber]
key_sources: ["PMID:31572132", "PMID:32352914", "DOI:10.7554/eLife.86340"]
---

# 攀爬纤维 (Climbing Fiber)

> **一句话定义**：来自下橄榄核（inferior olive）的输入纤维，沿普肯野细胞树突主干从下至上"攀援"形成数百至千个突触，每个普肯野细胞只接受一根攀爬纤维；激活时产生复杂棘波和树突大规模 Ca²⁺ 内流，作为小脑学习的"误差教师信号"触发平行纤维突触 LTD。

## 当前理解

攀爬纤维（climbing fiber，CF）是小脑学习系统中最关键的"教学通道"。其解剖特殊性令人印象深刻：每根攀爬纤维仅支配少数（1–3 个）普肯野细胞，而每个普肯野细胞只接受**一根**来自对侧下橄榄核的攀爬纤维。

与平行纤维的轻触式接触（单个突触，一过性激活）完全不同，攀爬纤维沿普肯野细胞树突全长"紧密缠绕"，在整个树突干上形成 300–1000 个突触。一次激活就能引发普肯野细胞产生**复杂棘波**（complex spike）：胞体的棘波簇发（2–4 个子棘波）和整个树突的大规模 Ca²⁺ 内流。

**约 1 Hz 激活频率**：CF 的基线放电极低，约每秒 1 次，这确保了学习信号的稀疏性——不会因频繁"误报"而干扰正常运动。

### 经典二值信号 vs 梯度化信号

**传统观点**：CF/CS 是二值"教师"——有 CS 则学，无 CS 则不学。

**修正观点（Zang & De Schutter 2019，PMCID: PMC6749063）**：CF 能提供梯度化信号。决定 LTD 幅度的 Ca²⁺ 内流强度，受以下因素调制：
- CS 内的子棘波数量（代表 CF 放电模式）
- 普肯野细胞当前膜电位状态
- 同期来自抑制性中间神经元或其他兴奋性突触的背景输入

这种梯度化能力使 CF 能够编码"误差有多大"，而不只是"有没有误差"。

### CF 响应的功能成分（Hoang et al. 2023）

Hoang et al.（eLife, DOI:10.7554/eLife.86340）使用双光子 Ca²⁺ 成像和张量分量分析，发现小脑 CF 响应可分解为 **4 个功能独立的成分**：
1. **时序控制**（motor timing）：同步性增加，精确校准动作时序
2. **误差学习**（error-based learning）：传统 LTD 教学信号
3. **奖励处理**（reward processing）：响应于奖励预测（下橄榄核接受奖励相关输入）
4. **行为抑制**（behavioral inhibition）：对应运动停止信号

这意味着 CF 系统不只是运动误差检测器，还参与奖励价值的整合。

## 关键机制

### 下橄榄核（IO）如何计算误差
IO 神经元接受：
- 来自脊髓/脑干的感觉反馈（实际运动后果）
- 来自运动皮层/深部小脑核的副本信号（预期运动后果）

IO 的输出（攀爬纤维）放电，代表实际-预期的差值（运动误差）。

**负反馈回路**：随着学习进行，运动误差减少 → IO 激活减少 → CF 放电减少 → LTD 诱导减少 → 学习率自动降低直至收敛（Herzfeld et al. 2020，PMCID: PMC7255800）。

## 关键证据
| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| CF 是误差教师信号（VOR 经典范式） | 翻转棱镜→视网膜滑动→CF 激活→VOR 增益改变 | PMID:32710914（Nagao 2021）| 高 |
| CF 提供梯度化信号 | 膜片钳+Ca²⁺ 成像 | PMCID:PMC6749063（Zang 2019）| 中高 |
| CF 活动有 4 个功能成分 | 双光子+TCA | eLife 2023 DOI:10.7554/eLife.86340 | 中 |

## 连接
- [[普肯野细胞]] — 唯一靶标
- [[小脑 LTD]] — 诱导的学习结果
- [[下橄榄核]] — 起源（待补充页面）
- [[小脑前馈内部模型]] — 系统功能背景

## 未解问题
- 见 Q-cbm-02, Q-cbm-03

## 修订历史
- 2026-06-23 · 创建 · 基于《错误的教育》文章 · 置信度：高

## 来源文章
- [[2026-06-23-cerebellar-learning-purkinje-climbing-fiber]]

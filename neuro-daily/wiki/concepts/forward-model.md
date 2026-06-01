---
title: 前向模型
slug: forward-model
domain: concepts
type: theory
status: mainstream
confidence: medium
created: 2026-06-23
updated: 2026-06-23
revision_count: 1
dimensions: [brain-region, cognition, behavior]
related: [cerebellum, predictive-coding, motor-cortex, world-model, efference-copy]
prerequisites: [cerebellum, motor-cortex]
opens_questions: [Q-cb-01, Q-fm-01]
source_articles: [2026-06-23-cerebellum-motor-prediction]
key_sources: ["PMID:21227230", "PMID:33203932"]
---

# 前向模型 (Forward Model)

> **一句话定义**：给定运动指令（传出拷贝），预测该运动将产生什么感觉后果的内部计算模型——被认为主要由小脑实现，使大脑能在感觉反馈到达（延迟 20–100ms）之前就对运动结果有精确预期，从而实现快速精确运动控制。

## 当前理解

感觉反馈存在神经传导延迟（末梢到皮层约 20–100ms），这使"等待反馈再纠错"无法实现快速精确的运动。Wolpert、Miall 和 Kawato（1998, PMID:21227230）提出，小脑包含两类**内部模型**：

**前向模型（Forward Model）**：
- 输入：运动指令的副本（**传出拷贝 / efference copy**）
- 输出：预测的感觉后果（手臂将在何处、将感知到何种触觉）
- 功能：让大脑预先知道运动的"期望结果"，而无需等待真实感觉反馈

**逆向模型（Inverse Model）**：
- 输入：期望的运动轨迹
- 输出：达到该轨迹所需的运动指令
- 功能：直接反向计算控制信号，实现精确轨迹跟踪

前向模型输出的预测，与通过下橄榄核→攀爬纤维到达浦肯野细胞的实际感觉信号**对比**，产生**预测误差**。这个误差驱动小脑可塑性（LTD/LTP）更新内部模型，使预测越来越准确。

这一框架的深远意义：小脑不是被动等待误差来纠正，而是**主动预测以超越延迟**。"闭眼精准接球"成为可能，正是因为大脑在球飞来的过程中持续更新前向模型的输出，在接触发生之前就完成了运动调整。

## 关键机制

### MOSAIC 模型（Wolpert & Kawato 扩展版）
多模块前向/逆向模型对（Multiple paired forward-inverse models），每对负责不同的运动情境（如持物 vs 空手）。责任信号（responsibility signal）动态选择哪组模型被激活，类似混合专家（mixture of experts）架构。

### 前向模型的神经底物（尚不确定）
- 小脑颗粒细胞的时序放电模式可能提供时间基础
- 小脑浦肯野细胞的简单放电（simple spike）编码预测输出
- 复杂放电（CF）→ 预测误差信号

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 小脑参与前向预测（间接） | 眼球跟踪（VOR/OKR）延迟补偿；计算建模 | PMID:21227230 | 中（间接） |
| 传出拷贝在运动前到达小脑 | 解剖学：皮质-脊髓投射侧支 → 小脑 | 解剖学证据 | 高 |
| 前向模型更新依赖小脑可塑性 | 小脑损伤患者 VOR 适应受损 | 临床证据 | 高 |
| 小脑实现多模块前向模型 | 间接行为学证据；fMRI 研究 | 多项研究 | 中 |

## 连接

- [[cerebellum]] — 前向模型的主要神经底物
- [[predictive-coding]] — 前向模型是预测处理的一个专用子系统
- [[motor-cortex]] — 发出运动指令和传出拷贝
- [[world-model]] — 前向模型是更广义世界模型的一个专用子系统（运动领域）
- [[cerebellar-ltd]] — 误差信号驱动前向模型更新的分子机制

## 未解问题

- Q-cb-01：前向模型的时序预测在颗粒细胞层面如何实现？时间基础是什么？
- Q-fm-01：前向模型框架能否扩展到语言（预测下一个词）和社会认知（预测他人反应）？与 CCAS 的关联？

## 修订历史

- 2026-06-23 · 创建 · 基于《小脑的秘密》一文 · 初始置信度：中（间接证据为主，计算框架合理但神经底物细节待确认）

## 来源文章

- [[2026-06-23-cerebellum-motor-prediction]]

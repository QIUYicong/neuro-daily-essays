---
title: 轴突始段
slug: axon-initial-segment
domain: neurons
type: structure
status: established
confidence: high
created: 2026-05-24
updated: 2026-05-24
revision_count: 1
dimensions: [molecular, cellular, microcircuit]
related: [action-potential, voltage-gated-sodium-channel, chandelier-cell, hodgkin-huxley-model]
prerequisites: [action-potential, voltage-gated-sodium-channel]
opens_questions: [Q-ais-gaba-polarity, Q-ais-plasticity-pathway, Q-nav-developmental-switch, Q-ais-disease-role, Q-human-ais-specificity]
source_articles: [2026-05-24-axon-initial-segment]
key_sources: ["PMID:41930336", "PMID:28536506"]
---

# 轴突始段 (Axon Initial Segment, AIS)

> **一句话定义**：轴突始段是轴突起点后约 20–60 μm 的特化区段，拥有超高密度的电压门控钠通道，是动作电位发起的主要位点，也是神经元整合所有输入、做出"发火或沉默"决定的解剖学中枢。

## 当前理解

我们现在认为，神经元的"决策"是**局部化、分子化**的，集中发生在轴突始段（AIS）而非整个细胞体。AIS 上的钠通道密度约为细胞体的 **50 倍**，配合激活阈值最低的 NaV1.6，使这里成为最易触发正反馈、最先产生动作电位的地方。所有来自树突和胞体的突触电位汇聚到 AIS，在此被阈值化为离散的全或无脉冲。

更重要的是，AIS 不是静态结构：它通过**活动依赖性稳态可塑性**动态调整自身长度与位置，从而调节神经元兴奋性。它还是大脑专属抑制（见 [[吊灯细胞]]）的精确靶点。因此 AIS 同时是动作电位的诞生地、神经元输入-输出转换的关键节点、以及一个可被调控的"决策旋钮"。

## 关键机制

**分子架构（三层）**：
1. 内层——平行微管束（Tau 蛋白参与稳定）。
2. 中层——周期性肌动蛋白环（间距 ~190 nm），由 βIV-血影蛋白四聚体连成膜下网格。
3. 脚手架——**AnkyrinG（锚蛋白 G）**：主组织者，通过膜结合域直接结合 Nav 通道 II-III 连接子上的保守胞内基序，把通道锁定在 AIS。AnkyrinG 缺失则 AIS 功能崩溃。CK2 磷酸化 Nav1.2 丝氨酸残基可调控其与 AnkyrinG 的结合。

**离子通道配置**：成熟 AIS 以 [[电压门控钠通道]] NaV1.6 为主（阈值最低），发育早期以 NaV1.2 为主；钾通道 KV7.2/7.3 居近端（设定静息电位），KV1 居远端（调波形与重复放电）。

**整合与发起**：汇聚的去极化在 AIS 达约 -50–-55 mV 阈值后，NaV1.6 正反馈雪崩 → 全或无动作电位（见 [[动作电位]]）。

**稳态可塑性**：慢性高活动 → AIS 变短并向远端移位（降兴奋性）；慢性低活动 → 变长并向近端移位（升兴奋性）。

**回路调控**：[[吊灯细胞]]（轴-轴突中间神经元）特异性靶向 AIS，是已知最高效的抑制方式，与 γ 振荡和工作记忆相关。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| AIS 钠通道密度约为胞体 50 倍 | 超分辨成像（STORM/STED）+ 膜片钳 | PMID:41930336 | 高 |
| AnkyrinG 是 AIS 组织必需，敲除则 Nav 无法聚集 | 条件性敲除实验 | PMID:28536506 | 高 |
| AnkyrinG 经膜结合域结合 Nav II-III 连接子保守基序 | 分子结合实验 | PMID:28536506 | 高 |
| 慢性活动剥夺（TTX）使 AIS 延长/近移、兴奋性升高 | 培养神经元 + 免疫荧光 | PMID:41930336 | 中-高 |
| 吊灯细胞特异靶向 AIS，与工作记忆/γ 振荡相关 | 光遗传 + 行为 | PMID:41930336 | 中 |

## 连接

- [[动作电位]] — AIS 是其发起位点
- [[电压门控钠通道]] — AIS 超高密度聚集的核心分子（NaV1.6/NaV1.2）
- [[吊灯细胞]] — 特异性抑制 AIS，调控其输出
- [[Hodgkin-Huxley 模型]] — 描述 AIS 处的钠/钾电导动力学

## 未解问题

- **Q-ais-gaba-polarity**：AIS 处 GABA 是超极化（抑制）还是去极化？（争议）
- **Q-ais-plasticity-pathway**：AIS 稳态可塑性的下游信号通路是什么？
- **Q-nav-developmental-switch**：NaV1.2→NaV1.6 发育转变的完整机制？
- **Q-ais-disease-role**：AIS 改变在神经退行性疾病中是代偿还是病理？
- **Q-human-ais-specificity**：人类 AIS 与啮齿类有何功能性差异？

## 修订历史

- 2026-05-24 · 创建 · 基于《决策的解剖学：神经元如何在混沌的输入中找到它唯一的声音》· 初始置信度：高

## 来源文章

- [[2026-05-24-axon-initial-segment]]

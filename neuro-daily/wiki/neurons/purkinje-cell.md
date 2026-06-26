---
title: 浦肯野细胞
slug: purkinje-cell
domain: neurons
type: structure
status: established
confidence: high
created: 2026-09-03
updated: 2026-10-09
revision_count: 3
dimensions: [cellular, synaptic, microcircuit, brain-region]
related: [cerebellum, cerebellar-ltd, climbing-fiber, parallel-fiber, granule-cell, deep-cerebellar-nuclei, forward-model, motor-cortex, molecular-layer-interneuron, rebound-potentiation]
prerequisites: [inhibitory-synapse, ampa-receptor, voltage-gated-calcium-channels, mGluR1]
opens_questions: [Q-pc-01, Q-pc-02, Q-pc-03]
source_articles: [2026-09-03-purkinje-cell-cerebellar-motor-learning, 2026-10-09-mli-cerebellar-interneuron-plasticity]
key_sources: ["PMID:40523942", "PMID:39049990", "PMID:31572132", "PMID:21482355", "PMID:24600347", "PMID:38692278"]
---

# 浦肯野细胞 (Purkinje Cell)

> **一句话定义**：小脑皮层的唯一输出神经元——整合约 20 万条平行纤维（运动情景信号）与单根攀爬纤维（误差/预测违反信号）的输入，通过长时程抑制（LTD）等多层可塑性机制持续优化运动预测，是实现精确、自动化运动技能的细胞基础。

## 当前理解

我们现在认为，浦肯野细胞（Purkinje cell，PC）是小脑皮层计算的核心节点。它具有脑中最复杂的树突扇形结构之一，轴突向下投射到深部小脑核（DCN），通过 GABA 介导的持续抑制调控 DCN 输出——当 PC 发放减少时，DCN 得以去抑制，向运动皮层/脑干输出驱动信号。

PC 的两类主要输入体现截然不同的信息流：
- **平行纤维（PF）**：来自颗粒细胞（约 20 万条，但每条在 PC 上仅形成少数突触），编码当前感觉运动情景
- **攀爬纤维（CF）**：来自下橄榄核（每 PC 仅一根，但形成数百个强突触），触发"复杂放电"，携带预测违反信号（经典：运动误差；新证据：也包括奖励预测误差）

当 PF 与 CF 同时激活时，发生 **PF-PC LTD**：AMPA 受体通过 mGluR1→IP₃→PKC→GluA2 Ser880 磷酸化→内吞 的级联从突触移除，削弱该 PF 通道对 PC 的影响。Schonewille 等 2011 年证明 LTD 并非运动学习唯一必要机制；多层可塑性（MLI 可塑性、内在可塑性、DCN 可塑性）提供冗余通道。

PC 计算模型（Fernández Santoro 2024）揭示其多稳态（multistable）动力学：除了连续发放，PC 可在特定条件下出现平台电位（plateau potential）和爆发—停顿模式——这些动力学特征也是其计算能力的来源。

## 关键机制

### 解剖特征
- 树突扇形展开在与平行纤维垂直的平面，形成巨大"接收面积"
- 每个 PC 约接受 200,000 条 PF（弱突触）+ 1 根 CF（极强突触，400–500 个释放位点）
- 轴突投射至 DCN（主要）和前庭神经核（部分）
- 发放类型：简单放电（Simple spike，~50–100 Hz，自发或 PF 驱动）vs 复杂放电（Complex spike，~1 Hz，CF 驱动）

### PF-PC LTD 级联
1. PF 激活 → AMPAR（快速）+ mGluR1（慢速）
2. CF 同时激活 → 复杂放电 → P/Q 型 VGCC → 大量 Ca²⁺ 内流
3. mGluR1 → Gq → PLCβ → IP₃ + DAG；IP₃ → ER Ca²⁺ 释放
4. 高 Ca²⁺ + DAG → PKCα/γ 激活
5. PKCα 磷酸化 GluA2 Ser880 → AMPAR 内吞 → PF-PC 突触削弱

### 多层可塑性（Schonewille 2011 后修订）
- **PF-PC LTD（经典）**：mGluR1→IP₃→PKC→AMPAR 内吞；见 [[cerebellar-ltd]]
- **PF-PC LTP**：单独 PF 激活（无 CF）或 LTD 反转
- **MLI 逆向可塑性**：PF→MLI LTP（CF 存在时）+ 反弹增强（RP，MLI→PC 抑制性 LTP）；见 [[molecular-layer-interneuron]] 和 [[rebound-potentiation]]
- **内在可塑性**：离子通道表达变化，影响 PC 放电特性
- **DCN 可塑性**：深部小脑核的下游存储

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| CF 触发复杂放电，驱动 PF-PC LTD | 脑片电生理 + mGluR1 KO | PMID:7954803 | 高 |
| LTD 对运动学习不是唯一必要机制 | 三种 AMPAR 内吞阻断突变小鼠运动学习正常 | PMID:21482355 | 高 |
| 复杂放电持续时间编码梯度可塑性信息 | 电控 CF 爆发时间 vs 可塑性量 | PMID:24814344 | 中-高 |
| PC 多稳态动力学是计算能力来源 | 详细 Hodgkin-Huxley 型模型 + 体外验证 | PMID:39049990 | 中 |
| CF 信号包含奖励预测误差特征 | 钙成像 + 光遗传学 in vivo | PMID:40848722 | 中（单实验室，外侧小脑） |

## 连接

- [[cerebellum]] — PC 所在的系统架构
- [[cerebellar-ltd]] — PC 的核心可塑性机制详情
- [[climbing-fiber]] — PC 的"教师"输入
- [[granule-cell]] — PC 的"学生"输入的来源
- [[parallel-fiber]] — 携带运动情景信息至 PC 的轴突
- [[deep-cerebellar-nuclei]] — PC 输出的主要靶点
- [[forward-model]] — PC 网络实现的功能：运动预测
- [[motor-cortex]] — PC→DCN→丘脑→运动皮层的功能环路
- [[molecular-layer-interneuron]] — MLI 对 PC 施加前馈抑制；在 CF 误差信号下与 PC 发生逆向可塑性；MLI1/MLI2 亚型门控 PC 学习窗口
- [[rebound-potentiation]] — CF 驱动 PC 去极化后，MLI→PC 抑制突触发生长时程增强（RP）；因果证据：RP 阻断 → VOR 适应受损

## 未解问题

- **Q-pc-01**（高优先级）：CF 在外侧小脑的奖励 rPE 信号与蚓部/中间区的运动误差信号如何在同一 PC 上整合？下橄榄核如何区分两类"预测违反"？
- **Q-pc-02**（高优先级，部分进展）：PC 的停顿（pause）在 DCN 层面通过去抑制机制被读出——Ishikawa 2014 灵长类证据确认 PC 暂停时 DCN 即刻激活（无反弹延迟）；但 Nguyen & Person 2025 的促进型 vs 抑制型 PC 亚型的 DCN 差异投射问题仍未解答——见 [[deep-cerebellar-nuclei]]
- **Q-pc-03**（中优先级）：人类技能习得中，PF-PC 权重如何在数周到数月训练中持续演化？体内长期追踪方法？

## 修订历史

- 2026-09-03 · 创建 · 基于《小脑里的误差教师》一文 · 初始置信度：高（解剖与 LTD 机制 established；奖励 CF 信号 emerging）
- 2026-09-04 · 修订 rev2 · Q-pc-02 部分更新：Ishikawa 2014 灵长类证据确认去抑制是 PC→DCN 信号读出的主要机制（PC 暂停 → DCN 即刻激活，无反弹延迟），补充 [[deep-cerebellar-nuclei]] 链接 · 基于 2026-09-04-deep-cerebellar-nuclei-dcn-output
- 2026-10-09 · 修订 rev3 · 新增：(1) 多层可塑性节详细说明 MLI 逆向可塑性和反弹增强（RP）（基于 Jörntell & Ekerot 2002 PMID:12062025；Hirano 2014 PMC3927423）；(2) 连接新增 molecular-layer-interneuron 和 rebound-potentiation；(3) 新增 key_sources PMID:24600347、PMID:38692278 · 基于 2026-10-09-mli-cerebellar-interneuron-plasticity

## 来源文章

- [[2026-09-03-purkinje-cell-cerebellar-motor-learning]]
- [[2026-09-04-deep-cerebellar-nuclei-dcn-output]]

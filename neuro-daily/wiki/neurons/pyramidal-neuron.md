---
title: 锥体神经元
slug: pyramidal-neuron
domain: neurons
type: entity
status: established
confidence: high
created: 2026-05-27
updated: 2026-07-25
revision_count: 2
dimensions: [cellular, microcircuit, brain-region, molecular]
related: [dendritic-computation, action-potential, axon-initial-segment, nmda-receptor, chandelier-cell, ltp, transcriptomic-cell-types, single-cell-rna-seq]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: []
source_articles: [2026-05-27-dendritic-computation]
key_sources: ["PMID:26605882", "PMID:23841837", "PMID:19661433", "PMID:30382198", "PMID:31435019"]
---

# 锥体神经元 (Pyramidal Neuron)

> **一句话定义**：皮层和海马中最主要的兴奋性神经元类型，以独特的锥体形胞体和双树突系统（顶端 apical + 基底 basal）为特征，是大脑皮层信息处理和树突计算的主要载体。

## 当前理解

我们现在认为，锥体神经元是大脑皮层和海马的主体（约占皮层兴奋性神经元的 70–80%）。其独特的形态——锥体形胞体、单根长顶端树突（apical dendrite，向皮层表面延伸，可超过 1 mm）、多根较短的基底树突（basal dendrites，在胞体附近向各方展开——使它能同时接受来自不同皮层层次和来源的输入，并通过活跃树突特性对这些输入进行非线性整合（见 [[树突计算]]）。

锥体神经元的不同部位接受解剖和功能上截然不同的输入：
- 顶端 tuft（L1）：皮层间长程反馈、丘脑调制输入（top-down）
- 顶端主干和斜向分支：皮层内兴奋性输入
- 基底树突：局部回路兴奋性和抑制性输入（bottom-up，前馈主体）
- 轴突始段（AIS）：动作电位发起位点（见 [[轴突始段]]）

## 关键结构特征

| 结构 | 位置 / 特征 | 功能 |
|------|------------|------|
| 顶端树突 (apical dendrite) | 从胞体向皮层表面延伸，L5 PC 可达 1 mm | 接受 top-down 反馈信号 |
| 顶端 tuft (apical tuft) | 顶端树突在 L1 的扩展部分 | 接受丘脑 Matrix 型和长程皮层反馈 |
| 基底树突 (basal dendrites) | 胞体附近，多根，向各方展开 | 接受局部前馈输入，树突棘的主要来源 |
| 树突棘 (dendritic spines) | 分布于树突分支的蘑菇状突起 | 突触后结构，含 AMPA/NMDA 受体 |
| 胞体 (soma) | 锥体形，5–20 µm | 整合树突输入，产生动作电位判决 |
| 轴突始段 (AIS) | 轴突起始 20–60 µm | 动作电位发起位点，高密度 Nav1.6 |

## 主要细胞类型（按皮层层次）

- **L2/3 锥体细胞**：主要投射到同侧皮层内（皮层间联合纤维）；树突主要在 L1–3 内；参与感觉处理的水平连接
- **L5A 锥体细胞**：投射到纹状体、丘脑等皮层下结构
- **L5B 大型锥体细胞（Betz 细胞等）**：皮层脊髓束；顶端树突最长；Ca²⁺ 棘波研究的主要对象
- **L6 锥体细胞**：大量投射回丘脑（皮质-丘脑反馈）

## 转录组亚型分类（scRNA-seq视角，2026-07-25更新）

scRNA-seq研究（Tasic et al. 2018，PMID:30382198）系统刻画了兴奋性锥体神经元的分子多样性。关键模式：

- **兴奋性细胞类型具有强烈的区域特异性**：视觉皮层和运动皮层的兴奋性亚型组成显著不同，提示皮层功能特化的分子基础主要来自兴奋性神经元的差异化（而GABAergic细胞跨区保守）
- **L5 ET（Extratelencephalic projecting，即皮层下投射）vs IT（Intratelencephalic，即皮层间投射）**：是转录组研究最清晰的兴奋性亚型划分，对应不同的轴突投射目标和功能（运动输出 vs 联合）
- **人类特有深层亚型**：Hodge et al. 2019（PMID:31435019）报告人类颞叶有小鼠中无法对应的深层谷氨酸能亚型，可能与人类高级认知相关（具体功能未知）
- **物种同源性**：尽管有差异，人类和小鼠皮层的兴奋性神经元有"同源"（transcriptomically homologous）类型，支持跨物种比较实验的合理性

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| L5 锥体细胞顶端 tuft 有 NMDA 棘波，统一整合原则 | 大鼠 L5 PC 脑片，tuft 刺激 + Ca²⁺ 成像 | PMID:19661433 | 高 |
| 树突整合的主动/被动特性综述 | 60 年文献综述 | PMID:26605882 (PMC6777373) | 高 |
| NMDA 受体是细薄树突非线性去极化的主要驱动 | 综述 | PMID:23841837 | 高 |

## 连接

- [[树突计算]] — 锥体神经元双树突系统是树突计算的物理基础
- [[动作电位]] — 轴突始段产生，整合树突输入的最终输出
- [[轴突始段]] — 锥体神经元中决定动作电位发放的关键位点
- [[吊灯细胞]] — 特异抑制锥体神经元的 AIS，调控放电阈值

## 未解问题

- 不同皮层区域（PFC、V1、S1）的锥体细胞树突计算特性是否有系统性差异？
- L5B 锥体细胞的前馈 × 反馈耦合（Ca²⁺ 棘波 × 动作电位）在哪些认知任务中被激活？

## 修订历史

- 2026-05-27 · 创建 · 基于《树突：神经元内部的神经网络》一文 · 作为树突计算的主要载体，同时连接 AIS 和 chandelier-cell 两个已有节点 · 初始置信度：高
- 2026-07-25 · 修订（rev2）· 基于《神经元类型的分子宇宙》文章 #93 · 新增"转录组亚型分类"节：兴奋性细胞的区域特异性、L5 ET vs IT划分、人类特有亚型 · 来源：Tasic 2018、Hodge 2019

## 来源文章

- [[2026-05-27-dendritic-computation]]
- [[2026-07-25-scrna-seq-neural-cell-type-diversity]]

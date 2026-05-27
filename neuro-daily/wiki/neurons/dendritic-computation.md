---
title: 树突计算
slug: dendritic-computation
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-05-27
updated: 2026-05-27
revision_count: 1
dimensions: [cellular, microcircuit, cognition]
related: [nmda-receptor, nmda-spike, action-potential, ltp, hebbian-learning, pyramidal-neuron, camkii, synaptic-transmission]
prerequisites: [action-potential, nmda-receptor, synaptic-transmission]
opens_questions: [Q-synaptic-clustering-prevalence, Q-dendritic-spike-in-vivo-frequency, Q-inhibition-dendritic-spike-control]
source_articles: [2026-05-27-dendritic-computation]
key_sources: ["PMID:26605882", "PMID:26167906", "PMID:24162850", "PMID:15156147", "PMID:10749211"]
---

# 树突计算 (Dendritic Computation)

> **一句话定义**：皮层锥体神经元的树突分支能局部产生 NMDA 棘波和 Ca²⁺ 棘波等主动电信号，使每根细薄分支成为独立的非线性计算单元，让单个神经元等价于一个两层神经网络。

## 当前理解

我们现在认为，神经元的树突远不是被动的电缆。皮层锥体神经元的细薄树突分支（基底树突和斜向分支）充满了电压门控离子通道，特别是 NMDA 受体，使它们在接收到相邻、同步的突触输入时能够产生**局部再生性棘波**——称为 NMDA 棘波。这些棘波具有全或无性质、持续 50–200 ms 的时间整合窗，并带来强烈的局部 Ca²⁺ 内流，可诱导局部 LTP。

不同树突分支的输入在胞体层面**线性叠加**，而单根分支内部则是 **sigmoid 非线性**整合——这与一个两层前馈神经网络的结构完全等价：每根分支 ≈ 隐藏层节点，胞体 ≈ 输出层节点。一个拥有 200–500 根树突分支的皮层锥体细胞，因此在功能上等价于一个中等规模的神经网络。

体内实验（视觉皮层、海马）确认树突棘波在活动物的自然感知和记忆编码过程中确实发生，并有行为意义。

## 关键机制

### NMDA 棘波（细薄树突）

1. 相邻的 5–20 个突触同步活跃 → 局部谷氨酸积累
2. 轻微去极化 → 部分解除 NMDA 受体 Mg²⁺ 阻断
3. NMDA 受体开放 → 进一步去极化（正反馈）
4. 突破阈值 → 局部全或无 NMDA 棘波（50–200 ms，Ca²⁺ 内流）
5. Ca²⁺ 触发局部 LTP，固化触发棘波的突触集合

**关键参数**：
- 触发所需输入数：~10 个相邻突触（同步）或 ~20 个更稀疏的时间相关输入
- 持续时间：随刺激强度线性增加，50–200 ms
- 阈值调制：背景去极化或先前 NMDA 棘波可降低阈值

### Ca²⁺ 棘波（顶端树突，L5 锥体细胞特有）

- 位置：顶端树突（apical dendrite）和顶端簇（apical tuft，位于 L1，距胞体 500–1000 µm）
- 介导通道：电压门控 L 型 Ca²⁺ 通道（Cav1.2/1.3）
- 触发：强烈的顶端 tuft 输入 + 背景去极化
- 特性：持续数十毫秒，可从顶端向胞体传播一定距离
- **联合效应**：单独的 Ca²⁺ 棘波通常不足以触发动作电位；若与胞体水平动作电位在数十毫秒内同时发生 → **爆发放电（burst firing）**

这一耦合机制使 L5 锥体细胞能同时感知来自顶端（皮层间反馈/top-down）和胞体附近（局部前馈/bottom-up）的信号，实现细胞层面的"前馈 × 反馈巧合检测"。

### 两层神经网络模型

实验证据（Polsky et al. 2004，PMID:15156147）：
- **同一分支相邻输入** → 胞体响应呈 sigmoid（NMDA 棘波阈值效应）
- **不同分支或远端输入** → 胞体响应呈线性叠加

等价模型：锥体神经元 ≈ 两层前馈神经网络
- 第一层：每根分支做 sigmoid 整合（输入 → 隐藏节点）
- 第二层：胞体线性累加所有分支输出 → 阈值 → 动作电位输出

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 基底树突 NMDA 棘波是真实的离体电生理事件 | 大鼠皮层脑片，焦点谷氨酸刺激 + 膜片钳 | PMID:10749211 | 高 |
| 同分支相邻输入 sigmoid 整合，不同分支线性叠加 | 双位点焦点刺激 + 共焦成像，大鼠新皮层锥体细胞 | PMID:15156147 | 高 |
| L5 顶端 tuft 中有 NMDA 棘波，统一解释远端输入整合 | 大鼠脑片 L5 PC，tuft 刺激 + Ca²⁺ 成像 | PMID:19661433 | 高 |
| 体内视觉皮层 NMDA 依赖树突棘波增强朝向选择性 | 小鼠 V1 in vivo patch-clamp，NMDA 阻断剂 MK-801 | PMID:24162850 (PMC6319606) | 高 |
| CA1 树突平台电位单次触发场所场形成 | 小鼠 CA1 in vivo whole-cell，人工诱导平台电位 | PMID:26167906 (PMC4888374) | 高 |
| 树突整合体内发生（60 年综述） | 多重实验证据综述 | PMID:26605882 (PMC6777373) | 高 |

## 连接

- [[nmda-receptor]] — NMDA 棘波的核心分子机器：NMDA 受体的再生性正反馈
- [[ltp]] — NMDA 棘波提供局部 LTP 所需的强烈 Ca²⁺ 内流，是突触修改的触发器
- [[hebbian-learning]] — 树突计算使 Hebb 规则在分支局部实现，而非仅在单个突触
- [[action-potential]] — 树突棘波与胞体动作电位的耦合（burst firing）是皮层前馈/反馈整合的关键
- [[synaptic-transmission]] — 树突棘波需要多个突触的协调活动，反过来影响突触传递效率
- [[pyramidal-neuron]] — 锥体神经元的特有形态（基底/顶端双树突系统）是树突计算的物理基础

## 未解问题

- Q-synaptic-clustering-prevalence：功能相关的突触是否在同一树突分支上真实聚类？这在不同脑区是否不同？
- Q-dendritic-spike-in-vivo-frequency：清醒自由行为动物中，正常行为条件下树突棘波的发生频率是多少？
- Q-inhibition-dendritic-spike-control：不同类型抑制性中间神经元（SST+、PV+、VIP+）如何精确调控树突棘波的阈值和时间窗？

## 修订历史

- 2026-05-27 · 创建 · 基于《树突：神经元内部的神经网络》一文 · 填补 Hodgkin-Huxley 模型页的悬空引用 · 初始置信度：高

## 来源文章

- [[2026-05-27-dendritic-computation]]

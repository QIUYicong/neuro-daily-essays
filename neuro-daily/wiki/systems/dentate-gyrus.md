---
title: 齿状回
slug: dentate-gyrus
domain: systems
type: region
status: established
confidence: high
created: 2026-08-28
updated: 2026-08-28
revision_count: 1
dimensions: [brain-region, microcircuit, cellular, cognition]
related: [hippocampal-circuit, pattern-separation, pattern-completion, place-cells, grid-cells, entorhinal-cortex, adult-neurogenesis, mossy-cells-dentate, fear-generalization, granule-cells-dentate]
prerequisites: [hippocampal-circuit, synaptic-transmission]
opens_questions: [Q-dg-sparse-01, Q-dg-mc-net-effect, Q-dg-human-imaging]
source_articles: [2026-08-28-dentate-gyrus-sparse-coding-pattern-separation]
key_sources: ["PMID:28132828", "PMID:23259953", "PMID:30790539", "PMID:21788086", "PMC5077296", "PMC3834622", "PMID:35221956"]
---

# 齿状回 (Dentate Gyrus, DG)

> **一句话定义**：海马三突触回路的第一站，通过极端稀疏编码（约 2–5% 颗粒细胞同时激活）将来自内嗅皮层的相似输入转化为高度不重叠的神经表征，实现模式分离，防止相似记忆相互干扰。

## 当前理解

我们现在认为，齿状回的核心计算功能是**主动变换**而非被动传递：它不是将内嗅皮层信号直接中继给 CA3，而是通过一套多层次的抑制回路，将相似的输入信号在高维空间中"展开"并"稀疏化"，使相似的场景在颗粒细胞群体层面产生几乎不重叠的激活模式。

这种稀疏性（约 2–5% 的颗粒细胞同时激活）并非神经元的自然沉默，而是由**篮状细胞、HIPP 细胞、MOPP 细胞**等 GABA 能中间神经元主动雕刻出来的结果。门区的**苔藓细胞**（一种兴奋性细胞）在这套系统中扮演了反直觉的角色：它们通过间接激励抑制性中间神经元，产生对颗粒细胞的净抑制效果；它们的缺失会导致颗粒细胞过兴奋和模式分离功能崩溃。

## 关键机制

### 1. 解剖结构与数量扩张

**连接来源**：
- 主要输入：内嗅皮层（EC）通过**穿通纤维**（perforant path）投射到颗粒细胞
  - 内侧 EC（MEC）：空间信息（网格细胞/头向细胞信号）
  - 外侧 EC（LEC）：物体/非空间情境信息
- 主要输出：颗粒细胞轴突（**苔藓纤维**，mossy fibers）→ CA3 锥体细胞，形成"雷管突触"（detonator synapse）

**数量扩张**：EC 约 20–30 万神经元 → DG 约 100–200 万颗粒细胞（5–10 倍扩张）。数量的扩张是实现高维稀疏表征的解剖学基础。

### 2. 颗粒细胞的内在静息偏好

- 静息膜电位约 -85 mV（比皮层神经元低约 15–20 mV）
- 高动作电位阈值，需要强去极化
- 高密度内向整流钾通道（Kir2.x）维持超极化静息状态

结果：只有接受**最强 EC 汇聚输入**的颗粒细胞才能越过阈值放电。

### 3. 多层 GABA 能抑制网络

| 中间神经元类型 | 靶向位置 | 主要功能 |
|-------------|---------|---------|
| 篮状细胞（basket cells） | 颗粒细胞胞体 / 轴突始段 | 前馈+反馈快速抑制，限制整体激活数量 |
| HIPP 细胞 | 颗粒细胞树突外层 | 与穿通纤维输入同步，"分母滤波" |
| MOPP 细胞 | 颗粒细胞树突（侧向） | 侧向抑制，产生"赢者通吃"竞争 |

### 4. 颗粒细胞 vs 苔藓细胞的双轨策略

（见 [[mossy-cells-dentate]] 专页）

- **颗粒细胞**：极度稀疏，单一位置场，环境变换以"有/无"方式响应 → **模式分离**
- **苔藓细胞**：多位置场，高放电率，环境变换以场位置移动方式响应 → 连接性整合 / 系统监督

### 5. 维度视角

Cayco-Gajic & Silver（2019）指出，模式分离的关键不只是稀疏，而是**表征空间的维度**。DG 的扩张 + 稀疏 + 侧向抑制共同最大化了表征空间的有效维度，使原本在 EC 中重叠的模式在高维 DG 表征空间中可线性分离。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 颗粒细胞激活率约 2–5% | IEG 标记（c-Fos/Arc）+ 体内 juxtacellular 记录 | PMC3834622; PMC5077296 | 高 |
| 颗粒细胞单场低频；苔藓细胞多场高频 | 硅探针 + juxtacellular 鉴定，啮齿类 | PMID:28132828 | 高 |
| 苔藓细胞消融 → 颗粒细胞过兴奋 → 模式分离失败 | 转基因特异性消融 + 行为测试 | PMID:23259953 | 中-高 |
| 苔藓细胞通过反馈抑制增强模式分离 | 计算模型 | PMID:35221956 | 中（待体内验证） |
| 模式分离关键是表征维度而非单纯稀疏 | 跨系统理论分析 | PMID:30790539 | 中（理论框架） |

## 连接

- [[hippocampal-circuit]] — DG 是海马三突触回路的第一站
- [[pattern-separation]] — DG 是模式分离的主要神经基底
- [[pattern-completion]] — DG 模式分离的输出喂给 CA3 的模式补全
- [[entorhinal-cortex]] — DG 接受内嗅皮层的穿通纤维输入
- [[mossy-cells-dentate]] — 门区的兴奋性神经元，通过反馈抑制协调颗粒细胞活动
- [[adult-neurogenesis]] — DG 是成体神经发生的主要场所，新生颗粒细胞动态调制模式分离能力
- [[fear-generalization]] — DG 模式分离失败（如苔藓细胞受损）是恐惧泛化的回路基础
- [[place-cells]] — DG 颗粒细胞的稀疏输出是 CA3/CA1 场所细胞的关键输入来源

## 未解问题

- Q-dg-sparse-01：颗粒细胞激活率在不同任务难度、不同行为状态（探索/奔跑/睡眠）下如何动态变化？2–5% 是所有条件下的固定值吗？
- Q-dg-mc-net-effect：苔藓细胞对颗粒细胞的净效果（抑制 vs 兴奋）是否在不同神经调质状态（ACh、DA、NE 水平）下动态反转？
- Q-dg-human-imaging：人类 DG 功能的直接 fMRI 成像至今面临空间分辨率瓶颈（DG 层极薄），7T fMRI 能否可靠区分 DG 和 CA3 的激活？

## 修订历史

- 2026-08-28 · 创建 · 基于《稀疏奇迹：齿状回如何以 5% 的激活率撑起大脑的记忆分辨》（文章 #126）· 初始置信度：高

## 来源文章

- [[2026-08-28-dentate-gyrus-sparse-coding-pattern-separation]]

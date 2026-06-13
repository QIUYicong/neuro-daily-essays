---
title: 分子层中间神经元
slug: molecular-layer-interneurons
domain: neurons
type: structure
status: established
confidence: high
created: 2026-06-13
updated: 2026-06-13
revision_count: 1
dimensions: [cellular, synaptic, microcircuit]
related: [cerebellum, purkinje-cell, cerebellar-ltd, climbing-fiber-error-signal, parallel-fiber]
prerequisites: [cerebellum, purkinje-cell, parallel-fiber]
opens_questions: [Q-cb-06, Q-cb-07]
source_articles: [2026-06-13-cerebellar-distributed-plasticity-motor-learning]
key_sources: ["PMID:38574161", "PMID:21482355"]
---

# 分子层中间神经元 (Molecular Layer Interneurons, MLI)

> **一句话定义**：小脑皮层分子层中的 GABA 能中间神经元（星状细胞 + 篮状细胞），接受颗粒细胞平行纤维（PF）输入，对浦肯野细胞（PC）施加前馈抑制；其 PF-MLI 突触在攀爬纤维误差信号下发生 LTP（与 PF-PC LTD 方向相反），与 PF-PC LTD 协同共同驱动小脑运动学习。

## 当前理解

分子层中间神经元（MLI）分为两类：
- **星状细胞（Stellate cells）**：位于分子层外侧，轴突与 PC 树突接触
- **篮状细胞（Basket cells）**：位于分子层内侧，轴突终末形成特征性"篮状结构"包围 PC 胞体/轴丘始段

两者均为 GABA 能，对 PC 施加**前馈抑制**：平行纤维 → MLI → PC（抑制）。

**关键新发现（Zhu et al. 2024，PMID:38574161）**：在眼睑条件反射（CEBC）等运动学习范式中，PF-MLI 突触的可塑性规则与 PF-PC 突触**方向相反**——当 PF 与 CF（攀爬纤维，来自下橄榄核）**同时激活**时：
- PF-PC 突触：**LTD**（AMPAR 内吞，权重降低）
- PF-MLI 突触：**LTP**（权重升高）

结果：MLI 对 PC 的抑制增强，从两条路径共同压低 PC 放电：直接削弱 PF→PC 兴奋性输入（LTD）+ 增强 MLI→PC 抑制性输入（MLI-LTP）。

**对 Schonewille 2011 悖论的解释**：三种阻断 AMPAR 内吞（LTD 表达）的突变小鼠运动学习正常，可能正是因为 MLI 通路完整，足以单独实现 PC 放电压低，从而补偿 LTD 的缺失。

## 关键机制

### MLI 前馈抑制回路
```
颗粒细胞 →（平行纤维）→ MLI → GABA → 浦肯野细胞
```

### PF-MLI LTP 诱导规则
- 触发条件：PF 激活 + CF 激活（同时）
- 与 PF-PC 方向相反（PF+CF → PC LTD；PF+CF → MLI LTP）
- 分子机制：尚未完全解明（可能涉及与 mGluR 不同的受体路径）

### 两路并联的协同效应
| 通路 | 可塑性方向 | 效果 |
|------|----------|------|
| PF-PC | LTD | PC 兴奋性输入减弱 |
| PF-MLI（LTP后）→ MLI-PC | MLI 抑制增强 | PC 受到更强抑制 |
| 净效应 | — | PC 放电可靠减少（是 CEBC 所需的条件性抑制）|

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| PF-MLI LTP 与 PF-PC LTD 协同支持 CEBC | 计算建模（系统性位点关闭）| PMID:38574161（Zhu 2024）| 中（计算模型，需神经记录直接验证）|
| 单独关闭 MLI 可塑性：CEBC 减少 ~15%；同时关闭 LTD+MLI：显著受损 | 计算建模 | PMID:38574161 | 中 |
| MLI 前馈抑制对 PC 简单放电具有精确门控功能 | 体外切片电生理 | 多来源 | 高（established）|

## 连接

- [[purkinje-cell]] — MLI 是 PC 的前馈抑制来源
- [[cerebellar-ltd]] — MLI 可塑性（LTP）与 PF-PC LTD 协同共同驱动小脑学习
- [[climbing-fiber-error-signal]] — CF 误差信号同时驱动 PF-PC LTD 和 PF-MLI LTP（方向相反）
- [[cerebellum]] — MLI 是小脑皮层分子层的关键组件
- [[parallel-fiber]] — PF 是 MLI 的主要兴奋性输入来源

## 未解问题

- Q-cb-06：MLI LTP 的确切分子机制是什么？是否与 mGluR1/PKC 通路相关，还是使用了不同的受体/激酶系统？
- Q-cb-07：体内（in vivo）实验中是否可以直接观测 MLI 突触在运动学习中的权重变化？

## 修订历史

- 2026-06-13 · 创建 · 基于《小脑运动学习的分布式革命》（文章#186）· 初始置信度：高（MLI 解剖/抑制功能 established）；PF-MLI LTP 的学习功能（中，计算模型，待实验验证）

## 来源文章

- [[2026-06-13-cerebellar-distributed-plasticity-motor-learning]]

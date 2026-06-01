---
title: 小脑长时程抑制（Cerebellar LTD）
slug: cerebellar-ltd
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-23
updated: 2026-06-23
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [ltd, purkinje-cell, climbing-fiber, mglur1, ampa-receptor, pkc, cerebellar-cortex, cerebellar-forward-model, ltp]
prerequisites: [ltd, ampa-receptor, synaptic-transmission, voltage-gated-calcium-channels]
opens_questions: [Q-cbm-01]
source_articles: [2026-06-23-cerebellar-learning-purkinje-climbing-fiber]
key_sources: ["PMID:36632066", "PMCID:PMC9826949", "PMID:31572132", "PMCID:PMC6749063"]
---

# 小脑长时程抑制 (Cerebellar LTD)

> **一句话定义**：平行纤维（PF）与攀爬纤维（CF）几乎同时激活同一普肯野细胞时，通过 mGluR1a → PKCα → AMPA 受体 GluA2 Ser880 磷酸化 → AMPA 受体内吞，导致该 PF-PC 突触传递效率持久降低，是小脑有监督运动学习的分子基础。

## 当前理解

小脑 LTD（cb-LTD）是神经科学中机制最清晰、研究最深入的学习相关突触可塑性形式之一。它在以下条件下诱导：平行纤维（PF）激活后约 100–300 毫秒内，攀爬纤维（CF）激活同一普肯野细胞（联合激活规则）。

**与海马 LTD 的关键区别**：
- 海马 CA1 NMDA-LTD：低频 → 低 Ca²⁺ → PP2B/PP1 → GluA1 去磷酸化
- **cb-LTD**：CF+PF 联合 → mGluR1a + P/Q-VGCC 高 Ca²⁺ → PKCα → GluA2 Ser880 磷酸化

两种 LTD 的触发条件截然不同：海马 LTD 依赖 NMDA 受体，不需要 CF；cb-LTD 依赖 mGluR1a 和 CF，不需要（至少不必须依赖）NMDA 受体。

**mGluR1a 亚型特异性**：Surdin et al.（2023，PMCID: PMC9826949）使用光遗传嵌合体证明，激活 mGluR1a（而非 mGluR1b）+ PF 共刺激就足以诱导 LTD。这是 cb-LTD 充分条件的直接实验证明。

## 关键机制

### 分子信号级联（标准模型）

**双路 Ca²⁺ 信号汇聚**：
1. PF → mGluR1a → PLC-β → IP₃ → IP₃R → 内质网 Ca²⁺ 释放（局部，仅在被激活的 PF 突触棘内）
2. CF → 复杂棘波 → P/Q-VGCC 开放 → 胞外 Ca²⁺ 大量内流（广泛树突）

两路 Ca²⁺ 在局部突触棘内汇聚，激活 **PKCα**（Ca²⁺ + DAG 双重激活）。

**AMPA 受体靶向内吞**：
- PKCα 磷酸化 GluA2 亚基 **Ser880**
- 磷酸化 → 破坏 GRIP1/2 的 PDZ 结合（锚定蛋白丧失）
- GluA2 转而与 PICK1 结合
- PICK1 介导 AMPA 受体通过网格蛋白依赖性内吞进入内体

**结果**：该 PF-PC 突触的 AMPA 受体数量减少 → 突触电流减小 → 突触权重持久降低（LTD）。

### 联合激活规则（Hebbian 的反面）
海马 Hebbian/LTP：相关性（同时激活→加强）
cb-LTD：CF 标记的误差（"同时激活错误" → 弱化），是**反 Hebbian** 的监督学习

### LTD 的空间特异性
虽然 CF 触发的 Ca²⁺ 内流覆盖整个树突，但只有**同时被 PF 激活**的那些突触棘内才有足够的 mGluR1a 信号（局部 IP₃/DAG）与 Ca²⁺ 协同激活 PKCα → 只有"错误同时激活了"的 PF 突触才发生 LTD，其他 PF 突触不受影响。

## 关键证据
| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| mGluR1a（非 1b）是 LTD 充分条件 | 光遗传+体外/体内 | PMCID:PMC9826949（Surdin 2023）| 高 |
| CF 提供梯度化 Ca²⁺ 信号 | 膜片钳+Ca²⁺ 成像 | PMCID:PMC6749063（Zang 2019）| 中高 |
| LTD 是小脑运动学习的充分（可能非必要）条件 | LTD 缺陷转基因小鼠（PICK1 KO 等）仍有部分学习 | PMCID:PMC4691440（Popa 2016 综述）| 中 |

## 与其他 LTD 形式的比较
→ 见 [[长时程抑制（LTD）]] 页面

## 未解问题
- Q-cbm-01：cb-LTD 是否是小脑学习的必要条件？（多位点可塑性争议）

## 修订历史
- 2026-06-23 · 创建 · 来自《错误的教育》文章 · 置信度：高

## 来源文章
- [[2026-06-23-cerebellar-learning-purkinje-climbing-fiber]]

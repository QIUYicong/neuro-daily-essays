---
title: 短语结构组装（Merge操作）
slug: phrase-structure-building
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-08-07
updated: 2026-08-07
revision_count: 1
dimensions: [brain-region, cognition, microcircuit]
related: [broca-area, language-network, arcuate-fasciculus, working-memory, hierarchical-representation]
prerequisites: [broca-area, language-network]
opens_questions: [Q-lang-03, Q-lang-06]
source_articles: [2026-08-07-brocas-area-syntax-merge-language-evolution]
key_sources: ["PMID:36405085", "PMID:36130104", "PMID:18554927", "PMID:31735144"]
---

# 短语结构组装（Merge操作）(Phrase Structure Building / Merge)

> **一句话定义**：短语结构组装是大脑将词汇序列"升维"为层级树状句法结构的核心计算，神经基础为左侧BA44（Broca区后部）；Chomsky的"Merge"操作——递归地将两个语言对象合并为一个更高级对象——是这一过程的最小计算描述。

## 当前理解

我们现在认为，句法组装（phrase structure building）是人类语言区别于所有已知动物通信系统的核心特征：它允许有限词汇生成无限新颖句子（Chomsky 1995，最小主义程序）。神经基础为左侧BA44（Broca区pars opercularis）。

**关键计算特征**：
- **递归性**：Merge可应用于自身的输出，产生任意深度的嵌套结构（"从句中的从句"）
- **层级性**：词组装为短语，短语组装为句子——结构是树状而非线性的
- **对偶性**：Merge同时创建两种结构——集合关系（什么被合并）和序列关系（线性顺序）

**与线性序列记忆的区分**：实验室常用AⁿBⁿ型人工语法（如`AAABBB`）vs. 简单邻接序列（如`ABABAB`）来分离层级处理和序列记忆。只有前者需要"跨距"的层级对应，才能选择性激活BA44。

**产出和理解共享Merge**：Hu et al.（2022）精准fMRI证明语言网络（含BA44）在产出和理解时均强激活，无产出/理解特异区域，说明Merge操作不是单向的"产出程序"，而是双向可用的语言知识表征。

## 关键机制

```
Merge操作示意（以"追猫的狗"为例）：

词库：{追, 猫, 的, 狗}
Step 1: Merge(追, 猫) → [VP 追猫]
Step 2: Merge([VP 追猫], 的) → [REL 追猫的]
Step 3: Merge([REL 追猫的], 狗) → [NP [REL 追猫的]狗]

这个NP可以继续作为更大句子的成分：
Step 4: Merge(动词, [NP ...]) → [VP ...] → ...
```

**BA44在回路中的位置**：
- 输入：颞顶界面区（Spt）通过弓状束（AF）传来的词汇序列信号
- 处理：执行Merge，维护当前构建中的句法树状结构
- 输出：语义整合（→颞叶）、发音程序（→运动前区）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| BA44选择性激活于层级句法（AⁿBⁿ型），非线性序列（ABⁿ型） | fMRI人工语法实验 | PMID:18554927 | 高 |
| BA44选择性编码grammatical词组（限定词+名词），BA45编码semantic词组 | fMRI MVPA解码（Schell 2022） | PMID:36405085 | 中高 |
| 句子产出（句法组装）> 词列产出（无组装），全语言网络均激活 | 精准fMRI n=29（Hu 2022） | PMID:36130104 | 高 |
| BA44激活强度随中心嵌入层级深度线性增加 | 参数化fMRI（Friederici等） | PMID:31735144 | 中高 |
| 猴子能学（AB）ⁿ但不能学AⁿBⁿ，对应人类BA44特化 | 灵长类行为实验 | Fitch & Hauser 2004 | 中 |

## 连接

- [[broca-area]] — BA44是Merge操作的主要神经基础
- [[language-network]] — 短语结构组装是整个语言网络协作完成的，BA44是额叶核心节点
- [[arcuate-fasciculus]] — 弓状束传递句法所需的词汇序列信息（Spt→BA44）
- [[working-memory]] — 句法组装过程中需要维护"构建中"的短语树，占用工作记忆资源
- [[hierarchical-representation]] — Merge生成的层级树是层级表征的语言实例

## 未解问题

- Q-lang-03：语法与语义的神经解离能否严格成立？BA44的激活是"纯句法Merge"还是"语义约束下的句法搜索"？
- Q-lang-06：BA44前部扩张（人类进化特化）与FOXP2的关联是否存在？

## 修订历史

- 2026-08-07 · 创建 · 基于《组装句子的机器》（#106） · 初始置信度：高

## 来源文章

- [[2026-08-07-brocas-area-syntax-merge-language-evolution]]

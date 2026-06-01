---
title: 模式分离
slug: pattern-separation
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-24
updated: 2026-06-24
revision_count: 1
dimensions: [microcircuit, cellular, cognition]
related: [hippocampal-circuit, attractor-network, pattern-completion, place-cells, adult-neurogenesis, dentate-gyrus, engram-cells]
prerequisites: [hippocampal-circuit, place-cells]
opens_questions: [Q-pc-03]
source_articles: [2026-06-24-hippocampal-ca3-pattern-completion]
key_sources: ["PMID:17303747", "PMID:21460835", "PMID:15272123", "PMID:7704110", "PMID:35368306"]
---

# 模式分离 (Pattern Separation)

> **一句话定义**：把相似的输入模式转化为高度不重叠（正交）的神经表征，防止记忆之间相互干扰，主要由海马齿状回（DG）的稀疏扩张编码实现。

## 当前理解

我们现在认为，模式分离不是记忆系统中的一个可选功能，而是实现**模式补全**的前提条件：如果相似事件不被首先分离成不相似的神经表征，它们就会落入同一个 CA3 吸引子，导致记忆混淆。

DG（齿状回）通过两个机制实现模式分离：
1. **扩张重编码**（expansion recoding）：将 EC 的约 20 万神经元的信号映射到约 100 万颗粒细胞，在高维空间中使原本相似的表征更易于分离
2. **稀疏激活竞争**：通过篮细胞/苔状细胞介导的侧向抑制，确保任意时刻只有约 2–5% 的颗粒细胞激活

成人神经发生为 DG 提供额外的模式分离能力：新生颗粒细胞活动更稀疏，选择性地增强对相似情景的区分（Sahay et al. 2011, PMID:21460835）。

## 关键机制

### 1. 扩张重编码（Expansion Recoding）

DG 的解剖结构在输入-输出比上是反向的：
- **输入**：EC → DG（穿孔通路）：约 20 万 EC 神经元 → 约 100 万 DG 颗粒细胞（5× 扩张）
- **输出**：DG → CA3（苔状纤维）：每个 CA3 细胞约 50 个苔状纤维输入

根据 Cover 定理：把 N 个点投影到足够高维的空间后，它们以高概率线性可分。DG 的高维展开使原本在 EC 中相似的模式在 DG 中被分得更开。

### 2. 稀疏激活

DG 颗粒细胞的激活稀疏性（<5%）由以下机制保证：
- **篮细胞**（basket cells）：接受兴奋性输入后反馈抑制周围颗粒细胞，实现侧向抑制
- **苔状细胞**（mossy cells）：通过中间抑制性神经元实现远程抑制
- 竞争结果：只有"最强"激活的颗粒细胞"存活"，其余被抑制

稀疏性的计算效应：两个有 70% 重叠的 EC 输入模式，在 DG 层面的颗粒细胞活动重叠可能降低到 5–10%，接近正交。

### 3. CA3 的双重身份：既分离又补全

重要的是，CA3 也有一定的模式分离能力，与 DG 有功能重叠但不完全相同：

- **Leutgeb 2004（PMID:15272123）**：CA3 在完全不同的环境中产生全局重映射（pattern separation），在相似环境中则倾向于维持已知的吸引子（pattern completion）
- **Leutgeb 2007（PMID:17303747）**：DG 对**微小**环境差异敏感（全局重映射），CA3 对小差异使用率重映射——DG 在细粒度分离上比 CA3 更激进

因此，DG 负责"细粒度分离"，CA3 负责"粗粒度分类/吸引子化"，两者串联形成梯度分离机制。

### 4. 成人神经发生与分离能力

DG 是成人大脑中成神经发生最活跃的区域之一。新生颗粒细胞具有：
- 更高的兴奋性（低激活阈值，更宽动作电位）
- 更稀疏的成熟后激活模式
- 特定时间窗口的增强可塑性

Sahay et al. (2011, PMID:21460835) 因果证明：增加 DG 新生神经元数量 → 选择性改善相似情景的区分（而不影响不相似情景的记忆）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| DG 对微小环境差异产生全局重映射 | 大鼠多环境单细胞记录 | PMID:17303747 | 高 |
| 增加神经发生改善模式分离 | BAX KO 小鼠神经发生增加→相似情境区分提升 | PMID:21460835 | 高（因果证据）|
| CA3 在大差异下产生全局重映射，小差异下产生率重映射 | 体内多单元记录+多相似度环境条件 | PMID:15272123 | 高 |
| DG 稀疏活动（<5% 颗粒细胞） | 钙成像和单元记录 | PMID:35368306（综述）| 高 |

## 连接

- [[pattern-completion]] — 互补的计算配对：分离确保不同事件的正交化表征，使补全能找到正确吸引子
- [[hippocampal-circuit]] — DG 是海马三突触回路的第一步
- [[attractor-network]] — 模式分离输出给吸引子网络，使不同记忆形成独立的吸引子盆地
- [[engram-cells]] — DG 是印迹细胞分配的主要场所；DG 的稀疏活动确保印迹间的低重叠度
- [[place-cells]] — 场所细胞的"重映射"（remapping）是模式分离在空间记忆中的具体表现
- [[complementary-learning-systems]] — 模式分离是 CLS 理论中海马快速稀疏编码的实现机制

## 未解问题

- Q-pc-03：人类成人海马神经发生对模式分离的贡献有多大？多项研究对人类成人神经发生规模有争议（Sorrells 2018 vs Boldrini 2018），这直接影响 Sahay 2011 结果是否适用于人类。

## 修订历史

- 2026-06-24 · 创建 · 基于"记忆不混淆的秘密"第 60 篇文章 · 新建专页，整合 DG 机制、成人神经发生因果证据和 CA3 双重功能 · 初始置信度：高

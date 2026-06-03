---
title: 记忆分配
slug: memory-allocation
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-03
updated: 2026-06-03
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, cognition]
related: [engram-cells, creb-activity, intrinsic-excitability, competition-selection-principle, coallocation, pv-interneurons, pattern-separation, pattern-completion, ltp, hebbian-learning]
prerequisites: [engram-cells, ltp, hebbian-learning, pv-interneurons]
opens_questions: [Q-alloc-epigenetic-natural, Q-alloc-cortex, Q-alloc-human-direct, Q-alloc-six-hour]
source_articles: [2026-06-03-engram-competition-creb-allocation]
key_sources: ["PMID:17446403", "PMID:25102562", "PMID:27463673", "PMID:27187069", "PMID:29709212", "PMID:41470040"]
---

# 记忆分配 (Memory Allocation)

> **一句话定义**：在一次学习事件中，决定哪些神经元被选入记忆印迹的竞争性过程；核心机制是：学习前 CREB 活性驱动的内在兴奋性差异使高兴奋性细胞优先被激活，赢得"印迹席位"，而赢者通过 GABA 能抑制压制输者，维持印迹稀疏性。

## 当前理解

我们现在认为，记忆编码不是被动地"激活哪里就记住哪里"，而是一个主动的竞争性选择过程——**记忆分配**。在大脑的学习结构（如杏仁核、海马齿状回）中，具有更高内在兴奋性（intrinsic excitability）的神经元在学习事件发生时优先被激活，因此优先发生突触可塑性变化，被纳入该记忆的印迹细胞群。

这个过程的时序至关重要：兴奋性差异在学习**之前**就已经存在，而不是在学习过程中产生。CREB（cAMP 应答元件结合蛋白）是调控这种预置兴奋性差异的关键转录因子，而其上游是表观遗传状态（特别是组蛋白 H3K27ac 乙酰化水平）。

赢得竞争的神经元（印迹细胞）并不只是"更活跃"，还会通过激活 PV+ GABA 能中间神经元，主动抑制邻近的竞争失败细胞，维持约 10–25% 的印迹稀疏度。这种抑制维持约 6 小时，构成了时间记忆整合的窗口（→ 共分配，coallocation）。

## 关键机制

### 1. 学习前兴奋性地形图（Pre-training excitability landscape）

神经元群体中存在内在兴奋性的自然波动（基于 CREB 活性、表观遗传状态等）。这个地形图决定了哪些神经元"准备好"在学习事件发生时首先越过发放阈值。

### 2. CREB 驱动的兴奋性调控

CREB 活性 → 调控 K⁺ 通道表达（下调导致膜电位更接近阈值）、Ih 电流、AMPA 受体亚基 → 整体内在兴奋性升高。
- **证据（PMID:17446403）**：LA 神经元 CREB OE → Arc+ 率显著更高；消融 CREB OE 细胞 → 记忆损坏
- **证据（PMID:25102562）**：训练前人工提升兴奋性（非 CREB OE）→ 同样偏向性分配；人工激活分配细胞 → 记忆提取

### 3. 竞争性抑制维持稀疏性

赢得分配的神经元（胜者）激活局部 PV+ 中间神经元 → GABA 能前馈抑制邻近输家 → 维持印迹稀疏度（~10–25%）和时间约 6 小时的"兴奋性压制窗口"。

### 4. 共分配（Coallocation）与时间整合

6 小时时间窗内发生的第二次学习事件：第一次的印迹细胞仍处于较高兴奋性余晖期 → 优先被再次招募 → 两个印迹细胞群重叠 → 两段记忆在细胞层面被物理连接。
- **证据（PMID:27463673）**：同日恐惧条件化 → ~35% 印迹重叠；7 天间隔 → ~5% 重叠

### 5. 跨脑区普遍性

同样机制在海马齿状回（DG）成立：DG CREB OE → 偏向分配进入情境恐惧记忆印迹（PMID:27187069，全文开放）。皮层中的类似机制尚待验证。

### 6. 表观遗传上游机制（最新，2025）

H3K27ac（组蛋白乙酰化）水平与内在兴奋性实时正相关 → 表观遗传异质性是兴奋性地形图的更深层基础。
- HAT OE（组蛋白乙酰转移酶过表达）→ 增加分配偏向（PMID:41470040，全文开放）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| CREB OE 偏向性纳入杏仁核恐惧印迹 | LA CREB OE；Arc+ 率↑；消融损坏记忆 | PMID:17446403（摘要） | 高 |
| 训练前兴奋性是分配关键变量 | DREADDs/光遗传↑兴奋性前 → 偏向分配 | PMID:25102562（摘要） | 高 |
| 时间接近决定印迹重叠程度 | 同日 ~35% 重叠 vs 7 天 ~5% 重叠 | PMID:27463673（摘要） | 高 |
| 竞争分配在海马 DG 同样成立 | DG CREB OE 分配实验 | PMID:27187069（全文） | 高 |
| GABA 竞争抑制维持稀疏性，窗口约 6h | 综合分析，机制推断 | PMID:29709212（全文，PMC9623596） | 中 |
| H3K27ac 与内在兴奋性实时正相关 | FRET + 钙成像同步测量 | PMID:41470040（全文，PMC12754038） | 中（新发现）|

## 连接

- [[engram-cells]] — 记忆分配决定哪些细胞成为印迹细胞；分配机制是印迹形成的前提
- [[competition-selection-principle]] — 记忆分配是神经科学中竞争-遴选架构在细胞级的具体实现
- [[pv-interneurons]] — PV+ 中间神经元执行"赢者抑制输者"的竞争压制
- [[ltp]] — 分配后的印迹细胞通过 LTP 完成突触增强，形成印迹的结构基础
- [[hebbian-learning]] — 分配机制解释了 Hebb 规则的"哪个神经元参与了共同激活"的前提条件
- [[pattern-separation]] — 分配竞争维持印迹稀疏性，是 DG 模式分离的细胞基础
- [[synaptic-tagging-capture]] — 6 小时时间窗口可能与突触标记抓取的"早晚 LTP"时间窗口相关
- [[perineuronal-nets]] — PNN 在关键期中类似地限制了可塑性竞争的"游戏规则"

## 未解问题

- Q-alloc-epigenetic-natural：自然学习条件下 H3K27ac 异质性的效应量？
- Q-alloc-cortex：皮层（前额叶、视觉皮层）是否有类似竞争分配机制？
- Q-alloc-human-direct：人类是否有不依赖 fMRI 的直接记忆分配证据？
- Q-alloc-six-hour：6 小时余晖窗口的分子基础（突触标记？CREB 激活动力学？）

## 修订历史

- 2026-06-03 · 创建 · 基于《神经元如何竞争"记忆席位"》一文 · 初始置信度：高（CREB/兴奋性机制）；中（竞争抑制时间窗、表观遗传层）

## 来源文章

- [[2026-06-03-engram-competition-creb-allocation]]

---
title: 记忆分配
slug: memory-allocation
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-05-31
updated: 2026-05-31
revision_count: 1
dimensions: [cellular, cognition, synaptic]
related: [engram-cells, hebbian-learning, ltp, hippocampal-circuit]
prerequisites: [engram-cells, ltp, hebbian-learning]
opens_questions: [Q-engram-human-allocation]
source_articles: [2026-05-31-engram-cells-memory-trace]
key_sources: ["PMID:29709212", "PMID:22441246"]
---

# 记忆分配 (Memory Allocation)

> **一句话定义**：在学习事件发生时，大脑通过神经元内在兴奋性的竞争，将记忆印迹"分配"给特定的稀疏神经元集群——兴奋性较高的神经元赢得竞争，成为印迹细胞。

## 当前理解

我们现在认为，并非所有神经元都有同等机会成为印迹细胞。学习事件发生时，局部神经元群进行**兴奋性竞争**，最终由训练时内在兴奋性（intrinsic excitability，即神经元对相同输入的放电倾向）最高的那一小部分神经元赢得"印迹席位"（Josselyn & Frankland 2018，PMID:29709212）。

这一机制确保了记忆印迹的：
- **稀疏性**（sparseness）：只有少数神经元被分配，使不同记忆的表征保持正交
- **可调节性**（manipulability）：通过人工改变兴奋性可以操控哪些神经元被分配
- **时间关联性**（temporal linking）：在同一兴奋性高峰期内发生的事件的印迹可以重叠

## 关键机制

### 1. CREB 依赖的兴奋性竞争

CREB（cAMP 反应元件结合蛋白）过表达提高神经元兴奋性，使其在 CFC（情境恐惧条件化）中优先进入印迹（Han et al. 2007；综述于 Josselyn 2018）。关键证据：CREB 过表达 → c-fos+ 比率显著高于邻近未感染神经元。

注：CREB 本身并非决定性因素；真正的决定因素是由 CREB 等上游信号介导的**内在兴奋性**高低。

### 2. 竞争的执行：侧向抑制

赢得竞争的神经元通过 GABA 能中间神经元**抑制周围的"输家"神经元**，强制执行印迹稀疏性。屏蔽这种抑制可使两个时间上相邻的记忆被分配到不重叠（而非重叠）的神经元群——即阻断了本应发生的记忆链接。

### 3. 记忆链接的时间窗（~6 小时）

学习后约 6 小时内，印迹细胞兴奋性高于基线。若第二件事在此窗口内发生：
- 两事件印迹**重叠分配**（co-allocation）→ 两段记忆被大脑关联
若超过此窗口：
- 两事件分配到**不重叠**的神经元群 → 两段记忆保持独立

这一机制可能解释了"同一天发生的事情更容易被一起回忆"的认知现象，以及过度紧张时记忆边界模糊（PTSD 泛化）的潜在机制。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| CREB 过表达神经元优先纳入恐惧记忆印迹 | 侧向杏仁核病毒载体 CREB 过表达 + CFC + c-fos/Arc 成像 | PMID:29709212（PMC9623596）| 高 |
| 人工降低兴奋性将神经元从印迹中排除 | 转基因 Kir2.1（内向整流 K⁺ 通道）降低兴奋性 → Arc 表达率降低 | PMID:29709212（PMC9623596）| 高 |
| 屏蔽 GABA 侧向抑制使时间相邻记忆分离 | GABAergic 抑制阻断剂；记忆链接测试 | PMID:29709212（PMC9623596）| 中 |

## 连接

- [[engram-cells]] — 记忆分配是印迹细胞形成的上游机制
- [[hebbian-learning]] — CREB 竞争是细胞层面的 Hebb 原理：更活跃者被优先强化
- [[ltp]] — 赢得分配的神经元随后经历 L-LTP 突触强化，提高自然检索可及性

## 未解问题

- Q-engram-human-allocation：人类海马中印迹分配是否也遵循 CREB 竞争规则？人类神经元兴奋性是否有同样的 6 小时窗口？

## 修订历史

- 2026-05-31 · 创建 · 基于《记忆的物质形式：印迹细胞》一文 · 初始置信度：高

## 来源文章

- [[2026-05-31-engram-cells-memory-trace]]

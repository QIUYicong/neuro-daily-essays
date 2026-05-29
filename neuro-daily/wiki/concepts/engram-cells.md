---
title: 印迹细胞
slug: engram-cells
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-31
updated: 2026-06-02
revision_count: 2
dimensions: [cellular, brain-region, behavior, cognition]
related: [place-cell, hippocampal-circuit, ltp, hebbian-learning, btsp, nmda-receptor, dendritic-computation, memory-consolidation, sharp-wave-ripples]
prerequisites: [ltp, hebbian-learning, place-cell, hippocampal-circuit]
opens_questions: [Q-engram-overlap-rate, Q-engram-necessity-vs-sufficiency, Q-silent-engram-information-locus, Q-human-engram-evidence]
source_articles: [2026-05-31-engram-cells-optogenetic-proof]
key_sources: ["PMID:31896692", "PMID:22441246", "PMID:26023136", "PMID:26982728", "PMID:23888038"]
---

# 印迹细胞 (Engram Cells)

> **一句话定义**：学习时被激活并因此发生持久物理化学改变的神经元集合；提取时被选择性再激活，从而支持记忆表达；光遗传学证明激活印迹细胞足以重现学习后的行为，即使没有任何外部感觉线索。

## 当前理解

我们现在认为，记忆具有部分细胞定位性——特定的学习经历在大脑中"指定"一批神经元（印迹细胞）作为该记忆的主要细胞载体。Tonegawa 实验室从 2012 年到 2016 年的四个里程碑实验，用光遗传学提供了直接证明。

印迹细胞满足三条认定标准（Josselyn & Tonegawa 2020，PMID:31896692）：
1. 学习时被激活（由即刻早期基因 c-Fos 等标记）
2. 被学习经历物理/化学修饰（突触强度↑、树突棘密度↑）
3. 提取时被再激活（产生记忆表达行为）

**竞争性分配**是印迹形成的核心规则：具有更高内在兴奋性（由 CREB 活性调控）的神经元在学习时优先被激活，因此优先"赢得"印迹席位。这种兴奋性优势维持数小时，为时间接近的经历之间建立记忆联结提供了细胞基础。

**沉默印迹**是一个关键的新概念（Ryan et al. 2015，PMID:26023136）：当记忆在逆行性遗忘或早期阿尔茨海默症后被"遗忘"时，印迹细胞可能仍保留连接拓扑，但因突触权重（AMPA/NMDA 比值、树突棘密度）降低而无法被自然感觉线索激活——这称为沉默印迹。关键发现：用光遗传学直接激活这些沉默印迹细胞，仍能重现记忆行为，证明**遗忘可以是提取障碍而非存储障碍**。

## 关键机制

### 1. 印迹细胞的分配（Allocation）

- **CREB 活性**调控神经元内在兴奋性：CREB ↑ → 兴奋性 ↑ → 学习时更易被激活 → 优先进入印迹
- **标记系统**：c-fos-tTA × TRE-ChR2 系统，由四环素（Dox）控制标记时间窗
- **稀疏性**：海马齿状回（DG）每次仅 ~2–4% 细胞被激活，保证不同记忆的高度正交

### 2. 印迹细胞的结构特征

- **突触强度**：印迹细胞 AMPA/NMDA 电流比值显著高于邻近非印迹细胞
- **树突棘密度**：印迹细胞树突棘密度高于非印迹细胞
- **印迹间优先连接（preferential connectivity）**：DG 印迹细胞 → CA3 印迹细胞 → CA1 印迹细胞 → BLA 印迹细胞，这条跨脑区印迹链的突触连接效率高于随机细胞对

### 3. 印迹的激活与提取

**自然提取**：感觉线索 → 感觉皮层 → 内嗅皮层 → DG 印迹细胞 → 沿印迹间链传播 → BLA → 恐惧/记忆行为表达

**人工激活（光遗传）**：蓝光（470 nm）直接激活 ChR2 标记的印迹细胞 → 跳过感觉线索，直接引发记忆行为

### 4. 沉默印迹机制

蛋白质合成抑制或早期 AD 损害突触增强，使印迹细胞处于沉默状态：
- 连接**拓扑**（谁连着谁）：被保留（DG→CA3 优先连接在遗忘后仍存在）
- 连接**权重**（连接有多强）：降低（AMPA/NMDA 比值减小，树突棘减少）

光遗传激活沉默印迹证明信息仍以某种形式保存。但信息究竟储存在拓扑中还是权重中，目前尚无决定性答案（见未解问题）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 激活 DG 印迹细胞足以重现恐惧记忆 | 光遗传激活 ChR2 标记印迹细胞，无感觉线索下诱导 ~35% 冻结 | PMID:22441246 (PMC3331914) | 高 |
| 人工激活印迹细胞可植入虚假记忆 | A 环境印迹激活 + B 环境电击 → A 环境冻结（无实际电击史） | PMID:23888038（仅摘要）| 高 |
| 遗忘后印迹细胞仍保留记忆信息（沉默印迹）| ANI 遗忘后光遗传激活 DG 印迹 → 冻结水平等同对照组 | PMID:26023136 (PMC5583719) | 高 |
| 早期 AD 记忆丧失为提取障碍 | APP/PS1 小鼠光遗传激活印迹 → LTM 完全恢复 | PMID:26982728 (PMC4847731) | 高 |
| 光学 LTP 可恢复沉默印迹的自然提取能力 | 高频光刺激 AD 印迹细胞 → 树突棘密度恢复 → 自然 LTM 恢复 | PMID:26982728 (PMC4847731) | 高 |
| 印迹细胞 AMPA/NMDA 比值高于非印迹细胞 | 急性脑片膜片钳，SAL 组印迹 vs 非印迹比较 | PMID:26023136 (PMC5583719) | 高 |

## 连接

- [[place-cell]] — 场所细胞是空间情景记忆的印迹细胞候选；CA1 场所细胞参与空间情景记忆印迹
- [[hippocampal-circuit]] — DG→CA3→CA1→BLA 印迹间链利用海马的三突触回路结构
- [[ltp]] — 印迹细胞的突触增强特征与 LTP 机制相同；光学 LTP 可恢复沉默印迹
- [[hebbian-learning]] — 竞争性分配是 Hebb 原理（同步放电→连接强化）的细胞层面实现
- [[btsp]] — BTSP 是场所细胞（一类印迹细胞）快速单次写入的突触机制
- [[nmda-receptor]] — NMDA 受体介导印迹细胞的突触增强（LTP 形式）
- [[dendritic-computation]] — 树突钙平台电位（BTSP 触发器）可能是印迹细胞快速建立突触增强的机制
- [[memory-consolidation]] — SWR 重播可能将海马印迹"复制/转移"至皮层印迹（系统巩固假说）
- [[sharp-wave-ripples]] — SWR 期间印迹细胞以 20 倍速高速重播，推动海马→皮层固化

## 未解问题

- Q-engram-overlap-rate：训练与提取时活跃细胞仅 20–40% 重叠，这是方法学误差、印迹精炼，还是状态依赖提取？
- Q-engram-necessity-vs-sufficiency：印迹细胞的充分性已证，必要性（消融印迹后记忆是否永久消失）尚存疑问
- Q-silent-engram-information-locus：沉默印迹中，信息究竟编码在连接拓扑（谁连着谁）还是连接权重（连接有多强）？
- Q-human-engram-evidence：人类是否存在印迹细胞集合？Quiroga 2005 的"概念细胞"是否是其表现？如何在人类进行实验验证？

## 修订历史

- 2026-05-31 · 创建 · 填补四个页面的高优先级悬空引用（ltp, hebbian-learning, dendritic-computation, place-cell）· 基于《印迹细胞的光子证明》文章 · 初始置信度：高
- 2026-06-02 · 修订 · 基于《记忆的夜间旅行》文章 · [[memory-consolidation]] 页面已建立；系统巩固框架补充：沉默印迹（Roy 2016）可能是被阻断系统巩固（突触权重未随时间恢复）的结果；皮层印迹的建立是系统巩固的细胞层面输出

## 来源文章

- [[2026-05-31-engram-cells-optogenetic-proof]]
- [[2026-06-02-memory-consolidation-systems]]

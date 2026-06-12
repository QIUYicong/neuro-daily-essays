---
title: 注意瞬盲
slug: attentional-blink
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-05-31
updated: 2026-10-04
revision_count: 2
dimensions: [behavior, cognition, whole-brain-network, brain-region]
related: [global-workspace-theory, consciousness-ignition, working-memory, prefrontal-cortex, p3-wave, gamma-oscillations, competition-selection-principle, attention-consciousness-dissociation]
prerequisites: [global-workspace-theory, consciousness-ignition, working-memory]
opens_questions: [Q-ab-01, Q-ab-02, Q-ab-03, Q-ab-04, Q-gwt-01, Q-gwt-02, Q-cogitate-02]
source_articles: [2026-05-31-attentional-blink, 2026-10-04-attention-consciousness-dissociation]
key_sources: ["PMID:7707027", "PMID:15482443", "PMID:16158062", "PMID:16603406", "PMID:29100736", "PMID:34435621", "PMID:36220535", "PMID:40310881", "PMC10784117"]
---

# 注意瞬盲 (Attentional Blink)

> **一句话定义**：在快速视觉呈现（RSVP）流中，成功感知第一目标（T1）后约 200–500ms 内，对第二目标（T2）的有意识知觉率显著下降——尽管感觉皮层已完整处理了 T2（早期 MEG 响应 P1/N1 与「看见」时完全相同），差异仅在约 270ms 处的前额-顶叶点燃是否发生。

## 当前理解

我们现在认为，注意瞬盲揭示了有意识知觉的一个基本时间约束：**意识广播是一个串行、容量为一的过程，每次广播需要约 200–500ms，在此期间新的「广播申请」会被拒绝**。

注意瞬盲的关键实验设计优势在于，它提供了一个近乎完美的有意识/无意识「内部对照」——同一物理刺激，感觉处理相同，仅因时机不同而产生截然不同的意识结果。这正是 COGITATE 2025 等阈上刺激实验无法实现的：在感觉输入严格等同的条件下检验 GWT 的核心预测。

核心机制解释（双阶段瓶颈模型，Chun & Potter 1995, PMID:7707027）：
- 视觉识别分两阶段：Stage 1（并行感觉处理，容量大）→ Stage 2（工作记忆巩固，串行，容量 = 1）
- T1 进入 Stage 2 时，T2 等候于 Stage 1；Stage 1 表征约 200–300ms 后衰减
- T2 若在 T1 的 Stage 2 处理完成前衰减，则永久失去进入意识的机会

全局工作空间理论（GWT）进一步解释（Raffone et al. 2014, PMID:24639586）：
- T1 触发前额顶叶工作空间「点燃」（~200–300ms）
- 工作空间被占据约 200–500ms，期间 T2 的点燃申请被竞争-遴选机制拒绝
- T2 感觉表征在视觉皮层局部存在，但无法触发全局广播——无意识，但有局部表征

**关键神经证据**（Sergent et al. 2005, PMID:16158062，MEG）：
- 0–200ms：成功感知 vs 失败感知 T2 的 P1/N1 完全相同
- ~270ms：强烈分叉——成功感知出现前额-顶叶浪涌，失败感知快速衰减至基线
- 这精确定位了意识的「诞生时刻」，与 GWT 的点燃时序预测吻合

## 关键机制

### Lag-1 Sparing（滞后 1 豁免）

当 T2 紧跟 T1（lag 1，<100ms），T2 通常被感知而非被瞬盲。解释：
- **事件标记合并**：T1 和 T2 被系统视为同一事件单元，共享一次 Stage 2 处理
- **提升与反弹（Boost-and-Bounce）**：T1 引发短暂放大效应，T2 落在「提升」相而非「反弹」相
- **预表征激活**：Alilović et al. 2021（PMID:33497774）发现，T2 的神经预表征动态预测 lag-1 sparing 是否发生

### 全有全无 vs 梯度：核心争议

- Sergent & Dehaene 2004（PMID:15482443）：可见度双峰分布，支持全有全无相变
- Eiserbeck et al. 2022（PMID:34435621）：ERP 梯度连续变化，挑战双峰结论
- 可能调和：全有全无是「中等输入强度」条件下的主要模式；RSVP 边界区域可能有梯度过渡

### 注意瞬盲 vs 掩蔽的神经分离

Noorman et al. 2025（PMID:40310881, eLife，开放全文）：
- 掩蔽：损害约 200–250ms 的特征整合（感觉反馈依赖过程）
- 注意瞬盲：保留特征整合，阻止后续广播过程
- 结论：注意瞬盲作用于感觉处理之后，在「感觉→意识广播」的传递环节

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| T1 后 200–500ms 内 T2 检测率下降 | RSVP 行为实验（多实验室） | 7707027（多次复现） | 高 |
| 感觉处理不受抑制（P1/N1 相同） | MEG 时频分析 | PMID:16158062 | 高 |
| ~270ms 处有意识/无意识神经分叉 | MEG 全脑记录 | PMID:16158062 | 高 |
| 意识可见度双峰分布（全有全无） | 连续量表评分 | PMID:15482443 | 中（Eiserbeck 2022 有争议） |
| ERP（N1/N2/P3）梯度连续随可见度 | ERP 记录 | PMID:34435621 | 中（与双峰结论冲突） |
| VAN 有 P3b 弱 | 高密度 EEG | PMID:36220535 | 中 |
| MTL 单细胞：意识失败时响应延迟减弱 | 人类颅内电极（综述） | PMID:29100736 | 高（单细胞人类数据稀缺）|
| 猕猴有同等时间窗的注意瞬盲 | 猕猴 RSVP 范式 | PMC10784117 | 高 |
| 注意瞬盲 vs 掩蔽神经机制可分 | Kanizsa 图形 + EEG 解码 | PMID:40310881（开放全文） | 高（2025，最新） |

## 连接

- [[global-workspace-theory]] — 注意瞬盲是 GWT 最直接的有/无意识分叉检验场景（COGITATE 无法检验的核心预测）
- [[consciousness-ignition]] — 注意瞬盲的 270ms 神经分叉是点燃机制最干净的时序证据
- [[working-memory]] — Chun & Potter 1995 的 Stage 2 巩固即工作记忆编码
- [[prefrontal-cortex]] — 前额顶叶浪涌（~270ms）是注意瞬盲中有意识知觉的关键神经标志
- [[competition-selection-principle]] — 注意瞬盲是工作空间竞争-遴选最典型的行为体现
- [[attention-consciousness-dissociation]] — 注意瞬盲是"有注意无意识"方向的核心范式之一

## 未解问题

- **Q-ab-01**（高优先级）：注意瞬盲中「无意识 T2 表征」能否产生语义启动效应？能否影响后续决策？
- **Q-ab-02**（中优先级）：冥想训练如何缩短注意瞬盲持续时间？神经机制未明。
- **Q-ab-03**（高优先级）：双阶段模型 vs GWT 广播占据 vs 提升与反弹——哪个机制是真正的瓶颈所在？
- **Q-ab-04**（中优先级）：Lag-1 sparing 是事件标记合并、提升效应，还是两者的混合？
- **Q-gwt-01**（高）：P3b 是意识本身的标志还是报告/决策过程的标志？
- **Q-gwt-02**（高）：前额叶浪涌是点燃的触发器还是报告系统的后果？
- **Q-cogitate-02**（高）：用注意瞬盲范式（有/无意识分叉直接检验），onset ignition 是否更强更稳定？

## 修订历史

- 2026-05-31 · 创建 · 基于《注意瞬盲：当意识成为稀缺资源》(#36) · 初始置信度：高（行为现象高度可靠；神经机制 mainstream；全有全无 vs 梯度争议标记为 contested）
- 2026-10-04 · rev2 · 补充注意-意识双重解离视角：将注意瞬盲明确定位为"有注意无意识"的核心范式，Fu & Rutishauser 2018 MTL单神经元证据已在证据表中，本次更新连接至新建 attention-consciousness-dissociation 页面

## 来源文章

- [[2026-05-31-attentional-blink]]
- [[2026-10-04-attention-consciousness-dissociation]]

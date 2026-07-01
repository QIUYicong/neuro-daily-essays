---
title: 深部小脑核
slug: deep-cerebellar-nuclei
domain: systems
type: structure
status: established
confidence: high
created: 2026-09-04
updated: 2026-10-21
revision_count: 2
dimensions: [cellular, microcircuit, brain-region, cognition, systems]
related: [cerebellum, purkinje-cell, thalamus, motor-cortex, forward-model, perineuronal-nets, inferior-olive, nucleus-accumbens, prefrontal-cortex, cerebellar-ltd, climbing-fiber, granule-cell-cerebellar, cerebellar-memory-transfer]
prerequisites: [purkinje-cell, cerebellum, GABA, thalamus]
opens_questions: [Q-dcn-01, Q-dcn-02, Q-dcn-03, Q-dcn-04, Q-pc-02, Q-pf-03]
source_articles: [2026-09-04-deep-cerebellar-nuclei-dcn-output, 2026-10-21-cerebellar-memory-transfer-task-difficulty]
key_sources: ["PMID:25279763", "PMID:29858484", "PMID:38534469", "PMID:40344058", "PMID:34789878", "PMID:34262527", "PMID:19675244", "PMID:32661395", "PMID:40595477"]
---

# 深部小脑核 (Deep Cerebellar Nuclei, DCN)

> **一句话定义**：小脑的唯一输出核团——三对核团（顶核、间位核、齿状核）以高频自发放电（60–100+ Hz）接受浦肯野细胞的强力 GABA 抑制，通过"PC 沉默即命令"的去抑制逻辑将精密的运动时序信号转化为丘脑-皮层-脑干可读懂的兴奋性指令，同时参与饱腹感调控和认知功能。

## 当前理解

我们现在认为，深部小脑核（DCN）远不只是被动的信号中转站：它是一台主动的多层计算节点，通过去抑制（disinhibition）、反弹放电（rebound excitation）和三层突触/内在可塑性机制，将小脑皮层的时序计算高保真地翻译成丘脑和脑干系统的激活信号。

**核心计算逻辑**：浦肯野细胞以约 60–80 Hz 持续发放 GABA 信号，将 DCN 谷氨酸能神经元"压制"在高频自发放电之下。当学习发生，PC 在特定运动时序窗口内停止放电（精确"暂停"），DCN 神经元因此脱离抑制，以精确的时序激发——这个信号通过上小脑脚传至对侧丘脑，进而驱动运动皮层完成预测性运动调整。

**关键认知框架更新**（相比旧观点）：
- 旧观点：DCN 是 PC 抑制的简单反转器
- 新认识：DCN 是主动的多层可塑性中枢，且参与运动以外的食欲调控、认知和社会行为
- **2026-10-21 新增**：DCN 也是"两级记忆转移"的目的地——按任务难度决定的比例，从小脑皮层转移来的运动记忆最终可能就沉淀在 DCN（或前庭核）的这三层可塑性机制里（Bae et al. 2025, PMID:40595477）。详见 [[cerebellar-memory-transfer]]。

## 解剖组织

### 三个核团（内→外）

| 核团 | 输入来源 | 主要投射目标 | 核心功能 |
|------|---------|------------|---------|
| 顶核（Fastigial Nucleus）| 小脑蚓部 PC | 同侧前庭核、延髓网状（谷Glu：对侧脑干；Gly：同侧前庭/网状）| 平衡、姿势、眼球运动、自主神经；aDCN 参与饱腹感 |
| 间位核（Interpositus）| 中间区 PC | 对侧红核（rubrospinal）、对侧 VL 丘脑 | 肢体运动时序协调；眼睑条件反射（前间位核/AIN）|
| 齿状核（Dentate Nucleus）| 外侧半球 PC（crus I/II）| 对侧 VL/VPLo 丘脑 → 运动/前运动皮层；非运动丘脑 → 前额叶 | 运动规划与启动；认知、语言、执行功能 |

### 三类投射神经元

1. **大型谷氨酸能投射神经元**（约 75–80%）
   - 自发放电：60–100+ Hz（脑中最高之一）
   - 被脑中密度**最高**的围神经元网（PNN）包裹
   - 投射：丘脑（VL/VPLo）、红核、脑干运动区、脊髓
   - 是运动输出的主体；病理激活驱动肌张力障碍（Wu 2025）

2. **GABA 能投射神经元**（小型，主要间位核/齿状核）
   - 投射：同侧**下橄榄核**（IO）
   - 功能：构成 Guillain-Mollaret 三角的抑制臂，门控攀爬纤维信号精度

3. **甘氨酸能投射神经元**（主要顶核，Bagnall et al. 2009）
   - 投射：**同侧**前庭核和延髓网状结构
   - 与谷氨酸能神经元的对侧投射形成互补通道，协同控制 VOR 和姿势

## 关键机制

### 机制一：去抑制（Disinhibition）——主要输出机制

PC 精确暂停 → GABA 释放减少 → DCN 谷氨酸能神经元脱笼激活

**证据**：Ishikawa et al. 2014（灵长类）：DN 神经元爆发与 PC 暂停同步（无反弹延迟），论文明确结论"PC 抑制的减少是产生 DN 输出的主要机制"（PMID:25279763）。

### 机制二：反弹放电（Rebound Excitation）——辅助增益机制

强超极化（来自 PC 爆发放电）→ 激活 HCN（Ih）和 T 型 Ca²+ 通道去失活 → 抑制解除后爆发

**证据**：在体外切片和部分在体情境中可直接测量（Patriarchi 2021, PMID:34194302）；PNN 移除后反弹幅度增加（138%→168%，Bhatt 2018）。反弹在节律性运动和 IO 振荡相关情境中更重要。

### 机制三：三层可塑性（以眼睑条件反射为范式）

**层 1 — 突触 LTP（MF→DCN）**：苔藓纤维→间位核突触在 PC 超极化的"解锁窗口"内发生 LTP，增强驱动力

**层 2 — 内在兴奋性变化**：训练后 AHP 减小、IA-like K+ 电流下调 → AIN 神经元更易触发，降低点火阈值

**层 3 — PNN 门控**：围神经元网调控 PC→DCN 的 GABA 释放效率和反弹放电幅度，决定学习窗口开放度
- ChABC 移除 PNN → mIPSC 频率 31.7→48.5 Hz（↑53%）；EBC CR率 51.1%→72.6%（Bhatt 2018）

### 机制四：长环路（前向预测）vs 短环路（误差门控）

**长环路**：DCN 谷氨酸能 → VL 丘脑 → 运动皮层 → 脑桥核 → 苔藓纤维 → 小脑皮层/DCN  
→ 实现前向模型（forward model），DCN 输出能预测 200ms 后运动状态（Miyata 2021）

**短环路**（Guillain-Mollaret 三角）：DCN GABA 能 → 下橄榄核 → 攀爬纤维 → 小脑皮层  
→ 负反馈稳定器：DCN 越活跃，对下一轮 CF 误差信号的抑制越强

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| 去抑制是 DCN 主要输出机制 | 灵长类在体双记录（PC + DN），主动运动任务 | PMID:25279763 | 中-高 |
| DCN 谷氨酸能神经元驱动肌张力障碍 | 光遗传学细胞类型特异性激活/消融，两种小鼠模型 | PMID:40344058 | 中-高 |
| PNN 限制 DCN 可塑性速率 | ChABC 注射 + 在体 EBC 行为（CR率51→73%）+ 电生理 | PMID:29858484 | 高 |
| 顶核含甘氨酸能投射神经元（同侧前庭）| GlyT2-EGFP 转基因 + 解剖追踪 | PMID:19675244 | 高 |
| aDCN→VTA 调控饱腹感 | 钙成像+光遗传+GRAB-DA传感器；人类PWS fMRI | PMID:34789878 | 中（单实验室） |
| 外侧 DCN→VM 丘脑→mPFC 调控社会行为 | 光遗传+化学遗传，自闭症小鼠模型 | PMID:32661395 | 中 |
| DCN 预测 200ms 后运动状态 | 系统辨识研究（Kakei et al.，转引于综述） | PMID:34262527 | 中（间接） |

## 连接

- [[purkinje-cell]] — DCN 的主要抑制性输入源
- [[cerebellum]] — DCN 是小脑计算的输出接口
- [[thalamus]] — VL/VPLo 丘脑是 DCN 到运动皮层的中继
- [[motor-cortex]] — 接受来自 VL 丘脑的 DCN 信号
- [[inferior-olive]] — 接受 DCN GABA 能反馈（短环路）
- [[forward-model]] — DCN 是前向预测模型的神经基础
- [[perineuronal-nets]] — 包裹 DCN 大型谷氨酸能神经元，门控可塑性
- [[nucleus-accumbens]] — aDCN→VTA→纹状体的饱腹感通路
- [[prefrontal-cortex]] — 齿状核→非运动丘脑→前额叶的认知通路
- [[cerebellar-memory-transfer]] — DCN 三层可塑性是承接从皮层转移来的记忆的具体候选载体；任务难度决定转移比例

## 未解问题

- Q-dcn-01：去抑制 vs 反弹放电的精确相对贡献，以及在不同核团/任务/物种中是否系统性不同
- Q-dcn-02：PNN 消化能否用于脑卒中康复中增强运动学习（DCN 水平干预）
- Q-dcn-03：外侧 DCN 的奖励 CF 信号（rPE）如何改变齿状核突触权重
- Q-dcn-04：aDCN 饱腹信号是否双向调控？如何整合内脏感觉与运动预测
- Q-pc-02（延伸）：PC 停顿 vs 爆发在 DCN 层面如何被"读出"？促进型/抑制型 PC 亚型是否有解剖分离的 DCN 靶向？
- Q-pf-03（关联，高优先级）：若将任务难度正规化原则（Bae 2025）应用于眼睑条件反射范式，DCN 内具体是哪类突触/哪种可塑性机制承接转移的记忆？目前仍缺乏直接分子证据。

## 修订历史

- 2026-09-04 · 创建 · 基于《深部小脑核的计算秘密》文章 #134 · 初始置信度：高（解剖/基本回路）、中（非运动功能）
- 2026-10-21 · 修订 rev1→rev2 · 基于《记忆搬家的经济学：任务难度如何决定运动学习记忆留在小脑皮层还是搬进深部小脑核》（文章 #189）· 新增：当前理解段补充"两级记忆转移目的地"视角；连接新增cerebellar-memory-transfer；未解问题新增Q-pf-03；新增key_sources：PMID:40595477

## 来源文章

- [[2026-09-04-deep-cerebellar-nuclei-dcn-output]]
- [[2026-10-21-cerebellar-memory-transfer-task-difficulty]]

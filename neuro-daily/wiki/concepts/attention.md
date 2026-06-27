---
title: 注意力
slug: attention
domain: concepts
type: concept
status: established
confidence: high
created: 2026-06-28
updated: 2026-06-27
revision_count: 2
dimensions: [microcircuit, brain-region, whole-brain-network, cognition, behavior]
related: [dorsal-attention-network, alpha-oscillations, thalamic-reticular-nucleus, lateral-geniculate-nucleus, working-memory, predictive-coding, biased-competition, consciousness-ignition, normalization-model, global-workspace-theory, attentional-blink, transformer-self-attention, blindsight, attention-consciousness-dissociation]
prerequisites: [thalamocortical-circuit, thalamic-reticular-nucleus, alpha-oscillations, dorsal-attention-network]
opens_questions: [Q-attention-01, Q-attention-02, Q-attention-03]
source_articles: [2026-06-28-attention-neural-mechanisms-spotlight, 2026-06-27-blindsight-attention-consciousness-dissociation]
key_sources: ["PMID:11994752", "PMID:18849967", "PMC2888515", "PMID:19186161", "PMC6725538", "PMID:21119777", "PMC6772495", "PMID:11584308"]
---

# 注意力 (Attention)

> **一句话定义**：注意力是大脑对有限感觉处理资源的主动分配机制，通过三级联动系统实现——前额叶/顶叶网络（DAN）设定目标，丘脑网状核（TRN）在皮层前 4ms 执行门控，α 振荡持续维持无关区域的抑制——其计算本质是规范化竞争中的乘法性增益调制。

## 当前理解

我们现在认为，注意力不是单一的神经机制，而是一个**三级联动的门控系统**，在多个时间和空间尺度上协同工作：

**第一级（高级认知层）**：背侧注意网络（DAN）由额叶眼区（FEF）和顶内沟（IPS）构成，在视觉刺激出现之前就已预期性激活，将行为目标转化为感觉皮层的增益状态偏置。腹侧注意网络（VAN，右 TPJ + IFC）负责检测意外事件并打断目标导向的任务执行——两者形成互补的目标驱动/显著性驱动双系统（Corbetta & Shulman 2002）。

**第二级（皮层前门控）**：丘脑网状核（TRN）作为感觉信号进入皮层前的第一道主动过滤器，其效应先于 LGN（外侧膝状体）约 4ms（McAlonan et al. 2008）。PFC 通过大型驱动型端钮直接"命令"TRN 调整各感觉通道的门控状态，使注意的选择性在感觉信号到达初级皮层之前就已经开始。

**第三级（皮层节律维持）**：α 振荡（8–13 Hz）通过功率升高在被忽略的皮层区域主动施加周期性抑制，在数十至数百毫秒内持续维持差异化的感觉门控状态（Jensen & Mazaheri 2010）。这不是被动的"大脑空闲"，而是主动的"通过抑制门控"。

在计算层面，规范化模型（Reynolds & Heeger 2009）提供了统一的数学框架：注意力 = 对目标输入的感觉增益乘数，其效果形式（对比度增益 vs 反应增益）取决于注意聚光灯大小与感受野大小的相对比例。这解释了为何不同实验室在不同条件下观察到表面矛盾的注意力效应。

## 关键机制

### 1. DAN/VAN 双网络系统

**背侧注意网络（DAN，目标驱动）**：
- FEF（额叶眼区，BA8）+ IPS/LIP（顶内沟/外侧顶叶内区）
- 预期性激活（刺激前即已激活），双侧分布
- 通过乘法性增益调制（~50–100% 调谐曲线幅度放大）提升目标感觉信号
- 投射路径：FEF→V4→V1（皮层反馈）+ FEF→TRN→LGN（丘脑门控）

**腹侧注意网络（VAN，显著性驱动）**：
- 右侧颞顶联合区（TPJ）+ 腹侧额叶皮层（VFC/IFG）
- 响应意外/显著事件，右侧偏侧化
- DAN 执行任务时 VAN 被抑制；VAN 检测到意外时打断 DAN（双向互调节）

### 2. TRN 皮层前门控（关键时序证据）

McAlonan et al. (2008, Nature) 在猕猴 LGN + TRN 同时记录：

```
注意力信号从 PFC/FEF 下达
     │
     ↓ 大型驱动型端钮（直接命令）
   TRN 放电降低（效应潜伏期 ~22ms）
     │
     ↓ TRN→LGN 的 GABA 抑制减弱（"解门控"）
   LGN 放电增强 20–30%（潜伏期 ~26ms）
     │
     ↓ 增强的视觉信号传递到 V1
   注意力增益在皮层前即已实现
```

**关键数据**：TRN 效应（22ms）先于 LGN 效应（26ms）约 4ms，提供了注意力皮层前门控的因果时序证据。

注意：这一 20–30% 的增益数字与 Alitto et al. (2025) 报告的 ~1% 存在矛盾（已登记为 C-2026-09-15-01），可能反映任务设计和采样策略的差异——TRN 先于 LGN 4ms 的时序本身无争议。

### 3. α 振荡：通过抑制门控

Jensen & Mazaheri (2010) 的"gating by inhibition"框架：

- **α 功率升高** = 大脑主动对某皮层区域施加周期性抑制（每个 ~100ms α 周期中，约 50–70ms 处于"抑制窗口"）
- **α 功率降低** = 该区域去抑制，进入持续高兴奋性
- **预期性**：α 偏侧化在目标出现前就已建立（自顶向下驱动）
- **跨模态一致**：视觉/听觉/触觉注意任务中被忽略侧皮层均出现 α 升高

α 波峰 = 抑制最强（γ 活动最少）；α 波谷 = 短暂兴奋窗口（允许 γ 和信息处理）。

α 振荡与 TRN 的关系：α 节律可能部分由 TRN-TC 振荡回路产生（TC 细胞的 T 型钙通道 → TRN-TC 反馈振荡 → 约 10 Hz 共振），但皮层内部（L5）也独立产生 α——两者对注意力的协同机制仍未完全明确。

### 4. 规范化模型：计算层描述

Reynolds & Heeger (2009) 的规范化框架：

```
神经元响应 = (驱动输入 × 注意力增益) / (规范化池 + 饱和常数)
```

- **规范化池** = 局部区域神经元总活动的加权平均
- **注意力效应** = 驱动输入的乘法性增益 S（Stimulus drive gain）
- **效果形式取决于聚光灯/感受野比例**：
  - 注意聚光灯 < 感受野 → **对比度增益**（对比度-响应曲线左移）
  - 注意聚光灯 > 感受野 → **反应增益**（曲线幅度整体增加）

这解释了为何不同实验室报告不同形式的注意力效应：他们使用了不同大小的刺激和注意条件，落入了规范化曲线的不同区间。

### 5. γ 同步与通信效率

Engel, Fries & Singer (2001) 的"通过相干通信"（CTC）假说：
- 注意力增强目标神经元群与高级区域之间的 γ 频段同步
- 同步神经集群的输出比不同步神经集群更能有效驱动下游神经元
- γ 同步增强（信号增益）+ α 抑制（背景压制）共同塑造注意选择

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| DAN（FEF+IPS）控制目标驱动空间注意 | fMRI 综述 + 空间忽视病变分析 | PMID:11994752（摘要） | 高 |
| TRN 注意效应先于 LGN 约 4ms | 猕猴 LGN/TRN 同时记录（n=29 TRN，n=多数 LGN）| PMID:18849967 (PMC2888515) | 高（时序因果） |
| LGN 注意增益约 20–30% | 猕猴单单元电生理，目标 vs 忽略比较 | PMID:18849967 (PMC2888515) | 中（与 Alitto 2025 矛盾） |
| 规范化模型统一对比度增益与反应增益 | 多实验室 V4/MT/V1 数据定量拟合 | PMID:19186161 (PMC6725538) | 高（现象学） |
| 被忽略侧皮层 α 预期性升高 | EEG，视觉/听觉/触觉注意任务 | PMID:21119777 (PMC6772495) | 高 |
| α 功率高时感觉响应弱、检测率低 | EEG + 行为阈值测量 | PMID:21119777 (PMC6772495) | 高 |
| α 门控具有预期性（刺激前已建立） | EEG，注意提示后 α 偏侧化提前 | PMID:21119777 (PMC6772495) | 高 |

## 连接

- [[dorsal-attention-network]] — DAN（FEF/IPS）是注意力第一级控制层，设定目标和预期
- [[alpha-oscillations]] — α 振荡是注意力第三级维持机制，通过抑制实现持续差异化门控
- [[thalamic-reticular-nucleus]] — TRN 是注意力第二级皮层前门控节点，先于 LGN 4ms 实现选择性过滤
- [[lateral-geniculate-nucleus]] — 注意力门控的直接执行对象，放电增益在 TRN 解门控后提高
- [[working-memory]] — 工作记忆维持注意任务目标模板（DAN 的 Query 信号来源）
- [[predictive-coding]] — 注意力 = 感觉精度上调（DAN 是精度加权的硬件实现）
- [[biased-competition]] — 注意通过偏置竞争（偏侧 α 抑制 + DAN 乘法增益）实现赢者通吃
- [[normalization-model]] — 规范化模型提供注意力计算的统一定量框架（悬空，待填页）
- [[consciousness-ignition]] — 注意与意识的精确边界：前者不必然引发后者（待填）
- [[global-workspace-theory]] — 注意力是全局广播（GWT 点燃）的前提条件
- [[attentional-blink]] — 注意瞬盲揭示注意资源的时间容量约束（~270ms 时间瓶颈）
- [[transformer-self-attention]] — Transformer 自注意力机制与 DAN/规范化竞争的计算类比

## 未解问题

- **Q-attention-01（高优先级）**：α 振荡对注意选择的因果作用是否得到充分证明？目前多为相关性证据；TMS/光遗传直接操控 α 功率后注意选择如何变化？（α 的因果角色有待直接干预实验）
- **Q-attention-02（高优先级）**：人类 TRN 的注意门控是否与猕猴等价？人类颅内电生理中是否有直接证据显示 TRN 效应先于皮层激活？目前仅有猕猴单单元记录（McAlonan 2008），人类直接证据缺失。
- **Q-attention-03（中优先级）**：注意与意识的精确分离条件是什么？无意识注意（意识阈下的注意偏置）是否需要 TRN/DAN 的全面参与，还是可以在较低层级实现（如 TRN 门控无需皮层反馈就能工作）？

## 修订历史

- 2026-06-28 · 创建 · 基于《注意力的神经机制：三级联动门控系统如何在皮层前就开始选择世界》（#178）· 综合 McAlonan 2008（TRN 门控时序）、Reynolds & Heeger 2009（规范化模型）、Jensen & Mazaheri 2010（α 振荡抑制门控）、Corbetta & Shulman 2002（DAN/VAN 双系统）· 初始置信度：高（系统层），中（机制层个别细节）

## 来源文章

- [[2026-06-28-attention-neural-mechanisms-spotlight]]

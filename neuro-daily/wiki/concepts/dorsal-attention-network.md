---
title: 背侧注意网络（DAN）
slug: dorsal-attention-network
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-01
updated: 2026-09-25
revision_count: 5
dimensions: [brain-region, whole-brain-network, cognition, behavior]
related: [working-memory, prefrontal-cortex, v1-primary-visual-cortex, thalamus, thalamocortical-circuit, biased-competition, attentional-blink, global-workspace-theory, predictive-coding, alpha-oscillations, gamma-oscillations, communication-through-coherence, dlpfc-rule-encoding, ventral-attention-network, interhemispheric-competition, spatial-neglect]
prerequisites: [prefrontal-cortex, v1-primary-visual-cortex, thalamus]
opens_questions: [Q-dan-01, Q-dan-02, Q-dan-03, Q-ctc-01, Q-alpha-01]
source_articles: [2026-07-01-dorsal-attention-network-FEF-IPS, 2026-07-21-alpha-oscillations-attentional-gating, 2026-08-31-fef-v4-gamma-coherence-ctc, 2026-09-23-ventral-attention-network-reorienting, 2026-09-25-interhemispheric-competition-corpus-callosum]
key_sources: ["PMID:11994752", "PMID:20192813", "PMID:13679398", "PMID:36730414", "PMID:10376597", "PMID:42125965", "PMID:19478185", "PMID:22325208", "PMID:18466742", "PMID:21692662", "PMID:23516306", "PMID:20053897"]
---

# 背侧注意网络（Dorsal Attention Network, DAN）

> **一句话定义**：由额叶眼区（FEF）和顶内沟（IPS/LIP）构成的目标驱动注意控制系统，通过LIP优先级地图整合信号，经V4→V1皮层反馈和FEF→TRN丘脑通路，对感觉皮层施加**乘法性增益调制**，实现空间注意的自上而下控制。

## 当前理解

我们现在认为，空间注意的神经控制由两套解剖上分离的网络共同实现（Corbetta & Shulman 2002, PMID:11994752）：

**背侧注意网络（DAN）**
- 核心节点：**额叶眼区（FEF, BA8）** + **顶内沟（IPS）及顶上小叶（SPL）**
- 功能特征：**目标驱动**（goal-directed）的自上而下注意控制
- 时序特征：在视觉刺激出现之**前**即已激活（预期性激活），是注意的主动预部署机制
- 两侧半球对称分布

**腹侧注意网络（VAN）**  
- 核心节点：右侧颞顶联合区（TPJ）+ 腹侧额叶皮层（VFC/IFG）
- 功能特征：**显著性驱动**（stimulus-driven）的意外刺激定向响应
- 明显右侧偏侧化

DAN 的核心操作逻辑是：将当前行为目标（"我需要找蓝色目标"）转化为感觉皮层的**增益状态变化**，在视觉刺激到达之前就预先放大特定视野区的神经处理能力。

## 关键机制

### 优先级地图（LIP/IPS）
顶内沟中的外侧顶叶内区（LIP）充当**优先级地图**（Bisley & Goldberg 2010, PMID:20192813）：
- 整合视觉信号、扫视计划信号和认知目标信号（三类信号可线性叠加）
- 活动峰值（population peak）反映行为优先级最高的位置
- 指导后续注意部署和眼动目标选择，两者共享同一地图

### FEF 的因果控制
FEF 微电刺激实验（Moore & Fallah 2004, PMID:13679398）证明：
- 次发放阈值（sub-saccadic）FEF 刺激因果性提高对应视野区目标的检测灵敏度（d' 提升）
- 效果严格视网膜拓扑性（只在 FEF 运动场对应位置有效）
- 等效于消除该位置的竞争干扰物

### V4→V1 皮层反馈增益调制
注意的感觉皮层效应通过皮层间反馈传递（Debes & Dragoi 2023, PMID:36730414）：
- 选择性消除 V4→V1 的反馈投射 → V1 注意调制效应完全消失
- 前馈感觉响应（V1 的基础视觉处理）保持正常
- 反馈末梢集中在 V1 浅层（L2/3），符合皮层间反馈终止规律

### 乘法性增益调制
注意产生的是**乘法增益**而非加法偏移（Treue & Martínez Trujillo 1999, PMID:10376597）：
- 调谐曲线幅度整体放大（~50-100%），但形状（偏好方向、调谐宽度）不变
- 保持感知特异性，同时提高信号清晰度
- 这使注意提高信号对比度而不引入感知畸变

### TRN 门控接口
FEF/IPS 也投射到视丘网状核（TRN），通过皮层-视丘回路传递注意信号（Halassa & Kastner 2017, PMID:29275841）：
- FEF → TRN → 视丘核（LGN/枕核等）→ 感觉皮层
- 与皮层直接反馈通路（FEF→V4→V1）并行，提供更大范围的感觉门控

### α 振荡控制：DAN 对感觉皮层 α 侧向化的指挥
**新增（2026-07-21）**：DAN 实施注意控制不仅通过增益调制，也通过控制感觉皮层 α 振荡（8–13 Hz）来抑制非目标区域（van Schouwenburg et al. 2017, PMID:28174529）：
- FEF-IPS 之间的 **α 频段相干性**（10 Hz coherence）是将注意控制信号传递到感觉皮层的振荡载体
- 结果：**目标区域感觉皮层 α 降低**（去抑制，信号畅通）；**非目标区域感觉皮层 α 升高**（主动压制，信号截断）
- 这套机制**先于**刺激出现（预期性），是 DAN 预先设置感觉皮层过滤状态的机制
- 与乘法性增益调制（V4→V1 反馈）并行，两者可能服务于不同感知任务类型（增益 vs 抑制选择性）
- 见 [[alpha-oscillations]] 页面中的完整机制描述

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| DAN（FEF+IPS）控制目标驱动注意 | fMRI 系统综述 + 空间忽视病变分析 | Corbetta & Shulman 2002, PMID:11994752 | 高 |
| LIP 是整合多信号的优先级地图 | 猕猴 LIP 单单元记录 + 药理失活 | Bisley & Goldberg 2010, PMID:20192813 | 高 |
| FEF 次发放阈值刺激因果增强对应视野注意 | 猕猴 FEF 微电刺激 + 视觉检测任务 | Moore & Fallah 2004, PMID:13679398 | 高 |
| V4→V1 反馈是 V1 注意调制的必要通道 | 猕猴 AAV 反馈末梢标记 + 光遗传抑制 | Debes & Dragoi 2023, PMID:36730414 | 高（需重复）|
| 注意通过乘法增益调制 MT 神经元 | 猕猴 MT 方向调谐曲线测量 | Treue & Trujillo 1999, PMID:10376597 | 高 |
| 人类 fMRI 确认 FEF/IPS 在空间注意中的角色 | 人类 fMRI + Posner 线索任务 | Chen et al. 2026, PMID:42125965 | 中-高 |

## 连接

- [[prefrontal-cortex]] — FEF（BA8）是 PFC 的注意控制子区域
- [[working-memory]] — DAN 与 dlPFC 工作记忆共享注意资源调配功能
- [[v1-primary-visual-cortex]] — DAN 通过 V4→V1 反馈产生乘法增益调制
- [[thalamus]] — FEF/IPS → TRN 通路实现皮层注意信号的视丘门控
- [[thalamocortical-circuit]] — TRN 是 DAN 信号传递到感觉门控的接口
- [[biased-competition]] — DAN 是偏置竞争模型的神经回路实现
- [[attentional-blink]] — 注意瞬盲反映 DAN 广播的时间容量约束
- [[global-workspace-theory]] — DAN 为 GWT 的广播机制提供空间选择基础
- [[predictive-coding]] — 注意 = 感觉精度的主动上调（DAN 是精度加权的硬件）
- [[alpha-oscillations]] — DAN 通过 FEF-IPS α 相干性指挥感觉皮层 α 侧向化，实现感觉门控

## 未解问题

- Q-dan-01：FEF→V4 皮层通路 vs FEF→TRN 丘脑通路的相对速度和贡献比较
- Q-dan-02：人类 FEF 与猕猴 FEF 的精确功能同源性
- Q-dan-03：DAN 是否调控全局警觉状态，还是只负责局部位置注意
- Q-thalamus-burst-awake：清醒视丘爆发放电与 DAN 注意转移的关系（已登记）

## FEF 的 γ 通信机制（新增 2026-08-31）

DAN 不只通过乘法增益和 α 抑制实施注意控制，还通过 **FEF-V4 γ 频段相干性**建立动态通信通道：

**Gregoriou et al. 2009（PMID:19478185，PMC2849291，开放全文）关键数据**：
- 注意期间 FEF-V4 γ coherence（50–90 Hz）升高 **26–37%**（空间特异性）
- FEF 注意调制时间（80 ms）早于 V4（130 ms），Granger 因果确认 FEF→V4 方向
- 维持期 V4→FEF 反馈增强，形成双向维持环路

**细胞类型分离（Gregoriou et al. 2012，PMID:22325208，PMC3297082）**：
- FEF **视觉神经元**（L2/3）→ V4：γ coupling（注意通路）
- FEF **运动神经元**（L5/6）→ SC/脑干：无 γ coupling，注意期 β 升高（眼跳准备通路）
- 注意与眼跳在 FEF 内部完全解离（细胞类型 + 皮层层级）

**与 CTC 框架整合**：这些发现是 Fries 2015 CTC（Communication Through Coherence，PMID:26447583）框架的核心实验基础。CTC 统一解释了：
- γ coherence（FEF-V4）= 前馈通信窗口打开（被注意刺激）
- α 升高（非目标枕叶）= 竞争通信窗口关闭
- β 同步（PFC-顶叶）= top-down 预期/注意信号的反馈载体

见 [[communication-through-coherence]] 页面完整框架。

## DAN-VAN 的动态对话（新增 2026-09-23）

DAN 并不是孤立运作的——它与腹侧注意网络（VAN，右侧 TPJ+VFC）通过相互抑制和断路器机制形成动态平衡（Corbetta et al. 2008，**PMID:18466742**）：

**正常专注任务（DAN 主导）**：
- DAN（FEF+IPS）激活，控制感觉皮层的注意聚焦
- **VAN 被 DAN 主动抑制**（而非被动不活跃）——防止任务执行被无关刺激打断
- fMRI 中两者呈负相关：DAN BOLD 信号高 ↔ VAN BOLD 信号低于基线

**意外显著刺激出现（VAN 断路）**：
- 右侧 TPJ 激活（~150-200 ms），P3a ERP 成分出现
- VAN 作为"断路器"：中断 DAN 当前注意聚焦
- DAN 重配置（~200-350 ms）：将资源重定向至新刺激
- 重定向完成后，VAN 再次被抑制

**临床意义**：右侧 VAN 损坏（卒中）不只影响 VAN 本身，还破坏 DAN 的连接性，导致左侧半侧空间忽视——注意被锁定在右侧视野，即使主动尝试也无法持续向左注意。

见 [[腹侧注意网络]] 页面完整描述。

## 修订历史

- 2026-07-01 · 创建 · 基于《空间注意的神经回路》一文 · 来源：Corbetta & Shulman 2002, Bisley & Goldberg 2010, Moore & Fallah 2004, Debes & Dragoi 2023, Treue & Trujillo 1999 · 初始置信度：高
- 2026-07-21 · 修订 rev2 · 新增"α 振荡控制"机制节：FEF-IPS α 相干性作为 DAN 控制感觉皮层 α 侧向化的振荡载体；更新 related 字段加入 alpha-oscillations · 来源：van Schouwenburg et al. 2017, PMID:28174529
- 2026-08-31 · 修订 rev3 · 新增"FEF 的 γ 通信机制"节：FEF-V4 γ coherence 升高 26–37%（Gregoriou 2009 开放全文）；FEF 细胞类型解离（Gregoriou 2012 开放全文）；整合 CTC 框架；related 新增 gamma-oscillations, communication-through-coherence, dlpfc-rule-encoding；opens_questions 新增 Q-ctc-01, Q-alpha-01；key_sources 新增 PMID:19478185, PMID:22325208
- 2026-09-23 · 修订 rev4 · 新增"DAN-VAN 动态对话"节：断路器模型详述（Corbetta et al. 2008，PMID:18466742，开放全文）；正常专注时 VAN 被主动抑制；意外刺激触发 VAN 断路并重定向；空间忽视的网络破坏机制；related 新增 ventral-attention-network；key_sources 新增 PMID:18466742, PMID:21692662
- 2026-09-25 · 修订 rev5 · 基于《半球间竞争》（#155）文章 · related 新增 interhemispheric-competition, spatial-neglect；key_sources 新增 PMID:23516306, PMID:20053897（左 FEF/IPS 较右侧有更强的对侧偏向信号；右 SPL1 的独特调制功能）

## 来源文章

- [[2026-07-01-dorsal-attention-network-FEF-IPS]]
- [[2026-07-21-alpha-oscillations-attentional-gating]]
- [[2026-08-31-fef-v4-gamma-coherence-ctc]]
- [[2026-09-25-interhemispheric-competition-corpus-callosum]]

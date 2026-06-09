---
title: α 振荡（Alpha Oscillations）
slug: alpha-oscillations
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-21
updated: 2026-08-31
revision_count: 2
dimensions: [whole-brain-network, brain-region, cognition, cellular, behavior]
related: [dorsal-attention-network, gamma-oscillations, beta-oscillations, theta-oscillations, working-memory, biased-competition, thalamus, thalamocortical-circuit, pv-interneurons, ei-balance, attentional-blink, multisensory-integration, predictive-coding, communication-through-coherence]
prerequisites: [action-potential, synaptic-transmission, pv-interneurons, thalamus]
opens_questions: [Q-alpha-01, Q-alpha-02, Q-alpha-03]
source_articles: [2026-07-21-alpha-oscillations-attentional-gating, 2026-08-31-fef-v4-gamma-coherence-ctc]
key_sources: ["PMID:10704517", "PMID:21119777", "PMID:20573914", "PMID:18093905", "PMID:21779269", "PMID:23141428", "PMID:26447583"]
---

# α 振荡 (Alpha Oscillations, 8–13 Hz)

> **一句话定义**：人类清醒脑电中功率最强的神经振荡，通过对皮层区域施加有节律的脉冲抑制（每 ~100 ms 一次 GABA 能超极化），主动压制非目标感觉区域的信息传递，是注意力选择性过滤的神经执行机制，而非"皮层闲置"的标志。

## 当前理解

我们现在认为，α 振荡（8–13 Hz，个体峰值频率 IAF 因人而异）是大脑注意力调控的**主动抑制工具**，而非早期（1929-1990s）认为的被动皮层休眠标志。

**核心框架**：Jensen & Mazaheri 2010（PMID:21119777）提出"Gating by Inhibition"（以抑制为门的脉冲架构）：

- 大脑路由信息的方式是**主动抑制任务无关区域**而非增强目标区域
- α 振荡通过 ~100 ms 节律性 GABA 能超极化实现**脉冲抑制**（pulsed inhibition）
- α 功率（power）调控 duty-cycle：功率越高，抑制相持续时间越长，神经元可用于信号传递的时间窗口越短
- **α 高区 = 功能性去耦合（任务无关）；α 低区 = 去抑制（任务相关）**

**空间注意的 α 侧向化**（Worden et al. 2000, PMID:10704517）：
- 注意左视野 → 右侧枕叶 α 降低（目标区域去抑制），左侧枕叶 α 升高（干扰区域主动抑制）
- 侧向化具有视网膜拓扑特异性
- 在视觉刺激出现**之前**就已建立（预期性布防）

**因果证据**（Romei et al. 2008, 2010）：
- 预刺激枕叶 α 功率反向预测 TMS 光幻视成功率：α 低 → 皮层易激发；α 高 → 皮层抑制中
- 节律性 TMS（rhTMS）以 10 Hz 施加于枕顶叶，频率特异性诱导对侧视野探测下降，确立因果地位

**跨感觉普遍性**（Foxe & Snyder 2011, PMID:21779269）：
- 视觉 α（枕叶）、触觉 μ（感觉运动皮层，8–14 Hz）、听觉注意 α 均遵循相同原则
- 跨模态注意（如专注听觉时）可触发视觉皮层预期性 α 升高（在视觉刺激到来前关闭视觉门）

## 关键机制

### 脉冲抑制（Pulsed Inhibition）模型
α 振荡不是持续静态抑制，而是有节律的开关：
- **α 波谷相（trough）**：神经元接近/超过阈值，可传递短暂信息
- **α 波峰相（peak）**：GABA 能超极化，传入突触前输入不能有效引发动作电位
- **Duty-cycle 调控**：α 功率升高 → 抑制相占更大时间比例 → 可处理窗口缩小 → 感知压制增强

### α 生理基础
- **GABA 能中间神经元**：皮层 GABA 网络（与 γ 共享，但时间常数更慢）
- **丘脑-皮层回路**：TRN（丘脑网状核）的 CaV3.x T 型低电压激活钙通道产生约 10 Hz 节律爆发；通过丘皮层回路影响皮层 α；与睡眠纺锤波（12-15 Hz）共享丘脑发生机制
- **皮层层级**：infragranular 层（V/VI 层）是皮层 α 的主要起搏器，通过向浅层传递抑制影响感觉信号处理

### α 与 γ 的互补对立
| 特征 | α（8–13 Hz） | γ（30–80 Hz） |
|------|-------------|--------------|
| 功能 | 主动抑制/门关 | 主动处理/门开 |
| 空间 | 非目标/干扰区域 | 目标/任务相关区域 |
| 注意效应 | 升高（干扰侧）/ 降低（目标侧） | 升高（目标侧） |

### 上游控制：DAN → α → 感知选择
1. FEF + IPS（背侧注意网络）编码当前任务目标
2. FEF-IPS 通过 α 频段皮层间相干性（coherence）传递注意控制信号
3. 感觉皮层按指令调整 α 侧向化（van Schouwenburg et al. 2017, PMID:28174529）
4. 目标区域去抑制 → γ 升高 → 信息传递；非目标区域抑制增强 → γ 受压 → 信号截断

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 注意任务中对侧被忽略位置枕叶 α 升高 | EEG 高密度记录，空间注意线索任务 | PMID:10704517 | 高 |
| 预刺激 α 预测 TMS 光幻视成功率 | 同时 EEG+TMS，光幻视探测 | PMID:18093905 | 高 |
| rhTMS 10Hz 因果性诱导视野特异性探测下降 | rhTMS（5/10/20Hz 对照）+ 视觉探测 | PMID:20573914 | 高 |
| 跨感觉 α 抑制（视觉/触觉/听觉） | 综合多实验室多任务证据 | PMID:21779269 | 高（综述） |
| FEF-IPS α 相干性调控枕叶 α 侧向化 | tACS + EEG + 注意偏向行为 | PMID:28174529 | 中-高 |
| 预刺激 α 升高预测注意失误 | MEG Go/NoGo，错误试次分析 | PMID:19308934 | 中-高 |

## 连接

- [[背侧注意网络]] — α 的上游控制者：FEF-IPS 指挥感觉皮层 α 侧向化
- [[γ 振荡]] — 互补角色：α 高/γ 低（抑制）vs α 低/γ 高（处理）
- [[丘脑]] / [[丘皮层回路]] — α 的部分起搏器：TRN T 型钙通道节律性爆发
- [[工作记忆]] — α 在工作记忆中压制干扰信息；β 主导维持
- [[多感觉整合]] — 时间绑定窗口（TBW）受 α 时间采样机制影响
- [[预测编码]] — α 预期性侧向化是预测编码中"主动预期过滤"的底层实现

## 未解问题

- **Q-alpha-01**（高优先级）：FEF 激活如何通过何种解剖通路（直接皮层反馈 vs 丘脑中继）精确调控特定视网膜拓扑位置的枕叶 α？
- **Q-alpha-02**（中优先级）：个体 IAF 差异（8–13 Hz）是否与注意效率指标（d'、RT 变异性）系统性相关？高 IAF 是否提供更精细的时间门控？
- **Q-alpha-03**（中优先级）：清醒时 α 门控（感觉过滤）与睡眠时丘脑纺锤波（记忆保护）是否共享相同的 TRN 硬件，但通过不同的神经调质状态（NE/ACh 高 vs 低）切换功能？

## α 在 CTC 框架中的角色（新增 2026-08-31）

在 Fries 2015 的 Communication Through Coherence（CTC）框架（PMID:26447583，PMC4605134）中，α 振荡是大脑路由系统的**关闭门**：

**CTC 视角下的 α 功能**：
- γ（30–90 Hz）= 通信窗口**打开**（被注意区域，前馈）
- α/β（8–30 Hz）= 通信窗口**关闭**（非目标区域，反馈抑制）
- 两者互补协同，共同实现选择性信息路由

**FEF-V4 γ coupling 与 α 抑制的协同**（Gregoriou et al. 2009，PMID:19478185）：
- FEF 向被注意位置的 V4 发出 γ coherence 信号（打开通信），同时
- FEF/IPS 向非目标视觉皮层发出 α/β 信号，使非目标区域 α 升高（关闭竞争通信）
- 这一双向机制共同实现了偏置竞争（biased competition）的物理路由

**对 Q-alpha-01 的部分回答**：CTC 框架提供了一个框架性答案——FEF 向非目标区域枕叶发送反馈投射，这些反馈在 α/β 频段传递（皮层深层 L5/6 → 非颗粒层反馈通路），使目标 α 降低、非目标 α 升高。但 FEF 的反馈是通过**直接皮层回路**还是**丘脑 TRN 中继**还有争议（Q-alpha-01 未完全解决）。

## 修订历史

- 2026-07-21 · 创建 · 基于《大脑的频闪滤网》第89篇文章 · 初始置信度：高（10个来源，9个开放全文，包含 rhTMS 因果证据）
- 2026-08-31 · 修订 rev2 · 新增"α 在 CTC 框架中的角色"节：将 α 抑制整合进 Fries CTC 框架；说明 FEF-V4 γ coupling 与 α 抑制的协同机制；related 新增 communication-through-coherence；key_sources 新增 PMID:26447583；Q-alpha-01 部分回答进展

## 来源文章

- [[2026-07-21-alpha-oscillations-attentional-gating]]
- [[2026-08-31-fef-v4-gamma-coherence-ctc]]

---
title: 规范微回路（新皮层）
slug: cortical-canonical-microcircuit
domain: circuits
type: structure
status: established
confidence: high
created: 2026-07-18
updated: 2026-07-18
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, whole-brain-network, cognition]
related: [cortical-layers, predictive-coding, thalamocortical-circuit, pv-interneurons, sst-interneurons, vip-interneurons, disinhibitory-circuit, stdp, ltp, hebbian-learning, gamma-oscillations, beta-oscillations, attractor-network]
prerequisites: [action-potential, synaptic-transmission, nmda-receptor, cortical-layers, thalamocortical-circuit]
opens_questions: [Q-ccm-01, Q-ccm-02, Q-ccm-03, Q-ccm-04]
source_articles: [2026-07-18-cortical-canonical-microcircuit]
key_sources: ["PMID:15217339", "PMID:23177956", "PMID:25622573", "PMID:23273272", "PMID:25556836"]
---

# 规范微回路（新皮层）(Cortical Canonical Microcircuit)

> **一句话定义**：新皮层高度保守的六层连接模式，以 L4（接受丘脑感觉输入）→ L2/3（前馈误差输出，γ 频）→ L5/6（预测生成与皮层下输出，β 频）→ L6（丘脑反馈门控）为主轴，配合 PV+/SST+/VIP+ 三类中间神经元的动态调控，在每个皮层砖上实现预测-比较-误差-更新的贝叶斯感知计算。

## 当前理解

我们现在认为，规范微回路是哺乳动物新皮层中高度保守的基本计算单元——同一套六层连接逻辑在视觉、听觉、体感、运动、语言皮层中反复出现，Harris & Shepherd（2015，PMID:25622573）将此称为"串联同源性"（serial homology）。不同皮层区域的功能差异来自（a）各自连接到不同的感觉输入和效应器，（b）在皮层层级中所处的层级位置，以及（c）L4 在联合皮层中的退化程度——而非根本不同的电路设计。

**核心发现**（Douglas & Martin 2004，PMID:15217339）：皮层内部循环兴奋性突触约为丘脑驱动输入的 4–7 倍，说明皮层不是被动转录感觉信号的机器，而是基于内部模型主动进行推断的计算引擎。

**与预测编码的对应**（Bastos et al. 2012，PMID:23177956）：规范微回路的六层结构在物理上实现了预测编码所有必要的计算节点：L2/3 是误差单元（前馈，γ 频）；L5/6 是预测单元（反馈，β 频）；L4 是感觉输入汇聚点；L1 是反馈预测的接受区（L5 顶端树突丛所在）；L6 是丘脑反馈门控。

## 关键机制

### 层级连接模式

```
       ↓ 丘脑感觉输入（驱动型）
┌────────────────────────────────────────────────┐
│  L4（棘突星形细胞：接受丘脑输入，分发给 L2/3）     │
│   ↓ 兴奋性投射                                  │
│  L2/3（误差单元：水平整合，前馈输出，γ 频）        │
│   ↓ 兴奋性（前馈到高级区域 L4）+ 反馈到 L4, L5    │
│  L5（预测/输出单元：整合底层感觉+顶端反馈，远程输出） │
│   ↓ 兴奋性投射                                  │
│  L6（皮质-丘脑反馈：调控丘脑增益）                 │
│   ↓ 反馈（β 频）                                │
└──────────────── → 丘脑 ─────────────────────────┘
   L1（接受高级区域 L5/6 的反馈终末轴突）
```

### 前馈 vs 反馈连接的解剖不对称

| 特性 | 前馈 Feedforward | 反馈 Feedback |
|------|-----------------|--------------|
| 起源层 | L2/3（浅层） | L5/6（深层） |
| 终止层 | 高级区域 **L4**（驱动型） | 低级区域 **L1, L2/3**（调制型，绕过 L4）|
| 振荡频率 | **γ（60-80 Hz）** | **β（14-18 Hz）** |
| 计算角色 | 传递预测误差 | 传递先验预测 |

（Markov et al. 2014，PMID:23983048；Bastos et al. 2015，PMID:25556836）

### L5 锥体细胞的两极整合（Larkum 2013，PMID:23273272）

L5 厚毛绒锥体细胞是规范微回路中最复杂的计算节点：

- **基底/近端树突**（~L4-5）：接受 L4 感觉输入（实际发生了什么）
- **顶端树突丛**（~L1）：接受高级区域的反馈预测（预期发生什么）
- **AND 门逻辑**：两极同步激活 → 顶端钙爆发（Ca²⁺ dendritic spike） → 高频爆发放电

```
底层感觉（基底） AND 高层预测（顶端）→ 爆发放电（确认匹配）
仅底层感觉（无反馈）→ 温和单个动作电位
仅高层预测（无感觉）→ 同样温和
```

### 中间神经元的调控层

| 类型 | 突触靶点 | 功能 |
|------|---------|------|
| **PV+**（快速放电） | 胞体/轴突始段 | 时间精度控制；产生 **γ 振荡**；竞争性选择 |
| **SST+**（马氏细胞） | 顶端树突 | 抑制顶端树突钙爆发；关闭"自上而下之门" |
| **VIP+**（双极细胞） | SST+ 中间神经元 | **去抑制（disinhibition）**：VIP+→抑制 SST+→释放顶端树突 |

**VIP+ 去抑制回路**是注意力在细胞层面的实现机制：注意/奖励/新奇信号激活 VIP+ → 抑制 SST+ → 顶端树突整合增强 → L5 更容易爆发（确认预测-实际匹配）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 皮层内循环兴奋约为丘脑输入的 4-7 倍 | 猫 V1 突触计数 + 定量连接模型 | PMID:15217339 | 高 |
| 六层规范微回路跨区域保守（串联同源性）| 多区域解剖学 + 基因表达 + 电生理综述 | PMID:25622573 | 高 |
| 前馈终止 L4（驱动型），反馈绕过 L4 至 L1/2/3（调制型）| 29区域定量逆行追踪 | PMID:23983048 | 高 |
| L2/3 在感觉运动失配时强烈响应（误差单元）| 清醒小鼠 V1 双光子钙成像 + VR | PMID:22681686 | 高 |
| 前馈 γ，反馈 β（28 对视觉区域）| 猴子 MEG + LFP Granger 因果分析 | PMID:25556836 | 高 |
| L5 顶端树突钙爆发（AND 门逻辑）| 体外切片树突全细胞记录 + 2P 成像 | PMID:23273272 | 中（体外高，体内尚争议）|

## 连接

- [[cortical-layers]] — 六层结构的解剖学详细描述（L1-L6 各层细胞类型、投射、发育）
- [[predictive-coding]] — 规范微回路的计算描述；L2/3=误差单元，L5/6=预测单元
- [[thalamocortical-circuit]] — L4（丘脑→皮层驱动型输入）和 L6（皮层→丘脑反馈门控）的双向连接
- [[pv-interneurons]] — PV+ 快速放电细胞：γ 振荡产生器，胞体级时间控制
- [[sst-interneurons]] — SST+ 马氏细胞：顶端树突门控，控制反馈整合
- [[vip-interneurons]] — VIP+ 双极细胞：去抑制回路，注意/奖励信号的细胞级实现
- [[disinhibitory-circuit]] — VIP→SST→锥体细胞的去抑制回路
- [[stdp]] — STDP 在 L2/3 和 L5 突触中发生，塑造规范微回路的连接权重
- [[gamma-oscillations]] — γ 振荡由 L2/3 的 PV+ E-I 回路产生；承载前馈误差信号
- [[beta-oscillations]] — β 振荡起源于深层（L5/6）；承载反馈预测信号
- [[attractor-network]] — L5/6 的预测状态可用吸引子动力学描述

## 未解问题

- Q-ccm-01（高优先级）：L2/3 误差单元和 L5/6 预测单元能否在同一体内实验中被直接、同时区分？（预测编码最核心的实验空白）
- Q-ccm-02（高优先级）：L5 顶端钙爆发在行为动物注意任务中的触发频率和触发条件是什么？体内光遗传学验证？
- Q-ccm-03（中优先级）：β/γ 频率规律是否普遍适用于非视觉皮层（前额叶、海马、运动皮层）？
- Q-ccm-04（中优先级）：无颗粒皮层（前额叶）的规范微回路是什么样的"变体"——L2/3 是否兼并了 L4 的功能？

## 修订历史

- 2026-07-18 · 创建 · 基于《大脑皮层的规范微回路》文章 #86 · 初始置信度：高（解剖学部分 established；预测编码实现层面 mainstream）

## 来源文章

- [[2026-07-18-cortical-canonical-microcircuit]]

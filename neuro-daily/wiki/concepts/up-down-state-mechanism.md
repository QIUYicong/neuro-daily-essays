---
title: 皮层 UP/DOWN 态机制
slug: up-down-state-mechanism
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-23
updated: 2026-07-23
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region]
related: [cortical-slow-oscillation, sleep-spindles, so-spindle-swr-coupling, action-potential, voltage-gated-sodium-channel, synaptic-transmission, pv-interneurons]
prerequisites: [action-potential, synaptic-transmission, membrane-potential]
opens_questions: [Q-updown-termination-weight, Q-updown-human-mechanism]
source_articles: [2026-07-23-cortical-up-down-state-pfc-gating-memory]
key_sources: ["PMID:8340806", "PMID:8340807", "PMID:11017176", "PMID:26834569"]
---

# 皮层 UP/DOWN 态机制 (Cortical UP/DOWN State Mechanism)

> **一句话定义**：皮层慢振荡中由 Layer 5 循环兴奋自主发起的双态交替——UP 态（约 −65 mV，0.8–1.5 s，神经元放电）由钠激活钾通道（KNa）积累 + 突触抑郁 + SST+ 延迟抑制联合终止为 DOWN 态（约 −90 mV，~1 s，神经元静默）；是不依赖视丘输入的皮层内在动力学。

## 当前理解

我们现在认为，皮层 UP/DOWN 态是**皮层回路的内在属性**，不依赖外部驱动（视丘、海马或感觉输入）：Sanchez-Vives & McCormick（2000，PMID:11017176）在孤立皮层切片中复现了 UP/DOWN 态交替；Steriade 等人（1993，PMID:8340807）证明视丘大范围损毁后体内 SO 仍存在。

UP/DOWN 态机制是理解皮层自主时序的基础：皮层在睡眠时不是"关机"，而是通过离子通道动力学（KNa 积累）和突触可塑性（突触抑郁）维持了一个**精确的内在节律计时器**，为 SO-纺锤波-SWR 三重协奏提供时间骨架。

## 关键机制

### 1. UP 态启动：Layer 5 循环兴奋

**Layer 5（第五层）锥体细胞**是 UP 态的启动引擎，通过**循环兴奋（recurrent excitation）**发起：

```
Layer 5 锥体细胞 A（自发低频放电）
      ↓ AMPA + NMDA（兴奋性突触侧支）
Layer 5 锥体细胞 B、C、D...
      ↓ 水平连接放大
Layer 2/3 锥体细胞
      ↓ 反馈投射
Layer 5 → 维持 UP 态（自维持兴奋环）
```

**为什么 NREM 睡眠时容易发生**：
- 清醒时：高 ACh（基底前脑） → M1 受体激活 → K+ 电导增大 → 静息电位约 −70 mV（远离阈值）
- 睡眠时：ACh 下降 60–80% → M1 脱活化 → K+ 电导减小 → 静息电位约 −65 mV（距阈值仅 10 mV）→ 极低的自发激活即可启动 UP 态

UP 态特征（Steriade 1993，PMID:8340806）：
- 膜电位：约 −65 mV（去极化，接近动作电位阈值 ~−55 mV）
- 持续时间：0.8–1.5 秒
- 放电：密集的动作电位序列

### 2. UP 态终止：三种并联机制

**机制 1：钠激活钾通道（KNa，KCNT1/KCNT2）积累（主要机制）**
- UP 态持续放电 → Na+ 持续内流（经电压门控钠通道 + AMPA 受体）
- 胞内 [Na+] 从 ~10 mM 上升至 ~15–20 mM
- KNa 通道被 [Na+] 激活 → 大量 K+ 外流 → 深度超极化 → DOWN 态
- 功能意义：KNa 是一个**自动计时器**——UP 态越长，Na+ 积累越多，终止越快

**机制 2：突触抑郁（短时程突触抑郁，STP）**
- 兴奋性突触的高频激活耗尽突触前快速可用囊泡池（RRP）
- 谷氨酸释放概率下降 → AMPA 激活减弱
- 循环兴奋回路增益降低 → 无法维持 UP 态 → 自然崩溃

**机制 3：SST+ 中间神经元延迟抑制**
- 枝形细胞（Martinotti cells，SST+）兴奋阈值高，UP 态早期相对静默
- UP 态持续一段时间后，SST+ 开始大量放电
- 向锥体细胞树突施以 GABA_A 介导的抑制 → 削减增益 → 加速 UP→DOWN 转变

**三种机制的相对权重**：在不同皮层区域、物种和深度麻醉 vs 自然睡眠状态下可能不同（见 Q-updown-termination-weight）。

### 3. DOWN 态：深度超极化与充能

DOWN 态特征（Steriade 1993，PMID:8340806）：
- 膜电位：约 −90 mV（深度超极化，远低于正常静息电位）
- 持续时间：约 0.5–1 秒
- 放电：几乎完全静默

DOWN 态深度的维持来自：
- GABA_B 受体介导的慢 K+ 通道激活（抑制性终末的 GABA 激活）
- KNa 通道持续激活（Na+ 清除需时间）
- TASK 家族漏电 K+ 通道（TASK-1、TASK-3）

**DOWN 态的功能意义**：
- 视丘网状核（TRN）CaV3.3 T 型钙通道完成**去失活（deinactivation）**（需要 < −75 mV 维持约 50 ms），为下次纺锤波充能
- 皮层突触抑郁恢复（RRP 再充填）
- 背景噪音清零，防止记忆间干扰
- SHY 假说认为 DOWN 态驱动突触稳态下调（约 18%，de Vivo 2017，PMID:28154076）

### 4. 振荡频率与参数

| 参数 | 数值 | 来源 |
|------|------|------|
| UP 态持续时间 | 0.8–1.5 s | Steriade 1993（PMID:8340806）|
| DOWN 态持续时间 | ~0.5–1 s | Steriade 1993（PMID:8340806）|
| 振荡频率（麻醉） | 0.3–0.4 Hz | Steriade 1993（PMID:8340806）|
| 振荡频率（自然睡眠） | 0.6–1 Hz | 估算/综述（PMID:26834569）|
| UP 态膜电位 | ~−65 mV | Steriade 1993（PMID:8340806）|
| DOWN 态膜电位 | ~−90 mV | Steriade 1993（PMID:8340806）|
| 胞内 [Na+] 变化 | ~10→15–20 mM | 模型推算（综述 PMID:26834569）|

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| SO 视丘损毁后存在 → 皮层自主 | 猫体内视丘损毁 + 皮层胞内记录 | PMID:8340807 (PMC6576520) | 高 |
| UP 态 0.8–1.5 s，DOWN ~1 s，~0.3 Hz | 猫皮层 N=254 神经元胞内记录 | PMID:8340806 (PMC6576541) | 高 |
| 离体皮层切片自发 SO（回路内在充分） | 雪貂皮层切片 + 多电极记录 | PMID:11017176 | 高 |
| Layer 5 是 UP 态启动层 | 皮层切片层析 + 局部场电位 | PMID:11017176 | 高 |
| KNa 通道参与 UP 态终止 | 皮层切片 + KNa 阻断剂实验（综述引用） | PMID:26834569 | 中-高 |
| SST+ 中间神经元延迟抑制参与终止 | 综述推断 + 间接光遗传证据 | PMID:26834569 | 中 |

## 连接

- [[cortical-slow-oscillation]] — UP/DOWN 态是 SO 的细胞实现；本页为 SO 的机制子页面
- [[sleep-spindles]] — DOWN 态为 TRN T 型通道去失活充能 → UP 态触发纺锤波
- [[so-spindle-swr-coupling]] — UP/DOWN 态交替是三重协奏的最顶层时间框架
- [[action-potential]] — UP 态中密集动作电位是兴奋的传播载体
- [[synaptic-transmission]] — 突触抑郁（短时程抑郁）是 UP 态终止的主要机制之一
- [[pv-interneurons]] — PV+ 快放电中间神经元参与 UP 态内的 E/I 平衡，SST+ 中间神经元参与 UP 态终止
- [[shy-hypothesis]] — DOWN 态驱动突触稳态下调（SHY 假说的核心执行单元）

## 未解问题

- **Q-updown-termination-weight（中优先级）**：KNa 积累、突触抑郁和 SST 延迟抑制在 UP 态终止中的相对权重是否在不同皮层区域（前额 vs 初级感觉皮层）和不同物种（大鼠 vs 人类）中显著不同？能否通过双光子 Na+ 成像直接测量 UP 态终止时的胞内 Na+ 动力学？
- **Q-updown-human-mechanism（低优先级）**：人类皮层（厚达 2.5–5 mm，更长层内回路）的 UP 态终止机制是否与大鼠/猫有定量差异？目前缺乏人类体内单细胞记录。

## 修订历史

- 2026-07-23 · 创建 · 基于《皮层的沉默与苏醒》文章(#91) · 填补 `cortical-slow-oscillation` 的细胞机制深层 · 来源：Steriade 1993（两篇 PMC）、Sanchez-Vives 2000、Neske 2015（PMC）· 初始置信度：高

## 来源文章

- [[2026-07-23-cortical-up-down-state-pfc-gating-memory]]

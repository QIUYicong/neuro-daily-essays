---
title: 持续内向电流
slug: persistent-inward-currents
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-10-08
updated: 2026-10-08
revision_count: 1
dimensions: [molecular, cellular, microcircuit, disease]
related: [alpha-motor-neuron, size-principle, motor-unit, neuromodulator-systems, spinal-cord-cpg, t-type-calcium-channels, action-potential]
prerequisites: [alpha-motor-neuron, ion-channels, action-potential, neuromodulator-systems]
opens_questions: [Q-pic-01, Q-pic-02, Q-pic-03]
source_articles: [2026-10-08-alpha-motor-neuron-size-principle]
key_sources: ["PMID:18381974", "PMID:31799904", "PMID:20462789", "PMID:19783207"]
---

# 持续内向电流 (Persistent Inward Currents, PICs)

> **一句话定义**：α运动神经元树突远端的 CaV1.3 L型 Ca²⁺ 通道和 Nav1.6 Na⁺ 通道产生的自维持内向电流，在单胺能驱动下将突触输入放大 2–6 倍，产生高原电位和双稳态，是运动神经元"增益调节器"的分子基础。

## 当前理解

我们现在认为，PICs 是理解运动输出为何远比简单"命令强度的线性复制"更复杂的关键机制（Heckman et al. 2008, PMID:18381974, PMC3326417；Binder et al. 2020, PMID:31799904, PMC7132324）。

**最关键的定量事实**：
- 无单胺能输入时，最大离子型突触驱动只能产生 **<30–40% 的最大运动输出**
- 中等单胺能驱动：PICs 产生 **2–4 倍**放大
- 高单胺能驱动：PICs 产生 **5–6 倍**放大

这意味着超过 60% 的最大肌肉力量依赖 PICs，而 PICs 依赖清醒/觉醒状态——运动能力与意识状态存在深层分子耦合。

**双稳态（bistability）**：PICs 在激活和去激活之间存在 10–20 mV 的滞后（hysteresis）。一旦膜电位进入激活范围，PICs 会维持去极化，即使突触输入暂时减弱：一次短暂的兴奋性输入可以"扳动"神经元进入持续放电的高原态（plateau state）；一次短暂的抑制性输入才能关闭它。

**病理意义**：
- **脊髓损伤（SCI）急性期**：单胺能驱动消失 → PICs 消失 → 弛缓性麻痹
- **SCI 慢性期**：5-HT₂ 受体发生组成型活跃（无配体也自发激活）→ PICs 过度上调 → 痉挛
- **ALS**：FF 型 α-MN（最大树突表面积，最高 PIC 密度）在 ALS 中优先退化（ElBasiouny et al. 2010, PMID:20462789, PMC3000632）

## 关键机制

### 分子成分

| 通道 | 类型 | 活化阈值 | 主要特征 |
|------|------|---------|--------|
| CaV1.3 | L型电压门控 Ca²⁺ | 相对较低（比 CaV1.2 低约 10–20 mV） | 主要 PIC 成分，激活慢（~50 ms）但极持久，有 warm-up 效应 |
| CaV1.2 | L型电压门控 Ca²⁺ | 较高 | 次要成分，与 CaV1.3 互补 |
| Nav1.6 | 持续性 Na⁺ | 阈下电位附近 | 快速激活，较缓慢失活；与 CaV1.3 互补 |

CaV1.3 的短 C 端变体（CaV1.3S）激活阈值更低，可能是脊髓运动神经元中的关键变体（Binder et al. 2020）。

### 空间位置

PICs 通道主要分布在**树突远端**（而非轴突始段动作电位发起处），恰好是皮层脊髓束和感觉传入突触的主要接触位置。这意味着 PICs 在接收突触信号的原位进行放大，而不是在信号传到轴突始段之后。

### 单胺能调制

```
5-HT（来自中缝大核 NRM）
    → 5-HT₂ 受体（Gq 耦联，可能是 2a/2b/2c 亚型）
    → PLC → IP₃ → PKC
    → 增强 CaV1.3 活性 → PICs 幅度上调

NE（来自蓝斑 LC）
    → α₁ 肾上腺素受体（Gq 耦联）
    → 类似 PLC 级联
    → 增强 CaV1.3 活性 → PICs 幅度上调

5-HT₁A（可能的拮抗调制）
    → Gi 耦联 → 抑制 PICs（方向相反）
```

两种单胺的效果强度类似（各约 5 倍增益），可以协同叠加（Heckman et al. 2009, PMID:19783207, PMC7312725）。

### delta-F 技术（人类 PIC 的间接测量）

由于人类 α-MN 不能进行细胞内记录，PICs 在人类中通过"delta-F"技术间接测量：
- 对比两个运动单元的放电率变化（配对单元方法）
- 利用 PIC 产生的放电加速（onset）和减速（offset）不对称性估计 PIC 幅度的代理指标
- 局限：受同一运动神经元池内抑制性突触活动干扰；表面 EMG 分解精度有限（Mesquita et al. 2024, PMID:39196985）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| PICs 放大突触输入 2–6 倍（依赖单胺能驱动） | 猫体内三角肌 α-MN 电压钳 + 单胺能药物操控 | PMID:18381974, PMC3326417 | 高 |
| 无单胺能时最大 I/O <30–40% 最大输出 | 单胺能耗竭动物 vs 完整对照比较 | PMID:18381974 | 高 |
| CaV1.3 是主要 Ca²⁺ 通道 | CaV1.3 KO 减少高原电位 | PMID:31799904, PMC7132324 | 高 |
| PICs 主要位于树突远端 | 局部药物注射（树突远端 vs 近端）+ 钙成像 | PMID:18381974, PMC3326417 | 高 |
| SCI 慢性期 5-HT₂R 组成型活跃 | 逆向激动剂（inverse agonist）改善 SCI 痉挛 | PMID:20462789, PMC3000632 | 高 |
| PICs 激活/去激活存在 10–20 mV 滞后 | 慢斜坡电流注射的放电开始 vs 结束电流比较 | PMID:18381974 | 高 |

## 连接

- [[alpha-motor-neuron]] — PICs 是 α-MN 内在非线性计算能力的分子基础
- [[size-principle]] — PICs 与大小原则协同，共同塑造运动单元的输出增益
- [[neuromodulator-systems]] — 5-HT（中缝）和 NE（蓝斑）是 PICs 的主要调制者
- [[t-type-calcium-channels]] — T型 Ca²⁺ 通道是不同类型的低阈值 Ca²⁺ 通道（相关但不同）
- [[parkinsons-disease]] — PD 中黑质多巴胺缺失可能通过下行网状脊髓束间接影响 PICs

## 未解问题

- Q-pic-01（高）：5-HT₂ 受体的具体亚型（2a/2b/2c）在人类脊髓 α-MN 上的功能区分
- Q-pic-02（中）：delta-F 技术的精度限制——能否发展出更直接的人类 PIC 测量方法
- Q-pic-03（中）：PICs 在正常生理运动中是否常规产生双稳态，还是主要作为增益调节器而非开关

## 修订历史

- 2026-10-08 · 创建 · 基于《最终公共通路》（#168）· 包含 ElBasiouny 2010 的 SCI/ALS 临床视角 · 初始置信度：高

## 来源文章

- [[2026-10-08-alpha-motor-neuron-size-principle]]

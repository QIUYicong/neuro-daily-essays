---
title: 沉默突触
slug: silent-synapse
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-05
updated: 2026-09-05
revision_count: 1
dimensions: [molecular, synaptic, cellular, microcircuit]
related: [ampa-receptor, nmda-receptor, ltp, psd-95, critical-period, ocular-dominance-columns, synaptic-transmission, hebbian-learning]
prerequisites: [nmda-receptor, ampa-receptor, synaptic-transmission, ltp]
opens_questions: [Q-ss-01, Q-ss-02]
source_articles: [2026-09-05-odp-stage2-hebbian-vs-homeostatic]
key_sources: ["PMID:26015564", "PMID:32765222", "PMID:30586380", "PMID:33649238"]
---

# 沉默突触 (Silent Synapse)

> **一句话定义**：谷氨酸能突触的一种未成熟形态，突触后膜只含 NMDA 受体（NMDAR）而缺乏 AMPA 受体（AMPAR）；在静息膜电位下 NMDAR 被 Mg²⁺ 阻塞，对常规突触前输入无电流响应（"沉默"），但一旦突触后充分去极化+突触前释放谷氨酸，则可通过 Hebbian LTP 被"开锁"（unsilenced）——AMPAR 插入突触后膜，突触永久激活。

## 当前理解

我们现在认为，沉默突触是神经发育关键期的核心分子底物。在关键期早期，皮层中存在大量沉默突触（AMPA/NMDA 比值 ~0.3–0.5）；感觉经验驱动 Hebbian LTP，逐渐将这些突触"开锁"，AMPA/NMDA 比值升至 ~1–2。关键期关闭，在结构性刹车（PNN/Lynx1）之外，还有一个底物耗竭机制：当沉默突触池耗尽，Hebbian LTP 失去可操作的底物，关键期可塑性自然停止。

**沉默突触的功能定义**：在正常突触前活动（单个刺激）下，突触后无或极小 AMPAR 电流（EPSC），但可以测到 NMDAR 电流（在去极化持钳电压 +40 mV 下）。AMPA/NMDA 电流比值接近 0 是"沉默"的操作指标。

## 关键机制

### 1. 结构基础

- 突触后致密体（PSD）仅含 NMDAR（主要 GluN1/GluN2B 组合）
- AMPAR 完全缺失或密度极低（<1 个 per PSD）
- PSD 支架蛋白 PSD-95 尚未到位或尚未将 GluA1-AMPAR 锚定于突触

### 2. 静默的原因：Mg²⁺ 阻塞

- 静息膜电位（~-65 mV）下，NMDAR 通道被 Mg²⁺ 电压依赖性阻塞
- 单个突触前动作电位释放谷氨酸 → 谷氨酸激活 NMDAR，但 Mg²⁺ 阻塞通道 → 无 Ca²⁺ 流入 → 无突触后电流
- 从突触前记录仍可见正常的谷氨酸释放；"沉默"是突触后电沉默，而非传递沉默

### 3. 开锁（Unsilencing）机制

1. **突触后充分去极化**（来自其他输入的 EPSP 总和，或高频突触前爆发）→ Mg²⁺ 解除阻塞
2. **同时突触前释放谷氨酸**（Hebbian 时序要求）→ NMDAR 打开 → Ca²⁺ 大量流入
3. **Ca²⁺ → CaMKII 激活** → GluA1（S831）磷酸化 → GluA1-AMPAR 外侧扩散至突触 + PSD-95 锚定
4. AMPAR 稳定插入 → AMPA/NMDA 比值升高 → 突触"开锁"（不再沉默）
5. 反复激活 → 更多 AMPAR 稳定 → LTP 长期维持

### 4. PSD-95 的核心作用

- PSD-95（突触后致密体-95，SAP90 家族）是将 GluA1-AMPAR 锚定于突触 PSD 的关键支架
- **PSD-95 KO**：AMPAR 无法被稳定插入 → 沉默突触不能被开锁 → 关键期无限延长（Huang et al. 2015，PMID:26015564）
- **PSD-93（paralogue）**：对 PSD-95 有竞争性抑制，防止过早开锁 → PSD-93 KO：关键期提前关闭（Favaro et al. 2018，PMID:30586380）
- PSD-95 和 PSD-93 的动态竞争精细调控沉默突触开锁速率，从而设定关键期时间轴

### 5. 关键期关闭的"底物耗竭"机制

随着视觉经验驱动的 Hebbian LTP，沉默突触池逐渐被耗尽（AMPA/NMDA 比值全面升高）。当无沉默突触可用时：
- Hebbian LTP 不再有"可开锁的底物"
- 可塑性底物耗竭 → 关键期关闭的内在逻辑

这一机制**与 PNN/Lynx1 的结构性关闭机制独立但协同**：结构性刹车防止过度激活，底物耗竭从内在限制了可塑性的继续。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 关键期早期大量 AMPA-silent 突触（AMPA/NMDA ~0.3） | 双电压钳 + mEPSC + AMPA/NMDA 比值测量 | PMID:32765222（综述） | 高 |
| PSD-95 KO 使关键期无限延长 | PSD-95 KO + ODP 时间轴（P90+）| PMID:26015564 | 高 |
| PSD-93 KO 使关键期提前关闭 | PSD-93 KO + ODP 时间轴 | PMID:30586380 | 高 |
| PSD-95 loss 保留成年期幼年型树突棘动力学 | 双光子 in vivo 成像 + PSD-95 KO | PMID:33649238 | 中-高 |
| MD 后 V1 AMPA/NMDA 比值升高（LTP 指标）；PSD-95 KO 减弱 | 单突触电生理 | PMID:32765222 | 中-高 |

## 连接

- [[nmda-receptor]] — 沉默突触的唯一功能性受体；NMDAR 的 Mg²⁺ 阻塞是"沉默"的机制基础
- [[ampa-receptor]] — 沉默突触开锁 = AMPAR（GluA1）插入突触；PSD-95 依赖
- [[ltp]] — 开锁过程分子机制与 LTP 完全重叠（CaMKII → GluA1 磷酸化 → AMPAR 插入）
- [[psd-95]] — 将 AMPAR 锚定于突触 PSD；PSD-95 KO 阻止开锁
- [[critical-period]] — 沉默突触是关键期 Hebbian 可塑性的底物；耗竭是关键期关闭的内在机制
- [[ocular-dominance-columns]] — ODP 第二阶段（开放眼增强）的突触底物；AMPA/NMDA 比值上升是第二阶段 LTP 的电生理标志
- [[hebbian-learning]] — 开锁遵循 Hebb 规则：突触前活动 + 突触后充分去极化 → 永久性增强

## 未解问题

- Q-ss-01（高优先级）：成年皮层中是否仍有功能性"沉默突触"储备，还是关键期后完全耗竭？若有，能否通过移除 PSD-95 或其他方法重新扩大沉默突触池以治疗弱视？
- Q-ss-02（中优先级）：沉默突触在大脑不同区域（海马 CA1、前额叶 L2/3 vs 视皮层 L4）的比例和开锁动力学是否相同？沉默突触耗竭是否也是海马等区域学习能力随年龄变化的分子基础？

## 修订历史

- 2026-09-05 · 创建 rev1 · 基于《开放眼的胜利》(#119) · 填补悬空引用（被 [[ocular-dominance-columns]] 和 [[metaplasticity]] 引用但无对应页） · 初始置信度：高

## 来源文章

- [[2026-09-05-odp-stage2-hebbian-vs-homeostatic]]

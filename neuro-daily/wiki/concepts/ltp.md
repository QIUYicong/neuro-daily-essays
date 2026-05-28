---
title: 长时程增强（LTP）
slug: ltp
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-26
updated: 2026-05-28
revision_count: 2
dimensions: [synaptic, cellular, cognition, brain-region]
related: [nmda-receptor, ampa-receptor, camkii, hebbian-learning, synaptic-transmission, ltp-ltd, btsp, place-cell, hippocampal-circuit]
prerequisites: [nmda-receptor, synaptic-transmission, action-potential]
opens_questions: [Q-ltp-lifetime-mechanism, Q-ltp-behavior-correspondence, Q-ltp-presynaptic-component]
source_articles: [2026-05-26-nmda-receptor-ltp, 2026-05-28-place-cells-btsp]
key_sources: ["PMID:22510460", "PMID:4727084", "PMID:6306230", "PMID:34908526", "PMID:28883072"]
---

# 长时程增强 (LTP, Long-Term Potentiation)

> **一句话定义**：高频或关联性刺激后突触传递效率的持久性增强，由 NMDA 受体介导的 Ca²⁺ 内流触发、CaMKII 维持、AMPA 受体插入表达，是目前研究最充分的学习记忆突触基础。

## 当前理解

我们现在认为，LTP 是突触可塑性的核心机制之一，是"用进废退"原则在突触层面的分子实现。LTP 的诱导需要 NMDA 受体的激活（即突触前和突触后活动的 Hebb 型巧合），Ca²⁺ 内流激活 CaMKII（自磷酸化至 T286），CaMKII 驱动 AMPA 受体从胞内再循环内体通过胞吐和横向扩散插入突触后致密区（PSD），突触传递效率持久增强。早期 LTP（E-LTP，数小时）主要依赖蛋白修饰（磷酸化）；晚期 LTP（L-LTP，数天至数周）还需要新蛋白质合成和树突棘结构的持久改变。海马 CA1 突触 LTP 的表达主要在突触后（AMPA 受体插入），而苔藓纤维→CA3 的 LTP 有明显的突触前成分（cAMP 依赖的递质释放增加）。

**重要**：LTP 不只是学习的必要条件，也与多种疾病相关——Aβ 寡聚体损害 LTP 并触发 LTD 样变化，可能是阿尔茨海默病早期记忆损害的突触层面机制。

**2026-05-28 新增（来自《场所细胞》文章）**：LTP 并非大脑唯一的持久性突触增强机制。海马 CA1 中的**行为时间尺度突触可塑性（BTSP）**是一种独立的学习规则，由树突钙平台电位（而非 NMDA 受体激活）触发，时间窗口约 ±3–4 秒（远超 LTP 诱导的毫秒级）。BTSP 可在单次体验中建立稳定的场所场。两者可能各有适用场景：LTP 适合精细调整和长期巩固，BTSP 适合快速写入行为级别的情景记忆。两者可能共享 NMDA 受体下游的部分分子机器（CaMKII 等），但触发条件和时间逻辑完全不同。

## 关键机制

### 1. 诱导（惰性 → 激活）

**必要条件**：NMDA 受体激活 → Ca²⁺ 内流（需 Hebb 型巧合：突触前谷氨酸 + 突触后去极化）

**Ca²⁺ 信号**：高 Ca²⁺ 脉冲（突触后棘内局部 Ca²⁺ 浓度短暂升高 10–100 倍）

**常用诱导协议**：
- 高频刺激（HFS）：100 Hz 四联，经典协议
- θ-burst 刺激（TBS）：5 Hz bursts × 4–5 spikes/burst，更接近体内θ振荡节律，效率更高
- 关联型配对协议：突触前刺激 + 突触后去极化配对

### 2. 早期表达（E-LTP，分钟–小时）

**Ca²⁺ → CaMKII 激活 → T286 自磷酸化**（自主活化状态）→
- GluA1 S831 磷酸化（提高单通道电导）
- AMPA 受体从再循环内体胞吐 → 树突膜 → 横向扩散 → PSD（被 TARP-PSD95 锚定）
- 沉默突触觉醒（原无 AMPA 受体的突触获得 AMPA 受体）
- 树突棘体积增大，PSD 面积扩大

### 3. 晚期表达（L-LTP，小时–数天及以上）

- 需要新蛋白质合成
- 信号通路：PKA → CREB → 即早基因（IEG）→ 结构蛋白
- 树突棘持久形态改变（穿孔突触出现、可能发生突触分裂）
- L-LTP 维持机制仍有争议（见未解问题）

### 4. CaMKII 对 LTP 维持的必要性

2021 年 Tao et al. 发现：在已建立的 LTP 之后，持续抑制 CaMKII 会导致 LTP 完全逆转。这证明 CaMKII 不只诱导 LTP，也是其维持所必需的——提示 CaMKII 的持续活化可能是 E-LTP 的关键维持机制。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| LTP 诱导需要 NMDA 受体 | AP5 阻断消除 LTP，保留基础传递 | PMID:6306230 | 高 |
| LTP 主要在突触后表达（AMPA 受体插入） | MK-801 速率法、PPF 不变、星形胶质细胞转运体电流不变 | PMID:22510460 (PMC3367554) | 高 |
| CaMKII 是 LTP 诱导和维持所必需的 | CaMKII 抑制剂（myr-CN27）在 LTP 后逆转增强 | PMID:34908526 (PMC8798046) | 高 |
| LTP 与突触后 AMPA 受体密度增加相关 | 静默突触实验、单通道电导增加 | PMID:22510460 (PMC3367554) | 高 |
| 树突棘增大伴随 LTP | 活体双光子成像 | PMID:22510460 (PMC3367554) | 高 |
| θ-burst 比等量高频刺激更有效诱发 LTP | 对比实验 | PMID:25452022 (PMC4411212) | 中-高 |

## 连接

- [[nmda-receptor]] — LTP 诱导的必要门卫，提供 Ca²⁺ 内流触发
- [[ampa-receptor]] — LTP 表达的主要执行机制（受体插入增加突触权重）
- [[camkii]] — Ca²⁺ 内流的第一个主要下游效应器，对诱导和维持均必要
- [[hebbian-learning]] — LTP 是 Hebb 规则在突触层面的分子实现
- [[synaptic-transmission]] — LTP 增强突触传递效率，是突触传递的可塑性形态
- [[btsp]] — 与 LTP 并列的第二种突触增强机制；秒级时间窗口，由树突钙平台电位触发；两者互补
- [[place-cell]] — 场所场的形成主要由 BTSP 驱动（非 LTP），但 LTP 可能参与场所场的长期巩固

## 未解问题

- Q-ltp-lifetime-mechanism：蛋白质周转率约数周，而记忆可持续数十年——什么机制赋予 LTP 如此持久的稳定性？CaMKII 亚基交换？突触结构自我维持？
- Q-ltp-behavior-correspondence：体内行为记忆的形成是否严格对应于特定突触群的 LTP？能否建立一一映射？印迹细胞（engram cells）研究在何种程度上回答了这一问题？
- Q-ltp-presynaptic-component：除苔藓纤维外，其他类型突触的 LTP 是否也有突触前贡献？谷氨酸释放概率的改变有多大贡献？

## 修订历史

- 2026-05-26 · 创建 · 基于《NMDA 受体：突触的巧合检测器》一文 · 初始置信度：高
- 2026-05-28 · 修订 · 基于《场所细胞》文章 · 新增 BTSP 作为平行突触增强机制；LTP 与 BTSP 的分工与互补关系；related 增加 btsp, place-cell, hippocampal-circuit

## 来源文章

- [[2026-05-26-nmda-receptor-ltp]]
- [[2026-05-28-place-cells-btsp]]

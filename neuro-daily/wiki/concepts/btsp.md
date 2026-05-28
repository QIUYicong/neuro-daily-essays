---
title: 行为时间尺度突触可塑性（BTSP）
slug: btsp
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-28
updated: 2026-05-28
revision_count: 1
dimensions: [synaptic, cellular, cognition]
related: [ltp, place-cell, dendritic-computation, hebbian-learning, nmda-receptor, camkii]
prerequisites: [ltp, dendritic-computation, nmda-receptor]
opens_questions: [Q-btsp-human-conservation, Q-btsp-nmda-role, Q-btsp-vs-stdp-interaction]
source_articles: [2026-05-28-place-cells-btsp]
key_sources: ["PMID:28883072", "PMID:26167906", "PMID:34882093", "PMID:39454575"]
---

# 行为时间尺度突触可塑性（BTSP, Behavioral Timescale Synaptic Plasticity）

> **一句话定义**：由树突钙平台电位触发的突触增强机制，时间窗口约 ±3–4 秒（远长于经典 STDP 的毫秒级），可在单次配对中增强在平台电位前后数秒内到达的突触输入，使海马场所场能在单次体验中一次性写入。

## 当前理解

我们现在认为，BTSP 是一种与经典 Hebbian STDP 并列的独立学习规则，而非后者的延伸。它在海马 CA1 和 CA3 神经元中被发现，且两者的时间窗口有所不同（CA1 不对称，CA3 对称）。

BTSP 的核心特征是：
1. **秒级时间窗口**（而非 STDP 的毫秒级）
2. **非因果性**：可以强化在平台电位之前数秒就已到达的突触输入（向后增强，"预测性"）
3. **单次写入**：5 次配对即可产生 3 倍的突触增强，自然发生时平均 1.4 次平台电位就足以建立稳定场所场
4. **全局触发信号**：触发器是树突钙平台电位（全局 Ca²⁺ 事件），而非局部突触的精确同步

这使 BTSP 特别适合**将行为级别的事件（秒量级）编码进突触权重**，而 STDP 更适合精细调整已有连接的权重。两者可能在不同时间尺度和不同任务中协同工作。

## 关键机制

### 1. 触发信号：树突钙平台电位

- 由内嗅皮层 EC3 和 CA3 两路输入联合驱动
- L 型钙通道（Cav1.2/1.3）介导，持续约 100–500 ms
- 提供强烈的全局 Ca²⁺ 内流（超过单个 NMDA 受体开放时的 Ca²⁺ 水平）
- 在 θ 振荡特定相位（约 56° 相位）优先触发

### 2. 不对称时间窗口（CA1）

在 CA1 神经元中，BTSP 的时间窗口呈**不对称形状**（Bittner et al., 2017, PMID:28883072）：

| 方向 | 时间常数 | 生理意义 |
|------|---------|---------|
| 向后（突触前输入早于平台电位） | τ_rise ≈ 1.31 s，窗口约 3–4 s | 强化"预测"信号（预告输入） |
| 向前（突触前输入晚于平台电位） | τ_decay ≈ 0.69 s，窗口约 2–3 s | 强化"结果"信号（后续输入） |

向后的窗口更宽意味着：已到达但未触发动作电位的输入更容易被强化——这产生了场所场中**向前偏移的斜坡膜电位**（ramp membrane potential），使细胞开始在到达场所场之前就升高放电率（预测性编码）。

### 3. CA3 的对称 BTSP

在 CA3 的循环突触上，BTSP 时间窗口是**对称的**（Li et al., 2024, PMID:39454575），发生在循环连接（recurrent synapses）而非苔状纤维（mossy fiber）上。这与 CA3 的模式补全功能一致：对称强化有助于在回路中形成吸引子状态。

### 4. 分子机制（部分已知）

- **NMDA 受体**：减弱约 84% 的 BTSP（D-APV）→ NMDA 受体参与局部突触信号放大
- **L 型钙通道（Cav1.2/1.3）**：减弱约 73%（尼莫地平）→ 是平台电位触发所必需
- **全局 Ca²⁺ 信号的作用**：可能激活 CaMKII、PKC 等 Ca²⁺ 依赖性激酶
- 具体的"读出分子"（哪个分子感受秒级时间窗口并驱动突触修改）尚不完全清楚

### 5. 双向 BTSP（Milstein et al., 2021, PMID:34882093）

BTSP 不只能写入新场所场，也能**修改已有场所场**：
- 场所场中心的钙棘波 → 场所场增强
- 场所场边缘的钙棘波 → 场所场移位或缩小
- 因此 BTSP 是一个动态的、双向调控的机制，而非单纯的"写入"操作

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| BTSP 时间窗口约 ±3–4 秒（CA1） | 脑片全细胞记录 + 在体胞内记录 + 药理学 | PMID:28883072 (PMC7289271) | 高 |
| 单次平台电位即可建立稳定场所场 | 清醒小鼠 CA1 在体记录，n=7（自然）+20（诱导） | PMID:26167906 (PMC4888374) | 高 |
| NMDA 受体减弱 84%，L 型 Ca 通道减弱 73% | 药理学实验，在体 + 离体 | PMID:28883072 (PMC7289271) | 高 |
| BTSP 可双向修改现有场所场 | 清醒小鼠胞内记录 + 钙棘波位置调控 | PMID:34882093 | 高 |
| CA3 BTSP 发生在循环突触，时间窗口对称 | 清醒小鼠 CA3 胞内记录 + 光遗传 | PMID:39454575 | 高（读摘要）|

## 连接

- [[ltp]] — 两者是并列的突触增强机制；BTSP 补充了 LTP（秒级 vs. 毫秒级时间窗口）
- [[place-cell]] — BTSP 是场所场形成的核心突触机制
- [[dendritic-computation]] — 树突钙平台电位是 BTSP 的触发机制；BTSP 是树突计算在可塑性层面的体现
- [[hebbian-learning]] — BTSP 不遵从严格的 Hebb 因果律（可以强化"非因果"输入）；但仍与 Hebb 精神相通（活动依赖的突触修改）
- [[nmda-receptor]] — NMDA 受体在 BTSP 中参与局部信号放大，但不是主要触发器（L 型钙通道是）

## 未解问题

- Q-btsp-human-conservation：BTSP 在人类海马中是否保守？（目前仅啮齿类实验）
- Q-btsp-nmda-role：NMDA 受体在 BTSP 中的确切角色是什么？局部放大器？还是有独立的触发功能？
- Q-btsp-vs-stdp-interaction：在同一突触上，BTSP 和 STDP 如何相互作用？它们是否竞争同一分子机器？

## 修订历史

- 2026-05-28 · 创建 · 基于《场所细胞》文章 · 提出 BTSP 作为独立学习规则 · 初始置信度：高

## 来源文章

- [[2026-05-28-place-cells-btsp]]

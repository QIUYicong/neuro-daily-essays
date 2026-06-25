---
title: 行为时间尺度突触可塑性（BTSP）
slug: btsp
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-28
updated: 2026-09-20
revision_count: 3
dimensions: [synaptic, cellular, cognition, behavior]
related: [ltp, place-cell, dendritic-computation, hebbian-learning, nmda-receptor, camkii, voltage-gated-calcium-channels, three-factor-learning-rule, entorhinal-cortex, social-memory]
prerequisites: [ltp, dendritic-computation, nmda-receptor, voltage-gated-calcium-channels]
opens_questions: [Q-btsp-human-conservation, Q-btsp-nmda-role, Q-btsp-vs-stdp-interaction, Q-btsp-ltype-vs-nmda, Q-btsp-ddsc-synapse-specificity, Q-btsp-in-vivo-ddsc, Q-btsp-non-spatial-generalization]
source_articles: [2026-05-28-place-cells-btsp, 2026-06-01-voltage-gated-calcium-channels, 2026-09-20-btsp-camkii-molecular-timekeeper]
key_sources: ["PMID:28883072", "PMID:26167906", "PMID:34882093", "PMID:39454575", "PMID:21746798", "PMID:32799605", "PMID:39385027", "PMID:37672577", "PMID:39253411", "PMID:41224656"]
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

### 4. 分子机制：αCaMKII的关键性与DDSC（2023–2024重大更新）

**已知的钙来源（2017–2022）**：
- **L 型钙通道（Cav1.2/1.3）**：减弱约 73%（尼莫地平）→ 平台电位的必要成分
- **NMDA 受体**：减弱约 84%（D-APV）→ 局部突触信号放大

**αCaMKII是BTSP必要因子（Xiao et al., 2023, PMID:37672577）**：

T286A点突变小鼠（T286=CaMKII自磷酸化位点）实验证明：
- 纯合T286A突变体BTSP几乎完全丧失（膜电位斜坡：2.3 mV vs 野生型8.0 mV）
- T286A激活衰减加速：1.9秒（突变体）vs 8.2秒（野生型）
- 行为验证：奖励区舔舐准确率下降，场所场几乎无法形成
- 关键点：CaMKII的**激活持续时间**（而非仅仅是否激活）是BTSP的关键

**DDSC：延迟、树突弥散、随机CaMKII激活（Jain et al., 2024, Nature, PMID:39385027）**：

2024年最重要的BTSP分子机制突破：使用2pFLIM（双光子荧光寿命成像）直接可视化CaMKII激活动态，发现与预期完全不同的激活模式：

- CaMKII**不在**平台电位期间立即大幅激活（推翻了原有假设）
- 实际发生的是：平台电位后**10–100秒**，CaMKII在**整根树突**中延迟、随机地激活（DDSC）
- DDSC峰值约在30–40秒后，具有弥散性（非突触特异性）和随机性
- **驱动力**：IP₃依赖的内质网（ER）延迟钙释放（平台电位→PLCβ→IP₃→ER钙释放→DDSC）

**因果性证明**（Jain et al., 2024）：
- paAIP2（光遗传CaMKII抑制剂）在**15–30秒窗口**阻断CaMKII → BTSP完全消失
- 在平台电位发生时阻断CaMKII → BTSP不受影响（即时CaMKII不是关键）
- 人工触发延迟去极化（模拟DDSC）→ 拯救被阻断的BTSP

**结论**：DDSC是BTSP分子秒表的核心——ER将即时钙信号变换为秒级延迟信号，CaMKII的延迟激活在10–100秒窗口内整合突触"资格痕迹"与平台电位事件。

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
| αCaMKII T286A突变体BTSP几乎完全丧失（2.3 vs 8.0 mV） | T286A敲入小鼠在体+脑片记录 | PMID:37672577 (PMC10482326) | 高 |
| DDSC：CaMKII在平台电位后10–100s延迟树突弥散激活 | 2pFLIM + FRET传感器脑片实验 | PMID:39385027 (PMC11540904) | 高（脑片；体内待验证）|
| DDSC由IP₃依赖ER钙释放驱动（阻断→DDSC/BTSP消失） | xestospongin C/U73122/thapsigargin药理学 | PMID:39385027 | 高（脑片）|
| DDSC在15–30s窗口是BTSP的因果性要求（paAIP2实验） | 光遗传CaMKII抑制 | PMID:39385027 | 高（脑片）|
| BTSP存在于非空间任务（嗅觉WM）：气味特异性CA1响应 | 体内钙成像+全息光遗传 | PMID:39253411 (PMC11383060) | 中高（待重复）|

## 连接

- [[ltp]] — 两者是并列的突触增强机制；BTSP 补充了 LTP（秒级 vs. 毫秒级时间窗口）
- [[place-cell]] — BTSP 是场所场形成的核心突触机制
- [[dendritic-computation]] — 树突钙平台电位是 BTSP 的触发机制；BTSP 是树突计算在可塑性层面的体现
- [[hebbian-learning]] — BTSP 不遵从严格的 Hebb 因果律（可以强化"非因果"输入）；但仍与 Hebb 精神相通（活动依赖的突触修改）
- [[nmda-receptor]] — NMDA 受体在 BTSP 中提供主要 Ca²⁺（APV 阻断→84% BTSP 降低）；两种 Ca²⁺ 来源协同维持平台电位
- [[voltage-gated-calcium-channels]] — L型通道（CaV1.2/1.3）提供平台电位的持续Ca²⁺内流（尼莫地平阻断→73% BTSP降低）；是 BTSP 的必要分子参与者
- [[camkii]] — αCaMKII 的自磷酸化（T286位点）维持 8.2 秒的激活持续时间是 BTSP 的必要条件；DDSC（延迟树突弥散激活）是 BTSP 的分子秒表（Xiao 2023；Jain 2024）
- [[three-factor-learning-rule]] — BTSP 是三因素学习规则的海马实现；树突平台电位（第三因素的生物学实现）整合局部突触活动（Hebbian 因子）形成秒级时序信用分配
- [[entorhinal-cortex]] — 内嗅皮层（EC3）是驱动树突平台电位的两路输入之一；MEC 调控 BTSP 触发频率，LEC 提供内容特异性信息（Dorian 2024/2025，嗅觉工作记忆中的非空间 BTSP）

## 未解问题

- Q-btsp-human-conservation：BTSP 在人类海马中是否保守？（目前仅啮齿类实验）
- Q-btsp-nmda-role：NMDA 受体在 BTSP 中的确切角色是什么？局部放大器？还是有独立的触发功能？
- Q-btsp-vs-stdp-interaction：在同一突触上，BTSP 和 STDP 如何相互作用？它们是否竞争同一分子机器？
- Q-btsp-ltype-vs-nmda：L 型 Ca 通道（73% 贡献）和 NMDA 受体（84% 贡献）在平台电位中的作用是否独立？总贡献超过 100% 意味着什么？
- Q-btsp-ddsc-synapse-specificity：DDSC（CaMKII 激活）是树突弥散的，但 BTSP 最终是突触特异性的——突触特异性从何而来？"资格痕迹"如何保留局部地址信息？
- Q-btsp-in-vivo-ddsc：DDSC 仅在脑片中被直接证明；清醒行为动物体内是否存在相同的 IP₃→ER→延迟 CaMKII 激活链？
- Q-btsp-non-spatial-generalization：BTSP 在嗅觉工作记忆中的推广是否真的依赖相同的平台电位+DDSC 机制，还是存在平行机制产生类似钙事件特征？

## 修订历史

- 2026-05-28 · 创建 · 基于《场所细胞》文章 · 提出 BTSP 作为独立学习规则 · 初始置信度：高
- 2026-06-01 · 修订 · 基于《神经元的三重钙门》一文 · 明确 L 型钙通道（CaV1.2/1.3）为平台电位的必要分子成分（尼莫地平降低 73% BTSP）；新增与 voltage-gated-calcium-channels 的连接；添加 Q-btsp-ltype-vs-nmda 未解问题
- 2026-09-20 · 修订（rev3）· 基于《BTSP的分子秒表》一文（#150）· 核心更新：DDSC 机制（Jain 2024, Nature）——CaMKII 在平台电位后 10–100 秒延迟弥散随机激活，由 IP₃ 依赖 ER 钙释放驱动，是 BTSP 时序整合的分子秒表；αCaMKII T286A 突变几乎完全阻断 BTSP（Xiao 2023）；CA3 对称 BTSP（Li 2024）；非空间 BTSP 扩展（Dorian 2024/2025）；新增连接：camkii、three-factor-learning-rule、entorhinal-cortex；新增未解问题：Q-btsp-ddsc-synapse-specificity、Q-btsp-in-vivo-ddsc、Q-btsp-non-spatial-generalization

## 来源文章

- [[2026-05-28-place-cells-btsp]]
- [[2026-06-01-voltage-gated-calcium-channels]]
- [[2026-09-20-btsp-camkii-molecular-timekeeper]]

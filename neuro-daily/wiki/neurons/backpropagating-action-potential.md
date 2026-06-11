---
title: 回传动作电位
slug: backpropagating-action-potential
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-08-26
updated: 2026-08-26
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit]
related: [action-potential, dendritic-computation, stdp, ltp, ltd, voltage-gated-sodium-channel, a-type-potassium-channel, nmda-receptor, camkii, voltage-gated-calcium-channels, axon-initial-segment]
prerequisites: [action-potential, voltage-gated-sodium-channel, synaptic-transmission, nmda-receptor]
opens_questions: [Q-bap-01, Q-bap-02]
source_articles: [2026-08-26-backpropagating-action-potential-stdp-signal]
key_sources: ["PMID:8107777", "PMID:8985013", "PMID:9202119", "PMID:9457640", "PMID:11731556", "PMID:17035526", "PMID:16675489", "PMID:18270515", "PMID:31230762", "PMID:41093758"]
---

# 回传动作电位 (Backpropagating Action Potential, bAP)

> **一句话定义**：动作电位在轴突始段触发后，同时沿树突逆向传播的再生性电信号，由树突 Na+ 通道主动支持，随距离递减衰减；其在树突棘处产生的去极化波与 EPSP 的时序叠加，决定了突触后 Ca²⁺ 动力学方向，从而实现 STDP 的细胞内时序裁决。

## 当前理解

我们现在认为，bAP 是单个锥体神经元实现时序依赖突触可塑性（STDP）的物理基础。

1994 年 Stuart 和 Sakmann（PMID:8107777，Nature）在大鼠新皮质锥体神经元上首次通过胞体-树突双位点膜片钳直接记录到 bAP：树突并非被动电缆，而是包含电压激活 Na+ 通道，能够主动支持动作电位的逆向再生传播。

bAP 的关键物理参数：
- **传播速度**：~0.5 m/s（Stuart et al. 1997，PMID:9457640）
- **幅度衰减**：随距离递减；新皮质锥体细胞在 300 μm 处仍保留 30–50% 幅度；海马 CA1 衰减更快（因 A 型 K+ 通道密度更高）
- **时间宽度**：比轴突动作电位略宽（~1–2 ms），因树突 Na+ 通道密度低而再生能力弱

bAP 的核心 STDP 功能（Magee & Johnston 1997，PMID:8985013）：
- 突触前放电在先（产生 EPSP）→ bAP 随后抵达 → EPSP 已部分解除 NMDA Mg²⁺ 阻断 + bAP 带来强去极化 → **超线性 Ca²⁺** → CaMKII → LTP
- bAP 在先 → Mg²⁺ 在谷氨酸到来前复位 → 低 Ca²⁺ → calcineurin → LTD

bAP 的传播受 A 型 K+ 通道（I_A）密度梯度调控（Hoffman et al. 1997，PMID:9202119）：在 CA1 树突中，I_A 密度随距离增高，构成"符合门"——单独的 bAP 无法远端入侵，但若树突棘刚接收过 EPSP（I_A 部分失活），bAP 即可充分传播，触发超线性 Ca²⁺。

## 关键机制

### 物理层：Na+ 通道驱动的主动再生

树突 Na+ 通道密度远低于 AIS（约为后者的 1/50），但仍足以支持主动再生传播。单个 bAP 依靠这些通道"接力"逆向传播，在每个树突节段补充因电流扩散而损失的幅度。由于密度低，补充量不足，最终导致递减性传播。

### 闸门层：A 型 K+ 通道的密度梯度

CA1 树突干的 A 型 K+ 通道密度从胞体到远端逐渐升高（Hoffman et al. 1997）：
- 距胞体 ~200–300 μm 处密度为胞体的 5–6 倍
- 这些通道在去极化时迅速激活，提供外向 K+ 电流，使 bAP 在远端熄灭
- 但若树突棘在 bAP 到来前 ~10–50 ms 内接收了 EPSP：EPSP 的去极化使 I_A 部分**失活** → bAP 可充分入侵 → 这形成了一个 AND 逻辑门

### 整合层：Ca²⁺ 超线性叠加

当 bAP（提供去极化）与 EPSP（提供谷氨酸）的时序叠加达到最佳范围（前先后随 +5 到 +40 ms）：
- NMDA 受体双重门打开（谷氨酸绑定 + Mg²⁺ 解除）
- **实测 Ca²⁺ > EPSP 单独 + bAP 单独之和**（超线性叠加）
- 高 Ca²⁺ 激活 CaMKII → LTP

后先前随时序（-5 到 -70 ms）：
- bAP 去极化后 Mg²⁺ 复位，谷氨酸后到时 NMDA 无法充分开放
- 低 Ca²⁺ → calcineurin/PP2B 激活 → AMPA 受体内吞 → LTD

### 位置依赖层：近端 vs 远端的不同规则

Letzkus et al.（2006，PMID:17035526）在 L5 锥体神经元中系统验证：
- **近端突触（<100 μm）**：单个 AP 配对即可遵循标准 STDP 时序规则
- **远端突触（>300 μm）**：单个 AP 的 bAP 幅度太弱，不能可靠诱导 LTP；需要高频爆发（200 Hz），且时序规则可能反转

高频爆发的机制：连续 AP 使 I_A 逐渐失活 → 后续 AP 传播更深，且触发树突 Ca²⁺ 棘波（T/R 型 VGCC 介导）→ LTP

### 细胞多样性层

Schamiloglu et al.（2025，PMID:41093758）在 PFC L5 中发现三类亚型的 bAP Ca²⁺ 响应截然不同：
- D3R+ 细胞：高度非线性（Cav1/Cav3 依赖），超线性指数 ~1.0
- D1R+ 细胞：中度超线性（BK 通道限制），超线性指数 ~0.39
- D2R+ 细胞：近线性（HCN 通道限制），超线性指数 ~0.07

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 新皮质树突含 Na+ 通道，bAP 主动逆向传播 | 大鼠新皮质锥体神经元双位点膜片钳（胞体+树突 100-400 μm）| PMID:8107777（Stuart & Sakmann 1994） | 高 |
| bAP + EPSP 超线性 Ca²⁺ → LTP | CA1 膜片钳 + Ca²⁺ 成像，人工配对实验 | PMID:8985013（Magee & Johnston 1997） | 高 |
| CA1 树突 A 型 K+ 通道密度梯度调控 bAP 幅度 | 外侧分离树突膜片钳，密度测量 + 4-AP 阻断 | PMID:9202119（Hoffman et al. 1997） | 高 |
| bAP 传播速度 ~0.5 m/s，从 AIS 起始 | 新皮质锥体神经元双位点延迟测量 | PMID:9457640（Stuart et al. 1997） | 高 |
| CA1 两类细胞：强/弱 bAP 二分化 | CA1 双位点记录，200–350 μm 距离 | PMID:11731556（Golding & Spruston 2001） | 高 |
| STDP 学习规则依赖树突位置，远端规则反转 | L5 锥体神经元，不同位置系统配对 | PMID:17035526（Letzkus et al. 2006） | 高 |
| 200 Hz 爆发诱导 L5 树突 Ca²⁺ 棘波和 LTP（50 Hz 无效）| L5 脑片 + Ca²⁺ 成像 + T/R 型 Ca²⁺ 通道阻断 | PMID:16675489（Kampa et al. 2006） | 高 |
| PFC L5 三类亚型 bAP Ca²⁺ 响应从近线性到高度非线性 | 小鼠 PFC 双光子成像 + 全细胞记录，3 转基因系 | PMID:41093758（Schamiloglu et al. 2025）| 中-高 |
| NaV1.2 缺失损害 PFC 树突 bAP 和突触可塑性（ASD 关联）| 条件性 SCN2A 敲除小鼠，PFC 电生理 + 成像 | PMID:31230762（Spratt et al. 2019）| 高 |

## 连接

- [[action-potential]] — bAP 是动作电位的逆向传播形式；AIS 是起始位点
- [[axon-initial-segment]] — bAP 从 AIS 出发，向树突逆向传播
- [[dendritic-computation]] — bAP 是树突主动信号的核心组成；bAP + 突触输入的叠加实现局部非线性计算
- [[stdp]] — bAP 是 STDP 的细胞内时序信使，将"突触后刚放电了"的信息传回每根树突棘
- [[ltp]] — bAP 与 EPSP 时序叠加的 Ca²⁺ 超线性效应是 LTP 诱导的关键步骤
- [[ltd]] — bAP 先于 EPSP 到来时产生低 Ca²⁺，激活 calcineurin，驱动 LTD
- [[nmda-receptor]] — NMDA 受体的 Mg²⁺ 阻断解除需要 bAP 提供的强去极化；bAP 时序决定 NMDA 开放幅度
- [[a-type-potassium-channel]] — A 型 K+ 通道密度梯度是控制 bAP 远端入侵的关键闸门
- [[voltage-gated-sodium-channel]] — 树突 Na+ 通道（含 NaV1.2）是 bAP 主动传播的分子基础
- [[voltage-gated-calcium-channels]] — T/R 型 VGCC 介导爆发放电时的树突 Ca²⁺ 棘波（Kampa 2006）
- [[camkii]] — bAP+EPSP 超线性 Ca²⁺ 的主要下游效应器，执行 LTP

## 未解问题

- Q-bap-01（高优先级）：清醒自由行为动物中，bAP 在生理背景活动下的真实传播效果与频率是多少？脉冲轰炸（synaptic bombardment）如何影响 bAP 传播？
- Q-bap-02（中优先级）：CA1 锥体神经元 bAP 传播强/弱二分化的确切分子决定因素是什么？通道密度差异如何形成？这种异质性是否在体内有功能意义？

## 修订历史

- 2026-08-26 · 创建 · 基于《逆流而上：回传动作电位》(#124) · 填补 stdp.md 的悬空引用 backpropagating-action-potential · 初始置信度：高（核心机制 established，体内条件尚待研究）

## 来源文章

- [[2026-08-26-backpropagating-action-potential-stdp-signal]]

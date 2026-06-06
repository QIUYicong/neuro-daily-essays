---
title: Neuroligin-Neurexin 突触粘附系统
slug: neuroligin-neurexin
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-06
updated: 2026-08-06
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [synaptogenesis, postsynaptic-density, gephyrin-scaffold, axon-guidance, autism-spectrum-disorder, lrrtm]
prerequisites: [synaptic-transmission, action-potential]
opens_questions: [Q-synaptogenesis-02]
source_articles: [2026-08-06-synaptogenesis-molecular-assembly]
key_sources: ["PMID:10892652", "PMID:18923512", "PMID:26209464", "PMID:12669065", "PMID:41824561"]
---

# Neuroligin-Neurexin 突触粘附系统 (Neuroligin-Neurexin Synaptic Adhesion System)

> **一句话定义**：跨突触间隙的粘附分子对——突触后 Neuroligin（NL）与突触前 Neurexin（NRXN）结合，通过"双向信号"协调突触前主动带和突触后密度体的同步装配，并以亚型特异性分配兴奋性和抑制性突触身份。

## 当前理解

我们现在认为，NL-NRXN 系统是突触身份建立的核心指令系统，而非单纯的物理粘合剂。两类分子均通过广泛的**可变剪接**产生数量庞大的异构体（NRXN 尤其复杂，每条链有 6 个可变外显子，理论组合数千种），这套"分子密码"在不同神经元类型和发育阶段差异表达，被认为负责赋予不同突触其独特的分子特性。

**突触类型二分**：NL1 定向至兴奋性（谷氨酸能）突触，与 PSD-95 骨架耦联；NL2 定向至抑制性（GABAergic/甘氨酸能）突触，与 Gephyrin/Collybistin 骨架耦联。这一分工在蛋白质水平和基因敲除实验中均得到验证，是 E/I 平衡从发育起点就开始编程的分子基础。

**弱结合的功能意义**：2026 年 Boyd 等人（PMC12985673）的研究揭示，NL2-NRXβ1 亲和力（~10 μM）弱于 NL1-NRXβ1（~nM 级别），但这种弱结合通过**聚集效应（avidity effect）**实现高效功能：约 15 对同时结合足以稳定牵引两张膜，且毫秒级的复合物解离动力学使突触保留动态可塑性。

**不只是粘附**：NL-NRXN 对产生**双向胞内信号**——NL 的胞质尾端与 PSD-95 的 PDZ3 域（通过 PSD-95 的 PDZ 结合基序）相互作用，将 NL 整合进 PSD 骨架；NRXN 的胞质尾端（α-NRXN）与 CASK、Mint 等蛋白结合，调控钙通道聚集和囊泡对接。

## 关键机制

### 分子结构

**Neuroligin（NL）**：I 型单次跨膜蛋白；胞外域为类胆碱酯酶（ChE-like）折叠，含配体（NRXN）结合口袋；胞质尾端短，但含 PDZ 结合基序（与 PSD-95 对接）

**Neurexin（NRXN）**：
- α-NRXN：大型胞外域，含 6 个 LNS（Laminin-Neurexin-Sex hormone binding globulin）域和 3 个 EGF 样域，参与多种配体（NL、LRRTM、CBLN、Latrophilin 等）结合
- β-NRXN：较短，含 1 个 LNS 域；NRXβ1 是 NL2 的优先结合伙伴

### 可变剪接密码

NRXN 基因（Nrxn1/2/3）含 6 个可变外显子（SS1–SS6），不同剪接影响配体结合特性：
- SS4（+）的 NRXN：不结合 NL1-B splice 插入；偏好其他 NL 亚型
- SS4（-）的 NRXN：广谱结合多种 NL；优先结合 LRRTM

NL1 的 B splice 插入（外显子 B）决定它对 SS4（-）NRXN 的结合偏好，从而影响 NL1 在突触类型选择中的精确度。

### 双向信号

**前向（NL → NRXN 方向）**：NL 胞外域结合 NRXN → 通过 NRXN 胞质域激活突触前下游效应（Munc18/SNARE 预组装、P/Q 型钙通道聚集）

**反向（NRXN → NL 方向）**：NRXN 接合 NL 胞外域 → 通过 NL 胞质尾端 PDZ 结合基序激活 PSD-95 募集 → PSD 骨架组装启动

### 抑制性突触特异性

NL2 的胞质域序列差异使其与 Collybistin（而非 PSD-95）优先结合，触发 Collybistin 的自抑制解除，激活 Cdc42→Gephyrin 格栅在抑制性接触点铺开（见 [[gephyrin-scaffold]]）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| NL 是主动突触诱导信号 | HEK293 异位表达 NL1/2 → 接触点突触前 SV 聚集 | PMID:10892652（Scheiffele 2000） | 高 |
| NL1→兴奋，NL2→抑制性突触 | 双亚型特异性免疫荧光 + 亚型 KO | PMID:26209464（Bemben 2015）| 高 |
| NL2-NRXβ1 弱结合 × 聚集效应 | 数学建模 + 活细胞荧光成像 | PMID:41824561（Boyd 2026） | 高 |
| NLGN3 R451C → ASD 相关症状 | NL3 R451C 敲入小鼠：社交缺陷 + E/I 异常 | PMID:12669065（Jamain 2003）+ 后续小鼠研究 | 高（人类遗传 + 小鼠功能） |

## 连接

- [[synaptogenesis]] — NL-NRXN 是突触生成的启动触发器
- [[postsynaptic-density]] — NL1 下游；PSD-95 通过 NL1 PDZ 结合锚定
- [[gephyrin-scaffold]] — NL2 下游；Gephyrin 通过 NL2-Collybistin 招募
- [[axon-guidance]] — NRXN 也参与轴突导向（嗅觉系统层状投射）；分子连续性
- [[lrrtm]] — 平行突触诱导系统（同样依赖 NRXN）
- [[autism-spectrum-disorder]] — NLGN3 R451C、NLGN4 缺失、NRXN1 拷贝数变异均与 ASD 相关

## 未解问题

- Q-synaptogenesis-02：NRXN 异构体密码在体内是否实现突触亚类特异性？条件敲除单一可变外显子后果如何？

## 修订历史

- 2026-08-06 · 创建 · 基于《轴突找到伙伴之后：突触如何从分子装配线上诞生》(#105) · 初始置信度：高

## 来源文章

- [[2026-08-06-synaptogenesis-molecular-assembly]]

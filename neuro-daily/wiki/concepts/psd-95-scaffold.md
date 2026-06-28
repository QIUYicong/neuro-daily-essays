---
title: PSD-95 支架（突触槽位模型）
slug: psd-95-scaffold
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-10-17
updated: 2026-10-17
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [postsynaptic-density, tarp-auxiliary-subunit, ampa-receptor, nmda-receptor, camkii, calcineurin, ltp, ltd, liquid-liquid-phase-separation, excitotoxicity, alzheimers-disease]
prerequisites: [synaptic-transmission, ampa-receptor, postsynaptic-density]
opens_questions: [Q-psd95-01, Q-psd95-02, Q-psd95-03, Q-psd95-04]
source_articles: [2026-10-17-psd-95-scaffold-synaptic-slot]
key_sources: ["PMID:23719161", "PMID:19596852", "PMID:23836932", "PMID:19169250", "PMID:37290118", "PMID:35704570", "PMID:12201694"]
---

# PSD-95 支架（突触槽位模型）

> **一句话定义**：PSD-95（DLG4）是突触后致密区（PSD）的核心支架蛋白，通过三个串联 PDZ 结构域锚定 AMPA/NMDA 受体，其拷贝数决定突触能容纳的受体数量上限（槽位模型）；棕榈酰化循环动态控制其突触定位；它在 LTP 中扩张受体槽位，在 LTD 中通过 AKAP150-钙调磷酸酶轴促进受体内吞，是突触双向可塑性的分子枢纽。

## 当前理解

我们现在认为，PSD-95 是兴奋性突触传递强度的物理守门人。每个 PSD-95 分子的 PDZ1/2 结构域是一个"停车位"——TARP 辅助的 AMPA 受体必须占据这些槽位才能在突触后膜稳定驻留。槽位数量 × 槽位密度 × 与释放位点的对准，共同决定突触的实际传递效率。

**槽位模型**（Slot Model）的核心证据（Schnell et al. 2002）：PSD-95 PDZ1/2 点突变使突触 AMPAR 骤降；PSD-95 过量表达使突触 AMPAR 增加——双向基因证据确立了 PSD-95 是 AMPAR 突触定位的"可寻址槽位"。

**纳米域组织**（MacGillavry et al. 2013）：PSD-95 不均匀分布于 PSD，而是形成约 80 nm 直径的纳米簇，AMPAR 在这些纳米簇内富集约 1.9 倍；纳米簇直接命中的 mEPSC 幅度约是离簇释放的 2 倍，说明受体的空间组织与释放位点对准是传递效率的关键变量。

**棕榈酰化循环**（Fukata et al. 2009, 2013）：PSD-95 通过 Cys3/Cys5 双棕榈酰化锚定于膜。DHHC2（树突局部棕榈酰转移酶）感知活动水平，在活动降低时定位于突触后膜，驱动 PSD-95 快速聚集；这种循环是持续的（t₁/₂ ~25 分钟），说明 PSD-95 的突触定位是能量依赖的动态平衡。

**双向可塑性枢纽**：同一个 PSD-95 分子通过不同结构域参与相反方向的可塑性——PDZ1/2 锚定 TARP（LTP 方向），SH3-GK 定位 AKAP150-钙调磷酸酶（LTD 方向）。Ca²⁺ 幅度决定哪个功能占主导。

## 关键机制

### 1. 分子结构：五结构域的多价枢纽

```
N ─ PDZ1 ─ PDZ2 ─ PDZ3 ─ SH3 ─ GK ─ C
        │         │         │      └──────┐
      AMPAR    NMDAR     TrkB/       AKAP150
      (TARP)  (GluN2B)  其他         (LTD轴)
```

- **PDZ1/2**：结合 TARP 的 PDZ 配体（–TTPV 等），锚定 AMPAR；结合 GluN2B C 末端，锚定 NMDAR；是槽位模型的物理实体
- **PDZ3**：更宽松的特异性，结合 TrkB（BDNF 受体）、Kv1.4 等
- **SH3-GK 超模块**：结合 AKAP150，定位钙调磷酸酶/PKA；在 LTD 中必要

### 2. 棕榈酰化循环

```
↓ 神经活动
DHHC2 小泡定位 → 突触后膜插入
    ↓
PSD-95 Cys3/Cys5 棕榈酰化（DHHC2 催化）
    ↓
PSD-95 锚定于突触后膜内叶 → 突触聚集
    ↓（持续循环，t₁/₂ ~25 min）
脱棕榈酰化酶活动 → PSD-95 脱离 → 再棕榈酰化
```

- 棕榈酰化是动态可逆的，不是静态锚定
- DHHC2 具有活动感知性；活动升高时 DHHC2 从突触后膜散开 → PSD-95 聚集减少

### 3. LTP 中的槽位扩张（两个时间尺度）

**早期**（分钟内）：TARP 磷酸化（CaMKII 介导）→ PDZ 配体暴露 → PSD-95 亲和力骤升 → 更多 AMPAR 被捕获在现有槽位（详见 `tarp-auxiliary-subunit`）

**晚期**（小时-天）：PSD 结构性扩张 → 更多 PSD-95 分子招募 → 槽位上限永久提升（需要新蛋白合成）

### 4. LTD 中的受体驱逐轴

```
NMDAR 弱激活 → 中低 Ca²⁺
    ↓
PP2B（钙调磷酸酶）激活（高 Ca²⁺ 亲和力）
    ↓
PP2B 通过 AKAP150 → PSD-95 SH3-GK 定位于 PSD 侧
    ↓（必要：PSD-95 L460P 突变阻断 AKAP150 结合 → LTD 消失）
GluA1 Ser845 去磷酸化（PKA 位点）
    ↓
AMPAR 对胞吞敏感化 → 网格蛋白内吞 → LTD
```

### 5. 纳米域密度控制传递效率

纳米簇内受体**密度**（而非总数量）决定传递效率（Han et al. 2022/NL3 模型）：
- 纳米簇变大但受体密度降低 → 突触强度降低
- 与释放位点的纳米级对准也是关键变量（MacGillavry 2013 模拟）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| PSD-95 PDZ1/2 双向控制突触 AMPAR 数量（槽位模型） | PDZ1/2 点突变→骤降；过量表达→增加 | PMID:12201694 (Schnell 2002) | 高 |
| PSD-95 纳米域 ~80 nm，AMPAR 富集 1.9× | PALM 超分辨（~25 nm 分辨率），双色成像 | PMID:23719161 (PMC3668352) | 高 |
| DHHC2 介导活动敏感性 PSD-95 棕榈酰化 | DHHC-shRNA 筛选；TTX 模型 | PMID:19596852 (PMC2712995) | 高 |
| PSD-95 突触 t₁/₂ ~25 min（动态循环） | FRAP + 构象特异性抗体 | PMID:23836932 (PMC3704990) | 高 |
| PSD-95 SH3-GK/AKAP150 轴是 NMDAR-LTD 必要条件 | L460P 突变，shRNA knockdown，ΔAKAP-PP2B 突变体 | PMID:19169250 (PMC2694745) | 高 |
| 纳米簇密度（非面积）决定突触强度 | NL3 KO：簇面积增大但密度降低→强度下降 | PMID:35704570 (PMC9200272) | 中-高 |
| PSD-95 过量表达需要 CaMKII 活动才能增强突触 | TTX 阻断大幅减弱 PSD-95 效应；CaMKII 抑制剂 CN19 | PMID:22114157 (PMC3289452) | 中（争议见下） |

## 连接

- [[postsynaptic-density]] — PSD-95 是 PSD 相分离凝聚体的核心支架；PSD-95/SynGAP 双组分网络驱动 LLPS
- [[tarp-auxiliary-subunit]] — TARP 是 PSD-95 PDZ1/2 槽位的配体；LTP 时 CaMKII 磷酸化 TARP 使 PDZ 结合亲和力骤升 10-30 倍
- [[ampa-receptor]] — PSD-95 决定 AMPAR 的突触定位上限；通过 TARP 锚定（LTP）和 AKAP150-钙调磷酸酶轴（LTD）双向调控 AMPAR
- [[nmda-receptor]] — GluN2B CTD 通过 PDZ2 与 PSD-95 直接结合；NMDAR 活化是 CaMKII（LTP）和钙调磷酸酶（LTD）的共同上游
- [[camkii]] — CaMKII 磷酸化 TARP 是 LTP 早期表达的关键步骤；CaMKII 的效应部分通过 TARP-PSD-95 轴实现
- [[calcineurin]] — PSD-95 SH3-GK 通过 AKAP150 将钙调磷酸酶定位于突触，是 NMDAR-LTD 的物理基础
- [[ltp]] — PSD-95 槽位数量是 LTP 的物理上限；晚期结构 LTP 通过扩大 PSD-95 库持久提升上限
- [[ltd]] — PSD-95-AKAP150-钙调磷酸酶轴是 NMDAR-LTD 的必要条件
- [[liquid-liquid-phase-separation]] — PSD-95/SynGAP 多价网络通过 LLPS 形成 PSD 凝聚相；PSD-95 是相分离的核心结构元素
- [[excitotoxicity]] — PSD-95 PDZ2 将 GluN2B 与 nNOS 连接，是兴奋毒性 NO 信号的物理媒介

## 未解问题

- Q-psd95-01（高优先级）：LTP 前后 PSD-95 分子数量是否有系统性、可测量的变化？目前超分辨数据（~300 拷贝/PSD）是否在 LTP 前后有统计显著性差异的报道？
- Q-psd95-02（中优先级）：棕榈酰化循环速率如何影响突触对反复活动的响应？是否存在循环饱和效应导致 PSD-95 供给不足？
- Q-psd95-03（高优先级）：晚期结构 LTP 中 PSD-95 纳米域是否系统性重排（增大/更密/更精准对准释放位点）？这种重排是否是结构 LTP 的必要条件？
- Q-psd95-04（中优先级）：靶向 GluN2B-PSD-95 的 nerinetide（III 期临床）长期阻断是否影响正常 LTP/LTD 和记忆巩固？

## 修订历史

- 2026-10-17 · 创建 · 基于《PSD-95：突触槽位的分子建筑师》(#185) · 初始置信度：高（槽位模型和棕榈酰化循环均为多来源验证的已建立机制）

## 来源文章

- [[2026-10-17-psd-95-scaffold-synaptic-slot]]

---
title: PSD-95 支架蛋白
slug: psd-95-scaffold
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-28
updated: 2026-06-28
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [ampa-receptor, tarp-auxiliary-subunit, postsynaptic-density, ltp, camkii, nmda-receptor, liquid-liquid-phase-separation, alzheimers-disease, synaptic-tagging-capture, synaptic-transmission]
prerequisites: [ampa-receptor, tarp-auxiliary-subunit, synaptic-transmission]
opens_questions: [Q-psd95-01, Q-psd95-02, Q-psd95-03, Q-psd95-04]
source_articles: [2026-06-28-psd-95-scaffold-synaptic-slot]
key_sources: ["PMID:11082065", "PMID:12359873", "PMID:23719161", "PMID:23926273", "PMID:27109929", "PMID:17360496", "PMID:28790172", "PMID:38839340", "PMID:27565345", "PMID:30864948"]
---

# PSD-95 支架蛋白 (PSD-95 Scaffold / Synaptic Slot Counter)

> **一句话定义**：PSD-95（DLG4 编码，80 kDa，约 300 拷贝/突触）是突触后致密区（PSD）的核心支架蛋白，通过 PDZ1/2 结构域为 TARP/AMPAR 复合物提供有限数量的锚定"槽位"（synaptic slots），其拷贝数直接决定突触能容纳多少 AMPA 受体（突触权重的物理上限）；超分辨率显微镜揭示其形成约 80 nm 纳米域，与突触前释放位点精确对齐构成跨突触纳米柱，是亚突触计算组织的结构基础。

## 当前理解

我们现在认为，PSD-95 不仅仅是突触后膜下的一个被动结构蛋白，而是突触权重的**分子计数器**。El-Husseini 等 2000（PMID:11082065）的过量表达实验和 Schnell 等 2002（PMID:12359873，PMC:PMC129795）的直接 PDZ-TARP 相互作用验证，共同建立了"槽位模型"：PSD-95 通过 PDZ1/2 结构域提供 AMPA 受体的锚定位点，其分子数量（~300 拷贝/PSD）是突触 AMPA 受体容量的物理上限。

2013 年以来，超分辨率显微镜（PALM/STORM/DNA-PAINT）进一步揭示，PSD-95 分子并非均匀分布在 PSD 中，而是组织成约 80 nm 的纳米域（MacGillavry 2013，PMID:23719161；Nair 2013，PMID:23926273；Broadhead 2016，PMID:27109929）。每个 PSD 内含 1–10 个纳米域，每个纳米域构成一组独立的 AMPAR 锚定单元，且与突触前释放位点（RIM/Munc13 纳米域）在纳米尺度上精确对齐（"跨突触纳米柱"），这一亚突触结构组织使突触传递效率最大化（Fukata 等 2024，PMID:38839340）。

PSD-95 本身还是动态变构调节器——PDZ3 的配体结合可触发下游 SH3-GK 构象变化（Rademacher 等 2019，PMID:30864948），Ser-561 的磷酸化调控双向结构可塑性（Wu 等 2017，PMID:28790172）。

## 关键机制

### 1. 结构：五域分工

- **N 端双棕榈酰化（Cys-3/Cys-5）**：膜锚定；棕榈酰化循环控制突触靶向
- **PDZ1/PDZ2（串联）**：结合 NMDAR GluN2A/B C 末端、TARP C 末端 PDZ 配体（–TTPV）；槽位功能的核心
- **PDZ3**：结合 CRIPT（微管连接）和 nNOS（一氧化氮信号）；配体结合触发 SH3-GK 变构
- **SH3**：与 GK 形成分子内超模块，调控 PSD-95 整体构象
- **GK（鸟苷酸激酶样，无催化活性）**：结合 GKAP/SAPAP，连接 Shank-Homer-mGluR5 深层支架；结合 AKAP150（PKA 信号锚定）

### 2. 槽位模型：分子数量 = 受体容量上限

| 实验 | 操作 | 结果 | 来源 |
|-----|-----|-----|-----|
| 过量表达 PSD-95 | 突触 PSD-95↑ | 突触 AMPAR 电流↑；总表面 AMPAR 不变 | Schnell 2002 |
| PDZ1/2 突变 | 破坏 TARP 结合 | 过量 PSD-95 不再增加 AMPAR | Schnell 2002 |
| 敲低 PSD-95 | 内源 PSD-95↓ | 突触 AMPAR 电流↓ | Schnell 2002 |
| PSD-95 过量表达 | 发育中神经元 | 脊头增大、突触成熟加速、AMPAR 增加 | El-Husseini 2000 |
| 敲低 PSD-95 | 成熟神经元 | LTP 可诱导但不能稳定维持 | Ehrlich 2007 |

### 3. 纳米组织：从槽位到纳米域到纳米柱

- **纳米域（~80 nm）**：每个 PSD 内 PSD-95 聚集成 1–10 个离散纳米簇；AMPAR 优先富集于 PSD-95 纳米域内（非均匀分布）
- **PSD-95 拷贝数 → AMPAR 纳米密度**：Nair 2013 因果实验：PSD-95 数量直接控制 AMPAR 纳米簇密度和 mEPSC 幅度
- **跨突触纳米柱**：PSD-95/AMPAR 纳米域与突触前 RIM/Munc13 纳米域空间对齐（横向偏差 <100 nm）；LTP 可增强对齐程度

### 4. LTP 时 PSD-95 的三阶段动态

1. **快速相（秒–分钟）**：CaMKII 磷酸化 TARP polybasic region → TARP/PSD-95 亲和力骤升 10–30 倍 → 槽位利用率增加（AMPAR 从突触外膜捕获至既有槽位）
2. **中间相（分钟–小时）**：PSD-95 Ser-561 磷酸化 → SH3-GK"开放构象" → 增强 GKAP 结合 → 更多 PSD-95 向突触靶向/稳定
3. **晚期结构相（小时）**：脊头体积增大（蛋白合成依赖）→ PSD 面积扩大 → 更多 PSD-95 可被招募 → 槽位上限升高

### 5. 相分离整合（与 PSD 凝聚相）

PSD-95（PDZ1/2 + SH3-GK）与 SynGAP 的多价相互作用形成液液相分离凝聚相（Zeng 等 2016，PMID:27565345），使 PSD-95 在突触后膜处高度浓缩（100–1000 倍于胞质背景）。Laursen 等 2022（PMID:36157580）进一步显示 PDZ 超模块架构在平衡配体结合与相分离倾向间有精细调谐。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| PDZ1/2-TARP 直接结合控制突触 AMPAR 数量 | 过量表达/敲低+电生理+PDZ 突变 | PMID:12359873 | 高 |
| PSD-95 过量表达驱动突触成熟 | 发育神经元过量表达+电生理+成像 | PMID:11082065 | 高（摘要仅）|
| PSD-95 对 LTP 稳定化必需 | shRNA 敲低+LTP 诱导+时程追踪 | PMID:17360496 | 高 |
| PSD-95 形成约 80 nm 纳米域 | PALM 超分辨率（海马神经元） | PMID:23719161 | 高 |
| PSD-95 拷贝数 → AMPAR 纳米域密度 → mEPSC | 过量表达/敲低+uPAINT+dSTORM+patch clamp | PMID:23926273 | 高 |
| 纳米域是突触基本建构单元（10 万突触统计）| 大规模 dSTORM 海马切片 | PMID:27109929 | 高 |
| Ser-561 磷酸化调控 SH3-GK 构象与双向结构可塑性 | 磷拟突变体+成像+电生理 | PMID:28790172 | 中-高 |
| PSD-95/SynGAP LLPS 形成 PSD 凝聚相 | 体外 LLPS + FRAP | PMID:27565345 | 高 |

## 连接

- [[ampa-receptor]] — PDZ1/2 通过 TARP 锚定 AMPAR；PSD-95 拷贝数决定突触 AMPAR 容量上限
- [[tarp-auxiliary-subunit]] — TARP C 末端 PDZ 配体插入 PSD-95 PDZ1/2，是槽位占用的关键分子锁
- [[postsynaptic-density]] — PSD-95 是 PSD 相分离凝聚相的核心蛋白；本页聚焦 PSD-95 个体蛋白功能，postsynaptic-density 聚焦整体 PSD 相行为
- [[ltp]] — PSD-95 槽位数决定突触可增强的 AMPAR 容量上限；PSD-95 对 LTP 稳定化必需
- [[camkii]] — CaMKII 磷酸化 TARP（间接改变 PSD-95 利用率）；可能磷酸化 PSD-95 本身（Ser-561）
- [[nmda-receptor]] — NMDAR GluN2B C 末端也竞争 PSD-95 PDZ1/2 结合位点
- [[liquid-liquid-phase-separation]] — PSD-95 通过 LLPS 浓缩于 PSD；相变调控 LTP 时 PSD 重组
- [[alzheimers-disease]] — Aβ 寡聚体损害 PSD-95 定位；PSD-95 是 AD 早期突触丢失的分子标志物
- [[synaptic-tagging-capture]] — PSD-95 在 LTP 突触标签中的作用（与 CaMKII 凝聚体共同）

## 未解问题

- Q-psd95-01（高优先级）：纳米域内 PSD-95 分子的精确数量？每个纳米域是固定还是动态数量？与 AMPAR 纳米簇的 1:1 对应如何建立和维持？
- Q-psd95-02（高优先级）：PSD-95 棕榈酰化-去棕榈酰化循环如何在神经活动中精确调控？是否对特定纳米域的子集有选择性？
- Q-psd95-03（中优先级）：SH3-GK 构象开关（Wu 2017）的体内生理调控机制？什么信号触发"开放"vs"关闭"构象？是否参与 LTD 时 PSD 拆卸？
- Q-psd95-04（高优先级）：跨突触纳米柱的可塑性机制——LTP/LTD 如何重新排列前后膜纳米域的空间对齐？时程？分子驱动？

## 修订历史

- 2026-06-28 · 创建 · 基于《PSD-95：突触权重的分子计数器》（#185）· 初始置信度：高（槽位模型 established；纳米域 established；SH3-GK 构象机制 mainstream）

## 来源文章

- [[2026-06-28-psd-95-scaffold-synaptic-slot]]

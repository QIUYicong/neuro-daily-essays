---
title: 液-液相分离（LLPS）
slug: liquid-liquid-phase-separation
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-09-12
updated: 2026-09-12
revision_count: 1
dimensions: [molecular, cellular, synaptic]
related: [postsynaptic-density, synapsin, tdp-43-pathology, ltp, ampa-receptor, nmda-receptor, camkii, synaptic-transmission, intrinsically-disordered-protein]
prerequisites: [synaptic-transmission, ampa-receptor]
opens_questions: [Q-llps-01, Q-llps-02]
source_articles: [2026-09-12-liquid-liquid-phase-separation-postsynaptic-density]
key_sources: ["PMID:29976799", "PMID:27565345", "PMID:30078712", "PMID:41405989"]
---

# 液-液相分离（LLPS, Liquid-Liquid Phase Separation）

> **一句话定义**：细胞内特定蛋白质（通常含有内禀无序区 IDR 或多价结合结构域）在超过临界浓度后，从均匀溶液中自发分离出富含自身的液态"浓缩相"，形成无膜细胞器（membraneless organelle）；在神经元中，LLPS 同时组织突触前小泡储备库和突触后信号密度。

## 当前理解

我们现在认为，液-液相分离是细胞组织无膜"浓缩相"（condensate）的普遍物理机制，也是突触前后两端维持蛋白质高度富集并动态调节的基础。在这一机制中：

**突触前**：突触素（Synapsin 1/2/3）通过其 C 末端 IDR 形成液态液滴，捕获突触小泡，构成小泡储备池。Ca²⁺/CaMKII 磷酸化能在数秒内溶解此液相，将储备池小泡动员至即发释放池。

**突触后**：PSD-95（MAGUK 支架蛋白）与 SynGAP（同源三聚体，Ras GAP 酶）的多价相互作用（PDZ-PDZ 结合基序多对多网络）驱动 LLPS，形成浓缩相，使 SynGAP 在突触后密度（PSD）中的浓度比背景高 400–1000 倍。此浓缩相是 AMPAR/NMDAR 锚定、下游信号通路组织的物理平台。

**LTP 中的相变**：LTP 诱导时，CaMKII 磷酸化 SynGAP，削弱其与 PSD-95 的结合，驱动 SynGAP 集体从浓缩相中逸散，Ras 抑制解除，AMPAR 插入，突触增强。这是突触权重调节的相变机制。

**病理意义**：TDP-43、FUS 等 RNA 结合蛋白的正常 LLPS（形成 RNA 应激颗粒）若发生固化（从液态转为不可逆固态聚集），则产生 ALS/FTD 等神经退行性疾病的病理包涵体。

## 关键机制

### 热力学驱动力

LLPS 发生的分子基础：

1. **内禀无序区（IDR）**：富含极性/带电氨基酸（精氨酸/赖氨酸/甘氨酸/丝氨酸等）的无固定折叠区段，通过弱、多重、短暂相互作用（阳离子-π、疏水集聚、氢键）驱动相分离。
2. **多价结合网络**：一个蛋白质同时携带 N 个结合位点（如 PSD-95 的 3 个 PDZ 结构域），与对应的多价配体（如 SynGAP 三聚体的 3 个 PDZ 结合基序）形成高阶交联网络，在浓度超过临界点后自发相分离。
3. **关键参数**：相分离的临界浓度依赖温度、pH、盐浓度（离子强度可竞争弱相互作用）、分子伴侣（如 crowding agents）。

### 凝聚体的特性（液态 vs. 凝胶/固态）

| 特性 | 液态凝聚体 | 凝胶/玻璃态 | 固态聚集体（病理） |
|------|-----------|-----------|----------------|
| FRAP 恢复 | 秒–分钟 | 分钟–小时 | 几乎不恢复 |
| 液滴融合 | 快速融合 | 融合受阻 | 不融合 |
| 反应性 | 磷酸化可快速溶解 | 需更强刺激 | 不可逆 |
| 代表 | 体外重组突触素/SynGAP 液滴 | 体内 PSD（t₁/₂ ~25 min） | ALS TDP-43 聚集体 |

**重要**：体内 PSD 的 FRAP 恢复比体外液滴慢得多（PSD-95 t₁/₂ ~25 分钟 vs 体外液滴秒级），提示体内 PSD 处于"凝胶样"而非真正液态。Chen et al. 2026 描述原生 PSD 为"凝胶样形态"——这是否意味着 PSD 不完全是 LLPS 的液态相？目前仍有争议（见未解问题 Q-llps-01）。

### 调控机制

- **磷酸化**：多个 IDR 内的磷酸化位点（如突触素的 S2/S3，SynGAP 的 CaMKII 靶点）能引入负电荷，破坏弱相互作用网络，溶解凝聚体
- **多价度改变**：三聚化（SynGAP）→ 二聚 → 单体：多价度下降导致相分离能力降低
- **局部浓度**：超过相分离临界浓度（saturation concentration, Csat）才会形成凝聚相；低于此浓度系统为均相

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 突触素 IDR 形成液态液滴 | 体外 DIC 显微镜 + FRAP（t₁/₂=65s 交换） + TKO 小鼠体内SV减少 | PMID:29976799 / PMC6191856 | 高 |
| CaMKII 磷酸化在 ~6 秒内溶解突触素液滴 | 体外磷酸化时间曲线（τ=5.9s） | PMID:29976799 | 高 |
| PSD-95/SynGAP 通过多价 PDZ 相互作用相分离 | 体外 LLPS + 截断实验（三聚体关键） | PMID:27565345 | 高 |
| 多蛋白 PSD 重建体富集受体、排除抑制性蛋白 | 支持膜双层上的 PSD 重建体系 | PMID:30078712 | 高 |
| 原生 PSD 为凝胶样凝聚体（Ca²⁺ 依赖重组） | 直接纯化小鼠脑原生 PSD + 荧光动力学 | PMID:41405989 | 中-高（2026 最新） |
| GluN2B-CTD 支持 LLPS；GluN2A-CTD 不支持 | 体外重组蛋白 LLPS 实验 + IDR 无序度分析 | PMID:36671389 | 中（体外，体内验证不足） |

## 连接

- [[postsynaptic-density]] — PSD 是 LLPS 在突触后的具体实现：PSD-95/SynGAP 凝聚体
- [[synapsin]] — 突触前的 LLPS 执行者：IDR 驱动的囊泡储备库
- [[ltp]] — LLPS/相变是 LTP 分子机制的物理框架（SynGAP 逸散 → Ras → AMPAR 插入）
- [[camkii]] — CaMKII 磷酸化是溶解/重组突触前/后 LLPS 的分子开关
- [[tdp-43-pathology]] — 正常 LLPS 失调 → 固态聚集 = 神经退行性疾病病理（ALS/FTD）
- [[nmda-receptor]] — GluN2B CTD 通过 LLPS 锚定于 PSD；GluN2A 不能（发育切换）
- [[ampa-receptor]] — AMPAR 由 LLPS 凝聚体（PSD-95）锚定于突触后膜

## 未解问题

- Q-llps-01（高优先级）：体内 PSD 是真正的液态凝聚体还是凝胶/玻璃态？FRAP 恢复时间 vs. 活性依赖重组——两者矛盾如何统一？是否存在从液到凝胶的亚结构梯度？
- Q-llps-02（中优先级）：在完整神经元内，如何用实时超分辨率成像直接观测单个树突棘 PSD 的 LLPS 动力学（而非纯化蛋白或固定样品）？

## 修订历史

- 2026-09-12 · 创建 · 基于《突触的自组装奥秘》文章（#142）· 初始置信度：高（LLPS 为主流机制；体内动力学争议登记为 Q-llps-01）

## 来源文章

- [[2026-09-12-liquid-liquid-phase-separation-postsynaptic-density]]

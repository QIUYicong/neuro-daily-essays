---
title: 突触后密度（PSD）
slug: postsynaptic-density
domain: concepts
type: structure
status: established
confidence: high
created: 2026-09-12
updated: 2026-06-28
revision_count: 2
dimensions: [molecular, synaptic, cellular]
related: [liquid-liquid-phase-separation, ltp, ampa-receptor, nmda-receptor, camkii, synaptic-transmission, synapsin, alzheimers-disease, arc-arg31, calcineurin, synaptic-tagging-capture, psd-95-scaffold, tarp-auxiliary-subunit]
prerequisites: [synaptic-transmission, ampa-receptor, nmda-receptor]
opens_questions: [Q-psd-01, Q-psd-02]
source_articles: [2026-09-12-liquid-liquid-phase-separation-postsynaptic-density]
key_sources: ["PMID:27565345", "PMID:30078712", "PMID:41405989", "PMID:36671389", "PMID:30599311"]
---

# 突触后密度（PSD, Postsynaptic Density）

> **一句话定义**：兴奋性突触后膜下的约 300–500 nm 宽、80 nm 厚的蛋白质富集区，由 PSD-95 为核心支架的多价多蛋白液态-凝胶相凝聚体构成，是 AMPAR/NMDAR 的锚定平台和突触可塑性的分子执行场所。

## 当前理解

我们现在认为，突触后密度（PSD）不是被膜隔离的细胞器，也不是精确装配的分子格架，而是通过液-液相分离（LLPS）维持的无膜蛋白质浓缩相。这一认识将 PSD 的两个表观矛盾特性统一解释：

- **高浓度**：PSD-95（丰度约 300 拷贝/PSD）、SynGAP、Shank、Homer、GKAP/SAPAP 等通过多价相互作用形成凝聚相，使这些蛋白质在 PSD 内的浓度比背景细胞质高 100–1000 倍
- **动态性**：凝聚相为液态或凝胶态，蛋白质仍可交换（PSD-95 FRAP t₁/₂ ~25 分钟）；LTP 诱导时 SynGAP 可在数秒内集体逸散重组

**核心蛋白质层级**：
- **MAGUK 层**（最近膜）：PSD-95/SAP102/PSD-93（3 个 PDZ + SH3 + GK 结构域），锚定于跨膜蛋白
- **SynGAP 层**：SynGAP 同源三聚体，通过 PDZ 结合基序与 PSD-95 多价结合（→LLPS），持续抑制 Ras
- **Shank-Homer 层**（远膜，约 40–80 nm）：Shank3 多聚体通过 Homer 连接 mGluR1/5，形成 PSD 的"外骨架"
- **受体层**：NMDA 受体（GluN2B CTD → PDZ）和 AMPA 受体（通过 TARP 与 PSD-95 PDZ）锚定于 MAGUK 层

2026 年 Chen & Zhang 直接纯化原生 PSD 证实，这些多蛋白体系在生理条件下形成"凝胶样凝聚体"，在 Ca²⁺/CaMKII 激活后发生选择性蛋白质招募和结构扩大（肌动蛋白聚合驱动）。

## 关键机制

### PSD 的形成（LLPS 机制）

**PSD-95/SynGAP 双组分核心**（Zeng et al. 2016）：
- SynGAP 形成同源三聚体（3 个 PDZ 结合基序）
- PSD-95 提供 3 个 PDZ 结构域
- 两者形成高度交联的多价网络 → 超过相分离临界浓度 → 浓缩液态相

**多蛋白扩展**（Zeng et al. 2018）：
加入 GKAP/SAPAP、Shank、Homer 后，多蛋白网络通过相分离在支持膜双层上形成 PSD 样凝聚体，额外实现：
- NMDA 受体胞内尾端富集
- 肌动蛋白聚合（Arp2/3 激活）→ 树突棘结构支撑
- 抑制性突触蛋白（Gephyrin）的排除

### LTP 中的 PSD 重组（相变控制）

1. **静息 PSD**：SynGAP 富集于凝聚相 → 持续 Ras-GAP 活性 → Ras-GTP 维持低水平 → AMPAR 低丰度
2. **LTP 诱导**（Ca²⁺ → CaMKII）：
   - CaMKII 磷酸化 SynGAP（多位点）→ 削弱 PSD-95 结合亲和力
   - SynGAP **集体从凝聚相逸散**（秒级）→ Ras 抑制解除
   - Ras-ERK 激活 → AMPAR 向 PSD 运输和插入
   - 同时：CaMKII 自身可能在 PSD 处形成凝聚体（突触标签）
   - 肌动蛋白聚合扩大 PSD（树突棘体积增大）

### 发育成熟（GluN2B → GluN2A 相态切换）

- **GluN2B 主导期（幼年）**：GluN2B CTD 支持 LLPS，PSD 液态性高，适合关键期快速可塑性
- **GluN2A 取代期（成熟）**：GluN2A CTD 不支持 LLPS，PSD 倾向凝胶/固态，关键期关闭，稳定性增强
- 这可能是关键期关闭的分子机制之一

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| PSD-95/SynGAP 通过多价相互作用形成 LLPS 凝聚相 | 体外 LLPS + FRAP + 截断实验（三聚体关键）| PMID:27565345 | 高 |
| 多蛋白 PSD 重建体富集受体、促进肌动蛋白、排除 Gephyrin | 支持膜双层 PSD 重建体系 | PMID:30078712 | 高 |
| 原生 PSD 为凝胶样凝聚体，Ca²⁺ 激活后重组 | 直接纯化小鼠脑原生 PSD | PMID:41405989 | 中-高（2026 最新）|
| GluN2B CTD 支持 LLPS，GluN2A CTD 不支持 | 体外蛋白相分离实验 + IDR 无序度分析 | PMID:36671389 | 中（体外）|

## 连接

- [[liquid-liquid-phase-separation]] — PSD 是 LLPS 在突触后的具体实现
- [[ltp]] — PSD 相变（SynGAP 逸散 → Ras → AMPAR）是 LTP 表达的分子平台
- [[ampa-receptor]] — AMPAR 通过 TARP 被 PSD-95 锚定于 PSD 凝聚相；LTP 时新 AMPAR 插入
- [[nmda-receptor]] — GluN2B CTD 通过 PDZ 与 PSD-95 相互作用，参与 LLPS；GluN2A 不参与
- [[camkii]] — CaMKII 是 PSD 相变的主要触发器（LTP 相关）
- [[synapsin]] — 突触前 LLPS 的对应物：同样是液态凝聚相，由 Ca²⁺/CaMKII 磷酸化溶解
- [[synaptic-tagging-capture]] — CaMKII 凝聚体可能作为突触标签物理基础
- [[alzheimers-disease]] — Aβ 寡聚体通过多条通路破坏 PSD 完整性（NMDAR/SynGAP/CaMKII），PSD 损坏是早期 AD 记忆障碍的突触底物

## 未解问题

- Q-psd-01（高优先级）：体内 PSD 是液态凝聚体（快速动态）还是凝胶/玻璃态（慢速稳定）？FRAP 数据（t₁/₂ ~25 min，接近凝胶）与活性依赖快速重组（SynGAP 秒级分散）如何共存？
- Q-psd-02（中优先级）：不同脑区和细胞类型的 PSD 相态是否有本质差异（CA1 PSD vs. 皮层 PSD vs. 纹状体 PSD）？E/I 平衡失调是否部分反映不同类型神经元 PSD 相变阈值的差异？

## 修订历史

- 2026-09-12 · 创建 · 基于《突触的自组装奥秘》文章（#142）· 初始置信度：高（结构维度 established；LLPS 机制维度 mainstream）
- 2026-06-28 · rev2 · 基于《PSD-95：突触权重的分子计数器》（#185）· 新增 [[psd-95-scaffold]] 和 [[tarp-auxiliary-subunit]] 连接

## 来源文章

- [[2026-09-12-liquid-liquid-phase-separation-postsynaptic-density]]
- [[2026-06-28-psd-95-scaffold-synaptic-slot]]

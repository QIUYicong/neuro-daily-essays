---
title: Cofilin-肌动蛋白轴（突触棘结构可塑性调控）
slug: cofilin-actin-spine
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-23
updated: 2026-09-23
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [dendritic-spine, ltp, camkii, actin-dynamics-spine]
prerequisites: [ltp, camkii, dendritic-spine]
opens_questions: [Q-spine-early-late-02]
source_articles: [2026-09-23-dendritic-spine-structural-plasticity]
key_sources: ["PMID:37290118", "PMID:41249054", "PMID:39158722", "PMID:19400723"]
---

# Cofilin-肌动蛋白轴（突触棘结构可塑性调控）

> **一句话定义**：LTP 诱导后，CaMKII 通过 Rac1/RhoA→LIMK→cofilin 磷酸化（Ser3 失活）路径减少 F-肌动蛋白的切割，驱动棘头内 F-肌动蛋白净聚合，产生突触棘头膨大；cofilin 是该分子级联的核心节点，其磷酸化状态决定了棘结构的可塑性方向。

## 当前理解

我们现在认为，cofilin 是突触棘内肌动蛋白动态的**主调控器**：

- 正常状态（低激活）：cofilin 活跃，切割 F-肌动蛋白，维持肌动蛋白快速周转（约 45 秒半衰期）和棘的运动性
- LTP 诱导后：LIMK 磷酸化 cofilin（Ser3 位点）→ cofilin 失活 → F-actin 切割减少 → 净聚合增加 → 棘头扩大
- LTD 诱导后：calcineurin/slingshot 磷酸酶去磷酸化 cofilin → cofilin 再激活 → F-actin 净解聚 → 棘收缩

这一双向机制使 cofilin 成为突触结构可塑性的**分子方向盘**——磷酸化（向增大）vs. 去磷酸化（向缩小）决定突触强化还是弱化的结构输出。

## 关键机制

### 上游激活路径（至 LIMK）

**路径 A（Rac1 分支）**：
- Ca²⁺/CaMKII → Tiam1/βPIX（GEF）→ Rac1-GTP → PAK1/2 → LIMK1/2 → cofilin（pSer3）
- 或：Rac1 可被直接光激活（不依赖 CaMKII），亦导致 LIMK 激活和棘扩大

**路径 B（RhoA 分支）**：
- Ca²⁺/CaMKII → GEF-H1/Lfc → RhoA-GTP → ROCK1/2 → LIMK1/2 → cofilin（pSer3）
- RhoA/ROCK 路径主要调控棘颈收缩和后期棘形态稳定

**路径 C（PI3K 分支）**：
- Ca²⁺/NMDAR → PI3K（p85α 亚基耦合到 PSD）→ PIP3 → PDK1/Akt → 抑制 GSK3β（cofilin 替代激酶）
- 或：PIP3 → Tiam1 → Rac1 → PAK → LIMK → cofilin

**三条路径在 LIMK 节点汇合**，共同维持 cofilin 失活和 F-actin 聚合的持续性。

### Cofilin 下游的肌动蛋白动态

1. **去磷酸化 cofilin（活性态）**：
   - 与 F-actin 结合 → 切断肌动蛋白丝（从1:1 肌动蛋白单体比例插入）
   - 增加 pointed end（负端）数量 → 加速解聚
   - 产生新的 barbed ends（正端）→ 短期内可促进重新聚合（"刺激-增殖效应"）

2. **磷酸化 cofilin（失活态，LTP 后）**：
   - 不与 F-actin 结合
   - 肌动蛋白丝切割减少
   - 既有 F-actin 丝稳定 + 新单体聚合到正端
   - 净结果：F-actin 总量增加，棘骨架扩张

3. **肌动蛋白聚合伴侣**：
   - Profilin 与 G-actin（球状）结合 → 催化 G-actin 添加到 F-actin 正端
   - LTP 后期 profilin 在棘内增加 → 驱动从头 F-actin 合成（晚期稳定阶段）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| LTP 诱导 15 min 时 cofilin pSer3 增加（与肌动蛋白周转减慢一致） | Western blot + FRAP | Bhatt et al. 2009, PMID:19400723 | 高 |
| Rac1 光激活（无 CaMKII 酶活性）→ 持续结构 LTP（F-actin 依赖） | 光遗传 Rac1 + latrunculin 对照 | Saneyoshi et al. 2025, PMID:41249054 | 高 |
| PI3K p85α 通过 cofilin 招募和 F-actin 聚合耦合 LTP 功能与结构 | PI3K 亚基敲除 | 2024 Cell Mol Life Sci, PMID:39158722 | 中（摘要读取） |
| CaMKII 综合调控 Rac1/RhoA GTPase（包括 GEF 激活） | 综合综述 | Nicoll & Schulman 2023, PMID:37290118 | 高 |

## 连接

- [[dendritic-spine]] — cofilin 轴是棘结构可塑性的核心分子机制
- [[ltp]] — LTP 诱导驱动 cofilin 磷酸化（失活）
- [[camkii]] — CaMKII 是 cofilin 失活的上游触发者（通过 GEFs/Rac1/RhoA）
- [[actin-dynamics-spine]] — cofilin 是肌动蛋白动态调控的核心蛋白

## 未解问题

- **Q-spine-early-late-02（高优先级）**：从早期动态 F-actin（cofilin 磷酸化主导）到晚期稳定 F-actin（profilin 合成依赖）的转变，其分子开关是什么？

## 修订历史

- 2026-09-23 · 创建 · 基于《记忆的雕塑家：树突棘如何用肌动蛋白重塑自身形状来固化一次学习》(#153) · 初始置信度：高

## 来源文章

- [[2026-09-23-dendritic-spine-structural-plasticity]]

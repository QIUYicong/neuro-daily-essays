---
title: D-丝氨酸
slug: d-serine
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-07-02
updated: 2026-07-02
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [astrocyte, tripartite-synapse, nmda-receptor, ltp, ltd, astrocyte-calcium-signaling, gliotransmitter]
prerequisites: [nmda-receptor, astrocyte]
opens_questions: [Q-astro-01]
source_articles: [2026-07-02-astrocyte-tripartite-synapse]
key_sources: ["PMID:20075918", "PMID:10322493"]
---

# D-丝氨酸 (D-Serine)

> **一句话定义**：NMDA 受体 GluN1 亚基"甘氨酸结合位点"的主要协同激动剂，在大脑皮层和海马中由星形胶质细胞中的丝氨酸消旋酶（serine racemase）合成，其钙依赖的释放量直接决定 NMDA 受体激活阈值，是 LTP 诱导的必要条件。

## 当前理解

我们现在认为，D-丝氨酸——而非甘氨酸（glycine）——是大脑皮层和海马 NMDA 受体功能的主要协同激动剂。传统教科书中甘氨酸占据的"第二把钥匙"位置，在大脑大部分区域实际上由 D-丝氨酸扮演。

**来源**：D-丝氨酸由丝氨酸消旋酶（serine racemase, SR）将 L-丝氨酸转化为 D-型对映体。SR 主要表达于星形胶质细胞（以及部分神经元），因此星形胶质细胞是 D-丝氨酸的主要生产源。

**释放控制**：Henneberger et al. 2010 的实验表明，星形胶质细胞 D-丝氨酸的释放依赖于 Ca²⁺ 信号（钳制 Ca²⁺ → LTP 消失；外源 D-丝氨酸恢复 LTP）。具体的释放机制仍在争议中：可能是囊泡胞吐、转运体逆转，或 VRAC 通道（Q-astro-01）。

**功能意义**：D-丝氨酸对 GluN1 协同位点的占用率直接决定 NMDA 受体对谷氨酸 + 去极化的响应幅度。低 D-丝氨酸 → NMDA 受体"部分激活" → LTP 诱导受损。这意味着突触 LTP 的阈值不只由突触两端神经元的活动决定，还取决于附近星形胶质细胞的钙信号状态。

## 关键机制

### NMDA 受体协同激动位点

NMDA 受体 GluN1 亚基上有一个与谷氨酸结合位点（GluN2）相独立的"协同激动位点"，在经典文献中称为"甘氨酸位点"。该位点必须被占用（甘氨酸或 D-丝氨酸结合），NMDA 受体才能被谷氨酸充分激活。在皮层和海马中，突触周边的 D-丝氨酸浓度决定该位点的占用率（未完全饱和），因此 D-丝氨酸是 NMDA 受体功能的可调控变量。

### 由星形胶质细胞 Ca²⁺ 信号门控

神经元高频活动 → 谷氨酸溢出激活 PAPs 的 mGluR → Ca²⁺ 升高 → D-丝氨酸释放增加 → NMDA 受体协同位点占用率上升 → LTP 诱导阈值降低。

这构成了一个**星形胶质细胞感知突触活动强度并"认证"突触是否具备 LTP 资格**的机制。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 星形胶质细胞 Ca²⁺ 信号通过 D-丝氨酸控制 LTP | 单细胞 Ca²⁺ 钳制；HOAsp 阻断 SR；外源 D-丝氨酸恢复 | PMID:20075918 (PMC2807667) | 高（Nature 因果实验） |
| D-丝氨酸而非甘氨酸是海马 NMDA 协同激动剂 | D-serine depletion 实验；SR KO 小鼠 | 多项研究（综述见 PMID:10322493）| 中-高 |
| NMDA 协同位点在体内未被完全饱和（受 D-丝氨酸供给调控） | 外源 D-丝氨酸增强 NMDA 响应 | PMID:20075918 | 高 |

## 连接

- [[nmda-receptor]] — D-丝氨酸是 GluN1 协同激动位点的主要内源性配体
- [[astrocyte]] — 主要生产和释放 D-丝氨酸的细胞
- [[astrocyte-calcium-signaling]] — Ca²⁺ 信号门控 D-丝氨酸的释放
- [[ltp]] — D-丝氨酸供给是 LTP 诱导的必要条件（Henneberger 2010）
- [[tripartite-synapse]] — D-丝氨酸是三方突触中最关键的胶质递质

## 未解问题

- Q-astro-01：D-丝氨酸的精确释放物理机制（囊泡胞吐 vs 转运体逆转 vs VRAC）

## 修订历史

- 2026-07-02 · 创建 · 基于《大脑的第三方》(#68) · 初始置信度：高（Henneberger 2010 因果证据；D-丝氨酸为主要协同激动剂的广泛共识）

## 来源文章

- [[2026-07-02-astrocyte-tripartite-synapse]]

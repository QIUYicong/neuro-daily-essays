---
title: 星形胶质细胞
slug: astrocyte
domain: systems
type: entity
status: established
confidence: high
created: 2026-07-02
updated: 2026-07-03
revision_count: 2
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, cognition, disease]
related: [tripartite-synapse, gliotransmitter, d-serine, astrocyte-calcium-signaling, glutamate-glutamine-cycle, ltp, ltd, nmda-receptor, synaptic-transmission, alzheimers-disease, synaptic-scaling, homeostatic-plasticity]
prerequisites: [synaptic-transmission, nmda-receptor, ltp]
opens_questions: [Q-astro-01, Q-astro-02, Q-astro-03]
source_articles: [2026-07-02-astrocyte-tripartite-synapse]
key_sources: ["PMID:10322493", "PMID:16025096", "PMID:20075918", "PMID:34334233", "PMID:30929313"]
---

# 星形胶质细胞 (Astrocyte)

> **一句话定义**：大脑中数量最多的胶质细胞亚型，通过高度分支的细小突起（PAPs）覆盖 ~57% 的海马兴奋性突触，主动参与突触传递、谷氨酸清除、D-丝氨酸供给和突触可塑性调控，是三方突触不可或缺的第三方参与者。

## 当前理解

我们现在认为，星形胶质细胞远非传统意义上的"脑的胶水"。它们是突触传递的主动第三方参与者，通过以下机制深度嵌入神经回路的功能：

1. **突触覆盖**：星形胶质细胞伸出数以万计的细小突起（perisynaptic astrocytic processes，PAPs），包裹突触外侧。海马 CA1 区约 57% 的兴奋性突触被 PAPs 部分或完全包绕（Zhou et al. 2019）。PAPs 的约 80% 的细胞膜面积是这些细小突起，而非细胞体。

2. **谷氨酸清除**：PAPs 表达高密度的谷氨酸转运体 EAAT2（GLT-1）和 EAAT1（GLAST），负责清除约 80% 的突触释放谷氨酸，防止兴奋性毒性（Volterra & Meldolesi 2005）。

3. **D-丝氨酸供给**：星形胶质细胞是大脑皮层和海马中 D-丝氨酸（NMDA 受体协同激动剂）的主要来源，通过钙依赖的释放机制供给突触间隙（Henneberger et al. 2010）。

4. **钙信号与胶质递质**：感知突触活动（谷氨酸溢出激活 mGluR），产生 IP₃-ER Ca²⁺ 信号，再释放胶质递质（D-丝氨酸、ATP、谷氨酸等）反向调控神经元活动。

5. **LTD 参与**：星形胶质细胞通过多条路径（D-丝氨酸、ATP/腺苷、胶质谷氨酸）参与不同脑区的 LTD，且在内源性大麻素介导的 LTD 中是必要中间节点（Durkee et al. 2021）。

**人类特异性**：人类星形胶质细胞比小鼠大 2.7 倍，每个细胞覆盖约 200 万个突触（小鼠约 10 万个），且拥有灵长类特有亚型（如 interlaminar astrocyte）。这种形态差异的功能意义尚不完全清楚（Q-astro-03）。

## 关键机制

### 1. 谷氨酸-谷氨酰胺循环（突触隔离与递质再生）

突触前释放谷氨酸 → 80% 由 EAAT2/GLT-1 摄取进入星形胶质细胞 → 谷氨酰胺合酶将谷氨酸转化为谷氨酰胺 → 谷氨酰胺转运体（SNAT3 等）输出 → 神经元摄取谷氨酰胺 → 谷氨酰胺酶重新合成谷氨酸 → 装入囊泡循环利用。

GLT-1 敲除小鼠出现自发性癫痫和神经元死亡——证明谷氨酸清除对脑功能绝对必要。

### 2. IP₃-Ca²⁺ 信号链（感知突触活动）

突触谷氨酸溢出 → 激活 PAPs 上 mGluR1/5 → Gq/PLC 激活 → IP₃ 产生 → IP₃R 开放（内质网 ER Ca²⁺ 释放）→ 细胞质 Ca²⁺ 升高 ~10 倍（振荡性）→ 激活下游效应器（释放胶质递质）。

钙信号还可通过 connexin43 缝隙连接在星形胶质细胞网络中以波速 15–27 μm/s 传播（Cornell-Bell et al. 1990）。

### 3. D-丝氨酸释放（NMDA 受体门控）

Ca²⁺ 升高 → 触发含 D-丝氨酸的囊泡（可能）胞吐或转运体逆转 → D-丝氨酸释放至突触间隙 → 结合 NMDA 受体 GluN1 亚基协同激动位点 → NMDA 受体激活阈值降低 → LTP 诱导得以完成。

单个星形胶质细胞 Ca²⁺ 钳制可消除其覆盖范围（<100 μm）内所有突触的 LTP（Henneberger et al. 2010）。

### 4. ATP/腺苷释放（网络状态调控）

星形胶质细胞释放 ATP → 胞外酶（CD73、ENPP）将 ATP 水解为腺苷 → A1 受体介导突触前神经递质释放减少（突触前抑制）→ 网络状态调控（尤其在睡眠稳态中重要）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 星形胶质细胞感知谷氨酸产生 Ca²⁺ 振荡和钙波 | Fluo-3 成像，培养海马星形胶质细胞 | PMID:1967852 | 高（多次重复） |
| 星形胶质细胞 Ca²⁺ 依赖释放的 D-丝氨酸是 LTP 的必要条件 | 单细胞 Ca²⁺ 钳制 + D-丝氨酸恢复实验，急性切片 | PMID:20075918 (PMC2807667) | 高（Nature 原始研究） |
| 星形胶质细胞参与 LTD（IP3R KO 损害 LTD 和行为记忆） | 条件性 IP3R 敲除小鼠 + 行为学 | PMID:34334233 (PMC8484065) | 中-高（综述汇总多个实验） |
| EAAT2/GLT-1 清除 ~80% 突触谷氨酸 | 放射性标记摄取 + GLT-1 KO 实验 | PMID:16025096 | 高（多重独立验证） |
| 海马 CA1 区 ~57% 突触被 PAPs 包裹 | 电子显微镜三维重建 | PMID:30929313 | 中-高（物种/脑区可能差异） |

## 连接

- [[tripartite-synapse]] — 星形胶质细胞是三方突触的第三方成员
- [[d-serine]] — 星形胶质细胞是 D-丝氨酸的主要来源，通过 Ca²⁺ 信号控制其释放
- [[astrocyte-calcium-signaling]] — 星形胶质细胞功能的核心信号机制
- [[gliotransmitter]] — 星形胶质细胞释放的活性调控分子
- [[glutamate-glutamine-cycle]] — 星形胶质细胞参与谷氨酸回收再生
- [[ltp]] — 星形胶质细胞 D-丝氨酸供给是 LTP 诱导的必要条件（Henneberger 2010）
- [[ltd]] — 星形胶质细胞通过三条路径参与 LTD（Durkee 2021）
- [[nmda-receptor]] — D-丝氨酸结合 NMDA 受体 GluN1 亚基，决定激活阈值
- [[synaptic-transmission]] — 参与突触信号的清除、调制和维持
- [[alzheimers-disease]] — 反应性星形胶质增生和 D-丝氨酸代谢受损可能加速 AD 突触功能损害
- [[synaptic-scaling]] — 星形胶质细胞释放的 TNFα 是突触稳态缩放长程维持的许可因子（Stellwagen & Malenka 2006，PMID:16547515）；说明星形胶质细胞同时参与 LTP（D-丝氨酸）和稳态调节（TNFα），在两个时间尺度上调控突触功能

## 未解问题

- Q-astro-01：D-丝氨酸从星形胶质细胞的精确释放机制（囊泡胞吐 vs 转运体逆转 vs VRAC）
- Q-astro-02：体内星形胶质细胞 Ca²⁺ 信号的激活阈值及其在不同脑状态下的变化
- Q-astro-03：人类星形胶质细胞（体积更大、覆盖突触更多）是否有不同于啮齿类的三方突触功能逻辑

## 修订历史

- 2026-07-03 · 修订 · 基于《突触稳态》(#69) · 在连接段落新增 synaptic-scaling；揭示星形胶质细胞在突触稳态中的第二重角色（TNFα 许可因子，与 D-丝氨酸在 LTP 中的门控角色形成双时间尺度分工）；related 新增 synaptic-scaling、homeostatic-plasticity
- 2026-07-02 · 创建 · 基于《大脑的第三方：星形胶质细胞如何改写突触的游戏规则》(#68) · 初始置信度：高

## 来源文章

- [[2026-07-02-astrocyte-tripartite-synapse]]
- [[2026-07-03-synaptic-scaling-homeostatic-plasticity]]

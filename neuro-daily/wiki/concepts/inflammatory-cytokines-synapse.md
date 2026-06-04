---
title: 炎症细胞因子对突触的损伤机制
slug: inflammatory-cytokines-synapse
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-10
updated: 2026-07-10
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [neuroinflammation, microglia, ltp, ltd, ampa-receptor, nmda-receptor, nf-kb, bdnf, glucocorticoid-hippocampus-plasticity]
prerequisites: [ltp, ampa-receptor, synaptic-transmission, neuroinflammation]
opens_questions: [Q-inflam-02]
source_articles: [2026-07-10-neuroinflammation-synaptic-damage]
key_sources: ["PMID:29861718", "PMID:30073573", "PMID:16626814", "PMID:23295855", "PMID:29458298", "PMID:20970492", "PMID:32579116"]
---

# 炎症细胞因子对突触的损伤机制 (Inflammatory Cytokines and Synaptic Damage)

> **一句话定义**：TNF-α、IL-1β 和 IL-6 在高浓度或慢性暴露时，分别通过 TNFR1/NF-κB（AMPA 受体内吞）、IL-1R1/p38 MAPK（GluA1 Ser831 去磷酸化 + NR2B 亚基减少）和 gp130/STAT3（Arc 异常激活 + BDNF 信号阻断）三条分子路径，系统性地损伤海马 LTP 的诱导与维持机制。

## 当前理解

我们现在认为，免疫细胞因子对突触可塑性的作用是严格**浓度依赖性**的，呈现倒 U 型（或双向）剂量-反应曲线：

- **低水平**（生理稳态）：TNF-α 和 IL-1β 等因子实际上**促进**LTP 和记忆巩固（通过 TNFR2/PI3K 增加 AMPA 受体表面表达，通过 IL-1R1 的基础信号支持 NMDA 受体功能）。IL-1RI KO 小鼠 LTP 受损——说明基线 IL-1β 信号是正常 LTP 所必需的。

- **高水平/慢性**（神经炎症）：同样这些因子通过**不同的受体和下游通路**转变为突触损伤者。这一浓度依赖的通路切换（TNFR2 → TNFR1 为主导；PI3K → NF-κB 为主导）是理解神经炎症突触损伤的核心逻辑。

这套机制与 #67（突触稳态缩放）中 Stellwagen & Malenka 2006 发现的 TNF-α 稳态功能形成对比：在稳态缩放中，星形胶质细胞分泌的低水平 TNF-α 在全局乘法性地上调 AMPA 受体——这是正常功能；神经炎症中高浓度小胶质细胞来源的 TNF-α 则局部内吞 AMPA 受体——这是病理状态。

## 关键机制

### TNF-α：浓度依赖的双重人格

| 浓度 | 主要受体 | 下游 | 突触效应 |
|------|--------|------|---------|
| 低（~1 ng/mL）| TNFR2 | PI3K/Akt | AMPA 受体（GluA2 缺失形式）表面表达↑ → LTP 增强 |
| 中（~10 ng/mL）| 混合 | 竞争 | 无显著净效应 |
| 高（~1 μg/mL，慢性）| TNFR1 | TRAF2→IKK→NF-κB | GluA1 内吞↑，PSD-95↓ → LTP 受阻 |

- TNFR1 信号激活 IκB 激酶（IKK），IKK 磷酸化 IκB → IκB 降解 → NF-κB p65/p50 二聚体核转位 → 促炎基因上调，PSD-95 等突触基因下调
- Aβ 通过诱导 TNF-α 分泌，再通过 TNFR1/IKK/NF-κB 抑制 LTP；英夫利西单抗（TNF 中和抗体）可恢复 LTP（PMID:29458298）
- 关键：高浓度 TNF 对 **LTP 诱导前**施用有损伤效果，对 **LTP 诱导后**施用无效——说明 TNF 损伤的是诱导机制而非维持机制（PMID:30073573）

**TREM2 变体与 TNF-α 的联系**（PMID:32579116）：
- TREM2 R47H（AD 高风险等位基因）小胶质细胞→ 即使无 Aβ 病理，也分泌过量 TNF-α
- 结果：兴奋性突触传递增强，但 LTP 容量下降（悖论！——基线兴奋增强 ≠ 可塑性增强）
- 抗 TNF-α 抗体处理后 LTP 恢复，直接证实是 TNF-α 依赖性

### IL-1β：AMPA 受体的三路"内吞促进剂"

**路径 A（突触后，直接受体修饰）**：
1. IL-1β → IL-1R1（突触后神经元）→ MyD88 → IRAK1/4 → TRAF6 → p38 MAPK（关键，不是 ERK）
2. p38 MAPK 磷酸化激活 → GluA1 的 Ser831 磷酸化水平**降低**（非 PKC 靶点的去磷酸化）
3. GluA1 内吞速率↑ → AMPA 受体表面密度减少 30–40%（PMID:16626814）
4. LTP 诱导时所需的 AMPA 受体"插入储备"减少 → LTP 幅度降低

**路径 B（NMDA 受体亚基选择性损伤）**：
- 在中枢炎症（非外周炎症）条件下，IL-1β 特异性减少海马 CA1 的 **NR2B 亚基**含量（PMID:23295855）
- NR2B（GluN2B）是 NMDA 受体慢衰减通道型，对 LTP 诱导的时间积分至关重要
- NR2B 减少 → LTP 诱导窗口收窄 → 相同刺激频率下 LTP 更难诱导
- 注意：NR2A 含量不受影响——这是对 NR2B 特异性的选择性损伤

**路径 C（突触前，谷氨酸释放减少）**：
- IL-1β → 减少海马神经元突触前谷氨酸释放量
- 突触前谷氨酸↓ → NMDA 受体激活不充分（Mg²⁺ 去除需要充分去极化）
- 同时 BDNF 表达减少（p38 → CREB 磷酸化减弱）→ L-LTP 维持减弱（PMID:23968970）

### IL-6：STAT3 介导的长期可塑性抑制

- IL-6 → gp130（共受体）/ IL-6Rα（经典或反式信号） → JAK1/2 → **STAT3** 磷酸化
- STAT3 核转位 → 靶基因激活：
  - Arc（即早基因）过度激活 → AMPA 受体非正常内吞（Arc 正常功能的病理化）
  - SOCS3（细胞因子信号抑制因子）上调 → 阻断 BDNF-TrkB 的 MAPK 信号 → L-LTP 维持减弱
- IL-6 的效果更持续（STAT3 是转录因子，效果需数小时到天），与 TNF/IL-1β 的急性效果互补

### 浓度依赖性的总结图谱

```
细胞因子浓度：
低（皮摩尔）─────→ 中（纳摩尔）─────→ 高（微摩尔）
    ↓                    ↓                    ↓
LTP 增强            无显著净效应          LTP 损伤
（TNFR2/PI3K）      （通路竞争）         （TNFR1/NF-κB）
（IL-1RI稳态）                          （IL-1RI/p38/GluA1内吞）
记忆巩固支持                            AMPA受体内吞
神经发生促进                            NR2B亚基减少
                                        BDNF信号阻断
                                        突触丢失
```

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| IL-1β 通过 p38 减少 GluA1 表面表达 | 海马神经元培养：IL-1β 处理24h后表面生物素化拉下，GluR1 表面量↓30-40%；IL-1Ra 或 p38 抑制剂逆转 | PMID:16626814（abstract only）| 高 |
| IL-1β 选择性减少 NR2B 但不影响 NR2A | 大鼠中枢炎症模型（海马内 LPS）：CA1 LTP 减弱；Western blot NR2B↓，NR2A 不变 | PMID:23295855（abstract only）| 中-高 |
| 高浓度 TNF 抑制 LTP 诱导（非维持） | 脑片：LTP 诱导前施用 TNF（μg/mL）→ HFS 诱导 LTP 减弱；LTP 诱导后施用无效 | PMID:30073573（abstract only）| 中 |
| Aβ 通过 TNF/NF-κB 抑制 LTP，抗 TNF 恢复 | 小鼠体内：Aβ→ LTP 抑制；英夫利西单抗（infliximab）→ LTP 恢复 | PMID:29458298（abstract only）| 中 |
| 多细胞因子协同阻断可塑性，IL-10 逆转 | 培养：LPS→TNF/IL-1β/IL-6/IFN-γ 综合升高→rMS 诱导可塑性丧失；IL-10→各细胞因子下降→可塑性恢复 | PMID:33391287（open）| 高 |
| TREM2 R47H→TNF-α↑→LTP 损伤 | 年幼大鼠（无 Aβ）：R47H→海马 TNF-α 升高；兴奋性传递增强，LTP 幅度降低；抗 TNF 抗体恢复 | PMID:32579116（eLife，open）| 高 |

## 连接

- [[neuroinflammation]] — 本页是神经炎症突触损伤的分子细节
- [[microglia]] — TNF-α、IL-1β、IL-6 的主要来源细胞
- [[ltp]] — 炎症细胞因子损伤 LTP 的靶机制
- [[ampa-receptor]] — GluA1 内吞是炎症损伤 LTP 的核心步骤
- [[bdnf]] — 炎症细胞因子阻断 BDNF-TrkB 信号，减弱 L-LTP 维持
- [[glucocorticoid-hippocampus-plasticity]] — 慢性 GC 与炎症细胞因子协同损伤海马 LTP（双重路径）
- [[nf-kb]] — TNF-α 高浓度效应的核心下游转录因子（待建页面）

## 未解问题

- Q-inflam-02：动物实验中用于损伤 LTP 的细胞因子浓度（通常 1–1000 ng/mL）远高于人类正常血清水平（皮克级别）。AD 脑内突触微环境的局部浓度是否真正达到损伤阈值？需要空间分辨率更高的细胞因子测量技术。

## 修订历史

- 2026-07-10 · 创建 · 基于《当卫士变成刽子手》(#78)；建立炎症细胞因子-突触损伤分子机制的独立节点；初始置信度：高

## 来源文章

- [[2026-07-10-neuroinflammation-synaptic-damage]]

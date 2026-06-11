---
title: 糖皮质激素与海马可塑性（MR/GR 双相调节）
slug: glucocorticoid-hippocampus-plasticity
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-09
updated: 2026-07-10
revision_count: 2
dimensions: [molecular, synaptic, cellular, brain-region, cognition, disease]
related: [hpa-axis, ltp, ltd, hippocampal-circuit, hippocampal-neurogenesis, bdnf, amyloid-beta-oligomers, alzheimers-disease, fear-conditioning, amygdala, circadian-clock, homeostatic-plasticity, neuroinflammation, microglia, inflammatory-cytokines-synapse]
prerequisites: [ltp, nmda-receptor, ampa-receptor, hippocampal-circuit, hpa-axis]
opens_questions: [Q-stress-01, Q-stress-02, Q-stress-03]
source_articles: [2026-07-09-stress-glucocorticoid-hippocampus-hpa-axis]
key_sources: ["PMID:15891777", "PMID:26286651", "PMID:19317179", "PMID:26741493", "PMID:10195112", "PMID:3527687"]
---

# 糖皮质激素与海马可塑性（MR/GR 双相调节）
# (Glucocorticoid Regulation of Hippocampal Plasticity)

> **一句话定义**：皮质醇通过高亲和力矿物皮质激素受体（MR，Kd≈0.5 nM）和低亲和力糖皮质激素受体（GR，Kd≈5 nM）的竞争性激活，实现"低浓度 MR 主导→LTP 增强/神经元存活"和"高浓度 GR 主导→LTP 受损/树突退缩/神经发生抑制"的双相调节，构成应激激素在海马的分子双刃剑效应。

## 当前理解

我们现在认为，糖皮质激素（GCs）对海马突触可塑性的调节是一个**双受体浓度依赖性双相系统**，而非简单的"应激→损害"关系：

**MR 主导相（基础/低浓度）**：在清晨皮质醇峰值和超日节律脉冲期间，高亲和力 MR 被优先占据。MR 激活通过非基因组路径（膜相关 MR，数分钟内效果）迅速增加 AMPA 受体膜表面表达和突触传递效能，通过基因组路径（数小时）维持神经元兴奋性和 BDNF 表达。净效果：LTP 诱导阈值降低，海马记忆编码效率提高。

**GR 主导相（急性应激高浓度）**：应激引起皮质醇急速升高至 GR 激活阈值。GR 激活启动"聚焦巩固"模式：快速非基因组 GR 信号（内源性大麻素/eCB 合成→逆行 CB1R→GABA 抑制神经元去抑制→短时兴奋↑）联合 NE（蓝斑→β-AR）放大当前威胁性情景记忆。基因组路径（数小时）则抑制竞争性无关记忆回路。**时间和空间特异性原则**（Joëls 2006）：GR 激活只有在应激时间窗内（±30分钟）且作用于当前激活的编码回路时，才增强记忆；否则产生干扰。

**慢性 GR 过激活相**：持续数周的高皮质醇导致 GR 基因组效应积累：BDNF exon IV 启动子抑制→BDNF 蛋白↓；GluA1 内吞增加（PP2B/calcineurin 上调，与 LTD 路径共用）；CaMKII 自磷酸化受抑；CRH 局部毒性（Ca²⁺ 过载）。形态学后果：CA3 顶端树突退缩（非死亡，可逆），DG 神经发生抑制（SGZ 干细胞增殖↓40-50%），CA3→CA1 传递效能下降，空间记忆损害。

**糖皮质激素级联**（Sapolsky 1986→ Conrad 2008 修正）：慢性 GC 损害海马→海马对 HPA 轴负反馈减弱→皮质醇持续升高→进一步损害海马的正反馈循环。Conrad 修正版：主要是可逆树突退缩（脆弱化），而非直接杀死细胞；脆弱窗口内如叠加额外损伤（缺血/炎症/Aβ），才导致不可逆损伤。

## 关键机制

### MR/GR 受体系统

| 特征 | MR（I 型） | GR（II 型） |
|------|----------|------------|
| 亲和力（皮质酮） | Kd ≈ 0.5 nM（高亲和力） | Kd ≈ 5 nM（低亲和力，约 1/10 MR）|
| 基础皮质醇时占用率 | ~70-90% | ~10% |
| 急性应激时额外占用 | 接近饱和 | 大量激活 |
| 海马主要表达 | CA1/CA2/DG（丰富）| 全海马（均匀）|
| 快速非基因组效应 | AMPA 受体上调，mEPSC↑ | eCB/CB1R 去抑制 |
| 基因组效应方向 | 促 LTP，促神经元存活 | 急性：聚焦巩固；慢性：损害 |
| 选择性激动剂（实验） | 醛固酮、fludrocortisone | DEX（地塞米松）|

### 非基因组快速路径（分钟）

膜相关 MR 激活（Sarabdjitsingh 2016 直接电生理证据）：
- 脉冲皮质酮→膜 MR→GS/cAMP→AMPA 受体 GluA1 Ser831 磷酸化→AMPA 表面表达↑→mEPSC 频率和幅度↑
- 膜 GR→花生四烯酸→内源性大麻素（2-AG/AEA）→逆行 CB1R→突触前 GABA 释放↓→去抑制→突触传递↑

### 基因组路径——LTP 影响（小时-天）

**促 LTP（MR 主导）**：
- CREB 磷酸化→BDNF 转录→TrkB 信号→突触强化
- 增加 GluA1 mRNA→AMPA 受体总量↑
- 维持正常 CaMKII 自磷酸化水平

**损害 LTP（慢性 GR）**：
- GR 结合 BDNF exon IV GRE 负调控元件→BDNF mRNA↓30-50%
- PP2B（钙调磷酸酶）表达↑→GluA1 Ser845 去磷酸化→AMPA 内吞↑（与 LTD 共用 calcineurin 路径）
- CaMKII α 亚基表达↓→LTP 诱导阈值升高，LTP 幅度减小

### CA3 树突退缩的细胞机制

21 天慢性应激/皮质酮后的 CA3 形态学变化（Conrad 2008，开放全文）：
1. **NMDA 受体过激活**：高皮质醇→突触谷氨酸积累增多（GLT-1/EAAT2 功能下调）→NMDA 持续激活→Ca²⁺ 过载→树突收缩
2. **局部 CRH 毒性**：海马中间神经元释放局部 CRH，通过 CRH-R1 激活→PKC/IP₃→Ca²⁺ 释放→树突棘丢失
3. **结构蛋白降解**：Ca²⁺ 过载→calcineurin 激活→MAP2 去磷酸化→微管稳定性↓→树突退缩
- 退缩在应激结束后 4 天内仍持续，约 10 天后恢复（可逆）
- CA3 更易受损（接受苔状纤维高频输入）；CA1 较 CA3 有一定延迟

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| MR 激活增强海马 LTP，GR 激活降低 LTP/增加 LTD | 选择性激动剂（醛固酮 vs DEX）海马切片 LTP 实验；KO 小鼠 | 多实验室（综述于 PMID:26286651）| 高 |
| 第一次皮质酮脉冲快速增加 mEPSC 和 AMPA 受体表面表达 | 体外海马培养；mEPSC 电生理 + 荧光标记 AMPA 受体 | PMID:26741493（开放全文）| 中-高 |
| 21 天慢性应激→CA3 顶端树突退缩（可逆） | Golgi 染色；树突追踪；退缩→苯妥英阻断→脆弱性消除 | PMID:19317179（开放全文）| 高 |
| 慢性皮质酮→体内树突棘翻转率增加（数小时） | 双光子活体成像；P30 鼠皮层 | PMID:21911374（开放全文）| 高 |
| 人类皮质醇升高（5年）预测海马萎缩+记忆损害 | MRI 体积测量；神经心理学测试；5 年纵向 | PMID:10195112 | 高 |
| 抑郁持续时长（非年龄）预测海马体积损失 | MRI；N=62；控制年龄因素 | PMID:10366636（开放全文）| 高 |
| Cushing 综合征：皮质醇↑与海马体积负相关；手术后恢复 | MRI + 血清皮质醇；纵向随访 | PMID:1450290 | 高 |
| PTSD：双侧海马缩小约 6.7% | Meta-analysis 13 项研究 n=215 | PMID:15988763 | 高 |

## 连接

- [[ltp]] — MR 激活增强 LTP；慢性 GR 激活损害 LTP（GluA1 内吞，BDNF 下调）
- [[ltd]] — GR→PP2B→GluA1 去磷酸化 = 与 LTD 共用 calcineurin/AMPA 内吞路径
- [[bdnf]] — 慢性 GR 激活通过 GRE 负调控元件抑制 BDNF 转录（BDNF 是 LTP 的关键催化分子）
- [[hippocampal-neurogenesis]] — 慢性 GC 通过抑制 VEGF/IGF-1/5-HT 通路减少 SGZ 增殖，是成体神经发生抑制的主要机制之一
- [[hippocampal-circuit]] — CA3 是 GC 损害最早的节点（苔状纤维-CA3 突触）
- [[hpa-axis]] — 海马 GR 激活提供 HPA 轴的负反馈；海马损伤→负反馈减弱→级联放大
- [[amygdala]] — 慢性应激同时增强杏仁核反应性（BLA 树突增长）vs 削弱海马——方向性分离
- [[homeostatic-plasticity]] — 慢性 GC 损害稳态可塑性（突触缩放所依赖的 TNFα 和 BDNF 通路均受 GC 影响）
- [[alzheimers-disease]] — GC 级联假说：AD 早期 SCN 退化→皮质醇节律崩溃→慢性高 GC→海马损伤→负反馈减弱→进一步升高
- [[circadian-clock]] — 皮质醇昼夜节律由 SCN 调控；SCN 退化（AD）破坏 MR/GR 系统的节律性工作模式
- [[neuroinflammation]] — 慢性应激/皮质醇通过 CRH 激活和 GR 耐受使小胶质细胞"预激"，构成 HPA 轴→神经炎症→突触损伤的间接损伤路径（补充 GC 直接路径之外的第二条机制）
- [[microglia]] — CRH-R1 在小胶质细胞表面表达；慢性 GC 暴露后小胶质细胞对 Aβ 刺激的炎症应答增强 2–5 倍（预激状态）
- [[inflammatory-cytokines-synapse]] — 预激小胶质细胞分泌的 TNF-α/IL-1β 通过与慢性 GC 相同的 GluA1 内吞路径损伤 LTP，两条路径在分子层面有协同效应

## 未解问题

- Q-stress-01：慢性应激海马损伤的可逆性边界——Cushing 恢复 10%、PTSD 部分恢复，但持续时间和叠加 Aβ 的可逆性未知
- Q-stress-02：慢性压力是否在 AD 之前就已启动海马萎缩（因），还是 AD 病理本身引起皮质醇升高（果）？
- Q-stress-03：慢性 GC 是否首先通过损伤 PV+ 中间神经元（破坏 E/I 平衡）间接损害海马 LTP，而非直接作用于锥体细胞？

## 修订历史

- 2026-07-09 · 创建 · 基于《应激的双刃剑：糖皮质激素如何让海马在压力下先锐化、后崩溃》(第 77 篇) · 初始置信度：高
- 2026-07-10 · 修订 · 基于《当卫士变成刽子手》(第 78 篇) · 补充慢性应激→小胶质细胞预激→神经炎症的间接损伤路径；新增连接节点 [[neuroinflammation]]、[[microglia]]、[[inflammatory-cytokines-synapse]]

## 来源文章

- [[2026-07-09-stress-glucocorticoid-hippocampus-hpa-axis]]
- [[2026-07-10-neuroinflammation-synaptic-damage]]

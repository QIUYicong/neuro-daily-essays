---
title: 小胶质细胞
slug: microglia
domain: neurons
type: entity
status: established
confidence: high
created: 2026-06-03
updated: 2026-07-10
revision_count: 2
dimensions: [cellular, synaptic, microcircuit, brain-region, disease]
related: [synaptic-pruning, complement-cascade-cns, tripartite-synapse, astrocyte, trem2, neuroinflammation, inflammatory-cytokines-synapse, alzheimers-disease, hpa-axis, ltp]
prerequisites: [action-potential, synaptic-transmission, complement-cascade-cns]
opens_questions: [Q-microglia-01, Q-microglia-02, Q-inflam-01, Q-inflam-02, Q-inflam-03, Q-inflam-04]
source_articles: [2026-06-03-microglia-synaptic-pruning, 2026-07-10-neuroinflammation-synaptic-damage]
key_sources: ["PMID:22632727", "PMID:18083105", "PMID:34738335", "PMID:20970492", "PMID:29861718", "PMID:36482444", "PMID:37575021", "PMID:29563239", "PMID:29992181", "PMID:32579116"]
---

# 小胶质细胞 (Microglia)

> **一句话定义**：小胶质细胞是中枢神经系统唯一真正意义上的常驻免疫细胞，在发育期通过补体（CR3/C3b）和磷脂酰丝氨酸（TREM2/PtdSer）信号物理剪枝弱突触，在成年稳态下以低水平细胞因子主动支持 LTP，在病理激活态则分泌大量 TNF-α/IL-1β/IL-6 系统性损伤突触可塑性——同一细胞族群在不同激活状态下扮演截然相反的角色。

## 当前理解

我们现在认为，小胶质细胞远不只是大脑的"免疫卫士"。它们是突触生命周期全程的主动参与者，具有双重身份：

**发育期**：作为**突触剪枝的执行者**，小胶质细胞通过识别补体标记（C3b→CR3）和磷脂酰丝氨酸（PtdSer→TREM2）的弱/沉默突触，物理吞噬并降解多余的突触连接，雕刻出功能神经回路。这一过程对突触活动水平敏感——活跃突触的"别吃我"信号（CD47）抑制吞噬，沉默突触则暴露出多重"吃我"信号。

**成年稳态期**：小胶质细胞通过 CX3CL1-CX3CR1 轴与神经元持续沟通，以低水平细胞因子（低浓度 TNF-α via TNFR2/PI3K、基础 IL-1β via IL-1RI）积极**支持** LTP 和记忆。IL-1RI KO 小鼠 LTP 减弱，证明基线免疫信号是可塑性必需的。

**病理激活期**：慢性炎症刺激或 Aβ 寡聚体可将小胶质细胞推入高激活态，细胞因子分泌量增加数十至数百倍，通过 TNFR1/NF-κB、IL-1R1/p38 MAPK 等路径内吞 AMPA 受体、降低 NR2B 亚基、阻断 BDNF 信号，系统性**损伤** LTP。

小胶质细胞起源于胚胎期卵黄囊中的祖细胞，脑实质建立后不被外周免疫细胞替代（除非 BBB 受损）。它们约占成年脑细胞总数的 5–15%，在不同脑区的密度和功能状态存在区域异质性（背侧 vs 腹侧海马小胶质细胞 LTP 调节方向相反，Maggi et al. 2022）。

## 关键机制

### 发育期突触剪枝

**补体-CR3 通路**：
1. 发育期神经元（受星形胶质细胞 TGF-β 诱导）合成并分泌 C1q
2. C1q 结合突触膜配体，激活 C4 → C3 转化酶
3. C3 转化酶将 C3 裂解为 C3b（共价结合到突触膜作为调理素）
4. 小胶质细胞 CR3（CD11b/CD18）识别 C3b-标记突触 → 吞噬体形成 → 突触末梢被降解

**PS-TREM2 通路**（并行）：
1. 弱突触前膜 scramblase 激活 → PtdSer 从内层翻转至外层
2. 小胶质细胞 TREM2 识别暴露的 PtdSer → 触发吞噬
3. PtdSer 暴露与 C1q 沉积在同一批突触上共定位，两条通路协同放大

**活动依赖机制**：
- 活跃突触：CD47 丰度高 → 与 SIRPα 结合 → 抑制吞噬（"别吃我"信号占优）
- 沉默突触：CD47 低 + C3b 标记 + PtdSer 暴露 → 多重"吃我"信号叠加 → 优先删除
- 直接证据：TTX 封闭单眼 → 该眼突触优先被小胶质细胞吞噬；forskolin 增强活动 → 突触受保护（Schafer et al. 2012）

### 成年稳态功能

**持续巡逻与突触监测**：
- 静息态（ramified）小胶质细胞伸展密集树突状突起，以约 1–2 小时/全脑速度持续巡逻
- 每隔约 5 分钟与脑内每个突触接触一次（双光子活体成像证实）
- 突起末端持续采样 ATP/ADP（P2Y12）、CX3CL1（CX3CR1）等信号

**CX3CL1-CX3CR1 轴**：
- 神经元活动时分泌 CX3CL1（fractalkine）→ 小胶质细胞 CX3CR1 感知
- CX3CR1-KO 小鼠背侧 CA1 LTP 减弱，腹侧 CA1 变化方向相反——说明小胶质细胞正常在场是区域特异性突触可塑性所必需的（PMID:36482444）

**低水平细胞因子的促塑性作用**：
- 低浓度 TNF-α（~1 ng/mL）→ TNFR2/PI3K → GluA1（含 GluA2 缺失形式）表面表达↑ → LTP 增强
- 低浓度 IL-1β → IL-1RI 基础信号 → 支持 LTP 巩固（IL-1RI KO → LTP 受损）
- 低水平 IL-1β 和 TNF-α 均促进海马神经发生（PMID:20970492）

### 激活态细胞因子损伤

（分子细节详见 [[inflammatory-cytokines-synapse]]）

**TNF-α（高浓度，~1 μg/mL）**：
- TNFR1/TRAF2/IKK/NF-κB → GluA1 内吞↑，PSD-95 下调
- Aβ 诱导 TNF-α 分泌，英夫利西单抗可恢复 LTP（PMID:29458298）
- 关键：仅对 LTP **诱导前**施用有效，诱导后施用无效

**IL-1β（高浓度）**：
- IL-1R1/p38 MAPK → GluA1 Ser831 去磷酸化 → GluA1 内吞（↓30-40%）
- 特异性减少 NR2B 亚基（NR2A 不变）→ NMDA 诱导窗口收窄
- 减少突触前谷氨酸释放 + BDNF 表达（PMID:23968970）

**IL-6（高浓度）**：
- gp130/JAK2/STAT3 → Arc 过激活（AMPA 内吞）+ BDNF-TrkB 信号阻断

### 疾病相关小胶质细胞（DAM）与 TREM2

在阿尔茨海默病中，小胶质细胞逐步过渡到 DAM 状态：
- **DAM-1**（TREM2 非依赖）：TREM2 表达量开始上调，IL-1β/TNF-α 分泌增加
- **DAM-2**（TREM2 依赖）：TREM2 大量表达，吞噬活性全面增强

**TREM2 的双重角色**：
- 早期保护性：识别 Aβ 诱导的 ePtdSer 暴露 → 吞噬过活跃突触 → 防止兴奋毒性（Rueda-Carrasco et al. 2023, PMID:37575021）
- TREM2 LOF 变体（R47H, T96K）→ 过活跃棘蓄积 → 兴奋毒性风险↑；人类 AD 脑验证

**TREM2 R47H 与 TNF-α 的联系**（PMID:32579116）：
- R47H 小鼠（无 Aβ）→ TNF-α 持续升高 → LTP 幅度降低
- 抗 TNF-α 抗体恢复 LTP，直接证实 TNF 依赖性

### 慢性应激诱发的小胶质细胞预激

（详见 [[hpa-axis]] 和 [[glucocorticoid-hippocampus-plasticity]]）
- CRH → 脑膜肥大细胞（CRH-R1）→ 预激小胶质细胞（先遣队反应）
- 慢性 GC 暴露 → 小胶质细胞对 Aβ 刺激的 TNF-α/IL-1β 反应增强 2–5 倍
- 这一预激状态是 HPA 轴慢性激活→AD 风险的中间机制

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 小胶质细胞物理吞噬完整突触末梢 | 电子显微镜：溶酶体内发现完整突触结构 | PMID:22632727 | 高 |
| CR3/C3 通路是主要剪枝机制之一 | CR3 KO → 吞噬容量减少 50%；C3 KO → 视网膜-膝状核分离失败 | PMID:22632727, 18083105 | 高 |
| TTX 封闭 → 优先吞噬沉默眼突触 | 单眼 TTX 注射 + 荧光示踪 + 共聚焦 | PMID:22632727 | 高 |
| TREM2 识别 PtdSer 是并行剪枝通路 | TREM2 KO → 海马突触密度升高；Annexin V 屏蔽 PtdSer → 剪枝减少 | PMID:32657463 | 中高 |
| AD 中 C1q 在突触上病理性重激活 | AD 小鼠 1 月龄 C1q↑（早于斑块）；抗 C1q → 突触保护 | PMID:27033548 | 高 |
| 低水平细胞因子促进 LTP | IL-1RI KO 小鼠 LTP 减弱；IL-1ra 低剂量阻断 LTP 巩固 | PMID:20970492（综述）| 中-高 |
| CX3CR1 缺失改变区域性 LTP | CX3CR1-KO 小鼠背侧/腹侧 CA1 LTP 幅度双向改变 | PMID:36482444 | 高 |
| TREM2 通过 PtdSer 清除过活跃突触 | hAPP NL-F 小鼠：ePtdSer 暴露棘被 TREM2 依赖性吞噬；TREM2 R47H 人脑验证 | PMID:37575021 | 高 |
| TREM2 R47H → TNF-α↑ → LTP 受损 | 年幼 TREM2 R47H 鼠（无 Aβ）→ TNF-α 升高 + LTP 减弱；抗 TNF 抗体恢复 | PMID:32579116 | 高 |
| 慢性应激 → 小胶质细胞预激 → AD 风险 | 慢性压力小鼠：IL-1β/TNF-α 反应幅度增强；Aβ 刺激后炎症放大 | PMID:29992181（综述）| 中 |

## 连接

- [[synaptic-pruning]] — 小胶质细胞是突触剪枝的主要执行细胞
- [[complement-cascade-cns]] — C1q→C3b→CR3 补体标记系统由小胶质细胞执行
- [[tripartite-synapse]] — 星形胶质细胞通过 TGF-β 上调神经元 C1q 表达，触发小胶质细胞剪枝
- [[astrocyte]] — 与星形胶质细胞的跨细胞协调（TGF-β 诱导 C1q，TNF-α 稳态合作）
- [[trem2]] — 磷脂酰丝氨酸识别受体；AD 风险基因；DAM 转变的关键分子
- [[neuroinflammation]] — 小胶质细胞是神经炎症的核心执行者和主要细胞因子来源
- [[inflammatory-cytokines-synapse]] — TNF-α/IL-1β/IL-6 损伤 LTP 的分子细节
- [[alzheimers-disease]] — 小胶质细胞在 AD 中兼具保护性（清除 Aβ、早期 TREM2 功能）和损伤性（炎症）角色
- [[hpa-axis]] — 慢性应激通过 GC/CRH 使小胶质细胞"预激"
- [[ltp]] — 小胶质细胞低水平激活支持 LTP；过度激活系统性损伤 LTP
- [[pv-interneurons]] — 精神分裂症中 PV+ 细胞与 C4A 过度剪枝有关联（待深入）

## 未解问题

- Q-microglia-01（高优先）：弱突触如何精确获得 C1q 标记？PtdSer 外翻的上游触发器是否是 LTD 相关的 caspase-3 激活？
- Q-microglia-02（中优先）：成年大脑中小胶质细胞是否持续参与突触的动态维护？其与记忆固结（SWR 期间）的关系？
- Q-inflam-01：小胶质细胞预激的可逆性边界（慢性压力解除后能否恢复基线激活阈值？）
- Q-inflam-02：损伤 LTP 的炎症细胞因子阈值在人脑局部突触微环境中是否真正达到？需要空间分辨率更高的细胞因子测量技术。
- Q-inflam-03：TREM2 激动剂在 AD 早期阶段是否能保护突触（早期人类证据缺乏）？
- Q-inflam-04：炎症细胞因子是否优先损伤 PV+ 中间神经元，通过 E/I 失衡间接损伤 LTP？

## 修订历史

- 2026-06-03 · 创建 · 基于《大脑的"质检员"》(#70) · 核心：发育期补体依赖突触剪枝机制；初始置信度：高
- 2026-07-10 · 修订 · 基于《当卫士变成刽子手》(#78) · 新增：成年稳态低水平细胞因子促可塑性、激活态 TNF-α/IL-1β/IL-6 损伤 LTP、TREM2/DAM 机制、慢性应激诱发小胶质细胞预激；扩展 related、opens_questions、key_sources；合并来自 wiki/systems/microglia.md 的内容

## 来源文章

- [[2026-06-03-microglia-synaptic-pruning]]
- [[2026-07-10-neuroinflammation-synaptic-damage]]

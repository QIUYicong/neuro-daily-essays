---
title: 神经炎症（中枢神经系统）
slug: neuroinflammation
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-10
updated: 2026-07-10
revision_count: 1
dimensions: [molecular, cellular, synaptic, brain-region, disease, cognition]
related: [microglia, astrocyte, inflammatory-cytokines-synapse, synaptic-pruning, complement-cascade-cns, alzheimers-disease, hpa-axis, glucocorticoid-hippocampus-plasticity, ltp, bdnf]
prerequisites: [microglia, astrocyte, synaptic-transmission]
opens_questions: [Q-inflam-01, Q-inflam-02, Q-inflam-03, Q-inflam-04]
source_articles: [2026-07-10-neuroinflammation-synaptic-damage]
key_sources: ["PMID:20970492", "PMID:29861718", "PMID:29992181", "PMID:42092480", "PMID:29302258"]
---

# 神经炎症（中枢神经系统）(Neuroinflammation)

> **一句话定义**：神经炎症是大脑对损伤、感染或病理蛋白（如 Aβ 寡聚体）的免疫反应，以小胶质细胞和星形胶质细胞激活、促炎细胞因子（TNF-α、IL-1β、IL-6）分泌为核心特征；低水平生理性神经炎症支持突触可塑性，而慢性或过度的神经炎症则系统性地损伤 LTP、促进突触丢失，是阿尔茨海默病等神经退行性疾病的早期驱动力。

## 当前理解

我们现在认为，神经炎症（neuroinflammation）与免疫学中经典的"炎症"概念既有联系也有本质区别。脑内神经炎症的关键特征：

**双向性**：
- **生理性神经炎症**（低水平）：必要的、支持认知的。CX3CL1-CX3CR1 介导的小胶质细胞-突触通讯，低浓度 IL-1β/TNF-α 增强 LTP，小胶质细胞分泌 BDNF 支持记忆巩固。这是"恰好合适的免疫稳态"。
- **病理性神经炎症**（高水平/慢性）：破坏性的、损伤突触的。炎症细胞因子浓度上升数十到数百倍，通过三条分子路径（AMPA 受体内吞、NR2B 减少、NF-κB 激活）瓦解 LTP 的分子基础。

**脑内特异性**：
- 血脑屏障（BBB）在正常状态下限制外周炎症信号进入大脑
- 脑内神经炎症通常在受损区域**局部启动**，由小胶质细胞和星形胶质细胞驱动
- 与外周炎症相比，神经炎症消退更慢（小胶质细胞半衰期长，炎症记忆持久）

**慢性应激的中介作用**：
- 长期应激（HPA 轴/GC/CRH）使小胶质细胞进入"预激"（priming）状态
- 预激状态：形态上静息，但反应阈值降低，对 Aβ 等后续刺激的炎症应答超量
- 这是连接心理社会应激与神经退行性疾病风险的关键分子链接（PMID:29992181）

## 关键机制

### 1. 诱发因素与激活信号

**内源性激活物（PAMPs/DAMPs 类）**：
- Aβ 寡聚体（AD 早期）→ TLR4/RAGE → 小胶质细胞激活
- 磷酸化 tau → 小胶质细胞和星形胶质细胞激活
- HMGB1（损伤-相关分子模式）→ TLR4 → 神经炎症
- ATP（来自受损神经元）→ P2X7R → NLRP3 炎症体激活 → IL-1β 成熟

**外源性信号（通过 BBB 受损或间接路径）**：
- 慢性全身性炎症 → 迷走神经→NF-κB → 脑内细胞因子升高
- CRH 直接激活小胶质细胞（小胶质细胞表面表达 CRH-R1）
- 慢性皮质醇 → GR 耐受 → 正常抗炎功能减弱 → 微胶质细胞预激

### 2. 核心执行细胞

**小胶质细胞**（主要执行者）：
- M1 样激活（促炎）：TNF-α、IL-1β、IL-6、ROS、NO 大量分泌
- DAM（疾病相关）：TREM2↑、ApoE↑、吞噬基因↑、稳态基因↓（见 [[microglia]]）

**星形胶质细胞**（A1 反应性）：
- 被激活小胶质细胞分泌的 TNF-α、IL-1α 和 C1q 诱导转变为 A1 表型
- A1 星形胶质细胞补体表达↑，神经营养因子↓，具有神经毒性
- 干扰突触旁的谷氨酸转运体（GLT-1/EAAT2）→ 突触间隙谷氨酸清除减慢 → 兴奋毒性风险

### 3. 炎症细胞因子对突触的损伤路径

（详见 [[inflammatory-cytokines-synapse]]）

简述：
- **TNF-α 高浓度**：TNFR1/NF-κB → GluA1 内吞↑ → AMPA 受体减少
- **IL-1β**：p38 MAPK → GluA1 Ser831 磷酸化减少 → 内吞↑；NR2B 亚基选择性减少
- **IL-6**：STAT3/Arc 过度激活 → AMPA 受体内吞，BDNF 信号阻断

### 4. 慢性应激→神经炎症→突触损伤链

```
慢性心理社会应激
    ↓
下丘脑分泌 CRH → 直接激活小胶质细胞（CRH-R1）
    +
垂体 ACTH → 肾上腺皮质 → 皮质醇（GC）
    ↓（慢性 GR 耐受）
小胶质细胞"预激"状态（阈值降低）
    ↓（遇到 Aβ 或其他刺激）
超量 TNF-α、IL-1β → AMPA 受体内吞、NR2B 减少
    ↓
LTP 损伤 → 记忆编码受损
    ↓（慢性持续）
突触丢失 → 认知减退 → AD 风险增加
```

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 低水平 IL-1β 促进 LTP，高水平损伤 | 倒 U 型剂量-反应曲线；IL-1RI KO LTP 受损 | PMID:20970492 综述 | 中-高 |
| 神经炎症（TNF+IL-1β 组合）集体阻断突触可塑性 | IL-10 抗炎处理（中和 TNF/IL-1β/IL-6）恢复 rMS 诱导的突触可塑性 | PMID:33391287 | 高 |
| 慢性应激→小胶质细胞预激→AD 风险 | 慢性应激小鼠：小胶质细胞对 Aβ 的炎症应答幅度提高 2–5 倍 | PMID:29992181 综述 | 中 |
| CRH 直接激活小胶质细胞 | CRH 处理→小胶质细胞促炎形态转变；CRHR 拮抗剂减轻神经炎症 | PMID:29302258, PMID:41751239 | 中 |
| 神经炎症早于 AD 临床症状 | AD 模型（1 月龄）：C1q 在突触预激活，先于斑块出现 | PMID:27033548 | 高 |

## 连接

- [[microglia]] — 神经炎症的主要执行细胞
- [[astrocyte]] — A1 反应性星形胶质细胞放大神经炎症
- [[inflammatory-cytokines-synapse]] — 神经炎症对突触的分子损伤机制细节
- [[synaptic-pruning]] — 神经炎症激活病理性突触剪枝
- [[complement-cascade-cns]] — 补体系统是神经炎症的重要下游效应器
- [[alzheimers-disease]] — 神经炎症是 AD 早期驱动力（先于斑块）
- [[hpa-axis]] — 慢性应激通过 HPA 轴促进神经炎症（慢性 GC/CRH 预激）
- [[glucocorticoid-hippocampus-plasticity]] — 慢性 GC 一方面直接损伤 LTP，另一方面促神经炎症（间接路径）
- [[ltp]] — 神经炎症通过细胞因子损伤 LTP（浓度依赖性双向效应）
- [[bdnf]] — 神经炎症下调 BDNF 表达和 TrkB 信号

## 未解问题

- Q-inflam-01：预激状态的可逆性边界（减压/运动/抗炎干预能否恢复？）
- Q-inflam-02：人脑 AD 局部神经炎症微环境中细胞因子浓度是否真正达到 LTP 损伤阈值？
- Q-inflam-03：TREM2 激动剂在 AD 早期的突触保护效果（人类临床试验数据不足）
- Q-inflam-04：PV+ 中间神经元对慢性神经炎症的优先脆弱性

## 修订历史

- 2026-07-10 · 创建 · 基于《当卫士变成刽子手》(#78)；初始置信度：高；建立神经炎症的独立知识库节点

## 来源文章

- [[2026-07-10-neuroinflammation-synaptic-damage]]

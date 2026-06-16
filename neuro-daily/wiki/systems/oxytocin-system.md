---
title: 催产素系统
slug: oxytocin-system
domain: systems
type: mechanism
status: established
confidence: high
created: 2026-06-16
updated: 2026-06-16
revision_count: 2
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, whole-brain-network, behavior, cognition]
related: [vasopressin-system, amygdala, dopamine-system, neuromodulator-systems, endocannabinoid-system, hpa-axis, pair-bond, social-reward, nucleus-accumbens, paraventricular-nucleus, fear-extinction, hippocampal-ca2-social-memory]
prerequisites: [synaptic-transmission, gpcr-signaling, action-potential, hypothalamus]
opens_questions: [Q-OT-01, Q-OT-02, Q-OT-03, Q-OT-04]
source_articles: [2026-06-16-oxytocin-social-bonding-neural-circuits, 2026-06-16-vasopressin-avp-social-circuit]
key_sources: ["PMID:35858094", "PMID:19481567", "PMID:15931222", "PMID:33589833", "PMID:29897293", "PMID:22197271", "PMID:23850525", "PMID:37248645"]
---

# 催产素系统 (Oxytocin System)

> **一句话定义**：催产素（9肽，PVN/SON合成）作为外周激素（分娩/泌乳）和中枢神经调质（通过 OXTR→Gq→Ca²⁺ 级联），通过 PVN→CeA（抗焦虑）、PVN→NAc（社会奖励）等关键投射，以高度依赖物种受体分布、个体经验和社会情境的方式，将社会刺激的显著性提升与奖励学习偶联，支撑信任、配对键形成和亲代照顾等社会行为。

## 当前理解

我们现在认为，催产素系统的核心功能不是"产生爱的感觉"，而是**调节社会刺激的神经显著性权重**：通过在奖励（NAc）、防御（CeA）和记忆（海马）回路中部署 OXTR，选择性地增强特定社会刺激的信号强度，使其更容易被学习系统记录为"奖励"，被防御系统标记为"安全"，被记忆系统写入长期印记。

催产素不是"亲社会开关"——它对内群体和外群体的效果相反，其行为结果高度依赖物种 OXTR 分布（草原田鼠 vs 草甸田鼠 NAc）、个体发育经历（早期亲代照顾影响成年 OXTR 密度）和当下社会情境（熟悉 vs 陌生）。

关键新理解（2021-2022）：
1. CeA 星形胶质细胞亚群表达 OXTR，且是催产素抗焦虑效应的必要中介（而非只是神经元；Wahis 2021）。
2. 配对键形成在 NAc 建立**从头 OT-eCB 耦合**：OXTR→Ca²⁺→2-AG→CB1R 链路在配对前不存在，配对经历建立后才出现（Borie 2022）。这表明社会经验不只改变突触强度，还在模块间创建新的连接协议。

## 关键机制

### 分子层：合成与受体信号

**合成**：下丘脑大细胞神经元（magnocellular neurons）在室旁核（PVN）和视上核（SON）合成，轴突投射到垂体后叶（外周释放）和脑内广泛区域（中枢调制）。树突释放形成下丘脑内的"催产素浴"，再通过脑脊液体积传递（volume transmission）到达远距离靶点。

**OXTR 信号级联**：
- 7TM GPCR，主要偶联 Gq/G11
- Gα-q → PLC → IP₃（→ ER Ca²⁺ 释放）+ DAG（→ PKC）
- Ca²⁺ → CaMKII（突触可塑性）
- MAPK/ERK（基因表达、长期可塑性）
- 细胞内 Ca²⁺ 升高还触发 eCB 合成（DGL-α→2-AG→逆行 CB1R 抑制）

### 回路层：三条关键投射

**PVN → 中央杏仁核（CeA）**：
- 抗焦虑的关键节点
- 炎性痛 → PVN OT 神经元活动降低 → 焦虑增加（Li 2023）
- 化学遗传激活 PVN OT 神经元或 CeA 微注射 OT → 完全逆转痛诱发焦虑
- 信号路径包含神经元 OXTR 和星形胶质细胞 OXTR 双轨（Wahis 2021）

**PVN → 伏隔核（NAc）**：
- 社会奖励的关键节点
- OT → VTA → NAc DA 升高（体内微透析）
- 配对键：OT（NAc）+ DA 协同 → 特定个体-奖励绑定
- 草原田鼠（高 NAc OXTR）→ 单配性；草甸田鼠（低 NAc OXTR）→ 杂交性
- 配对后从头建立 OT-eCB 耦合（Borie 2022）

**PVN → 海马、前额叶、嗅球**：
- 社会记忆（嗅觉识别）
- 高级社会认知（心理理论、情绪推断）

### 受体分布的物种与个体差异

| 层级 | 差异来源 | 行为后果 |
|------|---------|---------|
| 物种间 | OXTR 基因调控区变异 → 脑区表达差异 | 草原田鼠单配性 vs 草甸田鼠杂交性 |
| 个体间 | NAc OXTR 密度差异达8倍（Borie 2022） | 亲社会行为倾向差异；早期剥夺后差异 |
| 经验依赖 | 配对经历建立新 OT-eCB 耦合 | 配对后 NAc 对 OT 的响应方式质变 |

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 草原田鼠 NAc OXTR 差异决定单配性 | 自放射成像+转基因回补 | Ross & Young 2009, PMID:19481567 | 高 |
| 鼻内 OT 增加人类社会信任（非一般风险） | 双盲 RCT 信任博弈 N=128 | Kosfeld 2005, PMID:15931222 | 中-高 |
| PVN→CeA OT 投射抗焦虑 | DREADD + CeA 微注射 | Li 2023, PMID:37248645 | 中-高 |
| CeA 星形胶质细胞 OXTR 介导抗焦虑 | 条件性胶质细胞 OXTR KO | Wahis 2021, PMID:33589833 | 中（新发现） |
| 配对后 NAc 从头 OT-eCB 耦合 | 体外电生理+CB1 药理阻断 | Borie 2022, PMID:35858094 | 中 |
| OT 增强 NAc DA（VTA 注射） | 体内微透析 | Love 2013 综述, PMID:23850525 | 中 |

## 连接

- [[vasopressin-system]] — 分子孪生兄弟（仅差2个氨基酸）：OT 偏向雌性/NAc/配对键触发；AVP 偏向雄性/VP/社会记忆/攻击；两者共享 CA2 节点（OXTR+V1bR 协同），存在受体交叉激活
- [[hippocampal-ca2-social-memory]] — CA2 共表达 OXTR 和 V1bR；OXR+V1bR 双 KO 才完全损害社会记忆（协同功能）
- [[amygdala]] — PVN→CeA 投射；OT 降低杏仁核恐惧/防御反应；星形胶质细胞 OXTR
- [[dopamine-system]] — OT→VTA→NAc DA；社会奖励的 OT-DA 串扰（Feldman 2017）
- [[endocannabinoid-system]] — OXTR→Ca²⁺→2-AG→CB1R；配对键中从头建立的 OT-eCB 耦合
- [[hpa-axis]] — OT 抑制 HPA 应激反应（应激缓冲机制）
- [[neuromodulator-systems]] — 催产素是第五类主要中枢神经调质（除 ACh/NE/DA/5-HT）
- [[pair-bond]] — 草原田鼠配对键的 OT-DA-NAc 机制（雌性主导）；AVP-VP-V1aR（雄性主导）
- [[fear-extinction]] — OT 通过 CeA 促进恐惧消退（与 eCB 系统协同）

## 未解问题

- Q-OT-01（高优先级）：鼻内催产素真实脑内浓度？需要 OXTR-PET 示踪剂验证
- Q-OT-02（高优先级）：ASD 催产素治疗有效性条件（发育时机、OXTR 基因型、内源 OT 状态）
- Q-OT-03（中优先级）：人类配对键是否有 NAc OT-DA 同构机制？
- Q-OT-04（中优先级）：CeA 星形胶质细胞 OXTR 在其他脑区是否同样存在？

## 修订历史

- 2026-06-16 · 创建 · 基于《社会大脑的肽类密码》(#194) · 11个来源（3篇开放全文）· 初始置信度：高
- 2026-06-16 · rev2 · 基于《加压素系统》(#195)：新增 vasopressin-system 和 hippocampal-ca2-social-memory 连接；补充 OT/AVP 分子孪生关系；OXR+V1bR 在 CA2 的协同功能；updated related/source_articles

## 来源文章

- [[2026-06-16-oxytocin-social-bonding-neural-circuits]]
- [[2026-06-16-vasopressin-avp-social-circuit]]

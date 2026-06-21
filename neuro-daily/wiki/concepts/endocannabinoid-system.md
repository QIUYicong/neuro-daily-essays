---
title: 内源性大麻素系统
slug: endocannabinoid-system
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-05
updated: 2026-08-20
revision_count: 2
dimensions: [molecular, synaptic, cellular, microcircuit, brain-region, behavior]
related: [cb1-receptor, ltd, fear-extinction, stdp, ltp, amygdala, cerebellum, basal-ganglia, placebo-analgesia, endogenous-opioid-system, tripartite-synapse, nmda-receptor, voltage-gated-calcium-channels, short-term-synaptic-plasticity]
prerequisites: [synaptic-transmission, voltage-gated-calcium-channels, nmda-receptor, ltd]
opens_questions: [Q-ecb-01, Q-ecb-02, Q-ecb-03, Q-ecb-04]
source_articles: [2026-08-05-endocannabinoid-retrograde-signaling]
key_sources: ["PMID:23040807", "PMID:26698193", "PMID:11279497", "PMID:11588204", "PMID:19126760", "PMID:16776579"]
---

# 内源性大麻素系统 (Endocannabinoid System, ECS)

> **一句话定义**：大脑内源性的逆行突触调制系统：突触后神经元活动时合成脂质信使（2-AG、AEA），它们逆向穿越突触间隙激活突触前 CB1 受体，在秒级尺度暂时压制神经递质释放（DSI/DSE），或在分钟到小时尺度诱导长时程突触抑制（eCB-LTD）。

## 当前理解

我们现在认为，ECS 是大脑最主要的突触反馈调节系统之一，打破了"信号只从突触前到突触后"的经典范式。突触后神经元通过 ECS 向上游输入实施实时、局部的反馈控制——当突触后细胞过度激活时，它合成脂质信使 2-AG 和/或 AEA，这些分子逆向扩散激活突触前 CB1R，使上游细胞暂时或持久地"少说话"。

ECS 的功能不限于防止过度激活，它还参与：
1. **活动依赖性去抑制**：通过选择性抑制 CCK⁺ GABA 能中间神经元（而非 PV⁺），允许活跃的兴奋性神经元网络暂时解除对自身的抑制性约束
2. **长时程突触重塑**（eCB-LTD）：通过持续 CB1R 激活，永久降低突触前释放概率
3. **情绪记忆的可塑性调节**：在杏仁核中，AEA 水平决定恐惧消退学习的效率
4. **痛觉下行调制**：内脊髓 CB1R 参与下行镇痛回路（与内源性阿片系统协同）

## 关键机制

### 两种内源性配体

**2-AG（2-花生四烯酸甘油）**

合成：PLCβ（感知 Ca²⁺ + Gq/mGluR1/5）→ DAG → **DGLα**（突触后 PSD 周围）→ 2-AG

降解：**MAGL**（~85%，突触前）、ABHD6（~14%，突触后）、ABHD12（少量）

亦可被 COX-2 代谢为 PGE2-G（促兴奋，与 2-AG 效应相反）

特性：CB1R 和 CB2R **全激动剂**（高效能）；主要逆行信使

**AEA（花生四烯酸乙醇胺，大麻素/anandamide）**

合成：**NAPE-PLD**（主要，体内路径可能多元）→ AEA

降解：**FAAH**（突触后，水解效率高）

特性：CB1R **部分激动剂**（低效能）；TRPV1 **全激动剂**；更多参与持续性、非逆行信号

### DSI/DSE（短时程逆行抑制）

1. 强突触后去极化 → Cav1（L型）开启 → Ca²⁺ 升高（1–10 µM）
2. Ca²⁺ 激活 DGLα → 2-AG 合成
3. 2-AG 逆向扩散 → 突触前 CB1R 激活
4. **Gβγ** → 直接抑制 **Cav2.2**（N型）/Cav2.1 → 突触前 Ca²⁺ 下降 → 神经递质释放减少 50–80%
5. 效果持续 30–60 秒 → 2-AG 被 MAGL 降解后自行恢复

**mGluR 增强**：PLCβ 作为符合探测器（Ca²⁺ + Gq 同步激活），在亚阈值条件下触发 2-AG 合成——赋予 eCB 系统 Hebbian 逻辑（前后同步才激活）。

### eCB-LTD（长时程突触抑制）

CB1R 持续激活（分钟级）→ **Gαi** → ↓腺苷酸环化酶 → ↓cAMP → ↓PKA → **RIM1α**（活动带蛋白）去磷酸化 → 突触囊泡对接效率持久降低 → 释放概率长期下降

可发生于：
- **iLTD**（抑制性突触 LTD）：海马 CA1，去除 CCK⁺ 细胞对锥体细胞的长期 GABA 抑制
- **eLTD**（兴奋性突触 LTD）：纹状体、PFC，调节奖励和执行功能

### 非逆行模式（复杂性扩展）

1. **AEA → TRPV1（突触后）** → Ca²⁺ → 钙调磷酸酶 → AMPAR 内吞 → 突触后 LTD（不依赖 CB1R）
2. **星形胶质细胞 CB1R（Gq/11 偶联）** → Ca²⁺ → 谷氨酸释放 → 异突触调制（距原突触 70 µm 范围）
3. **慢自我抑制（SSI）**：胞体去极化 → 胞体 2-AG → 胞体 CB1R → GIRK（Kir3）活化 → K⁺ 外流 → 超极化（无需突触传递）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| eCBs 是海马 DSI 的逆行信使（Ca²⁺ 依赖，CB1R 阻断） | 脑片膜片钳；CB1R 拮抗剂（SR141716A）阻断；BAPTA 消除 | Wilson & Nicoll, 2001, Nature, PMID:11279497 | 高 |
| 小脑 DSI 同样依赖 CB1R（AM251 完全阻断） | 浦肯野细胞膜片钳；AM251；WIN55212-2 | Kreitzer & Regehr, 2001, J Neurosci, PMID:11588204 | 高 |
| 2-AG（非 AEA）是主要逆行信使；DGLα KO 消除 DSI | DGLα 基因敲除；药理分离 | Castillo et al., 2012, Neuron, PMID:23040807 | 高 |
| CB1R 富集于 CCK⁺ 中间神经元（5–10× PV⁺） | 免疫荧光定量；单细胞电生理 | Lu & Mackie, 2016, Biol Psychiatry, PMID:26698193 | 高 |
| eCB-LTD 通过 RIM1α 实现（KO 消除 LTD 不影响 DSI） | RIM1α 基因敲除；对比 DSI 与 LTD | Castillo et al., 2012, Neuron, PMID:23040807 | 高 |
| FAAH 抑制增强杏仁核恐惧消退；人类 PTSD 2a 期数据 | 啮齿类行为药理；PF-04457845 人类试验 | Mayo et al., 2022, Biol Psychiatry, PMID:34598785 | 中 |

## 连接

- [[cb1-receptor]] — ECS 的主要效应受体（突触前）
- [[ltd]] — eCB-LTD 是 LTD 的突触前形式
- [[fear-extinction]] — AEA 在 BLA 调控恐惧消退
- [[stdp]] — CB1-LTD 是 STDP 后时序（tpost < tpre）诱导 LTD 的一个实施机制
- [[amygdala]] — 恐惧消退的关键 ECS 作用区域
- [[basal-ganglia]] — 皮层-纹状体 eCB-LTD 与习惯形成
- [[cerebellum]] — 小脑 DSE 和平行纤维 LTD
- [[tripartite-synapse]] — 星形胶质细胞 CB1R 参与异突触调制
- [[endogenous-opioid-system]] — 两大"止痛/止恐"神经调质系统，在 PAG 和脊髓有功能协同；在 NAc 壳区享乐热点内，eCB 的 liking 增强依赖内源性阿片信号同时激活（功能耦合，Mitchell 2018，PMID:30069500）
- [[nucleus-accumbens]] — NAc壳区享乐热点：AEA/2-AG 在前内侧壳区激活 CB1R 增强 sucrose liking；社会互动→NAc内AEA/2-AG升高；CB1R阻断抑制社会CPP和配对联结维持
- [[hedonic-hotspot]] — NAc壳区的 eCB 享乐热点是 ECS 参与 liking（而非 wanting）产生的解剖位点

## 未解问题

- **Q-ecb-01**：eCB-LTD 和 NMDA-LTD 在同一突触如何共存和相互竞争？诱导条件的边界在哪里？
- **Q-ecb-02**：FAAH 抑制剂在人类 PTSD 的 3 期临床结果如何？能否复制啮齿类的显著消退增强效果？
- **Q-ecb-03**：慢自我抑制（SSI）在体内生理条件下是否实际发生（目前主要为体外证据）？
- **Q-ecb-04**：2-AG 通过 CB2R 调节神经炎症的通路是否有治疗靶点价值（AD、脑损伤）？

## 修订历史

- 2026-08-20 · 修订 rev2 · 基于《伏隔核的奖赏解剖》文章 #118 · 连接节新增 nucleus-accumbens（NAc壳区eCB享乐热点、社会奖赏eCB信号）和 hedonic-hotspot；endogenous-opioid-system 连接注释补充 NAc 壳区热点内eCB-阿片功能耦合（Mitchell 2018）
- 2026-08-05 · 创建 · 基于《逆行的信使》文章 #104 · 初始置信度：高（核心机制来自 Castillo 2012、Lu & Mackie 2016 开放全文）

## 来源文章

- [[2026-08-05-endocannabinoid-retrograde-signaling]]
- [[2026-08-20-nucleus-accumbens-wanting-liking-reward-circuit]]

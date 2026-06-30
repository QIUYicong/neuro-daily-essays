---
title: mGluR 依赖性 LTD（海马 mGluR-LTD）
slug: mglur-ltd
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-10-17
updated: 2026-10-17
revision_count: 1
dimensions: [molecular, synaptic, cellular, disease, cognition]
related: [ltd, ltp, ampa-receptor, homer1a, cerebellar-ltd, fragile-x-syndrome, fmrp-translational-repressor, grip1, pick1, arc-arg31, mglur5, synaptic-scaling, protein-synthesis-dependent-plasticity]
prerequisites: [synaptic-transmission, ampa-receptor, ltd, mglur5]
opens_questions: [Q-mglur-ltd-01, Q-mglur-ltd-02, Q-mglur-ltd-03, Q-mglur-ltd-04]
source_articles: [2026-10-17-mglur-ltd-hippocampal-fragile-x]
key_sources: ["PMID:20188650", "PMID:15219735", "PMID:12032354", "PMID:26764156", "PMID:21090964", "PMCID:PMC3019409"]
---

# mGluR 依赖性 LTD（海马 mGluR-LTD）

> **一句话定义**：海马 CA1 突触中，mGluR5 被强烈谷氨酸激活后通过 Gαq→PLCβ→IP3→ER Ca²⁺→PKCβ→GluA2-Ser880 磷酸化→GRIP 解离→PICK1 内化的完整级联，驱动 AMPA 受体持久减少；需要树突局部蛋白质合成；在脆性 X 综合征（FMR1 KO）中因 FMRP 的翻译刹车缺失而过度激活。

## 当前理解

我们现在认为，海马 mGluR-LTD 是突触强度的第二条减弱轴，与 NMDA-LTD 并列，但机制完全独立。其核心逻辑是：**强烈但非精确的突触活动**溢出谷氨酸到 AMPA/NMDA 受体以外的 mGluR5 区域，触发一套主动的 Ca²⁺/PKC 信号级联，最终将 AMPA 受体从突触后膜"主动推离"。

这套机制的关键特征是**蛋白质合成依赖性**：mGluR5 激活不仅触发即时的磷酸化信号，还解除 FMRP 对树突 mRNA 的翻译抑制，使 Arc 等 LTD 效应蛋白快速局部合成，为 LTD 的持久表达提供新物质基础。

脆性 X 综合征（FXS）的核心病理正是这套机制的失调：FMRP 缺失 → 翻译刹车丧失 → LTD 相关蛋白在静息态就过量 → mGluR-LTD 变成蛋白合成无关的持续过度激活 → 突触权重弥漫性减弱 → 认知障碍（Bear 等人 mGluR 理论，PMID:15219735）。

与睡眠期 Homer1a 介导的突触削减的关键区别（见 [[homer1a]]）：Homer1a 通过**解耦** mGluR5 与其下游效应子（被动安静化），而 mGluR-LTD 通过**激活** mGluR5 信号级联（主动执行内化）——两者共享受体分子，但逻辑相反。

## 关键机制

### 诱导条件

- **药理诱导**：DHPG（3,5-dihydroxyphenylglycine，I 族 mGluR 选择性激动剂）浸浴
- **电生理诱导**：配对脉冲低频刺激（PP-LFS），激活 mGluR5 而非 NMDAR
- **共同特点**：不依赖 NMDA 受体（AP5 不能阻断 mGluR-LTD）

### 信号级联（逐步）

**触发层（突触外 mGluR5）**：
- mGluR5 激活 → 与 Gαq/11 蛋白偶联
- 长型 Homer（Homer1b/c、Homer2）将 mGluR5 预先连接到 IP3R，放大信号传导效率

**第二信使层（Ca²⁺ + DAG）**：
- Gαq → PLCβ → PIP2 → IP3 + DAG
- IP3 → IP3R → ER Ca²⁺ 释放（胞外内流无关）
- DAG + Ca²⁺ → 激活 PKCβ（β 型蛋白激酶 C）

**执行层（GluA2 磷酸化→解锚→内化）**：
- PKCβ 磷酸化 GluA2 C 末端 **Ser880**
- 磷酸化 Ser880 → 破坏与 GRIP1/2 的结合（GRIP 是 AMPAR 的关键突触锚定蛋白）
- PICK1（对磷酸化 Ser880 有高亲和力）结合 GluA2 → 招募内吞机器
- 网格蛋白介导的 AMPAR 内吞 → 突触 AMPAR 数量持久减少

### 蛋白质合成依赖性

mGluR-LTD 需要**树突局部蛋白合成**（Huber et al. 2002，PNAS，PMID:12032354）：
- 翻译抑制剂（anisomycin/emetine）可完全阻断野生型 mGluR-LTD
- 关键新合成蛋白：**Arc/Arg3.1**（招募 dynamin/endophilin 执行内吞）、MAP1B 等
- FMRP 正常情况下抑制这些 mRNA 的翻译；mGluR5 激活导致 FMRP 磷酸化/降解 → 翻译解除 → Arc 等快速合成

### mGluR-LTD vs NMDA-LTD 的关键区别

| 特征 | mGluR-LTD | NMDA-LTD |
|------|-----------|---------|
| 触发受体 | mGluR5（代谢型，Gαq）| NMDAR（离子型，Ca²⁺ 通道）|
| Ca²⁺ 来源 | ER 内库（IP3R 介导）| 胞外（NMDAR 通道）|
| 关键激酶 | PKCβ | PP2B/PP1（磷酸酶！）|
| GluA2-Ser880 命运 | PKC 磷酸化→GRIP 解离 | 同！（两条路径共享效应器）|
| 蛋白合成需求 | 是 | 否（直接磷酸化级联）|
| NMDAR 依赖性 | 否 | 是 |

### 与小脑 LTD 的比较

- 海马：mGluR5（优先）→ PKCβ；蛋白合成依赖
- 小脑：mGluR1（优先）→ PKCα/γ；攀爬纤维 Ca²⁺ 参与
- 共同效应器：**PKC → GluA2-Ser880 磷酸化 → PICK1 → AMPAR 内吞**（进化保留的执行机制）

详见 [[cerebellar-ltd]]。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| mGluR-LTD 诱导不依赖 NMDA 受体 | AP5 不阻断 DHPG-LTD | Lüscher & Huber 综述 PMID:20188650 | 高 |
| mGluR-LTD 需要局部蛋白合成 | anisomycin 完全阻断野生型 LTD | PMID:12032354 | 高 |
| FMR1 KO 小鼠 mGluR-LTD 增强且蛋白合成独立 | Fmr1 KO 脑片 DHPG-LTD vs WT（82% vs 93%）| PMID:12032354 | 高 |
| FMRP 缺失 = 翻译刹车丧失（mGluR 理论）| 动物模型多种 FXS 表型被 mGluR5 减弱挽救 | PMID:15219735, PMC3019409 | 中-高（动物模型；人类 RCT 失败）|
| mGluR5 拮抗剂在人 FXS 临床试验未达终点 | Phase 2b RCT n=314，12 周，ABC-C 无改善 | PMID:26764156 | 高（RCT）|
| GluA2-Ser880 磷酸化→GRIP 解离→PICK1 内化 | 突变体功能丧失实验；共免疫沉淀 | 多篇（机制教科书级别）| 高 |

## 连接

- [[ltd]] — mGluR-LTD 是 LTD 的两条主要亚型之一（另一条为 NMDA-LTD）；共享 GluA2-Ser880-PICK1 效应器
- [[cerebellar-ltd]] — 共享受体家族（I 族 mGluR）和执行器（PKC-GluA2-Ser880-PICK1），但使用不同的 mGluR 亚型和上游 Ca²⁺ 来源
- [[homer1a]] — Homer1a 在睡眠期**解耦** mGluR5 信号（被动）；与 mGluR-LTD 的**激活**路线形成对比；FXS 中 Homer1a 病理性升高可能参与 mGluR5 调控失衡
- [[ampa-receptor]] — mGluR-LTD 的最终效应：AMPAR（含 GluA2 亚基）从突触膜内化并减少
- [[arc-arg31]] — Arc/Arg3.1 是 mGluR-LTD 的关键新合成效应蛋白，招募内吞机器
- [[fragile-x-syndrome]] — mGluR-LTD 在 FXS 中过度激活是该疾病的核心突触机制
- [[protein-synthesis-dependent-plasticity]] — mGluR-LTD 是突触可塑性中蛋白合成依赖的代表机制之一
- [[synaptic-scaling]] — 与 mGluR-LTD 相比，突触缩放是整体的、非突触特异的稳态机制

## 未解问题

- Q-mglur-ltd-01（高优先级）：PICK1 在 mGluR-LTD 中是否真的必要？不同实验室数据不一致，可能反映实验条件差异或体内外差异
- Q-mglur-ltd-02（高优先级）：在体（in vivo）mGluR-LTD 的自然诱导条件？哪种行为或认知操作会激活 mGluR5 到足以触发 LTD 的程度？
- Q-mglur-ltd-03（中优先级）：FXS 是否存在对 mGluR5 拮抗剂响应的亚群（如较年轻患者、特定遗传背景）？候选生物标志物？
- Q-mglur-ltd-04（中优先级）：mGluR-LTD 的蛋白合成靶标是否超越 Arc？其他蛋白（MAP1B、STEP）的因果贡献？

## 修订历史

- 2026-10-17 · 创建 · 基于《当受体失去支架》(#177) · 综合 Lüscher & Huber 2010 / Bear et al. 2004 / Huber et al. 2002 / Berry-Kravis et al. 2016 / Krueger & Bear 2011 · 初始置信度：高（机制教科书级别）；FXS 临床应用置信度中-高

## 来源文章

- [[2026-10-17-mglur-ltd-hippocampal-fragile-x]]

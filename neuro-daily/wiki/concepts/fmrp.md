---
title: FMRP（脆性X综合征智力低下蛋白）
slug: fmrp
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-06-04
updated: 2026-06-04
revision_count: 1
dimensions: [molecular, synaptic, cellular, cognition, disease]
related: [ltp, ltd, ampa-receptor, nmda-receptor, asd, mglur-ltd, synaptic-scaling, bdnf]
prerequisites: [synaptic-transmission, ltp, ltd, ampa-receptor]
opens_questions: [Q-fmrp-01, Q-fmrp-02]
source_articles: [2026-06-04-asd-ei-imbalance-circuit-mechanism]
key_sources: ["PMID:15219735", "PMID:21090964"]
---

# FMRP（脆性X综合征智力低下蛋白，Fragile X Mental Retardation Protein）

> **一句话定义**：FMRP 是由 FMR1 基因编码的 mRNA 结合蛋白，作为树突局部蛋白翻译的"刹车"，正常情况下抑制约 4% 大脑 mRNA 的翻译；FMRP 缺失导致 mGluR5 下游突触蛋白过量合成、LTD 增强、树突棘发育受阻，是脆性 X 综合征（最常见单基因 ASD 病因）的分子根源。

## 当前理解

我们现在认为，FMRP 是突触可塑性翻译调控的核心成分。在健康状态下，突触活动（特别是 mGluR5 激活）触发 FMRP 翻译靶标短暂合成，同时 FMRP 本身充当负反馈调节器防止过量合成。FMR1 基因失功能（三核苷酸重复扩展 CGG>200）→ FMRP 缺失 → **mGluR 依赖性 LTD 持续增强，树突棘无法正常成熟**（Bear et al. 2004，PMID:15219735）。

**mGluR 理论核心**（Bear et al. 2004）：
- 正常：mGluR1/5 激活 → FMRP 靶标蛋白短暂合成 → AMPA 受体内化（LTD）→ FMRP 负反馈阻止过量
- FXS：FMRP 缺失 → 无负反馈 → mGluR5 下游翻译失控 → AMPA 受体持续内化 → 突触弱化、树突棘形态异常

**树突棘表型**：FMR1 KO 鼠视觉皮层中未成熟的细长树突棘（filopodia-like）增多，成熟的蘑菇形棘减少，提示突触成熟过程受阻（Wang et al. 2023 引用数据，PMCID:PMC9915249）。

**mGluR5 拮抗剂的转化**：动物模型中，mGluR5 拮抗剂（CTEP, lovastatin, fenobam）可显著改善 FXS 小鼠的 spine 形态、惊厥阈值和学习行为（Krueger & Bear 2011，PMID:21090964，PMCID:PMC3100156）。人类临床试验结果不稳定，可能原因包括剂量窗口、成熟脑的 mGluR5 弱化或临床测量工具不灵敏。

## 关键机制

### 分子层面
- FMRP 结合 mRNA 编码突触蛋白（PSD-95、MAP1B、Arc、CaMKII、SHANK 等）的 3'UTR 或编码区
- 静息状态：FMRP 聚合在 mRNA 颗粒中，抑制多核糖体翻译
- 激活状态（mGluR1/5 → PKC → PP2A 脱磷酸化）：FMRP 磷酸化降低 → 翻译去抑制
- 随后：FMRP 重新被 S6 激酶磷酸化 → 翻译恢复抑制（负反馈）

### 突触层面
- mGluR-LTD：谷氨酸激活 mGluR5 → FMRP 靶标（如 Arc/Arg3.1）翻译 → AMPA 受体内化 → 突触弱化
- FXS：FMRP 缺失 → 上述过程失控 → AMPA 受体持续内化 → 突触弱化难以逆转
- 结果：树突棘密度增加但成熟度低，突触整体效率下降

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| FMRP 缺失→mGluR-LTD 增强 | FMR1 KO 小鼠 mGluR-LTD 增加 50%（DHPG 诱发）| PMID:15219735 | 高 |
| mGluR5 拮抗剂改善 FXS 表型 | CTEP/lovastatin 慢性治疗 FMR1 KO：spine、惊厥、学习改善 | PMID:21090964 | 高（小鼠）|
| FMRP 绑定约 4% 大脑 mRNA | RNA 免疫沉淀 + 微阵列（Darnell 2011 等） | PMID:36768153 引用 | 高 |

## 连接

- [[ltd]] — FMRP 是 mGluR 依赖性 LTD 的负调控因子；FXS 中 LTD 过强
- [[ampa-receptor]] — FMRP 缺失→AMPA 受体持续内化→突触弱化
- [[asd]] — FXS 是最常见单基因 ASD；FMRP 缺陷是 E/I 失衡的分子原型之一
- [[synaptic-scaling]] — FMRP 与突触稳态的关系：FMRP 缺失影响 GluA2 亚基表达，可能干扰稳态缩放
- [[bdnf]] — FMRP 可能调节 BDNF 下游翻译靶标

## 未解问题

- Q-fmrp-01（高优先级）：人类 FXS 临床试验的 mGluR5 拮抗剂失败的确切原因（成熟脑 vs 发育脑差异？剂量窗口？表型测量工具？）
- Q-fmrp-02（中优先级）：FMRP 是否通过调节 BDNF 翻译参与神经发生和成年可塑性？

## 修订历史

- 2026-06-04 · 创建 · 基于《当发育的精密时钟出错》(#73) · 初始置信度：高（机制明确）

## 来源文章

- [[2026-06-04-asd-ei-imbalance-circuit-mechanism]]

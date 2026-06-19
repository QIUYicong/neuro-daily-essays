---
title: 嗅觉受体（OR）基因家族
slug: olfactory-receptor
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-26
updated: 2026-07-26
revision_count: 1
dimensions: [molecular, cellular]
related: [olfactory-bulb, piriform-cortex, transcriptomic-cell-types, single-cell-rna-seq]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: [Q-or-pseudogene-loss, Q-or-human-odor-space]
source_articles: [2026-07-26-olfactory-coding-smell-memory-limbic]
key_sources: ["PMID:32166167", "PMID:32278646"]
---

# 嗅觉受体（OR）基因家族 (Olfactory Receptor Gene Family)

> **一句话定义**：嗅觉受体（OR）基因家族是哺乳动物基因组中最大的G蛋白偶联受体（GPCR）基因家族，人类约有400个功能性成员，每个嗅觉感觉神经元（OSN）仅单等位基因表达其中一种，并将轴突精确汇聚至嗅球特定小球，从而将化学多样性转化为可辨识的组合编码神经信号。

## 当前理解

我们现在认为，嗅觉受体（OR）基因家族是Buck & Axel 1991年发现的最大GPCR家族（2004年诺贝尔奖）：

- **规模**：小鼠约1100个功能性OR基因；人类约400个功能性OR基因（另有约60%为假基因，进化中功能丧失，可能与三色视觉的获得相关）
- **信号转导**：OR结合气味分子 → 激活Gs蛋白 → ACIII（腺苷酸环化酶III）激活 → cAMP升高 → 打开CNG通道（Na⁺/Ca²⁺内流）→ Ca²⁺激活Cl⁻通道（放大步骤）→ OSN去极化 → 动作电位

**三条基本规则**：
1. **一细胞一受体（单等位基因表达）**：每个OSN只表达约400种OR中的一种；选择机制通过OR的自我反馈信号实现稳定选择
2. **一受体一小球**：表达同一OR的所有OSN（散布在嗅觉上皮的特定区域带）将轴突精确汇聚到嗅球中的同一个小球
3. **组合编码**：每种气味激活多种OR的特定组合；每种OR响应多种结构相关气味；约400种OR × 组合逻辑 → 理论上可辨识10,000+种气味

OR并非高度选择性的"锁钥"机制，而是宽调谐传感器；同一OR对一类化学结构（如直链醛类分子、含一定碳链长度的酯类）都有响应，而非只对单一分子。

## 关键机制

**信号转导五步**（以cAMP通路为主）：
1. 气味分子结合OR（N端+跨膜区形成的疏水结合口袋）
2. Gs蛋白激活，Gαs亚基解离并结合ACIII
3. ACIII将ATP转化为cAMP
4. cAMP开放CNG（cyclic nucleotide-gated）通道 → Na⁺、Ca²⁺内流（初始去极化）
5. Ca²⁺内流激活Ca²⁺激活的Cl⁻通道 → Cl⁻外流（OSN内Cl⁻浓度高于平衡电位）→ 进一步去极化（放大）

**单等位基因表达机制**（不完全清楚）：
- OR的H位点（可能是核定位信号）决定其基因在基因组中的核区域定位
- 一旦某个OR基因被选择并在OSN中稳定表达，它通过反馈（可能通过OR蛋白本身经轴突顺式信号）抑制其他OR基因的表达

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| OR基因家族是最大GPCR家族 | 基因组克隆、序列分析 | Buck & Axel 1991; PMID:32166167 | 高 |
| 每个OSN只表达一种OR | 原位杂交 + 单细胞转录组 | PMID:32166167 | 高 |
| 同一OR的OSN汇聚到同一小球 | OR-GFP转基因小鼠轴突追踪 | PMID:32166167 | 高 |
| 组合编码（单个OR宽调谐） | 钙成像、电生理OR激活模式 | PMID:32166167 | 高 |
| 人类约60%OR基因为假基因 | 比较基因组学 | PMID:32166167 | 高 |

## 连接

- [[olfactory-bulb]] — 所有OSN汇聚至嗅球小球，每种OR对应一个小球
- [[piriform-cortex]] — 嗅球输出→外侧嗅束→梨状皮层；稀疏分布式编码
- [[transcriptomic-cell-types]] — OR基因表达是确定OSN细胞类型的核心标志
- [[single-cell-rna-seq]] — scRNA-seq可大规模鉴定不同OR表达的OSN亚类

## 未解问题

- Q-or-pseudogene-loss（中优先级）：人类约60%OR假基因化与三色视觉获得的因果关系？还是随机基因漂变？
- Q-or-human-odor-space（低优先级）：400种功能性人类OR能否真的编码"万亿种"气味，还是这一估计有重大方法论问题？

## 修订历史

- 2026-07-26 · 创建 · 基于《气味的神经密码：从一个分子到一段记忆的四级变换》(#94) · 初始置信度：高

## 来源文章

- [[2026-07-26-olfactory-coding-smell-memory-limbic]]

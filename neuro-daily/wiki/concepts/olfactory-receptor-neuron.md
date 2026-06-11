---
title: 嗅觉受体神经元
slug: olfactory-receptor-neuron
domain: concepts
type: structure
status: established
confidence: high
created: 2026-07-17
updated: 2026-07-17
revision_count: 1
dimensions: [molecular, cellular]
related: [olfactory-system, olfactory-glomerulus, adult-neurogenesis, voltage-gated-calcium-channels, action-potential]
prerequisites: [action-potential, voltage-gated-sodium-channel]
opens_questions: [Q-olfact-01]
source_articles: [2026-07-17-olfactory-system-molecular-to-memory]
key_sources: ["PMID:19804753", "PMID:1840504", "PMID:41131016", "PMID:19822638"]
---

# 嗅觉受体神经元 (Olfactory Receptor Neuron / Olfactory Sensory Neuron)

> **一句话定义**：嗅上皮中表达单一嗅觉受体（OR）的双极感觉神经元，纤毛端浸入黏液层捕捉气味分子，通过 OR→Gαolf→cAMP→CNG 通道→Anoctamin2 级联转导产生动作电位；每个 ORN 仅表达约 1000 种 OR 基因中的一种（单受体表达规则），约每 30-60 天再生一次。

## 当前理解

嗅觉受体神经元（ORN / OSN）是感觉神经科学中最具特殊性的细胞类型之一，原因有三：
1. **单受体表达规则**：每个 ORN 只表达约 1000 种 OR 基因中的一种，是"一类刺激—一类神经元"的极致实现
2. **直接暴露于外界**：ORN 纤毛直接接触外部化学环境（不像视网膜光感受器有角膜保护），是极少数直接暴露于环境中的成年中枢神经元
3. **终身再生**：ORN 约每 30-60 天死亡并由基底层干细胞替换，是哺乳动物中持续存在的神经发生场所之一

## 解剖结构

- **纤毛端（树突）**：延伸至嗅上皮表面，纤毛浸入黏液层；纤毛膜富含 OR 蛋白、Golf、AC III 等转导元件
- **细胞体**：位于嗅上皮中层
- **轴突**：穿越筛骨板，汇入嗅球的特定嗅小球（同类 OR 的 ORN 汇聚到同一嗅小球）

## 转导级联（五步）

1. **OR 激活**：气味分子（odorant）溶于黏液 → 与 OR（GPCR，7-TM）结合；结合通过疏水和范德华力介导，停留时间 <1 毫秒
2. **Gαolf 激活**：OR 激活特异性 G 蛋白 Gαolf（嗅觉特异性 Gα 亚单位）
3. **cAMP 生产**：Gαolf 激活腺苷酸环化酶 III（AC III）→ cAMP 浓度升高
4. **CNG 通道开放**：cAMP 开放环核苷酸门控（CNG）通道——由 2 个 CNGA2 + 1 个 CNGA4 + 1 个 CNGB1b 组成（2:1:1 化学计量，Xue et al. 2025 冷冻电镜确认）→ Na⁺ 和 Ca²⁺ 内流
5. **放大步骤**：Ca²⁺ 升高激活 Cl⁻ 通道（**Anoctamin2/TMEM16B**）→ Cl⁻ 外流（纤毛内 Cl⁻ 浓度被 NKCC1 等转运体维持在高水平）→ 膜电位进一步去极化 → 动作电位

**快速适应**：Ca²⁺ 升高 → Ca²⁺/钙调蛋白（CaM）与 CNGB1b 上的两个结合位点结合 → CNG 通道快速关闭 → cAMP 被 PDE 降解 → 信号衰减（嗅觉适应机制）

## 单受体表达规则的实现

每个 ORN 选择性表达约 1000 个 OR 基因中的一个，其他均被沉默。表观遗传机制包括：Lamin B 相关的核结构组织（OR 基因被边缘化）、H 增强子竞争假说（一个增强子在基因组范围内只激活一个 OR）。完整机制仍在研究中（Q-olfact-01）。

## 组合编码

单一气味激活多种不同 OR 亚型（宽谱）；单一 OR 可被多种结构相关分子激活。约 400 个（人类）OR 类型通过组合激活，理论上可编码指数级的气味空间（估计人类可辨别 >1 万亿种气味，Bushdid 2014，但方法论有争议）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| OR 是 7-TM GPCR 大基因家族 | 基因克隆（18 个初始成员） | PMID:1840504 | 高 |
| 每 ORN 单一 OR 表达 | 单细胞原位杂交 + OR-GFP 小鼠 | PMID:19804753 | 高 |
| CNG 通道 2:1:1 亚基化学计量 | 冷冻电镜 | PMID:41131016 | 高 |
| Anoctamin2 提供主要放大步骤 | TMEM16B KO ORN 电流减少 | PMID:19804753 引用 | 高 |
| CaM 两位点结合→快速适应 | 冷冻电镜 + 电生理 | PMID:41131016, PMID:19822638 | 高 |

## 连接

- [[olfactory-system]] — ORN 是嗅觉系统的第一感觉层
- [[olfactory-glomerulus]] — ORN 轴突汇聚目标
- [[adult-neurogenesis]] — ORN 持续更新；嗅上皮基底层干细胞驱动
- [[voltage-gated-calcium-channels]] — ORN 动作电位中的 Ca²⁺ 来源之一（VGCCs）
- [[action-potential]] — ORN 的最终输出

## 未解问题

- **Q-olfact-01**（高优先级）：OR 排他性表达（单受体选择）的完整表观遗传机制

## 修订历史

- 2026-07-17 · 创建 · 基于文章 #85 · 初始置信度：高（Buck & Axel 以来三十年验证，CNG 通道原子结构已解）

## 来源文章

- [[2026-07-17-olfactory-system-molecular-to-memory]]

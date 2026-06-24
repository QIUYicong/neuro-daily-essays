---
title: 二肽重复蛋白
slug: dipeptide-repeat-proteins
domain: concepts
type: mechanism
status: emerging
confidence: medium
created: 2026-09-11
updated: 2026-09-11
revision_count: 1
dimensions: [molecular, cellular, disease]
related: [ran-translation, als-amyotrophic-lateral-sclerosis, tdp-43-pathology, nucleocytoplasmic-transport, liquid-liquid-phase-separation]
prerequisites: [ran-translation, protein-aggregation]
opens_questions: [Q-als-02, Q-als-03]
source_articles: [2026-09-11-als-tdp43-motor-neuron-selective-vulnerability]
key_sources: ["PMID:30120348", "PMC6417666"]
---

# 二肽重复蛋白 (Dipeptide Repeat Proteins, DPR)

> **一句话定义**：C9orf72 GGGGCC 重复扩增经 RAN 翻译产生的五种重复氨基酸二联体聚合物（poly-GA、GP、GR、PA、PR），其中精氨酸富集的 poly-GR 和 poly-PR 毒性最强，通过与 LCD 结构域蛋白强力相互作用破坏核质运输、应激颗粒动力学和 TDP-43 稳态，是 C9orf72 ALS/FTD 的核心毒性分子。

## 当前理解

我们现在认为，DPR 蛋白是 C9orf72 ALS/FTD 三大机制（LOF / RNA GOF / DPR GOF）中最受关注的，也是最受争议的毒性分子。

**毒性等级**：poly-GR 和 poly-PR 毒性远强于 poly-GA、poly-GP、poly-PA：
- poly-GR/PR 富含精氨酸（+），能与含 LCD/PLD 结构域蛋白（TDP-43、FUS、hnRNP 等）通过静电相互作用结合
- 破坏核孔复合体和核质运输（细胞应激颗粒中的 NCT 因子被隔离）
- poly-GA 在哺乳动物中通过蛋白酶体阻塞发挥毒性，但在果蝇中无毒

**尸检关键发现**：在 C9orf72 ALS 患者中，poly-GR 包涵体（不是其他 DPR 类型）与神经退化区域特异共定位，且特异与 TDP-43 病理共定位——提示 poly-GR 可能是上游触发 TDP-43 聚集的关键中间分子（PMID:30120348 / PMC6417666）。

**空间解耦悖论**：DPR 包涵体主要分布于小脑和海马，而非 ALS 中最受损的脊髓（脊髓主要是 TDP-43 病理）。这一空间解耦提示 DPR 可能在上运动神经元或非神经元细胞中优先发挥毒性，再通过跨突触或间接机制损伤脊髓下运动神经元——这是当前最主要的开放性机制问题之一。

## 关键机制

### Poly-GR/PR 的分子毒性

1. **LCD 蛋白结合**：精氨酸阳离子与 LCD 中的 π 系统（酪氨酸等芳香族氨基酸）形成 cation-π 相互作用，优先结合 TDP-43、FUS、hnRNP、核孔蛋白中的 FG 重复等含 LCD 蛋白
2. **核质运输干扰**：poly-PR/GR 物理性堵塞核孔复合体的 FG 网络，损害蛋白质进出核的运输；同时将 NCT 因子招募进应激颗粒，抑制 NCT 功能
3. **应激颗粒病理化**：进入核仁，与 nucleophosmin 等核仁蛋白相互作用，破坏核仁功能（rRNA 加工，核糖体生成）
4. **TDP-43 固态化**：通过与 TDP-43 LCD 的强力结合，将 TDP-43 应激颗粒中的液态小滴推向固态聚集——这是连接 C9orf72 机制与 TDP-43 统一病理的分子桥

### Poly-GA 的独立毒性路径

- 在哺乳动物（细胞系、小鼠）中：形成星状或棒状聚集体，隔离和损伤蛋白酶体
- 在 Drosophila 模型：几乎无毒（物种差异明显）

## 关键证据

| 主张 | 方法 | 来源 | 置信度 |
|------|------|------|--------|
| Poly-GR/PR 毒性最强（细胞 / Drosophila / iPSC） | 多模型比较 | PMID:30120348 / PMC6417666 | 中-高 |
| Poly-GR 尸检中与神经退化区域和 TDP-43 特异共定位 | 患者尸检免疫荧光 | PMID:30120348 / PMC6417666 | 中-高（相关性）|
| Poly-PR/GR 通过 NCT 因子入应激颗粒介导核质运输障碍 | iPSC / 细胞系 | PMID:30120348 / PMC6417666 | 中 |
| DPR 包涵体主要在小脑/海马，非脊髓（与 TDP-43 解耦） | 患者尸检 | PMID:30120348 / PMC6417666 | 高（空间分布数据）|

## 连接

- [[ran-translation]] — DPR 蛋白的产生机制
- [[als-amyotrophic-lateral-sclerosis]] — C9-ALS 的核心毒性分子
- [[tdp-43-pathology]] — poly-GR 与 TDP-43 共定位，可能是 TDP-43 聚集的上游触发
- [[nucleocytoplasmic-transport]] — poly-PR/GR 的主要毒性靶点之一

## 未解问题

- Q-als-02（高）：DPR（主要 poly-GR/PR）对脊髓运动神经元的毒性是直接还是间接的？
- Q-als-03（中）：DPR 与 TDP-43 聚集的因果时序如何？是 DPR 先，还是 TDP-43 聚集先？

## 修订历史

- 2026-09-11 · 创建 · 基于《ALS TDP-43 文章》(#141) · 初始置信度：中（毒性等级明确，但体内主导机制仍争议）

## 来源文章

- [[2026-09-11-als-tdp43-motor-neuron-selective-vulnerability]]

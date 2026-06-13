---
title: KCC2（K⁺-Cl⁻ 共转运体 2）
slug: kcc2
domain: neurons
type: entity
status: established
confidence: high
created: 2026-06-13
updated: 2026-06-14
revision_count: 2
dimensions: [molecular, cellular, synaptic, disease]
related: [gaba-polarity-switch, nkcc1, gaba, temporal-lobe-epilepsy, ei-balance, adult-neurogenesis, critical-period, bdnf-trkb, wnt-signaling, central-sensitization, nociception, microglia]
prerequisites: [membrane-potential, synaptic-transmission, gaba]
opens_questions: [Q-kcc2-01, Q-kcc2-02, Q-kcc2-03]
source_articles: [2026-06-13-kcc2-gaba-polarity-switch]
key_sources: ["PMID:9930699", "PMID:25234263", "PMID:31615901", "PMID:26441542", "PMID:31963584"]
---

# KCC2（K⁺-Cl⁻ 共转运体 2）(Potassium-Chloride Cotransporter 2)

> **一句话定义**：大脑成熟神经元的主要氯离子外排泵，由 SLC12A5 基因编码；通过将 K⁺ 和 Cl⁻ 共同转运出细胞、维持低胞内 Cl⁻ 浓度，确保 GABA-A 受体产生超极化（抑制）效应；其发育性上调与功能活化（T906/T1007 脱磷酸化）是大脑从"幼年兴奋性 GABA"切换为"成熟抑制性 GABA"的分子核心。

## 当前理解

我们现在认为，KCC2 是神经元功能性 GABA 抑制的**主动维护者**——不是静态存在，而是每时每刻消耗 Na⁺/K⁺-ATPase 提供的 K⁺ 梯度，将 Cl⁻ 持续泵出细胞，对抗 Cl⁻ 通过各种通道持续渗漏回细胞的趋势。

KCC2 属于 SLC12 阳离子-氯化物共转运体家族，具有 12 个跨膜螺旋，以二聚体/四聚体形式在细胞膜上发挥功能；单体形式无转运活性（Kaila et al. 2014, PMID: 25234263）。KCC2 基因（SLC12A5）有两个主要剪接变体：KCC2a（发育早期有一定表达）和 KCC2b（成年期主导，约占总 KCC2 蛋白 90%）。

KCC2 功能成熟不只依赖蛋白质表达水平，还受**磷酸化状态**的决定性调控：C 末端 Thr906 和 Thr1007 位点在幼年期处于高磷酸化状态（被 WNK1-SPAK/OSR1 激酶级联磷酸化），使 KCC2 几乎无活性；随发育进程，这两个位点的磷酸化程度下降 > 95%，KCC2 转运效率提升 10 倍以上（Watanabe et al. 2019, PMID: 31615901）。这意味着即使 KCC2 蛋白在幼年期已存在于膜上，它也是"静默的"。

## 关键机制

### 转运原理
KCC2 以 Na⁺/K⁺-ATPase 建立的 K⁺ 梯度（细胞内高 K⁺、细胞外低 K⁺）为驱动力，将 K⁺ 和 Cl⁻ 以 1:1 比例共同向细胞外转运。这是**电中性、继发性主动转运**：自身不直接消耗 ATP，但依赖 Na⁺/K⁺-ATPase 维持的 K⁺ 梯度（间接消耗 ATP）。

### 多层调控
| 调控层面 | 调控因子 | 效果 |
|---------|---------|------|
| 转录 | BDNF→ERK1/2→EGR4 | ↑ KCC2b mRNA |
| 转录 | REST（疾病中激活）| ↓ KCC2 转录 |
| 转录 | IL-1β→MeCP2/REST | ↓ KCC2（炎症情况下）|
| 磷酸化（抑制性）| WNK1-SPAK→T906/T1007 | KCC2 失活 |
| 磷酸化（稳定性）| PKC→Ser940 | ↑ KCC2 膜表面稳定 |
| 快速去稳定 | NMDA→PP1→Ser940 脱磷酸 | ↑ KCC2 侧向扩散，↓ 突触定位 |
| 蛋白降解 | Ca²⁺ 过载→Calpain→C 末端切割 | KCC2 功能丧失 + 突触锚定丧失 |
| 寡聚化 | Neto2 scaffolding | 稳定 KCC2 二聚体/四聚体 |

### 功能结果
成熟神经元 KCC2 功能性表达 → [Cl⁻]ᵢ ≈ 5-10 mM（低）→ EGABA < Vr（约 -75 至 -80 mV vs Vr ≈ -65 mV）→ GABA-A 受体激活 → Cl⁻ 内流 → 超极化（抑制）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| KCC2 表达因果驱动 GABA 极性切换 | 海马锥体细胞 KCC2 反义抑制逆转 GABA 极性 | PMID:9930699 | 高 |
| T906/T1007 脱磷酸化是 KCC2 功能激活的必要条件 | T906E/T1007E 敲入小鼠出生后 4-12h 死亡；触觉诱发癫痫 | PMID:31615901 | 高 |
| 发育中 T906/T1007 磷酸化程度 E18.5→成年降低 >95% | 定量磷酸化蛋白质组学 | PMID:31615901 | 高 |
| Calpain 切割 KCC2 的 C 末端 | 兴奋毒性模型；Western blot 显示 ~20-40 kDa 片段丢失 | PMID:25234263 | 高 |
| KCC2 单体无活性；功能需二聚体/四聚体 | 生化和功能实验 | PMID:26441542 | 中-高 |
| BDNF/TrkB 是发育性（而非癫痫诱导性）KCC2 上调所不必需 | BDNF 完全敲除小鼠 KCC2 正常发育性上调 | PMID:25229715 | 中（结论出人意料，需更多证据） |

## 连接

- [[gaba-polarity-switch]] — KCC2 是极性切换的分子执行者
- [[nkcc1]] — KCC2 的功能对手；在幼年期占主导
- [[gaba]] — KCC2 决定 GABA 对成熟神经元的极性效应
- [[temporal-lobe-epilepsy]] — 发作诱导 KCC2 下调是 TLE 恶性循环的分子环节
- [[ei-balance]] — KCC2 是维持 E/I 平衡的底层氯离子稳态基础
- [[critical-period]] — KCC2 上调是 PV 细胞成熟和关键期开放的前提
- [[bdnf-trkb]] — BDNF-TrkB 双向调控 KCC2（发育上调 + 癫痫后下调）
- [[adult-neurogenesis]] — 新生神经元在整合过程中经历 NKCC1→KCC2 的氯离子稳态成熟
- [[central-sensitization]] — KCC2 下调是慢性神经病理性疼痛的核心分子机制之一
- [[nociception]] — 脊髓背角 KCC2 功能决定 GABA 抑制性闸门效率
- [[microglia]] — 激活小胶质细胞释放 BDNF→TrkB→KCC2 磷酸化，是慢性痛 KCC2 下调的上游机制

## 慢性疼痛中的 KCC2（补充，来自 #190）

脊髓背角 KCC2 在神经病理性疼痛模型（SNI、CCI、SNL）中显著下调，导致脊髓抑制性中间神经元的 GABA 效应从超极化（抑制）转变为去极化（兴奋），使脊髓闸门（Gate Control）失效。

**机制链**：
1. 周围神经损伤 → 初级传入持续释放 fractalkine/ATP
2. 脊髓小胶质细胞激活（P2X4/P2X7）→ BDNF 释放量大幅增加
3. BDNF 激活背角神经元 TrkB → 多个信号级联磷酸化/去稳定 KCC2
4. [Cl⁻]ᵢ 升高 → E_GABA 去极化偏移 → 抑制性突触功能缺失
5. 脊髓兴奋性净增 → 中枢敏化建立与维持

**药理意义**：KCC2 增强剂（CLP290、kenpaullone 的 KCC2 靶向衍生物）在啮齿类神经病理性痛模型中表现出镇痛效果，是区别于传统止痛药的新型靶点方向。

## 未解问题

- Q-kcc2-01：人类不同脑区 GABA 极性切换的精确时间线是什么？
- Q-kcc2-02：WNK-SPAK/OSR1 轴在发育中如何被程序性下调？上游信号是什么？
- Q-kcc2-03：系统性增强 KCC2 作为治疗靶点的安全性如何（特别是保留氯离子动态调节的需要）？
- Q-kcc2-04：脊髓背角 KCC2 下调的空间分布是否节段特异性（对应损伤节段 vs 泛化）？

## 修订历史

- 2026-06-13 · 创建 · 基于《大脑如何学会说"不"：KCC2、氯离子稳态与 GABA 极性切换》(#189)；来源：Kaila 2014/Watanabe 2019/Tang 2020/Rivera 1999 · 初始置信度：高
- 2026-06-14 · 修订（rev1→rev2）· 基于《伤害感受≠疼痛体验》(#190) · 新增：慢性疼痛中 KCC2 下调机制（小胶质细胞-BDNF-TrkB-KCC2 轴）、镇痛药物靶点；related 新增 central-sensitization/nociception/microglia；opens_questions 新增 Q-kcc2-04

## 来源文章

- [[2026-06-13-kcc2-gaba-polarity-switch]]

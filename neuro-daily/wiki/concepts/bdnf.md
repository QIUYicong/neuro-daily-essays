---
title: 脑源性神经营养因子（BDNF）
slug: bdnf
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-28
updated: 2026-09-11
revision_count: 4
dimensions: [molecular, cellular, synaptic, cognition, disease]
related: [ltp, ltd, adult-neurogenesis, hippocampal-neurogenesis, alzheimers-disease, nmda-receptor, camkii, arc-arg31, synaptic-tagging-capture, engram-cells, memory-consolidation, pattern-separation, critical-period, pv-interneurons, perineuronal-nets, glucocorticoid-hippocampus-plasticity, hpa-axis, trkb-receptor]
prerequisites: [ltp, synaptic-transmission, nmda-receptor]
opens_questions: [Q-bdnf-01, Q-bdnf-02, Q-bdnf-03, Q-stress-01]
source_articles: [2026-06-28-bdnf-trk-b-plasticity-memory, 2026-06-03-critical-period-plasticity, 2026-07-09-stress-glucocorticoid-hippocampus-hpa-axis, 2026-09-11-trkb-receptor-docking-signaling]
key_sources: ["PMID:16099088", "PMID:33096634", "PMID:17942328", "PMID:16025106", "PMID:12553913", "PMID:21282661", "PMID:30190379", "PMID:23674053", "PMID:15891777", "PMID:19317179", "PMID:12367511", "PMID:19675247", "PMID:22341689"]
---

# 脑源性神经营养因子 (BDNF, Brain-Derived Neurotrophic Factor)

> **一句话定义**：BDNF 是大脑中表达最广、功能最关键的神经营养因子，由神经活动诱导释放，通过 TrkB 受体激活三条平行信号通路（PLCγ、MAPK/ERK、PI3K/Akt），分别介导突触可塑性、基因表达和神经元存活；其前体 proBDNF 通过 p75NTR 产生相反效果，共同构成突触增强（LTP）与减弱（LTD）的双向分子开关。

## 当前理解

我们现在认为：BDNF 是连接"神经活动"与"持久突触变化"最重要的单一分子信使。它在细胞内以前体 proBDNF 合成，经胞外蛋白酶（tPA/纤溶酶）切割为约 14 kDa 的成熟 BDNF（mature BDNF）。两种形式分别与不同受体结合，产生几乎相反的突触效果：成熟 BDNF→TrkB 促进 LTP 和神经元存活；proBDNF→p75NTR 促进 LTD 和凋亡（Woo et al. 2005, PMID:16025106）。

成熟 BDNF 与 TrkB 结合后，激活三条平行通路：
- **PLCγ 通路**：DAG/Ca²⁺→PKC/CaMKII→突触可塑性
- **MAPK/ERK 通路**：Ras-Raf-MEK-ERK→CREB→基因表达（Arc、c-Fos）
- **PI3K/Akt/mTOR 通路**：神经元存活、局部蛋白合成

BDNF 对晚期 LTP（L-LTP）不可或缺，但对早期 LTP（E-LTP）影响较小（Bramham & Messaoudi 2005, PMID:16099088）。机制是 BDNF 驱动树突中 Arc mRNA 的局部翻译，Arc 蛋白调节肌动蛋白重塑和 AMPA 受体胞内转运，稳定树突棘。Lu et al. 2008（PMID:17942328）证明即便存在蛋白合成抑制剂，外源 BDNF 也可将 E-LTP 转化为持续 LTP，提示 BDNF 对已有蛋白质的调控也很重要。

在成年海马神经发生（SGZ）中，BDNF/TrkB 信号通过 PI3K/Akt（抗凋亡）和 MAPK/ERK（分化促进）分别支持新生颗粒细胞的存活和成熟。有氧运动上调血清 BDNF 水平，与人类海马体积增大相关（Erickson et al. 2011, PMID:21282661, RCT, n=120, 前海马体积+2%）。

在阿尔茨海默病中，BDNF/TrkB 信号是早期受损的靶点：死后脑组织研究显示海马和前额叶 BDNF 水平下降；Aβ 通过截断 TrkB→CREB 信号轴干扰 BDNF 信号（Colucci-D'Amato et al. 2020, PMID:33096634）。5×FAD 小鼠实验表明，单独增加 BDNF 或单独增加神经发生均不足以改善认知，而两者联合干预能完全模拟运动的认知改善效果（Choi et al. 2018, PMID:30190379）。

**慢性应激/糖皮质激素对 BDNF 的抑制**：慢性糖皮质激素过量是 BDNF 下调的重要内源性因素。GR 在慢性应激条件下通过**基因组路径**直接抑制 BDNF 转录：GR 结合 BDNF exon IV 启动子区域的负性糖皮质激素反应元件（negative GRE），使 BDNF exon IV mRNA↓30-50%（该亚型是海马最主要的活动依赖性 BDNF 异构体）。后果：① L-LTP 不能维持（E-LTP→L-LTP 转化需要 BDNF 驱动的 Arc 局部翻译）；② SGZ 新生神经元存活率↓（TrkB→PI3K/Akt 存活信号减弱）。这一路径使 BDNF 成为"慢性应激→突触损伤→认知下降"链条的**中间枢纽**：HPA 失调（慢性高皮质醇）→ GR 负调控 BDNF → L-LTP 失败 + 神经发生减少 → 海马记忆编码能力下降（综述于 de Kloet et al. 2005，PMID:15891777；Conrad 2008，PMID:19317179）。

## 关键机制

### 一、proBDNF/成熟 BDNF 的双向开关

```
BDNF前体(proBDNF)
    ↓ 胞内：furin/proprotein convertase
    ↓ 胞外：tPA/纤溶酶 (活动依赖性)
成熟BDNF (14 kDa)
    ↓ 高亲和力结合 TrkB
    → LTP促进 · 神经元存活 · 神经发生

proBDNF (32 kDa)
    ↓ 高亲和力结合 p75NTR
    → LTD促进 · 凋亡促进 · 突触弱化
```

关键点：胞外蛋白酶活性本身是突触方向性的调控变量——高活动时 tPA 活性高，更多 proBDNF 被切割为成熟 BDNF，系统偏向 LTP；低活动时，proBDNF 积累，系统偏向 LTD。

### 二、TrkB 三条信号通路

| 通路 | 触发点 | 关键适配蛋白 | 效果 | 时间尺度 |
|------|--------|-------------|------|---------|
| PLCγ→IP3/DAG→PKC/CaMKII | TrkB-Y816 | PLCγ（SH2域） | 突触可塑性（AMPA 受体修饰）；新生神经元存活（NFATc4） | 秒-分钟 |
| MAPK/ERK→CREB | TrkB-Y490 | Shc→Grb2-SOS→Ras | 基因转录（Arc、c-Fos、结构蛋白） | 分钟-小时 |
| PI3K/Akt/mTOR | TrkB-Y490 | Grb2-Gab1→PI3K | 存活（抗凋亡）、蛋白合成、记忆巩固 | 分钟-小时 |

**关键路由功能分工**（Minichiello 2002，PMID:12367511；Musumeci 2009，PMID:19675247）：
- Y816/PLCγ/CaMKII通路是**海马LTP和恐惧记忆获得**的主要分子执行者（trkB^PLC/PLC敲入小鼠LTP严重受损，Y816F→获得受损）
- Y490/PI3K/Akt通路对**记忆巩固和神经元长期存活**更重要（Y490F→巩固受损）
- 截断型TrkB-T1（成体脑中最丰富的TrkB异构体）缺乏激酶域→dominant negative效应；同时通过RhoGDI1独立信号调节星形胶质细胞骨架（Fenner 2012，PMID:22341689）

详细路由机制见 [[trkb-receptor]]。

### 三、BDNF 与 L-LTP 的正反馈循环

1. 高频突触活动 → NMDA-Ca²⁺ 内流 → CREB → BDNF 基因上调
2. 活动依赖性 BDNF 释放 → TrkB 激活
3. PLCγ→CaMKII：E-LTP 增强
4. ERK→Arc mRNA 局部翻译 → 树突棘稳定 → E-LTP→L-LTP 转化
5. PI3K/Akt/mTOR → 突触蛋白合成 → L-LTP 维持

### 四、BDNF 与 AD 的关键链

```
Aβ积累 → 激活 p38 MAPK / calcineurin → 
截断 TrkB→CREB 信号 → 
BDNF 下调 / 信号效率降低 → 
L-LTP 不能维持 · 新生神经元减少 →
认知储备下降
```

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| BDNF 对 L-LTP 必要，E-LTP 不受影响 | BDNF KO + 电生理；外源 BDNF 恢复 L-LTP | PMID:16099088（综述，多项研究） | 高（啮齿类） |
| proBDNF→p75NTR 选择性促进 LTD | p75NTR KO 小鼠；海马 LTD 选择性受损 | PMID:16025106 | 高（小鼠） |
| 有氧运动提高 BDNF，海马体积增大 2% | RCT n=120；结构 MRI + 血清 BDNF | PMID:21282661 (PMC3041121) | 高（人类 RCT） |
| Val66Met 使活动依赖性 BDNF 分泌受损 | 细胞荧光成像 + fMRI + 认知测试 | PMID:12553913 | 高（人类遗传+影像） |
| BDNF+AHN 协同恢复 AD 小鼠认知 | 5×FAD 多组对照（运动/遗传/药理） | PMID:30190379 (PMC6149542) | 高（动物；不可直接推广） |
| AD 中海马 BDNF/TrkB-CREB 信号受损 | 死后脑 + 转基因模型 | PMID:33096634 (PMC7589016) | 中（动物+人死后） |

## 连接

- [[ltp]] — BDNF 是 L-LTP（晚期 LTP）的必要信使；E-LTP 不依赖 BDNF
- [[ltd]] — proBDNF→p75NTR 促进 LTD；与成熟 BDNF→TrkB→LTP 构成双向调控
- [[adult-neurogenesis]] — BDNF/TrkB 是新生颗粒细胞存活和成熟的主要营养信号
- [[hippocampal-neurogenesis]] — SGZ 新生神经元 TrkB 信号维持存活（PI3K/Akt）
- [[alzheimers-disease]] — AD 中 BDNF 下降是早期病理靶点；Aβ 截断 TrkB→CREB
- [[arc-arg31]] — Arc 是 BDNF/ERK 通路驱动的局部翻译产物；稳定树突棘、调控 LTP→L-LTP
- [[synaptic-tagging-capture]] — L-LTP 的突触特异性由标签+BDNF 驱动的 PRP 合成共同实现
- [[nmda-receptor]] — NMDA 受体 Ca²⁺ 内流是 BDNF 上调的上游触发信号
- [[camkii]] — PLCγ/Ca²⁺ 通路激活 CaMKII；与 NMDA 通路并行的 LTP 维持机制
- [[engram-cells]] — 印迹细胞 AMPA/NMDA 比值高，可能部分由 BDNF 驱动的 L-LTP 解释
- [[glucocorticoid-hippocampus-plasticity]] — 慢性 GR 激活通过负性 GRE 直接抑制 BDNF exon IV 转录（BDNF↓30-50%）；BDNF 是 GC 慢性损害 LTP 的主要下游中间子
- [[hpa-axis]] — HPA 轴慢性过激活→皮质醇持续升高→GR 负性调控 BDNF→突触可塑性下降；是 HPA 失调的认知后果链
- [[trkb-receptor]] — TrkB 是 BDNF 的高亲和力受体；详细路由机制（Y490 vs Y816）、截断型 TrkB-T1 功能见该页面

## 未解问题

- Q-bdnf-01：BDNF 疗法的血脑屏障问题——有效的小分子 TrkB 激动剂能否在人类临床试验中取得成果？（目前仅动物模型；7,8-DHF 等候选分子）
- Q-bdnf-02：Val66Met 的实际认知风险权重——Meta 分析结果不一；其效应是否受运动习惯、压力暴露等环境因素显著调节？
- Q-bdnf-03：在 AD 中，BDNF/TrkB 信号下降是因（促进 Aβ 积累）还是果（被 Aβ 驱动下调）？纵向研究是否能在 Aβ 积累前测量到 BDNF 下降？

## 修订历史

- 2026-06-28 · 创建 · 基于《BDNF：大脑给自己的成长信号》一文 (#64) · 初始置信度：高（基础机制）/中（AD 及 Val66Met 部分）
- 2026-06-03 · 修订 rev2 · 基于《时间刻入神经回路：关键期》(#72) · 新增关键期相关角色：BDNF 通过 TrkB 加速 GABAergic 成熟（Huang 1999）、驱动 PV+ 细胞成熟时间轴、PNN-aggrecan-PTPσ 轴抑制 BDNF 信号进入 PV+ 细胞（Lesnikova 2021）；related 新增 critical-period, pv-interneurons, perineuronal-nets
- 2026-07-09 · 修订 rev3 · 基于《应激的双刃剑》(#77) · 新增"慢性应激/糖皮质激素对 BDNF 的抑制"段落（GR 负性 GRE→BDNF exon IV↓30-50%；L-LTP 失败和神经发生减少双重后果）；related 新增 glucocorticoid-hippocampus-plasticity、hpa-axis；key_sources 新增 PMID:15891777、PMID:19317179；opens_questions 新增 Q-stress-01；连接新增两条
- 2026-09-11 · 修订 rev4 · 基于《分子路由器》文章（#141）· TrkB三条通路表格增加适配蛋白列；新增Y816/Y490路由功能分工说明（Minichiello 2002, Musumeci 2009）；新增截断型TrkB-T1信息（Fenner 2012）；related新增trkb-receptor；key_sources新增PMID:12367511、PMID:19675247、PMID:22341689；连接新增trkb-receptor

## 来源文章

- [[2026-06-28-bdnf-trk-b-plasticity-memory]]
- [[2026-06-03-critical-period-plasticity]]
- [[2026-07-09-stress-glucocorticoid-hippocampus-hpa-axis]]

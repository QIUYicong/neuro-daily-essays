---
title: 脑源性神经营养因子（BDNF）
slug: bdnf
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-28
updated: 2026-10-21
revision_count: 4
dimensions: [molecular, cellular, synaptic, cognition, disease]
related: [ltp, ltd, adult-neurogenesis, hippocampal-neurogenesis, alzheimers-disease, nmda-receptor, camkii, arc-arg31, synaptic-tagging-capture, engram-cells, memory-consolidation, pattern-separation, critical-period, pv-interneurons, perineuronal-nets, huntingtons-disease, major-depressive-disorder, mtor]
prerequisites: [ltp, synaptic-transmission, nmda-receptor]
opens_questions: [Q-bdnf-01, Q-bdnf-02, Q-bdnf-03]
source_articles: [2026-06-28-bdnf-trk-b-plasticity-memory, 2026-06-03-critical-period-plasticity, 2026-09-07-huntingtons-disease-striatal-vulnerability-bdnf-polyglutamine, 2026-10-21-depression-ketamine-rapid-antidepressant]
key_sources: ["PMID:16099088", "PMID:33096634", "PMID:17942328", "PMID:16025106", "PMID:12553913", "PMID:21282661", "PMID:30190379", "PMID:23674053", "PMID:11408619", "PMID:15967378", "PMID:21677641", "PMID:30894661"]
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

| 通路 | 触发点 | 效果 | 时间尺度 |
|------|--------|------|---------|
| PLCγ→PKC/CaMKII | TrkB-Y816 | 突触可塑性（AMPA 受体修饰） | 秒-分钟 |
| MAPK/ERK→CREB | TrkB-Y490 | 基因转录（Arc、c-Fos、结构蛋白） | 分钟 |
| PI3K/Akt/mTOR | TrkB-Y490 | 存活（抗凋亡）、蛋白合成 | 分钟-小时 |

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

### 五、抑郁症与快速抗抑郁：eEF2K-BDNF 路径

**2026-10-21 新增（来自《氯胺酮与快速抗抑郁机制》#189）**

BDNF 在抑郁症中的特殊角色揭示了一个反直觉机制：静息态 NMDA 受体活动是 BDNF 翻译的**主动抑制器**。

**正常基线状态**：
- 突触自发活动持续激活低水平 NMDA 受体
- 维持 eEF2K（真核延伸因子 2 激酶）处于激活状态
- eEF2K 磷酸化 eEF2（翻译延伸因子），阻断 BDNF mRNA 的翻译延伸
- 因此，基线状态下 BDNF 蛋白水平受到主动压制

**抑郁状态下的加重**：
- 慢性应激通过糖皮质激素等机制，进一步降低 BDNF 基础水平
- mPFC/海马突触缺损的恶性循环

**氯胺酮的 30 分钟机制（Autry et al. 2011, PMID:21677641）**：
```
氯胺酮阻断静息态 NMDA 受体
    → eEF2K 活性↓ → p-eEF2↓
    → BDNF mRNA 翻译延伸解除阻断
    → 30 分钟内海马 BDNF 蛋白水平↑
    → 快速行为抗抑郁效果
```

关键区分：
- **30 分钟机制**（eEF2K→BDNF）：不依赖 mTOR，rapamycin 不能阻断
- **2-24 小时机制**（mTOR→突触蛋白合成）：需要 BDNF 先驱动 TrkB→mTOR，rapamycin 可阻断

SSRI 与快速抗抑郁药的本质差异在于 BDNF 释放模式：SSRI 通过基因转录→蛋白合成的迂回路线（2-4 周），快速抗抑郁药直接触发 BDNF **活动依赖性胞吐**（秒-分钟级）。Val66Met 多态性（损害活动依赖性 BDNF 分泌）使三类快速抗抑郁药（氯胺酮、东莨菪碱、HNK）均失效，证实此路径的核心地位（Duman 2019, PMID:30894661）。

### 六、HD 中的 BDNF-REST 轴断裂

亨廷顿病（HD）揭示了皮质纹状体 BDNF 营养供给的核心调控机制，是理解 BDNF 功能不可或缺的疾病窗口。

**正常轴**：野生型 huntingtin（wtHtt）将 REST（RE1 沉默转录因子 / NRSF）隔离于皮层神经元细胞质中，阻止其进入细胞核，从而解除 REST 对 BDNF exon II 启动子（RE1/NRSE 元件）的抑制 → 皮层高水平 BDNF 转录 → 沿皮质纹状体轴突顺行运输至纹状体 → 提供 MSN 存活必需的营养支持。

**断裂**：mutant huntingtin（mHTT）失去对 REST 的隔离能力 → REST 自由入核 → 占据 BDNF exon II 启动子 RE1 元件 → 皮层 BDNF 转录↓ → 纹状体 MSN 营养饥饿。

**关键不对称**：纹状体 MSN 自身 BDNF 产生量极低，几乎完全依赖皮质衍生 BDNF——皮层神经元尚有一定自给能力，MSN 是纯粹的营养依赖方。BDNF 断粮对 MSN 的打击是首要且无缓冲的（Zuccato & Cattaneo 2001，PMID:11408619；2005，PMID:15967378）。

```
wtHtt → 隔离 REST 于细胞质 → BDNF 启动子（RE1）解抑制 → 皮层 BDNF↑ → 纹状体 MSN 存活
mHTT → 失去 REST 隔离 → REST 入核 → BDNF 启动子抑制 → 皮层 BDNF↓ → MSN 营养饥饿
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
| wtHtt促进皮层BDNF转录；mHTT通过REST入核使皮层BDNF进行性减少 | HD小鼠模型（R6/2, YAC128等）+ REST机制分析 | PMID:11408619; PMID:15967378 | 高（多模型收敛） |

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
- [[huntingtons-disease]] — mHTT 破坏 wtHtt 对 REST 的隔离 → REST 入核抑制 BDNF 转录 → 皮质纹状体 BDNF 营养轴断裂 → MSN 选择性营养饥饿
- [[major-depressive-disorder]] — MDD 中 BDNF 减少是突触缺损的核心中间步骤；eEF2K-BDNF 路径是氯胺酮 30 分钟快速抗抑郁机制的分子基础

## 未解问题

- Q-bdnf-01：BDNF 疗法的血脑屏障问题——有效的小分子 TrkB 激动剂能否在人类临床试验中取得成果？（目前仅动物模型；7,8-DHF 等候选分子）
- Q-bdnf-02：Val66Met 的实际认知风险权重——Meta 分析结果不一；其效应是否受运动习惯、压力暴露等环境因素显著调节？
- Q-bdnf-03：在 AD 中，BDNF/TrkB 信号下降是因（促进 Aβ 积累）还是果（被 Aβ 驱动下调）？纵向研究是否能在 Aβ 积累前测量到 BDNF 下降？

## 修订历史

- 2026-06-28 · 创建 · 基于《BDNF：大脑给自己的成长信号》一文 (#64) · 初始置信度：高（基础机制）/中（AD 及 Val66Met 部分）
- 2026-06-03 · 修订 rev2 · 基于《时间刻入神经回路：关键期》(#72) · 新增关键期相关角色：BDNF 通过 TrkB 加速 GABAergic 成熟（Huang 1999）、驱动 PV+ 细胞成熟时间轴、PNN-aggrecan-PTPσ 轴抑制 BDNF 信号进入 PV+ 细胞（Lesnikova 2021）；related 新增 critical-period, pv-interneurons, perineuronal-nets
- 2026-09-07 · 修订 rev3 · 基于《亨廷顿病：纹状体选择性脆弱性》(#137) · 新增"HD中的BDNF-REST轴断裂"机制节（PMID:11408619/15967378）；关键证据新增HD wtHtt/REST/BDNF轴一行；related新增huntingtons-disease；key_sources新增PMID:11408619/15967378
- 2026-10-21 · 修订 rev4 · 基于《氯胺酮与快速抗抑郁机制》(#189) · 新增"抑郁症与快速抗抑郁：eEF2K-BDNF路径"机制节（Autry 2011 PMID:21677641；Duman 2019 PMID:30894661）；阐明静息态NMDA主动压制BDNF翻译（eEF2K门控机制）及30分钟vs2-24小时两阶段时序；连接新增major-depressive-disorder；related新增major-depressive-disorder、mtor；key_sources新增PMID:21677641/30894661；source_articles新增#189

## 来源文章

- [[2026-06-28-bdnf-trk-b-plasticity-memory]]
- [[2026-06-03-critical-period-plasticity]]
- [[2026-09-07-huntingtons-disease-striatal-vulnerability-bdnf-polyglutamine]]
- [[2026-10-21-depression-ketamine-rapid-antidepressant]]

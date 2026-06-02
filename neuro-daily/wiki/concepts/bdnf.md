---
title: 脑源性神经营养因子（BDNF）
slug: bdnf
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-28
updated: 2026-06-29
revision_count: 2
dimensions: [molecular, cellular, synaptic, cognition, disease]
related: [ltp, ltd, adult-neurogenesis, hippocampal-neurogenesis, alzheimers-disease, nmda-receptor, camkii, arc-arg31, synaptic-tagging-capture, engram-cells, memory-consolidation, pattern-separation, critical-period, v1-primary-visual-cortex, perineuronal-nets]
prerequisites: [ltp, synaptic-transmission, nmda-receptor]
opens_questions: [Q-bdnf-01, Q-bdnf-02, Q-bdnf-03, Q-cp-04]
source_articles: [2026-06-28-bdnf-trk-b-plasticity-memory, 2026-06-29-critical-period-visual-cortex]
key_sources: ["PMID:16099088", "PMID:33096634", "PMID:17942328", "PMID:16025106", "PMID:12553913", "PMID:21282661", "PMID:30190379", "PMID:23674053", "PMID:14514885", "PMID:32503914"]
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
- [[critical-period]] — BDNF 是关键期调控的分子枢纽：促进 PV+细胞成熟 → 触发关键期开启
- [[v1-primary-visual-cortex]] — V1 关键期内 BDNF 过表达绕过视觉经验，直接驱动 PV+细胞成熟
- [[perineuronal-nets]] — PNNs 形成与 BDNF 调控的 PV+细胞成熟程序协调进行

## BDNF 在关键期中的特殊作用（2026-06-29 补充）

BDNF 不只是突触可塑性信号，还是**调控关键期时序的关键分子**：

- **BDNF 过表达 → 提前开启关键期**：BDNF 转基因小鼠在暗养条件下（无视觉经验），视觉皮层功能（视力、感受野大小、E/I 平衡）与正常光照动物相同（Gianfranceschi et al. 2003, PMID:14514885）
- **机制**：BDNF 通过 TrkB→ERK 通路驱动 PV+细胞 parvalbumin 表达和 GABAergic 突触成熟；BDNF 信号加速 L4 层的 E/I 平衡转变
- **视觉经验 → BDNF 上调 → PV+细胞成熟 → 关键期开启**：这是一个正反馈回路，也解释了为什么暗养（减少视觉活动→减少 BDNF→延缓 PV+成熟）延迟关键期
- **跨时间尺度一致性**：BDNF 在 L-LTP（小时-天尺度）和关键期调控（周-月尺度）中都发挥核心作用，提示 BDNF/TrkB 信号是神经系统可塑性的通用分子杠杆

## 未解问题

- Q-bdnf-01：BDNF 疗法的血脑屏障问题——有效的小分子 TrkB 激动剂能否在人类临床试验中取得成果？（目前仅动物模型；7,8-DHF 等候选分子）
- Q-bdnf-02：Val66Met 的实际认知风险权重——Meta 分析结果不一；其效应是否受运动习惯、压力暴露等环境因素显著调节？
- Q-bdnf-03：在 AD 中，BDNF/TrkB 信号下降是因（促进 Aβ 积累）还是果（被 Aβ 驱动下调）？纵向研究是否能在 Aβ 积累前测量到 BDNF 下降？

## 修订历史

- 2026-06-28 · 创建 · 基于《BDNF：大脑给自己的成长信号》一文 (#64) · 整合 8 篇来源（4 篇 PMC 开放全文）· 填补多个 wiki 页面的悬空引用 [[bdnf]] · 初始置信度：高（基础机制）/中（AD 及 Val66Met 部分）
- 2026-06-29 · 修订 · 基于《窗口之谜：视觉皮层关键期》一文 (#65) · 新增"BDNF 在关键期中的特殊作用"小节；related 新增 critical-period、v1-primary-visual-cortex、perineuronal-nets；opens_questions 新增 Q-cp-04；key_sources 新增 PMID:14514885、PMID:32503914

## 来源文章

- [[2026-06-28-bdnf-trk-b-plasticity-memory]]
- [[2026-06-29-critical-period-visual-cortex]]

---
title: 关键期（视觉皮层）
slug: critical-period
domain: concepts
type: concept
status: established
confidence: high
created: 2026-06-29
updated: 2026-06-29
revision_count: 1
dimensions: [molecular, cellular, microcircuit, brain-region, behavior, cognition]
related: [v1-primary-visual-cortex, bdnf, perineuronal-nets, pv-interneurons, gamma-oscillations, orientation-selectivity, adult-neurogenesis, ltp, ltd]
prerequisites: [synaptic-transmission, ltp, v1-primary-visual-cortex]
opens_questions: [Q-cp-01, Q-cp-02, Q-cp-03, Q-cp-04, Q-cp-05]
source_articles: [2026-06-29-critical-period-visual-cortex]
key_sources: ["PMID:15217343", "PMID:10724170", "PMID:15017002", "PMID:12424383", "PMID:22462544", "PMID:32503914", "PMC7519216", "PMID:29905116", "PMC6047524"]
---

# 关键期（Critical Period）

> **一句话定义**：关键期是神经系统发育中的时间限定可塑性窗口——在此期间特定经验可永久且大幅改写神经回路，而同样的经验在窗口之外效果极为有限；以视觉皮层眼优势可塑性为最经典模型，其开启依赖 GABA 能 PV+中间神经元的成熟，关闭由围神经元网等分子制动器积极维持。

## 当前理解

我们现在认为：关键期不是大脑"年幼时更可塑"的笼统描述，而是一个被精确分子机制调控的**可塑性许可状态**——有精确的开窗时机（由 GABA 能抑制成熟触发）、有积极维持的关闭状态（由围神经元网、Lynx1、PSD-95 等"分子制动器"维持），并且原则上可以在成年后通过靶向移除这些制动器来重新开启（Hensch 2004, PMID:15217343；Pizzorusso et al. 2002, PMID:12424383）。

关键期的三个核心特征：
1. **时间精确性**：有明确的开窗和关窗时间（小鼠 V1 约 P28–P35 为峰值）
2. **效果不对称性**：窗口内剥夺造成的缺陷往往超出窗口后的效果，且难以逆转
3. **主动调控性**：可以被提前开启（BDNF 过表达）、延迟（暗养）或在成年后重新激活（软骨素酶、HDAC 抑制剂）

## 关键机制

### 关键期的触发：GABA 阈值与 PV+细胞

关键期不由兴奋性活动直接触发，而由 **GABA 能抑制回路达到特定成熟阈值**触发（Fagiolini & Hensch 2000, PMID:10724170）：
- GAD65 基因敲除小鼠（GABA 合成酶不足）永远不进入关键期
- 苯二氮䓬类（增强 GABA）在任何年龄均能人工触发关键期
- 具体亚型：GABA_A **α1 亚基**介导关键期触发（而非 α2）（Fagiolini et al. 2004, PMID:15017002）

触发关键期的核心细胞是**小清蛋白阳性快脉冲中间神经元（PV+ cells）**：
- 发育后期 PV+细胞成熟，提供强大的体周抑制
- PV+细胞生成 γ 振荡（40–80 Hz），与可塑性窗口相关
- BDNF 活动依赖性上调加速 PV+细胞成熟（Gianfranceschi et al. 2003, PMID:14514885）

### 关键期内的回路变化：单眼剥夺的双相动力学

关键期内单眼剥夺（MD）产生双相 OD 偏移（Espinosa & Stryker 2012, PMID:22841309）：
- **快（~3 天）**：剥夺眼皮层响应被抑制（类 LTD 机制）
- **慢（~5 天以上）**：开放眼皮层代偿性扩张（蛋白合成依赖）

结构层面：tPA（组织型纤溶酶原激活物）介导锥体细胞顶树突棘的瞬时修剪（仅在关键期内发生）（Mataga et al. 2004, PMID:15603745）

### 关键期的关闭：分子制动器系统

多种分子"制动器"积累导致关键期关闭（Hensch & Quinlan 2018, PMID:29905116）：

| 制动器 | 机制 | 证据 |
|-------|------|------|
| 围神经元网（PNNs）| 包裹 PV+细胞，物理+信号屏障 | 软骨素酶降解后成年 MD 恢复效果，PMID:12424383 |
| Lynx1 | 内源性 nAChR 变构抑制剂，减弱 ACh 调制 | Lynx1 KO 成年仍保有关键期样可塑性 |
| PSD-95 上调 | 稳定 AMPA 受体，减弱突触可塑性 | — |
| NR2B→NR2A 转换 | 缩短 NMDA 受体钙流时窗 | — |

### 多时间尺度调控（Reh et al. 2020, PMC7519216）

| 时间尺度 | 机制 | 效果 |
|---------|------|------|
| 毫秒-秒 | PV+细胞 γ 振荡 | 实时可塑性窗口开合 |
| 天-月 | CLOCK/BMAL 昼夜节律基因调控 PV 成熟 | CLOCK KO 延迟关键期 |
| 年-代际 | 表观遗传（组蛋白乙酰化）、跨代精子 RNA | ELA 损害关键期时序；EE 延长关键期 |

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| GABA 阈值触发关键期 | GAD65 KO + BDZ 实验 | PMID:10724170 | 高 |
| α1 亚基是特异触发者 | α1 点突变体小鼠 | PMID:15017002 | 高 |
| PNNs 是关键期关闭机制 | 暗养相关性 + 软骨素酶功能证明 | PMID:12424383 | 高 |
| MD 仅在关键期内修剪树突棘 | tPA KO 实验 + 时间对照 | PMID:15603745 | 高 |
| BDNF 过表达提前开启关键期 | BDNF 过表达转基因小鼠 | PMID:14514885 | 高 |
| HDAC 抑制剂成年重启可塑性 | 药理实验（啮齿动物） | PMID:32503914 | 中（啮齿动物，人类未验证） |

## 连接

- [[v1-primary-visual-cortex]] — 关键期最经典的研究系统（OD 可塑性）
- [[bdnf]] — 调控 PV+细胞成熟，促进关键期开启
- [[perineuronal-nets]] — 关键期关闭的主要结构机制
- [[gamma-oscillations]] — PV+细胞 γ 振荡与可塑性窗口的实时调控
- [[ltp]] — 关键期可塑性部分依赖 LTP 样突触增强
- [[ltd]] — 关键期内剥夺眼抑制的第一相机制
- [[adult-neurogenesis]] — 另一种成年保留的神经可塑性形式，时间调控有相似原则
- [[orientation-selectivity]] — V1 方向选择性在关键期内通过经验精细化

## 未解问题

- Q-cp-01（高）：关键期关闭的主导制动器是哪个？PNNs、Lynx1、PSD-95 的相对权重？
- Q-cp-02（高）：如何安全地在人类成年视觉皮层重启可塑性？
- Q-cp-03（中）：PNNs 的精确信号机制（物理、受体、Otx2 固定？）
- Q-cp-04（中）：语言关键期是否遵循与视觉关键期相同的 GABAergic-PV+ 机制？
- Q-cp-05（中）：关键期的跨代遗传机制有多稳健？

## 修订历史

- 2026-06-29 · 创建 · 基于《窗口之谜：视觉皮层关键期如何将经验烧录进回路》(#65) · 初始置信度：高 · 核心来源：Reh 2020 (PMC7519216)、Hensch & Quinlan 2018 (PMC6047524) 开放全文；Fagiolini & Hensch 2000、Pizzorusso 2002 等经典论文摘要

## 来源文章

- [[2026-06-29-critical-period-visual-cortex]]

---
title: 神经元周围网
slug: perineuronal-nets
domain: concepts
type: structure
status: established
confidence: high
created: 2026-06-24
updated: 2026-06-24
revision_count: 1
dimensions: [molecular, cellular, developmental]
related: [critical-period, pv-interneurons, synaptic-pruning, hebbian-learning]
prerequisites: [pv-interneurons, critical-period]
opens_questions: [Q-sp-02]
source_articles: [2026-06-24-synaptic-pruning-critical-period]
key_sources: ["PMID:16261181", "PMID:32503914", "PMID:40067078"]
---

# 神经元周围网 (Perineuronal Nets, PNNs)

> **一句话定义**：由硫酸软骨素蛋白聚糖、透明质酸、连接蛋白等细胞外基质分子形成的致密网格结构，优先包裹快速放电的 PV+ 中间神经元，随发育成熟逐渐形成，是关键期关闭的分子标志。

## 当前理解

我们现在认为，神经元周围网（PNNs）是大脑"关键期关闭"的主要分子执行者。PNNs 的形成时间与关键期关闭的时间高度吻合，实验降解 PNNs 可在成年动物重开部分可塑性。

PNNs 主要包绕**PV+ 中间神经元**（小清蛋白阳性快速放电细胞），偶尔也出现于其他细胞类型。其分子组成包括：
- **硫酸软骨素蛋白聚糖（CSPGs）**：如 aggrecan、brevican、neurocan、versican；
- **透明质酸（hyaluronic acid）**：骨架成分；
- **连接蛋白（link proteins）**：如 Hapln1、Hapln4；
- **腱糖蛋白-R（tenascin-R）**：交联成分。

关键实验：用硫酸软骨素酶 ABC（ChABC）降解 CSPGs → 成年小鼠恢复眼优势可塑性（Hensch 2005, PMID:16261181 综述引述），证明 PNNs 是维持成年大脑低可塑性状态的主动机制，而非仅仅是被动的解剖结构。

## 关键机制

### 形成时间

- 视觉皮层：小鼠约 P28–P35 后显著出现（关键期关闭期），之后持续致密化；
- 不同区域形成时间差异反映各区域关键期的先后顺序；

### 如何关闭可塑性

**物理屏障**：PNNs 致密网络物理约束 PV 细胞树突上的突触接触点，限制新突触的形成和重组。

**生长因子隔绝**：PNNs 与 BDNF 等神经营养因子结合，限制其在局部微环境的弥散，降低突触可塑性信号浓度。

**氧化保护**：PV 细胞对活性氧（ROS）高度敏感，PNNs 提供物理-化学双重保护，维持 PV 细胞的正常功能；降解 PNNs 会增加 PV 细胞的氧化应激易感性。

**受体稳定**：PNNs 固定 PV 细胞表面受体分布（如 GABA-A 受体），减少经验驱动的受体侧向移动和重新分布。

### Otx2 调控 PNN 形成

Reh et al. 2020（PMID:32503914, PMCID:PMC7519216）报告：
- Otx2（一种同源域转录因子）从视网膜 → 丘脑 → 皮层转运；
- Otx2 加速 PV 细胞中 PNN 成分的表达，提前关闭关键期；
- 中和 Otx2 可延长关键期。

这提示视觉经验（通过 Otx2 转运信号）本身参与调控关键期的关闭时机，是一种"用经验来决定何时停止经验可塑性"的负反馈机制。

### PNNs 的可逆性

尽管 PNNs 是关键期关闭的主要机制，它们并非永久性结构：
- **ChABC 注射**：降解 CSPGs，短暂重开可塑性窗口（动物研究）；
- **暗适应数天**：减少 Otx2 转运，部分减少 PNN 密度；
- **某些抗抑郁药（如氟西汀）**：可减少 PV+ 细胞 PNN 强度（Jetsonen et al. 2025, PMID:40921785）；
- **中风后康复**：卒中后 PV+/PNN 细胞减少，与运动功能恢复相关（Kuhl et al. 2025, PMID:39819253）。

这说明 PNNs 是动态调控的，大脑的"关键期之锁"并非一旦锁上就无法打开。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| PNN 形成时间与关键期关闭吻合 | 免疫组化（WFA 凝集素标记）+ 眼优势测量 | PMID:16261181（综述） | 高 |
| ChABC 降解 PNNs 恢复成年可塑性 | ChABC 注射 + 眼优势偏移测量 | PMID:16261181（综述引述） | 高 |
| Otx2 转运加速 PNN 成熟、提前关闭关键期 | Otx2 中和抗体实验 + 免疫组化 | PMID:32503914, PMC:PMC7519216 | 中（综述引述，来自其他实验室研究） |
| PNN 密度跨大脑区域和物种存在异质性 | WFA 组化 + CS 二糖分析 | PMID:40067078 | 中 |

## 连接

- [[critical-period]] — PNNs 形成标志关键期关闭
- [[pv-interneurons]] — PNNs 优先包裹 PV+ 细胞
- [[synaptic-pruning]] — 修剪主要在 PNNs 形成前（关键期内）完成

## 未解问题

- Q-sp-02（中优先级）：PNNs 通过什么具体分子机制"锁住" PV 细胞的可塑性？是否存在 PNN 成分的功能异质性（不同 CSPG 亚型的作用差异）？

## 修订历史

- 2026-06-24 · 创建 · 基于《用进废退的精密刻刀》一文 · 初始置信度：高

## 来源文章

- [[2026-06-24-synaptic-pruning-critical-period]]

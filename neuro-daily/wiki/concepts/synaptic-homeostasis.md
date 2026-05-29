---
title: 突触稳态假说
slug: synaptic-homeostasis
domain: concepts
type: theory
status: mainstream
confidence: high
created: 2026-06-01
updated: 2026-06-01
revision_count: 1
dimensions: [molecular, cellular, synaptic, whole-brain-network, behavior]
related: [memory-consolidation, ltp, sleep-spindles, slow-oscillations, engram-cells]
prerequisites: [ltp, synaptic-transmission, ampa-receptor]
opens_questions: []
source_articles: [2026-06-01-memory-consolidation-sleep]
key_sources: ["PMID:30614089", "PMID:31263066", "PMID:38973508"]
---

# 突触稳态假说 (Synaptic Homeostasis Hypothesis, SHY)

> **一句话定义**：SHY 由 Tononi & Cirelli 提出，认为清醒学习导致突触普遍净增强（synaptic net potentiation），而睡眠（尤其 NREM）通过选择性突触下调（synaptic down-selection）恢复稳态——使重要记忆的突触相对更强、背景突触被削弱，从而提高信噪比并恢复大脑的学习容量。

## 当前理解

我们现在认为，SHY 解决了一个基本问题：如果清醒学习持续增强突触，突触将趋于饱和（saturation），信噪比下降，新学习能力丧失，且代谢成本无法承受。睡眠提供了系统性重置的机会。

SHY 的核心预测已获电镜层面的直接证实：睡眠后皮层突触轴突-棘突接触面积平均缩小约 **18%**（De Vivo et al., 2017），且下调呈大小依赖性——小突触优先缩小，最大突触受保护。这被解读为对重要记忆的选择性保护。

**SHY 与主动系统巩固（SWR 重播）的关系**：两者不互斥。
- SWR 重播保护了参与编码特定记忆的特定突触（相对保留或甚至强化）。
- SHY 对大多数弱突触实施稳态下调。
- 净效果：信噪比提升，记忆的提取效率更高，下次学习的空间被腾出。

目前对 SHY 的主要批评是：它不能单独解释睡眠对某些记忆的选择性强化（如只有睡了觉才记住的词汇），需要与重播机制联合才能完整解释。

## 关键机制

- **Homer1a**：在睡眠期间积累于突触，促进 AMPA 受体从突触后膜内吞，弱化突触。
- **Arc（活性调控细胞骨架相关蛋白）**：选择性弱化低活动突触；在激活突触中表达受抑制。
- **GSK-3β（糖原合成酶激酶 3β）**：可能标记需要保护的突触（高活动 = 磷酸化 = 保护）。
- 大小依赖性保护：最大的突触（对应最重要/最强烈的记忆）下调幅度最小，甚至被豁免。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 睡眠后皮层突触平均缩小约 18% | 电镜三维重建（~7000 突触） | Tononi & Cirelli 2020, PMC6612535 | 高 |
| 睡眠剥夺后 CA1 突触密度增加 | 电镜（青春期小鼠 CA1） | Spano et al. 2019, PMID:31263066 | 高 |
| NREM 睡眠后皮层 GluA1 AMPA 受体下降 | 膜片钳 + 生化分析 | Squarcio et al. 2024, PMC11895523 | 高 |

## 连接

- [[memory-consolidation]] — SHY 是记忆巩固的稳态维度，与主动重播共同优化信噪比
- [[ltp]] — SHY 是 LTP 的稳态"对冲"：清醒期 LTP 提升突触权重，睡眠期 SHY 整体下调
- [[engram-cells]] — 印迹细胞对应的突触在 SHY 中受保护
- [[ampa-receptor]] — AMPA 受体的表面表达水平是 SHY 的关键分子指标

## 未解问题

- SHY 的大小依赖性保护的精确分子机制是什么？（GluA1 磷酸化？突触标签？）
- 清醒期与睡眠期突触的绝对强度随年龄如何变化？（青春期 vs. 成年 vs. 老年）
- REM 睡眠对 SHY 过程的贡献是什么？

## 修订历史

- 2026-06-01 · 创建 · 基于《记忆固化的夜间工厂》文章 · 初始置信度：高

## 来源文章

- [[2026-06-01-memory-consolidation-sleep]]

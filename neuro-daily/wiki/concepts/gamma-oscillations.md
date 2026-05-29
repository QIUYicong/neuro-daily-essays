---
title: γ 振荡（Gamma Oscillations）
slug: gamma-oscillations
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-05
updated: 2026-06-05
revision_count: 1
dimensions: [microcircuit, brain-region, cognition, cellular]
related: [pv-interneurons, working-memory, persistent-activity, prefrontal-cortex, theta-oscillations, temporal-coding-hierarchy]
prerequisites: [pv-interneurons, action-potential, synaptic-transmission]
opens_questions: [Q-gamma-wm-causality, Q-gamma-capacity]
source_articles: [2026-06-05-prefrontal-working-memory]
key_sources: ["PMID:26996084", "PMID:39381500", "PMID:41478518"]
---

# γ 振荡 (Gamma Oscillations, 30–80 Hz)

> **一句话定义**：由 PV+ 快速放电中间神经元与锥体细胞的快速兴奋-抑制循环产生的 30–80 Hz 皮层节律；在 PFC 中以短暂爆发形式（~67 ms）参与工作记忆的间歇性信息编码，在精神分裂症中功率减弱。

## 当前理解

γ 振荡（Gamma oscillations，30–80 Hz）是大脑皮层和海马中广泛存在的高频振荡，由 PV+ 快速放电中间神经元（篮状细胞为主）与锥体细胞的**互动抑制回路（PING/ING机制）**产生。

在 PFC 工作记忆中（Lundqvist et al. 2016，PMID:26996084），γ 振荡以**爆发（bursts）**而非持续振荡的形式出现：
- 工作记忆编码和读取时出现 γ 爆发（45–100 Hz，~67 ms/次）
- 爆发期间神经元精确编码记忆内容（信息解码清晰）
- 维持期（无需主动读取时）：γ 减弱，β 振荡（20–35 Hz）出现，代表"默认静息态"

γ 振荡与 θ 振荡（4–12 Hz）通过**嵌套耦合（theta-gamma coupling）**协作：每个 θ 周期（~125 ms）内嵌套约 5–7 次 γ 爆发，可能是工作记忆容量约 4–7 项的节律基础。

## 生成机制（PING 机制）

1. 锥体细胞放电 → 兴奋 PV 篮状细胞
2. PV 篮状细胞产生强力 GABA 抑制锥体细胞（~10–15 ms 抑制窗口）
3. 抑制解除后（GABA_A 衰减），锥体细胞再次去极化放电
4. 循环重复，产生 ~40–80 Hz 节律

关键：PV 细胞的快速放电能力（无适应）和 GABA_A 受体的快速动力学保证了高频节律的精度。

## 在精神分裂症中的病理证据（Hughes et al. 2024, PMID:39381500）

- dlPFC 中 PV mRNA 减少（多项研究一致）
- GAD67 蛋白在 PV 轴突终末中降低（影响 GABA 合成）
- 工作记忆任务中 dlPFC γ 功率不能正常升高
- γ 功率降低与认知损伤（工作记忆、注意）显著相关

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| PFC WM 延迟期出现 γ 爆发（非持续） | 猕猴 PFC 时频分析 | Lundqvist et al. 2016 (PMID:26996084, PMC:PMC5220584) | 中-高 |
| PV 细胞是 γ 生成的关键细胞类型 | PV 敲除/调控实验 | 综述 Boroujeni et al. 2026 (PMID:41478518) | 高 |
| 精神分裂症 dlPFC γ 功率降低 | 人类 dlPFC 尸检 + 影像 | Hughes et al. 2024 (PMID:39381500, PMC:PMC11458443) | 高 |

## 连接

- [[pv-interneurons]] — γ 振荡的主要生成者（PING 机制的关键细胞）
- [[working-memory]] — γ 爆发是工作记忆活动性编码的神经振荡载体
- [[persistent-activity]] — γ 爆发是持续活动的实际振荡形式
- [[theta-oscillations]] — θ/γ 嵌套：θ 提供时间框架，γ 承载内容
- [[temporal-coding-hierarchy]] — γ/θ 嵌套编码层级

## 未解问题

- Q-gamma-wm-causality：γ 爆发是工作记忆的因果机制还是相关物？（缺乏人类光遗传学证据）
- Q-gamma-capacity：θ/γ 嵌套是否是工作记忆 ~4 项容量的节律基础？

## 修订历史

- 2026-06-05 · 创建 · 基于《γ爆发、静默突触与持续放电》一文 · 初始置信度：高

## 来源文章

- [[2026-06-05-prefrontal-working-memory]]

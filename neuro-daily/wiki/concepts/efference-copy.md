---
title: 传出拷贝（效应传出）
slug: efference-copy
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-31
updated: 2026-07-31
revision_count: 1
dimensions: [cellular, brain-region, whole-brain-network, behavior, cognition]
related: [vestibular-system, forward-model, cerebellum, predictive-coding, corollary-discharge]
prerequisites: [action-potential, forward-model, cerebellum]
opens_questions: [Q-vest-03, Q-stdp-physiological-ca]
source_articles: [2026-07-31-vestibular-system-vor-efference-copy]
key_sources: ["PMID:31401034", "PMCID:PMC6733654", "PMID:21286693", "PMID:37739815", "PMCID:PMC10591839"]
---

# 传出拷贝（效应传出） (Efference Copy / Corollary Discharge)

> **一句话定义**：运动指令在输出到肌肉的同时，向感觉处理系统发送的一份副本，使大脑能预测自身运动将产生的感觉后果，并在最早的感觉处理中枢（而非皮层）就区分"自我生成的感觉"（可预测→抑制）和"外界施加的感觉"（意外→需响应）。

## 当前理解

我们现在认为，传出拷贝（efference copy）/ 效应传出副本（corollary discharge）是大脑中**"主动感知"原则的神经底层实现**。这一概念最初由 von Holst 和 Mittelstaedt（1950）提出（称为"效应传出与传入比较"），后来由 Sperry（1950）独立提出（称为 corollary discharge）。

核心工作原理：
1. 运动指令（efference）发出 → 一份副本（copy）同时送达感觉处理系统
2. 感觉处理系统利用这份副本**预测**即将到来的感觉反馈
3. 当实际感觉与预测**匹配**：感觉信号被抑制（自我生成，不需要特别响应）
4. 当实际感觉与预测**不匹配**：感觉信号得到充分处理（外界干扰，需要响应）

在前庭系统中，这一机制有最清晰的神经科学证据：前庭核的 VO 神经元在主动运动时被抑制约 70-80%，且仅在本体感觉反馈与传出拷贝的预测精确匹配时才发生（Brooks & Cullen 2019, PMID:31401034）。这种抑制不是粗糙的"运动时压制感觉"，而是精确的"预测-匹配驱动的选择性抑制"。

传出拷贝机制并非前庭系统专属——在躯体感觉系统（"自我挠痒"减弱触觉感知）、听觉系统（发声时减弱自身发声引起的听觉响应）中均有类似机制，且在小脑损伤后均受损，提示小脑是生成这些预测信号的核心结构。

## 关键机制

### 1. 前庭系统中的传出拷贝路径（最清晰的案例）

```
运动皮层/脑干运动核 → 运动指令 → 颈部肌肉（实际运动）
                    ↓ 副本（传出拷贝）
               前蚓部（anterior vermis of cerebellum）
                    ↓ 预测本体感觉反馈
               若预测 = 实际本体感觉反馈：
                    ↓ 消除信号
               前庭核 VO 神经元（~70-80% 抑制）
               → 不触发不必要的代偿反应
```

### 2. 抑制的条件依赖性

关键实验（Brooks & Cullen 2019）：注射神经肌肉阻断剂使颈部肌肉麻痹：
- 大脑发出运动指令（传出拷贝产生）
- 但肌肉无法运动 → 无本体感觉反馈
- → 消除信号消失 → VO 神经元正常响应

这证明：消除信号的触发条件是**"传出拷贝的预期反馈" = "实际本体感觉反馈"**，而不是单纯的"有运动指令发出"。

### 3. 学习与更新

当运动-感觉映射改变时（如安装新假肢、适应棱镜眼镜），消除信号初期不准确 → 感觉信号传递充分 → 通过小脑可塑性更新预测内部模型 → 消除信号重新变准确。这是传出拷贝系统适应性更新的直接证据（Cullen 2023, PMID:37739815）。

### 4. 跨感觉系统的泛化

| 系统 | 自我生成信号 | 抑制位点 | 证据强度 |
|------|------------|---------|--------|
| 前庭 | 主动头部旋转 | 前庭核 VO 神经元 | 高（灵长类体内） |
| 躯体感觉 | 自我挠痒 | 丘脑体感核 | 中（行为+fMRI） |
| 听觉 | 自身发声 | 下丘/听觉皮层 | 高（多物种） |

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| VO 神经元在主动运动时抑制 ~70-80% | 清醒猴，主动 vs 被动头部旋转，前庭核单神经元记录 | PMID:21286693 | 高 |
| 抑制依赖"预测=实际"匹配，非单纯运动指令 | 肌肉麻醉实验：有指令无运动 → 抑制消失 | PMID:31401034 | 高 |
| 前蚓部损伤破坏传出拷贝消除信号 | 小脑区域损伤后主动运动抑制消失 | PMID:37739815 | 高 |
| 消除信号在新运动-感觉关系中可重新学习 | 假肢适应实验 | PMID:31401034 | 中 |

## 连接

- [[vestibular-system]] — 传出拷贝最清晰的体内实例；前庭核 VO 神经元的主动运动抑制
- [[forward-model]] — 传出拷贝是前向模型的"输入"；前向模型使用传出拷贝预测感觉后果
- [[cerebellum]] — 小脑（前蚓部）是生成消除信号的关键结构
- [[predictive-coding]] — 传出拷贝机制是从脑干层次开始的预测性感觉处理；比皮层预测编码更早
- [[path-integration]] — 路径整合依赖传出拷贝（主动运动的前庭信号 + 本体感觉）驱动网格细胞更新

## 未解问题

- Q-vest-03（中）：精神分裂症患者的传出拷贝机制是否受损？内语（inner speech）的 corollary discharge 衰减是否导致幻听？
- 见 unresolved_questions.md 中 Q-vest-01 至 Q-vest-03

## 修订历史

- 2026-07-31 · 创建 · 基于《平衡的物理学》（#99）· 前向模型页面（forward-model.md）已将 efference-copy 列为 related 但无页面 · 今日补建 · 初始置信度：高（前庭系统直接体内证据充分）

## 来源文章

- [[2026-07-31-vestibular-system-vor-efference-copy]]

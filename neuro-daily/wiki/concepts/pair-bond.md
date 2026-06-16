---
title: 配对键
slug: pair-bond
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-16
updated: 2026-06-16
revision_count: 2
dimensions: [molecular, synaptic, microcircuit, brain-region, behavior]
related: [oxytocin-system, vasopressin-system, dopamine-system, nucleus-accumbens, social-reward, endocannabinoid-system]
prerequisites: [oxytocin-system, vasopressin-system, dopamine-system, long-term-potentiation]
opens_questions: [Q-OT-03]
source_articles: [2026-06-16-oxytocin-social-bonding-neural-circuits, 2026-06-16-vasopressin-avp-social-circuit]
key_sources: ["PMID:35858094", "PMID:19481567", "PMID:23850525", "PMID:15051143", "PMID:17118932"]
---

# 配对键 (Pair Bond)

> **一句话定义**：通过交配/社会互动诱发的催产素（NAc）+ 多巴胺（VTA→NAc）协同激活，在伏隔核建立对特定个体的持久偏好记忆，使该个体成为专属社会奖励目标的神经行为现象；在草原田鼠中，NAc 高密度 OXTR 是此机制的受体基础。

## 当前理解

我们现在认为，配对键不是"感情"的心理描述，而是一个具体的神经回路事件：

在草原田鼠模型中，配对键形成的神经机制包括三个要素：
1. **触发**：交配（或密切社会接触）诱发 PVN 催产素神经元大量放电，在 NAc 中释放催产素
2. **强化**：VTA 多巴胺轴突同时释放多巴胺到 NAc，形成"社会刺激 + 奖励"的时间叠加
3. **印记**：两者协同通过 NAc OXTR 和 D1/D2 受体产生突触可塑性，对特定个体的气味/面容/声音刻下长期偏好记忆

阻断 NAc 的 OXTR 或 DA 受体均阻止配对键形成（即使交配正常发生）——这是双重必要条件证据。

**物种差异揭示的设计原则**：
- 草原田鼠（单配性）：NAc 高密度 OXTR → OT 在 NAc 中有强信号 → 配对键形成
- 草甸田鼠（杂交性）：NAc 低密度 OXTR → OT 在 NAc 中无强信号 → 不形成配对键
- 将草甸田鼠 NAc OXTR 通过病毒转染提升 → 出现配对样行为
- 这证明 NAc OXTR 分布是行为策略的充分条件，而非仅仅相关

**经验依赖的回路修订（2022 年新发现）**：
配对键形成后，雌性草原田鼠 NAc 出现从头建立的 OT-eCB 耦合：OXTR→Ca²⁺→2-AG→CB1R 链路在配对前不存在，配对后才建立（Borie 2022）。这意味着：
- 配对不只是"权重调整"，还建立了新的模块间信号协议
- 已配对个体的 NAc 对 OT 的响应方式与未配对时质变
- 性别使用不同的从头机制（雌性：CB1 依赖；雄性：GABA-A 依赖），但产生相似行为结果

## 关键机制

**双轨信号模型**：
- OT（NAc 释放）：提供"社会焦点"——将注意定向至特定伴侣的感觉特征
- DA（VTA→NAc）：提供"动机驱动"——赋予该伴侣奖励价值，激发接近/维持接触

**行为表现**（草原田鼠配对偏好测试）：
- 配对田鼠在旷场实验中持续接近伴侣（而非陌生者）
- 对陌生者出现选择性攻击
- 偏好强度与 NAc 电生理 TGOT 增强强度显著相关

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 草原田鼠 NAc OXTR 密度决定配对键 | 自放射成像+受体 KO/回补 | Ross & Young 2009, PMID:19481567 | 高 |
| NAc DA 阻断阻止配对键（即使交配正常） | D1/D2 拮抗剂+配对偏好测试 | 文献综合（Love 2013, PMID:23850525） | 高 |
| 配对后 NAc 从头 OT-eCB 耦合 | 体外电生理+CB1 药理+行为相关 | Borie 2022, PMID:35858094 | 中 |

## 连接

- [[oxytocin-system]] — OT 是雌性配对键形成的必要触发信号（NAc OT 释放）
- [[vasopressin-system]] — AVP 是雄性配对键的关键机制：VP V1aR 密度决定雄性配对偏好强度；*avpr1a* 微卫星是物种间配对策略差异的遗传基础；配对后 AVP 还驱动伴侣保护攻击（侧下丘脑 V1aR）
- [[dopamine-system]] — DA 是配对键强化的必要信号（VTA→NAc DA 涌现）
- [[endocannabinoid-system]] — 配对后从头建立的 OT-eCB-CB1R 耦合
- [[social-reward]] — 配对键是社会奖励通路高度特异化的结果

## 未解问题

- Q-OT-03：人类配对键是否有与草原田鼠同构的 NAc OT-DA 机制？（目前只有间接影像证据）

## 修订历史

- 2026-06-16 · 创建 · 基于《社会大脑的肽类密码》(#194) · 初始置信度：高
- 2026-06-16 · rev2 · 基于《加压素系统》(#195)：补充 AVP/V1aR 在腹侧苍白球的雄性配对机制；*avpr1a* 微卫星作为遗传基础；伴侣保护攻击 AVP 机制；更新 related/prerequisites/key_sources

## 来源文章

- [[2026-06-16-oxytocin-social-bonding-neural-circuits]]

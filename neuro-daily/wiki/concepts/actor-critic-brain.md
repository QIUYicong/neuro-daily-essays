---
title: 演员-评论家架构（大脑）
slug: actor-critic-brain
domain: concepts
type: mechanism
status: mainstream
confidence: medium
created: 2026-07-12
updated: 2026-07-12
revision_count: 1
dimensions: [brain-region, microcircuit, whole-brain-network, behavior, cognition]
related: [dopamine-reward-prediction-error, td-learning, basal-ganglia, model-based-model-free, three-factor-learning-rule]
prerequisites: [dopamine-reward-prediction-error, td-learning, basal-ganglia]
opens_questions: [Q-actor-critic-prefrontal, Q-actor-critic-parallel-systems]
source_articles: [2026-07-12-dopamine-td-learning-brain-ai]
key_sources: ["PMID:12371510", "PMID:9054347", "PMID:8774460"]
---

# 演员-评论家架构（大脑）(Actor-Critic Architecture in the Brain)

> **一句话定义**：大脑的基底节实现了强化学习中的演员-评论家（Actor-Critic）框架：腹侧纹状体（评论家，Critic）估计状态价值 V(s) 并通过多巴胺 TD 误差指导学习，背侧纹状体（演员，Actor）通过 D1/D2 受体的差异调制执行"选择/抑制"的行动策略——两者共同实现了从多巴胺教学信号到适应性行为的闭环回路。

## 当前理解

我们现在认为，基底节-多巴胺系统是大脑中最接近计算强化学习中演员-评论家架构的实现。这一框架由 Joel、Niv 和 Ruppin（2002, PMID:12371510）明确提出，并得到后续电生理、光遗传和影像学研究的广泛支持。

**架构对应**：

| 计算角色 | 大脑结构 | 关键神经递质/受体 |
|---------|---------|----------------|
| TD 误差信号 δ | VTA / SNc 多巴胺神经元 | 多巴胺（DA）|
| 评论家（Critic）价值估计 V(s) | 腹侧纹状体（伏隔核 NAc）| D1 / D2 受体 |
| 演员（Actor）直接通路 Go | 背侧纹状体 D1-MSN | D1 受体→ 直接通路 → 丘脑激活 |
| 演员（Actor）间接通路 No-Go | 背侧纹状体 D2-MSN | D2 受体→ 间接通路 → 丘脑抑制 |

**多巴胺的双读数设计**：
- δ > 0（DA 爆发）：激活 D1（高阈值 Go 通路），同时抑制 D2（超高浓度 DA 激活 D2 的抑制性 Gi）→ 双重推进当前行动
- δ < 0（DA 抑制）：D2（高亲和力，对低浓度 DA 更敏感）转为主导，抑制通路激活 → 抑制当前行动

这一架构实现了"做 vs 不做"的动态平衡，是大脑选择行动的核心回路之一。

## 关键机制

### 评论家（Critic）的价值估计

腹侧纹状体（尤其是伏隔核 NAc）接收来自前额叶皮层（状态信息）和 VTA（DA 误差信号）的双重输入：
- 状态-价值学习：NAc 突触权重被 DA 信号塑造，使其能够根据当前状态预测未来期望奖励
- 评论家的"预测"通过 NAc → VP（腹侧苍白球）→ VTA 的反馈回路影响 DA 神经元的基线活动

### 演员（Actor）的策略执行

背侧纹状体（尾状核、壳核）中的中等棘状神经元（MSN）分为两类：
- **D1-MSN**（直接通路）：D1 受体激活 → 纹状体 → 苍白球内侧 / 黑质网状部的抑制减少 → 丘脑 / 皮层激活（"Go"信号）
- **D2-MSN**（间接通路）：D2 受体激活 → 纹状体 → 苍白球外侧 / 丘脑底核的激活 → 丘脑 / 皮层抑制（"No-Go"信号）

三因素学习规则在此执行：pre（皮层输入）× post（MSN 放电）× DA（δ 误差）= 突触权重更新，实现行动-奖励关联的强化。

### 腹侧 vs 背侧纹状体的功能分工

- **腹侧纹状体（评论家）**：与奖励预测、奖励价值评估、情绪动机相关；接收边缘系统（杏仁核、海马）输入
- **背侧纹状体（演员）**：与具体行动序列、习惯形成、运动技能相关；接收运动皮层和感觉皮层输入
- 两者有梯度重叠，并非完全分离

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 伏隔核（NAc）响应奖励预测误差（价值学习）| 人类 fMRI + 啮齿类单元记录 | 多篇综述 | 高 |
| D1-MSN 光遗传激活→行为强化；D2-MSN 激活→抑制 | 小鼠背侧纹状体细胞类型特异性光遗传 | PMID:21499125 | 高 |
| 背侧纹状体损伤→习惯性行为受损，不影响目标导向 | 背外侧纹状体损毁 + 结果贬值测试 | 多项啮齿类研究 | 中-高 |

## 连接

- [[dopamine-reward-prediction-error]] — DA 神经元提供 Actor-Critic 的 TD 误差信号；核心上游
- [[td-learning]] — Actor-Critic 是 TD 学习的一种实现形式
- [[basal-ganglia]] — 基底节是 Actor-Critic 的解剖底物；包含完整的 Go/No-Go 回路
- [[model-based-model-free]] — 背外侧纹状体（Actor，无模型）vs 背内侧纹状体（目标导向，基于模型）的分工
- [[three-factor-learning-rule]] — Actor-Critic 通过三因素规则（pre × post × DA）在突触层面执行策略更新
- [[parkinsons-disease]] — SNc DA 神经元死亡 → Actor-Critic 中 δ 信号缺失 → Go/No-Go 失衡 → 运动障碍

## 未解问题

- Q-actor-critic-prefrontal：前额叶皮层在 Actor-Critic 架构中扮演什么角色？是否实现某种"元评论家"（meta-critic），调节基底节评论家的学习率或注意力分配？
- Q-actor-critic-parallel-systems：背外侧纹状体（习惯/无模型）和背内侧纹状体（目标导向/基于模型）是两个并行的 Actor，还是同一个 Actor 的两种模式？它们的竞争机制是什么？

## 修订历史

- 2026-07-12 · 创建 · 基于《奖励信号的双重发现》第 80 篇文章 · 建立演员-评论家架构页，详述基底节实现、D1/D2 双读数机制和腹侧/背侧纹状体分工 · 初始置信度：中（框架广为接受，但具体神经元层面的 Critic/Actor 对应仍在深化中）

## 来源文章

- [[2026-07-12-dopamine-td-learning-brain-ai]]

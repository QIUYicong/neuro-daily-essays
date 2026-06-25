---
title: 习惯行为
slug: habitual-behavior
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-26
updated: 2026-09-26
revision_count: 1
dimensions: [microcircuit, brain-region, behavior, cognition]
related: [goal-directed-behavior, basal-ganglia, dopamine-reward-prediction-error, striatal-direct-indirect-pathway, medium-spiny-neuron, prefrontal-cortex, td-learning]
prerequisites: [basal-ganglia, dopamine-reward-prediction-error]
opens_questions: [Q-habit-01, Q-habit-02]
source_articles: [2026-09-26-habit-goal-directed-dorsal-striatum]
key_sources: ["PMID:14750976", "PMID:15772337", "PMID:19776734", "PMID:14643469"]
---

# 习惯行为 (Habitual Behavior)

> **一句话定义**：由刺激-反应（S-R）联结驱动、对行为后果的当前价值不敏感的自动行为，神经基底为背外侧纹状体（DLS）和下边缘皮层（IL）；随训练重复而强化，通过 IL 压制目标导向系统来主导控制权。

## 当前理解

我们现在认为，习惯行为不是目标导向行为的"简化版"，而是由完全不同的神经回路实现、从学习第一天起就并行运行的独立系统。习惯行为的核心特征是**刺激-反应解绑**：动作触发不再通过"评估后果价值"的步骤，而是由情境线索（S）直接触发反应（R）——这使习惯在行为后果价值改变后依然被惯性维持（经典测试：结果贬值无法降低习惯化行为）。

习惯的形成需要两个关键条件：①**背外侧纹状体（DLS）**的激活依赖学习（DLS 损毁后即使过度训练也无法形成习惯，Yin et al. 2004）；②**黑质-纹状体多巴胺通路**的完整性（6-OHDA 耗竭后习惯化消失，Faure et al. 2005）。

从计算视角，习惯行为对应**无模型（model-free）强化学习**：维护状态-动作对的"缓存值"（Q 值），通过时间差预测误差（TD 误差）更新，无需维护世界因果模型。

一个关键的反直觉发现：习惯化并不是消除目标导向能力，而是由**下边缘皮层（IL）主动抑制**目标导向系统——暂时性抑制 IL，可立即在习惯化大鼠中恢复对结果贬值的敏感性（Coutureau & Killcross 2003）。

## 关键机制

### 1. 背外侧纹状体（DLS）：S-R 联结的存储地点

DLS 接受来自初级运动皮层和感觉运动皮层的大量输入，以及来自黑质致密部（SNc）的多巴胺信号。随着训练重复，DLS 的中型多棘神经元（D1-MSN 和 D2-MSN）通过 DA 依赖性可塑性，将情境线索（S）与特定运动模式（R）之间的联结逐渐强化。一旦 S-R 联结超过阈值，情境出现即触发行为，无需前额叶参与对结果价值的评估。

### 2. 下边缘皮层（IL）的主动抑制角色

IL 通过投射到纹状体（尤其是腹侧纹状体），主动抑制前边缘皮层-DMS 系统的目标导向控制。这种抑制机制使习惯行为得以主导：目标导向能力并未消失，只是被 IL 压制。当 IL 受损或被暂时沉默时，目标导向系统解除压制，重新获得控制权。

### 3. 多巴胺在习惯形成中的时序迁移

随着训练重复，多巴胺神经元的脉冲放电逐渐从"奖励本身出现时"迁移到"奖励预测线索出现时"（经典的 Schultz RPE 时序迁移）。这种时序迁移在 DLS 层面"固化"了刺激-反应联结：线索出现时的 DA 释放强化了 S→R 突触，使后续动作对结果价值的追踪越来越弱。

### 4. 计算对应：Model-Free 强化学习

习惯行为的计算等价是 model-free RL：
- 维护 Q(s, a) = 在状态 s 下执行动作 a 的期望回报
- 更新规则：Q(s,a) ← Q(s,a) + α·δ，其中 δ = r + γ·max Q(s',a') - Q(s,a)
- 不需要"理解"因果关系，只需要记录"过去做了 A 之后获得了 R"
- 对环境变化（如结果贬值）的响应必须通过新的经验来更新——而不是即时推断

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| DLS 对习惯形成必要 | DLS 双侧损毁→过度训练后仍对结果贬值敏感（无习惯化） | Yin et al. 2004, PMID:14750976 | 高 |
| 黑质-纹状体 DA 对习惯形成必要 | 6-OHDA 耗竭→过度训练后无习惯化 | Faure et al. 2005, PMID:15772337, PMC:6725127 | 高 |
| IL 主动压制目标导向系统 | Muscimol 抑制 IL→习惯化大鼠恢复结果贬值敏感性 | Coutureau & Killcross 2003, PMID:14643469 | 高（大鼠） |
| 人类壳核后部随习惯化训练激活增强 | 第三天过度训练后 fMRI 壳核后外侧激活上升 | Tricomi et al. 2009，综述引用自 PMID:19776734 | 中（单一 fMRI 研究） |
| 习惯化行为不受结果贬值影响 | 广泛使用的行为学测试，跨物种（大鼠、小鼠、人类） | Adams & Dickinson 1981，Balleine & O'Doherty 2010, PMID:19776734 | 高 |

## 连接

- [[goal-directed-behavior]] — 互补的竞争系统：习惯与目标导向从学习开始并行运行，竞争行为控制权
- [[basal-ganglia]] — DLS 是习惯行为的解剖基底（背外侧纹状体即壳核后部）
- [[dopamine-reward-prediction-error]] — 多巴胺对习惯形成必要；时序迁移（奖励→线索）是习惯固化的关键
- [[striatal-direct-indirect-pathway]] — 直接/间接通路在习惯执行中协调作用
- [[medium-spiny-neuron]] — DLS 的主要细胞类型，S-R 联结的存储单元
- [[prefrontal-cortex]] — IL（下边缘皮层）主动抑制目标导向系统，支持习惯控制
- [[td-learning]] — 习惯行为的计算等价为 model-free 强化学习（TD 算法）

## 未解问题

- Q-habit-01：认知层面的习惯（如自动化的偏见、刻板思维模式）是否共享与运动习惯相同的 DLS/IL 神经机制？
- Q-habit-02：在高认知负荷、睡眠剥夺、焦虑等状态下，什么机制使习惯系统更容易主导行为？多巴胺基线变化、IL 兴奋性升高，还是 DMS 可用资源降低？

## 修订历史

- 2026-09-26 · 创建 · 基于《自动驾驶的大脑：纹状体双系统如何在习惯与目标之间争夺行为控制权》（文章 #156）· 整合 Balleine 实验室经典损毁实验和计算框架 · 初始置信度：高

## 来源文章

- [[2026-09-26-habit-goal-directed-dorsal-striatum]]

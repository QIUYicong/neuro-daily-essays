---
title: 心智理论
slug: theory-of-mind
domain: concepts
type: concept
status: established
confidence: high
created: 2026-07-25
updated: 2026-07-25
revision_count: 1
dimensions: [cognition, behavior, brain-region, whole-brain-network]
related: [mentalizing-network, tpj-temporoparietal-junction, mirror-neurons, predictive-coding, default-mode-network, autism-spectrum, prefrontal-cortex, empathy, anterior-insula]
prerequisites: [prefrontal-cortex, action-potential, synaptic-transmission]
opens_questions: [Q-tom-01, Q-tom-02, Q-tom-03]
source_articles: [2026-07-25-social-brain-mirror-neurons-theory-of-mind, 2026-07-26-empathy-anterior-insula-acc]
key_sources: ["PMID:12948738", "PMID:17714666", "PMID:16513098", "PMID:34241539"]
updated: 2026-07-26
revision_count: 2
---

# 心智理论 (Theory of Mind, ToM)

> **一句话定义**：心智理论是将他人（和自己）理解为拥有独立信念、欲望、意图、知识的"心理行为体"的能力——核心能力是理解他人的心理状态可以与现实和自身状态不同。

## 当前理解

我们现在认为，心智理论（ToM）是人类认知中最独特的能力之一，也是合作、道德判断、语言沟通和文化传承的神经基础。与其他灵长类相比，人类在约4岁时就能可靠地通过"错误信念测试"（false belief test）——理解他人可能持有与现实不符的心理表征。

ToM不是单一的计算能力，而是一个**多层级的推断系统**：
- **一阶ToM**："她相信X"
- **二阶ToM**："他认为她相信X"
- **更高阶**：复杂叙事理解（欺骗、反讽、社交博弈）

**核心神经基底**（Frith & Frith 2007, PMID:17714666）：
1. **颞顶联合区（TPJ）**：专门响应他人心理内容（信念、意图、欲望）的推断；右侧TPJ-M尤为关键（Saxe & Kanwisher 2003, PMID:12948738）
2. **内侧前额叶皮层（mPFC）**：高阶自我/他人表征；去中心化（decentering）时激活
3. **颞上沟（STS）**：生物运动感知和联合注意的感觉入口
4. **颞极（TP）**：情景记忆整合，支持对他人历史状态的建模

**与镜像神经元的关系**：ToM不能简化为镜像神经元激活。Heyes & Catmur（2022，PMC8785302）确认，镜像神经元系统提供低层动作区分，而ToM需要高层信念-欲望-意图建模，两者是不同层级的计算。

## 关键机制

### 错误信念理解
标准任务（Wimmer & Perner 1983）：
```
Maxi把巧克力放在位置A后离开 → 妈妈把巧克力移到位置B
→ 被试问：Maxi回来后会去哪里找巧克力？
```
4岁儿童能回答"位置A"（Maxi的错误信念）；3岁通常回答"位置B"（自己的正确知识）。
通过这个测试需要**元表征**（metarepresentation）：同时维护"现实状态"与"他人的心理表征"。

### 预测编码框架下的ToM
ToM本质上是一个**贝叶斯推断过程**：
- **先验**：基于对他人的人格特征、历史行为、情境规律构建的预期模型
- **预测**：从先验生成对他人下一动作/情绪的预测
- **预测误差**：实际行为与预测的差距（违背ToM预测时激活TPJ/mPFC）
- **更新**：用预测误差调整对他人的内部模型

这意味着ToM不是在行为发生**后**被动推断，而是**前瞻性的**——大脑持续预测他人的行为，并在预测失败时更新模型。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 右侧TPJ专门响应他人心理状态推断（非物理场景/非人类刺激） | fMRI，故事阅读范式，多控制条件 | PMID:12948738（Saxe & Kanwisher 2003） | 高（多实验室重复） |
| TMS抑制右侧TPJ损害信念-道德判断（但不损害结果-道德判断） | TMS + 道德判断任务；双重解离 | 后续TMS研究综述（Frith 2007） | 中-高（因果性证据，部分实验室未重复） |
| mPFC活动与需要区分自身/他人视角的任务相关（去中心化要求↑） | fMRI元分析（多项研究） | PMID:17714666综述综合 | 中-高 |
| 镜像神经元区域（BA44）损伤不导致ToM缺陷 | 人类病变研究 | PMID:19199415（Hickok 2009综述） | 中（基于有限病变数据） |
| ASD中ToM延迟/困难，但不能归因于镜像神经元损伤 | 行为测试 + fMRI + PMC8785302（Heyes & Catmur 2022） | PMID:34241539 | 中（ASD异质性大） |

## 连接

- [[mentalizing-network]] — ToM的神经网络底层（TPJ + mPFC + STS的功能回路）
- [[tpj-temporoparietal-junction]] — ToM中心节点，专用于心理内容推断
- [[mirror-neurons]] — 提供动作层面的共享表征，但不足以支撑高阶ToM
- [[predictive-coding]] — ToM是预测编码在社会领域的扩展：大脑持续预测他人的信念/意图
- [[default-mode-network]] — mPFC是DMN核心节点，休息时大脑默认进行社会心智模拟
- [[prefrontal-cortex]] — 去中心化、高阶表征维护的皮层基础
- [[empathy]] — 情感共情（AIC/ACC 主导）是 ToM（认知共情）的互补成分；两者可双解离
- [[anterior-insula]] — ToM 的认知推断（本页）之外，AIC 负责自动情感共情——两条不同的"理解他人"路径

## 未解问题

- Q-tom-01（高优先级）：TPJ在ToM中的具体计算角色——是注意重定向（信念处理占用注意资源）、信念归因（直接编码信念内容），还是预测误差信号？目前三种解释各有支持。
- Q-tom-02（高优先级）：mPFC如何区分"我的信念"与"他的信念"的神经表征——去中心化的具体实现机制？是时间分离的顺序表征还是空间分离的子区域？
- Q-tom-03（中优先级）：LLM（如GPT-4）在标准ToM任务上已超过多数4岁儿童——但缺乏情感共情基础的"语言ToM"是否是真正的心智理论，还是对ToM语言模式的统计学习？

## 修订历史

- 2026-07-25 · 创建 · 基于《大脑如何读懂另一颗大脑》（#93）· 初始置信度：高（ToM的行为/发育证据坚实；神经机制仍有争议，故神经部分置信度中-高）
- 2026-07-26 · 修订 · 基于《感同身受的神经密码》（#94）· 新增 empathy 和 anterior-insula 的相关连接，明确认知共情（ToM/本页）与情感共情（AIC/empathy 页面）的双解离关系

## 来源文章

- [[2026-07-25-social-brain-mirror-neurons-theory-of-mind]]
- [[2026-07-26-empathy-anterior-insula-acc]]

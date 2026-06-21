---
title: 价值决策（Value-Based Decision Making）
slug: value-based-decision-making
domain: concepts
type: concept
status: established
confidence: high
created: 2026-08-21
updated: 2026-08-21
revision_count: 1
dimensions: [brain-region, cognition, behavior]
related: [orbitofrontal-cortex, prefrontal-cortex, amygdala, basal-ganglia, nucleus-accumbens, dopamine-reward-prediction-error, anterior-cingulate-cortex]
prerequisites: [synaptic-transmission, ltp, dopamine-reward-prediction-error]
opens_questions: [Q-ofc-02, Q-ofc-03]
source_articles: [2026-08-21-orbitofrontal-cortex-value-decision-circuit]
key_sources: ["PMID:16633341", "PMID:29144973", "PMID:37592039", "DOI:10.7554/eLife.80926", "PMID:19407204"]
---

# 价值决策（Value-Based Decision Making）

> **一句话定义**：大脑在面临多个选项时，通过神经计算将各选项的主观效用（utility）显式表征并加以比较，最终选择效用最高选项的整个神经行为过程；其核心是眶额皮层（OFC）维护的主观价值地图，BLA 提供价值记忆，纹状体将价值信号转化为动作。

## 当前理解

价值决策是认知神经科学中研究最深入的功能之一。我们现在认为，大脑实现价值决策依赖一套层级化的神经回路：

1. **价值表征**（OFC）：在选项比较阶段，OFC 的"提案价值细胞"并行编码各候选选项的当前主观效用，"选定价值细胞"在选择完成后编码胜出选项的价值。

2. **价值记忆**（BLA↔OFC）：历史奖赏经验通过 BLA-OFC 双向回路存储为结果特异性记忆，并在决策时按当前情境（饱足、危险、情绪状态）检索，生成动态调整的主观价值。

3. **行动转换**（OFC→DMS）：OFC 将价值信号通过腹外侧亚区投射至背内侧纹状体（DMS），转化为目标导向行动选择指令。

4. **认知调制**（dlPFC→vmPFC）：背外侧前额叶在自控情境下调制 vmPFC 的价值整合，将长期目标和当前价值共同纳入计算。

价值决策与**习惯行为**（habit）形成对比：习惯行为依赖外侧纹状体，不随结果贬值而改变；价值决策依赖 OFC-BLA 系统，对结果当前价值敏感（去除奖赏后行为随之停止）。

## 关键机制

**价值读写循环**：
- 新奖赏经历：感觉信号→BLA（外侧核 LA 更新 CS-US 联系）→lOFC→BLA（写入结果特异性记忆）
- 决策时刻：环境线索→OFC（激活状态表征）→mOFC→BLA（检索匹配记忆）→OFC 提案价值细胞激活→比较→选定价值细胞读出→OFC→DMS→行动

**价值的三个维度**：
- **当前主观效用**：受饱足状态、情绪、习惯化影响
- **不确定性**（风险偏好）：lOFC 处理风险/惩罚成分；mOFC→PL 抑制过度风险诱惑
- **时间折扣**：vmPFC/OFC 系统受 dlPFC 调制，允许长期收益覆盖即时冲动

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| OFC 神经元显式编码主观价值（独立于感觉/运动） | 猴子电生理 | PMID:16633341 | 高 |
| OFC-BLA 回路是结果特异性价值记忆的神经基础 | 大鼠/小鼠，通路拆解实验 | DOI:10.7554/eLife.80926 | 中-高 |
| OFC→DMS 通路对经济决策因果必要 | 大鼠，光遗传学 | PMID:37592039 | 高 |
| vmPFC 整合多维价值；dlPFC 在自控时调制 | 人类 fMRI | PMID:19407204 | 中 |
| 目标导向行为（价值决策）vs 习惯行为（刺激-反应）的双系统分离 | 大鼠，结果贬值范式 | 综述 DOI:10.7554/eLife.80926 | 高 |

## 连接

- [[orbitofrontal-cortex]] — 价值地图的核心计算节点
- [[amygdala]] — BLA 是价值记忆存储与更新的关键节点
- [[basal-ganglia]] — 目标导向行为（DMS）vs 习惯行为（外侧纹状体）的分离系统
- [[nucleus-accumbens]] — Wanting（动机激励显著性）与价值决策的互补系统
- [[dopamine-reward-prediction-error]] — DA 提供的 RPE 信号驱动 OFC-BLA 价值学习
- [[prefrontal-cortex]] — dlPFC 调制 vmPFC/OFC 的价值权重（自控机制）

## 未解问题

- **Q-ofc-02**：OFC 是决策的生成者还是报告者？
- **Q-ofc-03**：社会价值（信任、利他）是否共用同一套 OFC 价值代码？

## 修订历史

- 2026-08-21 · 创建 · 基于《价值的解剖：眶额皮层如何为选项定价》（#119）· 初始置信度：高

## 来源文章

- [[2026-08-21-orbitofrontal-cortex-value-decision-circuit]]

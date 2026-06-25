---
title: 资格痕迹
slug: eligibility-trace
domain: concepts
type: mechanism
status: emerging
confidence: medium
created: 2026-09-29
updated: 2026-09-29
revision_count: 1
dimensions: [synaptic, cellular, molecular, behavior, cognition]
related: [synaptic-tagging-capture, three-factor-learning-rule, dopamine-reward-prediction-error, ltp, hebbian-learning, corticostriatal-stdp, striatal-plasticity, camkii]
prerequisites: [ltp, hebbian-learning, dopamine-reward-prediction-error, nmda-receptor]
opens_questions: [Q-eligibility-trace-striatum, Q-eligibility-trace-duration, Q-eligibility-trace-vs-stc]
source_articles: [2026-09-29-eligibility-trace-temporal-credit-assignment]
key_sources: ["PMID:36226826", "PMID:9020359", "PMID:20962282", "PMID:18687967"]
---

# 资格痕迹 (Eligibility Trace)

> **一句话定义**：突触前-突触后配对（Hebbian事件）在NMDA受体激活后，通过AC1/AC8（钙/钙调蛋白激活的腺苷酸环化酶）留下一个时间有限（~分钟级）的"资格痕迹"——突触处于"等待DA许可"的敏感状态，若多巴胺奖励信号在痕迹消退前到达，则cAMP骤升并触发LTP，将此前的Hebbian事件"追溯性地"强化。

## 当前理解

我们现在认为，资格痕迹是三因素学习规则（Δw ∝ pre × post × DA）解决时序信用分配问题的核心分子机制之一。其关键功能是：在Hebbian激活（毫秒级）与DA奖励信号（秒至分钟后）之间架设时间桥梁，使突触能够"记住"自己最近被激活，等待全局评估信号。

**基本逻辑**：

```
Hebbian配对（Δt=±20ms）
    → NMDA-R激活 → Ca²⁺内流
    → AC1/AC8进入"敏感态"（痕迹建立，~分钟级）
    → cAMP不立即升高（痕迹"沉默"）

             ↓（若在痕迹窗内）

DA爆发（奖励信号）+ 突触后爆发放电
    → DA→Gs→β-γ亚基 + Ca²⁺残留 → AC1/AC8共激活
    → cAMP骤升 → PKA → GluA1磷酸化/AMPAR插入 → LTP

             ↓（若无DA或DA延迟过长）

痕迹自然消退，突触不被长期增强
```

**直接实验证据**（Fuchsberger et al. 2022, PMID:36226826）：
- 小鼠CA1 post-before-pre配对（Δt=-20ms）→ 突触强度降至 61±11%（LTD）
- 10分钟后给予DA（1μM）+ 突触后爆发放电 → 突触强度升至 135±14.9%（p=0.044，LTD逆转为LTP）
- AC1/AC8双基因敲除小鼠：效应消失（证明AC1/AC8是资格痕迹的分子底物）
- NMDA拮抗剂（配对后施用）：不影响随后的DA+爆发诱导LTP（证明痕迹已在AC1/AC8处独立存储）

## 关键机制

### 分子底物（AC1/AC8核心）

AC1（腺苷酸环化酶1型）和AC8（腺苷酸环化酶8型）是Ca²⁺/钙调蛋白和Gs蛋白（DA-D1/D5→Gs）的**双重共激活**才高效产生cAMP。它们是"AND门"：

- **Ca²⁺单独**（NMDA激活）→ cAMP少量升高（不足以触发L-LTP）
- **DA（Gs）单独** → 中等cAMP升高（在多数突触不足以触发L-LTP）
- **Ca²⁺ + DA共激活** → cAMP大幅骤升（超线性，触发PKA→L-LTP）

资格痕迹的"沉默性"在于：Hebbian激活后，AC1/AC8虽进入敏感状态，但Ca²⁺残留量随时间衰减——在DA到来之前，cAMP维持低水平（痕迹"沉默"）。只有当DA在Ca²⁺残留仍足以协同激活AC1/AC8的时间窗内到来，才能激发强烈的cAMP反应。

### 资格痕迹 vs 突触标记（STC）

两者是解决时序信用分配的**两级机制**：

| 特征 | 资格痕迹 | 突触标记（STC） |
|------|---------|--------------|
| 时间尺度 | 毫秒→分钟（~10min证明） | 分钟→小时（~1-2h）|
| 分子底物 | AC1/AC8敏感状态（直接证明） | 未知（CaMKII？肌动蛋白？）|
| "捕获"信号 | DA + Ca²⁺共激活 → cAMP→PKA | PRPs（PKMζ, Arc, BDNF等）|
| 脑区证据 | CA1（直接）；纹状体（推论）| CA1, 杏仁核, CA2, ACC |
| 实验证明水平 | 高（Fuchsberger 2022） | 高（Frey & Morris 1997）|

两者在时间上**互补**：资格痕迹处理毫秒→分钟的延迟，STC处理分钟→小时的延迟，共同覆盖了生物体学习所需的时序信用分配范围。

### 体内验证

Fuchsberger et al.（2022）通过自由运动小鼠空间奖励任务（体内实验）发现：预激活的CA1细胞在学习过程中比非预激活细胞显示更高活动峰值（AUC：0.54 vs 0.42），提示资格痕迹在体内学习中功能性存在。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| AC1/AC8介导资格痕迹：STDP配对后10min，DA+爆发→LTD逆转为LTP（61±11%→135±14.9%）；AC1/AC8敲除消除效应 | 离体CA1膜片钳 + AC1/AC8双基因敲除小鼠 | PMID:36226826 (PMC9612916) | 高（直接证明）|
| 痕迹存在时NMDA-R已关闭（AC1/AC8独立存储痕迹）| 配对后施加NMDA拮抗剂仍不影响后续DA+爆发诱导LTP | PMID:36226826 (PMC9612916) | 高 |
| 资格痕迹的体内功能验证：预激活CA1细胞在学习中更活跃 | 自由运动小鼠空间奖励任务 + 光纤记录 | PMID:36226826 (PMC9612916) | 中（间接，相关性）|

## 连接

- [[synaptic-tagging-capture]] — STC是资格痕迹在更长时间尺度（小时）的类似机制；两者共同构成时序信用分配的多级体系
- [[three-factor-learning-rule]] — 资格痕迹是三因素规则（Δw ∝ pre × post × DA）在毫秒→分钟时间尺度的分子实现
- [[dopamine-reward-prediction-error]] — DA爆发是"捕获"资格痕迹的触发信号；D1/D5→Gs→β-γ与Ca²⁺共激活AC1/AC8
- [[corticostriatal-stdp]] — 资格痕迹解决了皮层-纹状体STDP中体外时序窗口（±20ms）与体内DA延迟（毫秒→分钟）的不匹配问题
- [[striatal-plasticity]] — 纹状体AC1/AC8机制（推论）是D1-MSN时序信用分配的分钟级解法
- [[camkii]] — CaMKII是资格痕迹候选分子之一（NMDA→CaMKII激活→特定磷酸化状态）；AC1/AC8与CaMKII的关系待厘清
- [[ltp]] — 资格痕迹最终导向LTP（通过PKA→GluA1磷酸化/AMPAR插入）；是E-LTP的触发条件之一
- [[hebbian-learning]] — Hebbian激活是设置资格痕迹的必要条件

## 未解问题

- Q-eligibility-trace-striatum：资格痕迹（AC1/AC8介导）是否在纹状体皮层-MSN突触中同样存在？纹状体AC5/AC6（主要亚型）是否有类似的Ca²⁺/DA共激活特性？
- Q-eligibility-trace-duration：资格痕迹的有效期确切是多长？10分钟已证明；上限（15min？30min？）未测定。与突触类型、突触后细胞类型、背景网络活动的关系？
- Q-eligibility-trace-vs-stc：资格痕迹（分钟级）与突触标记/捕获（小时级）是否在同一突触上串联工作？若资格痕迹→短期LTP被建立，STC标签是否同时设置？

## 修订历史

- 2026-09-29 · 创建 rev1 · 基于《时序信用分配》(#159) · 核心来源：Fuchsberger et al. 2022（直接证明，PMC9612916）· 概念页面从STC页面中独立出来，捕获毫秒→分钟时间尺度机制

## 来源文章

- [[2026-09-29-eligibility-trace-temporal-credit-assignment]]

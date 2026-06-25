---
title: 外侧缰核
slug: lateral-habenula
domain: systems
type: region
status: established
confidence: high
created: 2026-09-19
updated: 2026-09-19
revision_count: 1
dimensions: [molecular, cellular, microcircuit, brain-region, behavior, cognition, disease]
related: [dopamine-reward-prediction-error, basal-ganglia, nucleus-accumbens, serotonin-raphe-system, vmPFC, amygdala, prefrontal-cortex, lhb-rmtg-circuit, depression, thalamus]
prerequisites: [dopamine-reward-prediction-error, synaptic-transmission, basal-ganglia]
opens_questions: [Q-lhb-01, Q-lhb-02, Q-lhb-03]
source_articles: [2026-09-19-lateral-habenula-anti-reward-depression]
key_sources: ["PMID:17522629", "PMID:21832176", "PMID:31152135", "PMID:41925551", "PMID:41872515", "PMID:38863324", "PMID:42057617", "PMID:40769282", "PMID:33535028", "PMID:37414924"]
---

# 外侧缰核 (Lateral Habenula, LHb)

> **一句话定义**：间脑上丘脑中的小核团，大脑奖励系统的镜像计算器：在预期奖励未出现时爆发激活，通过喙侧内侧被盖核（RMTg）主动抑制 VTA 多巴胺神经元，同时直接抑制背侧中缝核血清素，编码负预测误差（nRPE）；在抑郁症中陷入病理性同步爆发放电。

## 当前理解

我们现在认为，外侧缰核（LHb）是大脑**主动惩罚信号计算器**，与 VTA 多巴胺系统形成严格的功能镜像：当 VTA 多巴胺爆发编码正预测误差时，LHb 爆发编码负预测误差（Matsumoto & Hikosaka 2007, PMID:17522629），且 LHb 的激活**先于**多巴胺抑制约 20-40 ms，说明因果关系明确——LHb 主动驱动了多巴胺的沉默，而非被动跟随。

LHb 的核心解剖回路：谷氨酸能 LHb 神经元 → 兴奋 GABAergic **喙侧内侧被盖核（RMTg）** → 抑制 VTA 多巴胺神经元（Hong et al. 2011, PMID:21832176, PMC3315151）。同时 LHb 直接向**背侧中缝核（DRN）**发送谷氨酸，调控血清素输出；并投射到蓝斑（LC），调控去甲肾上腺素。

**急性应激会反转 LHb 的奖励编码**：正常情况下，LHb 对奖励刺激呈抑制响应（从而允许 VTA 保持活跃）；急性应激后，同样的奖励刺激引发 LHb 爆发激活，导致快感缺失（Shabel et al. 2019, PMID:31152135, PMC6589650）。

在抑郁症动物模型中，LHb 神经元呈现**病理性同步爆发放电**——方波型、抛物线型或三角波型（Fedorov et al. 2026, PMID:41925551, PMC13082187）——驱动多巴胺和血清素系统持续被抑制。氯胺酮的快速抗抑郁作用（数小时内起效）部分通过阻断这种 LHb 爆发实现（Nakajima et al. 2026, PMID:41872515, PMC13269138）。

**输出回路特异性**（Liu et al. 2024, PMID:38863324, PMC11321664）：
- LHb→DRN 爆发 → 快感缺失 + 焦虑
- LHb→VTA 爆发 → 动力丧失
- LHb→MnR 同时参与 → 绝望感

## 关键机制

### 解剖位置

位于**间脑上丘脑**（epithalamus），丘脑背侧，第三脑室旁，通过缰连合（habenular commissure）与对侧相连。是脊椎动物高度保守的结构（从鱼类到人类均存在）。

### 主要输入

| 输入来源 | 信息内容 |
|---------|---------|
| 苍白球内节/内侧苍白球（GPi/EPN）| 基底节"空奖励"输出；动作抑制信号 |
| 腹内侧前额叶（vmPFC）、ACC | 价值期望未实现；错误监控 |
| 外侧下丘脑（LH）| 饥饿/能量亏缺 |
| 终纹床核（BNST）| 焦虑、威胁预期 |

### 主要输出（功能效果）

| 输出目标 | 效果 |
|---------|------|
| RMTg（GABA→VTA） | 多巴胺抑制 → 负RPE信号 |
| DRN（直接谷氨酸）| 血清素抑制 → 情绪/动机下降 |
| MnR | 情绪稳态 |
| LC（蓝斑）| 去甲肾上腺素调节 |

### 病理性爆发放电（抑郁模型）

慢性应激 → LHb 神经元同步爆发（方波型/抛物线型/三角波型）→ 持续多巴胺+血清素+去甲肾上腺素抑制 → 快感缺失 + 动力丧失 + 绝望感

爆发模式由膜电位超极化程度控制：超过临界分叉点即进入爆发动力学（Fedorov et al. 2026）。

### 氯胺酮机制

氯胺酮（亚麻醉剂量 0.5 mg/kg）→ 阻断 NMDAR → 打断 LHb 爆发的内部振荡动力学 → 数小时内恢复稀疏单峰放电 → 快速解除多巴胺/血清素抑制。NOX-1 抑制（mPFC）可延长此效果（Nakajima et al. 2026）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| LHb 编码负 RPE，响应先于 VTA 多巴胺抑制 20-40 ms | 灵长类奖励任务电生理 + LHb 电刺激 | PMID:17522629 | 高 |
| RMTg 是 LHb→VTA 负 RPE 的必要中继 | 灵长类逆行追踪 + RMTg 损毁 | PMID:21832176 (PMC3315151) | 高 |
| 急性应激将 LHb 奖励响应反转为惩罚信号 | 小鼠应激操控 + 电生理 | PMID:31152135 (PMC6589650) | 中高 |
| LHb 三种爆发模式，超极化诱发方波型 | 大鼠膜片钳 + 数学模型 | PMID:41925551 (PMC13082187) | 高 |
| 氯胺酮通过 LHb 爆发抑制快速起效 | 小鼠 CUMS，NOX-1操控 | PMID:41872515 (PMC13269138) | 中高 |
| LHb 输出特异性（DRN/VTA/MnR）对应不同抑郁症状 | 小鼠光遗传学分离 | PMID:38863324 (PMC11321664) | 高 |

## 连接

- [[dopamine-reward-prediction-error]] — LHb 编码镜像负 RPE，主动驱动多巴胺抑制
- [[lhb-rmtg-circuit]] — LHb→RMTg→VTA 的详细回路页
- [[basal-ganglia]] — GPi/EPN 向 LHb 提供基底节"空奖励"输出
- [[serotonin-raphe-system]] — LHb 直接投射 DRN，调控血清素输出
- [[nucleus-accumbens]] — 下游多巴胺信号目标，受 LHb 间接调控
- [[vmPFC]] — 向 LHb 提供价值期望未实现信号
- [[thalamus]] — 解剖邻近，共属间脑/上丘脑区域

## 未解问题

- Q-lhb-01：LHb 输出特异性（DRN vs VTA vs MnR）与不同抑郁症状的对应是否能在人类患者中验证？（高优先级）
- Q-lhb-02：GPi→LHb 连接中谷氨酸成分的分子身份确认——GPi 经典上是 GABAergic，但 GPi→LHb 的谷氨酸成分如何存在？（中优先级）
- Q-lhb-03：氯胺酮消除 LHb 爆发的精确分子机制——哪个 NMDAR 亚型（NR2A/NR2B），是否涉及星形胶质细胞 NMDAR？（高优先级）

## 修订历史

- 2026-09-19 · 创建 · 基于《外侧缰核：大脑的惩罚计算机》(文章 #149) · 初始置信度：高

## 来源文章

- [[2026-09-19-lateral-habenula-anti-reward-depression]]

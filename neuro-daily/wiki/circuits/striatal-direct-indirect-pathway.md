---
title: 纹状体直接/间接通路
slug: striatal-direct-indirect-pathway
domain: circuits
type: mechanism
status: mainstream
confidence: high
created: 2026-09-01
updated: 2026-09-28
revision_count: 2
dimensions: [synaptic, microcircuit, brain-region, behavior, cognition]
related: [medium-spiny-neuron, basal-ganglia, dopamine-reward-prediction-error, habit-vs-goal-directed, parkinsons-disease, hyperdirect-pathway, corticostriatal-stdp, three-factor-learning-rule, addiction]
prerequisites: [medium-spiny-neuron, basal-ganglia, action-potential, dopamine-reward-prediction-error]
opens_questions: [Q-direct-indirect-not-go-nogo, Q-corticostriatal-stdp-in-vivo-timing]
source_articles: [2026-09-01-medium-spiny-neurons-striatum, 2026-09-28-corticostriatal-stdp-d1d2-plasticity]
key_sources: ["PMID:21469956", "PMID:31171839", "PMID:27373834", "PMID:18687967", "PMID:20613723", "PMID:15528409"]
---

# 纹状体直接/间接通路 (Striatal Direct and Indirect Pathways)

> **一句话定义**：基底节的两条相互拮抗的输出回路——D1型MSN构成的直接通路通过解除对丘脑的抑制促进行动启动，D2型MSN构成的间接通路通过多级抑制增强丘脑抑制从而压制行动。

## 当前理解

我们现在认为，直接/间接通路构成了行动选择的核心竞争机制，但经典的"go/no-go"二分模型已被证明过度简化。现代体内记录和光遗传学研究表明：两条通路在运动执行期间**都被激活**（非单一开/关），它们的功能差异主要体现在行动**价值比较**和**学习历史编码**层面，而非简单的行动开始/停止。

值得注意的是，直接/间接通路不是固定的"行动开关"，而是反映了纹状体中**突触权重历史**的动态表达——哪条通路的MSN曾在奖励发生时被激活，哪条通路就在长期可塑性中得到了更强的加固。

**2026-09-28 新增（第158篇）**：两条通路的"记忆刻写"规则已在分子层面被直接证明。Shen et al.（2008, PMID:18687967，全文PMC2833421）用D1/D2荧光报告小鼠脑切片证实：多巴胺通过不对称STDP门控实现双通路"镜像可塑性"（D1-MSN偏向LTP；D2-MSN偏向LTD）。Kravitz et al.（2010, PMID:20613723）用光遗传学在活体中因果验证了功能分离（D1-MSN激活→Go；D2-MSN激活→僵直）。Frank et al.（2004, PMID:15528409）在帕金森病患者中证实了行为层的双重分离（正/负反馈学习随DA水平反转）。详见 [[corticostriatal-stdp]]。

## 关键机制

### 解剖通路（啮齿类）

**直接通路（Direct Pathway）**：
- 细胞类型：D1受体表达的dMSN（直接通路MSN）
- 投射：纹状体 → GPi（内侧苍白球）/SNr（黑质网状部）
- GPi/SNr是GABA能输出核，持续抑制丘脑运动核
- 效应：dMSN激活 → GPi/SNr受抑 → 丘脑抑制解除 → 丘脑-皮质激活 → **行动启动**

**间接通路（Indirect Pathway）**：
- 细胞类型：D2受体表达的iMSN（间接通路MSN）
- 投射：纹状体 → GPe（外侧苍白球）→ STN（丘脑底核）→ GPi/SNr
- 效应：iMSN激活 → GPe受抑 → STN去抑制 → STN兴奋GPi/SNr → 丘脑抑制增强 → **行动抑制**

### 多巴胺的协同调控

多巴胺通过相反方向同时调控两条通路：
- **D1（直接通路）**：多巴胺↑ → dMSN兴奋↑ + LTP → 直接通路强化 → 促进行动
- **D2（间接通路）**：多巴胺↑ → iMSN兴奋↓ + LTD（eCB机制） → 间接通路减弱 → 进一步促进行动

奖励时的净效应：直接通路加强、间接通路减弱，联合促进该行动被未来重复执行。

### 功能分离（背外侧 vs 背内侧纹状体）

| 纹状体区域 | 主要功能 | 破坏后效应 |
|-----------|---------|-----------|
| DMS（背内侧） | 目标导向学习，行动-结果联结 | 行为快速习惯化，弹性丧失 |
| DLS（背外侧） | 习惯形成，刺激-反应联结 | 无法形成习惯（即便过度训练） |
| NAc（腹侧） | 动机、Pavlovian学习 | 动机减退，奖励预期减弱 |

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| D1激活→丘脑正BOLD；D2激活→丘脑负BOLD | ofMRI（背内侧纹状体）| PMID:27373834 (PMC5528162) | 高 |
| 两条通路在运动期间都被激活（非go/stop对立） | 体内Ca²⁺成像 | PMID:31171839综述 | 中-高 |
| DMS损伤→习惯化；DLS损伤→无法习惯化 | 靶向损伤 + 行为实验 | PMID:31171839 (PMC7231228) | 高 |
| 奖励D1-LTP同时D2-LTD（双向刻写模型） | 电生理 + 分子生物学汇总 | PMID:21469956 (PMC3487690) | 高（理论框架）/ 中（体内直接验证） |
| D1-MSN正时序STDP→LTP；负时序无LTD（D1激活阻断mGluR5-CB1） | D1/D2-EGFP小鼠脑切片+STDP | PMID:18687967 (PMC2833421) | 高 |
| D2-MSN双向STDP：正时序→A2a-LTP；负时序→D2-CB1-LTD | 同上 | PMID:18687967 (PMC2833421) | 高 |
| D1-MSN激活→运动启动（因果）；D2-MSN激活→帕金森样僵直（因果） | 活体小鼠ChR2光遗传学（D1-Cre/D2-Cre） | PMID:20613723 (PMC3552484) | 高 |
| 低DA帕金森病患者：正反馈学习受损；服药后正反馈恢复/负反馈受损 | 帕金森病患者强化学习任务（服药vs停药） | PMID:15528409 | 高 |

## 连接

- [[medium-spiny-neuron]] — 直接/间接通路的细胞基础
- [[basal-ganglia]] — 两条通路是基底节信息流的核心
- [[dopamine-reward-prediction-error]] — 多巴胺RPE信号同时调控两条通路的可塑性
- [[hyperdirect-pathway]] — 第三条通路（STN直接皮质输入），实现快速行动取消
- [[habit-vs-goal-directed]] — DLS/DMS功能分化的行为表现
- [[parkinsons-disease]] — 多巴胺缺失导致两条通路失衡
- [[corticostriatal-stdp]] — 两条通路的分子可塑性机制（D1/D2不对称STDP，Shen 2008）
- [[three-factor-learning-rule]] — 皮层-纹状体STDP是三因素规则在纹状体的具体实现
- [[addiction]] — 成瘾药物劫持D1-MSN LTP的病理性机制

## 未解问题

- Q-direct-indirect-not-go-nogo：如果两条通路都在运动时激活，那么间接通路的准确功能是什么？目前假说包括：运动序列时序控制、竞争行动的抑制（非停止）、错误监测

## 修订历史

- 2026-09-01 · 创建 · 基于《纹状体的决策细胞》文章 · 初始置信度：高（解剖）/ 中（功能细节）
- 2026-09-28 · 修订（rev2）· 整合Shen 2008（PMID:18687967）STDP分子机制、Kravitz 2010（PMID:20613723）光遗传学因果验证、Frank 2004（PMID:15528409）人类临床证据；新增[[corticostriatal-stdp]]连接；突触层面机制由"理论框架"升级为"直接实验验证" · 依据：第158篇文章

## 来源文章

- [[2026-09-01-medium-spiny-neurons-striatum]]
- [[2026-09-28-corticostriatal-stdp-d1d2-plasticity]]

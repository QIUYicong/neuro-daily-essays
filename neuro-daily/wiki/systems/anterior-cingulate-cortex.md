---
title: 前扣带回皮层
slug: anterior-cingulate-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-08-29
updated: 2026-06-14
revision_count: 3
dimensions: [brain-region, cognition, behavior, microcircuit]
related: [working-memory, dopamine-reward-prediction-error, prefrontal-cortex, three-factor-learning-rule, error-related-negativity, basal-ganglia, orbitofrontal-cortex, pv-interneurons, dlpfc-rule-encoding, frontal-hierarchy, mixed-selectivity, pain-matrix, nociception, descending-pain-modulation]
prerequisites: [dopamine-reward-prediction-error, prefrontal-cortex, synaptic-transmission]
opens_questions: [Q-acc-evc-vs-conflict, Q-acc-subregion-boundary, Q-acc-ern-dopamine-causal]
source_articles: [2026-08-29-anterior-cingulate-cortex-evc-cognitive-control, 2026-08-30-dlpfc-mixed-selectivity-rule-encoding]
key_sources: ["PMID:11488380", "PMID:12374324", "PMID:14963333", "PMID:23889930", "PMID:27090954", "PMID:19443783", "PMID:19385990", "PMID:16783368", "PMID:19091968"]
---

# 前扣带回皮层 (Anterior Cingulate Cortex, ACC)

> **一句话定义**：前扣带回皮层（尤其是 dACC/aMCC）是大脑认知控制系统的调度中心，通过持续计算"投入控制的期望价值（EVC）"来决定是否激活前额叶执行网络；它同时编码行动价值历史、错误-冲突信号、努力成本和反事实奖励，是将突触层面的多巴胺 RPE 信号转化为系统级行为调整的枢纽。

## 当前理解

我们现在认为，dACC/aMCC 不是单一功能的"错误检测器"，而是一个**认知控制资源的成本-效益计算器**，执行"期望控制价值（EVC）"计算：

> EVC = Σ P(结果 | 控制信号, 状态) × 结果价值 − 控制成本(信号)

这一 EVC 框架（Shenhav et al. 2013, PMID:23889930）统一了过去五十年看似矛盾的实验发现：

1. **冲突监测**：冲突↑ → 任务失败概率↑ → 高控制信号的 EVC 升高 → 激活 DLPFC（Botvinick 2001）
2. **错误信号（ERN）**：负 RPE → 当前策略 EVC 下调 → 促发策略切换（Holroyd & Coles 2002）
3. **行动价值积累**：历史奖励塑造行动的期望价值（Kennerley 2006, Rudebeck 2008）
4. **努力成本**：成本↑ → EVC↓ → 降低控制强度或回避高努力选项（Walton/Rushworth 2009）
5. **反事实处理**：对未选选项的虚拟奖励放电，支持探索-利用决策（Hayden 2009）

从自下而上的单细胞视角（Heilbronner & Hayden 2016），dACC 神经元编码**任务状态-策略对（context-strategy pairs）**，功能类似"前运动皮层的上一级"——将任务情境评估转化为行动计划指令。

## 解剖分区

| 亚区 | Brodmann area | 主要功能 |
|------|--------------|---------|
| pgACC（膝下） | BA25, BA32v | 情绪调节、抑郁相关、内脏反应 |
| dACC（膝上） | BA32d, BA24 | **认知控制调度、冲突监测、EVC 计算** |
| aMCC（前中扣带回） | BA24 尾侧 | 行动-结果联系、疼痛、努力-奖励整合 |

**关键解剖特点**：
- 无颗粒层（agranular cortex）：类似运动皮层，输出偏向行动
- 直接连接脊髓（通过 CMA）：可绕过运动皮层直接影响行为
- 三向枢纽：同时连接情感系统（杏仁核、腹侧纹状体）、认知系统（DLPFC、顶叶）和运动系统（M1、SMA）

## 关键机制

### EVC 计算回路

```
冲突信号（来自 DLPFC 反馈）
RPE 信号（来自多巴胺系统）    →  dACC/aMCC
努力成本（来自前岛叶、ACC 内部）            EVC 计算
历史行动价值（来自 ACC 内部循环回路）         ↓
                                    向 DLPFC 等发送"所需控制强度"信号
```

### 错误相关负波（ERN）
- 错误发生后 80–100 ms，EEG 内侧额叶负波
- 源定位指向 dACC（Holroyd & Coles 2002）
- 机制：负 DA-RPE → D2 受体抑制解除 → ACC 激活
- 特点：在意识察觉错误之前就已产生（前意识的自动监控）
- 病理：强迫症（ERN 过强）；精神分裂症（ERN 减弱）

### 行动价值学习
- dACC 沟专门积累行动-奖励历史（Rudebeck 2008）
- 与 OFC 分工：ACC = 行动价值；OFC = 刺激价值
- 病变研究证实因果作用（Kennerley 2006）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 高冲突 → dACC 激活 | Stroop fMRI | PMID:11488380 | 高 |
| 高冲突 dACC → 下一试次 DLPFC↑ + 行为改善 | Stroop fMRI 序列分析 | PMID:14963333 | 高 |
| ERN 反映 DA-RPE 传递到 ACC | 理论+EEG 药理 | PMID:12374324 | 中-高 |
| ACC 病变→行动价值学习受损 | 猕猴切除 | PMID:16783368 | 高（因果） |
| ACC 沟=行动价值 / OFC=刺激价值 | 猕猴多区域病变 | PMID:19091968 (PMC6671924) | 高 |
| dACC 神经元对反事实奖励放电 | 猕猴单细胞 | PMID:19443783 (PMC3096846) | 高 |
| ACC 病变→回避高努力选项 | 大鼠T型迷宫 | PMID:19385990 (PMC2954046) | 高（因果） |
| EVC 框架统一冲突/错误/努力/奖励 | 理论+实验汇集 | PMID:23889930 (PMC3767969) | 中（理论，多实验支持） |
| dACC 神经元编码任务状态-策略对 | 猕猴单细胞综述 | PMID:27090954 (PMC5512175) | 中-高 |
| dACC 病变不影响基本认知控制任务 | 人类神经心理 | PMID:15705613 | 中（反例，需整合） |

## 连接

- [[working-memory]] — dACC 计算 EVC，向 DLPFC 发送激活信号；工作记忆任务中 dACC 检测冲突
- [[dopamine-reward-prediction-error]] — DA-RPE 是 ERN 的分子基础；RPE 是 EVC 计算的关键输入
- [[prefrontal-cortex]] — dACC（调度）→ DLPFC（执行）是认知控制的核心双节点
- [[dlpfc-rule-encoding]] — dACC EVC 计算决定是否激活 DLPFC 的规则编码/执行资源
- [[frontal-hierarchy]] — dACC 是额叶层级中的调度节点，DLPFC 是规则编码顶端
- [[mixed-selectivity]] — dACC 的错误/冲突信号可能是 DLPFC 混合选择性形成的学习输入
- [[three-factor-learning-rule]] — 突触层面的 DA-RPE（三因素规则）与系统层面的 ERN 使用同一条多巴胺通路
- [[orbitofrontal-cortex]] — 功能分工：ACC=行动价值；OFC=刺激价值（Rudebeck 2008）
- [[basal-ganglia]] — 纹状体接收来自 ACC 的行动价值信号；BG-ACC 共同构成动作选择回路
- [[error-related-negativity]] — ERN 是 dACC 活动的宏观 EEG 标志物

## ACC 在疼痛处理中的角色（补充，来自 #190）

前扣带皮层（特别是 aMCC/rACC）是疼痛矩阵情感-动机通路的核心节点：

- **痛觉不愉快感**：Rainville et al. 1997 经典催眠研究证明，催眠可选择性改变痛的不愉快感（ACC 活动改变），而不改变感觉强度（S1 不变），直接建立 ACC↔不愉快感的因果关系
- **下行调制的皮质驱动**：ACC 通过投射至 PAG（中脑导水管周围灰质），是情绪→下行镇痛（PAG→RVM→脊髓）路径的起点
- **安慰剂镇痛**：rACC 激活幅度与安慰剂镇痛效果正相关（Wager et al. 2004, *Science* 303:1162）
- **慢性痛的 ACC 变化**：慢性痛患者 ACC 灰质体积减少；默认模式网络（ACC 为核心）与疼痛回路异常连接增强

**pgACC vs aMCC 的分工**（与认知控制分工不同）：
- pgACC（BA25/32v）：情绪调制、安慰剂镇痛效果较强、与内脏自主神经直接联系
- aMCC（BA24 尾侧）：痛觉引起的行为驱动（逃避动机、努力-奖励整合）

## 未解问题

- Q-acc-evc-vs-conflict（高优先级）：dACC 是纯粹的 EVC 计算器，还是冲突检测是其独立功能之一？需要在控制冲突和 EVC 单独变化的实验设计中直接对比
- Q-acc-subregion-boundary（高优先级）：dACC 和 aMCC 的功能边界在人类 7T fMRI 或 iEEG 中是否能被清楚定义？
- Q-acc-ern-dopamine-causal（中优先级）：ERN 与 ACC 的 DA 释放是否有直接因果链？需要 fMRS 或 PET-EEG 联合测量
- Q-acc-pain-cog-overlap（中优先级）：ACC 的认知控制功能与痛觉情感功能是否共享神经元群体？还是存在可分离的子区域？

## 修订历史

- 2026-08-29 · 创建 · 基于《大脑的成本-效益计算器》一文（#129） · 涵盖冲突监测、ERN-DA理论、行动价值学习、EVC框架、反事实奖励 · 初始置信度：高（脑区解剖+功能有强实验证据；EVC整合框架有部分直接验证）
- 2026-08-30 · 修订（rev1→rev2）· 基于《前额叶皮层的高维秘密》(#130) · 新增 dACC→DLPFC 控制调度连接；related 新增 dlpfc-rule-encoding/frontal-hierarchy/mixed-selectivity；来源文章新增 #130
- 2026-06-14 · 修订（rev2→rev3）· 基于《伤害感受≠疼痛体验》(#190) · 新增：ACC 在疼痛矩阵中的角色（痛觉不愉快感催眠证据、安慰剂镇痛、pgACC vs aMCC 分工）；related 新增 pain-matrix/nociception/descending-pain-modulation；opens_questions 新增 Q-acc-pain-cog-overlap

## 来源文章

- [[2026-08-29-anterior-cingulate-cortex-evc-cognitive-control]]
- [[2026-08-30-dlpfc-mixed-selectivity-rule-encoding]]

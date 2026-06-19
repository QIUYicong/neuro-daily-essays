---
title: 前庭系统
slug: vestibular-system
domain: systems
type: structure
status: established
confidence: high
created: 2026-07-31
updated: 2026-07-31
revision_count: 1
dimensions: [molecular, cellular, brain-region, whole-brain-network, behavior, cognition]
related: [head-direction-cells, path-integration, multisensory-integration, superior-colliculus, cerebellum, forward-model, efference-copy, bayesian-causal-inference]
prerequisites: [action-potential, synaptic-transmission, mechanoreceptor-ltmr]
opens_questions: [Q-vest-01, Q-vest-02, Q-vest-03]
source_articles: [2026-07-31-vestibular-system-vor-efference-copy]
key_sources: ["PMID:37739815", "PMCID:PMC10591839", "PMID:31401034", "PMCID:PMC6733654", "PMID:35958995"]
---

# 前庭系统 (Vestibular System)

> **一句话定义**：位于内耳的六自由度运动传感器系统，由检测旋转的半规管和检测线性加速度/重力的耳石器官构成，经毛细胞机械传导将物理运动转化为神经信号，通过三神经元弧驱动前庭-眼反射（VOR）稳定视觉，并借助小脑的传出拷贝机制区分"主动自我运动"与"外界扰动"。

## 当前理解

我们现在认为，前庭系统远不止是一套简单的"平衡器官"——它是大脑感知运动世界的核心传感基础，并且是神经系统中"主动预测→感觉抑制"原则最早、最清晰的体现之一。

前庭系统由两个功能互补的感受器系统组成：
- **半规管（Semicircular Canals）**：三根近似正交的充液管，检测头部在三轴上的角加速度（旋转）
- **耳石器官（Otolith Organs）**：椭圆囊（utricle，水平面线性加速度）+ 球囊（saccule，垂直轴线性加速度+重力）

两者共同提供头部运动的完整六自由度（3轴旋转 + 3轴线性加速度）表征。耳石器官面临一个根本物理挑战：头部倾斜和线性平移在力学上等效（爱因斯坦等效原理），无法单独区分。大脑通过小脑蚓结节（nodulus/uvula）结合半规管信号解决这一歧义（Cullen 2023, PMID:37739815）。

更深层的机制是**传出拷贝（efference copy）**介导的自身运动区分：前庭核的 VO 神经元在主动运动时被小脑发出的预测消除信号抑制约 70-80%，只有当本体感觉反馈与预测不匹配时（意外被推），消除信号才停止发出，VO 神经元恢复正常响应（Brooks & Cullen 2019, PMID:31401034）。

## 关键机制

### 1. 毛细胞机械传导（分子层）

静纤毛（stereocilia）梯形阵列 → 顶端连接（CDH23-PCDH15 蛋白链，PMID:30617060）→ 传递张力至 TMC1/TMC2 通道 → K⁺/Ca²⁺ 内流 → 去极化 → 带状突触释放谷氨酸 → 前庭神经节（Scarpa's ganglion）激活

传导时间：亚毫秒级。TMC1/TMC2 是最可能的孔区亚基，与 LHFPL5、TMIE、CIB2/3 等辅助蛋白共同构成完整传导复合体（PMID:34617206）。

### 2. 半规管工作原理（细胞/系统层）

内淋巴液（endolymph）因惯性滞后于骨管旋转 → 流动冲击壶腹帽（cupula）→ deflect 毛细胞束 → 向高纤毛偏转（兴奋）/ 向低纤毛偏转（抑制）。三根管两两垂直 → 所有旋转轴均被覆盖。

### 3. 耳石器官工作原理（细胞/系统层）

耳石膜上的碳酸钙晶体（耳石/otoconia，由 Otoconin-90、Otolin-1 等蛋白调控，PMID:35958995）在线性加速度作用下相对毛细胞层滑动 → 毛细胞偏转。椭圆囊（水平面）+球囊（垂直轴）互补检测所有线性运动分量。

### 4. 三神经元 VOR 弧（脑区层）

前庭传入（VIII 神经/Scarpa 神经节）→ 前庭核（VN）→ 眼外肌运动核（动眼/滑车/外展）→ 眼球补偿运动。总延迟 ~7-10ms，比视觉矫正通路（70-100ms）快一个数量级。

### 5. 小脑三区的前庭功能分工（脑区层）

| 小脑区域 | 功能 |
|---------|------|
| 绒球（flocculus/paraflocculus） | VOR 增益适应（LTD/LTP 调节 PF-PC 突触强度）|
| 前蚓部（anterior vermis, lobules I-V） | 头坐标→体坐标转换；传出拷贝消除信号生成 |
| 蚓结节/腹蚓垂（nodulus/ventral uvula） | 倾斜-平移歧义解决（canal-otolith 信号整合）|

### 6. 传出拷贝机制（认知/全脑网络层）

运动指令发出 → 副本（传出拷贝）至前蚓部 → 预测本体感觉反馈 → 若实际匹配预测：向 VO 神经元发消除信号（抑制 70-80%）→ 主动运动不被感知为"外界运动"。若不匹配：无消除信号 → VO 正常响应 → 触发矫正反应。

### 7. 前庭皮层整合（全脑网络层）

前庭信号经丘脑多核（VPLo、Po、CL）广泛分发至皮层，核心在**顶岛前庭皮层（PIVC）**，包含纯前庭亚区和视觉-前庭混合亚区（PIVC+，PMID:29995604）。此外，前庭信号也到达海马，参与空间记忆和情景记忆的构建（PMID:21223979）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| TMC1/2 是毛细胞 MET 通道核心组分 | TMC KO 小鼠无听觉+前庭反应；电生理确认通道消失 | PMID:25074487 | 高（遗传+电生理） |
| VO 神经元主动运动时抑制 ~70-80% | 清醒猴主动 vs 被动头部运动，前庭核单神经元记录 | PMID:21286693 | 高（灵长类体内） |
| 消除信号需要本体感觉匹配（非仅运动指令） | 注射阻断肌肉收缩（运动指令有但无本体反馈）→ 抑制消失 | PMID:31401034 | 高（猫体内） |
| 蚓结节解决倾斜-平移歧义 | 猴，蚓结节浦肯野细胞单神经元记录，不同倾斜/平移协议 | PMID:37739815 | 高（灵长类体内） |
| 绒球损伤损害 VOR 适应 | 绒球切除，多物种，VOR 增益不能适应 | PMID:15543809 | 高（多物种） |
| PIVC 包含多功能亚区 | 人类 fMRI，热卡前庭刺激 vs 视觉运动刺激 | PMID:29995604 | 中（人类影像） |

## 连接

- [[head-direction-cells]] — 头向细胞的角速度输入来自前庭半规管（经前庭核→LMN→DTN→ADN→后下托）
- [[path-integration]] — 路径整合的角度维度由前庭半规管提供；主动运动时传出拷贝激活路径整合所需的前庭通路
- [[multisensory-integration]] — PIVC 是视觉-前庭整合的核心皮层节点；前庭是上丘多感觉融合的重要输入
- [[cerebellum]] — 小脑三个区域（绒球/前蚓/蚓结节）分别承担 VOR 适应/传出拷贝/倾斜-平移区分
- [[forward-model]] — 传出拷贝机制是前向模型最清晰的体内实例（预测感觉后果→消除自身运动信号）
- [[efference-copy]] — 传出拷贝/效应传出，前庭系统中的具体实现
- [[bayesian-causal-inference]] — 倾斜-平移消解是贝叶斯多感觉推断在前庭系统的具体案例

## 未解问题

- Q-vest-01（高）：PIVC 刺激能否在人类中产生明确的旋转/倾斜主观感知？能否用于前庭假体闭环控制？
- Q-vest-02（中）：前庭-海马连接在空间记忆和情景记忆中的具体功能？前庭损伤患者是否同时出现记忆障碍？
- Q-vest-03（中）：精神分裂症患者中传出拷贝机制是否异常？能否通过前庭刺激范式在人类中量化自我-他者信号区分阈值？

## 修订历史

- 2026-07-31 · 创建 · 基于《平衡的物理学》（#99）· 来源：PMID:37739815(OA)、31401034(OA)、35958995(OA)、25074487、34617206、29995604、21223979 · 初始置信度：高

## 来源文章

- [[2026-07-31-vestibular-system-vor-efference-copy]]

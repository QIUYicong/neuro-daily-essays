---
title: 前向模型
slug: forward-model
domain: concepts
type: theory
status: mainstream
confidence: medium
created: 2026-06-23
updated: 2026-06-13
revision_count: 4
dimensions: [brain-region, cognition, behavior, cellular, microcircuit]
related: [cerebellum, predictive-coding, motor-cortex, world-model, efference-copy, active-inference, proprioceptive-prediction, deep-cerebellar-nuclei, spinocerebellar-tracts, long-latency-stretch-reflex, optimal-feedback-control]
prerequisites: [cerebellum, motor-cortex]
opens_questions: [Q-cb-01, Q-fm-01, Q-fep-01]
source_articles: [2026-06-23-cerebellum-motor-prediction, 2026-09-02-cerebellum-active-inference-proprioceptive-prior, 2026-06-13-spinocerebellar-tracts-dsct-vsct, 2026-06-13-long-latency-stretch-reflex-transcortical-loop]
key_sources: ["PMID:21227230", "PMID:33203932", "PMID:41451122", "PMID:40523942", "PMID:30627965", "PMID:23613538", "PMID:25688187"]
---

# 前向模型 (Forward Model)

> **一句话定义**：给定运动指令（传出拷贝），预测该运动将产生什么感觉后果的内部计算模型——被认为主要由小脑实现，使大脑能在感觉反馈到达（延迟 20–100ms）之前就对运动结果有精确预期，从而实现快速精确运动控制。

## 当前理解

感觉反馈存在神经传导延迟（末梢到皮层约 20–100ms），这使"等待反馈再纠错"无法实现快速精确的运动。Wolpert、Miall 和 Kawato（1998, DOI:10.1016/S1364-6613(98)01221-2）提出，小脑包含两类**内部模型**：

**前向模型（Forward Model）**：
- 输入：运动指令的副本（**传出拷贝 / efference copy**）
- 输出：预测的感觉后果（手臂将在何处、将感知到何种触觉）
- 功能：让大脑预先知道运动的"期望结果"，而无需等待真实感觉反馈

**逆向模型（Inverse Model）**：
- 输入：期望的运动轨迹
- 输出：达到该轨迹所需的运动指令
- 功能：直接反向计算控制信号，实现精确轨迹跟踪

前向模型输出的预测，与通过下橄榄核→攀爬纤维到达浦肯野细胞的实际感觉信号**对比**，产生**预测误差**。这个误差驱动小脑可塑性（LTD/LTP）更新内部模型，使预测越来越准确。

**主动推断视角（2025 年更新）**：Parr、Ramstead 和 Friston（2025，PMID:41451122）提出了一个重要的重新解读：在主动推断框架中，**只需要前向模型**，逆向模型的计算被脊髓牵张反射弧代替。"运动命令"本质上是向脊髓发送的**本体感觉先验**（期望感觉状态），反射弧消除本体感觉预测误差，从而实现运动。这一视角使运动控制和感知统一在相同的自由能最小化目标下。

**直接神经证据**（Tanaka et al., 2019，PMID:30627965）：在猕猴多位点电生理记录中，齿状核在 t 时刻的放电率可预测 t+20ms 的苔藓纤维输入（R²=0.89），覆盖全部感觉反馈延迟窗口，网络级计算结构类似卡尔曼滤波器。

**与前馈映射框架的争议（2025，登记矛盾 C-2026-09-02-01）**：Nguyen & Person（2025，PMID:40523942）的综述提出，小脑可能实现"模型无关的前馈映射"（将情境直接映射到输出），而非维护显式的状态空间内部模型。这一分歧在运动泛化和新奇学习任务上有不同预测，尚待实验裁决（见矛盾 C-2026-09-02-01）。

## 关键机制

### MOSAIC 模型（Wolpert & Kawato 扩展版）
多模块前向/逆向模型对（Multiple paired forward-inverse models），每对负责不同的运动情境（如持物 vs 空手）。责任信号（responsibility signal）动态选择哪组模型被激活，类似混合专家（mixture of experts）架构。

### 前向模型的神经底物（尚不确定）
- 小脑颗粒细胞的时序放电模式可能提供时间基础
- 小脑浦肯野细胞的简单放电（simple spike）编码预测输出
- 复杂放电（CF）→ 预测误差信号

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 小脑参与前向预测（间接） | 眼球跟踪（VOR/OKR）延迟补偿；计算建模 | DOI:10.1016/S1364-6613(98)01221-2 | 中（间接） |
| 传出拷贝在运动前到达小脑 | 解剖学：皮质-脊髓投射侧支 → 小脑 | 解剖学证据 | 高 |
| 前向模型更新依赖小脑可塑性 | 小脑损伤患者 VOR 适应受损 | 临床证据 | 高 |
| 齿状核放电预测未来苔藓纤维输入（R²=0.89 @ 20ms） | 猕猴多位点电生理记录；线性重建 | PMID:30627965 | 高（单物种，间接） |
| 小脑实现多模块前向模型（MOSAIC） | 间接行为学证据；fMRI 研究 | 多项研究 | 中 |
| 小脑可能实现前馈映射而非内部模型 | 行为学；钙成像 | PMID:40523942 | 中（综述，争议中，见 C-2026-09-02-01）|
| DSCT 70% 神经元受 CPG 驱动（在无外周输入时）| 去脑猫细胞内记录，离断外周神经，虚拟运动 | PMID:23613538 (PMC3853486) | 高（单实验室，猫模型）|

## 连接

- [[cerebellum]] — 前向模型的主要神经底物
- [[predictive-coding]] — 前向模型是预测处理的一个专用子系统
- [[motor-cortex]] — 发出运动指令和传出拷贝
- [[world-model]] — 前向模型是更广义世界模型的一个专用子系统（运动领域）
- [[cerebellar-ltd]] — 误差信号驱动前向模型更新的分子机制
- [[spinocerebellar-tracts]] — 前向模型计算的关键输入通道（感觉 + CPG 混合信号）
- [[long-latency-stretch-reflex]] — LLR 是前向模型参与运动控制的近实时表现（小脑调制 LLR 增益）
- [[optimal-feedback-control]] — OFC 框架在计算级与前向模型互补（前向模型实现状态估计，OFC 定义代价函数）

## 未解问题

- Q-cb-01：前向模型的时序预测在颗粒细胞层面如何实现？时间基础是什么？
- Q-fm-01：前向模型框架能否扩展到语言（预测下一个词）和社会认知（预测他人反应）？与 CCAS 的关联？

## 矛盾条目

- **C-2026-09-02-01**（open）：小脑实现"显式内部模型"（claim_A，Wolpert-Kawato + 主动推断框架）vs "模型无关前馈映射"（claim_B，Nguyen & Person 2025）。nature: 计算级理论分歧；实验上需要运动泛化/新奇学习任务来裁决。

## 修订历史

- 2026-06-23 · 创建 · 基于《小脑的秘密》一文 · 初始置信度：中（间接证据为主，计算框架合理但神经底物细节待确认）
- 2026-09-02 · 修订（rev1→rev2）· 基于《小脑作为主动推断引擎》· 新增：主动推断视角（本体感觉先验，逆向模型被脊髓代替，Parr et al. 2025）；直接神经证据（Tanaka 2019，R²=0.89）；登记新矛盾 C-2026-09-02-01（内部模型 vs 前馈映射）；扩展 dimensions、related、key_sources
- 2026-06-13 · 修订（rev2→rev3）· 基于《双轨信使：脊髓小脑束》(#176) · 新增：脊髓小脑束作为前向模型输入通道的关键证据（DSCT 70% 受 CPG 驱动）；新增 spinocerebellar-tracts 到 related；更新 key_sources 和 source_articles
- 2026-06-13 · 修订（rev3→rev4）· 基于文章 #180《快反射的皮层真相》· 新增：LLR 作为小脑通过前向模型调制近实时运动增益的行为证据（Kurtzer 2015，小脑损伤患者 LLR 模式保留但幅度降低）；新增 long-latency-stretch-reflex 和 optimal-feedback-control 到 related；补充 PMID:25688187

## 来源文章

- [[2026-06-23-cerebellum-motor-prediction]]
- [[2026-09-02-cerebellum-active-inference-proprioceptive-prior]]
- [[2026-06-13-spinocerebellar-tracts-dsct-vsct]]

---
title: 前向模型
slug: forward-model
domain: concepts
type: theory
status: mainstream
confidence: medium
created: 2026-06-23
updated: 2026-10-04
revision_count: 3
dimensions: [brain-region, cognition, behavior]
related: [cerebellum, predictive-coding, motor-cortex, world-model, efference-copy]
prerequisites: [cerebellum, motor-cortex]
opens_questions: [Q-cb-01, Q-fm-01]
source_articles: [2026-06-23-cerebellum-motor-prediction, 2026-09-04-deep-cerebellar-nuclei-dcn-output, 2026-10-04-cerebellum-cognition-language-social]
key_sources: ["PMID:21227230", "PMID:33203932", "PMID:34262527", "PMID:28385461", "PMID:30697149", "PMID:31522332"]
---

# 前向模型 (Forward Model)

> **一句话定义**：给定运动指令（传出拷贝），预测该运动将产生什么感觉后果的内部计算模型——被认为主要由小脑实现，使大脑能在感觉反馈到达（延迟 20–100ms）之前就对运动结果有精确预期，从而实现快速精确运动控制；现代研究表明该原理也扩展到语言预测（Crus I/II 参与句子续接预测）和社会认知（Crus I/II 参与心理理论），统一了小脑运动和认知功能。

## 当前理解

感觉反馈存在神经传导延迟（末梢到皮层约 20–100ms），这使"等待反馈再纠错"无法实现快速精确的运动。Wolpert、Miall 和 Kawato（1998, PMID:21227230）提出，小脑包含两类**内部模型**：

**前向模型（Forward Model）**：
- 输入：运动指令的副本（**传出拷贝 / efference copy**）
- 输出：预测的感觉后果（手臂将在何处、将感知到何种触觉）
- 功能：让大脑预先知道运动的"期望结果"，而无需等待真实感觉反馈

**逆向模型（Inverse Model）**：
- 输入：期望的运动轨迹
- 输出：达到该轨迹所需的运动指令
- 功能：直接反向计算控制信号，实现精确轨迹跟踪

前向模型输出的预测，与通过下橄榄核→攀爬纤维到达浦肯野细胞的实际感觉信号**对比**，产生**预测误差**。这个误差驱动小脑可塑性（LTD/LTP）更新内部模型，使预测越来越准确。

这一框架的深远意义：小脑不是被动等待误差来纠正，而是**主动预测以超越延迟**。"闭眼精准接球"成为可能，正是因为大脑在球飞来的过程中持续更新前向模型的输出，在接触发生之前就完成了运动调整。

## 关键机制

### MOSAIC 模型（Wolpert & Kawato 扩展版）
多模块前向/逆向模型对（Multiple paired forward-inverse models），每对负责不同的运动情境（如持物 vs 空手）。责任信号（responsibility signal）动态选择哪组模型被激活，类似混合专家（mixture of experts）架构。

### 前向模型的神经底物

**小脑皮层层面**（尚不确定）：
- 小脑颗粒细胞的时序放电模式可能提供时间基础
- 浦肯野细胞的简单放电（simple spike）编码预测输出
- 攀爬纤维（CF）→ 预测误差信号（实际vs预测的对比）

**深部小脑核层面**（Miyata 2021, PMID:34262527 / PMC8273235）：
- DCN 谷氨酸能神经元是前向模型输出的最终执行者
- 系统辨识研究表明 **DCN 输出能预测 200ms 后的运动状态**——正好补偿感觉反馈延迟并留有余量
- 长环路闭合：DCN → VL 丘脑 → 运动皮层 → 脑桥核 → 苔藓纤维 → 小脑（传出拷贝路径）

**Kalman 滤波等价**：从计算角度，DCN 的预测-更新循环在数学上等价于 Kalman 滤波器——整合先验预测（PC 时序）和当前传入信息（苔藓纤维），输出最优状态估计

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 小脑参与前向预测（间接） | 眼球跟踪（VOR/OKR）延迟补偿；计算建模 | PMID:21227230 | 中（间接） |
| 传出拷贝在运动前到达小脑 | 解剖学：皮质-脊髓投射侧支 → 小脑 | 解剖学证据 | 高 |
| 前向模型更新依赖小脑可塑性 | 小脑损伤患者 VOR 适应受损 | 临床证据 | 高 |
| 小脑实现多模块前向模型 | 间接行为学证据；fMRI 研究 | 多项研究 | 中 |
| DCN 输出预测 200ms 后运动状态 | 系统辨识研究（Kakei et al.，间接）| PMID:34262527 | 中（间接）|
| 前向预测中断 → 意向性震颤 | 小脑损伤患者的不规则震颤与预测失败一致 | 临床病理对应 | 高 |
| **前向模型扩展至语言预测**：右侧 Crus I/II 在不可预期句子续接时激活增强 | fMRI 语言任务 meta-analysis | PMID:28385461 (Sokolov 2017) | 中（间接相关） |
| **前向模型扩展至社会认知**：左侧 Crus I/II 在心理理论（ToM）任务中激活增强 | fMRI ToM 任务 meta-analysis | PMID:28385461 (Sokolov 2017) | 中（间接相关） |
| **前向模型损伤 → 语言/社会认知障碍**（CCAS）：129 项研究 3140 患者，语言 d=−0.81，社会认知 d=−0.81 | 系统综述+元分析 | PMID:40047904 (Reumers 2025) | 高（元分析） |
| 浦肯野细胞简单放电以相反极性同时编码预测和反馈成分 | 猕猴浦肯野细胞单细胞记录 | PMID:30697149 (Popa 2019) | 高（直接电生理） |

## 连接

- [[cerebellum]] — 前向模型的主要神经底物
- [[predictive-coding]] — 前向模型是预测处理的一个专用子系统
- [[motor-cortex]] — 发出运动指令和传出拷贝
- [[world-model]] — 前向模型是更广义世界模型的一个专用子系统（运动领域）
- [[cerebellar-ltd]] — 误差信号驱动前向模型更新的分子机制
- [[deep-cerebellar-nuclei]] — 前向模型输出的最终执行节点（DCN → VL 丘脑）
- [[cerebellar-cognitive-affective-syndrome]] — CCAS：前向模型扩展至认知领域时受损的临床综合征
- [[interval-timing]] — 颗粒细胞秒级缓坡放电为认知前向模型提供时序基础（Garcia-Garcia 2024）

## 未解问题

- Q-cb-01：前向模型的时序预测在颗粒细胞层面如何实现？时间基础是什么？（Garcia-Garcia 2024 提供了秒级部分解答：颗粒细胞持续性缓坡放电）
- Q-fm-01：**部分解答（2026-10-04）**：前向模型框架已有合理证据扩展到语言和社会认知（Sokolov 2017, Reumers 2025 元分析），但语言/ToM 前向模型的**直接神经机制**（哪些颗粒细胞提供什么时序基础，攀爬纤维传递什么认知误差）仍未知。见 Q-cerebellar-cognitive-01/02。
- Q-cerebellar-cognitive-01：Crus I/II 的语言/ToM 前向模型是否依赖 PF-PC LTD 这同一分子机制？
- Q-cerebellar-cognitive-02：认知前向模型中攀爬纤维传递的是什么教师信号？

## 修订历史

- 2026-06-23 · 创建 · 基于《小脑的秘密》一文 · 初始置信度：中（间接证据为主，计算框架合理但神经底物细节待确认）
- 2026-09-04 · 补充 DCN 作为前向模型输出执行节点的证据：DCN 预测 200ms 后运动状态（Miyata 2021, PMID:34262527）；Kalman 滤波等价框架；长环路闭合机制 · 基于 2026-09-04-deep-cerebellar-nuclei-dcn-output
- 2026-10-04 · **重要扩展**：补充前向模型认知扩展的多项证据——Sokolov 2017 (PMID:28385461) 语言预测/ToM 的 Crus I/II fMRI 激活；Reumers 2025 元分析 (PMID:40047904) 129 项研究语言 d=−0.81 社会认知 d=−0.81；Popa 2019 浦肯野细胞双模式编码直接电生理；Garcia-Garcia 2024 颗粒细胞 2 秒时序缓坡放电；更新一句话定义以反映认知扩展；将 Q-fm-01 标注为部分解答 · 基于 2026-10-04-cerebellum-cognition-language-social

## 来源文章

- [[2026-06-23-cerebellum-motor-prediction]]
- [[2026-09-04-deep-cerebellar-nuclei-dcn-output]]

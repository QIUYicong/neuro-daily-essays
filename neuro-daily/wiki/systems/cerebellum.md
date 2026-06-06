---
title: 小脑
slug: cerebellum
domain: systems
type: structure
status: established
confidence: high
created: 2026-06-23
updated: 2026-08-01
revision_count: 2
dimensions: [cellular, microcircuit, brain-region, cognition]
related: [motor-cortex, predictive-coding, cerebellar-ltd, climbing-fiber-error-signal, purkinje-cell, forward-model, ltd, memory-consolidation]
prerequisites: [purkinje-cell, parallel-fiber, climbing-fiber-error-signal, deep-cerebellar-nuclei]
opens_questions: [Q-cb-01, Q-cb-02, Q-cb-03, Q-cb-04, Q-cb-05]
source_articles: [2026-06-23-cerebellum-motor-prediction, 2026-08-01-cerebellar-ltd-purkinje-motor-learning]
key_sources: ["PMID:33203932", "PMID:33288911", "PMID:21227230", "PMID:11319554", "PMID:23440175", "PMID:30069835", "PMID:30995136", "PMID:34219651", "PMID:31522332"]
---

# 小脑 (Cerebellum)

> **一句话定义**：大脑的精密预测处理器——以运动误差为教师信号，通过多层可塑性机制构建身体运动的前向模型，实现精确的预测性运动控制，并广泛参与认知和情感功能。

## 当前理解

小脑重约 150 克，占脑重约 10%，却含大脑约 80% 以上的神经元（约 690 亿，主要为颗粒细胞）。其核心功能长期被认为是运动协调和运动学习，但现代研究（De Zeeuw et al., 2021）表明，小脑实际上是一个**多样化、动态递归的系统**，通过并行大脑皮层环路广泛参与认知和情感调控（CCAS）。

我们现在认为，小脑的本质是一台**预测机器**：它利用传出拷贝（efference copy）预测运动的感觉后果，将预测与实际感觉（通过下橄榄核→攀爬纤维）对比，以误差信号驱动多层可塑性，不断优化对身体运动的内部模型（Wolpert et al., 1998）。

## 解剖架构

### 小脑皮层三层

| 层 | 主要细胞类型 | 功能 |
|----|-------------|------|
| 分子层 | 平行纤维终末、分子层中间神经元（星状细胞、篮状细胞） | 信息整合、LTD/LTP 发生位点 |
| 浦肯野细胞层 | 浦肯野细胞（PC） | 小脑皮层唯一输出；GABA 抑制 DCN |
| 颗粒层 | 颗粒细胞（GC，约 690 亿）、高尔基细胞 | 苔藓纤维信息膨胀式重编码 |

### 关键纤维系统

- **苔藓纤维（Mossy Fiber, MF）**：来自脊髓、脑桥核、前庭核等，携带感觉运动信息 → 颗粒细胞 → 平行纤维（PF）
- **攀爬纤维（Climbing Fiber, CF）**：来自对侧下橄榄核（IO）；每根 CF 只投射到单一 PC；触发复杂放电；被认为携带运动误差信号
- **平行纤维（Parallel Fiber, PF）**：颗粒细胞轴突分叉，横向穿越浦肯野细胞树突扇面

### 深部小脑核（DCN）

小脑皮层（PC）的 GABA 抑制 DCN；运动学习中 DCN 本身也发生可塑性变化。DCN 输出经丘脑至大脑皮层（运动/认知），形成小脑-皮层环路。

## 关键机制

### 1. 小脑 LTD（Marr-Albus-Ito 核心机制）
PF + CF 同时激活 → mGluR1/IP₃/PKC → AMPAR 内吞 → PF-PC 突触长期减弱。  
详见 [[cerebellar-ltd]]。

### 2. 多层可塑性（现代综合）
- PF-PC LTD（经典）
- PF-PC LTP（LTD 反转）
- 分子层中间神经元（MLI）可塑性
- 颗粒细胞内在可塑性
- DCN 可塑性
- 上行/下行微区双向学习（De Zeeuw 2021）

### 3. 前向/逆向模型
详见 [[forward-model]]。小脑利用传出拷贝预测运动感觉后果，超越反馈延迟。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| mGluR1 是 PF-LTD 诱导必要受体 | mGluR1 KO 小鼠：LTD 受损 + 眼睑反射学习障碍 | PMID:7954803 | 高 |
| 无 LTD 也能进行小脑运动学习 | 三种 AMPAR 内吞阻断突变小鼠，VOR/眼睑/步态学习正常 | PMID:21482355 | 高 |
| 小脑存在上行/下行微区双向学习 | 综合多任务体内记录 | PMID:33203932 | 中-高 |
| 小脑含前向/逆向内部模型 | 眼球跟踪 + 计算建模 | PMID:21227230 | 中（间接） |
| 小脑损伤导致认知情感障碍（CCAS） | 临床病例系列 + 损伤定位分析（156例）| PMID:31522332 | 高 |
| CF 复杂放电精确编码误差大小/方向（眼跳后 80–120ms）| 体内 PC 记录 + SC 刺激 | PMID:30995136 | 高 |
| 绒球最优 PF-CF 配对间隔 ≈ 120ms（匹配视觉延迟）| 精确时间窗口调控实验 | PMID:30069835 | 高 |
| GluA4 KO 小鼠：膨胀编码↓44%，眼睑条件反射消失 | eLife 因果实验 | PMID:34219651 | 高 |
| 小脑皮层 LTD 为快速适应，DCN LTP 为慢速巩固 | 双相时间进程 + 可逆橄榄核失活实验 | PMID:23440175 | 中 |

## 连接

- [[motor-cortex]] — 小脑-运动皮层闭环（通过丘脑）
- [[predictive-coding]] — 小脑是专用预测误差学习系统
- [[cerebellar-ltd]] — 经典 LTD 机制详情
- [[forward-model]] — 内部模型框架
- [[ltd]] — 小脑 LTD 与海马 LTD 的异同
- [[memory-consolidation]] — 程序性记忆（小脑）vs 陈述性记忆（海马）
- [[diseases/spinocerebellar-ataxia]] — 疾病作为窗口（SCA）

## 未解问题

- **Q-cb-01**（高优先级）：前向模型在哪个细胞/回路层面实现？颗粒细胞时间模式？PC 复杂放电时序？
- **Q-cb-02**（高优先级）：攀爬纤维究竟编码什么类型的"误差"——感觉预测误差、运动结果误差还是时间违规？
- **Q-cb-03**（中优先级）：小脑认知功能是否使用与运动 LTD 相同的可塑性机制？CCAS 的突触机制？
- 见 `state/unresolved_questions.md` 中的 Q-cb-01 至 Q-cb-03

## 修订历史

- 2026-06-23 · 创建 · 基于《小脑的秘密》一文 · 来源：PMID:33203932, 33288911, 21227230, 11319554, 21482355, 7954803
- 2026-08-01 · 修订（rev1→rev2）· 基于《教师信号的困境》（文章#100）· 新增：CF 误差信号量化数据（Soetedjo 2019）、绒球 120ms 最优窗口（Suvrathan 2018）、GluA4 膨胀编码因果实验（Kita 2021）、CCAS 156例临床证据（Task Force 2020）、双相记忆轨迹（Ito 2013）；新增 wiki 子页 purkinje-cell、climbing-fiber-error-signal；related/key_sources/prerequisites 更新；新增 Q-cb-04/Q-cb-05

## 来源文章

- [[2026-06-23-cerebellum-motor-prediction]]
- [[2026-08-01-cerebellar-ltd-purkinje-motor-learning]]

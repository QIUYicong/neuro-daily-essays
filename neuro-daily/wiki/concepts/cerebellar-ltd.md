---
title: 小脑 LTD（浦肯野细胞平行纤维长时程抑制）
slug: cerebellar-ltd
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-23
updated: 2026-10-04
revision_count: 3
dimensions: [molecular, synaptic, cellular, microcircuit]
related: [ltd, cerebellum, mGluR1, forward-model, climbing-fiber, parallel-fiber, purkinje-cell, granule-cell-cerebellar]
prerequisites: [ltd, nmda-receptor, pkc-signaling, ampa-receptor]
opens_questions: [Q-cb-01, Q-cb-02]
source_articles: [2026-06-23-cerebellum-motor-prediction, 2026-09-03-purkinje-cell-cerebellar-motor-learning, 2026-10-04-cerebellum-cognition-language-social]
key_sources: ["PMID:7954803", "PMID:21482355", "PMID:11319554", "PMID:33203932", "PMID:31572132", "PMID:40848722", "PMID:27857688", "PMID:38870929"]
---

# 小脑 LTD（Cerebellar LTD / PF-PC LTD）

> **一句话定义**：当颗粒细胞平行纤维输入与攀爬纤维误差信号在浦肯野细胞树突上同时激活时，该平行纤维突触的 AMPA 受体通过 mGluR1→IP₃→PKC 级联发生内吞，导致突触长期减弱——这是 Marr-Albus-Ito 理论的细胞机制，也是小脑运动学习的经典分子基础（尽管 2011 年证据表明其非唯一必要机制）。

## 当前理解

小脑 LTD（PF-PC LTD）是在浦肯野细胞（PC）的平行纤维（PF）突触上发生的长时程抑制。与海马 NMDA-LTD 不同，小脑 LTD **不依赖 NMDA 受体**，而是依赖 **mGluR1（第一型代谢型谷氨酸受体）和 PKCα** 的协同激活，以及攀爬纤维（CF）诱发的大量 Ca²⁺ 内流。

这是 Marr-Albus-Ito 学说的细胞实现：攀爬纤维携带运动误差信号，当误差信号与某一运动命令通道（平行纤维）同时激活浦肯野细胞时，该通道突触权重被降低，从而减少下次重复该运动模式。

然而，Schonewille et al. (2011, PMID:21482355) 证明，三种不同的 AMPAR 内吞阻断突变小鼠仍可正常学习多种运动任务，说明 PF-PC LTD 对运动学习不是唯一必要机制——更广泛的多层可塑性系统（见 [[cerebellum]]）提供了补偿。

## 关键机制

### 分子级联（五步）

1. **PF 激活** → 浦肯野细胞树突 AMPA 受体（快速）+ mGluR1（代谢型，慢速）
2. **CF 激活（同时）** → 复杂放电（complex spike）→ 大量 Ca²⁺ 内流（VGCCs）
3. **mGluR1 激活 + 高 Ca²⁺ 协同**：
   - mGluR1 → Gq → PLCβ → IP₃ + DAG
   - IP₃ → IP₃R 开放 → 内质网额外释放 Ca²⁺
   - DAG + Ca²⁺ → **PKCα/PKCγ 激活**
4. **PKCα 磷酸化 GluA2（Ser880）** → 破坏 GluA2-GRIP 相互作用 → AMPAR 内吞
5. **PF-PC 突触 AMPAR 密度降低** → LTD 完成（持续数小时至数天）

### 与海马 LTD 的关键差异

| 特征 | 小脑 LTD | 海马 NMDA-LTD |
|------|---------|--------------|
| 诱导受体 | mGluR1（代谢型） | NMDA 受体（离子型）|
| 钙来源 | VGCCs + IP₃R（ER） | NMDA 受体 |
| 关键激酶 | PKCα | PP2B/calcineurin（去磷酸化）|
| 时间窗口 | PF + CF 同时（经典：0-100ms；Hansel 2026：可达 400ms） | 突触前后低频同时激活 |
| 功能意义 | 运动误差纠正 | 突触效能下调，遗忘 |

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| mGluR1 是 LTD 诱导必要条件 | mGluR1 KO → LTD 缺失 + 眼睑学习障碍 | PMID:7954803 | 高 |
| PKCα/G 是 LTD 关键激酶 | Gαq 敲除阻断 LTD | PMID:15175381 | 高 |
| 无 PF-LTD 也能运动学习 | 三种 AMPAR 内吞阻断小鼠运动学习正常 | PMID:21482355 | 高 |
| PF-LTD 可由 LTP 反转 | 体外切片双向可塑性 | PMID:17046686 | 中-高 |
| LTD 时间窗口可宽至 400ms（预期性）| 清醒小鼠双光子成像（预印本）| PMID:42079241 | 低（预印本）|
| 颗粒细胞在 2s 时序任务中发展出持续性缓坡放电，攀爬纤维奖励信号不随学习减少 | 小鼠双光子同步记录颗粒细胞+攀爬纤维 | PMID:38870929 (Garcia-Garcia 2024) | 高（Nature，直接电生理）|
| PF-PC LTD 五步分子级联：mGluR1→PKCα→GluA2 Ser880→AMPAR 内吞 | 综述汇总体外和遗传学实验 | PMID:27857688 (Hoxha 2016) | 高（established）|

## 连接

- [[ltd]] — 小脑 LTD 与海马 LTD 是平行的两种长时程抑制机制
- [[cerebellum]] — 小脑回路架构和多层可塑性
- [[forward-model]] — LTD 的功能意义（误差驱动内部模型更新），包括认知域扩展
- [[ampa-receptor]] — AMPAR 内吞是小脑 LTD 和海马 LTD 的共同输出机制
- [[cerebellar-cognitive-affective-syndrome]] — CCAS：小脑 LTD 所在回路受损的临床表现，包括语言/社会认知障碍
- [[interval-timing]] — Garcia-Garcia 2024：颗粒细胞秒级放电为 LTD 提供时序基础，扩展了时间窗口

## 未解问题

- Q-cb-01：攀爬纤维携带的"误差"具体信息编码是什么？
- Q-cb-02：400ms 时间窗口（Hansel 2026）若确认，如何修订 Marr-Albus-Ito 理论？
- Q-cerebellar-cognitive-01：Crus I/II 的认知功能（语言预测、心理理论）是否同样依赖 PF-PC LTD，或有独立可塑性机制？
- Q-cerebellar-cognitive-02：Garcia-Garcia 2024 发现认知时序任务中攀爬纤维信号不减少——这意味着认知情境中攀爬纤维传递的不是"减少型预测误差"，而是什么？

## 修订历史

- 2026-06-23 · 创建 · 基于《小脑的秘密》一文 · 初始置信度：高（分子机制 established）；LTD 非唯一机制也有 established 证据
- 2026-09-03 · 补充 Zang & De Schutter 2019 梯度 CF 信号证据（CF 信号是模拟量而非二值）；新增 purkinje-cell 和 granule-cell-cerebellar 关联页面；整合 Jin & Hull 2025（CF 也携带奖励 rPE）的意义（攀爬纤维"误差"定义需要扩展）· 基于 2026-09-03-purkinje-cell-cerebellar-motor-learning
- 2026-10-04 · 增加 Garcia-Garcia et al. 2024 (PMID:38870929) 关键发现：颗粒细胞可在 2 秒时序任务中发展持续性缓坡放电，攀爬纤维奖励信号不随学习衰减，提示认知情境下 LTD 的时序范围和教师信号性质与运动学习可能不同；补充 Hoxha 2016 (PMID:27857688) 详细分子机制；新增连接至 CCAS 页面和 interval-timing；新增 Q-cerebellar-cognitive-01/02 · 基于 2026-10-04-cerebellum-cognition-language-social

## 来源文章

- [[2026-06-23-cerebellum-motor-prediction]]

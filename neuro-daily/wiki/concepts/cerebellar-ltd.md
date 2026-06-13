---
title: 小脑 LTD（浦肯野细胞平行纤维长时程抑制）
slug: cerebellar-ltd
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-23
updated: 2026-06-13
revision_count: 3
dimensions: [molecular, synaptic, cellular, microcircuit]
related: [ltd, cerebellum, forward-model, climbing-fiber-error-signal, purkinje-cell, parallel-fiber, deep-cerebellar-nuclei, inferior-olive, molecular-layer-interneurons]
prerequisites: [ltd, nmda-receptor, pkc-signaling, ampa-receptor]
opens_questions: [Q-cb-01, Q-cb-02, Q-cb-04, Q-cb-05, Q-cb-06, Q-cb-07, Q-cb-08]
source_articles: [2026-06-23-cerebellum-motor-prediction, 2026-08-01-cerebellar-ltd-purkinje-motor-learning, 2026-06-13-cerebellar-distributed-plasticity-motor-learning]
key_sources: ["PMID:7954803", "PMID:21482355", "PMID:11319554", "PMID:33203932", "PMID:30069835", "PMID:23440175", "PMID:30995136", "PMID:38574161", "PMID:37474638", "PMID:40523942"]
---

# 小脑 LTD（Cerebellar LTD / PF-PC LTD）

> **一句话定义**：当颗粒细胞平行纤维输入与攀爬纤维误差信号在浦肯野细胞树突上同时激活时，该平行纤维突触的 AMPA 受体通过 mGluR1→IP₃→PKC 级联发生内吞，导致突触长期减弱——这是 Marr-Albus-Ito 理论的细胞机制，也是小脑运动学习的经典分子基础（尽管 2011 年证据表明其非唯一必要机制）。

## 当前理解

小脑 LTD（PF-PC LTD）是在浦肯野细胞（PC）的平行纤维（PF）突触上发生的长时程抑制。与海马 NMDA-LTD 不同，小脑 LTD **不依赖 NMDA 受体**，而是依赖 **mGluR1（第一型代谢型谷氨酸受体）和 PKCα** 的协同激活，以及攀爬纤维（CF）诱发的大量 Ca²⁺ 内流。

这是 Marr-Albus-Ito 学说的细胞实现：攀爬纤维携带运动误差信号，当误差信号与某一运动命令通道（平行纤维）同时激活浦肯野细胞时，该通道突触权重被降低，从而减少下次重复该运动模式。

然而，Schonewille et al. (2011, PMID:21482355) 证明，三种不同的 AMPAR 内吞阻断突变小鼠仍可正常学习多种运动任务，说明 PF-PC LTD 对运动学习不是唯一必要机制——更广泛的多层可塑性系统（见 [[cerebellum]]）提供了补偿。

**2024 年更新（Zhu et al., PMID:38574161）**：大规模计算建模研究揭示小脑运动学习（以眼睑条件反射 CEBC 为范式）依赖 PF-PC LTD 与分子层中间神经元（MLI）可塑性的**协同**：PF-MLI 突触在 CF 信号下发生 LTP（与 PF-PC LTD 方向相反），两路并联共同实现浦肯野细胞放电的可靠压低。单独关闭任一位点学习受损有限，同时关闭则显著受损。这从计算角度解释了为何 AMPAR 内吞阻断（Schonewille 2011）不影响学习：MLI 通路提供了实质性补偿。

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
| 无 PF-LTD 也能运动学习 | 三种 AMPAR 内吞阻断小鼠运动学习正常（p > 0.5 vs 野生型） | PMID:21482355 | 高（争议核心） |
| PF-LTD 可由 LTP 反转 | 体外切片双向可塑性 | PMID:17046686 | 中-高 |
| LTD 时间窗口可宽至 400ms（预期性）| 清醒小鼠双光子成像（预印本）| PMID:42079241 | 低（预印本）|
| 绒球最优 PF-CF 配对间隔 ≈ 120ms，匹配视觉反馈延迟 | 绒球体外精确间隔调控实验 | PMID:30069835 | 高 |
| LTD 为快速适应初期机制，DCN LTP 为慢速巩固 | 双相适应时间进程 + 橄榄核可逆失活后记忆保留 | PMID:23440175 | 中 |
| 攀爬纤维复杂放电时序：眼跳后 80–120ms，编码误差大小/方向 | 体内 Purkinje 细胞记录 + SC 刺激（14.4ms 延迟）| PMID:30995136 | 高 |
| PF-PC LTD + PF-MLI LTP 协同支持 CEBC；单位点阻断影响有限，双位点阻断显著受损 | 计算建模（系统性位点关闭实验）| PMID:38574161（2024）| 中（计算模型，需神经记录验证）|
| 激发性核橄榄通路（顶核→IO 谷氨酸能投射）在眼跳中驱动有时序精度的 CF 放电 | 解剖追踪 + 光遗传激活 + 电生理（Nature Neurosci）| PMID:37474638（2023）| 高（顶级期刊，未读全文）|

## 连接

- [[ltd]] — 小脑 LTD 与海马 LTD 是平行的两种长时程抑制机制
- [[cerebellum]] — 小脑回路架构和多层可塑性
- [[forward-model]] — LTD 的功能意义（误差驱动内部模型更新）
- [[ampa-receptor]] — AMPAR 内吞是小脑 LTD 和海马 LTD 的共同输出机制
- [[molecular-layer-interneurons]] — MLI 可塑性（PF-MLI LTP）与 PF-PC LTD 协同，共同支持小脑运动学习
- [[deep-cerebellar-nuclei]] — DCN-LTP 是小脑运动记忆慢速巩固的关键位点
- [[inferior-olive]] — IO 是攀爬纤维的来源；新发现的激发性核橄榄通路使 IO 也可接受 DCN 的激发性反馈

## 未解问题

- Q-cb-01：攀爬纤维携带的"误差"具体信息编码是什么（感觉误差 vs 运动误差）？
- Q-cb-02：400ms 时间窗口（Hansel 2026）若确认，如何修订 Marr-Albus-Ito 理论？
- Q-cb-04（高优先级）：哪些具体学习范式中 LTD 是必要限速步骤？（见 state/unresolved_questions.md）
- Q-cb-05（中优先级）：小脑后叶认知区域（Crus I/II）的学习是否使用相同的 PF-PC LTD 机制？
- Q-cb-06（新，中优先级）：激发性核橄榄通路（顶核→IO 谷氨酸能）与经典抑制性核橄榄通路如何在时间上协调？两者分别在哪些行为中主导？
- Q-cb-07（新，高优先级）：若小脑可通过激发性核橄榄通路自主生成 CF 误差信号（"自教"），这是否意味着小脑实现了某种形式的自监督学习，而非纯粹的外部监督？
- Q-cb-08（新，中优先级）：Nguyen & Person（2025）的 model-free implicit mapping 框架与 Wolpert（1998）内部模型框架是否构成真实的理论分歧？颗粒细胞高维编码在两者中分别扮演什么角色？

## 修订历史

- 2026-06-23 · 创建 · 基于《小脑的秘密》一文 · 初始置信度：高（分子机制 established）；LTD 非唯一机制也有 established 证据
- 2026-08-01 · 修订（rev1→rev2）· 基于《教师信号的困境》（文章#100）· 新增：绒球 120ms 最优窗口（Suvrathan 2018）、攀爬纤维时序量化（Soetedjo 2019）、双相记忆轨迹（Ito 2013）；新增未解问题 Q-cb-04/Q-cb-05；related 新增 climbing-fiber-error-signal/purkinje-cell；key_sources 补充 PMID:30069835/23440175/30995136
- 2026-06-13 · 修订（rev2→rev3）· 基于《小脑运动学习的分布式革命》（文章#186）· 新增：PF-MLI LTP + PF-PC LTD 协同机制（Zhu 2024 计算模型，PMID:38574161）；激发性核橄榄通路（Wang 2023，PMID:37474638）；related 新增 molecular-layer-interneurons/deep-cerebellar-nuclei/inferior-olive；新增未解问题 Q-cb-06/Q-cb-07/Q-cb-08；key_sources 补充三篇新来源

## 来源文章

- [[2026-06-23-cerebellum-motor-prediction]]
- [[2026-08-01-cerebellar-ltd-purkinje-motor-learning]]
- [[2026-06-13-cerebellar-distributed-plasticity-motor-learning]]

---
title: 小脑 LTD（浦肯野细胞平行纤维长时程抑制）
slug: cerebellar-ltd
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-23
updated: 2026-10-08
revision_count: 4
dimensions: [molecular, synaptic, cellular, microcircuit]
related: [ltd, cerebellum, mGluR1, forward-model, climbing-fiber, parallel-fiber, purkinje-cell, granule-cell-cerebellar, inferior-olive, deep-cerebellar-nuclei, ip3-receptor, motor-learning]
prerequisites: [ltd, nmda-receptor, pkc-signaling, ampa-receptor]
opens_questions: [Q-cb-01, Q-cb-02, Q-ltd-01, Q-ltd-02, Q-ltd-03, Q-ltd-04]
source_articles: [2026-06-23-cerebellum-motor-prediction, 2026-09-03-purkinje-cell-cerebellar-motor-learning, 2026-10-04-cerebellum-cognition-language-social, 2026-10-08-cerebellar-ltd-mglur1-pkc]
key_sources: ["PMID:7954803", "PMID:21482355", "PMID:11319554", "PMID:33203932", "PMID:31572132", "PMID:40848722", "PMID:27857688", "PMID:38870929", "PMID:23666089", "PMID:18339599", "PMID:35006439", "PMID:1721243", "PMID:7969468"]
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

### IP₃R1——生物物理"与门"（关键节点，rev4 新增）

**IP₃R1（内质网三磷酸肌醇受体 1 型）是理解 LTD 同时激活要求的关键**：

IP₃R1 的开放活性呈钟形（bell-shaped）Ca²⁺ 依赖曲线：
- **低 Ca²⁺**：轻度激活（IP₃ 单独存在时，ER 释放少量 Ca²⁺）
- **中等 Ca²⁺**（CF 驱动的水平）：激活最旺盛 → ER 额外大量释放 Ca²⁺
- **极高 Ca²⁺**：被抑制（防止过度激活）

因此：
- **仅 PF 激活**：有 IP₃（来自 mGluR1），但缺乏 CF 的 Ca²⁺ 内流 → IP₃R1 激活不足 → PKC 无法被激活 → **不发生 LTD**
- **仅 CF 激活**：有大量 Ca²⁺ 内流，但缺乏 IP₃ → IP₃R1 未被充分激活 → DAG 也缺少 → **不发生 LTD**
- **PF + CF 同时**：IP₃ 浓度升高（PF 侧）+ Ca²⁺ 中等水平（CF 侧）→ IP₃R1 在最佳激活区间开放 → ER 额外释放 Ca²⁺ → 总 Ca²⁺ + DAG 协同激活 PKCα/γ → **LTD 发生**

这就是 LTD 的同时激活要求的生物物理机制：IP₃R1 实现了"必须两路信号同时到达"的逻辑门控。（来源：Hirano 2013 综述，PMID:23666089，开放全文 PMC3722574）

### AMPAR 内吞的分子细节：GRIP1 → PICK1 转换（rev4 新增）

LTD 表达机制中，AMPAR 并非被随机内吞：
1. **非磷酸化态**：GluA2 C 端与 **GRIP1**（谷氨酸受体交互蛋白）结合 → AMPAR 被锚定在突触后密度（PSD）
2. **PKCα 磷酸化 GluA2 Ser880**：GluA2 从 GRIP1 脱离，转向与 **PICK1**（C 激酶相互作用蛋白 1）结合
3. **PICK1 复合体**：使 AMPAR 从"锚定态"进入"可内吞态"，通过**网格蛋白（clathrin）介导**的胞吞从突触膜移走
4. **净效果**：突触膜上 AMPAR 数量减少，相同谷氨酸浓度产生更小的 EPSP → LTD 功能表达

（来源：Hirano 2013 综述，PMID:23666089；Kano et al. 2008，PMID:18339599）

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
| IP₃R1 是 PF+CF 同时激活的"与门"：钟形 Ca²⁺ 依赖曲线决定 LTD 诱导要求 | Hirano 2013 综述汇总，开放全文 PMC3722574 | PMID:23666089 | 高 |
| PKC 激活剂模拟 LTD；PKC 抑制剂阻断 LTD | 培养 PC 药理学实验 | PMID:1721243（Linden & Connor 1991, Science）| 高 |
| mGluR1 KO → 运动协调障碍 + 空间学习缺陷 | 基因敲除小鼠行为学 | PMID:7969468（Conquet 1994, Nature）| 高 |
| 抗 mGluR1/VGCC 自身抗体 → LTD 级联受阻 → 小脑共济失调，免疫治疗改善 | 临床病例 + 免疫组化，LTDpathies 框架 | PMID:35006439（Mitoma 2021，PMC8607360，开放全文）| 中（临床证据，机制间接）|

## 连接

- [[ltd]] — 小脑 LTD 与海马 LTD 是平行的两种长时程抑制机制
- [[cerebellum]] — 小脑回路架构和多层可塑性
- [[forward-model]] — LTD 的功能意义（误差驱动内部模型更新），包括认知域扩展
- [[ampa-receptor]] — AMPAR 内吞是小脑 LTD 和海马 LTD 的共同输出机制
- [[cerebellar-cognitive-affective-syndrome]] — CCAS：小脑 LTD 所在回路受损的临床表现，包括语言/社会认知障碍
- [[interval-timing]] — Garcia-Garcia 2024：颗粒细胞秒级放电为 LTD 提供时序基础，扩展了时间窗口
- [[inferior-olive]] — IO 通过 Cx36 缝隙连接同步化 CF 时序，精度影响 LTD 诱导效率
- [[deep-cerebellar-nuclei]] — DCN 可塑性是 LTD 被阻断时的重要代偿机制之一

## 未解问题

- Q-cb-01：攀爬纤维携带的"误差"具体信息编码是什么？
- Q-cb-02：400ms 时间窗口（Hansel 2026）若确认，如何修订 Marr-Albus-Ito 理论？
- Q-cerebellar-cognitive-01：Crus I/II 的认知功能（语言预测、心理理论）是否同样依赖 PF-PC LTD，或有独立可塑性机制？
- Q-cerebellar-cognitive-02：Garcia-Garcia 2024 发现认知时序任务中攀爬纤维信号不减少——这意味着认知情境中攀爬纤维传递的不是"减少型预测误差"，而是什么？
- **Q-ltd-01**（高优先级）：LTD 被特异性阻断时，哪种补偿机制接管运动学习？不同任务下是否相同？（MLI 可塑性 vs DCN 可塑性 vs PC 内在可塑性）
- **Q-ltd-02**（高优先级）：如何在人类活体内追踪 PF-PC AMPAR 数量变化？目前人类证据只有 LTDpathies 的间接临床数据。
- **Q-ltd-03**（中优先级）：IP₃R1 的 Ca²⁺ 调制曲线是否在不同 PC 亚群（蚓部 vs 外侧小脑）有差异，导致 LTD 诱导阈值在功能区域间不同？
- **Q-ltd-04**（中优先级）：mGluR1 驱动的 2-AG（内源性大麻素）与 LTD 的时空关系——DSE 是 LTD 诱导的前提还是后果？

## 修订历史

- 2026-06-23 · 创建 · 基于《小脑的秘密》一文 · 初始置信度：高（分子机制 established）；LTD 非唯一机制也有 established 证据
- 2026-09-03 · 补充 Zang & De Schutter 2019 梯度 CF 信号证据（CF 信号是模拟量而非二值）；新增 purkinje-cell 和 granule-cell-cerebellar 关联页面；整合 Jin & Hull 2025（CF 也携带奖励 rPE）的意义（攀爬纤维"误差"定义需要扩展）· 基于 2026-09-03-purkinje-cell-cerebellar-motor-learning
- 2026-10-04 · 增加 Garcia-Garcia et al. 2024 (PMID:38870929) 关键发现：颗粒细胞可在 2 秒时序任务中发展持续性缓坡放电，攀爬纤维奖励信号不随学习衰减，提示认知情境下 LTD 的时序范围和教师信号性质与运动学习可能不同；补充 Hoxha 2016 (PMID:27857688) 详细分子机制；新增连接至 CCAS 页面和 interval-timing；新增 Q-cerebellar-cognitive-01/02 · 基于 2026-10-04-cerebellum-cognition-language-social
- 2026-10-08 · 修订 rev3→rev4 · 基于《误差的解剖学：小脑 LTD 如何将"同时激活"转化为突触记忆》（文章 #168）· 新增：(1) IP₃R1 生物物理"与门"机制专节（钟形 Ca²⁺ 调制曲线解释 PF+CF 同时激活要求）；(2) AMPAR 内吞的 GRIP1→PICK1 分子细节专节；(3) 关键证据表新增 IP₃R1、PKC 药理学、Conquet 1994、LTDpathies 条目（Hirano 2013 PMC3722574、Linden 1991 PMID:1721243、Conquet 1994 PMID:7969468、Mitoma 2021 PMC8607360）；(4) 连接新增 inferior-olive、deep-cerebellar-nuclei；(5) 未解问题新增 Q-ltd-01 至 Q-ltd-04；新增 key_sources：PMID:23666089、PMID:18339599、PMID:35006439、PMID:1721243、PMID:7969468

## 来源文章

- [[2026-06-23-cerebellum-motor-prediction]]
- [[2026-09-03-purkinje-cell-cerebellar-motor-learning]]
- [[2026-10-04-cerebellum-cognition-language-social]]
- [[2026-10-08-cerebellar-ltd-mglur1-pkc]]

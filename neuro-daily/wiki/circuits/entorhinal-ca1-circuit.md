---
title: 内嗅皮层-CA1 双流回路
slug: entorhinal-ca1-circuit
domain: circuits
type: mechanism
status: established
confidence: high
created: 2026-09-24
updated: 2026-09-24
revision_count: 1
dimensions: [microcircuit, brain-region, synaptic, cognition, behavior]
related: [entorhinal-cortex, temporoammonic-path, place-cells, btsp, theta-oscillations, schaffer-collateral, ca3-hippocampus, dentate-gyrus, grid-cells, memory-consolidation, lateral-entorhinal-cortex]
prerequisites: [entorhinal-cortex, place-cells, theta-oscillations]
opens_questions: [Q-ec-ca1-01, Q-ec-ca1-02, Q-ec-ca1-03]
source_articles: [2026-09-24-entorhinal-ca1-dual-stream-theta-gate]
key_sources: ["PMID:12077421", "PMID:15965463", "PMID:16237162", "PMID:18215625", "PMID:37816349", "PMID:39253411"]
---

# 内嗅皮层-CA1 双流回路 (Entorhinal-CA1 Dual-Stream Circuit)

> **一句话定义**：内嗅皮层通过两条解剖上分离的平行输入流——EC-III 的直接穿通径路（终止于 CA1 远端树突 SLM）和 EC-II 经 DG→CA3 中继的三突触通路（终止于 CA1 近端树突 SR）——在 theta 振荡的时序框架下向 CA1 传递互补信息；CA1 锥体神经元充当"时序 AND 门"，整合两路输入形成精准的空间和目标表征。

## 当前理解

我们现在认为，CA1 是一个**双流时序整合器**，而非简单的信息汇聚节点：

- **三突触通路**（EC-II → DG → CA3 → CA1 via Schaffer 侧支，终止于 SR）：经过 3 次突触中继，传递联想预测信号；CA3 循环连接完成的模式补全经 Schaffer 侧支输入 CA1；驱动联想回忆能力
- **直接穿通径路（TA path）**（EC-III → CA1 SLM，直接投射）：提供当前感觉情境的精准空间锚定；维持场所场的精准度（Brun et al. 2008）

**关键机制**：CA1 锥体神经元是"时序特异性 AND 门"（Ang et al. 2005）——仅当 Schaffer 侧支先于 TA path 约半个 theta 周期（~40–60 ms）激活时，TA 信号才能穿透到胞体。机制：Schaffer 激活 NMDA 受体（去极化）+ 触发 GABA_B 介导的预突触去抑制（解锁 TA path 谷氨酸释放）。

**MEC vs LEC 的分工**（Bowler & Losonczy 2023，打破传统二分法）：
- **MEC 直接投射（EC-III）**：传递环境/语境地图——位置特异性 + 语境特异性；在环境视觉切换时重映射，奖励位置改变时不重映射
- **LEC 直接投射（EC-III）**：传递目标/奖励地图——也有位置特异性（！）；在奖励位置改变时重映射，环境切换时不重映射；选择性抑制 LEC→CA1 特异性损害新奖励位置学习

**在 BTSP 中的作用**（Dorian et al. 2024 预印本）：
- MEC 输入驱动 CA1 高钙平台事件的触发频率（写入机会）
- LEC 输入决定表征的信息特异性（写入什么内容）

**在长期记忆巩固中的作用**（Remondes & Schuman 2004）：TA path 在学习后约 3 周的巩固窗口内持续向 CA1 传递"复习信号"，支持系统巩固（海马→皮层迁移）。

## 关键机制

### 1. 三突触通路：联想预测流

```
MEC-II/LEC-II → 穿通纤维 → 齿状回（DG）→ 苔状纤维 → CA3 → Schaffer 侧支 → CA1 SR
```

- CA3 循环连接实现模式补全：从部分线索重建完整记忆
- Schaffer 侧支终止于 **stratum radiatum（SR）**，距胞体 100–200 μm（相对近端）
- 在 theta 波谷相位（slow gamma 主导期）激活

### 2. 直接穿通径路（TA path）：当前感觉精准流

```
MEC-III/LEC-III → 颞氨通路（TA path）→ CA1 SLM
```

- 终止于 **stratum lacunosum-moleculare（SLM）**，距胞体 300–400 μm（远端）
- 在 theta 波峰相位（fast gamma 主导期）激活
- 默认状态下被 OA 中间神经元的 GABA_B 预突触抑制，信号被锁死于远端树突

### 3. 时序 AND 门（Ang et al. 2005）

| 条件 | 结果 |
|------|------|
| 仅 Schaffer 激活 | CA1 放电，但缺少当前感觉精准锚定 |
| 仅 TA path 激活 | 信号被 GABA_B 预突触抑制锁死，CA1 不响应 |
| Schaffer 先于 TA ~40–60 ms | AND 门开启：NMDA 去极化 + GABA_B 去抑制，TA 穿透胞体，精准放电 |

### 4. theta 振荡的时序组织

| theta 相位 | 主要 gamma 频段 | 激活的输入 |
|-----------|---------------|----------|
| 波谷（trough） | 30–80 Hz（slow gamma） | CA3 Schaffer 侧支（联想预测） |
| 波峰（peak） | 60–120 Hz（fast gamma） | EC 直接输入 TA path（当前感觉） |

两个输入相差约半个 theta 周期，完美匹配 AND 门时序要求。

### 5. 抑制性协调（Udakis et al. 2020）

PV 中间神经元 LTD + SST 中间神经元 LTP → 动态重排 EC vs CA3 输入相对权重：
- 新环境：EC 权重上调，帮助形成新场所场
- 熟悉环境：CA3 权重上调，加强联想回忆能力

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| CA3 移除后 CA1 仍有场所场（来自 EC 直接输入） | CA3 选择性切断 + 行为测试 | PMID:12077421 | 高 |
| EC-III 损伤→ CA1 场所场变大变散 | MEC-III γ-乙炔基 GABA + CA1/CA3 记录 | PMID:18215625 | 高 |
| CA1 是时序 AND 门（Schaffer 先 TA path ~半 theta） | 离体膜片钳 + GABA_B 操控 | PMID:16237162，PMC:2048747 | 高 |
| MEC 传语境图，LEC 传奖励目标图 | 体内 2P 轴突成像 + DREADDs 抑制 | PMID:37816349，PMC:11490304 | 高（因果） |
| MEC 驱动 BTSP 平台事件频率，LEC 决定信息内容 | 化学遗传抑制 + 2P 钙成像（预印本） | PMID:39253411，PMC:11383060 | 中（预印本） |
| TA path 损伤→3 周后记忆受损（巩固窗口） | TA path 电解毁损 + 水迷宫不同时间点 | PMID:15470431 | 高 |
| theta 波谷=CA3 输入，波峰=EC 直接输入（gamma 分频） | 海马 LFP 分层记录 + 定向连接分析 | PMID:34439925，PMC:8389192 | 中-高 |

## 连接

- [[entorhinal-cortex]] — EC 是双流回路的上游信息源，分为 MEC（层级功能组织）和 LEC（感觉情境整合）
- [[temporoammonic-path]] — TA path 是直接流的解剖实体（EC-III→CA1 SLM）
- [[place-cells]] — 双流整合是 CA1 场所场形成和维持精准度的回路基础
- [[btsp]] — TA path 传递的高钙触发信号（MEC）和内容信号（LEC）共同驱动 BTSP
- [[theta-oscillations]] — theta 振荡提供时序 AND 门所需的两个半周期时序框架
- [[schaffer-collateral]] — CA3 Schaffer 侧支是三突触通路的终末段，提供联想预测输入
- [[memory-consolidation]] — TA path 在巩固窗口内持续传递复习信号，支持系统巩固
- [[grid-cells]] — MEC-II 网格细胞是三突触通路的空间度量输入源
- [[lateral-entorhinal-cortex]] — LEC 作为直接流的目标/奖励内容来源

## 未解问题

- Q-ec-ca1-01（高优先级）：LEC 的位置编码信号来自何处？旁海马回视觉投射、CA1→LEC 反馈回路还是物体-位置联想记忆？
- Q-ec-ca1-02（高优先级）：人类 TA path 是否有相同的 theta 时序 AND 门机制？手术患者的有限电生理数据能否验证？
- Q-ec-ca1-03（中优先级）：TA path 巩固窗口内传递的"复习信号"是什么形式？是睡眠离线重播还是清醒状态的持续监督？与 SWR 的时序关系？

## 修订历史

- 2026-09-24 · 创建 · 基于《时序之门》文章(#154) · 初始置信度：高（综合 11 篇来源，包含 6 篇开放全文）

## 来源文章

- [[2026-09-24-entorhinal-ca1-dual-stream-theta-gate]]

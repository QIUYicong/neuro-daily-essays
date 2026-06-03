---
title: 三方突触
slug: tripartite-synapse
domain: concepts
type: concept
status: mainstream
confidence: high
created: 2026-07-02
updated: 2026-07-02
revision_count: 1
dimensions: [synaptic, cellular, cognition]
related: [astrocyte, gliotransmitter, d-serine, astrocyte-calcium-signaling, ltp, ltd, nmda-receptor, synaptic-transmission]
prerequisites: [synaptic-transmission, nmda-receptor, astrocyte]
opens_questions: [Q-astro-01, Q-astro-02, Q-astro-03]
source_articles: [2026-07-02-astrocyte-tripartite-synapse]
key_sources: ["PMID:10322493", "PMID:20075918", "PMID:34334233"]
---

# 三方突触 (Tripartite Synapse)

> **一句话定义**：Araque 等人 1999 年提出的突触功能单元模型，将传统"两元素"（突触前神经元 + 突触后神经元）扩展为"三元素"——加入紧密包裹突触的星形胶质细胞突起（PAPs）作为主动的第三方功能参与者。

## 当前理解

我们现在认为，经典突触传递的"双方对话"模型是不完整的。在海马和皮层的绝大多数兴奋性突触中，星形胶质细胞的 PAPs 紧贴突触前末梢和突触后树突棘，通过三种主动机制参与突触功能：

1. **感知**：突触活动释放的谷氨酸溢出至突触外，激活 PAPs 上的 mGluR（代谢型谷氨酸受体），触发 Ca²⁺ 信号。
2. **响应**：Ca²⁺ 信号激活下游效应器，导致胶质递质（D-丝氨酸、ATP、谷氨酸）从星形胶质细胞释放。
3. **调控**：胶质递质作用于神经元上的受体，改变突触传递效率和可塑性（LTP/LTD）。

这种双向通讯不是噪声或副产物，而是突触正常功能的**必要条件**：Henneberger et al. 2010 的实验直接证明，阻断单个星形胶质细胞的 Ca²⁺ 信号（切断 D-丝氨酸供给），即可消除其覆盖范围内所有突触的 LTP。

**概念地位**：三方突触是一个**框架**而非单一机制——它提出了一个重新组织关于突触功能知识的方式，而不是对某一特定分子机制的描述。框架内部有许多细节仍在研究中（尤其是胶质递质的精确释放机制）。

## 关键机制

### 双向信号流

**神经元 → 星形胶质细胞**：
- 突触谷氨酸溢出 → mGluR 激活 → IP₃-Ca²⁺ 信号
- 突触 ATP 释放 → P2Y 受体激活 → Ca²⁺ 信号
- 内源大麻素（eCB）逆向扩散 → CB1 受体激活 → Ca²⁺ 信号

**星形胶质细胞 → 神经元**：
- Ca²⁺ 依赖 D-丝氨酸释放 → NMDA 受体协同激动位点 → 调控 LTP 诱导
- ATP/腺苷释放 → A1/P2X 受体 → 突触前抑制或 LTD
- 谷氨酸释放 → 突触外 NMDA/mGluR → 慢内向电流（SIC）

### 空间组织

每个星形胶质细胞通过 PAPs 覆盖约 10 万个突触（啮齿类）或 200 万个突触（人类），形成一个**局部功能域**。同一域内的突触接受来自同一星形胶质细胞的 D-丝氨酸信号，这意味着不同突触的 LTP 准入资格存在局部相关性。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 星形胶质细胞主动参与突触传递（三方突触概念） | 早期体外实验 + 综述整合 | PMID:10322493 | 中-高（概念综述） |
| 星形胶质细胞 D-丝氨酸是 LTP 的必要条件 | 单细胞 Ca²⁺ 钳制实验 | PMID:20075918 | 高（Nature 原始研究） |
| 星形胶质细胞参与多类型 LTD | IP3R KO + 行为学 | PMID:34334233 | 中-高（综述汇总） |

## 连接

- [[astrocyte]] — 三方突触的第三方成员
- [[d-serine]] — 最关键的胶质递质，决定 NMDA 受体激活
- [[gliotransmitter]] — 三方突触通讯的胶质侧信号分子
- [[astrocyte-calcium-signaling]] — 三方突触中星形胶质细胞感知和响应突触活动的核心机制
- [[ltp]] — 三方突触对 LTP 的必要性已有因果证据
- [[ltd]] — 三方突触对多种 LTD 机制的参与
- [[nmda-receptor]] — 三方突触通过 D-丝氨酸调控 NMDA 受体功能

## 未解问题

- Q-astro-01：胶质递质的精确物理释放机制
- Q-astro-03：人类三方突触与啮齿类的功能同质性

## 修订历史

- 2026-07-02 · 创建 · 基于《大脑的第三方》(#68) · 初始置信度：高（概念层面；机制细节部分有争议）

## 来源文章

- [[2026-07-02-astrocyte-tripartite-synapse]]

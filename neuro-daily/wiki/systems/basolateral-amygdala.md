---
title: 杏仁核基底外侧群（BLA）
slug: basolateral-amygdala
domain: systems
type: region
status: established
confidence: high
created: 2026-06-14
updated: 2026-06-14
revision_count: 1
dimensions: [microcircuit, brain-region, behavior, cognition]
related: [fear-conditioning, fear-extinction, ltp, engram-cells, hippocampal-circuit, prefrontal-cortex, dopamine-reward-prediction-error, memory-consolidation]
prerequisites: [ltp, nmda-receptor, pv-interneurons, sst-interneurons]
opens_questions: [Q-fear-temporal-gap, Q-itc-plasticity]
source_articles: [2026-06-14-amygdala-fear-circuit]
key_sources: ["PMID:10845062", "PMID:32047613", "PMID:20303254"]
---

# 杏仁核基底外侧群 (Basolateral Amygdala, BLA)

> **一句话定义**：BLA 是恐惧记忆形成（侧核 LA）、整合（基底核 BA）与表达（中央核 CeM）的核心回路节点，通过 NMDA-LTP 在 LA 将 CS 与 US 永久联结，并经前额叶和嵌合细胞群调控恐惧表达与消退。

## 当前理解

我们现在认为，杏仁核基底外侧群（BLA）是负责**威胁学习**的专用回路枢纽。BLA 不是一个均质结构，而是至少三个功能不同的核团的集合：

- **侧核（Lateral Nucleus, LA）**：CS（条件刺激，如音调）和 US（非条件刺激，如电击）的突触汇聚点；NMDA 受体依赖的 LTP 在此记录 CS-危险联结；约 10%–20% 的 LA 主细胞通过 CREB 竞争被纳入恐惧印迹（engram）。
- **基底核（Basal Nucleus, BA）**：整合恐惧信息与情境、奖励历史；投射到 CeM（驱动恐惧输出）、伏隔核（NAc，动机）和 PFC（认知调控）。
- **中央核（Central Nucleus, CeA）**：恐惧的输出台；CeM 神经元投射到下丘脑（压力激素）、PAG（冻结）和蓝斑（NE 唤醒）。

BLA 内约 20% 为 GABAergic 中间神经元，以 PV+ 和 SST+ 为主。PV+ 靶向主细胞的胞体/AIS，控制输出时序；SST+ 靶向远端树突，调控树突整合。CS 期间 PV 激活→抑制 SST→去抑制主细胞树突，是 LA 处理 CS 的关键去抑制机制。

BLA 还包含**嵌合细胞群（ITC cells）**——散布在 BLA 与 CeA 之间的 GABAergic 节点，接受来自 IL-PFC 的兴奋性输入后，抑制 CeM 的输出神经元，是恐惧消退的关键门禁。

## 关键机制

### 恐惧获得（LA 层面）
1. CS（听觉）→ 听觉丘脑（MGN）+ 听觉皮层 → LA 主细胞 AMPA 受体（快速 EPSP）
2. US（电击）→ 臂旁核（PBN）+ 躯体感觉皮层 → LA 主细胞（强去极化）
3. CS + US 同时激活 → NMDA 受体 Mg²⁺ 解阻 → Ca²⁺ 内流 → CaMKII → GluA1 磷酸化 + AMPA 受体插入 → LA-LTP
4. CREB 分配竞争：训练前兴奋性较高（CREB 活性高）的 LA 主细胞被优先纳入印迹

### 恐惧表达（LA→BA→CeM 路径）
- LA 印迹细胞（CS 响应增强）→ BA → CeM → 下丘脑/PAG/LC → 压力激素/冻结/唤醒

### 消退门控（ITC 路径）
- IL-PFC → ITC cells（GABAergic）→ 抑制 CeM → 恐惧输出被压制（见 [[fear-extinction]]）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| LA 损毁消除条件性恐惧 | 刻板电解损毁 + 行为测试 | PMID:10845062 (LeDoux 2000) | 高 |
| 恐惧条件反射后 LA 场电位增强（LTP 样） | 体内听觉诱发场电位记录 | PMID:9403688 (Rogan 1997) | 高 |
| 恐惧条件反射后 AMPA:NMDA 比值升高 | 离体全细胞膜片钳 | PMID:9403689 (McKernan 1997) | 高 |
| BLA 内 NMDA 拮抗剂阻断恐惧获得 | 立体定向注射 AP5 + 行为测试 | PMID:10542437 (Maren 1999) | 高 |
| CS 期间 PV 激活→SST 抑制→去抑制窗口 | 体内钙成像 + 光遗传 | PMID:29197563 (Lucas 2018) | 中 |
| ITC 损毁影响消退（非获得） | 立体定向毒素损毁 | PMID:20303254 (Sotres-Bayon 2010) | 中高 |

## 连接

- [[fear-conditioning]] — BLA 是恐惧条件反射发生的解剖位点
- [[fear-extinction]] — ITC 细胞是消退门控的关键结构，IL-PFC 经此抑制 CeM
- [[ltp]] — 恐惧学习的分子机制（LA-LTP）是 Hebbian LTP 在情绪系统的实例
- [[engram-cells]] — CREB 竞争决定 LA 印迹细胞分配
- [[nmda-receptor]] — NMDA 受体巧合检测实现 CS-US 联结
- [[pv-interneurons]] — PV 在 BLA 控制 CS 处理和去抑制
- [[sst-interneurons]] — SST 靶向 LA 主细胞远端树突，被 PV 抑制实现去抑制
- [[prefrontal-cortex]] — IL-PFC（→ITC→CeM）vs PL-PFC（→BA→CeM）双模控制
- [[hippocampal-circuit]] — 海马提供情境信息给 vHipp→mPFC 通路，门控恐惧/消退表达
- [[norepinephrine-locus-coeruleus]] — 情绪应激下 LC-NE 通过 β 受体增强 BLA-LTP，强化情绪记忆

## 未解问题

- Q-fear-temporal-gap：标准 CS 持续 30 s，US 在最后 0.5 s，LA 对 CS 在几百 ms 内就适应；如何在 CS 偏移后实现 NMDA 受体参与的 CS-US 联结？
- Q-itc-plasticity：ITC 细胞接收 IL-PFC 输入的突触可塑性机制（是否也是 NMDA-LTP？）
- Q-extinction-ltp-ltd：消退后 LA 是否存在部分 AMPA 受体内吞（LTD），或完全是新联结？

## 修订历史

- 2026-06-14 · 创建 · 基于《杏仁核的恐惧算法》一文 · 初始置信度：高

## 来源文章

- [[2026-06-14-amygdala-fear-circuit]]

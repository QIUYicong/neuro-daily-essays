---
title: SST+ 中间神经元（生长抑素阳性中间神经元）
slug: sst-interneurons
domain: circuits
type: entity
status: established
confidence: high
created: 2026-06-03
updated: 2026-06-03
revision_count: 1
dimensions: [cellular, synaptic, microcircuit]
related: [pv-interneurons, vip-interneurons, disinhibitory-circuit, dendritic-computation, theta-oscillations, hippocampal-circuit, place-cell, ltp, btsp]
prerequisites: [synaptic-transmission, dendritic-computation, nmda-receptor]
opens_questions: [Q-sst-dendritic-spike-gate, Q-olm-theta-function]
source_articles: [2026-06-03-inhibitory-interneuron-diversity]
key_sources: ["PMID:27477017", "PMID:18599766", "PMID:24429630"]
---

# SST+ 中间神经元（Somatostatin-expressing Interneurons）

> **一句话定义**：以生长抑素（SST）为标记、靶向锥体细胞远端树突的 GABA 能中间神经元，通过易化性反馈和顶端树突门控，调控皮层 top-down 输入的整合与树突非线性计算。

## 当前理解

我们现在认为，SST+ 中间神经元约占皮层 GABA 能神经元的 30%，发育自 MGE（受 Nkx2.1 调控），但分化方向与 PV+ 细胞不同。它们的核心特征是**靶向树突而非胞体**，以及接受来自锥体细胞的**强烈易化（strongly facilitating）**兴奋性输入。

最典型的亚类是**Martinotti 细胞**：胞体位于 L2/3 或 L5/6，轴突向上穿越多层，在 L1 形成广泛的水平轴突丛，靶向锥体细胞的顶端树突簇（apical tuft）。其他 SST+ 亚类（如双层纹状体细胞）则靶向基底和斜向树突。

SST+ 细胞是**活跃锥体细胞的反馈抑制器**：当锥体细胞高频放电时，传来的兴奋性突触电流在 SST+ 细胞处不衰减反而增强（短时程易化），甚至"单次高频爆发就能激活 SST+ 细胞"（Tremblay et al., 2016, PMID:27477017）。这意味着 SST+ 细胞被动态地绑定到活跃锥体细胞上，形成精确的**侧向抑制和顶端树突抑制**。

在海马中，O-LM 细胞（oriens-lacunosum moleculare）是 SST+ 的重要亚型，靶向内嗅皮层→CA1 的输入区（SLM），在 θ 振荡期间非常活跃，实现对"新皮层 top-down 信息"的时相门控。

## 关键机制

**突触特性（短时程易化）**：
- SST+ 细胞接受的锥体细胞→SST+ 突触具有强烈短时程易化（STP-facilitation）
- 效应：低频（单次）刺激几乎不激活 SST+ 细胞；高频（θ 爆发）刺激则强力激活
- 这使 SST+ 细胞充当"忙碌程度探测器"——只有持续高活跃的锥体细胞才能驱动 SST+ 抑制

**树突靶标（Martinotti）**：
- 顶端树突簇（L1 区域）：接受来自高层皮层区域的 top-down 反馈，以及来自内嗅皮层的信号
- Martinotti 细胞在此处的抑制，直接调控**Ca²⁺ 棘波**（Ca²⁺ spikes）的触发阈值
- 通过抑制 Ca²⁺ 棘波，SST+ 细胞实质上控制了**树突计算（dendritic computation）**的非线性程度

**O-LM 细胞的 θ 期功能**：
- 海马 CA1 的 O-LM 细胞胞体在 stratum oriens（近端），轴突终止于 SLM（内嗅皮层输入区）
- 在 θ 振荡期间，O-LM 细胞在特定相位强放电，压制内嗅皮层输入
- 这创造了一个"时间窗口"效应：θ 的不同相位分别允许/禁止 EC 输入进入 CA1

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| SST+ 细胞接受强烈易化性兴奋输入（单次高频爆发即可激活）| 双细胞膜片钳 | PMID:27477017 | 高 |
| Martinotti 细胞轴突在 L1 形成水平丛，靶向顶端树突 | 神经元形态重建 | PMID:27477017 | 高 |
| O-LM 细胞在 θ 期间放电活跃，靶向内嗅皮层输入区 | 清醒大鼠 CA1 体内记录 | PMID:18599766 | 高 |
| O-LM 细胞在 SWR 期间被压制（O-LM firing suppressed）| 清醒大鼠 CA1 体内记录 | PMID:18599766 | 高 |
| SST+ 约占皮层 GABA 能神经元 30% | 分子标记 + 细胞计数 | PMID:21154909 | 高 |

## 连接

- [[pv-interneurons]] — 并列的 MGE 来源抑制性家族；PV 靶向胞体，SST 靶向树突
- [[vip-interneurons]] — VIP+ 主要靶向 SST+ 进行抑制（去抑制回路的关键一环）
- [[disinhibitory-circuit]] — VIP→SST→锥体细胞的门控架构
- [[dendritic-computation]] — SST+ 细胞通过抑制顶端树突调控 Ca²⁺ 棘波和 NMDA 棘波的阈值
- [[theta-oscillations]] — O-LM 细胞（SST+ 亚类）在 θ 期间活跃，门控 EC 输入
- [[hippocampal-circuit]] — O-LM 细胞、bistratified 细胞是海马主要 SST+ 类型
- [[btsp]] — SST+ 抑制可能调控 BTSP 所需钙平台电位的阈值

## 未解问题

- Q-sst-dendritic-spike-gate：SST+ 细胞在体内如何精确调控 NMDA 棘波和 Ca²⁺ 棘波的发生阈值？不同强度的 top-down 信号如何调制 Martinotti 细胞活动？
- Q-olm-theta-function：O-LM 细胞在 θ 期间究竟是"允许 EC 输入进入"还是"压制 EC 输入"？其精确的时相关系（门控窗口在 θ 的哪个相位）尚需澄清。

## 修订历史

- 2026-06-03 · 创建 · 基于《回路中的少数精锐》一文 · 初始置信度：高

## 来源文章

- [[2026-06-03-inhibitory-interneuron-diversity]]

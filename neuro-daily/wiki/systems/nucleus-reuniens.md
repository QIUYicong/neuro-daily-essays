---
title: 丘脑中缝核
slug: nucleus-reuniens
domain: systems
type: structure
status: emerging
confidence: medium
created: 2026-08-31
updated: 2026-08-31
revision_count: 1
dimensions: [brain-region, microcircuit, whole-brain-network, cognition]
related: [hippocampal-prefrontal-coupling, thalamus, working-memory, theta-oscillations, hippocampal-circuit, prefrontal-cortex]
prerequisites: [thalamus, hippocampal-circuit, prefrontal-cortex]
opens_questions: [Q-hpfc-03]
source_articles: [2026-08-31-hippocampal-prefrontal-theta-coupling]
key_sources: ["PMID:25805977", "PMID:28420200"]
---

# 丘脑中缝核 (Nucleus Reuniens, NRe)

> **一句话定义**：丘脑腹侧中线核群中最大的核团，是迄今发现的唯一能同时向海马 CA1（stratum lacunosum-moleculare）和内侧前额叶皮层（mPFC）双向投射的丘脑结构，是 HPC-mPFC 双向三角回路的不可缺少枢纽。

## 当前理解

我们现在认为，丘脑中缝核（NRe）不是经典感觉丘脑核那样的"单向中继站"，而是一个**双向协调者**，使海马和前额叶皮层能够建立比单纯直接投射更复杂的反馈回路。

NRe 的核心特点：
- **解剖位置**：丘脑腹侧中线，与丰圆核（Rhomboid nucleus, Rh）相邻
- **输入**：来自 mPFC（PL/IL）、vHPC（subiculum 和 CA1）、脑干（VTA、LC、Raphe）
- **输出**：→ CA1 stratum lacunosum-moleculare（SLM），同时→ mPFC 各层
- **功能位置**：HPC-mPFC 三角回路的第三顶点

NRe 在工作记忆中的功能证据来自 Griffin（2015, PMID:25805977）的综述和 Wirt & Hyman（2017, PMID:28420200）的实验：选择性抑制 NRe 破坏需要 HPC-mPFC 协作的工作记忆任务（如延迟交替，依赖空间位置记忆），但不影响只依赖单一脑区的任务。

## 关键机制

### NRe 在三角回路中的角色

```
vHPC (CA1/Sub) ──单突触──→ mPFC (PL/IL)
      ↑                           │
      └─── NRe ←─────────────────┘
```

三角回路的功能解读：
1. **mPFC→NRe→CA1**：这是前额叶的"查询指令"路径——mPFC 可以通过 NRe 激活 CA1 SLM，调节哪些海马神经元在下一个 theta 周期内放电
2. **HPC→NRe→mPFC**：补充的海马→丘脑→前额叶路径（与直接 CA1→mPFC 路径并行）
3. NRe 的双向性使 HPC-mPFC 成为持续**协商**（bidirectional negotiation）而非单向提取

### 细胞特性

NRe 内部多数是谷氨酸能兴奋性投射神经元，少量 GABA 能中间神经元。其投射到 CA1 SLM 的纤维与内嗅皮层→CA1 的通路在同一层终止，意味着 NRe 和内嗅皮层在 CA1 SLM 产生竞争性输入（前额叶"选题"与内嗅皮层"感觉输入"在此争夺 CA1 注意力）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| NRe 双侧抑制破坏 HPC-mPFC 依赖性工作记忆 | 药理学（muscimol）选择性失活，行为测试 | PMID:25805977（综述）| 中（多数证据来自综述，原始实验散布多篇）|
| NRe 抑制同时降低 theta 同步和工作记忆 | NRe 光遗传 + LFP 记录 + 行为 | PMID:28420200（全文）| 中-高 |
| mPFC→NRe→CA1 路径存在 | 解剖追踪（anterograde/retrograde）| PMID:25805977（综述）| 高（解剖证据可靠）|

## 连接

- [[hippocampal-prefrontal-coupling]] — NRe 是这一耦合的三角回路枢纽
- [[thalamus]] — NRe 属于丘脑腹侧中线核群
- [[hippocampal-circuit]] — NRe 投射到 CA1 SLM
- [[working-memory]] — NRe 对 HPC-mPFC 协作的工作记忆是必要的
- [[theta-oscillations]] — NRe 参与调节 HPC-mPFC theta 同步

## 未解问题

- **Q-hpfc-03**（中）：NRe 内部神经元亚型（兴奋性 vs 抑制性）在不同任务阶段的时序分工？
- NRe 功能是"门控器"（选择性放行某些时刻的海马信号）还是"整合器"（混合多个来源）？
- NRe 在睡眠中（SWR-纺锤波协调）是否也发挥协调作用？

## 修订历史

- 2026-08-31 · 创建 · 基于《海马与前额叶的 theta 对话》（文章 #131）· 初始置信度：中（解剖证据可靠，功能证据尚在积累，人类直接证据缺乏）

## 来源文章

- [[2026-08-31-hippocampal-prefrontal-theta-coupling]]

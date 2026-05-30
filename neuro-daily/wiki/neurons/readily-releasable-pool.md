---
title: 就绪释放池（RRP）
slug: readily-releasable-pool
domain: neurons
type: structure
status: established
confidence: high
created: 2026-06-10
updated: 2026-06-10
revision_count: 1
dimensions: [molecular, synaptic]
related: [short-term-synaptic-plasticity, active-zone, synaptic-transmission, SNARE-complex, synaptotagmin, voltage-gated-calcium-channels]
prerequisites: [active-zone, synaptic-transmission, SNARE-complex]
opens_questions: []
source_articles: [2026-06-10-stp-short-term-plasticity]
key_sources: ["PMID:11826273", "PMID:22751149"]
---

# 就绪释放池（Readily Releasable Pool, RRP）

> **一句话定义**：就绪释放池是突触活动区中处于停靠（docked）且就绪（primed）状态的突触囊泡子集，可以被单个动作电位触发的Ca²⁺立刻融合，其大小和补充速率是决定突触抑制深度和恢复时间的关键参数。

## 当前理解

我们现在认为，突触囊泡池并非均一群体，而是按功能状态分层的：

1. **就绪释放池（RRP）**：停靠在活动区释放位点并处于就绪状态的囊泡（通常3–30个/突触），可被单个动作电位立刻融合
2. **储备池（Reserve Pool）**：尚未到达释放位点的囊泡，需要时间（数百毫秒至数秒）转入RRP
3. **再循环池（Recycling Pool）**：新近内吞的空囊泡正在重装填神经递质

RRP是决定突触瞬时释放能力的物理约束，也是**短时程突触抑制的主要机制**：高频放电使囊泡释放速度超过储备池补充速度，RRP暂时耗竭，每次动作电位的输出减小。

## 关键机制

### RRP的大小决定因素

- **停靠**（docking）：囊泡通过Rab3-RIM复合体靠近钙通道，形成"停靠-就绪"构象
- **就绪**（priming）：Munc13和Munc18-1促进SNARE复合体的N端预组装，使囊泡处于可被Ca²⁺立刻触发的就绪状态
- **维持**：ATPase（NSF/α-SNAP）持续拆装SNARE，维持就绪池的动态平衡

### RRP的补充速率

不受刺激时，储备池到RRP的补充速率：约数百毫秒至数秒（不同突触差异大）

**钙加速补充**：高频刺激期间胞内钙升高，通过钙/钙调蛋白信号加速RRP补充，最高达**10倍**（Regehr 2012, PMID:22751149）。这是突触在高频输入下保留部分传递能力的关键机制。

### RRP耗竭与突触抑制

数学模型（Zucker & Regehr 2002, PMID:11826273）：
- 设释放概率 p，RRP大小为 N
- 每次动作电位释放 p × N 个囊泡
- 第一个响应幅度 ∝ p × N
- 第二个响应幅度 ∝ p × (N - p×N) = p × N × (1-p)
- 抑制程度 = p（释放比例）

预测：高p突触（p→1）产生强烈抑制，低p突触（p→0）几乎无抑制。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| RRP耗竭是突触抑制的主要机制 | 神经肌肉接头、海马、calyx of Held等多系统统计分析 | PMID:11826273 | 高 |
| 钙依赖加速RRP补充 | calyx of Held钙成像+电生理；加速达10倍 | PMID:22751149 | 高 |
| RRP包含3–30个囊泡/突触 | 超微结构计数 + 统计电生理 | PMID:11826273 | 中-高 |

## 连接

- [[short-term-synaptic-plasticity]] — RRP耗竭是STP抑制的主要机制；RRP补充速率决定抑制后的恢复动力学
- [[active-zone]] — RRP囊泡停靠在活动区的专用释放位点上；活动区蛋白（RIM、Munc13）维持RRP
- [[synaptic-transmission]] — RRP大小和p值共同决定突触响应的幅度
- [[SNARE-complex]] — SNARE的就绪状态（N端预组装）定义了单个囊泡的"就绪"状态
- [[synaptotagmin]] — Syt1感知Ca²⁺后触发RRP中就绪囊泡的融合

## 未解问题

- RRP的精确超微结构定义（形态学"停靠"与功能学"就绪"是否完全重叠？）
- 不同突触类型RRP大小的决定因素
- 慢性活动变化如何稳态性地调节RRP大小（稳态可塑性）

## 修订历史

- 2026-06-10 · 创建 · 基于《瞬息之变：短时程突触可塑性》一文 · 填补STP抑制机制的结构性节点 · 初始置信度：高

## 来源文章

- [[2026-06-10-stp-short-term-plasticity]]

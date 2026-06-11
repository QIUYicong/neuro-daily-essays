---
title: 相位锁定（Phase Locking）
slug: phase-locking
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-18
updated: 2026-07-18
revision_count: 1
dimensions: [cellular, synaptic, brain-region]
related: [tonotopy, ribbon-synapse, auditory-cortex, theta-phase-precession, temporal-coding-hierarchy]
prerequisites: [action-potential, ribbon-synapse, tonotopy]
opens_questions: [Q-aud-01]
source_articles: [2026-07-18-auditory-cortex-tonotopy-dual-coding]
key_sources: ["PMID:33644871", "PMID:37800695"]
---

# 相位锁定（Phase Locking）

> **一句话定义**：听神经纤维（螺旋神经节神经元，SGN）的放电时刻与声波周期的特定相位精确同步的现象；有效范围约<3 kHz，为低频声音提供"时间精细结构（TFS）"编码，补充基底膜位置编码（tonotopy）在频率分辨率上的不足。

## 当前理解

我们现在认为，相位锁定（phase locking）是听觉系统频率编码的两套正交策略之一（另一套是基底膜tonotopy的位置编码）。两套策略分工不同：位置编码覆盖全频率范围（20–20,000 Hz），频率分辨率约1/3倍频程（被动）到更高（OHC放大后）；相位锁定仅在低频有效（<~3 kHz），但可提供Hz级频率分辨率，是人类精细音高辨别的主要机制。

相位锁定不要求每个声波周期都放电（放电率受限于不应期），而是要求**当SGN放电时，其时刻集中在声波周期的某一特定相位**（通常是压力上升段）。多个SGN的时刻直方图（phase histogram）呈现明显的相位特异性峰，同步矢量（synchrony vector）远离随机分布中心，可定量为同步度（VS, vector strength）。

相位锁定的物理上限由**内毛细胞膜时常数（0.2–1 ms）**决定：高频信号（>1–2 kHz）被IHC膜的RC低通特性衰减，使受体电位振幅变小，导致囊泡释放的周期性减弱，SGN放电随机化——位置编码成为唯一依据。

## 关键机制

**生理基础**：
- IHC受体电位对低频刺激（<3 kHz）保留明显的正弦成分（AC电位）
- AC成分导致CaV1.3钙通道在每个声波压力上升相优先开放→囊泡释放偏向该相位
- SGN放电时刻在该相位聚集→产生相位锁定

**频率限制的物理机制**：
- IHC膜时常数（τ = R×C）决定低通截止频率：τ~0.2–1 ms对应fc~160 Hz–800 Hz（理论低通）
- 实际上相位锁定延伸到~3 kHz，因为非线性整流（IHC的静息电位约–45 mV，接近MET通道半激活点）使受体电位不对称，AC成分可保留较小振幅到更高频率

**人类心理物理学限制**：
- 音高感知的TFS贡献在~1.5 kHz以上逐渐减弱（心理物理学研究范围争论于PMC6524635）
- 空间听觉（ITD利用）的TFS使用上限约为~1.3–1.5 kHz

**时间精细结构 vs 时间包络**：
- TFS：声波周期内的精细振荡信息（<3 kHz）；相位锁定携带
- 包络（Temporal Envelope）：信号调幅的缓慢变化（通常<50 Hz）；高频声音也能相位锁定于包络（如经AM调制的4 kHz）
- 两者被不同神经机制利用：TFS用于精细音调识别和声源定位；包络用于语音可懂度（关键的4–16 Hz语音节律）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| SGN放电与声波相位同步（相位锁定存在） | 听神经纤维单单元记录，相位直方图分析 | 经典文献（Rose et al. 1967 Cold Spring Harbor Symp）| 高（极度确立） |
| 相位锁定上限~3 kHz | 多物种听神经纤维记录，同步度 vs 频率曲线 | 多个经典实验室（猫、大鼠、豚鼠） | 高 |
| IHC膜时常数是高频锁定的物理限制 | 全细胞膜片钳测量IHC时常数；理论计算截止频率 | PMID:33644871 | 中-高 |
| 带状突触亚毫秒延迟使低频TFS编码成为可能 | IHC+SGN联合记录，突触延迟测量 | PMID:33644871 | 高 |
| TFS对精细音高识别至关重要（人工耳蜗验证） | CI患者（无TFS）与正常听者音高辨别力对比 | 多项临床研究 | 高 |

## 连接

- [[tonotopy]] — 两套并行频率编码策略（位置 vs 时间）；相位锁定补充tonotopy在精细频率分辨上的不足
- [[ribbon-synapse]] — 带状突触的亚毫秒延迟是SGN相位锁定精确性的突触基础
- [[auditory-cortex]] — A1等频率条带内的时序调谐单元可能整合上行相位锁定信息
- [[theta-phase-precession]] — 两者都是"放电时刻携带信息"的时间编码原理，发生在不同系统（听觉 vs 海马）和时间尺度（微秒–毫秒 vs 秒）
- [[temporal-coding-hierarchy]] — 相位锁定是时间编码层级中微秒–毫秒尺度的代表实例

## 未解问题

- Q-aud-01：人类相位锁定的确切上频限（1.5 kHz vs 3 kHz vs 5 kHz的争论）；神经生理学（猫<4 kHz）与心理物理学（人<1.5 kHz?）数据间的差异原因

## 修订历史

- 2026-07-18 · 创建 · 基于《大脑如何读懂音调》文章 #86 · 初始置信度：高 · 含IHC膜时常数机制（Rutherford 2021）、TFS vs 包络区分、AI耳蜗对比

## 来源文章

- [[2026-07-18-auditory-cortex-tonotopy-dual-coding]]

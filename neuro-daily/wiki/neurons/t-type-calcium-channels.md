---
title: T 型钙通道（低电压激活钙通道）
slug: t-type-calcium-channels
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-06-30
updated: 2026-06-30
revision_count: 1
dimensions: [molecular, cellular, synaptic]
related: [thalamic-firing-modes, voltage-gated-calcium-channels, voltage-gated-sodium-channel, sleep-spindles, action-potential]
prerequisites: [membrane-potential, action-potential, voltage-gated-calcium-channels]
opens_questions: []
source_articles: [2026-06-30-thalamic-burst-t-type-calcium-timing-gate]
key_sources: ["PMID:35803270", "PMID:24285899", "PMID:17168743", "PMID:40966082"]
---

# T 型钙通道（低电压激活钙通道）(T-type / Low-Voltage-Activated Calcium Channels, CaV3)

> **一句话定义**：T 型钙通道（CaV3 家族）是在 –65 至 –55 mV 即可激活的低电压钙通道，在视丘中继神经元（CaV3.1）和视丘网状核（CaV3.3）中高度表达，是视丘爆发放电的分子开关，同时参与 NREM 睡眠纺锤波、失神癫痫发作和感觉适应等生理与病理过程。

## 当前理解

我们现在认为，T 型钙通道（transient type，因其电流短暂快速而得名）是神经元兴奋性状态的关键分子调节器，尤其在视丘中具有独特的"双模式开关"功能。

与高电压激活钙通道（HVA：L型/N型/P/Q型/R型）不同，T 型通道激活阈值极低，使其能够在相对超极化的膜电位（约 –65 mV）附近触发。但 T 型通道也极易失活——在静息膜电位（约 –65 mV）附近长期停留时，通道处于**失活态**，需要先超极化至 –75 mV 以下 ≥50 ms 才能"去失活"（复位），之后才能再次激活。

这种失活-去失活的电压依赖性使 T 型通道成为**超极化检测器**：只有先经历超极化充电，才能在随后的去极化时触发低阈棘波（LTS），继而驱动爆发放电。

**CaV3 亚型分布**：
- **CaV3.1（α1G）**：主要在视丘中继神经元（TC cells）中高密度表达（LGN、VPM、VPL、MGN 等感觉核）；参与感觉门控的爆发-强直切换和前向抑制机制。
- **CaV3.3（α1I）**：主要在视丘网状核（TRN）神经元中表达；TRN 的 CaV3.3 参与纺锤波起搏（TRN 的爆发-抑制-爆发振荡），间接为 TC 神经元提供超极化输入。
- **CaV3.2（α1H）**：在视丘相对少见，但在背角/丘脑痛觉核中有表达，与慢性痛觉过敏相关。

## 关键机制

### 低阈棘波（LTS）的产生

T 型钙通道被激活后，产生约 20–40 ms 的慢速去极化包络（低阈棘波），其幅度足以超过钠棘波阈值，因此在 LTS 顶端叠加 2–7 个快速钠棘波（频率约 200–400 Hz），形成完整的爆发。LTS 之后 T 型通道再次失活，整个爆发历时约 20–30 ms 后自然终止。

### 失活-去失活动力学

| 状态 | 膜电位范围 | 条件 | 结果 |
|------|-----------|------|------|
| 失活 | 约 –65 mV（静息）持续存在 | 无法响应去极化 | 强直模式 |
| 去失活（复位） | 超极化至 < –75 mV，持续 ≥50 ms | T 通道复位为可激活关闭态 | 爆发条件具备 |
| 激活 | 去极化（回弹或主动刺激） | T 电流触发 LTS → 爆发 | 爆发模式 |

### 与 h 电流的协同

超极化激活的 HCN 通道（产生内向 h 电流，I_h）与 T 型通道协同：超极化激活 I_h → 缓慢去极化回弹 → 自动触发已去失活的 T 型通道 → LTS → 爆发。这种 I_h + I_T 的联合构成自发振荡基础，在 NREM 睡眠纺锤波和失神癫痫 3 Hz 棘-慢波中均可见。

### 病理情景：失神癫痫

T 型钙通道（主要 CaV3.1）的功能增强（突变、代偿性上调）是失神癫痫（absence seizures）的分子基础之一。

Cheong 等（2009）发现：PLCβ4 敲除导致视丘 TC 神经元偏向爆发放电，产生自发 3 Hz 棘-慢波放电（SWD），表现为失神癫痫；向视丘内注射 T 型（非 L 型）钙通道阻断剂可有效抑制 SWD（PMID:19955421）。

### 疾病窗口：脆性 X 综合征

O'Shea 等（2025）在 Fmr1 KO 小鼠（脆性 X 模型）中发现，视丘 T 型 Ca²⁺ 电流在超极化膜电位下显著减小（PMID:40966082），导致爆发放电受损、强直模式占主导。研究者假设这可能与脆性 X 的感觉超敏感症状相关——缺乏正常爆发的时序门控，皮层接受的是非压缩的持续感觉输入流。（注：单一研究，临床相关性尚未在人类患者中验证。）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| CaV3.1 是 TC 神经元爆发的关键通道 | 基因敲除（CaV3.1 KO）消除爆发-强直切换 | PMID:24285899 | 高 |
| CaV3.1 KO 消除听觉前向抑制 | KO 小鼠皮层记录 + 行为 | PMID:24285899 | 高 |
| PLCβ4 KO 增强 T 型电流 → 失神发作 | 小鼠遗传模型 + EEG | PMID:19955421 | 高 |
| Fmr1 KO 小鼠 T 型电流减小，爆发受损 | 膜片钳 | PMID:40966082 | 中（单一研究） |
| T 型通道抑制剂降低 3 Hz SWD | 视丘内注射 T 通道阻断剂 | PMID:19955421 | 高 |

## 连接

- [[thalamic-firing-modes]] — T 型通道是爆发/强直双模式的分子开关
- [[voltage-gated-calcium-channels]] — T 型是 LVA 钙通道，与 HVA（L/N/P/Q/R）对比
- [[sleep-spindles]] — TRN 的 CaV3.3 驱动纺锤波振荡，TC 的 CaV3.1 参与纺锤波传递
- [[action-potential]] — LTS 在顶端触发钠棘波，形成爆发

## 未解问题

- 目前尚无在清醒人类患者视丘中直接记录 T 型通道活动的技术
- CaV3.2 在视丘痛觉门控中的功能仍有争议

## 修订历史

- 2026-06-30 · 创建 · 基于《视丘的双面人格：T 型钙通道如何在爆发与强直之间切换》· 初始置信度：高；包含 CaV3.1/CaV3.3 分型、失活动力学、疾病连接

## 来源文章

- [[2026-06-30-thalamic-burst-t-type-calcium-timing-gate]]

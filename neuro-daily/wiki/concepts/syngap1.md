---
title: SynGAP1（突触 Ras GTPase 激活蛋白 1）
slug: syngap1
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-07
updated: 2026-09-07
revision_count: 1
dimensions: [molecular, synaptic, cellular, disease, cognition]
related: [psd-95, ltp, ltd, nmda-receptor, ampa-receptor, camkii, silent-synapse, critical-period, critical-period-plasticity, syngap1-related-disorder, ras-erk-signaling, hebbian-learning, homeostatic-plasticity, autism-spectrum-disorder]
prerequisites: [psd-95, nmda-receptor, ampa-receptor, ltp, synaptic-transmission, camkii]
opens_questions: [Q-syngap1-01, Q-syngap1-02]
source_articles: [2026-09-07-syngap1-synaptic-brake-intellectual-disability]
key_sources: ["PMID:32075947/PMC7046327", "PMID:9620694", "PMID:26558778/PMC4642239", "PMID:26912996/PMC4753466"]
---

# SynGAP1（突触 Ras GTPase 激活蛋白 1）(Synaptic Ras GTPase-Activating Protein 1)

> **一句话定义**：突触后密度（PSD）中含量第三丰富的支架蛋白（含量仅次于 CaMKIIα 和 PSD-95 家族），通过持续 Ras-GAP 活性压制 Ras-ERK 信号使突触保持"基线状态"，LTP 时被 CaMKII 磷酸化后从 PSD 弥散以解除制动——SynGAP1 是 LTP 表达的**必要解制动步骤**；其单倍剂量不足（SYNGAP1 +/−）导致突触提前过度成熟、关键期提前关闭，引发严重智力障碍和自闭症。

## 当前理解

我们现在认为，SynGAP1（*SYNGAP1* 基因，人类 6p21.32）是兴奋性突触的精密"双向制动器"，而非单纯的"抑制蛋白"。其核心逻辑是：

**平时（基线状态）**：SynGAP1 通过其 GAP 催化域持续加速 Ras 和 Rap1 的 GTP 水解，将两者维持在 GDP（无活性）状态。其中 Rap1-GAP 活性强于 Ras-GAP 活性，因此整体效果使突触倾向于低 AMPAR 状态（Ras-ERK 制动 = 阻止 AMPAR 插入；Rap1 轻度制动 = 轻度允许 AMPAR 移除）。

**LTP 时**：高频 NMDAR 激活 → Ca²⁺/CaMKII 激活 → CaMKII 磷酸化 SynGAP1（主要位点 Ser1108、Thr1286 等）→ SynGAP1 与 PSD-95 PDZ2 域的亲和力降低 → **SynGAP1 从 PSD 弥散（1-2 分钟内完成）** → Ras-ERK 信号解制动 → ERK 激活 Stargazin 磷酸化 → AMPAR 插入 → 同时 Rac1 激活 → 肌动蛋白聚合 → 棘突扩大 → LTP 完成。

关键洞察：**SynGAP1 弥散是 LTP 表达的必要步骤**——突变 SynGAP1 的 CaMKII 磷酸化位点会完全阻断 LTP 诱导的 AMPAR 插入和棘突扩大（Gamache et al. 2020）。

**SYNGAP1 单倍剂量不足的四重灾难**：
1. Ras-ERK 基线过高 → AMPAR 自发插入到应保持静默的突触
2. 静默突触池耗尽 → 失去发育期可塑性"原材料"
3. LTP 被遮蔽（occlusion）→ 无法进一步增强
4. 关键期提前关闭 → 回路永久过早固化

## 关键机制

### SynGAP1 的分子结构

| 域/特征 | 功能 |
|---------|------|
| GAP 催化域 + C2 域 | Ras 和 Rap1 GTPase 加速（C2 域对 Rap1-GAP 活性必要）|
| PH 域 + 卷曲螺旋（CC）| 蛋白质二聚化；膜靶向 |
| C 末端 PDZ 结合基序（–QTRV，仅 α1 亚型）| 与 PSD-95 PDZ2 域直接结合 → 突触定位 |
| 多种亚型（A/B/C 起始位点；α1/α2/β/γ C 末端）| 不同亚区分布和调控特性 |

### 磷酸化"代码"决定调控方向

| 激酶 | 主要效应 |
|------|---------|
| CaMKII（LTP 时）| 增强 Rap1-GAP 活性＞Ras-GAP 活性；降低 PSD-95 亲和力→弥散 |
| CDK5 | 增强 Ras-GAP 活性＞Rap1-GAP 活性 |
| Plk2 | 增强 H-Ras GAP 活性＞Rap1 |

因此，不同激酶输入使 SynGAP1 对"增强"和"减弱"两个方向的相对制动强度发生改变，实现精细的突触双向调控。

### LTP 解制动的完整回路

```
高频刺激
  → NMDAR 开放 → Ca²⁺ 内流
    → CaMKII 激活
      → SynGAP1 磷酸化 → 弥散离开 PSD
        → Ras-GTP 积累 → ERK 激活
          → Stargazin/TARP 磷酸化 → AMPAR 插入
        → Rac1 激活 → 肌动蛋白聚合 → 棘突扩大
  → [同时] CaMKII 磷酸化 AMPAR GluA1-S831 → 电导增加
```

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| SynGAP1 是 PSD 第三丰富蛋白 | 定量蛋白质组学 | PMID:32075947 (PMC7046327) | 高 |
| 磷酸化 SynGAP1 在 chemLTP 后 1-2 min 内弥散 | 荧光蛋白实时成像 | PMID:32075947 | 高 |
| 弥散幅度与 AMPAR 插入、棘突扩大正相关 | 电生理 + 成像同步 | PMID:32075947 | 高 |
| CaMKII 磷酸化位点突变体阻断 LTP | 磷酸化位点突变 + 电生理 | PMID:32075947 | 高 |
| SYNGAP1 +/- 海马神经元：更大棘突、更少静默突触、LTP occlusion | 电生理 + 形态学 | PMID:26558778 (PMC4642239) | 高（小鼠）|
| SynGAP1 对 Rap1 的 GAP 活性强于对 Ras | 体外 GTP 酶速率测定 | PMID:32075947 综述 | 高 |

## 连接

- [[psd-95]] — SynGAP1 通过 PDZ2 锚定于 PSD-95；LTP 时被 CaMKII 磷酸化后从 PDZ2 解离
- [[ltp]] — SynGAP1 弥散是 LTP 表达的必要解制动步骤
- [[nmda-receptor]] — NMDAR 激活触发 Ca²⁺→CaMKII→SynGAP1 磷酸化级联的起始
- [[ampa-receptor]] — Ras-ERK 解制动后驱动 AMPAR 插入；SynGAP1 制动时防止 AMPAR 自发插入
- [[camkii]] — 对 SynGAP1 进行关键磷酸化的执行者
- [[silent-synapse]] — SYNGAP1 +/- 使静默突触提前转化为活跃突触（静默突触池耗尽）
- [[critical-period]] — SynGAP1 制动维持关键期开放时间；制动失灵→关键期提前关闭
- [[syngap1-related-disorder]] — SYNGAP1 单倍剂量不足引发的临床综合征（ID+癫痫+ASD）
- [[autism-spectrum-disorder]] — ~50% SYNGAP1 患者同时满足 ASD 诊断
- [[homeostatic-plasticity]] — SynGAP1 与突触稳态共同调控突触强度的双重边界

## 未解问题

- Q-syngap1-01：不同 SynGAP1 亚型（α1 vs α2 vs β/γ）在海马 vs 前额叶的功能差异是否可以解释 SYNGAP1 患者认知损害的异质性？
- Q-syngap1-02：成年期基因治疗（AAV-SYNGAP1 补充或 ASO 激活）能否改善已固化的异常回路，治疗窗口的上限在哪里？

## 修订历史

- 2026-09-07 · 创建 · 基于《突触的"制动蛋白"：SynGAP1 如何通过解除 Ras-ERK 制动来执行 LTP》(#137) · 初始置信度：高（机制高，人类遗传学高）

## 来源文章

- [[2026-09-07-syngap1-synaptic-brake-intellectual-disability]]

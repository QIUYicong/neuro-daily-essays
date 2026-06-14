---
title: 去极化诱发的突触抑制（DSI/DSE）
slug: dsi-dse
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-15
updated: 2026-06-15
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit]
related: [endocannabinoid-system, cb1-receptor, 2-ag, ecb-ltd, endocannabinoid-ltd, synaptic-transmission, voltage-gated-calcium-channels]
prerequisites: [synaptic-transmission, action-potential, voltage-gated-calcium-channels]
opens_questions: [Q-ecb-01]
source_articles: [2026-06-15-endocannabinoid-retrograde-signaling]
key_sources: ["PMID:23040807", "PMID:25169670", "PMID:19126760"]
---

# 去极化诱发的突触抑制 (Depolarization-Induced Suppression of Inhibition/Excitation, DSI/DSE)

> **一句话定义**：突触后神经元强去极化→胞内 Ca²⁺ 升高→2-AG 合成释放→逆行激活突触前 CB1R→GABA 能（DSI）或谷氨酸能（DSE）突触的神经递质释放短暂减少（数秒至数十秒），是大脑中**逆向突触信号**的最早被发现也是研究最深入的形式。

## 当前理解

我们现在认为，DSI/DSE 是内源性大麻素（eCB）介导逆向信号的核心短时程形式。1991 年发现（Llano et al. 小脑；Pitler & Alger 海马），2001 年被 Wilson & Nicoll 和 Kreitzer & Regehr 两组同时证明为 eCB 依赖性。

DSI/DSE 的意义在于彻底证明了"突触后神经元可以主动调控其接收的突触输入"——即**突触通信是双向的**，而非单向从突触前到突触后。

2-AG（而非 AEA）是 DSI/DSE 的必要分子：DGLα 基因敲除小鼠在海马、纹状体、小脑三个脑区均完全丧失 DSI 和 DSE（Kano 2014, PMID:25169670）。

## 关键机制

### 完整信号级联

```
步骤1：突触后去极化（通常 1–5 秒强去极化脉冲）
  → 电压门控 Ca²⁺ 通道（VGCC）开放
  → 胞内 Ca²⁺ 快速升至微摩尔级

步骤2：2-AG 合成（可被 mGluR1/5 激活协同增强）
  → PLCβ（Ca²⁺/Gq 符合探测器）激活
  → DAG（二酰基甘油）↑
  → DGLα（突触后致密区旁）→ 2-AG 合成

步骤3：2-AG 逆行释放
  → 从突触后膜翻转/释放
  → 在 ~20 μm 内有效，靶向本突触前末梢

步骤4：突触前 CB1R 激活
  → CB1R（Gi/o 偶联）被 2-AG 结合
  → βγ 亚基直接偶联 P/Q 型 VGCC → Ca²⁺ 内流减少
  → 突触囊泡释放减少

步骤5：恢复
  → MAGL（突触前）水解 2-AG → 信号自然消退
  → GABA 能（DSI）或谷氨酸能（DSE）突触在 10–30 秒内恢复
```

### DSI vs DSE 的区别

| 特征 | DSI | DSE |
|------|-----|-----|
| 受影响突触类型 | GABA 能（抑制性）| 谷氨酸能（兴奋性）|
| 功能效果 | 减少对突触后的抑制 → 净兴奋增加 | 减少对突触后的兴奋 → 净抑制增加 |
| CB1R 分布 | CCK+ GABA 能末梢（高密度）| 谷氨酸能末梢（低密度但存在）|
| 典型研究脑区 | 海马 CA1、小脑 PC | 小脑（平行纤维→PC）、纹状体 |
| 功能意义 | 去抑制（短暂脱抑制）| 活动依赖的兴奋下调 |

### mGluR 协同（Ca²⁺ 辅助释放，最生理性模式）

纯粹 Ca²⁺ 驱动的 2-AG 合成需要较高 Ca²⁺ 浓度（微摩尔级），可能高于正常突触活动的 Ca²⁺ 水平。更生理性的触发方式是：

**亚阈值 Ca²⁺ + mGluR1/5 激活 → PLCβ 协同激活 → 2-AG 合成**

这就是"Ca²⁺ 辅助受体驱动释放（Ca²⁺-assisted RER）"模式：突触前谷氨酸激活突触后 mGluR → Gq/PLCβ → 同时 Ca²⁺ 协同 → 2-AG 大量合成。这一模式天然具有**联合法则**特性：需要突触前谷氨酸 + 突触后活动同时出现。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 2-AG 是 DSI/DSE 的必要分子 | DGLα-KO 小鼠（海马/纹状体/小脑 DSI 完全消失）| PMID:25169670 | 极高（遗传直接证明）|
| AEA 不是主导 DSI 分子 | NAPE-PLD-KO 小鼠（DSI 不变）| PMID:25169670 | 高 |
| MAGL 控制 DSI 持续时间 | MAGL 抑制剂延长 DSI；MAGL-KO 同效 | PMID:25169670 | 高 |
| CB1R 激活（βγ-VGCC）是短期机制 | 膜片钳 + CB1R 拮抗剂（SR141716A）| PMID:23040807 | 高 |
| mGluR 协同增强 DSI/DSE | mGluR 激动剂（DHPG）降低 DSI 阈值 | PMID:19126760 | 中-高 |

## 连接

- [[endocannabinoid-system]] — DSI/DSE 是 ECS 的短时程逆向信号形式
- [[2-ag]] — 唯一必要的 DSI/DSE 分子（DGLα-KO 直接证明）
- [[cb1-receptor]] — βγ-VGCC 偶联是短期效应机制
- [[ecb-ltd]] / [[endocannabinoid-ltd]] — 持续激活 CB1R 后 DSI 可演变为长期 LTD
- [[voltage-gated-calcium-channels]] — VGCC 是 2-AG 合成的 Ca²⁺ 来源，也是 CB1R 的下游靶标

## 未解问题

- Q-ecb-01：如果 eCB-LTD 的突触前靶蛋白（"T"）被鉴定，能否揭示 DSI 向 LTD 转变的分子开关？

## 修订历史

- 2026-06-15 · 创建 · 基于《逆向信使》一文（#193）· 初始置信度：高（遗传学和药理多重证明）

## 来源文章

- [[2026-06-15-endocannabinoid-retrograde-signaling]]

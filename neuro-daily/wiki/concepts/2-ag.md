---
title: 2-花生四烯酸甘油（2-AG）
slug: 2-ag
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-15
updated: 2026-06-15
revision_count: 1
dimensions: [molecular, synaptic]
related: [endocannabinoid-system, dsi-dse, ecb-ltd, endocannabinoid-ltd, cb1-receptor, camkii]
prerequisites: [synaptic-transmission, voltage-gated-calcium-channels]
opens_questions: [Q-ecb-02]
source_articles: [2026-06-15-endocannabinoid-retrograde-signaling]
key_sources: ["PMID:23040807", "PMID:25169670", "PMID:19126760"]
---

# 2-花生四烯酸甘油 (2-Arachidonoylglycerol, 2-AG)

> **一句话定义**：大脑中含量最高的内源性大麻素，由突触后神经元在 Ca²⁺ + PLCβ（±mGluR1/5）驱动下经 DGLα 按需合成，逆行激活突触前 CB1R，是 DSI/DSE 和多数脑区 eCB-LTD 的唯一必要分子。

## 当前理解

我们现在认为，2-AG 是 ECS 中**活动依赖性逆向信号的主力分子**。与另一种内源性大麻素 AEA 不同，2-AG 是 CB1R 的**完全激动剂**，且其合成路径（PLCβ-DGLα）定位于突触后致密区，使其能精准响应突触后活动。

关键遗传证据：DGLα-KO 小鼠在海马、纹状体和小脑的 DSI/DSE 完全缺失（PMID:25169670），直接证明 2-AG 是这些脑区 eCB 逆向信号的不可替代分子。

## 关键机制

### 合成（突触后，按需）

```
触发：突触后去极化/Ca²⁺ 升高 or Gq 受体激活
  → PLCβ（Ca²⁺ + Gq 符合探测器）
  → 膜磷脂酰肌醇 → 二酰基甘油（DAG）
  → DGLα（位于突触后棘头/树突）→ 2-AG

调节：
  CaMKII 磷酸化 DGLα → 酶活性↓ → 负反馈控制
```

### 释放与扩散

- 2-AG 从突触后膜释放（可能通过翻转扩散机制）
- 在 **~20 μm** 范围内有效（局限于本突触）
- 跨突触间隙的具体转运机制尚有争议（自由扩散 vs 蛋白辅助）

### 降解（突触前为主）

- **MAGL**（突触前）：负责 ~85% 的 2-AG 水解 → 控制 CB1R 激活时长
- **ABHD6**（突触后）：负责 ~15% → 防止突触后 2-AG 积累过多
- **COX-2**（突触后）：氧化降解通路，量少但功能有独特意义

### 与 AEA 的关键对比

| 特征 | 2-AG | AEA |
|------|------|-----|
| CB1R 亲和力 | 低（Ki ~500 nM）| 高（Ki ~50 nM）|
| CB1R 效能 | 完全激动剂 | 部分激动剂 |
| TRPV1 作用 | 弱 | 完全激动剂 |
| 脑内浓度 | 比 AEA 高 ~170–900 倍 | 低 |
| 合成主酶 | DGLα（明确）| NAPE-PLD（多路径，争议）|
| 主降解酶 | MAGL（突触前，85%）| FAAH（突触后）|
| DSI/DSE | 必要（KO 消失）| 不主导（NAPE-PLD-KO 不影响 DSI）|
| 主要功能 | 活动依赖性逆向抑制 | 基础调节 + TRPV1 LTD |

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 2-AG 是 DSI/DSE 的必要分子 | DGLα-KO（DSI 消失）| PMID:25169670 | 极高 |
| MAGL 控制 DSI 时长 | MAGL 抑制剂（JZL184）延长 DSI | PMID:25169670 | 高 |
| 2-AG 在 ~20 μm 内有效 | 刺激-距离关系实验 | PMID:23040807 | 中 |
| CaMKII 磷酸化 DGLα → 2-AG 合成↓ | CaMKII 激活实验 + DGLα 磷酸化质谱 | PMID:25169670 | 中 |

## 连接

- [[endocannabinoid-system]] — 2-AG 是 ECS 逆向信号的主力分子
- [[dsi-dse]] — 2-AG 是 DSI/DSE 的唯一必要分子（DGLα-KO 证明）
- [[cb1-receptor]] — 2-AG 是 CB1R 的主要内源配体（完全激动剂）
- [[camkii]] — CaMKII 通过磷酸化 DGLα 提供 2-AG 合成的负反馈

## 未解问题

- Q-ecb-02：2-AG（及 AEA）如何跨越含水的突触间隙？是自由扩散还是蛋白质辅助转运？

## 修订历史

- 2026-06-15 · 创建 · 基于《逆向信使》一文（#193）· 初始置信度：高（DGLα-KO 遗传直接证明，定量数据充分）

## 来源文章

- [[2026-06-15-endocannabinoid-retrograde-signaling]]

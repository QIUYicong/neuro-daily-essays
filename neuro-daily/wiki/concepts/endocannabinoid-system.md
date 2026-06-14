---
title: 内源性大麻素系统
slug: endocannabinoid-system
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-15
updated: 2026-06-15
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, behavior]
related: [dsi-dse, ecb-ltd, endocannabinoid-ltd, cb1-receptor, 2-ag, fear-extinction, pain-matrix, descending-pain-modulation, endogenous-opioids, dopamine, ltp, ltd, synaptic-transmission]
prerequisites: [synaptic-transmission, ltp, action-potential, voltage-gated-calcium-channels]
opens_questions: [Q-ecb-01, Q-ecb-02, Q-ecb-03, Q-ecb-04]
source_articles: [2026-06-15-endocannabinoid-retrograde-signaling]
key_sources: ["PMID:23040807", "PMID:19126760", "PMID:25169670", "PMID:37480845", "PMID:38957948"]
---

# 内源性大麻素系统 (Endocannabinoid System, ECS)

> **一句话定义**：由突触后神经元"按需合成"、逆向激活突触前 CB1 受体的脂质信号系统，实现从毫秒级抑制到持久 LTD 的多尺度突触调控，广泛参与恐惧消退、疼痛调节、运动学习和奖励回路。

## 当前理解

我们现在认为，ECS 是大脑最重要的**反馈增益控制系统**之一。与经典神经递质从突触前向突触后单向传递不同，ECS 的信号方向相反：突触后神经元在强烈活动时合成并释放内源性大麻素，这些脂质分子逆行激活突触前末梢的 CB1 受体，从而减少传入突触的神经递质释放。

ECS 在进化上高度保守（线虫→哺乳类），提示其执行基础性神经计算功能（Kano et al., 2009, PMID:19126760）。

ECS 具有三个层次的调控精度：
1. **空间精度**：2-AG 有效范围 ~20 μm，实现突触局限性
2. **时间精度**：DSI/DSE（秒级）vs eCB-LTD（分钟至持久）
3. **情境精度**：联合规则（同时需要突触后活动 + 突触前谷氨酸释放）确保选择性

## 关键机制

### 分子组成

| 组分 | 分子 | 功能 |
|------|------|------|
| 主配体 | 2-AG（2-花生四烯酸甘油）| 活动依赖性逆向抑制主力 |
| 次配体 | AEA（花生四烯酸乙醇胺）| 基础调节 + TRPV1 靶点 |
| 2-AG 合成酶 | DGLα（定位突触后） | Ca²⁺ + PLCβ 下游 |
| AEA 合成酶 | NAPE-PLD（路径不完全明确）| Gq/Ca²⁺ 依赖 |
| 2-AG 降解酶 | MAGL（突触前，~85%）| 控制信号时长 |
| AEA 降解酶 | FAAH（突触后内质网）| 控制 AEA 基础水平 |
| 主受体 | CB1R（Gi/o，突触前）| 短期和长期效应 |
| 二级受体 | TRPV1（AEA 靶点）| 突触后 LTD（纹状体、BLA）|

### 信号级联（以 DSI 为例）

```
突触后去极化（数秒）
 → Ca²⁺ 通过 VGCC 内流（± mGluR1/5 激活）
 → PLCβ（Ca²⁺/Gq 符合探测器）→ DAG 生成
 → DGLα → 2-AG 合成（按需）
 → 2-AG 从突触后膜释放（~20 μm 范围内有效）
 → 逆行激活突触前 CB1R（Gi/o）
 → [短期] βγ 亚基 → VGCC 抑制 → Ca²⁺↓ → 神经递质释放↓（秒级）
 → [长期] αi 亚基 → AC↓ → cAMP↓ → PKA↓ → 突触前蛋白去磷酸化 → LTD（分钟至持久）
```

### 三种 2-AG 动员模式

1. **Ca²⁺ 驱动（CaER）**：去极化 → Ca²⁺ 内流（微摩尔级）→ DGLα 激活。驱动 DSI/DSE。
2. **受体驱动（RER）**：Gq 偶联受体（mGluR1/5, M1/M3）→ PLCβ → 2-AG。无需 Ca²⁺ 升高。
3. **Ca²⁺ 辅助受体驱动（最生理性）**：亚阈值 Ca²⁺ + 亚阈值 Gq → 协同激活 PLCβ。联合法则的分子基础。

### 关键遗传学证据

- **DGLα-KO 小鼠**：海马、纹状体、小脑的 DSI 和 DSE **完全缺失** → 2-AG 是唯一必要分子（Kano 2014, PMID:25169670）
- **NAPE-PLD-KO 小鼠**：DSI 不受影响 → AEA 不是活动依赖性逆向信号的主导分子
- **MAGL-KO 或抑制**：DSI/DSE 持续时间延长 → MAGL 控制信号时长

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 2-AG 是 DSI/DSE 的必要分子 | DGLα-KO 小鼠（海马/纹状体/小脑 DSI 消失）| PMID:25169670 | 极高 |
| CB1R 激活→短期：βγ-VGCC 抑制 | 膜片钳 + CB1R 药理 | PMID:23040807 | 高 |
| CB1R 激活→长期：αi-AC-PKA 路径 | 腺苷酸环化酶抑制 + PKA 下游实验 | PMID:23040807 | 高 |
| vmPFC→BLA eCB-LTD 是恐惧消退机制 | 光遗传 + CB1R 成像 + 消退行为（小鼠）| PMID:37480845 | 高 |
| 炎症使脊髓 CB1R 抑制效果凸显 | 大鼠脊髓脑片 + AEA 药理（正常 vs 炎症）| PMID:38957948 | 中 |
| ECS 自身可塑（CaMKII-DGLα 轴）| CaMKII 磷酸化 DGLα 降低 2-AG 合成 | PMID:25169670 | 中 |

## 连接

- [[dsi-dse]] — ECS 介导的短时程逆向抑制（机制见专页）
- [[endocannabinoid-ltd]] — ECS 介导的长时程抑制（纹状体 D2-MSN 形式见专页）
- [[cb1-receptor]] — 主要突触前受体
- [[fear-extinction]] — vmPFC→BLA eCB-LTD 是恐惧消退的突触底物
- [[pain-matrix]] — 脊髓背角 CB1R/TRPV1 双重门控疼痛信号
- [[descending-pain-modulation]] — PAG 处 eCB 与阿片系统协同去抑制
- [[endogenous-opioids]] — 在 PAG 和脊髓共享去抑制机制
- [[dopamine]] — 纹状体 eCB-LTD 需要 D2R 协同；NAc 中 eCB 调节多巴胺释放
- [[ltp]] — eCB-LTD 与 LTP 互为平衡对（纹状体 D1 vs D2 回路）

## 未解问题

- Q-ecb-01：eCB-LTD 的突触前靶蛋白（"T"）的精确分子身份？（RIM1α 候选，证据不完整）
- Q-ecb-02：AEA 如何跨越突触间隙？自由扩散 vs 蛋白质载体（FABP, FLAT）？
- Q-ecb-03：FAAH/MAGL 抑制剂的临床安全性障碍（BIA 10-2474 毒性事件提示脱靶问题）
- Q-ecb-04：vmPFC→BLA eCB-LTD 在人类 PTSD 中是否受损？治疗时间窗？

## 修订历史

- 2026-06-15 · 创建 · 基于《逆向信使》一文（#193）· 初始置信度：高（基因敲除直接证明；多物种多脑区重复）

## 来源文章

- [[2026-06-15-endocannabinoid-retrograde-signaling]]

---
title: CB1 大麻素受体
slug: cb1-receptor
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-06-15
updated: 2026-06-15
revision_count: 1
dimensions: [molecular, cellular, synaptic]
related: [endocannabinoid-system, dsi-dse, ecb-ltd, endocannabinoid-ltd, 2-ag, voltage-gated-calcium-channels, dopamine, endogenous-opioids]
prerequisites: [synaptic-transmission, action-potential, voltage-gated-calcium-channels]
opens_questions: [Q-ecb-01]
source_articles: [2026-06-15-endocannabinoid-retrograde-signaling]
key_sources: ["PMID:23040807", "PMID:25169670", "PMID:41303613"]
---

# CB1 大麻素受体 (Cannabinoid Receptor 1, CB1R)

> **一句话定义**：脑内表达最广泛的 G 蛋白偶联受体（GPCR）之一，通过 Gi/o 偶联在突触前末梢介导内源性大麻素（主要是 2-AG）的逆向信号，实现神经递质释放的短期（βγ-VGCC）和长期（αi-AC-PKA）抑制。

## 当前理解

我们现在认为，CB1R 是 ECS 在神经系统中最主要的效应受体。它位于**突触前末梢**（顺位于突触后 DGLα 的逆行信号目标），通过两条 Gi/o 下游通路执行时间尺度截然不同的功能：

- **短期（秒级，DSI/DSE）**：βγ 亚基 → 直接偶联 P/Q 型 VGCC → Ca²⁺ 内流减少 → 囊泡融合减少
- **长期（分钟至持久，eCB-LTD）**：αi 亚基 → 腺苷酸环化酶（AC）抑制 → cAMP↓ → PKA↓ → 突触前蛋白去磷酸化 → 释放概率持久降低

CB1R 在 **CCK 阳性 GABA 能中间神经元**轴突末梢表达极高，在谷氨酸能末梢表达相对较低但功能重要。这种分布模式意味着 CB1R 主要调控抑制性突触的传递（DSI），兼顾兴奋性突触调节（DSE）。

## 关键机制

### 分子结构

- 7 次跨膜 GPCR（B 类 GPCR 家族成员）
- Gi/o 蛋白偶联（抑制性 G 蛋白）
- **主要内源配体**：2-AG（完全激动剂）; AEA（部分激动剂）
- **外源配体**：THC（Δ⁹-四氢大麻酚，部分激动剂）；SR141716A（拮抗剂/反向激动剂）

### 下游信号通路

```
2-AG + CB1R → Gi/o 蛋白激活 → αi/o + βγ 解离

[短期路径，βγ]
βγ → 直接偶联 P/Q 型 VGCC → Ca²⁺ 内流↓
→ 突触囊泡融合减少 → 神经递质释放↓（秒级）

[长期路径，αi]
αi → 腺苷酸环化酶（AC）抑制 → cAMP↓
→ PKA 活性↓
→ 突触前蛋白去磷酸化（候选：RIM1α）
→ 囊泡释放概率持久降低（eCB-LTD）

[其他通路，功能尚不完全清楚]
→ ERK/MAPK 激活（可能参与基因表达）
→ Kir（G 蛋白偶联内向整流 K⁺ 通道）激活
```

### CB1R 的分布特点

| 脑区 | 表达部位 | 密度 | 功能 |
|------|---------|------|------|
| 大脑皮层 | CCK+ GABA 末梢（极高）；锥体神经元谷氨酸末梢（低）| 高 | 调节 E/I 平衡 |
| 海马 | CCK+ 中间神经元末梢（极高）；Schaffer 侧枝（中等）| 高 | DSI、eCB-LTD |
| 纹状体（NAc/背侧纹状体）| MSN 接受的皮层谷氨酸终端 | 高 | eCB-LTD（D2-MSN）|
| 杏仁核（BLA）| 谷氨酸末梢（vmPFC 投射）| 中-高 | 恐惧消退 LTD |
| 小脑 | 平行纤维（PF）终端 | 高 | PF-PC LTD |
| 脊髓背角（浅层）| 一级传入（C 纤维/Aδ 末梢）| 中 | 镇痛（与 TRPV1 平衡）|
| PAG | GABA 能中间神经元末梢 | 中 | 镇痛去抑制 |
| VTA | GABA 能中间神经元末梢 | 中 | 多巴胺释放调节 |

### eCB-LTD 诱发的联合规则

eCB-LTD 区别于 DSI 的关键：它需要**联合规则**：
- 突触前活动（谷氨酸释放）→ mGluR1/5 激活 + 突触后 Ca²⁺ 升高 → 2-AG 大量合成
- **CB1R 只需在诱导期激活**（后续 CB1R 阻断不影响 LTD 表达）
- 确保只有"活跃的突触"才发生 LTD（输入特异性）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| CB1R 拮抗剂（SR141716A）完全阻断 DSI | 大鼠/小鼠脑片电生理 | PMID:23040807 | 极高 |
| CB1R-Gi/o→βγ 偶联 VGCC 是短期效应机制 | βγ 特异性干扰肽 + 电压钳 | PMID:23040807 | 高 |
| CB1R-αi→AC 抑制是长期效应机制 | AC 激活剂（forskolin）阻断 eCB-LTD | PMID:23040807 | 高 |
| vmPFC→BLA 突触处 CB1R 参与恐惧消退 | 光遗传激活 mPFC 轴突 + CB1R 成像 | PMID:37480845 | 高（小鼠）|
| CB1R 在 CCK+ GABA 末梢密度远高于兴奋性末梢 | 免疫电镜定量 | PMID:19126760 | 高（多物种）|

## 连接

- [[endocannabinoid-system]] — CB1R 是 ECS 的主要突触前效应受体
- [[2-ag]] — 2-AG 是 CB1R 的主要内源性完全激动剂
- [[dsi-dse]] — CB1R 通过 βγ-VGCC 介导 DSI/DSE
- [[endocannabinoid-ltd]] / [[ecb-ltd]] — CB1R 通过 αi-AC-PKA 介导 eCB-LTD
- [[voltage-gated-calcium-channels]] — CB1R 的主要短期下游靶标（βγ 偶联）
- [[fear-extinction]] — vmPFC→BLA CB1R 为恐惧消退的突触机制

## 未解问题

- Q-ecb-01：eCB-LTD 的 PKA 下游靶蛋白（"T"）分子身份？

## 修订历史

- 2026-06-15 · 创建 · 基于《逆向信使》一文（#193）· 初始置信度：高（多物种多脑区电生理 + 药理 + 遗传学）

## 来源文章

- [[2026-06-15-endocannabinoid-retrograde-signaling]]

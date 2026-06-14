---
title: 内源大麻素长时程抑制（纹状体）
slug: endocannabinoid-ltd
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-13
updated: 2026-06-15
revision_count: 2
dimensions: [molecular, synaptic, microcircuit, brain-region]
related: [corticostriatal-plasticity, basal-ganglia, habit-formation, dopamine, ltp, cb1-receptor, endocannabinoid-system, dsi-dse, 2-ag, fear-extinction]
prerequisites: [synaptic-transmission, ltp, dopamine, endocannabinoid-system]
opens_questions: [Q-cortstr-01, Q-ecb-01]
source_articles: [2026-06-13-corticostriatal-ltp-ltd, 2026-06-15-endocannabinoid-retrograde-signaling]
key_sources: ["PMID:11976704", "PMID:9169514", "PMID:15498813", "PMID:20096294", "PMID:19120438", "PMID:23040807", "PMID:37480845"]
---

# 内源大麻素长时程抑制（纹状体）(Endocannabinoid LTD in the Striatum)

> **一句话定义**：纹状体中型多棘神经元在强烈去极化时合成并释放内源大麻素（主要是 2-AG），作为逆行信使激活突触前皮质终端的 CB1 受体，持续抑制谷氨酸释放，产生长时程突触抑制（LTD）——这是间接通路 D2-MSN 可塑性的主要形式，也是习惯性行为自动化的候选分子基础。

## 当前理解

我们现在认为，纹状体的 eCB-LTD 是**突触前表达的逆行抑制**：不是突触后 MSN 对谷氨酸受体的敏感度下降，而是皮质终端释放的谷氨酸量本身减少。这一机制由 Gerdeman、Ronesi 和 Lovinger（2002, PMID:11976704，Nature Neuroscience）首次明确，彻底改变了对纹状体 LTD 机制的认识。

eCB-LTD 主要发生在 **D2-MSN（间接通路）**，因为 D2R 通过 Gq 臂协同 mGluR5 促进 2-AG 合成。在 D2 受体敲除小鼠（Calabresi et al. 1997, PMID:9169514）中，LTD 完全缺失并被 LTP 取代，这是 D2R 在 eCB-LTD 中发挥必要作用的遗传学证明。

## 关键机制

### 合成级联

```
1. 高频皮质输入 → MSN 强烈去极化（up state）
2. mGluR5（代谢型谷氨酸受体，Gq 耦合）被激活
3. + D2R 激活（Gq 臂，协同 PLC-DAG 通路）
4. PLC → DAG（二酰甘油）↑
5. DAGLα/β（二酰甘油脂酶）→ 2-AG（2-花生四烯酰甘油）合成
6. 2-AG 从 MSN 释放，逆行穿越突触裂隙
7. 结合突触前皮质终端的 CB1 受体（cannabinoid receptor 1）
8. CB1R-Gi → 腺苷酸环化酶↓ → cAMP↓
9. 突触前谷氨酸释放↓（通过 PKA 对释放机制的去磷酸化）
   → 长达数小时的谷氨酸释放减少 = LTD
```

### 中等频率也能诱导

Ronesi & Lovinger 2005（PMID:15498813）：10 Hz 中等频率皮质刺激（比高频 HFS 更接近生理范围）也能诱导 CB1 + D2 受体依赖的 eCB-LTD，提示这不只是实验室人工条件下的现象。

### 在 D1-MSN 中也存在（但较弱）

Adermark et al. 2009（PMID:19120438）：D1-MSN 也存在 eCB-LTD，但诱导阈值更高，需要更强的神经元放电。这意味着 eCB-LTD 不完全专属于间接通路，但在正常多巴胺状态下主要在 D2-MSN 中起主导作用。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| CB1R 拮抗剂完全阻断纹状体 LTD | 大鼠脑片；SR141716A；HFS | PMID:11976704（Gerdeman 2002, Nat Neurosci） | 高（多次独立重复） |
| D2-null 小鼠无 LTD（转为 LTP） | D2R 基因敲除小鼠脑片 | PMID:9169514（Calabresi 1997, J Neurosci） | 高 |
| 10 Hz 中等频率也能诱导 eCB-LTD | 大鼠纹状体脑片；10 Hz 皮质刺激；CB1/D2 药理 | PMID:15498813（Ronesi 2005, J Physiol） | 中-高 |
| eCB 调节兴奋性和抑制性突触可塑性 | 大鼠纹状体脑片；LFP 记录 | PMID:19120438（Adermark 2009, Eur J Neurosci） | 中 |

## 连接

- [[corticostriatal-plasticity]] — eCB-LTD 是 D2-MSN corticostriatal plasticity 的主要形式
- [[basal-ganglia]] — eCB-LTD 在间接通路中积累，影响 GPe→STN→GPi 的信号
- [[habit-formation]] — DLS D2-MSN eCB-LTD 积累被认为是习惯化的突触基础（直接证据仍待积累）
- [[dopamine]] — D2R 是 eCB-LTD 的必要协同因子（无 D2R 则无 eCB-LTD）
- [[ltp]] — 与 LTP 形成互补对：正向 DA 状态下 D1-MSN LTP + D2-MSN eCB-LTD 同时发生

## 未解问题

- Q-cortstr-01：清醒行为动物中，eCB-LTD 自然诱导的频率条件是什么？是否在每次正向奖励后都发生？持续时间多长？

### ★ 跨脑区视角（2026-06-15 更新）

纹状体 eCB-LTD 是 eCB-LTD 大家族在奖励/习惯回路中的特化形式。同一机制（2-AG→CB1R→AC/PKA 抑制→ 突触前蛋白去磷酸化→LTD）在其他脑区也以不同形式存在：

| 脑区 | 突触类型 | 诱导条件 | 功能意义 |
|------|---------|---------|---------|
| 纹状体（D2-MSN）| 皮层谷氨酸→MSN | HFS + D2R + mGluR5 | 习惯化自动化，本页主题 |
| 海马（CA1）| GABA 能中间神经元→CA1 | 突触后去极化 / θ-burst | 空间记忆精细化 |
| 小脑（PF-PC）| 平行纤维→浦肯野细胞 | CF 协同 + mGluR1 | 运动学习（与小脑 LTD 共存）|
| 杏仁核（BLA）| vmPFC→BLA 谷氨酸末梢 | 消退训练激活 eCB | 恐惧消退记忆形成（PMID:37480845）|

**BLA 的 eCB-LTD**（Gunduz-Cinar et al. 2023，PMID:37480845）证明 eCB-LTD 并非纹状体专属，而是脑内广泛存在的"输入特异性弱化"机制——见 fear-extinction 页。

## 修订历史

- 2026-06-13 · 创建 · 基于《学习写进突触：皮质纹状体回路的 D1/D2 二分可塑性》(#185) · 初始置信度：高（eCB-LTD 已有多次独立重复；但体内行为学直接证据尚在积累）
- 2026-06-15 · 修订（rev1→rev2）· 基于《逆向信使》一文（#193）· 新增"跨脑区视角"小节（海马、小脑、BLA 的 eCB-LTD）；related 新增 endocannabinoid-system / dsi-dse / 2-ag / fear-extinction；key_sources 新增 PMID:23040807 / PMID:37480845

## 来源文章

- [[2026-06-13-corticostriatal-ltp-ltd]]

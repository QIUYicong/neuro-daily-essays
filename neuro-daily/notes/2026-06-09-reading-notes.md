# 2026-06-09 阅读笔记：纹状体 D1/D2 极性突触可塑性

## 今日研究问题

多巴胺如何对纹状体直接通路（D1-MSN）和间接通路（D2-MSN）施加相反的长时程可塑性，从而将奖励信号转化为动作选择的持久偏好？

---

## 来源 1：Shen et al. 2008 Science（核心来源）

**PMID**：18687967 · **PMCID**：PMC2833421 · **全文可用**：是  
Shen W, Flajolet M, Greengard P, Surmeier DJ. Science. 2008;321(5890):848-51.

### 核心发现
- D1-MSN：正向 STDP（+5ms）→ LTP；负向（−10ms）→ 无变化（PKA 抑制 eCB-LTD）
- D2-MSN：正向 → LTP（A2A/PKA）；负向 → LTD（D2/eCB/CB1）
- PD 模型（6-OHDA）：D1-MSN 单向 LTD，D2-MSN 单向 LTP（极性对调）
- 方法：D1/D2-EGFP 小鼠 + 脑片 patch-clamp STDP

### 局限
离体，DA 恒定，非生理动态

---

## 来源 2：Kravitz et al. 2010 Nature（摘要引用）

**PMID**：20613723 · 全文不可用（付费）  
Kravitz AV et al. Nature. 2010;466:622-6.

- 体内光遗传：激活直接通路 → 缓解 PD 运动症状
- 激活间接通路 → 诱发类 PD 运动障碍

---

## 来源 3：Kravitz et al. 2012 Nat Neurosci

**PMID**：22544310 · **PMCID**：PMC3410042 · 全文可用  
Kravitz AV, Tye LD, Kreitzer AC. Nat Neurosci. 2012;15(6):816-8.

- D1-dSPN 激活 → 持续正强化（24h 后偏好持续）
- D2-iSPN 激活 → 短暂惩罚/回避（不如强化持久）

---

## 来源 4：Gurney et al. 2015 PLOS Biology

**PMID**：25562526 · **PMCID**：PMC4285402 · 全文可用  
Gurney KN, Humphries MD, Redgrave P. PLOS Biol. 2015;13(1):e1002034.

- STDE 框架：D1/D2 活动在学习中均升高，但方向相反
- D1：支持已选动作；D2：抑制未选竞争动作
- 两者协同，而非简单拮抗

---

## 来源 5：Calabresi et al. 2007 Trends Neurosci（摘要）

**PMID**：17367873 · 仅摘要  
奠基性综述，D1 促 LTP，D2/eCB 促 LTD，未读全文。

---

## 来源 6：Phillips et al. 2024 J Neurosci

**PMID**：38370850 · **PMCID**：PMC10871330 · 全文可用  
Phillips CD et al. J Neurosci. 2024;44(26):e0240242024.

- 运动技能学习中 DA 信号时序重加权（动作→预测性提示）
- D1 低亲和力（相位性 DA），D2 高亲和力（紧张性 DA）
- 多巴胺在 DLS（运动区）动力学快，DMS 慢

---

## 知识整合表

| 指标 | D1-MSN | D2-MSN |
|------|--------|--------|
| 受体偶联 | Gs → cAMP↑ → PKA↑ | Gi/o → cAMP↓；A2A → cAMP↑ |
| DA↑时可塑性 | LTP（单向） | LTD（eCB通路开放） |
| DA↓时可塑性 | LTD（PKA失保护） | LTP（A2A相对主导） |
| PD状态 | 单向LTD（错误方向） | 单向LTP（错误方向） |
| 光遗传激活 | 持续强化 | 短暂惩罚 |

## 新问题

1. A2A-D2 受体是否有物理二聚体，细胞内拮抗如何实现？
2. D1 低亲和力设计的演化/计算逻辑？
3. 皮层哪些区域的输入分别靶向 D1/D2 MSN？解剖特异性？

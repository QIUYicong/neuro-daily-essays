---
title: 树突棘
slug: dendritic-spine
domain: neurons
type: structure
status: established
confidence: high
created: 2026-09-23
updated: 2026-09-23
revision_count: 1
dimensions: [cellular, synaptic, molecular]
related: [ltp, camkii, ampa-receptor, nmda-receptor, cofilin-actin-spine, dendritic-computation, btsp, postsynaptic-density, actin-dynamics-spine]
prerequisites: [synaptic-transmission, nmda-receptor, ltp]
opens_questions: [Q-spine-btsp-01, Q-spine-early-late-02, Q-spine-size-bound-03, Q-spine-disease-04]
source_articles: [2026-09-23-dendritic-spine-structural-plasticity]
key_sources: ["PMID:15190253", "PMID:37290118", "PMID:41249054", "PMID:40986440", "PMID:19400723"]
---

# 树突棘 (Dendritic Spine)

> **一句话定义**：神经元树突上微小的突起结构（直径 0.1–2 μm），是大多数兴奋性突触（谷氨酸能）的突触后接受位点；棘头体积与 AMPA 受体数量和突触强度高度相关，棘形态在 LTP/LTD 后会发生持久性结构重塑，是记忆在细胞水平的物质基底之一。

## 当前理解

我们现在认为，树突棘不是静态的突触接收装置，而是**动态可塑的计算单元**。其关键特性包括：

**形态多样性与功能分级**：
- 蘑菇形棘（mushroom spine）：棘头直径 >0.6 μm，PSD 面积大，含大量 AMPA 受体 → 成熟"强突触"
- 细颈形/薄棘（thin/filopodium-like spine）：棘头小，PSD 不完整，多为"沉默突触"（仅有 NMDAR，无 AMPA） → LTP 前体
- 粗短形（stubby spine）：短棘颈，钙扩散不受限制 → 可能功能较弱
- 分叉形（branched spine）：见于发育期和某些可塑性情境

**结构-功能关系**：棘头体积与突触 AMPA 受体数量高度相关（r ≈ 0.9）；蘑菇棘是强突触，细颈棘是潜在突触。这不是静态分类，而是动态谱系：细颈棘在 LTP 后可扩大为蘑菇棘，蘑菇棘在 LTD 后会收缩。

**结构可塑性是 LTP 的形态学对应物**：LTP 诱导后，棘头体积在数十分钟内膨大 200–300%，并在 100 分钟后保持约 70% 的增大（Matsuzaki et al. 2004）。这是 Ca²⁺→CaMKII→Rac1/RhoA→LIMK→cofilin 失活→F-肌动蛋白净聚合驱动的持久结构变化，是将"短暂化学信号"转化为"持久空间结构"的核心机制。

**大小依赖性**：重要的是，**小棘的可塑性远大于大棘**——蘑菇棘对同样的 LTP 刺激几乎不响应（体积增大 <10%），而细颈棘可增大 200–300%。大棘已近"饱和"，小棘才有空间写入新记忆。

## 关键机制

### 1. 结构可塑性的分子级联（LTP 诱导后）

```
Ca²⁺（NMDAR）
    ↓
CaMKII 激活（T286 自磷酸化）
    ↓
GEFs（Tiam1/βPIX/GEF-H1等）激活
    ↓
Rac1-GTP ←——————→ RhoA-GTP
    ↓                    ↓
PAK1/2              ROCK1/2
    ↓                    ↓
LIMK1/2 ←——————————————
    ↓
cofilin 磷酸化（Ser3）→ 失活
    ↓
F-肌动蛋白净聚合减少切割
    ↓
棘头体积增大（结构 LTP）
```

### 2. 平行路径：Rac1 可以独立激活

Saneyoshi et al. 2025 证明：短暂光激活 Rac1（不依赖 CaMKII 激酶活性）足以诱导持续结构 LTP。Rac1 是 F-actin 聚合的**独立触发器**，不只是 CaMKII 的下游执行者。两条路径（CaMKII→GEF→Rac1 和直接 Rac1 激活）在 F-actin 节点汇合。

### 3. 结构与功能耦合：Rab 蛋白调控 AMPAR 流量

Wang et al. 2025 发现：
- Rab4 短暂激活（<10 min）→ 再循环内体移向棘头 → 新 AMPAR 插入
- Rab10 持续失活（>30 min）→ AMPAR 在棘头滞留（不回流棘颈区域）
- 时序：Rab4 激活（快速补充）→ 棘体积增大（结构扩展）→ Rab10 持续失活（维持受体驻留）

### 4. 两个阶段

| 阶段 | 时间 | F-actin 状态 | 药物敏感性 | 依赖 |
|------|------|------------|----------|------|
| 早期棘扩大 | 0–30 min | 动态，周转加速后减慢 | 对细胞松弛素敏感 | CaMKII 持续活性 |
| 晚期稳定 | >30 min | 稳定骨架 | 对细胞松弛素不敏感 | 新蛋白合成（BDNF/Arc） |

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 小棘 LTP 后膨大 200–300%，大棘几乎不变 | 2P 谷氨酸解笼 + 荧光体积成像 | Matsuzaki et al. 2004, Nature, PMID:15190253 | 高 |
| 棘头体积 ↔ AMPA 电流相关 r≈0.84 | 同上 | PMID:15190253 | 高 |
| Rac1 光激活独立诱导 sLTP（不需 CaMKII 激酶活性） | 光遗传 Rac1 + 2P 成像 | Saneyoshi et al. 2025, eNeuro, PMID:41249054 | 高 |
| Rab10 失活（>30 min）+ Rab4 短暂激活协调 AMPAR 流量与棘扩大 | 遗传编码 Rab 传感器 + sLTP | Wang et al. 2025, eLife, PMID:40986440 | 高 |
| F-actin 在 LTP 后净增加，LTD 后净减少 | FRAP + phalloidin 染色 | Bhatt et al. 2009, Annu Rev Neurosci, PMID:19400723 | 高 |

## 连接

- [[ltp]] — 树突棘结构可塑性是 LTP 的形态学对应物
- [[camkii]] — CaMKII 是结构可塑性的触发分子
- [[cofilin-actin-spine]] — cofilin 磷酸化是肌动蛋白聚合的关键开关
- [[ampa-receptor]] — 棘头体积扩大与 AMPA 受体插入耦合
- [[nmda-receptor]] — NMDAR 提供 Ca²⁺ 触发信号
- [[postsynaptic-density]] — PSD 面积随棘头扩大而增加
- [[btsp]] — BTSP 是否也伴随结构棘扩大是关键未解问题
- [[dendritic-computation]] — 棘作为细胞骨架计算单元影响树突计算

## 未解问题

- **Q-spine-btsp-01（高优先级）**：BTSP 诱导后棘是否也有结构性膨大？体内 2P 直接证据缺失。
- **Q-spine-early-late-02（高优先级）**：早期动态 F-actin → 晚期稳定 F-actin 的分子开关是什么？
- **Q-spine-size-bound-03（中优先级）**：蘑菇棘体积上限的调控机制（PSD 面积/膜张力/抑制反馈）？
- **Q-spine-disease-04（中优先级）**：tau 过度磷酸化如何干扰 cofilin-actin 动态（AD 机制）？

## 修订历史

- 2026-09-23 · 创建 · 基于《记忆的雕塑家：树突棘如何用肌动蛋白重塑自身形状来固化一次学习》(#153) · 初始置信度：高（4篇高质量全文来源）

## 来源文章

- [[2026-09-23-dendritic-spine-structural-plasticity]]

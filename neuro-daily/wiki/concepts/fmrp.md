---
title: FMRP（脆性X智力低下蛋白）
slug: fmrp
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-10-17
updated: 2026-10-17
revision_count: 1
dimensions: [molecular, synaptic, cellular, disease]
related: [mglur-ltd, fragile-x-syndrome, arc-arg31, ampa-receptor, mglur5, protein-synthesis-synaptic, bdnf]
prerequisites: [synaptic-transmission, ampa-receptor, mglur-ltd]
opens_questions: [Q-fmrp-01, Q-fmrp-02]
source_articles: [2026-10-17-mglur5-ltd-fragile-x-fmrp]
key_sources: ["PMID:33608673", "PMC:8094212", "PMID:15219735", "PMID:18093519"]
---

# FMRP（脆性X智力低下蛋白）(Fragile X Mental Retardation Protein)

> **一句话定义**：FMR1 基因编码的 RNA 结合蛋白，通过在突触局部停滞核糖体来抑制约 842 个 mRNA（包括 Arc、MAP1b、STEP 等 mGluR-LTD 执行蛋白）的翻译延伸；mGluR5 激活后经去磷酸化释放翻译抑制，允许突触可塑性执行；FMRP 缺失（FMR1 CGG 扩增导致 DNA 甲基化沉默）引发脆性X综合征（最常见遗传性智力障碍）。

## 当前理解

我们现在认为，FMRP 是突触可塑性的**翻译速率门控者**——它不是简单的翻译"开关"，而是一个可被信号精细调控的"限速阀"，将突触局部的蛋白合成维持在适当速率范围内。

FMRP 通过**停滞多聚核糖体**（stalling polysomes）来减慢 mRNA 的翻译延伸——这意味着核糖体在靶标 mRNA 的编码区上走走停停，而不是完全无法读取。这种机制允许快速响应：一旦 mGluR5 信号到来，FMRP 被去磷酸化（PP2A）或泛素化降解，核糖体速率加快，突触所需蛋白迅速累积。

HITS-CLIP 技术（2011）鉴定了幼鼠前脑中 842 个高置信度 FMRP 靶 mRNA，其中约 1/3 编码突触后蛋白（包括 mGluR 和 NMDA 受体亚基本身）（Richter 2021, Nat Rev Neurosci, PMC8094212）。FMRP 的调控范围远超"单一机制的单一蛋白"，是一个**系统性翻译速率调控器**。

在脆性X综合征（FXS）中，FMR1 基因 CGG 重复扩增（>200 次）引发甲基化沉默，FMRP 缺失，其 842 个靶 mRNA 的翻译速率失控升高，导致 mGluR-LTD、突触形态发育、突触稳态等多个依赖精确翻译控制的功能全面失调（Bear mGluR 理论，PMID:15219735）。

## 关键机制

### 分子结构

- **632 个氨基酸**（人类）
- **两个 KH 结构域**（hnRNP K 同源）：识别并结合 mRNA 编码区（CDS）而非 UTR（区别于多数 RNA 结合蛋白）
- **RGG 盒**：结合 G-四链体结构的 mRNA
- **N 端 Agenet/Tudor 结构域**：蛋白-蛋白互作
- 主要定位：胞质多聚核糖体，与 mRNA 相伴转运到树突

### 翻译抑制机制

FMRP 通过与核糖体（60S 亚基）的直接结合**停滞翻译延伸**，使核糖体在编码区某些位置"卡住"，降低多聚体的运动速率。不是阻止翻译启动，而是在延伸过程中降速。

### mGluR5 触发的 FMRP 释放

1. mGluR5 激活 → 下游信号（PP2A 激活）→ FMRP Ser499 去磷酸化
2. 去磷酸化的 FMRP 构象改变，对靶标 mRNA 亲和力降低
3. 核糖体解除停滞，翻译延伸加速
4. FMRP 也可经泛素-蛋白酶体降解（双重去抑制）
5. Arc、MAP1b、STEP 快速积累 → mGluR-LTD 执行

### 脆性X综合征的分子链

```
FMR1 CGG扩增（>200次）
    ↓ DNA甲基化
FMR1 基因沉默
    ↓
FMRP 缺失
    ↓
Arc/MAP1b/STEP 等基础翻译速率升高
    ↓
mGluR5 激活门槛降低；蛋白无需新合成已足够
    ↓
mGluR-LTD 增强且不再依赖急性翻译
    ↓
突触权重弥漫下调 + 突触形态发育异常（多而未成熟的树突棘）
    ↓
智力障碍、自闭症样行为、癫痫敏感性升高
```

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| FMRP 有 842 个高置信靶 mRNA（幼鼠前脑） | HITS-CLIP 技术 | PMID:33608673 | 高 |
| FMRP 主要结合 mRNA 编码区（CDS） | CLIP-seq 峰图分析 | PMID:33608673 | 高 |
| FMRP 通过停滞多聚核糖体抑制翻译延伸 | 蔗糖梯度离心分析；核糖体速率测量 | PMID:33608673 | 高 |
| Fmr1 KO 小鼠 mGluR-LTD 增强，且不再需要急性蛋白合成 | DHPG 诱导 + 翻译抑制剂在 KO 中无效 | PMID:20188650 | 高 |
| 50% mGluR5 遗传减少纠正 Fmr1 KO 多项 FXS 表型 | 双敲除/杂合遗传策略 | PMID:18093519 | 高 |
| mGluR5 激活 → FMRP Ser499 去磷酸化 | 磷酸化抗体 + 药理实验 | PMID:33608673 | 中-高 |

## 连接

- [[mglur-ltd]] — mGluR-LTD 翻译制动器：FMRP 限制 Arc/MAP1b/STEP 合成速率
- [[fragile-x-syndrome]] — FMRP 缺失的遗传后果，FXS 最常见遗传性智力障碍
- [[arc-arg31]] — FMRP 的关键靶标 mRNA 之一；mGluR 激活后 Arc 翻译的释放是 mGluR-LTD 的执行步骤
- [[ampa-receptor]] — FMRP 调控 AMPAR 亚基（GluA1、GluA2）的翻译；FMRP 缺失导致 AMPAR 表达失调
- [[mglur5]] — mGluR5 激活通过 PP2A 去磷酸化释放 FMRP 的翻译抑制
- [[bdnf]] — BDNF 的 mRNA 也是 FMRP 靶标之一；FXS 中 BDNF 翻译失调参与突触发育异常

## 未解问题

- Q-fmrp-01（中优先级）：FMRP 在不同树突区室（近端 vs 远端棘）、不同突触类型（兴奋性 vs 抑制性）的局部分布和局部浓度动态是什么？翻译释放是全树突同步发生还是局部化的？
- Q-fmrp-02（高优先级）：FMRP 缺失时，除 mGluR-LTD 外有哪些其他突触机制失调？Thomazeau 2021 已显示 NMDAR-棘通路的蛋白合成门控也消失——这是 FMRP 直接调控 NMDAR 通路蛋白（如 cofilin、actin 调节蛋白）的结果吗？

## 修订历史

- 2026-10-17 · 创建 · 基于《mGluR5 依赖的长时程抑制：突触削减的精密设计与脆性X综合征的分子悲剧》(#177) · 初始置信度：高 · 综合 Richter 2021 (PMC8094212)、Bear et al. 2004、Dölen et al. 2007

## 来源文章

- [[2026-10-17-mglur5-ltd-fragile-x-fmrp]]

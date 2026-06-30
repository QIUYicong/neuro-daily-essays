---
title: 脆性X综合征
slug: fragile-x-syndrome
domain: diseases
type: disease
status: established
confidence: high
created: 2026-10-17
updated: 2026-10-17
revision_count: 1
dimensions: [molecular, synaptic, cellular, cognition, disease]
related: [fmrp, mglur-ltd, arc-arg31, ampa-receptor, mglur5, autism-spectrum-disorder, intellectual-disability]
prerequisites: [fmrp, mglur-ltd, ampa-receptor]
opens_questions: [Q-fxs-01, Q-fxs-02]
source_articles: [2026-10-17-mglur5-ltd-fragile-x-fmrp]
key_sources: ["PMID:15219735", "PMID:18093519", "PMC:2199268", "PMID:33608673", "PMID:39483619", "PMID:32606374"]
---

# 脆性X综合征 (Fragile X Syndrome, FXS)

> **一句话定义**：由 X 染色体 FMR1 基因 CGG 三核苷酸重复扩增（>200 次）导致 FMRP 缺失的遗传性神经发育障碍，是迄今已知最常见的遗传性智力障碍（男性约 1/4000）和最常见的单基因自闭症原因；分子机制为 FMRP 缺失导致 mGluR5 依赖的蛋白合成调控失控，突触权重弥漫下调、发育可塑性异常。

## 当前理解

我们现在认为，FXS 是一种以**翻译调控失调为核心分子缺陷**的神经发育疾病，而非简单的"突触发育缺陷"。

正常情况下，FMRP 作为约 842 个突触局部 mRNA 的翻译速率限制器（Richter 2021），将 mGluR5→蛋白合成→可塑性这条轴的响应强度维持在适当范围。FMR1 CGG 扩增导致基因甲基化沉默、FMRP 消失后，多条依赖精确翻译控制的机制同时失调：

1. **mGluR-LTD 过度增强**（Bear mGluR 理论，PMID:15219735）：Arc、MAP1b、STEP 基础翻译速率升高，mGluR5 激活的门槛降低，突触权重系统性下调
2. **树突棘发育异常**：棘数量增多但形态细长不成熟（过多的突触形成后缺乏适当的稳定化和成熟化）
3. **NMDAR 通路的蛋白合成门控丧失**（Thomazeau et al. 2021, PMID:32606374）：FX 小鼠中，NMDAR 激活引起的棘收缩不再需要 mTORC1 或急性蛋白合成，说明 FMRP 的调控范围超出 mGluR 通路
4. **兴奋/抑制平衡失调**：癫痫敏感性（听源性发作等）升高

**临床上**，FXS 的主要表现为智力障碍（尤以男性严重，女性因 X 失活而表型不一）、语言延迟、自闭症样社交缺陷、感觉过敏、焦虑、注意缺陷等。

**治疗上**，Bear 的 mGluR 理论（2004）推动了 mGluR5 拮抗剂（mavoglurant、basimglurant）的临床开发，但 2019–2024 年多个试验均未达主要终点，提示简单阻断 mGluR5 不足以逆转 FXS 的复杂神经发育后果。

## 关键机制

### 遗传机制

- X 染色体 Xq27.3，FMR1 基因 5' UTR 的 CGG 三联体重复：
  - 正常：5–55 次
  - 前突变（前体）：55–200 次（可能有轻度症状，男性后代有 CGG 进一步扩增风险）
  - 全突变：>200 次 → DNA 甲基化 → FMR1 启动子沉默 → FMRP 缺失
- X 连锁遗传：男性（XY）只有一个 FMR1 拷贝，全突变时完全受影响；女性（XX）因 X 失活而表型可变

### 分子层面：翻译制动器缺失

见 [[fmrp]] 和 [[mglur-ltd]] 的详细机制。关键是：FMRP 缺失 → Arc/MAP1b/STEP 等 mGluR-LTD 执行蛋白的 mRNA 基础翻译速率升高 → mGluR-LTD 增强且不再需要急性激活 → 突触权重弥漫下调。

### 树突棘表型

FXS 小鼠和人死亡后组织均显示：树突棘密度增高（多）但棘形态细长、"不成熟"（filopodia 样），成熟蘑菇形棘比例减少。这既反映了突触形成过多、也反映了成熟化/稳定化不足，两者均与 FMRP 对发育期突触蛋白翻译的调控失调有关。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| FMR1 CGG 扩增 → DNA 甲基化 → FMRP 缺失 | 分子遗传学分析；免疫印迹 | 经典遗传学 | 高 |
| Fmr1 KO 小鼠 mGluR-LTD 增强且不依赖急性蛋白合成 | DHPG 诱导 + 翻译抑制剂测试 | PMID:20188650 | 高 |
| 50% mGluR5 遗传减少纠正 FX 小鼠多项表型 | Fmr1 KO × mGluR5+/- | PMID:18093519 | 高 |
| FXS 树突棘多而未成熟（filopodia 样） | 人脑死后组织 Golgi 染色；FX 小鼠成像 | 多篇经典研究 | 高 |
| mavoglurant 在 3–6 岁 FXS 儿童不改善语言 | FXLEARN RCT | PMID:39483619 | 高 |
| FX 小鼠 NMDAR-棘通路蛋白合成门控丧失 | 双光子成像 + 翻译抑制剂（mTORC1 抑制） | PMID:32606374 | 高 |

## 连接

- [[fmrp]] — 核心分子缺陷：FMRP 缺失是 FXS 所有分子后果的上游原因
- [[mglur-ltd]] — 核心受累通路：mGluR-LTD 失控是 FXS 突触病理的核心机制之一
- [[arc-arg31]] — FMRP 靶标之一，FXS 中 Arc 基础翻译过高参与 mGluR-LTD 过激
- [[ampa-receptor]] — AMPAR 内吞异常是 FXS 突触权重失调的表现层
- [[alzheimers-disease]] — AD 中 Aβ 也可通过 mGluR-LTD 样机制引起 AMPAR 移除（不同疾病共享通路）

## 未解问题

- Q-fxs-01（高优先级）：mGluR5 拮抗剂临床失败的核心原因——是治疗时机（发育窗口已过）、补偿机制（NMDAR 通路也已失调）、测量工具不灵敏，还是 Bear 理论本身对人类 FXS 的适用性有限？
- Q-fxs-02（中优先级）：基因治疗（AAV 载体恢复 FMRP 表达）或表观遗传去甲基化的时间窗口是什么？成年期恢复 FMRP 是否足够、还是必须在关键期前干预？

## 修订历史

- 2026-10-17 · 创建 · 基于《mGluR5 依赖的长时程抑制：突触削减的精密设计与脆性X综合征的分子悲剧》(#177) · 初始置信度：高 · 综合 Bear et al. 2004、Dölen et al. 2007、Richter 2021、Thomazeau et al. 2021

## 来源文章

- [[2026-10-17-mglur5-ltd-fragile-x-fmrp]]

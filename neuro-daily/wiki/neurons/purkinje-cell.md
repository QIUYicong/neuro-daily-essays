---
title: 浦肯野细胞
slug: purkinje-cell
domain: neurons
type: structure
status: established
confidence: high
created: 2026-06-23
updated: 2026-06-23
revision_count: 1
dimensions: [cellular, synaptic, microcircuit]
related: [cerebellum, cerebellar-motor-learning, climbing-fiber, parallel-fiber, long-term-depression]
prerequisites: [action-potential, synaptic-transmission, dendritic-computation]
opens_questions: [Q-cb-02]
source_articles: [2026-06-23-cerebellum-motor-learning]
key_sources: ["PMID:35803588", "PMID:32866603"]
---

# 浦肯野细胞 (Purkinje Cell)

> **一句话定义**：小脑皮层中形态最复杂、树突最宽大的 GABA 能神经元，是小脑皮层的唯一输出细胞，整合来自约 15–20 万条并行纤维的弱突触输入和单条攀爬纤维的强误差信号，输出驱动深部核团，是小脑运动学习（LTD）的关键执行者。

## 当前理解

我们现在认为，浦肯野细胞（PC）是小脑"教学回路"的核心整合器。它的巨大扇形树突（在矢状面展开，占分子层绝大部分）接收来自约 15–20 万条并行纤维的微弱突触接触——每个并行纤维突触仅贡献极小的兴奋性输入（AMPA/kainate）。与此同时，来自下橄榄核的单条攀爬纤维（adult 1:1 ratio）以高度强烈的方式接触整个树突树，产生剧烈的"复合脉冲（complex spike）"，触发广泛树突钙瞬变。

PC 的运动学习逻辑是：当并行纤维激活（代表某运动状态）与攀爬纤维信号（代表该状态下的运动误差）**时序上接近时**，mGluR1 + ΔCa²⁺ + PKC 级联启动 AMPA 受体内吞，导致该特定并行纤维-PC 突触的 LTD（见 [[cerebellar-motor-learning]]）。

PC 同时也是分子层中间神经元（MLIs）的靶点——MLIs 持续抑制 PC，通过新近发现的二级去抑制回路（Park et al. 2026）确保只有真实的、同步的误差信号才能触发学习。

**放电模式**：
- 简单脉冲（simple spike）：40–100 Hz 持续放电，由并行纤维驱动
- 复合脉冲（complex spike）：约 1 Hz，由攀爬纤维触发；代表误差信号；每次触发长时间的后超极化

**输出**：PC 轴突投射到深部小脑核团（齿状核、顶核等），通过 GABA 持续性抑制 DCN 神经元；PC 放电减少（LTD 结果）→ DCN 去抑制 → 运动输出精调

## 关键机制

**LTD 分子级联**（在 PF-PC 突触）：
1. 并行纤维 → 谷氨酸 → AMPA 受体（快速去极化）+ mGluR1（慢速 IP₃ 信号）
2. 攀爬纤维 → 剧烈去极化 + P/Q 型钙通道开放 → [Ca²⁺]↑↑
3. mGluR1 激活 → IP₃ → 内质网钙释放 → [Ca²⁺]进一步升高
4. PKC（C 型蛋白激酶）激活 → GluA2 亚基磷酸化
5. AMPA 受体内吞（clathrin 介导）→ PF-PC 突触弱化（LTD）

**时序窗口**：并行纤维激活必须早于攀爬纤维信号约 50–300 ms，才能有效诱发 LTD；这保证了"先行动→后评估误差"的因果方向

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| PC 是小脑皮层唯一输出（GABA 能）| 解剖学 + 电生理（Ito 1960s）| PMID:32866603 | 高 |
| PF-PC LTD 依赖 mGluR1 + Ca²⁺ + PKC → AMPA 内吞 | mGluR1 KO 无 LTD；钙成像；受体追踪 | PMID:35803588 | 高 |
| LTD 有 50–300 ms 时序窗口（PF 先于 CF）| 离体脑片诱发实验 | PMID:34953298 | 高 |
| PC 复合脉冲代表运动预测误差 | 在体记录（VOR、眼睑条件化、伸手任务）| PMID:32866603 | 高 |

## 连接

- [[cerebellum]] — 所在脑区
- [[cerebellar-motor-learning]] — PC 参与的学习回路
- [[climbing-fiber]] — 来自下橄榄核的强误差输入
- [[parallel-fiber]] — 来自颗粒细胞的弱状态输入
- [[long-term-depression]] — PC 上发生的 LTD，与 CA1-LTD 机制有异同
- [[dendritic-computation]] — PC 巨大树突上的非线性整合（参考文章 #04）

## 未解问题

- Q-cb-02：ASD 中的 PC 损失是原因还是结果？

## 修订历史

- 2026-06-23 · 创建 · 基于《静默的预测机器》(#59) · 初始置信度：高

## 来源文章

- [[2026-06-23-cerebellum-motor-learning]]

---
title: 小脑运动学习回路
slug: cerebellar-motor-learning
domain: circuits
type: mechanism
status: established
confidence: high
created: 2026-06-23
updated: 2026-06-23
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, behavior]
related: [cerebellum, purkinje-cell, long-term-depression, motor-cortex, sharp-wave-ripples]
prerequisites: [synaptic-transmission, long-term-depression, action-potential, purkinje-cell, cerebellum]
opens_questions: [Q-cb-01, Q-cb-03]
source_articles: [2026-06-23-cerebellum-motor-learning]
key_sources: ["PMID:35803588", "PMID:32866603", "PMID:36639897", "PMID:42135511"]
---

# 小脑运动学习回路 (Cerebellar Motor Learning Circuit)

> **一句话定义**：以攀爬纤维误差信号为教学输入、并行纤维–浦肯野细胞 LTD 为存储机制、深部核团为输出级的监督学习回路；最新发现揭示分子层中间神经元构成同步依赖的二级门控，确保学习的精确性与适应性。

## 当前理解

我们现在认为，小脑运动学习是目前神经科学中机制最为清晰的"误差驱动局域学习"实例之一，也是最接近工程学意义上"监督学习"的生物神经回路。

其核心架构（Marr-Albus-Ito 假说，1969–1982）：

1. **状态信号（MF → GrC → PF）**：苔藓纤维将当前感觉运动状态传入，颗粒细胞将其高维稀疏扩展为并行纤维上的稀疏模式，接触浦肯野细胞树突。
2. **误差信号（IO → CF）**：下橄榄核（IO）整合运动预测误差（如视网膜滑移、未预测的触觉），攀爬纤维以约 1 Hz 将误差信号送达浦肯野细胞。
3. **存储（PF-PC LTD）**：PF 激活（状态） + CF 触发（误差）→ LTD → PF-PC 突触减弱 → PC 放电减少 → 深部核团去抑制 → 运动输出改变以减少误差。

**双阶段学习整合（Lisberger 2020 的 4 条原则）**：
- 皮层快学（PF-PC LTD）：快速但不稳定，回路皮层小脑
- 核团慢固（MF-DCN LTP 等）：缓慢但稳定，运动记忆"迁移"到深部核团

**分子层中间神经元（MLI）门控（Bonnan 2023, Park 2026 的新层次）**：
- MLI（篮状细胞+星形细胞）持续抑制 PC，防止 CF 自发放电（1 Hz）触发无效 LTD
- CF 不只接触 PC，还接触一类特殊 MLI 亚型（去抑制 MLI），该亚型抑制抑制 PC 的 MLI
- 当多条 CF 同步放电（代表明确误差）时：去抑制 MLI 强激活 → MLI 对 PC 的抑制解除 → PC Ca²⁺↑↑ → LTD 有效触发
- 单条随机自发放电不足以驱动同步依赖的去抑制 → LTD 不触发 → 防误适应

## 关键机制（分层展开）

### 分子层：LTD 级联
- 并行纤维 → mGluR1 + AMPA → 小 ΔCa²⁺
- 攀爬纤维 → P/Q 型 VGCC → 大 ΔCa²⁺（复合脉冲）
- 共激活 → PKC → GluA2 磷酸化 → AMPA 内吞 → 突触减弱
- 时序窗口：PF 先于 CF 约 50–300 ms

### 回路层：MLI 同步门控（2026 新发现）
```
下橄榄核
    ↓ (CF，同步放电)
去抑制 MLI ──抑制──▶ 普通 MLI ──抑制──▶ PC
              (解除 MLI 对 PC 的抑制)
```
CF 同步性 → 去抑制 MLI 整合 → PC 抑制解除 → CF 信号有效 → LTD

### 系统层：双阶段巩固
```
早期：皮层 LTD（快速，不稳定）
         ↓ (PC → DCN 的反复激活)
晚期：DCN 可塑性（慢速，稳定）
```
类比：海马（快速灵活） → 皮层（慢速稳定）的系统巩固

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| CF 驱动 PF-PC LTD 是 VOR 学习的必要机制 | VOR 适应实验（多物种）+ mGluR1 KO | PMID:32866603 | 高 |
| 皮层→核团的学习转移（双阶段） | 选择性皮层/核灭活 + 追踪实验 | PMID:32866603 | 高 |
| MLI 活动模式在 VOR 学习后改变（MLI 学习） | VOR 适应 + 多点位电生理记录 | PMID:36639897 | 高 |
| 光遗传沉默 MLI → 阻断 VOR 运动记忆表达 | 选择性 optogenetics 沉默 | PMID:36639897 | 高 |
| CF 同步性通过二级去抑制 MLI 门控学习 | 连接组学 + 功能记录 + 建模 + 行为（小鼠）| PMID:42135511 | 中（2026，尚待重复） |

## 连接

- [[purkinje-cell]] — 回路中的核心整合器和存储位点
- [[cerebellum]] — 所在脑区
- [[long-term-depression]] — LTD 是回路中的存储机制
- [[motor-cortex]] — 小脑→DCN→丘脑→运动皮层的输出回路
- [[sharp-wave-ripples]] — 类比：海马 SPW-R 的系统巩固与小脑皮层→核团的转移
- [[predictive-coding]] — 小脑内部模型是大脑预测编码的最清晰例子之一
- [[disinhibitory-circuit]] — MLI 去抑制回路（与皮层 VIP-SST-PYR 去抑制回路的类比）

## 未解问题

- Q-cb-01：认知小脑是否也使用 CF/LTD 机制？
- Q-cb-03：多个并行运动技能的学习如何避免回路干涉？

## 修订历史

- 2026-06-23 · 创建 · 基于《静默的预测机器》(#59) · 综合 Hull & Regehr 2022, Lisberger 2020, Bonnan 2023, Park 2026 · 初始置信度：高

## 来源文章

- [[2026-06-23-cerebellum-motor-learning]]

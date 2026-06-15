---
title: 浦肯野细胞
slug: purkinje-cell
domain: neurons
type: structure
status: established
confidence: high
created: 2026-08-01
updated: 2026-10-11
revision_count: 2
dimensions: [cellular, synaptic, microcircuit, brain-region]
related: [cerebellum, cerebellar-ltd, climbing-fiber-error-signal, deep-cerebellar-nuclei, parallel-fiber]
prerequisites: [action-potential, gaba, ampa-receptor, cerebellum]
opens_questions: [Q-cb-01, Q-cb-04]
source_articles: [2026-08-01-cerebellar-ltd-purkinje-motor-learning, 2026-10-11-granule-cell-parallel-fiber-expansion-coding]
key_sources: ["PMID:23440175", "PMID:21482355", "PMID:30069835", "PMID:34219651"]
---

# 浦肯野细胞（Purkinje Cell）

> **一句话定义**：小脑皮层唯一的输出神经元——形如平行展开扇面的超大型 GABAergic 细胞，同时接受 ~15 万根平行纤维（弱输入）和 1 根攀爬纤维（强教师信号），通过整合两路信息在 PF-PC 突触处发生 LTD，并经 GABA 抑制深部小脑核（DCN）调节运动与认知。

## 当前理解

浦肯野细胞（Purkinje Cell, PC）是小脑皮层中最具标志性的细胞类型。它们形成一个单神经元层（浦肯野细胞层），其巨大而扁平的树突扇面（dendritic fan）垂直于平行纤维的走向，使每个 PC 能够采样来自数十万个颗粒细胞的信息。

我们现在认为，PC 的核心功能是**整合计划信号与误差信号**：约 15 万根平行纤维（PF）携带颗粒细胞重新编码的感觉运动信息（计划/状态），而 1 根攀爬纤维（CF）携带来自下橄榄核的运动误差信号。当两路信号在特定时间窗口内同时到达，PF-PC 突触发生 LTD（AMPAR 内吞），使 PC 对该运动模式的响应减弱，最终降低对 DCN 的 GABA 抑制，解除 DCN 对运动命令的抑制。

PC 的输出完全通过**GABAergic 抑制**实现——它们通过持续的简单放电（~50–100 Hz）维持对 DCN 的强烈抑制，运动学习的关键就是在特定条件下暂时降低这种抑制。

## 关键形态与电生理特征

### 形态

- **树突扇面**：高度分支的树突树在矢状面内展开，与冠状面内走行的平行纤维垂直，确保最大的 PF 覆盖。
- **树突棘密度**：PC 拥有大脑中最密集的树突棘之一，约 150,000–175,000 个，绝大多数为 PF 突触。
- **单根 CF 单一支配**：成年后，每个 PC 只被一根 CF 单一支配（单一化，mono-innervation），这是发育中突触竞争的结果。

### 电生理

- **简单放电（simple spikes）**：颗粒细胞 PF 输入驱动，50–100 Hz 的自发放电。
- **复杂放电（complex spikes）**：CF 激活触发，约 1 Hz（极为稀疏），形态复杂（初始大幅动作电位+多个小幅去极化波）。LTD 诱导依赖于 CF 激活后 Ca²⁺ 内流。

## 关键机制

### LTD 的输入-输出逻辑

```
平行纤维（PF）
    ↓ mGluR1 + AMPAR
浦肯野细胞树突棘 ←── 攀爬纤维（CF，复杂放电，Ca²⁺ 内流）
    ↓ LTD（PKC→AMPAR 内吞）
浦肯野细胞输出减弱（简单放电↓）
    ↓ GABA
深部小脑核（DCN）抑制减少→运动命令去抑制
```

### 简单放电 vs 复杂放电的双重信息流

| 参数 | 简单放电 | 复杂放电 |
|------|---------|---------|
| 驱动来源 | 颗粒细胞（PF）、内在节律 | 下橄榄核（CF，1:1 支配）|
| 频率 | 50–100 Hz | ~1 Hz（稀疏）|
| 波形 | 典型动作电位 | 复杂多峰波 |
| 功能 | 编码运动状态/计划 | 运动误差信号，触发LTD |
| 可塑性作用 | 学习后减弱（LTD 结果）| LTD 诱导信号 |

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| PC 是小脑皮层唯一输出，通过 GABA 抑制 DCN | 解剖学+电生理（多物种） | 教科书级 | 极高 |
| 每个成年 PC 由单根 CF 单一支配 | 多电极记录 + 基因标记 | PMID:18323688 | 高 |
| CF 激活在 LTD 诱导中起 "教师信号" 作用 | mGluR1 KO 小鼠（LTD 消失）+ CF 选择性损毁 | PMID:7954803 | 高 |
| 阻断 LTD（AMPAR 内吞）不影响运动学习 | 三种突变小鼠（PICK1 KO 等） | PMID:21482355 | 高 |
| 眼跳适应后 62% PC 的简单放电模式改变 | 体内记录 + 适应训练 | PMID:30995136 | 高 |

## 连接

- [[cerebellum]] — PC 是小脑皮层输出节点，整个小脑运动学习的核心
- [[cerebellar-ltd]] — LTD 发生在 PF-PC 突触，PC 是效应细胞
- [[climbing-fiber-error-signal]] — CF 是 PC 的"教师"（每 PC 仅 1 根）
- [[deep-cerebellar-nuclei]] — PC 通过 GABA 抑制 DCN，DCN 是小脑输出通道
- [[granule-cell]] — 颗粒细胞经 PF 提供 PC 的主要兴奋性输入（~150,000 突触）
- [[parallel-fiber]] — 颗粒细胞轴突，在分子层沿冠状面延伸 3-7mm，顺序接触 300-500 个 PC

## 未解问题

- **Q-cb-01**：PC 简单放电在运动学习中是否编码预测误差本身（前向模型预测），还是只编码运动状态？
- **Q-cb-04**：PC 的哪种可塑性形式（LTD、内在可塑性、MLI 介导的抑制）在不同学习范式中分别是必要的？

## 修订历史

- 2026-08-01 · 创建 · 基于《教师信号的困境》（文章#100）· 初始置信度：高（形态/电生理 established，LTD 相关机制 contested）
- 2026-10-11 · 修订（rev1→rev2）· 基于《宇宙中最大的展开器》(#173) · 新增 granule-cell 和 parallel-fiber 链接；澄清平行纤维接触数（~150,000-175,000/PC）和几何关系；source_articles 补充 2026-10-11

## 来源文章

- [[2026-08-01-cerebellar-ltd-purkinje-motor-learning]]
- [[2026-10-11-granule-cell-parallel-fiber-expansion-coding]]

---
title: 穿通径路（颞氨通路）
slug: temporoammonic-path
domain: circuits
type: structure
status: established
confidence: high
created: 2026-09-24
updated: 2026-09-24
revision_count: 1
dimensions: [microcircuit, brain-region, synaptic]
related: [entorhinal-ca1-circuit, entorhinal-cortex, place-cells, memory-consolidation, theta-oscillations, btsp, ltp]
prerequisites: [entorhinal-cortex, hippocampal-circuit]
opens_questions: [Q-ec-ca1-02, Q-ec-ca1-03]
source_articles: [2026-09-24-entorhinal-ca1-dual-stream-theta-gate]
key_sources: ["PMID:11961555", "PMID:15470431", "PMID:16237162", "PMID:18215625", "PMID:37816349"]
---

# 穿通径路（颞氨通路）(Temporoammonic Path, TA Path)

> **一句话定义**：EC 第三层（EC-III，包括 MEC-III 和 LEC-III）直接投射至 CA1 远端顶端树突（stratum lacunosum-moleculare，SLM）的回路分支，是内嗅皮层向 CA1 传递当前感觉情境精准信息的直接通路，与 CA3 Schaffer 侧支经 theta 时序门控整合，共同构建 CA1 的精准空间表征。

## 当前理解

我们现在认为，TA path 是一条**功能上复杂的双向调制器**，而非简单的感觉前馈通路：

1. **正常情况下被抑制**：SLM 区 OA 型抑制性中间神经元持续向 TA path 突触前末梢施加 GABA_B 预突触抑制，将 TA 信号锁死于远端树突，无法独立驱动 CA1 放电
2. **theta 门控激活**：当 CA3 Schaffer 侧支先于 TA path 约半个 theta 周期（~40–60 ms）激活，引起 NMDA 受体介导的局部去极化 + GABA_B 预突触去抑制，TA 信号才能穿透至胞体
3. **空间精准功能**：MEC-III 输入传递当前环境坐标；LEC-III 输入传递当前奖励目标位置；EC-III 损伤 → CA1 场所场变大、不精准（Brun et al. 2008）
4. **记忆巩固功能**：TA path 在学习后约 3 周内必须保持完整，以支持长期记忆的系统巩固（Remondes & Schuman 2004）

## 关键机制

### 解剖特征

- 起点：EC 第三层（MEC-III 和 LEC-III）锥体细胞
- 终点：CA1 的 stratum lacunosum-moleculare（SLM）——远端顶端树突，距胞体约 300–400 μm
- 到达 CA1 顶端树突的最远端，与 CA1→EC 的反馈联系共同构成海马皮层通路中的直接往返回路

### 时序 AND 门的突触机制（Ang et al. 2005）

| 步骤 | 分子机制 |
|------|---------|
| 1. Schaffer 先激活 | NMDA 受体激活 → SR 局部去极化扩散到更远端 |
| 2. GABA_B 去抑制 | Schaffer 活动触发 OA 中间神经元上的 GABA_B → 减少 TA 突触前 GABA 释放 |
| 3. TA path 信号穿透 | 在 ~40–60 ms 的去抑制窗口内，TA 信号不再被预突触抑制，加上树突去极化背景，成功穿透至胞体 |
| 4. OA 反馈隔离 | 短暂整合窗口后，OA 中间神经元恢复前馈抑制，防止过度整合 |

### 双向可塑性（Remondes & Schuman 2002）

TA path 在 SLM 的突触既能发生 LTP 也能发生 LTD——"易抑制，难增强"的特性（低频刺激易诱发 LTD）使 TA path 在默认状态偏向于抑制性调制，只在 theta 门控条件下选择性增强。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| TA path 损伤 → CA1 场所场变大 | MEC-III 毁损 + CA1/CA3 记录 | PMID:18215625 | 高 |
| TA path 是时序 AND 门的一路输入 | 离体膜片钳 + 选择性刺激 | PMID:16237162，PMC:2048747 | 高 |
| TA path 损伤 → 3 周后长期记忆受损 | 电解毁损 + 水迷宫时间点测试 | PMID:15470431 | 高 |
| TA path 可双向调制 CA1 可塑性 | 离体切片 LTP/LTD 诱导 | PMID:11961555 | 中-高 |
| MEC vs LEC 在 TA path 中传递不同内容 | 体内 2P 轴突成像 + DREADDs | PMID:37816349，PMC:11490304 | 高 |

## 连接

- [[entorhinal-ca1-circuit]] — TA path 是双流回路中直接流的解剖实体
- [[entorhinal-cortex]] — TA path 的起点为 EC-III（MEC-III/LEC-III）锥体细胞
- [[place-cells]] — TA path 是维持 CA1 场所场空间精准度的关键
- [[memory-consolidation]] — TA path 在巩固窗口内持续传递皮层→海马复习信号
- [[theta-oscillations]] — theta 振荡在波峰相位驱动 TA path 输入，在波谷相位驱动 CA3 输入
- [[btsp]] — TA path 传递触发 BTSP 平台事件的 EC 信号
- [[ltp]] — TA path 突触在 theta 门控条件下可以发生 LTP

## 未解问题

- Q-ec-ca1-02：人类 TA path 的时序 AND 门机制是否保守？手术中电生理能否验证？
- Q-ec-ca1-03：TA path 巩固窗口内的"复习信号"性质（离线重播 vs 清醒监督？SWR 相关？）

## 修订历史

- 2026-09-24 · 创建 · 基于《时序之门》文章(#154) · 初始置信度：高

## 来源文章

- [[2026-09-24-entorhinal-ca1-dual-stream-theta-gate]]

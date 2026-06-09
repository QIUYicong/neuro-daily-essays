---
title: D1/D2 多巴胺受体信号
slug: d1-d2-receptor-signaling
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-06
updated: 2026-06-09
revision_count: 2
dimensions: [molecular, synaptic, cellular, microcircuit, brain-region]
related: [dopamine-reward-prediction-error, direct-indirect-pathway, vta, substantia-nigra, dopamine-systems-anatomy, working-memory, prefrontal-cortex, basal-ganglia, parkinsons-disease, striatal-synaptic-plasticity, endocannabinoid-signaling, three-factor-learning-rule]
prerequisites: [synaptic-transmission, action-potential, g-protein-signaling]
opens_questions: [Q-d1-inverted-u-mechanism, Q-darpp32-network-state, Q-striatum-a2a-d2-dimer]
source_articles: [2026-06-06-dopamine-systems-anatomy, 2026-06-09-striatum-d1-d2-plasticity-dichotomy]
key_sources: ["PMID:30716356", "PMID:24130517", "PMID:35389678", "PMID:18687967", "PMID:22544310"]
---

# D1/D2 多巴胺受体信号 (D1/D2 Dopamine Receptor Signaling)

> **一句话定义**：多巴胺通过 D1 类（D1、D5）和 D2 类（D2、D3、D4）受体分别偶联 Gαs/olf（→cAMP↑→PKA↑）和 Gαi/o（→cAMP↓→PKA↓）产生相反的细胞内信号，分别驱动直接通路的兴奋（D1-MSN）和间接通路的去抑制（D2-MSN），是多巴胺在同一靶区产生对立功能效应的分子基础。

## 当前理解

我们现在认为，多巴胺的双向功能（奖励促进运动 vs 厌恶抑制运动；工作记忆增强 vs 损伤）的核心来源是 **D1 类与 D2 类受体的相反 G 蛋白信号逻辑**，而非多巴胺本身的浓度差异。

**D1 类受体（D1、D5）**
- 偶联 Gαs 或 Gαolf（嗅球特异）蛋白
- 激活 → 腺苷酸环化酶（AC）↑ → cAMP↑ → PKA↑
- PKA 关键底物：DARPP-32（Thr34 磷酸化 → 抑制 PP-1 → 放大下游 PKA 效应）、AMPAR GluA1 亚基（Ser845 磷酸化 → AMPAR 插入突触 → 快速兴奋性增强）
- 净效应：增强细胞兴奋性，促进突触增强（LTP 方向），驱动直接通路激活

**D2 类受体（D2、D3、D4）**
- 偶联 Gαi/o 蛋白
- 激活 → AC 被抑制 → cAMP↓ → PKA↓
- PKA 效应减弱：DARPP-32 Thr34 去磷酸化 → PP-1 活化（去磷酸化 AMPAR → 突触弱化）
- Gβγ 亚基直接效应：开放 GIRK 通道（K⁺ 外流 → 超极化）、抑制 L 型 Ca²⁺ 通道
- 净效应：降低细胞兴奋性，抑制突触增强，压制间接通路的 MSN 活性

**DARPP-32 是 D1/D2 信号的汇聚开关节点**：
- D1 激活 → Thr34 磷酸化 → PP-1 抑制 → 多种底物保持磷酸化状态（兴奋增强）
- D2 激活 → Thr34 去磷酸化 → PP-1 活化 → 多种底物去磷酸化（兴奋减弱）
- DARPP-32 本身还有 Thr75 位点（被 Cdk5 磷酸化 → 抑制 PKA 本身，形成负反馈）

**D2 受体的三重角色（Gallo 2019）**：
1. **突触后 D2R**（D2-MSN 间接通路抑制）
2. **突触前 D2 自受体**（多巴胺神经元终末/胞体，负反馈调控 DA 合成与释放量）
3. **皮层谷氨酸终末 D2R**（前额叶→纹状体谷氨酸传递的"音量旋钮"）

**前额叶皮层的 D1 受体倒 U 型**：
工作记忆表现与 PFC D1R 激活强度呈负二次曲线关系（Weber 等 2022，R²=0.26）：
- 过少 D1 激活：持续激活回路（吸引子）无法维持，工作记忆衰减
- 最优 D1 激活：PKA→AMPAR Ser845 磷酸化增强树突棘 NMDA 介导电流，稳定吸引子状态
- 过多 D1 激活：PKA 过度磷酸化 HCN 通道，削弱持续性去极化，信噪比崩溃

## 关键机制

### cAMP-PKA-DARPP-32 级联（D1 信号主干）

```
D1R 激活
 → Gαs/olf 激活腺苷酸环化酶
 → [cAMP] ↑（10-100μM 范围）
 → PKA 调节亚基脱落，催化亚基活化
 → DARPP-32 Thr34 磷酸化 → PP-1 抑制 → 放大 PKA 效应
 → GluA1 Ser845 磷酸化 → AMPAR 膜插入增加
 → ERK 磷酸化 → 转录因子 CREB 磷酸化 → 基因表达
```

### Gβγ 效应器（D2 信号辅助臂）

```
D2R 激活
 → Gαi/o 解离 → Gβγ 释放
 → GIRK 通道（Kir3.x）激活 → K⁺ 外流 → 超极化（约 −10 mV）
 → L 型 Cav1.2/1.3 通道抑制 → Ca²⁺ 内流减少 → 突触可塑性压制
```

### 亲和力差异决定信号模式
- D2R 对多巴胺亲和力（Kd ~1 nM）远高于 D1R（Kd ~1-10 μM）
- 低浓度基线多巴胺（紧张性放电，~100 nM）优先激活 D2R（包括自受体，形成负反馈）
- 高浓度相位性多巴胺爆发（~1-10 μM）才能有效激活 D1R（直接通路兴奋）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| D1→Gs→cAMP↑→PKA；D2→Gi→cAMP↓ | 膜片钳 + 药理 + 遗传标记 MSN | PMID:24130517; PMID:30716356 | 确立 |
| DARPP-32 Thr34 磷酸化是 D1 信号放大器 | 遗传敲除 + 磷酸化检测 | PMID:24130517 | 高 |
| D2 自受体敲除→DA 过度释放+过度运动 | 条件性基因敲除 | PMID:30716356 | 高 |
| PFC D1R 激活与工作记忆倒 U 型（R²=0.26） | 75 项研究荟萃分析 | PMID:35389678 | 高 |

## 连接

- [[direct-indirect-pathway]] — D1-MSN 驱动直接通路（Go），D2-MSN 驱动间接通路（No-Go）
- [[dopamine-reward-prediction-error]] — D1/D2 是 RPE 信号下游效应的执行器
- [[working-memory]] — PFC D1 受体的倒 U 型门控工作记忆信噪比
- [[basal-ganglia]] — D1/D2 分布的解剖基础在纹状体 MSN 中
- [[parkinsons-disease]] — DA 耗竭→D1/D2 平衡崩溃→直接/间接通路失衡
- [[striatal-synaptic-plasticity]] — D1/D2 信号如何产生相反的 STDP 极性（核心延伸）
- [[three-factor-learning-rule]] — D1/D2 极性逻辑是三因素规则在纹状体的实例化

## 未解问题

- Q-d1-inverted-u-mechanism：PFC D1 倒 U 型翻转的精确分子节点（HCN 磷酸化？AMPAR 内吞？cAMP 超激活导致 PP-2A 活化？）各实验室的结论是否一致？
- Q-darpp32-network-state：DARPP-32 磷酸化状态的网络级动态（是否存在局部回路级同步 DARPP-32 状态转换？）

## 修订历史

- 2026-06-06 · 创建 · 基于《奖励、运动与认知的统一信使》(#15) · 初始置信度：高
- 2026-06-09 · 修订 · 基于"纹状体极性开关"文章 · 新增：D1-MSN vs D2-MSN 的 STDP 极性差异（Shen 2008）；内源性大麻素（eCB/2-AG/DAGLα/CB1）LTD 通路；PD 模型下极性逆转；A2A 腺苷受体在 D2-MSN LTP 中的角色；新增 key_sources PMID:18687967/22544310；新增关联页 striatal-synaptic-plasticity/endocannabinoid-signaling

## 来源文章

- [[2026-06-06-dopamine-systems-anatomy]]
- [[2026-06-09-striatum-d1-d2-plasticity-dichotomy]]

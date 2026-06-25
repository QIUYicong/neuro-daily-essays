---
title: LHb-RMTg-VTA 反奖励回路
slug: lhb-rmtg-circuit
domain: circuits
type: mechanism
status: established
confidence: high
created: 2026-09-19
updated: 2026-09-19
revision_count: 1
dimensions: [microcircuit, brain-region, behavior, cognition, disease]
related: [lateral-habenula, dopamine-reward-prediction-error, basal-ganglia, striatal-direct-indirect-pathway, serotonin-raphe-system]
prerequisites: [lateral-habenula, dopamine-reward-prediction-error, synaptic-transmission]
opens_questions: [Q-lhb-02, Q-rmtg-heterogeneity]
source_articles: [2026-09-19-lateral-habenula-anti-reward-depression]
key_sources: ["PMID:21832176", "PMID:17522629", "PMID:40769282"]
---

# LHb-RMTg-VTA 反奖励回路 (Anti-Reward Circuit)

> **一句话定义**：以外侧缰核（LHb）为起点，经喙侧内侧被盖核（RMTg）为 GABA 中继，最终抑制腹侧被盖区（VTA）多巴胺神经元的三级回路，是大脑主动编码和传递"惩罚信号/负预测误差"的核心通路。

## 当前理解

我们现在认为，LHb→RMTg→VTA 是大脑实现负预测误差（negative reward prediction error, nRPE）信号传递的专用通路，与 VTA→纹状体的正 RPE 通路形成双轨并行的奖惩计算系统。

**三级结构**：
1. **LHb**（谷氨酸能，兴奋）→ 激活 RMTg
2. **RMTg**（GABAergic，抑制）→ 抑制 VTA 多巴胺神经元
3. **VTA 多巴胺神经元**（dopaminergic）→ 多巴胺释放被抑制 → 纹状体 MSN "无奖励"状态

灵长类电生理和损毁实验（Hong et al. 2011, PMID:21832176, PMC3315151）证实：RMTg 损毁削弱 LHb 对 VTA 的下行抑制，且 RMTg 神经元本身也携带 nRPE 信号（在 LHb 之后约 0-10 ms）。

**RMTg 作为二级整合器**：除被 LHb 驱动外，RMTg 可能接受来自其他来源的抑制信号（如丘脑底核，STN），形成对 VTA 抑制的更广泛整合。

## 关键机制

### 信号流程

```
负事件/奖励缺失
      ↓
LHb 神经元爆发（谷氨酸）
      ↓
RMTg 神经元激活（GABA）
      ↓
VTA 多巴胺神经元被抑制（firing rate → 接近0）
      ↓
纹状体/NAc 多巴胺释放减少
      ↓
"无奖励"学习信号 / 行为抑制
```

### 与 LHb→DRN 直接通路的分工

- LHb→RMTg→VTA：主要驱动即时多巴胺相关的 nRPE 学习
- LHb→DRN（直接）：调控血清素，影响持续情绪基调和焦虑

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| RMTg 是 LHb→VTA 的必要中继 | 灵长类逆行追踪 + 损毁实验 | PMID:21832176 (PMC3315151) | 高 |
| LHb→RMTg 是谷氨酸兴奋性，RMTg→VTA 是 GABA 抑制性 | 电生理 + 解剖 | PMID:40769282 | 高 |

## 连接

- [[lateral-habenula]] — 回路起点，编码 nRPE 和负价事件
- [[dopamine-reward-prediction-error]] — 此回路是负 RPE 信号的解剖实现
- [[basal-ganglia]] — GPi/EPN→LHb 是基底节信息进入此回路的入口

## 未解问题

- Q-lhb-02：GPi→LHb 是否含有谷氨酸成分（GPi 经典为 GABA）？
- Q-rmtg-heterogeneity：RMTg 是否存在功能亚群，分别对应不同的输出目标和计算功能？

## 修订历史

- 2026-09-19 · 创建 · 基于文章 #149 外侧缰核 · 初始置信度：高

## 来源文章

- [[2026-09-19-lateral-habenula-anti-reward-depression]]

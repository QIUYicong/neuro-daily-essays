---
title: 内侧隔核
slug: medial-septum
domain: systems
type: region
status: established
confidence: high
created: 2026-09-18
updated: 2026-09-18
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, behavior, cognition]
related: [theta-oscillations, theta-sequences, theta-phase-precession, hippocampal-circuit, place-cells, acetylcholine, gaba, memory-consolidation]
prerequisites: [theta-oscillations, hippocampal-circuit, action-potential]
opens_questions: [Q-ts-04]
source_articles: [2026-09-18-theta-sequences-episodic-memory]
key_sources: ["PMID:32526196", "PMID:37479632"]
---

# 内侧隔核 (Medial Septum / MS-DBB)

> **一句话定义**：基底前脑内侧隔核-斜角带核（MS-DBB）是海马θ振荡的主要起搏器，通过胆碱能和GABAergic投射向海马-内嗅皮层回路提供θ相位坐标框架，是θ序列空间组织和情节记忆编码的节律性基础设施。

## 当前理解

我们现在认为，内侧隔核不只是一个"速度按钮"（传统观点：MS加速=θ加快），而是**海马θ序列相位框架的守护者**：MS维护θ振荡的相位连贯性（coherence），使海马各区域场所细胞能以一致的相位坐标进行空间序列编码。

关键洞察（Petersen & Buzsáki 2020，PMID:32526196）：精准MS冷却实验表明：
- 距离-时间压缩（distance-time compression）随θ变慢而降低
- **距离-相位压缩（distance-phase compression）保持不变**
- 行为错误率增加约3倍

这意味着：θ序列的信息内容（空间序列）以**相位**为坐标，不以绝对时间为坐标。MS维持相位框架，但不直接编码序列内容。

## 关键机制

### 解剖结构

MS-DBB包含三类主要投射神经元：
- **胆碱能（ACh）神经元**：投射至海马（CA1/CA3/DG）和内嗅皮层；通过mAChR调节突触可塑性和θ产生
- **GABAergic神经元**（包含Parvalbumin+）：投射至海马中间神经元；节律性抑制调控θ相位
- **谷氨酸能神经元**（少量）：投射至海马锥体细胞

### θ起搏机制

MS-DBB通过两套机制驱动海马θ：
1. **直接胆碱能调制**：ACh激活海马mAChR→增强海马锥体细胞兴奋性→支持θ产生的网络状态
2. **GABAergic节律性抑制**：PV+ GABA神经元以θ频率节律性放电→抑制海马中间神经元→产生去抑制节律

### MS与行为的关系

- **主动探索/运动**：MS激活→θ出现（4–12 Hz）
- **静止/非REM睡眠**：MS沉默→SWR取代θ
- **REM睡眠**：MS激活→θ再现（与情绪记忆巩固相关）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| MS是θ振荡的主要起搏器 | MS损毁/冷却导致θ消失/减弱 | 多篇综述+PMID:32526196 | 高 |
| MS冷却保留距离-相位压缩（P=0.92）但增加行为错误3倍（P=10⁻⁶） | 精准低温探针+64通道硅探针，n=5只大鼠 | PMID:32526196，PMCID:PMC7442698 | 高 |
| 距离-时间压缩随MS冷却降低（P=0.02） | 同上 | PMID:32526196 | 高 |
| MS-海马通路对空间记忆至关重要 | 行为学+损毁+化学遗传学 | 多篇文献综述（PMID:37479632） | 高 |

## 连接

- [[theta-oscillations]] — MS-DBB是θ振荡的主要驱动源和相位守护者
- [[theta-sequences]] — MS提供θ序列的相位坐标框架；其节律性决定了序列的时间组织
- [[theta-phase-precession]] — 相位进动依赖MS维持的θ相位框架
- [[hippocampal-circuit]] — MS投射至海马全长（CA1/CA3/DG）和内嗅皮层
- [[place-cells]] — 场所细胞的相位进动受MS θ相位调控
- [[memory-consolidation]] — MS的胆碱能投射调控海马突触可塑性，影响记忆编码效率

## 未解问题

- **Q-ts-04**（中优先）：MS冷却后行为错误增加3倍，但相位框架（距离-相位压缩）保留。错误的确切原因是什么？可能候选：θ频率变化影响θ-γ耦合→工作记忆读取出错；MS胆碱能释放减少→突触可塑性改变；跨θ周期的序列"拼接"出错

## 修订历史

- 2026-09-18 · 创建 · 填补dangling reference（theta-oscillations页面引用的medial-septum） · 基于《θ序列》(#148)文章 · 主要来源：Petersen & Buzsáki 2020 PMID:32526196 · 初始置信度：高

## 来源文章

- [[2026-09-18-theta-sequences-episodic-memory]]

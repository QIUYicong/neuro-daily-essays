---
title: 时间细胞
slug: time-cells
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-07-26
updated: 2026-07-26
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, cognition]
related: [place-cells, grid-cells, cognitive-map, hippocampal-circuit, sharp-wave-ripples, theta-oscillations, theta-phase-precession, episodic-memory, interval-timing, pattern-completion]
prerequisites: [hippocampal-circuit, place-cells, action-potential]
opens_questions: [Q-timecell-mechanism, Q-timecell-longscale, Q-timecell-aging, Q-timecell-human-task]
source_articles: [2026-07-26-hippocampal-time-cells-temporal-coding]
key_sources: ["PMID:21867888", "PMID:25269553", "PMID:30349104", "PMID:39322671", "PMID:36585486"]
---

# 时间细胞 (Time Cells)

> **一句话定义**：海马 CA1/CA3（及内嗅皮层、前额叶）中在延迟间隔的特定时刻选择性放电的神经元——它们逐秒按序激活，集体拼出一张连续的神经时间地图，是情节记忆"几时"维度的神经底物。

## 当前理解

我们现在认为，海马不只维护一张空间认知地图，还维护一张**时间认知地图**。时间细胞（time cells）是这张时间地图的基本单元：就像场所细胞（place cells）在特定空间位置激活，时间细胞在延迟期间的特定时刻激活，每个细胞有自己的"偏好时刻"（preferred time），不同细胞的偏好时刻从延迟开始连续分布到延迟结束，形成覆盖整个延迟的序列。

时间细胞最重要的特性是**时间重映射**（temporal remapping）：当延迟长度改变时，整个序列按比例拉伸或压缩，类比场所细胞在不同空间环境中的重映射。这说明时间细胞编码的是**相对时间结构**（时间比例），而非绝对时间长度。

时间细胞不只存在于海马：内侧前额叶皮层（mPFC）、内侧内嗅皮层（mEC）均有类似的时序激活神经元，提示时间编码是海马-前额叶回路的分布式属性。2023 年的蝙蝠研究（Omer et al.）揭示了两种亚型：**情境性时间细胞**（在不同空间情境产生不同时序序列）和**纯粹时间细胞**（与情境无关，提供更通用的时间坐标）。

2024 年，Tacikowski 等人在人类颅内记录中直接证明了时间细胞的存在，且人类海马/EC 神经元的活动能编码图像序列的时间结构并表现出时间压缩重播——与啮齿类动物的时间细胞在结构上高度一致。

## 关键机制

### 1. 时序覆盖与精度递减

时间细胞的激活时刻在延迟早期更密集（精度更高）、在晚期更稀疏，精度随时间递减——类似 Weber-Fechner 定律。这可能反映了时间表征的积累噪声：随时间推移，神经状态的不确定性增加，时间精度自然下降。

### 2. 时间细胞 vs 持续活动

时间细胞不同于 PFC 的"持续活动"神经元（在整个延迟持续高频放电）：
- 持续活动编码的是"某信息正在被保持"，不编码时间进展
- 时间细胞编码的是"现在是延迟中的哪个时刻"，提供动态时间坐标

### 3. 机制假说（争议中）

**网络机制**：mEC 的连续吸引子网络动力学驱动激活状态逐步"漂移"，产生有序序列。Heys & Dombeck 2018 发现 mEC 在静止期（无空间运动输入）仍能维持时间序列，支持网络内在动力学驱动。

**单细胞慢传导机制**：持续性 Na⁺ 电流（I_Na,P）和超极化激活电流（I_h）的差异可让不同神经元在不同时刻自发激活，无需强依赖网络协调。

两种机制并不互斥，相对权重待实验区分。

### 4. 与 SWR 的关系

时间细胞的序列在尖波涟漪（SWR）期间以约 20 倍速重播，与场所细胞序列的重播方式相同。这种重播将情节记忆的时间结构写入系统巩固过程，是情节记忆时间轴离线固结的物理机制。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| CA1 有时序放电的时间细胞，集合覆盖延迟全程 | 大鼠 TPOT 任务 + 微丝记录 | MacDonald et al. 2011 (PMID:21867888) | 高 |
| 延迟长度变化时时序序列按比例拉伸 | 对照延迟长度变化的 TPOT 实验 | MacDonald et al. 2011 | 高 |
| CA3 也有时间细胞；CA3 时间精度更快递减 | 大鼠 CA3 记录 | Salz et al. 2016 (PMID:27413157) | 高 |
| mEC 在静止期有时序激活神经元（与网格细胞不同亚回路） | 小鼠头固定双光子 Ca²⁺ 成像 | Heys & Dombeck 2018 (PMID:30349104) | 高 |
| 两类时间细胞：情境性（情境绑定）vs 纯粹（情境无关） | 蝙蝠自由飞行多极记录 | Omer et al. 2023 (PMID:36585486) | 高 |
| 人类 MTL 神经元编码图像序列时间结构，有时间压缩重播 | 颅内 SEEG 单神经元记录 | Tacikowski et al. 2024 (PMID:39322671) | 高 |
| mPFC 也有时序放电神经元，精度衰减模式相似 | 大鼠 DNMS 任务 + mPFC 记录 | Tiganj et al. 2017 (PMID:29145670) | 中-高 |
| mEC 失活选择性破坏 CA1 时间编码（不影响空间） | 化学遗传学失活 mEC | Robinson et al. 2017 (PMID:28434800) | 中（**争议**：Sabariego 2019 反驳） |
| mEC 损伤后 CA1 时间细胞数量不减少 | mEC 切除损伤 + CA1/茎部记录 | Sabariego et al. 2019 (PMID:31056352) | 中（**争议**：与 Robinson 2017 冲突） |

## 连接

- [[place-cells]] — 空间维度的类比：场所细胞编码"哪里"，时间细胞编码"几时"
- [[cognitive-map]] — 时间细胞是认知地图时间维度的神经底物
- [[hippocampal-circuit]] — 时间细胞主要位于 CA1/CA3，与海马三突触回路功能整合
- [[sharp-wave-ripples]] — SWR 期间时间细胞序列以 20 倍速重播
- [[episodic-memory]] — 情节记忆的"几时"维度依赖时间细胞
- [[interval-timing]] — 纹状体的区间计时：与海马时间细胞互补的另一套时间系统
- [[theta-phase-precession]] — θ 相位前移是毫秒级时间压缩的相关机制

## 未解问题

- Q-timecell-mechanism：时间序列的产生机制——mEC 网络驱动 vs 单细胞慢传导，如何区分？
- Q-timecell-longscale：分钟到小时的时间信息是否也有时间细胞编码？
- Q-timecell-aging：老年人时间感知减弱是否对应时间细胞精度下降？
- Q-timecell-human-task：Tacikowski 2024 用被动任务；主动情节记忆时间推断是否激活同批细胞？

## 矛盾

- C-2026-07-26-01：mEC 输入对 CA1 时间细胞的必要性——Robinson 2017（选择性必要）vs Sabariego 2019（不必要）；状态：open

## 修订历史

- 2026-07-26 · 创建 · 基于《时间的神经地图：海马时间细胞如何让大脑记住"几时"》· 初始置信度：高

## 来源文章

- [[2026-07-26-hippocampal-time-cells-temporal-coding]]

---
title: 乙酰胆碱皮层调质
slug: acetylcholine-cortex
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-12
updated: 2026-06-30
revision_count: 2
dimensions: [molecular, cellular, synaptic, brain-region, whole-brain-network, cognition]
related: [neuromodulator-systems, gain-control, working-memory, orientation-selectivity, v1-primary-visual-cortex, theta-oscillations, ltp, acetylcholine-neuromodulation, basal-forebrain, sharp-wave-ripples, attention, norepinephrine-locus-coeruleus]
prerequisites: [synaptic-transmission, nmda-receptor, action-potential]
opens_questions: [Q-ach-ne-01, Q-ach-ne-02, Q-ach-ne-04]
source_articles: [2026-06-12-neuromodulators-ach-ne, 2026-06-30-acetylcholine-neuromodulation-modes]
key_sources: ["PMID:18633352", "PMID:17920021", "PMID:20668433", "PMID:30381436", "PMID:23818597"]
---

# 乙酰胆碱皮层调质 (Cortical Acetylcholine Neuromodulation)

> **一句话定义**：基底前脑胆碱能神经元向皮层弥散（但拓扑特异性）释放乙酰胆碱，通过突触后 M1 受体增加信号增益、通过突触前烟碱受体增强感觉输入、通过相位性/紧张性双时间尺度模式实现注意资源的精确分配。

## 当前理解

我们现在认为，皮层中的乙酰胆碱（ACh）是注意和信号编码的核心调质之一。其主要来源是基底前脑（尤其是 Meynert 基底核，Ch4），投射至整个新皮层；内侧隔核（Ch1/2）和对角带（Ch3）主要投射至海马和嗅球。

**重要修正（2018）**：传统认为基底前脑投射弥散无特异性，Záborszky et al. (2018, PMID:30381436) 的高分辨率解剖研究表明投射具有**拓扑特异性**——不同基底前脑神经元选择性地靶向特定皮层区域和层。这使"弥散ACh产生空间特异性注意效果"的悖论得以部分解决。

**核心功能**：
1. 增大信噪比（增强诱发响应，不增加自发噪声）
2. 放大注意性调制（Herrero 2008 在 V1 直接证明）
3. 促进皮层去同步化（感觉编码/学习模式）
4. 优先感觉输入相对于内部预测（减少皮层反馈，增加前馈）
5. 支持持续性放电和工作记忆维持（M1 激活 → 持续放电）

## 关键机制

**突触后受体（M1，Gq 偶联）**：
- 主要位于锥体细胞（L3/L5）的胞体和树突
- 激活 M1 → PLCβ → 减少 KCNQ/IM 型 K⁺ 通道漏电流 → 膜电位去极化 → 相同输入产生更多动作电位
- 净效果：增加皮层神经元对输入的响应增益

**突触前自受体（M2，Gi 偶联）**：
- 位于胆碱能末梢，激活 M2 → 减少 ACh 释放（负反馈，防止过度激活）

**烟碱受体（nAChR）**：
- **α4β2 型**：主要位于丘脑皮质末梢（L4），激活 → 增强感觉底-上输入
- **α7 型**（Yang et al. 2013, PMID:23818597）：位于 dlPFC 谷氨酸突触（突触后），激活 → 促进 NMDA 受体参与 → 增强 PFC 工作记忆表征的稳定性

**时间模式（Parikh et al. 2007, PMID:17920021）**：
- **相位性 ACh 瞬变**：在成功检测到任务刺激时，mPFC 出现 ~5 秒的 ACh 浓度峰值；运动皮层无此瞬变。预测性：侦测前 ACh 水平预测随后是否漏检。
- **紧张性 ACh 基线**：支撑持续注意能力

**皮层状态切换**：
- 高 ACh → 皮层脑电去同步（低频慢波 → 高频 β/γ 振荡）
- 去同步状态 = 最优感觉编码/学习状态
- 低 ACh（睡眠/休息）→ 同步慢波 → 有利于记忆固化（SWR 重放）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 肌碱受体（非烟碱受体）介导 V1 注意调制 | 电泳注射 scopolamine/mecamylamine + 猕猴 V1 记录 | Herrero 2008, PMID:18633352 | 高 |
| mPFC 中 ACh 相位性瞬变在刺激检测时出现 | 高时间分辨率电化学传感器，清醒大鼠 | Parikh et al. 2007, PMID:17920021 | 高 |
| ACh 通过响应增益模型（乘法缩放）增强 V1 | 对比度灵敏度 + 受体阻断实验 | Herrero et al. 2017, PMID:29311843 | 高 |
| α7-nAChR 增强 dlPFC NMDA 依赖的工作记忆表征 | α7 阻断/激活 + 猕猴 PFC 记录 | Yang et al. 2013, PMID:23818597 | 中（灵长类数据） |
| 基底前脑 ACh 投射具有拓扑特异性 | 高分辨率解剖重建 + 神经元追踪 | Záborszky et al. 2018, PMID:30381436 | 中-高 |
| ACh 增强诱发响应、增加信噪比（多感觉皮层） | 综述：视觉/听觉/体感皮层电生理 | Edeline 2012, PMID:22866031 | 高 |

## 连接

- [[acetylcholine-neuromodulation]] — **系统级框架页**：皮层+海马 ACh 的完整双模型；本页专注皮层机制细节（受体、增益、相位性/紧张性），系统框架见彼页
- [[neuromodulator-systems]] — ACh 是四大皮层调质系统之一
- [[norepinephrine-locus-coeruleus]] — 协同调节皮层信噪比的姐妹系统
- [[gain-control]] — ACh 的核心功能之一：增益控制
- [[working-memory]] — M1 激活支持持续放电；α7-nAChR 增强 PFC NMDA 信号
- [[attention]] — ACh 是注意调制的分子介质；VIP 去抑制回路提升信噪比
- [[orientation-selectivity]] — Herrero 2008 在 V1 方向选择性神经元中直接证明 ACh 的注意调制
- [[v1-primary-visual-cortex]] — ACh 通过肌碱受体放大 V1 的注意效应
- [[theta-oscillations]] — 内侧隔核 ACh 支持海马 θ 振荡（经由 Ch1/2 投射）
- [[sharp-wave-ripples]] — 低 ACh 是 SWR 生成的分子上游：M2 受体抑制 CA3 循环兴奋的解除允许 SWR 自发爆发
- [[ltp]] — ACh 通过 M1 促进皮层可塑性（M1→NMDA 协同→LTP 阈值降低）
- [[memory-consolidation]] — 低 ACh 状态（睡眠）有利于 SWR 重放和系统固化

## 未解问题

- Q-ach-ne-01：相位性 ACh 瞬变是否直接因果地产生行为检测（光遗传学验证进行中）
- Q-ach-ne-02：烟碱/肌碱受体在人类 V1 的分工是否与猕猴相同
- Q-ach-ne-04：ACh 和 NE 在同一回路中的相互作用机制

## 修订历史

- 2026-06-12 · 创建 · 基于《注意的化学语言》一文 · 初始置信度：高
- 2026-06-30 · rev2 · 基于《乙酰胆碱：大脑的模式开关》文章 #182 · 扩展 related 列表（新增 acetylcholine-neuromodulation、basal-forebrain、sharp-wave-ripples、attention）；连接段落新增系统级框架页 [[acetylcholine-neuromodulation]] 和 [[sharp-wave-ripples]] 条目；维度新增 whole-brain-network

## 来源文章

- [[2026-06-12-neuromodulators-ach-ne]]

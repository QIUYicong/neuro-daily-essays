---
title: 乙酰胆碱神经调质系统
slug: acetylcholine-neuromodulation
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-30
updated: 2026-06-30
revision_count: 1
dimensions: [molecular, cellular, synaptic, brain-region, whole-brain-network, cognition, behavior]
related: [acetylcholine-cortex, basal-forebrain, theta-oscillations, sharp-wave-ripples, memory-consolidation, attention, precision-weighting, vip-interneurons, dopamine-reward-prediction-error, norepinephrine-locus-coeruleus, alzheimers-disease, predictive-coding, ltp, working-memory, gain-control]
prerequisites: [synaptic-transmission, action-potential, theta-oscillations, sharp-wave-ripples]
opens_questions: [Q-ach-01, Q-ach-02, Q-ach-03]
source_articles: [2026-06-30-acetylcholine-neuromodulation-modes, 2026-06-12-neuromodulators-ach-ne]
key_sources: ["PMID:18633352", "PMID:17920021", "PMID:23818597", "PMID:30381436", "PMID:26135716"]
---

# 乙酰胆碱神经调质系统 (Acetylcholine Neuromodulation)

> **一句话定义**：基底前脑胆碱能系统通过差异性突触靶向，在高 ACh（清醒/编码）和低 ACh（睡眠/固化）两种全脑状态之间切换大脑——高 ACh 打开感觉输入通道、促进 θ 振荡编码；低 ACh 解放 CA3 循环兴奋、允许 SWR 重放和记忆固化。

## 当前理解

我们现在认为，乙酰胆碱（Acetylcholine, ACh）是大脑"操作系统模式切换"中最关键的神经调质之一。其功能不是单纯的兴奋或抑制，而是通过**差异性突触靶向**——选择性地抑制内部循环连接，同时保留感觉输入通道——实现全脑信息流向的主动路由控制。

**基底前脑解剖系统（Mesulam 分类）**：
- **Ch1/Ch2**（内侧隔核 + 对角带垂直部）→ 海马、内嗅皮层
- **Ch3**（对角带水平部）→ 嗅球
- **Ch4**（Meynert 基底核）→ 整个新皮层、杏仁核

投射不是弥散广播，而是具有**拓扑特异性**（Záborszky 2018, PMID:30381436）：不同基底前脑神经元群选择性靶向不同皮层区域和层次。

**Hasselmo 双模型**：
- 模式 A（高 ACh，清醒/任务）= 编码/外部输入主导
- 模式 B（低 ACh，睡眠/休息）= 回放/内部模式主导

这是由同一分子通过不同靶点、不同受体亚型在皮层和海马协调实现的全脑状态切换，是神经调质调控认知功能中最机制清晰的案例之一。

## 关键机制

### 两种 ACh 时间尺度

1. **紧张性（Tonic）**：维持基础 ACh 水平，决定整体觉醒/模式状态
2. **相位性（Phasic）**：对显著事件快速响应（~5s 峰值），实现事件级精度调制（Parikh 2007, PMID:17920021）

### 高 ACh 状态（清醒/编码模式）

**皮层**：
- M1 受体激活 → 降低 KCNQ/IM K⁺ 漏电流 → 膜电位轻度去极化 → 响应增益↑ → 信噪比↑
- EEG 去同步化：慢波 → 低幅 β/γ 振荡（最优编码状态）
- V1 注意调制：M1 受体介导（非烟碱型）(Herrero 2008, PMID:18633352)

**海马**：
- M2 受体（突触前）抑制 CA3 循环侧支 → 防止 SWR 自发爆发
- 选择性抑制 Schaffer 侧支传递 → 减少 CA3 存储模式对 CA1 的影响
- 保留内嗅皮层穿通通路 → 感觉输入优先进入 CA1
- Ch1/Ch2 → 内侧隔核 → 促进海马 θ 振荡（4-8 Hz）→ 支持相位编码和场所序列写入

**结果**：大脑优先接受当前感觉输入，新经历的场所序列得以编码

### 低 ACh 状态（睡眠/固化模式）

**海马**：
- ACh 对 CA3 循环侧支的抑制解除 → CA3 自发性群体爆发 → 产生 SWR
- SWR 期间白天场所细胞序列以 ~20 倍速压缩重播
- CA1 → 内嗅皮层 → 新皮层：记忆痕迹传出，逐步在皮层固化

**皮层**：
- 同步慢波振荡（0.5-1 Hz，UP/DOWN 态交替）
- 丘脑-皮层纺锤波（12-15 Hz）嵌套在 UP 态
- SWR 嵌套在纺锤波波谷 → 皮层接受海马输入的时间窗口（SO-纺锤波-SWR 三重奏）

**结果**：大脑优先处理内部存储模式，已学习的序列得以固化进皮层

### 受体分工

| 受体 | 位置 | 偶联 | 功能 |
|------|------|------|------|
| M1（突触后） | 皮层/海马锥体细胞 | Gq→PLCβ | 增加兴奋性增益 |
| M2（突触前） | 胆碱能末梢；CA3 侧支 | Gi/o | 负反馈（自受体）；抑制 CA3 兴奋 |
| α4β2 nAChR | 丘脑皮质末梢 L4 | 离子通道 | 增强感觉底-上输入 |
| α7 nAChR | dlPFC 谷氨酸突触后 | 离子通道（Ca²⁺通透） | 增强 NMDA 参与 → WM 持续放电（Yang 2013, PMID:23818597） |

### 精度加权与 VIP 去抑制

ACh 通过激活 VIP（血管活性肽）中间神经元 → 抑制 SST 中间神经元 → **去抑制**锥体细胞，选择性提升特定回路的信噪比。这在计算上等效于预测编码框架中的精度加权（Precision Weighting）：高精度 = 该通道的预测误差对模型更新有更大权重。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| M1（非 nAChR）介导 V1 注意增益 | 猕猴 V1 离子导入阻断 + 注意任务 | Herrero 2008, PMID:18633352 | 高 |
| 相位性 ACh 瞬变在刺激成功检测时出现，漏报无 | 大鼠 mPFC 高时间分辨率电化学传感器 | Parikh 2007, PMID:17920021 | 高 |
| α7 nAChR 增强 dlPFC 延迟期 WM 放电 | 猕猴 dlPFC α7 操控 + 延迟任务 | Yang 2013, PMID:23818597 | 中 |
| BF 投射拓扑特异性 | 高分辨率解剖重建，神经元追踪 | Zaborszky 2018, PMID:30381436 | 中-高 |
| 低 ACh → CA3 解放 → SWR | 体外切片 + 体内 ACh/LFP 相关 | 综述 Buzsaki PMID:26135716 | 高 |
| BF PV 神经元参与皮层去抑制注意调控（新发现）| BF-PV 特异性操控 + 注意行为 | Cell 2026, PMID:42349384（摘要，未核实）| 中（待验证） |

## 连接

- [[acetylcholine-cortex]] — 皮层 ACh 机制的专项页（M1/M2/nAChR 受体详细机制、增益控制）；本页提供更广的系统级框架
- [[sharp-wave-ripples]] — ACh 是 SWR 生成的分子上游控制器：高 ACh 阻止 SWR；低 ACh 解放 CA3 → SWR
- [[theta-oscillations]] — 内侧隔核 ACh 支持海马 θ 振荡；θ 和 SWR 是 ACh 高/低两种模式的振荡特征
- [[memory-consolidation]] — ACh 状态切换为"海马编码 → 睡眠固化"二阶段模型提供神经调质基础
- [[precision-weighting]] — ACh 是精度加权的分子实现（M1-VIP 去抑制回路）
- [[vip-interneurons]] — VIP 中间神经元是 ACh 精度调制的关键效应细胞
- [[working-memory]] — α7 nAChR 增强 PFC 工作记忆持续放电；M1 支持持续去极化
- [[alzheimers-disease]] — AD 早期最突出病理之一是 Meynert 基底核胆碱能神经元丢失；破坏 ACh 状态切换系统
- [[norepinephrine-locus-coeruleus]] — NE 是与 ACh 协同的第二大皮层调质；ACh 专注感觉增益/状态切换，NE 更侧重唤醒度/信噪比
- [[predictive-coding]] — ACh 精度加权是预测编码框架中"注意 = 精度调制"的回路实现

## 未解问题

- **Q-ach-01**（高优先级）：相位性 ACh 瞬变是否直接因果地产生行为刺激检测改善？目前证据是相关性的，光遗传选择性激活基底前脑 ChAT+ 神经元产生人工相位 ACh 释放的体内因果实验是否已完成？
- **Q-ach-02**（中优先级）：清醒 SWR 是否真正绕过 ACh 抑制机制？CA2 主导的 SWR 触发路径（绕过 CA3）是否对 ACh 水平更不敏感？
- **Q-ach-03**（中优先级）：在人类中，M1 vs α7 受体对认知功能的相对贡献是什么？胆碱酯酶抑制剂（AD 治疗）的效果通过哪条受体通路？

## 修订历史

- 2026-06-30 · 创建 · 基于《乙酰胆碱：大脑的模式开关》文章 #182 · 系统整合了皮层 ACh（见 acetylcholine-cortex.md）和海马 ACh 的机制，提出全脑双模模型；初始置信度：高（经典知识，机制跨多实验室验证）

## 来源文章

- [[2026-06-30-acetylcholine-neuromodulation-modes]]
- [[2026-06-12-neuromodulators-ach-ne]]

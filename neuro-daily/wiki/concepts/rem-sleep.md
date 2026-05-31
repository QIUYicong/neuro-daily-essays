---
title: REM睡眠
slug: rem-sleep
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-31
updated: 2026-05-31
revision_count: 1
dimensions: [molecular, cellular, brain-region, whole-brain-network, behavior, cognition]
related: [memory-consolidation, sharp-wave-ripples, sleep-spindles, theta-oscillations, fear-extinction, norepinephrine-locus-coeruleus, hippocampal-circuit, amygdala, emotional-memory-depotentiation]
prerequisites: [theta-oscillations, norepinephrine-locus-coeruleus, hippocampal-circuit, sleep-spindles]
opens_questions: [Q-rem-01, Q-rem-02, Q-rem-03, Q-rem-04, Q-rem-05]
source_articles: [2026-05-31-rem-sleep-emotional-memory]
key_sources: ["PMID:27174984", "PMID:19702380", "PMC:PMC2890316", "PMID:22119526", "PMC:PMC3237718", "PMID:28100731", "PMC:PMC5242402", "PMID:28729826", "PMC:PMC5498516"]
---

# REM睡眠 (REM Sleep — Rapid Eye Movement Sleep)

> **一句话定义**：睡眠周期的一个阶段，特征为脑电去同步、肌肉张力消失、眼球快速运动和海马θ振荡持续存在，是情绪记忆去饱和化和恐惧消退巩固的专用时间窗，其神经化学基础是蓝斑几乎完全沉默（去甲肾上腺素→0）。

## 当前理解

我们现在认为，REM睡眠的核心功能不是简单的"休息"，而是在独特神经化学环境（NE≈0）中执行**情绪记忆的选择性去饱和化**：保留情节事实内容，同时弱化情感电荷（杏仁核–自主神经反应性）。

REM睡眠在人类成年后占总睡眠的约20–25%，主要集中在后半夜。一夜正常睡眠中，NREM→REM循环4–5次，每次REM持续时间随循环递增（第一次约5–10分钟，最后一次可达45分钟）。

REM睡眠的两大神经化学特征：
1. **蓝斑（LC）几乎完全停止发放**：NE降至接近零，这是REM去极化功能的分子前提
2. **胆碱能主导**：ACh活动维持高水平（与LC沉默形成互补），驱动脑电去同步化和θ振荡

Walker（2009，PMID:19702380，PMC2890316）将REM的双重功能概括为"Sleep to Forget, Sleep to Remember"（SFSR）假说：REM同时实现情感去饱和化（遗忘情绪色彩）和记忆巩固（记住事实内容）。

Boyce等人（2016，PMID:27174984）通过光遗传因果实验在小鼠中证明：仅在REM睡眠期间沉默中隔核GABA神经元（特异性削弱θ振荡）就导致情境记忆和位置记忆受损，而在NREM或清醒期间做同样操作则无任何效果。这是REM θ对记忆巩固**充分必要性**的直接因果证明。

## 关键机制

### 1. 神经化学层：NE真空创造去极化窗口

- 清醒时NE持续存在：通过β受体和α1受体阻止突触去极化，促进LTP方向的可塑性
- REM时LC接近沉默：NE的缺失开放了去极化的分子窗口
- Poe（2017，PMID:28100731，PMC5242402）：海马场所细胞在REM期间的放电从θ**波峰**（LTP方向）转向θ**波谷**（去极化方向），这种相位反转使已被皮层接管的海马记忆局部弱化

### 2. 回路层：海马–杏仁核–PFC的θ三角同步

- REM期间，海马θ振荡持续存在（类似清醒探索，但无空间编码任务）
- 关键差异：REM θ特别组织海马–杏仁核–前额叶皮层之间的跨区域同步
- Totty等人（2017，PMID:28729826，PMC5498516）：在REM睡眠中，外侧杏仁核（LA）与腹侧海马（VH）之间的θ**相位差**（而非同步强度）预测恐惧消退记忆质量：反相（≈180°）→消退成功；同相（≈0°）→消退失败（R=0.954）

### 3. 功能层：情绪去饱和化

- van der Helm等人（2011，PMID:22119526，PMC3237718）：一夜睡眠后对同一情绪图片的杏仁核激活显著降低，且与REM期间低γ功率（NE活动代理）负相关
- 即：REM期间NE越低（低γ），次日对情绪刺激的杏仁核反应越弱
- 这种去饱和化不影响记忆的事实内容（事件仍被记住），只弱化情感成分

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| REM θ是情境记忆巩固的充分必要条件 | 光遗传沉默REM MS-GABA；比较REM vs. NREM时间窗口效应 | PMID:27174984 | 高（动物因果） |
| REM去饱和化杏仁核激活 | 人类fMRI：睡眠组vs清醒组，前后测；EEG γ相关 | PMID:22119526 | 高（人类直接测量） |
| NE缺失是REM去饱和化的分子前提 | 电生理记录LC在各状态的发放；NE阻断实验 | PMID:28100731 | 高（动物直接记录） |
| LA-VH θ相位差预测恐惧消退记忆 | 大鼠五区域LFP记录；恐惧条件反射+消退 | PMID:28729826 | 中（n=8，强相关） |
| REM θ功率与情绪记忆增强正相关 | 人类fMRI+EEG；小睡范式 | PMID:19702380 | 中（间接相关） |

## 连接

- [[theta-oscillations]] — REM的核心振荡机制；与清醒θ同频但功能不同（相位方向反转）
- [[norepinephrine-locus-coeruleus]] — NE系统在REM期间沉默是情绪去饱和化的分子前提
- [[memory-consolidation]] — REM和NREM构成睡眠记忆巩固的双轨系统
- [[fear-extinction]] — 恐惧消退记忆的巩固特别依赖REM睡眠期间的LA-VH θ同步
- [[sharp-wave-ripples]] — REM的补充：NREM的SWR重放和REM的θ去饱和化形成完整的睡眠记忆处理系统
- [[sleep-spindles]] — NREM的时序枢纽；与REM共同构成夜间记忆处理的两个专用时段
- [[amygdala]] — 情绪记忆存储和情感反应的核心区域；REM去饱和化的主要靶点
- [[emotional-memory-depotentiation]] — 本页描述的核心功能过程

## 未解问题

- Q-rem-01：情绪去饱和化是否对所有情绪效价（正性、负性）均有效？
- Q-rem-02：PTSD的REM功能障碍是因（NE过高→无法去饱和化）还是果（创伤激活LC→REM破坏）？
- Q-rem-03：灵长类REM θ振荡与记忆功能的因果关系是否可以像Boyce 2016在啮齿类中那样直接验证？
- Q-rem-04：NREM→REM序列的必要性：单独NREM或单独REM是否足以实现最优巩固？
- Q-rem-05：REM对情绪记忆的特殊处理是否是一般情境记忆巩固功能的附带产物，还是有独立专用机制？

## 修订历史

- 2026-05-31 · 创建 · 基于《REM睡眠：大脑夜晚的情绪炼金炉》（文章#34）· 初始置信度：高

## 来源文章

- [[2026-05-31-rem-sleep-emotional-memory]]

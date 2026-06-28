---
title: REM睡眠肌张力弛缓
slug: rem-muscle-atonia
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-10-17
updated: 2026-10-17
revision_count: 1
dimensions: [molecular, cellular, brain-region, whole-brain-network, behavior]
related: [rem-sleep, sublaterodorsal-nucleus, norepinephrine-locus-coeruleus, rem-sleep-behavior-disorder, glycinergic-inhibition, spinal-cord-circuits, theta-oscillations]
prerequisites: [rem-sleep, synaptic-inhibition, brainstem-anatomy]
opens_questions: [Q-rem-atonia-01, Q-rem-atonia-02, Q-rem-atonia-03]
source_articles: [2026-10-17-rem-sleep-atonia-rbd-parkinson]
key_sources: ["PMID:21115377", "PMC:10627170", "PMID:28007991", "PMC:6839496", "PMID:31832664", "PMC:7294404", "PMID:19625526", "PMID:11549748"]
---

# REM睡眠肌张力弛缓 (REM Sleep Muscle Atonia)

> **一句话定义**：REM睡眠期间全身横纹肌（眼外肌除外）的主动神经性抑制，由脑桥**被盖下外侧核（SLD）**谷氨酸神经元驱动→延髓腹内侧区（VMM）甘氨酸/GABA中间神经元→脊髓α运动神经元超极化的三级级联回路实现，并由LC/中缝核单胺去易化协同增强。

## 当前理解

REM肌张力弛缓不是被动的"断电"，而是**主动的持续抑制**。肌电图（EMG）显示REM期间脊髓α运动神经元持续超极化，需要上游系统持续泵送抑制信号才能维持——这解释了为何SLD损伤后立即出现REM期EMG活动恢复（而非逐渐恢复）。

核心证据：Valencia Garcia等人（2017，PMID:28007991，Brain）选择性敲除SLD中vGluT2基因，大鼠出现完整的RBD表型（PSG确认REM期EMG爆发+梦境行为化），证明SLD谷氨酸神经元是肌张力弛缓的**充分必要条件**。

## 关键机制

### 三级级联回路

**第一级：SLD（被盖下外侧核）**
- 脑桥尾部，蓝斑腹侧
- vGluT2+神经元在REM睡眠期间特异性激活
- 投射到VMM和脊髓中间神经元（谷氨酸传递）

**第二级：VMM（延髓腹内侧区）**
- 接收SLD谷氨酸激活
- 甘氨酸能/GABA能中间神经元向脊髓前角投射
- 直接证据：光遗传激活VMM→舌下运动神经元抑制（Dergacheva 2020，PMID:31832664）

**第三级：脊髓α运动神经元**
- 接收VMM的甘氨酸+GABA双重抑制性突触后电位（IPSP）
- 膜电位超极化约10-20mV，远超激活阈值
- 效果：全身骨骼肌弛缓（REM atonia）

### 协同机制：单胺去易化

清醒时LC（NE）和中缝核（5-HT）持续向脊髓运动神经元提供兴奋性背景张力；REM期两者发放接近零，消除单胺兴奋背景，放大甘氨酸/GABA抑制效果（Lai & Siegel 2001，PMID:11549748）。

**机制总结**：主动抑制（甘氨酸/GABA）+ 去兴奋（单胺↓）双重保障，防止运动神经元在任何噪声下误触发（Luppi et al. 2011，PMID:21115377综述）。

## 关键证据

| 主张 | 方法 | 来源 | 置信度 |
|------|------|------|--------|
| SLD vGluT2+神经元是REM肌张力弛缓的必要条件 | vGluT2条件性KO+PSG+行为分析 | PMID:28007991 | 高（动物因果） |
| VMM甘氨酸/GABA神经元直接抑制颅运动神经元 | 光遗传激活/沉默VMM+舌下MN记录 | PMID:31832664 | 高（动物因果，直接记录） |
| SLD损毁→RBD样行为 | 脑桥背盖病变，猫/大鼠 | PMID:21115377综述 | 高（经典实验，多次复现） |
| 单胺去易化协同肌张力弛缓 | 电生理记录LC/中缝核在REM期沉默 | PMID:11549748 | 高 |

## 连接

- [[rem-sleep]] — 肌张力弛缓是REM睡眠的三大定义特征之一（与快速眼动、脑电去同步化并列）
- [[sublaterodorsal-nucleus]] — SLD是肌张力弛缓回路的第一级指令节点
- [[rem-sleep-behavior-disorder]] — SLD受损（通常由α-突触核蛋白病变）导致肌张力弛缓失败
- [[norepinephrine-locus-coeruleus]] — LC在REM期沉默，NE消失是单胺去易化的主要来源
- [[parkinson-disease]] — α-突触核蛋白在SLD的早期沉积是body-first PD的脑干层面标志

## 未解问题

- Q-rem-atonia-01：SLD有多少比例的神经元直接投射脊髓（不经VMM）？直接通路对肌张力弛缓的贡献？
- Q-rem-atonia-02：VMM甘氨酸和GABA的相对贡献是否随着脊髓水平（颈段vs腰段）变化？
- Q-rem-atonia-03：睡眠麻痹（sleep paralysis，清醒时肌张力弛缓持续）与RBD（REM期肌张力弛缓失败）是否共享相同的SLD-VMM回路，只是失调方向相反？

## 修订历史

- 2026-10-17 · 创建 rev1 · 基于《梦中的麻痹》(#187) · 建立REM肌张力弛缓独立概念页面；定义SLD→VMM→脊髓三级回路及单胺去易化协同机制

## 来源文章

- [[2026-10-17-rem-sleep-atonia-rbd-parkinson]]

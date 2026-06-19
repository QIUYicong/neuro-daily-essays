---
title: 听觉皮层
slug: auditory-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-07-21
updated: 2026-07-21
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, whole-brain-network, cognition]
related: [tonotopy, mismatch-negativity, language-network, broca-area, predictive-coding, neuromodulator-systems, critical-period, v1-primary-visual-cortex]
prerequisites: [action-potential, synaptic-transmission, nmda-receptor]
opens_questions: [Q-ac-01, Q-ac-02, Q-ac-03, Q-ac-04]
source_articles: [2026-07-21-auditory-cortex-tonotopy-speech]
key_sources: ["PMID:27145914", "PMID:24052177", "PMID:30022729", "PMID:24482117", "PMID:38093008"]
---

# 听觉皮层 (Auditory Cortex)

> **一句话定义**：位于颞上回（Heschl's gyrus及周边）的皮层区域，负责将来自内侧膝状体的频率编码信号逐级转化为声音对象、音素和高级听觉表征，包含11个有序频率场图，并通过主动预测编码机制持续监测声学规律的违反。

## 当前理解

我们现在认为，听觉皮层是一个主动预测型感知系统，而非被动声学分析器。它的核心功能不是"接收"声音，而是：
1. 维护一个对外部声学世界统计规律的**内部模型**
2. 通过层级计算实现**噪声不变性表征**（非初级皮层）
3. 在声学统计规律被违反时发出**预测误差信号**（MMN/SSA）
4. 将频率信息逐级转化为音素、语音和音乐的**语义表征**

**解剖架构（人类）**：
- **核心区（Core）**：3个区域（hA1, hR, hRT），位于赫氏回（Heschl's gyrus），接受丘脑内侧膝状体（MGN）密集直接投射
- **带区（Belt）**：4个内侧带区 + 4个外侧带区，围绕核心区，接受核心区前馈输入
- **副带区（Parabelt）**：颞上沟（STS）及周边，最高级处理
- **总计**：11个有序的听觉场图（AFMs），以频率拓扑+周期性拓扑为两个正交轴，排列成苜蓿叶簇

**双流处理**：
- **腹侧流（What）**：前颞叶方向，声音身份/类别识别
- **背侧流（Where/How）**：后颞叶→顶叶→额叶，空间定位+感觉运动整合

## 关键机制

### 1. 频率拓扑（Tonotopy）
从耳蜗到A1保持的"频率=位置"映射原则。A1中高频在内侧，低频在外侧（人类），以V形梯度组织（赫氏回前后两侧各有一个镜像梯度）。

### 2. 层级噪声不变性
从初级（A1）到非初级（带区/副带区），神经元响应对背景噪声的稳定性逐渐提高。非初级皮层通过对环境噪声的持续适应实现噪声滤除，产生前景声音的稳定表征（Kell et al. 2019：t₁₀ = 8.37, p = 7.88×10⁻⁶）。

### 3. 预测编码（SSA & MMN）
- **刺激特异性适应（SSA）**：单神经元对重复标准音响应下降，对偏差音恢复
- **失匹配负波（MMN）**：人群/EEG层面的预测误差信号，峰值~150-250 ms，无需注意力
- 预测误差沿通路升级：A1约25% → 带区约50-80%
- NMDA 受体是SSA和MMN的共同分子基础

### 4. 音素编码（STG）
颞上回（STG）将声学模式转化为语言类别：
- 14种音素特征的STG空间分布（PMID:24482117）
- 浅层神经元→音调；中深层神经元→音素特征（Leonard 2024）
- 元音编码需非线性整合F1+F2共振峰

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 人类听觉皮层含11个有序AFMs | fMRI频率映射；11区域重复验证 | PMID:27145914 (PMC6436392) | 高 |
| 非初级皮层显著更耐噪声 | fMRI noise-invariance, t=8.37 | PMID:31477711 (PMC6718388) | 高 |
| STG编码14种音素特征 | 人类术中ECoG，自然语音 | PMID:24482117 (PMC4350233) | 高 |
| STG神经元深度依赖功能分层 | Neuropixels（685单神经元，8名病人） | PMID:38093008 (PMC10866713) | 高 |
| 非初级皮层有独立的语音/音乐选择性成分 | fMRI voxel decomposition，165种声音 | PMID:26687225 (PMC4740977) | 高 |
| SSA/MMN是统一预测误差层级 | 综述：下丘→丘脑→A1→带区梯度 | PMID:30022729 (PMC6053868) | 高（综述） |
| NB-ACh刺激配对声音可双向改变皮层跟随速率 | 大鼠，电极配对实验，20-25天 | PMID:10196590 (PMC2948964) | 高 |

## 连接

- [[tonotopy]] — 频率拓扑映射，听觉皮层的基本组织原则
- [[mismatch-negativity]] — 预测误差信号，SSA/MMN机制
- [[language-network]] — 语音选择性STG是听觉皮层到语言网络的界面
- [[predictive-coding]] — 听觉皮层是预测编码的最清晰体现之一
- [[neuromodulator-systems]] — NB-ACh系统门控听觉皮层可塑性
- [[critical-period]] — 听觉皮层有发育关键期，决定频率地图精度
- [[v1-primary-visual-cortex]] — 平行的层级感觉皮层结构（苜蓿叶簇、双流）
- [[thalamus]] — 内侧膝状体（MGN）是听觉皮层的主要丘脑输入源

## 未解问题

- **Q-ac-01**（高优先级）：频率拓扑在复杂自然声音处理中的意义是什么？是否存在更高级的"声音特征地图"（类比视觉方向选择性柱）？
- **Q-ac-02**（高优先级）：腹侧/背侧双流在人类语音实时处理中是串联还是并联？损伤研究提示分离，但影像研究有大量重叠。
- **Q-ac-03**（中优先级）：音乐选择性是"音乐"概念的特化，还是谐波音调选择性的上位体现？（Norman-Haignere 2015 vs 2022 自我修正）
- **Q-ac-04**（中优先级）：婴儿如何在几个月内无监督地从连续语音中提取音素系统？NB-ACh发育窗口与语音习得关键期的精确关系是什么？

## 修订历史

- 2026-07-21 · 创建 · 基于《听觉皮层：从频率地图到语音意义的六级解码之旅》· 来源：PMID:27145914, 24052177, 30022729, 24482117, 38093008, 31477711, 26687225, 10196590, 39172655, 20850511

## 来源文章

- [[2026-07-21-auditory-cortex-tonotopy-speech]]

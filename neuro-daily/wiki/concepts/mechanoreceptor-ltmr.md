---
title: 低阈值机械感受器（LTMR）
slug: mechanoreceptor-ltmr
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-19
updated: 2026-07-19
revision_count: 1
dimensions: [molecular, cellular, synaptic]
related: [piezo2-mechanotransduction, somatosensory-cortex, barrel-cortex, thalamus]
prerequisites: [action-potential, ion-channels]
opens_questions: [Q-soma-01]
source_articles: [2026-07-19-somatosensory-cortex-body-map]
key_sources: ["PMID:34312536", "PMID:24717433", "PMID:25471886"]
---

# 低阈值机械感受器（LTMRs）(Low-Threshold Mechanoreceptors)

> **一句话定义**：皮肤中对轻触力敏感的感觉传入神经，分SA1、RA1、RA2、SA2四型（以适应速度和感受野大小分类），通过PIEZO2等通道将皮肤机械变形转化为电信号，沿Aβ纤维传输至脊髓。

## 当前理解

我们现在认为，皮肤的精细触觉是四类（无毛皮肤）或五类（有毛皮肤）LTMR亚型的**群体编码**结果，而非单一感受器类型的输出。各亚型具有高度特化的感受器结构、适应动力学和功能分工，集体构成了触觉的丰富信息内容（纹理、形状、振动频率、皮肤牵张）。

PIEZO2已被确立为大多数LTMR亚型中机械转导的主要离子通道（Ranade et al. 2014, PMC4380172）。每类LTMR的频率响应特性在很大程度上由其**感受器结构的机械滤波特性**决定，而非仅由PIEZO2通道本身的化学特性决定。

## 关键机制

### 无毛皮肤（Glabrous Skin）的四类LTMR

| 类型 | 感受器结构 | 适应性 | 最优刺激 | 感受野 | 主要功能 |
|------|-----------|--------|---------|--------|---------|
| **SA1** (Aβ) | 梅克尔细胞-神经突复合体 | 慢适应 | 持续压迫 | 小（2-3mm） | 精细纹理、形状识别 |
| **RA1** (Aβ) | 迈斯纳小体（Meissner） | 快适应 | 40-60 Hz振动 | 小 | 微滑动检测、握持控制 |
| **RA2** (Aβ) | 帕奇尼小体（Pacinian） | 快适应 | 100-300 Hz振动 | 极大 | 工具振动感知（10纳米敏感） |
| **SA2** (Aβ) | 鲁菲尼末梢（Ruffini，争议） | 慢适应 | 皮肤牵张（方向敏感） | 大 | 手指位置感（本体感觉贡献） |

### 有毛皮肤（Hairy Skin）额外的LTMR亚型

- **Aδ-LTMR**：矛尖状末梢，方向敏感（~5 m/s，中等速度传导）
- **C-LTMR**：无髓鞘，矛尖状末梢，对慢速（~3 cm/s）轻柔触摸最敏感，与愉悦触觉/社交触觉（C-tactile afferents）相关

### 梅克尔细胞双感受器模型（SA1）

Woo et al.（2014, PMC4039622）建立了关键概念：
- **动态相**（快速压迫时的瞬时放电）→由Aβ SAI-LTMR末梢的PIEZO2介导
- **静态相**（持续压迫时的持续放电）→增强于梅克尔细胞自身的PIEZO2激活，梅克尔细胞通过某种化学突触（谷氨酸能？）将信号传给神经末梢

梅克尔细胞在基底表皮层（基底膜上方），与Aβ纤维末梢形成类突触接触（有致密核心囊泡），自身具有电兴奋性和内在的机械敏感性。

### 帕奇尼小体的机械高通滤波

Pacinian小体的层状包膜（约50层半环形弹性片层）对低频力起机械缓冲（衰减），对高频振动起共振放大（估计放大约8-12倍）。拆除外层包膜后，受体电位延长，证明频率选择性主要由机械结构实现，而非通道本身。

### PIEZO2的核心地位

双敲除实验（感觉神经元+梅克尔细胞同时敲除PIEZO2）的小鼠在多项轻触行为测试中几乎完全丧失感知（Ranade et al. 2014）。这确立了PIEZO2不可替代的地位，但每类LTMR中PIEZO2的精确亚细胞定位（帕奇尼小体中免疫染色阴性但功能依赖）仍待解决。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| PIEZO2是轻触主要转导通道 | 双KO（梅克尔+感觉神经元）几乎完全丧失轻触行为 | Ranade et al. 2014 (PMC4380172) | 高 |
| 梅克尔细胞双感受器模型 | 梅克尔细胞特异性KO→静态相选择性损伤；光遗传激活梅克尔细胞→Aβ放电 | Woo et al. 2014 (PMC4039622) | 高 |
| 帕奇尼小体机械滤波 | 拆除外层包膜→受体电位延长（Loewenstein经典实验） | Handler & Ginty 2021 review (PMC8485761) | 高 |
| SA2型（鲁菲尼）形态存疑 | 小鼠皮肤无形态学确认，生理记录存在 | Handler & Ginty 2021 (PMC8485761) | 中等（争议） |

## 连接

- [[piezo2-mechanotransduction]] — LTMR的主要分子转导通道
- [[somatosensory-cortex]] — LTMR信号的皮层计算中心（经脊髓背柱→VPL→3b区）
- [[action-potential]] — LTMR将机械刺激转化为动作电位的基本机制
- [[thalamus]] — VPL/VPM作为LTMR信号上行至皮层的丘脑中转站
- [[barrel-cortex]] — 大鼠胡须SA1型末梢→丘脑VPM→桶状皮层（经典模型）

## 未解问题

- Q-soma-01（附属）：SA2型感受器（鲁菲尼末梢）在小鼠中的形态学底物是什么？
- 帕奇尼小体中PIEZO2的精确亚细胞定位（功能存在但免疫染色阴性）
- 梅克尔细胞向Aβ-SAI传递信号的具体神经递质（谷氨酸？5-HT？肾上腺素？）

## 修订历史

- 2026-07-19 · 创建 · 基于《皮肤的密码》(#87) · 初始置信度：高（四类LTMR分类）/争议（SA2）

## 来源文章

- [[2026-07-19-somatosensory-cortex-body-map]]

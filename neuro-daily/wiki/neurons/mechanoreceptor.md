---
title: 皮肤机械感受器
slug: mechanoreceptor
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-07-19
updated: 2026-07-19
revision_count: 1
dimensions: [molecular, cellular, synaptic]
related: [somatosensory-cortex, thalamus, action-potential, voltage-gated-sodium-channel]
prerequisites: [action-potential, voltage-gated-sodium-channel]
opens_questions: [Q-s1-02]
source_articles: [2026-07-19-somatosensory-cortex-body-map]
key_sources: ["PMID:23972592", "PMID:24853935"]
---

# 皮肤机械感受器 (Skin Mechanoreceptors / Low-Threshold Mechanoreceptors)

> **一句话定义**：皮肤中对物理触摸敏感的初级感觉神经元终末，通过MET（mechano-electrical transduction）通道将皮肤变形转化为电信号，包括四类有髓鞘Aβ型（FA-I、FA-II、SA-I、SA-II）和一类无髓鞘C型（CT纤维），分别编码不同时空维度的触觉特征。

## 当前理解

我们现在认为，皮肤触觉的多维感知是由四种并行的机械感受器类型共同编码的，每种类型在受体结构、适应速度、感受野大小和调谐频率上都具有明确的专业化：FA-I（梅斯纳）负责轻触和滑动检测，SA-I（默克尔）负责静压和精细空间分辨，SA-II（鲁菲尼）负责皮肤拉伸和手部姿态，FA-II（环层）负责高频振动（工具使用）。

此外，一类独立的无髓鞘C-触觉纤维（CT afferents）专门响应有毛皮肤上的温柔轻抚（1–10 cm/s），不投射到S1而是到岛叶，编码触觉的情感和奖励维度（McGlone et al., 2014）。

## 关键机制

### 四类Aβ型机械感受器（无毛皮肤为主）

| 类型 | 感受器结构 | 适应 | 感受野 | 调谐频率 | 主要功能 |
|------|-----------|------|--------|---------|---------|
| FA-I | 梅斯纳小体（Meissner corpuscle） | 快 | 小（~2–3mm） | 5–50 Hz | 轻触、纹理、滑动检测 |
| SA-I | 默克尔盘（Merkel's disc） | 慢 | 小（~2–3mm） | 静压，<1 Hz | 精细空间分辨、盲文、边缘 |
| SA-II | 鲁菲尼小体（Ruffini ending） | 慢 | 大（>10mm） | 皮肤拉伸 | 手指/手部姿态感知 |
| FA-II | 环层小体（Pacinian corpuscle） | 高频快 | 极大（全手掌） | 200–300 Hz | 高频振动、工具触感 |

**密度梯度**：指尖FA-I密度约150/cm²，SA-I约70/cm²；背部皮肤各类均约5/cm²。这一密度梯度直接对应皮层放大倍率。

### C-触觉纤维（CT afferents，有毛皮肤）
- 无髓鞘，传导速度<2 m/s
- 对慢速（1–10 cm/s）、温热的轻抚最敏感
- 信号投射到岛叶（insula），而非S1
- 激活愉悦感、社会联结感
- 被认为是"情感性触觉（affective touch）"的神经底物

### 换能机制（MET）
皮肤变形→感受器终末膜变形→**力敏离子通道**（主要是PIEZO2，在SA-I/FA类型表达）开放→K⁺内流（皮下，轻度去极化）→达阈值→动作电位由Aβ纤维传导至脊髓背角→背柱上行

**PIEZO2的重要性**：2021年诺贝尔生理学或医学奖授予David Julius和Ardem Patapoutian，后者的工作包括发现PIEZO1/2是触觉和本体感觉的关键MET通道（PIEZO2）；先天性PIEZO2缺失患者丧失精细触觉和本体感觉，但粗触觉保留（通过其他通道）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 四类Aβ型LTMR功能独立，各自有调谐频率 | 人类单纤维记录（microneurography） | PMID:23972592 | 高 |
| CT纤维激活岛叶不激活S1 | Aβ缺失患者的fMRI+单纤维记录 | PMID:24853935 | 高 |
| PIEZO2是SA-I/本体感觉的关键MET通道 | PIEZO2缺失患者表型+小鼠基因敲除 | （诺贝尔2021，Patapoutian组） | 高 |

## 连接

- [[somatosensory-cortex]] — 机械感受器信号经脊髓背柱→丘脑VPL→S1 3b区
- [[thalamus]] — VPL/VPM是机械感受器信号的第三级中继
- [[action-potential]] — 机械感受器去极化触发Aβ纤维动作电位
- [[voltage-gated-sodium-channel]] — Nav1.8等亚型在初级感觉神经元中表达，参与感觉神经元兴奋性调节

## 未解问题

- Q-s1-02：CT afferents在不同个体中的密度是否有显著差异？这是否解释了"对触摸敏感度"的个体差异？

## 修订历史

- 2026-07-19 · 创建 · 基于《皮肤之上的地图》文章（#87） · 初始置信度：高

## 来源文章

- [[2026-07-19-somatosensory-cortex-body-map]]

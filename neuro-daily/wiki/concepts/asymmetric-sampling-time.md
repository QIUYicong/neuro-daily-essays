---
title: 非对称时间采样假说（AST）
slug: asymmetric-sampling-time
domain: concepts
type: theory
status: mainstream
confidence: medium
created: 2026-06-08
updated: 2026-06-08
revision_count: 1
dimensions: [brain-region, systems, cognition, whole-brain-network]
related: [speech-perception-phonology, cortical-entrainment-speech, auditory-cortex, hemispheric-asymmetry, language-network, predictive-coding]
prerequisites: [auditory-cortex, cortical-entrainment-speech]
opens_questions: [Q-speech-percep-02]
source_articles: [2026-06-08-speech-perception-phonology-STG]
key_sources: ["PMID:40010659", "PMID:22426255", "PMID:36605556", "PMID:40118260"]
---

# 非对称时间采样假说（AST）(Asymmetric Sampling in Time)

> **一句话定义**：Poeppel 提出的半球不对称理论：左颞上区对快速声学变化（约25–30ms 时间窗，音素级）更敏感，右颞上区对慢速变化（约150–300ms，音节级）更敏感，两个时间窗分别优化了语音中不同时间尺度的语言信息提取。

## 当前理解

我们现在认为，左右听觉皮层对语音信号实施不同时间粒度的采样：

**左半球**（约 25–30ms 整合窗）：
- 适合处理快速时间变化——辅音的爆发音（burst）、声调的快速起始、跨音素的频谱快速切换
- 语言中对辨别意义至关重要的辅音/音素边界信息
- 与发音和声-运动整合的左侧化相互加强

**右半球**（约 150–300ms 整合窗）：
- 适合处理音调轮廓、韵律节奏、慢速调幅
- 音节级信息的处理优势
- 也负责音乐旋律的感知（需要持续追踪音调变化的时间轮廓）

**重要限制（来自 Preisig & Meyer 2025）**：
侧化并非固定的底层硬件属性，而是受任务需求、预测编码和选择性注意的强烈调制——语言侧化在简单声音中最弱，在有意义语音中最强。这意味着 AST 描述的不是两个独立的感觉器官，而是同一皮层通过自顶向下机制动态分配注意资源的结果。

**Zatorre（2022）的频谱-时间框架**：从另一维度验证和细化 AST——右网络偏好频谱调制精度（音调、旋律），左网络偏好时间调制精度（快速时间过渡）。两种能力分别对应不同语言学需求（声调语言 vs 辅音丰富语言）。

## 关键机制

- 左颞上区：theta 振荡较高基础频率，gamma 振幅调制的时间分辨率更高
- 右颞上区：delta 振荡主导，更宽的时间积分窗口
- 两半球经胼胝体协调——慢速右半球信号为快速左半球处理提供语境框架
- 弓状束连接颞叶→额叶，可能是两半球信息整合的背侧通路

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 右半球~150–300ms 窗（音节），左半球~25–30ms 窗（音素） | fMRI、MEG 系统综述 + 元分析 | PMID:40010659 | 中-高 |
| 时间窗差异受任务需求和预测编码调制（非固定） | 综述 | PMID:40118260 | 中 |
| 右网络频谱精度，左网络时间精度（音乐/语言共用框架） | fMRI/MEG 综述 | PMID:36605556 | 中-高 |

## 争议

与 Preisig & Meyer 2025 存在张力：AST 原始版本将时间窗差异定位于底层声学属性（硬件）；2025 版综述认为主要是自顶向下过程（软件）的调制结果。此争议已登记于 `state/contested_claims.json`（C-2026-06-08-01）。

## 连接

- [[speech-perception-phonology]] — AST 是 STG 音韵处理的半球分工框架
- [[cortical-entrainment-speech]] — 夹带在左右半球的不同频段体现 AST
- [[hemispheric-asymmetry]] — AST 是半球不对称在语音领域的具体化
- [[auditory-cortex]] — 左右 A1/STG 是 AST 的物质基础

## 未解问题

- Q-speech-percep-02（中）：AST 在声调语言 vs 非声调语言使用者中是否有系统性差异？

## 修订历史

- 2026-06-08 · 创建 · 基于《声学流如何变成语言》（第119篇）· 初始置信度：中（AST 核心主张）

## 来源文章

- [[2026-06-08-speech-perception-phonology-STG]]

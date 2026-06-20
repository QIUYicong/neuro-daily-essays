---
title: 时间感受野
slug: temporal-receptive-window
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-08-13
updated: 2026-08-13
revision_count: 1
dimensions: [brain-region, whole-brain-network, cognition]
related: [intrinsic-neural-timescale, temporal-coding-hierarchy, language-network, default-mode-network, predictive-coding, auditory-cortex]
prerequisites: [intrinsic-neural-timescale, auditory-cortex]
opens_questions: [Q-temp-hier-01, Q-temp-hier-02]
source_articles: [2026-08-13-cortical-temporal-hierarchy-trw]
key_sources: ["PMID:18322098", "PMID:21414912", "PMID:36508677", "PMID:26642090", "PMID:36864133"]
---

# 时间感受野 (Temporal Receptive Window, TRW)

> **一句话定义**：皮层各区域能从外部输入中提取可靠信息的时间窗口大小——从初级听觉皮层的毫秒级到默认模式网络的数十秒级，反映该区域的外部信息时间整合能力，与内禀神经时间尺度（INT）高度相关。

## 当前理解

TRW（时间感受野）是 Hasson et al. 2008（PMID:18322098）提出的概念，测量方式是**将刺激在不同时间粒度上打乱顺序，找到打乱程度刚好导致该脑区响应下降的时间尺度**——这个时间尺度即为该区域的 TRW。

**人类皮层 TRW 梯度**（Lerner et al. 2011, PMID:21414912）：

| 区域 | TRW 近似值 | 整合内容 |
|------|----------|---------|
| 初级听觉皮层 A1 | 几百毫秒 | 瞬时声音特征 |
| 颞上沟中后部 STS | 1–4 秒 | 词汇、短句 |
| 颞顶联合区 / 楔前叶 | 12–20 秒 | 完整句子/短段落 |
| 默认模式网络核心节点（角回/后扣带/mPFC）| 30–60 秒 | 完整叙事/故事段落 |

**TRW 的功能意义**：TRW 决定了一个皮层区域能"看到"多长时间的历史——TRW 短的区域只感知当前输入，TRW 长的区域能整合跨越数十秒的上下文，支持叙事理解、情景记忆的编码和默认模式网络的自我指涉功能。

**TRW 与 INT 的关系**：TRW 是外部输入整合能力，INT 是内禀振荡时间常数，两者测量角度不同但高度相关。TRW 更依赖任务和输入的时间结构；INT 则是区域的内在属性，不依赖特定任务。

**TRW 的动态性**：Chang et al. 2022（PMID:36508677）发现，皮层信息流的时间滞后梯度（听觉→语言→注意→DMN）在叙事理解时出现，在乱序刺激时消失——说明 TRW 的激活依赖语义整合需求，不是固定的解剖滤波器。

## 关键机制

TRW 的产生依赖两个层面的机制：

**1. 内禀机制**：见 [[intrinsic-neural-timescale]] 页——NMDA 受体亚基梯度和局部递归连接梯度产生不同区域的内禀时间常数，这是 TRW 的内禀基础。

**2. 连接机制**：更高级的皮层区域通过长程连接接收来自多个低级区域的时序汇聚——这种结构上的"时间混合"放大了时间整合窗口。即使单个突触的时间常数只有几十毫秒，通过多突触链传递和递归回路，有效整合窗口可以扩展到数秒乃至数十秒。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 人类皮层TRW梯度存在（早期视觉区短→额顶联合区长） | fMRI + 打乱实验（视觉时间结构） | PMID:18322098 | 高 |
| 叙事TRW精细图：A1→STS→顶额联合区→DMN | fMRI + 叙事级别打乱（词/句/段落） | PMID:21414912 | 高 |
| 叙事时信息流滞后梯度：听觉→语言→注意→DMN | fMRI + 神经影像叙事数据集 | PMID:36508677 | 中-高 |
| 皮层同时在4Hz/2Hz/1Hz追踪词/短语/句子 | 颅内EEG + 频率标记，n=中文语音刺激 | PMID:26642090 | 高 |
| 额顶叶皮层对更长上下文做预测（预测编码层级） | fMRI n=304 + GPT-2对齐分析 | PMID:36864133 | 中-高 |

## 连接

- [[intrinsic-neural-timescale]] — INT 是 TRW 的内禀生成机制
- [[temporal-coding-hierarchy]] — TRW 与 INT 共同构成大脑多时间尺度编码的系统性描述
- [[language-network]] — 语言网络内各区域的 TRW 反映语言加工的时间层级（词→句→段落）
- [[default-mode-network]] — DMN 拥有最长 TRW，支持叙事整合和自我指涉思维
- [[predictive-coding]] — 时间层级的 TRW 梯度对应预测编码层级：高 TRW 区域预测更长时程内容
- [[auditory-cortex]] — A1 是 TRW 最短的皮层区域之一，仅追踪瞬时声音特征

## 未解问题

- Q-temp-hier-01：TRW 和 INT 的关系是相关还是因果？能否通过操控 INT（如 TMS）改变 TRW？
- 争议：Blank & Fedorenko 2020（PMID:32407994）发现语言特异性颞额区域内没有显著的 TRW 梯度——语言网络可能在所有时间尺度上并行工作，而非前后层级排列。

## 修订历史

- 2026-08-13 · 创建 · 基于《大脑皮层的时间帝国》文章 #112 · 初始置信度：高（多实验室独立复现）

## 来源文章

- [[2026-08-13-cortical-temporal-hierarchy-trw]]

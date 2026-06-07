---
title: 颞上回语音感知
slug: stg-speech-perception
domain: systems
type: region
status: established
confidence: high
created: 2026-08-20
updated: 2026-08-20
revision_count: 1
dimensions: [cellular, brain-region, whole-brain-network, cognition]
related: [auditory-dual-stream, auditory-cortex, broca-area, language-network, speech-production-circuit, superior-temporal-sulcus, anterior-temporal-lobe-hub, temporal-sampling-framework, arcuate-fasciculus]
prerequisites: [auditory-cortex, auditory-dual-stream]
opens_questions: [Q-stg-01, Q-stg-02, Q-stg-03]
source_articles: [2026-08-20-stg-speech-perception-phoneme-decoding]
key_sources: ["PMID:24482117", "PMID:34672685", "PMID:39241107", "PMID:37441880", "PMID:38687241", "PMID:22521208", "PMID:31220442"]
---

# 颞上回语音感知 (Superior Temporal Gyrus — Speech Perception)

> **一句话定义**：颞上回（STG）是将连续声学流变换为音韵表征的核心皮层区域，通过分布式声学-音韵特征检测、多时间尺度时间地标提取、约 1.7mm 音节处理模块以及自上而下的预测编码调制，将物理声波转换为大脑可用的离散语言单元，其神经活动反映的是主观感知而非声学物理真相。

## 当前理解

我们现在认为，STG 执行的语音感知计算远比早期"音素识别器"模型复杂，是一个具有多层并行机制的**动态推断系统**（Bhaya-Grossman & Chang 2021，PMID:34672685）：

**① 局部分布式特征检测（电极/毫米尺度）**

STG 局部神经元群（微小区域，ECoG 单电极所见）不对应单个音素，而是选择性响应"音韵特征"束：阻碍音（爆破/擦音）vs 共鸣音（鼻/元音），在此基础上进一步区分发音方式和发音位置（Mesgarani et al. 2014，PMID:24482117）。音素作为更抽象的范畴，是整个 STG 群体活动模式的涌现属性，而非任何局部神经元的输出。

**② 多时间尺度时间地标提取**

STG 在三个嵌套的时间尺度并行提取声学中的"时间地标"（temporal landmarks），为音节和词汇级整合提供时间脚手架：
- **毫秒尺度**：嗓音起始时间（VOT, ~15–80ms）——区分清/浊爆破音（范畴感知的神经底层）
- **音节尺度（~200ms）**：振幅包络峰值变化率（PeakRate）——音节边界的最可靠声学标记，在整个 STG 广泛分布
- **句子尺度（>200ms）**：言语起始响应——长时静音后的"重置信号"，持续约 600ms，初始化新句子的时间积分

**③ 模块化音节处理（~1.7mm 离散模块）**

超高分辨率 ECoG（50 微米间距电极，Cleary et al. 2024，PMID:39241107）揭示后颞上回中存在直径约 1.7mm 的离散功能模块，专门处理音节信息。相邻模块边界清晰，峰值响应潜期呈双峰分布（252ms 和 386ms），提示两类不同阶段的音节处理亚群体。这是联合皮层中首次发现类似初级感觉皮层（如 V1 朝向柱、桶状皮层）的精细模块化组织。

**④ 旋转动力学的时间上下文编码**

STG 群体活动在低维潜在状态空间中呈现旋转和循环动力学（Stephen et al. 2023，PMID:37441880），与运动皮层的预备旋转动力学高度相似。句子起始触发的旋转模式（持续~600ms）充当时间初始化，PeakRate 事件触发厘米尺度的同步旋转信号充当时间锚点，无需显式振荡器即可追踪时间上下文。

**⑤ 预测编码的自上而下调制**

STG 神经活动反映主观感知，而非声学物理输入（音韵修复效应）。Kim et al.（2024，PMID:38687241）证明，语言熟悉性在声学分析的最早阶段调制左 STS 的音素编码，机制可能是来自 IFG（Broca 区）的层级预测编码反馈。这使 STG 成为"自下而上的声学信息"与"自上而下的语言先验"的**汇合界面**。

## 关键机制

**声学-音韵特征编码层级**
1. 听觉核心皮层（A1）→ 频率调谐（tonotopy），时长、调制率编码
2. Belt 区（STG 内侧/上部）→ 复杂音节调制、音调起伏
3. Parabelt / STG 外侧 → 语音特异性加工，音韵特征检测开始
4. STG 腹侧面（中-前 STG）→ 振幅包络追踪（PeakRate 区域）
5. STG 后部（pSTG）→ 言语起始响应；音节处理模块（1.7mm）

**VOT 非线性编码**
STG 局部神经元对 VOT 的编码是非线性的（分类感知，categorical perception）：在 ~30ms VOT 边界两侧，响应突变而非线性变化，这是大脑实现语音范畴感知（/b/→/p/ 的突然转换）的神经基础。

**PeakRate 的时间锚点功能**
振幅包络上升率的峰值（PeakRate）是语音中最可靠的音节边界标记。STG 中广泛分布的 PeakRate 响应神经元在厘米尺度产生同步激活，像一个"全皮层时钟"，使得后续的词汇访问回路知道何时开始整合新音节的信息。

**IFG→STG 的预测编码回路**
Broca 区（IFG）向 STG 提供自上而下的预测（词汇级别和句法级别的语言预测），STG 将声学输入与这些预测进行比较，输出的是"预测误差+整合结果"，而非纯粹的声学转录。在语言熟悉的情况下，IFG 的预测高度准确，STG 的输出更多反映预测而非原始声学。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| STG 编码音韵特征而非音素（局部），音素为群体涌现 | ECoG 高伽马频段，6名被试，400说话者×500句 | PMID:24482117 | 高 |
| 三时间尺度时间地标（VOT/PeakRate/句子起始） | ECoG 综述整合，Chang 实验室多项研究 | PMID:34672685 | 高 |
| 后 STG 存在~1.7mm 离散音节处理模块，双峰潜期 | 超高分辨率 ECoG（50 μm 间距），7名被试 | PMID:39241107 | 中（需复现） |
| STG 群体活动呈旋转动力学，编码时间上下文 | ECoG + 降维分析（5-6维潜在空间） | PMID:37441880 | 中 |
| 语言熟悉性在 STS 音素编码阶段的调制（预测编码） | fMRI，英语母语者×英语/韩语 | PMID:38687241 | 中 |
| 音韵修复效应：STG 活动反映感知而非声学 | ECoG，噪声替换音素 paradigm | PMID:34672685综述引用 | 高 |
| AST：左STG短时间窗（音素），右STG长时间窗（韵律） | 行为+神经成像，多项独立研究 | PMID:22521208 综述 | 中（有争议） |

## 连接

- [[auditory-dual-stream]] — STG 是腹侧/背侧双流的起始分叉点，位于 Belt/Parabelt 层级
- [[speech-production-circuit]] — DIVA 模型的听觉目标图在 STG 中实现；产生-感知闭环在此完成
- [[broca-area]] — IFG 向 STG 提供自上而下的预测编码反馈；形成产生-感知-预测回路
- [[auditory-cortex]] — STG 的直接上游；从频率调谐到特征检测的层级过渡
- [[superior-temporal-sulcus]] — STS 在 STG 腹侧，负责多模态语音整合（视听、说话人识别）
- [[anterior-temporal-lobe-hub]] — 腹侧流中 STG 的下一站；语义整合
- [[temporal-sampling-framework]] — 理论框架：解释 STG 的振荡和时间窗机制
- [[arcuate-fasciculus]] — 连接后 STG 与 Broca 区的白质通路，是自上而下预测的硬件基础

## 未解问题

- **Q-stg-01（高优先级）**：音节模块（1.7mm，Cleary 2024）与音韵特征检测器（Mesgarani 2014）的空间关系是什么？是嵌套关系还是并列分布？
- **Q-stg-02（高优先级）**：预测编码修复（IFG→STG 自上而下）的置信度边界——STG 何时"相信"声学，何时"相信"先验？其神经实现是什么？
- **Q-stg-03（中优先级）**：声调语言（汉语）母语者与音段语言（英语）母语者的 STG 功能组织是否有可测量差异？右 STG 音调处理是否因语言经验而增强？

## 修订历史

- 2026-08-20 · 创建 · 基于《聆听的解码器》文章 #119 · 来源：Mesgarani 2014/Bhaya-Grossman 2021/Cleary 2024/Stephen 2023/Kim 2024/McGettigan 2012 · 初始置信度：高

## 来源文章

- [[2026-08-20-stg-speech-perception-phoneme-decoding]]

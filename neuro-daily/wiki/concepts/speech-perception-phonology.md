---
title: 音韵感知与颞上回
slug: speech-perception-phonology
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-06-08
updated: 2026-06-08
revision_count: 1
dimensions: [brain-region, systems, cognition, whole-brain-network]
related: [auditory-cortex, auditory-dual-stream, language-network, broca-area, cortical-entrainment-speech, asymmetric-sampling-time, categorical-perception, speech-production-circuit, predictive-coding, theta-oscillations]
prerequisites: [auditory-cortex, auditory-dual-stream, theta-oscillations]
opens_questions: [Q-speech-percep-01, Q-speech-percep-02, Q-speech-percep-03]
source_articles: [2026-06-08-speech-perception-phonology-STG]
key_sources: ["PMID:22426255", "PMID:40010659", "PMID:26023831", "PMID:38805278", "PMID:25948269", "PMID:36605556"]
---

# 音韵感知与颞上回 (Speech Perception and the Superior Temporal Gyrus)

> **一句话定义**：颞上回（STG）通过分层嵌套的皮层振荡（δ/θ/γ 三级时间窗）将连续声学流主动切割为音节和音素单元，结合左右半球不对称的时间采样策略，将声学信号转化为离散的语音符号。

## 当前理解

我们现在认为，颞上回不是被动的声学分析器，而是**主动的语音时间采样机器**。它通过以下机制将连续声学流转化为语言符号：

**三级时间窗架构**（Giraud & Poeppel 2012）：
- **Delta（1–4 Hz）**：追踪韵律/短语节律（~250ms–1s 窗口）
- **Theta（4–8 Hz）**：追踪音节节律（~125–250ms 窗口，与自然语音的 ~5 Hz 音节率吻合）
- **Gamma（25–80 Hz）**：编码音素特征（~12–40ms 窗口）

**θ-γ 交叉频率耦合**（Hyafil et al. 2015）：theta 相位调制 gamma 振幅，实现"音节时钟嵌套音素解码器"的双层架构——每个 theta 周期（~150ms）内，gamma 的振幅调制编码该音节中的音素特征序列。

**左右半球不对称**（AST 假说，Poeppel）：
- 左颞上区：偏好快速声学变化（~25–30ms 窗口），擅长辅音/音素级分析
- 右颞上区：偏好慢速变化（~150–300ms 窗口），擅长音节/韵律级分析

**预测性解码**（Leonard et al. 2015）：STG 神经元响应强度与音素序列的转移概率相关，低概率（预测误差大）的音素诱发更强响应——STG 是内置音韵统计先验的预测解码器，而非单纯的声学滤波器。

**相位门控的双重解离**（Ten Oever et al. 2024）：STG 振荡相位偏差影响音素感知，颞中回（MTG）相位偏差影响词汇频率感知——不同语言层级由不同皮层区域的振荡相位门控。

## 关键机制

**A1 → STG 层级**：
- A1：频谱-时间特征分析（音调、音强、调幅率）；语言特异性低
- STG：音素类别编码；语音序列统计；说话者身份；语言特异性显著升高
- 颞上沟（STS）：多模态整合（视听融合/McGurk 效应）；语义界面

**皮层夹带机制**：
- 皮层振荡通过网络中的兴奋-抑制动态主动追踪语音节律
- 夹带不是被动跟随，而是包含预测成分（振荡在刺激间歇中"预期"下一音节的时间）
- 注意力可以选择性增强对目标说话人语音的夹带，抑制对非目标声源的夹带（"鸡尾酒会效应"）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| δ/θ/γ 三级振荡分别追踪短语/音节/音素节率 | MEG、EEG、ECoG 多项研究综合 | PMID:22426255 | 高 |
| θ-γ CFC 实现音节-音素双层分段 | 神经建模 + EEG | PMID:26023831 | 中（模型，需体内验证） |
| 左半球~25ms 窗（音素），右半球~150ms 窗（音节） | fMRI、MEG 系统综述 | PMID:40010659 | 中-高 |
| STG 相位偏差影响音素感知，MTG 相位偏差影响词汇感知 | MEG 双重解离 | PMID:38805278 | 中（新近，需复现） |
| STG 编码语音序列转移概率（预测性解码） | ECoG 颅内记录 | PMID:25948269 | 中-高 |
| 右网络频谱精度（音调），左网络时间精度（快速过渡） | fMRI/MEG 综述 | PMID:36605556 | 中-高 |

## 连接

- [[auditory-cortex]] — A1 是 STG 的输入，提供初步声学分析
- [[auditory-dual-stream]] — 音韵处理是听觉双流的起始层级
- [[cortical-entrainment-speech]] — 皮层振荡夹带机制的详细说明
- [[asymmetric-sampling-time]] — 左右半球时间窗不对称的独立页
- [[categorical-perception]] — STG 实现音素范畴感知的心理物理学对应
- [[language-network]] — 音韵解码结果输入语言网络的词汇/句法层
- [[speech-production-circuit]] — 感觉-运动循环：语音输入反馈到运动系统（DIVA）
- [[theta-oscillations]] — θ 振荡在语音感知中的特殊角色
- [[predictive-coding]] — STG 的预测性解码框架的理论基础

## 未解问题

- Q-speech-percep-01（高）：振荡夹带对语音感知是否具有直接因果作用？
- Q-speech-percep-02（中）：AST 假说在不同语言（声调/非声调）中是否系统性差异？
- Q-speech-percep-03（中）：STG/MTG 相位解离的单细胞层面机制是什么？

## 修订历史

- 2026-06-08 · 创建 · 基于《声学流如何变成语言》（第119篇）· 初始置信度：高

## 来源文章

- [[2026-06-08-speech-perception-phonology-STG]]

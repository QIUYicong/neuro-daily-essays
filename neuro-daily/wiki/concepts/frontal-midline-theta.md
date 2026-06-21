---
title: 前额叶中线 θ 振荡（Frontal Midline Theta, FMθ）
slug: frontal-midline-theta
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-08-23
updated: 2026-08-23
revision_count: 1
dimensions: [cognition, cellular, whole-brain-network, methods]
related: [anterior-cingulate-cortex, error-related-negativity, conflict-monitoring, expected-value-of-control, response-inhibition, hyperdirect-pathway, theta-oscillations, gamma-oscillations]
prerequisites: [anterior-cingulate-cortex, theta-oscillations]
opens_questions: [Q-dacc-04]
source_articles: [2026-08-23-dacc-error-monitoring-conflict-effort]
key_sources: ["PMID:24835663", "PMID:23889930", "PMID:40930978"]
---

# 前额叶中线 θ 振荡（Frontal Midline Theta, FMθ）

> **一句话定义**：来源于 dACC/MCC 和 preSMA 的 4–8Hz 振荡，是大脑"需要认知控制"这一通用信号的电气实现——通过相位重置和跨区域 θ 相位同步，将控制需求信号（错误、冲突、努力、不确定性）统一传递给 dlPFC、STN 和运动皮层，协调控制实施。

## 当前理解

前额叶中线 θ（FMθ）是认知神经科学领域最重要的 EEG 振荡之一。Cavanagh & Frank（2014，PMID:24835663，PMCID:PMC4112145）在综合大量文献后提出：**FMθ 是大脑"认知控制需求"的通用振荡语言**。

核心证据：
1. 错误（ERN）、冲突（N2）、负性反馈（FRN）、正确但有冲突（CRN）等看似不同的 ERP 成分，都在 θ 频段（4–8Hz）共享共同的谱特征——它们是同一 θ 振荡在不同触发事件下的**相位重置**和**功率增强**
2. FMθ 来源：dACC/MCC + preSMA（源定位、EEG-fMRI 融合、颅内记录一致）
3. FMθ 通过跨区域 θ 相位同步协调远端区域，已有 **11 项独立研究复制**

## 关键机制

### θ 作为控制通信语言

```
dACC/MCC 检测到控制需求（错误/冲突/努力代价升高）
  → FMθ 功率增强 + 相位重置
  → 前额叶中线电极（Fz/FCz）负向偏转（ERN/N2/FRN 等 ERP 成分）
  → FMθ 相位与远端区域（dlPFC、运动皮层、STN）同步
  → 远端区域在 θ 相位窗口内增强信息处理
  → 认知控制实施（减慢反应、追加注意、抑制优势响应）
```

### 相位锁定机制

θ 振荡的功效来自其相位特性：
- 神经元在 θ 波谷附近放电概率最高（兴奋窗口）
- 跨区域 θ 相位同步 → 两个区域在同一 θ 周期的兴奋窗口对齐 → 突触传递效率提升
- FMθ 相位同步提供了"控制指令"从 dACC 传达到执行区域的生物物理机制

### 与 STN 的连接（冲突→抑制）

FMθ 与 STN 的 θ 相位同步是**冲突驱动的反应抑制机制**的核心：
1. dACC 检测冲突 → FMθ 功率增强
2. FMθ → STN θ 同步增强
3. STN 激活 → GPi 抑制 → 全局运动抑制
4. 赢得评估时间 → 选择正确反应
（参见 hyperdirect-pathway，#119）

### 行为预测

FMθ 功率预测：
- **Gratton 效应**：高冲突试次后的 FMθ 功率大小预测下一试次的反应减慢量
- **学习调整**：负性反馈（FRN）的 FMθ 功率预测后续强化学习的参数更新
- **决策阈值**：θ 功率与决策边界分离（boundary separation）正相关，即更谨慎的决策策略

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| ERN/N2/FRN 共享 θ 频谱基础 | EEG 时频分析 + 多任务对比 | Cavanagh & Frank 2014, PMID:24835663 | 高 |
| FMθ 来源于 dACC/MCC+preSMA | 偶极源分析 / EEG-fMRI / iEEG | 综述引用多项研究 | 高 |
| FMθ-远端区域θ同步（11项复制） | EEG 相位分析，多个实验室 | Cavanagh & Frank 2014 | 高 |
| FMθ 预测 Gratton 效应 | 单试次 EEG-行为相关 | Cavanagh & Frank 2014 | 高 |
| mPFC θ 功率随 DBS 增加，认知改善 | 临床 EEG + DBS 实验 | Glewwe 2025, PMID:40930978 | 中（临床群体） |

## 频率特异性

FMθ 在灵长类（包括人类）的频率为 **4–8Hz**，不同于大鼠海马 θ（4–12Hz）。这个频率范围被认为是组织大尺度脑区间协调的"最优频率"——既足够快以在单次试次内实施控制，又足够慢以协调相距较远的皮层区域。

## 未解问题

- Q-dacc-04: FMθ 与局部 γ 振荡如何协作？是否存在"θ-γ 耦合"实现控制计算？

## 连接

- [[anterior-cingulate-cortex]] — dACC/MCC 是 FMθ 的主要生成器
- [[error-related-negativity]] — ERN 是 FMθ 在错误事件时刻的时域/频域表达
- [[conflict-monitoring]] — N2 成分是 FMθ 在冲突时刻的表达；θ 功率预测 Gratton 效应
- [[expected-value-of-control]] — FMθ 是 EVC 计算结果驱动控制实施的振荡机制
- [[response-inhibition]] — FMθ→STN 同步将冲突信号转化为全局运动抑制
- [[hyperdirect-pathway]] — dACC 通过 FMθ 激活 STN 超直接通路
- [[theta-oscillations]] — FMθ 是 θ 振荡在前额叶认知控制语境下的特异化实例

## 修订历史

- 2026-08-23 · 创建 · 基于《背侧前扣带皮层的三重计算》文章（#121）· 初始置信度：高

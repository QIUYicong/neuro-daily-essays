---
title: 失匹配负波（MMN）
slug: mismatch-negativity
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-21
updated: 2026-07-21
revision_count: 1
dimensions: [synaptic, cellular, brain-region, cognition, methods]
related: [auditory-cortex, predictive-coding, nmda-receptor, global-workspace-theory]
prerequisites: [auditory-cortex, nmda-receptor, predictive-coding]
opens_questions: [Q-ac-02]
source_articles: [2026-07-21-auditory-cortex-tonotopy-speech]
key_sources: ["PMID:30022729", "PMID:9658025"]
---

# 失匹配负波（Mismatch Negativity, MMN）

> **一句话定义**：当听觉输入违反大脑维护的声学统计模型（"预期"）时，在偏差音后约150-250毫秒出现的皮层自动负电位，是预测编码系统在宏观神经群体层面的预测误差信号，无需注意力参与。

## 当前理解

我们现在认为，MMN 是大脑主动维护声学规律模型并持续监测其违反的直接神经证据，也是**预测编码**在听觉系统中最干净的体现之一。

**关键性质**：
- **前注意性（Preattentive）**：MMN 在睡眠、麻醉、昏迷中依然存在，不需要主动注意
- **发育早期**：新生儿出生时即可记录到MMN，说明预测性听觉处理是大脑出厂设置
- **语言特化**：人类MMN对母语音素边界处的声学变化比非音素变化更大，而这种差异在成年后学习外语时较弱——是音素关键期的神经标志

**与刺激特异性适应（SSA）的关系**：
- SSA（stimulus-specific adaptation）：单神经元层面，频率特异性适应导致对重复音响应抑制
- MMN：人群/EEG层面，不能被简单适应完全解释，包含真实的"偏差检测"成分
- Carbajal & Malmierca 2018 将两者统一为预测编码的 microscopic/macroscopic 层面，但两者精确对应关系仍有争议

## 关键机制

### 预测编码框架
大脑对声学规律（频率、时序、模式）维护内部统计模型 → 每个刺激产生预测 → 实际输入与预测比较 → 误差信号向上传递。MMN 是层级听觉系统中预测误差传播的 EEG 表现。

### 层级梯度
预测误差沿听觉通路逐级放大：
- 下丘皮质：极小贡献
- 非丘系丘脑：中等贡献  
- A1（初级听觉皮层）：约25%偏差检测
- 带区（belt）：约50-80%偏差检测

### NMDA 受体依赖
SSA 和 MMN 均被 NMDA 受体拮抗剂（氯胺酮）显著减弱，提示 NMDA 受体的巧合检测功能是预测编码的分子基础——NMDA 受体同时需要当前输入（谷氨酸）和历史预期（突触后去极化）才能激活，天然适合检测"当前是否符合预期"。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| MMN在麻醉下持续存在，是前注意性信号 | 多个麻醉/睡眠研究的EEG记录 | PMID:9658025 | 高 |
| SSA+MMN是同一预测误差机制的层级体现 | 综述：跨物种、跨方法的收敛证据 | PMID:30022729 (PMC6053868) | 高（综述） |
| 带区产生~80%偏差检测（清醒小鼠低强度） | 在体小鼠听觉皮层电生理 | PMID:30022729 | 中-高 |
| NMDA受体拮抗剂削弱SSA和MMN | 药理学操纵实验 | PMID:30022729 | 高 |

## 连接

- [[auditory-cortex]] — MMN主要产生于A1和带区，是听觉皮层预测编码的神经信号
- [[predictive-coding]] — MMN是预测编码框架在感觉皮层的最清晰体现之一
- [[nmda-receptor]] — NMDA受体是MMN/SSA的分子基础，提供巧合检测功能
- [[global-workspace-theory]] — P3波（有意识注意后）vs MMN（无意识预测误差）的对比揭示意识/无意识的时间边界

## 未解问题

- **Q-ac-02**（高优先级）：SSA和MMN是否真的是同一预测误差机制？还是存在某种程度的分离？精确的计算对应关系仍有争议。

## 修订历史

- 2026-07-21 · 创建 · 基于《听觉皮层》文章 · 来源：PMID:30022729, 9658025

## 来源文章

- [[2026-07-21-auditory-cortex-tonotopy-speech]]

---
title: 情绪调节
slug: emotion-regulation
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-25
updated: 2026-08-25
revision_count: 1
dimensions: [brain-region, whole-brain-network, cognition, behavior, disease]
related: [vmPFC, amygdala, fear-extinction, cognitive-reappraisal, anterior-cingulate-cortex, prefrontal-cortex, insular-cortex, interoception, hpa-axis, active-inference]
prerequisites: [amygdala, prefrontal-cortex, fear-extinction]
opens_questions: [Q-vmPFC-01, Q-vmPFC-03]
source_articles: [2026-08-25-vmPFC-sgACC-emotion-regulation]
key_sources: ["PMID:12495527", "PMID:23765157", "PMID:26617500", "PMCID:PMC4637424", "PMID:32960214", "PMID:19693001"]
---

# 情绪调节 (Emotion Regulation)

> **一句话定义**：个体通过内部（认知重评、注意部署、情绪压制）或外部手段修改情绪反应的时程、强度和表达的过程；其神经基础是以 vmPFC 为枢纽的前额叶-杏仁核-脑干多层级控制回路，通过对杏仁核输出的精细调制实现情绪的灵活应对。

## 当前理解

我们现在认为，情绪调节不是单一的"关掉情绪"机制，而是多种策略的神经实现集合，不同策略使用部分重叠但有显著差异的神经回路。主要策略包括：

1. **认知重评**（cognitive reappraisal）：改变对刺激的解读（→ vmPFC + vlPFC + 语义网络，见 cognitive-reappraisal 页面）
2. **注意部署**（attentional deployment）：转移对情绪触发物的注意（→ dlPFC + 背侧注意网络）
3. **情绪压制**（expressive suppression）：抑制情绪的表达，但不改变内部体验（→ 更高代价，更多 vlPFC 激活，但效果不持久）
4. **习惯化/消退**（habituation/extinction）：反复接触不再产生恐惧的刺激（→ IL/vmPFC → 腹侧 ITC → CeM 抑制回路）
5. **内感觉重估**（interoceptive reappraisal）：重新解读身体信号（→ 岛叶 + vmPFC）

从预测编码（active inference）视角，情绪调节是**精度权重的主动调整**：vmPFC 通过修改杏仁核/内感觉信号的精度权重，使某些情绪输入的"上调优先级"被降低，实现情绪调节。

**认知重评 vs 压制的代价差异**：长期使用情绪压制会产生更高的认知负荷（需要主动抑制自动化情绪表达），且在社会互动中代价更大（他人感受到的真实情绪信号减少）。认知重评在长期使用中神经代价更低，是心理健康文献中更推荐的调节策略。

## 关键机制

### 系统层级

```
外部/内部情绪触发 → 杏仁核 BLA（快速评估，<12ms 低路 / ~30ms 高路）
                            ↓
                   输出：自主神经激活、注意偏向、防御行为、内分泌应答
                            ↑
[调节层]
   vlPFC/dlPFC（认知评估）→ vmPFC（情绪整合）→ 杏仁核调制
   岛叶（内感觉监测）↗                ↓
   海马（情景-记忆）→ vmPFC       sgACC → 下丘脑/LC/DRN（自主神经和神经调质）
```

### 认知重评的前额叶层级

vlPFC（语义重构）→ vmPFC（情绪价值整合）→ 杏仁核（负向有效连接）→ 情绪输出↓
Buhle 2014 元分析：外侧 PFC + 语义颞叶区最稳健，vmPFC 可能是整合而非执行节点

### 恐惧消退/习惯化回路

IL/vmPFC → 腹侧 ITC（ICMMV）→ CeM 抑制 → 恐惧行为↓
同时：IL/vmPFC → BLA 消退神经元 → 安全信号

详见 [[fear-extinction]] 页面

### sgACC 轴（自主神经调节）

sgACC（BA25）→ LC/DRN/PAG/下丘脑：将情绪状态的皮层评估转化为神经调质和自主神经变化
正常功能：精准调节 5-HT/NE 基线、自主神经激活
抑郁症：持续过度激活，形成自我维持的负性情绪循环

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 认知重评时 PFC↑ + 杏仁核↓ | fMRI 实验 | Ochsner et al. 2002, PMID:12495527 | 高（多次重复）|
| 重评最稳健激活区：外侧 PFC + 颞叶语义区 | 48 项研究元分析 | Buhle et al. 2014, PMID:23765157 | 高 |
| vmPFC→杏仁核负向有效连接 | DCM 分析 | Steward et al. 2021, PMID:32960214 | 中-高 |
| IL 促进消退（恐惧调节的 vmPFC 基础）| 局部灭活，大鼠 | Giustino & Maren 2015, PMID:26617500 | 高 |
| sgACC 持续过度激活 → 抑郁（调节失败） | PET 纵向 + DBS 治疗 | Drevets 1999 + Mayberg 2005 | 高 |

## 连接

- [[vmPFC]] — 情绪调节的核心前额叶枢纽
- [[amygdala]] — 被调节的靶标（被 vmPFC 抑制）
- [[cognitive-reappraisal]] — 情绪调节的最重要认知策略之一
- [[fear-extinction]] — 情绪调节的最基本学习形式（习惯化/消退）
- [[active-inference]] — 从预测编码视角理解情绪调节（精度权重调整）
- [[insular-cortex]] — 内感觉信号提供情绪调节的原始材料
- [[interoception]] — 内感觉监测是情绪调节的感觉基础
- [[prefrontal-cortex]] — 情绪调节的上层认知控制来自 PFC 系统
- [[anterior-cingulate-cortex]] — rACC/sgACC 参与情绪调节和情感疼痛

## 未解问题

- Q-vmPFC-01（高优先级）：vmPFC 和 dlPFC 在情绪调节中的功能边界
- Q-vmPFC-03（高优先级）：PTSD 中 vmPFC 消退回忆障碍的精确机制

## 修订历史

- 2026-08-25 · 创建 · 基于《驯化杏仁核：vmPFC 与 sgACC》(#123) · 初始置信度：高

## 来源文章

- [[2026-08-25-vmPFC-sgACC-emotion-regulation]]

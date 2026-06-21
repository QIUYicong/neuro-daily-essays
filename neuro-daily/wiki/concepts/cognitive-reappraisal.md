---
title: 认知重评
slug: cognitive-reappraisal
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-25
updated: 2026-08-25
revision_count: 1
dimensions: [cognition, brain-region, behavior]
related: [emotion-regulation, vmPFC, amygdala, prefrontal-cortex, fear-extinction, active-inference, working-memory]
prerequisites: [emotion-regulation, amygdala, prefrontal-cortex]
opens_questions: [Q-vmPFC-01]
source_articles: [2026-08-25-vmPFC-sgACC-emotion-regulation]
key_sources: ["PMID:12495527", "PMID:15488398", "PMID:23765157", "PMID:37507228", "PMID:32960214"]
---

# 认知重评 (Cognitive Reappraisal)

> **一句话定义**：通过重新解释情绪触发事件的含义来改变其情绪影响的调节策略（"这不是灾难，而是一次学习机会"），是人类最有效且长期使用代价最低的情绪调节策略之一，神经基础是 vlPFC/dlPFC（语义重构）→ vmPFC（情绪整合）→ 杏仁核（抑制）三层级回路。

## 当前理解

我们现在认为，认知重评是人类情绪调节能力中独特的认知策略，依赖高度发达的前额叶皮层（特别是灵长类专有的外侧 PFC 和 vmPFC）。

**与情绪压制的对比**：
- **认知重评**：在情绪发生之前（生成阶段）改变情绪的意义，修改情绪在起点的评估过程，长期使用代价低
- **情绪压制**：在情绪产生之后（表达阶段）抑制其外部表达，不改变内部体验，长期使用代价高（持续认知负荷），且对主观体验改善有限

**神经机制的层级**：
Buhle et al. 2014 元分析（PMID:23765157，48 项 fMRI 研究）确认，重评最稳定激活区是**外侧 PFC（vlPFC/dlPFC）+ 颞叶语义区**，而非 vmPFC——这意味着重评的核心过程在于**语义重构**（给刺激赋予新含义），而 vmPFC 是整合阶段（新含义的情绪价值评估）。

He et al. 2023 (PMID:37507228) 的 TMS-fMRI 实验补充了因果性证据：刺激 vlPFC → vmPFC 激活增加，同时杏仁核和岛叶激活减少，建立了明确的信号传导方向。

**有效性边界**：
- 对可以语义重新解释的事件非常有效
- 对感官驱动的强烈情绪（如急性疼痛、创伤闪回）效果有限
- 需要认知资源，在认知负荷高或注意力严重分散时效果降低

## 关键机制

### 三层级回路

```
(1) 情绪触发事件 → 杏仁核（底层自动评估，~12-30ms）
                          ↓ 初始情绪激活

(2) 认知重评策略激活：
    vlPFC（外侧前额叶）+ 颞叶语义区 → 重新建构事件含义
                    ↓
(3) vmPFC（腹内侧前额叶）接收新的语义-情绪估价
                    ↓ 负向有效连接
(4) 杏仁核激活↓ + 岛叶（内感觉）激活↓
                    ↓
(5) 情绪反应（主观不适度、自主神经激活）减少
```

### Steward 2021 动态因果模型

直接估计重评过程中的有效连接：vmPFC→杏仁核存在负向驱动效应，是"将前额叶认知控制转化为皮层下情绪压制"的主要通道（PMID:32960214）。

### 重评 vs 注意转移

- **重评**：不移走注意力，而是改变对注意到的事物的解释；长期效果更好
- **注意转移（suppression/distraction）**：避免情绪加工；短期快速，但创伤相关刺激容易复现

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 重评→外侧 PFC↑ + 杏仁核↓ | fMRI（基础实验） | Ochsner et al. 2002, PMID:12495527 | 高（多次重复）|
| 重评→双向调节（上调↑，下调↓）均涉及 PFC | fMRI | Ochsner et al. 2004, PMID:15488398 | 高 |
| 48 项研究元分析：vlPFC + 颞叶语义区最稳健，vmPFC 非稳定激活区 | 元分析 | Buhle et al. 2014, PMID:23765157 | 高 |
| vlPFC TMS → vmPFC↑ + 杏仁核↓（因果确认三层级） | TMS-fMRI | He et al. 2023, PMID:37507228 | 中（单项）|
| vmPFC→杏仁核负向有效连接（DCM 量化） | 动态因果模型 | Steward et al. 2021, PMID:32960214 | 中-高 |

## 连接

- [[emotion-regulation]] — 认知重评是情绪调节策略的一种，也是研究最多的策略
- [[vmPFC]] — 认知重评回路的前额叶整合节点
- [[amygdala]] — 被重评过程通过 vmPFC 抑制的情绪输出中枢
- [[prefrontal-cortex]] — vlPFC/dlPFC 是语义重构的起点
- [[working-memory]] — 重评过程需要工作记忆维持新的解释框架
- [[fear-extinction]] — 功能上与消退相关：两者均通过 vmPFC→杏仁核通路减少情绪反应，但机制有差异

## 未解问题

- Q-vmPFC-01（高优先级）：vmPFC 在重评中是不稳定激活的原因——是策略依赖（重评类型？）、时间分辨率问题（整合阶段而非执行阶段）、还是个体差异较大导致元分析中被稀释？

## 修订历史

- 2026-08-25 · 创建 · 基于《驯化杏仁核：vmPFC 与 sgACC》(#123) · 初始置信度：高

## 来源文章

- [[2026-08-25-vmPFC-sgACC-emotion-regulation]]

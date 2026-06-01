---
title: 创伤后应激障碍（PTSD）
slug: ptsd
domain: diseases
type: disease
status: established
confidence: high
created: 2026-06-24
updated: 2026-06-24
revision_count: 1
dimensions: [brain-region, whole-brain-network, behavior, cognition, disease]
related: [fear-extinction, fear-conditioning, amygdala, prefrontal-cortex, hippocampal-circuit, norepinephrine-locus-coeruleus, reconsolidation]
prerequisites: [fear-extinction, amygdala, prefrontal-cortex]
opens_questions: [Q-ptsd-vmPFC-biomarker, Q-ptsd-reconsolidation-window, Q-ptsd-hippocampus-cause-effect]
source_articles: [2026-06-24-fear-extinction-circuits]
key_sources: ["PMID:19748076", "PMID:38116070", "PMID:17217927", "PMID:12422216"]
---

# 创伤后应激障碍（PTSD）

> **一句话定义**：以恐惧消退机制的三环节系统性失效为核心神经病理的焦虑障碍——vmPFC调控能力下降、杏仁核反应过激、海马情景编码紊乱，共同导致创伤记忆无法被正常抑制，恐惧反应在各种线索触发下反复全强度重现。

## 当前理解

PTSD的神经生物学核心可以概括为：**正常的恐惧消退机制，在三个关键节点上同时出了问题**。

从神经回路角度看，健康的消退依赖：
1. vmPFC（IL皮层）存储和提取消退安全记忆
2. 杏仁核ITC/BLA消退细胞接受vmPFC驱动、抑制CeA输出
3. 海马精确编码情景（区分"危险情景"与"当前安全情景"）

PTSD患者的神经影像研究（Milad et al. 2009，PMID:19748076）揭示了三个并发的回路失调：

**失调一：vmPFC激活不足**。PTSD患者在消退回忆测试时，vmPFC的激活显著低于对照组，且vmPFC激活量与消退记忆质量正相关。重要的是，PTSD患者在消退**训练**当天表现与对照组相当，但次日**提取**消退记忆时失败。这意味着问题不在于无法学习消退，而在于无法在应激状态下提取消退记忆。

**失调二：杏仁核过度激活**。PTSD患者对CS（及相关线索）的杏仁核激活显著高于对照组，且过激的杏仁核会通过BLA→IL前馈抑制通路，进一步压制已经孱弱的vmPFC功能——形成自我强化的恶性循环。

**失调三：海马情景辨别能力受损**。PTSD患者海马（尤其是CA3和齿状回）体积缩小，神经新生减少，导致对情景的精确辨别能力下降。患者无法清楚区分"当前安全情景"与"创伤情景"，消退记忆的情景特异性无法被正确调取。

## 关键机制

### PTSD的三环节失效模型

```
正常消退回路：
vmPFC/IL → ITC(腹侧) → CeA抑制 → 恐惧被压制
             ↑
海马vHPC → BLA(消退细胞) → ITC驱动

PTSD状态下：
vmPFC/IL（低活）→ ITC驱动不足 → CeA持续激活 → 恐惧持续
杏仁核（过激）→ 反向抑制vmPFC → vmPFC更弱
海马（受损）→ 情景辨别失败 → 安全情景线索无法激活消退回路
```

### 应激与NE在PTSD维持中的角色

高创伤暴露 → 蓝斑（LC）长期高激活 → 持续高NE水平在BLA中 → BLA慢性过激 → vmPFC持续被BLA前馈抑制 → 慢性消退提取障碍。Maren（2022，PMID:35520882）的研究揭示，NE-BLA-IL通路在急性应激下破坏消退的机制，可能也是PTSD中消退慢性失效的维持机制。

### dACC的异常激活

PTSD患者背侧前扣带回（dACC）在消退回忆时异常高激活，与vmPFC低激活形成对照。dACC通常在威胁不确定时（"危险还是安全？"）激活，dACC的持续过高激活可能反映了PTSD患者永久处于的威胁评估状态，并通过抑制vmPFC功能维持恐惧优势。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| PTSD患者消退训练正常但回忆次日失败 | 两日fMRI恐惧-消退范式，皮肤电导 | PMID:19748076（摘要） | 高 |
| PTSD的vmPFC低激活预测消退回忆质量 | 全样本fMRI相关分析 | PMID:19748076（摘要）；PMID:17217927（摘要） | 中-高 |
| PTSD患者杏仁核对CS过激 | fMRI杏仁核ROI分析 | PMID:19748076（摘要）；PMID:38116070（PMC开放） | 高 |
| PTSD海马体积缩小（CA3/DG尤甚） | MRI体积测量，多研究荟萃分析 | PMID:38116070（PMC开放） | 高 |
| β-受体阻断可救援急性应激后消退缺陷 | 动物模型BLA内普萘洛尔注射 | PMID:35520882（PMC开放） | 中（尚未临床验证） |

## 连接

- [[fear-extinction]] — PTSD是消退提取障碍的疾病体现；vmPFC低下是核心神经基础
- [[amygdala]] — 杏仁核过激是PTSD的主要驱动力之一；BLA-vmPFC反向抑制形成恶性循环
- [[prefrontal-cortex]] — vmPFC（IL对应区）是PTSD的关键受损区域和治疗靶点
- [[hippocampal-circuit]] — 海马萎缩导致情景辨别失败，消退的情景特异性崩溃
- [[norepinephrine-locus-coeruleus]] — 慢性LC-NE过激可能是PTSD维持消退失效的机制
- [[reconsolidation]] — 消退-重巩固交叉可能提供更有效的治疗窗口

## 未解问题

- Q-ptsd-vmPFC-biomarker（高优先级）：vmPFC激活量是否可作为PTSD暴露疗法的预测性生物标志物？
- Q-ptsd-reconsolidation-window（高优先级）：对多年历史的创伤记忆，重巩固窗口是否依然可以被激活用于治疗？
- Q-ptsd-hippocampus-cause-effect（中优先级）：PTSD中海马萎缩是创伤暴露的结果，还是预先存在的易感性因素？

## 修订历史

- 2026-06-24 · 创建 · 基于《消退不等于遗忘》一文 · 初始置信度：高（神经影像证据充分，回路机制清晰；治疗转化的某些方面仍是新兴研究）

## 来源文章

- [[2026-06-24-fear-extinction-circuits]]

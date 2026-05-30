---
title: 前额叶皮层（PFC）
slug: prefrontal-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-06-05
updated: 2026-06-14
revision_count: 2
dimensions: [brain-region, cognition, microcircuit, behavior]
related: [working-memory, persistent-activity, gamma-oscillations, pv-interneurons, sst-interneurons, vip-interneurons, nmda-receptor, memory-consolidation, fear-extinction, basolateral-amygdala, hippocampal-circuit]
prerequisites: [pyramidal-neuron, pv-interneurons, nmda-receptor]
opens_questions: [Q-wm-pfc-content-vs-control, Q-pfc-human-specificity]
source_articles: [2026-06-05-prefrontal-working-memory, 2026-06-14-amygdala-fear-circuit]
key_sources: ["PMID:7695894", "PMID:21345366", "PMID:41478518", "PMID:39381500", "PMID:20303254"]
---

# 前额叶皮层（Prefrontal Cortex, PFC）

> **一句话定义**：大脑额叶最前部的新皮层区域，是认知控制、工作记忆、决策和计划的关键神经基础；背外侧前额叶皮层（dlPFC）的循环回路是工作记忆维持的核心脑区。

## 当前理解

前额叶皮层（PFC）是灵长类特别发达的新皮层区域，在人类中占额叶面积的约 30%。其主要功能包括：
- **工作记忆**（working memory）：dlPFC 的核心功能
- **认知控制**（cognitive control）：目标维持、分心抑制
- **决策与计划**（decision making / planning）
- **社会认知与情绪调节**：vmPFC/OFC 参与

### dlPFC 的层级结构与工作记忆回路

背外侧前额叶皮层（dlPFC，对应 Brodmann 区 9/46）的工作记忆微回路（Hughes et al. 2024）：

- **第 2/3 层（浅层）**：锥体细胞水平侧支最密集，循环兴奋回路的核心；工作记忆内容编码的主要场所
  - 深部第 3 层（L3d）：精神分裂症中树突棘损失最严重的亚层
- **第 5/6 层（深层）**：时序控制和皮层下（丘脑、基底核）通信
- **抑制性中间神经元网络**：
  - PV 篮状细胞：γ 生成，围周抑制，工作记忆时序精度
  - SST Martinotti 细胞：树突控制，选择性访问
  - VIP/CR 双极细胞：去抑制，行为信号调制

### 多巴胺调节（Arnsten 2011, PMID:21345366）

dlPFC 工作记忆对多巴胺浓度极度敏感（倒 U 型关系）：
- D1 受体适中激活 → α-2A 受体抑制 cAMP → 抑制 HCN 通道 → 回路增强
- D1 受体过激活（急性压力、可卡因）→ cAMP 升高 → HCN 激活 → 回路"断开"
- D1 不足（衰老、睡眠剥夺）→ 背景噪声增加，信噪比下降

### PFC 的跨物种比较（Boroujeni et al. 2026, PMID:41478518）

- 啮齿类 PFC 缺乏灵长类 dlPFC 的第 3 层深部特化
- 猕猴 → 人类：dlPFC 进一步扩大，L3d 锥体细胞更高、棘更多、连接更复杂
- 人类特有的语言/符号工作记忆是否有独特神经机制，目前无法侵入性记录验证

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| dlPFC 延迟期放电是工作记忆的神经相关物 | 猕猴电生理 + 损毁实验 | Goldman-Rakic 1995 (PMID:7695894) | 高 |
| D1 受体倒 U 型调节 dlPFC 回路 | 猕猴微量注射 + 单单元记录 | Arnsten 2011 (PMID:21345366, PMC:PMC3115784) | 高 |
| dlPFC L3d 在精神分裂症中选择性损伤 | 人类尸检 | Arnsten 2011; Hughes 2024 | 高 |
| PFC 中间神经元多样性支撑认知功能 | 灵长类 + 啮齿类综述 | Boroujeni et al. 2026 (PMID:41478518, PMC:PMC12924665) | 高 |

### mPFC 的情绪调控功能（2026-06-14 新增）

**边缘下皮层（IL-PFC / Infralimbic Cortex）→ 恐惧消退**（Sotres-Bayon & Quirk 2010, PMC2878722）：

IL-PFC 是对应啮齿类"边缘下皮层"的亚区（对应人类 vmPFC/Brodmann 区 25）。消退训练后，IL-PFC 激活：
- IL-PFC → 嵌合细胞群（ITC cells，GABAergic）→ 抑制 CeM 输出 → 恐惧行为压制
- IL-PFC 损毁：不影响恐惧**获得**，但消退后恐惧更容易复发（消退提取障碍）
- IL-PFC 是暴露疗法发挥作用的神经基础

**边缘前皮层（PL-PFC / Prelimbic Cortex）→ 恐惧表达**：
PL-PFC → 基底杏仁核（BA）→ CeM → 恐惧行为
- PL 损毁：不影响恐惧获得；减弱恐惧表达
- PL 和 IL 构成**解剖对立的双模控制器**：IL 激活时 ITC 压制 CeM，PL 激活时 BA 驱动 CeM

**海马-mPFC 情境门控**：
- 腹侧海马（vHipp）→ mPFC 投射提供当前情境信息
- 在消退情境 → vHipp 激活 IL → ITC 压制 CeM → 无恐惧
- 在原始恐惧情境 → vHipp 信号改变 → PL 模式 → CeM 激活 → 恐惧复发（Renewal 现象的回路基础）

## 连接

- [[working-memory]] — dlPFC 是工作记忆的关键脑区
- [[persistent-activity]] — dlPFC 的延迟期放电是工作记忆持续活动的场所
- [[gamma-oscillations]] — dlPFC 中 γ 爆发是工作记忆的振荡载体
- [[pv-interneurons]] — dlPFC 中 PV 篮状细胞生成 γ，调控工作记忆时序
- [[memory-consolidation]] — PFC 是记忆巩固后远端记忆的皮层存储库
- [[fear-extinction]] — IL-PFC 经 ITC 细胞驱动消退表达；PL-PFC 经 BA 驱动恐惧表达
- [[basolateral-amygdala]] — PFC 对 BLA 的双向调控（IL→ITC→CeM 消退；PL→BA→CeM 恐惧）
- [[hippocampal-circuit]] — vHipp→mPFC 提供情境信息，门控 IL/PL 的相对激活

## 未解问题

- Q-wm-pfc-content-vs-control：PFC 是工作记忆内容的存储器，还是对感觉皮层的调度中心？
- Q-pfc-human-specificity：人类 dlPFC 是否有超越猕猴的特异性工作记忆机制？

## 修订历史

- 2026-06-05 · 创建 · 基于《γ爆发、静默突触与持续放电》一文
- 2026-06-14 · 修订 · 基于《杏仁核的恐惧算法》一文 · 新增 mPFC 的情绪调控功能（IL-PFC→消退，PL-PFC→恐惧），ITC 细胞通路，vHipp-mPFC 情境门控；related 新增 fear-extinction, basolateral-amygdala, hippocampal-circuit；key_sources 新增 PMID:20303254

## 来源文章

- [[2026-06-05-prefrontal-working-memory]]
- [[2026-06-14-amygdala-fear-circuit]]

---
title: 精神分裂症
slug: schizophrenia
domain: diseases
type: disease
status: mainstream
confidence: medium
created: 2026-07-20
updated: 2026-07-20
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, cognition, disease]
related: [pv-interneurons, gamma-oscillations, working-memory, nmda-receptor, dopamine-reward-prediction-error, prefrontal-cortex, ei-balance, hebbian-learning]
prerequisites: [pv-interneurons, nmda-receptor, gamma-oscillations, working-memory]
opens_questions: [Q-pv-schizophrenia-causal, Q-gamma-wm-causality, Q-sz-dopamine-gaba-interface]
source_articles: [2026-07-20-gamma-oscillations-ping-ing-mechanism]
key_sources: ["PMID:22355184", "PMID:22218597", "PMID:25863358", "PMID:39381500", "PMID:41478518", "PMID:19396159"]
---

# 精神分裂症 (Schizophrenia)

> **一句话定义**：以阳性症状（幻觉、妄想）、阴性症状（情感平淡、意志减退）和认知症状（工作记忆、注意、执行功能缺陷）为核心的精神疾病；其神经回路基础日益被理解为 PV+ 中间神经元功能损伤导致的前额叶 γ 振荡缺陷和多巴胺-谷氨酸信号失调。

## 当前理解

我们现在认为，精神分裂症的病理生理学不是单一神经递质异常，而是**多层级的回路功能障碍**，其中最核心、证据最充分的机制涉及前额叶 PV+ 中间神经元的功能损伤。

**PV-GAD67-γ 轴（核心分子-回路链）**：
1. NMDA 受体低活（可能是最上游触发因素之一，遗传+环境共同作用）
2. → PV 细胞（高密度 NR2A-NMDA）特异性受损
3. → GAD67（GABA 合成限速酶）mRNA 和蛋白下调
4. → PV 轴突终末 GABA 储量减少，IPSP 幅度降低
5. → PING 回路时序精度崩溃，γ 振荡功率减弱
6. → 工作记忆、注意、执行功能缺陷（认知症状）

这条链从分子（NMDA-R/GAD67/GABA）到细胞（PV 篮状细胞功能）到回路（PING/γ 振荡）到行为（认知缺陷）是目前精神分裂症研究中最清晰的机制路径之一。

**多巴胺假说的位置**：
多巴胺 D2 受体过度激活（皮质下纹状体）和前额叶 D1 受体信号不足并存，与阳性症状（幻觉、妄想）和阴性/认知症状分别相关。然而，多巴胺异常与谷氨酸/PV 功能损伤的**界面机制**仍不清楚：PV 细胞损伤是否因多巴胺信号紊乱导致，或二者是独立的并行病理？这是当前研究的核心争议点之一。

**遗传基础的复杂性**：
精神分裂症遗传风险高度多基因（GWAS 识别 >100 基因位点），DISC1、NRXN1、CNTN4 等神经连接相关基因以及 C4A（补体）基因均在风险集中。GWAS 最强信号之一在 MHC 区域（C4A 基因），提示突触剪枝异常可能是病因之一（与 [[synaptic-pruning]] 的关联）。

## 关键机制

**PV-γ 回路损伤机制**（见 [[pv-interneurons]] 和 [[gamma-oscillations]]）：
- GAD67 mRNA 下调在精神分裂症前额叶尸检中高度一致（多个独立实验室）
- 是最可重复的精神分裂症神经病理发现之一
- GAD67 下调导致 GABA 合成不足 → IPSP 振幅缩小 → PING γ 精度下降

**NMDA 受体假说与 PV 细胞的关联**（Gonzalez-Burgos & Lewis 2012, PMID:22355184）：
- PV 篮状细胞表达高密度 NR2A 亚型 NMDA 受体
- NMDA 拮抗剂（PCP、氯胺酮）优先减弱 PV 细胞兴奋性，诱导精神分裂症样症状
- 这是 NMDA 低活直接打击 PV-γ 回路的机制基础

**工作记忆缺陷的振荡机制**：
- 健康人执行 WM 任务时 dlPFC γ 功率升高（任务诱发 γ）
- 精神分裂症患者此 γ 升高缺失或减弱（多项 MEG/EEG 研究）
- 与认知损伤程度显著相关（Gonzalez-Burgos et al. 2015, PMID:25863358）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 精神分裂症前额叶 GAD67 mRNA 一致下调 | 多项尸检研究（qPCR，原位杂交）| PMID:22218597 | 高（多实验室复现）|
| WM 任务期间前额叶 γ 功率缺失与认知损伤相关 | MEG/EEG，患者 vs 健康对照 | PMID:25863358 | 高 |
| NMDA 低活优先损伤 PV 细胞（NR2A 密度高） | 体外模型 + 计算模型 | PMID:22355184 | 中-高（需体内直接验证）|
| PV 细胞损伤是认知症状（非阳性症状）的核心回路基础 | PV 特异性光遗传学 + 行为测试（动物） | PMID:19396159 | 中（尚无直接人类因果证据）|
| dlPFC PV mRNA 减少，与 γ 功率降低正相关 | 尸检蛋白组学 + 影像 | PMID:39381500 | 高 |

## 连接

- [[pv-interneurons]] — 精神分裂症最核心的细胞损伤靶点（GAD67 下调）
- [[gamma-oscillations]] — PING 崩溃 → γ 功率下降 → WM 缺陷
- [[working-memory]] — 认知症状的核心表现；γ 振荡是其神经回路基础
- [[nmda-receptor]] — NMDA 低活假说；PCP/氯胺酮模型
- [[dopamine-reward-prediction-error]] — 多巴胺 D2 过度激活（皮质下）与阳性症状
- [[ei-balance]] — 精神分裂症是 E/I 失衡的典型案例（PV 损伤 → 抑制↓ → E/I 比↑）

## 未解问题

- Q-pv-schizophrenia-causal：精神分裂症中 PV GAD67 下调是疾病病因、代偿性反应还是继发改变？（难以从人类尸检判断因果方向）
- Q-gamma-wm-causality：γ 功率缺失是认知缺陷的直接原因，还是 PV 损伤的另一个结果？
- Q-sz-dopamine-gaba-interface（新问题）：多巴胺异常（D2 过度激活）如何与 PV-GABA 损伤界面互动？是并行病理还是因果关系？

## 修订历史

- 2026-07-20 · 创建 · 基于《篮状细胞打出节拍》一文 (#88) · 初始置信度：中（机制理解尚在发展，多层病理并存）

## 来源文章

- [[2026-07-20-gamma-oscillations-ping-ing-mechanism]]

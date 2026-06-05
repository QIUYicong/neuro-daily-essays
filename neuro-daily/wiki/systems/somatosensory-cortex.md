---
title: 初级体感皮层（S1）
slug: somatosensory-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-07-19
updated: 2026-07-19
revision_count: 1
dimensions: [brain-region, microcircuit, cellular, whole-brain-network, cognition]
related: [thalamus, thalamocortical-circuit, mechanoreceptor, cortical-map-plasticity, motor-cortex, v1-primary-visual-cortex, auditory-cortex, olfactory-system, posterior-parietal-cortex]
prerequisites: [thalamus, thalamocortical-circuit, action-potential, synaptic-transmission]
opens_questions: [Q-s1-01, Q-s1-02, Q-s1-03]
source_articles: [2026-07-19-somatosensory-cortex-body-map]
key_sources: ["PMID:29519481", "PMID:23195880", "PMID:19038777", "PMID:34172735", "PMCID:PMC2674476", "PMCID:PMC8233353"]
---

# 初级体感皮层（S1）(Primary Somatosensory Cortex)

> **一句话定义**：位于中央后回（postcentral gyrus）的新皮层区域，包含四个功能亚区（3a/3b/1/2），接受来自丘脑VPL/VPM的触觉/本体感觉输入，以躯体拓扑（somatotopy）为组织原则，并以皮层放大倍率（cortical magnification factor）反映行为重要性而非解剖面积。

## 当前理解

我们现在认为，初级体感皮层（S1）是触觉、本体感觉和温度觉从皮肤到皮层的第一站皮层整合区，其核心特征是：

1. **拓扑保留**：从皮肤到VPL/VPM再到S1，空间毗邻关系被严格保留（躯体拓扑，somatotopy）。
2. **四亚区分工**：3a（本体感觉/深感觉）→ 3b（主要触觉门户）→ 1区（纹理/运动方向）→ 2区（形状/大小），构成串并联处理层级。
3. **失真地图（homunculus）**：皮层面积正比于感受器密度和行为重要性（手指尖 ≫ 躯干），反映突触竞争而非解剖比例。
4. **终生可塑**：成体地图随使用频率、受伤和训练动态重组；截肢后邻近区域占领失活领地；技能训练（盲文、弦乐）扩大高使用区域。
5. **可塑性的机制是回路增强而非重映射**：至少在啮齿动物卒中模型中，恢复来自已有回路的突触增强，而非功能性招募新神经元（Zeiger et al., 2021）。

S1的功能不止于感觉：它向M1发送内部模型预测（预期感觉），并通过后顶叶皮层参与感觉引导的运动（manipulation）和工具使用。

## 关键机制

### 外周到中枢的三段中继
1. 皮肤机械感受器（Meissner/Merkel/Ruffini/Pacinian，Aβ纤维）→ 脊髓**背柱**（薄束/楔束）→ 延髓薄/楔束核
2. 交叉为**内侧丘系**（medial lemniscus）上行至**丘脑VPL**（躯干/四肢）或**VPM**（面部/三叉）
3. VPL/VPM → 放射冠 → 内囊后肢 → S1（中央后回）

### S1四亚区
| 亚区 | Brodmann | 主要输入 | 主要功能 |
|------|----------|---------|---------|
| 3a | 3a | VPLc（肌梭Ia） | 本体感觉（肌张力/关节角度） |
| 3b | 3b | VPL主要 | 皮肤触觉（FA/SA），主地图门户 |
| 1区 | 1 | 3b | 纹理、皮肤运动方向 |
| 2区 | 2 | 1区+3b | 形状、大小，物体识别整合 |

### 皮层放大倍率（CMF）
指尖CMF：约为背部皮肤的100倍，直接对应感受器密度差异（FA-I密度：指尖~150/cm² vs 背部~5/cm²）

### 桶状皮层（S1 whisker region，大鼠/小鼠模型）
- 第IV层中每个"桶"（barrel）=一根特定胡须的皮层表征
- VPM桶小体（barreloid）→ S1桶柱（barrel column）：一对一拓扑
- 发育关键期（P4-P7）桶格局形成，依赖自发活动和感觉输入

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| S1分3a/3b/1/2四区，3b为主触觉门户 | 皮层电图+细胞构筑+电刺激，猕猴+人类 | PMID:29519481 | 高 |
| 桶柱是"一根胡须→一个功能列"的拓扑单元 | 细胞色素氧化酶染色+单单元记录 | PMID:23195880 | 高 |
| 成体桶状皮层可塑性通过LTP/LTD实现 | 胡须剥夺+皮层内记录，啮齿动物 | PMID:19038777（PMC2674476） | 高（多独立实验室） |
| 脑卒中后恢复是回路增强非功能重映射 | 双光子钙成像，小鼠光化学脑卒中模型 | PMID:34172735（PMC8233353） | 中（单实验室，需人类验证） |
| 截肢后S1手区被面区占领，与幻肢痛相关 | MEG脑磁图，截肢患者 | PMID:11403816 | 中-高（多研究，因果仍争议） |

## 连接

- [[thalamus]] — VPL（躯干四肢）和VPM（面部三叉）是S1的主要丘脑输入核团
- [[thalamocortical-circuit]] — S1是丘脑-皮层回路的核心靶区之一
- [[mechanoreceptor]] — 皮肤机械感受器是S1信息流的起点
- [[cortical-map-plasticity]] — S1地图可塑性是最早和最清楚被研究的皮层可塑性案例
- [[motor-cortex]] — M1与S1（3a/3b）高度互连，形成感觉-运动整合回路
- [[v1-primary-visual-cortex]] — 视觉系统的类似拓扑组织（retinotopy），与somatotopy互为参照
- [[auditory-cortex]] — 听觉系统的tonotopy，三套感觉地图（体感/视觉/听觉）共享"连续物理量→皮层空间维度"的组织原则
- [[pv-interneurons]] — PV+中间神经元在S1侧向抑制和关键期中发挥关键作用
- [[bdnf]] — BDNF是桶状皮层发育和成体可塑性的关键调节因子

## 未解问题

- Q-s1-01：S1面积改变（训练/截肢）的细胞学底物：是突触强度、树突棘数量还是轴突出芽？
- Q-s1-02：C触觉纤维（CT afferents）→岛叶路径与S1路径的中枢整合如何实现？
- Q-s1-03：Zeiger 2021"无功能重映射"发现在人类卒中后fMRI研究中是否得到验证？

## 修订历史

- 2026-07-19 · 创建 · 基于《皮肤之上的地图》文章（#87） · 初始置信度：高

## 来源文章

- [[2026-07-19-somatosensory-cortex-body-map]]

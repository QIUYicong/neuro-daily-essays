---
title: 前额叶皮层（PFC）
slug: prefrontal-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-06-05
updated: 2026-08-19
revision_count: 4
dimensions: [brain-region, cognition, microcircuit, behavior, whole-brain-network]
related: [working-memory, persistent-activity, gamma-oscillations, pv-interneurons, sst-interneurons, vip-interneurons, nmda-receptor, memory-consolidation, global-workspace-theory, consciousness-ignition, dorsal-attention-network, thalamus, executive-control, cognitive-flexibility, attractor-network]
prerequisites: [pyramidal-neuron, pv-interneurons, nmda-receptor]
opens_questions: [Q-wm-pfc-content-vs-control, Q-pfc-human-specificity, Q-dan-02, Q-dlpfc-hierarchy-mechanism]
source_articles: [2026-06-05-prefrontal-working-memory, 2026-07-01-dorsal-attention-network-FEF-IPS, 2026-08-19-dlpfc-executive-control-three-functions]
key_sources: ["PMID:7695894", "PMID:21345366", "PMID:41478518", "PMID:39381500", "PMID:13679398", "PMID:11994752", "PMID:34408280", "PMID:37919287", "PMID:26999822", "PMID:33790281"]
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

## 执行控制三功能分解（新增，2026-08-19）

DLPFC 实现执行控制的三个可分离组分，各有独立回路（Friedman & Robbins 2022，PMID:34408280）：

### 目标维持
- **神经子空间机制**：工作记忆内容编码在高维群体活动的低维稳定子空间（非主要依赖强直性持续放电；仅5–10%的PFC神经元表现出强直性放电，Langdon et al. 2023，PMID:37055616）
- **mPFC→背内侧纹状体（dmStr）通路**：维持期特异性激活，光遗传抑制仅在维持期降低成绩约9%（Wilhelm et al. 2023，PMID:37919287）

### 干扰抑制
- **白质通路是关键**：外囊/下额枕束（IFOF）损伤比 LIFG 皮层损伤更能预测干扰抑制障碍（Ries et al. 2021，PMID:33643192）
- **网络层面**：显著性网络（SN）→额顶网络（FPN）耦合介导，同时 SN 抑制 DMN（Menon & D'Esposito 2022，PMID:34408276）

### 规则切换
- **正交子空间门控**：不同规则的群体活动占据近正交神经子空间；SST 中间神经元树突抑制维持子空间隔离，沉默后崩溃（Liu & Wang 2023，PMID:37645801）
- **两步时序**：楔前叶网络（注意重定向，先激活）→ DLPFC 网络（规则重映射，约120ms后），颅内EEG验证（Mitsuhashi et al. 2022，PMID:35331870）

### LPFC 层级梯度（Nee & D'Esposito 2016，PMID:26999822）
- 尾侧 LPFC（BA44/45）：具体规则（特征层面）
- 中部 LPFC（BA46）：背景/元决策（**层级顶点**，整合上下行输入，预测认知能力）
- 额极（BA10）：时序抽象规划

### mPFC 的双向输出（de Kloet et al. 2021，PMID:33790281）
四条输出通路（大鼠）：dmPFC→MDL（丘脑，促进反应）、vmPFC→MDM（丘脑，抑制冲动）、dmPFC→DMS（纹状体，抑制冲动）、vmPFC→VMS（纹状体，效果微弱）——相对（促进 vs 抑制）的认知控制信号并行存在。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| dlPFC 延迟期放电是工作记忆的神经相关物 | 猕猴电生理 + 损毁实验 | Goldman-Rakic 1995 (PMID:7695894) | 高 |
| D1 受体倒 U 型调节 dlPFC 回路 | 猕猴微量注射 + 单单元记录 | Arnsten 2011 (PMID:21345366) | 高 |
| dlPFC L3d 在精神分裂症中选择性损伤 | 人类尸检 | Arnsten 2011; Hughes 2024 | 高 |
| PFC 中间神经元多样性支撑认知功能 | 灵长类 + 啮齿类综述 | Boroujeni et al. 2026 (PMID:41478518) | 高 |
| mPFC→dmStr通路在WM维持期特异性激活 | 光遗传+纤维光度（小鼠） | Wilhelm et al. 2023 (PMID:37919287) | 高（因果）|
| 白质通路（外囊/IFOF）比皮层更预测干扰抑制 | 单侧脑损伤患者n=55 | Ries et al. 2021 (PMID:33643192) | 中（相关）|
| SST沉默导致规则子空间崩溃 | 循环神经网络模型 | Liu & Wang 2023 (PMID:37645801) | 中（模型，需体内验证）|
| LPFC尾侧→中部→额极层级梯度 | fMRI + 动态因果建模 | Nee & D'Esposito 2016 (PMID:26999822) | 高 |

## 连接

- [[working-memory]] — dlPFC 是工作记忆的关键脑区
- [[persistent-activity]] — dlPFC 的延迟期放电是工作记忆持续活动的场所
- [[gamma-oscillations]] — dlPFC 中 γ 爆发是工作记忆的振荡载体
- [[pv-interneurons]] — dlPFC 中 PV 篮状细胞生成 γ，调控工作记忆时序
- [[memory-consolidation]] — PFC 是记忆巩固后远端记忆的皮层存储库
- [[global-workspace-theory]] — dlPFC 是全局工作空间神经元的核心解剖节点；参与意识点燃的广播
- [[consciousness-ignition]] — 意识点燃在 PFC 的神经基础：只有被感知刺激触发 dlPFC 持续放电（van Vugt et al. 2018）

## 未解问题

- Q-wm-pfc-content-vs-control：PFC 是工作记忆内容的存储器，还是对感觉皮层的调度中心？
- Q-pfc-human-specificity：人类 dlPFC 是否有超越猕猴的特异性工作记忆机制？

## 修订历史

- 2026-06-05 · 创建 · 基于《γ爆发、静默突触与持续放电》一文
- 2026-05-30 · 修订 · 基于《当意识在大脑中"点燃"》一文 · 新增 dlPFC 在全局工作空间点燃中的角色；添加 global-workspace-theory 和 consciousness-ignition 到 related；新增猕猴 van Vugt 2018 证据

- 2026-07-01 · 修订 · 基于《空间注意的神经回路》一文 · 新增 FEF（额叶眼区，BA8）作为 PFC 注意控制子区域；添加 dorsal-attention-network 和 thalamus 到 related；添加 Moore & Fallah 2004 和 Corbetta & Shulman 2002 到 key_sources；新增未解问题 Q-dan-02

## 来源文章

- [[2026-06-05-prefrontal-working-memory]]
- [[2026-07-01-dorsal-attention-network-FEF-IPS]]

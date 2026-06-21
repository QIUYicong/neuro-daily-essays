---
title: 前额叶皮层（PFC）
slug: prefrontal-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-06-05
updated: 2026-08-25
revision_count: 7
dimensions: [brain-region, cognition, microcircuit, behavior, disease]
related: [working-memory, persistent-activity, gamma-oscillations, pv-interneurons, sst-interneurons, vip-interneurons, nmda-receptor, memory-consolidation, global-workspace-theory, consciousness-ignition, dorsal-attention-network, thalamus, response-inhibition, hyperdirect-pathway, stop-signal-task, orbitofrontal-cortex, value-based-decision-making, dlpfc-cognitive-flexibility, mixed-selectivity, stability-flexibility-tradeoff, task-switching-cost, vmPFC, emotion-regulation, cognitive-reappraisal, amygdala, fear-extinction]
prerequisites: [pyramidal-neuron, pv-interneurons, nmda-receptor]
opens_questions: [Q-wm-pfc-content-vs-control, Q-pfc-human-specificity, Q-dan-02, Q-ri-03, Q-ofc-02, Q-dlpfc-01, Q-dlpfc-02, Q-dlpfc-03, Q-dlpfc-04, Q-vmPFC-01]
source_articles: [2026-06-05-prefrontal-working-memory, 2026-07-01-dorsal-attention-network-FEF-IPS, 2026-08-19-response-inhibition-hyperdirect-pathway, 2026-08-21-orbitofrontal-cortex-value-decision-circuit, 2026-08-24-dlpfc-cognitive-flexibility-rule-switching, 2026-08-25-vmPFC-sgACC-emotion-regulation]
key_sources: ["PMID:7695894", "PMID:21345366", "PMID:41478518", "PMID:39381500", "PMID:13679398", "PMID:11994752", "PMID:32155442", "PMID:16510720", "PMID:28103476", "PMID:19407204", "PMID:29144973", "PMID:11283309", "PMID:11209083", "PMID:23685452", "PMC4412347", "PMID:24201281", "PMC4121670", "PMID:23177967", "PMC3907768", "PMID:19672274", "PMID:38010299"]
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

### rIFG/preSMA 的反应抑制功能

右侧额下回（rIFG，BA44/45）是反应抑制的核心皮层驱动区，通过超直接通路（rIFG→STN 单突触投射，传导潜伏期 2.2 ms）在约 150 ms 内触发全局性运动抑制（Aron & Poldrack 2006，Chen et al. 2020）。辅助运动区前部（preSMA）是冲突检测的另一关键节点，主要驱动间接通路（preSMA→纹状体→GPe→STN→GPi）。

功能偏侧化：人类中反应抑制显著右侧化（右侧 IFG/STN 激活主导），与左侧语言优势互补。

### dlPFC 的认知弹性与规则切换

dlPFC 不仅"维持"工作记忆内容，更通过三重机制实现认知弹性（见 [[dlpfc-cognitive-flexibility]]）：

**混合选择性**（Rigotti et al. 2013，PMC4412347）：dlPFC 神经元对任务规则、刺激特征、时间位置的交叉项产生非线性响应，使神经表征高维化。高维表征支持任意任务规则的线性可读出，是认知弹性的编码基础。

**群体动力学**（Mante et al. 2013，PMC4121670）：不同任务背景下，dlPFC 群体动力学轨迹沿正交子空间展开——背景信号作为初始条件，把循环网络导入不同计算子空间。规则"选择"与感觉证据"整合"是同一回路中同一动力学过程的两个面，而非两个独立模块。

**振荡选通**（Buschman et al. 2012，PMC3907768）：规则切换时，beta 振荡（19–40 Hz）激活当前规则的神经集群，alpha 振荡（8–12 Hz）抑制无关集群，实现动态路由。

**BG 门控**（O'Reilly & Frank 2006，PMID:16378516）：基底节纹状体控制 dlPFC 工作记忆的更新时机，dACC 的错误/冲突信号触发 BG 开放更新门——将 dACC 监测功能与 dlPFC 弹性切换机制直接连接。

**前额叶前后轴层级**（Badre & D'Esposito 2009，PMID:19672274）：前侧 PFC（额极 BA10）表征"规则的规则"（高阶任务集），dlPFC（BA46 中段）表征特征类别规则，后 PFC（BA6）表征具体感觉—运动映射，形成抽象度递增的认知控制层级。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| dlPFC 延迟期放电是工作记忆的神经相关物 | 猕猴电生理 + 损毁实验 | Goldman-Rakic 1995 (PMID:7695894) | 高 |
| D1 受体倒 U 型调节 dlPFC 回路 | 猕猴微量注射 + 单单元记录 | Arnsten 2011 (PMID:21345366, PMC:PMC3115784) | 高 |
| dlPFC L3d 在精神分裂症中选择性损伤 | 人类尸检 | Arnsten 2011; Hughes 2024 | 高 |
| PFC 中间神经元多样性支撑认知功能 | 灵长类 + 啮齿类综述 | Boroujeni et al. 2026 (PMID:41478518, PMC:PMC12924665) | 高 |
| 右侧 IFG（BA44/45）在停止试次中激活，激活程度与 SSRT 负相关（r=0.68） | fMRI + 停止信号任务 | Aron & Poldrack 2006 (PMID:16510720, PMC:PMC5125216) | 高 |
| rIFG-STN 振荡同步强度与 SSRT 负相关（r=0.65）；单突触 2.2 ms 传导潜伏期 | PD 患者颅内 ECoG + STN DBS | Chen et al. 2020 (PMID:32155442, PMC:PMC7274135) | 高 |

## 连接

- [[working-memory]] — dlPFC 是工作记忆的关键脑区
- [[persistent-activity]] — dlPFC 的延迟期放电是工作记忆持续活动的场所
- [[gamma-oscillations]] — dlPFC 中 γ 爆发是工作记忆的振荡载体
- [[pv-interneurons]] — dlPFC 中 PV 篮状细胞生成 γ，调控工作记忆时序
- [[memory-consolidation]] — PFC 是记忆巩固后远端记忆的皮层存储库
- [[global-workspace-theory]] — dlPFC 是全局工作空间神经元的核心解剖节点；参与意识点燃的广播
- [[consciousness-ignition]] — 意识点燃在 PFC 的神经基础：只有被感知刺激触发 dlPFC 持续放电（van Vugt et al. 2018）
- [[response-inhibition]] — rIFG/preSMA 是反应抑制的关键皮层节点；rIFG 经超直接通路触发紧急制动
- [[hyperdirect-pathway]] — rIFG→STN 超直接通路的皮层起点；rIFG 单突触激活 STN（2.2 ms）
- [[stop-signal-task]] — rIFG/STN 激活强度预测 SSRT（Aron & Poldrack 2006，r=0.68）
- [[orbitofrontal-cortex]] — vmPFC/OFC 是 PFC 中负责价值整合和目标导向决策的腹侧亚区；dlPFC 在自控时调制 vmPFC 价值信号（Hare et al. 2009）
- [[value-based-decision-making]] — dlPFC 通过调制 vmPFC 的价值整合实现自控；前边缘皮层（PL）接受并反馈 mOFC 信号
- [[vmPFC]] — vmPFC（BA10/11/12/25/32 腹侧）是 PFC 中情绪调节的核心亚区；通过 vlPFC→vmPFC→杏仁核三层级回路实现认知重评，通过 IL/vmPFC→ITC→CeM 回路执行恐惧消退；详见 [[vmPFC]] 页面
- [[emotion-regulation]] — vmPFC 是情绪调节的前额叶枢纽；认知重评、恐惧消退均依赖 vmPFC→杏仁核的负向有效连接
- [[cognitive-reappraisal]] — 认知重评的三层级回路以 vmPFC 为中间整合节点（vlPFC 语义重构 → vmPFC 情绪估价 → 杏仁核抑制）
- [[amygdala]] — vmPFC/IL 通过腹侧 ITC 抑制杏仁核 CeM 输出，是情绪调节的主要皮层-皮层下轴
- [[fear-extinction]] — IL（啮齿类 vmPFC 同源）是恐惧消退记忆提取的关键皮层节点

### vmPFC — 情绪调节的 PFC 腹侧亚区

vmPFC（腹内侧前额叶皮层，BA10/11/12/25/32 腹侧）是 PFC 的情绪调节专用亚区，与 dlPFC（认知控制/工作记忆）功能互补，共享前额叶皮层的整体调控框架：

- **认知重评**：vlPFC（语义重构）→ vmPFC（情绪价值整合）→ 杏仁核 BLA（负向有效连接抑制）；TMS-fMRI 因果证明（He et al. 2023, PMID:37507228）
- **恐惧消退**：IL（大鼠 vmPFC 同源体）→ 腹侧 ITC（ICMMV）→ CeM 抑制；同时 IL → BLA 消退神经元激活安全信号
- **sgACC（BA25）轴**：下行至 LC/DRN/PAG/下丘脑，将皮层情绪估价转化为自主神经和神经调质变化；抑郁症中持续过度激活形成恶性循环
- **抑郁中的回路崩溃**：vmPFC 灰质减少 + sgACC 超激活 → 情绪调节失败；BA25 白质纤维 DBS 治疗难治性抑郁（Mayberg 2005）

见 [[vmPFC]]（专用页面）获取完整机制和证据表。

## 未解问题

- Q-wm-pfc-content-vs-control：PFC 是工作记忆内容的存储器，还是对感觉皮层的调度中心？
- Q-pfc-human-specificity：人类 dlPFC 是否有超越猕猴的特异性工作记忆机制？
- Q-ri-03：主动性抑制的前额叶-STN 机制是否与反应性抑制相同？
- Q-dlpfc-01：dlPFC 工作记忆的主要维持机制——持续激活还是活动-沉默状态？
- Q-dlpfc-02：dACC→BG→dlPFC 规则更新信号链的精确时间分辨率是多少？
- Q-dlpfc-03：人类 dlPFC 的混合选择性程度是否超越猕猴？
- Q-dlpfc-04：规则切换时旧规则被主动抑制还是竞争压制？
- Q-vmPFC-01（高优先级）：vmPFC 在认知重评中为何在元分析中未呈现稳定激活——是策略依赖、时间分辨率问题，还是个体差异稀释？

## 修订历史

- 2026-06-05 · 创建 · 基于《γ爆发、静默突触与持续放电》一文
- 2026-05-30 · 修订 · 基于《当意识在大脑中"点燃"》一文 · 新增 dlPFC 在全局工作空间点燃中的角色；添加 global-workspace-theory 和 consciousness-ignition 到 related；新增猕猴 van Vugt 2018 证据

- 2026-07-01 · 修订 · 基于《空间注意的神经回路》一文 · 新增 FEF（额叶眼区，BA8）作为 PFC 注意控制子区域；添加 dorsal-attention-network 和 thalamus 到 related；添加 Moore & Fallah 2004 和 Corbetta & Shulman 2002 到 key_sources；新增未解问题 Q-dan-02
- 2026-08-19 · 修订 · 基于《大脑的刹车系统》一文 · 新增 rIFG/preSMA 在反应抑制（超直接通路）中的因果作用证据；添加 response-inhibition、hyperdirect-pathway、stop-signal-task 到 related；新增 Aron & Poldrack 2006 和 Chen et al. 2020 证据；新增未解问题 Q-ri-03
- 2026-08-21 · 修订 · 基于《价值的解剖：眶额皮层如何为选项定价》一文 · 新增 vmPFC/OFC 作为 PFC 的价值决策腹侧亚区（dlPFC→vmPFC 自控调制，Hare et al. 2009）；添加 orbitofrontal-cortex、value-based-decision-making 到 related；新增未解问题 Q-ofc-02
- 2026-08-24 · 修订 · 基于《背外侧前额叶的认知弹性》文章 · 新增 dlPFC 认知弹性三重机制（混合选择性/群体动力学/振荡选通）与前额叶层级（Badre 2009）；添加 dlpfc-cognitive-flexibility、mixed-selectivity、stability-flexibility-tradeoff、task-switching-cost 到 related；新增未解问题 Q-dlpfc-01~04；新增关键来源 Mante 2013/Buschman 2012/Rigotti 2013/Sali 2024
- 2026-08-25 · 修订 · 基于《驯化杏仁核：vmPFC 与 sgACC》(#123) · 新增 vmPFC 作为 PFC 情绪调节腹侧亚区（认知重评三层级回路 + 恐惧消退 IL 同源 + sgACC 自主神经轴 + 抑郁回路崩溃）；添加 vmPFC、emotion-regulation、cognitive-reappraisal、amygdala、fear-extinction 到 related；新增未解问题 Q-vmPFC-01；添加 dimensions: disease

## 来源文章

- [[2026-06-05-prefrontal-working-memory]]
- [[2026-07-01-dorsal-attention-network-FEF-IPS]]
- [[2026-08-19-response-inhibition-hyperdirect-pathway]]
- [[2026-08-21-orbitofrontal-cortex-value-decision-circuit]]
- [[2026-08-24-dlpfc-cognitive-flexibility-rule-switching]]
- [[2026-08-25-vmPFC-sgACC-emotion-regulation]]

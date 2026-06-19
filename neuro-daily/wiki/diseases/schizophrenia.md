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
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, whole-brain-network, cognition, disease]
related: [pv-interneurons, gamma-oscillations, working-memory, prefrontal-cortex, ei-balance, nmda-receptor, dopamine-reward-prediction-error, glutamate-hypothesis]
prerequisites: [pv-interneurons, gamma-oscillations, working-memory, prefrontal-cortex, ei-balance]
opens_questions: [Q-pv-schizophrenia-causal, Q-pv-gamma-necessary]
source_articles: [2026-07-20-gamma-oscillations-ping-ing-schizophrenia]
key_sources: ["PMID:15803162", "PMID:18586694", "PMID:39381500", "PMID:25863358", "PMID:22219337", "PMID:20080054"]
---

# 精神分裂症 (Schizophrenia)

> **一句话定义**：一种以幻觉/妄想（正性症状）、情感淡漠（负性症状）和工作记忆/注意力缺陷（认知症状）为核心表现的神经发育性精神疾病，当前理解其认知症状主要源自前额叶PV+中间神经元的GABA合成酶（GAD67）下调→γ振荡受损→信息同步处理失效。

## 当前理解

我们现在认为，精神分裂症是一种**神经发育失调**（不仅是成人期的神经退化），其核心病理节点之一是前额叶皮层（特别是dlPFC）的**PV+快速放电中间神经元的功能损伤**。

**PV+/GAD67/γ级联假说**（Lewis et al. 2005，PMID:15803162；Gonzalez-Burgos & Lewis 2008，PMID:18586694；Hughes et al. 2024，PMID:39381500）：

1. BDNF/TrkB信号通路减弱（可能是环境应激、基因变异或发育失调的结果）
2. TrkB信号不足 → dlPFC PV+细胞中GAD67（谷氨酸脱羧酶67，GABA合成关键酶）mRNA下调 → 每个PV+细胞释放的GABA减少
3. GABA释放减少 → PV+篮状细胞对锥体细胞的围胞体抑制减弱 → PING回路中E-I循环的精度下降
4. PING回路受损 → 任务诱发的dlPFC γ振荡功率无法正常升高 → 皮层同步处理窗口消失
5. γ同步丢失 → 工作记忆编码和读取效率降低 → 临床上表现为工作记忆缺陷（注意、规划、认知控制全面受损）

这条因果链从分子（GAD67）到细胞（PV+突触传递）到回路（PING/γ）到系统（dlPFC同步）到行为（工作记忆），是目前精神科神经生物学中**因果链最完整的路径之一**。

**重要不确定性**（见Q-pv-schizophrenia-causal）：PV+细胞GAD67下调是原发致病因素（基因-发育失调直接驱动）、继发性代偿失败（对更上游缺陷的补偿尝试失败），还是神经炎症或氧化应激导致的二次损伤？目前三种解释均有部分支持，因果方向尚未明确。

**NMDA受体低功能假说的补充**：精神分裂症的另一重要假说是谷氨酸能NMDA受体低功能（可卡因/苯环己哌啶复制阳性症状）。NMDA低功能与PV+细胞损伤存在联系：PV+细胞对NMDA受体功能依赖较高，NMDA功能减弱可优先损伤PV+细胞的驱动（尽管这两个假说并非同义词）。

**发育时间线**（Uhlhaas & Singer 2010，PMID:20080054）：γ振荡同步性在青春期晚期（17-25岁）才完全成熟，恰好对应精神分裂症首次发病的高发期。PV+细胞的GABAergic成熟在此期间仍在进行，若发育轨迹被打乱（遗传×环境交互），可能在这个脆弱窗口期引发症状涌现。

## 关键机制

### 分子层面
- PV+细胞的GAD67 mRNA下调：多项死后研究（尸检）一致（Hughes et al. 2024）
- 蛋白层面：GAD67蛋白在PV+轴突终末中减少（免疫组化）
- BDNF/TrkB信号减弱是可能的上游驱动
- NMDA受体低功能的独立贡献尚待厘清

### 细胞层面
- PV+篮状细胞的围胞体抑制特异性减弱（非其他中间神经元类型）
- GAD67减少不影响PV+细胞数量（细胞不死亡，功能受损）
- 细胞类型特异性：SST+和VIP+中间神经元影响相对较小

### 回路层面
- PING回路E-I循环精度下降 → γ振荡功率降低
- dlPFC中γ振荡任务诱发升高能力受损（而静息γ可能相对保留）
- 部分代偿性突触重塑存在但不足以维持认知负荷时的γ同步

### 全脑网络层面
- 默认模式网络（DMN）脱抑制（正常认知任务时DMN应压制，SZ中DMN可能过度活跃）
- 前额叶-颞叶同步受损（幻听可能与此相关）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| dlPFC PV+细胞 GAD67 mRNA 下调（SZ死后） | 尸检组织 + 原位杂交/qPCR，多中心复制 | Lewis et al. 2005 (PMID:15803162)；Hughes et al. 2024 (PMID:39381500) | 高 |
| 精神分裂症患者工作记忆任务 dlPFC γ 功率无法升高 | MEG/EEG，多项研究 | PMID:25863358 | 高 |
| PV+细胞抑制 → γ 消失（光遗传学因果，非人灵长类/啮齿类） | 光遗传学，清醒行为动物 | Sohal et al. 2009 (PMID:19396159) | 高 |
| 精神分裂症中 PV 特异（非 SST/VIP）的细胞型改变 | 尸检多重免疫标记 | PMID:22219337 | 高（一致性强） |
| SZ 首发患者听觉稳态反应 γ 减弱（40 Hz ASSR 降低） | MEG，首发未治患者 | 多项研究综合 | 高（重复最多的 SZ 生物标志物） |

## 连接

- [[pv-interneurons]] — PV+细胞GAD67↓是SZ认知症状的核心分子-细胞机制
- [[gamma-oscillations]] — dlPFC γ振荡是SZ认知损伤的近端振荡指标
- [[working-memory]] — dlPFC工作记忆是SZ认知症状中损伤最一致的领域
- [[prefrontal-cortex]] — dlPFC是SZ认知病理的主要解剖焦点
- [[ei-balance]] — PV+损伤导致E/I平衡偏向兴奋方向，这是更广泛的SZ神经病理背景
- [[nmda-receptor]] — NMDA低功能假说与PV+损伤假说存在交叉和互补（NMDA可能优先损伤PV+）
- [[dopamine-reward-prediction-error]] — DA系统异常（特别是中脑边缘通路DA过多）驱动SZ正性症状（幻觉/妄想）；认知症状更依赖PFC DA和GABA

## 未解问题

- Q-pv-schizophrenia-causal：PV+细胞GAD67下调是SZ的原发失调、环境应激的结果，还是继发性神经炎症损伤？（核心未解，影响所有治疗靶点的逻辑）
- Q-pv-gamma-necessary：即使复原PV+的GABA合成，γ同步能否恢复到足以改善工作记忆的水平？（临床干预的可行性）

## 修订历史

- 2026-07-20 · 创建 · 基于《γ振荡的引擎：PV+篮状细胞如何铸造40赫兹节律》(#88) · 整合Lewis 2005, Gonzalez-Burgos 2008, Hughes 2024等关键文献；初始置信度：中（核心分子-回路链可信，但因果方向有争议）

## 来源文章

- [[2026-07-20-gamma-oscillations-ping-ing-schizophrenia]]

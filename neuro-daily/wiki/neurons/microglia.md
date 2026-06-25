---
title: 小胶质细胞
slug: microglia
domain: neurons
type: entity
status: established
confidence: high
created: 2026-06-03
updated: 2026-09-17
revision_count: 2
dimensions: [cellular, molecular, microcircuit, brain-region, disease]
related: [synaptic-pruning, complement-cascade-cns, tripartite-synapse, astrocyte, trem2, neuroinflammation, disease-associated-microglia, alzheimers-disease, als-amyotrophic-lateral-sclerosis]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: [Q-microglia-01, Q-microglia-02, Q-dam-01, Q-dam-02, Q-neuroinflamm-01]
source_articles: [2026-06-03-microglia-synaptic-pruning, 2026-09-17-neuroinflammation-microglia-dam-trem2]
key_sources: ["PMID:22632727", "PMID:18083105", "PMID:34738335", "PMID:24316888", "PMID:28602351", "PMID:28930663", "PMCID:PMC5719893", "PMID:23150934", "PMID:31042697"]
---

# 小胶质细胞 (Microglia)

> **一句话定义**：小胶质细胞是中枢神经系统的卵黄囊来源常驻免疫细胞，占脑细胞10-15%；在发育期通过补体/PS-TREM2信号执行突触剪枝；在成年期以稳态（P2RY12+/TMEM119+）状态持续巡逻；在神经退行性疾病中通过两步转化为DAM（疾病相关微胶质细胞），兼具保护性清除功能和潜在的神经毒性驱动风险。

## 当前理解

我们现在认为，小胶质细胞远不只是大脑的"免疫卫士"。在神经回路的建立过程中，它们担当一个更主动的角色：**突触剪枝的执行者**。发育期大脑产生远多于最终需要量的突触连接，小胶质细胞通过识别被补体（C3b）标记或暴露磷脂酰丝氨酸的突触末梢，并将其物理吞噬至溶酶体中降解。这一过程对活动水平敏感——活跃突触上的"别吃我"信号（CD47）丰度更高，从而受到保护；沉默突触则更容易被标记和删除。

在疾病中，小胶质细胞的剪枝功能可以朝两个方向失调：过度剪枝（如精神分裂症中 C4A 过度表达所触发的青春期前额叶过度剪枝）和不足剪枝（如 TREM2 缺失导致海马突触密度异常升高），以及病理性重激活（如阿尔茨海默病中 Aβ 低聚体触发 C1q 重新大量沉积在成年突触上）。

## 关键机制

### 发育期突触剪枝

**补体-CR3 通路**：
1. 发育期神经元（受星形胶质细胞 TGF-β 信号上调）合成并分泌 C1q
2. C1q 结合突触膜上的配体，激活 C4 → C3 转化酶
3. C3 转化酶将 C3 裂解为 C3b（调理素，共价结合到突触膜）
4. 小胶质细胞表面的 CR3（CD11b/CD18）识别 C3b-标记突触
5. CR3 激活 → 吞噬体形成 → 突触末梢被整体内化并降解

**PS-TREM2 通路**（并行）：
1. 弱突触的突触前膜 scramblase 激活 → PS 从内层翻转到外层
2. 小胶质细胞 TREM2 识别暴露的 PS → 触发吞噬
3. PS 暴露与 C1q 沉积在同批突触上共定位，两条通路协同

**活动依赖机制**：
- 活跃突触：CD47 丰度高 → 与 SIRPα 结合 → 抑制吞噬（"别吃我"信号占优）
- 沉默突触：CD47 低 + C3b 标记 + PS 暴露 → 多重"吃我"信号叠加 → 优先被删除
- 直接证据：TTX 封闭单眼 → 该眼突触优先被微胶质吞噬；forskolin 增强活动 → 突触受保护（Schafer et al. 2012）

### 成年期功能

- 持续巡逻（以伪足探查）：以 30 分钟为周期覆盖整个大脑
- 低水平突触维护（可能参与记忆相关的突触精调）
- 病原体和凋亡神经元的清除
- 神经炎症信号的传导与调控

### 稳态分子身份（Butovsky 2014）

健康成年小胶质细胞的转录组特征由一套"稳态签名基因"维持，主要包括：
- **P2RY12**：嘌呤受体，感知局部ATP/ADP，引导伪足向损伤灶定向延伸
- **TMEM119**：跨膜蛋白，区分真正CNS内小胶质细胞与血液来源巨噬细胞的可靠标志
- **CX3CR1**：分型趋化因子受体，配体CX3CL1（神经元分泌）维持"请保持安静"信号
- 以上基因在炎症激活时统一下调，是小胶质细胞激活状态的早期分子标志

稳态基因程序的维持依赖**TGF-β信号**（神经元和星形胶质细胞持续分泌），TGF-β减少是小胶质细胞激活的先决条件之一。

### 神经退行性疾病中的DAM转化

在神经退行性疾病（AD、ALS）中，小胶质细胞通过两步激活成为**DAM（疾病相关微胶质细胞）**：
- **Step 1（TREM2非依赖）**：稳态基因下调（P2RY12↓、CX3CR1↓）；TREM2↑、APOE↑
- **Step 2（TREM2依赖）**：完整DAM激活——LPL↑、CTSD↑（脂质代谢/溶酶体）；具备吞噬Aβ能力

DAM在AD斑块周围形成物理屏障（5XFAD模型中有记录），可能具有保护性；但持续的TREM2→APOE→稳态基因丢失（MGnD状态）可能转变为神经毒性。保护vs破坏的翻转点与疾病阶段相关，仍是核心未解问题。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 微胶质细胞物理吞噬完整突触末梢 | 电子显微镜：溶酶体内发现完整突触结构 | PMID:22632727 | 高 |
| CR3/C3 通路是主要剪枝机制之一 | CR3 敲除减少 50% 吞噬容量；C3 KO 视网膜膝状核分离失败 | PMID:22632727, 18083105 | 高 |
| TTX 封闭 → 优先吞噬沉默眼突触 | 单眼 TTX 注射 + 荧光示踪 + 共聚焦 | PMID:22632727 | 高 |
| TREM2 识别 PS 是并行剪枝通路 | TREM2 KO → 海马突触密度升高；Annexin V 屏蔽 PS → 剪枝减少 | PMID:32657463 | 中高 |
| AD 中 C1q 在突触上病理性重激活 | AD 小鼠 1 月龄 C1q↑（早于斑块）；抗 C1q → 突触保护 | PMID:27033548 | 高 |
| 精神分裂症中 C4A↑ → 过度剪枝 | 遗传关联（N=64,000+）；C4 敲入小鼠树突棘减少 | PMID:26814963 | 高 |
| 稳态签名基因（P2RY12/TMEM119/CX3CR1）炎症下调 | RNA-seq + 流式细胞术；CX3CR1-GFP小鼠活体确认 | PMID:24316888/PMC4066672 | 高 |
| DAM两步激活；Step 2 TREM2依赖 | scRNA-seq 5XFAD；TREM2-KO比较 | PMID:28602351 | 高（小鼠）/中（人类） |
| TREM2 R47H→AD风险↑3-5×（功能损失→剪枝/清除效率↓） | 外显子测序；冰岛队列 | PMID:23150934; 23150908 | 高 |

## 连接

- [[synaptic-pruning]] — 小胶质细胞是突触剪枝的主要执行细胞
- [[complement-cascade-cns]] — 提供"吃我"分子标记（C3b）
- [[tripartite-synapse]] — 星形胶质细胞通过 TGF-β 上调神经元 C1q 表达
- [[astrocyte]] — 星形胶质细胞也有自己的突触吞噬通路（MEGF10/MERTK），独立于微胶质
- [[trem2]] — 磷脂酰丝氨酸识别受体，AD风险基因，DAM Step 2激活的分子开关
- [[neuroinflammation]] — 小胶质细胞是神经炎症的核心效应细胞
- [[disease-associated-microglia]] — DAM是小胶质细胞在神经退行性疾病中的激活态
- [[alzheimers-disease]] — C1q重激活+DAM转化是AD病理微环境的双重免疫机制
- [[als-amyotrophic-lateral-sclerosis]] — ALS中DAM样签名在SOD1模型和ALS患者脊髓中被记录
- [[pv-interneurons]] — 精神分裂症中PV+细胞与C4A过度剪枝有关联（待深入）

## 未解问题

- Q-microglia-01（高优先）：弱突触如何精确获得 C1q 标记？PS 外翻的上游触发器是否是 LTD 相关的 caspase-3 激活？
- Q-microglia-02（中优先）：成年大脑中小胶质细胞是否持续参与突触的动态维护？其与记忆固结（SWR 期间）的关系？

## 修订历史

- 2026-06-03 · 创建 · 基于《大脑的"质检员"》(#70) · 初始置信度：高
- 2026-09-17 · 修订(rev2) · 基于《大脑内守军的两张面孔》(#147) · 补充稳态分子身份（P2RY12/TMEM119）、DAM两步激活机制、TREM2-APOE轴，更新一句话定义以反映DAM功能；新增DAM相关条目至关键证据表；补充连接到neuroinflammation、disease-associated-microglia、als

## 来源文章

- [[2026-06-03-microglia-synaptic-pruning]]
- [[2026-09-17-neuroinflammation-microglia-dam-trem2]]

---
title: 小胶质细胞
slug: microglia
domain: neurons
type: entity
status: established
confidence: high
created: 2026-06-03
updated: 2026-06-03
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, disease]
related: [synaptic-pruning, complement-cascade-cns, tripartite-synapse, astrocyte, trem2]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: [Q-microglia-01, Q-microglia-02]
source_articles: [2026-06-03-microglia-synaptic-pruning]
key_sources: ["PMID:22632727", "PMID:18083105", "PMID:34738335"]
---

# 小胶质细胞 (Microglia)

> **一句话定义**：小胶质细胞是中枢神经系统的常驻免疫细胞，占胶质细胞的 10%–15%，在发育期通过识别补体标记（CR3/CD11b）和磷脂酰丝氨酸信号（TREM2）物理吞噬弱突触，雕刻神经回路；在成年期持续巡逻大脑，参与炎症调节、突触维护和神经元死亡的清除。

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

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 微胶质细胞物理吞噬完整突触末梢 | 电子显微镜：溶酶体内发现完整突触结构 | PMID:22632727 | 高 |
| CR3/C3 通路是主要剪枝机制之一 | CR3 敲除减少 50% 吞噬容量；C3 KO 视网膜膝状核分离失败 | PMID:22632727, 18083105 | 高 |
| TTX 封闭 → 优先吞噬沉默眼突触 | 单眼 TTX 注射 + 荧光示踪 + 共聚焦 | PMID:22632727 | 高 |
| TREM2 识别 PS 是并行剪枝通路 | TREM2 KO → 海马突触密度升高；Annexin V 屏蔽 PS → 剪枝减少 | PMID:32657463 | 中高 |
| AD 中 C1q 在突触上病理性重激活 | AD 小鼠 1 月龄 C1q↑（早于斑块）；抗 C1q → 突触保护 | PMID:27033548 | 高 |
| 精神分裂症中 C4A↑ → 过度剪枝 | 遗传关联（N=64,000+）；C4 敲入小鼠树突棘减少 | PMID:26814963 | 高 |

## 连接

- [[synaptic-pruning]] — 小胶质细胞是突触剪枝的主要执行细胞
- [[complement-cascade-cns]] — 提供"吃我"分子标记（C3b）
- [[tripartite-synapse]] — 星形胶质细胞通过 TGF-β 上调神经元 C1q 表达
- [[astrocyte]] — 星形胶质细胞也有自己的突触吞噬通路（MEGF10/MERTK），独立于微胶质
- [[trem2]] — 磷脂酰丝氨酸识别受体，AD 风险基因
- [[alzheimers-disease]] — C1q 重激活导致早期突触丢失
- [[pv-interneurons]] — 精神分裂症中 PV+ 细胞与 C4A 过度剪枝有关联（待深入）

## 未解问题

- Q-microglia-01（高优先）：弱突触如何精确获得 C1q 标记？PS 外翻的上游触发器是否是 LTD 相关的 caspase-3 激活？
- Q-microglia-02（中优先）：成年大脑中小胶质细胞是否持续参与突触的动态维护？其与记忆固结（SWR 期间）的关系？

## 修订历史

- 2026-06-03 · 创建 · 基于《大脑的"质检员"》(#70) · 初始置信度：高

## 来源文章

- [[2026-06-03-microglia-synaptic-pruning]]

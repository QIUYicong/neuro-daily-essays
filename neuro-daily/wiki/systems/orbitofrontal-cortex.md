---
title: 眶额皮层（OFC）
slug: orbitofrontal-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-08-21
updated: 2026-08-22
revision_count: 2
dimensions: [brain-region, cognition, microcircuit, behavior]
related: [prefrontal-cortex, amygdala, basal-ganglia, nucleus-accumbens, value-based-decision-making, dopamine-reward-prediction-error, anterior-cingulate-cortex, vmPFC, insular-cortex, interoception]
prerequisites: [prefrontal-cortex, amygdala, synaptic-transmission, ltp]
opens_questions: [Q-ofc-01, Q-ofc-02, Q-ofc-03]
source_articles: [2026-08-21-orbitofrontal-cortex-value-decision-circuit]
key_sources: ["PMID:16633341", "PMID:29144973", "PMID:37592039", "PMID:32884146", "PMID:40068869", "DOI:10.7554/eLife.80926", "PMID:27112314", "PMID:39331504", "PMID:39547861", "PMID:19407204"]
---

# 眶额皮层（Orbitofrontal Cortex, OFC）

> **一句话定义**：位于额叶最腹侧、与眼眶骨板相邻的新皮层区域，是大脑主观价值编码、灵活行为适应和目标导向决策的核心枢纽；通过三类功能专化的神经元群体将候选选项的效用转化为可读出的选择信号，并通过与 BLA、vmPFC 和纹状体的回路连接将价值记忆整合为可执行的行为。

## 当前理解

我们现在认为，眶额皮层（OFC）是大脑"主观价值地图"的存储和实时更新引擎。它的核心功能不是感知奖赏本身（那是多巴胺奖赏系统和 NAc 的工作），而是在感觉信息到达之后、动作指令发出之前，计算和比较不同选项的**当前主观效用**。

Padoa-Schioppa & Assad 2006 年的经典实验（PMID:16633341）首次在单神经元水平证明：OFC 神经元的放电率与选项价值单调相关，且独立于提示的空间位置和随后的眼动方向。这意味着 OFC 维护的是一个真正的"价值坐标系"，而非感觉或运动表征。

OFC 内部由三类功能细胞群体构成（Padoa-Schioppa & Conen 2017, PMID:29144973）：
- **提案价值细胞（offer value cells）**：选项呈现时激活，分别编码各候选选项的效用
- **选定价值细胞（chosen value cells）**：选择完成后激活，编码胜出选项的效用
- **效用感知细胞（taste / good value cells）**：奖赏消费时激活，提供实际体验信号

这三类细胞在时间上串行激活，构成从比较到选择到消费的决策流水线。

OFC 不是单一功能区：**内侧 OFC（mOFC）**主要处理当前奖赏偏好和价值比较；**外侧 OFC（lOFC）**处理惩罚、逆向学习和结果-预期偏差。两者通过与 BLA 的双向连接协作：lOFC→BLA 写入结果特异性奖赏记忆，mOFC→BLA 在决策时检索这些记忆（Wassum 2022, DOI:10.7554/eLife.80926）。

OFC 的价值代码在个体成年期具有**纵向稳定性**（Zhang & Padoa-Schioppa 2024, PMID:39331504），仅有轻微表征漂移，支持"价值地图是长期内部标准"的观点。

新近框架（Moneta et al. 2024, PMID:39547861）指出，OFC 不只编码即时价值，还编码**任务状态**（混合选择性），使其作为内部世界模型的一部分支持基于模型的规划。

## 关键机制

**1. 分子/突触层**
OFC 锥体细胞通过 AMPA/NMDA 受体接受来自 BLA（奖赏预期/更新信号）、岛叶（内感受价值）、前额叶（认知目标）和感觉皮层（刺激特征）的汇聚输入。其突触可塑性（LTP/LTD 机制）是价值学习的分子基础。

**2. 回路层**
- **OFC-BLA 双向回路**（核心）：
  - lOFC→BLA：学习阶段写入"提示-结果-状态"特异性奖赏记忆
  - mOFC→BLA：决策时提取历史记忆，生成当前价值估计
  - BLA→lOFC：更新提示的预测权变关系
  - BLA→mOFC：根据当前状态调整奖赏期望
- **OFC→DMS 通路**：腹外侧 OFC 投射至背内侧纹状体（DMS），将价值信号转化为目标导向行动选择（Gore et al. 2023, PMID:37592039，光遗传学因果证明）
- **OFC-vmPFC-dlPFC 轴**：vmPFC 整合来自 OFC 的价值信号；dlPFC 在自控情境下调制 vmPFC 的价值权重（Hare et al. 2009, PMID:19407204）
- **lOFC→感觉皮层**：逆向学习时，lOFC 发出自上而下反馈，重塑感觉皮层的刺激表征（Banerjee et al. 2020, PMID:32884146）

**3. mOFC 的并行分支**（Jenni et al. 2025, PMID:40068869）
- mOFC→BLA：追踪相对价值变化，支持灵活切换
- mOFC→PL（前边缘皮层）：情境化处理结果（在赢/输历史下解读单次结果）
- PL→mOFC：抑制对高风险大奖的冲动性偏向

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| OFC 神经元以独立于感觉/运动的方式编码选项价值 | 猴子经济决策任务 + 单细胞记录，系统改变位置和动作方向 | PMID:16633341 | 高 |
| OFC 内存在三类功能神经元（offer/chosen/taste value） | 猴子电生理，多年数据整合 + 计算模型 | PMID:29144973 | 高 |
| OFC→DMS 投射对经济决策因果必要 | 大鼠，光遗传学特异沉默 ORBvl→DMS 投射 | PMID:37592039 | 高 |
| lOFC 损伤破坏逆向学习；lOFC→感觉皮层驱动重映射 | 小鼠，DREADD 沉默 + 电生理 | PMID:32884146 | 中-高 |
| mOFC→BLA/PL 的分离功能（价值追踪 vs 情境化） | 大鼠，DREADD 精确通路拆解 | PMID:40068869 | 中（单项研究） |
| BLA-OFC 四条通路功能专化（综述） | 系统综述多项研究 | DOI:10.7554/eLife.80926 | 中-高 |
| OFC 价值代码纵向稳定 | 小鼠，双光子钙成像，多周追踪 | PMID:39331504 | 中（小鼠） |
| dlPFC 调制 vmPFC 价值信号实现自控 | 人类 fMRI，食物选择任务 | PMID:19407204 | 中（fMRI相关性） |
| OFC/vmPFC 编码任务状态（混合选择性） | 综述 + 计算建模 | PMID:39547861 | 中（新兴框架） |

## 解剖功能分区

| 亚区 | 主要连接 | 核心功能 |
|------|---------|---------|
| 内侧 OFC（mOFC） | NAc、mPFC、BLA 内侧 | 当前奖赏偏好、价值比较、情境化奖赏检索 |
| 外侧 OFC（lOFC） | BLA 外侧、岛叶、感觉皮层 | 惩罚处理、逆向学习、预期-结果偏差信号 |
| 中央 OFC | mOFC↔lOFC 整合 | 价值整合枢纽（功能证据较少） |
| 腹外侧 OFC（ORBvl） | DMS（背内侧纹状体） | 经济决策信号→目标导向行动转化 |

## 连接

- [[prefrontal-cortex]] — vmPFC/dlPFC 整合并调制 OFC 价值信号
- [[amygdala]] — BLA↔OFC 双向回路，价值记忆的存储与检索
- [[basal-ganglia]] — OFC→DMS 通路，目标导向行动选择
- [[nucleus-accumbens]] — OFC 与 NAc 协作（OFC: 选哪个；NAc: 多想要）
- [[dopamine-reward-prediction-error]] — DA 调制 OFC 和 BLA 的突触可塑性
- [[anterior-cingulate-cortex]] — OFC 顺序表征价值后，ACC 加速选择准备
- [[value-based-decision-making]] — OFC 是价值决策回路的核心计算节点
- [[insular-cortex]] — 岛叶通过躯体标记（somatic marker）向 OFC/vmPFC 提供身体状态信号，影响价值更新的情感背景
- [[interoception]] — OFC 在编码奖赏预期时整合了来自岛叶的内感觉状态输入

## 未解问题

- **Q-ofc-01（高优先级）**：lOFC vs mOFC 的功能边界是否足够清晰？部分研究显示两者功能有重叠——究竟是解剖梯度（而非离散边界）、还是任务依赖的功能重配？
- **Q-ofc-02（中优先级）**：OFC 在做选择，还是只是报告已经由下游结构做出的选择？"chosen value cells"的滞后激活是生成信号还是读出信号？
- **Q-ofc-03（中优先级）**：OFC 在社会决策（信任、利他、竞争）中的角色：是共用同一套价值代码，还是有专化的社会价值维度？

## 修订历史

- 2026-08-21 · 创建 · 基于《价值的解剖：眶额皮层如何为选项定价》（#119）· 初始置信度：高
- 2026-08-22 · 修订 · 新增岛叶-OFC 躯体标记连接说明；更新 related 字段（新增 insular-cortex、interoception）· 依据：2026-08-22-insular-cortex-interoception-bodily-self

## 来源文章

- [[2026-08-21-orbitofrontal-cortex-value-decision-circuit]]

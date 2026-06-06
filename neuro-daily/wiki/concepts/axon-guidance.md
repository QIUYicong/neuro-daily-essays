---
title: 轴突导向
slug: axon-guidance
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-04
updated: 2026-08-04
revision_count: 1
dimensions: [molecular, cellular, brain-region]
related: [growth-cone, retinotopic-map, synaptogenesis, critical-period, connectomics, hippocampal-circuit, synaptic-pruning]
prerequisites: [synaptic-transmission, action-potential, hebbian-learning]
opens_questions: [Q-axon-guidance-01, Q-axon-guidance-02, Q-axon-guidance-03]
source_articles: [2026-08-04-axon-guidance-growth-cone-wiring]
key_sources: ["PMID:8895455", "PMID:21123392", "PMID:36942388", "PMID:39075893", "PMID:14077501"]
---

# 轴突导向 (Axon Guidance)

> **一句话定义**：轴突导向是发育中的神经元轴突借助生长锥感知四大家族导向分子（Netrin/Slit/Semaphorin/Ephrin）形成的化学梯度，将肌动蛋白骨架不对称重组转化为精确的方向性延伸，最终建立拓扑有序的神经回路的过程。

---

## 当前理解

我们现在认为，大脑精密回路的布线依赖两层互补机制：

1. **遗传编码的化学亲和性梯度**（由四大导向分子家族提供）：决定"轴突走的大方向和大框架"，建立粗略拓扑图。
2. **活动依赖的 Hebbian 精化**：在遗传框架基础上，根据神经元的同步活动进一步精化精确的连接模式（关键期）。

两种机制的分工原则：化学梯度确保"视网膜中央凹映射到视觉皮层中心区域"等大局精度；活动精化在局部调整"精确感受野大小和形状"等细节。

**这一理解如何改变我们对大脑的认识**：大脑的精密布线不是随机初始化后学习的，而是由进化在数亿年中筛选的基因程序写就的发育先验。这解释了为什么大脑以极少的经验就能学到很多（相比深度学习系统需要百亿训练样本）——结构先验已经内置了大量来自进化的"归纳偏置"（inductive bias）。

---

## 关键机制

### 1. 生长锥的感觉-运动整合

生长锥是轴突顶端的导航器官，由板状伪足（网状 F-actin）和丝状伪足（束状 F-actin 探针）组成。

运动机制：肌动蛋白**踏车运动**（treadmilling）——前端聚合推动膜前伸，后端解聚回收单体。感知信号后，受信号侧 F-actin 聚合被选择性增强或减弱，产生不对称性，驱动生长锥转向。

### 2. 四大导向分子家族

| 家族 | 分泌方式 | 受体 | 主要效应 | 典型场景 |
|------|---------|------|---------|--------|
| **Netrin**（神经蛋白） | 扩散型（长程） | DCC（吸引）/ UNC5（排斥）| 吸引或排斥（双功能） | 联合轴突穿越中线 |
| **Slit**（裂缝蛋白） | 扩散型（中线） | ROBO1/2 | 排斥 | 防止轴突二次穿越中线 |
| **Semaphorin**（信号素） | 扩散型+膜结合型 | NRP+Plexin 复合体 | 排斥为主（MICAL 氧化 actin）| 嗅球地图，多脑区局部排斥 |
| **Ephrin**（促速素） | 膜结合型 | Eph 受体（酪氨酸激酶）| 双向排斥为主，DV 轴可吸引 | 视网膜-上丘体地形图 |

### 3. 拓扑地形图建立的梯度×梯度逻辑

以视网膜-上丘体（retinocollicular）地形图为例：
- 视网膜颞侧高 EphA → 上丘体尾侧高 EphrinA → 颞侧轴突被排斥停在吻侧
- 上丘体的 EphA（反向信号）进一步精确限定终止区域
- 背腹轴：EphB/EphrinB 系统（吸引性正向信号）

完整地图 = EphA×EphrinA（NT轴）× EphB×EphrinB（DV轴）× 活动精化

### 4. 突触靶点分子识别（Teneurin-LPHN 系统）

海马内嗅皮层到 CA1 的层状投射机制：
- MEC 轴突 TEN3+ → CA1 近端树突 TEN3+：同质吸引（TEN3-TEN3）
- LEC 轴突 LPHN2+ → CA1 远端树突 LPHN2+：同质吸引（LPHN2-LPHN2）
- TEN3-LPHN2 异质排斥：防止错投

结果：MEC（空间/网格信息）→ CA1 近端；LEC（物体/情境信息）→ CA1 远端。这是海马信息路由架构的分子基础。

---

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Netrin-1 通过 DCC 受体吸引联合轴突穿越中线 | DCC 敲除→前连合减少；体外梯度转向实验 | PMID:8895455 | 高 |
| ROBO3 突变破坏人类中线交叉，导致 HGPPS | 人类遗传：ROBO3 突变患者眼动/脊柱表型 | PMID:36942388 | 高（人类遗传证据）|
| EphrinA-EphA 梯度建立视网膜鼻颞轴地图 | EphrinA2/5 双敲除→地图紊乱；正反信号联合删除 | PMID:8895455; PMID:21123392 | 高 |
| MICAL 氧化 actin 执行 Semaphorin 排斥 | MICAL 结构生化；MICAL KO → 轴突靶向异常 | PMID:36942388 | 中-高 |
| Teneurin-LPHN 系统建立海马 MEC/LEC 层状投射 | 遗传谱系追踪+条件敲除（小鼠）| PMID:36942388 | 中-高（需独立验证）|
| 化学梯度+活动精化协同建立视觉地图 | 联合删除 EphrinA 和视网膜波才完全破坏地图 | PMID:36942388 | 高 |

---

## 连接

- [[growth-cone]] — 轴突导向的执行器官；感受分子梯度，驱动方向性延伸
- [[retinotopic-map]] — 轴突导向机制（EphrinA/EphA 梯度）建立的最深研究案例
- [[synaptogenesis]] — 轴突到达靶区后的下一步：突触形成
- [[critical-period]] — 活动依赖精化是导向粗略框架的细化，关键期关闭切断精化通道
- [[connectomics]] — 连接组学记录"布线完成后"的结构，轴突导向是"布线发生"的机制——两者互补
- [[hippocampal-circuit]] — Teneurin-LPHN 系统建立了 MEC→CA1 近端/LEC→CA1 远端的层状投射，是海马回路功能架构的分子基础
- [[synaptic-pruning]] — 导向建立初始连接后，突触剪枝通过活动依赖的消除进一步精化

---

## 未解问题

- **Q-axon-guidance-01**（高优先级）：体内导向分子梯度的实际形态——体内测量方法的突破是整个领域亟需的
- **Q-axon-guidance-02**（中优先级）：人类/灵长类与小鼠的导向机制差异——新皮层扩张数量级是否需要特殊的导向适应
- **Q-axon-guidance-03**（高优先级）：多导向信号的整合规则——生长锥如何处理同时到达的矛盾信号

---

## 修订历史

- 2026-08-04 · 创建 · 基于《大脑如何给自己布线》文章（#103）· 课程脊柱第2章核心新节点 · 初始置信度：高（established，多物种、多层次证据）

---

## 来源文章

- [[2026-08-04-axon-guidance-growth-cone-wiring]]

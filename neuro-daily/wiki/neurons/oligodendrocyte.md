---
title: 少突胶质细胞
slug: oligodendrocyte
domain: neurons
type: structure
status: established
confidence: high
created: 2026-07-27
updated: 2026-07-27
revision_count: 1
dimensions: [molecular, cellular, brain-region]
related: [myelination, action-potential, axon-initial-segment, opc, multiple-sclerosis, critical-period, dopamine-reward-prediction-error, astrocyte, microglia]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: [Q-myelin-01, Q-myelin-02]
source_articles: [2026-07-27-myelination-oligodendrocyte-plasticity]
key_sources: ["PMID:33863642", "PMID:24727982", "PMID:34618550", "PMID:37857838"]
---

# 少突胶质细胞 (Oligodendrocyte)

> **一句话定义**：中枢神经系统中唯一的髓鞘制造细胞，单个细胞可同时包裹 40–50 条来自不同神经元的轴突段，并终生通过感知神经元活动来动态调节髓鞘厚度与分布，是大脑白质可塑性的核心执行者。

## 当前理解

我们现在认为，少突胶质细胞（oligodendrocyte，OL）不是被动的绝缘层铺设者，而是与神经元持续双向对话、终生参与回路调节的主动细胞。

**基本特征**：
- 形态：伸出 40–50 条细长过程，每条包裹一段不同轴突
- 与 PNS 施万细胞的区别：施万细胞一对一包裹单条轴突；OL 一对多，因此 OL 能感知多条轴突的集体活动并统筹响应
- 数量：约占大脑细胞总数的 5–10%（含前体细胞 OPC）

**前体细胞（OPC）**：少突胶质细胞前体细胞是成年大脑中数量最多的增殖细胞，均匀分布于白质和灰质中，保持终生分化潜能。OPC 表面表达谷氨酸受体（AMPA/NMDA）和嘌呤受体（P2X/P2Y），直接感知活跃轴突的信号，将神经元活动转化为细胞增殖和分化的指令。

**从 OPC 到 OL 的分化**：
1. 神经元放电 → 轴突释放谷氨酸/ATP
2. OPC 谷氨酸受体激活 → 胞内 Ca²⁺ 信号
3. 转录因子（Olig2、Myrf）激活 → OPC 增殖并分化
4. OL 伸出"臂膀"接触轴突 → 螺旋包裹并压缩脂质膜
5. 致密髓鞘形成，节点结构建立

**代谢支持功能**：除了制造髓鞘，OL 还通过乳酸穿梭（lactate shuttle）向包裹的轴突提供能量底物，保障轴突的长期存活。OL 功能障碍可导致轴突退化，早于髓鞘脱失本身。

## 关键机制

**1. 包裹机制**：OL 膜螺旋缠绕轴突，内侧细胞质被挤出，形成"致密髓鞘"（compact myelin，~70-80% 脂质，~20-30% 蛋白质）。关键蛋白：MBP（压缩层间黏合）、PLP（维持层间稳定）。

**2. 节点结构建立**：OL 末端（paranode）通过 Neurofascin-155 与轴膜上的 CASPR/Contactin 复合体结合，形成离子屏障，将 Nav1.6 钠通道限制在兰维耶节（Node of Ranvier），实现跳跃式传导。

**3. 活动依赖性调节**：Gibson et al. 2014（PMID:24727982）的光遗传实验表明，激活运动前区轴突 → OPC 增殖 → OL 生成增加 → 行为改善；阻断 OL 分化消除行为改善（因果关系）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 单个 OL 包裹 40–50 不同轴突段 | 电子显微镜三维重建 + 谱系追踪 | PMID:33863642（综述） | 高 |
| 神经元活动诱导 OPC 增殖和 OL 分化 | 光遗传激活 + BrdU 标记 + 遗传阻断对照 | PMID:24727982 | 高 |
| 阻断 OL 分化消除活动诱导的行为改善 | CreER 遗传阻断 + 运动测试 | PMID:24727982 | 高 |
| VTA 多巴胺活动驱动局部 OL 生成，OL 缺失损害多巴胺释放和奖励行为 | 光遗传激活 + 遗传阻断 OL 生成 | PMID:38839962 | 高 |
| 人类 OPC 更新速度比小鼠慢约 100 倍 | 碳同位素标记（14C 出生队列） + 细胞计数 | PMID:33863642（综述） | 中-高 |

## 连接

- [[myelination]] — OL 执行髓鞘化，是这一过程的唯一 CNS 细胞来源
- [[action-potential]] — 髓鞘改变动作电位的传导速度和节点结构
- [[opc]] — OL 的前体细胞，终生保持增殖和分化潜能（→待创建）
- [[multiple-sclerosis]] — 免疫系统攻击 OL 和髓鞘，导致信号传导障碍（→待扩充）
- [[critical-period]] — OL 缺失影响关键期的皮层可塑性（发育时序连接）
- [[dopamine-reward-prediction-error]] — VTA 中 OL 可塑性对奖励回路的调谐（Yalçın 2024）
- [[astrocyte]] — OL 与星形胶质细胞共同构成大脑神经胶质细胞的功能网络
- [[axon-initial-segment]] — AIS 是动作电位发起位点，髓鞘从 AIS 之外的轴突节段开始

## 未解问题

- Q-myelin-01：人类成年期的 OL 可塑性程度——大规模 OL 新生 vs 既有 OL 形态调整，哪种机制主导？
- Q-myelin-02：OPC 如何选择包裹哪条轴突？活跃轴突的竞争选择机制是什么？

## 修订历史

- 2026-07-27 · 创建 · 基于《绝缘层的革命》（第95篇）· 初始置信度：高

## 来源文章

- [[2026-07-27-myelination-oligodendrocyte-plasticity]]

---
title: 少突胶质细胞
slug: oligodendrocyte
domain: neurons
type: entity
status: established
confidence: high
created: 2026-10-05
updated: 2026-06-28
revision_count: 2
dimensions: [molecular, cellular, synaptic, brain-region, whole-brain-network]
related: [oligodendrocyte-precursor-cell, adaptive-myelination, saltatory-conduction, myelin-basic-protein, microglia, astrocyte, multiple-sclerosis, axon-initial-segment]
prerequisites: [action-potential, axon-initial-segment, synaptic-transmission]
opens_questions: [Q-ol-sleep-myelination, Q-ol-opc-selectivity, Q-ol-aging]
source_articles: [2026-10-05-oligodendrocyte-adaptive-myelination, 2026-06-28-multiple-sclerosis-myelin-computation]
key_sources: ["PMID:40761314", "PMID:25324381", "PMID:22801498", "PMID:10821275", "PMID:37838794"]
---

# 少突胶质细胞 (Oligodendrocyte)

> **一句话定义**：少突胶质细胞是中枢神经系统（CNS）唯一的产髓鞘胶质细胞，每个细胞向 40–50 条轴突延伸髓鞘节段，通过跳跃式传导将动作电位传导速度提升至最高约 120 m/s，同时经 MCT1-乳酸通路为轴突提供代谢底物，并在整个成年期持续响应神经活动进行自适应髓鞘化。

## 当前理解

我们现在认为，少突胶质细胞是一个集**绝缘体（跳跃式传导）、代谢供体（乳酸轴）和可塑性媒介（经验依赖髓鞘化）**三重功能于一身的细胞类型，远非最初认为的静态"包裹机器"。

关键认识转变发生在三个节点：
1. **2000年 Bergles 等人**的发现揭示，少突胶质细胞前体（OPC）直接接收神经元的谷氨酸能突触传入，从而能"感知"局部神经活动（PMID: 10821275）。
2. **2012年 Lee 等人**证明，少突胶质细胞通过 MCT1 向轴突输出乳酸，是轴突长期存活的代谢基础，MCT1 缺乏本身即可导致轴突退化（PMID: 22801498）。
3. **2014年 McKenzie 等人**证明，新生少突胶质细胞的产生是运动技能学习所必需的：条件性阻断 Myrf 导致 OPC 无法分化，运动学习能力丧失（PMID: 25324381）。

少突胶质细胞与神经元之间的关系因此应被理解为**双向的代谢-信号耦合**：神经元活动驱动 OPC 分化产生新 OL，新 OL 反过来调整轴突传导时序并提供代谢支持，进一步影响回路功能。

## 关键机制

### 髓鞘结构
- 一个成熟少突胶质细胞可向 40–50 条不同轴突伸出髓鞘节段
- 髓鞘由压缩的细胞膜脂质双层组成（约 70% 脂质，30% 蛋白质）
- **郎飞结**（nodes of Ranvier）是未被髓鞘覆盖的节点，集中了高密度电压门控钠通道
- 跳跃式传导：动作电位在郎飞结之间"跳跃"，无髓鞘轴突约 1 m/s，有髓鞘轴突约 70–120 m/s

### 代谢支持
- MCT1（单羧酸转运蛋白 1）高度富集于少突胶质细胞，将乳酸/丙酮酸输出到轴突旁空间
- 轴突通过 MCT2 摄取并氧化产生 ATP
- 少突胶质细胞内膜通道（inner tongue 细胞质管道）将代谢底物直接递送到与轴突接触的内层髓鞘

### OPC → 成熟 OL 分化信号
- 谷氨酸（AMPA/NMDA 受体）→ 钙内流 → 分化程序启动
- BDNF → TrkB → PI3K-AKT-mTOR → OPC 存活与分化
- NRG1 → ErbB3/ErbB4 → 髓鞘厚度调控
- Wnt/β-catenin（TCF7L2）和 Notch 通路的平衡决定 OPC 分化时机

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 成年期运动技能学习需要新 OL 生成 | Myrf 条件敲除小鼠复杂轮学习受损 | PMID:25324381 (摘要级) | 高 |
| 认知训练（工作记忆）驱动 OPC 增殖 4 倍 | T 迷宫 + BrdU 追踪 + Myrf KO 对照 | PMID:37838794 (全文) | 高 |
| MCT1 缺失导致轴突损伤 | MCT1 敲减 → 轴突退化，ALS 中 MCT1 降低 | PMID:22801498 (全文) | 高 |
| OPC 接收神经元谷氨酸能突触输入 | 全细胞膜片钳 + 电子显微镜确认突触结构 | PMID:10821275 (摘要级) | 高 |
| 光遗传激活 mPFC 轴突→髓鞘厚度增加（轴突特异性） | 光遗传 + 电子显微镜比较刺激 vs 非刺激轴突 | Gibson 2014（引自综述）| 中 |

## 连接

- [[oligodendrocyte-precursor-cell]] — 前体细胞，终生存在，接收突触输入
- [[adaptive-myelination]] — 核心机制：神经活动驱动新髓鞘生成
- [[saltatory-conduction]] — 髓鞘实现的信号传导方式
- [[multiple-sclerosis]] — 少突胶质细胞自身免疫损伤的疾病窗口
- [[microglia]] — 相关胶质细胞，主要参与免疫；共同构成神经免疫单元
- [[astrocyte]] — 相关胶质细胞，参与离子稳态和三突触系统
- [[axon-initial-segment]] — 动作电位发起位点，髓鞘化始于 AIS 远端
- [[mct1-lactate-transport]] — 代谢支持核心分子

## 未解问题

- Q-ol-sleep-myelination（高优先级）：夜间睡眠中是否存在优先的髓鞘化时间窗？新生 OL 的形成是否与 SWR 慢波活动协调？
- Q-ol-opc-selectivity（高优先级）：新生 OL 是否精确选择性地包裹活跃参与特定任务的轴突，还是存在非特异性整体扩张？OPC-轴突匹配规则是什么？
- Q-ol-aging（中优先级）：老年 OPC 分化能力下降与认知老化是否存在直接因果关系？恢复老年 OPC 分化是否能改善认知？

## 修订历史

- 2026-10-05 · 创建 · 基于《髓鞘的秘密：当少突胶质细胞感知神经冲动，开始重写脑的线路图》(#165) · 初始置信度：高
- 2026-06-28 · 修订 rev2 · 基于《当绝缘层失守：多发性硬化如何揭示髓鞘对神经时序与认知的隐形贡献》(#183) · 补充 MCT1-乳酸通路中断在 MS 轴突退化中的机制角色；关联 multiple-sclerosis 疾病条目

## 来源文章

- [[2026-10-05-oligodendrocyte-adaptive-myelination]]
- [[2026-06-28-multiple-sclerosis-myelin-computation]]

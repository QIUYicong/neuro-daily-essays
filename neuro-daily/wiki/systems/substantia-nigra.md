---
title: 黑质
slug: substantia-nigra
domain: systems
type: region
status: established
confidence: high
created: 2026-06-06
updated: 2026-06-06
revision_count: 1
dimensions: [cellular, brain-region, behavior, disease]
related: [vta, dopamine-reward-prediction-error, direct-indirect-pathway, d1-d2-receptor-signaling, basal-ganglia, parkinsons-disease, dopamine-systems-anatomy]
prerequisites: [synaptic-transmission, dopamine-systems-anatomy]
opens_questions: [Q-snc-anxa1-projection, Q-snc-dorsal-ventral-tier]
source_articles: [2026-06-06-dopamine-systems-anatomy]
key_sources: ["PMID:37537242", "PMID:24735820", "PMID:30716356"]
---

# 黑质 (Substantia Nigra, SN)

> **一句话定义**：中脑多巴胺系统的 A9 核团（黑质致密部，SNc），主要向背侧纹状体（尾状核+壳核）发出黑质纹状体通路，调控运动序列的启动与执行；其内部包含至少三种遗传-功能分离的亚群（Calb1+、Vglut2+、Anxa1+）。

## 当前理解

我们现在认为，黑质（尤其是致密部，SNc）不是"单一运动多巴胺核团"，而是一个内部存在功能分化的结构：

**经典角色**（已确立）：SNc 多巴胺神经元通过黑质纹状体通路（nigrostriatal pathway）向背侧纹状体投射，调控基底神经节直接/间接通路的平衡，进而影响运动序列的选择、启动和执行。帕金森病中 SNc 神经元死亡（症状出现时已失去约 60-80% 神经元）导致纹状体多巴胺耗竭，直接/间接通路严重失衡。

**遗传亚型的功能分化**（Azcorra 等 2023，Nat Neurosci，PMID:37537242）：
- **Calb1+（钙结合蛋白 D-28k 阳性）**：强奖励响应（奖励量越大激活越强→价值编码）+ 运动减速时激活。提示 SNc 的 Calb1+ 亚群参与价值学习，不只是"纯运动"功能。
- **Vglut2+**：中等奖励响应 + 运动相关活动；可能参与多巴胺-谷氨酸共释放功能。
- **Anxa1+（膜联蛋白 A1 阳性，首次报告）**：奖励响应几乎完全缺失；仅在运动**加速**时显著激活（而非减速）。可能专门负责运动方向初始化或运动启动信号。

这一发现打破了"SNc = 运动 / VTA = 奖励"的粗糙二分法：SNc 内部 Calb1+ 亚群同样参与奖励价值编码，而 Anxa1+ 亚群则代表了一种全新的功能维度（运动加速方向），其完整图谱尚待研究。

**黑质的解剖分区**（腹侧层 vs 背侧层）：
- **腹侧层**（ventral tier）：主体 SNc，钙结合蛋白阴性（calbindin-negative），主要投射到腹侧纹状体，与奖励相关纹状体区域联系更密切，是帕金森病中最先丢失的神经元群
- **背侧层**（dorsal tier）：钙结合蛋白阳性，与 VTA 相邻，投射到背侧纹状体，相对抗 PD 损伤

## 关键机制

### 黑质纹状体通路的运动控制逻辑
SNc 多巴胺释放 → D1-MSN 激活（直接通路）+ D2-MSN 抑制（间接通路）→ 去抑制丘脑 → 皮层运动指令顺利执行

帕金森病中 DA 耗竭后：D2-MSN（间接通路）失去抑制 → 间接通路过度激活 → 丘脑过度抑制 → 运动启动困难 + β振荡锁死（13-30 Hz）

### SNc 多巴胺神经元的电生理特征
- 宽动作电位（>2ms），有自主低频放电
- L型钙通道驱动的起搏电位（是 SNc 神经元对氧化应激更敏感的原因之一，也是帕金森病选择性损伤的分子基础之一）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| SNc Anxa1+亚型奖励响应缺失；运动加速时激活 | 双光子钙成像 + 遗传标记 + 非监督聚类（91%准确率）| PMID:37537242 | 中（首次报告，待复制）|
| SNc Calb1+亚型有奖励响应（价值编码） | 双光子钙成像 | PMID:37537242 | 中 |
| SNc（A9）主要投射背侧纹状体（黑质纹状体通路） | 荧光逆行/顺行示踪 | PMID:24735820 | 确立 |
| 帕金森病 SNc 腹侧层神经元优先死亡 | 死后尸检 + PET + TH 免疫组化 | 多项综述 | 确立 |

## 连接

- [[vta]] — 相邻核团（A10），主要投射 NAc/PFC（奖励/认知）；SNc 与 VTA 的功能边界正在被遗传亚型研究重新划定
- [[direct-indirect-pathway]] — SNc 多巴胺信号通过 D1/D2 调控直接/间接通路的平衡（黑质纹状体通路的功能核心）
- [[d1-d2-receptor-signaling]] — 纹状体 D1/D2 受体是 SNc 信号的下游执行器
- [[basal-ganglia]] — 纹状体（SNc 的主要投射靶区）是基底神经节的输入层
- [[parkinsons-disease]] — SNc 神经元死亡的直接后果

## 未解问题

- Q-snc-anxa1-projection：Anxa1+ 亚型投射到纹状体哪个具体亚区？其下游是 D1 还是 D2 受体介导？
- Q-snc-dorsal-ventral-tier：背侧/腹侧层（calbindin+/-）的功能差异与遗传亚型（Calb1/Anxa1）分类是否对应？

## 修订历史

- 2026-06-06 · 创建 · 基于《奖励、运动与认知的统一信使》(#15) · 初始置信度：高（黑质纹状体通路），中（遗传亚型分化）

## 来源文章

- [[2026-06-06-dopamine-systems-anatomy]]

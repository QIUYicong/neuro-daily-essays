---
title: 腹侧被盖区
slug: vta
domain: systems
type: region
status: established
confidence: high
created: 2026-06-06
updated: 2026-06-06
revision_count: 1
dimensions: [cellular, brain-region, whole-brain-network, behavior, cognition]
related: [dopamine-reward-prediction-error, substantia-nigra, nucleus-accumbens, prefrontal-cortex, direct-indirect-pathway, d1-d2-receptor-signaling, lateral-habenula, rmtg, dopamine-systems-anatomy]
prerequisites: [synaptic-transmission, action-potential, dopamine-systems-anatomy]
opens_questions: [Q-da-heterogeneity, Q-da-aversion]
source_articles: [2026-06-06-dopamine-systems-anatomy]
key_sources: ["PMID:35226827", "PMID:24735820", "PMID:24130517"]
---

# 腹侧被盖区 (Ventral Tegmental Area, VTA)

> **一句话定义**：中脑多巴胺系统的 A10 核团，位于黑质腹内侧，向伏隔核、前额叶及其他边缘结构发出中脑边缘和中脑皮层多巴胺投射，是奖励、动机与认知调控的关键解剖节点；其内部存在基于解剖拓扑和遗传亚型的功能异质性。

## 当前理解

我们现在认为，VTA 不是一个均质的"奖励核团"，而是一个内部具有精细拓扑组织的异质结构。其多巴胺神经元按照投射靶区在 VTA 内部呈现清晰的空间分布：

**内侧 VTA 神经元** → NAc 内侧壳（medial shell）和 NAc 核心：这类神经元的一个亚群对厌恶刺激选择性激活（NAc 腹侧内侧壳多巴胺增加），而非对奖励的简单响应。

**外侧 VTA 神经元** → NAc 外侧壳（lateral shell）：这是经典的"奖励多巴胺神经元"——奖励预期和获得时激活，厌恶刺激时被抑制。

VTA 的主要传出通路包括：
- **中脑边缘通路**（mesolimbic pathway）：VTA → NAc（伏隔核）→ 奖励/动机
- **中脑皮层通路**（mesocortical pathway）：VTA → PFC（前额叶皮层）→ 认知门控/工作记忆
- 次要投射：眶额皮层、杏仁核、海马、外侧隔核、腹侧苍白球等

VTA 的主要传入来源分三层（Yetnikoff 等 2014）：
1. 下丘脑-视前区-苍白球延续带（同步驱动/代谢状态输入）
2. NAc/嗅球结节/外侧隔核的 MSN（来自靶区的反馈）
3. 皮层谷氨酸投射（认知控制信号）

VTA 多巴胺神经元还可以**共释放谷氨酸**（via VGluT2）和 **GABA**（via VMAT2），使其信号传递超越单纯多巴胺调制。

**长期被忽视的偏差**：de Jong 等（2022）指出，该领域大多数研究偏好记录外侧 VTA 神经元，但在 NAc *核心*（而非外侧壳，即外侧 VTA 的真正主要靶区）测量多巴胺释放——这一解剖坐标错位造成了"VTA 多巴胺 = 奖励信号"这一认知的系统性偏差，遮蔽了内侧 VTA 的厌恶编码功能。

## 关键机制

### 多巴胺释放的时序模式
- **相位性爆发（Phasic burst）**：3-8个动作电位的短暂高频爆发（>20 Hz），产生 NAc 短暂多巴胺峰值，编码奖励预测误差（δ）
- **紧张性放电（Tonic）**：基线低频放电（~4 Hz），维持目标区域的基础多巴胺水平，设定"背景动机状态"

### VTA 多巴胺神经元的抑制性输入
外侧缰核（LHb）→ 喙内侧被盖核（RMTg，GABA能）→ VTA 多巴胺神经元抑制：这是奖励预测误差负向臂（δ<0）的回路实现（见 [[lateral-habenula]], [[rmtg]]）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 内侧 VTA→NAc 内侧壳；外侧 VTA→NAc 外侧壳（拓扑投射） | 荧光逆行示踪 + 光遗传 | PMID:35226827 | 高 |
| 内侧 VTA 亚群对厌恶刺激激活 | 光纤光度法钙成像 + 无线记录 | PMID:35226827 | 中-高 |
| VTA 多巴胺共释放谷氨酸（VGluT2+亚群）| 免疫组化 + 电生理 + 光遗传 | PMID:24735820 综述 | 高 |

## 连接

- [[dopamine-reward-prediction-error]] — VTA 多巴胺神经元是 RPE 信号的主要来源
- [[substantia-nigra]] — 相邻核团（A9），主要投射背侧纹状体（运动控制）
- [[nucleus-accumbens]] — VTA 的主要投射靶区之一（中脑边缘通路）
- [[prefrontal-cortex]] — VTA 的另一主要投射靶区（中脑皮层通路）
- [[d1-d2-receptor-signaling]] — 靶区的多巴胺受体决定了 VTA 信号的下游效应
- [[lateral-habenula]] — 提供 VTA 多巴胺神经元的间接 GABA 抑制（负预测误差的回路来源）
- [[direct-indirect-pathway]] — VTA/SNc 多巴胺信号通过 D1/D2 调控这两条通路的平衡

## 未解问题

- Q-da-heterogeneity：内侧 VTA 厌恶编码多巴胺神经元的体内多巴胺释放是否有直接电化学验证？
- Q-da-aversion：厌恶刺激时 NAc 内侧壳的多巴胺增加是 DA 本身还是共递质谷氨酸/GABA 的效果？

## 修订历史

- 2026-06-06 · 创建 · 基于《奖励、运动与认知的统一信使》(#15) · 初始置信度：高（三条通路解剖），中-高（VTA内部异质性）

## 来源文章

- [[2026-06-06-dopamine-systems-anatomy]]

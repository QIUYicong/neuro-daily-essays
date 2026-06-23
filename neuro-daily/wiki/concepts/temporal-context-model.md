---
title: 时间情境模型
slug: temporal-context-model
domain: concepts
type: theory
status: emerging
confidence: medium
created: 2026-08-04
updated: 2026-09-06
revision_count: 2
dimensions: [brain-region, cognition, whole-brain-network]
related: [time-cells, hippocampal-circuit, memory-consolidation, entorhinal-cortex, complementary-learning-systems, ca2-hippocampus, prefrontal-cortex, sharp-wave-ripples]
prerequisites: [hippocampal-circuit, time-cells]
opens_questions: [Q-tc-01, Q-tc-04]
source_articles: [2026-08-04-hippocampal-time-cells-episodic-memory, 2026-09-06-tcm-neural-basis-mec-ca2-temporal-scaffold]
key_sources: ["PMID:23915126", "PMID:24672015", "PMID:28858612", "PMID:23318095", "PMID:34474155", "PMID:30175425", "PMID:32277786", "PMID:29145670"]
---

# 时间情境模型 (Temporal Context Model, TCM)

> **一句话定义**：Howard & Eichenbaum提出的海马时间记忆理论框架——海马维持一个随时间缓慢连续漂移的"时间情境状态"（temporal context state），这个状态在编码时被绑定到每个经历的事件，在提取时恢复这个状态即实现"精神时间旅行"（mental time travel）。

## 当前理解

我们现在认为，TCM提供了一个解释海马如何跨越不同时间尺度组织情节记忆的统一框架。其核心主张：

1. **时间情境状态**（$\mathbf{t}$）：一个缓慢连续演化的内部神经状态向量，不需要外部刺激驱动，类似于一个"内部时钟读数"
2. **编码**：事件A发生时，被绑定到当时的时间情境状态 $\mathbf{t}_A$；事件B发生时，绑定到 $\mathbf{t}_B$
3. **提取**：如果检索线索能恢复接近 $\mathbf{t}_A$ 的时间情境状态，则事件A得以提取
4. **时间梯度**：$\mathbf{t}$ 缓慢漂移，因此时间上接近的事件有相似的 $\mathbf{t}$，远离的事件 $\mathbf{t}$ 差异大 → 预测"新近性效应"（recency effect）和"邻近性效应"（contiguity effect）

**行为预测**：在自由回忆任务中，参与者倾向于按照学习时间顺序提取（时间聚类），并且刚刚提取了第N个词后，倾向于提取时间上相邻的第N±1个词（contiguity effect）。这些预测与实验数据高度吻合（Howard & Eichenbaum 2013）。

**与时间细胞的联系**：时间细胞的依次序列激发，可能正是TCM中"时间情境状态"的神经实现——每一时刻激发的神经集群模式就是该时刻的 $\mathbf{t}$。Umbach et al. 2020发现时间细胞稳定性预测时间聚类性，直接支持这一联系。

## 关键机制

### 时间情境状态的漂移

- $\mathbf{t}$ 是一个高维向量，随时间连续漂移（类比于空间中的"当前位置"向量随运动连续变化）
- 漂移速度决定"时间分辨率"：漂移慢则记忆时间排序精细；漂移快则远期记忆的时间分辨率下降
- **标量特性**的自然解释：随着时间延伸，$\mathbf{t}$ 的漂移量增大，时间情境相似性下降更快 → 远期记忆的时间辨别更难（符合韦伯定律的时间版本）

### 精神时间旅行

提取时，成功的记忆线索会"锚定"海马状态到近似 $\mathbf{t}_A$，引发当年的时间情境状态被部分恢复——这就是Tulving所描述的情节记忆"亲历感"（autonoetic consciousness）的可能神经机制。

### 数学框架：泄漏积分器与Laplace变换（Howard et al. 2014）

Howard等人2014年（PMID: 24672015）提出了统一的计算框架：用**泄漏积分器（leaky integrators）**实现对过去输入的Laplace变换，从而在不同时间尺度同时表示时间信息。

关键预测：
- 时间细胞的激发时间窗与任务间隔等比例缩放（标量特性）
- 同一神经集群可以同时编码秒/分/天三个尺度的时间信息
- 空间编码（路径积分）和时间编码共享同一计算结构

这些预测均已获得部分实验验证（Mau et al. 2018，PMID: 29706516；Shimbo et al. 2021）。

### 神经底层候选：MEC漂移 + CA2 + CA1时间细胞序列

**（更新于2026-09-06，基于文章#136）**

TCM时间情境状态$\mathbf{t}$的神经实现目前最佳候选是分布式的三节点系统：

1. **内嗅皮层（MEC）**：约15%的Layer III非网格细胞在6小时内显著时间漂移（Diehl et al. 2019，PMID: 30175425）；通过颞氨通路（Layer III→CA1）直接传递时间信号；MEC损伤选择性损害长时间判断（>10秒，Vo et al. 2021，PMID: 34474155）；MEC光遗传沉默→CA1时间细胞序列降解（Robinson et al. 2017，PMID: 28434800）

2. **CA2区**：活动跨时间变化大于跨空间情境变化（Mankin et al. 2015，PMID: 25569350）；接受来自上乳头核（SuM）的时间调制信号；CA2→CA1投射选择性组织CA1时间细胞（48%受影响，MacDonald & Tonegawa 2021，PMID: 33431691）

3. **CA1**：输出端；整合MEC（时间）+CA3（内容）+CA2（时间组织）→ 时间-内容联合表征；Mau et al. 2018证明同一CA1集群同时编码秒/分/天三尺度时间

**状态**：分段因果证据充分（MEC→CA1，CA2→CA1各有独立实验），但**完整MEC→CA2→CA1链路尚无整合验证**；Q-tc-01仍开放（见未解问题）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 自由回忆中存在时间聚类效应 | 行为学（多个实验室重复） | PMID:23915126 | 高 |
| TCM预测的contiguity effect符合行为数据 | 自由回忆条件概率分析 | PMID:23915126 | 高（行为层面） |
| 时间情境状态神经实现候选：CA1时间细胞稳定性预测时间聚类性 | 人类癫痫患者颅内记录 | PMID:33109718 | 中 |
| 同一CA1集群同时编码秒/分/天多尺度（支持Laplace框架） | 小鼠钙成像4天 | PMID:29706516 | 高 |
| MEC损伤→选择性损害长时间判断（>10秒） | 大鼠MEC损伤+时间二分任务 | PMID:34474155 | 高（因果）|
| MEC Layer III约15%非网格细胞随时间漂移（不跨空间） | 大鼠MEC电生理6小时追踪 | PMID:30175425 | 中-高 |
| MEC→CA1颞氨通路传递时间信号（vs穿透纤维传情境） | 解剖+功能综述 | PMID:32277786 | 中（综述）|
| CA2活动跨时间变化大于跨空间变化 | 大鼠CA2多情境电生理 | PMID:25569350 | 高 |
| mPFC也有时间细胞（时间编码跨区域通用） | 大鼠mPFC时间判别任务 | PMID:29145670 | 高 |

## 连接

- [[time-cells]] — 时间细胞是TCM中"时间情境状态"的神经实现候选；CA1时间细胞序列 = $\mathbf{t}$ 向量的依次激活
- [[hippocampal-circuit]] — 海马CA1是TCM的神经输出节点；CA3提供内容，CA2提供时间组织
- [[ca2-hippocampus]] — CA2是TCM时间情境状态的组织节点候选（Mankin 2015；MacDonald&Tonegawa 2021）
- [[entorhinal-cortex]] — MEC Layer III提供上游时间漂移信号（Diehl 2019；Vo 2021）
- [[memory-consolidation]] — TCM框架如何延伸到系统巩固中尚待确定；SWR回放是否保留时间情境结构
- [[complementary-learning-systems]] — TCM与互补学习系统（CLS）理论的关系：CLS定义了海马/皮层的结构分工，TCM定义了海马内的时间组织原则
- [[prefrontal-cortex]] — mPFC有时间细胞（Tiganj 2017）；可能是CA1时间序列的下游读出器（Q-tc-04）
- [[sharp-wave-ripples]] — SWR期间时间细胞序列压缩重放；是否保留时间顺序结构待研究（Q-tc-04相关）

## 未解问题

- **Q-tc-01**（高优先）：CA2/MEC是否构成TCM时间情境状态的神经底层？MEC→CA2→CA1的完整链路尚需整合验证；"内在时间计数"vs"任务认知序列"解释仍未分离
- **Q-tc-04**（中优先）：时间细胞序列的下游读出器是什么？mPFC时间细胞（Tiganj 2017）是候选，但CA1→mPFC直接因果传递证据缺乏；SWR如何保留时间顺序结构同样未解

## 修订历史

- 2026-08-04 · 创建 · 基于《时间细胞》文章(#103)中Howard & Eichenbaum 2013理论框架部分 · 初始状态：emerging；置信度：medium
- 2026-09-06 · 修订 rev2 · 基于《大脑的内部时间轴》(#136) · 重大扩展：补充Howard 2014数学框架（Laplace变换/泄漏积分器）；新增MEC三证据（Diehl 2019漂移细胞/Vo 2021因果损伤/Marks&Kitamura 2021颞氨通路功能分化）；新增CA2时间偏好证据（Mankin 2015）；新增mPFC时间细胞（Tiganj 2017）；证据表扩展至9行；新增Q-tc-04；related增ca2-hippocampus/prefrontal-cortex/sharp-wave-ripples；revision_count+1；状态维持emerging/medium（因果链路仍不完整）

## 来源文章

- [[2026-08-04-hippocampal-time-cells-episodic-memory]]
- [[2026-09-06-tcm-neural-basis-mec-ca2-temporal-scaffold]]

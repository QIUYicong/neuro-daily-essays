---
title: 梨状皮层（初级嗅觉皮层）
slug: piriform-cortex
domain: concepts
type: region
status: established
confidence: high
created: 2026-07-26
updated: 2026-07-26
revision_count: 1
dimensions: [cellular, synaptic, microcircuit, brain-region, cognition]
related: [olfactory-bulb, olfactory-receptor, amygdala, entorhinal-cortex, pattern-completion, hippocampal-circuit, attractor-network, memory-consolidation]
prerequisites: [olfactory-bulb, synaptic-transmission, pattern-completion]
opens_questions: [Q-piriform-topography, Q-piriform-human-subdivision, Q-piriform-td-control]
source_articles: [2026-07-26-olfactory-coding-smell-memory-limbic]
key_sources: ["PMID:19555653", "PMID:32422571", "PMID:37620443"]
---

# 梨状皮层（初级嗅觉皮层）(Piriform Cortex, PCX)

> **一句话定义**：大脑中最古老的皮层之一（仅三层），是嗅球输出的主要皮层目标，通过稀疏分布式编码（~10%激活）和类CA3的递归联想回路，把嗅球的拓扑小球激活图综合成一个与具体气味浓度相对无关、以"气味身份"为核心的分布式表征；无拓扑图，有模式补全能力。

## 当前理解

我们现在认为，梨状皮层（PCX）的编码逻辑与其他感觉皮层（视觉/听觉/体感）有根本性差异：

**特征1：稀疏编码（Sparse Coding）**
- 任意单个气味只激活约10%的梨状皮层神经元（Poo & Isaacson, 2009）
- 被激活神经元的平均放电率增加仅约2 Hz，强响应（>10 Hz增加）仅见于约6%细胞
- 原因：宽调谐的抑制性中间神经元产生全局抑制；选择性兴奋性输入（来自嗅球）激活少数特定细胞

**特征2：无拓扑图（No Topographic Map）**
- 与视觉皮层（视网膜拓扑图）、听觉皮层（频率拓扑图）、体感皮层（躯体拓扑图）不同
- 响应相似化学结构气味的梨状皮层神经元并不聚集；它们随机分布在整个梨状皮层
- 这使得梨状皮层的"读出"必须跨越宏观空间——与嗅球小球局部图相反

**特征3：递归联想网络（类CA3）**
- 主神经元（锥体细胞）之间有广泛的水平联接（excitatory associative fibers）
- 这些联接连接性均匀、弥散（与毗邻或远距离神经元的连接概率相近），跨越整个梨状皮层
- 结构上与海马CA3高度类似 → 同样具备**模式补全**（Pattern Completion）能力

**特征4：早期信号门控与浓度不变性**
- 气味中最先激活的高亲和力OR信号，经嗅球到达梨状皮层后迅速传播
- 早期兴奋触发全局反馈抑制（约50 ms后），压制后续嗅球输入
- 结果：气味身份主要由"最先到达的最强OR信号"决定，而非气味浓度的绝对值
- 即使气味浓度变化10倍，仅约100个随机神经元的响应模式即可准确分类气味身份（Bolding & Franks, 2020）

**梨状皮层分区**：
- **前梨状皮层（aPCX/前额面）**：更靠近嗅球；对单一气味成分更敏感（分析式编码）
- **后梨状皮层（pPCX/颞叶面）**：距嗅球较远；对混合气味整体更敏感（综合式编码）
- 人类的aPCX/pPCX与啮齿类ANT/POST的功能对应关系尚不明确

**在感知层级中的位置**（Sagar et al. 2023, Nature Neuroscience）：
- 梨状皮层：编码粗粒度气味类别（intensity, chemical category, ~低维感知空间）
- 杏仁核：中等精细度
- 眶额皮层（OFC）：最细粒度、最主观、高度个体化的气味感知

## 关键机制

**全局抑制机制**（Poo & Isaacson, 2009）：
1. 气味刺激触发嗅球僧帽细胞放电
2. 僧帽细胞轴突（LOT）激活梨状皮层的少数兴奋性主神经元（气味特异性）
3. **同时**：局部中间神经元接收到宽调谐的嗅球输入，产生广泛的GABA抑制
4. 抑制压制大多数主神经元，仅让最强的气味特异性兴奋性输入驱动的神经元放电
5. 净结果：从嗅球接收多重激活小球信号 → 梨状皮层产生稀疏的、气味特异性的神经元激活图

**浓度不变性机制**（Bolding & Franks, 2020）：
- 浓度增加时，更多OR被激活，嗅球输出增加
- 梨状皮层的全局反馈抑制随着兴奋增加而等比例增加（规范化机制）
- 结果：梨状皮层的激活模式（哪些神经元激活）对浓度相对不变，主要编码气味"是什么"而非"多强"

**振荡同步**：
- 气味诱发梨状皮层约15–30 Hz β振荡，与嗅球振荡同步
- 振荡中的精确峰时（spike timing）可能提供额外的编码维度

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 梨状皮层稀疏编码（~10%激活，~2 Hz增量） | 大鼠体内全细胞膜片钳；40种气味 | Poo & Isaacson 2009, PMID:19555653 | 高 |
| 全局抑制：宽调谐抑制vs选择性兴奋 | 膜片钳兴奋/抑制分离测量 | PMID:19555653 | 高 |
| ~100神经元可准确分类气味身份 | 大群体记录+线性解码 | PMID:32422571 | 中高 |
| 早期信号+全局抑制实现浓度不变性 | 多单元记录+光遗传学操控时间 | PMID:32422571 | 中高 |
| 梨状皮层在感知层级中编码低维感知（类别/强度） | 人类7T fMRI + 多维感知评分 | Sagar et al. 2023, PMID:37620443 | 中高 |
| OFC（而非梨状皮层）编码个体化精细气味感知 | 7T fMRI，个体差异分析 | PMID:37620443 | 中高 |

## 连接

- [[olfactory-bulb]] — 梨状皮层是嗅球输出（经LOT）的主要皮层目标；嗅球提供拓扑图输入，梨状皮层产生非拓扑稀疏表征
- [[olfactory-receptor]] — OR组合激活嗅球小球图 → 梨状皮层稀疏表征
- [[amygdala]] — 梨状皮层→杏仁核投射；气味与情绪/恐惧价值联结；杏仁核也直接接收嗅球输入（先于梨状皮层）
- [[entorhinal-cortex]] — 梨状皮层→内嗅皮层→海马；气味记忆的巩固和提取通路
- [[pattern-completion]] — 梨状皮层的递归联想回路与CA3类似，具备从降级或混合气味信号恢复完整气味表征的能力
- [[hippocampal-circuit]] — 梨状皮层→内嗅皮层→海马三突触回路；嗅觉记忆的长期存储
- [[attractor-network]] — 梨状皮层的递归兴奋连接可以建模为Hopfield吸引子网络

## 未解问题

- Q-piriform-topography（中优先级）：梨状皮层是否完全没有任何功能组织？还是有超出当前分辨率的微尺度拓扑结构？
- Q-piriform-human-subdivision（中优先级）：人类aPCX/pPCX的功能分工与啮齿类ANT/POST是否有可比性？人类颞叶皮层中的梨状皮层如何与其他感觉联合皮层整合？
- Q-piriform-td-control（中优先级）：OFC和PFC对梨状皮层的自上而下控制如何通过学习和期望改变气味感知？这个控制回路与预测编码框架的关系？

## 修订历史

- 2026-07-26 · 创建 · 基于《气味的神经密码：从一个分子到一段记忆的四级变换》(#94) · 初始置信度：高

## 来源文章

- [[2026-07-26-olfactory-coding-smell-memory-limbic]]

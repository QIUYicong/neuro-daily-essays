---
title: 梨状皮层（初级嗅觉皮层）
slug: piriform-cortex
domain: concepts
type: region
status: established
confidence: high
created: 2026-07-26
updated: 2026-10-04
revision_count: 2
dimensions: [cellular, synaptic, microcircuit, brain-region, cognition]
related: [olfactory-bulb, olfactory-receptor, amygdala, entorhinal-cortex, pattern-completion, hippocampal-circuit, attractor-network, memory-consolidation, predictive-coding, active-inference]
prerequisites: [olfactory-bulb, synaptic-transmission, pattern-completion]
opens_questions: [Q-piriform-topography, Q-piriform-human-subdivision, Q-piriform-td-control, Q-pc-olfaction-01, Q-pc-olfaction-03]
source_articles: [2026-07-26-olfactory-coding-smell-memory-limbic, 2026-10-04-predictive-coding-olfactory-piriform-feedback]
key_sources: ["PMID:19555653", "PMID:32422571", "PMID:37620443", "PMID:40345946", "PMID:27927961", "PMID:32662420"]
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

**特征5：梨状皮层作为预测性处理器（Lyons & Gottfried 2025）**

梨状皮层不是被动的感觉接收站，而是**主动生成嗅觉预测**并通过反馈回路抑制"已预期"信号的预测处理器（Lyons & Gottfried 2025, PMID:40345946）：

- **PCx→OB 预测反馈**：梨状皮层锥体细胞轴突侧支→嗅球颗粒细胞（兴奋性，谷氨酸能）→嗅球僧帽细胞（抑制性，GABA能）。这一解剖学回路的功能解读：梨状皮层将其对当前气味的"预测"传至嗅球，压制僧帽细胞中与预测匹配的信号；与预测不符的气味信息（预测误差）以强信号进入皮层，驱动感知更新
- **嗅觉认知地图**：梨状皮层不仅表征单一气味，还编码气味与其他感觉模态（视觉、空间位置）的联合分布，构成"嗅觉认知地图"，支持跨模态预测（如看到咖啡杯→预激活咖啡气味表征）
- **鼻呼吸作为主动推断**：Zelano et al.（2016, PMID:27927961）证明鼻呼吸将梨状皮层振荡锁定于吸气-呼气周期；口呼吸时效应消失。主动吸气（sniffing）不仅传输气味分子，还为预测-误差循环提供时间基准
- **与 OFC/PFC 的自上而下控制**：OFC 和 PFC 通过梨状皮层→OFC 正向投射（以及 OFC→PCx 反馈）调节梨状皮层的增益和预测权重，使气味感知受期望、学习历史和情绪状态调制——这是 Q-piriform-td-control 的核心回答（见下）

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
| PCx→OB反馈回路（预测性压制）解剖学确认 | 跨物种示踪剂解剖；功能模型综述 | Lyons & Gottfried 2025, PMID:40345946 | 中高（解剖确立；功能预测角色为模型解读） |
| 鼻呼吸将梨状皮层振荡锁定吸气相；口呼吸时效应消失 | 人类颅内电极 + 鼻/口呼吸任务对照 | Zelano et al. 2016, PMID:27927961 | 高（直接人类测量）|
| 递归联想回路维持跨脑状态气味表征稳健性 | TeLC阻断 + 群体记录 + 解码 | Bolding et al. 2020, PMID:32662420 | 高（直接因果操控）|

## 连接

- [[olfactory-bulb]] — 梨状皮层是嗅球输出（经LOT）的主要皮层目标；嗅球提供拓扑图输入，梨状皮层产生非拓扑稀疏表征
- [[olfactory-receptor]] — OR组合激活嗅球小球图 → 梨状皮层稀疏表征
- [[amygdala]] — 梨状皮层→杏仁核投射；气味与情绪/恐惧价值联结；杏仁核也直接接收嗅球输入（先于梨状皮层）
- [[entorhinal-cortex]] — 梨状皮层→内嗅皮层→海马；气味记忆的巩固和提取通路
- [[pattern-completion]] — 梨状皮层的递归联想回路与CA3类似，具备从降级或混合气味信号恢复完整气味表征的能力
- [[hippocampal-circuit]] — 梨状皮层→内嗅皮层→海马三突触回路；嗅觉记忆的长期存储
- [[attractor-network]] — 梨状皮层的递归兴奋连接可以建模为Hopfield吸引子网络
- [[predictive-coding]] — 梨状皮层是嗅觉域的预测处理器：PCx→OB反馈回路（预测压制）+ 鼻呼吸主动推断 + 递归回路维持预测稳健性（Lyons & Gottfried 2025）；**Q-piriform-td-control 得到部分解答**
- [[active-inference]] — 鼻呼吸（sniffing）作为主动推断行为：大脑通过主动采样（吸气动作）最小化气味感知的不确定性；Zelano et al. 2016 是嗅觉主动推断的直接证据

## 未解问题

- Q-piriform-topography（中优先级）：梨状皮层是否完全没有任何功能组织？还是有超出当前分辨率的微尺度拓扑结构？
- Q-piriform-human-subdivision（中优先级）：人类aPCX/pPCX的功能分工与啮齿类ANT/POST是否有可比性？人类颞叶皮层中的梨状皮层如何与其他感觉联合皮层整合？
- Q-piriform-td-control（**2026-10-04 部分解答**）：OFC和PFC对梨状皮层的自上而下控制如何通过学习和期望改变气味感知？这个控制回路与预测编码框架的关系？**→ 部分回答**：Lyons & Gottfried 2025 将该回路纳入预测编码框架——梨状皮层通过PCx→OB反馈实现预测压制，OFC/PFC通过分层调节梨状皮层增益修改预测权重；但PCx→OB反馈的直接功能因果证据（光遗传学操控）尚缺（新问题 Q-pc-olfaction-01）
- Q-pc-olfaction-01（中优先级，新增 2026-10-04）：用光遗传学特异性沉默梨状皮层→嗅球颗粒细胞反馈纤维，气味辨别能力是否真的下降？反馈强度在气味学习期间是否增加？
- Q-pc-olfaction-03（中优先级，新增 2026-10-04）：梨状皮层"嗅觉认知地图"（气味-空间、气味-视觉联合表征）在人类层面的精细组织原则？7T fMRI 能否在人类 aPCX/pPCX 中分辨跨模态联合预测表征？

## 修订历史

- 2026-07-26 · 创建 · 基于《气味的神经密码：从一个分子到一段记忆的四级变换》(#94) · 初始置信度：高
- 2026-10-04 · 修订 rev2 · 基于《大脑的嗅觉预言》(#164) · 新增"特征5：梨状皮层作为预测性处理器"段落（PCx→OB反馈回路、嗅觉认知地图、鼻呼吸主动推断、OFC/PFC自上而下控制）；新增3行关键证据（Lyons & Gottfried 2025, Zelano et al. 2016, Bolding et al. 2020）；related 新增 predictive-coding、active-inference；连接新增 predictive-coding、active-inference；Q-piriform-td-control 部分解答；新增未解问题 Q-pc-olfaction-01、Q-pc-olfaction-03；key_sources 新增 PMID:40345946、PMID:27927961、PMID:32662420

## 来源文章

- [[2026-07-26-olfactory-coding-smell-memory-limbic]]
- [[2026-10-04-predictive-coding-olfactory-piriform-feedback]]

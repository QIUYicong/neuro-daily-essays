# 研究笔记：2026-06-15

**主题**：预测编码（Predictive Coding / Predictive Processing）  
**核心来源**：8 篇论文（7 篇开放全文 / 1 篇摘要）  
**检索策略**：PubMed E-utilities + Europe PMC，搜索词："predictive coding visual cortex review"、"Rao Ballard 1999"、"Bastos canonical microcircuits"、"Keller Mrsic-Flogel predictive processing"、"Clark 2013 whatever next"、"free energy principle Friston"、"dopamine prediction error review"

---

## 来源 1：Rao & Ballard 1999 (PMID:10195184)

**论文**：Predictive coding in the visual cortex: a functional interpretation of some extra-classical receptive-field effects  
**来源**：*Nature Neuroscience*, 1999  
**全文**：开放获取（PMC）

**要解决的问题**：V1 神经元的非经典感受野效应（环绕抑制、末端停止）如何从简单的前馈模型生成？反馈连接的功能是什么？

**核心方法**：构建两层层级网络，基于自然图像训练，反馈连接携带预测，前馈连接携带残差误差

**关键发现**：
- 层级网络自发涌现了简单细胞感受野（Gabor 形状）
- 误差单元自发展示出末端停止和非经典环绕效应
- 这些效应是有效编码自然图像统计的自然结果，无需专门设计

**改变了什么理解**：将非经典感受野效应从"感觉奇异现象"重新定义为"高效编码的计算预测"

**证据强度**：计算模型 + 自然图像数据拟合；缺乏直接神经元标记实验，但预测与经验数据高度吻合

**局限**：模型是两层简化，真实皮层层级更复杂；未解决具体神经元类型的对应

---

## 来源 2：Bastos et al. 2012 (PMID:23177956)

**论文**：Canonical microcircuits for predictive coding  
**来源**：*Neuron*, 2012  
**全文**：开放获取（PMC3777738）

**要解决的问题**：预测编码的抽象计算框架如何映射到皮层柱的具体解剖结构？

**核心方法**：理论综合 + 文献回顾（结合皮层柱解剖、振荡记录、层级连接解剖学）

**关键发现**：
- 浅层（L2/3）锥体细胞 ↔ 误差单元，投射前馈，γ 振荡主导
- 深层（L5/6）锥体细胞 ↔ 表征/预测单元，投射反馈，α/β 振荡主导
- 这一对应与多项灵长类 LFP 记录数据一致

**改变了什么理解**：将预测编码从纯理论框架转化为有具体解剖预测的神经科学理论

**证据强度**：高——振荡频段的前馈/反馈不对称有多项独立电生理实验支持

**局限**：振荡到计算角色的映射仍有争议（2026 年 Westerberg 等提出反例），层内细胞类型的精确对应需要更直接的标记实验

---

## 来源 3：Keller et al. 2012 (PMID:22681686)

**论文**：Sensorimotor mismatch signals in primary visual cortex of the behaving mouse  
**来源**：*Neuron*, 2012  
**全文**：摘要（PMC 完整版本未独立确认）

**要解决的问题**：V1 是否不只处理视觉输入，还编码视觉与运动的一致性？

**核心方法**：清醒小鼠 + 虚拟现实跑步机 + 双光子钙成像（L2/3）；操控视觉流动与运动速度的耦合状态

**关键发现**：
- 正常耦合状态（预期确认）：V1 L2/3 对视觉刺激响应相对低
- 失配条件（运动持续但视觉流停止）：L2/3 产生强烈短暂激活
- 失配响应超出单纯视觉停止的效应，说明运动预测信号影响了 V1

**改变了什么理解**：V1 不是照相机，而是整合运动预测与视觉输入的误差检测器；提供了预测编码在 V1 的直接体内行为实验证据

**证据强度**：中-高；行为+影像的体内实验，但失配响应的神经来源（来自运动皮层反馈 vs. 高级视觉区域 vs. 神经调质）尚未完全分离

---

## 来源 4：Keller & Mrsic-Flogel 2018 (PMID:30359606)

**论文**：Predictive Processing: A Canonical Cortical Computation  
**来源**：*Neuron*, 2018  
**全文**：开放获取（PMC）

**要解决的问题**：如何从实验检验角度设计能区分预测处理与其他皮层计算模型的关键实验？

**核心内容**：
- 框架预测处理是皮层的"典范计算"（canonical cortical computation）
- 提出三类可测试的预测：情境依赖响应、失配信号、反馈塑造前馈
- 讨论健康和病理状态的预测处理含义

**改变了什么理解**：将预测编码从理论/回顾性解释提升为产生具体可验证预测的框架

**证据强度**：综述性，无新实验数据；但整合了多项体内实验结果（包括作者自己的 2012 失配实验）

---

## 来源 5：Clark 2013 (PMID:23663408)

**论文**：Whatever next? Predictive brains, situated agents, and the future of cognitive science  
**来源**：*Behavioral and Brain Sciences*, 2013  
**全文**：开放获取（PMC10800426）

**要解决的问题**：如何用统一的预测误差最小化框架解释感知、行动、注意和学习？

**核心贡献**：
- "主动推断"（Active Inference）：行动与感知都在最小化预测误差
- 精度加权 = 注意的计算定义
- 层级预测处理作为认知科学的统一框架

**改变了什么理解**：将纯感知理论扩展为覆盖行动、注意和具身认知的统一框架

**证据强度**：理论综合；无新实验数据；影响极大（被大量引用）

**局限**：理论过于宽泛，被批评者认为可解释一切 = 排除一切的风险（Karl Popper 的可证伪性问题）

---

## 来源 6：Shipp 2016 (PMID:27917138)

**论文**：Neural Elements for Predictive Coding  
**来源**：*Frontiers in Psychology*, 2016  
**全文**：开放获取（PMC5114244）

**核心贡献**：详细分析皮层层级中误差单元和表征单元的候选神经元类型；讨论中间神经元（特别是 VIP 细胞）在精度调节中的可能作用；将前馈 Gabor 滤波器与反馈轮廓完形（contour integration）联系

---

## 来源 7：Shipp 2023 (PMID:38259953)

**论文**：Computational components of visual predictive coding circuitry  
**来源**：*Frontiers in Neural Circuits*, 2023  
**全文**：开放获取（Frontiers）

**核心贡献**：最新综述，整合了小鼠和猴的视觉皮层数据；提出三类功能神经元：预测生成器（L5 锥体细胞）、误差信号生成器（L2/3 锥体细胞）、精度/增益控制抑制性中间神经元；提出可测试的细胞类型级别预测

---

## 来源 8：Friston 2010 (PMID:20068583)

**论文**：The free-energy principle: a unified brain theory?  
**来源**：*Nature Reviews Neuroscience*, 2010  
**全文**：开放获取（PMC）

**核心贡献**：将预测编码置于"自由能最小化"的统一数学框架；提出贝叶斯脑假说；将感知、行动、学习全部纳入一个原理；对 Helmholtz 无意识推断的现代数学实现

**注意**：此论文使用高度抽象的变分贝叶斯数学，可证伪性问题仍有争议

---

## 来源 9（支撑）：Diederen & Fletcher 2021 (PMID:32338128)

**论文**：Dopamine, Prediction Error and Beyond  
**来源**：*The Neuroscientist*, 2021  
**全文**：开放获取（PMC7804370）

**核心贡献**：将多巴胺 RPE 信号与预测编码框架整合；讨论 DA 误差信号在精神分裂症（aberrant salience）、抑郁症、成瘾中的失调模式

---

## 来源 10（争议）：Westerberg et al. 2026 (PMID:41120233)

**论文**：Hierarchical interactions between sensory cortices defy predictive coding  
**来源**：*Trends in Cognitive Sciences*, 2026  
**全文**：摘要（最新文献，未获取全文，标注限制）

**核心主张**：来自视觉联合皮层的新数据显示，感觉皮层之间的层级交互不符合简单预测编码模型中 γ = 前馈误差、α/β = 反馈预测的对应

**局限说明**：本文只读了摘要；结论可能比标题更细微（"defy"不一定意味着完全否定，可能是针对特定版本的预测编码）

---

## 选题反思

预测编码既是支撑整个课程脊柱（意识与自我、感知、学习、神经调质、AI 比较）的统一框架，也是当前神经科学理论中最受关注也最有争议的理论之一。今天的文章在建立了多个具体主题（V1、DA、ACh/NE、振荡）之后引入这一框架，时机恰当——读者有足够背景来理解各个联结。

主要局限：Keller 2012 的 PMC 全文未独立确认，使用时标注为摘要。Westerberg 2026 的反驳文献只有摘要，引用时明确标注限制。

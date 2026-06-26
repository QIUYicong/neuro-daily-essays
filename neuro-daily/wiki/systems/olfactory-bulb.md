---
title: 嗅球（主嗅觉球）
slug: olfactory-bulb
domain: systems
type: region
status: established
confidence: high
created: 2026-07-26
updated: 2026-10-04
revision_count: 2
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region]
related: [olfactory-receptor, piriform-cortex, amygdala, entorhinal-cortex, gamma-oscillations, lateral-inhibition, predictive-coding, active-inference]
prerequisites: [olfactory-receptor, action-potential, synaptic-transmission]
opens_questions: [Q-ob-human-organization, Q-ob-topography-logic]
source_articles: [2026-07-26-olfactory-coding-smell-memory-limbic, 2026-10-04-predictive-coding-olfactory-piriform-feedback]
key_sources: ["PMID:32166167", "PMID:19555653", "PMID:32278646", "PMID:40345946"]
---

# 嗅球（主嗅觉球）(Olfactory Bulb, OB)

> **一句话定义**：大脑最前端的嗅觉初级处理站，通过"一受体一小球"规则将分散的嗅觉感觉神经元轴突汇聚成拓扑图，再经僧帽/簇状细胞-颗粒细胞的抑制性回路对气味模式进行侧向抑制和对比度增强，输出信号直接（无视丘中继）投射到梨状皮层、杏仁核和内嗅皮层。

## 当前理解

我们现在认为，嗅球是将化学感觉多样性映射为神经活动的第一级中继站，其核心特征是：

**1. 小球层（Glomerular layer）——一受体一小球规则**
- 人类约含5500–10000个小球；小鼠约1800个
- 表达同一OR的所有OSN（可在嗅觉上皮散布分布）精确汇聚到同一个小球
- 每个小球接收约2500个OSN输入，对应一种OR的调谐特性
- 结果：嗅球形成一张"受体激活拓扑图"——每个小球代表一种OR，并对应气味化学空间的一个维度

**2. 僧帽细胞和簇状细胞——主要输出神经元**
- 两种输出神经元；簇状细胞（tufted cells）对嗅球内更近端的突触更敏感，响应较快
- 僧帽细胞（mitral cells）树突深入单一小球，接收来自对应OSN的兴奋性信号
- 轴突经外侧嗅束（LOT）直接投射到梨状皮层、前嗅核、杏仁核皮质内侧核、嗅结节、内嗅皮层

**3. 颗粒细胞——侧向抑制执行者**
- 无轴突的抑制性中间神经元（GABAergic）
- 通过**树突-树突双向突触**（dendrodendritic reciprocal synapse）与僧帽细胞相互作用：
  - 僧帽细胞激活颗粒细胞（谷氨酸→颗粒细胞树突）
  - 颗粒细胞反馈抑制僧帽细胞（GABA→僧帽细胞树突）
- 这个设计允许一侧小球激活的僧帽细胞通过颗粒细胞抑制相邻小球的僧帽细胞——侧向抑制
- 功能：增强气味模式的对比度，类似视网膜的中心-周围抑制

**4. 周小球细胞（Periglomerular cells, PG cells）**
- 位于小球外层，GABA能（部分也释放多巴胺）
- 在小球间实现短程侧向抑制
- 受自上而下的调制信号调控（如乙酰胆碱、去甲肾上腺素）

**5. γ/β振荡**
- 气味刺激时嗅球产生~15–30 Hz β振荡（或称"低γ"）；有时40–100 Hz γ
- 由兴奋性-抑制性（僧帽细胞-颗粒细胞）动力学产生
- 与梨状皮层振荡同步，可能参与气味辨别的时序编码（spike timing coding）

**嗅球的特殊地位**：嗅球输出**不经过视丘**，直接到达嗅觉皮层和边缘系统——这在所有感觉系统中独一无二。

**6. 梨状皮层→嗅球反馈（自上而下预测）**
- 梨状皮层锥体细胞轴突侧支向嗅球回送**兴奋性反馈**（谷氨酸能），主要靶向颗粒细胞（也部分靶向PG细胞）
- 颗粒细胞接受梨状皮层兴奋后，通过树突-树突双向突触**抑制僧帽细胞**（GABA能）
- 功能角色（预测编码框架，Lyons & Gottfried 2025, PMID:40345946）：梨状皮层将其对当前气味的"预测"通过此回路传至嗅球，压制与预测匹配的僧帽细胞信号；与预测不符的气味成分以强信号进入皮层（"预测误差"）
- 即：颗粒细胞不仅执行嗅球内侧向抑制（对比度增强），还执行**来自皮层的自上而下预测性抑制**——两种功能共用同一解剖结构

## 关键机制

**从OSN到小球输入**：
- OSN轴突穿过筛板到达嗅球
- 在小球层与僧帽细胞近端树突、簇状细胞树突形成突触（谷氨酸能）
- 一个小球内约有20–50个僧帽/簇状细胞分叉树突（来自不同细胞）

**侧向抑制放大**：
1. 气味A强烈激活小球X（OR_x偏好A）
2. 小球X的僧帽细胞放电 → 激活颗粒细胞
3. 颗粒细胞通过树突-树突突触抑制小球Y（相邻OR的僧帽细胞）
4. 结果：小球X的信号相对增强，小球Y的信号相对减弱 → 气味A的小球激活图更清晰

**注意调制**：来自前脑的胆碱能（乙酰胆碱）、去甲肾上腺素等调质投射到嗅球，通过修改中间神经元兴奋性改变嗅球对气味的增益（注意力依赖的嗅觉灵敏度变化）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 一受体一小球规则（OR-GFP追踪） | 转基因小鼠轴突标记；两类小球/两类OR分开聚集 | PMID:32166167 | 高 |
| 颗粒细胞-僧帽细胞树突-树突双向突触 | 电子显微镜超微结构；双向电生理 | 经典Shepherd 1970s工作 | 高 |
| 嗅球β振荡与气味辨别相关 | 局部场电位；电生理相关实验 | PMID:19555653 | 中高 |
| 嗅球输出直接到达杏仁核（无视丘中继） | 示踪剂解剖；功能神经影像 | PMID:32278646 | 高 |
| 人类嗅球结构与啮齿类有显著差异 | 人类死后解剖；MRI | PMID:32278646 | 高 |

## 连接

- [[olfactory-receptor]] — OSN轴突（每种OR一条通道）汇聚至同一小球；OR是嗅球小球图的基础
- [[piriform-cortex]] — 僧帽/簇状细胞经外侧嗅束直接投射；梨状皮层是主要皮层目标
- [[amygdala]] — 僧帽细胞直接投射到杏仁核皮质内侧核（无视丘中继）→ 气味触发直接情绪反应
- [[entorhinal-cortex]] — 嗅球→内嗅皮层（LEC）→海马：Proust效应的解剖基础
- [[gamma-oscillations]] — 嗅球产生β/γ振荡；其机制与皮层γ振荡（PING）类似但有独特的树突-树突回路特征
- [[predictive-coding]] — 嗅球颗粒细胞是预测编码框架中的"误差单元"：接收梨状皮层预测反馈并以GABA能抑制压制已预期的僧帽细胞信号；僧帽细胞残余放电 = 预测误差信号
- [[active-inference]] — 嗅球的呼吸相位锁定振荡（Zelano et al. 2016）为主动推断的时间采样窗口提供神经基础

## 未解问题

- Q-ob-human-organization（低优先级）：人类嗅球的不规则小球分布是否改变了"一受体一小球"规则的严格性？
- Q-ob-topography-logic（中优先级）：嗅球小球的拓扑图（化学感觉的几何邻近性）对应什么编码原则？是否有"化学空间-物理空间"映射的规律性？

## 修订历史

- 2026-07-26 · 创建 · 基于《气味的神经密码：从一个分子到一段记忆的四级变换》(#94) · 初始置信度：高
- 2026-10-04 · 修订 rev2 · 基于《大脑的嗅觉预言》(#164) · 新增"6. 梨状皮层→嗅球反馈（自上而下预测）"段落，补充颗粒细胞作为预测编码误差单元的角色（Lyons & Gottfried 2025, PMID:40345946）；related 新增 predictive-coding、active-inference；connections 新增预测编码和主动推断链接；key_sources 新增 PMID:40345946

## 来源文章

- [[2026-07-26-olfactory-coding-smell-memory-limbic]]
- [[2026-10-04-predictive-coding-olfactory-piriform-feedback]]

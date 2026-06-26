---
title: 预测编码
slug: predictive-coding
domain: theories
type: theory
status: mainstream
confidence: medium
created: 2026-06-15
updated: 2026-10-04
revision_count: 11
dimensions: [molecular, synaptic, microcircuit, brain-region, whole-brain-network, behavior, cognition, AI]
related: [precision-weighting, v1-primary-visual-cortex, orientation-selectivity, dopamine-reward-prediction-error, gain-control, working-memory, theta-oscillations, active-inference, default-mode-network, global-workspace-theory, world-model, language-network, ventral-language-stream, cerebellum, forward-model, free-energy-principle, variational-autoencoder, cortical-canonical-microcircuit, cortical-layers, beta-oscillations, intrinsic-neural-timescale, temporal-receptive-window, piriform-cortex, olfactory-bulb, gamma-oscillations]
prerequisites: [action-potential, synaptic-transmission, ltp, nmda-receptor, dopamine-reward-prediction-error]
opens_questions: [Q-pc-01, Q-pc-02, Q-pc-03, Q-pc-04, Q-pc-05, Q-pc-06, Q-pc-07, Q-pc-08, Q-pc-09, Q-pc-olfaction-01, Q-pc-olfaction-02, Q-pc-olfaction-03]
source_articles: [2026-06-15-predictive-coding, 2026-06-16-default-mode-network, 2026-05-31-week4-synthesis, 2026-07-13-predictive-coding-free-energy-vae, 2026-07-19-beta-oscillations-cortical-prediction, 2026-09-14-v1-laminar-prediction-error-evidence, 2026-10-04-predictive-coding-olfactory-piriform-feedback]
key_sources: ["PMID:10195184", "PMID:23177956", "PMID:22681686", "PMID:30359606", "PMID:23663408", "PMID:27917138", "PMID:38259953", "PMID:20068583", "PMID:28333583", "PMID:33683317", "PMID:19528002", "PMID:25556836", "PMID:29339471", "PMID:36864133", "PMID:38697110", "PMID:40345946", "PMID:27927961", "PMID:32662420"]
---

# 预测编码 (Predictive Coding / Predictive Processing)

> **一句话定义**：皮层层级持续生成对感觉输入的自上而下预测，只将"实际输入 − 预测"的差值（预测误差）沿前馈方向向上传递；感知是推断世界状态的过程，而非被动复制感觉信号的过程。

## 当前理解

我们现在认为，视觉皮层的反馈连接（数量约是前馈连接 10 倍）不是修饰性的，而是计算的核心组成：它们携带高级区域对低级区域的**预测**，而前馈连接携带**预测误差**（实际输入与预测之差）。这与经典前馈感知模型正好相反。

Rao & Ballard（1999, PMID:10195184）的奠基性计算模型显示，在这样的层级网络中：
- 每级区域维护对输入的"当前最优估计"（表征单元，representation units）
- 预测误差（误差单元，error units）被向上传递，驱动更高层级更新其估计
- 仅传递误差（而非原始信号）是在统计结构化的自然图像上的高效编码策略

**主动推断（Active Inference）**：Clark（2013, PMID:23663408）和 Friston（2010, PMID:20068583）进一步提出，行动也是预测误差最小化的一种方式——运动不是"执行命令"，而是"实现本体感觉预测"。感知和行动共享一个计算原理：最小化预测误差（或其数学近似：自由能）。

**精度加权（Precision Weighting）**：预测误差信号不是均等重要的，其影响信念更新的程度取决于精度（可信度/1/方差）权重。注意力在计算上被定义为选择性地提升任务相关误差信号的精度，神经调质（ACh、NE）是在神经回路层面实现这一精度调节的分子机器。

## 关键机制

### 层级推断结构

在皮层层级中（以视觉为例：LGN → V1 → V2 → V4 → IT）：

```
高级区域 ←─误差信号（前馈）─── 低级区域
         ───预测信号（反馈）──→
```

每级区域做的是：
1. 接受来自高级区域的预测（反馈）
2. 与实际接收的输入（来自低级区域）比较
3. 计算预测误差，向上传递
4. 更新本层的当前估计

### 皮层层级的解剖学实现（Bastos et al. 2012, PMID:23177956）

| 皮层层 | 功能角色 | 投射方向 | 振荡频段 |
|--------|---------|---------|---------|
| L2/3（浅层） | 误差单元 | 前馈（到上级 L4） | **γ（30-80 Hz）** |
| L4 | 接受前馈输入 + 接受上级反馈预测 | — | — |
| L5/6（深层） | 表征/预测单元 | 反馈（到下级 L1/6） | **α/β（8-20 Hz）** |

振荡频段的功能分工：
- **γ 振荡**：前馈误差信号的载波；灵长类视觉皮层前馈方向以 γ 为主
- **α/β 振荡**：反馈预测信号的载波；灵长类视觉皮层反馈方向以 α/β 为主

### 精度加权与注意

每个误差信号 ε 被精度因子 π 加权：**有效误差 = π × ε**

精度 π 越高，该误差对更新的影响越大。注意力 = 提升特定感觉通道的 π，等效于选择性放大该通道对内部模型的更新能力。

**分子机制候选**（Shipp 2016, PMID:27917138; 2023, PMID:38259953）：
- VIP 中间神经元通过去抑制回路增加目标神经元的增益（精度↑）
- NMDA 受体的激活程度调节突触传递增益
- ACh（M1 受体）直接放大 V1 中注意相关刺激的响应增益（见 Herrero et al. 2008）

### 主动推断（Active Inference）

运动控制在主动推断框架中被理解为：
1. 运动皮层生成本体感觉的预测（"手应在位置 X"）
2. 脊髓反射弧执行使实际本体感觉匹配预测的肌肉命令
3. 感知与行动共享"最小化预测误差"的目标

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 预测编码框架复现 V1 非经典感受野效应（末端停止、环绕抑制） | 层级网络 + 自然图像训练；计算预测与已知神经数据对比 | PMID:10195184 | 高（计算模型）|
| 皮层前馈方向 γ 主导，反馈方向 α/β 主导 | 灵长类多脑区 MEG/LFP 记录；层级连接解剖与振荡记录对比 | PMID:23177956 | 高（多项独立研究）|
| 28 对灵长类视觉区域：前向 γ（60–80 Hz），后向 β（14–18 Hz），跨区域高度一致 | Granger 因果分析 + 独立解剖层级确认（灵长类多电极 LFP） | PMID:25556836 | 高（系统性多区域）|
| 前额叶层流：L5/6 深层 α/β 调控 L2/3 浅层 γ 爆发；在 WM 任务中验证感觉皮层频率层级规律 | 猕猴 PFC 层流电极；相位-功率耦合分析 | PMID:29339471 | 高（层流电极直接分辨）|
| 小鼠 V1 L2/3 在感觉运动失配时强烈激活（预测误差响应） | 清醒小鼠 + VR + 双光子钙成像；操控运动-视觉耦合状态 | PMID:22681686 | 高（体内行为实验）|
| 注意可被理解为精度加权（ACh 实现 V1 精度调制） | 猕猴 V1 + M1 受体阻断 + 注意任务（Herrero et al. 2008） | PMID:27917138；PMID:30359606 综述 | 高（体内药理+电生理）|
| 某些感觉皮层间交互不符合简单振荡-方向映射预测 | 灵长类视觉联合皮层新数据（仅读摘要） | PMID:41120233 | 待评估（限于摘要）|
| 局部赫布学习规则的预测编码网络在特定条件下收敛于反向传播 | 数学证明 + 计算仿真；误差节点活动趋近零时权重更新等价于梯度下降 | PMID:28333583（PMC开放） | 高（数学定理，但生物条件苛刻）|
| 人腹侧视觉流对预期刺激有系统性抑制（BOLD 降低） | 人类 fMRI + 重复抑制范式；V1→IT 全通路检测 | PMID:30030402 | 中（存在神经适应混淆）|
| 现有视觉皮层预测误差证据有限，多与神经适应不可区分 | 批判性综述；猕猴和人类电生理重新分析 | PMID:33683317 | 高（批评性证据，降低其他证据置信度）|
| **人类 V1 深层（L5/6）编码预期表征，浅层（L2/3）专门在非预期刺激时激活（预测误差）** | 7T fMRI 层级多变量解码；75% 预期 vs 25% 非预期 Gabor 朝向；活体人脑 | PMID:38697110（Thomas et al. 2024，Current Biol）| **中-高**（层级 fMRI 直接分辨；全文待确认）|
| 预测编码自由能最小化与 VAE 的 ELBO 优化数学等价 | 理论分析；比较 Friston 自由能方程与 Kingma-Welling ELBO 方程 | PMID:20068583；arXiv:1312.6114 | 高（数学等价，已形成共识）|

### 小脑：专用预测误差学习系统

小脑是大脑中实现预测编码最具体、最古老的子系统（Wolpert et al. 1998, PMID:21227230）：
- **前向模型**：利用传出拷贝（efference copy）预测运动感觉后果 → 与实际感觉（攀爬纤维）对比 → 预测误差
- **可塑性更新**：误差驱动 PF-LTD/LTP，更新内部模型（浦肯野细胞突触权重）
- 预测编码原理在小脑的实现早于皮层预测编码理论的提出，是同一计算原则在进化上的较古老版本

小脑的预测编码是**局部的、运动-感觉专用的**；皮层的预测编码是**层级的、多模态的**。两者可能共享"预测 → 误差 → 更新"这一核心循环。

### 嗅觉系统：预测编码的进化实验室

嗅觉系统（嗅球 + 梨状皮层）提供了预测编码在进化上最古老的皮层实现案例，且具备独特的实验优势（Lyons & Gottfried 2025, PMID:40345946）：

**PCx→OB 反馈回路**：梨状皮层锥体细胞将轴突侧支回送嗅球颗粒细胞（谷氨酸能），颗粒细胞再通过树突-树突双向突触抑制嗅球僧帽细胞（GABA能）。这条回路的功能解读完全符合预测编码框架：
- 梨状皮层 = 高层"表征单元"（生成对当前气味的预测）
- 嗅球颗粒细胞 = "误差单元"（将预测与传入OR激活比较）
- 嗅球僧帽细胞被压制 = 已预期信号被抑制；超预期部分以强信号进入皮层 = 预测误差上行

**与视觉/语言系统的关键类比**：

| 特征 | 视觉（V1↔LGN） | 嗅觉（PCx↔OB） | 语言（颞叶↔额叶）|
|------|--------------|--------------|----------------|
| 反馈通路 | V1深层→LGN | PCx锥体细胞→OB颗粒细胞 | 额叶Broca区→颞叶STG |
| 中间误差层 | LGN中继/V1L2/3 | OB颗粒细胞（GABA能） | 颞叶预测误差区 |
| 预测内容 | 视觉边缘/方向/运动 | 气味身份/化学结构 | 词义/句法结构 |
| 振荡载体 | γ（误差前馈）/β（预测反馈）| β/γ（嗅觉刺激相关）| γ（词级预测误差）|

**嗅觉系统的独特优势**：反馈回路仅需一步（PCx→OB），解剖极为简洁；刺激可以高精度控制；可在清醒动物中进行光遗传学精确操控（OB颗粒细胞可选择性靶向）。这使嗅觉系统成为检验预测编码具体回路假设的理想实验对象。

**鼻呼吸作为主动推断**：Zelano et al.（2016, PMID:27927961）的人类颅内电极研究证明鼻呼吸将梨状皮层、杏仁核、海马振荡锁定于吸气-呼气周期，口呼吸时效应消失。主动吸气（sniffing）不仅增加气味分子传入，还为预测-误差循环提供精确的时间基准——这正是"主动推断（active inference）"框架中的关键行为：通过主动采样降低感觉预测不确定性。

## 连接

- [[cortical-canonical-microcircuit]] — 规范微回路是预测编码的解剖实现载体：L2/3=误差单元（前馈，γ），L5/6=预测单元（反馈，β），L4=丘脑感觉输入汇聚点，L1=反馈预测接收区
- [[cortical-layers]] — 六层解剖学骨架：每层的细胞类型、输入/输出投射和振荡特征
- [[beta-oscillations]] — β 振荡是预测编码反馈通路的频率实现（14–18 Hz 后向信号，L5/6 深层起源）；γ 爆发是前馈误差信号的频率实现（L2/3 浅层起源）；二者的层级分工是误差单元（浅层γ）与表征单元（深层β）的振荡表达
- [[cerebellum]] — 专用预测误差学习系统（前向模型 + 攀爬纤维误差信号）
- [[forward-model]] — 小脑前向模型是预测编码的一个具身子系统
- [[precision-weighting]] — 预测编码框架中注意力和神经调质的计算角色
- [[v1-primary-visual-cortex]] — 预测编码在视觉系统中最被研究的具体实例
- [[orientation-selectivity]] — 方向选择性作为高效预测编码自然涌现的结果
- [[dopamine-reward-prediction-error]] — 多巴胺 RPE = 奖励域中预测误差信号的神经实现（同一计算原理）
- [[gain-control]] — 增益控制是精度加权的低层级实现机制
- [[working-memory]] — 工作记忆可被理解为主动维护预测模板（先验）
- [[theta-oscillations]] — θ 振荡可能是序列预测（时间上的预测编码）的载波
- [[ltp]] — LTP/LTD 是预测误差驱动的突触层面权重更新
- [[global-workspace-theory]] — GWT 与预测编码互补：足够大的预测误差（无法被局部层级消解）可能是触发全局工作空间点燃的候选机制；意识 = 大脑在无法预测时召唤全局计算资源
- [[language-network]] — 语言理解是预测编码在词汇层面的实例化：额叶（Broca区）在词出现前200ms生成语义-感觉运动预测，颞叶返回预测误差，构成词级预测-更新循环（Grisoni 2024, PMC10957213）
- [[ventral-language-stream]] — 腹侧语言流的具身语义预测（工具词→运动皮层预激活；动物词→视觉皮层预激活）是预测编码具身性的直接神经证据
- [[piriform-cortex]] — 梨状皮层通过PCx→OB反馈回路（PCx锥体细胞→OB颗粒细胞→抑制OB僧帽细胞）实现嗅觉域的预测压制；梨状皮层是嗅觉预测编码的"高层表征单元"；其递归联想网络（Bolding et al. 2020）维持跨脑状态气味表征稳健性（Lyons & Gottfried 2025, PMID:40345946）
- [[olfactory-bulb]] — 嗅球颗粒细胞在预测编码框架中扮演"误差单元"角色，接收梨状皮层预测反馈并抑制僧帽细胞；僧帽细胞放电强度 = 超出预测的气味成分（预测误差前馈信号）
- [[gamma-oscillations]] — 嗅球β/γ振荡由兴奋性（僧帽细胞）-抑制性（颗粒细胞）动力学产生，与梨状皮层振荡同步；呼吸锁定振荡（Zelano 2016）可能是嗅觉预测-误差循环的时间载波

## 未解问题

- Q-pc-01：误差单元和表征单元是否能被可靠地在体内直接区分？（**部分更新 2026-09-14**：Thomas et al. 2024 在人类 V1 用 7T fMRI 层级解码首次观察到深层=预期、浅层=误差的解剖分离；神经适应解释仍不能完全排除；见文章 #144）
- Q-pc-02：预测编码/自由能原理是否足够可证伪？其核心实验预测是什么？（高优先级）
- Q-pc-03：环绕抑制和末端停止究竟是预测误差还是侧抑制？如何在体内区分？（中优先级）
- Q-pc-04：V1 感觉运动失配响应的具体来源（运动皮层反馈 vs 高级视觉 vs 神经调质）？（高优先级）
- Q-pc-05：层级振荡映射（γ/α-β）的普适性如何？Westerberg 2026 的挑战范围有多大？（高优先级）
- Q-pc-06：在严格排除神经适应后，V1 和其他皮层区域是否存在真正的预期依赖性预测误差信号？（高优先级，来自 Solomon 2021 批评）
- Q-pc-07：VAE 编码器与皮层前馈通路的对应是否超出数学类比，存在真实的计算等价性？（中优先级）
- Q-pc-08（中优先级，2026-09-14 新增，**2026-10-04 部分更新**）：Thomas 2024 观察到的 V1 层级分离是否在其他初级感觉皮层可以复现？**嗅觉系统的 PCx→OB 反馈回路提供了一个间接支持**——嗅觉中同样存在高层（PCx）→低层（OB）的预测反馈，且解剖上仅需一步；但嗅觉皮层无六层结构，"深层=预期、浅层=误差"的层级分工是否适用于三层皮层尚未检验。A1/S1 的层级分离证据仍然缺乏。
- Q-pc-09（中优先级，2026-09-14 新增）：7T fMRI 时间分辨率（~1s BOLD 信号）无法分辨"预期建立"与"误差计算"的毫秒时间动态。层级 ECoG 或层级探针电生理何时能提供时间分辨的直接证据？L5/6 的预测信号是在刺激出现前（真正预期）还是刺激出现后（快速推断）建立的？
- Q-pc-olfaction-01（中优先级，2026-10-04 新增）：PCx→OB 反馈回路的**因果证据**仍不充分。如果用光遗传学特异性沉默梨状皮层→嗅球颗粒细胞反馈纤维，气味辨别能力是否真的下降？在气味学习（气味-奖励联结）期间，反馈强度是否增加？（检验"预测压制"假说的关键缺失实验）
- Q-pc-olfaction-02（低优先级，2026-10-04 新增）：鼻呼吸振荡同步的方向性——是鼻气流驱动梨状皮层振荡（机械感觉→电信号），还是梨状皮层的内生振荡恰好与呼吸相位共振？Zelano et al. 2016 的口呼吸对照支持"鼻气流是必要条件"，但不能排除鼻子介导的多模态整合。
- Q-pc-olfaction-03（中优先级，2026-10-04 新增）：梨状皮层的"嗅觉认知地图"（气味-空间、气味-视觉联合表征）在人类层面的精细组织原则？7T fMRI 是否能在人类 aPCX/pPCX 中分辨气味-跨模态联合预测表征？

## 修订历史

- 2026-06-15 · 创建 · 基于《当大脑主动预测而非被动接收》一文 · 初始置信度：中（框架是 mainstream，但具体机制仍有争议）
- 2026-06-16 · 修订 · 基于《默认模式网络》一文 · 添加 DMN 作为预测编码层级高层先验生成器的关联；related 新增 default-mode-network
- 2026-05-30 · 修订 · 基于《当意识在大脑中"点燃"》一文 · 添加 GWT 与预测编码的互补关系：足够大的预测误差触发工作空间点燃；related 新增 global-workspace-theory
- 2026-05-31 · 修订 · 基于《第四周综合：当大脑成为自己的宇宙》(#28) · 将预测编码定位为「世界模型误差加权更新层」；新增 world-model 到 related；明确预测编码给出了世界模型的贝叶斯更新方程：Δmodel ∝ precision_weighted_prediction_error
- 2026-06-20 · 修订 · 基于《语言的解剖》一文 · 新增语言域的预测编码实例：词出现前200ms的语义-感觉运动预测（Grisoni 2024），腹侧流具身语义预测（工具词→运动皮层，动物词→视觉皮层）；related 新增 language-network, ventral-language-stream
- 2026-06-23 · 修订 · 基于《小脑的秘密》一文 · 新增"小脑专用预测误差学习系统"段落（前向模型→误差→LTD更新）；related 新增 cerebellum, forward-model
- 2026-07-13 · 修订 · 基于《大脑的预言机》一文（#81）· 新增 AI 比较维度（dimensions 加 AI）；关键证据表增加 Whittington & Bogacz 2017（PC ≈ 反向传播）、Richter 2018（腹侧流抑制）、Solomon 2021（批评性证据）、VAE 数学等价；related 新增 free-energy-principle、variational-autoencoder；未解问题新增 Q-pc-06、Q-pc-07；key_sources 新增 PMID:28333583、PMID:33683317、PMID:19528002
- 2026-07-18 · 修订 · 基于《大脑皮层的规范微回路》一文（#86）· 补充规范微回路作为预测编码解剖实现载体的关联；related 新增 cortical-canonical-microcircuit、cortical-layers；connections 段新增两条解剖实现链接
- 2026-07-19 · 修订 · 基于《β振荡的三副面孔》一文（#87）· 关键证据表新增 Bastos 2015（28 对视觉区域γ前向/β后向，PMID:25556836）和 Bastos 2018（前额叶层流验证频率层级规律，PMID:29339471）；连接新增 beta-oscillations（β作为反馈预测的振荡载体，γ作为前馈误差的振荡载体）；related 新增 beta-oscillations；key_sources 新增 PMID:25556836、PMID:29339471
- 2026-08-13 · 修订 rev9 · 基于《大脑皮层的时间帝国》文章 #112 · 新增关键证据行：Caucheteux et al. 2023（PMID:36864133，n=304，额顶叶皮层预测更长时程/更高上下文的语言表征，颞叶皮层预测短时程/低上下文）——将预测编码层级与 INT/TRW 时间层级显式连接；related 新增 intrinsic-neural-timescale、temporal-receptive-window；key_sources 新增 PMID:36864133
- 2026-09-14 · 修订 rev10 · 基于《谁说了什么：V1 各层如何区分预测与误差》文章 #144 · 新增 Thomas et al. 2024（PMID:38697110）为关键证据行——7T fMRI 层级解码首次在人脑直接验证 L5/6=预期、L2/3=误差的解剖分离；Q-pc-01 状态更新为"部分回答（存争议）"；新增未解问题 Q-pc-08（跨感觉皮层普遍性）和 Q-pc-09（层级时间分辨证据）；key_sources 新增 PMID:38697110；source_articles 新增 #144
- 2026-10-04 · 修订 rev11 · 基于《大脑的嗅觉预言》文章 #164 · 新增"嗅觉系统：预测编码的进化实验室"段落，梳理PCx→OB反馈回路作为预测编码的嗅觉实现（Lyons & Gottfried 2025，PMID:40345946）；新增鼻呼吸主动推断机制（Zelano et al. 2016，PMID:27927961）；新增视觉/嗅觉/语言三系统预测编码比较表；Q-pc-08 部分更新（嗅觉系统提供间接支持，但三层皮层层级分离尚未检验）；related 新增 piriform-cortex、olfactory-bulb、gamma-oscillations；connections 新增三条嗅觉系统链接；新增未解问题 Q-pc-olfaction-01、Q-pc-olfaction-02、Q-pc-olfaction-03；key_sources 新增 PMID:40345946、PMID:27927961、PMID:32662420

## 来源文章

- [[2026-06-15-predictive-coding]]
- [[2026-06-20-language-dual-stream]]
- [[2026-07-19-beta-oscillations-cortical-prediction]]
- [[2026-08-13-cortical-temporal-hierarchy-trw]]
- [[2026-09-14-v1-laminar-prediction-error-evidence]]
- [[2026-10-04-predictive-coding-olfactory-piriform-feedback]]

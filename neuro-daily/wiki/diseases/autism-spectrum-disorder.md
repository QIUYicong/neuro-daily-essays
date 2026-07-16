---
title: 自闭症谱系障碍
slug: autism-spectrum-disorder
domain: diseases
type: disease
status: mainstream
confidence: medium
created: 2026-10-18
updated: 2026-07-17
revision_count: 2
dimensions: [molecular, synaptic, microcircuit, brain-region, whole-brain-network, behavior, cognition, disease, development]
related: [ei-balance, cntnap2, fragile-x-syndrome, fmrp, mglur-ltd, pv-interneurons, synaptic-scaling, neuroligin, shank3, intellectual-disability, global-workspace-theory, syngap1]
prerequisites: [ei-balance, synaptic-transmission, pv-interneurons, action-potential]
opens_questions: [Q-asd-01, Q-asd-02, Q-asd-03]
source_articles: [2026-10-18-autism-synaptopathy-ei-balance, 2026-07-17-syngap1-intellectual-disability-mechanism]
key_sources: ["PMID:18923512", "PMID:31089192", "PMID:34690695", "PMID:30610205", "PMID:26289574", "PMID:39585908", "PMID:21962519", "PMID:38422154"]
---

# 自闭症谱系障碍 (Autism Spectrum Disorder, ASD)

> **一句话定义**：ASD 是一组以社交沟通困难和限制性重复行为为核心特征的神经发育综合征，遗传异质性极高（>100 个高可信度风险基因），不同分子路径（突触黏附规范、PSD支架、GABA能发育、翻译调控）通过破坏 E/I 平衡汇聚于相似的回路功能障碍；约影响全球 1-2% 人口。

## 当前理解

我们现在认为，ASD 在分子层面是**多因汇聚**的典型案例：数百条独立的遗传路径，各自通过不同的分子机制最终削弱皮层回路的 E/I 平衡（兴奋-抑制动态均衡），降低信噪比，最终在社交认知（对信噪比要求最高的功能域）上产生类似的损伤。

**遗传异质性**：高外显率单基因变异影响约 30% 的伴有智力障碍或癫痫的 ASD 个体（Leblond et al. 2024）；其余更大比例由大量常见变异的微弱累加效应贡献，且与 ADHD、抑郁症等神经发育状态有广泛遗传重叠。ASD 更准确地应被理解为"遗传异质性神经发育综合征群"而非单一疾病实体。

**分子路径集群**（Bourgeron 2015）：风险基因功能分布于：
1. **突触黏附/规范**：Neurexin (NRXN1)、Neuroligin (NLGN3/4)、CNTNAP2——决定突触 E/I 身份的分子标识系统
2. **PSD 支架**：SHANK3/SHANK2——后突触密度的结构框架
3. **离子通道/受体**：GRIN2B (NMDA)、SCN1A (Nav1.1)、SYNGAP1（RasGAP+PSD-95占位竞争，见 [[syngap1]]）——突触传递的执行元件
4. **翻译调控**：FMRP/FMR1 (脆性X)、TSC1/TSC2 (结节硬化)——局部蛋白合成的速率调节器
5. **转录/染色质**：ARID1B、CHD8、KMT2C——发育期基因表达程序

**汇聚终点**：这五类分子机制通过不同路径最终影响皮层 E/I 平衡——大多数路径导致 GABA 能抑制不足（中间神经元减少或功能受损），少数路径（如 FMRP 缺失）导致兴奋性突触强度系统性下调，但两个方向都会降低回路的信噪比。

**神经多样性视角**：大量 ASD 相关遗传变异与 ADHD 和抑郁症有遗传重叠（Leblond et al. 2024），提示 ASD 代表的可能不只是神经系统的"损坏模式"，而是部分属于神经回路配置的连续变异谱。

## 关键机制

### 突触黏附规范失效（Neurexin-Neuroligin）

NLGN1 规范兴奋性突触，NLGN2 规范抑制性突触（PV+ 中间神经元输入）；任何突变破坏这种规范，均可在突触身份分配层面引入 E/I 混乱（Südhof 2008）。

NLGN3 R451C（发现于两兄弟，ASD表型）：蛋白表面表达减少~90%（内质网滞留），但海马 CA1 的 AMPAR 介导传递反常**增强**，纹状体 D1+ 细胞 mIPSC 频率减少 50%——同一突变在不同回路方向相反，说明"NLGN3 ASD"不是单一机制（Uchigashima & Futai 2021）。

### PSD 支架功能障碍（SHANK3）

SHANK3 是 PSD 的多功能"建筑师"，同时结合 GKAP（连接 NMDA 受体复合体）、Homer（连接 mGluR5）和 actin（细胞骨架）。SHANK3 单倍剂量不足（22q13.3 缺失 = Phelan-McDermid 综合征）导致基础谷氨酸能传递缺陷和 LTP 损伤。

SHANK3 是模块化的：不同变异损害不同下游通路（ABI1/WAVE 复合体、GKAP-结合、Homer-结合等），单一通路的修复无法恢复全部功能（Wang et al. 2020）。

### GABA 能中间神经元发育缺失（CNTNAP2）

CASPR2 在胚胎期 MGE/CGE 中表达，参与 GABA 能中间神经元迁移导引。CNTNAP2 敲除导致 PV+/CR+/NPY+ 中间神经元数量减少（异位定居），皮层 E/I 时序协调崩溃（见 cntnap2.md）。关键证据：光遗传选择性激活 mPFC PV+ 细胞可完全救治社交行为缺陷（Sohal & Rubenstein 2019）。

### 可塑性失控（FMRP/mGluR5，脆性X）

FMRP 缺失 → mGluR-LTD 过度增强 → AMPAR 系统性内吞 → 兴奋性突触弥漫下调（与前三条路径的"抑制不足"方向相反，但同样破坏 E/I 平衡）。详见 fragile-x-syndrome.md 和 mglur-ltd.md。

### 突触结构性占位失衡（SynGAP1）

SYNGAP1单倍剂量不足是另一条重要的单基因ASD/智力障碍共病路径（2026-07-17更新，见 [[syngap1]]）：SynGAP的C端结构域经液-液相分离与AMPA受体辅助蛋白TARP竞争PSD-95结合位点，失衡后导致AMPA受体在关键发育窗口内提前/过量插入（兴奋性一侧）；同时独立损害PV+中间神经元的突触驱动和内在兴奋性（抑制性一侧）——是本页"多因汇聚于E/I平衡"框架下证据链最完整、且同时从兴奋和抑制两个方向独立破坏平衡的单基因案例。值得注意的是，2024年的分离功能实验（Araki et al., PMID:38422154）证明SynGAP的经典RasGAP催化"刹车"活性对上述表型并非必需，真正机制是结构性占位竞争——这提示本页第3类"离子通道/受体执行元件"中的部分基因，其致病机制可能比"直接改变离子通道/受体功能"更复杂，涉及此前被低估的蛋白结构性占位/相分离机制。

### E/I 失衡的信噪比效应

E/I 平衡的功能是放大激活集群的信号、压制非激活集群的背景噪声（稀疏编码）。无论偏向哪个方向，E/I 失衡都降低回路信噪比——社交沟通对信噪比要求最高，因此社交表型最先受损（Sohal & Rubenstein 2019）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| ASD 高外显率单基因变异约占~30%（伴ID/癫痫） | 全外显子组测序+大样本队列 | PMID:39585908 | 高 |
| NLGN1→兴奋性；NLGN2→抑制性突触（Nlgn KO小鼠） | KO小鼠+电生理 | PMID:18923512 | 高（小鼠） |
| NLGN3 R451C: 表面蛋白-90%+海马CA1 AMPAR传递增强 | KI小鼠+膜片钳 | PMID:34690695 | 高（小鼠） |
| SHANK3 S685I 特异破坏 ABI1/WAVE 招募（模块化功能） | 转基因小鼠+Co-IP | PMID:30610205 | 高（小鼠） |
| CNTNAP2 KO: PV+ 减少+光遗传PV激活完全救治社交缺陷 | KO小鼠+光遗传 | PMID:31089192 (综述 PMID:21962519) | 高（小鼠） |
| 多种ASD小鼠模型mIPSC减少→低剂量苯二氮䓬类改善行为 | KO小鼠+电生理+行为 | PMID:31089192 | 高（小鼠，剂量和时机重要） |
| 非特异性增强抑制有时恶化ASD行为（VPA模型） | VPA模型+行为+神经药理 | PMID:31089192 | 中-高（重要警告） |

## 连接

- [[ei-balance]] — ASD 多条分子路径的共同功能汇聚终点
- [[cntnap2]] — GABA能中间神经元发育路径的关键基因
- [[fragile-x-syndrome]] — mGluR-LTD/FMRP 路径的典型单基因 ASD
- [[fmrp]] — FXS 的分子核心，与 ASD 连接
- [[mglur-ltd]] — FXS 中突触弱化的执行机制
- [[pv-interneurons]] — E/I 平衡的核心执行者，多条ASD路径的共同受损目标
- [[synaptic-scaling]] — 突触稳态可塑性，与ASD中的补偿机制相关
- [[intellectual-disability]] — ASD 常见共病，部分分子机制重叠
- [[global-workspace-theory]] — ASD 的意识和信息整合理论背景
- [[syngap1]] — 离子通道/受体执行元件类的代表基因，同时从兴奋和抑制两侧独立破坏E/I平衡

## 未解问题

- Q-asd-01（高优先级）：不同基因亚型 ASD 的 E/I 偏移方向是否确实不同（有些兴奋过多，有些兴奋不足）？是否可通过 EEG/MEG 在人类中直接验证？
- Q-asd-02（中优先级）：NLGN3 R451C 小鼠同时存在行为增强（空间学习）和社交减少——来自相同 E/I 偏移或不同回路节点的独立效应？
- Q-asd-03（高优先级）：ASD 亚型分层的临床可行性——针对特定遗传亚型的靶向干预能否在人类临床试验中实现统计效力？

## 修订历史

- 2026-10-18 · 创建 · 基于《突触病的汇聚：ASD 如何将一千条分子路径折叠成同一张失衡的天平》(#178) · 来源：PMID:18923512/31089192/34690695/30610205/26289574/39585908/21962519 · 初始置信度：中（概念框架成熟，但大多数证据来自小鼠模型，人类直接验证有限）
- 2026-07-17 · 修订 rev2 · 基于《占位胜过刹车：当SynGAP1的"刹车"活性被证明并非必需，最常见的单基因智力障碍还剩下什么解释？》(#200) · "分子路径集群"第3类新增SYNGAP1；新增"突触结构性占位失衡"小节，记录SynGAP1同时从兴奋和抑制两侧独立破坏E/I平衡的机制，及其RasGAP催化活性非必需这一分离功能新发现；related新增syngap1；key_sources新增PMID:38422154

## 来源文章

- [[2026-10-18-autism-synaptopathy-ei-balance]]
- [[2026-07-17-syngap1-intellectual-disability-mechanism]]

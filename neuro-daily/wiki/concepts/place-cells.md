---
title: 场所细胞
slug: place-cells
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-22
updated: 2026-07-16
revision_count: 4
dimensions: [cellular, microcircuit, brain-region, behavior, cognition]
related: [grid-cells, theta-oscillations, sharp-wave-ripples, theta-phase-precession, memory-consolidation, hippocampal-circuit, cognitive-map, remapping, path-integration, pattern-separation, pattern-completion, entorhinal-ca1-circuit, temporoammonic-path, btsp, goal-directed-theta-sweeps]
prerequisites: [hippocampal-circuit, action-potential, synaptic-transmission]
opens_questions: [Q-gc-01, Q-gc-03]
source_articles: [2026-06-22-grid-cells-place-cells, 2026-06-24-hippocampal-ca3-pattern-completion, 2026-07-16-hippocampal-theta-sweeps-goal-direction]
key_sources: ["PMID:5124915", "PMID:8353611", "PMID:23354386", "PMID:16858394", "PMID:42386948", "PMID:42386950"]
---

# 场所细胞 (Place Cells)

> **一句话定义**：海马CA1/CA3中在动物占据环境特定位置时选择性放电的神经元，是大脑认知地图的基本编码单元，在不同环境中通过"重映射"生成完全正交的表征。

## 当前理解

我们现在认为，场所细胞不是被动的感觉转发器，而是**主动构建的空间表征**：它们的激活由对内嗅皮层网格细胞输入的整合和海马内部回路的竞争性编码共同决定，而非由某个具体的感觉刺激直接驱动。

场所细胞的核心计算贡献是：在任意连续空间（物理环境、虚拟环境）中，以稀疏编码维护一张"当前位置的唯一标识"——任何时刻仅约1–5%的CA1锥体细胞激活，避免表征之间的相互干扰。

最重要的进展是理解了两点：（1）场所细胞通过"重映射"使不同环境的记忆完全正交，避免了知识的相互覆盖；（2）场所细胞不只编码当前位置，还通过θ相位前移机制在时间维度上编码过去-当前-未来的轨迹序列（θ序列），这与情节记忆的序列组织同构。

## 关键机制

### 1. 场所场的空间特性

- **场所场（place field）大小**：直径约20–40厘米（大鼠标准箱），CA3细胞场所场通常大于CA1；人类海马对应细胞场所场可达数米
- **稀疏编码**：任意位置，激活CA1锥体细胞约1–5%；高度稀疏性保证不同环境的表征在神经活动空间中接近正交
- **多场所场**：CA3锥体细胞常有多个场所场；CA1通常只有一个

### 2. 场所场的生成：来自网格细胞

多模块网格输入叠加假说（McNaughton等 2006）：海马接收来自多个不同间距网格细胞模块的输入，只有在某个特定位置，所有模块的网格激活同时处于极大值附近——加权求和产生单一活动峰，形成场所场。光遗传证据（Zhang SJ等 2013，PMID: 24366130）支持MEC II层激活直接诱发海马位置选择性响应。

### 3. 重映射（Remapping）

- **全局重映射**：换入完全陌生的环境时，CA1场所细胞几乎完全重新分配（不同细胞激活，或同一细胞在完全不同位置激活）
- **率重映射（rate remapping）**：环境相似时，相同细胞保留场所场但改变放电率
- 重映射使不同环境的表征在神经状态空间中接近正交，互相干扰最小化

### 4. θ相位前移与时间编码

场所细胞的放电相位在穿越场所场时系统性提前（O'Keefe & Recce 1993，PMID: 8353611）：
- 进入场所场：晚期θ相位（近波峰）
- 穿越中途：中期θ相位
- 离开：早期θ相位（近波谷）
- 总位移约100–355°，与位置强相关

这产生了"θ序列"：单个θ周期（约125 ms）内编码了时间压缩的空间轨迹，为突触可塑性（STDP）提供时间压缩框架。

**2026-07-16 新增**：θ序列并非单一现象。除了上述侧向交替扫描外，两项独立研究（Tang et al.、Yu et al. 2026, *Nat Neurosci*）确认存在第二种学习依赖的"目标导向θ扫描"——同一群场所细胞在θ周期内系统性地指向记忆中的目标位置，独立于动物当下的运动方向和头部朝向，随训练增强，并与前额叶协同。详见独立页面 [[goal-directed-theta-sweeps]]。

### 5. EC 双流输入对场所场的差异化贡献

CA1 场所场的生成和精准度依赖两条来自内嗅皮层的平行输入（Brun et al. 2002, 2008）：

**EC-III 直接穿通径路（→ CA1 SLM）**：维持场所场的空间精准度
- 选择性破坏 MEC-III（Brun et al. 2008）→ CA1 场所场变大、更分散，但 CA3 场所场不受影响
- 结论：EC-III 直接输入提供当前感觉情境的精准空间锚定

**EC-II → CA3 → CA1 三突触通路（→ CA1 SR）**：支持联想记忆回忆
- 切断 CA3 Schaffer 侧支（Brun et al. 2002）→ CA1 仍形成清晰场所场，空间识别完好，但空间回忆（水迷宫主动检索）受损
- 结论：三突触通路（经 CA3 中继）是联想记忆回忆的必要条件，而非场所场基本编码的必要条件

**两条通路的功能冗余**（Hales et al. 2014）：大面积 MEC 损伤后，CA1 场所场仅部分降级（不完全消失），提示 LEC 输入能提供有限的空间信息作为代偿。

### 6. 尖波涟漪（SWR）期间的重播

静息和NREM睡眠中，场所细胞以约20倍速重播白天的激活序列（SWR事件）。这是记忆巩固的物理基础：序列重播逐渐在新皮层刻印长期记忆。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 场所细胞存在于大鼠海马CA1 | 自由运动单细胞电记录 | PMID:5124915 | 高（教科书级） |
| 暗室中场所场仍维持（路径整合依赖） | 遮蔽视觉实验+记录 | 多个实验室 | 高 |
| θ相位前移（100–355°，与位置相关） | 大鼠线性轨道单细胞+LFP | PMID:8353611 | 高（经典，多次重复） |
| 重映射：不同环境完全正交 | 多环境切换+单细胞记录 | 综述PMID:23354386 | 高 |
| MEC光遗传激活→海马位置特异放电 | 光遗传激活MEC II层 | PMID:24366130 | 中-高（因果） |
| CA3 切断后 CA1 仍有场所场，但回忆受损 | CA3 选择性切断 + 水迷宫行为 | PMID:12077421 | 高 |
| MEC-III 损伤→ CA1 场所场变大变散 | MEC-III γ-乙炔基 GABA + CA1/CA3 记录 | PMID:18215625 | 高 |
| LEC 也编码空间位置（打破 LEC=非空间假设） | 体内 2P 轴突成像（VR 导航） | PMID:37816349，PMC:11490304 | 高 |
| SWR期间场所序列以20倍速重播 | 多单元记录+Bayesian解码 | PMID:26135716 | 高 |
| 人类海马（fMRI/ECoG）有类似空间选择性响应 | 人类神经外科iEEG | 多篇 | 中-高 |
| θ扫描存在学习依赖的目标导向类型，独立于运动/头部朝向 | 蜂窝迷宫+开放场地任务对比，两独立实验室 | PMID:42386948、PMID:42386950（均bioRxiv全文） | 高（独立交叉验证） |

## 连接

- [[grid-cells]] — 多模块网格输入叠加生成场所场；场所细胞是网格坐标的下游解码
- [[theta-oscillations]] — θ振荡为场所细胞的相位编码提供时间参照框架
- [[theta-phase-precession]] — 场所细胞的核心时间编码机制：放电相位随位置系统性前移
- [[sharp-wave-ripples]] — 静息/睡眠中场所细胞序列在SWR中被高速重播，是记忆巩固机制
- [[memory-consolidation]] — 场所细胞序列的SWR重播驱动海马→新皮层的记忆转写
- [[hippocampal-circuit]] — 场所细胞主要位于CA1（少数CA3）；依赖EC输入和海马内部回路
- [[cognitive-map]] — 场所细胞是认知地图的基本构成单元
- [[path-integration]] — 在无外部地标时，场所场由路径整合（网格细胞）维持
- [[entorhinal-ca1-circuit]] — EC-CA1 双流回路是场所场生成的解剖基础；直接 TA path 提供精准锚定，三突触 CA3 通路提供联想预测
- [[temporoammonic-path]] — EC-III 直接输入维持 CA1 场所场空间精准度的回路实体
- [[btsp]] — BTSP 是场所场写入的主要突触机制；EC 双流输入驱动 BTSP 的触发和内容
- [[goal-directed-theta-sweeps]] — 场所细胞群体θ扫描中的学习依赖子类型，编码指向记忆目标的方向向量

## 未解问题

- Q-gc-01：海马remapping时，上游的MEC网格地图是否也完全重配，还是只在海马层面发生正交变换？
- Q-gc-03：人类单细胞水平的场所细胞记录能否在无损伤情况下实现？当前iEEG记录的信噪比是否足以捕获单场所细胞？

## 修订历史

- 2026-07-16 · 修订（rev4）· 基于《脚还没动，海马已经指向了目标》一文（#199）· "θ相位前移与时间编码"小节新增目标导向θ扫描的简述；证据表新增1行；related新增goal-directed-theta-sweeps
- 2026-06-24 · 修订 · 基于"记忆不混淆的秘密"文章 · 加入模式分离/补全视角：场所细胞的"重映射"行为是模式分离在空间记忆中的具体体现；Leutgeb 2004 的 CA3 vs CA1 不同计算策略与场所细胞的率重映射 vs 全局重映射直接相关；related 新增 pattern-separation、pattern-completion
- 2026-06-22 · 创建 · 填补长期悬空引用（被theta-oscillations、sharp-wave-ripples等多页引用但无对应页面） · 基于《六边形的秘密》文章 · 初始置信度：高
- 2026-09-24 · 修订（rev3）· 基于《时序之门》一文（#154）· 新增"EC 双流输入对场所场的差异化贡献"机制小节（Brun 2002 CA3 切断实验；Brun 2008 MEC-III 损伤实验；Hales 2014 MEC 大面积损伤）；证据表新增 3 行；连接新增 entorhinal-ca1-circuit、temporoammonic-path、btsp

## 来源文章

- [[2026-06-22-grid-cells-place-cells]]
- [[2026-06-24-hippocampal-ca3-pattern-completion]]
- [[2026-09-24-entorhinal-ca1-dual-stream-theta-gate]]
- [[2026-07-16-hippocampal-theta-sweeps-goal-direction]]

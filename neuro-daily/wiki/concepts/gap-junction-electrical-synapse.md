---
title: 缝隙连接与电突触（Gap Junctions & Electrical Synapses）
slug: gap-junction-electrical-synapse
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-10-04
updated: 2026-10-04
revision_count: 1
dimensions: [molecular, synaptic, cellular, microcircuit]
related: [pv-interneurons, gamma-oscillations, binding-by-synchrony, connexin36, theta-gamma-coupling, sst-interneurons, inferior-olive, retina, ephaptic-coupling]
prerequisites: [membrane-potential, ion-channels, synaptic-transmission, action-potential]
opens_questions: [Q-gap-junction-01, Q-gap-junction-02, Q-gap-junction-03, Q-gap-junction-04]
source_articles: [2026-10-04-electrical-synapse-gap-junction-gamma]
key_sources: ["PMID:15217338", "PMID:15738956", "PMID:12574431", "PMID:30824857", "PMID:27121576", "PMID:36455063", "PMID:32393538", "PMID:32276058", "PMID:38988663"]
---

# 缝隙连接与电突触 (Gap Junctions & Electrical Synapses)

> **一句话定义**：缝隙连接是由 Connexin-36（神经元）等蛋白构成的细胞间直接通道，允许电流在相邻神经元之间以亚毫秒延迟双向流动，在抑制性中间神经元网络中协调同步放电并支持（至少在海马中）γ 振荡的产生。

## 当前理解

我们现在认为，电突触（由缝隙连接形成）是哺乳动物神经系统中"普遍存在但被严重低估"的第二通信系统（Connors & Long, 2004, PMID:15217338）。与化学突触的有延迟、单向、量子化通信不同，电突触实现的是直接的细胞质连接：电流可以在两个相邻神经元之间几乎瞬时（<0.2 ms）、双向地流动。

在哺乳动物脑中，**Connexin-36（Cx36）**是神经元电突触的主要蛋白（Söhl 2005, PMID:15738956）。Cx36 主要在 PV+ 和 SST+ 中间神经元之间形成电突触，使这些抑制性细胞形成"电耦合网络"，从而能够在毫秒内协调大群中间神经元的同步放电，驱动或维持 γ 频段振荡（Buhl 2003, PMID:12574431）。

然而，Cx36 对 γ 振荡的必要性存在显著的区域特异性争议：海马中 Cx36 KO 导致 γ 功率显著降低（Buhl 2003），但在新皮层中 Cx36 KO 几乎不影响 γ 振荡（Neske & Connors 2016, PMID:27121576）。计算模型提示，缝隙连接对"超极化抑制"主导的网络（更接近海马）更为关键，对"分流抑制"主导的网络（可能更接近新皮层）贡献有限（Via 2022, PMID:36455063）。**此矛盾已在 contested_claims.json 中登记（C-2026-10-04-01）。**

此外，电突触并非静态导线——Alcamí & Pereda（2019, PMID:30824857）综述表明，Cx36 通道的导电性受 pH、磷酸化状态、神经调质和活动状态的动态调制，使电突触成为可调节的回路元件。

## 分子机制

### Connexin 蛋白与通道组装
- **连接蛋白（connexin, Cx）**：哺乳动物约 21 种，按分子量命名（如 Cx36 ≈ 36 kDa）
- **连接子（connexon/hemichannel）**：6 个 connexin 蛋白环状排列，形成含中心孔道的半通道
- **完整通道**：两个相邻细胞各贡献一个连接子，对接形成约 1.5 nm 孔道
- **分子筛选**：允许通过离子、cAMP、IP₃、葡萄糖等 <1000 Da 小分子；阻止蛋白质通过
- 细胞间缝隙：2–4 nm（vs. 化学突触间隙 20–40 nm）

### 神经元中的主要 Connexin 亚型
| 亚型 | 主要细胞类型 | 功能 |
|------|------------|------|
| Cx36 | PV/SST 中间神经元；下橄榄核；视网膜 | γ 振荡协调；运动节律；视觉适应 |
| Cx45 | 部分抑制性中间神经元 | 补充角色 |
| Cx43/Cx30/Cx26 | 星形胶质细胞 | 胶质网络（与神经元电突触独立） |
| Panx1/Panx2 | 多种细胞 | 可形成半通道，细胞外信号传递；是否形成真正细胞间电突触尚有争议 |

## 电突触的生物物理特性

### 耦合系数（Coupling Coefficient κ）
```
κ = ΔV_post / ΔV_pre
```
- 典型值：0.01–0.1（1–10%）
- 含义：突触前膜去极化 10 mV → 突触后膜感受 0.1–1 mV 的同步去极化
- 看似微弱，但结合亚毫秒延迟，在网络接近阈值时足以实现同步触发

### 与化学突触的关键对比
| 特性 | 化学突触 | 电突触 |
|------|---------|-------|
| 传递延迟 | 1–3 ms | <0.2 ms |
| 方向性 | 单向 | 双向 |
| 信号类型 | 量子化（递质包） | 连续（电流） |
| 放大/非线性 | 是 | 否（线性） |
| 调制能力 | 丰富（多类受体） | 有（pH、磷酸化等） |
| 传递分子 | 递质→离子（通过受体） | 离子+小分子（直接） |

### 低通滤波特性
电突触对信号有低通滤波效果：缓慢的亚阈值电压变化（θ 振荡、慢去极化）比尖锐的动作电位波形更高效地通过。这意味着电突触更擅长同步"振荡性活动"，而不是逐个动作电位的1:1复制。

## 功能角色

### 1. 中间神经元网络同步（主要功能）
PV 篮状细胞之间的 Cx36 连接在化学突触发挥作用之前，率先传播"准备发火"信号，将多个 PV 细胞同步拉向发火阈值。这是 ING（interneuron network gamma）模式中的关键同步启动机制（至少在海马）。

### 2. 远程皮层同步的间接调制
Cx36 KO 小鼠中，皮层区域间的自发活动远程同步（infra-slow band）发生改变（Kraft 2020, PMID:32276058），表明局部电耦合塑造全脑网络拓扑。

### 3. 发育功能（短暂性）
胚胎和出生后早期，connexin 在几乎所有神经细胞间广泛表达，协调神经元迁移和早期自发活动。随化学突触成熟，大部分电突触消失（关键期），只保留特定回路中的"专业"连接。

### 4. 混合突触（Mixed Synapse）
许多电突触与化学突触并存于同一接触位点（混合突触）：同一对神经元同时通过 Cx36 传递电信号，通过 GABA 传递化学抑制信号，两者互补。

### 5. 谷氨酸能主细胞中的"沉默"连接
Ixmatlahua 2020（PMID:32393538）发现海马苔状纤维-CA3 突触处存在 pH 敏感的沉默 Cx36 连接——正常状态下关闭，特定 pH 变化时激活。提示主细胞电耦合的潜在储备，功能意义待明确。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Cx36 是神经元主要连接蛋白 | 免疫组化、原位杂交、KO小鼠 | PMID:15738956（摘要）| 高 |
| 海马γ振荡选择性依赖Cx36 | Cx36 KO在体LFP记录 | PMID:12574431（PMC） | 高 |
| 新皮层γ振荡不依赖Cx36 | Cx36 KO新皮层记录 | PMID:27121576（摘要） | 中高 |
| 电突触是动态可调节的 | 多实验室综述 | PMID:30824857（摘要） | 高 |
| 谷氨酸能神经元中存在沉默Cx36 | 海马离体记录+pH操作 | PMID:32393538（PMC） | 中（单篇）|
| 电耦合影响远程皮层同步 | Cx36 KO + fMRI/LFP | PMID:32276058（PMC） | 中 |

## 争议：海马 vs. 新皮层 Cx36 依赖性

→ 见 `state/contested_claims.json`，条目 **C-2026-10-04-01**

**主张A**（Buhl 2003）：海马 Cx36 KO → γ 功率选择性降低  
**主张B**（Neske & Connors 2016）：新皮层 Cx36 KO → γ 振荡不受影响

**当前最可能的解释**：
1. 海马 PV 细胞（超极化抑制主导）需要电突触；新皮层 PV 细胞（分流抑制主导）不需要（Via 2022 计算模型）
2. 轴突间耦合（Traub 2003 预测的 pyramid-pyramid）可能在特定条件下替代树突间耦合
3. 离体 vs. 在体记录条件差异

**证据状态**：假说阶段；需要在对应回路中直接检验抑制类型（超极化 vs. 分流）与 Cx36 的交互。

## 连接

- [[pv-interneurons]] — 主要形成 Cx36 电突触的细胞类型
- [[gamma-oscillations]] — 电突触在海马γ产生中的贡献
- [[sst-interneurons]] — 也可形成 Cx36 电突触
- [[binding-by-synchrony]] — γ 振荡功能假说（电突触是γ产生的上游机制）
- [[theta-gamma-coupling]] — γ 振荡的宏观网络背景
- [[inferior-olive]] — 下橄榄核：Cx36 大量存在，产生运动节律（电突触机制最清楚的区域）
- [[ephaptic-coupling]] — 另一种非化学的细胞间电信号传递（场效应，不通过通道）

## 未解问题

- **Q-gap-junction-01（高优先级）**：轴突间 Cx36 电突触（pyramid-pyramid）在人类新皮层中是否存在并参与 γ？（Traub 2003 计算预测，但解剖学直接证据稀少）
- **Q-gap-junction-02（中优先级）**：沉默的谷氨酸能 Cx36 连接（Ixmatlahua 2020）在海马 LTP 或学习中是否被功能性激活？
- **Q-gap-junction-03（中优先级）**：Cx36 电突触在快速涟漪振荡（SWR，140–200 Hz）中的角色？Buhl 2003 显示 fast ripples 不受影响，但其他 connexin 或解剖接触可能贡献。
- **Q-gap-junction-04（低优先级）**：如何无创测量人类大脑中的电突触活动？Cx36 基因多态性与认知表型的关联？

## 修订历史

- 2026-10-04 · 创建 · 基于《神经元的秘密握手》（#164）一文 · 初始置信度：高（建立机制）/ 海马vs.新皮层差异为中（活跃争议）

## 来源文章

- [[2026-10-04-electrical-synapse-gap-junction-gamma]]

---
title: 感知决策
slug: perceptual-decision-making
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-01
updated: 2026-09-01
revision_count: 1
dimensions: [microcircuit, brain-region, cognition, behavior]
related: [drift-diffusion-model, lip-area, mt-v5-motion-area, posterior-parietal-cortex, superior-colliculus, neural-manifold, dorsal-attention-network, value-based-decision-making]
prerequisites: [action-potential, mt-v5-motion-area, posterior-parietal-cortex]
opens_questions: [Q-pdm-01, Q-pdm-02, Q-pdm-03, Q-pdm-04, Q-pdm-05]
source_articles: [2026-09-01-perceptual-decision-making-lip-drift-diffusion]
key_sources: ["PMID:11600651", "PMID:12417672", "PMID:17600525", "PMID:20174574", "PMID:26160947", "PMID:35915096", "PMID:37352857", "PMID:39422555", "PMID:2770878"]
---

# 感知决策 (Perceptual Decision-Making)

> **一句话定义**：大脑将随时间累积的感觉证据转化为分类选择的过程；核心神经实现是外侧顶内区（LIP）神经元沿一维决策变量流形的随机漂移扩散动力学。

## 当前理解

我们现在认为感知决策是一个**证据积累到阈值**的过程：感觉皮层（MT/V5）持续提供带噪声的感觉证据，顶叶联合皮层（LIP）将这些证据在时间上积分，当积累的证据超过决策边界时，运动系统（经上丘触发）执行选择。

这一框架的最有力支持来自随机点运动（RDM）范式：猴子判断一定比例（相干度 0–51.2%）随机点的整体运动方向，同时记录者追踪从感觉（MT）到决策（LIP）到运动（SC/眼跳系统）的完整信号链。

Steinemann et al.（2024，eLife，Neuropixels 同步记录 54-203 个 LIP 神经元）将感知决策推进到单次试验群体层面：LIP 群体活动沿一维流形（PC1 解释 44% 方差，参与比率 4.4，极低维）进行随机扩散，自相关结构与无界扩散方程精确吻合。这是迄今对漂移扩散模型神经实现最直接的实验验证。

## 关键机制

### 证据流水线：MT → LIP → SC

1. **MT/V5（感觉编码）**：方向选择性神经元对运动方向以正弦（余弦）调谐响应，编码瞬时证据。Newsome et al.（1989）MT 微电刺激的因果实验证明 MT 活动直接影响决策（Newsome/Britten/Movshon，PMID:2770878）。

2. **LIP（证据积累）**：支持选择靶点的 LIP 神经元放电率单调升高（爬坡动力学），达到固定阈值后眼跳触发。不同相干度下到达阈值的时间不同，与反应时分布精确匹配（Roitman & Shadlen 2002，PMID:12417672）。

3. **SC（决策终止）**：上丘充当阈值传感器，检测到 LIP 越过边界后爆发放电，触发眼跳。SC 失活延长 LIP 积累时间并增加反应时（Stine et al. 2023，PMID:37352857）。

### 漂移扩散模型（DDM）的神经对应

| DDM 参数 | 神经实现 | 关键证据 |
|---------|---------|---------|
| 漂移速率 μ | LIP 爬坡斜率（随相干度正相关） | Shadlen & Newsome 2001 |
| 扩散系数 σ | LIP 单次轨迹的随机波动 | Steinemann 2024 |
| 决策边界 B | LIP 阈值放电率（跨相干度一致） | Roitman & Shadlen 2002 |
| 起点偏置 z | LIP 初始放电率（奖励/先验调制） | Rorie et al. 2010 |
| 非决策时间 t₀ | 感觉延迟（~200ms） + 运动执行 | Gold & Shadlen 2007 |

### 多信号整合：感知证据 vs 奖励先验

Rorie et al.（2010，PLoS One，PMCID:PMC2824817）证明奖励和感知证据通过不同机制影响 LIP：
- **奖励**主要移动积累器**起点**（运动刺激出现前 ~100ms，LIP 放电基线即上移）
- **感知证据**改变**漂移速率**（刺激出现后 ~200ms 显现斜率差异）
- 两者时间上分离，符合贝叶斯最优先验×似然乘积的理论预期

### 决策信心编码

Zylberberg & Shadlen（2025，Cell Reports，PMID:40208792）发现 LIP 群体在反应前 100-200ms 的**协方差结构**（非均值）编码决策信心：高相干度→群体状态集中→更高信心。这为大脑自我监控的神经底物提供了直接证据。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| LIP 爬坡活动预测选择和反应时 | 猕猴 LIP 单细胞记录，RDM 任务 | PMID:11600651；PMID:12417672 | 高 |
| MT 微电刺激因果偏向决策 | MT 微电刺激 + 行为 | PMID:2770878 | 高 |
| LIP 达到固定阈值时触发眼跳 | RT 版本 RDM，阈值放电率跨相干度一致 | PMID:12417672 | 高 |
| 奖励移动起点，证据改变漂移速率 | 平衡/不平衡奖励条件，线性回归时域分解 | PMID:20174574（PMC2824817）| 高 |
| 单次试验 LIP 群体动力学匹配 DDM | Neuropixels 群体记录，1D 流形，自相关分析 | PMID:39422555（PMC11488853）| 高 |
| SC 爆发触发决策终止 | LIP+SC 同时记录，SC 失活延长 RT | PMID:37352857 | 高 |
| LIP 可能主要是空间注意图而非纯积累器 | 强迫时限任务：更强证据→更弱 LIP 分化 | PMID:35915096（PMC9343639）| 中（争议中）|
| 单次试验 LIP 神经元可被踩步模型更好描述 | 统计模型比较（爬坡 vs 踩步） | PMID:26160947 | 中（已被群体证据部分反驳）|

## 连接

- [[drift-diffusion-model]] — 感知决策的数学框架
- [[lip-area]] — 神经实现的核心脑区（外侧顶内区）
- [[mt-v5-motion-area]] — 感觉证据的来源（随机点运动）
- [[posterior-parietal-cortex]] — LIP 所在的大脑系统
- [[superior-colliculus]] — 决策终止的执行者（阈值传感器）
- [[neural-manifold]] — LIP 群体活动的一维决策变量流形
- [[dorsal-attention-network]] — DAN 是感知决策的注意门控系统
- [[value-based-decision-making]] — 与感知决策的比较（奖励整合交叉点）

## 未解问题

- Q-pdm-01（高优先级）：LIP 究竟是纯粹的证据积累器还是空间注意优先图？Seideman 2022 的强迫时限范式揭示的逆转现象如何与 Steinemann 2024 的扩散证据调和？
- Q-pdm-02（高优先级）：决策边界是 LIP 内生属性（放电最大值）还是由 SC 外部定义？Stine 2023 支持 SC 阈值传感器假说，但 LIP 内部 threshold cell 的存在仍需直接证实。
- Q-pdm-03（中优先级）：单次试验踩步动力学（Latimer 2015）在什么条件下出现？它与群体层面的扩散（Steinemann 2024）在细胞亚型层面如何调和？Tin 细胞（14.5%）是否是踩步的真实来源？
- Q-pdm-04（中优先级）：人类 hIP3（左 IPS）和猴子 LIP 的功能同源是否存在计算层面的差异？Wongtrakun 2025 的 EEG+fMRI 结合方案能否扩展到更复杂的自然场景决策？
- Q-pdm-05（低优先级）：决策信心编码（Zylberberg 2025 协方差结构）和决策变量（均值）在下游（例如前额叶、前扣带回）是否通过不同通路传输？

## 修订历史

- 2026-09-01 · 创建 · 基于《大脑如何投票：从随机点到决策信号》(#131) · 初始置信度：高

## 来源文章

- [[2026-09-01-perceptual-decision-making-lip-drift-diffusion]]

---
title: 下橄榄核
slug: inferior-olive
domain: systems
type: structure
status: established
confidence: high
created: 2026-08-08
updated: 2026-06-13
revision_count: 2
dimensions: [cellular, microcircuit, brain-region, behavior]
related: [cerebellum, climbing-fiber-error-signal, deep-cerebellar-nuclei, purkinje-cell, motor-learning, predictive-coding]
prerequisites: [cerebellum, climbing-fiber-error-signal, action-potential]
opens_questions: [Q-io-01, Q-cb-02]
source_articles: [2026-08-08-deep-cerebellar-nuclei-motor-learning-circuit]
key_sources: ["PMID:23440175", "PMID:28858616", "PMID:40848722", "PMID:30069835", "PMID:37474638"]
---

# 下橄榄核（Inferior Olive, IO）

> **一句话定义**：小脑的教师核团——位于延髓腹侧，通过对侧攀爬纤维以极稀疏放电（~1 Hz）将运动误差信号（以及可能的奖励信号）广播给浦肯野细胞，驱动 LTD 和运动学习；其缝隙连接网络、低阈值 Ca²⁺ 振荡和 TMEM16B 通道共同赋予其精密的时序计算能力。

## 当前理解

下橄榄核（inferior olive，IO）是位于延髓腹侧的一对复杂折叠结构，向对侧小脑皮层发出攀爬纤维（climbing fibers，CF）。每根 CF 与单个浦肯野细胞（PC）形成 1:1 支配关系，其激活产生 PC 的特征性**复杂放电（complex spike）**，是 Marr（1969）预言的"教师信号"的物理实现。

我们现在认为，IO 不只是误差信号的被动转发站，而是一个具有独特生物物理特性的**主动计算节点**：
- 缝隙连接（Cx36）介导的神经元间同步，确保相邻小脑微区同时接收误差信号
- 低阈值 Ca²⁺ 通道驱动的阈下振荡（~4–10 Hz），使 IO 成为具有时序门控功能的"计时器"
- TMEM16B（ANO2）氯通道调节振荡特性，影响 CF 信号的精度（Zhang et al. 2017，PMID:28858616）

2025 年新发现（Jin & Hull，PMID:40848722）提示 CF 可能不只传递误差，还传递奖励幅度信号——若证实，IO 将升格为更广义的"评价系统"（详见矛盾条目 C-2026-08-08-01）。

IO 同时接受 DCN 的抑制性反馈（经脑干中继），构成"学习完成后自动关闭"的负反馈环路。

**2023 年范式修订（Wang et al., PMID:37474638，Nature Neuroscience）**：顶核（fastigial nucleus，DCN 的一部分）除了经典抑制性投射外，还存在一条**谷氨酸能激发性投射**直达 IO 特定区域。这条**激发性核橄榄通路**在高速眼动（眼跳）期间活跃，在运动执行期主动产生有时序精度的复杂放电，参与在线调节眼动幅度和速度。这打破了"DCN 只抑制 IO"的经典教条，意味着小脑可以**主动生成自己的教师信号**（而非只被动接受外界感觉误差）——这是理解小脑自主学习能力的重要一步。目前，两条平行通路（抑制性 vs 激发性）的具体分工和时间协调机制尚不明确（见 Q-cb-06）。

## 解剖结构：三个亚核的分工

| 亚核 | 对应小脑区域 | 误差信号来源 |
|------|------------|------------|
| 主橄榄核（PO） | 小脑半球 | 感觉运动皮层下行输入 |
| 背侧副橄榄核（DAO）/背盖（dorsal cap） | 绒球（flocculus）| 视网膜滑移（视觉误差）、前庭输入 |
| 内侧副橄榄核（MAO） | 蚓部中间 | 前肢/脊髓体感输入 |

**不同小脑区域的最优 PF-CF 时间间隔不同**，与该区域所服务行为的感觉反馈延迟精确匹配：绒球区 ≈ 120ms（匹配视觉延迟，Suvrathan & Raymond 2018，PMID:30069835）。这说明不同 IO 亚核/CF 通路经演化调谐到与所服务运动系统的反馈延迟匹配。

## 关键生物物理特性

### 1. 缝隙连接同步网络（Connexin 36，Cx36）
IO 神经元之间广泛分布 Cx36 缝隙连接，使相邻细胞同步振荡并协同放电。这确保了：
- 相邻小脑微区同时接收误差信号
- CF 信号具有空间上的连贯性（而非单一 PC 的孤立事件）
Cx36 敲除导致 IO 同步性降低，相应地，精细运动学习的空间协调出现缺陷。

### 2. 阈下 Ca²⁺ 振荡（T 型 Ca²⁺ 通道）
IO 神经元在静息状态维持约 4–10 Hz 的阈下膜电位振荡，主要由 T 型钙通道介导。这使 IO 成为"相位门控"的信号处理器：只有在振荡特定相位收到输入才产生放电，赋予 IO 对误差信号的时序选择性。

### 3. TMEM16B（ANO2）氯通道
Zhang et al.（2017，Neuron，PMID:28858616）发现：
- TMEM16B 在 IO 神经元高表达（相对于其他脑区）
- IO 特异 TMEM16B KO → VOR 适应受损，但基本视觉/平衡功能正常
- 机制：TMEM16B 通过调节 Ca²⁺ 触发的 Cl⁻ 电流，精确控制 IO 振荡的时序
- 意义：IO 神经元的**离子通道组成**本身是学习精度的决定因素

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| IO → CF → 复杂放电是 LTD 诱导必要条件 | CF 选择性损毁（3-AP）→ LTD 消失 + 运动适应障碍 | PMID:7954803 | 高 |
| 最优 PF-CF 时间间隔因区域而异（绒球 ≈ 120ms）| 绒球精确间隔调控实验 | PMID:30069835 | 高 |
| IO TMEM16B KO 损害 VOR 适应 | IO 特异 KO 小鼠，VOR 测试 | PMID:28858616 | 中-高 |
| CF 信号含奖励幅度编码（不只误差）| 奖励任务 CF 记录（2025）| PMID:40848722 | 低（单篇，未复现）|
| IO 接受 DCN 抑制性反馈 | 解剖学追踪 + 电生理 | 多来源 | 高 |
| 顶核→IO 激发性（谷氨酸能）通路在眼跳中驱动有时序精度的 CF 放电 | 解剖追踪 + 光遗传激活 + 电生理 | PMID:37474638（Wang 2023，Nature Neurosci）| 高（未读取全文）|

## 连接

- [[climbing-fiber-error-signal]] — IO 是攀爬纤维的来源，误差计算在 IO 进行
- [[cerebellum]] — IO 是小脑运动学习的教师；IO-小脑轴是 Marr 算法的硬件实现
- [[purkinje-cell]] — 每个 IO 神经元通过 CF 以 1:1 方式支配一个 PC
- [[deep-cerebellar-nuclei]] — DCN 对 IO 施加抑制性反馈，形成自动"学习关闭"环路
- [[motor-learning]] — IO 是监督式运动学习的误差信号来源
- [[predictive-coding]] — IO 检测感觉预测误差是预测处理理论在小脑层面的实现

## 未解问题

- **Q-io-01**（高优先级）：CF 奖励信号（Jin & Hull 2025）是 IO 自身对奖励信息的响应，还是经由小脑-基底神经节反馈通路传入的奖励信息？其神经回路基础是什么？
- **Q-cb-02**（高优先级，共享）：IO/CF 究竟主要编码感觉预测误差（DAO/感觉输入）还是运动结果误差（MAO/运动输入）？这两类误差在 PC 侧是整合的还是分离的？
- **Q-cb-06**（新，中优先级）：激发性核橄榄通路（顶核→IO 谷氨酸能）与经典抑制性核橄榄通路如何在时间上协调？它们是在同一眼动中的不同时相激活，还是服务于不同类型的运动？

## 矛盾条目

- **C-2026-08-08-01**（open）：CF 信号传递"纯误差"（Marr 经典理论）vs CF 信号也传递"奖励幅度"（Jin & Hull 2025）。见 contested_claims.json。

## 修订历史

- 2026-08-08 · 创建 · 基于《深部核团的门与教师》（文章#107）· 初始置信度：高（IO 解剖/CF 功能 established）；CF 奖励信号（low，单篇待复现）
- 2026-06-13 · 修订（rev1→rev2）· 基于《小脑运动学习的分布式革命》（文章#186）· 新增：激发性核橄榄通路（Wang 2023，PMID:37474638）；更新当前理解说明双通路调控；新增 Q-cb-06；key_sources 补充 PMID:37474638

## 来源文章

- [[2026-08-08-deep-cerebellar-nuclei-motor-learning-circuit]]
- [[2026-06-13-cerebellar-distributed-plasticity-motor-learning]]

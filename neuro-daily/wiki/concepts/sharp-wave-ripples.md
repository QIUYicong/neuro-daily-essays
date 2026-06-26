---
title: 尖波涟漪（SWR）
slug: sharp-wave-ripples
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-29
updated: 2026-10-11
revision_count: 12
dimensions: [whole-brain-network, brain-region, cellular, microcircuit, behavior, cognition]
related: [hippocampal-circuit, place-cells, theta-oscillations, memory-consolidation, ltp, hebbian-learning, norepinephrine-locus-coeruleus, dopamine-reward-prediction-error, sleep-spindles, cortical-slow-oscillation, so-spindle-swr-coupling, ca2-hippocampus, prefrontal-cortex, pv-interneurons, slow-wave-sleep]
prerequisites: [hippocampal-circuit, synaptic-transmission, place-cells]
opens_questions: [Q-swr-reverse-forward, Q-swr-cortical-consolidation, Q-swr-large-vs-small, Q-swr-tagging-mechanism, Q-swr-human-translation, Q-pfc-suppression-selectivity, Q-inhibitory-plasticity-bounds, Q-swr-duration-mechanism-01, Q-swr-nr-substate-01]
source_articles: [2026-05-29-theta-oscillations-phase-coding, 2026-06-02-memory-consolidation-systems, 2026-06-17-sharp-wave-ripples-memory-replay, 2026-06-19-sleep-spindles-nrem, 2026-06-22-grid-cells-place-cells, 2026-07-07-sleep-memory-consolidation-so-spindle-swr, 2026-07-11-dopamine-lc-hippocampus-memory-tagging, 2026-07-16-hippocampal-replay-experience-replay, 2026-08-14-ca2-hippocampus-social-memory-temporal-context, 2026-09-22-swr-replay-selection-consolidation, 2026-09-30-swr-sleep-ltp-consolidation, 2026-10-11-swr-duration-sleep-microstructure-memory]
key_sources: ["PMID:26135716", "PMID:23354386", "PMID:34936810", "PMID:26238360", "PMID:23589831", "PMID:41205608", "PMID:38547293", "PMID:38867049", "PMID:39743590", "PMID:35040779", "PMID:19749750", "PMID:30356103", "PMID:28689981", "PMID:38443198", "PMID:31533977", "PMID:27182818", "PMID:38895442", "PMID:27593179", "PMID:38834064", "PMID:39227715", "PMID:26904941", "PMID:27840002", "PMID:37987008", "PMID:31197012", "PMID:22555434", "PMID:34001599"]
---

# 尖波涟漪（Sharp Wave-Ripples, SWR）

> **一句话定义**：海马在静息和非REM睡眠期间产生的高度同步群体事件——CA3自发群体爆发通过Schaffer侧支驱动CA1的110–200 Hz快速涟漪，同时以约20倍速压缩重播白天的场所细胞序列，是记忆从海马向新皮层转写的核心机制。

## 当前理解

我们现在认为，SWR是海马**离线模式**的核心事件，与θ振荡（在线/探索模式）在功能上互补、在时间上互斥。SWR发生时，大脑在不接收新感觉输入的情况下，主动重播和重组已编码的经历，是记忆固化（memory consolidation）的物理载体。

SWR不仅是回顾性的（重播已发生的路径），也具有前瞻性特征：有时重播动物**从未实际经历**过的路径，暗示海马具有一定程度的**规划/想象**能力（Tang & Jadhav, 2022）。

**SWR是哺乳动物大脑中最同步的群体放电模式**（Buzsáki, 2015）：一次大型SWR可招募多达50%的CA1锥体细胞，比基线状态高出约6倍的同步度。

## 关键机制

### 1. 生成：CA3自发群体爆发与 CA2 触发

SWR由**CA3庞大的循环联络系统**驱动：
- CA3拥有哺乳动物大脑中最大的循环兴奋性回路（每个锥体细胞有~12,000个CA3内部突触连接）
- 探索时，胆碱能张力（ACh）通过毒碱受体抑制CA3循环兴奋，防止自发爆发
- 在静息/睡眠中，胆碱能张力下降 → CA3循环兴奋**解放** → 自发性群体爆发 → SWR

这一过程不是"触发"，而是"释放"：胆碱能的解除是开关，CA3内在的循环动力学决定了何时和以何种顺序爆发。

**CA2 作为 SWR 的主动触发者（Oliva et al. 2016, PMID:27593179）**：高密度硅探针大鼠实验修订了上述"CA3释放模型"——约半数 SWR 实际上由 CA2 主导启动：
- CA2 "ramping cells"（约 50% CA2 锥体细胞）在 SWR 前 **20–30 ms** 斜升激发
- 随后 CA3 群体爆发，最后 CA1 涟漪；时序：CA2 → CA3 → CA1
- 光遗传激活 CA2 可**诱导人工 SWR**（直接因果证据）
- 约 20% SWR 完全**绕过 CA3**，直接经 CA2→CA1 基底树突传播
- CA2 触发效果在清醒/探索后休息时最强（不是睡眠时最强）

**修订后的 SWR 生成模型**：SWR 有两条并行触发路径——"CA3内部释放"路径和"CA2主动启动"路径。CA2 的社会记忆和时间情境信息不仅在线编码，还通过 SWR 触发决定"哪些经历被写入离线回放流程"——CA2 是记忆巩固的"优先队列调度者"（详见 [[ca2-hippocampus]]）。

### 2. 传导：CA3→CA1链路

CA3群体爆发通过**Schaffer侧支**传至CA1：
- CA1 stratum radiatum（辐射层）接受大量同步兴奋性输入
- 在CA1 pyramidal layer（锥体细胞层）产生110–200 Hz快速涟漪（ripple）
- 电流源密度（CSD）分析显示：辐射层汇（sink）与锥体层源（source）同步

涟漪的产生依赖**兴奋-抑制的精确平衡**：PV+篮细胞和其他快速抑制性中间神经元的精密介入，将锥体细胞的去极化塑形成规律的高频振荡。

### 3. 序列重播

在SWR期间，白天激活的场所细胞**按相同顺序再次激活**，但速度约为行为时的**20倍**（时间压缩）：
- 动物花5–10秒穿越的路径，在~50 ms的SWR内重播
- 不均匀分布：1.5%的细胞参与50%的SWR事件
- 同一探索轨迹可被重播多次，每次略有变形（确保多样性？）

重播存在多种方向：
- **前向重播**（forward replay）：与行为顺序相同（常见于探索暂停时）
- **反向重播**（reverse replay）：与行为顺序相反（常见于目标到达后）
- **新颖路径重播**：从未实际走过的环境路径（规划功能的可能证据）

### 4. SWR诱导LTP的突触层面机制

Sadowski, Jones & Mellor (2016, PMID:26904941, PMC4785795) 通过"体内→体外桥接"实验直接揭示了SWR重播诱导LTP的精确条件：

- **树突（非胞体）去极化是必要条件**：SWR通过Schaffer侧支给予CA1树突辐射层的同步兴奋输入，造成树突去极化，这是LTP诱导的关键——用胞体电流替代时LTP消失
- **NMDA受体依赖**：DL-AP5阻断后，即使时序完整的放电模式也不能诱导LTP；树突去极化的作用是解除NMDA受体的Mg²⁺封闭
- **时序窗口严格**：CA3先于CA1约30毫秒内的因果放电对，发生在涟漪前60%时间窗口内时，与突触强度变化相关（r²=0.89）；人工时序偏移±100毫秒显著减弱LTP
- **实验范式**：实验者从体内记录中提取真实放电时间戳，用三路刺激（Schaffer侧支→阈下EPSP + 胞体注入→动作电位 + 涟漪路径→100Hz树突刺激）在体外精确再现；4种组合中3种诱导LTP，第4种（CA3-CA1不相关）无LTP

**含义**：SWR是精密LTP诱导器，不是宽泛广播信号。它不只是"告诉大脑重播了什么"，而是主动提供了NMDA激活所需的树突去极化——这是SWR联结突触标记-捕获（STC）机制与系统层面记忆巩固的关键一环。

### 5. 记忆固化的两阶段模型

SWR在**两阶段记忆固化**中扮演关键角色（Buzsáki, 2015）：
- **第一阶段**（探索/θ态）：海马快速编码新经历；BTSP使场所场在单次穿越中写入
- **第二阶段**（静息/睡眠/SWR态）：海马高速重播，逐渐通过Hebbian突触修改在新皮层建立连接；重播次数累积，皮层突触权重逐渐增大

**关键实验**：选择性SWR中断实验（通过闭环刺激在SWR发生时立即给予干扰）损害次日空间记忆，但不损害即时记忆——直接证明SWR的因果作用（综述于 PMID:26135716）。

### 5. SWR的关键数字

- SPW（锐波）持续时间：40–100 ms（模态~50 ms）
- 涟漪频率：110–200 Hz（非REM睡眠时模态~167 Hz；清醒静息时~177 Hz）
- 非REM睡眠时发生频率：约2–4次/秒
- 清醒静息时：约1–2次/秒

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| SWR起源于CA3循环兴奋，CA1产生涟漪 | 多电极记录+CSD分析；CA3选择性破坏实验 | PMID:26135716 | 高 |
| SWR期间场所细胞序列以~20倍速重播 | 多单元记录+序列比较分析（Bayesian解码） | PMID:26135716；PMID:34936810 | 高 |
| 选择性SWR中断损害空间记忆（闭环电刺激） | 闭环刺激（检测SWR触发干扰）+行为 | PMID:19749750 | 高（因果） |
| SWR存在前向、反向和新颖路径重播 | 多单元记录+时空轨迹解码 | PMID:34936810 | 高 |
| CA3学习突触结构同时决定SWR生成和重放内容 | 数据驱动CA3计算模型 + STDP规则比较 | PMID:35040779 (eLife开放) | 中（模型预测） |
| 只有大振幅SWR亚集与海马-PFC同步再激活相关 | 多区域记录 + SWR振幅分类 | PMID:41205608 | 中-高（新发现） |
| 光遗传增强SWR振幅改善记忆（因果） | 闭环光遗传 + 行为测试 | PMID:41205608 | 中-高（因果证据，鼠类） |
| 清醒SWR标记特定经历供睡眠优先重放 | 大规模群体记录 + 降维分析 | PMID:38547293 | 中（新发现，需独立验证） |
| 睡眠剥夺：SWR仍发生但振幅降低，重放效率下降 | 睡眠剥夺鼠类记录 + 序列解码 | PMID:38867049 | 高（分离证据） |
| NREM睡眠微结构（NE/瞳孔状态）区隔新旧记忆重放 | CA1大规模记录 + 瞳孔追踪 | PMID:39743590 | 中（新发现） |
| 情绪效价也在SWR期间重播 | 联合情绪学习+SWR记录 | PMID:31334590 | 中（新兴） |
| 闭环增强 SO-纺锤波-SWR 三重耦合 → 隔天空间记忆改善（因果） | 大鼠 NREM 闭环刺激，对照组（非同步刺激）无效 | PMID:27182818 | 高（因果） |
| VTA 失活在新颖（非熟悉）环境中破坏 SWR 空间重播位置选择性 | VTA 化学失活 + 多单元记录 + 空间解码 | PMID:38895442 | 中（新颖度依赖性分工值得关注）|
| CA2 ramping cells 在 SWR 前 20–30ms 先行激发；光遗传激活 CA2 诱导人工 SWR | 大鼠高密度硅探针 CA2+CA3+CA1 同步记录；光遗传激活 CA2 | PMID:27593179 | 高（因果+高时间分辨率，Neuron 发表）|
| PFC 独立涟漪（71.2%）期间 CA1 被显著抑制，后续再激活量降低（r=−0.71） | CA1+PFC 同步多电极记录 + 涟漪分类分析 | Shin & Jadhav 2024, PMID:38834064 | 高 |
| 抑制性突触对干扰细胞权重高 38.9%；SWR 驱动对称性抑制性 STDP | 全细胞膜片钳 + 光遗传 + 大样本统计 | Liao et al. 2024, PMID:39227715 | 高 |
| SWR诱导NMDA依赖性LTP需树突（非胞体）去极化；CA3→CA1因果时序r²=0.89 | 体内多电极→体外全细胞膜片钳三路刺激（"虚拟重播"）；DL-AP5对照 | Sadowski et al. 2016, PMID:26904941 (PMC4785795) | 高 |
| 渐强型细胞集成体（而非早稳型）依赖SWR离线重激活；选择性光遗传SWR抑制仅损害渐强型 | 大鼠CA1多电极 + 闭环光遗传SWR抑制 + 上下文重暴露测试 | van de Ven et al. 2016, PMID:27840002 (PMC5158132) | 高（因果） |
| 清醒SWR内容预测睡眠重播优先级（R=0.86, P<10⁻³⁶）；漂移种群编码记录试次信息 | 超大规模多电极（>150神经元）+ UMAP/seqNMF降维分析 | Yang & Buzsáki 2024, PMID:37987008 (PMC10659301) | 中-高（关联性） |
| 清醒态 SWR 干扰导致特异性空间学习缺陷（不影响场所细胞整体表征） | 大鼠空间交替任务 + 闭环清醒 SWR 干扰（不干扰睡眠 SWR） | Jadhav et al. 2012, PMID:22555434 | 高（因果，功能分离） |
| 长时程 SWR（>150 ms）比短 SWR 携带更完整的场所细胞序列；光遗传延长 SWR → 迷宫学习加快 | 大鼠 CA1/CA3 多电极记录 + 光遗传延长 SWR 时长（不改变时机） | Fernández-Ruiz et al. 2019, PMID:31197012 (PMC11068097) | 高（因果，行为） |
| 人类 SWR-慢波耦合预测同侧皮层激活（61.4% 耦合位点激活 vs 16.2% 对照） | 人类癫痫患者颅内多区域记录（海马+杏仁核+多皮层） | Skelin et al. 2021, PMID:34001599 | 中-高（人类直接证据；未读取全文） |

## 连接

- [[theta-oscillations]] — SWR（静息/睡眠）与θ（探索）互斥：海马的两种工作模式
- [[hippocampal-circuit]] — CA3循环系统生成SWR；CA1通过Schaffer侧支产生涟漪
- [[place-cell]] — SWR期间场所细胞序列被高速重播
- [[memory-consolidation]] — SWR是海马→新皮层记忆巩固的物理机制
- [[so-spindle-swr-coupling]] — SWR 是三重耦合的"载荷"，嵌套在纺锤波波谷，将压缩记忆序列写入皮层
- [[ltp]] — SWR重播可能通过反复激活强化海马-皮层突触（LTP机制）
- [[hebbian-learning]] — SWR重播序列中前后神经元的同步激活可能触发Hebbian型突触修改
- [[ca2-hippocampus]] — CA2 是 SWR 的主要触发者；~50% SWR 由 CA2 ramping cells 在 SWR 前 20–30ms 启动；约 20% SWR 完全绕过 CA3 直接经 CA2→CA1 传播

## 新发现（2024-2026）

### 大振幅SWR亚集的特殊地位（Robinson et al. 2026）

Robinson等（2026，PMID:41205608）的多区域记录发现，SWR并非均质——只有**大振幅SWR子集**与海马和前额叶皮层（PFC）的同步记忆再激活相关。学习新内容后，这类大型SWR的出现频率选择性增加。关键因果证据：闭环光遗传增强SWR振幅→海马-PFC再激活增强 + 记忆改善。这一发现解释了Giri等（2024）的"睡眠剥夺悖论"——剥夺睡眠时SWR仍出现但振幅降低，重放效率下降。**SWR振幅是功能区分的关键维度，不只是"有SWR"就够。**

### 清醒SWR的记忆标记功能（Yang et al. 2024）

Yang等（2024，PMID:38547293）揭示，清醒探索时SWR选择性在部分经历后出现，其尖峰内容编码周围试次的神经表征（"标记"），被标记的经历在随后睡眠中被优先重放。这表明**记忆的优先级选择不只在睡眠中发生——清醒SWR本身就是一种主动标记机制**。

### 睡眠微结构防止新旧记忆干扰（Chang et al. 2025）

Chang等（2025，PMID:39743590）发现NREM睡眠中瞳孔收缩期（NE低）专门重放近期记忆，瞳孔扩张期（NE较高）优先重放陈旧记忆。这种分时机制使大脑在同一夜内既能巩固新经历又不破坏旧记忆——**睡眠是精密调度的多记忆多路复用系统，不是均匀处理窗口**。

### 前额叶主动抑制门控（Shin & Jadhav 2024）

Shin & Jadhav（2024, PMID:38834064）揭示，PFC 在睡眠固化中**并非被动接收者**，而是主动参与选择的门控器：
- 71.2% 的 PFC 涟漪为"独立涟漪"（与 CA1 SWR 不同步），在此期间 CA1 锥体细胞和中间神经元被显著抑制（P = 1.37×10⁻⁹）
- 这种 PFC 主动抑制与后续 CA1 再激活量呈**强负相关**（r = −0.71，P = 4.25×10⁻⁸⁷）
- 意味着 PFC 通过"否决"机制参与记忆选择：它不只接受海马传来的内容，还在清除"不值得固化"的神经模式

**修订了什么**：经典 CLS 模型将固化视为"海马→皮层的单向传输"；此发现表明固化是**双向对话**，前额叶的主动反馈是回路的必要组成部分。

### 抑制性可塑性驱动统计抽象（Liao 2024）

Liao 等（2024, PMID:39227715）的发现表明 SWR 期间发生的可塑性不只是兴奋性的：
- 经历后，CA1 抑制性突触（PV+篮细胞→锥体细胞）对"干扰细胞"的权重比对"场所细胞"高 38.9%（P = 2.5×10⁻¹⁸⁷）
- 这种抑制性 STDP 在 SWR 期间选择性强化对非相关神经元的抑制
- 结果：回放序列不是精确的录像重演，而是对任务相关结构的**统计提炼**
- 这为记忆泛化（而非死记硬背）提供了细胞层面的机制

**修订了什么**：此前理解中，SWR 重播机制聚焦于兴奋性序列再激活；此发现将抑制性可塑性纳入核心机制，SWR 系统同时是"放大器"（放大相关信号）和"滤波器"（压制干扰）。

### CA3突触结构双重决定（Ecker et al. 2022）

Ecker等（2022，PMID:35040779，eLife开放）的CA3计算模型表明，学习依赖的突触权重结构（对称STDP）既决定重放内容也决定SWR能否产生。对称STDP→前向+逆向重放；非对称STDP→仅前向。**"学什么"和"重放什么"共用同一张突触地图。**

## 未解问题

- Q-swr-reverse-forward：前向重播、反向重播、新颖路径重播分别在何种条件下产生？是否对应不同的认知功能（强化 vs. 规划 vs. 泛化）？
- Q-swr-cortical-consolidation：SWR期间海马的信号如何精确地在新皮层留下持久印记？是Schaffer-皮层的直接突触修改，还是通过下丘脑/脑干/睡眠调节因子介导？
- Q-swr-large-vs-small：是什么决定了一次SWR的振幅（大 vs 小）？CA3群体爆发规模、CA1 PV细胞同步度、局部兴奋-抑制平衡的作用分别是什么？睡眠剥夺如何精确降低SWR振幅？
- Q-swr-tagging-mechanism：清醒SWR是什么触发了对特定经历的选择性"标记"？DA/NE的角色？与奖励系统（VTA）的连接是必要的吗？**部分进展（2026-07-11）**：Igata 2024（PMID:38895442）直接证明 VTA 在新颖（非熟悉）环境中调控 SWR 重播的空间位置选择性（不影响 SWR 频率）——VTA DA 信号决定"重播哪里"。但 VTA→SWR 选择的机制（直接 DA 投射？还是间接通路？）仍未明。LC-DA 在清醒 SWR 触发中的角色仍完全未探索。
- Q-swr-human-translation：大振幅SWR的特殊功能是否在人类中也成立？颅内电极研究能否提供类似证据？

## 修订历史

- 2026-09-30 · 修订 rev11 · 基于《睡眠中的最后一步》(#160) · 新增"SWR诱导LTP的突触层面机制"小节（Sadowski 2016：树突去极化+NMDA依赖性，r²=0.89时序关联）；证据表新增3行（Sadowski 2016, van de Ven 2016, Yang & Buzsáki 2024）；key_sources新增PMID:26904941/27840002/37987008；source_articles新增2026-09-30
- 2026-05-29 · 创建 · 基于《θ振荡与相位编码》文章 · 填补了 memory-consolidation 悬空引用 · 初始置信度：高
- 2026-06-02 · 修订 · 基于《记忆的夜间旅行》文章 · [[memory-consolidation]] 页面已建立；补充 SO-spindle-SWR 三重奏嵌套机制与因果破坏证据 · 关键来源增加 PMID:26238360、PMID:23589831
- 2026-06-17 · 修订 · 基于《夜晚，大脑重写自己的神经地图》文章 · 新增4个关键新发现（Robinson 2026大型SWR因果证据、Yang 2024清醒SWR标记、Giri 2024睡眠剥夺分离、Chang 2025睡眠微结构）、Ecker 2022 CA3模型；扩充证据表（+6行）；新增"新发现"小节；新增3个未解问题；related新增norepinephrine-locus-coeruleus和dopamine-reward-prediction-error
- 2026-06-22 · 修订 · 修正悬空引用：place-cell→place-cells；source_articles新增2026-06-22 · 基于《六边形的秘密》文章
- 2026-06-19 · 修订 · 基于《当大脑钟声响起》文章 · related新增sleep-spindles和cortical-slow-oscillation（SWR作为SO-spindle-SWR三重奏的第三层）；key_sources扩充3个（Latchoumane 2017三重耦合因果、Staresina 2024综述、Jiang 2019人类颅内验证）；source_articles新增2026-06-19
- 2026-07-07 · 修订 · 基于《三重协奏》文章(#75) · 新增 Maingret 2016 闭环刺激因果证据（PMID:27182818）；related 新增 so-spindle-swr-coupling；connections 增加三重耦合页面链接
- 2026-07-11 · 修订 rev7 · 基于《当蓝斑充当"新奇探测器"》(#79) · 证据表新增1行（Igata 2024，VTA调制新颖环境SWR空间重播选择性）；Q-swr-tagging-mechanism 部分进展更新；key_sources新增PMID:38895442；source_articles新增2026-07-11
- 2026-07-16 · 修订 rev8 · 基于《记忆的时光机》(#84) · 新增 Mattar-Daw Need×Gain 规范化理论（PMID:30349103）：SWR 回放内容的前向/反向方向和时机由 Need（未来访问频率）× Gain（策略改善幅度）决定，统一解释 6 条经验规律；新增 hippocampal-replay wiki 页（本页 implements [[hippocampal-replay]]）；source_articles 新增 2026-07-16
- 2026-08-14 · 修订 rev9 · 基于《CA2：海马遗忘的第三元件》(#113) · 修订 SWR 生成模型：增加 CA2 主动触发路径（~50% SWR 由 CA2 ramping cells 在 SWR 前 20–30ms 启动；~20% SWR 绕过 CA3 直接经 CA2→CA1 传播）；新增 Oliva 2016 光遗传因果证据（PMID:27593179）；连接新增[[ca2-hippocampus]]；证据表新增1行；related新增ca2-hippocampus；key_sources新增PMID:27593179
- 2026-09-22 · 修订 rev10 · 基于《记忆的裁判官》(#152) · "新发现"小节新增两个：(1) PFC 主动抑制门控（Shin & Jadhav 2024，独立涟漪 71.2% 抑制 CA1，r=−0.71）；(2) 抑制性可塑性驱动统计抽象（Liao 2024，抑制权重对干扰细胞高 38.9%）；证据表新增 2 行；related 新增 prefrontal-cortex, pv-interneurons；opens_questions 新增 Q-pfc-suppression-selectivity, Q-inhibitory-plasticity-bounds；key_sources 新增 PMID:38834064, PMID:39227715
- 2026-10-11 · 修订 rev12 · 基于《时长与时机》(#171) · 证据表新增 3 行：(1) Jadhav 2012（清醒态 SWR 干扰导致特异性学习缺陷，功能分离因果证据）；(2) Fernández-Ruiz 2019（长 SWR 信息容量优势 + 光遗传延长改善记忆，PMC11068097 开放全文）；(3) Skelin 2021（人类颅内 SWR-慢波耦合预测皮层激活，61.4% vs 16.2%）；related 新增 slow-wave-sleep；opens_questions 新增 Q-swr-duration-mechanism-01, Q-swr-nr-substate-01；key_sources 新增 PMID:31197012, PMID:22555434, PMID:34001599；source_articles 新增 2026-10-11-swr-duration-sleep-microstructure-memory

## 来源文章

- [[2026-05-29-theta-oscillations-phase-coding]]
- [[2026-06-02-memory-consolidation-systems]]
- [[2026-06-17-sharp-wave-ripples-memory-replay]]
- [[2026-07-11-dopamine-lc-hippocampus-memory-tagging]]
- [[2026-07-16-hippocampal-replay-experience-replay]]
- [[2026-08-14-ca2-hippocampus-social-memory-temporal-context]]
- [[2026-09-30-swr-sleep-ltp-consolidation]]
- [[2026-10-11-swr-duration-sleep-microstructure-memory]]

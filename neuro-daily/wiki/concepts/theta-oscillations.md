---
title: θ振荡
slug: theta-oscillations
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-29
updated: 2026-07-07
revision_count: 6
dimensions: [whole-brain-network, brain-region, cellular, behavior, methods]
related: [place-cells, grid-cells, hippocampal-circuit, ltp, btsp, sharp-wave-ripples, theta-phase-precession, memory-consolidation, rem-sleep, fear-extinction, emotional-memory-depotentiation, path-integration, entorhinal-cortex, theta-gamma-coupling, working-memory, gamma-oscillations, septohippocampal-cholinergic, medial-septum]
prerequisites: [action-potential, hippocampal-circuit, place-cells]
opens_questions: [Q-theta-primate, Q-theta-btsp-coordination, Q-theta-sufficiency-memory, Q-rem-01, Q-rem-03, Q-rem-05]
source_articles: [2026-05-29-theta-oscillations-phase-coding, 2026-05-31-rem-sleep-emotional-memory, 2026-06-22-grid-cells-place-cells, 2026-07-21-theta-gamma-coupling-working-memory, 2026-06-29-acetylcholine-hippocampal-memory-gate, 2026-07-07-medial-septum-theta-pacemaker]
key_sources: ["PMID:23354386", "PMID:26135716", "PMID:37720546", "PMID:8353611", "PMID:28729826", "PMID:27174984", "PMID:19702380", "PMID:39721980", "PMID:35926456", "PMID:19553449", "PMID:15456820", "PMID:25982367", "PMID:26961955", "PMID:3185735"]
---

# θ振荡 (Theta Oscillations)

> **一句话定义**：海马局部场电位中4–12 Hz的正弦波节律，在动物主动探索时出现，由内侧隔核（MS-DBB）驱动，为场所细胞的相位编码、θ序列压缩和突触可塑性窗口提供时间组织框架。

## 当前理解

我们现在认为，θ振荡不只是海马活动的背景节律，而是**时间组织的核心基础设施**。它决定神经元**何时放电**（以相位为参照），而非直接编码**什么信息**。

θ振荡的关键特性：
- **频率**：4–12 Hz（大鼠探索时约8–10 Hz）；人类海马也有类似θ成分，但节律性较弱
- **状态依赖**：探索/运动/快速眼动睡眠时出现；静止、非REM睡眠时消失（被SWR取代）
- **空间分布**：贯穿海马全长（DG/CA3/CA1）和相邻内嗅皮层

θ振荡的功能通过两个核心现象体现：
1. **相位前进（phase precession）**：场所细胞的放电相位随位置系统性移动，实现速率+相位的双重编码
2. **θ序列**：单个θ周期（120 ms）内多个场所细胞顺序放电，将行为时间尺度的路径压缩为时间序列

θ振荡打断后（MS-DBB病变），动物的空间记忆显著受损，但场所细胞的位置选择性大体保留——说明θ携带的是**时间框架**，而非空间表征本身（Etter et al., 2023）。

θ振荡不只出现于探索状态，也在**REM睡眠**中持续存在，且发挥截然不同的功能。REM θ的频率与清醒θ相近（4–8 Hz），但功能情境发生根本转换：从主动路径导航转换为**离线情绪记忆巩固**。Totty等人（2017，PMID:28729826）发现，恐惧消退训练后的REM睡眠中，外侧杏仁核（LA）与腹侧海马（VH）之间的θ振荡**相位差**（约180°反相）与次日消退记忆质量的相关系数高达R=0.954——这表明REM θ的相位关系直接编码情绪记忆巩固质量，而非仅仅是神经元活动的旁观相关物。Boyce等人（2016，PMID:27174984）的光遗传实验确立了因果关系：选择性沉默REM睡眠期间（而非非REM）的内侧隔核GABA神经元，可消除REM θ并损害情境记忆——证明REM期θ是记忆巩固的**必要条件**。

## 关键机制

### 1. 起搏器：内侧隔核–斜角带（MS-DBB）

θ节律的主要驱动来自内侧隔核（Medial Septum, MS）和斜角带（Diagonal Band of Broca, DBB）——完整的三细胞分工机制与因果证据见专页[[medial-septum]]，此处仅概述：

- **GABAergic 投射（相位）**：PV+起搏神经元选择性投射至海马PV+抑制性中间神经元 → 节律性去抑制 → 锥体细胞θ节律性去极化 → 锥体细胞再受抑 → 循环振荡。这些起搏神经元并非同步放电的单一整体，而是通过局部轴突返侧支相互耦合，类似惠更斯摆钟的自发同步机制拉齐频率，并分裂为两个反相位（~178°/~330°）簇群（Kocsis 2022, PMID:35926456；Borhegyi 2004, PMID:15456820）。在体记录显示这些神经元放电领先海马场电位约79ms，形成清晰的因果时序梯度（Hangya 2009, PMID:19553449）。
- **谷氨酸能投射（频率）**：VGluT2+神经元提供张力性兴奋，其活动强度与运动速度、θ频率线性耦合；光遗传学证实节律性激活这些神经元胞体足以在6–10 Hz范围内精确牵引θ频率（Fuhrmann 2015, PMID:25982367；Robinson 2016, PMID:26961955）。
- **胆碱能（ACh）投射**：提供长效调制，影响海马整体兴奋性和θ振荡的稳定性，详见[[septohippocampal-cholinergic]]

内嗅皮层和CA3的内在回路也参与，使θ不是单中心广播，而是**分布式共振网络**。

### 2. 相位前进（Phase Precession）

场所细胞的放电相位在动物穿越场所场时系统性地"前进"（O'Keefe & Recce, 1993）：
- 进入场所场：放电在θ**晚期**相位（近波峰）
- 中途：放电在θ**中期**相位
- 离开场所场：放电在θ**早期**相位（近波谷）
- 总位移约 100–355°；与位置强相关，与时间弱相关

机制解释有两种竞争模型：
- **振荡干涉模型**（Burgess et al.）：细胞内在振荡频率略高于背景θ，两者干涉产生相位漂移
- **双路径输入模型**（Chance 2012）：CA3（晚相位到达）和EC3（早相位到达）顺序激活CA1

### 3. θ序列（Theta Sequences）

在单个θ周期（约120 ms）内：
- **早期相位**放电 → 代表当前位置**前方**（未来）
- **中期相位**放电 → 代表**当前位置**
- **晚期相位**放电 → 代表当前位置**后方**（过去）

时间压缩比约20:1；行为尺度的路径（数秒）压缩进θ周期（120 ms）。这是大脑实时运行的**预测性前向推断**：每次θ振荡，海马都在预演紧接下来的路径。

### 4. θ/γ嵌套（Theta-Gamma Nesting）

每个θ周期（约125 ms）内嵌套约5–8个γ振荡（40–80 Hz）子循环。θ-γ跨频率耦合（CFC）是工作记忆多项目维持的核心节律机制，有两层含义：

**容量分格（Lisman-Idiart 1995）**：每个γ子周期通过活动依赖后去极化（ADP）维持一项记忆，θ/γ比率决定容量上限≈4–6项（生理γ频率下）。人类颅内记录（Axmacher 2010, PMID:20133762）证实，海马中PAC随工作记忆项数增加而增强，且个体PAC精度预测WM容量。Wolinski 2018（PMID:29538384）进一步证明：个体顶叶θ频率越慢，WM容量越大——直接验证了容量 = θ周期时长 × γ频率的定量预测。

**双通道路由（Colgin 2009, PMID:19924214）**：CA1中γ分裂为两个频率通道：
- 慢γ（25–50 Hz，θ波峰约180°）→ 相位锁定CA3输入（存储的自联想记忆）
- 快γ（65–140 Hz，θ波谷约0°/360°）→ 相位锁定MEC输入（当下感觉信息）
- 同一神经基质通过θ相位实现时分多路复用：预期（CA3）与感知（MEC）在每个θ周期内交替在线

详细机制见 [[theta-gamma-coupling]] 独立页面。跨频率耦合（PAC）的强度与记忆表现相关（人类和啮齿类一致）。

### 5. REM睡眠θ：情绪记忆巩固的相位窗口

清醒θ与REM θ共享频段，但功能情境不同：

| 特征 | 清醒θ | REM θ |
|------|-------|-------|
| 功能状态 | 主动探索、导航 | 离线，眼球快速运动 |
| 核心功能 | 相位编码、θ序列 | 情绪记忆离线巩固 |
| 关键脑区间同步 | CA3-CA1-EC（空间回路） | LA-VH（情绪-情境回路） |
| 决定性的相位关系 | 场所细胞相位前进 | LA-VH约180°反相 |
| 可塑性结果 | LTP/BTSP（编码） | 去增强/消退记忆巩固 |

**LA-VH θ同步机制**：REM睡眠中，LA与腹侧海马（VH）之间的θ振荡维持特定相位关系。Totty（2017）测量的"约180°反相"与清醒状态下两区域的同相激活形成鲜明对比。这种反相激活被认为反映了情绪记忆痕迹的"去耦合"——削弱记忆的情感色彩同时保留事实内容（与Walker的SFSR假说一致）。

**因果链**：MS GABA神经元节律性抑制 → 海马PV+中间神经元去抑制 → θ振荡驱动 → REM期维持LA-VH θ同步 → 情绪记忆去饱和化。Boyce 2016通过在REM睡眠（而非NREM）期间光遗传激活MS GABA神经元以打乱θ，证明了MS-θ-记忆这条因果链。

### 6. θ与BTSP的协调（新假说）

Etter et al.（2023）提出：θ振荡可能通过协调树突膜电位振荡的时机，使特定输入更容易触发**树突钙平台电位**（BTSP的触发器）。如果成立，θ不只是记录时间的时钟，也是主动创造BTSP"机会窗口"的调制机制。

### 7. SPEAR 模型：ACh 调控θ相位编码/提取分离（Hasselmo 2025）

Hasselmo（2025，PMID:39721980）提出的 **SPEAR 模型**（Separate Phases of Encoding And Retrieval）将θ相位功能与编码/提取的计算需求正式绑定：

| θ相位 | 计算功能 | 网络状态 |
|------|---------|---------|
| θ 波谷（下降相） | 编码相——新信息写入 | EC 传入强；CA3 回返侧支被 ACh 抑制（弱）；LTP 有利 |
| θ 波峰（上升相） | 提取相——已存储记忆激活 | CA3 回返强（EC 弱）；LTD 倾向 |

每 ~125 ms 切换一次（8 Hz θ 频率下）。同一 Hebbian 规则无法同时服务编码（需弱回返）和提取（需强回返），因此相位分离是解决"干涉问题"的必要计算策略。

**双时间尺度 ACh/GABA 分工**：
- **ACh 慢时间尺度（秒-分钟）**：MSDB 胆碱能投射设定全局状态偏向（清醒探索高 ACh → 编码模式主导；休息/睡眠低 ACh → SWR 主导）
- **GABA 快时间尺度（<2s）**：MSDB PV+GABA 神经元执行每θ周期内的编码↔提取快速切换

**证据支撑**：Rogers & Kesner（2004）行为药理学双重解离（CA3 scopolamine→编码受损；physostigmine→提取受损）为此模型提供独立行为证据；Kremin & Hasselmo（2007）层选择性电生理证据（CA3 回返被 ACh 选择性抑制 > EC 传入）与之一致；场所细胞相位前进（进入场所场：提取相激活旧记忆 → 离开：编码相写入新信息）在行为层面呼应该模型。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| θ振荡在探索时出现，频率4–12 Hz | 大鼠海马多电极LFP记录 | PMID:23354386 综述 | 高 |
| 相位前进现象（100–355°位移） | 大鼠线性轨道单单元记录+LFP | PMID:8353611 | 高（经典；被多个实验室重复） |
| MS-DBB病变消除θ→记忆受损，但空间调谐保留 | MS-DBB病变+迷宫实验+单单元记录 | PMID:37720546 综述 | 高 |
| θ/γ嵌套，每θ包含5–9个γ | 大鼠海马多频段LFP记录 | PMID:23354386；PMID:18559405 | 高 |
| 人类θ-γ耦合与工作记忆表现相关 | 颅内电极记录（神经外科患者） | PMID:23354386 综述 | 中（人类数据少） |
| θ是记忆的必要条件，但非充分条件 | MS-DBB光遗传沉默+行为 | PMID:37720546 | 中-高 |
| LA-VH θ相位差（~180°）预测消退记忆质量（R=0.954） | 大鼠恐惧消退后REM睡眠LFP同步记录 | PMID:28729826 | 高 |
| 沉默REM期间MS GABA神经元→θ消失→情境记忆受损 | 光遗传操控（仅REM期，精确时控） | PMID:27174984 | 高（因果） |
| θ波谷=编码相（EC强/CA3弱/LTP有利），θ波峰=提取相（CA3强/EC弱）；ACh 慢时间尺度设定全局状态偏向 | SPEAR模型综合：行为药理学双重解离+脑片电生理层选择性+场所细胞相位前进 | Hasselmo 2025, PMID:39721980 | 中高（整合理论；多项独立预测待闭环光遗传因果验证）|

## 连接

- [[place-cell]] — 场所细胞的相位前进是θ相位编码的直接体现
- [[phase-precession]] — θ振荡的核心功能现象：场所细胞放电相位随位置移动
- [[hippocampal-circuit]] — θ协调CA3/CA1/EC三向通信的时间框架
- [[sharp-wave-ripples]] — θ（探索）与SWR（静止）是海马两种互斥的工作模式
- [[grid-cell]] — 内嗅皮层网格细胞也显示θ相位前进；振荡干涉模型解释网格图案
- [[ltp]] — θ振荡的体内诱导节律（theta-burst stimulation是标准LTP诱导方法）
- [[btsp]] — θ可能协调BTSP所需的树突平台电位触发时机
- [[memory-consolidation]] — θ态（编码）与SWR态（固化）是记忆形成的两个阶段
- [[rem-sleep]] — REM睡眠中θ振荡持续活跃，驱动情绪记忆的离线巩固；REM θ是清醒θ功能的情景变体
- [[fear-extinction]] — LA-VH θ相位差（约180°）预测消退记忆质量，REM θ同步是消退记忆巩固的神经底物
- [[emotional-memory-depotentiation]] — REM θ振荡的功能结果之一：通过LA-VH去耦合，减弱情绪记忆的情感色彩
- [[septohippocampal-cholinergic]] — MSDB 胆碱能投射是 SPEAR 模型"ACh 慢时间尺度偏向"的分子底物：高 ACh 将θ节律的全局偏向设定为编码模式，低 ACh 允许 SWR 主导的固化模式

## 未解问题

- Q-theta-primate：灵长类海马缺乏θ节律性放电，是替代机制（工作记忆α？）还是功能保守？
- Q-theta-btsp-coordination：θ振荡是否直接协调BTSP所需平台电位的触发时机？
- Q-theta-sufficiency-memory：单纯增强θ频率或功率是否能改善记忆？阿尔茨海默病中恢复θ-γ耦合是否有治疗价值？
- Q-rem-01：REM睡眠中LA-VH θ同步的精确细胞机制是什么？哪些突触和回路层级负责维持约180°反相？
- Q-rem-03：θ相位反转假说（峰值→谷值触发LTD）是否适用于REM期LA-VH同步中的具体突触？
- Q-rem-05：人工增强REM θ同步（通过经颅刺激或光遗传）是否能加速或改善情绪记忆的去饱和化？

## 修订历史

- 2026-05-29 · 创建 · 填补高优先级悬空引用（由 place-cell、ltp、hippocampal-circuit、grid-cell 引用） · 基于《θ振荡与相位编码》文章 · 初始置信度：高
- 2026-06-22 · 修订 · 修正悬空引用：place-cell→place-cells、grid-cell→grid-cells、phase-precession→theta-phase-precession；新增related条目：path-integration、entorhinal-cortex；source_articles新增2026-06-22 · 基于《六边形的秘密》文章
- 2026-07-21 · 修订 · 大幅扩充θ/γ嵌套机制节（Lisman-Idiart 1995容量分格 + Colgin 2009双通道路由，引入关键证据）；新增related: theta-gamma-coupling, working-memory, gamma-oscillations；source_articles增加2026-07-21 · 基于《海马的节律钟表》文章 #89
- 2026-05-31 · 修订 · 整合REM睡眠θ内容：新增「REM睡眠θ：情绪记忆巩固的相位窗口」机制节（LA-VH θ相位差、Boyce 2016光遗传因果证据、清醒/REM θ功能对比表）；补充当前理解段落；关键证据表增加2行；连接增加rem-sleep/fear-extinction/emotional-memory-depotentiation；未解问题增加Q-rem-01/Q-rem-03/Q-rem-05 · 基于《REM睡眠与情绪记忆》文章
- 2026-06-29 · 修订 rev5 · 基于《乙酰胆碱的双重使命》文章 · 新增「SPEAR 模型」机制节（θ相位编码/提取功能分离，双时间尺度 ACh/GABA 分工，Hasselmo 2025）；证据表新增1行（PMID:39721980）；连接新增 [[septohippocampal-cholinergic]]；related 新增 septohippocampal-cholinergic；key_sources 新增 PMID:39721980；source_articles 新增 2026-06-29
- 2026-07-07 · 修订 rev6 · 基于《谁在给记忆打拍子：内侧隔核如何用起搏神经元合奏出海马θ振荡》· "起搏器"小节从概述扩展为GABA能（相位）/谷氨酸能（频率）/胆碱能（模式切换）三细胞分工模型，新增惠更斯同步机制、反相位簇群、79ms因果时序梯度等细节；新增 [[medial-septum]] 专页连接（related、prerequisites层面）；key_sources新增6个PMID；source_articles新增2026-07-07

## 来源文章

- [[2026-05-29-theta-oscillations-phase-coding]]
- [[2026-05-31-rem-sleep-emotional-memory]]
- [[2026-06-29-acetylcholine-hippocampal-memory-gate]]
- [[2026-07-07-medial-septum-theta-pacemaker]]

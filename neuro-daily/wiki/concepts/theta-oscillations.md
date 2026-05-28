---
title: θ振荡
slug: theta-oscillations
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-29
updated: 2026-05-29
revision_count: 1
dimensions: [whole-brain-network, brain-region, cellular, behavior, methods]
related: [place-cell, grid-cell, hippocampal-circuit, ltp, btsp, sharp-wave-ripples, phase-precession, memory-consolidation]
prerequisites: [action-potential, hippocampal-circuit, place-cell]
opens_questions: [Q-theta-primate, Q-theta-btsp-coordination, Q-theta-sufficiency-memory]
source_articles: [2026-05-29-theta-oscillations-phase-coding]
key_sources: ["PMID:23354386", "PMID:26135716", "PMID:37720546", "PMID:8353611"]
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

## 关键机制

### 1. 起搏器：内侧隔核–斜角带（MS-DBB）

θ节律的主要驱动来自内侧隔核（Medial Septum, MS）和斜角带（Diagonal Band of Broca, DBB）：

- **GABAergic 投射**：以θ频率节律性地抑制海马的PV+抑制性中间神经元 → 去抑制 → 锥体细胞θ节律性去极化 → 锥体细胞再受抑 → 循环振荡
- **胆碱能（ACh）投射**：提供长效调制，影响海马整体兴奋性和θ振荡的稳定性

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

每个θ周期内嵌套5–9个γ振荡（30–80 Hz）周期：
- 每个γ周期（10–30 ms）对应一个细胞集合的同步活动窗口
- 一个θ周期可承载5–9个独立的信息单元（位置/记忆项目）
- γ周期的时间尺度与STDP可塑性窗口匹配
- 跨频率耦合（theta-gamma CFC）的强度与记忆表现相关（人类和啮齿类一致）

### 5. θ与BTSP的协调（新假说）

Etter et al.（2023）提出：θ振荡可能通过协调树突膜电位振荡的时机，使特定输入更容易触发**树突钙平台电位**（BTSP的触发器）。如果成立，θ不只是记录时间的时钟，也是主动创造BTSP"机会窗口"的调制机制。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| θ振荡在探索时出现，频率4–12 Hz | 大鼠海马多电极LFP记录 | PMID:23354386 综述 | 高 |
| 相位前进现象（100–355°位移） | 大鼠线性轨道单单元记录+LFP | PMID:8353611 | 高（经典；被多个实验室重复） |
| MS-DBB病变消除θ→记忆受损，但空间调谐保留 | MS-DBB病变+迷宫实验+单单元记录 | PMID:37720546 综述 | 高 |
| θ/γ嵌套，每θ包含5–9个γ | 大鼠海马多频段LFP记录 | PMID:23354386；PMID:18559405 | 高 |
| 人类θ-γ耦合与工作记忆表现相关 | 颅内电极记录（神经外科患者） | PMID:23354386 综述 | 中（人类数据少） |
| θ是记忆的必要条件，但非充分条件 | MS-DBB光遗传沉默+行为 | PMID:37720546 | 中-高 |

## 连接

- [[place-cell]] — 场所细胞的相位前进是θ相位编码的直接体现
- [[phase-precession]] — θ振荡的核心功能现象：场所细胞放电相位随位置移动
- [[hippocampal-circuit]] — θ协调CA3/CA1/EC三向通信的时间框架
- [[sharp-wave-ripples]] — θ（探索）与SWR（静止）是海马两种互斥的工作模式
- [[grid-cell]] — 内嗅皮层网格细胞也显示θ相位前进；振荡干涉模型解释网格图案
- [[ltp]] — θ振荡的体内诱导节律（theta-burst stimulation是标准LTP诱导方法）
- [[btsp]] — θ可能协调BTSP所需的树突平台电位触发时机
- [[memory-consolidation]] — θ态（编码）与SWR态（固化）是记忆形成的两个阶段

## 未解问题

- Q-theta-primate：灵长类海马缺乏θ节律性放电，是替代机制（工作记忆α？）还是功能保守？
- Q-theta-btsp-coordination：θ振荡是否直接协调BTSP所需平台电位的触发时机？
- Q-theta-sufficiency-memory：单纯增强θ频率或功率是否能改善记忆？阿尔茨海默病中恢复θ-γ耦合是否有治疗价值？

## 修订历史

- 2026-05-29 · 创建 · 填补高优先级悬空引用（由 place-cell、ltp、hippocampal-circuit、grid-cell 引用） · 基于《θ振荡与相位编码》文章 · 初始置信度：高

## 来源文章

- [[2026-05-29-theta-oscillations-phase-coding]]

---
title: θ相位前移
slug: theta-phase-precession
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-22
updated: 2026-09-18
revision_count: 2
dimensions: [cellular, microcircuit, brain-region, behavior, cognition]
related: [theta-oscillations, theta-sequences, place-cells, grid-cells, hippocampal-circuit, ltp, memory-consolidation, medial-septum, entorhinal-cortex, sharp-wave-ripples]
prerequisites: [theta-oscillations, place-cells, action-potential]
opens_questions: [Q-theta-btsp-coordination, Q-ts-01, Q-ts-02, Q-ts-03]
source_articles: [2026-06-22-grid-cells-place-cells, 2026-09-18-theta-sequences-episodic-memory]
key_sources: ["PMID:8353611", "PMID:23354386", "PMID:8797016", "PMID:16600862", "PMID:17663452", "PMID:23594744", "PMID:32526196", "PMID:33033222", "PMID:39746924", "PMID:34376673"]
---

# θ相位前移 (Theta Phase Precession)

> **一句话定义**：场所细胞的放电相位在动物穿越场所场时相对于背景θ振荡系统性提前约100–355°，使单个θ周期内的场所细胞序列编码时间压缩的空间轨迹，是位置信息率+相位双重编码的核心机制。

## 当前理解

我们现在认为，θ相位前移是大脑实现**率-相位双重编码**的核心机制：场所细胞不只通过放电率（firing rate）编码当前位置，还通过放电相位（firing phase）相对于θ振荡编码位置精度信息。这大约将空间分辨率翻倍（相位码提供额外维度）。

更重要的是，相位前移产生了"θ序列"（theta sequences）：在单个θ周期（约125 ms）内，不同位置的场所细胞按**从过去到未来**的顺序依次放电——时间上压缩约20:1，使行为尺度的路径（数秒）在突触可塑性的时间窗口（约20 ms）内完整呈现。这被认为是路径学习和认知地图实时建构的核心神经机制。

## 关键机制

### 1. 基本现象（O'Keefe & Recce 1993）

- 动物进入场所场时：放电在θ**晚期相位**（近波峰，约270°）
- 穿越中途：放电在**中期相位**（约180°）
- 离开场所场时：放电在**早期相位**（近波谷，约0°）
- 总相位位移：约100–355°（与位置强相关，与时间弱相关）

### 2. θ序列（Theta Sequences）

单个θ周期（约125 ms）内的场所细胞时序：
- **早相位**（近θ谷）：代表当前位置**前方**（未来位置）的场所细胞激活
- **中相位**：代表**当前位置**的场所细胞激活
- **晚相位**（近θ峰）：代表当前位置**后方**（刚经过位置）的场所细胞激活

时间压缩比：约20:1；行为尺度5–10秒的路径压缩进约125 ms的θ周期内。

### 3. 突触可塑性的含义

时间压缩后，前后相邻位置的场所细胞激活间隔约10–30 ms——正好落入**STDP（突触时序依赖可塑性）**的关联窗口。因此θ序列天然地提供了"哪些细胞应该被联合强化"的时间框架：路径上前后相邻位置的场所细胞，在θ序列中以正确的时序激活，满足Hebbian学习的条件。

### 4. 竞争机制解释

**振荡干涉（OI）模型**：细胞内在振荡频率略高于背景θ，两者干涉产生相位漂移  
**双路径输入模型**（Chance 2012）：CA3（晚相位输入）和EC层III（早相位输入）顺序激活CA1，产生相位前进

两个模型各有实验支持，尚无定论。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| θ相位前移存在，位移约100–355° | 大鼠线性轨道单细胞+LFP | PMID:8353611 | 高（经典；多物种重复） |
| 相位与位置相关，与时间弱相关 | 速度控制实验+相关分析 | PMID:8353611 | 高 |
| 群体θ序列压缩比约10:1 | CA1多单元同步记录，时序相关分析 | PMID:8797016 | 高 |
| θ序列编码前/当/后位置 | 多单元记录+贝叶斯解码 | PMID:23354386综述 | 高 |
| CA3（晚相位）/ CA1（早相位）交错激活编码时间序列 | CA3+CA1双区域记录 | PMID:16600862 | 高 |
| 前向θ序列预测未来行为路径 | 开放场地+行为预测 | PMID:23594744 | 高 |
| θ序列以相位坐标为基础（MS冷却保留相位压缩P=0.92） | MS精准低温探针，n=5大鼠 | PMID:32526196 | 高 |
| θ振荡内前向/逆向独立双序列 | 贝叶斯解码，144细胞×115845振荡 | PMID:33033222 | 高 |
| DG控制CA3晚期相位起点（47%斜率下降） | DG选择性损毁+CA3记录 | PMID:39746924 | 中-高（2025，待复现） |
| 人类MTL神经元表现θ相位序列编码（~58°） | 颅内电极，9名患者 | PMID:34376673 | 中（小样本） |
| 两机制模型均不完整 | 综述与模型比较 | PMID:23354386 | 高（争议本身） |

## 连接

- [[theta-oscillations]] — θ振荡是相位前移的时间参照框架；无θ则无相位前移现象
- [[theta-sequences]] — 相位前移在群体层面产生θ序列；本页是机制，theta-sequences是功能
- [[place-cells]] — 场所细胞是θ相位前移的主体
- [[grid-cells]] — MEC网格细胞也显示类似的θ相位前移（振荡干涉模型的基础）
- [[medial-septum]] — MS-DBB是θ振荡（和相位框架）的主要起搏器
- [[entorhinal-cortex]] — EC层III驱动逆向θ序列；EC输入与CA3输入在CA1以不同相位到达
- [[ltp]] — θ序列压缩后的时序激活恰好落入STDP/LTP的关联窗口
- [[memory-consolidation]] — θ序列提供了路径学习的神经时间框架
- [[sharp-wave-ripples]] — 双峰细胞连接了θ序列（在线编码）与SWR（离线巩固）

## 未解问题

- Q-theta-btsp-coordination：θ相位前移所创造的时间压缩序列，是否通过BTSP（树突平台电位）而非经典STDP实现突触强化？
- Q-ts-01：θ序列/相位进动在非空间情节记忆中是否存在？
- Q-ts-02：双向序列的CA3/EC III回路假说需光遗传学因果验证
- Q-ts-03：STDP vs BTSP的相对贡献？两者是否分管不同时间尺度？

## 修订历史

- 2026-06-22 · 创建 · 填补theta-oscillations页面引用的 phase-precession 悬空slug · 基于《六边形的秘密》文章 · 初始置信度：高
- 2026-09-18 · 重大修订 · 基于《θ序列》(#148) · 新增：(1) Skaggs 1996压缩比量化；(2) Dragoi & Buzsáki 2006 CA3/CA1分工；(3) Wang et al. 2020双向序列；(4) Pfeiffer & Foster 2013前瞻性扫描；(5) Petersen & Buzsáki 2020 MS相位框架；(6) Ahmadi 2025 DG/MEC回路分工；(7) Reddy 2021人类证据 · 新增连接：theta-sequences, medial-septum, entorhinal-cortex, sharp-wave-ripples

## 来源文章

- [[2026-06-22-grid-cells-place-cells]]
- [[2026-09-18-theta-sequences-episodic-memory]]

---
title: 三因素学习规则
slug: three-factor-learning-rule
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-06-07
updated: 2026-09-29
revision_count: 4
dimensions: [synaptic, cellular, microcircuit, cognition, behavior]
related: [hebbian-learning, dopamine-reward-prediction-error, ltp, synaptic-tagging-capture, ampa-receptor, camkii, engram-cells, competition-selection-principle, btsp, corticostriatal-stdp, striatal-direct-indirect-pathway, eligibility-trace]
prerequisites: [hebbian-learning, ltp, synaptic-transmission, nmda-receptor]
opens_questions: [Q-three-factor-time-window, Q-stc-molecular-tag, Q-three-factor-btsp-third-factor-identity, Q-corticostriatal-stdp-in-vivo-timing]
source_articles: [2026-06-07-dopamine-reward-prediction-error, 2026-09-20-btsp-camkii-molecular-timekeeper, 2026-09-28-corticostriatal-stdp-d1d2-plasticity, 2026-09-29-eligibility-trace-temporal-credit-assignment]
key_sources: ["PMID:12371508", "PMID:9054347", "PMID:8774460", "PMID:9020359", "PMID:7708662", "PMID:28883072", "PMID:39385027", "PMID:41224656", "PMID:18687967", "PMID:20613723", "PMID:15528409", "PMID:11544526", "PMID:36226826", "PMID:21170072"]
---

# 三因素学习规则 (Three-Factor Learning Rule)

> **一句话定义**：突触权重的改变不仅由局部 Hebbian 条件（突触前 × 突触后活动）决定，还需要全局调制信号（第三因素，如多巴胺）的"许可"：**Δw ∝ (pre × post) × M**，这使突触可塑性具有方向性和选择性，能够被全局目标（奖励、注意、显著性）所导向。

## 当前理解

我们现在认为，经典 Hebbian 规则（二因素：Δw = η × pre × post）描述了突触可塑性的必要条件，但不是充分条件——至少在行为意义的学习中，需要第三因素的"评估"。三因素学习规则写成：

**Δw = η · (pre × post) × M**

其中 M 是全局调制信号，对于不同学习类型有不同底物：
- **奖励学习**：M = 多巴胺（DA）浓度变化（来自 VTA/SNc）
- **注意调制**：M = 乙酰胆碱（ACh）（来自基底前脑胆碱能神经元）
- **显著性/应激**：M = 去甲肾上腺素（NE）（来自蓝斑）

三个关键含义：
1. **必要性**：M 和 Hebbian 激活都是必要条件，缺一不可（乘法，不是加法）
2. **方向性**：M > 0（DA 爆发）→ LTP；M < 0（DA 抑制）→ LTD；M = 0 → 无变化
3. **选择性**：M 作为全局广播，只强化"最近被 Hebbian 激活的突触"——选择性由 Hebbian 条件而非 M 本身实现

**最直接实验证据**（Reynolds & Wickens 2002）：在纹状体皮层-纹状体突触，高频皮层刺激（Hebbian）+ DA 脉冲 → LTP；单独 Hebbian 激活或单独 DA 均不诱导 LTP；三因素的乘法逻辑在纹状体得到直接验证。

## 关键机制

### 奖励学习（DA 作为第三因素）

```
突触前活动（谷氨酸释放）
    + 突触后去极化（AMPAR/NMDAR激活）
    = Hebbian 激活 → Ca²⁺ 内流 → CaMKII 激活 → 设置"突触标签"

                                    +

DA 爆发（RPE > 0）
    → D1/D5 激活 → cAMP↑ → PKA
    → ① GluA1 Ser845 磷酸化（E-LTP 增强）
    → ② CREB 磷酸化 → PRPs 合成（被突触标签捕获 → L-LTP）

= 三因素 LTP（比单独 Hebbian 激活更持久、更强）
```

DA 抑制（δ < 0）时，通过 D2 受体 → Gi → cAMP↓ → PP2B/PP1 级联 → AMPAR 去磷酸化 → 三因素 LTD。

### 注意调制（ACh 作为第三因素）

基底前脑胆碱能神经元（Ch1-Ch4）在注意任务中被激活，释放 ACh 到皮层。ACh 通过：
- M1 受体（突触后）：增强 NMDAR 的 Ca²⁺ 内流，放大 Hebbian 激活
- nAChR（突触前）：增加皮层谷氨酸释放，增强 pre 因素

使注意焦点内的刺激表征优先被 Hebbian 强化——注意力改变学习的选择性（而非方向性）。

### 纹状体 D1/D2 双通道实现

纹状体 D1-SPNs（直接通路）和 D2-SPNs（间接通路）是三因素规则的对称实现：

| | D1-SPNs（Go） | D2-SPNs（No-Go） |
|--|--------------|-----------------|
| DA 爆发（正 RPE） | LTP（强化正确行动） | LTD（削弱竞争行动） |
| DA 抑制（负 RPE） | LTD（削弱错误行动） | LTP（强化回避行动） |
| DA 基线 | 无变化 | 无变化 |

这一双通道设计使大脑**同时学习"做什么"和"不做什么"**，比单纯正向强化高效得多。

**2026-09-28 新增（第158篇，Shen 2008）——纹状体三因素规则的STDP分子机制**：

这一双通道设计已在Shen et al.（2008, PMID:18687967）中用精确的STDP协议直接验证。关键发现是多巴胺状态**不对称地**改变两条通路的STDP规则：

- D1-MSN中，D1受体激活（高DA）**主动阻断LTD路径**（抑制mGluR5→内源性大麻素→CB1级联），使D1-MSN在正常多巴胺水平下**只能LTP**，无法被STDP削弱——这意味着"正确行动"的突触一旦被奖励强化，就很难被简单的STDP配对逆转
- D2-MSN中，多巴胺（通过D2受体）**拮抗A2a腺苷受体的LTP信号**，同时开放D2-mGluR5-CB1的LTD通路——高DA时D2-MSN几乎只能LTD（"竞争行动被清除"）

这不是简单的"DA高→LTP/LTD更强"，而是DA从根本上重写了STDP的**可塑性方向规则**。详细分子级联见 [[corticostriatal-stdp]]。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 纹状体三因素乘法规则（pre × post × DA = LTP）| 纹状体-皮层突触电生理 + 多巴胺精控 | PMID:12371508 | 高 |
| DA 是奖励学习必要条件（不只是充分） | 6-OHDA 损毁 DA 系统的学习缺陷 + 光遗传 DA 激活替代奖励 | 多篇；基于综述 | 高 |
| D1→cAMP→PKA→L-LTP（海马） | D1/D5 激动剂诱导 CA1 L-LTP；茴香霉素阻断 | PMID:7708662（PMC42234） | 高 |
| ACh 调制 NMDAR 增强 Hebbian 激活 | M1 受体阻断消除 ACh 的学习促进效果 | 多篇；基于综述 | 中-高 |

## 资格痕迹：三因素规则的毫秒→分钟时间桥（2026-09-29 新增）

三因素规则面临的核心时序挑战：行为发生（Hebbian激活，ms级）与DA奖励信号到来（数百毫秒至数分钟后）之间有显著延迟，经典STDP时序窗口（±20ms）远不够。**资格痕迹**是三因素规则如何跨越这一时间鸿沟的分子机制（Fuchsberger et al. 2022, PMID:36226826）：

```
毫秒时间尺度：
突触前-突触后配对（Δt=±20ms）
    → NMDA-R开放 → Ca²⁺内流
    → AC1/AC8（腺苷酸环化酶）进入"敏感-沉默"状态
    → 突触强度变化（短暂，可能为LTD）
    → 痕迹开始计时（持续~分钟）

分钟时间尺度（在资格痕迹有效期内）：
DA爆发 + 突触后爆发放电
    → DA(Gs)→β-γ亚基 + Ca²⁺残留 → AC1/AC8共激活 → cAMP骤升
    → PKA → GluA1磷酸化 → AMPAR插入 → LTP
    → 净效应：原本的LTD被逆转为LTP（三因素规则"写入"）

无DA或DA延迟过长（>痕迹寿命）：
    → 突触强度维持LTD或恢复基线（行为未被强化）
```

**资格痕迹 vs STC 的时间层次**：

| 机制 | 有效时间窗 | 分子底物 | 脑区 |
|------|----------|---------|------|
| 资格痕迹（eligibility trace）| 毫秒→分钟（~10min）| AC1/AC8敏感状态 | CA1（直接证据）；纹状体（推论）|
| 突触标记与捕获（STC）| 分钟→小时（~1-2h）| 突触标签（CaMKII？）+ PRPs | CA1, LA, 多区域 |
| 行为标记（behavioral tagging）| ~6h内 | STC在行为层面的涌现 | 全脑（行为层级）|

这三个机制在时间上**接力**，共同覆盖奖励学习中可能遇到的各种延迟范围——从快速条件反射（毫秒）到复杂工具性学习（分钟）再到情节记忆（小时）。

## BTSP 作为三因素规则的海马实现

BTSP（行为时间尺度突触可塑性）为三因素规则提供了一个与多巴胺-奖励通路并列、但完全不同的神经生理实现（Madar et al., 2025, PMID:41224656）：

**BTSP 的三因素对应关系**：

| 三因素规则元素 | 多巴胺-奖励版本 | BTSP 版本（海马） |
|-------------|-------------|----------------|
| 第一因素（突触前） | 皮层→纹状体谷氨酸释放 | CA3/EC 输入→CA1 谷氨酸释放 |
| 第二因素（突触后） | 纹状体棘突神经元去极化 | CA1 锥体神经元去极化 |
| 第三因素（全局调制） | VTA/SNc 多巴胺爆发（RPE > 0） | 树突钙平台电位（EC3 + CA3 联合驱动） |
| 资格痕迹 | 突触标签（CaMKII、PKA 磷酸化状态） | 突触前输入在 ±3–4 秒窗口内的 Ca²⁺ 痕迹 |
| 时间窗口 | 毫秒至数秒（与 DA 爆发对齐） | 秒级（向后 3–4 s，向前 2–3 s） |
| 输出 | 纹状体 LTP/LTD（行动选择） | CA1 场所场写入（情节记忆）|

**关键区别**：
- DA 三因素规则中，第三因素是**外部评估信号**（奖励反馈），由环境决定
- BTSP 中，第三因素是**内部生成事件**（树突平台电位），由海马网络状态（θ 振荡、EC3+CA3 联合输入）决定
- 两者都解决了**时序信用分配问题**，但在不同时间尺度和不同脑区运作

**BTSP 的分子秒表（DDSC）**与三因素规则的资格痕迹类比：
- CaMKII 的延迟弥散激活（DDSC，10–100 秒后）整合了平台电位前后数秒内到达的突触输入的"痕迹"
- 这与 STC（突触标记与捕获）中的"标签有效期"（TAG duration）在概念上等价，但分子机制不同

## 连接

- [[hebbian-learning]] — 三因素规则是 Hebb 规则的扩展：加入全局调制因子 M，使突触可塑性有了方向性和行为意义
- [[dopamine-reward-prediction-error]] — DA-RPE 是奖励学习中 M 因素的主要来源
- [[ltp]] — 三因素规则的正向（DA > 0）结果是 LTP；D1→PKA→CREB 是 DA 诱导 L-LTP 的分子链
- [[synaptic-tagging-capture]] — 突触标记（Hebbian 产物）+ 捕获（DA 驱动的 PRP 合成）是三因素规则的时间整合机制
- [[camkii]] — Hebbian 激活 → Ca²⁺ → CaMKII 激活可能是"突触标签"的分子身份（假说）；在 BTSP 中，CaMKII 的 DDSC 充当资格痕迹整合器
- [[ampa-receptor]] — 三因素 LTP 最终通过 AMPAR 插入/磷酸化表达
- [[engram-cells]] — CREB 竞争性分配（印迹细胞选择）可能受 DA 三因素规则调制
- [[competition-selection-principle]] — 三因素规则在细胞层面实现了竞争性突触遴选
- [[btsp]] — BTSP 是三因素学习规则在海马情节记忆写入中的神经生理实现；树突平台电位充当"第三因素"，DDSC 实现秒级时序整合
- [[corticostriatal-stdp]] — 三因素规则在纹状体的具体STDP实现（D1/D2-MSN不对称门控规则，Shen 2008）
- [[striatal-direct-indirect-pathway]] — 三因素规则通过直接/间接通路双轨写入，实现"正确行动强化+竞争行动削弱"
- [[eligibility-trace]] — 资格痕迹是三因素规则在毫秒→分钟时间尺度的分子实现（AC1/AC8沉默痕迹）；与STC共同构成三因素规则的时间积分体系

## 未解问题

- Q-three-factor-time-window：三因素规则中 Hebbian 激活与 DA 信号之间的有效时间窗口（标签有效期）在不同脑区和突触类型中有多大差异？光遗传精控 DA 时序是否可以精确绘制这个窗口？
- Q-stc-molecular-tag：突触标签的分子身份——CaMKII 特定构象？PKM-ζ？F-actin 聚合？目前缺乏直接分子证据。
- Q-three-factor-btsp-third-factor-identity：BTSP 中，"平台电位"究竟是怎样充当"第三因素"的？平台电位是否等价于 DA 爆发？它是否也携带"评估"（评分）语义，还是只是解锁时间窗口的纯机械性触发？

## 修订历史

- 2026-06-07 · 创建 · 基于《多巴胺的时间机器》一文 · 填补 [[hebbian-learning]] 页面的悬空引用 [[three-factor-learning-rule]] · 初始置信度：高
- 2026-09-20 · 修订（rev2）· 基于《BTSP的分子秒表》一文（#150）· 新增「BTSP 作为三因素规则的海马实现」章节；对比 DA-奖励三因素与 BTSP-平台电位三因素的共性与区别；DDSC 与资格痕迹的分子类比；related 新增 btsp；开放问题新增 Q-three-factor-btsp-third-factor-identity
- 2026-09-28 · 修订（rev3）· 基于《纹状体的突触法庭》一文（#158）· 在「纹状体D1/D2双通道实现」章节补入Shen 2008的STDP具体分子机制（D1阻断mGluR5-CB1路径；D2拮抗A2a的分子细节）；新增[[corticostriatal-stdp]]和[[striatal-direct-indirect-pathway]]连接；key_sources新增PMID:18687967、20613723、15528409、11544526；开放问题新增Q-corticostriatal-stdp-in-vivo-timing
- 2026-09-29 · 修订（rev4）· 基于《时序信用分配》(#159) · 新增「资格痕迹：三因素规则的毫秒→分钟时间桥」章节，包含资格痕迹 vs STC vs 行为标记的时间层次对比表；connections新增eligibility-trace；key_sources新增PMID:36226826、21170072

## 来源文章

- [[2026-06-07-dopamine-reward-prediction-error]]
- [[2026-09-20-btsp-camkii-molecular-timekeeper]]
- [[2026-09-28-corticostriatal-stdp-d1d2-plasticity]]
- [[2026-09-29-eligibility-trace-temporal-credit-assignment]]

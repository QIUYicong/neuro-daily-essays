---
title: 习惯 vs 目标导向行为：双系统竞争与转换
slug: habit-vs-goal-directed
domain: concepts
type: framework
status: mainstream
confidence: high
created: 2026-10-20
updated: 2026-10-20
revision_count: 1
dimensions: [synaptic, microcircuit, brain-region, behavior, cognition, disease]
related: [habitual-behavior, goal-directed-behavior, striatal-direct-indirect-pathway, basal-ganglia, dopamine-reward-prediction-error, prefrontal-cortex, three-factor-learning-rule, addiction, endocannabinoid-system, orbitofrontal-cortex]
prerequisites: [habitual-behavior, goal-directed-behavior, striatal-direct-indirect-pathway, dopamine-reward-prediction-error]
opens_questions: [Q-switch-01, Q-switch-02, Q-switch-03, Q-switch-04]
source_articles: [2026-10-20-habit-goal-directed-dms-dls-circuit-switch]
key_sources: ["PMID:14750976", "PMID:16045504", "PMID:14643469", "PMID:27238866", "PMID:33774666", "PMID:39896502", "PMID:40771101", "PMID:32324535", "PMID:26515740", "PMID:41663373"]
---

# 习惯 vs 目标导向行为：双系统竞争与转换

> **一句话定义**：大脑并行维护两套行为控制系统——目标导向系统（DMS 依赖，model-based RL，对结果价值实时敏感）与习惯系统（DLS 依赖，model-free RL，S-R 联结驱动）——习惯的形成不是 DLS 被动积累的结果，而是一个需要 OFC-CB1 内大麻素门控开启、DMS 直接通路主动突触压制、D1+/A2A+ 细胞命运分叉共同完成的主动建设过程。

## 当前理解

行为神经科学区分目标导向与习惯行为的金标准是**结果贬值范式**（outcome devaluation，Balleine & Dickinson 1990s）：让动物学会"动作→奖励"后，通过饱食或厌恶条件化降低奖励价值，测试动物是否继续执行该动作。目标导向动物立即减少行为（实时追踪结果价值）；习惯化动物对贬值不敏感（S-R 联结驱动，与结果断联）。

**经典框架**（约 2010 年）认为，这两套系统的竞争主要体现在 DMS vs DLS 的**相对突触权重积累**上：DLS 随重复训练逐渐建立更强的 S-R 联结，最终胜过 DMS 的 A-O 联结。DMS 系统在习惯化过程中被动"退场"，行为控制权自然移交给 DLS。

**修正图景**（2021-2026 年后）揭示习惯形成是一个**多步骤、主动构建**的过程，包含至少四个关键主动操作：

1. **OFC→DLS CB1 内大麻素门控开启**（Gremel et al. 2016）——分子许可信号
2. **DMS 直接通路 D1-MSN 的突触压制**（Yu et al. 2021）——目标导向系统的主动退场
3. **D1+（直接通路）细胞继续稳定编码行动-结果关系**，而 **A2A+（间接通路）细胞从学习阶段重组为习惯执行模式**（Malvaez et al. 2025）——细胞类型命运分叉
4. **DLS 激活本身主动抑制 DMS 的目标导向决策**（Hart et al. 2025）——习惯系统的主动压制

习惯因此不是"无为的自动化"，而是大脑主动建设的一条计算捷径：它既需要 DLS 的增强，也需要 DMS 的主动降权，还需要特定分子信号（内大麻素）的触发。

## 关键机制

### 1. 多巴胺三因素规则的双系统不对称实现

纹状体可塑性的分子基础是多巴胺依赖性三因素学习规则（Δw ∝ 突触前活动 × 突触后去极化 × 多巴胺）。Shen et al.（2008, PMID:18687967）在 D1/D2-EGFP 小鼠中证明，DA 通过不对称 STDP 同时"刻写"两条通路：
- **D1-MSN（DMS + DLS 直接通路）**：高 DA（奖励）时正时序 STDP → **LTP**
- **D2-MSN（DMS + DLS 间接通路）**：高 DA（奖励）时正时序 STDP → **LTD**（经 CB1 内大麻素）

这种不对称规则保证奖励时"成功行动通路增强 + 竞争行动通路减弱"同步发生，是两套系统从训练第一天就并行学习的分子基础。

### 2. 下边缘皮层（IL）的中间裁判角色

IL 是目标导向与习惯系统竞争的中间调节点：
- **IL 活跃**：通过投射抑制前边缘皮层-DMS 系统，习惯回路主导
- **IL 沉默**（Muscimol 注射）：目标导向系统解除压制，习惯化动物立即恢复对结果贬值的敏感性（Coutureau & Killcross 2003, PMID:14643469）

重要含义：习惯是"压制"目标导向，而非"抹除"——目标导向能力始终潜伏，IL 决定谁获得控制权。

### 3. OFC→DLS CB1 内大麻素门控：习惯形成的分子开关

Gremel et al.（2016, Neuron, PMID:27238866，PMC4911264 开放全文）通过皮层特异性 CB1 受体敲除揭示了习惯形成的分子触发点：
- 选择性敲除 OFC 锥体神经元的 CB1 受体
- CB1 缺失小鼠：经过相同过度训练后，动作控制**始终保持目标导向**，无法转换为习惯
- 机制：正常情况下，OFC 神经元活动触发末梢内大麻素释放（逆行）→ CB1 被激活 → 抑制 OFC→DLS 的兴奋性传递 → 削弱 OFC 对 DLS 的目标导向输入 → DLS 的 S-R 联结逐渐主导

OFC→DLS 的 CB1 内大麻素是从"目标导向模式"切换到"习惯模式"的必要分子许可信号。

### 4. DMS 直接通路 D1-MSN 的主动退场（Yu et al. 2021）

Yu et al.（2021, Cerebral Cortex, PMID:33774666）揭示了习惯获得的关键隐藏步骤：

- 过度训练（生成习惯）后，DMS D1-MSN 皮层→纹状体兴奋性突触 EPSC 幅度显著降低（突触后压制）
- 此压制 DMS 特异性（DLS 无此变化）
- DREADD 拯救此压制（使 D1-MSN 恢复正常兴奋性）→ 损害习惯的**获得**，但不影响已形成习惯的**表达**

这将习惯形成的公式从：
- **旧**：习惯 = DLS 增强 + DMS 被动退出
- **新**：习惯 = DLS 增强 + **DMS D1-MSN 主动突触压制**

### 5. D1+/A2A+ 细胞命运分叉（Malvaez et al. 2025）

Malvaez et al.（2025, bioRxiv, PMID:39896502, PMC11785256 开放全文）通过单细胞钙成像追踪整个训练-习惯化过程：

| 细胞类型 | 目标导向学习阶段 | 习惯化后 | 功能角色 |
|---------|----------------|---------|---------|
| DMS D1+（直接通路） | 稳定编码行动 + 发展结果编码 | **继续稳定编码**行动-结果关系 | 目标导向决策的"持续看门人" |
| DMS A2A+（D2 间接通路） | 初期编码行动 | **重组为刻板执行模式** | 学习初期必要，后迁移至习惯支持 |

化学遗传学验证：
- 抑制 D1+ → 损害目标导向决策；习惯保留
- 抑制 A2A+ → 损害初期动作-结果学习；建立后目标导向可正常执行

### 6. DLS 对 DMS 的主动抑制（Hart et al. 2025）

Hart et al.（2025, European Journal of Neuroscience, PMID:40771101）发现：
- 单侧 DLS DREADD 激活即可**消除目标导向行为**（双侧和同侧均有效）
- 这证明 DLS 不只是"接管了控制权"，而是**主动抑制**了 DMS 的目标导向评估过程

### 7. 两条通路的对立时序调控（Bakhurin et al. 2020）

Bakhurin et al.（2020, eLife, PMID:32324535）将经典 go/no-go 模型升级：
- 直接通路（D1-MSN）：**启动行动并重置内部时序计时器**
- 间接通路（D2-MSN）：**暂停时序计时器并在竞争行动间选择**
- 两条通路在动作执行中**都被激活**，功能不同而非互斥

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| DLS 损毁→无法形成习惯（即便过度训练） | 双侧 DLS 损毁 + 结果贬值 | PMID:14750976 | 高 |
| DMS 损毁→早期训练即习惯化 | 双侧 DMS 损毁 + 结果贬值 | PMID:16045504 | 高 |
| IL 沉默→习惯化动物恢复目标导向敏感性 | Muscimol + 结果贬值范式 | PMID:14643469 | 高（大鼠） |
| OFC CB1 KO→无法转换为习惯 | 皮层特异性 CB1 KO + 工具性学习 | PMID:27238866 | 高（开放全文，独立实验室复制）|
| DMS D1-MSN 突触压制是习惯获得的必要条件 | DREADD 拯救 + EPSC 记录 | PMID:33774666 | 中-高（单实验室，需独立复制）|
| D1+ 稳定编码；A2A+ 重组为习惯模式 | 单细胞钙成像 + DREADD | PMID:39896502 | 中（预印本 2025，待同行评审）|
| DLS 激活主动消除目标导向行为 | 单侧 DREADD + 结果贬值 | PMID:40771101 | 中-高（2025 已出版）|
| 两通路对立调控行动时序，而非 go/stop | 体内 Ca²⁺成像 + 行为分析 | PMID:32324535 | 中-高（开放全文）|
| 扩展到主动回避行为，存在性别差异 | 安全信号贬值 + 化学遗传学 | PMID:41663373 | 中-高（2026 已出版）|
| METH 损伤 DMS D1 通路，A2a 拮抗剂恢复目标导向 | c-Fos + DMS ZM241385 | PMID:26515740 | 高（开放全文）|

## 连接

- [[habitual-behavior]] — 习惯系统的详细机制（DLS, S-R 联结, 多巴胺时序迁移, model-free RL）
- [[goal-directed-behavior]] — 目标导向系统的详细机制（DMS, A-O 联结, PL 皮层, model-based RL）
- [[striatal-direct-indirect-pathway]] — D1/D2-MSN 在两套系统中的细胞实现；DMS vs DLS 功能分化
- [[three-factor-learning-rule]] — 多巴胺三因素规则是两套系统底层学习机制的统一框架
- [[basal-ganglia]] — 两套系统的解剖基底；基底节信息流的整体架构
- [[dopamine-reward-prediction-error]] — DA RPE 驱动两套系统的学习；时序迁移（奖励→线索）固化 DLS 侧
- [[prefrontal-cortex]] — PL（prelimbic）对 DMS 目标导向获得必要；IL（infralimbic）主动抑制目标导向；OFC 通过 CB1 信号门控习惯转换
- [[addiction]] — 成瘾药物通过损伤 DMS D1 通路复制习惯化状态；A2a 拮抗剂恢复目标导向
- [[endocannabinoid-system]] — CB1 内大麻素信号是 OFC→DLS 习惯门控的分子机制
- [[orbitofrontal-cortex]] — OFC 作为 CB1 门控的来源；OFC 异常与强迫症/成瘾相关

## 未解问题

- Q-switch-01：DMS D1-MSN 突触压制的具体分子机制是什么？是 AMPAR 内化（类 LTD）、突触前谷氨酸释放减少，还是内大麻素参与？（Yu et al. 2021 只描述现象）
- Q-switch-02：DLS 主动抑制 DMS 目标导向决策的神经回路路径是什么？是否通过 DLS→GPe→STN→GPi 间接通路反馈抑制了 DMS 相关的丘脑-皮层环路？
- Q-switch-03：目标导向/习惯的性别差异（雌性对结果贬值更敏感，Sears 2026）的神经机制是什么？与焦虑症和 PTSD 的性别差异是否共享机制？
- Q-switch-04：成瘾治疗靶点——增强 DMS D1-MSN 的目标导向功能（如 A2a 拮抗剂，Furlong 2017）能否持续、可转化地恢复人类患者的控制能力？

## 修订历史

- 2026-10-20 · 创建（rev1）· 基于《目标导向还是习惯？纹状体双系统的分子开关机制》（文章 #188）· 填补 striatal-direct-indirect-pathway.md 的悬空引用 [[habit-vs-goal-directed]]；综合经典损毁实验（Yin 2004/2005）与 2016-2026 新发现（Gremel 2016 CB1 门控、Yu 2021 DMS 压制、Malvaez 2025 细胞命运分叉、Hart 2025 DLS 主动抑制）；初始置信度：高（经典框架）/ 中（2021-2025 新机制，部分尚待独立复制）

## 来源文章

- [[2026-10-20-habit-goal-directed-dms-dls-circuit-switch]]

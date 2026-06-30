---
title: Homer1a（睡眠突触削减的分子开关）
slug: homer1a
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-10-16
updated: 2026-10-17
revision_count: 2
dimensions: [molecular, synaptic, cellular, cognition]
related: [ampa-receptor, arc-arg31, adenosine, norepinephrine-locus-coeruleus, synaptic-scaling, homeostatic-plasticity, mglur-ltd, slow-wave-sleep, flip-flop-switch-sleep-wake, circadian-clock]
prerequisites: [ampa-receptor, synaptic-transmission, adenosine, norepinephrine-locus-coeruleus]
opens_questions: [Q-homer1a-01, Q-homer1a-02, Q-homer1a-03, Q-homer1a-04]
source_articles: [2026-10-16-homer1a-arc-sleep-ampa-downscaling, 2026-10-17-mglur-ltd-hippocampal-fragile-x]
key_sources: ["PMID:28154077", "PMC:5382711", "PMID:36632309", "PMC:9826981", "PMID:30923476", "PMC:6430175", "PMID:39163472", "PMC:11364421"]
---

# Homer1a（睡眠突触削减的分子开关）(Homer1a — Molecular Switch for Sleep-Dependent Synaptic Downscaling)

> **一句话定义**：Homer1a 是一种即早基因产物（IEG）、Homer1 的短型显性负效应变体，在清醒期被高水平去甲肾上腺素排斥在突触后致密区（PSD）之外，入睡后随 NA 水平骤降、腺苷 A1R 信号增强而大量进入 PSD，瓦解 mGluR1/5-IP3R 信号复合物并触发 AMPA 受体（GluA1/GluA2）脱落，是 NREM 睡眠期间突触权重全局下调的核心分子执行者。

## 当前理解

我们现在认为，Homer1a 是连接神经调质状态（NA/腺苷水平）与突触权重动态之间的一个关键分子接口。它的功能依赖一个精妙的"门控"逻辑：

- **清醒期**：蓝斑释放高水平 NA，通过 α/β 肾上腺素受体（特定下游通路尚待明确）将 Homer1a 排斥在突触 PSD 之外。此时即使 Homer1a 因神经活动而被大量合成，也无法进入突触发挥功能。
- **入睡后**：NA 水平随蓝斑放电停止而骤降；与此同时，由清醒期积累的腺苷通过 A1R 主动促进 Homer1a 向 PSD 靶向输送。两路信号汇合，Homer1a 得以大量进入 PSD。

进入 PSD 后，Homer1a（只含 EVH1 结构域，缺乏 C 端卷曲螺旋域）与 mGluR1/5 竞争性结合，将长型 Homer 蛋白顶出，瓦解 mGluR1/5-IP3R-PKCγ 复合物。失去支架后，GluA1 和 GluA2 亚基开始从 PSD 松动并经横向扩散移出突触，突触权重下降。

Homer1a 与 **Arc** 协同作用：Homer1a 负责松动 GluA1/GluA2（支架瓦解），Arc 负责执行内吞（召唤 dynamin/endophilin）。两者共同完成睡眠期突触权重的全局下调。

## 关键机制

### Homer 蛋白家族结构

- **长型 Homer（Homer1b/c, Homer2, Homer3）**：含 N 端 EVH1 域（结合 mGluR1/5）+ C 端卷曲螺旋域（与 IP3R、Shank 等交联）。是清醒突触 PSD 的正常支架组分，将 mGluR1/5 信号与 Ca²⁺ 释放偶联。
- **Homer1a（短型 IEG）**：仅含 EVH1 域，缺少 C 端卷曲螺旋。作为"显性负效应物（dominant negative）"，与 mGluR1/5 结合但无法与下游 IP3R/Shank 交联 → 瓦解长型 Homer 搭建的复合物 → 信号解耦合。

### 双路门控：NA（屏障）与腺苷（推动力）

**NA 屏障（清醒时）**：
- 阻断 α/β-AR → 清醒小鼠 PSD-Homer1a 升高（证明 NA 是阻止 Homer1a 进入 PSD 的关键）
- 机制尚待完全明确，可能涉及 PKA/PKC 下游的突触骨架磷酸化使 Homer1a 结合位点封闭

**腺苷 A1R 推动力（睡眠时）**：
- 阻断 A1R → 睡眠期 PSD-Homer1a 升高**完全被阻止**（Diering 2017，PMC5382711）
- 给予 A1R 激动剂 → 清醒小鼠可以模拟睡眠期 Homer1a 靶向
- 这将 Homer1a 的突触靶向与腺苷（Process S/睡眠稳态信号）直接连接

### 功能后果：mGluR 信号模式切换

Martin, Monroe, Diering 2019 (PMC6430175) 表明：
- 完整长型 Homer：mGluR1/5 信号 → IP3R → IP3 → Ca²⁺ 振荡 → 蛋白激酶激活（"清醒模式"）
- Homer1a 替换后：mGluR1/5 信号解耦 → 低 Ca²⁺ → 无下游激活（"睡眠模式"）
- GluA1 Ser831/Ser845 去磷酸化 → 横向扩散 → 内吞候选

### Homer1a 与记忆特异性

阻断 mGluR1/5（模拟 Homer1a 功能缺失）在睡眠期恐惧条件化后 → 记忆泛化增加（不只害怕训练笼，也害怕新笼子）（Diering 2017）。这说明 Homer1a 介导的突触削减**提高了记忆的特异性**：背景噪音（非训练突触）被削减 → 训练特异突触相对增强 → 信噪比提升。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| Homer1a 清醒时被排斥在 PSD 外，睡眠时大量进入 | PSD 分离物 Homer1a 免疫印迹（睡眠 vs 剥夺 vs 清醒） | PMID:28154077 / PMC5382711 | 高 |
| NA 是阻止 Homer1a 进入 PSD 的关键屏障 | α/β-AR 拮抗剂注射 → 清醒期 PSD-Homer1a 升高 | PMID:28154077 | 高 |
| 腺苷 A1R 是 Homer1a 进入 PSD 的推动信号 | A1R 拮抗剂完全阻止睡眠期 PSD-Homer1a 升高；A1R 激动剂在清醒期诱导 Homer1a 靶向 | PMID:28154077 | 高 |
| Homer1a 进入 PSD 导致 GluA1/GluA2 减少并去磷酸化 | PSD GluA1/GluA2 免疫印迹 + 磷酸化位点抗体 | PMID:28154077 | 高 |
| 阻断 Homer1a 功能（mGluR1/5 KD）→ 睡眠期记忆泛化 | 睡眠期恐惧训练 + mGluR1/5 拮抗剂 → 上下文泛化 | PMID:28154077 | 中-高 |
| CDK5/Homer1a 候选为下丘脑 AMPA 受体睡眠削减机制 | 文献分析+下丘脑 GluA1 定量 | PMID:39163472 / PMC11364421 | 中（候选，未直接验证） |

## 连接

- [[ampa-receptor]] — Homer1a 是 AMPA 受体从 PSD 脱落的上游触发器（支架瓦解 → GluA1/GluA2 横向扩散）
- [[arc-arg31]] — Homer1a 与 Arc 协同：前者松动，后者执行内吞；共同完成睡眠期突触权重下调
- [[adenosine]] — 腺苷 A1R 是 Homer1a 进入 PSD 的主要推动信号（Process S 到分子机制的桥梁）
- [[norepinephrine-locus-coeruleus]] — NA 高水平是 Homer1a 进入 PSD 的屏障；入睡时 LC 静默 → NA 降→ 屏障解除
- [[mglur-ltd]] — Homer1a 解耦 mGluR5 信号（睡眠期：mGluR5 无法触发 IP3→PKCβ→GluA2-Ser880 级联）；mGluR-LTD 则是 mGluR5 **主动激活**该级联的结果——两者共享受体，机制相反。FXS 中 Homer1a 病理性升高可能通过慢性解调 mGluR5 信号平衡而参与 LTD 失调。详见 [[fragile-x-syndrome]]。
- [[slow-wave-sleep]] — Homer1a 进入 PSD 发生在 NREM 慢波睡眠期；REM 不是必需的
- [[synaptic-scaling]] — 睡眠依赖的突触削减（Homer1a/GluA1 通路）与经典突触缩放（GluA2 通路）是两套独立但互补的稳态机制
- [[flip-flop-switch-sleep-wake]] — Homer1a 的门控状态（NA 屏障 vs 腺苷推动）是翻转开关状态的分子读出
- [[circadian-clock]] — NA 昼夜节律（由 SCN 协调 LC）决定 Homer1a 功能的时间窗口

## 未解问题

- Q-homer1a-01：pCaMKIIβ（印迹突触的 Arc 排斥标记）在 LTP 后的磷酸化维持时间是多少？印迹保护窗口的时长决定了睡眠削减的安全期。
- Q-homer1a-02：CDK5 在睡眠突触削减中的具体角色——是 Homer1a 的下游效应子，还是独立的并行通路？
- Q-homer1a-03：海马 CA1（记忆巩固最关键区域）的 Homer1a 进入 PSD 是否与皮层同步？其分子环境（NA 受体密度、A1R 分布）有何差异？
- Q-homer1a-04：衰老中蓝斑萎缩（NA 节律减弱）是否使 Homer1a 的 NA 屏障减弱 → 错误时机的突触削减？这能否解释年龄相关的记忆巩固减弱？

## 修订历史

- 2026-10-16 · 创建 · 基于《睡眠如何修剪突触：Homer1a 与 Arc 的分子协奏》(#176) · 初始置信度：高 · 综合 Diering 2017 (Science), Diering 2022, Martin 2019, Liu 2024
- 2026-10-17 · 修订 · 基于《当受体失去支架》(#177) · 深化 [[mglur-ltd]] 连接说明：明确 Homer1a 解耦（睡眠/被动）vs mGluR-LTD 激活（清醒/主动）的对比；新增 FXS 中 Homer1a 病理性升高的潜在机制参与；添加 [[fragile-x-syndrome]] 参考

## 来源文章

- [[2026-10-16-homer1a-arc-sleep-ampa-downscaling]]

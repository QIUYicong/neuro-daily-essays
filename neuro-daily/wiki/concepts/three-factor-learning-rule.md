---
title: 三因素学习规则
slug: three-factor-learning-rule
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-07
updated: 2026-06-09
revision_count: 3
dimensions: [molecular, synaptic, cellular, microcircuit, behavior, cognition]
related: [hebbian-learning, dopamine-reward-prediction-error, ltp, synaptic-tagging-capture, ampa-receptor, camkii, engram-cells, competition-selection-principle, eligibility-trace, stdp, btsp, backpropagating-action-potential, striatal-synaptic-plasticity, d1-d2-receptor-signaling, habit-formation]
prerequisites: [hebbian-learning, ltp, synaptic-transmission, nmda-receptor, stdp]
opens_questions: [Q-three-factor-time-window, Q-stc-molecular-tag, Q-striatum-d1-affinity-logic]
source_articles: [2026-06-07-dopamine-reward-prediction-error, 2026-08-28-three-factor-learning-rule-eligibility-traces, 2026-06-09-striatum-d1-d2-plasticity-dichotomy]
key_sources: ["PMID:12371508", "PMID:9054347", "PMID:9020359", "PMID:7708662", "PMID:30108488", "PMID:25258080", "PMID:28883072", "PMID:17220510", "PMID:18687967", "PMID:22544310"]
---

# 三因素学习规则 (Three-Factor Learning Rule)

> **一句话定义**：突触权重的改变由三个因素的乘积决定：赫布协同激发（突触前 × 突触后活动）产生临时资格迹，而真正的永久权重变化只有在神经调质（多巴胺、去甲肾上腺素、血清素）作为第三因素在时间窗内到来时才发生——这一机制使毫秒级 STDP 与秒级行为奖励之间的时间鸿沟得以跨越，是大脑实现强化学习的分子基础。

## 当前理解

我们现在认为，三因素学习规则的核心不是简单的"Δw = (pre × post) × M"，而是引入了**资格迹**（eligibility trace）这一关键中间变量（Gerstner et al. 2018，PMID:30108488）：

$$\frac{d}{dt} e_{ij}(t) = f_j(x_j) \cdot g_i(y_i) - \frac{e_{ij}(t)}{\tau_e}$$

$$\frac{d}{dt} w_{ij}(t) = e_{ij}(t) \cdot M_{3rd}(t)$$

这两个方程的含义：
1. **赫布协同激发**（f_j × g_i）在突触处产生资格迹 e_ij，但权重不立即改变
2. 资格迹以时间常数 τ_e **自然衰减**（秒级），代表"该突触最近被使用过"的临时标记
3. 只有**第三因素 M_3rd 到来时**，资格迹才被转化为实际权重变化；M_3rd = 0 时权重永远不变

第三因素（M_3rd）的生物来源：
- **奖励学习**：多巴胺（DA）来自 VTA/SNc，编码 RPE（奖励预测误差）
- **注意/显著性**：去甲肾上腺素（NE）来自蓝斑
- **惩罚/停止**：血清素（5-HT）来自背缝核（DRN）

**关键修订**（相较于旧版理解）：
- 旧版：Δw = (pre × post) × M（即时乘法）
- 新版：赫布协同 → 资格迹（延迟，秒级衰减）→ 遇到 M_3rd → 权重变化（时间分离的两步）
- 这一修订解决了**远端奖励问题**（distal reward problem）：奖励比行为晚数秒到来，仍能正确归因到参与行为的突触

**最直接实验证据**（Yagishita et al. 2014，PMID:25258080）：在纹状体 D1 型 MSN 树突棘，谷氨酸激活后 0.3–2 秒内给予多巴胺 → 棘扩大（LTP）；超过 4 秒的多巴胺无效；资格迹寿命约 1.5 秒。这是对三因素规则中"时间分离赫布+调质"的首次直接单棘分辨率成像证明。

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

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 纹状体三因素乘法规则（pre × post × DA = LTP）| 纹状体-皮层突触电生理 + 多巴胺精控 | PMID:12371508 | 高 |
| DA 是奖励学习必要条件（不只是充分） | 6-OHDA 损毁 DA 系统的学习缺陷 + 光遗传 DA 激活替代奖励 | 多篇；基于综述 | 高 |
| 纹状体资格迹时窗 0.3-2s（直接成像）| 单棘两光子成像 + 光遗传 DA 时序控制 | PMID:25258080 (PMC4225776) | 高 |
| 皮层 STDP 需神经调质才产生持久 LTP/LTD | STDP × 200 次单独 → 无可塑性；加 NE → LTP，加 5-HT → LTD | He et al. 2015 (via PMID:30108488) | 中 |
| BTSP 是三因素规则的极端案例（±3-4s） | CA1 离体+在体记录，平台电位前后时间窗 | PMID:28883072 (PMC7289271) | 高 |
| D1→cAMP→PKA→L-LTP（海马） | D1/D5 激动剂诱导 CA1 L-LTP；茴香霉素阻断 | PMID:7708662（PMC42234） | 高 |
| ACh 调制 NMDAR 增强 Hebbian 激活 | M1 受体阻断消除 ACh 的学习促进效果 | 多篇；基于综述 | 中-高 |

## 连接

- [[eligibility-trace]] — **资格迹是三因素规则的核心中间变量**；Δw = e_ij × M_3rd；资格迹页面详述分子机制
- [[hebbian-learning]] — 三因素规则是 Hebb 规则的扩展：加入全局调制因子，使突触可塑性有了方向性和行为意义；Hebb 协同激发产生资格迹，而非直接改变权重
- [[stdp]] — STDP 事件（pre 先于 post）是产生正向资格迹的赫布触发器；三因素规则解释了为何单独 STDP 在皮层中不足以产生持久变化
- [[dopamine-reward-prediction-error]] — DA-RPE（δ = r + γV(s') - V(s)）是奖励学习中第三因素 M_3rd 的主要来源；多巴胺广播 × 资格迹 = 行为相关突触的选择性强化
- [[btsp]] — BTSP 是三因素规则的极端案例：树突钙平台电位触发秒级（±3-4s）资格迹，无需峰电位因果时序
- [[ltp]] — 三因素规则的正向（M_3rd > 0）结果是 LTP；D1→PKA→CREB 是 DA 诱导 L-LTP 的分子链
- [[synaptic-tagging-capture]] — STC（突触标签 + 捕获）是三因素规则的小时级版本（蛋白质合成依赖），与秒级资格迹是同一框架的不同时间尺度
- [[camkii]] — 纹状体中 CaMKII 与 PDE10A 抑制共同构成资格迹时间窗的分子底物
- [[ampa-receptor]] — 三因素 LTP 最终通过 AMPAR 插入/磷酸化表达
- [[engram-cells]] — CREB 竞争性分配（印迹细胞选择）可能受 DA 三因素规则调制
- [[competition-selection-principle]] — 三因素规则在细胞层面实现了竞争性突触遴选

## 未解问题

- Q-three-factor-time-window：三因素规则中 Hebbian 激活与 DA 信号之间的有效时间窗口（标签有效期）在不同脑区和突触类型中有多大差异？光遗传精控 DA 时序是否可以精确绘制这个窗口？
- Q-stc-molecular-tag：突触标签的分子身份——CaMKII 特定构象？PKM-ζ？F-actin 聚合？目前缺乏直接分子证据。

## 修订历史

- 2026-06-07 · 创建 · 基于《多巴胺的时间机器》一文 · 填补 [[hebbian-learning]] 页面的悬空引用 [[three-factor-learning-rule]] · 初始置信度：高
- 2026-08-28 · 重大修订 · 基于《信用的时间归属》一文（#128）· 核心升级：引入资格迹（e_ij）数学框架（Gerstner 2018，PMID:30108488）；更新分子机制为 PDE10A 时钟（Yagishita 2014，PMID:25258080）；整合 BTSP 为极端案例（Bittner 2017，PMID:28883072）；新增与 eligibility-trace / stdp / btsp 的连接；status 从 mainstream → established（多系统实验证据）；confidence 保持 high
- 2026-06-09 · 补充修订 · 基于"纹状体极性开关"文章 · 新增：第三因素（DA）在纹状体 D1/D2 MSN 上产生相反方向效果的具体分子机制（Shen 2008, PMID:18687967）；D1-MSN 偏向 LTP、D2-MSN 双向可塑性；新增关联页 striatal-synaptic-plasticity；新增 key_sources PMID:18687967/22544310

## 来源文章

- [[2026-06-07-dopamine-reward-prediction-error]]
- [[2026-08-28-three-factor-learning-rule-eligibility-traces]]
- [[2026-06-09-striatum-d1-d2-plasticity-dichotomy]]

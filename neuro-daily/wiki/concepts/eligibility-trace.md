---
title: 资格迹
slug: eligibility-trace
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-08-28
updated: 2026-08-28
revision_count: 1
dimensions: [molecular, synaptic, cellular, behavior]
related: [three-factor-learning-rule, stdp, dopamine-reward-prediction-error, synaptic-tagging-capture, btsp, ltp, hebbian-learning, backpropagating-action-potential]
prerequisites: [stdp, ltp, hebbian-learning, dopamine-reward-prediction-error]
opens_questions: [Q-three-factor-time-window, Q-stc-molecular-tag]
source_articles: [2026-08-28-three-factor-learning-rule-eligibility-traces]
key_sources: ["PMID:30108488", "PMID:25258080", "PMID:28883072", "PMID:17220510"]
---

# 资格迹 (Eligibility Trace)

> **一句话定义**：突触在赫布协同激发（STDP/Hebbian 事件）后进入的短暂亚稳态标记，不代表权重改变，而是代表"该突触最近参与过协同激发、有资格在后续奖励信号到来时被永久修改"——这一机制使突触可塑性能够跨越毫秒级 STDP 与秒级奖励信号之间的时间鸿沟。

## 当前理解

我们现在认为，突触权重的变化不是直接由赫布协同激发（NMDA 受体巧合探测、STDP）引发的——至少在行为相关的学习中，赫布协同激发只产生一个**临时的、自然衰减的亚稳态标记**（资格迹），真正的永久权重改变需要等待神经调质（多巴胺、去甲肾上腺素、血清素）在时间窗内到来，与资格迹相乘才能实现。

这一机制是**三因素学习规则**的关键中间变量：

$$\frac{d}{dt} e_{ij}(t) = f_j(x_j) \cdot g_i(y_i) - \frac{e_{ij}(t)}{\tau_e}$$

$$\frac{d}{dt} w_{ij}(t) = e_{ij}(t) \cdot M_{3rd}(t)$$

- **e_ij**：突触 j→i 的资格迹（eligibility trace）
- **f_j × g_i**：突触前（x_j）× 突触后（y_i）的赫布协同项（只有协同激发时才设置资格迹）
- **τ_e**：衰减时间常数（不同系统/脑区差异极大）
- **M_3rd**：第三因素（神经调质）——当 M_3rd = 0 时，权重永远不变

资格迹解决的核心问题是**时间信用分配（temporal credit assignment）**：当奖励在行为结束后数秒才到来，大脑如何知道该强化哪些突触？答案是：参与了行为的突触留下了资格迹，奖励信号（多巴胺）到来时只有仍有资格迹的突触才响应写入。

## 关键机制

### 分子层：资格迹在不同系统中的实体

资格迹不是一个统一的分子实体，而是在不同脑区由不同分子实现：

**纹状体（Yagishita et al. 2014，PMID:25258080）——PDE10A 时钟**：
1. 谷氨酸激活 → Ca²⁺ 升高 → CaM 激活 AC1（合成 cAMP）
2. Ca²⁺/CaM **同时抑制 PDE10A**（通常 PDE10A 快速降解 cAMP）
3. → 在 Ca²⁺ 仍在的数秒内，cAMP 处于"可积累"状态 = 资格迹存在的时间窗
4. 此时多巴胺（D1R → Gs → AC1）推高 cAMP → PKA → 棘扩大（LTP）
5. Ca²⁺ 消退 → PDE10A 恢复 → cAMP 积累窗关闭 = 资格迹结束

时间常数：0.3–2 秒（最优约 0.6 s）

**皮层（He et al. 2015，via Gerstner 2018 PMID:30108488）**：
- STDP 200 次单独重复 → 无可塑性（无第三因素时资格迹不转化）
- 前先后随 + 去甲肾上腺素 → LTP（资格迹时窗 5–10 秒）
- 后先前随 + 血清素（5-HT₂c）→ LTD（资格迹时窗 3 秒）
- 皮层资格迹的分子实体尚未完全确定

**海马 BTSP（Bittner et al. 2017，PMID:28883072）——树突平台电位式资格迹**：
- 触发信号：树突 Ca²⁺ 平台电位（而非峰电位时序）
- 时间窗：平台电位前 3–4 秒 + 后 2–3 秒（双向非对称）
- 比纹状体资格迹宽 2–10 倍
- 分子机制与纹状体 PDE10A 时钟是否相同，尚不清楚

### 功能层：选择性强化的实现

资格迹与第三因素的乘法组合解决了"广播信号如何实现突触选择性"的问题：

- 多巴胺从 VTA 广播到整个纹状体/前额叶（体积传播，volume transmission）
- 但只有在奖励前数秒内参与过赫布协同激发的突触才有资格迹
- 多巴胺广播 × 突触资格迹 = 只有"最近参与了行为"的突触被永久修改
- 等待期间的随机神经活动不符合 STDP 时序 → 无资格迹 → 不被多巴胺强化

这是一个**分布式、局部的计算**：没有中央处理器需要知道"哪些突触应该被强化"；每个突触通过自身的资格迹状态自动"举手表示资格"。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 纹状体 1.5s 多巴胺时窗（资格迹寿命） | 两光子成像 + 光遗传，单棘分辨率，直接测量 | PMID:25258080 (PMC4225776) | 高 |
| 皮层 STDP 需神经调质门控才产生持久变化 | 皮层切片 STDP × 200 次 + NE/5-HT | He et al. 2015（via PMID:30108488） | 中（单实验室） |
| 海马 BTSP 时间窗 ±3-4 秒 | 离体全细胞记录 + 在体行为实验 | PMID:28883072 (PMC7289271) | 高 |
| 理论框架：三因素规则统一各系统 | 综合数学模型 + 5个实验系统综述 | PMID:30108488 (PMC6079224) | 高（理论一致性） |
| 离体→体内验证缺失 | 清醒行为动物中直接测量资格迹状态 | — | 低（技术瓶颈） |

## 连接

- [[three-factor-learning-rule]] — 资格迹是三因素规则的中间变量；Δw = e_ij × M_3rd(t)
- [[stdp]] — STDP 事件是设置资格迹的赫布触发器（f_j × g_i 项）
- [[dopamine-reward-prediction-error]] — 多巴胺 RPE 是奖励学习中将资格迹转化为权重变化的 M_3rd
- [[synaptic-tagging-capture]] — STC 是资格迹的原型前辈：突触标签（小时级）类比资格迹（秒级），但两者时间常数相差 3 个数量级
- [[btsp]] — BTSP 是资格迹的极端案例：海马中由树突钙平台电位触发的秒级资格迹，无需峰电位因果时序
- [[backpropagating-action-potential]] — bAP 是 STDP 事件的"突触后时序信号"，因此也是触发皮层/海马资格迹的部分必要条件
- [[ltp]] — LTP 是资格迹在第三因素（M_3rd > 0）到来时的最终表达形式
- [[hebbian-learning]] — 赫布规则是资格迹设置的逻辑（协同激发才设旗）

## 未解问题

- **Q-three-factor-time-window**：不同脑区（纹状体 1-2s、皮层 5-10s、海马 ±3-4s）的资格迹时间常数差异巨大，是否有统一机制？是否与突触类型、树突位置有关？
- **Q-stc-molecular-tag**：皮层资格迹的分子实体是什么？（纹状体已知为 PDE10A/CaMKII；皮层缺乏类似直接证据）
- **分钟/小时级延迟奖励**：经典条件反射 CS-US 间隔可达数十秒，靠何种机制实现（不可能是同一种资格迹）？
- **体内清醒动物验证**：目前所有直接测量都来自离体切片；在清醒行为动物中，能否实时追踪单突触资格迹状态？

## 修订历史

- 2026-08-28 · 创建 · 基于《信用的时间归属》一文（#128）· 填补 metaplasticity → stdp → three-factor-learning-rule 链条中的关键缺失节点；整合 Yagishita 2014 / Bittner 2017 / Gerstner 2018 的实验证据 · 初始置信度：高

## 来源文章

- [[2026-08-28-three-factor-learning-rule-eligibility-traces]]

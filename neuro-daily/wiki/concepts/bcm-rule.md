---
title: BCM 规则
slug: bcm-rule
domain: concepts
type: theory
status: mainstream
confidence: high
created: 2026-08-27
updated: 2026-08-27
revision_count: 1
dimensions: [synaptic, cellular, cognition, behavior]
related: [metaplasticity, hebbian-learning, ltp, ltd, stdp, critical-period, visual-cortex-plasticity, homeostatic-plasticity]
prerequisites: [hebbian-learning, ltp, nmda-receptor, synaptic-transmission]
opens_questions: [Q-bcm-01, Q-bcm-02]
source_articles: [2026-08-27-metaplasticity-bcm-sliding-threshold]
key_sources: ["PMID:1765807", "PMID:8182481", "PMID:11675507", "PMID:8658594", "PMID:20554832"]
---

# BCM 规则 (Bienenstock-Cooper-Munro Rule)

> **一句话定义**：BCM 规则描述突触修改方向如何由突触后活动相对于一个**滑动修改阈值（θ_m）**决定：y > θ_m 产生 LTP，y < θ_m 产生 LTD，而 θ_m 本身随近期平均活动超线性升高——这形成了一个内置的负反馈稳定机制。

## 当前理解

我们现在认为，BCM 规则（Bienenstock, Cooper & Munro 1982, J Neurosci 2:32-48）是对 Hebbian 学习规则的重要扩展，它在数学上解决了纯 Hebb 规则的稳定性危机（正反馈导致突触权重无限增长或归零），并准确预言了视觉皮层中一系列经验依赖可塑性现象。

**BCM 规则核心方程**：

> Δw ∝ φ(y, θ_m) · x

其中：
- x = 突触前活动
- y = 突触后活动
- θ_m = 滑动修改阈值
- φ(y, θ_m) = 非单调函数：当 y > θ_m → 正（LTP）；当 0 < y < θ_m → 负（LTD）；当 y ≈ 0 → 零

**滑动阈值规则**：

> θ_m ∝ ‹y²›_t（近期突触后活动的时间平均的二次方，或某等价超线性函数）

其含义：活动越高，阈值越高；活动越低，阈值越低。

**稳定性分析**：θ_m 的超线性依赖（非线性 > 1次方）保证了系统存在稳定不动点：突触权重不会无限增大，也不会趋向零。

## 关键机制

### 视觉皮层实验验证（BCM 的"实验室"）

BCM 理论的主要验证来自猫/小鼠视觉皮层的可塑性实验：

1. **单眼剥夺（Monocular Deprivation）**：闭合一眼后，剥夺眼通路的 θ_m 下降（活动低 → 阈值低），最终导致该通路的突触反而更容易被 LTD 驱动（因为 y 相对于更低的 θ_m 也是低的，见于去极化较少的情形）。Clothiaux, Bear & Cooper 1991 仿真结果与实验一致（PMID: 1765807）。

2. **视觉皮层 LTD**：BCM 预言低频刺激（y < θ_m）应能诱导 LTD。Kirkwood & Bear 1994（PMID: 8182481）直接实验验证：1 Hz 低频刺激在视觉皮层确实诱发 NMDA 受体依赖性 LTD，且依赖蛋白磷酸酶 1/2A（冈田酸敏感），完全符合 BCM 框架的磷酸化/去磷酸化双向调节预言。

3. **黑暗饲养（Dark Rearing）**：剥夺视觉经验后，LTP 阈值降低，LTD 阈值升高 → 黑暗饲养动物更容易诱发 LTP，更难诱发 LTD。这与 BCM 对 θ_m 随活动降低而下降的预言完全一致，且与 GluN2B/GluN2A 比例在暗养后增高相对应。

### θ_m 的分子实现

BCM 的 θ_m 不对应单一分子，而是多条分子机制共同决定的阈值水平（详见 [[metaplasticity]]）：
- NMDA 受体 GluN2B→GluN2A 切换（改变 Ca²⁺ 内流时间窗口）
- Ih 电流（改变树突兴奋性，全局性影响 θ_m）
- CaM/RC3/CaMKII 磷酸化状态（改变 Ca²⁺ 的下游激酶响应）
- mGluR 状态（预处理后锁定可塑性范围）

### 从 BCM 到 STDP 的关系

STDP（见 [[stdp]]）描述的是"毫秒时序差异决定 LTP/LTD 方向"，而 BCM 描述的是"近期活动历史决定 LTP/LTD 阈值"。两者是互补的：

- STDP 是细粒度的时序规则（输入信号的局部特征）
- BCM 是粗粒度的历史调控规则（神经元的全局状态）
- 理论整合：BCM 的 θ_m 是 STDP 规则的"可塑性窗口宽度调节器"——θ_m 高时 STDP 的 LTP 窗口有效范围收窄，θ_m 低时 LTP 更容易被诱发

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| BCM 单参数集能拟合多种视觉经验条件下的皮层可塑性 | 计算模型 vs 多种实验数据 | Clothiaux, Bear & Cooper 1991 (PMID:1765807) | 高 |
| BCM 预言的低频 LTD 在视觉皮层存在，磷酸酶依赖 | 脑片电生理 + 药理 | Kirkwood & Bear 1994 (PMID:8182481) | 高 |
| NMDA 亚基组成变化实现 BCM 滑动阈值 | 生物物理模型 | Castellani et al. 2001 (PMID:11675507) | 中（模型，需更多体内验证） |
| Ih 电流作为 θ_m 的全局调控候选 | 计算模型 | Narayanan & Johnston 2010 (PMID:20554832) | 中（计算，体内验证不足） |

## BCM 规则的局限性

1. **原版 BCM 无误差信号**：它是无监督的，无法学习与特定目标对应。现代三因素学习规则（多巴胺 RPE 作为第三因素）在 BCM 基础上加入了目标导向调控。
2. **θ_m 时间常数未精确确定**：从数分钟到数天，不同实验系统差异很大，可能反映多个时间尺度的机制叠加。
3. **空间解析度**：BCM 原始版本是针对单细胞的，对于多突触神经元，θ_m 的空间异质性（不同树突分支可能有不同的局部 θ_m）尚未被充分整合到 BCM 框架中。

## 连接

- [[metaplasticity]] — BCM θ_m 滑动即元可塑性的数学形式化
- [[hebbian-learning]] — BCM 是 Hebb 规则的稳定化扩展
- [[ltp]] — y > θ_m 时的突触增强过程
- [[ltd]] — 0 < y < θ_m 时的突触减弱过程
- [[stdp]] — 毫秒时序规则，与 BCM 在不同时间尺度上互补
- [[critical-period]] — 关键期结束部分由 θ_m 系统性升高解释

## 未解问题

- **Q-bcm-01**（高优先级）：θ_m 滑动的确切时间常数，以及它是否在不同脑区和不同发育阶段有实质性差异？
- **Q-bcm-02**（中优先级）：如何在体内清醒动物中直接测量 θ_m 的变化（而非仅通过诱导 LTP/LTD 的难易程度间接推断）？

## 修订历史

- 2026-08-27 · 创建 · 基于《可塑性的守门人：BCM 规则与元可塑性如何防止突触失控》· 初始置信度：高

## 来源文章

- [[2026-08-27-metaplasticity-bcm-sliding-threshold]]

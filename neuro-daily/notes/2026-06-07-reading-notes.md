# 2026-06-07 阅读笔记：短时程突触可塑性（STP）

## 研究问题
突触在连续激活时如何在毫秒到秒时间尺度上改变释放概率？突触易化和抑制的分子机制是什么？Syt7 在易化中的角色？STP 如何连接到工作记忆？

---

## 来源 1：Regehr WG (2012) "Short-term presynaptic plasticity"
**PMID**: 22751149 / PMC: 3385958 (开放全文)
**期刊**: Cold Spring Harb Perspect Biol

### 要解决什么问题
系统梳理突触前短时程可塑性的分子机制：突触抑制（depression）、易化（facilitation）、增强（augmentation）和突触后强化效应（PTP）的机制与功能。

### 方法
文献综述，整合 1960 年代至 2011 年的电生理、钙成像和遗传学研究。

### 关键发现
- **抑制主要由囊泡耗竭驱动**：RRP（就绪囊泡池）在高频激活时被迅速消耗，恢复时间常数约为数百 ms 至几秒。囊泡耗竭是绝大多数中枢突触抑制的主要机制。
- **易化的"残余钙假说"定量上有困难**：Cares 约为 Calocal 的 1%，即使按 Ca⁴ 非线性计算，纯粹的残余钙叠加也只能解释约 4% 的增强，远不足以解释观察到的 2–5 倍易化。
- **钙缓冲蛋白饱和可解释部分易化**：Calbindin（快速高亲和力缓冲蛋白）在第一个 AP 后被钙"占满"，第二个 AP 时局部 Ca²⁺ 更多地到达 Syt1 附近 → 释放增强
- **PTP 机制**：线粒体钙缓慢释放（数十秒）+ PKC 激活（磷酸化 Munc18-1）+ RRP 扩大（约 30%）
- **增强（augmentation）**：时间常数约 4–5 秒，机制包括残余钙长尾 + 囊泡补充加速

### 改变了什么理解
从单一"残余钙"视角（Katz & Miledi 1968 经典假说）走向多机制视角：不同形式的 STP 由不同分子机制驱动，时间常数和振幅也不同。

### 证据强度
综述性，包含多个高引实验；钙成像数据的定量分析较可信。

### 局限
2012 年综述，Syt7 作为易化分子基础尚未确立（Jackman 2016 在后）。

### 与认知的关系
提供了"突触是实时状态机"的基本框架，为后续 Tsodyks-Markram 模型和活动无声 WM 奠定机制基础。

### 需解释的术语
- **RRP**：readily releasable pool，位于活动区膜附近、已进入"就绪"状态的囊泡，约占总囊泡的几个百分点
- **Augmentation**：高频刺激后约 4–5 秒时间尺度的增强，有别于易化（<1 s）和 PTP（>10 s）

---

## 来源 2：Jackman SL, Turecek J, Belinsky JE, Regehr WG (2016) "The calcium sensor synaptotagmin 7 is required for synaptic facilitation"
**PMID**: 26738595 / PMC: 4729191 (开放全文)
**期刊**: Nature

### 要解决什么问题
突触易化的分子传感器是什么？残余钙是如何被"感知"并转化为释放增强的？

### 方法
Syt7 全身敲除小鼠（KO）和条件性病毒重表达；在多类突触（Schaffer 侧枝、丘脑皮层、苔藓纤维、穿通路）记录配对脉冲比（PPR）；点突变 Syt7（C2A 钙结合失活）恢复实验。

### 关键发现
- Syt7 KO → PPF 在上述四类突触**全部消失**；基础释放概率（通过 MK-801 封闭法、自发 mEPSC 频率等方法测量）不变
- Ca²⁺ 感应突变体（Syt7 C2A 双钙结合突变）表达到 KO 小鼠中 → 无法恢复易化
- CA3 锥体细胞选择性重表达 Syt7 → 仅恢复 CA3→CA1（Schaffer 侧枝）突触的易化，其他突触不受影响（细胞自主性证明）
- Syt7 的钙亲和力远高于 Syt1（对应毫秒尺度残余钙信号 ~1–5 μM），Syt1 的亲和力低（对应纳米域峰值 ~20–100 μM）
- 配对脉冲易化幅度：WT 约 2 倍增强，KO 接近 1（无易化）

### 改变了什么理解
突触易化不是简单的"更多钙叠加"物理效应，而是由特化的高亲和力慢速钙传感器（Syt7）主动介导。Syt7 与 Syt1 在同一终末共存，各自负责不同时间尺度的钙响应。

### 证据强度
非常高。Nature 发表，多类突触验证，多种实验方法（PPR、MK-801、失活突变体、细胞自主性实验）。

### 局限
仅在小鼠（啮齿类）验证；Syt7 的精确分子作用方式（与 SNARE 的相互作用、在突触前膜的确切位置）尚未完全阐明。

### 需解释的术语
- **C2A 结构域**：Syt 蛋白的两个关键钙结合结构域之一，Syt7 的 C2A 对钙亲和力更高（而 Syt1 的 C2B 更关键）

---

## 来源 3：Turecek J, Regehr WG (2018) "Synaptotagmin 7 Mediates Both Facilitation and Asynchronous Release at Granule Cell Synapses"
**PMID**: 29593071
**期刊**: Journal of Neuroscience

### 关键发现
- 小脑颗粒细胞突触的 Syt7 KO → 易化减少 + 异步释放（AR，动作电位后数毫秒内仍持续的递质释放成分）也减少
- 初始释放概率在 KO 中不变，与 Jackman 2016 一致
- 但两种效应（易化和异步释放）在时间常数和钙敏感性上有所不同 → Syt7 的功能可能比单纯"检测残余钙-触发易化"更复杂

### 重要性
说明 Syt7 是一个更广义的"低钙信号传感器"，参与多种时间尺度的突触前增强；并不只是"易化"的专用分子

---

## 来源 4：Mongillo G, Barak O, Tsodyks M (2008) "Synaptic theory of working memory"
**PMID**: 18339943
**期刊**: Science（订阅，未读取全文）

### 要解决什么问题
工作记忆是否需要持续的神经元放电？突触的短时程易化能否作为信息的"无声储存"基质？

### 方法
计算模型（循环网络 + STP，基于 Tsodyks-Markram 框架）

### 关键发现（基于摘要和引用）
- 工作记忆可以无需持续放电，通过突触 STP 易化"沉默地"维持数百毫秒至秒
- 偶发的 γ 爆发足以读取和刷新无声储存的记忆内容
- 模型预测：延迟期 PFC 放电率可以低于我们的预期，而记忆容量不受影响

### 改变了什么理解
挑战了"持续高频放电 = 工作记忆维持"的经典图景（Goldman-Rakic 框架）。为后来 Lundqvist et al. 2016 发现 γ 爆发而非持续放电提供了理论框架。

### 证据强度
计算模型，中等（需要实验验证）

### 限制
- 计算模型而非体内测量
- 目前直接体内证据仍不足

---

## 来源 5：Tsodyks MV, Markram H (1997) "The neural code between neocortical pyramidal neurons depends on neurotransmitter release probability"
**PMID**: 9012851
**期刊**: PNAS

### 关键发现（基于摘要）
- 高释放概率（Pr）突触：慢速抑制（depression 主导）→ 下游细胞接收放电率（firing rate）信息
- 低释放概率突触：快速易化 → 下游细胞接收时间相干性（temporal coherence）信息
- 提出 u × x × A 的三参数模型

### 重要性
STP 不只影响单个突触的强弱，而是影响"哪类信息"被传递给下游神经元。

---

## 来源 6：Jackman SL, Regehr WG (2017) "The Mechanisms and Functions of Synaptic Facilitation"
**PMID**: 28472650
**期刊**: Neuron

### 关键内容（基于摘要）
- 系统回顾易化的分子机制（残余钙 vs. Syt7 vs. 缓冲蛋白饱和）
- 讨论易化在不同回路中的功能角色（爆发探测、工作记忆、增益控制）
- 指出现有理论多基于体外实验，体内功能验证仍有很大缺口

---

## 来源 7：Motanis H, Seay MJ, Buonomano DV (2018) "Short-Term Synaptic Plasticity as a Mechanism for Sensory Timing"
**PMID**: 30274605
**期刊**: Trends Neurosci

### 关键内容
- STP 使神经元可以区分不同时序模式（刺激间隔的区分）
- 不对称的 STP（某些方向的突触序列被易化型接力，另一个方向被抑制型）可产生方向选择性（弱电鱼的例子）
- 皮层 STP 多样性是时间计算不同"时钟分辨率"的来源

---

## 总结：今日核心洞见

1. STP 是突触在毫秒-秒时间尺度上的实时状态机，由残余钙（易化）和囊泡耗竭（抑制）驱动
2. Syt7 是突触易化的分子必要条件，将"残余钙假说"从物理推测升级为分子实体
3. Tsodyks-Markram 模型（A×u×x）提供了将 STP 纳入网络计算的数学语言
4. 活动无声工作记忆假说将 STP 连接到认知层，但直接体内证据仍需积累
5. 不同突触类型具有不同的 STP 特性，这种多样性是回路时序计算的功能资产，不是噪声

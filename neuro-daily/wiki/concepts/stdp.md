---
title: 突触时序依赖可塑性（STDP）
slug: stdp
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-06-19
updated: 2026-07-25
revision_count: 2
dimensions: [synaptic, molecular, cellular, microcircuit, cognition]
related: [nmda-receptor, ltp, ltd, hebbian-learning, three-factor-learning-rule, theta-oscillations, place-cells, btsp, synaptic-tagging-capture, dopamine-reward-prediction-error, dendritic-computation, short-term-synaptic-plasticity, barrel-cortex, critical-period, pv-interneurons]
prerequisites: [nmda-receptor, action-potential, synaptic-transmission, ltp]
opens_questions: [Q-stdp-physiological-ca, Q-stdp-inhibitory-synapses, Q-stdp-human-evidence, Q-stdp-all-ltp-molecular-switch]
source_articles: [2026-07-17-stdp-spike-timing-dependent-plasticity, 2026-07-25-barrel-cortex-somatosensory-map]
key_sources: ["PMID:9852584", "PMC6793365", "PMID:22920249", "PMC3431193", "PMID:34616278", "PMC8488271", "PMC10019887", "PMID:30018546", "PMC6037788", "PMID:30877173", "PMID:41002424"]
---

# 突触时序依赖可塑性 (STDP, Spike-Timing Dependent Plasticity)

> **一句话定义**：突触前神经元在突触后神经元放电之前激活（因→果），突触增强（LTP）；反之（果先于因），突触减弱（LTD）——NMDA 受体通过双重门控机制在毫秒级时序中充当"时序仲裁者"，将放电顺序转化为连接强弱的变化。

## 当前理解

我们现在认为，STDP 是 Hebb 规则的时间分辨精化版本：它不仅要求突触前和突触后活动"共同发生"，还要求突触前先于突触后激活才能诱导 LTP，反向则诱导 LTD。这一规则的分子基础是 NMDA 受体的双重门控机制：谷氨酸结合（突触前信号）+ 突触后去极化（来自反向传播动作电位 bAP）的时间重叠，产生不同幅度的 Ca²⁺ 内流——高峰 Ca²⁺ 激活 CaMKII→LTP，低流 Ca²⁺ 激活钙调磷酸酶→LTD。

STDP 被发现于 1997–1998 年（Markram et al. 1997, PMID:8985014；Bi & Poo 1998, PMID:9852584），揭示了大脑学习规则中存在精确的因果方向性检测能力。然而，STDP 并非单一规则，而是一个家族：不同脑区有不同形式（NMDAR-LTD 或 CB1-LTD），不同频率下有不同结果，树突不同位置有不同效果（bAP 衰减梯度）。

**关键未解问题**：生理钙浓度（1.3–1.8 mM）下，经典的单次毫秒配对无法诱导 STDP（Inglebert & Debanne 2021，PMC8488271）——提示体内 STDP 需要 θ 振荡背景（5–12 Hz）作为必要条件。

## 关键机制

### 1. 时序窗口（经典形式，海马/皮层 L2/3）

```
Δw (突触变化)
  +  LTP←——     
     ──────┬────────── Δt（突触后 - 突触前，ms）
           0
         ——→ LTD
  -
```

- **LTP 窗口**：Δt = +1 to +20 ms（突触前先）→ 约 48% EPSC 增幅（Bi & Poo 1998）
- **LTD 窗口**：Δt = -1 to -20 ms（突触后先）→ 约 18% EPSC 减幅
- **过渡**：LTP→LTD 切换在 ±5 ms 内完成

### 2. 分子机制：NMDA 受体作为时序仲裁者

**突触前先（LTP 情形）**：
1. 突触前释放谷氨酸 → 谷氨酸与 NMDA 受体结合，部分解锁
2. 约 5–15 ms 后，bAP 抵达树突棘 → 膜去极化 → Mg²⁺ 完全去阻断
3. 两者时间重叠 → NMDA 受体充分开放 → 高峰 Ca²⁺ 内流
4. 高 Ca²⁺ → CaMKII 激活（自磷酸化）→ AMPA 受体插入 → LTP

**突触后先（LTD 情形）**：
1. bAP 先到达，Mg²⁺ 被临时去除，但此时无谷氨酸
2. 当谷氨酸随后到达时，膜电位已复极化，Mg²⁺ 可能重新占据
3. 低幅度、持续的 Ca²⁺ 内流（通道未能充分开放）
4. 低 Ca²⁺ → 钙调磷酸酶优先激活 → AMPA 受体内吞 → LTD

### 3. 两种 STDP 形式（Feldman 2012，PMC3431193）

| 形式 | 脑区 | LTP 机制 | LTD 机制 |
|------|------|---------|---------|
| 形式一 | 海马 CA1，皮层 L2/3 | NMDAR-Ca²⁺ → CaMKII | NMDAR-Ca²⁺ → 钙调磷酸酶 |
| 形式二 | 体感/视觉皮层，纹状体 | NMDAR → CaMKII | mGluR + 内源大麻素(CB1)→ 突触前递质降低 |

### 4. 频率和位置依赖

- **频率**：10–30 Hz 内 STDP 最有效；<10 Hz 仅 LTD；>30 Hz 无视时序
- **近端突触**（<100 μm）：健壮 Hebbian STDP
- **远端突触**（>500 μm）：bAP 衰减 >50%，倾向 anti-Hebbian LTD 或无效

### 5. 生理条件的约束（Inglebert & Debanne 2021）

| [Ca²⁺]e | 结果 |
|---------|------|
| 1.3 mM（生理） | 无可塑性 |
| 1.8 mM（接近生理） | 仅 LTD |
| 3.0 mM（体外常规） | 经典 Hebbian STDP |

→ 生理条件下，需要 5–10 Hz 背景频率（θ 振荡）才能恢复 STDP

### 6. 发育期STDP的多样性：全LTP型→赫布型的切换（桶状皮层案例）

桶状皮层研究揭示了一种在海马/皮层L2/3经典STDP之外的**发育性STDP多样性**：同一突触类型（L4→L2/3）在不同发育阶段遵循根本不同的STDP规则（Kimura & Itami 2019，PMID:30877173；Itami & Kimura 2025，PMID:41002424）：

| 发育阶段 | STDP类型 | 信号通路 | 功能目的 |
|---------|---------|---------|---------|
| 关键期前（<P13，突触形成期） | **全LTP型STDP**（all-LTP STDP）：无论前→后还是后→前，突触均增强 | PKA→NMDA | 初始连接的保守性建立：不因随机时序误差而削弱有用突触 |
| 关键期开启后（P13–P15+） | **赫布型STDP**：前→后=LTP，后→前=LTD | CaMKII→NMDA | 精确的经验依赖竞争：地图可塑性 |

**切换机制**：PV+中间神经元成熟（约P14）为L4→L2/3突触创造精确时序约束——被刺激触须的信号产生L4领先L2/3的时序（→LTP），被剥夺触须产生逆序时序（→LTD）。无PV精确约束时，随机配对多数结果是LTP（→全LTP STDP的表观效果）。

**概念意义**：这揭示了NMDA受体是"可被重新接线到不同下游通路（PKA vs CaMKII）的可编程时序传感器"——同一受体可以执行不同的学习规则，取决于回路的成熟状态。"STDP规则"不是固定的，而是由细胞类型发育状态动态决定的。

### 7. 体内 STDP：θ 振荡的角色（PMC10019887）

θ 相位前进（theta phase precession）将行为轨迹压缩进 STDP 窗口：
- 动物穿越场所场时，场所细胞放电相位在 θ 周期内逐渐提前
- 相邻场所（A→B）的场所细胞放电时序差压缩至 ~20 ms → 落入 LTP 窗口
- 路径方向性自动编码进突触权重不对称性

模型验证：STDP + θ 前进 → R²=0.87 vs TD 后继表征；5 min 学习 75% 权重；无 θ → R²=0.63，慢 4.5 倍

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| LTP 窗口 +20ms，LTD 窗口 -20ms | 培养海马神经元双全细胞记录，60次配对 | PMID:9852584, PMC6793365 | 高 |
| 两种 STDP 形式（NMDAR-LTD vs CB1-LTD） | 多脑区对比综述 + 药理学阻断实验 | PMC3431193 | 高 |
| 生理钙浓度（1.3 mM）下经典 STDP 无法诱导 | CA3-CA1 突触，系统性钙浓度梯度测试 | PMC8488271 | 高 |
| θ 前进 + STDP → R²=0.87 vs TD 后继矩阵 | 计算建模，生物合理 SNN 参数 | PMC10019887 | 中（计算模型） |
| 新皮层 STDP 存在（bAP-EPSP 时序控制） | 大鼠体感皮层层5锥体神经元双全细胞记录 | PMID:8985014 | 高 |

## 连接

- [[nmda-receptor]] — NMDA 受体双重门控是 STDP 的分子执行器
- [[ltp]] — 前先后的 STDP 的细胞结果（AMPA 受体插入）
- [[ltd]] — 后先前的 STDP 的细胞结果（AMPA 受体内吞）
- [[hebbian-learning]] — STDP 是 Hebb 规则的时间分辨精化版本
- [[theta-oscillations]] — θ 振荡既是体内 STDP 的必要激活条件，又通过相位前进压缩轨迹进入 STDP 窗口
- [[place-cells]] — 场所细胞的 θ 相位前进是体内 STDP 空间学习的关键机制
- [[btsp]] — BTSP（行为时间尺度，秒级）是与 STDP（毫秒级）并行的另一种海马学习规则
- [[three-factor-learning-rule]] — Δw ∝ (pre×post)×M：DA/ACh/NE 调制 STDP 使学习具有目标导向性
- [[synaptic-tagging-capture]] — STC 解决 STDP 与秒级奖励的时间整合问题
- [[dendritic-computation]] — 树突位置梯度使远端突触的 STDP 规则与近端不同
- [[dopamine-reward-prediction-error]] — DA-RPE 作为三因素 STDP 的 M 因子
- [[barrel-cortex]] — 桶状皮层是 STDP 发育性切换（全LTP→赫布型）最清晰的研究系统
- [[critical-period]] — STDP 从全LTP到赫布型的切换是桶状皮层功能关键期开启的分子事件
- [[pv-interneurons]] — PV 成熟通过时序精确化使赫布型 STDP 成为可能

## 未解问题

- Q-stdp-physiological-ca：生理钙浓度（1.3 mM）下 STDP 的实际触发模式是什么？θ 振荡是唯一的使能条件，还是存在其他机制？
- Q-stdp-inhibitory-synapses：抑制性突触（GABAergic）上的 STDP 规则与兴奋性突触有什么根本性差异？其功能意义是什么？
- Q-stdp-human-evidence：人类 STDP 的直接电生理证据缺乏；现有的感知转移和 tACS 行为证据能否真正验证 STDP 机制？
- Q-stdp-all-ltp-molecular-switch：桶状皮层 L4→L2/3 从全LTP STDP 切换到赫布型的精确分子节点是什么？PKA→CaMKII 的切换是否由单一分子事件（CB1 受体出现？）触发，还是多条通路协调重配？

## 修订历史

- 2026-06-19 · 创建 · 基于《突触时序依赖可塑性：用毫秒级时间窗口书写神经因果律》一文 · 初始置信度：高；填补了 hebbian-learning.md 中长期悬空的 [[stdp]] 引用
- 2026-07-25 · 修订 rev2 · 基于《触须的神经地图》（#93）· 新增"发育期STDP多样性"小节：桶状皮层全LTP型→赫布型STDP的发育切换机制（Kimura & Itami 2019；Itami & Kimura 2025）；补充 barrel-cortex/critical-period/pv-interneurons 连接；新增 Q-stdp-all-ltp-molecular-switch

## 来源文章

- [[2026-07-17-stdp-spike-timing-dependent-plasticity]]
- [[2026-07-25-barrel-cortex-somatosensory-map]]

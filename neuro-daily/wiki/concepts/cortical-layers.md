---
title: 皮层六层架构
slug: cortical-layers
domain: concepts
type: structure
status: established
confidence: high
created: 2026-07-23
updated: 2026-08-11
revision_count: 2
dimensions: [cellular, microcircuit, brain-region]
related: [canonical-microcircuit, barrel-cortex, somatosensory-cortex, predictive-coding, thalamus, alpha-oscillations, gamma-oscillations, orientation-selectivity, thalamocortical-circuit, lissencephaly, cortical-migration-disorders, cortical-neurogenesis]
prerequisites: [action-potential, synaptic-transmission, cortical-homunculus]
opens_questions: [Q-cl-01, Q-cl-02, Q-cl-03]
source_articles: [2026-07-23-cortical-layers-canonical-microcircuit]
key_sources: ["PMID:1666655", "PMID:23177956", "PMID:22798946", "PMID:23983048", "PMID:1822724"]
---

# 皮层六层架构（Cortical Layers）

> **一句话定义**：哺乳动物新皮层（2–4 mm 厚）由从表面到深部的六个神经细胞层构成（L1–L6），各层细胞类型和连接方向不同，共同实现"感觉前馈输入"（L4 接收丘脑，L2/3→前馈）与"自上而下反馈预测"（L5/6→反馈，L1 接收高级皮层）的解剖分工。

## 当前理解

我们现在认为，皮层六层不是装饰性分层，而是一套高度保守的**计算分工架构**：几乎所有哺乳动物的新皮层（从初级感觉皮层到前额叶）都呈现出相同的六层基本组织，尽管各层厚度随功能而异（初级感觉皮层 L4 极厚；运动皮层 L4 几乎消失）。

最重要的功能分工：
- **L4（颗粒层）**：接收丘脑的感觉前馈输入（但丘脑输入仅占 L4 突触的 10–20%；其余 80–90% 来自皮层内部），通过 L4 内部的高密度相互兴奋（连接率 25–36%）放大弱丘脑输入。
- **L2/3（浅层锥体层）**：接受 L4 前馈输入（单突触 EPSP 仅 0.7 mV，需 45–50 个 L4 细胞同时激活），实现高阈值"群体活动检测"；发出**前馈连接**（浅层起源）到更高级区域的 L4；在预测编码框架中对应"预测误差单元"，载波为 γ 振荡（30–80 Hz）。
- **L5（内锥体层）**：皮层到皮下和皮层间的主要输出通道（L5A→皮层；L5B→皮下/脊髓）；在预测编码框架中对应"预测/表征单元"，发出**反馈连接**（深层起源），载波为 α/β 振荡（8–20 Hz）。
- **L6（多形层）**：皮层-丘脑精确反馈投射（L6A），提供对丘脑活动的闭合控制；也参与皮层内横向调制。
- **L1（分子层）**：几乎无局部神经元体；接受来自高级皮层区域的长程**反馈轴突终末**，作用于本地锥体细胞的远端顶树突（NMDA spike 域），实现情境依赖的调制。

**层间连接的方向性法则**（Felleman & Van Essen 1991，PMID:1822724；Markov et al. 2014，PMID:23983048）：
- 前馈连接（feedforward/driving）：起源于浅层（L2/3），**终止于目标区域 L4**
- 反馈连接（feedback/modulatory）：起源于深层（L5/6），**终止于目标区域 L1/6，绕开 L4**

在灵长类视觉皮层，反馈连接数量约是前馈的 2:1，V1 中来自高级区域的反馈轴突终末面积是前馈的 12 倍——感觉皮层接受的"预测"远多于"数据"。

## 关键机制

### 层间信号流（以桶状皮层为模型）

```
丘脑 VPM ──（主要输入，10–20%突触）──→ L4 棘星形细胞
    ↓                                    ↓（内部相互兴奋放大，25–36%连接率）
L4群体激活 ──（单向，高阈值门控）──→ L2/3 锥体细胞
                                         ↓（侧向广播 + 前馈上行）
                                        L5 锥体细胞（A：皮层；B：皮下）
                                         ↓
                                        L6A 皮层-丘脑投射
                                         ↓
                                    返回丘脑 VPM（闭合回路）
```

### L4 内部放大机制

L4 棘星形细胞以 25–36% 的连接率高度互联，是皮层中最密集的局部连接之一。丘脑输入仅触发少量 L4 细胞，这些细胞通过相互兴奋（recurrent excitation）级联激活更多 L4 细胞，实现约 10 倍放大——这是 Douglas & Martin（1991，PMID:1666655）规范微回路的核心洞察。

### L4→L2/3 的高阈值门控

Feldmeyer 等（2002，PMID:11826166）定量测定：单对 L4→L2/3 突触的 EPSP 均值仅 0.7±0.6 mV，需要 **45–50 个 L4 细胞几乎同时放电**才能在 L2/3 触发动作电位（若 L4 爆发放电则只需 20–30 个）。此门控使 L2/3 仅响应 L4 的**显著群体激活**——实现了统计显著事件的选择性广播。

### L5/6 的双重输出

L5B（粗大锥体细胞）的轴突投射到皮下结构（纹状体、上丘、脑桥核、脊髓），通过与 POm 的"巨型突触"（giant synapses）驱动次级丘脑核爆发放电，是皮层→皮下运动命令的主要物理线路。L6A（皮层-丘脑投射）以列特异性方式精确反馈到丘脑相应核，调制"下一时刻丘脑向皮层发送什么"。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 丘脑输入仅占 L4 突触的 10–20% | 电镜 + 突触数量分析（猫、大鼠） | PMID:1666655 + PMID:22798946 | 高 |
| L4 内连接率 25–36%（皮层最高） | 双细胞膜片钳（大鼠桶状皮层体外） | PMID:22798946 | 高 |
| L4→L2/3 需45–50个细胞同时激活 | 双细胞膜片钳+定量计算（Feldmeyer 2002） | PMID:11826166 | 高 |
| 前馈：浅层→L4；反馈：深层→L1/6 | 305条灵长类连接解剖追踪（Felleman & Van Essen 1991） | PMID:1822724 | 高（多物种独立重复）|
| 反馈连接数量约是前馈的2:1 | 337条连接SLN定量（灵长类体内） | PMID:23983048 | 高 |
| L2/3=γ前馈，L5/6=α-β反馈 | 灵长类多脑区LFP+MEG记录（综述整合） | PMID:23177956 | 中（理论框架；啮齿类普适性有争议）|

## 连接

- [[canonical-microcircuit]] — 六层架构的简化三群体计算模型（Douglas-Martin 1991）
- [[barrel-cortex]] — 桶状皮层是六层回路研究最清晰的模型系统
- [[predictive-coding]] — Bastos 2012：L2/3=误差单元（γ/前馈），L5/6=预测单元（α-β/反馈）
- [[thalamus]] — L4（前馈输入门）和 L6（皮层-丘脑反馈）是丘脑-皮层双向耦合的解剖锚点
- [[alpha-oscillations]] — α/β 振荡是 L5/6 深层反馈投射的振荡特征
- [[gamma-oscillations]] — γ 振荡是 L2/3 浅层前馈投射的振荡特征
- [[orientation-selectivity]] — V1 方向选择性通过六层层间回路（L4→L2/3前馈+L6反馈调制）实现
- [[thalamocortical-circuit]] — 皮层六层是丘脑-皮层回路（TC-CT）的皮层侧组织原则

## 未解问题

- Q-cl-01（高优先级）：规范微回路在颗粒层缺失（agranular）的额叶/运动皮层中如何修订？这些区域的 L4 几乎不存在，前馈-反馈法则如何适配？
- Q-cl-02（高优先级）：γ-FF / α-β-FB 振荡分工在啮齿类和非视觉皮层的普适性（Westerberg 2024 对此提出挑战）
- Q-cl-03（中优先级）：中间通路（intermediate pathways）同时终止于 L4 和 L1/L6 的例外如何整合进统一框架？

## 修订历史

- 2026-07-23 · 创建 · 基于《皮层六层架构：大脑用六层细胞片实现感知与预测的解剖分工》(#91) · 初始置信度：高

## 来源文章

- [[2026-07-23-cortical-layers-canonical-microcircuit]]

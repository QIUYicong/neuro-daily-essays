---
title: 规范微回路
slug: canonical-microcircuit
domain: concepts
type: theory
status: established
confidence: high
created: 2026-07-23
updated: 2026-09-01
revision_count: 2
dimensions: [cellular, microcircuit, brain-region]
related: [cortical-layers, barrel-cortex, predictive-coding, ltp, pv-interneurons, thalamus, gamma-oscillations, alpha-oscillations, free-energy-principle, active-inference]
prerequisites: [cortical-layers, synaptic-transmission, action-potential]
opens_questions: [Q-cl-01]
source_articles: [2026-07-23-cortical-layers-canonical-microcircuit, 2026-09-01-free-energy-principle-active-inference]
key_sources: ["PMID:1666655", "PMID:23177956", "PMID:21647397"]
---

# 规范微回路（Canonical Microcircuit）

> **一句话定义**：由 Douglas & Martin（1991）基于猫视觉皮层提出的皮层通用电路模板——将皮层神经元简化为三个群体（浅层锥体/深层锥体/抑制中间神经元），核心洞察是丘脑输入仅充当"触发器"（约 10% 突触），皮层主要响应来自皮层内部相互兴奋（recurrent excitation），使皮层成为状态依赖的主动计算单元。

## 当前理解

我们现在认为，规范微回路是理解皮层层状计算的基础框架。Douglas & Martin（1991，J Physiol，PMID:1666655）在对猫视觉皮层进行系统胞内记录后发现，丘脑刺激诱发的皮层兴奋中，**真正来自丘脑输入的部分只是一小部分（约10%）**，大量响应来自 L4 棘星形细胞和锥体细胞之间的相互兴奋回路——皮层将弱丘脑信号放大约 10 倍，这个放大量取决于皮层当前的内部状态。

三群体模型：
1. **浅层兴奋细胞（L2/3 锥体细胞）**：接受 L4 和层内前馈输入；发出前馈轴突（→高级区域 L4）；在预测编码框架中被认定为"预测误差单元"
2. **深层兴奋细胞（L5/6 锥体细胞）**：接受浅层→深层的内部连接；发出反馈轴突（→低级区域 L1/6）；在预测编码框架中被认定为"预测/表征单元"
3. **抑制性中间神经元（主要是 PV+ 篮状细胞和 SST+ 细胞）**：接受兴奋细胞驱动，提供前馈抑制（feedforward inhibition）、反馈抑制（feedback inhibition）和侧向抑制，整形放电时窗和响应的稀疏性

基本操作：
- **前馈抑制（FI）**：传入轴突→抑制中间神经元→锥体细胞（快速、短时间窗）
- **相互兴奋（RE）**：锥体细胞轴突侧支→邻近锥体细胞（放大 + 持续 + 状态保持）
- **反馈抑制（FBI）**：锥体细胞→中间神经元→锥体细胞（调节增益，防止过度激发）

Shepherd（2011，PMID:21647397）进一步指出，这三种基本操作（FI/RE/FBI）也存在于三层旧皮层（嗅皮层、海马）中，支持规范微回路代表了皮层计算的进化保守核心。

Bastos 等（2012，PMID:23177956）将规范微回路与预测编码整合，赋予三群体以计算角色：浅层（误差/γ/前馈）vs 深层（预测/α-β/反馈）——这是将解剖、计算和振荡三层描述统一在一个框架内的里程碑综述。

## 关键机制

### 丘脑触发 + 皮层放大（核心洞察）

```
丘脑输入 （~10% L4突触）
    ↓ 弱触发
L4 棘星形细胞群
    ↓ 相互兴奋（25–36%连接率）
L4 群体激活（约10倍放大）
    ↓
浅层锥体（L2/3）激活
    ↓（分两路）
    ├→ 前馈（→上级区域 L4）
    └→ 内部前馈（→深层锥体 L5/6）
           ↓（分两路）
           ├→ 反馈（→下级区域 L1/6）
           └→ 内部反馈（→浅层锥体）
                [形成皮层内部递归回路]
```

### 状态依赖性（Attentional Modulation）

皮层放大量（相互兴奋的程度）取决于皮层当前的"内部状态"——受自上而下调制（注意、期望）和神经调质（ACh 增益、NE 信噪比）影响。这使皮层对相同的丘脑输入可以产生截然不同的响应（注意 vs 无关），而不需要改变任何硬件连接。

### 颗粒层缺失皮层中的修订

运动皮层和前额叶等"颗粒层缺失（agranular）"皮层几乎没有明显的 L4，丘脑输入（主要来自 MD 核，而非 VPM 等特异性核）更分散地投射到 L2/3 和 L5/6。这些区域的规范微回路变体尚在研究中（Q-cl-01）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 丘脑输入仅占 L4 突触的 ~10% | 猫和大鼠皮层电镜突触统计 | PMID:1666655；PMID:22798946 | 高 |
| 相互兴奋放大约为丘脑驱动的10倍 | 胞内记录+电路建模（猫 V1） | PMID:1666655 | 高（模型预测，与实验数据吻合）|
| 规范回路适用于嗅皮层/海马（三层皮层进化同源） | 比较解剖综述（Shepherd 2011） | PMID:21647397 | 中（比较框架）|
| L2/3=γ/误差，L5/6=α-β/预测的计算角色 | 多脑区 LFP/MEG 记录+综述整合（Bastos 2012） | PMID:23177956 | 中（框架性综述；啮齿类普适性有争议）|

## 连接

- [[cortical-layers]] — 规范微回路是六层解剖的功能提炼（三群体映射到六层）
- [[predictive-coding]] — Bastos 2012 将规范微回路与预测编码整合：浅层=误差/γ，深层=预测/α-β
- [[barrel-cortex]] — 桶状皮层提供了规范微回路的最精确定量验证（Feldmeyer 系列）
- [[ltp]] — LTP/LTD 修改相互兴奋回路的突触权重，是学习在规范微回路中的实现机制
- [[pv-interneurons]] — PV+ 篮状细胞是提供前馈抑制和整形放电时窗的主要中间神经元群体
- [[gamma-oscillations]] — γ 振荡来自 PV 中间神经元的快速抑制振荡，是 L2/3 误差信号的振荡载体
- [[alpha-oscillations]] — α/β 振荡主要来自深层（L5/6）的反馈投射，是预测信号的振荡载体

## 未解问题

- Q-cl-01（高优先级）：颗粒层缺失的额叶/运动皮层中，规范微回路如何修订？丘脑输入的分布和内部相互兴奋的组织方式有何差异？

## 修订历史

- 2026-07-23 · 创建 · 基于《皮层六层架构》文章(#91) · 初始置信度：高
- 2026-09-01 · 修订 · 基于《变分自由能与主动推断》(#132) · 确认规范微回路与 FEP/主动推断框架的关联；related 新增 free-energy-principle, active-inference

## 来源文章

- [[2026-07-23-cortical-layers-canonical-microcircuit]]
- [[2026-09-01-free-energy-principle-active-inference]]

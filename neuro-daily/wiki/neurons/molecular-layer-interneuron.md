---
title: 分子层中间神经元
slug: molecular-layer-interneuron
domain: neurons
type: structure
status: established
confidence: high
created: 2026-10-09
updated: 2026-10-21
revision_count: 2
dimensions: [cellular, synaptic, microcircuit, brain-region]
related: [purkinje-cell, parallel-fiber, climbing-fiber, cerebellar-ltd, rebound-potentiation, gap-junction-electrical-synapse, pv-interneurons, cerebellum, cerebellar-memory-transfer]
prerequisites: [purkinje-cell, inhibitory-synapse, cerebellar-ltd]
opens_questions: [Q-mli-01, Q-mli-02, Q-mli-03, Q-pf-04]
source_articles: [2026-10-09-mli-cerebellar-interneuron-plasticity, 2026-10-21-cerebellar-memory-transfer-task-difficulty]
key_sources: ["PMID:12062025", "PMID:38692278", "PMID:24600347", "PMID:26179122", "PMID:18855095", "PMID:40595477"]
---

# 分子层中间神经元 (Molecular Layer Interneuron, MLI)

> **一句话定义**：小脑皮层分子层中的 GABA 能抑制性中间神经元，包括篮状细胞和星状细胞两类，接收颗粒细胞平行纤维的兴奋性输入，对浦肯野细胞（PC）施加前馈抑制；在攀爬纤维（CF）误差信号驱动下，MLI 的多层可塑性与 PC 的 LTD 互补，共同放大运动学习信号，并在 LTD 被阻断时提供代偿通道。

## 当前理解

我们现在认为，分子层中间神经元不只是静态的前馈抑制元件，而是具有独立可塑性规则、能够参与小脑运动学习的**第二条学习通道**。

最初，MLI 被视为颗粒细胞→PC 兴奋性通路的侧抑制组件，功能是调节 PC 响应的侧向抑制（lateral inhibition）和时间精度。但 Jörntell & Ekerot（2002，PMID:12062025）的发现改变了这一图景：当攀爬纤维（CF）携带运动误差信号时，MLI 对相同平行纤维（PF）输入产生的可塑性变化，与浦肯野细胞的变化方向完全相反——这被称为"逆向可塑性"（inverse plasticity）。

Lackey 等人（2024，PMID:38692278）进一步揭示 MLI 内部的亚型分化：

- **MLI1**（"同步抑制型"）：表达 Cx36 缝隙连接蛋白（*Gjd2*），具脊棘状胞体，电偶联，毫秒尺度同步放电，**直接抑制浦肯野细胞**
- **MLI2**（"去抑制型"）：表达神经素蛋白 1（*Nxph1*），光滑胞体，无电偶联，**主要抑制 MLI1 而非 PC** → 实现对 PC 的间接去抑制（disinhibition）

这两种亚型构成双层控制：MLI1 提供同步抑制（"踩刹车"），MLI2 解除 MLI1 的抑制（"松刹车"），共同门控 PC 在运动学习中的可塑性窗口。

## 关键机制

### 解剖位置与接线

| 亚型 | 胞体位置 | 轴突靶点 | 分子标记 | 功能 |
|------|---------|---------|---------|------|
| 篮状细胞（basket cell，BC）| 分子层下部 | PC 胞体 + AIS（轴突始段） | - | 控制 PC 放电阈值 |
| 星状细胞（stellate cell，SC）| 分子层上部 | PC 树突 | - | 调控树突计算 |
| MLI1（现代亚型）| 分子层 | 浦肯野细胞 | Gjd2（Cx36），脊棘状 | 同步抑制 PC |
| MLI2（现代亚型）| 分子层 | MLI1（主要）| Nxph1，光滑 | 去抑制 PC |

注：经典的"篮状细胞 vs 星状细胞"分类（按轴突靶点位置）与新的"MLI1 vs MLI2"分类（按分子标记和接线模式）并非一一对应，但存在很大重叠：篮状细胞主要是 MLI1 的一部分。

### 逆向可塑性（PF→MLI 突触）

攀爬纤维误差信号决定 MLI 的 PF 突触可塑性方向，与 PC 完全相反：

| CF 状态 | PC 可塑性（PF→PC 突触） | MLI 可塑性（PF→MLI 突触）| 净效果 |
|--------|----------------------|------------------------|------|
| CF 存在（误差）| PF-PC LTD（PC 对该 PF 响应减弱）| MLI LTP（MLI 对该 PF 响应增强 → 更多 GABA → PC 被压制）| PC 输出双重减少 |
| CF 缺失（无误差）| PF-PC LTP（PC 对该 PF 响应增强）| MLI LTD（MLI 对该 PF 响应减弱 → 更少 GABA → PC 被解放）| PC 输出双重增加 |

（来源：Jörntell & Ekerot 2002，PMID:12062025）

### 反弹增强——抑制性突触 LTP（MLI→PC 突触）

除了 PF→MLI 的兴奋性突触可塑性，MLI→PC 的**抑制性突触**本身也能发生长时程增强，称为"反弹增强"（Rebound Potentiation，RP）：

1. CF 激活 PC → 复杂放电 → PC 内大量 Ca²⁺ 进入
2. Ca²⁺ → 钙调蛋白 → 激活 **β-CaMKII**
3. β-CaMKII 磷酸化 **GABARAP**（GABA_A 受体关联蛋白）
4. GABARAP 构象改变 → 促进 GABA_A 受体向 PC 突触膜聚集
5. 突触 GABA_A 受体**数量增加** → 相同 GABA 输入产生更大抑制电流

关键调控：**α-CaMKII/β-CaMKII 比值**决定 RP 是否可发生：α-CaMKII 占优时 RP 被抑制；β-CaMKII 占优时 RP 容易被诱导。

（来源：Hirano 2014，PMID:24600347，开放全文 PMC3927423）

### 篮状细胞特异性抑制 LTP（He et al. 2015）

He 等人（PMID:26179122）发现，RP 在空间上是**输入特异性**的：
- **篮状细胞（BC）→PC 突触**（胞体/AIS）：可发生 LTP，依赖 β2 亚基含有型 GABA_A 受体 + CaMKII 磷酸化 → 新受体插入突触
- **星状细胞（SC）→PC 突触**（树突）：相同条件下不发生同类 LTP

这意味着运动学习中的抑制性门控主要由篮状细胞承担——靠近 AIS 的抑制控制直接影响 PC 是否能产生动作电位。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| MLI 与 PC 在 CF 信号下发生逆向双向可塑性 | 猫在体电生理，感受野可塑性测量 | PMID:12062025 | 中-高 |
| MLI1 电偶联驱动同步放电，MLI2 实现 PC 去抑制 | scRNA-seq + EM + 在体电生理，小鼠 | PMID:38692278（PMC11360088）| 高 |
| RP 诱导：Ca²⁺ → β-CaMKII → GABARAP → GABA_A 受体增加 | 离体培养 PC 电生理 + 基因操控 | PMID:24600347（PMC3927423）| 高 |
| RP 阻断 → VOR 适应受损（因果证据）| 转基因小鼠（γ2 肽链阻断 GABARAP 磷酸化）| PMID:24600347 | 高 |
| RP 增加受体数量而非电导（NSFA 分析）| 非稳态涨落分析 | PMID:26930485（PMC4773004）| 高 |
| BC 特异性 LTP 依赖 β2-GABA_A + CaMKII | 脑片膜片钳 + 选择性阻断 | PMID:26179122 | 高 |
| 星状细胞 PF 突触 AMPAR 亚型切换 | 离体培养 | PMID:18855095 | 中（仅摘要）|

## 连接

- [[purkinje-cell]] — MLI 对 PC 施加前馈抑制，也通过 RP 接受 PC 的反馈信号调控
- [[cerebellar-ltd]] — PF-PC LTD 与 MLI 逆向可塑性互补，共同利用 CF 误差信号
- [[rebound-potentiation]] — MLI→PC 抑制性突触的长时程增强机制
- [[climbing-fiber]] — CF 是 MLI 逆向可塑性的指令来源
- [[parallel-fiber]] — PF→MLI 突触是 MLI 可塑性的主要位点
- [[cerebellum]] — MLI 是小脑皮层多层可塑性系统的重要组成
- [[gap-junction-electrical-synapse]] — MLI1 通过 Cx36 电偶联实现同步放电
- [[pv-interneurons]] — PV 是 MLI 的标志性标记蛋白之一；与新皮层 PV 中间神经元有功能类比
- [[cerebellar-memory-transfer]] — MLI 逆向可塑性是"皮层内部代偿通道"，与"皮层→核团跨区域转移"是两个不同维度，二者互补而非竞争

## 未解问题

- **Q-mli-01**（高优先级）：MLI 逆向可塑性（Jörntell & Ekerot 2002）是否在小鼠中以相同分子形式存在？光遗传学+钙成像能否在啮齿类中验证？
- **Q-mli-02**（高优先级）：MLI2 自身的突触可塑性规则是什么？在 CF 信号下，MLI2→MLI1 突触是否也发生 LTP/LTD？这是否是去抑制门控的分子基础？
- **Q-mli-03**（中优先级，rev2补充视角）：当 PF-PC LTD 和 RP 同时被阻断时（双重阻断），是否出现比单独阻断更严重的运动学习缺陷？这将决定两者的代偿关系。2026-10-21新增视角（Bae 2025）：双重阻断实验的结果可能还需要按任务难度分层解读——若任务足够"容易"，即使双重阻断皮层内部通道，核团独立学习仍可能足以支撑表现，因此需要与核团失活联合设计才能真正区分"皮层内代偿"与"皮层外转移"两种解释。
- **Q-pf-04**（关联，中优先级）：皮层内部代偿通道（MLI逆向可塑性、反弹增强）与跨区域转移的相对贡献如何随任务难度变化？见 [[cerebellar-memory-transfer]]。

## 修订历史

- 2026-10-09 · 创建 · 基于《误差的双重利用：分子层中间神经元如何在浦肯野细胞的阴影里构建第二条学习通道》（文章 #169）· 初始置信度：高（MLI1/MLI2 亚型有高质量 2024 证据；RP 机制有转基因因果证据）
- 2026-10-21 · 修订 rev1→rev2 · 基于《记忆搬家的经济学：任务难度如何决定运动学习记忆留在小脑皮层还是搬进深部小脑核》（文章 #189）· 新增：连接 cerebellar-memory-transfer；Q-mli-03 补充任务难度维度的实验设计视角；新增key_sources：PMID:40595477

## 来源文章

- [[2026-10-09-mli-cerebellar-interneuron-plasticity]]
- [[2026-10-21-cerebellar-memory-transfer-task-difficulty]]

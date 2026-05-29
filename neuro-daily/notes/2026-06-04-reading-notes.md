# 阅读笔记 · 2026-06-04
## 主题：长时程抑制（LTD）——突触弱化的精准分子机制

---

### 来源 1：Huganir & Nicoll (2013) — *Neuron* — PMID:24183021 (PMC4195488)
**"AMPARs and synaptic plasticity: the last 25 years"**

**解决什么问题**：综述过去25年 AMPA 受体在突触可塑性中角色的理解演变，重点梳理 LTP 和 LTD 的分子机制。

**核心方法**：叙述性综述，汇集了数百个体外电生理学、基因敲除/敲入、超分辨成像的实验证据。

**关键发现**：
- NMDA-LTD：低 Ca²⁺ → PP2B（钙调磷酸酶）→ PP1 → GluA1 Ser831/Ser845 去磷酸化 → AMPAR 内吞
- GluA2 Ser880 磷酸化（PKC）→ 破坏 GRIP1/2 结合 → 促进 PICK1 结合 → 内吞
- mGluR-LTD：不依赖 NMDA 受体，需要翻译
- 小脑 LTD：PKC 而非 PP2B，严格依赖 GluA2（非 GluA3），不依赖 NMDA 受体
- GluA2/GluA3 双敲除小鼠海马 LTD 仍然正常 → LTD 有多条表达路径（重要争议）
- NMDA 受体非竞争性拮抗剂（MK-801）不完全阻断 LTD → "代谢型 NMDA 受体"假说（争议）

**改变了什么理解**：明确 LTD 是主动的分子过程，不同脑区使用不同机器，但最终效应（AMPAR 内吞）相同。

**证据强度**：高（经典综述，多年积累，同行共识）

**局限**：没有单一统一的 LTD 分子模型；证据来自不同物种和突触类型，整合需谨慎

**与认知的关系**：突触"遗忘"是主动设计；LTD 是 LTP 的对称补充，共同实现双向权重调节

---

### 来源 2：Bhattacharyya et al. (2009) — *Nat Neurosci* — PMID:19169250 (PMC2694745)
**"A critical role for PSD-95/AKAP interactions in endocytosis of synaptic AMPA receptors"**

**解决什么问题**：PSD-95 如何精确定位钙调磷酸酶于突触以支持 LTD？

**核心方法**：shRNA 敲减 + 共免疫沉淀 + 定点突变（L460P）+ AMPA 受体内吞定量荧光成像（海马神经元）

**关键发现**：
- PSD-95 通过其 SH3-GK 结构域与 AKAP150 结合，将钙调磷酸酶锚定于突触
- PSD-95 敲减 → NMDA 触发的 AMPAR 内吞几乎完全消失（~95% 减少）
- **选择性**：PSD-95 敲减不影响 mGluR 触发的 AMPAR 内吞 → 两条路径使用完全不同的分子机器
- AKAP150 缺少 PP2B 结合域的突变体（ΔAKAP-PP2B）也完全阻断 NMDA-LTD

**改变了什么理解**：空间定位（PSD-95/AKAP150 复合体将 PP2B 定位在 NMDAR 旁边）是 LTD 选择性的关键；NMDA-LTD 和 mGluR-LTD 是两条独立的内吞路径，而非同一路径的不同入口。

**证据强度**：高（原始研究，多个正交实验）

**局限**：主要在培养神经元，in vivo 验证的数据较少；小鼠年龄/发育阶段是否影响结论未详细讨论

**需要解释的术语**：AKAP（A 激酶锚定蛋白）= 将 PKA 和其他激酶/磷酸酶锚定到特定胞内位置的支架蛋白家族

---

### 来源 3：Hanley (2014) — *Front Cell Neurosci* — PMID:25429259 (PMC4150421)
**"Actin-dependent mechanisms in AMPA receptor trafficking and synaptic plasticity"**

**解决什么问题**：肌动蛋白（actin）细胞骨架如何调控 AMPAR 的运输？

**核心方法**：文献综述，汇集细胞骨架、AMPAR trafficking 相关研究

**关键发现**：
- LTD 时：肌动蛋白去聚合（树突棘收缩）与 AMPAR 内吞同时发生
- Arc 直接与 dynamin 和 endophilin（内吞机器核心蛋白）结合，促进网格蛋白内吞囊泡的 GTP 水解（动力学驱动）
- 肌动蛋白分枝（Arp2/3）控制内吞囊泡的出芽
- cofilin（肌动蛋白切割蛋白）在 LTD 中被 LIMK 调控，影响棘内肌动蛋白动力学

**改变了什么理解**：AMPAR 内吞不是孤立的膜蛋白运动，而是与树突棘整体细胞骨架重塑协调进行的事件；Arc 是连接化学信号（mGluR 激活）和机械内吞机器的关键接口。

**证据强度**：中-高（综述，但原始实验证据充分）

**局限**：肌动蛋白功能是双向的（LTP 时也涉及），如何区分 LTP/LTD 中的肌动蛋白动力学差异尚不完整

---

### 来源 4：Bramham et al. (2010) — *Exp Brain Res* — PMID:19690847 (PMC2803749)
**"The Arc of synaptic memory"**

**解决什么问题**：Arc/Arg3.1 在突触可塑性中的多功能角色

**核心方法**：叙述性综述 + 体内实验数据总结

**关键发现**：
- Arc mRNA 在神经元活动后数分钟内从核输出，在激活的树突棘中累积并翻译
- Arc 有两个主要功能：(a) LTP 中：激活 PAK，促进 cofilin 磷酸化（稳定棘内肌动蛋白），参与晚期 LTP 巩固；(b) LTD 中：与 dynamin 和 endophilin 结合，促进 AMPAR 内吞
- Arc 的表达水平是活动的"量规"：高活动 → 大量 Arc → AMPAR 内吞 → 突触稳态下调（防止饱和）
- Arc 敲除小鼠：LTP 可以诱导但不能巩固；LTD 受损；空间学习障碍

**改变了什么理解**：Arc 是一个"活动传感器—突触调制器"，根据活动量调节 AMPAR 密度；它的双向功能（LTP 巩固 + LTD 执行）体现了突触可塑性的精细平衡。

**证据强度**：高（综述，基于多个独立实验室的体内外证据）

**局限**：Arc 的"量规"功能和"执行"功能在同一细胞中如何区分，分子开关尚未完全明确

---

### 来源 5：Malenka & Bear (2004) — *Neuron* — PMID:15450156（仅摘要）
**"LTP and LTD: an embarrassment of riches"**

**未读取全文**（paywalled）。基于摘要的信息：
- 经典综述，建立了"突触可塑性多样性"框架
- 明确提出低频刺激（1 Hz, 900 次）诱发海马 NMDA-LTD 的标准协议
- Ca²⁺ 量决定可塑性方向的核心框架在此文中得到系统阐述

---

### 来源 6：Bear, Huber & Warren (2004) — *Trends Neurosci* — PMID:15219735（仅摘要）
**"The mGluR theory of fragile X mental retardation"**

**未读取全文**（paywalled）。基于摘要的信息：
- 提出 FXS 的 mGluR 理论：FMRP 缺失 → mGluR-LTD 过度激活 → 认知障碍
- 预测 mGluR5 拮抗剂可改善 FXS 症状（在 Fmr1 KO 小鼠中得到验证）
- 理论框架为 FXS 的临床试验设计提供了科学基础

---

### 今日研究总结

**已解决的问题**：
- NMDA-LTD 的完整磷酸酶级联（PP2B → PP1 → GluA1 去磷酸化）已清楚
- AKAP150-PSD-95-PP2B 空间定位机制已明确（Bhattacharyya 2009）
- mGluR-LTD 的 Arc/dynamin 内吞机制已建立

**仍不清楚的问题**：
- NMDA 受体是否可通过构象信号（非离子流）触发 LTD（争议！）
- GluA2 敲除后 LTD 仍存在，说明备用内吞路径的分子身份未知
- LTD 的长期维持机制（受体降解 vs. 持续内化 vs. 磷酸酶自持）
- 恐惧消退中 LTD 与原有 LTP 的精确对应关系

**开放全文检索效率**：6 篇中 4 篇读取全文（67%），高于最低要求（≥2 篇）。

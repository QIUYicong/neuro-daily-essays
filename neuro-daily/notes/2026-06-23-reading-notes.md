# 阅读笔记 2026-06-23：小脑与运动学习

**文章**：#59 小脑与运动学习——静默的预测机器  
**日期**：2026-06-23

---

## 来源 1：Hull & Regehr (2022)
**引用**：Hull C, Regehr WG. "The Cerebellar Cortex." *Annu Rev Neurosci.* 2022;45:151-175. PMID:35803588, PMCID:PMC10268027（开放全文）

**核心问题**：小脑皮层如何超越了经典 Marr-Albus 模型？

**方法**：综述；综合最新离体电生理、在体钙成像、遗传工具

**关键发现**：
1. 颗粒细胞（GrC）层并非均一——至少 3 种分子亚型，功能可能有区分
2. 苔藓纤维来源多样（脑干、前庭、脊髓等），短时程突触动态各异，使同一 GrC 能对不同来源 MF 产生不同时序响应
3. Golgi 细胞（GoC）通过 α1-GABA_A（快速）和 α6δ-GABA_A（慢速 tonic）双机制抑制 GrC——可灵活调节 GrC 激活阈值
4. PF-PC LTD 分子机制：mGluR1 + ΔCa²⁺ → IP₃/PKC → AMPA-GluA2 磷酸化与内吞
5. 单独 PF 刺激（无 CF 同步）可触发 PF-PC LTP（与 LTD 方向相反）——暗示双向学习
6. 小脑不只有 LTD：DCN（深部核团）内也有突触可塑性（mossy fiber-DCN LTP）

**改变理解**：经典 Marr-Albus 的"只有 LTD"图景被丰富为多种可塑性协作的复杂系统

**证据强度**：高（多实验室、多方法，教科书级综述）

**局限**：大多数机制研究来自鼠类离体脑片，在体的 GrC 活动模式（稀疏 vs. 密集）仍有争议

**需解释的术语**：Golgi cell tonic inhibition（GoC 持续性 GABA 释放，维持 GrC 基线阈值）

---

## 来源 2：Lisberger (2020)
**引用**：Lisberger SG. "The Rules of Cerebellar Learning: Around the Ito Hypothesis." *Neuroscience.* 2021;462:175-190. PMID:32866603, PMCID:PMC7914257（开放全文）

**核心问题**：Ito 最初的 VOR 学习假说在 2020 年仍然成立吗？有哪些扩展？

**方法**：理论/综述（基于猴平滑追踪眼动 Lisberger 自己实验室数据）

**关键发现**：
1. 伊藤假说的骨架仍然成立：CF 驱动 PF-PC LTD，改变 Purkinje cell 输出，矫正运动
2. 4 条学习原则（见文章正文）
3. 皮层学习（快，不稳）→ 核学习（慢，稳定）：双阶段模型
4. IO-DCN 反馈限制学习幅度（防止过拟合）
5. "学习转移"：通过浦肯野细胞→DCN 的反复激活，记忆从皮层转移到核

**改变理解**：小脑学习不是一次性的 LTD，而是皮层快/核慢的两阶段动态过程

**证据强度**：高（30 年研究积累，第一手实验 + 模型）

**局限**：主要基于猴眼动，推广到其他小脑功能（如肢体运动、认知）仍需更多证据

---

## 来源 3：Bonnan et al. (2023)
**引用**：Bonnan A, Zhang K, Gaffield MA, Christie JM. "Expression of a Form of Cerebellar Motor Memory Requires Learned Alterations to the Activity of Inhibitory Molecular Layer Interneurons." *J Neurosci.* 2023;43(4):601-612. PMID:36639897, PMCID:PMC9888511（开放全文）

**核心问题**：分子层中间神经元（MLI）在 VOR 运动记忆表达中的角色是什么？

**方法**：小鼠 VOR 适应 + 光遗传学沉默 MLI + 多点位记录

**关键发现**：
1. VOR 增益增加的适应后，绒球 MLI 的相位响应发生系统性偏移（即 MLI 本身"学习"了）
2. 急性光遗传学沉默 MLI → 完全取消 VOR 增益增加的表达（不影响基线 VOR）
3. 多日巩固后，MLI 沉默不再影响学习表达（与早期不稳定记忆 vs. 晚期稳定记忆对应）

**改变理解**：MLI 不只是 Purkinje 细胞的被动抑制者，它本身也是运动记忆回路的可变组件

**证据强度**：高（预注册双盲，光遗传学直接因果干预）

**局限**：仅研究 VOR 增益增加，不清楚其他学习方向（增益减少？眼睑条件化？）是否相同

---

## 来源 4：Park et al. (2026)——摘要阅读
**引用**：Park C et al. "Synchronous climbing fiber activity enables instructive signaling for cerebellar learning through modulation of disinhibitory circuits." *Nat Neurosci.* 2026 May 14. PMID:42135511（**摘要只，未读全文**）

**核心发现**：
- CF 不只接触 PC，还接触一类特殊 MLI 亚型（该亚型抑制抑制 PC 的 MLI），构成"CF → 去抑制 MLI → MLI → PC" 去抑制回路
- 去抑制 MLI 整合多条 CF——CF **同步**放电时激活更强 → 更大的 PC Ca²⁺ → LTD 触发
- 阻断 MLI-to-MLI 抑制（破坏去抑制回路）→ CF 驱动的 VOR 学习被完全阻断
- 结论：CF 同步性是触发学习的计算条件，而非单条 CF 的绝对幅度

**不确定性**：新发表（2026.05），尚无独立重复；该去抑制回路的普遍性（跨小脑分区/行为范式）待确认

---

## 来源 5：Habas (2021)
**引用**：Habas C. "Functional Connectivity of the Cognitive Cerebellum." *Front Syst Neurosci.* 2021;15:642225. PMID:33897382, PMCID:PMC8060696（开放全文）

**核心发现**：
- 外侧小脑（新皮质小脑，lobule VII，尤其 Crus I/II）在灵长类演化中与 PFC 平行扩张
- 静息态 fMRI：外侧小脑参与所有主要内在连接网络（中央执行、DMN、显著性、注意、语言）
- 外侧小脑区域以三种梯度（前后、内外、背腹）组织，反映不同认知功能的拓扑
- 认知小脑可能通过"计算内部模型"参与认知网络的同步和时序控制

**改变理解**：小脑不是运动附件，是脑网络架构的核心节点之一

**局限**：功能连接（fMRI）不等于因果连接；认知小脑的精确计算机制仍不清楚

---

## 来源 6：Gill & Sillitoe (2019)
**引用**：Gill JS, Sillitoe RV. *Front Cell Neurosci.* 2019;13:441. PMID:31636540, PMCID:PMC6787289（开放全文）

**核心发现**：
- 小脑发育畸形（如小脑皮质发育不全、Dandy-Walker 综合征）不仅引起运动共济失调，也引起认知障碍
- ASD（自闭症谱系障碍）中 Purkinje 细胞减少和 LTD 异常是最一致的神经病理发现之一
- 精神分裂、抑郁、焦虑均与小脑功能连接改变相关
- 小脑内部电路连接（zebrin 纵条纹组织）与行为结果直接对应

---

## 文章触及的概念清单

| Slug | 是否已有 wiki | 行动 |
|------|-------------|------|
| cerebellum | 无 | 创建新页 |
| purkinje-cell | 无 | 创建新页 |
| climbing-fiber | 无 | 创建新页 |
| parallel-fiber | 无 | 创建新页（或并入 cerebellar-motor-learning） |
| cerebellar-ltd | 无 | 创建新页 |
| granule-cell | 无 | 创建新页 |
| cerebellar-motor-learning | 无 | 创建新页（回路页） |
| inferior-olive | 无 | 创建为小节，并入 cerebellum |
| mli-disinhibition | 无 | 记录在 cerebellar-motor-learning |
| cognitive-cerebellum | 无 | 创建新页（或并入 cerebellum） |

# 阅读笔记：皮质纹状体突触可塑性（D1/D2 二分机制）

**日期**：2026-06-13
**文章编号**：#185
**主题**：Corticostriatal LTP/LTD——皮质纹状体可塑性的 D1/D2 二分机制

---

## 来源 1：Gerdeman, Ronesi & Lovinger 2002

**PMID**：11976704  
**期刊**：Nature Neuroscience  
**全文可用性**：否（订阅墙），仅摘要  

**要解决的问题**：纹状体 LTD 的逆向信号是什么？突触前还是突触后机制？

**方法**：大鼠背侧纹状体脑片；高频皮质刺激（HFS）；CB1 受体拮抗剂 SR141716A；CNQX/AP5 阻断实验

**发现**：
- CB1 受体拮抗剂完全阻断 HFS 诱导的 LTD
- CB1 激动剂（WIN 55212-2）模拟 LTD 效应
- 结论：内源大麻素（eCB）是逆行信号，突触后产生，突触前 CB1R 表达——这是**逆行大麻素信号**的经典发现

**改变了什么理解**：突破了"突触后表达 LTD"的经典模型，建立了纹状体 eCB-LTD 的范式

**证据强度**：高（Nature Neuroscience，多次独立重复）

**局限**：全是体外脑片实验；体内行为学习中的 eCB-LTD 尚需验证

**与认知的关系**：习惯形成的候选分子机制，特别是间接通路的突触压制

---

## 来源 2：Shen, Flajolet, Greengard & Surmeier 2008

**PMID**：18687967  
**期刊**：Science  
**全文可用性**：否（订阅墙），仅摘要 + 引用综述中的描述  

**要解决的问题**：D1-MSN 和 D2-MSN 的可塑性方向是否真的不同？

**方法**：D1-eGFP 和 D2-eGFP 转基因小鼠；在精确识别神经元类型后记录 LTP/LTD；多巴胺受体激动剂/拮抗剂药理学

**发现（二分法核心）**：
- D1-MSN：D1R 激活 → LTP；D1R 阻断 → LTD
- D2-MSN：D2R 激活 → eCB-LTD；D2R 阻断 → LTP
- 多巴胺通过 D1 和 D2 受体在两类 MSN 上施加**互补的双向控制**
- PD 模型（DA 剥夺）：双向可塑性崩塌为单向，解释 PD 运动学习困难

**改变了什么理解**：以前认为多巴胺只是强化剂；现在看到 DA 同时调控两条通路，实现互补的遴选机制

**证据强度**：高（Science，使用特异转基因工具确认细胞类型）

**局限**：脑片实验；是否在体内自然奖励学习中发生仍需验证

---

## 来源 3：Pawlak & Kerr 2008

**PMID**：18322089  
**期刊**：Journal of Neuroscience  
**全文可用性**：否（订阅墙），仅摘要  

**要解决的问题**：STDP 在纹状体的方向由什么决定？多巴胺是否必须？

**方法**：大鼠纹状体脑片；精确脉冲配对（pre-before-post vs post-before-pre）；D1/D5 拮抗剂 SCH 23390；D2 拮抗剂

**发现**：
- 前-后 STDP → LTP，需要 D1/D5R 激活（缺少则无 LTP）
- 后-前 STDP → LTD（内源大麻素依赖）
- D2 受体调制早期时相，但 D1/D5 是 LTP 的必要条件

**证据强度**：高（J Neuroscience，精确的配对刺激实验）

---

## 来源 4：Lovinger 2010

**PMID**：20096294  
**期刊**：Neuropharmacology  
**全文可用性**：否（订阅墙），仅摘要  

**综述要点**：
- LTP：需要 NMDA + D1R 或 A2A（腺苷受体，主要在 D2-MSN）
- LTD：需要 eCB + mGluR + D2（或 mGluR5 单独）
- 结论：DA 多巴胺是 LTP/LTD 方向决定的关键

---

## 来源 5：Vignoud, Venance & Touboul 2024

**PMID**：38724614  
**期刊**：Communications Biology（Nature 旗下开放期刊）  
**DOI**：10.1038/s42003-024-06203-8  
**全文可用性**：是（开放获取），已读摘要  

**要解决的问题**：anti-Hebbian STDP（后-前=LTP，前-后=LTD，D2-MSN观察到的）能否在计算上解释纹状体序列学习？

**方法**：计算建模；皮质输入→纹状体输出神经元的 STDP 模型；序列辨识任务

**发现**：
- 反 Hebbian STDP + 非联结性增强 → 有效学习序列性皮质输入
- Spiking 延迟 + 侧向抑制（类 FSI）提高序列辨识准确性
- 结论：D2-MSN 上的反 Hebbian STDP 是序列习惯化学习的候选生物机制

**与 #185 的关联**：补充了为何 D2-MSN 的反 Hebbian 规则在序列学习中有利

---

## 来源 6：González-Redondo et al. 2025

**PMID**：41057437  
**期刊**：Scientific Reports（开放期刊）  
**全文可用性**：是（Scientific Reports OA），已读摘要  

**发现**：三因子学习规则（突触前 × 突触后 × 多巴胺）在计算模型中可以成功实现行动选择；乙酰胆碱（CIN 暂停）在功能上限制可塑性时间窗，防止无关突触被意外修饰

---

## 关键技术术语

| 术语 | 英文 | 简要含义 |
|------|------|---------|
| MSN | Medium Spiny Neuron | 中型多棘神经元，纹状体主要细胞类型 |
| D1-MSN / dSPN | Direct-pathway Spiny Projection Neuron | 直接通路投射神经元，表达 D1/D5 受体 |
| D2-MSN / iSPN | Indirect-pathway Spiny Projection Neuron | 间接通路投射神经元，表达 D2 受体 |
| eCB | Endocannabinoid | 内源大麻素（如 2-AG），作为逆行信使 |
| 2-AG | 2-arachidonoylglycerol | 主要纹状体内源大麻素，逆行 CB1R 激动剂 |
| DAGLα/β | Diacylglycerol lipase α/β | 合成 2-AG 的关键酶 |
| DARPP-32 | Dopamine and cAMP-regulated phosphoprotein, 32 kDa | PKA 底物，D1 信号的关键整合子 |
| STDP | Spike-Timing-Dependent Plasticity | 脉冲时序依赖可塑性 |
| Three-factor rule | 三因子学习规则 | 突触前 × 突触后 × 调制因子（多巴胺）联合决定可塑性方向 |
| CIN/TAN | Cholinergic Interneuron / Tonically Active Neuron | 胆碱能中间神经元，产生乙酰胆碱暂停信号 |

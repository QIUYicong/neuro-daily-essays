# 阅读笔记 2026-06-10：短时程突触可塑性（STP）

## 选题背景

本篇填补突触层最后一个关键缺口：短时程突触可塑性（STP）。此主题被连续5篇文章（06-03 至 06-07）列为下一优先主题，与工作记忆（Q-wm-active-vs-silent）、Syt7（synaptotagmin.md 悬空引用）、活动静默 WM 均有直接关联。

---

## 来源 1：Regehr 2012（PMC3385958）

**题目**：Short-term presynaptic plasticity  
**来源**：Cold Spring Harb Perspect Biol, 2012  
**状态**：全文（PMC）

**要解决的问题**：STP 有哪些形式？每种的时间尺度和分子机制是什么？

**主要机制**：
- STD：囊泡池耗竭（RRP），模型：A_2/A_1 = (1 - F)，F = 单次释放概率
- STF：残余钙假说；buffer saturation 模型；Ca²⁺ 依赖性囊泡补充
- 增效（augmentation）和PTP：依赖线粒体缓冲和 Na/Ca 交换体，时间常数数十秒

**核心发现**：释放概率（P_r）决定 STP 方向——高 P_r → 抑制型；低 P_r → 易化型。同一突触改变胞外 Ca²⁺ 即可切换方向。

**改变了什么理解**：明确 STD 有两个机制（囊泡耗竭 + AMPA 去敏化），但突触前耗竭是主导；STF 的残余钙积累通过高亲和力传感器而非直接叠加 Syt1 激活。

**证据强度**：高（多个模式系统，定量建模验证）  
**局限**：主要来自体外切片或离体标本，体内情况有差异

---

## 来源 2：Jackman et al. 2016（PMC4729191）

**题目**：The calcium sensor synaptotagmin 7 is required for synaptic facilitation  
**来源**：Nature, 2016  
**状态**：全文（开放获取）

**要解决的问题**：易化的分子传感器是什么？残余钙如何被放大到产生 100-200% 的增强？

**方法**：Syt7 KO 小鼠；4 种突触（Schaffer、苔藓纤维、穿孔通路、丘脑皮层）；全细胞膜片钳；钙成像；病毒载体重表达 + C2A*突变体

**主要发现**：Syt7 KO → 所有 4 种突触 PPF 完全消失；P_r 不变；野生型 Syt7 救援；Ca²⁺ 不敏感突变体不能救援。

**机制结论**：Syt7（高亲和力，K_D ~μM）感知 AP 后残余低水平 Ca²⁺（0.5–2 μM），而 Syt1（低亲和力，K_D ~100 μM）只响应高浓度峰值。这解释了"残余钙叠加效应"。

**证据强度**：高（4种突触类型独立验证，基因敲除+救援+点突变三角验证）  
**与已知知识的关系**：直接回答 Q-syt7-facilitation-mechanism；补全 synaptotagmin.md

---

## 来源 3：Turecek, Jackman & Regehr 2017（PMC5892411）

**题目**：Synaptotagmin 7 confers frequency invariance onto specialized depressing synapses  
**来源**：Nature, 2017  
**状态**：全文（开放获取）

**要解决的问题**：Syt7 只在易化型突触中有用吗？高 P_r 突触中 Syt7 做什么？

**发现**：浦肯野细胞→DCN 突触（高 P_r，通常抑制型）野生型在 5–150 Hz 响应稳定（频率不变性）；Syt7 KO → 高频时严重衰减。结论：Syt7 提供"隐性易化"，恰好补偿了高频时的囊泡耗竭。

**计算意义**：小脑输出的线性频率编码依赖 Syt7 驱动的补偿机制。

**证据强度**：高（浦肯野+前庭两种突触；生理（1.5 mM）和低钙（0.3–1.0 mM）条件均验证）

---

## 来源 4：Shin et al. 2026（PMC12890252）

**题目**：Progressive overfilling of readily releasable pool underlies short-term facilitation at recurrent excitatory synapses in layer 2/3 of the rat prefrontal cortex  
**来源**：eLife, 2026  
**状态**：全文（开放获取）

**要解决的问题**：当 P_v ≈ 1 时，STF 还能如何发生？PFC L2/3 的特殊机制？

**核心发现**：STF 通过"进行性过载"实现——发射点位占有率从基础 30% 升至易化时 60%。Syt7 KD 使囊泡补充速率从 ~100 ms 延缓至 ~5 s。Syt7 特异性 KD → 追踪恐惧记忆受损。

**局限**：单一实验室，PFC 区域特异性，Syt7 KD 效率的可变性，行为数据需要独立重复

**证据强度**：中（新发现，需要复制）

---

## 来源 5：Mongillo, Barak & Tsodyks 2008（PMID:18339943）

**题目**：Synaptic theory of working memory  
**来源**：Science, 2008  
**状态**：仅摘要（无开放全文）

**要解决的问题**：工作记忆是否必须依赖持续放电？STP 能否在无活动时维持记忆？

**核心主张**：WM 由 STF 状态（残余钙升高）而非持续神经元活动维持；低频偶发"刷新"足以维持；比持续放电节能。

**证据状态**：理论建模 + 间接行为支持；体内直接验证困难。连接 Q-wm-active-vs-silent。

---

## 来源 6：Grover et al. 2026（PMC12908934）

**题目**：Synaptic footprints of time in working memory  
**来源**：eLife, 2026  
**状态**：全文（开放获取）

**核心扩展**：将 Mongillo 框架延伸：augmentation（更慢的 STP）可编码 WM 的时序信息，不只是身份。这解释了为何人类可以在无排练情况下记住序列的顺序。

---

## 来源 7：Motanis et al. 2018（PMC6171349）

**题目**：Short-Term Synaptic Plasticity as a Mechanism for Sensory Timing  
**来源**：Trends Neurosci, 2018  
**状态**：全文（PMC）

**核心内容**：抑制型突触=低通滤波器；易化型突触=高通滤波器；组合可形成带通。听觉和视觉时间感知的 STP 基础。

---

## 来源 8：[2026 MNTB 研究]（PMC13197447）

**题目**：Non-calyceal inputs gate the timing of calyx of Held evoked MNTB output  
**来源**：Commun Biol, 2026  
**状态**：全文（开放获取）

**关键内容**：易化型小突触补偿抑制型大突触（Calyx of Held）在高频时的衰减，使 MNTB 在持续声音刺激下保持精确时序编码（±5–250 μs），服务于双耳时间差编码（声音定位）。

---

## 术语需要解释

- **RRP（readily releasable pool）**：已停泊在活动区、处于就绪发射状态的突触囊泡，数量约 5–30 个/突触
- **P_r（release probability）**：单次 AP 使 RRP 中一个囊泡发射的概率
- **PPF（paired-pulse facilitation）**：两个间隔 50–200 ms 的 AP，第二个比第一个产生更大的 EPSC，是 STF 的标准测量指标
- **频率不变性（frequency invariance）**：突触传递强度在不同输入频率下保持相对稳定

---

## 需要解释的术语（供 wiki 添加）

- short-term-synaptic-plasticity（新建页）
- 需更新：synaptotagmin（补充 Syt7 机制；Q-syt7-facilitation-mechanism 可部分关闭）
- 需更新：synaptic-transmission（添加 STP 小节）
- 需更新：working-memory（添加活动静默 WM → STP 机制链接）
- 需更新：active-zone（添加 RRP 耗竭与补充动力学）

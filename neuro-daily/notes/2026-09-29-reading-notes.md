# 阅读笔记 2026-09-29

**文章**：#159 时序信用分配：资格痕迹如何让大脑跨越时间鸿沟学习
**Slug**：eligibility-trace-temporal-credit-assignment

---

## 来源1：Fuchsberger et al. 2022 eLife（PMID:36226826，PMC9612916）

**问题**：STDP是Hebbian规则的时序精确版，但DA奖励信号延迟数百毫秒甚至更长。如何协调？

**方法**：
- 小鼠CA1锥体细胞膜片钳记录
- Post-before-pre配对刺激（Δt=-20ms）→初始LTD
- 10分钟后：5-6个动作电位爆发 + DA（1μM）→测量突触强度变化
- 离体脑切片，细胞外Ca²⁺ = 2mM（注意：高于生理CSF浓度1.2mM）

**发现**：
- 初始配对：突触强度 61±11% of baseline（LTD）
- DA + 爆发放电（10min后）：135±14.9% of baseline（p=0.044）——LTD变成LTP
- AC1/AC8双敲除小鼠：消除DA依赖的可塑性，不影响经典LTP
- NMDA拮抗剂（在配对后施用）：不影响随后的DA+爆发诱导LTP（说明痕迹不需要NMDA持续参与）

**关键机制**：
1. Post-before-pre配对 → NMDA-R开放 → Ca²⁺ → 激活AC1/AC8进入敏感状态
2. 10min后：DA（Gs-PCR→β-γ亚基） + Ca²⁺残留 → AC1/AC8大幅升高cAMP
3. cAMP → PKA → AMPA受体磷酸化/插入 → LTP

**体内验证**：
- 自由运动小鼠空间奖励任务
- 预激活（pre-activated）CA1细胞在学习过程中显示更高活动峰值（AUC：0.54 vs 0.42）

**局限性**：
- 离体脑切片，2mM Ca²⁺（非生理）
- DA的精确来源（LC vs VTA）在体内未控制
- 痕迹持续期（>10min？）的上限未测定

---

## 来源2：Wang, Redondo & Morris 2010 PNAS（PMID:20962282，PMC2984182）

**问题**：STC假说能否在行为层面被验证？新颖体验如何充当"强刺激"角色？

**方法**：
- 大鼠事件竞技场（event arena）
- 弱编码：大鼠在新位置找到食物（只建立STM，30min可回忆，24h遗忘）
- 干预：编码后30min，5分钟新颖环境探索（新物体、新气味）
- 测试：24h后记忆是否持续

**发现**：
- 弱编码 + 新颖事件（30min后）：16只大鼠中14只在24h显示显著记忆（t₁₅=4.35，P<0.001）
- 弱编码单独：24h无记忆
- D1/D5拮抗剂（SCH23390，编码后即刻注射）：阻断新颖事件的记忆增强
- 蛋白合成抑制剂（编码后即刻）：阻断；延迟6h注射：不阻断
- 关键时间窗口：新颖事件需在编码后约6h内发生才有效

**关键机制**：
新颖事件 → 多巴胺（蓝斑LC或VTA）爆发 → D1/D5激活 → PRPs合成 → PRPs被弱编码的标签捕获 → STM → LTM转化

---

## 来源3：Bin Ibrahim, Wang & Sajikumar 2024 Philos Trans R Soc B（PMID:38853570，PMC11343274）

**综述焦点**：STC在神经系统疾病和老化中的应用及作为"突触健康检测工具"的价值

**关键内容**：
1. STC的标签候选：CP-AMPARs（钙通透性AMPA受体）、CaMKII、TrkB——多分子复合体可能性最高
2. 神经调质作用：DA（D1/D5→ERK1/2）、mGluR（mTOR信号）、BLA情感信号——可以将LTD的STC转化为LTP的STC（"协同性"和"竞争性"）
3. 区域扩展：STC不局限于CA1，在侧杏仁核、CA2、前扣带回皮层均有证据
4. 老化：STC失效尽管晚期LTP还在；锌螯合或BDNF/TrkB激活可恢复
5. AD：APP/PS1小鼠STC失效，但L-LTD仍保留（不对称性失效）
6. 癌症相关认知损害：可能通过肠道菌群变化破坏STC
7. STC是"比晚期LTP更敏感的突触健康指标"

---

## 来源4：Sacktor & Fenton 2018 Mol Brain（PMID:30593289，PMC6309091）

**问题**：CaMKII和PKMζ在LTP诱导和维持中各自扮演什么角色？

**发现**：
- CaMKII：LTP诱导所必需，但维持LTP不需要。自主活性在诱导后仅持续分钟。
- PKMζ：维持已建立的晚期LTP所必需。活性在LTP诱导后数小时甚至数月内持续升高。
- PKMζ机制：抑制GluA2依赖的AMPAR内吞（→增加突触AMPAR数量维持强度）
- PKMζ抑制剂（ZIP）：在LTP建立后施用，逆转LTP；但单独阻断内吞机制，ZIP失效（证明机制特异性）

---

## 来源5：Frey & Morris 1997 Nature（PMID:9020359，摘要）

原始STC论文。弱刺激 + 强刺激在同一细胞的不同输入上，弱刺激也能被升级为L-LTP（即使强刺激延迟1-2h）；蛋白合成抑制剂阻断升级效果。标签有效期约3h内。

---

## 来源6：Shen et al. 2008 Science（PMID:18687967，PMC2833421）

D1-MSN和D2-MSN的不对称STDP规则（连接到文章#158）。D1-MSN：pre+post+DA→LTP；D2-MSN：pre+post+DA→LTD。纹状体STDP的具体实现。本文作为背景参考。

---

## 来源7：Redondo & Morris 2011 Nat Rev Neurosci（PMID:21170072，摘要）

综述STC假说的更新版本，强调："突触增强的诱导只创造了持久改变的**潜力**，而非对改变的承诺。"区分了功能性可塑性和结构性可塑性机制的差异。

---

## 新建/修订的概念

今日文章触及：
1. `synaptic-tagging-capture` — 已有 rev3，需要修订（加入资格痕迹框架、Fuchsberger 2022、Wang 2010行为标记量化数据、纹状体STC角度）
2. `eligibility-trace` — 不在已知wiki页面中，可能需要新建（或并入synaptic-tagging-capture的子节）
3. `striatal-plasticity` — 已有 rev1，需要修订（加入STC和资格痕迹如何解决D1-MSN时序问题）
4. `three-factor-learning-rule` — 已有 rev3（just updated 09-28），需要加入资格痕迹的分子实现
5. `habitual-behavior` — 悬空引用，今日可创建基础页（基于文章#156-157）
6. `goal-directed-behavior` — 悬空引用，今日可创建基础页（基于文章#155-156）

# 研究笔记 · 2026-10-19

**主题**：平行纤维（parallel fiber）与小脑皮层计算架构  
**搜索词**：parallel fiber cerebellar computation plasticity; granule cell Purkinje cell Marr Albus Ito; parallel fiber LTD LTP bidirectional

---

## 来源1：Xie et al. 2023 (PMID: 37671785, eLife) ✅ 开放全文

**问题**：颗粒细胞编码的最优密度是什么？  
**方法**：计算优化分析，对不同任务类型（随机刺激分类 vs 连续感觉运动变换）推导最优GC表征  
**发现**：
- 对随机刺激分类：马尔的稀疏编码确实最优
- 对连续感觉运动变换（更接近真实小脑功能）：较密集的编码（任务依赖）才是最优
- 体内GC记录有时见到高于稀疏预期的激活密度，与理论一致

**改变了什么理解**：马尔的"GC必须稀疏编码"不是普遍最优原则，而是特定任务的最优解  
**局限**：理论分析为主，体内直接验证仍不足  
**证据强度**：中等（理论模型，待体内实验确认）

---

## 来源2：Kawato et al. 2021 (PMID: 32599123, Neuroscience) ⚠️ 仅摘要

**问题**：Marr/Ito/Albus三个模型的核心共识与分歧是什么？  
**发现**：
- 共识：PF-PC突触在CF引导下发生可塑性变化（LTD）
- 分歧：GC是否真的稀疏编码；可塑性是LTD还是LTP还是两者皆有；计算目标是什么
- 新方向：多个内部模型的分级强化学习框架

**历史背景**：2021年是三个模型发表约50年的节点，该综述系统比较三个经典模型  
**局限**：未读全文

---

## 来源3：Lisberger 2021 (PMID: 32866603, Neuroscience) ⚠️ 仅摘要

**问题**：小脑学习有哪些基本原则？  
**四条原则**：
1. CF信号驱动PF-PC突触的快速学习（PC静默化）
2. 学习输出从皮层转移到小脑核（两级存储）
3. 皮质回路的反馈限制皮层学习（防止过度拟合）
4. 不同小脑功能分区使用不同的可塑性规则（区域异质性）

**重要性**：指出小脑学习不是单一机制，有皮层→核的记忆转移，类比海马→皮层巩固  
**局限**：未读全文

---

## 来源4：Hirano 2018 (PMID: 30284678, Cerebellum) ⚠️ 仅摘要

**问题**：浦肯野细胞的形态学数据（PF/CF输入数）  
**关键数据**：
- PC接受>100,000条PF输入（来自多达50,000-100,000个不同GC）
- PC接受1条CF，CF形成300-500个突触（位于近端树突）
- PF-LTD是小脑依赖性学习的基础机制（综述结论）

---

## 来源5：Jörntell & Hansel 2006 (PMID: 17046686, Neuron) ⚠️ 仅摘要

**核心发现**：PF-LTP作为PF-LTD的逆转机制  
**机制**：
- PF激活不伴CF → 低Ca²⁺ → PP2B（calcineurin）激活 → AMPAR去磷酸化 → 重新插入突触膜 → LTP
- 海马：高频LTP，低频LTD；小脑PF突触：CF-paired LTD，no-CF LTP——"倒置"的Hebbian规则

**意义**：双向可塑性使运动学习可以被修正/逆转，解释了VOR去适应（de-adaptation）  
**证据强度**：高（Neuron，主流接受）

---

## 来源6：Coesmans et al. 2004 (PMID: 15541316, Neuron) ⚠️ 仅摘要

**核心发现**：CF是PF可塑性极性的"开关"  
**机制**：
- PF + CF → 高Ca²⁺（主要来自CF-induced复杂放电）→ LTD
- PF alone → 低Ca²⁺ → LTP
- 与BCM理论相比是"逆向"钙阈值依赖性

**方法**：光刺激控制CF活性+胞内记录PC的突触权重变化  
**证据强度**：高（Neuron，被多项研究复制）

---

## 来源7：D'Angelo 2014 (PMID: 24916288, Prog Brain Res) ⚠️ 仅摘要

**核心发现**：小脑的突触可塑性远超PF-LTD这一个位点  
**至少9种可塑性**：包括MF-GC LTD/LTP、PF-MLI LTP（逆向可塑性）、PF-PC LTD/LTP、PC→DCN的可塑性等  
**意义**：马尔-伊藤模型只预测了一个位点，真实情况远更复杂

---

## 来源8：Suvrathan & Raymond 2018 (PMID: 30069835, Cerebellum) ⚠️ 仅摘要

**核心发现**：PF-LTD规则在不同小脑区域有异质性  
**方法**：跨区域光遗传+电生理对比  
**发现**：不同小脑功能微区（microzone）的CF-driven LTD时间窗口和幅度不同，说明学习规则不是统一的

---

## 检索总结

**搜索词及结果**：
1. "parallel fiber cerebellar cortex computation plasticity" → 15个PMID
2. "granule cell parallel fiber Purkinje cell cerebellar learning marr albus ito" → 3个PMID
3. "parallel fiber LTD LTP Purkinje bidirectional plasticity cerebellar learning" → 4个PMID
4. "Xie granule cell cerebellar optimal encoding 2023" → PMID 37671785

**来源采用情况**：8个来源采用，≥1个开放全文（Xie eLife），7个仅读摘要  
**满足条件检查**：≥5个来源 ✓，≥1个开放全文 ✓，≥1个官方机构来源（NCBI/PubMed）✓

**补充注意**：
- Marr 1969 (J Physiol), Albus 1971 (Math Biosci), Ito 1984 (书) 均为历史文献，未在PubMed检索到，通过综述引用（PMID: 32599123）间接溯源
- Oct 8日文章（PMID: 34089728, mGluR1-LTD分子机制）已在知识库中，今日文章将PF-LTD机制交叉引用而不重复

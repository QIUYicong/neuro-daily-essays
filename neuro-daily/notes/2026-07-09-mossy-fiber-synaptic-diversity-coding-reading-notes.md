# 阅读笔记 2026-07-09

**文章**：#192《颗粒细胞的输入密码：苔藓纤维如何用突触多样性给感觉信号打上"身份标签"》

> **命名说明**：真实日期 2026-07-09 已被本知识库此前"日期漂移"事件中产生的虚拟时间线文章占用（`2026-07-09-glucocorticoids-stress-memory-amygdala.md`，第77篇，糖皮质激素与应激记忆），依据 2026-07-07 修复事件（见 `wiki/CHANGELOG.md`）确立的"日期+slug"消歧命名惯例，本篇 notes/sources/log 均采用带 slug 后缀的文件名，不覆盖、不修改任何已有文件。

---

## 开放全文阅读（精读）

### Chabrol et al. 2015, Nature Neuroscience（PMID:25821914 / PMCID:PMC4413433）
*Synaptic diversity enables temporal coding of coincident multisensory inputs in single neurons*
- **关键发现**：小鼠前庭小脑中，来自前庭初级传入、前庭次级传入、视觉相关通路的苔藓纤维终扣，在同一颗粒细胞上表现出可区分的突触强度与短时程动态；多模态共激活时颗粒细胞放电率提升、首个动作电位潜伏期改变，实现时间编码
- **方法**：脑片全细胞膜片钳记录 + 通路特异性光遗传/电刺激，区分不同苔藓纤维输入来源
- **结论的局限性**：局限于前庭小脑这一个功能高度专一的小脑分区，未验证其他小脑叶是否存在类似机制；决定"生物物理签名"的具体分子基础未阐明
- **对知识库的意义**：为"苔藓纤维不是被动传声筒"这一今日核心论点提供了最直接的电生理证据，填补了颗粒细胞输入层计算贡献的空白

### Oh et al. 2014, Nature（PMID:24695228 / PMCID:PMC5102064）
*A mesoscale connectome of the mouse brain*
- **阅读范围**：摘要 + 方法概述 + 脑区覆盖统计段落（确认脑桥21区、小脑21区被纳入295个标准化追踪结构）
- **关键内容**：Allen Mouse Brain Connectivity Atlas 用 EGFP 病毒示踪 + 序列双光子断层成像，建立了脑区间标准化连接矩阵，为苔藓纤维前体核团（脑桥核、前庭核等）到小脑的解剖学投射提供官方、可复现的底图
- **对知识库的意义**：作为官方机构来源，支撑"苔藓纤维来源极为多样"这一背景论点，不涉及苔藓纤维本身的突触生理机制

### Holla, Brown & Raman 2026, J Neurosci（PMID:41381355 / PMCID:PMC12828877）
*Effects of Short-Term Synaptic Plasticity in Feedforward Inhibitory Circuits on Cerebellar Responses to Repetitive Sensory Input*
- **关键发现**：清醒头固定小鼠中，重复胡须气流刺激下，苔藓纤维到小脑核的兴奋性传递本身发生短时程抑制；这与平行纤维易化（减弱浦肯野细胞净抑制）、分子层中间神经元募集减少共同驱动全链条对重复刺激的适应
- **方法**：在体多细胞类型（MLI/浦肯野细胞/小脑核/苔藓纤维终末）同步胞外记录，头固定清醒小鼠，重复气流刺激范式
- **结论的局限性**：未在体内直接区分苔藓纤维传递减弱的具体机制（受体脱敏 vs 囊泡耗竭 vs 突触前抑制性调制）
- **对知识库的意义**：首次提供在体证据，证明苔藓纤维本身参与重复刺激适应，而非只是下游浦肯野细胞/核团"过滤"的被动上游

---

## 摘要阅读（浏览）

### Xu-Friedman & Regehr 2003, J Neurosci（PMID:12657677 / PMCID:PMC6742013，正文XML受限）
- 连续电镜重建苔藓纤维小球超微结构：数百个释放位点，中心距~0.46微米，7.1个邻居/微米范围，无胶质完全隔离
- 双脉冲抑制~60%（10ms间隔），恢复时间常数~30ms；cyclothiazide（阻断AMPA脱敏）可减弱此抑制，提示机制为受体脱敏而非单纯囊泡耗竭
- 本文超微结构证据的核心来源，但正文完整图表未能通过API获取，只依据摘要与已知图表描述转述

### D'Angelo, Rossi, Armano, Taglietti 1999, J Neurophysiol（PMID:9914288）
- 首次证明苔藓纤维-颗粒细胞突触存在NMDA/mGluR依赖LTP，需Ca²⁺升高+PKC激活
- 提示该突触本身具有学习/记忆存储能力，而非固定传输线

### Andreescu et al. 2011, Neuroscience（PMID:21185357）
- NR2A敲除小鼠丧失苔藓纤维-颗粒细胞LTP，同时丧失VOR相位翻转适应能力，但基础运动表现不受影响
- 提供了该突触可塑性与具体行为学功能（前庭-眼动适应）之间的因果链接（基因操控+行为学）

### Nieus et al. 2006, J Neurophysiol（PMID:16207782）
- LTP会消除短时程易化、加速抑制、增强谷氨酸溢出电流成分——即LTP改写突触短时程动态本身，而不只是提高强度
- 计算建模部分预测：突触前释放概率增加主要影响首个尖峰潜伏期，突触后受体电导增加主要影响放电频率

### Ando, Ueda, Luo, Sugihara 2020, J Comp Neurol（PMID:31904871）
- 单轴突生物素葡聚糖胺重建显示内侧前庭核（MVN）苔藓纤维至少3种投射类型（Cbm/cVN-Cbm/iVN-Cbm型），终扣密度、分布位置各异
- 为"苔藓纤维生物物理签名多样性"提供了可能的解剖学/细胞起源根源，但该研究本身未测量突触生理特性

---

## 检索策略记录

- NCBI E-utilities esearch：`cerebellar mossy fiber glomerulus granule cell`（34条）、`mossy fiber cerebellum short term plasticity granule cell`（17条）、`cerebellar mossy fiber origin pontine nuclei spinal vestibular`（39条）、`D'Angelo mossy fiber granule cell synapse NMDA`（19条）
- 定向检索确认关键论文：Chabrol 2015（`Chabrol DiGregorio mossy fiber granule cell synaptic diversity`，1条精确命中）
- PMC全文获取：通过 NCBI BioC API（`pmcoa.cgi/BioC_json`）成功获取 Chabrol 2015、Oh 2014 全文；Holla 2026 与 Xu-Friedman 2003 通过 BioC 失败后改用 `efetch.fcgi?db=pmc&rettype=full&retmode=xml` 补充获取（Holla 2026 成功，Xu-Friedman 2003 因出版方限制仅获得元数据框架，正文引用改用摘要）
- 排除的候选：`granule cell layer adaptive filter Marr Albus Silver`（0命中，术语组合过于宽泛未匹配）、`Allen Institute cerebellum mossy fiber connectivity atlas`（0命中，改用更通用的Allen mesoscale connectome原始论文替代）

## 今日固结涉及的 wiki 页面

- 新建：`wiki/neurons/mossy-fiber.md`
- 修订：`wiki/neurons/granule-cell-cerebellar.md`（rev2→rev3）、`wiki/neurons/parallel-fiber.md`（rev2→rev3）

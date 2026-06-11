---
title: 突触剪枝
slug: synaptic-pruning
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-03
updated: 2026-08-07
revision_count: 2
dimensions: [synaptic, cellular, microcircuit, brain-region, cognition, disease]
related: [microglia, complement-cascade-cns, homeostatic-plasticity, synaptic-scaling, critical-period, ltp, ltd, autism-spectrum-disorder, synaptogenesis]
prerequisites: [synaptic-transmission, action-pointer, long-term-potentiation]
opens_questions: [Q-pruning-01, Q-pruning-02, Q-pruning-03, Q-pruning-04, Q-pruning-05]
source_articles: [2026-06-03-microglia-synaptic-pruning, 2026-08-07-synaptic-pruning-complement-autism-schizophrenia]
key_sources: ["PMID:18083105", "PMID:22632727", "PMID:26814963", "PMID:27033548", "PMID:32657463", "PMID:34738335", "PMID:32661396", "PMID:30308165", "PMCID:PMC11876149"]
---

# 突触剪枝 (Synaptic Pruning)

> **一句话定义**：突触剪枝是大脑在发育期（及某些病理情况下）主动消除冗余突触连接的过程，以活动依赖的方式保留有用连接、删除弱连接，通过补体蛋白标记和小胶质细胞吞噬实现，是神经回路从"粗糙"走向"精确"的核心机制。

## 当前理解

我们现在认为，大脑在建立精确回路时采用"先多建再精删"策略：神经元在发育早期铺设数倍于最终所需量的突触连接，随后通过活动依赖的竞争机制将不活跃的连接删除。这个过程由小胶质细胞和补体系统共同执行，是决定大脑回路最终精确度的关键机制之一。

突触剪枝的活动依赖性体现在：神经活动水平通过"吃我"信号（C3b、磷脂酰丝氨酸）和"别吃我"信号（CD47）的动态平衡，将突触的使用频率转化为保留/删除的分子决策。活跃突触积累更多的"别吃我"信号（CD47），而沉默突触则积累更多的"吃我"信号，最终被小胶质细胞识别并吞噬。

这套机制在不同脑区和时间点展现不同的分子特征：补体-CR3 通路在视网膜膝状核发育期最为突出；PS-TREM2 通路在海马早期发育中起重要作用；前额叶皮层的突触剪枝则在青春期最为活跃，且其失调与精神分裂症密切相关。

## 关键机制

### 触发信号：分子层面的"标记"

**"吃我"信号**：
- **C3b**（补体调理素）：C1q→C4→C3 级联产生，共价结合突触膜，被微胶质 CR3 识别
- **磷脂酰丝氨酸（PS）外翻**：弱/沉默突触前膜 scramblase 激活 → PS 翻至外层，被 TREM2 识别
- **C1q 本身**：C1q 也可能直接触发某些吞噬受体（间接机制）

**"别吃我"信号**：
- **CD47**：在活跃突触上表达更高，与小胶质细胞 SIRPα 结合产生抑制性信号
- **SRPX2**：神经元分泌的补体抑制因子，优先保护谷氨酸能突触（VGluT2）

### 执行：小胶质细胞的物理吞噬

1. 微胶质细胞伪足（filopodia）接触 C3b-标记或 PS-暴露的突触末梢
2. CR3/TREM2 激活下游 Rac1/RhoA 信号通路
3. 吞噬体形成 → 突触末梢被完整包裹
4. 吞噬体与溶酶体融合 → 突触物质被酶解降解
（直接形态学证据：电子显微镜在微胶质溶酶体内发现完整突触结构，Schafer et al. 2012）

### 活动依赖性的机制假说

**保护模型（活跃突触）**：高神经活动 → CD47 高表达 → SIRPα 信号 → 抑制吞噬
**惩罚模型（弱/沉默突触）**：低活动/LTD → caspase-3 局部激活（非凋亡性）→ PS scramblase 激活 → PS 外翻 → TREM2 吞噬
两种模型可能同时工作，共同实现弱者删除/强者保留的活动依赖选择性

### SRPX2：神经元自带的补体"刹车"（2020 新增）

2020 年发现，神经元自身分泌 SRPX2（sushi repeat containing protein X-linked 2），通过直接结合 C1q 阻止 C2 裂解，在补体级联的源头截断信号（PMID:32661396）。SRPX2 优先保护 VGluT2+ 谷氨酸能突触（兴奋性 > 抑制性），揭示 E/I 突触的修剪不对称性在分子层面早有编码。人类 SRPX2 基因突变与语言障碍和癫痫相关。

### 胶质-胶质信号：系统级时间门控（2025 新增）

突触修剪不只是"神经元→胶质"的单向信号，**胶质细胞间的对话同样必不可少**：
- 星形胶质细胞分泌 **IL-33** → 小胶质细胞 IL1RL1 受体 → 吞噬能力上调
- 果蝇研究（Miller & Broadie 2024）：胶质细胞内 **5-HT（血清素）** 信号时间限制关键期窗口；关键期结束后 5-HT 信号消失，可塑性关闭；成年期重新激活胶质 5-HT 可重启关键期样修剪
- 这为"关键期的开与关"提供了分子层面的解释（PMCID:PMC11876149）

### 执行时间窗口

| 脑区 | 主要剪枝期 | 主要信号 |
|------|---------|---------|
| 视网膜膝状核（dLGN） | P2–P10 | C1q/C3-CR3 + PS-TREM2；SRPX2 调节 |
| 海马（CA1） | P15 前后 | CX3CR1、TREM2 为主 |
| 前额叶皮层 | 儿童期–青春期 | C4A/补体-CR3 |
| 其他新皮层 | 关键期内 | 区域依赖性（SRPX2 等调节）；V1 眼势力优势不依赖 C1q/CX3CR1 |

**重要异质性**：V1 皮层眼势力优势（ODP）的突触可塑性**不需要** C1q 或 CX3CR1，说明新皮层的关键期修剪使用了不同于 dLGN 的分子通路，后者目前仍基本未知。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 突触剪枝需要 C1q 和 C3 | C1QA−/−、C3−/− 小鼠：dLGN 眼特异性分离失败，持续大量冗余突触 | PMID:18083105 | 高 |
| 微胶质细胞物理吞噬完整突触 | 电镜：溶酶体内整体突触前结构 | PMID:22632727 | 高 |
| 弱突触被优先删除（活动依赖） | TTX 封闭 → 该眼突触优先被吞噬；forskolin 保护活跃突触 | PMID:22632727 | 高 |
| PS 是独立的"吃我"信号 | Annexin V 屏蔽 PS → 剪枝减少约 50% | PMID:32657463 | 中高 |
| C4A 过度表达→过度剪枝→精神分裂症 | 遗传关联 N=64,000+；C4 敲入小鼠树突棘减少 | PMID:26814963 | 高 |
| AD 早期 C1q 重激活先于斑块 | AD 小鼠 1 月龄 C1q 突触↑；Aβ 低聚体触发；阻断 C1q 保护突触 | PMID:27033548 | 高 |
| SRPX2 是内源性神经元补体抑制因子 | SRPX2−/− 小鼠 C3 沉积↑，dLGN/S1 突触↓；需 C3 存在；优先保护 VGluT2+ | PMID:32661396 | 高 |
| CD47 介导活动依赖的突触保护选择性 | CD47−/− 鼠：过度修剪 + 活动依赖选择性消失；CD47 在活跃突触更高 | PMID:30308165 | 高 |
| 16p11.2 缺失（ASD）导致修剪不足 | CD47 感知障碍→小胶质吞噬减弱→突触密度↑→社交行为缺陷 | doi:10.1073/pnas.2411080122 | 中高 |
| 胶质内 5-HT 信号时间门控关键期 | 胶质 5-HT 与关键期高度吻合；成年期重激活→重启可塑性窗口 | PMCID:PMC11876149 | 中（果蝇，待哺乳类验证）|

## 连接

- [[microglia]] — 突触剪枝的主要执行细胞
- [[complement-cascade-cns]] — 提供分子标记（C3b）
- [[homeostatic-plasticity]] — 两者都维持 E/I 平衡，但时间尺度不同（发育期剪枝：周–月；稳态可塑性：小时–天）
- [[synaptic-scaling]] — 稳态可塑性的突触后机制；与剪枝共同维护回路动态平衡
- [[ltp]] — 突触强化（与剪枝相对）；活动依赖的两极：LTP 留，剪枝删
- [[critical-period]] — 关键期内剪枝最活跃（悬空引用，待补）
- [[alzheimers-disease]] — C1q 重激活 → 突触前丢失 → 早期认知下降
- [[pv-interneurons]] — 精神分裂症中 PV+ 细胞缺陷与补体过度剪枝相互关联
- [[autism-spectrum-disorder]] — 修剪不足（CD47 缺陷型）作为 ASD 病理机制之一
- [[synaptogenesis]] — 与突触生成互为镜像；两者共同决定回路最终突触密度

## 未解问题

- Q-pruning-01（高优先）：PS 外翻的精确上游触发器是什么？是 LTD 相关的 caspase-3 局部激活，还是其他机制？
- Q-pruning-02（中优先）：成年大脑是否仍有周期性突触剪枝？如果有，时间尺度和分子机制与发育期是否相同？
- Q-pruning-03（中优先）：不同脑区（dLGN vs 海马 vs 前额叶皮层）的剪枝机制差异来自何处？SRPX2 等局部调节因子的完整图谱是什么？
- Q-pruning-04（高优先）：SRPX2 保护谷氨酸能突触的机制是否与 CD47 通路存在串扰？NL-NRXN 接合强度是否同时上调 CD47/SRPX2 局部表达（连接 synaptogenesis-pruning 一体化）？
- Q-pruning-05（中优先）：精神分裂症患者成年后，C4A 介导的过度补体修剪是否仍在进行，还是只在青春期造成不可逆损伤后停止？这决定了补体抑制剂（ANX005 抗 C1q 抗体）是否适用于成年患者。

## 修订历史

- 2026-06-03 · 创建 · 基于《大脑的"质检员"》(#70) · 初始置信度：高（多个独立实验室的直接证据）
- 2026-08-07 · 修订 · 基于《大脑的删除艺术》(#106) · 新增：SRPX2 详细机制（binds C1q, 优先保护 VGluT2+）；胶质-胶质 5-HT 信号时间门控；CD47+16p11.2 ASD 2025 数据；V1 皮层 ODP 不依赖 C1q 的异质性注记；新增 3 条证据表；添加 Q-pruning-04/05

## 来源文章

- [[2026-06-03-microglia-synaptic-pruning]]
- [[2026-08-07-synaptic-pruning-complement-autism-schizophrenia]]

# 阅读笔记 2026-09-21

**文章**: #151 《记忆的分子守夜人：PKMζ的发现、颠覆与新生》
**主题**: PKMζ与晚期LTP持久性机制

## 核心文献笔记

### Ling et al. 2006 (PMID:16463388) — PKMζ过表达使突触AMPA受体翻倍
- 单独过表达PKMζ足以将突触AMPA受体数量增加~2倍
- 不需要突触刺激，是激酶活性的直接后果
- 这是LTP中PKMζ增强突触传递的功能证明

### Sajikumar et al. 2005 (PMID:15958741) — PKMζ是第一个L-LTP特异性PRP
- 在STC框架内，PKMζ是明确鉴定的晚期LTP可塑性相关蛋白
- E-LTP标签 + PKMζ合成信号 → 升级为L-LTP
- 这将PKMζ纳入三因素学习规则的分子实现

### Sacktor 2011综述 (PMID:21119699) — PKMζ无调节域，持续激活
- PKMζ从PKCζ基因的内部启动子转录
- 缺少调节结构域 → 不需要第二信使激活
- 树突mRNA → 局部合成 → 突触特异性积累（可能）

### Migues et al. 2010 (PMID:20383136) — GluR2机制
- PKMζ通过NSF-GluR2通路阻止含GluA2的AMPAR内吞
- 这是LTP"维持"的分子机制：不断阻止突触减弱

### Lee et al. 2013 (PMID:23283171) — Prkcz KO小鼠记忆正常
- 利用条件性KO，完全删除PKMζ
- LTP和空间记忆完全正常
- 发现原因：PKCι/λ代偿上调（后来被证实）

### Volk et al. 2013 (PMID:23283174) — 独立重复
- 独立实验室，独立KO策略，同样结论
- ZIP在KO小鼠中仍然有效 → ZIP非PKMζ特异性的第一个证据

### Frankland & Josselyn 2013 (PMID:23283170) — 评论
- 标题"Memory and the single molecule"点出核心问题
- 单一分子不可能支撑复杂记忆功能

### Tsokas et al. 2016 (PMID:27187150) — PKCι/λ代偿机制
- PKMζ缺失 → PKCι/λ从出生起代偿上调
- PKCι/λ与PKMζ有相似的催化结构域
- 解释了为何发育性KO小鼠表现正常

### Hsieh et al. 2021 (PMID:33540466) — 记忆神经元中PKMζ持续升高1个月
- 用c-Fos-DREADD标记记忆编码时的海马CA1细胞
- 1个月后，这些细胞中PKMζ水平仍显著高于非记忆神经元
- **最直接的体内证据**：PKMζ在自然记忆中长期持续

### Stokes et al. 2025 (PMID:39814881) — ZIP机制重写
- ZIP的记忆破坏作用来自阳离子电荷，不是PKMζ伪底物序列
- 机制：阳离子肽 → endophilin-A2 → 巨胞饮 → AMPAR非特异性大规模内吞
- 重大发现：20年的ZIP实验需要重新解读

### Hsieh et al. 2026 (PMID:41814337) — KIBRA-PKMζ寡聚体
- AlphaFold3预测 + 体外验证：KIBRA与PKMζ形成稳定多聚体
- "感染性磷酸化"：新合成的PKMζ加入复合物后被已磷酸化的PKMζ激活
- 这是分子更新悖论的解答：激活状态代代传递
- 工具：K-ZAP（KIBRA拮抗肽）、ζ-stat（新型PKMζ状态探针）

### Tsokas et al. 2026 (PMID:41889799) — 双敲除验证
- 同时删除PKMζ和PKCι/λ → L-LTP完全消失
- 单独删除任一个：L-LTP正常
- E-LTP可以诱导，但3小时后衰退至基线
- 这是aPKC功能层对L-LTP必要性的最终证明

## 关键概念整理

**克里克问题**（Crick 1984）：蛋白质寿命24h-数周，记忆持续数十年——如何解决？
**PKMζ解答**：功能状态的感染性传播（非分子永生）
**功能冗余层**：PKMζ + PKCι/λ双保险（非单一分子）
**GluA2机制**：通过阻止AMPAR内吞来维持突触强度
**KIBRA scaffold**：寡聚体结构使磷酸化状态可以传递

## wiki更新计划

1. 创建 pkm-zeta.md（新页面，rev1）
2. 更新 ltp.md（rev12→rev13）：新增PKMζ持久性机制节，标记Q-ltp-lifetime-mechanism为部分解答
3. 更新 synaptic-tagging-capture.md（rev2→rev3）：PKMζ作为STC的PRP分子细节
4. 更新 arc-arg31.md（rev1→rev2）：完善寡聚体/capsid结构（与PKMζ寡聚体机制类比）

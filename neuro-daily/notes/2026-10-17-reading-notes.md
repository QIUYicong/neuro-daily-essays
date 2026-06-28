# 阅读笔记 · 2026-10-17 · PSD-95 支架蛋白与突触槽位

## 来源概览

本次文献研究使用 PubMed E-utilities 和 PMC 开放全文检索，核心搜索词：
- "PSD-95 scaffold LTP AMPA receptor"
- "PSD-95 palmitoylation DHHC synaptic targeting"
- "PSD-95 nanodomains PALM super-resolution"
- "DLG4 neurodevelopmental disorder synaptic"

---

## S1 · MacGillavry et al. 2013 · PMID:23719161 · PMC3668352 · OPEN

**标题**：Nanoscale scaffolding domains within the postsynaptic density concentrate synaptic AMPA receptors

**核心问题**：PSD 内部是否有纳米尺度的微组织？

**方法**：PALM（光激活定位显微镜，分辨率 ~25 nm），双色成像，蒙特卡罗模拟

**关键发现**：
- PSD-95 形成 ~80 nm 纳米簇（4580 ± 402 nm²）
- 每个 PSD 约 300 个 PSD-95 分子，15-20% 集中于纳米簇
- AMPA 受体（GluA2）在纳米簇内密度约 1.9× PSD 平均值
- NMDA 受体（GluN1）几乎不富集（<1.1×）
- 模拟：直接命中纳米簇的 mEPSC 约 2× 远离簇的大小
- TTX 48h 后 PSD 面积增大（0.094 → 0.125 μm²），纳米簇增大

**证据强度**：高（超分辨直接可视化 + 功能模拟）

**局限性**：体外培养神经元；PALM 需要过量表达荧光蛋白融合体，可能影响蛋白分布

**改变了什么认识**：PSD 不是均质盘，而是有纳米热点结构；突触传递效率部分取决于受体与释放位点的纳米级对准

---

## S2 · Fukata et al. 2009 · PMID:19596852 · PMC2712995 · OPEN

**标题**：Mobile DHHC palmitoylating enzyme mediates activity-sensitive synaptic targeting of PSD-95

**核心问题**：哪个 PAT 负责 PSD-95 的活动敏感性棕榈酰化？

**方法**：DHHC-shRNA 筛选，TTX 活动阻断，免疫荧光，表面受体 assay

**关键发现**：
- DHHC2（树突局部酶）而非 DHHC3（Golgi 酶）介导活动敏感性 PSD-95 棕榈酰化
- 神经活动降低 → DHHC2 从移动小泡定位至突触后膜
- DHHC2 突触定位 → PSD-95 棕榈酰化 ↑ → PSD-95 突触聚集 → AMPAR 增加

**证据强度**：高（特定酶的 shRNA，因果链清晰）

**局限性**：以 TTX 为模型；体内 DHHC2 的精确调控机制（哪个上游信号）仍需澄清

---

## S3 · Fukata et al. 2013 · PMID:23836932 · PMC3704990 · OPEN

**标题**：Local palmitoylation cycles define activity-regulated postsynaptic subdomains

**核心问题**：PSD-95 的棕榈酰化是一次性修饰还是持续循环？

**方法**：构象特异性重组抗体（抗棕榈酰化 PSD-95），超分辨活细胞成像

**关键发现**：
- 连续的去/再棕榈酰化循环维持 PSD-95 纳米域
- DHHC2 在质膜的插入是 PSD-95 纳米域形成的必要条件
- FRAP 显示 PSD-95 突触半衰期 ~25 分钟（动态平衡）

**改变了什么认识**：PSD-95 不是静态锚定，而是通过持续能量消耗维持的动态组织

---

## S4 · Bhattacharyya et al. 2009 · PMID:19169250 · PMC2694745 · OPEN

**标题**：A critical role for PSD-95/AKAP interactions in endocytosis of synaptic AMPA receptors

**核心问题**：PSD-95 在 LTD 中扮演什么角色？

**方法**：shRNA knockdown，结构域点突变（L460P），NMDAR-LTD 和 mGluR-LTD 分开诱导

**关键发现**：
- PSD-95 knockdown 阻断 NMDAR-LTD，不影响 mGluR-LTD 或基本突触传递
- PSD-95 SH3-GK 域（L460P 或 SH3-GK 缺失）→ AKAP150 结合丧失 → LTD 阻断
- AKAP150 无法结合钙调磷酸酶的突变体 → LTD 阻断
- 结论：PSD-95-AKAP150-钙调磷酸酶轴是 NMDAR-LTD 的必要条件

**证据强度**：高（因果突变实验，双向对照）

---

## S5 · Nicoll & Schulman 2023 · PMID:37290118 · PMC10642921 · OPEN

**标题**：Synaptic memory and CaMKII

**类型**：综述，Physiological Reviews

**关键发现对本文的贡献**：
- 描述 LTP 的七步机制：CaMKII 激活 → TARP 磷酸化 → PDZ 配体暴露 → PSD-95 亲和力骤升 → AMPAR 积累
- 将 PSD-95 定位为 LTP 早期表达的关键中间节点

---

## S6 · Levy & Tümer 2022 · PMID:35457207 · PMC9025546 · OPEN

**标题**：Neurodevelopmental Disorders Associated with PSD-95 and Its Interaction Partners

**关键发现**：
- DLG4 变异谱系：PDZ 结构域功能缺失突变 → 智力障碍、癫痫、ASD
- 突显 PSD-95 在认知发育中的不可替代性

---

## S7 · Han et al. 2022 · PMID:35704570 · PMC9200272 · OPEN

**标题**：Neuroligin-3 Confines AMPA Receptors into Nanoclusters, thereby Controlling Synaptic Strength

**关键发现**：
- NL3 KO → PSD-95/AMPAR 纳米簇面积增大但密度降低
- 纳米簇内受体**密度**而非总大小决定突触强度
- 精化了槽位模型：密度 > 总数

---

## S8 · Ugalde-Triviño & Díaz-Guerra 2021 · PMID:34830481 · PMC8618101 · OPEN

**标题**：PSD-95: An Effective Target for Stroke Therapy Using Neuroprotective Peptides

**关键发现**：
- PSD-95 PDZ2 将 GluN2B-NMDAR 和 nNOS 连接 → 兴奋毒性
- nerinetide（抑制 GluN2B-PSD-95 连接）III 期临床研究

---

## S9 · Huie et al. 2025 · PMID:39511336 · PMC11914665 · OPEN

**标题**：Peptidomimetic inhibitors targeting TrkB/PSD-95 signaling improves cognition in Angelman Syndrome

**关键发现**：
- PSD-95 PDZ3 与 TrkB 相互作用是 BDNF 信号的关键
- 靶向 PDZ3 的肽药物改善 LTP 和认知

---

## S10 · Zhang & Lisman 2012 · PMID:22114157 · PMC3289452 · OPEN

**标题**：Activity-dependent regulation of synaptic strength by PSD-95

**关键发现**（重要争议）：
- PSD-95 过量表达单独不增强突触（需要 CaMKII 活动）
- 简单增加槽位数量 ≠ 增强突触；槽位必须被"激活"
- 提示槽位数量是必要非充分条件

---

## S11 · Schnell et al. 2002 · PMID:12201694 · 摘要仅（已引 TARP 文）

**标题**：Regulated multiprotein complex assembly at PSD-95

**关键发现（从 TARP 文章和文献知识）**：
- PDZ1/2 点突变 → AMPAR 骤降；PSD-95 过量表达 → AMPAR 增加
- 双向基因证据确立槽位模型

---

## 研究局限说明

- S11（Schnell 2002）未读取全文，基于摘要和 TARP 文章引用内容
- 所有其他来源（S1-S10）为 PMC 开放全文，已核实
- 体外培养神经元数据外推至在体需谨慎
- PSD-95 纳米域的超分辨数据大多依赖过量表达的荧光融合体，原生状态数据较少

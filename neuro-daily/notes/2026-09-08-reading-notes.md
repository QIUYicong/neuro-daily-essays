# 阅读笔记 · 2026-09-08
# 主题：兴奋毒性——突触内外的生死信号与钙-线粒体三联体

---

## S1：Hardingham & Bading (2010) — Nature Reviews Neuroscience
**PMID 20842175 / PMC2948541 / 开放全文**

**解决什么问题**：为什么NMDA受体既是学习的必要条件，又是神经元死亡的触发器？（"NMDAR悖论"）

**方法**：综述+机制梳理，整合多个研究室20年的发现。

**主要发现**：
- 突触内NMDAR（SynNMDARs）→ CREB磷酸化 → AID基因组（Atf3, Btg2, Npas4, Nr4a1等约10个）→ 上调抗凋亡蛋白和BDNF，下调Puma/Apaf-1/Caspase-9 → "存活屏障"
- 突触外NMDAR（ExSynNMDARs）→ Jacob入核 → CREB去磷酸化 → ERK灭活 → FOXO激活 → DAPK1激活（增大GluN2B单通道电导）→ Calpain-STEP-p38死亡级联
- 同等量的Ca²⁺，位置不同，信号完全相反
- "χ形模型"：突触活动↑ = 存活↑ 且 死亡↓；突触外活动↑ = 存活↓ 且 死亡↑
- 美金刚的选择性：快速解离→不干扰相位性突触激活；在慢性强直性外突触激活中积累
- HD相关：mtHtt增强外突触NMDAR电流+CREB-PGC1α受损；低剂量美金刚（1mg/kg）在YAC128小鼠恢复CREB磷酸化并防止运动缺陷

**改变了什么理解**：位置特异性（而非化学特异性）是NMDAR信号命运分叉的关键

**证据强度**：综述级别；依赖多个原始研究室的实验；体外细胞实验 + 转基因小鼠模型

**局限**：大多来自体外和啮齿动物实验；人类应用需要更多验证；Jacob/DAPK1机制在人脑中的直接证据有限

---

## S2：Choi DW (1987) — J Neuroscience
**PMID 2880938 / 未读取全文（仅摘要）**

**解决什么问题**：谷氨酸毒性的离子机制是什么？

**方法**：皮层神经元培养，谷氨酸处理+选择性改变胞外离子浓度（Na⁺、Cl⁻、Ca²⁺ 缺失/恢复）

**主要发现**：
- 两相模型：早期相（分钟级，Na⁺/Cl⁻ 依赖，可逆肿胀） + 迟发相（小时级，Ca²⁺依赖，不可逆死亡）
- NMDA受体激活可能主导Ca²⁺ 依赖性致死（与非NMDA型受体相比）
- 这是"钙假说（calcium hypothesis）"的奠基实验

**证据强度**：原始实验，控制良好；此后被大量研究重复验证

**局限**：体外培养系统；神经元成熟度和体内环境差异大

---

## S3：Verma, Lizama, Chu (2022) — Translational Neurodegeneration
**PMID 35078537 / PMC8788129 / 开放全文**

**解决什么问题**：急性兴奋毒性与慢性神经退行性疾病中的兴奋毒性有何不同？线粒体在其中扮演什么角色？

**主要发现**：
- 基线细胞质Ca²⁺：50–100 nM；活动期可达数µM
- MCU（线粒体钙单运体）和NCLX（线粒体Na⁺/Ca²⁺ 交换体）是主要调控器
- 慢性条件下：亚致死性兴奋毒性→线粒体Ca²⁺积累→ROS→树突退化（早于细胞体死亡）
- 新概念：EMT（兴奋性线粒体毒性），区别于急性"爆发式"兴奋毒性死亡
- PD：LRRK2突变→MCU表达上调→线粒体Ca²⁺摄取增强→树突线粒体损伤→PINK1/Parkin依赖的有丝分裂自噬
- AD：Aβ积累在突触线粒体→Ca²⁺超载；tau病理→Ca²⁺外排受损
- ALS：SOD1突变→早期MCU表达升高（补偿性？）后期↓
- HD：mtHtt→线粒体Ca²⁺处理受损（与Hardingham/Bading论文互补）
- MCU抑制剂（Ru360, DS16570511）在多种模型中显示保护效果

**改变了什么理解**：兴奋毒性在慢性病中可能以"亚致死性树突退行"形式存在，而非急性死亡；线粒体Ca²⁺平衡是跨疾病的共同靶点

**局限**：部分机制来自体外或特定突变体模型；对慢性病中EMT贡献大小仍有争议

---

## S4：Arnold et al. (2024) — Int J Mol Sci
**PMID 38891774 / PMC11171854 / 开放全文**

**ALS-兴奋毒性综述**

主要机制：
1. AMPA受体GluR2亚基的mRNA编辑缺陷（ADAR2酶活性降低）→ 未编辑GluR2→Ca²⁺可渗透AMPA受体 → 在正常谷氨酸浓度下已过度Ca²⁺内流
2. EAAT2丢失 → 谷氨酸清除失败 → 运动神经元暴露于高谷氨酸
3. 增强的突触前谷氨酸释放
4. GABAergic内抑制损伤

继发通路：Ca²⁺激活Calpain→裂解MFN2（线粒体融合蛋白）→线粒体碎裂→ROS；ER应激→TDP-43病理

利鲁唑（Riluzole）通过稳定Na⁺通道减少谷氨酸释放，是唯一获批的延缓ALS进展（约3个月）的兴奋毒性靶向药物

---

## S5：Neves et al. (2023) — Life Sciences
**PMID 37236602 / 未读取全文（仅摘要）**

缺血兴奋毒性综述：
- 定义：过量谷氨酸释放 + 膜受体过度激活 → 神经元损伤
- 涉及机制：谷氨酸受体下游促死亡信号 + Ca²⁺超载 + 氧化应激 + 线粒体损伤
- NAD代谢在兴奋毒性中的作用
- 缺血状态下GLT-1反向运输的关键性

---

## S6：Soriano et al. (2008) — J Neuroscience
**PMID 18923045 / J Neurosci开放全文**

PSD-95/nNOS解耦合策略：
- PSD-95连接GluN2B（NMDAR）与nNOS（PDZ1-2与GluN2B的C末端结合；PDZ2与nNOS的N末尾结合）
- 切断此连接（使用Tat-NR2B9c肽）→ 选择性阻断NMDAR→死亡信号，而不阻断Ca²⁺内流本身
- 不损伤突触可塑性（LTP保留）
- 细胞死亡信号依赖PDZ结合，但程度不同（某些更依赖NR2B C末端）
- nerinetide（Tat-NR2B9c）已进入中风III期试验

---

## S7：Soriano & Hardingham (2007) — J Physiology
**PMID 17690142 / J Physiol开放全文**

空间隔离的NMDAR信号：
- "当等量的Ca²⁺由突触和突触外NMDAR触发时，引发截然不同的下游事件"
- 信号分子直接与NMDAR物理结合（PDZ相互作用），决定信号传导的方向性
- 此文是Hardingham/Bading 2010大综述的原始研究支撑

---

## 关键专业术语整理

| 术语 | 英文 | 简释 |
|------|------|------|
| 兴奋毒性 | Excitotoxicity | 谷氨酸过度激活导致神经元死亡 |
| 突触内NMDAR | Synaptic NMDARs (SynNMDARs) | PSD内受体，受相位性激活，促存活 |
| 突触外NMDAR | Extrasynaptic NMDARs (ExSynNMDARs) | PSD外受体，受强直性激活，促死亡 |
| 延迟性钙失调 | Delayed Calcium Deregulation (DCD) | 兴奋毒性后期Ca²⁺ 无法恢复的临界点 |
| mPTP | Mitochondrial Permeability Transition Pore | 线粒体通透性转换孔，开放→死亡 |
| DAPK1 | Death-Associated Protein Kinase 1 | 磷酸化GluN2B，增强外突触Ca²⁺内流 |
| Jacob | 钙传感蛋白 | 外突触激活后入核，CREB去磷酸化 |
| MCU | Mitochondrial Calcium Uniporter | 线粒体钙摄取通道 |
| NCLX | Mitochondrial Na⁺/Ca²⁺ Exchanger | 线粒体钙外排通道 |
| EAAT2/GLT-1 | Excitatory Amino Acid Transporter 2 | 星形胶质细胞谷氨酸摄取转运体 |
| PSD-95 | Postsynaptic Density Protein 95 | 突触后脚手架蛋白，连接NMDAR与nNOS |
| nNOS | Neuronal Nitric Oxide Synthase | 产生NO，在兴奋毒性中产生亚硝化应激 |
| 美金刚 | Memantine | 低亲和力NMDA开通道阻断剂，选择性外突触 |
| nerinetide | Tat-NR2B9c / NA-1 | PSD-95-nNOS解耦合肽，III期试验 |

---

*阅读者：Claude | 日期：2026-09-08*

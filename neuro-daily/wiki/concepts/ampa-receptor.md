---
title: AMPA 受体
slug: ampa-receptor
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-26
updated: 2026-10-21
revision_count: 6
dimensions: [molecular, synaptic, cognition, behavior]
related: [nmda-receptor, ltp, ltd, camkii, calcineurin, arc-arg31, synaptic-transmission, hebbian-learning, tarp-auxiliary-subunit, synaptic-scaling, homeostatic-plasticity, homer1a, slow-wave-sleep, major-depressive-disorder, bdnf]
prerequisites: [synaptic-transmission, action-potential]
opens_questions: [Q-ampa-receptor-silent-synapse, Q-ampa-glua1-atd-partners, Q-homer1a-03]
source_articles: [2026-05-26-nmda-receptor-ltp, 2026-06-04-ltd-long-term-depression, 2026-07-03-synaptic-scaling-homeostatic-plasticity, 2026-10-16-homer1a-arc-sleep-ampa-downscaling, 2026-06-28-tarp-ampa-receptor-synaptic-trafficking, 2026-10-21-depression-ketamine-rapid-antidepressant]
key_sources: ["PMID:30359599", "PMID:34271016", "PMID:22510460", "PMID:24183021", "PMID:19169250", "PMID:38973508", "PMC:11895523", "PMID:28154077", "PMC:5382711", "PMID:11140673", "PMID:36223737", "PMID:37471228", "PMID:39380368", "PMID:30894661", "PMID:27144355", "PMID:20724638"]
---

# AMPA 受体 (AMPA Receptor / AMPAR)

> **一句话定义**：突触快速兴奋传递的主要执行者，无 Mg²⁺ 阻断、衰减极快（~2–5 ms）；其在突触后膜上的数量是 LTP 期间突触权重增强的主要决定因素。

## 当前理解

我们现在认为，AMPA 受体是突触快速 EPSP 的核心来源。与 NMDA 受体不同，AMPA 受体不需要突触后去极化即可开放——谷氨酸结合后在几毫秒内即完成激活和失活循环，产生快速的突触电流。AMPA 受体在突触后膜上的数量并非固定，而是随活动状态动态调节：LTP 时大量插入（突触权重增强），LTD 时从突触移除（突触权重减弱）。这一动态性使 AMPA 受体成为突触可塑性的"物理实现"——突触权重在生化上等价于突触后膜 AMPA 受体的数量和电导。

## 关键机制

### 亚基组成与分工（分子层面）

AMPA 受体是由 GluA1–4 亚基组成的四聚体（通常为二聚体的二聚体）。成熟海马 CA1 区：
- ~80% 为 **GluA1/GluA2 异聚体**（高表达）
- ~20% 为 **GluA2/GluA3 异聚体**（较少）

**GluA1 vs GluA2 的差异**：
- GluA1（长尾 C 末端）：负责**活动依赖性**突触运输；LTP 诱导时主要被插入
- GluA2/GluA3（短尾 C 末端）：负责**组成性循环**（constitutive cycling），维持基础突触传递
- GluA2 含有 Arg（R）于 Q/R 编辑位点，使受体对 Ca²⁺ 不通透（Ca²⁺-impermeable AMPARs）
- GluA2 缺失的受体（GluA1 同聚体）对 Ca²⁺ 通透——这类受体可能在某些可塑性状态下增加以提高 Ca²⁺ 流入

### LTP 期间 AMPA 受体插入（突触层面）

1. CaMKII 磷酸化 **GluA1 S831** → 提高单通道电导，促进 GluA1 靶向 PSD
2. CaMKII 同步磷酸化 **TARP（Stargazin/γ-2 的 polybasic region；TARPγ-8 的 Ser277/Ser281）** → 静电掩蔽解除 → PDZ 配体暴露 → PSD-95 亲和力骤升 10–30 倍（Opazo 2010, Park 2016）
3. AMPA 受体从**再循环内体**（recycling endosome）通过**胞吐**到达树突干非突触区
4. 受体-TARP 复合物通过**横向扩散（lateral diffusion）**进入 PSD，被高亲和力的 TARP-PSD-95 相互作用**捕获锁定**（"扩散陷阱"）
5. **TARP（如 Stargazin/γ-2；海马中主要是 TARPγ-8）**与 PSD-95 的 PDZ1/2 结构域相互作用，将受体**锚定**于突触"槽位"（synaptic slot）

**TARP 磷酸化是 LTP 突触后表达的最后一公里**：Ravi et al. 2022（PMID:36223737）正交突变实验证明，TARP PDZ 配体-PSD-95 PDZ 单一相互作用是 LTP 表达的最小充分条件——无需其他因子。Park et al. 2023（PMID:37471228）ExSYTE 化遗传学工具直接因果证明 TARP-脂质静电锚定是 LTP 分子开关。

### 沉默突触与 AMPA 受体（突触层面）

沉默突触（silent synapse）只含 NMDA 受体，无 AMPA 受体 → 静息电位下功能沉默。LTP 诱导后，AMPA 受体插入这类突触 → 突触觉醒。这可能是早期学习和发育期突触精炼的关键机制。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| LTP 主要通过 AMPA 受体插入（非释放增加）表达 | MK-801 法、PPF 不变、星形胶质细胞转运体电流不变 | PMID:22510460 (PMC3367554) | 高 |
| CaMKII 磷酸化 GluA1 S831 并驱动其突触插入 | CaMKII 突变 + 磷酸化特异性抗体 | PMID:30359599 (PMC6214363) | 高 |
| LTP 需要 GluA1，但不需要 GluA2 | GluA1/GluA2 条件性敲除实验 | PMID:34271016 (PMC9122021) | 高 |
| TARP-PSD95 相互作用锚定 AMPA 受体于突触 | Stargazin 突变 + 电生理 | PMID:34271016 (PMC9122021) | 高 |

### LTD 期间 AMPA 受体内吞（突触层面）

LTD 时，AMPA 受体从突触后膜内吞，是突触权重降低的物理实现（Huganir & Nicoll, 2013，PMC4195488）：

1. **GluA1 Ser831/Ser845 去磷酸化**（PP2B→PP1 级联）→ 受体稳定性降低，开始横向扩散离开 PSD
2. **GluA2 Ser880 磷酸化**（PKC）→ 破坏 GluA2-GRIP1/2 结合（突触锚点丧失）→ 转为 PICK1 结合 → 内吞
3. **Arc 蛋白**（mGluR-LTD 路径）→ Arc 与 dynamin/endophilin 结合 → 加速网格蛋白包被小泡形成 → AMPAR 内化

**重要争议**：GluA2/GluA3 双敲除小鼠海马 LTD 仍然正常，表明 GluA2 Ser880 路径不是唯一的 LTD 表达机制，存在 GluA2 非依赖的备用内吞路径（分子身份未明，→ Q-ltd-glua2-redundancy）。

内化后受体进入早期内体：可被再循环回突触（LTP 时优先）或被溶酶体降解（LTD 维持时可能）。

### GluA1 插入：快速抗抑郁药的收敛效应终点（2026-10-21 新增）

**来源**：《氯胺酮与快速抗抑郁机制》文章 #189（Duman RS 2019, PMID:30894661；Zanos P et al. 2016, PMID:27144355；Li N et al. 2010, PMID:20724638）

Duman RS 2019 的综述揭示了一个重要规律：氯胺酮、东莨菪碱、HNK 三类结构完全不同的快速抗抑郁药，尽管初始分子靶点各异，但**最终都依赖 GluA1 突触插入**——NBQX（AMPA 受体特异性阻断剂）可消除所有三者的抗抑郁效果。

**三类快速抗抑郁药的 AMPA 依赖性比较**：

| 化合物 | 初始靶点 | GluA1↑？ | NBQX 消除？ | mTOR 依赖？ |
|--------|---------|---------|-----------|-----------|
| 氯胺酮 | NMDA 受体阻断 | 是 | 是 | 是（2-24h机制） |
| (2R,6R)-HNK | 直接 AMPA 增强 | 是 | 是 | 否 |
| 东莨菪碱（毒蕈碱拮抗剂）| mAChR 阻断 | 是 | 是 | 是 |

**Val66Met 多态性验证**：Val66Met 突变损害 BDNF 的活动依赖性胞吐（分泌，而非合成）。在 Val66Met KI 小鼠中，三类快速抗抑郁药均失效——证明 BDNF 活动依赖性释放（而非 BDNF 合成本身）是上游必要条件，而 GluA1 增加是 BDNF 信号作用的最终突触执行环节。

**与经典 LTP 的 GluA1 插入的区别**：
- 经典 LTP：高频突触刺激 → CaMKII → GluA1 S831 磷酸化 → 局部胞吐 → 数分钟内特定突触插入
- 快速抗抑郁：mTOR 或 BDNF-TrkB 信号 → 广泛 mPFC 突触蛋白合成上调 → 数小时内 mPFC 整体突触密度增加

两者共享 GluA1 插入这一终点，但上游触发机制和空间尺度不同（局部突触 vs 脑区范围的结构性重建）。

### 睡眠依赖的 GluA1 下调（Homer1a/Arc 通路）

**2026-10-16 新增**：与经典 LTD（需要 NMDAR 激活触发）不同，NREM 睡眠期间存在一条独立的 **GluA1 特异性下调通路**，由 Homer1a 和 Arc 协同介导：

1. **NA 屏障解除**：入睡时蓝斑静默，NA 水平骤降，Homer1a 进入 PSD 的障碍消失
2. **腺苷 A1R 促进**：积累的腺苷通过 A1R 主动引导 Homer1a 向 PSD 靶向输送
3. **Homer1a 进入 PSD**：瓦解 mGluR1/5-IP3R 支架 → GluA1/GluA2 开始从 PSD 松动
4. **GluA1 Ser845 去磷酸化**：NA 下降→cAMP 下降→PKA 活性下降→Ser845 去磷酸化 → GluA1 横向扩散
5. **Arc 执行内吞**：Arc 靶向去磷酸化 CaMKIIβ 的安静突触，调用 dynamin/endophilin
6. **净效果**：皮层突触体 GluA1 在 5h 睡眠期间比剥夺状态降低约 31.7%（Squarcio 2024）；p-GluA1(845) 在睡眠剥夺后比正常睡眠高出约 78.9%

**与经典突触缩放的区别**：经典突触稳态缩放（Turrigiano 1998）主要通过 GluA2 通路（GRIP/ABP 依赖），时间尺度数小时到数天，乘法性全细胞调节。睡眠依赖的削减通过 GluA1/Homer1a 通路，时间尺度数小时，且具有突触特异性（Arc 逆向标记绕过印迹突触）。两者是独立的互补机制。

## 连接

- [[nmda-receptor]] — NMDA 受体 Ca²⁺ 内流激活 CaMKII，后者驱动 AMPA 受体插入；低 Ca²⁺ 时激活 PP2B，驱动内吞
- [[ltp]] — AMPA 受体插入（exocytosis → lateral diffusion → PSD 锚定）是 LTP 在突触后的主要表达机制
- [[ltd]] — AMPA 受体内吞（endocytosis）是 LTD 在突触后的主要表达机制；GluA1 去磷酸化 + GluA2 Ser880 磷酸化是关键开关
- [[camkii]] — CaMKII 磷酸化 GluA1 S831（LTP），与 PP2B-PP1 去磷酸化相对立（LTD）
- [[calcineurin]] — PP2B/PP1 级联在 LTD 时去磷酸化 GluA1 Ser831/845，驱动内吞
- [[arc-arg31]] — Arc 是 mGluR-LTD 路径中促进 AMPAR 内吞的执行蛋白
- [[synaptic-transmission]] — AMPA 受体是快速 EPSP 的主要产生者
- [[tarp-auxiliary-subunit]] — TARP 是 AMPA 受体从 ER 到突触的全程辅助亚基：ER 出口许可、横向扩散引导、PSD 锚定（槽位模型）、门控动力学改造（失敏减慢/亲和力提升）；CaMKII 磷酸化 TARP 是 LTP 突触后表达的分子核心（#184）
- [[synaptic-scaling]] — 突触稳态缩放专门使用 GluA2 通路（不同于 LTP 用的 GluA1），Gainey 2009 直接证明这是两套独立的受体亚型通路
- [[homer1a]] — Homer1a 是睡眠期 GluA1 从 PSD 脱落的上游触发器；双门控由 NA（抑制）和腺苷 A1R（激活）决定
- [[slow-wave-sleep]] — NREM 睡眠中，GluA1 皮层突触体水平在 5h 恢复睡眠后从剥夺水平降低约 31.7%（Squarcio 2024）
- [[major-depressive-disorder]] — GluA1 突触插入是所有快速抗抑郁药（氯胺酮、HNK、东莨菪碱）的收敛效应终点；NBQX 消除所有快速抗抑郁效果

## 未解问题

- Q-ampa-receptor-silent-synapse：沉默突触觉醒中，AMPA 受体的首个分子被插入的精确分子触发事件是什么？
- Q-ampa-glua1-atd-partners：GluA1 氨基末端结构域（ATD）通过哪些跨突触配体（neuronal pentraxins？细胞黏附分子？）建立突触外的相互作用？
- Q-tarp-01（高优先级）：TARP 帮助 AMPA 受体离开 ER 的具体分子机制（TARP 屏蔽 ER 滞留信号还是帮助达到 COP II 识别构象？）
- Q-tarp-03（中优先级）：LTP 后期 TARP 磷酸化状态维持机制（与 KIBRA-PKMζ 的关联）

## 修订历史

- 2026-10-21 · 修订 rev6 · 基于《氯胺酮与快速抗抑郁机制》(#189) · 新增"GluA1插入：快速抗抑郁药的收敛效应终点"段落（Duman 2019, PMID:30894661；Zanos 2016, PMID:27144355；Li 2010, PMID:20724638）；三类快速抗抑郁药的AMPA依赖性对比表；Val66Met验证；与经典LTP的GluA1插入区别；连接新增major-depressive-disorder；related新增major-depressive-disorder, bdnf；key_sources新增3条；source_articles新增#189
- 2026-06-28 · 修订 rev5 · 基于《AMPA 受体的突触之旅：TARP 辅助亚基》(#184) · 扩充 LTP 插入机制，加入 TARP polybasic region 的 CaMKII 磷酸化步骤和扩散陷阱详细机制（Opazo 2010, Park 2016）；更新 [[tarp-auxiliary-subunit]] 链接为正式描述（删除"待建页面"）；key_sources 新增 4 条 TARP 来源；未解问题新增 Q-tarp-01/Q-tarp-03；source_articles 新增 #184
- 2026-10-16 · 修订 rev4 · 基于《睡眠如何修剪突触：Homer1a 与 Arc 的分子协奏》(#176) · 新增"睡眠依赖的 GluA1 下调（Homer1a/Arc 通路）"段落；Squarcio 2024 定量数据（31.7%降低/78.9%升高）；GluA1 vs GluA2 通路的睡眠/缩放区别；related 新增 homer1a、slow-wave-sleep；连接新增 2 条；key_sources 新增 4 个
- 2026-07-03 · 修订 · 基于《突触稳态》(#69) · 在连接段落新增 synaptic-scaling；明确 GluA2 通路是突触缩放（非 LTP）的特异性分子路径（Gainey 2009 PMID:19458219）；related 新增 synaptic-scaling、homeostatic-plasticity
- 2026-05-26 · 创建 · 基于《NMDA 受体：突触的巧合检测器》一文 · 初始置信度：高
- 2026-06-04 · 修订 · 基于《LTD 文章》· 新增"LTD 期间 AMPA 受体内吞"机制段落；GluA2 Ser880 磷酸化→PICK1 路径；Arc 在 mGluR-LTD 中的内吞执行角色；GluA2 双敲除后 LTD 正常的争议（备用内吞路径）；related 增加 ltd、calcineurin、arc-arg31；key_sources 新增 PMC4195488, PMC2694745

## 来源文章

- [[2026-05-26-nmda-receptor-ltp]]
- [[2026-06-04-ltd-long-term-depression]]
- [[2026-07-03-synaptic-scaling-homeostatic-plasticity]]
- [[2026-10-21-depression-ketamine-rapid-antidepressant]]

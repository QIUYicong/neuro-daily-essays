---
title: 长时程增强（LTP）
slug: ltp
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-26
updated: 2026-09-23
revision_count: 14
dimensions: [synaptic, cellular, cognition, brain-region, disease, molecular]
related: [nmda-receptor, ampa-receptor, camkii, hebbian-learning, synaptic-transmission, ltd, btsp, place-cell, hippocampal-circuit, engram-cells, calcineurin, dopamine-reward-prediction-error, synaptic-tagging-capture, three-factor-learning-rule, alzheimers-disease, amyloid-beta-oligomers, fear-conditioning, amygdala, pattern-completion, complementary-learning-systems, bdnf, arc-arg31, astrocyte, tripartite-synapse, d-serine, astrocyte-calcium-signaling, synaptic-scaling, homeostatic-plasticity, liquid-liquid-phase-separation, postsynaptic-density, pkm-zeta, dendritic-spine, cofilin-actin-spine]
prerequisites: [nmda-receptor, synaptic-transmission, action-potential]
opens_questions: [Q-ltp-lifetime-mechanism, Q-ltp-behavior-correspondence, Q-ltp-presynaptic-component, Q-spine-btsp-01, Q-spine-early-late-02]
source_articles: [2026-05-26-nmda-receptor-ltp, 2026-05-28-place-cells-btsp, 2026-05-31-engram-cells-optogenetic-proof, 2026-06-04-ltd-long-term-depression, 2026-06-07-dopamine-reward-prediction-error, 2026-06-08-alzheimers-amyloid-synaptic-mechanism, 2026-05-30-amygdala-fear-memory, 2026-06-24-hippocampal-ca3-pattern-completion, 2026-06-28-bdnf-trk-b-plasticity-memory, 2026-07-02-astrocyte-tripartite-synapse, 2026-09-12-liquid-liquid-phase-separation-postsynaptic-density, 2026-09-21-pkm-zeta-late-ltp-persistence, 2026-09-23-dendritic-spine-structural-plasticity]
key_sources: ["PMID:22510460", "PMID:4727084", "PMID:6306230", "PMID:34908526", "PMID:28883072", "PMID:26023136", "PMID:26982728", "PMID:7708662", "PMID:9020359", "PMID:11932745", "PMID:17360908", "PMID:21543591", "PMID:24896183", "PMID:11584069", "PMID:16099088", "PMID:17942328", "PMID:20075918", "PMID:27565345", "PMID:29976799", "PMID:16463388", "PMID:15958741", "PMID:27187150", "PMID:41814337", "PMID:41889799", "PMID:39814881"]
---

# 长时程增强 (LTP, Long-Term Potentiation)

> **一句话定义**：高频或关联性刺激后突触传递效率的持久性增强，由 NMDA 受体介导的 Ca²⁺ 内流触发、CaMKII 维持、AMPA 受体插入表达，是目前研究最充分的学习记忆突触基础。

## 当前理解

我们现在认为，LTP 是突触可塑性的核心机制之一，是"用进废退"原则在突触层面的分子实现。LTP 的诱导需要 NMDA 受体的激活（即突触前和突触后活动的 Hebb 型巧合），Ca²⁺ 内流激活 CaMKII（自磷酸化至 T286），CaMKII 驱动 AMPA 受体从胞内再循环内体通过胞吐和横向扩散插入突触后致密区（PSD），突触传递效率持久增强。早期 LTP（E-LTP，数小时）主要依赖蛋白修饰（磷酸化）；晚期 LTP（L-LTP，数天至数周）还需要新蛋白质合成和树突棘结构的持久改变。海马 CA1 突触 LTP 的表达主要在突触后（AMPA 受体插入），而苔藓纤维→CA3 的 LTP 有明显的突触前成分（cAMP 依赖的递质释放增加）。

**2026-05-30 新增（来自《当杏仁核学会恐惧》文章）**：LTP 不只是海马 CA1 的专属机制，而是**大脑跨区域的通用联想写入算法**。在外侧杏仁核（LA）中，恐惧条件反射的分子机制与海马 LTP **完全同构**：CS（音调）弱激活 LA 突触（AMPA），US（电击）强去极化同一神经元（NMDA 去 Mg²⁺）→ Ca²⁺→CaMKII→GluA1 插入。Nabavi 等人 2014 年光遗传实验明确证明：LA 突触 LTP 是恐惧记忆的因果底物（LTP→恐惧；LTD→消除；再 LTP→恢复）。这强化了 LTP 是 Hebbian 学习跨脑区统一机器的论断。

**重要：LTP的病理镜像**：LTP是学习的正向引擎，也是疾病攻击的核心靶标。Aβ寡聚体通过至少五条并行通路（突触外NR2B/p38/CREB、calcineurin过激活/AMPA内吞、BDNF/TrkB截断、tau错位、PrPC/Fyn/NR2B过激活）将LTP机器系统性拆解，是阿尔茨海默病早期记忆损害的突触层面机制。**关键洞见**：LTP的可逆阻断（"突触沉默"而非细胞死亡）在早期AD是可恢复的（Shankar et al. 2007：撤去Aβ处理5天后棘密度恢复），这解释了为什么早期干预有潜在效果。

**2026-05-28 新增（来自《场所细胞》文章）**：LTP 并非大脑唯一的持久性突触增强机制。海马 CA1 中的**行为时间尺度突触可塑性（BTSP）**是一种独立的学习规则，由树突钙平台电位（而非 NMDA 受体激活）触发，时间窗口约 ±3–4 秒（远超 LTP 诱导的毫秒级）。BTSP 可在单次体验中建立稳定的场所场。两者可能各有适用场景：LTP 适合精细调整和长期巩固，BTSP 适合快速写入行为级别的情景记忆。两者可能共享 NMDA 受体下游的部分分子机器（CaMKII 等），但触发条件和时间逻辑完全不同。

## 关键机制

### 1. 诱导（惰性 → 激活）

**必要条件**：NMDA 受体激活 → Ca²⁺ 内流（需 Hebb 型巧合：突触前谷氨酸 + 突触后去极化）

**Ca²⁺ 信号**：高 Ca²⁺ 脉冲（突触后棘内局部 Ca²⁺ 浓度短暂升高 10–100 倍）

**常用诱导协议**：
- 高频刺激（HFS）：100 Hz 四联，经典协议
- θ-burst 刺激（TBS）：5 Hz bursts × 4–5 spikes/burst，更接近体内θ振荡节律，效率更高
- 关联型配对协议：突触前刺激 + 突触后去极化配对

### 2. 早期表达（E-LTP，分钟–小时）

**Ca²⁺ → CaMKII 激活 → T286 自磷酸化**（自主活化状态）→
- GluA1 S831 磷酸化（提高单通道电导）
- AMPA 受体从再循环内体胞吐 → 树突膜 → 横向扩散 → PSD（被 TARP-PSD95 锚定）
- 沉默突触觉醒（原无 AMPA 受体的突触获得 AMPA 受体）
- 树突棘体积增大，PSD 面积扩大

### 2b. LTP 的相变维度（LLPS 框架，2016–2026 新增）

**2026-09-12 新增（来自《突触的自组装奥秘》文章，#142）**：LTP 的分子事件可以从"信号级联"框架升级为"相变控制的计算开关"框架。

突触后密度（PSD）本身是由 PSD-95/SynGAP 多价相互作用维持的**液态-凝胶态凝聚体**（LLPS）：

- **静息 PSD**：SynGAP（同源三聚体）富集在 PSD-95 形成的凝聚相中，浓度比背景高约 400–1000 倍，持续抑制 Ras-ERK 通路 → AMPAR 低丰度
- **LTP 诱导时**（Ca²⁺ → CaMKII）：CaMKII 磷酸化 SynGAP，削弱其与 PSD-95 的结合亲和力，SynGAP 在**数秒内集体从凝聚相逸散** → Ras 抑制解除 → Ras-ERK 激活 → AMPAR 向 PSD 招募插入
- **CaMKII 凝聚体**：激活的 CaMKII 本身也能在突触处形成凝聚体（LLPS），增加局部 CaMKII 浓度，可能作为"突触标签"物理基础（Hayashi 2022, PMID:34375719）

**关键转变**：LTP 不只是"哪些分子被磷酸化了"，而是"凝聚体的相组成发生了什么集体变化"——学习的分子本质包含一次相变。

来源：PMID:27565345（Zeng et al. 2016 Cell）；PMID:30078712（Zeng et al. 2018 Cell）；PMID:41405989（Chen & Zhang 2026 Cell Reports）

### 3. 晚期表达（L-LTP，小时–数天及以上）

- 需要新蛋白质合成
- 信号通路：PKA → CREB → 即早基因（IEG）→ 结构蛋白
- 树突棘持久形态改变（穿孔突触出现、可能发生突触分裂）
- L-LTP 维持机制仍有争议（见未解问题）

### 5. 多巴胺调制的 LTP（DA-LTP）与突触标记-捕获

**2026-06-07 新增（来自《多巴胺的时间机器》文章）**：LTP 不只由 Hebbian 激活触发，还可以由多巴胺 D1/D5 受体调制（DA-LTP），且 LTP 的晚期阶段通过"突触标记与捕获"（STC）机制被选择性诱导。

**DA-LTP 分子链**（Huang & Kandel 1995，PMC42234）：
- D1/D5 受体激活 → 偶联 Gs → 腺苷酸环化酶 → cAMP↑ → PKA 激活
- PKA → ① GluA1 Ser845 磷酸化（降低脱敏，E-LTP 增强）；② CREB Ser133 磷酸化 → IEGs 转录 → PRPs 合成
- PRPs（Arc、Homer、新 AMPAR 等）被带有标签的突触捕获 → L-LTP 维持
- 即使没有高频 Hebbian 刺激，D1/D5 激动剂单独可在海马 CA1 诱导 >6h 的 L-LTP（蛋白质合成依赖）

**三因素规则中 LTP 的角色**：LTP 是三因素学习规则（Δw = (pre × post) × DA）的正向输出——Hebbian 激活（pre × post）设置突触标签，DA 爆发（三因素）提供 PRP 合成触发，PRP 被标签捕获 → L-LTP。

### 4. CaMKII 对 LTP 维持的必要性

2021 年 Tao et al. 发现：在已建立的 LTP 之后，持续抑制 CaMKII 会导致 LTP 完全逆转。这证明 CaMKII 不只诱导 LTP，也是其维持所必需的——提示 CaMKII 的持续活化可能是 E-LTP 的关键维持机制。

### 7. 三方突触条件：星形胶质细胞的 D-丝氨酸是 LTP 的隐性必要条件

**2026-07-02 新增（来自《大脑的第三方》文章，#68）**：LTP 的经典 Hebb 规则（突触前 + 突触后活动 → NMDA-Ca²⁺ → CaMKII → AMPAR 插入）是 LTP 的**充分描述**，但并非**完整描述**。还有一个隐性条件：附近星形胶质细胞必须供给足够的 D-丝氨酸占据 NMDA 受体的 GluN1 协同激动位点。

**因果证据**（Henneberger et al. 2010, *Nature*, PMID: 20075918, PMC2807667）：
- 将单个星形胶质细胞的 Ca²⁺ 钳制于低水平（EGTA 胞内灌注）→ 该星形胶质细胞覆盖范围（<100 μm）内所有突触的 LTP 完全消失
- 外源 D-丝氨酸 + Ca²⁺ 钳制 → LTP 完全恢复
- 阻断星形胶质细胞内 D-丝氨酸合成（HOAsp 阻断丝氨酸消旋酶）→ LTP 消失
- NMDA 受体响应 −22%（协同位点占用率降低）

**含义**：LTP 的诱导需要**三方参与者**的协同：突触前（谷氨酸/去极化）+ 突触后（NMDA 受体开放、CaMKII）+ 星形胶质细胞（D-丝氨酸供给认证）。每个星形胶质细胞是其局部域（约 100 μm，覆盖数万突触）内所有突触 LTP 资格的"认证控制器"——其 Ca²⁺ 信号状态成为 LTP 写入的门控变量之一。

### 8. PKMζ与aPKC功能层：L-LTP的持久性维持机制（克里克问题的分子答案）

**2026-09-21 新增（来自《记忆的分子守夜人》文章，#151）**：L-LTP诱导后，AMPA受体插入突触后膜如何抵抗蛋白周转而持续数天至数年？这一"克里克问题"现有了分子答案：**PKMζ和PKCι/λ构成的aPKC功能层** + **KIBRA-PKMζ寡聚体传递激活状态**。

**PKMζ的持久维持机制**：
- PKMζ（蛋白激酶M-ζ）是非典型PKCζ的无调节域剪接形式，合成即持续激活
- PKMζ通过阻止含GluA2 AMPA受体内吞，**主动维持**突触AMPA受体密度（Ling 2006, PMID:16463388）
- L-LTP诱导后30–60分钟，PKMζ在突触局部合成并作为STC框架的第一个明确PRP被标签捕获（Sajikumar 2005, PMID:15958741）

**功能冗余层（非单一分子）**：
- 单独敲除PKMζ：记忆正常（PKCι/λ从发育期起代偿上调，Lee 2013, PMID:23283171；Tsokas 2016, PMID:27187150）
- **同时敲除PKMζ + PKCι/λ（双KO）→ L-LTP完全消失**（E-LTP可诱导但3小时后衰退）（Tsokas 2026, PMID:41889799）
- 结论：**aPKC功能本身不可或缺，但具有分子冗余**

**KIBRA-PKMζ寡聚体：克里克问题的分子答案**（Hsieh 2026, PMID:41814337）：
- KIBRA支架蛋白与PKMζ在突触后密度形成稳定寡聚体（AlphaFold3验证）
- 新合成PKMζ加入复合物后被"感染性磷酸化"激活（类朊病毒构象传播，但属生理机制）
- 老PKMζ降解，新PKMζ继承激活状态 → **激活状态的代际传递**，无需蛋白质永生

**体内证据**（Hsieh 2021, PMID:33540466）：恐惧记忆编码时激活的海马CA1细胞（c-Fos标记）在1个月后仍维持高于背景水平的PKMζ，直接证明PKMζ在自然记忆中的长期持续。

**ZIP的重新解读**（Stokes 2025, PMID:39814881）：ZIP注射可破坏记忆的机制并非PKMζ特异性抑制，而是阳离子肽→endophilin-A2→巨胞饮→AMPAR非特异性大规模内吞。ZIP实验结论需全面重新评估。

### 6. BDNF 对 L-LTP 的催化作用（突触固结机制）

**2026-06-28 新增（来自《BDNF：大脑给自己的成长信号》文章，#64）**：

L-LTP 除依赖 PKA/CREB/PRPs 通路外，还需要 BDNF/TrkB 信号的介入（Bramham & Messaoudi 2005，PMID:16099088；Lu et al. 2008，PMID:17942328）：

- 高频刺激 → NMDA-Ca²⁺ → 上调 BDNF 转录（通过 CREB 激活 BDNF 多启动子之一）
- **活动依赖性 BDNF 分泌**到突触间隙（只在激活突触附近，提供局部特异性）
- BDNF/TrkB → ERK → **Arc mRNA 局部翻译**（Arc 蛋白调节 AMPA 受体内吞和肌动蛋白重组 → 树突棘稳定）
- BDNF/TrkB → PI3K/Akt/mTOR → 其他 PRP（可塑性相关蛋白）合成
- **关键点**：BDNF KO 小鼠 E-LTP 基本正常，但 L-LTP 严重受损——说明 BDNF 是 E-LTP→L-LTP 转化的必要催化剂，而非 LTP 诱导本身的必要条件

**BDNF 的 L-LTP 作用与 DA 的 STC 机制的关系**：两者共享最终产物（PRPs 合成，包括 Arc），但 BDNF 由局部突触活动触发（活动直接诱导），DA 则由奖励预测误差触发（远程调制）。两条路径汇聚于同一套局部蛋白合成机制，可能在实际学习中协同工作。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| LTP 诱导需要 NMDA 受体 | AP5 阻断消除 LTP，保留基础传递 | PMID:6306230 | 高 |
| LTP 主要在突触后表达（AMPA 受体插入） | MK-801 速率法、PPF 不变、星形胶质细胞转运体电流不变 | PMID:22510460 (PMC3367554) | 高 |
| CaMKII 是 LTP 诱导和维持所必需的 | CaMKII 抑制剂（myr-CN27）在 LTP 后逆转增强 | PMID:34908526 (PMC8798046) | 高 |
| LTP 与突触后 AMPA 受体密度增加相关 | 静默突触实验、单通道电导增加 | PMID:22510460 (PMC3367554) | 高 |
| 树突棘增大伴随 LTP | 活体双光子成像 | PMID:22510460 (PMC3367554) | 高 |
| θ-burst 比等量高频刺激更有效诱发 LTP | 对比实验 | PMID:25452022 (PMC4411212) | 中-高 |
| LA-LTP是恐惧记忆因果底物（光遗传LTP→恐惧；LTD→消除；再LTP→恢复） | 光遗传双向操控LA突触 + 行为测试 | PMID:24896183（Nabavi et al. 2014, Nature） | 极高（双向因果） |

## 连接

- [[alzheimers-disease]] — AD的核心病理是LTP的系统性失效；Aβ寡聚体通过多通路将LTP机器单向瓦解
- [[amyloid-beta-oligomers]] — LTP的主要分子劫持者；通过突触外NR2B、calcineurin、BDNF截断等机制阻断LTP
- [[nmda-receptor]] — LTP 诱导的必要门卫，提供 Ca²⁺ 内流触发
- [[ampa-receptor]] — LTP 表达的主要执行机制（受体插入增加突触权重）
- [[camkii]] — Ca²⁺ 内流的第一个主要下游效应器，对诱导和维持均必要
- [[hebbian-learning]] — LTP 是 Hebb 规则在突触层面的分子实现
- [[synaptic-transmission]] — LTP 增强突触传递效率，是突触传递的可塑性形态
- [[btsp]] — 与 LTP 并列的第二种突触增强机制；秒级时间窗口，由树突钙平台电位触发；两者互补
- [[place-cell]] — 场所场的形成主要由 BTSP 驱动（非 LTP），但 LTP 可能参与场所场的长期巩固
- [[dopamine-reward-prediction-error]] — DA D1/D5 受体通过 cAMP→PKA→CREB 通路诱导海马 L-LTP（蛋白质合成依赖）；DA-LTP 与 Hebbian-LTP 共享蛋白质合成通路，但触发条件不同
- [[synaptic-tagging-capture]] — 突触标记（E-LTP 的产物）被 DA-驱动的 PRP 合成捕获，是三因素规则实现 L-LTP 的分子接口
- [[three-factor-learning-rule]] — LTP 是三因素规则（Δw = (pre × post) × DA）的正向表达结果；DA 爆发与 Hebbian 激活必须时序配对
- [[fear-conditioning]] — 外侧杏仁核（LA）LTP 是恐惧条件反射的分子底物；与海马 LTP 分子机制完全同构
- [[amygdala]] — LA 突触 LTP 写入恐惧印迹；LTD（消退去增强）同样在 LA 发生
- [[bdnf]] — BDNF 是 L-LTP（晚期 LTP）不可或缺的催化分子；驱动 Arc 局部翻译和 PRP 合成，将 E-LTP 转化为结构性持久增强
- [[arc-arg31]] — Arc 蛋白是 BDNF/ERK 通路驱动的局部翻译产物，是 L-LTP 的执行者之一
- [[astrocyte]] — 星形胶质细胞是 LTP 诱导的隐性必要条件（D-丝氨酸供给控制 NMDA 受体协同位点占用率）
- [[tripartite-synapse]] — LTP 是三方突触框架中神经元-胶质细胞协同可塑性的核心体现
- [[d-serine]] — D-丝氨酸是星形胶质细胞控制 LTP 准入的分子媒介；Ca²⁺ 钳制切断 D-丝氨酸 → LTP 消失（Henneberger 2010）
- [[astrocyte-calcium-signaling]] — 星形胶质细胞 Ca²⁺ 信号是 D-丝氨酸释放的上游门控
- [[synaptic-scaling]] — 突触缩放是 LTP 的互补机制：LTP 用 GluA1 通路写入（快），缩放用 GluA2 通路归一化（慢）；两者时间尺度隔离，共时运行
- [[homeostatic-plasticity]] — 稳态可塑性是 Hebbian 正反馈的必要负反馈，LTP 之所以能维持学习能力，正是因为稳态可塑性持续维护网络工作区间
- [[liquid-liquid-phase-separation]] — LLPS 是 PSD 组织的物理原则；SynGAP 的相变逸散是 LTP 表达的集体物理事件
- [[postsynaptic-density]] — PSD 凝聚体是 LTP 分子机制的物理平台；其相变状态直接决定 AMPAR 的插入效率
- [[pkm-zeta]] — PKMζ（+PKCι/λ）是L-LTP持久性的aPKC功能层；KIBRA-PKMζ寡聚体机制直接回答Q-ltp-lifetime-mechanism；ZIP的记忆破坏非PKMζ特异性

## 未解问题

- Q-ltp-lifetime-mechanism：~~蛋白质周转率约数周，而记忆可持续数十年——什么机制赋予 LTP 如此持久的稳定性？CaMKII 亚基交换？突触结构自我维持？~~ **【部分解答，2026-09-21】** PKMζ+PKCι/λ构成的aPKC功能层通过阻止GluA2-AMPAR内吞主动维持突触强度；KIBRA-PKMζ寡聚体的"感染性磷酸化"机制使激活状态在蛋白周转中代际传递（Hsieh 2026, PMID:41814337；Tsokas 2026, PMID:41889799）。剩余未解：寡聚体机制的体内行为学验证（K-ZAP实验）；不同脑区的aPKC冗余比例；是否存在超越aPKC层的第二备份机制。
- Q-ltp-behavior-correspondence：体内行为记忆的形成是否严格对应于特定突触群的 LTP？能否建立一一映射？印迹细胞（engram cells）研究在何种程度上回答了这一问题？（部分回答：Ryan et al. 2015 显示印迹细胞 AMPA/NMDA 比值高于非印迹细胞，但两者对应关系的精确映射仍有争议）
- Q-ltp-presynaptic-component：除苔藓纤维外，其他类型突触的 LTP 是否也有突触前贡献？谷氨酸释放概率的改变有多大贡献？

## 修订历史

- 2026-09-23 · 修订（rev14）· 基于《记忆的雕塑家》(#153) · 新增树突棘结构可塑性作为 LTP 的形态学对应物：Ca²⁺→CaMKII→Rac1/RhoA→LIMK→cofilin 失活→F-actin 净聚合→棘头膨大；early/late 两阶段结构基础；Rab10/Rab4 时序耦合 AMPAR 流量与棘体积；BTSP 结构对应物为知识空白（新未解问题 Q-spine-btsp-01）；related 新增 dendritic-spine、cofilin-actin-spine；opens_questions 新增 Q-spine-btsp-01、Q-spine-early-late-02；key_sources 新增 PMID:15190253、PMID:41249054、PMID:40986440
- 2026-09-21 · 修订（rev13）· 基于《记忆的分子守夜人》(#151) · 新增"PKMζ与aPKC功能层"段落（PKMζ无调节域持续激活；双KO→L-LTP消失；KIBRA寡聚体感染性磷酸化；ZIP重新解读）；Q-ltp-lifetime-mechanism标记为部分解答；related新增pkm-zeta；key_sources新增6个；source_articles新增#151；连接新增pkm-zeta
- 2026-09-12 · 修订 · 基于《突触的自组装奥秘》(#142) · 新增"LTP 的相变维度"段落（PSD 是 LLPS 凝聚体；SynGAP 集体逸散是 LTP 相变机制；CaMKII 凝聚体作为突触标签）；related 新增 liquid-liquid-phase-separation、postsynaptic-density；key_sources 新增 PMID:27565345、PMID:29976799；dimensions 新增 molecular；source_articles 新增 #142；连接新增两条
- 2026-07-03 · 修订 · 基于《突触稳态》(#69) · 在连接段落新增 synaptic-scaling 和 homeostatic-plasticity；GluA1（LTP）vs GluA2（稳态缩放）分子路径分叉关系明确化；related 新增 synaptic-scaling、homeostatic-plasticity
- 2026-07-02 · 修订 · 基于《大脑的第三方》(#68) · 新增"三方突触条件"段落：星形胶质细胞 D-丝氨酸供给是 LTP 的隐性必要条件（Henneberger 2010 因果证据）；related 新增 astrocyte、tripartite-synapse、d-serine、astrocyte-calcium-signaling；key_sources 新增 PMID:20075918；连接段落新增四条
- 2026-06-28 · 修订 · 基于《BDNF》文章 (#64) · 新增 BDNF/TrkB→Arc→L-LTP 突触固结机制段落；related 新增 bdnf、arc-arg31；key_sources 新增 PMID:16099088、PMID:17942328；source_articles 新增 2026-06-28-bdnf-trk-b-plasticity-memory；悬空引用 [[bdnf]] 已建页
- 2026-06-24 · 修订 · 基于"记忆不混淆的秘密"文章 · 新增：CA3 循环突触 NMDA 受体依赖性 LTP 是模式补全（pattern completion）的分子基础——Nakazawa et al. 2002 (PMID:12040087) 基因因果证据；related 新增 pattern-completion、complementary-learning-systems；source_articles 新增 2026-06-24-hippocampal-ca3-pattern-completion
- 2026-05-26 · 创建 · 基于《NMDA 受体：突触的巧合检测器》一文 · 初始置信度：高
- 2026-05-28 · 修订 · 基于《场所细胞》文章 · 新增 BTSP 作为平行突触增强机制；LTP 与 BTSP 的分工与互补关系；related 增加 btsp, place-cell, hippocampal-circuit
- 2026-05-31 · 修订 · 基于《印迹细胞》文章 · 新增：印迹细胞是 LTP 的细胞层面体现（印迹细胞 AMPA/NMDA 比值高于非印迹）；沉默印迹中 LTP 缺失但拓扑保留；光学 LTP 可恢复 AD 模型中的沉默印迹；related 增加 engram-cells；key_sources 新增 PMID:26023136, 26982728；Q-ltp-behavior-correspondence 补充印迹研究的部分回答
- 2026-06-04 · 修订 · 基于《LTD 文章》· 补充 LTP 的对称对立面（LTD）的完整图景；Ca²⁺ 量决定 LTP vs. LTD 方向（BCM 框架）；related 新增 ltd、calcineurin（PP2B 是 LTP 的拮抗者）；ltp-ltd 悬空引用修正为 ltd
- 2026-06-07 · 修订 · 基于《多巴胺的时间机器》一文 · 新增 DA-LTP 机制（D1/D5→cAMP→PKA→CREB→L-LTP，来自 Huang & Kandel 1995 PNAS，PMC42234）；新增突触标记与捕获（STC）作为 L-LTP 选择性诱导机制；related 新增 dopamine-reward-prediction-error、synaptic-tagging-capture、three-factor-learning-rule；key_sources 新增 PMID:7708662、PMID:9020359
- 2026-06-08 · 修订 · 基于《记忆的分子遗忘》一文（AD与LTP失效） · 扩展"LTP的病理镜像"段落（Aβ五条并行攻击通路；突触沉默的可逆性）；related 新增 alzheimers-disease、amyloid-beta-oligomers；key_sources 新增 PMID:11932745、PMID:17360908、PMID:21543591；dimensions 新增 disease；连接新增 alzheimers-disease 和 amyloid-beta-oligomers
- 2026-05-30 · 修订 · 基于《当杏仁核学会恐惧》一文 · 新增 LA-LTP 作为恐惧条件反射因果底物的段落（Nabavi 2014 光遗传双向因果证明）；LTP 通用性（海马/杏仁核同构机器）认识加深；关键证据表新增 PMID:24896183 行；连接新增 fear-conditioning 和 amygdala；related 新增 fear-conditioning、amygdala；key_sources 新增 PMID:24896183、PMID:11584069

## 来源文章

- [[2026-05-26-nmda-receptor-ltp]]
- [[2026-05-28-place-cells-btsp]]
- [[2026-05-31-engram-cells-optogenetic-proof]]
- [[2026-06-04-ltd-long-term-depression]]
- [[2026-06-07-dopamine-reward-prediction-error]]
- [[2026-05-30-amygdala-fear-memory]]

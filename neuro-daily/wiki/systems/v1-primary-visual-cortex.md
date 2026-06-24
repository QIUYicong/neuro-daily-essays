---
title: 初级视觉皮层（V1）
slug: v1-primary-visual-cortex
domain: systems
type: brain-region
status: established
confidence: high
created: 2026-06-11
updated: 2026-09-14
revision_count: 8
dimensions: [brain-region, systems, microcircuit, cellular]
related: [orientation-selectivity, synaptic-clustering, dendritic-computation, nmda-receptor, ltp, prefrontal-cortex, pv-interneurons, sst-interneurons, working-memory, short-term-synaptic-plasticity, acetylcholine-cortex, gain-control, predictive-coding, precision-weighting, dorsal-attention-network, biased-competition, ventral-visual-stream, cnn-visual-cortex-analogy, divisive-normalization]
prerequisites: [action-potential, synaptic-transmission, nmda-receptor]
opens_questions: [Q-v1-orientation-column-advantage, Q-v1-pinwheel-function, Q-v1-human-organization, Q-ach-ne-02, Q-pc-04, Q-pc-08, Q-pc-09]
source_articles: [2026-06-11-v1-orientation-selectivity, 2026-06-12-neuromodulators-ach-ne, 2026-06-15-predictive-coding, 2026-07-01-dorsal-attention-network-FEF-IPS, 2026-07-14-cnn-visual-cortex-hierarchy, 2026-09-02-divisive-normalization-canonical-computation, 2026-09-14-v1-laminar-prediction-error-evidence]
key_sources: ["PMID:15660108", "PMC3477598", "PMID:22726830", "PMID:23804085", "PMID:27383898", "PMID:20810772", "PMID:18633352", "PMID:22681686", "PMID:10195184", "PMID:23177956", "PMID:24812127", "PMCID:PMC4060707", "PMID:22108672", "PMID:28835531", "PMID:38697110"]
---

# 初级视觉皮层（V1）

> **一句话定义**：初级视觉皮层（V1，Brodmann 17 区）是视觉信息进入大脑皮层的第一站，将外侧膝状体（LGN）的非定向输入转化为具有精确方向、空间频率和眼优势偏好的神经元响应；其核心计算成就是方向选择性——从 LGN 圆对称感受野中从头提取方向信息。

## 当前理解

V1 位于枕叶，接受来自外侧膝状体（LGN）的主要前馈视觉输入（经白质辐射），并向 V2、V3 发送前馈信号，同时接受来自 V2、V4、MT 乃至前额叶皮层的大量反馈投射。在猫和灵长类中，V1 呈现精确的功能拓扑组织：**方向柱**（orientation columns）、**眼优势柱**（ocular dominance columns）和**细胞色素氧化酶斑点**（CO blobs）在皮层表面形成系统性图谱。

### 基本功能特性

V1 神经元相比 LGN 神经元具有更复杂的感受野特性：

- **方向选择性**（orientation selectivity）：约 80% 的 V1 神经元对特定方向的光条/边缘偏好明显，是 LGN 的最显著功能跃升
- **空间频率调谐**：偏好特定宽度的条纹，Gabor 函数很好地描述了 V1 简单细胞的感受野
- **眼优势**：偏好来自特定眼的输入，左右眼输入以约 0.5 mm 间距交替形成优势柱
- **对比度增益控制**：对比度不变性（调谐宽度随对比度不变），由 E/I 平衡和除法规范化共同维持（→ [[divisive-normalization]]）

### 分层结构与输入-输出

V1 遵循皮层 6 层结构：
- **L4**：LGN 前馈输入的主要终止层；包含主要接受 M 通道输入的 L4Cα 和接受 P 通道输入的 L4Cβ（灵长类）
- **L2/3**：处理 L4 输出，是方向选择性进一步精细化的层级；向 V2、MT 发出投射
- **L5/6**：向上丘（superior colliculus）、LGN 和其他皮层区发出投射（皮层-丘脑反馈）

前馈主要沿 L4→L2/3→L5/6 轴流动。

## 简单细胞与复杂细胞

Hubel 和 Wiesel（1962）根据感受野特性将 V1 细胞分为两大类：

| 特性 | 简单细胞 | 复杂细胞 |
|------|---------|---------|
| ON/OFF 子区 | 明确分隔 | 混合/重叠 |
| 相位敏感性 | 是（F1/F0 > 1） | 否（F1/F0 < 1） |
| 空间位置依赖 | 是 | 否 |
| 位置 | 主要 L4 | 主要 L2/3、L5/6 |
| 解释模型 | 前馈 LGN 汇聚 | 简单细胞非线性叠加（能量模型）|

简单细胞的感受野由 Gabor 函数精确描述：高斯包络 × 正弦载波，方向和空间频率由 Gabor 参数决定。

## 方向柱与超柱（猫/灵长类）

在猫和非人灵长类中，相邻方向偏好相似的神经元在皮层表面聚集，形成方向柱。每套覆盖全部方向（0-180°）的皮层区域称为**超柱**（hypercolumn，约 1 mm）。在超柱内部，所有方向柱的汇聚点形成 **pinwheel center**，180° 的方向空间在约 0.1 mm 的面积内完整表征。

Ohki 等（2005，Nature）用双光子钙成像首次在单细胞分辨率下可视化了这一结构，并发现 pinwheel center 的神经元方向选择性与非中心区域同样锐利。

## 小鼠的盐-胡椒型组织

小鼠 V1 完全缺乏方向柱：相邻神经元的方向偏好几乎随机分布（盐-胡椒型组织）。然而，单个神经元的方向选择性同样锐利，OSI 分布与猫高度重叠（Niell & Stryker 2010）。

**意义**：方向柱不是精确方向选择性的必要条件。Hansel & van Vreeswijk（2012）的理论工作证明，通过功能连接偏好的 E/I 平衡网络，盐-胡椒型布局也能实现等效的精确选择性。

## 树突计算的贡献

Wilson 等（2016，Nat Neurosci）在雪貂 V1 发现，方向选择性更锐利的神经元，其树突上同向偏好突触的聚类程度更高（→详见 [[synaptic-clustering]]）。偏好方向刺激时树突 NMDA 棘波热点约为非偏好方向的 2 倍，表明树突局部计算（NMDA 棘波作为"与门"）为方向选择性提供额外增益层，位于峰电位阈值之前。

## 发育与关键期

V1 方向柱的形成具有遗传（活动非依赖）的初始组分，随后通过视觉经验驱动的精细化完成（Espinosa & Stryker 2012）。关键期的开放和关闭与 GABA 能神经元（特别是 PV+ 细胞）的成熟所引起的 E/I 平衡转变高度相关。关键期内的单眼剥夺可永久性地改变眼优势柱分布。

## 物种比较小结

| 物种 | 方向柱 | LGN方向选择性 | V1单细胞OSI |
|------|--------|--------------|------------|
| 猫   | 有（系统性方向图）| 极弱 | 锐利 |
| 猕猴 | 有（系统性方向图）| 弱 | 锐利 |
| 雪貂 | 有（系统性方向图）| 弱 | 锐利 |
| 小鼠 | 无（盐-胡椒型）  | 中等（独立于皮层反馈，PMID:23804085）| 锐利 |

## 神经调质对 V1 的调制

V1 的方向选择性和感觉增益受到来自基底前脑胆碱能系统（ACh）的显著调制：

**乙酰胆碱（ACh）通过肌碱受体放大注意调制**（Herrero et al., 2008, Nature, PMID:18633352）：
- 在猕猴执行空间注意任务时，向 V1 电泳注射东莨菪碱（肌碱受体拮抗剂）显著降低了注意诱导的神经元增益提升（P<0.001）
- 注射美加明（烟碱受体拮抗剂）无效（P=0.465）
- 结论：**V1 中的注意性增益调制由 M1 肌碱受体介导**
- 机制：ACh 改变 V1 神经元的生物物理状态，使之更能被来自 PFC/顶叶的特异性谷氨酸能反馈信号所增强
- V1 中烟碱受体主要位于丘脑皮质（L4）突触前，增强底-上感觉输入，但不直接参与注意调制

**注意对 V1 的效果**（综合多项研究）：
- 注意力集中于某位置 → 该位置感受野内神经元响应增强约 20-50%
- 响应形式：倾向于"响应增益"（乘法性缩放），而非"对比度增益"（阈值移动）
- 对 OSI（方向选择指数）也可能有轻度改善效应

## 开放问题

- **Q-v1-orientation-column-advantage**：方向柱是否提供方向计算之外的计算/布线/速度优势？
- **Q-v1-pinwheel-function**：pinwheel center 在视觉信息处理中是否有特殊的功能角色？
- **Q-v1-human-organization**：人类 V1 的方向组织与猫/猴有何差异？高分辨率功能成像技术能否直接可视化人类 V1 方向柱？
- **Q-ach-ne-02**：烟碱/肌碱受体在人类 V1 的功能分工是否与猕猴一致？

## 预测编码视角下的 V1（2026-06-15 补充）

V1 不只是被动的"图像接收站"——它是大脑皮层层级预测机器中的**误差检测节点**。

**感觉运动失配响应（Keller et al. 2012, PMID:22681686）**：清醒小鼠在虚拟现实中奔跑时，V1 L2/3 神经元对感觉运动失配（运动持续但视觉流动停止）产生强烈激活，而在正常耦合状态下响应被抑制——这是预测误差响应的直接证据：运动皮层发送本体感觉预测，V1 比较预测与实际视觉输入，编码失配误差。

**环绕抑制和末端停止的新解释（Rao & Ballard 1999, PMID:10195184）**：这两种非经典感受野效应传统上归因于侧抑制，但预测编码框架提供另一解释——均匀背景刺激被高级区域预测覆盖（"解释掉"），产生较小误差；孤立刺激或不符合预测的边缘端点产生较大误差（更强响应）。**除法规范化框架**同样解释环绕抑制：感受野外神经元加入抑制性池，增大分母而不改变分子（→ [[divisive-normalization]]），三种解释（侧抑制/预测编码/规范化）不互斥，区分需精确层特异性操控实验。

**分层振荡分工**：根据 Bastos et al. 2012，V1 的前馈输出（L2/3→V2 L4）以 γ 振荡为主（传递误差），V1 接受来自 V2/V4 的反馈（传递预测）以 α/β 振荡为主。这将 V1 的经典"前馈视觉处理"角色扩展为双向误差-预测交换的参与者。

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| V1 L2/3 编码感觉运动预测误差（失配响应） | 清醒小鼠 VR + 双光子钙成像 | PMID:22681686 | 高 |
| V1 接受来自高级视觉区的预测反馈（α/β 主导） | 灵长类 MEG/LFP 多脑区记录 | PMID:23177956 | 高 |
| 环绕抑制/末端停止可由预测编码模型复现 | 计算模型 + 自然图像训练 | PMID:10195184 | 中（模型证据，非直接区分实验）|
| **人类 V1 L5/6（深层）编码预期表征，L2/3（浅层）专门编码预测误差（非预期刺激时激活）** | 7T fMRI 层级多变量解码；75%/25% 概率 Gabor 朝向；活体人脑 | PMID:38697110（Thomas et al. 2024）| **中-高**（层级 fMRI 直接验证；神经适应无法完全排除）|

## CNN 第一层的 V1 类比（2026-07-14 补充）

Yamins et al. 2014（PMID:24812127，PMCID:PMC4060707）的目标驱动建模框架显示：**在层次卷积神经网络中，第一层卷积核通过自然图像优化后自发地学习出 Gabor 型滤波器**——与 V1 简单细胞的感受野（方向选择性、空间频率调谐）在形式上几乎完全相同。

这种收敛不是偶然的：V1 和 CNN 第一层都在解决同一个问题——从局部像素中提取边缘和方向信息，而 Gabor 函数是这个问题在自然图像统计约束下的最优解（稀疏编码的角度也支持此结论）。

V1 在腹侧流层级（V1→V4→IT）中对应 CNN 的早期层，而非整个视觉皮层。CNN 中间层更好地预测 V4，CNN 顶层更好地预测 IT——这种层级对应是目标驱动框架最强的直接证据。

**V1 ≠ CNN 的地方**：V1 广泛接受来自 V2、V4 乃至前额叶的反馈投射，因此其响应不只是前馈特征检测的结果。感觉运动失配响应（Keller 2012）和环绕抑制的预测编码解释都说明 V1 是预测-误差网络中的一个节点，而非单纯的滤波器组。

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| CNN 第一层卷积核自发学习出 Gabor 型滤波器 | 卷积核可视化 + V1 感受野拟合 | Yamins & DiCarlo 2016 综述（PMID:26906502）| 高 |
| CNN 层级与 V1→V4→IT 层级系统对应（分层预测力测试）| 2000+ 网络 × 多电极 V4/IT 记录 | Yamins et al. 2014（PMID:24812127，PMCID:PMC4060707）| 高 |

## 修订历史

- 2026-06-11 · 创建 · 基于《V1初级视觉皮层的方向选择性》一文 · 初始置信度：高
- 2026-06-12 · 修订 · 基于《注意的化学语言》一文 · 新增"神经调质对 V1 的调制"小节（ACh/肌碱受体介导注意调制，Herrero 2008）；related 新增 acetylcholine-cortex, gain-control；opens_questions 新增 Q-ach-ne-02；key_sources 新增 PMID:18633352
- 2026-06-15 · 修订 · 基于《当大脑主动预测而非被动接收》一文 · 新增"预测编码视角下的 V1"小节；新增感觉运动失配实验（Keller 2012）和环绕抑制预测编码解释；related 新增 predictive-coding, precision-weighting；opens_questions 新增 Q-pc-04；key_sources 新增 PMID:22681686, PMID:10195184, PMID:23177956
- 2026-07-01 · 修订 · 基于《空间注意的神经回路》一文 · 新增 V4→V1 皮层反馈作为注意调制的必要通道（Debes & Dragoi 2023，PMID:36730414）；related 新增 dorsal-attention-network, biased-competition；key_sources 新增 PMID:36730414
- 2026-07-14 · 修订 · 基于《镜中影像：CNN与灵长类视觉皮层层级对应》一文 · 新增"CNN第一层的V1类比"小节；related 新增 ventral-visual-stream, cnn-visual-cortex-analogy；key_sources 新增 PMID:24812127, PMCID:PMC4060707
- 2026-08-29 · 修订 · 基于《腹侧视觉流的"解缠"之旅》(#127) · 腹侧流完整 wiki 页（ventral-visual-stream）已创建，填补此前 related 中的悬空引用；V1 在腹侧流层级中的位置（第一站，方向选择性→向 V2 传递基础特征）进一步明确
- 2026-09-02 · 修订 rev7 · 基于《除法规范化：大脑皮层的规范计算》（#132）· 在基本功能特性中补充规范化解释对比度增益控制；在预测编码小节补充规范化框架对环绕抑制的解释（三种框架并列）；related 新增 divisive-normalization；source_articles 追加 2026-09-02；key_sources 新增 PMID:22108672、PMID:28835531
- 2026-09-14 · 修订 rev8 · 基于《谁说了什么》文章 #144 · 在预测编码证据表新增 Thomas et al. 2024（PMID:38697110）——7T fMRI 层级解码直接验证 V1 L5/6=预期、L2/3=预测误差；opens_questions 新增 Q-pc-08、Q-pc-09；key_sources 新增 PMID:38697110；source_articles 追加 2026-09-14

## 来源文章

- [[2026-06-11-v1-orientation-selectivity]]
- [[2026-06-12-neuromodulators-ach-ne]]
- [[2026-06-15-predictive-coding]]
- [[2026-07-01-dorsal-attention-network-FEF-IPS]]
- [[2026-07-14-cnn-visual-cortex-hierarchy]]
- [[2026-08-29-ventral-visual-stream-object-recognition]]
- [[2026-09-02-divisive-normalization-canonical-computation]]
- [[2026-09-14-v1-laminar-prediction-error-evidence]]

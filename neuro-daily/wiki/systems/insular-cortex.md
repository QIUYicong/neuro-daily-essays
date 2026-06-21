---
title: 岛叶皮层
slug: insular-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-08-22
updated: 2026-08-22
revision_count: 1
dimensions: [molecular, cellular, brain-region, whole-brain-network, cognition]
related: [interoception, anterior-cingulate-cortex, orbitofrontal-cortex, amygdala, prefrontal-cortex, nucleus-accumbens, thalamus, basal-ganglia, active-inference, precision-weighting]
prerequisites: [thalamus, somatosensory-cortex]
opens_questions: [Q-ins-01, Q-ins-02, Q-ins-03, Q-ins-04]
source_articles: [2026-08-22-insular-cortex-interoception-bodily-self]
key_sources: ["PMID:12154366", "PMID:19096369", "PMID:26016744", "PMID:23749500", "PMID:30985277", "PMID:35774133", "PMID:28314446", "PMID:41836516"]
---

# 岛叶皮层 (Insular Cortex / Insula)

> **一句话定义**：岛叶皮层是隐藏于外侧裂深处的多层级内感觉处理中枢，沿后→中→前轴将身体的生理状态信号逐步整合为主观感受，并通过与前额叶、杏仁核和纹状体的密集投射将身体状态嵌入情绪、显著性检测与决策。

## 当前理解

我们现在认为，岛叶皮层不是单一功能区域，而是一条功能梯度轴：后岛（颗粒型皮层）是初级内感觉皮层，接收来自丘脑 VMpo 核的专属内感觉传入，形成身体热痛觉、内脏张力和心脏状态的精细躯体地图；中岛（过渡型无颗粒层）计算身体预期状态与实际状态之间的预测误差；前岛（无颗粒型皮层）整合躯体信号、情绪背景和行动选项，生成被我们称为"感受"的主观体验，并通过密集的前额叶连接将身体状态嵌入认知决策。

前岛极（anterior pole, Region IV）是整个系统最高阶的节点：电刺激几乎沉默（无感觉运动反应），但在显著性检测和行为模式切换时强烈激活，且其对下级岛区的影响强于逆向影响，实现顶端向下的非对称控制。

岛叶与前扣带皮层（ACC）共同构成大脑的"**显著性网络**"（Salience Network），负责检测生物学相关事件（来自内部或外部），并动态切换默认模式网络和执行控制网络之间的激活。

## 关键机制

### 解剖结构与组织

岛叶藏于外侧裂（Sylvian fissure）深处，被额叶岛盖、颞叶岛盖和顶叶岛盖覆盖，不拨开外侧皮层则不可见。根据细胞构筑学，从后到前分三型：
- **后颗粒岛（granular insula, gINS）**：含清晰 Layer IV，类似初级感觉皮层
- **中无颗粒岛（dysgranular insula, dINS）**：Layer IV 消退，处于过渡态
- **前无颗粒岛（agranular insula, aINS）**：无 Layer IV，类似运动皮层和眶额皮层

### 内感觉通路

专属内感觉通路（Craig 2002, PMID:12154366）：
1. 脊髓背角 **I 层神经元（lamina I）** → 对侧脑干（孤束核 NTS，臂旁核 PBN）
2. **丘脑 VMpo 核**（灵长类特有核团，与一般体感 VPM→S1 通路相互独立）
3. **后岛叶皮层**（初级内感觉皮层）

这一通路与外感觉体感通路（皮肤感受器→VPM→S1）解剖上独立，传递内脏、痛觉、温度、心率、呼吸等生理参数。

### 后→中→前梯度处理（IMAC 模型，Fermin et al. 2022, PMID:35774133）

| 层级 | 区域 | 计算功能 | 调制 |
|------|------|---------|------|
| 一阶 | 后颗粒岛 | 基于内脏的惯性预测 + 一阶预测误差 | — |
| 二阶 | 中无颗粒岛 | 基于行为背景的模型预测 | 多巴胺（精确度权重） |
| 三阶 | 前无颗粒岛 | 将内脏反应映射到新颖行动 | 乙酰胆碱（可塑性） |
| 顶端 | 前岛极 | 网络状态整合，顶端控制 | PFC 双向连接 |

### 前岛（AIC）的功能拓扑

- **背侧 aINS**：外感觉显著性监测、集中注意；与背侧注意网络（FEF、IPS）选择性连接
- **腹侧 aINS**：焦虑性反刍和情绪整合；与下膝 ACC（subgenual ACC）和边缘控制网络相连

### von Economo 神经元（VENs）

前岛 Layer V 含有大型双极梭形 VENs，体积为邻近锥体神经元的 4.6 倍（Gu et al. 2013, PMID:23749500）。仅见于人类、大猿、大象和部分鲸类。功能假说：长轴突 + 高传导速度 → 实现前岛与远端网络节点（PFC, ACC, NAc）之间的毫秒级远程同步，支持"意识广播"。VENs 损伤/减少与失感情症（alexithymia）高度相关。

### 预测编码框架（EPIC 模型，Barrett & Simmons 2015, PMID:26016744）

大脑主动预测身体状态而非被动读取：
- **下行预测**：aINS → dINS → gINS（无颗粒皮层 → 颗粒皮层），发出预期的内脏状态
- **上行预测误差**：gINS → dINS → aINS，传递"实际-预期"的差值
- **主动推断**：当预测误差高且不可解释时，aINS 通过自主神经系统主动改变身体状态以减小误差

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 后岛是初级内感觉皮层，接收 VMpo 专属传入 | 解剖追踪 + SEEG 颅内刺激体感拓扑（手区最大） | PMID:12154366; PMID:41836516 | 高 |
| AIC 对内感觉注意必要（AIC 病变→BDT 准确性下降） | 6 名 AIC 局灶性病变患者，呼吸觉察 d' 显著降低；视觉任务无差异 | PMID:30985277 | 高 |
| AIC 一致性激活于跨三类情绪（疼痛/负性/正性） | 47 项 fMRI 研究元分析（2029 个激活焦点）；AIC 显著，ACC 不显著 | PMID:23749500 | 高 |
| VENs 损伤与 alexithymia 相关 | 组织学（VEN 减少）与临床 AIC 激活降低的横断面关联 | PMID:23749500 | 中-高 |
| 前岛极电刺激沉默，显著性任务激活，对下级岛区非对称控制 | SEEG 颅内刺激 n=87；CCEPs 方向不对称分析 | PMID:41836516（预印本）| 新兴 |
| 后岛→前岛预测编码层级与皮层层级解剖一致 | 无颗粒（前岛）→颗粒（后岛）连接方向与 Friston 主动推断模型吻合 | PMID:26016744; PMID:35774133 | 中 |
| 岛叶灰质减少 / 功能连接异常见于 MDD、精神分裂症、成瘾 | 多中心结构 MRI、静息态 fMRI 综述 | PMID:28314446 | 中-高 |

## 连接

- [[interoception]] — 岛叶是内感觉的核心皮层基础
- [[anterior-cingulate-cortex]] — 共同构成显著性网络（Salience Network）；ACC 参与认知控制，岛叶提供内脏状态信号
- [[orbitofrontal-cortex]] — 岛叶通过躯体标记向 OFC/vmPFC 提供身体状态输入，影响价值更新
- [[amygdala]] — 双向情绪调制：杏仁核 → 岛叶（情绪激活触发内脏反应）；岛叶 → 杏仁核（内脏状态修饰情绪评价）
- [[prefrontal-cortex]] — 前岛极与 dlPFC 和 vmPFC 的密集连接；PFC 调制内感觉的认知解读
- [[nucleus-accumbens]] — 岛叶内脏状态信号门控 NAc 的奖赏处理（情感背景调制 wanting/liking）
- [[thalamus]] — VMpo 核是内感觉传入岛叶的中继站
- [[active-inference]] — 岛叶的主动预测-误差框架是 Friston 主动推断在内感觉领域的具体实现
- [[precision-weighting]] — 多巴胺和乙酰胆碱调制岛叶不同层级内感觉预测的精确度权重

## 未解问题

- Q-ins-01（高优先级）：Craig 映射框架 vs. Barrett 预测框架——能否通过 ECoG 时间序列解码区分方向（后→前先到 vs. 前→后预测先行）？
- Q-ins-02（高优先级）：前岛极电刺激沉默的机制——是网络状态依赖性计算还是频率范围不匹配？
- Q-ins-03（中优先级）：VENs 因果功能——大型灵长类 VEN 样细胞光遗传操控是否可行？
- Q-ins-04（中优先级）：不同决策类型（风险/道德/社会）是否使用统一内感觉-情绪编码还是招募不同岛叶子区域？

## 修订历史

- 2026-08-22 · 创建 · 基于《岛叶皮层：身体的感知地图如何生成主观感受并导航决策》· 初始置信度：高（8 篇来源，6 篇开放全文）

## 来源文章

- [[2026-08-22-insular-cortex-interoception-bodily-self]]

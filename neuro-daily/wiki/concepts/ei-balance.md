---
title: 兴奋-抑制平衡
slug: ei-balance
domain: concepts
type: concept
status: mainstream
confidence: medium
created: 2026-07-04
updated: 2026-06-04
revision_count: 2
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, cognition, disease]
related: [pv-interneurons, sst-interneurons, vip-interneurons, gamma-oscillations, homeostatic-plasticity, synaptic-scaling, synaptic-pruning, perineuronal-nets, working-memory, competition-selection-principle]
prerequisites: [synaptic-transmission, action-potential, pv-interneurons]
opens_questions: [Q-ei-balance-01, Q-ei-balance-02, Q-ei-balance-03]
source_articles: [2026-07-04-ei-balance-pv-interneuron, 2026-06-04-asd-ei-imbalance-circuit-mechanism]
key_sources: ["PMID:31089192", "PMID:37143468", "PMID:36598942", "PMID:34887320", "PMID:36008036", "PMID:14606691", "PMID:38796123"]
---

# 兴奋-抑制平衡 (Excitation-Inhibition Balance, E/I Balance)

> **一句话定义**：皮层回路中兴奋性（谷氨酸能）与抑制性（GABA 能）神经元活动维持的动态稳定状态，本质是神经回路的信噪比控制机制；由 PV+、SST+、VIP+ 三类抑制性中间神经元协同维持，失调则引发从癫痫（过度兴奋）到认知障碍（信噪比下降）的一系列病理状态。

## 当前理解

我们现在认为，E/I 平衡不是一个简单的化学等式，而是**多维度的、分布式自组织的回路属性**。Sohal & Rubenstein（2019，PMID:31089192）明确指出：E/I 平衡指的是特定回路中的全局活动稳定水平——不同抑制性中间神经元亚型针对不同靶点提供抑制，任何单一亚型的损伤都会产生不同的回路失衡模式。

**信噪比框架**（Rubenstein & Merzenich 2003，更新版 Sohal & Rubenstein 2019）：E/I 平衡的核心功能是放大激活神经集群的信号（兴奋）并压制背景集群的噪声（抑制），实现皮层信息的稀疏化编码。E/I 失衡即信噪比下降：不是感知消失，而是无法区分重要信号与背景噪声。

**E/I 平衡的时间层次**（从快到慢）：
- 毫秒级：PV+ 中间神经元的快速反馈抑制（回路即时稳定）
- 秒-分钟级：突触可塑性的短时调整
- 小时-天级：突触稳态缩放（synaptic scaling）慢速补偿
- 发育级：围神经元网（PNNs）沉积固化关键期经验

**计算模型证据**（Lam et al. 2022，PMID:34887320）：升高的 E/I 比导致冲动决策（过分权重早期证据）；降低的 E/I 比导致迟疑行为（证据整合弱化）。两个方向的失衡都损害认知，支持"最优 E/I 比"的倒 U 形关系。

## 关键机制

### 分子层面
- **GABA-A 受体**：α1 亚型（PV+ 细胞突触后）介导快速 Cl⁻ 内流，是抑制性突触传递的主力
- **AMPA 受体**：密度调节通过受体侧向扩散实现；PNNs 限制这种扩散来固化 E/I 状态
- **Kv3.1/3.2 钾通道**：PV+ 细胞快速复极的关键，由 OTX2-PNN 信号通路调控

### 细胞/回路层面
E/I 平衡由三类中间神经元分工维持：

| 类型 | 抑制靶点 | 功能 | 时间尺度 |
|------|---------|------|---------|
| PV+（篮细胞）| 胞体/近端树突 | 控制输出增益，产生 γ 振荡 | 毫秒 |
| SST+（马氏节苔）| 远端树突 | 控制输入权重 | 毫秒-百毫秒 |
| VIP+ | 抑制 SST+/PV+ | 去抑制，觉醒/注意力调节 | 百毫秒 |

E→I→E 的反馈回路：锥体细胞激活 PV+，PV+ 反馈抑制锥体细胞，这是皮层稳定性的基础。

### 发育层面
- PV+ 中间神经元 GABA 能抑制成熟 → 关键期开放
- 围神经元网（PNNs）沉积 → 固化回路状态，关闭关键期（见 [[perineuronal-nets]]）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| E/I 平衡是多维度的，不同中间神经元亚型不可替代 | CNTNAP2 KO 选择性损伤 PV（非 SST）；光遗传 PV 激活恢复社交行为 | PMID:31089192 | 高 |
| 多种 ASD 基因通过不同分子机制均减少 GABA 能抑制 | KO 小鼠 mIPSC 降低；苯二氮䓬类低剂量改善行为（Scn1a、Arid1b 模型）| PMID:31089192 | 高（小鼠）|
| 升高 E/I 比→冲动决策；降低→迟疑行为 | 皮层回路计算模型（NMDA 受体扰动）| PMID:34887320 | 中（计算模型） |
| 精神分裂症：过度剪枝 → E/I 失调 → 多巴胺脱抑制 | 影像学突触密度 + PV GAD67 下调 + 纹状体多巴胺过活跃 | PMID:36008036 | 中-高（相关性） |
| 非特异性抑制增强有时恶化 ASD 行为；需靶向特定细胞类型 | VPA 暴露模型 mPFC 非特异性抑制 → 社交行为恶化 | PMID:31089192 | 高（临床启示重要）|

## 连接

- [[pv-interneurons]] — E/I 平衡的主要实时执行者（毫秒反馈抑制）
- [[sst-interneurons]] — 远端树突输入权重控制，E/I 平衡的第二执行者
- [[vip-interneurons]] — 去抑制回路，调节 E/I 平衡的觉醒/注意力维度
- [[gamma-oscillations]] — E/I 平衡状态的动态振荡读出（40 Hz 伽马频率）
- [[homeostatic-plasticity]] — E/I 平衡的慢速（小时-天）稳态补偿机制
- [[synaptic-scaling]] — 稳态可塑性的突触形式，慢速调整 E/I
- [[perineuronal-nets]] — PV+ 细胞周围的细胞外矩阵"刹车"，发育期固化 E/I 状态
- [[synaptic-pruning]] — 发育期突触剪枝影响 E/I 平衡（精神分裂症过度剪枝的病理路径）
- [[competition-selection-principle]] — 侧向抑制是竞争性选择的回路机制
- [[asd]] — ASD 是 E/I 失衡的主要疾病应用场景；多条遗传路径（SHANK3/FMRP/SCN1A/MeCP2）汇向 E/I 升高

## 未解问题

- Q-ei-balance-01（高优先级）：如何精准非侵入性测量人类特定皮层区域的 E/I 状态？MRS 测量 GABA/谷氨酸只是代理指标，无法区分中间神经元亚型
- Q-ei-balance-02（高优先级）：E/I 失衡在 ASD 中是兴奋过多还是抑制过少？有些 ASD 个体皮层活动减少，与标准模型矛盾
- Q-ei-balance-03（中优先级）：VIP+ → SST+/PV+ 去抑制回路在调制感知状态时的精确时序和幅度

## 修订历史

- 2026-07-04 · 创建 · 基于《信号与噪声之间：皮层 E/I 平衡的回路逻辑》一文 · 初始置信度：中（框架成熟，但异质性和精确测量方法仍有争议）
- 2026-06-04 · rev2 · 基于《当发育的精密时钟出错》(#73) · 新增 ASD 应用：Rubenstein & Merzenich 2003 原始假说 + MRS 元分析 GABA 减少证据（Thomson 2024）；添加 [[asd]] 连接

## 来源文章

- [[2026-07-04-ei-balance-pv-interneuron]]

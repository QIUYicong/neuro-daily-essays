---
title: 杏仁核
slug: amygdala
domain: systems
type: region
status: established
confidence: high
created: 2026-05-30
updated: 2026-06-16
revision_count: 6
dimensions: [cellular, microcircuit, brain-region, behavior, cognition, disease]
related: [fear-conditioning, fear-extinction, ltp, hippocampal-circuit, dopamine-reward-prediction-error, norepinephrine-locus-coeruleus, basal-ganglia, hpa-axis, glucocorticoid-hippocampus-plasticity, olfactory-system, bla-valence-circuits, incentive-salience, subjective-value-encoding, oxytocin-system]
prerequisites: [ltp, synaptic-transmission, nmda-receptor]
opens_questions: [Q-fear-human-amygdala-specificity, Q-fear-low-road-function, Q-stress-01, Q-OT-04]
source_articles: [2026-05-30-amygdala-fear-memory, 2026-07-09-stress-glucocorticoid-hippocampus-hpa-axis, 2026-07-17-olfactory-system-molecular-to-memory, 2026-07-30-bla-reward-fear-circuits, 2026-07-31-pfc-amygdala-emotion-regulation, 2026-06-16-oxytocin-social-bonding-neural-circuits]
key_sources: ["PMID:24908482", "PMID:22129456", "PMID:20393190", "PMID:26286651", "PMID:12042880", "PMID:19804753", "PMID:25925480", "PMID:27041499", "PMID:38396258", "PMID:33589833", "PMID:37248645"]
---

# 杏仁核 (Amygdala)

> **一句话定义**：颞叶深部由多个亚核组成的复合核团，是大脑情绪记忆（尤其是恐惧与奖励）的写入与表达中枢，通过基底外侧杏仁核（BLA）中两类功能对立的神经元群分别编码正向与负向情绪价值，经由分叉的投射通道（BLA→NAc vs BLA→CeA）路由至决策系统，通过中央核输出防御反应，并与前额叶、海马、OFC构成情境依赖的情绪调控网络。

## 当前理解

我们现在认为，杏仁核不是一个统一的"情绪中枢"，而是由功能截然不同的亚结构组成的微回路复合体。其中基底外侧杏仁核复合体（BLA，包括外侧核LA和基底核BA）是感觉信息的输入与可塑性发生地，中央核（CeA）是防御行为的输出引擎，而散布其间的插入细胞（ITC）是恐惧与消退之间的可塑性闸门。

恐惧记忆的写入本质是LA突触的LTP——与海马LTP使用相同的NMDA→CaMKII→AMPA插入分子机器。恐惧消退不是记忆抹除，而是IL皮层→腹侧ITC→CeM的新抑制回路对原始恐惧回路的竞争性压制。两套记忆痕迹在杏仁核及其前额叶-海马连接网络中并行共存，情境信号决定哪套痕迹占主导。

**杏仁核的情绪价值双极编码**：BLA不仅写入恐惧记忆，还是大脑**情绪价值的双极编码器**。BLA中存在功能对立的两类神经元群：后部的Ppp1r1b+神经元（奖励偏向，优先投射伏隔核NAc）和前部的Rspo2+神经元（厌恶偏向，优先投射CeA）。这两类神经元相互抑制，形成二元竞争机制。奖励学习使BLA→NAc突触增强、BLA→CeM突触减弱；恐惧学习做完全相反的变化——相反方向的突触可塑性规则将情绪极性"分流"到不同下游结构（Namburi et al. 2015，Beyeler et al. 2016）。

**杏仁核与海马在应激下的方向性分离**：慢性应激或高皮质醇状态下，杏仁核（BLA）和海马呈现**结构和功能的反向变化**——这是同一组应激激素（GC + NE）在不同靶区产生截然相反效果的经典案例。慢性应激（21 天）使 BLA 顶端/基底树突分支均增多（树突密度↑、树突棘↑），同时增强 BLA 对威胁刺激的电生理响应；而同一应激方案导致 CA3 顶端树突退缩、海马 LTP 受损（Kim & Diamond 2002，PMID:12042880；Kim et al. 2015，PMID:26286651）。行为后果：杏仁核依赖的情绪/恐惧记忆强化，海马依赖的情景/空间记忆削弱。这一双向分离被认为是应激适应的短期逻辑（当前威胁优先）与慢性暴露后病理化的共同来源。

## 关键机制

### 亚核架构
- **外侧核（LA）**：首要感觉输入站；CS（音调）从听觉丘脑/皮层、US（电击）从躯体感觉丘脑汇聚于此；是LTP发生的核心位点；约80%为兴奋性锥体神经元，~20%为GABAergic中间神经元；条件反射后约20%神经元形成稀疏CS响应（恐惧印迹）
- **基底核（BA）**：包含恐惧神经元（投射PL皮层，条件反射后CS+）和消退神经元（投射IL皮层，消退后CS+）两个功能截然不同的群体；接收海马情景信息，决定哪群神经元主导
- **中央核（CeA）**：外侧部（CeL）含PKCδ+（关闭细胞）和SOM+（开启细胞），形成局部去抑制回路；内侧部（CeM）是主要输出，投射至PAG（冻结）、下丘脑（自主神经）、BNST（持续焦虑）

### 插入细胞（ITC）
- 散布于BLA与CeA之间的GABAergic神经元群
- **背侧ITC（ICMMD）**：LA→ICMMD→抑制ICMMV→CeM去抑制 → 恐惧表达
- **腹侧ITC（ICMMV）**：BLA+IL皮层→ICMMV→直接抑制CeM → 消退表达
- ITC上富含µ-阿片受体，阿片系统可调节消退
- 选择性损毁ITC（dermorphin-saporin，靶向µOR+细胞，约减少34%）→ 恐惧获得正常，消退表达严重受损；存活ITC数量与消退测试冻结率呈强负相关（**r=−0.67，p<0.01**，Likhtik et al. 2008，PMID:18615014）
- 腹侧ITC（ICMMV）同时接收 IL 皮层和 BLA 的汇合信号；IL→BLA 直接投射在消退后也发生内在兴奋性↑（Bloodgood et al. 2018，PMID:29507292），两条通路协同增强消退神经元回路

### 恐惧表达的完整输出
CeM → PAG → 冻结行为；CeM → 下丘脑 → 自主神经激活（心率↑）；CeM → 下丘脑室旁核（PVN）→ HPA 轴 → CRH → ACTH → 皮质醇/皮质酮；CeM → BNST → 持续焦虑/广泛性焦虑

**慢性应激下的 BLA 可塑性（与海马反向）**：
- 树突总长度和分支数增加（顶端 + 基底均受影响）
- 树突棘密度↑（不同于 CA3 的退缩，BLA 是增生）
- BLA 神经元对应激刺激的 c-Fos 表达↑（激活增强）
- 机制：NE（β-AR）激活在 BLA 增强 LTP 和树突可塑性；GC 则在 BLA 与海马产生相反的受体动力学效应（BLA 的 GR 下调机制与海马 GR 的反馈调控路径不同）

### BLA奖励-恐惧双通道（Reward-Fear Dual Channels）

BLA中存在两类遗传、突触、投射三层面同步分化的神经元群，实现情绪价值的正/负极性分流：

**遗传身份（先天预设）**
- **Ppp1r1b+神经元**（后部BLA）：奖励偏向，编码状态价值（state value），倾向投射NAc
- **Rspo2+神经元**（前部BLA）：厌恶/恐惧偏向，倾向投射CeA
- 两类神经元相互抑制 → 促进二元价值判断（O'Neill, Gore & Salzman 2018，PMID:29525574）

**突触可塑性的对立规则（学习写入）**
- 两条投射通道在条件化后发生**方向完全相反**的AMPAR/NMDAR比值变化（Namburi et al. 2015，PMID:25925480）：
  - 奖励条件化：NAc投射↑，CeM投射↓
  - 恐惧条件化：CeM投射↑，NAc投射↓
- 两者共享NMDA→CaMKII→AMPA插入/移除分子机器（Janak & Tye 2015，PMID:25592533）

**投射路由（结构分流）**
- BLA→NAc神经元：**77%**被奖励预测线索激活（vs整体BLA的51%）
- BLA→CeA神经元：**100%**被厌恶预测线索激活（vs整体BLA的49%）
- 情绪极性由**投射靶点**决定，而非神经元固有属性（Beyeler et al. 2016，PMID:27041499）

**多巴胺的特异性触发角色**
- VTA DA→BLA投射专门驱动结果特异性线索-奖励记忆编码（非泛化奖励信号）
- DA→BLA是奖励特异性记忆写入BLA的"权限授权"触发器（Sias et al. 2024，PMID:38396258）

**行为输出的因果验证**
- 光激活BLA→NAc → 条件性位置偏好（正强化，趋近）
- 光激活BLA→CeM → 实时位置厌恶（负价值，回避）

**注意**：上述光遗传因果证据几乎全部来自小鼠，人类BLA细胞层面的直接等价证据缺失。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| LA突触LTP是恐惧记忆因果底物 | 光遗传LTP→恐惧；LTD→消除恐惧；再LTP→恢复恐惧 | PMID:24896183 | 高 |
| 条件反射后约20% LA神经元发展CS响应（稀疏代码） | 多通道电极记录+行为范式 | PMID:24908482 (PMC4103014) | 高 |
| ITC神经元是消退表达的必要条件 | 选择性免疫毒素损毁ITC→消退表达缺陷 | PMID:18615014 | 高 |
| BA中恐惧/消退神经元双群切换 | 多单元记录+逆行标记 | PMID:18615015 | 高 |
| vmPFC/IL激活强度预测消退回忆质量 | 人类fMRI多研究汇总 | PMID:22129456 (PMC4942586) | 中-高 |
| 奖励/恐惧条件化使BLA→NAc和BLA→CeM突触发生完全相反的AMPAR/NMDAR变化 | 逆行光遗传标记+离体膜片钳 | Namburi et al. 2015（PMID:25925480） | 高（小鼠） |
| BLA→NAc神经元77%偏向奖励线索；BLA→CeA神经元100%偏向厌恶线索 | 光遗传光标记+在体电生理 | Beyeler et al. 2016（PMID:27041499） | 高（小鼠） |
| VTA DA→BLA专门驱动结果特异性奖励记忆编码 | 回路特异性条件光遗传+行为解离 | Sias et al. 2024（PMID:38396258） | 高（小鼠） |

## 连接

- [[ltp]] — LA突触LTP是恐惧记忆写入的分子机器
- [[fear-conditioning]] — 外侧核LTP的行为诱导范式
- [[fear-extinction]] — 消退作为竞争性抑制记忆，依赖ITC和IL皮层
- [[hippocampal-circuit]] — 海马提供情景信号给BA，决定恐惧/消退哪套记忆被调取
- [[norepinephrine-locus-coeruleus]] — 蓝斑NE投射通过β-肾上腺素受体增强杏仁核LTP和恐惧记忆巩固
- [[dopamine-reward-prediction-error]] — VTA DA投射到BLA专门驱动结果特异性奖励记忆写入（Sias 2024）
- [[engram-cells]] — LA恐惧印迹细胞（~20%稀疏）与海马场所细胞印迹遵循相同的竞争选择逻辑
- [[hpa-axis]] — CeM → PVN 是 HPA 轴激活的上行通路；BLA 通过 BNST → PVN 提供威胁信号驱动 CRH 释放
- [[glucocorticoid-hippocampus-plasticity]] — 慢性 GC 同时增强 BLA 可塑性（树突增生）和削弱海马 LTP（树突退缩）——方向性分离
- [[olfactory-system]] — 嗅球→皮层杏仁核（cortical amygdala）是唯一不经过丘脑的感觉到杏仁核的直接通路，解释了气味触发情绪记忆的神经基础（"Proustian 效应"）
- [[bla-valence-circuits]] — BLA双通道（奖励/恐惧）的详细机制：遗传身份、对立可塑性、投射路由
- [[incentive-salience]] — BLA→NAc通道直接向伏隔核传递奖励价值信号，参与激励显著性计算
- [[subjective-value-encoding]] — BLA提供情绪价值的特异性分量（结果身份+激励价值），是主观价值编码的情绪维度

## 未解问题

- Q-fear-human-amygdala-specificity（高优先级）：人类杏仁核功能架构与啮齿类的保守程度
- Q-fear-low-road-function（中优先级）：丘脑"低路"直接投射的恐惧学习独立贡献
- Q-fear-itc-bidirectionality（中优先级）：ITC在恐惧重现时的具体再平衡机制
- Q-stress-01（高优先级）：慢性应激下BLA可塑性增生的功能意义与病理化临界点

## 修订历史

- 2026-05-30 · 创建 · 基于《当杏仁核学会恐惧》一文 · 初始置信度：高
- 2026-07-09 · 修订 rev2 · 基于《应激的双刃剑》(#77) · 新增应激下 BLA-海马方向性分离（慢性应激→BLA 树突增生 vs CA3 退缩）；CeM→HPA 轴输出路径扩展（CeM→PVN→CRH 完整链）；related 新增 hpa-axis、glucocorticoid-hippocampus-plasticity；opens_questions 新增 Q-stress-01；连接新增两条
- 2026-07-17 · 修订 rev3 · 基于《一缕香气的旅行》(#85) · 新增嗅觉→皮层杏仁核直接通路（唯一不经丘脑的感觉-情绪通路）；related 新增 olfactory-system；key_sources 新增 PMID:19804753
- 2026-07-30 · 修订 rev4 · 基于《情绪的两条轨道》(#98) · 新增BLA奖励-恐惧双通道小节（Ppp1r1b+/Rspo2+遗传身份；NAc vs CeM投射对立可塑性；DA→BLA驱动奖励记忆）；更新一句话定义；当前理解新增BLA双极编码段落；关键证据表添加3行；related新增bla-valence-circuits、incentive-salience、subjective-value-encoding；key_sources新增PMID:25925480、PMID:27041499、PMID:38396258；连接新增3条；updated→2026-07-30
- 2026-06-16 · 修订 rev6 · 基于《社会大脑的肽类密码》(#194) · 新增催产素调制小节：PVN→CeA 投射通过 OT 降低 CeA 防御反应；CeA 星形胶质细胞 OXTR（Wahis 2021）；related 新增 oxytocin-system；opens_questions 新增 Q-OT-04；key_sources 新增 PMID:33589833、PMID:37248645

## 来源文章

- [[2026-05-30-amygdala-fear-memory]]
- [[2026-07-09-stress-glucocorticoid-hippocampus-hpa-axis]]
- [[2026-07-17-olfactory-system-molecular-to-memory]]
- [[2026-07-30-bla-reward-fear-circuits]]
- [[2026-06-16-oxytocin-social-bonding-neural-circuits]]

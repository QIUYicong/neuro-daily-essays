---
title: β振荡
slug: beta-oscillations
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-06-14
updated: 2026-07-19
revision_count: 2
dimensions: [molecular, synaptic, cellular, microcircuit, brain-region, whole-brain-network, cognition, behavior, disease]
related: [parkinsons-disease, basal-ganglia, gamma-oscillations, theta-oscillations, dopamine-reward-prediction-error, working-memory, cortical-canonical-microcircuit, predictive-coding, cortical-layers, pv-interneurons, persistent-activity]
prerequisites: [basal-ganglia, action-potential, synaptic-transmission, cortical-layers]
opens_questions: [Q-pd-beta-causality, Q-beta-gamma-transitions, Q-beta-01, Q-beta-02, Q-beta-03, Q-beta-04]
source_articles: [2026-06-14-parkinson-basal-ganglia-circuit, 2026-07-19-beta-oscillations-cortical-prediction]
key_sources: ["PMID:20463229", "PMID:38954651", "PMID:29381817", "PMID:20359884", "PMID:25556836", "PMID:25585017", "PMID:26996084", "PMID:28785729", "PMID:29339471"]
---

# β振荡 (Beta Oscillations, 13–30 Hz)

> **一句话定义**：频率 13–30 Hz 的神经振荡，以离散爆发（约 100–200 ms）而非持续振荡的形式出现；在运动皮层、感觉皮层和工作记忆三个系统中，其共同功能是**维持当前内部状态/假设的激活**，直到新的不匹配信号（通常为 γ 爆发）要求更新；在帕金森病中因多巴胺缺失而病理性持续增强。

## 当前理解

我们现在认为，β 振荡代表大脑回路对"当前内部状态有效，无需更新"这一判断的振荡性表达。这个原理在三个主要系统中均有体现，构成一个统一框架：

**1. 运动皮层（状态维持 vs 运动解锁）**

β 振荡在运动皮层"等待状态"中主导。当运动意图出现时，β 功率下降（ERD，Event-Related Desynchronization），允许运动回路从相位约束中解放出来，以更精细的时序执行运动指令。运动完成后，β 反弹（PMBR，Post-Movement Beta Rebound）——代表"当前运动目标完成，回到维持/监控状态"。

关键量化：ERD 始于运动前约 500–1000 ms；PMBR 持续约 500–1500 ms，幅度与运动成功度正相关。

**2. 感觉皮层层级（反馈频道）**

在灵长类视觉皮层的 28 对区域之间（Bastos et al., 2015，PMID: 25556836），前向信号（低→高级，感觉上行）以 γ 频段（60–80 Hz）传递；后向信号（高→低级，预测反馈）以 β 频段（14–18 Hz）传递，跨区域一致。DCM 建模（Bastos et al., 2015，PMID: 25585017）进一步显示浅层（L2/3）主γ前向，深层（L5/6）主β后向。

这使 β 成为皮层层级中"当前预测有效"反馈的振荡载体——承载 L5/6 深层神经元从高级皮层向低级皮层发出的内部模型。

**3. 工作记忆（背景守护 + 内容召回）**

猴子前额叶皮层的工作记忆延迟期中（Lundqvist et al., 2016，PMID: 26996084），β 爆发（平均 130 ms）是默认背景态；γ 爆发（平均 67 ms，刺激选择性）在编码和读取时打断 β。深层 α/β 的特定相位调制浅层 γ 爆发的概率，构成内容访问的时间"许可窗口"（Bastos et al., 2018，PMID: 29339471）。

补充证据（Spitzer & Haegens 2017，PMID: 28785729）显示：β 还能以**内容特异**的方式参与记忆再激活——不同记忆内容对应不同 β 功率水平或同步模式，在数百毫秒内短暂出现。

**4. 帕金森病（病理卡死）**

多巴胺缺失使 STN-GPe 网络陷入持续 β 同步，产生病理性相位-振幅耦合（PAC）：β 相位锁定 >200 Hz 高频振荡振幅，占据皮层-STN 信息通道，阻断运动意图实施（López-Azcárate et al., 2010，PMID: 20463229）。

**统一框架**："当前内部假设有效，维持状态" → β 增强；"新信息不符合假设，需更新" → β 被 γ 爆发打断或消失。

## 关键机制

### β 振荡的产生

β 振荡的主要产生位点：

1. **皮层深层（L5/6 次粒层）**：厚锥体细胞（thick-tufted pyramidal cells）的膜时间常数与 β 半周期（30–70 ms）匹配，使其自然倾向在 β 频段整合和输出。深层神经元产生的 β 在皮层内向上传播，调制浅层（L2/3）的 γ 产生。

2. **丘脑-皮层-基底节回路**：正常状态下的 β 由皮层-STN-GPe-丘脑-皮层回路协作维持，多巴胺通过 D1/D2 受体调控 β 功率。

3. **PV+ 中间神经元参与 γ 生成，间接影响 β**：β/γ 的相互抑制（β 抑制 γ，γ 打断 β）是深层 β 调制浅层 γ 的局部回路机制之一。

### β 爆发的离散性

β 振荡以**短暂离散爆发**（burst，约 100–200 ms，频率 1–5 次/秒）而非持续振荡出现。传统功率谱的"持续高 β"实际上是"β 爆发密集期"。这一认识（Lundqvist 2016 在 WM 中明确，运动研究中有并行发现）意味着：β 不是连续的背景功率，而是离散的信息事件。

### β 的两种形式

| 类型 | 特征 | 功能 | 来源 |
|------|------|------|------|
| **保护性 β** | 非内容特异，广泛分布，延迟期背景 | 阻断随机感觉干扰 | Lundqvist 2016 |
| **内容特异性 β** | 参数化编码记忆内容，短暂（数百 ms） | 主动再激活特定记忆表征 | Spitzer & Haegens 2017 |

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| β ERD（运动前）代表运动回路解锁，不是"激活" | 运动皮层 LFP/EEG 记录，运动前 500–1000 ms 开始 | Pfurtscheller & Aranibar 1979 + 后续系列 | 高（established） |
| β 反弹幅度与运动成功度正相关 | 运动皮层 MEG，行为-振荡关联 | 多项研究 | 中（mainstream） |
| 28 对灵长类视觉区域：前向 γ，后向 β | Granger 因果分析，解剖学层级独立确认 | PMID: 25556836 | 高 |
| V1-V4 DCM：L2/3 产生前向 γ；L5/6 产生后向 β | DCM 分层重建 | PMID: 25585017 | 中-高 |
| WM 延迟期：β 爆发 130 ms（背景），γ 爆发 67 ms（内容编码） | 猴 PFC LFP，单次实验爆发分析 | PMID: 26996084 | 高 |
| WM 延迟期内容特异性 β（振动频率参数化） | 人类 MEG + 灵长类 LFP 综合 | PMID: 28785729 | 中 |
| 前额叶层流：深层 L5/6 α/β 调制浅层 L2/3 γ 爆发概率 | 猴 PFC 层流电极，相位-功率耦合 | PMID: 29339471 | 高 |
| PD 中 OFF 状态 STN β 主导，伴 β-高频 PAC | n=15 PD 患者 STN-LFP 记录 | PMID: 20463229 | 高 |
| 左旋多巴/DBS 通过 β→θ 切换改善 PD 运动 | n=25 患者皮层+STN LFP 同步 | PMID: 38954651 | 中-高 |

## 连接

- [[cortical-canonical-microcircuit]] — β 是规范微回路 L5/6 后向反馈通路的频率实现
- [[predictive-coding]] — β/γ 频率分工是预测编码前馈误差/反馈预测分离的振荡基础
- [[gamma-oscillations]] — β 与 γ 功能上互补对立；深层 β 调制浅层 γ 的触发时机
- [[working-memory]] — β 爆发是 WM 延迟期的默认背景态和内容再激活机制
- [[cortical-layers]] — β 主要起源于深层（L5/6），γ 主要起源于浅层（L2/3）
- [[pv-interneurons]] — PV+ 篮状细胞在 β 调制浅层 γ 的局部回路中参与作用
- [[parkinsons-disease]] — 多巴胺缺失导致 β 病理性持续增强
- [[basal-ganglia]] — STN-GPe-GPi 网络中 β 振荡的基底节来源
- [[theta-oscillations]] — θ（4–10 Hz）与 β 在运动选择中功能对立

## 未解问题

- **Q-pd-beta-causality**（中优先级）：β 振荡是 PD 症状的直接原因还是并行标记？Adaptive DBS 证据支持因果，但未最终确定
- **Q-beta-gamma-transitions**（中优先级）：正常→PD 状态中，γ→β 振荡占主导的分子触发机制
- **Q-beta-01**（高优先级）：β/γ 频率层级规律（灵长类视觉+前额叶）是否在啮齿类、人类和非视觉脑区同样成立？
- **Q-beta-02**（中优先级）：保护性β（Lundqvist 2016）和内容特异性β（Spitzer 2017）能否在同一实验中同时区分和量化？
- **Q-beta-03**（中优先级）：β 是 PD 运动障碍的因还是果？
- **Q-beta-04**（低优先级）：不同脑区（前额叶、海马、小脑）的 β 起搏机制是否相同？

## 修订历史

- 2026-06-14 · 创建 · 基于《多巴胺的沉默与节律的失控》（PD/基底节文章）· 仅覆盖 PD/运动系统
- 2026-07-19 · **重大修订（rev2）** · 基于《β振荡的三副面孔》（文章 #87）· 新增感觉皮层层级证据（Bastos 2015 ×2）、工作记忆证据（Lundqvist 2016、Bastos 2018）、内容特异性β（Spitzer 2017）· 建立统一框架 · status 维持 mainstream，confidence 由 medium 升至 high · 新增未解问题 Q-beta-01 至 Q-beta-04

## 来源文章

- [[2026-06-14-parkinson-basal-ganglia-circuit]]
- [[2026-07-19-beta-oscillations-cortical-prediction]]

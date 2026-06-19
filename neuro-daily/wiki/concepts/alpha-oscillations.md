---
title: α振荡
slug: alpha-oscillations
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-22
updated: 2026-07-22
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, whole-brain-network, cognition, behavior]
related: [theta-gamma-coupling, gamma-oscillations, beta-oscillations, theta-oscillations, working-memory, thalamus, thalamocortical-circuit, sleep-spindles, pv-interneurons, dorsal-attention-network, cortical-layers, prefrontal-cortex]
prerequisites: [thalamocortical-circuit, voltage-gated-calcium-channels, pv-interneurons, cortical-layers]
opens_questions: [Q-theta-primate, Q-alpha-thalamic-vs-cortical, Q-alpha-c-vs-dprime]
source_articles: [2026-07-22-alpha-oscillations-attention-wm]
key_sources: ["PMID:10576479", "PMID:10704517", "PMID:16887192", "PMID:18829955", "PMID:18287498", "PMID:21779269", "PMID:21779257", "PMID:29044823", "PMID:24268290", "PMID:31972202", "PMID:30887701", "PMID:32513573"]
---

# α振荡 (Alpha Oscillations)

> **一句话定义**：α振荡（8–12 Hz）是大脑中振幅最强的神经振荡，由视丘-皮层回路与皮层下颗粒层（L5）协同产生，通过规律性的**间歇性抑制脉冲**主动压制无关感觉输入、调控注意选择，并在工作记忆中通过α-γ跨频率耦合参与信息容量管理。

## 当前理解

我们现在认为，α振荡（8–12 Hz，个体差异约±1–2 Hz）不是大脑"闲置"时的副产品，而是一种**主动的、目标导向的抑制信号**。经典的"α减弱=激活"观点只描述了现象的一半：同等重要的另一半是"α增强=主动压制"。

α的核心功能是**差异化感觉门控**：通过在被忽略皮层区域主动增强α功率，大脑在数十毫秒前就"预先关闭"无关输入的通道，使有限的皮层资源集中于当前任务相关的输入。这是一种**抑制驱动的选择机制**，与Transformer注意力机制的"激活驱动选择"形成鲜明对比。

在工作记忆中，α的功能从"感知门控"延伸为"存储门控"：α-γ PAC（相位-幅度耦合）提供了类似θ-γ嵌套的信息分格机制——但这一机制的证据基础仍以相关性研究为主，因果证据尚弱。

## 关键机制

### 生成回路：视丘-皮层双源

**视丘来源（主流模型）**：
- TC细胞（谷氨酸能）超极化 → T型Ca²⁺通道（CaV3系列）去失活
- IPSP（来自TRN的GABAergic抑制）结束 → T型通道反弹激活 → 低阈值Ca²⁺脉冲（LTS）→ TC细胞簇放电
- TC→皮层→TRN→TC的回路在约10 Hz处产生共振
- 枕核/LP复合体（Pulvinar）投射广泛，作为"α广播器"同步多个皮层区域

**皮层来源（层流电极证据）**：
- 低级视觉区（V2/V4）：下颗粒层L5作为主要α节律发生器（Granger因果→L4/L2/3）
- 高级联合区（IT）：超颗粒层L2/3为主要发生器，且功能与低级区相反
- L5既接受视丘（LP/LGN等）输入，也发出皮层→视丘反馈，使两种来源本质上是同一回路的不同节点

### 抑制机制：脉冲式周期性门控

Klimesch (2007) 抑制-时序假说：
- 每个α周期（~100 ms）中存在**兴奋窗口**（波谷附近，~20–50 ms）和**抑制窗口**（波峰附近，~50–70 ms）
- ERS（功率增强）= 大脑主动指令某区域进入周期性抑制模式
- ERD（功率降低）= 该区域去抑制，进入高兴奋性持续态

Mathewson (2011) 脉冲式抑制：
- α产生交替的"开/关"微态序列，而非持续抑制
- 外部节律性刺激可相位锁定α，使刺激落入兴奋窗口

### 空间注意：差异化α拓扑图

**"忽略哪里 → 哪里α升高"原则**（Worden 2000, Foxe & Snyder 2011）：
- 视觉空间：关注右侧 → 左枕区α升高（按视网膜拓扑图）
- 听觉：关注左侧声音 → 右顶区α升高
- 触觉：关注一侧肢体 → 对侧体感区α升高
- 特征注意：忽略运动 → 背流α升高；忽略颜色 → 腹流α升高

这一拓扑特异性是预期性的（刺激出现前已建立），由额顶网络通过皮质-皮质通路（而非仅视丘）自上而下调控。

### 工作记忆：α-γ PAC的分格容量机制

Roux & Uhlhaas (2014) 双代码模型：
- 海马θ-γ CFC：编码顺序性信息（时序标记）
- 额颞α-γ CFC：编码内容性信息（α作为分格器，γ编码具体内容）

Wianda & Ross (2019) WM三阶段：
- 编码期：枕区α-γ PAC↑（γ在α波谷编码视觉特征）
- 维持期：额颞α功率↑（保护记忆免受视觉干扰）
- 提取期：额→枕α-γ PAC↑（额叶α门控枕颞γ的记忆再激活）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 被忽略位置皮层α预期性升高（空间选择） | 64导EEG，视觉/听觉/触觉提示范式 | Worden 2000 PMID:10704517 | 高 |
| α为主动压制而非被动闲置 | RSVP范式+10 Hz rTMS因果验证 | Foxe & Snyder 2011 PMID:21779269 | 高 |
| 预刺激α↑→视觉辨别↓（独立于警觉） | EEG+视觉辨别，顶枕沟源定位 | van Dijk 2008 PMID:18287498 | 高 |
| 低级视觉区α由L5产生（Granger因果） | 清醒猕猴层流CSD+Granger | Bollimunta 2008 PMID:18829955 | 中 |
| 枕核α调制皮层增益，影响注意选择 | 枕核病变+fMRI+MEG综合证据 | Bourgeois 2020 PMID:31972202 | 中 |
| α影响感知决策标准（c），不改变d' | 信号检测理论分析 | Samaha 2020 PMID:32513573 | 中（争议） |
| WM中α-γ PAC在编码/维持/提取三阶段变化 | MEG + WM范式 | Wianda 2019 PMID:30887701 | 中 |
| rTMS增强额-枕α-γ PAC改善MCI工作记忆 | 双盲rTMS+EEG+行为 | Yuan 2025 PMID:40500659 | 低-中（单中心） |

## 连接

- [[thalamocortical-circuit]] — α的主要发生回路（TRN-TC相互作用）
- [[sleep-spindles]] — 睡眠纺锤波（12–14 Hz sigma）与清醒α共享TRN-TC机制
- [[gamma-oscillations]] — α-γ CFC（α提供分格，γ编码内容）
- [[theta-gamma-coupling]] — θ-γ vs α-γ在WM中的争议（Q-theta-primate）
- [[working-memory]] — α-γ PAC参与WM容量管理的机制
- [[dorsal-attention-network]] — 额顶网络通过α调控感觉皮层
- [[thalamus]] — 枕核/LP生成广播式α信号
- [[cortical-layers]] — L5主导低级视觉区α；L2/3主导高级联合区α
- [[beta-oscillations]] — β（13–30 Hz）与α在频率相邻但功能不同：β=状态维持，α=选择性压制

## 未解问题

- **Q-theta-primate（高优先级）**：人类工作记忆中，α-γ PAC是否真正替代θ-γ嵌套实现容量分格？α频率下的"分格数"（~1–2）远少于θ频率下（~4–8），如何解决容量计数的不吻合？
- **Q-alpha-thalamic-vs-cortical**：清醒状态下，视丘（枕核/TRN）来源的α与皮层（L5）产生的α是同一机制的不同层级，还是两个独立的振荡器？二者如何相互影响？
- **Q-alpha-c-vs-dprime**：α振荡究竟影响感知决策标准（c）还是真实感觉灵敏度（d'）？两种研究结论的矛盾来自方法学差异还是真实分歧？

## 修订历史

- 2026-07-22 · 创建 · 基于《α振荡：视丘节拍器、感知闸门与人类工作记忆的抑制性容量机制》 · 初始置信度：高（注意/感知功能层），中（机制层与WM α-γ证据）

## 来源文章

- [[2026-07-22-alpha-oscillations-attention-wm]]

---
title: 双眼竞争
slug: binocular-rivalry
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-10-05
updated: 2026-10-05
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, whole-brain-network, cognition, methods]
related: [attention-consciousness-dissociation, neural-correlates-of-consciousness, v1-primary-visual-cortex, inferior-temporal-cortex, v4-visual-area, global-workspace-theory, recurrent-processing-theory, predictive-coding, integrated-information-theory, access-consciousness, phenomenal-consciousness, attentional-blink, visual-awareness-negativity]
prerequisites: [action-potential, synaptic-transmission, v1-primary-visual-cortex, neural-correlates-of-consciousness]
opens_questions: [Q-rivalry-01, Q-rivalry-02, Q-rivalry-03]
source_articles: [2026-10-05-binocular-rivalry-visual-competition]
key_sources: ["PMID:2772635", "PMID:8602261", "PMID:9808462", "PMID:11823801", "PMID:16051174", "PMID:25749677", "PMID:28854000", "PMID:41397973", "PMID:41852726"]
---

# 双眼竞争 (Binocular Rivalry)

> **一句话定义**：当两眼各接收一幅相互不兼容的图像时，主观知觉在两个图像之间自发周期性地切换（约每次支配2-4秒），而非形成稳定叠加——这一现象揭示了意识不由感觉输入直接决定，而是在皮层多层级的竞争性互抑制与神经适应中主动构建。

## 当前理解

我们现在认为，双眼竞争是目前最有力的"分离物理刺激与意识内容"的实验范式。从1838年Wheatstone发明立体镜以来，大量研究已经建立了以下共识（Blake & Logothetis 2002 综述，PMID:11823801）：

**1. 竞争不在单眼层，而在表征层。** Logothetis等（1996，PMID:8602261）的刺激交换实验证明，当竞争图像在两眼间快速交换位置时，知觉支配不随之立即改变——一段知觉支配可以跨越多次物理交换延续。这意味着竞争发生在比眼优势柱（V1）更高级的"图像表征"层。

**2. 皮层存在知觉追踪梯度。** 越往视觉层级高处，神经元追踪知觉（而非物理刺激）的比例越高：MT/V4约35%，IT/STS高达90%。V1主要追踪眼信号（Haynes & Rees 2005，PMID:16051174）；FFA/PPA追踪知觉内容（Tong et al. 1998，PMID:9808462）。

**3. 机制：互抑制+神经适应+噪声。** 竞争性知觉表征通过互抑制性中间神经元相互压制（winner-take-all），同时支配表征的神经元随时间出现神经适应（疲劳），使其抑制力减弱，对侧表征逐渐逃脱并翻转。支配期的随机性来自神经噪声叠加在确定性适应过程上。

**4. 前额叶-顶叶有因果参与。** 不只是相关——右侧IFC损伤（前岛叶+下额叶，Fritsch et al. 2026，PMID:41852726）直接减慢多稳态翻转速率，支持前额叶在知觉推断更新中的主动角色（而非仅反映报告行为）。

**5. LOC具有预测性意识活动。** 2025年Vanhoyland等（PMID:41397973）在人类外侧枕叶复合区（LOC）记录到：翻转前约1500ms，神经活动已开始向"即将到来的"知觉状态转移。这与预测编码框架高度一致——大脑在翻转发生前就已经在计算下一个最可能的知觉状态。

**6. 注意依赖性独特。** 双眼竞争的翻转在注意资源被占据时显著减慢乃至停止（Dieter et al. 2016，PMID:27230785），而其他双稳态感知（内克尔立方体等）在无注意下仍可翻转——说明双眼竞争有独特的注意依赖机制，可能因其需要整合来自独立视觉通路的信号。

## 关键机制

### 分子/突触层
- **GABA能抑制**：互抑制性神经元释放GABA，实现两个竞争表征之间的相互抑制
- **适应机制**：重复激活导致高压激活钾通道开放（可能的细胞内适应机制）或突触短时程压制（STP），使支配神经元的有效驱动力随时间下降

### 细胞/微回路层
- **竞争性互抑制网络**（winner-take-all）：两个竞争表征的神经元群通过中间抑制性神经元互相抑制；胜者全拿但胜者自身逐渐适应
- **Levelt定律（修订版，Brascamp et al. 2015，PMID:25749677）**：
  - 增加任意眼的刺激对比度 → 加速翻转（两眼效果相似）
  - 增加支配眼刺激 → 延长其支配期
  - 非支配眼刺激强度对支配期影响有限（弱修订版）
  - 支配期分布：近对数正态分布（噪声驱动）

### 皮层层级
- **V1（眼优势柱）**：主要追踪眼信号；局部有少量知觉调制神经元；不是竞争的主要场所
- **V4/MT（中级视觉皮层）**：约35%神经元追踪知觉；是从眼信号到知觉信号过渡的层级
- **IT/FFA/PPA/STS（高级颞叶）**：>90%神经元追踪知觉；是知觉内容的主要神经表征区
- **LOC（外侧枕叶复合区）**：新发现（Vanhoyland 2025）的预测性意识节点，1500ms前预测翻转方向

### 前额叶-顶叶
- **推断更新功能**（Brascamp et al. 2018，PMID:28854000）：将双眼竞争翻转理解为贝叶斯假说更新；前额顶叶是"重采样"的执行者
- **因果角色**：右侧IFC（前岛叶+下额叶）损伤减慢多稳态翻转（Fritsch et al. 2026）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 竞争在表征层，不在单眼层 | 猕猴刺激交换范式：知觉跨越眼间交换持续 | PMID:8602261（摘要） | 高 |
| V1追踪眼信号，高级皮层追踪知觉 | 人类双眼竞争fMRI多变量解码 | PMID:16051174（摘要） | 高 |
| FFA/PPA追踪知觉内容 | 面孔-房子双眼竞争fMRI，BOLD信号随知觉而非刺激切换 | PMID:9808462（摘要） | 高 |
| 前额叶有因果参与翻转 | 右IFC缺血性损伤（n=9），翻转期延长19.33s vs 14.14s | PMID:41852726（全文） | 中（样本小） |
| LOC翻转前1500ms预测意识内容 | 人类SEEG颅内电极，3种感知范式，解码时间分析 | PMID:41397973（全文） | 中-高（单个研究） |
| 双眼竞争翻转依赖注意 | 注意任务消耗下双眼竞争翻转停止，其他双稳态继续 | PMID:27230785（摘要） | 中（方法论争议） |
| Levelt定律：支配期对数正态分布 | 50年大量心理物理实验 | PMID:25749677（综述） | 高 |

## 连接

- [[attention-consciousness-dissociation]] — 双眼竞争是证明注意-意识解离的核心实验平台（被抑制图像仍可无意识加工）
- [[neural-correlates-of-consciousness]] — 双眼竞争是定位NCC的金标准范式（刺激不变，意识变）
- [[v1-primary-visual-cortex]] — V1主要追踪眼信号，是竞争层级的最底层（非主要竞争场所）
- [[inferior-temporal-cortex]] — IT皮层~90%神经元追踪知觉；知觉梯度的顶端
- [[v4-visual-area]] — V4是知觉追踪比例的中间层（约35%）
- [[global-workspace-theory]] — 知觉翻转时出现额顶点火（P3b），支持GWT的广播机制
- [[recurrent-processing-theory]] — 强版本（不需要前额叶）受到IFC损伤研究和LOC预测活动的挑战
- [[predictive-coding]] — LOC翻转前1500ms预测性活动与预测编码框架一致
- [[integrated-information-theory]] — IIT预测支配状态有更高Φ，但计算困难，尚无定量验证
- [[attentional-blink]] — 另一个注意-意识解离范式，与双眼竞争机制不同（一个耗竭注意，一个需要注意）

## 未解问题

- **Q-rivalry-01**（高优先级）：V1究竟是"完全被动的眼信号传递者"还是"弱但真实的意识贡献者"？RPT理论认为V1递归活动是意识必要基础，但双眼竞争数据（V1主要追踪眼信号）似乎与此矛盾——两者如何调和？
- **Q-rivalry-02**（中优先级）：被抑制眼的图像在哪个层级被加工？这种无意识加工能否跨越单次竞争翻转而累积（影响下一个翻转的概率）？
- **Q-rivalry-03**（中优先级）：LOC的翻转前1500ms预测活动是否也见于其他意识范式（掩蔽、注意瞬脱）？它在意识层级中是"早期传感器"还是"推断执行器"？

## 修订历史

- 2026-10-05 · 创建 · 基于《双眼竞争：当两眼看到不同的世界，谁在决定你看到什么？》(#165) · 初始置信度：高（机制和层级竞争证据充分，established；LOC预测活动等新发现为emerging→mainstream）

## 来源文章

- [[2026-10-05-binocular-rivalry-visual-competition]]

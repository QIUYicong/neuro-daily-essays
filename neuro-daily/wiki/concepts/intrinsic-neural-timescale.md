---
title: 内禀神经时间尺度
slug: intrinsic-neural-timescale
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-08-13
updated: 2026-08-13
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, whole-brain-network, cognition]
related: [temporal-coding-hierarchy, temporal-hierarchy, temporal-receptive-window, predictive-coding, ei-balance, nmda-receptor, default-mode-network, prefrontal-cortex]
prerequisites: [action-potential, ltp, ei-balance]
opens_questions: [Q-temp-hier-01, Q-temp-hier-02, Q-temp-hier-03]
source_articles: [2026-08-13-cortical-temporal-hierarchy-trw]
key_sources: ["PMID:25383900", "PMID:34991988", "PMID:37045604", "PMID:35110401", "PMID:32663642"]
---

# 内禀神经时间尺度 (Intrinsic Neural Timescale, INT)

> **一句话定义**：神经元自发放电时间序列的自相关函数指数衰减时间常数 τ，反映该皮层区域的自发活动模式能持续多久、能将过去多长时间的输入整合进当前状态——从初级感觉皮层的约 50 ms 到前扣带回的约 300 ms，构成一条跨越两个数量级的皮层时间层级梯度。

## 当前理解

我们现在认为，大脑皮层不同区域天然地调谐在不同时间尺度上工作——这不是偶然，而是由突触化学组成的系统性梯度决定的。Murray et al. 2014（PMID:25383900）在猕猴7个皮层区域的自发放电中直接测量了这一梯度：初级感觉区（MT、S1）的 τ ≈ 50–70 ms，顶叶联合区（LIP）≈ 100–120 ms，外侧前额叶 ≈ 150–180 ms，眶额叶 ≈ 200 ms，前扣带回 ≈ 250–350 ms。

这一梯度（rs=0.89 与解剖层级的 Spearman 相关，P<10⁻⁵）意味着：
- **短 INT（感觉皮层）**：活动快速衰减，对新刺激高度敏感，"活在当下"
- **长 INT（联合皮层 / DMN）**：活动持续更长，自动整合过去数百毫秒至数秒的输入，"记得历史"

人类大脑的 INT 梯度通过 fMRI、MEG 和颅内 EEG 均已证实（Wolff et al. 2022，PMID:34991988；Golesorkhi et al. 2021，PMID:33664456）：单模态感觉区 INT 最短，默认模式网络（DMN）核心节点 INT 最长。时间层级还延伸进入内嗅皮层和海马（Cusinato et al. 2023，PMID:37045604）。

**INT 与时间感受野（TRW）的关系**：INT 是区域的内禀振荡属性（用自发活动测量），TRW 是区域的外部输入整合能力（用打乱刺激的 fMRI 测量）。两者高度相关，但不等同——INT 更基础，TRW 更依赖任务和输入结构。

## 关键机制

### 分子机制：NMDA 受体亚基组成梯度

NMDA 受体的时间常数由 GluN2 亚基决定：GluN2B（慢，衰减时间 ~150–200 ms）在联合皮层（高 INT 区）比例更高；GluN2A（快，衰减时间 ~30–50 ms）在初级感觉皮层（低 INT 区）比例更高。GluN2B/GluN2A 比率梯度直接导致突触电流持续时间的皮层梯度，从而贡献 INT 差异（Murray et al. 2014 提出的机制假说）。

### 回路机制：局部递归连接梯度

联合皮层区域兴奋性神经元之间的局部递归连接（E→E）更强，形成更强的自我维持正反馈回路。一旦被激活，联合皮层能在更长时间内维持活跃状态（类似于"高增益慢衰减"放大器）。这与联合皮层更厚的第 II/III 层和更多锥体细胞-锥体细胞的水平连接一致。

### 系统机制：长程兴奋与局部抑制的精细平衡

Li & Wang 2022（PMID:35110401）的计算模型揭示第三个机制：联合皮层接受更强的长程皮层间兴奋性输入，同时配备更强的局部 GABA 能抑制（精细平衡）。这种"强驱动 + 强制动"的组合产生慢动力学：系统被激活后，强局部抑制不会立即终止活动，而是形成一个慢速、持续的活动平台。

### 结构基础：髓鞘化梯度

Ito et al. 2020（PMID:32663642）发现 INT 与 T1w/T2w 比值（髓鞘含量代理指标）负相关：初级感觉皮层髓鞘化程度高（INT 短），DMN 核心节点髓鞘化程度低（INT 长）。低髓鞘化区域倾向于有更密集的局部水平连接（递归连接更强），这与回路机制一致。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 猕猴皮层 INT 层级：MT~50ms → ACC~350ms | 自发放电自相关 + 指数拟合，7皮层区域，rs=0.89 | PMID:25383900 | 高 |
| 人类 INT 梯度：感觉区短→DMN长 | fMRI/MEG/EEG 多模态复现，跨多项独立研究 | PMID:34991988 | 高（多来源）|
| 颞叶→内嗅→海马→杏仁核 INT 梯度 | 颅内 EEG，11名癫痫患者，毫米级分辨率 | PMID:37045604 | 中-高（临床人群）|
| 三机制（突触梯度+E/I属性+长程精细平衡）产生 INT 梯度 | 大规模计算模型（33区域猕猴皮层） | PMID:35110401 | 中（计算模型，待实验验证）|
| INT 与髓鞘含量负相关 | fMRI + T1w/T2w 比值，多被试 | PMID:32663642 | 中（相关性，非因果）|
| 癫痫患者 INT 减短；ML 诊断准确率 76%/定侧 96% | 颅内 EEG + ML 分类器 | PMID:36764677 | 高（临床验证）|

## 连接

- [[temporal-receptive-window]] — TRW 是 INT 在外部输入整合能力上的表现；两者高度相关，测量角度不同
- [[temporal-coding-hierarchy]] — INT 是嵌套时间编码层级（记忆层面）的区域时间常数基础
- [[temporal-hierarchy]] — INT 是多时间尺度并行计算的皮层区域实现
- [[predictive-coding]] — INT 梯度与预测编码层级对应：高 INT 区域预测更长时程的上下文（Caucheteux 2023）
- [[ei-balance]] — E/I 平衡决定局部网络动力学；高 INT 区域有更强局部兴奋+更强局部抑制的精细平衡
- [[nmda-receptor]] — GluN2B/GluN2A 亚基比率梯度是 INT 梯度的分子机制候选
- [[default-mode-network]] — DMN 核心节点是 INT 最长的皮层区域，其超长 INT 支撑叙事自我和心智游移
- [[prefrontal-cortex]] — PFC（尤其 ACC/mPFC）INT ~200–350ms，是认知控制和情绪整合的时间整合基础
- [[language-network]] — 语言处理利用 INT 梯度在音节（颞叶，~100ms）到句子（额顶叶，~500ms）到段落（DMN，~秒）并行追踪

## 未解问题

- **Q-temp-hier-01**（高优先级）：GluN2B/GluN2A 亚基比率的皮层梯度是否能在单个大脑通过空间转录组/蛋白质组直接测量，并与同一大脑的 INT 梯度建立单个体水平的因果链？目前证据主要来自跨物种相关性。
- **Q-temp-hier-02**（中优先级）：能否通过精确 TMS 靶向 DMN 核心节点，人为改变其 INT，进而影响叙事理解和自我指涉思维？
- **Q-temp-hier-03**（低优先级）：INT 在发育过程中如何成熟？Miles et al. 2026（PMID:41389010）显示 alpha 频率与 INT 的负相关在发育期只出现于联合区——但分子机制（GluN2B→GluN2A 转换？髓鞘化？）尚未厘清。

## 修订历史

- 2026-08-13 · 创建 · 基于《大脑皮层的时间帝国》文章 #112 · 初始置信度：高（多来源、多物种、多模态的收敛证据）

## 来源文章

- [[2026-08-13-cortical-temporal-hierarchy-trw]]

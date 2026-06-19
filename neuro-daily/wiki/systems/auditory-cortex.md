---
title: 听觉皮层
slug: auditory-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-07-28
updated: 2026-07-28
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, whole-brain-network, cognition]
related: [tonotopic-map, cochlea, thalamus, language-network, dorsal-attention-network, predictive-coding]
prerequisites: [cochlea, tonotopic-map, thalamus]
opens_questions: [Q-ac-01, Q-ac-02, Q-ac-03, Q-ac-04]
source_articles: [2026-07-28-auditory-cortex-tonotopy]
key_sources: ["PMID:19471271", "PMID:22303281", "PMID:27145914", "PMID:22522927", "PMID:23916753"]
---

# 听觉皮层 (Auditory Cortex)

> **一句话定义**：听觉皮层是颞上回（Heschl 回及其周围）的皮层区域，通过核心-带状-旁带状三级层级从简单音调到复杂语义递增提取声学特征，并以 11 张音调拓扑场图的形式组织信息；注意力在此层面主动重写皮层内容，实现鸡尾酒会效应。

## 当前理解

听觉皮层不是单一均质的皮层区域，而是一套高度组织化的多区域层级系统。从人类 fMRI 研究可以识别出多达 **11 张有序的听觉场图**（Brewer & Barton 2016，PMID:27145914），沿音调梯度（tonotopy，频率-位置有序排列）和正交的周期性梯度（periodotopy，时间调制速率偏好）组织——与视觉皮层的偏心率×极角双轴组织高度类似。

听觉皮层按层级分为三个区域（Rauschecker & Scott 2009，PMID:19471271，PMC2846110）：

- **核心区（Core）**：初级听觉皮层 A1 + 吻侧核心区 R，位于 Heschl 回（HG）；对纯音精确调谐，延迟短（~30 ms）。A1 和 R 在 HG 上呈 V 形镜像排列（Saenz & Langers 2014，PMID:23916753）
- **带状区（Belt）**：围绕核心的 7–8 个功能分区（前/后带状），对带通噪声和复杂声学特征响应，延迟 ~50–100 ms
- **旁带状区（Parabelt）**：颞上沟（STS）/颞上回（STG），响应语音/语义内容，延迟 >100 ms

**双听觉流**从带状区分叉：
- **腹侧流（"What"）**：前带状 → 颞叶前极 → 腹侧 PFC — 声音身份识别/语音可懂度
- **背侧流（"Where/How"）**：后带状 → 顶后皮层 → 运动前区 — 空间定位与语音-运动整合

**注意力的皮层重写**：Mesgarani et al.（2012，PMID:22522927）直接证明，在双说话者环境中，STG 群体响应编码被注意者的谱时特征（而非混合信号）；注意切换时，皮层表征内容随之切换。这是注意力实现生成性过滤的直接神经证据。

**颞上回（pSTG）的语音编码**：Pasley et al.（2012，PMID:22303281，PMC3269422）显示，pSTG 的高频 γ（70–170 Hz）活动以谱时感受野（STRF）编码语音，可重建至词语识别精确率中位数 0.89；慢调制（<8 Hz，音节节律）由线性包络追踪，快调制（>8 Hz，音节边界）由非线性能量追踪。

## 关键机制

**音调拓扑图保真**：来自内侧膝状体腹侧（MGBv）的精确拓扑投射将耳蜗频率-位置对应关系在 A1 精确复现（cochleotopy → tonotopy）

**皮层-丘系下行调节（corticofugal）**：皮层向下丘（IC）发送大量反馈投射，主动调节 IC 的频率调谐；听觉感知是主动预测-纠错系统，而非被动前馈

**三级层级内的感受野扩展**：从 A1 到 STG，神经元感受野的频率跨度递增、延迟递增、响应刺激类型的复杂度递增——与视觉 V1→IT 的层级计算逻辑一致

**注意机制与偏置竞争**：自上而下注意信号（来自 DAN/FEF/IPS）通过偏置竞争（biased competition）在 STG 层面优先化被注意声源的表征（类比视觉注意在 V4/IT 的作用）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 人类听觉皮层存在11张有序场图 | 人类高分辨率 fMRI | PMID:27145914 | 中（fMRI分辨率有限，精确数量有争议） |
| A1和R在HG上呈V形镜像排列 | 7T fMRI音调拓扑图 | PMID:23916753 | 中-高（多中心重复） |
| 核心-带状-旁带状三级层级 | 灵长类神经生理+解剖综述 | PMID:19471271 | 高（跨物种一致性） |
| STG注意性选择编码（鸡尾酒会）| 颅内ECoG双说话者实验 | PMID:22522927 | 高（颅内直接测量，因果设计） |
| pSTG以STRF编码语音，可重建词语 | 颅内ECoG+线性解码 | PMID:22303281 | 高（开放全文，直接测量） |

## 连接

- [[cochlea]] — 耳蜗提供经过频率分解的听觉输入，通过 MGBv 精确投射至 A1
- [[tonotopic-map]] — 音调拓扑图是 A1/R 的核心组织原则
- [[thalamus]] — 内侧膝状体腹侧（MGBv）是听觉皮层的直接上游
- [[language-network]] — 腹侧听觉流与语言网络腹侧流（A1→STG→BA45）直接重叠
- [[dorsal-attention-network]] — DAN（FEF/IPS）通过偏置竞争调节 STG 的注意选择
- [[predictive-coding]] — 皮层-丘系下行投射是预测编码的听觉实现；STG 的注意性重写符合生成性过滤预测

## 未解问题

- Q-ac-01：A1 拓扑地图在成人行为中是否被学习历史重组（固定感觉分析器 vs 可塑经验图）？
- Q-ac-02：注意过滤是否也发生在皮层下（MGB 甚至 IC），或仅限皮层？其解剖通路？
- Q-ac-03：11 张场图是否在所有成人中普遍存在，还是受个体语言/音乐经历影响？
- Q-ac-04：ITD 在哺乳类 MSO 的神经机制是否真的是 Jeffress 延迟线？

## 修订历史

- 2026-07-28 · 创建 · 基于《从蜗旋到皮层音图》（#96）· 初始置信度：高

## 来源文章

- [[2026-07-28-auditory-cortex-tonotopy]]

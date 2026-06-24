---
title: 丘脑网状核
slug: thalamic-reticular-nucleus
domain: circuits
type: structure
status: established
confidence: high
created: 2026-09-15
updated: 2026-09-15
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, cognition]
related: [thalamus, thalamocortical-circuit, lateral-geniculate-nucleus, sleep-spindles, prefrontal-cortex, basal-ganglia, dorsal-attention-network, alpha-oscillations, beta-oscillations]
prerequisites: [action-potential, synaptic-transmission, thalamus, thalamocortical-circuit]
opens_questions: [Q-lgn-01, Q-lgn-03, Q-thalamus-gating-mechanism]
source_articles: [2026-09-15-lgn-thalamic-reticular-nucleus-attention-gate]
key_sources: ["PMID:18849967", "PMID:31202541", "PMID:16837581", "PMID:29184210", "PMID:41702717"]
---

# 丘脑网状核 (Thalamic Reticular Nucleus, TRN)

> **一句话定义**：丘脑网状核是一层包裹丘脑外表面的纯GABAergic神经元薄膜，通过监听所有进出丘脑的轴突侧支来实施注意力门控——它是感觉信号进入皮层之前最早的、受前额叶直接"命令"的主动过滤器。

## 当前理解

我们现在认为，TRN是注意力系统在皮层以外部署的最前沿节点：它在感觉信号到达初级感觉皮层之前就已经开始了过滤工作，而且其响应先于丘脑中继核（如LGN）约4毫秒，构成注意力级联的第一道门。

TRN实现这一功能有三个核心特征：

1. **监听者位置**：TRN接收所有进出丘脑的轴突（TC上行轴突 + CT下行轴突）的侧支，因此能"感知"经过丘脑的所有信号流，同时向丘脑中继核发出GABA抑制，形成"监听-反馈抑制"回路。

2. **权力不对称**：前额叶（PFC）向TRN发送**大型驱动型**突触端钮（~1.69 μm，高释放概率）；感觉皮层只发送**小型调制型**端钮（~0.82 μm，低释放概率）（Zikopoulos & Barbas 2006）。这意味着PFC可以直接"命令"TRN调整门控状态，而感觉皮层只能"请求"TRN适度调整。

3. **跨模态选择能力**：TRN在功能上按感觉模态分区（视觉TRN子区、听觉TRN子区等），PFC可以通过基底神经节中间通路选择性地激活"需要压制的感觉模态"对应的TRN子区，实现跨模态注意的精确分配（Nakajima et al. 2019）。

在睡眠期间，TRN扮演完全不同的角色：通过TRN→TC→TRN振荡回路产生NREM睡眠纺锤波（见[[sleep-spindles]]）。这一双重功能（注意门控/纺锤波起搏器）由神经调质（特别是ACh）的张力状态决定：高ACh（清醒）→ 注意门控模式；低ACh（NREM）→ 振荡/纺锤波模式。

## 关键结构

| 特征 | 细节 |
|------|------|
| 神经递质 | 纯GABAergic（GABA-A，部分GABA-B） |
| 位置 | 包裹丘脑外侧表面的薄层"网状"结构（1–2 mm厚） |
| 关键离子通道 | CaV3.3（T型钙通道，CACNA1I基因），NREM纺锤波起搏器必需 |
| 主要输入 | (1)丘脑TC神经元轴突侧支；(2)皮层CT（第6层）轴突侧支；(3)前额叶PFC大型驱动型端钮；(4)基底神经节（GPi/SNr）抑制性输入 |
| 主要输出 | 丘脑各中继核的GABAergic抑制（TC神经元） |
| 功能分区 | 视觉子区（对应LGN）、听觉子区（对应MGB）、体感子区（对应VPM/VPL）等 |

## 关键机制

### 注意力门控机制（前额叶 → TRN → TC）

```
前额叶（PFC）发出注意指令
     │
     ↓ 大型驱动型端钮（直接"命令"TRN）
   TRN活动↓（McAlonan 2008：TRN放电降低约4%，潜伏期22ms）
     │
     ↓ TRN对目标感觉TC核的GABA抑制减弱（"解门控"）
   目标TC核（如LGN）放电增强（约9-11%，潜伏期26ms）
     │
     ↓ 增强的视觉信号进入V1
   注意力的早期放大实现
```

时序关键：TRN效应（22ms）先于LGN效应（26ms），证明注意信号流经TRN→LGN，而非直接到LGN。

### 跨模态感觉抑制（PFC → BG → TRN，Nakajima 2019）

```
PFC下达"优先注意视觉"指令
     │
     ↓ PFC→纹状体→苍白球/黑质网状部（BG输出核）
   BG输出核对TRN听觉子区的抑制
     │
     → TRN听觉子区活动↑（解除BG抑制 → TRN自身释放增强）
     → TRN对听觉TC核的GABA抑制↑
     → 听觉信号传递被压制（"降低听觉噪声"）
```

重要：这是通过**主动抑制干扰**而非放大目标来提高信噪比的策略。

### NREM纺锤波生成（TRN↔TC振荡）

见[[sleep-spindles]]专页。核心：TRN→TC的GABA超极化→TC CaV3.1去失活→TC反跳爆发→再激活TRN，形成10–14 Hz自持振荡。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| TRN注意效应先于LGN约4ms | 猕猴LGN/TRN同时记录：TRN 22ms，LGN 26ms | PMID:18849967 (PMC2713033) | 高（时序因果证据） |
| TRN活动在注意时降低约4% | 猕猴单神经元n=29，p=0.004 | PMID:18849967 (PMC2713033) | 高 |
| PFC→TRN为大型驱动型端钮（vs 感觉皮层的小型调制型） | 猕猴EM + 3D重建端钮大小 | PMID:16837581（PMC6674204） | 高（解剖直接证据） |
| PFC→BG→TRN通路实现跨模态感觉抑制 | 鼠类光遗传学 + 行为辨别任务 | PMID:31202541 (PMC6886709) | 中（鼠类，灵长类有待验证） |
| TRN CaV3.3是纺锤波起搏所必需 | CaV3.3 KO → 纺锤波消失 | PMID:30583750 | 高 |

## 连接

- [[thalamus]] — TRN是丘脑的内在门控层；整体丘脑架构见此
- [[thalamocortical-circuit]] — TRN↔TC是丘脑-皮层回路的核心调制节点；注意门控和纺锤波都在此回路中实现
- [[lateral-geniculate-nucleus]] — TRN是LGN注意门控的上游节点；TRN效应先4ms触发LGN放电变化
- [[sleep-spindles]] — TRN↔TC振荡是NREM睡眠纺锤波的起搏器
- [[prefrontal-cortex]] — PFC→TRN的大型驱动型端钮是注意力"命令"的解剖基础
- [[basal-ganglia]] — PFC→BG→TRN的间接通路实现跨模态感觉抑制（Nakajima 2019）
- [[dorsal-attention-network]] — FEF/IPS是PFC注意系统的关键组件，通过PFC→TRN通路实现注意门控

## 未解问题

- Q-thalamus-gating-mechanism：清醒状态下皮层注意（dlPFC、顶叶）如何通过皮层-丘脑-TRN通路精确门控特定感觉丘脑核，实现感觉注意？（部分回答：McAlonan 2008提供了视觉系统的电生理证据，Nakajima 2019提供了跨模态抑制的因果证据）
- Q-lgn-03：TRN的视觉/听觉/体感子区分化（在鼠类中已证明）在灵长类是否等价？灵长类TRN是否具有类似的模态特异性功能区？

## 修订历史

- 2026-09-15 · 创建 · 基于《守门人的守门人：外侧膝状体如何成为视觉注意的第一道主动关卡》文章 #145 · 整合TRN解剖（GABAergic外套层、功能分区）、注意门控机制（McAlonan时序证据、PFC驱动型端钮不对称）、跨模态抑制（Nakajima PFC→BG→TRN）、睡眠双重功能 · 初始置信度：高

## 来源文章

- [[2026-09-15-lgn-thalamic-reticular-nucleus-attention-gate]]

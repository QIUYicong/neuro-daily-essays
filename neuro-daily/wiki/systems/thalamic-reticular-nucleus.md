---
title: 丘脑网状核
slug: thalamic-reticular-nucleus
domain: systems
type: structure
status: established
confidence: high
created: 2026-06-17
updated: 2026-06-17
revision_count: 1
dimensions: [molecular, cellular, microcircuit, brain-region, cognition]
related: [thalamocortical-circuit, thalamic-firing-modes, sleep-spindles, prefrontal-cortex, basal-ganglia, attention-consciousness-dissociation, dorsal-attention-network]
prerequisites: [thalamus, thalamocortical-circuit, thalamic-firing-modes, action-potential]
opens_questions: [Q-trn-01, Q-trn-02, Q-trn-03]
source_articles: [2026-06-17-thalamic-reticular-nucleus-attention-gating]
key_sources: ["PMID:6589612", "PMID:25126786", "PMID:26503050", "PMID:30405364", "PMID:32699411", "PMID:29673480"]
---

# 丘脑网状核 (Thalamic Reticular Nucleus, TRN)

> **一句话定义**：丘脑网状核是包裹在背侧丘脑外侧的一层弯曲 GABAergic 神经元薄层，接收皮层和丘脑轴突侧支并向所有背侧丘脑核团发出抑制投射；由功能特化子网络组成，清醒时通过 PFC 偏置实现感觉选通（注意力闸门），睡眠时通过 T 型钙通道驱动的振荡产生睡眠纺锤波。

## 当前理解

我们现在认为，TRN 是大脑注意力系统中的关键皮层下节点，同时也是睡眠记忆整合振荡的来源——两个功能使用同一个分子机制（T 型钙通道爆发放电）在不同脑状态下实现。

TRN 不是简单的"开关"，而是由多个功能特化子网络组成的分布式过滤器：
- **感觉投射子网络**：清醒时受 PFC 调制，注意力期间活动降低（disinhibition），释放特定感觉丘脑核团的传递；睡眠时活跃，产生纺锤波
- **边缘投射子网络**：跟踪整体觉醒水平，对注意力任务不直接响应

前额叶皮层（PFC）通过至少两条路径调控 TRN：(1) 直接皮层丘脑投射（快速、模态特异性偏置）；(2) 经基底神经节的间接路径（全局噪音抑制）。

Crick 1984 年提出的"聚光灯假说"预测了 TRN 是注意力内部聚光灯的控制装置——这已被 2014-2020 年的多项直接实验验证。

## 关键机制

### 解剖位置与连接性

TRN 是一片弧形 GABAergic 神经元层，位于内囊与背侧丘脑之间。几乎所有丘脑-皮层轴突和皮层-丘脑（L6 CT 投射）轴突都穿越 TRN，TRN 神经元从这些轴突侧支获得谷氨酸兴奋性输入。TRN 本身只有一种输出：对背侧丘脑核团（感觉、运动、边缘等）的 GABA 抑制投射。

### 分子亚型（Li et al. 2020）

单细胞转录组学揭示 TRN 神经元沿连续梯度排列，两端为：
- **Spp1+ 神经元（核心区）**：富含 Cacna1i（CaV3.3 T 型钙通道），爆发放电强（166 Hz, 5.5 次/5s），主要投射至**一级感觉丘脑核团**（first-order, FO）——感觉门控的关键神经元
- **Ecel1+ 神经元（壳区）**：爆发放电弱（86 Hz, 0.95 次/5s），主要投射至**高阶丘脑核团**（higher-order, HO）——皮层间信息中转调制

### 感觉选通机制（Wimmer et al. 2015; Halassa et al. 2014）

PFC→visTRN→LGN 前馈抑制回路：
1. PFC 识别任务需求 → 发送偏置信号至视觉 TRN (visTRN)
2. "注意视觉"时：visTRN 活动**降低** → LGN 受到的 GABA 抑制减少 → LGN 增益上升 → 更多视觉信息到达皮层
3. "注意听觉"时：visTRN 活动**升高** → LGN 受抑制增加 → 视觉信息被压制

关键发现：PFC 通过感觉**丘脑**（不是感觉皮层）完成跨模态感觉选择——注意力的关键过滤在皮层之前就完成了。

### 睡眠纺锤波生成（Spp1+ TRN 的双重功能）

在 NREM 睡眠中，神经调质（ACh、NE）水平下降 → TRN Spp1+ 神经元超极化 → CaV3.3 T 型通道从失活恢复 → 受输入触发爆发放电 → GABA 抑制 TC 神经元 → TC 反弹爆发 → 再激活 TRN → 约 12-15 Hz 振荡 = 睡眠纺锤波。

Spp1+ 神经元特异性扰动（减少 CaV3.3 活性）→ NREM 睡眠纺锤波数量减少，但不影响总 NREM 时长（Li et al. 2020）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| TRN 感觉子网络在注意力期间活动降低（not 升高）| 自由活动小鼠 TRN 系综记录 + 连接性光遗传标记 | Halassa et al. 2014, Cell（PMID:25126786, PMC4205482）| 高 |
| 激活 visTRN → 注意力表现下降；抑制 → 上升 | 双向光遗传 + 行为（跨模态注意力任务）| Wimmer et al. 2015, Nature（PMID:26503050, PMC4626291）| 高（因果）|
| PFC 驱动 visTRN 前馈抑制控制 LGN 增益 | 氯离子光度测量直接测量 LGN 内 GABA 抑制 | Wimmer et al. 2015 | 高 |
| Spp1+（FO 投射）vs Ecel1+（HO 投射）TRN 亚群 | 单细胞转录组 + FISH + 逆行示踪 + 电生理 | Li et al. 2020, Nature（PMID:32699411, PMC7394718）| 高 |
| Spp1+ 神经元参与纺锤波生成（NREM 睡眠）| 选择性 Gamma6 过表达降低 CaV3.3 活性 → 纺锤波减少 | Li et al. 2020 | 高 |
| PFC→基底神经节→TRN 间接路径实现噪音抑制 | 光遗传 + fMRI + 行为（小鼠）| Nakajima et al. 2019, Neuron（PMID:31202541）| 中（单实验室）|
| PTCHD1 缺失 → TRN 爆发减弱 + ASD 样注意力/睡眠缺陷 | Ptchd1-KO 小鼠 + TRN 特异性敲除 | Krol et al. 2018, Neuron（PMID:29673480）| 中（小鼠，外推有限）|

## 连接

- [[thalamocortical-circuit]] — TRN 是丘脑皮层回路的核心调制器：控制 TC 神经元的爆发/强直及 TRN↔TC 振荡（纺锤波）
- [[thalamic-firing-modes]] — TRN CaV3.3 T 型通道爆发放电是纺锤波的分子驱动力
- [[sleep-spindles]] — TRN Spp1+ 神经元通过 CaV3.3 爆发驱动 TRN↔TC 振荡 = 纺锤波来源
- [[prefrontal-cortex]] — PFC 通过直接投射和基底神经节路径双重偏置 TRN 子网络
- [[basal-ganglia]] — 基底神经节是 PFC→TRN 间接路径的中继（噪音抑制功能）
- [[dorsal-attention-network]] — 背侧注意网络的皮层偏置信号经 TRN 转化为皮层下感觉增益控制
- [[attention-consciousness-dissociation]] — TRN 门控感觉信息进入皮层，是注意力与意识关系研究的重要节点

## 未解问题

- Q-trn-01（高优先级）：PFC→TRN 直接路径（快速模态选择）与 PFC→基底神经节→TRN 间接路径（全局噪音抑制）如何在时间和功能上协调？
- Q-trn-02（高优先级）：TRN 在人类注意力中的作用多大？灵长类皮层更发达，皮层内注意力反馈是否更突出，TRN 的相对贡献是否小于小鼠？
- Q-trn-03（中优先级）：TRN 在 REM 睡眠中的状态是什么？REM 纺锤波不出现，TRN 是否静默，如何被阻止产生振荡？

## 修订历史

- 2026-06-17 · 创建 · 基于《注意力的闸门》文章 #196 · 整合 Crick 1984 聚光灯假说、Halassa 2014 子网络状态依赖性、Wimmer 2015 PFC→visTRN→LGN 回路、Li 2020 分子亚型、Krol 2018 神经发育疾病 · 初始置信度：高

## 来源文章

- [[2026-06-17-thalamic-reticular-nucleus-attention-gating]]

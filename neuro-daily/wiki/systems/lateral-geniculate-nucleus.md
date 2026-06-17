---
title: 外侧膝状核
slug: lateral-geniculate-nucleus
domain: systems
type: region
status: established
confidence: high
created: 2026-10-05
updated: 2026-06-17
revision_count: 2
dimensions: [brain-region, cellular, molecular]
related: [v1-primary-visual-cortex, thalamus, thalamocortical-circuit, binocular-rivalry, ocular-dominance-columns, retinal-waves, pulvinar, transthalamic-pathway]
prerequisites: [action-potential, synaptic-transmission, thalamus]
opens_questions: [Q-lgn-01, Q-lgn-02]
source_articles: [2026-10-05-binocular-rivalry-consciousness-mechanism, 2026-06-17-pulvinar-visual-attention-router]
key_sources: ["PMID:36609303", "PMC9840381", "PMID:16997612", "PMID:37712093", "PMID:22561455"]
---

# 外侧膝状核 (Lateral Geniculate Nucleus, LGN)

> **一句话定义**：外侧膝状核是丘脑内负责视觉信息传递的核团，接受来自视网膜神经节细胞的双眼输入，通过眼特异性的分层组织将两眼信息分别传递到初级视皮层（V1），是视觉信号从外周到皮层的关键门控站。

## 当前理解

LGN 不是单纯的"被动中继站"，而是一个受皮层-膝状体反馈强烈调制的主动视觉处理结构。我们现在认为，LGN 在以下方面发挥主动作用：

1. **双眼信息的眼特异性隔离**：LGN 有 6 层（灵长类），交替接受来自同侧眼（I）和对侧眼（C）的输入，保持两眼信息在传向 V1 之前的完全分离
2. **M/P 通路分流**：大细胞层（magnocellular, M, 层1-2）处理运动/低对比度/高时间分辨率信息；小细胞层（parvocellular, P, 层3-6）处理颜色/精细形状/高空间分辨率信息
3. **感知竞争的早期参与**：双眼竞争期间，LGN 的眼特异性层活动与感知状态相关——被感知眼的 LGN 层活动增强，被抑制眼的减弱（Yildirim & Schneider 2023, PMID:36609303）
4. **皮层-膝状体反馈**：V1 向 LGN 发送大量反馈投射（约是前馈数量的 6 倍），这些反馈可能携带注意和预期信号，调制 LGN 的响应增益

### 组织结构

| 层 | 眼优势 | 通路 |
|----|-------|------|
| 1（最腹侧） | 对侧眼 | M（大细胞） |
| 2 | 同侧眼 | M（大细胞） |
| 3 | 对侧眼 | P（小细胞） |
| 4 | 同侧眼 | P（小细胞） |
| 5 | 对侧眼 | P（小细胞） |
| 6（最背侧） | 同侧眼 | P（小细胞） |

K（koniocellular，尘细胞）层夹于各层之间，参与颜色和调制处理。

## 关键机制

### 门控与增益控制

LGN 接受来自多个结构的调制输入：
- **V1 皮层反馈**：数量远超视网膜前馈，可能负责"预测残差"信号传递
- **脑干网状结构**：通过胆碱能和去甲肾上腺素能输入调制 LGN 的整体激活水平（睡眠-觉醒调节）
- **丘脑枕**：参与注意调制

### 双眼竞争中的 LGN

Yildirim & Schneider（2023）用 7T fMRI 发现：
- M 层和 P 层在感知交替期间的响应幅度**相近**，均高度追踪感知状态
- 这与预测（M/P 差异参与）不符，提示竞争机制不依赖通路选择性
- 感知期与物理交替期（实验控制）的 LGN 活动幅度相近，支持竞争从皮层下开始

这是否意味着竞争"发生在 LGN"？可能不是——更可能的解释是，皮层-膝状体的**反馈投射把皮层竞争结果回传到 LGN**，使 LGN 活动反映了"谁赢得了意识"。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| LGN M/P 层均参与双眼竞争相关活动 | 人类 7T fMRI 直接成像 LGN 分层 | PMID:36609303 | 中 |
| LGN 6 层交替眼优势（灵长类） | 解剖 + 单细胞记录 | 教科书建立事实 | 高 |
| 皮层-膝状体反馈数量超过视网膜-膝状体前馈 | 解剖追踪 | 多来源综述 | 高 |

## 连接

- [[v1-primary-visual-cortex]] — LGN 是 V1 的主要前馈输入来源
- [[thalamus]] — LGN 是丘脑的视觉子核
- [[thalamocortical-circuit]] — LGN-V1 构成最重要的丘脑皮层回路
- [[binocular-rivalry]] — LGN 眼特异性层参与竞争早期处理
- [[ocular-dominance-columns]] — LGN 的眼分离信息投射形成 V1 眼优势柱
- [[pulvinar]] — 枕叶是高阶丘脑核（皮层输入→皮层），与 LGN（视网膜输入→V1）并行构成两条丘脑-V1 驱动通路
- [[transthalamic-pathway]] — LGN 是一阶核（非跨丘脑通路），枕叶通过跨丘脑通路实现皮层间中继

## 未解问题

- Q-lgn-01：LGN 的竞争相关活动是局部竞争机制还是皮层-膝状体反馈的镜像？需要 LGN 特异性干扰实验（如冷冻失活 V1→LGN 反馈通路时 LGN 的竞争信号是否消失）
- Q-lgn-02：M/P 通路在双眼竞争中是否有功能分工？Yildirim 的结论是否代表所有刺激条件？

## 修订历史

- 2026-10-05 · 创建 · 基于《感知的最小战场：双眼竞争》(#165) · 双眼竞争研究中 LGN 活动的发现 · 初始置信度：高
- 2026-06-17 · 修订 · 基于《丘脑枕叶：视觉注意的皮层下路由器》(#197) · 新增与枕叶的对比（一阶 vs 高阶核）；新增 pulvinar 和 transthalamic-pathway 到 related；Casanova & Chalupa 2023 补充 · 置信度维持：高

## 来源文章

- [[2026-10-05-binocular-rivalry-consciousness-mechanism]]
- [[2026-06-17-pulvinar-visual-attention-router]]

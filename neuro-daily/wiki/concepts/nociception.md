---
title: 伤害感受（Nociception）
slug: nociception
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-14
updated: 2026-06-14
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit]
related: [gate-control-theory, pain-matrix, central-sensitization, trpv1, nav17, kcc2, spinal-cord-dorsal-horn]
prerequisites: [action-potential, ion-channels, synaptic-transmission]
opens_questions: [Q-pain-01]
source_articles: [2026-06-14-nociception-pain-pathways]
key_sources: ["PMID:21041958/PMC2964977", "PMID:22958566/PMC3438523"]
---

# 伤害感受（Nociception）

> **一句话定义**：外周感觉神经元对接近或超过组织损伤阈值刺激（热/机械/化学）的检测与脊髓初级处理过程；与"疼痛体验"可解离——无意识者有伤害感受但无疼痛，幻肢痛者有疼痛但无外周伤害感受。

## 当前理解

伤害感受是大脑痛觉构建过程的**第一个站点**，但不是疼痛的全部。组织损伤激活特化的伤害感受器（nociceptors），通过两类轴突（A-δ 快传导 / C 慢传导）将信号送入脊髓背角，在那里经过闸门控制（抑制性中间神经元调节）后上传至大脑。

**关键理解**：伤害感受器不是"痛觉接收器"的被动传导者，而是主动的分子探测装置，具有敏化、适应和调制能力。

## 关键机制

### 1. 伤害感受器纤维类型
| 纤维 | 髓鞘 | 传导速度 | 痛觉性质 | 典型受体 |
|------|------|---------|---------|---------|
| A-δ (I/II型) | 薄髓鞘化 | 5–30 m/s | 第一痛：锐利/刺痛 | TRPA1, 机械敏感通道 |
| C （多模态） | 无髓鞘 | 0.4–1.4 m/s | 第二痛：灼痛/持续钝痛 | TRPV1, TRPA1, Nav1.8/1.9 |

### 2. 分子感受器
- **TRPV1**：热敏感（激活阈值 ~43°C）+ 辣椒素 + 酸（质子）→ 热痛觉 + 炎症超敏的门户
- **TRPA1**：冷（<17°C）+ 芥末/氯/丙烯醛 → 化学性刺激痛觉；常与 TRPV1 共表达
- **Nav1.7**：电压门控 Na⁺ 通道；功能缺失突变 = 人类先天性无痛症（CIP）；功能增益突变 = 红斑性肢痛症（极度痛觉过敏）
- **Nav1.8/1.9**：仅在伤害感受器中表达；支持持续动作电位发放

### 3. 外周敏化（炎症后痛觉过敏的机制）
组织损伤释放"炎症汤"：缓激肽（bradykinin）、PGE₂、H⁺、NGF、5-HT、组胺
→ 这些介质降低 TRPV1/TRPA1 激活阈值，使本来不足以引发痛觉的温度/压力也触发放电
→ **原发性痛觉过敏**（primary hyperalgesia）的分子机制

### 4. 脊髓背角处理（第一个中枢站点）
伤害感受纤维在脊髓背角 I 和 II 板层（Rexed）释放谷氨酸（快速 AMPAR 激活）和 P 物质（慢速 NK1R 激活），激活投射神经元，同时受到抑制性中间神经元（GABA/甘氨酸能，即"闸门"）的调控 → 见 [[gate-control-theory]]

## 关键证据
| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| A-δ 5–30 m/s，C 0.4–1.4 m/s | 多物种电生理测量 | PMID:21041958/PMC2964977 | 高 |
| TRPV1 激活温度阈值 ~43°C | 异源表达系统 + 人类 C-MH 电生理 | PMC2964977 | 高 |
| Nav1.7 功能缺失 = 人类 CIP | 遗传家系 + 基因测序 | PMC2964977 | 高 |
| 炎症汤降低 TRPV1 阈值 | 行为+电生理+基因KO | PMC2964977 | 高 |

## 连接
- [[gate-control-theory]] — 脊髓第一个调制站点
- [[central-sensitization]] — 持续伤害感受导致的中枢增益上调
- [[kcc2]] — KCC2 下调导致脊髓闸门失效，是慢性痛的分子基础
- [[pain-matrix]] — 上行通路的皮层目标
- [[proprioception]] — 同为体感通路分支，与伤害感受共享部分脊髓回路

## 未解问题
- 见 state/unresolved_questions.md Q-pain-01（脊髓背角抑制性中间神经元精确亚型）

## 修订历史
- 2026-06-14 · 创建 · 基于《伤害感受≠疼痛体验》一文 #190 · 初始置信度：高

## 来源文章
- [[2026-06-14-nociception-pain-pathways]]

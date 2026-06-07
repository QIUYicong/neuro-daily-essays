---
title: 视网膜波
slug: retinal-waves
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-15
updated: 2026-08-15
revision_count: 1
dimensions: [molecular, cellular, microcircuit, brain-region, systems]
related: [ocular-dominance-columns, thalamocortical-axons, ltp, lgn, cortical-arealization]
prerequisites: [synaptic-transmission, action-potential]
opens_questions: [Q-retwave-01, Q-retwave-02]
source_articles: [2026-08-15-ocular-dominance-columns-visual-critical-period]
key_sources: ["PMID:22841309", "PMID:39036421"]
---

# 视网膜波 (Retinal Waves)

> **一句话定义**：哺乳动物胚胎期和新生期（小鼠约 P0–P14）视网膜神经节细胞（RGC）产生的自发、周期性、波浪状放电活动，不依赖光刺激，由内在视网膜回路（Stage II 乙酰胆碱能；Stage III 谷氨酸能）驱动；通过"同一眼邻近 RGC 的活动高度相关、不同眼 RGC 的活动不相关"的时空模式，为 LGN 的眼特异性分层和 V1 感受野地图形成提供活动依赖的 Hebbian 驱动力。

## 当前理解

我们现在认为，视网膜波是大脑在任何真实感觉经验到来之前，用内部自发活动来**预先调试视觉回路拓扑**的关键机制。视网膜波在 LGN 和皮层水平上均有重要功能，但两者的机制窗口有所不同。

**三个发育阶段**：
- **Stage I**（胚胎末期，~E17–P0，小鼠）：钙依赖，由无长突细胞（amacrine cells）连接驱动；空间范围小，波速慢
- **Stage II**（P0–P10，主要影响 LGN 分层）：β2-nAChR（烟碱型乙酰胆碱受体）依赖；邻近 RGC 同步放电，波以 ~400 μm/s 跨视网膜传播；这一阶段对 LGN 眼特异性分层最为关键
- **Stage III**（P10–P14，眼睛睁开前）：谷氨酸能驱动；空间模式更接近成熟视网膜活动

**为什么视网膜波有效**：同一眼内邻近的 RGC 被同一波"扫过"而同步放电 → 它们投射到 LGN 的突触前后同步激活 → Hebbian LTP（同步者增强）→ 同眼轴突在 LGN 中聚集。不同眼的 RGC 各有独立的波，时间相关性极低 → Hebbian LTD/竞争失败 → 不同眼轴突在 LGN 中被互斥分离。

## 关键机制

### 分子基础
- **Stage II 驱动分子**：β2-nAChR（无长突细胞到 RGC 的突触）；乙酰胆碱触发视网膜内自发波传播
- **Stage III 驱动分子**：谷氨酸能突触（双极细胞到 RGC）；波特性与 Stage II 不同

### 下游效应
1. **LGN 眼特异性分层**：β2-nAChR KO → Stage II 波消失 → LGN 眼特异分层严重破坏（Espinosa & Stryker 2012，PMID: 22841309）
2. **V1 视野地图精化**：视网膜波 + ephrin-A 梯度协同精化 V1 内的方位地图；双重缺失 → 地图几乎消失
3. **预分层 V1 ODC 雏形**：波使得眼特异性 LGN 神经元的轴突到 V1 Layer 4 也表现出相关性图案 → ODC 解剖前体出生前已部分形成

### 与感觉经验的关系
- 视网膜波发生在眼睛睁开**之前**，不依赖任何光刺激
- Stage II 波是遗传编码的"预先排练"——大脑用自发信号模拟真实视觉的时空相关结构
- 眼睛睁开后，真实视觉活动取代视网膜波，进一步精化回路（关键期 ODP）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| β2-nAChR KO → 视网膜波消失 → LGN 眼特异分层破坏 | 基因 KO + 解剖 + 电生理 | PMID:22841309 | 高 |
| 视网膜波 + ephrin-A 双重 KO → V1 视野图几乎消失 | 双重 KO + intrinsic imaging | PMID:22841309 | 高 |
| Stage III 波（~P10–P14）为谷氨酸能驱动 | 药理学 + 电生理 | 综述证据 | 中-高 |
| 视网膜波的扫过方向在 LGN 中诱发预测性的方向性激活 | 多电极阵列记录 | 多来源 | 中 |

## 连接

- [[ocular-dominance-columns]] — 视网膜波是 ODC 解剖前体的主要驱动力（LGN 预分层）
- [[thalamocortical-axons]] — 视网膜波驱动 LGN 眼特异性分层后，TCA 将该分层信息传递至 V1
- [[ltp]] — 视网膜波通过 Hebbian LTP 机制驱动 LGN 突触重组
- [[cortical-arealization]] — 视网膜波（视觉模态）与体感丘脑波竞争性决定皮层区域相对大小

## 未解问题

- Q-retwave-01（中优先级）：Stage III 视网膜波（谷氨酸能，P10–P14）在关键期开启中有何作用？是否通过影响 V1 Layer 4 突触成熟参与设定关键期时钟？
- Q-retwave-02（低优先级）：人类视网膜波的时间窗口？人类早产儿（在 Stage II 波尚未完成时分娩）的 LGN 分层是否与足月儿有差异？

## 修订历史

- 2026-08-15 · 创建 rev1 · 基于《左眼还是右眼》(#114) · 初始置信度：高

## 来源文章

- [[2026-08-15-ocular-dominance-columns-visual-critical-period]]

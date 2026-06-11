---
title: FGF8 皮层图案化
slug: fgf8-cortical-patterning
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-13
updated: 2026-08-13
revision_count: 1
dimensions: [molecular, cellular, brain-region]
related: [cortical-arealization, cortical-neurogenesis, growth-cone, axon-guidance]
prerequisites: [cortical-neurogenesis, cortical-layers]
opens_questions: []
source_articles: [2026-08-13-cortical-arealization-transcription-gradients]
key_sources: ["PMID:11567107", "PMID:18524571", "PMID:17509151"]
---

# FGF8 皮层图案化 (FGF8 Cortical Patterning)

> **一句话定义**：成纤维细胞生长因子 8（FGF8）由前方连合板/前神经嵴分泌，在发育皮层形成前高后低的形态素梯度，通过抑制 EMX2 和 COUP-TFI 在前方的表达，建立皮层前后轴的转录因子坐标系，是内在区域化蓝图的上游组织者。

## 当前理解

FGF8 是皮层区域化分子层级的顶端信号。在发育早期（小鼠 E9-12，人类 GW5-9 左右），**连合板（commissural plate）/ 前神经嵴（anterior neural ridge）** 作为皮层前方的信号中心，大量分泌 FGF8（以及 FGF17、FGF18）。FGF8 向后方皮层扩散，形成前高后低的浓度梯度。

FGF8 的主要效应是：
1. 在靠近信号中心的区域（将来的前额叶/运动皮层），抑制 EMX2 和 COUP-TFI 的表达
2. 这种抑制使 EMX2 和 COUP-TFI 呈现后高前低的梯度（与 FGF8 梯度相反）
3. FGF8 同时激活 ETS 家族转录因子（如 Etv4），参与前方皮层区域的命运决定

FGF8 的表达本身受 Sp8 转录因子的正反馈调节（Sp8 在前方皮层高表达，激活 FGF8 转录），而 EMX2 则在后方抑制 Sp8，防止 FGF8 信号后延——这形成一个空间上自组织的分子极性系统。

Fukuchi-Shimogori & Grove（2001, PMID:11567107）的体内电穿孔实验是迄今最直接的因果证据：在皮层后方引入异位 FGF8 来源 → 在正常桶皮层后方产生完整的第二套桶皮层拷贝；改变前方 FGF8 强度 → 所有感觉区域界限整体前移或后移。

## 关键机制

```
FGF8（前方高）
    ↓ 前方抑制
EMX2（后内侧高）        PAX6（前外侧高）
    ↓                        ↓
后方皮层命运              前方皮层命运
（V1, S1, A1）            （M1, PFC）
```

- **Sp8 正反馈**：Sp8（前高）→ 激活 FGF8 → FGF8 维持 Sp8 表达
- **EMX2 负反馈**：EMX2（后高）→ 抑制 Sp8 → FGF8 在后方不表达
- **净效果**：一个稳健的、自我维持的前后极性梯度系统

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| FGF8 直接移动区域界限 | 体内电穿孔异位 FGF8 → 桶皮层复制/移位 | PMID:11567107 | 高 |
| FGF8 抑制 EMX2/COUP-TFI 前方表达 | FGF8 低表达 → EMX2 前方扩张；FGF8 高表达 → EMX2 后缩 | PMID:18524571（综述） | 高 |
| Sp8 维持 FGF8 表达 | Sp8 KO → 前方 FGF8 减少 → 区域界限前移 | PMID:17509151 | 中 |

## 连接

- [[cortical-arealization]] — FGF8 是建立区域化坐标系的上游信号
- [[cortical-neurogenesis]] — 祖细胞阶段接受 FGF8 浓度信号并据此设置转录因子状态
- [[growth-cone]] — FGF 信号家族在轴突导向中也有作用（FGF 受体在生长锥上表达）

## 未解问题

（暂无高优先级开放问题）

## 修订历史

- 2026-08-13 · 创建 · 基于《皮层地图学》（文章 #112）· 初始置信度：高

## 来源文章

- [[2026-08-13-cortical-arealization-transcription-gradients]]

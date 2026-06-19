---
title: 低阈值机械感受器
slug: mechanoreceptor-ltmr
domain: neurons
type: structure
status: established
confidence: high
created: 2026-07-29
updated: 2026-07-29
revision_count: 1
dimensions: [molecular, cellular, behavior]
related: [somatosensory-cortex, action-potential, piezo2-channel, voltage-gated-sodium-channel]
prerequisites: [action-potential, ion-channels]
opens_questions: [Q-s1-03]
source_articles: [2026-07-29-s1-somatosensory-cortex-body-map-plasticity]
key_sources: ["PMID:23972592", "PMID:15730450"]
---

# 低阈值机械感受器 (Low-Threshold Mechanoreceptors, LTMRs)

> **一句话定义**：皮肤中专门响应轻触、振动和压力的感觉神经末梢，按适应速度（慢/快）和感受野大小（小/大）分为四类（SA1/SA2/RA1/RA2），是触觉信息传入大脑的第一站，其机械转导主要由 PIEZO2 离子通道介导。

## 当前理解

我们现在认为，皮肤的触觉分辨能力不来自单一感受器，而是由四类功能互补的 LTMR 并行编码的。每类 LTMR 专注于特定维度的机械刺激：SA1 擅长空间细节（纹理、形状边缘），RA1 擅长速度变化（滑动检测），SA2 感知皮肤大范围拉伸，RA2 感知高频振动（工具使用）。

Abraira & Ginty（2013, PMID:23972592）的综述提出，这四类 LTMR 的集成放电模式在**脊髓背角**就已经开始层级整合（"机械感觉柱"），而非全部延迟到皮层才整合。这重新定位了感觉分析的第一个中枢节点。

机械转导的分子基础：轻触、细振动主要依赖 **PIEZO2** 通道（机械门控的非选择性阳离子通道），在皮肤受压时由膜变形直接打开，无需第二信使，响应速度极快（<1 ms）。

## 关键机制

### 四类 LTMR 特性对比

| 类型 | 末梢结构 | 适应速度 | 感受野 | 最优频率 | 功能 |
|------|---------|---------|--------|---------|------|
| SA1 | Merkel 盘 | 慢适应 | 小（~2–3 mm²，指尖） | 5–15 Hz | 纹理、形状细节、持续压力 |
| SA2 | Ruffini 终末 | 慢适应 | 大（~10–15 cm²） | 低频持续变形 | 皮肤拉伸、手指位置（争议） |
| RA1 | Meissner 小体 | 快适应 | 小（~3–5 mm²，指尖） | 5–50 Hz | 滑动感、运动速度、抓握反射 |
| RA2 | Pacini 小体 | 快适应 | 大（数 cm²） | ~250 Hz（20–400 Hz） | 高频振动、工具传导震动 |

### 感受野密度与皮层放大

- 指尖：SA1 密度 ~140 个/cm²，RA1 密度 ~150 个/cm²
- 背部：SA1 密度 ~1 个/cm²
- 皮层放大因子与感受野密度正比 → 手指在 S1 中的表征面积远超背部
- 两点辨别阈（TPD）：指尖 ~2–3 mm；背部 ~40 mm

### 中枢投射

1. 脊髓背角 → 机械感觉柱（spinal mechanosensory columns）整合 LTMR 信号
2. 背柱-内侧丘系（DC-ML）通路 → 延髓 → 内侧丘系 → 丘脑 VPL → S1 (layer 4, 3b)

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 四类 LTMR 并行编码不同机械特性 | 人体微神经记录法（单纤维记录） | PMID:15730450 | 高 |
| 脊髓背角形成机械感觉整合柱 | 遗传标记 + 电生理（小鼠） | PMID:23972592 | 中-高 |
| PIEZO2 敲除导致触觉缺陷 | 条件性基因敲除小鼠 | （参考 Nobel Prize 2021 背景文献）| 高 |

## 连接

- [[somatosensory-cortex]] — LTMR 是 S1 触觉信息的外周来源
- [[action-potential]] — LTMR 将机械变形转化为动作电位
- [[thalamus]] — 经 VPL 中继进入皮层

## 未解问题

- Q-s1-03：SA2（Ruffini 终末）在人类本体感觉中的确切贡献——电生理证据稀少，争议存在

## 修订历史

- 2026-07-29 · 创建 · 基于《触觉的神经地图》文章（#97）· 初始置信度：高

## 来源文章

- [[2026-07-29-s1-somatosensory-cortex-body-map-plasticity]]

---
title: 方向选择性
slug: orientation-selectivity
domain: concepts
type: neural-property
status: established
confidence: high
created: 2026-06-11
updated: 2026-06-11
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, systems]
related: [v1-primary-visual-cortex, synaptic-clustering, dendritic-computation, nmda-receptor, pv-interneurons, sst-interneurons, short-term-synaptic-plasticity, ltp]
prerequisites: [action-potential, synaptic-transmission, nmda-receptor]
opens_questions: [Q-v1-orientation-column-advantage, Q-v1-mouse-random-mechanism, Q-v1-synaptic-clustering-universality]
source_articles: [2026-06-11-v1-orientation-selectivity]
key_sources: ["PMID:15660108", "PMC3477598", "PMID:22442071", "PMID:27383898", "PMID:23804085"]
---

# 方向选择性（Orientation Selectivity）

> **一句话定义**：神经元对特定方向的视觉刺激（光条、边缘、光栅）反应最强、对正交方向反应最弱的特性，是初级视觉皮层（V1）将非定向的 LGN 圆对称输入转化为方向特异性响应的核心计算成就。

## 当前理解

方向选择性（OS）是 V1 神经元最具代表性的功能特性之一，由 Hubel 和 Wiesel（1962）在猫 V1 中首次系统记录。

**量化指标**：方向选择性指数（OSI）= (Rpref - Rorth) / (Rpref + Rorth)，其中 Rpref 是偏好方向的响应，Rorth 是正交方向的响应。OSI = 1 表示对正交方向完全无响应，OSI = 0 表示无方向选择性。猫、猴和小鼠 V1 神经元的 OSI 中位数均约为 0.5-0.7，调谐半宽（半高半宽，HWHM）约为 20-30°。

**重要特性**：
- **对比度不变性**：调谐宽度（HWHM）不随刺激对比度变化，即使增加10倍对比度，调谐曲线的形状不变（仅幅度缩放）——这是 E/I 平衡的标志
- **速度调谐**：方向选择性通常伴随速度（temporal frequency）偏好，但方向和速度可以独立调谐

## 产生机制（三层模型）

### 1. 前馈机制（Hubel-Wiesel 模型）

多个 LGN 细胞（圆形感受野）的感受野中心沿视野中的某条直线排列，汇聚投射到同一 V1 简单细胞。当一条平行于该排列方向的光条出现时，能同时激活所有 LGN 输入，产生最大驱动；正交方向仅激活部分输入，驱动力弱。

**关键证据**：阈下膜电位记录显示，V1 神经元的阈下调谐已优于 LGN 输入（Priebe & Ferster 2012）；阈值非线性将其放大约 3 倍。

### 2. 皮层 E/I 平衡（van Vreeswijk-Sompolinsky 框架）

即使前馈输入仅提供弱的方向偏好"种子"，皮层内的循环连接（兴奋性锥体细胞 + 抑制性 PV+/SST+ 中间神经元）通过功能连接偏好（偏好相似方向的神经元间更强连接）将弱偏好放大为锐利调谐。

**关键预测**：这一机制在无方向图（小鼠盐-胡椒型）和有方向图（猫/猴方向柱）中均能实现等效的精确选择性（Hansel & van Vreeswijk 2012，PMC6621225）。

### 3. 跨方向抑制（LGN 非线性）

高对比度刺激使 LGN 反应趋于饱和；正交方向的叠加刺激所产生的额外抑制效果，等价于皮层的跨方向抑制。此机制部分由 LGN 而非皮层抑制性中间神经元介导（Priebe & Ferster 2006）。

### 4. 树突突触聚类（树突内计算）

Wilson 等（2016）发现，同向偏好的突触在树突分支上聚类，使局部 NMDA 棘波充当"与门"——只有相邻同向突触同时激活才能触发局部棘波，进一步增强方向选择性（→详见 [[synaptic-clustering]]）。这是一个在峰电位阈值之前发生的额外非线性增益层。

## 三种机制的关系

| 机制 | 主要证据物种 | 独立作用 | 作用阶段 |
|------|------------|---------|---------|
| 前馈 LGN 排列 | 猫/猴（主要）| 是（提供方向"种子"）| 突触前到阈值 |
| E/I 平衡放大 | 理论（猫/小鼠均适用）| 否（放大前馈偏好）| 皮层循环 |
| 树突 NMDA 棘波 | 雪貂（Wilson 2016）| 否（提供额外增益）| 峰电位阈值前 |

三者非互斥，而是协同分层作用：LGN 前馈提供"种子" → E/I 循环放大锐化 → 树突 NMDA 棘波进一步增益。

## 方向柱 vs 盐-胡椒型：相同计算，不同架构

| 参数 | 猫/猴（方向柱）| 小鼠（盐-胡椒型）|
|------|--------------|----------------|
| 空间组织 | 系统性方向图 | 随机分布 |
| 单细胞 OSI | 0.5-0.7 | 0.5-0.7（相似！）|
| 方向调谐宽度 | 约 25-30° HWHM | 约 25-35° HWHM |
| LGN 方向选择性 | 极弱 | 中等（Zhao 2013）|
| 推断的主要机制 | 前馈+E/I | E/I（+预先存在的LGN偏好）|

方向柱可能是布线经济（偏好相似方向的神经元间轴突最短路径）的优化结果，而非方向选择性计算本身的必要条件。

## 在视觉系统层级中的位置

方向选择性是从 LGN（无方向偏好）到 V1（强方向偏好）的功能跃升的核心。V2 之后的高级视觉区（V4、IT）进一步整合方向信息以实现形状、物体识别。CNN 的第一卷积层在自然图像上训练后自发学出 Gabor 状定向滤波器，与 V1 简单细胞高度收敛（Kindel 2019，PMC6485988）。

## 开放问题

- **Q-v1-mouse-random-mechanism**：小鼠 V1 单细胞方向偏好的决定因素——LGN 随机投射？发育活动？还是隐藏的微尺度组织？
- **Q-v1-orientation-column-advantage**：方向柱在方向计算之外提供什么优势？
- **Q-v1-synaptic-clustering-universality**：树突突触聚类增强方向选择性的机制在小鼠（无方向柱）V1 中是否依然存在？

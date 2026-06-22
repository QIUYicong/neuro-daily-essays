---
title: 腹侧视觉流
slug: ventral-visual-stream
domain: systems
type: structure
status: established
confidence: high
created: 2026-07-14
updated: 2026-08-29
revision_count: 2
dimensions: [brain-region, whole-brain-network, cognition]
related: [v1-primary-visual-cortex, inferior-temporal-cortex, object-recognition, cnn-visual-cortex-analogy, predictive-coding, dorsal-attention-network, entorhinal-cortex, hippocampal-circuit, biased-competition]
prerequisites: [v1-primary-visual-cortex, action-potential]
opens_questions: [Q-cnn-vc-01, Q-cnn-vc-02, Q-cnn-vc-03]
source_articles: [2026-07-14-cnn-visual-cortex-hierarchy, 2026-08-29-ventral-visual-stream-object-recognition]
key_sources: ["PMID:22325196", "PMID:24812127", "PMCID:PMC4060707", "PMID:25521294", "PMCID:PMC4270441", "PMID:31036945", "PMID:17631409", "PMID:20869601", "PMCID:PMC2946943", "PMID:32494012", "PMID:26906502"]
---

# 腹侧视觉流 (Ventral Visual Stream)

> **一句话定义**：腹侧视觉流（"what pathway"）是从 V1 经 V2、V4 延伸至颞下皮层（IT）的视觉信息处理层级，核心计算任务是将二维视网膜输入"解开纠缠"——使不同物体的神经表征变得线性可分，同时对物体的位置、大小、视角和光照保持不变性，实现核心物体识别。

## 当前理解

腹侧视觉流（ventral visual stream，或称"what pathway"）是视觉系统中负责物体识别和视觉形式处理的主要通路。从初级视觉皮层（V1）出发，信息依次经过 V2、V4，最终到达颞下皮层（IT），形成一个在感受野大小、特征复杂度和位置不变性上逐层升级的处理层级。

**关键计算框架**（DiCarlo, Zoccolan, Rust 2012, PMID:22325196）：腹侧流的核心任务是"解开纠缠"（untangling）——在 V1 中，同一物体在不同视角/位置下的神经表征高度纠缠（无法用线性分类器区分），而在 IT 皮层末端，这些表征已经线性可分。每个阶段都在同时做两件看似矛盾的事：扩大感受野（获取更多空间上下文）和精细化特征表征（从边缘到部件到物体身份）。

背侧流（"where/how pathway"，经 V1→MT→顶叶皮层）负责空间处理和运动引导行为，与腹侧流并行但互补。

## 关键机制

### 层级架构

| 脑区 | 感受野大小 | 典型特征偏好 | 不变性程度 |
|------|-----------|------------|-----------|
| V1 | 0.1–1° | 方向、空间频率、眼优势 | 极低（位置特异）|
| V2 | ~1–2° | 角度、曲率、轮廓连接 | 低 |
| V4 | ~2–8° | 中等复杂曲线、形状部件 | 中 |
| IT（后） | ~10–20° | 形状、纹理组合 | 中高 |
| IT（前） | ~50°或更大 | 物体身份（人脸、物体类别）| 高 |

### 前馈核心 + 循环调制

腹侧流的基础信号流是前馈的（V1→V2→V4→IT），处理速度约 100ms 内完成初始物体识别（前馈扫描）。但：
- 每一级都接受来自更高层的大量**反馈投射**（解剖上反馈和前馈连接数量相当）
- 对于困难图像（遮挡、低对比度、视觉歧义），额外需要约 30ms 的循环处理（Kar et al. 2019, PMID:31036945）
- 注意力调制（来自顶叶和前额叶的反馈）在腹侧流各级都产生显著的增益变化

### IT 皮层的线性可分性

IT 皮层的一个核心属性是其神经表征可以被简单的线性分类器读出——一个线性 SVM 在 IT 表征上识别物体的性能接近灵长类行为水平，而在 V1 上则接近随机水平。这意味着 IT 完成了识别所需的非线性变换，留给"输出层"（下游决策区域）的是一个简单的线性分类任务。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 腹侧流各级感受野大小和特征复杂度逐级增大 | 单细胞记录（猫、猕猴） | DiCarlo et al. 2012（PMID:22325196，综述）| 高 |
| IT 皮层神经表征线性可分（vs V1 接近随机）| 线性分类器在 IT/V1 表征上的性能对比 | Cadieu et al. 2014（PMID:25521294，PMCID:PMC4270441）| 高 |
| 困难图像识别需要额外 ~30ms 循环处理 | 神经错时图像学 + IT 时间分辨率 | Kar et al. 2019（PMID:31036945）| 高 |
| 目标优化的 CNN 中间层预测 V4，顶层预测 IT | 2000+ 网络 + 多电极 V4/IT 记录 | Yamins et al. 2014（PMID:24812127，PMCID:PMC4060707）| 高 |

## 连接

- [[v1-primary-visual-cortex]] — 腹侧流起点，方向/空间频率的前馈提取
- [[inferior-temporal-cortex]] — 腹侧流终点，物体身份表征（2026-08-29 页面已创建）
- [[cnn-visual-cortex-analogy]] — 腹侧流的计算结构与深度CNN的系统性类比
- [[predictive-coding]] — 腹侧流中反馈投射的预测编码解释
- [[dorsal-attention-network]] — 通过反馈调制腹侧流各级的注意力通路
- [[object-recognition]] — 腹侧流的核心计算目标（2026-08-29 页面已创建）
- [[entorhinal-cortex]] — 接收IT皮层的"what"输出，传入海马情节记忆系统
- [[hippocampal-circuit]] — IT→内嗅→海马：物体"what"与空间"where"在CA1的整合
- [[biased-competition]] — 注意如何在腹侧流中偏置物体竞争（IPS/FEF反馈→V4/IT）

## 未解问题

- **Q-cnn-vc-01**：反馈/循环连接在腹侧流中具体计算了什么？（预测精细化 vs 吸引子动力学 vs 注意调制）
- **Q-cnn-vc-03**：形状 vs 纹理偏见的皮层来源：IT 的形状偏见从哪一级开始形成？

## 修订历史

- 2026-07-14 · 创建 · 基于《镜中影像：CNN与灵长类视觉皮层层级对应》一文 · 初始置信度：高
- 2026-08-29 · 修订 · 基于《腹侧视觉流的"解缠"之旅》(#127) · 此前 related 中的悬空引用 inferior-temporal-cortex 和 object-recognition 已创建对应页面；新增 key_sources（Li & DiCarlo 2010, Yamins & DiCarlo 2016, Bao et al. 2020, DiCarlo & Cox 2007）；related 新增 entorhinal-cortex, hippocampal-circuit, biased-competition；source_articles 更新

## 来源文章

- [[2026-07-14-cnn-visual-cortex-hierarchy]]
- [[2026-08-29-ventral-visual-stream-object-recognition]]

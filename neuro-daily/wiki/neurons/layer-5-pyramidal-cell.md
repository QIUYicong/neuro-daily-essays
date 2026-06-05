---
title: 第 5 层厚簇型锥体细胞（PT 神经元）
slug: layer-5-pyramidal-cell
domain: neurons
type: structure
status: established
confidence: high
created: 2026-07-23
updated: 2026-07-23
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, cognition]
related: [neocortical-layers, cortical-column, canonical-microcircuit, predictive-coding, action-potential, voltage-gated-calcium-channels, apical-dendrite-computation, consciousness]
prerequisites: [action-potential, synaptic-transmission, voltage-gated-calcium-channels, neocortical-layers]
opens_questions: [Q-L5-01, Q-L5-02, Q-L5-03]
source_articles: [2026-07-23-neocortical-layers-columns-canonical-circuit]
key_sources: ["PMID:23273272", "PMID:25622573", "PMCID:PMC3394394", "PMID:1666655"]
---

# 第 5 层厚簇型锥体细胞（Layer 5 Thick-Tufted Pyramidal Cell / PT Neuron）

> **一句话定义**：新皮质第 5B 层的厚簇型锥体细胞（PT 型）是大脑皮层最大的兴奋性神经元，其胞体-轴突在 L5 处理前馈输入并投射到皮质下靶标，同时其顶端树突延伸至 L1 接收来自高级皮层的反馈预测信号——这种跨越皮层全部厚度的双区间结构，使单个细胞成为层级整合（前馈 × 反馈）的符合检测器，可能是哺乳动物皮层高级认知能力的关键细胞基础。

## 当前理解

我们现在认为，L5 PT（Pyramidal Tract）细胞的最重要特征不是其大尺寸或皮质下投射，而是其**跨层树突结构**所赋予的计算能力：

- **胞体（L5）**：接收来自 L2/3 的前馈皮层内输入和部分丘脑输入（POm 等非特异性核团）
- **顶端树突（L1）**：接收来自更高级皮层区域、内嗅皮层、杏仁核、基底前脑等的**反馈/调制**输入

Matthew Larkum 在 1999 年（*Nature*，DOI:10.1038/18686）和 2013 年（*Trends Neurosci*，PMID:23273272）证明，当这两种输入在时间上接近同步（约 5–10 ms 窗口）时，发生 **BAC（Backpropagation-Activated Ca²⁺ spike）放电**：前馈动作电位沿顶端树突反向传播，遭遇顶端树突内被反馈输入触发的钙平台电位，两者碰撞形成长达 50 ms 的去极化平台，回传到胞体驱动高频爆发放电（burst firing）。

这使 L5 PT 细胞成为一个物理意义上的**符合检测器**：只有当"来自下方的感觉前馈"与"来自上方的预期/预测"在时间上吻合，细胞才爆发性激活并向皮质下结构发出强信号。这是预测编码框架在单细胞水平的解剖实现。

## 关键机制

### 解剖结构
```
L1   ────────[顶端树突簇 apical tuft]────── 接收高级皮层反馈、5-HT、ACh
              │
L2/3 ─────────┤ 顶端树突干（apical trunk）
              │
L4   ─────────┤
              │
L5   ─────────[胞体 + 基础树突]───────────── 接收 L2/3 前馈 + POm 丘脑输入
              │
              └─── [轴突]→ 脑干 / 脊髓 / 上丘 / 纹状体（PT 投射）
```

### BAC 放电机制

1. **前馈输入**（胞体/基础树突）：L2/3 AMPA/NMDA 突触激活 → 局部去极化 → 胞体动作电位
2. **动作电位反向传播**：AP 沿顶端树突干向 L1 方向反向传播（backpropagating AP）
3. **反馈输入**（顶端树突簇 L1）：高级皮层/内嗅皮层输入 → 触发 L/N 型钙通道 → 钙平台电位
4. **BAC 符合**：反向传播 AP + 钙平台电位在时间上相遇（时间窗约 5–10 ms）→ 激活 CaV 通道爆发反应
5. **高频爆发**：去极化平台回传胞体 → 高频 AP 簇（5–15 Hz 以上）→ 突触前递质量大幅增加
6. **皮质下输出放大**：L5B 轴突突触对皮质下靶标（POm 等）具有高释放概率的"巨型突触"，4–8 个接触位点，足以单独触发靶细胞

### 与非 BAC 状态的比较

| 条件 | 前馈 | 反馈 | 胞体输出 |
|------|------|------|---------|
| 只有前馈 | ✓ | ✗ | 单个 AP，或稀疏放电 |
| 只有反馈 | ✗ | ✓ | 顶端树突局部活动，通常不产生胞体 AP |
| 前馈 + 反馈（非同步）| ✓ | ✓ | 正常放电 |
| **前馈 + 反馈（~同步）** | ✓ | ✓ | **BAC：高频爆发放电** |

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| L5B 厚簇型细胞顶端树突达 L1 | 形态重建（biocytin 填充）| PMCID:PMC3394394 | 高 |
| BAC 放电需前馈+反馈时间符合 | 体外脑片双区间刺激 + 钙成像 | PMID:23273272 | 高（体外，麻醉） |
| L5B 轴突对 POm 丘脑有"巨型突触"（高释放概率）| 配对记录 + 解剖 | PMCID:PMC3394394 | 高 |
| 清醒动物 L5 细胞爆发放电与感知相关 | 体内两光子 + 行为学 | （未读全文，间接引用 Larkum 2020）| 中 |
| IT/PT 分类的分子区分（Fezf2 等转录因子）| 单细胞 RNA-seq + CRISPR | PMID:25622573 | 高 |

## 连接

- [[neocortical-layers]] — L5 PT 细胞是六层结构中最具跨层整合特色的细胞类型
- [[canonical-microcircuit]] — 是 L4→L2/3→**L5B**（PT 输出）规范通道的终点节点
- [[predictive-coding]] — BAC 放电机制是预测编码"前馈误差 × 反馈预测 = 感知"的细胞级实现
- [[voltage-gated-calcium-channels]] — CaV1/CaV2 通道是顶端树突钙平台的分子基础
- [[thalamocortical-circuit]] — L5B 向 POm/MD 的反向投射形成 "高级丘脑-皮层回路"（second-order thalamus）

## 未解问题

- Q-L5-01（高优先级）：BAC 放电在清醒行为状态下的精确触发条件是什么？清醒状态下神经调质（ACh, NE）如何影响 BAC 阈值？现有体内证据仍不完整
- Q-L5-02（高优先级）：顶端树突 BAC 放电是否是感知意识报告（perceptual report）的**必要条件**？L5 PT 细胞的爆发放电与主观感知报告的因果关系是否可以用光遗传学直接测试？
- Q-L5-03（中优先级）：跨物种演化中，L5 PT 细胞顶端树突的长度（决定 BAC 整合的时间参数）是否与认知复杂度系统性相关？有初步证据（人 L5 树突最长），但大规模比较解剖学研究缺乏

## 修订历史

- 2026-07-23 · 创建 · 基于《新皮质六层算法》(#91) · 初始置信度：高（BAC 放电机制有力，但清醒体内证据仍需加强）

## 来源文章

- [[2026-07-23-neocortical-layers-columns-canonical-circuit]]

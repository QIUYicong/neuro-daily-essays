---
title: 逆向遮蔽
slug: backward-masking
domain: concepts
type: method
status: established
confidence: high
created: 2026-06-12
updated: 2026-06-12
revision_count: 1
dimensions: [cognition, methods, behavior]
related: [temporal-threshold-consciousness, access-consciousness, global-workspace-theory, recurrent-processing-theory, p300-component, visual-awareness-negativity]
prerequisites: [action-potential, v1-primary-visual-cortex, feedforward-processing]
opens_questions: [Q-temporal-02]
source_articles: [2026-06-12-temporal-threshold-consciousness-ignition]
key_sources: ["PMID:17896866", "PMID:15482443"]
---

# 逆向遮蔽 (Backward Masking)

> **一句话定义**：在目标刺激**之后**呈现一个掩蔽刺激（mask），从而截断目标刺激的后续神经处理，使其无法到达意识——是研究意识时间结构的最重要实验范式之一。

## 当前理解

逆向遮蔽（又称后向遮蔽）是视觉知觉和意识研究中使用最广泛的实验工具之一。与前向遮蔽（forwardmasking，掩蔽在目标之前）不同，逆向遮蔽的关键特点是：**掩蔽在目标之后到达**，却能有效阻止目标进入意识——这说明意识知觉不在目标刺激到达视网膜时即时发生，而是依赖**之后数十到数百毫秒内的持续神经处理**。

我们现在认为，逆向遮蔽的效果取决于**刺激起始同步时间（SOA，Stimulus Onset Asynchrony）**——目标与掩蔽之间的时间间隔：
- SOA 极短（<30ms）：目标与掩蔽几乎同时到达皮层，发生**能量遮蔽（pattern masking）**，即两者的表征重叠干扰。
- SOA 中等（30–100ms）：掩蔽到达时目标的前馈处理已经完成，但**递归处理/长程广播被截断**——这是最能精确控制意识出现的窗口。
- SOA 长（>100ms）：掩蔽到达时目标的神经处理已经足够建立意识；遮蔽效果减弱。

Del Cul et al. 2007（PMID:17896866）用系统变化的 SOA（16-100ms）揭示：意识产生的时间阈限约为 SOA = 43.9ms（平均），对应大脑处理层次约在 270ms 处发生非线性跃变。

## 关键机制

### 两种遮蔽机制

| 机制 | SOA | 作用位点 | 原理 |
|------|-----|---------|------|
| 能量遮蔽（Energy/pattern masking） | 极短（<30ms） | 视觉皮层（V1-V2） | 目标与掩蔽的视觉能量重叠，干扰初级皮层表征 |
| 反向馈送遮蔽（Feedback masking） | 中等（30-100ms） | V4→V1 的反馈通路 | 掩蔽触发的高级区域激活发出反馈信号，干扰目标正在进行的递归处理 |

GWT 解释：逆向遮蔽截断了目标进入全局工作空间所需的 >270ms 额顶颞激活。  
RPT 解释：逆向遮蔽截断了视觉皮层内的递归回路（~100-200ms 阶段），使图像-背景分离信号无法完成。

### 时间窗口与神经活动

```
目标呈现
   ↓ 0ms
V1 初始激活（~17ms）——前馈扫描开始
   ↓ 50-100ms
V2/V4/IT 激活——前馈已完成，类别识别已发生
   ↓ SOA（43ms 平均阈限）
掩蔽呈现 ← 此时后向遮蔽截断了：
   - 目标的递归/反馈回路（RPT 机制）
   - 目标进入全局工作空间的长程广播（GWT 机制）
   ↓
结果：目标的 P3 波消失；被试报告"未看见"
```

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| P3（270-370ms）是唯一对 SOA 变化表现出 Sigmoid 非线性的 EEG 成分 | EEG + 逆向遮蔽，SOA 系统变化 | Del Cul et al. 2007, PLoS Biol (PMID:17896866) | 高 |
| 意识知觉呈全有或全无分布（双峰，非连续梯度） | 注意瞬脱 + 逆向遮蔽范式 | Sergent & Dehaene 2004 (PMID:15482443) | 中（有争议） |
| 逆向遮蔽截断了图像-背景分离信号（V1 的延迟递归成分） | 猕猴 V1 电生理 + 遮蔽 | Lamme & Roelfsema 2000 (PMID:11074267) | 中 |

## 连接

- [[temporal-threshold-consciousness]] — 逆向遮蔽是研究意识时间门槛的核心工具
- [[global-workspace-theory]] — GWT 解释遮蔽截断全局广播
- [[recurrent-processing-theory]] — RPT 解释遮蔽截断递归处理
- [[access-consciousness]] — 遮蔽消除的是通达意识还是现象意识？（关键争议）
- [[visual-awareness-negativity]] — VAN 成分在遮蔽条件下的行为

## 未解问题

- Q-temporal-02：在无报告范式中，逆向遮蔽是否同样能消除 VAN（Visual Awareness Negativity）？
- 如果掩蔽能消除报告但 VAN 仍存在，则支持 RPT（现象意识早于通达意识）

## 修订历史

- 2026-06-12 · 创建 · 基于《意识的时间解剖学》文章 #162 · 初始置信度：高

## 来源文章

- [[2026-06-12-temporal-threshold-consciousness-ignition]]

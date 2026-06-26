---
title: 睡眠两进程模型
slug: two-process-model
domain: concepts
type: theory
status: established
confidence: high
created: 2026-10-13
updated: 2026-10-13
revision_count: 1
dimensions: [molecular, cellular, behavior, cognition, whole-brain-network]
related: [adenosine, circadian-clock, slow-wave-sleep, flip-flop-switch-sleep-wake, rem-sleep, memory-consolidation, glymphatic-system]
prerequisites: [circadian-clock, adenosine, slow-wave-sleep]
opens_questions: [Q-aden-03]
source_articles: [2026-10-13-adenosine-sleep-homeostasis-process-s]
key_sources: ["PMID:7185792", "PMID:31236513"]
---

# 睡眠两进程模型 (Borbély Two-Process Model of Sleep)

> **一句话定义**：Borbély（1982）提出的睡眠调控框架：睡眠时机与深度由 Process S（内稳态睡眠压力，随清醒时间积累，随睡眠慢波活动消减；分子实体为腺苷）和 Process C（昼夜节律，由 SCN 产生的~24 h 振荡）的动态叠加共同决定——仅当 S 足够高且 C 不再主动对抗睡眠时，入睡才发生。

## 当前理解

我们现在认为，两进程模型是理解睡眠时机和深度的核心框架。它的核心洞察在于：睡眠不仅是"白天/黑夜"的节律现象（Process C），也不仅是"累了就睡"（Process S），而是两个独立调控维度的**实时动态平衡**。

**Process S（内稳态，Homeostatic）**：
- 在清醒状态下**线性积累**（线性增长），在睡眠（特别是 NREM 慢波睡眠）中**指数衰减**
- 分子实体：基底前脑细胞外腺苷浓度（Porkka-Heiskanen 1997，PMID:9157887）
- 行为指标：NREM 慢波活动（SWA，0.5–4 Hz EEG 功率）精确反映 S 的当前值
- 预测：睡眠剥夺后 S 高 → 恢复睡眠中 SWA 增强（"慢波反弹"）→ S 快速消减

**Process C（昼夜节律，Circadian）**：
- 来自视交叉上核（SCN）分子振荡器（TTFL：CLOCK/BMAL1 → PER/CRY 负反馈回路）
- 在白天主动维持清醒（"对抗" S）；在黑夜和傍晚后允许睡眠发生
- 与 S 的协同：C 的"睡眠允许窗口"（大约20:00–06:00）与积累的 S 叠加，触发可靠的入睡
- 与 S 的互作：高 S（高腺苷）可减弱 SCN 对光照的敏感性；强 C（健康节律）促进更深 NREM 睡眠 → 加速 S 消减（Deboer 2018，PMID:31236513）

**模型的结合点**：
入睡发生在 S 超过"入睡阈值"且 C 不再主动上推清醒的时刻。这两个条件的同时满足创造了每日规律的"睡眠窗口"。这也解释了：
- 为什么昼夜工作者（轮班制）难以入睡：S 积累但 C 仍在峰值
- 为什么傍晚打盹会推迟当晚入睡：S 被部分消减，夜间需要更长时间才能再次超过阈值

## 关键机制

### Process S 的动力学

Process S 在清醒时以指数接近法（约 18–20 h 时间常数）积累；在 NREM SWS 睡眠时以约 4 h 时间常数消减。

Borbély 的原始 EEG 验证：延长清醒（36 h）后，恢复睡眠的前几个小时 SWA 比正常夜晚高出 30–50%；随后的恢复夜晚 SWA 逐渐恢复正常水平，与 S 从高值消减相吻合。

### Process C 的波形

Process C 的促清醒驱动在约 18:00–21:00 达到峰值（称为"Forbid zone"——人类自然很难在这个时段入睡），然后迅速下降，在夜晚与 S 协同，最终在清晨（约 04:00–06:00 觉醒时间）再次上升。

### 两进程的相互调制

两进程不是完全独立的（Deboer 2018）：
- 强昼夜节律（健康 SCN 振荡）→ 更深 NREM（更强 SWA）→ Process S 消减更快
- 高 Process S（高腺苷浓度）→ 减弱 SCN 神经元对光照的响应 → 昼夜节律光迁移减慢

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 清醒时长与 SWA 正相关 | EEG 测量不同睡眠剥夺持续时间后的 SWA 反弹 | PMID:7185792 | 高 |
| 腺苷是 Process S 的分子实体 | 基底前脑微透析腺苷随清醒线性增加 | PMID:9157887 | 高 |
| Process S + C 互相调制 | 睡眠剥夺+光照迁移实验 | PMID:31236513 | 中 |
| 两进程模型预测昼夜节律睡眠时机 | 数学模型与 polysomnography 数据拟合 | PMID:7185792 | 高 |

## 连接

- [[adenosine]] — Process S 的分子实体：腺苷积累 = 内稳态睡眠压力
- [[circadian-clock]] — Process C 的分子实体：SCN TTFL 振荡器
- [[slow-wave-sleep]] — SWA（慢波活动）是 Process S 当前值的 EEG 指标，也是 S 消减的主要途径
- [[flip-flop-switch-sleep-wake]] — 两进程共同驱动双稳触发器的翻转时机
- [[rem-sleep]] — REM 睡眠有自己的内稳态调控（REM 压力），但与 NREM 的 Process S 机制不同
- [[memory-consolidation]] — Process S 驱动的 SWA 反弹是记忆巩固的必要条件

## 未解问题

- **Q-aden-03（中优先级）**：Process S 是否仅由腺苷一种分子编码？前列腺素 D₂、DSIP 等其他睡眠因子与腺苷的关系？

## 修订历史

| 版本 | 日期 | 变化 | 来源文章 |
|------|------|------|---------|
| rev1 | 2026-10-13 | 初始页面建立：两进程框架（Borbély 1982）、Process S（腺苷）与 Process C（SCN）、相互调制（Deboer 2018） | #173 |

## 来源文章

- [[2026-10-13-adenosine-sleep-homeostasis-process-s]]

---
title: 统计学习（语言习得）
slug: statistical-learning
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-22
updated: 2026-08-22
revision_count: 1
dimensions: [cognition, behavior, cellular]
related: [language-critical-period, phoneme-categorical-perception, social-gating-language, language-network]
prerequisites: [language-network]
opens_questions: [Q-sl-01]
source_articles: [2026-08-22-language-acquisition-critical-period]
key_sources: ["PMID:8943209", "PMID:19284661", "PMID:37344237", "PMID:15496861"]
---

# 统计学习（语言习得）(Statistical Learning in Language Acquisition)

> **一句话定义**：婴儿（以及成人）大脑能够在无监督条件下，从连续语音流中隐式计算相邻元素的转移概率，并利用这些统计规律提取词语、音素范畴和语法规律，这一能力从出生起即可运转。

## 当前理解

统计学习是语言习得的基础计算工具，但它是语言专属的，还是域通用的（亦适用于视觉序列、音乐等），目前仍有讨论。

核心证据：
- 8月大婴儿能从2分钟人工语言中提取词（Saffran 1996）——证明这是高效的早期能力
- 睡眠中的新生儿（ERP）已能追踪统计词边界（Teinonen 2009）——证明无需后天学习
- 婴儿能从双峰分布（bimodal）vs.单峰分布（unimodal）中学习音素范畴（Kuhl 2004）——统计分布形状驱动范畴形成

**统计学习的局限**：单独的统计学习（无社会互动）不足以习得语言：
- 通过电视/录音接触语音，统计结构完全相同，但婴儿学习效果等于零（社会门控实验）
- 这说明统计学习需要社会"门控"才能在语言习得中高效运作（→[[social-gating-language]]）

## 关键机制

### 转移概率学习（Transitional Probability Learning）
- 词内相邻音节转移概率高（如"baby"：ba→bi 概率高）
- 词间转移概率低（"ba"→下一词首音节概率低）
- 大脑隐式追踪这些概率差异，将高概率序列识别为"词"

### 分布学习（Distributional Learning）
- 语音范畴形成与语音在输入中的频率分布有关
- 双峰分布（两个峰，对应两个范畴）比单峰分布（单峰，跨范畴）更快诱导范畴分化
- 婴儿大脑"投票"给最有信息量的声学特征

### 规则提取（Rule Extraction）
- 超越相邻统计：婴儿能提取非相邻依赖规则（ABB型 vs ABA型序列，约4个月）
- 新生儿：相邻依赖规则（最简单层级）
- 婴儿后期：非相邻依赖规则（需要更复杂的工作记忆）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 8月婴儿2分钟内学会统计词分割 | 头转偏好测试，人工语言 | PMID:8943209 | 高（多实验室重复） |
| 新生儿睡眠中统计词边界学习 | ERP，3天大新生儿 | PMID:19284661 | 中（需更多重复） |
| 婴儿从分布形状学音素范畴 | 头转偏好，双峰vs单峰刺激 | PMID:15496861 综述 | 高 |
| 统计学习需社会门控才能有效 | 真人vs录像随机实验 | PMID:17181708 | 高 |

## 连接

- [[language-critical-period]] — 统计学习是语言关键期的计算引擎
- [[phoneme-categorical-perception]] — 分布学习驱动音素范畴的形成和维持
- [[social-gating-language]] — 统计学习的效率依赖社会门控

## 未解问题

- Q-sl-01：统计学习是语言专属机制，还是域通用学习机制（同样驱动视觉序列学习、音乐节奏等）的语言应用？若域通用，语言的特殊性来自何处？

## 修订历史

- 2026-08-22 · 创建 · 基于《语言习得关键期》文章#120 · 初始置信度：高

## 来源文章

- [[2026-08-22-language-acquisition-critical-period]]

---
title: 髓鞘化
slug: myelination
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-07
updated: 2026-09-07
revision_count: 1
dimensions: [cellular, molecular, microcircuit, brain-region, cognition]
related: [oligodendrocyte, activity-dependent-myelination, action-potential, axon-initial-segment, critical-period, hebbian-learning, ltp]
prerequisites: [action-potential, axon-initial-segment, oligodendrocyte]
opens_questions: [Q-myelin-01, Q-myelin-02, Q-myelin-03]
source_articles: [2026-09-07-activity-dependent-myelination-white-matter-plasticity]
key_sources: ["PMID:26585800", "PMID:28817797", "PMID:24727982", "PMID:34618550"]
---

# 髓鞘化 (Myelination)

> **一句话定义**：髓鞘化是少突胶质细胞将自身细胞膜反复包裹轴突节段、形成多层脂质绝缘鞘（髓鞘）的过程，使动作电位以跳跃传导方式高速传播，同时精确控制神经元回路的信号传导时序。

## 当前理解

髓鞘（myelin）是中枢神经系统白质的核心组成。髓鞘节段（internode）与郎飞结（Node of Ranvier）交替分布：
- **节段内**：高电阻、低电容的髓鞘绝缘，电流损失最小
- **郎飞结**：Na⁺ 通道密集，动作电位在此再生（amplify）
- **结果**：跳跃传导（saltatory conduction），速度 50–200 m/s

**无髓纤维速度**：<2 m/s（相差约 100 倍）。人类胼胝体有髓：~30 ms 双侧传导；若失髓鞘：~300 ms。

### 髓鞘化的两大功能

| 功能 | 机制 | 证据 |
|------|------|------|
| **速度与时序**：精确控制信号到达时间，影响神经元同步和 STDP | 髓鞘厚度决定传导速度；1 ms 延迟差 → 30° gamma 相位偏移 | 谷仓猫头鹰声音定位（微秒精度）；Bonetto 2021 计算模型 |
| **代谢支持**：向高能耗轴突提供乳酸等能量底物 | 少突胶质细胞通过 MCT1 向轴突输送乳酸 | MCT1 KO 小鼠轴突退化（不失髓鞘即退化） |

### 发育时程

髓鞘化在人类从妊娠晚期持续到成年期（甚至到 40–50 岁），不同区域时程差异巨大：
- 感觉/运动皮层：出生后 1–2 年基本完成
- 前额叶联合皮层：持续到 20–25 岁
- 白质连接（如胼胝体）：贯穿童年和青春期

这种时程差异与认知发育（注意控制、冲动抑制、执行功能）的成熟时程吻合，暗示前额叶髓鞘化是青春期延迟成熟的生物学基础之一。

### 活动依赖性调节

髓鞘化并非纯粹由遗传程序决定的静态过程，而是对神经元活动动态响应的可塑过程 → 见 [[activity-dependent-myelination]]。

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| 髓鞘化大幅提高传导速度 | 有髓 vs 无髓纤维速度对比（电生理直接测量） | 经典神经生理学（多实验室） | 极高 |
| 髓鞘化精确调控时序/同步 | 谷仓猫头鹰双耳延迟调节（微秒精度）；计算模型：1ms→30° gamma 偏移 | Fields 2015; Bonetto 2021 (PMID:26585800, PMID:34618550) | 中高 |
| 少突胶质细胞提供轴突代谢支持 | MCT1 KO 轴突退化而不失髓鞘结构 | Fields 2015 综述 (PMID:26585800) | 高 |
| 髓鞘化影响学习和认知 | Mrf KO（阻断髓鞘化）→ 运动学习障碍；OPC 抑制→运动改善消失 | de Faria 2017; Gibson 2014 (PMID:28817797, PMID:24727982) | 高（因果） |
| 前额叶髓鞘化持续到 20s | MRI/DTI 纵向研究、尸脑髓鞘染色 | 多项人类发育研究（Fields 2015 综述） | 高 |

## 连接

- [[oligodendrocyte]] — 少突胶质细胞是髓鞘的形成者
- [[activity-dependent-myelination]] — 髓鞘化的活动依赖性调控亚类
- [[action-potential]] — 动作电位的传播速度由髓鞘决定
- [[critical-period]] — 白质髓鞘化也存在经验敏感的关键期
- [[ltp]] — 髓鞘化影响 STDP 时窗，与 LTP 交互
- [[hebbian-learning]] — 活动依赖性髓鞘化是 Hebbian 原则在白质层面的体现

## 未解问题

- **Q-myelin-01**：髓鞘化的时序功能 vs 代谢支持功能，哪个对认知更关键？
- **Q-myelin-02**：人类 DTI 观察到的"2h 学习后白质变化"具体是什么生物过程？
- **Q-myelin-03**：白质个体差异（DTI FA 值）有多大程度因果性解释认知差异？

## 修订历史

- 2026-09-07 · 创建 · 基于《白质的秘密语言》(#124) · 基础髓鞘化机制页面；覆盖速度/时序/代谢支持/发育时程；established，高置信度

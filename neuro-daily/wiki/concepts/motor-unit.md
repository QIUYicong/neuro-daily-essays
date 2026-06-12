---
title: 运动单元
slug: motor-unit
domain: concepts
type: concept
status: established
confidence: high
created: 2026-10-08
updated: 2026-10-08
revision_count: 1
dimensions: [cellular, microcircuit, behavior]
related: [alpha-motor-neuron, size-principle, persistent-inward-currents, neuromuscular-junction]
prerequisites: [alpha-motor-neuron, action-potential]
opens_questions: [Q-mu-01]
source_articles: [2026-10-08-alpha-motor-neuron-size-principle]
key_sources: ["PMID:14328454", "PMID:23720261"]
---

# 运动单元 (Motor Unit)

> **一句话定义**：一个 α运动神经元及其通过神经肌肉接头所支配的全部肌纤维的总和，是神经肌肉系统的最小可控单元——单个 α-MN 的放电必然导致其所有靶肌纤维同步收缩。

## 当前理解

我们现在认为，运动单元是将神经命令转化为肌肉力量的最基本功能模块。大脑无法单独控制某块肌肉中的某一根肌纤维，只能以"运动单元"为最小粒度进行控制。

**神经支配比**（一个 α-MN 支配的肌纤维数）决定了运动单元的力量分辨率：
- 眼外肌：5–15 根/MN（极高精度）
- 手内肌（第一骨间背侧肌）：约 100–150 根/MN
- 腓肠肌（小腿）：约 1,000–2,000 根/MN（力量导向，精度低）

**三类运动单元的系统分类**来自 Burke et al. 1973 等经典研究（综述见 Heckman & Enoka 2012, PMID:23720261）：
- **S 型（Slow）**：慢速收缩、氧化代谢、高抗疲劳性、小峰值力量，最先被招募（大小原则），适合姿势维持
- **FR 型（Fast-Resistant）**：中速收缩、混合代谢、高抗疲劳性、中等力量
- **FF 型（Fast-Fatigable）**：快速收缩、糖酵解、低抗疲劳性、大峰值力量，最后被招募，适合爆发动作

力量调控依赖两种机制的同时使用：
1. **招募编码（recruitment coding）**：增加活跃运动单元的数量
2. **频率编码（rate coding）**：增加已激活运动单元的放电频率

两者均由大小原则组织，并受持续内向电流（PICs）的非线性放大。

## 关键机制

### 解剖结构

```
α运动神经元（胞体位于脊髓前角）
    → 运动轴突（前根出脊髓）
        → 分支到多根肌纤维
            → 神经肌肉接头（释放 ACh → 触发肌纤维动作电位 → 收缩）
```

### 同步性

一个运动单元内的所有肌纤维**完全同步**（同一 α-MN 放电 → 全部肌纤维在约 1–5 ms 内相继激活）。但不同运动单元通常**不同步**，这种"去同步化"（asynchrony）是平滑肌肉收缩的关键——多个运动单元轮流激活，避免了单一抽搐（twitch）的颤抖感。

### 疲劳特性

- S 型：依靠氧化磷酸化，几乎不疲劳（姿势肌可连续工作数小时）
- FR 型：混合代谢，数分钟到数十分钟才疲劳
- FF 型：依靠快速糖酵解，数十秒到几分钟内疲劳，乳酸积累是主要原因

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 运动单元三类分型（S/FR/FF）及其生理-组化对应 | 猫腓肠肌完整 MU 追踪（MN 电生理 + 肌纤维 PAS + ATP酶组化） | Burke 1973，综述 PMID:23720261 | 极高 |
| 大小原则决定招募顺序 | 猫脊髓 α-MN 导电速度（代理大小）与阈值相关性 | PMID:14328454 | 极高 |
| 神经支配比与精度的反比关系 | 解剖计数 + EMG 分解研究 | 综述 PMID:23720261 | 极高 |

## 连接

- [[alpha-motor-neuron]] — 运动单元的神经元核心
- [[size-principle]] — 决定运动单元招募顺序的物理规则
- [[persistent-inward-currents]] — α-MN 的内在放大机制，影响运动单元输出增益
- [[neuromuscular-junction]] — 神经元与肌纤维之间的突触（悬空引用，待补）

## 未解问题

- Q-mu-01（低）：人类活体中三类运动单元的精确数量比例（不同肌肉之间差异大）

## 修订历史

- 2026-10-08 · 创建 · 基于《最终公共通路》（#168）· 初始置信度：高

## 来源文章

- [[2026-10-08-alpha-motor-neuron-size-principle]]

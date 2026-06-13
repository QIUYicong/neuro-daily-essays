---
title: 自身抑制
slug: autogenic-inhibition
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-13
updated: 2026-06-13
revision_count: 1
dimensions: [synaptic, microcircuit, behavior]
related: [golgi-tendon-organ, alpha-motor-neuron, stretch-reflex, spinal-cord-cpg, proprioception, reciprocal-inhibition]
prerequisites: [action-potential, synaptic-transmission, alpha-motor-neuron, golgi-tendon-organ]
opens_questions: [Q-gto-03]
source_articles: [2026-06-13-golgi-tendon-organ-ib-autogenic-inhibition]
key_sources: ["PMID:1626033", "PMID:10899663", "PMID:14653157", "PMID:1929231"]
---

# 自身抑制 (Autogenic Inhibition)

> **一句话定义**：肌肉的高尔基腱器官（GTO）Ib 型传入激活脊髓 Ib 抑制性中间神经元，后者通过甘氨酸能突触抑制同肌（及协同肌）α 运动神经元，使肌肉在张力增大时产生反射性抑制——也称"逆肌牵张反射（inverse myotatic reflex）"，与肌梭介导的牵张反射方向相反。

## 当前理解

我们现在认为，自身抑制不是一个固定的"安全阀"机制，而是一个**行为状态依赖的可切换回路**：

- **静息/摆动相**：Ib 传入激活抑制性中间神经元 → 同肌 α-MN 受抑制（经典自身抑制）
- **步行站立相**：Ib 抑制性通路被 CPG 下行信号关闭，Ib 兴奋性通路激活，同一批 GTO 信号转变为延长站立相的兴奋性信号

"逆肌牵张反射"的描述仅代表静息状态下的默认模式；完整理解必须包含步态中的状态切换。

## 关键机制

### 回路结构

```
GTO Ib 传入
    ↓
Ib 抑制性中间神经元（脊髓中间区）
    ↓ 甘氨酸能（glycinergic）
同肌 α-MN（受抑制）    拮抗肌 α-MN（受激活）
```

- 至少双突触（disynaptic）连接
- Ib 中间神经元同时接受来自 Ia 传入、皮层脊髓束、网状脊髓束的收敛输入
- 与肌梭单突触牵张反射形成功能对应：张力增大→自身抑制 vs 长度增加→牵张反射

### 与牵张反射的对比

| 特性 | 牵张反射（肌梭 Ia）| 自身抑制（GTO Ib）|
|------|-----------------|----------------|
| 传感器 | 肌梭（并联）| GTO（串联）|
| 刺激 | 肌肉拉伸 | 肌肉张力增加 |
| 效果 | 兴奋同肌 α-MN | 抑制同肌 α-MN |
| 突触数 | 单突触 | 至少双突触 |
| 步态调制 | Ia 在摆动相被前突触抑制 | Ib 在站立相被相位切换 |

### 临床测量方法

H 反射范式（以比目鱼肌为例）：
1. 刺激腓肠肌内侧神经（激活 Ib 传入）
2. 条件刺激后 3–8ms 测量比目鱼肌 H 反射
3. 正常：显著抑制（峰值 5ms）
4. 帕金森患者：抑制减弱（Delwaide 1991）
5. 脊髓损伤：抑制保留（Downes 1995，证明回路完全在脊髓内）

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| Ib 自身抑制为双突触回路 | 猫脊髓电生理 | PMID:1626033 | 高 |
| 帕金森病 Ib 抑制减弱 | 人类 H 反射范式 | PMID:1929231 | 高 |
| 脊髓损伤 Ib 抑制保留 | 人类 H 反射范式 | PMID:7675233 | 高 |
| 步行站立相 Ib 抑制→兴奋切换 | 步行电生理 + 切断实验 | PMID:10899663 | 高 |

## 连接

- [[高尔基腱器官]] — 自身抑制的传感器来源（GTO Ib 传入）
- [[α运动神经元]] — 被抑制的目标
- [[牵张反射]] — 功能上相对的脊髓反射（肌梭 Ia 介导的兴奋性）
- [[脊髓中枢模式发生器]] — 调制 Ib 通路的相位切换
- [[本体感觉]] — 自身抑制在更宽本体感觉框架中的角色

## 未解问题

- 见 Q-gto-03：站立相 Ib 切换的具体脊髓中间神经元身份尚待光遗传学验证

## 修订历史

- 2026-06-13 · 创建 · 基于《肌肉力量的精确传感器》(#174) 文章 · 初始置信度：高

## 来源文章

- [[2026-06-13-golgi-tendon-organ-ib-autogenic-inhibition]]

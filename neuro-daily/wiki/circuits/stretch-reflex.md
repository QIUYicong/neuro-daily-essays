---
title: 牵张反射弧
slug: stretch-reflex
domain: circuits
type: mechanism
status: established
confidence: high
created: 2026-06-13
updated: 2026-06-13
revision_count: 1
dimensions: [cellular, synaptic, microcircuit, behavior]
related: [muscle-spindle, alpha-motor-neuron, gamma-motor-neuron, golgi-tendon-organ, ia-inhibitory-interneuron, renshaw-cell, presynaptic-inhibition-ia, spinal-cord-cpg, corticospinal-tract, somatosensory-cortex-3a, spinal-interneurons-locomotion, motor-cortex]
prerequisites: [muscle-spindle, alpha-motor-neuron, gamma-motor-neuron, synaptic-transmission, action-potential]
opens_questions: [Q-stretch-01, Q-stretch-02, Q-stretch-03]
source_articles: [2026-06-13-stretch-reflex-arc]
key_sources: ["PMID:5540547", "PMID:11351007", "PMID:16716488", "PMID:26446220", "PMID:24636954"]
---

# 牵张反射弧 (Stretch Reflex Arc)

> **一句话定义**：哺乳动物神经系统中**唯一的单突触反射**——当肌肉被拉伸时，Ia 传入纤维直接（无中间神经元）激活同名肌和协同肌的 α 运动神经元，产生抗拒牵张的肌肉收缩；其增益由互反抑制、复现抑制、突触前抑制和 γ 运动神经元四重机制动态调控，在不同运动状态下可被下行系统根本性地重配置。

## 当前理解

我们现在认为，牵张反射弧虽然是脊髓中最简单的回路，却是一个**高度可调的感觉-运动伺服系统**，而非固定的硬连线电路。

核心电路由两个元件构成：（1）肌梭的 Ia 传入纤维检测肌肉牵张速度，（2）Ia 纤维直接接触同名肌 α-MN，产生单突触 EPSP，驱动肌肉收缩以抵抗牵张。这个基本弧的延迟约为 25–35 ms（人类下肢），是所有反射中最快的，因为它仅需一个中枢突触。

但真正使牵张反射弧功能丰富的是嵌套在其中的三种制动机制：互反抑制（Ia INs 抑制拮抗肌，Eccles 等 1956 最早描述）、复现抑制（Renshaw 细胞提供 α-MN 自我负反馈，Moore 等 2015 提供突触分辨率证据）、突触前抑制（PAD 机制减少 Ia 终末量子释放，Rudomin 2002 综述）。三种机制共同限制反射增益，防止运动系统振荡失控。

更深刻的发现来自 Hultborn（2001）：反射的增益不只是"可以被调小"，其**极性本身可以反转**。在步态 CPG 激活的状态下，同样的 Group I 传入可以兴奋（而非抑制）伸肌运动神经元——这表明脊髓中间神经元是"功能单元"而非独立回路，其状态决定了感觉输入的路由方向。

此外，牵张反射具有**突触可塑性**：通过操作性条件反射，H反射（单突触牵张反射的电生理等价体）的振幅可在数周内改变 20–35%，改变发生在脊髓内部，但需要完整的皮层-脊髓通路才能建立（Wolpaw & Thompson 系列，2015–2023）。

## 关键机制

### 基本回路

```
肌梭 → Ia 传入纤维 (12–20 μm, 70–120 m/s)
    → 脊髓腹角
    → α-MN 单突触 EPSP（谷氨酸/AMPA）
    → 骨骼肌收缩（抵抗牵张）

同时：Ia → Ia抑制性中间神经元 → 拮抗肌 α-MN 的 IPSP（互反抑制）
```

### 单根 Ia 纤维的覆盖范围

Mendell & Henneman（1971）的解剖研究：单根 Ia 纤维与~300个同名 α-MN 中的**几乎每一个**形成突触接触。这确保了牵张时运动神经元池的**全体协调响应**，而不是只有部分运动单元被招募。

### 三种增益制动机制

| 机制 | 效应器 | 神经递质 | 功能 |
|------|--------|---------|------|
| 互反抑制 | Ia INs | 甘氨酸 | 抑制拮抗肌α-MN，协调关节运动 |
| 复现抑制 | Renshaw细胞 | 甘氨酸 | α-MN轴突侧支反馈抑制，防止高频持续放电 |
| 突触前抑制 | GABAergic INs（轴-轴突触） | GABA | 减少Ia终末量子释放，任务依赖性闸控 |

### γ运动神经元：增益旋钮

- 静态 γ-MN：增强基础放电率，提高牵张反射的静态增益
- 动态 γ-MN：增强对速度的敏感性，使反射对快速牵张更敏感
- α-γ 协同激活：确保主动收缩时肌梭不松弛失感

### 状态依赖性调制

静止：Group I 抑制伸肌（正常姿势维持时的制动）
步态 CPG 激活：Group I 兴奋伸肌（支撑期的助推）

这种**反射极性反转**由脊髓中间神经元的"功能单元"组织实现（Hultborn 2001）。

### 长潜伏期牵张反射

- M1 成分（~25–35 ms）：脊髓单突触，增益相对固定
- M2 成分（~50–80 ms）：涉及皮层（S1 → M1 → 脊髓），任务依赖性
- M3 成分（~80–120 ms）：皮层随意反应，高度可塑

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Ia→α-MN 是哺乳动物唯一单突触反射 | 潜伏期分析+脊髓电生理 | Lloyd 1943 | 极高 |
| 单根 Ia 纤维接触全部~300个同名 α-MN | 单纤维 HRP 追踪 | Mendell & Henneman 1971, PMID:5540547 | 高 |
| 互反抑制由 Ia-INs 介导 | 细胞内记录+反向刺激 | Eccles et al. 1956, PMID:13396937 | 极高 |
| Renshaw 细胞实现复现抑制 | 光遗传学+全细胞记录 | Moore et al. 2015, PMID:26446220 | 高 |
| 离心收缩时突触前抑制压低牵张反射 | H反射 vs 机械牵张比较 | Duchateau & Enoka 2008, PMC2655422 | 中-高 |
| 状态依赖性反射反转 | 虚构行走 + Group I 刺激 | Hultborn 2001, PMC2278613 | 高（猫）/ 中（人） |
| H反射可通过操作性条件化改变 | 多日训练+EMG | Wolpaw/Thompson 系列, PMC4167198 | 高 |

## 连接

- [[muscle-spindle]] — 牵张反射的感受器（Ia/II 传入纤维来源）
- [[alpha-motor-neuron]] — 牵张反射的效应器（最终公共通路）
- [[gamma-motor-neuron]] — 调节肌梭灵敏度，控制反射增益
- [[golgi-tendon-organ]] — Ib 通路（自源抑制）是牵张反射的对偶机制
- [[ia-inhibitory-interneuron]] — 互反抑制的中介
- [[renshaw-cell]] — 复现抑制的中介
- [[presynaptic-inhibition-ia]] — 突触前增益控制
- [[spinal-cord-cpg]] — 通过功能单元重配置反射极性
- [[corticospinal-tract]] — 皮质脊髓束调控突触前抑制，实现随意运动时的反射增益管理
- [[somatosensory-cortex-3a]] — Ia 传入经丘脑 VPLc → 3a 区，参与长潜伏期反射上行通路
- [[motor-cortex]] — 参与长潜伏期牵张反射（M2/M3 成分）；预先配置反射增益状态

## 未解问题

- Q-stretch-01（高优先级）：人类 Ia-INs 的功能特性是否与猫一致？人类无直接细胞内记录
- Q-stretch-02（中优先级）：长潜伏期牵张反射的 M2 成分是否真的通过 M1 产生，还是皮层的任务相关输出？
- Q-stretch-03（中优先级）：H 反射可塑性的脊髓与皮层贡献比例，及两者协调机制

## 修订历史

- 2026-06-13 · 创建（rev1）· 填补悬空引用 `stretch-reflex` · 基于文章 #179《脊髓最短捷径》· 初始置信度：高

## 来源文章

- [[2026-06-13-stretch-reflex-arc]]

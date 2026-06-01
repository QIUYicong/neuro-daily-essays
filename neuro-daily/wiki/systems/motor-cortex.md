---
title: 运动皮层
slug: motor-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-06-21
updated: 2026-06-21
revision_count: 1
dimensions: [brain-region, microcircuit, behavior, cognition]
related: [corticospinal-tract, population-vector, rotational-dynamics, mirror-neurons, basal-ganglia, prefrontal-cortex, language-network, broca-area, pyramidal-neuron, pv-interneurons]
prerequisites: [pyramidal-neuron, action-potential, synaptic-transmission]
opens_questions: [Q-motor-01, Q-motor-02, Q-motor-03, Q-motor-04]
source_articles: [2026-06-21-motor-cortex-voluntary-movement]
key_sources: ["PMID:3749885", "PMID:22722855", "PMID:21040842", "PMID:23725001", "PMID:39041460"]
---

# 运动皮层 (Motor Cortex)

> **一句话定义**：位于额叶后部中央前回的皮层区域，通过皮质脊髓束驱动对侧随意运动；其内部分为初级运动皮层（M1）、运动前皮层（PMC）和辅助运动区（SMA），分别负责执行、规划和序列协调。

## 当前理解

我们现在认为，运动皮层不是一张静态的"身体地图"，而是一台**动力学机器**：神经元群体在高维状态空间中以旋转轨迹演化，在运动开始前约 150ms 即生成时序肌肉激活模式。

初级运动皮层（M1，BA4）的单个神经元对运动方向有宽余弦调谐，但单细胞无法精确编码方向；运动方向信息以分布式方式存储在群体中，通过**群体向量**（population vector）叠加可精确预测运动方向。更深层的发现是，M1 的准备活动不是亚阈值运动激活，而是在设定动力系统的**初始条件**——这一初始状态通过系统内在动力学演化，生成随后的运动指令。

Graziano 的行为行为地图研究表明，M1 不仅有粗略的体感分区（手/面/腿），还有跨越这些分区的行为类别地图——长时程皮层刺激会引发进化上有意义的完整多关节动作（防御姿势、进食动作、攀爬姿势），且动作总"收敛"到同一终态，暗示 M1 编码的是**行为终态**而非中间肌肉序列。

## 关键机制

### 解剖层次

**M1（BA4）**：
- 第 V 层巨型 Betz 细胞（直径达 80–100 μm）是皮质脊髓束的主要输出来源
- 皮质运动神经元连接（corticomotoneuronal, CM connection）：M1 Betz 细胞直接单突触连接脊髓 α 运动神经元，灵长类特有（尤其人类），是精细手指控制的神经解剖基础

**PMC（BA6外侧）**：
- 背侧运动前区（PMd）：视觉引导运动规划，条件性运动选择
- 腹侧运动前区（PMv / 猕猴 F5 区）：抓握、手口配合；含镜像神经元（执行+观察动作均放电）；是人类 BA44（Broca 区）的演化同源区

**SMA（BA6内侧）**：
- 自我启动的运动；Bereitschaftspotential 提前运动约 1–2秒
- 多关节、双侧协调运动
- 运动序列的内部时序组织

**Pre-SMA**：
- 动作选择的时序控制与抑制
- 准备活动早于 SMA，参与"何时启动"的决策

### 旋转动力学（Churchland 2012）

神经集群在状态空间中旋转，约 2.5 Hz，旋转始于运动前 150ms；两个正交旋转平面解释总方差的 50–70%；用旋转振荡器模型预测 EMG 的相关系数 r=0.97–0.99。

### 群体向量（Georgopoulos 1986）

每个 M1 神经元贡献一个向量（方向=偏好方向，长度=放电率），群体所有神经元向量之和（群体向量）精确预测运动方向。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| M1 神经元早于运动放电，与力相关 | 清醒猕猴慢性记录 + 腕关节力量任务 | Evarts 1968/1969 (无PMID，历史文献) | 高 |
| 个体 M1 神经元余弦调谐 | 三维伸手 + 单神经元记录 | Georgopoulos系列 PMID:3749885 | 高 |
| 群体向量精确预测方向 | 向量叠加 + 三维伸手 | PMID:3749885 | 高 |
| 准备活动调谐与运动期相关性 0.06–0.21 | 延迟任务 + 单神经元 | PMID:21040842 PMC2991102 | 高 |
| M1 群体活动呈旋转动力学，运动前150ms出现 | jPCA降维，469神经元 | PMID:22722855 PMC3393826 | 高 |
| 长时程刺激引发行为行为地图中的完整终态动作 | 500ms皮层刺激 | PMID:17964243 | 中（仅摘要）|
| M1/SMA/pre-SMA 在离散动作和步态中使用相似控制机制 | 猕猴+猫跨物种比较记录 | PMID:39041460 PMC12103638 | 中 |

## 连接

- [[corticospinal-tract]] — M1 输出的主要下行通路
- [[population-vector]] — M1 运动方向的群体编码机制
- [[rotational-dynamics]] — M1 群体活动的时序生成机制
- [[mirror-neurons]] — PMv/F5 中的特殊神经元亚类
- [[basal-ganglia]] — 通过丘脑对 M1 的增益控制（PD中 beta 振荡抑制 M1 输出）
- [[prefrontal-cortex]] — PMd/PMv 与 dlPFC 的边界及协作
- [[broca-area]] — PMv/F5 的人类演化同源区
- [[language-network]] — 运动皮层与语言的演化连接
- [[pyramidal-neuron]] — M1 Betz 细胞是特化的第V层锥体神经元

## 未解问题

- Q-motor-01：旋转动力学在人类（通过 MEG/ECoG）是否同样存在？
- Q-motor-02：小脑通过丘脑如何修正 M1 旋转动力学以实现误差校正？
- Q-motor-03：运动学习（如演奏乐器）如何改变 M1 神经元的调谐特性？
- Q-motor-04：BMI 解码应基于编码格式（direction tuning）还是动力学特性（trajectory prediction）？

## 修订历史

- 2026-06-21 · 创建 · 基于《运动皮层：从地图到发动机》· 初始置信度：高

## 来源文章

- [[2026-06-21-motor-cortex-voluntary-movement]]

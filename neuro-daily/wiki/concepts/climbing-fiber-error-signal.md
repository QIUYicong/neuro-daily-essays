---
title: 攀爬纤维误差信号
slug: climbing-fiber-error-signal
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-01
updated: 2026-08-08
revision_count: 2
dimensions: [cellular, microcircuit, synaptic, behavior]
related: [cerebellum, cerebellar-ltd, purkinje-cell, inferior-olive, predictive-coding]
prerequisites: [cerebellum, purkinje-cell, action-potential]
opens_questions: [Q-cb-02, Q-cb-01]
source_articles: [2026-08-01-cerebellar-ltd-purkinje-motor-learning, 2026-08-08-deep-cerebellar-nuclei-motor-learning-circuit]
key_sources: ["PMID:23440175", "PMID:30995136", "PMID:30069835", "PMID:21482355", "PMID:40848722", "PMID:28858616"]
---

# 攀爬纤维误差信号（Climbing Fiber Error Signal）

> **一句话定义**：下橄榄核（inferior olive）神经元检测运动误差（感觉预测误差或运动结果误差），通过攀爬纤维（climbing fiber）以复杂放电形式将误差信号传递给 Purkinje 细胞——以 ~1 Hz 的极稀疏频率、毫秒级精确时序，触发 LTD 并驱动小脑运动学习，是 Marr 1969 年所预言的"教师信号"的物理实现。

## 当前理解

我们现在认为，攀爬纤维（climbing fiber, CF）是小脑皮层中独特的"教师通道"：每根 CF 来自对侧**下橄榄核（inferior olive, IO）**，以 1:1 的方式支配单个 Purkinje 细胞（PC），其激活产生 PC 特有的**复杂放电（complex spike）**。CF 的正常放电极为稀疏（~1 Hz），但这稀疏的放电并非随机——它在运动误差出现后以精确时序出现，携带误差的大小和方向信息，驱动 PF-PC 突触的 LTD。

这是 Marr（1969）预言的核心：攀爬纤维是监督学习中的"教师"，当运动输出与期望不符时发送纠错信号，引导 Purkinje 细胞修改哪些平行纤维的突触连接需要减弱。

Ito（2013，PMID:23440175）区分了两类误差的计算来源：
- **感觉误差**：视觉/前庭信号与预测结果的不匹配（如视网膜滑移），由 IO 的背侧盖（dorsal cap）计算。
- **运动误差**：实际运动结果与期望动作的偏差，可能经由齿状核-红核-橄榄核通路到达 IO。

## 关键机制

### 下橄榄核→攀爬纤维→复杂放电的信号链

```
运动误差（感觉预测误差 / 运动结果误差）
    ↓ 汇聚到下橄榄核（inferior olive, IO）
IO 神经元的随机低频放电（~1 Hz 基线）→ 误差后放电概率↑
    ↓ 攀爬纤维（CF，跨中线投射到对侧小脑）
浦肯野细胞（PC）的复杂放电
    ↓ 大幅 Ca²⁺ 内流 + mGluR1 信号同步
LTD 诱导（若同时有 PF 激活）→ 运动学习
```

### 误差信号的精度特性（量化）

1. **时序精度**：复杂放电出现在运动误差后约 **80–120ms**（Soetedjo & Fuchs, 2019，PMID:30995136），精确对应视觉误差处理的反馈延迟。
2. **来源延迟**：上丘（SC）→ IO 的中继延迟约 **14.4 ± 0.4ms**（体内 SC 刺激实验）。
3. **误差编码**：复杂放电概率随误差大小（2°–6°范围）系统性增加，且不同 PC 对不同误差方向有"偏好方向"——整体群体编码所有方向和大小。
4. **区域特异时窗**：绒球（flocculus）的最优 PF-CF 配对间隔 ≈ **120ms**（Suvrathan & Raymond, 2018，PMID:30069835），精确匹配该区域服务的眼球运动视觉反馈延迟；不同区域有不同的最优时窗，与所服务行为的感觉延迟对应。

### 下橄榄核的特殊性质

- IO 神经元通过**缝隙连接（gap junctions）**相互耦合，产生同步的 CF 活动爆发，使相邻小脑微区同时接收误差信号。
- 正常放电极低（~1 Hz），误差事件时发放概率上升但仍维持低频——这是生物学中"事件驱动"学习的典型实现。
- IO 神经元将高频突触输入重新编码为低频随机放电（"低通滤波"），避免小脑皮层因误差信号过于密集而过度修改突触。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| CF 激活在 LTD 诱导中必要 | CF 选择性损毁（3-乙酰吡啶）→ LTD 消失 + 运动适应障碍 | PMID:7954803 | 高 |
| 复杂放电编码眼跳误差大小和方向 | 体内 PC 记录 + 系统性误差大小调控 | PMID:30995136 | 高 |
| SC 是眼跳适应误差信号来源（中继到 IO） | SC 阈下刺激诱发复杂放电，延迟 14.4ms | PMID:30995136 | 高 |
| 最优 PF-CF 配对间隔因区域而异（~120ms 绒球） | 绒球精确间隔调控体外实验 | PMID:30069835 | 高 |
| CF 信号含运动成分约为感觉成分 2 倍 | 眼球跟踪实验 IO 活动分析 | PMID:23440175 | 中 |
| IO 缝隙连接驱动 CF 同步，调控学习空间模式 | IO 缝隙连接蛋白（Cx36）敲除实验 | 多来源 | 中-高 |
| CF 放电随奖励大小系统性增加（非仅误差）| 奖励任务 CF 记录（小鼠）| PMID:40848722 | 低（单篇，2025，待复现）|

## 连接

- [[cerebellum]] — CF 是小脑运动学习中的"教师通道"
- [[purkinje-cell]] — CF 以 1:1 支配 PC，激活复杂放电
- [[cerebellar-ltd]] — CF 激活是 PF-PC LTD 诱导的必要条件（提供 Ca²⁺ + 时序信号）
- [[predictive-coding]] — CF 信号可理解为预测误差（prediction error）的神经实现
- [[inferior-olive]] — CF 的起源：下橄榄核是误差计算核团

## 未解问题

- **Q-cb-02**（高优先级）：CF 究竟主要编码感觉预测误差还是运动结果误差？两者在 IO 的不同子区分别计算，但 PC 接收到的信息是否已经整合，还是仍保持分离？
- **Q-cb-01**：前向模型的预测在哪里与实际感觉比较——是在 IO 还是在更上游？小脑皮层 PC 的简单放电是否本身就是"预测"输出？

## 矛盾条目

- **C-2026-08-08-01**（open）：CF "纯误差信号"（claim_A）vs "也传递奖励幅度"（claim_B，Jin & Hull 2025）。矛盾性质：claim_B 基于单篇研究，证据等级低；若复现，则需扩展 Marr-Albus-Ito 模型。见 contested_claims.json。

## 修订历史

- 2026-08-01 · 创建 · 基于《教师信号的困境》（文章#100）· 初始置信度：高（功能和时序特性有高质量体内记录支持）
- 2026-08-08 · 修订（rev1→rev2）· 基于《深部核团的门与教师》（文章#107）· 新增：CF 奖励信号新发现（Jin & Hull 2025，PMID:40848722，低置信度）；登记矛盾 C-2026-08-08-01；IO TMEM16B 离子通道调节证据（PMID:28858616）；key_sources 更新

## 来源文章

- [[2026-08-01-cerebellar-ltd-purkinje-motor-learning]]

---
title: 脊髓中枢模式发生器
slug: spinal-cord-cpg
domain: circuits
type: mechanism
status: established
confidence: high
created: 2026-10-07
updated: 2026-10-07
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, behavior]
related: [spinal-interneurons-locomotion, motor-cortex, cerebellum, basal-ganglia, motor-neuron, proprioception, mesencephalic-locomotor-region]
prerequisites: [synaptic-transmission, action-potential, motor-neuron]
opens_questions: [Q-cpg-rg-identity, Q-cpg-vsct, Q-cpg-human, Q-cpg-forelimb]
source_articles: [2026-10-07-spinal-cpg-locomotion]
key_sources: ["PMID:26935168", "PMID:19543221", "PMID:23812590", "PMID:34070932", "PMID:35063074"]
---

# 脊髓中枢模式发生器 (Spinal Cord Central Pattern Generator, CPG)

> **一句话定义**：位于脊髓腰骶段的神经元网络，能在无感觉反馈和无大脑持续指令的情况下自主产生步态样节律运动；由节律生成（RG）层与模式形成（PF）层构成双层架构，五类遗传标记中间神经元分工实现速度依赖的步态切换与屈伸/左右协调。

## 当前理解

我们现在认为，脊髓 CPG 是一套**分层模块化**的自主计算系统，而非单一振荡器。其最重要的组织原则：

**双层架构**（Kiehn, 2016, PMC4844028）：
- **节律生成层（RG）**：SHOX2+ 非 V2a 兴奋性神经元为核心候选，产生基础振荡驱动；细胞机制包括 I_NaP、NMDA 依赖性爆发和网络兴奋性互联；节律生成在腰骶段是分布式的（非单一位点）
- **模式形成层（PF）**：V0、V1、V2a、V2b、V3 中间神经元将 RG 信号翻译为正确的步态协调模式

**速度依赖的步态切换**（Talpalar et al., 2013, PMID:23812590）：
- 低速（走步）：V0D 抑制性连合中间神经元主导，保证对侧抑制→左右交替
- 中速（小跑）：V0V 兴奋性连合中间神经元叠加，通过间接抑制保证高速交替
- 高速（飞奔/跳跃）：非 V0 同步化回路占主导，V0 系统被压制→双侧同步

**屈伸协调由 V1+V2b 半中枢保证**：
V1（En1+，抑制屈肌）和 V2b（Gata3+，抑制伸肌）共同构成屈伸半中枢；双重删除→屈伸同步（但左右交替保留），证明屈伸和左右协调由独立回路模块控制（Grillner & Kozlov, 2021, PMC8198624）。

**最小振荡回路**（Talpalar et al., 2011, PMID:21943604）：
去除谷氨酸传递后，仅含 rIa-IN（Ia 互逆抑制中间神经元）的抑制性网络仍能产生屈伸交替节律——抑制性网络是屈伸协调的充分条件。

**虚构运动证明了 CPG 的自主性**：
离体腰骶段脊髓（或神经肌肉阻断后的体内制备）在药物激活（L-DOPA/5-HT/NMDA 激动剂）或 MLR 电刺激下，产生完整的节律性步态样放电——无需感觉反馈，无需大脑持续指令（Goulding, 2009, PMC2847453）。

## 关键机制

### 节律生成的细胞机制

候选离子机制：
- **持续性钠电流（I_NaP）**：为膜电位振荡提供去极化驱动
- **NMDA 受体**：条件性起搏活性（电压依赖性 Mg²⁺ 解阻）
- **Ca²⁺ 激活的 K⁺ 电流（I_KCa）**：爆发终止机制（主要在七鳃鳗 CPG 中明确证明）

半中枢逃逸机制：活跃的一侧半中枢通过 I_NaP 疲劳/适应逐渐减弱其对另一侧的抑制，被抑制侧"逃逸"并激活，循环往复。

### 感觉反馈的相位调制

感觉反馈不生成节律，但精确锚定节律的相位：
- Ia 肌梭传入→在肌肉卸载时触发迈步启动（站立→迈步转换）
- Ib 高尔基腱器官传入→在踝关节伸肌负载时抑制屈肌→延长站立相
- CPG 对同一感觉输入的响应因步态相位而异（相位依赖性反射逆转）

### 脑干下行控制的等级体系

MLR（中脑运动区）→ 网状脊髓束 → CPG：
- MLR 电刺激强度与步行速度正相关（弱→走，强→跑）
- MLR 自身受基底节（SNr 去抑制）控制
- V2a"停止神经元"（脑干）激活→通过抑制脊髓前运动网络停止行走（Bouvier et al., 2015, PMID:26590422）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 离体脊髓产生节律性步态样放电 | 离体腰骶段+药物激活+腹根记录 | PMID:19543221 综述 | 高 |
| 完全 V0 删除→全速度同步跳跃 | Dbx1−/−小鼠遗传消融 | PMID:23812590 | 高（仅鼠模型） |
| V0D 删除→低速失交替，V0V 删除→小跑消失 | 选择性 Cre/DTA 消融 | PMID:23812590 | 高 |
| V1+V2b 双重阻断→屈伸同步 | 四重 Cre TeNT 条件性阻断 | PMID:26935168 | 高 |
| 最小抑制性网络产生屈伸节律 | 去谷氨酸脊髓电生理 | PMID:21943604 | 中-高 |
| SHOX2+非V2a 沉默→节律扰乱 | 选择性光遗传沉默 | PMID:24267650 | 中（非完全停止） |
| VSCT 沉默→停止行走；激活→产生步态 | 化学遗传+光遗传 | PMID:35063074 | 中-高（需独立验证） |

## 连接

- [[spinal-interneurons-locomotion]] — CPG 的分子细胞组成（V0/V1/V2/V3 详述）
- [[motor-cortex]] — 皮层通过 CST 叠加精细调控，基础步行中 CPG 主导
- [[cerebellum]] — 通过 VSCT 投射接收脊髓步态信号并反馈协调
- [[basal-ganglia]] — 通过 SNr→MLR→CPG 轴控制步态启动与速度
- [[mesencephalic-locomotor-region]] — CPG 的上游"启动器与调速旋钮"（悬空，待补页面）

## 未解问题

- Q-cpg-rg-identity：哺乳动物 RG 层的完整细胞组成——SHOX2+ 之外还有哪些必要细胞群？
- Q-cpg-vsct：Chalif 2022 的 VSCT 必要/充分性发现是否可独立重复？VSCT 如何整合到既有 V 型中间神经元框架？
- Q-cpg-human：人类脊髓是否存在类似小鼠的 V0-V3 组织架构？硬膜外刺激恢复 SCI 步行的机制中 CPG 如何被激活？
- Q-cpg-forelimb：前肢与后肢 CPG 的协调机制（跨颈腰段长环路）尚未解析

## 修订历史

- 2026-10-07 · 创建 · 基于《步态的脊髓时钟》(#167) · 初始置信度：高（CPG存在性和基本组织），中（RG层细胞身份），中（VSCT证据需重复）

## 来源文章

- [[2026-10-07-spinal-cpg-locomotion]]

---
title: 经皮质牵张反射（长潜伏期牵张反射）
slug: transcortical-stretch-reflex
domain: circuits
type: mechanism
status: established
confidence: high
created: 2026-06-13
updated: 2026-06-13
revision_count: 1
dimensions: [microcircuit, brain-region, whole-brain-network, behavior, cognition]
related: [stretch-reflex, motor-cortex, somatosensory-cortex-3a, corticospinal-tract, muscle-spindle, alpha-motor-neuron, thalamus, optimal-feedback-control, motor-learning, forward-model]
prerequisites: [stretch-reflex, somatosensory-cortex-3a, motor-cortex, corticospinal-tract]
opens_questions: [Q-llr-01, Q-llr-02, Q-llr-03]
source_articles: [2026-06-13-transcortical-stretch-reflex-long-latency]
key_sources: ["PMID:957257", "PMID:9729635", "PMID:21964335", "PMID:24672006", "PMID:18187462", "PMID:23453250", "PMID:25309359"]
---

# 经皮质牵张反射（长潜伏期牵张反射，M2/M3）

> **一句话定义**：肌梭 Ia 传入经脊髓→丘脑→初级躯体感觉皮层（3a 区）→初级运动皮层（M1）→皮质脊髓束→α 运动神经元的经皮质回路产生的牵张反射成分（M2：~50–75 ms；M3：~75–120 ms），区别于单突触脊髓反射（M1：~20–28 ms）的核心在于：可被任务目标调制，能整合多关节信息，随运动学习而改变，并对皮质脊髓束损伤（如中风）特异性敏感。

## 当前理解

长潜伏期牵张反射（Long-latency stretch reflex，LLR）是人体肌肉应对机械扰动时，在脊髓单突触M1反射之后产生的第二层（M2，~50–75 ms）和第三层（M3，~75–120 ms）肌肉响应。其核心特征是通过经皮质回路（transcortical loop）实现——信号不只在脊髓内完成，而是上行到皮层、在皮层整合任务信息后再经皮质脊髓束下行驱动肌肉。

**三个时间成分的比较**：

| 成分 | 典型潜伏期（上肢） | 通路 | 任务依赖 | 学习可塑性 |
|------|-------------|------|---------|---------|
| M1（短潜伏期） | 20–28 ms | 脊髓单突触（Ia→α-MN） | 否 | 低（H反射条件化较慢） |
| M2（长潜伏期早期） | 50–75 ms | 经皮质/脑干混合 | 中度 | 中（数周训练） |
| M3（长潜伏期晚期） | 75–120 ms | 完全经皮质，与随意反应重叠 | 高 | 高（与技能学习相关） |

**核心区别**：M2/M3拥有M1不具备的三种能力：①任务目标调制（相同扰动，不同目标→不同响应幅度）；②多关节整合（肘部扰动→M1神经元正确配置肩部响应）；③环境适应学习（运动适应期间M2/M3与行为学习协同变化）。

## 关键机制

### 经皮质弧的解剖通路

```
肌梭 Ia 传入纤维
    ↓ 脊髓后柱（楔束/薄束）
丘脑腹后外侧核（VPLc）+ 腹外侧核（VLc，小脑信号）
    ↓ ~20 ms 到丘脑
初级躯体感觉皮层 3a 区（本体感觉专属站）
    ↓ 皮层内短程纤维 ~2–5 ms
初级运动皮层（M1）← 在此完成任务目标整合
    ↓ 皮质脊髓束（CST） ~10–14 ms 到脊髓
脊髓 α 运动神经元
    ↓
肌肉收缩（M2/M3 成分）
```

总传导时间约47–57 ms，加上脊髓初始处理，可解释M2的50–75 ms潜伏期。

### M1如何整合任务目标

Pruszynski等2014年（PMID:24672006）在猴子M1的单神经元记录中发现：
- 目标依赖的M1神经元发放分化出现在**35 ms**（扰动后），早于肌肉的目标依赖分化（~70 ms）约35 ms
- 约2/3的神经元在"扰动远离目标"（OUT）条件下比"扰动朝向目标"（IN）有更强响应
- 少部分神经元呈现相反选择性——提示M1内存在多种计算子回路

这种早期（35 ms后）的目标依赖性说明：任务目标信息在扰动发生时已经**预先加载**到M1神经元状态中（通过运动准备期间的前运动皮层→M1投射），使M1在接收到扰动信号时能立即生成适当响应。

### 多关节整合能力

Pruszynski等2011年（PMID:21964335，Nature）通过猴子双关节机械臂实验证明：
- M1神经元在扰动后40–60 ms已整合肩-肘多关节信息
- **纯肘部扰动**引起肩部肌肉M1神经元的适当激活——尽管肩关节没有任何机械刺激
- 这要求M1在50 ms内完成"如果肘部移动，肩部需要什么补偿"的多关节动力学计算

这种能力曾被认为是随意运动的专属——即需要足够时间的意识加工。但M2时间窗内的实现说明，大脑实际上在皮层维持了一个实时的多关节"内部模型"，随时准备在扰动到来时快速运行。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 提出M2/M3经皮质假说 | 拇指长屈肌延迟分析；多块肌肉比较 | Marsden et al. 1976, PMID:957257 | 高（推断性，历史奠基）|
| TMS在M3时间窗产生346%超线性叠加 | TMS+扰动超线性效应；单运动单元PSTH | Petersen et al. 1998, PMID:9729635 | 高 |
| M1神经元在~50 ms整合多关节信息 | 猴单神经元记录+人类TMS | Pruszynski et al. 2011, PMID:21964335 | 高 |
| M1目标依赖调制先于肌肉分化（35 ms） | 猴M1单神经元记录（354神经元）| Pruszynski et al. 2014, PMID:24672006 | 高 |
| 中风后M2/M3双侧受损；M1反射保留 | 柔性vs刚性环境中M2/M3幅度测量 | Trumbower et al. 2013, PMID:23453250 | 高（临床）|

## 连接

- [[stretch-reflex]] — M1（单突触脊髓）是经皮质反射的前驱和基础
- [[motor-cortex]] — M2/M3的皮层整合中枢；接受扰动信号并生成任务依赖响应
- [[somatosensory-cortex-3a]] — 本体感觉信号到达皮层的第一站；经皮质弧的必要节点
- [[corticospinal-tract]] — 经皮质弧的下行臂；损伤后M2/M3特异性受损
- [[muscle-spindle]] — Ia传入提供经皮质弧的感觉输入
- [[optimal-feedback-control]] — OFC框架统一解释了M1/M2/M3和随意运动的连续性
- [[forward-model]] — 小脑前向模型可能参与M2/M3的时序预测计算
- [[thalamus]] — VPLc和VLc是经皮质弧的皮层下中继

## 未解问题

- **Q-llr-01（高优先级）**：M2成分（50–75 ms）中皮质脊髓束（CST）vs 网状脊髓束（RST）的相对贡献？尤其在近端肌肉vs远端手指肌肉中是否不同？能否用选择性CST vs RST损伤模型（如ALS早期、脊髓损伤特定节段）分离？
- **Q-llr-02（中优先级）**：运动准备如何预设M1神经元使其在扰动到来时快速读取任务目标？运动意图（PMA → M1）的突触预激活机制是什么？
- **Q-llr-03（中优先级）**：中风康复训练是否应针对M2/M3的任务依赖调制能力（而非单纯肌力）？现有临床试验（机器人辅助康复）是否量化了M2/M3恢复？

## 修订历史

- 2026-06-13 · 创建（rev1）· 基于文章 #180《反射的第二次进化》· 初始置信度：高（多独立研究，Nature发表）

## 来源文章

- [[2026-06-13-transcortical-stretch-reflex-long-latency]]

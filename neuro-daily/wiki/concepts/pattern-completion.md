---
title: 模式补全
slug: pattern-completion
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-24
updated: 2026-08-27
revision_count: 2
dimensions: [microcircuit, cellular, cognition, disease]
related: [hippocampal-circuit, attractor-network, pattern-separation, ca3-recurrent-collaterals, nmda-receptor, ltp, place-cells, mossy-cells, complementary-learning-systems]
prerequisites: [hippocampal-circuit, ltp, nmda-receptor]
opens_questions: [Q-pc-01, Q-pc-02, Q-ps-03]
source_articles: [2026-06-24-hippocampal-ca3-pattern-completion, 2026-08-27-pattern-separation-completion-dg-ca3]
key_sources: ["PMID:12040087", "PMID:1308182", "PMID:15272123", "PMID:35368306", "PMID:24198767", "PMID:32502734", "PMID:22365813"]
---

# 模式补全 (Pattern Completion)

> **一句话定义**：用不完整或带噪声的线索恢复出完整记忆表征的过程，由海马 CA3 的循环连接通过吸引子动力学实现。

## 当前理解

我们现在认为，模式补全不是"读取特定内存地址"的过程，而是一个**动力学收敛**过程：CA3 循环连接构成的自联想吸引子网络，在接收到部分激活后，通过循环兴奋逐步演化到与之最近的完整存储模式。

这一过程的神经分子基础是：CA3 循环突触（CA3→CA3 Schaffer collateral precursor）上的 NMDA 受体依赖性 LTP 在学习阶段存储了完整模式，检索时循环激活重建这些模式。

最关键的证据来自 Nakazawa et al. (2002, PMID:12040087)：CA3 特异性 NR1 基因敲除小鼠在完整线索下记忆正常，但在部分线索下表现严重受损，证明 CA3 循环突触的 NMDAR 是模式补全的必要条件。

**关键更新（2026-08-27）**：Rolls（2013，PMID:24198767，全文 PMC3812781）提供了 CA3 吸引子网络的定量参数：每个 CA3 细胞约 12,000 个递归侧支突触，苔藓纤维仅 46 条（但极强大），穿孔路径约 3,600 条；理论存储容量约 36,000 条记忆（稀疏度 a=0.02）。此外，**远端 CA3**（而非整个 CA3）被确认为模式补全的主要执行区（Lee et al. 2020，PMID:32502734）——远端 CA3 接受 MEC 空间输入、具有丰富的递归侧支，是 Hopfield 型吸引子动力学的主要场所；而**近端 CA3**更多参与模式分离（与 DG 协同）。DGC 功能二态性中，老粒细胞（>4周龄）也参与支持模式补全，通过苔藓纤维激活 CA3 已有吸引子（Nakashiba et al. 2012，PMID:22365813）。

## 关键机制

### 1. CA3 的吸引子网络结构

CA3 每个锥体细胞接受约 12,000 个来自其他 CA3 细胞的兴奋性循环突触输入，相比之下来自 DG 苔状纤维的输入只有约 50 个。这种极度递归的结构使 CA3 满足 Hopfield 型吸引子网络的结构前提。

**吸引子动力学**：存储 N 个记忆模式后，网络的能量景观（energy landscape）形成 N 个"吸引子盆地"。输入一个部分或噪声版本的模式，网络状态会滚向最近的盆地底部（完整记忆），实现自动补全。

### 2. NMDA 受体在循环突触 LTP 中的作用

循环突触（CA3→CA3）的 LTP 依赖 NMDA 受体的"巧合检测"：
- 前突触释放谷氨酸 + 后突触去极化（来自多个 CA3 细胞的协同激活）→ 解除 Mg²⁺ 阻塞 → 钙内流 → CaMKII 激活 → AMPA 受体插入 → 突触增强

这使得共同激活的 CA3 细胞集群之间的连接增强，完整模式被编码为分布式突触权重矩阵。

### 3. 苔状纤维（DG→CA3）：编码的"强制激活器"

DG 的苔状纤维（mossy fibers）是 CA3 的**去整合者（detonator synapses）**：
- 每个 CA3 细胞只接受约 50 个苔状纤维突触，但这些突触**突触强度极高**（giant mossy fiber boutons）
- 功能：在编码新记忆时，苔状纤维激活强制 CA3 进入新的随机模式，**防止新记忆被旧吸引子捕获**
- Treves & Rolls（1992, PMID:1308182）预测这一双输入系统是 CA3 自联想功能所必需的

### 4. 模式补全的阈值与环境相似度

CA3 的吸引子动力学有一个关键特性：当输入与某个存储模式的相似度超过某个阈值时，网络快速收敛到该吸引子；低于阈值时，可能激活不同的吸引子或在多个吸引子间振荡。

Leutgeb et al. (2004, PMID:15272123) 的体内数据支持这一观点：CA3 对相似环境倾向于产生"非此即彼"的离散表征（阈值效应），而 CA1 产生连续的相似度映射。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| CA3 NMDAR 对模式补全必要 | CA3-NR1 KO 小鼠部分线索条件下行为受损 + 场所细胞失活 | PMID:12040087 | 高 |
| CA3 产生离散吸引子状态 | 多环境记录：相似环境中 CA3 集群几乎完全不同 | PMID:15272123 | 高 |
| 苔状纤维是编码的"强制激活器" | 计算分析 + 苔状纤维突触独特形态（giant boutons）| PMID:1308182 | 中（理论） |
| CA3 递归侧支 ~12,000/细胞，存储容量约 36,000 条记忆 | 定量 Hopfield 模型 + 神经解剖计数 | PMID:24198767（PMC3812781）| 中-高（计算预测，需行为验证）|
| 远端 CA3 为模式补全主场（MEC 输入 + 丰富递归侧支）| 解剖连接分析 + 综述 | PMID:32502734（PMC8136469）| 中（连接证据强，功能分化待体内验证）|
| 老粒细胞苔藓纤维阻断 → 模式补全速度下降（非容量下降）| DG-TeTX 小鼠 + 部分线索检索时间测量 | PMID:22365813（PMC3319279）| 高（因果证据，小鼠）|

## 连接

- [[attractor-network]] — 模式补全的计算机制：吸引子动力学
- [[hippocampal-circuit]] — CA3 是模式补全发生的解剖结构
- [[pattern-separation]] — 与模式补全互补：DG 先分离输入，CA3 再补全输出
- [[nmda-receptor]] — 循环突触 LTP 的关键分子基础
- [[ltp]] — CA3 循环突触增强是模式编码的突触机制
- [[place-cells]] — CA3 场所细胞在模式补全中扮演实际的计算角色
- [[mossy-cells]] — 老 DGC 通过苔藓纤维激活 CA3 已有吸引子，参与支持模式补全
- [[complementary-learning-systems]] — 模式补全是 CLS 理论中海马快速联想检索的实现机制

## 未解问题

- Q-pc-01：CA3 的实际记忆容量（Rolls 2013 预测约 36,000 条）是否与行为数据一致？超过容量后干扰率如何变化？
- Q-pc-02：CA1 的"比较器"模型（CA3 预测 vs EC 直接输入）是否有直接的因果实验支持？
- Q-ps-03（新）：θ 振荡是否在不同相位上门控模式分离（编码）与模式补全（检索）的切换？Hasselmo 2002 的假说缺乏细胞层面直接验证。

## 修订历史

- 2026-06-24 · 创建 · 基于"记忆不混淆的秘密"第 60 篇文章 · 填补了 hippocampal-circuit.md 中长期提到但无专页的悬空引用 · 初始置信度：高
- 2026-08-27 · 修订 · 基于《分与合》第 125 篇文章 · 加入 Rolls 2013 定量 CA3 模型（12K 递归侧支，46 苔藓纤维，~36K 容量）、远端 CA3 专业化（Lee 2020）、老 DGC 苔藓纤维对补全的贡献（Nakashiba 2012）；证据表新增 3 行；连接新增 mossy-cells/complementary-learning-systems；未解问题新增 Q-ps-03

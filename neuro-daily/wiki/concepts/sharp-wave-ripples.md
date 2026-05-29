---
title: 尖波涟漪（SWR）
slug: sharp-wave-ripples
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-29
updated: 2026-06-02
revision_count: 2
dimensions: [whole-brain-network, brain-region, cellular, behavior, cognition]
related: [hippocampal-circuit, place-cell, theta-oscillations, memory-consolidation, ltp, hebbian-learning]
prerequisites: [hippocampal-circuit, synaptic-transmission, place-cell]
opens_questions: [Q-swr-reverse-forward, Q-swr-cortical-consolidation]
source_articles: [2026-05-29-theta-oscillations-phase-coding, 2026-06-02-memory-consolidation-sleep]
key_sources: ["PMID:26135716", "PMID:23354386", "PMID:34936810", "PMID:26389842", "PMID:27182818", "PMID:19749750"]
---

# 尖波涟漪（Sharp Wave-Ripples, SWR）

> **一句话定义**：海马在静息和非REM睡眠期间产生的高度同步群体事件——CA3自发群体爆发通过Schaffer侧支驱动CA1的110–200 Hz快速涟漪，同时以约20倍速压缩重播白天的场所细胞序列，是记忆从海马向新皮层转写的核心机制。

## 当前理解

我们现在认为，SWR是海马**离线模式**的核心事件，与θ振荡（在线/探索模式）在功能上互补、在时间上互斥。SWR发生时，大脑在不接收新感觉输入的情况下，主动重播和重组已编码的经历，是记忆固化（memory consolidation）的物理载体。

SWR不仅是回顾性的（重播已发生的路径），也具有前瞻性特征：有时重播动物**从未实际经历**过的路径，暗示海马具有一定程度的**规划/想象**能力（Tang & Jadhav, 2022）。

**SWR是哺乳动物大脑中最同步的群体放电模式**（Buzsáki, 2015）：一次大型SWR可招募多达50%的CA1锥体细胞，比基线状态高出约6倍的同步度。

## 关键机制

### 1. 生成：CA3自发群体爆发

SWR由**CA3庞大的循环联络系统**驱动：
- CA3拥有哺乳动物大脑中最大的循环兴奋性回路（每个锥体细胞有~12,000个CA3内部突触连接）
- 探索时，胆碱能张力（ACh）通过毒碱受体抑制CA3循环兴奋，防止自发爆发
- 在静息/睡眠中，胆碱能张力下降 → CA3循环兴奋**解放** → 自发性群体爆发 → SWR

这一过程不是"触发"，而是"释放"：胆碱能的解除是开关，CA3内在的循环动力学决定了何时和以何种顺序爆发。

### 2. 传导：CA3→CA1链路

CA3群体爆发通过**Schaffer侧支**传至CA1：
- CA1 stratum radiatum（辐射层）接受大量同步兴奋性输入
- 在CA1 pyramidal layer（锥体细胞层）产生110–200 Hz快速涟漪（ripple）
- 电流源密度（CSD）分析显示：辐射层汇（sink）与锥体层源（source）同步

涟漪的产生依赖**兴奋-抑制的精确平衡**：PV+篮细胞和其他快速抑制性中间神经元的精密介入，将锥体细胞的去极化塑形成规律的高频振荡。

### 3. 序列重播

在SWR期间，白天激活的场所细胞**按相同顺序再次激活**，但速度约为行为时的**20倍**（时间压缩）：
- 动物花5–10秒穿越的路径，在~50 ms的SWR内重播
- 不均匀分布：1.5%的细胞参与50%的SWR事件
- 同一探索轨迹可被重播多次，每次略有变形（确保多样性？）

重播存在多种方向：
- **前向重播**（forward replay）：与行为顺序相同（常见于探索暂停时）
- **反向重播**（reverse replay）：与行为顺序相反（常见于目标到达后）
- **新颖路径重播**：从未实际走过的环境路径（规划功能的可能证据）

### 4. 记忆固化的两阶段模型

SWR在**两阶段记忆固化**中扮演关键角色（Buzsáki, 2015）：
- **第一阶段**（探索/θ态）：海马快速编码新经历；BTSP使场所场在单次穿越中写入
- **第二阶段**（静息/睡眠/SWR态）：海马高速重播，逐渐通过Hebbian突触修改在新皮层建立连接；重播次数累积，皮层突触权重逐渐增大

**关键实验**：选择性SWR中断实验（通过闭环刺激在SWR发生时立即给予干扰）损害次日空间记忆，但不损害即时记忆——直接证明SWR的因果作用（综述于 PMID:26135716）。

### 5. SWR的关键数字

- SPW（锐波）持续时间：40–100 ms（模态~50 ms）
- 涟漪频率：110–200 Hz（非REM睡眠时模态~167 Hz；清醒静息时~177 Hz）
- 非REM睡眠时发生频率：约2–4次/秒
- 清醒静息时：约1–2次/秒

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| SWR起源于CA3循环兴奋，CA1产生涟漪 | 多电极记录+CSD分析；CA3选择性破坏实验 | PMID:26135716 | 高 |
| SWR期间场所细胞序列以~20倍速重播 | 多单元记录+序列比较分析（Bayesian解码） | PMID:26135716；PMID:34936810 | 高 |
| 选择性SWR中断损害空间记忆（因果证据）| 闭环实时检测+CA1电干扰选择性中断SWR，次日空间记忆测试下降 | PMID:19749750（Girardeau 2009） | 高 |
| SWR存在前向、反向和新颖路径重播 | 多单元记录+时空轨迹解码 | PMID:34936810 | 高 |
| 人类大脑中SWR嵌套于纺锤波中，纺锤波嵌套于慢波振荡 | 癫痫患者颅内电极，NREM睡眠，三层振荡时序分析 | PMID:26389842（Staresina 2015） | 高 |
| 操控SO-纺锤波-SWR时序精度因果影响记忆 | 大鼠：同步增强→记忆改善；时序打乱→记忆损害 | PMID:27182818（Maingret 2016） | 高 |
| 情绪效价也在SWR期间重播 | 联合情绪学习+SWR记录 | PMID:31334590 | 中（新兴） |

## 连接

- [[theta-oscillations]] — SWR（静息/睡眠）与θ（探索）互斥：海马的两种工作模式
- [[hippocampal-circuit]] — CA3循环系统生成SWR；CA1通过Schaffer侧支产生涟漪
- [[place-cell]] — SWR期间场所细胞序列被高速重播
- [[memory-consolidation]] — SWR是海马→新皮层记忆巩固的物理机制
- [[ltp]] — SWR重播可能通过反复激活强化海马-皮层突触（LTP机制）
- [[hebbian-learning]] — SWR重播序列中前后神经元的同步激活可能触发Hebbian型突触修改

## 未解问题

- Q-swr-reverse-forward：前向重播、反向重播、新颖路径重播分别在何种条件下产生？是否对应不同的认知功能（强化 vs. 规划 vs. 泛化）？
- Q-swr-cortical-consolidation：SWR期间海马的信号如何精确地在新皮层留下持久印记？是Schaffer-皮层的直接突触修改，还是通过下丘脑/脑干/睡眠调节因子介导？

## 修订历史

- 2026-05-29 · 创建 · 基于《θ振荡与相位编码》文章 · 填补了 memory-consolidation 悬空引用 · 初始置信度：高
- 2026-06-02 · 修订 · 基于《记忆的睡眠转写》文章 · 新增：(1) Girardeau 2009 因果证据的独立行；(2) Staresina 2015 人类三层嵌套振荡证据；(3) Maingret 2016 时序因果操控证据；更新 key_sources

## 来源文章

- [[2026-05-29-theta-oscillations-phase-coding]]
- [[2026-06-02-memory-consolidation-sleep]]

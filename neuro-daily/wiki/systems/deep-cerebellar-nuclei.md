---
title: 深部小脑核
slug: deep-cerebellar-nuclei
domain: systems
type: structure
status: established
confidence: high
created: 2026-08-08
updated: 2026-08-08
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, behavior, cognition]
related: [cerebellum, purkinje-cell, cerebellar-ltd, climbing-fiber-error-signal, motor-learning, thalamus, motor-cortex, inferior-olive]
prerequisites: [cerebellum, purkinje-cell, gaba]
opens_questions: [Q-dcn-01, Q-dcn-02, Q-dcn-03]
source_articles: [2026-08-08-deep-cerebellar-nuclei-motor-learning-circuit]
key_sources: ["PMID:9378587", "PMID:23440175", "PMID:19684593", "PMID:29643480", "PMID:31522332"]
---

# 深部小脑核（Deep Cerebellar Nuclei, DCN）

> **一句话定义**：小脑的 GABA 去抑制输出门与程序性运动记忆的长期存储库——浦肯野细胞持续抑制 DCN，当 LTD 降低 PC 的放电，DCN 被"解除抑制"而驱动运动输出；同时，苔藓纤维-DCN 突触的 LTP 将短期适应巩固为持久运动记忆。

## 当前理解

深部小脑核（DCN）是嵌在小脑白质中的四对（双侧 8 个）核团，它们是小脑皮层唯一的输出通道：浦肯野细胞（PC）的 GABA 轴突终末覆盖 DCN 神经元的胞体和近端树突，以持续的强抑制（50–100 Hz）维持 DCN 的低活动状态。

运动学习的核心逻辑是**"去抑制驱动输出"**：当 PC 在某一运动情境下的放电因 LTD 减少，DCN 被去抑制，活动增加，经丘脑驱动运动皮层产生运动输出（如条件性眨眼）。

我们现在认为，DCN 不只是输出门，更是**程序性运动记忆的长期存储库**：研究表明，在充分训练后用 GABA 激动剂灭活下橄榄核（消除攀爬纤维教师信号），已巩固的条件反应仍能表达（Ke et al. 2009，PMID:19684593）——这说明记忆已从皮层 LTD 转移到 DCN 自身的苔藓纤维 LTP（Ito 2013，PMID:23440175）。

## 三核团的解剖与功能分工

| 核团 | 位置 | 输入来源（小脑皮层） | 主要输出 | 功能 |
|------|------|---------------------|---------|------|
| **齿状核** (dentate nucleus) | 最外侧 | 小脑半球外侧部（新小脑）| 丘脑 VL → 运动皮层/前额叶 | 自主运动规划、认知 |
| **间位核** (interposed nucleus: emboliform + globose) | 中间 | 旁蚓（spinocerebellar）| 红核 → 脊髓；丘脑 → 运动皮层 | 肢体精细运动、条件性运动反射 |
| **顶核** (fastigial nucleus) | 最内侧 | 蚓部 + 绒球小叶部 | 前庭核、脑干网状结构 | 轴向控制、平衡、眼动 |

**间位核与眼眨条件反射**：Thompson et al.（1997，PMID:9378587）的经典损毁实验证明：精确灭活**前间位核（anterior interpositus）**完全消除条件性眨眼反应（CR），而气流触发的无条件眨眼反应（UR）完全保留。这是运动记忆定位到 DCN 的最直接因果证据。

**齿状核与认知**：齿状核通过丘脑与前额叶和顶叶皮层直接连接；齿状核损伤（或小脑半球病变）可引起小脑认知情感综合征（CCAS），表现为执行功能、语言流利性和空间认知的细微损伤（Schmahmann Task Force 2020，PMID:31522332）。

## 关键机制

### 去抑制-驱动输出
```
浦肯野细胞（训练前）：持续 50–100 Hz → GABA → DCN（低活动）→ 丘脑（弱激活）
学习后：PC 在 CS 期间放电↓（LTD 结果）→ DCN 去抑制→ 活动↑ → 运动输出
```

### 苔藓纤维-DCN LTP（记忆巩固）
- DCN 神经元同时接受苔藓纤维（MF，AMPA/NMDA 兴奋性）和 PC（GABA 抑制性）两种输入
- PC 抑制减少时，MF 输入驱动 DCN 的 NMDA 受体激活程度增加
- → NMDA 依赖的 LTP 在 MF-DCN 突触发生（AMPAR 表达上调）
- → DCN 对 CS（通过 MF）的响应长期增强，形成独立于皮层 LTD 的记忆印记

### 小脑-基底神经节互联
Bostan & Strick（2018，PMID:29643480）证明：小脑齿状核通过丘脑旁区与纹状体有直接突触连接，纹状体也经脑桥核向小脑投射——两个传统上被视为独立系统的运动学习回路之间存在皮层下直接对话。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 前间位核是 CR 必要结构（不是 UR） | 利多卡因/肌肉松弛素灭活前间位核 → CR 消失，UR 保留 | PMID:9378587 | 极高 |
| 记忆从皮层 LTD 转移到 DCN LTP | 训练后灭活 IO，已巩固 CR 仍能表达 | PMID:19684593 | 高 |
| DCN 激活可人为产生 CR | 电刺激间位核 → 眨眼运动 | 多来源 | 高 |
| DCN 损伤导致认知功能损伤（CCAS）| 156 例临床病例系列 + 损伤定位 | PMID:31522332 | 高 |
| 小脑-基底神经节皮层下直接连接 | 逆向神经追踪，灵长类 | PMID:29643480 | 高 |

## 连接

- [[cerebellum]] — DCN 是小脑皮层（浦肯野细胞）输出的唯一门控核团
- [[purkinje-cell]] — PC 通过 GABA 持续抑制 DCN；LTD 减少 PC 放电即去抑制 DCN
- [[inferior-olive]] — IO→CF→PC→DCN：误差信号驱动 DCN 的间接解除抑制；DCN 也反馈抑制 IO
- [[motor-learning]] — DCN 是程序性运动记忆的存储位点
- [[thalamus]] — DCN 经小脑上脚→丘脑 VL 核→运动皮层
- [[motor-cortex]] — DCN-丘脑-运动皮层构成小脑-皮层环路

## 未解问题

- **Q-dcn-01**（高优先级）：人类运动技能学习（如钢琴）中，DCN LTP 的时间进程如何？是否可以用 fMRI/cerebellar imaging 分辨皮层 vs 核团的可塑性贡献？
- **Q-dcn-02**（中优先级）：DCN LTP 是否依赖 NMDA 受体？是否有类似海马的关键期？
- **Q-dcn-03**（中优先级）：小脑认知功能（CCAS）是否使用与运动 DCN-LTP 相同的记忆转移机制？

## 修订历史

- 2026-08-08 · 创建 · 基于《深部核团的门与教师》（文章#107）· 初始置信度：高（解剖和因果损毁实验 established；DCN LTP 分子机制 medium）

## 来源文章

- [[2026-08-08-deep-cerebellar-nuclei-motor-learning-circuit]]

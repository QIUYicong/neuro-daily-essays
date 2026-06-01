---
title: 记忆重巩固
slug: reconsolidation
domain: concepts
type: mechanism
status: mainstream
confidence: medium
created: 2026-06-24
updated: 2026-06-24
revision_count: 1
dimensions: [molecular, cellular, brain-region, behavior, cognition, disease]
related: [fear-extinction, fear-conditioning, ltp, memory-consolidation, ptsd, engram-cells]
prerequisites: [memory-consolidation, fear-conditioning, ltp]
opens_questions: [Q-fear-reconsolidation-boundary, Q-recons-boundary-old-memories, Q-recons-clinical-translation]
source_articles: [2026-06-24-fear-extinction-circuits]
key_sources: ["PMID:19342552", "PMID:23404065", "PMID:11423909"]
---

# 记忆重巩固（Memory Reconsolidation）

> **一句话定义**：已固化的记忆在被单次回忆（retrieval）触发后，短暂重新进入不稳定的可塑性状态（约1小时），这一窗口内记忆可以被修改、更新或削弱，窗口关闭后记忆再次固化——但可能已经被改写。

## 当前理解

记忆重巩固理论的核心洞见是：**记忆不是一次性被"写死"的档案，而是每次被读取时都短暂重新变得可写**。这一发现颠覆了经典"记忆巩固是单向不可逆过程"的教科书观点。

重巩固理论的核心证据来自以下实验逻辑：
1. 让动物形成稳定的条件性恐惧记忆（通常1天以上才进行测试）
2. 用单次CS呈现"激活"（reactivate）记忆，触发记忆重新进入可塑状态
3. 在激活后约1小时内给予干预（蛋白质合成抑制剂/NMDA拮抗剂）
4. 干预后的记忆表达出现选择性损害——只影响被重激活的记忆，不影响同期未被激活的其他记忆

**与正常消退的关键区别**：常规消退（反复CS-alone呈现）在原始恐惧痕迹之上叠加抑制性安全记忆，原始痕迹依然存在，可以表现为自发恢复/再激活/情景更新。重巩固窗口内的干预理论上修改了原始痕迹本身。

**Monfils等人（2009，PMID:19342552，Science）**的突破性发现：先用单次CS触发重巩固，然后在窗口内进行消退训练，所产生的"消退"不表现出自发恢复、再激活或情景更新——与常规消退形成鲜明对比。这提示消退-重巩固交叉可以真正"更新"恐惧记忆。

## 关键机制

### 重巩固的分子底物
重巩固窗口内，原本稳定的突触连接（如LA内LTP的AMPA受体群）暂时变得依赖持续的蛋白质合成来维持——此时蛋白质合成抑制剂可干扰记忆的再次固化，导致记忆削弱（类似"新巩固失败"）。

NMDA受体激活是触发重巩固窗口的关键步骤：记忆激活时LA突触的突触前活动 + 突触后的部分去极化 → NMDA受体允许少量Ca²⁺内流 → 激活局部信号级联 → 突触进入短暂不稳定状态。

### 边界条件（boundary conditions）
重巩固窗口不是无条件的：
- **记忆年龄**：新近形成的记忆（1-2天）最容易被重激活修改；非常老的记忆是否依然有可用窗口，证据不足
- **记忆强度**：过强的恐惧记忆（多次训练）可能对重激活有更大的稳定性，窗口效应更小
- **CS数量**：单次CS触发重巩固；多次CS呈现反而触发常规消退
- **激活与干预的时间精度**：在激活后1-6小时内干预有效；超过6小时窗口关闭

### 消退-重巩固的交叉
时间线：
- t=0: 单次CS（激活，触发重巩固）
- t=10min-1h: 多次CS消退训练（在重巩固窗口内）
- t=次日: 消退回忆 → 无自发恢复、再激活、情景更新

推测机制：重巩固窗口内进行的消退训练，不只是叠加新的安全记忆，而是在原始恐惧痕迹的突触被"打开"时，直接用"安全"信息替换了部分恐惧信息。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| 记忆激活后蛋白质合成抑制剂可削弱记忆 | 大鼠LA内茴香霉素（Anisomycin）注射 | PMID:11423909 (Nader et al. 2000, *Nature*)（摘要） | 高 |
| 消退-重巩固交叉消除自发恢复/再激活/更新 | 单次CS先激活，窗口内消退训练 | PMID:19342552（摘要） | 中（啮齿类）|
| 边界条件限制转化效果 | 各实验室复制与变参数研究 | PMID:23404065（摘要）等 | 中（转化有争议） |
| 窗口内干预仅影响被激活记忆 | 条件性激活+非激活记忆的选择性测试 | PMID:11423909 | 高 |

## 连接

- [[fear-extinction]] — 消退-重巩固交叉是修改恐惧记忆的新治疗思路
- [[fear-conditioning]] — 重巩固的对象是原始恐惧条件反射形成的LA突触LTP
- [[memory-consolidation]] — 重巩固是记忆初次巩固之后的动态可塑性窗口
- [[ltp]] — LA内LTP突触是重巩固窗口的分子底物
- [[ptsd]] — 重巩固窗口提供了针对PTSD创伤记忆的新治疗思路
- [[engram-cells]] — 重巩固时被激活的可能正是原始印迹细胞群

## 未解问题

- Q-fear-reconsolidation-boundary（高优先级）：记忆多强/多老才会抵抗重巩固更新？
- Q-recons-boundary-old-memories（高优先级）：数年历史的PTSD记忆是否依然有重巩固窗口？在人类中如何安全诱导？
- Q-recons-clinical-translation（中优先级）：消退-重巩固程序在人类中的疗效与安全性；在何种条件下触发可控的重巩固而不导致记忆不必要的削弱？

## 修订历史

- 2026-06-24 · 创建 · 基于《消退不等于遗忘》一文 · 初始置信度：中（分子机制在啮齿类充分，人类临床转化仍有不确定性）

## 来源文章

- [[2026-06-24-fear-extinction-circuits]]

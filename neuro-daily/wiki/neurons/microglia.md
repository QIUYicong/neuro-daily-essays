---
title: 小胶质细胞
slug: microglia
domain: neurons
type: structure
status: established
confidence: high
created: 2026-05-31
updated: 2026-05-31
revision_count: 1
dimensions: [cellular, molecular, synaptic]
related: [synaptic-pruning, complement-cns, critical-period, alzheimers-disease, hippocampal-circuit]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: [Q-cp-02]
source_articles: [2026-05-31-synaptic-pruning-critical-period]
key_sources: ["PMID:22632727", "PMID:21778362", "PMID:27033548"]
---

# 小胶质细胞 (Microglia)

> **一句话定义**：大脑的固有免疫细胞，占脑细胞的 5–12%，起源于卵黄囊前体（而非骨髓），在发育期通过 C3b-CR3 补体机制活动依赖地吞噬弱突触（突触修剪）；在成年大脑持续监视神经活动和损伤；在神经退行性疾病中错误重激活发育期修剪机制导致病理性突触丢失。

## 当前理解

我们现在认为，小胶质细胞不是被动的"大脑看护者"，而是神经回路发育的**主动雕刻师**，与神经元、星形胶质细胞共同参与突触精修剪。这一认识从根本上改变了对大脑发育中"免疫系统角色"的理解。

**发育期功能**：通过补体 C3b（C1q→C3 级联的产物）识别弱活动突触，利用 CR3（CD11b-CD18）受体将其吞噬进入 CD68+ 溶酶体，实现活动依赖的突触选择性消除（Schafer 2012）。修剪在时间上高度集中：视网膜-LGN 系统中在 P5（约出生后 5 天）达到高峰，P9 以后显著下降。

**成年期功能**：小胶质细胞持续对大脑进行"微型突起快速扫描"（resting microglia 并非静止），接触每一个突触约每几小时一次；它们还响应局部神经活动、损伤信号（DAMPs）、细胞因子，转变为不同激活状态（M1-like 炎症型 vs M2-like 修复型，但这一二元分类已被认为过于简化）。

**疾病中的再激活**（Hong 2016）：在阿尔茨海默病模型中，可溶性 Aβ 寡聚体上调神经元 C1q 表达，使发育期已"关闭"的突触修剪机制被重新激活，导致不应该被删除的成年突触被错误吞噬——在斑块形成前即可检测到。

## 关键机制

**起源**：小胶质细胞来自卵黄囊前体细胞（而非骨髓），在大约 E9 时迁移进入发育中的大脑，此后终生在大脑中驻留自我更新，与外周循环单核细胞分离维护。

**修剪执行步骤**：
1. C1q 沉积于弱突触 → 补体级联激活 → C3b
2. 小胶质细胞微小突起感知 C3b 信号
3. CR3（CD11b-CD18）结合 C3b → 内化吞噬
4. 突触材料进入 CD68+ 溶酶体 → 降解

**形态变化**：
- 发育期（高修剪状态）：相对粗大的突起，多个吞噬体
- 静息成年状态：高度分枝的细突起，快速运动，持续监视
- 激活状态：回缩突起，向圆形阿米巴样形态转变，分泌炎症因子

**CX3CR1-CX3CL1（fractalkine 通路）**：神经元分泌 fractalkine（CX3CL1），小胶质细胞通过 CX3CR1 受体响应——这是神经元控制小胶质细胞行为（包括修剪）的信号通路之一；CX3CR1 KO 小鼠突触修剪受损（Paolicelli 2011）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 小胶质细胞在 P5 主动吞噬突触前成分 | 免疫组化 + 电镜（CD68+ 溶酶体内 40nm 囊泡）；35% 小胶质细胞含突触物质 | PMID:22632727 (Schafer 2012) | 高 |
| CX3CR1 缺失导致突触修剪失败和神经发育异常 | CX3CR1 KO 小鼠：突触密度↑，海马回路异常，孤独症样行为 | PMID:21778362 (Paolicelli 2011) | 高 |
| 补体修剪在 AD 中错误重激活 | AD 模型早期 C1q 上调；C1q KO 减轻突触损失 | PMID:27033548 (Hong 2016) | 高 |

## 连接

- [[synaptic-pruning]] — 小胶质细胞是突触修剪的细胞执行者
- [[complement-cns]] — C1q/C3b 是小胶质细胞识别弱突触的分子信号
- [[critical-period]] — 小胶质细胞修剪在关键期最活跃
- [[alzheimers-disease]] — 小胶质细胞错误激活是 AD 突触病理核心
- [[hippocampal-circuit]] — 海马中小胶质细胞修剪异常与神经发育障碍相关

## 未解问题

- 小胶质细胞的"选择函数"究竟如何精确？仅仅是 C3b 浓度，还是还响应其他突触局部信号？
- 不同脑区的小胶质细胞是否有区域特异性的修剪偏好？

## 修订历史

- 2026-05-31 · 创建 · 基于《发育之剪》一文 · 初始置信度：高（多系统独立验证；小胶质细胞突触修剪功能教科书级共识）

## 来源文章

- [[2026-05-31-synaptic-pruning-critical-period]]

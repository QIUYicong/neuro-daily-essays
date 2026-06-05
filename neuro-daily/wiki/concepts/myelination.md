---
title: 髓鞘化与髓鞘可塑性
slug: myelination
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-27
updated: 2026-07-27
revision_count: 1
dimensions: [molecular, cellular, microcircuit, brain-region, behavior, cognition]
related: [oligodendrocyte, action-potential, axon-initial-segment, saltatory-conduction, critical-period, multiple-sclerosis, dopamine-reward-prediction-error, ltp, three-factor-learning-rule, working-memory, activity-dependent-plasticity]
prerequisites: [action-potential, oligodendrocyte]
opens_questions: [Q-myelin-01, Q-myelin-02, Q-myelin-03]
source_articles: [2026-07-27-myelination-oligodendrocyte-plasticity]
key_sources: ["PMID:24727982", "PMID:34618550", "PMID:33863642", "PMID:37857838", "PMID:38839962"]
---

# 髓鞘化与髓鞘可塑性 (Myelination & Myelin Plasticity)

> **一句话定义**：少突胶质细胞将压缩脂质膜螺旋缠绕轴突，形成致密髓鞘，使动作电位在节点间跳跃传导（最高 120 m/s，是无髓纤维的 100 倍）；近年来发现髓鞘化是活动依赖性的终生可塑过程——神经元放电历史调控 OPC 分化和 OL 形态，从而改变回路中轴突的传导延迟，构成与突触可塑性互补的学习机制。

## 当前理解

我们现在认为，髓鞘化有两层含义，且同等重要：

**层次一：跳跃式传导的物理原理**

致密髓鞘将轴突节间段的膜电阻（Rm）提高约 1000 倍、膜电容（Cm）降低约 50 倍，使离子在节间段几乎无法穿越，局部电流得以快速传播至下一个**兰维耶节**（Node of Ranvier）。节点处集中了高密度 Nav1.6 钠通道，重新发起动作电位，实现"跳跃"。这一机制同时将能量消耗降低约 100 倍（每段轴突无需泵回大量离子）。

速度谱（根据轴突直径和髓鞘厚度）：
- 无髓 C 类纤维：0.5–2 m/s
- 薄髓 Aδ 纤维：5–30 m/s  
- 厚髓 Aα/Aβ 纤维：50–120 m/s

**层次二：活动依赖性髓鞘可塑性**（核心新发现）

Gibson et al. 2014（PMID:24727982，Science）用光遗传学证明：激活运动前区神经元 → OPC 增殖和分化 → 该区域髓鞘化增加 → 运动学习改善；阻断 OL 分化则消除行为改善。这是髓鞘可塑性参与学习的首个直接因果证据。

信号通路：
1. 活跃轴突释放谷氨酸（经小泡外胞吐）+ ATP（经缺口连接或直接释放）
2. OPC 表面的 AMPA/NMDA 受体接收谷氨酸 → Ca²⁺ 信号 → 转录因子激活（Olig2, Myrf）
3. OPC 增殖并分化为 OL → 包裹相邻轴突 → 新髓鞘形成
4. 传导延迟改变 → 影响下游神经元的整合时窗 → 回路计算特性改变

**髓鞘可塑性的功能意义**（Bonetto et al. 2021，PMID:34618550，Science）：
- 突触可塑性改变信号**强度**（权重）
- 髓鞘可塑性改变信号**时机**（延迟）
- 两者共同决定神经元何时以何种模式同步放电

这使髓鞘成为大脑学习机制的第二维度：**突触权重 × 传导时序**共同构成回路计算能力。

**人类特异性**（Fletcher et al. 2021，PMID:33863642）：
- 人类 OPC 更新速度比小鼠慢约 100 倍
- 成年人的髓鞘可塑性可能更多通过**既有 OL 的形态调整**（节间长度、g-ratio 改变）实现，而非大量产生新 OL
- 这与啮齿类实验结论不能直接等同，需要独立人类研究验证

## 关键机制

### 一、髓鞘的分子组成

**致密髓鞘**（compact myelin）：70–80% 脂质 + 20–30% 蛋白质
- MBP（Myelin Basic Protein）：维持层间静电吸引，是压缩结构的"胶水"
- PLP（Proteolipid Protein）：CNS 最丰富的髓鞘蛋白，稳定层间结构；PLP 突变导致 Pelizaeus-Merzbacher 病

**兰维耶节**（Node of Ranvier）：
- 宽 1–2 μm，Nav1.6 钠通道密度极高
- 近节区（paranode）：CASPR + Contactin 与 OL 的 Neurofascin-155 结合，构成离子屏障
- 近节旁区（juxtaparanode）：Kv1 钾通道集中，负责复极化

### 二、发育时序

人类大脑髓鞘化是一个持续数十年的过程：
- 妊娠 24 周：脊髓开始
- 出生时：脑干、小脑基本完成
- 1 岁：初级感觉/运动区
- 5–7 岁：大部分区域初步完成（对应认知飞跃）
- 青春期：边缘系统和皮层联合区
- **20–30 岁**：**前额叶皮层**（PFC）才最终完成（解释为何青少年冲动控制弱于成年人）

### 三、可塑性时间尺度

| 机制 | 时间尺度 | 参数 |
|------|---------|------|
| 突触 LTP/LTD | 毫秒-小时 | 突触权重（强度） |
| 髓鞘可塑性（新 OL 生成） | 天-周 | 传导延迟（时机） |
| 成年神经发生（DG 新神经元） | 周-月 | 回路节点数量 |

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 神经元活动驱动 OPC 增殖和 OL 分化 | 光遗传激活运动前区 + BrdU 标记 | PMID:24727982 | 高 |
| 阻断 OL 分化消除活动诱导的行为改善 | CreER 遗传阻断 + 运动表现测试 | PMID:24727982 | 高 |
| 运动学习使运动皮层 OL 数量增加约 2 倍 | 运动任务 + OL 谱系追踪 | PMID:33863642（综述） | 高 |
| 丰富化环境使 OPC→OL 转化成功率提升 5 倍 | 环境操控 + 细胞计数 | PMC8555870（综述） | 中-高 |
| VTA 多巴胺神经元活动驱动 OL 生成；OL 缺失损害多巴胺释放和奖励行为 | 光遗传 + CreER 遗传阻断 | PMID:38839962 | 高 |
| 人类额叶髓鞘化持续至 30 岁 | MRI/DTI 纵向追踪 | PMID:33863642（综述） | 高 |
| Olig2 / Myrf 敲除损害空间记忆 | 条件基因敲除 + Morris 水迷宫 | PMID:36703503（综述） | 中（特定基因，非全 OL 缺失） |

## 连接

- [[oligodendrocyte]] — 执行髓鞘化的细胞实体
- [[action-potential]] — 髓鞘改变动作电位的传导速度和节点结构（跳跃式传导）
- [[axon-initial-segment]] — AIS 是动作电位发起位点，OL 包裹从 AIS 之外的轴突开始
- [[critical-period]] — 额叶髓鞘化延续至 30 岁，与认知控制关键期的延长直接相关
- [[multiple-sclerosis]] — 免疫攻击髓鞘的病理模型，OPC 可尝试修复但不完整
- [[ltp]] — LTP 改变突触强度；髓鞘可塑性改变传导时机——两者互补的学习双轴
- [[three-factor-learning-rule]] — 髓鞘可塑性是否也受奖励/惩罚信号（DA）调制？Yalçın 2024 提供初步线索
- [[dopamine-reward-prediction-error]] — VTA 奖励回路中 OL 可塑性参与多巴胺动力学调节

## 未解问题

- Q-myelin-01：人类成年期 OL 可塑性的主要机制——新 OL 生成 vs 既有 OL 形态调整？各自的比例、时间常数和脑区特异性如何？
- Q-myelin-02：OPC 通过何种竞争机制选择包裹哪条特定轴突？活动模式如何在分子层面被"解读"为"应被包裹"的信号？
- Q-myelin-03：MS 再髓鞘化为何不完整（节间段更短、髓鞘更薄）？初次髓鞘化 vs 再髓鞘化在分子程序上有何差异？

## 修订历史

- 2026-07-27 · 创建 · 基于《绝缘层的革命》（第95篇）· 初始置信度：高

## 来源文章

- [[2026-07-27-myelination-oligodendrocyte-plasticity]]

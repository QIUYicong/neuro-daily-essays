---
title: 脊髓小脑束
slug: spinocerebellar-tracts
domain: systems
type: structure
status: established
confidence: high
created: 2026-06-13
updated: 2026-06-13
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, whole-brain-network, behavior]
related: [cerebellum, muscle-spindle, golgi-tendon-organ, spinal-cord-cpg, forward-model, clarkes-nucleus, alpha-motor-neuron, proprioception, deep-cerebellar-nuclei]
prerequisites: [spinal-cord-cpg, muscle-spindle, golgi-tendon-organ, proprioception]
opens_questions: [Q-sct-01, Q-sct-02, Q-sct-03, Q-sct-04]
source_articles: [2026-06-13-spinocerebellar-tracts-dsct-vsct]
key_sources: ["PMID:11274339", "PMID:23613538", "PMID:23100134", "PMID:24115921", "PMID:24042498"]
---

# 脊髓小脑束 (Spinocerebellar Tracts)

> **一句话定义**：从脊髓向小脑传递本体感觉信息与运动指令副本的四条平行上行通路——不仅是感觉数据的管道，DSCT 神经元的 70% 同时受脊髓 CPG 直接驱动，意味着它们传递的是感觉状态与运动预测的整合信号，使小脑能实现近实时误差校正。

## 当前理解

我们现在认为，脊髓小脑束是小脑前向模型计算的关键输入通道，提供两类关键信息：

1. **当前肢体状态**：来自肌梭（Ia/Ib 传入）和 GTO（Ib 传入）的精确本体感觉数据
2. **运动指令副本（传出拷贝）**：CPG 和脊髓中间神经元网络的当前状态

**关键范式转变（Stecina et al., 2013）**：传统观点认为 DSCT = 纯感觉，VSCT = 纯运动副本。但细胞内记录证明，70% 的 DSCT 神经元在无外周感觉输入的条件下也受脊髓 CPG 直接驱动，出现与运动神经元同步的"locomotor drive potentials"（3.5–5 mV 膜电位振荡）。这意味着 DSCT 传递的是"实际感觉 + CPG 预期后果"的混合信号，小脑在脊髓层面就已经开始了预测-感觉融合。

## 关键机制

### 四条并行通路

| 通路 | 起源 | 覆盖区域 | 路径 | 小脑入口 | 主要信息类型 |
|------|------|----------|------|----------|-------------|
| DSCT（背侧束） | Clarke 柱（T1-L2）+ 背角 | 下肢、躯干 | 同侧外侧索 | 小脑下脚（ICP） | 感觉 + CPG 混合 |
| VSCT（腹侧束） | 脊髓边缘细胞（腰骶） | 下肢 | 对侧→再交叉（双重交叉）| 小脑上脚（SCP） | 以 CPG 为主 |
| CCT（楔小脑束） | 外侧楔束副核（延髓） | 上肢、颈部 | 同侧 | 小脑下脚（ICP） | 上肢本体感觉 |
| RSCT（吻侧束） | 颈段脊髓 | 上肢 | 双重交叉 | 小脑上脚（SCP） | 上肢 CPG 副本 |

### DSCT 核心特性

- 起源于 **Clarke 柱**（C8/T1–L2）：大细胞，直接接受 Ia 和 Ib 传入的单突触投射（VGluT1 标记末梢密度高）
- 亚群：Clarke 柱（CC-DSCT）、背角（dh-DSCT）、内侧 VI（mVI-DSCT）、VIII 层（VIII-DSCT）
- 关键发现：**70% 在虚拟运动中受 CPG 驱动**；3.5–5 mV locomotor drive potentials
- 解剖：同侧外侧索上行，经 ICP 进入小脑，苔藓纤维终止于前叶和后叶旁正中区

### VSCT 核心特性

- 起源于**脊髓边缘细胞**（SBC）：VGluT2 末梢密度高（脊髓中间神经元输入为主）
- **双重交叉**：对侧外侧索上行→经 SCP 再次交叉→到达同侧小脑前叶
- 信息内容：以 CPG 驱动为主（所有 30/30 神经元在虚拟运动中有节律）
- 功能：运动系统当前状态的传出拷贝

### 颗粒层信息处理

DSCT/VSCT 作为**苔藓纤维**进入颗粒层：
- 每条苔藓纤维驱动多个颗粒细胞
- 颗粒细胞（~690 亿）：每个接受约 4–5 条苔藓纤维输入，稀疏激活（~5–10%）
- 实验（Geborek 2013）：只有部分颗粒细胞对 VSCT 刺激有强响应；>50% PC 被激活
- 稀疏编码 = 高维重编码 = 浦肯野细胞 LTD/LTP 的理想输入格式

### 外侧网状核（LRN）的补充角色

LRN（Alstermark & Ekerot 2013）：从多个运动系统汇聚输入，向小脑提供跨系统整合的全局状态——与 DSCT/VSCT 的分隔信息互补，实现"细节"+"全局"双分辨率监控。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| DSCT Clarke 柱接受 Ia/Ib 单突触投射 | 解剖示踪 + VGluT1 免疫化学 | Bosco & Poppele 2001 (PMID:11274339) | 高 |
| 70% DSCT 神经元受 CPG 驱动 | 去脑猫细胞内记录，去传入，虚拟运动 | Stecina 2013 (PMC3853486) | 高（单实验室，猫模型）|
| VSCT 全部神经元受 CPG 驱动 | 细胞外记录，虚拟运动和抓挠 | Stecina 2013 (PMID:23100134) | 高 |
| VSCT 直接激活 >50% PC | 在体 SBC 束刺激 + 单细胞记录 | Geborek 2013 (PMID:24115921) | 中 |
| 颗粒细胞对 VSCT 输入稀疏响应 | 双侧刺激实验 + 计算模型 | Geborek 2014 + Spanne 2014 | 中 |

## 连接

- [[muscle-spindle]] — Ia/Ib 传入经 DSCT 上行至小脑
- [[golgi-tendon-organ]] — Ib 传入经 DSCT 上行
- [[spinal-cord-cpg]] — CPG 通过中间神经元驱动 DSCT（70%）和 VSCT（100%）
- [[clarkes-nucleus]] — DSCT 的主要起源核团
- [[cerebellum]] — DSCT/VSCT 的终点；苔藓纤维 → 颗粒细胞
- [[forward-model]] — SCT 是小脑前向模型计算的关键输入
- [[proprioception]] — DSCT 是下肢本体感觉上行的主要通道
- [[alpha-motor-neuron]] — α-MN 接受来自 DSCT/小脑 via 丘脑 via M1 的反馈调控
- [[deep-cerebellar-nuclei]] — DSCT/VSCT 苔藓纤维 → 颗粒细胞 → PC → DCN

## 未解问题

- Q-sct-01：DSCT CPG 驱动比例在清醒自然运动中如何变化？
- Q-sct-02：人类 DSCT 是否同样受 CPG 驱动？非人灵长类证据？
- Q-sct-03：颗粒细胞稀疏响应格局是否随运动学习而改变？
- Q-sct-04：Friedreich 共济失调中 DSCT vs 背柱退化对共济失调症状的相对贡献？

## 修订历史

- 2026-06-13 · 创建 · 基于《双轨信使：脊髓小脑束如何让大脑在运动发生前就开始纠错》(#176) · 初始置信度：高（教科书级解剖 + Stecina 2013 电生理直接证据）

## 来源文章

- [[2026-06-13-spinocerebellar-tracts-dsct-vsct]]

---
title: 隔-海马胆碱能投射
slug: septohippocampal-cholinergic
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-29
updated: 2026-06-29
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, cognition]
related: [acetylcholine-cortex, theta-oscillations, sharp-wave-ripples, memory-consolidation, ltp, pattern-completion, hippocampal-circuit, medial-septum, working-memory]
prerequisites: [hippocampal-circuit, synaptic-transmission, theta-oscillations]
opens_questions: [Q-ach-encoding-01, Q-ach-encoding-02, Q-ach-encoding-03]
source_articles: [2026-06-29-acetylcholine-hippocampal-memory-gate]
key_sources: ["PMID:39721980", "PMID:14747523", "PMID:17964734", "PMID:35453495", "PMID:33833054", "PMID:36866246", "PMID:9034856"]
---

# 隔-海马胆碱能投射 (Septohippocampal Cholinergic Projection)

> **一句话定义**：内侧隔核（MSDB）的胆碱能神经元投射至海马全区，通过 M1 毒蕈碱受体（谷氨酸能神经元）和 α7 烟碱受体（OLM 中间神经元）的细胞类型特异性作用，在高 ACh（编码模式/θ主导）和低 ACh（固结模式/SWR主导）之间动态切换，实现记忆编码与提取的相位分离。

## 当前理解

我们现在认为，隔-海马胆碱能投射是海马"计算模式切换器"的关键分子机制，而不仅仅是一般性的神经调制信号。其核心功能是通过 ACh 浓度的动态变化，在以下两种计算状态之间切换：

**高 ACh 状态（编码模式，清醒/主动探索）**：
- 突触前 M1 mAChR 抑制 CA3 回返侧支（Schaffer侧支，stratum radiatum）的谷氨酸释放
- 嗅皮层穿通纤维传入（stratum lacunosum-moleculare）几乎不受抑制
- 结果：新感觉信息主导网络，防止旧记忆干扰新编码（避免灾难性干扰）
- M1 mAChR 同时激活 IP₃→ER Ca²⁺ 通路，促进 AMPAR 运输，协同诱导 LTP
- θ 振荡主导，波谷（编码相）与波峰（提取/预演相）以 ~125ms 节奏交替

**低 ACh 状态（固结/提取模式，休息/睡眠）**：
- CA3 回返连接解除抑制，模式补全（pattern completion）激活
- 尖波涟漪（SWR）频率升高，以 ~20× 速度压缩重放白天经历
- 皮层-海马对话开启，系统记忆固结进行

**直接证据**（Zhang et al. 2021, PMID:33833054）：
- GRABACh3.0 传感器显示 ACh 与 SWR 反相关（ACh 谷值对应 SWR 峰值）
- 光遗传激活 MSDB 胆碱能→延迟区 SWR 抑制→工作记忆成绩下降

## 关键机制

### 解剖结构与投射路径

**起源**：内侧隔核（Medial Septum-Diagonal Band of Broca, MSDB）
- 胆碱能神经元（Ch1/2 区）
- 投射至海马全区（DG、CA3、CA2、CA1）和嗅球（Ch3 区）

**双路径模型**（Gu & Yakel 2022, PMID:35453495）：
- **直接路径**：MSDB 胆碱能 → 海马 M1/α7 受体
- **间接路径**：MSDB 胆碱能调控 MSDB 内部 PV+GABA 神经元（真正的 θ 节奏发生器）

### 受体类型特异性（2020年 KO 实验确认）

| 受体类型 | 表达细胞 | 主要效果 |
|---------|---------|---------|
| M1 mAChR | 谷氨酸能锥体细胞（不是中间神经元） | 促进 θ 序列稳定、LTP 协同诱导 |
| α7 nAChR | OLM 中间神经元（不是谷氨酸能神经元） | 激活后抑制 EC 传入（SLM）+ 增强 Schaffer侧支（SC） |

### 层选择性突触前抑制（Kremin & Hasselmo 2007, PMID:17964734）

| 层 | 连接来源 | ACh 抑制强度 |
|---|---------|------------|
| Stratum Radiatum（SR） | CA3→CA3/CA1 回返侧支 | **强**（低浓度卡巴可即显著） |
| Stratum Lacunosum-Moleculare（SLM） | 嗅皮层穿通纤维 | 弱（高浓度才有效果） |
| Stratum Lucidum（SL） | DG→CA3 苔藓纤维 | 极弱 |

机制：M1 mAChR 突触前激活 → 谷氨酸释放概率降低（PPF 增加）

### M1→LTP 促进路径（Sumi & Harada 2023, PMID:36866246）

$$\text{ACh} \to \text{M1 mAChR} \to \text{G}_q/\text{G}_{11} \to \text{PLC} \to \text{IP}_3 \to \text{ER Ca}^{2+} \to \text{AMPAR 突触插入（LTP）}$$

此通路与 NMDAR-LTP 共享 AMPAR 运输机制但钙源不同（ER vs 胞外），两者可协同作用降低 LTP 诱导阈值。

### SPEAR 模型中的时间动态（Hasselmo 2025, PMID:39721980）

- **θ 波谷**（下降相）：编码相——EC 传入强，CA3 回返弱，LTP 有利
- **θ 波峰**（上升相）：提取相——CA3 回返强，EC 弱，LTD 倾向
- 每125ms 切换一次
- ACh 慢时间尺度（秒-分钟）决定整体偏向；GABA 快时间尺度（<2s）执行θ周期内切换

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| CA3 scopolamine 损害编码不损害提取 | 行为药理学（双重解离，n=7）| PMID:14747523 | 高 |
| CA3 physostigmine 损害提取不损害编码 | 行为药理学（双重解离，n=7）| PMID:14747523 | 高 |
| ACh 层选择性抑制 CA3 回返 > EC 传入 | 离体脑片电生理（PPF，卡巴可）| PMID:17964734 | 高 |
| ACh-SWR 反相关（在体传感器）| GRABACh3.0 光纤传感 | PMID:33833054 | 高 |
| MSDB ACh 激活→SWR 抑制→工作记忆下降 | 光遗传学（因果）| PMID:33833054 | 高 |
| M1→IP₃→ER Ca²⁺→LTP（独立于 NMDAR）| 脑片电生理 + 药理学阻断 | PMID:36866246 | 中高 |
| M1 表达于谷氨酸能神经元，α7 表达于 OLM | 条件性基因敲除 | 引自 PMID:35453495 | 高 |

## 连接

- [[theta-oscillations]] — MSDB 胆碱能调控θ节奏（间接路径通过 PV+GABA；直接路径调制谷氨酸能）
- [[sharp-wave-ripples]] — ACh 谷值时 SWR 主导；ACh 升高主动抑制 SWR（反相关）
- [[memory-consolidation]] — ACh 是系统固结的"状态门控信号"
- [[ltp]] — M1→IP₃→ER Ca²⁺ 协同促进 LTP 诱导
- [[hippocampal-circuit]] — CA3 回返连接的层选择性抑制是核心机制靶点
- [[acetylcholine-cortex]] — 同一分子在皮层的注意/信号增益功能（互补，不冗余）
- [[pattern-completion]] — CA3 回返连接的解除是模式补全的前提
- [[working-memory]] — SWR 维持工作记忆，被 ACh 调控

## 未解问题

- Q-ach-encoding-01（高优先）：θ相位编码/提取分离的闭环光遗传因果证据是否已确立？
- Q-ach-encoding-02（高优先）：高 ACh 抑制提取的精确阈值机制（CA3 回返激活最低量）
- Q-ach-encoding-03（中优先）：人类颅内直接电生理 + ACh 传感器证据

## 修订历史

- 2026-06-29 · 创建 · 基于《乙酰胆碱的双重使命》（文章#182）· 整合 Hasselmo 2025 SPEAR 模型、Rogers & Kesner 2004 双重解离、Kremin & Hasselmo 2007 层选择性、Zhang et al. 2021 光遗传学、Gu & Yakel 2022 受体特异性综述 · 初始置信度：高

## 来源文章

- [[2026-06-29-acetylcholine-hippocampal-memory-gate]]

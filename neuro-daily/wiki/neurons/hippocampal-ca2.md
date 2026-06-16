---
title: 海马 CA2 区（社会记忆节点）
slug: hippocampal-ca2-social-memory
domain: neurons
type: region
status: mainstream
confidence: high
created: 2026-06-16
updated: 2026-06-16
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, cognition, behavior]
related: [vasopressin-system, oxytocin-system, hippocampal-circuit, lateral-septum, social-reward]
prerequisites: [hippocampal-circuit, synaptic-transmission, vasopressin-system]
opens_questions: [Q-AVP-01]
source_articles: [2026-06-16-vasopressin-avp-social-circuit]
key_sources: ["PMID:30518859", "PMID:36789441", "PMID:24739578", "PMID:29085277"]
---

# 海马 CA2 区（社会记忆节点）(Hippocampal CA2: Social Memory Node)

> **一句话定义**：海马 CA2 锥体神经元是经典三突触回路（DG→CA3→CA1）中被长期忽视的"旁路节点"，独特地共表达加压素 V1bR 和催产素受体（OXTR），是啮齿类短期社会记忆的必要回路组件，通过 CA2→LS（侧隔核）投射将社会刺激编码转化为识别记忆和攻击性驱动。

## 当前理解

我们现在认为，CA2 不是 CA3 到 CA1 信号传递的惰性过渡区，而是大脑中**专门处理社会信息的一个计算节点**：

- CA2 接收大量来自内嗅皮层（直接通路，bypassing DG-CA3 的三突触通路）和副嗅球/嗅觉皮层的输入，对社会化学信号（尤其是物种成员特异气味）有精准表示
- CA2 的主要输出靶点是 CA1（海马内环路）和**侧隔核（LS）**（场外输出）——后者对社会行为的调节至关重要
- CA2 锥体神经元独特地共表达 AVPR1b（V1bR）和 OXTR，且两受体均在突触前末梢上有表达，受加压素和催产素的突触前增益控制

**关键修订（2014–2023 年**）：
- 2014：Hitti & Bhatt（Nature）首次证明 CA2 对短期社会记忆的必要性（CA2 特异性抑制 → 社会记忆缺失，但空间记忆完整）
- 2018：Bhatt et al.（Nature）发现 V1bR 在 CA2→LS 突触前末梢上，AVP 通过突触前促进增强攻击行为
- 2023：Cymerblit-Sabba 等发现 OXTR + V1bR 协同维持社会记忆，单 KO 代偿，双 KO 失代偿

## 关键机制

### 细胞特征

CA2 锥体神经元独特的分子标记（区别于 CA1 和 CA3）：
- **高表达**：AVPR1b（V1bR），OXTR，Pcp4（Purkinje cell protein 4），ErbB4，STEP（striatal-enriched protein tyrosine phosphatase）
- **独特可塑性**：CA2 突触对 LTP 诱导（典型的 Schaffer collateral-CA1 刺激方案）有内在抵抗性——这可能防止 CA2 社会编码被普通空间/情节记忆"污染"
- CA2 不接受 DG→CA2 的重要投射（区别于 CA3），而接受 DG 的间接内嗅皮层旁路投射

### 突触组织

**传入**：
- 内嗅皮层（EC）第2层→ CA2 直接投射（Perforant path）
- Schaffer collaterals（CA3→CA2）
- 外侧隔核（LS→CA2）反馈投射（提供 AVP 信号的来源之一？）
- 下丘脑 PVN 的直接 OT/AVP 投射（证据正在积累）

**传出**：
- CA2→CA1（标准海马内环路输出）
- **CA2→侧隔核（LS）**：社会行为调节的关键场外输出

### AVP 的突触前门控机制

AVP（来自 BNST/PVN 投射，在 LS 释放）作用于 CA2 轴突末梢的 V1bR：
- V1bR→Gq→PKC→Ca²⁺通道磷酸化→释放概率↑
- Paired-pulse ratio 降低（预突触易化特征）
- CA2→LS 突触传递增强约 82%（100 nM AVP，膜片钳实验）
- 特异性：V1bR 拮抗剂（SSR149415）完全阻断；V1aR/OTR 拮抗剂无效（Bhatt 2018）

### 社会状态转换模型（Bhatt 2018 提出）

| AVP 释放水平 | CA2→LS 输出强度 | 行为结果 |
|-------------|---------------|---------|
| 低（平静社交） | 适度 | 社会记忆巩固（认知模式）|
| 高（激越/威胁感知） | 强烈 | 攻击行为触发（防御模式）|

这是**同一回路根据神经调质状态切换功能模式**的典型例证。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| CA2 对短期社会记忆必要（空间记忆完整） | CA2 特异性化学遗传沉默+社会/空间记忆测试 | PMID:24739578 | 高 |
| V1bR 在 CA2 突触前末梢促进 CA2→LS 传递 | 膜片钳+选择性 V1bR 工具 | PMID:30518859 | 高 |
| OXTR + V1bR 协同维持社会记忆 | CA2 双 KO + 社会识别测试 | PMID:36789441 | 高 |
| CA2 LTP 抵抗（与 CA1 相反） | 标准 HFS 方案比较 | 多篇文献 | 高 |

## 连接

- [[vasopressin-system]] — V1bR 的核心作用位点；CA2 的社会记忆功能部分依赖 AVP 突触前调制
- [[oxytocin-system]] — OXTR 在 CA2 的共表达；OXR+V1bR 协同；OT/AVP 在社会记忆中的串扰
- [[hippocampal-circuit]] — CA2 是三突触回路中的特殊旁路节点，与 DG-CA3-CA1 主路并行
- [[lateral-septum]] — CA2 的关键场外输出目标，社会行为状态转换的执行节点

## 未解问题

- Q-AVP-01：人类 CA2 V1bR 是否起同等关键作用？人类社会记忆（高度语言化）与啮齿类（嗅觉主导）的 CA2 依赖程度差异？

## 修订历史

- 2026-06-16 · 创建 · 基于《加压素系统》文章 (#195)，重点整合 CA2 V1bR 机制 · 初始置信度：高

## 来源文章

- [[2026-06-16-vasopressin-avp-social-circuit]]

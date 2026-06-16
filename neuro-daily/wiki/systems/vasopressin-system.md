---
title: 加压素系统
slug: vasopressin-system
domain: systems
type: mechanism
status: established
confidence: high
created: 2026-06-16
updated: 2026-06-16
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, whole-brain-network, behavior, cognition]
related: [oxytocin-system, pair-bond, amygdala, hpa-axis, hippocampal-ca2-social-memory, dopamine-system, lateral-septum, ventral-pallidum]
prerequisites: [synaptic-transmission, gpcr-signaling, action-potential, hypothalamus, oxytocin-system]
opens_questions: [Q-AVP-01, Q-AVP-02, Q-AVP-03, Q-AVP-04]
source_articles: [2026-06-16-vasopressin-avp-social-circuit]
key_sources: ["PMC9968743", "PMID:17118932", "PMID:30518859", "PMID:36789441", "PMID:35863332", "PMID:34978098"]
---

# 加压素系统 (Vasopressin System / AVP)

> **一句话定义**：精氨酸加压素（AVP，9肽）是催产素的分子孪生兄弟（仅差2个氨基酸），由下丘脑 PVN/SON（非性别化）和 BNST/MeA（睾酮依赖、雄性 2-3 倍多）双重来源合成，通过 V1aR（腹侧苍白球→配对键；侧隔→社会辨别）和 V1bR（海马 CA2 突触前→社会记忆/攻击；垂体→HPA协同）调节社会行为，其效果高度依赖回路、性别和情境——不是"攻击激素"，而是一套精确的社会状态–行为转换器。

## 当前理解

我们现在认为，加压素系统的核心功能是**在社会情境中按回路特异性方式调节社会刺激的行为响应**：在不同脑区，通过不同的受体亚型（V1aR vs V1bR）、不同的细胞类型（神经元 vs 突触前末梢）和不同的下游效应，产生从配对键强化、社会记忆编码到攻击行为触发的完全不同结果。

**关键新理解（2018–2023）**：
1. V1bR 主要位于 CA2 到侧隔核投射轴突的**突触前末梢**（而非 CA2 细胞体），是突触前增益控制的分子实体（Bhatt 2018）。
2. CA2 中 OXR 和 V1bR 的**协同作用**维持社会记忆——单一 KO 可被代偿，双重 KO 才显现严重社会记忆损伤（Cymerblit-Sabba 2023）。
3. 不同 AVP 细胞来源（BNST vs PVN vs SCN）在**功能上相互独立**：BNST 来源驱动雄性社会通讯和调查，PVN 来源调节应激-行为接口，SCN 来源调节昼夜节律。

## 关键机制

### 分子层：合成与受体

**合成场所**（按性别化程度）：
| 来源 | 性别化程度 | 主要投射目标 | 功能 |
|------|----------|------------|------|
| PVN/SON 大细胞神经元 | 低（PVN投射方向有性别差异） | 垂体后叶（外周）、LS、CA2、NAc（雌性更强）| 外周：血压/水平衡；中枢：社会行为、应激 |
| BNST/MeA（终纹床核/内侧杏仁核） | **高**（雄性 2-3 倍，睾酮/雌二醇依赖）| LS、VP、LHb、DRN、mPOA | 社会通讯、配偶识别、攻击性调节 |
| SCN（视交叉上核） | 低 | 散布全脑 | 昼夜节律（非社会行为主要机制） |

**受体信号**：V1aR 和 V1bR 均为 Gq/11 偶联 GPCR → PLC → IP₃（ER Ca²⁺释放）+ DAG（PKC）。

**与 OT 的交叉激活**：高浓度 AVP 可部分激活 OXTR（亲和力约低 10 倍），高浓度 OT 也可激活 V1aR——这种串扰使纯药理学实验难以区分两系统，基因工具（受体特异性 KO/agonist）是必要手段。

### 回路层 I：VP V1aR——配对键的雄性节点

- 腹侧苍白球（VP）V1aR 密度在草原田鼠（单配性）显著高于草甸田鼠（杂交性）
- 向 VP 局部注射 V1aR 拮抗剂 → 阻止配偶偏好形成（即使交配正常）
- 向草甸田鼠 VP 病毒转染草原田鼠 *avpr1a* → 出现配对偏好（Lim 2004）
- **avpr1a 微卫星**（启动子上游约 660 bp 处的重复序列）：长版本→更高 V1aR 表达→配对键倾向强；个体内微卫星长度预测父性行为强度

**配对键诱导的伴侣保护攻击**：配对后雄性对入侵者的攻击性依赖 AVP 信号（AVP 在侧下丘脑 V1aR 的激活），而非 OT 信号——同一配对键行为的"爱"与"守卫"面向被不同的 AVP 回路分开处理。

### 回路层 II：CA2 V1bR——社会记忆的突触前门控

- V1bR 表达于 CA2 锥体神经元投射至侧隔（LS）的轴突末梢（突触前位置）
- AVP 激活突触前 V1bR → 谷氨酸释放概率↑ → CA2→LS 传递增强 82% （Bhatt 2018，100 nM AVP）
- LS 局部注射 V1bR 拮抗剂 → 攻击率从 32% 降至 0%
- CA2 在社会状态中的双重功能模型：
  - AVP（低释放量）：CA2→LS 适度激活 → 社会记忆巩固
  - AVP（高释放量/激越状态）：CA2→LS 强激活 → 攻击行为触发

**OXR 与 V1bR 协同**（Cymerblit-Sabba 2023）：CA2 锥体神经元共表达 OXTR 和 V1bR。单 KO 任一受体被代偿；双 KO 导致：短时间间隔社会辨别任务失败，CA2→CA3 突触传递改变，delta 波功率异常。

### 回路层 III：BNST→LS V1aR——社会调查与个体识别

- BNST AVP 轴突大量投射到 LS，与 PVN 来源的 AVP 投射在 LS 汇聚
- LS V1aR 激活 → 双向效果（兴奋直接 LS 神经元 + 间接抑制 LS 神经元，通过抑制性中间神经元）
- BNST AVP 消融 → 雄性社会调查减少，超声通讯减少，配偶辨别受损
- BNST AVP 敲减对雌性无显著行为效果（功能性别二态性）

### 系统层：垂体 V1bR——HPA 轴应激接口

- 垂体前叶促肾上腺皮质细胞表达 V1bR，与 CRH 协同刺激 ACTH 释放（超线性协同）
- 慢性社会应激 → PVN 从 CRH 主导切换到 AVP 主导 → HPA 持续高活化（慢性压力生物学标记）
- V1bR 拮抗剂（SSR149415）在动物实验中有抗抑郁/抗焦虑效果
- Ⅱ期临床（重度抑郁、广泛性焦虑）：未能优于安慰剂（转化鸿沟）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| VP V1aR 是雄性配对键必要条件 | 局部拮抗剂/激动剂注射行为实验 | PMID:15051143 | 高 |
| avpr1a 微卫星决定 V1aR 分布和配对策略 | 物种比较+AAV 基因转移 | PMID:17118932 | 高 |
| CA2 V1bR 突触前促进 CA2→LS 传递 | 膜片钳+选择性药理工具 | PMID:30518859 | 高 |
| V1bR 激活驱动社会攻击 | LS 局部 V1bR 拮抗剂注射 | PMID:30518859 | 高 |
| OXR+V1bR 协同维持社会记忆 | CA2 双 KO 模型 | PMID:36789441 | 高 |
| BNST AVP 雄性偏向 2-3 倍（睾酮依赖） | 免疫荧光计数+去势实验 | PMID:23239101 | 高 |
| BNST AVP 敲减降低雄性社会行为 | siRNA 敲减+多项行为测试 | PMID:34978098 | 高 |
| 鼻内 AVP 改善 ASD 儿童社会能力 | 随机双盲 RCT（n≈130） | PMID:33782612 | 中（单次，效应量中等） |

## 连接

- [[oxytocin-system]] — 分子孪生：2个氨基酸差异，互补功能分工；OT（雌性/NAc配对键），AVP（雄性/VP配对键）
- [[pair-bond]] — VP V1aR 是配对键形成的雄性机制节点
- [[hippocampal-ca2-social-memory]] — V1bR 的关键作用位点；CA2→LS 社会记忆/攻击双功能节点
- [[hpa-axis]] — 垂体 V1bR 与 CRH 协同驱动应激反应
- [[amygdala]] — MeA 作为性别化 AVP 来源；接收副嗅球社会化学信号
- [[lateral-septum]] — BNST/CA2 AVP 信号的汇聚节点；社会行为状态切换
- [[dopamine-system]] — VP 的 V1aR 激活与 NAc DA 协同完成配对键奖励学习

## 未解问题

- Q-AVP-01：CA2 V1bR 在人类社会记忆中的作用（人类 CA2 V1bR 密度是否与啮齿类相当？）
- Q-AVP-02：雌性 BNST AVP 在围产期/产后行为中的特定功能（被严重低估的空白）
- Q-AVP-03：BNST 和 PVN 来源 AVP 在 LS 汇聚时如何整合（功能协同还是竞争？）
- Q-AVP-04：鼻内 AVP 的中枢作用机制（能否通过嗅觉神经直接进入嗅球-杏仁核通路？）

## 修订历史

- 2026-06-16 · 创建 · 基于《社会行为的分子二重奏：加压素如何以性别化回路书写攻击、配对与社会记忆》(#195) · 初始置信度：高（核心机制 established，临床应用中等）

## 来源文章

- [[2026-06-16-vasopressin-avp-social-circuit]]

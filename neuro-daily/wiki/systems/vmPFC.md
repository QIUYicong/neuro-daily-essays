---
title: 腹内侧前额叶皮层（vmPFC）
slug: vmPFC
domain: systems
type: region
status: established
confidence: high
created: 2026-08-25
updated: 2026-08-26
revision_count: 2
dimensions: [brain-region, whole-brain-network, cognition, disease]
related: [amygdala, anterior-cingulate-cortex, prefrontal-cortex, orbitofrontal-cortex, fear-extinction, emotion-regulation, cognitive-reappraisal, hippocampal-circuit, nucleus-accumbens, default-mode-network, insular-cortex, hpa-axis, ptsd]
prerequisites: [prefrontal-cortex, amygdala, fear-extinction]
opens_questions: [Q-vmPFC-01, Q-vmPFC-02, Q-vmPFC-03]
source_articles: [2026-08-25-vmPFC-sgACC-emotion-regulation, 2026-08-26-ptsd-fear-circuit-vmPFC-hippocampus-amygdala]
key_sources: ["PMID:19693001", "PMCID:PMC3055427", "PMID:12495527", "PMID:23765157", "PMID:15748841", "PMID:41171999", "PMCID:PMC12578624", "PMID:10415674", "PMID:19358877", "PMID:19748076", "PMID:41663712"]
---

# 腹内侧前额叶皮层（Ventromedial Prefrontal Cortex, vmPFC）

> **一句话定义**：额叶内侧面底部的新皮层区域（约 BA10/11/12/25/32 腹侧），大脑情绪调节的顶层枢纽；通过直接投射杏仁核中间神经元（GABAergic 抑制），和间接调制（经 sgACC/BA25 下行至下丘脑、脑干、神经调质系统），将来自前额叶的认知评估信号转化为对边缘系统情绪输出的精细调控；在抑郁症中其亚区 sgACC 持续过度激活，构成难以自行打破的情绪失调恶性回路。

## 当前理解

我们现在认为，vmPFC 是一个功能上定义的区域而非单一解剖实体，指额叶内侧面腹侧的新皮层（大致 BA10/11/12/25/32 腹侧），在灵长类和人类中高度发达。它的核心功能是**情绪调节的前额叶接口**：将来自外侧前额叶（vlPFC/dlPFC）的语义-认知评估信号，与来自杏仁核、岛叶和海马的情绪-内感觉信号整合后，通过多条下行通路调制杏仁核输出和自主神经-神经调质系统。

**关键亚区**（Price & Drevets 2010, PMID:19693001 [开放全文 PMC3055427]）：

| 亚区 | Brodmann 区 | 主要功能 |
|------|------------|---------|
| **sgACC / BA25** | 胼胝体膝下方 | 情绪调节、自主神经控制、抑郁核心靶区 |
| rACC 腹侧 / BA32 | 胼胝体嘴部前方 | 情感疼痛、安慰剂镇痛、情绪冲突监测 |
| OFC 内侧 / BA11m | 眶额皮层内侧 | 价值整合（→ orbitofrontal-cortex 页面）|
| mPFC 极 / BA10v | 额极内侧 | 社会认知、自我参照、DMN 核心节点 |

Price & Drevets 将 sgACC 定义为"**内脏运动皮层**"（visceromotor cortex）——类比初级运动皮层对随意运动的控制，sgACC 对内脏/自主神经功能的调控也处于同等地位：它是下行到下丘脑、脑干核团（LC、DRN、PAG）的皮层起点，将情绪状态的皮层评估结果转化为全身性自主神经和神经调质改变。

**啮齿类同源结构**：vmPFC 的最重要功能同源区是大鼠/小鼠内侧前额叶的**下边缘皮层（infralimbic cortex, IL）**，也包括部分**前边缘皮层（prelimbic cortex, PL）**。IL≈sgACC（恐惧抑制/消退），PL≈rACC（恐惧表达/认知控制）。这种对应关系使大量啮齿类机制研究可以支撑人类临床发现。

## 关键机制

### 机制一：认知重评通路（人类 fMRI + TMS-fMRI）

```
外部负面刺激 → 杏仁核（快速激活）
                      ↑情绪信号↓
vlPFC（语义重构）─→ vmPFC ─→ 负向有效连接 ─→ 杏仁核↓（激活减少）
                              ↕
                         岛叶↓（内感觉唤醒减少）
```

- Ochsner et al. 2002 (PMID:12495527)：fMRI 重评→内外侧 PFC↑ + 杏仁核↓
- He et al. 2023 (PMID:37507228)：vlPFC TMS→vmPFC 激活↑ + 杏仁核/岛叶↓（因果确认）
- Steward et al. 2021 (PMID:32960214)：DCM 估计 vmPFC→杏仁核存在负向有效连接（抑制性的因果影响）
- Buhle et al. 2014 元分析（PMID:23765157）：跨 48 项研究，vmPFC 不是稳定激活区，可能是整合阶段而非执行阶段的节点

### 机制二：恐惧消退通路（啮齿类 IL + 人类 fMRI）

IL（vmPFC 同源区）→ 腹侧 ITC（ICMMV）→ CeM 抑制 → 恐惧行为↓
同时：IL → BLA 消退神经元激活 → 安全信号释放

- Giustino & Maren 2015 (PMID:26617500 [OPEN])：PL 促进恐惧，IL 促进消退（双分离）
- Sierra-Mercado et al. 2011 (PMID:20962768)：IL 灭活→消退学习的 within-session 受损
- 人类 vmPFC/sgACC 激活强度直接预测消退记忆回忆质量（多项研究）
- PTSD 患者的 vmPFC 激活不足是消退回忆障碍的神经基础

### 机制三：sgACC 作为内脏运动皮层（神经解剖 + 灵长类示踪）

```
sgACC ─→ 蓝斑（LC）→ NE 释放调节
sgACC ─→ 中缝背核（DRN）→ 5-HT 释放调节
sgACC ─→ 导水管周围灰质（PAG）→ 内源性镇痛 / 心血管
sgACC ─→ 下丘脑外侧区 → 交感激活
sgACC ─→ 孤束核（NTS）→ 副交感调节
sgACC ─→ 伏隔核（NAc）→ 奖励-动机评估
sgACC ↔ 杏仁核 BLA（双向）
```

### 机制四：抑郁症中的 sgACC 失调

正常：sgACC 精准调节自主神经和神经调质输出
抑郁：sgACC 持续过度激活（Drevets 1999, PMID:10415674）
→ 持续 5-HT↓（DRN 长期被下调）→ anhedonia
→ NE 失调（LC）→ 应激高反应性
→ 持续驱动杏仁核正向激活 → 负面情绪偏见固化
→ vmPFC 整体功能受损 → 无法抑制杏仁核
→ 恶性循环：负面情绪→更多 sgACC 激活→更强杏仁核→更多负面情绪

DBS 解锁机制：sgACC 旁白质纤维刺激→局部代谢↓→前额叶代谢↑→回路脱离锁死态（Mayberg 2005, PMID:15748841）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| 认知重评时前额叶↑ + 杏仁核↓ | fMRI，46受试者 | Ochsner et al. 2002, PMID:12495527 | 高（多次重复） |
| vmPFC→杏仁核负向有效连接 | 动态因果模型 | Steward et al. 2021, PMID:32960214 | 中-高 |
| vlPFC→vmPFC→杏仁核三层级（因果） | TMS-fMRI | He et al. 2023, PMID:37507228 | 中（单项） |
| IL 功能双分离（促消退）/ PL（促恐惧） | 综述+多项实验，大鼠 | Giustino & Maren 2015, PMID:26617500 | 高 |
| sgACC = 内脏运动皮层（投射 LC/DRN/PAG/NAc） | 灵长类神经解剖示踪综述 | Price & Drevets 2010, PMID:19693001 | 高 |
| 家族性抑郁症 sgACC 代谢过度+灰质减少 | PET + MRI | Drevets 1999, PMID:10415674 | 高（广泛重复） |
| 抗抑郁治疗→sgACC 代谢选择性降低 | PET 纵向 | Drevets et al. 2002, PMID:12468016 | 中-高 |
| sgACC DBS：4/6 TRD 患者缓解 | 开放标签，6例 | Mayberg et al. 2005, PMID:15748841 | 中（小样本） |
| sgACC DBS 24个月：73.1% 反应率 | 最大单中心 RCT 随访 | Giacobbe et al. 2026, PMID:41171999 | 中-高 |

## 连接

- [[amygdala]] — vmPFC 直接抑制杏仁核输出（认知重评和恐惧消退的共同效应器）
- [[fear-extinction]] — IL（vmPFC 同源区）是消退表达的皮层起点
- [[emotion-regulation]] — vmPFC 是情绪自主调节的核心皮层节点
- [[cognitive-reappraisal]] — 重评策略的神经基础：vlPFC→vmPFC→杏仁核
- [[anterior-cingulate-cortex]] — sgACC/BA25 是 ACC 的膝下亚区，在本页做详细覆盖
- [[orbitofrontal-cortex]] — vmPFC 的外侧延伸，专注价值编码
- [[prefrontal-cortex]] — vmPFC 是 PFC 的腹内侧亚区，其他 PFC 亚区见该页
- [[hippocampal-circuit]] — 情景信号从海马到达 vmPFC，调制情境依赖的情绪记忆激活
- [[hpa-axis]] — sgACC→下丘脑 PVN 路径参与 HPA 轴的皮层调制
- [[default-mode-network]] — mPFC（vmPFC 最前部）是 DMN 核心节点之一
- [[ptsd]] — PTSD 患者消退记忆回忆时 vmPFC 激活显著减弱（Milad 2009, PMID:19748076 fMRI 直接证据）；vmPFC 沉默是消退刹车失效的核心机制，消退记忆本身储存于 IL/vmPFC；Yi 2026（PMID:41663712）提出联合靶向 vmPFC-IL 的整合多通路治疗框架

## 未解问题

- Q-vmPFC-01（高优先级）：vmPFC 和 dlPFC 在情绪调节中的功能边界——是 dlPFC 提供任务目标、vmPFC 提供情绪估价，在 vlPFC 整合后共同决定调节策略？（见 state/unresolved_questions.md）
- Q-vmPFC-02（中优先级）：sgACC DBS 的长期缓解机制——是局部场电位振荡改变，还是轴突末梢顺行激活投射通路？
- Q-vmPFC-03（高优先级）：vmPFC/IL 的消退回忆功能在 PTSD 中失败的确切机制——连接减弱、PNNs 异常，还是情景信号错误提取？

## 修订历史

- 2026-08-25 · 创建 · 基于《驯化杏仁核：vmPFC 与 sgACC 如何编织情绪控制的神经语言》(#123) · 初始置信度：高
- 2026-08-26 · 修订 rev2 · 基于《PTSD 中的记忆囚笼》(#124) · 连接节新增 ptsd（Milad 2009 fMRI 直接证据：PTSD 消退回忆时 vmPFC 激活↓；Yi 2026 整合多靶点治疗框架）；related 新增 ptsd；key_sources 新增 PMID:19748076/41663712；source_articles 新增 2026-08-26

## 来源文章

- [[2026-08-25-vmPFC-sgACC-emotion-regulation]]
- [[2026-08-26-ptsd-fear-circuit-vmPFC-hippocampus-amygdala]]

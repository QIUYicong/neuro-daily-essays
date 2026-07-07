---
title: 光遗传学
slug: optogenetics
domain: methods
type: method
status: established
confidence: high
created: 2026-06-09
updated: 2026-07-08
revision_count: 2
dimensions: [molecular, cellular, microcircuit, brain-region, behavior, cognition, methods]
related: [channelrhodopsin, engram-cells, place-cell, hippocampal-circuit, pv-interneurons, ltp, dopamine-reward-prediction-error, alzheimers-disease, neuropixels, distributed-decision-coding]
prerequisites: [action-potential, voltage-gated-sodium-channel, synaptic-transmission]
opens_questions: [Q-opto-depth-limit, Q-opto-distributed-representation, Q-opto-clinical-ethics]
source_articles: [2026-06-09-optogenetics-causal-neuroscience]
key_sources:
  - "PMID:16116447"
  - "PMID:17375185"
  - "PMID:21692661"
  - "PMID:22266941"
  - "PMID:23888038"
  - "PMID:24478647"
  - "PMID:25162525"
---

# 光遗传学 (Optogenetics)

> **一句话定义**：将微生物视蛋白（通道视紫质激活、卤视紫质沉默）通过遗传手段表达于特定细胞类型，以毫秒精度和细胞类型特异性用光操控神经元活动，实现对神经回路的可逆因果干预。

---

## 当前理解

光遗传学诞生于 2005 年（Boyden et al., PMID:16116447），核心原理是将**单组件光敏蛋白**直接表达于神经元：光照→蛋白构象变化→离子电流→膜电位改变，整个过程无需级联放大，延迟极短（亚毫秒到毫秒量级）。

激活工具的代表是**通道视紫质-2（ChR2）**，来自莱茵衣藻，蓝光（~470 nm）激活，驱动阳离子（Na⁺、H⁺）内流，诱发动作电位。抑制工具的代表是**卤视紫质（NpHR/halorhodopsin）**，来自古菌 *Natromonas pharaonis*，黄光（~560 nm）驱动氯离子内流，超极化膜电位，沉默神经元。

结合**细胞类型特异性表达**（AAV 载体 + 启动子特异性，或 Cre-lox 系统），光遗传学可以：
1. 在自由行为动物中激活/沉默任意遗传定义的神经元亚群；
2. 以毫秒精度与自然神经活动同步；
3. 在同一动物中可逆切换状态，实现双向因果检验。

这一技术使神经科学从"相关性科学"进化为"因果实验科学"（Fenno et al. 2011, PMID:21692661）。

2026-07-08 补充：这一"相关性 vs 因果性"的区分，在 [[neuropixels]] 时代获得了新的紧迫性。大规模同步电生理记录（如 Steinmetz 2019 的全脑42脑区记录）能从几乎任何脑区解码出任务相关信息（见 [[distributed-decision-coding]]），但"能解码"不等于"该脑区真的参与了计算"——这正是 Q-opto-distributed-representation 提出的问题在全脑尺度上的具体化。光遗传学是目前裁决这一问题最直接的工具：对广泛分布、可解码的信号逐一进行选择性沉默，观察行为是否真的因此受损，才能把"到处都能读出"的相关性图景收窄为"真正在计算"的因果图景。

---

## 关键机制

### 激活工具：ChR2 分子机制

- **结构**：七跨膜（7-TM）α螺旋蛋白，全反式视黄醛作为发色团共价连接于 Lys257（PMID:22266941）
- **激活波长**：~470 nm（蓝光）
- **机制**：蓝光→视黄醛顺-反异构化→蛋白构象变化→阳离子通道开放→Na⁺/H⁺内流→去极化→动作电位
- **时间常数**：开放 ~1-2 ms；自然关闭 ~10 ms
- **优化变体**：ChETA（更快动力学，高频控制）；C1V1、ReaChR、Chrimson（红移，更深穿透）；CoChR（高光敏感性）

### 抑制工具：NpHR（halorhodopsin）分子机制

- **来源**：古菌 *Natromonas pharaonis*
- **类型**：光驱动氯离子泵（非通道）
- **激活波长**：~560 nm（黄/绿光）
- **机制**：黄光→视黄醛异构→Cl⁻ 被主动泵入细胞→膜超极化（约 33 mV，来自全文 PMID:17375185）→动作电位被阻断
- **起效时间**：~10-15 ms（全文数据）
- **单脉冲精度**：可精确消除单个动作电位而不影响前后放电
- **优化变体**：eNpHR3.0（改善膜靶向）；Arch（古菌视紫红质，质子泵，绿光驱动，效率更高）；GtACR（通道型抑制，更大电流）

### 遗传特异性递送策略

| 策略 | 机制 | 特异性 |
|------|------|--------|
| AAV + 细胞特异性启动子 | CaMKII→兴奋性，hSyn→全部神经元，PV→PV+抑制性 | 启动子活性定义细胞类型 |
| Cre-lox 系统 | floxed ChR2 + Cre-转基因鼠 | Cre 表达定义精确细胞类型 |
| c-fos-tTA（TetTag） | 活动诱导 c-fos 启动子 → tTA → TRE-ChR2；dox 窗口控制标记时间 | 标记特定时间窗内激活的神经元 |
| 跨突触病毒（AAV-retro 等） | 逆向/顺向标记连接神经元 | 投射特异性（回路层面） |

---

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 蓝光（470nm）可毫秒精度触发神经元放电 | ChR2 在培养/在体神经元中的电生理验证 | PMID:16116447 | 高 |
| 黄光（560nm）通过 NpHR 超极化神经元（~33mV）| 全细胞膜片钳，在体验证；全文数据 | PMID:17375185 | 高 |
| ChR2 在猕猴皮层安全有效 | 慢病毒靶向额叶皮层兴奋性神经元，数月内稳定表达 | PMID:19409264 | 高 |
| 激活 DG 印迹细胞足以触发完整记忆表达 | c-fos 标记 + 光激活 → 冻结行为（假记忆实验） | PMID:23888038 | 高 |
| 记忆效价可通过操控 DG（非BLA）印迹双向切换 | ChR2 标记 + 对侧条件化 → 效价翻转 | PMID:25162525 | 高 |
| ChR2 为七跨膜结构，视黄醛结合口袋介导光激活 | 晶体结构（C1C2 嵌合，2.3 Å） | PMID:22266941 | 高 |

---

## 连接

- [[engram-cells]] — 光遗传学是印迹细胞研究的核心因果工具（假记忆、效价翻转）
- [[action-potential]] — ChR2 激活直接诱发动作电位
- [[hippocampal-circuit]] — 大量海马 DG/CA1/CA3 回路的因果解析
- [[pv-interneurons]] — 选择性激活/沉默 PV+ 细胞以解析 gamma 振荡与认知
- [[place-cell]] — 光遗传学在体验证了场所细胞对空间导航的因果贡献
- [[ltp]] — optogenetics 证明了诱导 LTP 的突触特异性，支持印迹细胞假说
- [[dopamine-reward-prediction-error]] — 选择性激活 VTA DA 神经元触发奖励行为
- [[channelrhodopsin]] — 待建立（ChR1/ChR2 的分子生物学页面）
- [[neuropixels]] — 大规模同步记录提供相关性/可解码性证据，光遗传学提供因果验证，两者互补
- [[distributed-decision-coding]] — 全脑分布式可解码信号是 Q-opto-distributed-representation 问题在全脑尺度的具体案例

---

## 未解问题

- **Q-opto-depth-limit**：脑组织对光的散射限制了光遗传学在大型哺乳类（包括人类）深部脑区的应用。无线微 LED、光纤导管的改进能在多大程度上克服这一限制？
- **Q-opto-distributed-representation**：激活一个遗传定义的细胞类型（PV+/DG/VTA DA）是否总能反映自然编码状态？对于分布式表征（如记忆在皮层的分布），光遗传学操控是否只能捕获"粗粒度"的因果关系？
- **Q-opto-clinical-ethics**：视网膜色素变性的视力恢复已进入临床试验。用于认知功能操控（记忆修复、情感障碍治疗）的人类脑内光遗传学面临哪些不可绕过的伦理边界？

---

## 修订历史

- 2026-06-09 · 创建 · 基于《光遗传学：用一束光解开神经回路的因果之谜》一文 · methods 层第一个页面 · 初始置信度：高（established）
- 2026-07-08 · 修订（rev2）· 基于文章 #191《决策无处不在：神经像素探针如何终结"一个脑区一个功能"，又如何暴露出新的陷阱》· 新增：与 [[neuropixels]]/[[distributed-decision-coding]] 的因果 vs 相关性讨论，呼应既有未解问题 Q-opto-distributed-representation

---

## 来源文章

- [[2026-06-09-optogenetics-causal-neuroscience]]
- [[2026-07-08-neuropixels-distributed-decision-coding]]

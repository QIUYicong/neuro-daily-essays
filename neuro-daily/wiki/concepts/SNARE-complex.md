---
title: SNARE复合体
slug: SNARE-complex
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-25
updated: 2026-07-14
revision_count: 3
dimensions: [molecular, synaptic]
related: [synaptic-transmission, synaptotagmin, active-zone, complexin, munc18, membrane-fusion]
prerequisites: [synaptic-transmission]
opens_questions: [Q-snare-partial-zipper, Q-snare-number-per-fusion]
source_articles: [2026-05-25-synaptic-vesicle-exocytosis, 2026-07-12-complexin-dual-function-vesicle-fusion, 2026-07-14-munc18-stxbp1-template-mechanism]
key_sources: ["PMID:22026965", "PMID:23060190", "PMID:22068972", "PMID:28813412", "PMID:30540253", "PMID:21499244"]
---

# SNARE复合体 (SNARE Complex)

> **一句话定义**：SNARE复合体是由突触囊泡膜上的Synaptobrevin和靶膜上的Syntaxin-1、SNAP-25共同组成的四螺旋蛋白束，通过N→C端的"拉链式"组装产生机械力，驱动突触囊泡与突触前膜的融合。

## 当前理解

SNARE（Soluble N-ethylmaleimide-sensitive factor Attachment protein REceptors）蛋白是所有真核细胞膜融合事件的核心分子机器，在突触中经过高度特化以实现毫秒级的精确融合。

**三个组成蛋白：**
- **Synaptobrevin/VAMP2**（v-SNARE，位于囊泡膜）：含短N端序列、一个SNARE基序、跨膜锚定区
- **Syntaxin-1**（t-SNARE，位于靶膜/突触前膜）：含N端序列、Habc结构域（自我抑制域）、SNARE基序、跨膜锚定区
- **SNAP-25**（t-SNARE，位于靶膜）：罕见地含**两个**SNARE基序（通过棕榈酰化锚定）

四个SNARE基序（1+1+2）共同形成一个**平行方向的四螺旋束**，其中央含保守的"亲水层"（3个Gln残基+1个Arg残基）。

**融合机制（拉链模型）：**
组装从N端开始向C端"拉合"，将囊泡膜和靶膜拉近，最终克服两层磷脂双层间的斥力，触发融合（PMID:22026965）。

**关键调控：**
- Munc18-1与Syntaxin的闭合构象结合，**并非单纯"防止过早组装"，而是同时充当组装模板**：其3a结构域螺旋发夹在Syntaxin仍闭合时，就已将Syntaxin与Synaptobrevin-2的SNARE基序N端预先对齐（"态7"模板中间体），组装加速约25倍（详见[[munc18]]）
- Munc13的MUN结构域协同加速该模板态向Syntaxin开放构象转化，同时直接激活Munc18-1本身的催化能力（双靶点作用，详见[[munc18]]）
- Complexin插入C端侧的沟槽，既防止自发融合，又为钙触发准备
- NSF + α-SNAP利用ATP水解将融合后的顺式（cis）SNARE复合体解体，回收各蛋白

**能量来源：**
SNARE复合体的组装是高度放热反应，释放的自由能驱动膜融合所需的弯曲形变。估计约1-3个SNARE复合体即可驱动单次融合事件（PMID:23060190；PMID:37891212）。

## 关键机制

### 分子结构
- 四螺旋束由SNARE基序按照Qa（Syntaxin）、Qb（SNAP-25 N端）、Qc（SNAP-25 C端）、R（Synaptobrevin）分类组装
- 中央亲水层是SNARE复合体的独特结构特征，区分于其他卷曲螺旋
- 复合体热稳定性极高（解折叠温度>80°C）

### 组装调控
- Syntaxin-1自抑制：Habc域折叠于SNARE基序之上，需Munc13打开
- 体外SNARE自组装"耗时数小时"——体内需要蛋白辅助才能达到毫秒级
- NSF/α-SNAP将融合后的SNARE复合体分解，实现蛋白周转

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 三蛋白构成四螺旋束 | X射线晶体学、NMR | PMID:22026965 | 极高 |
| 从N→C端拉链式组装触发融合 | 截断突变、单分子力学测量 | PMID:23060190 | 高 |
| 约1-3个复合体足以触发融合 | 单复合体实验+计算模型 | PMID:23060190 | 中 |
| NSF/α-SNAP解体复合体为下一轮融合准备 | 生化实验、电子显微镜 | PMID:22026965 | 高 |
| Complexin通过Syt1-SNARE-Cpx三方界面（990 Å²）锁定预融合态，Ca²⁺结合Syt1后解锁完成拉链 | X射线晶体学(1.85-2.5Å)+突变功能验证 | PMID:28813412（PMC全文） | 高 |
| Munc18-1闭合构象结合Syntaxin时，已通过3a结构域将SNARE基序N端预先对齐成"模板态"中间体，为组装提供起始轨道 | 单分子光镊+突变验证 | PMID:30540253（全文开放） | 高 |
| Munc13 MUN结构域协同加速模板态向开放态转化25-240倍 | NMR+FRET+突变验证 | PMID:21499244（PMC全文） | 高 |

## 连接

- [[synaptic-transmission]] — SNARE是突触传递的核心执行机器
- [[synaptotagmin]] — 调控SNARE最终拉合的钙传感器
- [[complexin]] — 锁住并超启动SNARE复合体的调控蛋白；2017年晶体结构揭示其与Syt1共同锁定预融合态的三方界面机制（详见[[complexin]]）
- [[munc18]] — 组装启动阶段的模板蛋白；将闭合构象结合从"阻碍者"重新理解为"精确对齐SNARE基序的模板"（详见[[munc18]]）
- [[active-zone]] — SNARE组装发生的特化位点
- [[membrane-fusion]] — SNARE是普遍性膜融合机器（突触特化版）

## 未解问题

- Q-snare-partial-zipper：就绪态（primed）囊泡的SNARE是"部分拉合"还是"完全游离等待"？这一争议影响对融合能量学的理解
- Q-snare-number-per-fusion：体内每次融合事件平均需要几个SNARE复合体？

## 修订历史

- 2026-05-25 · 创建 · 基于《神经信号的化学渡口》一文 · 初始置信度：高
- 2026-07-12 · 修订 · 基于《刹车还是油门？Complexin 如何用同一段螺旋同时钳制与催化囊泡融合》一文 · 新增complexin三方界面结构证据，"连接"中complexin条目更新为指向新建专页
- 2026-07-14 · 修订 · 基于《一把先关上的锁：Munc18-1 如何在"堵住"SNARE的同时，充当组装它的模板》一文 · 填补munc18悬空引用（新建专页），修正"关键调控"段落中Munc18-1"防止过早组装"的简化表述为"模板机制"，新增2条关键证据行，"连接"新增munc18条目

## 来源文章

- [[2026-05-25-synaptic-vesicle-exocytosis]]
- [[2026-07-14-munc18-stxbp1-template-mechanism]]

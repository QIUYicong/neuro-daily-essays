---
title: 工作记忆
slug: working-memory
domain: concepts
type: concept
status: established
confidence: high
created: 2026-06-05
updated: 2026-06-05
revision_count: 1
dimensions: [cognition, brain-region, microcircuit, behavior]
related: [persistent-activity, gamma-oscillations, prefrontal-cortex, pv-interneurons, nmda-receptor, theta-oscillations, sharp-wave-ripples, memory-consolidation]
prerequisites: [nmda-receptor, pv-interneurons, synaptic-transmission]
opens_questions: [Q-wm-active-vs-silent, Q-wm-capacity-mechanism, Q-wm-pfc-content-vs-control, Q-wm-human-specificity]
source_articles: [2026-06-05-prefrontal-working-memory]
key_sources: ["PMID:4998337", "PMID:7695894", "PMID:26996084", "PMID:18339943", "PMID:21345366"]
---

# 工作记忆 (Working Memory)

> **一句话定义**：在数秒内主动维持少量信息（容量约 4 项）并对其进行操作的认知能力，神经基础为 dlPFC 循环回路的 γ 爆发（间歇性主动编码）与突触 STP 易化（活动无声储存）的协同机制。

## 当前理解

工作记忆是认知控制的核心基础设施。心理学实验（Baddeley & Hitch 1974）将其定义为容量有限（~4 项）、时间有限（约 15–30 秒）、需主动维持的信息暂存-操作系统。

其神经基础集中在背外侧前额叶皮层（dlPFC），尤其是第 2/3/5 层锥体细胞的循环连接网络。当前最佳理解（2020 年代）认为工作记忆由多层机制共同实现：

1. **活动性编码**（active coding）：γ 爆发（45–100 Hz，~67 ms/次）期间，神经元高精度编码记忆内容（Lundqvist et al. 2016）
2. **突触静默储存**（activity-silent storage）：突触 STP 易化（Ca²⁺ 残留 + 囊泡就绪）在爆发间隔期无声保持信息（Mongillo et al. 2008）
3. **主动抑制**（active suppression）：β 振荡（20–35 Hz）压制竞争信息
4. **层级特化**：浅层（L2/3）负责内容编码，深层（L5/6）负责时序控制

经典持续放电模型（Goldman-Rakic 1995）仍然有效，但需修订：延迟期放电是**间歇性 γ 爆发**而非连续高频，且并非所有信息都需要主动放电维持。

## 关键机制

### 回路机制：吸引子网络
dlPFC 第 2/3 层锥体细胞通过水平侧支形成循环兴奋回路。一个刺激激活的神经集群通过循环连接形成**吸引子状态（attractor state）**，在外部输入消失后自持活动（Wang 2001）。NMDA 受体的慢衰减（τ ~100–300 ms）赋予回路所需的时间积分能力。

### γ 爆发机制
PV+ 篮状细胞的兴奋-抑制循环（锥体细胞兴奋 → PV 反馈抑制 → 10-15 ms 后再激活）产生 30–80 Hz γ 振荡。工作记忆维持期间，γ 以短暂爆发形式出现（非持续），间歇性"刷新"信息表征。

### 多巴胺调节
多巴胺 D1 受体对 dlPFC 工作记忆呈倒 U 型调节（Arnsten 2011）：适中水平通过 α-2A 受体抑制 cAMP，强化循环回路；过高（急性压力）或过低（衰老）均损害工作记忆。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| PFC 神经元在延迟期持续放电 | 猕猴单单元记录 + 延迟任务 | Fuster & Alexander 1971 (PMID:4998337) | 高 |
| 持续活动呈内容选择性 | 猕猴 PFC 空间延迟任务 | Goldman-Rakic 1995 (PMID:7695894) | 高 |
| 延迟期为 γ 爆发非持续放电 | 猕猴 PFC 时频分析 | Lundqvist et al. 2016 (PMID:26996084, PMC:PMC5220584) | 中-高 |
| STP 可实现活动无声 WM | 计算模型 | Mongillo et al. 2008 (PMID:18339943) | 中 |
| D1 受体倒 U 型调节 | 猕猴 PFC 微量注射 | Arnsten 2011 (PMID:21345366, PMC:PMC3115784) | 高 |
| PV 损伤导致 γ 下降和 WM 缺陷 | 人类 dlPFC 尸检 | Hughes et al. 2024 (PMID:39381500, PMC:PMC11458443) | 高 |

## 连接

- [[persistent-activity]] — 工作记忆维持的活动性机制（γ 爆发的神经相关物）
- [[gamma-oscillations]] — PV+中间神经元生成的 30–80 Hz 节律，工作记忆的时序框架
- [[prefrontal-cortex]] — 工作记忆的关键脑区，dlPFC 第 2/3/5 层
- [[pv-interneurons]] — γ 生成者，控制工作记忆的时序精度
- [[nmda-receptor]] — PFC 循环回路的时间积分器
- [[theta-oscillations]] — θ 周期内可嵌套 5–7 个 γ 爆发，可能与工作记忆容量相关
- [[memory-consolidation]] — 工作记忆的长期化需要海马参与

## 未解问题

- Q-wm-active-vs-silent：在真实任务中，活动性编码与突触静默储存各贡献多少？
- Q-wm-capacity-mechanism：约 4 项的容量限制是来自吸引子间的相互干扰还是 θ/γ 嵌套约束？
- Q-wm-pfc-content-vs-control：PFC 究竟是"内容存储器"还是"调度控制中心"？
- Q-wm-human-specificity：人类 dlPFC 是否有特有的工作记忆机制？

## 修订历史

- 2026-06-05 · 创建 · 基于《γ爆发、静默突触与持续放电》一文 · 初始置信度：高

## 来源文章

- [[2026-06-05-prefrontal-working-memory]]

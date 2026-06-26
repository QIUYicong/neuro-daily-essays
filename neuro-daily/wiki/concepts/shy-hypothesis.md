---
title: 突触稳态假说（SHY）
slug: shy-hypothesis
domain: concepts
type: theory
status: mainstream
confidence: high
created: 2026-07-07
updated: 2026-10-14
revision_count: 2
dimensions: [synaptic, cellular, microcircuit, whole-brain-network, cognition]
related: [synaptic-scaling, homeostatic-plasticity, sleep-spindles, sharp-wave-ripples, cortical-slow-oscillation, so-spindle-swr-coupling, memory-consolidation, ltp, ltd, up-down-state-mechanism, ampa-receptor]
prerequisites: [synaptic-transmission, ltp, ltd, homeostatic-plasticity, cortical-slow-oscillation]
opens_questions: [Q-shy-vs-active-consolidation, Q-shy-molecular-mechanism, Q-shy-onoff-bistability-human]
source_articles: [2026-07-07-sleep-memory-consolidation-so-spindle-swr, 2026-10-14-cortical-onoff-periods-sleep-shy-validation]
key_sources: ["PMID:28154076", "PMID:30614089", "PMID:38973508", "PMID:31374117", "DOI:10.1038/s41593-026-02318-9", "PMID:24411729"]
---

# 突触稳态假说（Synaptic Homeostasis Hypothesis, SHY）

> **一句话定义**：Tononi & Cirelli 提出的睡眠功能理论：清醒期学习使突触整体增强（净 LTP），而 NREM 睡眠通过慢振荡驱动的突触轻度抑制，将约80%的突触权重向下调整约18%，恢复信噪比、节省神经元资源、为次日新的学习清空"带宽"——而被睡眠期间 SWR 重播激活的记忆痕迹突触受到保护（down-selection），实现选择性记忆巩固。

## 当前理解

我们现在认为，SHY 不是"睡眠清空记忆"，而是"睡眠精炼记忆"的机制理论。其核心命题：

> **"清醒是可塑性的代价；睡眠偿还这笔债。"**（Tononi & Cirelli 2020，PMID:30614089）

**清醒期**：感觉输入 + 学习 → 广泛的 Hebbian 突触增强（LTP）→ 突触权重平均上升 → 神经元能量消耗增加、受体资源趋于饱和、信噪比（SNR）下降。如果不加干预，突触权重将无限积累，最终：
- 突触能量代谢不可持续
- 新的突触增强无处安放（已达饱和）
- 背景噪音过大，信号被淹没

**NREM 睡眠期**：SO 的 UP state 对皮层神经元施以温和的"低强度群体激活"→ 对绝大多数突触触发轻度 LTD（而非 LTP）→ 突触权重整体下调 → 恢复动态范围和信噪比。

**关键修订：Down-selection，非 Downscaling**（Tononi & Cirelli 2020）：
- 最初的 SHY 被理解为"所有突触等比缩小"（downscaling），类似 Turrigiano 的突触稳态缩放
- 更新的框架是"下选择"：大多数突触被削弱；但被 SWR 重播激活的记忆痕迹突触受到"保护免于抑郁"（protection from depression）
- 净效应：被重播的记忆痕迹突触信噪比相对升高，等效于选择性记忆巩固

**与 Turrigiano 突触稳态缩放（synaptic scaling）的区别**：
- Turrigiano 的突触稳态缩放（PMID:9495341）是细胞自主的多日慢速乘法性调节，针对异常高/低活动
- SHY 是每天睡眠周期性驱动的快速（数小时内完成）整体调节，时间尺度和触发条件不同
- 两者均属于稳态可塑性，但机制和功能不同

## 关键机制

### 1. 慢振荡驱动的突触下调

- SO UP state：皮层群体兴奋 → 兴奋性突触的突触前末梢钙内流 → 温和激活 → 未达到 LTP 阈值 → 施加 LTD
- 机制候选：Ca²⁺ 依赖的 AMPA 受体去磷酸化（CaMKII 脱激活）→ AMPA 受体内吞 → 突触权重下降
- 这种"低强度激活"类似于 mGluR-LTD 或脱磷酸化驱动的被动 LTD

### 2. SWA 是突触强度的"负债表"

一个重要的实验预测：**入睡时皮层 SWA（慢波活动）功率反映该脑区之前清醒期积累的突触增强程度**：
- 单侧练习右手运动 → 右侧运动皮层对应区域入睡 SWA 更强
- 在认知任务后局部 SWA 功率升高 → 睡眠对该区域"偿债"更多
- 动物模型：局部 kisspeptin/optogenetic 诱导局部 LTP → 该区域 SWA 选择性升高

这一预测已被大量实验支持（综述于 Tononi & Cirelli 2020）。

### 3. 超微结构直接证据（de Vivo et al. 2017，PMID:28154076）

- SBEM 测量小鼠运动皮层和体感皮层 L2 的 6,920 个突触
- 睡眠后 vs 清醒后：ASI（轴突-棘界面面积）平均缩小 **~18%**
- **选择性**：最小 80% 突触缩小 ~11.9%；最大 20% 突触基本不变（+0.7%）
- 含再循环内体突触缩小更多（~20–25%）
- 意义：首次在超微结构层面直接观察到睡眠依赖的突触缩小，且具有大突触保留的选择性

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| 睡眠后突触 ASI 缩小 ~18%（超微结构） | SBEM，6920 个突触，L2 运动/体感皮层 | PMID:28154076 | 高 |
| 选择性：最大 20% 突触不受影响 | 同上，突触大小分层分析 | PMID:28154076 | 高 |
| 睡眠后皮质突触 GluA1 表达下降 | 睡眠剥夺 + 恢复睡眠 vs 正常睡眠，Western blot | PMID:38973508 | 中-高 |
| 幼鼠睡眠依赖突触缩小（发育普遍性） | 幼鼠 SBEM，ASI 缩小 33.9% | PMID:31374117 | 中-高 |
| SWA 功率与先前清醒突触使用正相关 | 单侧训练+局部EEG（综述引用多个实验） | Tononi & Cirelli 综述 | 中 |
| **ON/OFF 双稳态是突触下调的充分因果条件**（新增 2026-10-14） | 清醒小鼠皮层光遗传诱导 ON/OFF → GluA1↓（t₇=5.51 p<0.001）+ pGluA1(Ser845)↓ + 后续 SWA↓（t₁₀=-17.69 p<0.001）；强直性抑制对照无效（p=0.62） | DOI:10.1038/s41593-026-02318-9 (PMC12632314) | 高（动物；直接因果） |
| **ON/OFF 诱导恢复睡眠剥夺后的记忆巩固** | FTR：睡眠剥夺0.45±0.09 → 诱导后0.56±0.08（vs 正常睡眠0.61±0.08）；F=7.34, p=0.005 | DOI:10.1038/s41593-026-02318-9 (PMC12632314) | 中-高（动物；局限于感觉运动记忆） |

## 争议

**SHY 的替代解释**：
1. **昼夜节律解释**：部分突触缩小可能受节律性分子时钟驱动（非睡眠本身）
2. **体温/能量状态解释**：睡眠期间体温下降可能直接影响突触功能而非塑性
3. **SHY 与主动巩固的矛盾**：（见 Q-shy-vs-active-consolidation）→ 已通过 down-selection 框架部分调和，但单突触层面实验证据仍待补全

**SHY 与 Turrigiano 的比较**：两者都是稳态可塑性，但 SHY 特异于睡眠周期触发的每日波动，而 Turrigiano 稳态缩放针对数天至周的异常活动偏移。两者可能同时工作，时间尺度不重叠。

## 连接

- [[synaptic-scaling]] — Turrigiano 的突触稳态缩放；与 SHY 同为稳态可塑性，但机制/时间尺度不同
- [[homeostatic-plasticity]] — SHY 是稳态可塑性的睡眠专属形式
- [[so-spindle-swr-coupling]] — 三重耦合机制中，SO 驱动 SHY；SWR 提供保护机制
- [[cortical-slow-oscillation]] — SO UP state 是 SHY 下调的直接触发器
- [[memory-consolidation]] — SHY（整体下调）与主动巩固（选择性加固）通过 down-selection 统一
- [[ltp]] — 清醒 LTP 积累→SHY 在睡眠中反向下调是整套机制的两端

## 未解问题

- Q-shy-vs-active-consolidation（高优先）：能否在同一个实验中同时追踪"被 SWR 保护的突触"和"被下调的突触"，直接验证 down-selection？
- Q-shy-molecular-mechanism：SO UP state 驱动突触 LTD 的分子触发器是什么？是 NMDAR 激活阈下的 Ca²⁺ 信号、mGluR 激活，还是内源性大麻素系统？
- Q-shy-onoff-bistability-human（高优先）：经颅交流电刺激（tACS）或重复 TMS 序列能否在人类皮层中诱导可靠的 ON/OFF 双稳态周期？若能，是否能复现 Driessen 2026 在小鼠中观察到的突触下调和记忆效应？这是 SHY 人类治疗转化的关键障碍。

## 修订历史

- 2026-07-07 · 创建 · 基于《三重协奏》(#75) · 初始置信度：中（超微结构直接证据强，但分子机制和 down-selection 的单突触验证仍待完成）
- 2026-10-14 · 修订 rev2 · 基于《清醒中的"睡眠"》(#174) · 新增 Driessen et al. 2026 直接因果证据：清醒小鼠皮层 ON/OFF 诱导→突触 GluA1 下调+SWA 减少+记忆恢复，强直性抑制无效 → 将 ON/OFF 双稳态确立为突触稳态的充分执行单元；confidence 从 medium 升至 high；related 新增 up-down-state-mechanism、ampa-receptor；prerequisites 新增 cortical-slow-oscillation；opens_questions 新增 Q-shy-onoff-bistability-human；key_sources 新增 DOI:10.1038/s41593-026-02318-9 和 PMID:24411729

## 来源文章

- [[2026-07-07-sleep-memory-consolidation-so-spindle-swr]]
- [[2026-10-14-cortical-onoff-periods-sleep-shy-validation]]

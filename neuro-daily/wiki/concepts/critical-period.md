---
title: 关键期
slug: critical-period
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-28
updated: 2026-06-28
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, behavior, cognition]
related: [pv-interneurons, ltp, hebbian-learning, gamma-oscillations, adult-neurogenesis, binding-by-synchrony]
prerequisites: [pv-interneurons, synaptic-transmission, ltp]
opens_questions: [Q-cp-01, Q-cp-02, Q-cp-03]
source_articles: [2026-06-28-critical-period-visual-cortex]
key_sources: ["PMID:9822384", "PMID:10724170", "PMID:12424383", "PMID:21068299", "PMID:32503914", "PMID:33293360"]
---

# 关键期 (Critical Period)

> **一句话定义**：发育过程中一段有限的时间窗口，期间神经回路对特定感觉经验具有极高可塑性；由 PV 中间神经元的成熟和 E/I 平衡阈值启动，由围神经元网（PNN）积累以及髓磷脂相关抑制因子的出现而关闭。

## 当前理解

我们现在认为，大脑皮层的深度可塑性（回路水平的突触重组）不是发育进程中的默认状态，而是被一套精密的分子许可机制主动"开启"和"关闭"的。关键期代表了这一许可系统的核心运行阶段。

在视觉皮层，关键期由 PV 快速刺激中间神经元的成熟触发：当 PV 细胞发育成熟，皮层兴奋-抑制（E/I）比值到达特定阈值时，皮层获得精确检测两眼竞争性输入差异的能力，眼优势可塑性（关键期的标准读出）随之开启。这一时机受到至少三条并行调控时钟的控制——内在发育程序（CLOCK/BMAL 昼夜节律基因）、来自视网膜的跨突触 Otx2 信号，以及视觉活动驱动的 BDNF 分泌。

关键期的关闭由 PNN（主要由 CSPG 构成）在 PV 细胞周围的积累执行：PNN 中的 CSPG 激活受体型磷酸酶 PTPσ，后者使 PV 神经元上的 TRKB 受体持续去磷酸化，阻断 BDNF-TRKB 驱动的可塑性信号通路。髓磷脂相关抑制因子（Nogo/NgR/PirB）则作为平行的结构性制动机制，限制轴突侧支生长和突触重组。

成年大脑并非"不可改变"——关键期关闭的实质是可塑性阈值的显著提高，而非可塑性能力的消失。通过 ChABC（降解 PNN）、氟西汀（直接阻断 PTPσ-TRKB 相互作用）、富集环境、暗养或表观遗传干预（HDAC 抑制剂），可以在成年大脑中部分重启关键期相关可塑性。ChABC 和氟西汀的共同下游靶点均为 PV 神经元中 TRKB 的磷酸化激活（Lesnikova et al. 2021）。

## 关键机制

### 分子层面

**关键期开启通路**：
- 三条分子时钟整合决定 PV 细胞成熟时机：
  1. CLOCK/BMAL 昼夜节律基因 → 内在发育时钟
  2. 视网膜 Otx2（homeoprotein）→ 跨突触激活皮层 PV 细胞成熟程序
  3. BDNF → 通过 TRKB 促进 PV 细胞突触效率提高
- PV 细胞成熟 → 突触 GABA 效能提高 → E/I 平衡到达关键期触发阈值
- GAD65 敲除（GABA 合成减少）→ 阻止关键期开启；地西泮（增强 GABA 效能）→ 可提前触发关键期

**关键期关闭通路（PNN 分子机制）**：
- PNN 中 CSPG 积累 → 激活 PTPσ（受体型酪氨酸磷酸酶）
- 激活的 PTPσ → 使 PV 神经元 TRKB 去磷酸化（失活状态）
- TRKB 失活 → 阻断 BDNF 下游信号（MAPK/ERK、PI3K/Akt）→ 可塑性信号关闭
- 平行机制：髓磷脂-Nogo/NgR/PirB → RhoA/ROCK → 抑制突触结构重排

**关键期重启通路**：
- ChABC → 降解 CSPG → 减少 PTPσ 激活 → TRKB 磷酸化恢复 → 可塑性信号开启
- 氟西汀 → 与 TRKB 跨膜域结合 → 空间位阻阻断 PTPσ-TRKB 接触 → TRKB 激活
- HDAC 抑制剂 → 增加组蛋白乙酰化 → 重新开放发育期基因表达 → 部分可塑性恢复

### 细胞层面

- PV 阳性快速刺激中间神经元（Fast-spiking PV Interneurons）：发放频率高（≤数百 Hz），时间精度高，是 E/I 平衡的主要调节者
- PV 细胞成熟标志：PV 蛋白表达上调、髓鞘化程度增加、突触 GABA 释放量增大、约 40 Hz γ 振荡功率升高
- PNN 形成：主要包绕 PV 细胞（及部分运动神经元），由星形胶质细胞和神经元共同分泌的 CSPG（aggrecan、brevican 等）与 Hyaluronan、Tenascin-R 组装而成

### 回路层面

- E/I 平衡调控：关键期开启需要"足够但不过剩"的抑制（精确的量阈值，Fagiolini & Hensch 2000）
- γ 振荡（~40 Hz）：PV 细胞成熟的功能性读出；关键期开启时 γ 功率升高；暗养阻断 γ 升高并延迟关键期
- 竞争性突触消除：在适宜 E/I 背景下，活动强的突触（开眼）增强，活动弱的突触（闭眼）被消除

### 系统层面

- 眼优势柱重组（视觉皮层）：关键期内单眼遮蔽 4-5 天即可引起可测量的眼优势转变（电生理 + 光学成像）
- 关键期时间窗口（物种差异）：小鼠 P21-P32，猫 3-7 周，人类视觉关键期持续数年
- 关键期序列性：低级感觉（视觉、听觉）→ 语言/音韵 → 社会情感 → 高级认知（前额叶），各有独立时间窗口

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| GABA 回路是关键期开启的必要触发器 | GAD65 KO 小鼠无眼优势可塑性；地西泮局部注射完全救援 | Hensch et al. 1998 (PMID:9822384) | 高 |
| 关键期时机由 GABA 量阈值（而非有/无）决定 | 提前给予地西泮可提前开启关键期 | Fagiolini & Hensch 2000 (PMID:10724170) | 较高（仅摘要） |
| PNN 积累与关键期关闭有因果关系 | PNN 积累时间进程与关键期关闭重合；暗养同时延迟二者；ChABC 降解 PNN 后成年大鼠重现眼优势可塑性 | Pizzorusso et al. 2002 (PMID:12424383) | 较高（仅摘要） |
| 成年可塑性受多重制动因子限制 | PNN（ChABC 治疗）、Nogo/NgR（KO 小鼠）、PirB（阻断实验）各自独立促进成年可塑性 | Bavelier et al. 2010 (PMID:21068299) | 较高（综述） |
| BDNF、Otx2 和昼夜节律基因调控关键期时机 | BDNF 过表达→提前关键期；Otx2 跨突触输入→调控 PV 成熟；CLOCK/BMAL KO→延迟关键期 | Reh et al. 2020 (PMID:32503914) | 较高（综述） |
| ChABC 和氟西汀共用 PV 神经元 TRKB/PTPσ 机制 | CSPG→PTPσ→TRKB 去磷酸化链；ChABC 和氟西汀分别通过不同入口恢复 TRKB 磷酸化 | Lesnikova et al. 2021 (PMID:33293360) | 高 |

## 连接

- [[pv-interneurons]] — PV 快速刺激中间神经元的成熟是关键期开启的直接触发器；PV 细胞也是 PNN 的主要包绕对象和 TRKB/PTPσ 机制的主要细胞底物
- [[ltp]] — 关键期内眼优势可塑性依赖于 LTP/LTD 机制；关键期是发育期 LTP 正常表达的必要背景条件
- [[hebbian-learning]] — 关键期可塑性是 Hebb 突触竞争规则的典型体现：活动强的眼优势突触增强，活动弱的被消除
- [[gamma-oscillations]] — γ 振荡是 PV 细胞成熟的功能性读出，与关键期开启时机高度相关（Reh et al. 2020）
- [[adult-neurogenesis]] — 成年神经发生是成年大脑可塑性的另一条途径，与关键期重启机制部分共享调控节点（BDNF、富集环境）
- [[binding-by-synchrony]] — PV 细胞驱动的 γ 同步振荡不仅与关键期相关，也是皮层特征整合的核心机制

## 未解问题

- **Q-cp-01**：PNN 去除（ChABC）的长期安全性与特异性？PNN 同时参与记忆稳定性、离子缓冲和突触保护功能——靶向降解 PNN 以重开可塑性，是否会代价性地破坏依赖 PNN 稳定性的已有记忆痕迹？如何实现对可塑性重开的时空精确控制？
- **Q-cp-02**：人类关键期的分子机制是否与啮齿类根本相同？人类大脑发育时间尺度远长于小鼠，PNN 形成动态、PV 细胞成熟进程和 Otx2/CLOCK 机制是否在人类中有相同的因果作用？在人类中进行类似干预的安全性和有效性尚未可知。
- **Q-cp-03**：语言习得、社会认知等高级认知关键期是否也涉及 PV/PNN 机制，还是有完全不同的分子基础？目前几乎所有直接机制研究来自视觉皮层；高级认知关键期的分子机制接近空白。

## 修订历史

- 2026-06-28 · 创建 · 基于《发育的窗口：大脑关键期如何开启、关闭与重启》· 初始置信度：高

## 来源文章

- [[2026-06-28-critical-period-visual-cortex]]

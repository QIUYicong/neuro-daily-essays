---
title: 突触后致密体（兴奋性）
slug: postsynaptic-density
domain: concepts
type: structure
status: established
confidence: high
created: 2026-08-06
updated: 2026-09-06
revision_count: 2
dimensions: [molecular, synaptic, cellular]
related: [synaptogenesis, neuroligin-neurexin, gephyrin-scaffold, ltp, camkii, working-memory, psd-95, tarp-auxiliary-subunit, silent-synapse]
prerequisites: [synaptic-transmission, neuroligin-neurexin]
opens_questions: [Q-synaptogenesis-01]
source_articles: [2026-08-06-synaptogenesis-molecular-assembly]
key_sources: ["PMID:41614918", "PMID:30359597"]
---

# 突触后致密体（兴奋性）(Postsynaptic Density, PSD)

> **一句话定义**：兴奋性谷氨酸能突触后膜下方的纳米蛋白质结构（厚 30–100 nm），由 PSD-95/MAGUK、GKAP、Shank 和 Homer 构成三层级联骨架，将 AMPA 和 NMDA 受体精确锚定在释放位点正对面，是突触可塑性的物理基础。

## 当前理解

我们现在认为，PSD 不是固态的蛋白胶块，而是一个具有**层次化纳米结构**的动态分子机器。冷冻电子断层重建显示，PSD 由大小异质的"纳米亚结构单元（nanoblocks）"拼接而成，O 型（环状）和 Y 型（叉形）颗粒对应不同的受体-骨架复合物。在 LTP 诱导后，"新生区"可在 5 分钟内转变为功能性活跃区（Ramírez-Expósito 2026, PMC12840169）。

PSD 的三层架构（从膜近端到深部）：
1. **膜近端层**：PSD-95 垂直排列，通过 PDZ1/2 抓住 NMDA 受体 GluN2B 亚基的 -ESDV 末端；TARP 介导 AMPA 受体与 PSD-95 的间接耦联
2. **转接层**：GKAP 连接 PSD-95 的 GK 域与深部 Shank 骨架
3. **深部骨架层（pallium）**：Shank 和 Homer 通过四聚体螺旋自组装形成网格；Homer 的 EVH1 域与 mGluR1/5 C 端结合，将代谢型谷氨酸受体锚定于 NMDA 受体附近

这个三层机构决定了突触的计算属性：PSD-95 的磷酸化和泛素化动态调控受体密度（LTP/LTD 的分子执行者）；Shank 影响突触棘形态和 mGluR 信号动力学；CaMKII 在活动期进入骨架层，加速 LTP 固化。

## 关键机制

### 分子组成（从膜近端到深部）

**PSD-95 / MAGUK 家族**：
- PSD-95（=SAP90）：PDZ1/2 结合 NMDA-GluN2B -ESDV；PDZ3 结合 NL1 的 C 端序列（整合突触粘附与骨架）；SH3+GK 域与 GKAP 连接
- 相关成员：SAP97、SAP102、PSD-93，各有空间和发育特异性

**GKAP / SAPAP**：
- GKAP N 端与 PSD-95 GK 域结合；C 端与 Shank PDZ 域结合
- 四个 GKAP 蛋白（GKAP1–4）提供分子多样性

**Shank（ProSAP）**：
- 通过 SAM 域四聚体化形成 Shank 网格
- 含 PDZ（接 GKAP）、SH3（接 Homer/Cortactin）和 Ank 重复序列（接 SpinophilinA/PP1）
- 三个亚型：Shank1（突触前亚型）、Shank2、Shank3（纹状体高表达）

**Homer**：
- Homer 长型（Homer1b/1c、Homer2/3）通过 CC（coiled-coil）域四聚体化形成 Homer 网格
- EVH1 域结合 mGluR1/5 的 PPXXF 基序，把 mGluR 锁在 NMDA 受体旁
- Homer 短型（Homer1a）：活动诱导表达，无 CC 域，充当竞争性抑制剂，使突触进入可塑状态

**CaMKII**：
- 突触活动激活后进入 pallium 层
- 磷酸化 GluA1 S831，促进 AMPA 受体插入
- 磷酸化 Shank3，调控突触棘形态

### 组装过程

突触形成初期，NL1 将 PSD-95 分子招募至接触点（NL1 的 C 端 PDZ 结合基序 + PSD-95 PDZ3）；PSD-95 进而通过 GKAP 联接 Shank/Homer；Shank/Homer 自组装形成骨架层；最终 AMPA 受体通过 TARP 蛋白（γ-2 即 Stargazin 等）插入并被 PSD-95 侧向稳定。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| PSD 三层架构（PSD-95→GKAP→Shank/Homer） | 免疫电镜 + 超分辨荧光（STORM/STED）+ 蛋白质互作（BiFC/Co-IP） | PMID:41614918（Ramírez-Expósito 2026） | 高 |
| LTP 后 5 分钟内 PSD 纳米亚结构单元重组 | 活细胞冷冻电镜断层扫描时序实验 | PMID:41614918（Ramírez-Expósito 2026） | 中（近期技术数据，待独立重复） |
| PSD-95 PDZ 域直接结合 NL1 C 端 | GST pull-down + 晶体结构 | 多篇生化研究（综述：PMID:30359597） | 高 |
| Shank3 缺失 → 突触棘密度降低 + ASD 样行为 | Shank3 条件 KO 小鼠 | PMID:36846568（综述）| 高 |

## 连接

- [[neuroligin-neurexin]] — NL1 通过 PDZ 结合基序直接招募 PSD-95，是 PSD 组装的上游触发
- [[gephyrin-scaffold]] — 抑制性突触的平行骨架系统
- [[ltp]] — LTP 通过 CaMKII 磷酸化和 AMPA 受体插入在 PSD 层面实现；PSD 是 LTP 的物理底座
- [[camkii]] — PSD 的活动传感器和效应分子
- [[synaptogenesis]] — PSD 在突触生成过程中从接触点逐步组装

## 未解问题

- Q-synaptogenesis-01：突触从接触到第一个功能性 AMPA 电流的体内时间进程？
- Q-psd-01：各层蛋白分子的定量（绝对分子数）在活体突触中是否已精确确定？不同神经元类型的 PSD 组成差异？

## 修订历史

- 2026-09-06 · 修订 rev2 · 基于《PSD-95：兴奋性突触的主控分子》(#136) · related 新增 psd-95、tarp-auxiliary-subunit、silent-synapse；独立 psd-95 页面已创建（填补 silent-synapse 文章创建的悬空引用）
- 2026-08-06 · 创建 · 基于《轴突找到伙伴之后：突触如何从分子装配线上诞生》(#105) · 初始置信度：高

## 来源文章

- [[2026-09-06-psd95-synaptic-scaffold]]
- [[2026-08-06-synaptogenesis-molecular-assembly]]

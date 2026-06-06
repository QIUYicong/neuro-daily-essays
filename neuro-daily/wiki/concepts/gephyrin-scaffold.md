---
title: Gephyrin 抑制性突触骨架
slug: gephyrin-scaffold
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-06
updated: 2026-08-06
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [synaptogenesis, neuroligin-neurexin, postsynaptic-density, inhibitory-synapse, gaba]
prerequisites: [synaptic-transmission, neuroligin-neurexin]
opens_questions: [Q-synaptogenesis-03]
source_articles: [2026-08-06-synaptogenesis-molecular-assembly]
key_sources: ["PMID:41614918", "PMID:41824561"]
---

# Gephyrin 抑制性突触骨架 (Gephyrin Inhibitory Postsynaptic Scaffold)

> **一句话定义**：Gephyrin 是抑制性（GABAergic/甘氨酸能）突触后的核心组织蛋白，在 Collybistin（Cdc42 GEF）辅助下在突触后膜下方铺设六角形格栅，通过捕获侧向扩散的 GABA-A 受体（α/β3 亚基的胞内环）建立抑制性突触的受体锚定平台。

## 当前理解

我们现在认为，抑制性突触的突触后组织不是 PSD-95 三层骨架的变体，而是一套完全独立的、以 Gephyrin 为核心的**格栅锚定系统**。Gephyrin 最初因从脊髓提纯甘氨酸受体时被共分离而被发现；后来证明它对 GABAergic 突触同样不可或缺。

Gephyrin 以六角形格栅形式自组装（G 域参与六聚体化，E 域参与蛋白配体结合），通过 Collybistin 的 GEF 活性激活 Cdc42 而定向锚定至 GABAergic 接触点。NL2 是抑制性突触特异性的上游信号——NL2 聚集时通过其胞质域解除 Collybistin 的自抑制，从而在 NL2-NRXβ1 接触点精确启动 Gephyrin 格栅铺设（Boyd et al. 2026, PMC12985673）。

GABA-A 受体不是"主动靶向"到 Gephyrin 格栅，而是通过**侧向扩散+陷阱捕获模型**被动富集：受体先在细胞膜上扩散，随机进入 Gephyrin 格栅区域后被 α/β3 亚基的胞内大环（IL）与 Gephyrin E 域的相互作用"卡住"。这种机制使抑制性突触的受体密度可以通过改变 Gephyrin 格栅大小或受体侧向扩散速率动态调节。

## 关键机制

### 分子结构

**Gephyrin**：
- G 域（N 端）：GTPase 样；参与三聚体化（与 MoeA 同源）
- C 域（中央）：连接器，含磷酸化位点（Ser-268/270；招募 Pin1）和可变剪接盒（C3、C5 等）
- E 域（C 端）：受体结合域；结合 GABA-A-α/β 亚基 IL 环、甘氨酸受体 β 亚基 IL 环、Collybistin SH3 域

**Collybistin（CB）**：
- DH/PH 域（RhoGEF）：催化 Cdc42 GDP→GTP 交换
- SH3 域：自抑制 / 配体（NL2/GABARAPL2）解除自抑制
- 膜定位：通过 PH 域结合 PI(3)P，将 Gephyrin 格栅导向 GABAergic 膜区域

### 组装流程

1. NL2 识别 NRXβ1（抑制性接触点标志）→ NL2 聚集
2. NL2 胞质域直接结合 Collybistin SH3 域，解除 CB 自抑制
3. 激活的 CB（DH/PH 活性上调）激活 Cdc42
4. Gephyrin 通过 G 域六聚体化形成格栅，格栅通过 CB-PI(3)P 定向锚定至接触点膜
5. GABA-A 受体侧向扩散进入格栅区，α/β3 IL 环被 Gephyrin E 域捕获 → 受体密度 >1000/μm²

### 可塑性调节

- Gephyrin C 域 Ser-268/270 磷酸化（ERK/GSK3β）→ 招募 Pin1 脯氨酸异构酶 → 格栅构象改变（增大/缩小）
- NL2 被 MMP 蛋白酶切割（活动依赖）→ 破坏 NL2-NRX 接合 → Gephyrin 解聚 → 抑制性突触弱化
- Neurosteroids（如别孕烷醇酮）通过 GABA-A 的 δ 亚基增强受体开放概率，间接减少受体对格栅位点的需求（抑制性稳态可塑性）

### 与甘氨酸能突触的差异

甘氨酸受体（GlyR）的 β 亚基 IL 环与 Gephyrin E 域亲和力**高于** GABA-A（解离常数约 1–10 nM vs. μM 级），因此 GlyR 在 Gephyrin 格栅上的固定比 GABA-A 受体更稳定、扩散更慢。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| Gephyrin 缺失→ GABA-A/GlyR 弥散（无突触聚集） | Gephyrin 全身 KO 和条件 KO 小鼠 | 综述：PMC12840169 | 高 |
| NL2 解除 Collybistin 自抑制 → Gephyrin 定向 | Collybistin SH3 截短突变体 + 荧光定位实验 | 综述：PMC12840169 | 高 |
| NL2 聚集同步招募 Gephyrin + GlyR | HEK293 共培养 + 荧光定量 + 受体密度 >1000/μm² | PMID:41824561（Boyd 2026, PMC12985673） | 高 |
| 侧向扩散+陷阱捕获模型 | 单分子追踪（sptPALM）+ 光漂白恢复（FRAP） | 多篇独立研究（综述：PMC12840169）| 高 |

## 连接

- [[neuroligin-neurexin]] — NL2 是 Gephyrin 格栅定向组装的上游信号
- [[postsynaptic-density]] — 兴奋性突触的平行（但完全独立）骨架系统
- [[synaptogenesis]] — 抑制性突触生成的后端装配步骤
- [[inhibitory-interneuron]] — 放电的 PV/SOM 中间神经元对提供的 GABA 输入在这里被 Gephyrin 格栅捕获

## 未解问题

- Q-synaptogenesis-03：突触初始装配与稳定化（抗修剪）的分子机制是否独立？Gephyrin 格栅的"保留信号"是什么？

## 修订历史

- 2026-08-06 · 创建 · 基于《轴突找到伙伴之后：突触如何从分子装配线上诞生》(#105) · 初始置信度：高

## 来源文章

- [[2026-08-06-synaptogenesis-molecular-assembly]]

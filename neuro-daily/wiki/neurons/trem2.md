---
title: TREM2（髓系细胞触发受体2）
slug: trem2
domain: neurons
type: mechanism
status: mainstream
confidence: high
created: 2026-09-17
updated: 2026-09-17
revision_count: 1
dimensions: [molecular, cellular, disease]
related: [microglia, disease-associated-microglia, neuroinflammation, alzheimers-disease, synaptic-pruning, apoe4]
prerequisites: [microglia, synaptic-transmission, action-potential]
opens_questions: [Q-dam-01, Q-dam-02, Q-dam-04]
source_articles: [2026-06-03-microglia-synaptic-pruning, 2026-09-17-neuroinflammation-microglia-dam-trem2]
key_sources:
  - "PMID:24316888"
  - "PMID:28602351"
  - "PMID:28930663"
  - "PMCID:PMC5719893"
  - "PMID:23150934"
  - "PMCID:PMC3631573"
  - "PMID:23150908"
  - "PMCID:PMC3677583"
  - "PMID:41787076"
---

# TREM2（髓系细胞触发受体2 / Triggering Receptor Expressed on Myeloid Cells 2）

> **一句话定义**：TREM2是小胶质细胞表面的跨膜脂质传感器和危险信号受体，通过DAP12→PI3K→Akt→mTOR信号通路促进细胞存活、增殖和吞噬，是DAM（疾病相关微胶质细胞）Step 2激活的分子开关，也是阿尔茨海默病的重要遗传风险因子（R47H变异OR≈3-5×）。

---

## 当前理解

我们现在认为，TREM2是小胶质细胞在神经退行性疾病中的核心传感器，执行双重功能：
1. **配体识别**：感知凋亡细胞（磷脂酰丝氨酸/PS）、APOE蛋白、脂质聚集物（可能包括Aβ相关脂质）等危险信号
2. **效应器激活**：通过DAP12（TYROBP）→PI3K→Akt→mTOR促进小胶质细胞在疾病位点的存活、增殖和完整吞噬功能

2013年两篇同期NEJM论文确定了TREM2 R47H（精氨酸→组氨酸）变异与AD的强遗传关联（OR 2.92-4.5），从遗传学方向迫使神经科学界将小胶质细胞免疫功能纳入AD病理机制的核心。

TREM2的功能性角色存在双向解读：保护性（围堵斑块、吞噬Aβ）还是有害性（驱动APOE自分泌→稳态基因丢失→MGnD）——这一争论的解答可能依赖于疾病阶段。2026年INVOKE-2 Phase 2临床试验（TREM2激动抗体AL002c）的阴性结果提示，在临床确诊的早期AD阶段靶向TREM2不足以逆转认知衰退，时间窗口可能是关键。

---

## 关键机制

### 1. 结构与配体识别

TREM2是Ⅰ型跨膜蛋白（免疫球蛋白超家族），通过短跨膜域与**DAP12（TYROBP）**形成非共价信号复合体。DAP12携带胞内ITAM（免疫受体酪氨酸激活基序）。

**TREM2配体**（已确认或强证据）：
- **磷脂酰丝氨酸（PS）**：凋亡细胞外翻到外叶膜的标志性脂质（"吃我"信号）
- **APOE蛋白**：特别是APOE4型，TREM2直接识别APOE参与脂质转运
- **硫酸软骨素蛋白聚糖（CSPGs）**：细胞外基质成分
- **脂多糖（LPS）和其他微生物脂质**（感染相关）
- **可能**：Aβ聚集体表面的磷脂成分（机制尚不完全清楚）

**R47H变异的分子影响**：精氨酸47位于TREM2配体结合区，R→H替换显著削弱了TREM2对PS和APOE的结合亲和力（体外结合实验），导致小胶质细胞对凋亡信号和Aβ的吞噬效率降低。

### 2. 下游信号通路

```
TREM2配体识别 → TREM2聚集
                    ↓
              DAP12（TYROBP）ITAM磷酸化（Src激酶）
                    ↓
              Syk激酶招募
                    ↓
              PI3K → PIP3
                    ↓
              Akt → mTOR激活
                    ↓
    ┌─────────────────────────────┐
    ↓                             ↓
细胞存活↑（抗凋亡）           吞噬体形成↑
增殖信号↑（CSF1↑）          溶酶体生物合成↑
```

同时，TREM2信号还通过磷脂酰肌醇通路激活：DAG→PKC路线，以及通过SH2域招募多种适配蛋白协调细胞骨架重组（支持吞噬杯形成）。

### 3. TREM2与APOE轴（MGnD通路）

当TREM2识别PS并被激活后，触发小胶质细胞自分泌**APOE**。分泌的APOE通过自分泌/旁分泌回路：
- 抑制稳态转录因子MEF2A、MAFB、SMAD3
- 诱导miR-155（进一步降解稳态基因的mRNA）
- 结果：小胶质细胞稳态功能丧失，进入MGnD/DAM晚期状态

**关键实验**：选择性敲除小胶质细胞APOE（CX3CR1-Cre/APOE-flox）可在SOD1和APP-PS1模型中恢复homeostatic基因表达并减少神经元死亡——这说明TREM2→APOE通路的有害效果主要通过APOE自分泌介导（Krasemann et al. 2017，PMID:28930663/PMC5719893）。

---

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| TREM2 R47H→AD风险↑4.5× | 外显子测序7000+样本 | PMID:23150934/PMC3631573 | 高 |
| TREM2 R47H冰岛人群复制 OR≈2.92 | deCODE队列 | PMID:23150908/PMC3677583 | 高 |
| TREM2 Step 2 DAM依赖（TREM2-KO缺失Step 2 DAM） | scRNA-seq；TREM2-KO 5XFAD | PMID:28602351 | 高（小鼠） |
| TREM2→APOE自分泌→MGnD；阻断APOE→神经元保护 | CX3CR1-Cre APOE-KO；SOD1+APP-PS1 | PMID:28930663/PMC5719893 | 高（小鼠）/中（人类） |
| TREM2激动抗体Phase 2（INVOKE-2）：临床阴性 | 381人，早期AD，48-96周，CDR-SB | PMID:41787076 | 高（阴性结果） |
| TREM2信号通过DAP12→PI3K→Akt→mTOR | 体外激酶活性；siRNA阻断实验 | 多项基础研究 | 高 |

---

## 连接

- [[microglia]] — TREM2是小胶质细胞的关键表面受体；在稳态微胶质细胞上低表达，DAM中上调
- [[disease-associated-microglia]] — TREM2依赖的Step 2激活是DAM的分子开关
- [[neuroinflammation]] — TREM2→APOE轴是神经炎症转化的核心机制之一
- [[alzheimers-disease]] — R47H变异是AD遗传风险因子（仅次于APOE4）；TREM2功能直接影响Aβ清除
- [[synaptic-pruning]] — TREM2识别PS参与发育期突触剪枝（与DAM的配体重叠）
- [[apoe4]] — APOE4是TREM2的重要配体，也是AD最强遗传风险因子；两者在同一通路中交互

---

## 未解问题

- Q-dam-01（高）：TREM2激活的保护→有害翻转点在AD时间轴何处？
- Q-dam-02（高）：TREM2激动治疗的最优时间窗口——临床前MCI期vs症状前期？
- Q-dam-04（中）：APOE4携带者的TREM2-APOE轴激活幅度是否高于APOE3/APOE2？

---

## 修订历史

- 2026-06-03 · 隐式存在于 microglia.md 的 related 字段，未建页面
- 2026-09-17 · 创建正式页面 · 基于《大脑内守军的两张面孔》(文章#147) · 初始置信度：高（基础机制）；临床应用：中（INVOKE-2阴性）

---

## 来源文章

- [[2026-06-03-microglia-synaptic-pruning]]（隐式引用）
- [[2026-09-17-neuroinflammation-microglia-dam-trem2]]

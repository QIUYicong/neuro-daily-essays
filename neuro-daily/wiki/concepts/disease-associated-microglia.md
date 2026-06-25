---
title: 疾病相关微胶质细胞（DAM）
slug: disease-associated-microglia
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-09-17
updated: 2026-09-17
revision_count: 1
dimensions: [cellular, molecular, disease]
related: [microglia, neuroinflammation, trem2, alzheimers-disease, als-amyotrophic-lateral-sclerosis, parkinsons-disease, excitotoxicity]
prerequisites: [microglia, trem2, neuroinflammation]
opens_questions: [Q-dam-01, Q-dam-02, Q-dam-03, Q-dam-04]
source_articles: [2026-09-17-neuroinflammation-microglia-dam-trem2]
key_sources:
  - "PMID:28602351"
  - "PMID:29775591"
  - "PMID:28930663"
  - "PMCID:PMC5719893"
  - "PMID:31042697"
  - "PMCID:PMC6865822"
---

# 疾病相关微胶质细胞（DAM / Disease-Associated Microglia）

> **一句话定义**：DAM是在神经退行性疾病（特别是阿尔茨海默病）的斑块周围发现的一种特化小胶质细胞亚态，通过两步激活（第一步TREM2非依赖，第二步TREM2依赖）转化而来，具备强吞噬和脂质代谢能力——是保护性清除者还是慢性损伤的推手，取决于疾病阶段和信号背景。

---

## 当前理解

我们现在认为，DAM是小胶质细胞在面对神经退行性病理（淀粉样蛋白积累、凋亡神经元产生的危险信号）时激活的一种转录程序，由Keren-Shaul等人2017年利用单细胞RNA测序（scRNA-seq）在5XFAD小鼠模型中首次系统描述，并随后在ALS、老龄化小鼠及人类AD脑（Mathys 2019）中获得广泛验证。

**DAM vs 稳态小胶质细胞的对比**：

| 特征 | 稳态小胶质细胞 | DAM |
|------|--------------|-----|
| P2RY12 | ↑↑（高） | ↓↓ |
| TMEM119 | ↑↑ | ↓ |
| CX3CR1 | ↑↑ | ↓↓ |
| TREM2 | 低基线 | ↑↑ |
| APOE | 低 | ↑↑ |
| Cst7 | 低 | ↑↑ |
| LPL | 低 | ↑（脂质代谢） |
| CTSD | 低 | ↑（溶酶体降解） |
| Axl | 低 | ↑（凋亡细胞识别） |
| 吞噬能力 | 基础 | 显著增强 |

**注意**：Krasemann等2017年在同类研究中描述的MGnD（Microglia Neurodegenerative Phenotype）与DAM高度重叠，但重点不同——DAM论文强调保护性清除功能，MGnD论文强调稳态功能的丧失和潜在神经毒性。两者可能代表同一细胞状态的不同侧面，或不同疾病阶段的变体。

---

## 关键机制

### 两步激活的分子逻辑

**Step 1（TREM2非依赖）**：
- 触发信号：任何危险分子模式（DAMPs）、Aβ聚集体、IL-4等
- 效果：P2RY12↓、CX3CR1↓（稳态基因首波下调）；TREM2、APOE、Axl初步上调
- TREM2功能：此时TREM2上调，但Step 1的发生不需要TREM2（TREM2-KO小鼠中Step 1仍发生）

**Step 2（TREM2依赖）**：
- 触发信号：TREM2对PS（凋亡细胞膜外翻的磷脂酰丝氨酸）、APOE蛋白、脂质聚集物的识别
- TREM2信号：TREM2→DAP12（TYROBP）→Syk→PI3K→Akt→mTOR
- 效果：LPL↑（脂质代谢）、CTSD↑（溶酶体蛋白酶）、CSF1↑（促增殖）、Itgax↑
- 结果：细胞获得对Aβ的主动吞噬能力，在斑块周围形成致密微胶质细胞屏障

**关键证据**：TREM2-KO 5XFAD小鼠：Step 1 DAM正常出现，Step 2 DAM几乎缺失；斑块周围无屏障；斑块扩散更广；神经元损伤更重。

### 微胶质屏障（Microglial Barrier）

在5XFAD模型中，完整DAM在Aβ斑块周围形成紧密的多层微胶质细胞包裹，物理上限制斑块向外扩散，同时提供持续的局部吞噬压力。TREM2-KO小鼠中此屏障缺失，斑块形态更加"丝状"（filamentous）且周围神经元损伤更严重。这是DAM"保护性"假说的主要结构证据。

---

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| DAM两步激活（Step 1 TREM2非依赖，Step 2依赖）| scRNA-seq；TREM2-KO比较 | PMID:28602351 | 高（小鼠）/中（人类） |
| DAM内含吞噬的Aβ颗粒 | 电子显微镜 | PMID:28602351 | 高 |
| TREM2-KO→斑块屏障缺失→神经元损伤更重 | TREM2-KO 5XFAD形态分析 | PMID:28602351 | 高（小鼠模型） |
| 人类AD脑中DAM样细胞亚群确认（TREM2↑、APOE↑、CST7↑） | snRNA-seq 80,660核 | PMID:31042697/PMC6865822 | 高 |
| DAM在ALS、老龄化中也出现（普遍性） | SOD1小鼠、野生型老龄小鼠、ALS患者脊髓 | PMID:28602351; PMID:29775591 | 中（跨疾病扩展数据有限） |
| MGnD（DAM近亲）：阻断TREM2-APOE轴 → 神经元保护 | CX3CR1-Cre APOE-KO；急性损伤模型 | PMID:28930663/PMC5719893 | 中高 |

---

## 连接

- [[microglia]] — DAM是小胶质细胞的疾病激活态，前体细胞
- [[trem2]] — Step 2激活的分子开关；R47H变异阻止完整DAM形成
- [[neuroinflammation]] — DAM是神经炎症的重要执行者
- [[alzheimers-disease]] — DAM是AD病理微环境的核心组成部分
- [[als-amyotrophic-lateral-sclerosis]] — ALS中也发现DAM样签名
- [[excitotoxicity]] — DAM产生的炎性信号可协同增强兴奋毒性
- [[complement-cascade-cns]] — 补体信号可触发DAM Step 1（部分机制）

---

## 未解问题

- Q-dam-01（高）：DAM是保护性的还是有害的？在AD时间轴上的哪个点发生功能翻转？
- Q-dam-02（高）：小鼠5XFAD中的微胶质屏障在人类AD中是否存在同等功能性结构？人类AD晚期小胶质细胞的耗竭（senescence）是否使屏障在临床相关时间点缺失？
- Q-dam-03（中）：MGnD与DAM之间是否是同一细胞状态的不同侧面，还是具有不同功能后果的不同状态？
- Q-dam-04（中）：APOE4携带者的TREM2-APOE轴激活强度是否高于APOE3，导致MGnD更重——解释APOE4与AD风险的部分机制？

---

## 修订历史

- 2026-09-17 · 创建 · 基于《大脑内守军的两张面孔》(文章#147) · 初始置信度：高（小鼠机制）；人类功能意义：中

---

## 来源文章

- [[2026-09-17-neuroinflammation-microglia-dam-trem2]]

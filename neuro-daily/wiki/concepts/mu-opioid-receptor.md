---
title: μ阿片受体
slug: mu-opioid-receptor
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-14
updated: 2026-06-14
revision_count: 1
dimensions: [molecular, cellular, synaptic]
related:
  - endogenous-opioids
  - kappa-opioid-receptor
  - descending-pain-modulation
  - vta
  - placebo-analgesia
  - gaba
prerequisites:
  - ion-channels
  - synaptic-transmission
opens_questions:
  - Q-opioid-02
source_articles:
  - "articles/2026-06-14-endogenous-opioid-system-analgesia-reward.md"
key_sources:
  - "PMID:29852083 (Corder et al. 2018, Annu Rev Neurosci) - PMC6428583"
  - "PMC6224460 (Valentino & Volkow 2018, Neuropsychopharmacology)"
---

# μ阿片受体 (Mu Opioid Receptor, MOR)

> **一句话定义**：由 *Oprm1* 基因编码的 Gi/Go 偶联 GPCR，是内源性阿片系统的核心受体，通过抑制腺苷酸环化酶、激活 GIRK 和抑制电压门控钙通道产生神经抑制，分布于 PAG、VTA、NAc、ACC 等关键区域，介导镇痛、欢愉感和社会奖励。

## 当前理解

μ 受体（MOR/MOPR）是三类经典阿片受体中临床最重要、研究最深入的亚型：
- 主要内源性配体：β-内啡肽（最高亲和力）、met-脑啡肽
- 分子量约 45 kDa，7 次跨膜（A 类 GPCR），存在多种 C 端剪接变体
- 与其他三类阿片受体（DOR/KOR/NOP）氨基酸序列 >60% 同源（Corder et al. 2018）

**信号通路**（Gi/Go 偶联）：
```
MOR 激动 → Gαi 抑制 AC → cAMP↓（蛋白激酶 A 下调）
          → Gβγ 激活 GIRK 钾通道 → 膜超极化
          → Gβγ 抑制 N/P/Q 型 VGCCs → Ca²⁺↓ → 递质释放减少
```

**偏向信号（contested）**：同一受体激活后可进入 G 蛋白通路（镇痛）或 β-arrestin 通路（耐受/副作用），不同配体对两条通路的偏向程度不同。Gi-biased 激动剂（如 PZM21）理论上可分离镇痛与副作用，但临床证据尚不充分（Valentino & Volkow 2018）。

**关键分布**：
- PAG（vlPAG）：GABAergic 中间神经元突触前 MOR → 去抑制下行镇痛
- VTA：GABAergic 中间神经元 MOR → 去抑制 DA 神经元 → 奖励
- NAc 壳：直接 MOR 激活 → 阿片性"喜欢"(liking)
- ACC / 前额叶：参与认知驱动镇痛（安慰剂效应）

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| MOR 在 PAG GABAergic 末梢（突触前）发挥去抑制 | 脑片 IPSC 记录 | PMID:31971607 | 高 |
| 安慰剂激活 ACC/NAc 的 MOR | PET ¹¹C-卡芬太尼 | PMID:16120776 | 高 |
| OPRM1(-/-) 小鼠社交互动缺陷 | 基因敲除行为 | PMC6016638 | 高（动物） |
| Gi-biased agonist 减少耐受？ | PZM21 啮齿类数据（有争议） | PMC6224460 | 低-中 |

## 连接

- [[endogenous-opioids]] — 所属系统
- [[descending-pain-modulation]] — PAG/RVM 镇痛中的核心角色
- [[vta]] — VTA 中通过 MOR 去抑制 DA 神经元
- [[placebo-analgesia]] — 期待激活 MOR 产生镇痛
- [[kappa-opioid-receptor]] — 功能相对的受体（μ=欢愉，κ=烦躁）

## 修订历史

- 2026-06-14 · 创建 · 基于《同一把钥匙，三扇门》(#192) · 初始置信度：高

## 来源文章

- [[2026-06-14-endogenous-opioid-system-analgesia-reward]] (#192)

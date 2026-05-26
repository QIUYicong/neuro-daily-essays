---
title: 突触结合蛋白（Synaptotagmin）
slug: synaptotagmin
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-05-25
updated: 2026-05-25
revision_count: 1
dimensions: [molecular, synaptic]
related: [SNARE-complex, synaptic-transmission, active-zone, complexin, calcium-channel]
prerequisites: [SNARE-complex, synaptic-transmission]
opens_questions: [Q-syt7-facilitation-mechanism, Q-syt-isoform-specificity]
source_articles: [2026-05-25-synaptic-vesicle-exocytosis]
key_sources: ["PMID:22068972", "PMID:23060190", "PMID:37891212"]
---

# 突触结合蛋白（Synaptotagmin）

> **一句话定义**：Synaptotagmin是位于突触囊泡膜上的钙传感器蛋白，通过其C2A和C2B结构域感知局部钙离子浓度升高，并通过物理桥接两层膜、调控SNARE复合体最终拉合来触发毫秒级神经递质释放。

## 当前理解

Synaptotagmin（Syt）家族含17个成员，其中**Syt1、Syt2、Syt9**是快速同步神经递质释放的主要钙传感器（Syt2反应最快，Syt9中等），**Syt7**则参与异步释放和短时程突触易化（PMID:22068972）。

**结构：**
- 单个跨膜区锚定于囊泡膜
- 胞内侧：两个C2结构域（C2A + C2B），通过柔性连接子相连
- C2结构域是由8股β折叠片构成的刚性椭圆形结构，顶端有钙结合环
  - C2A：结合2个Ca²⁺
  - C2B：结合3个Ca²⁺；额外含一个"基本斑块"（basic patch），靶向PI(4,5)P₂

**触发机制（当前最佳模型）：**
1. Ca²⁺进入结合位点后，C2域顶端的钙结合环与磷脂双层疏水浅层结合（部分插入）
2. C2B同时与SNARE复合体和突触前膜的PI(4,5)P₂结合——**跨膜桥接**，将囊泡膜与突触前膜拉近数纳米
3. 解除Complexin对SNARE C端的位阻封闭
4. SNARE拉链急速完成，膜融合发生

磷脂环境使Syt1的表观Ca²⁺亲和力提高**2-3个数量级**，与局部钙浓度高度匹配（PMID:22068972）。

**速度：** Syt1触发融合的延迟约100-200微秒（calyx of Held系统测量）。

## 关键机制

### C2域的钙结合与膜作用
- 钙结合是电中性补偿：Ca²⁺协调Asp残基和水分子，消除C2域顶端的负电荷，暴露疏水面插入膜
- C2B的basic patch（多个Lys和Arg）靶向突触前膜富含PIP₂的区域，是定向结合的关键

### 多传感器模型（Syt1 + Syt7）
Norman et al. (2023) 计算模型显示：Syt1（低钙亲和力，快速反应）负责触发同步释放；Syt7（高钙亲和力，慢速反应）在重复刺激后的残余钙中介导短时程易化（PMID:37891212）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Syt1是快速同步释放的主要传感器 | Syt1敲除→同步释放消失；重表达→恢复 | PMID:22068972 | 极高 |
| C2B域对释放比C2A更关键 | 点突变阻断Ca²⁺结合的差异实验 | PMID:22068972 | 高 |
| Syt7介导异步释放与短时程易化 | Syt7敲除 + 双敲除实验 | PMID:37891212 | 中 |
| 磷脂将Syt1表观Ca²⁺亲和力提高2-3个数量级 | 脂质结合实验 | PMID:22068972 | 高 |

## 连接

- [[SNARE-complex]] — Syt1通过物理接触调控SNARE最终拉合
- [[synaptic-transmission]] — Syt是触发突触传递的关键开关
- [[complexin]] — Syt1与Complexin协同：Syt解除Complexin锁定
- [[calcium-channel]] — 钙通道开放是Syt激活的上游信号

## 未解问题

- Q-syt7-facilitation-mechanism：Syt7如何精确介导短时程易化？残余钙浓度阈值是多少？
- Q-syt-isoform-specificity：不同突触类型为何选择不同Syt亚型？是否与精确的钙动力学匹配有关？

## 修订历史

- 2026-05-25 · 创建 · 基于《神经信号的化学渡口》一文 · 初始置信度：高

## 来源文章

- [[2026-05-25-synaptic-vesicle-exocytosis]]

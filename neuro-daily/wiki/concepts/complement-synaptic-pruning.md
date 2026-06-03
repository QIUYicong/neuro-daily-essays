---
title: 补体介导的突触修剪
slug: complement-synaptic-pruning
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-04
updated: 2026-07-04
revision_count: 1
dimensions: [molecular, synaptic, cellular, microcircuit, development, disease]
related: [microglia, synaptic-pruning, alzheimers-disease, hebbian-learning, ltp, homeostatic-plasticity, astrocyte]
prerequisites: [synaptic-transmission, ltp, microglia]
opens_questions: [Q-microglia-01, Q-microglia-02, Q-microglia-03]
source_articles: [2026-07-04-microglia-synaptic-pruning]
key_sources: ["PMID:18083105", "PMID:22632727", "PMID:27033548", "PMID:26814963", "PMCID:PMC5094372", "PMCID:PMC6252206"]
---

# 补体介导的突触修剪 (Complement-Mediated Synaptic Pruning)

> **一句话定义**：大脑发育期通过在弱活动突触上沉积补体蛋白（C1q→C3→iC3b），引导小胶质细胞经 CR3 受体定向吞噬这些突触，将过剩冗余的连接精修为功能精确的成熟回路；这一机制在阿尔茨海默病中被 Aβ 病理性重激活，导致成年大脑中突触的异常丢失。

## 当前理解

我们现在认为，补体介导的突触修剪是发育神经科学与免疫学的交叉发现，代表大脑借用古老的先天免疫工具箱来实现**活动依赖性神经回路雕刻**。

核心分子机制的四步级联：
1. **C1q 沉积**：发育期弱活动突触表面积累 C1q 蛋白（神经元和星形胶质细胞共同产生；TGF-β 上调神经元 C1q 表达）
2. **C3 激活**：C1q 触发经典补体级联，切割 C3 为 C3b/iC3b，后者共价沉积于突触膜
3. **CR3 识别**：小胶质细胞 CR3 受体（CD11b/CD18）专一识别 iC3b
4. **吞噬消化**：微胶质将突触末梢内化至吞噬溶酶体降解

这套机制的精妙在于将**电生理信号（活动强度）转换为分子标记（C1q/C3 密度）**：弱活动突触更可能积累补体标记，活跃突触通过维持糖基化保护位点等机制而免于标记。

C1q/C3 KO 小鼠（Stevens 2007, PMID:18083105）和 CR3 KO 小鼠（Schafer 2012, PMID:22632727）均在视网膜膝状体系统中显示出持续的突触精修缺陷，证明补体系统是发育期精修的**必要**（而非充分）机制。

## 关键机制

### 分子步骤（完整级联）

```
弱活动突触
    ↓ TGF-β 信号（星形胶质细胞→神经元）
    ↓ 神经元上调 C1q 表达
C1q 结合于突触膜
    ↓ 激活 C4、C2（经典途径）
C3 转化酶形成 → C3 切割 → C3b/iC3b 沉积
    ↓
小胶质细胞 CR3 识别 iC3b
    ↓
吞噬溶酶体降解突触末梢
```

### 活动依赖性选择逻辑

- **弱突触被优先标记**：神经活动减少 → 线粒体代谢变化 → C1q 结合位点暴露增加（机制尚不完全清楚）
- **活跃突触的保护机制**：细胞表面唾液酸化（sialylation）可阻断 C1q 与突触的结合；活跃突触可能维持更高水平的糖基化（PMC6252206）
- **磷脂酰丝氨酸（PS）通路**：PS 外翻作为独立的"eat-me"信号（Scott-Hewitt 2020, PMID:32657463），被 TREM2 识别；可能与补体通路协同

### 与赫布法则的互补关系

- 赫布法则（Hebbian learning）：强化一起活动的突触（"fire together, wire together"）
- 补体修剪：消除不活动/弱活动的突触（"stop firing, get pruned"）
- 两套机制共同实现"活动选择性的回路雕刻"：一套保留有价值的连接，一套清除冗余连接

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| C1q/C3 为发育精修必需分子 | C1qa/C3 KO 小鼠视网膜膝状体精修缺陷 | Stevens et al. 2007, PMID:18083105 | 高 |
| CR3/C3 通路介导活动依赖性精修 | 单眼 TTX + CR3 KO，活动偏向精修消失 | Schafer et al. 2012, PMID:22632727 | 高 |
| Aβ 通过 C1q 重激活发育修剪 | J20 小鼠 1 月龄 C1q 升高；抗 C1q 抗体保护突触和 LTP | Hong et al. 2016, PMID:27033548 | 高 |
| C4A 高拷贝 → 精神分裂症风险 → 推断过度修剪 | 大规模 GWAS + 突触 C4 定位 + 小鼠过度修剪 | Sekar et al. 2016, PMID:26814963 | 中（机制为推断）|
| 唾液酸化保护活跃突触免于 C1q 标记 | 去糖基化实验；糖蛋白分析 | PMC6252206 综述 | 中 |
| PS 外翻为独立 eat-me 信号 | PS 传感器；TREM2 实验 | Scott-Hewitt 2020, PMID:32657463 | 中 |

## AD 中的病理激活

Hong et al. 2016 揭示了关键的疾病机制：

- **时序**：J20 小鼠中 C1q 升高（1 月龄）→ 突触丢失（3-4 月龄）→ 淀粉样斑块（6-8 月龄）
- **触发因子**：可溶性 Aβ 寡聚体（oAβ）直接诱发成年健康大脑的 C1q/C3 激活
- **保护性干预**：C1qa KO 或抗 C1q 抗体均可防止 oAβ 诱导的突触丢失和 LTP 损伤
- **机制假说**：Aβ 将补体级联激活于成熟（正常活动）突触上，失去活动依赖选择性，造成无差别修剪

**关键不确定性**：AD 中的修剪是否完全失去选择性？还是仍有偏向（如 AD 相关的功能减弱突触）？目前缺乏直接证据。

## 连接

- [[microglia]] — 执行补体识别和吞噬的细胞
- [[synaptic-pruning]] — 更广义的突触消除过程（包含非补体机制）
- [[alzheimers-disease]] — 发育机制病理重激活的主要案例
- [[hebbian-learning]] — 互补机制：一个保留强连接，一个消除弱连接
- [[homeostatic-plasticity]] — 突触稳态缩放（功能调整）vs 补体修剪（结构删除）的关系

## 未解问题

- Q-microglia-01：活动水平如何在分子层面决定 C1q 是否沉积于一个特定突触？
- Q-microglia-02：发育修剪与 AD 病理修剪的分子差异是什么？
- Q-microglia-03：补体修剪（结构性消除）与突触稳态缩放（功能性调整）如何协调互动？

## 修订历史

- 2026-07-04 · 创建 · 基于《大脑的免疫剪刀》(#70) · 初始置信度：高（核心机制 established，部分细节 medium）

## 来源文章

- [[2026-07-04-microglia-synaptic-pruning]]

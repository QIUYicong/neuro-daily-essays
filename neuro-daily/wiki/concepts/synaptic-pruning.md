---
title: 突触修剪
slug: synaptic-pruning
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-24
updated: 2026-06-24
revision_count: 1
dimensions: [molecular, cellular, developmental]
related: [critical-period, perineuronal-nets, pv-interneurons, complement-cascade-synapse, ltp, ltd, hippocampal-circuit]
prerequisites: [synaptic-transmission, action-potential]
opens_questions: [Q-sp-01, Q-sp-02]
source_articles: [2026-06-24-synaptic-pruning-critical-period]
key_sources: ["PMID:18083105", "PMID:22632727", "PMID:32503914", "PMID:41169352"]
---

# 突触修剪 (Synaptic Pruning)

> **一句话定义**：发育过程中大脑主动消除多余突触的过程，由补体蛋白（C1q/C3）标记弱突触，小胶质细胞通过 CR3/C3 信号通路吞噬，活动强的突触获得竞争性保留。

## 当前理解

我们现在认为，突触修剪是大脑构建精确神经回路的核心发育机制。大脑在出生后经历"突触过剩期"（synaptic overproduction），随后通过修剪将初始的粗糙连接雕刻成功能精确的成熟网络。

修剪机制的核心发现来自两个突破性研究：Stevens et al. 2007（*Cell*, PMID:18083105）证明免疫补体蛋白 C1q 由神经元表达并标记突触；Schafer et al. 2012（*Neuron*, PMID:22632727, PMCID:PMC3528177）直接证明小胶质细胞是吞噬被标记突触的执行者。

修剪具有**活动依赖性**：活动强的突触获得竞争性保留，活动弱或缺失的突触优先被删除。这一机制在视网膜-侧膝状体系统中得到了最严格的实验验证。

## 关键机制

### 分子层面：补体标记

1. **C1q 定位**：出生后神经元表达并分泌 C1q，C1q 优先与活动弱的突触结合（具体识别机制尚不完全明确，可能涉及突触表面分子的差异表达）；
2. **补体级联激活**：C1q → 激活 C4 → 裂解 C3 → C3b（"调理素"）沉积于突触表面；
3. **"吃我"信号**：C3b 作为"吃我"信号，被小胶质细胞表面的补体受体 CR3（CD11b）识别。

**"别吃我"信号（拮抗机制）**：活动强的突触可能通过表达 CD47/SIRPα 信号轴来拮抗吞噬，但这一机制的相对重要性仍在研究中（Q-sp-01）。

### 细胞层面：小胶质细胞吞噬

小胶质细胞通过以下步骤完成突触吞噬：
- CR3 识别 C3b 标记的突触；
- 形成吞噬囊泡，将突触前成分完整包裹；
- 在溶酶体（CD68+）中消化突触物质；

关键定量数据（Schafer 2012, PMID:22632727）：
- CR3 KO 成年鼠：视网膜-膝状体突触密度增加约 **1.3倍**；
- RGC 末端密度增加约 **1.8倍**；
- P5 修剪峰期后（P9）吞噬显著减少，与修剪窗口关闭吻合。

### 发育层面：时间窗口与竞争

- 修剪发生在特定发育关键期内（受 GABA 抑制性回路成熟调控，见 [[critical-period]]）；
- 竞争机制：两个输入争夺同一突触后细胞时，活动弱者被清除；
- 视觉系统中：TTX 抑制一只眼的活动 → 该眼的输入被优先吞噬（Schafer 2012）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| C1q 由神经元表达并定位于发育中的突触 | 免疫组化，C1q KO 小鼠 | PMID:18083105（摘要） | 高 |
| C1q/C3 KO 小鼠视网膜-膝状体突触消除失败 | C1q/C3 敲除 + dLGN 连接精度分析 | PMID:18083105（摘要） | 高 |
| 小胶质细胞在溶酶体中吞噬 RGC 突触前成分 | 3D 共聚焦重建 + CD68 染色 + 电镜 | PMID:22632727, PMC:PMC3528177 | 高 |
| CR3/C3 信号通路介导小胶质细胞修剪 | CR3/C3 KO + 突触密度定量 | PMID:22632727, PMC:PMC3528177 | 高 |
| 修剪具有活动依赖性（弱输入优先被清除） | TTX/Forskolin 药理 + 眼特异荧光标记 | PMID:22632727, PMC:PMC3528177 | 高 |
| 精神分裂症患者前额叶突触密度减少与 C4A 遗传变异相关 | 死后病理 + GWAS | PMID:41169352, PMC:PMC12568506 | 中（相关性，非直接因果） |

## 连接

- [[critical-period]] — 修剪主要发生在发育关键期内；关键期的开启/关闭调控修剪的时间窗口
- [[perineuronal-nets]] — PNNs 形成标志关键期（及主要修剪窗口）关闭
- [[pv-interneurons]] — PV 细胞成熟开启关键期（间接影响修剪时机）
- [[ltp]] — 被保留的突触往往通过 LTP 强化
- [[ltd]] — 被修剪候选突触可能先经历 LTD 弱化
- [[hippocampal-circuit]] — 海马青春期突触修剪与记忆功能发展相关

## 未解问题

- Q-sp-01（高优先级）：C1q 为什么优先定位于弱突触？"别吃我"信号（CD47/SIRPα）的相对重要性是什么？
- Q-sp-02（中优先级）：神经元什么时候表达 C1q？哪些信号调控其分泌？是否存在突触特异性的标记调控？

## 修订历史

- 2026-06-24 · 创建 · 基于《用进废退的精密刻刀》一文 · 初始置信度：高

## 来源文章

- [[2026-06-24-synaptic-pruning-critical-period]]

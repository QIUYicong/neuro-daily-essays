---
title: 齿状回门控
slug: dentate-gyrus-gate
domain: concepts
type: mechanism
status: mainstream
confidence: medium
created: 2026-06-13
updated: 2026-06-13
revision_count: 1
dimensions: [cellular, synaptic, microcircuit, brain-region, cognition, disease]
related: [hippocampal-circuit, temporal-lobe-epilepsy, place-cell, pattern-separation, pv-interneurons, adult-neurogenesis, ei-balance]
prerequisites: [hippocampal-circuit, synaptic-transmission, action-potential]
opens_questions: [Q-tle-01]
source_articles: [2026-06-13-temporal-lobe-epilepsy-hippocampal-circuit]
key_sources: ["PMID:31232111", "PMCID:PMC6891841"]
---

# 齿状回门控 (Dentate Gate / Dentate Gyrus Gate Hypothesis)

> **一句话定义**：颗粒细胞（Granule Cells, GC）以极度超极化的静息电位（≈-80 mV）和强烈的放电频率适应，主动过滤从内嗅皮层（EC）进入 CA3 的信息流——仅允许最显著的输入通过，从而实现模式分离并防止病理性同步扩散；齿状回门控失效是颞叶癫痫（TLE）发生的关键环节。

## 当前理解

我们现在认为，齿状回门控（Dentate Gate）是海马实现**模式分离（Pattern Separation）**和抵御**癫痫扩散**的双重机制核心（Scharfman 2019, PMID:31232111）。

颗粒细胞是哺乳动物大脑中最安静的神经元之一：
- 静息膜电位约 -80 mV（比皮层锥体细胞负 10-15 mV）
- 强烈的放电频率适应（即使持续刺激，放电频率迅速下降至接近零）
- 稀疏激活：任意时刻仅约 2-5% 的颗粒细胞处于活跃状态

这种极端稀疏性有两个直接功能价值：

**① 模式分离**：不同但相似的输入（例如，今天的停车位 vs 昨天的停车位）由几乎不重叠的颗粒细胞集群激活表示 → 防止记忆混淆 → 输入 CA3 的表征是稀疏且正交的。

**② 癫痫防御**：内嗅皮层的大规模同步活动（如 TLE 中出现的痫样放电）无法轻易穿透颗粒细胞层进入 CA3，因为绝大多数颗粒细胞不响应 → 阻止了 CA3 循环兴奋回路的触发。

门控的维持依赖于多种机制协同：
- HIPP 细胞（生长抑素+门区抑制性中间神经元）提供强反馈抑制到颗粒细胞树突
- 苔状细胞（Mossy Cells）通过 HIPP 细胞的间接抑制调节颗粒细胞整体兴奋性
- 分子层前馈抑制（EC → 分子层 LPP → Basket Cells → 颗粒细胞）

**门控失效**：在 TLE 中，HIPP 细胞的选择性死亡 + 苔状纤维出芽（颗粒细胞间兴奋性侧枝）+ KCC2 下调（GABA 极性改变）叠加，使颗粒细胞从"静息保守"变为"容易被招募"，门控功能瓦解。

## 关键机制

- **高密度 HIPP 细胞抑制**：HIPP 细胞轴突延伸至齿状回外分子层，通过 GABA 持续压制颗粒细胞树突兴奋性
- **苔状细胞的双重调节**：苔状细胞既直接兴奋颗粒细胞，又通过 HIPP 细胞间接抑制——净效果通常偏向抑制
- **GABA-A δ 亚基介导的强直性抑制**：颗粒细胞表面高密度 δ 亚基 GABA-A 受体提供持续的突触外抑制（Tonic Inhibition），进一步压低颗粒细胞静息兴奋性
- **内在膜特性**：颗粒细胞的 A 型 K⁺ 通道、高 Kv4 密度等特性共同构成低兴奋性表型

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 颗粒细胞极度超极化且放电稀疏 | 在体膜片钳 + 单细胞记录；Vm ≈ -80 mV | Scharfman 2019 (PMC6891841) | 高 |
| 齿状回门控阻止癫痫扩散 | 颗粒细胞激活阈值上调 → 阻断 EC 到 CA3 的痫样扩散（脑片电生理）| Scharfman 2019 | 中（因果性主要来自动物实验） |
| 门控失效与苔状纤维出芽相关 | 出芽量化（Timm 染色）+ 颗粒细胞兴奋性测量；TLE 动物模型 | Scharfman 2019 | 中（因果关系仍有争议）|

## 连接

- [[hippocampal-circuit]] — 门控是海马 EC→DG→CA3→CA1 信息流的关键过滤步骤
- [[temporal-lobe-epilepsy]] — TLE 中门控失效是发作发生的核心环节
- [[place-cell]] — 门控维持的稀疏编码是海马认知地图精度的前提
- [[adult-neurogenesis]] — 新生颗粒细胞在整合期具有较低阈值和异常兴奋性，可能暂时削弱门控
- [[ei-balance]] — HIPP 细胞驱动的反馈抑制是 E/I 平衡在 DG 层面的核心执行机制

## 未解问题

- 与 Q-tle-01 相关：门控的精确分子底物（HIPP 细胞 vs δ-GABA-A vs 内在膜特性）在人类海马中的相对权重是什么？

## 修订历史

- 2026-06-13 · 创建 · 基于《失控的门卫：颞叶癫痫如何在五个层级揭示大脑的防御体系》(#188) · 初始置信度：中（机制在动物中确立，人类 TLE 中的具体权重有争议）

## 来源文章

- [[2026-06-13-temporal-lobe-epilepsy-hippocampal-circuit]]

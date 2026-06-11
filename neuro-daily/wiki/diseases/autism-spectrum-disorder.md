---
title: 自闭症谱系障碍
slug: autism-spectrum-disorder
domain: diseases
type: disease
status: mainstream
confidence: medium
created: 2026-08-07
updated: 2026-08-07
revision_count: 1
dimensions: [molecular, synaptic, microcircuit, brain-region, behavior, cognition, disease]
related: [synaptic-pruning, complement-cascade-cns, synaptogenesis, neuroligin-neurexin, ei-balance, gephyrin-scaffold, microglia]
prerequisites: [synaptic-pruning, synaptogenesis, neuroligin-neurexin]
opens_questions: [Q-asd-01, Q-asd-02]
source_articles: [2026-08-07-synaptic-pruning-complement-autism-schizophrenia]
key_sources: ["PMID:26814963", "PMID:30308165", "doi:10.1073/pnas.2411080122", "PMID:32661396"]
---

# 自闭症谱系障碍 (Autism Spectrum Disorder, ASD)

> **一句话定义**：自闭症谱系障碍是一类以社交沟通困难、重复行为和感觉异常为核心特征的神经发育障碍，其神经科学机制高度异质，当前较有证据支持的通路包括：突触修剪不足（CD47 缺陷模型）、突触装配蛋白突变（Neuroligin-Neurexin 轴）和 E/I 平衡偏移。

## 当前理解

我们现在认为，ASD 不是单一病因的疾病，而是一个**高度异质的神经发育谱系**，不同遗传背景的患者可能有截然不同的分子机制。然而，多个通路汇聚于一个共同的表型特征：神经回路精确性的受损——要么突触太多（修剪不足），要么突触质量异常（突触装配蛋白突变），要么 E/I 平衡偏向兴奋侧。

**突触修剪不足假说**（证据强度：中）：
与精神分裂症（过度修剪）形成镜像，部分 ASD 遗传亚型表现为突触密度过高。尸检研究显示，ASD 患者颞叶皮层突触密度高于正常发育个体，且与自噬（synapse-specific autophagy）受损相关（Bhatt 等研究）。2025 年 PNAS 研究发现，16p11.2 缺失（高外显率 ASD 遗传变异）小鼠的小胶质细胞 CD47 感知功能受损——小胶质细胞无法区分高 CD47（活跃）和低 CD47（沉默）突触，导致两类突触的吞噬都减弱，总体突触密度偏高，并出现 ASD 样社交行为缺陷（doi:10.1073/pnas.2411080122）。

**突触装配蛋白突变假说**（证据强度：中高）：
Neuroligin（NLGN3 R451C、NLGN4X）和 Shank（SHANK3、SHANK1、SHANK2）的基因突变在 ASD 中被多个独立研究验证。NLGN3 R451C 敲入小鼠出现抑制性突触功能增强和社交行为缺陷，但这一表型在不同遗传背景下重现性参差不齐。这说明突触装配蛋白的病理效应高度依赖背景遗传变量。

**E/I 失衡假说**（证据强度：中）：
E/I 平衡偏向兴奋（更多兴奋性突触 / 更少抑制性突触）被提出作为多种 ASD 遗传亚型的共同中间层机制。然而，ASD 患者的神经影像和神经生理数据并不一致支持单一方向的 E/I 失衡，这一假说仍处于 emerging 阶段。

## 关键机制（突触修剪不足通路，本文重点）

```
16p11.2 缺失 → CD47 表达或信号异常
         ↓
小胶质细胞 CD47-SIRPα 感知受损
         ↓
对活跃与沉默突触无法区分 → 两类吞噬均↓
         ↓
总体突触密度↑（无法执行正常精修）
         ↓
神经回路"过密"→ 信号噪音↑，处理特异性↓
         ↓
社交沟通、感知整合困难
```

与精神分裂症的对比：

| 维度 | 精神分裂症 | ASD（修剪不足型） |
|------|-----------|----------------|
| 修剪方向 | 过度 | 不足 |
| 主要病理分子 | C4A 过表达 → 过度 C3 标记 | CD47 感知障碍 → 吞噬减弱 |
| 发病时间窗 | 青春期（前额叶修剪峰） | 早期发育（出生后 2 年内）|
| 突触密度 | 偏低（尤其前额叶 L3）| 偏高 |
| 主要认知受损 | 工作记忆、认知控制 | 社交认知、感知整合 |

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| ASD 皮层突触密度高于对照 | 颞叶尸检突触密度计数 + 自噬标记 | 多项尸检研究（综述）| 中 |
| 16p11.2 缺失→CD47 感知障碍→修剪不足 | 16p11.2−/− 小鼠：小胶质吞噬↓，突触↑，ASD 样行为 | doi:10.1073/pnas.2411080122 | 中高 |
| NLGN3 R451C→ASD 样行为 | NLGN3 R451C 敲入鼠：抑制性突触增强，社交缺陷 | PMID:16369484（Tabuchi et al. 2007）| 中（重现性问题）|
| ASD 遗传风险基因富集突触蛋白 | GWAS + 罕见变异分析：Shank、NL、NRXN 突变汇聚 | 多个 GWAS | 高（遗传关联）；中（因果机制）|

## 连接

- [[synaptic-pruning]] — ASD 修剪不足型的上游机制
- [[synaptogenesis]] — 突触装配蛋白（NL/NRXN/Shank）变异是 ASD 另一主要机制
- [[neuroligin-neurexin]] — 核心 ASD 遗传靶点
- [[ei-balance]] — E/I 失衡作为多种 ASD 亚型的共同中间层
- [[microglia]] — 执行突触修剪（或无法正确执行）的细胞
- [[complement-cascade-cns]] — 与精神分裂症共享同一分子系统，但 ASD 是"功能过弱"端
- [[gephyrin-scaffold]] — 抑制性突触支架蛋白，部分 ASD 亚型抑制性突触异常

## 未解问题

- Q-asd-01（高优先）：ASD 中多种突变亚型（NLGN3、SHANK3、16p11.2 缺失等）的突触密度变化是否都朝同一方向（修剪不足），还是不同亚型有相反的方向性？这决定了是否存在统一的"ASD 突触表型"。
- Q-asd-02（中优先）：CD47 感知障碍模型是否适用于 16p11.2 缺失以外的 ASD 遗传亚型？若 CD47 通路是广泛的 ASD 机制，则抗 CD47 激动剂（恢复 SIRPα 信号）是否可作为 ASD 治疗靶点？

## 修订历史

- 2026-08-07 · 创建 · 基于《大脑的删除艺术》(#106) · 初始置信度：中（机制异质性大，现有直接因果证据多来自特定遗传亚型）

## 来源文章

- [[2026-08-07-synaptic-pruning-complement-autism-schizophrenia]]

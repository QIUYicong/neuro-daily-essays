---
title: 径向神经胶质细胞
slug: radial-glia
domain: neurons
type: structure
status: established
confidence: high
created: 2026-05-31
updated: 2026-05-31
revision_count: 1
dimensions: [molecular, cellular]
related: [cortical-neurogenesis, outer-radial-glia, pyramidal-neuron, hippocampal-circuit, action-potential]
prerequisites: [action-potential]
opens_questions: [Q-neuro-02]
source_articles: [2026-05-31-cortical-neurogenesis-radial-glia]
key_sources: ["PMID:17467805", "PMID:30186101", "PMID:33227588"]
---

# 径向神经胶质细胞 (Radial Glial Cells, RGCs)

> **一句话定义**：胚胎大脑皮层中的主要神经干细胞，同时作为新生神经元向皮层外侧迁移的物理轨道（脚手架）和产生这些神经元的祖细胞（建筑师）。

## 当前理解

我们现在认为，径向神经胶质细胞（RGCs）是大脑皮层发育的核心执行者，承担双重角色：一是提供贯穿皮层全厚的纤维骨架，引导新生神经元径向迁移；二是作为具有自我更新能力的神经干细胞，通过对称和不对称分裂产生全部兴奋性皮层投射神经元（以及后期的星形胶质细胞和少突胶质细胞）。

RGCs 的细胞体贴附于脑室腔（顶端/apical），同时延伸一条极长的基底突起（basal process）至软膜表面，这根突起是新生神经元沿径向轴向外迁移的轨道。RGCs 具有严格的细胞周期伴随的核运动（IKNM），在有丝分裂期分裂发生在顶端（脑室面）。

每个 RGC 谱系平均产生约 8–9 个神经元（高斯分布），表明存在内在控制的增殖时钟（Lin 2020）。这一过程高度有序：RGC 先经过若干次对称扩增分裂，再进入非对称分裂产生神经元阶段，最后转为产生胶质细胞。

## 关键机制

**IKNM（核间运动）**
- G1：细胞核向基底侧运动
- S：DNA 在近基底侧完成复制
- G2：细胞核快速回到顶端
- M：分裂严格发生在脑室面（apical）
- 分子马达：动力蛋白（G2→顶端）+ 驱动蛋白（G1→基底侧）

**分裂方式**
- 对称增殖（symmetric proliferative）：两个 RGC 子代，扩大祖细胞池
- 不对称（asymmetric）：一个 RGC + 一个有丝分裂后神经元（直接神经发生）
- 不对称（asymmetric）：一个 RGC + 一个中间祖细胞 IP（间接神经发生，IP 再对称分裂产 2 个神经元）

**Pax6→Tbr2→Tbr1 命运级联**
RGC（Pax6+）产生的子代通过这一转录因子序列逐步特化（详见 [[cortical-neurogenesis]]）

**神经发生-胶质发生切换**
皮层神经元产生完毕后，Gli3 和 Pax6 对 Olig2 的抑制被 Shh 信号解除，RGC 转为产生胶质细胞（Li 2024, PMC11098099）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| RGC 是皮层兴奋性神经元的主要祖先 | 逆转录病毒谱系追踪（猕猴/小鼠） | PMID:17467805 | 高 |
| IKNM 分裂发生在顶端 | 活体成像 + 固定标本 | 多个独立研究 | 高 |
| 每 RGC 谱系约产生 8–9 个神经元 | 克隆分析（小鼠） | PMID:33227588 | 中 |
| Pax6→Tbr2→Tbr1 驱动表观遗传重编程 | RNA-seq + ChIP-seq 小鼠皮层 | PMID:30186101 | 高 |
| Shh 触发神经-胶质开关 | 条件性敲除 + 增益功能小鼠 | PMID:38713624 | 高（小鼠），中（人类） |

## 连接

- [[cortical-neurogenesis]] — RGC 是皮层神经发生的执行者
- [[outer-radial-glia]] — oRG 是从 RGC 脱离顶端附着后的特化子类型
- [[pyramidal-neuron]] — RGC 的主要产物之一（皮层兴奋性锥体神经元）

## 未解问题

- Q-neuro-02：IKNM 是否有主动信号感受功能（顶端 Notch 配体传感）？

## 修订历史

- 2026-05-31 · 创建 · 基于《诞生的顺序就是命运》（第 37 篇） · 初始置信度：高

## 来源文章

- [[2026-05-31-cortical-neurogenesis-radial-glia]]

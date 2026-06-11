---
title: 嗅小球
slug: olfactory-glomerulus
domain: concepts
type: structure
status: established
confidence: high
created: 2026-07-17
updated: 2026-07-17
revision_count: 1
dimensions: [cellular, synaptic, microcircuit]
related: [olfactory-system, olfactory-receptor-neuron, pv-interneurons, lateral-inhibition]
prerequisites: [olfactory-receptor-neuron, synaptic-transmission]
opens_questions: [Q-olfact-02]
source_articles: [2026-07-17-olfactory-system-molecular-to-memory]
key_sources: ["PMID:19804753", "PMID:32982699", "PMID:16841172"]
---

# 嗅小球 (Olfactory Glomerulus)

> **一句话定义**：嗅球皮层表面的球状神经毡结构（直径约 50-100 μm），接收表达同一 OR 类型的所有 ORN 轴突输入（~5000 ORN/嗅小球，小鼠），与僧帽/簇状细胞顶突树突在此形成突触，构成嗅球表面精确的"OR 功能地图"。

## 当前理解

嗅小球是嗅觉系统中将分子化学识别信息转化为神经回路拓扑信息的核心界面。其关键功能有两个：
1. **汇聚放大**：将来自数千个稀疏分布的同类 OR ORN 的信号整合，放大弱信号（信号-噪声增强装置，Chen 2005）
2. **拓扑编码**：嗅小球在嗅球表面的位置对应特定 OR 类型，构成功能性"气味地图"（在不同个体间高度保守）

## 解剖与微回路

**结构**：嗅小球是球形神经毡区，位于嗅球最浅层（嗅小球层）；每个嗅小球直径约 50-100 μm，主要由：
- ORN 轴突末梢（谷氨酸能输入）
- 僧帽细胞（Mitral Cell）和簇状细胞（Tufted Cell）的顶突树突（接受输入）
- 嗅小球周围中间神经元（PG 细胞、外簇状细胞等）

**汇聚数量**（Su et al. 2009）：
- 小鼠：约 5000 ORN / 嗅小球（每种 OR 类型约 1-2 个嗅小球/嗅球，共约 2000 个嗅小球/嗅球）
- 果蝇：约 50 ORN / 嗅小球

**嗅小球内回路**：
- ORN 轴突 → 外簇状细胞（ET cells，直接兴奋性）+ 僧帽/簇状细胞顶突树突
- ET 细胞产生 theta 节律性 burst（1-10 Hz），可能同步嗅小球活动
- 嗅小球周围 GABAergic 中间神经元（PG 细胞等）提供嗅小球内和嗅小球间前突触抑制

**僧帽与簇状细胞的差异**（Imamura et al. 2020）：
- 僧帽细胞：持续放电；顶突树突深入嗅小球；对较高浓度气味反应；投射至前/后梨状皮层、杏仁核、内嗅皮层
- 簇状细胞：与吸气相锁定；对约低 10 倍气味浓度敏感；仅投射前外侧区域（不投射梨状皮层）
- 梨状皮层只接受**僧帽细胞**轴突（功能分流）

**颗粒细胞侧抑制**（嗅小球间）：
- 颗粒细胞（Granule Cells）通过往返树突-树突突触（dendrodendritic reciprocal synapse）与多个嗅小球的僧帽细胞形成连接
- 强激活 → 颗粒细胞兴奋 → GABA 抑制邻近僧帽细胞（侧抑制，lateral inhibition）
- 功能：对比增强、增益控制、气味判别

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 同类 OR 的 ORN 轴突汇聚到固定嗅小球 | 基因示踪（OR-Cre × reporter小鼠） | PMID:19804753 | 高 |
| ~5000 ORN/嗅小球（小鼠） | 电子显微镜 + 基因标记 | PMID:19804753 | 高 |
| 嗅小球位置跨个体保守 | 功能成像 + 解剖对比 | PMID:19804753 | 高 |
| 嗅小球是信号-噪声增强装置 | 电生理 + 计算模型 | PMID:16841172 | 中-高 |
| 梨状皮层只接受僧帽细胞轴突 | 追踪研究 | PMID:32982699 | 高 |
| 颗粒细胞侧抑制增强气味判别 | 电生理+光遗传 | PMID:19804753 综述 | 中-高 |

## 连接

- [[olfactory-system]] — 嗅小球是嗅球功能单元
- [[olfactory-receptor-neuron]] — ORN 轴突汇聚至嗅小球
- [[pv-interneurons]] — 嗅球中也有 PV 中间神经元参与抑制

## 未解问题

- **Q-olfact-02**（中优先级）：嗅球层面的"粗糙化学拓扑"（类似气味分子在相邻嗅小球）在梨状皮层是否进一步映射为语义/情感拓扑？

## 修订历史

- 2026-07-17 · 创建 · 基于文章 #85 · 初始置信度：高

## 来源文章

- [[2026-07-17-olfactory-system-molecular-to-memory]]

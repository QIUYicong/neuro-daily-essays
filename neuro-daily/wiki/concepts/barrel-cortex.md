---
title: 桶状皮层
slug: barrel-cortex
domain: concepts
type: structure
status: established
confidence: high
created: 2026-07-19
updated: 2026-07-23
revision_count: 2
dimensions: [cellular, microcircuit, brain-region]
related: [somatosensory-cortex, cortical-homunculus, critical-period, thalamus, pv-interneurons, orientation-selectivity]
prerequisites: [somatosensory-cortex, thalamus]
opens_questions: [Q-som-02]
source_articles: [2026-07-19-somatosensory-cortex-homunculus-barrel-cortex, 2026-07-23-neocortical-layers-columns-canonical-circuit]
key_sources: ["PMID:31367018", "PMID:17622195", "PMCID:PMC7486654", "PMCID:PMC3394394"]
---

# 桶状皮层（Barrel Cortex）

> **一句话定义**：啮齿类初级体感皮层（S1）第 4 层中由细胞密集壁围成的圆柱形聚集体，一个桶对应一根胡须，是皮层拓扑映射精确性和皮层柱（cortical column）结构-功能关系的经典研究模型。

## 当前理解

我们现在认为，桶状皮层是自然界演化出的"天然标记"组织：每根胡须的机械感觉信号沿着胡须毛囊→三叉神经节→脑干（barrelette）→丘脑 VPM（barreloid）→皮层（barrel）四站精确传递，从胡须偏转到皮层去极化仅约 **5 ms**。

每个桶对应一个垂直穿越皮层六层的**皮层柱（barrel column）**（高度约 1.2 mm，横截面约 200–300 μm，约 6500 个神经元，85% 兴奋性）。L4 接收丘脑直接输入，L2/3 是皮层内整合与跨柱传播的关键节点，L5 输出到皮下结构，L6 反馈到丘脑。

桶状皮层展示了所有感觉皮层的几个通用原则：**稀疏编码**（<10% 神经元响应主胡须刺激）、**局部异质性**（相邻 50 μm 内神经元感受野可截然不同）和**主动感知**（颤动相位锁定实现物体定位）。

## 关键机制

### 四站精确中继
```
胡须毛囊机械感受器
  → 三叉神经节（第一级神经元）
  → 脑干三叉主核（PrV，barrelette 组织）
  → 丘脑腹后内侧核（VPM，barreloid 组织）
  → S1 第 4 层（barrel）
```

### 皮层柱内规则回路（定量细节见 Feldmeyer 2012）
L4（棘星形细胞，接收 VPM 输入；但 VPM 仅提供 L4 突触的 10–20%，其余来自 L4 内部循环兴奋）
→ L2/3（单向，EPSP 0.6–1.0 mV，连接率 10–15%；锥体细胞，侧向传播，投射到 S2/M1）
→ L5（需多单元时间汇聚，EPSP ~0.1 mV，短时易化；PT 神经元，输出到皮下结构）
→ L6（反馈到 VPM/VPL）

L5B 厚簇型锥体细胞（PT 型）顶端树突延伸至 L1，接收高级皮层反馈预测信号；胞体整合 L2/3 前馈输入，两者符合时发生 BAC 爆发放电。

### 稀疏编码机制
PV+ 篮状细胞对主胡须刺激产生快速前馈抑制，将响应时间窗口压缩至约 10–20 ms，使多数神经元在单个刺激试次中不放电（响应概率 ~0.32）。

### 发育关键期（P0–P4）
- 丘脑皮层轴突（TCA）在出生时入侵皮层，P4 前完成胡须特异性分离
- 关键期关闭由皮下机制（脑干/丘脑）控制，而非皮层本身
- MAOA KO（5-HT 积累）→ TCA 无法形成胡须特异性图案 → 桶缺失
- AC1 KO → cAMP 信号缺陷 → 皮层无桶（皮层内在缺陷）
- P4 前破坏胡须毛囊 → 对应桶缺失，邻近桶扩大填充

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 一胡须对应一桶（严格拓扑）| Woolsey & Van der Loos 1970 Nissl 染色切向切片 | 历史发现 | 高 |
| 桶柱高度约 1.2 mm，横截面 200–300 μm，约 6500 神经元 | 组织解剖 + 体内成像 | PMID:31367018 | 高 |
| 稀疏编码：响应概率 ~0.32，相邻 50 μm 神经元异质性 | 双光子钙成像（体内单神经元） | PMID:17622195 | 高 |
| 关键期 P4 前，由皮下机制控制 | MAOA KO / AC1 KO / 胡须焦灼实验 | PMC7486654 | 高 |
| 10 Hz 颤动相位锁定实现物体定位 | 体内多单元电生理 | PMID:31367018 | 高 |

## 连接

- [[somatosensory-cortex]] — 桶状皮层是 S1 的组成部分（S1bfd，桶状皮层域）
- [[cortical-homunculus]] — 桶的大小按胡须受体密度分配，是小人原则在啮齿类的实例
- [[critical-period]] — 桶的发育关键期（P0–P4）是视觉皮层关键期（猫 P20–P30）的快速版
- [[pv-interneurons]] — PV+ 中间神经元提供快速前馈抑制，是稀疏编码的回路实现
- [[orientation-selectivity]] — V1 方向柱 vs 桶状皮层桶列：两种皮层功能图谱组织的比较
- [[tonotopy]] — 音调拓扑 vs 胡须拓扑：不同感觉系统中"感觉参数→皮层空间维度"的平行实例
- [[neocortical-layers]] — 桶柱是六层结构 L4→L2/3→L5 规范回路的最精确研究实例
- [[layer-5-pyramidal-cell]] — 桶柱 L5B 厚簇型锥体细胞是 BAC 放电机制的主要研究对象

## 未解问题

- Q-som-02：桶内局部异质性神经元（复杂感受野）在自然纹理辨别任务中是否有功能特异性（cf. Q-aud-02 听觉皮层中的同类问题）

## 修订历史

- 2026-07-19 · 创建 · 基于《从皮肤到大脑的身体地图》(#87) · 初始置信度：高
- 2026-07-23 · rev2 · 基于《新皮质六层算法》(#91) · 补充 L4→L2/3→L5 的定量突触数据（Feldmeyer 2012），明确 VPM 仅提供 L4 突触 10–20% 和 L5B PT 细胞 BAC 放电机制；新增 [[layer-5-pyramidal-cell]] 连接

## 来源文章

- [[2026-07-19-somatosensory-cortex-homunculus-barrel-cortex]]

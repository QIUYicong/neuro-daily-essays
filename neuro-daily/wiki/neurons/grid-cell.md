---
title: 网格细胞
slug: grid-cell
domain: neurons
type: entity
status: established
confidence: high
created: 2026-05-28
updated: 2026-07-27
revision_count: 2
dimensions: [brain-region, cellular, behavior, cognition]
related: [place-cell, hippocampal-circuit, path-integration, theta-oscillations, head-direction-cells, border-cells, entorhinal-cortex]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: [Q-grid-pattern-generation, Q-grid-abstract-space, Q-grid-place-conversion, Q-grid-human-single-unit]
source_articles: [2026-05-28-place-cells-btsp, 2026-07-27-grid-cells-head-direction-spatial-coordinate-system]
key_sources: ["PMID:15965463", "PMID:27023731", "PMID:34254836", "PMID:18284371", "PMID:20090680", "PMID:29073650", "PMID:38231426"]
---

# 网格细胞 (Grid Cell)

> **一句话定义**：内侧内嗅皮层（MEC）中的神经元，其激活位置在环境中构成等边三角形六角网格，为海马场所细胞提供空间坐标框架，并具有路径整合能力（在地标消失后仍能维持放电）。

## 当前理解

我们现在认为，网格细胞是大脑内部坐标系的核心组件。它们不像场所细胞那样只对单一地点响应，而是对**多个均匀分布的地点**（形成规则六角网格）同时响应。不同网格细胞的网格间距（spacing）和朝向（orientation）在同一 MEC 模块内是共享的，但网格顶点位置（phase）不同——这使不同相位的网格细胞组合可以唯一标识任意空间位置。

从 MEC 背侧到腹侧，网格间距逐渐增大（约 25 cm → >1 m），形成一套多分辨率的空间刻度系统，类似地图上的不同比例尺。

网格细胞的发现（Hafting et al., 2005, PMID:15965463）与奥基夫的场所细胞共同获得 2014 年诺贝尔生理学或医学奖，被称为"大脑 GPS 系统的分子基础"。

## 关键机制

### 1. 放电特征

- **六角网格**：等边三角形格子，每个顶点都是激活热点（firing field）
- **网格间距**：单个细胞的相邻激活区域间距固定（约 25–180 cm，背侧→腹侧梯度）
- **网格朝向**：网格轴线相对于环境的方向；同一模块内的细胞共享朝向
- **网格相位**：网格顶点在空间中的绝对位置；同一模块内各细胞相位随机分布
- **速度依赖**：放电频率与运动速度相关（对路径积分至关重要）

### 2. 路径整合（Path Integration）

关键实验：即使移除所有视觉、嗅觉地标，网格细胞仍能维持放电模式（在黑暗条件下或覆盖所有外部线索后）。这表明网格细胞依赖**内源性运动积分信号**（速度+方向）来更新自己的网格位置，而不依赖外部地标的持续输入。

运动信号来源：MEC 接收来自前庭系统、视流、本体感觉的输入，以及海马和基底神经节的反馈。

### 3. 从网格细胞到场所细胞

**转换机制**：一个假说认为，CA1 场所细胞的场所场对应于多个不同间距、不同相位的网格细胞输入的**叠加热点**——当动物位于某处时，该位置恰好在多个网格细胞的六角顶点交汇，使它们共同激活对应的 CA1 细胞，通过 BTSP 写入场所场。

**量化**：单个场所场可能由来自背侧 MEC 的 6–12 个不同相位网格细胞的组合输入叠加而成（计算模型预测；实验验证仍在进行中）。

### 4. 网格图案的生成机制（争议中）

**振荡干涉模型（Oscillatory Interference）**：
- 不同频率的内部振荡在树突中相互干涉，产生空间周期性放电
- 预测：去除 θ 振荡应消除网格性 → 实验结果不一致

**连续吸引子网络模型（Continuous Attractor Network）**：
- MEC 神经元间的抑制性连接自组织成环形吸引子
- 当前主流模型；MEC 内在微回路具有支持此机制的解剖结构（Tukker et al., 2022, PMID:34254836）

两种模型可能各有贡献，并非互斥。

### 5. 模块结构与多尺度精度

网格细胞在 MEC 中分组成**模块（modules）**：同一模块内的所有细胞共享相同的间距（spacing）和朝向（orientation），但相位（phase，即网格顶点的空间位置）各不相同。不同模块的间距不同，且相邻模块间的间距比约为 **1.4:1**。

这个特定比值的意义：利用**残差数系统（residue number system）**原理，少量几个不同间距的模块叠加，可以以厘米级精度区分数平方公里范围内的任意位置。例如，8–10 个模块的网格组合，理论上能以几厘米分辨率覆盖 40 × 40 km 的空间。

### 6. 头向细胞接口（2026-07-27 新增）

网格细胞的路径积分需要角度方向信息。MEC 中的**联合细胞（conjunctive cells）**同时对网格位置和头部方向敏感——它们是网格细胞系统与头向系统的整合节点。**头向细胞**（见 wiki/neurons/head-direction-cells.md）为网格的"活跃泡"更新提供角度坐标。

### 7. 网格细胞的非空间应用

近年发现，类似网格样放电（grid-like responses）也出现在：
- 非空间导航任务（概念空间中导航）
- 前额叶和眶额皮层（抽象"价值空间"中的网格状编码）
- 情景记忆中的时间维度编码

Behrens et al.（2018, Neuron 100:490–509）综述提出：认知地图可能编码任何结构化知识，而网格样机制是其通用计算基础。但 fMRI 方法的局限性使这一结论尚需单神经元级别的直接验证。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| MEC 神经元有六角网格放电 | 大鼠 MEC 四极管胞外记录，自由探索圆形环境 | PMID:15965463 | 高 |
| 网格放电在地标消失后仍维持（路径积分） | 黑暗或覆盖地标后的记录 | PMID:15965463 | 高 |
| 背侧→腹侧网格间距梯度（约 25cm→>1m） | 沿 MEC 背腹轴系统记录 | PMID:27023731 综述 | 高 |
| 人类内嗅皮层 fMRI 六边形信号（60° 调制） | 42名参与者虚拟现实导航 + fMRI | PMID:20090680 (PMC3173857) | 中-高（fMRI间接证据） |
| 网格信号强度与空间记忆成绩正相关 | Spearman's rho=0.32, p=0.039 | PMID:20090680 | 中 |
| 网格模式在不规则环境中扭曲变形 | 方形、圆形、L形环境对比记录 | PMID:38231426（综述引用） | 高 |

## 连接

- [[place-cell]] — 网格细胞通过穿孔通路提供场所细胞的空间坐标输入
- [[hippocampal-circuit]] — 网格细胞（MEC）通过穿孔通路输入到 DG、CA3、CA1
- [[path-integration]] — 网格细胞实现路径积分（无外部地标的空间位置追踪）
- [[theta-oscillations]] — θ 振荡可能参与网格图案生成（振荡干涉模型）
- [[head-direction-cells]] — 头向细胞为网格路径积分提供角度坐标；联合细胞整合两类信号
- [[border-cells]] — 边界细胞为网格坐标系提供空间锚点，防止路径积分误差累积
- [[entorhinal-cortex]] — MEC 是网格细胞的解剖位置，层 II 含网格细胞，层 III/V 含联合细胞

## 未解问题

- Q-grid-pattern-generation：网格六角图案的生成机制：振荡干涉 vs. 连续吸引子，哪个更接近真实？两者是否在不同条件下各有贡献？
- Q-grid-abstract-space：网格细胞是否真的是通用"内部坐标系"，用于抽象概念空间、时间等非物理空间？fMRI 六边形信号是否真的来自网格细胞而非混淆因素？
- Q-grid-place-conversion：从网格细胞的六角码到场所细胞的点状码的转换，具体通过哪些突触机制实现？叠加热点假说是否完整？
- Q-grid-human-single-unit（新增）：人类内嗅皮层单神经元级别的网格证据（Jacobs 2013 是开始，但样本量小）是否能被大样本颅内记录研究所扩展和证实？

## 修订历史

- 2026-05-28 · 创建 · 基于《场所细胞》文章 · 填补网格细胞知识 · 初始置信度：高
- 2026-07-27 · 修订 · 基于《大脑内置的坐标系》文章 #95 · 新增：人类 fMRI 六边形信号（Doeller 2010）、模块结构与 1.4:1 间距比、头向细胞接口（第6节）、Behrens 2018 非空间应用综述、Jeffery 2024 网格扭曲证据；更新关键证据表和连接；添加 Q-grid-human-single-unit

## 来源文章

- [[2026-05-28-place-cells-btsp]]
- [[2026-07-27-grid-cells-head-direction-spatial-coordinate-system]]

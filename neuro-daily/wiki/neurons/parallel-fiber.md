---
title: 平行纤维
slug: parallel-fiber
domain: neurons
type: structure
status: established
confidence: high
created: 2026-10-19
updated: 2026-10-19
revision_count: 1
dimensions: [cellular, microcircuit, systems]
related: [granule-cell-cerebellar, purkinje-cell, climbing-fiber, cerebellar-ltd, molecular-layer-interneuron, mossy-fiber, cerebellum]
prerequisites: [granule-cell-cerebellar, synaptic-transmission, action-potential]
opens_questions: [Q-pf-01, Q-pf-02]
source_articles: [2026-10-19-parallel-fiber-cerebellar-cortex-computation]
key_sources: ["PMID:37671785", "PMID:17046686", "PMID:15541316", "PMID:30284678", "PMID:32866603"]
---

# 平行纤维 (Parallel Fiber, PF)

> **一句话定义**：小脑颗粒细胞轴突在分子层中T形分叉形成的水平纤维束，长约1.5–3 mm/侧，沿与浦肯野细胞树突扇面垂直的方向延伸，每个浦肯野细胞接受超过100,000条平行纤维输入；平行纤维是Marr-Albus-Ito监督学习模型的情景载体，其与浦肯野细胞突触的双向可塑性（PF-LTD/LTP，由攀爬纤维Ca²⁺信号决定方向）是已知最清晰的神经元层面监督学习回路。

## 当前理解

平行纤维（PF）是小脑皮层计算架构的核心元件——颗粒细胞（GC）将苔藓纤维输入展开为高维稀疏表征后，由PF将这些编码传递给浦肯野细胞（PC）。在Marr-Albus-Ito模型中，PF承担"情景信号"（context signal）的角色：任何运动序列的感觉运动状态都在PF活动模式中编码，当攀爬纤维（CF）携带运动误差时，对应PF-PC突触发生LTD，下调该情景-运动输出的关联权重。

**几何的奇特性**：PF以T字形横跨整个分子层，方向与PC树突扇面正交——一条PF可逐个接触数百个PC的树突，而每个PC接受来自不同GC的超过100,000条PF输入。这种"一对多"和"多对一"的交叉拓扑，赋予小脑皮层强大的联想学习容量。

**稀疏 vs 任务依赖编码（2023年更新）**：经典Marr理论认为GC必须极度稀疏激活（正交性最大化），但Xie等人（2023，PMID:37671785）的计算分析表明：
- 对随机刺激分类任务：稀疏编码确实最优
- 对连续感觉运动变换（更接近真实小脑功能）：较密集的任务依赖编码才是最优
- 体内GC记录有时观察到高于稀疏预期的激活密度，与理论一致

这一发现将"稀疏编码"从普遍原则降格为特定任务的最优解。

## 关键机制

### 解剖结构

| 参数 | 数值 | 来源 |
|------|------|------|
| 每PC接受PF输入数 | >100,000条 | PMID:30284678 |
| 每PC接受CF输入数 | 1条（成体）| PMID:30284678 |
| CF在PC树突的突触数 | 300–500个（近端树突）| PMID:30284678 |
| PF单侧长度 | 1.5–3 mm（总长3–6 mm）| 教科书级解剖学 |
| PF延伸方向 | 与PC树突扇面正交 | 教科书级 |
| 人脑GC总数 | ~690亿 | PMID:37141091 |
| GC: PC 比值 | 约3000:1（人脑）| 推算 |

### PF-PC双向可塑性（Ca²⁺阈值开关机制）

攀爬纤维是PF-PC突触可塑性方向的"极性开关"（Coesmans et al. 2004，PMID:15541316）：

| CF状态 | 突触后Ca²⁺ | 触发机制 | 可塑性结果 |
|--------|-----------|---------|----------|
| PF + CF（同时激活）| 高（CF诱发复杂放电 + VDCC大开）| PKC激活 → AMPAR Ser880磷酸化 → 受体内吞 | **PF-LTD**（突触抑压）|
| PF alone（无CF）| 低 | PP2B（钙调神经磷酸酶）激活 → AMPAR去磷酸化 → 受体重新插入膜 | **PF-LTP**（突触增强）|

- PF-LTP是PF-LTD的精确逆转机制，由PP2B/calcineurin介导（Jörntell & Hansel 2006，PMID:17046686）
- 这一机制与海马BCM规则"倒置"：海马中高频激活→LTP；小脑PF中CF配对→LTD（而非LTP）
- 双向可塑性为运动学习的修正与逆转（去适应，de-adaptation）提供分子基础

### 苔藓纤维→GC→PF扩展重编码

颗粒细胞通过PF实现的"扩维重编码"（expansion recoding）赋予小脑强大的分类能力：
1. **输入维度**：约7,000条苔藓纤维（来自脊髓、前庭核、脑桥核等）
2. **中间维度**：约690亿GC（人脑），产生等量PF
3. **功能效果**：将低维感觉运动状态映射到极高维稀疏空间 → PC可用简单线性阈值区分复杂情景（Cover定理的神经实现）

### 波束假说 vs 微区块假说

| 模型 | 预测 | 状态 |
|------|------|------|
| 波束假说（beam hypothesis）| PF激活产生沿PF方向延伸的PC激活"波束"（横贯多叶） | 实验证据不支持：体内PC响应呈局部斑块状，非长程波束 |
| 微区块假说（patch/beam）| 皮层功能组织为纵向微区（与CF输入匹配），PF的横向激活被MLI侧抑制限制为局部斑块 | 与多数体内钙成像数据更符合 |

此争议至今未完全解决，但微区块视角与最新功能解剖数据更为兼容。

### Lisberger 2021四条学习原则

Lisberger（2021，PMID:32866603）总结小脑学习的四条基本规则（均涉及PF）：
1. CF信号驱动PF-PC突触的快速学习（PC暂时静默化）
2. 学习输出从皮层（PF-PC LTD）转移到小脑核（两级存储），类比海马→皮层巩固
3. 皮质回路反馈限制皮层学习幅度（防止过度拟合）
4. 不同小脑功能微区使用不同的PF可塑性规则（区域异质性，见Suvrathan & Raymond 2018，PMID:30069835）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| PC接受>100,000条PF输入，1条CF输入 | 电子显微镜计数+解剖学 | PMID:30284678 | 高 |
| PF+CF → LTD；PF alone → LTP（Ca²⁺阈值开关）| 光刺激控制CF + 脑片膜片钳 | PMID:15541316 | 高 |
| PF-LTP由PP2B/calcineurin介导，逆转PF-LTD | 脑片电生理 + 药理阻断 | PMID:17046686 | 高 |
| 对连续感觉运动变换，密集GC编码更优（非稀疏）| 计算优化分析 | PMID:37671785 | 中（理论，体内验证不足）|
| 小脑学习可从皮层转移至核（两级存储）| 电生理+行为 | PMID:32866603 | 中-高 |
| PF-LTD规则在不同小脑微区存在异质性 | 光遗传+跨区电生理 | PMID:30069835 | 中-高 |
| 至少9种小脑皮层突触可塑性（超越PF-LTD）| 综述 | PMID:24916288 | 高（综述共识）|

## 连接

- [[granule-cell-cerebellar]] — GC是PF的细胞来源；GC→PF是扩维重编码的输出步骤
- [[purkinje-cell]] — PF-PC突触是PF的主要功能靶点；PC整合>100,000条PF输入
- [[climbing-fiber]] — CF是PF-PC突触可塑性方向的决定因素（Ca²⁺极性开关）
- [[cerebellar-ltd]] — PF-PC LTD是PF参与小脑学习的核心分子机制
- [[molecular-layer-interneuron]] — MLI接受PF输入，产生与PC方向相反的逆向可塑性，放大CF误差信号
- [[mossy-fiber]] — MF是GC的主要输入，经GC→PF转化为高维编码
- [[cerebellum]] — PF是小脑皮层计算架构的核心元件

## 未解问题

- **Q-pf-01**（高优先级）：PF-LTD对运动学习是必要且充分的吗？已有多项研究用基因方法阻断PF-LTD却不损害小脑依赖性学习——这是因为LTP/MLI逆向可塑性提供了代偿通道，还是运动学习根本上不依赖PF-LTD？（关联Q-mli-01、Q-mli-02、Q-mli-03）
- **Q-pf-02**（中优先级）：在真实运动任务中，体内GC激活密度究竟是多少？Xie 2023的理论预测能否被宽视野双光子或光场显微镜在小脑颗粒层的大规模钙成像直接验证？

## 修订历史

- 2026-10-19 · 创建 · 基于《平行纤维：小脑皮层最细的导线，如何传递误差学习的语言》（文章 #179）· 来源：PMID:37671785/17046686/15541316/30284678/32866603/30069835/24916288/32599123 · 初始置信度：高（解剖和LTD/LTP机制有扎实直接证据；稀疏编码争议和波束假说有高质量挑战数据）

## 来源文章

- [[2026-10-19-parallel-fiber-cerebellar-cortex-computation]]

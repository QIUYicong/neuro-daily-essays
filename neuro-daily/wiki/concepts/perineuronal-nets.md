---
title: 围神经元网
slug: perineuronal-nets
domain: concepts
type: structure
status: established
confidence: high
created: 2026-07-04
updated: 2026-09-08
revision_count: 3
dimensions: [molecular, cellular, microcircuit, cognition, disease]
related: [pv-interneurons, ei-balance, synaptic-pruning, adult-neurogenesis, bdnf, homeostatic-plasticity, critical-period, microglia, critical-period-reopening, lynx1]
prerequisites: [pv-interneurons, synaptic-transmission]
opens_questions: [Q-ei-balance-02, Q-pnn-human-therapy, Q-cp-04]
source_articles: [2026-07-04-ei-balance-pv-interneuron, 2026-06-03-critical-period-plasticity, 2026-09-08-critical-period-reopening]
key_sources: ["PMID:37143468", "PMID:16243601", "PMID:24309249", "PMID:36598942", "PMID:12424383", "PMID:22764251", "PMID:33293360", "PMID:34045309"]
---

# 围神经元网 (Perineuronal Nets, PNNs)

> **一句话定义**：致密包裹 PV+ 快放电中间神经元胞体和近端树突的细胞外基质（ECM）网络，由 aggrecan 核心蛋白多糖、透明质酸骨架和连接蛋白组成；通过固定 AMPA 受体、捕获 OTX2 信号蛋白和提供物理保护，在发育关键期末将皮层回路状态"固化"，关闭大规模突触重塑窗口。

## 当前理解

我们现在认为，围神经元网不是静态的"胶水"，而是**主动维持回路稳定性的可逆分子刹车**。PNNs 的特异性沉积在 PV+ 中间神经元周围（而非其他神经元类型），反映了发育关键期关闭的精准执行机制。

**PNNs 的组成**（Mueller-Buehl & Faissner 2023，PMID:37143468）：
- **核心结构**：硫酸软骨素蛋白多糖（CSPGs），以 aggrecan 为主要成分（brevican、neurocan、versican 为次要成分）
- **骨架**：透明质酸（hyaluronan）链，与 CSPGs 和连接蛋白（link proteins）共同形成三维网状结构
- **特征分子**：高度硫酸化的硫酸软骨素链，硫酸化模式（4-硫酸化 vs 6-硫酸化）决定其功能

**关键期关闭的 PNN 机制**：在视觉皮层，关键期（眼优势可塑性窗口）的高峰期约在鼠出生后 P25–P35（小鼠），此后随 PNNs 沉积密度增加，可塑性逐渐降低。Takesian & Hensch（2013，PMID:24309249）指出，大脑不是"被动失去可塑性"，而是"主动关闭可塑性"——PNNs 是这一主动过程的关键分子工具。

## 关键机制

### 机制 1：OTX2 正反馈回路（PV 成熟的加速器）
1. 视网膜（眼睛）分泌的转录因子 OTX2 通过血液和 CSF 到达大脑
2. OTX2 通过结合 PNNs 的硫酸软骨素链被 PV+ 细胞**选择性内化**
3. 胞内 OTX2 激活 Kv3.1（钾通道基因），增强 PV+ 细胞快放电能力
4. 更成熟的 PV+ 细胞产生更多 PNN 组分 → PNN 更致密 → 关键期加速关闭
5. 关键实验证据：人工向视觉皮层输注 OTX2 可提前关闭关键期；清除 OTX2 可延迟关闭

### 机制 2：AMPA 受体固化（突触权重锁定）
- 正常情况下，突触 AMPA 受体在突触位点（固定态）和树突膜非突触区域（扩散态）之间动态流动
- PNNs 中 CSPGs 的物理屏障**限制 AMPA 受体侧向扩散**，维持突触位点的受体密度
- 效果：已形成的强突触连接被"固化"，可塑性所需的受体流动受限
- 可逆性证据：ChABC（软骨素酶）降解 PNNs → AMPA 受体流动性恢复 → 突触重新开放可塑性窗口

### 机制 3：PTPσ-TRKB 轴——封锁 BDNF 信号进入 PV+ 细胞（新增 2026-06-03）
- PNN 中的 aggrecan/CSPG 通过与 PTPσ（蛋白酪氨酸磷酸酶σ）相互作用，激活 PTPσ
- PTPσ 直接将 PV+ 细胞内 TRKB 去磷酸化，抑制 BDNF 信号进入 PV+ 细胞
- 效果：PV+ 细胞无法响应 BDNF 的可塑性驱动信号，回路状态固化
- **ChABC 破坏 PNN → aggrecan 消失 → PTPσ 压制解除 → TRKB 磷酸化恢复 → 关键期可塑性重开**
- **氟西汀（fluoxetine）直接结合 TRKB 跨膜域，竞争性干扰 TRKB-PTPσ 相互作用**，产生类似效果
- 关键证据：Lesnikova et al. 2021（J Neurosci，PMC7880295）：ChABC 和氟西汀均通过这一分子链重开视皮层可塑性
- 这将 PNN 降解、BDNF/TRKB 信号和抗抑郁药机制统一到同一条分子通路中

### 机制 4：轴突出芽抑制
- CSPGs 通过与受体酪氨酸磷酸酶 PTPσ 结合，**抑制轴突生长锥的伸展**
- 效果：防止成年期发育新的突触连接，维护已建立的回路拓扑

### 机制 4：PV+ 细胞氧化应激防护
- PV+ 细胞代谢率极高（持续快放电），对活性氧（ROS）特别脆弱
- PNNs 的致密 ECM 结构提供**离子缓冲**（减少氧化损伤相关的钙超载）和**物理屏障**
- 临床意义：精神分裂症患者中 PNN 减少可能加剧 PV+ 细胞的氧化损伤，与 GAD67 下调相互促进

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| ChABC 降解 PNNs 可在成年大鼠重开眼优势可塑性 | ChABC 注射 + 单侧眼遮蔽 + 记录 | 引用于 PMID:37143468 | 高（动物）|
| OTX2 通过 PNNs 内化促进 PV 成熟、加速关键期关闭 | 视网膜切除 / 胞内 OTX2 输注实验 | 引用于 PMID:37143468 | 高（动物）|
| PNNs 限制 AMPA 受体侧向流动，固定突触权重 | 单分子追踪 + ChABC 处理 | PMID:37143468（综述）| 中-高 |
| 精神分裂症患者前额叶 PNN 密度降低，与 γ 功率受损相关 | 尸检免疫组化 | PMID:37143468（综述）| 中（相关性，非因果）|
| PV 成熟触发关键期开启；PNN 固化触发关键期关闭 | GABA 操控（安定/免疫毒素）+ 发育时序 | PMID:16243601 | 高 |
| aggrecan 通过 PTPσ 降低 TRKB 磷酸化；PTPσ KO 保有成年可塑性 | 生化 + PTPσ KO + 光遗传 | PMID:33293360 | 高 |
| 成年皮层 PNN 密度受 PV+ 细胞活动动态调节 | DREADD 抑制 PV+ + PNN 定量（1周） | PMID:34045309 | 中-高 |

## 连接

- [[pv-interneurons]] — PNNs 特异性包裹 PV+ 细胞；通过 OTX2 驱动 PV 成熟
- [[ei-balance]] — PNNs 是发育期 E/I 平衡状态固化的分子基础
- [[synaptic-pruning]] — 发育期突触剪枝与 PNN 沉积在时间上协同，共同建立成年回路
- [[bdnf]] — BDNF 可促进 PV 细胞分化和 PNN 形成；aggrecan-PTPσ 轴抑制 TRKB（BDNF 受体）进入 PV+ 细胞
- [[critical-period]] — PNN 是关键期关闭的主刹车；ChABC 降解 PNN 可重开关键期

## 未解问题

- Q-pnn-human-therapy（高优先级）：ChABC 等 PNN 降解方法能否安全转化到人类？PNN 的氧化防护功能是否会被同时破坏？
- Q-ei-balance-02（相关）：E/I 失衡在精神分裂症中 PNN 减少是病因还是继发改变？
- Q-cp-04：不同脑区关键期时间窗口的差异是否与 PNN 沉积速率差异相关？

## 修订历史

- 2026-07-04 · 创建 · 基于《信号与噪声之间：皮层 E/I 平衡的回路逻辑》一文 · 初始置信度：高（动物证据强；人类转化有限）
- 2026-06-03 · 修订 rev2 · 基于《时间刻入神经回路：关键期的开关机制》(#72) · 新增机制3（PTPσ-TRKB 轴统一 ChABC/氟西汀机制，Lesnikova 2021）；新增成年 PNN 动态调节证据（Devienne 2021）；补充 critical-period 链接

## 来源文章

- [[2026-07-04-ei-balance-pv-interneuron]]
- [[2026-06-03-critical-period-plasticity]]

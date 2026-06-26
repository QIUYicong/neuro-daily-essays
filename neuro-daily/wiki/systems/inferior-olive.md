---
title: 下橄榄核
slug: inferior-olive
domain: systems
type: structure
status: established
confidence: high
created: 2026-10-07
updated: 2026-10-07
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region]
related: [climbing-fiber, purkinje-cell, gap-junction-electrical-synapse, cerebellum, deep-cerebellar-nuclei, cerebellar-ltd, motor-learning]
prerequisites: [gap-junction-electrical-synapse, climbing-fiber, synaptic-transmission, action-potential]
opens_questions: [Q-io-01, Q-io-02, Q-io-03, Q-io-04]
source_articles: [2026-10-07-inferior-olive-cx36-motor-learning]
key_sources: ["PMID:9735947", "PMID:18498740", "PMID:21151372", "PMID:24656256", "PMID:24990915", "PMID:29311830", "PMID:41345279"]
---

# 下橄榄核 (Inferior Olivary Nucleus)

> **一句话定义**：延髓腹侧的一对高度折叠状核团，通过高密度 Cx36 缝隙连接同步神经元的 4–10 Hz 亚阈值振荡，将运动误差信号以精确的时间码经攀爬纤维传递至对侧小脑浦肯野细胞，驱动运动学习；其同步性受小脑深核 GABAergic 反馈和 PKA/CaMKII 信号实时调控。

## 当前理解

下橄榄核（inferior olivary nucleus，IO）是小脑运动学习系统的"误差时钟"。它不直接参与运动执行，而是作为运动结果与预期之间的比较器，将误差信息以有时间结构的神经语言写入小脑。

我们现在认为，IO 的核心功能机制分三个层次：

1. **细胞内在节律**：IO 神经元因 T 型 Ca²⁺ 通道（CaV3）与 Ih（HCN）电流的相互拮抗，自发产生 4–10 Hz 亚阈值振荡（STO）。这是 IO 独特的内在属性——不依赖 Na⁺ 动作电位，可被 Ni²⁺ 而非 TTX 消除（Lampl & Yarom, 1997）。

2. **Cx36 缝隙连接同步**：树突小球（dendritic glomeruli）内，相邻 IO 神经元的树突棘通过 Cx36 电偶联，把各自的 STO 相位锁定，使 5–7 个神经元振荡步调一致。无缝隙连接时，各细胞可自发振荡但相位随机（Long et al., 2002）。

3. **同步放电→时间化的误差信号**：同步的 IO 神经元在振荡特定相位触发动作电位，经攀爬纤维（CF）触发浦肯野细胞（PC）的复杂放电（complex spike，CS）。CS 的时序精确性（哪一批 PC 在何时收到误差信号）和持续时间（编码误差量级）共同决定运动学习的方向、幅度和精度。

**IO 同步是运动学习的专属条件**：Cx36 敲除小鼠运动能力基本保留，但运动学习时序精度严重受损（Van Der Giessen et al., 2008）；人类服用 Cx36 阻断剂甲氟喹后，运动学习速度和容量受损而基础运动不受影响（van Essen et al., 2010）。这个双解离是支持"IO 同步专属于运动学习"最强的因果证据。

## 解剖结构

### 位置与整体形态
- **位置**：延髓腹侧，成对存在，左右各一个
- **形态**：高度折叠的薄片状，横截面如皱纸卷；折叠增大容纳密度
- **大小**：每侧约 50,000 个神经元
- **投射**：轴突越过正中线 → 对侧小脑皮层，以攀爬纤维形式与浦肯野细胞建立强突触（1:1 原则）

### 主要亚核
| 亚核 | 缩写 | 对应小脑区域 | 主要功能关联 |
|------|------|------------|------------|
| 主下橄榄核 | PIO | 小脑半球（外侧） | 精细肢体运动、认知运动 |
| 背侧副橄榄核 | DAO | 蚓部、前叶 | 体轴运动、下肢协调 |
| 内侧副橄榄核 | MAO | 蚓部、绒球 | 眼动、多感觉整合 |

### 树突小球（关键微结构）
- 5–7 个 IO 神经元将树突棘（dendritic spines）伸向同一微结构
- 相邻棘之间通过 **Cx36 缝隙连接**电偶联
- 每个小球既接受兴奋性（感觉/皮层）也接受抑制性（DCN GABAergic）突触输入
- 功能：同步偶联 + 门控调制的微型计算单元

## 关键机制

### 亚阈值振荡（STO）的离子基础
- **CaV3（T型 Ca²⁺ 通道）**：从超极化复极时激活 → 内向去极化电流 → 推向阈值
- **HCN（Ih）**：超极化时激活 → 恢复性去极化驱动；K⁺ 外流电流在峰后使膜复极
- 结果：相互追赶的振荡回路，频率 4–10 Hz
- 证据：TTX 无效，Ni²⁺ 基本消除 → CaV3 是核心，非 Na⁺ AP（Lampl & Yarom, 1997）

### Cx36 偶联的动态调控
| 调控信号 | 效果 | 机制 |
|---------|------|------|
| PKA 激活 | 偶联减弱 | 降低 Cx36 开放概率（Ser110/293 磷酸化） |
| βCaMKII 缺失 | 偶联几乎消失 | Cx36 数量从 87 → 1/mm² |
| DCN GABA_A 输入 | 耦合降低+STO 阻断 | 超极化 + 改变偶联强度 |

（Bazzigaluppi et al., 2017; Lefler et al., 2014）

### DCN → IO 反馈门控
小脑深核（DCN）发出 GABAergic 轴突投射回 IO（反馈回路）：
- 直接：超极化 IO 神经元
- 间接：降低 Cx36 电偶联强度，阻断 STO
- 意义：小脑可以从下游"关掉"误差广播——误差信号是受调控的，不是无条件广播

### 攀爬纤维 → 复杂放电 → LTD
IO 同步放电 → CF 激活 → 浦肯野细胞复杂放电：
- CS 触发大量 Ca²⁺ 内流（P/Q 型 VGCC）+ mGluR1 信号 → PF-PC LTD
- CS 持续时间越长 → Ca²⁺ 峰值越高 → LTD 越强 → 运动修正幅度越大（Yang & Lisberger, 2014）
- CS 跨微区同步增强 → 大规模协调修正（De Gruijl et al., 2014）

## 关键证据
| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| IO STO 由 CaV3 + Ih 产生，不依赖 Na⁺ AP | 豚鼠体外，TTX/Ni²⁺药理，阻抗分析 | PMID:9145790 | 高 |
| 单细胞可振荡，但 Cx36 GJ 提供跨细胞同步 | Cx36 KO 小鼠体外 IO 记录 | PMID:12486184 | 高 |
| Cx36 KO 导致 CS 时序变异增大，运动学习受损 | Cx36 KO 小鼠；眨眼条件反射+步态 | PMID:18498740 | 高 |
| 甲氟喹（Cx36 阻断剂）损害人类运动学习，不影响执行 | 随机对照试验，健康人群 | PMID:21151372 | 高 |
| DCN-GABA 输入降低 IO 耦合并阻断 STO | 体外 IO 切片 + DCN 刺激 | PMID:24656256 | 中-高 |
| PKA → Cx36 开放概率降低；βCaMKII KO → Cx36 数量骤降 | 小鼠基因 KO + 免疫组化 | PMID:29311830 | 高 |
| 运动时 Cx36 KO 小鼠 CS 不能跨微区同步，反射变慢 | 多电极阵列体内 + 行为 | PMID:24990915 | 中-高 |
| 灵长类 IO 也有 STO 和电偶联（保守性） | 恒河猴双重膜片钳 | PMID:27307237 | 高 |
| 种群级正/负交替 CS 调制编码误差方向+量级 | 小鼠体内钙成像，操纵杆扰动任务 | PMID:41345279 | 中（单实验室，2025年新） |

## 连接
- [[climbing-fiber]] — IO 的轴突投射；攀爬纤维是 IO→PC 的信号载体
- [[purkinje-cell]] — CF 的突触靶点；CS 触发 LTD
- [[gap-junction-electrical-synapse]] — Cx36 缝隙连接是 IO 同步的分子基础
- [[cerebellum]] — IO 是小脑运动学习系统的误差节律源
- [[deep-cerebellar-nuclei]] — DCN→IO 的 GABAergic 反馈门控误差广播
- [[cerebellar-ltd]] — CS 诱导的 PF-PC LTD 是运动学习的突触机制（待建专页）
- [[motor-learning]] — IO 同步是精确运动学习的专属必要条件

## 未解问题
- **Q-io-01（高优先级）**：IO STO 因果性——全局 Cx36 KO 有发育代偿问题；成年期条件 KO + 光遗传学控制同步性将给出更干净的因果证据
- **Q-io-02（高优先级）**：STO 相位到 CF 放电的触发机制——什么条件决定 STO 峰值是否突破阈值？DCN GABA 的相位门控？
- **Q-io-03（中优先级）**：IO 跨亚核长程同步——是否存在、范围多大、协调大范围运动的功能证据
- **Q-io-04（中优先级）**：DCN GABAergic 门控与甲氟喹 Cx36 阻断的功能是否完全等价，还是有精细空间选择性差异

## 修订历史
- 2026-10-07 · 创建 · 基于《下橄榄核：大脑最奇特的节律师》（#167）· 初始置信度：高（解剖与经典功能 established；Nguyen 2025 种群级编码：emerging）

## 来源文章
- [[2026-10-07-inferior-olive-cx36-motor-learning]]

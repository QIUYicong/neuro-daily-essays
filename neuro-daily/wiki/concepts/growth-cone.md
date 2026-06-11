---
title: 生长锥
slug: growth-cone
domain: concepts
type: structure
status: established
confidence: high
created: 2026-08-04
updated: 2026-08-04
revision_count: 1
dimensions: [molecular, cellular]
related: [axon-guidance, synaptogenesis, actin-cytoskeleton, axon-initial-segment]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: [Q-axon-guidance-01, Q-axon-guidance-03]
source_articles: [2026-08-04-axon-guidance-growth-cone-wiring]
key_sources: ["PMID:21123392", "PMID:36942388", "PMID:8895455"]
---

# 生长锥 (Growth Cone)

> **一句话定义**：生长锥是发育中的轴突顶端高度动态的感觉-运动装置，由板状伪足（lamellipodia）和丝状伪足（filopodia）构成，通过肌动蛋白踏车运动向前推进，并通过感知外部导向信号驱动不对称的骨架重组，实现精准的方向性轴突延伸。

---

## 当前理解

生长锥是1890年由卡哈尔（Ramón y Cajal）在银染胚胎脊髓切片中首次观察和描述的。他直觉地推测这是轴突主动寻找目标的感觉器官——事实证明他是对的，尽管那时分子生物学还不存在。

生长锥同时执行两个功能：
1. **感觉功能**：丝状伪足顶端密布导向分子受体（DCC、ROBO、NRP、EphA/B），不断采样周围化学环境。
2. **运动功能**：将感知到的化学不对称性转化为肌动蛋白骨架的不对称重组，驱动生长锥向特定方向前进。

生长锥因此是一个**实时的"感知-执行"整合器**，在没有任何神经信号参与的情况下，在细胞生物学层面完成轴突的导航决策。

---

## 关键机制

### 结构组成

| 结构 | 骨架类型 | 功能 |
|------|---------|------|
| 板状伪足（lamellipodia） | 网状分支 F-actin（Arp2/3 介导） | 宽扁探索区，整合全局方向信息 |
| 丝状伪足（filopodia） | 束状平行 F-actin（Fascin 捆绑）| 细长前哨探针，5-50 µm，采样精细局部信号 |
| 中央区（C域） | 微管主导 | 轴突延伸的骨架支撑，轴突物质运输通道 |
| 过渡区（T域） | F-actin + 肌球蛋白 II | 连接板状伪足和中央区，产生向心性 F-actin 流 |

### 踏车运动（Treadmilling）

F-actin 的踏车运动是生长锥前进的核心引擎：
- **(+)端**（丝状伪足前端）：G-actin 单体聚合，消耗 ATP，推动膜向前。
- **(-) 端**（过渡区）：F-actin 解聚，回收 G-actin 单体。
- **肌球蛋白 II**：在过渡区驱动 F-actin 网络向轴突方向的向心性流（retrograde flow）。

**产生前进**的条件：丝状伪足前端的 F-actin 与基质（或靶细胞）发生粘附（通过整合素或细胞粘附分子），将向心性流的力学对立面转化为向前的推力。

### 导向信号转化为方向转向

**吸引信号**（如 Netrin-1/DCC）：
- DCC → FAK、Src → 招募 DOCK1 → 激活 Rac1/Cdc42
- Rac1/Cdc42 → N-WASP/WAVE → Arp2/3 → F-actin 分支聚合
- 信号侧 F-actin 增多 → 该侧丝状伪足延伸 → 生长锥转向该侧

**排斥信号**（如 Sema3A/Plexin）：
- Plexin 激活 GAP 域 → 抑制 R-RAS → 降低整合素粘附
- MICAL 被激活 → 氧化 F-actin 的 Met44/Met47 → F-actin 不稳定解聚
- 信号侧 F-actin 减少 + 粘附降低 → 该侧丝状伪足收缩 → 生长锥转离该侧

### 生长锥的动态重编程

生长锥不仅被动响应信号，还会主动改变自身的响应能力：
- 穿越中线后：Robo3 下调 → 解除对 Robo1 的抑制 → 对 Slit 的排斥敏感性急剧升高
- 局部翻译：生长锥内部有 mRNA 池，可在接收到特定导向信号（如 Sema3A）后快速在局部翻译 RhoA，放大排斥响应，而无需等待细胞体的蛋白合成和轴浆运输

---

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| 板状伪足由 Arp2/3 介导的分支肌动蛋白网络支撑 | Arp2/3 抑制剂（cytochalasin）消除板状伪足；超分辨荧光成像 | 多来源 | 高 |
| 生长锥通过整合素-基质粘附产生前进推力 | 整合素功能阻断抗体阻止轴突延伸 | PMID:21123392 | 高 |
| DCC 信号通过 Rac1/Cdc42 → Arp2/3 驱动吸引性转向 | DCC 胞内结构域突变体；体外梯度转向 + 信号通路抑制 | PMID:21123392; PMID:36942388 | 高 |
| MICAL 氧化 F-actin 驱动 Semaphorin 排斥 | MICAL 生化活性；MICAL KO → 排斥减弱 | PMID:36942388 | 中-高 |
| 生长锥内的局部 mRNA 翻译参与导向响应 | β-actin mRNA 局部定位；荧光报告蛋白局部翻译追踪 | PMID:21123392 | 中（体外为主） |

---

## 连接

- [[axon-guidance]] — 生长锥是轴突导向机制的执行器官；四大导向分子家族作用于生长锥上的受体
- [[axon-initial-segment]] — 成熟轴突的另一端：动作电位的发起位点；与生长锥共同构成轴突的功能极性
- [[synaptogenesis]] — 生长锥到达靶区并停止延伸后，转化为突触的预前体结构
- [[critical-period]] — 关键期可塑性中，成熟神经元的轴突侧枝仍保留部分生长锥样的伸展能力

---

## 未解问题

- **Q-axon-guidance-01**：体内导向分子梯度的实际形态——体内梯度测量技术的突破将直接检验生长锥在真实环境中的感知能力
- **Q-axon-guidance-03**：多信号整合机制——生长锥如何计算同时存在的吸引和排斥信号的合力向量？

---

## 修订历史

- 2026-08-04 · 创建 · 基于《大脑如何给自己布线》文章（#103）· 填补 axon-guidance 相关缺口 · 初始置信度：高（established，基础细胞生物学证据充分）

---

## 来源文章

- [[2026-08-04-axon-guidance-growth-cone-wiring]]

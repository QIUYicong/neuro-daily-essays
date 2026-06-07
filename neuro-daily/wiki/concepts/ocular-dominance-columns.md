---
title: 眼优势柱
slug: ocular-dominance-columns
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-15
updated: 2026-08-15
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, systems, cognition]
related: [v1-primary-visual-cortex, critical-period, retinal-waves, pv-interneurons, perineuronal-nets, ltp, ltd, silent-synapse, bdnf, thalamocortical-axons, ei-balance, orientation-selectivity, homeostatic-plasticity]
prerequisites: [synaptic-transmission, ltp, ltd, critical-period, v1-primary-visual-cortex, thalamocortical-axons]
opens_questions: [Q-odc-01, Q-odc-02, Q-odc-03]
source_articles: [2026-08-15-ocular-dominance-columns-visual-critical-period]
key_sources: ["PMID:22841309", "PMID:32765222", "PMID:23975100", "PMID:39036421", "PMID:11861172"]
---

# 眼优势柱 (Ocular Dominance Columns, ODC)

> **一句话定义**：在猫和灵长类的初级视觉皮层（V1）Layer 4，来自左眼和右眼的 LGN 轴突通过活动依赖的 Hebbian 竞争形成的交替分布条带状功能图谱（宽约 0.5–1 mm）；其形成分两阶段——视网膜波驱动的解剖前体（出生前）和关键期视觉经验驱动的生理成熟（出生后），啮齿类缺乏解剖 ODC 但有完整的眼优势可塑性（ODP）。

## 当前理解

我们现在认为，ODC 不是一种预先写死的解剖结构，而是**遗传分子梯度与活动依赖竞争协同作用的动态产物**。ODC 的形成和维持体现了大脑皮层最核心的组织原则之一：相关活动的输入轴突争取突触空间，不相关的失去。

**发育时间轴（Espinosa & Stryker 2012，PMID: 22841309）**：
1. 出生前：视网膜波（Stage II，乙酰胆碱依赖）驱动 LGN 眼特异性分层；同一眼 RGC 放电高度同步、两眼 RGC 不同步 → Hebbian 竞争使同眼轴突聚集
2. 出生前后：LGN 眼特异性轴突（TCAs）抵达 V1 Layer 4，形成解剖 ODC 雏形（经验独立）
3. 关键期（小鼠 ~P21–P35）：真实视觉经验驱动生理 ODP——双眼竞争雕刻最终的眼优势分布

**物种差异**：
- 猫、灵长类：清晰的 ODC 条带（单眼宽 ~0.5–1 mm，交替分布）
- 啮齿类小鼠：无 ODC 条带（盐-胡椒混合分布）；但有完整 ODP
- 长毛大鼠（Long-Evans）：有 ODC；白化大鼠：无（ipsilateral 投射异常导致，Takahata 2024）
- 这说明 ODC 存在与否取决于 ipsilateral/contralateral 输入比例，不等同于"是否有关键期"

## 关键机制

### 1. 视网膜波驱动的 LGN 预分层（出生前）

- β2-nAChR（烟碱型乙酰胆碱受体）驱动自发视网膜波
- 同一眼的 RGC 时间相关性高 → Hebbian 竞争 → 同眼 LGN 突触增强
- β2-nAChR KO → 视网膜波消失 → LGN 层间混合 → V1 视野图破坏
- ephrin-A + 视网膜波双重 KO → V1 方位图几乎完全消失（两机制必须协同）

### 2. 关键期 ODP 的回路机制（出生后）

**去抑制启动**（Kuhlman et al. 2013，PMID: 23975100）：
- MD → 被剥夺眼驱动减弱 → PV+ 中间神经元（先于锥体细胞 ~24 小时）活动下降
- PV+ 围体抑制减弱 → L4 锥体细胞进入可塑状态（去抑制启动）

**阶段一：剥夺眼 LTD（MD 第 1–4 天）**
- NMDAR 不足激活（低 Ca²⁺）→ PP2B/PP1 激活 → GluA2 AMPAR 内吞 → 剥夺眼突触权重↓
- 不依赖蛋白质合成；阻断 NMDAR 或 AMPAR 内吞均阻止阶段一

**阶段二：开放眼 LTP + 稳态缩放（MD 第 3–7 天）**
- NMDAR 充分激活（高 Ca²⁺）→ CaMKII 激活 → GluA1 磷酸化 → AMPAR 插入 → 开放眼突触权重↑
- 稳态缩放（TNFα 介导）：总活动下降 → 全局上调 AMPAR 密度 → 维持活动稳态
- 依赖 BDNF-TrkB 信号和蛋白质合成

### 3. 沉默突触的开锁（AMPA/NMDA 比值上升）

（详见 [[silent-synapse]]）
- 关键期初：大量沉默突触（NMDAR only, AMPA/NMDA ~0.3–0.5）
- 视觉活动驱动 AMPAR 插入（"开锁"）→ AMPA/NMDA 比值升至 ~1–2
- PSD-95 KO → 无法完成开锁 → 关键期延长
- 关键期关闭 ≈ 沉默突触耗竭 + PNN 封印

### 4. tPA-塑素级联的结构重塑（MD 1–2 周）

- 活跃突触末梢分泌 tPA → 纤溶酶原 → 塑素（胞外蛋白酶）
- 塑素降解细胞外基质（层粘连蛋白等）→ 树突棘流动性增加 → 突触接触点调整
- 功能性 OD 偏移（几天）早于解剖学 ODC 重塑（1–2 周）；两层机制时序分离

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| β2-nAChR KO 视网膜波消失→LGN 分层破坏 | 基因 KO + 电生理 + 解剖 | PMID:22841309 (综述) | 高 |
| ephrin-A + 视网膜波双重 KO→V1 视野图几乎消失 | 双重 KO + intrinsic imaging | PMID:22841309 | 高 |
| MD 后 PV+ 活动先于锥体细胞下降（~24h） | 双光子 Ca 成像 | PMID:23975100 | 高 |
| ChR2 维持 PV+→OD 偏移被阻止 | 光遗传 + VEP | PMID:23975100 | 高 |
| ODP 阶段一（剥夺眼）：NMDAR-LTD，不依赖蛋白质合成 | APV/放线菌素 D/AMPAR 内吞阻断 | PMID:22841309 | 高 |
| ODP 阶段二（开放眼）：BDNF-TrkB 依赖；TNFα KO 破坏稳态缩放 | TrkB KO + TNFα KO + VEP | PMID:22841309 | 高 |
| 沉默突触开锁→AMPA/NMDA 比值 ~0.3→~2 | 单突触电生理 | PMID:32765222 (综述) | 中-高 |
| Long-Evans 大鼠有 ODC；白化大鼠无 | 解剖+功能成像 | PMID:39036421 | 中-高 |

## 连接

- [[v1-primary-visual-cortex]] — ODC 在 V1 Layer 4 形成；双眼视觉处理的解剖基础
- [[critical-period]] — ODC 成熟发生在关键期内；PV+/PNN 机制共用
- [[retinal-waves]] — 驱动 LGN 眼特异性预分层；ODC 解剖前体的形成驱动力
- [[pv-interneurons]] — 去抑制启动机制：PV+ 活动下降触发 ODP 入口
- [[ltp]] — 开放眼 LTP 是 ODP 阶段二的主要突触机制
- [[ltd]] — 剥夺眼 LTD 是 ODP 阶段一的主要突触机制
- [[bdnf]] — TrkB 信号驱动开放眼阶段二增强；依赖蛋白质合成
- [[perineuronal-nets]] — PNN 封印关键期结束，固化 ODC 最终格局
- [[thalamocortical-axons]] — TCA 是 ODC 形成的物质基础；TCA 到达 V1 Layer 4 是 ODC 竞争的前提
- [[homeostatic-plasticity]] — 稳态突触缩放是 ODP 阶段二的并行机制（TNFα 介导）
- [[orientation-selectivity]] — ODC 与方向图在 V1 重叠；两种图谱形成机制有平行之处

## 未解问题

- Q-odc-01（高优先级）：人类 V1 ODC 的发育时序——人类关键期 ODC 竞争的分子时钟是否与视网膜波、AMPA/NMDA 比值相关，还是由人类特异性发育时钟决定？
- Q-odc-02（中优先级）：小鼠无 ODC 条带，但有 ODP——这是否意味着 ODC 形成和 ODP 竞争在机制上是可解耦的？具体哪些机制是 ODC 形成必需但 ODP 非必需的？
- Q-odc-03（中优先级）：ODP 阶段二（开放眼增强）的主导机制到底是 Hebbian LTP（沉默突触开锁，Xu 2020）还是稳态缩放（TNFα/Kaneko 2017）？两者的时间窗口和层级特异性分工如何？（见 contested_claims C-2026-08-15-01）

## 修订历史

- 2026-08-15 · 创建 rev1 · 基于《左眼还是右眼：视觉皮层如何通过 Hebbian 竞争从沉默突触中雕刻出眼优势柱》(#114) · 初始置信度：高

## 来源文章

- [[2026-08-15-ocular-dominance-columns-visual-critical-period]]

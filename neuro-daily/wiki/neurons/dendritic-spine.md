---
title: 树突棘
slug: dendritic-spine
domain: neurons
type: structure
status: established
confidence: high
created: 2026-09-23
updated: 2026-09-23
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [ltp, camkii, dendritic-computation, ampa-receptor, nmda-receptor, cofilin-actin, synaptic-tagging-capture, btsp, pkm-zeta, engram-cells, pyramidal-neuron, postsynaptic-density]
prerequisites: [synaptic-transmission, ltp, ampa-receptor]
opens_questions: [Q-spine-01, Q-spine-02, Q-spine-03, Q-spine-04]
source_articles: [2026-09-23-dendritic-spine-structural-ltp-actin]
key_sources: ["PMID:15190253", "PMID:20835250", "PMID:24742465", "PMID:37489746", "PMID:41249054", "PMID:39158722", "PMID:34440848", "PMID:19448623"]
---

# 树突棘 (Dendritic Spine)

> **一句话定义**：大多数兴奋性突触建立在其上的树突微型突起，形如蘑菇，由肌动蛋白骨架支撑；LTP 期间棘头持续扩大（结构性 LTP），为突触强度增加提供物理基底，是记忆以物质形态持久存在的微观载体。

## 当前理解

我们现在认为，树突棘不是被动的突触附着点，而是**有动态可塑性的信息存储单元**：

1. **形态即功能的记录**：棘头体积与突触权重正相关——更大的棘头容纳更多的 PSD 面积 → 更多 AMPA 受体 → 更强的兴奋性突触电位。因此，棘头体积是突触强度的**物理记录仪**。

2. **肌动蛋白（actin）骨架决定棘头形态**：约 85% 的棘头肌动蛋白处于动态踏车运动（G-actin↔F-actin 持续循环）；约 15% 是稳定 F-actin 核心。通过调控聚合/解聚速率，无需合成新蛋白质即可在数分钟内改变棘头体积。

3. **结构性 LTP（sLTP）是功能性 LTP 的物理接力棒**：LTP 诱导后的分钟至小时内，棘头体积持续扩大（Matsuzaki 2004）；这种结构扩大为 PKMζ 等晚期维持机制提供了物理空间（更大棘头→更多 AMPAR 插入槽位），确保功能性增强在蛋白质更新过程中得以维持。

4. **记忆的物质印记**：Yang 等人（2009，PMID:19448623）的慢性双光子成像显示，小鼠运动技能学习后出现的新生棘，在数月内保持稳定——成功的运动记忆在大脑皮层留下了可以用显微镜看见的物理结构。

## 关键形态与组成

### 蘑菇型棘的三部分

| 结构 | 直径/长度 | 主要成分 | 功能 |
|------|---------|---------|------|
| **棘头（spine head）** | 0.1–2 μm | PSD、AMPAR、NMDAR、CaMKII、actin | 突触后信号整合；LTP 的主要表达位点 |
| **棘颈（spine neck）** | 0.1–1.5 μm（长）；0.05–0.2 μm（径） | F-actin 网络 | 电学和化学隔离（限制 Ca²⁺ 和 cAMP 扩散到树突轴） |
| **棘设备（spine apparatus）** | 存在于大型蘑菇棘中 | 堆叠 ER 膜；synaptopodin | 本地 Ca²⁺ 储存、IP₃R 介导的 Ca²⁺ 释放；本地蛋白合成平台 |

### 棘的形态谱系

- **蘑菇型（mushroom）**：大棘头+细颈；成熟突触，已有稳固的 LTP；PSD 面积大
- **细薄型（thin）**：小棘头；更易被诱导 sLTP（Matsuzaki 2004：小棘是 LTP 优先位点）
- **粗短型（stubby）**：无明显颈部；见于发育期
- **丝状伪足（filopodia）**：细长无头；突触发生前驱体；探索性结构

## 结构性 LTP 的分子级联

sLTP 分三个时相，共同作用产生持久棘头扩大：

### 第一时相（0–5 分钟）：Cofilin 去磷酸化→actin 短暂解聚

```
NMDA-R → Ca²⁺ → Calcineurin（PP2B）→ SSH1（磷酸酶）→ cofilin-1 去磷酸化（Ser3）
                                                          → cofilin 激活
                                                          → F-actin 切割/解聚
                                                          → G-actin 单体供应增加
```

活化的 cofilin 大量涌入棘头（Bosch 2014，PMID:24742465）；棘头体积尚未扩大，但单体库建立。

### 第二时相（5–30 分钟）：Rac1→Arp2/3→F-actin 分支扩增→棘头扩大

```
主通路：CaMKII → Tiam1（Rac1 GEF） → Rac1 → WAVE/WASP → Arp2/3
                                                         → F-actin 新分支 → 棘头体积扩大

磷脂层：PI3K/p85α → Rac1/Cdc42（López-García 2024，PMID:39158722）

直接锚定：CaMKII → α-actinin-2（F-actin 交联蛋白） → PSD 与 F-actin 的物理耦合（Yu 2023，PMID:37489746）

独立通路：Rac1（直接激活，无需 CaMKII） → PAK1 → actin 扩张（Saneyoshi 2025，PMID:41249054）
```

### 第三时相（>30 分钟）：LIMK→Cofilin 再磷酸化→F-actin 锁定

```
Rac1 → PAK → LIMK1/2 → cofilin-1 磷酸化（Ser3）→ cofilin 失活
                                                   → 停止 F-actin 解聚
                                                   → 扩大后的 F-actin 网络稳定维持
```

负反馈闭环：Rac1 扩张 F-actin 同时激活 LIMK 保护自己建造的结构。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 单棘 sLTP：棘头体积扩大 2–3 倍且持续 | 双光子解笼放谷氨酸；离体 CA1 切片 | PMID:15190253 | 高 |
| LTP→F-actin 增加；LTD→G-actin 增加（双向） | FRET 肌动蛋白传感器活细胞成像 | PMID:15361876 | 高 |
| Cofilin 去磷酸化→再磷酸化时序驱动 AMPAR 插入 | 生化分析 + 磷酸化 cofilin 抗体 + LTP 功能测量 | PMID:20835250 | 高 |
| Cofilin 涌入棘头的三波动态（对应三时相） | 荧光标记蛋白 + 2P 成像 | PMID:24742465 | 高 |
| CaMKII/α-actinin-2 复合体直接锚定 F-actin | 蛋白互作验证 + 突变体小鼠 + 棘形态分析 | PMID:37489746 | 高 |
| Rac1 单独激活→持久 sLTP（不依赖 CaMKII） | 光遗传 Rac1 + CaMKII 抑制剂共同应用 | PMID:41249054 | 高 |
| PI3K/p85α 选择性参与 LTP（非 LTD）；与 cofilin 耦合 | p85α siRNA 敲降；LTP/LTD 分离实验 | PMID:39158722 | 高 |
| LIMK 是 F-actin 锁定的关键激酶（KO→结构异常+学习受损） | LIMK1 KO 小鼠行为+形态分析 | PMID:34440848 | 高 |
| 运动学习后新生棘维持数月（记忆-棘对应） | 慢性双光子成像，小鼠运动皮层 | PMID:19448623 | 高 |
| LIMK 抑制→成年视觉皮层关键期样可塑性重开 | 视觉皮层注射 LIMK 抑制肽 + 眼优势可塑性测量 | PMID:41506312 | 中（动物）|

## 功能性 LTP 与结构性 LTP 的关系

两者**高度耦合但可解耦**：

**耦合机制**：
- 同一 Ca²⁺ 信号并行驱动：CaMKII → GluA1-S831 磷酸化（功能性）AND CaMKII → Rac1 → actin（结构性）
- 棘头扩大提供更多 PSD 面积 → 容纳更多 AMPAR（物理扩容）

**解耦证据**（Biosystems 2026）：
- 阻断 actin 重塑 → 仍可有有限功能性 LTP（但幅度减小、维持时间缩短）
- 光遗传 Rac1 → 纯粹结构 sLTP（无明显功能性 LTP）

**解读**：结构性 LTP 是功能性 LTP 长期维持的**物理保障**，而非功能增强的唯一条件。

## 棘设备（Spine Apparatus）

较大的蘑菇型棘（即经历 sLTP 的棘）内含棘设备：内质网（ER）延伸形成的堆叠囊泡结构。

- **synaptopodin** 是棘设备的关键组织蛋白；synaptopodin 过表达 → 棘设备和活跃突触数量增加（PMID:42277239）
- 棘设备提供本地 Ca²⁺ 储存（IP₃R/RyR）和本地蛋白合成平台
- 连接到突触标签-捕获（STC）理论：大型棘（即"标记"突触）有棘设备 → 有 mRNA 翻译能力 → 是 PRP 合成的本地基础

## 连接

- [[ltp]] — 树突棘是 LTP 的物理基底；功能性 LTP 与结构性 LTP 耦合
- [[camkii]] — CaMKII 通过 Tiam1/Rac1 和 α-actinin-2 驱动 sLTP 的两条分叉通路
- [[ampa-receptor]] — 棘头体积与 AMPA 受体数量正相关；扩大棘头容纳更多 AMPAR 槽位
- [[nmda-receptor]] — NMDAR 开放触发 Ca²⁺ 内流，启动 sLTP 级联
- [[dendritic-computation]] — 树突棘是树突计算的基本单元；棘颈提供化学隔离，使棘头 Ca²⁺ 动态成为局部整合单元
- [[synaptic-tagging-capture]] — 大型棘（经历 sLTP 后）含棘设备，是突触标签捕获 PRP 的物理载体
- [[pkm-zeta]] — PKMζ 维持 AMPAR 数量；结构性 sLTP 为 PKMζ 提供可维持更多 AMPAR 的物理空间
- [[btsp]] — BTSP 可能通过 sLTP 在场所场内棘上留下持久结构标记
- [[engram-cells]] — 印迹细胞中 AMPA/NMDA 比值高于非印迹细胞，可能对应更多/更大的棘
- [[postsynaptic-density]] — PSD 是棘头的功能核心；棘头扩大伴随 PSD 面积扩大和重构
- [[pyramidal-neuron]] — 皮层锥体神经元是树突棘最丰富的细胞类型之一

## 未解问题

- **Q-spine-01**（高优先级）：体内清醒行为动物中，自然学习是否在 1–48 小时尺度内产生与体外（解笼放谷氨酸）相同幅度的单棘体积变化？中间时间段无直接证据
- **Q-spine-02**（中优先级）：sLTP 后扩大的棘在日级时间尺度上如何维持？LIMK 锁定解释即时稳定（分钟级），天级维持机制不明
- **Q-spine-03**（中优先级）：体内功能性 LTP 和结构性 LTP 各自对行为记忆的贡献如何分配？能否分别损伤并分别测试行为？
- **Q-spine-04**（低优先级）：PI(4,5)P₂ 在棘头不同微区的时空分布如何指导 actin 重塑的空间模式（需超分辨脂质成像）？

## 修订历史

- 2026-09-23 · 创建 · 基于《突触的形状即记忆的形状》(#153) · 初始置信度：高（sLTP 分子机制 established；体内长期棘稳定性 established；体内时序细节中等）

## 来源文章

- [[2026-09-23-dendritic-spine-structural-ltp-actin]]

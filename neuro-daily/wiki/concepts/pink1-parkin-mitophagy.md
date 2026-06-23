---
title: PINK1/Parkin 线粒体自噬
slug: pink1-parkin-mitophagy
domain: concepts
type: mechanism
status: mainstream
confidence: medium
created: 2026-09-09
updated: 2026-09-09
revision_count: 1
dimensions: [molecular, cellular, disease]
related: [mitochondrial-dysfunction, parkinsons-disease, alzheimers-disease, ubiquitin-proteasome-system]
prerequisites: [mitochondrial-dysfunction]
opens_questions: [Q-mito-02]
source_articles: [2026-09-09-mitochondrial-dysfunction-neurodegeneration]
key_sources: ["PMID:33168089", "PMC7654589", "PMID:38744846", "PMC11094169"]
---

# PINK1/Parkin 线粒体自噬 (PINK1/Parkin-mediated Mitophagy)

> **一句话定义**：当线粒体膜电位（ΔΨm）消失时，PINK1 在外膜积累并磷酸化泛素（Ser65），招募并激活 Parkin E3 泛素连接酶，通过正反馈放大的泛素化链标记受损线粒体，再由 NDP52/OPTN 连接自噬体将其送往溶酶体降解——这是神经元清除功能障碍线粒体的核心质量控制机制，PINK1 和 Parkin 基因突变是早发性帕金森病的主要遗传原因。

## 当前理解

我们现在认为，PINK1/Parkin 通路是一个高度依赖 **ΔΨm 作为"损伤传感器"** 的精密质量控制系统。其最核心的设计逻辑是：在健康线粒体上，PINK1 被持续导入并快速降解（维持低水平），系统处于"关闭"状态；一旦线粒体 ΔΨm 消失（无论是 ETC 缺陷、Ca²⁺ 超载还是氧化损伤造成），PINK1 无法被拉入内膜，在外膜积累并触发一个具有正反馈放大特性的级联反应，最终将受损线粒体打包清除。

这一通路的医学意义无法过分强调：编码 PINK1 的 *PARK6* 基因和编码 Parkin 的 *PARK2* 基因突变是人类早发性（发病年龄 <40 岁）帕金森病的最常见常染色体隐性遗传原因，直接证明了线粒体质量控制失效是 PD 发病的充分条件（PMID:33168089, PMC7654589）。

**重要不确定性**：大量机制证据来自体外急性 CCCP（解偶联剂）处理模型。Pink1 基因敲除小鼠表现出相对轻微的表型（无 PD 样大量神经退化），但 CRISPR/Cas9 介导的 Pink1 敲除猕猴出现严重的皮层/纹状体/黑质神经退化，暗示体内慢性低水平压力下的通路活性与急性体外模型差异显著，小鼠存在代偿机制。

## 关键机制

### 第一步：PINK1 的条件性积累（ΔΨm 传感）

**健康线粒体**：
1. PINK1 在细胞质中合成，含有 N 端线粒体靶向序列（MTS）
2. TOM 复合体识别 MTS → TIM23 复合体需要 ΔΨm（~−180 mV）驱动，将 PINK1 导入内膜
3. PARL（内膜菱形蛋白酶）在内膜处切割 PINK1 → 切割片段被 26S 蛋白酶体降解
4. 结果：PINK1 蛋白水平维持极低

**损伤线粒体（ΔΨm ↓↓）**：
1. TIM23 无法在无 ΔΨm 的情况下拉动 PINK1 进入内膜
2. PINK1 滞留在外膜（OMM），由 Tom7 辅助稳定
3. OMM 上的 PINK1 发生**二聚化**和**自磷酸化（Thr257/Ser228）**→ 催化活性激活
4. 激活的 PINK1 开始磷酸化 OMM 上的底物（首先是游离的泛素 Ub）

### 第二步：Parkin 招募与激活（正反馈机制）

**Parkin 的自抑制状态**（细胞质中）：
- REP 结构域遮蔽 E2 结合位点（RING1）
- RING0 结构域封闭催化 Cys431
- Ubl 结构域维持自我抑制

**激活步骤（有序多步）**：
1. PINK1 磷酸化游离 Ub 的 **Ser65** → **pSer65-Ub（磷酸化泛素）**
2. pSer65-Ub 与 Parkin 的 Ubl 结构域结合 → 触发构象重排（Ubl 从自抑制位置移开）
3. PINK1 同时磷酸化 Parkin 自身的 Ubl **Ser65** → 进一步增强 pUb 的结合亲和力
4. 构象重排后，RING1 上的 E2 结合位点暴露 → Parkin 与 UBE2D/UBE2L3 E2 偶联 → E3 连接酶活性完全激活

**正反馈放大**：
- 激活的 Parkin 泛素化 OMM 蛋白，生成 Ub 链
- 链上新的 Ub 分子被 PINK1 继续磷酸化为 pUb
- pUb 链再招募更多 Parkin → 更多泛素化 → 更多 pUb → 信号指数放大

### 第三步：自噬体招募与溶酶体降解

- pUb 链被**线粒体自噬适配蛋白**识别：**NDP52**（核域 10 蛋白 52）和 **optineurin（OPTN）**
- **TBK1**（TANK 结合激酶 1）磷酸化 OPTN → 增强 OPTN 与 pUb 的结合亲和力
- NDP52/OPTN 通过 **LIR（LC3 相互作用区）**结构域与自噬体表面的 **LC3** 结合
- LC3+ 自噬体包裹线粒体 → 与溶酶体融合 → 自溶酶体 → 线粒体蛋白被水解，氨基酸/脂质回收

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| PINK1 在 ΔΨm 丢失（CCCP处理）时在 OMM 积累，健康线粒体上快速降解 | 荧光标记 PINK1 + CCCP处理；Western blot；电镜 | PMC7654589 | 高（体外）；中（体内） |
| PINK1 磷酸化 Ub Ser65 是 Parkin 招募的关键信号 | Ub Ser65Ala 突变阻断 Parkin 招募；磷特异性抗体 | PMC7654589 | 高 |
| NDP52 和 OPTN 是主要的线粒体自噬适配蛋白 | NDP52/OPTN 双敲除细胞；荧光 LC3 追踪 | PMC7654589 | 高（细胞模型） |
| PD 患者 PINK1 基因突变阻止 ΔΨm 丢失时的 PINK1 OMM 积累 | 患者源 iPSC 神经元；PINK1 突变重组蛋白 | PMC7654589 | 高 |
| Pink1 KO 猕猴出现严重神经退化（小鼠不出现） | CRISPR/Cas9 猕猴 Pink1 敲除（2019-2020年中国实验室） | PMC7654589 | 高 |
| AD 患者成纤维细胞中 Parkin 招募受损（无 Parkin 基因突变） | 原代成纤维细胞去极化后 Parkin 定位追踪 | PMC7654589 | 中（细胞模型；机制未完全阐明） |

## 连接

- [[mitochondrial-dysfunction]] — ΔΨm 消失是 PINK1 积累的触发信号；通路是对线粒体功能障碍的应答
- [[parkinsons-disease]] — PINK1 (*PARK6*) 和 Parkin (*PARK2*) 基因突变是早发性 PD 的主要常染色体隐性原因
- [[alzheimers-disease]] — AD 中 Parkin 招募受损（无基因突变）；PINK1/Parkin 水平在 AD 脑活检中异常

## 未解问题

- Q-mito-02（高优先级）：PINK1/Parkin 通路在体内慢性压力下的活性——体内线粒体损伤速率是否足以维持通路的基础水平激活？小鼠的代偿机制是什么？
- 慢性 PARKIN 激活是否会耗竭细胞质 Parkin 池，导致质量控制反而不足（SOD1-ALS 小鼠的悖论性发现提示此可能）

## 修订历史

- 2026-09-09 · 创建 · 基于《线粒体功能障碍：神经元高能耗的代价》一文 · 初始置信度：中（机制在体外高度确立，体内证据相对较弱）

## 来源文章

- [[2026-09-09-mitochondrial-dysfunction-neurodegeneration]]

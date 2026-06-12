---
title: 补体级联（CNS中的突触功能）
slug: complement-cascade-cns
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-03
updated: 2026-10-10
revision_count: 3
dimensions: [molecular, cellular, synaptic, microcircuit, disease]
related: [microglia, synaptic-pruning, alzheimers-disease, astrocyte, autism-spectrum-disorder, myasthenia-gravis, neuromuscular-junction]
prerequisites: [synaptic-transmission, microglia]
opens_questions: [Q-complement-01, Q-complement-02]
source_articles: [2026-06-03-microglia-synaptic-pruning, 2026-08-07-synaptic-pruning-complement-autism-schizophrenia]
key_sources: ["PMID:18083105", "PMID:22632727", "PMID:22715882", "PMID:27033548", "PMID:34738335", "PMID:32661396", "PMID:26814963", "PMC12110157", "PMID:32547535"]
---

# 补体级联（CNS 中的突触功能）(Complement Cascade in CNS Synaptic Function)

> **一句话定义**：经典补体级联（C1q→C4→C3b）在 CNS 中被神经元和星形胶质细胞-神经元轴挪用为突触剪枝的分子标记系统：发育期在弱突触上沉积 C3b，微胶质细胞通过 CR3 识别并吞噬；在阿尔茨海默病中被 Aβ 低聚体病理性重激活，导致斑块出现前的早期突触丢失。

## 当前理解

我们现在认为，补体系统——免疫系统的一套古老级联酶促反应——在 CNS 中有一个迄今未被完全认识的非免疫功能：充当突触剪枝的分子标记系统。补体蛋白 C1q 由发育期神经元（受星形胶质细胞 TGF-β 上调）产生，在出生后关键期突触上积累，启动 C3b 的级联生成和沉积。沉积了 C3b 的突触被小胶质细胞通过 CR3 识别和吞噬，从而被从回路中删除。

这套机制与神经活动耦合：活跃突触上的"别吃我"信号（CD47）抑制吞噬，而沉默突触则积累 C3b 而未被 CD47 保护，优先被吞噬。发育结束后，CNS 中的补体活性大幅下降；但在神经退行性疾病（AD 等）和可能的精神分裂症青春期加速剪枝期，补体可被病理信号重新激活。

## 关键机制

### 经典补体通路（CNS 中的发育版本）

**信号来源（CNS 特异）**：
- C1q：发育期神经元自身产生（非外周血液来源）
- 星形胶质细胞 → 分泌 TGF-β → 上调邻近神经元的 C1q 表达
- 这构成了星形胶质细胞→神经元→补体→微胶质的跨细胞信号轴

**C1q 启动**：
1. C1q 结合突触膜上的配体（具体配体在 CNS 中仍不完全清楚）
2. C1q 构象改变 → 激活 C1r→C1s 蛋白酶
3. C1s 裂解 C4 → C4b（沉积于膜表面）和 C4a（游离）
4. C4b 结合 C2 → C3 转化酶（C4bC2a）

**C3b 形成（调理素化）**：
5. C3 转化酶裂解 C3 → C3a（促炎，游离）+ C3b（调理素，共价结合膜）
6. C3b 与膜表面共价结合，形成稳定的突触标记
7. C3b 可进一步形成替代途径 C3 转化酶（C3bBb），放大信号

**微胶质识别与吞噬**：
8. 微胶质 CR3（αM/CD11b-CD18 异二聚体）识别 C3b（特别是 iC3b）
9. CR3 激活下游吞噬信号
10. 吞噬体形成，包裹突触末梢，与溶酶体融合降解

### 活动依赖调节（与 CD47 和 SRPX2 的三方博弈）

**"别吃我"信号（保护活跃突触）**：
- **CD47-SIRPα 轴**：活跃突触高表达 CD47 → 与小胶质 SIRPα 结合 → SHP-1/SHP-2 抑制吞噬体形成（PMID:30308165）
- **SRPX2**（2020 新增）：神经元分泌，直接结合 C1q，阻止 C2 裂解，截断源头。优先保护 VGluT2+ 谷氨酸能突触（PMID:32661396）

**"吃我"信号（弱突触自我暴露）**：
- C3b 沉积（主通道）
- PS 外翻（LTD/caspase-3 后，作用于 TREM2/MERTK）

注：V1 皮层的眼势力优势可塑性**不依赖** C1q 或 CX3CR1，说明不同脑区可能存在替代通路，补体-CR3 并非所有关键期修剪的普遍机制。

### 发育期与成年期的表达差异

| 时期 | C1q/C3 水平 | 功能状态 |
|------|------------|---------|
| 胚胎期 | 低 | 不参与突触功能 |
| 出生后关键期（P2–P21，鼠） | 高（突触局部） | 主动剪枝 |
| 成年正常期 | 低（但可检测） | 低水平维护？尚不清楚 |
| AD 等疾病 | 病理性升高（突触局部） | 过度标记→过度剪枝 |

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| C1q 在发育期 CNS 突触上定位 | 免疫组化：C1q 与突触蛋白共定位；P5 峰值后下降 | PMID:18083105 | 高 |
| C1q/C3 缺失导致剪枝失败 | C1QA−/−、C3−/− 小鼠：dLGN 眼特异性分离失败 | PMID:18083105 | 高 |
| 星形胶质细胞 TGF-β 诱导 C1q 表达 | 培养实验：去除星形胶质细胞条件培养基降低 C1q | PMID:22715882 | 中 |
| 成年 AD 脑中 C1q 在突触重激活 | STED 超分辨：C1q 与 PSD95 共定位，1 月龄 AD 小鼠↑ | PMID:27033548 | 高 |
| C4（补体中间步骤）与精神分裂症相关 | 遗传研究 N=64,000+；C4A 拷贝数↑ → 风险↑ | PMID:26814963 | 高 |

### 补体在外周 NMJ 的作用（与 CNS 剪枝的对比）

以下是同一套经典补体通路在 NMJ（外周）的病理性激活，与 CNS 突触剪枝（发育性）形成重要对比：

| 维度 | CNS 突触剪枝（发育性） | NMJ-MG（病理性） |
|------|---------------------|----------------|
| 启动信号 | 神经元自产 C1q + 星形胶质细胞 TGF-β | 自身 IgG1/IgG3 抗 AChR 抗体六聚体 |
| C1q 来源 | 神经元内源性 | 血清来源，通过 Fc 区结合 IgG 复合体 |
| 终点效应 | C3b 调理突触 → 微胶质 CR3 吞噬 | MAC（C5b-9）穿孔终板膜 |
| 功能角色 | 生理性回路精修（弱突触删除） | 病理性突触破坏（AChR 丢失） |
| 干预靶点 | 无（正常发育需要） | C5（eculizumab/ravulizumab）|

关键认识：补体并非"坏的"系统，而是**语境依赖的双刃剑**：在 CNS 发育期用于精确剪枝，在 NMJ 被自身抗体激活时则造成病理破坏。这也解释了为何补体抑制剂（eculizumab）不用于正常儿童大脑发育——因为那样会干扰正常的突触精修（PMC12110157）。

## 连接

- [[microglia]] — CR3 的表达细胞，补体标记的识别和执行者
- [[synaptic-pruning]] — 补体-CR3 通路是突触剪枝的核心机制
- [[astrocyte]] — TGF-β 来源，上调神经元 C1q 表达
- [[alzheimers-disease]] — Aβ 低聚体触发 C1q 病理性重激活
- [[autism-spectrum-disorder]] — CD47 感知障碍导致修剪不足（与精神分裂症 C4A 过激活形成互补）
- [[myasthenia-gravis]] — 外周 NMJ 的病理性 MAC 形成（最成功的补体抑制剂治疗靶点之一）
- [[neuromuscular-junction]] — MAC 穿孔终板膜的物理底物

## 未解问题

- Q-complement-01（高优先）：CNS 中 C1q 结合突触膜的具体配体是什么？为何弱突触积累更多 C1q？是 C1q 直接检测活动，还是通过抗体样分子间接识别？
- Q-complement-02（中优先）：SRPX2 抑制 C1q 只保护 VGluT2+ 突触的机制是什么？是 SRPX2 在谷氨酸能终末优先表达，还是 C1q 在这些突触的配体差异？这种不对称性是否对 E/I 平衡的最终比例有决定性影响？

## 修订历史

- 2026-06-03 · 创建 · 基于《大脑的"质检员"》(#70) · 初始置信度：高
- 2026-08-07 · 修订 · 基于《大脑的删除艺术》(#106) · 新增 SRPX2 机制；活动依赖调节小节扩充为"三方博弈"框架；注记 V1 皮层 ODP 不依赖补体的异质性；添加 Q-complement-02
- 2026-10-10 · 修订 · 基于《当免疫系统发动叛乱》(#170) · 新增"补体在外周 NMJ 的作用"小节，建立 CNS 发育性剪枝 vs NMJ 病理性 MAC 穿孔的对比框架；新增 [[myasthenia-gravis]] 和 [[neuromuscular-junction]] 连接；补充 key_sources

## 来源文章

- [[2026-06-03-microglia-synaptic-pruning]]
- [[2026-08-07-synaptic-pruning-complement-autism-schizophrenia]]
- [[2026-10-10-myasthenia-gravis-nmj-immune-attack]]

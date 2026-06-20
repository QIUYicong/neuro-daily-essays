---
title: 中枢敏化（Central Sensitization）
slug: central-sensitization
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-02
updated: 2026-08-02
revision_count: 1
dimensions: [molecular, cellular, synaptic]
related: [gate-control-theory, nociceptor, nmda-receptor, pain-matrix, spinal-dorsal-horn, periaqueductal-gray]
prerequisites: [nmda-receptor, long-term-potentiation, inhibitory-interneurons]
opens_questions: [Q-pain-04]
source_articles: [2026-08-02-pain-nociception-spinal-dorsal-horn-acc]
key_sources: ["PMID:19837031", "PMID:28961064"]
---

# 中枢敏化（Central Sensitization）

> **一句话定义**：持续性伤害性传入在脊髓背角（及更高级中枢）诱发的突触效能持久增强——其分子机制与海马 LTP 高度同源，但发生在"错误的地方"，是急性疼痛转变为慢性疼痛的核心神经可塑性机制。

## 当前理解

中枢敏化（central sensitization）是慢性疼痛区别于急性保护性疼痛的关键病理学转折点。在外周伤害感受器持续激活（炎症、神经损伤）后，脊髓背角的突触连接发生类似 LTP 的可塑性变化，导致：

1. **痛觉过敏（Hyperalgesia）**：对有害刺激的反应增强
2. **触诱发痛（Allodynia）**：低阈值触觉刺激（Aβ 纤维）激活痛觉通路
3. **自发痛（Spontaneous Pain）**：无外周刺激时仍持续疼痛

Basbaum et al.（2009, Cell, PMID:19837031）的综述确认：中枢敏化的分子基础与海马 LTP 使用相同的信号级联，核心差异在于它在脊髓背角的"异位"表达——学习记忆的机制被"错误地"用于持续编码损伤状态。

## 关键机制

### 机制一：NMDA 受体依赖的突触增强

**触发条件**：强烈或持续的 C 纤维输入（炎症、神经损伤）

```
强烈 C 纤维输入
    ↓
突触前末梢大量释放：谷氨酸 + P 物质（SP）+ CGRP + ATP
    ↓
AMPA 受体激活 → 膜去极化
    ↓ (去极化充分时)
NMDA 受体 Mg²⁺ 解阻断 → Ca²⁺ 大量内流
    ↓
激活多条激酶级联：
  - MAPK（ERK）→ 突触后受体磷酸化
  - PKC → AMPA 受体表面表达增加
  - PKA → cAMP → CREB → 基因表达改变
  - PI3K → Akt → 存活/可塑性信号
  - Src 激酶 → NMDA 受体 NR2B 磷酸化（增强 Ca²⁺ 内流）
    ↓
突触效能持久增强（Wind-up / LTP-like）→ 中枢敏化建立
```

**"Wind-up" 现象**：重复低频 C 纤维刺激下，投射神经元的放电频率逐步递增——这是中枢敏化建立过程的实时体现。

### 机制二：KCC2 下调与 GABA 功能翻转

这是中枢敏化最具临床意义的机制之一：正常起抑制作用的 GABA 能突触转变为兴奋性输入。

**正常状态**：
- KCC2（K⁺/Cl⁻ 共转运体）向外泵出 Cl⁻ → 细胞内 [Cl⁻] 低
- GABA-A 受体激活 → Cl⁻ 内流 → 超极化（抑制）

**损伤后**：
- 神经损伤 → 脊髓小胶质细胞激活（P2X4/P2X7/P2Y12 受体感知 ATP）
- 激活的小胶质细胞释放 BDNF
- BDNF → TrkB → 磷酸化下调 KCC2
- KCC2 减少 → 细胞内 [Cl⁻] 积累
- GABA-A 受体激活 → Cl⁻ 外流 → **去极化（兴奋！）**
- 原本的抑制性闸门转化为兴奋性输入 → 持续正反馈

**小胶质细胞-BDNF-KCC2 恶性循环**：
```
神经损伤 → 小胶质细胞激活（P2X4）→ BDNF ↑ → TrkB → KCC2 ↓
    ↑                                                      ↓
持续激活 ←←←←←←←← 更多神经活动 ←←←←← GABA 变兴奋
```

### 机制三：脊髓背角兴奋/抑制失衡

除 KCC2 机制外，中枢敏化还涉及：
- **抑制性中间神经元丧失**：神经损伤后 GABAergic/甘氨酸能神经元的选择性凋亡（excitotoxicity）
- **下行易化增强**：PAG-RVM 的 ON-cells 在慢性疼痛状态过度激活，提供持续下行兴奋
- **星形胶质细胞贡献**：谷氨酸再摄取减少 → 突触外谷氨酸积累 → NMDA 受体持续激活（特别是 extrasynaptic NR2B 亚型）

## 与海马 LTP 的比较

| 特征 | 海马 LTP（记忆） | 脊髓 LTP（中枢敏化） |
|------|----------------|-------------------|
| 触发 | 高频突触刺激 | 持续 C 纤维活动 |
| 核心机制 | NMDA Ca²⁺ → AMPA 增加 | 同上 |
| 关键激酶 | CaMKII, PKC, MAPK | PKC, PKA, Src, MAPK |
| 基因表达 | CREB → c-fos, BDNF | c-fos, COX-2, 电压门控通道 |
| 功能 | 适应性（学习） | 病理性（慢性痛） |
| 持续时间 | 小时到终生 | 小时到月/年 |

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| NMDA 阻断剂抑制 wind-up | AP5 脊髓注射 + 电生理 | PMID:19837031 | 高 |
| 神经损伤→ KCC2 下调→ GABA 变兴奋 | 脊髓切片 Cl⁻ 成像 + 电生理 | PMID:19837031 | 高 |
| 小胶质细胞 BDNF → TrkB → KCC2 下调 | BDNF 注射 + TrkB 拮抗剂 | PMID:19837031 | 高（啮齿类） |
| 脊髓 ERK 激活与痛觉过敏同步 | 磷酸化 ERK 免疫染色 + 行为 | PMID:19837031 | 高 |
| 抑制 PKCγ+ 神经元减轻触诱发痛 | 光遗传抑制 + 神经损伤模型 | PMID:28961064 | 高（啮齿类） |

## 临床相关性

中枢敏化理论直接解释多种临床现象：

- **纤维肌痛综合征（Fibromyalgia）**：广泛性慢性疼痛，外周无明显组织损伤，中枢敏化是主要机制
- **慢性腰背痛**：初始损伤愈合后中枢敏化持续存在
- **手术后慢性疼痛**：术前短暂 NMDA 阻断（氯胺酮）可降低术后慢性痛发生率——为这一机制提供临床支持
- **阿片诱导的痛觉过敏（OIH）**：长期阿片使用反而增强中枢敏化

## 连接

- [[gate-control-theory]] — 中枢敏化的前级：闸门功能正常是防止中枢敏化的第一道防线
- [[nmda-receptor]] — 中枢敏化的分子核心
- [[nociceptor]] — 持续激活的外周输入是中枢敏化的触发源
- [[pain-matrix]] — 中枢敏化最终影响大脑处理疼痛的方式
- [[periaqueductal-gray]] — 下行系统在慢性疼痛状态从镇痛转为易化

## 未解问题

- **Q-pain-04**（高优先级）：中枢敏化建立后有无"窗口期"干预可完全逆转？慢性疼痛的中枢可塑性变化（如 KCC2 下调、抑制性神经元丧失）有多大比例是可逆的？基于 NMDA 阻断或 TrkB 拮抗的药理干预窗口期有多长？

## 修订历史

- 2026-08-02 · 创建 · 基于《痛觉的守门人》文章（#101）

## 来源文章

- [[2026-08-02-pain-nociception-spinal-dorsal-horn-acc]]

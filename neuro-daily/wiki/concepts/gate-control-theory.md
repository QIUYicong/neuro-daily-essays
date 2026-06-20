---
title: 闸门控制理论（Gate Control Theory）
slug: gate-control-theory
domain: concepts
type: theory
status: mainstream
confidence: high
created: 2026-08-02
updated: 2026-08-02
revision_count: 1
dimensions: [cellular, synaptic, microcircuit]
related: [nociceptor, central-sensitization, spinal-dorsal-horn, pain-matrix, periaqueductal-gray]
prerequisites: [nociceptor, inhibitory-interneurons]
opens_questions: [Q-pain-03]
source_articles: [2026-08-02-pain-nociception-spinal-dorsal-horn-acc]
key_sources: ["PMID:28961064", "PMID:19837031"]
---

# 闸门控制理论（Gate Control Theory）

> **一句话定义**：Melzack & Wall 1965 提出的脊髓痛觉调控框架：伤害性传入在脊髓背角经由抑制性中间神经元（"闸门"）调控，闸门开闭决定痛信号是否上传至大脑——现代神经科学已在分子细胞层面确认并扩展了这一回路。

## 当前理解

Melzack 和 Wall 在 1965 年提出闸门控制理论，一举革新了疼痛研究范式：痛觉不是外周→大脑的简单电线传递，而是在脊髓背角经过一套"闸门"（gate）调控。闸门打开，痛信号上传；闸门关闭，痛信号被抑制。

这一理论预测了：(1) 脊髓有抑制性中间神经元负责门控；(2) 低阈值触觉纤维（Aβ）可以激活这些抑制性神经元，进而抑制痛觉传入（这解释了为什么揉搓受伤部位可以减痛）；(3) 下行脑干信号也可以调控脊髓闸门。

50 年后，Koch, Acton & Goulding（2018, Annual Review of Physiology, PMID:28961064, PMCID:PMC5891508）在分子细胞层面验证并详细描述了这些预测：

**分子定义的闸门参与者**：
- **DYN+（强啡肽+）抑制性中间神经元**：接收 Aβ 单突触传入，通过 GABA/甘氨酸抑制阻止触觉进入痛觉通路。消融→触诱发痛（allodynia）——轻触变成痛
- **Ret+ 抑制性中间神经元**：通过突触前和突触后双重机制抑制 Aβ 和 C 纤维传入
- **PKCγ+ 兴奋性中间神经元**（"被闸门压制的信号放大器"）：正常被抑制性神经元压制；神经损伤后去抑制→allodynia 的关键节点
- **SOM+（生长抑素+）兴奋性中间神经元**：传递急性机械痛和慢性 Aβ 多突触输入

## 关键机制

### 正常状态（闸门关闭）

```
Aβ 触觉纤维 ──→ DYN+ 抑制性神经元 ──→ 抑制 PKCγ+ → 阻止 → 投射神经元
C/Aδ 伤害性纤维 ──→ 板层Ⅰ投射神经元 (被监管) → 受抑制
                              ↑ 同时被 DYN+ 直接抑制
结果：轻触不产生痛；伤害性刺激在阈值以上产生痛
```

### 病理状态（闸门失控 → Allodynia）

神经损伤或炎症破坏闸门的两条路径：

**路径 A — KCC2 下调（氯离子梯度翻转）**：
神经损伤 → KCC2（K⁺/Cl⁻ 共转运体）表达减少 → 神经元内 [Cl⁻] 升高 → GABA-A 受体激活产生去极化（而非超极化）→ 原本的"闸门"变成"促进器"

**路径 B — 小胶质细胞-BDNF 正反馈**：
神经损伤 → 小胶质细胞激活（P2X4 受体，ATP）→ BDNF 释放 → TrkB 激活 → KCC2 进一步下调 → 恶性循环

→ 最终：Aβ 触觉纤维绕过失效的闸门，通过 PKCγ+ 兴奋性神经元激活痛觉投射通路 → 轻触 = 痛（触诱发痛）

### 下行调控（顶下闸门信号）

脊髓闸门不是孤立的——大脑可以通过 PAG-RVM 下行系统实时调控脊髓闸门的"开闭状态"：
- PAG-RVM → 脊髓背角释放 NE/5-HT → 增强抑制性中间神经元活动 → 关闸（镇痛）
- 应激、注意力集中、内源性阿片激活 → 下行镇痛 → 闸门关闭

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|-----------|------|--------|
| DYN+ 神经元消融 → 触诱发痛 | 条件性消融小鼠 + von Frey 行为 | PMID:28961064 | 高（鼠类） |
| PKCγ+ 兴奋性神经元是 allodynia 关键节点 | 光遗传激活 + 神经损伤模型 | PMID:28961064 | 高（鼠类） |
| KCC2 下调 → GABA 由抑制变兴奋 | 脊髓切片 Cl⁻ 成像 + 电生理 | PMID:19837031 | 高 |
| 小胶质细胞 BDNF → KCC2 下调 | BDNF 注射 + TrkB 拮抗剂实验 | PMID:19837031 | 高（啮齿类） |
| 揉搓减痛（临床经验符合理论） | 人类现象学 + Aβ 纤维激活实验 | 经典文献 | 中（机制间接） |

## 比较视角：Melzack-Wall 原始模型 vs 现代分子修订

| 维度 | 1965 年原始模型 | 现代分子回路（Koch 2018） |
|------|---------------|--------------------------|
| 闸门细胞类型 | 抽象的"T细胞"和"SG细胞" | 分子定义：DYN+/Ret+（抑制）/ PKCγ+/SOM+（兴奋） |
| Aβ 的角色 | 激活 SG 细胞→抑制 T 细胞 | Aβ→DYN+ 单突触→抑制 PKCγ+ |
| 下行控制 | "中枢控制扳机" | PAG-RVM-脊髓 NE/5-HT 下行通路 |
| 闸门失控机制 | 未细化 | KCC2 下调 + 小胶质细胞 BDNF |

## 连接

- [[nociceptor]] — 进入脊髓的伤害性信号
- [[central-sensitization]] — 闸门失控后脊髓兴奋性持久增强的后续
- [[periaqueductal-gray]] — 提供下行镇痛信号的上级中心
- [[pain-matrix]] — 通过脊髓闸门的信号到达大脑的整合区域

## 未解问题

- **Q-pain-03**（中优先级）：Melzack-Wall 理论中的"T细胞"（投射神经元）具体对应板层 Ⅰ 的哪些分子亚型？NK1R+投射神经元是否是"T细胞"的现代版本？消融 NK1R+ 神经元是否完全复现切断 STT 的镇痛效果？

## 修订历史

- 2026-08-02 · 创建 · 基于《痛觉的守门人》文章（#101）

## 来源文章

- [[2026-08-02-pain-nociception-spinal-dorsal-horn-acc]]

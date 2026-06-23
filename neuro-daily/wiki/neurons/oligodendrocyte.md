---
title: 少突胶质细胞
slug: oligodendrocyte
domain: neurons
type: entity
status: established
confidence: high
created: 2026-09-07
updated: 2026-09-07
revision_count: 1
dimensions: [cellular, molecular, synaptic, microcircuit]
related: [myelination, activity-dependent-myelination, action-potential, axon-initial-segment, bdnf, microglia, synaptic-transmission]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: [Q-myelin-01, Q-myelin-02, Q-myelin-04]
source_articles: [2026-09-07-activity-dependent-myelination-white-matter-plasticity]
key_sources: ["PMID:26585800", "PMID:28817797", "PMID:32094969", "PMID:24727982"]
---

# 少突胶质细胞 (Oligodendrocyte)

> **一句话定义**：少突胶质细胞是中枢神经系统特有的胶质细胞，通过将自身细胞膜反复缠绕轴突，形成髓鞘节段，使动作电位以跳跃传导方式高速传播；其前体细胞（OPC）终身存在并监听神经元放电，主动参与活动依赖性的白质可塑性。

## 当前理解

少突胶质细胞是中枢神经系统（CNS）的髓鞘形成细胞，相当于外周神经系统的施旺细胞（Schwann cell）。每个成熟少突胶质细胞可同时包裹多达 40–50 条不同轴突节段，形成髓鞘。

**细胞谱系**：
1. **OPC（少突胶质前体细胞）**：又称 NG2 细胞，终身存在于成年脑中（约占胶质细胞 5–8%），保持增殖和分化能力
2. **未成熟少突胶质细胞（immature OL）**：OPC 分化后延伸突起，探索轴突，决定是否包裹
3. **成熟少突胶质细胞（mature OL）**：完成髓鞘包裹，进入相对静止状态，同时提供代谢支持

**功能双重性**：
- **绝缘功能**：髓鞘将轴突的膜电容隔绝，使电流只能在郎飞结处进出，实现跳跃传导（有髓 50–200 m/s vs 无髓 <2 m/s）
- **代谢支持功能**：通过内侧髓鞘层向轴突输送乳酸（通过 MCT1 转运体），支持轴突的高能量需求（Fields 2015, PMID:26585800）

## 关键机制

### OPC 的神经活动感受

OPC 与轴突之间存在突触样连接，可记录到小型兴奋性突触后电流（mEPSC），具有：
- 突触囊泡（轴突侧）：含谷氨酸，依赖轴突放电频率释放
- 突触后密度（OPC 侧）：AMPA 受体、NMDA 受体

这意味着 OPC 以突触精度"监听"单个轴突的放电历史，使髓鞘化可以是轴突特异的。

### OPC→成熟少突胶质细胞的分化通路

主要信号：谷氨酸 → Ca²⁺ → FYN 激酶 → MBP 局部合成；ATP → 腺苷 → A1R → cAMP-PKA → 分化；BDNF → TrkB（OPC 上） → 髓鞘基因表达；NRG1 → ErbB → 髓鞘厚度调节。

转录因子 **Mrf/Myrf** 是分化的关键闸门：Mrf 条件敲除完全阻断髓鞘化，导致运动技能学习障碍（de Faria et al. 2017, PMID:28817797）。

### 代谢轴：小胶质细胞 → BDNF → OPC

小胶质细胞通过分泌 BDNF 支持 OPC 的髓鞘可塑性。炎症（化疗、感染、衰老）→ 小胶质细胞过激活 → BDNF 分泌受抑 → 髓鞘可塑性下降 → 认知缺陷（2023 Nat Rev Neurosci, PMID:37857838）。

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| OPC 与轴突形成突触样连接 | 全细胞记录到 mEPSC；电镜可见突触样形态 | Fields 2015 综述引用 Bergles et al. (PMID:26585800) | 高（多实验室复现） |
| 少突胶质细胞提供轴突代谢支持 | MCT1 KO 轴突退化而不失髓鞘 | Fields 2015 综述 (PMID:26585800) | 高 |
| Mrf KO 阻断运动学习 | Mrf 条件 KO 小鼠转轮运动学习完全受损 | de Faria et al. 2017, Neuron (PMID:28817797) | 高（因果） |
| 光遗传激活→OPC 增殖 | 运动前皮层光遗传刺激 8 周，胼胝体 OPC +60% | Gibson et al. 2014, Science (PMID:24727982) | 高（因果） |

## 连接

- [[myelination]] — 少突胶质细胞的主要功能产物；二者关系为 entity-produces
- [[activity-dependent-myelination]] — 少突胶质细胞参与的关键可塑性机制
- [[action-potential]] — 轴突动作电位是招募 OPC 的触发信号
- [[bdnf]] — BDNF-TrkB 是 OPC 分化和髓鞘可塑性的必要分子途径
- [[microglia]] — 小胶质细胞通过 BDNF 调控少突胶质细胞功能
- [[axon-initial-segment]] — 轴突结构相关节点

## 未解问题

- **Q-myelin-01**：绝缘功能 vs 代谢支持功能，哪个是活动依赖性招募的主要驱动力？
- **Q-myelin-02**：人脑 DTI 观察到的"2h 白质变化"究竟对应 OPC 分化的哪个阶段？
- **Q-myelin-04**：促 OPC 分化药物（clemastine 等）在人类临床的实际效果如何？

## 修订历史

- 2026-09-07 · 创建 · 基于《白质的秘密语言》(#124) · status: established，高置信度；覆盖 OPC 谱系、突触样接触、分化机制、代谢支持

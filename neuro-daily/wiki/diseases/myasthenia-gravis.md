---
title: 重症肌无力
slug: myasthenia-gravis
domain: diseases
type: disease
status: established
confidence: high
created: 2026-10-10
updated: 2026-10-10
revision_count: 1
dimensions: [molecular, synaptic, cellular, behavior, disease]
related: [neuromuscular-junction, agrin-musk-achr-clustering, complement-cascade-cns, alpha-motor-neuron, end-plate-potential-safety-factor, lambert-eaton-syndrome]
prerequisites: [neuromuscular-junction, agrin-musk-achr-clustering, synaptic-transmission, complement-cascade-cns]
opens_questions: [Q-mg-01, Q-mg-02, Q-mg-03]
source_articles: [2026-10-10-myasthenia-gravis-nmj-immune-attack]
key_sources: ["PMID:32547535", "PMID:38494283", "PMID:39105625", "PMID:35065039", "PMID:36074148", "PMID:35869073", "PMC12110157"]
---

# 重症肌无力 (Myasthenia Gravis, MG)

> **一句话定义**：由自身抗体介导的神经肌肉接头功能性疾病，通过补体激活/受体内吞（AChR-MG）或 IgG4 信号阻断（MuSK-MG）两条路径侵蚀 NMJ 安全因子，导致波动性、疲劳性骨骼肌无力。

## 当前理解

我们现在认为，MG 不是单一疾病，而是**至少两种机制截然不同的神经肌肉接头自身免疫病**，共同表现为疲劳性肌无力，但在分子层面、治疗靶点和预后上都存在显著差异。

**AChR 抗体型（80–85%）**：IgG1/IgG3 类自身抗体通过三条协同路径攻击突触后 AChR：①直接阻断 ACh 结合位点；②交联 AChR 诱发加速内吞和降解；③激活经典补体途径，形成膜攻击复合物（MAC），物理破坏终板膜的接头折叠结构。补体激活不由单个抗体克隆完成，而需要靶向不同 AChR 亚基表位的抗体协同在细胞膜上形成六聚体平台，因此血清抗体滴度与病情严重度相关性较弱（PMID:36074148）。

**MuSK 抗体型（5–8%）**：主要由 IgG4 亚类抗体介导，该亚类因铰链区 Ser228 而非 Cys228 导致 Fab-arm exchange，形成功能单价抗体。单价 IgG4 直接阻断 LRP4-MuSK 相互作用界面，抑制 Agrin 触发的 MuSK 磷酸化级联，导致 AChR 聚集维护失败。此途径**不激活补体**，因此补体抑制剂对 MuSK-MG 无效（PMID:32547535）。

胸腺在 AChR-MG 的发病中扮演"自身免疫反应堆"角色：约 70% 早发型（女性 <50 岁）患者存在胸腺滤泡性增生，胸腺髓质上皮细胞（mTECs）异常表达神经肌肉基因（包括 AChR 亚基序列），为自反应性 T/B 细胞的逃逸和激活提供了抗原呈递环境（PMID:35869073）。

## 关键机制

### AChR-MG 三条攻击路径

**路径 1 — 受体阻断**：
- IgG 结合 AChR 主要免疫原区（Main Immunogenic Region, MIR，α1 亚基 N 端）
- 空间阻断 ACh 接触受体
- 单独阻断效果较弱，需与其他路径协同

**路径 2 — 抗原调变（加速内吞）**：
- 二价 IgG1/IgG3 交联相邻 AChR → 受体聚集 → 网格蛋白依赖内吞
- NMJ AChR 半寿期从正常约 8–11 天缩短
- 最慢但最稳定的长期侵蚀

**路径 3 — 补体激活 → MAC 穿孔**（最具破坏力）：
```
IgG1/IgG3 抗体在 AChR 表面形成六聚体 → C1q 结合
→ C1r/C1s 激活 → C4 裂解 → C3 转化酶（C4bC2a）
→ C3b 共价结合膜面（调理素化）→ C5 转化酶
→ C5 裂解 → C5b → 招募 C6-C9 → MAC（C5b-9）
→ 终板膜穿孔 → 接头折叠破坏 → AChR + rapsyn 丢失
```

### MuSK-MG IgG4 机制

**Fab-arm exchange（FAE）**：
- IgG4 铰链区 Ser228（非 IgG1/2/3 的 Cys228）→ 无铰链间二硫键
- 生理温度 + 还原环境下两条重链解离→与其他 IgG4 半分子重组
- 产物：双特异性、功能单价（monovalent）抗体

**功能单价阻断 MuSK**：
- 靶向 MuSK Ig1 域（LRP4 结合界面）
- 单价 → 不交联 MuSK 分子 → 不激活补体 → 不触发 AChR 内吞
- 但高效阻断 Agrin-LRP4-MuSK 信号级联
- MuSK 磷酸化↓ → Dok7 协激活↓ → rapsyn 锚定失效 → AChR 聚集缓慢解体

### NMJ 安全因子的侵蚀动力学

正常 NMJ：安全因子 2–5（EPP ~30–40 mV，阈值 ~15–20 mV）。

MG 进展中，随 AChR 密度下降：
1. 安全因子从 2–5 降低，但高频刺激期间（囊泡释放减少）安全因子暂时低于阈值
   → 临床表现：运动后疲劳加重、晨轻暮重
2. 进一步下降时，静息状态安全因子 <1
   → 持续性肌无力

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| MAC（C3/C9）沉积于 MG 患者 NMJ | 免疫组化：患者活检 NMJ 检出 C3/C9 | PMC12110157 | 高 |
| 补体抑制剂（eculizumab）改善 AChR-MG | REGAIN RCT (n=125)：MG-ADL 改善，获益持续 130 周 | PMC12110157 | 高 |
| 单 AChR 单抗激活补体能力弱；混合抗体协同激活 | 体外补体激活测定 + 大鼠被动转移模型 | PMID:36074148 | 高 |
| IgG4 Fab-arm exchange（FAE）体内发生 | 生理条件下 IgG4 双特异性混合体的质谱检测 | PMID:32547535 | 高 |
| 胸腺瘤 mTEC 异常表达神经肌肉基因 | 单细胞 RNA 测序 + 空间转录组 | PMID:35869073, PMID:39180749 | 中-高 |
| 胸腺切除术改善 AChR-MG（MGTX 试验） | RCT 3 年随访：缓解率、免疫抑制剂量优于对照 | PMID:26980901（Wolfe 2016，未直接读取） | 高 |
| 利妥昔单抗对 MuSK-MG 显著有效（vs AChR-MG 部分有效） | 系列病例 + 回顾性队列 | PMID:32547535 综述整理 | 中（缺乏大规模 RCT） |
| FcRn 抑制剂（efgartigimod）改善 AChR-MG | ADAPT 试验：AChR+ 组约 68% 达临床改善 | PMID:38724842 | 高 |

## 亚型对比

| 维度 | AChR-MG (80%) | MuSK-MG (5–8%) | 血清阴性 (~10%) |
|------|---------------|----------------|----------------|
| 主要 IgG 亚类 | IgG1/IgG3 | IgG4 | 未知/混合 |
| 补体激活 | 是（核心） | 否 | 不确定 |
| AChR 内吞 | 是 | 否 | 部分 |
| 直接信号阻断 | 间接（AChR 阻断） | 是（MuSK-LRP4） | 不确定 |
| 胸腺异常 | 常见（增生/胸腺瘤） | 正常 | 不确定 |
| 主要受累肌群 | 眼肌→全身 | 球部/面肌/颈肌 | 多样 |
| 乙酰胆碱酯酶抑制剂 | 有效 | 慎用/避免 | 多样 |
| 补体抑制剂 | 有效（FDA 批准） | 无效 | 不适用 |
| 利妥昔单抗（抗 CD20） | 部分有效 | 极佳 | 待定 |
| FcRn 拮抗剂 | 有效 | 有效（全 IgG 降低） | 部分有效 |

## 连接

- [[neuromuscular-junction]] — MG 直接攻击 NMJ 突触后膜
- [[agrin-musk-achr-clustering]] — MuSK-MG 的分子靶点
- [[complement-cascade-cns]] — AChR-MG 的核心损伤机制（外周 NMJ 补体 vs CNS 突触剪枝补体）
- [[alpha-motor-neuron]] — 运动指令通过 NMJ 传至肌纤维
- [[end-plate-potential-safety-factor]] — MG 的功能后果是安全因子侵蚀
- [[lambert-eaton-syndrome]] — 突触前 VGCC 抗体型 NMJ 疾病，与 MG 互补

## 未解问题

- Q-mg-01（高优先）：血清阴性 MG（约 10%）的致病抗体/机制是什么？是否存在细胞免疫（T 细胞直接损伤）而非抗体依赖的亚型？
- Q-mg-02（中优先）：AChR 抗体的"协同激活补体"要求哪些最小表位组合？是否存在"主导致病性克隆"？为何血清滴度与严重程度相关性弱？
- Q-mg-03（中优先）：MuSK-MG 中 IgG4 如何打破正常 B 细胞耐受？Treg 的特异性失调模式是什么？

## 修订历史

- 2026-10-10 · 创建 · 基于《当免疫系统发动叛乱》（#170）· 填补 neuromuscular-junction 页中的悬空引用 [[myasthenia-gravis]] · 初始置信度：高

## 来源文章

- [[2026-10-10-myasthenia-gravis-nmj-immune-attack]]

---
title: 突触素（Synapsin）
slug: synapsin
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-09-12
updated: 2026-09-12
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [liquid-liquid-phase-separation, synaptic-transmission, active-zone, voltage-gated-calcium-channels, camkii, readily-releasable-pool]
prerequisites: [synaptic-transmission, action-potential]
opens_questions: [Q-synapsin-01]
source_articles: [2026-09-12-liquid-liquid-phase-separation-postsynaptic-density]
key_sources: ["PMID:29976799"]
---

# 突触素（Synapsin）

> **一句话定义**：突触前终末的支架蛋白家族（Synapsin 1/2/3），通过 C 末端内禀无序区（IDR）驱动液-液相分离，形成将突触小泡捕获在储备池的液态凝聚体；Ca²⁺/CaMKII 磷酸化在数秒内溶解此凝聚体，动员储备池小泡参与持续神经传递。

## 当前理解

我们现在认为，突触素是突触前终末中"小泡储备库"组织的核心分子，其机制不是传统模型中的物理"链接绳"，而是通过液-液相分离（LLPS）形成液态凝聚体，以物理化学捕获的方式聚集突触小泡（SV）。

**三种异构体**（Synapsin 1/2/3）：都含有 N 末端保守结构域（与 SV 磷脂和肌动蛋白结合）和 C 末端可变结构域（IDR，驱动 LLPS）。

**功能分工**：
- **Synapsin 1a/1b**：最丰富，与小泡磷脂和肌动蛋白双重结合，将小泡锚定于液相
- **Synapsin 2**：调节快速动员；参与抑制性突触的小泡聚集
- **Synapsin 3**：相对低丰度，功能较少了解

**突触素液相**（Milovanovic et al. 2018 Science）：

1. **相形成**：C 末端 IDR 在生理盐浓度（150 mM NaCl）下自发形成液态液滴（0.5–20 μM 浓度范围；体内浓度 >100 μM）
2. **囊泡捕获**：液相选择性捕获含带负电磷脂（PI、PS）的囊泡（50–150 nm），不捕获中性磷脂囊泡
3. **活性调节**：Ca²⁺ 激活 CaMKII → CaMKII 磷酸化突触素 IDR 上的 S2/S3 位点 → 引入负电荷破坏弱相互作用 → 液相在 τ ≈ 5.9 秒内完全溶解 → 储备池小泡被释放，向即发释放池移动

**三重敲除小鼠（TKO）**：突触素 1/2/3 全部敲除 → 突触终末内 SV 数量减少，聚集程度严重下降 → 证明突触素液相是 SV 储备库的必要条件

## 关键机制

### IDR 驱动的 LLPS

- **驱动残基**：IDR 通过电荷依赖相互作用（阳离子、π 电子）参与 LLPS；高盐（>250 mM NaCl）抑制液滴形成
- **多价增强**：SH3 结构域蛋白（intersectin-5）能与突触素 IDR 的 PXXP 基序结合，形成额外交联，增加液滴稳定性（同时减慢 FRAP 恢复速率，从 t₁/₂=65s 至 t₁/₂=3.2min）
- **液态特性**：FRAP t₁/₂ = 65 s（液滴整体交换），t₁/₂ = 40 s（局部重排）→ 确认液态而非凝胶

### 磷酸化调控

| 激酶 | 位点 | 效果 |
|------|------|------|
| CaMKII | S2, S3（IDR 内） | 液相在 ~6 s 内溶解；对 CaMKII 精确，PKC 无效 |
| PKA, MAPK | S1（N 端保守域）| 主要调节与肌动蛋白的结合，不主要影响 LLPS |

### 在传递中的功能

- **静息时**：突触素液相捕获约 80–90% 的终末 SV → 储备池
- **低频刺激**：少量 SV 从液相逃逸至活性区 → 即发释放池（RRP）
- **高频/持续刺激**：Ca²⁺ 大量涌入 → CaMKII 大量激活 → 突触素液相快速溶解 → 储备池 SV 大规模动员 → 维持持续神经递质释放

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 突触素 IDR 形成液态液滴（LLPS） | 体外 DIC 显微镜 + FRAP，IDR 截断分析 | PMID:29976799 / PMC6191856 | 高 |
| 液相选择性捕获脂质囊泡 | 荧光脂质囊泡 + 突触素液滴共定位（带电磷脂选择性）| PMID:29976799 | 高 |
| CaMKII 磷酸化在 ~6 s 内溶解液相 | 体外磷酸化时间曲线（τ=5.9 s）；PKC 阴性对照 | PMID:29976799 | 高 |
| 突触素 TKO 小鼠 SV 聚集严重减少 | 电镜定量计数（TKO vs WT） | PMID:29976799 | 高 |

## 连接

- [[liquid-liquid-phase-separation]] — 突触素液相是 LLPS 在突触前的具体实现
- [[synaptic-transmission]] — 突触素通过组织 SV 储备库影响突触传递动态学
- [[active-zone]] — 活性区是 SV 融合的最终地点，突触素液相提供 SV 库供给
- [[camkii]] — CaMKII 是突触素液相溶解的主要触发器
- [[readily-releasable-pool]] — 突触素液相溶解产生 SV 向 RRP 的动员
- [[voltage-gated-calcium-channels]] — Ca²⁺ 内流激活 CaMKII，启动液相溶解

## 未解问题

- Q-synapsin-01（中优先级）：突触素液相的组成在不同突触类型（兴奋性 vs. 抑制性）和不同脑区（海马 vs. 小脑 vs. 皮层）是否有实质差异？LLPS 的调控阈值是否随发育、疾病状态而变化？

## 修订历史

- 2026-09-12 · 创建 · 基于《突触的自组装奥秘》文章（#142）· 初始置信度：高

## 来源文章

- [[2026-09-12-liquid-liquid-phase-separation-postsynaptic-density]]

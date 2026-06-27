---
title: KIBRA（KIdney BRAin protein / WWC1）
slug: kibra
domain: concepts
type: mechanism
status: emerging
confidence: medium-high
created: 2026-06-28
updated: 2026-06-28
revision_count: 1
dimensions: [molecular, synaptic, cellular, cognition]
related: [pkm-zeta, ltp, synaptic-tagging-capture, ampa-receptor, memory-consolidation, postsynaptic-density]
prerequisites: [ltp, pkm-zeta, synaptic-tagging-capture]
opens_questions: [Q-kibra-invivo-hexamer, Q-kibra-region-specificity, Q-zstat-ptsd-potential]
source_articles: [2026-06-28-ltp-60-kibra-pkm-zeta-molecular-persistence]
key_sources: ["PMID:41814337", "PMID:42104413", "PMID:42363710"]
---

# KIBRA（KIdney BRAin protein，WWC1）

> **一句话定义**：突触后膜支架蛋白（基因名 WWC1），在 LTP 后约 2–3 小时招募至突触后致密区（PSD），与 PKMζ 形成稳定的异质六聚体寡聚体；通过"感染性磷酸化"机制，在 PKMζ 蛋白周转过程中持续传递激活状态，为远程记忆的分子持久性提供结构基础。

## 当前理解

KIBRA（KIdney BRAin protein，也称 WWC1 或 WW domain-containing protein 1）最初在肾脏研究中发现，随后在海马和皮层神经元中被识别为高表达支架蛋白。其与记忆的关联来自两个方向：

1. **遗传流行病学**：KIBRA 基因（WWC1）的特定多态性与人类空间记忆能力相关联，早期研究（Papassotiropoulos et al. 2006）发现携带 T 等位基因者情景记忆测试成绩更优。
2. **分子机制**：Hsieh & Sacktor（2026, PMID:41814337）揭示 KIBRA 与 PKMζ 共同构成 KIBRA-PKMζ 异质六聚体寡聚体，是解答 Crick 分子周转悖论的核心机制。

## 关键机制

### 一、KIBRA 作为突触标签的时间窗

LTP 诱导后：
```
LTP 诱导（0 min）
  → CaMKII 激活（秒内）+ AMPA 受体插入（分钟内）→ E-LTP
  → 蛋白质合成依赖的晚期程序（30–60 min）→ PKMζ 新合成
  → KIBRA 在 PSD 中浓度显著升高（约 2–3 h）
  → KIBRA + PKMζ 形成异质二聚体 → 进一步组装六聚体（~3 h）
```

KIBRA 的 PSD 富集时间窗（2–3 h）对应 L-LTP 的巩固窗口，提示它是突触标记与捕获（STC）框架中"晚期标签"的分子执行者之一。

### 二、KIBRA-PKMζ 寡聚体结构

AlphaFold 3 预测（Hsieh & Sacktor 2026）：

```
KIBRA + PKMζ（磷酸化）
  → 异质二聚体（heterodimer）
  │  核心界面：PKMζ R957 残基，3个氢键
  │  K-ZAP 靶向此界面（FVRNSLERRSVRMKRPS-966）
  ↓
多个二聚体 → 异质六聚体（hetero-hexamer）
  │  六聚体界面：PKMζ 柄区 P291/F297 残基
  │  ζ-stat 靶向此界面
  ↓
稳定的大分子复合物（驻留在 PSD）
```

### 三、感染性磷酸化：Crick 问题的拓扑解答

```
（稳态维持周期）
现有六聚体（含磷酸化 PKMζ × N 个）
  ↓ 单个 PKMζ A 降解（半衰期约数天）
  ↓ KIBRA 招募新合成的 PKMζ B（未磷酸化）
  ↓ PKMζ B 加入六聚体，与磷酸化邻居接触
  ↓ "感染性磷酸化"：PKMζ B 被激活
  ↓ 六聚体维持完整，激活状态传递
  → 重复直至所有分子被逐一替换
  → 激活状态（≠具体分子）无限期维持
```

这一机制的拓扑本质：**记忆存储在寡聚体的激活状态拓扑中，而非任何单一蛋白质分子中**。

## 两把干预工具

| 工具 | 靶点 | 效果 | 时间特异性 |
|------|------|------|-----------|
| **K-ZAP** | KIBRA-PKMζ 二聚体界面（R957） | 阻断异质二聚体形成 | 破坏 1 天和 1 个月记忆（所有时间点） |
| **ζ-stat** | PKMζ 柄区六聚体界面（P291/F297） | 阻断六聚体组装，不影响二聚体 | 选择性破坏 4 周以上远程记忆；不影响新近（<24h）记忆 |

**K-ZAP 在 PKMζ KO 中无效**（机制特异性关键验证）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| KIBRA 与 PKMζ 形成异质六聚体 | AlphaFold 3 预测 + 体外生化验证（免疫共沉淀、质谱） | PMID:41814337 | 中-高（部分体外） |
| K-ZAP 破坏 1 天和 1 个月空间记忆 | 大鼠海马注射 + Morris 水迷宫 | PMID:41814337 | 高 |
| K-ZAP 在 PKMζ KO 中无效 | KO 小鼠 + K-ZAP 注射 + 行为测试 | PMID:41814337 | 高 |
| ζ-stat 破坏 4 周空间记忆（不影响新近记忆） | 大鼠双侧海马注射 + 行为测试 | PMID:41814337 | 高 |
| 感染性磷酸化的概念框架 | 综合评述 + 类比朊病毒构象传播 | PMID:42104413 | 中-高（概念性） |

## 连接

- [[pkm-zeta]] — KIBRA 与 PKMζ 共同构成 KIBRA-PKMζ 寡聚体的两个核心组分；KIBRA 作为支架，PKMζ 提供激酶活性和感染性磷酸化能力
- [[ltp]] — KIBRA-PKMζ 寡聚体机制是 L-LTP 远程维持的分子基础，直接回答 Q-ltp-lifetime-mechanism（Crick 悖论）
- [[synaptic-tagging-capture]] — KIBRA 可能是 STC 框架中长效突触标签的分子执行者之一（与 CaMKII 凝聚体、PSD-95 磷酸化并列）
- [[ampa-receptor]] — KIBRA-PKMζ 寡聚体通过 PKMζ 的 GluA2 内吞抑制功能间接维持突触后 AMPA 受体密度
- [[memory-consolidation]] — KIBRA-PKMζ 六聚体机制是突触层面记忆巩固（尤其是远程巩固）的分子基础
- [[postsynaptic-density]] — KIBRA 在 LTP 后 2–3 小时在 PSD 富集，六聚体组装发生在 PSD 微环境中

## 未解问题

- Q-kibra-invivo-hexamer：AlphaFold 3 预测的 KIBRA-PKMζ 六聚体是否有 cryo-EM 直接结构证据？K-ZAP 体内行为效应是否与寡聚体特异性阻断直接对应（排除其他 KIBRA 相互作用的影响）？
- Q-kibra-region-specificity：KIBRA 的突触标签功能在海马 CA1 之外（杏仁核、前额叶皮层、纹状体）是否一致？不同脑区的 KIBRA-PKMζ vs. KIBRA-PKCι/λ 比例是否有差异？
- Q-zstat-ptsd-potential：ζ-stat 能否实现对特定创伤记忆的选择性修改（再巩固窗口期干预）？血脑屏障穿透性、脑区靶向性、长期安全性是否有体内验证？

## 修订历史

- 2026-06-28 · 创建（rev1）· 基于《蛋白质会凋零，记忆却能永存》(#181) · 覆盖 KIBRA-PKMζ 寡聚体机制全貌；K-ZAP 和 ζ-stat 双工具；感染性磷酸化框架；AlphaFold 3 结构预测；初始置信度：中-高（核心机制有行为验证；六聚体结构部分体外证据）

## 来源文章

- [[2026-06-28-ltp-60-kibra-pkm-zeta-molecular-persistence]]

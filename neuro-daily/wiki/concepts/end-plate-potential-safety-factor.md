---
title: 终板电位与安全因子
slug: end-plate-potential-safety-factor
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-10-09
updated: 2026-10-09
revision_count: 1
dimensions: [synaptic, cellular, molecular]
related: [neuromuscular-junction, quantal-release, action-potential, myasthenia-gravis, lambert-eaton-syndrome]
prerequisites: [neuromuscular-junction, action-potential, synaptic-transmission]
opens_questions: [Q-nmj-02]
source_articles: [2026-10-09-neuromuscular-junction-synaptic-machine]
key_sources: ["PMID:30823359", "PMID:37270145"]
---

# 终板电位与安全因子 (End-Plate Potential & Safety Factor)

> **一句话定义**：终板电位（EPP）是一次 NMJ 量子释放事件在肌纤维终板区产生的总去极化，安全因子是 EPP 幅度与触发肌纤维动作电位所需阈值之比（2–5），是 NMJ 超可靠传递的定量指标。

## 当前理解

安全因子是理解 NMJ 可靠性的核心概念：

$$\text{安全因子} = \frac{\text{EPP 幅度（≈30–40 mV）}}{\text{触发肌纤维 AP 的阈值（≈15–20 mV）}} = 2\text{–}5$$

正常哺乳动物 NMJ 的安全因子为 2–5，人类约 2（Arnold 2023, PMC10847753）。这意味着即使量子释放随机减少一半，EPP 仍然足以触发肌纤维收缩。

**EPP 的决定因素**：

$$\text{EPP 幅度} = m \times q$$

其中：
- $m$ = 量子释放数（quantal content，≈50–100 个/AP）
- $q$ = 单量子幅度（MEPP 幅度，≈0.5–1 mV）

$m$ 取决于：Ca²⁺ 内流（Cav2.1 活性）× 突触前释放概率  
$q$ 取决于：nAChR 密度（~10,000/μm²）× 单通道电导 × 受体开放时间

**微终板电位（MEPP）**：自发性单量子释放产生的电位波动，是研究 NMJ 的基础工具。MEPP 幅度反映突触后功能状态；MEPP 频率反映突触前自发释放概率。

## 关键机制

### 安全因子的多重贡献者

| 因子 | 正/负 | 机制 |
|------|-------|------|
| 量子释放数 m | 正 | ↑Ca²⁺ 内流 or ↑释放机制效率 |
| nAChR 密度 | 正 | 折顶 ~10,000/μm² 确保足量电流 |
| 接头折叠深度 | 正 | 折底聚集 Nav1.4，↓动作电位阈值 |
| AChE 活性 | 双刃 | 正常：清除 ACh 防失敏；过弱：脱敏 |
| 膜静息电位 | 正（更负更好） | 更大驱动力 |

### 安全因子下降与疾病

- **重症肌无力（MG）**：抗 AChR 抗体 → nAChR 密度↓ → q↓ → EPP↓ → 安全因子跌破 1 → 疲劳性无力
- **Lambert-Eaton（LEMS）**：抗 Cav2.1 抗体 → Ca²⁺ 内流↓ → m↓ → EPP↓；运动后短暂改善（Ca²⁺ 积累代偿）
- **肉毒毒素**：SNARE 切断 → m = 0 → EPP = 0 → 弛缓性瘫痪
- **老化 NMJ**：接头折减少 → Nav1.4 重分布 → 有效阈值↑ → 安全因子↓ → 传递偶发失败

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 安全因子 2–5 | 细胞内电极记录 EPP + 阈值比较 | PMID:30823359, PMC6429197 | 极高 |
| MEPP ~0.5–1 mV；一量子激活 ~2,000 nAChR | 微电极记录 + 统计分析 | PMID:30823359 | 极高 |
| 人类 NMJ 安全因子 ~2x 阈值 | 肌肉活检体外电生理 | PMID:37270145, PMC10847753 | 高（测量有限） |
| 接头折叠增大后突触膜面积 8 倍 | 电镜形态计量学 | PMID:37270145 | 极高 |

## 连接

- [[neuromuscular-junction]] — EPP 是 NMJ 传递的功能输出
- [[action-potential]] — EPP 超过阈值后触发肌纤维 AP
- [[myasthenia-gravis]] — 安全因子下降的典型疾病模型（待建）
- [[lambert-eaton-syndrome]] — 量子释放减少的典型模型（待建）
- [[quantal-release]] — 量子释放概念（见 wiki/neurons/readily-releasable-pool.md）

## 未解问题

- Q-nmj-02（中）：NMJ 安全因子下降的最早可检测分子标志物是什么？能否在功能失败前通过生物标志物预测老龄相关肌无力？

## 修订历史

- 2026-10-09 · 创建 · 基于《命令的最后一公里》（#169）· 初始置信度：高

## 来源文章

- [[2026-10-09-neuromuscular-junction-synaptic-machine]]

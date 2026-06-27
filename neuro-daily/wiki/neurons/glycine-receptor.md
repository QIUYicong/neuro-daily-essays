---
title: 甘氨酸受体
slug: glycine-receptor
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-06-28
updated: 2026-06-28
revision_count: 1
dimensions: [molecular, cellular, synaptic]
related: [rem-sleep-atonia, synaptic-transmission, gaba-receptor, vmm-inhibitory-neurons, spinal-motoneuron]
prerequisites: [synaptic-transmission, membrane-potential, ion-channels]
opens_questions: []
source_articles: [2026-06-28-glycine-rem-atonia-vmm]
key_sources: ["PMID:1968326", "PMID:33372061", "PMCID:PMC7896014"]
---

# 甘氨酸受体 (Glycine Receptor, GlyR)

> **一句话定义**：甘氨酸受体（GlyR）是一种五聚体配体门控氯离子通道，属于 Cys-loop 超家族，是脊髓和脑干中最重要的快速抑制性受体，通过甘氨酸结合触发Cl⁻内流实现抑制性突触后电位（IPSP）。

## 当前理解

我们现在认为，GlyR 是脊髓和脑干低级运动控制回路中介导快速抑制的核心分子工具，与 GABA-A 受体在高级脑区的抑制角色地位相当。

GlyR 的重要性体现在两个方面：
1. **REM睡眠肌张力弛缓**：VMM的甘氨酸能神经元（GlyVMM→Mn亚群）通过GlyR对脊髓α运动神经元施加抑制，是REM期身体瘫痪的分子基础之一（Uchida et al. 2021，PMID:33372061）
2. **运动协调**：脊髓抑制性中间神经元（如Renshaw细胞）通过GlyR调控拮抗肌的对抗性抑制（reciprocal inhibition），是顺滑运动的基础

甘氨酸是人体最简单的氨基酸，在高级脑区作为前体代谢，但在脊髓和脑干中以经典神经递质的身份发挥快速抑制功能。

## 关键机制

### 亚基组成

GlyR 是由5个亚基环绕中央Cl⁻通道构成的五聚体：
- **α亚基（α1-α4）**：含甘氨酸结合位点；决定受体药理学特性
- **β亚基**：不独立形成功能性受体，与α亚基结合形成主要的突触形式

成人脊髓主要亚型：**α1/β 异源五聚体**（α1₂β₃，最常见）

发育变化：新生大鼠以α2同源体为主（对甘氨酸亲和力高，脱敏慢）；出生后逐渐被α1/β异源体替代（亲和力稍低，但动力学更快）。

### 分子动力学

甘氨酸结合→构象变化→Cl⁻孔道开放（单通道电导约45-50 pS）→Cl⁻内流→膜电位向Cl⁻平衡电位（约-70 mV）移动→超极化或分流（shunt）

特点：
- **快速**：开放时间~5 ms（比GABA-B的数百ms快得多）
- **士的宁（strychnine）**：经典GlyR竞争性拮抗剂；士的宁中毒→甘氨酸抑制消失→全身骨骼肌痉挛（符合脊髓disinhibition的预期）
- **甲喹酮（taurine）和β-丙氨酸（β-alanine）**：弱GlyR激动剂

### 在突触前和突触后的分布

**突触后**（主要角色）：聚集在脊髓抑制性突触后膜，与支架蛋白gephyrin相互作用形成稳定簇；gephyrin突变→GlyR定位受损→过度兴奋（类似甘氨酸能神经元损伤）。

**突触前**（次要角色）：部分证据表明突触前GlyR通过自身激动（spillover glycine）调节释放，但重要性尚存争议。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| REM期脊髓甘氨酸升高+IPSP增加 | 猫脊髓微透析+电生理 | PMID:1968326 | 高 |
| VMM甘氨酸能神经元（GlyVMM→Mn）激活脊髓GlyR实现REM atonia | GlyT2-iCre小鼠+EEG/EMG | PMID:33372061，PMC7896014 | 高 |
| α1/β为成人脊髓主要亚型（影响REM atonia药理学） | 亚基表达图谱+电生理 | 教科书知识，多来源 | 高 |
| Strychnine阻断GlyR→痉挛（脊髓抑制消失） | 经典药理学 | 历史实验 | 高 |

## 连接

- [[rem-sleep-atonia]] — GlyR是VMM→脊髓快速抑制的分子执行工具
- [[synaptic-transmission]] — GlyR属于配体门控离子通道介导的快速化学突触传递
- [[vmm-inhibitory-neurons]] — VMM甘氨酸能亚群通过突触前释放甘氨酸激活脊髓GlyR
- [[gephyrin]] — GlyR突触后定位的关键支架蛋白

## 未解问题

- α亚基各亚型（α1-α4）在不同运动核团的分布是否解释了不同肌肉群对REM atonia的敏感性差异？
- 甘氨酸的清除（转运体GlyT2负责再摄取）效率是否可被调控以影响REM肌张力弛缓的深度？

## 修订历史

- 2026-06-28 · 创建 · 基于《睡眠中的身体枷锁》（文章#178）· 重点：GlyR在REM atonia中的分子角色 · 初始置信度：高

## 来源文章

- [[2026-06-28-glycine-rem-atonia-vmm]]

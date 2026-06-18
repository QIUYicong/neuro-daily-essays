---
title: 恐惧消退
slug: fear-extinction
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-30
updated: 2026-07-10
revision_count: 3
dimensions: [molecular, cellular, microcircuit, brain-region, behavior, cognition, disease]
related: [fear-conditioning, amygdala, ltp, ltd, hippocampal-circuit, working-memory, parkinsons-disease, rem-sleep, theta-oscillations, emotional-memory-depotentiation, memory-reconsolidation]
prerequisites: [fear-conditioning, amygdala, ltp, ltd]
opens_questions: [Q-fear-reconsolidation-boundary, Q-fear-itc-bidirectionality, Q-fear-extinction-ptsd-biomarker, Q-rem-01, Q-rem-02]
source_articles: [2026-05-30-amygdala-fear-memory, 2026-05-31-rem-sleep-emotional-memory, 2026-07-10-memory-reconsolidation-ptsd]
key_sources: ["PMID:22129456", "PMID:18615014", "PMID:18615015", "PMID:24908482", "PMID:38370858", "PMID:28729826", "PMID:19702380"]
---

# 恐惧消退 (Fear Extinction)

> **一句话定义**：反复在无US情况下呈现CS，使条件性恐惧反应逐渐减弱的过程；消退不是抹除原始恐惧记忆，而是通过IL皮层→腹侧ITC→CeM新抑制回路建立竞争性安全记忆，两套痕迹并行共存，情景信号决定哪套占主导。

## 当前理解

我们现在认为，消退的核心是**新学习（new learning）而非遗忘（erasure）**。原始恐惧记忆（LA突触LTP）在消退训练后仍然保留——这被三类现象明确证明：（1）**自发恢复**：消退后数天恐惧自发重现；（2）**再激活**：消退后一次US即恢复完整恐惧；（3）**更新**：换到陌生情境恐惧重现。Nabavi等人2014年光遗传实验进一步证明：LTD消灭恐惧后，一次LTP即可完全恢复，说明原始突触位点仍然可以被重新增强。

消退学习建立的是一套竞争性抑制记忆，通过两种并行机制：**去增强**（弱化原始恐惧突触的类LTD机制，早期主导）和**新回路建立**（IL皮层→腹侧ITC→CeM抑制回路的突触增强，后期主导）。这套新回路是情景依赖的：只在消退训练发生的情景中有效，换情景则被关闭——这是情景信息从海马→BA的门控作用。

前额叶皮层对消退的双向控制是核心：前边缘皮层（PL）促进恐惧表达，下边缘皮层（IL）促进消退表达。vmPFC/IL在人类中的激活强度直接预测消退回忆的质量，PTSD患者vmPFC激活不足是其消退记忆提取障碍的神经底物。

**消退 vs 再巩固窗口消退（2026-07-10 新增）**：标准消退（长时间多次CS暴露）建立竞争性安全记忆，原始恐惧痕迹保留，故有自发恢复。"再巩固窗口消退"（Monfils 2009）在策略上根本不同：单次短暂CS再激活（开启再巩固窗口）→ 10 min 内进行消退训练 → 消退学习写入去稳定化的原始痕迹本身 → 无自发恢复、无更新、无再激活恢复。人类 fMRI 证据（Agren 2012）显示 BLA BOLD 信号被消除（原始痕迹删除），而标准消退中 BLA 信号保留。两者的关键时机区别（10 min vs 6h 后开始消退）对临床 PTSD 治疗设计有直接意义。

消退记忆的巩固特别依赖**REM睡眠**：Totty等人（2017，PMID:28729826）发现，消退训练后夜间睡眠期间，外侧杏仁核（LA）与腹侧海马（VH）之间θ振荡的相位关系（约180°反相）预测次日消退记忆的质量（R=0.954）。这表明消退记忆不只依赖于训练中的突触可塑性，还依赖于训练后REM睡眠期间特定的LA-VH θ同步状态。此外，REM睡眠通过蓝斑沉默（NE≈0）实现情绪记忆的去饱和化，有助于减弱原始恐惧痕迹的情感色彩，同时保留消退学习的信息内容（Walker 2009）。

## 关键机制

### 双重机制
1. **去增强（Depotentiation）**：低频CS重复 → NMDA/mGluR5依赖的LTD → CS传入LA突触轻度弱化；早期消退中起主要作用
2. **新抑制记忆建立**：
   - IL皮层投射 → ICMMV（腹侧ITC）：突触增强
   - 激活的ICMMV → CeM：GABAergic抑制
   - 消退神经元（BA）获得CS响应 → 通过ICMMV抑制恐惧输出

### ITC闸门：背侧与腹侧的角色分工
- **恐惧表达时**：LA→ICMMD（背侧ITC）激活 → ICMMD抑制ICMMV（腹侧）→ ICMMV无法抑制CeM → CeM活跃→恐惧
- **消退表达时**：BLA+IL→ICMMV激活 → ICMMV抑制CeM → 恐惧被压制
- 消退训练后，BLA→ICMMV突触增强（塑性变化）

### BA双神经元群（情景依赖的开关）
- **恐惧细胞**：条件反射后CS+，消退后响应消失；投射PL皮层
- **消退细胞**：消退后CS+；投射IL皮层
- 海马情景信号到达BA → 决定哪类细胞主导（安全情景→消退细胞；危险情景→恐惧细胞）

### 前额叶双向控制
- **PL（前边缘皮层）→ BA恐惧细胞/CeA**：激活PL → 促进恐惧表达；刺激PL → 恐惧重现；沉默PL → 恐惧减弱
- **IL（下边缘皮层）→ ICMMV + BA消退细胞**：激活IL → 促进消退表达；刺激IL → 消退增强；沉默IL → 消退受损

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| 消退不抹除原始恐惧（LTD→消退，LTP→恢复） | 光遗传双向操控LA突触 | PMID:24896183 | 极高（因果） |
| ITC神经元是消退表达的必要条件 | 选择性ITC损毁 → 消退表达缺陷 | PMID:18615014 | 高 |
| BA中恐惧/消退双神经元群，PL/IL差异投射 | 多通道记录+逆行标记 | PMID:18615015 | 高 |
| vmPFC激活强度预测消退回忆质量 | 人类fMRI多研究汇总 | PMID:22129456 (PMC4942586) | 中-高 |
| IL→BLA投射光遗传激活促进消退形成 | 光遗传操控IL→BLA通路 | PMID:38370858 (PMC10869525) | 高 |
| PTSD：消退训练正常，消退回忆次日失败 | 恐惧条件反射范式+fMRI | PMID:22129456 (PMC4942586) | 中 |

## 连接

- [[fear-conditioning]] — 被消退的对象；消退不抹除，而是建立竞争性抑制
- [[amygdala]] — 消退的神经解剖基础（ITC闸门、BA双群、CeA抑制）
- [[ltp]] — 原始恐惧记忆的底物（消退不能完全逆转）
- [[ltd]] — 去增强机制（早期消退中的NMDA/mGluR-LTD）；恐惧条件反射与消退的双向塑性
- [[hippocampal-circuit]] — 提供情景信号给BA，决定恐惧/消退哪套主导；消退的情景特异性来源
- [[norepinephrine-locus-coeruleus]] — 应激时NE过度激活 → 损害消退（Plas 2024）
- [[memory-reconsolidation]] — 再巩固窗口消退（短暂CS+10min内消退训练）是消退的升级版：修改原始痕迹而非竞争性压制，无自发恢复（Monfils 2009, Agren 2012）

## 未解问题

- Q-fear-reconsolidation-boundary（高优先级，部分解答 2026-07-10）：强记忆/旧记忆再巩固窗口的精确边界条件——Sevenster 2013 和 Eisenberg 2003 已明确：短暴露+小预测误差→再巩固；长暴露+大预测误差→消退；极强/极旧记忆难以去稳定化；临床转化的精确时机仍未解决
- Q-fear-itc-bidirectionality（中优先级）：ITC背侧/腹侧在恐惧重现时如何再平衡
- Q-fear-extinction-ptsd-biomarker（高优先级）：vmPFC激活作为个体化PTSD治疗预后标志物的临床可行性

## 修订历史

- 2026-07-10 · 修订 rev3 · 基于《记忆再巩固》(#78) · 当前理解节新增"消退 vs 再巩固窗口消退"段落（Monfils 2009 行为干预、Agren 2012 fMRI 证据、临床意义）；连接节新增 memory-reconsolidation；Q-fear-reconsolidation-boundary 标记为部分解答；source_articles/related 相应更新
- 2026-05-30 · 创建 · 基于《当杏仁核学会恐惧》一文 · 初始置信度：高（啮齿类证据充分，人类转化大体一致）

## 来源文章

- [[2026-05-30-amygdala-fear-memory]]

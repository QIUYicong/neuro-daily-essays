---
title: 延髓腹内侧区抑制性神经元
slug: vmm-inhibitory-neurons
domain: circuits
type: structure
status: established
confidence: high
created: 2026-06-28
updated: 2026-06-28
revision_count: 1
dimensions: [cellular, microcircuit, brain-region]
related: [rem-sleep-atonia, sublaterodorsal-nucleus, glycine-receptor, rem-sleep, narcolepsy, rem-behavior-disorder, flip-flop-switch-sleep-wake, parkinsons-disease]
prerequisites: [rem-sleep-atonia, glycine-receptor, brainstem-anatomy]
opens_questions: [Q-atonia-01, Q-atonia-02, Q-atonia-03]
source_articles: [2026-06-28-glycine-rem-atonia-vmm]
key_sources: ["PMID:1726063", "PMID:16891059", "PMID:29402935", "PMID:30450004", "PMCID:PMC6236475", "PMID:33372061", "PMCID:PMC7896014"]
---

# 延髓腹内侧区抑制性神经元 (VMM Inhibitory Neurons)

> **一句话定义**：延髓腹内侧区（VMM）的GABA能和甘氨酸能神经元群，在REM睡眠期被脑桥SLD的谷氨酸投射激活，通过向脑干和脊髓运动神经元发送抑制信号实现肌张力弛缓；其中的甘氨酸亚群（GlyVMM→Mn）特异性避开眼外肌运动核，是REM期眼动保留的解剖基础。

## 当前理解

我们现在认为，VMM抑制性神经元构成REM睡眠肌张力弛缓回路的"中继-效应"节点——既不是REM的发生器（SLD是发生器），也不是简单的传导管道，而是整合来自SLD的信号并精确分配到不同运动核团的专用处理站。

关键认识来自Uchida et al. 2021（PMID:33372061，PMC7896014）：VMM甘氨酸能神经元中存在一个功能特化的亚群（GlyVMM→Mn），其轴突终止于脑干和脊髓所有层级的体运动神经元，但系统性地绕过眼外肌运动核（动眼神经核III、外展神经核VI）。这种"选择性失联"正是REM睡眠命名由来——快速眼球运动发生在全身肌肉瘫痪的背景下，需要眼动运动神经元在atonia回路的覆盖范围外。

VMM抑制性神经元的"执行器"角色（而非"发生器"角色）由Valencia Garcia et al. 2018（PMID:30450004）的定量实验明确：灭活VMM GABA/Gly神经元使REM总量仅减少15%，而灭活SLD谷氨酸神经元使REM减少约30%。

## 关键机制

### 细胞类型组成

VMM抑制性神经元并非单一类型，目前可以区分：

1. **GABA能（GAD+，vGAT+）**：释放GABA，通过GABA-A和/或GABA-B受体抑制运动神经元
2. **甘氨酸能（GlyT2+，vGAT+）**：释放甘氨酸，通过GlyR抑制运动神经元
3. **共释放亚群**：许多神经元同时表达vGAT（GABA和甘氨酸共用的囊泡转运体），可能共释放两者

在Holstege & Bongers 1991（PMID:1726063）的电镜双标记研究中，VMM→脊髓末梢中约15%含甘氨酸免疫反应；结合GABA标记，>50%含GABA和/或甘氨酸。

### 精确的投射解剖（Uchida et al. 2021）

使用GlyT2-iCre转基因小鼠（99.1%特异性标记甘氨酸能神经元）+cTRIO（细胞类型特异性跨突触狂犬病毒追踪），研究者绘制了GlyVMM→Mn神经元的精确投射图：

**覆盖的运动核团**（均有密集甘氨酸能末梢）：
- 脊髓前角α运动神经元（颈髓、胸髓、腰髓）
- 三叉神经运动核（V）——控制咬合/下颌肌
- 面神经运动核（VII）——控制面部肌肉
- 舌下神经核（XII）——控制舌肌
- 疑核（NA）——控制咽喉/声带肌

**回避的运动核团**（无甘氨酸能末梢）：
- 动眼神经核（III）——上直肌、下直肌、内直肌等眼外肌
- 外展神经核（VI）——外直肌
- （注：眼内肌运动神经元的分布尚待确认）

### 上游输入（来自SLD）

SLD谷氨酸能神经元（约85.7%为Vglut2+）向VMM的GlyVMM→Mn亚群发送直接兴奋性突触。cTRIO追踪证实SLD→VMM的单突触连接，构成三节点回路的第一个突触。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| VMM甘氨酸能神经元在REM激活（c-fos） | 猫药物诱导REM+c-fos | PMID:16891059 | 高 |
| VMM GABA/Gly灭活→RBD样症状 | 大鼠AAV-vGAT-shRNA | PMID:29402935 | 高 |
| VMM是"执行器"（REM灭活减少15%）非"发生器" | 大鼠AAV定量 | PMID:30450004，PMC6236475 | 高 |
| GlyVMM→Mn覆盖体运动核但避开眼外肌核 | GlyT2-iCre+cTRIO | PMID:33372061，PMC7896014 | 高 |
| 沉默GlyVMM→Mn→EMG升高+猝倒减少92% | 破伤风毒素轻链+EEG/EMG | PMID:33372061，PMC7896014 | 高 |
| SLD→VMM直接谷氨酸能突触 | cTRIO逆行追踪 | PMID:33372061，PMC7896014 | 高 |

## 临床相关：PD与α-突触核蛋白

VMM抑制性神经元很可能是帕金森病（PD）和路易体痴呆（DLB）早期α-突触核蛋白病变的靶点。Braak分期描述PD的突触核蛋白病变从延髓（I/II期）向脑桥（III/IV期）再向中脑/皮层（V/VI期）推进。VMM正好位于Braak I-II期的延髓区域——与RBD的高转化率（40-65%，PMID:22019718）在解剖上吻合。

这使VMM抑制性神经元成为潜在的早期PD生物标志物靶点。

## 连接

- [[rem-sleep-atonia]] — VMM是REM atonia的主要执行节点
- [[sublaterodorsal-nucleus]] — SLD是VMM的上游谷氨酸能驱动器
- [[glycine-receptor]] — GlyR是GlyVMM→Mn亚群的突触后效应器
- [[narcolepsy]] — 猝倒与REM atonia共享GlyVMM→Mn回路
- [[parkinsons-disease]] — α-突触核蛋白病变可能最早攻击VMM
- [[rem-behavior-disorder]] — VMM GABA/Gly神经元退化导致RBD

## 未解问题

- Q-atonia-01：不同物种中甘氨酸 vs GABA-B vs 去促进化的权重差异
- Q-atonia-02：GlyVMM→Mn神经元发育过程中如何特异性"排除"眼外肌运动核的投射
- Q-atonia-03：α-突触核蛋白在VMM的早期入侵是否可被结构MRI/PET检测到

## 修订历史

- 2026-06-28 · 创建 · 基于《睡眠中的身体枷锁》（文章#178） · 聚焦GlyVMM→Mn亚群的精确解剖 · 初始置信度：高

## 来源文章

- [[2026-06-28-glycine-rem-atonia-vmm]]

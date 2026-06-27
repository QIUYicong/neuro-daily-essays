---
title: REM睡眠肌张力弛缓
slug: rem-sleep-atonia
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-28
updated: 2026-06-28
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, behavior]
related: [rem-sleep, glycine-receptor, vmm-inhibitory-neurons, sublaterodorsal-nucleus, flip-flop-switch-sleep-wake, narcolepsy, rem-behavior-disorder, alpha-synuclein, spinal-motoneuron]
prerequisites: [rem-sleep, synaptic-transmission, glycine-receptor]
opens_questions: [Q-atonia-01, Q-atonia-02, Q-atonia-03]
source_articles: [2026-06-28-glycine-rem-atonia-vmm]
key_sources: ["PMID:1968326", "PMID:33372061", "PMCID:PMC7896014", "PMID:29402935", "PMID:30450004", "PMCID:PMC6236475", "PMID:38060134", "PMID:38972672", "PMID:18385312"]
---

# REM睡眠肌张力弛缓 (REM Sleep Muscle Atonia)

> **一句话定义**：REM睡眠期间由脑桥SLD谷氨酸能神经元→延髓VMM甘氨酸/GABA能神经元→脊髓运动神经元构成的三节点回路主动执行的骨骼肌近乎完全瘫痪，使梦境内容不会被肌肉"表演"出来；该回路失效导致REM睡眠行为障碍（RBD）。

## 当前理解

我们现在认为，REM睡眠肌张力弛缓是由一条专用的三级抑制回路主动执行的，而非被动的"运动指令消失"。这条回路的三个节点分别是：

1. **SLD（被盖下背核）**：脑桥背侧的谷氨酸能神经元群，是 REM 睡眠的核心发生器（Vetrivelan & Bandaru 2023，PMID:38060134）。约85.7%的SLD神经元表达Vglut2（Uchida et al. 2021，PMID:33372061）。
2. **VMM（延髓腹内侧区）**：含GABA能和甘氨酸能神经元，REM期被SLD激活，充当回路的"中继-效应"节点。其中存在一个专门投射到运动神经元的甘氨酸亚群（GlyVMM→Mn），该亚群特异性地避开眼外肌运动核，解释了为何REM中眼球可以运动而躯体不能（Uchida et al. 2021）。
3. **脊髓α运动神经元**：接受VMM下行的甘氨酸/GABA抑制性突触，产生超极化，无法响应皮层运动指令。

肌张力弛缓的分子基础是多重叠加的：
- **甘氨酸/GABA-A**：快速、直接的Cl⁻通道介导的超极化
- **GABA-B**：慢速、持续的K⁺通道介导的超极化（Brooks & Peever 2010，PMID:20217361）
- **去促进化（disfacilitation）**：单胺能（5-HT、NE）神经元在REM期近乎沉默，撤回对运动神经元的基础兴奋性

这三种机制的相对权重在不同物种和不同运动核团间存在差异（见"争议"）。

## 关键机制

### 分子层：甘氨酸如何锁定运动神经元

甘氨酸受体（GlyR）是五聚体配体门控Cl⁻通道（Cys-loop家族，与GABA-A同属）。成人脊髓主要亚型为α1/β异源体。甘氨酸结合→Cl⁻内流→超极化→IPSP。

历史上，Chase & Morales（1990，PMID:1968326）用猫脊髓电生理+微透析首先证明：REM期脊髓腹角甘氨酸浓度升高，运动神经元接收大量甘氨酸介导的IPSP。

### 突触层：VMM-脊髓通路的化学性质

Holstege & Bongers（1991，PMID:1726063）用大鼠电镜双标记证明：VMM下行到脊髓的末梢中约15%含甘氨酸免疫反应；结合GABA数据，超过50%含GABA和/或甘氨酸。Morales et al.（2006，PMID:16891059）进一步证明猫VMM甘氨酸能神经元在诱导REM中被激活（c-fos阳性）。

### 回路层：SLD→VMM→脊髓

Valencia Garcia et al.（2018，PMID:29402935，Nat Commun）用大鼠AAV-vGAT-shRNA靶向灭活VMM的GABA/甘氨酸能神经元，产生RBD样症状，证明这类神经元对REM肌张力弛缓是充分必要的，且不影响清醒期运动（REM特异性效应器角色）。同期研究（PMID:30450004）证明VMM的GABA/Gly灭活仅使REM减少15%（效应器），而SLD谷氨酸灭活则减少约30%（发生器）。

Uchida et al.（2021，PMID:33372061，PMC7896014）用GlyT2-iCre小鼠精确定位了VMM中专门投射到运动神经元的甘氨酸亚群（GlyVMM→Mn），证明：选择性沉默该亚群→REM肌电显著升高（p=0.0292）；该亚群避开动眼/外展神经核（解释眼动保留）；在narcoleptic小鼠中，沉默该通路→猝倒减少92%（说明REM atonia和cataplexy共享此回路）。

### 系统层：上游调控

Luppi et al.（2025，PMID:38972672）描述的完整上游级联：外侧下丘脑MCH神经元（REM激活）→抑制vPAG（导水管周围灰质）GABA能神经元（REM抑制器）→解除对SLD的抑制→SLD激活→VMM激活→脊髓抑制。这是一套典型的去抑制级联（disinhibitory cascade）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| REM期运动神经元接收甘氨酸介导的IPSP | 猫脊髓电生理+甘氨酸微透析 | PMID:1968326 | 高 |
| VMM→脊髓末梢含GABA+甘氨酸（>50%） | 大鼠电镜双标记 | PMID:1726063 | 高 |
| VMM GABA/Gly神经元在REM中被激活 | 猫c-fos免疫组化 | PMID:16891059 | 高 |
| VMM GABA/Gly灭活→RBD样表型 | 大鼠AAV-vGAT-shRNA | PMID:29402935 | 高 |
| GlyVMM→Mn避开眼外肌核（眼动保留机制） | GlyT2-iCre+cTRIO追踪 | PMID:33372061，PMC7896014 | 高 |
| 沉默GlyVMM→Mn→REM期EMG升高（p=0.0292） | 破伤风毒素+EEG/EMG | PMID:33372061，PMC7896014 | 高 |
| SLDGlut→VMM突触（85.7%为Vglut2+） | Vglut2免疫荧光+AAV追踪 | PMID:33372061，PMC7896014 | 高 |
| GABA-B也参与REM上气道运动神经元抑制 | 微注射GABA-B拮抗剂+EMG | PMID:20217361 | 中 |
| 阻断GlyR+GABA-A仍有REM atonia（争议） | 微注射strychnine+bicuculline | PMID:18385312 | 中 |

## 连接

- [[rem-sleep]] — REM睡眠的状态框架；肌张力弛缓是REM的定义特征之一
- [[glycine-receptor]] — GlyR是实现快速抑制的分子基础
- [[vmm-inhibitory-neurons]] — VMM的GABA/甘氨酸能亚群是回路的执行节点
- [[sublaterodorsal-nucleus]] — SLD谷氨酸能神经元是回路的上游驱动器
- [[flip-flop-switch-sleep-wake]] — 状态切换电路控制SLD的激活与否
- [[narcolepsy]] — 猝倒（cataplexy）与REM atonia共享GlyVMM→Mn回路
- [[rem-behavior-disorder]] — REM atonia失效的临床表现
- [[parkinsons-disease]] — α-突触核蛋白病变攻击VMM→RBD→PD前驱症状

## 未解问题

- Q-atonia-01：不同物种间甘氨酸 vs GABA-B vs 去促进化的权重差异是否可调和？
- Q-atonia-02：GlyVMM→Mn神经元发育过程中如何"学会"避开眼外肌运动核？
- Q-atonia-03：PD早期α-突触核蛋白何时侵入VMM？是否可用MRI/PET早期检测？

## 修订历史

- 2026-06-28 · 创建 · 基于《睡眠中的身体枷锁》（文章#178）· 综合Uchida et al. 2021、Valencia Garcia et al. 2018等 · 初始置信度：高

## 来源文章

- [[2026-06-28-glycine-rem-atonia-vmm]]

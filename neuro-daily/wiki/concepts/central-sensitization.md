---
title: 中枢敏化（Central Sensitization）
slug: central-sensitization
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-14
last_revised: 2026-06-14
revision_count: 1
related:
  - nociception
  - gate-control-theory
  - kcc2
  - nmda-receptor
  - microglia
  - descending-pain-modulation
  - pain-matrix
article_sources:
  - "articles/2026-06-14-nociception-pain-pathways.md"
tags:
  - chronic pain
  - plasticity
  - NMDA
  - wind-up
  - KCC2
  - microglia
  - neuroinflammation
---

# 中枢敏化（Central Sensitization）

## 核心理解

中枢敏化（Central Sensitization, CS）是指脊髓及脑内痛觉传导回路发生的异常放大状态，表现为伤害性刺激诱发的神经元反应增强、感受野扩大、阈值降低。CS 是慢性疼痛综合征（纤维肌痛、CRPS、IBS、偏头痛）的核心机制，可在无持续外周炎症的情况下自主维持。IASP（国际疼痛研究协会）已将中枢敏化列为慢性疼痛病理生理学核心概念。

**本页面当前版本**：rev1（2026-06-14）

---

## 机制详解

### 1. NMDA 受体与 Wind-Up

**Wind-up** 是 CS 的电生理基础：C 纤维以 >0.3 Hz 的频率重复刺激时，脊髓背角 WDR 神经元的动作电位发放量逐渐累积增加（超出线性叠加）。

**分子机制**：
- NMDA 受体正常状态下被 Mg²⁺ 阻断（电压依赖）
- 持续性 C 纤维输入释放谷氨酸 + SP（substance P），激活 NK1 受体
- 反复去极化解除 Mg²⁺ 阻断，NMDA 受体开放
- Ca²⁺ 内流激活 CaMKII、PKC、ERK 信号级联
- 产生长时程增强（LTP）样突触可塑性

| 阶段 | 时间尺度 | 关键分子 | 可逆性 |
|---|---|---|---|
| Wind-up（即时） | 秒—分钟 | NMDA-R 去阻断 | 高 |
| 早期 CS | 分钟—小时 | PKC、ERK 磷酸化 | 中 |
| 晚期 CS | 小时—天 | 基因表达改变，Nav1.3↑ | 低 |
| 持续 CS | 天—月 | KCC2↓、胶质细胞激活 | 极低 |

### 2. KCC2 下调与 GABA 去极化

在正常成熟脊髓神经元中，KCC2 转运蛋白维持低胞内 [Cl⁻]，GABA-A 受体激活导致 Cl⁻ 内流→超极化（抑制）。

慢性伤害性输入触发：
1. BDNF（来自激活的小胶质细胞）激活 TrkB 受体
2. TrkB 信号磷酸化 KCC2，导致其内化/降解
3. 胞内 [Cl⁻] 升高 → GABA-A 受体激活变为 Cl⁻ 外流 → 去极化
4. 抑制性突触转变为兴奋性 → 闸门失效 → CS 自我维持

**这一机制直接将 KCC2（#189 文章主题）与慢性痛联系**：KCC2 功能丧失是 GABA 由抑制转兴奋的分子开关，在神经病理性疼痛模型（SNI、CCI、SNL）中均有记录。

### 3. 小胶质细胞—BDNF—TrkB 轴

周围神经损伤后：
- 初级传入释放 fractalkine、ATP、substance P
- 脊髓小胶质细胞激活（P2X4/P2X7 受体）
- 激活的小胶质细胞释放 **BDNF**、IL-1β、TNF-α、NO
- BDNF→TrkB→KCC2 磷酸化（如上）
- IL-1β/TNF-α 直接增强 AMPA 受体/Nav1.7 表达

**Coull et al. 2005（*Nature* 438:1017）**是证明这一轴的里程碑研究：将激活的脊髓小胶质细胞注射入朴素大鼠脊髓即可引发机械性异常性疼痛（allodynia）。

### 4. 星形胶质细胞的参与

慢性 CS 阶段：
- 星形胶质细胞激活（GFAP 上调）
- 谷氨酸转运蛋白（GLT-1/GLAST）表达降低 → 突触间隙谷氨酸蓄积
- 细胞因子（IL-6、CCL2）旁分泌信号强化 CS
- 谷氨酸溢出激活突触外 NMDA 受体（慢性 LTP）

---

## 临床表现三联征

1. **痛觉超敏（Hyperalgesia）**：对有害刺激的过度反应
   - 原发性痛觉超敏：损伤部位（外周敏化主导）
   - 继发性痛觉超敏：损伤周围正常组织（CS 主导）

2. **异常性疼痛（Allodynia）**：无害刺激诱发疼痛
   - 机械性 allodynia（轻触→剧痛）：A-β 纤维接入伤害性回路
   - 冷 allodynia：TRPM8 通路异常整合

3. **时间总和增强（Temporal Summation of Pain）**：
   - 重复相同刺激引起递增疼痛（wind-up 的主观等价）
   - 是临床诊断 CS 的量化工具

---

## CS 在慢性疼痛综合征中的角色

| 综合征 | CS 证据 | 特征性 CS 标志 |
|---|---|---|
| 纤维肌痛 | fMRI 显示痛觉回路异常激活 | 广泛性 allodynia、TS 增强 |
| CRPS | 脊髓/皮质重组 | 镜像疼痛、痛觉超敏 |
| 糖尿病神经病变 | Nav1.3 上调，KCC2 下调 | 烧灼痛、冷 allodynia |
| 慢性腰痛 | 默认模式网络解耦 | 情绪/认知加工异常 |
| 偏头痛 | 三叉神经核尾侧敏化 | 光声过敏、皮肤触痛 |

---

## 治疗靶点

| 靶点 | 策略 | 代表药/手段 |
|---|---|---|
| NMDA-R | 拮抗 Mg²⁺ 通道阻断位点 | 氯胺酮（低剂量 IV） |
| KCC2 | 恢复 KCC2 功能/表达 | 研发中（CLP290、furosemide 衍生物） |
| 小胶质细胞 | P2X4/P2X7 拮抗 | 米诺环素（临床试验） |
| BDNF-TrkB | TrkB 拮抗 | ANA-12 等（临床前） |
| 脊髓 GABAergic | 增强 GABA 抑制 | 巴氯芬（GABA-B 激动剂） |
| Na 通道 | Nav1.7/1.8 选择性阻断 | PF-05089771、A-803467 |

---

## 关键证据

| 证据 | 内容 |
|---|---|
| Woolf 1983 | 首次记录脊髓 WDR wind-up，*Pain* 15(2) |
| Coderre & Katz 1992 | NMDA 拮抗剂阻断 CS，PMID: 1324720 |
| Coull et al. 2005 | 小胶质细胞 BDNF→KCC2↓→allodynia，*Nature* 438 |
| Torsney & MacDermott 2006 | KCC2 在神经病理性痛脊髓中下调 |
| Woolf 2011 综述 | CS 概念框架，*Pain* 152(3 Suppl)，PMCID: PMC3436214 |

---

## 未解问题

- CS 的"临界点"：何种输入量级/时程不可逆触发持续 CS？
- 脑内（皮质/丘脑）CS 与脊髓 CS 的相对贡献如何分离？
- KCC2 恢复策略能否在不干扰其他 KCC2 依赖功能（如呼吸节律、运动回路）的情况下实现？

---

## 修订历史

| 版本 | 日期 | 修改内容 | 来源文章 |
|---|---|---|---|
| rev1 | 2026-06-14 | 初始创建：NMDA wind-up、KCC2 机制、小胶质细胞轴、临床表现三联征、治疗靶点 | #190 |


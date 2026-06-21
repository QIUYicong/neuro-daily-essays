---
title: 催产素
slug: oxytocin
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-16
updated: 2026-08-17
revision_count: 2
dimensions: [molecular, cellular, microcircuit, brain-region, behavior, cognition]
related: [ca2-hippocampus, social-memory, supramammillary-nucleus, vasopressin, dopamine-reward-prediction-error, active-zone, cntnap2, nucleus-accumbens, incentive-salience]
prerequisites: [synaptic-transmission, hippocampal-circuit]
opens_questions: [Q-oxt-01, Q-oxt-02, Q-sum-01]
source_articles: [2026-08-16-oxytocin-circuit-social-memory-bonding, 2026-08-17-nucleus-accumbens-wanting-liking-social-reward]
key_sources: ["PMID:10888874", "PMID:38052983", "PMID:41548026", "PMID:28606306", "PMID:22325206", "PMID:29897293", "PMID:14568015", "PMID:24948805", "PMID:31826983"]
---

# 催产素 (Oxytocin, OXT)

> **一句话定义**：催产素是由下丘脑PVN/SON合成的九肽神经肽，通过至少五条结构专化的长程投射路径（→SuM→CA2写入社会记忆、→NAc编码社会奖赏、→CeA抑制恐惧与辨别情绪、→外侧隔核预防社会恐惧、→BNST调制应激依赖社交倾向），实现"投射靶区决定功能"的多路社会行为调制——是"社会大脑"的核心基础设施之一，而非简单的"爱的激素"。

## 当前理解

我们现在认为，催产素（OXT）的功能不能用单一情绪效价（"促进爱与联结"）来概括——**功能由投射靶区决定，而非由分子本身决定**。

在外周，OXT促进子宫收缩（分娩）和乳腺收缩（泌乳），这些效应经血液循环介导。在中枢，OXT通过神经元间的突触传递和容量传递（volume transmission），在五个不同的脑区靶点产生功能上对立的效应，共同构成社会行为的神经基础。

关键奠基性证据：Ferguson et al. 2000（PMID:10888874）发现，催产素基因敲除小鼠（Oxt⁻/⁻）具有完整的嗅觉辨别能力和空间记忆，但**对反复见过的同伴依然表现出"第一次见面"的探索模式**——即对社会身份的记忆选择性消失。注射外源催产素可以恢复这种社会记忆，确立了催产素在社会认知中的特异性因果作用。

## 关键机制

### 1. 分子结构与受体

**催产素九肽序列**：Cys-Tyr-Ile-Gln-Asn-Cys-Pro-Leu-Gly-NH₂（9个氨基酸，C末端酰胺化，Cys1-Cys6形成二硫键）

**催产素受体（OTR/OXTR）**：G蛋白耦联受体（GPCR），耦联Gq/11，激活PLC-IP₃-DAG→PKC和CaMK通路；也可耦联Gi（细胞类型依赖）。与加压素受体（V1aR、V1bR/Avpr1b）结构高度相似（~46%氨基酸同源），两种受体对催产素和加压素均有一定交叉反应性（催产素也能激活V1bR）。

### 2. 产生细胞与亚群分化

OXT由两个下丘脑核团合成：
- **PVN（室旁核）**：含大细胞神经元（主要投射神经垂体和前脑）和小细胞神经元（投射脑干/脊髓）；PVN内部存在前/后功能分化（Chrisman 2026，PMID:41548026）
- **SON（视上核）**：以大细胞神经元为主；投射神经垂体（血液循环OXT）以及外侧隔核（SON→LS社会恐惧通路）

**PVN内亚群**（Chrisman et al. 2026）：
- **前PVN（aPVN）**：电生理接近BNST神经元，高自发突触活动；调控**应激依赖的社交回避**（aPVN OXT增强应激后社交回避）
- **后PVN（pPVN）**：较安静；支持**基线社交动机**（pPVN OXT促进正常社交接近）

### 3. 释放模式

OXT的中枢作用通过三种时空尺度不同的释放模式实现：
1. **突触释放（axonal release）**：在靶区的传统突触接触点释放，精准快速
2. **树突/胞体释放（somatodendritic release）**：大量释放到PVN/SON附近，形成自反馈
3. **容量传递（volume transmission）**：扩散到突触间隙外，影响较大空间范围（尤其在海马等区域可能更重要）

### 4. 五条专化投射路径

| 路径 | 来源 | 靶区 | 功能 |
|------|------|------|------|
| ① PVH→SuM→CA2 | PVH大细胞 | 海马CA2（经SuM中继） | 社会识别记忆写入 |
| ② PVN→NAc | 前PVN | 伏隔核壳 | 社会奖赏、配对联结 |
| ③ PVN→CeA | PVN大细胞 | 中央杏仁核外侧 | 恐惧抑制、情绪辨别 |
| ④ SON→LS | SON | 外侧隔核 | 哺乳期社会恐惧预防 |
| ⑤ aPVN→BNST | 前PVN | 终纹床核 | 应激依赖社交调制 |

**路径①（PVH→SuM→CA2）**（Thirtamara Rajamani 2024, PMID:38052983）：PVH催产素神经元投射到乳头丘脑上核（SuM），SuM中的谷氨酸能神经元高表达OTR，再投射到CA2。化学遗传沉默PVH-OXT或阻断SuM-OTR均损害社会识别记忆。

**路径②（PVN→NAc）**：NAc壳中的OTR激活强化配对联结偏好；与多巴胺（来自VTA）、μ阿片受体和内源性大麻素（anandamide）协同产生社会奖赏感（Borland 2025, PMID:39892577）。

**路径③（PVN→CeA）**：光遗传激活CeA内OXT轴突终末诱发催产素释放 → 激活CeL-off抑制性细胞 → 抑制CeM的恐惧输出 → 冻结被解除（Knobloch 2012, PMID:22325206; Rickenbacher 2017, PMID:28606306）。星形胶质细胞（OTR⁺亚群）协同介导此效应（Wahis 2021, PMID:33589833）。

**路径④（SON→LS）**：SON催产素神经元在哺乳期激活 → 抑制外侧隔核的社会恐惧回路 → 允许哺乳期母亲对大量社会接触保持开放（Menon 2018, PMID:29551417）。

**路径⑤（aPVN→BNST）**：前PVN催产素神经元在应激下激活，通过BNST介导应激后的社交回避调制（Chrisman 2026, PMID:41548026）。

### 5. 社会凸显假说（理论框架）

Shamay-Tsoory & Abu-Akel 2016（PMID:26321019）的"社会凸显假说"认为：催产素不改变情绪效价（不是让一切变得更好），而是**增强对社会相关刺激的感知显著性**——包括正性刺激（亲密、联结）和负性刺激（外群体威胁、社会危险）。这解释了人类研究中催产素既能促进亲社会行为又能增强群体偏见的"双面性"。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Oxt⁻/⁻小鼠社会失忆，空间/嗅觉正常 | 基因敲除+社会认知测试+OXT补充恢复 | PMID:10888874 (Ferguson 2000) | 高（奠基性遗传证明） |
| PVH→SuM→CA2路径对社会记忆因果必要 | DREADD+病毒追踪+SuM-OTR阻断 | PMID:38052983 (PMC11116117) | 中-高（需独立复制） |
| CeA内OXT轴突释放抑制条件恐惧冻结 | 光遗传激活CeA-OXT轴突+OTR拮抗剂 | PMID:22325206 (Knobloch 2012) | 高 |
| CeL-off cells是CeA中OXT作用的细胞靶点 | 电生理+光遗传+母性行为测试 | PMID:28606306 (PMC5469614) | 高 |
| NAc壳OTR激活强化配对联结，阻断则削弱 | 草原田鼠OTR激动剂/拮抗剂+配对偏好测试 | PMID:39892577（综述） | 高（多项独立研究） |
| SON→LS催产素防止哺乳期社会恐惧 | 特异性沉默LS-投射OXT神经元+社会恐惧测试 | PMID:29551417 (Menon 2018) | 中-高 |
| 前/后PVN催产素神经元电性质和行为功能对立 | shRNA敲减+电生理+多行为范式 | PMID:41548026 (PMC13003577) | 中（新结果） |

## 连接

- [[ca2-hippocampus]] — 催产素通过PVH→SuM→CA2路径写入社会识别记忆
- [[social-memory]] — 社会记忆的神经底物之一；OXT是门控信号
- [[supramammillary-nucleus]] — 催产素到CA2的关键中继站
- [[vasopressin]] — 与催产素同家族，共用受体（Avpr1b在CA2），功能部分互补
- [[cntnap2]] — CNTNAP2缺失导致PVN催产素神经元减少，是ASD社交缺陷的重要机制之一
- [[hippocampal-circuit]] — CA2是社会记忆底物，位于海马回路中
- [[pv-interneurons]] — CA2中的PV+中间神经元受CNTNAP2影响，间接影响催产素效应
- [[nucleus-accumbens]] — NAc是OXT-DA协同产生社会奖赏/配对联结的关键节点（Liu & Wang 2003；Heifets 2019）
- [[incentive-salience]] — OT与DA在NAc协同时，赋予社会刺激特殊的"社会身份标记"而非单纯激励显著性

## 未解问题

- **Q-oxt-01（高优先级）**：PVH→SuM→CA2路径和PVN→CA2直接加压素路径在时间上如何协调？两条路径是竞争的还是互补的？有没有实验同步测量两条路径在社会接触时的激活时序？
- **Q-oxt-02（中优先级）**：人类鼻腔给药催产素（IN-OXT）是否真的提高脑内催产素浓度？药代动力学证据矛盾，需要高质量直接测量研究（如PET追踪）。
- **Q-sum-01（高优先级）**：SuM的θ节律起搏功能和催产素中继功能是否由不同的神经元亚群承担？

## 修订历史

- 2026-08-16 · 创建 · 基于《催产素回路：五条专化投射》文章 #115 · 整合 Ferguson 2000、Thirtamara Rajamani 2024、Chrisman 2026、Borland 2025、Knobloch 2012、Rickenbacher 2017、Menon 2018 等来源 · 初始置信度：高（多项独立研究支持五条路径的核心主张）
- 2026-08-17 · 修订 rev2 · 基于《大脑的欲望引擎》（文章#116）· 新增NAc配对联结路径（Liu & Wang 2003：OT+D2 NAc共同激活是配对联结必要条件；Heifets 2019：MDMA通过SERT→5-HT→OTR→NAc实现促社交效应）；新增连接：nucleus-accumbens、incentive-salience；key_sources新增PMID:14568015、PMID:24948805、PMID:31826983

## 来源文章

- [[2026-08-16-oxytocin-circuit-social-memory-bonding]]
- [[2026-08-17-nucleus-accumbens-wanting-liking-social-reward]]

---
title: 线粒体功能障碍
slug: mitochondrial-dysfunction
domain: diseases
type: mechanism
status: established
confidence: high
created: 2026-09-09
updated: 2026-09-09
revision_count: 1
dimensions: [molecular, cellular, synaptic, disease]
related: [parkinsons-disease, alzheimers-disease, huntingtons-disease, excitotoxicity, reactive-oxygen-species, pink1-parkin-mitophagy, drp1, nmda-receptor, bdnf, medium-spiny-neuron]
prerequisites: [action-potential, voltage-gated-calcium-channels, parkinsons-disease]
opens_questions: [Q-mito-01, Q-mito-02, Q-mito-03]
source_articles: [2026-09-09-mitochondrial-dysfunction-neurodegeneration]
key_sources: ["PMID:38241161", "PMC10903104", "PMID:38744846", "PMC11094169", "PMID:33168089", "PMC7654589", "PMID:28379197", "PMC5488005", "PMID:11598490", "PMID:36943668", "PMID:19682570"]
---

# 线粒体功能障碍 (Mitochondrial Dysfunction)

> **一句话定义**：线粒体氧化磷酸化效率降低、活性氧过量产生、ΔΨm（线粒体膜电位）崩溃、Ca²⁺ 缓冲失效和/或 PINK1/Parkin 介导的质量控制通路失效的综合状态，是帕金森病（Complex I）、阿尔茨海默病（Complex IV）和亨廷顿病（Complex II）等主要神经退行性疾病共享的核心病理轴。

## 当前理解

我们现在认为，线粒体功能障碍并非神经退行性疾病的"结果"，而是驱动疾病进展的**主动机制**。神经元对线粒体氧化磷酸化（OXPHOS）的依赖程度接近绝对：大脑以 2% 体重消耗 20% 全身能量，其中 90% 通过 OXPHOS 产生；单个皮层神经元在静息状态下每秒消耗约 47 亿个 ATP（PMID:38241161, PMC10903104）。

当电子传递链（ETC）功能受损时，发生一系列相互放大的事件：ATP 减少 → 膜电位维护困难 → Na⁺/K⁺ 泵减弱 → 局部去极化 → 更多 ATP 消耗，与此同时 ROS 产生增加 → mtDNA 损伤 → ETC 亚基缺陷 → 更多 ROS（"ROS 诱导 ROS"自我放大循环）。当 Ca²⁺ 超载叠加上来时，**mPTP（线粒体通透性转变孔）**开放，ΔΨm 崩溃，细胞色素 c 释放，caspase 激活，神经元凋亡。

三种主要神经退行性疾病各有其 ETC 攻击靶点：PD 攻击 Complex I，AD 攻击 Complex IV（以及 Complex I），HD 攻击 Complex II/III——但无论从哪个入口进入，终点都是 mPTP 开放与神经元死亡。

## 关键机制

### 电子传递链（ETC）与 OXPHOS

线粒体内膜上的五个复合体将 NADH/FADH₂ 的化学能转化为 ATP：

| 复合体 | 功能 | 质子泵 | 神经退行疾病关联 |
|------|------|------|------|
| Complex I（NADH脱氢酶） | NADH → 泛醌 | 4H⁺/电子对 | **PD**（MPTP、鱼藤酮；死后脑研究显著降低） |
| Complex II（琥珀酸脱氢酶） | 琥珀酸 → 泛醌（TCA接口） | 无 | **HD**（死后脑显著降低；3-NP复制HD样损伤） |
| Complex III（细胞色素bc₁） | 泛醌 → Cyt c | 2H⁺/电子 | HD（Complex III也降低）；超氧产生位点 |
| Complex IV（Cyt c氧化酶） | Cyt c → O₂ → H₂O | 4H⁺/电子对 | **AD**（Complex IV活性降低；APP阻断COX亚基导入） |
| Complex V（ATP合酶） | 质子回流 → ATP | 3H⁺/ATP | AD（Complex V也有报道减少） |

驱动整个系统的是 **ΔΨm**（跨内膜质子电化学梯度，约 −180 mV）。ΔΨm 消失是线粒体功能障碍的最早可测量信号之一，也是 PINK1 积累和线粒体自噬启动的触发条件。

### 活性氧（ROS）的双面性

正常条件下，约 1-2% 经 ETC 的电子逸出生成超氧（O₂•⁻），经 SOD2（线粒体）→ H₂O₂ → 过氧化氢酶/GPx 安全转化。这些低浓度 ROS 作为信号分子参与 Nrf2 抗氧化适应和 UCP2/3 解偶联保护。

超过清除阈值后，•OH（羟自由基，Fenton 反应）损伤：
- **mtDNA**（无组蛋白保护，损伤率可达核 DNA 的 4–48 倍）→ ETC 亚基突变
- **内膜脂质**（心磷脂氧化，破坏 Complex I/III/IV 的组装平台）
- **ETC 铁硫簇**（Complex I/II/III 的电子传递中心直接失活）

### 线粒体钙缓冲与 mPTP

**生理功能**：线粒体通过 MCU 复合体（MCU + EMRE + MICU1/2）摄取 Ca²⁺（ΔΨm 驱动），基质内 Ca²⁺ 升高激活 TCA 循环脱氢酶，使 ATP 产生与神经活动水平实时匹配。

**病理过载**：慢性/过量 Ca²⁺ 内流（兴奋毒性、ΔΨm 已部分损失时）→ 基质 Ca²⁺ 超载 → **mPTP** 开放 → ΔΨm 崩溃 → ATP 合酶逆转消耗 ATP → 基质肿胀→外膜破裂 → **细胞色素 c** 释放入细胞质 → **caspase-9 → caspase-3** → 凋亡（PMID:38744846, PMC11094169）。

mPTP 的分子身份仍有争议（Q-mito-01）：Cyclophilin D 是已确认的调节亚基（CsA 抑制 CypD 可阻断 mPTP），通道蛋白本体（ATP 合酶 c 亚基环？ANT？）尚未最终确定。

### 分裂/融合动力学失衡

**融合**（有利于 ATP 效率和 mtDNA 互补）：MFN1/MFN2（外膜）+ OPA1（内膜）

**分裂**（有利于运输和损伤隔离）：DRP1 从细胞质转位至 OMM，与 FIS1/MFF/MiD49/51 结合后，通过 GTP 水解驱动膜收缩和切断

**神经退行性疾病中的失衡**：
- **AD**：Aβ 通过 S-亚硝基化（S-nitrosylation）异常激活 DRP1 → 病理性过度分裂 → 碎片化线粒体 ATP 产出降低 + 突触损失（PMID:28379197, PMC5488005）
- **PD**：α-突触核蛋白与 DRP1 直接相互作用 → 分裂过度
- **HD**：mHTT 损伤 PGC-1α → MFN1/2 和 OPA1 基因表达降低 → 融合减少 + 运输障碍

### PINK1/Parkin 线粒体自噬（详见 wiki/concepts/pink1-parkin-mitophagy）

**正常稳态**：PINK1 被 TOM/TIM23 持续导入，PARL 切割，蛋白酶体降解（低水平）。

**ΔΨm 丢失后**：
1. PINK1 不再被 TIM23 拉入（需要 ΔΨm），在 OMM 积累 → 二聚化+自磷酸化
2. PINK1 磷酸化泛素 **Ser65** → pSer65-Ub 生成
3. pSer65-Ub 结合 Parkin Ubl 结构域 → 构象变化激活 Parkin E3 活性
4. Parkin 泛素化 OMM 蛋白 → 正反馈放大（新 Ub 再被 PINK1 磷酸化）
5. pUb 链被 **NDP52** 和 **OPTN**（optineurin）识别 → **TBK1** 磷酸化 OPTN → LIR 结合 LC3 → 自噬体包裹 → 溶酶体降解（PMID:33168089, PMC7654589）

**疾病中的失效**：PD 突变（PINK1 G309D 等）阻止 ΔΨm 丢失时的 OMM 积累；Parkin 突变破坏 E3 活性；AD 中即使无直接突变，Parkin 招募也受损。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 皮层神经元静息 ATP 消耗 ~4.7×10⁹/秒 | 计算建模（解剖+电生理数据） | PMID:11598490（摘要）；PMID:38241161 | 中-高（模型推算） |
| PD 黑质死后脑 Complex I 活性显著降低 | 死后脑酶活性测定；MPTP/鱼藤酮模型 | PMID:38241161, PMID:36943668 | 高 |
| AD 死后脑 Complex IV 活性降低；APP 阻断 COX 亚基导入 | 死后脑酶活性；体外 APP 过表达 | PMID:38241161 | 中-高 |
| HD 死后纹状体 Complex II/III 降低 | 死后脑酶活性（多项独立研究） | PMID:19682570; PMID:38241161 | 高 |
| 3-NP（Complex II抑制剂）选择性复制 HD 样纹状体 MSN 死亡 | 大鼠/灵长类 3-NP 注射模型 | PMID:19682570 | 高（但模型 ≠ HD，已明确） |
| PINK1 在 ΔΨm 丢失时积累于 OMM，激活 Parkin | 细胞去极化（CCCP）模型；荧光成像；生化验证 | PMID:33168089, PMC7654589 | 高（体外）；中（体内） |
| Pink1 KO 猕猴出现严重神经退化（小鼠不出现） | CRISPR/Cas9 猕猴敲除 vs Pink1 KO 小鼠对比 | PMID:33168089 | 高 |
| Aβ 通过 DRP1 S-亚硝基化诱发病理性线粒体分裂 | AD 模型神经元；体外 Aβ 处理 | PMID:28379197, PMC5488005 | 中（体外高浓度 Aβ） |
| mPTP 开放依赖 CypD；CsA 抑制 CypD 阻断 mPTP | 遗传敲除（CypD KO 小鼠）；CsA 药理学 | PMID:38744846 | 高 |

## 连接

- [[parkinsons-disease]] — Complex I 缺陷是 PD 的核心分子标志；多巴胺能神经元的额外 Ca²⁺ 振荡负担放大了 Complex I 损伤的毒性
- [[alzheimers-disease]] — Complex IV 降低（APP 毒性）+ Aβ 诱发 DRP1 过度分裂 + tau 干扰线粒体运输
- [[huntingtons-disease]] — Complex II/III 缺陷 + PGC-1α 轴损伤 + Ca²⁺ 缓冲容量降低 → MSN 选择性脆弱性
- [[excitotoxicity]] — 兴奋毒性 Ca²⁺ 超载的最终致死步骤是 mPTP 开放；两条通路在 mPTP 处汇聚
- [[pink1-parkin-mitophagy]] — 线粒体功能障碍时的最后防线；ΔΨm 丢失触发 PINK1 积累和 Parkin 招募
- [[reactive-oxygen-species]] — ETC 电子泄漏产生的 ROS 是线粒体损伤与 mtDNA 突变的直接原因（页面尚未创建，悬空引用）
- [[nmda-receptor]] — NMDA 受体的 Ca²⁺ 内流是触发线粒体 Ca²⁺ 超载的主要途径之一
- [[bdnf]] — 线粒体功能障碍减少 BDNF 的 TrkB 信号（能量不足）；BDNF 减少反过来损害线粒体生物合成（PGC-1α 轴）
- [[medium-spiny-neuron]] — MSN 的 Complex II 特异性脆弱性 + Ca²⁺ 缓冲容量降低解释了 HD 的纹状体选择性

## 未解问题

- Q-mito-01（高优先级）：mPTP 的分子身份——通道蛋白是 ATP 合酶 c 亚基环？ANT？还是多蛋白复合体？CypD 调节亚基已确认但通道本体仍争议
- Q-mito-02（高优先级）：PINK1/Parkin 通路在体内慢性低水平压力下的真实活性——体外 CCCP 诱导的急性去极化与神经退行性疾病的慢性进展是否有机制差异？
- Q-mito-03（中优先级）：PD/AD 中，ROS 过量产生 vs 线粒体质量控制失效，哪个是启动事件？两者之间是否存在时序关系？

## 修订历史

- 2026-09-09 · 创建 · 基于《线粒体功能障碍：神经元高能耗的代价》一文 · 初始置信度：高；填补图谱唯一悬空引用 `mitochondrial-dysfunction`

## 来源文章

- [[2026-09-09-mitochondrial-dysfunction-neurodegeneration]]

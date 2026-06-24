---
title: TDP-43 病理
slug: tdp-43-pathology
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-11
updated: 2026-09-11
revision_count: 1
dimensions: [molecular, cellular, disease]
related: [als-amyotrophic-lateral-sclerosis, cryptic-exon, liquid-liquid-phase-separation, ran-translation, dipeptide-repeat-proteins, huntingtons-disease, alzheimers-disease, excitotoxicity, proteostasis]
prerequisites: [rna-splicing, liquid-liquid-phase-separation, protein-aggregation]
opens_questions: [Q-als-01]
source_articles: [2026-09-11-als-tdp43-motor-neuron-selective-vulnerability]
key_sources: ["PMID:17023659", "PMID:35197626", "PMC8891019", "PMID:35197628", "PMC8891020", "PMID:35767949", "PMC9327139", "PMID:30120348", "PMC6417666"]
---

# TDP-43 病理 (TDP-43 Pathology)

> **一句话定义**：TDP-43 从细胞核中消失（核清除）并在细胞质中形成磷酸化、泛素化聚集体的过程，是 ALS（>97%）、FTLD-TDP 和部分阿尔茨海默病（~57%）的统一分子病理标志，同时产生核功能丧失（隐蔽外显子暴露，UNC13A/STMN2）和胞质毒性获得（RBP 隔离，朊病毒样传播）双重损伤。

## 当前理解

我们现在认为，TDP-43 病理代表了蛋白质从正常功能态（核内液液相分离态）到不可逆病理态（胞质固态聚集体）的相转变，是一种热力学不可逆过程而非主动的功能改变。TDP-43 的 C 端低复杂度结构域（LCD/PLD）驱动正常的液液相分离（LLPS），使 TDP-43 参与应激颗粒等膜less细胞器；在病理条件下（过度磷酸化、长期应激、疾病突变）液态小滴失去可逆性，转化为固态凝胶或聚集体。

核功能丧失（LOF）和胞质毒性功能获得（GOF）同时发生，两者都独立地对神经元有害，且互相放大：LOF 导致 UNC13A（突触囊泡释放调控）和 STMN2（轴突微管动力学）隐蔽外显子暴露，产生截短蛋白；GOF 包括 RBP 隔离、UPS 负荷超载、朊病毒样传播。

TDP-43 病理在阿尔茨海默病中的高发率（~57%）提示 TDP-43 稳态失调可能是多种神经退行性疾病的共同参与机制，而非 ALS/FTD 的专属。

## 关键机制

### 正常 TDP-43 功能

- 两个 RNA 识别基序（RRM1/RRM2）：识别 UG 富集 RNA 序列
- C 端 LCD/PLD：驱动 LLPS，参与应激颗粒的可逆形成
- 核内抑制隐蔽外显子：结合靶基因内含子，阻止剪接体识别隐蔽剪接位点

### 病理相转变：液态→固态

1. **应激颗粒停留时间延长**：正常情况下，应激解除后 TDP-43 从应激颗粒溶解回核；病理状态下溶解失败
2. **LCD 的过度磷酸化**（多个丝氨酸，尤其 S409/S410）：改变相互作用热力学，增加聚集倾向
3. **疾病相关 LCD 突变**（A315T、G298S 等）：直接破坏 LCD 的可逆相分离平衡
4. **DPR（poly-GR/PR）相互作用**：C9orf72 来源的 DPR 与 TDP-43 LCD 强力结合，诱导固态化

### 核功能丧失（LOF）下游

- **UNC13A 隐蔽外显子**：TDP-43 耗竭→内含子中隐蔽外显子暴露→含提前终止密码子的截短 mRNA→UNC13A 蛋白减少（PMID:35197626/35197628）
- **STMN2 隐蔽多腺苷酸化**：第 1 内含子中的隐蔽 PolyA 位点暴露→STMN2 mRNA 截短→轴突再生能力丧失（PMID:35767949）

### 胞质毒性获得（GOF）

- RBP 隔离（sequestration）：聚集体吸附正常 hnRNP，扩大 RNA 代谢紊乱
- UPS 负荷超载：泛素化聚集体饱和蛋白酶体
- 朊病毒样传播：细胞外释放的 TDP-43 聚集体种子进入邻近细胞，引发级联聚集

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| TDP-43 聚集是 ALS 统一病理标志（>97%） | 尸检免疫组化 | PMID:17023659 | 高 |
| TDP-43 耗竭导致 UNC13A 隐蔽外显子暴露 | RNA-seq + 患者脑组织 | PMID:35197626, 35197628 | 高 |
| STMN2 截短是 TDP-43 LOF 下游且损害运动神经元 | iPSC-MN + KO 小鼠 | PMID:35767949 | 高 |
| Poly-GR/PR 与 TDP-43 LCD 相互作用诱导固态化 | 体外相分离 + 细胞系 | PMID:30120348 / PMC6417666 | 中-高 |

## 连接

- [[als-amyotrophic-lateral-sclerosis]] — TDP-43 病理是 ALS 分子核心
- [[cryptic-exon]] — 核 LOF 的直接下游后果
- [[ran-translation]] — C9orf72 DPR 诱导 TDP-43 固态化
- [[dipeptide-repeat-proteins]] — poly-GR/PR 特异与 TDP-43 共定位
- [[excitotoxicity]] — 运动神经元的共同脆弱性背景
- [[huntingtons-disease]] — 对比：类似的"汇聚性病理"设计，不同的蛋白

## 未解问题

- Q-als-01（高）：LOF 与 GOF 哪个是主驱动？两者是否可以解耦干预？

## 修订历史

- 2026-09-11 · 创建 · 基于《ALS TDP-43 文章》(#141) · 初始置信度：高

## 来源文章

- [[2026-09-11-als-tdp43-motor-neuron-selective-vulnerability]]

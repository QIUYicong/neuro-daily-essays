---
title: 兴奋毒性
slug: excitotoxicity
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-09-08
updated: 2026-09-08
revision_count: 1
dimensions: [molecular, synaptic, cellular, disease]
related: [nmda-receptor, glutamate-glutamine-cycle, ltp, calcium-channel, bdnf, huntingtons-disease, alzheimers-disease, parkinsons-disease, mitochondrial-dysfunction, astrocyte-calcium-signaling, tripartite-synapse, medium-spiny-neuron]
prerequisites: [nmda-receptor, synaptic-transmission, glutamate-glutamine-cycle]
opens_questions: [Q-exc-01, Q-exc-02, Q-exc-03]
source_articles: [2026-09-08-excitotoxicity-synaptic-extrasynaptic-calcium-death]
key_sources: ["PMID:20842175", "PMC2948541", "PMID:2880938", "PMID:35078537", "PMC8788129", "PMID:38891774", "PMID:37236602", "PMID:18923045"]
---

# 兴奋毒性 (Excitotoxicity)

> **一句话定义**：由谷氨酸或其他兴奋性神经递质的过度激活引发的神经元死亡机制；关键不在于谷氨酸的绝对量，而在于NMDA受体激活的**位置**——突触内激活触发存活程序，突触外激活触发死亡程序。

## 当前理解

我们现在认为，兴奋毒性是神经系统中最具悖论色彩的病理机制之一：赋予学习和记忆可能的分子机器（NMDA受体→Ca²⁺→LTP），在时空失控时变成摧毁神经元的工具。

核心范式（Hardingham & Bading 2010，PMID:20842175）将NMDA受体按位置区分为两类，激活截然相反的信号通路：

**突触内NMDAR（SynNMDARs）→ 存活**：Ca²⁺信号激活CREB磷酸化，上调约10个AID（死亡抑制因子）基因，构建"存活屏障（neuroprotective shield）"。

**突触外NMDAR（ExSynNMDARs）→ 死亡**：Jacob蛋白入核 → CREB去磷酸化；ERK灭活；FOXO激活；DAPK1磷酸化GluN2B增大Ca²⁺通量；Calpain-STEP-p38死亡级联。

Ca²⁺超载的终端执行机制：线粒体钙单运体（MCU）过摄→活性氧（ROS）爆发→线粒体通透性转换孔（mPTP）开放→细胞色素C释放→Caspase级联→凋亡；若能量耗竭则走向坏死。

在慢性神经退行性疾病中，可能存在"兴奋性线粒体毒性（EMT）"的亚致死性形式：长期亚致死Ca²⁺超载导致树突/突触退行，先于细胞体死亡（Verma et al. 2022，PMID:35078537）。

**守门机制**：星形胶质细胞的谷氨酸转运体GLT-1/EAAT2将突触外谷氨酸维持在约25–100 nM，防止突触外NMDAR的慢性激活。此防线在ALS、HD、缺血时失守。

## 关键机制

### 1. Choi两相模型（1987，PMID:2880938）

| 时相 | 时程 | 离子依赖 | 可逆性 | 结局 |
|------|------|---------|--------|------|
| 早期相 | 数分钟 | Na⁺/Cl⁻ | 可逆（撤去谷氨酸） | 神经元肿胀 |
| 迟发相 | 数小时 | Ca²⁺ | 不可逆 | 神经元死亡 |

### 2. 突触内/外NMDAR信号二分（Hardingham & Bading 2010，PMID:20842175，全文开放PMC2948541）

**突触内（SynNMDAR）激活的存活程序**：
- Ca²⁺ → 核Ca²⁺/CaM激酶 → CREB磷酸化(Ser133) → AID基因组（Atf3, Btg2, Npas4, Nr4a1…）
- 上调：抗凋亡蛋白、BDNF、硫氧还蛋白-过氧化物还原蛋白抗氧化系统
- 下调：Puma, Apaf-1, Caspase-9, Caspase-3

**突触外（ExSynNMDAR）激活的死亡程序**：
- Jacob → 入核 → CREB去磷酸化
- ERK1/2去磷酸化（保护信号消失）
- FOXO转录因子入核 → 上调Noxa, Bim, FasL
- Calpain激活 → 裂解STEP → p38激活 → 死亡
- DAPK1招募到GluN2B C末端 → GluN2B磷酸化 → 单通道电导增大（正反馈）
- PSD-95-nNOS偶联 → nNOS激活 → NO+超氧自由基 → 过氧亚硝酸盐 → 亚硝化损伤

### 3. 线粒体钙-ROS-mPTP三联体（Verma et al. 2022，PMID:35078537，全文开放PMC8788129）

```
持续Ca²⁺内流（外突触NMDAR）
    ↓
MCU饱和 → 线粒体Ca²⁺超载
    ↓
复合体I受损 → ROS爆发
    ↓
ROS + Ca²⁺ 共同触发 mPTP 开放
    ↓
ΔΨm崩溃 → 细胞色素C释放
    ↓
Caspase级联（凋亡）/ ATP耗竭（坏死）
```

**延迟性钙失调（DCD）**：兴奋毒性刺激后Ca²⁺短暂恢复后的二次不可逆升高，标志着线粒体缓冲能力的终末耗竭，是不可逆死亡的时间节点。

### 4. 谷氨酸转运体防线

GLT-1/EAAT2（星形胶质细胞）利用Na⁺梯度驱动谷氨酸摄入，将突触外谷氨酸维持在nM级（防止慢性外突触NMDAR激活）。

功能丧失情景：
- ALS：60–70%患者运动皮层/脊髓EAAT2显著减少（PMID:38891774）
- 缺血：能量耗竭导致GLT-1反向运输，主动释放谷氨酸
- HD：突变huntingtin降低EAAT2表达

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 谷氨酸毒性的迟发相依赖Ca²⁺（两相模型） | 皮层神经元培养，选择性离子缺失实验 | PMID:2880938（Choi 1987） | 高（经典实验，多次重复） |
| 突触内NMDAR激活CREB/存活基因；突触外激活Jacob/DAPK1/死亡通路 | 神经元培养，选择性突触内/外NMDAR激活方案 | PMID:20842175（H&B 2010，PMC2948541） | 高（多个研究室验证）|
| MCU饱和→ROS→mPTP→死亡 | 线粒体成像，Ca²⁺染料，ROS探针，多种神经退行性模型 | PMID:35078537（Verma 2022，PMC8788129） | 中（不同模型和疾病中证据一致，但DCD的确切分子触发仍在研究中） |
| ALS中EAAT2丢失（60–70%患者） | 患者运动皮层和脊髓后死组织免疫组化/Western | PMID:38891774（Arnold 2024） | 高（多项独立病理研究确认） |
| PSD-95-nNOS偶联介导NMDAR→氧化应激的通路 | Tat-NR2B9c肽解耦合实验，神经保护验证 | PMID:18923045（Soriano 2008） | 高（体外；nerinetide临床试验部分验证） |

## 连接

- [[nmda-receptor]] — 兴奋毒性的主要Ca²⁺入口
- [[ltp]] — 正常NMDAR/Ca²⁺信号；兴奋毒性是其病理镜像
- [[glutamate-glutamine-cycle]] — GLT-1/EAAT2的谷氨酸清除是防止外突触激活的关键
- [[bdnf]] — 由突触内NMDAR/CREB上调；被外突触NMDAR下调
- [[huntingtons-disease]] — mtHtt增强外突触NMDAR，抑制CREB-PGC1α
- [[alzheimers-disease]] — Aβ寡聚体增强外突触NMDAR/DAPK1信号
- [[mitochondrial-dysfunction]] — 兴奋毒性的核心执行站；钙-ROS-mPTP三联体
- [[astrocyte-calcium-signaling]] — 星形胶质细胞GLT-1防线失守 = 兴奋毒性开始
- [[medium-spiny-neuron]] — HD中选择性脆弱的神经元（外突触NMDAR丰富）
- [[tripartite-synapse]] — 兴奋毒性发生的空间场景

## 未解问题

- **Q-exc-01**（中优先级）：mPTP的精确蛋白组成是什么？ANT-Cyclophilin D复合体是否是唯一的孔成分？SPATA18（线粒体精子样蛋白18）的作用？
- **Q-exc-02**（高优先级）：在慢性神经退行性疾病（PD、AD、ALS）中，亚致死性EMT与急性兴奋毒性的贡献如何区分？是否有可操作的生物标志物（如线粒体Ca²⁺探针的体内成像）？
- **Q-exc-03**（中优先级）：DAPK1特异性抑制剂能否在不影响DAPK1正常功能（自噬调控、肿瘤抑制）的情况下提供神经保护？DAPK1的激酶域与支架域的分工？

## 修订历史

- 2026-09-08 · 创建 · 基于《兴奋毒性：谷氨酸的双刃剑》(#138) · 初始置信度：高 · status: mainstream（多次独立验证的核心机制，但慢性病中EMT角色仍有争议）

## 来源文章

- [[2026-09-08-excitotoxicity-synaptic-extrasynaptic-calcium-death]]

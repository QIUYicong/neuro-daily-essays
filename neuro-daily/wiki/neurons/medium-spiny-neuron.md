---
title: 中型多棘神经元
slug: medium-spiny-neuron
domain: neurons
type: structure
status: established
confidence: high
created: 2026-09-01
updated: 2026-09-07
revision_count: 2
dimensions: [molecular, cellular, synaptic, microcircuit]
related: [basal-ganglia, striatal-direct-indirect-pathway, dopamine-reward-prediction-error, long-term-potentiation, ltd, endocannabinoid-system, parkinsons-disease, habit-vs-goal-directed, huntingtons-disease]
prerequisites: [action-potential, dopamine-reward-prediction-error, long-term-potentiation]
opens_questions: [Q-msn-d1d2-coexpression, Q-msn-primate-subtype-function, Q-hd-msn-d1d2-vulnerability]
source_articles: [2026-09-01-medium-spiny-neurons-striatum, 2026-09-07-huntingtons-disease-striatal-vulnerability-bdnf-polyglutamine]
key_sources: ["PMID:21469956", "PMID:31171839", "PMID:21906660", "PMID:34727523", "PMID:27373834", "PMID:37629202", "PMID:11298997"]
---

# 中型多棘神经元 (Medium Spiny Neuron, MSN)

> **一句话定义**：纹状体的主要投射神经元（占95%以上），以密布树突棘接收皮质谷氨酸输入和多巴胺调控，通过D1/D2受体分离的两条通路实现行动的"选择与压制"。

## 当前理解

我们现在认为，MSN是大脑将即时多巴胺信号（奖励预测误差）写入突触长期可塑性的核心细胞类型。它并非简单的"开关"，而是一个在分子、树突棘、回路三个层次上同时计算的复合决策单元。

D1型MSN（dMSN，直接通路）通过Gs-cAMP-PKA-DARPP-32级联促进LTP，强化刚刚被激活的皮质-纹状体突触；D2型MSN（iMSN，间接通路）通过Gi-内源大麻素（eCB）-CB1级联促进LTD，削弱竞争性行动的突触权重。两者协同，实现对行动选择的"双向刻写"。

单细胞转录组研究（灵长类）揭示了至少9种转录学独特的MSN亚型，挑战了传统的D1/D2二分框架；这些亚型的功能意义仍是主要研究前沿。

## 关键机制

### 形态特征
- 胞体约10–15μm，中等大小（介于大型胆碱能中间神经元和小型快放电中间神经元之间）
- 每个MSN：约5000–10000个树突棘
- 每个棘头部：一个皮质/丘脑谷氨酸突触 + 附近的多巴胺能突触（"三联体"结构）
- dMSN的树突比iMSN更长（约50%更多谷氨酸突触输入）

### 上行/下行状态（双稳特性）
- **下行态**（静息）：Kir2内向整流K+通道将膜电位维持在约-90mV（K+平衡电位），远离放电阈值（约-50mV）
- **上行态**：大量皮质输入同步激活AMPA/NMDA受体，膜电位上升至约-60mV并维持数百毫秒
- 多巴胺调节从下行→上行态的转换容易程度，而非直接触发放电

### D1受体信号（dMSN，直接通路）
D1 → Gs/Golf → 腺苷酸环化酶↑ → cAMP↑ → PKA激活 →
- DARPP-32磷酸化（Thr34）→ 抑制PP1 → CaMKII活跃 → AMPA受体突触插入（LTP）
- L型Ca²⁺通道（CaV1.2/1.3）开放增加
- K+通道（Kv4）抑制
- **净效应**：dMSN兴奋性升高；在与谷氨酸激活同时发生时诱发皮质-纹状体LTP

### D2受体信号（iMSN，间接通路）
D2 → Gi/o → 腺苷酸环化酶↓ → cAMP↓ → PKA↓ →
- L型Ca²⁺通道内流减少
- 内源大麻素（2-AG）逆向释放 → CB1受体 → 谷氨酸释放概率↓（eCB-LTD）
- **净效应**：iMSN兴奋性降低；在与谷氨酸激活同时发生时诱发皮质-纹状体LTD

### 奖励时的双向写入（完整机制）
1. 皮质输入 → dMSN和iMSN均进入上行态（两者均被激活）
2. 奖励 → VTA/SNc多巴胺释放（正RPE）
3. 多巴胺同时作用：dMSN D1-LTP（强化该行动）+ iMSN D2-LTD（压制竞争行动）

### HD中的选择性脆弱性

在亨廷顿病（HD）中，MSN是最先且最严重受损的神经元类型（纹状体神经元>90%最终死亡，Vonsattel 4级）。其选择性脆弱性由四层因素共同决定：

1. **营养依赖性不对称**：MSN自身BDNF转录水平极低，几乎完全依赖皮质衍生BDNF（经皮质纹状体谷氨酸能投射轴突末梢顺行释放）。mHTT破坏野生型huntingtin对REST的细胞质隔离，REST入核抑制皮层BDNF转录，MSN陷入营养饥饿（PMID:11408619）。

2. **NR2B富集的兴奋毒性敏感性**：MSN树突棘的NMDA受体以NR2B亚基为主，较NR2A亚基具有更慢的去激活动力学（更长的Ca²⁺内流窗口）。叠加星形胶质细胞GLT1/GLAST下调导致的谷氨酸清除障碍，MSN承受慢性兴奋毒性Ca²⁺超载。

3. **转录失调靶向性**：REST调控子在纹状体MSN中尤为丰富（DARPP-32、神经肽Y等纹状体标志基因含RE1元件）；CBP（CREB结合蛋白）被mHTT N端片段隔离入核内包涵体，进一步削减纹状体特异性基因表达及线粒体生物合成（PGC-1α轴）。

4. **体细胞CAG不稳定性**：纹状体MSN中HTT基因的CAG重复序列随年龄体细胞扩展程度高于其他脑区，导致MSN中实际polyQ毒性最重。

胆碱能中间神经元和PV+快放电中间神经元在HD晚期相对豁免，反向验证了上述机制（PMID:37629202; PMID:11298997）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| D1 MSN激活→丘脑/运动皮质兴奋；D2 MSN激活→丘脑/运动皮质抑制 | 光遗传学fMRI（ofMRI），AAV-ChR2选择性激活 | PMID:27373834 (PMC5528162) | 高 |
| dMSN树突比iMSN长，接受约50%更多谷氨酸突触 | 解剖测量 + BAC转基因小鼠标记 | PMID:21906660 (PMC3235731) | 高 |
| 多巴胺耗竭后选择性iMSN（D2）树突棘丧失30-50% | 动物模型 + 人类帕金森尸检 | PMID:18267246 (PMC4820336) | 高 |
| DMS损伤→目标导向行为退化为习惯；DLS损伤→无法形成习惯 | 靶向损伤 + 行为测试（小鼠） | PMID:31171839 (PMC7231228) | 高 |
| 灵长类纹状体≥9种转录学MSN亚型 | 单细胞RNA测序（恒河猴） | PMID:34727523 (PMC9359438) | 高（分类）/ 低（功能意义） |
| 多巴胺信号可在行动后1秒内有效触发LTP | 体外切片 + 体内光遗传学 | PMID:37841525 (PMC10572094) | 中 |

## 连接

- [[basal-ganglia]] — MSN是纹状体的主要输出细胞，构成基底节的输入端
- [[striatal-direct-indirect-pathway]] — D1/D2 MSN分别组成直接/间接通路
- [[dopamine-reward-prediction-error]] — 多巴胺RPE信号是MSN突触可塑性的"教学信号"
- [[long-term-potentiation]] — D1-MSN通过DARPP-32-AMPA插入机制实现纹状体LTP
- [[ltd]] — D2-MSN通过eCB-CB1机制实现纹状体LTD
- [[endocannabinoid-system]] — eCB是D2-MSN LTD的逆行信使
- [[parkinsons-disease]] — 多巴胺缺失导致D2-MSN选择性树突棘丧失
- [[huntingtons-disease]] — HD中MSN是选择性脆弱的靶细胞（BDNF营养剥夺+NR2B兴奋毒性+转录失调+体细胞CAG扩展四重打击）
- [[action-potential]] — 上行态是MSN放电的前提，受Kir2通道调控

## 未解问题

- Q-msn-d1d2-coexpression：D1/D2共表达MSN的功能意义是什么？它们是否构成第三条通路？
- Q-msn-primate-subtype-function：灵长类9种MSN亚型各自的功能角色是什么？D1-NUDAP是否真的是享乐热点？
- Q-hd-msn-d1d2-vulnerability：HD中iMSN（D2型）是否比dMSN（D1型）更早退化？经典成人型HD（舞蹈症）与青少年型HD（肌强直为主）的症状差异是否反映了D1/D2-MSN不同的退化时序？

## 修订历史

- 2026-09-01 · 创建 · 基于《纹状体的决策细胞》文章 · 来源：9篇PMC开放全文 · 初始置信度：高
- 2026-09-07 · 修订 rev2 · 基于《亨廷顿病：纹状体选择性脆弱性》文章 (#137) · 新增HD选择性脆弱性机制节（BDNF-REST轴/NR2B兴奋毒性/转录失调/体细胞CAG不稳定）；related新增huntingtons-disease；opens_questions新增Q-hd-msn-d1d2-vulnerability；key_sources新增PMID:37629202/11298997

## 来源文章

- [[2026-09-01-medium-spiny-neurons-striatum]]
- [[2026-09-07-huntingtons-disease-striatal-vulnerability-bdnf-polyglutamine]]

---
title: 帕金森病
slug: parkinsons-disease
domain: diseases
type: disease
status: established
confidence: high
created: 2026-06-14
updated: 2026-09-09
revision_count: 3
dimensions: [molecular, cellular, microcircuit, brain-region, whole-brain-network, behavior, cognition, disease]
related: [dopamine-reward-prediction-error, basal-ganglia, beta-oscillations, alzheimers-disease, alpha-synuclein, voltage-gated-calcium-channels, ltp, mitochondrial-dysfunction, pink1-parkin-mitophagy]
prerequisites: [dopamine-reward-prediction-error, basal-ganglia, synaptic-transmission]
opens_questions: [Q-pd-beta-causality, Q-pd-closed-loop-dbs, Q-pd-lewy-protective, Q-pd-snc-vulnerability]
source_articles: [2026-06-14-parkinson-basal-ganglia-circuit, 2026-09-01-medium-spiny-neurons-striatum, 2026-09-09-mitochondrial-dysfunction-neurodegeneration]
key_sources: ["PMID:21469956", "PMID:2479133", "PMID:2402638", "PMID:34124057", "PMID:38954651", "PMID:30897356", "PMID:18267246", "PMID:38241161", "PMC10903104", "PMID:36943668", "PMID:33168089", "PMC7654589"]
---

# 帕金森病 (Parkinson's Disease)

> **一句话定义**：黑质致密部多巴胺神经元的选择性死亡导致基底节直接/间接通路失衡——间接通路过度激活、GPi/SNr过度抑制丘脑——产生运动减少、僵直和震颤；其回路特征是β振荡（13-30 Hz）的病理性增强，阻断运动意图的实施。

## 当前理解

我们现在认为，帕金森病（PD）的核心运动症状根植于一个精确的回路失衡，而不仅仅是多巴胺的化学缺失。这一区别至关重要：多巴胺的丧失引发了基底节回路的振荡状态改变，而正是这种振荡状态——而非简单的"缺少一种化学物质"——直接导致了运动减少。

**发病机制（多层面）**：

1. **分子层面**：α-突触核蛋白错误折叠→寡聚体/路易小体积累→线粒体、蛋白酶体、自噬三重功能障碍→黑质致密部（SNc）多巴胺神经元死亡

2. **回路层面**：SNc多巴胺耗竭→纹状体D1（直接通路）失活 + D2（间接通路）脱抑制→GPi/SNr过度活跃→丘脑-皮层通路持续受抑→运动发起失败

3. **振荡层面**：多巴胺缺失使基底节-皮层回路陷入β频段（13-30 Hz）同步振荡，这种"抗运动"模式主动阻断运动意图的皮层-STN执行

**临床表现**（四主征）：
- 运动迟缓（bradykinesia）：启动困难，动作缓慢
- 肌肉强直（rigidity）：铅管样/齿轮样阻力
- 静止性震颤（rest tremor）：3-5 Hz，运动时减轻
- 姿势不稳（postural instability）：晚期表现

**前驱期症状**（运动症状前5-20年）：嗅觉丧失、便秘、快速眼动睡眠行为障碍（RBD）——对应Braak I-II期（肠神经系统/嗅球受累阶段）

## 关键机制

### α-突触核蛋白病理

正常α-突触核蛋白是突触前调节蛋白（SNARE相互作用、酪氨酸羟化酶调控）。病理聚集：单体→寡聚体→原纤维→路易小体。神经毒性经由三条路径（Ray 2021）：
1. 线粒体复合物I抑制→ROS升高→能量危机
2. 蛋白酶体20S/26S抑制→蛋白积累毒性
3. Rab1A抑制→自噬失能

朊蛋白样扩散：聚集α-突触核蛋白可通过突触跨细胞传递，与Braak分期的解剖进展吻合（ENS→延髓→SNc→边缘→新皮层）。

### 回路失衡：Albin-DeLong框架

**直接通路（促进运动）**：dSPNs（D1受体）→ GPi/SNr（抑制）→ 丘脑去抑制 → 皮层激活  
**间接通路（抑制运动）**：iSPNs（D2受体）→ GPe（抑制）→ STN（兴奋）→ GPi/SNr（激活）→ 丘脑抑制

多巴胺的平衡效应：D1促进直接通路活跃，D2抑制间接通路活跃。DA耗竭使两个效应同时反转：直接通路减弱（运动油门失效）+ 间接通路增强（运动刹车卡死）。

分子细节（Gerfen & Surmeier 2011；Day et al. 2008）：DA耗竭后**iSPNs（间接通路，D2-MSN）树突棘选择性丧失30-50%**，而dSPNs（直接通路，D1-MSN）基本不受影响——机制为D2受体对CaV1.3 L型钙通道的抑制解除→Ca²⁺内流急增→CaMKII过激活；皮质输入的继续驱动对棘丧失是必要的（去皮质可阻断该过程）。重要：L-DOPA治疗**无法恢复已丢失的树突棘**（棘丧失不可逆）。这些结构变化解释了左旋多巴长期治疗后的疗效波动，以及为何运动减少是PD的核心症状（间接通路MSN过度活跃、直接通路MSN突触驱动减弱的净效应）。

### β振荡与治疗机制

多巴胺缺失时STN和基底节-皮层回路呈现13-30 Hz的β振荡主导，该状态与运动减少症状强度正相关。

**Köhler et al. 2024的关键发现**：左旋多巴和STN-DBS通过相同的机制改善运动——均将皮层-STN耦合从β（13-35 Hz）切换到θ（4-10 Hz）；这一切换将运动意图到执行的延迟缩短约270-360 ms（UPDRS-III评分改善~10分）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 直接通路dSPNs富含D1，间接通路iSPNs富含D2 | BAC转基因小鼠（eGFP+膜片钳） | PMID:21469956 | 高 |
| STN损毁逆转MPTP帕金森猴的运动减少/僵直/震颤 | MPTP猴模型+立体定向手术 | PMID:2402638 | 高 |
| 双通路失衡模型（运动减少vs运动过多） | 人类/灵长类回路研究综合 | PMID:2479133, PMID:1695404 | 高 |
| α-突触核蛋白朊蛋白样扩散与Braak分期 | 神经病理学+PD患者神经元移植研究 | PMID:34124057 | 中 |
| OFF状态β振荡与运动迟缓相关 | STN-DBS患者LFP记录（n=15） | PMID:20463229 | 高 |
| DA和DBS共享β→θ切换治疗机制 | 同时ECoG+STN-LFP记录（n=25） | PMID:38954651 | 中-高 |
| DA耗竭后iSPNs（D2-MSN）选择性树突棘丧失30-50%（dSPNs基本不受影响）；L-DOPA治疗不可逆转 | 大鼠/小鼠6-OHDA模型+Thy-YFP骨架标记 | PMID:18267246 (PMC4820336) | 高（动物模型）/ 中（人类推广） |

## 连接

- [[basal-ganglia]] — 直接/间接通路回路（PD的核心受损回路）
- [[dopamine-reward-prediction-error]] — SNc多巴胺神经元同时承担RPE和运动控制功能
- [[beta-oscillations]] — PD的病理振荡状态
- [[alzheimers-disease]] — 同为神经退行性疾病，共享Aβ-LTP损害 vs α-syn-回路失衡的不同病理路径
- [[voltage-gated-calcium-channels]] — CaV1.3（L型钙通道）是SNc自主起搏的关键，与SNc脆弱性相关
- [[ltp]] — 多巴胺耗竭改变基底节突触可塑性（dSPNs偏向LTD，iSPNs偏向LTP）
- [[medium-spiny-neuron]] — iSPN（D2-MSN）是PD中选择性结构受损的细胞
- [[striatal-direct-indirect-pathway]] — 直接/间接通路失衡是PD运动症状的核心回路机制

## 未解问题

- Q-pd-beta-causality：β振荡是PD运动症状的直接原因还是结果？
- Q-pd-closed-loop-dbs：基于实时β监测的闭环DBS是否优于持续DBS？
- Q-pd-lewy-protective：路易小体是保护性隔离还是毒性机制？
- Q-pd-snc-vulnerability：降低CaV1.3活性能否保护SNc神经元免于死亡？
- Q-pd-dbs-theta-mechanism：DBS诱导θ耦合的具体回路机制（STN→GPe/GPi/皮层哪一路径主导？）

## 修订历史

- 2026-06-14 · 创建 · 基于《多巴胺的沉默与节律的失控》一文 · 初始置信度：高
- 2026-09-01 · 修订 rev2 · 基于《纹状体的决策细胞》一文（#131）· 修正：原文误将树突棘丧失归于dSPNs（D1-MSN），新证据（PMID:18267246）明确为iSPNs（D2-MSN）选择性受损30-50%；新增L-DOPA不可逆性说明；添加medium-spiny-neuron和striatal-direct-indirect-pathway连接
- 2026-09-09 · 修订 rev3 · 基于《线粒体功能障碍：神经元高能耗的代价》（#139）· 补充：(1) PD 中 Complex I 缺陷的多来源证据（黑质死后脑研究 + MPTP/鱼藤酮毒理学模型）；(2) DA 神经元多重叠加脆弱性（CaV1.3 自主节律钙负荷 + 超长无髓轴突 + DA 代谢本底 ROS）；(3) PINK1/*PARK6* 和 Parkin/*PARK2* 基因突变与早发性 PD 的关系；(4) related 新增 mitochondrial-dysfunction 和 pink1-parkin-mitophagy；(5) key_sources 新增 5 个来源

## 来源文章

- [[2026-06-14-parkinson-basal-ganglia-circuit]]
- [[2026-09-01-medium-spiny-neurons-striatum]]
- [[2026-09-09-mitochondrial-dysfunction-neurodegeneration]]

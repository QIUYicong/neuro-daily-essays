---
title: 阿尔茨海默病
slug: alzheimers-disease
domain: diseases
type: disease
status: established
confidence: high
created: 2026-06-08
updated: 2026-07-10
revision_count: 8
dimensions: [molecular, synaptic, cellular, microcircuit, brain-region, whole-brain-network, cognition, disease]
related: [amyloid-beta-oligomers, ltp, nmda-receptor, hippocampal-circuit, memory-consolidation, engram-cells, theta-oscillations, synaptic-tagging-capture, bdnf, default-mode-network, adult-neurogenesis, tau-pathology, microglia, complement-cascade-cns, synaptic-pruning, glymphatic-system, aqp4, hpa-axis, glucocorticoid-hippocampus-plasticity, circadian-clock, neuroinflammation, inflammatory-cytokines-synapse]
prerequisites: [ltp, nmda-receptor, hippocampal-circuit, memory-consolidation]
opens_questions: [Q-ad-vulnerable-synapses, Q-ad-tau-cascade, Q-ad-intervention-window, Q-nmda-alzheimer, Q-glyph-01, Q-glyph-02, Q-stress-02]
source_articles: [2026-06-08-alzheimers-amyloid-synaptic-mechanism, 2026-06-16-default-mode-network, 2026-06-03-microglia-synaptic-pruning, 2026-07-06-glymphatic-system-sleep-clearance, 2026-07-09-stress-glucocorticoid-hippocampus-hpa-axis]
key_sources: ["PMID:1789684", "PMID:11932745", "PMID:17360908", "PMID:21543591", "PMID:22762015", "PMID:20581818", "PMID:26871627", "PMID:41929946", "PMID:30190379", "PMID:1759558", "PMID:26691836", "PMID:22365544", "PMID:27033548", "PMID:22896675", "PMID:30679382", "PMID:19779148", "PMID:41593094", "PMID:3527687", "PMID:15891777", "PMID:10195112"]
---

# 阿尔茨海默病 (Alzheimer's Disease, AD)

> **一句话定义**：最常见的神经退行性疾病，核心病理机制是可溶性Aβ寡聚体通过多条分子通路瓦解海马突触可塑性（特别是LTP），导致情景记忆选择性丧失；斑块是伴随病理而非主要毒性物种。

## 当前理解

我们现在认为，AD的早期认知损伤主要来自**突触功能失效**（特别是海马CA3-CA1突触的LTP能力丧失），而非神经元的死亡。核心毒性物种是**可溶性Aβ寡聚体**（2-12个Aβ单体的小聚合物），它们通过至少五条并行分子通路拆解海马突触可塑性机器：

1. **PrPC/mGluR5/Fyn/NR2B轴**：Aβ与细胞表面PrPC蛋白结合 → 激活mGluR5 → 激活Fyn激酶 → NR2B磷酸化 → 通道开放时间延长 → 异常持续Ca²⁺内流
2. **突触外NR2B/p38 MAPK通路**：Aβ优先激活突触外（而非突触内）NR2B-NMDA受体 → p38 MAPK → CREB去磷酸化 → LTP所需基因表达阻断
3. **钙调磷酸酶/AMPA内吞**：慢性Ca²⁺过载 → calcineurin/PP1过激活 → GluA1 Ser845去磷酸化 → AMPA受体大量内吞 → 突触强度崩解；CaMKII活性降低约60%
4. **BDNF/TrkB截断**：BDNF表达下调+TrkB信号抑制 → 晚期LTP所需蛋白合成被阻断；proBDNF积累通过p75NTR主动促进棘收缩
5. **tau错位至突触后**：Aβ诱发的tau过磷酸化 → tau错位至树突棘 → PSD-95置换/AMPA受体失锚 → GluA1顺行运输受阻

在回路层面：SST+中间神经元功能受损 → theta振荡减弱（theta-gamma耦合损伤甚至早于Aβ大量产生）→ LTP时间门控关闭，形成"双重锁定"（分子机器拆除 + 驱动机器的节律器损坏）。

关键量化数据：
- 突触密度与认知测量相关r=0.96（Terry et al. 1991），斑块贡献仅26%
- 100-300 pM天然Aβ二聚体/三聚体在15天内引发~75%树突棘密度丢失（早期可逆）

靶向Aβ寡聚体（而非斑块）的抗体药物在早期AD中减缓认知衰退，而斑块清除量与认知获益不相关（"斑块清除悖论"），反向验证了寡聚体假说。

## 关键机制

### 病理阶段概览

AD的分子时间轴（简化）：
1. **沉默期**（症状前10-20年）：Aβ产生与清除失衡 → 可溶性Aβ寡聚体积累（无明显症状）
2. **突触沉默期**（轻度认知障碍 MCI）：寡聚体达到毒性浓度 → 海马突触LTP失效 → 情景记忆逐渐下降
3. **回路失调期**（轻-中度AD）：抑制性中间神经元损伤 → 振荡失调 + 过度兴奋 → 更多tau磷酸化 + 更多Aβ产生
4. **神经元死亡期**（中-重度AD）：tau纤维缠结 → 神经元死亡 → 不可逆认知衰退

### Aβ的来源与聚合形式

Aβ由APP（淀粉样前体蛋白）通过β-分泌酶（BACE1）和γ-分泌酶顺序切割产生。主要形式：
- **Aβ40**：40个氨基酸，溶解度相对高，主要形式
- **Aβ42**：42个氨基酸，疏水性更强，更易寡聚化；与AD关联更紧密

聚合谱：单体 → 寡聚体（2-12聚体，高毒性）→ 原纤维 → 淀粉样纤维 → 老年斑（不溶性聚合体，低直接毒性）

### 胶质淋巴清除失效：AD 的上游功能原因（新增 2026-07-06）

AD 病理的核心是"Aβ/tau 清除 < 产生"，而胶质淋巴系统是 Aβ 和 tau 清除的主要功能通路之一。衰老导致以下三重胶质淋巴衰退，使 Aβ/tau 积累从第一天起就偏向积累：

1. **深度 NREM 睡眠减少**：慢波睡眠随年龄减少至 25 岁时的 30–40%，蓝斑核 NE 振荡驱动的清洗窗口相应缩短
2. **AQP4 去极化**：AQP4 从星形胶质细胞终足漂移，CSF-ISF 交换效率下降，老年小鼠 Aβ 清除降低约 40%（PMID:25204284）
3. **动脉弹性下降**：脑动脉硬化减弱血管搏动，胶质淋巴泵力减弱约 27%

**蓝斑核的双重角色**：蓝斑核（LC）是 AD tau 病理最早侵犯的区域（Braak 零期），LC NE 神经元早期 tau 积累 → LC 受损 → NREM 期 NE 振荡减弱 → 胶质淋巴清洗减少 → 更多 tau/Aβ 积累 → 更多 LC 损伤，构成完美的自催化恶性循环（Holth et al. 2019, PMID:30679382）。

**睡眠剥夺实验**：一夜不睡使人类 CSF tau 升高 >50%（PMID:30679382）；ISF Aβ 在清醒时比睡眠时高约 24.4%（Kang et al. 2009, PMID:19779148）。慢性睡眠限制显著加速转基因 AD 小鼠的斑块形成。

**人类直接证据**：随机交叉试验（n=39）证明，正常睡眠后血浆 Aβ/tau 高于睡眠剥夺后，直接证明睡眠期间大脑将这些蛋白清至血液（Dagum et al. 2026, PMID:41593094）。

### 糖皮质激素级联假说与 AD（新增 2026-07-09）

除 Aβ/tau 直接病理外，**慢性皮质醇升高**是 AD 风险的独立促进因素，两条路径收敛：

**路径一：SCN 退化 → 皮质醇节律崩溃**（AD 特有机制）
- AD 早期 SCN VIP 神经元萎缩（Braak 0-I 期即有记录）→ 皮质醇昼夜节律振幅↓ + 基础水平升高
- 皮质醇昼夜节律破坏 → MR/GR 系统节律性工作模式丧失 → 慢性 GR 过激活

**路径二：慢性 GR 激活 → 海马加速损伤**
- GR 过激活 → BDNF exon IV↓ + GluA1 内吞↑ + CA3 树突退缩 → 海马对 HPA 轴的负反馈减弱
- 海马负反馈减弱 → 皮质醇进一步升高（Sapolsky 1986 糖皮质激素级联假说，PMID:3527687）
- 皮质醇升高 → 进一步损害海马 → 正反馈循环

**汇聚点**：在 Aβ 毒性基础上叠加 GC 级联 → 双重攻击 → 加速从 MCI 向 AD 进展；Conrad（2008）"脆弱性"框架：CA3 树突退缩后神经元对兴奋性毒性的易感性增大 2 倍以上，此时 Aβ 诱发的 Ca²⁺ 过载将产生更大损伤。

**人类纵向证据**：5 年随访中皮质醇升高预测海马萎缩 + 记忆损害（Lupien et al. 1998，PMID:10195112，Nature Neuroscience）；Cushing 综合征（慢性皮质醇极高）显示显著海马萎缩，手术纠正后体积部分恢复（可逆性证据）。

**未解因果问题**（→ Q-stress-02）：慢性皮质醇升高究竟是 AD 发病的危险因素（因），还是 SCN 萎缩 + 海马损伤 + HPA 失调的结果（果）？目前横断面证据多，真正的因果时序尚待明确。

### 神经炎症：AD 突触损伤的早期共同驱动力（新增 2026-07-10）

除 Aβ 直接毒性、GC 级联和胶质淋巴清除失效外，**神经炎症**是 AD 突触丢失的第四条关键路径，且时序上可能最早——早于斑块出现，早于 tau 大量磷酸化：

**Aβ → 补体重激活 → 小胶质细胞过度剪枝**：
- 可溶性 Aβ 寡聚体（AD 最早期）激活经典补体通路：C1q 在突触上沉积，触发 C3 → C3b 调理素化
- 小胶质细胞通过 CR3 识别 C3b 标记突触 → 物理吞噬突触末梢
- 这是**斑块出现前**的早期突触丢失机制（Hong et al. 2016，PMID:27033548）
- 抗 C1q 中和或 CR3 阻断：在 AD 早期模型中保护突触密度（早期干预意义）

**小胶质细胞→慢性 TNF-α/IL-1β → 突触可塑性抑制**：
- AD 小胶质细胞分泌过量 TNF-α（尤其是携带 TREM2 R47H 等位基因的小胶质细胞）
- 过量 TNF-α 通过 TNFR1/NF-κB 路径：GluA1 内吞↑ + LTP 损伤（详见 [[inflammatory-cytokines-synapse]]）
- 慢性应激（HPA 轴/GC）→ 小胶质细胞预激 → 对 Aβ 刺激的炎症放大，形成"应激 × Aβ 的神经炎症协同"

**TREM2：早期保护还是晚期损伤？**
- 早期 AD（低 Aβ 负荷）：TREM2 依赖的 DAM 状态清除过活跃突触（ePtdSer 信号），保护作用
- TREM2 功能缺失变体（R47H）→ 无法清除过活跃突触 → 兴奋毒性风险↑ + TNF-α 额外升高
- 晚期 AD（高 Aβ 负荷）：DAM 持续激活 → 炎症因子量增大 → 突触损伤为主

**三重神经炎症协同**（新模型）：
```
慢性应激（HPA/GC/CRH）
    ↓ 小胶质细胞预激
         ↓        ×
           Aβ 寡聚体
              ↓ 超量 TNF-α/IL-1β
                   ↓
       LTP 损伤 + 突触丢失（早于斑块）
           ↓
     认知下降提前启动
```

### 为什么海马首当其冲

1. **高NR2B密度**：CA3-CA1突触（Schaffer侧支）的NMDA受体中NR2B亚基比例高，对Aβ的毒性通路（突触外NR2B激活）敏感性高
2. **LTP依赖性**：情景记忆严重依赖CA3-CA1 NMDA-LTP，这是Aβ的首要攻击对象
3. **内嗅皮层→海马是Aβ传播早期通路**（对应Braak I-II期神经原纤维缠结分布），APP高表达神经元（内嗅皮层II层细胞）是最早被波及的区域

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 突触密度（非斑块）是AD认知衰退主要预测因子 | 免疫组化量化+神经心理测试，r=0.96 | Terry et al. 1991, PMID:1789684 | 高 |
| 天然分泌Aβ寡聚体抑制体内海马LTP | 海马内注射+大鼠在体电生理 | Walsh et al. 2002, PMID:11932745 | 高 |
| 100-300 pM Aβ二/三聚体引发75%棘丢失，可逆 | 活体细胞成像，撤药后恢复 | Shankar et al. 2007, PMID:17360908 | 高 |
| 突触外NR2B/p38 MAPK是Aβ阻断LTP的关键通路 | NR2B阻断剂救援LTP；脑片电生理+生化 | Li et al. 2011, PMID:21543591 | 高 |
| theta-gamma耦合损伤早于Aβ大量产生 | 转基因AD鼠海马场电位记录 | Goutagny et al. 2013, PMID:23773058 | 中 |
| 靶向Aβ寡聚体（非斑块）抗体减缓早期AD认知衰退 | 随机双盲3期临床试验 | 综述 PMC:8231952 | 高（临床） |

## 连接

- [[amyloid-beta-oligomers]] — Aβ寡聚体是AD的核心毒性物种，本条目的分子主角
- [[ltp]] — 受Aβ攻击的主要突触可塑性机制；LTP失效是AD早期认知衰退的突触基础
- [[nmda-receptor]] — LTP攻击的核心分子靶标（突触外NR2B激活是关键通路）
- [[hippocampal-circuit]] — AD最早、最严重损伤的回路结构（CA3-CA1，内嗅皮层-海马通路）
- [[memory-consolidation]] — AD损害记忆巩固的系统机制（快速眼动/SWR期间重激活依赖于突触强度差异）
- [[engram-cells]] — AD早期的"沉默印迹"：印迹细胞拓扑保留但突触强度被Aβ压低（Roy et al. 2016光学恢复实验）
- [[theta-oscillations]] — theta振荡是LTP的时间门控，AD早期theta-gamma耦合损伤关闭了LTP诱导窗口
- [[synaptic-tagging-capture]] — Aβ通过截断BDNF-TrkB，阻断了STC机制中的蛋白合成捕获步骤
- [[bdnf]] — AD 早期 BDNF/TrkB 信号受损（Aβ截断 TrkB→CREB 轴）；BDNF+神经发生协同干预可改善认知（Choi 2018）
- [[adult-neurogenesis]] — AD 中 SGZ 神经发生早于病理发生下降（Moreno-Jiménez 2019）；恢复神经发生+BDNF 可改善认知
- [[tau-pathology]] — AD 的第二条核心损伤通路：tau 过磷酸化（CDK5/GSK-3β）→ 树突棘错位 → 突触毒性 → PHF/NFT → 跨突触 Braak 分期蔓延；NFT 比斑块更能预测认知衰退（Braak & Braak 1991）
- [[microglia]] — Aβ 低聚体触发补体 C1q 在突触上的病理性沉积，激活小胶质细胞通过 CR3 过度吞噬突触（早于斑块形成）；抗 C1q 干预可保护 AD 早期突触（Hong et al. 2016）
- [[complement-cascade-cns]] — 发育期突触剪枝机制的病理性重激活是 AD 早期突触丢失的机制之一
- [[synaptic-pruning]] — 补体-微胶质突触剪枝的异常重激活导致斑块出现前的突触前丢失
- [[glymphatic-system]] — 胶质淋巴清除失效是 Aβ/tau 积累的功能上游原因；睡眠剥夺和衰老通过三重机制削弱清洗，与 AD 形成双向恶性循环
- [[aqp4]] — AQP4 去极化在老年脑中导致胶质淋巴效率下降；可能是 AD 预防干预的靶点
- [[hpa-axis]] — AD 早期 SCN 退化→皮质醇节律崩溃→HPA 失调是 AD 的独立风险放大器；海马受损后 HPA 负反馈减弱形成正反馈恶化循环
- [[glucocorticoid-hippocampus-plasticity]] — 慢性 GR 激活（因 SCN 萎缩引发皮质醇节律崩溃）叠加 Aβ 毒性，双重攻击海马 LTP 和结构完整性
- [[circadian-clock]] — SCN VIP 神经元萎缩是 AD 最早期事件之一；昼夜节律崩溃通过皮质醇节律失调和胶质淋巴清洗减少双重路径促进 AD 进展
- [[neuroinflammation]] — 神经炎症是 AD 早期突触丢失的独立驱动力：Aβ→补体→小胶质 CR3 过度剪枝（早于斑块）；慢性 TNF-α/IL-1β 损伤 LTP；与 GC 级联协同放大
- [[inflammatory-cytokines-synapse]] — 高浓度 TNF-α（TNFR1/NF-κB/GluA1 内吞）和 IL-1β（p38/GluA1+NR2B 减少）的 LTP 损伤机制在 AD 中被 Aβ+小胶质激活所触发

## 未解问题

- Q-ad-vulnerable-synapses：为什么CA3-CA1突触（而非纹状体或小脑突触）特别脆弱？分子因素（高NR2B）+ 几何因素（内嗅皮层传播路径）是否足以解释？
- Q-ad-tau-cascade：Aβ如何在时序上触发tau病理？Aβ-tau正反馈放大环（Aβ→Ca²⁺过载→tau磷酸化→突触损伤→更多Aβ）的分子细节？
- Q-ad-intervention-window：突触损伤的可逆阶段（Shankar 2007的"5天恢复"）在人类AD中对应多长时间？"早期干预"的黄金窗口的分子标志物是什么？
- Q-nmda-alzheimer：突触内vs突触外NR2B的比例是否在AD中发生漂移？是否是治疗靶点（选择性增强突触内NR2B、抑制突触外NR2B）？

## 修订历史

- 2026-06-08 · 创建 · 基于《记忆的分子遗忘》一文 · 建立AD疾病页，聚焦Aβ寡聚体-突触可塑性损伤通路 · 初始置信度：高
- 2026-06-28 · 修订 rev2 · 基于《BDNF》文章 (#64) · 修正 related 中的 `bdnf-trkb`（错误 slug）为 `bdnf`（已建页）；新增 adult-neurogenesis 连接；补充 BDNF+AHN 协同干预 AD 认知的 Choi 2018 证据（PMID:30190379）；key_sources 新增 PMID:30190379
- 2026-06-16 · 修订 rev3 · 基于《默认模式网络》一文 · 新增：Aβ 优先沉积 DMN 枢纽节点（PCC/mPFC）的功能解剖解释（Buckner 2009）；related 新增 default-mode-network；dimensions 新增 whole-brain-network
- 2026-06-29 · 修订 rev4 · 基于《tau 蛋白病理》一文（第 65 篇）· related 新增 tau-pathology；key_sources 新增 Braak 1991 (PMID:1759558)、Zempel 2015 (PMID:26691836)、de Calignon 2012 (PMID:22365544)；在"连接"段落新增 tau-pathology 节点
- 2026-06-03 · 修订 rev5 · 基于《大脑的"质检员"》一文（第 70 篇）· 补充 C1q/补体-微胶质突触剪枝机制（Hong et al. 2016）：Aβ低聚体触发C1q早期突触沉积（早于斑块），CR3阻断保护突触；related 新增 microglia/complement-cascade-cns/synaptic-pruning；key_sources 新增 PMID:27033548
- 2026-07-06 · 修订 rev6 · 基于《大脑的"垃圾清运"》一文（第 75 篇）· 新增胶质淋巴清除失效段落（三重衰退机制：NREM 减少/AQP4 去极化/动脉弹性下降）；蓝斑核双重角色（LC tau 早期积累→NREM 振荡↓→清洗↓）；相关人类证据（Dagum 2026、Holth 2019）；related 新增 glymphatic-system、aqp4
- 2026-07-09 · 修订 rev7 · 基于《应激的双刃剑》(#77) · 新增"糖皮质激素级联假说与 AD"段落（SCN 退化→皮质醇节律崩溃→慢性 GC→海马损伤→负反馈减弱的正反馈环；AD 特有的双重攻击汇聚机制；Lupien 1998 人类纵向证据）；related 新增 hpa-axis、glucocorticoid-hippocampus-plasticity、circadian-clock；key_sources 新增 PMID:3527687、PMID:15891777、PMID:10195112；opens_questions 新增 Q-stress-02；连接新增三条
- 2026-07-10 · 修订 rev8 · 基于《当卫士变成刽子手》(#78) · 新增"神经炎症：AD 突触损伤的早期共同驱动力"段落（Aβ→补体重激活→小胶质 CR3 过度剪枝；TREM2 保护性 vs 损伤性双重角色；慢性应激×Aβ 的神经炎症协同模型）；related 新增 neuroinflammation、inflammatory-cytokines-synapse；连接新增两条

## 来源文章

- [[2026-06-08-alzheimers-amyloid-synaptic-mechanism]]
- [[2026-07-09-stress-glucocorticoid-hippocampus-hpa-axis]]
- [[2026-07-10-neuroinflammation-synaptic-damage]]

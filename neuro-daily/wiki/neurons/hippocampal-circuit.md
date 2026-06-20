---
title: 海马回路
slug: hippocampal-circuit
domain: neurons
type: structure
status: established
confidence: high
created: 2026-05-28
updated: 2026-08-14
revision_count: 12
dimensions: [brain-region, microcircuit, cognition, disease]
related: [place-cell, grid-cell, dendritic-computation, ltp, hebbian-learning, btsp, engram-cells, theta-oscillations, memory-consolidation, pv-interneurons, sst-interneurons, alzheimers-disease, amyloid-beta-oligomers, default-mode-network, pattern-completion, pattern-separation, attractor-network, complementary-learning-systems, glucocorticoid-stress-memory, hpa-axis, time-cells, temporal-context-model, ca2-hippocampus, social-memory, sharp-wave-ripples]
prerequisites: [synaptic-transmission, ltp, action-potential]
opens_questions: [Q-ca2-function, Q-ca2-pnn-plasticity-window, Q-ca2-disease-mechanism, Q-hippocampal-consolidation-mechanism, Q-ad-vulnerable-synapses, Q-gc-02, Q-tc-01, Q-tc-02, Q-tc-04]
source_articles: [2026-05-28-place-cells-btsp, 2026-05-31-engram-cells-optogenetic-proof, 2026-06-08-alzheimers-amyloid-synaptic-mechanism, 2026-06-16-default-mode-network, 2026-06-17-sharp-wave-ripples-memory-replay, 2026-06-24-hippocampal-ca3-pattern-completion, 2026-07-09-glucocorticoids-stress-memory-amygdala, 2026-08-04-hippocampal-time-cells-episodic-memory, 2026-08-14-ca2-hippocampus-social-memory-temporal-context]
key_sources: ["PMID:32042144", "PMID:18007020", "PMID:18284371", "PMID:39454575", "PMID:26135716", "PMID:23354386", "PMID:1789684", "PMID:20581818", "PMID:35040779", "PMID:12040087", "PMID:15272123", "PMID:1308182", "PMID:21460835", "PMID:9405958", "PMID:7729802", "PMID:21867888", "PMID:33431691", "PMID:29706516", "PMID:24572357", "PMID:27593179", "PMID:31874067", "PMID:34201943", "PMID:24863146"]
---

# 海马回路 (Hippocampal Circuit)

> **一句话定义**：海马由齿状回（DG）、CA3、CA1（及下托）四个亚区串行连接构成三突触回路，并行接受内嗅皮层（EC）输入，共同实现空间记忆的编码、模式分离、模式补全和输出。

## 当前理解

我们现在认为，海马回路并非简单的串行管道，而是一个**多路并行、功能分工**的网络。经典的"三突触回路"（EC→DG→CA3→CA1）是主要路径之一，但内嗅皮层还通过穿孔通路直接与 CA1 和 CA3 相连（bypass path），使不同类型的记忆可以通过不同路径编码。

各亚区的核心计算功能：
- **DG（齿状回）**：模式分离——将相似输入变成不相似表征，防止记忆混淆
- **CA3**：模式补全——通过循环连接，用部分线索激活完整表征
- **CA1**：整合与输出——综合 CA3 和 EC3 两路信息，是场所细胞密度最高的区域

海马是情景记忆（episodic memory）的核心结构，损伤（如 H.M. 案例）导致无法形成新的情景记忆，但远期记忆和技能记忆相对保留。

## 关键机制

### 1. 信息流入：内嗅皮层的两路输入

**内嗅皮层（EC）**是皮层与海马之间的枢纽，提供两类输入：
- **内侧内嗅皮层（MEC）**：空间信息（网格细胞、头向细胞、边界细胞）→ 空间坐标框架
- **外侧内嗅皮层（LEC）**：物体和非空间信息 → 事件"内容"

输入路径：
- **穿孔通路（perforant path, PP）**：EC→DG（主要）、EC→CA3（侧支）、EC3→CA1（远端树突）

### 2. 齿状回（DG）：模式分离

**粒细胞（granule cells）**：
- 活动极稀疏：每次环境探索中仅 <5% 的细胞激活
- 每个细胞有单一、长期稳定的场所场
- 通过**苔状纤维（mossy fiber）**投射到 CA3

**模式分离机制**：
- 大量颗粒细胞（啮齿类约 100 万）接受少量内嗅皮层神经元输入 → 投影展开（expansion recoding）
- 颗粒细胞间强抑制（篮细胞、苔状细胞介导）→ 竞争稀疏化
- 结果：相似输入 → 不相似 DG 输出 → 防止 CA3 中记忆干扰

### 3. CA3：模式补全与联想记忆

CA3 的独特结构是大量的**循环连接（recurrent collaterals）**：CA3 锥体细胞约有 12,000 个同类细胞的兴奋性突触输入（来自其他 CA3 细胞），与来自 DG 的约 50 个苔状纤维突触相比数量悬殊。

**模式补全**：当部分线索激活 CA3 的一小部分，循环连接可逐步激活代表完整记忆的整个 CA3 集群（类似 Hopfield 网络的吸引子动力学）。

**关键因果证据（2026-06-24 新增）**：Nakazawa et al. (2002, Science, PMID:12040087) 使用 CA3 特异性 NR1 基因敲除小鼠，直接证明 CA3 循环突触的 NMDA 受体对模式补全必要——完整线索下表现正常，部分线索下行为和 CA3 场所细胞活动均严重受损。这是从相关性到因果性的关键实验跨越。详细机制见 [[pattern-completion]]。

**CA3 vs CA1 的计算个性**：Leutgeb et al. (2004, Science, PMID:15272123) 的体内记录显示：CA3 对相似环境产生近离散的全局重映射（吸引子式），而 CA1 产生连续的相似度映射（比较器式）。CA3 是非线性的状态分类机；CA1 是线性的相似度计量器。

**CA3 的 BTSP**（Li et al., 2024, PMID:39454575）：
- 发生在循环突触（而非苔状纤维）
- 时间窗口对称（vs CA1 的不对称）
- 依赖内嗅皮层更新；DG 输入不是必须的

### 4. CA1：整合与输出

**CA1 是三突触回路的终点**，整合两路主要输入：
- **近端树突**：CA3 Schaffer collaterals（模式完整的联想信息）
- **远端树突**：EC3 直接输入（穿孔通路远端支，空间坐标信息）

CA1 的场所细胞通过 BTSP 在单次穿越中建立场所场，时间窗口不对称（向后偏移），产生预测性斜坡电位（ramp membrane potential）。

CA1 输出到**下托（Subiculum）**，再到内嗅皮层（EC）、前额叶和杏仁核等皮层结构。

### 5. 海马的两种工作模式：θ态与SWR态

海马在不同行为状态下运行截然不同的工作模式，两者在时间上几乎互斥：

**θ态（在线/编码模式）**：
- 出现于主动探索、运动和REM睡眠时
- 局部场电位呈4–12 Hz θ振荡
- 场所细胞以相位前进（phase precession）方式放电，实现空间位置的双重编码（速率+相位）
- 每个θ周期内，多个场所细胞形成时间序列（θ sequences），将行为尺度路径压缩约20倍
- BTSP等突触可塑性依赖于θ振荡协调的时机，实现快速记忆写入

**SWR态（离线/固化模式）**：
- 出现于静止、非REM睡眠和进食/梳洗等消耗性行为时
- CA3循环兴奋自发爆发，通过Schaffer侧支驱动CA1产生110–200 Hz涟漪
- 白天的场所细胞序列以~20倍速度高速重播
- 重播内容包括前向、反向，甚至新颖路径（规划/想象？）
- 选择性SWR中断损害次日空间记忆（因果证据）
- 被认为是海马→新皮层记忆巩固的物理载体

**两种模式的切换机制**：
- 胆碱能（ACh）张力是关键开关：ACh高→θ态；ACh低→SWR自发爆发
- MS-DBB驱动θ时，同时抑制CA3的循环兴奋；θ消失时，循环兴奋解放

### 6. CA3 的慢性应激脆弱性

CA3 是海马中对慢性糖皮质激素（GC）**选择性最脆弱**的亚区（McEwen 1997, PMID:9405958；Uno 1994, PMID:7729802）：

**结构损伤**：
- 啮齿类 21 天束缚应激→CA3 锥体细胞顶树突萎缩约 **20%**（树突总长度、分支复杂度）
- 灵长类慢性社会从属应激→海马体积萎缩约 **30%**（CA3 细胞密度降低为主）

**CA3 选择性脆弱的机制**：
1. **循环突触高兴奋性**：CA3 循环连接（~12,000 个/神经元）形成局部正反馈网络，在慢性 GC 刺激下比 CA1/DG 更易发生 NMDAR 过激活
2. **高 GR 密度**：CA3 锥体细胞 GR 表达高于 CA1，对 GC 更敏感
3. **谷氨酸-NMDA 机制**：慢性 GC→突触前谷氨酸释放增加→NMDAR 过激活→树突结构损伤；NMDAR 拮抗剂（AP5）可防止萎缩（因果证据）

**功能后果**：
- 模式补全功能受损（CA3 循环回路是模式补全的关键结构）
- DG→CA3→CA1 模式分离-补全信息流的整体容量下降
- 场所细胞重映射能力下降→空间导航灵活性受损

**可逆性**：解除慢性应激后 2-3 周，CA3 树突部分恢复——结构可塑性在成年脑中仍保留（但恢复不完全）。

**HPA 负反馈恶性循环**：CA3/CA1 GR→抑制 HPA 轴（负反馈制动）。慢性 GC 损害海马 → 负反馈减弱 → HPA 轴更难关闭 → 更多 GC → 进一步 CA3 损伤（正反馈恶性循环），这可能是慢性应激→AD 风险升高的部分机制（Q-gc-02）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| DG 粒细胞活动稀疏（<5%）| 钙成像，体内探索实验 | PMID:32042144 综述 | 高 |
| CA3 循环回路支持模式补全 | 选择性 CA3 损伤损害线索完整记忆提取 | PMID:18007020 | 中-高 |
| CA1 整合 CA3 + EC3 两路输入 | 分层记录 + 光遗传阻断 | PMID:32042144 综述 | 高 |
| 海马损伤导致顺行性遗忘 | H.M. 案例等神经心理学经典 | 引用于 PMID:18284371 | 高 |
| CA3 BTSP 在循环突触上，依赖内嗅皮层 | 清醒小鼠胞内 + 光遗传 | PMID:39454575 | 高（读摘要）|
| 慢性应激→CA3 顶树突萎缩约 20%（NMDAR 机制） | 束缚应激 + 形态学测量 + AP5 阻断 | PMID:9405958 | 高（啮齿类） |
| 灵长类慢性社会应激→海马体积萎缩约 30% | 树鼩社会从属应激 + 神经病理 | PMID:7729802 | 高（灵长类） |

## 连接

- [[place-cell]] — CA1 场所细胞是海马回路的主要输出表征
- [[btsp]] — BTSP 是 CA1（和 CA3）场所场写入的突触机制
- [[grid-cell]] — 内嗅皮层网格细胞通过穿孔通路输入到 DG/CA3/CA1
- [[ltp]] — CA3 循环突触和 CA1 Schaffer 突触的 LTP 是长期记忆的突触基础
- [[dendritic-computation]] — CA1 锥体细胞的树突计算（平台电位）是 BTSP 的物理基础
- [[memory-consolidation]] — 海马 SWR 重放是海马→皮层记忆巩固的机制
- [[theta-oscillations]] — θ 振荡（4–12 Hz）协调海马回路的编码节律，调控 BTSP 触发时机
- [[engram-cells]] — DG 是印迹细胞的主要居所；DG→CA3→CA1→BLA 的印迹间优先连接链利用三突触回路结构
- [[pv-interneurons]] — CA1 的 PV+ 篮状细胞在 SWR 期间强放电，产生涟漪（100–200 Hz）；在 θ 期间控制放电时序
- [[sst-interneurons]] — CA1 的 O-LM 细胞（SST+ 亚型）在 θ 期间活跃，靶向内嗅皮层输入区（SLM），实现 top-down 输入门控
- [[glucocorticoid-stress-memory]] — 慢性 GC 选择性损伤 CA3（树突萎缩、GR 高密度、循环兴奋过激）；急性 GC 增强 BLA-海马通路的记忆巩固
- [[hpa-axis]] — 海马（CA1/CA3/DG GR）是 HPA 轴负反馈的主要制动节点；慢性应激导致的 CA3 萎缩削弱此制动 → HPA 恶性循环
- [[time-cells]] — CA1 时间细胞是情节记忆"何时"维度的细胞基础；CA2→CA1 回路专门组织时间序列
- [[temporal-context-model]] — TCM 理论框架：时间细胞序列可能是"时间情境状态"的神经实现
- [[ca2-hippocampus]] — CA2 亚区专用详细页（社会记忆/时间序列/SWR触发三功能枢纽；RGS14/PCP4/Avpr1b 分子标记）
- [[sharp-wave-ripples]] — CA2 是 SWR 的主要触发者（约 50% SWR 由 CA2 ramping cells 在 SWR 前 20–30ms 启动）

### 7. CA2 亚区：社会记忆、时间序列与 SWR 触发的三功能枢纽

**CA2**（海马最小亚区，以 RGS14/PCP4/Avpr1b 为分子标记，与 CA1/CA3 形成功能性分工）曾是回路中最被忽视的元件——现在我们知道它承载三项独立的关键功能（完整机制详见 [[ca2-hippocampus]]）：

**① 社会记忆的专用基底（Hitti & Siegelbaum 2014, PMID:24572357）**：
- Amigo2-Cre+TeNT 小鼠选择性灭活 CA2 突触输出 → 社会识别记忆**完全丧失**
- 空间记忆、恐惧记忆、物体识别均**正常**——CA2 是社会记忆的专用基底，非一般记忆节点
- CA2 接受下丘脑 PVN 的加压素/催产素（Avpr1b 特异表达），是 CA1/CA3 不具备的激素门控输入

**② CA1 时间细胞序列的必要组织者（MacDonald & Tonegawa 2021, PMID:33431691）**：
- CA2-Cre+ArchT 光遗传沉默 CA2→CA1 → **~48% 时间细胞**（149/313）放电精度显著下降
- 场所细胞仅 **15%** 受影响（χ² P = 8.19×10⁻⁶ 的时间-空间双分离）
- 工作记忆任务延迟阶段错误显著增加（F(1,20)=21.67, P=0.002）

**③ 尖波涟漪的主要触发器（Oliva et al. 2016, PMID:27593179）**：
- 高密度探针记录：CA2 "ramping cells"（约 50% CA2 锥体细胞）在 SWR 前 **20–30 ms** 斜升放电
- 光遗传激活 CA2 可诱导人工 SWR（CA3+CA1 均被驱动）
- 部分 SWR **绕过 CA3**，直接经 CA2→CA1 基底树突传播

**海马功能回路的修订图谱**：
```
外侧内嗅皮层（LEC：物体/事件内容）→ CA1（内容维度）
内侧内嗅皮层（MEC：时间/空间信号）→ CA2 → CA1（时间维度）
                                    → DG → CA3 → CA1（空间维度）
室旁核（PVN：加压素/催产素）————→ CA2（社会情境可塑性门控）
```

CA1 是时间（CA2通路）、空间（CA3通路）和内容（LEC直接输入）的**三路整合终点**；CA2 同时作为 SWR 的"发令枪"，决定哪些社会/时间信息通过离线回放写入皮层长期存储。

## 未解问题

- Q-ca2-function：CA2 亚区（在 CA3 和 CA1 之间）的完整功能图谱？已知：社会记忆（OXT受体）+时间序列组织（MacDonald&Tonegawa 2021）；两者如何在CA2内整合？CA2是否也参与其他形式的序列记忆？
- Q-hippocampal-consolidation-mechanism：海马→皮层的记忆巩固是如何精确调控的？SWR 重放选择哪些序列？
- Q-ad-vulnerable-synapses：为什么CA3-CA1突触（Schaffer侧支）是AD中首批受损的突触？高NR2B密度+内嗅皮层传播路径（Braak I期）的联合假说是否足够？什么分子标志物可以预测某个突触的AD易损性？
- Q-tc-01：时间细胞的激发是内在计时（内在动力学驱动）还是内隐认知序列表征？
- Q-tc-02：时间细胞对情节记忆提取的因果贡献是什么？（相关已知，因果未知）
- Q-tc-04：情节记忆固化时，时间细胞序列如何在SWR中被回放？精确重现还是压缩/重排？

## 修订历史

- 2026-08-14 · 修订 rev12 · 基于《CA2：海马遗忘的第三元件》(#113) · 将"CA2亚区"机制节从单一时间编码全面扩展为三功能枢纽（社会记忆 Hitti 2014 PMID:24572357 / 时间序列 MacDonald 2021 PMID:33431691 / SWR 触发 Oliva 2016 PMID:27593179）；连接新增[[ca2-hippocampus]]、[[sharp-wave-ripples]]；related新增ca2-hippocampus、social-memory、sharp-wave-ripples；opens_questions新增Q-ca2-pnn-plasticity-window、Q-ca2-disease-mechanism；key_sources新增5个PMID
- 2026-08-04 · 修订 rev11 · 基于《时间细胞：海马如何为情节记忆打上时间戳》(#103) · 新增"CA2亚区：时间序列专门组织者"机制节；更新"当前理解"为三流输入（LEC内容+MEC时间+CA3空间）；related新增time-cells、temporal-context-model；opens_questions新增Q-tc-01、Q-tc-02、Q-tc-04；key_sources新增PMID:21867888、PMID:33431691、PMID:29706516
- 2026-07-09 · 修订 rev10 · 基于《记忆为什么最牢记住恐惧》一文 (#77) · 新增"CA3 的慢性应激脆弱性"机制节（CA3 树突萎缩 20%、灵长类海马体积萎缩 30%、GR 高密度机制、NMDAR 拮抗剂防萎缩、HPA 负反馈恶性循环）；证据表新增 2 行（PMID:9405958、PMID:7729802）；连接新增 glucocorticoid-stress-memory、hpa-axis；未解问题新增 Q-gc-02；related/key_sources/source_articles 相应更新
- 2026-06-24 · 修订 · 基于"记忆不混淆的秘密"文章 · 新增：CA3 模式补全因果证据（Nakazawa 2002 PMID:12040087 CA3-NR1 KO 实验）；CA3 vs CA1 不同计算个性（Leutgeb 2004 PMID:15272123）；related 新增 pattern-completion、pattern-separation、attractor-network、complementary-learning-systems；key_sources 新增 4 篇关键来源
- 2026-05-28 · 创建 · 基于《场所细胞》文章 · 整合 Hainmueller & Bartos 2020 和 Li 2024 的信息 · 初始置信度：高
- 2026-05-29 · 修订 · 基于《θ振荡与相位编码》文章 · 新增"海马两种工作模式"（θ态/SWR态）章节；新增 SWR 生成和重播机制；新增 key_sources
- 2026-05-31 · 修订 · 基于《印迹细胞》文章 · 新增：DG 是印迹细胞分配竞争的主要场所（2–4% 稀疏活动→高正交性）；DG→CA3→CA1→BLA 印迹间优先连接链的描述；连接增加 [[engram-cells]]
- 2026-06-02 · 修订 · 基于《记忆的夜间旅行》文章 · [[memory-consolidation]] 页面已建立；填补 Q-hippocampal-consolidation-mechanism 的核心内容（SO-spindle-SWR三重奏、ACh 双模式开关、两阶段模型）
- 2026-06-03 · 修订 · 基于《回路中的少数精锐》文章 · 新增：CA1 内 PV+ 篮状细胞（SWR 期高速放电、涟漪产生者）和 SST+ O-LM 细胞（θ期活跃、门控EC输入）的角色描述；connected to [[pv-interneurons]] 和 [[sst-interneurons]]
- 2026-06-08 · 修订 · 基于《记忆的分子遗忘》一文（AD机制） · 新增 AD 易损性分析（CA3-CA1 Schaffer侧支高NR2B密度+内嗅皮层传播路径联合机制）；related 新增 alzheimers-disease、amyloid-beta-oligomers；dimensions 新增 disease；opens_questions 新增 Q-ad-vulnerable-synapses；key_sources 新增 PMID:1789684、PMID:20581818
- 2026-06-16 · 修订 · 基于《默认模式网络》一文 · 确认海马（MTL）是 DMN 核心节点；related 新增 default-mode-network
- 2026-06-17 · 修订 · 基于《夜晚，大脑重写自己的神经地图》文章 · 新增Ecker 2022关键发现：CA3学习依赖突触权重结构同时决定SWR生成与重放内容（"学什么和重放什么共用同一张突触地图"）；key_sources新增PMID:35040779；source_articles新增2026-06-17

## 来源文章

- [[2026-05-28-place-cells-btsp]]
- [[2026-05-29-theta-oscillations-phase-coding]]
- [[2026-05-31-engram-cells-optogenetic-proof]]
- [[2026-06-02-memory-consolidation-systems]]
- [[2026-06-03-inhibitory-interneuron-diversity]]
- [[2026-08-14-ca2-hippocampus-social-memory-temporal-context]]

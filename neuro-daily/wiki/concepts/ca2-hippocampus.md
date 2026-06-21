---
title: CA2 区（海马第二角）
slug: ca2-hippocampus
domain: concepts
type: structure
status: mainstream
confidence: high
created: 2026-08-14
updated: 2026-08-17
revision_count: 3
dimensions: [cellular, microcircuit, brain-region, cognition, behavior]
related: [hippocampal-circuit, place-cells, time-cells, sharp-wave-ripples, social-memory, vasopressin, oxytocin, supramammillary-nucleus, rgs14, ltp, mgluR-ltd, theta-oscillations, pattern-completion, pattern-separation, aggression, lateral-septum]
prerequisites: [hippocampal-circuit, synaptic-transmission, ltp]
opens_questions: [Q-tc-01, Q-ca2-function, Q-ca2-pnn-plasticity-window, Q-ca2-disease-mechanism, Q-oxt-01, Q-avp-01]
source_articles: [2026-08-14-ca2-hippocampus-social-memory-temporal-context, 2026-08-16-oxytocin-circuit-social-memory-bonding, 2026-08-17-vasopressin-social-behavior-avp-circuit]
key_sources: ["PMID:24572357", "PMID:33431691", "PMID:31874067", "PMID:34201943", "PMID:27593179", "PMID:36971428", "PMID:24863146", "PMID:29705549", "PMID:36575880", "PMID:38052983", "PMID:30518859"]
---

# CA2 区（海马第二角, Hippocampal CA2）

> **一句话定义**：CA2 是插于 CA3 和 CA1 之间的小型海马亚区，以独特的分子标记（RGS14/PCP4）和对标准 LTP 的主动抗性著称，是社会记忆的不可或缺节点、CA1 时间细胞序列的关键输入源，以及尖波涟漪事件的主要触发器——三项功能指向同一计算原则：在禁止随机改写的基础上，精准实施社会情境与时间情境的专用可塑性。

## 当前理解

我们现在认为，CA2 并非经典三突触回路（EC→DG→CA3→CA1）的惰性旁观者，而是一个**主动的多功能中继枢纽**，通过以下三条独立功能线路深刻影响海马信息处理：

1. **社会记忆的分子门（Hitti & Siegelbaum 2014, PMID:24572357）**：选择性灭活 CA2 锥体神经元导致社会识别记忆完全丧失，而空间记忆、恐惧记忆、物体识别均正常——CA2 是社会记忆的专用基底，非一般记忆的模块。

2. **CA1 时间细胞序列的关键输入（MacDonald & Tonegawa 2021, PMID:33431691）**：光遗传沉默 CA2→CA1 投射使约 48% 的时间细胞精度下降，而场所细胞不受影响——CA2 为 CA1 的"时间维度"提供不可替代的组织信号，空间编码与时间编码在此实现功能解耦。

3. **尖波涟漪事件的触发者（Oliva et al. 2016, PMID:27593179）**：高密度探针记录显示 CA2 "ramping cells" 在 SWR 前 20–30ms 斜升放电，先于 CA3/CA1 的群体事件——约半数 SWR 由 CA2 主导触发，CA2 是记忆离线回放的"发令枪"。

CA2 的独特之处在于其**反直觉的分子策略**：它表达 RGS14 蛋白，主动压制标准 Hebbian LTP，使自身在普通学习刺激下不被随意改写；但它支持催产素/加压素诱导的突触增强，允许**社会情境专用的可塑性**在特定神经调制条件下发生（Pagani et al. 2015, PMID:24863146）。

## 关键机制

### 1. 分子身份：与 CA1/CA3 的本质区别

CA2 锥体神经元表达一系列在 CA1/CA3 中几乎不表达的特征性标志物：
- **RGS14**（G蛋白信号调节蛋白14）：LTP 的主动抑制器（见下）
- **PCP4**（Purkinje cell protein 4）：钙缓冲蛋白，调节钙瞬变振幅
- **STEP**（纹状体富集蛋白酪氨酸磷酸酶）：参与 mGluR-LTD
- **SHP2**（SH2域蛋白酪氨酸磷酸酶）：调节 ERK/MAPK 信号
- **Avpr1b**（加压素 1b 受体）：密度远高于 CA1/CA3
- 催产素受体（特定亚型）

这些标志物使 CA2 在冷冻切片或钙成像中可被精准识别，Amigo2-Cre 小鼠系（Hitti & Siegelbaum 2014）便利用 Amigo2 基因的 CA2 特异性表达实现了选择性操控。

### 2. RGS14 介导的 LTP 主动抗性

在相同高频刺激下，CA1 锥体细胞产生强健 LTP，CA2 锥体细胞几乎无 LTP（Harbin et al. 2021, PMID:34201943）。

**RGS14 的多通路抑制机制**：
- **钙瞬变缓冲**：RGS14 抑制树突棘 Ca²⁺ 升高；只有超生理高钙（8 mM）才能突破抑制
- **G 蛋白调节**：作为 GAP（GTPase 激活蛋白）控制 Gαi/o 的 cAMP 依赖信号
- **CaMKII 互作**：直接与 CaMKII 结合抑制其活化
- **ERK 抑制**：通过 H-Ras 结合抑制 ERK/MAPK 通路（LTP 后期所需）
- **细胞骨架调控**：抑制树突棘扩大所需的肌动蛋白重组

**逻辑后果**：RGS14 敲除小鼠的 CA2 出现正常 LTP，且 Morris 水迷宫空间记忆和物体识别均改善——说明 LTP 抗性是 CA2 的主动功能配置，不是缺陷。

### 3. mGluR-LTD：CA2 支持的特殊可塑性

尽管抗拒标准 LTP，CA2 支持代谢型谷氨酸受体（mGluR）依赖的长时程抑制（Samadi et al. 2023, PMID:36971428）：
- 依赖蛋白质合成和 STEP
- 需要 RGS14（而非 RGS4）参与
- RGS14 KO 小鼠的 mGluR-LTD 受损，社会识别记忆也受损

这提示 CA2 的社会记忆功能可能部分通过 mGluR-LTD（而非 LTP）实现信息储存。

### 4. 加压素/催产素通路：社会情境可塑性的激素钥匙

CA2 接受来自下丘脑**室旁核（PVN）**的加压素和催产素能纤维投射，这是 CA1/CA3 不具备的输入：
- Avpr1b 激动剂在 CA2 诱发 NMDA 受体和 Ca²⁺ 依赖的突触增强（在 CA1 无效）（Pagani et al. 2015, PMID:24863146）
- PVN→CA2 加压素通路增强社会记忆表现（Piskorowski & Chevaleyre 2018, PMID:29705549）
- 催产素信号在 CA2 参与社会行为（催产素受体选择性表达于 CA2）

**机制假说（社会记忆写入）**：社会接触触发垂体肽释放→OTR 激活→Ca²⁺ 信号解除 RGS14 的部分抑制→CA2 突触短暂进入可塑性窗口→社会身份信息被写入（mGluR-LTD）。

### 4b. V1bR（Avpr1b）路径：社会攻击的海马触发器

CA2 的 V1bR（Avpr1b）密度在海马各亚区中最高，其功能与 OTR 路径对立（Leroy et al. 2018, PMID:30518859）：

**回路**：
```
AVP → CA2-V1bR（增强谷氨酸输出）
        ↓
外侧隔核（LS）抑制性中间神经元（激活）
        ↓（抑制 LS→VMH 投射）
腹内侧下丘脑（VMH）（去抑制）
        ↓
社会攻击行为
```

**双受体对比**：
- **OTR 激活 CA2** → mGluR-LTD → 社会识别记忆写入（"记住是谁"）
- **V1bR 激活 CA2** → 增强谷氨酸输出 → LS→VMH 脱抑制 → 社会攻击（"对威胁者做出反应"）

**功能逻辑**：同一 CA2 神经元，通过激活不同受体，产生对立社会计算——可能的两步操作：先识别个体身份（OTR 路径），再根据威胁状态决定是否攻击（V1bR 路径）。

### 5. 连接结构：多源输入与定向输出

**CA2 主要输入**：
- 外侧/内侧内嗅皮层（EC）II 层（直接穿孔通路）
- 齿状回颗粒细胞（苔状纤维侧支）
- CA3 锥体细胞（Schaffer 侧支）
- CA2 自身（密集递归连接）
- 下丘脑乳头上核（SMN）：节律性输入
- 室旁核（PVN）：加压素/催产素纤维
- 腹侧被盖区（VTA）：多巴胺调制
- 内侧隔核：胆碱能与 GABA 能输入

**CA2 主要输出**：
- 背侧 CA1 锥体细胞（basal 树突，stratum oriens/radiatum）
- 内侧内嗅皮层 II 层（反馈路径）

**关键不对称**：EC 激发 CA2 的效率高于 CA1/CA3（Middleton & McHugh 2020, PMID:31874067），且 CA2 有密集递归自联；这使 CA2 能够在没有持续外部输入的情况下维持活动——恰好符合"内部时间流"发生器的角色。

### 6. 触发尖波涟漪：CA2 的网络主导角色

Oliva et al. 2016（PMID:27593179）用高密度硅探针在同一大鼠同步记录 CA2+CA3+CA1：
- CA2 "ramping cells"（约 50% CA2 锥体细胞）在 SWR 前 ~20–30ms 斜升激发
- CA2 "phasic cells" 在 SWR 起始时激发
- 随后 CA3 群体爆发，最后 CA1 涟漪
- 清醒时触发效果 > 睡眠时
- 光遗传激活 CA2 诱导 CA3+CA1 的人工 SWR

部分 SWR **绕过 CA3**，直接经 CA2→CA1 基底树突传播——存在 CA2 独立触发路径。

这意味着 CA2 不仅是社会和时间信息的编码节点，也是决定"何时把信息通过 SWR 回放给皮层"的**触发决策者**。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| CA2 灭活选择性损害社会记忆，空间/恐惧记忆不受影响 | Amigo2-Cre+TeNT 小鼠；5试次社会认知测试 | PMID:24572357 (PMC4000264) | 高 |
| CA2→CA1 投射对时间细胞序列因果必要 | CA2-Cre+ArchT；光遗传沉默；延迟交替任务；630 CA1 细胞 | PMID:33431691 (PMC7826404) | 高 |
| RGS14 是 CA2 LTP 抗性的必要充分条件 | RGS14 KO 小鼠；CA2 电生理；高频刺激 | PMID:34201943 (PMC8268017) | 高 |
| CA2 mGluR-LTD 需要 RGS14，且影响社会记忆 | RGS14 KO；mGluR 激动剂；社会识别测试 | PMID:36971428 | 高 |
| CA2 ramping cells 先于 SWR 触发，CA2 可诱导人工 SWR | 大鼠高密度探针；光遗传激活 CA2 | PMID:27593179 | 高 |
| Avpr1b 激动剂在 CA2（而非 CA1）诱发 NMDA 依赖突触增强 | 小鼠 CA2/CA1 切片电生理；选择性 Avpr1b 激动剂 | PMID:24863146 | 高 |
| CA2 在颞叶癫痫中比 CA1/CA3 弹性更大 | TLE 患者切除组织病理 | PMID:31874067 | 中-高 |
| CA2→LS→VMH 脱抑制回路触发社会攻击；V1bR 增强 CA2 输出 | 光遗传+化学遗传+回路解剖；草原田鼠 | PMID:30518859 (Leroy 2018 Nature) | 高 |

## 连接

- [[hippocampal-circuit]] — CA2 是经典三突触回路中被长期忽视的第四元件，插于 CA3 和 CA1 之间
- [[time-cells]] — CA2→CA1 投射为时间细胞序列提供关键组织信号（MacDonald & Tonegawa 2021）
- [[sharp-wave-ripples]] — CA2 是 SWR 的主要触发者，50% SWR 由 CA2 ramping cells 引发（Oliva 2016）
- [[ltp]] — CA2 对标准 Hebbian LTP 有 RGS14 介导的主动抗性（区别于 CA1/CA3）
- [[social-memory]] — CA2 灭活选择性消除社会识别记忆（Hitti & Siegelbaum 2014）
- [[vasopressin]] — Avpr1b 信号在 CA2 诱发社会情境专用可塑性（直接通路）
- [[oxytocin]] — 催产素通过 PVH→SuM→CA2 间接通路参与社会记忆写入（Thirtamara Rajamani 2024）；OTR 与 V1bR 共享 CA2 资源
- [[vasopressin]] — V1bR（Avpr1b）在 CA2 密集表达；AVP 通过 V1bR 增强 CA2 谷氨酸输出触发社会攻击（CA2→LS→VMH；Leroy 2018）
- [[aggression]] — CA2-V1bR 是社会攻击的海马触发节点；CA2→LS 脱抑制 VMH 回路
- [[lateral-septum]] — CA2 通过 LS 抑制性中间神经元对 VMH 进行门控（Leroy 2018 攻击回路）
- [[supramammillary-nucleus]] — SuM 是催产素信号到 CA2 的关键中继站
- [[hippocampal-ca3-pattern-completion]] — CA3 循环连接的联想记忆功能与 CA2 的社会/时间功能并行

## 未解问题

- Q-tc-01：CA2 与 MEC 对时间细胞的贡献是加性、乘性还是功能冗余的？是否有实验同步沉默两者？
- Q-ca2-function：CA2 的社会记忆功能与时间记忆功能是否共享相同的细胞机制，或是由不同亚型神经元承担？
- Q-ca2-pnn-plasticity-window：CA2 围神经元网（PNNs）在青春期成熟后是否关闭了社会记忆的关键期？
- Q-ca2-disease-mechanism：双相障碍和精神分裂症中 CA2 特异性 RGS14 减少与哪些回路功能失调有关？
- Q-avp-01：CA2 的 OTR 和 V1bR 如何在同一时刻协调？社会记忆写入和攻击触发是时序分离、由不同亚型神经元响应，还是根据当前神经肽浓度动态切换？

## 修订历史

- 2026-08-14 · 创建 · 基于《CA2：海马遗忘的第三元件》文章 #113 · 来源：PMID:24572357/33431691/31874067/34201943/27593179 · 初始置信度：高
- 2026-08-16 · rev2 · 基于《催产素回路》文章 #115 · 新增：(1) PVH→SuM→CA2间接催产素通路（PMID:38052983）；(2) 与supramammillary-nucleus、oxytocin的新连接；(3) Q-oxt-01加入未解问题（Avpr1b和OTR两条通路的时序协调）
- 2026-08-17 · rev3 · 基于《加压素回路》文章 #116 · 新增：(1) 第4b节：CA2-V1bR→LS→VMH攻击回路（Leroy 2018，PMID:30518859）；(2) OTR vs. V1bR双受体功能对比；(3) 与vasopressin、aggression、lateral-septum的新连接；(4) Q-avp-01加入未解问题；(5) key_sources新增PMID:30518859

## 来源文章

- [[2026-08-14-ca2-hippocampus-social-memory-temporal-context]]
- [[2026-08-16-oxytocin-circuit-social-memory-bonding]]
- [[2026-08-17-vasopressin-social-behavior-avp-circuit]]

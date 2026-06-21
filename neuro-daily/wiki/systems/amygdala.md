---
title: 杏仁核
slug: amygdala
domain: systems
type: region
status: established
confidence: high
created: 2026-05-30
updated: 2026-08-26
revision_count: 8
dimensions: [cellular, microcircuit, brain-region, behavior, cognition, disease]
related: [fear-conditioning, fear-extinction, ltp, hippocampal-circuit, dopamine-reward-prediction-error, norepinephrine-locus-coeruleus, basal-ganglia, glucocorticoid-stress-memory, hpa-axis, memory-consolidation, memory-reconsolidation, olfactory-bulb, piriform-cortex, orbitofrontal-cortex, value-based-decision-making, vmPFC, emotion-regulation, cognitive-reappraisal, ptsd]
prerequisites: [ltp, synaptic-transmission, nmda-receptor]
opens_questions: [Q-fear-human-amygdala-specificity, Q-fear-low-road-function, Q-fear-itc-bidirectionality, Q-vmPFC-03, Q-ptsd-01]
source_articles: [2026-05-30-amygdala-fear-memory, 2026-07-09-glucocorticoids-stress-memory-amygdala, 2026-07-10-memory-reconsolidation-ptsd, 2026-07-24-amygdala-fear-engram-extinction-reward-neurons, 2026-07-26-olfactory-coding-smell-memory-limbic, 2026-08-21-orbitofrontal-cortex-value-decision-circuit, 2026-08-25-vmPFC-sgACC-emotion-regulation, 2026-08-26-ptsd-fear-circuit-neural-mechanism]
key_sources: ["PMID:24908482", "PMID:22129456", "PMID:20393190", "PMID:30877244", "PMID:16310958", "PMID:23968228", "PMID:34168140", "PMID:31952856", "PMID:38396226", "PMID:25162525", "PMID:37620443", "PMID:32278646", "DOI:10.7554/eLife.80926", "PMID:40068869", "PMID:19693001", "PMID:12495527", "PMID:26617500", "PMID:19748076", "PMID:35352034"]
---

# 杏仁核 (Amygdala)

> **一句话定义**：颞叶深部由多个亚核组成的复合核团，是大脑情绪记忆（尤其是恐惧）的写入与表达中枢，通过外侧核的LTP学习CS-US关联，通过中央核输出防御反应，通过与前额叶和海马的三角回路实现情境依赖的情绪调控。

## 当前理解

我们现在认为，杏仁核不是一个统一的"情绪中枢"，而是由功能截然不同的亚结构组成的微回路复合体。其中基底外侧杏仁核复合体（BLA，包括外侧核LA和基底核BA）是感觉信息的输入与可塑性发生地，中央核（CeA）是防御行为的输出引擎，而散布其间的插入细胞（ITC）是恐惧与消退之间的可塑性闸门。

恐惧记忆的写入本质是LA突触的LTP——与海马LTP使用相同的NMDA→CaMKII→AMPA插入分子机器。恐惧消退不是记忆抹除，而是IL皮层→腹侧ITC→CeM的新抑制回路对原始恐惧回路的竞争性压制。两套记忆痕迹在杏仁核及其前额叶-海马连接网络中并行共存，情境信号决定哪套痕迹占主导。

## 关键机制

### 亚核架构
- **外侧核（LA）**：首要感觉输入站；CS（音调）从听觉丘脑/皮层、US（电击）从躯体感觉丘脑汇聚于此；是LTP发生的核心位点；约80%为兴奋性锥体神经元，~20%为GABAergic中间神经元；条件反射后约20%神经元形成稀疏CS响应（恐惧印迹）——稀疏性由**突触可塑性竞争规则**决定：初始突触权重更高（CREB/内在兴奋性更高）的神经元在CS-US配对中更易发生LTP，从而竞争性选入印迹（Jeong et al. 2021, Nat Commun, PMID:34168140）
- **基底核（BA）**：包含恐惧神经元（投射PL皮层，条件反射后CS+）和消退神经元（投射IL皮层，消退后CS+）两个功能截然不同的群体（Herry et al. 2008, PMID:18615015）；接收海马情景信息，决定哪群神经元主导。**关键新发现（2026-07-24）**：消退神经元/消退印迹细胞 ≈ BLA 中天然的**奖励响应神经元**——激活消退印迹细胞产生奖励行为（CPP），与自然奖励响应神经元高度重叠；消退训练本质上是奖励系统对感觉输入的重新占领（Zhang, Kim, Tonegawa 2020, Neuron, PMID:31952856）。恐惧/消退印迹是**不同的细胞群体**（Luft et al. 2024, Hippocampus, PMID:38396226）
- **中央核（CeA）**：外侧部（CeL）含PKCδ+（关闭细胞）和SOM+（开启细胞），形成局部去抑制回路；内侧部（CeM）是主要输出，投射至PAG（冻结）、下丘脑（自主神经）、BNST（持续焦虑）

### 插入细胞（ITC）
- 散布于BLA与CeA之间的GABAergic神经元群
- **背侧ITC（ICMMD）**：LA→ICMMD→抑制ICMMV→CeM去抑制 → 恐惧表达
- **腹侧ITC（ICMMV）**：BLA+IL皮层→ICMMV→直接抑制CeM → 消退表达
- ITC上富含µ-阿片受体，阿片系统可调节消退
- 选择性损毁ITC → 恐惧获得正常，消退表达严重受损（Likhtik et al. 2008）

### 恐惧表达的完整输出
CeM → PAG → 冻结行为；CeM → 下丘脑 → 自主神经激活（心率↑）；CeM → 下丘脑室旁核 → HPA轴 → 皮质醇；CeM → BNST → 持续焦虑/广泛性焦虑

### 糖皮质激素（GC）与去甲肾上腺素（NE）协同增强应激记忆

应激激活两条平行的内分泌-神经内分泌路径，在 BLA 产生协同效果（McGuire 2013, PMC5581004）：

**路径 1（HPA 轴，慢速，5-30 分钟）**：
- 应激→下丘脑 PVN → CRH → 垂体 ACTH → 肾上腺皮质 → 糖皮质激素（GC）
- GC 穿越血脑屏障 → BLA 中 GR 激活
- GR 基因组途径：转录激活（Arc、BDNF、c-Fos）→ 30-120 分钟后蛋白合成 → LA 突触 AMPA 受体增量插入 → L-LTP 转化

**路径 2（SAM 轴，快速，秒级）**：
- 应激→交感神经→肾上腺髓质→肾上腺素（不穿越 BBB）
- 间接路径：①肾上腺素→迷走传入→孤束核（NTS）→BLA ② 触发蓝斑（LC）→NE 释放
- BLA 中 NE→β-肾上腺素受体（β-AR）→ cAMP→PKA→AMPAR 磷酸化→快速 LTP 增强

**协同门控**（Roozendaal 2006, PMID:16310958; Barsegyan 2019, PMID:30877244）：
- BLA 内单独高 GC（无 NE）→**不能**增强记忆（β-AR 阻断实验证明）
- BLA 内 NE + GC 协同 → 记忆巩固显著增强
- 这确立了"GC 需要情绪唤醒（NE）作为协同门控"的关键原理

**BLA 作为全脑 GC 记忆网络的必要枢纽**（Barsegyan 2019, PMC6452745）：
- 即便 GC 直接注射到**前额叶皮层（PrL）**，其记忆增强效果也完全依赖功能性 BLA
- BLA 失活（利多卡因）→ 完全阻断 PrL GC 的记忆增强
- 也依赖前扣带皮层（AIC）和背侧海马（dHPC）：多节点网络，BLA 为核心

### BLA 中的记忆再巩固去稳定化分子链（2026-07-10 新增）

LA（外侧杏仁核）不仅是恐惧记忆的写入位点，也是再巩固去稳定化事件的核心发生地。当已巩固的恐惧记忆被短暂再激活（单次CS，产生预测误差），以下分子级联在 BLA-LA 中展开：

```
预测误差信号（CS出现但US缺席）
  → GluN2B-NMDA 受体激活（Ro 25-6981 BLA内注射→阻断去稳定化）
  → Ca²⁺ 内流
  → CaMKII 激活（T286自磷酸化）
  → 20S 蛋白酶体调节亚基磷酸化（PMID:26779588）→ UPS 激活
  → GluA2-AMPA 受体内吞（TAT-GluA23Y 阻断→去稳定化失败）
  → Shank + GKAP 选择性降解（~2h，PSD-95 不降解）（PMID:18258863）
  → CP-AMPAR 出现（Ca²⁺ 通透型，使突触进入高敏感态）
```

**随后，在 1-6 小时内进行再稳定化**：
```
PKA / ERK / CaMKIV → CREB 磷酸化
  → Arc, zif268, BDNF 表达
  → 新蛋白合成 → 突触结构重建
  → 记忆重新锁定
```

**窗口内干预靶点**：
- 蛋白合成抑制剂（茴香霉素，仅实验用）→ 阻断再稳定化 → 记忆抹除
- β-AR 阻断（普萘洛尔）→ 干扰 NE 驱动的 PKA/CREB 信号 → 选择性消除情绪成分
- GR 拮抗（米非司酮）→ 阻断 GC 增强再稳定化 → Phase 2a RCT 未达主要终点（PMID:37159200）

### CRH 在 CeA 的中枢独立效应

CRH 不只是 HPA 轴的启动分子，也作为神经肽在 CeA **独立于外周 HPA 效应**直接调控防御行为：
- CeA 含高密度 CRH 神经元和 CRH₁R 受体
- BLA 激活 → CeA CRH 释放 → CRH₁R → 防御行为增强（冻结、逃跑）
- 肾上腺切除动物（无外周 GC）仍存在 CRH-CeA 介导的行为反应
- 慢性 CRH₁R 过激活是 PTSD 和广泛性焦虑的候选机制

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| LA突触LTP是恐惧记忆因果底物 | 光遗传LTP→恐惧；LTD→消除恐惧；再LTP→恢复恐惧 | PMID:24896183 | 高 |
| 条件反射后约20% LA神经元发展CS响应（稀疏代码） | 多通道电极记录+行为范式 | PMID:24908482 (PMC4103014) | 高 |
| ITC神经元是消退表达的必要条件 | 选择性免疫毒素损毁ITC→消退表达缺陷 | PMID:18615014 | 高 |
| BA中恐惧/消退神经元双群切换 | 多单元记录+逆行标记 | PMID:18615015 | 高 |
| vmPFC/IL激活强度预测消退回忆质量 | 人类fMRI多研究汇总 | PMID:22129456 (PMC4942586) | 中-高 |
| 突触竞争规则：初始突触权重高的LA神经元优先编码恐惧 | 光学LTP预增强+恐惧训练，小鼠 | PMID:34168140 (Nat Commun, 开放全文) | 高 |
| 消退印迹 = BLA奖励神经元（激活→奖励行为且抑制恐惧） | c-Fos-DREADD标记+激活，小鼠 | PMID:31952856 | 高（需独立重复） |
| 恐惧/消退印迹是不同细胞群（灭活IL消退印迹→恐惧重现） | Daun02灭活，大鼠 | PMID:38396226 | 中-高 |
| 情感价值可逆转：恐惧印迹重训→趋近行为（DG→BLA重路由） | TetTag+光遗传，小鼠 | PMID:25162525 | 高 |

## 连接

- [[ltp]] — LA突触LTP是恐惧记忆写入的分子机器；GC+NE协同驱动LA的L-LTP转化
- [[fear-conditioning]] — 外侧核LTP的行为诱导范式
- [[fear-extinction]] — 消退作为竞争性抑制记忆，依赖ITC和IL皮层；慢性应激损害消退回路
- [[hippocampal-circuit]] — 海马提供情景信号给BA，决定恐惧/消退哪套记忆被调取
- [[norepinephrine-locus-coeruleus]] — 蓝斑NE投射通过β-肾上腺素受体增强杏仁核LTP和恐惧记忆巩固；NE是GC效应的必要协同门控
- [[dopamine-reward-prediction-error]] — VTA DA投射到杏仁核调节奖励关联（与恐惧回路并行）
- [[engram-cells]] — LA恐惧印迹细胞（~20%稀疏）与海马场所细胞印迹遵循相同的竞争选择逻辑；BLA消退印迹 = 奖励神经元（Zhang 2020）；恐惧/消退印迹是不同细胞群（Luft 2024）；情感价值可逆转（Redondo 2014 DG→BLA重路由）
- [[glucocorticoid-stress-memory]] — BLA是GC记忆增强的必要枢纽；GC通过BLA GR基因组途径驱动L-LTP转化；CRH在CeA独立调控防御反应
- [[hpa-axis]] — HPA轴产生的GC在BLA实现记忆增强；CeM→PVN投射参与HPA激活正反馈
- [[memory-consolidation]] — BLA GC+NE协同驱动情绪显著性记忆的优先长期巩固
- [[memory-reconsolidation]] — BLA-LA 是再巩固去稳定化的核心位点：GluN2B-NMDA→CaMKII→UPS→Shank/GKAP 降解+GluA2 内吞的完整分子链在此发生
- [[olfactory-bulb]] — 杏仁核（皮质内侧核）直接接收嗅球僧帽/簇状细胞输出（无视丘中继），是所有感觉系统中唯一的"第一突触即情绪评估"设计；解释了气味为何能在意识觉知前触发强烈情绪反应（Proust效应的解剖基础）
- [[piriform-cortex]] — 梨状皮层→杏仁核投射叠加于嗅球→杏仁核的直接通路；梨状皮层编码粗粒度气味类别，杏仁核整合情感价值（Sagar et al. 2023 7T fMRI）
- [[orbitofrontal-cortex]] — BLA 与 OFC 形成双向价值学习回路：lOFC→BLA 写入结果特异性奖赏记忆（学习阶段），mOFC→BLA 检索记忆生成当前价值估计（决策阶段），BLA→lOFC 更新刺激-结果权变关系（Wassum 2022, DOI:10.7554/eLife.80926；Jenni et al. 2025, PMID:40068869）
- [[value-based-decision-making]] — BLA 是 OFC-BLA 价值决策回路中的记忆存储节点；OFC-BLA 双向连接是目标导向行为（vs. 习惯行为）的神经基础
- [[vmPFC]] — vmPFC（及其同源区 IL）通过 GABAergic 中间神经元对 CeM 的抑制，是认知重评和恐惧消退的皮层控制节点；vmPFC 对杏仁核的负向有效连接（Steward 2021, DCM）是情绪调节的主传导器；sgACC 过度激活（抑郁症）导致杏仁核慢性过度激活，形成负性情绪恶性回路（Drevets 1999, PMID:10415674；Price & Drevets 2010, PMID:19693001）
- [[emotion-regulation]] — 杏仁核是情绪调节的被调节目标；vmPFC→杏仁核的调控通路是情绪调节的核心神经基础
- [[cognitive-reappraisal]] — 认知重评通过 vlPFC→vmPFC→杏仁核三层级回路减少杏仁核激活（Ochsner 2002, PMID:12495527；He 2023, PMID:37507228）

## 未解问题

- Q-fear-human-amygdala-specificity（高优先级）：人类杏仁核功能架构与啮齿类的保守程度
- Q-fear-low-road-function（中优先级）：丘脑"低路"直接投射的恐惧学习独立贡献
- Q-fear-itc-bidirectionality（中优先级）：ITC在恐惧重现时的具体再平衡机制
- Q-extinction-reward-overlap（高优先级，2026-07-24新增）：BLA消退印迹细胞与奖励响应细胞的重叠率精确值；阻断BLA奖励通路是否导致消退失败（因果方向性验证）
- Q-vmPFC-03（高优先级，2026-08-25新增）：PTSD 中 vmPFC/IL 消退回忆功能失败的精确机制——连接减弱、PNNs 异常还是情景信号错误提取？（见 state/unresolved_questions.md）

## 修订历史

- 2026-07-24 · 修订 rev4 · 基于《恐惧的印迹与奖励的入侵》(#92) · LA亚核条目新增"突触可塑性竞争规则"（Jeong 2021 Nat Commun, PMID:34168140）；BA亚核条目新增"消退印迹=BLA奖励神经元"（Zhang 2020, PMID:31952856）和"恐惧/消退印迹是不同细胞群"（Luft 2024, PMID:38396226）；证据表新增4行；engram-cells连接注释扩展；未解问题新增Q-extinction-reward-overlap；key_sources/source_articles相应更新
- 2026-07-10 · 修订 rev3 · 基于《记忆再巩固》(#78) · 新增"BLA 中的记忆再巩固去稳定化分子链"机制节（GluN2B-NMDA→CaMKII→UPS→Shank/GKAP降解+GluA2内吞级联；再稳定化路径；窗口内干预靶点）；连接节新增 memory-reconsolidation；source_articles/related 相应更新
- 2026-07-09 · 修订 rev2 · 基于《记忆为什么最牢记住恐惧》一文 (#77) · 新增"GC与NE协同增强应激记忆"机制节（BLA必要枢纽、GC-NE协同门控、β-AR阻断实验）；新增"CRH在CeA的中枢独立效应"节；related新增glucocorticoid-stress-memory、hpa-axis、memory-consolidation；key_sources新增PMID:30877244、PMID:16310958、PMID:23968228；未解问题新增Q-fear-itc-bidirectionality
- 2026-07-26 · 修订 rev5 · 基于《气味的神经密码：从一个分子到一段记忆的四级变换》(#94) · 连接节新增 olfactory-bulb（杏仁核皮质内侧核直接接收嗅球输出，无视丘中继）和 piriform-cortex（梨状皮层→杏仁核投射，气味感知层级）；related和key_sources/source_articles相应更新
- 2026-08-21 · 修订 rev6 · 基于《价值的解剖：眶额皮层如何为选项定价》(#119) · 连接节新增 orbitofrontal-cortex（BLA↔OFC 双向价值记忆回路：lOFC→BLA 写入，mOFC→BLA 检索，BLA→lOFC 更新权变，Wassum 2022 & Jenni 2025）和 value-based-decision-making；related 新增 orbitofrontal-cortex、value-based-decision-making；key_sources 新增 DOI:10.7554/eLife.80926、PMID:40068869；source_articles 新增 2026-08-21
- 2026-05-30 · 创建 · 基于《当杏仁核学会恐惧》一文 · 初始置信度：高
- 2026-08-25 · 修订 rev7 · 基于《驯化杏仁核：vmPFC 与 sgACC》(#123) · 连接节新增 vmPFC（vmPFC 通过 GABAergic 中间神经元抑制 CeM、情绪调节和认知重评的核心通路）、emotion-regulation、cognitive-reappraisal；未解问题新增 Q-vmPFC-03；related 新增 vmPFC/emotion-regulation/cognitive-reappraisal；key_sources 新增 PMID:19693001/12495527/26617500；source_articles 新增 2026-08-25
- 2026-08-26 · 修订 rev8 · 基于《恐惧记忆的囚徒：PTSD》(#124) · related 新增 ptsd；opens_questions 新增 Q-ptsd-01；key_sources 新增 PMID:19748076（Milad 2009，杏仁核在 PTSD 消退回忆测试期间超激活的直接证据）、PMID:35352034（Ressler 2022，PTSD 杏仁核超反应性及其遗传机制）；来源文章新增 2026-08-26

## 来源文章

- [[2026-05-30-amygdala-fear-memory]]
- [[2026-07-09-glucocorticoids-stress-memory-amygdala]]
- [[2026-07-10-memory-reconsolidation-ptsd]]
- [[2026-07-24-amygdala-fear-engram-extinction-reward-neurons]]
- [[2026-07-26-olfactory-coding-smell-memory-limbic]]
- [[2026-08-21-orbitofrontal-cortex-value-decision-circuit]]
- [[2026-08-25-vmPFC-sgACC-emotion-regulation]]
- [[2026-08-26-ptsd-fear-circuit-neural-mechanism]]

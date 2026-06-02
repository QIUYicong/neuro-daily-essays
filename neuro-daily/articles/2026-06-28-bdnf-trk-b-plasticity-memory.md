# BDNF：大脑给自己的成长信号

**日期**：2026-06-28  
**文章编号**：#64  
**分类**：分子 / 突触 / 细胞 / 认知  
**slug**：`bdnf-trk-b-plasticity-memory`

---

## 今日核心问题

BDNF（脑源性神经营养因子）如何通过 TrkB 受体信号级联，在分子层面将"神经活动"翻译为突触强化的晚期维持、新生神经元的存活分化、以及持续一生的认知储备？为什么阿尔茨海默病会以系统性截断 BDNF/TrkB 信号作为破坏突触的早期步骤之一？

---

## 一句话摘要

BDNF 是大脑最重要的自产"成长信号"：它由神经活动诱导释放，通过 TrkB 受体触发三条平行信号通路（PI3K/Akt、MAPK/ERK、PLCγ），分别负责神经元存活、基因表达和突触可塑性；它是 LTP 后期维持（L-LTP）和成年海马神经发生不可或缺的分子驱动力；而它的前体 proBDNF 通过 p75NTR 发挥几乎相反的效果——促进 LTD 和突触弱化——使整个 BDNF 系统成为大脑精细调控突触增强与削弱的双向开关。

---

## 为什么重要

在过去二十年里，有一个发现一再从不同方向被证实：**几乎所有我们认为重要的脑可塑性过程，都有 BDNF 的参与**。

学习一个新技能时，BDNF 被释放到突触间隙，它帮助固化新形成的记忆轨迹。一个人坚持有氧运动，血清 BDNF 升高，海马体积增大（Erickson et al. 2011，PMID:21282661）。齿状回的新生神经元需要 BDNF/TrkB 信号才能存活和成熟。而阿尔茨海默病的早期标志之一，是海马和前额叶的 BDNF 水平下降——这早于大规模神经元死亡。

如果说突触是大脑的"书写单元"，那么 BDNF 就是书写工具的持续供应商。理解它的工作机制，是理解大脑如何从分子层面写就记忆、维持可塑性、并在疾病中走向崩溃的关键。

---

## 背景：神经营养因子家族

BDNF 属于**神经营养因子家族**（neurotrophin family），这个家族还包括：
- **NGF**（神经生长因子）：最早被发现（Rita Levi-Montalcini，1986 年诺贝尔奖），主要支持外周感觉和交感神经元
- **NT-3**（神经营养因子-3）：支持本体感觉神经元和小脑神经元
- **NT-4/5**（神经营养因子-4）：在感觉系统和海马有作用

BDNF 在中枢神经系统中表达最广、功能最多样。它在大脑皮层、海马（尤其是 CA1、CA3 和 DG）、杏仁核、小脑高度表达，与学习记忆相关区域高度重叠——这不是巧合，而是功能的直接反映。

BDNF 基因（人类在 11p13）受多个启动子调控（至少 8 个），不同神经活动模式会激活不同启动子，产生具有相同蛋白质编码序列但不同 5' UTR 的多种 mRNA 转录本。这种多启动子架构使 BDNF 的表达能够以极高的情境特异性响应不同类型的神经活动——光是这一点，就已经暗示了它在可塑性中的核心角色。

---

## 核心机制

### 一、两种命运：proBDNF 与成熟 BDNF 的阴阳图

BDNF 首先以**前体形式**（proBDNF）合成，约 32 kDa。proBDNF 在细胞内被 furin 或 proprotein convertase 部分切割，或者分泌到胞外后被 tPA（组织型纤溶酶原激活物）/纤溶酶系统切割，生成约 14 kDa 的**成熟 BDNF**（mature BDNF）。

这两种形式与不同受体结合，效果几乎相反：

| 形式 | 受体 | 主要效果 |
|------|------|---------|
| 成熟 BDNF | TrkB（高亲和力） | 促存活、促 LTP、促突触生长 |
| proBDNF | p75NTR（高亲和力） | 促凋亡、促 LTD、促突触弱化 |

2005 年，Woo 等人（PMID:16025106）在《Nature Neuroscience》发表了奠定这一yin-yang 图景的实验：他们用电子显微镜证明 p75NTR 定位于海马神经元的树突棘和轴突末梢；p75NTR 敲除小鼠表现出选择性的 NMDA 受体依赖性 LTD 损害（LTP 不受影响）。进一步机制是 proBDNF→p75NTR 激活后降低了 NR2B NMDA 受体亚型的表达，减弱了 NR2B 依赖性电流，从而削弱了 LTD 的诱导。

这意味着：**大脑对突触的最终调控，不仅取决于 BDNF 的释放量，还取决于它在胞外被怎样加工**。当 tPA 活性高时（往往在高频活动时），proBDNF 被更多地切割为成熟 BDNF，信号偏向 TrkB/LTP；当 tPA 活性低时，proBDNF 积累，信号偏向 p75NTR/LTD。这是一个将突触前活动与突触加工状态关联起来的精妙调控层。

### 二、TrkB 信号级联：三条路，三种功能

成熟 BDNF 与 TrkB 结合后，TrkB 二聚化并自磷酸化胞内激酶域的多个酪氨酸残基，激活三条平行的下游通路（Colucci-D'Amato et al. 2020，PMID:33096634，PMC7589016）：

**（1）PLCγ 通路 → 突触可塑性**  
TrkB-Y816 磷酸化招募 PLCγ → 水解 PIP₂ → DAG + IP₃ → 一方面通过 IP₃ 释放细胞内钙，另一方面 DAG 激活 PKC → PKC 磷酸化 AMPA 受体亚基 GluA1（S831）→ 提高单通道电导。此外，Ca²⁺ 激活 CaMKII，形成与 NMDA 受体独立的并行突触增强通路。

**（2）MAPK/ERK 通路 → 基因表达与结构可塑性**  
TrkB-Y490 磷酸化招募 Shc/Grb2/Sos → Ras→Raf→MEK→ERK1/2。ERK 进入细胞核激活转录因子 CREB（Ser133 磷酸化）→ 触发即早基因（c-Fos、Arc、Zif268）的转录。ERK 还促进细胞骨架蛋白（cypin）的合成和树突生长分支。

**（3）PI3K/Akt/mTOR 通路 → 存活、蛋白质合成**  
TrkB-Y490 同时招募 PI3K→PIP₃→Akt→磷酸化 BAD（抗凋亡）和激活 mTOR→4E-BP1/S6K1 磷酸化 → 蛋白质合成起始因子活化 → 局部蛋白合成增加。这是 L-LTP 和神经发生所需的新蛋白质的关键供应机制。

这三条通路不是线性串联的，而是并行运作，各有侧重：PLCγ 通路起效最快（毫秒-秒级），MAPK 通路起效中等（分钟级，需要基因转录），PI3K/mTOR 通路涉及蛋白合成，时间尺度最长（分钟到小时）。三者共同解释了 BDNF 为何能同时影响 LTP 的早期表达和晚期维持。

### 三、BDNF 与 LTP：活动制造自身的催化剂

这里有一个优美的正反馈循环：

1. 高频突触活动（θ-burst）诱导 NMDA 受体激活和 Ca²⁺ 内流  
2. Ca²⁺ 信号经多条通路上调 BDNF 基因的转录（CREB 通路）  
3. BDNF 被释放到突触间隙（**活动依赖性分泌**）  
4. BDNF/TrkB 信号进一步强化突触增强，特别是通过激活局部 Arc mRNA 翻译

关键证据来自 Bramham 和 Messaoudi 的"突触固结假说"（PMID:16099088，2005）：BDNF 不仅是 LTP 的触发器之一，也是 LTP 由"早期"（E-LTP，数小时内）过渡到"晚期"（L-LTP，数天至数周）的**必要信使**。L-LTP 的标志是需要新的蛋白质合成——而 BDNF 通过 PI3K/mTOR 通路和局部 Arc mRNA 翻译正是这种蛋白质合成的主要驱动力。

Lu et al. 2008（PMID:17942328，PMC2387254）回顾了多条关键证据：
- BDNF 缺乏（KO 小鼠）：E-LTP 基本正常，L-LTP 严重受损
- 外源性 BDNF 应用：即便在蛋白质合成抑制剂存在时，也能将 E-LTP 转变为持续性的 LTP（提示 BDNF 对已合成蛋白的调控，而非仅靠诱导新蛋白合成）
- Arc（一种 IEG 蛋白）：被 BDNF 信号诱导的局部翻译，其 mRNA 沿树突运输并在活跃突触处被翻译——弧形蛋白（Arc）随后调节 AMPA 受体的内吞

因此，BDNF 在 LTP 中的精确角色可以描述为：**它是突触活动的下游分子，也是让突触强化能够在时间中稳定的"固化剂"**。活动产生 BDNF，BDNF 催化活动的长期后果。

### 四、BDNF 与成年神经发生：新神经元的生死裁判

在海马齿状回颗粒细胞下区（SGZ），新生神经元的命运极大程度上取决于 BDNF/TrkB 信号的强度（Colucci-D'Amato et al. 2020）：

- **存活**：PI3K/Akt 的抗凋亡信号是未成熟新生神经元在 4-8 周危险期内存活的关键。BDNF 通过磷酸化 BAD、激活 Bcl-2 家族抗凋亡成员来维持线粒体膜完整性。
- **分化**：MAPK/ERK 通路和 PLCγ 通路共同促进神经母细胞从增殖向分化的过渡，以及轴突的延伸和树突的复杂化。
- **突触整合**：BDNF/TrkB 信号促进新生颗粒细胞在关键期（~4-6 周）内形成功能性突触，包括接受来自内嗅皮层的穿孔通路输入。

Erickson et al. 2011（PMID:21282661，PMC3041121）给出了令人印象深刻的人类证据：120 名老年人随机接受有氧运动训练（步行组）或拉伸运动（对照组）一年。结果：步行组前海马体积增大约 **2%**，相当于逆转了约 1-2 年的年龄相关萎缩；而这一结构变化与血清 BDNF 水平的升高显著相关。对照组则出现约 1.4% 的体积下降（正常老化速率）。

这项研究把实验室里的分子观察——运动提高 BDNF，BDNF 促进神经发生——直接联系到了人脑可测量的结构变化。

---

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| BDNF 对 L-LTP 必要（E-LTP 不受影响） | BDNF KO 小鼠电生理记录 | 综述 PMID:16099088，PMID:17942328 (PMC2387254) | 高（啮齿类） |
| BDNF 促进 Arc mRNA 的突触局部翻译 | 树突 Arc mRNA 荧光原位杂交 + TrkB 抑制 | PMID:16099088 (综述) | 中-高 |
| proBDNF→p75NTR 选择性促进 LTD；p75NTR KO 损害 LTD 不损 LTP | 基因敲除小鼠 + 海马 LTP/LTD 电生理 | PMID:16025106 (Woo et al. 2005) | 高（小鼠） |
| 有氧运动 1 年使人类前海马体积增大 ~2%，与血清 BDNF 正相关 | 随机对照试验，120 名老年人，结构 MRI + 血清 BDNF | PMID:21282661 (PMC3041121) | 高（人类，RCT） |
| Val66Met 携带者 BDNF 活动依赖性分泌受损，海马激活减弱，空间记忆下降 | 细胞成像 + fMRI + 行为学，N12 家系 + 99 对照 | PMID:12553913 (Egan et al. 2003, Cell) | 高（人类遗传+影像） |
| AD 小鼠模型中，认知改善需 BDNF 提升 + 神经发生同时激活（不可各行其是） | 5×FAD 小鼠 + 运动/遗传/药理多组，认知行为测试 | PMID:30190379 (PMC6149542, Choi et al. 2018, Science) | 高（动物，多组）；不可直接推广人类 |
| AD 脑中海马/前额叶 BDNF 蛋白水平下降；Aβ 干扰 TrkB→CREB 信号轴 | 死后脑组织定量 + APPswe/PS1ΔE9 模型 | 综述 PMID:33096634 (PMC7589016)，PMID:23674053 | 中-高（人死后组织 + 动物） |

---

## 一个比喻（及其有效与失效之处）

想象 BDNF 是一种"建筑许可证"。

神经元正在努力工作（高频放电），于是自动申请建筑许可证（释放 BDNF）；许可证激活了三种施工队：第一队（PLCγ）立刻去加固窗户（AMPA 受体电导）；第二队（ERK）去重新绘制图纸（基因转录）；第三队（Akt）去采购更多建材（蛋白合成）。如果许可证（BDNF）不来，第三队就不会工作，临时加固的窗户会慢慢恢复原样（E-LTP 消退）。

**比喻有效之处**：它抓住了"活动触发→信号→稳定化"这一核心逻辑，以及 L-LTP 依赖 BDNF 媒介的蛋白合成这一关键机制。

**比喻失效之处**：它没有表现出 proBDNF 的反向作用（有一种"拆除许可证"也在同时发放）；它也掩盖了 BDNF 分泌的精确时空性（它在哪个树突棘被释放，只影响那个树突棘）；以及 BDNF 本身也是信号的**接收者**（它被活动触发而上调，但也能被活动进一步影响其受体表达）——这是一个多层嵌套的反馈系统，而不是线性的建筑流程。

---

## 如何改变我们对大脑的理解

在 BDNF 被充分理解之前，突触可塑性主要被描述为一个局部、即时的 Hebbian 过程：巧合检测（NMDA 受体）→ Ca²⁺ 内流 → AMPA 受体插入。这是一个精密的微观机器，但它解释不了为什么记忆能持续数年，也解释不了为什么运动和环境丰富性会促进学习，更解释不了为什么大脑有一套从分子层面调节自身可塑性阈值的机制。

BDNF 的发现和机制研究，提供了这些问题的一部分答案：

1. **L-LTP 的蛋白质合成如何被选择性触发**：不是所有突触都能得到 BDNF 的"许可证"，只有那些被高频活动激活、能够活动依赖性释放 BDNF 的突触才能进入 L-LTP 程序。这解释了为什么记忆写入有"阈值效应"——偶尔的弱刺激不会留下永久印迹。

2. **经验如何改变大脑的物理结构**：BDNF 是连接"经验"（运动、学习）与"结构"（海马体积、树突复杂度）的分子桥梁。这一联系让"大脑的可塑性终身持续"从哲学宣言变成了可测量的生物学现实。

3. **突触增强和减弱的统一调控框架**：proBDNF/p75NTR（→LTD）与成熟 BDNF/TrkB（→LTP）共享一个前体分子，意味着细胞外蛋白酶的活动本身就是突触可塑性方向的调控机制——活动不只决定激活还是抑制，还决定了通过胞外加工途径来切换 LTP 还是 LTD 程序。

4. **阿尔茨海默病的早期可干预窗口**：如果 BDNF/TrkB 信号的丧失先于大规模神经元死亡，而这种丧失又是 Aβ 诱导的（可逆的——见 Shankar et al. 2007 关于突触沉默可逆性），那么在 BDNF 信号尚未完全崩溃的早期阶段，增强 BDNF/TrkB 通路可能是延缓认知衰退的真实干预点。

---

## 争议与未解问题

**1. Val66Met 的真实风险权重**

Egan et al. 2003 发现 Val66Met（rs6265）携带者 BDNF 的活动依赖性分泌受损，但 BDNF 的总量不变——问题在于 Met-BDNF 前体无法正常定位至分泌颗粒和突触。然而，Meta 分析结果不一：有些研究表明 Met 等位基因增加 AD 或抑郁风险，另一些则未发现显著关联（综述 PMID:33096634）。这可能因为 Val66Met 的效应大小本身偏小，在不同人群和环境背景（锻炼习惯、压力暴露）下会被放大或掩盖。Val66Met 对认知的"净贡献"至今仍有争议，不应被单纯解读为"坏基因"。

**2. BDNF 治疗的血脑屏障问题**

如果 BDNF 信号下降是多种神经系统疾病的共同病理节点，为什么 BDNF 本身的给药还没有成为临床治疗？根本障碍在于 BDNF 是一个约 14 kDa 的蛋白质，**不能有效穿越血脑屏障**。静脉注射后几乎没有达到治疗浓度的可能。基因治疗（腺相关病毒载体直接递送到海马）在动物模型中显示疗效（Nagahara et al. 2009），但从动物到人类的转化面临递送效率、安全性和靶向精确度等挑战（Lu et al. 2013，PMID:23674053）。小分子 TrkB 激动剂（如 7,8-二羟黄酮，7,8-DHF）能穿越血脑屏障，动物实验结果令人鼓舞，但人类临床试验数据极为有限。

**3. 因果方向问题（在 AD 中）**

Choi et al. 2018 的实验（PMID:30190379）证明在 AD 小鼠模型中，AHN 早于 AD 病理受损，且恢复 AHN + BDNF 可改善认知——但这能说明 AHN/BDNF 下降是 AD 认知损害的"因"吗？还是说它们都是 Aβ/tau 积累的平行结果（"果"）？从相关性到因果性的跃迁需要纵向数据：在 AHN/BDNF 开始下降时（但 Aβ 还很少时）就启动干预，看是否能延缓认知症状。这类人类前瞻性研究目前几乎不存在。

**4. BDNF 在不同脑区和不同细胞类型的差异**

本文主要聚焦海马 CA1/DG。但 BDNF 在皮层、杏仁核、纹状体的作用可能有重要差异。例如，在纹状体，多巴胺能系统对 BDNF 信号有独特调制；在杏仁核，BDNF 参与恐惧记忆的习得和消退（见 Meis et al. 2020，PMID:32845430）。BDNF 的"通用可塑性因子"标签有简化之嫌——它在不同情境下扮演的具体角色需要区分，不能简单外推。

---

## 与 AI 的对照

BDNF 在大脑中扮演的角色，让人想到深度学习中的**学习率调度器**（learning rate scheduler）。

BDNF 水平决定了突触的"学习速率"和"稳定化能力"：高 BDNF 环境下，新突触更容易被强化（高学习率），且增强更持久（低遗忘率）；低 BDNF 环境下，突触更新困难，已有强化也难以维持。

但这个类比有一个根本差异：在人工神经网络中，学习率是**全局的**——所有权重用同一个调度器。而 BDNF 的分泌是**突触局部的**、**活动依赖的**——它只在刚刚被激活的突触附近以高浓度出现，其他突触不受影响。这是大脑避免"灾难性遗忘"的关键机制之一：不是全局更新，而是精准标注、局部固化。

当前大型神经网络正在摸索各种局部学习规则（Hebbian、对比学习）来近似大脑的这种局部性。BDNF 的机制提示，真正的关键可能不只是"哪个突触被激活"，而是"激活事件是否触发了一套精确的局部加工程序"——分子的局部合成与释放，才是记忆精确写入的保险机制。

---

## 今日概念卡片

**BDNF（脑源性神经营养因子）**

- 核心角色：神经活动→突触稳定化的分子桥梁
- 受体：成熟 BDNF→TrkB（三通路：PLCγ/ERK/Akt）；proBDNF→p75NTR（促凋亡/LTD）
- LTP：L-LTP（而非 E-LTP）的必要条件；通过促进 Arc 等 mRNA 的局部翻译实现
- 神经发生：促进 SGZ 新生神经元存活与成熟的主要 TrkB 配体
- 运动效应：有氧运动上调血清 BDNF，增大人类海马体积（Erickson 2011）
- AD：BDNF/TrkB 信号早期丧失；BDNF + 神经发生需协同干预才能改善认知（Choi 2018）
- 基因变异：Val66Met→活动依赖性分泌受损→认知储备下降（Egan 2003）
- 治疗瓶颈：不穿血脑屏障；小分子 TrkB 激动剂仍在临床早期

---

## 今日认知地图更新

```
今天新增节点：
  bdnf → 连接 ltp（L-LTP 维持必要条件）、adult-neurogenesis（存活/成熟驱动力）、
         alzheimers-disease（早期受损信号通路）、exercise（上调效应，结构变化）

填补悬空引用：
  ltp.md 中的 [[bdnf]] 悬空引用 → 已建页
  adult-neurogenesis.md 中的 [[bdnf]] 悬空引用 → 已建页

修订：
  ltp.md → 补充 BDNF/TrkB 在 L-LTP 维持中的详细机制
  adult-neurogenesis.md → 补充 BDNF 对 SGZ 新生神经元存活的具体通路

今天的认知地图跃迁：
  从"LTP 是 NMDA-Ca²⁺-AMPA 的单向因果链"
  进化为"LTP 是 Hebbian 触发 + BDNF 催化固化 + proBDNF 竞争弱化 的三角博弈"
```

---

## 参考来源

1. **Bramham CR, Messaoudi E. (2005)** BDNF function in adult synaptic plasticity: the synaptic consolidation hypothesis. *Progress in Neurobiology* 76(2):99-125. PMID:16099088. DOI:10.1016/j.pneurobio.2005.06.003. **[摘要；全文需订阅，未读取全文]**

2. **Colucci-D'Amato L, Speranza L, Volpicelli F. (2020)** Neurotrophic Factor BDNF, Physiological Functions and Therapeutic Potential in Depression, Neurodegeneration and Brain Cancer. *International Journal of Molecular Sciences* 21(20):7777. PMID:33096634. PMCID:PMC7589016. **[开放全文已读取]**

3. **Lu Y, Christian K, Lu B. (2008)** BDNF: a key regulator for protein synthesis-dependent LTP and long-term memory? *Neurobiology of Learning and Memory* 89(3):312-23. PMID:17942328. PMCID:PMC2387254. **[开放全文已读取摘要；主要内容来自综述分析]**

4. **Woo NH, Teng HK, Siao CJ, et al. (2005)** Activation of p75NTR by proBDNF facilitates hippocampal long-term depression. *Nature Neuroscience* 8(8):1069-77. PMID:16025106. DOI:10.1038/nn1510. **[摘要；全文需订阅，未读取全文]**

5. **Egan MF, Kojima M, Callicott JH, et al. (2003)** The BDNF val66met polymorphism affects activity-dependent secretion of BDNF and human memory and hippocampal function. *Cell* 112(2):257-69. PMID:12553913. **[摘要已读；标注为 free article]**

6. **Erickson KI, Voss MW, Prakash RS, et al. (2011)** Exercise training increases size of hippocampus and improves memory. *Proceedings of the National Academy of Sciences* 108(7):3017-22. PMID:21282661. PMCID:PMC3041121. **[开放全文已读取摘要]**

7. **Choi SH, Bylykbashi E, Chatila ZK, et al. (2018)** Combined adult neurogenesis and BDNF mimic exercise effects on cognition in an Alzheimer's mouse model. *Science* 361(6406):eaan8821. PMID:30190379. PMCID:PMC6149542. **[开放全文已读取关键数据]**

8. **Lu B, Nagappan G, Guan X, Nathan PJ, Wren P. (2013)** BDNF-based synaptic repair as a disease-modifying strategy for neurodegenerative diseases. *Nature Reviews Neuroscience* 14(6):401-16. PMID:23674053. DOI:10.1038/nrn3505. **[摘要；全文需订阅，未读取全文]**

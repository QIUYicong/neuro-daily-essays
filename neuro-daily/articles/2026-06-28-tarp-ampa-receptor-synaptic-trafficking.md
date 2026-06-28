# AMPA 受体的突触之旅：TARP 辅助亚基如何引导受体驻扎、改造门控并参与 LTP

**日期**：2026-06-28  
**编号**：#184  
**文件名**：2026-06-28-tarp-ampa-receptor-synaptic-trafficking.md  
**核心层级**：分子 × 突触 × 细胞  
**课程脊柱**：脊柱 4（学习与记忆：LTP 的突触后表达机制）

---

## 今日核心问题

AMPA 受体是快速突触传递的主角，也是 LTP"突触权重增强"的物理体现。但 AMPA 受体是在细胞体的内质网（ER）里合成的，它必须经历一段漫长旅程才能抵达特定树突棘的突触后致密区（PSD），精确卡位在等待它的"槽位"里。

**这段旅程如何完成？是什么分子充当导航员、搬运工和锚点？当 LTP 被诱导时，这套机制如何被临时征用，将更多受体快速锁定到突触？以及：单单改变 TARP 与其锚点的亲和力，是否足以人工制造出与真实 LTP 等价的突触增强？**

---

## 一句话摘要

TARP（跨膜 AMPA 受体调控蛋白）是 AMPA 受体从 ER 到突触的全程伴侣：帮助受体离开 ER，通过与 PSD-95 的 PDZ 相互作用将受体锚定于突触"槽位"，并深刻改变受体的门控动力学；LTP 时，CaMKII 磷酸化 TARP 的 C 末端，使其与 PSD-95 亲和力骤升，将扩散中的受体捕获并锁定——2022 年的体外重构实验证明，这一 TARP-PSD-95 相互作用不需要任何其他因子，就足以完整重构 LTP。

---

## 为什么重要

LTP 的故事大多从 Ca²⁺ 内流讲起，从 CaMKII 激活讲起，但很少有人问：CaMKII 被激活之后，信号如何物理地变成"更多 AMPA 受体"在突触上？这中间需要一套精密的分子机器——而 TARP 正是这台机器的核心轴承。理解 TARP 的机制，等于补全了突触可塑性最后一公里的完整因果链。

更重要的是，TARP 家族中的 γ-8 成员在海马中富集，是年龄依赖性认知衰退、失神癫痫、阿尔茨海默病、酒精依赖等多种疾病的分子焦点，也是正在临床研发的选择性抗癫痫药物的靶点。理解 TARP，意味着理解了一批脑疾病在突触层面的分子病理。

---

## 背景：突触的"停车位"问题

一个 CA1 锥体神经元有约 10,000 个树突棘，每个棘上的 PSD 面积各不相同，对应的 AMPA 受体数量也从 0 到近 100 个不等。这不是随机分布：突触权重被精确编码在 PSD 面积与 AMPA 受体密度的乘积中。

但 AMPA 受体是在细胞体（以及部分近端树突）的 ER 里合成的。它们是四聚体，在成熟海马 CA1 区，约 80% 是 GluA1/GluA2 异聚体。这些受体必须：

1. 通过 ER 的质量控制检查，折叠正确才能出口；
2. 经高尔基体处理后，沿树突运输；
3. 到达附近树突膜，通过胞吐暴露在细胞外；
4. 沿树突膜横向扩散，进入 PSD；
5. 在 PSD 内被锚定——否则会继续扩散出去。

哪一步出错，AMPA 受体就无法就位。而 TARP 几乎参与了其中每一步。

---

## 发现史：一只仰望星空的小鼠

1998 年，遗传学家们描述了一种自发突变小鼠系——stargazer（"凝星鼠"）。这只小鼠反复将头向上抬起，好像在凝视星空，同时伴随共济失调和失神癫痫。突变基因是 *CACNG2*，编码一个四次跨膜蛋白，因其序列与电压门控钙通道 γ 亚基有远亲同源性，最初被命名为"钙通道 γ-2 亚基"（Letts et al., 1998；PMID:9799228）。

但在 2000 年，一项小脑研究带来了震撼：**Chen et al. 在《Nature》发表实验，证明 stargazin 小鼠的小脑颗粒细胞完全不能在细胞表面表达 AMPA 受体**（PMID:11140673）。这些细胞里有正常量的 AMPA 受体蛋白，但受体全部被困在细胞内。原来，这个"钙通道亚基"的真实身份是 AMPA 受体的专属伴侣蛋白——没有它，受体出不了门。

"TARP"这个名字——**Transmembrane AMPA Receptor Regulatory Proteins**（跨膜 AMPA 受体调控蛋白）——在 2003–2005 年间被正式提出和推广，以描述 stargazin 代表的这一新蛋白家族（Tomita et al., 2005；PMID:15858532）。

---

## TARP 的结构：四次跨膜，三段功能

TARP 是四次跨膜蛋白，横跨突触后膜四次，露出三段功能区域：

**胞外段**：直接接触 AMPA 受体的配体结合结构域（LBD）外表面，用非共价键抱住受体。2025 年《Nature Communications》报道了第一个 TARP γ-2 的高分辨率冷冻电镜结构，揭示了 EX1 环和 EX2 环如何与 AMPA 受体胞外穿孔环（M1/M4）精密接触——正是这段接触让 TARP"坐"在受体上并改变门控。

**跨膜段**（TM1–TM4）：锚定在膜中，帮助 AMPA 受体正确定向。TM1 和 TM2 之间的 EX1 loop 对 TARP 与 AMPA 受体的结合特别关键。

**胞内 C 末端**：末端含一个 PDZ 配体序列（–TTPV 等），可以插入 PSD-95 的 PDZ1 和 PDZ2 结构域——这是 AMPA 受体锚定于突触的分子锁。C 末端上方有一段带正电荷的 **polybasic region**，其磷酸化状态（由 CaMKII 调控）决定了 TARP 与 PSD-95 的亲和力高低——直接决定突触能"停"多少 AMPA 受体。

2021 年，两项背靠背《Nature》论文（PMID:33981040；PMID:34079129）分别解析了海马 GluA1/GluA2 与 TARP γ-8 和 CNIH2 共组成的异型八聚体复合物的冷冻电镜结构，首次在原子分辨率揭示了 TARP γ-8 与 AMPA 受体的空间关系：γ-8 和 CNIH2 占据非随机的特定位置，γ-8 与 AMPAR 的化学计量比直接解释了 JNJ-55511118 等选择性抑制剂的亚饱和抑制曲线。

---

## 三项功能：伴、搬、锚

### 功能 1：ER 出口许可证

没有 TARP，AMPA 受体会被 ER 滞留系统检测为"不完整"，无法离开。Chen et al. 2000 的关键实验证明，用野生型 stargazin cDNA 转染 stargazer 小脑颗粒细胞，AMPA 受体立刻能出现在表面（PMID:11140673）。

2022 年，Mol. Psychiatry 报道了人类 stargazin V143L 突变（PMID:35256745）：这个单个氨基酸替换发生在第三跨膜结构域，导致 AMPA 受体-stargazin 界面不稳定，AMPA 受体无法正常离开 ER，在纯合子敲入小鼠中产生海马 LTP 缺陷、树突棘成熟异常和认知/社交行为障碍——是 TARP 在 ER 出口环节不可替代性的直接人类遗传学证据。

### 功能 2：突触外膜的交付与横向扩散

受体离开 ER 后进入再循环内体，在活动依赖情境下，内体囊泡在树突棘附近的树突膜融合（胞吐），将 AMPA 受体"喷"到树突外表面。胞吐位点通常不在突触正下方，受体必须横向扩散才能进入 PSD。

**单粒子追踪（SPT）技术**（由 Choquet 实验室等先驱开创）直接可视化了这一过程：荧光标记的 AMPA 受体在 PSD 外自由扩散，进入 PSD 后运动骤然减缓——这是"扩散陷阱（diffusional trap）"的直接影像证据。TARP 与 PSD-95 的相互作用就是这个"陷阱"的分子本质（Bessa-Neto & Choquet, 2023；PMID:37105372）。

### 功能 3：突触锚定——"停车位"的分子锁

TARP 的 C 末端 PDZ 配体插入 PSD-95 的 PDZ1/2 结构域。PSD-95 本身通过 N 末端棕榈酰化固定在突触后膜，其 PDZ1 和 PDZ2 以串联方式排列，可同时接纳多个 TARP。

这就是**突触槽位（synaptic slot）模型**的物理基础：PSD-95 分子数量决定了可以容纳多少 TARP/AMPA 受体复合物。Schnell et al. 2002（Science，PMID:12201694）第一个用遗传学直接证明：PSD-95 PDZ1/2 突变使突触 AMPA 受体数量骤降；过量表达 PSD-95 则使突触 AMPA 受体增加。

---

## 改造门控：TARP 不只是搬运工

Tomita et al. 2005（Nature，PMID:15858532）系统比较了 TARP 家族各成员对 AMPA 受体门控动力学的影响，结论震惊了领域：**TARP 根本性地改变了 AMPA 受体的电生理性质**。

当 stargazin 结合到 AMPA 受体上时：

**失敏减慢（Slowed desensitization）**：没有 TARP 的受体在谷氨酸持续存在时约 3ms 内完成失敏。有 TARP 后，这个时间延长至约 15–30ms——突触电流时程大幅延长。

**失活减缓（Slowed deactivation）**：谷氨酸脱离后受体关闭速度也因 TARP 减缓，进一步延长突触电流。

**亲和力提升（Increased glutamate affinity）**：谷氨酸对 AMPA 受体的 EC₅₀ 降低约 10 倍。突触间隙中谷氨酸峰值浓度高但下降极快（亚毫秒量级）；更高的亲和力意味着受体能响应更低浓度的谷氨酸，提高信号传递可靠性。

**再激活能力（Resensitization）**：某些 TARP 亚型（尤其是 γ-8）可以让已失敏的受体在谷氨酸持续存在时重新开放——在纯受体中基本不可能。这意味着 TARP 不仅延长响应，还允许受体在高频刺激下"回弹"。

这些发现彻底更新了领域认知：我们之前测量到的"突触 AMPA 受体"的动力学，其实是 TARP-AMPAR 复合物的动力学，而非纯受体的性质。

2025 年《Nat. Struct. Mol. Biol.》的冷冻电镜研究（PMID:40954371）进一步揭示了这些门控效应的结构基础：TARP 通过接触 AMPA 受体 TM1/M4 的细胞外段，稳定激活态受体构象，延缓其进入失敏态。

---

## LTP 的分子锁扣：CaMKII 磷酸化 TARP

现在来到最关键的联系——TARP 如何参与 LTP。

**基线状态**：unphosphorylated stargazin 的 C 末端 polybasic region（带正电荷）与突触后膜的负电性磷脂（PIP₂、磷脂酰丝氨酸）发生静电吸引，将 C 末端"吸"到膜上，PDZ 配体被掩蔽，与 PSD-95 的亲和力相对低。AMPA 受体可以进出 PSD，维持低速的横向扩散平衡。

**LTP 诱导时**：高频刺激激活 NMDA 受体，Ca²⁺ 大量内流，CaMKII 被激活并进入 PSD。CaMKII 磷酸化 stargazin C 末端 polybasic region 的多个丝氨酸（包括 Ser-277、Ser-281、Thr-282 等）——磷酸基团的负电荷**中和了 polybasic region 的正电荷**，静电吸引消失，C 末端从膜上"弹出"，PDZ 配体充分暴露，与 PSD-95 的亲和力骤升约 10–30 倍。

**净效果**：在 CaMKII 的驱动下，突触 PSD 内的 AMPA 受体被大量"锁定"，横向扩散出去的受体大幅减少，进入 PSD 的受体被高效捕获。突触 AMPA 受体数量净增加。

这个"**扩散陷阱**"机制在 2023 年被一项利落的化遗传学实验直接证明（Park et al., 2023；PMID:37471228）：研究者设计了 ExSYTE 工具——强力霉素控制的嵌合蛋白，专门靶向 TARP γ-8 C 末端与膜脂质的静电锚定。关键结论：

1. **单独破坏 TARP-脂质锚定**（不需要 NMDA 受体激活，不需要 Ca²⁺ 内流），即足以产生 LTP 样的突触增强；
2. 在杏仁核神经元中激活 ExSYTE，可以模拟条件性恐惧训练产生的冻僵行为；
3. ExSYTE 激活后再进行生理性 LTP 诱导，LTP 被遮蔽（occlusion）——说明两者共享同一突触槽位；
4. 停药后效应完全可逆。

这是对"TARP-脂质界面是 LTP 的核心分子开关"的最直接因果证明。

### 人工重构 LTP

Ravi et al. 2022（Cell Reports；PMID:36223737）通过正交突变策略进一步证明了 TARP-PSD-95 相互作用的充分性：设计了只能彼此结合（不能与野生型配体结合）的 TARP 和 PSD-95 工程蛋白。当两者共表达时，基础突触传递和 LTP 均完全被救出——**TARP PDZ 配体与 PSD-95 PDZ 结构域的相互作用，是 AMPA 受体突触运输和 LTP 表达所需的最小充分核心机制**。不需要其他因子。

---

## TARP 家族：一族蛋白，各司其职

经典 TARP 有四个成员：γ-2（stargazin/CACNG2）、γ-3（CACNG3）、γ-4（CACNG4）、γ-8（CACNG8）。另有非典型 TARP：γ-5、γ-7（通常负向调节某些受体亚型）。

**脑区特异性**是理解 TARP 的关键维度：

| TARP | 主要表达脑区 | 主要功能特点 |
|------|------------|-----------|
| γ-2（stargazin） | 小脑颗粒细胞、海马、皮层 | 最先发现；小脑功能不可缺少 |
| γ-3 | 皮层、纹状体（广泛但低水平） | 部分补偿 γ-2 |
| γ-4 | 发育期广泛，成年后降低 | 发育关键期 AMPAR 定位的主力 |
| **γ-8（CACNG8）** | **海马高度特异性（尤其 CA1）** | **海马 LTP 和空间记忆的专属 TARP** |

**γ-8 的特殊重要性**：在 CA1 锥体细胞，γ-8 是 AMPA 受体定位的主力军，而非 γ-2。γ-8 缺失导致海马 AMPA 受体数量减少约 50%，LTP 幅度显著降低，空间记忆受损——但小脑功能基本正常（依赖 γ-2）。这种精准的脑区特异性使 γ-8 成为了理想的选择性药理靶点。

2023 年的 PET 成像研究（Yamasaki et al.；PMID:36655318；PMC10196744）在活体大鼠中直接定量了 γ-8 的分布：海马分布容积（1.4 ± 0.3 mL/cm³）远高于皮层、纹状体和小脑——首次在活体动物中以体内成像方式证实了 γ-8 的海马富集。这为临床转化研究提供了分子成像工具。

---

## 衰老与 TARP：认知衰退的新分子机制

2024 年，一项重要研究（He et al., Aging Cell；PMID:39380368；PMC11709088）揭示了 TARP γ-8 在年龄依赖性认知衰退中的因果作用，通过以下因果链：

**老化 → 海马 Cav1.3（L 型钙通道）过度激活 → pCaMKII-α 水平降低 → TARP γ-8 磷酸化不足 → 突触 AMPA 受体数量减少 → LTP 缺陷 → 空间记忆受损**

实验证明：
- 在老龄小鼠（22–27 月）海马中，TARPγ-8 蛋白水平显著低于年轻对照；
- 在年轻小鼠海马中特异性敲低 TARPγ-8，重现了老化表型（LTP 缺陷+空间记忆下降）；
- 在老龄小鼠海马中表达人类 TARPγ-8，同时恢复了 LTP 和认知功能；
- 用尼非地平（L 型钙通道阻断剂）处理老龄小鼠，pCaMKII-α 和 TARPγ-8 水平均被恢复。

这一发现直接连接了"异常钙通道活性→CaMKII-TARP-AMPAR 轴失调→记忆老化"这条因果链，为老年认知药物干预提供了可验证的分子靶点。

---

## 疾病视角：失神癫痫、智力障碍、阿尔茨海默病

**失神癫痫**：stargazer 小鼠（γ-2 缺失）是最早也是最重要的失神癫痫动物模型之一。皮层快速放电中间神经元（Fast Spiking interneurons）失去 TARPγ-2 后无法获得功能性 AMPA 受体，抑制/兴奋比例失调，产生 3Hz 棘慢波放电。

**智力障碍**：人类 stargazin V143L 突变（PMID:35256745）直接证明 TARP 功能缺失导致海马 LTP 不能正常诱导，产生认知和社交行为障碍。

**阿尔茨海默病**：在 APP/PS1 转基因小鼠中，升高的 caspase-1/IL-1β（神经炎症标志）直接破坏 stargazin-GluA1 相互作用，阻止 GluA1 到达神经元表面；caspase-1 抑制恢复了 stargazin-GluA1 结合，并改善了小鼠记忆表现（PMID:33509083，2021）。

**药物靶点**：TARPγ-8 选择性 AMPA 受体负性变构调节剂（如 JNJ-55511118/LY3130481/CERC-611）正在开发为抗癫痫和镇痛药物，其海马选择性恰好来源于 γ-8 在海马的富集。2023 年《Nature Communications》报告了 GluA1/GluA2-γ8 复合物结合多种候选化合物的冷冻电镜结构，为选择性药物设计提供了结构基础（PMC10039940）。

---

## 比喻：停车场与通行证

想象每个突触是一个有限车位的停车场，AMPA 受体是停车的车辆。TARP 则是三重系统：
- **驾驶证**：没有 TARP，车无法从工厂（ER）开出来；
- **导航 App**：引导车辆从胞吐位点横向扩散到突触入口；
- **停车卡**：没有 TARP 与 PSD-95 的配对，车进了停车场也会很快被驱逐出去。

LTP 时，CaMKII 的磷酸化相当于临时**升级了停车卡的磁性**——同样的车有了更强的锁定能力，停得更久、更稳。

**比喻的有效边界**：有效之处在于，它准确捕捉了 TARP 多步骤伴侣角色，以及磷酸化"升级亲和力"的核心机制。失效之处在于，真实系统是动态平衡——AMPA 受体在突触内外持续扩散，LTP 增加的是"平均停留时间"，而非绝对锁定。同时，PSD 面积（停车场大小）本身在 LTP 后也会扩大（结构性 LTP），超出了比喻的描述能力。

---

## 它如何改变我们对大脑的理解

**LTP 的最后一公里**：TARP 的磷酸化机制填补了 CaMKII 激活到"更多 AMPA 受体在突触"之间的空白。CaMKII 不只磷酸化 GluA1 S831（LTP 的经典解释）——更关键的一步是通过磷酸化 TARP 的 polybasic region，解除静电掩蔽，让 PDZ 配体暴露，捕获扩散中的受体。

**突触强度的物理上限**：TARP-PSD95 槽位模型提供了突触强度上限的概念框架：最终受制于 PSD 中 PSD-95 分子的数量。PSD-95 数量增加（结构性 LTP）扩大容量上限。这将突触可塑性分为两个时间尺度的层次：快速层（TARP 磷酸化驱动的受体捕获，数分钟内）和慢速结构层（PSD 扩大，数小时至数天）。

**辅助亚基重塑通道生理**：在 TARP 之前，"离子通道的生理性质"被视为由亚基本身决定的固有属性。TARP 的门控调制作用表明，离子通道在脑内的实际行为由通道蛋白与长期结合的辅助蛋白共同决定——没有 TARP，测量到的 AMPA 受体动力学与突触上的真实行为有质的差异。这一认识范式已延伸到 NMDA 受体（NETO 亚基）、钠通道（β 亚基）等。

---

## 争议与未解问题

**Q-tarp-01（高优先级）**：TARP 帮助 AMPA 受体离开 ER 的具体分子机制是什么？TARP 是屏蔽了某个 ER 滞留信号，还是帮助受体达到 COP II 囊泡识别的构象？V143L 突变的分子动力学研究（PMID:39895898）提供了线索，但完整机制仍未阐明。

**Q-tarp-02（中优先级）**：不同 TARP 家族成员对 AMPA 受体门控动力学的调制强度不同（γ-2/γ-8 效果强于 γ-3），这种差异的结构基础是什么？是 EX1 loop 序列差异还是跨膜段的细节？

**Q-tarp-03（中优先级）**：LTP 后期（数小时至数天），TARP 的磷酸化状态靠什么维持？PKMζ 和 KIBRA 提供了 LTP 持久维持的机制，但它们与 TARP 磷酸化维持是否有直接关联？KIBRA-PKMζ 是否通过维持 AMPA 受体在 PSD 内的锚定状态来实现记忆的分子永生（与本系列上篇 #181 的直接接口）？

**Q-tarp-04（高优先级）**：γ-8 特异性靶向治疗的安全性：γ-8 AMPA 受体负性变构调节剂已进入临床，但 γ-8 在海马外（额叶皮层、杏仁核）也有表达，抑制这些区域的 γ-8 是否会引起认知副作用？如何实现真正的脑区选择性？

---

## 与 AI 的对照

Transformer 的多头自注意力有一个关键步骤：通过 Softmax 将注意力权重归一为概率，决定每个位置最终"注意"哪些信息。

TARP-PSD95 槽位机制与之在结构上有某种对应：PSD-95 的 PDZ 槽位数量决定一个突触能"锁定"多少 AMPA 受体，TARP 的磷酸化状态（亲和力）类似注意力权重——磷酸化高 = 亲和力高 = 更多受体被该 PSD-95 "捕获"。

但有一个根本区别：Transformer 的注意力是无状态的前向传播，每次推理都重新计算；TARP 磷酸化状态可以持续数小时至数天，这种**持续性**是生物突触实现"记忆"而非"在线处理"的关键。另一个区别是学习规则：Transformer 由反向传播的梯度更新；突触 TARP 磷酸化由局部 NMDA 受体 Ca²⁺ 内流决定。一个是全局优化，一个是局部赫布规则——两者指向"某些连接应当被加权"的共同目标，但哲学上截然不同。

还有一个 Transformer 尚未解决的问题：自注意力机制没有"槽位上限"——一个 token 可以被无限多的头"关注"；而 TARP/PSD-95 槽位模型引入了突触强度的**物理上限**，这与神经系统的能量约束和有限资源相呼应。这种约束是否也是生物记忆系统泛化能力的来源之一？一个值得深思的开放问题。

---

## 今日概念卡片

**TARP（Transmembrane AMPA Receptor Regulatory Proteins）**

- **定义**：AMPA 受体的辅助亚基蛋白家族，4次跨膜；功能三重奏：①ER 出口许可；②PSD-95 PDZ 相互作用锚定受体于突触；③改变受体门控动力学（失敏减慢/亲和力提升/再激活）。
- **关键成员**：γ-2（stargazin，小脑/海马）；γ-8（海马特异，LTP/空间记忆/认知衰老核心）。
- **LTP 机制**：CaMKII 磷酸化 TARP C 末端 polybasic region → 静电掩蔽解除 → PDZ 配体暴露 → PSD-95 亲和力骤升 → 受体被扩散陷阱捕获锁定。
- **发现**：stargazer 小鼠（1998，失神癫痫+共济失调）→ 2000 年 Chen et al. 证明 stargazin 是 AMPA 受体表面定位的必要条件 → 2022 年人工 TARP/PSD-95 复合物完整重构 LTP。

---

## 今日认知地图更新

- **新建 wiki 页**：`wiki/concepts/tarp-auxiliary-subunit.md`（首次建立独立节点，补全 ampa-receptor 页的悬空引用）
- **修订 wiki 页**：`wiki/concepts/ampa-receptor.md`（rev4→rev5）：更新 TARP 相互作用描述；补充 CaMKII-stargazin 磷酸化/扩散陷阱机制；填充 [[tarp-auxiliary-subunit]] 链接
- **修订 wiki 页**：`wiki/neurons/camkii.md`（+1 修订）：新增 TARP γ-2 和 γ-8 作为 CaMKII 在 LTP 中的关键突触后底物

---

## 参考来源

| 编号 | 来源 | PMID / PMCID | 全文可用性 | 本文使用 |
|------|------|-------------|-----------|---------|
| 1 | Letts VA et al. (1998). The mouse stargazer gene encodes a neuronal Ca2+-channel γ subunit. *Nat Genet*. | PMID:9799228 | 摘要 | stargazer 小鼠发现 |
| 2 | Chen L et al. (2000). Stargazin regulates synaptic targeting of AMPA receptors by two distinct mechanisms. *Nature*. | PMID:11140673 | 摘要（全文未确认开放） | stargazin 是 AMPAR ER 出口和突触定位的必要条件 |
| 3 | Schnell E et al. (2002). Direct interactions between PSD-95 and stargazin control synaptic AMPA receptor number. *Science*. | PMID:12201694 | 摘要 | PSD-95-stargazin 直接控制突触 AMPAR 数量（槽位模型） |
| 4 | Tomita S et al. (2005). Functional studies and distribution define a family of transmembrane AMPA receptor regulatory proteins. *Nature*. | PMID:15858532 | 摘要 | TARP 家族系统比较：失敏减慢/亲和力提升 |
| 5 | Ravi A et al. (2022). Long-term potentiation reconstituted with an artificial TARP/PSD-95 complex. *Cell Rep*. | PMID:36223737; PMCID:PMC9797105 | **开放全文** | TARP-PSD-95 相互作用是 LTP 充分条件（正交突变实验） |
| 6 | Park J et al. (2023). Chemogenetic regulation of the TARP-lipid interaction mimics LTP and reversibly modifies behavior. *Cell Rep*. | PMID:37471228 | 摘要（PMC 待确认） | ExSYTE 工具：TARP-脂质界面是 LTP 核心开关 |
| 7 | Bessa-Neto D & Choquet D (2023). Molecular mechanisms of AMPA receptor reversible stabilization at synapses. *Mol Cell Neurosci*. | PMID:37105372 | 摘要 | 扩散陷阱机制综述 |
| 8 | Yu J et al. (2021). Hippocampal AMPA receptor assemblies and mechanism of allosteric inhibition. *Nature*. | PMID:33981040 | 摘要（PMC 待确认） | GluA1/A2-TARPγ-8 复合物冷冻电镜结构 |
| 9 | Zhang D et al. (2021). Gating and modulation of a hetero-octameric AMPA glutamate receptor. *Nature*. | PMID:34079129 | 摘要 | GluA1/A2/TARPγ-8/CNIH2 异型八聚体结构与门控 |
| 10 | Watson JF et al. (2021). AMPA receptor anchoring at CA1 synapses is determined by N-terminal domain and TARP gamma-8 interactions. *Nat Commun*. | PMID:34426577; PMCID:PMC8382838 | **开放全文** | CA1 突触 AMPAR 锚定双重机制（TARP + NTD） |
| 11 | Yamasaki T et al. (2023). Small-animal PET study for noninvasive quantification of TARP gamma-8 in the brain. *J Cereb Blood Flow Metab*. | PMID:36655318; PMCID:PMC10196744 | **开放全文** | 活体 PET 定量海马 TARPγ-8 富集 |
| 12 | He Y et al. (2024). CaMKIIα-TARPγ8 signaling mediates hippocampal synaptic impairment in aging. *Aging Cell*. | PMID:39380368; PMCID:PMC11709088 | **开放全文** | Cav1.3→CaMKII↓→TARPγ-8↓→LTP/记忆衰退的因果链 |
| 13 | Guergueltcheva V et al. (2022). Human CACNG2/Stargazin V143L mutation associated with intellectual disability. *Mol Psychiatry*. | PMID:35256745 | 摘要 | 人类 stargazin 突变：LTP 缺陷+认知障碍 |
| 14 | Zhang T et al. (2021). Stargazin-GluA1 interaction disrupted by caspase-1 in Alzheimer's disease. *Mol Medicine*. | PMID:33509083 | 摘要 | 阿尔茨海默病中 caspase-1 破坏 TARP-AMPAR 结合 |
| 15 | Nicoll RA (2017). A brief history of long-term potentiation. *Neuron*. | PMID:28103477 | 摘要 | LTP 机制综述，TARP 的历史地位 |

**全文可用数量**：5 篇开放全文（PMC9797105、PMC8382838、PMC10196744、PMC11709088 及 PMID:36223737）；其余使用摘要/综述。

---

*本文是"AMPA 受体命运三部曲"的第三篇：#64（BDNF-TrkB，LTP 信号触发）→ #181（KIBRA-PKMζ，LTP 长期维持）→ 本篇（TARP-PSD-95，受体突触定位的分子导航）。三篇合在一起，给出了从突触活动信号到持久突触增强的完整分子故事：Ca²⁺→CaMKII→{GluA1 S831 磷酸化；stargazin 磷酸化→AMPAR 捕获}→{BDNF-TrkB 持久性信号；PKMζ-KIBRA 长期维持}。*

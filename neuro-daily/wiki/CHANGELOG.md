# Wiki 变更日志

> 每日固结步骤产生的 wiki 变更记录。新条目置于顶部。

---

## 2026-10-12（文章 #177：马尔-阿尔布斯-伊藤模型——小脑如何用攀爬纤维的教学信号学会精确运动）

**创建新页（1 页）**：
- `wiki/theories/marr-albus-ito.md`（rev1）：MAI框架完整理论——攀爬纤维（IO）作为教学信号；PF-PC LTD作为突触实现；Schonewille 2011（PMID:21482355）证明LTD非唯一必要条件；Yang & Lisberger 2014（PMID:24814344）CS时长梯度编码误差幅度（-0.70 sp/s per ms）；Zebrin阳/阴性分区差异化学习策略；分布式协同可塑性框架（Gao 2012，PMID:22895474）；status=mainstream, confidence=high；填补 `marr-albus-ito` 悬空引用

**修订既有页（2 页）**：
- `wiki/concepts/climbing-fiber-error-signal.md` rev2→rev3：新增 marr-albus-ito 连接（CF是MAI教学信号物理实现）；related、source_articles 更新
- `wiki/concepts/cerebellar-ltd.md` rev4→rev5：新增 marr-albus-ito 连接（LTD是MAI核心突触实现但非唯一必要条件）；source_articles 更新

**图谱变化**：
- 新节点（1）：marr-albus-ito
- 新边（10）：marr-albus-ito→{cerebellar-ltd, climbing-fiber-error-signal, forward-model, purkinje-cell, granule-cell, parallel-fiber, cerebellum, deep-cerebellar-nuclei}；climbing-fiber-error-signal→marr-albus-ito(supports)；cerebellar-ltd→marr-albus-ito(supports)
- 悬空引用 `marr-albus-ito` 已解决（从 dangling_references 移除）
- 图谱统计：395→397 节点，2254→2264 边

**登记矛盾**：无新矛盾（既有 C-2026-08-08-01 关于CF奖励信号争议，今日文章已整合引用但未新增裁决依据，维持 open）

**新增未解问题**：Q-mai-01（IO如何将误差幅度编码为CS时长）、Q-mai-02（Zebrin模块协调）、Q-mai-03（DCN与皮层LTD的存储主次问题）

---

## 2026-06-16（文章 #195：社会行为的分子二重奏——加压素系统）

**创建新页（2 页）**：
- `wiki/systems/vasopressin-system.md`（rev1）：AVP 9肽结构；PVN/SON（非性别化）和 BNST/MeA（睾酮依赖、雄性 2-3 倍）双重来源；V1aR（VP→配对键；LS→社会辨别）和 V1bR（CA2 突触前→社会记忆/攻击；垂体→HPA协同）；*avpr1a* 微卫星基因机制；klinical trials（balovaptan 失败，鼻内 AVP 中等效果）；status=established, confidence=high
- `wiki/neurons/hippocampal-ca2.md`（rev1）：CA2 锥体神经元特征（V1bR+OXTR 共表达、LTP 抵抗）；CA2→LS 突触前 V1bR 门控（AVP 增强传递 82%）；社会状态切换模型；OXR+V1bR 协同社会记忆（双 KO 失代偿）；status=mainstream, confidence=high

**修订既有页（2 页）**：
- `wiki/concepts/pair-bond.md` rev1→rev2：新增 AVP/VP V1aR 雄性配对机制；*avpr1a* 微卫星遗传基础；伴侣保护攻击 AVP 机制；更新 related/prerequisites/key_sources
- `wiki/systems/oxytocin-system.md` rev1→rev2：新增 vasopressin-system 和 hippocampal-ca2-social-memory 连接；补充 OT/AVP 分子孪生关系；CA2 OXR+V1bR 协同功能

**图谱变化**：
- 新节点（3）：vasopressin-system, hippocampal-ca2-social-memory, lateral-septum
- 新边（13）：vasopressin-system↔oxytocin-system(related)；vasopressin-system→pair-bond(supports)；vasopressin-system→hippocampal-ca2-social-memory(mechanism-of)；vasopressin-system→hpa-axis(regulates)；vasopressin-system→amygdala(part-of)；vasopressin-system→lateral-septum(regulates)；hippocampal-ca2-social-memory→{vasopressin-system, oxytocin-system, hippocampal-circuit, lateral-septum}；lateral-septum→hippocampal-ca2-social-memory(related)；pair-bond→vasopressin-system(related)
- 图谱统计：393→396 节点，2241→2254 边

**登记矛盾**：无新矛盾（AVP 在 ASD 中的临床结果相悖已在文章中如实呈现并标注为不确定性，未录入 contested_claims，因其属于临床证据不足而非科学模型冲突）

**新增未解问题**：Q-AVP-01~04（见 vasopressin-system.md）

---

## 2026-10-11（文章 #173：宇宙中最大的展开器——小脑颗粒细胞与平行纤维展开编码）

**创建新页（2 页）**：
- `wiki/neurons/granule-cell.md`（rev1）：颗粒细胞形态（直径 5-7μm）；低扇入（4-7 MF/GC）；glomerulus 微结构；展开编码的计算原理；高尔基细胞门控；任务依赖编码密度（Xie et al. 2023）；status=established, confidence=high
- `wiki/concepts/parallel-fiber.md`（rev1）：T 形分叉几何（3-7mm）；每 PF 接触 300-500 PC；每 PC 接受约 150,000 PF；on-beam/off-beam 空间锐化；LTD 时序窗 50-150ms（峰值 80ms）；eCB（CB1R）必要性；Marr-Albus-Ito 理论连接；status=established, confidence=high

**修订既有页（2 页）**：
- `wiki/concepts/cerebellar-ltd.md` rev3→rev4：新增 Safo & Regehr 2008 LTD 时序窗（50-150ms）及 CB1R 必要性证据；key_sources 补充 PMID:17669443；修订历史追加
- `wiki/neurons/purkinje-cell.md` rev1→rev2：新增 granule-cell 和 parallel-fiber 链接；澄清 PF 接触数量（~150,000-175,000/PC）及几何关系

**图谱变化**：
- 新节点（3）：granule-cell, parallel-fiber, expansion-coding
- 新边（12）：granule-cell→{parallel-fiber(part-of), cerebellum(part-of), cerebellar-ltd(supports), expansion-coding(mechanism-of)}；parallel-fiber→{purkinje-cell(regulates), cerebellar-ltd(mechanism-of), climbing-fiber-error-signal(related), expansion-coding(supports)}；purkinje-cell→granule-cell(related)；cerebellar-ltd→parallel-fiber(mechanism-of)；endocannabinoid-system→cerebellar-ltd(regulates)；expansion-coding→marr-albus-ito(related)
- 图谱统计：390→393 节点，2229→2241 边
- 悬空引用 parallel-fiber 已解决

**登记矛盾**：无新矛盾（LTD 时序窗与既有记录的 PF+CF 同时激活描述相符，新的定量数据是精化而非冲突）

**新增未解问题**：Q-gc-01（颗粒细胞编码密度动态调整机制）、Q-gc-02（展开假说 vs 液态机框架的区分）、Q-pf-01（平行纤维正交走向的演化最优性）

---

## 2026-06-16（文章 #194：社会大脑的肽类密码——催产素系统如何从分子到联结构建社会神经回路）

**创建新页（2 页）**：
- `wiki/systems/oxytocin-system.md`（rev1）：催产素系统综合概述；双重身份（垂体激素+中枢调质）；OXTR Gq→Ca²⁺信号级联；PVN→CeA（抗焦虑）/PVN→NAc（社会奖励）/OT-DA串扰三条关键投射；物种/个体OXTR分布差异；配对后从头OT-eCB耦合（Borie 2022）；CeA星形胶质细胞OXTR（Wahis 2021）；争议（鼻内OT到脑量/社会特异 vs 一般焦虑抑制）；status=established, confidence=high
- `wiki/concepts/pair-bond.md`（rev1）：草原田鼠配对键神经机制（OT+DA双必要条件）；NAc OXTR密度决定单配性/杂交性；配对后从头OT-eCB耦合（性别特异机制但行为趋同）；Q-OT-03（人类同构问题）；status=established, confidence=high

**修订既有页（2 页）**：
- `wiki/systems/amygdala.md` rev5→rev6：related新增 oxytocin-system；opens_questions新增 Q-OT-04；key_sources新增 PMID:33589833/37248645；source_articles新增当日文章；updated→2026-06-16；修订历史追加一行（PVN→CeA OT投射；CeA星形胶质细胞OXTR）
- `wiki/systems/neuromodulator-systems.md` rev4→rev5：related新增 oxytocin-system/endocannabinoid-system；opens_questions新增 Q-OT-01；source_articles新增当日文章；updated→2026-06-16；修订历史追加一行（催产素作为第五类神经调质）

**图谱变化**：
- 新节点（2）：oxytocin-system, pair-bond
- 新边（10）：oxytocin-system→amygdala(regulates)、dopamine-system(regulates)、endocannabinoid-system(regulates)、hpa-axis(regulates)、neuromodulator-systems(is-a)、pair-bond(mechanism-of)；pair-bond→dopamine-system(mechanism-of)、endocannabinoid-system(related)；fear-extinction→oxytocin-system(related)；oxytocin-system→fear-extinction(supports)
- 图谱统计：388→390 节点，2219→2229 边

**登记矛盾**：无新矛盾（催产素社会特异 vs 一般焦虑抑制之争已在article中并列陈述但不在wiki主张层面形成直接冲突，后续若有解决性研究则登记C条目）

**新增未解问题**：Q-OT-01（鼻内OT脑内到达率）、Q-OT-02（ASD治疗有效性条件）、Q-OT-03（人类配对键机制）、Q-OT-04（CeA胶质OXTR在其他脑区分布）

---

## 2026-06-15（文章 #193：逆向信使——内源性大麻素系统如何从突触后端重写突触规则）

**创建新页（4 页）**：
- `wiki/concepts/endocannabinoid-system.md`（rev1）：ECS 综合概述；两种配体（2-AG/AEA）、三种 2-AG 动员模式（CaER/RER/Ca²⁺-assisted RER）、CB1R 双路径信号（βγ-VGCC 短期 / αi-AC-PKA 长期）、跨脑区分布；status=established, confidence=high
- `wiki/concepts/dsi-dse.md`（rev1）：去极化诱发抑制性/兴奋性抑制；完整信号级联；DSI vs DSE 功能区别；DGLα-KO 遗传证明；status=established, confidence=high
- `wiki/neurons/cb1-receptor.md`（rev1）：CB1R 分子机制（Gi/o 偶联、βγ-VGCC、αi-AC-PKA）；脑区分布（CCK+ GABA 末梢 vs 谷氨酸末梢）；eCB-LTD 联合规则；status=established, confidence=high
- `wiki/concepts/2-ag.md`（rev1）：2-AG 的合成（DGLα）、降解（MAGL 85%/ABHD6 15%）、空间范围（20μm）、与 AEA 的系统对比；DGLα-KO 遗传直接证明；status=established, confidence=high

**修订既有页（2 页）**：
- `wiki/concepts/fear-extinction.md` rev3→rev4：新增 vmPFC→BLA eCB-LTD 机制小节（Gunduz-Cinar 2023，PMC10592324）；新增 PTSD-eCB 含义；related 新增 endocannabinoid-system/cb1-receptor/endocannabinoid-ltd；key_sources 新增 PMID:37480845
- `wiki/concepts/endocannabinoid-ltd.md` rev1→rev2：新增"跨脑区视角"小节（海马/小脑/BLA 的 eCB-LTD）；related 新增 endocannabinoid-system/dsi-dse/2-ag/fear-extinction；key_sources 新增 PMID:23040807/37480845

**图谱变化**：
- 新节点（4）：endocannabinoid-system, dsi-dse, cb1-receptor, 2-ag
- 新边（19）：ECS 系统关系链（endocannabinoid-system → fear-extinction / pain-matrix / descending-pain-modulation / endogenous-opioids / synaptic-transmission；cb1-receptor ↔ ECS / VGCC / DSI / LTD；2-ag ↔ cb1-receptor / DSI-DSE）
- 图谱统计：384→388 节点，2200→2219 边
- **填补悬空引用**：cb1-receptor（被 endocannabinoid-ltd 引用但原无节点 → 现创建）

**登记矛盾**：无（本文所述机制均有多重独立重复；未与既有 wiki 主张产生冲突）

**新增未解问题**：Q-ecb-01（eCB-LTD 靶蛋白）、Q-ecb-02（AEA 转运）、Q-ecb-03（FAAH/MAGL 临床安全性）、Q-ecb-04（vmPFC→BLA eCB 在 PTSD 中的状态）

---

## 2026-06-14（维护修复：补全 topic_ledger #190 缺失条目）

**情景层维护**：
- `state/topic_ledger.json`：补全文章 #190（nociception-pain-pathways，2026-06-14）缺失条目。原因：第 #191/#192 运行时读取的 topic_ledger 版本早于 #190 写入版本，导致 #190 条目被覆盖丢失（lost update）。总条目数从 172 → 173 条（total_articles 仍为 192，计数正确）。

---

## 2026-06-14（文章 #192：同一把钥匙，三扇门——内源性阿片系统如何统一镇痛、欢愉与成瘾）

**创建新页（4 页）**：
- `wiki/concepts/endogenous-opioids.md`（rev1）：内源性阿片系统（μ/δ/κ/NOP 四类受体 + 四族肽 β-内啡肽/脑啡肽/强啡肽/孤啡肽）；共同 Gi/Go 信号逻辑；PAG-镇痛、VTA-奖励、安慰剂-认知三大功能模块；**填补 descending-pain-modulation.md 中的悬空引用**；status=established, confidence=high
- `wiki/concepts/mu-opioid-receptor.md`（rev1）：μ 受体（OPRM1 编码）分子机制（AC抑制+GIRK+Cav抑制）、PAG/VTA/NAc 分布、偏向信号争议；status=established, confidence=high
- `wiki/concepts/kappa-opioid-receptor.md`（rev1）：κ 受体 + 强啡肽轴，烦躁不快功能，应激/成瘾戒断负性情感机制；status=established, confidence=high
- `wiki/concepts/placebo-analgesia.md`（rev1）：安慰剂通过认知预期激活 μ-阿片系统（PET ¹¹C-卡芬太尼直接证据，Zubieta 2005）；pregenual ACC/dlPFC/NAc 为关键激活区；与内感受预测编码的联系；status=established, confidence=high

**修订既有页（2 页）**：
- `wiki/concepts/descending-pain-modulation.md` rev1→rev2：补充 Lau et al. 2020 突触前去抑制实证（脑片电生理）；补充 Zubieta 2005 安慰剂 PET 证据；新增 related 链接（mu-opioid-receptor、placebo-analgesia）
- `wiki/systems/vta.md` rev1→rev2：新增 μ 受体 VTA GABA 去抑制机制、"喜欢"vs"想要"分离、慢性疼痛 VTA MOR 脱敏；新增 related（endogenous-opioids、mu-opioid-receptor）

**图谱变化**：
- 新节点（4）：endogenous-opioids, mu-opioid-receptor, kappa-opioid-receptor, placebo-analgesia
- 新边（15）：阿片系统核心关系链（镇痛、奖励、安慰剂、成瘾交叉路径）
- 图谱统计：380→384 节点，2185→2200 边
- **悬空引用填补**：endogenous-opioids（被 descending-pain-modulation 引用）；placebo-analgesia（被 interoception 引用）

**登记矛盾（0 条新增）**：
无新矛盾。偏向信号假说（Gi vs β-arrestin）已在 mu-opioid-receptor.md 中标注为 contested，暂不升级为 contested_claims（属于现役临床研究争议，等待更多人类数据）。

**新增未解问题（4 条）**：
- Q-opioid-01（高）：GRAB opioid sensor 追踪自然行为中内源性阿片肽实时释放
- Q-opioid-02（高）：μ/δ/κ 受体在情绪调节中的独立功能分工
- Q-opioid-03（中）：跑步者愉悦感中阿片 vs 内源性大麻素的贡献比例
- Q-opioid-04（中）：社会联结中内啡肽与催产素时序关系

---

## 2026-06-14（文章 #191：身体的诗学——内感受预测编码如何从心跳塑造情绪感受）

**创建新页**：
- `wiki/concepts/allostasis.md`（rev1）：稳态预测——大脑预测性调节身体资源需求，情绪=身体预算状态的主观体验；支持稳态的网络（下丘脑/PAG/NTS+前岛叶/ACC/杏仁核）与情绪网络高度重叠（Kleckner 2017 N=591三样本fMRI验证）；status=mainstream, confidence=high
- `wiki/concepts/cardiac-interoception.md`（rev1）：心脏内感受——压力感受器→NTS→杏仁核/岛叶通路；心脏收缩期特异性加速威胁刺激意识突破（Ozturk 2025 CFS范式）；收缩期放大 vs 舒张期效应待统一解释；status=emerging, confidence=medium

**修订页面**：
- `wiki/concepts/interoception.md`（rev1→rev2）：新增EPIC模型机制细节（内感受预测-误差-更新循环）；稳态-情绪网络重叠证据（Kleckner 2017）；精度加权机制与焦虑假说（Seth & Friston 2016）；心脏收缩期感知优先窗口（Ozturk 2025）；内感受三维框架（Garfinkel 2015）；related新增allostasis/cardiac-interoception/ACC；开放问题新增Q-intero-01/02

**图谱变更**：380 节点（+2：allostasis, cardiac-interoception），2185 条边（+12：allostasis→interoception/anterior-insula/predictive-coding/ACC/hpa-axis/amygdala；cardiac-interoception→interoception/anterior-insula/amygdala/nociception；双向 interoception↔allostasis；anterior-insula→allostasis）

**新增未解问题**：Q-intero-01（内感受精度加权的直接神经测量缺乏）；Q-intero-02（精度加权的发育轨迹/关键期）；Q-cardiac-intero-01（心脏收缩期"放大vs抑制"矛盾的统一解释）；Q-cardiac-intero-02（IA高个体的前岛叶预测精度差异）；Q-allostasis-01（稳态预测负担的个体弹性差异机制）

**登记矛盾**：无新矛盾（心脏收缩期效应的放大vs抑制矛盾已在cardiac-interoception页面争议节中并列呈现，登记为开放争议节，暂未正式登记至contested_claims因仅为单项研究vs早期研究，证据基础差异过大，待第二篇独立重复后登记）

---

## 2026-06-13（文章 #188：失控的门卫——颞叶癫痫与海马回路的五层级防御体系）

**创建新页**：
- `wiki/diseases/temporal-lobe-epilepsy.md`（rev1）：颞叶癫痫——KCC2下调（GABA去极化化）+ HIPP细胞选择性死亡 + 苔状纤维出芽 + CCK/PV/CR中间神经元差异性丧失 + SNr-PF去抑制网络放大；status=established, confidence=high
- `wiki/concepts/dentate-gyrus-gate.md`（rev1）：齿状回门控——颗粒细胞稀疏性（-80mV静息，频率适应）+ HIPP细胞反馈抑制；正常时防止EC→CA3同步传播，也实现模式分离；TLE中失效；status=mainstream, confidence=medium

**修订页面**：
- `wiki/concepts/ei-balance.md`（rev3→rev4）：新增颞叶癫痫的五层级 E/I 失衡（KCC2去极化化、CCK+负向缩放紧急刹车、MGE中间神经元移植绕过KCC2失效）；related 新增 temporal-lobe-epilepsy, dentate-gyrus-gate；key_sources 新增 PMC13024002/PMC8832350

**图谱变更**：370 节点（+2：temporal-lobe-epilepsy, dentate-gyrus-gate），2145 条边（+14：TLE/dentate-gate 与 hippocampal-circuit/ei-balance/pv-interneurons/place-cell/sharp-wave-ripples/adult-neurogenesis/basal-ganglia 的新连接）

**新增未解问题**：Q-tle-01（人类TLE中KCC2下调神经元是否构成发作起始区核心？）；Q-tle-02（CA2在人类iEEG中是否可识别为发作放大器？）；Q-tle-03（SNr→PF回路能否成为人类DBS新靶点？）

**登记矛盾**：无新矛盾（苔状纤维出芽的因果争议已在文章中明确列为开放性问题，既有证据并列呈现）

**新增悬空引用**：mossy-fiber-sprouting（苔状纤维出芽专页待建）；kcc2-chloride-homeostasis（KCC2专页待建）

---

## 2026-06-13（文章 #187：当感觉自相矛盾时，大脑如何裁决？——多感觉贝叶斯整合）

**创建新页**：
- `wiki/theories/bayesian-multisensory-integration.md`（rev1）：贝叶斯多感觉整合——MLE可靠性加权（Ernst & Banks 2002）；感觉运动学习贝叶斯先验（Körding & Wolpert 2004）；概率群体编码PPC（Ma et al. 2006）；MSTd一致性神经元（Gu et al. 2008）；因果推断框架（Shams & Beierholm 2010）；status=established, confidence=high

**修订页面**：
- `wiki/concepts/optimal-feedback-control.md`（rev2→rev3）：新增"贝叶斯多感觉整合是OFC卡尔曼估计器的感觉输入端"这一关键连接；related 加入 bayesian-multisensory-integration；连接节点和修订历史更新

**图谱变更**：368 节点（+1：bayesian-multisensory-integration），2131 条边（+7：bayesian-multisensory-integration 与 optimal-feedback-control/predictive-coding/forward-model/muscle-spindle/active-inference/mst-medial-superior-temporal/optimal-feedback-control 的新连接）

**新增未解问题**：Q-msi-01（vmPFC在因果推断P(C=1)中的角色）；Q-msi-02（PPC理论需Neuropixels直接验证）；Q-msi-03（发育轨迹：婴儿何时具备MLE整合）

**登记矛盾**：无（亚最优整合证据Wozny2010为边界条件差异，非根本矛盾；如实在文章中说明）

**新增悬空引用**：causal-inference-perception（因果推断专页待建）；active-inference（主动推断专页待建）

---

## 2026-06-13（文章 #186：小脑运动学习的分布式革命——PF LTD 只是冰山一角）

**创建新页**：
- `wiki/neurons/molecular-layer-interneurons.md`（rev1）：分子层中间神经元（MLI，星状+篮状细胞）——GABA 能前馈抑制；PF-MLI LTP（与 PF-PC LTD 方向相反）；与 PF-PC LTD 协同驱动运动学习（Zhu 2024 计算模型）；status=established, confidence=high

**修订页面**：
- `wiki/concepts/cerebellar-ltd.md`（rev2→rev3）：新增 PF-MLI LTP 协同机制（Zhu 2024，PMID:38574161）；激发性核橄榄通路（Wang 2023，PMID:37474638）；related 新增 molecular-layer-interneurons/deep-cerebellar-nuclei/inferior-olive；新增未解问题 Q-cb-06/Q-cb-07/Q-cb-08；key_sources 补充三篇新来源
- `wiki/systems/inferior-olive.md`（rev1→rev2）：新增激发性核橄榄通路（顶核→IO 谷氨酸能投射，Wang 2023）；更新当前理解为双通路调控模型；新增 Q-cb-06；key_sources 补充 PMID:37474638

**图谱变更**：367 节点（+1：molecular-layer-interneurons），2124 条边（+6：molecular-layer-interneurons 与 purkinje-cell/cerebellar-ltd/cerebellum/climbing-fiber-error-signal/parallel-fiber 的新连接；deep-cerebellar-nuclei→inferior-olive 激发性调控）

**新增未解问题**：Q-cb-06（激发性 vs 抑制性核橄榄通路的分工与时间协调）；Q-cb-07（小脑自监督学习的理论含义）；Q-cb-08（model-free mapping vs 内部模型框架的真实分歧）

**登记矛盾**：无新矛盾（MLI 协同机制暂不与既有主张冲突；Schonewille 2011 悖论已有计算层面解释）

**新增悬空引用**：molecular-layer-interneurons 中的 parallel-fiber 节点是否独立存在需核查

---

## 2026-06-13（文章 #185：学习写进突触——皮质纹状体 D1/D2 二分可塑性）

**创建新页**：
- `wiki/concepts/corticostriatal-plasticity.md`（rev1）：皮质纹状体突触可塑性（D1/D2 二分机制）——正向 DA 下 D1-MSN 通过 PKA→AMPAR 获得 LTP，D2-MSN 通过 eCB 逆行信号获得 LTD；Shen 2008 二分法；STDP 时序规则；三因子学习规则的基底神经节实现；与习惯形成的行为联系；status=mainstream, confidence=high
- `wiki/concepts/endocannabinoid-ltd.md`（rev1）：内源大麻素长时程抑制（纹状体）——MSN 去极化→mGluR5+D2R→DAGLα/β→2-AG→CB1R（逆行）→谷氨酸释放↓；Gerdeman 2002 奠基发现；D2R 必要性遗传学证据（Calabresi 1997）；中等频率诱导（Ronesi 2005）；status=established, confidence=high

**修订页面**：
- `wiki/concepts/habit-formation.md`（rev4→rev5）：新增皮质纹状体可塑性分子机制小节（D1/D2 二分、eCB-LTD、三因子规则与习惯化 S-R 联结的关系）；related 新增 corticostriatal-plasticity, endocannabinoid-ltd, three-factor-learning-rule；key_sources 更新
- `wiki/circuits/basal-ganglia.md`（rev3→rev4）：related 新增 corticostriatal-plasticity, endocannabinoid-ltd；key_sources 新增 PMID:11976704, PMID:18687967, PMID:19038213
- `wiki/concepts/three-factor-learning-rule.md`（rev3→rev4）：新增皮质纹状体可塑性作为三因子规则的核心生物学实例；乙酰胆碱暂停窗时间门控机制（González-Redondo 2025）；related 新增 corticostriatal-plasticity, endocannabinoid-ltd, habit-formation

**图谱变更**：366 节点（+2：corticostriatal-plasticity, endocannabinoid-ltd），2118 条边（+16：新节点与 habit-formation/basal-ganglia/dopamine-reward-prediction-error/three-factor-learning-rule/striatal-chunking/ltp/parkinsons-disease/endocannabinoid-ltd 的新连接）

**新增未解问题**：Q-cortstr-01（清醒行为动物中 eCB-LTD 自然诱导条件）；Q-cortstr-02（D1/D2 二分法的简化程度——D1/D2 MSN 同步激活的证据与二分法矛盾）

**登记矛盾**：无新矛盾

**新增悬空引用**：endocannabinoid-ltd 中的 cb1-receptor 节点尚无独立 wiki 页（已记为待补）

---

## 2026-06-13（文章 #184：行为的括号——纹状体序列组块化与习惯形成）

**创建新页**：
- `wiki/concepts/striatal-chunking.md`（rev1）：纹状体序列组块化（活动书签）——SPN 起/止括号 + FSI 反向中段激活的双轨机制；Martiros 2018 单细胞分辨率证据；强化依赖性；括号早于习惯化出现（神经前兆）；status=emerging, confidence=medium

**修订页面**：
- `wiki/concepts/habit-formation.md`（rev3→rev4）：新增 Martiros 2018 SPN/FSI 括号机制（单细胞级别证据）；Smith & Graybiel 2016 括号-犹豫负相关及习惯神经前兆；related 新增 striatal-chunking；key_sources 更新
- `wiki/circuits/basal-ganglia.md`（rev2→rev3）：新增 DLS 序列组块化机制引用；related 新增 striatal-chunking；key_sources 更新

**图谱变更**：364 节点（+1：striatal-chunking），2102 条边（+6：striatal-chunking↔habit-formation/basal-ganglia/motor-learning/dopamine-reward-prediction-error）

**新增未解问题**：Q-chunk-01（SPNs 括号化的突触分子机制）；Q-chunk-02（括号化可逆性及其临床含义）

**登记矛盾**：无

**新增悬空引用**：无（新节点与已有节点连接完整）

---

## 2026-06-13（文章 #183：周综合第9期——感觉运动反馈整合）

**创建新页**：无（周综合不创建新 wiki 页，但大幅修订现有页）

**修订页面**：
- `wiki/concepts/optimal-feedback-control.md`（rev1→rev2）：在多层闭环框架中明确OFC作为脊髓反射、经皮质反射(M2/M3)和小脑前向模型的统一数学框架；与旋转动力学和肌肉协同的整合关系得到强调
- `wiki/circuits/transcortical-stretch-reflex.md`（rev1→rev2）：阐明M2/M3任务依赖调制是OFC最小干预原则的皮层-脊髓实现；3a区作为感觉融合节点的中枢地位得到明确
- `wiki/systems/spinocerebellar-tracts.md`（rev1→rev2）：强调DSCT 70% CPG驱动在感觉运动整合三原则中的位置（"预测先于感觉"的解剖基础）
- `wiki/concepts/muscle-synergies.md`（rev1→rev2）：阐明协同是"维度压缩"三原则之一，与OFC整合——将600维肌肉控制压缩至4–7维，使最优控制计算上可行

**图谱变更**：363 节点；+3 条新边（somatosensory-cortex-3a→optimal-feedback-control, spinocerebellar-tracts→optimal-feedback-control, stretch-reflex→optimal-feedback-control，均为supports类型）

**新增未解问题**：Q-syn-01（协同数目的决定因素：脊髓拓扑 vs 任务代数自由度）；Q-m1-01（M1群体旋转频率是否随感觉噪声系统性变化，作为OFC Kalman增益调整的证据）

**登记矛盾**：无新矛盾（C-2026-06-13-01和C-2026-06-13-02已登记，本次综合阐明了两者的意义）

**新增悬空引用**：无

---

## 2026-06-13（文章 #182：运动的降维之道——肌肉协同）

**创建新页**：
- `wiki/concepts/muscle-synergies.md`（rev1）：肌肉协同（Muscle Synergies）——伯恩斯坦自由度问题的降维解；NMF提取方法；脊髓中枢起源证据（去传入实验、脊髓横断、PreM-IN聚类）；生物力学约束替代假说（Kutch 2012）；皮层通过CSC调制协同激活系数（Ortega-Auriol 2023）；与OFC框架的整合；中风后协同合并作为生物标志物；status=mainstream, confidence=medium

**修订页面**：无（本次主要创建新页）

**图谱变更**：363 节点（+1: muscle-synergies）；2093 边（+8 条新边：muscle-synergies↔spinal-interneurons-locomotion, ↔spinal-cord-cpg, ↔alpha-motor-neuron, CST→muscle-synergies, M1→muscle-synergies, ↔optimal-feedback-control, ↔rotational-dynamics-motor）

**登记矛盾**：muscle-synergies 整体（神经起源 vs 生物力学约束）记入 contested_claims

**新增悬空引用**：无

---

## 2026-06-13（文章 #181：最优反馈控制 OFC）

**创建新页**：
- `wiki/concepts/optimal-feedback-control.md`（rev1）：最优反馈控制（OFC）理论，涵盖代价函数、三大核心预测（结构化变异、任务依赖增益、多效应器协作）、卡尔曼滤波神经实现框架，10 个来源（6 个开放全文）

**修订页面**：
- `wiki/systems/motor-cortex.md`（rev6→rev7）：新增"OFC 框架对 M1 的重新解读"小节（M1 混合编码作为控制器特征、LLR 目标依赖性、旋转动力学 OFC 解释）；related 新增 optimal-feedback-control
- `wiki/concepts/rotational-dynamics-motor.md`（rev2→rev3）：新增"OFC 视角的挑战"小节（Kalidindi 2021：无循环连接有感觉反馈的网络产生旋转，S1/顶叶也有旋转）；登记矛盾 C-2026-06-13-01
- `wiki/concepts/forward-model.md`（rev3→rev4）：补充前向模型在 OFC 卡尔曼滤波框架中的具体角色（预测步）；related 新增 optimal-feedback-control

**登记矛盾**：
- `C-2026-06-13-01`（open）：M1 旋转动力学来源——内在循环连接（Sussillo 2015）vs 感觉反馈回路涌现（Kalidindi 2021）；需要选择性感觉反馈阻断因果实验裁决

**图谱变更**：362 节点（更新 OFC 节点 domain/confidence/page）；2085 边（+7 条新边：OFC→M1, OFC→forward-model, OFC→cerebellum, OFC→predictive-coding, OFC→output-null-space, OFC→rotational-dynamics-motor, M1→OFC）

**新增悬空引用**：无（所有 related 均已有节点）

---

## 2026-06-13（文章 #180：反射的第二次进化——长潜伏期牵张反射 M2/M3）

### 新建 wiki 页面（1 页）

- `circuits/transcortical-stretch-reflex.md`（经皮质牵张反射/长潜伏期牵张反射）：Rev1 创建；M2（~50–75ms）和M3（~75–120ms）经由 Ia传入→脊髓→丘脑→3a区→M1→CST→α-MN 的经皮质回路；三个核心能力：任务目标调制（Pruszynski 2014，PMC6608123）、多关节整合（Pruszynski 2011 Nature，PMC4974074）、运动学习适应；OFC框架统一解释（Scott 2008，PMC2375659）；Marsden 1976（PMC1309044）历史奠基；Petersen 1998（PMC2231172）TMS直接证明；中风后M2/M3双侧受损（Trumbower 2013，PMC3674210）；状态 established / confidence: high。

### 修订 wiki 页面（2 页）

- `circuits/stretch-reflex.md` rev1→rev2：related新增 transcortical-stretch-reflex；M2/M3描述扩充（时序、任务依赖、学习可塑性）；连接节新增 transcortical-stretch-reflex 链接；修订历史追加。
- `systems/somatosensory-cortex-3a.md` rev1→rev2：related新增 transcortical-stretch-reflex；source_articles新增 #180；修订历史追加（3a区作为M2/M3经皮质弧的必要节点）。

### 图谱变化

- 新建节点 2 个：transcortical-stretch-reflex、optimal-feedback-control
- 新增边 8 条：transcortical-stretch-reflex → stretch-reflex（is-a）；somatosensory-cortex-3a → transcortical-stretch-reflex（mechanism-of）；motor-cortex → transcortical-stretch-reflex（mechanism-of）；corticospinal-tract → transcortical-stretch-reflex（mechanism-of）；muscle-spindle → transcortical-stretch-reflex（supports）；transcortical-stretch-reflex → optimal-feedback-control（supports）；transcortical-stretch-reflex → motor-learning（related）；thalamus → transcortical-stretch-reflex（mechanism-of）
- 图谱状态：362 节点，2078 边

### 登记/裁决矛盾

- 无新矛盾登记。M2成分的通路（经皮质CST vs 网状脊髓束RST）存在未解分歧，但属于"量化贡献之争"而非"存在性之争"——已在新建页的未解问题（Q-llr-01）中标注，尚未触发矛盾协议。

### 悬空引用新增

- `optimal-feedback-control`：在 transcortical-stretch-reflex 中引用，待补独立页面（目前已添加为图谱节点但无wiki页面）。


---

## 2026-06-13（文章 #177：3a区——皮层本体感觉的第一站与运动控制的感觉门）

### 新建 wiki 页面（1 页）

- `systems/somatosensory-cortex-3a.md`（S1区3a/Brodmann area 3a）：Rev1 创建；填补 spinocerebellar-tracts（#176）中登记的悬空引用；位于中央沟底部；接收肌梭Ia传入（经VPLc丘脑）和小脑-VLc双重丘脑输入（Huffman & Krubitzer 2001，PMID:11406813）；直接投射M1；腱振动100Hz激活Ia并产生运动错觉（Goodwin 1972，PMID:4258209）；人类fMRI证据（Fasold 2008，PMID:18296073）；去传入后M1预运动活动降低约70%（Voigt 2026，PMC13089743，开放全文）；区分了痛觉处理争议（Whitsel 2019）；状态 established / confidence: high。

### 修订 wiki 页面（3 页）

- `systems/somatosensory-cortex.md` rev1→rev2：related 新增 somatosensory-cortex-3a、motor-cortex、proprioception；连接节新增3a区子页链接；修订历史追加。
- `concepts/proprioception.md` rev2→rev3：DCML通路描述补充3a区双重丘脑输入（VPLc + VLc）和直接M1投射；related新增 somatosensory-cortex-3a；连接节新增[[somatosensory-cortex-3a]]；修订历史追加。
- `neurons/muscle-spindle.md` rev2→rev3：填补 somatosensory-cortex-3a 悬空引用；related新增 somatosensory-cortex-3a；连接节新增[[somatosensory-cortex-3a]]；修订历史追加。

### 图谱变化

- 新建节点 1 个：somatosensory-cortex-3a
- 新增边 9 条：somatosensory-cortex-3a → somatosensory-cortex（part-of）；somatosensory-cortex-3a → motor-cortex（regulates）；somatosensory-cortex-3a → proprioception（mechanism-of）；somatosensory-cortex-3a → forward-model（supports）；muscle-spindle → somatosensory-cortex-3a（related）；thalamus → somatosensory-cortex-3a（related）；cerebellum → somatosensory-cortex-3a（regulates）；spinocerebellar-tracts → somatosensory-cortex-3a（related）；proprioception → somatosensory-cortex-3a（related）
- 图谱状态：355 节点，2046 边

### 登记/裁决矛盾

- 无新矛盾登记。3a区的"痛觉响应"（PMID:30227224）与"本体感觉专属"的经典认知存在张力，但尚无足够的冲突证据触发矛盾协议——在新建页中已如实标注为"争议中/证据强度中"。

### 悬空引用修复

- `somatosensory-cortex-3a` ✓（来自 spinocerebellar-tracts 文章，#176 CHANGELOG 中已登记，本次填补）

### 新增悬空引用待补

- `spinocerebellar-ataxia`：沿用 #176 登记，待创建疾病页

---

## 2026-06-13（文章 #176：双轨信使——脊髓小脑束 DSCT/VSCT 与前向模型输入）

### 新建 wiki 页面（2 页）

- `systems/spinocerebellar-tracts.md`（脊髓小脑束）：Rev1 创建；四条并行通路（DSCT/VSCT/CCT/RSCT）解剖框架；关键范式转变：DSCT 70% 受 CPG 驱动（Stecina 2013，PMC3853486，直接电生理）；VSCT 全部受 CPG 驱动；颗粒层稀疏编码（Geborek 2013/2014）；LRN 系统级整合（Alstermark & Ekerot 2013）；疾病窗口（Friedreich 共济失调 fMRI）；状态 established / confidence: high。
- `neurons/clarkes-nucleus.md`（Clarke 柱）：Rev1 创建；T1-L2 背内侧灰质中继核；直接 Ia/Ib 单突触投射（VGluT1 高密度）；DSCT 主要起源；细胞体直径 60-80 μm；CPG 驱动证据（Stecina 2013）；状态 established / confidence: high。

### 修订 wiki 页面（3 页）

- `systems/cerebellum.md` rev4→rev5：related 新增 spinocerebellar-tracts；key_sources 新增 PMID:23613538/11274339；opens_questions 新增 Q-sct-01；source_articles 新增 #176；连接节新增 [[spinocerebellar-tracts]]；修订历史追加。
- `concepts/forward-model.md` rev2→rev3：关键证据表新增 DSCT CPG 驱动行（PMID:23613538）；related 新增 spinocerebellar-tracts；连接节新增 [[spinocerebellar-tracts]]；key_sources/source_articles 更新；修订历史追加。
- `wiki/index.md`：最后更新行更新至 #176；新增 spinocerebellar-tracts（systems）和 clarkes-nucleus（neurons）条目；cerebellum rev5/forward-model rev3/alpha-motor-neuron 描述更新；图谱状态更新至 354 节点 2038 边。

### 图谱变化

- 新建节点 2 个：spinocerebellar-tracts、clarkes-nucleus
- 新增边 18 条：muscle-spindle/GTO → spinocerebellar-tracts（mechanism-of）；spinal-cord-cpg → spinocerebellar-tracts（regulates）；clarkes-nucleus → spinocerebellar-tracts（part-of）；spinocerebellar-tracts → cerebellum（mechanism-of）；spinocerebellar-tracts → forward-model（supports）；proprioception ↔ spinocerebellar-tracts；muscle-spindle/GTO → clarkes-nucleus（mechanism-of）；clarkes-nucleus → cerebellum（mechanism-of）；alpha-motor-neuron → spinocerebellar-tracts（related）；motor-system-hierarchy → spinocerebellar-tracts（part-of）；spinocerebellar-tracts → deep-cerebellar-nuclei（mechanism-of）；forward-model → spinocerebellar-tracts（prerequisite-for）；corticospinal-tract → spinocerebellar-tracts（related）；spinocerebellar-tracts → motor-system-hierarchy（part-of）
- 图谱状态：354 节点，2038 边

### 登记/裁决矛盾

- 无新矛盾登记。DSCT "既传感觉又传 CPG 信号"与"DSCT = 纯感觉"的经典预期存在范式转变，但这是同一实验室（Stecina/Hultborn）基于明确实验的修正——不构成科学矛盾，而是对机制的深化。已在 spinocerebellar-tracts.md 正文中如实呈现"经典观点"和"新发现"。

### 新增悬空引用待补

- `somatosensory-cortex-3a`：被 spinocerebellar-tracts.md 正文提及（本体感觉在 3a 区的皮层终点），尚无独立页面——是下一个重要缺口
- `spinocerebellar-ataxia`：被 cerebellum.md related 引用（wiki/diseases/spinocerebellar-ataxia.md），待创建疾病页

---

## 2026-06-13（文章 #175：运动系统周综合——七个节点如何构成完整运动回路）

### 新建 wiki 页面（1 页）

- `concepts/motor-system-hierarchy.md`（运动控制层级）：Rev1 创建；整合 #166-#174 七篇运动系统文章；五层下行通路（皮层→CPG→α-MN→NMJ→肌肉）；两路感觉反馈（肌梭长度+GTO力量）；四个设计原则（分层分工/预测+反应/动态重配置/进化馈赠）；运动疾病节点失效分析表；时间尺度层级（20–25 ms Ia反射→50–150 ms小脑→100–300 ms皮层）；状态 established / confidence: high。

### 修订 wiki 页面（1 页）

- `systems/corticospinal-tract.md` rev1→rev2：source_articles 新增 2026-06-13-week-synthesis-motor-system-circuit；related 新增 motor-system-hierarchy。

### 图谱变化

- 新建节点 1 个：motor-system-hierarchy
- 新增边 16 条：motor-system-hierarchy↔corticospinal-tract/spinal-cord-cpg/alpha-motor-neuron/neuromuscular-junction/muscle-spindle/golgi-tendon-organ（part-of 双向）；motor-system-hierarchy→motor-cortex（part-of）；motor-system-hierarchy→size-principle/distributed-motor-control（supports）
- 图谱状态：352 节点，2020 边

### 登记/裁决矛盾

- 无新矛盾登记（综合文章，整合已有知识）。

### 新增悬空引用待补

- `motor-cortex-rotation-dynamics`：被 motor-system-hierarchy 正文引用（旋转动力学框架），待创建或并入 motor-cortex.md

---

## 2026-06-13（文章 #174：肌肉力量的精确传感器——高尔基腱器官如何把张力翻译成脊髓语言，并在步态中切换角色）

### 新建 wiki 页面（2 页）

- `neurons/golgi-tendon-organ.md`（高尔基腱器官）：Rev1 创建；串联排列（vs 肌梭并联）；Ib 传入低阈值特性（每次收缩均放电，推翻"安全阀"范式）；三条脊髓通路（Ib 抑制性/兴奋性/DSCT 上行）；步行站立相 Ib 抑制→兴奋切换；力量感知（与传出副本的贡献分工）；"折刀反射"修正（主要为 III/IV 类传入）；临床应用（帕金森、脊髓损伤、痉挛）；状态 established / confidence: high。
- `concepts/autogenic-inhibition.md`（自身抑制）：Rev1 创建；Ib 传入→甘氨酸能抑制性中间神经元→同肌 α-MN 抑制；与牵张反射的功能对比；步态相位切换机制；H 反射测量范式；临床证据（帕金森/脊髓损伤）；状态 established / confidence: high。

### 修订 wiki 页面（2 页）

- `concepts/proprioception.md` rev1→rev2：大幅扩展 GTO 子系统描述；更正低阈值特性；步态 Ib 切换机制；力量感知贡献；"折刀反射"修正；新增 3 条关键证据行；key_sources 补充 3 项。
- `neurons/muscle-spindle.md` rev1→rev2：填补 golgi-tendon-organ 悬空引用（该节点现已有 wiki 页面）；更新 source_articles。

### 图谱变化

- 新建节点 1 个：autogenic-inhibition（golgi-tendon-organ 已存在于图谱中）
- 新增边 13 条：golgi-tendon-organ↔muscle-spindle（related）、golgi-tendon-organ→proprioception（part-of）、golgi-tendon-organ→autogenic-inhibition（mechanism-of）、autogenic-inhibition→alpha-motor-neuron（regulates）、golgi-tendon-organ→spinal-cord-cpg（regulates）、golgi-tendon-organ→cerebellum（supports）等
- 图谱状态：351 节点，2004 边

### 登记/裁决矛盾

- 无新矛盾登记。
- 新增未解问题：Q-gto-01（人类 GTO 跨运动单元采样策略）、Q-gto-02（GTO 老化动力学）、Q-gto-03（站立相 Ib 切换的具体脊髓中间神经元身份）。

### 填补悬空引用

- `golgi-tendon-organ`：在 muscle-spindle、proprioception 中已被引用，现已有 wiki 页面。✓

---

## 2026-06-13（文章 #173：进化写下的专线——皮质脊髓束如何让人类获得世界上最灵巧的双手）

### 新建 wiki 页面（2 页）

- `systems/corticospinal-tract.md`（皮质脊髓束）：Rev1 创建；多元皮层起源（M1/PMC/SMA/S1）；延髓锥体交叉（~85%）；终止分布（59%中间灰质/18%直达运动核）；PlexA1/CIS分子调控 CM 连接保留；物种进化楼梯（啮齿类→灵长类）；ALS split-hand 机制；CST 发育（青春期完成）；与其他下行通路比较（红核/网状/本体脊髓）；填补 motor-cortex 页面悬空引用；状态 established / confidence: high。
- `concepts/corticomotoneuronal-connections.md`（皮质-运动神经元直接连接）：Rev1 创建；直接单突触皮层→α-MN；猕猴 75% 上肢 MN 接受单突触投射；Lawrence&Kuypers 1968 经典实验；C5 vs 延髓锥体切断比较；CM 系统脆弱性与 ALS；状态 established / confidence: high。

### 修订 wiki 页面（2 页）

- `systems/motor-cortex.md` rev4→rev5：更新 corticospinal-tract 引用（"待建页面"→正式页）；补充 CST 终止数据（59%中间灰质/18%直达运动核）；key_sources 新增 PMID:30906528, PMID:24312077。
- `neurons/alpha-motor-neuron.md` rev3→rev4：related 新增 corticospinal-tract 和 corticomotoneuronal-connections；修订历史追加；source_articles 加入 #173。

### 图谱变化

- 新建节点 2 个：corticospinal-tract、corticomotoneuronal-connections
- 新增边 13 条：包括 motor-cortex→corticospinal-tract（mechanism-of）、corticospinal-tract→alpha-motor-neuron（regulates）、corticospinal-tract→corticomotoneuronal-connections（part-of）、corticomotoneuronal-connections→alpha-motor-neuron（mechanism-of）、cerebellum/basal-ganglia→corticospinal-tract（regulates）等
- 图谱状态：350 节点，1991 边

### 登记/裁决矛盾

- 无新矛盾登记（CST 轴突数量传统估计与精确有髓纤维计数差异已在文章中明确注释为方法差异，非科学矛盾）。
- 新增未解问题：Q-cst-01（人类CM分布图），Q-cst-02（ALS由上至下vs由下至上），Q-cst-03（CST损伤可塑性时间窗），Q-cst-04（红核脊髓束人类状态）。

### 填补悬空引用

- `corticospinal-tract`（来自 motor-cortex.md related 列表）✓ 已填补

### 新增悬空引用待补

- 无新增悬空引用

---

## 2026-10-10（文章 #172：感觉会自我校准的尺子——肌梭、γ 运动神经元与本体感觉的分子回路）

### 新建 wiki 页面（4 页）

- `neurons/muscle-spindle.md`（肌梭）：Rev1 创建；核袋1/2/链纤维三类型；PIEZO2 机械换能；Ia/II 型传入；α-γ 协同激活；牵张反射单突触回路；上行 DCML + 脊髓小脑束通路；状态 established / confidence: high。
- `neurons/gamma-motor-neuron.md`（γ 运动神经元）：Rev1 创建；γd→bag1/γs→bag2+chain；α-γ 协同激活机制；Err3/Gfrα1/Wnt7a/5Ht1d 分子标记；人类 vs 猫的独立控制差异；状态 established / confidence: high。
- `concepts/piezo2-mechanotransduction.md`（PIEZO2 机械换能）：Rev1 创建；PIEZO2 KO 消除肌梭感觉；人类 LOF 突变→本体感觉缺陷；快/慢适应悖论；谷氨酸囊泡假说；状态 established / confidence: high。
- `concepts/proprioception.md`（本体感觉）：Rev1 创建；多源融合（肌梭+GTO+皮肤+传出副本）；关节感受器次要；DCML+小脑双通路；thixotropy 效应；状态 established / confidence: high。

### 修订 wiki 页面（1 页）

- `neurons/alpha-motor-neuron.md` rev2→rev3：新增 related: [gamma-motor-neuron, muscle-spindle]；连接节新增 γ-α 协同激活和牵张反射关系描述；修订历史追加；source_articles 加入 #172。

### 图谱变化

- 新建节点 5 个：muscle-spindle、gamma-motor-neuron、piezo2-mechanotransduction、proprioception、golgi-tendon-organ
- 新增边 13 条：包括 muscle-spindle→gamma-motor-neuron（regulates）、gamma-motor-neuron→muscle-spindle（regulates）、piezo2-mechanotransduction→muscle-spindle（mechanism-of）、muscle-spindle→alpha-motor-neuron（regulates）、proprioception→cerebellum/somatosensory-cortex（related）等
- 图谱状态：348 节点，1978 边

### 登记/裁决矛盾

- 无新矛盾登记。新增 Q-spindle-01（PIEZO2 快/慢适应悖论）、Q-spindle-02（人类 γ 独立控制）、Q-spindle-03（肌梭非运动功能机制）。

### 新增悬空引用待补

- `somatosensory-cortex`（在 proprioception 中引用，尚无独立 wiki 页——应在 S1/3a 区讲解时建立）
- `body-schema`（在 proprioception 相关中引用）
- `golgi-tendon-organ`（建了节点但尚无 wiki 页内容，需在后续文章中补建）

---

## 2026-06-12（文章 #171：CNTNAP2——FOXP2 基因网络中从语言基因到大脑布线蓝图的关键分子接触器）

### 新建 wiki 页面（1 页）

- `concepts/cntnap2-language-circuit.md`（CNTNAP2 语言回路布线基因）：Rev1 创建；FOXP2 直接结合 CNTNAP2 第2内含子并转录激活（Vernes 2008 ChIP-chip）；Caspr2 双重功能（旁节 Kv1 K+通道聚簇 + 皮层 PV+中间神经元迁移调控）；人类额叶皮层左侧化表达（Alarcón 2008，黑猩猩中不明显）；SLI/ASD/ADHD 遗传关联；剂量-表型（双等位基因→CDFE）；Q-SLF-03 候选分子机制（emerging，未经直接因果验证）；状态 established / confidence: high。

### 修订 wiki 页面（2 页）

- `concepts/foxp2-language-gene.md` rev1→rev2：新增 related: cntnap2-language-circuit 和 superior-longitudinal-fasciculus；关键机制链更新（加入 CNTNAP2 和 264 轴突导向靶基因，Vernes 2011）；opens_questions 加入 Q-SLF-03；新增 key_sources（PMID:18987363, PMID:21765815）；修订历史追加。
- `systems/superior-longitudinal-fasciculus.md` rev1→rev2：新增"SLF III 左侧化的分子候选机制"小节（FOXP2→CNTNAP2→左侧额叶连接优势；status: emerging；Q-SLF-03 状态更新为"有候选机制待验证"）；related 加入 foxp2-language-gene 和 cntnap2-language-circuit；修订历史追加。

### 图谱变化

- 新建节点 1 个：cntnap2-language-circuit（concepts/mechanism/established）
- 新增边 5 条：foxp2-language-gene→cntnap2-language-circuit（regulates）、cntnap2-language-circuit→superior-longitudinal-fasciculus（supports）、cntnap2-language-circuit→pv-interneurons（regulates）、cntnap2-language-circuit→language-lateralization（supports）、foxp2-language-gene→superior-longitudinal-fasciculus（supports）
- 图谱状态：343 节点，1965 边

### 登记/裁决矛盾

- 无新矛盾登记。Q-SLF-03 从"完全未知"升级为"有候选机制（FOXP2→CNTNAP2→左侧额叶），但无直接因果验证"，维持 status=open。

### 新增悬空引用待补

- `voltage-gated-potassium-channels`（在 cntnap2-language-circuit 的 prerequisites 中被引用，尚无独立 wiki 页）

---

## 2026-06-13（文章 #170：白质的三条平行弦——上纵束（SLF）亚束系统）

### 新建 wiki 页面（1 页）

- `systems/superior-longitudinal-fasciculus.md`（上纵束 SLF 系统）：Rev1 创建；SLF I/II/III + AF 四部分框架；SLF I（额上回/SMA ↔ 顶上小叶，运动程序化）；SLF II（dlPFC ↔ 角回，空间注意，右侧化，h²≈0.68）；SLF III（BA44/PMv ↔ 缘上回，语音-运动映射，左侧化，DCS→anarthria）；AF（pSTG ↔ BA44，音韵传输，DCS→音韵错语）；DCS 功能双解离证据（Lu 2021，多中心三语言一致）；发育遗传数据（Budisavljevic 2015）；发育可塑性案例（Yeatman 2013）；命名争议综述；状态 established / confidence: high；新增未解 Q-SLF-01/02/03/04。

### 修订 wiki 页面（1 页）

- `concepts/arcuate-fasciculus.md` rev2→rev3：新增 related: superior-longitudinal-fasciculus；加入 Lu 2021（PMID:33792674）为 key_source（AF DCS→音韵错语 vs SLF III→anarthria 的直接功能双解离证据）；新增来源文章；修订历史追加。

### 图谱变化

- 新建节点 1 个：superior-longitudinal-fasciculus
- 新增边 7 条（SLF ↔ AF、SLF → language-network、SLF → dorsal-language-stream、SLF → broca-area、SLF → speech-production-circuit、SLF → conduction-aphasia）
- 节点总数：341 → 342；边总数：1953 → 1960
- **填补悬空引用**：`superior-longitudinal-fasciculus`（被多个页面引用）已建立正式节点
- 剩余悬空引用：`aging`、`cognition`（通用概念，后续处理）

### 矛盾状态

- 无新矛盾登记
- 已有矛盾 C-2026-08-21-01（AF 颞叶端争议）：状态仍为 open，今日文章未提供决定性新证据

---

## 2026-10-09（文章 #169：命令的最后一公里——神经肌肉接头如何把大脑意志翻译成肌肉收缩）

### 新建 wiki 页面（3 页）

- `neurons/neuromuscular-junction.md`（神经肌肉接头）：Rev1 创建；三细胞架构（运动神经末梢+肌纤维终板+PSC）；超微结构（主动区、接头折、nAChR ~10,000/μm²、间隙 50–100 nm）；Cav2.1 触发→SNARE→量子释放（m≈50–100）；Agrin-LRP4-MuSK-rapsyn 轴；安全因子 2–5；填补 alpha-motor-neuron 悬空引用；状态 established / confidence: high；新增未解 Q-nmj-01/02/03。

- `concepts/agrin-musk-achr-clustering.md`（Agrin-LRP4-MuSK-Rapsyn 轴与 AChR 聚集）：Rev1 创建；五元件信号级联；Agrin 增强 LRP4-MuSK 亲和力 36 倍（SPR）；Agrin 作为"抗去聚集因子"（非诱导者）的争议模型；CMS 和 MuSK+ MG 疾病关联；状态 established / confidence: high。

- `concepts/end-plate-potential-safety-factor.md`（终板电位与安全因子）：Rev1 创建；EPP = m×q；安全因子定义和量化（2–5；人类 ~2x 阈值）；MEPP ~1 mV；一量子激活 ~2,000 nAChR；影响安全因子的因素表；MG/LEMS/BoNT 的安全因子下降机制；状态 established / confidence: high。

### 修订 wiki 页面（1 页）

- `neurons/alpha-motor-neuron.md` rev1→rev2：修订历史追加（悬空引用 neuromuscular-junction 已填补，NMJ 专页建立）；source_articles 新增今日文章；updated 更新为 2026-10-09。

### 图谱变化

- 新建节点 3 个：neuromuscular-junction、agrin-musk-achr-clustering、end-plate-potential-safety-factor
- 新增边 14 条
- 节点总数：338 → 341；边总数：1939 → 1953
- 填补悬空引用：`neuromuscular-junction`（由 alpha-motor-neuron related 字段引用）已建立正式节点
- 新增悬空引用待补：myasthenia-gravis、lambert-eaton-syndrome、nicotinic-achr

---

## 2026-10-08（文章 #168：最终公共通路——α运动神经元如何用大小原则和持续内向电流把大脑命令变成肌肉力量）

### 新建 wiki 页面（4 页）

- `neurons/alpha-motor-neuron.md`（α运动神经元）：Rev1 创建；大小原则（Henneman 1965，物理自动招募，PMID:14328454）；PICs（CaV1.3 + Nav1.6，树突远端，2–6倍放大，PMID:18381974/31799904）；三类运动单元（S/FR/FF 及代谢特征）；单胺能调制（5-HT₂/α₁AR）；ALS FF 脆弱性；SCI 痉挛机制；状态 established / confidence: high；新增未解 Q-mn-01/02/03。

- `concepts/motor-unit.md`（运动单元）：Rev1 创建；最小可控神经肌肉单元（α-MN + 支配肌纤维）；神经支配比（眼外肌5-15 → 腓肠肌1000-2000）；S/FR/FF三类型；招募编码 vs 频率编码；去同步化与平滑收缩的关系；状态 established / confidence: high。

- `concepts/size-principle.md`（Henneman 大小原则）：Rev1 创建；物理机制（高R_in小型MN先去极化先放电）；S→FR→FF有序招募；节能优先设计原则；Hug 2023 修订（共同输入簇内严格，跨簇不保证，PMID:36353890, PMC10098498）；任务特异性招募例外争议；状态 established / confidence: high。

- `concepts/persistent-inward-currents.md`（持续内向电流）：Rev1 创建；CaV1.3（主要，比CaV1.2低10-20 mV激活）+ Nav1.6 双通道；树突远端位置；2–6倍放大（中等/高单胺能驱动）；无单胺能时<30-40%最大输出；5-HT₂R + α₁AR调制；高原电位/双稳态（10-20 mV激活-去激活滞后）；SCI弛缓性麻痹→痉挛机制；delta-F间接测量局限；状态 established / confidence: high；新增未解 Q-pic-01/02/03。

### 修订 wiki 页面（1 页）

- `circuits/spinal-cord-cpg.md` rev1→rev2：prerequisites 中 motor-neuron 悬空引用替换为 alpha-motor-neuron 正式节点；related 新增 alpha-motor-neuron / motor-unit / persistent-inward-currents；连接节新增三条（CPG→α-MN、motor-unit、PICs）；key_sources 和 source_articles 补充今日文章；修订历史追加。

### 图谱变化

- 新建节点 4 个：alpha-motor-neuron（neurons, structure, established/high）、motor-unit（concepts, concept, established/high）、size-principle（concepts, mechanism, established/high）、persistent-inward-currents（concepts, mechanism, established/high）
- 新增边 18 条：spinal-cord-cpg→alpha-motor-neuron (regulates)；motor-cortex→alpha-motor-neuron (regulates)；alpha-motor-neuron↔motor-unit (part-of)；alpha-motor-neuron↔size-principle (mechanism-of)；alpha-motor-neuron↔persistent-inward-currents (mechanism-of)；neuromodulator-systems→persistent-inward-currents (regulates)；size-principle→motor-unit (mechanism-of)；alpha-motor-neuron→action-potential (mechanism-of)；alpha-motor-neuron↔parkinsons-disease (related)；persistent-inward-currents↔size-principle (supports/related)；persistent-inward-currents→t-type-calcium-channels (related)
- 节点总数：334 → 338（+4）
- 边总数：1921 → 1939（+18）
- 已填补悬空引用：`motor-neuron` 悬空引用（spinal-cord-cpg prerequisites 中）已替换为正式 alpha-motor-neuron 节点

### 登记矛盾（0 条）

- 无新增矛盾。Hug 2023 对大小原则的修订（共同输入簇内有序 vs 跨簇不保证）不构成与既有主张的冲突，而是精化——已在 size-principle 页面明确表述为"精化而非否定"，无需登记矛盾协议。

### 新增悬空引用待补

- `neuromuscular-junction`：被 motor-unit 和 alpha-motor-neuron 引用，待创建（神经肌肉接头；ACh释放；终板电位；重症肌无力病理）
- `mesencephalic-locomotor-region`：被 spinal-cord-cpg 引用，自 #167 起存在，仍待创建

### 新增未解问题（7 条）

- Q-mn-01（高）：任务特异性招募中是否存在大小原则的真正例外（同一共同输入簇内逆序招募）？
- Q-mn-02（中）：CaV1.3 在人类脊髓 α-MN 的精确分布（目前主要来自大鼠/猫数据）
- Q-mn-03（中）：ALS FF 型优先退化的最早可检测时间节点（高分辨率 EMG 纵向研究需求）
- Q-pic-01（高）：5-HT₂ 受体亚型（2a/2b/2c）在人类脊髓 α-MN 的功能区分
- Q-pic-02（中）：delta-F 技术精度限制，能否发展更直接的人类 PIC 测量方法？
- Q-pic-03（中）：PICs 在正常生理运动中是否常规产生双稳态，还是主要作为增益调节器？
- Q-sp-01（中）：任务特异性招募例外的神经机制（同 Q-mn-01，但专注于机制层面）
- Q-sp-02（低）：大小原则在无脊椎动物运动系统中的跨物种普遍性
- Q-mu-01（低）：人类活体中三类运动单元的精确数量比例

---

## 2026-10-07（文章 #167：步态的脊髓时钟——中枢模式发生器如何在没有大脑指令的情况下编排节律运动）

### 新创建页面（3 页）
- `circuits/spinal-cord-cpg.md`（脊髓中枢模式发生器）：CPG 双层架构（RG节律生成层+PF模式形成层）；V0D/V0V 速度依赖步态切换（走/小跑/飞奔）；V1+V2b 屈伸半中枢；SHOX2+ 神经元节律生成候选；虚构运动历史证据；MLR→网状脊髓束下行控制；VSCT 枢纽争议（Chalif 2022）；状态 established（CPG 存在性和基本组织），中（RG 层细胞身份，VSCT 证据待重复）；来源 PMID:26935168、PMID:23812590 等；新增未解问题 Q-cpg-rg-identity/Q-cpg-vsct/Q-cpg-human/Q-cpg-forelimb。
- `circuits/spinal-interneurons-locomotion.md`（步态中间神经元 V 型）：V0/V1/V2a/V2b/V3 各亚型的分子标记（Dbx1/En1/Chx10/Gata3/Sim1）、投射方向（同侧/对侧）、递质类型（兴奋/抑制）与功能角色的详细矩阵；SHOX2+ 非 V2a 节律生成；VSCT 必要充分性；关键遗传学实验证据表；状态 established（V型神经元功能），中（SHOX2/VSCT）。
- `systems/dopamine-system.md`（多巴胺系统总览）：**填补悬空引用 `dopamine-system`**；VTA+SNc 两大核团及三条通路（中脑边缘/中脑皮层/黑质纹状体）；相位性爆发（RPE）vs 紧张性放电；LHb→RMTg→DA 负预测误差回路；指向各专题页（VTA/SNc/DA-RPE/D1D2/基底节）；小页（综合提示索引页）。

### 修订页面（2 页）
- `systems/motor-cortex.md`（revision 3→4）：新增"运动皮层与 CPG 的分工"小节，明确皮层在基础步行（低介入）vs 复杂地形（高介入）vs 精细手指（最高介入/单突触CST）三类运动中的差异化角色；related 新增 spinal-cord-cpg、spinal-interneurons-locomotion；修订历史更新。

### 矛盾检查
- 无新矛盾：脊髓 CPG（本篇）与 motor-cortex 页（皮层直接控制运动）不冲突——两者描述不同类型运动（基础节律 vs 精细/复杂），且现有 motor-cortex 页强调的是"皮层对运动的直接控制"，本篇补充的是"基础步行的分层委托架构"，两者互补。
- VSCT 枢纽发现（Chalif 2022）与既有"分布式 CPG"框架存在**潜在矛盾**——但 VSCT 证据尚需独立验证，暂不登记为 contested；在文章和 wiki 中明确标注为"需独立验证"的争议性发现。

### 悬空引用状态
- **填补**：`dopamine-system` 悬空引用已通过新建 `systems/dopamine-system.md` 解决 ✅
- 剩余悬空引用（减少至 3 个）：aging, cognition, superior-longitudinal-fasciculus

### 图谱变化
- 新增节点 3：spinal-cord-cpg, spinal-interneurons-locomotion, dopamine-system
- 新增边 12 条（CPG与motor-cortex/cerebellum/basal-ganglia的关联；dopamine-system与VTA/SNc/DA-RPE的关联等）
- 图谱总计：334 节点，1921 边

---

## 2026-10-06（文章 #166：当大脑与脊髓合为一张接线图——BANC 连接组揭示分布式运动控制架构）

### 新创建页面（2 页）
- `concepts/distributed-motor-control.md`（分布式运动控制）：BANC 2026 揭示的果蝇运动控制组织原则（局部感觉-运动回路优先、DNs/ANs 双向输出、15行为超群集、中央复合体监督角色）；状态 emerging（结构证据强，功能验证和跨物种推广待完成）；来源 PMID:40766407、PMID:39358518；新增未解问题 Q-dmc-01/02/03。
- `systems/ventral-nerve-cord.md`（腹侧神经索）：果蝇类脊髓结构，~20,000 个神经元（BANC 2026），按体段组织（T1-T3 控腿翅，A1-A10 控内脏生殖）；运动神经元最强输入来自同体段局部感觉神经元；DNs/ANs 在 VNC 内有实质突触输出；去头果蝇仍可协调行走（局部自主性的行为证明）；状态 established。

### 修订页面（1 页）
- `methods/connectomics.md`（revision 2→3）：新增 BANC 2026（PMID:40766407，PMC12324551，开放全文）在规模阶梯表中（脑+VNC，~160,000神经元，~10^8突触）；新增"BANC：脑与脊髓合为一张图"专节（分布式控制发现的完整描述）；证据表新增2条 BANC 主张；related 新增 distributed-motor-control、ventral-nerve-cord；key_sources 新增 PMID:40766407 和 PMID:41030982；新增未解问题 Q-conn-04（VNC propriospinal 类比）和 Q-conn-05（Connectome-seq 灵敏度提升）。

### 矛盾检查
- 无新矛盾：BANC 的"分布式控制"发现与既有 motor-cortex 页（灵长类皮层对运动的直接控制）的描述不冲突，前者针对果蝇，后者针对灵长类，层级差异已在文章中明确说明。
- 现有 contested_claims 中无相关条目被影响。

### 悬空引用状态
- 本次未引入新悬空引用（所有新边的 from/to 均已有对应节点）
- 剩余悬空引用（4个）：aging, cognition, dopamine-system, superior-longitudinal-fasciculus（与前次相同）

### 图谱变化
- 新增节点 2：distributed-motor-control, ventral-nerve-cord
- 新增边 8：distributed-motor-control↔connectomics, distributed-motor-control→ventral-nerve-cord, distributed-motor-control→motor-cortex, ventral-nerve-cord→connectomics, ventral-nerve-cord→distributed-motor-control, ventral-nerve-cord→cerebellum, connectomics→distributed-motor-control, connectomics→ventral-nerve-cord
- 总计：331 节点，1909 边

---

## 2026-10-05（文章 #165：感知的最小战场——双眼竞争如何让意识的门槛暴露在显微镜下）

### 新创建页面（2 页）
- `concepts/binocular-rivalry.md`（双眼竞争）：**填补悬空引用**（#164 中悬空）。竞争现象学（Levelt 四定律、Gamma 分布主导期）、层级竞争机制（LGN→V1→IT 感知忠实度梯度）、互相抑制-适应-噪声计算模型（Seely & Chow 2011）、层级双稳变量模型（Cao et al. 2021）、CFS 扩展应用（Yang et al. 2014）、Blake et al. 2014 的四条方法论质疑；12 条来源（PMID:2772635/9096407/11036274/16997612/17632508/24639582/25749677/34369875/36609303/37520732/25071685/21775721）；6 条开放全文。
- `systems/lateral-geniculate-nucleus.md`（外侧膝状核）：LGN 组织（6 层眼特异性分层、M/P 通路）、皮层-膝状体反馈、双眼竞争中的 LGN 活动（Yildirim & Schneider 2023，M/P 均参与）；状态 established，置信度高。

### 修订页面（4 页）
- `systems/v1-primary-visual-cortex.md`（revision 7→8）：新增双眼竞争中 V1 角色的争议（fMRI 55% vs 电生理 20%）；注意门控 V1→高级区的证据（Lee et al. 2007, PMID:17632508）；V1 适应替代触发机制（Carlson et al. 2023, PMID:37520732）；related 新增 binocular-rivalry, lateral-geniculate-nucleus。
- `systems/inferior-temporal-cortex.md`（revision 1→2）：新增双眼竞争的感知忠实度梯度（Sheinberg & Logothetis 1997：几乎所有 IT 神经元追踪感知而非物理刺激）；related 新增 binocular-rivalry, neural-correlates-of-consciousness。
- `concepts/neural-correlates-of-consciousness.md`（revision 2→3）：新增双眼竞争作为 NCC 研究平台；补充 Blake et al. 2014 四条质疑（方法论局限）；related 新增 binocular-rivalry, attention-consciousness-dissociation, inferior-temporal-cortex。

### 填补悬空引用
- `binocular-rivalry`：已创建专页，悬空引用解决 ✅

### 知识图谱更新
- 新节点：binocular-rivalry, lateral-geniculate-nucleus（节点总数：329）
- 新边：18 条（边总数：1901）

---

## 2026-10-04（文章 #164：注意不等于意识——探照灯与舞台灯光的神经科学分离）

### 新创建页面（1 页）
- `concepts/attention-consciousness-dissociation.md`（注意-意识双重解离）：整合了双重解离的两个方向（有注意无意识 / 无注意有意识）、γ 振荡双解离（54-64Hz 意识，76-90Hz 注意）、VAN/P3b 时间解离、fMRI 空间解离、Koch & Tsuchiya 2007 框架、Block 2011 溢出假说、Cohen et al. 2012 反驳；5 条来源（PMID:17129748, 18322110, 25339922, 22795561, 33034851）；状态 mainstream，置信度中。

### 修订页面（2 页）
- `concepts/visual-awareness-negativity.md`（revision_count: 1→2）：补充与注意-意识解离框架的连接；明确 VAN 在无报告条件下存在是它比 P3b 更接近 P-consciousness 的根据；新增 Q-atcon-02。
- `concepts/access-consciousness.md`（revision_count: 1→2）：补充 A vs P 区分与注意-意识解离的关系；注意对 A-consciousness 和 P-consciousness 存在不对称依赖性；新增 PMID:22078929。

### 新增悬空引用（待填）
- `binocular-rivalry`：文章引用但尚无专页（候选主题）
- `inattentional-blindness`：文章引用但尚无专页（候选主题）

### 知识图谱更新
- 新节点：attention-consciousness-dissociation（节点总数：327）
- 新边：10 条（边总数：1883）

---

## 2026-10-03（文章 #163：前连合——进化遗留的大脑渡口，裂脑意识整合的最后防线？）

### 新建 wiki 页面（1 页）

- `systems/anterior-commissure.md`（新建）：**填补悬空引用**（图谱中 anterior-commissure 悬空引用自 2026-09-26 建立）。前连合解剖（前肢=嗅觉段；后肢=颞叶-杏仁核段）、系统发育（比胼胝体更古老；有袋类唯一联合纤维）、AgCC 代偿（Barr 2002：J.P. 扩大 AC 接近正常跨半球视觉匹配）、裂脑手术保留 AC 这一关键技术细节（可能是 Pinto 2017 统一意识行为的结构候选解释）、Starkweather 2026 OFC 跨半球 CCEP 证据；8 条关键来源（PMID:41759515/PMC13160234、PMID:12382985、PMID:31412269、PMID:32399946/PMC7305066 等）

### 修订 wiki 页面（2 页）

- `concepts/split-brain.md` rev1→rev2：新增"标准裂脑手术保留前连合"这一关键细节到皮层下代偿路径节；新增 Pinto 2023（PMID:38021222）两路模型（自动处理分裂，有意识处理整合）到当前理解；更新 related 加入 anterior-commissure；补充 opens_questions（Q-ac-01, Q-unified-01）
- `systems/corpus-callosum.md` rev2→rev3：确认 anterior-commissure 悬空引用已填补；新增 Starkweather 2026（OFC 跨半球 CCEP）和 Barr 2002（AgCC 代偿案例）到 key_sources；更新 source_articles

### 图谱状态

- **新增节点**：`anterior-commissure`（1 个）
- **新增边**：8 条（anterior-commissure ↔ corpus-callosum、split-brain、amygdala、olfactory-system、agenesis-corpus-callosum、orbitofrontal-cortex、interhemispheric-competition）
- **悬空引用减少**：5 → 4（`anterior-commissure` 已填补；`aging`、`cognition`、`dopamine-system`、`superior-longitudinal-fasciculus` 待补）
- 图谱总计：326 节点，1873 条边

### 矛盾登记与裁决

- 无新矛盾登记；Q-unified-01（裂脑统一意识通路）获得新证据候选（AC 结构解释），但 open 状态保持（因果证据不足）

---

## 2026-10-02（文章 #162：意识障碍的临床谱系——植物状态、最小意识状态、锁闭综合征与认知运动解离如何成为意识理论的体内检验台）

### 新建 wiki 页面（4 页）

- `diseases/disorders-of-consciousness.md`（新建）：意识障碍谱系的总纲页面，涵盖 VS/MCS/LIS/CMD/PCI 的临床分类和神经基础；来源 Casarotto 2016, Claassen 2019, Bodien 2024, ISICEM 2025
- `concepts/cognitive-motor-dissociation.md`（新建）：认知运动解离（CMD）——行为无反应但神经有响应；15–25% DoC 患者阳性；Claassen 2019 + Bodien 2024 关键证据
- `diseases/vegetative-state.md`（新建）：植物状态 / 无反应觉醒综合征（VS/UWS）；40% 误判率；PCI 三组分层（30%无测、49%低、21%高）；6 个月预后数据
- `diseases/minimally-conscious-state.md`（新建）：最小意识状态（MCS）；MCS-/MCS+ 亚分类；PCI 94.7% 阳性；金刚烷胺治疗证据

### 修订 wiki 页面（2 页）

- `methods/perturbational-complexity-index.md` rev2→rev3：补充 Casarotto 2016（PMID:27717082）DoC 临床应用的完整验证数据；新增 disorders-of-consciousness 和 cognitive-motor-dissociation 到 related；补充 Q-phi-01
- `concepts/neural-correlates-of-consciousness.md` rev2→rev3：新增 disorders-of-consciousness 和 cognitive-motor-dissociation 到 related（DoC 是检验 NCC 最直接的临床数据集；CMD 是自然无报告范式）；补充 key_sources（PMID:27717082, PMID:31242361）

### 矛盾条目更新（无新矛盾）

- 无新矛盾登记。CMD 存在的哲学问题（"CMD = 意识？"）已记入 cognitive-motor-dissociation.md 的未解问题，但不构成与既有 wiki 主张的直接冲突（NCC 框架已包含无报告范式的不确定性）

### 图谱变化

- 新增节点：4（disorders-of-consciousness, cognitive-motor-dissociation, vegetative-state, minimally-conscious-state）
- 新增边：13（包括 is-a, mechanism-of, supports, related 等类型）
- 节点总数：325；边总数：1865
- 悬空引用减少（disorders-of-consciousness 等新节点填补了 PCI 页面的部分悬空引用）
- 剩余悬空引用：aging, anterior-commissure, cognition, dopamine-system, superior-longitudinal-fasciculus

---

## 2026-10-01（文章 #161：第七期周综合——振荡、胼胝体与高阶表征如何共同描绘意识神经科学的坐标系）

### 新建 wiki 页面（0 页）

- 无新建页面（综合文章涉及的概念均已有 wiki 页面）

### 修订 wiki 页面（3 页）

- `methods/adversarial-collaboration.md` rev1→rev2：补充 Sattin 2021 综述（PMID:33923218，29 种意识理论均能事后解释数据）作为对抗性协作必要性的独立证据；related 补充 recurrent-processing-theory、higher-order-theory、neural-correlates-of-consciousness；updated: 2026-10-01
- `theories/global-workspace-theory.md` rev9→rev10：综合文章新增 A/P consciousness 分离讨论——VAN 报告无关持续存在是对 GWT 作为 P-consciousness 解释的挑战；GWT 最合适作为 A-consciousness（可报告性）而非 P-consciousness 的解释框架；updated: 2026-10-01
- `theories/integrated-information-theory.md` rev6→rev7：综合文章补充 IIT 与 RPT 共同点（后方皮层、P-consciousness）；强调 Pinto 2017 对 IIT 裂脑预测的挑战；加入 Sattin 2021（PMID:33923218）作为背景框架来源；updated: 2026-10-01

### 矛盾条目更新（0 条新增）

- 无新矛盾登记。综合文章确认了已有矛盾条目（GWT vs VAN、IIT vs COGITATE）的当前状态，无新发现。

### 图谱变化

- 节点数：321（无新增节点，所有相关概念已在图谱中）
- 更新 `_graph.json` updated 字段为 2026-10-01
- 悬空引用（已知，待补）：aging, anterior-commissure, cognition, dopamine-system, superior-longitudinal-fasciculus

---

## 2026-09-30（文章 #160：高阶意识理论与无报告范式——当神经科学开始质疑自己的测量尺子）

### 新建 wiki 页面（5 页）

- `theories/higher-order-theory.md` rev1：高阶意识理论（HOT）——Rosenthal→Lau&Rosenthal 2011→LeDoux&Brown 2017 HOROR；高阶表征的两级结构（感觉一阶 + PFC 高阶）；一般认知网络（GNC）；情绪意识的皮层起源；与 GWT/RPT/IIT 的对比定位；Q-hot-01/02/03
- `methods/no-report-paradigm.md` rev1：无报告范式——Pitts 2014（VAN 持续，P3b 消失）+ Cohen 2020（F=151.13，P3b 6.55→0.462 µV）+ Siclari 2017（睡眠 87% 准确率）；Duman 2022 批评（过度/不足包含，心智游荡）；Q-nrp-01/02
- `concepts/visual-awareness-negativity.md` rev1：VAN（100-300ms，后枕区，报告独立性）——P3b 的对比与分离；神经发生器争议（V1 递归 vs 注意增益）；PAN 跨模态泛化；Q-van-01
- `concepts/access-consciousness.md` rev1：通达意识（Block A-consciousness）——与 P-consciousness 的概念区分；P3b 为 A-consciousness NCC；溢出争议；各理论对 A-P 关系的立场；Q-ac-01
- `concepts/phenomenal-consciousness.md` rev1：现象意识（Block P-consciousness）——qualia/what-it's-like；四大理论对 P-consciousness 神经基础的预测矩阵；VAN 和 Siclari 睡眠高频活动的 NCC 候选；Q-pc-01

### 修订 wiki 页面（3 页）

- `theories/recurrent-processing-theory.md` rev1→rev2：新增 Siclari 2017（PMID:28394322）NREM 睡眠无报告证据行（87% 准确率，前额叶对感知性梦非必要，支持后方皮层是意识基质）；related 增加 higher-order-theory、visual-awareness-negativity、phenomenal-consciousness；key_sources 增加 PMID:28394322
- `concepts/posterior-cortical-hot-zone.md` rev2→rev3：新增 Siclari 2017 精确数据行（后方顶枕高频，87% 预测，91.6%/80.7%，面孔梦→梭状回，空间梦→海马旁回）——PCHZ 的最强无报告证据；related 增加 no-report-paradigm、higher-order-theory、phenomenal-consciousness、visual-awareness-negativity；key_sources 增加 PMID:28394322
- `theories/global-workspace-theory.md` rev8→rev9：新增 Cohen 2020（PMID:32409620）精确统计数据行（P3b 6.55→0.462 µV，F=151.13，p<0.001，86.3% 记忆识别）——P3b 不是意识 NCC 而是报告 NCC 的最直接量化证据；related 增加 higher-order-theory、no-report-paradigm、visual-awareness-negativity、access-consciousness；key_sources 增加 PMID:32409620

### 矛盾条目更新（0 条新增）

- 无新矛盾登记。P3b 不是意识 NCC 与 GWT 主张可调和（GWT 可以主张 P3b 反映的是 A-consciousness 广播，而非意识内容本身），不构成直接矛盾；仅作为 Q-gwt-01 的强化证据记录在 GWT 修订历史中。

### 图谱变化

- 节点数：321（新增 5 个：higher-order-theory, no-report-paradigm, visual-awareness-negativity, access-consciousness, phenomenal-consciousness）
- 新增边：15 条（HOT→GWT, HOT→RPT 对立, HOT→PFC 机制, VAN→PCHZ 支持, 等）
- 修订节点（3 个）：recurrent-processing-theory（rev2），posterior-cortical-hot-zone（rev3），global-workspace-theory（rev9）

### 新增悬空引用待补

- `eeg-erp`：visual-awareness-negativity.md 的 prerequisites 中引用，尚无独立页面（可纳入 methods 领域）

---

## 2026-09-29（文章 #159：当意识被计算——整合信息 Φ 的 NP-Hard 困境、整合-放电网络的新实验，以及扰动复杂性指数的临床十年）

### 修订 wiki 页面（3 页，无新建）

- `concepts/phi-measure.md` rev1→rev2：新增 IIT 4.0 版本（ΦID 近似框架）；新增 Danilczuk 2026（IF 网络 Φ：递归提升、噪声降低、时间常数扩大、规模扩大）；新增 Onoda 2025（宏观 fMRI Φ，5网络，麻醉/NREM 下降，REM 不变）；新增 Shin 2025 AI Φ 分析（LLM 前馈 Φ≈0）和 Aaronson XOR 批评；扩展近似方法表（ΦID/pyphi/平均场/宏观Φ）；新增证据行（Danilczuk 2026、Onoda 2025、Shin 2025）；新增 Q-iit-06（宏观 vs 微观 Φ 关系）；related 增加 recurrent-processing-theory、critical-dynamics
- `methods/perturbational-complexity-index.md` rev1→rev2：新增 Maschke 2024（临界动力学作为 PCI 替代机制解释：皮层距相变临界点越近，响应越复杂）；新增 Stikvoort 2025（非平衡有效连接框架：有效连接非对称性驱动传播复杂性）；新增 Xu 2024（rTMS RCT，N=40，35%响应者，PCIst 预测疗效，6月随访）；新增 Hagan 2026（AD PCIst：M=20.1 vs 对照 M=28.2，与 MMSE 相关）；新增 Fecchio 2026（ICU 应用）；新增 PCI vs Φ vs 宏观Φ 三方比较表；新增 Q-pci-01/02/03；related 增加 critical-dynamics、default-mode-network、neural-correlates-of-consciousness
- `theories/integrated-information-theory.md` rev5→rev6：增加 IIT 4.0（ΦID，ΦID 近似操作化排他性公理）；新增 Onoda 2025（宏观 Φ 随麻醉/NREM 显著下降，支持 IIT 意识水平预测）；新增区分"意识水平预测（Onoda 支持）"vs"机制预测（COGITATE 否定）"；新增 Danilczuk 2026（IF 网络：递归提升 Φ）；新增证据行（Onoda 2025 宏观 Φ，Danilczuk 2026 递归 Φ）；新增 Q-iit-06；source_articles 增加 2026-09-29-phi-computation-pci-consciousness-measurement；key_sources 增加 PMID:40901488、PMID:41801929

### 矛盾条目更新（1 条）

- C-2026-05-31-01（IIT 后方皮层同步 vs COGITATE）：新增 2026-09-29 证据更新——Onoda 2025 宏观 Φ 证据支持 IIT 的"意识水平预测"（Φ 随麻醉下降），但不能否定 COGITATE 的"机制预测失败"（gamma 同步缺失）。关键新维度：level prediction（宏观 Φ 支持）vs mechanism prediction（微观 gamma 同步否定）属于不同层次，不直接矛盾。裁决仍 open，但证据图景更丰富。

### 图谱变化

- 节点数：316（无变化；critical-dynamics 记录为悬空引用，未建正式节点）
- 边变化：phi-measure 和 perturbational-complexity-index 的 related 字段各新增 critical-dynamics（待正式化）
- 受更新节点（3个）：phi-measure（rev1→rev2）、perturbational-complexity-index（rev1→rev2）、integrated-information-theory（rev5→rev6）

### 登记矛盾（0 条新增）

- 无新矛盾登记（Onoda 2025 宏观 Φ 与 COGITATE 微观否定，属于不同实验层次，不构成新矛盾；已在 C-2026-05-31-01 的证据更新中记录为"层次区分"）

### 新增悬空引用待补

- `critical-dynamics`：被 phi-measure 和 perturbational-complexity-index 的 related 字段引用；待创建 `wiki/concepts/critical-dynamics.md`（临界动力学：二阶相变、幂律、大脑临界性假说、与意识/癫痫的关系）
- `alzheimers-disease`：被 perturbational-complexity-index 的 related 字段引用（Hagan 2026 AD 应用）；若已有 diseases/alzheimers.md 则补充相关；否则待创建

### 新增未解问题（4 条）

- Q-pci-01（高）：PCI 究竟测量什么——Φ 代理、临界动力学，还是非平衡有效连接？三种理论解释之间能否设计实验区分？
- Q-pci-02（高）：PCIst 作为 rTMS 疗效预测指标的最优切割点和临床价值，能否在 N>200 的 RCT 中复现？
- Q-pci-03（中）：AD 患者 PCIst 下降能否先于认知症状出现？与淀粉样蛋白 PET 的相关性如何？MCI 阶段是否已可检测？
- Q-iit-06（高）：宏观 Φ（fMRI 网络层面）与微观 Φ（神经元层面）是否测量同一现象？宏观支持（Onoda 2025）能否为 IIT 提供充分验证？

---

## 2026-09-28（文章 #158：前馈与递归——Victor Lamme 的递归处理理论如何把意识锚定在视觉皮层的反馈回路中）

**今日主题：** 递归处理理论（RPT）——前馈扫描 vs 递归处理的两种视觉模式；V1 图像-背景分离信号作为 RPT 核心神经标记；麻醉/掩蔽实验证据；四阶段视觉意识模型；RPT vs GWT vs IIT 三方比较；无报告范式方法论；Allen et al. 2020 的 TMS 挑战；"缺失要素"（NMDA+网络可塑性）。填补图谱悬空引用 `recurrent-processing-theory`（在 2026-09-27 CHANGELOG 中已标记为待建）。

### 新建 wiki 页面（1 个）

- `wiki/theories/recurrent-processing-theory.md` — 递归处理理论 | mainstream / medium | 填补 2026-09-27 悬空引用；前馈（无意识）vs 递归（有意识）两种处理模式；V1 图像-背景分离信号三条证据链（麻醉 PMID:9501251、掩蔽 PMID:12419127、刺激前状态 PMID:12716948）；四阶段模型（PMID:32116908）；RPT vs GWT（无前额叶广播必要）vs IIT（时间动态 vs 因果结构）；无报告范式（PMID:26585549）；Allen TMS 挑战（PMID:32922860）；缺失要素（PMID:30061458）

### 修订 wiki 页面（3 个）

- `wiki/theories/global-workspace-theory.md` rev8 — 新增 recurrent-processing-theory 到 related；在连接节新增 RPT 对照说明（意识是否需要前额叶广播的核心分歧）
- `wiki/theories/integrated-information-theory.md` rev5 — 新增 recurrent-processing-theory 到 related；在连接节新增 RPT vs IIT 机制差异（Φ vs 时间动态；RPT 不接受 IIT 泛心论推论）
- `wiki/concepts/neural-correlates-of-consciousness.md` rev2 — 新增 recurrent-processing-theory 到 related 和连接节；更新三理论对比表（GWT/IIT/RPT 三列比较：NCC 位置/时间动力学/核心机制/注意是否必要/报告是否等于意识/COGITATE 支持程度）

### 图谱更新

- 新增节点：`recurrent-processing-theory`；图谱节点数：315 → 316
- 新增边（6 条）：recurrent-processing-theory→global-workspace-theory（contradicts）；recurrent-processing-theory→integrated-information-theory（related）；recurrent-processing-theory→neural-correlates-of-consciousness（mechanism-of）；recurrent-processing-theory→v1-primary-visual-cortex（mechanism-of）；recurrent-processing-theory→predictive-coding（related）；recurrent-processing-theory→consciousness-ignition（contradicts）；图谱边数：1832 → 1838

### 登记或裁决矛盾

- **无新矛盾登记**：Allen et al. 2020 的 TMS 结果（早期 TMS 比晚期 TMS 更大破坏意识）被记入 wiki/theories/recurrent-processing-theory.md 关键证据表，作为"挑战简单二分法"的反例，置信度"中"，不构成裂脑级别的直接矛盾——更多是 RPT 简化版本的修正信号

### 新增悬空引用待补

- `figure-ground-segregation`（RPT 页面连接中引用，独立概念页尚未建立）
- `no-report-paradigm`（RPT 页面连接中引用，方法论页面尚未建立）
- `feedforward-processing`（RPT 页面 prerequisites 中引用，概念页尚未建立）

---

## 2026-09-27（文章 #157：当胼胝体被切断——裂脑患者的意识、诠释者与 Pinto 的统一意识论）

**今日主题：** 裂脑综合征（Gazzaniga 经典"双意识"与 Pinto 2017"统一意识+分裂感知"框架）、意识理论检验（IIT/GWT/RPT 各自的裂脑预测）、诠释者模块、跨提示争议、触觉/fMRI 后续证据（de Haan 2020/2021）、异手综合征（agency 解离）、填补图谱悬空引用 `split-brain`。

### 新建 wiki 页面（2 个）

- `wiki/concepts/split-brain.md` — 裂脑综合征 | mainstream / medium | 填补悬空引用；Sperry/Gazzaniga 经典实验（视野测试、诠释者效应）；Pinto 2017 三报告通道实验；de Haan 2020 触觉（任意手可报告任意侧触觉）；de Haan 2021 resting-state fMRI（双侧相关持续）；IIT/GWT/RPT 对裂脑的不同预测；交叉提示争议；PMID:32399946/PMC7305066、31923846/PMC7061321、PMC8048575、28958646
- `wiki/diseases/alien-hand-syndrome.md` — 异手综合征 | mainstream / medium | 三种亚型（前型/SMA、后型/后顶叶、胼胝体型）；agency 解离机制；与 split-brain 的关系；PMID:41053873/PMC12502178

### 修订 wiki 页面（3 个）

- `wiki/theories/integrated-information-theory.md` rev4 — 新增"裂脑综合征对 IIT 的挑战"节（Φ分裂预测 → 两个意识；Pinto 统一证据是对 IIT 排他性公理的直接挑战；可能的逃避路线）；新增 split-brain 到 related；补充 Q-cc-01；PMID:32399946
- `wiki/theories/global-workspace-theory.md` rev7 — 新增裂脑的 GWT 预测（两侧前额叶分别形成独立工作空间→两个意识）；补充 Pinto 证据对 GWT 的挑战；新增 split-brain 到 related；新增 Q-cc-01
- `wiki/systems/corpus-callosum.md` rev2 — 新增意识章节（裂脑意识深入证据的来源标注）；补充 split-brain 文章到 source_articles

### 图谱更新

- 新增节点：`split-brain`、`alien-hand-syndrome`；图谱节点数：313 → 315
- 新增边（9 条）：split-brain→corpus-callosum（mechanism-of）；split-brain→integrated-information-theory（contradicts）；split-brain→global-workspace-theory（contradicts）；split-brain→neural-correlates-of-consciousness（related）；split-brain→language-lateralization（related）；split-brain→interhemispheric-competition（related）；alien-hand-syndrome→split-brain（related）；alien-hand-syndrome→corpus-callosum（part-of）；corpus-callosum→split-brain（mechanism-of）；图谱边数：1823 → 1832

### 登记或裁决矛盾

- **Q-cc-01（深化但仍 open）**：裂脑意识分裂问题——今日文章系统整理了 Pinto 2017/de Haan 2020/2021 的支持统一意识的证据，以及 Volz/Gazzaniga 的交叉提示批评。证据深化但无法裁决，Q-cc-01 仍保持 open 状态。
- 无新矛盾登记到 contested_claims.json（两种意识框架基于理论预设，非直接数据矛盾）

### 新增悬空引用待补

- `recurrent-processing-theory`（Lamme RPT，split-brain.md 连接中需要，今日未建）
- `supplementary-motor-area`（SMA，alien-hand-syndrome.md 连接中引用，今日未建）
- `anterior-commissure`（corpus-callosum.md 中已存在悬空引用，本日文章再次引用）

---

## 2026-09-26（文章 #156：连接两个大脑——胼胝体的解剖地图、发育时钟与裂脑之谜）

**今日主题：** 胼胝体解剖拓扑（五段/纤维直径梯度）、发育时序（后→前髓鞘化，前额叶连接约25岁成熟）、跨胼抑制（TMS-iSP范式、发育与老化轨迹）、胼胝体缺失症（AgCC，1/4000，复杂推理损害+晶体智力保留）、裂脑综合征与意识分裂争议（Pinto 2017 vs Sperry/Gazzaniga）。填补图谱悬空引用 `corpus-callosum`。

### 新建 wiki 页面（3 个）

- `wiki/systems/corpus-callosum.md` — 胼胝体 | established / high | 五段拓扑（rostrum/genu/body/isthmus/splenium）各连接对应皮层功能区；纤维直径梯度（膝部细→峡部粗）；70%有髓鞘；发育后→前时序；DTI FA值；AgCC（1/4000，复杂推理损害）；裂脑综合征+意识争议；PMID:25550994/PMC4278150、32399946/PMC7305066、30691545/PMC7989584、17375041
- `wiki/concepts/transcallosal-inhibition.md` — 跨胼抑制 | established / high | TMS-iSP范式（潜伏期~35-40ms，持续~14-16ms）；发育：潜伏期r=−0.631随年龄缩短；老化：iSP面积减少57%（73岁vs年轻）；女孩早于男孩5ms；单侧运动精确性和半球间竞争的物理基础；PMID:28381485/PMC5494372、23800346/PMC3695846
- `wiki/diseases/agenesis-corpus-callosum.md` — 胼胝体缺失症 | established / high | 发生率1/4000；核心缺陷：跨半球传递、处理速度、复杂推理；保留：晶体智力、过度学习技能（IQ通常>80）；代偿：前连合、发育可塑性；先天vs后天切除差异揭示可塑性关键期；PMID:30691545/PMC7989584、17375041

### 修订 wiki 页面（0 个）

- 无需修订既有页面（corpus-callosum 为新建，前两天的 interhemispheric-competition 和 spatial-neglect 已完整描述胼胝体相关内容；今日填补结构基础页面）

### 图谱更新

- 新增节点：`corpus-callosum`、`transcallosal-inhibition`、`agenesis-corpus-callosum`；图谱节点数：310 → 313
- 新增边（12 条）：corpus-callosum↔interhemispheric-competition（part-of）；transcallosal-inhibition→corpus-callosum（mechanism-of）；transcallosal-inhibition→interhemispheric-competition（mechanism-of）；transcallosal-inhibition→motor-cortex（regulates）；corpus-callosum→motor-cortex（regulates）；corpus-callosum→prefrontal-cortex（related）；agenesis-corpus-callosum→corpus-callosum（related）；agenesis-corpus-callosum→anterior-commissure（related）；corpus-callosum→spatial-neglect（related）；corpus-callosum→DAN（related）；corpus-callosum→VAN（related）；corpus-callosum→alpha-oscillations（related）；图谱边数：1811 → 1823

### 登记或裁决矛盾

- 无新矛盾登记（裂脑意识争议 Q-cc-01 登记为未解问题，但两种解读均有合理证据基础，不属于"证据直接冲突"而是"诠释框架分歧"）

### 新增悬空引用待补

- `split-brain`（引用于corpus-callosum相关，建议建立裂脑综合征专页）
- `alien-hand-syndrome`（引用于文章，建议建立异手综合征专页）
- `anterior-commissure`（在agenesis-corpus-callosum中引用为代偿通路，建议建立前连合页面）

---

## 2026-09-23（文章 #153：大脑的断路器——腹侧注意网络如何在专注中守护感知完整性）

**今日主题：** 腹侧注意网络（VAN）的解剖（TPJ+VFC）、功能（断路器模型）、右侧化机制、注意重定向的振荡动力学（P3a, α快速重组）和空间忽视（半侧空间忽视）的网络机制。从振荡/语言主题（#151-152）切换到认知控制×感觉编码轨道。

### 新建 wiki 页面（1 个）
- `wiki/concepts/ventral-attention-network.md` — 腹侧注意网络（VAN） | established / high | 核心节点 rTPJ+VFC；断路器模型（正常任务被 DAN 抑制，意外时激活打断 DAN）；右侧化机制；LC-NE 调制；P3a/α 振荡标志；空间忽视联系；PMID:11994752, 18466742, 21692662, 23835449

### 修订 wiki 页面（3 个）
- `wiki/concepts/dorsal-attention-network.md`（rev3→rev4）：新增"DAN-VAN 动态对话"节（断路器模型、反相关、空间忽视网络破坏）；related 新增 ventral-attention-network；key_sources 新增 PMID:18466742, 21692662
- `wiki/systems/tpj-temporoparietal-junction.md`（rev1→rev2）：新增"TPJ 作为 VAN 核心感知节点"节（多流汇聚、预测违背检测、P3a 时序、双重功能统一框架、空间忽视）；related 新增 ventral-attention-network, norepinephrine-locus-coeruleus；opens_questions 新增 Q-van-01
- `wiki/concepts/alpha-oscillations.md`（rev3→rev4）：新增"α 在注意重定向中的快速重组"节（VAN 激活触发 α 反转、P3a 时序关系）；related 新增 ventral-attention-network

### 图谱更新
- 新增节点：`ventral-attention-network`（VAN）；图谱节点数：306 → 307
- 新增边（7 条）：VAN→TPJ（part-of），TPJ→VAN（part-of），VAN→DAN（regulates），DAN→VAN（regulates），VAN→α-oscillations（mechanism-of），VAN→NE-系统（related），DAN→VAN（related）；图谱边数：1788 → 1795

### 登记或裁决矛盾
- 无新矛盾登记（VAN的功能模糊性是程度/边界问题，不是真正的相互冲突主张）

### 新增未解问题
- Q-van-01（高）：VAN/TPJ 激活的"行为相关性门控"机制——如何区分行为无关意外噪声 vs 行为相关意外信号？
- Q-van-02（中）：VAN 抑制深度是否随任务难度非线性变化？是否存在注意捕获的"最大抑制"上限？

### 新增悬空引用待补
- `spatial-neglect-concept`（在 ventral-attention-network.md 中作为 related 引用，建议为空间忽视建立专用 wiki 页面）

---

## 2026-09-21（文章 #151：δ振荡——大脑解析语音层级的慢速时钟）

**今日主题：** δ振荡（1–4 Hz）在语音处理和语言层级追踪中的功能。填补图谱中 `delta-oscillations` 悬空引用。核心发现：δ追踪抽象语法结构（Ding 2016）；δ是语音特异性的（Molinaro 2018）；清醒语音δ与睡眠δ的机制区别；阅读障碍的TSF框架（Goswami 2011）。

### 新建 wiki 页面（1 个）
- `wiki/concepts/delta-oscillations.md` — δ振荡 | mainstream / medium | 清醒语音处理（预测性夹带，语法层级追踪，语言特异性）与睡眠记忆巩固（HCN/T型钙通道，内嗅皮层TA通路）的双重功能；PMID:22426255, 26642090, 29283465, 34083380, 21093350, 37838945

### 修订 wiki 页面（2 个）
- `wiki/concepts/neural-oscillations.md`（rev2→rev3）：细化 δ 频段说明（语音语法追踪 + 睡眠记忆巩固双重功能；与 SO 的区别）；related 新增 delta-oscillations（填补悬空引用）；key_sources 新增 PMID:22426255、26642090
- `wiki/concepts/cortical-slow-oscillation.md`（rev4→rev5）：明确 SO（<1 Hz）与 δ（1–4 Hz）的机制区别；related 新增 delta-oscillations、neural-oscillations

### 图谱更新
- delta-oscillations 节点从"悬空引用"状态转为"已有 wiki 页面"；新增 7 条边（delta-oscillations → neural-oscillations, theta-oscillations, predictive-coding, cortical-slow-oscillation, communication-through-coherence, memory-consolidation）；图谱边数：1745 → 1752

### 登记或裁决矛盾
- 无新矛盾登记（δ的双重功能是机制区别，非冲突主张）

### 新增未解问题
- Q-delta-01（高）：声学驱动 vs 句法计算驱动的 δ 相位分离方法论
- Q-delta-02（中）：阅读障碍 δ 缺陷的皮层 vs 脑干起源
- Q-delta-03（中）：清醒语音 δ 与睡眠 δ 的机制关联性

### 新增悬空引用待补
- `dyslexia`（在 delta-oscillations 中引用，TSF框架建议创建专页）
- `language-network-dual-stream`（已存在，但与 delta 的连接较稀疏，建议后续加深）

---

## 2026-09-20（文章 #150 周综合：当节律守门人遇见认知层级——七天思考的汇聚点）

**今日主题：** 周综合（#143-149）——从PV-γ精神分裂症（#143）→多巴胺D1R倒U型（#144）→NMDA GluN2亚单位发育切换（#145）→遗传汇聚PV-γ回路（#146）→θ-γ嵌套工作记忆（#147）→θ序列情节记忆（#148）→振荡层级全脑架构（#149）的七篇整合叙事。核心新概念：**时序多路复用**（temporal multiplexing）；核心合成认识：PV中间神经元是认知超级节点，振荡是认知计算的时序基础设施。

### 新建 wiki 页面（1 个）
- `wiki/concepts/temporal-multiplexing.md` — 时序多路复用 | mainstream / medium | θ-γ嵌套为WM实现4-8项并行存储；θ序列为情节记忆实现20-40倍时间压缩；Boran 2024 PAC细胞直接证据；与AI位置编码的对比

### 修订 wiki 页面（2 个）
- `wiki/circuits/pv-interneurons.md`（rev6→rev7）：升级"当前理解"段——从"抑制细胞"到"认知超级节点"定位（接收NMDA/DA分子输入，输出γ振荡，是DISC1/NRG1/GRIN2A遗传汇聚点和θ-γ耦合执行者）；related新增temporal-multiplexing/theta-gamma-coupling/dopamine-pfc-inverted-u
- `wiki/concepts/neural-oscillations.md`（rev1→rev2）：related新增temporal-multiplexing/theta-sequences（振荡层级的两个核心认知用例）；source_articles新增周综合文章

### 登记或裁决矛盾
- 无新矛盾登记（本次为周综合，无新原始来源；矛盾C-2026-09-17-01和Q-osc-01仍open，本周证据未化解）

### 新增悬空引用待补
- `delta-oscillations`（在neural-oscillations.md中多次引用）、`aging`（在GluN2切换叙事中引用）——仍为悬空引用，建议下周优先处理

---

## 2026-09-19（文章 #149：节律的层级——大脑振荡频段如何通过相位嵌套构建多时间尺度通信架构）

**今日主题：** 皮层振荡层级综合——从慢振荡（<1 Hz）到 γ（>30 Hz）的六个频段产生机制（Steriade 1993、Lakatos 2005、Whittington 2003、Engel & Fries 2010）；相位振幅耦合（PAC）三层嵌套直接证据（δ→θ→γ，Lakatos 2005）；通信通道假说（CTC，Fries 2015，全文读）；频率-方向分工（γ前馈 vs α-β反馈）与预测编码框架的统一；振荡层级的多时间尺度整合功能

### 新建 wiki 页面（1 个）
- `wiki/concepts/neural-oscillations.md` — 神经振荡层级 | mainstream / medium | 六频段产生机制总结；PAC三层嵌套（Lakatos 2005）；CTC框架（Fries 2015）；频率-方向分工；与预测编码统一

### 修订 wiki 页面（3 个）
- `wiki/concepts/beta-oscillations.md`（rev1→rev2）：新增β在全脑振荡层级中的角色（Engel & Fries 2010状态保持假说；CTC反馈方向；PMBR机制）；related新增neural-oscillations/predictive-coding/communication-through-coherence/canonical-microcircuit；key_sources新增PMID:20359884/26447583
- `wiki/concepts/gamma-oscillations.md`（rev7→rev8）：新增γ在振荡层级中的位置节（PAC嵌套层级；前馈载体角色；频率-方向分工与预测编码对应）；related新增neural-oscillations/predictive-coding/canonical-microcircuit；key_sources新增PMID:15218136/15901760
- `wiki/concepts/alpha-oscillations.md`（rev2→rev3）：补充α与PAC层级框架的关系（Canolty & Knight 2010）；related新增neural-oscillations/canonical-microcircuit；opens_questions新增Q-osc-02

### 登记或裁决矛盾
- **无新矛盾登记**（振荡层级框架是 mainstream，已有广泛独立证据支持；PAC的功能因果性争议已在 Q-osc-01 中登记，但程度不足以登记 contested_claim）

### 新增未解问题
- `Q-osc-01`：振荡是功能性计算机制还是能量耗散副产品？（高优先级）
- `Q-osc-02`：CTC框架中频率-方向分工的跨区普适性？（中优先级）

### 填补悬空引用
- `delta-oscillations` — 文章中提到δ振荡但无wiki节点，已在图谱中添加stub节点，待后续补页

### 新增悬空引用（待补页面）
- `delta-oscillations` — 今天文章详细讨论了δ振荡但尚无独立wiki页面

### 图谱变化
- 节点：302 → 304（+2：neural-oscillations、delta-oscillations）
- 边：1745 → 1763（+18）

---

## 2026-09-18（文章 #148：θ序列——大脑如何在每个节律脉冲中同时容纳过去、当下与未来）

**今日主题：** θ序列（theta sequences）的完整机制——相位进动的群体效应、10:1时间压缩、CA3/CA1分工（Dragoi & Buzsáki 2006）、θ振荡内前向/逆向双序列（Wang et al. 2020, Science）、前瞻性扫描（Pfeiffer & Foster 2013, Nature）、内侧隔核相位框架（Petersen & Buzsáki 2020, Neuron）、DG/MEC回路分工（Ahmadi 2025）、人类证据（Reddy 2021）；填补medial-septum悬空引用

### 新建 wiki 页面（2 个）
- `wiki/concepts/theta-sequences.md` — θ序列 | established / high | 核心机制：相位进动→群体θ序列（10:1压缩）→前向（CA3）/逆向（EC III）双向序列（PMID:33033222）→前瞻性扫描（PMID:23594744）→相位坐标框架（PMID:32526196）→DG/MEC回路分工（PMID:39746924）→人类MTL证据（PMID:34376673）
- `wiki/systems/medial-septum.md` — 内侧隔核 | established / high | 填补dangling reference；MS-DBB为θ振荡主要起搏器；MS冷却实验：距离-相位压缩保留（P=0.92）但行为错误增加3倍；θ序列以相位为坐标

### 修订 wiki 页面（2 个）
- `wiki/concepts/theta-phase-precession.md`（rev1→rev2）：关键证据表从4行扩展至10行（新增：Skaggs 1996压缩比、Dragoi 2006 CA3/CA1分工、Pfeiffer 2013前瞻性扫描、Petersen 2020 MS冷却、Wang 2020双向序列、Ahmadi 2025 DG回路、Reddy 2021人类证据）；连接新增theta-sequences/medial-septum/entorhinal-cortex/sharp-wave-ripples；opens_questions新增Q-ts-01/Q-ts-02/Q-ts-03；key_sources从2个扩展到10个
- `wiki/concepts/theta-oscillations.md`（rev4→rev5）：related新增theta-sequences/medial-septum；key_sources新增PMID:32526196/33033222；opens_questions新增Q-ts-01；source_articles新增2026-09-18

### 登记或裁决矛盾
- **无新矛盾登记**（今日文章的证据与既有wiki主张一致；双向序列属于新发现而非与旧观点冲突）

### 填补悬空引用
- `medial-septum` → 已于本日创建wiki/systems/medial-septum.md，填补theta-oscillations页面的dangling reference

### 新增悬空引用（待补页面）
- `path-integration` — θ序列的前瞻性扫描（prospective sweeps）与路径整合密切相关；theta-sequences页面引用

### 图谱变化
- 节点：300 → 302（+2：theta-sequences、medial-septum）
- 边：1733 → 1745（+12）

### 新增未解问题（4 条）
- **Q-ts-01**（高优先）：θ序列/相位进动在非空间情节记忆中是否存在？
- **Q-ts-02**（高优先）：双向θ序列的CA3/EC III回路假说需光遗传学因果验证
- **Q-ts-03**（中优先）：STDP vs BTSP的相对贡献？两者是否分管不同时间尺度？
- **Q-ts-04**（中优先）：MS冷却后行为错误增加3倍但相位框架保留——确切原因？

---

## 2026-09-15（文章 #145：NMDA 受体的两张脸——GluN2B→GluN2A 发育切换与突触可塑性阈值的终身漂移）

**今日主题：** NMDA 受体 GluN2B→GluN2A 亚单位发育切换的分子机制（REST 表观遗传沉默 + GluN2A 浓度驱动）；切换如何升高 LTP 阈值（CaMKII-GluN2B 锚定机制）；人类皮层切换峰值约 36 岁（Siu 2017）；老年期 GluN2A 骤降 75%；"更多 GluN2A ≠ 更好"（Li 2022）；部分解答 Q-glun2-switch-development

### 新建 wiki 页面（1 个）
- `wiki/concepts/glun2-developmental-switch.md` — GluN2 亚单位发育切换 | established / high | REST 驱动 GluN2B 下调 + GluN2A 浓度主导切换（McKay 2018）；人类皮层 GluN2A:2B 峰值约 36 岁、老年期骤降 75%（Siu 2017）；CaMKII-GluN2B 物理结合是 LTP 充要条件（Nicoll 2023）；GluN2A 过量损害 LTP+LTD+认知（Li 2022）；BCM 修改阈值的分子底层

### 修订 wiki 页面（1 个）
- `wiki/concepts/nmda-receptor.md`（rev4→rev5）：新增第五重角色"GluN2 亚单位切换与突触可塑性阈值的终身调节"小节；GluN2B/2A 衰减时间常数对比；人类峰值数据；CaMKII-GluN2B 锚定机制；"平衡优于最大化"；related 新增 glun2-developmental-switch, bcm-rule, critical-period-plasticity；key_sources 新增 PMID:22960932, 28554889, 37290118, 35484243；opens_questions 新增 Q-glun2-triheteromeric-region-ratio；source_articles 新增 2026-09-15 文章

### 登记或裁决矛盾
- **新登记 C-2026-09-15-01**："GluN2A 促 LTP / GluN2B 促 LTD" 历史模型 vs 当前证据（over-simplified claim）→ 登记为 contested，见 state/contested_claims.json

### 新增悬空引用（待补页面）
- 无新增（aging 页面尚未创建，但为 glun2-developmental-switch 的 related，已标记）

### 图谱变化
- 节点：296 → 297（+1：glun2-developmental-switch）
- 边：1703 → 1711（+8）

### 新增未解问题（3 条）
- Q-glun2-switch-upstream-rest（高）：REST 激活本身的上游信号是什么？
- Q-glun2-triheteromeric-region-ratio（中）：成熟突触三异四聚体比例的脑区特异性？
- Q-aging-glun2a-loss-mechanism（中）：老年期 GluN2A 选择性骤降的精确机制？

### 部分解答开放问题（1 条）
- Q-glun2-switch-development（部分解答）：切换由 REST 表观遗传沉默 + GluN2A 浓度共同驱动，非 CTD 特异性机制；人类切换漫长（峰值约 36 岁）。未解部分：REST 激活上游信号、三异四聚体脑区比例、老年期骤降机制

---

## 2026-09-14（文章 #144：多巴胺双面刃——前额叶 D1 受体倒 U 型工作记忆调控）

**今日主题：** 多巴胺 D1 受体对前额叶 dlPFC 工作记忆的倒 U 型调控机制；D1R-cAMP-HCN 通道分子级联；低剂量滤噪 vs 高剂量全面压制；D1R（层III棘 Delay cells）vs D2R（层V树突干 Response cells）解剖分工；应激→DA/NE过载→HCN开放→PFC关闭；SCZ认知症状（Okubo 1997 PET）；胍法辛 α2A 机制；解答 Q-d1-inverted-u-mechanism

**新建 wiki 页面（1 个）：**
- `wiki/concepts/dopamine-pfc-inverted-u.md`（新建，rev1）：D1R→cAMP→HCN/KCNQ门控机制完整页；低/高剂量细胞级联；D1/D2解剖分工表；α2A拮抗对；应激路径；D1R vs WM方差26%（荟萃分析）；Q-d1-pfc-01/02/03新增；confidence=high；Q-d1-inverted-u-mechanism标注已解答

**修订 wiki 页面（2 个）：**
- `wiki/concepts/d1-d2-receptor-signaling.md`（rev1→rev2）：opens_questions 删除已解答 Q-d1-inverted-u-mechanism；在未解问题中标注"✅已解答"并指向 dopamine-pfc-inverted-u 页；related 新增 dopamine-pfc-inverted-u, hcn-channel；dimensions 新增 cognition；source_articles 新增今日文章
- `wiki/concepts/working-memory.md`（rev9→rev10）：related 新增 dopamine-pfc-inverted-u, d1-d2-receptor-signaling；dimensions 新增 molecular；source_articles 新增今日文章；修订历史追加今日条目；key_sources 新增 PMID:17277774, PMID:25731884, PMID:35389678

**登记或裁决矛盾：**
- Q-d1-inverted-u-mechanism：今日文章因果确认 HCN 通道大量开放是高剂量 D1R 损害 WM 的充要机制（ZD7288 逆转实验），此前 d1-d2-receptor-signaling.md 的 open question 已标注为 resolved（非矛盾，是机制补全）
- SCZ 的 D1R PET 发现仍存在争议（Okubo 1997 vs Cumming 2021 综述提及部分研究反而上调），登记为 contested（见 state/contested_claims.json，C-2026-09-14-01）

**新增悬空引用（待补）：**
- `hcn-channel`：HCN 通道页面在本文中多次被提及（dopamine-pfc-inverted-u.md 的 related 和 working-memory.md 中的 NE 段落引用），尚无独立 wiki 页，建议下次写"HCN 通道与 PFC 认知"时创建

**图谱变化：** 288节点（+1：dopamine-pfc-inverted-u），1637边（+9）

**新增未解问题（3 条）：**
- Q-d1-pfc-01（中）：人类 dlPFC D1R-HCN2 共定位的解剖证据——目前主要来自猕猴，人类解剖学验证缺失
- Q-d1-pfc-02（高）：SCZ 患者 dlPFC D1R PET 结合力变化方向（减少 vs 增加）——不同研究结论矛盾，是否与发病阶段/药物史相关？
- Q-d1-pfc-03（中）：D1R 激活 PV 中间神经元（增强抑制）vs D1R 直接激活锥体棘（HCN 门控）两条路径在活体 WM 任务中各自贡献比例

---

## 2026-09-12（文章 #142：TrkB受体的三重角色）

**今日主题：** TrkB受体结构（Y490/Y816磷酸化节点，三通路）、PV细胞成熟时钟（Huang 1999）、PNN-PTPσ-TrkB关键期闸门（Lesnikova 2021）、成年海马新生神经元4-6周存活判决（PNAS 2008）、TrkB跨膜域变构靶点（Li 2024）、TrkB/mGluR5交叉对话（Arefin 2026）、截断型TrkB.T1独立信号功能

**新建 wiki 页面（1 个）：**
- `wiki/concepts/trkb-receptor.md`（新建，rev1）：TrkB受体完整机制页；三通路分工表（MAPK/ERK、PI3K/Akt、PLCγ）；PNN-PTPσ封锁机制；TrkB.T1主动信号功能表；三个生理角色（PV细胞时钟/关键期闸门/AHN存活判决）；Q-trkb-01/02/03新增；confidence=high（基础结构/三通路），medium（TrkB.T1独立信号/2026新发现）

**修订 wiki 页面（2 个）：**
- `wiki/concepts/bdnf.md`（rev3→rev4）：新增TrkB跨膜域作为多类抗抑郁药变构靶点段落（Li 2024，PMID:38433044）；新增TrkB/mGluR5双模式交叉对话段落（Arefin 2026，PMID:42066082）；related新增trkb-receptor；key_sources新增2条
- `wiki/concepts/adult-neurogenesis.md`（rev4→rev5）：新增"TrkB依赖的存活判决"子节（PI3K/Akt→Bcl-2抗凋亡；TrkB KO→焦虑；抗抑郁药增殖 vs BDNF/TrkB存活的分工）；related新增trkb-receptor；key_sources新增PMID:18832146、PMID:15689544

**登记或裁决矛盾：** 无新矛盾（TrkB.T1的dominant negative vs 主动信号争议已在既有contested_claims登记框架外；作为已知概念扩展而非新矛盾处理，因为两种功能在不同实验系统中均有证据支持）

**新增悬空引用（待补）：** 无（本次新建trkb-receptor填补了bdnf/adult-neurogenesis等页面的关键引用空缺；synaptic-transmission已有页面）

**图谱变化：** 293→294节点（+1：trkb-receptor），1671→1683边（+12）

**新增未解问题（3条）：**
- Q-trkb-01（高优先）：TrkB.T1在体内 dominant negative vs 独立Rho信号的功能平衡——细胞类型和发育阶段依赖性如何分布
- Q-trkb-02（中优先）：人类PNN-PTPσ-TrkB轴与认知老化的关系——是否部分解释成年认知灵活性下降
- Q-trkb-03（中优先）：TrkB跨膜域不同抗抑郁药的差异性变构构象——是否产生不同的下游效应器激活模式

---

## 2026-09-11（#141 · 皮层记忆印迹的诞生：当"沉默"走向"成熟"）

**新建页面（1页）**：
- `concepts/engram-systems-consolidation.md`（新建）— 印迹细胞的系统巩固专页：双印迹并行成熟模型（Kitamura 2017）；皮层沉默印迹→成熟的机制；电路重组（Refaeli 2023，CA1→ACC↑，ACC→CA1↓，EC/PVT↑）；病理性沉默印迹与 AD（Roy 2016）；系统性再巩固的新印迹（Lei 2025）；status=emerging（主要证据来自小鼠），confidence=medium

**修订页面（2页）**：
- `concepts/engram-cells.md`（rev6→rev7）— 当前理解新增"皮层印迹：并行成熟而非顺序迁移"段落（Kitamura 2017 双印迹框架；Refaeli 2023 电路重组）；related +3（engram-systems-consolidation, complementary-learning-systems, adult-neurogenesis）；opens_questions +2（Q-engram-cortical-silent-mechanism, Q-engram-sct-vs-mtt）；connections +3条；key_sources +3（PMID:28386011, 37586373, 29970909）；dimensions 新增 whole-brain-network
- `concepts/memory-consolidation.md`（rev9→rev10）— related +3（engram-systems-consolidation, prefrontal-cortex, anterior-cingulate-cortex）；key_sources +3（PMID:28386011, 37586373, 15685217）；source_articles +1；修订历史 +1行

**图谱更新**：+1节点（engram-systems-consolidation）；+8条新边（engram-systems-consolidation→engram-cells/memory-consolidation/complementary-learning-systems/hippocampal-circuit/prefrontal-cortex/sharp-wave-ripples/adult-neurogenesis/memory-reconsolidation）；总计293节点、1671边

**矛盾登记**：无新矛盾。Kitamura 2017"皮层印迹在学习当天形成"与既有"记忆从海马漂移到皮层"的描述性说法有张力，但这是模型精细化而非真实矛盾（两者描述的不同层面）；未触发矛盾协议。

**新增悬空引用**：Q-engram-cortical-silent-mechanism 依赖 pv-interneurons（已有页面 ✓）；Q-human-cortical-engram 提及 Quiroga 2005 概念细胞（无专页，后续可建 concept-cells.md）

---

## 2026-09-10（#140 · 海马给新皮层写的信：互补学习系统与尖波涟漪驱动的记忆系统巩固）

**新建页面（0页）**：今日无新建页面；所有概念在既有页面中处理。

**修订页面（3页）**：
- `concepts/complementary-learning-systems.md`（rev1→rev2）— **重大扩充**：新增 SO-spindle-SWR 三重协奏详细机制（Born & Wilhelm 2011）；新增清醒 SWR 主动记忆标记机制（Yang et al. 2023, PMID:37987008, R=0.86 睡眠重播预测）；新增 PFC 涟漪顶-下门控（Shin & Jadhav 2023, PMID:38168420）；新增 SHY vs 主动巩固调和框架（Tononi & Cirelli 2014）；证据表 +5行；related +5个（prefrontal-cortex、sleep-spindles、adult-neurogenesis、shy-hypothesis、so-spindle-swr-coupling）；key_sources +8个；opens_questions +3（Q-cls-cortical-gating-01/Q-cls-interleaved-replay-01/Q-cls-human-01）；纠正 PMID:7704110→PMID:7624455（McClelland 1995 正确 PMID）
- `concepts/sharp-wave-ripples.md`（rev6→rev7）— 新增"皮层涟漪顶-下抑制与门控"新发现节（Shin & Jadhav 2023, PMID:38168420）：PFC涟漪独立时抑制海马；同步时选择性增强；时序：纺锤波→PFC涟漪→SWR；key_sources +2（PMID:38168420, PMID:37987008）
- `concepts/memory-consolidation.md`（rev8→rev9）— 证据表 +3行（Yang 2023 R=0.86直接预测 PMID:37987008；PFC涟漪顶-下门控 PMID:38168420；更新清醒SWR标记条目区分两个Yang来源）；key_sources +2

**图谱更新**：+5条新边（complementary-learning-systems→prefrontal-cortex；complementary-learning-systems→sleep-spindles；complementary-learning-systems→adult-neurogenesis；complementary-learning-systems→shy-hypothesis；prefrontal-cortex→sharp-wave-ripples(regulates)）；总计292节点、1663边

**矛盾登记**：无新矛盾（PFC涟漪门控是新发现但不冲突既有主张；SHY vs 主动巩固调和框架在既有memory-consolidation页面已登记为open，今日新信息互补而非矛盾）

**悬空引用**：无新悬空引用；所有新边的目标节点均已存在

---

## 2026-09-08（#138 · 当大脑的"学习窗口"再次开启：成年关键期重开的四条分子路径）

**新建页面（2页）**：
- `concepts/critical-period-reopening.md`（emerging/medium-high）— 成年关键期重开的四条路径：① PNN 降解（ChABC → PTPσ 去激活 → TRKB 重磷酸化）；② Lynx1 KO/nAChR 激动（胆碱能去制动）；③ HDAC 抑制（组蛋白乙酰化恢复）；④ 黑暗饲养/感觉剥夺（E/I 再平衡）；PTPσ–TRKB 统一下游节点假说（Lesnikova 2021）；弱视治疗前景；SynGAP1 成年干预可能性（Q-syngap1-02）
- `concepts/lynx1.md`（established/high）— 内源性 nAChR 抑制蛋白，关键期结束后视觉皮层上调；结构类似蛇毒三指毒素；Lynx1 KO 成年恢复幼年型 ODP；弱视自发恢复；physostigmine 药理模拟；nAChR 必要性验证

**修订页面（2页）**：
- `concepts/critical-period.md`（rev5）— related 新增 critical-period-reopening、lynx1；连接节新增两条说明；修订历史追加；source_articles 新增 2026-09-08
- `concepts/perineuronal-nets.md`（rev3）— related 新增 critical-period-reopening、lynx1；source_articles 新增 2026-09-08

**矛盾登记**：无（多路径重开的证据高度一致；PTPσ–TRKB 统一下游假说目前仅覆盖 ChABC 和 fluoxetine 两条路径，Lynx1/HDAC 路径是否汇聚尚无数据，标注为 emerging）

**解决悬空引用**：`critical-period-reopening` 和 `lynx1` 从 critical-period.md 的悬空 related 变为实体页面

**知识图谱**：291 节点，1654 边（新增 2 节点，13 条边）

---

## 2026-09-07（#137 · 突触的"制动蛋白"：SynGAP1 如何通过解除 Ras-ERK 制动来执行 LTP）

**新建页面（2页）**：
- `concepts/syngap1.md`（established/high）— SynGAP1：PSD第三丰富蛋白，通过PDZ2与PSD-95结合；双向GAP制动器（Ras-GAP抑制AMPAR插入、Rap1-GAP调控AMPAR移除）；LTP时CaMKII磷酸化→弥散→Ras-ERK解制动→AMPAR插入；弥散幅度与LTP强度正相关；SYNGAP1+/-导致静默突触提前耗尽、LTP遮蔽、关键期提前关闭
- `diseases/syngap1-related-disorder.md`（established/high）— SRD（SYNGAP1相关神经发育障碍）：de novo SYNGAP1截短突变→单倍剂量不足；约1%非综合征性ID；>70%癫痫、~50% ASD；首次人类关联（Hamdan NEJM 2009）；治疗前沿（AAV基因补充、ASO）

**修订页面（3页）**：
- `concepts/ltp.md`（rev15）— related 新增 syngap1、syngap1-related-disorder；SynGAP1弥散明确为LTP表达必要解制动步骤；SYNGAP1+/-的LTP occlusion补充
- `concepts/psd-95.md`（rev2）— related 中 syngap→syngap1 slug 更新；related 新增 syngap1-related-disorder；SynGAP1-PDZ2相互作用细节明确
- `concepts/silent-synapse.md`（rev2）— related 新增 syngap1、syngap1-related-disorder；dimensions 新增 disease；SynGAP1是防止静默突触自发开锁的制动器明确写入

**矛盾登记**：无新矛盾（SynGAP1机制高度一致，各来源无分歧）

**解决悬空引用**：
- `syngap1` ✅ 已建立（被 psd-95、ltp 等引用）
- `syngap1-related-disorder` ✅ 已建立（填补疾病维度）

**新增未解问题**：
- Q-syngap1-01：不同 SynGAP1 亚型（α1 vs α2 vs β/γ）在海马 vs 前额叶的功能差异？
- Q-syngap1-02：成年期基因治疗的治疗窗口上限在哪里？

**图谱**：289 节点 / 1641 条边（+2节点 +13条边）

---

## 2026-09-06（#136 · PSD-95：兴奋性突触的主控分子）

**新建页面（2页）**：
- `concepts/psd-95.md`（established/high）— PSD-95（DLG4）：兴奋性突触最丰富的支架蛋白（~300分子/突触）；PDZ1/2锚定NMDAR-GluN2B；经TARP（Stargazin）间接稳定AMPAR；突触槽位（synaptic slot）的物理基础；SynGAP竞争PDZ槽位的LTP机制；棕榈酰化动态循环（ZDHHC2活动依赖）；液液相变（SynGAP/PSD-95凝聚体）；PSD-95/PSD-93竞争设定关键期时间轴；填补 silent-synapse / postsynaptic-density 悬空引用
- `concepts/tarp-auxiliary-subunit.md`（established/high）— TARP（跨膜 AMPAR 调控蛋白）：AMPA受体辅助亚基；Stargazin（γ-2）C末端(-TTPV)直接结合PSD-95 PDZ1/2（Schnell 2002 PNAS）；AMPAR-TARP-PSD95三元复合物是突触AMPAR锚定的必要中介；调控AMPAR门控动力学和表面运输；填补 ampa-receptor 悬空引用

**修订页面（2页）**：
- `concepts/ltp.md`（rev14）— related 新增 psd-95、tarp-auxiliary-subunit、silent-synapse；source_articles 新增 2026-09-06-psd95-synaptic-scaffold；PSD-95槽位机制是LTP物理底层的明确说明
- `concepts/postsynaptic-density.md`（rev2）— related 新增 psd-95、tarp-auxiliary-subunit、silent-synapse；source_articles 新增 2026-09-06-psd95-synaptic-scaffold；PSD-95 专页链接已激活

**矛盾登记**：无新矛盾

**解决悬空引用**：
- `psd-95` ✅ 已建立（被 silent-synapse、postsynaptic-density 引用）
- `tarp-auxiliary-subunit` ✅ 已建立（被 ampa-receptor 引用）

**新增未解问题**：
- Q-psd95-01：LTP 时 PSD-95 分子绝对数量是否真的增加，还是只是槽位占用率变化？
- Q-psd95-02：PSD-95 棕榈酰化-去棕榈酰化周期是否在睡眠期参与突触强度全局下调（SHY 假说）？

**图谱**：287 节点 / 1628 条边（+2节点 +22条边）

---

## 2026-09-05（#119 · ODP 第二阶段机制之争：开放眼的胜利）

**新建页面（2页）**：
- `concepts/silent-synapse.md`（established/high）— 沉默突触（AMPAR-silent）：关键期 Hebbian LTP 的分子底物；PSD-95 依赖的开锁机制；关键期关闭的底物耗竭理论；填补悬空引用
- `concepts/critical-period-plasticity.md`（established/high）— 关键期可塑性：ODP 两阶段分子机制综合（TNFα 稳态许可 + Hebbian LTP 精修）；与 [[critical-period]] 区分（本页聚焦突触机制）；填补悬空引用（被 metaplasticity 引用）

**修订页面（1页）**：
- `concepts/ocular-dominance-columns.md`（rev2）— ODP 第二阶段机制从"两机制并列"更新为"稳态许可在先、Hebbian 精修在后"的整合框架；新增 TNFα KO（PMID:18549780）、幼年/成年分工（PMID:22232689）、丘脑 CaV3.1（PMID:41240337）；关键证据表扩充 3 行；related 新增 critical-period-plasticity、synaptic-scaling、silent-synapse

**矛盾更新**：
- C-2026-08-15-01（ODP Stage 2 机制分歧）**→ 新增整合模型证据**：Kaneko 2008（TNFα）、Ranson 2012（幼年/成年差异）、Sugimura 2015（TNFα→LTP 桥接）、Echavarri-Leet 2025（CaV3.1 成年替代机制）。两机制从"互相排斥"修订为"时序协同（稳态先、Hebbian 后）"；裁决从 open 更新为 open（部分整合），直接实验（同一动物同时测量两种指标）仍缺失。

**悬空引用（新增待补）**：
- `psd-95`（silent-synapse 和 critical-period-plasticity 页中引用，暂无独立页 → 下次填补）

**解决悬空引用**：
- `critical-period-plasticity` ✅ 已建立（被 metaplasticity 引用）

**图谱**：285 节点 / 1606 条边（+2节点 +15条边）

---

## 2026-09-04（#135 · 平衡传播与皮层两相学习）

**新建页面（2页）**：
- `concepts/equilibrium-propagation.md`（emerging/medium）— Scellier & Bengio 2017 框架：两相活动差精确等于代价梯度；STDP 等价；2025 年隐式非平衡记忆解决两相协调问题
- `concepts/hopfield-network.md`（established/high）— Hopfield 1982 能量极小化联想记忆；诺贝尔物理学奖 2024；Transformer attention = 连续 Hopfield 检索

**修订页面（3页）**：
- `concepts/credit-assignment.md`（rev2）— 新增 EP 作为空间信用分配的能量极小化路径（与 PC-Learning 并列）；related 新增 equilibrium-propagation、hopfield-network
- `concepts/pc-learning.md`（rev2）— 新增 EP 与 PC-Learning 的并行关系说明（能量语言 vs 误差语言）；related 新增 equilibrium-propagation、hopfield-network
- `concepts/cortical-slow-oscillation.md`（rev4）— 新增 EP 框架视角（UP/DOWN 态两态切换 = EP 两相候选，假说）；新增信息最大化视角（全局 SO → 均一下调，局部 SWR → 选择性强化）

**矛盾登记**：无

**悬空引用（新增待补）**：
- `contrastive-hebbian-learning`（EP 页中引用，暂无独立页）
- `associative-memory`（Hopfield 页中引用，暂无独立页）
- `energy-based-models`（EP 和 Hopfield 页中引用，暂无独立页）

**图谱**：283 节点 / 1591 条边（+2节点 +12条边）

---

## 2026-09-03（文章 #134 — 大脑的反向传播幻觉：预测编码如何近似梯度下降 / Q-fep-02 部分回答）

**新建页面（2 页）**：
- `wiki/concepts/credit-assignment.md`：信用分配问题——双维度解析（空间维度：PC-Learning 层级误差传播；时间维度：三因素规则 + 资格迹）；顶树突物理分区作为解剖底层；status=established, confidence=high
- `wiki/concepts/pc-learning.md`：预测编码学习——Whittington & Bogacz 2017 数学等价证明（局部 Hebbian ↔ 反向传播梯度）；Max et al. 2026 皮层实现（L2/3=误差单元，L5=表征单元）；实验预测（扰动误差神经元损害 > 表征神经元）；status=emerging, confidence=medium

**修订页面（1 页）**：
- `wiki/theories/predictive-coding.md`（rev9→rev10）：新增"PC-Learning = 反向传播的生物近似"段落（Whittington & Bogacz 2017 证明 + Max et al. 2026 皮层实现 + Brucklacher 2023 计算验证）；key_sources 新增 3 篇；related_learning 新增 pc-learning, credit-assignment；source_articles 新增 #134

**图谱更新**：+2 节点（credit-assignment, pc-learning），+13 条边；281 节点，1579 条边

**矛盾登记 / 裁决**：无新矛盾

**未解问题进展**：
- Q-fep-02（"VAE 等价与生物反向传播"）状态更新：权重更新维度已由 PC-Learning 等价定理部分回答；剩余开放问题 A（时间维度信用分配与 PC-Learning 协同）、B（非 IID 感觉流下推断稳定性）

**悬空引用**：
- `cortical-layers → pc-learning`（在 pc-learning.md 的 prerequisites 中引用）：cortical-layers 节点已存在 ✅
- `backpropagating-action-potential → pc-learning`：已有 bAP 节点 ✅

---

## 2026-09-02（文章 #133 — 小脑作为主动推断引擎：本体感觉先验、精度校准 / Q-fep-01 追踪）

**新建页面（1 页）**：
- `wiki/concepts/proprioceptive-prediction.md`：本体感觉预测——主动推断框架中运动命令重定义为本体感觉先验（均值+精度）；精度两分量（空间分量=高尔基细胞门控，时间分量=DCN 调节）；脊髓反射弧执行层；只需一个前向模型；DCN 损坏→时间精度失调→意向性震颤；status=emerging, confidence=medium

**修订页面（3 页）**：
- `wiki/concepts/forward-model.md`（rev1→rev2）：新增主动推断视角（逆向模型被脊髓代替，只需前向模型，Parr et al. 2025）；新增 Tanaka 2019 直接神经证据（R²=0.89）；登记新矛盾 C-2026-09-02-01（内部模型 vs 前馈映射）；扩展 dimensions、related、key_sources
- `wiki/systems/cerebellum.md`（rev3→rev4）：新增主动推断视角段落（DCN 时间精度 + 高尔基细胞空间精度）；颗粒细胞时间基础集（Nguyen & Person 2025）；更新 key_sources（+5）、related（+3）、opens_questions
- `wiki/theories/active-inference.md`（rev1→rev2）：深化小脑精度先验角色（DCN 时间 + 高尔基细胞空间）；主动推断单前向模型优势；Friston & Herreros 2016 眼睑模型；key_sources、related 更新

**图谱更新**：+1 节点（proprioceptive-prediction），+6 条边；279 节点，1566 条边

**矛盾登记 / 裁决**：
- 登记矛盾 C-2026-09-02-01（open）：小脑实现"显式内部模型"（Wolpert-Kawato + 主动推断框架）vs "模型无关前馈映射"（Nguyen & Person 2025）；性质=计算级理论分歧；需运动泛化/新奇学习实验裁决
- Q-fep-01（部分回答）：问题 A 有理论框架支持（神经机制待验证）；问题 B/C 仍为 open

**悬空引用**：新页 proprioceptive-prediction 引用 spinal-cord-reflex（尚无独立 wiki 页，待补）

---

## 2026-09-01（文章 #132 — 变分自由能与主动推断：大脑如何用一个原则统一感知、行动与学习）

**新建页面（2 页）**：
- `wiki/theories/free-energy-principle.md`：自由能原理（FEP）——变分自由能是感觉惊喜的可计算上界；最小化 F 的两条路径（感知=更新信念，行动=改变感觉输入）；层级生成模型（广义运动坐标，时间尺度分离）；精度加权；学习=长期模型参数更新；VAE 数学等价；status=mainstream, confidence=medium
- `wiki/theories/active-inference.md`：主动推断——行动理解为实现本体感觉预测而非运动命令输出；感知与行动统一于同一优化目标；期望自由能最小化推导目标导向行为；与小脑前向模型的整合（Q-fep-01 未解）；status=emerging, confidence=medium

**修订页面（3 页）**：
- `wiki/theories/predictive-coding.md`（rev8→rev9）：新增"动态预测编码（Jiang & Rao 2024）"段落（时间层级扩展，低层→快时间尺度，高层→慢时间尺度，自然视频训练涌现类 V1 RFs）；新增"自由能原理数学基础"段落；related 新增 free-energy-principle；连接节新增 FEP/主动推断条目；key_sources 新增 PMID:19528002, 38330098, 29497060；opens_questions 新增 Q-fep-01, Q-fep-02
- `wiki/concepts/canonical-microcircuit.md`（rev1→rev2）：related 新增 free-energy-principle, active-inference；确认 FEP/主动推断与规范微回路的关联
- `wiki/index.md`：新增 free-energy-principle 和 active-inference 条目；更新 predictive-coding 条目（rev9）；更新页面总数（259页）和图谱统计（278节点，1560边）

**图谱更新**：+2 节点（free-energy-principle, active-inference），+14 条边；278 节点，1560 条边

**矛盾登记 / 裁决**：无新矛盾。Q-fep-01（主动推断与小脑前向模型整合）和 Q-fep-02（VAE等价与生物反向传播）作为新未解问题登记。

---

## 2026-08-31（文章 #131 — 振荡路由：γ 相干性如何让大脑把注意力变成专用通信线路）

**新建页面（1 页）**：
- `wiki/concepts/communication-through-coherence.md`：Communication Through Coherence（CTC）——振荡相位对齐创造通信窗口；γ（30–90 Hz）前馈感觉内容，α/β（8–30 Hz）反馈预测控制；FEF-V4 γ coherence 升高 26–37%（Gregoriou 2009 开放全文）；频段-方向皮层层级对应（Bastos 2015）；status=mainstream, confidence=medium（框架有争议）

**修订页面（3 页）**：
- `wiki/concepts/gamma-oscillations.md`（rev4→rev5）：新增 FEF-V4 注意 γ 相干性节（Gregoriou 2009, 2012 两篇开放全文数据）；visual FEF 神经元解离；related 新增 communication-through-coherence, dorsal-attention-network；key_sources 新增 PMID:19478185, PMID:22325208
- `wiki/concepts/dorsal-attention-network.md`（rev2→rev3）：新增 FEF γ 通信机制节（Gregoriou 2009, 2012）；整合 CTC 框架；related 新增 gamma-oscillations, communication-through-coherence, dlpfc-rule-encoding
- `wiki/concepts/alpha-oscillations.md`（rev1→rev2）：新增 α 在 CTC 框架中的角色节；Q-alpha-01 部分进展（CTC 框架性解释）；related 新增 communication-through-coherence

**图谱更新**：+1 节点（communication-through-coherence），+9 条边；275 节点，1544 条边

**矛盾登记 / 裁决**：无新矛盾（CTC 的 Q-ctc-01 γ coherence 因果性争议已在 opens_questions 中记录，相关议题 Ray & Maunsell 批评尚未达到裁决阶段）

**新增未解问题**：Q-ctc-01（高优先级，γ coherence 是否因果机制）、Q-ctc-02（高优先级，不同任务中 γ 功能一致性）、Q-ctc-03（中优先级，人类 FEF-V4 CTC 验证）；Q-alpha-01 获得部分进展

---

## 2026-08-30（文章 #130 — 前额叶皮层的高维秘密：混合选择性如何让 DLPFC 同时编码无数种规则）

**新建页面（3 页）**：
- `wiki/concepts/mixed-selectivity.md`：混合选择性——DLPFC 神经元同时对多任务变量非线性组合响应；非线性 NMS 是高维表征的来源；维度坍塌与行为错误的关联；status=mainstream, confidence=high
- `wiki/concepts/dlpfc-rule-encoding.md`：DLPFC 规则编码——分布式高维动态编码；额叶层级顶端；Miller & Cohen 偏置信号框架；Stokes 动态编码；人类 24% 规则选择性神经元；status=mainstream, confidence=high
- `wiki/concepts/frontal-hierarchy.md`：额叶认知控制层级——前后轴层级（情境→维度→特征→反应）；BA46 是情境级顶端；Badre 2009 病变双解离证据；离散层级 vs 连续梯度争议；status=mainstream, confidence=medium

**修订页面（3 页）**：
- `wiki/systems/prefrontal-cortex.md`（rev4→rev5）：新增 dlPFC 规则编码与混合选择性子节（偏置信号框架、混合选择性、动态编码、额叶层级、人类证据、维度坍塌）；related 新增 4 个节点；key_sources 新增 4 个 PMID
- `wiki/systems/anterior-cingulate-cortex.md`（rev1→rev2）：related 新增 dlpfc-rule-encoding/frontal-hierarchy/mixed-selectivity；补充 dACC→DLPFC 调度连接说明
- `wiki/concepts/working-memory.md`（rev8→rev9）：key_sources 新增 PMID:23562541（Stokes 2013 动态编码）；Q-wm-active-vs-silent 新增群体层面低活动稳态证据；related 新增 mixed-selectivity, dlpfc-rule-encoding

**图谱更新**：+3 节点（mixed-selectivity, dlpfc-rule-encoding, frontal-hierarchy），+13 条边；274 节点，1535 条边

**矛盾登记 / 裁决**：无新矛盾（NMS 因果性争议已在 Q-ms-02 中记录，暂不达到登记 contested_claim 标准）

**新增未解问题**：Q-ms-01（高优先级）、Q-ms-02（高优先级）、Q-ms-03（中优先级）、Q-fh-01（高优先级）、Q-fh-02（中优先级）

---

## 2026-08-29（文章 #129 — 大脑的成本-效益计算器：前扣带回皮层如何决定"值不值得控制自己"）

**新建页面（1 页）**：
- `wiki/systems/anterior-cingulate-cortex.md`：前扣带回皮层——认知控制调度中心；涵盖冲突监测假说（Botvinick 2001）、ERN-多巴胺理论（Holroyd & Coles 2002）、行动价值学习（Kennerley 2006, Rudebeck 2008）、反事实奖励编码（Hayden 2009）、EVC 框架（Shenhav 2013）、自下而上单细胞视角（Heilbronner & Hayden 2016）；status=established, confidence=high

**修订页面（3 页）**：
- `wiki/concepts/dopamine-reward-prediction-error.md`（rev10→rev11）：related 新增 anterior-cingulate-cortex；补充 DA-RPE 通过 ERN 机制（D2 去抑制→ACC 激活）产生系统级行为调整信号的说明
- `wiki/concepts/three-factor-learning-rule.md`（rev2→rev3）：related 新增 anterior-cingulate-cortex；补充突触层面 DA（三因素规则）与系统层面 DA（dACC ERN）共享多巴胺通路的架构
- `wiki/concepts/working-memory.md`（rev7→rev8）：related 新增 anterior-cingulate-cortex；补充 dACC 通过 EVC 调度 DLPFC 工作记忆激活的元层控制关系

**图谱更新**：+1 节点（anterior-cingulate-cortex），+8 条边；271 节点，1522 条边

**矛盾登记 / 裁决**：无新矛盾；无矛盾裁决

**新增未解问题**：Q-acc-evc-vs-conflict（高优先级）、Q-acc-subregion-boundary（高优先级）、Q-acc-ern-dopamine-causal（中优先级）

---

## 2026-08-28（文章 #128 — 信用的时间归属：突触标记、资格迹与三因素学习规则如何让大脑实现强化学习）

**新建页面（1 页）**：
- `wiki/concepts/eligibility-trace.md`：资格迹——突触在赫布协同激发后进入的亚稳态临时标记；三因素规则中间变量（e_ij → w_ij × M_3rd）；纹状体分子机制（PDE10A/PKA 时钟，Yagishita 2014，PMID:25258080）；皮层机制（NE/5-HT 门控，He et al. 2015）；海马 BTSP（±3-4s 时窗，Bittner 2017，PMID:28883072）；解决时间信用分配问题；status=mainstream, confidence=high

**修订页面（3 页）**：
- `wiki/concepts/three-factor-learning-rule.md`（rev1→rev2）：**重大修订**——引入资格迹数学框架（Gerstner 2018，PMID:30108488）；更新分子机制为 PDE10A 时钟（Yagishita 2014）；整合 BTSP 为极端案例；新增与 eligibility-trace / stdp / btsp / backpropagating-action-potential 的连接；status 从 mainstream → established；新增 5 条关键证据行
- `wiki/concepts/btsp.md`（rev2→rev3）：新增与 three-factor-learning-rule / eligibility-trace 的连接；明确 BTSP 是三因素规则极端案例（±3-4s 资格迹）
- `wiki/concepts/stdp.md`（rev2→rev3）：related 新增 eligibility-trace；补充 STDP → 资格迹中间变量关系；皮层 STDP 单独无持久性实验说明

**矛盾登记 / 裁决**：无新矛盾；无矛盾裁决

**新增未解问题**：无新问题（三因素规则的主要未解问题已在 Q-three-factor-time-window / Q-stc-molecular-tag 中覆盖）

**图谱更新**：+1节点（eligibility-trace），+10条边；三因素规则状态升级 mainstream→established；总节点 270，总边 1514

---

## 2026-08-27（文章 #127 — 可塑性的守门人：BCM 规则与元可塑性如何防止突触失控）

**新建页面（2 页）**：
- `wiki/concepts/metaplasticity.md`：元可塑性——"可塑性的可塑性"；Abraham & Bear 1996 命名；多机制并行（NMDA 亚基切换/Ih/CaM-RC3/mGluR）；异突触元可塑性与星形胶质细胞 ATP/腺苷信号（Hulme 2014）；AD 发育性元可塑性失调（Megill 2015）；AI 灾难性遗忘对照（Jedlicka 2022）；status=established, confidence=high
- `wiki/concepts/bcm-rule.md`：BCM 规则（Bienenstock, Cooper, Munro 1982）——滑动修改阈值 θ_m；Δw ∝ φ(y,θ_m)·x；视觉皮层验证（Kirkwood & Bear 1994, Clothiaux 1991）；NMDA 亚基切换与 Ih 的分子实现；与 STDP 的互补关系；status=mainstream, confidence=high

**修订页面（2 页）**：
- `wiki/concepts/hebbian-learning.md`（rev5→rev6）：新增 metaplasticity 和 bcm-rule 连接；Q-hebbian-stability 更新（补充元可塑性为第二解决方案）；related 和 source_articles 扩展
- `wiki/concepts/ltp.md`（rev13→rev14 frontmatter only）：related 新增 metaplasticity, bcm-rule；source_articles 新增本文

**新增未解问题**：
- Q-meta-01（高优先）：θ_m 滑动的时间常数在不同实验系统中的差异
- Q-meta-02（高优先）：Ih 机制在清醒行为动物体内是否真实承担 θ_m 调节
- Q-meta-03（中优先）：异突触元可塑性传播范围和选择性
- Q-bcm-01（高优先）：θ_m 确切时间常数及跨脑区差异
- Q-bcm-02（中优先）：如何体内直接测量 θ_m 变化

**图谱更新**：+2节点（metaplasticity, bcm-rule），+12条边；总节点269，总边1504

---

## 2026-08-26（文章 #124 — 逆流而上：回传动作电位如何让树突棘"知道"何时该加强）

**新建页面（2 页）**：
- `wiki/neurons/backpropagating-action-potential.md`：回传动作电位（bAP）——填补 stdp.md 悬空引用；Stuart & Sakmann 1994 发现；A 型 K+ 通道符合门（Hoffman 1997）；bAP+EPSP 超线性 Ca²⁺（Magee & Johnston 1997）；位置依赖 STDP 规则（Letzkus 2006）；200 Hz 爆发与树突 Ca²⁺ 棘波（Kampa 2006）；PFC L5 亚型多样性（Schamiloglu 2025）；NaV1.2/SCN2A 与 ASD（Spratt 2019）；status=established, confidence=high
- `wiki/concepts/a-type-potassium-channel.md`：A 型钾通道（I_A）——bAP 的可调节闸门；Kv4.2 分子身份；密度梯度（远端 5–6 倍于胞体）；EPSP 引起的失活开放 bAP 入侵通道；磷酸化/神经调质调控；status=established, confidence=high

**修订页面（2 页）**：
- `wiki/concepts/stdp.md`（rev1→rev2）：新增 bAP 机制详解（I_A 密度梯度、位置依赖规则、细胞多样性）；related 新增 a-type-potassium-channel
- `wiki/neurons/dendritic-computation.md`（rev4→rev5）：新增 bAP 作为树突计算前提条件段落；新增 Schamiloglu 2025 PFC L5 亚型多样性数据；related 新增 backpropagating-action-potential, a-type-potassium-channel

**悬空引用解决**：
- `backpropagating-action-potential`（stdp.md related 中已引用，今日建页）

**新增未解问题**：
- Q-bap-01（高优先）：清醒行为动物中 bAP 体内传播效果与频率
- Q-bap-02（中优先）：CA1 bAP 强/弱二分化的分子决定因素

**图谱更新**：+2节点（backpropagating-action-potential, a-type-potassium-channel），+12条边；总节点267，总边1492

---

## 2026-08-25（文章 #123 — 突触的时间守门人：STDP 如何用毫秒差异决定学习的方向）

**新建页面（1 页）**：
- `wiki/concepts/stdp.md`：脉冲时序依赖可塑性（STDP）——赫布规则的毫秒级精化；经典学习窗口（Markram 1997/Bi & Poo 1998）；NMDA 受体符合探测+bAP 超线性 Ca²⁺ 机制；AMPA 受体时间精度调控（Holbro 2010）；生理钙浓度挑战（Inglebert & Debanne 2021）；短期因果 vs 长期同步性张力（Anisimova 2022）；神经调质第三因素（Foncelle 2018）；人类 ccPAS 证据（Hernandez-Pavon 2022）；status=mainstream, confidence=medium；填补 hebbian-learning 悬空引用 [[stdp]]

**修订页面（2 页）**：
- `wiki/concepts/ltp.md`（rev12→rev13）：related 新增 stdp；连接新增 [[stdp]] 说明 STDP 是 LTP 的时序精化形式；source_articles 新增
- `wiki/concepts/hebbian-learning.md`（rev4→rev5）：[[stdp]] 从"待建页面"升级为已建立连接；补充 STDP 分子机制描述；source_articles 新增

**矛盾登记（1 条新登记）**：
- C-2026-08-25-01（open）：STDP 的"因果性"（Bi & Poo 1998 经典窗口——前先后随→LTP，后先前随→LTD，短期内方向敏感）vs"同步性"（Anisimova et al. 2022——3天后无论方向，只要同步均→LTP）；nature=真实分歧（短期 vs 长期时间尺度，以及生理钙浓度差异）；status=open

**新增未解问题**：
- Q-stdp-01（高优先）：体内生理 Ca²⁺ 下，STDP 规则形态——是否需要 θ-burst 才能诱导 LTP？需体内单突触分辨率验证
- Q-stdp-02（高优先）：短期因果 vs 长期同步性的整合——哪个描述真正稳定的长期记忆？
- Q-stdp-03（中优先）：不同脑区 STDP 规则差异（皮质/海马/小脑）的分子决定因素

**图谱更新**：+1节点（stdp），+9条边；总节点265，总边1480

---

## 2026-08-23（文章 #121 — 从声波到意义：大脑如何用预测编码完成语音理解）

**新建页面（3 页）**：
- `wiki/concepts/wernicke-area.md`（填补悬空引用）：韦尼克区——现代修正观：pSTG/BA22 是音韵形式提取/缓冲区，非理解中枢；损伤主要产生传导性失语；真正理解依赖双侧分布网络（MTG/STS/ATL）；整合 Binder 2017 和 DeWitt & Rauschecker 2013 两模块说；status=contested（经典解读 vs 现代修正存在实质分歧）
- `wiki/concepts/planum-temporale.md`（填补悬空引用）：颞平面——外侧裂深处、HG 后方；65% 人类左>右（Geschwind & Levitsky 1968）；时序声学分析；失聪者/音乐家中也有左侧化；左 PT 大小与语言左侧化相关但不确定；status=mainstream
- `wiki/concepts/speech-comprehension-prediction.md`：语音理解的预测编码——IFG→STG/STS 自上而下预测回路；STG 编码预测误差；正确理解=误差信号减弱；Sohoglu & Davis 2012/2016；Blank & Davis 2016/2018；Cope & Davis 2023 运动皮层预测实例化；status=mainstream

**修订页面（2 页）**：
- `wiki/systems/stg-phoneme-processing.md`（rev1→rev2）：新增"语境修复与预测编码"完整段落；新增5条预测编码证据行（Sohoglu & Davis 2012/2016；Blank & Davis 2016/2018）；related 新增 speech-comprehension-prediction、wernicke-area；连接新增2个节点；key_sources 新增3个PMID
- `wiki/circuits/ventral-language-stream.md`（rev2→rev3）：新增"预测回路（IFG→STG/STS 反馈）"段落；整合 Sohoglu & Davis 2012 和 Cope & Davis 2023 证据；key_sources 新增2个PMID

**矛盾登记（0条新登记）**：今日证据与既有 wiki 无冲突，均为补充和加深。

**新增未解问题**：
- Q-wernicke-01（中优先）：纯粹 pSTG/BA22 局灶性损伤（不累及 MTG/白质）的理解缺陷大小，缺乏系统定量 VLSM 研究
- Q-pt-01（中优先）：PT 左侧化是语言习得的**结果**还是先天**原因**？新生儿影像支持先天假说，但习得塑形程度不明

**新增悬空引用（待填补）**：
- `language-lateralization`（speech-comprehension-prediction 提及语言左半球优势；待建专页）
- `analysis-by-synthesis`（运动系统参与感知的完整计算框架；Cope & Davis 2023 引出）

**图谱更新**：+3节点（wernicke-area/planum-temporale/speech-comprehension-prediction），+10条边；总节点262，总边1460

---

## 2026-08-22（文章 #120 — 语言习得关键期：感知收窄、统计学习与神经成熟的协同舞蹈）

**新建页面（3 页）**：
- `wiki/concepts/language-critical-period.md`：语言习得关键期——分层敏感期框架（音位0-12月/词义12-30月/形态句法2-5岁/复杂句法5-7岁）；三层驱动机制（统计学习/社会门控/白质成熟）；感知收窄时间线与预测力；key_sources含PMID:15496861/17181708/22347185/41886982/8943209
- `wiki/concepts/statistical-learning.md`：统计学习——转移概率学习/分布学习/规则提取；8月婴儿2分钟学词（Saffran 1996）；新生儿睡眠中统计学习（Teinonen 2009）；社会门控依赖性
- `wiki/concepts/social-gating-language.md`：社会门控假说——真人vs录像零学习对比（Kuhl 2007/2003）；目光接触预测学习；鸣禽发声学习类比；神经机制推测（STS/TPJ/注意/奖励）；status=mainstream（行为证据高，神经机制待确认）

**修订页面（3 页）**：
- `wiki/concepts/phoneme-categorical-perception.md`（rev1→rev2）：新增感知收窄预测力（Kuhl 2004 纵向数据）；新增社会门控依赖性（真人互动必要性）；related新增language-critical-period/statistical-learning/social-gating-language；key_sources新增PMID:15496861/8943209
- `wiki/circuits/dorsal-language-stream.md`（rev2→rev3）：新增Klein 2026行为验证段落（N=120学龄前儿童DTI：4岁断点，句法-白质相关）；related新增language-critical-period；key_sources新增PMID:41886982；source_articles新增#120
- `wiki/systems/language-network.md`（rev4→rev5）：related新增language-critical-period；key_sources新增PMID:22347185；source_articles新增#120

**矛盾登记（0条新登记）**：今日证据与既有wiki无冲突，均为补充和加深。

**新增未解问题（3条）**：
- Q-lcp-01（中优先）：成人L2习得局限主要源于皮层可塑性、L1干扰，还是认知控制主导？
- Q-lcp-02（中优先）：社会门控具体神经回路（注意/奖励/共同注意/感知-动作耦合的相对贡献）
- Q-lcp-03（高优先）：ASD中社会门控功能受损是否是语言延迟的主要神经路径？

**新增悬空引用（待填补）**：
- `autism-language-delay`（social-gating-language引用，ASD中语言延迟的社会门控机制专页待建）
- `gaba-critical-period-closure`（language-critical-period提及GABA调制关闭机制，待专页）

**图谱更新**：+3节点（language-critical-period/statistical-learning/social-gating-language），+约12条边；总节点259，总边约1448（具体见_graph.json）

---

## 2026-08-21（文章 #119 — 语言之弦：弓状束三段式纤维架构如何编织感知与产生之间的神经桥梁）

**新建页面（1 页）**：
- `wiki/diseases/conduction-aphasia.md`：传导性失语症——三特征（理解完整/产出流利/重复受损）；经典解释（AF直接段损伤）vs. 修订观点（Spt皮层损伤）；conduite d'approche在DIVA模型中的解释；key_sources含PMID:15597383/PMID:17431404/PMID:20720112

**修订页面（3 页）**：
- `wiki/concepts/arcuate-fasciculus.md`（rev1→rev2）：**重大修订**——整合Catani 2005三段式架构（直接段/间接后段/间接前段）；Glasser 2008左右AF差异化靶区；Friederici 2012背侧路径I/II发育双分组；Balezeau 2020跨物种进化比较（灵长类听觉原型+人类左侧化p=0.002）；Shekari 2023 AF-音韵/IFOF-语义双解离；Giampiccolo 2022颞叶端争议（登记矛盾C-2026-08-21-01）；新增related:conduction-aphasia,stg-phoneme-processing,speech-production-circuit；新增3个未解问题（Q-af-01/02/03）
- `wiki/circuits/dorsal-language-stream.md`（rev1→rev2）：新增AF三段式架构子节（直接/后间接/前间接段）；新增背侧路径I/II发育时间线；新增进化起源（Balezeau 2020）；新增related:conduction-aphasia,stg-phoneme-processing
- `wiki/systems/language-network.md`：minor——related字段新增conduction-aphasia

**矛盾登记（1 条）**：
- `C-2026-08-21-01`（open）：AF颞叶端边界争议——传统模型（AF终止于pSTG/Wernicke区）vs. Giampiccolo & Duffau 2022（DCS+DTI显示AF延伸至MTG/ITG梭状回/VWFA/基底颞叶语言区）；性质：方法差异+可能的真实解剖变异；影响：失读症解释和术中语言保护

**新增悬空引用（待填补）**：
- `phonological-loop`（被arcuate-fasciculus和dorsal-language-stream引用，Baddeley语音工作记忆专页待建）

**图谱更新**：+1节点（conduction-aphasia），+6边（arcuate-fasciculus→conduction-aphasia:mechanism-of；conduction-aphasia→dorsal-language-stream:is-a；conduction-aphasia→language-network:related；arcuate-fasciculus→stg-phoneme-processing:related；arcuate-fasciculus→speech-production-circuit:related；arcuate-fasciculus→ventral-language-stream:related）；总节点256，总边1436

---

## 2026-08-20（文章 #102 — 声音之刀：颞上回如何将连续声学流切割为音素）

**新建页面（3 页）**：
- `wiki/systems/stg-phoneme-processing.md`：STG四大核心计算（非线性范畴化/说话者归一化/语境修复/时间标记提取）；pSTG/mSTG/aSTG/STS功能梯度；双尺度表征（局部→特征，群体→音素身份）；key_sources含PMID:34672685/PMC:9447996/PMID:24482117
- `wiki/concepts/cortical-speech-entrainment.md`：θ-γ嵌套振荡与言语包络相位同步；非对称采样时间（AST，左快右慢）；MEG和颅内SEEG证据；开放争议：主动预测 vs 被动声学驱动
- `wiki/concepts/phoneme-categorical-perception.md`：范畴感知的非线性神经机制；双尺度（局部特征/群体音素）表征；发育收窄与θ-γ动力学；开放争议：竞争抑制 vs 自上而下词汇反馈的权重

**修订页面（2 页）**：
- `wiki/systems/auditory-cortex.md`（rev4）：新增STG音素计算层小节（pSTG/mSTG/aSTG功能梯度）；新增 related: stg-phoneme-processing, cortical-speech-entrainment
- `wiki/systems/auditory-dual-stream.md`（rev2）：新增 related: stg-phoneme-processing, cortical-speech-entrainment, phoneme-categorical-perception；双流起点现有独立STG音素计算页面支撑

**矛盾登记**：无新矛盾（STG言语特异性与通用听觉计算之争已在stg-phoneme-processing页面标注为opens_questions，未成熟到qualified_claim级别）

**新增悬空引用（待填补）**：
- `efference-copy-speech`（被stg-phoneme-processing引用，尚无独立页面）
- `hemispheric-asymmetry`（被auditory-cortex/auditory-dual-stream引用，尚无独立页面）
- `perceptual-learning`（被phoneme-categorical-perception引用，尚无独立页面）

**图谱更新**：+3节点（stg-phoneme-processing, cortical-speech-entrainment, phoneme-categorical-perception），+13边；总节点255，总边1430

---

## 2026-08-19（文章 #118 — 言语产生：DIVA 模型与前馈/反馈双控制系统）

**新建页面（3 页）**：
- `wiki/systems/speech-production-circuit.md`：六层分布式架构（SMA启动→左IFG音节程序→vPCSA/dPCSA协调→M1执行→pSTG/SMG感觉监控→右vPMC纠偏）；前馈/反馈功能分工；效应副本预测性抑制机制；双前中央言语区（vPCSA发音/dPCSA音调）；口吃/失用症的网络模型
- `wiki/concepts/diva-model.md`：Guenther团队DIVA/GODIVA计算神经框架；七个模型组件与神经对应；前馈（左侧化）/反馈（右侧化）；运动等价（声学目标空间控制）；婴儿咿呀学语习得序列；GODIVA双BG环路（运动vPMC+SMA/计划pIFS+preSMA）
- `wiki/systems/sma-presma.md`：言语启动最早激活节点（pre-SMA峰值-240ms/SMA峰值-170ms）；活动随RT动态伸缩；115人iEEG大样本证据（Bullock 2024, PMID:39807169）；准备协调者而非执行者

**修订页面（1 页）**：
- `wiki/systems/broca-area.md`（rev3）：整合Hickok et al. 2022（PMID:36746488）——言语运动协调中枢重定位至前中央回（vPCSA/dPCSA），而非IFG pars opercularis本身；布罗卡区功能定位为高层语言（句法/词汇/WM）；更新"三成分"框架中"发音成分"的精确神经解剖；新增证据行、连接和来源文章

**矛盾登记**：无新矛盾（Hickok 2022的vPCSA/dPCSA发现与既有broca-area页面的"三成分框架"一致，而非冲突；"发音成分"重定位是精化而非否定）

**新增悬空引用（待填补）**：
- `efference-copy-speech`（效应副本在言语产生中的具体机制，被speech-production-circuit引用）
- `apraxia-of-speech`（言语失用症，被diva-model引用作为疾病窗口）

**图谱更新**：+3节点（speech-production-circuit, diva-model, sma-presma），+12边；总节点252，总边1417

---

## 2026-08-18（文章 #100 — 听觉皮层双流架构：从耳蜗到语言）

**新建页面（1 页）**：
- `wiki/systems/auditory-dual-stream.md`：听觉腹侧流（前颞→VLPFC：声音身份→语义，双侧）vs 背侧流（后颞→Spt→顶叶→Broca/运动：空间/言语运动，强左侧化）；VLSM直接验证（PMID:27956600，138例卒中）；半球谱-时序不对称（左AAC快时序/右AAC慢时序，96例颅内SEEG，PMC:7067489）；背侧流前向模型（Spt作为感觉-运动整合枢纽）；门控流第三通路（新兴，低置信度）

**修订页面（1 页）**：
- `wiki/systems/auditory-cortex.md`（rev3）：新增双流架构摘要节（腹侧/背侧路径概述）；新增半球谱-时序不对称（左快右慢）；related 补充 auditory-dual-stream, hemispheric-asymmetry；key_sources 补充 PMID:17431404/PMC:3483386/PMC:7067489

**图谱更新**：新增 1 节点（auditory-dual-stream），新增 8 条有类型边；图谱总节点 249，总边 1405

**矛盾登记**：无新矛盾（门控流为新兴假说，标注为 emerging/low-confidence，不与既有主流观点冲突）

**新增悬空引用（待填补）**：`hemispheric-asymmetry`（被 auditory-dual-stream 和 auditory-cortex 引用，暂无 wiki 页面）

---

## 2026-08-17（文章 #116 — 背侧视觉流：MT/V5、MST、LIP 的运动感知与行动决策）

**新建页面（4 页）**：
- `wiki/systems/dorsal-visual-stream.md`：背侧流"how"定位（Goodale-Milner 1992 框架）；三级计算层级（MT→MST→LIP）；双子通路（背外侧：MT→MST→VIP；背内侧：V6A→MIP）；动态网络而非固定层级；临床双分离（D.F. vs L.M.）
- `wiki/systems/area-MT-V5.md`：MT/V5 方向选择性（>90%神经元）；速度调谐；双眼视差；光圈问题解决（模式细胞 vs 分量细胞）；三条因果证据（病变/微电刺激/患者L.M.运动失认症）；方向柱组织
- `wiki/systems/mst-medial-superior-temporal.md`：MSTd 大感受野光流调谐（扩张/旋转/平动）；三维航向提取；视觉-前庭双模态整合（64% 神经元前庭调谐）；MSTl vs MSTd 功能分离
- `wiki/systems/lip-lateral-intraparietal.md`：LIP 斜坡活动（ramping activity）；与漂移扩散模型的定量对应；速度-准确性权衡的神经实现；争议：决策节点 vs 眼跳计划区（status=mainstream）

**修订页面（2 页）**：
- `wiki/systems/v1-primary-visual-cortex.md`（rev7）：related 新增 area-MT-V5, dorsal-visual-stream，显式链接 V1 作为背侧流起点
- `wiki/systems/inferior-temporal-cortex.md`（元数据补丁）：related 新增 dorsal-visual-stream, area-MT-V5，完成腹侧-背侧双流对称连接

**图谱更新**：新增 4 节点（dorsal-visual-stream, area-MT-V5, mst-medial-superior-temporal, lip-lateral-intraparietal），新增 11 条有类型边；图谱总节点 248，总边 1397

**新登记的未解问题**：
- Q-dorsal-01（中）：MSTd 的前庭-视觉整合具体机制？冲突时如何权重？
- Q-dorsal-02（高）：LIP 斜坡活动的细胞机制（内部积分 vs 持续外部输入）？
- Q-dorsal-03（中）：两条背侧子通路（背外侧 vs 背内侧）如何协调？

**新登记的矛盾**：
- 无（LIP 争议已在页面内以 status=mainstream 标注，暂未升级为 contested_claims 条目，因争议尚属方法论分歧而非真实分歧）

---

## 2026-08-16（文章 #115 — 腹侧视觉流与颞下皮层不变量物体识别）

**新建页面（4 页）**：
- `wiki/systems/inferior-temporal-cortex.md`：IT 皮层四阶段偏心率框架（Conway 2018）；选择性与不变性平衡、稀疏度守恒（~10%，Rust & DiCarlo 2012）；面孔块层级（ML/MF→AM）；分布式 vs. 模块论调和
- `wiki/systems/v4-visual-area.md`：V4 形状选择性在物体中心坐标系（曲率×角度空间）；真实 vs. 偶然轮廓的区分；平均响应潜伏期 76.6 ms；多维联合调谐（形状×纹理×颜色×深度）
- `wiki/concepts/invariant-object-recognition.md`：不变量识别的核心计算概念；选择性/不变性/稀疏度三角关系；腹侧流各层级实现方式；形状 vs. 纹理统计争论（Q-it-01）
- `wiki/systems/face-patch-system.md`：猕猴 6 个面孔块（PL/ML/MF/AF/AL/AM）；视角特异→视角不变功能梯度（Freiwald & Tsao 2010）；人类 FFA 与猕猴面孔块对应关系（Q-it-03）

**修订页面（1 页）**：
- `wiki/systems/v1-primary-visual-cortex.md`（rev6）：related 新增 v4-visual-area, inferior-temporal-cortex, invariant-object-recognition；source_articles 新增 #115；显式连接 V1 作为腹侧流起点与 V4/IT 层级

**图谱更新**：新增 4 节点（inferior-temporal-cortex, v4-visual-area, invariant-object-recognition, face-patch-system），新增约 16 条有类型边；图谱总节点 244，总边 ~1386

**新登记的未解问题**：
- Q-it-01（高）：腹侧流是否计算全局形状？（Ayzenberg & Behrmann 2022 vs. 经典 IT 研究）
- Q-it-02（中）：反馈连接（PFC→IT）在日常物体识别中的定量贡献
- Q-it-03（高）：人类 IT 皮层面孔识别（FFA）与猕猴 6 个面孔块的精确对应关系

**新登记的矛盾**：
- C-2026-08-16-01（高优先级）：腹侧流是否计算全局形状？claim_A=经典 IT 物体形状表征（established view），claim_B=Ayzenberg & Behrmann 2022 texforms 证据（腹侧流计算纹理统计非全局形状）

---

## 2026-08-15（文章 #114 — 眼优势柱与视觉关键期可塑性）

**新建页面（2 页）**：
- `wiki/concepts/ocular-dominance-columns.md`：ODC 发育双阶段（视网膜波→LGN 预分层→解剖前体；关键期 ODP→生理成熟）；ODP 两阶段（剥夺眼 NMDAR-LTD / 开放眼 LTP+稳态缩放）；PV+ 去抑制启动微回路；沉默突触开锁（AMPA/NMDA 比值 0.3→2）；tPA-塑素结构重塑；物种差异（猫/猴有 ODC 条带，小鼠无）
- `wiki/concepts/retinal-waves.md`：Stage I/II/III 视网膜波时序；β2-nAChR 驱动的 Stage II 对 LGN 眼特异分层的关键作用；与 ephrin-A 梯度的协同（双重 KO→V1 视野图几乎消失）；波→LGN 分层→TCA→ODC 的因果链

**修订页面（2 页）**：
- `wiki/concepts/critical-period.md`（rev4）：新增 [[ocular-dominance-columns]] 和 [[retinal-waves]] 连接；ODP 的去抑制启动（PV+ 先于锥体细胞响应）与关键期 PV+ 机制的直接关联被明确；source_articles 新增 #114
- `wiki/systems/v1-primary-visual-cortex.md`（rev5）：新增"眼优势柱与 ODP"小节（ODC 形成时间轴、ODP 证据表、小鼠特殊性）；related 新增 ocular-dominance-columns, retinal-waves, critical-period, thalamocortical-axons；key_sources 新增 PMID:22841309, PMID:32765222, PMID:23975100

**图谱更新**：新增 2 节点（ocular-dominance-columns, retinal-waves），新增 12 条有类型边；图谱总节点 240，总边 1370

**新登记的矛盾（1 条）**：
- C-2026-08-15-01（中优先级）：ODP 阶段二主导机制争议——Hebbian LTP（沉默突触开锁，Xu 2020）vs. 稳态突触缩放（TNFα，Kaneko 2017）

**新登记的未解问题**：
- Q-odc-01（高）：人类 V1 ODC 关键期竞争的分子时序
- Q-odc-02（中）：ODC 形成与 ODP 竞争的分子可解耦性
- Q-odc-03（中）：ODP 阶段二主导机制分工（详见 C-2026-08-15-01）

**解决的悬空引用**：此前 critical-period.md 和 v1-primary-visual-cortex.md 中提及 ODC 但无对应 wiki 页的悬空引用，今日以 `ocular-dominance-columns.md` 创建解决

---

## 2026-08-14（文章 #113 — 丘脑皮层轴突导向与感觉地图）

**新建页面（2 页）**：
- `wiki/concepts/thalamocortical-axons.md`：TCA 从丘脑出发的三段旅程（DTB→走廊→PSPB握手）；Ephrin-A5/EphA4 拓扑编码；FGF3 双路径排斥（PC-PLC 直接 + PI3K→Slit1 间接）；丘脑自发钙波功能；上丘感觉门控机制
- `wiki/concepts/subplate-neurons.md`：皮层最早出生的神经元，下板三亚层组织（入侵/导航/等待），握手假说的中心角色，TCA 等待区与皮层最早谷氨酸能突触，人类胎儿下板的特殊发育与临床意义

**修订页面（3 页）**：
- `wiki/concepts/barrel-cortex.md`（rev3）：新增 thalamocortical-axons 和 subplate-neurons 连接；加入 TCA 布线机制细节（Ephrin 拓扑、下板等待区、关键期 P0-P4）；key_sources 补充 PMID:40745219, PMID:32817388
- `wiki/concepts/cortical-arealization.md`（rev2）：新增上丘感觉门控机制（视网膜波驱逐触觉→LGN 成为纯视觉核）；新增 thalamocortical-axons 和 subplate-neurons 连接；key_sources 补充 PMID:40745219, PMID:38167425
- `wiki/concepts/axon-guidance.md`（rev3）：新增 TCA 特异性导向（走廊细胞-NRG1/ErbB4、握手假说、Ephrin-A5/EphA4）；新增 FGF3 双路径排斥机制（PMID:40806490）；related 扩展

**图谱更新**：新增 2 节点（thalamocortical-axons, subplate-neurons），新增 10 条有类型边；图谱总节点 238，总边 1358

**新登记的未解问题**：
- Q-tca-01（高）：TCA 等待区的停止-放行分子信号身份
- Q-tca-02（高）：丘脑波体内（in vivo）动力学——频率/振幅/核间同步
- Q-tca-03（中）：上丘感觉门控在人类胎儿中是否存在同等机制
- Q-subplate-01（中）：人类早产儿下板损伤与 ASD/CP 的因果关系

**裁决的矛盾**：无新增矛盾；"TCA 自发波调控区域大小"是对已有 cortical-arealization 中相应主张的细化，无冲突

**解决的悬空引用**：CHANGELOG-2026-08-13 中提到的 `thalamocortical-circuit` 悬空引用 — 今日以 `thalamocortical-axons` 形式创建对应页面，覆盖了该悬空引用的主要内容

---

## 2026-08-13（文章 #112 — 皮层区域化）

**新建页面（2 页）**：
- `wiki/concepts/cortical-arealization.md`：皮层区域化的两阶段机制——EMX2/PAX6/COUP-TFI/Sp8 转录因子梯度 + 丘脑活动雕刻；涵盖原图谱 vs. 原皮层之争历史、FGF8 信号中心、人类 GW20 V1-V2 离散边界
- `wiki/concepts/fgf8-cortical-patterning.md`：FGF8 如何从连合板作为上游信号中心建立皮层前后轴坐标系；Sp8-FGF8-EMX2 自调节回路

**修订页面（2 页）**：
- `wiki/concepts/cortical-neurogenesis.md`（rev4）：新增 cortical-arealization 和 fgf8-cortical-patterning 为 related 连接，标注祖细胞阶段 EMX2/Pax6 梯度是区域化的上游入口
- `wiki/concepts/cortical-layers.md`（rev3）：新增 cortical-arealization 为 related 连接

**图谱更新**：新增 2 个节点（cortical-arealization, fgf8-cortical-patterning），新增 10 条有类型边（regulates/prerequisite-for/related）；图谱总节点 236，总边 1348

**新登记的未解问题**：
- Q-area-01（高）：人类 PFC 相对扩大的分子基础
- Q-area-02（中）：V1-V2 离散边界的细胞机制（谱系 vs 丘脑活动）
- Q-area-03（低）：EMX2/PAX6 梯度在人类中的定量保守性

**裁决的矛盾**：无

**新增的悬空引用**：`thalamocortical-circuit`（在 cortical-arealization 页引用但可能未有独立页，需检查）

---

## 2026-08-12 · 文章 #111 · 不完整的礼物：SRGAP2C 与 ARHGAP11B 如何给人类大脑装上更多突触和更多神经元

**核心主题**：两个人类特异性截断基因复制（SRGAP2C ~240万年前；ARHGAP11B ~350万年前）——SRGAP2C 通过与祖先蛋白 SRGAP2A 异二聚化产生显性负效应，延缓突触棘成熟（neoteny）、提升密度（+71% 幼鼠，+40% 成年）；ARHGAP11B 通过 47-aa C 端尾部靶向线粒体激活谷氨酰胺酶解、增加天冬氨酸供给，促进基底放射状胶质细胞自我更新、引发皮层折叠——两者分别针对"连接密度"与"神经元数量"这两个维度推动人类皮层进化跃迁。

**新建页面（2）**：
- `concepts/srgap2c-neoteny.md` rev1 — SRGAP2C 显性负效应；F-BAR 异二聚化机制；突触棘密度 +71%（P18-21）/+40%（成年）；幼态化意义；进化时间点 ~240 万年前 (mechanism, established, confidence:high)
- `concepts/arhgap11b-cortical-expansion.md` rev1 — ARHGAP11B 发现（人类胎儿 bRG 特异性）；47-aa C 端尾部；谷氨酰胺酶解机制；GLUD2 协同效应；小鼠皮层折叠诱导；认知行为改变 (mechanism, established, confidence:high)

**修订页面（2）**：
- `concepts/outer-radial-glia.md` rev1→rev2 — related 新增 arhgap11b-cortical-expansion；连接 ARHGAP11B 作为 bRG 扩张驱动因子
- `concepts/notch2nl-cortical-expansion.md` rev1→rev2 — related 新增 arhgap11b-cortical-expansion/srgap2c-neoteny；建立三种人类特异性皮层进化机制之间的连接网络

**矛盾登记**：无新矛盾（ARHGAP11B 认知效益证据强度有限，标注为"中"置信度）

**新增悬空引用待补**：无新增

**图谱**：232→234 节点（+2），1324→1338 边（+14）

---

## 2026-08-11 · 文章 #110 · 皮层建造的故障报告：LIS1/DCX/Reelin 突变与无脑回谱系障碍

**核心主题**：I 型无脑回（LIS1 dynein N-C 偶联失败；DCX 微管束化缺陷及 X 染色体随机失活导致双皮层综合征；RELN 终止信号缺失导致层序倒置）；II 型无脑回（α-dystroglycan 糖基化缺陷基底膜破裂过度迁移）；多小脑回（GPR56、tubulinopathies）；三种故障模式揭示 Inside-Out 规则的三个独立模块（迁移机械/导航终止/物理边界）。

**新建页面（3）**：
- `concepts/lissencephaly.md` rev1 — 无脑回分类（I型/II型）；LIS1 N-C偶联机制；DCX 微管束化+性别二态性表型（SBH）；Reelin/Dab1 终止信号失活层序倒置；α-DG 糖基化缺陷过度迁移；基因治疗前景 (disease, established, confidence:high)
- `concepts/reelin-signaling.md` rev1 — VLDLR/ApoER2→Dab1磷酸化；PI3K/AKT/GSK3β路径（微管稳定）；LIMK1/cofilin路径（F-actin）；p-Dab1与LIS1的交叉；"脱离并跃迁"模型（Cooper 2008）；成年期突触可塑性功能；精神分裂症/AD连接 (mechanism, established, confidence:high)
- `concepts/cortical-migration-disorders.md` rev1 — 六类MCD分类（无脑回/双皮层/脑室旁异位/多小脑回/裂脑）；三层独立机制框架（迁移机械/导航终止/物理边界）；与切向迁移障碍的关系 (disease, established, confidence:high)

**修订页面（3）**：
- `concepts/cortical-neurogenesis.md` rev2→rev3 — related 新增 lissencephaly/reelin-signaling/cortical-migration-disorders；强化 Reelin 在 Inside-Out 终止中的位置
- `concepts/tangential-migration.md` rev1→rev2 — related 新增 cortical-migration-disorders/lissencephaly（两类迁移障碍并列）
- `concepts/cortical-layers.md` rev1→rev2 — related 新增 lissencephaly/cortical-migration-disorders/cortical-neurogenesis（六层结构崩溃连接）

**矛盾登记**：无新矛盾（已有矛盾未更新）

**新增悬空引用待补**：无新增（已有遗留悬空引用 `cognition` 仍未填补）

**图谱**：229→232 节点（+3），1302→1324 边（+22）

---

## 2026-08-10 · 文章 #109 · 皮层的第二种建筑学：GABA 能中间神经元切向迁移与命运决定

**核心主题**：皮层 GABAergic 中间神经元的发育起源（MGE/CGE）、切向迁移（CXCL12/CXCR4 + NRG1/ErbB4）、Nkx2.1→Lhx6 命运决定转录因子接力、程序性细胞死亡筛选 E/I 比（Wong 2018）、PV/SST/VIP 三类分化、精神分裂症/癫痫/ASD 的发育机制联系。**填补图谱悬空引用 `gaba`**。

**新建页面（4）**：
- `concepts/cortical-interneuron-development.md` rev1 — 中间神经元发育全流程：MGE/CGE 起源 → 切向迁移 → 命运决定（Nkx2.1-Lhx6/COUP-TFII）→ 程序性死亡（30-40%，Wong 2018）→ PV 功能成熟（KCC2/BDNF）(established, confidence:high)
- `concepts/tangential-migration.md` rev1 — 盐跃运动；CXCL12-CXCR4/CXCR7 维持迁移流；NRG1/ErbB4 吸引；Semaphorin/Neuropilin 排斥；48h 等待期；"分子握手"（兴奋性神经元前体 → CXCL12） (established, confidence:high)
- `concepts/medial-ganglionic-eminence.md` rev1 — MGE 空间分区（背侧偏 SST，腹侧偏 PV）；Shh→Nkx2.1→Lhx6 级联；SST 先出生（E11-13），PV 后出生（E13-15）；AP vs BP 分裂模式偏向 (established, confidence:high)
- `concepts/gaba.md` rev1 — GABA 合成（GAD65/67）分解；GABA-A（快 Cl⁻）/GABA-B（慢 G蛋白）；发育方向翻转（新生儿去极化→成年超极化，NKCC1→KCC2 转变，BDNF 驱动）；三类 GABA 能中间神经元总览 (established, confidence:high)

**修订页面（5）**：
- `circuits/pv-interneurons.md` rev4→rev5 — 新增：MGE 腹侧来源、Nkx2.1→Lhx6 命运路径、程序性死亡（Wong 2018）；related 新增 cortical-interneuron-development/MGE/gaba/tangential-migration；key_sources 更新（PMID:21154909, 18339674, 29849154）
- `circuits/sst-interneurons.md` rev1→rev2 — 新增：MGE 背侧来源、SST 早出生（E11-13）、精神分裂症 OFC SST 减少 67%（Joshi 2015）；related 和 dimensions 扩展
- `circuits/vip-interneurons.md` rev1→rev2 — 新增：CGE 来源（COUP-TFII/Sp8）、5HT3aR 作为 CGE 来源全谱标志（Lee 2010）；related 扩展
- `concepts/cortical-neurogenesis.md` rev1→rev2 — 新增：中间神经元"第二种建筑学"的互补连接；related 新增 cortical-interneuron-development/tangential-migration/MGE/gaba
- `concepts/ei-balance.md` rev1→rev2 — 新增：程序性细胞死亡（Wong 2018）作为发育期 E/I 比校准机制；related 新增 cortical-interneuron-development/gaba

**矛盾登记（0）**：今日来源未发现与既有 wiki 主张直接冲突（MGE 背腹分区的 SST/PV 偏向 vs 克隆混合问题已在文章正文争议节中说明，但不冲突现有已登记页面主张）。

**填补悬空引用**：`gaba`（已建 wiki 页 `concepts/gaba.md`，图谱悬空引用消除）

**新增悬空引用**：`cognition`（来自旧边，已知待建，非今日新增）

**知识图谱**：225 → 229 节点（+4），1281 → 1302 边（+21）

---

## 2026-08-09 · 文章 #108 · 皮层的诞生：从神经干细胞到六层皮质的 Inside-Out 建筑法则

**核心主题**：皮层神经发生（cortical neurogenesis）、Inside-Out 规则、aRGC/IPC 祖细胞系、Pax6→Tbr2→Tbr1 转录因子级联、FEZF2/SATB2 层身份开关、外放射状胶质细胞（oRGC）与 OSVZ、NOTCH2NL 人类皮层扩张分子机制、小头/大头畸形遗传基础。

**新建页面（3）**：
- `concepts/cortical-neurogenesis.md` rev1 — Inside-Out 规则；aRGC-IPC-神经元三级产出链；Pax6→Tbr2→Tbr1 接力；FEZF2/SATB2 层命运互斥开关；Reelin 迁移终止信号 (established, confidence:high)
- `concepts/outer-radial-glia.md` rev1 — oRGC vs aRGC 关键差异；OSVZ 作为次级增殖中枢；MST（有丝分裂体向基底迁移）；脑回形成张力-增殖模型 (established, confidence:high)
- `concepts/notch2nl-cortical-expansion.md` rev1 — NOTCH2NL 人类特有旁系同源体；DLL1-cis 竞争机制延长干细胞自我更新；1q21.1 CNV 剂量效应（缺失→小头，重复→大头）(established, confidence:high)

**修订页面（2）**：
- `concepts/adult-neurogenesis.md` rev2→rev3 — 新增 [[cortical-neurogenesis]] 连接（胚性 vs 成年神经发生对照）；related 字段更新；修订历史更新
- `concepts/critical-period.md` rev2→rev3 — 新增 [[cortical-neurogenesis]] 连接（Inside-Out 建造的皮层层结构为关键期提供解剖底座；PV+ 中间神经元 MGE 起源连接到胚性发育时序）；related 字段更新

**矛盾登记（0）**：今日来源未发现与既有 wiki 主张冲突。

**新增悬空引用**：`radial-glia`（在 cortical-neurogenesis.md 文本中引用但未建独立页，次要节点，并入 cortical-neurogenesis）；`intermediate-progenitor-cell`（同上）

---

## 2026-08-08 · 文章 #107 · 深部核团的门与教师：深部小脑核如何接管运动记忆

**核心主题**：深部小脑核（DCN）、下橄榄核（IO）与运动学习——填补三个悬空引用（deep-cerebellar-nuclei、inferior-olive、motor-learning）。内容：DCN 三核团（齿状核/间位核/顶核）的解剖与功能分工；间位核因果损毁证据（Thompson 1997，眼眨条件反射）；两相运动记忆模型（皮层 LTD 快速适应→DCN 苔藓纤维 LTP 缓慢巩固，Ito 2013+Ke 2009）；IO 的缝隙连接同步、阈下振荡（T型Ca²⁺）、TMEM16B 氯通道（Zhang 2017）；攀爬纤维奖励信号新发现（Jin & Hull 2025，待复现）；小脑-基底神经节直接皮层下连接（Bostan & Strick 2018）；CF "纯误差"vs"也编码奖励"矛盾登记。

**新建页面（3）**：
- `systems/deep-cerebellar-nuclei.md` rev1 — DCN 三核团解剖功能；去抑制输出逻辑；MF-DCN LTP 巩固机制；小脑-基底神经节互联 (established, confidence:high)
- `systems/inferior-olive.md` rev1 — IO 解剖亚核分工；Cx36 缝隙连接同步；TMEM16B 生物物理调节；CF 奖励信号（low confidence）；DCN→IO 抑制反馈 (established, confidence:high)
- `concepts/motor-learning.md` rev1 — 运动学习小脑-基底神经节双系统综述；两相记忆模型；眼眨条件反射范式 (established, confidence:high)

**修订页面（2）**：
- `systems/cerebellum.md` rev2→rev3 — 新增：间位核 CR 因果证据（Thompson 1997）、DCN LTP 两相巩固（Ke 2009）、小脑-基底神经节直接连接（Bostan 2018）；source_articles/key_sources 更新
- `concepts/climbing-fiber-error-signal.md` rev1→rev2 — 新增 CF 奖励信号证据（PMID:40848722，低置信度）；登记矛盾 C-2026-08-08-01；key_sources/source_articles 更新

**矛盾登记（1）**：C-2026-08-08-01（open，medium 优先级）：CF "纯误差信号"（Marr 经典，极高证据）vs "也传递奖励幅度"（Jin & Hull 2025，单篇待复现，低证据）。见 contested_claims.json。

**新增开放问题（4）**：Q-dcn-01（人类技能学习中 DCN LTP 时间进程，高优先级）、Q-dcn-02（DCN LTP 的 NMDA 依赖性与关键期）、Q-dcn-03（认知功能的 CCAS 是否走两相记忆模型）、Q-io-01（CF 奖励信号的回路来源）。

**图谱更新**：节点 219→222（+3），边 1255→1269（+14）。新节点：deep-cerebellar-nuclei、inferior-olive、motor-learning。悬空引用完全消除（之前：motor-learning/deep-cerebellar-nuclei/inferior-olive 均为悬空）。

---

## 2026-08-06 · 文章 #105 · 轴突找到伙伴之后：突触如何从分子装配线上诞生

**核心主题**：突触生成——课程脊柱第2章"神经网络如何建成"的续集（轴突导向 #103 的下一步）。核心内容：Neuroligin-Neurexin 跨突触"握手协议"（双向信号诱导前后侧装配）；NL1→兴奋性/NL2→抑制性突触身份二分；NL2-NRXβ1 弱结合×聚集效应的膜牵引+Gephyrin 招募机制（Boyd 2026, PMC12985673）；兴奋性 PSD 三层骨架（PSD-95/GKAP/Shank-Homer）；PSD 纳米亚结构单元（Ramírez-Expósito 2026, PMC12840169）；Gephyrin-Collybistin-Cdc42 格栅定向锚定抑制性受体；LRRTM 平行突触诱导系统（Roppongi 2020）；Kim 2026 "分子连续性"模型（轴突导向分子双重功能）；ASD 窗口（NLGN3 R451C, Shank3 缺失）；脑-AI 比较（结构约束 vs 无约束权重）。

**新建页面（4）**：
- `concepts/synaptogenesis.md` rev1 — 突触生成机制全面初始化；NL-NRXN 双向信号；分子连续性模型；兴奋性/抑制性双轨装配；活动依赖稳定与修剪 (established, confidence:high)
- `concepts/neuroligin-neurexin.md` rev1 — NL-NRXN 系统结构功能；可变剪接密码；NL1/NL2 突触类型二分；弱结合×聚集效应（Boyd 2026）；ASD 突变（NLGN3 R451C） (established, confidence:high)
- `concepts/postsynaptic-density.md` rev1 — PSD 三层架构（PSD-95/GKAP/Shank-Homer pallium）；纳米亚结构单元；LTP 5分钟重组；CaMKII 进入骨架层 (established, confidence:high)
- `concepts/gephyrin-scaffold.md` rev1 — Gephyrin 六角格栅；Collybistin/Cdc42 定向锚定；NL2→Collybistin 解自抑制；GABA-A 侧向扩散+陷阱捕获；甘氨酸受体高亲和力 (established, confidence:high)

**修订页面（1）**：
- `concepts/axon-guidance.md` rev1→rev2 — 新增"分子连续性"模型段落（Kim 2026, PMC13094498）：Latrophilin/Neurexin/NMDAR/Cerebellin 的导向→突触双重功能；更新 related（+neuroligin-neurexin）、key_sources（+PMID:41895449）、source_articles、revision_count

**矛盾登记（0）**：今日内容与现有 wiki 无矛盾。NL2-NRXβ1 弱结合的新证据（Boyd 2026）补充而非推翻已有理解（NL-NRXN 是突触识别中心机制），一致。

**新增开放问题（3）**：见 Q-synaptogenesis-01、Q-synaptogenesis-02、Q-synaptogenesis-03（追加到 unresolved_questions.md）

**图谱更新**：节点 214→218（+4），边 1233→1249（+16）。新节点：synaptogenesis、neuroligin-neurexin、postsynaptic-density、gephyrin-scaffold。新边涵盖轴突导向→突触生成→PSD/Gephyrin/LTP/ASD 的连接链。

---

## 2026-08-05 · 文章 #104 · 解剖即是命运？FlyWire 全脑连接组与"结构决定功能"大问题

**核心主题**：连接组学与结构-功能关系——课程脊柱第9章（Connectomics）与第10章（方法革命）首篇。核心内容：C. elegans（1986）→ Drosophila hemibrain（Scheffer 2020）→ FlyWire 完整果蝇大脑（Dorkenwald 2024，139,255神经元，~5400万突触）的历史跃迁；FlyWire 全脑网络拓扑统计（Lin 2024）：小世界系数SΔ=141（迄今最高生物神经网络）、平均路径4.42跳、富有节点（40,218个神经元，内部连接密度5.4倍）、广播者（胆碱能/视觉系统）vs 整合者（多巴胺能）；MICrONS 2025（小鼠V1功能-结构协注册，200,000+细胞，5亿突触）直接验证功能相似性预测突触连接；人类HCP宏观连接组尺度对比；C. elegans 40年教训（完整布线图+仍无法完全预测行为 = 神经调质不在布线图里）；脑-AI权重矩阵类比及其局限。

**新建页面（3）**：
- `concepts/small-world-network.md` rev1 — 小世界网络定义；SΔ量化指标；果蝇SΔ=141 vs C. elegans SΔ≈3.21 vs 互联网SΔ≈98.1；演化解释（局部专门化+全局整合双重压力）(established, confidence:high)
- `concepts/rich-club.md` rev1 — 富有节点定义；果蝇全脑约30%（40,218个）内部连接密度5.4倍；跨半球整合枢纽；人类DTI富有节点与DMN核心重叠；形成机制三假说 (established, confidence:high)
- `concepts/structure-function-relationship.md` rev1 — 结构约束而非决定功能；MICrONS 2025正向验证；C. elegans反例；"共同输入假说"机制；神经调质不变量问题 (mainstream, confidence:medium)

**修订页面（1）**：
- `methods/connectomics.md` rev1→rev2 — 新增：FlyWire 2024 全脑网络拓扑统计（小世界SΔ=141、富有节点、广播者/整合者、反馈连接13.8%）；MICrONS 2025 功能-结构协注册关键发现；更新 related（+small-world-network, rich-club, structure-function-relationship, axon-guidance）、key_sources（+PMID:39358527, 40205211, 21304930）、source_articles

**矛盾登记（0）**：今日文章内容与现有 wiki 无矛盾。C. elegans 40年局限与 MICrONS 2025 的部分验证属于互补而非矛盾——两者共同支持"结构约束但不决定功能"的框架。

**新增开放问题（3）**：见 Q-connectome-01、Q-connectome-02、Q-connectome-03（追加到 unresolved_questions.md）

**图谱修复 + 更新**：修复了 _graph.json 中 position 207725 的 JSON 语法错误（edges 数组过早关闭，axon-guidance 边组被孤立）；节点 211→214（+3），边 1219→1233（+14）

---

## 2026-08-04 · 文章 #103 · 大脑如何给自己布线：生长锥的分子导航与精密回路的发育起源

**核心主题**：轴突导向机制全面初始化——首次深入覆盖课程脊柱第2章"神经网络如何建成"中的轴突导向环节。核心内容：生长锥的结构与肌动蛋白踏车运动；四大导向分子家族（Netrin-DCC/UNC5双功能；Slit-ROBO中线单向阀门；Semaphorin-NRP-Plexin-MICAL排斥机制；Ephrin-Eph双向信号）；视网膜-上丘体地形图作为梯度×梯度建图的案例（Sperry化学亲和性假说的分子实现；正向+反向Ephrin信号协同；活动依赖精化的协同冗余）；Teneurin-LPHN系统在海马MEC/LEC层状投射的突触靶点识别机制；疾病窗口（ROBO3突变/水平凝视麻痹；苔藓纤维发芽/癫痫）；脑-AI布线逻辑比较（遗传先验 vs 随机初始化+梯度下降）。

**新建页面（2）**：
- `concepts/axon-guidance.md` rev1 — 轴突导向全面概述；四大家族、地形图逻辑、Teneurin-LPHN系统；疾病关联；连接 connectomics、critical-period、hippocampal-circuit (established, confidence:high)
- `concepts/growth-cone.md` rev1 — 生长锥结构（板状/丝状伪足）；踏车运动机制；各信号通路的骨架效应；动态重编程（Robo3→Robo1切换）；局部翻译 (established, confidence:high)

**修订页面（0）**：今日无修订（新建主题，无既有页面需更新）。

**矛盾登记（0）**：今日文章内容与现有 wiki 无矛盾。（体内梯度测量不确定性为已知局限，非新矛盾。）

**新增开放问题（3）**：
- Q-axon-guidance-01（高）：体内导向分子梯度的实际形态——体内测量方法突破是整个领域瓶颈
- Q-axon-guidance-02（中）：人类/灵长类 vs 小鼠的导向机制差异
- Q-axon-guidance-03（高）：多导向信号整合规则——生长锥如何计算矛盾信号的合力向量

**图谱**：203节点（+2：axon-guidance、growth-cone），~1189边（+10条）

---

## 2026-08-02 · 文章 #101 · 当大脑"放空"：默认模式网络如何成为自我的神经底座

**核心主题**：默认模式网络（DMN）的全面深化——Raichle 2001 的意外发现（OEF定量证明真实基线）；Andrews-Hanna 2010 双子系统架构精细解剖（dMPFC子系统=当前自我/心智化，MTL子系统=情景记忆/未来模拟，中线核心PCC+aMPFC=枢纽整合器）；PCC的"沉浸体验"框架（Leech & Sharp 2013：非仅自我参照，而是"被体验吸引"的更广泛状态；冥想PCC降低、渴求PCC升高、神经反馈实验验证）；心智漫游的感知解耦机制（Christoff 2016，早期感觉ERP下降，主动带宽切换）；刻意/非刻意漫游的神经差异（FPCN协同/不协同）；DMN-DAN反相关的功能意义（计算资源分配，FPCN作为切换器）；AD早期生物标志物（Sheline 2021，认知正常者DMN连接降低预测未来衰退）；脑-AI类比（无静息态内部网络、无持久自我模型、无情景性未来模拟）。

**新建页面（2）**：
- `concepts/self-referential-processing.md` rev1 — 自我参照效应历史（Rogers 1977记忆增强）；mPFC/PCC的神经底座；双子维度（当前vs历时自我）；文化差异与普遍神经机制 (established, confidence:high)
- `concepts/mind-wandering.md` rev1 — 感知解耦机制；刻意/非刻意两类型；DMN子系统的分工（MTL=记忆浮现，dMPFC=社会内容）；功能意义假说（情景性未来模拟/创造性/社会维护/记忆整合） (mainstream, confidence:high)

**修订页面（1）**：
- `systems/default-mode-network.md` rev3→rev5 — 新增Andrews-Hanna 2010双子系统分析（PMID:20188659）；PCC"沉浸体验/执念检测器"框架（PMC3788347）；心智漫游感知解耦（PMC5490683）；Sheline 2021 AD前临床DMN损伤证据（PMC8490784）；新增Q-dmn-05至Q-dmn-08；related新增self-referential-processing, mind-wandering；key_sources扩充至11个；updated→2026-08-02

**矛盾登记（0）**：今日无新增矛盾。DMN-DAN反相关的方法论争议（GSR问题）已在现有DMN页面登记为Q-dmn-01，今日新增证据支持反相关真实性（无GSR情况下较弱但仍存在），未登记新矛盾。

**新增开放问题（4）**：
- Q-dmn-05（高）：DMN默认模拟是否真代表情景性未来模拟（有功能目的）？
- Q-dmn-06（高）：TMS抑制PCC能否在行为层面减少"心理执念"（因果验证PCC沉浸框架）？
- Q-dmn-07（中）：DMN连接性的经验依赖可塑性——冥想/学习/创伤如何改变连接拓扑？
- Q-dmn-08（中）：DMN是否可操作化为预测编码的先验项？

**图谱**：203节点（+2：self-referential-processing、mind-wandering），新增约10条边（DMN↔新概念，新概念↔理论/现象）

---

## 2026-08-01 · 文章 #100（里程碑）· 教师信号的困境：攀爬纤维 LTD 的分子机制与小脑运动学习的"分布式可塑性"革命

**核心主题**：小脑 LTD（Marr-Albus-Ito 模型核心）的分子级联（mGluR1→PKC→GluA2 S880磷酸化→PICK1介导AMPAR内吞）详解；攀爬纤维误差信号的精密时序（眼跳后80–120ms，SC→IO延迟14.4ms，编码误差大小2°–6°和方向）；绒球最优 PF-CF 配对间隔≈120ms（匹配视觉反馈延迟，Suvrathan 2018）；颗粒细胞膨胀编码GluA4机制（200:1扩展比，GluA4 KO→电流↓80%、眼睑条件反射消失，Kita 2021）；Schonewille 2011 三种突变小鼠阻断LTD→运动学习仍正常，迫使范式转移；分布式可塑性（≥15种机制）；双相记忆轨迹（皮层LTD快速→DCN LTP慢速巩固，Ito 2013）；CCAS"思维失调"假说（156例，PMC6978293）；脑-AI类比（监督学习、稀疏误差信号、时间信用分配、冗余鲁棒性）。

**新建页面（2）**：
- `neurons/purkinje-cell.md` rev1 — 浦肯野细胞形态（~150,000树突棘、1:1 CF单一支配）、双重放电（简单50–100Hz/复杂~1Hz）、LTD输入-输出逻辑、GABAergic抑制DCN机制 (established, confidence:high)
- `concepts/climbing-fiber-error-signal.md` rev1 — CF误差信号全链（IO计算→CF传递→复杂放电→LTD触发）、误差时序量化（80–120ms/14.4ms延迟）、区域特异时窗、IO缝隙连接同步；感觉误差vs运动误差区分 (established, confidence:high)

**修订页面（2）**：
- `concepts/cerebellar-ltd.md` rev1→rev2 — 新增绒球120ms最优时窗（Suvrathan 2018）、攀爬纤维复杂放电时序量化（Soetedjo 2019）、双相记忆轨迹（Ito 2013）；新增未解问题Q-cb-04/Q-cb-05；related新增climbing-fiber-error-signal/purkinje-cell；key_sources补充3个PMID；updated→2026-08-01
- `systems/cerebellum.md` rev1→rev2 — 新增关键证据7行（CF时序、绒球窗口、GluA4实验、CCAS 156例、双相记忆轨迹）；相关页链接更新（新子页）；key_sources扩充至9个；opens_questions新增Q-cb-04/Q-cb-05；updated→2026-08-01

**矛盾登记（0）**：今日无新增矛盾。LTD非必要（Schonewille 2011）与LTD是运动误差机制（Ito经典）的张力已在文章#64时在cerebellar-ltd页登记，今日新增证据（Suvrathan 2018、Ito 2013双相轨迹）进一步充实了"分布式可塑性"范式对这个张力的统一解释，但核心矛盾（Q-cb-04：哪些范式中LTD是必要的）仍open。

**新增开放问题（2）**：
- Q-cb-04（高）：哪些具体学习范式中 LTD 仍是必要限速步骤？
- Q-cb-05（中）：小脑后叶认知学习（Crus I/II）是否使用相同的PF-PC LTD机制？

**图谱**：201节点（+3：purkinje-cell、climbing-fiber-error-signal；cerebellar-ltd已存在），新增约18条边

---

## 2026-07-31 · 文章 #99 · 皮层的"安抚手"：vmPFC 如何通过截获细胞与 BLA 直接投射平息杏仁核的恐惧输出

**核心主题**：内侧前额叶皮层下边缘子区（IL/vmPFC）通过三路并联机制实现对杏仁核恐惧输出的自上而下调控：①IL→腹侧ITC（截获细胞）→CeM的GABAergic门控（Likhtik et al. 2008，PMID:18615014；r=−0.67强负相关，选择性损毁因果证明）；②IL→BLA直接投射（消退后内在兴奋性↑，DREADD沉默→消退受损，Bloodgood et al. 2018，PMID:29507292）；③IL→PVT→CeA中继通路（Tao et al. 2021，PMID:33180308）。IL内部机制：消退训练激活mGluR5→AMPAR插入+内在兴奋性↑（Sepulveda-Orengo 2013，PMID:23616528）。时间逻辑：IL在消退训练时必要（写入），而非回忆时（Do-Monte 2015，PMID:25716859）。PL与IL功能可双重解离（Sierra-Mercado 2011）。

**新建页面（1）**：
- `circuits/pfc-amygdala-emotion-regulation.md` rev1 — 前额叶-杏仁核三路并联情绪调控回路整合节点；PL vs IL功能分工；ITC门控/BLA直接投射/PVT三通路；IL内部mGluR5可塑性；训练vs回忆时间逻辑；人类vmPFC对应证据；Q-pfc-amyg-01~04新增 (established, confidence:high)

**修订页面（3）**：
- `concepts/fear-extinction.md` rev2→rev3 — 新增IL→BLA直接投射消退专门化（Bloodgood 2018）；新增IL内部mGluR5→AMPAR分子可塑性（Sepulveda-Orengo 2013）；新增IL时间窗口（Do-Monte 2015）；新增IL→PVT第三通路（Tao 2021）；related/key_sources更新；updated→2026-07-31
- `systems/prefrontal-cortex.md` rev3→rev4 — 新增vmPFC/IL情绪调控功能子区完整小节（PL vs IL分工、三路并联机制、行为双重解离证据、人类vmPFC对应）；related新增amygdala/fear-extinction/pfc-amygdala-emotion-regulation；key_sources新增三个PMID；updated→2026-07-31
- `systems/amygdala.md` rev4→rev5 — ITC小节补充Likhtik 2008量化数据（r=−0.67，34%损毁）；新增IL→BLA直接投射对ICMMV协同增强；source_articles更新；updated→2026-07-31

**矛盾登记（0）**：今日无新增矛盾。IL→BLA直接投射（Bloodgood 2018）与经典IL→ITC→CeA模型是并列扩充而非冲突。

**新增开放问题（4）**：
- Q-pfc-amyg-01（中）：PL与IL的相互协调机制（mPFC内中间神经元？）
- Q-pfc-amyg-02（高）：人类vmPFC/BA25→杏仁核ITC门控机制的直接验证问题
- Q-pfc-amyg-03（中）：mGluR5 IL可塑性的上游驱动者（CS直接 vs vHPC预测误差信号？）
- Q-pfc-amyg-04（低）：儿童期IL未成熟对早期创伤消退障碍的具体分子机制

**图谱**：198节点（+1：pfc-amygdala-emotion-regulation），1145+边（新增：pfc-amygdala-emotion-regulation与amygdala/fear-extinction/prefrontal-cortex/fear-conditioning/hippocampal-circuit/bla-valence-circuits的多条关系边）

---

## 2026-07-30 · 文章 #98 · 情绪的两条轨道：杏仁核如何同时为奖励和恐惧编码价值

**核心主题**：基底外侧杏仁核（BLA）并非单一"恐惧中枢"，而是一个**价值极性双编码器**——两类神经元群（Ppp1r1b+后部奖励神经元 / Rspo2+前部恐惧神经元）通过**完全相反的突触可塑性规则**和**分叉的投射通道**（BLA-NAc / BLA-CeA），分别向奖励驱动和威胁防御系统传递正向与负向情绪价值信号。核心实验：Namburi et al. 2015（PMID:25925480，Nature）——恐惧学习使 NAc 投射 AMPAR/NMDAR 比值 ↓、CeM 投射 ↑；奖励学习则完全相反。Beyeler et al. 2016（PMID:27041499，Neuron）——光标记发现 BLA-NAc 神经元 77% 被奖励线索激活，BLA-CeA 神经元 100% 被厌恶线索激活。Corbit & Balleine 2005（PMID:15673677）双解离证明 BLA 编码奖励结果身份（outcome-specific PIT）。Sias et al. 2024（PMID:38396258，Nature Neuroscience）——VTA-DA→BLA 投射专门驱动结果特异性奖励记忆的编码。Wassum 2022（PMID:36062909，eLife）——BLA-OFC 四向协作：lOFC→BLA 编码记忆、mOFC→BLA 用于决策、BLA→lOFC 提取奖励身份、BLA→mOFC 传递预期价值。

**新建页面（1）**：
- `concepts/bla-valence-circuits.md` rev1 — BLA 奖励-恐惧双通道：遗传分化（Ppp1r1b+ vs Rspo2+）、突触对立可塑性（Namburi 2015）、投射路由（Beyeler 2016）、PIT 行为证据（Corbit 2005）、DA→BLA 奖励记忆写入（Sias 2024）；Q-bla-01~03 (established, confidence:high)

**修订页面（2）**：
- `systems/amygdala.md` rev3→rev4 — 新增"BLA 奖励-恐惧双通道"完整小节（Ppp1r1b+/Rspo2+遗传身份、对立可塑性表格、77%/100%数据、DA→BLA 角色、光遗传行为验证）；一句话定义更新包含双极编码功能；related 新增 bla-valence-circuits, incentive-salience, subjective-value-encoding；key_sources 新增三个 PMID；updated→2026-07-30
- `systems/orbitofrontal-cortex.md` rev1→rev2 — 新增"BLA-OFC 双向协作"小节（四向回路：lOFC→BLA/mOFC→BLA/BLA→lOFC/BLA→mOFC）；来源 Wassum 2022（PMID:36062909）；related 新增 bla-valence-circuits；updated→2026-07-30

**矛盾登记（0）**：今日无新增矛盾。BLA 奖励-恐惧双通道与既有 amygdala 页（原聚焦恐惧）是互补扩展而非矛盾；与 OFC 的协作已在 OFC 页预留连接，今日补全细节。

**新增开放问题（3）**：
- Q-bla-01（高优先）：BLA 奖励神经元与恐惧神经元的比例是否可以在成年期通过经验或训练重塑？
- Q-bla-02（中）：人类 BLA 中 Ppp1r1b+/Rspo2+ 遗传分化是否同样存在？功能等价物是什么？
- Q-bla-03（中）：DA→BLA 奖励记忆写入的时间窗口（RPE 后多久？是否需要 NMDAR 协同）？

**图谱**：197 节点（+1：bla-valence-circuits），1139 边（+6 条新边：bla-valence-circuits 的部分/机制/调控/支持关系）

---

## 2026-07-29 · 文章 #97 · 价值的地图：眶额叶皮层如何计算"什么值得追求"

**核心主题**：眶额叶皮层（OFC）作为大脑的"估价系统"，将多维奖励属性（大小、概率、延迟、主观偏好）整合为单一可比较的主观价值信号，是目标导向决策与奖励学习的关键节点。核心细胞证据：Padoa-Schioppa & Assad（2006，PMID:16633341）在猕猴 OFC 发现三类商品价值神经元（offer-value-A、offer-value-B、chosen-value），其编码格式是行为无关的"goods-based"（商品基础）而非"action-based"。Rangel et al.（2008，PMID:18545266）三系统框架：OFC 作为目标导向系统（DMS+OFC）的价值输入源，向腹侧纹状体（NAc）提供结果当前价值信号；OFC 损伤 → 目标导向系统退化为习惯系统（贬值不敏感）。Hattori et al.（2023，PMID:37957318）OFC 元学习：CaMKII 可塑性积累跨会话任务结构知识，使 actor-critic 批评家的 V(s) 初始化更准确。Hare et al.（2009，PMID:19407204）vmPFC+dlPFC 自我控制回路：dlPFC 调制 vmPFC 的多维价值权重，高 dlPFC 活动时认知目标权重↑。

**新建页面（2）**：
- `systems/orbitofrontal-cortex.md` rev1 — OFC：多模态汇聚（味觉/嗅觉/视觉/内脏/体感）+三功能子区（内侧OFC/外侧OFC/中央OFC）+三类价值神经元（Padoa-Schioppa 2006）+三系统框架角色（目标导向价值输入源）+vmPFC自我控制调制（Hare 2009）+OFC元学习（Hattori 2023）；Q-ofc-01~03 (established, confidence:high)
- `concepts/subjective-value-encoding.md` rev1 — 主观价值编码：三系统竞争框架（巴甫洛夫/习惯/目标导向）+价值信号时序（offer-value → chosen-value）+vmPFC+dlPFC自我控制+两时间尺度学习（ms-s RPE / days CaMKII）；Q-sval-01~02 (established, confidence:high)

**修订页面（3）**：
- `concepts/habit-formation.md` rev2→rev3 — 新增"OFC 对目标导向系统的关键贡献"小节：OFC→DMS 价值信号是目标导向系统灵活性的来源；OFC 损伤解释临床"强制习惯"表现；related 新增 orbitofrontal-cortex, subjective-value-encoding；key_sources 新增 PMID:18545266, PMID:16633341
- `concepts/actor-critic-model.md` rev1→rev2 — 新增"OFC 作为批评家的价值输入源"小节：OFC→NAc 价值信号投射使 V(s) 实时更新；Hattori 2023 元学习扩展层；related 新增 orbitofrontal-cortex, subjective-value-encoding；key_sources 新增 PMID:18545266, PMID:16633341, PMID:37957318
- `concepts/dopamine-reward-prediction-error.md` rev8→rev9 — 新增"OFC 双层学习对 DA-RPE 框架的扩展"小节：OFC CaMKII 元学习使 V(s) 初始化不从零开始；证据表（Hattori 2023 证据）；related 新增 orbitofrontal-cortex, subjective-value-encoding

**矛盾登记（0）**：今日无新增矛盾。OFC 为 actor-critic 批评家提供价值输入与现有 DA-RPE 框架完全兼容（补充而非修正）。

**新增开放问题（5）**：
- Q-ofc-01（高优先）：OFC 价值编码是真正的单一标量压缩还是多维向量保留至下游整合？
- Q-ofc-02（中）：外侧 OFC 与内侧 OFC 的价值信号功能分工是否绝对（惩罚/奖励双轨）？
- Q-ofc-03（低）：OFC 元学习在多长时间尺度上积累（跨会话 vs 跨数周）？CaMKII 磷酸化是否参与?
- Q-sval-01（高优先）：价值信号是单一标量还是多维向量？
- Q-sval-02（中）：主观价值编码与自我意识的关系——无自我意识系统能否实现"主观价值"？

**图谱**：198 节点（+2：orbitofrontal-cortex, subjective-value-encoding），1149 边（+16 条新边）

---

## 2026-07-28 · 文章 #96 · 记忆的活书稿：记忆再巩固现象揭示的大脑真相

**核心主题**：记忆再巩固（reconsolidation）——已完全巩固的长期记忆，在每次被提取后会短暂回到蛋白质合成依赖的不稳定状态（去稳定化），需要重新合成蛋白质才能再次固化（再稳定化）。分子机制：NMDA受体激活→GluA2亚基内吞（含GluA2的AMPAR从突触膜移除）→泛素-蛋白酶体激活（支架蛋白降解）→去稳定化；新的基因转录（CREB/C/EBP/Zif268）→翻译→再稳定化，时间窗约6小时。关键计算条件：**预测误差**是必要条件（Sevenster et al. 2013 Science，人类直接证据）。临床应用：普萘洛尔（β受体阻断剂）在记忆激活后给予可削弱PTSD记忆（Debiec & LeDoux 2004；Mallet et al. 2022初步临床证据）。边界条件：强记忆、老记忆、完整提取（无预测误差）不触发再巩固，与GluN2A/GluN2B元可塑性假说相关。

**新建页面（1）**：
- `concepts/memory-reconsolidation.md` rev1 — 记忆再巩固：去稳定化（GluA2内吞+UPS）→再稳定化（CREB/Zif268/蛋白合成）；预测误差驱动；边界条件；PTSD临床应用；与消退的关系 (established, confidence:high)

**修订页面（2）**：
- `concepts/memory-consolidation.md` rev8 — 新增"再巩固"作为第三种巩固类型（突触巩固、系统巩固、再巩固三分类）；连接节新增 [[memory-reconsolidation]]；related扩充；dimensions新增molecular/synaptic；updated→2026-07-28
- `concepts/engram-cells.md` rev6 — 当前理解新增"再巩固作为印迹修改的窗口"段落（GluA2内吞使印迹进入可编辑状态；再巩固失败→印迹真实消除，区别于沉默印迹）；连接节新增 [[memory-reconsolidation]]；related扩充；dimensions新增molecular/synaptic；updated→2026-07-28

**矛盾登记（0）**：今日无新增矛盾。再巩固与消退均为提取后可塑性过程，不冲突，而是同一现象的不同表现（已在 Q-recon-02 记录为未解问题）。

**新增开放问题（4）**：
- Q-recon-01（高优先）：能否开发特异性靶向单一记忆的再巩固干预手段？
- Q-recon-02（高优先）：再巩固与消退是否共享底层分子机制？分叉点在哪里？
- Q-recon-03（中）：强记忆/老记忆的边界条件全貌（元可塑性是否是唯一机制？）
- Q-recon-04（中）：人类再巩固的突触层面直接证据（现有仅为行为/fMRI间接证据）

**图谱**：196 节点（+1：memory-reconsolidation），1133 边（+11条新边）

---

## 2026-07-27 · 文章 #95 · 绝缘层的革命：少突胶质细胞与活动依赖性髓鞘化

**核心主题**：少突胶质细胞（OL）是 CNS 唯一的髓鞘制造者，单个细胞可包裹 40–50 段来自不同神经元的轴突，通过致密脂质膜（MBP+PLP）和兰维耶节（Nav1.6）实现跳跃式传导（saltatory conduction），速度提升约 100 倍（0.5→120 m/s）、能耗降低约 100 倍。关键新认知：活动依赖性髓鞘化（Gibson et al. 2014, Science PMID:24727982）——光遗传激活运动前区 → OPC 增殖分化 → 髓鞘化增加 → 行为改善；阻断 OL 分化则消除行为改善（因果确定）。Yalçín et al. 2024（Nature）进一步揭示 VTA 多巴胺神经元活动驱动局部 OL 生成，OL 缺失损害多巴胺释放和阿片类奖励行为，将白质可塑性纳入奖励回路分析。人类额叶髓鞘化延续至 30 岁。髓鞘可塑性与突触可塑性是互补的学习双轴：前者改变传导**时机**，后者改变信号**强度**。

**新建页面（2）**：
- `neurons/oligodendrocyte.md` rev1 — 少突胶质细胞：1对40–50轴突包裹；OPC终生分化潜能；活动依赖信号（谷氨酸/ATP→AMPA/NMDA受体）；代谢支持（乳酸穿梭）；VTA奖励回路中必要性 (established, confidence:high)
- `concepts/myelination.md` rev1 — 髓鞘化：跳跃式传导原理（Rm×1000/Cm÷50）；发育时间表（额叶至30岁）；活动依赖可塑性（Gibson 2014因果证据）；人类特异性（OPC更新速度比小鼠慢100倍）；三个未解问题 (established, confidence:high)

**修订页面（3）**：
- `neurons/action-potential.md` rev4 — 新增与 myelination、oligodendrocyte 的关联；说明跳跃式传导是髓鞘化的核心功能输出；updated→2026-07-27
- `concepts/dopamine-reward-prediction-error.md` rev8 — 新增 VTA 髓鞘化维度：Yalçın 2024（PMID:38839962）表明 OL 可塑性参与 DA 回路传导时序调节；related新增myelination、oligodendrocyte；updated→2026-07-27
- `concepts/critical-period.md` （updated→2026-07-27，新增连接额叶髓鞘化延迟至30岁的维度）

**矛盾登记（0）**：今日无新增矛盾。但 Q-myelin-01 登记一个重要不确定性：人类成年期 OL 可塑性机制（新 OL 生成 vs 既有 OL 形态调整）缺乏直接证据，人类与小鼠不可直接类比。

**新增开放问题（3）**：
- Q-myelin-01（高优先）：人类成年 OL 可塑性主导机制
- Q-myelin-02（中）：OPC 选择包裹哪条轴突的竞争机制
- Q-myelin-03（中）：MS 再髓鞘化不完整的分子原因

**图谱**：195 节点（+3），1122 边（+11）

---

## 2026-07-24 · 文章 #92 · 大脑的第四维罗盘：时间细胞与速度细胞如何建立时间坐标系

**核心主题**：时间细胞（time cells）是海马CA1神经元在记忆任务延迟期以接力棒式序列放电的功能状态，与场所细胞同源（同一神经元，不同激活模式）；标量特性（可重新校准，延迟时长改变→放电峰值按比例调整）对应行为韦伯律；人类证据来自Umbach等2020（PMID:33109718）颅内记录。速度细胞（speed cells）是MEC中放电率与运动速度线性正相关的神经元，通过脑干PPN→基底前脑HDB→MEC通路接收运动速度信号（Carvalho 2020，PMID:32905779），为路径整合提供速度输入（有~50-80ms前瞻偏置）。外侧内嗅皮层（LEC）群体状态漂移在秒到小时时间尺度编码经历时间（Tsao 2018，PMID:30158699），提供情节记忆的时间戳。三者共同将空间认知地图升级为完整的时空情节坐标系。

**新建页面（2）**：
- `concepts/time-cells.md` rev1 — 时间细胞：海马CA1接力棒式时间序列；可重新校准标量特性；与场所细胞同源（75%+含空间信息）；人类颅内记录证据（Umbach 2020）（established, confidence:high）
- `concepts/speed-cells.md` rev1 — 速度细胞：MEC线性速度编码；环境无关；50-80ms前瞻偏置；PPN→HDB→MEC脑干通路（Carvalho 2020）（established, confidence:high）

**修订页面（4）**：
- `concepts/place-cells.md` rev3 — 新增"场所细胞=时间细胞同一神经元双重模式"认识（MacDonald 2011）；related新增time-cells；key_sources新增PMID:21867888；updated→2026-07-24
- `concepts/grid-cells.md` rev3 — 新增速度细胞补全路径整合速度分量；联合细胞小节补充速度来源；related新增speed-cells/time-cells；key_sources新增PMID:26176924；updated→2026-07-24
- `systems/entorhinal-cortex.md` rev2 — 新增MEC速度细胞亚群（Kropff 2015, Carvalho 2020）；新增LEC时间戳漂移功能（Tsao 2018）；情节编码框架升级为"空间×情境×时间"三维；related/key_sources更新；updated→2026-07-24
- `concepts/path-integration.md` rev3 — 新增速度细胞为速度输入细胞实现（Carvalho 2020）；新增时间细胞作为时间路径整合类比；related/key_sources更新；updated→2026-07-24

**矛盾登记（0）**：今日无新增矛盾。时间细胞（MacDonald 2011）和速度细胞（Kropff 2015）均为教科书级established知识，多实验室重复；LEC时间戳（Tsao 2018）人类证据待补但现有大鼠证据高置信。

**新增开放问题（4）**：Q-tc-01（高优先：时间细胞序列内部生成vs外部驱动）、Q-tc-02（中：速度细胞人类直接证据缺失）、Q-tc-03（高优先：标量特性的网络机制）、Q-tc-04（低：LEC漂移分子基础）

**图谱**：184 节点（+2），~1085 边（估计+27）

---

## 2026-07-23 · 文章 #91 · 皮层六层架构：大脑用六层细胞片实现感知与预测的解剖分工

**核心主题**：皮层六层结构（L1–L6）是哺乳动物新皮层的高度保守计算架构——L4 接收丘脑前馈输入（但丘脑输入仅占 L4 突触 10–20%，相互兴奋放大约 10 倍）；L2/3 以高阈值门控（需45–50个 L4 细胞同时激活）实现群体活动检测，发出前馈 γ 振荡；L5/6 发出反馈 α/β 振荡到低级区域 L1/6；L1 接收来自高级区域的远程反馈作用于顶端树突。Douglas & Martin（1991，PMID:1666655）规范微回路（三群体：浅层锥体/深层锥体/抑制中间神经元）是跨脑区通用模板；Felleman & Van Essen（1991，PMID:1822724）确立前馈（浅层→L4）/ 反馈（深层→L1/6）层间法则；Markov 等（2014，PMID:23983048）定量证明反馈连接数量约是前馈的2:1；Bastos 等（2012，PMID:23177956）将规范微回路与预测编码整合：L2/3=误差单元/γ，L5/6=预测单元/α-β。

**新建页面（2）**：
- `concepts/cortical-layers.md` rev1 — 皮层六层架构：L1–L6 功能分工；丘脑输入仅10-20%；L4内连接率25-36%；L4→L2/3高阈值门控（45-50个细胞）；FF/FB层间法则；γ-FF/α-β-FB振荡分工（established, confidence:high）
- `concepts/canonical-microcircuit.md` rev1 — 规范微回路（Douglas-Martin 1991）：三群体模型；相互兴奋放大10倍丘脑输入；状态依赖计算；Bastos 2012整合为预测编码解剖底层（established, confidence:high）

**修订页面（2）**：
- `concepts/barrel-cortex.md` rev2 — 新增 cortical-layers 和 canonical-microcircuit 为关联节点；桶状皮层作为六层回路定量验证最清晰模型系统的角色明确；related 列表更新；updated→2026-07-23
- `theories/predictive-coding.md` rev8 — 新增 canonical-microcircuit 和 cortical-layers 到 related 和连接节；明确规范微回路是预测编码的解剖底层（Bastos 2012）；source_articles 加入 2026-07-23 文章；updated→2026-07-23

**矛盾登记（0）**：今日无新增矛盾。皮层六层架构和规范微回路是多物种、多实验室高度验证的 established 结论；FF/FB 振荡分工在啮齿类的普适性争议已记录为 Q-cl-02，与 predictive-coding.md 中 Q-pc-05 联动。

**解决的悬空引用（0）**：无（cortical-layers 和 canonical-microcircuit 为今日新增，之前未被显式引用；barrel-cortex 现增加对它们的引用）

**新增开放问题（3）**：Q-cl-01（高优先：agranular 皮层规范微回路如何修订）、Q-cl-02（高优先：振荡分工普适性争议）、Q-cl-03（中：中间通路例外的整合）

**图谱**：182 节点（+2），1058 边（+22）

---

## 2026-07-22 · 文章 #90 · 大脑的内置罗盘：头向细胞与边界细胞完成空间导航四元组

**核心主题**：头向细胞（Head Direction Cells）与边界细胞（Border Cells/BVCs）——大脑 GPS 系统的方向编码器和边界传感器，完成空间导航四元组（场所细胞/网格细胞/头向细胞/边界细胞）。头向细胞回路（DTN→LMN→ADN→PoS→RSC→MEC深层）以环形吸引子机制由前庭系统驱动，由视觉地标锚定；Peyrache 2015（PMID:25706474）证明 ADN 群体相干旋转说明吸引子内在动力学。边界细胞（Solstad 2008 MEC；Lever 2009 下托）是 O'Keefe & Burgess 1996 BVC 理论的实验验证，拉伸实验证明边界特异性；计算模型提示边界细胞通过重置网格吸引子校正路径整合漂移。

**新建页面（3）**：
- `systems/head-direction-cells.md` rev1 — 头向细胞：首选方向/调谐宽度~90°/位置无关；DTN-LMN-ADN-PoS-RSC-MEC回路；环形吸引子内在动力学（Peyrache 2015）；前庭驱动+视觉锚定（established, confidence:high）
- `concepts/border-cells.md` rev1 — 边界细胞：MEC（Solstad 2008）+下托（Lever 2009）；边界特异性/拉伸实验；BVC模型；路径整合误差校正；对新边界秒级响应（established, confidence:high）
- `concepts/ring-attractor.md` rev1 — 环形吸引子网络：距离依赖兴奋-抑制；稳定活跃峰；角速度驱动旋转；Zhang 1996 理论+Peyrache 2015 实验；与CA3离散吸引子的对比（established, confidence:high）

**修订页面（1）**：
- `concepts/path-integration.md` rev2 — 新增 head-direction-cells 和 border-cells 为已填补的相关节点（原为悬空引用 head-direction-cells）；修订历史追加；updated→2026-07-22；revision_count 1→2

**矛盾登记（0）**：今日无新增矛盾。头向细胞的经典放电特性（Taube 1990）和边界细胞的发现（Solstad 2008，Lever 2009）均是多次独立重复的 established 结论。

**解决的悬空引用（1）**：`head-direction-cells`（被 path-integration.md 的 related 列表引用，原为悬空；今日填补）

**新增开放问题（3）**：Q-hd-01（高优先：HD信号首发地DTN vs LMN）、Q-hd-02（中：重映射中HD是否同步重映射）、Q-bc-01（高优先：边界细胞重置网格吸引子的因果机制）

**图谱**：180 节点（+3），1036 边（+18）

---

## 2026-07-21 · 文章 #89 · 大脑的频闪滤网：α 振荡的脉冲抑制机制与注意力门控

**核心主题**：α 振荡（8–13 Hz）从"皮层闲置"到"主动脉冲抑制"的概念革命（Track 5 认知控制 × Track 3 感觉编码交叉篇）——Jensen & Mazaheri 2010 "Gating by Inhibition" 框架：大脑通过主动抑制无关区域（而非增强目标区域）路由信息；α 脉冲抑制（每 ~100ms GABA 超极化）调控 duty-cycle；空间注意时对侧被忽略枕叶 α 升高（视网膜拓扑特异性，Worden 2000）；预刺激 α 反向预测视觉皮层兴奋性（Romei 2008 TMS 光幻视）；节律性 TMS 10Hz 频率特异性因果诱导视野特异感知抑制（Romei 2010）；跨视觉/体感/听觉的 α 抑制普遍性（Foxe & Snyder 2011）；FEF-IPS α 相干性是 DAN 控制感觉皮层 α 侧向化的振荡载体（van Schouwenburg 2017）；α-γ 互补关系（α 高区 = γ 低区）。

**新建页面（1）**：
- `concepts/alpha-oscillations.md` rev1 — α 振荡：脉冲抑制机制；空间特异 α 侧向化；α-γ 互补；丘脑-皮层生理基础；FEF-IPS 上游控制；跨感觉普遍性；ADHD 相关（established, confidence:high）

**修订页面（3）**：
- `concepts/dorsal-attention-network.md` rev2 — 新增"α 振荡控制"机制节：FEF-IPS α 相干性指挥感觉皮层 α 侧向化；更新 related 加入 alpha-oscillations；更新 updated/revision_count/修订历史
- `concepts/gamma-oscillations.md` rev4 — 新增"α-γ 互补关系"对照表节；更新 related 加入 alpha-oscillations；更新 updated/revision_count
- `wiki/_graph.json` — +1节点（alpha-oscillations），+14边（177总节点，1018总边）

**矛盾登记（0）**：今日无新增矛盾。α 振荡的主动抑制功能已在多个独立实验室获广泛验证（Worden 2000→Romei 2008, 2010→Foxe & Snyder 2011→van Schouwenburg 2017），知识地位已为 established。

**解决的悬空引用（1）**：`alpha-oscillations`（被 dorsal-attention-network、gamma-oscillations、working-memory 中隐含引用，现有明确源页面）

**新增开放问题（3）**：Q-alpha-01（高优先：FEF→枕叶 α 的解剖通路）、Q-alpha-02（中：IAF 个体差异与注意效率）、Q-alpha-03（中：清醒 α 门控与睡眠丘脑纺锤波共享机制）

**图谱**：177 节点（+1），1018 边（+14）

---

## 2026-07-20 · 文章 #88 · 感官交响曲：多感觉整合的计算神经科学

**核心主题**：多感觉整合（Track 3 感觉编码闭环篇）——贝叶斯因果推断（先判断是否同源）+ 最大似然估计（可靠性加权融合）两级计算架构；上丘三原则（空间对齐、时间一致、逆效性法则）；时间绑定窗口（TBW）测量、发育轨迹和训练可塑性（40-64%缩小）；TBW 在 ASD/阅读障碍/精神分裂症中的扩宽；pSTS 作为视听整合皮层枢纽（嘴型-声音联合选择性）；ALE 荟萃分析确认的多感觉网络（STG/MTG-丘脑-岛叶-IFG）；三经典幻觉（麦格克效应、声音诱导闪光幻觉、腹语效应）作为整合机制的行为证据；与预测编码框架的深层联结（两者共享"感知=贝叶斯推断"认识论）。

**新建页面（5）**：
- `concepts/multisensory-integration.md` rev1 — 多感觉整合：贝叶斯因果推断+MLE框架；上丘三原则；pSTS枢纽；TBW可塑性；ASD/精神分裂症临床关联（established, confidence:high）
- `concepts/temporal-binding-window.md` rev1 — 时间绑定窗口：SJ/TOJ测量；100-500ms范围随刺激复杂度；训练可缩小40-64%（PMC2771316全文）；ASD/阅读障碍/精神分裂症扩宽（established, confidence:high）
- `concepts/bayesian-sensory-integration.md` rev1 — 贝叶斯感觉整合：MLE公式w_i=σ_j²/Σσ_k²；因果推断层；与逆效性法则数学等价（mainstream, confidence:high）
- `concepts/mcgurk-effect.md` rev1 — 麦格克效应：视觉/ga/+听觉/ba/→感知/da/；前意识自动过程；pSTS联合选择性是神经基础（established, confidence:high）
- `systems/superior-temporal-sulcus.md` rev1 — 后颞上沟（pSTS）：位于听觉-视觉皮层交界；嘴型-声音联合选择性；后→前功能梯度（感觉运动→语义）；ALE荟萃分析确认为多感觉整合最一致激活皮层节点（mainstream, confidence:high）

**修订页面（3）**：
- `systems/auditory-cortex.md` rev2 — 新增 related: superior-temporal-sulcus, multisensory-integration, mcgurk-effect；确认 A1→pSTS 视听整合的上游输入地位
- `theories/predictive-coding.md` rev7 — 新增 related: multisensory-integration, bayesian-sensory-integration；确认多感觉贝叶斯整合是预测编码框架的多模态输入层实现
- `wiki/_graph.json` — +5节点，+30边（176总节点，1004总边）

**矛盾登记（0）**：今日无新增矛盾。多感觉整合的核心计算原则（MLE、贝叶斯因果推断）已获广泛实验支持，无需登记分歧。

**新增开放问题（3）**：Q-msi-01（高优先：贝叶斯因果推断的单细胞神经表示）、Q-msi-02（中优先：婴儿期MLE整合能力发展）、Q-msi-03（中优先：ASD的TBW扩宽是原发还是继发）

**解决的悬空引用**：superior-temporal-sulcus（被 language-network, broca-area 隐式引用；现有明确源页面）

**图谱**：176 节点（+5），1004 边（+30）

---

## 2026-07-19 · 文章 #87 · 从皮肤到大脑的身体地图：触觉机械感受器、背柱通路与初级体感皮层的拓扑映射

**核心主题**：体感系统（Track 3 感觉编码第 6 篇）——四类皮肤机械感受器的结构-功能分工（梅斯纳/帕西尼/迈克尔/鲁菲尼）；背柱-内侧丘系三级中继通路；S1 四子区（3a本体感觉/3b触觉/1质地/2整合）分工；皮质体感小人（版图大小∝受体密度而非面积）；桶状皮层（一胡须一桶）作为精确拓扑映射的经典模型；发育关键期（P0–P4，MAOA/AC1 KO 机制）；成人皮层重映射（截肢→嘴唇区移位/盲文→视觉皮层跨模态）；S2 对感觉阈值的因果门控（PMID:38346995）。

**新建页面（6）**：
- `systems/somatosensory-cortex.md` rev1 — 初级体感皮层（S1）：四子区功能分工（3a/3b/1/2）；皮层版图∝受体密度；成人可塑性；S2 层级连接（established, confidence:high）
- `concepts/barrel-cortex.md` rev1 — 桶状皮层：一胡须一桶；四站传递 ~5 ms；柱约 6500 神经元，稀疏编码响应概率 0.32；发育关键期 P0–P4；MAOA/AC1 KO 遗传解剖（established, confidence:high）
- `concepts/mechanoreceptors-skin.md` rev1 — 皮肤机械感受器：四类 Aβ 传入；快适应（梅斯纳/帕西尼）vs 慢适应（迈克尔/鲁菲尼）；频率响应范围；受体密度→两点阈值（established, confidence:high）
- `concepts/cortical-homunculus.md` rev1 — 皮质体感小人：Penfield 电刺激标测；版图大小∝受体密度（非面积）；跨系统设计原则（音调拓扑/V1放大/桶状皮层）（established, confidence:high）
- `concepts/cortical-remapping.md` rev1 — 皮层重映射：截肢后嘴唇代表区移位 ~8 mm；机制主要为突触解蔽；幻肢痛相关（相关 vs 因果未定）；盲文/跨模态可塑性（mainstream, confidence:medium）
- `concepts/dorsal-column-pathway.md` rev1 — 背柱-内侧丘系通路：三级中继（DRG→背柱核→内侧丘系→VPL→S1）；薄束/楔束躯体拓扑保持；损伤表现（established, confidence:high）

**修订页面（0）**：今日无修订现有页面（新领域进入，无既有体感皮层页面需修订）。

**矛盾登记（0）**：今日无新增矛盾（体感系统核心机制均为高度确立知识；皮层重映射与幻肢痛因果关系已在 cortical-remapping 页面标注为相关性证据，尚无需登记矛盾）。

**新增开放问题（4）**：Q-som-01（高优先：S1重映射与幻肢痛相关vs因果）、Q-som-02（中优先：桶状皮层局部异质性功能意义）、Q-som-03（中优先：人类3a/3b/1/2在7T fMRI解析）、Q-som-04（低优先：盲文S1扩展与视觉皮层跨模态重映射因果顺序）

**解决的悬空引用**：somatosensory-cortex（被 thalamus, language-network 隐式引用；现有明确源页面）；barrel-cortex（被 critical-period 隐式引用）

**图谱**：171 节点（+6：somatosensory-cortex, barrel-cortex, mechanoreceptors-skin, cortical-homunculus, cortical-remapping, dorsal-column-pathway），974 边（+27 条新边）

---

## 2026-07-18 · 文章 #86 · 大脑如何读懂音调：从耳蜗行波到初级听觉皮层的音调拓扑图

**核心主题**：听觉系统双重频率编码策略——位置编码（基底膜行波+OHC Prestin主动放大+TMC1分子梯度）与时间精细结构编码（IHC带状突触+听神经相位锁定）；初级听觉皮层A1全局音调拓扑与局部复杂感受野异质性；core-belt-parabelt层级时间组织；A1与A2并行功能分工。

**新建页面（4）**：
- `systems/auditory-cortex.md` rev1 — 初级听觉皮层（A1）：全局音调拓扑梯度；局部复杂感受野异质性（Gaucher 2020）；core-belt-parabelt chronotopy（Benner 2023）；A1/A2并行双流（Kline 2023）（established, confidence:high）
- `concepts/tonotopy.md` rev1 — 音调拓扑：三层机制（基底膜力学/TMC1分子梯度/皮层梯度）；OHC Prestin主动放大（Fisher 2012因果证明）；皮层全局秩序与局部异质性张力（established, confidence:high）
- `concepts/ribbon-synapse.md` rev1 — 带状突触：RIBEYE蛋白/CaV1.3触发；Pillar vs Modiolar侧异质性；三型SGN（Ia/Ib/Ic）；动态范围分解原理（Moser 2023 EMBO J）（established, confidence:high）
- `concepts/phase-locking.md` rev1 — 相位锁定：IHC膜时常数决定上频限（~3 kHz）；时间精细结构（TFS）vs 时间包络编码；人工耳蜗TFS缺失的语音感知影响（established, confidence:high）

**修订页面（0）**：今日无修订现有页面。

**矛盾登记（0）**：今日无新增矛盾（听觉系统核心机制均为高度确立知识）。

**新增开放问题（4）**：Q-aud-01（高优先：人类相位锁定上频限）、Q-aud-02（中优先：A1局部异质性功能意义）、Q-aud-03（中优先：Belt/Parabelt串行vs并行）、Q-aud-04（低优先：TMC1梯度发育机制）

**解决的悬空引用**：auditory-cortex（language-network、thalamus、olfactory-system页面中的隐式引用现有明确源页面）

**图谱**：165 节点（+4：auditory-cortex, tonotopy, ribbon-synapse, phase-locking），948 边（+16 条新边）

---

## 2026-07-17 · 文章 #85 · 一缕香气的旅行：嗅觉系统如何将化学分子转化为感知、记忆与情感

**核心主题**：嗅觉系统三层计算架构（受体层→嗅球层→梨状皮层层）；ORN单受体表达规则与五步转导级联（OR→Gαolf→AC III→cAMP→CNG→Anoctamin2）；嗅小球轴突汇聚图谱（~5000 ORN/嗅小球，小鼠）；无丘脑中转的独特解剖路径；梨状皮层符合探测与稀疏编码；嗅觉→皮层杏仁核直接通路（Proustian效应神经基础）。

**新建页面（3）**：
- `systems/olfactory-system.md` rev1 — 嗅觉系统：三层架构；无丘脑中转路径；组合编码；梨状皮层计算；Proustian效应（established, confidence:high）
- `concepts/olfactory-receptor-neuron.md` rev1 — 嗅觉受体神经元：单受体规则；五步转导级联（OR→Gαolf→AC III→cAMP→CNG通道→Anoctamin2 Cl⁻放大）；CaM双位点快速适应；终身再生（established, confidence:high）
- `concepts/olfactory-glomerulus.md` rev1 — 嗅小球：OR功能地图；~5000 ORN/嗅小球汇聚；僧帽vs簇状细胞功能分流；颗粒细胞侧抑制（established, confidence:high）

**修订页面（1）**：
- `systems/amygdala.md` rev3 — 新增嗅觉→皮层杏仁核直接通路（唯一不经丘脑的感觉-情绪通路）；related新增olfactory-system；key_sources新增PMID:19804753；source_articles新增文章#85

**矛盾登记（0）**：今日无新增矛盾。

**新增开放问题**：Q-olfact-01（高优先：OR排他性表达的表观遗传机制）、Q-olfact-02（中优先：梨状皮层语义/情感拓扑图）、Q-olfact-03（中优先：COVID-19相关嗅觉丧失神经修复机制）

**解决的悬空引用**：olfactory-receptor-neuron、olfactory-glomerulus（amygdala页面新增嗅觉通路填补"丘脑低路"相关空白）

**图谱**：161 节点（+3：olfactory-system, olfactory-receptor-neuron, olfactory-glomerulus），932 边（+12 条新边）

---

## 2026-07-16 · 文章 #84 · 意义的诞生地：前颞叶如何将感官碎片组装成概念

**核心主题**：ATL语义枢纽的计算机制深化（hub-and-spoke双层架构；ATL→spoke不对称广播；双侧ATL组织）；rTMS双离解因果证据（Pobric 2010）；C3连接约束认知模型（Chen 2017：ATL损伤→跨类别损伤是数学必然）；概念空间几何（内嗅皮层六重对称编码概念类别方向；mPFC编码类别距离）；DSI统一模型（Haga 2025 PNAS：后继者表征≡逐点互信息，网格细胞=概念细胞空间类比）；大型语言模型词嵌入与生物概念空间的几何比较。

**新建页面（2）**：
- `concepts/semantic-memory-hub.md` rev1 — 语义记忆枢纽（Hub-and-Spoke模型）：ATL→spoke不对称连接（t₁₉=5.11）；双侧ATL组织；C3计算模型；rTMS双离解（mainstream, confidence:high）
- `concepts/conceptual-space-geometry.md` rev1 — 概念空间几何：内嗅皮层六重对称概念导航编码；mPFC距离编码；DSI统一框架（SR≡PMI）；LLM类比（emerging, confidence:medium）

**修订页面（4）**：
- `concepts/anterior-temporal-lobe-hub.md` rev2 — 新增：ATL→spoke不对称连接（DCM t₁₉=5.11）、rTMS双离解因果证据、ATL双侧组织元分析、C3计算模型；新增连接至semantic-memory-hub和conceptual-space-geometry；Q-sem-01新增；关键证据表扩展至8行
- `concepts/grid-cells.md` rev2 — 新增"概念空间中的网格样编码"机制节（Bokeria 2021；Haga 2025 DSI模型）；新增连接至semantic-memory-hub和conceptual-space-geometry
- `concepts/embodied-semantics.md` rev2 — 新增C3模型对Hub-and-Spoke调和立场的计算支撑；新增连接至semantic-memory-hub和anterior-temporal-lobe-hub
- `concepts/cognitive-map.md` rev2 — 新增DSI统一计算框架节（Haga 2025，SR≡PMI等价）；新增概念空间fMRI证据行（Bokeria 2021）；新增连接至semantic-memory-hub和conceptual-space-geometry

**矛盾登记（0）**：LLM词嵌入空间与生物概念空间的拓扑等价性（Q-sem-02）及概念空间真实几何（Q-sem-01）登记为新开放问题，未达contested_claims阈值。

**新增开放问题**：Q-sem-01（高优先：概念空间真实几何，六边形网格是否是精确描述）、Q-sem-02（高优先：LLM词嵌入与生物概念空间的拓扑等价性）

**解决的悬空引用**：无新建悬空引用；所有连接指向已有节点或当日新建节点。

**图谱**：158 节点（+2：semantic-memory-hub, conceptual-space-geometry），920 边（+14 条新边）

---

## 2026-07-15 · 文章 #83 · 听懂一句话：大脑如何用双流网络将声音转化为意义

**核心主题**：语言双流模型深化（Hickok & Poeppel）——腹流（ATL语义枢纽→hub-and-spoke）与背流（Spt区→传导性失语症自然实验）的功能解剖；Fedorenko & Blank 2020对"Broca区不是自然种类"的重要证明（LANG/MD三成分分离）；Shain & Fedorenko 2020语言专属surprisal效应（仅在LANG网络，不在MD网络）；腹流四大白质束（IFOF/UF/ILF/MLF）的DES临床证据；ATL作为语义枢纽的病变-网络和EEG/MEG时序证据。

**新建页面（1）**：
- `concepts/anterior-temporal-lobe-hub.md` rev1 — 前颞叶语义枢纽：hub-and-spoke模型；语义痴呆为自然实验；ATL 0-250ms早期激活、角回 250-450ms晚期接管；fMRI磁敏感低估问题（established, confidence:high）

**修订页面（3）**：
- `systems/broca-area.md` rev2 — 重大修订：新增LANG/MD三成分框架（语言专属/多需求/发音）；更新一句话定义"Broca区不是自然种类"；新增四条独立证据；说明群体平均fMRI中的6mm混叠问题；依据Fedorenko & Blank 2020 (PMID:32160565)
- `circuits/ventral-language-stream.md` rev2 — 新增腹流四大白质束详细描述（IFOF/UF/ILF/MLF）及DES临床验证（Sefcikova 2022）；新增ATL语义枢纽为关键节点；新增三条证据表行（Zhao 2017, Farahibozorg 2022, Sefcikova 2022）
- `systems/language-network.md` rev4 — 新增LANG/MD网络分离（Fedorenko 2020）；新增语言专属预测编码（Shain 2020，surprisal仅在LANG网络）；新增ATL语义枢纽为腹流关键节点

**矛盾登记（0）**：今日无新增矛盾。背流在语言理解中的作用争议（Hickok vs 具身认知阵营）记录为已知争议点，在文章中并列呈现，但因两者研究条件差异大（清晰 vs 模糊语音），未达需登记 contested_claims 的阈值。

**新增开放问题**：Q-lang-01（极端囊 vs 弓状束腹侧段：语义理解的关键白质通路）、Q-lang-02（ATL fMRI低估问题的范围）、Q-lang-03（语言网络左侧化的发育机制）、Q-lang-04（ATL语义整合的计算机制）

**解决的悬空引用**：无（`[[anterior-temporal-lobe-hub]]` 新引用由同日新建页面填补）

**图谱**：156 节点（+1：anterior-temporal-lobe-hub），906 边（+6 条新边）

---

## 2026-07-14 · 文章 #82 · 欲望的叛变：成瘾如何在分子层面重写大脑的奖励规则

**核心主题**：成瘾的三阶段神经回路模型（Koob & Volkow 2016）、ΔFosB 作为持续分子开关（Nestler 2001）、激励显著性 wanting/liking 分离（Robinson & Berridge）、NAc 沉默突触成熟与渴望孵化（Lüscher & Malenka 2011；Ma & Dong 2016）、D2 受体下调与 allostatic 重设。

**新建页面（4）**：
- `diseases/substance-use-disorder.md` rev1 — 物质使用障碍（成瘾）：三阶段模型（基底节/扩展杏仁核/PFC）；超生理 DA 冲击；D2 下调；习惯系统的病理极端（established, confidence:high）
- `concepts/deltaFosB.md` rev1 — ΔFosB 成瘾分子开关：截短机制/稳定性；NAc D1-MSN 选择性积累；CDK5/GluA2/dynorphin/G9a 下游靶点；与 CREB 的拮抗（established, confidence:high）
- `concepts/incentive-salience.md` rev1 — 激励显著性：wanting（多巴胺/中脑边缘）vs liking（阿片/内源大麻素）的神经分离；L-DOPA 实验；cue-triggered wanting（mainstream, confidence:medium）
- `concepts/incubation-of-craving.md` rev1 — 渴望孵化：沉默突触三阶段动态；CP-AMPA 插入（6-7 周峰值）；BLA→NAc 投射特异性；光遗传 LTD 重沉默实验（Ma & Dong 2016）（established, confidence:high）

**修订页面（2）**：
- `concepts/habit-formation.md` rev2 — 补充成瘾作为习惯系统病理极端的机制解释（ΔFosB/NAc CP-AMPA + 激励显著性解耦）；updated related 字段（addiction → substance-use-disorder, deltaFosB, incentive-salience）；Q-habit-01 部分解答
- `concepts/dopamine-reward-prediction-error.md` rev7 — 新增 DA-RPE 系统在成瘾中的 allostatic 崩溃（超生理冲击 20x、D2 下调 PET 证据、wanting/liking 分离）；新增关联 substance-use-disorder、incentive-salience、deltaFosB

**矛盾登记（0）**：未登记新矛盾。ΔFosB 的适应性 vs 促成瘾效应（GluA2↑ 保护 vs CDK5↑ 促进）记录为 Q-addiction-02（未解问题），未达 contested 标准（两种效应非直接冲突，而是同一转录因子的不同下游通路）。

**新增开放问题**：Q-addiction-01（成瘾记忆的消除 vs 覆盖）、Q-addiction-02（ΔFosB 适应性 vs 促成瘾效应的边界）；Q-habit-01 部分解答（成瘾不可逆性的双层机制）

**解决的悬空引用**：`[[addiction]]`（habit-formation 页面中的引用现已由 substance-use-disorder 填补，并更新为正确 slug）

**图谱**：155 节点（+4：substance-use-disorder, deltaFosB, incentive-salience, incubation-of-craving），900 边（+31 条新边）

---

## 2026-07-13 · 文章 #81 · 行动的仲裁者：纹状体如何决定你该动还是不动，以及习惯是如何在神经回路中悄然生长的

**核心主题**：基底节直接/间接通路的光遗传学因果证据（Kravitz 2010）、Haber螺旋-上升模型、背内侧（目标导向）vs背外侧（习惯）纹状体功能分化、括号化神经动力学（Jog 1999）、演员-批评家计算架构。

**新建页面（2）**：
- `concepts/habit-formation.md` rev1 — 习惯形成（目标导向vs习惯性行为）：DMS/DLS解剖分工；奖励贬值测试范式；括号化机制（Jog 1999）；prelimbic/infralimbic PFC分工；Piray 2016人类白质证据（established, confidence:high）
- `concepts/actor-critic-model.md` rev1 — 演员-批评家模型：NAc=批评家（TD误差）；背侧纹状体=演员（策略更新）；model-based（DMS）vs model-free（DLS）双轨；Haber螺旋作为架构基础（mainstream, confidence:medium）

**修订页面（2）**：
- `circuits/basal-ganglia.md` rev2 — 新增Kravitz 2010光遗传因果证据（直接/间接通路的第一强因果验证）；Haber螺旋-上升模型（三层功能区划+级联结构）；DMS/DLS习惯/目标导向分工表格；演员-批评家框架作为计算解释；新增关联habit-formation, actor-critic-model, prefrontal-cortex; Q-bg-habit-goal-split部分解答；新增Q-actor-critic-01/02
- `concepts/dopamine-reward-prediction-error.md` rev6 — 明确DA-RPE作为演员-批评家框架中批评家信号的解剖角色；SNc→背侧纹状体传递路径说明；model-free演员（DLS）S-R权重稳定性的计算解释；新增关联actor-critic-model, habit-formation

**矛盾登记（0）**：Go/NoGo二分法受到Soares-Cunha 2016的批判，但未达到contested标准（知识库内已有dual-pathway模型，观点分歧属于精化而非矛盾）

**新增开放问题**：Q-habit-01、Q-habit-02、Q-actor-critic-01、Q-actor-critic-02；Q-bg-habit-goal-split部分解答（病变行为证据明确；分子切换机制仍未解）

**新增悬空引用（待补）**：`[[addiction]]`（habit-formation页面引用，暂无对应节点）；`[[prefrontal-cortex]]`（已有概念，但无专属页面）

**图谱**：151 节点（+2：habit-formation, actor-critic-model），880 边（估算，+11条主要新边）

---

## 2026-07-12 · 文章 #80 · 世界的倒影：大脑皮层反馈连接之谜与预测编码的统一框架

**核心主题**：预测编码作为大脑统一计算框架——从视觉皮层感受野效应到听觉皮层省略响应神经元（Yaron 2025）到多巴胺精度加权（Haarsma 2020），整合前79篇文章的碎片知识。

**新建页面（0）**：无新页（所有核心概念已有页面）

**修订页面（3）**：
- `theories/predictive-coding.md` rev6 — 新增 Yaron 2025（PEONs，听觉省略响应，13%神经元，ρ=0.34）直接单细胞证据；新增 Haarsma 2020（舒必利破坏额上回精度加权，FEP患者无精度加权）药理因果证据；新增 LHb 作为奖励域"省略响应"类比；Q-pc-06（PEONs 自然感知泛化性）；related 新增 lateral-habenula
- `concepts/precision-weighting.md` rev2 — 新增 Haarsma 2020 直接药理证据（列入关键证据表）；Q-prec-02（LHb负误差精度加权）；related 新增 lateral-habenula；dimensions 新增 disease
- `concepts/dopamine-reward-prediction-error.md` rev5 — 明确 DA-RPE 作为预测编码框架在奖励域的神经货币化实现；补充精度加权完整链路说明

**矛盾登记（0）**：无新矛盾（Hodson 2024 提示预测编码证据有限，记录为理论层面不确定性，未达 contested 标准）

**新增开放问题**：Q-pc-06、Q-prec-02

**新增悬空引用（待补）**：无（所有引用的 slug 均已有节点）

**图谱**：149 节点，869 边（+3 边：predictive-coding↔lateral-habenula, precision-weighting→lateral-habenula）

---

## 2026-07-11（文章 #79·大脑的"惩罚计算器"·外侧缰核与抑郁症）

**源文章**：[[2026-07-11-lateral-habenula-depression-ketamine]] —《大脑的"惩罚计算器"：外侧缰核如何将厌恶信号翻译为抑郁，以及氯胺酮为何能在数小时内打破这个恶性循环》

**新建页面（3 页）**：
- `systems/lateral-habenula.md`：外侧缰核——上丘脑进化保守核团，编码负向奖励预测误差，通过LHb→RMTg→DA和LHb→DRN→5-HT两条并行路径压制单胺能系统；抑郁中三重分子改变（βCaMKII↑、Kir4.1失调、突触前增益↑）驱动病理性爆发放电；氯胺酮NMDAR使用依赖性捕获机制（established, confidence:high）
- `systems/rmtg.md`：喙内侧被盖核——LHb到多巴胺神经元的GABA能中继站；接受LHb谷氨酸能输入，输出GABA抑制至VTA/SNc（established, confidence:high）
- `concepts/burst-firing-lhb.md`：外侧缰核爆发放电（抑郁机制）——LHb从正常紧张性放电转为病理性爆发；需NMDAR+T型Ca²⁺共同激活；氯胺酮使用依赖性捕获的分子靶点；与视丘爆发放电的机制同源但功能意义相反（established, confidence:high）

**修订页面（2 页）**：
- `concepts/dopamine-reward-prediction-error.md`（rev3→rev4）：补充DA负预测误差的回路底物——LHb→RMTg→DA三节点链；将LHb连接到DA-RPE框架的负向臂；新增related: lateral-habenula, rmtg
- `concepts/hpa-axis.md`（rev1→rev2）：补充HPA轴-外侧缰核双向耦合：PVN（CRH）→LHb兴奋性输入，以及LHb激活→HPA轴维持；新增related: lateral-habenula

**图谱更新**：新增 3 节点（lateral-habenula, rmtg, burst-firing-lhb）、11 条边；总计 149 节点，866 边

**新登记矛盾（1 个）**：
- C-2026-07-11-01（open）：NMDA受体是否对LHb爆发放电必要——Yang 2018（必要）vs 2026年Frontiers新论文（可能非必要）

**新增未解问题（4 个）**：
- Q-lhb-01（高优先）：LHb是否是氯胺酮起效的唯一关键位点？代谢产物在海马/PFC的AMPAR作用多大？
- Q-lhb-02（高优先）：NMDA受体是否是LHb爆发放电的必要条件（2026年新争议）？
- Q-lhb-03（中优先）：Kir4.1失调的上游触发器——慢性应激如何通过GR改变星形胶质细胞Kir4.1？
- Q-lhb-04（中优先）：不同抑郁亚型中LHb活动特征的异质性

**新增悬空引用（待补）**：
- `t-type-calcium-channels-thalamus`：T型Ca²⁺通道专页（burst-firing-lhb prerequisites中提及）

---

## 2026-07-10（文章 #78·当卫士变成刽子手·神经炎症与突触损伤）

**源文章**：[[2026-07-10-neuroinflammation-synaptic-damage]] —《当卫士变成刽子手：神经炎症如何从突触守护走向突触破坏》

**新建页面（2 页）**：
- `concepts/neuroinflammation.md`：神经炎症（CNS）——小胶质细胞/星形胶质细胞过度激活引发的 CNS 慢性低水平炎症；三阶段病理转变（免疫监视→急性保护→慢性损伤）；M1/M2 极化；Aβ 触发 C1q 补体重激活；CRH/肥大细胞桥接 HPA 轴；小胶质细胞预激（established, confidence:high）
- `concepts/inflammatory-cytokines-synapse.md`：炎症细胞因子对突触的损伤机制——浓度依赖性双向效应（低水平促 LTP，高水平损伤）；TNF-α（TNFR2→AMPA↑，TNFR1/NF-κB→GluA1 内吞）；IL-1β（p38 MAPK→GluA1 Ser831 去磷酸化 + NR2B 选择性↓ + 突触前谷氨酸↓）；IL-6（gp130/STAT3→Arc 过激活 + BDNF-TrkB 阻断）；TREM2 R47H→TNF-α↑→LTP 受损（established, confidence:high）

**修订页面（3 页）**：
- `neurons/microglia.md`（rev1→rev2）：合并 wiki/systems/microglia.md 的神经炎症内容；新增 CX3CR1-CX3CL1 稳态轴、激活态三路细胞因子损伤、DAM/TREM2 双重角色、慢性应激→小胶质细胞预激；扩展 related/opens_questions/key_sources；填补 2026-06-03 创建后遗留的神经炎症盲区
- `concepts/glucocorticoid-hippocampus-plasticity.md`（rev1→rev2）：新增慢性应激→CRH/GC→小胶质细胞预激→神经炎症间接损伤路径；related 新增 neuroinflammation/microglia/inflammatory-cytokines-synapse
- `diseases/alzheimers-disease.md`（rev7→rev8）：新增"神经炎症：AD 突触损伤的早期共同驱动力"完整机制节；related 新增 neuroinflammation/inflammatory-cytokines-synapse；key_sources 新增 PMID:20970492、PMID:37575021、PMID:32579116

**图谱更新**：新增 3 节点（neuroinflammation, inflammatory-cytokines-synapse, trem2）、41 条边；总计 146 节点，855 边

**新登记矛盾**：无

**新增未解问题（4 个）**：
- Q-inflam-01（高优先）：小胶质细胞预激的可逆性边界
- Q-inflam-02（高优先）：AD 脑内细胞因子局部浓度是否真正达到损伤 LTP 的阈值
- Q-inflam-03（高优先）：TREM2 激动剂在 AD 早期的突触保护证据
- Q-inflam-04（中优先）：炎症细胞因子是否优先损伤 PV+ 中间神经元

**新增悬空引用（待补）**：
- `trem2`：TREM2 受体专页（已作为图谱节点登记）
- `disease-associated-microglia`：DAM 疾病相关小胶质细胞专页

---

## 2026-07-09（文章 #77·应激的双刃剑·糖皮质激素与海马可塑性 MR/GR 双相调节）

**源文章**：[[2026-07-09-stress-glucocorticoid-hippocampus-hpa-axis]] —《应激的双刃剑：糖皮质激素如何让海马在压力下先锐化、后崩溃》

**新建页面（2 页）**：
- `concepts/hpa-axis.md`：下丘脑-垂体-肾上腺轴——PVN→垂体→肾上腺皮质 CRH→ACTH→皮质醇三步信号链；海马/杏仁核/PFC 对 PVN 的差异性调控；三速负反馈机制（快速/中速/慢速）；超日节律（每60-90分钟脉冲）与昼夜节律双时间结构；Sapolsky 1986 糖皮质激素级联假说；SCN→皮质醇节律的起搏器角色（established, confidence:high）
- `concepts/glucocorticoid-hippocampus-plasticity.md`：糖皮质激素与海马可塑性（MR/GR 双相调节）——MR（Kd≈0.5nM）/GR（Kd≈5nM）双受体亲和力与占用率对比表；MR 主导相（非基因组 AMPA 上调/基因组 BDNF 维持）；急性 GR 相（eCB/CB1R 去抑制 + 时空特异性增强原则）；慢性 GR 相（BDNF exon IV 负调控/PP2B-GluA1 内吞/CaMKII↓）；CA3 树突退缩细胞机制（NMDA 过激活/CRH 毒性/MAP2 去磷酸化）；8 行关键证据表（Conrad 2008 因果；Lupien 1998 人类纵向）（established, confidence:high）

**修订页面（5 页）**：
- `systems/amygdala.md`（rev1→rev2）：新增"应激下杏仁核-海马方向性分离"段落（慢性应激→BLA树突增生 vs CA3退缩；Kim & Diamond 2002证据）；CeM→PVN→HPA轴输出路径扩展；related 新增 hpa-axis、glucocorticoid-hippocampus-plasticity；opens_questions 新增 Q-stress-01；连接新增两条
- `concepts/hippocampal-neurogenesis.md`（rev3→rev4）：新增"糖皮质激素对神经发生的抑制"机制段落（GR→VEGF/IGF-1/5-HT1A 通路抑制；SGZ 增殖↓40-50%；BDNF 间接路径；Conrad 2008 可逆性证据）；related 新增 hpa-axis、glucocorticoid-hippocampus-plasticity；key_sources 新增 PMID:19317179、PMID:26286651；连接新增两条
- `concepts/ltp.md`（rev11→rev12）：新增"糖皮质激素双相调节 LTP"完整机制段落（MR 促进/急性 GR 时空特异/慢性 GR 损害三相；BDNF 下调、PP2B/calcineurin/GluA1 内吞；与 AD 汇聚点）；related 新增 glucocorticoid-hippocampus-plasticity、hpa-axis；key_sources 新增 PMID:15891777、PMID:26286651；连接新增两条
- `concepts/bdnf.md`（rev2→rev3）：新增"慢性应激/糖皮质激素对 BDNF 的抑制"段落（GR 负性 GRE→BDNF exon IV↓30-50%；L-LTP 失败和神经发生减少双重后果；HPA 失调链条）；related 新增 glucocorticoid-hippocampus-plasticity、hpa-axis；key_sources 新增 PMID:15891777、PMID:19317179；连接新增两条
- `diseases/alzheimers-disease.md`（rev6→rev7）：新增"糖皮质激素级联假说与 AD"段落（SCN 退化→皮质醇节律崩溃→慢性 GC→海马损伤→负反馈减弱正反馈环；双重攻击汇聚机制；Lupien 1998 人类纵向证据）；related 新增 hpa-axis、glucocorticoid-hippocampus-plasticity、circadian-clock；key_sources 新增 PMID:3527687、PMID:15891777、PMID:10195112；opens_questions 新增 Q-stress-02；连接新增三条

**图谱更新**：新增 2 节点（hpa-axis, glucocorticoid-hippocampus-plasticity）、20 条边；总计 140 节点，814 边

**新登记矛盾**：无（GC 双相效应的浓度阈值在不同海马亚区可能有差异，已记录为 Q-stress-01 研究前沿而非知识库内矛盾）

**新增未解问题（3 个）**：
- Q-stress-01（中优先）：慢性应激海马损伤的可逆性边界——Cushing 恢复 10%、PTSD 部分恢复，但叠加 Aβ 的可逆性阈值未知
- Q-stress-02（高优先）：慢性压力是 AD 的因还是果？海马萎缩先于还是后于 Aβ 积累？纵向因果时序问题
- Q-stress-03（中优先）：慢性 GC 是否首先通过损伤 PV+ 中间神经元（破坏 E/I 平衡）间接损害 LTP，而非直接作用于锥体细胞？

**新增悬空引用（待补）**：无（所有连接指向已有节点）

---

## 2026-07-08（文章 #76·大脑的 24 小时时钟·昼夜节律与 SCN 主时钟）

**源文章**：[[2026-07-08-circadian-clock-scn-brain-rhythm]] —《大脑的 24 小时时钟：视交叉上核如何用分子振荡设定时间，协调睡眠、记忆与衰老》

**新建页面（2 页）**：
- `concepts/circadian-clock.md`：昼夜节律分子振荡器（TTFL）——CLOCK/BMAL1 E-box 激活→PER/CRY 负反馈→CKIδ/ε 磷酸化延迟产生约 24h 振荡；REV-ERB/ROR 辅助稳定回路；温度补偿；FASPS 遗传证据（CKIδ T44A）；全身细胞自主振荡；CLOCK/BMAL1 调控 PV+ 成熟和关键期时序（Reh 2020）（established, confidence:high）
- `systems/scn-circadian-pacemaker.md`：视交叉上核（SCN 主时钟）——ipRGC/黑视素→RHT→VIP 核心区→AVP 壳区；VIP/VPAC2 细胞间耦合同步；三条输出路径（自主神经→褪黑素、神经投射→LC/VLPO/DMH、体液 AVP/PROK2）；SCN 移植实验（Ralph 1990）；星形胶质细胞时钟（Brancaccio 2019）；AD 中 SCN VIP 神经元早期萎缩（established, confidence:high）

**修订页面（6 页）**：
- `concepts/rem-sleep.md`（rev1→rev2）：新增"昼夜节律对 REM 睡眠的时序门控"小节（后半夜 REM 优势的 SCN 门控、两过程模型、PTSD 脆弱性含义）；related 新增 circadian-clock、scn-circadian-pacemaker；key_sources 新增 PMID:12198538、PMID:7185792
- `concepts/memory-consolidation.md`（rev6→rev7）：新增"昼夜节律对记忆巩固的时间门控"小节（LTP 昼夜波动、BMAL1 KO 学习损伤、AD SCN 萎缩→记忆功能下降双重恶化）；related 新增 circadian-clock、scn-circadian-pacemaker；key_sources 新增 PMID:12198538
- `systems/glymphatic-system.md`（rev1→rev2）：连接节新增 circadian-clock、scn-circadian-pacemaker、norepinephrine-locus-coeruleus 三条路径说明（胶质淋巴清洗的昼夜节律门控机制经 SCN→LC→NE 振荡路径）；key_sources 新增 PMID:19798445
- `concepts/cortical-slow-oscillation.md`（rev2→rev3）：连接节新增 circadian-clock、scn-circadian-pacemaker（两过程模型将 SO 丰富的慢波睡眠定时于前半夜）；key_sources 新增 PMID:7185792
- `systems/neuromodulator-systems.md`（rev3→rev4）：新增"昼夜节律对神经调质系统的协调"小节（四大调质系统昼夜节律模式 × SCN 调控路径一览表；大脑时间依赖工作模式切换架构）；related 新增 circadian-clock、scn-circadian-pacemaker、glymphatic-system
- `concepts/critical-period.md`（rev1→rev2）：连接节新增 circadian-clock（Reh 2020：CLOCK/BMAL1→PV+ 成熟速率→关键期时间轴）；related 新增 circadian-clock；key_sources 新增 PMID:32503914

**图谱更新**：新增 2 节点（circadian-clock, scn-circadian-pacemaker）、22 条边；总计 138 节点，794 边

**新登记矛盾**：无（昼夜节律局部时钟 vs SCN 主时钟的相对贡献争议已记录为 Q-circ-01）

**新增未解问题（3 个）**：
- Q-circ-01（高优先）：局部脑区时钟（海马、PFC）与 SCN 主时钟的相对贡献——SCN 萎缩后局部时钟能否部分代偿？
- Q-circ-02（高优先）：定时光照 + 褪黑素干预能否稳定昼夜节律进而延缓 AD Aβ 积累？III 期 RCT 证据缺失。
- Q-circ-03（中优先）：SCN 星形胶质细胞独立功能时钟（Brancaccio 2019）在 AD 反应性胶质增生中的功能改变？

**新增悬空引用（待补）**：无（所有连接指向已有节点或新建节点）

---

## 2026-07-07（文章 #75·三重协奏·SO-纺锤波-SWR 与 SHY 假说）

**源文章**：[[2026-07-07-sleep-memory-consolidation-so-spindle-swr]] —《三重协奏：皮层慢振荡如何指挥纺锤波与海马涟漪，把白天的经历刻入长期记忆》

**新建页面（2 页）**：
- `concepts/so-spindle-swr-coupling.md`：SO-纺锤波-SWR 三重耦合——SO（主时钟）→纺锤波（皮层预热，L型Ca²⁺窗口）→SWR（记忆写入，纺锤波波谷）的时间嵌套机制；Maingret 2016 闭环刺激因果证明；Helfrich 2018 老龄化耦合精度下降（d=1.19）；神经调质（NE/DA/ACh）调节（established, confidence:high）
- `concepts/shy-hypothesis.md`：突触稳态假说（SHY）——清醒 LTP 积累→睡眠期 SO 驱动整体突触下调（de Vivo 2017：ASI 缩小~18%）；down-selection 框架：被 SWR 重播激活的突触受保护；与 Turrigiano 突触稳态缩放的区别；Q-shy-molecular-mechanism 未解问题（mainstream, confidence:medium）

**修订页面（3 页）**：
- `concepts/memory-consolidation.md`（rev5→rev6）：新增 so-spindle-swr-coupling、shy-hypothesis 两个 related 节点；新增 Helfrich 2018 和 de Vivo 2017 证据行；Q-shy-vs-active-consolidation 部分解决（通过 down-selection 框架）；source_articles 新增 2026-07-07 文章
- `concepts/sleep-spindles.md`（rev1→rev2）：新增 Helfrich 2018 SO-纺锤波相位精度证据行（d=1.19；老年相位偏移 46.3°）；related 新增 so-spindle-swr-coupling；source_articles 新增 2026-07-07 文章
- `concepts/sharp-wave-ripples.md`（rev5→rev6）：新增 Maingret 2016 闭环刺激因果证据行（PMID:27182818）；related 新增 so-spindle-swr-coupling；source_articles 新增 2026-07-07 文章

**图谱更新**：新增 2 节点（so-spindle-swr-coupling, shy-hypothesis）、18 条边；总计 136 节点，772 边

**新登记矛盾**：无（SHY vs 主动巩固的对立通过 down-selection 框架部分调和；已记录为 Q-shy-vs-active-consolidation 部分解答）

**新增/更新未解问题（3 个）**：
- Q-replay-human-translation（高优先）：人类直接因果实验（闭环增强三重耦合）能否复现大鼠结果？
- Q-shy-molecular-mechanism（高优先）：SO UP state 驱动突触 LTD 的分子触发器是 NMDAR 阈下 Ca²⁺、mGluR 还是内源性大麻素系统？
- Q-shy-vs-active-consolidation（已部分解答）：down-selection 框架调和了两者，但单突触层面直接追踪"被保护 vs 被下调"突触的实验仍缺失

**新增悬空引用（待补）**：
- `locus-coeruleus`：蓝斑核独立条目（so-spindle-swr-coupling 和 shy-hypothesis 均提及 NE 调节，目前无独立页面）

---

## 2026-07-06（文章 #74·大脑的夜间清洗工程·胶质淋巴系统与睡眠废物清洗）

**源文章**：[[2026-07-06-glymphatic-system-sleep-clearance]] —《大脑的夜间清洗工程：胶质淋巴系统如何在睡眠中清除阿尔茨海默病的始动毒素》

**新建页面（2 页）**：
- `systems/glymphatic-system.md`：胶质淋巴系统——CSF 沿动脉旁间隙入流、经星形胶质细胞终足 AQP4 穿越脑实质、沿静脉旁出流；蓝斑核 NE 振荡驱动慢性血管运动为主要驱动力；深度 NREM 睡眠期高效运转；AQP4 KO→70% 清除效率下降（mainstream, confidence:medium）
- `concepts/aqp4.md`：AQP4 水通道蛋白 4——高度极化富集于星形胶质细胞终足；CSF-ISF 对流的分子水门；AQP4 去极化是衰老导致胶质淋巴衰退的分子基础（established, confidence:high）

**修订页面（3 页）**：
- `systems/astrocyte.md`（rev2→rev3）：新增第六大功能（胶质淋巴功能）：终足 AQP4 极化驱动 CSF-ISF 对流交换；dimensions 新增 whole-brain-network；related 新增 glymphatic-system、aqp4；key_sources 新增 PMID:22896675
- `diseases/alzheimers-disease.md`（rev5→rev6）：新增关键机制节"胶质淋巴清除失效：AD 的上游功能原因"（衰老三重削弱 + 蓝斑核双重角色 + 人类直接证据）；related 新增 glymphatic-system、aqp4；opens_questions 新增 Q-glyph-01/02；key_sources 新增 PMID:22896675/30679382/19779148/41593094
- `concepts/cortical-slow-oscillation.md`（rev1→rev2）：新增 NREM 慢波睡眠同时驱动记忆巩固和胶质淋巴清洗的双重功能连接；related 新增 glymphatic-system、alzheimers-disease；key_sources 新增 PMID:39788123

**图谱更新**：新增 2 节点（glymphatic-system, aqp4）、10 条边；总计 134 节点，754 边

**新登记矛盾**：无（对流 vs 扩散增强之争是已知争议，但两派均同意睡眠增强清洗这一核心事实，不构成全面对立的 contested_claim；保留为未解问题）

**新增未解问题（4 个）**：
- Q-glyph-01（高优先级）：蓝斑核 NE 振荡的最优频率是什么？~0.05 Hz 是最优还是副产物？
- Q-glyph-02（高优先级）：AQP4 去极化在衰老中的分子触发器？M23/M1 比例是否可药物干预？
- Q-glyph-03（中优先级）：胶质淋巴系统对 α-突触核蛋白、TDP-43 等其他聚集蛋白的选择性
- Q-glyph-04（中优先级）：唑吡坦等安眠药长期使用对胶质淋巴清洗的量化影响

**新增悬空引用（待补）**：
- `locus-coeruleus`：蓝斑核独立条目（glymphatic-system 和 tau-pathology 均引用，目前只有 locus-coeruleus-anatomy 待建记录）

---

## 2026-07-05（文章 #73·记忆的竞争法庭·神经元分配与记忆联结机制）

**源文章**：[[2026-07-05-engram-allocation-memory-competition]] —《记忆的竞争法庭：大脑如何选定那些承载记忆的神经元》

**新建页面（2 页）**：
- `concepts/memory-allocation.md`：神经元分配——CREB/内在兴奋性竞争决定哪些神经元进入印迹；零和竞争；PV+侧向抑制赢家通吃；表观遗传前置层（H3K27ac）；训练后5min巩固窗口（mainstream, confidence:high）
- `concepts/memory-linking.md`：记忆联结——时间接近（~6h）的两段学习因共享高兴奋性印迹神经元而实现联结；Cai 2016 CA1钙成像直接证据；老年小鼠CA1兴奋性下降→联结缺陷→DREADD救援；scFLARE2精确时间边界（3h vs 27h）（emerging, confidence:medium）

**修订页面（1 页）**：
- `concepts/engram-cells.md`（rev4→rev5）：related新增 memory-allocation、memory-linking、pv-interneurons；key_sources新增 PMID:29709212、27251287、41470040；修订历史追加2026-07-05条目；source_articles新增2026-07-05文章

**图谱更新**：新增 2 节点（memory-allocation, memory-linking）、16 条边；总计 135 节点，770 边

**新登记矛盾**：无（CREB内源性波动是否足以影响自然分配——Q-alloc-01尚不构成正式矛盾，标记为未解问题）

**新增未解问题（3 个）**：
- Q-alloc-01（高优先级）：内源性CREB活性波动是否足以在自然学习中真实影响分配？
- Q-alloc-02（高优先级）：记忆联结时间窗（~6h）的分子决定因素和跨物种差异
- Q-alloc-03（中优先级）：H3K27ac等表观遗传标记是否可作为记忆增强干预靶点？

**新增悬空引用（待补）**：
- `creb`：CREB 蛋白（被 memory-allocation 多次引用，尚无独立 wiki 节点）
- `intrinsic-excitability`：内在兴奋性稳态（被 memory-allocation、memory-linking 引用，尚无独立页面）

---

## 2026-07-04（文章 #54·信号与噪声之间·皮层 E/I 平衡与 PV 中间神经元守门机制）

**源文章**：[[2026-07-04-ei-balance-pv-interneuron]] —《信号与噪声之间：皮层 E/I 平衡的回路逻辑、PV 中间神经元的守门机制与大脑"刹车"的分子基础》

**新建页面（2 页）**：
- `concepts/ei-balance.md`：兴奋-抑制平衡——皮层回路信噪比控制机制；PV+/SST+/VIP+ 三类中间神经元分工维持；多维度（非单一数字）；ASD/精神分裂症/癫痫的共同汇流点；关键证据：Sohal & Rubenstein 2019（mainstream, confidence:medium）
- `concepts/perineuronal-nets.md`：围神经元网——包裹 PV+ 细胞的细胞外基质网络；aggrecan+透明质酸+连接蛋白；OTX2 正反馈驱动 PV 成熟；固化 AMPA 受体；ChABC 可逆转关键期（动物）（established, confidence:high）

**修订页面（3 页）**：
- `circuits/pv-interneurons.md`（rev2→rev3）：新增 E/I 平衡执行者角色、关键期初始靶点（Quast & Hensch 2023）、PNN 固化机制、神经炎症脆弱性（Allami 2025）；related 新增 ei-balance/perineuronal-nets；key_sources 新增 3 个
- `concepts/gamma-oscillations.md`（rev2→rev3）：新增伽马振荡作为 E/I 平衡动态读出的维度；关键期 γ 瞬态爆发（Quast & Hensch 2023）；related 新增 ei-balance/perineuronal-nets；来源文章新增
- `concepts/homeostatic-plasticity.md`（rev1→rev2）：新增与 E/I 平衡的互补关系（慢速 vs 快速机制）；related 新增 ei-balance

**新登记矛盾**：无（E/I 失衡方向在 ASD 中存在争议，已在文章和 wiki 中标注为待解问题，暂不登记矛盾）

**新增未解问题（3 个）**：
- Q-ei-balance-01（高优先级）：如何精准非侵入性测量人类特定皮层 E/I 状态？
- Q-ei-balance-02（高优先级）：ASD 中 E/I 失衡方向的异质性——不同基因突变的回路变化方向一致吗？
- Q-ei-balance-03（中优先级）：VIP+ 去抑制回路调制 E/I 平衡的精确时序和幅度

**新增悬空引用（待补）**：
- `critical-period`：关键期（从 perineuronal-nets、ei-balance 页面引用，尚未独立成页）
- `intrinsic-excitability`：内在兴奋性稳态（homeostatic-plasticity 页面的第二大类型，尚未独立页面）

**图谱更新**：新增节点 2（ei-balance, perineuronal-nets）；新增边 14；总计 **132 节点、744 条边**

---

## 2026-06-03（文章 #70·大脑的"质检员"·小胶质细胞与补体介导的突触剪枝）

**源文章**：[[2026-06-03-microglia-synaptic-pruning]] —《大脑的"质检员"：小胶质细胞如何用补体分子标签精雕突触回路》

**新建页面（3 页）**：
- `neurons/microglia.md`：小胶质细胞——CNS 常驻免疫细胞，发育期突触剪枝执行者；CR3（C3b识别）+ TREM2（PS识别）双通路；活动依赖性（TTX实验）；疾病连接（AD C1q重激活、精神分裂症 C4A 过度表达）（established）
- `concepts/synaptic-pruning.md`：突触剪枝——先多建再精删策略；"吃我"（C3b/PS）+"别吃我"（CD47）双向信号博弈；视网膜膝状核模型（C1QA/C3 KO 眼特异性分离失败）；发育窗口：dLGN P2-P10、海马 P15、前额叶青春期（established）
- `concepts/complement-cascade-cns.md`：补体级联（CNS突触功能版）——C1q→C4→C3b的步骤；TGF-β（星形胶质细胞）→C1q（神经元）的跨细胞诱导轴；发育期/成年期的活性差异；AD和精神分裂症中的病理失调（established）

**修订页面（1 页）**：
- `diseases/alzheimers-disease.md`（rev4→rev5）：新增 C1q 补体介导的早期突触丢失机制（Hong et al. 2016，PMID:27033548）：Aβ低聚体触发C1q早期突触沉积（早于斑块）；related 新增 microglia/complement-cascade-cns/synaptic-pruning；key_sources 新增 PMID:27033548

**新登记矛盾**：无

**新增悬空引用（待补）**：
- `critical-period`：关键期（发育期 E/I 平衡与突触剪枝直接关联）
- `cx3cr1`：fractalkine 受体——趋化因子-微胶质轴（影响海马剪枝，Soteros 2022）
- `megf10` / `mertk`：星形胶质细胞自身的突触吞噬受体（非微胶质依赖的并行剪枝通路）

**图谱更新**：新增节点 3（microglia, synaptic-pruning, complement-cascade-cns）；新增边 10；总计 **130 节点、~730 条边**

---

## 2026-07-03（文章 #69·突触稳态·赫布规则的稳定器）

**源文章**：[[2026-07-03-synaptic-scaling-homeostatic-plasticity]] —《突触稳态：当赫布规则失控时，大脑如何给自己"归零"》

**新建页面（2 页）**：
- `concepts/synaptic-scaling.md`：突触稳态缩放——乘法性负反馈；GluA2 通路（不同于 LTP 的 GluA1）；钙/CaMKIV 全细胞传感；树突局部视黄酸非基因组信号；星形胶质细胞 TNFα 许可因子；突触前 PHP（Sema3a）；记忆特异性雕刻（Wu 2021）（established）
- `concepts/homeostatic-plasticity.md`：稳态可塑性总概念页——三大类型（突触缩放/内在兴奋性/突触前稳态）；时间尺度隔离（小时/天 vs 秒/分）；功能：维护网络动态范围；与 Hebbian 规则形成互补稳定系统（established）

**修订页面（4 页）**：
- `concepts/ltp.md`（rev10→rev11）：在连接段新增 synaptic-scaling 和 homeostatic-plasticity；明确 GluA1（LTP）vs GluA2（稳态缩放）分子路径分叉；related 新增两条
- `concepts/hebbian-learning.md`（rev3→rev4）：在连接段新增 synaptic-scaling 和 homeostatic-plasticity；Q-hebbian-stability 更新为"部分有答案"状态；related 新增两条
- `concepts/ampa-receptor.md`（rev2→rev3）：在连接段新增 synaptic-scaling；明确 GluA2 通路为稳态缩放特异通路（Gainey 2009 证据）；related 新增两条
- `wiki/systems/astrocyte.md`（rev1→rev2）：在连接段新增 synaptic-scaling；揭示星形胶质细胞 TNFα 在稳态中的许可角色（双时间尺度分工：D-丝氨酸→LTP；TNFα→稳态）；related 新增两条

**新登记矛盾**：无（今日证据无与既有主张冲突）

**新增悬空引用**：`homeostatic-plasticity`（已立即建页）；`synaptic-scaling`（已立即建页）

**图谱更新**：新增节点 2（synaptic-scaling, homeostatic-plasticity）；新增边约 12；总计 **127 节点、~721 条边**

---

## 2026-07-02（文章 #68·大脑的第三方·星形胶质细胞与三方突触）

**源文章**：[[2026-07-02-astrocyte-tripartite-synapse]] —《大脑的第三方：星形胶质细胞如何改写突触的游戏规则》

**新建页面（6 页）**：
- `systems/astrocyte.md`：星形胶质细胞——三方突触第三方成员；PAPs 覆盖 57% 突触；EAAT2 清除 80% 谷氨酸；D-丝氨酸供给；Ca²⁺ 信号；LTP/LTD 必要参与者（established）
- `concepts/tripartite-synapse.md`：三方突触——Araque 1999 框架；双向神经元-星形胶质细胞信号；Ca²⁺-D-丝氨酸-NMDA 轴；LTP/LTD 的三方必要性（mainstream）
- `concepts/d-serine.md`：D-丝氨酸——NMDA 受体 GluN1 协同激动剂；星形胶质细胞来源；Ca²⁺ 依赖释放；LTP 的隐性必要条件（Henneberger 2010）（mainstream）
- `concepts/gliotransmitter.md`：胶质递质——D-丝氨酸/ATP/谷氨酸；三种释放机制；争议（medium confidence；C-2026-07-02-01）
- `concepts/astrocyte-calcium-signaling.md`：星形胶质细胞钙信号——mGluR-IP₃-ER 路径；钙波传播；门控 D-丝氨酸（established）
- `concepts/glutamate-glutamine-cycle.md`：谷氨酸-谷氨酰胺循环——EAAT2 清除；GS 转化；递质再生；防兴奋毒性（established）

**修订页面（2 页）**：
- `concepts/ltp.md`（rev9→rev10）：新增"三方突触条件"段落——星形胶质细胞 D-丝氨酸是 LTP 的隐性必要条件（Henneberger 2010 因果证据）；related 新增 astrocyte、tripartite-synapse、d-serine、astrocyte-calcium-signaling；连接段落新增四条
- `concepts/ltd.md`（rev2→rev3）：新增星形胶质细胞参与 LTD 的三条路径（D-丝氨酸/ATP-腺苷/eCB-CB1R）；related 新增 astrocyte、tripartite-synapse、gliotransmitter、d-serine；连接段落新增四条

**新登记矛盾（1 条）**：
- `C-2026-07-02-01（open）`：星形胶质细胞 Ca²⁺ 依赖性谷氨酸胞吐在生理条件下是否真实发生（Parpura 1994 vs Fiacco/Bhatt 2007-2009）

**新增悬空引用**：无（所有引用的 slug 均已建页）

**图谱更新**：新增节点 6（astrocyte, tripartite-synapse, d-serine, gliotransmitter, astrocyte-calcium-signaling, glutamate-glutamine-cycle）；新增边约 20；总计 **125 节点、~709 条边**

---

## 2026-07-01（文章 #67·空间注意的神经回路·背侧注意网络 DAN）

**源文章**：[[2026-07-01-dorsal-attention-network-FEF-IPS]] —《空间注意的神经回路：前额叶眼区与顶内沟如何驾驭大脑的聚光灯》

**新建页面（2 页）**：
- `concepts/dorsal-attention-network.md`：背侧注意网络（DAN）——FEF+IPS 构成目标驱动注意控制系统；LIP 优先级地图；FEF 微电刺激因果证据；V4→V1 反馈必要通道；乘法性增益调制；FEF→TRN 门控接口（established）
- `concepts/biased-competition.md`：偏置竞争模型——Desimone & Duncan 1995；多刺激竞争感觉表征资源；DAN 提供偏置信号；乘法增益是偏置计算形式（mainstream）

**修订页面（3 页）**：
- `systems/prefrontal-cortex.md`（rev2→rev3）：新增 FEF（BA8）作为 PFC 注意控制子区域；related 新增 dorsal-attention-network 和 thalamus；key_sources 新增 PMID:13679398 和 PMID:11994752；opens_questions 新增 Q-dan-02
- `systems/v1-primary-visual-cortex.md`（rev3→rev4）：新增 V4→V1 反馈是注意调制必要通道（Debes & Dragoi 2023）；related 新增 dorsal-attention-network 和 biased-competition；key_sources 新增 PMID:36730414
- `systems/thalamus.md`（rev2→rev3）：新增 DAN（FEF/IPS）→TRN 通路作为皮层注意信号向下传递接口；related 新增 dorsal-attention-network；Q-dan-01 交叉引用；Q-thalamus-gating-mechanism 部分回答

**新登记矛盾**：无新矛盾
**新增悬空引用**：无
**图谱更新**：新增节点 2（dorsal-attention-network, biased-competition）；新增边 13；总计 119 节点、689 条边

---

## 2026-06-30（文章 #66·视丘的双面人格·T 型钙通道与感知时序门控）

**源文章**：[[2026-06-30-thalamic-burst-t-type-calcium-timing-gate]] —《视丘的双面人格：T 型钙通道如何在爆发与强直之间切换，让清醒大脑实现精确感知》

**新建页面（2）**：
- `neurons/thalamic-firing-modes.md`（视丘放电模式/爆发强直双模式）🟢 established — 清醒VPm约15%感觉响应为爆发；爆发提高时序精度非幅度；爆发-强直连续谱（Whitmire 2016）；前馈FSU同步创造10ms时窗（Borden 2022）；CaV3.1去失活机制；填补thalamus.md的悬空引用
- `neurons/t-type-calcium-channels.md`（T型钙通道/CaV3/低电压激活钙通道）🟢 established — CaV3.1（TC）/CaV3.3（TRN）分布；失活-去失活动力学；LTS产生机制；疾病连接（失神癫痫/脆性X/PLCβ4通路）

**修订页面（1）**：
- `systems/thalamus.md`（rev2）— 更新"双模放电"小节：加入 Borden 2022 清醒因果实验（爆发→时序精度↑非幅度↑）和 Whitmire 2016 爆发-强直连续谱；更新 Q-thalamus-burst-awake 为"部分回答"；补充 key_sources

**矛盾登记（0）**：新证据与既有主张一致，无新矛盾。

**未解问题状态更新**：
- Q-thalamus-burst-awake：部分回答（时序门控机制确认）；剩余开放：触发机制（TRN vs 适应性KATP）

**新增边（9）**：thalamic-firing-modes↔thalamus、t-type-calcium-channels→thalamic-firing-modes、thalamic-firing-modes→pv-interneurons 等

**图谱**：节点 117，边 676。

---

## 2026-06-03（第 66 篇·视丘的三张面孔·感觉门控、认知放大器与意识开关）

**源文章**：[[2026-06-03-thalamus-gatekeeper-cognition]] —《视丘的三张面孔：感觉门控、认知放大器与意识开关》

**核心任务**：从近期分子/疾病系列（tau, BDNF, NCC）转回系统/回路层级；填补 Q-thalamus-gating-mechanism（睡眠纺锤波文章遗留）；整合视觉注意（Pulvinar-V1）、工作记忆（MD-PFC）和意识（CM-Pf）的视丘视角；建立 thalamus 专页作为系统层核心节点。

**新建页面（2）**：
- `systems/thalamus.md`（视丘）🟢 established / 置信度高 — TRN/TC解剖学、双模放电调控、一次/高次核区分（Sherman框架）、Pulvinar-V1因果证据（Purushothaman 2012）、MD-PFC工作记忆放大（Parnaudeau 2018）、CM-Pf与意识（Cacciatore 2025）
- `concepts/thalamic-firing-modes.md`（视丘双模放电）🟢 established / 置信度高 — T型Ca²⁺通道机制、tonic/burst信息论差异（Zeldenrust 2018）、清醒爆发功能（Borden 2022 因果）、timing-based gating模型

**修订页面（2）**：
- `circuits/thalamocortical-circuit.md`（修订 #2）— 新增：一次/高次视丘核区分、驱动/调制型突触对比表、PFC→TRN大型端钮解剖证据（Zikopoulos&Barbas 2006）；related 新增 thalamus/thalamic-firing-modes/working-memory/prefrontal-cortex/neural-correlates-of-consciousness；Q-thalamus-burst-awake 新增为未解问题
- `concepts/working-memory.md`（修订 #6）— 新增MD视丘放大器角色小节：MD维持延迟期晚期活动、MD-PFC θ/β同步、认知灵活性MD-OFC依赖、精神分裂症临床证据；related 新增 thalamus, thalamocortical-circuit

**矛盾处理**：无新矛盾登记。清醒爆发功能（Q-thalamus-burst-awake）登记为新开放问题而非矛盾。

**新增悬空引用待补**：`[[prefrontal-cortex]]`（需要单独系统页）、`[[v1-primary-visual-cortex]]`（已有但需更新Pulvinar联系）

---

## 2026-06-29（第 65 篇·tau 蛋白病理·磷酸化级联、树突棘错位与朊蛋白样传播）

**源文章**：[[2026-06-29-tau-pathology-alzheimer]] —《形状即命运：tau 蛋白从微管守护者到神经原纤维缠结的分子蜕变》

**核心任务**：填补 alzheimers-disease.md 长期悬空引用 `[[tau-pathology]]`；建立 tau 病理独立 wiki 页面；回答 Q-ad-tau-cascade（高优先级开放问题）；完善 AD 分子损伤双刃剑模型（Aβ + tau）。

**新建页面（1）**：
- `concepts/tau-pathology.md`（tau 蛋白病理）🟢 established / 置信度高 — Braak 分期、CDK5/GSK-3β 激酶级联、Zempel 2015 树突棘错位（TTLL6-spastin 微管破坏）、Fitzpatrick 2017 cryo-EM 结构、de Calignon 2012 跨突触传播、FTD-MAPT 独立神经毒性证据

**修订页面（1）**：
- `diseases/alzheimers-disease.md`（修订 #4）— related 新增 tau-pathology；"连接"段落新增 tau-pathology 节点；key_sources 新增 PMID:1759558、PMID:26691836、PMID:22365544；已填补悬空引用

**矛盾处理**：无新矛盾登记（tau 低聚物 vs NFT 毒性争议记录为 Q-tau-01，待后续实验裁决；内部争议已在 tau-pathology.md 页内并列记录）

**图谱更新**：新增节点 1（tau-pathology）；新增边 12 条（tau-pathology ↔ alzheimers-disease、ltp、nmda-receptor、amyloid-beta-oligomers、engram-cells、hippocampal-circuit、bdnf、pattern-completion、memory-consolidation）；总计 110 节点，637 条边

**新增未解问题**：Q-tau-01（低聚物 vs NFT 相对毒性的活体分离实验）、Q-tau-02（EC-II 神经元优先受累的细胞选择性机制）

**下一步建议（来自 topic_ledger）**：
1. MAPT 突变与 FTD-MAPT 专篇（连接 tau-pathology 页面的 FTD 内容；独立 tauopathy 类群展开）
2. AD 整合综合（Aβ + tau + BDNF + 神经发生四线整合，完成 AD 系列）
3. 无报告范式的意识研究（Q-ncc-01）——从 AD 系列切换至意识系列

---

## 2026-06-02（第 65 篇·具身语义·行动词义的感觉运动神经基底与复制危机）

**源文章**：[[2026-06-02-embodied-semantics]] —《当大脑读到"踢"，脚步已先响——具身语义的神经科学》

**核心任务**：填补唯一悬空引用 `embodied-semantics`（被 motor-cortex 页面引用）；建立具身语义的独立 wiki 页面；整合2004-2026年的支持与反驳证据链；更新 motor-cortex 和 language-network 页面。

**新建页面（1）**：
- `concepts/embodied-semantics.md`（具身语义）🟡 contested / 置信度中 — Hauk等2004 somatotopic fMRI证据；Pulvermüller TMS类别特异性因果效应；Watson 2013 ALE元分析挑战；de Zubicaray 2026 复制危机；分级具身论与Hub-and-Spoke整合模型

**修订页面（2）**：
- `systems/motor-cortex.md`（修订 #3）— related 新增 embodied-semantics；新增连接"运动皮层作为词义的感觉运动辐条"；key_sources 新增 PMID:14741110, PMID:15733097
- `systems/language-network.md`（修订 #3）— related 新增 embodied-semantics；source_articles 新增 2026-06-02-embodied-semantics

**矛盾处理**：无新矛盾登记（具身语义本身状态设为 contested，内部争议已在页内并列记录）

**图谱更新**：新增节点 1（embodied-semantics）；新增/更新边 7 条；悬空引用从 1 减少至 0；总计 112 节点，644 条边

**新增未解问题**：Q-emb-01（运动激活的因果必要性）、Q-emb-02（复制危机系统检验）、Q-emb-03（任务依赖的具体机制）、Q-emb-04（先天无肢者的行动词语义）、Q-emb-05（Hub辐条的表征vs存储区分）

**下一步建议**：语言网络深化（语音知觉：颞上沟/颞平面/音素处理）；Wernicke区功能专篇；主动推断/自由能原理（FEP，填补 Q-pc-02）

---

## 2026-06-28（第 64 篇·BDNF·TrkB信号级联、LTP后期维持与AD分子接点）

**源文章**：[[2026-06-28-bdnf-trk-b-plasticity-memory]] —《BDNF：大脑给自己的成长信号》

**核心任务**：填补多页悬空引用 `[[bdnf]]`（被 adult-neurogenesis、hippocampal-neurogenesis、ltp 等页面引用）；建立 BDNF/TrkB 信号机制的独立 wiki 页面；补充 L-LTP 中 BDNF→Arc→突触固结的完整机制链。

**新建页面（1）**：
- `concepts/bdnf.md`（脑源性神经营养因子 BDNF）🟢 established / 置信度高 — proBDNF/成熟 BDNF 双向开关（p75NTR vs TrkB）；TrkB 三条信号通路（PLCγ/ERK/Akt）；L-LTP 的必要催化分子（Bramham 2005）；SGZ 神经发生 PI3K/Akt 存活机制；有氧运动→血清 BDNF↑→海马体积+2%（Erickson 2011 RCT）；Val66Met 多态性；AD 早期 BDNF/TrkB-CREB 受损；BDNF+AHN 协同改善认知（Choi 2018 Science）

**修订页面（4）**：
- `concepts/ltp.md`（修订 #9）— 新增 BDNF→Arc mRNA 局部翻译→E-LTP→L-LTP 转化段落（突触固结机制）；补充 BDNF 与 DA/STC 路径的汇聚；related 新增 bdnf、arc-arg31；key_sources 新增 PMID:16099088、PMID:17942328
- `concepts/adult-neurogenesis.md`（修订 #2）— 悬空引用 [[bdnf]] 已建页；补充 PI3K/Akt+MAPK/ERK 双通路机制描述
- `concepts/hippocampal-neurogenesis.md`（修订 #3）— 悬空引用 [[bdnf]] 已建页；补充 TrkB 信号机制说明
- `diseases/alzheimers-disease.md`（修订 #3）— 修正 related 中错误 slug `bdnf-trkb`→`bdnf`（已建页）；新增 adult-neurogenesis 连接；补充 Choi 2018 BDNF+AHN 协同干预证据；key_sources 新增 PMID:30190379

**矛盾处理**：无新矛盾登记

**图谱更新**：新增节点 1（bdnf）；新增边 12 条（bdnf→ltp/ltd/adult-neurogenesis/hippocampal-neurogenesis/alzheimers-disease/nmda-receptor/camkii/arc-arg31/synaptic-tagging-capture/memory-consolidation + 反向边 2 条）；总计 111 节点，638 条边

**新增未解问题**：Q-bdnf-01（血脑屏障/TrkB 激动剂临床）、Q-bdnf-02（Val66Met 风险权重）、Q-bdnf-03（AD 中 BDNF 因果方向）

**下一步建议**：阿尔茨海默病分子机制完整文章（tau/淀粉样蛋白/神经发生三线整合）；预测编码与 NCC 的整合；无报告范式意识研究（Q-ncc-01）

---

## 2026-06-27（第 63 篇·意识在哪里·NCC 框架与 COGITATE 2025 综合）

**源文章**：[[2026-06-27-ncc-consciousness-where]] —《意识在哪里？——神经相关物（NCC）框架与 2025 年大脑意识科学的真实地平线》

**核心任务**：推进裁决 C-2026-05-31-01（IIT 后方皮层同步预测 vs COGITATE）和 C-2026-05-31-02（GWT 偏移点燃预测 vs COGITATE）；引入 NCC 三分法框架作为意识理论讨论的基础架构。

**新建页面（1）**：
- `concepts/neural-correlates-of-consciousness.md`（意识的神经相关物 NCC）🟢 mainstream / 置信度高 — Crick & Koch 纲领；最小性+充分性约束；Koch 等（2016）三分法（内容特异 NCC / 完整 NCC / 使能 NCC）；COGITATE 2025 实验裁决摘要；无报告范式的方法学意义；两个竞争框架（GWT/IIT）对 NCC 预测的比较表

**修订页面（4）**：
- `theories/global-workspace-theory.md`（修订 #6）— 新增 NCC 三分法定位（GWT 主要描述使能+完整 NCC）；补充 GNW 回应论文（PMC12510449）四个论点；强调阈限刺激范式是 GWT 真正检验场景；新增 neural-correlates-of-consciousness 到 related
- `theories/integrated-information-theory.md`（修订 #3）— 新增 NCC 三分法定位（IIT 主要描述内容特异 NCC）；补充可证伪性讨论（Lakatos 框架：gamma 同步是辅助假说带而非硬核）；新增 neural-correlates-of-consciousness 到 related
- `concepts/consciousness-ignition.md`（修订 #5）— 补充 GNW 回应论点（offset ignition 从未是核心预测）；NCC 三分法视角（点燃是使能 NCC 的时间动力学描述）；新增 neural-correlates-of-consciousness 到 related
- `concepts/posterior-cortical-hot-zone.md`（修订 #2）— 补充 NCC 三分法视角（PCHZ = 内容特异 NCC 定位假说）；补充 Boly et al. 2017 临床证据（完全额叶切除不影响意识；214 倍植物状态风险）；新增 neural-correlates-of-consciousness 到 related

**矛盾处理**：
- C-2026-05-31-01（IIT 后方同步 vs COGITATE）：evidence_update 补充——GNW 回应论文（PMC12510449）提供额外视角；claim_B 证据进一步积累；裁决仍 open，需要直接测量 Φ 的实验；
- C-2026-05-31-02（GWT 偏移点燃 vs COGITATE）：evidence_update 补充——GNW 回应明确指出偏移点燃从未是核心预测，脑范围广播被确认；裁决仍 open，但 GWT 防线得到明确；新增可证伪性作为核心未解问题

**图谱更新**：新增节点 1（neural-correlates-of-consciousness）；新增边 11 条（NCC→GWT/IIT/posterior-hot-zone/consciousness-ignition/phi-measure/predictive-coding/prefrontal-cortex/v1 + 反向边 2 条）

**新增未解问题**：Q-ncc-01（无报告范式完整 NCC，高优先）、Q-ncc-02（相关性到因果性，高优先）、Q-ncc-03（三类 NCC 边界，中优先）

**下一步建议**：BDNF（仍是悬空引用，被多页引用）；预测编码与 NCC 的整合框架（Q-gwt-04）；阿尔茨海默病分子机制（连接神经发生-AD 线）

---

## 2026-06-26（第 62 篇·大脑的自我更新·成年齿状回神经发生与模式分离）

**源文章**：[[2026-06-26-adult-neurogenesis-dentate-gyrus]] —《大脑的自我更新：成年齿状回如何生产新神经元，以及一场三十年未决的科学之争》

**新建页面（1）**：
- `concepts/adult-neurogenesis.md`（成年神经发生）🟡 emerging / 置信度中 — 五阶段分化程序（qNSC→成熟颗粒细胞）；GABA 开关两阶段功能（协作期→竞争期）；关键期可塑性（NR2B、低 LTP 阈值）；前馈抑制机制支持模式分离；人类争议：Sorrells 2018 vs Boldrini 2018 → Moreno-Jiménez 2019 方法论破局（固定时间）→ snRNA-seq 独立确认；碳-14 定年（~700/天）；AD 中神经发生衰退

**修订页面（2）**：
- `concepts/hippocampal-neurogenesis.md`（修订 #2）— 新增 GABA 开关机制详解；更新人类神经发生评估（从"争议尚未解决"升级为"多维证据支持"）；方法论破局分析（固定时间）；snRNA-seq 证据（Zhou 2022）；AD 连接；证据表更新 3 行；连接新增 adult-neurogenesis、pattern-separation、alzheimers-disease；key_sources 新增 4 篇
- `concepts/pattern-separation.md`（修订 #2）— 神经发生机制部分深化：GABA 开关两阶段程序、关键期分子特性（NR2B）、前馈抑制机制、Clelland 2009 必要性证据；证据表新增 2 行；连接新增 adult-neurogenesis

**矛盾登记**：无新矛盾（Q-adult-neurogenesis-human-controversy 状态更新：从"有争议"升级为"多维证据汇聚支持存在，但规模不确定"，不需要新矛盾条目，因为不是新旧证据对立而是方法论统一）

**图谱更新**：新增节点 1（adult-neurogenesis）；新增边 9 条；修复 _graph.json JSON 格式错误（2026-06-25 遗留的缺少逗号和尾随逗号）；hippocampal-neurogenesis 节点 status→emerging

**新增悬空引用（待填补）**：
- `bdnf`（BDNF/TrkB 信号，被 adult-neurogenesis 和 hippocampal-neurogenesis 引用）

**新增未解问题**：Q-neurogenesis-AD（高优先级）、Q-gaba-switch-timing（中优先级）

---

## 2026-06-25（第 61 篇·当大脑把碎片缝合在一起·伽马振荡与神经绑定）

**源文章**：[[2026-06-25-gamma-oscillations-neural-binding]] —《当大脑把碎片缝合在一起：伽马振荡与神经绑定之谜》

**新建页面（1）**：
- `concepts/binding-by-synchrony.md`（绑定假说）🟡 contested / 置信度中 — Gray & Singer 1989 提出的神经绑定假说；PING/ING 机制作为伽马振荡基础；CTC 框架（Fries 2015）的通信窗口解释；支持证据（Garrett & Halgren 2024：语言绑定时 co-ripples）与反对证据（Costa & Castelo-Branco 2024：视觉整合时伽马反而降低）；未解因果问题（Q-gamma-bind-01/02/03）

**修订页面（1）**：
- `concepts/gamma-oscillations.md`（修订 #2）— 新增绑定假说维度（Gray & Singer 1989 证据）；ING 机制补充；CTC 框架；Costa 2024 反例（γ 在分离时升高）；Williams 2026 ING-PING 转换；精神分裂症 Sklar 2024；新增 related 节点 3 个；新增 key_sources 5 篇；opens_questions 新增 3 条

**矛盾登记**：无新矛盾（C-2026-05-31-01 更新状态说明：新证据进一步支持"IIT 伽马同步预测过于具体"，但矛盾仍 open；C-2026-06-22-01 无更新）。

**新增悬空引用（待填补）**：
- `binding-problem`（绑定问题背景，被 binding-by-synchrony 引用）
- `co-ripples`（高频共振波机制，被 binding-by-synchrony 引用）
- `visual-cortex-v4`（V4 区域页，被 binding-by-synchrony 和 gamma-oscillations 引用）

**新增未解问题**：Q-gamma-bind-01（高）、Q-gamma-bind-02（中）、Q-gamma-bind-03（高）

---

## 2026-06-24（第 60 篇·记忆不混淆的秘密·CA3 吸引子与 DG-CA1 模式分离）

**源文章**：[[2026-06-24-hippocampal-ca3-pattern-completion]] —《记忆不混淆的秘密：CA3 的吸引子动力学与海马如何在「自动补全」与「精准分离」之间走钢丝》

**新建页面（4）**：
- `concepts/pattern-completion.md`（模式补全）🟢 established / 置信度高 — CA3 循环连接 + Hopfield 吸引子动力学；苔状纤维"强制激活"编码 vs 穿孔通路检索的双输入系统；Nakazawa 2002 CA3-NR1 KO 因果证据（PMID:12040087）；吸引子收敛是"记忆提取"的计算本质
- `concepts/pattern-separation.md`（模式分离）🟢 established / 置信度高 — DG 扩张重编码（5×）+ 稀疏激活（<5%）→ 相似输入的神经表征正交化；Leutgeb 2007 DG 全局重映射证据（PMID:17303747）；Sahay 2011 成人神经发生因果改善分离（PMID:21460835）；CA3 的速率重映射（小差异）vs 全局重映射（大差异）梯度机制
- `concepts/attractor-network.md`（吸引子网络）🔵 mainstream / 置信度中 — Hopfield 网络（1982）数学基础；存储容量约 0.14N；现代 Hopfield 网络 = Transformer softmax attention 的数学等价（Ramsauer 2021, arXiv:2008.02217）；连续吸引子（工作记忆/头向细胞）；CA3 生物实现
- `concepts/complementary-learning-systems.md`（互补学习系统）🔵 mainstream / 置信度中 — O'Reilly & McClelland 1994 框架（PMID:7704110）；稳定性-可塑性困境；海马（快/稀疏）+ 新皮层（慢/分布式）；SWR 睡眠重放是知识转移机制；深度强化学习经验回放缓冲区（DQN）是 CLS 理论的直接工程应用

**修订页面（3）**：
- `neurons/hippocampal-circuit.md`（修订#9）— 新增 CA3 模式补全的因果证据（Nakazawa 2002, PMID:12040087）和 CA3 vs CA1 不同计算个性（Leutgeb 2004, PMID:15272123）；related 新增 4 项；key_sources 新增 4 篇
- `concepts/ltp.md`（修订#8）— 新增 CA3 循环突触 NMDAR-LTP 与模式补全因果链的连接；related 新增 pattern-completion、complementary-learning-systems
- `concepts/place-cells.md`（修订#2）— 加入模式分离视角（重映射 = 空间记忆中模式分离的具体表现）；related 新增 pattern-separation、pattern-completion

**矛盾登记**：无新矛盾。

**悬空引用（新增，待填补）**：
- `adult-neurogenesis`（成人神经发生，被 pattern-separation 引用）
- `dentate-gyrus`（齿状回，被 pattern-separation, pattern-completion 引用，目前合并在 hippocampal-circuit）
- `ca3-recurrent-collaterals`（CA3 循环侧支，被 pattern-completion 引用，目前合并在 hippocampal-circuit）

---

## 2026-06-23（第 59 篇·小脑的秘密·运动预测与多层可塑性）

**源文章**：[[2026-06-23-cerebellum-motor-prediction]] —《小脑的秘密：浦肯野细胞如何让大脑成为一台预测机器》

**新建页面（3）**：
- `systems/cerebellum.md`（小脑）🟢 established / 置信度高 — 小脑解剖（三层皮层/DCN）；PF-LTD → 多层可塑性；前向/逆向模型（Wolpert 1998）；CCAS（认知情感综合征，Schmahmann 1998）；De Zeeuw 2021 双向微区综合框架
- `concepts/cerebellar-ltd.md`（小脑 LTD）🟢 established / 置信度高 — mGluR1/IP₃/PKC/AMPAR 内吞五步级联；与海马 NMDA-LTD 的根本差异；Schonewille 2011 "无 LTD 照样学习"挑战；Hansel 2026 预印本 400ms 时间窗口
- `concepts/forward-model.md`（前向模型）🔵 mainstream / 置信度中 — 给定传出拷贝预测运动感觉后果；逆向模型（计算运动指令）；小脑的内部模型功能；MOSAIC 多模块扩展；认知领域扩展可能性

**修订页面（3）**：
- `concepts/ltd.md`（修订#2）— 新增小脑 LTD 独特性段落（mGluR1/PKC，与 NMDA-LTD 并列）；related 新增 cerebellar-ltd, cerebellum；连接段新增两项
- `theories/predictive-coding.md`（修订#5）— 新增"小脑专用预测误差学习系统"段落（前向模型→攀爬纤维误差→LTD更新）；related 新增 cerebellum, forward-model
- `systems/motor-cortex.md`（修订#2）— 新增"小脑-运动皮层闭环"段落（皮质-脑桥-小脑→DCN→VL丘脑→M1回路）；related 新增 cerebellum, forward-model；连接段新增两项

**矛盾登记**：无新矛盾（Schonewille 2011 挑战 LTD 中心论已是已知历史争议，不新登记为 open 矛盾，但在文章和 wiki 中如实呈现两方证据）

**悬空引用（新增，待填补）**：
- `climbing-fiber`（攀爬纤维，被 cerebellum, cerebellar-ltd 引用）
- `parallel-fiber`（平行纤维，被 cerebellum, cerebellar-ltd 引用）
- `deep-cerebellar-nuclei`（深部小脑核，被 cerebellum 引用）
- `spinocerebellar-ataxia`（脊髓小脑性共济失调，被 cerebellum 引用）

---

## 2026-06-22（第 58 篇·网格细胞与场所细胞·填补6个长期悬空引用）

**源文章**：[[2026-06-22-grid-cells-place-cells]] —《六边形的秘密：内嗅皮层网格细胞如何为大脑装备空间坐标系》

**新建页面（6）**：
- `concepts/place-cells.md`（场所细胞）🟢 established / 置信度高 — O'Keefe & Dostrovsky 1971；稀疏编码；重映射（不同环境正交）；θ相位前移；SWR重播；认知地图基本单元
- `concepts/grid-cells.md`（网格细胞）🟢 established / 置信度高 — Hafting等2005 Nature；六边形格点；三参数描述；4–7离散模块（√2比，Stensola 2012）；路径整合坐标输出；发育研究（Qu 2026 Cell）
- `concepts/path-integration.md`（路径整合）🟢 established / 置信度高 — McNaughton等2006；连续吸引子网络；联合细胞整合速度×方向；漂移需地标校准
- `concepts/cognitive-map.md`（认知地图）🔵 mainstream / 置信度高 — Tolman 1948到场所/网格双系统；泛化到情节记忆、心理模拟（Bellmund 2016）、概念空间（Viganò 2023）
- `concepts/theta-phase-precession.md`（θ相位前移）🟢 established / 置信度高 — O'Keefe & Recce 1993；100–355°相位位移；θ序列时间压缩（20:1）；STDP时间窗口框架
- `systems/entorhinal-cortex.md`（内嗅皮层）🟢 established / 置信度高 — MEC（网格/联合细胞）vs LEC（情境感觉）；Layer II-VI功能层级；AD最早受损皮层（Braak分期）

**修订页面（2）**：
- `concepts/theta-oscillations.md`（修订#3）— 修正悬空引用：place-cell→place-cells、grid-cell→grid-cells、phase-precession→theta-phase-precession；related新增 path-integration、entorhinal-cortex
- `concepts/sharp-wave-ripples.md`（修订#5）— 修正悬空引用：place-cell→place-cells；source_articles新增2026-06-22

**矛盾登记**：
- C-2026-06-22-01（OPEN）：人类网格信号稳定性争议。Bellmund 2016 / Nau 2018 等多项fMRI研究发现六边形对称信号 vs Kransberg 2026（PMID:41958631）预注册被动导航研究未检测到信号。性质：方法论差异（主动 vs 被动导航）。登记于 state/contested_claims.json。

**悬空引用**（新增，待填补）：
- `head-direction-cells`（头朝向细胞，被 grid-cells、path-integration 引用）
- `border-cells`（边界细胞，被 cognitive-map、entorhinal-cortex 引用）
- `remapping`（重映射机制，被 place-cells、cognitive-map 引用）

**图谱更新**：新增节点6（place-cells, grid-cells, path-integration, cognitive-map, theta-phase-precession, entorhinal-cortex）；修订节点2（theta-oscillations, sharp-wave-ripples）；新增有向边26条（总计：100节点/559边）

---

## 2026-06-21（第 57 篇·运动皮层·课程路线3 运动系统缺口填补）

**源文章**：[[2026-06-21-motor-cortex-voluntary-movement]] —《从意图到动作——运动皮层如何用旋转的神经交响乐指挥肌肉》

**新建页面（5）**：
- `systems/motor-cortex.md`（运动皮层）🟢 established / 置信度高 — M1/PMC/SMA分层组织；Betz细胞；均质小人；群体向量编码、旋转动力学、输出零空间三框架综合
- `concepts/population-vector-coding.md`（群体向量编码）🟢 established / 置信度高 — Georgopoulos 1986 Science；单神经元宽泛调谐→群体向量精确预测方向；心理旋转732°/s
- `concepts/rotational-dynamics-motor.md`（旋转动力学）🟡 mainstream / 置信度高 — Churchland 2012 Nature；执行期2–2.8 Hz旋转；动力学引擎而非参数地图；RNN可复现
- `concepts/output-null-space.md`（输出零空间）🟡 mainstream / 置信度高 — Kaufman 2014 NatNeuro；准备期活动集中于零空间（调谐比4.5×）；几何机制解释准备不触发运动
- `circuits/mirror-neurons.md`（镜像神经元）🟡 mainstream / 置信度中等 — Gallese/Rizzolatti 1996 Brain；F5区17%双重激活（执行+观察）；F5/BA44同源；语言演化假说

**修订页面（1）**：
- `systems/language-network.md`（修订#2）— 新增镜像神经元（F5/BA44同源）与运动皮层的连接；related 新增 mirror-neurons, motor-cortex；语言演化的动作理解背景

**矛盾登记**：无新矛盾

**悬空引用**：新增 `corticospinal-tract`（皮质脊髓束，motor-cortex 和 dorsal-language-stream 均引用）

**图谱更新**：新增节点5（motor-cortex, population-vector-coding, rotational-dynamics-motor, output-null-space, mirror-neurons）；修订节点1（language-network）；新增有向边12条（总计：88节点/505边）

---

## 2026-06-20（第 56 篇·双流语言网络·课程路线7 语言与抽象思维 首篇）

**源文章**：[[2026-06-20-language-dual-stream]] —《语言的解剖：双流网络如何将声波解码为思想》

**新建页面（5）**：
- `systems/language-network.md`（语言网络）🟢 established / 置信度高 — Hickok & Poeppel 2007 双流模型；腹侧流（声音→意义，双侧）+ 背侧流（声音→动作/句法，左侧主导）；超模态证据（手语研究）；主动预测性
- `systems/broca-area.md`（Broca区）🟢 established / 置信度高 — BA44（pars opercularis，层级句法Merge运算，背侧流）vs BA45（pars triangularis，语义工作记忆，腹侧流）内部分工；Friederici 2020 发育证据
- `concepts/arcuate-fasciculus.md`（弓状束）🟢 established / 置信度高 — 背侧流主干白质通路；左侧优势；出生时低髓鞘化随句法习得成熟；损伤→传导性失语
- `circuits/dorsal-language-stream.md`（背侧语言流）🟢 established / 置信度高 — A1→颞平面→Spt→弓状束→BA44→运动皮层；音韵短期记忆+句法层级运算；左侧主导
- `circuits/ventral-language-stream.md`（腹侧语言流）🟢 established / 置信度高 — A1→MTG/STS→ITG→角回→BA45；声音→词义映射；双侧分布；具身语义（工具词→运动皮层，动物词→视觉皮层）

**修订页面（3）**：
- `concepts/working-memory.md`（修订#5）— 新增语音回路（phonological loop）对应背侧流Spt↔BA44环路的描述；related 新增 dorsal-language-stream, language-network
- `theories/predictive-coding.md`（修订#5）— 新增语言预测编码实例（词前200ms语义-感觉运动预测，Grisoni 2024）；related 新增 language-network, ventral-language-stream
- `systems/default-mode-network.md`（修订#4）— 新增角回（BA39）作为DMN-语言网络共享节点；related 新增 language-network, ventral-language-stream

**矛盾登记**：无新矛盾（语言网络的双流分工已被多来源独立支持，证据一致）

**悬空引用**：新增潜在悬空引用待补：
- `wernicke-area`（颞上回语音区，与 language-network 密切相关）
- `embodied-semantics`（具身语义，ventral-language-stream 中的核心机制）
- `planum-temporale`（颞平面，语音时序分析节点）

**图谱更新**：新增节点5（language-network, broca-area, arcuate-fasciculus, dorsal-language-stream, ventral-language-stream）；修订节点3（working-memory, predictive-coding, default-mode-network）；新增有向边约20条

---

## 2026-05-31（第 36 篇·注意瞬盲·填补 Q-gwt-02 + Q-cogitate-02·课程路线8 意识与自我 第五篇）

**源文章**：[[2026-05-31-attentional-blink]] —《注意瞬盲：当意识成为稀缺资源，大脑如何在时间中撞墙》

**新建页面（1）**：
- `concepts/attentional-blink.md`（注意瞬盲）🔵 mainstream / 置信度高 — 填补 consciousness-ignition 和 global-workspace-theory 的悬空引用；RSVP 范式中 T1 后 200–500ms 内 T2 感知抑制；Chun & Potter 双阶段模型 + GWT 工作空间占据机制；270ms MEG 神经分叉是 GWT 有/无意识分叉最直接证据；全有全无 vs 梯度标记为 contested

**修订页面（2）**：
- `theories/global-workspace-theory.md`（修订#5）— 新增 attentional-blink 相关链接；新增注意瞬盲三行证据（270ms 分叉、双峰分布、掩蔽 vs 瞬盲分离）；更新 source_articles 和 key_sources；标注注意瞬盲是 COGITATE 未能检验的核心场景的直接补充
- `concepts/consciousness-ignition.md`（修订#4）— 填充 attentional-blink 悬空引用（添加说明文字）；更新 source_articles；新增修订历史行

**矛盾登记**：无新矛盾（现有矛盾状态未变化：C-2026-05-31-01 和 C-2026-05-31-02 仍 open）

**悬空引用解决**：
- `attentional-blink`（已解决）：consciousness-ignition.md（related 字段）和 global-workspace-theory.md（related 字段）均引用此 slug，今日新建页面，悬空消除

**图谱更新**：新增节点 1（attentional-blink）；新增有向边 7；总计 83 节点 493 条边

---

## 2026-05-31（第 35 篇·COGITATE预注册对决意识理论·裁决矛盾 C-2026-05-31-01 & C-2026-05-31-02·课程路线8·意识与自我 + 方法论）

**源文章**：[[2026-05-31-cogitate-adversarial-test-consciousness]] —《当意识理论遭遇实验法庭：COGITATE预注册对决如何同时挑战IIT与全局工作空间理论》

**新建页面（1）**：
- `methods/adversarial-collaboration.md`（对抗性协作）🟡 emerging / 置信度高 — 理论家共同预注册预测+通过/失败标准；COGITATE 2025 是最大规模实践（256人，3模态，IIT vs GNWT）；操作化争议是核心局限

**修订页面（3）**：
- `theories/integrated-information-theory.md`（修订#2）— 补充 COGITATE 全文精确数字（3.8% 电极持续激活，BF₀₁=1.15–4.9，<0.75s 同步，方向信息 0.5s 后衰减）；新增 adversarial-collaboration 相关链接；key_sources 补充 PMID:32135090
- `theories/global-workspace-theory.md`（修订#4）— 补充 COGITATE 精确数字（0/655 offset ignition，PFC 70% 0.2-0.4s，BF₀₁=1.94×10⁴）；更新证据表（拆分 PFC 解码条目+新增 offset ignition 失败行）；新增 adversarial-collaboration 相关链接
- `concepts/consciousness-ignition.md`（修订#3）— 证据表新增 offset ignition 完全缺失行（0/655）+ onset 时序偏差行；新增 Q-cogitate-02 于未解问题；source_articles 补充 COGITATE 文章

**矛盾裁决进展**：
- C-2026-05-31-01（IIT 后方皮层同步 vs COGITATE 否定）：**未裁决，但已深化**。COGITATE 全文数字（3.8% 电极，BF₀₁=1.15–4.9）进一步支持 claim_B（IIT 同步预测失败），但 IIT 理论家认为操作化不完全代表理论核心。状态维持 open，confidence 降级记录在 wiki。
- C-2026-05-31-02（GNWT offset ignition vs COGITATE 否定）：**未裁决，但已深化**。0/655 电极的 offset ignition 极强地支持 claim_B（GNWT 预测失败），但 GNWT 阵营争辩操作化版本非核心预测。状态维持 open。

**新增悬空引用**：无（图谱 83 节点 492 条边，无悬空边）

---

## 2026-05-31（第 34 篇·REM睡眠与情绪记忆·深化课程路线4·学习与记忆 + 课程路线6·情绪与动机）

**源文章**：[[2026-05-31-rem-sleep-emotional-memory]] —《情绪炼金炉：REM睡眠如何重写记忆的情感底色》

**新建页面（2）**：
- `concepts/rem-sleep.md`（REM睡眠）🟢 established / 置信度高 — NE真空（蓝斑沉默）+ θ振荡 + 杏仁核-海马θ同步三机制；情绪记忆去饱和化的离线窗口；Boyce 2016光遗传因果（仅REM期沉默MS GABA→θ消失→情境记忆损害）；van der Helm 2011人类fMRI（REM睡眠降低杏仁核情绪反应）；Walker SFSR假说
- `concepts/emotional-memory-depotentiation.md`（情绪记忆去饱和化）🟡 emerging / 置信度中 — REM期NE≈0 → θ谷值驱动LA突触类LTD → 情绪色彩选择性弱化、事实内容保留；Poe θ相位反转假说（峰值→谷值）；Totty 2017 LA-VH 180°反相 (R=0.954)；PTSD可能是去饱和化失败

**修订页面（3）**：
- `concepts/fear-extinction.md`（修订#2）— 当前理解节新增REM睡眠巩固段落（Totty 2017 LA-VH θ相位差，Walker SFSR）；frontmatter新增rem-sleep/theta-oscillations/emotional-memory-depotentiation至related，Q-rem-01/Q-rem-02至opens_questions，PMID:28729826/PMID:19702380至key_sources
- `concepts/theta-oscillations.md`（修订#2）— 新增「REM睡眠θ：情绪记忆巩固的相位窗口」机制节（清醒/REM θ功能对比表，LA-VH θ相位差机制，Boyce 2016因果链）；当前理解节补充REM θ段落；关键证据表新增2行；连接新增rem-sleep/fear-extinction/emotional-memory-depotentiation；opens_questions新增Q-rem-01/Q-rem-03/Q-rem-05
- `concepts/memory-consolidation.md`（修订#5）— 当前理解节新增REM睡眠角色段落（Boyce 2016因果链、van der Helm 2011、Walker SFSR假说）；关键证据表新增2行；Q-rem-sleep-role标记为部分解答；related新增rem-sleep/emotional-memory-depotentiation

**矛盾登记（0）**：θ相位反转假说（Poe）机制细节仍待验证，已登记为Q-rem-03；SFSR假说在人类层面证据仍弱，已在文章和wiki中标注置信度差异

**新增未解问题（5）**：Q-rem-01（LA-VH θ同步细胞机制）、Q-rem-02（θ相位反转是否区分不同强度情绪记忆）、Q-rem-03（θ峰值→谷值转变的充分/必要性）、Q-rem-04（人类REM去饱和化的个体差异来源）、Q-rem-05（增强REM θ是否改善情绪调节或治疗PTSD）

**图谱变化**：82节点（+2），486边（+18）

---

## 2026-06-19（第 33 篇·睡眠纺锤波·深化课程路线4·学习与记忆）

**源文章**：[[2026-06-19-sleep-spindles-nrem]] —《当大脑钟声响起：睡眠纺锤波的丘脑起源与记忆巩固的时间建筑学》

**新建页面（3）**：
- `concepts/sleep-spindles.md`（睡眠纺锤波）🟢 established / 置信度高 — TRN CaV3.3 T型钙通道驱动TRN↔TC振荡环路生成12–15 Hz纺锤波；皮层树突L型Ca²⁺预热窗口；CACNA1I精神分裂症风险基因；SO-spindle-SWR三重嵌套中间层；Latchoumane 2017因果实验（三重耦合必要）
- `circuits/thalamocortical-circuit.md`（丘脑-皮层回路）🟢 established / 置信度高 — TRN（CaV3.3）↔TC（CaV3.1）振荡回路是纺锤波起搏器；核心/矩阵双通路；皮层-丘脑反馈（CT第六层）调制纺锤波振幅；清醒（强直）vs睡眠（爆发）模式切换
- `concepts/cortical-slow-oscillation.md`（皮层慢振荡）🟢 established / 置信度高 — NREM深睡眠0.5–1 Hz UP/DOWN态交替；起源PFC向后传播；SO上行相触发纺锤波（CT→TRN）；三重奏顶层时间框架

**修订页面（2）**：
- `concepts/memory-consolidation.md`（修订#4）— NREM三重奏小节深化：纺锤波主动触发机制（CT→TRN→钙预热）；Latchoumane 2017因果实验；related/prerequisites新增sleep-spindles、cortical-slow-oscillation、thalamocortical-circuit
- `concepts/sharp-wave-ripples.md`（修订#4）— related新增sleep-spindles和cortical-slow-oscillation；key_sources扩充3个（三重耦合文献）；source_articles新增2026-06-19

**矛盾登记（0）**：今日文章核心机制（TRN纺锤波生成、三重耦合）在领域内无重大争议；CaV3.1 vs CaV3.3 分工已登记为"快/慢纺锤波待厘清"的开放问题，但不属于矛盾协议范围

**新增未解问题（3）**：Q-spindle-fast-vs-slow、Q-spindle-augmentation-clinical、Q-spindle-rem-division

**图谱变化**：80节点（+3），468边（+16）

---

## 2026-06-18（第 32 篇·连接组学：接线图之上·首次覆盖课程路线9·Connectomics）

**源文章**：[[2026-06-18-connectomics-wiring-diagram]] —《接线图之上：当我们拥有了完整神经地图，理解大脑的征途才刚刚开始》

**新建页面（2）**：
- `methods/connectomics.md`（连接组学）🟢 established / 置信度高 — 用串行电子显微镜重建神经元全突触接线图的方法；C. elegans（302神经元，White 1986）→果蝇FlyWire（139,255神经元，Dorkenwald 2024）；揭示小世界、富人俱乐部、前馈回路主题等网络拓扑原理；斑马鱼脑干连接组成功预测眼动吸引子动力学（Vishwanathan 2024）；核心局限：突触权重/动力学状态/个体差异均超出静态连接图的描述能力
- `concepts/circuit-motifs.md`（回路主题）🔵 mainstream / 置信度高 — 神经回路中反复出现的小型拓扑模式（前馈回路FFL、反馈循环、富人俱乐部rich-club）；可能反映神经计算基本需求；Drosophila全脑连接组（Lin 2024，30%枢纽神经元，前馈回路过表达）提供最大规模系统验证；蘑菇体15个学习隔室为典型应用

**修订页面（0）**：无修订现有页面

**矛盾登记（0）**：无新矛盾（连接组学主要发现在该领域内无重大争议，结构-功能鸿沟为领域共识）

**新增悬空引用待补**：
- `c-elegans-nervous-system` — 专用的 C. elegans 神经系统页面（可从 connectomics 主页分拆）
- `mushroom-body` — 果蝇蘑菇体专页（connectomics 文章中有详细内容但缺独立wiki页）
- `stomatogastric-ganglion` — 螃蟹/龙虾胃神经节作为神经调质改变回路功能的经典案例；connectomics 局限论点的关键实验系统

**图谱**：节点 75→77，边 438→452（新增14条边，围绕 connectomics 和 circuit-motifs 两个新节点建立连接）

---

## 2026-05-31（第 31 篇·五月月报·大图景·三十篇文章的跨月整合）

**源文章**：[[2026-05-31-may-monthly-synthesis]] —《五月月报·大图景：从一个动作电位到世界模型——三十篇文章如何拼出大脑构建认知的完整弧线》

**新建页面（1）**：
- `concepts/temporal-hierarchy.md`（时间层级编码）🔵 mainstream / 置信度高 — 从纳秒到终身的多时间尺度并行计算框架；从SNARE融合（100μs）到威胁记忆（终身）的完整时间谱；是世界模型架构的时间维度

**修订页面（1）**：
- `concepts/world-model.md`（世界模型）— revision_count 1→2；将六层架构扩展为八层分层贝叶斯预测机器；related 新增 temporal-hierarchy、sharp-wave-ripples、integrated-information-theory；补充 COGITATE 2025 对顶层意识理论的挑战

**矛盾登记（0）**：无新矛盾（月度综合不引入新实验数据）

**新增悬空引用待补**：
- `hebbian-learning` — world-model prerequisites 引用但独立页面不足（已有内容在 ltp.md 中）
- `active-inference` — 月度大图景提及但缺独立页面（高优先级：下月优先补充）
- `bayesian-brain` — 整合框架缺独立页面

**图谱**：节点 74→75，边 428→438（新增10条边，连接 temporal-hierarchy 到各时间尺度机制）

---

## 2026-06-17（第 30 篇·海马锐波涟漪与记忆重放·多项2024-2026新发现整合）

**源文章**：[[2026-06-17-sharp-wave-ripples-memory-replay]] —《夜晚，大脑重写自己的神经地图——海马锐波涟漪、记忆选择与睡眠期巩固的新机制》

**新建页面（0）**：今日无新建页面（相关 wiki 页面均已存在）

**修订页面（3）**：

- `concepts/sharp-wave-ripples.md`（revision 2→3）：新增4个关键2024-2026新发现：(1) Robinson 2026 — 只有大振幅SWR亚集与海马-PFC同步再激活相关，光遗传增强SWR改善记忆（因果充分性证据）；(2) Yang 2024 — 清醒SWR作为记忆标记机制，标记经历供睡眠优先重放；(3) Giri 2024 — 睡眠剥夺SWR振幅降低、重放效率下降（SWR发生率≠有效性的分离证据）；(4) Chang 2025 — NREM睡眠微结构（NE/瞳孔状态）将新旧记忆重放分时段组织防止干扰；另新增 Ecker 2022 CA3模型（学习突触结构同时决定SWR生成与重放内容）；证据表从5行扩展到11行；未解问题从2增到5；related新增norepinephrine-locus-coeruleus和dopamine-reward-prediction-error

- `concepts/memory-consolidation.md`（revision 2→3）：证据表新增3行（Robinson 2026因果充分性、Chang 2025微结构分时、Yang 2024清醒标记）；key_sources扩充3项；related新增norepinephrine-locus-coeruleus；source_articles新增今日文章

- `neurons/hippocampal-circuit.md`（revision 7→8）：新增Ecker 2022关键发现：CA3学习依赖突触权重结构同时决定SWR生成与重放内容；key_sources新增PMID:35040779；source_articles新增今日文章

**矛盾登记（0）**：今日新证据与既有wiki页面主张一致；Robinson 2026、Yang 2024、Chang 2025均为既有框架的深化而非推翻

**新增悬空引用（0）**：所有新增related字段的节点均已有wiki页面

**图谱变化**：节点 74→74（无变化，无新页面），边 424→428（+4：SWR↔NE双向调控边 ×2、DA→SWR调控边、SWR→DA关联边）

---

## 2026-05-31（第 29 篇·整合信息理论 IIT·COGITATE 双重挑战）

**源文章**：[[2026-05-31-integrated-information-theory]] —《意识等于整合信息：一个方程式的野心与困境》

**新建页面（4）**：
- `theories/integrated-information-theory.md`（整合信息理论）🔴 contested / 置信度中 — 意识 = Φ（整合信息量）；五公理推导物理约束；后方皮层热区解剖预测；小脑/视网膜低 Φ 预测与临床一致；COGITATE 2025（Nature，256被试，3种成像）挑战核心机制预测（后方皮层同步缺失）；泛心论蕴含；前馈网络 Φ ≈ 0
- `concepts/phi-measure.md`（Φ 整合信息度量）🔴 contested / 置信度中 — IIT 核心量；最优分割时的因果信息损失；NP-hard 精确计算；IIT 2.0→3.0 演化；前馈/并行/循环网络对比；PCI 作为实用代理
- `concepts/posterior-cortical-hot-zone.md`（后方皮层热区）🔵 mainstream / 置信度中 — V1/V4/MT/下颞叶的高整合连接拓扑；内容特异 NCC vs 完整 NCC vs 使能 NCC 三分法；COGITATE 2025 对后方皮层同步预测（机制核心）的挑战
- `methods/perturbational-complexity-index.md`（扰动复杂性指数 PCI）🟢 established / 置信度高 — Casali 2013 奠基；TMS+EEG+Lempel-Ziv 压缩；区分清醒/NREM/麻醉/MCS/VS；Sarasso 2015 跨麻醉药对比；临床意识评估客观工具

**修订页面（2）**：
- `theories/global-workspace-theory.md`（revision 2→3）：新增 IIT vs GWT 核心分歧对比表（前额叶 vs 后方皮层；瞬态点燃 vs 持续激活）；COGITATE 2025 偏移点燃缺失和前额叶内容解码有限的详细记录；related 新增 integrated-information-theory 和 posterior-cortical-hot-zone
- `concepts/consciousness-ignition.md`（revision 1→2）：新增 COGITATE 2025 对点燃预测的挑战（刺激偏移时前额叶点燃缺失）；新增 IIT 对比框架（持续激活 vs 瞬态点燃）；related 新增 integrated-information-theory 和 posterior-cortical-hot-zone；source_articles 新增今日文章

**矛盾登记（2）**：
- C-2026-05-31-01（新）：IIT 预测后方皮层内部持续同步 vs COGITATE 2025 否定此预测 — open
- C-2026-05-31-02（新）：GWT 预测刺激偏移时前额叶点燃 vs COGITATE 2025 否定偏移点燃 — open（更新 consciousness-ignition 页面 confidence 降为中）

**新增悬空引用（待建页面）**：
- `panpsychism`（被 integrated-information-theory 引用）
- `adversarial-collaboration`（方法论概念，被 cogitate 讨论引用）

**图谱变化**：节点 70→74（+4），边 410→424（+14）

---

## 2026-05-31（第 28 篇·第四周综合·世界模型六层架构）

**源文章**：[[2026-05-31-week4-synthesis]] —《第四周综合：当大脑成为自己的宇宙——世界模型的六层建构架构》

**新建页面（1）**：
- `concepts/world-model.md`（世界模型）🟡 emerging / 置信度中 — 大脑对外部世界和自身状态持续维护的贝叶斯最优内部模型；六层架构（化学调控层→运动预测层→情感标注层→误差加权层→离线仿真层→意识广播层）整合第四周六篇文章；Friston 2010 自由能原理为数学框架；整合框架，非单一实验结论，置信度设为中；**第四周综合框架节点**

**修订页面（3）**：
- `theories/global-workspace-theory.md`（revision 1→2）：添加"GWT 作为世界模型意识广播层"的整合框架定位；related 新增 world-model；世界模型广播更新机制描述；DMN 先验生成器 vs GWT 广播基础设施的互补关系再次强调
- `theories/predictive-coding.md`（revision 3→4）：将预测编码定位为"世界模型误差加权更新层"；related 新增 world-model；明确更新方程 Δmodel ∝ precision_weighted_prediction_error
- `systems/default-mode-network.md`（revision 2→3）：将 DMN 定位为"世界模型离线仿真层"；related 新增 world-model；AD/DMN 连接补充世界模型视角

**矛盾登记（0）**：无新矛盾。六层世界模型框架为今日新提出的整合性概念工具，尚无与既有 wiki 主张的冲突（该框架有意标注为 emerging 和 medium confidence）。

**图谱更新**：70 节点（+1 world-model），410 条边（+10 edges）

---

## 2026-05-30（第 27 篇·意识·全局工作空间理论，课程路线8第二篇）

**源文章**：[[2026-05-30-global-workspace-theory]] —《当意识在大脑中"点燃"：全局工作空间理论与感知的临界翻转》

**新建页面（2）**：
- `theories/global-workspace-theory.md`（全局工作空间理论）🔵 mainstream / 置信度中 — Baars（1988）认知GWT → Dehaene-Changeux（1998–2011）神经GWT；点燃机制；三个意识神经标志；GWT vs IIT 2025年COGITATE对抗性合作结果（两者均受挑战）；课程路线8第二篇
- `concepts/consciousness-ignition.md`（意识点燃）🔵 mainstream / 置信度中 — 全有或全无的非线性临界翻转；~270-300ms 前额顶叶激活；双触发条件（感觉超阈 + 注意可用）；注意瞬盲范式的黄金证据（Sergent et al. 2005）；P3b EEG标志（Cohen et al. 2024 无报告范式挑战其地位）

**修订页面（3）**：
- `systems/default-mode-network.md`（revision 1→2）：部分回应 Q-dmn-04；添加 DMN（先验生成器）vs GWT工作空间（广播基础设施）的互补架构描述；related 新增 global-workspace-theory
- `theories/predictive-coding.md`（revision 2→3）：添加 GWT-预测编码整合：足够大的预测误差可能触发工作空间点燃；related 新增 global-workspace-theory
- `systems/prefrontal-cortex.md`（revision 1→2）：添加 dlPFC 在 GWT 点燃中的角色；related 新增 global-workspace-theory 和 consciousness-ignition；新增 van Vugt 2018 猕猴证据

**矛盾登记（0）**：无新矛盾（GWT vs IIT 的争议已作为已知理论分歧记录在文章中，不需要在矛盾登记册中作为新条目，因为这是理论间分歧而非同一事实的相互矛盾证据）

**新增悬空引用（待补缺口）**：
- `attentional-blink`（注意瞬盲）— 被 GWT 和 consciousness-ignition 页引用
- `p3-wave`（P3波）— 被 consciousness-ignition 页引用

**图谱更新**：69 节点，400 条边（+2 节点，+15 边）

---

## 2026-06-16（第 26 篇·全脑网络·默认模式网络，课程路线8开篇）

**源文章**：[[2026-06-16-default-mode-network]] —《当大脑"休息"时，它在做什么？——默认模式网络与大脑内部宇宙的构建逻辑》

**新建页面（1）**：
- `systems/default-mode-network.md`（默认模式网络）🟢 mainstream / 置信度高 — 大脑内部模拟基础设施；Raichle 2001 发现；Fox 2005 反相关（GSR 方法论争议）；Buckner 2008 综述；Andrews-Hanna 2011 双子系统（MTL子系统=情节记忆/场景构建；dMPFC子系统=心智化）；aMPFC+PCC枢纽节点；Buckner 2009 Aβ优先沉积枢纽节点；**课程路线8（意识与自我）首次进入**

**修订页面（3）**：
- `theories/predictive-coding.md`（revision 1→2）：related 新增 default-mode-network；修订历史追加"DMN 作为预测编码层级高层先验生成器"
- `neurons/hippocampal-circuit.md`（revision 6→7）：related 新增 default-mode-network；确认海马（MTL）是 DMN 核心节点；修订历史追加
- `diseases/alzheimers-disease.md`（revision 1→2）：related 新增 default-mode-network；dimensions 新增 whole-brain-network；新增 Aβ 优先沉积 DMN 枢纽节点（Buckner 2009）；修订历史追加

**登记矛盾（0）**：Fox 2005 的反相关发现存在 GSR 方法论争议，已在文章和 wiki 页面中标注，但不构成知识库既有主张的直接矛盾（既有页面未声称特定反相关强度值）。

**新增悬空引用 / 待补缺口（3）**：
- `salience-network` — DMN 切换的中介（突显网络），尚无独立页；被 default-mode-network 的描述中提及
- `task-positive-network` — DMN 的反相关对象，尚无独立页
- `self-referential-processing` — DMN 枢纽的核心计算（自我参照），尚无独立页

**图谱变动**：新增节点1（default-mode-network）；新增边14条；总计：67节点，385边

---

## 2026-06-15（第 25 篇·理论框架·预测编码）

**源文章**：[[2026-06-15-predictive-coding]] —《当大脑主动预测而非被动接收：预测编码理论如何重新定义视觉皮层的计算逻辑》

**新建页面（2）**：
- `theories/predictive-coding.md`（预测编码）🟡 mainstream / 置信度中 — 皮层层级反馈传预测/前馈传误差；Rao & Ballard 1999 奠基；Bastos 2012 分层映射（γ/α-β振荡分工）；Keller 2012 V1感觉运动失配实验；主动推断：行动也是预测误差最小化；注意=精度加权；DA-RPE 同一计算结构；**首个理论域页面，开创 theories/ 子目录**
- `concepts/precision-weighting.md`（精度加权）🟡 emerging / 置信度中 — 预测误差精度权重 π；注意=提升关键误差精度；ACh/NE/DA 是分子层面精度调节器；VIP-SST 去抑制是回路层面实现候选；精度失调=精神分裂症/孤独症理论框架

**修订页面（2）**：
- `systems/v1-primary-visual-cortex.md`（revision_count 2→3）：新增"预测编码视角下的V1"小节；纳入 Keller 2012 感觉运动失配实验（V1 L2/3 误差响应）、环绕抑制预测编码解释、分层振荡分工；related 新增 predictive-coding, precision-weighting；opens_questions 新增 Q-pc-04；key_sources 新增 PMID:22681686, PMID:10195184, PMID:23177956
- `concepts/dopamine-reward-prediction-error.md`（revision_count 2→3）：新增"DA-RPE 作为预测编码框架中奖励域预测误差"小节；纳入 Diederen & Fletcher 2021 (PMID:32338128) 整合框架；新增精神分裂症 aberrant salience 的精度失调解释；related 新增 predictive-coding, precision-weighting；key_sources 新增 PMID:32338128, PMID:20068583

**登记矛盾（0）**：无新矛盾。预测编码与现有 wiki 主张（V1、DA、ACh、增益控制）的关系是扩展和深化，而非冲突。

**新增悬空引用 / 待补缺口（3）**：
- `active-inference` — 在 predictive-coding 的 related 中引用，尚无独立页
- `free-energy-principle` — 预测编码理论的数学基础（Friston 2010），尚无独立页
- `aberrant-salience` — 精神分裂症的精度失调假说，尚无独立页（在精度加权页中提及）

**图谱**：节点 64→66，边 353→371。新增2节点（predictive-coding, precision-weighting），新增18条有类型边（predictive-coding↔v1/orientation/gain-control/DA-RPE/precision-weighting/working-memory/theta/ltp/nmda/temporal-coding-hierarchy/competition-selection-principle；precision-weighting↔predictive-coding/gain-control/ACh/NE/VIP/DA-RPE）。

---

## 2026-05-30（第 24 篇·情绪与动机首篇）

**源文章**：[[2026-05-30-amygdala-fear-memory]] —《当杏仁核学会恐惧——突触可塑性如何将一次经历铸成防御记忆，以及大脑为何难以遗忘》

**新建页面（3）**：
- `systems/amygdala.md`（杏仁核）🟢 established / 置信度高 — LA/BA/ITC/CeA四层架构；恐惧印迹~20%稀疏LA编码；ITC背侧/腹侧分工闸门；前额叶PL/IL双向控制；课程主题6（情绪与动机）首个系统页
- `concepts/fear-conditioning.md`（恐惧条件反射）🟢 established / 置信度高 — CS+US在LA汇聚→NMDA巧合检测→CaMKII→GluA1插入→LA-LTP；与海马LTP分子机器同构；Nabavi 2014光遗传双向因果证明
- `concepts/fear-extinction.md`（恐惧消退）🟢 established / 置信度高 — 消退≠遗忘（LTD去增强+新IL→ITC→CeM回路）；BA双群竞争（恐惧/消退神经元）；vmPFC激活预测消退质量；PTSD=消退记忆提取失败

**修订页面（2）**：
- `concepts/ltp.md`（revision_count 6→7）：新增LA-LTP是恐惧记忆因果底物（Nabavi 2014 PMID:24896183）；"LTP是通用跨区域联想学习算法"洞见明确化；related新增fear-conditioning、amygdala；key_sources新增PMID:24896183、PMID:11584069
- `concepts/norepinephrine-locus-coeruleus.md`（revision_count 1→2）：新增LC-杏仁核轴恐惧记忆机制（β受体→BLA-LTP→闪光灯记忆）；新增应激-NE-消退损害机制（Plas 2024）；related新增amygdala、fear-conditioning、fear-extinction；key_sources新增PMID:38370858

**登记矛盾（0）**：无新矛盾，新内容与已有wiki一致（LTP机器、印迹细胞稀疏编码、海马情景信息）

**解决悬空引用（0）**：今日新建节点amygdala/fear-conditioning/fear-extinction均为首次创建，填补了"情绪与动机"方向的重要空白

**新增悬空引用（待填）**：
- `reconsolidation`（记忆再巩固）— 被fear-extinction页引用
- `vmPFC`（腹内侧前额叶）— 被fear-extinction和amygdala页引用（与已有prefrontal-cortex页不同，vmPFC特指IL/infralimbic皮层）

**图谱**：节点 61→64，边 326→353（新增 27 条边）

---

## 2026-06-14（第四周第二篇·第 23 篇）

**源文章**：[[2026-06-14-parkinson-basal-ganglia-circuit]] —《多巴胺的沉默与节律的失控：帕金森病如何揭示大脑运动控制的回路逻辑》

**新建页面（3）**：
- `diseases/parkinsons-disease.md`（帕金森病）🟢 established / 置信度高 — α-突触核蛋白病理（Braak分期/路易小体）、Albin-DeLong回路失衡模型（直接/间接通路）、β振荡病理状态、DBS机制（β→θ振荡切换，Köhler 2024）
- `circuits/basal-ganglia.md`（基底节）🟢 established / 置信度高 — 完整回路解剖（纹状体/GPi/GPe/STN/SNc）、直接/间接/超直接通路、D1/D2受体的双向调节、振荡状态依赖性
- `concepts/beta-oscillations.md`（β振荡）🔵 mainstream / 置信度中 — 13-30 Hz抗运动振荡、PAC耦合证据（López-Azcárate 2010 n=15）、β→θ治疗机制（Köhler 2024 n=25）、与γ/θ振荡的功能对立

**修订页面（1）**：
- `concepts/dopamine-reward-prediction-error.md`（revision_count 1→2）：补充DA的双重功能（RPE教学信号 vs 基底节回路调节器）；新增PD作为DA-RPE系统崩溃极端案例的讨论；新增[[parkinsons-disease]]、[[basal-ganglia]]连接

**登记矛盾（0）**：无新矛盾（β振荡因果性争议为该领域已知开放问题，未触发与现有wiki页面的直接矛盾）

**新增悬空引用（1）**：
- `alpha-synuclein`：被 parkinsons-disease.md 的 related 字段引用，需单独文章覆盖（路易小体/错误折叠机制专页）

**图谱更新**：新增3个节点（parkinsons-disease, basal-ganglia, beta-oscillations），新增18条边；图谱总计61节点、326条边

---

## 2026-06-13（第四周第一篇·第 22 篇）

**源文章**：[[2026-06-13-serotonin-autoreceptor-ssri-delay]] —《血清素的慢时钟：为什么抗抑郁药需要等待两周？》

**新建页面（3）**：
- `systems/serotonin-raphe-system.md`（血清素-缝际核系统）🟢 established / 置信度高 — DRN/MRN解剖、体积传输机制、14种5-HT受体分类、与DA/ACh/NE系统的比较
- `concepts/5-ht-autoreceptor.md`（5-HT自受体与SSRI延迟起效）🔵 mainstream / 置信度高 — 5-HT1A树突自受体负反馈机制；自受体脱敏的分子机制（GRK/β-arrestin）；pindolol加速起效的临床RCT证据（Celada 2004 PMC446220）；5-HT1A/2A在PFC的功能拮抗
- `concepts/hippocampal-neurogenesis.md`（海马神经发生）🔴 contested / 置信度中 — 啮齿类SGZ神经发生证据充分；阻断神经发生→SSRI行为效果消失（Santarelli 2003）；人类成人神经发生存在与规模存在 Sorrells 2018 vs Boldrini 2018 的真实矛盾（已登记 status=contested）

**修订页面（2）**：
- `systems/neuromodulator-systems.md`（revision_count 2→3）：补全5-HT系统（第四个调质系统）；新增5-HT系统对比其他三种调质最严格自受体负反馈机制的说明；新增[[serotonin-raphe-system]]和[[5-ht-autoreceptor]]连接；key_sources新增 PMID:15309042、PMID:10462127
- `concepts/gain-control.md`（revision_count 2→3）：新增5-HT自受体脱敏作为"第四个时间尺度"（天-周，情绪/可塑性层）的增益控制形式；新增[[serotonin-raphe-system]]和[[5-ht-autoreceptor]]连接

**登记矛盾（0）**：无新矛盾（海马神经发生争议已作为 status=contested 处理，未触发与现有 wiki 页面的直接矛盾）

**新增悬空引用（1）**：
- `major-depressive-disorder`：被 serotonin-raphe-system.md 引用，需单独文章覆盖

**图谱更新**：新增3个节点（serotonin-raphe-system, 5-ht-autoreceptor, hippocampal-neurogenesis），新增21条边；图谱总计58节点、308条边

---

## 2026-05-30（第三周综合·第 21 篇）

**源文章**：[[2026-05-30-week3-synthesis]] —《第三周综合：大脑的增益控制架构——神经调质如何在多重时间尺度上重配神经回路》

**新建页面（1）**：
- `concepts/multi-timescale-plasticity.md`（多层增益控制架构）🟡 emerging / 置信度中 — 第三周综合框架；三层嵌套（STP层一/ACh-NE层二/DA-RPE层三）；Marder原则（PMID:23040802）：解剖连接体只提供骨架，调质状态决定功能回路；来自 Thiele & Bellgrove 2018（PMID:29470969）的注意调质综述支撑；状态设为 emerging 因三层整合框架尚未被单一实验直接验证

**修订页面（3）**：
- `concepts/gain-control.md`（revision_count 1→2）：新增"第三周综合更新"段落，将皮层增益控制（层二，ACh/NE）定位为多层架构的第二层；新增与 [[multi-timescale-plasticity]]、[[short-term-synaptic-plasticity]]、[[dopamine-reward-prediction-error]] 的连接；opens_questions 新增 Q-gain-timescale-interaction；key_sources 新增 PMID:23040802、PMID:29470969
- `systems/neuromodulator-systems.md`（revision_count 1→2）：新增 Marder 原则（PMID:23040802）作为调质系统理论框架；新增多层架构定位；related 新增 [[multi-timescale-plasticity]]、[[short-term-synaptic-plasticity]]；opens_questions 新增 Q-gain-timescale-interaction、Q-marder-principle-cortex
- `concepts/short-term-synaptic-plasticity.md`（revision_count 1→2）：新增 [[multi-timescale-plasticity]] 和 [[gain-control]] 连接；定位 STP 为多层架构层一；opens_questions 新增 Q-gain-timescale-interaction

**悬空引用新增（1）**：
- 无新增悬空引用；`multi-timescale-plasticity` 页面的 prerequisites 均已有对应节点

**悬空引用解决（0）**：今日综合文章未针对现有悬空引用，专注整合框架

**矛盾登记（0）**：今日无新矛盾。多层框架（STP/ACh-NE/DA-RPE）各层独立证据充分，整合框架本身是理论综合（emerging 状态）而非具体机制争议

**图谱更新**：
- 新节点：multi-timescale-plasticity（54→55 总节点）
- 新边（9）：STP→multi（part-of）, gain-control→multi（part-of）, DA-RPE→multi（part-of）, ACh→multi（supports）, NE→multi（supports）, multi→neuromodulator-systems（related）, multi→working-memory（mechanism-of）, multi→orientation-selectivity（mechanism-of）, multi→alzheimers-disease（related）

**新增未解问题（3）**：
- Q-gain-timescale-interaction（高优先级）：三层增益控制之间的相互作用是否可预测？
- Q-marder-principle-cortex（中优先级）：Marder原则在哺乳类皮层的直接验证？
- Q-gain-architecture-ai（低优先级）：AI系统中的多层增益控制等效物设计？

---

## 2026-06-12（第三周·第 6 篇，文章 #20）

**源文章**：[[2026-06-12-neuromodulators-ach-ne]] —《注意的化学语言：乙酰胆碱与去甲肾上腺素如何向大脑发出行动指令》

**新建页面（4）**：
- `concepts/acetylcholine-cortex.md`（皮层乙酰胆碱）🟢 established / 置信度高 — 皮层ACh系统首个专页；基底前脑（Meynert核Ch4）解剖；M1受体（Gq→减少K⁺漏电流→促进持续放电）/M2受体（Gi→突触前自受体→负反馈）/α4β2+α7 nAChR功能分工；双时间尺度（紧张背景+相位爆发）；皮层去同步化；核心来源：Herrero 2008（PMC2666819）
- `concepts/norepinephrine-locus-coeruleus.md`（去甲肾上腺素/蓝斑系统）🟢 established / 置信度高 — NE系统首个专页；蓝斑（LC）解剖（约5万个神经元，投射全皮层）；α2A（高亲和力Gi→HCN抑制→PFC WM稳定）/α1（低亲和力Gq→噪声增加）/β（Gs→LTP促进）三受体分工；倒U型调节曲线；相位-紧张模式（Aston-Jones & Cohen 2005）；PFC→LC自上而下控制
- `systems/neuromodulator-systems.md`（神经调质系统总览）🟢 established / 置信度高 — 四大调质系统（ACh/NE/DA/5-HT）首个综合页；紧张 vs 相位释放区分；受体亲和力梯度；核心区别：调制"如何处理"而非"处理什么"；连接8个既有节点
- `concepts/gain-control.md`（皮层增益控制）🟢 established / 置信度高 — 增益控制首个专页；响应增益（斜率变化）vs 对比度增益（阈值移动）；乘法性增益实现机制（M1→K⁺漏电；NE/α2A→HCN抑制）；除法归一化（PV+中间神经元）；信噪比改善；核心来源：Herrero 2008/2017、Edeline 2012

**修订页面（2）**：
- `systems/v1-primary-visual-cortex.md`（revision_count 1→2）：新增"神经调质对 V1 的调制"小节（ACh/肌碱受体介导注意调制，Herrero 2008，东莨菪碱P<0.001，美加明P=0.465，注意效应~20-50%响应增益）；related 新增 acetylcholine-cortex, gain-control；opens_questions 新增 Q-ach-ne-02；key_sources 新增 PMID:18633352；source_articles 新增 2026-06-12
- `concepts/working-memory.md`（revision_count 3→4）：新增"NE 和 ACh 对工作记忆的调制"小节（α2A→HCN抑制→WM表征稳定；α1→噪声→应激性认知崩溃；胍法辛ADHD临床；M1→持续放电；α7-nAChR→NMDA稳定性）；related 新增 norepinephrine-locus-coeruleus, acetylcholine-cortex；key_sources 新增 PMID:16254995, PMID:23818597；source_articles 新增 2026-06-12

**悬空引用新增（2）**：
- `basal-forebrain`（被 acetylcholine-cortex/norepinephrine-locus-coeruleus 引用）— 基底前脑解剖待专页
- `locus-coeruleus-anatomy`（被 norepinephrine-locus-coeruleus 引用）— LC详细解剖专页待建立

**悬空引用解决（0）**：今日无旧悬空引用被填补。

**矛盾登记（0）**：今日无新矛盾。两个现有开放矛盾（C-2026-05-24-01, C-2026-05-25-01）今日文献未直接涉及，状态不变。

**图谱更新**：
- 新节点：acetylcholine-cortex, norepinephrine-locus-coeruleus, neuromodulator-systems, gain-control（50→54 总节点）
- 新边：22条（含 acetylcholine-cortex→v1-primary-visual-cortex(regulates)、acetylcholine-cortex→working-memory(regulates)、norepinephrine-locus-coeruleus→working-memory(regulates)、norepinephrine-locus-coeruleus→ltp(regulates)、gain-control→v1-primary-visual-cortex(mechanism-of)、neuromodulator-systems→acetylcholine-cortex(contains)等；256→278 总边数）
- 新增悬空引用：basal-forebrain, locus-coeruleus-anatomy

---

## 2026-06-11（第三周·第 5 篇，文章 #19）

**源文章**：[[2026-06-11-v1-orientation-selectivity]] —《V1初级视觉皮层的方向选择性：从随机输入到精确编码》

**新建页面（3）**：
- `systems/v1-primary-visual-cortex.md`（初级视觉皮层V1）🟢 established / 置信度高 — 首个 systems 层视觉脑区页面；视觉信息皮层第一站；简单/复杂细胞区分（F1/F0）；方向柱/超柱/pinwheel（猫/猴，Ohki 2005 PMID:15660108）；盐-胡椒型组织（小鼠，Niell 2010 PMID:20810772）；三层方向选择性机制（前馈/E-I平衡/NMDA棘波）；树突突触聚类与OSI正相关（Wilson 2016 PMC5240628）；连接8个既有节点（dendritic-computation、nmda-receptor、pv-interneurons、sst-interneurons、prefrontal-cortex等）
- `concepts/orientation-selectivity.md`（方向选择性）🟢 established / 置信度高 — V1核心计算特性；OSI定量定义（HWHM约25-30°）；对比度不变性由E/I维持；三层机制（前馈LGN排列、E/I平衡网络、树突NMDA棘波聚类）；物种比较（猫/猴有方向柱 vs 小鼠盐-胡椒，OSI分布相似）；CNN Gabor滤波器收敛（Kindel 2019）；连接6个既有节点
- `concepts/synaptic-clustering.md`（突触聚类）🟡 emerging / 置信度中 — **填补 dendritic-computation 页面的长期悬空引用**；功能相似突触在同一树突分支聚集→NMDA棘波超线性整合；Wilson 2016（雪貂V1，双光子GCaMP6s）首次体内直接证据：聚类程度与OSI正相关，偏好方向热点2倍于非偏好方向；Smith 2013（PMID:24162850）独立验证；体外原理验证established，体内普遍性为emerging；开放问题：小鼠V1/海马/PFC中的聚类是否同样存在；连接5个既有节点

**修订页面（1）**：
- `neurons/dendritic-computation.md`（revision_count 3→4）：新增 V1 突触聚类体内证据节（Wilson 2016，雪貂V1双光子成像，OSI与聚类程度正相关，偏好方向NMDA棘波热点2倍）；部分解答 Q-synaptic-clustering-prevalence（体内存在，但物种/脑区普遍性仍open）；related 新增 synaptic-clustering, orientation-selectivity, v1-primary-visual-cortex；key_sources 新增 PMID:27383898；source_articles 新增 2026-06-11

**悬空引用新增（0）**：今日无新悬空引用（V1文章涉及概念均已在新建页面或既有页面中处理）。

**悬空引用解决（1）**：
- ~~`synaptic-clustering`~~ ✅ 已建立（concepts/synaptic-clustering.md）——自 2026-05-27 dendritic-computation 创建时起的悬空引用，历时14逻辑日

**矛盾登记（0）**：今日无新矛盾。两个现有开放矛盾（C-2026-05-24-01, C-2026-05-25-01）今日文献未直接涉及，状态不变。

**图谱更新**：
- 新节点：v1-primary-visual-cortex, orientation-selectivity, synaptic-clustering（47→50 总节点）
- 新边：13条（orientation-selectivity↔v1-primary-visual-cortex、orientation-selectivity→dendritic-computation、orientation-selectivity→nmda-receptor、orientation-selectivity→pv-interneurons、synaptic-clustering→dendritic-computation、synaptic-clustering→nmda-receptor、synaptic-clustering→orientation-selectivity、dendritic-computation→synaptic-clustering、v1-primary-visual-cortex→dendritic-computation、v1-primary-visual-cortex→pv-interneurons、v1-primary-visual-cortex→sst-interneurons、v1-primary-visual-cortex→prefrontal-cortex；243→256 总边数）
- 解决悬空：synaptic-clustering

---

## 2026-06-10（第三周·第 4 篇，文章 #18）

**源文章**：[[2026-06-10-stp-short-term-plasticity]] —《瞬息之变：短时程突触可塑性的分子机制与计算逻辑》

**新建页面（2）**：
- `concepts/short-term-synaptic-plasticity.md`（短时程突触可塑性）🟢 established / 置信度高 — 四种形式（易化/抑制/增强/PTP）的分子机制全覆盖；Syt7为脑内多突触易化的主要传感器（Jackman & Regehr 2017，PMID:28472650）；RRP耗竭驱动抑制（Zucker & Regehr 2002，PMID:11826273）；频率不变传输（Turecek 2017，PMID:29088700）；Mongillo活动无声工作记忆模型（PMID:18339943）；高p=低通/低p=高通计算逻辑（Tsodyks-Markram 1997，PMID:9012851）；连接9个既有节点
- `neurons/readily-releasable-pool.md`（就绪释放池/RRP）🟢 established / 置信度高 — 填补 synaptic-transmission 等多页引用的悬空引用；RRP停靠/就绪机制（Rab3-RIM/Munc13/Munc18-1）；RRP耗竭数学模型（PPR ≈ 1-p）；钙加速补充（10倍加速，PMID:22751149）；连接6个既有节点

**修订页面（2）**：
- `neurons/synaptotagmin.md`（revision_count 2→3）：大幅扩展Syt7作为易化传感器的机制（4种突触PPF KO实验；高钙亲和力 Kd ~1.5 μM；慢解离约60倍；频率不变传输PC→DCN）；related 新增 short-term-synaptic-plasticity；key_sources 新增 PMID:28472650, PMID:29088700；source_articles 新增 2026-06-10；更新 Q-syt7-facilitation-mechanism（主体机制已确立）；新增 Q-stp-syt7-human
- `concepts/working-memory.md`（revision_count 2→3）：related 新增 short-term-synaptic-plasticity；source_articles 新增 2026-06-10；连接段落新增 [[short-term-synaptic-plasticity]]；STP易化作为活动无声WM储存机制明确化

**悬空引用新增（0）**：今日无新悬空引用。

**悬空引用解决（1）**：
- ~~`readily-releasable-pool`~~ ✅ 已建立（neurons/readily-releasable-pool.md）

**矛盾登记（0）**：今日无新矛盾。两个现有开放矛盾（C-2026-05-24-01, C-2026-05-25-01）今日文献未直接涉及，状态不变。

**图谱更新**：
- 新节点：short-term-synaptic-plasticity, readily-releasable-pool（45→47 总节点）
- 新边：10条（STP↔synaptotagmin、STP↔readily-releasable-pool、STP↔synaptic-transmission、STP↔active-zone、STP↔voltage-gated-calcium-channels、STP↔working-memory、STP↔pv-interneurons、synaptotagmin↔short-term-synaptic-plasticity、readily-releasable-pool↔synaptic-transmission、readily-releasable-pool↔active-zone；233→243 总边数）
- 解决悬空：readily-releasable-pool

---

## 2026-06-09（第三周·第 3 篇，文章 #17）

**源文章**：[[2026-06-09-optogenetics-causal-neuroscience]] —《光遗传学：用一束光解开神经回路的因果之谜》

**新建页面（1）**：
- `methods/optogenetics.md`（光遗传学）🟢 established / 置信度高 — **methods 层第一个页面，填补完全空白的方法层**；ChR2（蓝光~470nm激活，7TM视黄醛门控阳离子通道，开放τ~1-2ms）+ NpHR（黄光~560nm沉默，Cl⁻泵，超极化~33mV，全文验证 PMID:17375185）分子机制；晶体结构（Kato 2012，2.3Å，C1C2嵌合体）；遗传特异性递送三策略（细胞特异性启动子/Cre-lox/c-fos-tTA）；假记忆实验（Ramirez 2013 Science）和效价翻转（Redondo 2014 Nature）因果实验；从相关性到因果性的方法论革命；与AI可解释性/mechanistic interpretability的类比；连接10个既有节点，新增14条边

**修订页面（1）**：
- `concepts/engram-cells.md`（revision_count 3→4）：补充 c-fos-tTA 标记系统技术细节（TetTag 小鼠、doxycycline 控制窗口、2-6% DG 稀疏性；全文来源 PMC3894458）；新增 [[optogenetics]] 到 related 字段；来源新增 PMID:24478647；来源文章新增 2026-06-09

**悬空引用新增（1）**：
- `channelrhodopsin`：被 optogenetics 引用，通道视紫质分子生物学专页（ChR1/ChR2 结构、光谱、工程变体）；待建页面

**矛盾登记（0）**：今日无新矛盾。C-2026-05-24-01（GABA 极性）和 C-2026-05-25-01（SNARE 就绪态）仍为 open，今日文献未直接涉及，未更新。

**图谱更新**：
- 新节点：optogenetics（45 个总节点）
- 新边：14条（optogenetics↔engram-cells、hippocampal-circuit、place-cell、pv-interneurons、ltp、dopamine-reward-prediction-error、disinhibitory-circuit、memory-consolidation、action-potential、synaptic-transmission、voltage-gated-sodium-channel；engram-cells↔optogenetics；hippocampal-circuit↔optogenetics）
- 新悬空：channelrhodopsin

---

## 2026-06-08（第三周·第 2 篇，文章 #16）

**源文章**：[[2026-06-08-alzheimers-amyloid-synaptic-mechanism]] —《记忆的分子遗忘：淀粉样寡聚体如何精准瓦解海马突触可塑性》

**新建页面（2）**：
- `diseases/alzheimers-disease.md`（阿尔茨海默病）🟢 established / 置信度高 — 首次建立疾病页（disease层空缺填补）；Aβ寡聚体5条并行通路；突触密度与认知衰退r=0.96（Terry 1991）；早期棘丢失可逆性（Shankar 2007）；斑块清除悖论（临床反向验证）；AD易损性分析（CA3-CA1高NR2B+内嗅皮层传播路径）；连接8个既有节点；新增未解问题Q-ad-vulnerable-synapses、Q-ad-tau-cascade、Q-ad-intervention-window
- `concepts/amyloid-beta-oligomers.md`（Aβ寡聚体）🟢 established / 置信度高 — Aβ寡聚体毒性物种认定（Walsh 2002：天然分泌寡聚体vs单体/纤维）；浓度数据（100-300 pM → 75%棘丢失）；PrPC/mGluR5/Fyn通路；突触外NR2B→p38/CREB通路；CaMKII降低60%、NR2B开放概率升高40%；连接6个既有节点

**修订页面（3）**：
- `concepts/ltp.md`（revision_count 5→6）：扩展"LTP病理镜像"段落（5条并行Aβ攻击通路；突触沉默可逆性早期干预意义）；related 新增 alzheimers-disease、amyloid-beta-oligomers；dimensions 新增 disease；key_sources 新增 PMID:11932745、17360908、21543591；连接 2 个新节点
- `concepts/nmda-receptor.md`（revision_count 3→4）：新增"第四重角色：突触外NR2B-LTP反向信号"小节；**解答 Q-nmda-alzheimer**（Aβ通过优先激活突触外而非突触内NR2B阻断LTP，而非直接破坏受体）；related 新增 alzheimers-disease、amyloid-beta-oligomers、calcineurin；dimensions 新增 disease；Q-nmda-alzheimer 更新为"已部分解答"
- `neurons/hippocampal-circuit.md`（revision_count 5→6）：新增AD易损性分析（CA3-CA1高NR2B密度+内嗅皮层Braak I期传播路径）；related 新增 alzheimers-disease、amyloid-beta-oligomers；dimensions 新增 disease；opens_questions 新增 Q-ad-vulnerable-synapses

**悬空引用新增（2）**：
- `bdnf-trkb`：被 alzheimers-disease 引用，BDNF/TrkB信号轴是L-LTP蛋白合成的关键上游；待建页面
- `prc-prion-protein`：被 amyloid-beta-oligomers、alzheimers-disease 引用，Aβ寡聚体的高亲和力细胞表面受体；待建页面

**矛盾登记（0）**：今日无新矛盾。theta-gamma耦合早于Aβ产生（Goutagny 2013）与Aβ→振荡失调（Mucke 2012）看似矛盾，但实为不同时间点的观察（振荡损伤先于Aβ大量积累，并非晚于），记录为未解问题Q-ad-vulnerable-synapses而非矛盾。

**解答的未解问题（1）**：
- Q-nmda-alzheimer（创建于 2026-05-26）："Aβ寡聚体如何选择性损害NMDA受体依赖的LTP？" → 已部分解答：Aβ通过PrPC/mGluR5/Fyn磷酸化NR2B，并优先激活突触外（而非突触内）NR2B/p38 MAPK/CREB失活通路；突触内vs突触外NR2B比例的AD中变化仍待研究

**图谱更新**：
- 新节点：alzheimers-disease、amyloid-beta-oligomers（44个总节点）
- 新增约12条边：alzheimers-disease→ltp/nmda-receptor/hippocampal-circuit/memory-consolidation/engram-cells/theta-oscillations；amyloid-beta-oligomers→ltp/nmda-receptor/calcineurin/camkii/ampa-receptor；等

---

## 2026-06-07（第三周·第 1 篇，文章 #15）

**源文章**：[[2026-06-07-dopamine-reward-prediction-error]] —《多巴胺奖励预测误差：大脑如何用一个信号重写所有预期》

**新建页面（3）**：
- `concepts/dopamine-reward-prediction-error.md`（多巴胺奖励预测误差）🟢 established / 置信度高 — VTA/SNc DA 神经元编码 δ = 实际奖励 − 预期奖励；Schultz 三种响应模式（正/零/负 RPE）；TD 学习的神经基底（Montague-Dayan-Sejnowski 1996）；三因素规则 Δw = (pre×post)×DA；D1/D2 双通路对称学习；DA 三大投射路径；连接 8 个已有节点；新增未解问题 Q-da-heterogeneity、Q-da-hippocampus-source
- `concepts/three-factor-learning-rule.md`（三因素学习规则）🟡 mainstream / 置信度高 — **填补 hebbian-learning 页面的悬空引用** — Δw = η·(pre×post)×M 统一框架；M = DA（奖励）/ ACh（注意）/ NE（显著性）三种调制因子；D1→cAMP→PKA 分子实现路径；Reynolds & Wickens 2002 在纹状体中的电生理验证；与 STC 解决 DA-Hebb 时间延迟问题的关系
- `concepts/synaptic-tagging-capture.md`（突触标记与捕获）🟡 mainstream / 置信度中 — 标记（~1-2 h 短暂 CaMKII 磷酸化）+ PRP 捕获（DA→D1→PKA→CREB→Arc/Homer/BDNF）将 E-LTP 转化为 L-LTP；解决 DA 来迟几秒~数十分钟的时间窗口问题；候选分子标签尚未完全确定（见 Q-stc-molecular-tag）

**修订页面（2）**：
- `concepts/hebbian-learning.md`（revision_count 2→3）：三因素规则小节从简述升级为完整分子机制（DA 作为 M 因子，D1→cAMP→PKA 链，Reynolds & Wickens 2002 验证，STC 解决时间延迟）；related 新增 dopamine-reward-prediction-error、synaptic-tagging-capture；三因素规则悬空引用标记为已建立
- `concepts/ltp.md`（revision_count 4→5）：新增"多巴胺调制的 LTP（DA-LTP）与突触标记-捕获"小节，详述 D1/D5→Gs→cAMP→PKA→GluA1 Ser845→CREB→PRP 分子链；related 新增 dopamine-reward-prediction-error、synaptic-tagging-capture、three-factor-learning-rule；key_sources 新增 PMID:7708662、PMID:9020359

**悬空引用解决（1）**：
- `three-factor-learning-rule`：首次出现于 hebbian-learning 页面，标记为"待建页面"；今日创建正式页面，hebbian-learning 已更新为"已建立"状态

**矛盾登记（0）**：今日无新矛盾。注：VTA DA 神经元功能异质性（奖励 vs 厌恶细胞）是活跃争议领域，记录为未解问题 Q-da-heterogeneity 而非矛盾，因两类细胞均有独立证据支持且互补而非互斥。

**图谱更新**：
- 新节点：dopamine-reward-prediction-error、three-factor-learning-rule、synaptic-tagging-capture（42 个总节点）
- 新增 14 条边（总计 207 条边）：含三因素规则→Hebb/LTP/竞争-遴选；DA-RPE→工作记忆/印迹细胞/记忆巩固；STC→CaMKII/Hebb；等

---

## 2026-06-06（第二周综合，文章 #14）

**源文章**：[[2026-06-06-week2-synthesis]] —《第二周综合：竞争法则——大脑如何在五个层次上通过竞争与遴选构建精简的世界模型》

**新建页面（1）**：
- `concepts/competition-selection-principle.md`（嵌套竞争-遴选架构）🟡 emerging / 置信度 medium — 大脑在突触（LTP/LTD Ca²⁺博弈）、细胞（CREB印迹竞争）、回路（PV+/SST+/VIP+时序门控）、系统（SWR选择性重播）、认知（PFC吸引子博弈）五个层次通过竞争决定记忆遴选；与嵌套时间编码层级互补（后者决定何时，前者决定选什么）；连接 10 个既有节点；第二周综合分析框架（分析性抽象，非命名理论）

**修订页面（3）**：
- `concepts/engram-cells.md`（revision_count 2→3）：新增"印迹细胞分配的竞争机制"小节，将 CREB 竞争纳入嵌套竞争-遴选架构的细胞层次；related 新增 competition-selection-principle
- `concepts/memory-consolidation.md`（revision_count 1→2）：新增"系统巩固中的竞争遴选"小节，明确 SWR 选择性（非全量）重播和 SHY 假说作为竞争-遴选的极端形式；related 新增 competition-selection-principle
- `concepts/working-memory.md`（revision_count 1→2）：新增"工作记忆容量的吸引子竞争机制"小节，从竞争角度解释约4项上限（θ/γ嵌套约束 + 吸引子干扰两种假说）；related 新增 competition-selection-principle

**矛盾登记（0）**：今日无新矛盾。综合框架（竞争-遴选）与既有知识无冲突——它是分析性抽象而非独立的实证主张。

**图谱更新**：
- 新节点：competition-selection-principle（39 个总节点）
- 新增 15 条边（总计 193 条边）：competition-selection-principle 与 ltp/ltd/engram-cells/memory-consolidation/pv-interneurons/sst-interneurons/vip-interneurons/working-memory/sharp-wave-ripples/temporal-coding-hierarchy 的双向/单向连接

**本周知识库增长（第8-14篇）**：节点 23→39（+16），边 86→193（+107）；覆盖层级首次扩展至 systems/prefrontal-cortex；disease 和 methods 层仍空缺

---

## 2026-06-05（第二周·第 6 篇，文章 #13）

**源文章**：[[2026-06-05-prefrontal-working-memory]] —《γ 爆发、静默突触与持续放电：前额叶皮层如何在数秒内维持工作记忆》

**新建页面（4）**：
- `concepts/working-memory.md`（工作记忆）🟢 established / 置信度高 — 容量~4项临时信息系统；γ爆发（活动性编码）+ STP突触易化（静默储存）双机制；dlPFC吸引子回路 + PV-γ轴 + D1倒U型调节三支柱；工作记忆容量与θ/γ嵌套的可能关系；4个未解问题
- `concepts/persistent-activity.md`（持续活动/延迟期放电）🟢 established / 置信度高 — PFC延迟期高于基线的神经活动；现已证明为间歇性γ爆发而非连续高频放电；依赖NMDA慢衰减和循环兴奋吸引子网络（Wang 2001）
- `concepts/gamma-oscillations.md`（γ振荡 30–80 Hz）🟢 established / 置信度高 — PV+篮状细胞PING机制产生；工作记忆中以~67ms爆发出现；精神分裂症中功率减弱与PV/GAD67损伤相关；θ/γ嵌套编码层级
- `systems/prefrontal-cortex.md`（前额叶皮层）🟢 established / 置信度高 — dlPFC L2/3 循环回路是WM关键脑区；多巴胺D1倒U型调节；深层L3d对压力/疾病的选择性脆弱性；跨物种比较（啮齿类→猕猴→人类）

**修订页面（2）**：
- `circuits/pv-interneurons.md`：系统层面新增PFC γ爆发WM应用（Lundqvist 2016）和精神分裂症病理证据（Hughes 2024）；related新增 working-memory, gamma-oscillations, prefrontal-cortex；dimensions新增 cognition；revision_count 1→2
- `concepts/nmda-receptor.md`：新增第三重角色——PFC吸引子回路时间积分器（慢衰减τ~100-300ms支撑循环激活；Wang 2001）；related新增 persistent-activity, working-memory, prefrontal-cortex；dimensions新增 brain-region；revision_count 2→3

**系统新增**：首次建立 `wiki/systems/` 子目录，知识库从分子/细胞/回路扩展到脑区/系统层级

**矛盾登记（0）**：今日无新矛盾。注意：活动性 WM vs 活动无声 WM 两种模型的相对贡献尚无定论，但两者并非互斥，记录为未解问题 Q-wm-active-vs-silent 而非矛盾（两种机制均有证据支持，互补而非冲突）。

**悬空引用新增**：dopamine-d1（dlPFC 倒 U 型调节中频繁引用，待建页面）；activity-silent-wm（Mongillo 2008 模型的独立概念页，可建）

---

## 2026-06-04（第二周·第 5 篇，文章 #12）

**源文章**：[[2026-06-04-ltd-long-term-depression]] —《遗忘的精准：突触如何弱化自身，以及这为何是大脑最聪明的设计》

**新建页面（3）**：
- `concepts/ltd.md`（长时程抑制 LTD）🟢 established / 置信度高 — NMDA-LTD（PP2B/PP1/GluA1去磷酸化/GluA2-Ser880-PICK1内吞）+ mGluR-LTD（Arc/dynamin内吞）+ 小脑 LTD（PKC/GluA2-Ser880）；AKAP150 机制；脆性 X 综合征连接；LTD 在 AD、恐惧消退、睡眠稳态中的角色；4 个未解问题
- `concepts/calcineurin.md`（钙调磷酸酶 PP2B）🟢 established / 置信度高 — 高亲和力 Ca²⁺ 磷酸酶；中低 Ca²⁺ 时优先激活；PP2B→PP1→GluA1去磷酸化；AKAP150 空间定位机制；与 CaMKII 构成 LTP/LTD 方向性的分子开关
- `concepts/arc-arg31.md`（Arc/Arg3.1）🟢 established / 置信度高 — 即早基因活动量规器；树突局部翻译；LTD 中与 dynamin/endophilin 结合→AMPAR 内吞；LTP 巩固中稳定肌动蛋白；Arc 敲除 L-LTP 受损；突触稳态下调的分子感受器

**修订页面（2）**：
- `concepts/ltp.md`：新增 LTD 作为双向对称的完整图景；related 从 ltp-ltd（悬空）改为 ltd（已建立）；新增 calcineurin 进 related；source_articles 新增 2026-06-04；revision_count 3→4
- `concepts/ampa-receptor.md`：新增"LTD 期间 AMPA 受体内吞"机制段落（GluA2 Ser880 磷酸化→PICK1路径；Arc/dynamin；GluA2 双敲除争议）；related 新增 ltd, calcineurin, arc-arg31；key_sources 新增 PMC4195488, PMC2694745；revision_count 1→2

**矛盾登记（0）**：今日无新矛盾。发现一个既有争议：GluA2/GluA3 双敲除后 LTD 仍然正常（Huganir & Nicoll 2013），与 GluA2 Ser880/PICK1 路径为必需机制的描述存在张力——但这不与 wiki 现有主张冲突（现有 AMPA-receptor 页原本未声明 GluA2 必需），记录为 Q-ltd-glua2-redundancy 未解问题。

**悬空引用解决**：
- `ltp-ltd`（ltp 页 related 字段悬空引用）✅ 改为已建立的 `ltd` 页面，悬空消除

**新增悬空引用**：
- `mglur-ltd`：被 ltd.md 和 arc-arg31.md 引用；目前内容已合并于 ltd 页面，可在未来单独展开

**已登记开放矛盾状态**（无变化）：
- `C-2026-05-24-01`（AIS GABA 极性）：仍 open
- `C-2026-05-25-01`（SNARE 就绪态装配状态）：仍 open

---

## 2026-06-03（第二周·第 4 篇，文章 #11）

**源文章**：[[2026-06-03-inhibitory-interneuron-diversity]] —《回路中的少数精锐：三类抑制性中间神经元如何统治大脑的计算时序》

**新建页面（4）**：
- `circuits/pv-interneurons.md`（PV+ 中间神经元）🟢 established / 置信度高 — 篮状细胞+吊灯细胞全貌；快速放电、围胞体抑制、γ振荡、0.7 ms 突触延迟；精神分裂症连接
- `circuits/sst-interneurons.md`（SST+ 中间神经元）🟢 established / 置信度高 — Martinotti 细胞、树突远端靶向、易化性输入特性；O-LM 细胞θ期功能；树突计算调控
- `circuits/vip-interneurons.md`（VIP+ 中间神经元）🟢 established / 置信度高 — 去抑制专家；被行为奖惩激活；主要抑制 SST+；Pi 2013 + Letzkus 2011
- `circuits/disinhibitory-circuit.md`（去抑制回路）🟢 established / 置信度高 — VIP→SST/PV→锥体细胞三级架构；学习门控；注意放大；跨皮层保守模块

**修订页面（3）**：
- `circuits/chandelier-cell.md`：新增 [[pv-interneurons]] 连接，纳入 PV+ 家族背景；revision_count 1→2
- `neurons/dendritic-computation.md`：新增 [[sst-interneurons]] 和 [[pv-interneurons]] 连接，填补 Q-inhibition-dendritic-spike-control 机制说明；revision_count 2→3
- `neurons/hippocampal-circuit.md`：新增 CA1 PV+ 篮状细胞（SWR 期涟漪产生者）和 SST+ O-LM 细胞（θ期 EC 输入门控）的角色描述；connected 到 pv-interneurons、sst-interneurons；revision_count 4→5

**矛盾登记（0）**：无新增矛盾。VIP 去抑制是否抑制 PV 部分的量化（主要抑制 SST 还是两者各半）在不同皮层区域有差异，但尚未引发与既有 wiki 内容的直接矛盾，记录为 Q-vip-sst-pv-ratio 未解问题。

**已登记开放矛盾状态**（无变化）：
- `C-2026-05-24-01`（AIS GABA 极性）：仍 open
- `C-2026-05-25-01`（SNARE 就绪态装配状态）：仍 open

**悬空引用解决**：
- `chandelier-cell → pv-interneurons` ✅ 新建 pv-interneurons 页面，吊灯细胞的 PV+ 家族归属现有完整背景页
- `dendritic-computation → sst-interneurons` ✅ 新建 sst-interneurons 页面，填补 Q-inhibition-dendritic-spike-control 机制说明

**新增悬空引用候选**：
- `three-factor-learning-rule`（三因素学习规则，VIP 去抑制的认知意义）→ 低优先级
- `e-i-balance`（兴奋-抑制平衡，精神疾病连接）→ 中优先级

**图谱**：节点 27→31（+4 新节点），边 136→约152（+~16 新边）

---

## 2026-06-02（第二周·第 3 篇，文章 #10）

**源文章**：[[2026-06-02-memory-consolidation-systems]] —《记忆的夜间旅行：大脑如何在睡眠中把海马的故事刻进皮层的石头》

**新建页面（1）**：
- `concepts/memory-consolidation.md`（记忆巩固·系统层面）🟢 established / 置信度高 — **填补了 hippocampal-circuit、sharp-wave-ripples、place-cell、engram-cells 共4个页面的最高优先级悬空引用**；整合系统巩固全貌（两阶段模型、SO-spindle-SWR三重奏、SCT vs MTT、CLS模型、SHY对立视角）；opens 4 个新未解问题

**修订页面（3）**：
- `concepts/sharp-wave-ripples.md`：填补 memory-consolidation 悬空引用解析完成；补充 SO-spindle-SWR 嵌套机制与因果破坏证据（PMID:26238360, 23589831）；key_sources +2；revision_count 1→2
- `neurons/hippocampal-circuit.md`：Q-hippocampal-consolidation-mechanism 内容通过 memory-consolidation 页面得到回答；来源文章增加 2026-06-02；revision_count 3→4
- `concepts/engram-cells.md`：补充系统巩固框架下沉默印迹的解读（被阻断的系统巩固）；来源文章增加 2026-06-02；revision_count 1→2

**矛盾登记（0）**：SHY（突触稳态假说）与主动系统巩固的张力已记录为 Q-shy-vs-active-consolidation 未解问题，但证据方向不完全对立（两者可能并行），未达到 contested_claims 登记门槛。

**已登记开放矛盾状态**（无变化）：
- `C-2026-05-24-01`（AIS GABA 极性）：仍 open
- `C-2026-05-25-01`（SNARE 就绪态装配状态）：仍 open

**悬空引用解决（1）**：
- `memory-consolidation` ✅ 已填补（被 hippocampal-circuit/sharp-wave-ripples/place-cell/engram-cells 共4个页面引用；最高优先级悬空引用之一）

**新增悬空引用**：memory-consolidation 页面的 related 字段中 `CLS-model`（互补学习系统）和 `slow-oscillation`（皮层慢振荡）可考虑在未来建立独立页面，已添加为低优先级悬空引用候选。

**图谱**：节点 26→27，边 120→136，新增 16 条边（memory-consolidation 出发 8 条 + 其他节点指向 memory-consolidation 8 条）。

---

## 2026-06-01（第二周·第 2 篇，文章 #9）

**源文章**：[[2026-06-01-voltage-gated-calcium-channels]] —《神经元的三重钙门：电压门控钙通道如何在不同地点执行截然不同的命令》

**新建页面（1）**：
- `neurons/voltage-gated-calcium-channels.md`（电压门控钙通道）🟢 established / 置信度高 — 填补了 synaptotagmin、active-zone、synaptic-transmission、nmda-receptor、dendritic-computation、btsp 共 6 个页面的最高优先级悬空引用（calcium-channel）；整合三亚家族（CaV1/CaV2/CaV3）的分类、结构（α1亚基四域架构）和三地点功能（突触前纳米域耦合、树突L型BTSP、核钙信号LTP）；opens 3 个新未解问题

**修订页面（3）**：
- `neurons/active-zone.md`：补充纳米域耦合量化数值（10-20 nm，23 nm，61 nm），P/Q型vs N型发育分布（P8→P16 转变），septin-5调控机制；更新 voltage-gated-sodium-channel→voltage-gated-calcium-channels 连接；key_sources 增 PMID:22183436, 25674049；revision_count 1→2
- `concepts/btsp.md`：明确L型通道（CaV1.2/1.3）作为平台电位的必要Ca²⁺来源（73% BTSP降低）；新增与 voltage-gated-calcium-channels 的连接；新增 Q-btsp-ltype-vs-nmda 未解问题；revision_count 1→2
- `neurons/synaptotagmin.md`：将悬空引用 calcium-channel 解析为 voltage-gated-calcium-channels；补充synprint位点与Syt1 C2B域的预结合机制（20 μM Ca²⁺时最强）；revision_count 1→2

**矛盾登记（0）**：今日新内容与既有wiki主张无直接冲突。CaV1.2在LTP中同时参与早期（mTOR局部蛋白合成，Sridharan 2020）和晚期（转录，CREB，既有综述）LTP的发现，是对既有"L型通道参与晚期LTP"主张的**扩展**而非矛盾——在ltp.md中添加注记即可，无需登记矛盾。

**已登记开放矛盾状态**（无变化）：
- `C-2026-05-24-01`（AIS GABA 极性）：仍 open
- `C-2026-05-25-01`（SNARE 就绪态装配状态）：仍 open

**悬空引用解决（1）**：
- `calcium-channel` ✅ 已填补（以 voltage-gated-calcium-channels 为新slug，被 synaptotagmin/active-zone/synaptic-transmission/nmda-receptor/dendritic-computation/btsp 共 6 个页面引用）

**新增悬空引用（0）**：voltage-gated-calcium-channels 页面的所有 related 节点均已有对应页面；Q-vgcc-nanodomain-universal、Q-cav1-cav13-functional-split、Q-btsp-ltype-vs-nmda 已加入 unresolved_questions。

**图谱**：节点 25→26，边 108→120，新增 12 条边（voltage-gated-calcium-channels 出发 10 条 + 其他节点指向 VGCCs 2 条）。

---

## 2026-05-31（第二周·第 1 篇，文章 #8）

**源文章**：[[2026-05-31-engram-cells-optogenetic-proof]] —《印迹细胞的光子证明：记忆真的宿于特定神经元集合吗？》

**新建页面（1）**：
- `concepts/engram-cells.md`（印迹细胞）🟢 established / 置信度高 — 填补了 ltp、hebbian-learning、dendritic-computation、place-cell 共 4 个页面的高优先级悬空引用；记录 Liu 2012、Ryan 2015、Roy 2016、Ramirez 2013 四个里程碑实验；定义三条认定标准、竞争性分配机制、沉默印迹；opens 4 个新未解问题

**修订页面（3）**：
- `concepts/ltp.md`：新增印迹细胞作为 LTP 细胞层面体现（AMPA/NMDA 比值）；补充沉默印迹中 LTP 缺失的证据；光学 LTP 恢复 AD 印迹；related 加 engram-cells；key_sources 增 PMID:26023136, 26982728；revision_count 2→3
- `neurons/place-cell.md`：明确场所细胞作为空间情景记忆印迹细胞候选的实验证据；更新 [[engram-cells]] 连接描述；revision_count 2→3
- `neurons/hippocampal-circuit.md`：新增 DG 作为印迹分配竞争主要场所的描述（2–4% 稀疏性→正交性）；DG→CA3→CA1→BLA 印迹间连接链；连接加 engram-cells；revision_count 2→3

**矛盾登记（0）**：新证据（沉默印迹）与既有 wiki 内容无直接冲突；沉默印迹丰富了 LTP 与遗忘关系的理解，补充而非推翻既有主张。

**已登记开放矛盾状态**（无变化）：
- `C-2026-05-24-01`（AIS GABA 极性）：仍 open
- `C-2026-05-25-01`（SNARE 就绪态装配状态）：仍 open

**悬空引用解决（1）**：
- `engram-cells` ✅ 已填补（被 ltp/hebbian-learning/dendritic-computation/place-cell 共 4 个页面引用）

**新增悬空引用（0）**：engram-cells 页的所有 related 节点均已有对应页面；memory-consolidation 原已在悬空列表中。

**图谱**：节点 24→25，边 95→108，新增 13 条边（engram-cells 出发 9 条 + 其他节点指向 engram-cells 4 条）。

---

## 2026-05-30（第一周综合，文章 #7）

**源文章**：[[2026-05-30-week1-synthesis]] —《第一周综合：时间的阶梯——大脑如何在七个数量级的尺度上编码记忆》

**本次运行说明**：今日（UTC+8）为 2026-05-28，但前序会话已生成 2026-05-28 和 2026-05-29 的日常文章。本次运行按 ROUTINE.md"每 7 篇写周综合"规则写第 7 篇（周综合），逻辑日期顺延至 2026-05-30，维护序列完整性。情景层 append-only 规则已遵守。

**新建页面（1）**：
- `concepts/temporal-coding-hierarchy.md`（嵌套时间编码层级）🟡 emerging / 置信度中 — 综合分析框架；从亚毫秒（钙纳米域）到年（记忆持久），大脑在每个时间尺度通过"精确巧合检测"修改突触权重；7 层嵌套结构；连接 ltp/btsp/theta-oscillations/sharp-wave-ripples/phase-precession/nmda-receptor/dendritic-computation/place-cell/hebbian-learning 共 9 个节点；status=emerging（各层单独证据强，整合框架待系统验证）

**修订页面（1）**：
- `concepts/hebbian-learning.md`：新增"多尺度 Hebb 规则"一节——将 LTP（ms）、BTSP（s）、θ 序列（120ms 压缩 s 级）和 SWR（离线批量）统一在 Hebb 原理的多时间尺度实现框架下；related 新增 btsp/theta-oscillations/sharp-wave-ripples/temporal-coding-hierarchy；dimensions 扩展为 behavior/whole-brain-network；revision_count 1→2

**矛盾登记（0）**：本周综合未发现新的概念间冲突。嵌套时间编码层级中各层机制的证据相互支持，而非冲突。

**已登记开放矛盾状态**（无变化）：
- `C-2026-05-24-01`（AIS GABA 极性）：仍 open
- `C-2026-05-25-01`（SNARE 就绪态装配状态）：仍 open

**悬空引用解决（0）**：本次未填补新悬空引用（temporal-coding-hierarchy 是新建节点，非悬空引用填补）。

**新增悬空引用（0）**：无新增（temporal-coding-hierarchy 页的 prerequisites 都已有节点）。

**图谱**：节点 23→24，边 86→95，新增 9 条边（temporal-coding-hierarchy 出发的 8 条 + hebbian-learning→temporal-coding-hierarchy 1 条）。

**知识意义**：第一周（文章 1–7）完整记录了从单神经元分子机制（AIS, 突触释放, LTP）到海马空间记忆系统（场所细胞, θ振荡, SWR）的完整故事链。今日周综合提取出这一链条的统一原理：嵌套时间编码层级，为第二周（印迹细胞、记忆巩固、抑制性回路）提供了系统性参照框架。

---

## 2026-05-29

**源文章**：[[2026-05-29-theta-oscillations-phase-coding]] —《θ振荡与相位编码：大脑如何用节律将空间压缩成时间》

**新建页面（3）**：
- `concepts/theta-oscillations.md`（θ振荡）🟢 established — **填补高优先级悬空引用**（此前被 place-cell、ltp、hippocampal-circuit、grid-cell 共4个页面引用）；4–12 Hz 探索节律，由 MS-DBB 驱动；相位编码框架；θ序列（20:1压缩）；θ/γ嵌套（5-9个γ/θ）；θ与BTSP协调的新假说
- `concepts/sharp-wave-ripples.md`（尖波涟漪 SWR）🟢 established — CA3循环兴奋→CA1涟漪（110-200 Hz）；~20倍速序列重播；前向/反向/新颖路径重播；记忆固化机制；选择性SWR中断→记忆受损（因果证据）；两阶段记忆理论的离线阶段
- `concepts/phase-precession.md`（相位前进）🟢 established — O'Keefe & Recce 1993经典发现；放电相位随位置移动100–355°；θ序列的基础；振荡干涉 vs 双路径输入两种机制争议

**修订页面（2）**：
- `neurons/hippocampal-circuit.md`：新增"海马两种工作模式"（θ态/SWR态双模切换）章节；新增胆碱能张力作为切换开关的机制；key_sources 增加 PMID:26135716、PMID:23354386；revision_count 1→2
- `neurons/place-cell.md`：新增"相位前进"（第4节）：场所细胞的速率+相位双重编码，θ序列的20:1压缩；key_sources 增加 PMID:8353611、PMID:23354386；连接新增 [[phase-precession]]、[[sharp-wave-ripples]]；revision_count 1→2

**矛盾登记（0）**：今日证据与既有 wiki 主张无冲突。相位前进的振荡干涉 vs 双路径输入两种机制争议已在新建 phase-precession 页面中如实并列（不足以登记为contested_claim，因两者可能互补而非真实冲突）。

**悬空引用解决（1）**：
- `theta-oscillations`（θ振荡）— 已建页面（此前被 4 个页面引用，高优先级）

**新增悬空引用（1）**：
- `medial-septum`（内侧隔核/MS-DBB）— θ振荡主要起搏器，待建页面

**层级跨越**：今日进入**全脑网络（whole-brain-network）层**——θ振荡是全海马同步的网络现象；SWR是海马→新皮层的跨区信息传递机制。同时覆盖 behavior 层（序列编码、空间导航中的时间结构）。

**图谱**：节点 20→23，边 68→86，悬空引用：`theta-oscillations` 已填补，新增 `medial-septum`。

---

## 2026-05-28

**源文章**：[[2026-05-28-place-cells-btsp]] —《场所细胞：海马如何在单次穿越中一次性写入空间记忆》

**新建页面（4）**：
- `neurons/place-cell.md`（场所细胞）🟢 established — **填补高优先级悬空引用**；CA1 场所细胞通过 BTSP 单次写入场所场；O'Keefe 1971 认知地图假说；群体编码+重映射+序列编码
- `concepts/btsp.md`（行为时间尺度突触可塑性 BTSP）🟢 established — 独立于 LTP/STDP 的第三种突触可塑性规则；秒级时间窗口（±3–4 s）；不对称性（CA1）vs 对称性（CA3）；单次写入；NMDA 84% + L-型 Ca 通道 73% 依赖
- `neurons/hippocampal-circuit.md`（海马回路）🟢 established — DG/CA3/CA1 三突触回路；模式分离（DG）+ 模式补全（CA3）+ 整合输出（CA1）；并行穿孔通路；记忆巩固与重放
- `neurons/grid-cell.md`（网格细胞）🟢 established — MEC 六角网格放电；背侧→腹侧间距梯度；路径整合能力；振荡干涉 vs 连续吸引子两种机制假说

**修订页面（2）**：
- `neurons/dendritic-computation.md`：新增钙平台电位→BTSP 连接段；related 增加 place-cell/btsp/hippocampal-circuit；dimensions 增加 brain-region；key_sources 增加 PMID:28883072；revision_count 1→2
- `concepts/ltp.md`：新增 BTSP 作为平行可塑性规则段落；related 增加 btsp/place-cell/hippocampal-circuit；dimensions 增加 brain-region；key_sources 增加 PMID:28883072；revision_count 1→2

**矛盾登记（0）**：今日证据与既有 wiki 主张无冲突。BTSP 是 LTP 的**补充而非替代**；关于 BTSP 的单一路径 vs 多路径（Sumegi 2025）尚不足以登记矛盾（证据水平差异过大：胞内记录 vs 群体钙成像）。

**悬空引用解决（1）**：
- `place-cell`（场所细胞）— 已建页面（此前被 [[树突计算]] 引用，高优先级）

**新增悬空引用（4）**：
- `engram-cells`（印迹细胞）— 场所细胞 × 记忆行为证据，今日 place-cell 页新引用
- `path-integration`（路径整合）— 网格细胞无地标时维持放电的内源机制
- `memory-consolidation`（记忆巩固）— 海马 SWR 重放→皮层巩固机制
- `theta-oscillations`（θ振荡）— 调控 BTSP 触发时机和场所场形成节律（已在旧悬空引用列表中，今日新证据加强了其重要性）

**层级跨越**：今日从细胞/微回路层（昨日）跨入**脑区层（brain-region）**——从单神经元的树突计算，到海马亚区的回路分工，到内嗅-海马系统的空间地图构建。

**图谱**：节点 16→20，边 50→68，悬空引用：`place-cell` 已填补，新增 path-integration / memory-consolidation；engram-cells 和 theta-oscillations 已在旧列表中。

---

## 2026-05-27

**源文章**：[[2026-05-27-dendritic-computation]] —《树突：神经元内部的神经网络——NMDA 棘波与 Ca²⁺ 棘波如何使一根树突变成一台计算机》

**新建页面（2）**：
- `neurons/dendritic-computation.md`（树突计算）🟢 established — 填补 Hodgkin-Huxley 模型页的长期悬空引用；NMDA 棘波（50–200 ms，全或无）+ Ca²⁺ 棘波 + 两层神经网络等价；体内证据：视觉皮层朝向选择性 + 海马场所场快速形成
- `neurons/pyramidal-neuron.md`（锥体神经元）🟢 established — 树突计算的物理载体；双树突系统（顶端 tuft top-down + 基底 bottom-up）是前馈/反馈整合的结构基础；连接 AIS、chandelier-cell、dendritic-computation

**修订页面（2）**：
- `concepts/nmda-receptor.md`：新增"NMDA 受体的双重身份"概念（突触层面巧合检测器 vs 树突分支层面 NMDA 棘波计算单元）；关键证据表新增 Smith 2013（体内 OSI 0.82→0.45）和 Schiller 2000（首次 NMDA 棘波）；连接新增 dendritic-computation；dimensions 新增 cellular；revision_count 1→2
- `concepts/hodgkin-huxley-model.md`：[[树突计算]] 悬空引用已填补，source_articles 补充今日文章；revision_count 1→2

**矛盾登记（0）**：今日新证据与既有 wiki 主张无冲突。NMDA 受体的"树突棘波"维度是对已有突触LTP功能的扩展，而非冲突。

**悬空引用解决（1）**：
- `dendritic-computation`（树突计算）— 已建页面（此前在 hodgkin-huxley-model 中为悬空引用）

**新增悬空引用（3）**：
- `place-cell`（场所细胞）— 海马 CA1/CA3，体内树突平台电位证据来源，高优先级
- `synaptic-clustering`（突触聚类假说）— NMDA 棘波发生的关键前提，有争议
- `apical-tuft`（顶端簇）— L5锥体细胞 Ca²⁺ 棘波的发生地

**层级转换**：今日从分子/突触层（连续4天）跨入**细胞/微回路层**——NMDA 棘波是从"分子 NMDA 受体"到"细胞计算单元"的层级跨越。

**图谱**：节点 14→16，边 36→50，悬空引用 8→9（net，减1填补，加3新增）。

---

## 2026-05-26

**源文章**：[[2026-05-26-nmda-receptor-ltp]] —《NMDA 受体：突触的"巧合检测器"，以及大脑如何在神经元间刻写记忆》

**新建页面（5）**：
- `concepts/nmda-receptor.md`（NMDA 受体）🟢 established — 双重门控巧合检测器（谷氨酸 + 去极化解除 Mg²⁺），LTP 诱导的必要门卫，GluN2 亚型多样性决定时间整合窗口
- `concepts/ltp.md`（长时程增强）🟢 established — 突触可塑性核心机制：NMDA→CaMKII→AMPA 受体插入→突触增强；填补此前悬空引用
- `concepts/hebbian-learning.md`（Hebbian 学习）🟢 established — Hebb 规则的分子实现；三因素学习规则扩展；填补此前悬空引用
- `concepts/ampa-receptor.md`（AMPA 受体）🟢 established — 快速 EPSP 执行者，GluA1 S831 磷酸化，LTP 期间大量插入，"突触权重"的物理载体
- `neurons/camkii.md`（CaMKII）🟢 established — T286 自磷酸化实现"分子记忆翻转"；LTP 诱导和维持均必需（2021 关键实验）

**修订页面（2）**：
- `neurons/synaptic-transmission.md`：新增突触后受体层（AMPA/NMDA 的功能分工及其在 LTP 中的角色）；related/dimensions/key_sources 扩展；revision_count 1→2
- `neurons/action-potential.md`：补充反向传播动作电位（bAP）在 STDP/LTP 中的作用；related 新增 nmda-receptor、ltp、hebbian-learning；revision_count 2→3

**矛盾登记（0）**：今日新证据与既有主张无冲突。

**悬空引用解决（2）**：
- `ltp`（长时程增强）— 已建页面
- `hebbian-learning`（Hebb 规则）— 已建页面

**新增悬空引用（4）**：
- `theta-oscillations`（θ振荡）— LTP 体内诱导节律
- `engram-cells`（印迹细胞）— 记忆存储的细胞群体
- `three-factor-learning-rule`（三因素学习规则）— Hebb × 多巴胺
- `tarp-auxiliary-subunit`（TARP 辅助亚基）— AMPA 受体突触锚定关键

**层级跨越**：今日首次从分子/突触层（前两天主题）跨入**认知层**——NMDA 受体巧合检测 → LTP → Hebb 学习 → 记忆的分子基础。

**图谱**：节点 9→14，边 20→36。

---

## 2026-05-25

**源文章**：[[2026-05-25-synaptic-vesicle-exocytosis]] —《神经信号的化学渡口：钙离子如何在不到一毫秒内触发突触囊泡融合》

**新建页面（4）**：
- `neurons/synaptic-transmission.md`（突触传递）🟢 established — 填补此前悬空引用；突触前→突触后化学信号转化全流程，约100-200微秒
- `concepts/SNARE-complex.md`（SNARE复合体）🟢 established — Synaptobrevin+Syntaxin-1+SNAP-25四螺旋束拉链，融合驱动机器
- `neurons/synaptotagmin.md`（突触结合蛋白）🟢 established — C2A/C2B双域钙传感器，触发SNARE最终拉合
- `neurons/active-zone.md`（活动区）🟢 established — RIM/CAST/ELKS/Bassoon脚手架，纳米级精度定位钙通道与就绪囊泡

**修订页面（1）**：
- `neurons/action-potential.md`：新增下游连接节点（突触传递、活动区），扩展dimensions为synaptic层，revision_count 1→2

**矛盾登记（1）**：
- `C-2026-05-25-01`：SNARE就绪态模型争议——"部分拉合"（N端预组装，Complexin锁C端）vs "完全游离"（Ca²⁺到来后从头组装）；两种模型均有体外/体内证据，尚无定论（PMID:23060190；见 contested_claims.json）

**悬空引用解决（1）**：
- `synaptic-transmission` — 已建页面（此前为悬空引用）

**新增悬空引用（4）**：
- `calcium-channel`（电压门控钙通道）
- `complexin`（复合素）
- `readily-releasable-pool`（RRP）
- `munc18`（SM蛋白，次要）

**图谱**：节点 5→9，边 9→20。

---

## 2026-05-24

**源文章**：[[2026-05-24-axon-initial-segment]] —《决策的解剖学：神经元如何在混沌的输入中找到它唯一的声音》

**Wiki 初始化 + 首次固结**：本日建立语义层（`wiki/`）并从首篇文章固结出 5 个主题页。

**新建页面（5）**：
- `neurons/action-potential.md`（动作电位）🟢 established — 全或无脉冲，神经系统基本信息单位
- `neurons/axon-initial-segment.md`（轴突始段）🟢 established — 动作电位诞生地，本日核心节点（5 条边、5 个未解问题）
- `neurons/voltage-gated-sodium-channel.md`（电压门控钠通道）🟢 established — 动作电位上升相分子引擎
- `concepts/hodgkin-huxley-model.md`（Hodgkin-Huxley 模型）🟢 established — 动作电位的数学框架
- `circuits/chandelier-cell.md`（吊灯细胞）🔵 mainstream / 置信度中 — 特异抑制 AIS（机制有争议）

**修订页面（0）**：无（首日，全部为新建）

**矛盾登记（0）**：无新矛盾。

**新增悬空引用（待补缺口）**：
- `dendritic-computation`（树突计算）— 被 Hodgkin-Huxley 模型页引用
- `synaptic-transmission`（突触传递）— 课程脊柱下一站

**图谱**：节点 5，边 9。

---

## 2026-06-03 · 文章 #72 · 时间刻入神经回路：大脑发育关键期的开关机制与可塑性窗口的重启

**核心主题**：视觉皮层关键期（Critical Period）的分子开关机制——GABA 阈值触发开启，PNN/OTX2/Lynx1 三道刹车主动关闭，ChABC/氟西汀/催产素重开关键期。

**新建页面（1）**：
- `concepts/critical-period.md`（发育关键期）🟢 established — PV+成熟/PNN/OTX2/BDNF/Lynx1机制；19篇来源（13篇开放全文）；连接 pv-interneurons, perineuronal-nets, ei-balance, bdnf, microglia, synaptic-pruning, ltp, ltd

**修订页面（3）**：
- `concepts/perineuronal-nets.md` rev2 — 新增机制3（PTPσ-TRKB轴统一ChABC/氟西汀机制，Lesnikova 2021，PMC7880295）；新增成年PNN动态调节证据（Devienne 2021，PMC8265812）；related新增 critical-period, microglia
- `circuits/pv-interneurons.md` rev4 — 新增关键期角色：PV+去激活是ODP首要微回路事件（Kuhlman 2013，PMC3962838），OTX2经PNN驱动PV成熟（Sugiyama 2008/Beurdeley 2012），BDNF设定PV成熟时间轴（Huang 1999），Rett综合征MeCP2 KO使关键期错位（Krishnan 2015，PMC4553776），小胶质细胞上游调控（Wang 2025，PMC12013681）；related新增 critical-period, bdnf, microglia
- `concepts/bdnf.md` rev2 — 新增关键期相关角色：BDNF驱动GABAergic成熟时间轴，PNN-aggrecan-PTPσ轴抑制BDNF信号进入PV+细胞；related新增 critical-period, pv-interneurons, perineuronal-nets

**矛盾登记（0）**：无新矛盾；Q-pnn-human-therapy（已有，关键期视角下新增 Q-cp-01至Q-cp-04）

**新增开放问题**：Q-cp-01（人类视觉CP时序）、Q-cp-02（语言CP分子机制）、Q-cp-03（SSRI临床转化可塑性重开安全性）、Q-cp-04（不同脑区CP时间窗口的分子决定因素）

**新增悬空引用（需补）**：无新悬空引用（critical-period所需关联节点均已存在）

**图谱**：133节点，754边（+1节点，+10边）

## 2026-07-25 · 文章 #93 · 大脑如何读懂另一颗大脑：镜像神经元、心智理论与社会预测编码

**核心主题**：社会脑——镜像神经元系统（MNS）的功能重新定位（低层动作区分而非意图理解）+ 心智化网络（TPJ/mPFC/pSTS/TP）的神经回路 + 社会预测编码统一框架（Koster-Hale & Saxe 2013：ToM作为神经预测问题）

**新建页面（3）**：
- `concepts/theory-of-mind.md`（心智理论）🟡 established/high — 错误信念测试机制、多层次ToM（一阶/二阶/更高阶）、神经底层（TPJ/mPFC/STS）、预测编码框架、与镜像系统的区分；来源：PMID:12948738, PMID:17714666, PMID:34241539, PMID:24012000
- `concepts/mentalizing-network.md`（心智化网络）🟡 mainstream/medium — mPFC+TPJ+pSTS+TP+PCu节点分工表；层级时间尺度预测（Koster-Hale & Saxe 2013）；与镜像系统的效应连接控制（Sobeh & Shamay-Tsoory 2025 PMCID:PMC12651549）；情感共情 vs 认知共情分离；来源：6项（4项开放全文）
- `systems/tpj-temporoparietal-junction.md`（颞顶联合区）🟡 mainstream/medium — 右侧TPJ-M的功能特异性（Saxe 2003）；TMS因果证据；108项元分析确认跨范式收敛（Merchant 2025 PMCID:PMC12617318）；双功能（心智化 vs 注意重定向）共存的解剖解释；来源：PMID:12948738, PMID:24012000, PMID:41245222

**修订页面（1）**：
- `circuits/mirror-neurons.md` rev2 — 大幅更新当前理解：纳入Hickok 2009（8个问题）和Heyes & Catmur 2022（PMC8785302，10年系统综述）；明确功能限于低层动作区分；破镜理论无支持；新增related（theory-of-mind/mentalizing-network/predictive-coding）和Q-mirror-01

**矛盾登记（0）**：镜像神经元理论的争议已在mirror-neurons页面如实呈现，属于既知分歧，无新注册矛盾（旧观点弱化而非新冲突出现）

**新增开放问题**：Q-tom-01（TPJ具体计算角色）、Q-tom-02（mPFC去中心化机制）、Q-tom-03（LLM的"ToM"与生物ToM）、Q-mn-01（mentalizing-network节点因果分工）、Q-mn-02（个体差异预测）、Q-mirror-01（ASL模型因果证据）

**新增悬空引用（需补）**：无新悬空引用

**图谱**：188节点，1090条边（+4节点，+16条边）


## 2026-07-26 · 文章 #94 · 感同身受的神经密码：前岛叶皮层如何将内感受转化为共情

**核心主题**：前岛叶皮层（AIC）的共情机制——内感受预测编码（EPIC 模型）、自-他共享表征、与前扣带回（ACC）的功能分工、冯·伊科诺莫神经元的演化与功能；共情的社会调节（种族偏见、专业经验、公平感）

**新建页面（4）**：
- `systems/anterior-insula.md`（前岛叶皮层）🟢 established/high — 后→前岛叶内感受梯度；AIC 是共情因果必要节点（Gu 2012 损伤研究）；EPIC 内感受预测编码；VEN 第 Vb 层；自动化任务无关响应；来源：PMID:22961548, PMID:20220007, PMID:23749500, PMID:26016744, PMID:30985277
- `concepts/empathy.md`（共情）🟢 established/high — 情感共情（AIC/ACC）vs 认知共情（TPJ/mPFC）双解离；Singer 2004 开创性实验；Fallon 2020 元分析共享/特异网络；社会调节因素（内群效应、专业经验）；来源：PMID:14976305, PMID:22961548, PMID:32608498, PMID:23898249
- `concepts/interoception.md`（内感受）🟢 established/high — EPIC 模型（Barrett & Simmons 2015）；内感受预测编码后→前梯度；情感体验作为内感受预测输出；与情感共情的机制关联；来源：PMID:26016744, PMID:30985277, PMID:23749500
- `neurons/von-economo-neurons.md`（冯·伊科诺莫神经元）🟡 emerging/medium — 形态（纺锤形，~4.6× 邻近锥体细胞）；AIC+ACC 第 Vb 层；物种分布（大猿/鲸豚/大象）；bvFTD 中减少 69% 伴社会认知损失；演化约 2500 万年前；因果作用待确认

**修订页面（2）**：
- `concepts/theory-of-mind.md` rev2 — 新增 empathy、anterior-insula 连接；明确认知共情（ToM）与情感共情（AIC）的双轨关系
- `concepts/mentalizing-network.md` rev2 — 新增 empathy、anterior-insula、interoception 连接；明确双轨社会脑框架

**矛盾登记（0）**：无新矛盾；现有 7 条开放矛盾状态不变

**新增开放问题**：Q-empathy-01（特质共情稳定神经基础）、Q-empathy-02（共情培训效果和 AIC 可塑性）、Q-aic-01（AIC 激活特异性：共情专属 vs 情感通用信号）、Q-ven-01（VEN 因果角色 vs 相关性标志）

**新增悬空引用（需补）**：anterior-cingulate-cortex（被 AIC 页多次引用，尚无专页）、social-cognition（empathy 页引用）

**图谱**：192 节点，1111 条边（+4 节点，+21 条边）

## 2026-06-06

### 今日主题：多巴胺能系统三重回路解剖（文章 #101，dopamine-systems-anatomy）

**创建 wiki 页面（4 个）：**
- `wiki/systems/vta.md`（腹侧被盖区）：建立 VTA 解剖结构、三条主要投射通路、VTA 内部拓扑异质性（内侧 vs 外侧 VTA 对奖励/厌恶的相反响应）；首次在知识库中明确区分 VTA 异质性（来源：de Jong 2022, PMID:35226827）
- `wiki/systems/substantia-nigra.md`（黑质）：建立 SNc/SN 解剖、黑质纹状体通路、三种遗传功能亚型（Calb1+/Vglut2+/Anxa1+）；Anxa1+ 为首次报告的运动加速专属亚型（来源：Azcorra 2023, PMID:37537242）
- `wiki/concepts/d1-d2-receptor-signaling.md`（D1/D2 受体信号）：建立 D1→Gs→cAMP↑→PKA 和 D2→Gi→cAMP↓→GIRK 的完整信号级联；DARPP-32 作为汇聚开关节点；D2 三重角色；PFC D1 倒 U 型（Weber 2022）
- `wiki/concepts/direct-indirect-pathway.md`（直接/间接通路）：建立纹状体 D1-MSN/D2-MSN 分别构成直接（Go）/间接（No-Go）通路；多巴胺协同效应；帕金森病通路失衡逻辑

**修订 wiki 页面（1 个）：**
- `wiki/concepts/dopamine-reward-prediction-error.md`（rev9→rev10）：新增 prerequisites: dopamine-systems-anatomy；related 新增 vta/substantia-nigra/d1-d2-receptor-signaling/direct-indirect-pathway；source_articles 新增今日文章；建立解剖基础—计算逻辑前后序关系

**新增未解问题（3 条）：**
- Q-da-anxa1（高优先级）：Anxa1+ 亚型的投射靶区和下游机制
- Q-da-aversion（中优先级）：内侧 VTA 厌恶编码多巴胺的化学身份验证
- Q-d1-inverted-u-mechanism（中优先级）：PFC D1 倒 U 型翻转的精确分子节点

**登记或裁决矛盾：** 无（今日无新矛盾被发现；现有矛盾不涉及今日主题）

**新增悬空引用待补：** `nucleus-accumbens`（NAc）页面（被今日文章多处引用，但无对应 wiki 页面）

---

## 2026-08-03（文章 #102：工作记忆神经密码之争）

**今日主题：** 工作记忆持续放电 vs 活动沉默 vs γ 爆发的三国博弈，以 Panichello 2024 Nature On/Off 态发现为高潮

**修订 wiki 页面（2 个）：**
- `wiki/concepts/working-memory.md`（rev6 → rev7）：新增 Panichello 2024 Neuropixels 8225 神经元 On/Off 态实验整合证据；新增"On/Off 态交替机制"小节；Q-wm-active-vs-silent 更新为部分解答；新增 Q-wm-onoff-01/02/03；key_sources 新增 PMID:39506106, PMID:34654556
- `wiki/concepts/persistent-activity.md`（rev1 → rev2）：新增 Wang 2021（吸引子框架与 γ 爆发兼容；活动沉默在主动WM局限）和 Panichello 2024 证据行；更新修订历史

**无新建页面：** 今日核心概念均已有对应 wiki 页面。

**图谱状态：** 209 节点，1209 边（无变化）

**登记或裁决矛盾：** 无。Q-wm-active-vs-silent 从"开放"标注为"部分解答（Panichello 2024）"，尚未完全裁决。

**新增悬空引用：** 无新增。原有悬空引用（motor-learning, deep-cerebellar-nuclei, inferior-olive, gaba）待后续填补。

---

## 2026-08-07（文章 #106：突触修剪的补体-小胶质机制与疾病联系）

**今日主题：** 补体 C1q/C3b 标记、小胶质细胞 CR3 吞噬、CD47/SRPX2 保护机制，以及精神分裂症（C4A 过激活→过度修剪）与自闭症（CD47 缺陷→修剪不足）的镜像疾病模型

**新建 wiki 页面（1 个）：**
- `wiki/diseases/autism-spectrum-disorder.md`（新建）：填补悬空引用；涵盖修剪不足假说（CD47-16p11.2）、突触装配蛋白突变假说（NL/Shank）、E/I 失衡假说三大通路；与精神分裂症镜像对比表；confidence=medium（机制异质性大）

**修订 wiki 页面（2 个）：**
- `wiki/concepts/synaptic-pruning.md`（rev1→rev2）：新增 SRPX2 机制（binds C1q, 保护 VGluT2+）；新增胶质-胶质 5-HT 时间门控段落（Nelson 2025）；新增 3 条证据表（SRPX2, CD47 autism, 5-HT glial）；添加 autism-spectrum-disorder 和 synaptogenesis 到 related；V1 ODP 不依赖补体的异质性注记；Q-pruning-04/05 新增
- `wiki/concepts/complement-cascade-cns.md`（rev1→rev2）：活动依赖调节小节扩充为"三方博弈"（CD47 + SRPX2 + C3b/PS）；新增 SRPX2 和 V1 皮层异质性注记；autism-spectrum-disorder 加入 related；Q-complement-02 新增

**图谱状态：** 219 节点（+1），1255 边（+6）；填补悬空引用 autism-spectrum-disorder

**登记或裁决矛盾：** 无新矛盾（SRPX2 保护 VGluT2+ 的不对称性是新信息，与既有内容无冲突，已整合）

**新增未解问题（4 条）：**
- Q-pruning-04（高优先）：SRPX2 与 CD47 通路串扰及 NL-NRXN 接合对两者的调控
- Q-pruning-05（中优先）：精神分裂症成年期补体修剪是否持续
- Q-complement-02（中优先）：SRPX2 优先保护 VGluT2+ 的机制
- Q-asd-01/02（高/中优先）：ASD 不同亚型突触密度方向性；CD47 通路在 ASD 的普遍性

**原有悬空引用状态：** autism-spectrum-disorder 已填补；motor-learning, deep-cerebellar-nuclei, inferior-olive, gaba 仍待补

## 2026-08-24 (文章 #122：语言左侧化起源)

### 新建 wiki 页面
- `wiki/concepts/language-lateralization.md` — 语言侧化机制综述；AST假说；先天vs后天；互补专化
- `wiki/concepts/foxp2-language-gene.md` — FOXP2 转录因子；KE家族；鸟类/小鼠/人类进化三角证据

### 修订 wiki 页面
- `wiki/concepts/planum-temporale.md` (rev1→rev2)：新增 Gannon 1998 黑猩猩 PT 左侧化数据、Leroy 2015 STAP 发现；修正 Geschwind 1968 PMID（5673631→5657070）；status 升级为 established
- `wiki/systems/language-network.md` (rev5→rev6)：related 新增 language-lateralization/foxp2-language-gene；key_sources 新增 AST/FOXP2 来源
- `wiki/concepts/language-critical-period.md` (rev1→rev2)：related+prerequisites 新增 language-lateralization；新增 Dehaene-Lambertz 2002 先天侧化证据

### 新增矛盾登记
- 无（今日无新矛盾；Q-pt-01 状态更新但未解决）

### 新增悬空引用（待补页面）
- `handedness-and-language`（在 language-lateralization.md related 中引用，尚无 wiki 页）

### 图谱变化
- 节点：256 → 264（+8，含原有计数误差修正）
- 边：1436 → 1471（+35）

## 2026-09-09 (文章 #139：成人大脑的秘密育儿所)

### 新建 wiki 页面（1 个）
- `wiki/concepts/neurogenesis-induced-forgetting.md` — 神经发生诱导遗忘 | emerging / medium | Akers 2014 双向因果证据（增加神经发生加速遗忘；降低婴儿期神经发生减轻婴儿失忆症；跨物种验证）；机制：突触竞争改写连接组

### 修订 wiki 页面（2 个）
- `wiki/concepts/adult-neurogenesis.md`（rev3→rev4）：新增遗忘功能段落（Akers 2014）；新增"数量 vs 活性解耦"认识（Betters 2025 氯胺酮活性依赖机制）；Bax KO 凋亡率数据更新（60-80%）；证据表新增2行；related 新增 neurogenesis-induced-forgetting/depression；key_sources 新增4条；opens_questions 新增 Q-ahn-01/02
- `wiki/concepts/pattern-separation.md`（rev2→rev3）：前馈抑制机制描述加深（McAvoy 2015 hilar mossy cells + PV+篮状细胞双路径；8周 vs 4周龄抑制强度差异）；key_sources 新增 PMID:26347621；source_articles 新增

### 登记或裁决矛盾
- 无新矛盾（今日来源与既有 wiki 主张一致，进一步强化而非冲突）

### 新增悬空引用（待补页面）
- 无新悬空引用（今日涉及概念均已有对应页面或已在本次创建）

### 图谱变化
- 节点：291 → 292（+1：neurogenesis-induced-forgetting）
- 边：1654 → 1658（+4）

### 新增未解问题（2 条）
- Q-ahn-01（中优先）：神经发生诱导遗忘的记忆类型选择性（恐惧条件化之外的记忆类型是否同样受影响）
- Q-ahn-02（中优先）：人类神经元数量 vs 活性的独立调控机制（SSRI/氯胺酮解耦现象是否存在独立的分子开关）

## 2026-09-13 (文章 #143：当 γ 节奏失声)

### 新建 wiki 页面（1 个）
- `wiki/diseases/schizophrenia.md` — 精神分裂症 | mainstream / medium | γ-PV 假说：DLPFC PV+ 细胞 GAD67/PV 分子缄默（非细胞死亡，Hashimoto 2003）→ PING 受损 → γ 功率降低 → θ-γ 耦合解体 → 工作记忆缺陷；NMDAR 低激活（Javitt 1991）→ GluN2A 选择性 PV 脆弱性（Hosseini 2025）；Kv3.1/3.2 治疗靶点

### 修订 wiki 页面（3 个）
- `wiki/circuits/pv-interneurons.md`（rev5→rev6）：新增"精神分裂症疾病视角"小节（GAD67缄默机制、NMDAR约束引用Gonzalez-Burgos 2012、Kv3靶点）；related 新增 schizophrenia/trkb-receptor/nmda-receptor；key_sources 新增 5 条；opens_questions 新增 Q-scz-pv-01/02
- `wiki/concepts/gamma-oscillations.md`（rev5→rev6）：新增"精神分裂症中的 γ 振荡缺陷"小节（SCZ γ功率临床证据、θ-γ耦合、Cardin/Sohal 2009 因果证据、GABA-γ相关性）；related 新增 schizophrenia/nmda-receptor；dimensions 新增 disease；key_sources 新增 4 条
- `wiki/concepts/ei-balance.md`（rev2→rev3）：新增"精神分裂症中的 E/I 失衡"小节（PV GAD67下调→前额叶E/I偏移→多巴胺脱抑制→正性症状；与ASD E/I失衡的对比）；related 新增 schizophrenia/autism-spectrum-disorder/nmda-receptor；key_sources 新增 3 条

### 登记或裁决矛盾
- 无新矛盾（今日证据内部一致；Q-pv-schizophrenia-causal 转移为新的 Q-scz-pv-01 但仍 open）

### 新增悬空引用（待补页面）
- `nmda-receptor`（在 schizophrenia.md 的 related 和多处引用，尚无独立 wiki 页）
- `dopamine-system`（在 schizophrenia.md 中引用，尚无独立 wiki 页）

### 图谱变化
- 节点：294 → 295（+1：schizophrenia）
- 边：1683 → 1695（+12）

### 新增未解问题（3 条）
- Q-scz-pv-01（高）：PV 细胞 GAD67 下调时间窗——UHR 中 γ 振荡变化能否预测发病？
- Q-scz-pv-02（高）：PV 细胞功能缄默的分子可逆性——Lhx6 再激活/TrkB 激动剂能否恢复 GAD67？
- Q-scz-pv-03（中）：GluN2A vs GluN2B 亚基在 SCZ PV 细胞缺陷中的相对贡献

## 2026-09-16 (文章 #146：当遗传学汇聚于同一个回路)

### 新建 wiki 页面（2 个）
- `wiki/concepts/nrg1-erbb4.md` — NRG1-ErbB4 信号轴 | mainstream / medium | ErbB4 专门表达于 PV+ 中间神经元（Fazzari 2010）；控制 PV 细胞抑制性突触布线 + 谷氨酸突触成熟（Yang 2013）；通过 Src 抑制压制 NMDAR 功能（Pitcher 2011）；SCZ 遗传路径之一；GluN2D KO 导致 Nrg1/ErbB4 下调（汇聚证据 Gawande 2023）
- `wiki/concepts/disc1.md` — DISC1（精神分裂症中断基因 1）| emerging / medium | NUDEL/LIS1 微管调控 + GSK3β-Dlx2 MGE 发育；DBZ 结合蛋白维护 PV 篮状细胞形态（Koyama 2013）；DISC1 LI 小鼠选择性 PV GABA 减少（Delevich 2020）；GWAS 未确认 DISC1 为常见变异风险位点——重要争议

### 修订 wiki 页面（1 个）
- `wiki/diseases/schizophrenia.md`（rev1→rev2）：新增"遗传汇聚视角"节（DISC1/NRG1-ErbB4/GRIN2A 三路径汇聚；Trubetskoy 2022 GWAS 287 位点概述；Gawande 2023 分子汇聚点证据）；related 新增 nrg1-erbb4/disc1/cortical-interneuron-development；key_sources 新增 4 条；opens_questions 新增 Q-scz-gen-01/02/03

### 登记或裁决矛盾
- 无新矛盾登记（DISC1 的 GWAS 缺席情况在 disc1.md 中已作为内部争议详述，不构成与既有 wiki 主张的新矛盾；无需写入 contested_claims.json）

### 新增悬空引用（待补页面）
- 无新悬空引用（今日涉及概念的主要 wiki 页面均已建立）

### 图谱变化
- 节点：288 → 290（+2：nrg1-erbb4、disc1）
- 边：1637 → 1649（+12）

### 新增未解问题（3 条）
- Q-scz-gen-01（高）：DISC1、NRG1、GRIN2A 三路径是否有时间先后顺序？哪条是原发，哪条是继发？
- Q-scz-gen-02（高）：NMDAR 低激活（GluN2D/GluN2A）是否是 SCZ 遗传回路崩溃的上游触发因素，DISC1/NRG1 下调是继发结果？
- Q-scz-gen-03（中）：ErbB4 正向变构调制是否可作为 SCZ PV 细胞突触布线修复的基因治疗靶点？

---

## 2026-09-17（文章 #147）

### 新建页面（1 个）
- `wiki/concepts/theta-gamma-coupling.md`（rev1）— θ-γ 耦合机制专属页面，填补此前缺失的关键节点；整合了 Lisman-Jensen 2013 理论、Axmacher 2010 人类颅内证据、Daume 2024 PAC 细胞机制、Colgin 2009 CA1 路由机制、Sengupta 2025 细胞类型分工

### 修订页面（3 个）
- `wiki/concepts/theta-oscillations.md`（rev3→rev4）— related 新增 theta-gamma-coupling/working-memory/gamma-oscillations；dimensions 新增 cognition；key_sources 新增 PMID:23522038/20133762/38632400
- `wiki/concepts/gamma-oscillations.md`（rev6→rev7）— related 新增 theta-gamma-coupling；key_sources 新增 PAC 相关文献；修订历史追加
- `wiki/concepts/working-memory.md`（rev10→rev11）— related 新增 theta-gamma-coupling；key_sources 新增 PAC 直接证据；修订历史追加

### 登记矛盾（1 条）
- C-2026-09-17-01（open）— Besosa 2026 谱依赖性框架 vs 传统 θ-γ 专用机制解释：γ 功率协变于 θ 功率是否说明耦合只是涌现效应？

### 图谱变化
- 节点：299 → 300（+1：theta-gamma-coupling）
- 边：1723 → 1733（+10：theta-gamma-coupling 与 theta/gamma/working-memory/hippocampal-circuit/theta-phase-precession/schizophrenia/memory-consolidation 之间的有类型边）

### 新增未解问题（4 条）
- Q-tgc-01（高）：工作记忆容量约 4 项（Cowan）与频率比 4:1 的对应——不同研究报告 2:1 到 8:1 的变异来源？
- Q-tgc-02（中）：人类 θ 节律弱且不规则——人类嵌套编码的神经基础是否与大鼠不同？
- Q-tgc-03（高）：AD/SCZ 中 θ-γ 耦合损伤原发还是继发？恢复耦合能否改善记忆？
- Q-tgc-04（中）：相邻 γ 槽之间是否存在串扰？防止串扰的抑制性边界机制？

---

## 2026-09-22（文章 #152）

### 新建页面（1 个）
- `wiki/concepts/temporal-sampling-framework.md`（rev1）— 非对称时间采样（AST）框架专属页面；Poeppel 2003 起源；左半球γ快时序窗口（~25ms，音素精度）和右半球θ慢时序窗口（~200ms，韵律整合）；AAC层级产生（非A1）；连接振荡机制与语言左侧化

### 修订页面（3 个）
- `wiki/systems/language-network.md`（rev6→rev7）— 新增"振荡实现机制"节：背侧流与左半球γ对应，腹侧流与双侧θ-δ对应；related扩展（temporal-sampling-framework/cortical-speech-entrainment/delta-oscillations/neural-oscillations）；key_sources新增Giraud 2012/Ding 2016/Doelling 2014；opens_questions新增Q-lang-ast-01
- `wiki/concepts/cortical-speech-entrainment.md`（rev1→rev2）— 新增"与双流架构的映射"节（γ→背侧流，θ-δ→腹侧流，δ语法追踪→左IFG/pSTG）；增加Doelling 2014因果证据（R²=0.47）；related扩展（language-network/temporal-sampling-framework/delta-oscillations）；opens_questions新增Q-delta-01
- `wiki/concepts/delta-oscillations.md`（rev1→rev2）— 新增与双流架构的具体映射（左IFG对应背侧流，ATL>500ms时间窗对应腹侧流）；连接页扩展（temporal-sampling-framework/cortical-speech-entrainment/dorsal-language-stream/ventral-language-stream）；key_sources新增Doelling 2014（PMC:3839250）和Drijvers 2019（PMC:6850406）

### 登记矛盾（0 条）
- 无新矛盾；现有Q-delta-01（声学驱动vs语法驱动δ分离）仍open

### 图谱变化
- 节点：305 → 306（+1：temporal-sampling-framework）
- 边：1777 → 1788（+11：temporal-sampling-framework与language-network/language-lateralization/cortical-speech-entrainment/gamma/theta/delta的有类型边；delta-oscillations到dorsal/ventral-language-stream；cortical-speech-entrainment到language-network/temporal-sampling-framework）

### 新增未解问题（1 条）
- Q-lang-ast-01（高）：AST框架的半球不对称在高级语言区（IFG BA44/45、TPJ）是否与颞叶一致？前额叶γ/θ不对称直接证据缺乏

---

## 2026-09-24（文章 #154：空间忽视——大脑一半世界的消失）

### 新建 wiki 页面（1 页）

- `diseases/spatial-neglect.md` — 空间忽视（Hemispatial Neglect）：右半球腹侧额顶颞网络（TPJ/STG/IPL/VFC/SLF）损伤→VAN直接受损→DAN半球间失衡→注意系统整体向右偏斜的多维综合征（感知/运动/表征/病觉缺失）；棱镜适应疗法（Rossetti 1998）；网络归一化恢复（Ramsey 2016）；核心来源：PMID:21692662（开放全文）等6篇开放全文

### 修订 wiki 页面（2 页）

- `concepts/ventral-attention-network.md` rev1→rev2：将悬空引用 spatial-neglect-concept 替换为正式节点 spatial-neglect；新增 source_articles；修订历史追加
- `systems/tpj-temporoparietal-junction.md` rev2→rev3：新增 spatial-neglect 到 related；新增 Q-neglect-01（STG vs IPL 解剖争论）；dimensions 新增 disease；修订历史追加

### 图谱变化

- 新增节点：3（spatial-neglect, interhemispheric-competition [悬空], prism-adaptation [悬空]）
- 新增边：10（spatial-neglect↔VAN mechanism-of/related，↔DAN related，↔TPJ related，↔interhemispheric-competition，↔prism-adaptation，interhemispheric-competition→DAN/VAN）
- 节点总数：307 → 310
- 边总数：1795 → 1805

### 登记矛盾

- 无新矛盾（STG vs IPL 争论体现为知识不确定性，已在 wiki 中如实呈现两种观点；不是主张冲突）

### 新增悬空引用待补

- `interhemispheric-competition`：被 spatial-neglect 和 VAN 引用，待创建 `wiki/concepts/interhemispheric-competition.md`
- `prism-adaptation`：被 spatial-neglect 引用，待创建 `wiki/methods/prism-adaptation.md`
- `anosognosia`：被 spatial-neglect 引用，待创建（可独立页面或并入 spatial-neglect）

### 新增未解问题（3 条）

- Q-neglect-01（高）：STG vs IPL——忽视核心病灶的解剖争论，影响 tDCS/TMS 治疗靶点精确性
- Q-neglect-02（中）：棱镜适应的"认知扩散"神经底物——感觉运动可塑性如何通过小脑-顶叶通路进入高级空间认知？
- Q-neglect-03（中）：病觉缺失（anosognosia）的神经基础——前额叶-岛叶自我监测回路失效的具体机制？

---

## 2026-09-25（文章 #155：半球间竞争——两个大脑如何通过胼胝体争夺注意控制权）

### 新建 wiki 页面（1 页）

- `concepts/interhemispheric-competition.md` — 半球间竞争机制，Rev1：Kinsbourne 对立处理器框架；TMS 因果证明（Szczepanski & Kastner 2013，PMID:23516306，双侧 TMS 无净效果）；右 PPC 单向跨胼胝体抑制优势（Koch 2011，PMID:21677180）；后部胼胝体 FA 与竞争效率及忽视严重程度（Bozzali 2012，r=0.91）；纯竞争模型的挑战（Eshel 2010，PMID:20678510）；临床治疗逻辑（抑制对侧→重平衡）；status: established, confidence: high

### 修订 wiki 页面（3 页）

- `diseases/spatial-neglect.md` rev1→rev2：补充右 PPC 单向跨胼胝体抑制证据（Koch 2011）；更新后部胼胝体 FA 与忽视严重度数据（Bozzali 2012，r=0.91）；将 interhemispheric-competition 从悬空引用更新为正式节点；新增 prerequisites: interhemispheric-competition；key_sources 新增 PMID:23516306, PMID:23110177, PMID:21677180
- `concepts/ventral-attention-network.md` rev2→rev3：补充跨胼胝体单向抑制到右侧化机制节；新增 [[interhemispheric-competition]] 连接；key_sources 新增 PMID:23516306, PMID:21677180
- `concepts/dorsal-attention-network.md` rev4→rev5：related 新增 interhemispheric-competition, spatial-neglect；key_sources 新增 PMID:23516306, PMID:20053897；修订历史追加

### 图谱变化

- interhemispheric-competition 节点从"待创建"升级为正式节点（status: established, confidence: high）
- 新增边：8（interhemispheric-competition↔TPJ mechanism-of；↔alpha-oscillations related；↔SLF related；corpus-callosum→interhemispheric-competition mechanism-of；VAN/DAN→interhemispheric-competition related）
- 节点总数：302 → 303（+1：interhemispheric-competition 正式化；prism-adaptation 保持待创建）
- 边总数：1752 → 1760

### 登记矛盾（0 条）

- 纯竞争模型 vs 兴奋性跨半球机制（Eshel 2010）：体现为知识争议，已在 wiki 中如实呈现（竞争模型通常成立，但不完全是零和；任务依赖）；不降低 interhemispheric-competition 整体置信度，因为竞争抑制证据来自多个独立来源

### 新增悬空引用待补

- `corpus-callosum`：被 interhemispheric-competition 和 spatial-neglect 引用，待创建 `wiki/concepts/corpus-callosum.md`（胼胝体结构、区段功能、发育时程、split-brain）

### 新增未解问题（3 条）

- Q-ihc-01（高）：胼胝体跨半球传递净效果（抑制 vs 兴奋）如何随任务/脑区/年龄变化？是否有生物标志物？
- Q-ihc-02（中）：右半球单向抑制优势的发育起源——天生固定还是可重塑？
- Q-ihc-03（中）：忽视患者左侧 PPC 过激活：被动去抑制 vs 主动代偿——两种解释有不同的治疗含义

---

## 2026-06-13 更新（第 178 篇：旋转的引擎——运动皮层群体动力学）

### 新建 wiki 页面

**methods/**
- `jpca.md` — jPCA（旋转主成分分析）| mainstream / high | 搜寻神经群体旋转结构的降维工具；反对称矩阵特征分解；Churchland et al. 2012 核心分析方法；置换检验验证

**concepts/**
- `neural-manifold.md` — 神经流形 | mainstream / high | 神经群体活动分布的低维曲面（6–20维）；流形约束学习（in-manifold快速/out-of-manifold极难）；旋转在流形子空间展开

### 修订 wiki 页面

- `concepts/rotational-dynamics-motor.md` rev1→rev2 — 加深jPCA方法细节（反对称矩阵推导、置换检验）；加多物种证据行（水蛭/踏步/伸取）；加EMG旋转分解结论；加RNN验证（Sussillo 2015 PMID:26075643）；加神经流形约束学习（Vyas 2020）；related新增jpca, neural-manifold；key_sources增PMID:26075643, PMID:24487233
- `concepts/output-null-space.md` rev1→rev2 — 加PMd零空间证据统计细节（4组数据集p<0.03）；加感觉反馈decoder-null预测（Vyas 2020）；加钟摆比喻说明零空间与旋转协作机制；related新增neural-manifold, jpca；opens_questions增Q-rd-03；key_sources增PMID:22722855, PMID:32640928
- `systems/motor-cortex.md` rev5→rev6 — 在旋转动力学节补充RNN验证（Sussillo 2015）和jPCA工具引用；related新增neural-manifold, jpca；key_sources补充PMID:26075643, PMID:17178410；source_articles补充#178

### 图谱变化

- 新建节点：jpca（methods）、neural-manifold（concepts）
- 新增边：10条（jpca↔rotational-dynamics-motor, neural-manifold, motor-cortex, output-null-space；neural-manifold↔rotational-dynamics-motor, output-null-space, motor-cortex, attractor-network）
- 节点总数：355 → 357（+2）
- 边总数：2046 → 2056（+10）

### 登记矛盾（0 条）

- 无新矛盾；旋转动力学与群体向量编码为互补而非竞争关系，已在wiki中如实呈现

### 新增未解问题（4 条）

- Q-rd-01（高）：运动学习期间，神经流形如何通过突触可塑性从"无组织"演变为"有组织"？学习的分子机制是什么？
- Q-rd-02（高）：旋转动力学是否存在于人类大脑皮层？有限的人类BCI记录如何验证？
- Q-rd-03（中）：SMA/PMd如何精确触发活动从输出零空间流入主动空间？"执行信号"的神经机制是什么？
- Q-rd-04（中）：旋转动力学在神经系统疾病中如何破坏？能否作为BCI解码的生物标志物？

---

## 2026-06-13 更新（第 179 篇）

### 新建 wiki 页面（3 页）

**circuits/**
- `stretch-reflex.md` — 牵张反射弧 | established / high | 唯一单突触反射（Ia→α-MN）；三重增益制动（互反抑制/复现抑制/突触前抑制）；γ-MN 增益旋钮；状态依赖性极性反转（Hultborn 2001）；H反射可塑性（Wolpaw 系列）；填补悬空引用 `stretch-reflex`

**neurons/**
- `ia-inhibitory-interneuron.md` — Ia 抑制性中间神经元 | established / high | 互反抑制的专用中介；甘氨酸能；接收 Ia 传入+Renshaw 抑制+下行调控
- `renshaw-cell.md` — Renshaw 细胞 | established / high | α-MN 轴突侧支驱动的甘氨酸能 INs；复现抑制；通过抑制 Ia-INs 允许共收缩；汇聚-发散结构（Moore 2015）

### 修订 wiki 页面（3 页）

- `neurons/alpha-motor-neuron.md` rev4→rev5 — 新增 stretch-reflex、ia-inhibitory-interneuron、renshaw-cell 到 related；α-MN 作为牵张反射效应器的连接明确
- `neurons/gamma-motor-neuron.md` rev1→rev2 — 新增 stretch-reflex 到 related；γ-MN 作为牵张反射增益旋钮的连接明确
- `neurons/muscle-spindle.md` rev3→rev4 — 新增 stretch-reflex 到 related；Ia 传入作为牵张反射输入端的连接完整化

### 图谱变化

- 新建节点：stretch-reflex（circuits）、ia-inhibitory-interneuron（neurons）、renshaw-cell（neurons）
- 新增边：14条（stretch-reflex↔muscle-spindle/alpha-motor-neuron/gamma-motor-neuron/ia-inhibitory-interneuron/renshaw-cell/spinal-cord-cpg/corticospinal-tract/somatosensory-cortex-3a/motor-cortex；ia-inhibitory-interneuron↔alpha-motor-neuron；renshaw-cell↔alpha-motor-neuron/ia-inhibitory-interneuron）
- 节点总数：357 → 360（+3）
- 边总数：2056 → 2070（+14）
- **悬空引用填补**：`stretch-reflex`（被多个运动系统节点引用但无独立页，今日创建）
- 剩余悬空：2条（aging, cognition）

### 登记矛盾（0 条）

无新矛盾；牵张反射机制高度确立（教科书级）

### 新增未解问题（3 条）

- Q-stretch-01（高）：人类 Ia-INs 的功能特性与猫是否一致？（无直接人类细胞内记录）
- Q-stretch-02（中）：长潜伏期牵张反射 M2 成分是否真正通过 M1？
- Q-stretch-03（中）：H 反射可塑性的脊髓 vs 皮层贡献比例

---

## 2026-06-13（文章 #189：KCC2 与 GABA 极性切换）

### 新建页面（3 个）

- `neurons/kcc2.md` — KCC2（K⁺-Cl⁻ 共转运体 2）分子实体；WNK-SPAK 磷酸化调控；发育性激活机制；疾病谱（TLE、慢性疼痛、Rett）；来源 Rivera 1999/Kaila 2014/Watanabe 2019
- `concepts/gaba-polarity-switch.md` — GABA 极性切换（E→I 发育转变）；NKCC1/KCC2 比例机制；区域时间轴；催产素出生保护窗；来源 Tyzio 2014/Kaila 2014
- `neurons/nkcc1.md`（图谱节点，暂无独立 wiki 页内容，仅图谱记录，待后续补全）

### 修订页面（1 个）

- `concepts/gaba.md` rev1→rev2 — 大幅扩展 GABA 极性切换机制详情（NKCC1/KCC2 比例、WNK-SPAK T906/T1007 磷酸化轴定量数据、区域时间线、GDPs）；新增 related 链接（kcc2/gaba-polarity-switch/nkcc1/temporal-lobe-epilepsy）；新增 3 条证据（PMID:9930699, 31615901）

### 图谱变化

- 新建节点：kcc2（neurons）、gaba-polarity-switch（concepts）、nkcc1（neurons，仅图谱）
- 新增边：14 条（kcc2↔gaba/gaba-polarity-switch/temporal-lobe-epilepsy/ei-balance/critical-period；gaba-polarity-switch↔kcc2/nkcc1/gaba/critical-period/glun2-developmental-switch/temporal-lobe-epilepsy/adult-neurogenesis；nkcc1↔gaba-polarity-switch/gaba）
- 节点总数：370 → 373（+3）
- 边总数：2145 → 2159（+14）
- **悬空引用填补**：nkcc1（被 gaba 和 gaba-polarity-switch 引用但无节点）；kcc2（新增为核心节点）

### 登记矛盾（0 条）

无新矛盾。布美他尼临床数据（人类 vs 动物差异）在文章中已作为"争议"明确呈现，暂不升级为正式 contested_claims 条目（属于临床转化不确定性，而非核心机制冲突）。

### 新增未解问题（3 条）

- Q-kcc2-01（高）：人类不同脑区 GABA 极性切换的精确时间线？
- Q-kcc2-02（高）：WNK-SPAK/OSR1 轴在发育中程序性下调的上游调控机制？
- Q-kcc2-03（中）：系统性 KCC2 增强治疗的安全性边界？

---

## 2026-06-14 · 文章 #190 · 伤害感受与疼痛通路

**文章**：伤害感受≠疼痛体验：大脑如何将分子警报转化为主观苦难

### 新建页面（5 页）

| 页面 | 路径 | 域 | 状态 |
|---|---|---|---|
| 伤害感受（Nociception） | `concepts/nociception.md` | concepts | established/high |
| 闸门控制理论（Gate Control Theory） | `concepts/gate-control-theory.md` | concepts | established/high |
| 中枢敏化（Central Sensitization） | `concepts/central-sensitization.md` | concepts | established/high |
| 下行疼痛调制（Descending Pain Modulation） | `concepts/descending-pain-modulation.md` | concepts | established/high |
| 疼痛矩阵（Pain Matrix） | `systems/pain-matrix.md` | systems | established/moderate |

### 修订页面（4 页）

| 页面 | 修订 | 修改内容 |
|---|---|---|
| `neurons/kcc2.md` | rev1→rev2 | 新增慢性疼痛中KCC2下调机制（小胶质细胞-BDNF-TrkB-KCC2轴、CLP290镇痛靶点）；related新增3个；新增Q-kcc2-04 |
| `systems/anterior-insula.md` | rev1→rev2 | 新增前岛叶在疼痛矩阵角色（痛觉不愉快感、Pain Asymbolia、慢性痛灰质减少、Craig S3理论）；related新增3个；新增Q-aic-02 |
| `systems/anterior-cingulate-cortex.md` | rev2→rev3 | 新增ACC疼痛处理角色（Rainville 1997催眠实验、安慰剂镇痛rACC→PAG通路、pgACC vs aMCC分工）；related新增3个；新增Q-acc-pain-cog-overlap |
| `neurons/microglia.md` | rev2→rev3 | 新增脊髓小胶质细胞与慢性疼痛（P2X4/P2X7激活、BDNF→TrkB→KCC2、Coull 2005里程碑证据）；related新增3个 |

### 知识图谱变更

- 新节点（5）：nociception, gate-control-theory, central-sensitization, descending-pain-modulation, pain-matrix
- 新边（14）：疼痛通路核心关系链
- 图谱统计：378 节点，2173 边（之前：373 节点，2159 边）

### 新增未解问题（7 条）

- Q-pain-01（高）：C纤维功能亚型的脊髓投射目标差异与疼痛类型对应关系？
- Q-pain-02（高）：脊髓闸门在自然行为中的实时动态（体内双光子钙成像可行性）？
- Q-pain-03（中）：疼痛矩阵意识必要成分——Pain Asymbolia 病例数量是否足够推断因果？
- Q-pain-04（高）：中枢敏化临界点及KCC2恢复策略的安全性边界？
- Q-kcc2-04（中）：脊髓背角KCC2下调的节段特异性分布？
- Q-aic-02（中）：前岛叶对痛觉不愉快感的因果必要性？
- Q-acc-pain-cog-overlap（中）：ACC认知控制功能与痛觉情感功能是否共享神经元群体？


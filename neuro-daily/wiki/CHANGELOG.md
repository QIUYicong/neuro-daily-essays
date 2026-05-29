# Wiki 变更日志

> 每日固结步骤产生的 wiki 变更记录。新条目置于顶部。

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

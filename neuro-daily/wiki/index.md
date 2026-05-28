# 神经科学 Wiki 知识库 · 总地图

> 这是语义层的人读地图。每个条目链接到一个**活的**主题页（会随时间被修订加深）。
> 机读版见 `_graph.json`；每日变更见 `CHANGELOG.md`；设计原理见仓库根 `KNOWLEDGE-BASE-DESIGN.md`。
>
> 成熟度图例：🟢 established · 🔵 mainstream · 🟡 emerging · ⚪ speculative · 🔴 contested
>
> 最后更新：2026-05-29 · 主题页总数：23

---

## neurons（神经元）

- 🟢 [动作电位](neurons/action-potential.md) — 神经系统的基本信息单位，全或无脉冲（修订3次）
- 🟢 [轴突始段 (AIS)](neurons/axon-initial-segment.md) — 动作电位的诞生地与神经元决策中枢
- 🟢 [电压门控钠通道](neurons/voltage-gated-sodium-channel.md) — 动作电位上升相的分子引擎
- 🟢 [突触传递](neurons/synaptic-transmission.md) — 神经元间化学信号转化的核心机制，含突触后受体（修订2次）
- 🟢 [突触结合蛋白 Synaptotagmin](neurons/synaptotagmin.md) — 突触囊泡上的钙传感器，触发融合的分子开关
- 🟢 [活动区（Active Zone）](neurons/active-zone.md) — 突触前终末的纳米级分子发射台
- 🟢 [CaMKII（钙/钙调素依赖性蛋白激酶 II）](neurons/camkii.md) — LTP 诱导和维持的核心激酶，"分子记忆开关"
- 🟢 [树突计算](neurons/dendritic-computation.md) — NMDA 棘波与 Ca²⁺ 棘波使单根树突成为独立计算单元，单神经元等价两层神经网络（修订2次）
- 🟢 [锥体神经元](neurons/pyramidal-neuron.md) — 皮层主体兴奋性神经元，双树突系统是树突计算和前馈/反馈整合的物理基础
- 🟢 [场所细胞](neurons/place-cell.md) — 海马 CA1/CA3 的空间位置编码器，通过 BTSP 单次写入场所场，构成大脑认知地图 **[NEW]**
- 🟢 [海马回路](neurons/hippocampal-circuit.md) — DG（模式分离）→ CA3（模式补全）→ CA1（整合输出）的三突触回路与并行穿孔通路 **[NEW]**
- 🟢 [网格细胞](neurons/grid-cell.md) — 内侧内嗅皮层的六角网格空间编码器，为场所细胞提供坐标框架 **[NEW]**

## circuits（回路）

- 🔵 [吊灯细胞](circuits/chandelier-cell.md) — 特异靶向 AIS 的抑制性中间神经元

## concepts（概念/框架）

- 🟢 [Hodgkin-Huxley 模型](concepts/hodgkin-huxley-model.md) — 动作电位的定量数学框架
- 🟢 [SNARE复合体](concepts/SNARE-complex.md) — 突触囊泡融合的核心分子机器（四螺旋束拉链）
- 🟢 [NMDA 受体](concepts/nmda-receptor.md) — 突触巧合检测器 + 树突 NMDA 棘波的核心机器（修订2次）
- 🟢 [长时程增强（LTP）](concepts/ltp.md) — 突触可塑性与学习记忆的分子基础（修订2次）
- 🟢 [Hebbian 学习](concepts/hebbian-learning.md) — "共同激发的神经元连接在一起"，NMDA 受体实现其分子逻辑
- 🟢 [AMPA 受体](concepts/ampa-receptor.md) — 快速突触传递的执行者，LTP 权重变化的物理载体
- 🟢 [行为时间尺度突触可塑性（BTSP）](concepts/btsp.md) — 秒级时间窗口的突触增强规则，单次写入场所场，与 LTP 并列的独立学习法则
- 🟢 [θ振荡](concepts/theta-oscillations.md) — 海马4–12 Hz探索节律；提供相位编码时间框架；θ序列压缩路径；θ/γ嵌套承载5-9项目序列 **[NEW]**
- 🟢 [尖波涟漪（SWR）](concepts/sharp-wave-ripples.md) — CA3→CA1高频群体事件；20倍速序列重播；记忆固化的离线物理载体 **[NEW]**
- 🟢 [相位前进](concepts/phase-precession.md) — 场所细胞在θ周期中放电相位随位置移动；速率+相位双重编码；O'Keefe & Recce 1993经典发现 **[NEW]**

## systems（系统） — *待建*

## methods（方法） — *待建*

## theories（理论） — *待建*

## diseases（疾病） — *待建*

---

## 待补的悬空引用（缺口，下一步可写）

- ~~`place-cell`（场所细胞）~~ ✅ **2026-05-28 已建立**
- ~~`theta-oscillations`（θ振荡）~~ ✅ **2026-05-29 已建立**
- `engram-cells`（印迹细胞）— 被 [[场所细胞]]、[[ltp]]、[[hebbian-learning]]、[[树突计算]] 引用，**高优先级**：场所细胞是空间情景记忆的印迹细胞候选
- `memory-consolidation`（记忆巩固）— 被多个页面引用；SWR 已有详细覆盖（sharp-wave-ripples），但**系统巩固专页**尚缺（皮层侧机制、睡眠阶段分工、标准巩固 vs 多重痕迹理论），**高优先级**
- `calcium-channel`（电压门控钙通道）— 被多个页面引用（L-type 驱动树突 Ca²⁺ 棘波+BTSP，P/Q/N-type 驱动突触前 Ca²⁺），高优先级
- `path-integration`（路径整合）— 被 [[网格细胞]] 引用，网格细胞无地标时维持空间表征的内源机制
- `memory-consolidation`（记忆巩固）— 被 [[海马回路]]、[[场所细胞]] 引用，SWR重放→皮层巩固
- `synaptic-clustering`（突触聚类假说）— 被 [[树突计算]] 引用，NMDA 棘波的前提条件，有争议
- `apical-tuft`（顶端簇）— 被 [[树突计算]]、[[锥体神经元]] 引用，Ca²⁺ 棘波的主要发生地
- `three-factor-learning-rule`（三因素学习规则）— 被 [[hebbian-learning]] 引用，Hebb × 多巴胺
- `tarp-auxiliary-subunit`（TARP 辅助亚基）— 被 [[ampa-receptor]] 引用，AMPA 受体突触锚定关键
- `readily-releasable-pool`（可释放池/RRP）— 被突触传递页引用
- `complexin`（复合素）— 被 SNARE-complex 等引用

---

## 当前知识前沿（高连接、待深挖）

- **θ振荡**（今日新建，整合节点）：连接 place-cell、grid-cell、hippocampal-circuit、ltp、btsp、sharp-wave-ripples、phase-precession 等 7+ 节点；是"全脑网络层"的首个关键节点。**高优先级深挖方向**。
- **海马回路**（修订，连接枢纽）：θ/SWR双模更新后，连接更密——现在是从"细胞层"到"全脑网络层"的核心通道。
- **场所细胞**（修订）：加入相位前进后，连接维度更广（theta-oscillations、phase-precession、sharp-wave-ripples）。
- **NMDA 受体**（最高连接）：连接突触 LTP、树突计算、BTSP（间接）；仍是最密集枢纽节点。
- **印迹细胞（engram-cells）**（最高优先级悬空引用）：被 4 个页面引用；下一步首选主题。

---

## 知识路线进度

| 课程主题 | 状态 |
|---------|------|
| 1. 神经元如何工作 | 🔵 进行中（已覆盖：AIS, 动作电位, 突触传递, NMDA/AMPA 受体, CaMKII, 树突计算, 锥体神经元；待覆盖：神经调质, 中间神经元多样性, LTD） |
| 3. 大脑如何编码世界 | 🔵 进行中（已覆盖：**场所细胞**, **网格细胞**, 视觉皮层朝向选择性, **θ振荡/相位编码**；待覆盖：听觉/体感系统, 头向细胞, 时间表征）|
| 4. 学习和记忆 | 🔵 进行中（已覆盖：LTP, Hebb 规则, BTSP, **海马回路**, 场所场形成, **SWR重播**；待覆盖：LTD, 记忆巩固（系统），印迹细胞, 记忆提取）|
| 2, 5–12 | ⚪ 待开始 |

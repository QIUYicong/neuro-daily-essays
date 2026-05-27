# 神经科学 Wiki 知识库 · 总地图

> 这是语义层的人读地图。每个条目链接到一个**活的**主题页（会随时间被修订加深）。
> 机读版见 `_graph.json`；每日变更见 `CHANGELOG.md`；设计原理见仓库根 `KNOWLEDGE-BASE-DESIGN.md`。
>
> 成熟度图例：🟢 established · 🔵 mainstream · 🟡 emerging · ⚪ speculative · 🔴 contested
>
> 最后更新：2026-05-27 · 主题页总数：16

---

## neurons（神经元）

- 🟢 [动作电位](neurons/action-potential.md) — 神经系统的基本信息单位，全或无脉冲（修订3次）
- 🟢 [轴突始段 (AIS)](neurons/axon-initial-segment.md) — 动作电位的诞生地与神经元决策中枢
- 🟢 [电压门控钠通道](neurons/voltage-gated-sodium-channel.md) — 动作电位上升相的分子引擎
- 🟢 [突触传递](neurons/synaptic-transmission.md) — 神经元间化学信号转化的核心机制，含突触后受体（修订2次）
- 🟢 [突触结合蛋白 Synaptotagmin](neurons/synaptotagmin.md) — 突触囊泡上的钙传感器，触发融合的分子开关
- 🟢 [活动区（Active Zone）](neurons/active-zone.md) — 突触前终末的纳米级分子发射台
- 🟢 [CaMKII（钙/钙调素依赖性蛋白激酶 II）](neurons/camkii.md) — LTP 诱导和维持的核心激酶，"分子记忆开关"
- 🟢 [树突计算](neurons/dendritic-computation.md) — NMDA 棘波与 Ca²⁺ 棘波使单根树突成为独立计算单元，单神经元等价两层神经网络 **[NEW]**
- 🟢 [锥体神经元](neurons/pyramidal-neuron.md) — 皮层主体兴奋性神经元，双树突系统是树突计算和前馈/反馈整合的物理基础 **[NEW]**

## circuits（回路）

- 🔵 [吊灯细胞](circuits/chandelier-cell.md) — 特异靶向 AIS 的抑制性中间神经元

## concepts（概念/框架）

- 🟢 [Hodgkin-Huxley 模型](concepts/hodgkin-huxley-model.md) — 动作电位的定量数学框架
- 🟢 [SNARE复合体](concepts/SNARE-complex.md) — 突触囊泡融合的核心分子机器（四螺旋束拉链）
- 🟢 [NMDA 受体](concepts/nmda-receptor.md) — 突触巧合检测器 + 树突 NMDA 棘波的核心机器（修订2次）
- 🟢 [长时程增强（LTP）](concepts/ltp.md) — 突触可塑性与学习记忆的分子基础
- 🟢 [Hebbian 学习](concepts/hebbian-learning.md) — "共同激发的神经元连接在一起"，NMDA 受体实现其分子逻辑
- 🟢 [AMPA 受体](concepts/ampa-receptor.md) — 快速突触传递的执行者，LTP 权重变化的物理载体

## systems（系统） — *待建*

## methods（方法） — *待建*

## theories（理论） — *待建*

## diseases（疾病） — *待建*

---

## 待补的悬空引用（缺口，下一步可写）

- `place-cell`（场所细胞）— 被 [[树突计算]] 引用，海马 CA1/CA3，树突平台电位→场所场的核心体内证据，**高优先级**
- `calcium-channel`（电压门控钙通道）— 被多个页面引用（L-type 驱动 Ca²⁺ 棘波，P/Q/N-type 驱动突触前终末 Ca²⁺ 内流），高优先级
- `engram-cells`（印迹细胞）— 被 [[ltp]]、[[hebbian-learning]]、[[树突计算]] 引用，记忆存储的细胞群体
- `theta-oscillations`（θ振荡）— 被 [[ltp]] 引用，LTP 的体内诱导节律
- `synaptic-clustering`（突触聚类假说）— 被 [[树突计算]] 引用，NMDA 棘波的前提条件，有争议
- `apical-tuft`（顶端簇）— 被 [[树突计算]]、[[锥体神经元]] 引用，Ca²⁺ 棘波的主要发生地
- `three-factor-learning-rule`（三因素学习规则）— 被 [[hebbian-learning]] 引用，Hebb × 多巴胺
- `tarp-auxiliary-subunit`（TARP 辅助亚基）— 被 [[ampa-receptor]] 引用，AMPA 受体突触锚定关键
- `readily-releasable-pool`（可释放池/RRP）— 被突触传递页引用

---

## 当前知识前沿（高连接、待深挖）

- **树突计算**（今日新建，高连接）：连接 NMDA 受体、LTP、Hebbian 学习、动作电位、突触传递、锥体神经元六个已有节点，是从"分子机制"到"细胞计算"的关键桥梁；新增 3 个悬空引用待补。
- **NMDA 受体**（修订后，最高连接）：今日新增树突棘波维度，现在连接突触LTP + 树突计算两个层级，成为全图最重要的枢纽节点之一。
- **LTP**：连接 NMDA、AMPA、CaMKII、Hebb 规则、树突计算；3 个重要未解问题。
- **突触传递**：连接度 10+ 条边，最密集节点。

---

## 知识路线进度

| 课程主题 | 状态 |
|---------|------|
| 1. 神经元如何工作 | 🔵 进行中（已覆盖：AIS, 动作电位, 突触传递, NMDA/AMPA 受体, CaMKII, **树突计算**, 锥体神经元；待覆盖：神经调质, 中间神经元多样性, LTD） |
| 3. 大脑如何编码世界 | 🟡 初涉（今日：视觉皮层朝向选择性 + 海马场所场形成）|
| 4. 学习和记忆 | 🟡 进行中（已覆盖：LTP 分子机制, Hebb 规则, 树突平台电位→场所场；待覆盖：LTD, 海马回路详解, 记忆巩固, 睡眠） |
| 2, 5–12 | ⚪ 待开始 |

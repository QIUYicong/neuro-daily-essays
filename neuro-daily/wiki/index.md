# 神经科学 Wiki 知识库 · 总地图

> 这是语义层的人读地图。每个条目链接到一个**活的**主题页（会随时间被修订加深）。
> 机读版见 `_graph.json`；每日变更见 `CHANGELOG.md`；设计原理见仓库根 `KNOWLEDGE-BASE-DESIGN.md`。
>
> 成熟度图例：🟢 established · 🔵 mainstream · 🟡 emerging · ⚪ speculative · 🔴 contested
>
> 最后更新：2026-05-26 · 主题页总数：14

---

## neurons（神经元）

- 🟢 [动作电位](neurons/action-potential.md) — 神经系统的基本信息单位，全或无脉冲（修订3次）
- 🟢 [轴突始段 (AIS)](neurons/axon-initial-segment.md) — 动作电位的诞生地与神经元决策中枢
- 🟢 [电压门控钠通道](neurons/voltage-gated-sodium-channel.md) — 动作电位上升相的分子引擎
- 🟢 [突触传递](neurons/synaptic-transmission.md) — 神经元间化学信号转化的核心机制，含突触后受体（修订2次）
- 🟢 [突触结合蛋白 Synaptotagmin](neurons/synaptotagmin.md) — 突触囊泡上的钙传感器，触发融合的分子开关
- 🟢 [活动区（Active Zone）](neurons/active-zone.md) — 突触前终末的纳米级分子发射台
- 🟢 [CaMKII（钙/钙调素依赖性蛋白激酶 II）](neurons/camkii.md) — LTP 诱导和维持的核心激酶，"分子记忆开关" **[NEW]**

## circuits（回路）

- 🔵 [吊灯细胞](circuits/chandelier-cell.md) — 特异靶向 AIS 的抑制性中间神经元

## concepts（概念/框架）

- 🟢 [Hodgkin-Huxley 模型](concepts/hodgkin-huxley-model.md) — 动作电位的定量数学框架
- 🟢 [SNARE复合体](concepts/SNARE-complex.md) — 突触囊泡融合的核心分子机器（四螺旋束拉链）
- 🟢 [NMDA 受体](concepts/nmda-receptor.md) — 突触巧合检测器，LTP 诱导的分子门卫 **[NEW]**
- 🟢 [长时程增强（LTP）](concepts/ltp.md) — 突触可塑性与学习记忆的分子基础 **[NEW]**
- 🟢 [Hebbian 学习](concepts/hebbian-learning.md) — "共同激发的神经元连接在一起"，NMDA 受体实现其分子逻辑 **[NEW]**
- 🟢 [AMPA 受体](concepts/ampa-receptor.md) — 快速突触传递的执行者，LTP 权重变化的物理载体 **[NEW]**

## systems（系统） — *待建*

## methods（方法） — *待建*

## theories（理论） — *待建*

## diseases（疾病） — *待建*

---

## 待补的悬空引用（缺口，下一步可写）

- `calcium-channel`（电压门控钙通道）— 被活动区、Synaptotagmin、突触传递页引用，突触前终末 Ca²⁺ 内流的执行者，高优先级
- `dendritic-computation`（树突计算）— 已被 [[Hodgkin-Huxley 模型]] 引用，尚无页面
- `theta-oscillations`（θ振荡）— 被 [[ltp]] 引用，LTP 的体内诱导节律
- `engram-cells`（印迹细胞）— 被 [[ltp]]、[[hebbian-learning]] 引用，记忆存储的细胞群体
- `three-factor-learning-rule`（三因素学习规则）— 被 [[hebbian-learning]] 引用，Hebb × 多巴胺
- `tarp-auxiliary-subunit`（TARP 辅助亚基）— 被 [[ampa-receptor]] 引用，AMPA 受体突触锚定关键
- `readily-releasable-pool`（可释放池/RRP）— 被突触传递页引用

---

## 当前知识前沿（高连接、待深挖）

- **NMDA 受体**（新建，高连接）：连接动作电位、突触传递、LTP、Hebbian 学习四个主要节点，是从"传递"到"学习"的关键枢纽。
- **LTP**（新建，高连接）：连接 NMDA、AMPA、CaMKII、Hebb 规则、突触传递，是学习/记忆主题的核心入口，有 3 个重要未解问题。
- **突触传递**：修订后连接度达 10+ 条边，横跨前突触（SNARE/Syt/活动区）和后突触（AMPA/NMDA/LTP），是全图最密集的节点。

---

## 知识路线进度

| 课程主题 | 状态 |
|---------|------|
| 1. 神经元如何工作 | 🔵 进行中（已覆盖：AIS, 动作电位, 突触传递, NMDA/AMPA 受体, CaMKII；待覆盖：树突计算, 神经调质, 中间神经元多样性） |
| 4. 学习和记忆 | 🟡 刚刚开始（已覆盖：LTP 分子机制, Hebb 规则；待覆盖：LTD 细节, 海马回路, 记忆巩固, 睡眠） |
| 2–3, 5–12 | ⚪ 待开始 |

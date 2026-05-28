# 2026-05-28 研究笔记

**主题**：场所细胞 · BTSP · 海马回路 · 网格细胞  
**核心问题**：场所场如何通过单次体验写入？  

---

## 来源 1：Bittner et al. 2017 (PMID:28883072, PMC7289271)

**标题**：Behavioral time scale synaptic plasticity underlies CA1 place fields  
**期刊**：Science 357(6355):1033-1036  
**全文**：开放（PMC7289271）

### 要解决什么问题
经典 Hebbian STDP 时间窗口约 10–100 ms，但行为发生在秒量级。场所场能在单次穿越中形成意味着需要一种时间窗口更宽的可塑性机制。

### 方法
- 清醒行为小鼠（线性跑道）的 CA1 胞内记录（in vivo whole-cell）
- 脑片实验（whole-cell patch clamp）配对弱突触激活与钙平台电位

### 关键发现
1. **BTSP 的时间窗口**：向后约 3–4 秒（τ_rise=1.31±0.22 s），向前约 2–3 秒（τ_decay=0.69±0.11 s）
2. **单次写入**：5 次配对即可产生大幅增强（3×基线 EPSP）
3. **不对称性**：强化更倾向于"预告输入"（平台电位之前的输入），这与预测编码一致
4. **NMDA 受体依赖性**：D-APV 减弱 84% 增强
5. **L 型钙通道依赖性**：尼莫地平减弱 73%；体内减弱场所场斜坡从 6.2→1.3 mV
6. 自然发生的平台电位诱导场所场（n=7）；人工诱导（n=20）；平均 1.4 次自然平台即建立场所场

### 改变了什么理解
证明大脑有 **秒级** 时间窗口的突触增强机制，完全不依赖毫秒级同步——是对 Hebb 规则和 STDP 的根本性补充，而不是修正。

### 证据强度
高。胞内记录 + 药理学 + 体内体外交叉验证。样本量不大（n=7自然，n=20诱导），但方法是金标准。

### 局限
仅在啮齿类；仅在 CA1；Sumegi 2025 提示多条路径并存。

---

## 来源 2：Bittner et al. 2015 (PMID:26167906, PMC4888374)

**标题**：Conjunctive input processing drives feature selectivity in hippocampal CA1 neurons  
**期刊**：Nat Neurosci 18(8):1133-42  
**全文**：开放（PMC4888374）；已用于 2026-05-27 文章（树突计算）

### 核心结论（今日新角度）
- 平台电位由 EC3 和 CA3 的联合输入驱动（光遗传阻断 EC3 → 平台概率降低 ~50%）
- 自然发生的平台电位后，场所场立刻稳定并维持 19.8±4.2 圈（约 9.6 min）
- 关键证明：仅高频动作电位簇（无平台电位）→ 仅产生 0.8±0.1 Hz 持续放电（无场所场）
- 平台电位 → EPSP 幅度增加（var 从 2.4→8.0 mV²），非频率增加

### 与今日的联系
为 BTSP 的"为什么需要平台电位"提供了细胞层面的机制：平台电位提供了 L 型 Ca²⁺ 内流，激活 CaMKII 和其他 Ca 依赖激酶，产生比 NMDA 受体单独激活更强的突触修改信号。

---

## 来源 3：Hafting et al. 2005 (PMID:15965463)

**标题**：Microstructure of a spatial map in the entorhinal cortex  
**期刊**：Nature 436:801-806  
**全文**：未开放（Nature paywall）；读摘要

### 核心结论
- 内侧内嗅皮层（MEC）存在"网格细胞"：激活位置构成六角形网格
- 网格间距从 MEC 背侧到腹侧增大（精度梯度）
- 网格放电在地标消失后持续 → 路径整合机制
- 网格细胞的"朝向"和"间距"在相邻细胞间共享，"相位"不同

### 证据强度
高（里程碑式发现，已被数百项研究重复）。

---

## 来源 4：Hainmueller & Bartos 2020 (PMID:32042144, PMC7115869)

**标题**：Dentate gyrus circuits for encoding, retrieval and discrimination of episodic memories  
**期刊**：Nat Rev Neurosci 21:153-168  
**全文**：开放（PMC7115869）

### 关键信息（海马回路）
- DG 粒细胞活动极稀疏（<5%），主功能：模式分离
- DG 苔状纤维→CA3：促进 LTP，但记忆储存在 PP 和循环突触，不在苔状纤维
- 海马不是单一串行回路，而是并行回路（PP 直接到 CA1、CA3）
- MEC 抑制 → CA1 场所场长期稳定性下降

---

## 来源 5：Moser et al. 2008 (PMID:18284371)

**标题**：Place cells, grid cells, and the brain's spatial representation system  
**期刊**：Annu Rev Neurosci 31:69-89  
**全文**：未开放；读摘要

### 关键信息
- 场所细胞 + 网格细胞 + 头向细胞 + 边界细胞 → 大脑的空间表征系统
- 网格细胞为场所细胞提供坐标输入
- 场所细胞（位置码）是网格细胞（坐标码）的下游整合

---

## 来源 6：Li et al. 2024 (PMID:39454575)

**标题**：Mechanisms of memory-supporting neuronal dynamics in hippocampal area CA3  
**期刊**：Cell 187(XX)  
**全文**：未确认 PMC；读摘要

### 关键信息
- CA3 也有 BTSP，发生在循环突触（recurrent），而非苔状纤维
- CA3 的 BTSP 时间窗口**对称**（vs CA1 的不对称）
- 需要内嗅皮层输入来更新场所场；DG 不是必须的

---

## 来源 7：Milstein et al. 2021 (PMID:34882093)

**标题**：Bidirectional synaptic plasticity rapidly modifies hippocampal representations  
**期刊**：eLife 10:e73046  
**全文**：开放（eLife）

### 关键信息
- CA1 中树突钙棘波可以**双向**（增强或减弱）改变现有场所场
- 已建立的场所场中心位置的钙棘波 → 场所场加强
- 场所场边缘位置的钙棘波 → 场所场移位或缩小
- 表明 BTSP 是动态的双向调控，不只是写入

---

## 来源 8：Sumegi et al. 2025 (PMID:41025505)

**标题**：Diverse calcium dynamics underlie place field formation in hippocampal CA1 pyramidal cells  
**期刊**：eLife  
**全文**：开放（eLife）

### 关键信息
- 大量细胞（群体）钙成像研究发现场所场形成时的钙动态高度多样
- 部分场所场形成不符合典型 BTSP 特征曲线
- 暗示存在**多条并行路径**，BTSP 不是唯一机制

### 重要性
对 BTSP 模型的审慎挑战，需要与 Bittner 胞内记录（金标准）对比解读。可能反映细胞类型差异或成像分辨率的限制。

---

## 未解问题（今日新增）

1. BTSP 在人类海马中是否保守？
2. BTSP 与 STDP 的触发条件如何在体内动态切换？
3. 网格细胞六角图案的完整生成机制？
4. 场所细胞重映射（remapping）的触发条件？
5. 场所细胞是否编码情绪/奖励等非空间信息？

# 阅读笔记 — 2026-09-03

**文章**：小脑里的误差教师：浦肯野细胞如何将攀爬纤维信号转化为运动预测
**知识库日期**：2026-09-03 | **系统时钟**：2026-06-22 UTC+8

---

## 来源 1：Nguyen & Person (2025) — Nature Reviews Neuroscience

**PMID**：40523942 | **PMC**：12643008
**标题**：Cerebellar circuit computations for predictive motor control
**来源状态**：✅ 开放全文（PMC12643008）

### 问题：解决什么问题？
感觉延迟（50–120 ms）如何在快速运动中被克服；小脑如何实现预测性运动控制。

### 方法
综述 + 计算框架分析，整合电生理（in vivo 单神经元记录）、光遗传学、人群编码分析。

### 核心发现
- 小脑执行"feedforward control"：学习将感觉运动情景映射到预测性纠错信号
- 浦肯野细胞在运动中分为"抑制型"和"促进型"两群，人群层面产生净 DCN 调制
- 颗粒细胞生成"时序基底集合"：级联激活编码运动中的时间坐标
- 小脑实现的是 model-free implicit mapping，而非显式逆动力学模型

### 改变了哪些认识
从"小脑存储前向模型"升级到"小脑实现上下文→输出的隐式映射，无需显式内部模型"

### 证据强度
高（Nature Reviews 系统性综述，整合多条独立实验线）

### 局限
综述性，部分机制细节（如颗粒细胞时序编码的细节）需要原始实验进一步验证

---

## 来源 2：Jin & Hull (2025) — Current Biology

**PMID**：40848722 | **PMC**：12380153
**标题**：Reward-driven cerebellar climbing fiber activity influences both neural and behavioral learning
**来源状态**：✅ 开放全文（PMC12380153）

### 问题：解决什么问题？
攀爬纤维是否仅编码运动误差，还是也携带奖励相关信号？

### 方法
小鼠 Pavlovian 奖励任务 + 光纤钙成像（记录攀爬纤维诱导的复杂放电相关 Ca²⁺ 信号）+ 光遗传学抑制下橄榄核

### 核心发现
- 攀爬纤维活动具有奖励预测误差（rPE）特征：初始对意外奖励响应，随训练转移至 CS
- 刺激阻断效应证实 rPE 特性（与多巴胺系统相似）
- 光遗传学抑制下橄榄核阻断 CF 响应转移 → 损害预测性舔水的时间精度

### 改变了哪些认识
攀爬纤维不仅是"运动误差教师"，也是"奖励预测教师"——小脑可能参与广义强化学习

### 证据强度
中-高（单个实验室，光遗传学因果证明较强，但仅在小鼠 Pavlovian 任务中，泛化性待验证）

### 局限
仅测试了外侧小脑（crus I/II），其他小脑区域是否类似尚未确定；奖励 CF 信号与运动误差 CF 信号如何在同一 PC 上整合不清楚

---

## 来源 3：Xie et al. (2023) — eLife

**PMID**：37671785 | **PMC**：10541175
**标题**：Task-dependent optimal representations for cerebellar learning
**来源状态**：✅ 开放全文（PMC10541175）

### 问题：解决什么问题？
颗粒细胞应该以何种密度激活才最优？稀疏编码是否适合所有任务？

### 方法
理论计算分析 + 数学优化框架；将连续感觉运动任务与随机分类任务做比较

### 核心发现
- 随机刺激分类：稀疏颗粒细胞激活最优（经典 Marr-Albus 预测）
- 连续感觉运动变换（更接近真实运动）：较密集的颗粒细胞激活反而更优
- 颗粒细胞层"频率依赖的归纳偏差"使不同激活密度适合学习不同频率分量

### 改变了哪些认识
稀疏颗粒细胞编码不是普适真理，而是任务依赖的；颗粒细胞密度可能随任务自适应调整

### 证据强度
中（理论分析，缺乏体内系统验证）

---

## 来源 4：Fernández Santoro et al. (2024) — Front. Computational Neuroscience

**PMID**：39049990 | **PMC**：11266113
**标题**：Purkinje cell models: past, present and future
**来源状态**：✅ 开放全文（PMC11266113）

### 问题：解决什么问题？
计算模型如何捕捉浦肯野细胞的生理特征（放电、钙信号、突触可塑性）？

### 方法
综述：从 Hodgkin-Huxley 详细模型（1970s–1990s）到简化模型、突触模型、网络模型

### 核心发现
- 浦肯野细胞在脊椎动物中高度保守，"单一计算机制"可能在所有浦肯野细胞共享
- 复杂放电（complex spike）的持续时间可变，且携带量化的可塑性信息
- 多稳态（multistable）动力学是浦肯野细胞计算能力的来源之一

### 改变了哪些认识
浦肯野细胞不只是被动权重求和器，其自身动力学（多稳态、plateau potential）也是运算的一部分

---

## 来源 5：Zang & De Schutter (2019) — Front. Systems Neuroscience

**PMID**：31572132 | **PMC**：6749063
**标题**：Climbing Fibers Provide Graded Error Signals in Cerebellar Learning
**来源状态**：✅ 开放全文（PMC6749063）

### 核心发现
- CF 信号是梯度（analog）而非二元（binary）
- 复杂放电持续时间 + 背景突触活动 + 树突 Ca²⁺ 局部化 共同产生梯度误差信号
- 不同树突分支可能独立接受不同幅度的 LTD 驱动

---

## 来源 6：Schonewille et al. (2011) — Neuron

**PMID**：21482355 | **PMC**：3104468
**标题**：Reevaluating the Role of LTD in Cerebellar Motor Learning
**来源状态**：✅ 开放全文（PMC3104468）

### 核心发现
- 三种 AMPAR 内吞阻断突变小鼠的 VOR 适应、眼睑反射、步态学习均正常
- PF-PC LTD 不是运动学习的唯一必要机制
- 替代机制可能包括：MLI 可塑性、内在可塑性、DCN 可塑性

---

## 来源 7：Lee et al. (2023) — Cell Reports

**PMID**：37141091 | **PMC**：10258556
**标题**：Cerebellar granule cell signaling is indispensable for normal motor performance
**来源状态**：✅ 开放全文（PMC10258556）

### 核心发现
- 颗粒细胞 CaV2 敲除完全阻断苔藓纤维→颗粒细胞突触传递
- 小鼠出现严重运动障碍（平衡木、转棒）
- 浦肯野细胞基线放电保持正常，但运动相关调制消失
- 颗粒细胞信号负责编码运动上下文，而非维持 PC 基线活动

---

## 矛盾检查

**矛盾 1**：Jin & Hull 2025 的奖励 CF 信号 vs 经典"CF = 运动误差信号"
- 两者不必然矛盾：奖励 CF 可能主要在外侧小脑，运动误差 CF 主要在蚓部和中间区
- 可能代表小脑不同分区在功能上的分工
- 登记为潜在分区争议（下橄榄核功能异质性），但暂不登记为 contested_claim（尚无直接冲突实验）

**矛盾 2**：Xie 2023 密集颗粒细胞 vs 经典稀疏编码
- 理论层面的修正，非实验直接冲突
- 两者在不同任务类型下均成立（任务依赖），不登记为冲突

---

## Wiki 固结计划

今日文章触及的概念：
1. `purkinje-cell` — 无 wiki 页，新建
2. `climbing-fiber` — 无 wiki 页，新建
3. `granule-cell` — 无 wiki 页，新建（简版）
4. `cerebellar-ltd` — 已有 wiki 页，修订（加入 Schonewille 2011 revisit + 梯度 CF 信号）
5. `cerebellum` — 已有 wiki 页，修订（加入 Nguyen & Person 2025 前向控制框架 + Jin & Hull 2025 奖励 CF）
6. `dacc-conflict-monitoring` — 创建极简页（指向已有的 conflict-monitoring 和 anterior-cingulate-cortex），填补悬空引用

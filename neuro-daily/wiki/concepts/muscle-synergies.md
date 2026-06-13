---
title: 肌肉协同
slug: muscle-synergies
domain: concepts
type: mechanism
status: mainstream
confidence: medium
created: 2026-06-13
updated: 2026-06-13
revision_count: 2
dimensions: [molecular, cellular, microcircuit, spinal-cord, behavior]
related: [spinal-interneurons-locomotion, spinal-cord-cpg, corticospinal-tract, alpha-motor-neuron, optimal-feedback-control, rotational-dynamics-motor, motor-cortex]
prerequisites: [alpha-motor-neuron, spinal-cord-cpg, corticospinal-tract]
opens_questions: [Q-ms-01, Q-ms-02, Q-ms-03, Q-ms-04, Q-ofc-03]
source_articles: [2026-06-13-muscle-synergies-bernstein, 2026-06-13-week-synthesis-sensorimotor-feedback-integration]
key_sources: ["PMID:23641212", "PMID:16000633", "PMID:28739958", "PMID:30334575", "PMID:22570602", "PMID:35370571", "PMID:37737925"]
---

# 肌肉协同 (Muscle Synergies)

> **一句话定义**：多块肌肉被神经系统以固定比例绑定为功能模块，作为运动控制的基本单元被调用；脊髓中间神经元是这些模块的主要承载者，皮层通过调制模块的激活系数（而非直接控制单块肌肉）实现运动多样性。

## 当前理解

我们目前认为，脊髓中间神经元（Pre-Motor Interneurons, PreM-INs）以"聚类投射"方式组织，每个簇投射到对应同一功能群的多块肌肉，形成协同的神经实体（Takei & Seki 2017）。当运动皮层通过皮质脊髓束发出下行指令时，其作用是激活这些预存在脊髓的协同模块，而非逐一控制肌纤维（Ortega-Auriol et al. 2023 的 CSC 显著、CMC 不显著证据支持这一观点）。

从 EMG 数据的角度，肌肉协同满足分解：M ≈ Σ aᵢ(t)·Wᵢ，其中 Wᵢ 为时不变权重向量（协同结构），aᵢ(t) 为激活系数（时序包络）。4–7 个协同通常解释 85–95% 的 EMG 方差。

然而，神经起源假说面临严肃挑战（Kutch & Valero-Cuevas 2012）：生物力学约束本身可以产生低维 EMG 模式，现有研究尚未充分控制非神经因素。这是一个重要的未解张力（见争议）。

**置信度 medium 的原因**：脊髓横断和去传入证据支持中枢起源，PreM-IN 聚类提供了神经元级证据；但最终的因果实验（选择性阻断特定 PreM-IN 簇后观察对应协同消失）尚未完成，且生物力学替代解释未被完全排除。

## 关键机制

### 层次化控制架构

```
皮层 → 协同激活系数 a(t)
         ↓ 皮质脊髓束
脊髓 PreM-IN 簇 → 协同权重 W（固定）
         ↓ 直接突触
α运动神经元池 → 肌肉激活 M
```

- **第 1 层（皮层）**：选择哪个协同、何时以何种幅度激活（CSC 频带：α 和 β）
- **第 2 层（脊髓中间神经元）**：存储协同结构 W，将激活信号"解压缩"为多肌肉模式
- **第 3 层（α-MN 池）**：执行最终的肌肉收缩

### 协同的刚性与灵活性

- **刚性**：协同结构 W 在不同运动方向/距离中保持稳定（跨条件稳健性）；脊髓横断和中风后协同结构仍可识别（神经损伤下的保守性）
- **灵活性**：激活系数 aᵢ(t) 随任务连续可变；协同在技能习得过程中可缓慢重组（成人主要调整 a(t)，发育期可形成新协同）

### 提取方法

非负矩阵分解（NMF）：约束 W≥0, A≥0，对应肌肉只能收缩的物理约束。协同数量由"解释方差-协同数"曲线的拐点确定（通常 85–95% 方差为门槛）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 协同有中枢起源，不依赖感觉反馈 | 青蛙去传入后 4–6/6 协同保留 | PMID:16000633 | 高（多动物、多行为） |
| 脊髓编码步态协同，不需要大脑 | 猫完整脊髓横断后 7 个协同保留 | PMID:30334575 | 高 |
| PreM-INs 以聚类方式实现协同 | 猕猴 PreM-IN 肌肉场聚类，群体活动解释 60% 协同 | PMID:28739958 | 中（神经元样本量有限） |
| 皮层通过协同而非直接肌肉控制运动 | CMC 不显著，CSC 显著 | PMID:37737925 | 中（单一实验室，任务限于等长收缩） |
| 生物力学约束可产生类协同低维结构 | 计算分析：可行力空间低维性 | PMID:22570602 | 中（理论论证为主） |
| 协同鲁棒性来自脊髓群体编码异质性 | 群体协同模型：相似度 > 0.90（ρ≤0.3） | PMID:35370571 | 中（模型预测待体内验证） |

## 争议：神经实体 vs 生物力学约束

**张力的本质**：
- **神经起源立场**（Bizzi、d'Avella、Cheung、Tresch）：去传入/脊髓横断证据 + PreM-IN 聚类证据，协同是脊髓网络的真实属性
- **生物力学约束立场**（Kutch、Valero-Cuevas）：任何在低维力空间中运动的系统都会产生低维 EMG，无需神经模块；"证明门槛未被满足"

**为何难以裁决**：生物力学约束与神经协同的预测在大多数实验中重叠；真正裁决需要的实验（选择性阻断特定 PreM-IN 簇）在技术上极为困难。

**可能的调和**：两者可能都是真的——进化优化使得神经协同与生物力学约束"对齐"（协同结构反映最优力学配置），因此两种解释的预测难以区分。

登记矛盾：见 `state/contested_claims.json`（C-2026-06-06-ms-01）

## 连接

- [[spinal-cord-cpg]] — 脊髓 CPG 可能是步态协同的组织基础
- [[spinal-interneurons-locomotion]] — PreM-INs 是协同的神经实体
- [[alpha-motor-neuron]] — 协同的最终执行者
- [[corticospinal-tract]] — 皮层通过 CST 调制协同激活，CM 细胞可绕过协同实现精细控制
- [[motor-cortex]] — 皮层旋转动力学与协同激活的关系待厘清
- [[optimal-feedback-control]] — OFC 在协同空间中可能有更高效的实现（Q-ofc-03）

## 未解问题

- Q-ms-01（高）：如何设计实验证明 PreM-IN 簇是协同的必要条件（控制生物力学约束）？
- Q-ms-02（中）：专业训练（如杂技演员）是否能在成年后形成全新协同？
- Q-ms-03（中）：专门针对协同结构的康复方案能否逆转中风后的协同合并？
- Q-ms-04（低）：OFC 能否在协同空间中被完整形式化，使计算维度大幅降低？

## 修订历史

- 2026-06-13 · 创建（rev1）· 基于文章 #182《运动的降维之道》· 初始置信度：medium（中枢起源证据支持，但生物力学替代解释未完全排除）
- 2026-06-13 · 修订（rev2）· 周综合 #183：在感觉运动整合框架中，协同被明确为"维度压缩"三原则之一；与 OFC 的关系得到阐明——OFC 将600维肌肉控制问题降至4–7维协同层面，使最优控制在计算上可行

## 来源文章

- [[2026-06-13-muscle-synergies-bernstein]]
- [[2026-06-13-week-synthesis-sensorimotor-feedback-integration]]

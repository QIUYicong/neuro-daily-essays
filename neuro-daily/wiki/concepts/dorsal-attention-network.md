---
title: 背侧注意网络（DAN）
slug: dorsal-attention-network
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-01
updated: 2026-07-15
revision_count: 2
dimensions: [brain-region, whole-brain-network, cognition, behavior]
related: [working-memory, prefrontal-cortex, v1-primary-visual-cortex, thalamus, thalamocortical-circuit, biased-competition, attentional-blink, global-workspace-theory, predictive-coding, transformer-self-attention, attractor-network]
prerequisites: [prefrontal-cortex, v1-primary-visual-cortex, thalamus]
opens_questions: [Q-dan-01, Q-dan-02, Q-dan-03]
source_articles: [2026-07-01-dorsal-attention-network-FEF-IPS, 2026-07-15-brain-attention-transformer-qkv]
key_sources: ["PMID:11994752", "PMID:20192813", "PMID:13679398", "PMID:36730414", "PMID:10376597", "PMID:42125965", "PMID:17417935", "arXiv:2008.02217", "DOI:10.1371/journal.pcbi.1011843"]
---

# 背侧注意网络（Dorsal Attention Network, DAN）

> **一句话定义**：由额叶眼区（FEF）和顶内沟（IPS/LIP）构成的目标驱动注意控制系统，通过LIP优先级地图整合信号，经V4→V1皮层反馈和FEF→TRN丘脑通路，对感觉皮层施加**乘法性增益调制**，实现空间注意的自上而下控制。

## 当前理解

我们现在认为，空间注意的神经控制由两套解剖上分离的网络共同实现（Corbetta & Shulman 2002, PMID:11994752）：

**背侧注意网络（DAN）**
- 核心节点：**额叶眼区（FEF, BA8）** + **顶内沟（IPS）及顶上小叶（SPL）**
- 功能特征：**目标驱动**（goal-directed）的自上而下注意控制
- 时序特征：在视觉刺激出现之**前**即已激活（预期性激活），是注意的主动预部署机制
- 两侧半球对称分布

**腹侧注意网络（VAN）**  
- 核心节点：右侧颞顶联合区（TPJ）+ 腹侧额叶皮层（VFC/IFG）
- 功能特征：**显著性驱动**（stimulus-driven）的意外刺激定向响应
- 明显右侧偏侧化

DAN 的核心操作逻辑是：将当前行为目标（"我需要找蓝色目标"）转化为感觉皮层的**增益状态变化**，在视觉刺激到达之前就预先放大特定视野区的神经处理能力。

## 关键机制

### 优先级地图（LIP/IPS）
顶内沟中的外侧顶叶内区（LIP）充当**优先级地图**（Bisley & Goldberg 2010, PMID:20192813）：
- 整合视觉信号、扫视计划信号和认知目标信号（三类信号可线性叠加）
- 活动峰值（population peak）反映行为优先级最高的位置
- 指导后续注意部署和眼动目标选择，两者共享同一地图

### FEF 的因果控制
FEF 微电刺激实验（Moore & Fallah 2004, PMID:13679398）证明：
- 次发放阈值（sub-saccadic）FEF 刺激因果性提高对应视野区目标的检测灵敏度（d' 提升）
- 效果严格视网膜拓扑性（只在 FEF 运动场对应位置有效）
- 等效于消除该位置的竞争干扰物

### V4→V1 皮层反馈增益调制
注意的感觉皮层效应通过皮层间反馈传递（Debes & Dragoi 2023, PMID:36730414）：
- 选择性消除 V4→V1 的反馈投射 → V1 注意调制效应完全消失
- 前馈感觉响应（V1 的基础视觉处理）保持正常
- 反馈末梢集中在 V1 浅层（L2/3），符合皮层间反馈终止规律

### 乘法性增益调制
注意产生的是**乘法增益**而非加法偏移（Treue & Martínez Trujillo 1999, PMID:10376597）：
- 调谐曲线幅度整体放大（~50-100%），但形状（偏好方向、调谐宽度）不变
- 保持感知特异性，同时提高信号清晰度
- 这使注意提高信号对比度而不引入感知畸变

### TRN 门控接口
FEF/IPS 也投射到视丘网状核（TRN），通过皮层-视丘回路传递注意信号（Halassa & Kastner 2017, PMID:29275841）：
- FEF → TRN → 视丘核（LGN/枕核等）→ 感觉皮层
- 与皮层直接反馈通路（FEF→V4→V1）并行，提供更大范围的感觉门控

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| DAN（FEF+IPS）控制目标驱动注意 | fMRI 系统综述 + 空间忽视病变分析 | Corbetta & Shulman 2002, PMID:11994752 | 高 |
| LIP 是整合多信号的优先级地图 | 猕猴 LIP 单单元记录 + 药理失活 | Bisley & Goldberg 2010, PMID:20192813 | 高 |
| FEF 次发放阈值刺激因果增强对应视野注意 | 猕猴 FEF 微电刺激 + 视觉检测任务 | Moore & Fallah 2004, PMID:13679398 | 高 |
| V4→V1 反馈是 V1 注意调制的必要通道 | 猕猴 AAV 反馈末梢标记 + 光遗传抑制 | Debes & Dragoi 2023, PMID:36730414 | 高（需重复）|
| 注意通过乘法增益调制 MT 神经元 | 猕猴 MT 方向调谐曲线测量 | Treue & Trujillo 1999, PMID:10376597 | 高 |
| 人类 fMRI 确认 FEF/IPS 在空间注意中的角色 | 人类 fMRI + Posner 线索任务 | Chen et al. 2026, PMID:42125965 | 中-高 |

## DAN 与 Transformer Q/K/V 的类比

Knudsen（2007, PMID:17417935）将注意力分解为四个组件：工作记忆（维持目标模板）、自上而下灵敏度控制（偏置感觉皮层）、竞争性选择（赢者通吃）、自动底部过滤（显著性驱动）。这四个组件在 Transformer 自注意力中均有对应：

| Knudsen 注意力组件 | 生物实现 | Transformer 对应 |
|-----------------|---------|----------------|
| 工作记忆（目标模板） | dlPFC 吸引子活动 | Query 投影矩阵 $W_Q$（编码当前任务目标） |
| 自上而下灵敏度控制 | FEF/IPS top-down 偏置信号 | QK 点积相似度计算 |
| 竞争性选择 | V4/IT 侧抑制 + 赢者通吃 | softmax 归一化（竞争-选择） |
| 自动底部过滤 | 显著性地图 / VAN（TPJ） | 位置编码 + 无监督注意头 |

关键：FEF 同时控制注意和眼动（眼球运动 = 行动），而 Transformer 的注意力与任何运动输出完全脱耦——这是最根本的不对称之一。

## 连接

- [[prefrontal-cortex]] — FEF（BA8）是 PFC 的注意控制子区域
- [[working-memory]] — DAN 与 dlPFC 工作记忆共享注意资源调配功能；WM 维持 Query 信号
- [[v1-primary-visual-cortex]] — DAN 通过 V4→V1 反馈产生乘法增益调制
- [[thalamus]] — FEF/IPS → TRN 通路实现皮层注意信号的视丘门控
- [[thalamocortical-circuit]] — TRN 是 DAN 信号传递到感觉门控的接口
- [[biased-competition]] — DAN 是偏置竞争模型的神经回路实现
- [[attentional-blink]] — 注意瞬盲反映 DAN 广播的时间容量约束
- [[global-workspace-theory]] — DAN 为 GWT 的广播机制提供空间选择基础
- [[predictive-coding]] — 注意 = 感觉精度的主动上调（DAN 是精度加权的硬件）
- [[transformer-self-attention]] — DAN 信号 = 生物 Query；感觉皮层特征 = 生物 K/V；完整类比见专页
- [[attractor-network]] — FEF 的吸引子动力学维持目标模板（Query 向量的生物基础）

## 未解问题

- Q-dan-01：FEF→V4 皮层通路 vs FEF→TRN 丘脑通路的相对速度和贡献比较
- Q-dan-02：人类 FEF 与猕猴 FEF 的精确功能同源性
- Q-dan-03：DAN 是否调控全局警觉状态，还是只负责局部位置注意
- Q-thalamus-burst-awake：清醒视丘爆发放电与 DAN 注意转移的关系（已登记）

## 修订历史

- 2026-07-01 · 创建 · 基于《空间注意的神经回路》一文 · 来源：Corbetta & Shulman 2002, Bisley & Goldberg 2010, Moore & Fallah 2004, Debes & Dragoi 2023, Treue & Trujillo 1999 · 初始置信度：高
- 2026-07-15 · 修订 · 基于《同一个算法，两种实现》一文 · 新增"DAN 与 Transformer Q/K/V 的类比"一节（Knudsen 2007 四组件框架与 Q/K/V 的对应）；related 新增 transformer-self-attention、attractor-network；key_sources 新增 PMID:17417935、arXiv:2008.02217、DOI:10.1371/journal.pcbi.1011843

## 来源文章

- [[2026-07-01-dorsal-attention-network-FEF-IPS]]

---
title: 内感觉
slug: interoception
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-22
updated: 2026-08-22
revision_count: 1
dimensions: [molecular, cellular, brain-region, cognition]
related: [insular-cortex, anterior-cingulate-cortex, active-inference, precision-weighting, embodied-semantics, pain-matrix]
prerequisites: [thalamus, somatosensory-cortex]
opens_questions: [Q-ins-01, Q-ins-02]
source_articles: [2026-08-22-insular-cortex-interoception-bodily-self]
key_sources: ["PMID:12154366", "PMID:19096369", "PMID:26016744", "PMID:30985277"]
---

# 内感觉 (Interoception)

> **一句话定义**：内感觉是大脑对身体内部生理状态（心率、内脏张力、温度、痒、渴、饥饿等）的感知系统，有专属的脊髓→脑干→丘脑 VMpo→后岛叶解剖通路，与外感觉体感系统相互独立，并在前岛叶经高阶整合后转化为主观感受。

## 当前理解

我们现在认为，内感觉不是体感觉的子集，而是一个独立的感觉系统。其核心解剖证据是：脊髓背角 I 层（lamina I）的专属神经元接收来自内脏器官、血管、皮下组织的化学感受器和机械感受器信号，经由脑干（孤束核 NTS、臂旁核 PBN）传递至丘脑 VMpo 核（灵长类特有精细核团），再投射至后岛叶皮层，形成区别于皮肤体感（VPM→S1）的平行内感觉通路（Craig 2002, PMID:12154366）。

在计算层面，Barrett 和 Simmons（2015, PMID:26016744）提出的 EPIC 模型认为，内感觉体验**不只是对身体信号的读取，更是大脑对身体状态的主动预测**：前岛作为预测发生器向后岛发出下行预测，后岛将实际传入信号与预测比较，将误差向前传回。感受 = 大脑当前的内感觉预测 + 实际信号约束下的校正。

## 关键机制

### 解剖通路

```
内脏感受器 / 皮下组织
    ↓ （Aδ/C 纤维）
脊髓背角 I 层（lamina I）
    ↓ （脊髓-丘脑内感觉束）
脑干：孤束核（NTS）→ 臂旁核（PBN）
    ↓
丘脑 VMpo 核（灵长类特有）
    ↓
后岛叶皮层（初级内感觉皮层）
    ↓ 阶梯整合
中岛 → 前岛 → 前岛极
```

### 后→前梯度

- **后岛（颗粒型）**：身体物理参数的原始拓扑地图（疼痛、温度、心率）；体感拓扑组织（手区面积最大）
- **中岛（无颗粒过渡）**：预测误差计算；行为背景的整合
- **前岛（无颗粒）**：主观感受生成；情绪显著性整合；躯体标记的意识化
- **前岛极**：网络状态整合；沉默于单一刺激但响应显著性变化；顶端非对称控制

### 内感觉精确度（Interoceptive Accuracy）

个体在觉察自身心跳（heartbeat detection）的准确性（内感觉精确度）与前岛激活强度正相关（Wang et al. 2019, PMID:30985277）。前岛局灶性病变导致呼吸觉察 d' 显著下降，视觉检测不受影响（因果证据）。

### 主动推断（Active Interoceptive Inference）

当内感觉预测误差高且不可用认知校正消除时，前岛/aINS 通过下行自主神经信号主动改变身体状态（如提高心率、调节呼吸）以使身体符合预测——这是内感觉的"主动"维度（Friston 主动推断在内脏域的实现）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| lamina I → VMpo → 后岛是专属内感觉通路（区别于 VPM→S1） | 非人灵长类解剖追踪 + 人类神经影像 | PMID:12154366 | 高 |
| 后岛是初级内感觉皮层（疼痛温度体感拓扑） | SEEG 颅内刺激（n=87），清晰体感拓扑 | PMID:41836516（预印本） | 新兴 |
| AIC 对内感觉注意必要 | AIC 病变（n=6）→呼吸觉察 d' 显著降低 | PMID:30985277 | 高 |
| 内感觉为预测性构建（EPIC 模型） | 层级解剖（无颗粒→颗粒方向）+ 理论建模 | PMID:26016744 | 中（理论） |

## 连接

- [[insular-cortex]] — 内感觉的核心皮层基础（后→中→前梯度轴）
- [[anterior-cingulate-cortex]] — 共同参与情绪显著性和内感觉的认知调制
- [[active-inference]] — EPIC 模型是 Friston 主动推断在内感觉域的具体化
- [[precision-weighting]] — DA/ACh 调制内感觉预测的精确度权重
- [[pain-matrix]] — 疼痛感受的内感觉成分通过后岛-前岛通路
- [[embodied-semantics]] — 内感觉参与语义表征的身体锚定

## 未解问题

- Q-ins-01：Craig 映射框架 vs. Barrett 预测框架——哪个时序优先？可否用 ECoG 时间解码验证？
- Q-ins-02：前岛极沉默的机制——网络状态依赖还是频率不匹配？

## 修订历史

- 2026-08-22 · 创建 · 基于《岛叶皮层：身体的感知地图如何生成主观感受并导航决策》· 初始置信度：高

## 来源文章

- [[2026-08-22-insular-cortex-interoception-bodily-self]]

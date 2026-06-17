---
title: 丘脑枕叶
slug: pulvinar
domain: systems
type: region
status: established
confidence: high
created: 2026-06-17
updated: 2026-06-17
revision_count: 1
dimensions: [brain-region, microcircuit, whole-brain-network, cognition]
related: [thalamic-reticular-nucleus, lateral-geniculate-nucleus, thalamocortical-circuit, transthalamic-pathway, prefrontal-cortex, dorsal-attention-network, v1-primary-visual-cortex, superior-colliculus, attention-consciousness-dissociation]
prerequisites: [thalamus, thalamocortical-circuit, action-potential, thalamic-firing-modes]
opens_questions: [Q-pulvinar-01, Q-pulvinar-02, Q-pulvinar-03]
source_articles: [2026-06-17-pulvinar-visual-attention-router]
key_sources: ["PMID:38143202", "PMID:39197951", "PMID:22561455", "PMID:22968697", "PMID:26748092", "PMID:19237580", "PMID:32290073", "PMID:32942125"]
---

# 丘脑枕叶 (Pulvinar)

> **一句话定义**：丘脑枕叶是灵长类丘脑中体积最大的高阶核团，接收来自皮层 Layer 5 的"驱动性"投射并将信号转发至其他皮层区域，通过控制 alpha/gamma 振荡协调皮层间信息流，并在竞争注意条件下对忽视目标实施真正的"门控排除"（而非仅仅增益下调）。

## 当前理解

我们现在认为，丘脑枕叶不是一个被动的视觉信号中继站，而是皮层间通信的**高阶路由枢纽**——它在直接皮层-皮层连接之外，提供了一条可被注意力状态动态调制的并行通道（跨丘脑皮层通路）。

枕叶有四个功能相对独立的亚核：
- **下枕叶（PI）**：连接 V1、MT/MST，中继初级与背侧流视觉信号
- **侧枕叶（PL）**：连接 V1-V4、IT、顶下小叶、dlPFC，负责腹侧流精细视觉与空间注意
- **内侧枕叶（PM）**：连接颞/顶/前额叶、OFC、杏仁核，与执行功能和情绪性注意关联
- **前枕叶（PA）**：连接体感和运动皮层（功能争议较多）

在注意力状态下，枕叶对竞争刺激中被注意目标的编码实现**精确保留**，同时对被忽视目标的编码实施**完全排除**（Fischer & Whitney 2012）——这比早期视觉皮层（V1-MT+）的增益调制更彻底。

枕叶还作为皮层间振荡协调器：正常状态下协调 gamma（前馈，低级→高级皮层）和 alpha（反馈，高级→低级皮层）的平衡；失活后皮层出现异常 gamma 上升和 alpha 反馈减弱（Cortes et al. 2020）。

## 关键机制

### 跨丘脑皮层通路（Transthalamic Pathway）
- 皮层 A 的 Layer 5 锥体神经元 → 枕叶亚核（driver 输入，强 AMPA 突触）
- 枕叶神经元 → 皮层 B 的 Layer 1/上层（兴奋性，到达不同皮层区）
- 与直接皮层 A→B 连接并行存在
- TRN 对枕叶输出的 GABAergic 投射提供选择性门控（哪些枕叶-皮层路径被允许）

### V1 门控（Lateral Pulvinar）
- 侧枕叶失活 → V1 视觉响应 −64%；脉冲发放完全几乎消失（95% 神经元）
- 侧枕叶激活 → 对应感受野 V1 中央 +232%，周边 −83%（center-surround 结构）
- 枕叶对 V1 的驱动独立于 LGN（LGN 完全毁损后仍可 14× 激活 V1）

### 注意力门控编码（Human fMRI）
- 被注意刺激：位置和方向均可从枕叶 BOLD 解码
- 被忽视刺激：两者均不可检测（真正门控，非增益下调）
- 枕叶的注意调制强于 V1-MT+ 视觉皮层

### 振荡同步（Alpha / Gamma 协调）
- 枕叶协调 gamma（前馈：V1→高级皮层）和 alpha（反馈：高级→V1）的正常平衡
- 枕叶失活：高级视觉皮层 gamma +103%，皮层进入"慢波样"状态
- 注意力以 theta 节律在枕叶中周期性组织；alpha 同步主要发生在注意准备期（delay period）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 侧枕叶失活使 V1 响应降低 64% | 猫/猴：muscimol 注射，多电极记录 V1 | PMID:22561455 | 高 |
| 枕叶驱动 V1 独立于 LGN | LGN 毁损后枕叶激活仍 14× V1 响应 | PMID:22561455 | 高 |
| 注意力在人类枕叶中完全排除忽视物编码 | 人类 fMRI，SVM 解码，竞争刺激范式 | PMID:22968697 | 高 |
| 枕叶注意调制强于 V1-MT+ | 枕叶 vs 早期视觉皮层注意效果对比，p=0.008 | PMID:22968697 | 高 |
| 腹侧枕叶失活使注意力任务从 74% 降至 11% | 猴：muscimol，注意力行为任务 | PMID:26748092 | 高 |
| 枕叶失活使高级视觉皮层 gamma 增加 103% | 猫：LP 失活，32 道 LFP，Granger 分析 | PMID:32290073 | 中（猫数据，2只） |
| 枕叶损伤导致选择性干扰物过滤障碍 | 3 例人类单侧枕叶损伤患者临床研究 | PMID:19237580 | 中（N=3） |
| 枕叶 Layer 5 driver + Layer 6 modulator 双通道 | 综述：多物种解剖学+电生理 | PMID:39197951 | 中（综述整合） |

## 连接

- [[thalamic-reticular-nucleus]] — TRN 对枕叶输出的 GABAergic 门控：TRN 是一阶闸门，枕叶是高阶路由器
- [[lateral-geniculate-nucleus]] — LGN 是一阶核（视网膜输入→V1），枕叶是高阶核（皮层输入→皮层），两条并行丘脑-V1 通路
- [[transthalamic-pathway]] — 枕叶是跨丘脑皮层通路的核心节点
- [[thalamocortical-circuit]] — 枕叶是 TC 回路的高阶延伸
- [[prefrontal-cortex]] — PFC 通过 PM 亚核参与情绪性和执行性注意
- [[dorsal-attention-network]] — 与枕叶的空间注意功能（PL 亚核→IPL）紧密关联
- [[v1-primary-visual-cortex]] — 枕叶是 V1 的重要门控来源（与 LGN 并行）
- [[superior-colliculus]] — 上丘→枕叶：空间显著性的皮层下通道

## 未解问题

- Q-pulvinar-01（高）：Layer 5 driver 和 Layer 6 modulator 是否靶向枕叶内不同细胞类型/亚核？两条输入通路如何在枕叶内整合？
- Q-pulvinar-02（中）：枕叶在睡眠中扮演什么角色？是否参与记忆巩固期的皮层间信息重播？
- Q-pulvinar-03（中）：PM（内侧枕叶）在情绪性注意和焦虑中的因果角色？是否是 PTSD 等障碍中过度威胁注意的节点？

## 修订历史

- 2026-06-17 · 创建 · 基于《丘脑枕叶：视觉注意的皮层下路由器》（#197）· 来源 8 篇开放全文 + 3 篇摘要 · 初始置信度：高（已建立）

## 来源文章

- [[2026-06-17-pulvinar-visual-attention-router]]

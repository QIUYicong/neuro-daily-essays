---
title: 额眼区（FEF）
slug: frontal-eye-field
domain: systems
type: region
status: established
confidence: high
created: 2026-09-13
updated: 2026-09-13
revision_count: 1
dimensions: [brain-region, whole-brain-network, cognition, behavior]
related: [dorsal-attention-network, biased-competition, v1-primary-visual-cortex, gamma-oscillations, alpha-oscillations, posterior-parietal-cortex, superior-colliculus, feature-based-attention, prefrontal-cortex, divisive-normalization]
prerequisites: [dorsal-attention-network, biased-competition, cortical-layers]
opens_questions: [Q-fef-01, Q-fef-02, Q-fef-03]
source_articles: [2026-09-13-fef-attention-oscillatory-feedback-biased-competition]
key_sources: ["PMID:20303256", "PMID:22325208", "PMID:25632139", "PMID:38194453", "PMID:38759641", "PMID:9770219", "PMC2901796", "PMC3297082", "PMC4308606", "PMC10801865"]
---

# 额眼区（Frontal Eye Field, FEF）

> **一句话定义**：额眼区（前运动皮层 BA8，前弓状沟回腹侧）是控制眼动优先级的皮层运动区，同时作为背侧注意网络（DAN）的核心节点，通过 γ 振荡同步（增强注意目标）与 α 抑制（压制干扰物）对 V4/MT 等视觉皮层施加因果性的自上而下注意增益调制；2024 年光遗传学实验定量确认直接 FEF→MT 通路贡献约 30% 的注意调制效应。

## 当前理解

我们现在认为，额眼区（FEF）是灵长类动物大脑中**唯一一个被直接实验证明可以因果驱动视觉皮层注意调制**的前额皮层区域（Noudoost et al. 2010, PMID:20303256）。

**进化逻辑**：FEF 原本是控制目标导向性扫视的运动前区，但它包含精细的视网膜拓扑优先级地图——控制眼动的区域必然知道"眼动目标在哪里"，而注意与眼动共用同一套优先级表征系统。因此 FEF 被"劫持"为自上而下注意控制的核心节点。

**双重身份**：
1. **运动规划区**：高强度刺激（>50μA）诱发扫视；包含视觉神经元、运动神经元、视觉运动神经元三类
2. **注意控制区**：次发放阈值（sub-saccadic）刺激不引发眼动，但提升对应视野位置的视觉感知阈值（Moore & Fallah 2001/2004, PMID:13679398）

**关键解剖**：FEF 有直接前馈投射到 V4、MT（V5）和 V3a，以及间接投射到 V1（通过 V4→V1 皮层间反馈链）。这些反馈投射终止于目标区域的 **L1 和 L5–6**（Hüer et al. 2024, PMID:38194453），符合皮层间反馈解剖规律。

## 关键机制

### 1. 因果性注意增益（微电刺激证据）

次发放阈值 FEF 微电刺激（Moore & Fallah 2001, 2004；Moore & Armstrong 2003）：
- 因果提升对应视野目标的检测 d'（信号检测论灵敏度）
- 在约 **40 毫秒**内增强 V4 对应感受野神经元的放电率
- 效果严格视网膜拓扑（仅限 FEF 运动场对应位置，临近位置无效）

### 2. γ 振荡同步通道（注意"开路"）

**Gregoriou et al. 2012**（PMID:22325208）：
- 注意期间，FEF **视觉神经元**（非运动神经元）与 V4 之间 35–60 Hz γ 相干性增强 16%（p<0.001）
- 细胞类型高度特异：运动细胞无此效应，视觉细胞专用
- γ 同步先于 V4 放电率变化（暗示 FEF 是驱动方）
- V1–V4 之间无对应 γ 同步增强（此为 FEF→V4 的长程效应，非 V1→V4 前馈）

### 3. α 振荡抑制通道（干扰"关路"）

**Marshall et al. 2015**（PMID:25632139）：
- FEF 因果控制对侧视觉皮层的 **预期性 α 功率降低**（注意侧，"去抑制"）
- 左右 FEF 均控制 α 调制；但右侧 FEF 额外控制刺激诱发 γ 增强（右半球主导性）
- FEF 受损后对侧视野目标反应时显著变慢

### 4. 层特异性反馈（2024 光遗传学）

**Hüer et al. 2024**（PMID:38194453）通路选择性光遗传学：
- 直接 FEF→MT 通路贡献注意调制效应的 **约 30%**（另 70% 来自其他通路）
- 反馈末梢在 MT 的 **L1 和 L5–6**
- 关闭此通路不影响基础视觉响应，只减弱注意成分

### 5. 特征注意 vs 空间注意的功能分工

空间注意主要由 **FEF（背侧弓前区）** 控制；特征注意由 **VPA（腹侧弓前区，FEF 腹侧邻居）** 控制（Bichot et al. 2019, PMID:31844117）：
- VPA 失活消除 V4 的特征调制，空间调制不受影响
- 两个区域都向 V4 直接投射，但传递不同维度的"偏置信号"

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| FEF 次发放阈值刺激提升目标检测 d' | 猕猴微电刺激 + 行为测量 | Moore & Fallah 2004, PMID:13679398 | 高 |
| FEF→V4 因果增益，40ms 内 | 猕猴微电刺激 + V4 单单元记录 | Noudoost 2010, PMID:20303256 | 高 |
| FEF 视觉细胞（非运动细胞）与 V4 注意 γ 同步 | 猕猴双区同时记录 + 相干性分析 | Gregoriou 2012, PMID:22325208 | 高 |
| FEF 因果控制枕叶 α 振荡 | 人类 TMS-MEG | Marshall 2015, PMID:25632139 | 中-高 |
| FEF→MT 直接通路贡献 ~30% 注意效应 | 猕猴通路选择性光遗传学 | Hüer 2024, PMID:38194453 | 中（单实验室，灵长类） |
| VPA（非 FEF）控制特征注意 | 猕猴 VPA 失活 + V4 记录 | Bichot 2019, PMID:31844117 | 高 |
| 反馈投射终止 L1/L5–6 | 解剖追踪 + 光遗传学 | Hüer 2024 | 中-高 |

## 连接

- [[dorsal-attention-network]] — FEF 是 DAN 的核心节点之一（与 IPS 并列）
- [[biased-competition]] — FEF 的反馈信号是偏置竞争的主要"偏置信号"来源
- [[v1-primary-visual-cortex]] — FEF 通过 V4→V1 间接反馈影响 V1；直接投射较弱
- [[gamma-oscillations]] — FEF 视觉细胞与 V4 的 γ 同步是注意信号的频率载体之一
- [[alpha-oscillations]] — FEF 因果控制对侧视觉皮层 α 功率降低（注意侧去抑制）
- [[posterior-parietal-cortex]] — IPS/LIP 与 FEF 共同构成 DAN；LIP 整合优先级信号
- [[superior-colliculus]] — FEF 与 SC 有双向联系；两者在空间优先级和注意中协同
- [[feature-based-attention]] — 特征注意由 VPA（FEF 腹侧邻居）而非 FEF 控制
- [[divisive-normalization]] — FEF 传递的注意增益信号在 V4 中通过除法规范化实现
- [[prefrontal-cortex]] — FEF 是前额皮层的一个功能特化子区，运动控制+注意功能并存

## 未解问题

- **Q-fef-01（高优先级）**：FEF→视觉皮层的其余 70% 注意信号来自哪里？IPS→MT 直接通路？FEF→V4→MT 的间接路径？不同通路在不同任务条件下的权重如何动态变化？
- **Q-fef-02（高优先级）**：猕猴实验中 γ 主导 FEF→V4 同步，而人类 TMS 实验揭示 β 主导——这是真实的物种差异，还是方法学灵敏度差异（MEG 对高频 γ 的检测能力有限）？
- **Q-fef-03（中优先级）**：FEF 视觉神经元的 γ 同步是注意增益的**因果载体**，还是仅仅是与放电率增加同时发生的相关现象？（Spyropoulos 2024 提示后者可能更重要，但未直接检验 FEF 侧的因果性）

## 修订历史

- 2026-09-13 · 创建 · 基于《偏置竞争的解剖学》一文（#143） · 来源：Noudoost 2010, Gregoriou 2012, Marshall 2015, Bichot 2019, Hüer 2024 · 初始置信度：高

## 来源文章

- [[2026-09-13-fef-attention-oscillatory-feedback-biased-competition]]

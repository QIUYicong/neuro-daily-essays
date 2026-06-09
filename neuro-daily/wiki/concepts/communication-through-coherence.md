---
title: 相干通信（CTC）
slug: communication-through-coherence
domain: concepts
type: theory
status: emerging
confidence: medium
created: 2026-08-31
updated: 2026-08-31
revision_count: 1
dimensions: [microcircuit, brain-region, whole-brain-network, cognition]
related: [gamma-oscillations, alpha-oscillations, dorsal-attention-network, frontal-eye-fields, biased-competition, predictive-coding, ei-balance]
prerequisites: [gamma-oscillations, alpha-oscillations, action-potential, synaptic-transmission]
opens_questions: [Q-ctc-01, Q-ctc-02]
source_articles: [2026-08-31-attention-frontoparietal-fef-alpha-gamma]
key_sources: ["PMID:26447583", "PMID:25585017", "PMID:19478185", "PMID:16774286"]
---

# 相干通信（Communication through Coherence, CTC）

> **一句话定义**：Pascal Fries 提出的注意与跨区通信理论：神经区域之间的有效通信取决于发送区的节律性输出与接收区的可兴奋相（γ 波谷）是否同步对齐；注意通过增强被选中感觉表征的 γ 相干性来选择性"打开"前馈通信信道，同时 α/β 振荡介导自上而下的反馈/调控通信。

## 当前理解

我们现在认为，CTC 是目前将"神经振荡"与"注意选择"统一起来的最有影响力的理论框架之一，但其预测并未全部获得直接因果验证，属于"新兴"（emerging）阶段。

**核心主张**（Fries 2015, PMID:26447583）：

1. **γ（30–90 Hz）= 前馈/自下而上通信的载体**：
   - 感觉皮层向更高层区域发送信息时，以 γ 同步编码
   - γ 爆发以足够快的节律调制兴奋，使突触后神经元在抑制介入前能有效放电
   - 被注意刺激的神经表征 γ 更强 → 更有效驱动下游神经元 → 信息向上传递优先级高

2. **α/β（8–30 Hz）= 反馈/自上而下通信的载体**：
   - 高层区域（FEF、DLPFC）向低层区域发送调控/预测信号时，用 α/β 同步
   - α/β 产生周期性抑制，非目标区域 α 升高 = 前馈通道关闭

3. **注意的 CTC 机制**：
   - 注意选中刺激 A：A 的皮层表征 γ 同步增强 → 与下游神经元兴奋相对齐 → A 的信息有效上传
   - 刺激 B（竞争者）γ 弱 → 无法有效驱动下游 → B 的信息被"噪声淹没"
   - 结论：注意 = 通过选择性调制 γ 相干性，打开/关闭特定的前馈通信信道

4. **多节律协作**：
   - θ（7–8 Hz）：注意对空间的节律性扫描
   - γ（30–90 Hz）：前馈信号传输
   - α/β（8–30 Hz）：反馈/调控/抑制

## 关键机制：时序匹配

CTC 的核心是时序匹配问题。考虑 FEF→V4 连接（Gregoriou 2009）：

- FEF 以 γ 节律（例如 50 Hz）向 V4 发送动作电位
- 轴突传导时间（FEF→V4 约 5ms）+ 突触整合延迟（约 5–8ms）= 约 10–13ms
- 如果 FEF 的 γ 周期与 V4 的 γ 周期（20ms/周期）恰好错开这 10–13ms，则 FEF 的输出恰好在 V4 的**兴奋相**（γ 波谷，神经元接近阈值）到达
- 结果：FEF 的每一个突触前事件都以最大效率激活 V4 突触后神经元
- 实验确认（Gregoriou 2009）：FEF-V4 γ 耦合确实存在 8–13ms 时移，方向 FEF 先行

相反，如果竞争刺激 B 对应的 FEF 位点没有这种精确时移 γ 耦合，其信号到达 V4 时处于**抑制相**（γ 波峰），突触激活效率低 → 信息无法有效传递。

## 视觉层级的频段不对称（Bastos et al. 2015）

CTC 框架的视觉层级验证（PMID:25585017）：
- V1→V4 前馈连接：偏好 **γ 频段**（Bayesian DCM 统计显著）
- V4→V1 反馈连接：偏好 **α/β 频段**
- 这种不对称性在整个腹侧视觉流中广泛存在
- 与预测编码框架形成统一：γ 传递预测误差（感觉信号的新信息），α/β 传递预测（自上而下的期望）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 注意增强 FEF-V4 γ 相干，FEF 先行 8–13ms | 猕猴 FEF+V4 同步记录 | Gregoriou 2009, PMID:19478185 | 高 |
| V1→V4 前馈用 γ，V4→V1 反馈用 α/β | 猕猴 ECoG + 动态因果模型 | Bastos 2015, PMID:25585017 | 中-高 |
| V1 被注意刺激的 γ 驱动 V4 γ，被忽视刺激不能 | 猕猴 V1+V4 同步记录 | Bosman 2012（引用于 Fries 2015） | 中-高 |
| 感知整合时 γ **降低**（与 CTC 预测相反） | MEG+sEEG，人类感知整合任务 | Costa & Castelo-Branco 2024, PMID:39185735 | 中（需复制）|

## 连接

- [[gamma-oscillations]] — γ 振荡是 CTC 的前馈通信载体
- [[alpha-oscillations]] — α 振荡是 CTC 的反馈/抑制载体
- [[frontal-eye-fields]] — FEF-V4 γ 耦合是 CTC 在注意中的核心例证
- [[dorsal-attention-network]] — DAN 通过 CTC 机制调控感觉皮层
- [[biased-competition]] — CTC 提供了偏置竞争的振荡实现机制
- [[predictive-coding]] — CTC 与预测编码有结构对应（γ=预测误差上行，α/β=预测下行）
- [[ei-balance]] — γ 生成的 E/I 平衡状态决定 CTC 的通信效率

## 未解问题

- **Q-ctc-01**（高优先级）：CTC 预测 γ = 前馈，但多项研究（包括 Costa 2024）发现感知整合时 γ 降低，与框架相反。两类现象如何调和？CTC 是否只适用于特定类型的感知处理（如空间注意）而不适用于整合性感知？
- **Q-ctc-02**（中优先级）：能否直接通过因果干预测试 CTC 预测？例如：(a) 在 FEF-V4 连接上通过光遗传学打破 γ 相干，是否损伤注意表现？(b) 人工同步两区 γ 节律（如 tACS），是否增强感知？这些实验在技术上可行但尚未完成。

## 修订历史

- 2026-08-31 · 创建 · 基于《规则变感知》(#131)文章 · 来源：Fries 2015, Bastos 2015, Gregoriou 2009 · status=emerging（理论框架，非所有预测直接验证；存在反例 Costa 2024）· 初始置信度：中

## 来源文章

- [[2026-08-31-attention-frontoparietal-fef-alpha-gamma]]

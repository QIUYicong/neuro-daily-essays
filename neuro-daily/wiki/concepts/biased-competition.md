---
title: 偏置竞争模型
slug: biased-competition
domain: concepts
type: theory
status: mainstream
confidence: high
created: 2026-07-01
updated: 2026-08-31
revision_count: 2
dimensions: [cognition, whole-brain-network, brain-region, microcircuit]
related: [dorsal-attention-network, working-memory, v1-primary-visual-cortex, attentional-blink, global-workspace-theory, frontal-eye-fields, communication-through-coherence, alpha-oscillations, gamma-oscillations]
prerequisites: [dorsal-attention-network, v1-primary-visual-cortex]
opens_questions: [Q-ctc-01, Q-fef-02]
source_articles: [2026-07-01-dorsal-attention-network-FEF-IPS, 2026-08-31-attention-frontoparietal-fef-alpha-gamma]
key_sources: ["PMID:7605061", "PMID:11994752", "PMID:10376597", "PMID:19478185", "PMID:26447583"]
---

# 偏置竞争模型 (Biased Competition Model)

> **一句话定义**：多个视觉刺激在感觉皮层中竞争有限的神经表征资源；注意通过自上而下的偏置信号（来自 FEF/IPS）倾斜这场竞争，使目标刺激获得更强的皮层表征和处理优先权。

## 当前理解

偏置竞争模型由 Desimone 和 Duncan（1995, PMID:7605061）提出，是目前解释选择性视觉注意神经机制最有影响力的理论框架之一。

核心主张：
1. **竞争**：同时呈现在神经元感受野内的多个刺激会**相互抑制**对方的表征——当两个刺激同时出现时，神经元的响应低于单独呈现任一刺激时的响应
2. **偏置**：注意通过自上而下的偏置信号（来自前额叶、FEF、IPS）改变竞争的"起点"——被注意的刺激获得额外增益，从而在竞争中胜出
3. **分布式**：竞争在感觉处理的每一层级都发生（从 V1 到 IT），不局限于高级皮层

核心预测（均获实验支持）：
- 当两个刺激同时出现在同一感受野时，神经元响应 < 单独呈现任一刺激（相互抑制）
- 注意于其中一个刺激 → 该刺激"主导"感受野，响应接近单独呈现水平（偏置后的竞争胜出）
- 感受野越小、刺激间距越近，竞争越激烈

## 关键机制

偏置竞争中的"偏置信号"来自 FEF 和 IPS 构成的背侧注意网络（DAN），通过以下方式施加：

1. **皮层反馈增益调制**：FEF → V4 → V1 的反馈路径产生乘法增益，使被注意位置的所有神经元响应整体放大
2. **视丘门控**：FEF/IPS → TRN → 视丘核，调节感觉信号的丘脑传递效率
3. **局部抑制竞争**：在 V4、IT 等区域，被注意目标的活动通过侧抑制压制竞争者的表征

乘法增益（Treue & Martínez Trujillo 1999, PMID:10376597）是偏置竞争的核心调制形式：不改变神经元的偏好特性（调谐宽度不变），只整体放大响应强度。

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| 多刺激相互抑制（竞争存在） | 猕猴 V4/IT 双刺激 vs 单刺激比较 | 多个 Desimone 实验室研究 | 高 |
| 注意恢复竞争（偏置有效） | 猕猴单单元记录 + 注意任务 | Reynolds et al. 系列 | 高 |
| 偏置信号来自前额叶-顶叶 DAN | fMRI + 微电刺激（FEF） | Corbetta & Shulman 2002 | 高 |
| 乘法增益是偏置的计算形式 | 猕猴 MT 方向调谐曲线 | Treue & Trujillo 1999, PMID:10376597 | 高 |

## 振荡机制实现（新增 2026-08-31）

偏置竞争的神经振荡实现由两套互补机制组成（见 [[communication-through-coherence]]）：

**增强目标竞争者**（γ 路径）：
- FEF 通过 8–13ms 时移 γ 相干耦合驱动 V4 目标位置神经元（Gregoriou 2009, PMID:19478185）
- 目标神经元 γ 功率升高 → 能有效驱动更高层（IT 皮层）→ 竞争中"发声更响"

**压制非目标竞争者**（α 路径）：
- DAN 通过 IPS 调控竞争者对应枕叶区域 α 升高（主动脉冲抑制）
- 非目标区域神经元的兴奋窗口收窄 → 感觉输入无法有效引发响应 → 竞争中"发声被压制"

**净效果**：目标刺激 γ 强 + 竞争者 α 强 = 竞争高度不对称 → 目标表征主导感受野，接近单刺激响应水平

这解释了为什么偏置竞争的核心预测（注意将两刺激响应恢复至单刺激水平）能够实现：不只是目标被增强，竞争者也被主动压制。

## 连接

- [[dorsal-attention-network]] — DAN（FEF+IPS）是产生偏置信号的解剖实体
- [[frontal-eye-fields]] — FEF 是偏置竞争中最直接的前额叶执行器，因果控制 V4 增益
- [[communication-through-coherence]] — CTC 提供了偏置竞争的振荡实现机制（γ 打开目标信道，α 关闭竞争信道）
- [[alpha-oscillations]] — α 振荡是压制竞争者的脉冲抑制机制
- [[gamma-oscillations]] — γ 振荡是驱动目标感知表征的前馈通信载体
- [[working-memory]] — 工作记忆维持目标信息，提供持续的偏置信号来源
- [[v1-primary-visual-cortex]] — V1 是竞争发生的早期感觉皮层层级
- [[attentional-blink]] — 注意瞬盲是竞争资源（Stage 2 工作记忆巩固）被占用的表现
- [[global-workspace-theory]] — GWT 的"广播"可以理解为赢得偏置竞争后进入全局工作空间

## 未解问题

- Q-ctc-01：CTC 的 γ=前馈通信预测与感知整合时 γ 降低的反例如何调和？
- Q-fef-02：多目标注意时（≥2 个位置），偏置竞争是否能同时在多个位置运作？注意容量限制（~4 物体）的振荡机制来自哪一层级？

## 修订历史

- 2026-07-01 · 创建 · 基于《空间注意的神经回路》一文 · 来源：Desimone & Duncan 1995, Corbetta & Shulman 2002, Treue & Trujillo 1999 · 初始置信度：高
- 2026-08-31 · 修订 rev2 · 基于《规则变感知》(#131) · 新增：振荡机制实现节（γ 驱动目标 + α 压制竞争者的双向机制）；related 新增 frontal-eye-fields, communication-through-coherence, alpha-oscillations, gamma-oscillations；key_sources 新增 PMID:19478185, 26447583；opens_questions 新增 Q-ctc-01, Q-fef-02

## 来源文章

- [[2026-07-01-dorsal-attention-network-FEF-IPS]]
- [[2026-08-31-attention-frontoparietal-fef-alpha-gamma]]

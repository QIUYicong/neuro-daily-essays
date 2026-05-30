---
title: 恐惧消退
slug: fear-extinction
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-14
updated: 2026-06-14
revision_count: 1
dimensions: [synaptic, microcircuit, brain-region, behavior, cognition]
related: [fear-conditioning, basolateral-amygdala, prefrontal-cortex, hippocampal-circuit, ltp, ltd, memory-consolidation]
prerequisites: [fear-conditioning, basolateral-amygdala, prefrontal-cortex]
opens_questions: [Q-extinction-ltp-ltd, Q-itc-plasticity, Q-reconsolidation-clinical]
source_articles: [2026-06-14-amygdala-fear-circuit]
key_sources: ["PMID:32970967", "PMID:20303254", "PMID:32047613"]
---

# 恐惧消退 (Fear Extinction)

> **一句话定义**：恐惧消退是"CS → 不再有 US"的新联结学习，由边缘下皮层（IL-PFC）经嵌合细胞群（ITC）驱动，压制（而非删除）侧杏仁核中的原始恐惧 LTP——情境依赖性强，原始恐惧记忆始终保持完好。

## 当前理解

我们现在认为，**消退（Extinction）不是遗忘，不是 LTD 对 LTP 的逆转，而是一个独立的新学习过程**（Bouton et al., 2021）。

关键证据来自三个行为现象：
- **自发恢复（Spontaneous Recovery）**：消退后时间流逝，恐惧自动重现
- **续新（Renewal）**：在情境 A 获得恐惧，在情境 B 消退，回到情境 A 恐惧完全复发
- **重建（Reinstatement）**：消退后单独给 US，恐惧重现

这三个现象共同证明：**原始 LA-LTP 在消退后完好保存，消退创造了一个与之竞争的抑制性记忆**，其激活高度依赖情境（由海马提供）。

这一发现对临床极为重要：暴露疗法（Prolonged Exposure Therapy）的本质是在治疗室情境中进行消退训练，但患者回到日常环境（不同情境）后容易复发（Renewal），即使治疗成功。

## 关键机制

### 回路层：前额叶双模控制器

消退表达依赖**边缘下皮层（IL-PFC）**的激活：

**消退路径（IL-PFC → 门控关闭）**：
IL-PFC → 嵌合细胞群（ITC cells，GABAergic）→ 抑制 CeM 输出神经元 → 恐惧行为被压制

**恐惧表达路径（PL-PFC → 门控开放）**：
PL-PFC → 基底核（BA）→ CeM 激活 → 恐惧行为产生

这两条路径形成**解剖对立的双模控制器**（Sotres-Bayon & Quirk, 2010）：
- IL 损毁：不影响恐惧获得；削弱消退提取（已消退的恐惧更容易复发）
- PL 损毁：不影响恐惧获得；减弱恐惧表达

### 情境门控（海马参与）

腹侧海马（vHipp）→ mPFC 投射提供当前情境信息，决定是 IL 模式（消退情境）还是 PL 模式（危险情境）激活：
- 消退训练后，vHipp-mPFC 突触强度增加
- 在消退情境 = vHipp 激活 IL → ITC 压制 CeM → 无恐惧
- 在原始获得情境 = vHipp 信号改变 → PL 模式 → CeM 激活 → 恐惧复发（Renewal）

### 嵌合细胞群（ITC Cells）的关键角色

ITC cells = 散布在 BLA 与 CeA 之间的 GABAergic 小细胞群，是 IL-PFC 到 CeM 路径的中继站：
- 接受 IL-PFC 的兴奋性谷氨酸能输入
- 激活后释放 GABA 抑制 CeM 输出神经元
- ITC 损毁影响消退但不影响恐惧获得（因果证据）
- ITC 细胞是否通过 LTP 机制来固结消退记忆仍在研究中（Q-itc-plasticity）

### 消退的分子需求

与获得 LTP 类似，消退也需要：
- NMDA 受体激活（BLA 内 NMDA 阻断也阻断消退）
- IL-PFC 中的蛋白质合成（晚期消退巩固所需）
- BDNF-TrkB 信号参与 IL-PFC 可塑性

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 消退是新学习（自发恢复/续新/重建） | 多实验室行为实验 | PMID:32970967 (Bouton 2021) | 高 |
| IL-PFC 损毁削弱消退提取 | 离子通道素/利多卡因失活 + 恐惧测试 | PMID:20303254 (Sotres-Bayon 2010) | 高 |
| PL-PFC 驱动恐惧表达（损毁减弱恐惧） | 同上 | PMID:20303254 | 高 |
| ITC 损毁影响消退 | 局部毒素 + 消退行为测试 | PMID:20303254 | 中高 |
| BLA 内 NMDA 拮抗剂阻断消退获得 | 立体定向 AP5 注射 | PMID:32047613 (Sun 2020) | 中高 |
| 消退后恐惧记忆 LA-LTP 依然存在 | 续新/自发恢复实验设计 | PMID:32970967 | 高 |

## 连接

- [[fear-conditioning]] — 消退是恐惧条件反射的竞争性抑制（而非删除），原始 LA-LTP 保持完好
- [[basolateral-amygdala]] — ITC cells 是消退门控的关键 BLA 内结构
- [[prefrontal-cortex]] — IL-PFC（→ITC→CeM 消退驱动）vs PL-PFC（→BA→CeM 恐惧驱动）
- [[hippocampal-circuit]] — vHipp 提供情境信息，决定消退/恐惧状态切换
- [[ltp]] — 消退也需要 NMDA 受体（可能在 ITC 细胞或 IL-PFC）；与 LA-LTP 竞争而非逆转
- [[memory-consolidation]] — 消退记忆需要 IL-PFC 蛋白质合成巩固，与系统巩固过程类似

## 未解问题

- Q-extinction-ltp-ltd：消退后 LA 内是否有部分 AMPA 受体内吞（LTD 成分），或完全是新联结？
- Q-itc-plasticity：ITC 细胞接收 IL-PFC 输入的突触可塑性机制是什么？
- Q-reconsolidation-clinical：再巩固窗口（Reconsolidation window）在人类是否可靠地可利用于 PTSD 治疗？

## 修订历史

- 2026-06-14 · 创建 · 基于《杏仁核的恐惧算法》一文 · 初始置信度：高

## 来源文章

- [[2026-06-14-amygdala-fear-circuit]]

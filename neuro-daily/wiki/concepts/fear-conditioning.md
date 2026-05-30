---
title: 恐惧条件反射
slug: fear-conditioning
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-14
updated: 2026-06-14
revision_count: 1
dimensions: [molecular, synaptic, microcircuit, brain-region, behavior]
related: [basolateral-amygdala, ltp, nmda-receptor, ampa-receptor, camkii, engram-cells, fear-extinction, hebbian-learning, three-factor-learning-rule]
prerequisites: [ltp, nmda-receptor, basolateral-amygdala]
opens_questions: [Q-fear-temporal-gap]
source_articles: [2026-06-14-amygdala-fear-circuit]
key_sources: ["PMID:10845062", "PMID:9403688", "PMID:9403689", "PMID:10542437", "PMID:32047613"]
---

# 恐惧条件反射 (Pavlovian Fear Conditioning)

> **一句话定义**：巴甫洛夫恐惧条件反射是侧杏仁核（LA）中 NMDA 受体依赖的 LTP 过程——CS（音调等中性刺激）和 US（电击等伤害性刺激）的同时激活，通过突触可塑性将两者永久联结，使 CS 此后足以单独触发全套防御反应。

## 当前理解

我们现在认为，经典巴甫洛夫恐惧条件反射（Pavlovian Fear Conditioning）在分子层面是**侧杏仁核（LA）中的一次突触 LTP 事件**，使用与海马 LTP 几乎完全相同的 NMDA 受体-CaMKII-AMPA 受体轴。

**核心定义**：
- **CS（Conditioned Stimulus，条件刺激）**：训练前无特殊意义的中性刺激（音调、光、场所）
- **US（Unconditioned Stimulus，非条件刺激）**：固有引发防御反应的伤害性刺激（电击、捕食者气味）
- **CR（Conditioned Response，条件反应）**：CS 单独出现后引发的防御反应（冻结、惊跳增强、心率升高、HPA 激活）

该记忆的三个核心特征：
1. **极度样本高效**：1–5 次配对即可产生终身记忆（vs 海马空间记忆通常需要更多重复）
2. **不可删除性**：一旦形成，无法通过 LTD 反转，只能被新的"CS → 安全"联结（消退）竞争性压制
3. **泛化性**：与原始 CS 相似的刺激也会触发 CR（泛化），这是 PTSD 症状的机制基础

## 关键机制

### 分子层（LA 突触）

1. CS 激活 → LA 主细胞 AMPA 受体 → EPSP（弱去极化）
2. US 激活 → LA 主细胞强去极化（AMPA 电流 + 直接突触后兴奋）
3. CS + US 同时激活 → NMDA 受体 Mg²⁺ 解阻 → Ca²⁺ 内流
4. CaMKII 激活 → GluA1 Ser831 磷酸化 + AMPA 受体向突触插入
5. AMPA:NMDA 比值升高（= LTP 指纹）
6. 此后 CS 单独激活足以产生 LA 主细胞 AP → 下游恐惧反应

### 细胞层（去抑制窗口）

CS 诱发 PV+ 中间神经元激活 → PV 抑制 SST+ → 去抑制 LA 主细胞远端树突 → 提高 CS 输入整合能力（为 NMDA 受体 Mg²⁺ 解阻创造条件）

同时，US 激活下 PV 和 SST 均被抑制 → 主细胞强烈去极化 → NMDA 进一步开放

### 记忆分配（细胞竞争）

- 训练前 ~1 小时窗口内，BLA 主细胞之间存在 CREB 活性差异
- CREB 较高 → 兴奋性较高 → 更容易在 CS-US 配对时激活 → 更容易获得 LTP → 被纳入印迹
- 约 10%–20% 的 LA 主细胞最终成为恐惧记忆印迹的成员（见 [[engram-cells]]）

### 情感增强调制

强烈情绪应激 → LC 释放 NE → β-肾上腺素受体 → PKA → GluA1-Ser845 磷酸化 → 增强 AMPA 受体膜定位，增大 LTP 幅度。这是"情绪性闪光灯记忆"的分子基础：越强烈的情绪，越难忘。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| LA 损毁消除听觉恐惧 CR | 刻板损毁 + 冻结测试 | PMID:10845062 (LeDoux 2000) | 高 |
| 恐惧条件反射产生 LA-LTP（体内场电位） | 听觉诱发场电位记录，配对 vs 非配对对照 | PMID:9403688 (Rogan 1997) | 高 |
| 恐惧条件反射后 AMPA:NMDA 比值升高 | 离体全细胞膜片钳（MGN→LA 突触） | PMID:9403689 (McKernan 1997) | 高 |
| BLA 内注射 NMDA 拮抗剂 AP5 阻断获得（不影响表达） | 立体定向注射 + 行为测试 | PMID:10542437 (Maren 1999) | 高 |
| CREB 时序决定 LA 印迹分配（opto-DN-CREB） | 光遗传控制 CREB 时序 + 小鼠自由行为测试 | PMID:31837649 (Park 2020) | 中高 |

## 连接

- [[basolateral-amygdala]] — 恐惧条件反射发生的解剖位点（LA）
- [[ltp]] — 分子实现机制（NMDA-CaMKII-AMPA LTP）
- [[nmda-receptor]] — CS-US 巧合检测器
- [[engram-cells]] — CREB 竞争决定 LA 印迹细胞分配
- [[fear-extinction]] — 消退是恐惧条件反射的竞争性抑制，而非删除
- [[hebbian-learning]] — 巴甫洛夫条件反射是 Hebb 规则的经典行为表达
- [[three-factor-learning-rule]] — NE 作为第三因素增强 US 相关突触的 LTP 幅度
- [[memory-consolidation]] — 恐惧记忆获得后需要海马-杏仁核联合巩固（情境恐惧）

## 未解问题

- Q-fear-temporal-gap：标准 CS 时长 30 s，US 在末尾 0.5 s，LA 主细胞对 CS 适应在几百 ms 内；时序悖论如何被去抑制窗口或其他机制解决？

## 修订历史

- 2026-06-14 · 创建 · 基于《杏仁核的恐惧算法》一文 · 初始置信度：高

## 来源文章

- [[2026-06-14-amygdala-fear-circuit]]

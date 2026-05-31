---
title: 补体系统（中枢神经系统中的角色）
slug: complement-cns
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-31
updated: 2026-05-31
revision_count: 1
dimensions: [molecular, cellular, synaptic]
related: [synaptic-pruning, critical-period, microglia, alzheimers-disease, v1-primary-visual-cortex]
prerequisites: [synaptic-transmission]
opens_questions: [Q-cp-02]
source_articles: [2026-05-31-synaptic-pruning-critical-period]
key_sources: ["PMID:18083105", "PMID:22632727", "PMID:27033548"]
---

# 补体系统（中枢神经系统中的角色）(Complement System in CNS)

> **一句话定义**：免疫系统的经典补体级联（C1q→C3→C3b）在大脑发育期被征用为突触"标记-吞噬"系统：C1q 响应星形胶质细胞信号沉积在弱活动突触上，C3b 调理化后由小胶质细胞 CR3 受体识别并吞噬清除，这一机制在阿尔茨海默病中被异常重激活导致病理性突触丢失。

## 当前理解

我们现在认为，CNS 中的补体系统并非仅仅是外周免疫功能的"旁观者"，而是被神经系统主动整合为发育期突触精修剪的核心分子工具。这一认识改变了对神经系统"免疫特权"的理解：大脑不是简单地"屏蔽"免疫系统，而是选择性地**招募**特定免疫信号分子为神经发育服务。

**发育期正常功能**（Stevens 2007，Schafer 2012）：
- 出生后未成熟星形胶质细胞分泌信号（具体分子尚不完全清楚），诱导神经元表达 C1q
- C1q 精确沉积于突触，尤其是活动弱、竞争处于劣势的突触
- 经典补体级联激活：C1q → C1r/C1s → C4b2a（C3 转化酶）→ C3b
- C3b 共价与突触膜结合（opsonization）→ 小胶质细胞 CR3 受体识别 → 吞噬清除

**活动依赖的选择逻辑**：高活动的突触前神经元可能通过分泌某些因子（如 fractalkine/CX3CL1）或改变局部补体调节蛋白平衡，使 C3b 沉积效率降低，从而受到"保护"。低活动突触则 C3b 积累更多，被优先清除。

**疾病中的错误激活**（Hong 2016）：在阿尔茨海默病的早期阶段（淀粉样斑块出现之前），可溶性 Aβ 寡聚体上调 C1q 表达并促进 C1q 在成年突触上的沉积，导致本应已经完成的突触修剪机制被重新激活，在不该被删除的成年突触上执行吞噬清除。

## 关键机制

**三个关键蛋白**：
- **C1q**（150 kDa，六聚体）：经典补体级联的识别组件；在外周系统识别细菌表面或抗原-抗体复合物；在大脑发育中识别突触
- **C3b**：C3 裂解产物，通过硫酯键共价结合靶表面；稳定的 opsonin；被多种吞噬受体识别
- **CR3（CD11b-CD18，Mac-1）**：β₂ 整合素，小胶质细胞的主要 C3b 受体；活化后启动吞噬溶酶体通路

**补体调节蛋白**（控制补体不过度激活）：
- CD46、CD55、CD59：阻止补体在自身细胞表面过度激活
- Factor H：液相补体调节蛋白；靶标是自身组织；GWAS 研究发现 Factor H 基因变异与 AMD（年龄相关黄斑变性）和 AD 风险相关

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| C1q 沉积在发育期突触，响应星形胶质细胞信号 | C1q 免疫染色；共培养实验；C1q null 小鼠突触修剪失败 | PMID:18083105 (Stevens 2007) | 高 |
| C3b-CR3 机制介导活动依赖的小胶质细胞吞噬 | 视网膜-LGN 系统；CR3/C3 KO 表型；TTX/Forskolin 活动操控 | PMID:22632727 (Schafer 2012) | 高 |
| C1q 在 AD 中被重激活导致成年突触异常丢失 | AD 小鼠模型早期 C1q 上调；C1q KO 减轻突触损失和认知障碍 | PMID:27033548 (Hong 2016) | 高 |

## 连接

- [[synaptic-pruning]] — C1q/C3 是突触修剪的启动分子
- [[microglia]] — CR3 在小胶质细胞上，是吞噬的分子执行者
- [[critical-period]] — 补体修剪在关键期内最为活跃
- [[alzheimers-disease]] — 补体重激活是 AD 早期突触病理的关键机制

## 未解问题

- **Q-cp-02**：哪些分子信号使高活动突触抵抗 C3b 沉积？具体"保护突触"的正向信号是什么？
- 为什么成年大脑在 C1q 异常上调时，通常不激活的补体修剪路径会被重新触发？补体调节蛋白的老化失效？Aβ 的直接激活作用？

## 修订历史

- 2026-05-31 · 创建 · 基于《发育之剪》一文 · 初始置信度：高（多系统独立验证；补体修剪在发育和疾病中的证据链完整）

## 来源文章

- [[2026-05-31-synaptic-pruning-critical-period]]

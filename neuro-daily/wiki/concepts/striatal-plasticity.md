---
title: 纹状体突触可塑性
slug: striatal-plasticity
domain: concepts
type: mechanism
status: mainstream
confidence: high
created: 2026-09-01
updated: 2026-09-01
revision_count: 1
dimensions: [molecular, synaptic, microcircuit, behavior]
related: [medium-spiny-neuron, long-term-potentiation, ltd, endocannabinoid-system, dopamine-reward-prediction-error, striatal-direct-indirect-pathway, DARPP-32]
prerequisites: [medium-spiny-neuron, long-term-potentiation, ltd, action-potential]
opens_questions: [Q-striatal-ltp-ltd-behavior-link]
source_articles: [2026-09-01-medium-spiny-neurons-striatum]
key_sources: ["PMID:20096294", "PMID:21469956", "PMID:37841525"]
---

# 纹状体突触可塑性 (Striatal Synaptic Plasticity)

> **一句话定义**：纹状体（尤其是皮质-纹状体谷氨酸突触）的长时程增强（LTP）和长时程抑制（LTD），通过D1/D2受体介导的不同分子级联分别在直接和间接通路MSN中实现，是大脑将奖励历史编码为行为倾向的突触机制。

## 当前理解

我们现在认为，纹状体具有两种形式的长时程突触可塑性，分别在D1型和D2型MSN中优先发生，且方向相反：

**D1-MSN的LTP**：奖励时多巴胺D1受体激活→cAMP/PKA→DARPP-32磷酸化→AMPA受体突触插入增加。这与同时激活的谷氨酸（NMDA受体开放）协同，使刚刚被激活的皮质-纹状体突触得到长期强化。

**D2-MSN的eCB-LTD**：多巴胺D2受体激活（或奖励缺失时D2抑制解除）+谷氨酸mGluR1/5激活→内源大麻素（2-AG等）逆行释放→突触前CB1受体→谷氨酸释放概率持久下降。这种机制在**所有类型纹状体突触（谷氨酸+GABA）**中都存在。

关键时间约束：多巴胺信号在行为发生后约1秒内仍能有效触发LTP，这通过cAMP的持续时间自然实现（无需显式时间戳机制），是大脑解决"时间信用分配问题"的生物解法。

## 关键机制

### 纹状体LTP机制
1. **触发条件**：高频皮质输入 + D1受体激活（多巴胺存在）
2. **分子级联**：D1→Gs→AC→cAMP↑→PKA→DARPP-32（Thr34）磷酸化→PP1抑制→CaMKII激活
3. **突触后表达**：AMPA受体（GluA1亚基）磷酸化+突触后膜插入；棘头部变大（蘑菇型）
4. **NMDA受体的必要性**：NR1亚基敲除小鼠缺乏纹状体LTP和运动技能学习
5. **多巴胺的时间窗**：行动后≤1秒的多巴胺信号仍可触发LTP（信用分配解法）

### 纹状体eCB-LTD机制
1. **触发条件**：高频皮质输入（激活mGluR1/5）+ D2受体激活（或mGluR激活产生DAG→DGL→2-AG）
2. **内源大麻素生成**：突触后DAG脂酶（DGL-α）催化2-AG合成
3. **逆行信号**：2-AG从突触后扩散到突触前，激活CB1受体
4. **突触前表达**：突触前CB1激活→PKA↓→vesicle release probability↓（持久性）
5. **注意**：eCB-LTD可在无多巴胺的情况下由单纯mGluR激活诱发，但D2受体的同时激活会促进其发生

### 竞争与平衡
两种可塑性形式在同一纹状体区域共存，形成"奖励/惩罚"的双向记忆：
- 奖励（多巴胺增加）→ D1-LTP优先（该行动被强化）+ D2-LTD（竞争行动被抑制）
- 惩罚/奖励省略（多巴胺减少）→ D2-MSN D2受体抑制解除 → eCB-LTD可能减弱（间接通路恢复活力），抑制该行动

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| NMDA受体对纹状体LTP必需 | NR1亚基条件性敲除小鼠 | PMID:20096294 (PMC2849868) | 高 |
| DARPP-32磷酸化是LTP必需步骤 | DARPP-32敲除小鼠缺乏LTP | PMID:20096294 (PMC2849868) | 高 |
| eCB-LTD经CB1受体突触前机制实现 | CB1受体敲除/拮抗剂实验 | PMID:20096294 (PMC2849868) | 高 |
| 多巴胺1秒时间窗仍可触发LTP | 急性切片+体内实验 | PMID:37841525 (PMC10572094) | 中 |

## 连接

- [[medium-spiny-neuron]] — LTP/LTD发生在MSN的树突棘
- [[long-term-potentiation]] — 纹状体LTP与海马LTP机制相似（NMDA/AMPA），但依赖D1而非单纯突触活动
- [[ltd]] — 纹状体eCB-LTD与小脑LTD（平行纤维-浦肯野细胞）机制不同，但同属逆行信使介导
- [[endocannabinoid-system]] — eCB是纹状体LTD的主要逆行信使
- [[dopamine-reward-prediction-error]] — 多巴胺RPE是触发D1-LTP的教学信号

## 未解问题

- Q-striatal-ltp-ltd-behavior-link：特定突触的LTP/LTD与特定习惯行为的因果关系在细胞分辨率上尚未完全建立

## 修订历史

- 2026-09-01 · 创建 · 基于《纹状体的决策细胞》文章 · 初始置信度：高（机制）/ 中（时间窗的人类推广）

## 来源文章

- [[2026-09-01-medium-spiny-neurons-striatum]]

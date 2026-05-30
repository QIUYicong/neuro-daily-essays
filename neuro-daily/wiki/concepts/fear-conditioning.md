---
title: 恐惧条件反射
slug: fear-conditioning
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-05-30
updated: 2026-05-30
revision_count: 1
dimensions: [molecular, cellular, microcircuit, brain-region, behavior]
related: [amygdala, fear-extinction, ltp, nmda-receptor, camkii, ampa-receptor, engram-cells, hebbian-learning]
prerequisites: [ltp, nmda-receptor, amygdala]
opens_questions: [Q-fear-low-road-function, Q-fear-human-amygdala-specificity]
source_articles: [2026-05-30-amygdala-fear-memory]
key_sources: ["PMID:11584069", "PMID:24896183", "PMID:24908482", "PMID:30415278"]
---

# 恐惧条件反射 (Fear Conditioning)

> **一句话定义**：将中性条件刺激（CS，如音调）与厌恶非条件刺激（US，如电击）配对，通过外侧杏仁核（LA）突触LTP，使CS单独即可触发完整防御反应（冻结、应激激素释放）的巴甫洛夫联想记忆过程。

## 当前理解

我们现在认为，恐惧条件反射是LA中一次Hebbian-LTP事件的直接结果：US引发的强去极化移除NMDA受体的Mg²⁺阻塞，同时CS到来提供谷氨酸配体，Ca²⁺内流激活CaMKII→AMPA受体插入，CS传入突触永久增强。这与海马LTP使用完全相同的分子机器，证明LTP是跨脑区的通用联想学习算法。

记忆写入后，条件性CS通过LA→CeA（含ITC去抑制回路）→PAG/下丘脑驱动冻结和应激激素释放。只有约20%的LA锥体神经元形成增强的CS响应（稀疏代码），这些神经元因具有更高内在兴奋性或CREB水平而被竞争性选中——与海马场所细胞印迹的选择逻辑完全一致。

## 关键机制

### 双路CS输入与巧合检测
- **低路（Low Road）**：听觉丘脑（MGm/PIN）→ LA，~12ms，粗糙但迅速
- **高路（High Road）**：听觉丘脑 → 听觉皮层 → LA，~40ms，精细表征
- 两路CS信号汇聚于LA同一批神经元；US从躯体感觉丘脑到达同一神经元
- US强去极化 → Mg²⁺解封 → NMDA受体允许Ca²⁺内流（巧合检测）

### 分子级联
1. **NMDA受体**：CS提供谷氨酸配体，US提供去极化 → Ca²⁺内流（门卫）
2. **L型钙通道**：反向传播动作电位（bAP）激活树突L型VGCCs，提供第二条Ca²⁺入路（对L-LTP固结重要）
3. **CaMKII**：T286自磷酸化 → GluA1-Ser831磷酸化 → AMPA受体突触膜插入
4. **GluA1特异性增加**：GluA1（非GluA2/3）在LA突触条件反射后特异性增加

### 稀疏编码与竞争
- 条件反射后约20% LA主神经元发展CS响应（其余被抑制或中性）
- 高兴奋性/高CREB细胞优先被招募（竞争选择）
- 与海马场所细胞/印迹细胞的稀疏逻辑一致（稳定性-效率权衡）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| LA内注射NMDA拮抗剂APV阻断恐惧获得 | 体内药理学注射+行为测试 | PMID:11584069 | 高 |
| LA-LTP是恐惧记忆因果底物（LTP→恐惧；LTD→消除） | 光遗传LTP/LTD操控LA突触 | PMID:24896183 | 极高（双向因果） |
| GluA1特异性上调，CaMKII激活 | 体内免疫印迹+行为范式 | PMID:30415278 (PMC6374177) | 高 |
| 约20% LA神经元发展CS响应 | 多通道电极记录 | PMID:24908482 (PMC4103014) | 高 |
| 丘脑输入1次训练后增强，皮层输入6次后增强 | 体外切片LTP测量 | PMID:23864645 (PMC3718199) | 中 |

## 连接

- [[amygdala]] — 恐惧条件反射的解剖基础（LA, ITC, CeA）
- [[fear-extinction]] — 与恐惧条件反射竞争的消退记忆
- [[ltp]] — 恐惧条件反射的分子底物；NMDA→CaMKII→AMPA插入与海马LTP相同
- [[nmda-receptor]] — 巧合检测器，恐惧LA-LTP的必要门卫
- [[camkii]] — 恐惧LTP分子级联的核心激酶
- [[engram-cells]] — LA中约20%稀疏恐惧印迹细胞，与海马印迹逻辑一致
- [[norepinephrine-locus-coeruleus]] — NE通过β受体增强杏仁核LTP，强化情绪记忆巩固

## 未解问题

- Q-fear-low-road-function（中优先级）：丘脑低路直接投射的独立学习贡献
- Q-fear-human-amygdala-specificity（高优先级）：人类LA架构与啮齿类的保守程度

## 修订历史

- 2026-05-30 · 创建 · 基于《当杏仁核学会恐惧》一文 · 初始置信度：高

## 来源文章

- [[2026-05-30-amygdala-fear-memory]]

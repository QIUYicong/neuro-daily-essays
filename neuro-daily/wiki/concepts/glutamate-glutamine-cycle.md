---
title: 谷氨酸-谷氨酰胺循环
slug: glutamate-glutamine-cycle
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-02
updated: 2026-07-02
revision_count: 1
dimensions: [molecular, cellular, synaptic]
related: [astrocyte, synaptic-transmission, ltp, nmda-receptor, alzheimers-disease]
prerequisites: [astrocyte, synaptic-transmission]
opens_questions: []
source_articles: [2026-07-02-astrocyte-tripartite-synapse]
key_sources: ["PMID:16025096"]
---

# 谷氨酸-谷氨酰胺循环 (Glutamate-Glutamine Cycle)

> **一句话定义**：神经元-星形胶质细胞间的谷氨酸回收再生循环：突触释放的谷氨酸由星形胶质细胞摄取后转化为谷氨酰胺，再回送神经元重新合成谷氨酸，既防止兴奋性毒性又维持突触递质池——这是谷氨酸能突触功能不可或缺的代谢基础。

## 当前理解

我们现在认为，谷氨酸能突触的可持续工作依赖于神经元和星形胶质细胞之间的代谢协作循环。突触释放的谷氨酸不能由神经元自身完全降解和再利用，需要借道星形胶质细胞完成再生：

**循环步骤**：
1. 突触前末梢释放谷氨酸进入突触间隙
2. EAAT2（GLT-1）和 EAAT1（GLAST）由星形胶质细胞 PAPs 高效摄取（约 80% 的突触释放谷氨酸由此清除）
3. 星形胶质细胞内，谷氨酰胺合酶（GS）消耗一个 ATP 将谷氨酸转化为谷氨酰胺
4. 谷氨酰胺通过中性氨基酸转运体（SNAT3/5）输出至细胞外，被神经元摄取
5. 神经元中，谷氨酰胺酶（PAG）将谷氨酰胺水解为谷氨酸，装入突触囊泡，准备下一轮释放

**功能双重性**：
- **安全功能**：快速清除突触间隙谷氨酸，防止兴奋性毒性（excitotoxicity）。GLT-1 敲除小鼠出现自发性癫痫和神经元死亡，证明清除功能的必要性。
- **维持功能**：谷氨酸不能从突触前神经元中从头合成（神经元缺乏 GS），必须依赖星形胶质细胞提供谷氨酰胺前体。无此循环，谷氨酸能突触的递质池将被耗竭。

## 关键机制

```
突触前末梢
   释放谷氨酸（Glu）
       ↓ (EAAT2/GLT-1)
星形胶质细胞
   Glu + NH₃ + ATP → 谷氨酰胺（Gln）+ ADP + Pi  [谷氨酰胺合酶]
   Gln 输出 ↓ (SNAT3/5)
细胞外
   Gln 被神经元摄取 ↓ (SNAT1/2)
突触前末梢
   Gln → Glu  [谷氨酰胺酶 PAG]
   Glu 重新装入囊泡
```

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 星形胶质细胞清除 ~80% 突触释放谷氨酸 | 放射性标记摄取实验；EAAT2 KO | PMID:16025096 | 高 |
| GLT-1 敲除导致癫痫和神经元死亡 | GLT-1 KO 小鼠 | 多项研究 | 高（多次重复）|
| 谷氨酰胺循环是神经元谷氨酸池的主要再生途径 | ¹³C NMR 代谢示踪 | 多项研究 | 高 |

## 连接

- [[astrocyte]] — 循环的代谢核心；承担谷氨酸摄取和谷氨酰胺合成
- [[synaptic-transmission]] — 循环维持谷氨酸递质池的可持续性
- [[ltp]] — 突触功能的代谢基础；谷氨酸清除也保证了突触间隙信号的时序精确性

## 修订历史

- 2026-07-02 · 创建 · 基于《大脑的第三方》(#68) · 初始置信度：高（多重独立验证的经典代谢机制）

## 来源文章

- [[2026-07-02-astrocyte-tripartite-synapse]]

---
title: FKBP51（糖皮质激素受体伴侣蛋白）
slug: fkbp51
domain: concepts
type: mechanism
status: mainstream
confidence: medium
created: 2026-08-27
updated: 2026-08-27
revision_count: 1
dimensions: [molecular, cellular, disease]
related: [glucocorticoid-stress-memory, hpa-axis, adult-neurogenesis, sgk3-autophagic-nsc-death, ptsd]
prerequisites: [glucocorticoid-stress-memory, hpa-axis]
opens_questions: [Q-fkbp51-01, Q-fkbp51-02]
source_articles: [2026-08-27-stress-hippocampal-neurogenesis-hpa-gc]
key_sources: ["PMID:36104438", "PMID:34589890"]
---

# FKBP51（糖皮质激素受体伴侣蛋白）(FKBP51 / FK506-Binding Protein 51)

> **一句话定义**：FKBP51（由 *FKBP5* 基因编码）是糖皮质激素受体（GR）-HSP90 伴侣复合体的成分，通过降低 GR 对糖皮质激素的配体亲和力并阻碍 GR 核转位，调节细胞对 HPA 轴信号的敏感度；*FKBP5* 基因多态性（如 rs1360780）被大量人类研究关联到 PTSD 易感性、HPA 轴反应过激和抑郁症风险，是"分子缓冲器"与"遗传脆弱性因子"的双重角色。

## 当前理解

我们现在认为：FKBP51 是糖皮质激素信号传导中的一个关键"分子减速器"——当它与 GR 结合时，降低 GR 对皮质醇/皮质酮的亲和力并阻碍 GR 的核转位，从而减少 GC 信号的细胞内效应（PMID:36104438）。

这套机制有重要的**负反馈设计**：GR 激活 → GRE 上 *FKBP5* 基因转录增加 → FKBP51 蛋白增加 → FKBP51 与 GR 结合 → GR 灵敏度降低 → 形成对 GC 信号的超短自适应反馈环。在健康应激反应中，这一环路保证了 HPA 轴激活的自限性。

当 *FKBP5* 基因存在特定多态性（低甲基化版本，如 rs1360780 T 等位基因）时，FKBP51 对 GC 刺激的诱导更为强烈，形成更强的 GR 抑制 → HPA 轴负反馈效率低 → 皮质醇水平在应激后恢复更慢 → 持续激活 HPA。这与 PTSD 中观察到的 HPA 轴失调高度一致，也是 PTSD 患者中 *FKBP5* 多态性频率升高的分子解释。

FKBP51 的另一个效应是调节海马神经发生：通过影响 GR 的活性程度，*FKBP5* 基因型间接决定了 NSC 上 GR 激活水平，进而影响 SGK3 路径、BDNF 表达等 AHN 调节机制。选择性 FKBP51 抑制剂（SAFit2）在体外直接促进 NSC 增殖和分化（PMID:36104438），提示 FKBP51 抑制是一个潜在的神经发生促进和应激弹性靶点。

## 关键机制

### GR-FKBP51 互动模型

```
应激 → CORT 升高
  ↓
CORT + GR（胞浆，与 HSP90/FKBP51 结合）
  ↓
FKBP51 降低 GR-CORT 亲和力（EC₅₀↑）
  + 阻碍 GR 二聚化和核转位
  ↓
较少 GR 进入细胞核
  ↓
较少 GRE 转录激活（包括较少 BDNF 抑制，较少 SGK3 激活）
  ↓
（GR 激活仍触发 FKBP5 转录 → 负反馈环）
```

与 FKBP52（另一 GR 伴侣）的对比：FKBP52 具有**促进** GR 活性的效果（增加 GR-CORT 亲和力），而 FKBP51 具有**抑制** GR 活性的效果，二者相互竞争结合 HSP90-GR 复合物，共同决定细胞的 GC 敏感性。

### FKBP5 基因多态性的表观遗传调节

*FKBP5* 的 rs1360780 多态性（T→C）：
- T 等位基因：增强 FKBP5 对 GC 的转录响应性 → FKBP51 诱导更强 → GR 更难激活 → 应激后 CORT 更难恢复基线
- 早期创伤 × T 等位基因 × 成年 PTSD 的三重交互（基因-环境交互，Binder et al. 2008）是目前 PTSD 分子机制中人类证据最强的发现之一

表观遗传机制：童年创伤可导致 *FKBP5* 内含子区域的 CpG 位点去甲基化 → 这些位点是 GRE 功能位点 → 去甲基化使 GR 与该位点的结合更高效 → FKBP5 转录进一步增强 → FKBP51 蛋白进一步增加 → GR 更难激活 → HPA 负反馈更差（表观遗传锁定的应激超敏感回路）。

### FKBP51 抑制剂 SAFit2

SAFit2 是选择性 FKBP51 抑制剂（阻断 FKBP51 与 GR-HSP90 复合物的结合），在体外促进海马 NPC 增殖（BrdU+↑）和分化（TuJ1+/β-III-tubulin+↑），效果超过外源 BDNF（100 nM 浓度）；在体内产生慢性社会失败应激（CSDS）后的应激弹性行为，但体内 BrdU 标记的细胞数目差异未达显著性——提示 SAFit2 的行为效应可能并不完全通过神经发生介导（PMID:36104438）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| FKBP51 降低 GR 对 GC 的亲和力并阻碍核转位 | GR 配体结合实验 + 核转位荧光显微镜 | PMID:36104438（综述部分） | 高（体外，经典机制） |
| *FKBP5* rs1360780 T 等位基因 × 童年创伤 → 成年 PTSD 风险↑ | 多中心 GWAS 关联研究 + 三重交互分析 | Binder et al. 2008 | 高（人类，多个队列） |
| SAFit2 促进 NPC 增殖和分化（体外） | BrdU / TuJ1 标记 + SAFit2 处理 | PMID:36104438（PMC9763121） | 中（体外，小鼠 NPC） |
| SAFit2 在体内减少应激后社会回避（CSDS） | 社会互动测试 + 开野 | PMID:36104438 | 中（小鼠，需更多剂量/模型验证） |
| *FKBP5* 内含子 CpG 去甲基化 × 早期创伤 → HPA 轴超敏感 | 焦磷酸测序 + HPA 反应性测量 | Klengel et al. 2013 | 中-高（人类 + 小鼠） |

## 连接

- [[glucocorticoid-stress-memory]] — FKBP51 通过调节 GR 灵敏度，影响 GC 对记忆巩固和 BDNF 抑制的效率
- [[hpa-axis]] — *FKBP5* 多态性决定 HPA 轴负反馈效率；FKBP51 是 GR 负反馈环的分子缓冲器
- [[adult-neurogenesis]] — FKBP51 的 GR 灵敏度调节间接影响神经发生；SAFit2 直接促进 NPC 增殖
- [[sgk3-autophagic-nsc-death]] — FKBP51 决定 GR 激活程度，从而决定 SGK3 路径的激活阈值
- [[ptsd]] — *FKBP5* rs1360780 × 童年创伤 × 成年 PTSD 是目前 PTSD 分子遗传中人类证据最强的三重交互之一

## 未解问题

- Q-fkbp51-01（高优先级）：SAFit2 的体外促神经发生效应为何未在体内显著复现？是药代动力学问题、血脑屏障穿透率问题，还是体内 NSC 微环境的复杂性问题？
- Q-fkbp51-02（中优先级）：FKBP51 抑制剂是否可以通过提升 GR 灵敏度（反而促进 HPA 负反馈效率）来发挥应激弹性效果，而不仅仅通过 HSP90/Akt 的非 GR 路径？两种机制的相对贡献？

## 修订历史

- 2026-08-27 · 创建 · 基于《应激如何重塑海马新生神经元》一文 (#125) · 初始置信度：中（SAFit2 在体内证据不足；FKBP5 人类遗传关联高但神经发生连接需更多证据）

## 来源文章

- [[2026-08-27-stress-hippocampal-neurogenesis-hpa-gc]]

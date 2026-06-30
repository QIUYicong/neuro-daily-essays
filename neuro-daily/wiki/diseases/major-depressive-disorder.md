---
title: 重度抑郁症（MDD）
slug: major-depressive-disorder
domain: diseases
type: disease
status: established
confidence: high
created: 2026-10-21
updated: 2026-10-21
revision_count: 1
dimensions: [molecular, synaptic, cellular, brain-region, whole-brain-network, behavior, cognition, disease]
related: [lateral-habenula, bdnf, nmda-receptor, ampa-receptor, prefrontal-cortex, hpa-axis, hippocampal-neurogenesis, serotonin-raphe-system, dopamine-reward-prediction-error, default-mode-network, mtor, excitotoxicity]
prerequisites: [synaptic-transmission, bdnf, nmda-receptor, dopamine-reward-prediction-error]
opens_questions: [Q-mdd-01, Q-mdd-02, Q-mdd-03, Q-ketamine-01, Q-hnk-01]
source_articles: [2026-10-21-depression-ketamine-rapid-antidepressant]
key_sources: ["PMID:20724638", "PMID:21677641", "PMID:23042884", "PMID:27144355", "PMID:30894661", "PMID:38177353", "PMID:39207462"]
---

# 重度抑郁症 (Major Depressive Disorder, MDD)

> **一句话定义**：重度抑郁症是一种以持续情绪低落、快感缺失和认知损害为核心症状的精神疾病，其神经基础是多层级的突触结构缺损——从前额叶皮层突触密度的实际减少，到外侧缰核的病理性爆发放电——而非单纯的神经递质失衡；氯胺酮通过在数小时内重建突触、快速逆转这些病理变化，彻底改变了我们对"抗抑郁作用机制"的理解。

## 当前理解

抑郁症的主流理解经历了三次范式转变：

**单胺假说（1960年代）**：血清素、多巴胺、去甲肾上腺素不足导致抑郁，SSRI 等药物通过增加单胺水平起效。这一模型在解释 SSRIs 起效慢（2-4 周）和 30% 患者无效时陷入困境。

**神经营养假说（2000年代）**：BDNF 表达下降是抑郁的重要生物标志；运动、抗抑郁药和电休克治疗均上调 BDNF。但这一假说的因果方向未定（BDNF 是原因还是结果？）。

**突触缺损假说（2010年代至今）**：Duman & Aghajanian 2012（PMID:23042884）综合了多线证据，确立了 MDD 的结构基础——**突触密度的实际减少**。关键证据：
- 人类死后脑组织电镜显示 MDD 患者 dlPFC 突触数量减少
- 神经影像学发现 mPFC 灰质体积缩小（结构 MRI）
- CUS（慢性不可预测应激）动物模型 mPFC 第 V 层锥体神经元顶端树突缩短、棘密度降低

这一范式将 MDD 从"神经递质失衡"重新定义为**有形态基础的突触损伤病**，并为氯胺酮的快速突触重建机制提供了理论框架。

## 关键机制

### 一、突触缺损的上游驱动链

```
慢性应激/糖皮质激素长期升高
    ↓
BDNF 合成减少（VGF、Arc 等营养相关基因↓）
mTOR 信号通路受抑（突触蛋白合成减少）
    ↓
mPFC 第 V 层锥体神经元
  · 顶端树突缩短
  · 树突棘（尤其蘑菇形棘）密度降低
  · 突触数量减少（电镜可见）
    ↓
mPFC→奖励/情绪回路的前向调控减弱
→ 快感缺失、情绪调节失败、认知执行功能受损
```

### 二、外侧缰核的病理放电

在抑郁症动物模型中，慢性应激使 LHb 神经元陷入**病理性同步爆发放电**（burst firing），其具体特征是方波型/抛物线型/三角波型高频爆发。这种爆发通过 LHb→RMTg→VTA 回路主动抑制多巴胺输出，通过 LHb→DRN 抑制血清素，构成奖励/动机系统的持续性压制，直接对应快感缺失（anhedonia）症状。

### 三、快速抗抑郁机制的三条分子路径

氯胺酮（0.5 mg/kg 亚麻醉剂量）在数小时内产生抗抑郁效果，涉及三条平行机制：

**路径 A：mTOR 突触生成（2-24 小时窗口）**
```
氯胺酮 → NMDA 阻断 → 解除 GABA 中间神经元上 NMDA 受体激活 
    → 突触后谷氨酸/AMPA 激增（爆发性去抑制）
    → PI3K/Akt → mTOR 激活
    → PSD-95、GluR1、突触素 I、Arc 突触蛋白合成上调
    → mPFC 第 V 层蘑菇形树突棘数量在 2 小时内增加
    → rapamycin 局部注射可完全阻断此效果及行为改善
```
Li et al. 2010（PMID:20724638）通过双光子活体成像和 rapamycin 因果验证确立此路径。

**路径 B：eEF2K-BDNF 脱抑制（30 分钟窗口）**
```
静息态 NMDA 受体持续低水平激活（自发突触活动驱动）
    → 维持 eEF2K（真核延伸因子 2 激酶）活性
    → eEF2 磷酸化 → BDNF mRNA 翻译延伸受阻
    → 静息态 BDNF 蛋白水平低

氯胺酮阻断静息态 NMDA 受体
    → eEF2K 活性↓ → p-eEF2↓
    → BDNF mRNA 翻译去抑制
    → 30 分钟内海马 BDNF 蛋白↑
    → rapamycin 不阻断此 30 分钟行为效果
```
Autry et al. 2011（PMID:21677641）通过 eEF2K 抑制剂表型复制和 rapamycin 分离实验确立此路径。

**路径 C：HNK 代谢产物的 AMPA 增强（独立于 NMDA 阻断）**
```
氯胺酮 → 体内代谢 → (2R,6R)-羟基去甲氯胺酮 (HNK)
    → HNK 不与 NMDA 受体竞争结合（不阻断 NMDA）
    → 增强 AMPA 受体介导的 EPSP
    → GluA1/GluA2 突触膜水平升高
    → p-eEF2↓、BDNF↑（但不激活 mTOR）
    → NBQX（AMPA 受体阻断剂）可消除 HNK 的抗抑郁效果
```
Zanos et al. 2016（PMID:27144355）发现 HNK 的 NMDA 非依赖性抗抑郁机制，质疑了"NMDA 阻断是唯一机制"的假设。

### 四、GluA1 突触插入：所有快速抗抑郁药的收敛终点

Duman RS 2019（PMID:30894661）对比了氯胺酮、东莨菪碱（scopolamine）、HNK 三类结构完全不同的快速抗抑郁药，发现三个不变量：
1. **AMPA 受体依赖性**：NBQX 均消除抗抑郁效果
2. **BDNF 活动依赖性释放**：Val66Met 多态性（损害 BDNF 活动依赖分泌）携带小鼠中三者均失效
3. **mTOR 依赖性**：mTOR 激活均可检测

SSRI 与快速抗抑郁药的核心区别在于：SSRI 通过增加突触间隙血清素**间接**上调 BDNF 合成（需 2-4 周），而快速抗抑郁药直接触发 BDNF **活动依赖性分泌**（秒-分钟级），绕过了耗时的基因转录合成步骤。

**SST 中间神经元的关键作用**：mPFC 中的生长抑素（SST）中间神经元上 GluN2B-NMDA 受体是氯胺酮作用的关键靶点之一——阻断这些中间神经元上的 NMDA 受体，解除对第 V 层锥体神经元的 GABA 抑制，触发谷氨酸爆发，激活 mTOR 通路。

### 五、元可塑性框架：如何延长疗效

Brown KA et al. 2024（PMID:38177353）提出元可塑性（metaplasticity）框架：
- 快速抗抑郁药通过降低后续 LTP 的诱导阈值，使情绪回路更易进入增强状态
- AMPAR trafficking、BDNF-TrkB-mTORC1 信号和 CREB 转录是关键持续机制
- mGluR2/3 拮抗剂与 HNK 联用可增强 LTP 持续时间
- 这为理解重复氯胺酮给药的方案设计提供了理论基础

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| MDD 患者 dlPFC 突触数量减少 | 死后脑组织电镜突触计数 | PMID:23042884 | 中（人类死后，样本量有限） |
| 氯胺酮 2 小时内增加 mPFC 树突棘密度 | CUS 小鼠 + 双光子活体成像 + rapamycin 因果验证 | PMID:20724638 | 高（多模态验证） |
| 30 分钟内 BDNF↑通过 eEF2K 脱抑制 | eEF2K 抑制剂表型复制；eEF2 磷酸化测量 | PMID:21677641 | 高（小鼠，多方法） |
| HNK 不阻断 NMDA 但有抗抑郁效果 | 受体竞争结合 + NBQX 消除 | PMID:27144355 | 高（小鼠，多角度） |
| 三类快速抗抑郁药均依赖 AMPA 受体 | Val66Met KI 小鼠 + NBQX + mTOR 抑制 | PMID:30894661 | 高（跨化合物收敛） |
| 氯胺酮阻断 LHb 爆发放电 | 小鼠 CUMS 模型电生理 | PMID:41872515 | 中高 |
| 艾氯胺酮（intranasal）TRD 获 FDA 批准 | III 期 RCT（TRANSFORM-2 等）| PMID:42065202 | 高（人类临床） |

## 连接

- [[lateral-habenula]] — LHb 病理性爆发放电驱动奖励系统抑制；氯胺酮的快速抗抑郁作用部分通过阻断 LHb 爆发实现
- [[bdnf]] — BDNF 减少是 MDD 突触缺损的核心中间步骤；eEF2K-BDNF 路径是快速抗抑郁的 30 分钟机制
- [[nmda-receptor]] — 静息态 NMDA 活动主动压制 BDNF 翻译；氯胺酮通过阻断 NMDA 受体启动抗抑郁级联
- [[ampa-receptor]] — GluA1 突触插入是所有已知快速抗抑郁药的收敛效应终点
- [[prefrontal-cortex]] — mPFC 第 V 层锥体神经元突触缺损是 MDD 的结构核心；mTOR 突触重建靶向此区域
- [[hpa-axis]] — HPA 轴持续激活（皮质醇升高）是 MDD 突触损伤的上游驱动
- [[hippocampal-neurogenesis]] — BDNF 驱动的成体神经发生在 MDD 中受损；抗抑郁药物通过恢复神经发生产生部分效果
- [[serotonin-raphe-system]] — LHb→DRN 投射抑制血清素；SSRI 的治疗靶点
- [[dopamine-reward-prediction-error]] — LHb→RMTg→VTA 回路；快感缺失的多巴胺基础
- [[mtor]] — mTOR 是路径 A（氯胺酮→突触生成）的核心激酶节点；rapamycin 阻断可消除氯胺酮抗抑郁效果

## 未解问题

- Q-mdd-01（高优先级）：MDD 突触缺损是否有分子分型——哪些患者主要是 mTOR 路径受损，哪些主要是 eEF2K-BDNF 路径受损？这种分型能否预测氯胺酮响应性？
- Q-mdd-02（高优先级）：Val66Met 多态性（损害 BDNF 活动依赖性分泌）是否真正预测人类 TRD 对氯胺酮的响应？现有人类基因型-响应研究结果不一致。
- Q-mdd-03（中优先级）：反复氯胺酮给药的长期安全性——突触可塑性是否存在饱和风险？成瘾风险与 NMDA 阻断的解离剂效应如何权衡？
- Q-ketamine-01（高优先级）：氯胺酮的三条路径（NMDA→mTOR、eEF2K→BDNF、HNK→AMPA）在人类 TRD 中各贡献多少？现有机制证据几乎完全来自小鼠，转化可信度待提升。
- Q-hnk-01（中优先级）：体内 HNK 的峰值浓度是否足以达到实验中的有效浓度阈值？HNK I 期临床（截至 2025）结果如何？

## 修订历史

- 2026-10-21 · 创建 · 基于《氯胺酮与快速抗抑郁机制》(#189) · 初始置信度：高（机制）/中（人类转化）

## 来源文章

- [[2026-10-21-depression-ketamine-rapid-antidepressant]]

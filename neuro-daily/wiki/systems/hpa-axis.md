---
title: HPA 轴（下丘脑-垂体-肾上腺轴）
slug: hpa-axis
domain: systems
type: system
status: established
confidence: high
created: 2026-07-09
updated: 2026-07-09
revision_count: 1
dimensions: [molecular, cellular, brain-region, whole-brain-network, behavior, cognition, disease]
related: [glucocorticoid-stress-memory, amygdala, hippocampal-circuit, norepinephrine-locus-coeruleus, fear-conditioning, memory-consolidation, circadian-clock, alzheimers-disease, bdnf]
prerequisites: [synaptic-transmission, amygdala]
opens_questions: [Q-gc-01, Q-gc-02]
source_articles: [2026-07-09-glucocorticoids-stress-memory-amygdala]
key_sources: ["PMID:29428549", "PMID:9807058", "PMID:30877244", "PMID:23968228"]
---

# HPA 轴（下丘脑-垂体-肾上腺轴）

> **一句话定义**：HPA 轴是大脑对应激的主要内分泌应答系统，通过 PVN-CRH → 垂体-ACTH → 肾上腺皮质-皮质醇的级联，在 5-30 分钟内将神经性应激信号转化为循环糖皮质激素，既驱动全身适应性应激反应，又通过对杏仁核、海马和前额叶皮层的直接作用调控情绪性记忆的优先编码与长期存储。

## 当前理解

HPA 轴是进化上高度保守的神经内分泌系统，同时具有三种时间尺度的作用：
1. **即时（分钟级）**：皮质醇穿越血脑屏障，激活高亲和力 MR，快速调整神经元兴奋性和行为准备度
2. **慢速（小时级）**：皮质醇激活低亲和力 GR，驱动基因组途径（转录→蛋白质合成），促进记忆巩固
3. **长期（日-月级）**：慢性 HPA 激活改变 MR/GR 比值和海马结构，累积性损伤神经可塑性

HPA 轴不是单向的"下命令"系统，而是包含多层负反馈的平衡回路：皮质醇自身通过 GR（高密度分布于海马、PFC、PVN）抑制 CRH 和 ACTH 的进一步分泌。这一负反馈机制保证了 HPA 轴的自限性——正常个体在应激结束后 2-3 小时内，皮质醇恢复基线。

## 关键机制

### 级联解剖

```
应激输入
  ↓ 感觉皮层 → 杏仁核（BLA/CeA）→ BNST
  ↓ 或：前额叶皮层 → PVN（抑制性调控）
下丘脑室旁核（PVN）
  → CRH（促肾上腺皮质激素释放激素）
  → 垂体门脉系统（30-90 秒）
垂体前叶（促肾上腺皮质细胞）
  → ACTH（促肾上腺皮质激素）
  → 体循环（2-5 分钟）
肾上腺皮质（束状带）
  → 皮质醇（人类）/ 皮质酮（啮齿类）
  → 体循环峰值（15-30 分钟后）
  → 穿越血脑屏障（脂溶性，自由扩散）
  → 全脑 MR/GR 激活
```

### 负反馈系统

皮质醇通过三个水平的负反馈关闭 HPA 轴：
- **快速负反馈**（分钟级，非基因组）：皮质醇通过膜型受体快速抑制垂体 ACTH 分泌
- **中速负反馈**（小时级，基因组）：GR 激活 PVN 和垂体内的抑制基因
- **慢速负反馈**（天-周级）：海马 GR 激活后产生 CRH 基因下调的持续性抑制

**海马作为负反馈制动器**：海马（CA1/CA3/DG 均有高密度 GR）激活后抑制 PVN 的 CRH 释放。这创造了一个重要的反向关系：海马损伤（慢性应激所致）→ 负反馈减弱 → HPA 轴更难关闭 → 更多皮质醇 → 进一步海马损伤（正反馈恶性循环）。

### MR/GR 双受体分工

| 特征 | MR（盐皮质激素受体） | GR（糖皮质激素受体） |
|------|--------------------|--------------------|
| 亲和力 | 高（EC₅₀ ~0.5 nM） | 低（EC₅₀ ~5 nM） |
| 激活时机 | 基础皮质醇水平即激活 | 仅应激峰值皮质醇激活 |
| 主要分布 | 海马（CA1/CA2/DG）、杏仁核 | 全脑广泛，海马和PFC密度最高 |
| 功能 | 情境评估、探索反应、情绪稳定性 | 记忆巩固、代谢调控、HPA 反馈 |
| 慢性过激活后果 | MR 下调→情绪不稳定 | GR 下调→HPA 负反馈失调 |

### CRH 在杏仁核的独立作用

除了 HPA 轴的外周效应，CRH 作为神经肽直接在**中央杏仁核（CeA）**内起作用：
- CeA 含有高密度 CRH 神经元和 CRH₁R 受体
- BLA 激活 → CeA CRH 释放 → CRH₁R 激活 → 防御行为（冻结、逃跑）增强
- 这是**独立于 HPA 轴外周效应**的中枢机制——肾上腺切除动物仍有 CRH-CeA 介导的应激行为
- 慢性 CRH₁R 过激活是焦虑障碍（PTSD、广泛性焦虑）的候选发生机制

### 昼夜节律对 HPA 轴的门控

HPA 轴的基础活动受昼夜节律严格控制：
- SCN → AVP 投射 → PVN CRH 神经元（晨起前显著抑制→晨起后释放皮质醇峰值）
- 人类皮质醇在清醒后 30 分钟达峰（皮质醇觉醒反应，CAR）
- 皮质醇晨峰是 MR 完全激活、大脑进入高效注意力/学习状态的内分泌开关
- 睡眠剥夺和昼夜节律紊乱→CAR 变钝→记忆巩固效率降低

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| MR/GR 亲和力分离及时序功能 | 选择性 MR/GR 配体给药 + 行为范式（多系列实验） | PMID:29428549（综述） | 高 |
| GC 记忆增强通过 BLA GR 介导 | BLA 内 GR 拮抗剂（RU486）注射 + 记忆测试 | PMID:30877244；PMID:23968228 | 高 |
| 海马是 HPA 轴负反馈的关键节点 | 海马损毁→HPA 基础活性↑+应激反应时间延长 | PMID:9807058（综述） | 高（多项实验） |
| 慢性 GC → 海马萎缩 → HPA 负反馈进一步削弱 | 慢性应激 + 皮质醇测量 + 海马体积 MRI | PMID:9807058；PMID:9405958 | 高 |
| CRH 在 CeA 独立于 HPA 轴驱动防御行为 | 肾上腺切除动物 + CRH₁R 拮抗剂注射 + 行为 | 见 amygdala.md | 高（啮齿类） |

## 连接

- [[glucocorticoid-stress-memory]] — HPA 轴产生的 GC 是应激记忆调控的主要内分泌信使
- [[amygdala]] — BLA 是 GC 记忆效应的核心枢纽；CeA CRH 神经元是 HPA 轴的中枢独立效应器；BLA→PVN 投射调控 HPA 激活
- [[hippocampal-circuit]] — 海马（CA1/DG）是 HPA 轴负反馈的主要制动节点；慢性 GC 造成 CA3 萎缩削弱此制动功能
- [[norepinephrine-locus-coeruleus]] — SAM 轴（快速，秒级）和 HPA 轴（慢速，分钟级）协同在 BLA 产生记忆增强效果；NE 是 GC 效应的必要协同因子
- [[circadian-clock]] — SCN 门控 HPA 轴基础节律；皮质醇晨峰由 AVP/CRH 的昼夜节律振荡产生
- [[fear-conditioning]] — HPA 轴激活是恐惧条件反射记忆形成的内分泌背景；GC 增强 LA LTP
- [[memory-consolidation]] — GC 通过 GR 基因组路径是情绪显著性记忆巩固的关键内分泌信号
- [[alzheimers-disease]] — 慢性 HPA 激活（海马负反馈受损 → 皮质醇升高）是 AD 风险因素；GC 促进 APP 加工和 Aβ 生成

## 未解问题

- Q-gc-01：GR 拮抗剂在创伤记忆再巩固窗口的临床有效性（见 glucocorticoid-stress-memory）
- Q-gc-02：慢性应激 → CA3 萎缩 → AD 风险的因果链强度

## 修订历史

- 2026-07-09 · 创建 · 基于《记忆为什么最牢记住恐惧》一文 (#77) · 初始置信度：高

## 来源文章

- [[2026-07-09-glucocorticoids-stress-memory-amygdala]]

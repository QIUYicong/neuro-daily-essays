---
title: 颞顶联合区
slug: tpj-temporoparietal-junction
domain: systems
type: region
status: mainstream
confidence: medium
created: 2026-07-25
updated: 2026-07-25
revision_count: 1
dimensions: [brain-region, whole-brain-network, cognition]
related: [theory-of-mind, mentalizing-network, dorsal-attention-network, alpha-oscillations, default-mode-network]
prerequisites: [action-potential, synaptic-transmission]
opens_questions: [Q-tom-01]
source_articles: [2026-07-25-social-brain-mirror-neurons-theory-of-mind]
key_sources: ["PMID:12948738", "PMID:24012000", "PMID:16701204", "PMID:41245222"]
---

# 颞顶联合区 (Temporo-Parietal Junction, TPJ)

> **一句话定义**：颞顶联合区是颞叶、顶叶和枕叶交界处的一块皮层区域，是心智化（推断他人信念、意图）和注意重定向（被意外刺激打断时）两个功能系统的共同节点。

## 当前理解

我们现在认为，TPJ至少参与两个功能上有部分重叠的系统：

1. **心智化系统**（mentalizing）：推断他人心理状态（信念、意图、欲望）。右侧TPJ-M是最关键的节点——Saxe & Kanwisher（2003，PMID:12948738）首次确认其在推断他人心理内容时特异性激活。
2. **腹侧注意网络**（ventral attention network）：在意外或行为相关的刺激出现时，触发注意重定向（打断当前注意焦点）。

这两种功能共享同一解剖位置在某种程度上是合理的：**"注意到与预期不符的他人行为"**正是启动深度心智化推断的时刻——预测违背触发注意，注意触发信念更新，两者在神经底层共享预测误差信号。

**关键细分（右侧TPJ-M vs TPJ-p/TPJ-a）**：
- **右侧TPJ-M**（Saxe定义）：位于颞上沟/角回交界，专用于心理状态内容的推断
- 双侧TPJ的腹侧部分（TPJ-a）：更多参与注意重定向和感觉突显检测

## 关键机制

### 信念归因（Belief Attribution）

TPJ在以下条件下激活：
1. 阅读关于他人信念/意图/欲望的故事
2. 推断他人在特定情境中的想法（即便从未见过该情境）
3. **错误信念任务**（false belief）：推断他人持有与现实不符的错误信念
4. 视角采纳（perspective-taking）：从他人视角描述同一场景

不激活于：物理描述故事、非人类物体故事、纯粹的感觉运动任务。

### 因果性证据（TMS研究）

**经颅磁刺激（TMS）抑制右侧TPJ**：
- **损害**：基于他人信念的道德判断（"尝试伤害但偶然未成功"的判断）
- **不损害**：基于行为结果的道德判断（"意外造成伤害"的判断）

这一双重解离证明TPJ不只是被动激活，而是**因果性地参与**了信念推断，且其参与对基于信念（而非结果）的判断是特异性必要的。

### 预测编码框架中的TPJ（Koster-Hale & Saxe 2013，PMID:24012000）

TPJ在分钟尺度上对他人信念/意图进行预测：
- 他人行为**可预测**时：TPJ激活减弱（预测误差低 → 预测编码中的"期望抑制"）
- 他人行为**出乎意料**时：TPJ激活增强（预测误差高 → 需要更新对他人的心理模型）

这与其他皮层区域的预测编码特征一致，提示TPJ参与的社会推断与其他领域共享相同的计算原理。

## 解剖学特征

- **位置**：颞上回（STG）后部与顶下小叶（inferior parietal lobule）交界处；颞中回（MTG）与角回（angular gyrus）也有贡献
- **双侧存在**：左右TPJ均激活，但**右侧**在心智化任务中更为关键
- **相邻区域**：
  - 前方：初级体感皮层
  - 下方：颞上沟（pSTS，生物运动感知）
  - 内侧：后扣带回/楔前叶（PCu/PCC，自我参照）
  - 外侧：角回（语言、数字认知、注意）
- **与DMN的关系**：右侧TPJ与mPFC、楔前叶的功能连接（在静息态和ToM任务中）构成心智化网络的骨架

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| TPJ-M专门响应他人心理状态推断（非物体/非物理描述） | fMRI + 多控制条件，双重解离（EBA vs TPJ-M） | PMID:12948738（Saxe 2003） | 高（10+实验室重复） |
| TMS抑制右侧TPJ选择性损害信念-道德判断 | TMS + 道德判断任务，双重解离 | 后续TMS研究（PMID:17714666综述引用） | 中-高（因果性，部分实验室重复）|
| TPJ在108项社交互动fMRI研究中跨范式收敛激活 | ALE元分析（108项研究，双侧TPJ均列入） | PMID:41245222（Merchant 2025，PMCID PMC12617318） | 高（大样本元分析） |
| 他人行为可预测性降低时TPJ激活增强（预测误差信号特征） | fMRI + 可预测性操纵 | PMID:24012000（Koster-Hale & Saxe 2013，PMCID PMC4041537） | 中（直接测试有限） |

## 连接

- [[theory-of-mind]] — TPJ是ToM的中心节点；信念归因的专用区域
- [[mentalizing-network]] — TPJ是心智化网络中处于TPJ节点位置的关键区域
- [[dorsal-attention-network]] — TPJ（腹侧注意网络节点）与背侧注意网络（IPS/FEF）交互，共同管理注意的主动与被动切换
- [[alpha-oscillations]] — α振荡参与TPJ的注意抑制/释放（腹侧注意网络的α功率调节）
- [[default-mode-network]] — 右侧TPJ与mPFC、楔前叶构成DMN的社会认知子网络

## 未解问题

- Q-tom-01（高优先级）：TPJ在ToM中的具体计算角色——注意重定向、信念归因、还是预测误差信号？双重功能（注意/心智化）如何在同一解剖区域共存？亚区域功能分化是否存在？

## 修订历史

- 2026-07-25 · 创建 · 基于《大脑如何读懂另一颗大脑》（#93）· 整合Saxe 2003、Koster-Hale & Saxe 2013、Merchant 2025、Frith & Frith 2007 · 初始置信度：中（功能定位高度一致；具体计算机制争议仍存）

## 来源文章

- [[2026-07-25-social-brain-mirror-neurons-theory-of-mind]]

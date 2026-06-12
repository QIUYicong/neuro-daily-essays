---
title: 颞下皮层
slug: inferior-temporal-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-08-16
updated: 2026-10-05
revision_count: 2
dimensions: [brain-region, whole-brain-network, cognition]
related: [v4-visual-area, v1-primary-visual-cortex, face-patch-system, invariant-object-recognition, prefrontal-cortex, amygdala, entorhinal-cortex, dorsal-visual-stream, area-MT-V5, binocular-rivalry, neural-correlates-of-consciousness]
prerequisites: [v1-primary-visual-cortex, v4-visual-area, action-potential]
opens_questions: [Q-it-01, Q-it-02, Q-it-03]
source_articles: [2026-08-16-inferotemporal-cortex-ventral-stream-object-recognition, 2026-10-05-binocular-rivalry-consciousness-mechanism]
key_sources: ["PMID:30059648", "PMID:21051642", "PMID:22836252", "PMID:9096407", "PMID:2772635"]
---

# 颞下皮层 (Inferior Temporal Cortex, IT)

> **一句话定义**：颞下皮层是腹侧视觉流（V1→V2→V4→IT）的最高级视觉区域，通过稀疏的群体编码实现对物体身份的不变量表征，无论物体的位置、大小、旋转或光照如何变化。

## 当前理解

我们现在认为，IT 皮层沿后前轴分为多个功能阶段（PIT→CIT→AIT→AMIT），每个阶段的神经元感受野覆盖更大的视野范围，对刺激位置的敏感性更低（Conway 2018, PMID:30059648）。IT 神经元的核心计算特性是**不变量物体表征**：同一物体在不同视角、大小、位置、光照下，激活高度相似的神经元群体响应模式，使物体身份得以识别（Rust & DiCarlo 2012, PMID:22836252）。

IT 皮层的组织原则基于偏心率（eccentricity）模板：中央凹表征区对应面孔/精细物体识别，中间偏心率区对应颜色/行为相关性处理，周边区对应场景/背景处理。这不是随机排列，而是从早期视觉皮层继承的偏心率结构在 IT 层次的延续。

关于"模块论"与"分布论"的争论：两种描述在不同分析尺度上都是正确的。在单神经元和面孔块（face patches）尺度，存在明确的功能专门化（如面孔块）；在整个颞叶的多体素模式分析（MVPA）尺度，物体信息是分布式的——去除面孔最优区（FFA）后，仍可从其余区域解码面孔类别（Haxby et al. 2001, PMID:11577229）。

## 关键机制

### 选择性与不变性的平衡（核心计算原则）

从 V4 到 IT，神经元同时增加两种属性：
- **选择性（selectivity）**：对更复杂特征组合（and-like 操作）有要求，响应更"挑剔"
- **不变性（tolerance）**：对同一物体的更多变换版本（or-like 操作）保持响应

关键发现：两者精确平衡，维持约 **10% 的稀疏激活率**（V4: ~11%，IT: ~9.4%，无显著差异）不变（Rust & DiCarlo 2012）。这可能代表信息效率与能量消耗之间的最优权衡。

### IT 皮层的偏心率组织框架

每个 IT 阶段包含三类平行表征流：
1. **中央凹表征** → 面孔识别、精细物体（高空间频率）
2. **中间偏心率** → 颜色信号（行为相关性：成熟度、危险）
3. **周边表征** → 场景/地点识别（低空间频率，大尺度布局）

### 面孔块系统（IT 专门化的典型示例）

猕猴 IT 皮层中有 **6 个面孔块**（PL、ML、MF、AF、AL、AM），形成从视角特异到视角不变的层级（详见 [[face-patch-system]]）。

### 稀疏群体编码

任意物体激活约 1-2% 的 IT 神经元组合；极端熟悉的概念（如特定名人）在下游（海马/内嗅皮层）可能激活极少数"概念细胞"（Quiroga et al. 2005, PMID:15973409）。无"祖母神经元"意义上的单神经元编码，但高度稀疏的群体编码可达到类似效果。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| IT 沿后前轴分阶段，每阶段有偏心率组织 | 解剖+fMRI 定位+电生理 | PMID:30059648 | 中-高 |
| 选择性与不变性同时增加，稀疏度守恒（~10%） | 自然图像单元记录，V4 vs IT 定量比较 | PMID:22836252 | 高 |
| 面孔块从视角特异（ML/MF）→视角不变（AM） | fMRI 定位 + 清醒猕猴单神经元记录 | PMID:21051642 | 高 |
| 分布式编码：去 FFA 仍可解码面孔类别 | 人类 fMRI + 多体素模式分析（MVPA） | PMID:11577229 | 高 |
| IT 响应可被无监督 DNN 高质量预测 | 神经拟合度（neural predictivity）定量比较 | PMID:33431673 | 中 |

## 连接

- [[v4-visual-area]] — IT 皮层的直接输入来源；V4 提供形状/颜色/深度的中级特征
- [[v1-primary-visual-cortex]] — 腹侧流的起点；V1 方向边缘特征层级处理的基础
- [[face-patch-system]] — IT 内的面孔处理专门化子系统（详细层级描述）
- [[invariant-object-recognition]] — IT 皮层实现不变量识别的计算概念
- [[prefrontal-cortex]] — IT 输出到 PFC；PFC↔IT 反馈调制注意力和工作记忆中的物体表征
- [[amygdala]] — IT 面孔块输出 → 杏仁核（面孔的情绪价值；社会危险信号）
- [[entorhinal-cortex]] — IT 输出 → 内嗅皮层 → 海马（物体与情境记忆的绑定）

## 未解问题

- Q-it-01：腹侧流/IT 是否真正计算全局物体形状，还是只计算局部纹理统计？
- Q-it-02：反馈连接在日常物体识别中的定量贡献是多少？
- Q-it-03：人类 IT 皮层面孔识别与猕猴面孔块的精确对应关系是什么？

## 修订历史

- 2026-10-05 · 修订 rev2 · 基于《感知的最小战场：双眼竞争》(#165) · 新增"双眼竞争中的感知忠实度梯度"：IT 皮层几乎所有神经元跟随感知而非物理刺激（Sheinberg & Logothetis 1997, PMID:9096407）；related 新增 binocular-rivalry, neural-correlates-of-consciousness；key_sources 新增 PMID:9096407, PMID:2772635
- 2026-08-16 · 创建 · 基于《从线条到身份：腹侧视觉流如何解决不变量物体识别的核心难题》 · 初始置信度：高（IT 的总体组织和功能为 established；具体颜色功能假说为 emerging）

## 来源文章

- [[2026-08-16-inferotemporal-cortex-ventral-stream-object-recognition]]
- [[2026-10-05-binocular-rivalry-consciousness-mechanism]]

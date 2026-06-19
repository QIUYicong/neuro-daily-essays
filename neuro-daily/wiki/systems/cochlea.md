---
title: 耳蜗
slug: cochlea
domain: systems
type: structure
status: established
confidence: high
created: 2026-07-28
updated: 2026-07-28
revision_count: 1
dimensions: [molecular, cellular, brain-region]
related: [auditory-cortex, tonotopic-map, voltage-gated-calcium-channels]
prerequisites: [voltage-gated-calcium-channels]
opens_questions: []
source_articles: [2026-07-28-auditory-cortex-tonotopy]
key_sources: ["PMID:11427697"]
---

# 耳蜗 (Cochlea)

> **一句话定义**：耳蜗是内耳中充满淋巴液的蜗旋管，通过基底膜的物理行波将声音频率映射为空间位置（地点编码），并通过内/外毛细胞将机械振动转化为神经电信号；外毛细胞的 Prestin 电动蛋白提供主动放大（耳蜗放大器），使灵敏度提高 40–50 dB，频率分辨率提升约 100 倍。

## 当前理解

耳蜗是听觉系统的外周频率分析仪，在神经信号处理开始之前完成声音频率的物理分解。

**基底膜（BM）地点编码**（Robles & Ruggero 2001，PMID:11427697）：
- 基底膜展开约 35 mm，弹性渐变：基部（stapes 端）窄/硬 → 高频（~20 kHz）；顶部（apex）宽/软 → 低频（~20 Hz）
- 声波经卵圆窗传入 → BM 产生行波（traveling wave）→ 行波在特征频率（CF）位置振幅最大后迅速消散
- 这一 CF-位置对应关系（cochleotopic map）是贯穿整个听觉通路拓扑地图的物理起点

**耳蜗放大器**：
- **外毛细胞（OHC）**：~12,000 个，侧膜富含 **Prestin** 电动蛋白，跨膜电压变化 → 细胞快速伸缩（~100 kHz 响应频率）→ 主动放大 BM 振动
- 效果：低声压下增益 40–50 dB；CF 调谐 Q 因子提高 ~100 倍
- 非线性：低强度→高增益（锐利调谐）；高强度→增益压缩（保护作用）— 称为"CF特异性压缩性非线性"
- OHC 损伤 → 频率分辨率严重下降（感音性听力损失的主要机制）

**内毛细胞（IHC）与机械-电换能（MET）**：
- ~3,500 个 IHC，接收 ~95% 听觉传入神经纤维
- 顶端静纤毛偏转 → 尖端连接（tip links，cadherin-23/protocadherin-15） 拉开 **TMC1/TMC2** 机械电换能通道 → K⁺/Ca²⁺ 内流 → 去极化
- 去极化 → 基底外侧 L 型 Ca²⁺ 通道（Ca_v1.3）→ 谷氨酸释放至突触带（ribbon synapse）→ I 型螺旋神经节细胞激活
- 突触带（ribbon synapse）：IHC 独特结构，支持持续、高速率谷氨酸释放，与中枢神经系统突触的囊泡释放池机制类似但进化独立

## 关键机制

**地点编码的物理实现**：BM 弹性梯度 → 行波 → CF 位置振幅最大，是频率→空间变换的物理基础。von Békésy（1961 Nobel Lecture）用力学模型首次证实行波，Robles & Ruggero（2001）用激光测振计提供现代定量证据。

**耳蜗放大器的主动回路**：IHC MET → 毛束偏转 → OHC 去极化 → Prestin 收缩/伸长 → BM 振动增强 → 反馈至 IHC — 这是一个局部正反馈回路（必须被精确调控以防振荡）

**听耳声发射（OAEs）**：OHC 主动放大的副产品可被逆向传入外耳道，作为耳蜗功能的临床无创检测指标

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 基底膜行波的频率-位置对应 | 激光测振计体内测量 | PMID:11427697 | 高 |
| Prestin是外毛细胞电动马达 | Prestin KO小鼠→失去非线性/放大 | Dallos 2008 Curr Opin Neurobiol | 高 |
| TMC1/TMC2是MET通道 | KO小鼠→失去机械电换能 | Kawashima 2011 Neuron | 高 |
| OHC损伤→频率分辨率下降 | 氨基糖苷类毒素选择性损伤OHC | 多项研究 | 高 |

## 连接

- [[tonotopic-map]] — 耳蜗 cochleotopic map 是 A1 tonotopic map 的物理起点（mechanism-of）
- [[auditory-cortex]] — 耳蜗经 CN→SOC→IC→MGB 的升序通路投射至 A1（prerequisite-for）
- [[voltage-gated-calcium-channels]] — IHC 基底外侧 Ca_v1.3 （L型）是谷氨酸释放的触发器；与海马/皮层 L 型钙通道作用类比但细胞类型不同

## 未解问题

（暂无高优先级未解问题；耳蜗机制总体高度确立）

## 修订历史

- 2026-07-28 · 创建 · 基于《从蜗旋到皮层音图》（#96）· 初始置信度：高

## 来源文章

- [[2026-07-28-auditory-cortex-tonotopy]]

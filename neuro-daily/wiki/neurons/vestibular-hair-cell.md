---
title: 前庭毛细胞
slug: vestibular-hair-cell
domain: neurons
type: entity
status: established
confidence: high
created: 2026-07-31
updated: 2026-07-31
revision_count: 1
dimensions: [molecular, cellular]
related: [vestibular-system, mechanoreceptor-ltmr, action-potential, voltage-gated-calcium-channels]
prerequisites: [action-potential, voltage-gated-calcium-channels]
opens_questions: []
source_articles: [2026-07-31-vestibular-system-vor-efference-copy]
key_sources: ["PMID:25074487", "PMID:34617206", "PMID:30617060"]
---

# 前庭毛细胞 (Vestibular Hair Cell)

> **一句话定义**：内耳前庭感觉器官中的机械感受器细胞，通过顶端静纤毛阵列和顶端连接（CDH23-PCDH15）将物理运动（内淋巴液流动/耳石膜滑动）转化为 TMC1/TMC2 通道的离子电流，在亚毫秒内完成从机械力到神经信号的转换。

## 当前理解

我们现在认为，前庭毛细胞是自然界最高灵敏度的机械传感器之一，其传导速度（亚毫秒）和灵敏度（皮米级位移）远超任何工程传感器。毛细胞顶端的**静纤毛阵列（stereocilia bundle）**按高度排列成梯形，最高处为一根动纤毛（kinocilium）。相邻静纤毛间由**顶端连接（tip link）**——CDH23（上端）和 PCDH15（下端）构成的蛋白质细线——相连。

机械传导通道（MET channel）现在被认为是以 TMC1 和 TMC2 为核心组分的跨膜蛋白复合体（PMID:25074487; PMID:34617206）。完整的传导复合体含至少十余种蛋白，包括 LHFPL5（稳定 PCDH15 与 TMC 的连接）、TMIE（调节通道功能）、CIB2/3（Ca²⁺ 调节）。

前庭毛细胞分两型：
- **I 型（Type I）**：梨形，被杯状突触末梢（calyx ending）完全包裹；对应不规律放电（irregular firing）传入神经，高增益，对快速运动瞬态敏感
- **II 型（Type II）**：圆柱形，接受多个点状突触；对应规律放电（regular firing）传入神经，低噪声，编码持续性运动信号

底部的**带状突触（ribbon synapse）**是毛细胞输出的特殊结构：突触带（synaptic ribbon）将大量谷氨酸囊泡锚定在活动区（active zone），实现持续、快速的神经递质释放，与普通骨骼肌运动终板相比有完全不同的动力学特性。

## 关键机制

### 机械传导步骤

1. 头部运动 → 内淋巴液流动/耳石膜滑动
2. 毛细胞束向高纤毛方向偏转 → 顶端连接拉伸 → 张力增加
3. TMC1/TMC2 通道门控开放 → K⁺（主要）和 Ca²⁺ 内流（内淋巴液富含 K⁺，Nernst 电位驱动力大）
4. 毛细胞去极化 → 基底部 L 型电压门控 Ca²⁺ 通道（CaV1.3）开放
5. Ca²⁺ 触发带状突触囊泡融合 → 谷氨酸释放
6. 谷氨酸激活突触后的前庭神经节（Scarpa's ganglion）树突
7. 动作电位沿前庭神经（VIII 颅神经的前庭支）传向脑干

向低纤毛方向偏转 → 顶端连接松弛 → TMC 通道关闭 → 超极化 → 谷氨酸释放减少 → 传入神经放电减少（静止自发放电 ~100 spk/s）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| TMC1/2 KO 消除毛细胞 MET 电流 | 小鼠基因敲除 + 膜片钳电生理 | PMID:25074487 | 高 |
| CDH23-PCDH15 构成顶端连接 | 冷冻电镜结构 + Usher 综合征遗传学 | PMID:30617060 | 高 |
| 传导复合体含十余种蛋白 | 蛋白质互作 + KO 表型分析 | PMID:34617206 | 高（分子层面确认） |
| I 型毛细胞对应不规律神经，II 型对应规律神经 | 单细胞形态电生理对照 | PMID:31789675 | 高 |

## 连接

- [[vestibular-system]] — 前庭毛细胞是前庭感受器系统的核心细胞单元
- [[mechanoreceptor-ltmr]] — 同为机械传导感觉神经元；LTMR（皮肤触觉）和毛细胞（内耳）使用不同的分子机器但相同的物理原理
- [[action-potential]] — 毛细胞突触后的传入神经产生动作电位，传递前庭信号
- [[voltage-gated-calcium-channels]] — CaV1.3 是带状突触释放的关键 Ca²⁺ 门控通道

## 修订历史

- 2026-07-31 · 创建 · 基于《平衡的物理学》（#99）· 初始置信度：高

## 来源文章

- [[2026-07-31-vestibular-system-vor-efference-copy]]

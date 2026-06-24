---
title: 特征注意
slug: feature-based-attention
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-13
updated: 2026-09-13
revision_count: 1
dimensions: [brain-region, cognition, whole-brain-network]
related: [biased-competition, dorsal-attention-network, frontal-eye-field, v1-primary-visual-cortex, divisive-normalization, spatial-attention, working-memory]
prerequisites: [biased-competition, dorsal-attention-network]
opens_questions: [Q-fba-01, Q-fba-02]
source_articles: [2026-09-13-fef-attention-oscillatory-feedback-biased-competition]
key_sources: ["PMID:31844117", "PMID:20303256", "PMC6915702"]
---

# 特征注意 (Feature-Based Attention)

> **一句话定义**：特征注意是一种基于目标特征（颜色、方向、空间频率等）而非空间位置的选择机制，由腹侧弓前区（VPA，FEF 腹侧）控制，通过向 V4 等视觉区传递特征特异性偏置信号，在整个视野范围内（而非只在注意位置）增强与目标特征匹配的神经元响应。

## 当前理解

我们现在认为，特征注意（Feature-Based Attention）与空间注意（Spatial Attention）由前额皮层中**解剖上分离的子区域**分别控制，但两者都通过偏置视觉皮层中的竞争来实现选择（Bichot et al. 2019, PMID:31844117）。

**空间注意** vs **特征注意**的关键区别：
- 空间注意：增强特定**位置**的所有神经元（视野中某个位置的所有特征）
- 特征注意：增强编码特定**特征**（如红色）的神经元，不论刺激在哪个位置

**前额控制节点分离**（Bichot et al. 2019, PNAS）：
- **FEF（额眼区，背侧弓前区）**：空间注意的主要前额来源
- **VPA（腹侧弓前区）**：特征注意的关键前额来源，FEF 的腹侧邻居

实验证据：单侧 VPA 失活（muscimol）使猕猴对侧 V4 神经元完全失去对注意特征的优先响应，但同一组神经元的空间注意调制（注意位置 vs 非注意位置的增益差异）完全保留。行为上，视觉搜索受损而简单检测正常。

## 关键机制

### 特征增益的全视野扩展

特征注意的一个独特性质：对某一特征（如运动方向）的注意会在**整个视野**中增强编码该特征的神经元，而不是只在被注意的空间位置。这被称为"特征相似性增益"（feature similarity gain）模型（Treue & Martínez Trujillo 1999, PMID:10376597）。

例如：当你注意右侧视野中向右运动的点光栅，左侧视野中编码向右运动的 MT 神经元**也**会被增强——尽管你没有注意那个位置。

### VPA 的解剖投射

VPA 向 V4 发送直接投射，携带特征特异性的"偏置信号"。这些信号如何在 V4 中实现特征调制的具体机制尚不清楚（是振荡同步？是增益调制？层级靶点是否与 FEF 相同？）

### 空间注意 × 特征注意的叠加

两类偏置在 V4 中相互叠加：同时满足"目标位置"和"目标特征"的神经元获得最大增益，两者的效应在 V4 中可近似线性叠加（尽管底层计算是非线性的除法规范化）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| VPA 控制特征注意，不影响空间注意 | 猕猴单侧 VPA 失活 + V4 记录 | Bichot et al. 2019, PMID:31844117 | 高 |
| 特征注意增益遍布整个视野（特征相似性增益） | 猕猴 MT 方向调谐 + 注意任务 | Treue & Martínez Trujillo 1999, PMID:10376597 | 高 |

## 连接

- [[biased-competition]] — 特征注意是偏置竞争的"特征维度偏置"实例
- [[frontal-eye-field]] — FEF（背侧弓前区）控制空间注意；VPA（腹侧弓前区）控制特征注意
- [[dorsal-attention-network]] — DAN 整合空间和特征注意信号
- [[divisive-normalization]] — 特征增益通过 V4 的除法规范化计算实现

## 未解问题

- **Q-fba-01（高优先级）**：VPA 向 V4 传递特征偏置信号的神经机制是什么？是否也利用 γ 振荡同步？层级靶点是否与 FEF 的 L1/L5–6 反馈相同？
- **Q-fba-02（中优先级）**：人类中 VPA 的同源区是哪里？fMRI 刺激-失活联合实验能否在人类中复现 Bichot 2019 的解离？

## 修订历史

- 2026-09-13 · 创建 · 基于《偏置竞争的解剖学》一文（#143） · Bichot et al. 2019 (PMID:31844117) · 初始置信度：高

## 来源文章

- [[2026-09-13-fef-attention-oscillatory-feedback-biased-competition]]

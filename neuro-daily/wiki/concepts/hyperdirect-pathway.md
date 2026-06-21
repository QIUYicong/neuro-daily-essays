---
title: 超直接通路
slug: hyperdirect-pathway
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-19
updated: 2026-08-19
revision_count: 1
dimensions: [microcircuit, brain-region, behavior, cognition]
related: [response-inhibition, basal-ganglia, prefrontal-cortex, beta-oscillations, stop-signal-task]
prerequisites: [basal-ganglia, prefrontal-cortex]
opens_questions: [Q-ri-01, Q-ri-02]
source_articles: [2026-08-19-response-inhibition-hyperdirect-pathway]
key_sources: ["PMID:32155442", "PMID:16510720", "PMID:28103476", "PMID:27911752"]
---

# 超直接通路 (Hyperdirect Pathway)

> **一句话定义**：前额叶皮层（右侧额下回rIFG/辅助运动区preSMA）通过单突触谷氨酸投射直接激活丘脑底核（STN）的快速制动回路；在人类中传导潜伏期仅2.2 ms，跳过纹状体，是基底节三条皮质-皮层下通路中最快的，通过STN→GPi发散投射产生广泛的"全局"丘脑-皮层抑制。

## 当前理解

超直接通路（Hyperdirect Pathway）是基底节三条核心通路之一，其特点是：
1. **速度最快**：皮层→STN 的直接单突触连接，传导潜伏期仅 2.2 ms（Chen et al. 2020），远快于需要多个突触接力的间接通路（>10 ms 多突触）
2. **空间发散**：STN→GPi 的轴突投射是发散性的（一个 STN 神经元轴突可影响广泛的 GPi 区域）→ 产生全局性丘脑-皮层抑制
3. **皮层起点偏侧化**：在反应抑制中，右侧 rIFG 是主要驱动区；冲突检测中，preSMA 也有重要贡献

**解剖学**：前额叶皮层（主要是 IFG/BA44/BA45 和 preSMA）的锥体神经元通过皮质-丘脑底核白质纤维束（hyperdirect fiber tract）直接投射到 STN 腹侧区域。这条通路在灵长类（包括人类）中已被白质追踪（DTI/MRI）确认。

**功能逻辑**：超直接通路的速度优势使它成为"紧急制动"的主要机制。代价是缺乏选择性——STN 激活后通过 GPi 广泛抑制所有丘脑皮层驱动（全局抑制），而不是精确针对特定运动程序。

## 关键机制

### 回路结构

rIFG/preSMA（皮层）→ 单突触谷氨酸（2.2 ms 传导）→ STN（丘脑底核，唯一兴奋性基底节核团）→ 谷氨酸（发散性投射）→ GPi（苍白球内节，主要输出站）→ GABA（抑制）→ 丘脑（广泛丘脑-皮层回路）→ 皮层运动输出减弱（全局运动暂停）

### 与间接通路的对比

| 特征 | 超直接通路 | 间接通路 |
|------|---------|---------|
| 传导速度 | 极快（单突触，2.2 ms） | 慢（多突触，>10 ms） |
| 选择性 | 全局（非选择性） | 较高（纹状体拓扑） |
| 功能角色 | 速度优先的紧急制动 | 精度补充 |
| 皮层起点 | rIFG/preSMA | 额叶（IFG/preSMA）→纹状体 |
| 主要证据 | 颅内记录（Chen 2020）；fMRI（Aron 2006） | DCM有效连接（Jahfari 2011）；TUS（Nakajima 2022） |

### β振荡与同步

前额叶-STN 之间的 β 振荡（13-30 Hz）同步为信号传输提供"时间窗口"——相位对齐的振荡使 rIFG 的停止信号能更高效地激活 STN（Aron et al. 2016，PMID:27911752）。β 振荡的因果地位仍有争议（Q-ri-02）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| 人类IFG-STN单突触连接（2.2 ms潜伏期） | PD患者颅内记录+STN DBS（n=21） | PMID:32155442 [全文] | 高 |
| 传导速度约25 m/s（快速有髓轴突） | 同上 | PMID:32155442 [全文] | 高 |
| rIFG-STN同步强度与SSRT负相关（r=0.65） | 颅内LFP+ECoG同步分析 | PMID:32155442 [全文] | 高 |
| 超直接通路优先在停止信号后激活 | fMRI+SST（n≈20） | PMID:16510720 [全文] | 高 |
| STN→GPi发散投射→全局运动抑制 | TMS-MEP+行为溢出效应 | PMID:28103476 [全文] | 高 |
| β振荡在停止中提供前额叶-STN传输时间窗口 | LFP+计算分析 | PMID:27911752 [全文] | 中-高 |

## 连接

- [[response-inhibition]] — 超直接通路是反应抑制（特别是反应性停止）的速度机制
- [[basal-ganglia]] — 超直接通路是基底节三通路之一（直接/间接/超直接）
- [[prefrontal-cortex]] — rIFG/preSMA 是超直接通路的皮层起点
- [[stop-signal-task]] — SSRT 是量化超直接通路功能效率的行为指标
- [[beta-oscillations]] — β振荡同步增强前额叶→STN 信号传输效率

## 未解问题

- Q-ri-01：全局抑制（STN发散投射）与选择性抑制的解剖分离机制是什么？
- Q-ri-02：β振荡在停止中是机制本身（刹车）还是相关标志（温度计）？

## 修订历史

- 2026-08-19 · 创建 · 基于《大脑的刹车系统》文章 #105 · 初始置信度：高（Chen 2020 人类颅内记录提供直接生理证据）

## 来源文章

- [[2026-08-19-response-inhibition-hyperdirect-pathway]]

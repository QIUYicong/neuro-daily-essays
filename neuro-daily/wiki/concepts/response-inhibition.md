---
title: 反应抑制
slug: response-inhibition
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-08-19
updated: 2026-08-19
revision_count: 1
dimensions: [microcircuit, brain-region, behavior, cognition]
related: [hyperdirect-pathway, stop-signal-task, basal-ganglia, prefrontal-cortex, beta-oscillations, working-memory, dopamine-reward-prediction-error]
prerequisites: [basal-ganglia, prefrontal-cortex]
opens_questions: [Q-ri-01, Q-ri-02, Q-ri-03]
source_articles: [2026-08-19-response-inhibition-hyperdirect-pathway]
key_sources: ["PMID:32155442", "PMID:16510720", "PMID:28103476", "PMID:27911752", "PMID:17962524", "PMID:21543619", "PMID:20932513"]
---

# 反应抑制 (Response Inhibition)

> **一句话定义**：在接收到内部或外部停止信号时，取消已启动的运动（或认知）程序的能力；通过前额叶-基底节超直接通路（rIFG→STN→GPi）在约150毫秒内实现，并可分为反应性、主动性和选择性三种模式。

## 当前理解

我们现在认为，反应抑制是认知控制系统的核心功能，其神经基础主要由额叶-基底节回路承担，通过两条平行通路实现：**超直接通路**（rIFG→STN→GPi，速度优先，全局刹车）和**间接通路**（额叶→纹状体→GPe→STN→GPi，精度补充）。

反应抑制的标准量化工具是**停止信号任务（SST）**，核心指标是 SSRT（停止信号反应时，正常范围约 200-250 ms）。SSRT 延长见于 ADHD、物质成瘾和冲动控制障碍。

一个关键的现代发现是**全局运动抑制**（Wessel & Aron 2017，PMID:28103476）：叫停并非精确靶向，而是先触发全局性运动暂停（包括非目标效应器的抑制），再在皮层层面选择性地部分恢复。这是 STN→GPi 发散投射架构的必然结果。

Aron 2011（PMID:20932513）区分三种抑制模式：
- **反应性抑制**（reactive）：外部停止信号触发，经超直接通路快速响应
- **主动性抑制**（proactive）：预期可能需要停止，提前进入刹车就绪态
- **选择性抑制**（selective）：只停止特定效应器，可能依赖皮层内机制

## 关键机制

### 超直接通路（速度优先）

rIFG（右侧额下回，BA44/45）→ STN（单突触，谷氨酸）→ GPi（广泛激活）→ 丘脑-皮层输出全面抑制

关键参数（Chen et al. 2020，帕金森患者颅内记录）：
- 传导潜伏期：2.2 ± 0.2 ms（证明单突触性质）
- 传导速度：约 25 m/s（快速有髓轴突）
- IFG-STN 振荡同步强度 ↑ → SSRT ↓（r=0.65, p=0.040）

### 间接通路（精度补充）

额叶（rIFG/preSMA）→ 纹状体（iSPNs）→ GPe（抑制）→ STN（去抑制）→ GPi → 丘脑抑制

纹状体的精细躯体拓扑组织提供了选择性靶向能力（Jahfari et al. 2011，PMID:21543619）：
- 快速抑制者：rIFG→尾状核连接更强
- 慢速抑制者：preSMA→尾状核连接更强

### β振荡与就绪态

STN 和运动皮层中的 β 振荡（13-30 Hz）在停止试次中增强；振荡同步为 rIFG 到 STN 的信息传输提供时间窗口（Aron et al. 2016，PMID:27911752）。β 振荡的因果角色仍有争议（Q-ri-02）。

### STN 作为冲突缓冲器

除了对停止信号的反应性响应，STN 还在高冲突决策时发出"等一下"信号，增加决策慎重性。STN DBS 开启→高冲突决策更冲动（Frank et al. 2007，PMID:17962524），提供因果证据。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| 右侧IFG+STN在停止试次激活，与SSRT相关 | fMRI + SST（n≈20） | PMID:16510720 [全文] | 高 |
| 人类IFG-STN单突触连接（2.2 ms潜伏期） | PD患者颅内记录（n=21） | PMID:32155442 [全文] | 高 |
| 停止触发全局运动抑制（非目标MEP降低） | TMS-MEP + 行为溢出 | PMID:28103476 [全文] | 高 |
| 超直接（速度）+间接（精度）双通路协作 | 有效连接分析（DCM） | PMID:21543619 [摘要] | 中-高 |
| STN DBS影响高冲突决策（因果证据） | PD患者DBS ON/OFF | PMID:17962524 [摘要] | 高 |
| preSMA TMS 延长 SSRT（因果） | TMS-SSRT因果实验 | PMID:33045520 [摘要] | 中 |
| 间接通路（anterior IFG→putamen）独立因果贡献 | 经颅超声刺激（TUS） | PMID:35977493 [摘要] | 中 |

## 连接

- [[hyperdirect-pathway]] — 反应抑制的核心速度机制（rIFG→STN→GPi 超直接通路）
- [[stop-signal-task]] — 量化反应抑制能力的标准行为范式
- [[basal-ganglia]] — 提供反应抑制的解剖回路基础（STN/GPi/纹状体）
- [[prefrontal-cortex]] — rIFG/preSMA是反应抑制的皮层驱动区
- [[beta-oscillations]] — β振荡与STN就绪态和停止过程相关
- [[working-memory]] — 全局抑制短暂干扰工作记忆维持；认知控制的协同执行
- [[dopamine-reward-prediction-error]] — 多巴胺水平影响纹状体（间接通路）的停止倾向

## 未解问题

- Q-ri-01：全局 vs 选择性抑制的解剖基础（STN广播 vs 皮层内精化）
- Q-ri-02：β振荡在停止中是因果机制还是相关标志？
- Q-ri-03：主动性抑制的前额叶-STN 机制是否与反应性抑制相同？

## 修订历史

- 2026-08-19 · 创建 · 基于《大脑的刹车系统》文章 #105 · 初始置信度：高（established，多项人类颅内记录和fMRI收敛证据）

## 来源文章

- [[2026-08-19-response-inhibition-hyperdirect-pathway]]

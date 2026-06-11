---
title: 辅助运动区与前辅助运动区（言语启动）
slug: sma-presma
domain: systems
type: region
status: mainstream
confidence: high
created: 2026-08-19
updated: 2026-08-19
revision_count: 1
dimensions: [brain-region, behavior, cognition]
related: [speech-production-circuit, diva-model, basal-ganglia, motor-cortex]
prerequisites: [motor-cortex, basal-ganglia]
opens_questions: []
source_articles: [2026-08-19-speech-production-diva-motor-control]
key_sources: ["PMID:39807169", "PMID:23667281", "PMID:37337871"]
---

# 辅助运动区与前辅助运动区（SMA / pre-SMA）(Supplementary Motor Area / Pre-Supplementary Motor Area)

> **一句话定义**：SMA（BA6内侧部）和pre-SMA（BA6前端/SMA前方）是言语启动的最早皮层激活节点——在开口前约170–240ms开始活动，通过基底节-丘脑-皮层回路门控运动程序的释放，是"准备协调者"而非运动执行者。

## 当前理解

我们现在认为，SMA/pre-SMA 在言语系统中扮演**时序协调枢纽**的角色（Bullock et al. 2024, PMID:39807169）：

- **最早激活**：在视觉线索出现后约200ms开始激活，是所有言语相关脑区中最早之一（与IFS并列）
- **持续准备**：活动从刺激后200ms持续到实际开口，且持续时长随反应时动态伸缩（越慢越长）
- **开口即退出**：在开口后SMA/pre-SMA活动迅速撤退，而运动皮层（M1）才真正接管执行
- **RT预测**：SMA对反应时的预测能力在刺激后270ms即出现，早于腹侧感觉运动皮层约100ms

**pre-SMA vs. SMA的差异**：
- pre-SMA（更靠前）：峰值激活更早（-240ms）；与认知/计划功能更相关（GODIVA计划环路的节点）
- SMA（更靠后）：峰值激活稍迟（-170ms）；与运动执行准备更相关（GODIVA运动环路的节点）

**与基底节-丘脑的关系**：
- 当前模型：基底节→丘脑腹外侧核→SMA的时序输入，触发SMA产生"go"信号
- SMA作为BG输出与皮层运动系统之间的中继站
- 直接体内证据（人类胚胎期）：目前缺乏毫秒级精度证据，主要基于解剖连接+DIVA模型推断

## 关键机制

### 言语启动时序
1. 视觉线索 → ~200ms → SMA/pre-SMA开始激活
2. SMA活动持续，直到发音开始（随RT伸缩）
3. SMA活动在发音时迅速终止 → M1接管执行
4. SMA的RT预测能力：SMA振幅/持续时间预测当次试验的反应时

### SMA失活的效应（SMA损伤）
- 丘脑/SMA损伤/卒中：可导致SMA性失语（SMA aphasia）——初期缄默，恢复后言语启动困难、非流利，但理解保留
- SMA手术切除（胶质瘤）：术后临时言语启动困难，多数在数周内恢复（提示SMA损伤可通过网络代偿）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| pre-SMA激活峰值：开口前~240ms | 颅内iEEG，115人，10788次试验 | PMID:39807169 (2024) | 高 |
| SMA激活峰值：开口前~170ms | 同上 | PMID:39807169 (2024) | 高 |
| SMA活动随RT动态伸缩 | 混合效应线性模型；RT相关BGA | PMID:39807169 (2024) | 高 |
| SMA是DIVA模型中的启动图节点 | 计算模型+fMRI预测 | PMID:23667281 (2010) | 中 |
| pre-SMA是GODIVA计划BG环路节点 | 计算模型 | PMID:37337871 (2023) | 中（仍属模型推断） |

## 连接

- [[speech-production-circuit]] — SMA是该回路的启动节点
- [[diva-model]] — SMA对应DIVA的"启动图"
- [[basal-ganglia]] — BG→丘脑→SMA的"go"信号通路
- [[motor-cortex]] — SMA将准备信号传递给M1执行

## 未解问题

- SMA和BG之间精确时序关系的体内毫秒级证据（目前缺乏）
- SMA何时进入"已准备好"状态的分子/网络机制

## 修订历史

- 2026-08-19 · 创建 · 基于《大脑如何开口说话》第118篇 · 初始置信度：高

## 来源文章

- [[2026-08-19-speech-production-diva-motor-control]]

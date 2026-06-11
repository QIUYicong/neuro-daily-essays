---
title: 腹侧注意网络（VAN）
slug: ventral-attention-network
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-23
updated: 2026-09-23
revision_count: 1
dimensions: [brain-region, whole-brain-network, cognition, behavior]
related: [dorsal-attention-network, tpj-temporoparietal-junction, alpha-oscillations, prefrontal-cortex, spatial-neglect-concept, default-mode-network, norepinephrine-locus-coeruleus, theory-of-mind, communication-through-coherence]
prerequisites: [dorsal-attention-network, alpha-oscillations, tpj-temporoparietal-junction]
opens_questions: [Q-van-01, Q-van-02, Q-dan-03]
source_articles: [2026-09-23-ventral-attention-network-reorienting]
key_sources: ["PMID:11994752", "PMID:18466742", "PMID:21692662", "PMID:23835449"]
---

# 腹侧注意网络（Ventral Attention Network, VAN）

> **一句话定义**：以右侧颞顶联合区（TPJ）和腹侧额叶皮层（VFC/IFG）为核心的注意网络，专门检测行为相关的意外显著刺激，在背侧注意网络（DAN）专注于目标任务时充当"断路器"，触发注意的自动重定向；其右侧化反映了全景感知监控（双侧视野）的功能需求。

## 当前理解

我们现在认为，注意控制由两套解剖上分离但功能互补的网络协同完成（Corbetta & Shulman 2002，**PMID:11994752**）。其中，腹侧注意网络（VAN）是**显著性驱动**（stimulus-driven）注意的神经底物：

**核心特性**：
- **核心节点**：右侧颞顶联合区（rTPJ）+ 腹侧额叶皮层（VFC/IFG，右侧为主）
- **功能定位**：检测意外但行为相关的刺激，触发注意重定向（脱离当前目标聚焦，转向显著刺激）
- **右侧化**：VAN 以右半球为主，覆盖双侧视野的意外事件监控（"全景守卫"）
- **任务中的状态**：在主动任务执行期间，VAN 被背侧注意网络（DAN）**主动抑制**；意外刺激出现时 VAN 短暂激活（断路器）

**与 DAN 的动态关系**（Corbetta et al. 2008，**PMID:18466742**）：
- 正常专注任务：DAN 高活动，VAN 被主动抑制（两者呈 fMRI BOLD 信号负相关）
- 意外显著刺激出现：VAN 激活（~150-200 ms），中断 DAN 当前聚焦，触发 DAN 重配置
- 重定向完成后：VAN 再次被抑制，DAN 在新位置建立稳定聚焦

## 解剖结构

### 颞顶联合区（TPJ）
- **位置**：颞叶后部（STG）、顶下小叶（角回/缘上回）和枕叶的交汇处，双侧存在但右侧主导
- **接收输入**：来自腹侧视觉流（物体识别）、背侧流（空间信息）和多感觉皮层的多流汇聚
- **核心计算**：检测行为相关的感知预测违背（与期望不符且具有行为意义的刺激）
- **双重功能**：除 VAN 角色外，TPJ 也是心智化网络的核心节点（见 [[tpj-temporoparietal-junction]] 条目）

### 腹侧额叶皮层（VFC/IFG）
- **位置**：下额叶皮层（BA44/45/47），右侧为主
- **角色**：接收 TPJ 的检测信号，协调执行响应；"等待"机制确保充分评估后再切换；向 DAN 发送重定向指令

## 关键机制

### 断路器模型（Circuit Breaker Model）

正常目标导向任务期间（DAN 主导，VAN 抑制）：
1. FEF/IPS（DAN）控制感觉皮层的注意偏向
2. VAN（TPJ+VFC）维持低活动水平（被 DAN 主动抑制）
3. α 侧向化稳定，非目标区域被系统性抑制

意外显著刺激出现时：
1. **TPJ 激活**（~150-200 ms）：预测违背检测，P3a ERP 成分
2. **VFC 协调**：评估刺激行为相关性，触发执行响应
3. **DAN 重配置**（~200-350 ms）：接收 VAN 信号，中断当前聚焦，将资源重定向到新刺激
4. **VAN 退出**：重定向完成后，VAN 重新被抑制

### 右侧化机制

VAN 右侧化的功能性解释（Corbetta et al. 2008）：
- **双侧监控需求**：目标导向注意（DAN）只需为当前目标分配资源；但 VAN 必须持续监控**整个**感知场，覆盖两侧视野
- **右半球的弥散连接优势**：右半球具有更大范围的功能连接，与"广域监控"需求更匹配
- **与左侧 DAN 的不对称互补**：左侧 DAN 主要控制对侧（右侧）视野的主动注意；右侧 VAN 覆盖双侧视野的被动监控

### 神经调质调节：LC-NE 系统

蓝斑-去甲肾上腺素（LC-NE）系统调节 VAN 的激活阈值（Corbetta et al. 2008）：
- 高 NE（高唤醒）：降低 VAN 激活阈值 → 更容易被意外刺激打断
- 低 NE（疲劳、低唤醒）：升高阈值 → 更难被打断，但也更容易错过重要信号
- 目前证据主要来自间接研究，直接因果验证困难

### α 振荡重组：注意重定向的神经动力学

VAN 激活时的 α 动力学变化（EEG/MEG 研究）：
- 正常专注时：α 侧向化稳定（目标侧低，非目标侧高）
- VAN 激活触发重定向时：α 快速重组（原目标区域 α 升高，新目标区域 α 降低），约 150-250 ms 内完成
- **P3a 成分**（~250-350 ms）：VAN 激活的可靠 ERP 标志，分布于前额-中央区域（FCz/Cz）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| DAN（FEF+IPS）和 VAN（TPJ+VFC）解剖上分离、功能互补 | fMRI 系统综述 + 病变分析 | PMID:11994752 | 高 |
| 正常任务中 DAN-VAN 呈 BOLD 信号负相关 | 静息态 fMRI + 任务 fMRI | PMID:18466742 | 高 |
| VAN 正常任务中被主动抑制（非被动不活跃） | fMRI 任务调制分析 | PMID:18466742 | 高 |
| 右侧 VAN 损坏 → 左侧半侧空间忽视 | 右半球卒中患者系列研究 + fMRI | PMID:21692662 | 高 |
| DAN 和 VAN 的功能边界可能比最初描述更模糊 | TMS-fMRI 有效连接分析 | PMID:23835449 | 中 |
| LC-NE 调节 VAN 激活阈值 | 间接：药理 + 唤醒水平相关 | PMID:18466742 | 低-中（间接证据）|

## 连接

- [[dorsal-attention-network]] — 功能互补；任务中互抑；VAN 是 DAN 的断路器
- [[tpj-temporoparietal-junction]] — VAN 的核心感知节点（part-of）
- [[alpha-oscillations]] — VAN 激活时触发 α 快速重组（目标区域 α 侧向化翻转）
- [[norepinephrine-locus-coeruleus]] — LC-NE 系统调节 VAN 激活阈值
- [[default-mode-network]] — 右侧 TPJ 与 DMN 社会认知子网络（mPFC-PCu）有功能重叠
- [[theory-of-mind]] — TPJ 同时是心智化网络节点（双重功能）
- [[communication-through-coherence]] — CTC 框架中 VAN 激活时的 α/γ 动态变化
- [[prefrontal-cortex]] — VFC/IFG 是 VAN 的执行控制节点（PFC 腹侧部分）

## 疾病联系

**半侧空间忽视（Hemispatial Neglect）**：
- 最常见病因：右侧顶叶-颞叶联合区卒中，导致右侧 VAN 功能丧失
- 症状：忽视左侧视野的一切（感觉信号存在但无法获得注意资源），包括自身左侧身体
- 网络机制：不只是 VAN 局部损坏，还引发 DAN 连接性异常（网络平衡破坏）
- 治疗方向：棱镜适应疗法、对侧眼遮挡、持续向左注意训练（恢复网络平衡而非修复损伤脑区）

## 未解问题

- **Q-van-01**（高优先级）：VAN 激活的"行为相关性门控"如何实现？TPJ 如何区分"行为无关的意外噪声"和"行为相关的意外信号"？候选机制：来自杏仁核/眶额叶的价值信号，或当前任务 set 的预期调制
- **Q-van-02**（中优先级）：VAN 在 DAN-VAN 互抑中的抑制深度是否随任务难度非线性变化？是否存在"最大抑制"上限，此时任何外周刺激都无法打断专注？

## 修订历史

- 2026-09-23 · 创建 · 基于《大脑的断路器》（#153）文章 · 核心来源：Corbetta & Shulman 2002 (PMID:11994752)、Corbetta et al. 2008 (PMID:18466742，开放全文)、Corbetta & Shulman 2011 (PMID:21692662)、Vossel et al. 2014 (PMID:23835449) · 初始置信度：高

## 来源文章

- [[2026-09-23-ventral-attention-network-reorienting]]

---
title: DIVA 模型（言语产生计算-神经框架）
slug: diva-model
domain: concepts
type: theory
status: mainstream
confidence: high
created: 2026-08-19
updated: 2026-08-19
revision_count: 1
dimensions: [brain-region, cognition, methods]
related: [speech-production-circuit, sma-presma, broca-area, motor-cortex, efference-copy-speech]
prerequisites: [motor-cortex, auditory-dual-stream, basal-ganglia, cerebellum]
opens_questions: [Q-speech-01, Q-speech-02]
source_articles: [2026-08-19-speech-production-diva-motor-control]
key_sources: ["PMID:23667281", "PMID:22661828", "PMID:37337871"]
---

# DIVA 模型（言语产生计算-神经框架）(DIVA/GODIVA Model)

> **一句话定义**：DIVA（Directions Into Velocities of Articulators）是一个计算神经模型，将言语产生的前馈（左IFG音节程序）、反馈（pSTG听觉 + SMG体感误差→右vPMC纠偏）和效应副本（自产语音预测性抑制）三套机制整合为可预测、可检验的神经-计算框架；GODIVA 扩展版增加了双基底节环路以解释音节序列规划。

## 当前理解

DIVA（Tourville & Guenther 2010, PMID:23667281）是Frank Guenther实验室历时三十余年发展的言语运动控制模型，目前是该领域最完整的理论框架。

**核心组件及其神经对应**：

| 模型组件 | 神经对应 | 功能 |
|---------|---------|------|
| 言语声音图 | 左IFG（BA44）+ 左vPMC（BA6） | 储存音节前馈运动程序 |
| 启动图 | SMA（通过BG-丘脑） | 门控前馈命令的释放时机 |
| 听觉目标/误差图 | 双侧pSTG（两位置） | 储存声学目标；计算听觉误差 |
| 体感目标/状态图 | 腹侧SMG | 储存声道接触/位置目标；计算体感误差 |
| 反馈控制图 | 右腹侧vPMC | 将误差→纠偏运动命令 |
| 前向模型学习 | 双侧小脑（前旁蚓部+上外侧） | 预测运动后果；误差驱动学习 |
| 发声器官速度/位置图 | 腹侧M1（双侧） | 发出最终肌肉命令 |

**核心计算逻辑**：
1. 言语声音图激活音节前馈命令 → M1 → 发声器官运动
2. 同时向听觉/体感目标图发送"预期感觉"（效应副本）
3. 实际感觉 vs. 预期感觉 → 误差信号
4. 误差 → 右vPMC → 叠加纠偏命令（与前馈整合）
5. 误差信号同时用于更新前馈程序（学习）

**GODIVA 扩展**（言语序列规划，Meier & Guenther 2023, PMID:37337871）：
- **运动BG环路**（vPMC + SMA）：选择并释放当前音节的运动程序
- **计划BG环路**（pIFS + pre-SMA）：在执行当前音节时，通过"梯度阶序工作记忆"预加载下一音节

## 关键机制

### 前馈/反馈动态平衡
- 流利成人言语：~95%+ 依赖前馈（听觉反馈延迟120-150ms > 音素持续时间）
- 学习阶段（婴幼儿咿呀学语）：反馈比重高（通过误差驱动修改前馈程序）
- 扰动/噪音条件：反馈比重临时上调

### 运动等价
- 相同声学目标可通过不同发声器官组合实现（舌高 vs. 唇圆产生/u/）
- 说明DIVA的控制目标是**声学空间**（非肌肉-关节空间）
- 这是DIVA区别于纯粹运动控制模型的关键特征

### 婴儿习得的计算序列
1. 咿呀学语：随机运动 → 建立发声器官运动与听觉结果的映射
2. 模仿阶段：对比大人语音（目标）与自己发音（实际）→ 学习语言特异性声学目标
3. 成熟后：前馈程序固化，反馈主要用于维护（无听觉则程序缓慢漂移）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| 前馈主导流利言语 | 失聪者保留语音；遮蔽噪音无即时影响 | PMID:22661828 | 高 |
| 听觉误差→右vPMC纠偏（fMRI有效连接） | F1实时扰动+fMRI | PMID:23667281 (Tourville 2008引用) | 高 |
| 失用症：左侧BA44/vPMC损伤→程序提取失败 | 损伤-症状相关研究 | PMID:23667281 | 高 |
| 共济失调性构音障碍：小脑损伤→音节计时障碍 | 损伤-症状相关研究 | PMID:23667281 | 高 |
| 口吃：反馈依赖过度（右侧过激活） | fMRI元分析；节拍器效应 | PMID:23667281 | 中 |

## 连接

- [[speech-production-circuit]] — 该模型描述的完整神经回路
- [[sma-presma]] — 启动图的神经基础（开口前240ms激活）
- [[efference-copy-speech]] — 效应副本/预测性抑制的理论核心
- [[broca-area]] — 言语声音图所在脑区（但非运动协调本身）
- [[motor-cortex]] — 模型输出端（发声器官位置图）

## 未解问题

- Q-speech-01：GODIVA梯度阶序工作记忆的具体神经实现（持续放电/短期突触增强/相位编码）？
- Q-speech-02：韵律（prosody）控制如何整合进DIVA/GODIVA框架？（目前几乎无处理）

## 修订历史

- 2026-08-19 · 创建 · 基于《大脑如何开口说话：前馈/反馈双控制系统》第118篇 · 初始置信度：高

## 来源文章

- [[2026-08-19-speech-production-diva-motor-control]]

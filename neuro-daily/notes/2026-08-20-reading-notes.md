# 阅读笔记 2026-08-20

**今日主题**: STG 音素感知神经计算机制
**文章**: 声音之刀：颞上回如何将连续声学流切割为音素

---

## 核心来源笔记

### 来源1：Bhaya-Grossman & Chang (2022) Annual Review of Psychology
**PMID:34672685 / PMC:PMC9447996**
- **研究问题**：STG执行哪些神经计算来实现音素感知？
- **方法**：综述，整合ECoG、fMRI、MEG、行为研究
- **主要发现**：
  - STG有4大核心计算：非线性范畴化、说话者归一化、语境修复（预测）、时间标记提取
  - 局部尺度编码声学-音素特征（feature），群体尺度编码音素身份（phoneme identity）
  - STG反应是非线性动态的，不是线性特征检测器
  - pSTG：声音起始标记；mSTG：peakRate事件（音节边界）；aSTG/STS：语音可理解性
- **改变了什么理解**：从"被动声学传递"到"主动预测与范畴化"
- **证据强度**：综述，整合多项ECoG研究，质量高
- **局限**：大部分ECoG研究来自英语，跨语言普遍性待验证
- **全文可用**：✅

### 来源2：Mesgarani et al. (2014) Science
**PMID:24482117**
- **研究问题**：人脑 STG 如何在直接记录中编码英语音素特征？
- **方法**：ECoG（直接颅内电极），手术患者，自然语音朗读
- **主要发现**：
  - 单个电极选择性响应音素特征（发音方式、部位、送气性）
  - 英语完整音素库可从群体激活模式中解码
  - 非线性多cue整合
- **全文可用**：摘要（*Science*付费）
- **重要性**：这是"STG编码音素特征非音素本身"这一结论的核心实验证据

### 来源3：Giraud & Poeppel (2012) Nat Neurosci
**PMID:22426255**
- **核心主张**：神经振荡通过theta（~5Hz，~200ms）和gamma（~40Hz，~25ms）两个频段实现言语的双时间尺度采样
- **全文可用**：摘要（Nat Neurosci付费）
- **与STG的关系**：提出了实现双时间窗口的振荡机制，是理论框架性文章

### 来源4：PMC:3364513（MEG+两时间窗口）
- **主要发现**：MEG实验直接验证theta（200ms）和gamma（25ms）的相位相干性追踪；右半球theta追踪更强；白噪声控制下无相位锁定（排除纯声学解释）
- **全文可用**：✅

### 来源5：Ten Oever et al. (2024) PNAS
**PMID:38805278**
- **重要发现**：STG振荡相位与音素频率统计相关，MTG振荡相位与词汇频率统计相关——两个相邻区域用不同统计量锁定不同语言层次
- **全文可用**：摘要

### 来源6：Ortiz-Mantilla et al. (2016) J Neurosci
**PMID:27903720**
- **主要发现**：婴儿6-12个月 theta 减少 + gamma 增强 → 母语音素范畴固化（perceptual narrowing）
- **全文可用**：摘要
- **与认知图的关系**：发育维度的证据，连接到语言关键期

---

## 今日需写/更新的 wiki 页面

1. **新建**: `wiki/systems/stg-phoneme-processing.md`
2. **新建**: `wiki/concepts/cortical-speech-entrainment.md`
3. **新建**: `wiki/concepts/phoneme-categorical-perception.md`
4. **修订**: `wiki/systems/auditory-cortex.md` — 添加 stg-phoneme-processing 相关细节
5. **修订**: `wiki/systems/auditory-dual-stream.md` — 添加 STG 音素计算细节

---

## 关键术语

- **peakRate event**：声学包络一阶导数的极值时刻，对应音节边界/元音起始，mSTG高度选择
- **AST（Asymmetric Sampling in Time）**：左右半球在时间整合窗口上的非对称性（左快右慢）
- **phoneme restoration**：噪声掩蔽音素但感知完整；神经机制是STG提前300ms的预测性激活
- **speaker normalization**：STG对说话者声道差异进行归一化后的元音表征
- **cortical entrainment**：STG振荡与言语包络的theta相位同步

---

## 未解问题（待录入 unresolved_questions.md）

- Q-stg-01：STG皮层振荡entrainment是主动预测（internal clocking）还是被动声学驱动（stimulus tracking）？（优先级：高）
- Q-stg-02：STG的音素范畴化机制：局部竞争抑制 vs 自上而下词汇反馈的权重分配？（优先级：中）
- Q-stg-03：STG的四大计算（归一化/范畴化/修复/时间标记）是否在解剖上可以解离（分别损毁后分别失效）？（优先级：中）

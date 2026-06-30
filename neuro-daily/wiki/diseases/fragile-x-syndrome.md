---
title: 脆性 X 综合征（Fragile X Syndrome, FXS）
slug: fragile-x-syndrome
domain: diseases
type: disease
status: established
confidence: high
created: 2026-10-17
updated: 2026-10-17
revision_count: 1
dimensions: [molecular, cellular, synaptic, cognition, disease]
related: [mglur-ltd, fmrp-translational-repressor, ampa-receptor, arc-arg31, homer1a, autism-spectrum-disorder, intellectual-disability, synaptic-plasticity]
prerequisites: [mglur-ltd, protein-synthesis-dependent-plasticity, ampa-receptor]
opens_questions: [Q-mglur-ltd-03, Q-fxs-developmental-window, Q-fxs-biomarker]
source_articles: [2026-10-17-mglur-ltd-hippocampal-fragile-x]
key_sources: ["PMID:15219735", "PMID:12032354", "PMID:26764156", "PMID:21090964", "PMCID:PMC3019409", "PMID:23083736"]
---

# 脆性 X 综合征（Fragile X Syndrome）

> **一句话定义**：最常见的遗传性单基因智力障碍，由 FMR1 基因 CGG 重复扩增导致 FMRP 蛋白缺失，FMRP 作为树突 mRNA 翻译抑制剂的功能丧失导致 mGluR-LTD 过度激活和突触功能障碍，表现为智力障碍、语言迟滞、社交回避和感觉过敏。

## 当前理解

我们现在认为，FXS 是一个分子-突触-回路因果链高度清晰的神经发育障碍：
1. **遗传**：FMR1 基因（Xq27.3）5'UTR CGG 重复扩增（>200次）→ 甲基化沉默 → FMRP 蛋白缺失
2. **分子**：FMRP 正常作为树突 mRNA 翻译抑制剂；其缺失导致 mGluR5 下游翻译失控
3. **突触**：mGluR-LTD 过度激活（Arc 等 LTD 效应蛋白持续过量）→ AMPAR 过度内化
4. **认知**：突触权重弥漫性减弱 → 信噪比下降 → 学习记忆受损

FXS 代表了神经科学将基因-机制-疾病-治疗因果链完整打通的范本，同时也揭示了动物模型与人类临床之间深刻的转化鸿沟（mavoglurant 临床失败）。

## 关键机制（疾病视角）

### 遗传基础

- **正常**：FMR1 CGG 重复 5–44 次，FMRP 正常表达
- **前突变**：55–200 次，FMRP 部分减少，与脆性 X 相关震颤/共济失调综合征（FXTAS）相关
- **完全突变**：>200 次 → CGG 甲基化 → 启动子甲基化 → FMR1 转录沉默 → FMRP 缺失

流行率：约 1/4000 男性，1/8000 女性（X 连锁，男性更重）

### FMRP 的正常功能（疾病理解窗口）

FMRP（fragile X mental retardation protein）是一种 RNA 结合蛋白，识别和结合数百种树突 mRNA 的 G 四链体结构，在静息状态抑制其翻译：
- 靶 mRNA 包括：Arc/Arg3.1、MAP1B、CaMKIIα、PSD-95、GluA1 等
- 这些 mRNA 编码的蛋白质正是 mGluR-LTD 和突触可塑性的核心效应子
- mGluR5 激活 → FMRP 磷酸化/泛素化降解 → 翻译解除 → LTD 精准执行（有刹车控制）

**FMR1 KO（FXS）中**：这些 mRNA 在静息状态持续翻译（无刹车）→ Arc 等蛋白持续过量 → mGluR-LTD 不需要等新蛋白合成就能充分执行（蛋白合成独立的增强 LTD）

### FXS 突触表型

- **mGluR-LTD 增强**（Huber et al. 2002, PMID:12032354）：82% vs 93% 基线（p=0.004），翻译抑制剂无效
- **树突棘过密（immature spines）**：细长型棘（非成熟型）过多，头部偏小
- **AMPAR 数量减少趋势**：部分脑区
- **听觉惊恐过强（audiogenic seizures）**：FMR1 KO 小鼠
- **眼部畸形（drosophila）**：Drosophila dfmr1 KO 模型

### Bear 的 mGluR 理论与治疗预测

**核心假设**（Bear et al. 2004, PMID:15219735）：
- FXS 的核心病理 = mGluR5 下游蛋白合成过度
- 预测：减弱 mGluR5 信号应能挽救 FXS 表型
- 遗传验证：Fmr1 KO × mGluR5 杂合 KO → 多种表型纠正（Bhattacharya et al. 2012, PMID:23083736）

## 临床试验与转化困境

### mavoglurant（AFQ056）Phase 2b RCT（Berry-Kravis et al. 2016）
- **两个平行 RCT**：成人（n=175, 18-45 岁）+ 青少年（n=139, 12-17 岁），12 周
- **结果**：两个试验均未达主要终点（ABC-C 行为量表无显著改善）
- **结论**：未能在人类中证实 mGluR 理论；建议未来探索更年轻人群、更长疗程、更好的生物标志物

**失败分析**（置信度中）：
1. 患者异质性：FXS 表型变异极大
2. 治疗时间窗：成人的发育关键期可能已过
3. 结果测量：行为量表对认知/神经生物学变化不够敏感
4. 动物模型局限：小鼠 FXS 模型可能不充分代表人类 FXS 复杂性

### Homer1a 在 FXS 中的病理角色（新兴，置信度中）

FMR1 KO 中 Homer1a mRNA 翻译增加 → PSD 中 Homer1a 持续升高 → 长型 Homer 减少 → mGluR5 与 IP3R 解耦调节受损 → mGluR5 信号"慢性部分激活"状态 → 这可能是 mGluR-LTD 持续过强的贡献机制之一。注：该因果关系尚未被独立实验直接证明。

## 关键证据

| 主张 | 证据 | 来源 | 置信度 |
|------|------|------|--------|
| FMR1 CGG 扩增→甲基化→FMRP 缺失 | 遗传测序+蛋白免疫印迹 | 经典遗传学文献 | 高 |
| Fmr1 KO mGluR-LTD 增强且蛋白合成独立 | 脑片电生理+翻译抑制剂 | PMID:12032354 | 高 |
| 减弱 mGluR5（遗传）纠正 FX 小鼠表型 | Fmr1 KO × mGluR5+/- 表型救济 | PMID:23083736 | 中-高 |
| mavoglurant RCT 未改善人 FXS 行为症状 | Phase 2b RCT n=314 | PMID:26764156 | 高（负性结果）|

## 连接

- [[mglur-ltd]] — FXS 的核心突触病理；mGluR-LTD 在 FMRP 缺失时过度激活
- [[homer1a]] — FXS 中 Homer1a 病理性升高可能参与 mGluR5 信号失调
- [[ampa-receptor]] — FXS 突触的最终效应：AMPAR 过度内化
- [[arc-arg31]] — Arc 是 mGluR-LTD 的执行蛋白；FXS 中 Arc 翻译持续过量

## 未解问题

- Q-fxs-developmental-window（高优先级）：mGluR5 干预在哪个发育时间窗最有效？能否在儿童早期（发育关键期内）取得更好效果？
- Q-mglur-ltd-03（高优先级）：是否存在对 mGluR5 拮抗剂响应的 FXS 亚型？预测生物标志物？
- Q-fxs-biomarker（中优先级）：能否用神经成像（fMRI 功能连接）或 EEG 生物标志物预测治疗响应？

## 修订历史

- 2026-10-17 · 创建 · 基于《当受体失去支架》(#177) · 综合 Bear et al. 2004 / Huber et al. 2002 / Berry-Kravis et al. 2016 / Krueger & Bear 2011 · 初始置信度：高

## 来源文章

- [[2026-10-17-mglur-ltd-hippocampal-fragile-x]]

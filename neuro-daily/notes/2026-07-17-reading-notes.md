# 2026-07-17 阅读笔记：突触时序依赖可塑性（STDP）

## 检索策略

- 数据库：PubMed / NCBI E-utilities，PMC Open Access
- 搜索词：`spike timing dependent plasticity STDP review`、`Bi Poo 1998 synaptic hippocampal`、`STDP calcium physiological`、`STDP theta oscillations place cells`
- 候选结果：~15 篇精选，采用 10 篇核心来源

---

## 来源 1：Bi & Poo 1998（PMID:9852584；PMC6793365）

**实验设置**：培养大鼠海马神经元（E18-20，8-14天体外），双全细胞穿孔patch-clamp

**关键数字**：
- LTP 窗口：突触后在突触前后 20ms 内 → 平均 48% EPSC 增幅
- LTD 窗口：突触后在突触前前 20ms 内 → 平均 18% EPSC 减幅
- NMDA 拮抗（AP-5）→ 两种可塑性均消失
- 靶细胞特异性：谷氨酸→GABAergic 突触无可塑性

**局限**：体外培养，非生理钙浓度，单次配对需重复 60 次

---

## 来源 2：Markram et al. 1997（PMID:8985014，仅摘要）

**历史地位**：第一篇新皮层 STDP 论文，先于 Bi & Poo
**方法**：大鼠体感皮层层5锥体神经元双全细胞记录，bAP-EPSP 时序控制

---

## 来源 3：Feldman 2012（PMID:22920249；PMC3431193）

**两种 STDP 形式**：形式一（NMDAR-LTP + NMDAR-LTD）；形式二（NMDAR-LTP + mGluR/CB1-LTD）
**频率依赖**：10–30 Hz 有效；<10 Hz 只有 LTD；>30 Hz 无视时序
**树突位置**：近端 Hebbian；远端 anti-Hebbian（bAP 衰减）
**神经调质**：DA 可反转 STDP 符号

---

## 来源 4：Inglebert & Debanne 2021（PMID:34616278；PMC8488271）

**生理钙浓度对 STDP 的影响**：
- 1.3 mM → 无可塑性
- 1.8 mM → 仅 LTD
- 3.0 mM → 经典 Hebbian STDP
- 恢复策略：5–10 Hz 背景激活可在生理钙下恢复 STDP

---

## 来源 5：Theta-STDP 模型（PMC10019887）

**关键数字**：
- θ 前进+STDP：R²=0.87 vs TD 后继表征
- 无 θ 前进：R²=0.63，慢 4.5 倍
- 5 分钟（9.6 圈）达到 75% 最终权重

---

## 来源 6：Foncelle et al. 2018（PMID:30018546；PMC6037788）

三因素调制：DA/ACh/NE/NO/BDNF/星形胶质细胞均调制 STDP；计算模型如何涌现 STDP 时序特性

---

## 仅摘要的来源（7-10）

- Brzosko 2019（PMID:31437453）：神经调质调制 STDP 综述
- Debanne & Inglebert 2023（PMID:36924615）：STDP 与记忆，忆阻器应用
- Caporale & Dan 2008（PMID:18275283）：Annual Review，跨物种 STDP
- Dan & Poo 2004（PMID:15450157）：Neuron 综述

---

## 核心认知获取

1. STDP 时序窗口由 NMDA 动力学 + bAP 传播时间决定
2. 钙假说：高峰→CaMKII→LTP；低流→钙调磷酸酶→LTD
3. 生理钙浓度下单次配对无效 → θ 振荡是体内 STDP 的必要条件
4. θ 前进将行走方向压缩进 STDP 窗口 → 认知地图自动获得方向性
5. 三因素规则 + STC → STDP 与奖励信号的跨时间尺度整合

---

## 待建/修订 wiki 页面

- **创建**：`wiki/concepts/stdp.md`（填补悬空引用）
- **修订**：`wiki/concepts/nmda-receptor.md`（STDP 特定机制补充）
- **修订**：`wiki/concepts/hebbian-learning.md`（标注 [[stdp]] 已建立）

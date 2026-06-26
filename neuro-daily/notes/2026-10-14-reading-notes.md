# 阅读笔记 2026-10-14（文章 #174）

## 主题
清醒中的"睡眠"：皮层 ON/OFF 双稳态与突触稳态假说的因果验证

---

## 来源 1：Driessen et al. 2026 — 核心论文

**完整引用**：Driessen K, Squarcio F, Tononi G, Cirelli C (2026). Induction of cortical on/off periods in awake mice fulfills sleep functions. *Nature Neuroscience*. DOI: 10.1038/s41593-026-02318-9. PMC: PMC12632314.

**要解决什么问题**：
睡眠中皮层 ON/OFF 双稳态周期是突触稳态（SHY）的因果机制，还是只是睡眠的相关物？若在清醒动物中人工诱导 ON/OFF 周期，能否复现睡眠的突触和记忆功能？

**方法**：
- SOM+/ChR2 小鼠：激活 SST+ 中间神经元触发网络级抑制 → ON/OFF 周期
- ACR/stGtACR1 小鼠：直接抑制锥体神经元 → ON/OFF 周期
- 对照：halorhodopsin 强直性抑制（同等降低放电率，无 ON/OFF 转换）
- 30 分钟诱导，5 小时睡眠剥夺末期
- 三大评判标准：① 后续睡眠 SWA ② 突触小体 GluA1/p-GluA1 ③ 地板纹理识别 24h 记忆

**发现**：
1. SWA 显著减少（诱导侧 vs 对侧）：SOM+ t₁₀=-17.69 p<0.001；ACR t₉=-13.12 p<0.001
2. 恢复至均等：3-5小时后
3. 频谱特异性：仅 delta 频段（0.5-4 Hz）有效，宽频无显著变化
4. GluA1 下调：SOM+ t₇=5.51 p<0.001；ACR t₇=6.26 p<0.001
5. p-GluA1(Ser845) 下调：SOM+ t₇=8.77 p<0.001；ACR t₇=4.77 p<0.01
6. 记忆恢复：睡眠0.61±0.08；睡眠剥夺0.45±0.09；诱导组0.56±0.08（F=7.34, p=0.005）
7. 神经元同步性（STTC）下降：SOM+ t₁₀=3.85 p=0.004；ACR t₈=2.49 p=0.041
8. **强直性抑制对照**：SWA p=0.62，无效！

**改变了什么理解**：
- ON/OFF 双稳态从"睡眠相关物"升格为"突触稳态的充分执行单元"
- 提供了 SHY 的直接因果证据
- 解释了单侧大脑睡眠（海豚/鸟类）的功能可能性
- 强约束：突触下调需要 ON→OFF 转换时序，不只是放电率降低

**证据强度**：高（PMC开放全文；两种独立光遗传学策略；多重测量指标；严格对照）

**局限**：
- 30 分钟非完整睡眠，记忆仅部分恢复（0.56 vs 0.61）
- 只测试了非陈述性感觉运动记忆（FTR）
- 光遗传学不可直接转化至人类
- 清醒期 NE/ACh 系统仍处于觉醒状态（与真实睡眠的化学背景不同）

**需解释的术语**：
- STTC（spike-time tiling coefficient）：衡量神经元对之间放电同步性的无偏统计量
- Synaptoneurosome：分离纯化的突触后密度富集制品，用于测量突触蛋白水平

---

## 来源 2：Tononi & Cirelli 2014 Neuron 综述 — SHY 框架

**引用**：Tononi G, Cirelli C (2014). Sleep and the price of plasticity. *Neuron* 81:12-34. PMID:24411729. PMC:PMC3921176（开放全文）

**核心内容**：
- SHY 完整理论框架：清醒→净 LTP→突触饱和；睡眠→慢振荡驱动→净 LTD→突触归一化
- 预测：SWA 功率 ∝ 之前清醒的突触增强程度
- 证据汇总：单侧训练增加对侧 SWA；认知任务后局部 SWA 升高
- Down-selection 框架初稿：被 SWR 激活的记忆突触可能被保护

**与今日文章的关系**：今日论文是对该综述核心预测的因果验证

---

## 来源 3：de Vivo et al. 2017 Science — 超微结构直接证据

**引用**：de Vivo L et al. (2017). Ultrastructural evidence for synaptic scaling. *Science* 355:507-510. PMID:28154076

**核心内容**：
- SBEM（序列块面扫描电镜）测量小鼠体感+运动皮层 L2 的 6,920 个突触
- 睡眠后 vs 清醒后：ASI（轴突-棘界面面积）平均缩小 ~18%
- 选择性：最小 80% 突触缩小 ~11.9%；最大 20% 基本不变（+0.7%）
- 含再循环内体突触缩小更多（~20-25%）

**全文可用性**：未读取全文（需机构访问）；数据来自 SHY 综述和今日论文引用

---

## 来源 4：Tononi & Cirelli 2006 Sleep Med Rev — SHY 初始版本

**引用**：Tononi G, Cirelli C (2006). Sleep function and synaptic homeostasis. *Sleep Med Rev* 10:49-62. PMID:16376591

**核心内容**：
- SHY 最初提出：学习→突触增强→睡眠慢波→突触下调（最初版本是"downscaling"不是"down-selection"）
- SWA 作为突触负债表的原始预测
- 旧版的核心命题：无睡眠→突触饱和→认知功能下降

**全文可用性**：未读取全文（摘要可用）

---

## 概念连接记录

- ON/OFF 双稳态 → shy-hypothesis（因果验证）
- ON/OFF 双稳态 → cortical-slow-oscillation（UP/DOWN 是 SO 的基础特征）
- GluA1 下调 → ampa-receptor（分子机制页面可更新）
- SHY down-selection → memory-consolidation（与主动巩固理论的张力）
- 局部睡眠 → unihemispheric sleep（需要新页面或在相关页面提及）
- 人类应用前景 → tacs-sleep-stimulation（潜在未来页面）

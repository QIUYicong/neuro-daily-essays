---
title: CaMKII（钙调蛋白依赖蛋白激酶 II）
slug: camkii
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-05-26
updated: 2026-06-28
revision_count: 4
dimensions: [molecular, synaptic, cellular]
related: [nmda-receptor, ltp, ampa-receptor, synaptic-transmission, btsp, dendritic-computation, three-factor-learning-rule, voltage-gated-calcium-channels, dendritic-spine, cofilin-actin-spine]
prerequisites: [nmda-receptor, synaptic-transmission]
opens_questions: [Q-camkii-subunit-exchange, Q-camkii-maintenance-lifetime, Q-camkii-ddsc-synapse-specificity, Q-camkii-two-modes-interaction, Q-spine-btsp-01]
source_articles: [2026-05-26-nmda-receptor-ltp, 2026-09-20-btsp-camkii-molecular-timekeeper, 2026-09-23-dendritic-spine-structural-plasticity, 2026-06-28-tarp-ampa-receptor-synaptic-trafficking]
key_sources: ["PMID:34908526", "PMID:22510460", "PMID:30359599", "PMID:37672577", "PMID:39385027", "PMID:15664178", "PMID:20670832", "PMID:27667007", "PMID:36223737"]
---

# CaMKII（钙调蛋白依赖蛋白激酶 II，Ca²⁺/Calmodulin-Dependent Protein Kinase II）

> **一句话定义**：突触后致密区（PSD）中浓度极高的丝氨酸/苏氨酸蛋白激酶，Ca²⁺ 内流时被激活，通过 T286 自磷酸化形成持续活化状态；在 LTP 中表现为快速局部激活，在 BTSP 中则表现为平台电位后 10–100 秒的延迟弥散随机激活（DDSC），是两种时间尺度突触可塑性的共同核心分子。

## 当前理解

我们现在认为，αCaMKII 至少有**两种截然不同的激活模式**，分别支持不同时间尺度的突触可塑性：

| 激活模式 | 触发 | 激活位置 | 时间尺度 | 可塑性功能 |
|---------|------|---------|---------|----------|
| 快速局部模式（LTP 模式） | 单个突触 NMDA 受体 Ca²⁺ 内流 | 突触后密度（突触特异性） | 毫秒级激活，秒内衰退（T286A: 1.9 s，WT: 8.2 s 自主激活期） | 经典 LTP，突触特异性增强 |
| 延迟弥散模式（DDSC，BTSP 模式） | 树突钙平台电位→IP₃→ER 钙释放 | 整根树突（非突触特异性） | 平台电位后 10–100 秒延迟激活，峰值约 30–40 秒 | BTSP，行为时间尺度突触增强 |

**T286 自磷酸化**是 CaMKII 实现时间整合的关键：Ca²⁺/CaM 激活 CaMKII 后，T286 位点自磷酸化使激酶在 Ca²⁺ 清除后仍保持活性（"自主激活"）。野生型 αCaMKII 激活持续约 8.2 秒；T286A 突变体（无法自磷酸化）激活仅持续 1.9 秒，导致 BTSP 几乎完全丧失（Xiao et al., 2023，PMID:37672577）。

**LTP 中的作用（2021 年关键修正）**：CaMKII 不只参与 LTP 诱导，也是已建立 LTP 的**维持**所必需的。在已完成 LTP 的突触上持续抑制 CaMKII，LTP 会完全逆转（Tao et al., 2021，PMID:34908526）。

**BTSP 中的新角色（2024 年重大发现）**：Jain et al. 2024（Nature，PMID:39385027）使用 2pFLIM 直接可视化，证明平台电位期间 CaMKII **不**立即大幅激活（推翻原有预期）；真正的激活发生在平台电位后 10–100 秒，以延迟、弥散、随机的方式席卷整根树突（DDSC）。paAIP2 光遗传实验提供了因果证明：在 15–30 秒窗口阻断 CaMKII → BTSP 完全消失。

## 关键机制

### LTP 模式：快速局部激活

1. NMDA 受体开放 → Ca²⁺ 内流进入突触后棘
2. Ca²⁺ 结合**钙调素（calmodulin）**，形成 Ca²⁺/CaM 复合物
3. Ca²⁺/CaM 结合并激活 CaMKII（构象变化，解除自抑制结构域）
4. **T286 自磷酸化**（催化亚基之间互相磷酸化）→ 形成**自主激活状态**
5. 磷酸化 **GluA1 S831**：提高 AMPA 受体单通道电导；促进 GluA1 靶向突触
6. 磷酸化 **TARP C 末端 polybasic region**（stargazin/γ-2 的 9 个丝氨酸；TARPγ-8 的 Ser277/Ser281）→ 静电掩蔽解除 → PDZ 配体暴露 → PSD-95 亲和力骤升约 10–30 倍 → AMPA 受体扩散陷阱捕获（Opazo 2010, PMID:20670832；Park 2016, PMID:27667007；Ravi 2022, PMID:36223737）
7. LTP 表达（突触特异性）：GluA1 S831 磷酸化（增加电导）和 TARP 磷酸化（增加受体捕获数量）并行实现突触权重增加

CaMKII 是由 12 个亚基组成的环形全酶（六聚体或十二聚体）。激活后，亚基间自磷酸化可能使磷酸化状态在蛋白质更新中传递（**亚基交换假说**）。

### BTSP 模式：延迟弥散随机激活（DDSC）

**发现于 Jain et al., 2024, Nature（PMID:39385027）**，全程通过 2pFLIM 直接成像：

```
树突钙平台电位（100–500 ms）
  → L 型 Ca²⁺ 通道 + NMDA 受体大量 Ca²⁺ 内流
  → 激活磷脂酶 Cβ（PLCβ）
  → IP₃ 生成
  → IP₃ 受体激活内质网（ER）
  → ER 延迟钙释放（延迟 10–100 秒）
  → DDSC：整根树突 CaMKII 延迟、弥散、随机激活
      峰值约 30–40 秒后
  → 整合此前到达的"资格痕迹"突触输入
  → BTSP（行为时间尺度突触增强）
```

**DDSC 三特征（"DDS"）**：
- **Delayed（延迟）**：平台电位后 10–100 秒才出现激活峰
- **Dendritic（树突弥散）**：CaMKII 激活遍及整根树突，而非局限于单个突触
- **Stochastic（随机）**：个体树突中激活的时间和空间分布具有随机性

**因果性证明**（paAIP2 光遗传实验）：
- 在**15–30 秒窗口**精准抑制 CaMKII → BTSP 完全消失
- 在平台电位发生时抑制 CaMKII → BTSP **不受影响**（即时激活非关键）
- 人工触发"延迟去极化"（模拟 DDSC 时序）→ 拯救被阻断的 BTSP

### 两种模式的分子区别

| 特征 | LTP 模式 | DDSC/BTSP 模式 |
|-----|---------|--------------|
| Ca²⁺ 来源 | NMDA 受体（突触局部） | ER 延迟释放（IP₃ 依赖） |
| 激活时间 | < 1 ms | 10–100 s（延迟）|
| 激活范围 | 突触后密度（点状） | 整根树突（弥散）|
| 关键中间信号 | Ca²⁺ 直接激活 CaM | IP₃→ER→延迟 Ca²⁺ |
| T286 自磷酸化作用 | 维持数秒短期自主激活 | 维持足够长的激活以跨越 15–30 s 时间窗口 |
| 所支持的可塑性 | LTP（毫秒级时序） | BTSP（秒级时序） |

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| CaMKII T286 自磷酸化形成自主活化态 | T286A 突变消除 LTP，生化自磷酸化实验 | PMID:22510460 (PMC3367554) | 高 |
| CaMKII 对 LTP 维持必需（非仅诱导） | myr-CN27 处理后完全逆转已建立 LTP | PMID:34908526 (PMC8798046) | 高 |
| CaMKII 磷酸化 GluA1 S831 | 磷酸化特异性抗体 + 点突变实验 | PMID:30359599 (PMC6214363) | 高 |
| αCaMKII T286A 突变→BTSP 几乎消失（2.3 vs 8.0 mV 斜坡） | T286A 敲入小鼠在体+脑片记录 | PMID:37672577 (PMC10482326) | 高 |
| T286A 激活衰减：1.9 s（突变体）vs 8.2 s（野生型） | 荧光 CaMKII 传感器时间分辨成像 | PMID:37672577 | 高 |
| DDSC：CaMKII 在平台电位后 10–100 s 延迟弥散激活 | 2pFLIM + FRET 传感器（2dV-Camui）脑片 | PMID:39385027 (PMC11540904) | 高（脑片）|
| DDSC 由 IP₃ 依赖 ER 钙释放驱动 | xestospongin C / U73122 / thapsigargin 药理学 | PMID:39385027 | 高（脑片）|
| paAIP2 在 15–30 s 窗口阻断 → BTSP 消失 | 光遗传 CaMKII 抑制，精准时间窗口 | PMID:39385027 | 高（脑片）|

## 连接

- [[nmda-receptor]] — Ca²⁺ 内流激活 CaMKII（LTP 模式）；NMDA 受体也是平台电位 Ca²⁺ 的主要来源之一（84% BTSP 贡献）
- [[ltp]] — CaMKII 是 LTP 诱导和维持的必要分子机器（快速局部模式）；T286 自磷酸化支持短期自主激活
- [[ampa-receptor]] — CaMKII 磷酸化 GluA1 S831（提高电导）和 TARP polybasic region（扩散陷阱捕获受体），双轨道共同驱动 AMPA 受体突触数量净增 = LTP 物理实现
- [[tarp-auxiliary-subunit]] — TARP γ-2/γ-8 的 C 末端 polybasic region 是 CaMKII 在 LTP 中的关键突触后底物；磷酸化解除静电掩蔽，使 PDZ 配体暴露，PSD-95 亲和力骤升，受体被捕获锁定（#184）
- [[btsp]] — CaMKII 的延迟弥散激活（DDSC）是 BTSP 时序整合的分子基础；T286A 突变→BTSP 几乎消失
- [[dendritic-computation]] — DDSC 将树突钙平台电位（树突计算的输出）转换为秒级 CaMKII 信号
- [[voltage-gated-calcium-channels]] — L 型 Cav1.2/1.3 通道的大量 Ca²⁺ 内流触发 PLCβ→IP₃→ER→DDSC 链
- [[three-factor-learning-rule]] — CaMKII 是三因素规则中 Hebbian 因子的分子读出器；在 BTSP 中，DDSC 使 CaMKII 充当"资格痕迹整合器"和第三因素的时序桥梁

## 未解问题

- Q-camkii-subunit-exchange：CaMKII 的亚基交换假说（磷酸化状态在蛋白质更新中通过亚基替换传递）是否在体内得到验证？这能否解释 E-LTP 在蛋白降解情况下的持久性？
- Q-camkii-maintenance-lifetime：CaMKII 的自主活化状态在体内能持续多久？与记忆的实际时间跨度相比有多大差距？
- Q-camkii-ddsc-synapse-specificity：DDSC 是树突弥散的，但 BTSP 是突触特异性的——突触特异性从何而来？弥散 CaMKII 如何选择性增强带有资格痕迹的突触？
- Q-camkii-two-modes-interaction：当一个树突同时发生 LTP 诱导（NMDA 快速激活）和 BTSP 诱导（平台电位→DDSC），两种 CaMKII 激活模式如何相互作用？是否存在竞争、饱和或协同？

## 修订历史

- 2026-06-28 · 修订（rev4）· 基于《AMPA 受体的突触之旅：TARP 辅助亚基》(#184) · LTP 模式机制列表新增步骤6（TARP polybasic region 磷酸化→扩散陷阱）和步骤7（GluA1+TARP 双轨道）；连接新增 [[tarp-auxiliary-subunit]]；key_sources 新增 4 条 TARP 来源（PMID:15664178/20670832/27667007/36223737）；source_articles 新增 #184
- 2026-05-26 · 创建 · 基于《NMDA 受体：突触的巧合检测器》一文 · 初始置信度：高
- 2026-09-23 · 修订（rev3）· 基于《记忆的雕塑家》(#153) · 新增 CaMKII→GEF→Rac1/RhoA→LIMK→cofilin 轴作为结构可塑性的分子路径（LTP 诱导后的形态学输出）；CaMKII 在 PSD 的物理迁移和锚定（Nicoll & Schulman 2023 综述支持）；Rac1 平行路径（Saneyoshi 2025：不依赖 CaMKII 激酶活性可独立诱导结构 LTP）；related 新增 dendritic-spine、cofilin-actin-spine；source_articles 新增 #153
- 2026-09-20 · 修订（rev2）· 基于《BTSP的分子秒表》一文（#150）· 核心更新：区分 CaMKII 两种激活模式（LTP 快速局部 vs BTSP DDSC）；DDSC 机制（Jain 2024, PMID:39385027）；αCaMKII T286A 证据（Xiao 2023, PMID:37672577）；T286 自磷酸化在 BTSP 中的作用（8.2 s vs 1.9 s）；新增连接：btsp、dendritic-computation、voltage-gated-calcium-channels、three-factor-learning-rule；新增未解问题：Q-camkii-ddsc-synapse-specificity、Q-camkii-two-modes-interaction

## 来源文章

- [[2026-05-26-nmda-receptor-ltp]]
- [[2026-09-20-btsp-camkii-molecular-timekeeper]]
- [[2026-09-23-dendritic-spine-structural-plasticity]]

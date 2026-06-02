---
title: tau 蛋白病理
slug: tau-pathology
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-06-29
updated: 2026-06-29
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, disease]
related: [alzheimers-disease, ltp, amyloid-beta-oligomers, engram-cells, hippocampal-circuit, bdnf, pattern-completion, nmda-receptor]
prerequisites: [ltp, nmda-receptor, amyloid-beta-oligomers]
opens_questions: [Q-tau-01, Q-tau-02]
source_articles: [2026-06-29-tau-pathology-alzheimer]
key_sources: ["PMID:26631930", "PMID:1759558", "PMID:11520930", "PMID:28678775", "PMID:26691836", "PMID:22365544", "PMID:26635213"]
---

# tau 蛋白病理 (Tau Pathology)

> **一句话定义**：tau 蛋白在阿尔茨海默病中被 CDK5/GSK-3β 激酶风暴过磷酸化、从轴突错位至树突棘造成突触损伤、聚合成 PHF/NFT，并以朊蛋白样构象种子沿 Braak I→VI 分期在神经回路中蔓延扩散。

## 当前理解

tau 是 MAPT 基因编码的天然无序蛋白，正常功能为稳定微管和维持轴突运输。在 AD 中，Aβ 诱发的 Ca²⁺ 过载（CDK5/p25 路径）和胰岛素信号受阻（GSK-3β 路径）使 tau 过磷酸化程度达正常的约 25 倍，导致三条并行毒性通路：

1. **轴突破坏**：tau 脱离微管 → 微管不稳定 → 轴突运输瘫痪
2. **突触毒性**：tau 错位至树突棘 → 招募 Fyn/锚定 NR2B → Ca²⁺ 过载；同时 TTLL6 错位 → spastin 切割树突微管 → 线粒体断供 → 棘消失（tau KO 保护 Zempel & Mandelkow 2015）
3. **聚合传播**：tau → 低聚物（最毒）→ PHF/SF（cryo-EM R3+R4 核心，cross-β/β-helix 折叠）→ NFT；朊蛋白样构象种子跨突触传播（de Calignon 2012）

Braak 分期（I-VI）反映 tau 沿神经解剖连接的刻板顺序扩散。FTD-MAPT 突变（>50 种）证明 tau 具有独立于 Aβ 的神经毒性。

**不确定性**：tau 低聚物 vs 成熟 NFT 的相对毒性贡献；突触内 vs 细胞外液传播的相对权重；干预最佳时间窗的分子标志物。

## 关键机制

### 正常 tau

- 天然无序蛋白（IDP），稳定微管，维持轴突运输极性
- 成人大脑：6 种同种型（3R/4R × 0-2 个 N 端插入），3R:4R ≈ 1:1
- 轴突专属分布：AIS 的 AnkyrinG-βIV 网络过滤维持
- 正常磷酸化：2-3 个磷酸基团，短暂可逆调控微管结合

### 病理磷酸化与激酶

- **CDK5/p25**：Aβ → Ca²⁺ → calpain 切割 p35→p25 → CDK5/p25 过活化
- **GSK-3β**：Aβ → 胰岛素信号受阻 → Akt↓ → GSK-3β 去抑制；与 CDK5 形成正反馈（CDK5 priming 位点）
- **MARK**：磷酸化 KXGS 序列，触发 tau 初始脱离微管
- 其他：JNK、p38 MAPK、DYRK1A（priming）
- AD tau：50-90 个磷酸基团（正常的约 25 倍）（Iqbal et al. 2016）

### 关键磷酸化位点与生物标志物

| 位点 | 生物标志物意义 |
|------|--------------|
| Ser202/Thr205（AT8）| 最早期 NFT 标志 |
| Thr181（p-tau181）| 血浆早期 AD 诊断生物标志物 |
| Thr231（p-tau231）| 可能在 Aβ 积累最早阶段即升高 |
| Ser396/Ser404（PHF1）| PHF 纤维核心相关，晚期标志 |

### PHF/NFT 的原子结构（Fitzpatrick 2017）

- 核心：两条相同原纤维，由 **R3+R4 MT 结合重复序列**构成
- 折叠：cross-β/β-helix 杂化（全新折叠类型）
- PHF vs SF：原纤维本身相同，仅原纤维间接触界面不同
- 模糊外壳（fuzzy coat）：无序 N/C 端，含大多数磷酸化位点

### Braak 分期

| 分期 | 区域 | 临床状态 |
|------|------|--------|
| I-II | 内嗅皮层 II 层（EC-II）、旁内嗅区 | 无症状 |
| III-IV | 海马 CA1、杏仁核、基底前脑 | MCI 至轻度 AD |
| V-VI | 全联合皮层 | 中至重度痴呆 |

### tau 传播机制

1. 神经元通过外泌体或非传统分泌途径释放 tau
2. 邻近神经元通过大胞饮或受体介导内吞摄取
3. 错误折叠 tau 逃出内体 → 构象种子 → 诱导内源性 tau 发生相同构象变化
4. 新种子再次分泌，沿解剖回路蔓延

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| tau 过磷酸化约 25 倍，NFT 比斑块更能预测认知衰退 | 尸检比较；神经心理测试相关性 | Iqbal et al. 2016 (PMID:26631930) | 高 |
| NFT 刻板 Braak I-VI 分布反映解剖连接传播 | 83 例尸检脑，银染分期 | Braak & Braak 1991 (PMID:1759558) | 高 |
| tau 错位至树突棘通过 TTLL6-spastin 破坏微管 → 棘丢失；tau KO 保护 | 原代神经元培养 + Aβ 处理 + 活细胞成像 | Zempel & Mandelkow 2015 (PMID:26691836, PMC4687341) | 高 |
| tau 从 EC 跨突触传播至海马；与内源性 tau 共聚合 | 转基因小鼠（EC 特异性 P301L tau 表达）| de Calignon et al. 2012 (PMID:22365544) | 高 |
| AD PHF/SF 核心由 R3+R4 组成，cross-β/β-helix 折叠，3.4-3.5 Å | 患者脑组织 cryo-EM | Fitzpatrick et al. 2017 (PMID:28678775) | 高 |
| MAPT 突变（>50 种）导致 FTD，无 Aβ 即可致病 | 遗传学；家系研究；尸检病理 | Lee et al. 2001 (PMID:11520930) | 高 |

## 连接

- [[alzheimers-disease]] — tau 病理是 AD 的核心损伤机制；NFT 比斑块更预测认知衰退
- [[amyloid-beta-oligomers]] — Aβ 是 tau 过磷酸化的上游触发器（Ca²⁺/CDK5/GSK-3β 通路）
- [[ltp]] — tau 过磷酸化破坏 LTP 所需的突触机器（与 Aβ 通路并行）
- [[nmda-receptor]] — 错位 tau 招募 Fyn 锚定 NR2B，加剧突触外 NMDA 受体过激活
- [[bdnf]] — tau 错位封闭 BDNF/TrkB 信号的突触端点，与 BDNF 截断形成双重打击
- [[engram-cells]] — AD 早期 tau 破坏印迹细胞的突触权重，与 Aβ 诱发的沉默印迹协同
- [[hippocampal-circuit]] — NFT 在 CA1 累积（Braak III-IV）直接损伤 CA3→CA1 模式补全回路
- [[pattern-completion]] — CA1 NFT 损伤使模式补全（输入→完整记忆）效率下降

## 未解问题

- **Q-tau-01（高优先级）**：tau 低聚物 vs 成熟 NFT 的相对毒性——低聚物是主要毒性物种，NFT 是保护性封存，还是两者均毒？活体实验难以分离。
- **Q-tau-02（中优先级）**：EC-II 神经元（内嗅皮层星形细胞，网格细胞先祖区域）为何优先受累？是 tau 表达量更高，还是代谢特性（高活动频率、高 Ca²⁺ 需求）使其更脆弱？

## 修订历史

- 2026-06-29 · 创建 · 基于《形状即命运：tau 蛋白分子蜕变》一文（第 65 篇）· 初始置信度：高；填补 alzheimers-disease.md 长期悬空引用 [[tau-pathology]]

## 来源文章

- [[2026-06-29-tau-pathology-alzheimer]]

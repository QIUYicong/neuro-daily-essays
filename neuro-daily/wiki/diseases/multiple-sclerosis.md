---
title: 多发性硬化
slug: multiple-sclerosis
domain: diseases
type: disease
status: established
confidence: high
created: 2026-06-28
updated: 2026-06-28
revision_count: 1
dimensions: [molecular, cellular, synaptic, brain-region, whole-brain-network, cognition, disease]
related: [oligodendrocyte, adaptive-myelination, stdp, action-potential, neuroinflammation, glymphatic-system, myelin-basic-protein, saltatory-conduction, oligodendrocyte-precursor-cell]
prerequisites: [oligodendrocyte, action-potential, adaptive-myelination]
opens_questions: [Q-ms-remyelination-crispr-human, Q-ms-ebv-mechanism, Q-ms-btk-microglia-role]
source_articles: [2026-06-28-multiple-sclerosis-myelin-computation]
key_sources: ["PMID:29320652", "PMID:18931697", "PMID:27248601", "PMID:22801498", "PMID:26585800", "PMID:39384784", "PMID:35182510", "PMID:24871874"]
---

# 多发性硬化 (Multiple Sclerosis, MS)

> **一句话定义**：多发性硬化是中枢神经系统自身免疫性炎性脱髓鞘病，T/B 淋巴细胞攻击髓鞘和少突胶质细胞，导致传导延迟、时序离散、异位放电和继发性轴突退行性变——它是理解髓鞘作为神经时序计算基础设施的最清晰天然实验。

## 当前理解

我们现在认为，MS 是一种**双相疾病**：

1. **炎症期**（复发阶段，以 RRMS 为代表）：CD4+ Th1/Th17 T 细胞和 CD20+ B 细胞穿越血脑屏障，攻击髓鞘蛋白（MBP、PLP、MOG），触发急性脱髓鞘灶。B 细胞不只产生抗体，更重要的是作为抗原呈递细胞（APC）放大 T 细胞应答——抗 CD20 单抗（ocrelizumab）的显著疗效（PMID: 27248601）证明了 B 细胞在此的核心角色。

2. **神经退行性变期**（进展阶段，以 SPMS/PPMS 为代表）：急性炎症减弱，但**缓慢扩展的病变（SELs）**边缘的小胶质细胞持续活化，形成铁聚积的环状结构，驱动慢性轴突丢失和脑萎缩（PMID: 29320652）。

**MS 的核心计算损伤**是对神经时序精度的系统性破坏（Fields 2015，PMID: 26585800）：脱髓鞘使轴突传导从精确的 50–120 m/s 降低至 <5 m/s 甚至传导阻断，将毫秒级的时序信号变成无效的延迟噪声。这解释了为什么**信息处理速度**是 MS 最早受损的认知功能。

**2022 年重大发现**：EBV 感染后 MS 发病风险增加 32 倍（Bjornevik et al. 2022，PMID: 35045247），分子拟态（EBV 蛋白与髓鞘抗原的交叉反应）是目前最强的病因假说。

## 关键机制

### 1. 免疫病理级联

```
EBV 感染（分子拟态触发）
    ↓
外周自身反应性 CD4+ T 细胞活化（Th1/Th17）
    ↓  B 细胞作为 APC 放大
BBB 破坏（IL-17↑ → 紧密连接蛋白↓）
    ↓
CNS 浸润：T 细胞 + B 细胞 + 单核细胞
    ↓
髓鞘攻击（TNF-α / ROS / 补体）
    ↓
急性脱髓鞘灶（active lesion）
    ↓
OPC 招募 → 部分再髓鞘化（RRMS 恢复基础）
         ↕（慢性病灶中 LINGO-1/CSPGs 阻断分化）
小胶质细胞慢性活化 → SEL → 轴突退化 → 不可逆残疾
```

### 2. 脱髓鞘的计算后果

| 后果 | 机制 | 临床表现 |
|------|------|--------|
| 传导延迟 | 跳跃传导失效 → 全长连续传导（v ↓ 90%）| VEP P100 潜伏期延长 |
| 时序离散 | 不同轴突脱髓鞘程度不同 → 传导速度离散 | SDMT 信息处理速度↓ |
| 传导阻断 | 安全系数降至 <1（正常 5–7）| 温度↑ → Uhthoff 现象 |
| 异位放电 | Na⁺ 通道在脱髓鞘节段弥散 → 自发冲动 | Lhermitte 征 |
| STDP 窗口失配 | 传导延迟↑ → 两路输入错失 ±20 ms 窗口 | 学习和记忆形成障碍 |

### 3. 轴突继发性退行性变的双重机制

**代谢解耦**：OL 通过 MCT1 向轴突供应乳酸（PMID: 22801498）；脱髓鞘 → MCT1 供应中断 → 轴突 ATP 耗竭 → 线粒体失能 → 退行性变

**兴奋毒性**：炎症区谷氨酸↑ + 脱髓鞘轴突上异位 NMDA/AMPA 受体 → Ca²⁺ 超载 → 轴突蛋白酶激活 → Waller 退化

**生物标志物**：sNfL（血清神经丝轻链）反映轴突损伤程度；sNfL Z 分数 >1.5 预测未来疾病活动（PMID: 35182510）

### 4. 再髓鞘化失败（慢性病灶）

| 抑制因子 | 来源 | 机制 |
|---------|------|------|
| LINGO-1 | OPC 和星形胶质细胞 | 配体-受体抑制 OL 分化 |
| CSPGs（硫酸软骨素蛋白聚糖）| 胶质瘢痕 | 物理屏障 + 受体抑制分化 |
| Nogo-A | 轴突 | 趋化排斥 OPC 迁移 |
| 髓鞘碎片 | 坏死 OL | 含分化抑制物（亦被巨噬细胞清除失效）|
| M1 极化小胶质细胞 | 慢性炎症 | TNF-α/IFN-γ 对 OL 毒性 |

**2024 年突破**：CRISPR 改造的 hES-OPC（Wagstaff 2024，PMID: 39384784）通过基因编辑赋予 OPC 抵抗趋化排斥物的能力，在慢性 MS 鼠模型（含老年宿主）中实现高效再髓鞘化——提供了细胞疗法绕过慢性微环境抑制的概念验证。

## 临床分型（Lublin 2014，PMID: 24871874）

| 类型 | 特征 | 频率 | 主要病理 | 已批准治疗 |
|------|------|------|--------|---------|
| RRMS | 发作+部分缓解 | 85–90% | 急性炎性脱髓鞘 | 多种 DMT（干扰素、那他珠、ocrelizumab 等）|
| SPMS | RRMS 后持续进展 | ~50% RRMS 转化 | 慢性神经退行为主 | 有限（奥瑞珠单抗/西普尼莫）|
| PPMS | 起病即进展 | 10–15% | 进展性，脊髓受累突出 | Ocrelizumab（首个 PPMS 批准药）|
| CIS | 单次发作，未达 MS 标准 | - | 早期炎症 | 预防性 DMT 可延缓转变 |

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| B 细胞是 MS（包括 PPMS）的核心驱动者 | ocrelizumab III 期 RCT（PPMS 进展↓24%）| PMID:27248601 | 高 |
| OL-MCT1 乳酸支持轴突存活（独立于绝缘） | 条件 MCT1-KO → 轴突退行（小鼠）| PMID:22801498 | 高 |
| 髓鞘化设定传导时序用于 STDP | 白质 DTI FA 随学习变化 + 计算建模 | PMID:26585800 | 中-高 |
| EBV 是 MS 强因果因子（32 倍风险↑）| 百万人前瞻性军队队列血清学 | PMID:35045247 | 高 |
| sNfL Z>1.5 预测未来 MS 活动 | 多队列前瞻性研究 | PMID:35182510 | 高 |
| CRISPR-OPC 克服趋化排斥实现再髓鞘化 | hES-OPC CRISPR 改造，慢性 MS 小鼠 | PMID:39384784 | 中（动物模型）|
| VEP 延迟是最敏感 MS 电生理标志物 | 临床综述 | PMID:18931697 | 高 |
| 胶淋巴 ALPS 指数和白质体积独立预测认知 | 横截面，45 RRMS（小样本）| PMID:41896770 | 低-中 |

## 连接

- [[oligodendrocyte]] — MS 的主要攻击靶细胞（OL 被免疫介导损伤）
- [[adaptive-myelination]] — MS 是髓鞘化时序功能失败的疾病验证（disrupts）
- [[stdp]] — 脱髓鞘时序离散破坏 STDP 所需的 ±20 ms 窗口（indirectly-disrupts）
- [[action-potential]] — 脱髓鞘从根本上改变动作电位传导速度和安全系数（impairs）
- [[neuroinflammation]] — T/B 细胞浸润是 MS 早期病理的驱动者（mechanism-of）
- [[glymphatic-system]] — 胶淋巴功能受损独立预测 MS 认知损害（associated-with）
- [[oligodendrocyte-precursor-cell]] — OPC 是再髓鞘化的执行者；MS 中分化受阻（target-of-repair）
- [[saltatory-conduction]] — MS 破坏的核心传导机制（disrupts）

## 未解问题

- Q-ms-remyelination-crispr-human（高优先级）：CRISPR 改造的 hES-OPC 能否在人类 MS 中安全应用？血脑屏障穿越策略、移植排斥、潜在肿瘤风险等问题如何解决？
- Q-ms-ebv-mechanism（高优先级）：EBV 分子拟态（EBNA1 vs GlialCAM 交叉反应）是 MS 的充分触发原因，还是只是易感因素之一？阻断 EBV 重激活的抗病毒疗法（MK-1654 等）是否能预防 MS？
- Q-ms-btk-microglia-role（中优先级）：BTK 抑制剂（托伯鲁替尼等）同时靶向外周 B 细胞和 CNS 小胶质细胞，对进展型 MS 的疗效主要来自哪个靶点？CNS 穿透的 BTK 抑制剂能否真正延缓 SEL 进展？

## 修订历史

- 2026-06-28 · 创建 · 基于《当绝缘层失守：多发性硬化如何以自身为代价揭示髓鞘对神经时序与认知的隐形贡献》(#183) · 整合 Reich 2018、Franklin 2008、Kappos 2016、Lee 2012、Fields 2015、Wagstaff 2024、Benkert 2022、Song 2026 · 初始置信度：高（机制与分型 established，CRISPR/EBV 为 emerging）

## 来源文章

- [[2026-06-28-multiple-sclerosis-myelin-computation]]

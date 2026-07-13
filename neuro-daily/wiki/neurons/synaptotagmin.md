---
title: 突触结合蛋白（Synaptotagmin）
slug: synaptotagmin
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-05-25
updated: 2026-07-14
revision_count: 5
dimensions: [molecular, synaptic]
related: [SNARE-complex, synaptic-transmission, active-zone, complexin, munc18, voltage-gated-calcium-channels, short-term-synaptic-plasticity]
prerequisites: [SNARE-complex, synaptic-transmission, voltage-gated-calcium-channels]
opens_questions: [Q-syt7-facilitation-mechanism, Q-syt-isoform-specificity]
source_articles: [2026-05-25-synaptic-vesicle-exocytosis, 2026-06-01-voltage-gated-calcium-channels, 2026-06-10-stp-short-term-plasticity, 2026-07-12-complexin-dual-function-vesicle-fusion]
key_sources: ["PMID:22068972", "PMID:23060190", "PMID:37891212", "PMID:31064106", "PMID:28472650", "PMID:29088700", "PMID:28813412"]
---

# 突触结合蛋白（Synaptotagmin）

> **一句话定义**：Synaptotagmin是位于突触囊泡膜上的钙传感器蛋白，通过其C2A和C2B结构域感知局部钙离子浓度升高，并通过物理桥接两层膜、调控SNARE复合体最终拉合来触发毫秒级神经递质释放。

## 当前理解

Synaptotagmin（Syt）家族含17个成员，其中**Syt1、Syt2、Syt9**是快速同步神经递质释放的主要钙传感器（Syt2反应最快，Syt9中等），**Syt7**则参与异步释放和短时程突触易化（PMID:22068972）。

**结构：**
- 单个跨膜区锚定于囊泡膜
- 胞内侧：两个C2结构域（C2A + C2B），通过柔性连接子相连
- C2结构域是由8股β折叠片构成的刚性椭圆形结构，顶端有钙结合环
  - C2A：结合2个Ca²⁺
  - C2B：结合3个Ca²⁺；额外含一个"基本斑块"（basic patch），靶向PI(4,5)P₂

**触发机制（当前最佳模型）：**
1. Ca²⁺进入结合位点后，C2域顶端的钙结合环与磷脂双层疏水浅层结合（部分插入）
2. C2B同时与SNARE复合体和突触前膜的PI(4,5)P₂结合——**跨膜桥接**，将囊泡膜与突触前膜拉近数纳米
3. 解除Complexin对SNARE C端的位阻封闭
4. SNARE拉链急速完成，膜融合发生

磷脂环境使Syt1的表观Ca²⁺亲和力提高**2-3个数量级**，与局部钙浓度高度匹配（PMID:22068972）。

**速度：** Syt1触发融合的延迟约100-200微秒（calyx of Held系统测量）。

## 关键机制

### C2域的钙结合与膜作用
- 钙结合是电中性补偿：Ca²⁺协调Asp残基和水分子，消除C2域顶端的负电荷，暴露疏水面插入膜
- C2B的basic patch（多个Lys和Arg）靶向突触前膜富含PIP₂的区域，是定向结合的关键

### 多传感器模型（Syt1 + Syt7）
Norman et al. (2023) 计算模型显示：Syt1（低钙亲和力，快速反应）负责触发同步释放；Syt7（高钙亲和力，慢速反应）在重复刺激后的残余钙中介导短时程易化（PMID:37891212）。

**Syt7作为短时程易化的专属传感器（2017年更新）**

Jackman & Regehr（2017，PMID:28472650，PMC:PMC5865607）通过4种突触类型的Syt7敲除实验系统证明，Syt7是大多数中枢突触配对脉冲易化（paired-pulse facilitation, PPF）的主要分子传感器：

- **4种突触均受影响**：沙费尔侧支、苔藓纤维、皮层丘脑连接、外侧穿通路的PPF在Syt7 KO后几乎消失（PPR从1.5–2.5降至约1.0）
- **Syt7的分子特性赋予其易化传感功能**：
  - 高钙亲和力（Kd ~1.5 μM），可被残余钙（50–200 nM）激活
  - 慢解离（比Syt1慢约60倍）：激活后在突触前膜驻留数十毫秒，即使残余钙已衰减
  - 不独立触发释放，而是与膜结合后增强Syt1驱动融合的概率（降低能垒2–5 kT）

**机制精确图像**：第一次释放后，残余钙（~100 nM）激活Syt7（高亲和力），Syt7结合突触前膜并维持约50–100 ms的膜结合状态（慢解离）。当第二个动作电位到来时，Syt7-膜结合状态增大了Syt1-Ca²⁺复合体引发融合的概率。数学预测：PPR ∝ (Syt1-bound量) × (Syt7-bound量)，可定量重现实验中的易化幅度。

**频率不变传输**：Turecek et al.（2017，PMID:29088700，PMC:PMC5892411）发现，在小脑浦肯野细胞→深部小脑核（PC→DCN）突触（天然抑制性），Syt7提供的隐藏易化精确抵消depression，使跨5–150 Hz的传输保持频率不变。Syt7 KO后高频下严重depression出现。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Syt1是快速同步释放的主要传感器 | Syt1敲除→同步释放消失；重表达→恢复 | PMID:22068972 | 极高 |
| C2B域对释放比C2A更关键 | 点突变阻断Ca²⁺结合的差异实验 | PMID:22068972 | 高 |
| Syt7介导异步释放与短时程易化 | Syt7敲除 + 双敲除实验 | PMID:37891212 | 中 |
| Syt7是4种中枢突触PPF的主要传感器 | Syt7 KO小鼠4种突触类型PPF消失 | PMID:28472650 (PMC5865607) | 高 |
| Syt7赋予PC→DCN突触频率不变传输 | Syt7 KO消除频率不变性；突触前AAV救援恢复 | PMID:29088700 (PMC5892411) | 高 |
| 磷脂将Syt1表观Ca²⁺亲和力提高2-3个数量级 | 脂质结合实验 | PMID:22068972 | 高 |

## 连接

- [[SNARE-complex]] — Syt1通过物理接触调控SNARE最终拉合
- [[synaptic-transmission]] — Syt是触发突触传递的关键开关
- [[complexin]] — Syt1与Complexin协同：Syt解除Complexin锁定；2017年晶体结构（PMID:28813412）揭示二者通过"三方界面"（第二个Syt1 C2B的HA螺旋直接拼接进complexin中央螺旋末端，与SNARE共同形成六螺旋束，界面990 Å²）在Ca²⁺到来前共同锁定预融合态，界面不涉及Ca²⁺结合位点本身，解释了[[synaptotagmin]]激活后如何具体"解锁"complexin
- [[voltage-gated-calcium-channels]] — CaV2.1（P/Q型）/CaV2.2（N型）开放产生局部Ca²⁺浓度暴升是Syt1激活的直接上游；Syt1的C2B域与CaV2通道的synprint位点预结合，实现纳米域预组织
- [[short-term-synaptic-plasticity]] — Syt7是STP易化（facilitation）的主要分子传感器；Syt1是快速同步释放的传感器，两者分工明确
- [[munc18]] — 作用于SNARE组装的更上游阶段：Munc18-1在Syntaxin闭合构象下充当模板、预先对齐SNARE基序N端；Synaptotagmin则在组装完成后的钙触发阶段介导最终解锁，二者分工覆盖囊泡融合"组装启动→钙触发解锁"的完整链路

## 未解问题

- Q-syt7-facilitation-mechanism：Syt7通过直接调控SNARE还是纯通过磷脂膜结合改变融合能垒？超分辨率实验正在进行（更新：已知Syt7是主要易化传感器，精确机制仍open）
- Q-syt-isoform-specificity：不同突触类型为何选择不同Syt亚型？是否与精确的钙动力学匹配有关？
- Q-stp-syt7-human：人类皮层突触的Syt7表达模式和易化特性是否与啮齿类系统性不同？

## 修订历史

- 2026-05-25 · 创建 · 基于《神经信号的化学渡口》一文 · 初始置信度：高
- 2026-06-01 · 修订 · 基于《神经元的三重钙门》一文 · 明确钙通道（CaV2.1/2.2）通过synprint位点与Syt1 C2B域的预结合机制（约20 μM Ca²⁺时最强）；将悬空引用 calcium-channel 更新为 voltage-gated-calcium-channels
- 2026-06-10 · 修订 · 基于《瞬息之变：短时程突触可塑性》一文 · 大幅扩展Syt7机制：加入4种突触PPF KO实验（Jackman & Regehr 2017）、Syt7的钙亲和力/慢解离特性、频率不变传输（Turecek 2017）；将 short-term-synaptic-plasticity 加入 related；解答了悬挂已久的 Q-syt7-facilitation-mechanism（主体机制确立，精确构象仍open）
- 2026-07-12 · 修订 · 基于《刹车还是油门？Complexin 如何用同一段螺旋同时钳制与催化囊泡融合》一文 · 在complexin连接条目中补充Zhou 2017三方界面结构机制细节，新增key_source（PMID:28813412）
- 2026-07-14 · 修订 · 基于《一把先关上的锁：Munc18-1 如何在"堵住"SNARE的同时，充当组装它的模板》一文 · 新增munc18交叉链接，说明其与Synaptotagmin在囊泡融合链路中的分工（组装启动 vs 钙触发解锁）

## 来源文章

- [[2026-05-25-synaptic-vesicle-exocytosis]]
- [[2026-06-01-voltage-gated-calcium-channels]]
- [[2026-06-10-stp-short-term-plasticity]]

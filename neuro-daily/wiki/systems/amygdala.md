---
title: 杏仁核
slug: amygdala
domain: systems
type: region
status: established
confidence: high
created: 2026-05-30
updated: 2026-06-24
revision_count: 2
dimensions: [cellular, microcircuit, brain-region, behavior, cognition, disease]
related: [fear-conditioning, fear-extinction, ltp, hippocampal-circuit, dopamine-reward-prediction-error, norepinephrine-locus-coeruleus, basal-ganglia, ptsd, prefrontal-cortex, reconsolidation]
prerequisites: [ltp, synaptic-transmission, nmda-receptor]
opens_questions: [Q-fear-human-amygdala-specificity, Q-fear-low-road-function]
source_articles: [2026-05-30-amygdala-fear-memory, 2026-06-24-fear-extinction-circuits]
key_sources: ["PMID:24908482", "PMID:22129456", "PMID:20393190", "PMID:18615014", "PMID:19748076", "PMID:35520882"]
---

# 杏仁核 (Amygdala)

> **一句话定义**：颞叶深部由多个亚核组成的复合核团，是大脑情绪记忆（尤其是恐惧）的写入与表达中枢，通过外侧核的LTP学习CS-US关联，通过中央核输出防御反应，通过与前额叶和海马的三角回路实现情境依赖的情绪调控。

## 当前理解

我们现在认为，杏仁核不是一个统一的"情绪中枢"，而是由功能截然不同的亚结构组成的微回路复合体。其中基底外侧杏仁核复合体（BLA，包括外侧核LA和基底核BA）是感觉信息的输入与可塑性发生地，中央核（CeA）是防御行为的输出引擎，而散布其间的插入细胞（ITC）是恐惧与消退之间的可塑性闸门。

恐惧记忆的写入本质是LA突触的LTP——与海马LTP使用相同的NMDA→CaMKII→AMPA插入分子机器。恐惧消退不是记忆抹除，而是IL皮层→腹侧ITC→CeM的新抑制回路对原始恐惧回路的竞争性压制。两套记忆痕迹在杏仁核及其前额叶-海马连接网络中并行共存，情境信号决定哪套痕迹占主导。

## 关键机制

### 亚核架构
- **外侧核（LA）**：首要感觉输入站；CS（音调）从听觉丘脑/皮层、US（电击）从躯体感觉丘脑汇聚于此；是LTP发生的核心位点；约80%为兴奋性锥体神经元，~20%为GABAergic中间神经元；条件反射后约20%神经元形成稀疏CS响应（恐惧印迹）
- **基底核（BA）**：包含恐惧神经元（投射PL皮层，条件反射后CS+）和消退神经元（投射IL皮层，消退后CS+）两个功能截然不同的群体；接收海马情景信息，决定哪群神经元主导
- **中央核（CeA）**：外侧部（CeL）含PKCδ+（关闭细胞）和SOM+（开启细胞），形成局部去抑制回路；内侧部（CeM）是主要输出，投射至PAG（冻结）、下丘脑（自主神经）、BNST（持续焦虑）

### 插入细胞（ITC）
- 散布于BLA与CeA之间的GABAergic神经元群
- **背侧ITC（ICMMD）**：LA→ICMMD→抑制ICMMV→CeM去抑制 → 恐惧表达
- **腹侧ITC（ICMMV）**：BLA+IL皮层→ICMMV→直接抑制CeM → 消退表达
- ITC上富含µ-阿片受体，阿片系统可调节消退
- 选择性损毁ITC → 恐惧获得正常，消退表达严重受损（Likhtik et al. 2008）

### 恐惧表达的完整输出
CeM → PAG → 冻结行为；CeM → 下丘脑 → 自主神经激活（心率↑）；CeM → 下丘脑室旁核 → HPA轴 → 皮质醇；CeM → BNST → 持续焦虑/广泛性焦虑

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|---------|------|--------|
| LA突触LTP是恐惧记忆因果底物 | 光遗传LTP→恐惧；LTD→消除恐惧；再LTP→恢复恐惧 | PMID:24896183 | 高 |
| 条件反射后约20% LA神经元发展CS响应（稀疏代码） | 多通道电极记录+行为范式 | PMID:24908482 (PMC4103014) | 高 |
| ITC神经元是消退表达的必要条件 | 选择性免疫毒素损毁ITC→消退表达缺陷 | PMID:18615014 | 高 |
| BA中恐惧/消退神经元双群切换 | 多单元记录+逆行标记 | PMID:18615015 | 高 |
| vmPFC/IL激活强度预测消退回忆质量 | 人类fMRI多研究汇总 | PMID:22129456 (PMC4942586) | 中-高 |

## 连接

- [[ltp]] — LA突触LTP是恐惧记忆写入的分子机器
- [[fear-conditioning]] — 外侧核LTP的行为诱导范式
- [[fear-extinction]] — 消退作为竞争性抑制记忆，依赖ITC和IL皮层
- [[hippocampal-circuit]] — 海马提供情景信号给BA，决定恐惧/消退哪套记忆被调取
- [[norepinephrine-locus-coeruleus]] — 蓝斑NE投射通过β-肾上腺素受体增强杏仁核LTP和恐惧记忆巩固
- [[dopamine-reward-prediction-error]] — VTA DA投射到杏仁核调节奖励关联（与恐惧回路并行）
- [[engram-cells]] — LA恐惧印迹细胞（~20%稀疏）与海马场所细胞印迹遵循相同的竞争选择逻辑
- [[ptsd]] — 杏仁核慢性过激是PTSD的核心病理之一；BLA→IL前馈抑制使vmPFC失效
- [[prefrontal-cortex]] — vmPFC/IL通过BLA消退细胞和ITC抑制杏仁核输出；应激下BLA反向压制vmPFC
- [[reconsolidation]] — 记忆重激活时LA突触短暂进入可塑性窗口，为记忆更新提供机会

## 未解问题

- Q-fear-human-amygdala-specificity（高优先级）：人类杏仁核功能架构与啮齿类的保守程度
- Q-fear-low-road-function（中优先级）：丘脑"低路"直接投射的恐惧学习独立贡献
- Q-fear-itc-bidirectionality（中优先级）：ITC在恐惧重现时的具体再平衡机制

## 修订历史

- 2026-05-30 · 创建 · 基于《当杏仁核学会恐惧》一文 · 初始置信度：高
- 2026-06-24 · 修订 · 新增PTSD中杏仁核过激的神经影像证据（Milad 2009）、BLA→IL前馈抑制在应激下破坏消退的机制（Maren 2022）、重巩固窗口与LA突触的关联；更新related、连接、key_sources

## 来源文章

- [[2026-05-30-amygdala-fear-memory]]
- [[2026-06-24-fear-extinction-circuits]]

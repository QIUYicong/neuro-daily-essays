---
title: vmPFC-杏仁核情绪调节回路
slug: vmPFC-amygdala-circuit
domain: circuits
type: mechanism
status: mainstream
confidence: medium-high
created: 2026-07-11
updated: 2026-07-11
revision_count: 1
dimensions: [microcircuit, brain-region, whole-brain-network, behavior, cognition, disease]
related: [amygdala, prefrontal-cortex, fear-extinction, fear-conditioning, memory-reconsolidation, hippocampal-circuit, pv-interneurons, hpa-axis]
prerequisites: [amygdala, fear-extinction, fear-conditioning, prefrontal-cortex]
opens_questions: [Q-vmPFC-IL-01, Q-vmPFC-IL-02, Q-vmPFC-IL-03]
source_articles: [2026-07-11-vmPFC-amygdala-emotion-regulation]
key_sources: ["PMID:20962768", "PMID:17882236", "PMID:24673881", "PMID:37480845", "PMID:17217927"]
---

# vmPFC-杏仁核情绪调节回路 (vmPFC-Amygdala Emotion Regulation Circuit)

> **一句话定义**：前额叶内侧皮层通过两个功能对立的亚区（PL 促进恐惧表达、IL 通过 ITC 闸门抑制 CeA 恐惧输出）对杏仁核实施双向调控；该回路在 PTSD 中因 vmPFC 功能不足而断裂，是消退治疗困难的神经学根源。

## 当前理解

我们现在认为，前额叶内侧部（mPFC）对杏仁核的调控并非单向"抑制"，而是通过两个解剖上相邻、功能上对立的亚区实施双向调控：

- **前边缘皮层（PL，对应人类 dmPFC 部分）**：促进恐惧表达，通过激活杏仁核基底外侧区（BLA）的恐惧细胞→中央核（CeA）输出通路
- **下边缘皮层（IL，对应人类 vmPFC）**：压制恐惧表达，通过激活插入细胞（ITC）的腹侧群，后者对 CeA 内侧部（CeM）施加 GABAergic 抑制

这一双向架构的功能意义是：同一条件性刺激（CS）在不同情景下可触发截然不同的响应——危险情景中 PL 主导（恐惧表达），安全情景中 IL 主导（恐惧压制）。

PTSD 的核心神经回路缺陷体现在 vmPFC/IL 功能不足（激活↓），使 ITC 无法有效抑制 CeM，杏仁核处于持续解抑制状态——这是 PTSD 患者消退学习困难的神经学根源。

## 关键机制

### 回路架构（由背侧到腹侧）

```
PL（前边缘皮层）─────────→ BLA 恐惧细胞 ──→ CeM ──→ 恐惧输出（PAG/下丘脑/BNST）
                                  ↑                  ↑
                              LA 感觉输入      ↑ 去抑制
                                         背侧 ITC
                                          │ 抑制
                                      腹侧 ITC
                                          ↑
IL（下边缘皮层）── 直接投射 ──→ 腹侧 ITC ──────────→ CeM（抑制）
```

### PL → 恐惧表达

- PL 投射至 BLA 的恐惧细胞（条件反射后 CS+的群体）
- 药理失活 PL（muscimol）→ 恐惧**表达**显著降低（but 不影响消退记忆）
- 机制：PL 通过促进 BLA→CeA 传导实现"选择性放大"威胁信号

### IL → 消退表达（ITC 闸门机制）

- IL 直接投射至腹侧 ITC（ICMMV），形成 IL→ITC→CeM 抑制通路
- 药理失活 IL → 消退获得受损（within-session），次日消退回忆严重降低
- 分子机制：IL 神经元在消退训练结束期出现 burst firing；此 burst 幅度预测次日消退质量
- IL→ITC 突触需要 NMDA 受体：IL 内 NMDA 拮抗剂灌注 → 消退巩固受损

### ITC 双层逻辑闸门

| 状态 | 活跃 ITC 群 | 对 CeM 的净效应 |
|------|------------|----------------|
| 恐惧表达 | 背侧 ITC（ICMMD）抑制腹侧→解除对 CeM 的抑制 | CeM 激活→恐惧输出 |
| 消退表达 | 腹侧 ITC（ICMMV）直接抑制 CeM | CeM 沉默→恐惧压制 |

### eCB-CB1R 在 vmPFC→BLA 突触的第三层调控

- vmPFC→BLA 投射末梢上表达 CB1 受体（Cnr1 基因）
- 光遗传激活 vmPFC→BLA 投射 → BLA 局部内源性大麻素（eCB）释放，时序与消退训练匹配
- CRISPR 特异性敲除 vmPFC→BLA 末梢的 Cnr1 → 消退受损 + 焦虑样行为增加
- dmPFC→BLA 末梢 Cnr1 敲除无此效应（路径特异性）
- 推测机制：vmPFC 激活→ eCB 逆行释放→抑制 BLA 局部 GABA 末梢→BLA 微回路状态调整

### 海马作为情景门控

- 腹侧海马（vHPC）→ BLA 基底核的消退细胞提供情景安全信号
- vHPC 失活 → 恐惧表达和消退记忆均受损（情景信号中断）
- 消退回忆中 vmPFC 与海马**协同激活**（Milad 2007：vmPFC-海马功能连接正相关，与消退质量正相关）
- 海马损伤→消退回忆情景依赖性丧失（在错误情景中触发消退 OR 在正确情景中不触发消退）

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| PL 失活→恐惧表达↓（不影响消退记忆）| muscimol 失活，大鼠恐惧条件反射 | PMID:20962768 | 高 |
| IL 失活→消退获得/记忆受损（不影响恐惧表达）| muscimol 失活，大鼠 | PMID:20962768 | 高 |
| IL→腹侧 ITC→CeM 抑制（直接突触证据）| 解剖追踪 + 电生理，大鼠/小鼠 | PMID:25753409, PMID:17882236 | 高 |
| 消退回忆中 vmPFC + 海马激活，与消退质量相关 | fMRI，人类 | PMID:17217927 | 高 |
| vmPFC 损伤→杏仁核响应增强 + 功能连接升高 | fMRI，人类 vmPFC 损伤 n=4 | PMID:24673881 | 中高（小样本） |
| vmPFC→BLA 末梢 CB1R 对消退记忆形成必要 | 光遗传 + CRISPR，小鼠 | PMID:37480845 | 高 |
| PTSD：vmPFC 激活不足 + 杏仁核过活动（双重失衡）| fMRI 综述，20 年文献 | PMID:29734226 | 高（多研究一致）|
| 认知重评通过外侧 PFC（非 vmPFC）调制杏仁核 | fMRI 元分析，48 项研究 | PMID:23765157 | 高 |

## 连接

- [[amygdala]] — 杏仁核（BLA/ITC/CeA）是回路的效应器端
- [[fear-extinction]] — IL→ITC 回路是消退记忆提取的神经执行机制
- [[fear-conditioning]] — PL 驱动恐惧表达的 BLA 侧连接
- [[prefrontal-cortex]] — vmPFC/IL 是前额叶皮层的情绪调节亚区
- [[hippocampal-circuit]] — 海马为回路提供情景门控信号
- [[memory-reconsolidation]] — vmPFC 在再巩固窗口消退中也起关键作用
- [[hpa-axis]] — HPA 轴 GC 反馈与 vmPFC→杏仁核回路的交叉调控
- [[pv-interneurons]] — PV+ 中间神经元在 vmPFC-BLA 间的局部调控

## 未解问题

- Q-vmPFC-IL-01：大鼠 IL 与人类 vmPFC 的精确同源区域（Brodmann 区）是什么？BA25（海马旁回皮层）还是 BA32（前扣带回）？
- Q-vmPFC-IL-02：BLA→vmPFC 反馈投射是否形成恶性循环（BLA 过激活→抑制 vmPFC→vmPFC 更难抑制 BLA）？
- Q-vmPFC-IL-03：在 PTSD 患者中，vmPFC 功能不足是结构萎缩（灰质减少）还是功能性抑制（可逆）？两者比例如何，以及对治疗选择的影响？

## 修订历史

- 2026-07-11 · 创建 · 基于《前额叶如何压制恐惧》(#79) · 初始置信度：中高

## 来源文章

- [[2026-07-11-vmPFC-amygdala-emotion-regulation]]

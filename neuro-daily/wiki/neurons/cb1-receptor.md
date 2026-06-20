---
title: CB1 大麻素受体
slug: cb1-receptor
domain: neurons
type: mechanism
status: established
confidence: high
created: 2026-08-05
updated: 2026-08-05
revision_count: 1
dimensions: [molecular, synaptic, cellular]
related: [endocannabinoid-system, voltage-gated-calcium-channels, synaptic-transmission, ltd, fear-extinction, amygdala, cerebellar-ltd]
prerequisites: [synaptic-transmission, voltage-gated-calcium-channels]
opens_questions: [Q-ecb-03, Q-ecb-04]
source_articles: [2026-08-05-endocannabinoid-retrograde-signaling]
key_sources: ["PMID:23040807", "PMID:26698193", "PMID:19126760"]
---

# CB1 大麻素受体 (Cannabinoid Receptor Type 1, CB1R)

> **一句话定义**：脑内表达量最高的 G 蛋白偶联受体（GPCR），主要分布于突触前轴突终末（富集于 CCK⁺ GABA 能中间神经元），被内源性大麻素（主要是 2-AG）激活后通过 Gi/o 蛋白抑制 Cav2.2 和腺苷酸环化酶，从而减少神经递质释放——是内源性大麻素系统逆行调控突触传递的核心效应器。

## 当前理解

CB1R 于 1988 年被克隆，是第一个鉴定的大麻素受体。它是脑内最丰富的 GPCR，反映了内源性大麻素系统在突触调控中的基础地位。

CB1R 的核心功能是"翻译"逆行脂质信号：当突触后神经元通过 DGLα 合成 2-AG 并释放，2-AG 逆向扩散至突触前，激活 CB1R 的 Gi/o 蛋白，Gβγ 亚基直接抑制 Cav2.2（N型）Ca²⁺ 通道，Gαi 亚基抑制腺苷酸环化酶降低 cAMP，两者协同使突触前 Ca²⁺ 流入减少、神经递质释放减弱。

**关键分布特点**：CB1R 在皮层和海马高度富集于 **CCK⁺（胆囊收缩素阳性）篮状细胞**终末，浓度约是 PV⁺ 细胞的 5–10 倍。这种选择性使 eCB 系统优先调制"灵活性"抑制（CCK⁺）而保留"精确时序"抑制（PV⁺），允许活跃的兴奋性网络通过 eCB 实现局部去抑制。

## 关键机制

### 信号通路

**Gβγ 通路**（短时程效应）：
CB1R 激活 → Gβγ 亚基从 Gαβγ 解离 → 直接结合 Cav2.2（N型）和 Cav2.1（P/Q型）Ca²⁺ 通道 β 亚基 → **电压依赖性抑制**（通道激活右移）→ 突触前 Ca²⁺ 流入下降 → 递质释放减少

**Gαi 通路**（长时程效应）：
CB1R 激活 → Gαi → 抑制腺苷酸环化酶（AC）→ ↓cAMP → ↓PKA → **RIM1α**（Rab3A 互作分子）去磷酸化 → 活动带囊泡对接效率下降 → 释放概率长期降低（eCB-LTD）

**GIRK 激活**（神经元兴奋性抑制）：
CB1R → Gβγ → GIRK（Kir3）通道开放 → K⁺ 外流 → 超极化 → 神经元兴奋性直接降低（见 SSI 慢自我抑制）

### 分布与靶细胞特异性

| 脑区 | 主要靶细胞 | 功能结果 |
|------|-----------|---------|
| 海马/皮层 | CCK⁺ 篮状细胞 | 去抑制（disinhibition），允许锥体细胞网络增强 |
| 小脑 | 平行纤维（兴奋性）终末 | 浦肯野细胞 DSE，运动学习 LTD |
| 杏仁核 BLA | 抑制性+兴奋性终末 | 恐惧消退，AEA 在此浓度尤其重要 |
| 纹状体 | 皮层-纹状体投射终末（谷氨酸能） | 皮层-纹状体 eCB-LTD，习惯形成 |
| 脊髓背角 | Aδ/C 纤维终末 | 下行痛觉调制（与阿片系统协同） |

### 配体偏好

| 配体 | 效能 | 主要受体 | 主要功能 |
|------|------|---------|---------|
| 2-AG | 全激动剂（高） | CB1R，CB2R | DSI/DSE，eCB-LTD |
| AEA | 部分激动剂（低） | CB1R；TRPV1（全） | 杏仁核消退；TRPV1-LTD |
| THC | 部分激动剂 | CB1R（弥散非选择性）| 精神活性、认知损伤 |

### 与其他突触蛋白的关系

- **下游 RIM1α**：eCB-LTD 的关键效应分子；RIM1α 基因敲除选择性消除 eCB-LTD 而不影响 DSI，证明 DSI（短时程）和 LTD（长时程）使用不同下游机器
- **上游 PLCβ（符合探测器）**：mGluR1/5 + Ca²⁺ → PLCβ → DGLα → 2-AG → CB1R；PLCβ 充当"共同激活"才触发的门
- **COX-2 竞争通路**：COX-2 氧化 2-AG → PGE2-G（通过 EP3R 促进兴奋），是 CB1R 激活的潜在拮抗通路

## 关键证据

| 主张 | 证据 | 来源 |
|------|------|------|
| 脑内最丰富 GPCR；主要在突触前 | 放射自显影、免疫荧光分布图 | Lu & Mackie, 2016, PMID:26698193 |
| CB1R 激活通过 Gβγ 抑制 Cav2.2 | 膜片钳+pertussis toxin（PTX）阻断 Gi/o | 多个研究，综合见 Castillo 2012 |
| CCK⁺ 细胞 CB1R 浓度约为 PV⁺ 的 5–10 倍 | 免疫荧光定量 | Lu & Mackie, 2016, PMID:26698193 |
| RIM1α KO 消除 eCB-LTD，不影响 DSI | 遗传敲除+电生理 | Castillo et al., 2012, PMID:23040807 |

## 连接

- [[endocannabinoid-system]] — CB1R 是 ECS 的核心效应器
- [[voltage-gated-calcium-channels]] — CB1R via Gβγ 抑制 Cav2.2
- [[ltd]] — eCB-LTD 通过 Gαi-RIM1α 机制实现
- [[fear-extinction]] — BLA 的 CB1R 激活对恐惧消退因果必要
- [[cerebellar-ltd]] — 小脑平行纤维 LTD 涉及 CB1R 信号

## 未解问题

- Q-ecb-03：SSI（慢自我抑制）中 GIRK 激活是否在体内生理条件下实际发生？
- Q-ecb-04：神经元上的 CB2R（少量表达）与 CB1R 功能是否有分工？

## 修订历史

- 2026-08-05 · 创建 · 基于《逆行的信使》文章 #104 · 初始置信度：高

## 来源文章

- [[2026-08-05-endocannabinoid-retrograde-signaling]]

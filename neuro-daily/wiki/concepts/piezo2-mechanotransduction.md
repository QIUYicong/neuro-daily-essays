---
title: PIEZO2机械转导通道
slug: piezo2-mechanotransduction
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-07-19
updated: 2026-07-19
revision_count: 1
dimensions: [molecular, cellular]
related: [mechanoreceptor-ltmr, somatosensory-cortex, ion-channels, action-potential]
prerequisites: [ion-channels, action-potential]
opens_questions: []
source_articles: [2026-07-19-somatosensory-cortex-body-map]
key_sources: ["PMID:34312536", "PMID:24717433", "PMID:25471886"]
---

# PIEZO2机械转导通道 (PIEZO2 Mechanotransduction Channel)

> **一句话定义**：哺乳动物皮肤轻触觉的主要机械转导离子通道，表达于皮肤低阈值机械感受器（梅克尔细胞和Aβ纤维末梢），将皮肤压力/变形转化为钙离子内流和动作电位；双敲除后小鼠几乎完全丧失轻触感觉行为。

## 当前理解

我们现在认为，PIEZO2是哺乳动物轻触觉的关键分子开关。它是一种大型机械敏感性阳离子通道（PIEZO家族，三聚体结构，每个亚基~38个跨膜域），在机械力施加于膜时开放，允许Na+、K+、Ca²+内流，从而产生快速的内向机械电流（rapidly adapting mechanically activated current, RAMP current）。

PIEZO2与另一家族成员PIEZO1（主要在血管内皮和红细胞）不同，PIEZO2高度富集于背根神经节（DRG）感觉神经元、梅克尔细胞和部分其他特化感受器，与其在触觉中的专职角色一致。

从分子到行为的完整因果链（Ranade et al. 2014, PMC4380172）：
`Piezo2基因` → `PIEZO2蛋白（感觉神经元+梅克尔细胞）` → `机械激活内向电流` → `动作电位` → `轻触觉行为`

## 关键机制

### PIEZO2的双重感受器作用（SA1复合体）

**梅克尔细胞内的PIEZO2**（Woo et al. 2014, PMC4039622）：
- 介导梅克尔细胞自身的机械敏感电流（无Piezo2时，梅克尔细胞体外无MA电流）
- 梅克尔细胞激活后通过突触样接触（可能是谷氨酸能）增强Aβ SAI-LTMR的静态持续放电
- 梅克尔细胞特异性KO→选择性损害静态相，动态相相对保留

**Aβ纤维末梢内的PIEZO2**：
- 介导动态相（压迫开始时0.2-0.3毫秒极快的受体电位）
- 速度依赖性放电（表征刺激快慢）

结果：梅克尔-神经突复合体的SA1响应是两个PIEZO2感受位点的叠加——神经末梢提供动态相时间码，梅克尔细胞提供静态相持续码。

### PIEZO2的其他定位

- **迈斯纳小体（RA1）**：PIEZO2已被组织学确认，主要在感觉轴突（非板层细胞）
- **帕奇尼小体（RA2）**：功能上依赖PIEZO2（基因敲除影响150 Hz振动响应），但免疫染色阴性——亚细胞定位未解
- **毛囊矛尖状末梢（有毛皮肤）**：PIEZO2参与，但精确位置未知

### 行为证明

双敲除（感觉神经元+梅克尔细胞）小鼠：
- Von Frey细丝测试：几乎无响应
- 无毛皮肤电刺激（神经纤维记录）：大多数SA和RA型纤维的MA电流消失
- 维持正常痛觉（痛觉TRPV1等通道不受影响）

PIEZO2是**专门用于轻触觉**的通道，痛觉的机械伤害感受另有通道（可能是PIEZO1，或未知通道）。

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| PIEZO2主导轻触觉转导 | 双KO小鼠几乎完全丧失轻触行为（多项测试） | Ranade et al. 2014 (PMC4380172) | 高 |
| 梅克尔细胞PIEZO2→静态相 | 梅克尔特异性KO：静态相选择性减弱 | Woo et al. 2014 (PMC4039622) | 高 |
| PIEZO2阳离子通道 | 全细胞膜片钳，机械压力激活内向电流 | Handler & Ginty 2021 (PMC8485761) | 高 |
| Pacinian小体功能依赖但免疫染色阴性 | KO影响高频振动响应；但IHC无信号 | Handler & Ginty 2021 (PMC8485761) | 中等（矛盾） |

## 连接

- [[mechanoreceptor-ltmr]] — PIEZO2是各类LTMR的主要转导通道
- [[ion-channels]] — PIEZO2是机械激活离子通道（与电压门控、配体门控通道并列的第三类）
- [[action-potential]] — PIEZO2开放→去极化→动作电位在Aβ纤维传入中枢

## 未解问题

- 帕奇尼小体中PIEZO2的精确亚细胞定位（功能存在但免疫染色阴性）
- 梅克尔细胞向Aβ-SAI传递信号的具体神经递质
- PIEZO2在Aδ-LTMR和C-LTMR（有毛皮肤）中的精确作用
- 人类PIEZO2功能缺失突变（痛觉保留，轻触严重受损）的完整临床表型

## 修订历史

- 2026-07-19 · 创建 · 基于《皮肤的密码》(#87) · 初始置信度：高

## 来源文章

- [[2026-07-19-somatosensory-cortex-body-map]]

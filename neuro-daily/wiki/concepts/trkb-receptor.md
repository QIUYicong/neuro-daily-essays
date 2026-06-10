---
title: TrkB受体
slug: trkb-receptor
domain: concepts
type: mechanism
status: established
confidence: high
created: 2026-09-11
updated: 2026-09-11
revision_count: 1
dimensions: [molecular, cellular, synaptic, brain-region, cognition]
related: [bdnf, ltp, fear-conditioning, critical-period, adult-neurogenesis, pv-interneurons, camkii, nmda-receptor, p75ntr, synaptic-transmission]
prerequisites: [bdnf, synaptic-transmission, ltp]
opens_questions: [Q-trkb-01, Q-trkb-02, Q-trkb-03, Q-trkb-04]
source_articles: [2026-09-11-trkb-receptor-docking-signaling]
key_sources: ["PMID:12367511", "PMID:19675247", "PMID:16571757", "PMID:19927149", "PMID:12676795", "PMID:10499792", "PMID:22341689"]
---

# TrkB受体 (TrkB Receptor)

> **一句话定义**：结合BDNF（及NT-4）的受体酪氨酸激酶，通过胞内域两个关键磷酸化酪氨酸位点（Y490→Shc-MAPK/PI3K轴；Y816→PLCγ-Ca²⁺-CaMKII轴）将BDNF信号路由到基因表达、神经元存活与快速突触可塑性三条平行通道；截断型TrkB-T1缺乏激酶域，通过竞争抑制和独立的RhoGDI1信号调节BDNF信号的时空范围。

## 当前理解

TrkB（Tropomyosin receptor kinase B，也称NTRK2）是脑内最重要的神经营养因子受体，是BDNF和NT-4/5的高亲和力结合受体。TrkB属于Trk受体酪氨酸激酶家族（TrkA: NGF；TrkB: BDNF/NT-4；TrkC: NT-3）。

**分子架构**：全长TrkB（TrkB.TK+）包含：
- 胞外域：LRR区 + 两个半胱氨酸簇 + 两个Ig样结构域（Ig-C1, Ig-C2，BDNF结合位点）
- 跨膜域
- 胞内域：近膜区（含Y490）+ 激酶域（含Y816活化环）+ C末端尾

**激活机制**：BDNF同源二聚体→两个TrkB分子的Ig-C2域结合→受体同源二聚化→胞内域相互接近→反式自磷酸化激活激酶域（Y706/Y707活化环磷酸化）→激活的激酶进一步磷酸化Y490和Y816。

**两条核心路由**（Minichiello 2002，PMID:12367511）：
- **Y490路由**：Shc结合→Grb2-SOS→Ras→MAPK/ERK→CREB（基因表达，分钟-小时）；同时Grb2-Gab1→PI3K→Akt-mTOR（存活、蛋白合成，分钟-小时）
- **Y816路由**：PLCγ结合→磷酸化激活→IP3+DAG→胞内Ca²⁺释放+PKC激活→CaMKII→AMPA受体磷酸化/插入（突触增强，秒-分钟）；Ca²⁺→钙调磷酸酶→NFATc4（转录，存活）

**关键功能分工**（来自分子敲入实验）：
- 海马LTP：**Y816/PLCγ为主**（Y816F小鼠LTP严重受损，Y490F小鼠LTP基本正常）（PMID:12367511）
- 恐惧记忆获得：**Y816/PLCγ/CaMKII**（Y816F→杏仁核CaMKII激活受损→获得受损）（PMID:19675247）
- 恐惧记忆巩固：**Y490/PI3K/Akt**（Y490F→Akt激活受损→巩固受损）（PMID:19675247）
- LTP的双侧贡献：突触前TrkB（通过PKC增强释放）和突触后TrkB（通过CaMKII增强AMPA响应）均参与LTP（PMID:16571757）

**截断型TrkB（TrkB-T1/T2）**（Fenner 2012，PMID:22341689）：
- 缺乏激酶域，替换为12或11个氨基酸的独特C末端
- TrkB-T1是**成体脑中含量最丰富的TrkB异构体**，在星形胶质细胞和神经发生区（SGZ）高表达
- **Dominant negative**：与TK+形成无活性杂二聚体，降低全长TrkB的自磷酸化效率
- **BDNF扣押**：TrkB-T1内吞BDNF，限制BDNF的胞外扩散范围，维持突触特异性
- **独立信号**：TrkB-T1-C末端→RhoGDI1→RhoA激活→肌动蛋白骨架重塑→filopodia形成（星形胶质细胞形态调节、突触形成）

**BDNF/TrkB在关键期**（Huang 1999，PMID:10499792）：BDNF通过TrkB激活（PLCγ+MAPK路由）驱动PV+中间神经元中Kv3.1和GAD67上调，加速GABA能成熟→更早达到LTP诱发所需的抑制阈值→更早开启关键期。

**BDNF/TrkB在AHN**（Chan 2008，PMID:18718867；Quadrato 2012，PMID:22586092）：BDNF对AHN的作用集中在终末分化阶段（非增殖）；PLCγ→Ca²⁺→NFATc4（钙调磷酸酶依赖的转录因子）是新生神经元存活的必要转录中介；TrkB-PI3K/Akt提供抗凋亡支持。

## 关键机制

```
BDNF二聚体 + 2× TrkB → 二聚化 → 反式自磷酸化
                                        ↓
                           Y490磷酸化           Y816磷酸化
                          ↙          ↘               ↓
                     Shc-Grb2      Grb2-Gab1      PLCγ
                        ↓               ↓           ↓
                    Ras-MAPK         PI3K       DAG + IP3
                        ↓               ↓     ↙         ↘
                    ERK→CREB        Akt    PKC         Ca²⁺
                   (基因表达)    (存活/合成) ↓              ↓
                                      (长期)  CaMKII    CaMKIV/NFATc4
                                              (突触增强)  (转录/存活)
```

## 关键证据

| 主张 | 证据/方法 | 来源 | 置信度 |
|------|----------|------|--------|
| Y816/PLCγ对海马LTP必要，Y490/Shc不必要 | trkB^PLC/PLC vs trkB^SHC/SHC敲入小鼠+电生理 | PMID:12367511 | 高（小鼠遗传） |
| Y816→fear获得，Y490→fear巩固 | 同样的敲入小鼠+行为+生化（杏仁核CaMKII/Akt） | PMID:19675247 | 高 |
| 突触前+突触后PLCγ协同支持LTP | 病毒过表达PH域阻断+电生理 | PMID:16571757 | 中-高 |
| BDNF驱动PV成熟→提前关键期 | BDNF过表达转基因+视觉皮层发育分析 | PMID:10499792 | 高（小鼠，经多项研究证实） |
| TrkB-T1 dominant negative + RhoGDI独立信号 | 过表达/KO实验综述 | PMID:22341689 | 中（多实验室，过表达为主） |
| NFATc4是BDNF/TrkB存活信号的转录中介 | NFATc4 KO+TrkB-Fc scavenger+AHN计数 | PMID:22586092 | 高 |

## 连接

- [[bdnf]] — BDNF是TrkB的主要配体；成熟BDNF→TrkB.TK+；proBDNF→p75NTR（反向效应）
- [[ltp]] — TrkB-Y816/PLCγ/CaMKII路由是海马LTP的必要信号组成
- [[fear-conditioning]] — Y816→获得，Y490→巩固；杏仁核TrkB的时间分工
- [[critical-period]] — BDNF/TrkB驱动PV+细胞GABAergic成熟，调控关键期开启时机
- [[adult-neurogenesis]] — TrkB-PI3K/Akt维持新生颗粒细胞存活；PLCγ-NFATc4转录存活
- [[pv-interneurons]] — TrkB信号（PLCγ+MAPK）上调PV+细胞Kv3.1和GAD67
- [[camkii]] — Y816/PLCγ/Ca²⁺的主要效应激酶；GluA1-S831磷酸化
- [[nmda-receptor]] — NMDA-Ca²⁺与TrkB-PLCγ-Ca²⁺是LTP中两条平行的钙信号来源
- [[p75ntr]] — 低亲和力神经营养因子受体；proBDNF→p75NTR→凋亡/LTD；与TrkB协同或拮抗

## 未解问题

- Q-trkb-01（高）：体内突触LTP期间，Y490和Y816磷酸化的时序和空间分布是什么？是否有细胞特异性差异？
- Q-trkb-02（中）：人类TrkB（Y515/Y816）的信号路由是否与小鼠完全对应？
- Q-trkb-03（高）：TrkB-T1在成体学习中的净效应（dominant negative抑制 vs BDNF扣押维持空间精确性）？
- Q-trkb-04（中）：TrkB转激活（腺苷A2A受体、Zn²⁺、GPCR）是否产生与BDNF相同的Y490/Y816磷酸化模式，还是只激活部分路由？

## 修订历史

- 2026-09-11 · 创建 · 基于《分子路由器》文章（#141）· 初始置信度：高（Y816/Y490路由机制有分子遗传学支持）/中（TrkB-T1生理功能）

## 来源文章

- [[2026-09-11-trkb-receptor-docking-signaling]]

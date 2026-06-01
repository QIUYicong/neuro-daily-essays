---
title: 发育关键期
slug: critical-period
domain: concepts
type: concept
status: established
confidence: high
created: 2026-06-24
updated: 2026-06-24
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, developmental, cognition]
related: [synaptic-pruning, perineuronal-nets, pv-interneurons, ltp, ltd, hebbian-learning, orientation-selectivity, working-memory]
prerequisites: [synaptic-transmission, pv-interneurons, ltp]
opens_questions: [Q-sp-03, Q-sp-04]
source_articles: [2026-06-24-synaptic-pruning-critical-period]
key_sources: ["PMID:16261181", "PMID:22462544", "PMID:32503914", "PMID:41240337"]
---

# 发育关键期 (Critical Period)

> **一句话定义**：大脑发育中特定的时间窗口，期间神经回路对特定类型的感觉经验高度可塑，该窗口由抑制性 PV 细胞成熟触发开启，由神经元周围网（PNNs）的形成封闭；错过窗口的感觉剥夺可造成不可逆的功能缺损。

## 当前理解

我们现在认为，关键期是大脑通过经验精修神经回路的特权时间窗口。关键期不是全或无的开关，而是一个具有时间延伸的可塑性高峰期，经典模型来自视觉皮层眼优势可塑性研究。

**经典实验**（Hubel & Wiesel，1981年诺贝尔奖）：在猫关键期内缝合一只眼睑（单眼剥夺），被剥夺眼失去视觉皮层代表区（皮层可塑性），开放眼代表区扩张。关键期外同样操作，无此效应。

**关键期的分子驱动**（Hensch 2005, PMID:16261181；Reh et al. 2020, PMID:32503914, PMCID:PMC7519216）：
1. **开启**：GABA 能 PV 细胞成熟 → E/I 平衡进入可塑窗口；
2. **维持**：经验驱动的突触竞争在开放窗口内重塑连接权重；
3. **关闭**：神经元周围网（PNNs）包裹 PV 细胞表面 → 可塑性巩固。

不同脑区关键期先后不同，反映 PV 细胞成熟的区域差异：感觉皮层（初级视觉、听觉）最早，前额叶认知回路最晚（青春期末）。

## 关键机制

### 关键期开启（GABA 成熟）

- 视觉皮层关键期：猫约3–8周龄（与 PV 细胞成熟对应）；小鼠约P21-P35；人类约生后6个月–2岁；
- GAD65 KO（GABA 合成酶缺失）→ 关键期不开启；苯二氮䓬类注射（GABA 增强）→ 关键期恢复（Hensch 2005，PMID:16261181）；
- PV 细胞产生 γ 振荡（40–80 Hz）= 突触竞争的"裁判时钟"。

### 关键期内的突触竞争

- **竞争性原则**：两眼争夺同一皮层神经元时，活动强者胜出，弱者的突触被修剪（见 [[synaptic-pruning]]）；
- **Hebbian 机制**：同时激活的突触得到 LTP 强化（"fire together, wire together"）；
- **反 Hebbian 机制**：时序失配的突触经 LTD 弱化，最终被补体/小胶质细胞清除。

### 关键期关闭（PNNs 形成）

- 神经元周围网逐渐包裹 PV 细胞 → 物理约束突触可塑性；
- ChABC（硫酸软骨素酶）降解 PNNs → 成年鼠部分恢复关键期可塑性（见 [[perineuronal-nets]]）；
- Otx2 转运蛋白（视网膜→丘脑→皮层）加速 PNNs 成熟（Reh 2020, PMID:32503914）。

### 关键期的多时间尺度调控

根据 Reh et al. 2020（PMID:32503914, PMCID:PMC7519216）：

- **分钟-毫秒**：PV 细胞 γ 振荡的当下状态；
- **发育月-年**：CLOCK/BMAL1 调控 PV 细胞成熟速度；早期逆境通过组蛋白乙酰化改变关键期轨迹；
- **跨代**：亲代环境体验可通过表观遗传影响后代关键期（机制尚不完全明确）。

### 成年期关键期重开

成年期虽然关键期已关闭，但可通过以下手段重开部分可塑性：
- ChABC 降解 PNNs；
- 暗适应数天（减少视觉驱动的 Otx2 转运）；
- 丘脑爆发放电（T 型 Ca 通道依赖，Echavarri-Leet 2025, PMID:41240337, PMCID:PMC12723367）；
- 某些抗抑郁药（通过 BDNF-TrkB-GAD65 通路）。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 单眼剥夺仅在关键期内造成眼优势偏移 | 猫单眼缝合 + 神经元放电记录 | Hubel & Wiesel 经典实验（1959-1977）| 高（教科书级） |
| GAD65 KO 小鼠关键期不开启，苯二氮䓬类可恢复 | 遗传学 + 药理学 + 单眼剥夺测试 | PMID:16261181（摘要） | 高 |
| 关键期关闭时 PNNs 形成；ChABC 降解 PNNs 重开可塑性 | 免疫组化 + ChABC 注射 + 眼优势测量 | PMID:16261181（综述引述） | 高 |
| PV 细胞伽马振荡在关键期内与可塑性正相关 | 综述整合 | PMID:32503914, PMC:PMC7519216 | 中（综述推断） |
| 人类婴儿6→12个月非母语音素伽马响应消失 | 婴儿 EEG | PMID:32503914, PMC:PMC7519216 | 中（人类相关研究） |
| TTX 诱导丘脑爆发放电可恢复成年弱视小鼠皮层响应 | TTX 注射 + 电生理 + Cav3.1 KO | PMID:41240337, PMC:PMC12723367 | 中（小鼠单一研究） |

## 连接

- [[synaptic-pruning]] — 关键期是主要突触修剪窗口
- [[perineuronal-nets]] — PNNs 关闭关键期
- [[pv-interneurons]] — PV 细胞成熟开启关键期
- [[orientation-selectivity]] — V1 朝向选择性在关键期内由经验精修
- [[ltp]] — 关键期内活跃突触通过 LTP 强化
- [[hebbian-learning]] — 关键期内的 Hebbian 可塑性驱动竞争

## 未解问题

- Q-sp-03（中优先级）：人类前额叶皮层关键期的精确时间窗口是什么？与语言/社会关键期的重叠关系？
- Q-sp-04（中优先级）：跨代表观遗传影响关键期的具体机制？生殖细胞如何携带亲代环境记忆？

## 修订历史

- 2026-06-24 · 创建 · 基于《用进废退的精密刻刀》一文 · 初始置信度：高

## 来源文章

- [[2026-06-24-synaptic-pruning-critical-period]]

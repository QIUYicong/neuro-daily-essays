---
title: 本体感觉
slug: proprioception
domain: concepts
type: concept
status: established
confidence: high
created: 2026-10-10
updated: 2026-06-13
revision_count: 3
dimensions: [cellular, microcircuit, brain-region, whole-brain-network, behavior, cognition]
related: [muscle-spindle, gamma-motor-neuron, golgi-tendon-organ, somatosensory-cortex, somatosensory-cortex-3a, cerebellum, proprioceptive-prediction, forward-model, body-schema]
prerequisites: [muscle-spindle, action-potential]
opens_questions: [Q-spindle-01, Q-spindle-02, Q-spindle-03]
source_articles: [2026-10-10-muscle-spindle-proprioception-gamma-motor, 2026-06-13-golgi-tendon-organ-ib-autogenic-inhibition]
key_sources: ["PMID:23073629", "PMID:19581378", "PMID:29978899", "PMID:30095484", "PMID:1626033", "PMID:10899663", "PMID:30604022"]
---

# 本体感觉 (Proprioception)

> **一句话定义**：机体不依赖视觉感知自身肢体位置、运动和力量的感觉系统，主要依赖肌梭（长度/速度）、高尔基腱器官（力量/张力）和皮肤感受器（皮肤牵张），并整合来自运动指令的传出副本，产生有意识的运动感知和无意识的反射控制。

## 当前理解

我们现在认为，本体感觉不是单一传感器的输出，而是多源信号的主动**融合与重建**：

**传感器层级**：
1. **肌梭**（主力）→ Ia/II 型传入 → 肌肉长度和速度
2. **高尔基腱器官（GTO）** → Ib 型传入 → 肌肉张力/力量
3. **皮肤 Ruffini 末梢** → 关节角度变化时的皮肤牵张（手指处尤重要）
4. **关节感受器** → 仅在运动极端位置激活（次要）
5. **传出副本（efference copy）** → 运动指令的中枢内部复制 → 即使无外周反馈也能提供位置信息（约 8–20°）

**核心证据**（Proske & Gandevia 2009，PMC2754351）：
- 关节置换术后本体感觉基本正常 → 关节感受器不是主力
- 腱振动（100 Hz）选择性激活 Ia → 产生运动错觉 → 证明肌梭主导
- 全麻醉外周神经后主动尝试运动 → 仍产生约 20° 位置感知 → 传出副本贡献

本体感觉也是**可被欺骗**的：肌肉的"thixotropy"（触变性）——肌肉静止时形成的钙桥增加肌纤维僵硬度——会扭曲肌梭的基线放电，导致位置匹配任务中高达 20° 的系统误差。

## 关键机制

### 外周传感器

**肌梭-γ 系统**：
- Ia 传入：编码速度 + 长度
- II 型传入：编码静态长度
- γ 运动神经元：主动配置肌梭灵敏度（防运动时沉默）

**高尔基腱器官（GTO）**：
- Ib 传入：编码肌腱张力（与肌纤维串联，对主动收缩高度敏感）
- 每次收缩都放电（非仅高张力时激活，Jami 1992 PMID:1626033）
- 触发脊髓 Ib 抑制性中间神经元 → 自身抑制（静息/摆动相）
- **步行站立相**：Ib 抑制被下行信号关闭，转为 Ib 兴奋性负荷信号（延长支撑相）
- 与传出副本共同构建"重量感"和"力感"（Proske & Allen 2019 PMID:30604022）
- "折刀反射"修正：该反射主要来自 III/IV 类传入，非 GTO 高阈值激活

### 中枢处理通路

**意识通路（DCML）**：
```
Ia/II → 脊髓后柱（薄/楔束）→ 延髓 → 内侧丘系
→ 丘脑 VPLc → S1 第 3a 区（有意识位置感知；同时接收VLc运动丘脑输入）
→ M1（3a区直接投射，感觉告知运动）
→ 顶叶后皮层（PPC）整合视觉+本体感觉 → 身体图式
```
**3a区的核心特征**：S1的3a子区位于中央沟底部，是皮层层面本体感觉的专属第一站。它不仅接收来自VPLc丘脑的Ia传入（实际感觉），还接收来自小脑-VLc通路的运动预测信号，并直接投射到M1。这使它成为皮层层面的"预测-实际比较器"（详见[[somatosensory-cortex-3a]]）。

**小脑通路（无意识）**：
```
Ia/II → 脊髓小脑束（DSCT/VSCT）→ 小脑皮层
→ 深小脑核 → 丘脑 → 运动皮层
（前馈预测、运动协调）
```

### 传出副本（Efference Copy）

大脑在发出运动指令时同时产生一份内部副本，发送到小脑和其他区域。小脑利用这个副本预测运动结果，并与实际感觉反馈比较，检测并纠正误差。这使得大脑能够区分"自身运动产生的感觉"和"外部干扰"。

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| 肌梭是主要本体感觉器官 | 关节置换不影响本体感觉；振动激活 Ia 产生错觉 | PMID:19581378 | 高 |
| 传出副本独立贡献本体感觉 | 全麻醉外周神经后主动运动→位置感知 | PMID:19581378 | 高 |
| thixotropy 扭曲位置判断 | 肌肉历史依赖性的匹配误差（20°） | PMID:19581378 | 高 |
| PIEZO2 缺失消除本体感觉 | PIEZO2 KO 小鼠 + 人类 PIEZO2 突变病例 | PMID:35430481 | 高 |
| 皮肤 Ruffini 末梢补充本体感觉 | 手指去感觉后本体感觉下降 | PMID:19581378 | 中 |
| GTO 低阈值：每次收缩均放电 | 猫细胞外记录（各型运动单元） | PMID:1626033 | 高 |
| GTO 步态功能：站立相负荷信号 | 步行电生理 + Ib 传入切断实验 | PMID:10899663 / PMID:14653157 | 高 |
| GTO Ib 传入参与力量感知 | 双臂力量匹配 + 振动干扰范式 | PMID:23073629 / PMID:30604022 | 中 |

## 连接

- [[muscle-spindle]] — 核心传感单元（长度/速度）
- [[gamma-motor-neuron]] — 主动配置肌梭灵敏度
- [[golgi-tendon-organ]] — 力量传感器，构成双传感器系统
- [[somatosensory-cortex]] — S1 3a 区接收本体感觉信号
- [[somatosensory-cortex-3a]] — 3a区：本体感觉皮层专属中继，双重丘脑输入，直接投射M1
- [[cerebellum]] — 利用本体感觉做前馈预测和误差校正
- [[proprioceptive-prediction]] — 预测编码框架下的本体感觉信号处理
- [[forward-model]] — 小脑作为前馈模型整合传出副本和本体感觉

## 未解问题

- Q-spindle-01：PIEZO2 快/慢适应悖论的解释机制？
- Q-spindle-02：人类动态/静态 γ 神经元独立控制的证据？
- 老龄化和 DOMS 如何影响肌梭 Ia 末梢的 PIEZO2 功能？

## 修订历史

- 2026-10-10 · 创建 · 基于《感觉会自我校准的尺子》(#172) · 初始置信度：高
- 2026-06-13 · rev2 · 基于《肌肉力量的精确传感器》(#174) · 大幅扩展 GTO 子系统描述：更正低阈值特性、步态 Ib 切换机制、力量感知贡献、"折刀反射"修正；新增3条关键证据行；更新 key_sources
- 2026-06-13 · rev3 · 基于《3a区——皮层本体感觉的第一站》(#177) · 在DCML通路描述中补充3a区双重丘脑输入（VPLc感觉+VLc运动）和直接M1投射；新增[[somatosensory-cortex-3a]]链接；更新related字段

## 来源文章

- [[2026-10-10-muscle-spindle-proprioception-gamma-motor]]

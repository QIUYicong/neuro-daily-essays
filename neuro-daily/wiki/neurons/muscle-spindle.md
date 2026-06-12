---
title: 肌梭
slug: muscle-spindle
domain: neurons
type: structure
status: established
confidence: high
created: 2026-10-10
updated: 2026-10-10
revision_count: 1
dimensions: [molecular, cellular, synaptic, microcircuit, brain-region, behavior, cognition]
related: [gamma-motor-neuron, alpha-motor-neuron, piezo2-mechanotransduction, golgi-tendon-organ, proprioception, spinal-cord-cpg, neuromuscular-junction, somatosensory-cortex, cerebellum]
prerequisites: [action-potential, synaptic-transmission, alpha-motor-neuron]
opens_questions: [Q-spindle-01, Q-spindle-02, Q-spindle-03]
source_articles: [2026-10-10-muscle-spindle-proprioception-gamma-motor]
key_sources: ["PMID:23073629", "PMID:19581378", "PMID:35430481", "PMID:36561377", "PMID:30095484"]
---

# 肌梭 (Muscle Spindle)

> **一句话定义**：嵌入骨骼肌内、与梭外肌纤维并联排列的感觉器官，内含 2–12 根梭内肌纤维（bag1/bag2/链），通过 PIEZO2 机械换能通道和 Ia/II 型传入纤维向脊髓和皮层报告肌肉的长度与变化速度，是本体感觉系统的核心传感单元。

## 当前理解

我们现在认为，肌梭是骨骼肌内最精密的感觉器官，其核心创新在于：传感器本身的灵敏度是**可主动配置**的。通过 **γ 运动神经元**对梭内肌纤维极端区（收缩段）的支配，脑干和脊髓上运动中枢能够实时调整肌梭的工作范围和灵敏度类型，使其在肌肉收缩时不沉默（α-γ 协同激活）、在不同任务中优先编码速度或静态长度。

机械换能的分子核心是 **PIEZO2**——一种大型三叶螺旋桨状的机械门控阳离子通道。遗传学研究（Chesler et al. 2016; Wilkinson et al. 2022）证明，DRG 本体感觉神经元中 PIEZO2 的缺失几乎完全消除肌梭的拉伸响应，而 PIEZO2 功能缺失突变在人类中导致严重本体感觉缺陷、脊柱侧弯和髋关节发育不良。

肌梭并非孤立传感器：它与 Ia 中间神经元、α 运动神经元、GTO-Ib 回路共同构成脊髓内的**本体感觉闭环**，实现牵张反射（单突触）、交互抑制和自身抑制的快速自动调控。

## 关键机制

### 结构层次

**整体拓扑**：
- 肌梭纺锤形封闭囊，长 4–7 mm，宽 < 0.5 mm
- 与梭外肌纤维**并联**排列（随肌肉拉伸/缩短同步变化）
- 每块肌肉含 10–200 个肌梭（近端精细运动肌肉更多）

**梭内肌纤维三类型**（按细胞核排列）：

| 类型 | 别称 | 细胞核排布 | 主要功能 | γ 支配类型 |
|------|------|-----------|---------|-----------|
| 核袋1纤维 | bag1 | 中央聚团 | 速度检测（动态） | 动态 γ（γd） |
| 核袋2纤维 | bag2 | 中央聚团（较小） | 长度检测（静态） | 静态 γ（γs） |
| 核链纤维 | chain | 单排链状 | 长度检测（静态） | 静态 γ（γs） |

**传入神经**：
- **Ia 型**（Group Ia）：环螺旋末梢 → 所有三型纤维赤道区；70–120 m/s；动态+静态双编码；单突触牵张反射
- **II 型**（Group II）：花簇末梢 → bag2 和链纤维极端区；20–50 m/s；主要静态长度

### 机械换能（分子层）

```
拉伸力 → PIEZO2 通道开放（需细胞骨架和 ECM 力传递）
  ↓ 非选择性阳离子（Na⁺/Ca²⁺）内流
受体电位（去极化）
  ↓ 传向半节（heminode）
Nav1.1/1.6/1.7 放大信号
  ↓
动作电位序列 → 脊髓（Ia 到 α 运动神经元 / 中间神经元）
```

**静态相维持**（谷氨酸囊泡假说）：
- Ia 末梢含 vGluT1 标记的突触小泡
- 持续拉伸期间谷氨酸分泌 → 维持静态相放电
- 抑制 vGluT1 选择性降低静态相（不影响动态相）

**Ia vs II 型差异的离子通道基础**：
- Ia 高表达 Kv1.1/Kv1.2 → 赋予相位性（速度依赖）放电
- II 型高表达 ASIC3 → 紧张性放电

### α-γ 协同激活（系统层）

```
大脑运动指令
  ├─→ α 运动神经元 → 梭外肌纤维收缩（产力）
  └─→ γ 运动神经元 → 梭内肌纤维极端区收缩（维持传感器张力）
         ↓
肌梭在整个收缩过程中持续报告长度/速度
```

- **γd 激活** → bag1 缩短 → Ia 对速度更敏感（动态增益↑）
- **γs 激活** → bag2+chain 缩短 → Ia/II 静态长度编码维持（防沉默）

### 牵张反射回路

```
肌肉突然拉伸 → Ia 传入 → 脊髓腹角（单突触）→ 同肌 α 运动神经元 → 收缩对抗拉伸
                              ↓
                      Ia 中间神经元 → 拮抗肌 α 运动神经元抑制（交互抑制）
```
延迟：20–30 ms（人体最快完整反射）

### 上行本体感觉通路

- **意识通路**：后柱（薄/楔束核）→ 内侧丘系 → 丘脑 VPLc → S1 第 3a 区（有意识位置感）
- **小脑通路**：脊髓小脑束（DSCT/VSCT）→ 小脑皮层 → 运动协调和前馈预测（无意识）

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| PIEZO2 是肌梭机械换能的必要分子 | DRG 特异性 Piezo2 敲除消除拉伸响应；人类 PIEZO2 突变→本体感觉缺失 | PMID:35430481 (PMC9815952) | 高 |
| γd 支配 bag1，γs 支配 bag2+chain | 电生理分类 + 解剖追踪（猫） | PMID:36561377 (PMC9770680) | 高（猫）；低（人类） |
| 肌梭是主要本体感觉器官 | 关节置换后本体感觉正常；振动激活 Ia 产生运动错觉 | PMID:19581378 (PMC2754351) | 高 |
| 谷氨酸囊泡维持静态相放电 | 抑制 vGluT1 → 选择性降低静态相 Ia 放电 | PMID:35430481 | 中（机制尚不完整） |
| Ia 和 II 型动态差异源于 Kv1.1/Kv1.2 | 药理阻断 Kv1.1/1.2 → Ia 放电模式向 II 型转变 | PMID:35430481 | 中 |
| 肌梭参与骨骼对位的非运动功能 | 去传入动物骨折愈合异常；GBS 患者脊柱侧弯 | PMID:30095484 | 中（证据间接） |

## 连接

- [[gamma-motor-neuron]] — 支配梭内肌纤维极端区，调节肌梭灵敏度
- [[alpha-motor-neuron]] — 接受 Ia 传入的单突触驱动（牵张反射）；与 γ 协同激活
- [[piezo2-mechanotransduction]] — 肌梭机械换能的核心分子
- [[golgi-tendon-organ]] — 力量传感器，与肌梭共同构成本体感觉双传感器系统
- [[proprioception]] — 肌梭是本体感觉的核心传感单元
- [[spinal-cord-cpg]] — CPG 模式发生器调控肌梭回路；本体感觉反馈影响 CPG 节律
- [[neuromuscular-junction]] — 运动命令从 NMJ 传到梭外肌纤维；γ 运动神经元通过 NMJ 传到梭内
- [[cerebellum]] — 通过脊髓小脑束接收肌梭信号，参与前馈运动控制
- [[somatosensory-cortex]] — S1 3a 区是本体感觉的皮层终点；产生位置意识感知

## 未解问题

- Q-spindle-01（高优先级）：PIEZO2 快适应与 Ia 慢适应的矛盾——谷氨酸囊泡是否是充分解释？末梢的 PIEZO2 局部调控机制？
- Q-spindle-02（中优先级）：人类 γ 运动神经元是否存在真正的动态/静态独立控制？需要什么实验技术验证？
- Q-spindle-03（中优先级）：肌梭如何通过本体感觉传入促进脊髓损伤后轴突再生？具体分子通路？

## 修订历史

- 2026-10-10 · 创建 · 基于《感觉会自我校准的尺子》(#172) · 初始置信度：高

## 来源文章

- [[2026-10-10-muscle-spindle-proprioception-gamma-motor]]

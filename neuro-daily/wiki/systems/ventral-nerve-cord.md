---
title: 腹侧神经索（果蝇）
slug: ventral-nerve-cord
domain: systems
type: structure
status: established
confidence: high
created: 2026-10-06
updated: 2026-10-06
revision_count: 1
dimensions: [cellular, microcircuit, brain-region, behavior]
related: [connectomics, distributed-motor-control, motor-cortex, spinal-cord, descending-neurons]
prerequisites: [action-potential, synaptic-transmission, neuromuscular-junction]
opens_questions: [Q-vnc-01]
source_articles: [2026-10-06-drosophila-banc-connectome-distributed-control]
key_sources:
  - "PMID:40766407"
  - "PMID:39358518"
---

# 腹侧神经索 (Ventral Nerve Cord, VNC) — 果蝇

> **一句话定义**：果蝇（及昆虫）中枢神经系统的类脊髓结构，包含约20,000个神经元，负责处理来自肢体、翅膀、内脏和生殖器官的感觉输入，并整合这些信号驱动对应的运动输出；BANC 连接组（2026）首次将其与大脑合并为完整接线图，揭示 VNC 是分布式运动控制的主要执行层。

---

## 当前理解

腹侧神经索（Ventral Nerve Cord, VNC）是昆虫中枢神经系统的重要组成部分，在功能上类似脊椎动物的脊髓。在果蝇（*Drosophila melanogaster*）中：

**解剖结构**：
- VNC 由多个融合的神经节（ganglia）组成，分别对应不同身体部位：胸部（控制翅膀和腿部）、腹部（控制内脏和生殖器官）
- 与大脑通过**颈连合**（cervical connective）相连，其中传导约1,300个下行神经元（DNs）和约1,900个上行神经元（ANs）的轴突
- 约 **20,000个神经元**（BANC 数据，Bates et al. 2026，PMID:40766407，开放全文）

**功能组织**（来自 BANC 2026）：

VNC 内的神经元主要可分为：
1. **感觉神经元末梢**：来自腿部、翅膀、腹部、生殖器官的感觉纤维在 VNC 内形成突触
2. **运动神经元（Motor Neurons, MNs）**：从 VNC 直接投射到相应肌肉，是运动命令的最终共同通路
3. **内脏传出神经元**：控制消化道、心脏、生殖器官
4. **本体感觉整合神经元**：处理身体位置和运动状态
5. **局部中间神经元**：连接同一体段内的感觉和运动成分，构成局部反射弧

**核心特点——局部感觉-运动回路**：

BANC 的关键发现是：在 VNC 中，**执行细胞（主要是运动神经元）的最强突触输入来自同一体段的感觉神经元**。例如：
- 咽部运动神经元 → 最强输入来自咽部感觉细胞
- 翅膀运动神经元 → 主要由翅膀感觉神经元驱动
- 腿部运动神经元 → 以腿部本体感觉反馈为主

这些局部闭合回路的延迟远低于经由大脑的长程路径，是运动精度和快速反应的基础。

**与大脑的关系**：

VNC 不是大脑命令的被动中继。大脑通过 DNs 向 VNC 发送调制信号，但这些信号在权重上系统弱于局部感觉-运动连接。VNC 具有相当程度的自主性——当果蝇头部被去除后，去头果蝇的身体仍可以执行某些协调的行走动作（Pearson & Iles 1970等早期经典研究），这正是 VNC 局部回路自主性的行为学证明。

---

## 关键机制

### VNC 的体段特异性

VNC 的神经元按体段（segment）组织，每个体段的感觉-运动回路相对独立：
- **T1-T3 节（胸部）**：控制三对腿（前腿/中腿/后腿）和翅膀
- **A1-A10 节（腹部）**：控制内脏、生殖器官、腹部运动

各体段之间通过**节间神经元**（intersegmental neurons）协调，产生协调的节律性行为（如行走步态）。

### DNs 和 ANs 在 VNC 中的角色

BANC 揭示 DNs（下行神经元）在 VNC 中有实质突触输出——它们不只是"穿过" VNC 传递命令，而是直接与 VNC 内的局部中间神经元和运动神经元形成突触，调制局部回路的激活阈值和时序。ANs（上行神经元）同样在 VNC 内有实质输出，参与 VNC 内的局部计算，而不只是上传状态信号。

---

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| VNC 含约 20,000 个神经元（成体雌果蝇） | BANC 接线图直接计数 | PMID:40766407（开放全文） | 高（单只样本） |
| VNC 运动神经元最强输入来自同体段感觉神经元 | BANC 240亿对影响力评分 | PMID:40766407（开放全文） | 高（结构）；功能待验证 |
| DNs 和 ANs 在 VNC 内有实质突触输出（不只是过路信号） | BANC 突触统计 | PMID:40766407（开放全文） | 高 |
| 去头果蝇身体可执行协调行走 | 行为实验（经典研究） | 多项早期果蝇行为学研究 | 高（行为层面自主性的证明） |

---

## 连接

- [[connectomics]] — BANC 是揭示 VNC 完整接线图的方法基础
- [[distributed-motor-control]] — VNC 是分布式运动控制架构的主要执行层
- [[motor-cortex]] — 脊椎动物运动皮层与果蝇大脑的功能类比；两者在分布式控制框架中均担任"监督"而非直接执行角色
- [[descending-neurons]] — 连接大脑与 VNC 的中间层，在 VNC 内有实质突触输出（双向协调节点）

---

## 未解问题

- **Q-vnc-01**（高优先级）：果蝇 VNC 的分布式感觉-运动架构，在多大程度上可以类比到脊椎动物脊髓？二者的主要结构差异（如脊椎动物脊髓固有神经元网络的规模和复杂性）是否影响局部自主性的程度？

---

## 修订历史

- 2026-10-06 · 创建 · 基于《当大脑与脊髓合为一张接线图》(#166) · 填补 systems 子目录对 VNC 的空白 · 基于 BANC 连接组（PMID:40766407）及果蝇经典行为学

---

## 来源文章

- [[2026-10-06-drosophila-banc-connectome-distributed-control]]

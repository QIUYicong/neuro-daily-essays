---
title: 后顶叶皮层
slug: posterior-parietal-cortex
domain: systems
type: region
status: established
confidence: high
created: 2026-08-30
updated: 2026-08-30
revision_count: 1
dimensions: [brain-region, systems, behavior, cognition]
related: [dorsal-visual-stream, mt-v5-motion-area, motor-cortex, dorsal-attention-network, place-cell, grid-cell, v1-primary-visual-cortex, temporoparietal-junction]
prerequisites: [v1-primary-visual-cortex, dorsal-visual-stream]
opens_questions: [Q-ppc-01, Q-ppc-02]
source_articles: [2026-08-30-dorsal-visual-stream-parietal-action]
key_sources: ["PMID:24634664", "PMCID:PMC3942635", "PMID:38076390", "PMCID:PMC10710236", "PMID:1374953"]
---

# 后顶叶皮层 (Posterior Parietal Cortex, PPC)

> **一句话定义**：后顶叶皮层是背侧视觉流的核心处理枢纽，沿顶内沟（IPS）轴排列多个功能分区（LIP、AIP、VIP、MIP），以自我中心坐标整合视觉、本体感觉和前庭信号，构建可被行动系统调用的空间意图图谱。

## 当前理解

我们现在认为后顶叶皮层（PPC）是感知与行动之间的神经接口——它不是单一功能区域，而是沿颅内沟（IPS）前后轴分布的多个专用计算模块的集合。不同模块处理不同的行动参数：眼动的空间优先级（LIP）、抓握时的手型预编码（AIP）、近身空间防御（VIP）、到达轨迹规划（MIP/V6A）。

与腹侧流用异我中心（allocentric）坐标构建物体的感知表征不同，PPC 的所有计算都以自我为中心（egocentric）——以头、眼、手为参照。这种编码方式对于实时引导行动是必要的：行动需要知道"物体相对于我的手在哪里"，而不是"物体在世界坐标系里的位置"。

PPC 同时接受来自 MT/V5 的运动信号、来自背侧注意网络（FEF-IPS）的自上而下注意控制，以及来自前额叶的任务目标信息，使其同时负责感知驱动的反应和目标导向的行动规划。

## 关键机制

### LIP（Lateral Intraparietal area）
- 构建**空间显著性/注意优先级图谱**，标记视野中重要位置
- 持续性放电追踪注意焦点，但不直接触发眼动（Brunamonti & Paré 2023：93% 的 LIP 运动相关神经元无法在眼动取消时序内改变放电）
- 通过 LIP → FEF → SC（上丘）路径间接引导眼动
- 接受来自 MT/V5 的运动输入，参与运动目标的眼跳规划

### AIP（Anterior Intraparietal area）
- 在抓握动作**前**预编码手的构型，响应物体的形状、大小和方向
- 与腹侧前运动皮层（PMv）形成回路，构成"抓握行动生成器"
- 损伤 → 光学性共济失调（optic ataxia）：视觉正常但无法精准抓握

### VIP（Ventral Intraparietal area）
- 接受多模态输入（视觉+触觉+前庭），对靠近面部的物体（peripersonal space）特别敏感
- 参与近身空间防御性地图的构建

### MIP（Medial Intraparietal area / PRR）
- 主要负责到达（reaching）目标的空间坐标计算
- 与背侧前运动皮层（PMd）形成 SPL-PMd 路径，控制手臂轨迹

### 双路输出（Rizzolatti & Matelli 2003，PMID: 12955383）
- **背背侧流**：SPL（AIP/MIP）→ PMd（背侧前运动皮层）→ M1：控制到达
- **腹背侧流**：IPL（AIP/SMG）→ PMv（腹侧前运动皮层）→ M1：控制抓握与工具使用

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| aIPS（AIP）预编码抓握手型 | 人类 fMRI + 光学性共济失调病例 | PMID: 24634664，PMC3942635 | 高 |
| LIP 不足以直接触发眼动 | 猕猴颅内记录 + 反制任务（93%神经元不符合时序标准） | PMID: 38076390，PMC10710236 | 高 |
| PPC 损伤 → 视觉忽视（hemispatial neglect） | 右顶叶损伤案例 + 行为学 | 教科书级证据（多重独立来源） | 高 |
| 工具使用激活左侧 SMG 双焦点 | 人类 fMRI 系统综述 | PMID: 24634664 | 中-高 |
| D.F. 患者：感知损伤但抓握完整 | 神经心理案例研究 | PMID: 1374953 | 高 |

## 连接

- [[dorsal-visual-stream]] — PPC 是背侧流的核心处理节点
- [[mt-v5-motion-area]] — MT/V5 向 LIP/VIP 提供运动输入
- [[motor-cortex]] — 通过 PMd/PMv 向 M1 输出行动指令
- [[dorsal-attention-network]] — IPS 是背侧注意网络的关键节点（与 FEF 协同）
- [[temporoparietal-junction]] — IPL 的一部分，涉及社会认知和注意定向
- [[place-cell]] / [[grid-cell]] — PPC 通过 EC-海马通路连接空间认知地图

## 未解问题

- Q-ppc-01（高优先级）：IPS 的功能分区是否比当前二分（背背侧/腹背侧）更细？人类影像学显示至少 4 个激活梯度，但标准化分类尚无共识。
- Q-ppc-02（中优先级）：人类顶叶下回（IPL）的演化扩展如何解释人类独特的工具使用能力？VEN 样细胞或 L5 锥体神经元是否在 IPL 中扮演特殊角色？

## 修订历史

- 2026-08-30 · 创建 · 基于《视觉的另一半：背侧流如何把世界变成动作》· 初始置信度：高

## 来源文章

- [[2026-08-30-dorsal-visual-stream-parietal-action]]

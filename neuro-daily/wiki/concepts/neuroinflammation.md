---
title: 神经炎症
slug: neuroinflammation
domain: concepts
type: concept
status: established
confidence: high
created: 2026-09-17
updated: 2026-09-17
revision_count: 1
dimensions: [cellular, molecular, brain-region, disease]
related: [microglia, astrocyte, disease-associated-microglia, trem2, complement-cascade-cns, alzheimers-disease, parkinsons-disease, als-amyotrophic-lateral-sclerosis, excitotoxicity, mitochondrial-dysfunction]
prerequisites: [microglia, astrocyte, synaptic-transmission]
opens_questions: [Q-neuroinflamm-01, Q-neuroinflamm-02, Q-neuroinflamm-03]
source_articles: [2026-09-17-neuroinflammation-microglia-dam-trem2]
key_sources:
  - "PMID:28602351"
  - "PMID:28930663"
  - "PMCID:PMC5719893"
  - "PMID:29775591"
  - "PMCID:PMC8497816"
---

# 神经炎症 (Neuroinflammation)

> **一句话定义**：神经炎症是中枢神经系统对损伤、病原体或错误折叠蛋白积累的免疫应答，由小胶质细胞（主要效应器）和星形胶质细胞协同介导，既是神经退行性疾病的共同病理特征，又可在早期发挥保护性清除功能——其保护或破坏的净效应取决于持续时间、强度、疾病阶段和具体分子背景。

---

## 当前理解

我们现在认为，神经炎症不是单一的"有害状态"，而是一个**连续谱系**，从急性保护性应答到慢性神经毒性状态的转变，是当前神经退行性疾病研究的核心争论焦点之一。

**主要效应细胞**：
- **小胶质细胞**：CNS常驻免疫细胞，神经炎症的核心效应器。从稳态P2RY12+/TMEM119+巡逻状态，转化为疾病相关微胶质细胞（DAM）或MGnD（神经退行性表型）。
- **星形胶质细胞**：响应神经炎症信号，可转化为A1型（有害）或A2型（修复性），但M1/M2和A1/A2的二元分类在体内已被质疑为过度简化。
- **外周免疫细胞渗入**：在晚期或血脑屏障破坏时，单核细胞、T细胞可进入CNS参与炎症（在PD中有证据）。

**关键触发信号**：
- 错误折叠蛋白：Aβ（AD）、α-突触核蛋白（PD）、TDP-43聚集（ALS）、polyQ（HD）
- 凋亡神经元的危险信号（PS暴露、DAMPs）
- 线粒体功能障碍产生的ROS
- 溶酶体/内质网应激

**关键炎症分子**：TNF-α、IL-1β、IL-6（促炎）；IL-4、IL-10、TGF-β（抗炎/修复）；NLRP3炎症小体；iNOS/ROS；谷氨酸过量释放（与兴奋毒性相交）

---

## 关键机制

### 1. 稳态→炎症转化（以DAM为例）

小胶质细胞在健康状态下由神经元持续分泌的TGF-β和CX3CL1维持稳态（P2RY12↑、TMEM119↑）。当神经元凋亡（PS暴露）或Aβ积累时：

- **Step 1（TREM2非依赖）**：稳态基因（P2RY12↓、CX3CR1↓）下调，TREM2↑、APOE↑初步上调
- **Step 2（TREM2依赖）**：完整DAM激活——脂质代谢基因（LPL↑、CTSD↑）全面上调，细胞具备吞噬能力

### 2. TREM2-APOE信号轴（MGnD通路）

TREM2（脂质传感器，通过DAP12/TYROBP→PI3K→Akt）识别PS并触发APOE自分泌。APOE抑制稳态转录因子（MEF2A、MAFB、SMAD3），诱导miR-155进一步削弱稳态程序。净效果：小胶质细胞丧失"城市默契"，可能进入神经毒性状态。

### 3. 炎症小体与细胞因子风暴

在慢性炎症中，NLRP3炎症小体被激活（触发因素：mtDNA、Aβ聚集体），释放IL-1β和IL-18。持续的TNF-α可直接诱导神经元凋亡（TNFR1通路）。IL-6通过JAK-STAT3影响突触可塑性。

---

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| DAM在AD模型斑块周围形成两步激活 | scRNA-seq 5XFAD；TREM2-KO缺失Step 2 | PMID:28602351 | 高（小鼠）/中（人类） |
| TREM2-APOE轴驱动MGnD，阻断它减少神经元死亡 | CX3CR1-Cre APOE-KO；SOD1和APP-PS1模型 | PMID:28930663/PMC5719893 | 高（小鼠）/中（人类） |
| 人类AD脑确认DAM样亚群 | snRNA-seq 80,660核，48名AD患者 | PMID:31042697/PMC6865822 | 高 |
| TREM2 R47H → AD风险↑3-5× | 外显子测序7000+样本；冰岛队列独立复制 | PMID:23150934; 23150908 | 高 |
| TREM2激动（AL002）不改善早期AD临床结局 | Phase 2 INVOKE-2, 381人，48-96周 | PMID:41787076 | 高（临床阴性） |
| PD中BAM（非小胶质细胞）是CD4 T细胞抗原呈递者 | α-syn模型；MHCII-cKO；人脑BAM-T细胞近邻 | PMID:37365181/PMC10293214 | 中（PD特异） |

---

## 连接

- [[microglia]] — 神经炎症的核心效应细胞；DAM/MGnD是其激活状态
- [[disease-associated-microglia]] — 神经退行性疾病中的特定小胶质细胞状态
- [[trem2]] — 关键触发受体，DAM激活的分子开关
- [[astrocyte]] — 星形胶质细胞参与神经炎症（A1反应性）
- [[complement-cascade-cns]] — 补体标记激活小胶质细胞吞噬（与突触剪枝共享机制）
- [[excitotoxicity]] — 神经炎症→谷氨酸过量释放→突触外NMDAR激活；两者相互放大
- [[mitochondrial-dysfunction]] — 神经炎症→ROS→线粒体损伤；反向也成立（线粒体损伤→DAMP释放→炎症）
- [[alzheimers-disease]] — Aβ触发神经炎症；TREM2-DAM轴是AD的第三大遗传风险通路
- [[parkinsons-disease]] — α-syn触发微胶质激活；PD中BAMs特殊角色
- [[als-amyotrophic-lateral-sclerosis]] — 运动神经元死亡→大量PS信号→DAM激活；TREM2-APOE通路在SOD1模型中被记录

---

## 未解问题

- Q-neuroinflamm-01（高）：DAM保护→MGnD破坏的翻转发生在什么时机点（斑块负荷？神经元丢失比例？APOE基因型）？有无体内可测标志物？
- Q-neuroinflamm-02（高）：MGnD的主要神经毒性输出是哪些分子（TNF、IL-1β、ROS、谷氨酸），各自贡献比例？
- Q-neuroinflamm-03（中）：TREM2激活的最优时间窗口（认知正常/淀粉样蛋白PET阳性期？）——能否在AD预防研究框架中回答？

---

## 修订历史

- 2026-09-17 · 创建 · 基于《大脑内守军的两张面孔》(文章#147) · 初始置信度：高（机制established；治疗应用仍emerging）

---

## 来源文章

- [[2026-09-17-neuroinflammation-microglia-dam-trem2]]

# 阅读笔记：2026-09-13

## 今日主题
空间转录组学（Spatial Transcriptomics）与 BICCN 全鼠脑细胞类型图谱

---

## 来源 1：Yao Z et al. 2023（PMID:38092916）
**A high-resolution transcriptomic and spatial atlas of cell types in the whole mouse brain**
*Nature* 624:317–332. DOI:10.1038/s41586-023-06812-z. PMCID:PMC10719114

### 解决什么问题
将单细胞 RNA 测序（scRNA-seq）与空间 MERFISH 技术结合，建立覆盖整个成年小鼠大脑的细胞类型图谱，解决"细胞分子身份 + 空间位置"的双维度解析问题。

### 方法
- scRNA-seq：~700 万个单细胞转录组（781 个文库）
- MERFISH：59 张冠状切片，1,147 个基因，~430 万个细胞
- 四级分层聚类：34 类 → 338 亚类 → 1,201 超类 → 5,322 集群

### 关键发现
- 神经元 46% / 非神经元 54%
- 谷氨酸能 ~63% / GABA 能 ~36% / 调质神经元 ~2%
- 背腹侧二元性：背侧少而分化大，腹侧多而相近
- scRNA-seq → MERFISH 标签转移准确率：亚类 83%，集群 74%

### 改变了什么理解
提供了大脑细胞多样性的系统框架，将"大脑有多少种细胞"从猜测转化为可量化的答案（5,322 个转录组学集群）。

### 证据强度
高——多实验室合作，样本量大，公开数据，方法透明。

### 局限
- 成年小鼠快照，不反映发育动态或疾病状态
- 1,147 个基因面板不是全转录组，细胞类型定义受基因选择影响
- 细胞类型与功能类型的对应需要多模态验证

---

## 来源 2：Zhang M et al. 2023（PMID:38092912）
**Molecularly defined and spatially resolved cell atlas of the whole mouse brain**
*Nature* 624:333–342. DOI:10.1038/s41586-023-06808-9. PMCID:PMC10719103

### 解决什么问题
在完整三维解剖空间中为每个细胞提供转录组学身份，建立细胞类型的精细空间分布图。

### 方法
- MERFISH：1,122 个基因，32 位汉明距离 4 编码
- 245 张切片（冠状 + 矢状），4 只小鼠
- ~930 万个细胞，9.3 百万通过质控
- 配准至 Allen CCF v3

### 关键发现
- 16 个一级、130 个二级空间模块（大多与已知解剖边界对应，少数揭示更精细分区）
- 星形胶质细胞：36 个集群，各有独特空间分布
- 纹状体 D1/D2 MSN 背外侧—腹内侧梯度
- IT 神经元在皮层深度轴上的连续梯度
- 多处脑区空间梯度（下丘脑、脑干）

### 改变了什么理解
- 发现大脑组织原则不仅是"分区"（region A / region B），也是"梯度"（连续变化的分子特性）
- 胶质细胞多样性的程度远超预期

### 证据强度
高——多只动物，冠状+矢状双方向，与独立 scRNA-seq 交叉验证。

### 局限
- MERFISH 1,122 个基因仍非全转录组
- 细胞分割误差在密集区域可能引入噪声
- 同上，成年快照

---

## 来源 3：Zhang M et al. 2021（PMID:34616063）
**Spatially resolved cell atlas of the mouse primary motor cortex by MERFISH**
*Nature* 598:137–143. DOI:10.1038/s41586-021-03705-x. PMCID:PMC8494645

### 解决什么问题
验证 MERFISH 技术在皮层细胞类型识别中的可行性，并揭示初级运动皮层（MOp）的细胞类型空间组织。

### 方法
- MERFISH：~300,000 个细胞，识别 95 个神经元和非神经元集群
- 初级运动皮层单一区域

### 关键发现
- MOp 组成：57% 谷氨酸能 / 7% GABA 能 / 36% 非神经元
- IT 神经元沿皮层深度轴形成连续梯度（非离散分层）
- GABAergic 亚类：Pvalb 43%，Sst 22%，Lamp5 18%，Vip 15%，Sncg 2%

### 历史意义
先驱性验证了 MERFISH 在皮层细胞图谱绘制中的可行性和精度，为后续全脑图谱奠定方法学基础。

### 证据强度
高——单区域精细验证，与电生理/形态学数据交叉验证。

---

## 来源 4：NIH BICCN 官方网站
**URL**：https://biccn.org
**类型**：官方机构来源
**用途**：背景、项目设计、数据集描述

---

## 来源 5：Allen Brain Cell Atlas
**URL**：https://portal.brain-map.org
**类型**：官方机构来源（Allen Institute for Brain Science）
**用途**：交互式数据浏览平台，MERFISH 数据可视化

---

## 今日选题理由

近期文章（#138-#142）集中在疾病和分子机制层（兴奋毒性、线粒体功能障碍、ALS、LLPS），需要切换到方法革命层（课程脊柱第 10 项）。空间转录组学是 2023 年神经科学最重要的方法突破之一，且目前知识库中尚无独立的空间转录组学页面，是明确的悬空引用缺口。

## 悬空引用识别
今日文章引入的新概念，需要在 wiki 中建立页面：
- `spatial-transcriptomics`（新建）
- `brain-cell-type-hierarchy`（新建）
- `merfish`（可并入 spatial-transcriptomics 或单独建）

可能需要修订的已有页面：
- `wiki/methods/connectomics.md`（补充空间转录组学与连接组学的互补关系）
- `wiki/systems/astrocyte.md`（补充空间多样性数据）

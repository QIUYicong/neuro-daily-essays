# 读书笔记 · 2026-09-02

**主题**：小脑 + 主动推断 / 本体感觉先验
**对应文章**：`2026-09-02-cerebellum-active-inference-proprioceptive-prior.md`
**Q-fep-01 追踪**：首次系统性回应

---

## 来源 1：Parr, Ramstead, Friston (2025) — "Priors and Proprioceptive Predictions"
PMID: 41451122 | PMCID: PMC7618530 | DOI: 10.1016/j.cobeha.2025.101509
**全文可用**：是（PMC）

### 核心论点
- 运动控制不需要逆向模型；本体感觉预测 = 脊髓反射弧的目标设定点
- 主动推断中，"运动命令"是下级牵张反射接收的本体感觉预期（均值+协方差）
- 精度分解为：空间分量（影响反射增益，γ 运动神经元）+ 时间分量（基于自相关，影响振荡倾向）
- 小脑核团（DCN）调节时间精度估计
- 三大兼容框架：平衡点假说 + 感知控制理论 + 主动推断

### 对理解认知的意义
- 运动控制 = 大脑对身体状态的"生成模型推断"的一个实例
- DCN 不仅是"输出中继"，而是精度计算节点
- 时间精度过高 → 振荡（小脑综合征的一个计算解释）

### 证据强度
- 理论框架强（数学一致性高）；直接神经实验验证少（框架性论文，非实验性论文）
- 对临床预测有一致性，但机制性因果验证尚待开展

### 局限
- 短评性文章（7页），更多是概念框架，实验数据引用来自其他来源

---

## 来源 2：Nguyen & Person (2025) — "Cerebellar circuit computations for predictive motor control"
PMID: 40523942 | PMCID: PMC12643008
**全文可用**：是（PMC）
期刊：Nature Reviews Neuroscience（权威综述）

### 核心论点
1. **颗粒细胞时间基础集**：不同 GC 亚群在运动的不同时刻发放，形成时间展开的高维编码空间
2. **浦肯野细胞异质性**：部分 PC 在运动时降低放电（去抑制 DCN，产生运动命令），部分增加；群体编码才有意义
3. **攀爬纤维 LTD**：仍是监督学习的核心（攀爬纤维 = 教师信号）
4. **关键争议**：小脑可能实现的是"模型无关的前馈映射"而非"显式内部模型"——这是对 Wolpert-Kawato 框架的直接挑战

### 对 wiki 的影响
- `forward-model.md`：需要新增这一矛盾（内部模型 vs 前馈映射）
- `cerebellum.md`：需要更新"当前理解"段落，加入 Nguyen & Person 的观点

### 证据强度
- 高质量综述；引用了多个独立实验室的钙成像和电生理数据
- "前馈映射 vs 内部模型"的分歧是领域前沿，尚未解决

---

## 来源 3：Tanaka, Ishikawa, Kakei (2019) — "Neural Evidence of the Cerebellum as a State Predictor"
PMID: 30627965 | PMCID: PMC6517560
**全文可用**：是（PMC）
期刊：Cerebellum

### 关键数据
- 94 苔藓纤维 + 83 浦肯野细胞 + 73 齿状核细胞（1只猕猴）
- 齿状核在 t 时刻的活动预测 t+20ms 的苔藓纤维活动：R²=0.89
- 预测 t+100ms：R²=0.86（覆盖整个感觉反馈延迟窗口）
- 提出三步卡尔曼滤波器类比

### 局限
- 单只动物；线性重建只能证明"信息存在于网络中"，不能证明因果机制
- R² 值高但不能完全排除相关性解释

---

## 来源 4：Kakei, Manto, Tanaka, Mitoma (2021) — "Pathophysiology of Cerebellar Tremor"
PMID: 34262527 | PMCID: PMC8273235
**全文可用**：是（PMC）
期刊：Frontiers in Neuroscience

### 两类震颤框架
1. **前向模型相关震颤**：大脑小脑（长环路）受损，预测能力丧失，代偿延迟增加
   → 不规则的意向性震颤
2. **下橄榄核振荡相关震颤**：IO 神经元异常同步，通过短环路产生规则振荡
   → 规则的姿势性震颤

### 临床意义
- Holmes 震颤（混合两种机制）
- 区分两种类型有助于靶向治疗

---

## 来源 5：Palacios, Houghton, Chadderton (2021) — "Accounting for uncertainty: inhibition for neural inference in the cerebellum"
PMID: 33757352 | PMCID: PMC8059656
**全文可用**：是（PMC）
期刊：Proc R Soc B

### 核心主张
- 高尔基细胞（Golgi cell）= 精度加权机制
- 通过反馈抑制调节颗粒细胞活跃度，从而控制传递信号的"确信度"
- 不确定性 → Golgi 抑制增强 → GC 活跃度降低 → 低置信传递

### 证据强度
- 计算建模结合已知生理学；缺乏直接体内验证"Golgi cell = 精度计算器"的实验

---

## 来源 6：Boisgontier & Swinnen (2014) — "Proprioception in the cerebellum"
PMID: 24782740 | PMCID: PMC3988398
**全文可用**：是（PMC）
期刊：Frontiers in Human Neuroscience

### 关键发现
- 颗粒细胞可混合来自脊髓小脑传导束的本体感觉信号和来自大脑皮层的传出拷贝
- 小脑损伤患者失去"主动运动改善本体感觉"的优势（被动运动本体感觉不受影响）
→ 直接证明：小脑的预测模型提升了本体感觉精度

---

## 来源 7：Friston & Herreros (2016) — "Active Inference and Learning in the Cerebellum"
PMID: 27391681
**全文可用**：否（Neural Computation；未读全文，仅摘要）

### 摘要要点
- 眼睑条件化（eyeblink conditioning）作为主动推断的小脑模型
- 将 Pavlovian 条件化映射为变分自由能最小化
- 模型再现了时间和轨迹条件化的选择性损伤模式

---

## 来源 8：Wolpert, Miall, Kawato (1998) — "Internal models in the cerebellum"
DOI: 10.1016/S1364-6613(98)01221-2
**全文可用**：否（经典论文，仅参阅综述引用）

### 历史背景要点
- 前向/逆向模型框架
- MOSAIC：多对前向/逆向模型，责任信号动态选择
- 奠定了随后二十年的小脑计算理论

---

## 总结与待处理事项

### 新增未解问题
- Q-fep-01 (A)：部分回答，神经实现机制仍待验证
- Q-fep-01 (B)：部分支持，皮层/小脑分工仍待实验
- Q-fep-01 (C)：仍开放，实验设计挑战大

### 新登记矛盾
- C-2026-09-02-01：内部模型 vs 前馈映射（Wolpert-Kawato vs Nguyen & Person）

### 需要更新的 wiki 页面
1. `wiki/concepts/forward-model.md`：加新矛盾；加主动推断视角；rev_count 1→2
2. `wiki/systems/cerebellum.md`：加主动推断段落；新 key_sources；rev_count 3→4
3. `wiki/theories/active-inference.md`：加小脑子节；rev_count 1→2
4. 新建 `wiki/concepts/proprioceptive-prediction.md`
5. 新建 `wiki/concepts/precision-prior.md`（或合并进相关页）

# 阅读笔记：2026-05-30 杏仁核恐惧记忆

*对应文章：2026-05-30-amygdala-fear-memory.md*

---

## 来源 1：Blair et al. 2001（PMID:11584069）
**标题**：Synaptic plasticity in the lateral amygdala: a cellular hypothesis of fear conditioning
**期刊**：Learning & Memory
**全文**：摘要（未读全文）

**核心问题**：LA中什么细胞机制使CS-US关联得以存储？
**方法**：理论综述，整合行为药理学（APV注射）和电生理数据
**关键发现**：
- CS激活LA神经元弱AMPA突触；US强烈去极化同一神经元
- 去极化移除NMDA受体Mg²⁺阻塞 → Ca²⁺内流 → LTP
- NMDA受体激活对短期记忆可能不必要，但对长期记忆必须
- L型钙通道提供第二条Ca²⁺入路，通过bAP（反向传播动作电位）激活
- bAP+US联合激活L型通道，可能对L-LTP的固结有重要作用
**证据强度**：高（多实验室重复）
**局限**：综述文章，部分假设尚未直接验证

---

## 来源 2：Nabavi et al. 2014（PMID:24896183）
**标题**：Engineering a memory with LTD and LTP
**期刊**：Nature
**全文**：摘要（未读全文）

**核心问题**：LTP/LTD是否是恐惧记忆的真正因果底物？
**方法**：光遗传LTP/LTD + 行为测试（恐惧冻结）
**关键发现**：
- 光遗传LTP增强LA听觉输入突触 → 无电击训练即产生CS-触发冻结
- 随后光遗传LTD削弱同一批突触 → 冻结消失
- 再次光遗传LTP → 冻结恢复
- **这是双向可逆因果证明：恐惧=LA突触权重变化**
**证据强度**：极高（直接因果，最高标准）
**局限**：是否所有恐惧记忆都完全依赖LA？CeA内部可塑性的贡献？
**与认知地图关系**：与海马印迹细胞光遗传实验（Ramirez 2013）形成方法上的强连接

---

## 来源 3：Likhtik et al. 2008（PMID:18615014）
**标题**：Amygdala intercalated neurons are required for expression of fear extinction
**期刊**：Nature
**全文**：摘要（未读全文）

**核心问题**：ITC神经元在消退表达中是否必要？
**方法**：免疫毒素选择性损毁ITC + 行为测试
**关键发现**：
- ITC选择性损毁 → 恐惧获得正常，但消退表达严重受损
- 损伤程度与ITC神经元存活率负相关（量效关系）
- ITC细胞高度表达µ-阿片受体
**证据强度**：高（必要性直接损毁实验）
**局限**：损毁范围可能不精确；背侧/腹侧ITC的具体分工未直接区分
**未解问题**：ITC的µ-阿片受体如何调节恐惧消退？内源性阿片类系统？

---

## 来源 4：Herry et al. 2008（PMID:18615015）
**标题**：Switching on and off fear by distinct neuronal circuits
**期刊**：Nature
**全文**：摘要（未读全文）

**核心问题**：BA中是否存在专门的恐惧/消退神经元？
**方法**：多单元记录（多通道电极）+ 恐惧条件反射/消退行为范式
**关键发现**：
- BA中约两类神经元：恐惧细胞（条件反射后CS+），消退细胞（消退后CS+）
- 恐惧细胞 → 投射PL皮层；消退细胞 → 投射IL皮层（逆行标记）
- 不活化BA的特定神经元 → 阻断行为状态转变（不影响记忆本身）
- 海马→BA投射通过情景信息决定哪类细胞主导
**证据强度**：高（单细胞记录，直接行为相关性）
**局限**：主要在小鼠，人类是否存在类似双群？

---

## 来源 5：Duvarci & Paré 2014（PMID:24908482 / PMCID:PMC4103014）
**标题**：Amygdala microcircuits controlling learned fear
**期刊**：Neuron
**全文**：**开放全文（PMC4103014）**

**核心问题**：BLA/ITC/CeA的微回路如何组织恐惧与消退？
**方法**：综合电生理、形态学、药理学、光遗传学证据
**关键发现**：
- LA约80%是兴奋性谷氨酸能主神经元，20%是GABAergic中间神经元
- 条件反射后只有~20% LA神经元发展出增强的CS响应（稀疏代码）
- CeL-Off（PKCδ+）持续抑制CeM；CeL-On（SOM+）激活后抑制CeL-Off→去抑制CeM
- 消退后BA输入增强ICMMV，ICMMV增强激活后抑制CeM → 恐惧输出减少
- 恐惧细胞→PL；消退细胞→IL的双向回路（证实Herry 2008）
**改变了什么认识**：明确了ITC两个亚群的互补功能分工
**未解**：CeL-On/Off神经元在自然行为中的精确时序

---

## 来源 6：Luchkina & Bolshakov 2018（PMID:30415278 / PMCID:PMC6374177）
**标题**：Mechanisms of fear learning and extinction: synaptic plasticity–fear memory connection
**期刊**：Psychopharmacology
**全文**：**开放全文（PMC6374177）**

**核心问题**：恐惧学习与消退的突触机制如何统一理解？
**方法**：综述
**关键发现**：
- GluA1（非GluA2/3）在恐惧条件反射后在LA突触特异性增加
- 恐惧条件反射激活CaMKII（T286自磷酸化）→ GluA1-Ser831磷酸化
- 消退有两种机制并存：(1)去增强（depotentiation，NMDA/mGluR依赖LTD）+(2)新建抑制记忆（IL→ITC回路塑性）
- 两种机制可能在消退的不同阶段起主导作用：早期以去增强为主，后期以新记忆建立为主
**重要观点**：消退与LTD的分子机制重叠—丰富了LTD的生理意义

---

## 来源 7：Milad & Quirk 2012（PMID:22129456 / PMCID:PMC4942586）
**标题**：Fear extinction as a model for translational neuroscience: ten years of progress
**期刊**：Annual Review of Psychology
**全文**：**开放全文（PMC4942586）**

**核心问题**：消退的神经回路在啮齿类与人类之间有何共性与差异？
**方法**：横断面综述，整合啮齿类/人类fMRI数据
**关键发现**：
- vmPFC（人类IL同源区）激活越强，消退回忆越好（跨多项研究一致）
- vmPFC厚度与消退回忆能力正相关
- PTSD患者：条件反射正常，但消退**回忆**缺陷（训练时能消退，次日无法提取消退记忆）
- PTSD患者：vmPFC激活减弱 + 背侧前扣带回（dACC）激活增强 + 杏仁核对CS的夸大反应
- "PTSD是消退记忆提取障碍，不是消退获得障碍"这一观点有重要治疗意义（强化在安全情境中的消退回忆）
**改变了什么认识**：PTSD不是"学不会消退"，而是"已学会的消退在情境切换时提取失败"

---

## 来源 8：Plas et al. 2024（PMID:38370858 / PMCID:PMC10869525）
**标题**：Neural circuits for the adaptive regulation of fear and extinction memory
**期刊**：Frontiers in Behavioral Neuroscience
**全文**：**开放全文（PMC10869525）**

**核心问题**：最新数据如何更新我们对恐惧/消退回路的理解？
**方法**：综述（最新，含2022-2024数据）
**关键发现**：
- 蓝斑-NE系统在应激诱导的消退损害中起关键作用（β-肾上腺素信号在杏仁核）
- Nucleus reuniens（RE，丘脑核团）是mPFC-海马-杏仁核三角回路的关键枢纽，RE损伤损害消退回忆
- vmPFC→BLA投射的光遗传激活**促进**消退记忆形成；沉默该通路**损害**消退形成
- 恐惧回忆和消退回忆的竞争不只在BLA内部，还涉及更广泛的三角回路（mPFC-海马-杏仁核）

---

## 综合分析与认知连接

**最重要的跨来源整合**：
1. Nabavi 2014（因果LTP/LTD）× Luchkina 2018（分子机制）× Likhtik 2008（ITC必要性）→ 形成完整的"LA-LTP写入→ITC门控表达→IL覆写"因果链
2. Herry 2008（细胞群切换）× Plas 2024（情景回路）→ 恐惧/消退是双群神经元的竞争，情景门控来自mPFC-海马-RE三角
3. Milad & Quirk 2012（人类转化）→ 将动物机制连接到PTSD临床

**与知识库已有概念的连接**：
- LTP/LTD（核心分子机制）
- 印迹细胞（稀疏LA编码=恐惧印迹）
- 去甲肾上腺素（NE增强恐惧记忆巩固，Plas 2024明确）
- 海马回路（提供情景信息决定恐惧/消退哪种占主导）
- 记忆巩固（再巩固窗口是恐惧记忆更新的机会）
- 多巴胺（VTA→杏仁核DA调节奖励关联，与恐惧回路互补）

**新需要建立的wiki页**：
1. `systems/amygdala.md`：杏仁核整体解剖与功能（新建）
2. `concepts/fear-conditioning.md`：恐惧条件反射机制（新建）
3. `concepts/fear-extinction.md`：恐惧消退机制（新建）

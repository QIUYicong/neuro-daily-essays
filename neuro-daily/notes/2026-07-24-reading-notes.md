# 阅读笔记：2026-07-24（文章 #92）

**主题**：杏仁核恐惧印迹的竞争写入与消退记忆的奖励神经元基础

---

## 核心来源 1：LeDoux JE (2000) Emotion circuits in the brain. Annu Rev Neurosci. PMID:10845062

- **要解决什么问题**：杏仁核在恐惧学习中的角色是什么？情绪记忆的神经回路是什么？
- **方法**：综述，基于 LeDoux 实验室的经典恐惧条件反射系列研究
- **发现**：LA 是 CS-US 关联的写入位点；双路输入（丘脑低路/皮层高路）；LA→CeA 是恐惧输出通路
- **改变了什么理解**：确立"杏仁核=情绪记忆核心"的框架
- **证据强度**：综述，奠基性
- **局限**：2000 年，未涉及印迹细胞/光遗传学证据
- **与认知的关系**：感觉输入→价值标注→行为输出的基本框架

---

## 核心来源 2：Johansen JP, Cain CK, Ostroff LE, LeDoux JE (2011) Molecular mechanisms of fear learning and memory. Cell. PMID:22036561

- **要解决什么问题**：恐惧条件反射的分子级联是什么？
- **方法**：综述，整合体内药理学（NMDA 拮抗剂等）+ 分子生物学（CREB/CaMKII/ERK）数据
- **发现**：三时相（获取/巩固/再巩固）的完整分子链；GluA1 选择性上调；蛋白合成窗口
- **证据强度**：Cell 综述，多来源证据
- **局限**：综述，原始实验细节见引用文献
- **与认知的关系**：分子机制层面的 LTP 与联想学习的统一

---

## 核心来源 3：Herry C, Ciocchi S, Senn V, Demmou L, Müller C, Lüthi A (2008) Switching on and off fear by distinct neuronal circuits. Nature. PMID:18615015

- **要解决什么问题**：BA 中是否存在专门的"恐惧"和"消退"神经元？
- **方法**：大鼠，多单元电极记录，恐惧条件反射+消退范式，逆行荧光标记分离 PL 和 IL 投射神经元
- **发现**：BA 中两类神经元：恐惧细胞（条件后CS+，投射PL）和消退细胞（消退后CS+，投射IL）；情景切换驱动两群的快速切换
- **证据强度**：Nature，核心原始研究，多次被重复证实
- **局限**：大鼠实验；未能直接操控这两群细胞的活动（描述性）
- **未读全文**：是（只读摘要）

---

## 核心来源 4：Jeong Y et al. (2021) Synaptic plasticity-dependent competition rule influences memory formation. Nat Commun. PMID:34168140

- **要解决什么问题**：突触可塑性本身是否决定哪些神经元优先进入印迹（即：不只是"活动"，而是"突触权重"决定竞争）？
- **方法**：小鼠；靶向 LA 传入神经元的稀疏子集；光遗传 LTP 预增强；随后标准恐惧条件反射；c-Fos 追踪+行为测试；逆转实验（光学 LTD + 单独光学 LTP）
- **发现**：突触被预先增强的神经元优先编码恐惧记忆（更高 c-Fos 活化率；更强 CS 响应）；光学 LTD 逆转优先性；单独光学 LTP 足以驱动恐惧行为
- **证据强度**：Nat Commun（开放全文），严谨，多重证据
- **局限**：小鼠实验；LA 传入亚群（不是 LA 本身）的预增强，是否直接等效于 LA 内部的竞争仍有推断成分
- **与认知的关系**：竞争规则揭示了"为什么约 20% 的神经元被选中"的细胞内在原因
- **全文可用**：是（Nature Communications 开放全文）

---

## 核心来源 5：Zhang X, Kim J, Tonegawa S (2020) Amygdala Reward Neurons Form and Store Fear Extinction Memory. Neuron. PMID:31952856

- **要解决什么问题**：消退记忆的细胞载体是什么？消退印迹是什么类型的神经元？
- **方法**：小鼠；c-Fos-DREADD 系统在消退训练期间标记 BLA 活跃神经元；激活这些消退印迹细胞，测试奖励行为（条件性位置偏好）；反向：先标记奖励训练期间的 BLA 神经元，消退训练后测试是否获得 CS 响应
- **发现**：消退印迹细胞激活 → 奖励行为（趋近/CPP）；消退印迹细胞与奖励响应细胞高度重叠；激活奖励细胞 → 抑制条件恐惧
- **证据强度**：Neuron，开创性，但为单一实验室（Tonegawa lab）；独立重复有限
- **局限**：小鼠实验；未直接阻断奖励通路后测试消退是否失败（因果方向需更多验证）
- **未读全文**：是（Neuron 非开放）

---

## 核心来源 6：Luft JG et al. (2024) Distinct engrams control fear and extinction memory. Hippocampus. PMID:38396226

- **要解决什么问题**：消退记忆是修改了原始恐惧印迹，还是建立了全新的独立印迹？
- **方法**：大鼠；c-Fos-lacZ 转基因（Daun02 程序）；在消退训练后用 Daun02 灭活消退印迹细胞；随后测试恐惧行为
- **发现**：灭活 IL 皮层消退印迹 → 原始恐惧记忆重新激活；恐惧和消退印迹是不同细胞群（有重叠但功能分离）；消退依赖全新记忆存储
- **证据强度**：Hippocampus，方法论严谨（Daun02），但样本量有限
- **局限**：大鼠实验；Daun02 的特异性和完整性仍有技术争议；重叠率未定量

---

## 核心来源 7：Redondo RL, Kim J, Arons AL et al. (2014) Bidirectional switch of the valence associated with a hippocampal contextual memory engram. Nature. PMID:25162525

- **要解决什么问题**：同一记忆印迹的情感价值是否可以被逆转？如何实现？
- **方法**：TetTag 小鼠（c-Fos-tTA × TRE-ChR2）标记恐惧条件反射期间的海马 DG 印迹；然后在异性存在（奖励）情景下光激活这些 DG 印迹 → 测试情感价值是否逆转
- **发现**：原始恐惧 DG 印迹的情感价值可以从厌恶逆转为趋近；逆转依赖 DG→BLA 连接的重塑（BLA 连接权重变化）
- **证据强度**：Nature，严谨，但为单次重训范式（奖励情景重训），临床转化距离远
- **局限**：异性存在不是标准奖励；是否所有类型的恐惧记忆都可被如此逆转需验证

---

## 核心来源 8：Bouton ME, Maren S, McNally GP (2021) Behavioral and neurobiological mechanisms of Pavlovian and instrumental extinction learning. Physiol Rev. PMID:32970967

- **要解决什么问题**：消退是什么？为什么恐惧会"回来"？
- **发现**：消退 = 新的抑制性学习（不是抹除）；三类"恐惧重现"现象（自发恢复、更新、再激活）是核心证据；IL-海马-杏仁核三角回路
- **证据强度**：Physiol Rev（最高档综述期刊），综合力极强

---

## 核心来源 9：Bloodgood DW et al. (2018) Fear Extinction Requires Infralimbic Cortex Projections to the Basolateral Amygdala. Transl Psychiatry. PMID:29507292

- **方法**：小鼠，化学遗传学（DREADD）选择性阻断 IL→BLA 投射
- **发现**：阻断 IL→BLA 通路不影响消退训练期间的行为，但导致次日消退回忆完全失败 → IL→BLA 是消退记忆**存储**的必要条件（不只是表达通道）
- **证据强度**：Transl Psychiatry（开放全文），化学遗传学，因果证据

---

## 核心来源 10：Kredlow MA et al. (2022) Prefrontal cortex, amygdala, and threat processing: implications for PTSD. Neuropsychopharmacology. PMID:34545196

- **要解决什么问题**：PTSD 的 PFC-杏仁核回路异常是什么？
- **发现**：PTSD = 恐惧失调障碍；vmPFC 激活不足是消退回忆障碍的神经底物；人类的 vmPFC 对应 IL 皮层；光遗传/化学遗传在啮齿类的发现如何转化到临床干预

---

## 方法论笔记

1. **c-Fos-DREADD/TetTag/Daun02**：三种不同的印迹追踪方法，各有优缺：
   - c-Fos-DREADD：灵活激活/抑制，但存在漏标记
   - TetTag（TetO-ChR2 × c-Fos-tTA）：精准时间窗（dox 移除），适合双时间点标记
   - Daun02（c-Fos-lacZ + Daun02 灭活）：永久灭活，逻辑清晰，但不可逆

2. **物种差异注意**：小鼠 vs 大鼠的消退回路可能有差异；所有关键发现都需在第二物种中重复

3. **光遗传学的优缺点**：提供精确因果证据，但光传导需要手术植入，激活时机/范围与自然条件不同

---

## 术语笔记

- **CeL/CeM**：中央杏仁核外侧部（含 PKCδ+ OFF 细胞和 SOM+ ON 细胞，局部去抑制）/ 内侧部（输出引擎）
- **ITC（Intercalated Cells）**：插入细胞，GABAergic，散布于 BLA 与 CeA 之间；背侧（ICMMD）→ 消退时被门控关闭；腹侧（ICMMV）→ 消退时被 IL 激活，抑制 CeM
- **BNST（Bed Nucleus of Stria Terminalis）**：纹状体终末床核；CeA→BNST 投射介导持续性/广泛性焦虑（区别于 CeA→PAG 的即时冻结）
- **Daun02 程序**：向 c-Fos-lacZ 大鼠海马/杏仁核注射 Daun02，在指定时间窗内活跃（表达 β-gal 因 c-Fos 激活）的神经元被永久性化学灭活（Daun02 被 β-gal 转化为活性毒素）

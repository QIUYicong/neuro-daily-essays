---
title: 变分自编码器
slug: variational-autoencoder
domain: concepts
type: concept
status: established
confidence: high
created: 2026-07-13
updated: 2026-07-13
revision_count: 1
dimensions: [AI, cognition, whole-brain-network]
related: [predictive-coding, free-energy-principle, td-learning, complementary-learning-systems, world-model]
prerequisites: [predictive-coding, free-energy-principle]
opens_questions: [Q-pc-07]
source_articles: [2026-07-13-predictive-coding-free-energy-vae]
key_sources: ["arXiv:1312.6114", "PMID:20068583", "PMID:28333583"]
---

# 变分自编码器 (Variational Autoencoder, VAE)

> **一句话定义**：Kingma & Welling（2014）提出的深度生成模型，通过最大化证据下界（ELBO）学习数据的潜在表征，其数学目标（最小化重建误差+KL散度）与弗里斯顿自由能原理中的预测编码框架高度等价——两者都在解决同一个贝叶斯推理问题：如何从有限、噪声数据中学习一个生成世界的内部模型。

## 当前理解

我们现在认为，变分自编码器（VAE）与大脑预测编码框架之间存在深刻的数学对应，远超表面上的架构类比。

**VAE 的核心架构**：
- **编码器**（recognition model, $q(z|x)$）：把观测 $x$ 映射到潜变量 $z$ 的概率分布
- **解码器**（generative model, $p(x|z)$）：从潜变量 $z$ 生成重建数据 $\hat{x}$
- **目标函数（ELBO）**：$$\mathcal{L} = \mathbb{E}_{q(z|x)}[\log p(x|z)] - D_{KL}[q(z|x) \| p(z)]$$

**与预测编码的数学对应**：

| 概念 | VAE | 预测编码（弗里斯顿自由能） |
|------|-----|------------------------|
| 观测数据 | $x$ | 感觉输入 $\tilde{s}$ |
| 潜变量分布 | $q(z|x)$（编码器） | $q(\vartheta)$（内部信念） |
| 生成模型 | $p(x|z)$（解码器） | $p(\tilde{s}|\vartheta)$ |
| 重建误差 | $-\mathbb{E}[\log p(x|z)]$ | 预测误差（加精度权重） |
| 复杂度惩罚 | $D_{KL}[q(z|x)\|p(z)]$ | KL 散度（信念偏离先验） |
| 优化目标 | 最大化 ELBO | 最小化变分自由能（等价）|

**关键洞察**：最大化 ELBO 等价于最小化变分自由能。两个框架在数学上是同一个变分贝叶斯推理问题的两种表述，分别在人工神经网络和生物神经网络中独立发现。

## 关键机制

### ELBO 推导

$$\log p(x) \geq \mathbb{E}_{q(z|x)}[\log p(x|z)] - D_{KL}[q(z|x) \| p(z)] = \text{ELBO}$$

ELBO 是观测数据对数似然的下界（Evidence Lower BOund）。最大化 ELBO 同时实现了：
1. **最大化重建准确性**：学习的生成模型应能从潜变量重建观测数据
2. **正则化潜变量**：编码器学到的潜变量分布不能偏离先验 $p(z)$ 太多

### 重参数化技巧

VAE 训练时，梯度需要通过采样节点（无法直接反向传播）。Kingma & Welling 提出重参数化技巧：$z = \mu + \sigma \odot \epsilon$，其中 $\epsilon \sim \mathcal{N}(0, I)$，使梯度可以反向传播到 $\mu$ 和 $\sigma$。

### 与预测编码的关键区别

尽管数学目标等价，VAE 和预测编码在实现上有根本差异：
1. **学习规则**：VAE 用全局反向传播；预测编码用局部赫布规则（Whittington & Bogacz 2017, PMID:28333583）
2. **时间动力学**：VAE 推理是单次前向传播；预测编码推理是迭代收敛过程
3. **行动**：VAE 无法执行"通过行动改变感觉输入"；弗里斯顿的主动推断框架可以
4. **分布外泛化**：两者在未见分布上的失败模式尚未系统比较

## 关键证据

| 主张 | 证据 / 方法 | 来源 | 置信度 |
|------|------------|------|--------|
| ELBO 最大化等价于变分自由能最小化 | 数学推导；两套方程直接对比 | arXiv:1312.6114；PMID:20068583 | 高（数学等价，已形成共识）|
| VAE 可以学习有意义的潜变量表征（人脸、语义） | 大量图像和文本 VAE 实验 | arXiv:1312.6114 | 高（工程实践广泛验证）|
| PC 网络中局部赫布规则可收敛于反向传播 | 数学证明 | PMID:28333583 | 高（数学定理，条件苛刻）|

## 连接

- [[predictive-coding]] — 预测编码与 VAE 共享变分贝叶斯优化目标
- [[free-energy-principle]] — FEP 的数学框架与 ELBO 等价
- [[td-learning]] — TD 学习（奖励层面）与预测编码（感觉层面）是同一"预测-误差-更新"循环的不同领域
- [[complementary-learning-systems]] — CLS 的情景记忆（海马）/ 统计学习（皮层）分工与 VAE 的编码器/解码器有类似的信息分工
- [[world-model]] — VAE 学到的潜变量空间是一种人工"世界模型"，类比大脑的内部世界表征

## 未解问题

- Q-pc-07（中优先级）：VAE 编码器（识别模型）与皮层前馈通路的对应是否超出数学类比？两者在面对分布外输入时的失败模式是否相似？

## 修订历史

- 2026-07-13 · 创建 · 基于《大脑的预言机》（#81）一文 · 来源：VAE 文章（arXiv:1312.6114）与 Friston 自由能原理（PMID:20068583）数学对比 · 初始置信度：高（工程实践广泛验证；数学等价已形成共识；神经对应仍在探索中）

## 来源文章

- [[2026-07-13-predictive-coding-free-energy-vae]]

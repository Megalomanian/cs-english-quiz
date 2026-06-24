# 第7章 机器学习与人工智能 — Machine Learning and Artificial Intelligence

---

## 📝 核心词汇

### 人工智能基础

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **artificial intelligence** | /ˌɑːtɪˈfɪʃl ɪnˈtelɪdʒəns/ | 人工智能 | AI enables machines to simulate human intelligence. | 简称 AI |
| **machine learning** | /məˈʃiːn ˈlɜːnɪŋ/ | 机器学习 | Machine learning allows systems to learn from data without explicit programming. | AI 的核心子领域 |
| **deep learning** | /diːp ˈlɜːnɪŋ/ | 深度学习 | Deep learning uses multi-layered neural networks to model complex patterns. | ML 的子领域 |
| **neural network** | /ˈnjʊərəl ˈnetwɜːk/ | 神经网络 | Neural networks are inspired by the structure of the human brain. | 深度学习的核心架构 |
| **algorithm** | /ˈælɡərɪðəm/ | 算法 | ML algorithms improve their performance as they are exposed to more data. | 机器学习的数学基础 |
| **model** | /ˈmɒdl/ | 模型 | A trained ML model can make predictions on new data. | 训练后的算法产物 |

### 学习类型

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **supervised learning** | /ˈsuːpəvaɪzd ˈlɜːnɪŋ/ | 监督学习 | In supervised learning, models are trained on labeled data. | 有标签数据，输入→输出映射 |
| **unsupervised learning** | /ʌnˈsuːpəvaɪzd ˈlɜːnɪŋ/ | 无监督学习 | Unsupervised learning finds hidden patterns in unlabeled data. | 无标签数据，发现隐藏结构 |
| **reinforcement learning** | /ˌriːɪnˈfɔːsmənt ˈlɜːnɪŋ/ | 强化学习 | Reinforcement learning trains agents through rewards and penalties. | 通过奖惩机制学习 |
| **classification** | /ˌklæsɪfɪˈkeɪʃn/ | 分类 | Classification predicts which category an input belongs to. | 监督学习的一种 |
| **regression** | /rɪˈɡreʃn/ | 回归 | Regression predicts a continuous numerical value. | 监督学习的一种 |
| **clustering** | /ˈklʌstərɪŋ/ | 聚类 | Clustering groups similar data points together. | 无监督学习的一种 |

### 训练与评估

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **training data** | /ˈtreɪnɪŋ ˈdeɪtə/ | 训练数据 | The model learns patterns from training data. | 用于模型学习的样本数据 |
| **feature** | /ˈfiːtʃə(r)/ | 特征 | Selecting relevant features improves model accuracy. | 输入变量的属性 |
| **label** | /ˈleɪbl/ | 标签 | Each training example in supervised learning has a label. | 监督学习中的正确答案 |
| **overfitting** | /ˌəʊvəˈfɪtɪŋ/ | 过拟合 | Overfitting occurs when a model learns noise instead of patterns. | 模型复杂度太高导致 |
| **generalization** | /ˌdʒenrəlaɪˈzeɪʃn/ | 泛化 | Good models generalize well to unseen data. | 模型在新数据上的表现 |
| **accuracy** | /ˈækjərəsi/ | 准确率 | Accuracy measures the proportion of correct predictions. | 模型评估指标 |
| **bias** | /ˈbaɪəs/ | 偏差 | Bias refers to systematic errors in model predictions. | 模型简化带来的误差 |
| **variance** | /ˈveəriəns/ | 方差 | High variance means the model is too sensitive to small data changes. | 偏差-方差权衡 |
| **optimization** | /ˌɒptɪmaɪˈzeɪʃn/ | 优化 | Gradient descent is a common optimization algorithm. | 寻找最优参数 |

### 应用领域

| 术语 | 英文 | 说明 |
|:---|:---|:---|
| 自然语言处理 | Natural Language Processing (NLP) | 文本分析、翻译、对话系统 |
| 计算机视觉 | Computer Vision (CV) | 图像识别、物体检测 |
| 语音识别 | Speech Recognition | 语音转文字 |
| 推荐系统 | Recommendation System | 个性化内容/商品推荐 |
| 大语言模型 | Large Language Model (LLM) | 如 GPT 系列，生成文本 |
| 生成式AI | Generative AI | 生成文字、图像、视频等内容 |

---

## ✍️ 长句分析

### Sentence 1
> Machine learning is a subset of artificial intelligence that enables computer systems to learn from data and improve their performance over time without being explicitly programmed for every scenario.

**机器学习是人工智能的一个子集，使计算机系统能够从数据中学习并随时间改进性能，而无需为每种场景显式编程。**

- **定语从句：** that enables computer systems to learn...
- **without + 动名词：** without being explicitly programmed
- **重点词汇：** subset（子集）、artificial intelligence（人工智能）、explicitly（显式地）

### Sentence 2
> In supervised learning, algorithms are trained on labeled datasets where each input is paired with a correct output, allowing the model to learn the mapping from features to predictions.

**在监督学习中，算法在带标签的数据集上训练，每个输入都配有一个正确的输出，使模型能够学习从特征到预测的映射。**

- **定语从句：** where each input is paired with a correct output
- **现在分词：** allowing the model to learn the mapping...
- **重点词汇：** supervised learning（监督学习）、labeled（带标签的）、mapping（映射）、feature（特征）

### Sentence 3
> Deep learning utilizes multi-layered artificial neural networks to automatically extract hierarchical features from raw data, eliminating the need for manual feature engineering.

**深度学习利用多层人工神经网络自动从原始数据中提取层次化特征，消除了手动特征工程的需求。**

- **不定式：** to automatically extract hierarchical features...
- **现在分词：** eliminating the need for manual feature engineering
- **重点词汇：** deep learning（深度学习）、neural network（神经网络）、hierarchical（层次化的）、feature engineering（特征工程）

### Sentence 4
> Overfitting occurs when a model becomes too complex and learns the noise in the training data rather than the underlying patterns, resulting in poor generalization to new, unseen data.

**当过拟合发生时，模型变得过于复杂，学习了训练数据中的噪声而非底层模式，导致对新数据的泛化能力很差。**

- **时间状语从句：** when a model becomes too complex...
- **rather than：** rather than the underlying patterns
- **现在分词：** resulting in poor generalization
- **重点词汇：** overfitting（过拟合）、noise（噪声）、underlying（底层的）、generalization（泛化）

### Sentence 5
> The bias-variance trade-off is a fundamental challenge in machine learning: high bias leads to underfitting and missed patterns, while high variance causes overfitting and sensitivity to small fluctuations in the training data.

**偏差-方差权衡是机器学习中的一个基本挑战：高偏差导致欠拟合和遗漏模式，而高方差导致过拟合和对训练数据中小波动的敏感性。**

- **冒号解释：** ...is a fundamental challenge: high bias leads to... while high variance causes...
- **对比连词：** while，对比偏差和方差的不同影响
- **重点词汇：** bias（偏差）、variance（方差）、trade-off（权衡）、underfitting（欠拟合）、overfitting（过拟合）

---

## 📄 核心概念

### 三种学习范式

| 范式 | 数据 | 目标 | 典型应用 |
|:---|:---|:---|:---|
| **监督学习** | 有标签 | 学习输入→输出映射 | 图像分类、房价预测、垃圾邮件检测 |
| **无监督学习** | 无标签 | 发现数据结构 | 客户分群、异常检测、降维 |
| **强化学习** | 环境交互 | 最大化累积奖励 | 游戏 AI、机器人控制、自动驾驶 |

### 偏差-方差权衡

| 问题 | 表现 | 原因 | 解决 |
|:---|:---|:---|:---|
| **高偏差（欠拟合）** | 训练集和测试集都差 | 模型太简单 | 增加模型复杂度、更多特征 |
| **高方差（过拟合）** | 训练集好、测试集差 | 模型太复杂 | 正则化、更多数据、简化模型 |

### AI/ML 发展时间线

| 时期 | 里程碑 |
|:---|:---|
| 1950s | AI 概念提出、图灵测试 |
| 1980s | 专家系统、反向传播算法 |
| 2000s | 大数据+GPU 推动深度学习复兴 |
| 2010s | AlexNet、GAN、Transformer |
| 2020s | 大语言模型（GPT）、生成式 AI 爆发 |

---

## 🗣️ 口语练习

**练习形式：** 技术概念解释

**场景：** 向非技术背景的同学解释机器学习和人工智能。

**示例对话：**
- Q: "What's the difference between AI and machine learning?"
- A: "AI is the broad goal of making machines intelligent. Machine learning is a specific approach where systems learn from data rather than following explicit rules."
- Q: "How does a machine actually 'learn'?"
- A: "Think of it like teaching a child. In supervised learning, you show many labeled examples — 'this is a cat, this is a dog' — and the algorithm gradually learns to tell them apart by finding patterns in the data."
- Q: "What can go wrong?"
- A: "A common problem is overfitting — the model memorizes the training examples instead of understanding general patterns, so it fails on new data."

---
*信息工程学院 丁彤 | tongding@nxu.edu.cn*

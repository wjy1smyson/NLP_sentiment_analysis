# NLP_Sentiment_Analysis
## 项目简介
本项目旨在利用 BERT 模型进行情感分析任务。通过使用 Twitter 数据集，模型能够对文本进行分类，识别出文本的情感标签（例如：积极、消极、中立、无关）。本项目的核心是使用Pytorch深度学习框架，使用BERT 进行微调，并通过 Scikit-learn相关功能模块实现模型训练和评估。最后将实验结果与逻辑回归、支持向量机、随机森林三种算法的实验结果对比。
## 数据集
本项目使用的训练数据集和验证数据集来自于 Twitter 情感分析任务。数据集包含了推文文本及其对应的情感标签。
### 数据文件
twitter_training.csv:训练数据集，包含推文文本及其对应的情感标签。

twitter_validation.csv:测试数据集，包含验证集的推文文本及其对应的情感标签。

### 数据字段：

id: 数据标识符

topic: 推文话题

sentiment: 情感标签（包括 Negative, Positive, Neutral, Irrelevant）

text: 推文内容

## 环境要求

Ubuntu 20.04

Python >= 3.8

PyTorch >= 1.7

Transformers (Hugging Face) >= 4.0

tqdm

scikit-learn

pandas


## 使用方法

clone本项目，在nlp.ipynb中修改对应模型与数据集的路径。运行该文件即可。

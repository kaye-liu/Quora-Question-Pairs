# Quora-Question-Pairs
Can you identify question pairs that have the same intent?
### 项目课题
句子相似度匹配
地址：https://github.com/udacity/cn-machine-learning/tree/master/quora-question-duplicate
### 项目环境
Anaconda jupyter Notebook5.6.0
### 本项目用到的库
- warnings
- numpy
- pandas
- matplotlib
- gensim
- time
- sklearn
- timeit
- string
- nltk
- fuzzywuzzy
- tqdm
- scipy
- csv
- xgboost

### 数据准备
数据集下载地址：https://www.kaggle.com/c/quora-question-pairs/data
额外数据GoogleNews-vectors-negative300.bin下载地址：https://s3.amazonaws.com/dl4j-distribution/GoogleNews-vectors-negative300.bin.gz
### 项目运行时间
在我自己的电脑上大约需要一个小时，电脑配置如下：
- 处理器：2.4GHz Intel Core i5
- 内存：8GB 1600MHz DDR3
- 图形卡：Intel iris 1536 MB
- 操作系统：macOS Mojave 10.14.1

### 项目文件说明
- 项目运行过程中产生的特征工程文件存储在“features_file”文件夹中
- 数据集需下载并放在“quora_dataset”文件夹中
- GoogleNews-vectors-negative300.bin文件下载后存储在“词向量_for_toxic”文件夹中

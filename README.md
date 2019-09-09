# Twitter-airline-sentiment-analysis
对twitter上的航空公司评价进行情感分类(kaggle的数据集)

分别基于CBOW和词向量进行预测
CBOW：集成学习模型，分别训练学习器SVM，随机森林，Naive Bayes，和逻辑回归，用多数表决来决定最后的分类 acc:80.11%
词向量：基于Bert动态词表征来训练分类器，进行预测  acc:85.1%

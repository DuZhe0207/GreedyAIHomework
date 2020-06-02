# 贪心学院NLP课程代码



本项目主要是记录一下我自己的练习，里面的代码可能写的并不好但是用jupyter notebook是都能运行的



## 小练习

`Python 编程学习.ipynb`：lambda、map、filter、reduce、闭包、装饰器等练习





## 项目

### 项目1

#### 分词工具编写

- 利用枚举法来实现分词，也就是首先把所有可能的分词结果列出来，然后通过UNIGRAM模型来选择最好的分词结构（这部分的难点在于怎么生成所有的可能的分词结果）（已完成）
- 利用维特比算法来实现分词。这部分首先需要创建一个有向图，然后根据维特比算法来计算出最好的分词结果。这部分里的创建有向图和维特比部分需要一定的思考。 （已完成）

#### 简单的问答系统编写

- 文本的读取： 从JSON文件里读数据，并把文本写到问题变量和答案变量中（list）（已完成）
- 文本的预处理： 需要对原始文本做预处理操作，包括一些词的过滤（已完成）
- 文本的表示： 把文本转换成tf-idf格式/词向量，句子向量（已完成）
- 文本相似度计算： 利用余弦相似度来计算文本之间的相似度（已完成）
- 倒排列表：通过倒排列表来加快文档的检索
- 用词向量完成问答系统


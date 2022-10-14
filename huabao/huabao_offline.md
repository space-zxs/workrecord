## huabao_offline

### make_action_top_dict

- 从hdfs中拷贝数据到本地
- 解析数据从redis中获取全局数据，到列表或字典
- 生成静态/动态壁纸的，use、click、preview、cold、类别的倒排高热

### make_use_profile

- 从hdfs中同步action数据
- 解析数据从redis中取出类别标签，统计点击次数
- 生成用户profile的dict

### train_item_vec

faiss 

https://github.com/facebookresearch/faiss

faiss 使用gpu进行数十亿规模的相似性搜索  

https://arxiv.org/abs/1702.08734

#### icf,make_similar_item

- 将用户对资源的点击序列，转化为资源的倒排
- sent2vec 将字符串分词(资源的倒排)转变为一个固定长度的向量（url_pemb.scr）
- 将向量和资源数据单独存储在列表，用faiss给向量列表建立索引，通过train方法和add方法
- 通过index的search，返回新资源最相似的k个向量，通过倒排找到具体的资源数据，存储到icf.dict  

### train_rank_model

通过make_train_log.py，读取数据，组合特征，生成train/test log文件

通过train_model.py 拼接路径调用 bin中的命令执行data中的数据文件

### problem 

url.pemb.scr 文件的生成 （可能是用户embedding的均值）

    如何表达user embedding 向量呢，

    有两种想法：1.先进行item-user倒排索引，把user作为单词，通过item2vec的方法计算user的向量，这样对于新的user id或者未参与训练的userid，如何获取embedding向量呢

    2. 通过user-item矩阵，计算item向量，然后如何表示user向量呢，如果把item 向量拼接起来，特征维度会比较多，如果用多个item向量mean的方式，这个user embedding 特征的意义是什么

fm.model 数据的生成

fm.model 中用'/1'分割

特征的选取

label 0  ，点击 1

一个用户一个模型

pred 文件含义
### 准确率的计算

auc.python 读取 pred 文件

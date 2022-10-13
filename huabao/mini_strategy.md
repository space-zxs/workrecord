## mini_strategy
***
make package 出现cannot stat ‘news_push’: No such file or directory错误

### conf 

配置文件中的resource 含义

### parse_plugin 
基础信息中rel_n来自引擎，要展示的数量

recall_map 中取出recall_type，取出要一种类型放置的最小值和最大值

设定返回条数上限，真实展现条数的1.5倍，超过一百则重置为99

从resource中取出每一类数据的数量值，每个类别最多存储200个

解析用户基本信息、返回召回的数据列表设置阈值、解析每条item的信息、填充item中的特征信息

### filter_plugin

### insert_plugin

idx 和 recall 强插

将需要强插的数据，添加到候选数据列表，优先处理召回强插

### diversity_plugin

三种多样性处理

common多样性 

从候选列表中选择每个类型，赋给idx值。

在news列表中但不在强插列表中的赋给0值

conf 多样性

mscore乘了一个分数衰减数



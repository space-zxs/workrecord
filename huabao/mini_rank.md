# MINI_RANK
****
调用rank的服务返回十条被打分的数据

![image](https://user-images.githubusercontent.com/77714764/193181870-67bf3a3b-5813-438d-a380-033e654770f7.png)

为什么召回里面解析了用户的历史点击和展现，rank里面还要重新解析

**FM 的解释**

一般的线性模型：

![image](https://user-images.githubusercontent.com/77714764/194702171-9ad0948e-4d0f-4399-a795-85f76e515bd5.png)

线性模型可以进行预测，但是由于one_hot 编码带来的巨大维度、以及无法表示特征之间的相互关系，fm模型在线性模型上增添了一项：

![image](https://user-images.githubusercontent.com/77714764/194702292-c8cf4db5-563e-4d0b-a39c-57c2ddfa6b22.png)


**FM 的三个优点**

- 可以在非常稀疏的数据中进行合理的参数估计
- FM模型的时间复杂度是线性的
- FM是一个通用模型，它可以用于任何特征为实值的情况
****
**整体实现的流程**‘

- 将多路召回里面返回的数据和rank中解析出的当前用户的历史点击、展现数据，组合成数据列表
- 根据数据id，解析数据的详细信息，比如类型、分类等
- 通过FM预测数据的分数
- 返回带有预测分数的数据列表

# 按喜好图文、视频的用户分成两组

## 0908-2days

### 时间: 2022-09-08 09:31:38,push_id: 220908-01

- 内容： 图文和视频
- test相对于base点击下降41%，ctr下降46%，跟0907第一次push相同
- 混和内容，test没有选出大部分喜欢的新闻

**base和test比较**

![image](https://user-images.githubusercontent.com/77714764/189029802-36753b37-caaa-4433-a02a-cae1ddeb0075.png)

base组的新闻数据

![image](https://user-images.githubusercontent.com/77714764/189030395-2cab394c-be82-422d-95dd-d880d98143c9.png)

test组的新闻数据

![image](https://user-images.githubusercontent.com/77714764/189030272-421d7838-643c-4773-b032-6e5f679959e0.png)

可以发现两组中高pv的数据完全不一样，并且test组中的高pv新闻没有对应高点击，因此最后的点击率跟base差距很大。可能因为分组的特征并不明显，并不能选出大部分人喜欢的新闻数据。

**test组中喜欢图文和视频的新闻数据比较**

喜欢图文分组

![image](https://user-images.githubusercontent.com/77714764/189031264-fb21947d-94a3-4134-bf46-cac9f31311c8.png)

没有选出高热的图文数据，高pv的都是视频

喜欢视频分组

![image](https://user-images.githubusercontent.com/77714764/189031438-c2400a78-d8ab-448f-ab3c-51b3a666925a.png)

数据量太少，结果可能不可信

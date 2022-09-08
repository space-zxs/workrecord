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

### 时间: 2022-09-08 11:31:48，push_id: 220908-02
- 内容：图文
- test相对于base的点击提升4.6%，ctr提升3%
- 单一内容，ctr出现小幅增长

**test和base的比较**

![image](https://user-images.githubusercontent.com/77714764/189093972-32b69b33-efa1-43dd-b3cb-0a9d5f2b21b2.png)

base组的新闻数据

![image](https://user-images.githubusercontent.com/77714764/189094275-1d5eacf4-7f1d-44c3-be29-7846a4bf2e8f.png)

test组的新闻数据

![image](https://user-images.githubusercontent.com/77714764/189094517-c9c11cc0-1367-4e1a-93a4-12913e1beb04.png)

最高pv的新闻是一样的，但是test组中对于这条消息的展现和点击更多，ctr更高。这也是最后test组ctr更高的原因（test的用户对于图文新闻的点击热情更高）

**test组中喜欢图文和视频的新闻数据比较**

-喜好图文分组的最终新闻数据

![image](https://user-images.githubusercontent.com/77714764/189095296-ab9e3133-eb56-4e13-8d7f-302f88b6852a.png)

-喜好视频分组的最终新闻数据

![image](https://user-images.githubusercontent.com/77714764/189095508-b1cdcf91-eb24-46ea-a1e1-2a91a7e38300.png)

细分test组，可以发现图文组对于这条图文的点击率很高，而视频组点击率低于一般情况，因此图文组点击率高是test组点击率高的重要原因

### 时间: 2022-09-08 15:32:13，push_id: 220908-03

- 内容： 小视频
- test相对于base点击上升36.7%，ctr上升35.7%
- 单一视频内容，test多选出了优质的视频新闻

**base和test比较**

![image](https://user-images.githubusercontent.com/77714764/189099688-bc247141-2444-47bd-ab00-d9f8bdd24d95.png)

base组的新闻数据

![image](https://user-images.githubusercontent.com/77714764/189099951-7e26440c-cf9c-44b6-a73f-f16c3e118e10.png)

test组的新闻数据

![image](https://user-images.githubusercontent.com/77714764/189100071-4f34386e-7a3b-41a7-bd85-23ac951d1d9b.png)


可以发现base中只有一条两万pv的新闻但是test中多选出了一条，并且test组中的高pv新闻对于了更高的点击，因此最后的点击率跟base拉开差距。可能因为在base的分组中选出了更好的视频内容

**test组中喜欢图文和视频分组的新闻数据比较**

喜欢图文分组

![image](https://user-images.githubusercontent.com/77714764/189100692-951de8ab-c62e-4b6a-857d-82a8fb648ed5.png)

喜欢图文的分组选出了另一条视频新闻

喜欢视频分组

![image](https://user-images.githubusercontent.com/77714764/189101122-21ed4123-91ce-46c6-ab2a-704badf80ec9.png)

视频分组中虽然选出了跟base一样的新闻，但是点击率明显更高。

可以发现喜欢图文分组对于视频有跟视频分组不一样的重点

### 时间: 2022-09-08 17:32:40,push_id: 220908-04

- 内容： 小视频
- test相对于base点击下降17.3%，ctr下降16.6%
- 单一视频内容，test多选出了优质的视频新闻

**base和test比较**

![image](https://user-images.githubusercontent.com/77714764/189115850-d09e71af-8a79-4183-972e-5ddf61e5743e.png)

base组的新闻数据

![image](https://user-images.githubusercontent.com/77714764/189115459-437118c9-089d-4986-a1fc-1d8f59901231.png)

test组的新闻数据

![image](https://user-images.githubusercontent.com/77714764/189115742-fa766413-bfb5-4a5f-8152-6eaeffb08fc7.png)


可以发现base中只有一条一万以上pv的新闻但是test中三条数据都是几千展现，并且test组中的ctr不高，因此最后的点击率跟base有差距。可能因为在test的分组中未能选出更好的视频内容

**test组中喜欢图文和视频分组的新闻数据比较**

喜欢图文分组

![image](https://user-images.githubusercontent.com/77714764/189117700-e3aa0445-66c7-40d3-8cdf-d1b80f5795f9.png)

喜欢图文的分组选出了另外两条多余的视频新闻

喜欢视频分组

![image](https://user-images.githubusercontent.com/77714764/189118079-bcec6e97-7238-424d-a8a7-45d9075c2028.png)

视频分组中虽然选出了跟base一样的新闻，但是点击率明显更高。 

可以发现喜欢图文分组对于视频有跟视频分组不一样的重点,对于单一视频内容是导致ctr变化的重要原因


## 总结

- 对于混合内容效果差、对于单一内容有效果
- 对于数据量少的时候，效果差
- 第一次推送差的原因可能是不能精准推送，没有把视频推给喜欢视频的，没有把图文推给喜欢图文的

## 按照用户历史点击的新闻标签分组

***
### 将用户分成了社会、娱乐、国际三组

如果是图文统计tag_y1,如果是视频统计tag_vc 都记为tag，分成娱乐、社会、国际三组，取四周的数据，一共939w，分成三组娱乐 227w 社会 525w 国际 166w

![1664183387547](https://user-images.githubusercontent.com/77714764/192238509-de862ffb-09f6-43e5-9c01-b8e1caf936f4.jpg)

结果波动明显，上涨不明显

### 原因 

- 社会组的特征不明显，社会新闻范围太大
- 国际组的人数较少，可能不置信

### 修改

-去掉社会组
-扩充三组的人数，尽量均衡

波动较大是因为选出了和高热不同的数据，但是不如高热点击量大
### 修改前

***
### base和test两组实时ctr的变化


### 修改后

![image](https://user-images.githubusercontent.com/77714764/192495997-4802c2ea-5006-4607-97af-48eb7472d807.png)

整体出现下滑的波动，分组选出了不同的新闻但是点击的热情不够

### base和test两组实时ctr的变化

push_id: 220927-01|4

![image](https://user-images.githubusercontent.com/77714764/192496562-cb2a83f2-555a-40a1-849a-177430e74d58.png)

push_id: 220927-02

![image](https://user-images.githubusercontent.com/77714764/192496736-2171b9cc-ea14-40fc-82ae-ec0377d85f6c.png)

push_id: 220927-03

![image](https://user-images.githubusercontent.com/77714764/192496917-5893ec2d-d4e3-423e-b5ec-95daf70dae17.png)

push_id: 220927-04

![image](https://user-images.githubusercontent.com/77714764/192495846-2652b82e-b3ec-4ecc-8ceb-c96244ae2f3d.png)

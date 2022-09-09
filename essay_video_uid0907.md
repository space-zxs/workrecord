# 按图文和视频喜好分组实验记录

## 0907实验第一天
***
* ### ctr一天的整体变化
  >![image](https://user-images.githubusercontent.com/77714764/189296511-b5882ae1-5db4-42dc-9bee-934e05444dcd.png)
***
* ### 时间: 2022-09-07 09:31:34,push_id: 220907-01

  >内容：图文和视频

  >第一次push, test相较于base降低1.5%左右,ctr相对下降百分之40

  >![image](https://user-images.githubusercontent.com/77714764/189296695-436fbf31-596b-422d-af24-39a3cb22a9b9.png)

  > ### 原因
  > 两个组的pv相差不多，但是test组的点击比base组的点击减少了两千五左右的点击，下降了百分之四十。
    >>base组的新闻ctr数据

    >>>![image](https://user-images.githubusercontent.com/77714764/189296915-59215026-2b44-475e-a70e-5767d9b26f81.png)

    >>test组的新闻ctr数据

    >>>![image](https://user-images.githubusercontent.com/77714764/189296990-4ce1a4ab-340b-44f8-9c49-32c053b94f13.png)
    
    >>random探测的新闻ctr数据

    >>>![image](https://user-images.githubusercontent.com/77714764/189297040-c360e598-58fd-43ce-a054-4ee6ea88120c.png)
    
  > 1.test组的点击明显比base组少很多，对于MD5=99ede26a808c8b9d31ab4feea22acafc，这条新闻，在base中属于高热数据，pv和click都很多，但是在test中没有被探测成高热数据只有五千的pv。

  > 2.base组中高pv的99ede26a808c8b9d31ab4feea22acafc、ca21280fddffa44093a5d60574de3c05、98fc464e8997a414a83f259ff4d05d5a、396c858f144bd8877cb620f4a70e1cda 的四条新闻有两条视频、两条图文。
  但是test组的高pv的0ce37045b1f23dd945fa84d00243519f、fb4556ca457ee8e8c52f7a33e5f8fd60、fa42e9e12024eb1a61dbf83391f1c663、265fcac35fe62c00da19cc6fa968c511的四条新闻全是视频类

  >base和test探测出的高pv新闻差异明显只有一条一样，base的探测的数据和random更相似,test选出的高pv数据效果差

  > test中喜好看图文分组的探测数据

  >>![image](https://user-images.githubusercontent.com/77714764/189297163-c8d45b6c-daa8-437a-9611-960f5c5b4896.png)

  > test中喜好看视频的分组的探测数据

  >>![image](https://user-images.githubusercontent.com/77714764/189297210-1de5d762-b6ca-461a-a2fc-cdd10fb3d3cd.png)

  >>喜好看图文的分组里面全是视频，喜好看视频分组里面也有图文高于视频的新闻

  > base中喜好看图文分组的探测数据

  >>![image](https://user-images.githubusercontent.com/77714764/189297254-e309998d-2d71-4813-9641-d329cbd8f0a5.png)

  > base中喜好看视频的分组的探测数据

   >>![image](https://user-images.githubusercontent.com/77714764/189297288-fa5b27ae-18ae-479f-b140-ea3b40838500.png)
***
* ### 时间: 2022-09-07 11:31:44,push_id: 220907-02
    >内容：图文
    >第二次push, test相较于base提高0.9%左右,ctr相对上升百分之12%
    >![image](https://user-images.githubusercontent.com/77714764/189297370-d84a78db-b98b-41a5-95f3-1b7af870c2d5.png)

    > ### 原因
    > pv不变的情况下，点击出现13%的增长

    >>base组的新闻ctr数据

    >>>![image](https://user-images.githubusercontent.com/77714764/189297417-d4452a86-0bf6-4591-b2a0-871332419b25.png)

    >>test组的新闻ctr数据

    >>>![image](https://user-images.githubusercontent.com/77714764/189297449-0a4bf765-8114-4065-8479-aa0d923e6301.png)

    >>random探测的新闻ctr数据

    >>>![image](https://user-images.githubusercontent.com/77714764/189297488-cfdd8aa7-cfe2-4857-a7cf-fb0067b350bf.png)

    >>两组探测出的高热新闻各自有一条不一样，test组探测的高热数据点击率更高。

    > test中喜好看图文分组的探测数据

    >>![image](https://user-images.githubusercontent.com/77714764/189297535-b19b5475-25f8-4243-8a70-acc755903d0c.png)
      
    > test中喜好看视频分组的探测数据

    >>![image](https://user-images.githubusercontent.com/77714764/189297596-c4a420ce-c131-4af4-a1f3-b1ad05099100.png)

    >>可以看出喜欢看图文分组对图文消息的点击率更高

    > base中喜好看图文分组的探测数据

    >>![image](https://user-images.githubusercontent.com/77714764/189297626-876f46af-2136-4185-8c93-f70a556137eb.png)
      
    > bsae中喜好看视频分组的探测数据

    >>![image](https://user-images.githubusercontent.com/77714764/189297667-8769f96d-4bff-4843-b487-ce9762adafc0.png)
***
* ### 时间: 2022-09-07 15:32:19,push_id: 220907-03
    >内容：小视频

    >第三次push, test相较于base的点击提高9.6%左右,ctr相对上升百分之10%

    >![image](https://user-images.githubusercontent.com/77714764/189297730-c91311d6-a7a4-4fca-9a0d-9de759d0cbd5.png)

    > ### 原因
    > pv不变的情况下，点击出现10%的增长

    >>base组的新闻ctr数据

    >>![image](https://user-images.githubusercontent.com/77714764/189297812-a2dc0bf2-9929-4c47-90a7-65fa12c9e385.png)

    >>test组的新闻ctr数据

    >>![image](https://user-images.githubusercontent.com/77714764/189297862-bcfea56a-ae2b-4eb6-90d0-56a37b6c12ac.png)

    >>random探测的新闻ctr数据

    >>>![image](https://user-images.githubusercontent.com/77714764/189297921-82edf6ce-710b-41a9-9b2c-a79f49a25ef3.png)

    >>两组探测出的数据前两条是一样的，但是对于test组对视频的点击率更高

    > test中喜好看图文分组的探测数据

    >>![image](https://user-images.githubusercontent.com/77714764/189297965-7bff594e-272d-49f6-b860-50e3399695e0.png)
      
    > test中喜好看视频分组的探测数据

    >>![image](https://user-images.githubusercontent.com/77714764/189298020-b2b15edf-92d4-476e-91eb-e011ad64adec.png)

    >结论

    > base中喜好看图文分组的探测数据

    >>![image](https://user-images.githubusercontent.com/77714764/189298112-a0baef2c-d4fe-43d9-9be1-8d31f3121592.png)
      
    > base中喜好看视频分组的探测数据

    >>![image](https://user-images.githubusercontent.com/77714764/189298152-4c576a00-8df4-4adb-b66d-10aa8b659efe.png)

***
* ### 时间: 2022-09-07 17:32:22,push_id: 220907-04
    >内容：小视频
    
    >第四次push，test相较于base的点击下降0.36%左右,ctr相对下降百分之0.09%
    
    >![image](https://user-images.githubusercontent.com/77714764/189298207-6e6b7769-a6b4-4932-bc27-751c18ca40ff.png)
    
    > ### 原因
    >pv不变情况下，出现了接近百分之一的下降
    
    >>base组的新闻ctr数据

    >>>![image](https://user-images.githubusercontent.com/77714764/189298265-806a09eb-408d-4fb8-becd-ba37ad6bb59f.png)

    >>test组的新闻ctr数据

    >>>![image](https://user-images.githubusercontent.com/77714764/189298308-c12a0cae-216b-4c3c-93b0-01d222aa397a.png)
    
    >>random探测的新闻ctr数据

    >>>![image](https://user-images.githubusercontent.com/77714764/189298340-333e69fe-7142-4ed4-8c33-9595af79d2a4.png)

    >>两个组探测出的数据不一样,test比base多产生一条数据

    > test中喜好看图文分组的探测数据

    >>![image](https://user-images.githubusercontent.com/77714764/189298385-efb0e9c7-013f-4391-8a0a-35701112aa59.png)
      
    > test中喜好看视频分组的探测数据

    >>![image](https://user-images.githubusercontent.com/77714764/189298420-079c9d69-87af-473f-98d8-1d33d9e592d1.png)

    >>可以发现多出的一条探测数据是喜欢video的一组产生的，base只探测出一条数据

    > base中喜好看图文分组的探测数据

    >>![image](https://user-images.githubusercontent.com/77714764/189298492-5f40deab-7889-4905-8358-dbc041d1f39a.png)
      
    > base中喜好看视频分组的探测数据

    >>![image](https://user-images.githubusercontent.com/77714764/189298530-cbd10ede-dc0c-46e5-a42d-0124c96a5081.png)

***

***

clickhouse中数据的展现量比邮件中少一部分导致两者计算出来的ctr不相同

混合内容、单一内容、推送的人数是有影响的




  


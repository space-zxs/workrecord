# pictorial
***
## rocket_recall 召回服务
***
### 执行流程
start_plugin->parse_plugin->topctr_plugin/profile_plugin/icf_plugin->end_plugin

高热召回、cf召回

高热：

static_manual_recall,live_manual_recall,static_click_topctr_recall,live_click_topctr_recall,live_use_topctr_recall,static_use_topctr_recall,live_preview_topctr_recall,

用户标签的召回：

live_tag_profile_recall,static_tag_profile_recall,

item cf 召回：

live_icf_recall,static_icf_recall

### startplugin

初始化上下文结构，初始化消重服务

### praseplugin

解析用户信息、历史点击和历史展现

### topctr_plugin

disk_list.h:

DoubleBuffer

### 编译执行

make / make package

transfer_pd2.py 传输协议

返回几种召回的壁纸id列表，preview、tag_profile、usetop 

### 两个工具类

- 取list中数据（值）
- 取dict中数据（键值对）

线下hubao_offline 提供数据

对取到的数据列表进行消重。然后在task中消重存放到payload中

online_api_test()

http://papi.look.360.cn/mlist?crec=0&u=mytestuid_1232134e23423&hsid=lzs202209091628&sqid=&sign=360_190fb446&version=1.0&market=pc_def&device=2&v=1&sv=7&c=hb2&net=5&ufrom=1&n=18&scene=2&sub_scene=1&refer_scene=0&refer_subscene=0&f=json&where=list&action=1&rec_v=2

服务打包成的api,测试服务是否返回正常数据

static_manual_dict 

如何保证用户连续数据的消重

list 直接全部取出
icf_dict 

数据是 新闻id 和 dupid 拼接

request_id



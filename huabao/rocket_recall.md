# pictorial
***
## rocket_recall 召回服务

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

返回几种召回的壁纸id列表，preview、topctr、usetop

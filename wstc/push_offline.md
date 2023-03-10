# push_offline 线下

## select_top.py 
从输入中解析MD5 md5, pv, clk, ctr, s 等信息 分类存储
保存 图文和视频各自的新闻
    save_detail('wstc_xxl_top_news.t', md5_ytag_dict)
    save_detail('wstc_xxl_top_news.v', md5_vctag_dict)
    到redis

## update_safe_qid.py

更新胫骨审核的安全的qid到 safe_qid_list

## news_sync.py

得到审核通过的内容： news_safe_wstc、video_safe_wstc  

video_safe_wstc 由不同的类型 比如娱乐 国际等新闻，这些新闻数据 存储在redis 的不同的 队列中

最后按时间对 video_safe_wstc 进行排序

## load_yunying

wstc_conn.set('default_url_wstc', default_url_wstc)
 wstc_conn.set('template_url_wstc', template_url_wstc)
 
## make_random.py

生成random_list、default_list, defaul_list 是编辑配置的兜底数据  random_list 使用审核通过的内容

## hctr.py

获取random 探测的全局ctr 以及  各个分组探测的分组ctr


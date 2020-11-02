# 1. pycharm关闭拼写检查   
打开pycharm，点击[File]->[Settings]，在出现如的界面中选中[Inspections]，取消[Spelling]即可
# python的datetime库
'''  
curr_time = datetime.datetime.now()　　# 2019-07-06 14:55:56.873893 <class 'datetime.datetime'>
curr_time.year　　# 2019 <class 'int'>
curr_time.month　　# 7 <class 'int'>
curr_time.day　　# 6 <class 'int'>
curr_time.hour　　# 14 <class 'int'>
curr_time.minute　　# 55 <class 'int'>
curr_time.second　　# 56 <class 'int'>
curr_time.date()　　# 2019-07-06 <class 'datetime.date'>
time_str = datetime.datetime.strftime(curr_time,'%Y-%m-%d %H:%M:%S')　　# 2019-07-06 15:50:12
str-->datetime
time_str = '2019-07-06 15:59:58'
curr_time = datetime.datetime.strptime(time_str,'%Y-%m-%d %H:%M:%S')  
'''  

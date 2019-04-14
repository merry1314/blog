# 问题记录与笔记整理  作者：筑梦之路  email:434754018@qq.com

# Python3 问题
1.python3 matplotlib 画图 中文显示问题：中文显示为方块； （windows系统）  
解决办法：  
找到matplotlibrc 添加这两行  
font.serif	         : simhei.ttf  
font.sans-serif      : simhei.ttf  
找到这个字体复制到Lib\site-packages\matplotlib\mpl-data\fonts\ttf目录下  
在代码中添加：  
plt.rcParams['font.sans-serif'] = ['simhei']  
plt.rcParams['axes.unicode_minus'] = False  


# 计算机科学与编程入门课程第二次作业  
# 1900012800 胡一淳  
## 1.作业1  
[homework1][1]  
词频统计图

如何利用段落词频衡量人物间关系的紧密程度是一个值得思考的问题。 

一种直观而有效的判断方法：若两个人物频繁在某些小段内同时出现，那么必然这二者间关系紧密。
于是衡量人物间关系大致分为以下步骤。 

文章分段：定义上述的“小段”为一个自然段。使用字符串的split函数，以“\n” 为分割标志，
对原文进行分割得到若干小段。 

维护人物关系矩阵：矩阵初始为全0矩阵。在每一段中，两两枚举不同人物x与y，若同时出现在该段内，则relationships[x][y]增加1。 

关系网可视化：使用pyecharts库的Graph模式，将节点名称设为人物名，节点大小设置为3×log（count_name+1）

## .作业2  
[homework2][2]  
地理连线图  
胡一淳绕着五个城市飞行，最终化成了五角星，表达内心的赤诚爱国情


## .作业3
[homework3.1][3]  
中国地图：2020年各地房价  
[homework3.2][4]  
世界地图：2008年金牌榜前10

## .作业4
[homework4][5]  
组合图表  
某公司在2016至2020年市场持续扩张，该图反映了该公司在全国各地的扩张情况、同当地人口差异的对比，以及以扇形图的方式体现占据主体的城市。

[1]:https://mogician233.github.io/relation.html
[2]:https://mogician233.github.io/geo_line_star.html
[3]:https://mogician233.github.io/%E5%90%84%E7%9C%81%E7%9C%81%E4%BC%9A%E5%9F%8E%E5%B8%82%E6%88%BF%E4%BB%B7%E6%95%B0%E6%8D%AE%E5%9C%B0%E5%9B%BE_map.html
[4]:https://mogician233.github.io/Beijing2008.html
[5]:https://mogician233.github.io/MarketExpand.html

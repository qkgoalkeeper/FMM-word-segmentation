# 一.运行环境

用anaconda的Jupiter lab或者Jupiter notebook直接运行即可，主要代码的首行都写有该段代码的注释，按照顺序一步步执行即可。



# 二.操作步骤

## 1.获取数据并预处理

先读取dict存入dic列表，对应以下代码

![](https://github.com/qkgoalkeeper/FMM-word-segmentation/blob/master/截图/1.PNG)

再同理读取文章存入sentence列表，对应以下代码

![](https://github.com/qkgoalkeeper/FMM-word-segmentation/blob/master/截图/2.PNG)



可以直接查看dic和sentence列表内容



## 2.最大匹配法

用最大匹配法分句，对应以下代码

![](https://github.com/qkgoalkeeper/FMM-word-segmentation/blob/master/截图/3.PNG)

然后可以得到corpus.out.txt的结果

![](https://github.com/qkgoalkeeper/FMM-word-segmentation/blob/master/截图/9.PNG)



## 3.分词算法评价

先读取要比较的两个文件，对应以下代码

![](https://github.com/qkgoalkeeper/FMM-word-segmentation/blob/master/截图/4.PNG)

初始化全局三个变量，对应以下代码

![](https://github.com/qkgoalkeeper/FMM-word-segmentation/blob/master/截图/5.PNG)

用双指针法计算每行相同个数，对应以下代码

![](https://github.com/qkgoalkeeper/FMM-word-segmentation/blob/master/截图/6.PNG)

输出PRF的答案并存储到corpus.prf.txt中，代码和结果如下

![](https://github.com/qkgoalkeeper/FMM-word-segmentation/blob/master/截图/6.5.PNG)

![](https://github.com/qkgoalkeeper/FMM-word-segmentation/blob/master/截图/8.PNG)

最后计算总的200行prf的值并输出，对应以下代码

![](https://github.com/qkgoalkeeper/FMM-word-segmentation/blob/master/截图/7.PNG)

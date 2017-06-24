#demo4

##混合强调样式

基本强调样式：  
*倾斜*  
**加粗**  
***斜体加粗***  
~~删除线~~  
~~删除线的样式~~  

**~~加粗删除~~**  
*~~倾斜删除~~*  
***~~加粗倾斜删除~~***  


##图片链接

基本文字链接：  

	[链接的文字]（URL）
	
[baidu](http://www.baidu.com)  


基本图片链接：  
	![alt](URL txt)  
	
![百度网](https://www.baidu.com/img/bd_logo1.png "百度网站")  
![](https://www.baidu.com/img/bd_logo1.png )  
注：这里的方括号和txt都可以不要
	


图片链接：  
[![百度网](https://www.baidu.com/img/bd_logo1.png "百度网站")  ](http://www.baidu.com) 

这样写太复杂，可以简化

[![][baidu_logo]][baidu]



##多级列表
问题1：如何打断多级列表？
回答：光加空格没用，要在空格上架文字


1. item1  
	1. item 1.1  
	2. item 1.2  
2. item2 

aaaa
 
2. item3  
2. item4  

问题2：如何恢复被打断的多级列表，并且接着上一次的列表？
回答：把加上的文字空4格（缩进4格 ），让添加的文字成为上一行的段落。

1. item1  
	1. item 1.1  
	2. item 1.2  
2. item2 

    aaaa
 
2. item3  
2. item4  



<!-- 下面是网站的地址 -->

[baidu]: http://www.baidu.com
[baidu_logo]:https://www.baidu.com/img/bd_logo1.png


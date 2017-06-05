#Demo2


##链接  

###内嵌式链接  
- 外部链接：[百度](http://www.baidu.com)   
格式：[]()  即注释的说明+链接的地址  

- 内部链接1，链接仓库的其他文件：[demo1](README.md)  
- 内部链接2，链接文本的其他部分 :[代码块 demo](demo2.md#代码块-demo)   

###引用式链接  
- 外部链接：[百度]
- 外部链接： [百度][baidu]
- 内部链接1，链接仓库的其它文件：[demo1]
- 内部链接2，链接文本的其它地方：[代码块 demo]


##图片 demo 
- 图片的MarkDown语法  
    ![](URL txt)
外部图片，例子：  
![baidu](https://www.baidu.com/img/bd_logo1.png "百度网站") 
![爱因斯坦](https://imgsa.baidu.com/baike/c0%3Dbaike80%2C5%2C5%2C80%2C26/sign=9974a97c09f79052fb124f6c6d9abcaf/d009b3de9c82d158756f83de800a19d8bd3e42f4.jpg "爱因斯坦")

- 仓库内的图片  
![爱因斯坦](images/ayst.jpg "爱因斯坦")  
说明：方括号里面的内容可省略，后面小括号的提示内容是当鼠标放到图片上时显示的，也可不要。重点只要图片的地址和绝对路径。  


图片的引用式链接：  
外部图片，例子：  
![baidu](baidu_log) 
![爱因斯坦](爱因斯坦_图片)  


仓库内的图片：
![](ayst_jpg)




##引用 demo

> 这是一个引文  

	                     --出自《出处》  

多次引用：  
>>> 这是多重引文  

引用一次就加一个大于号  


##代码块 demo

- 行内代码
这个代码中用来声明的变量是`int a = 10; int b = 3;`,打印变量的内容是`a,b`.    


- 块式代码  

  
```c
int a = 10;  
int b = 3;  
printf("%d %d\n",a,b);
```





<!--  下面是文档中引用到的链接  -->
[百度]:(http://www.baidu.com)
[baidu]:(http://www.baidu.com)
[demo1]:(README.md)  
[代码块 demo]:(demo2.md#代码块-demo)  

[baidu_log]: (https://www.baidu.com/img/bd_logo1.png)
[爱因斯坦_图片]： （https://imgsa.baidu.com/baike/c0%3Dbaike80%2C5%2C5%2C80%2C26/sign=9974a97c09f79052fb124f6c6d9abcaf/d009b3de9c82d158756f83de800a19d8bd3e42f4.jpg)
[ayst_jpg]: (images/ayst.jpg)  

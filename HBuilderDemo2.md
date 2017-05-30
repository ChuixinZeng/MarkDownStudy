###HBuilderDemo2

##一、 链接  

### 内嵌式链接

- 外部链接,[百度](http://www.baidu.com)

- 内部链接1,链接仓库的其他文件：[Demo1](Demo1.md)

- 内部链接2,链接本文档的其他部分：[代码块](HBuilderDemo2.md#四、代码块)

### 引用式链接(推荐使用)  

- 外部链接[百度] 
- 外部链接[百度](baidu)
- 内部链接1,链接仓库的其他文件：[Demo1]
- 内部链接2,链接本文档的其他部分：[代码块]


## 二、图片  

### 图片的内嵌式链接

- 添加图片的语法格式  
    ![alt](url text)
- 外部图片 demo  
    ![baidu](https://www.baidu.com/img/bd_logo1.png "百度网站首页图片")  
- 仓库内部的图片 demo  
    ![](Images/test.jpg)#因为Web浏览器不是特别智能，所以图片未显示  
    ![](Images/test.jpg)#把jpg图片放到web浏览器图片所在目录下就看到了，地址是：C:\360安全浏览器下载\HBuilder_8.0.2_windows\HBuilder\configuration\org.eclipse.osgi\bundles\103\data\preview   
    
### 图片的引用式链接
    
- 外部图片 demo  
    ![baidu][baidu_logo]  
- 仓库内部的图片 demo  
    ![][open_jpg]


## 三、引用  

引用其他人说过的话语

> 这是一个引文。

出自《出处》

多重引用。  
>>> 这是多重引文。  


## 四、代码块  

- 行内代码  

这个代码中用来声明变量是`var a = 110`,打印变量内容是`console.log(a)`;

- 块式代码  

```javascript
var a = 110;
console.log(a);
#前面加了JavaScript标记，所以代码块的内容可以自动高亮
```

    #前面插入四个空格，也可以实现块式代码，但是不支持代码高亮，不能加语言标记
    var a = 110;
    console.log(a);


<!--- 下面是本文档中用到的链接-->

把引用的文档放到最后，作为引用式链接，在一个地方定义好，然后在别的地方引用它

[百度]: http://www.baidu.com
[baidu]: http://www.baidu.com
[Demo1]: Demo1.md
[代码块]: HBuilderDemo2.md#四、代码块

[baidu_logo]: https://www.baidu.com/img/bd_logo1.png  
[open_jpg]: Images/test.jpg  
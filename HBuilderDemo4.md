###HBuilderDemo4

## 混合强调样式

##### - 基本强调样式

- **加粗**
- *倾斜*
- ~~删除~~

##### - 混合强调样式

- ***加粗倾斜***
- **~~加粗删除~~**
- *~~倾斜删除~~*
- ***~~加粗倾斜删除~~***

## 图片链接

##### - 基本文字链接

[链接文字](url)

[百度](http://www.baidu.com)

##### - 基本图片

![](https://www.baidu.com/img/bd_logo1.png)

##### - 图片链接
[![](https://www.baidu.com/img/bd_logo1.png)](http://www.baidu.com)

##### - 图片链接（引用图片）

[![][baidu_logo]][baidu]

## 引用链接的问题

##### - 基本引用链接

- 好的写法

[baidu]

[百度][baidu]

[百度网站][baidu]

- low的写法（自引用）引用的地址如果和上面的一样的话，就是重复了

[百度]

[百度logo]

<!-- 以下是本文中可以引用的链接 -->

[baidu]: http://www.baidu.com
[baidu_logo]: https://www.baidu.com/img/bd_logo1.png
[百度]: http://www.baidu.com
[百度logo]: https://www.baidu.com/img/bd_logo1.png

## 多级列表问题

- item1
  - item 1.1
  - item 1.2
  - item 1.3
- item2
- item3

---

1. item1
  1. item 1.1
  2. item 1.2
  3. item 1.3
2. item2
3. item3

---

- 在列表项目之间插入文字，就可以打断多级列表

1. item1
  1. item 1.1
  2. item 1.2
  3. item 1.3
  
  
  打断多级列表
  
  
2. item2
3. item3

- 问题1：如何打断：空行不行，需要文字段落
- 问题2：打断的列表如何续上？把插入的打断文字缩进

1. item1
  1. item 1.1
  2. item 1.2
  3. item 1.3
  
  
     续上多级列表
  
  
2. item2
3. item3

---






